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

Total: 364

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Ubuntu 20.04                 | 49        | 18.35%  |
| Ubuntu 18.04                 | 18        | 6.74%   |
| Debian 11                    | 8         | 3%      |
| Ubuntu 22.04                 | 7         | 2.62%   |
| Pop!_OS 21.04                | 7         | 2.62%   |
| OpenMandriva 4.3             | 7         | 2.62%   |
| Pop!_OS 20.04                | 6         | 2.25%   |
| Ubuntu 19.04                 | 5         | 1.87%   |
| Fedora 36                    | 5         | 1.87%   |
| Fedora 35                    | 5         | 1.87%   |
| Ubuntu 21.04                 | 4         | 1.5%    |
| Pop!_OS 20.10                | 4         | 1.5%    |
| Linux Mint 20.2              | 4         | 1.5%    |
| KDE neon 20.04               | 4         | 1.5%    |
| Endless 3.7.8                | 4         | 1.5%    |
| Zorin 16                     | 3         | 1.12%   |
| Zorin 15                     | 3         | 1.12%   |
| Ubuntu 20.10                 | 3         | 1.12%   |
| Ubuntu 19.10                 | 3         | 1.12%   |
| Ubuntu 18.10                 | 3         | 1.12%   |
| ROSA R10                     | 3         | 1.12%   |
| Pop!_OS 21.10                | 3         | 1.12%   |
| OpenMandriva 4.2             | 3         | 1.12%   |
| Linux Mint 20.3              | 3         | 1.12%   |
| Endless 3.9.5                | 3         | 1.12%   |
| Endless 3.9.4                | 3         | 1.12%   |
| Arch Rolling                 | 3         | 1.12%   |
| Arch                         | 3         | 1.12%   |
| Ubuntu 21.10                 | 2         | 0.75%   |
| Pop!_OS 22.04                | 2         | 0.75%   |
| Manjaro 21.0.7               | 2         | 0.75%   |
| Manjaro 21.0                 | 2         | 0.75%   |
| Manjaro 20.2.1               | 2         | 0.75%   |
| Manjaro 20.2                 | 2         | 0.75%   |
| Manjaro 20.1.2               | 2         | 0.75%   |
| Manjaro 18.1.5               | 2         | 0.75%   |
| Linux Mint 20                | 2         | 0.75%   |
| Linux Mint 19.3              | 2         | 0.75%   |
| Kubuntu 21.04                | 2         | 0.75%   |
| Kubuntu 20.04                | 2         | 0.75%   |
| Fedora 34                    | 2         | 0.75%   |
| Fedora 33                    | 2         | 0.75%   |
| Endless 3.9.3                | 2         | 0.75%   |
| Endless 3.8.3                | 2         | 0.75%   |
| Debian 10                    | 2         | 0.75%   |
| ArcoLinux Rolling            | 2         | 0.75%   |
| Xubuntu 18.04                | 1         | 0.37%   |
| Ubuntu MATE 20.04            | 1         | 0.37%   |
| Ubuntu MATE 18.04            | 1         | 0.37%   |
| Ubuntu Budgie 20.04          | 1         | 0.37%   |
| ROSA R9                      | 1         | 0.37%   |
| ROSA R8.1                    | 1         | 0.37%   |
| ROSA R8                      | 1         | 0.37%   |
| Parrot 4.9                   | 1         | 0.37%   |
| Parrot 4.8                   | 1         | 0.37%   |
| openSUSE Tumbleweed-XXXXXXXX | 1         | 0.37%   |
| openSUSE Leap-15.1           | 1         | 0.37%   |
| OpenMandriva 4.50            | 1         | 0.37%   |
| Manjaro 21.3.6               | 1         | 0.37%   |
| Manjaro 21.2.5               | 1         | 0.37%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 84        | 35.29%  |
| Pop!_OS       | 21        | 8.82%   |
| Endless       | 21        | 8.82%   |
| Linux Mint    | 15        | 6.3%    |
| Fedora        | 15        | 6.3%    |
| Manjaro       | 13        | 5.46%   |
| OpenMandriva  | 11        | 4.62%   |
| Debian        | 10        | 4.2%    |
| Kubuntu       | 7         | 2.94%   |
| Zorin         | 6         | 2.52%   |
| ROSA          | 6         | 2.52%   |
| Arch          | 6         | 2.52%   |
| KDE neon      | 4         | 1.68%   |
| Ubuntu MATE   | 2         | 0.84%   |
| openSUSE      | 2         | 0.84%   |
| Kali          | 2         | 0.84%   |
| EndeavourOS   | 2         | 0.84%   |
| Elementary    | 2         | 0.84%   |
| ArcoLinux     | 2         | 0.84%   |
| Xubuntu       | 1         | 0.42%   |
| Ubuntu Budgie | 1         | 0.42%   |
| Parrot        | 1         | 0.42%   |
| LMDE          | 1         | 0.42%   |
| LinuxFX       | 1         | 0.42%   |
| Gentoo        | 1         | 0.42%   |
| CentOS        | 1         | 0.42%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 7         | 2.41%   |
| 5.8.0-14-generic                | 6         | 2.07%   |
| 5.11.0-38-generic               | 6         | 2.07%   |
| 5.4.0-42-generic                | 5         | 1.72%   |
| 5.11.0-7620-generic             | 5         | 1.72%   |
| 5.3.0-28-generic                | 4         | 1.38%   |
| 5.13.0-30-generic               | 4         | 1.38%   |
| 5.8.16-2-MANJARO                | 3         | 1.03%   |
| 5.8.0-7630-generic              | 3         | 1.03%   |
| 5.8.0-59-generic                | 3         | 1.03%   |
| 5.8.0-43-generic                | 3         | 1.03%   |
| 5.4.0-52-generic                | 3         | 1.03%   |
| 5.4.0-48-generic                | 3         | 1.03%   |
| 5.4.0-47-generic                | 3         | 1.03%   |
| 5.4.0-37-generic                | 3         | 1.03%   |
| 5.4.0-29-generic                | 3         | 1.03%   |
| 5.4.0-19-generic                | 3         | 1.03%   |
| 5.15.0-40-generic               | 3         | 1.03%   |
| 5.13.0-7620-generic             | 3         | 1.03%   |
| 5.13.0-52-generic               | 3         | 1.03%   |
| 5.11.0-41-generic               | 3         | 1.03%   |
| 5.11.0-40-generic               | 3         | 1.03%   |
| 5.10.14-desktop-1omv4002        | 3         | 1.03%   |
| 4.18.0-18-generic               | 3         | 1.03%   |
| 5.9.16-1-MANJARO                | 2         | 0.69%   |
| 5.8.0-49-generic                | 2         | 0.69%   |
| 5.8.0-48-generic                | 2         | 0.69%   |
| 5.4.0-91-generic                | 2         | 0.69%   |
| 5.4.0-84-generic                | 2         | 0.69%   |
| 5.4.0-7642-generic              | 2         | 0.69%   |
| 5.4.0-58-generic                | 2         | 0.69%   |
| 5.4.0-54-generic                | 2         | 0.69%   |
| 5.4.0-40-generic                | 2         | 0.69%   |
| 5.3.0-23-generic                | 2         | 0.69%   |
| 5.16.11-76051611-generic        | 2         | 0.69%   |
| 5.15.0-27-generic               | 2         | 0.69%   |
| 5.11.0-35-generic               | 2         | 0.69%   |
| 5.11.0-34-generic               | 2         | 0.69%   |
| 5.11.0-27-generic               | 2         | 0.69%   |
| 5.11.0-25-generic               | 2         | 0.69%   |
| 5.10.0-9-amd64                  | 2         | 0.69%   |
| 5.0.0-20-generic                | 2         | 0.69%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 2         | 0.69%   |
| 4.18.0-15-generic               | 2         | 0.69%   |
| 4.15.0-23-generic               | 2         | 0.69%   |
| 5.9.9-arch1-1                   | 1         | 0.34%   |
| 5.9.16-200.fc33.x86_64          | 1         | 0.34%   |
| 5.9.16-050916-generic           | 1         | 0.34%   |
| 5.9.11-arch2-1                  | 1         | 0.34%   |
| 5.9.11-3-MANJARO                | 1         | 0.34%   |
| 5.9.1-gentoo                    | 1         | 0.34%   |
| 5.8.6-1-MANJARO                 | 1         | 0.34%   |
| 5.8.0-7625-generic              | 1         | 0.34%   |
| 5.8.0-63-lowlatency             | 1         | 0.34%   |
| 5.8.0-63-generic                | 1         | 0.34%   |
| 5.8.0-51-generic                | 1         | 0.34%   |
| 5.8.0-31-generic                | 1         | 0.34%   |
| 5.7.11-arch1-1                  | 1         | 0.34%   |
| 5.6.6-300.fc32.x86_64           | 1         | 0.34%   |
| 5.6.2-050602-generic            | 1         | 0.34%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 50        | 18.32%  |
| 5.11.0  | 31        | 11.36%  |
| 5.8.0   | 20        | 7.33%   |
| 5.13.0  | 16        | 5.86%   |
| 4.15.0  | 15        | 5.49%   |
| 5.3.0   | 11        | 4.03%   |
| 5.15.0  | 10        | 3.66%   |
| 5.0.0   | 10        | 3.66%   |
| 4.18.0  | 10        | 3.66%   |
| 5.16.7  | 8         | 2.93%   |
| 5.10.0  | 8         | 2.93%   |
| 5.9.16  | 4         | 1.47%   |
| 5.8.16  | 3         | 1.1%    |
| 5.10.14 | 3         | 1.1%    |
| 4.9.60  | 3         | 1.1%    |
| 4.19.0  | 3         | 1.1%    |
| 5.9.11  | 2         | 0.73%   |
| 5.5.0   | 2         | 0.73%   |
| 5.16.11 | 2         | 0.73%   |
| 5.15.8  | 2         | 0.73%   |
| 5.14.0  | 2         | 0.73%   |
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
| 5.19.1  | 1         | 0.37%   |
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

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 53        | 19.78%  |
| 5.11    | 36        | 13.43%  |
| 5.8     | 24        | 8.96%   |
| 5.13    | 19        | 7.09%   |
| 5.10    | 16        | 5.97%   |
| 5.15    | 15        | 5.6%    |
| 4.15    | 15        | 5.6%    |
| 5.16    | 13        | 4.85%   |
| 5.3     | 12        | 4.48%   |
| 5.0     | 11        | 4.1%    |
| 4.18    | 10        | 3.73%   |
| 5.9     | 8         | 2.99%   |
| 5.17    | 5         | 1.87%   |
| 4.9     | 5         | 1.87%   |
| 5.6     | 4         | 1.49%   |
| 5.18    | 3         | 1.12%   |
| 5.14    | 3         | 1.12%   |
| 4.19    | 3         | 1.12%   |
| 5.5     | 2         | 0.75%   |
| 5.12    | 2         | 0.75%   |
| 5.7     | 1         | 0.37%   |
| 5.2     | 1         | 0.37%   |
| 5.19    | 1         | 0.37%   |
| 5.1     | 1         | 0.37%   |
| 4.17    | 1         | 0.37%   |
| 4.16    | 1         | 0.37%   |
| 4.12    | 1         | 0.37%   |
| 4.1     | 1         | 0.37%   |
| 3.10    | 1         | 0.37%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 226       | 97.84%  |
| i686   | 5         | 2.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 123       | 50%     |
| KDE5            | 35        | 14.23%  |
| Unknown         | 35        | 14.23%  |
| X-Cinnamon      | 10        | 4.07%   |
| XFCE            | 6         | 2.44%   |
| KDE             | 6         | 2.44%   |
| Cinnamon        | 6         | 2.44%   |
| MATE            | 5         | 2.03%   |
| KDE4            | 4         | 1.63%   |
| GNOME Flashback | 4         | 1.63%   |
| DWM             | 3         | 1.22%   |
| Unity           | 2         | 0.81%   |
| Pantheon        | 2         | 0.81%   |
| Budgie          | 2         | 0.81%   |
| LXQt            | 1         | 0.41%   |
| i3              | 1         | 0.41%   |
| bspwm           | 1         | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 187       | 75.1%   |
| Wayland | 32        | 12.85%  |
| Unknown | 27        | 10.84%  |
| Tty     | 3         | 1.2%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 117       | 49.16%  |
| GDM     | 48        | 20.17%  |
| SDDM    | 31        | 13.03%  |
| GDM3    | 16        | 6.72%   |
| LightDM | 12        | 5.04%   |
| TDM     | 10        | 4.2%    |
| KDM     | 3         | 1.26%   |
| Ly      | 1         | 0.42%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 123       | 51.46%  |
| hr_HR   | 57        | 23.85%  |
| Unknown | 38        | 15.9%   |
| en_GB   | 8         | 3.35%   |
| de_DE   | 6         | 2.51%   |
| C       | 4         | 1.67%   |
| hr_BA   | 1         | 0.42%   |
| fr_FR   | 1         | 0.42%   |
| en_DE   | 1         | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 143       | 59.83%  |
| BIOS | 96        | 40.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 186       | 77.82%  |
| Unknown | 16        | 6.69%   |
| Overlay | 14        | 5.86%   |
| Btrfs   | 12        | 5.02%   |
| Zfs     | 4         | 1.67%   |
| Xfs     | 4         | 1.67%   |
| Ext2    | 2         | 0.84%   |
| Jfs     | 1         | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 128       | 54.7%   |
| GPT     | 83        | 35.47%  |
| MBR     | 23        | 9.83%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 219       | 93.19%  |
| Yes       | 16        | 6.81%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 182       | 77.45%  |
| Yes       | 53        | 22.55%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 60        | 25.97%  |
| Hewlett-Packard         | 48        | 20.78%  |
| Acer                    | 40        | 17.32%  |
| ASUSTek Computer        | 28        | 12.12%  |
| Dell                    | 27        | 11.69%  |
| Toshiba                 | 6         | 2.6%    |
| Apple                   | 4         | 1.73%   |
| Samsung Electronics     | 3         | 1.3%    |
| eMachines               | 3         | 1.3%    |
| HUAWEI                  | 2         | 0.87%   |
| Fujitsu Siemens         | 2         | 0.87%   |
| TUXEDO                  | 1         | 0.43%   |
| System76                | 1         | 0.43%   |
| SHENZHEN X&F TECHNOLOGY | 1         | 0.43%   |
| Razer                   | 1         | 0.43%   |
| Notebook                | 1         | 0.43%   |
| Medion                  | 1         | 0.43%   |
| Gigabyte Technology     | 1         | 0.43%   |
| Chuwi                   | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Acer Aspire A315-21                        | 4         | 1.73%   |
| Lenovo G710 20252                          | 3         | 1.3%    |
| Acer Aspire A515-51G                       | 3         | 1.3%    |
| Lenovo Z50-70 20354                        | 2         | 0.87%   |
| Lenovo ThinkBook 16p Gen 2 20YM            | 2         | 0.87%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ           | 2         | 0.87%   |
| Lenovo G40-30 80FY                         | 2         | 0.87%   |
| HP ProBook 450 G7                          | 2         | 0.87%   |
| HP EliteBook 850 G6                        | 2         | 0.87%   |
| HP 2000                                    | 2         | 0.87%   |
| Fujitsu Siemens ESPRIMO Mobile V5535       | 2         | 0.87%   |
| Dell XPS 13 9310                           | 2         | 0.87%   |
| Dell Vostro 3500                           | 2         | 0.87%   |
| ASUS X751NV                                | 2         | 0.87%   |
| ASUS VivoBook 15_ASUS Laptop X560UD        | 2         | 0.87%   |
| ASUS VivoBook 15_ASUS Laptop X540BP        | 2         | 0.87%   |
| Acer Aspire E5-771G                        | 2         | 0.87%   |
| Acer Aspire A715-72G                       | 2         | 0.87%   |
| Acer Aspire 7739G                          | 2         | 0.87%   |
| TUXEDO Pulse 15 Gen1                       | 1         | 0.43%   |
| Toshiba Satellite P200                     | 1         | 0.43%   |
| Toshiba Satellite L750                     | 1         | 0.43%   |
| Toshiba Satellite L50-B                    | 1         | 0.43%   |
| Toshiba Satellite C850-1GD                 | 1         | 0.43%   |
| Toshiba Satellite C55-A-1M7                | 1         | 0.43%   |
| Toshiba Satellite A300                     | 1         | 0.43%   |
| System76 Oryx Pro                          | 1         | 0.43%   |
| SHENZHEN X&F TECHNOLOGY ST106              | 1         | 0.43%   |
| Samsung N150/N210/N220                     | 1         | 0.43%   |
| Samsung 300E4C/300E5C/300E7C               | 1         | 0.43%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.43%   |
| Razer Blade                                | 1         | 0.43%   |
| Notebook MAM2080                           | 1         | 0.43%   |
| Medion P6618                               | 1         | 0.43%   |
| Lenovo Y520-15IKBN 80WK                    | 1         | 0.43%   |
| Lenovo Y50-70 20378                        | 1         | 0.43%   |
| Lenovo V340-17IWL 81RG                     | 1         | 0.43%   |
| Lenovo ThinkPad X260 20F5S0JF00            | 1         | 0.43%   |
| Lenovo ThinkPad X240 20AMS30A01            | 1         | 0.43%   |
| Lenovo ThinkPad X1 Carbon 6th 20KH006JSC   | 1         | 0.43%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGSA3T00   | 1         | 0.43%   |
| Lenovo ThinkPad X1 Carbon 6th 20KGS7SE00   | 1         | 0.43%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR005YSC   | 1         | 0.43%   |
| Lenovo ThinkPad W540 20BHS04K00            | 1         | 0.43%   |
| Lenovo ThinkPad T61 6458AU9                | 1         | 0.43%   |
| Lenovo ThinkPad T580 20LAS27000            | 1         | 0.43%   |
| Lenovo ThinkPad T490s 20NXCTO1WW           | 1         | 0.43%   |
| Lenovo ThinkPad T480s 20L8S23300           | 1         | 0.43%   |
| Lenovo ThinkPad T460 20FMS0X022            | 1         | 0.43%   |
| Lenovo ThinkPad T450s 20BWS2US00           | 1         | 0.43%   |
| Lenovo ThinkPad T440p 20AWS1HK0P           | 1         | 0.43%   |
| Lenovo ThinkPad T440 20B7S14N0U            | 1         | 0.43%   |
| Lenovo ThinkPad T430 2349AK2               | 1         | 0.43%   |
| Lenovo ThinkPad T410 2522DK2               | 1         | 0.43%   |
| Lenovo ThinkPad T15 Gen 1 20S6000USC       | 1         | 0.43%   |
| Lenovo ThinkPad P53 20QNZ4RBUS             | 1         | 0.43%   |
| Lenovo ThinkPad P1 20MES1T700              | 1         | 0.43%   |
| Lenovo ThinkPad L15 Gen 1 20U70001SC       | 1         | 0.43%   |
| Lenovo ThinkPad E590 20NB006MSC            | 1         | 0.43%   |
| Lenovo ThinkPad E580 20KS005ASC            | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Acer Aspire                   | 35        | 15.15%  |
| Lenovo ThinkPad               | 27        | 11.69%  |
| HP ProBook                    | 10        | 4.33%   |
| HP EliteBook                  | 10        | 4.33%   |
| ASUS VivoBook                 | 8         | 3.46%   |
| HP Pavilion                   | 7         | 3.03%   |
| Dell XPS                      | 7         | 3.03%   |
| Dell Vostro                   | 7         | 3.03%   |
| Toshiba Satellite             | 6         | 2.6%    |
| Lenovo ThinkBook              | 6         | 2.6%    |
| Lenovo IdeaPad                | 6         | 2.6%    |
| Dell Latitude                 | 6         | 2.6%    |
| Lenovo Legion                 | 5         | 2.16%   |
| Dell Inspiron                 | 5         | 2.16%   |
| HP Laptop                     | 4         | 1.73%   |
| HP 250                        | 4         | 1.73%   |
| Lenovo G710                   | 3         | 1.3%    |
| HP Compaq                     | 3         | 1.3%    |
| Acer Swift                    | 3         | 1.3%    |
| Lenovo Z50-70                 | 2         | 0.87%   |
| Lenovo G40-30                 | 2         | 0.87%   |
| Lenovo B590                   | 2         | 0.87%   |
| HP OMEN                       | 2         | 0.87%   |
| HP 2000                       | 2         | 0.87%   |
| Fujitsu Siemens ESPRIMO       | 2         | 0.87%   |
| ASUS ZenBook                  | 2         | 0.87%   |
| ASUS X751NV                   | 2         | 0.87%   |
| ASUS ROG                      | 2         | 0.87%   |
| TUXEDO Pulse                  | 1         | 0.43%   |
| System76 Oryx                 | 1         | 0.43%   |
| SHENZHEN X&F TECHNOLOGY ST106 | 1         | 0.43%   |
| Samsung N150                  | 1         | 0.43%   |
| Samsung 300E4C                | 1         | 0.43%   |
| Samsung 300E4A                | 1         | 0.43%   |
| Razer Blade                   | 1         | 0.43%   |
| Notebook MAM2080              | 1         | 0.43%   |
| Medion P6618                  | 1         | 0.43%   |
| Lenovo Y520-15IKBN            | 1         | 0.43%   |
| Lenovo Y50-70                 | 1         | 0.43%   |
| Lenovo V340-17IWL             | 1         | 0.43%   |
| Lenovo G500                   | 1         | 0.43%   |
| Lenovo G50-45                 | 1         | 0.43%   |
| Lenovo G50-30                 | 1         | 0.43%   |
| Lenovo B50-70                 | 1         | 0.43%   |
| HUAWEI WRTB-WXX9              | 1         | 0.43%   |
| HUAWEI KLVL-WXX9              | 1         | 0.43%   |
| HP ZBook                      | 1         | 0.43%   |
| HP Presario                   | 1         | 0.43%   |
| HP Notebook                   | 1         | 0.43%   |
| HP 255                        | 1         | 0.43%   |
| HP 2140                       | 1         | 0.43%   |
| Gigabyte G5                   | 1         | 0.43%   |
| eMachines G725                | 1         | 0.43%   |
| eMachines E725                | 1         | 0.43%   |
| eMachines E525                | 1         | 0.43%   |
| Dell Precision                | 1         | 0.43%   |
| Dell G3                       | 1         | 0.43%   |
| Chuwi GemiBook                | 1         | 0.43%   |
| ASUS X75A1                    | 1         | 0.43%   |
| ASUS X71Sr                    | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2018 | 34        | 14.72%  |
| 2019 | 24        | 10.39%  |
| 2017 | 23        | 9.96%   |
| 2020 | 20        | 8.66%   |
| 2013 | 20        | 8.66%   |
| 2021 | 17        | 7.36%   |
| 2016 | 17        | 7.36%   |
| 2014 | 16        | 6.93%   |
| 2011 | 15        | 6.49%   |
| 2012 | 9         | 3.9%    |
| 2007 | 9         | 3.9%    |
| 2015 | 8         | 3.46%   |
| 2009 | 6         | 2.6%    |
| 2008 | 6         | 2.6%    |
| 2010 | 5         | 2.16%   |
| 2006 | 2         | 0.87%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 231       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 205       | 88.36%  |
| Enabled  | 27        | 11.64%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 231       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 79        | 33.47%  |
| 8.01-16.0   | 44        | 18.64%  |
| 3.01-4.0    | 42        | 17.8%   |
| 16.01-24.0  | 35        | 14.83%  |
| 32.01-64.0  | 16        | 6.78%   |
| 1.01-2.0    | 10        | 4.24%   |
| 24.01-32.0  | 5         | 2.12%   |
| 2.01-3.0    | 4         | 1.69%   |
| 64.01-256.0 | 1         | 0.42%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 95        | 35.58%  |
| 2.01-3.0   | 63        | 23.6%   |
| 4.01-8.0   | 44        | 16.48%  |
| 3.01-4.0   | 34        | 12.73%  |
| 0.51-1.0   | 15        | 5.62%   |
| 8.01-16.0  | 12        | 4.49%   |
| 16.01-24.0 | 2         | 0.75%   |
| 0.01-0.5   | 2         | 0.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 177       | 74.37%  |
| 2      | 51        | 21.43%  |
| 3      | 4         | 1.68%   |
| 0      | 3         | 1.26%   |
| 6      | 1         | 0.42%   |
| 5      | 1         | 0.42%   |
| 4      | 1         | 0.42%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 156       | 66.95%  |
| Yes       | 77        | 33.05%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 199       | 85.78%  |
| No        | 33        | 14.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 229       | 99.13%  |
| No        | 2         | 0.87%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 193       | 81.78%  |
| No        | 43        | 18.22%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Croatia | 231       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Zagreb              | 151       | 56.34%  |
| Split               | 12        | 4.48%   |
| Rijeka              | 12        | 4.48%   |
| Varaždin           | 6         | 2.24%   |
| Pula                | 5         | 1.87%   |
| Velika Gorica       | 4         | 1.49%   |
| Zaprešić          | 3         | 1.12%   |
| Jesenice            | 3         | 1.12%   |
| Čakovec            | 3         | 1.12%   |
| Rovinj              | 2         | 0.75%   |
| Petrinja            | 2         | 0.75%   |
| Osijek              | 2         | 0.75%   |
| Omiš               | 2         | 0.75%   |
| Novska              | 2         | 0.75%   |
| Krizevci            | 2         | 0.75%   |
| Komiža             | 2         | 0.75%   |
| Kastav              | 2         | 0.75%   |
| Bjelovar            | 2         | 0.75%   |
| Đakovo             | 1         | 0.37%   |
| Zminj               | 1         | 0.37%   |
| Zadar               | 1         | 0.37%   |
| Zabok               | 1         | 0.37%   |
| Virovitica          | 1         | 0.37%   |
| Vinkovci            | 1         | 0.37%   |
| Varazdinske Toplice | 1         | 0.37%   |
| Umag                | 1         | 0.37%   |
| Udbinja             | 1         | 0.37%   |
| Trenkovo            | 1         | 0.37%   |
| Sveti Ivan Zelina   | 1         | 0.37%   |
| Sveta Marija        | 1         | 0.37%   |
| Supetar             | 1         | 0.37%   |
| Sracinec            | 1         | 0.37%   |
| Šibenik            | 1         | 0.37%   |
| Sesvete             | 1         | 0.37%   |
| Senj                | 1         | 0.37%   |
| Samobor             | 1         | 0.37%   |
| Rokovci             | 1         | 0.37%   |
| Požega             | 1         | 0.37%   |
| Pitomaca            | 1         | 0.37%   |
| Otocac              | 1         | 0.37%   |
| Opuzen              | 1         | 0.37%   |
| Ogulin              | 1         | 0.37%   |
| Novo Cice           | 1         | 0.37%   |
| Našice             | 1         | 0.37%   |
| Medulin             | 1         | 0.37%   |
| Matulji             | 1         | 0.37%   |
| Mala Subotica       | 1         | 0.37%   |
| Labin               | 1         | 0.37%   |
| Krk                 | 1         | 0.37%   |
| Koprivnica          | 1         | 0.37%   |
| Klis                | 1         | 0.37%   |
| Kastel Stafilic     | 1         | 0.37%   |
| Karlovac            | 1         | 0.37%   |
| Jelsa               | 1         | 0.37%   |
| Hvar                | 1         | 0.37%   |
| Dugopolje           | 1         | 0.37%   |
| Donji Desinec       | 1         | 0.37%   |
| Dinjevac            | 1         | 0.37%   |
| Cret Bizovacki      | 1         | 0.37%   |
| Cres                | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Samsung Electronics   | 46        | 60     | 16.31%  |
| WDC                   | 37        | 46     | 13.12%  |
| Kingston              | 27        | 35     | 9.57%   |
| Seagate               | 24        | 46     | 8.51%   |
| SK hynix              | 21        | 32     | 7.45%   |
| Toshiba               | 19        | 20     | 6.74%   |
| SanDisk               | 18        | 23     | 6.38%   |
| Micron Technology     | 12        | 13     | 4.26%   |
| Intel                 | 8         | 14     | 2.84%   |
| Hitachi               | 8         | 8      | 2.84%   |
| HGST                  | 8         | 8      | 2.84%   |
| Unknown               | 7         | 7      | 2.48%   |
| Crucial               | 7         | 12     | 2.48%   |
| A-DATA Technology     | 5         | 5      | 1.77%   |
| Fujitsu               | 4         | 4      | 1.42%   |
| Apple                 | 4         | 4      | 1.42%   |
| LITEON                | 3         | 4      | 1.06%   |
| Transcend             | 2         | 3      | 0.71%   |
| Silicon Motion        | 2         | 3      | 0.71%   |
| Lenovo                | 2         | 3      | 0.71%   |
| KingFast              | 2         | 4      | 0.71%   |
| Intenso               | 2         | 3      | 0.71%   |
| Verbatim              | 1         | 1      | 0.35%   |
| UMIS                  | 1         | 1      | 0.35%   |
| StoreJet              | 1         | 1      | 0.35%   |
| Realtek Semiconductor | 1         | 3      | 0.35%   |
| Phison                | 1         | 1      | 0.35%   |
| Patriot               | 1         | 1      | 0.35%   |
| Netac                 | 1         | 1      | 0.35%   |
| Mass                  | 1         | 1      | 0.35%   |
| Lite-On               | 1         | 1      | 0.35%   |
| LaCie                 | 1         | 1      | 0.35%   |
| KIOXIA                | 1         | 1      | 0.35%   |
| Gigabyte Technology   | 1         | 1      | 0.35%   |
| Corsair               | 1         | 1      | 0.35%   |
| AMD                   | 1         | 3      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung NVMe SSD Drive 512GB            | 7         | 2.45%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD     | 6         | 2.1%    |
| SanDisk NVMe SSD Drive 512GB            | 5         | 1.75%   |
| Toshiba MQ01ABD100 1TB                  | 4         | 1.4%    |
| Kingston SA400S37240G 240GB SSD         | 4         | 1.4%    |
| SK hynix NVMe SSD Drive 256GB           | 3         | 1.05%   |
| Seagate ST500LT012-1DG142 500GB         | 3         | 1.05%   |
| Seagate ST1000LM035-1RK172 1TB          | 3         | 1.05%   |
| Seagate ST1000LM024 HN-M101MBB 1TB      | 3         | 1.05%   |
| Samsung SSD 850 EVO 250GB               | 3         | 1.05%   |
| Kingston SA400S37480G 480GB SSD         | 3         | 1.05%   |
| Kingston SA400S37120G 120GB SSD         | 3         | 1.05%   |
| Intel NVMe SSD Drive 256GB              | 3         | 1.05%   |
| HGST HTS721010A9E630 1TB                | 3         | 1.05%   |
| WDC WD5000LPCX-60VHAT0 500GB            | 2         | 0.7%    |
| WDC WD5000LPCX-24C6HT0 500GB            | 2         | 0.7%    |
| WDC WD1600BEVT-22ZCT0 160GB             | 2         | 0.7%    |
| WDC WD10SPZX-21Z10T0 1TB                | 2         | 0.7%    |
| WDC WD10JPVX-22JC3T0 1TB                | 2         | 0.7%    |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB      | 2         | 0.7%    |
| Unknown SD/MMC/MS PRO 128GB             | 2         | 0.7%    |
| Toshiba MQ04ABF100 1TB                  | 2         | 0.7%    |
| Toshiba MQ01ABF050 500GB                | 2         | 0.7%    |
| SK hynix NVMe SSD Drive 512GB           | 2         | 0.7%    |
| SK hynix HFS256G39TND-N210A 256GB SSD   | 2         | 0.7%    |
| SK hynix HFS128G39TND-N210A 128GB SSD   | 2         | 0.7%    |
| SK hynix HFM512GDJTNI-82A0A 512GB       | 2         | 0.7%    |
| SK hynix BC511 HFM256GDJTNI-82A0A 256GB | 2         | 0.7%    |
| Seagate ST9500325AS 500GB               | 2         | 0.7%    |
| Seagate ST2000LM007-1R8174 2TB          | 2         | 0.7%    |
| SanDisk SD8SN8U-256G-1006 256GB SSD     | 2         | 0.7%    |
| Samsung SSD 860 QVO 1TB                 | 2         | 0.7%    |
| Samsung PM9A1 NVMe 2048GB               | 2         | 0.7%    |
| Samsung PM981 NVMe 512GB                | 2         | 0.7%    |
| Samsung NVMe SSD Drive 256GB            | 2         | 0.7%    |
| Samsung MZNLN256HAJQ-000H1 256GB SSD    | 2         | 0.7%    |
| Samsung MZALQ512HALU-000L2 512GB        | 2         | 0.7%    |
| Micron 1100_MTFDDAV512TBN 512GB SSD     | 2         | 0.7%    |
| Micron 1100 SATA 256GB SSD              | 2         | 0.7%    |
| Kingston SV300S37A240G 240GB SSD        | 2         | 0.7%    |
| KingFast 256GB                          | 2         | 0.7%    |
| Intel SSDPEKNW512G8H 512GB              | 2         | 0.7%    |
| Hitachi HTS543232A7A384 320GB           | 2         | 0.7%    |
| HGST HTS541010A9E680 1TB                | 2         | 0.7%    |
| Crucial CT500MX500SSD1 500GB            | 2         | 0.7%    |
| Crucial CT240BX500SSD1 240GB            | 2         | 0.7%    |
| A-DATA SU650 240GB SSD                  | 2         | 0.7%    |
| A-DATA SU650 120GB SSD                  | 2         | 0.7%    |
| WDC WDS500G2B0A-00SM50 500GB SSD        | 1         | 0.35%   |
| WDC WDS250G2B0B-00YS70 250GB SSD        | 1         | 0.35%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD        | 1         | 0.35%   |
| WDC WDS100T2G0A-00JH30 1TB SSD          | 1         | 0.35%   |
| WDC WDS100T2B0C-00PXH0 1TB              | 1         | 0.35%   |
| WDC WDS100T2B0A-00SM50 1TB SSD          | 1         | 0.35%   |
| WDC WD800BEVS-08RST2 80GB               | 1         | 0.35%   |
| WDC WD7500BPVT-80HXZT1 752GB            | 1         | 0.35%   |
| WDC WD7500BPVT-08A1YT1 752GB            | 1         | 0.35%   |
| WDC WD600VE-75HDT0 64GB                 | 1         | 0.35%   |
| WDC WD5000LPCX-22VHAT0 500GB            | 1         | 0.35%   |
| WDC WD2500BEVT-22ZCT0 250GB             | 1         | 0.35%   |

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
| Kingston            | 23        | 27     | 23.47%  |
| Samsung Electronics | 17        | 25     | 17.35%  |
| SanDisk             | 10        | 14     | 10.2%   |
| Micron Technology   | 10        | 11     | 10.2%   |
| Crucial             | 7         | 12     | 7.14%   |
| SK hynix            | 6         | 11     | 6.12%   |
| WDC                 | 5         | 6      | 5.1%    |
| A-DATA Technology   | 5         | 5      | 5.1%    |
| Apple               | 4         | 4      | 4.08%   |
| LITEON              | 2         | 3      | 2.04%   |
| Transcend           | 1         | 2      | 1.02%   |
| Toshiba             | 1         | 1      | 1.02%   |
| StoreJet            | 1         | 1      | 1.02%   |
| Patriot             | 1         | 1      | 1.02%   |
| Netac               | 1         | 1      | 1.02%   |
| Intenso             | 1         | 1      | 1.02%   |
| Intel               | 1         | 2      | 1.02%   |
| Gigabyte Technology | 1         | 1      | 1.02%   |
| AMD                 | 1         | 3      | 1.02%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 90        | 131    | 33.46%  |
| HDD     | 85        | 106    | 31.6%   |
| NVMe    | 84        | 116    | 31.23%  |
| Unknown | 6         | 18     | 2.23%   |
| MMC     | 4         | 4      | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 156       | 230    | 61.66%  |
| NVMe | 84        | 116    | 33.2%   |
| SAS  | 9         | 25     | 3.56%   |
| MMC  | 4         | 4      | 1.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 120       | 163    | 67.8%   |
| 0.51-1.0   | 50        | 65     | 28.25%  |
| 1.01-2.0   | 7         | 9      | 3.95%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 80        | 32.92%  |
| 251-500        | 59        | 24.28%  |
| 501-1000       | 36        | 14.81%  |
| 1001-2000      | 23        | 9.47%   |
| 51-100         | 15        | 6.17%   |
| 1-20           | 12        | 4.94%   |
| 21-50          | 7         | 2.88%   |
| Unknown        | 7         | 2.88%   |
| More than 3000 | 2         | 0.82%   |
| 2001-3000      | 2         | 0.82%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 88        | 33.46%  |
| 21-50          | 61        | 23.19%  |
| 51-100         | 33        | 12.55%  |
| 101-250        | 30        | 11.41%  |
| 501-1000       | 20        | 7.6%    |
| 251-500        | 19        | 7.22%   |
| Unknown        | 7         | 2.66%   |
| 1001-2000      | 4         | 1.52%   |
| More than 3000 | 1         | 0.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 1      | 6.25%   |
| WDC WD600VE-75HDT0 64GB              | 1         | 1      | 6.25%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 1      | 6.25%   |
| Toshiba MK6459GSXP 640GB             | 1         | 1      | 6.25%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 6.25%   |
| Seagate ST9250827AS 250GB            | 1         | 1      | 6.25%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1      | 6.25%   |
| SanDisk SDSSDXPS960G 960GB           | 1         | 1      | 6.25%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD  | 1         | 1      | 6.25%   |
| LITEON LMH-256V2M-11 MSATA 256GB SSD | 1         | 1      | 6.25%   |
| Hitachi HTS542512K9SA00 120GB        | 1         | 1      | 6.25%   |
| HGST HTS721010A9E630 1TB             | 1         | 1      | 6.25%   |
| HGST HTS545050A7E380 500GB           | 1         | 1      | 6.25%   |
| HGST HTS541010A9E680 1TB             | 1         | 1      | 6.25%   |
| Crucial CT1024M550SSD1 1024GB        | 1         | 1      | 6.25%   |
| A-DATA Technology SU630 240GB SSD    | 1         | 1      | 6.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 3         | 3      | 20%     |
| Seagate           | 3         | 3      | 20%     |
| HGST              | 3         | 3      | 20%     |
| Toshiba           | 1         | 1      | 6.67%   |
| SanDisk           | 1         | 2      | 6.67%   |
| LITEON            | 1         | 1      | 6.67%   |
| Hitachi           | 1         | 1      | 6.67%   |
| Crucial           | 1         | 1      | 6.67%   |
| A-DATA Technology | 1         | 1      | 6.67%   |

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
| HDD  | 10        | 10     | 71.43%  |
| SSD  | 4         | 6      | 28.57%  |

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
| Detected | 143       | 226    | 58.37%  |
| Works    | 88        | 133    | 35.92%  |
| Malfunc  | 14        | 16     | 5.71%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 169       | 58.48%  |
| Samsung Electronics              | 30        | 10.38%  |
| AMD                              | 30        | 10.38%  |
| SK hynix                         | 15        | 5.19%   |
| SanDisk                          | 14        | 4.84%   |
| Toshiba America Info Systems     | 6         | 2.08%   |
| Kingston Technology Company      | 4         | 1.38%   |
| Silicon Motion                   | 2         | 0.69%   |
| Silicon Integrated Systems [SiS] | 2         | 0.69%   |
| Phison Electronics               | 2         | 0.69%   |
| Nvidia                           | 2         | 0.69%   |
| Micron Technology                | 2         | 0.69%   |
| Lite-On Technology               | 2         | 0.69%   |
| Lenovo                           | 2         | 0.69%   |
| KIOXIA                           | 2         | 0.69%   |
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
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 29        | 9.39%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 28        | 9.06%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 15        | 4.85%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 14        | 4.53%   |
| Samsung NVMe SSD Controller 980                                                  | 13        | 4.21%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 13        | 4.21%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 11        | 3.56%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 11        | 3.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 9         | 2.91%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 7         | 2.27%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 7         | 2.27%   |
| SK hynix Gold P31 SSD                                                            | 6         | 1.94%   |
| Intel Tiger Lake-LP SATA Controller                                              | 6         | 1.94%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 6         | 1.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 6         | 1.94%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 5         | 1.62%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 5         | 1.62%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 1.62%   |
| SK hynix BC511                                                                   | 4         | 1.29%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 4         | 1.29%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 4         | 1.29%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 1.29%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                             | 3         | 0.97%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                  | 3         | 0.97%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                          | 3         | 0.97%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 0.97%   |
| Intel Comet Lake SATA AHCI Controller                                            | 3         | 0.97%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 3         | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 0.97%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 3         | 0.97%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.65%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                    | 2         | 0.65%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 2         | 0.65%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 2         | 0.65%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 2         | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 2         | 0.65%   |
| Samsung Electronics SATA controller                                              | 2         | 0.65%   |
| Micron Non-Volatile memory controller                                            | 2         | 0.65%   |
| Lite-On Non-Volatile memory controller                                           | 2         | 0.65%   |
| Lenovo Non-Volatile memory controller                                            | 2         | 0.65%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 2         | 0.65%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 2         | 0.65%   |
| Intel SSD 660P Series                                                            | 2         | 0.65%   |
| Intel SSD 600P Series                                                            | 2         | 0.65%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.65%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 2         | 0.65%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]             | 2         | 0.65%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                         | 2         | 0.65%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                  | 2         | 0.65%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                  | 2         | 0.65%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 2         | 0.65%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 2         | 0.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 0.65%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                      | 1         | 0.32%   |
| VIA VT8237A SATA 2-Port Controller                                               | 1         | 0.32%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 1         | 0.32%   |
| Toshiba America Info Systems Toshiba America Info Non-Volatile memory controller | 1         | 0.32%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 1         | 0.32%   |
| SanDisk WD Black NVMe SSD                                                        | 1         | 0.32%   |
| SanDisk Non-Volatile memory controller                                           | 1         | 0.32%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 176       | 59.46%  |
| NVMe | 85        | 28.72%  |
| IDE  | 21        | 7.09%   |
| RAID | 14        | 4.73%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 189       | 81.82%  |
| AMD    | 42        | 18.18%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 11        | 4.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 9         | 3.9%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 3.46%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 2.6%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 2.16%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 4         | 1.73%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 4         | 1.73%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.73%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 1.73%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 1.73%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 3         | 1.3%    |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 1.3%    |
| Intel Pentium CPU 2020M @ 2.40GHz             | 3         | 1.3%    |
| Intel Pentium 3556U @ 1.70GHz                 | 3         | 1.3%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 1.3%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 1.3%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 1.3%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 3         | 1.3%    |
| Intel Celeron CPU N2840 @ 2.16GHz             | 3         | 1.3%    |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 1.3%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 1.3%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.3%    |
| Intel Pentium M processor 1.86GHz             | 2         | 0.87%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 2         | 0.87%   |
| Intel Core i9-9880H CPU @ 2.30GHz             | 2         | 0.87%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.87%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.87%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.87%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 2         | 0.87%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.87%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.87%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.87%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 2         | 0.87%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 2         | 0.87%   |
| Intel Core i3-4000M CPU @ 2.40GHz             | 2         | 0.87%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 2         | 0.87%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 2         | 0.87%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 2         | 0.87%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz          | 2         | 0.87%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz          | 2         | 0.87%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 2         | 0.87%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 0.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 2         | 0.87%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 0.87%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 0.87%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 0.87%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 2         | 0.87%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 2         | 0.87%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 2         | 0.87%   |
| AMD Ryzen 3 2200U with Radeon Vega Mobile Gfx | 2         | 0.87%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G  | 2         | 0.87%   |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 2         | 0.87%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.43%   |
| Intel Pentium Dual CPU T3200 @ 2.00GHz        | 1         | 0.43%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.43%   |
| Intel Pentium Dual CPU T2370 @ 1.73GHz        | 1         | 0.43%   |
| Intel Pentium Dual CPU T2330 @ 1.60GHz        | 1         | 0.43%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.43%   |
| Intel Pentium CPU N3540 @ 2.16GHz             | 1         | 0.43%   |
| Intel Pentium CPU N3530 @ 2.16GHz             | 1         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 71        | 30.74%  |
| Intel Core i7           | 40        | 17.32%  |
| Intel Core i3           | 17        | 7.36%   |
| Intel Pentium           | 15        | 6.49%   |
| AMD Ryzen 5             | 14        | 6.06%   |
| Intel Core 2 Duo        | 12        | 5.19%   |
| Other                   | 11        | 4.76%   |
| AMD Ryzen 7             | 9         | 3.9%    |
| Intel Celeron           | 6         | 2.6%    |
| Intel Pentium Dual      | 4         | 1.73%   |
| AMD Ryzen 3             | 4         | 1.73%   |
| AMD A6                  | 4         | 1.73%   |
| Intel Pentium Silver    | 3         | 1.3%    |
| Intel Pentium Dual-Core | 3         | 1.3%    |
| Intel Core i9           | 3         | 1.3%    |
| Intel Atom              | 3         | 1.3%    |
| Intel Pentium M         | 2         | 0.87%   |
| AMD Ryzen 9             | 2         | 0.87%   |
| AMD E1                  | 2         | 0.87%   |
| AMD E                   | 2         | 0.87%   |
| Intel Celeron M         | 1         | 0.43%   |
| AMD Turion 64 X2 Mobile | 1         | 0.43%   |
| AMD Athlon              | 1         | 0.43%   |
| AMD A4                  | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 116       | 50.22%  |
| 4       | 79        | 34.2%   |
| 6       | 18        | 7.79%   |
| 8       | 13        | 5.63%   |
| 1       | 4         | 1.73%   |
| Unknown | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 230       | 99.57%  |
| Unknown | 1         | 0.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 164       | 71%     |
| 1       | 66        | 28.57%  |
| Unknown | 1         | 0.43%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 220       | 94.42%  |
| Unknown        | 9         | 3.86%   |
| 32-bit         | 4         | 1.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 49        | 20.16%  |
| 0x806ea    | 15        | 6.17%   |
| 0x806e9    | 13        | 5.35%   |
| 0x306c3    | 13        | 5.35%   |
| 0x306a9    | 12        | 4.94%   |
| 0x40651    | 11        | 4.53%   |
| 0x906ea    | 10        | 4.12%   |
| 0x806ec    | 10        | 4.12%   |
| 0x6fd      | 8         | 3.29%   |
| 0x806c1    | 6         | 2.47%   |
| 0x206a7    | 6         | 2.47%   |
| 0x0a50000c | 6         | 2.47%   |
| 0x306d4    | 5         | 2.06%   |
| 0x1067a    | 5         | 2.06%   |
| 0x06006705 | 5         | 2.06%   |
| 0x406e3    | 4         | 1.65%   |
| 0x30678    | 4         | 1.65%   |
| 0x08600106 | 4         | 1.65%   |
| 0x08108109 | 4         | 1.65%   |
| 0x0810100b | 4         | 1.65%   |
| 0xa0652    | 3         | 1.23%   |
| 0x706e5    | 3         | 1.23%   |
| 0x506c9    | 3         | 1.23%   |
| 0x20655    | 3         | 1.23%   |
| 0x08608103 | 3         | 1.23%   |
| 0x08600103 | 3         | 1.23%   |
| 0x05000119 | 3         | 1.23%   |
| 0x906ed    | 2         | 0.82%   |
| 0x906e9    | 2         | 0.82%   |
| 0x806eb    | 2         | 0.82%   |
| 0x706a1    | 2         | 0.82%   |
| 0x6fb      | 2         | 0.82%   |
| 0x6d8      | 2         | 0.82%   |
| 0x406c4    | 2         | 0.82%   |
| 0x10676    | 2         | 0.82%   |
| 0x906c0    | 1         | 0.41%   |
| 0x6fa      | 1         | 0.41%   |
| 0x6e8      | 1         | 0.41%   |
| 0x506e3    | 1         | 0.41%   |
| 0x40661    | 1         | 0.41%   |
| 0x106ca    | 1         | 0.41%   |
| 0x106c2    | 1         | 0.41%   |
| 0x08608102 | 1         | 0.41%   |
| 0x08600104 | 1         | 0.41%   |
| 0x08108102 | 1         | 0.41%   |
| 0x07030105 | 1         | 0.41%   |
| 0x06006704 | 1         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| KabyLake      | 65        | 28.14%  |
| Haswell       | 28        | 12.12%  |
| IvyBridge     | 16        | 6.93%   |
| Core          | 11        | 4.76%   |
| Zen 2         | 9         | 3.9%    |
| TigerLake     | 9         | 3.9%    |
| Silvermont    | 9         | 3.9%    |
| Penryn        | 8         | 3.46%   |
| Zen 3         | 7         | 3.03%   |
| Skylake       | 7         | 3.03%   |
| SandyBridge   | 7         | 3.03%   |
| Zen+          | 6         | 2.6%    |
| Excavator     | 6         | 2.6%    |
| Broadwell     | 6         | 2.6%    |
| Unknown       | 5         | 2.16%   |
| Zen           | 4         | 1.73%   |
| Westmere      | 4         | 1.73%   |
| IceLake       | 4         | 1.73%   |
| P6            | 3         | 1.3%    |
| Goldmont plus | 3         | 1.3%    |
| Goldmont      | 3         | 1.3%    |
| CometLake     | 3         | 1.3%    |
| Bobcat        | 3         | 1.3%    |
| Tremont       | 1         | 0.43%   |
| Puma          | 1         | 0.43%   |
| K8 Hammer     | 1         | 0.43%   |
| Jaguar        | 1         | 0.43%   |
| Bonnell       | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 170       | 54.49%  |
| Nvidia                           | 79        | 25.32%  |
| AMD                              | 60        | 19.23%  |
| Silicon Integrated Systems [SiS] | 2         | 0.64%   |
| VIA Technologies                 | 1         | 0.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 19        | 5.96%   |
| Intel HD Graphics 620                                                                    | 14        | 4.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 14        | 4.39%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 14        | 4.39%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 13        | 4.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 11        | 3.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 2.82%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 2.82%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 8         | 2.51%   |
| AMD Renoir                                                                               | 8         | 2.51%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 6         | 1.88%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 1.88%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 1.88%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 1.88%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 1.57%   |
| Nvidia GM108M [GeForce 840M]                                                             | 5         | 1.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 5         | 1.57%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 5         | 1.57%   |
| Intel HD Graphics 5500                                                                   | 5         | 1.57%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 5         | 1.57%   |
| AMD Cezanne                                                                              | 5         | 1.57%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 1.25%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4         | 1.25%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.25%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.25%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 4         | 1.25%   |
| AMD Lucienne                                                                             | 4         | 1.25%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 3         | 0.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.94%   |
| Nvidia GM108M [GeForce MX130]                                                            | 3         | 0.94%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 3         | 0.94%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 3         | 0.94%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 0.94%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.94%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 0.94%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 3         | 0.94%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.94%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 3         | 0.94%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 2         | 0.63%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.63%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 2         | 0.63%   |
| Nvidia GF119M [GeForce GT 520M]                                                          | 2         | 0.63%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 0.63%   |
| Nvidia G86M [GeForce 8400M GS]                                                           | 2         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.63%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.63%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 2         | 0.63%   |
| Intel HD Graphics 630                                                                    | 2         | 0.63%   |
| Intel HD Graphics 530                                                                    | 2         | 0.63%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                                 | 2         | 0.63%   |
| VIA Technologies P4M890 [S3 UniChrome Pro]                                               | 1         | 0.31%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.31%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.31%   |
| Nvidia TU104GLM [Quadro RTX 4000 Mobile / Max-Q]                                         | 1         | 0.31%   |
| Nvidia TU104BM [GeForce RTX 2080 Mobile]                                                 | 1         | 0.31%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.31%   |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                              | 1         | 0.31%   |
| Nvidia GP107GLM [Quadro P2000 Mobile]                                                    | 1         | 0.31%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 96        | 41.56%  |
| Intel + Nvidia | 58        | 25.11%  |
| 1 x AMD        | 33        | 14.29%  |
| Intel + AMD    | 16        | 6.93%   |
| 1 x Nvidia     | 14        | 6.06%   |
| AMD + Nvidia   | 7         | 3.03%   |
| 2 x AMD        | 4         | 1.73%   |
| 1 x SiS        | 2         | 0.87%   |
| 1 x VIA        | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 184       | 79.31%  |
| Proprietary | 40        | 17.24%  |
| Unknown     | 8         | 3.45%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 134       | 55.83%  |
| 1.01-2.0   | 34        | 14.17%  |
| 0.01-0.5   | 28        | 11.67%  |
| 3.01-4.0   | 27        | 11.25%  |
| 0.51-1.0   | 11        | 4.58%   |
| 7.01-8.0   | 3         | 1.25%   |
| 5.01-6.0   | 2         | 0.83%   |
| 2.01-3.0   | 1         | 0.42%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 46        | 17.04%  |
| LG Display              | 41        | 15.19%  |
| BOE                     | 39        | 14.44%  |
| Chimei Innolux          | 36        | 13.33%  |
| Samsung Electronics     | 29        | 10.74%  |
| Dell                    | 22        | 8.15%   |
| Sharp                   | 9         | 3.33%   |
| Goldstar                | 5         | 1.85%   |
| Lenovo                  | 4         | 1.48%   |
| Chi Mei Optoelectronics | 4         | 1.48%   |
| Apple                   | 4         | 1.48%   |
| PANDA                   | 3         | 1.11%   |
| LG Philips              | 3         | 1.11%   |
| CSO                     | 3         | 1.11%   |
| AOC                     | 3         | 1.11%   |
| Quanta Display          | 2         | 0.74%   |
| Hewlett-Packard         | 2         | 0.74%   |
| BenQ                    | 2         | 0.74%   |
| Philips                 | 1         | 0.37%   |
| Panasonic               | 1         | 0.37%   |
| NCS                     | 1         | 0.37%   |
| MSI                     | 1         | 0.37%   |
| InnoLux Display         | 1         | 0.37%   |
| InfoVision              | 1         | 0.37%   |
| Iiyama                  | 1         | 0.37%   |
| IBM                     | 1         | 0.37%   |
| Grundig                 | 1         | 0.37%   |
| Fujitsu Siemens         | 1         | 0.37%   |
| BOE Technology Group    | 1         | 0.37%   |
| Achieva Shimian         | 1         | 0.37%   |
| Acer                    | 1         | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                      | 5         | 1.8%    |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch              | 4         | 1.44%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 4         | 1.44%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                     | 4         | 1.44%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 4         | 1.44%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch               | 3         | 1.08%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 3         | 1.08%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 3         | 1.08%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch          | 3         | 1.08%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch                   | 2         | 0.72%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                   | 2         | 0.72%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch      | 2         | 0.72%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch      | 2         | 0.72%   |
| Quanta Display LCD Monitor QDS002D 1400x1050 285x214mm 14.0-inch          | 2         | 0.72%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch               | 2         | 0.72%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch              | 2         | 0.72%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch              | 2         | 0.72%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch              | 2         | 0.72%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch              | 2         | 0.72%   |
| LG Display LCD Monitor LGD0289 1600x900 382x215mm 17.3-inch               | 2         | 0.72%   |
| Goldstar 22EN43 GSM59D8 1920x1080 480x270mm 21.7-inch                     | 2         | 0.72%   |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                         | 2         | 0.72%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 2         | 0.72%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                        | 2         | 0.72%   |
| Dell SE2717H/HX DELD0A1 1920x1080 600x340mm 27.2-inch                     | 2         | 0.72%   |
| Dell P2417H DELA0DB 1920x1080 530x300mm 24.0-inch                         | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch           | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 2         | 0.72%   |
| Chimei Innolux LCD Monitor CMN1487 1366x768 309x173mm 13.9-inch           | 2         | 0.72%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.72%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                     | 2         | 0.72%   |
| AU Optronics LCD Monitor AUODF87 1920x1080 344x193mm 15.5-inch            | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch             | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch            | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch             | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO313D 1920x1080 309x174mm 14.0-inch            | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch            | 2         | 0.72%   |
| AU Optronics LCD Monitor AUO159E 1600x900 382x214mm 17.2-inch             | 2         | 0.72%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                   | 1         | 0.36%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch                   | 1         | 0.36%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch                   | 1         | 0.36%   |
| Sharp LCD Monitor SHP1479 1920x1280 259x173mm 12.3-inch                   | 1         | 0.36%   |
| Sharp LCD Monitor SHP1449 1920x1080 294x165mm 13.3-inch                   | 1         | 0.36%   |
| Samsung Electronics U28E590 SAM0C4E 3840x2160 610x350mm 27.7-inch         | 1         | 0.36%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch         | 1         | 0.36%   |
| Samsung Electronics T27B300 SAM0933 1920x1080 600x340mm 27.2-inch         | 1         | 0.36%   |
| Samsung Electronics T24D390 SAM0B6E 1920x1080 520x290mm 23.4-inch         | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM0626 1920x1080                          | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM0486 1920x1080                          | 1         | 0.36%   |
| Samsung Electronics SyncMaster SAM021D 1680x1050 433x271mm 20.1-inch      | 1         | 0.36%   |
| Samsung Electronics SE790C SAM0BFE 3440x1440 797x333mm 34.0-inch          | 1         | 0.36%   |
| Samsung Electronics S23B300 SAM08CA 1920x1080 510x287mm 23.0-inch         | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC4B41 1280x800 261x163mm 12.1-inch      | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC4256 1600x900 382x215mm 17.3-inch      | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch      | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3953 1366x768 256x144mm 11.6-inch      | 1         | 0.36%   |
| Samsung Electronics LCD Monitor SEC3741 1280x800 331x207mm 15.4-inch      | 1         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 125       | 49.6%   |
| 1366x768 (WXGA)    | 47        | 18.65%  |
| 1600x900 (HD+)     | 22        | 8.73%   |
| 3840x2160 (4K)     | 12        | 4.76%   |
| 2560x1440 (QHD)    | 9         | 3.57%   |
| 1440x900 (WXGA+)   | 7         | 2.78%   |
| 1280x800 (WXGA)    | 6         | 2.38%   |
| 1920x1200 (WUXGA)  | 4         | 1.59%   |
| 1680x1050 (WSXGA+) | 4         | 1.59%   |
| 2160x1440          | 3         | 1.19%   |
| 3840x2400          | 2         | 0.79%   |
| 2560x1600          | 2         | 0.79%   |
| 1400x1050          | 2         | 0.79%   |
| 3440x1440          | 1         | 0.4%    |
| 2880x1800          | 1         | 0.4%    |
| 1920x1280          | 1         | 0.4%    |
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
| 15      | 126       | 46.15%  |
| 17      | 37        | 13.55%  |
| 13      | 23        | 8.42%   |
| 14      | 20        | 7.33%   |
| 27      | 16        | 5.86%   |
| 24      | 12        | 4.4%    |
| 23      | 7         | 2.56%   |
| 12      | 7         | 2.56%   |
| 31      | 4         | 1.47%   |
| 21      | 4         | 1.47%   |
| 54      | 3         | 1.1%    |
| 16      | 3         | 1.1%    |
| Unknown | 3         | 1.1%    |
| 20      | 2         | 0.73%   |
| 10      | 2         | 0.73%   |
| 34      | 1         | 0.37%   |
| 25      | 1         | 0.37%   |
| 18      | 1         | 0.37%   |
| 11      | 1         | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 152       | 56.72%  |
| 351-400     | 40        | 14.93%  |
| 501-600     | 27        | 10.07%  |
| 201-300     | 26        | 9.7%    |
| 601-700     | 8         | 2.99%   |
| 401-500     | 8         | 2.99%   |
| 1001-1500   | 3         | 1.12%   |
| Unknown     | 3         | 1.12%   |
| 701-800     | 1         | 0.37%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 193       | 83.91%  |
| 16/10   | 26        | 11.3%   |
| 3/2     | 5         | 2.17%   |
| 4/3     | 3         | 1.3%    |
| 5/4     | 1         | 0.43%   |
| 21/9    | 1         | 0.43%   |
| Unknown | 1         | 0.43%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 127       | 46.52%  |
| 121-130        | 32        | 11.72%  |
| 81-90          | 31        | 11.36%  |
| 201-250        | 18        | 6.59%   |
| 301-350        | 16        | 5.86%   |
| 71-80          | 11        | 4.03%   |
| 61-70          | 6         | 2.2%    |
| 351-500        | 5         | 1.83%   |
| 251-300        | 4         | 1.47%   |
| 151-200        | 4         | 1.47%   |
| 131-140        | 4         | 1.47%   |
| More than 1000 | 3         | 1.1%    |
| Unknown        | 3         | 1.1%    |
| 41-50          | 2         | 0.73%   |
| 141-150        | 2         | 0.73%   |
| 111-120        | 2         | 0.73%   |
| 91-100         | 2         | 0.73%   |
| 51-60          | 1         | 0.37%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 126       | 47.55%  |
| 101-120       | 72        | 27.17%  |
| 51-100        | 42        | 15.85%  |
| 161-240       | 14        | 5.28%   |
| More than 240 | 4         | 1.51%   |
| 1-50          | 4         | 1.51%   |
| Unknown       | 3         | 1.13%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 182       | 75.21%  |
| 2     | 45        | 18.6%   |
| 0     | 9         | 3.72%   |
| 3     | 5         | 2.07%   |
| 4     | 1         | 0.41%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 136       | 35.51%  |
| Intel                             | 118       | 30.81%  |
| Qualcomm Atheros                  | 64        | 16.71%  |
| Broadcom                          | 20        | 5.22%   |
| MediaTek                          | 8         | 2.09%   |
| Broadcom Limited                  | 5         | 1.31%   |
| Samsung Electronics               | 4         | 1.04%   |
| Marvell Technology Group          | 3         | 0.78%   |
| Xiaomi                            | 2         | 0.52%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.52%   |
| Ralink                            | 2         | 0.52%   |
| Qualcomm Atheros Communications   | 2         | 0.52%   |
| Qualcomm                          | 2         | 0.52%   |
| Lenovo                            | 2         | 0.52%   |
| D-Link                            | 2         | 0.52%   |
| VIA Technologies                  | 1         | 0.26%   |
| TP-Link                           | 1         | 0.26%   |
| Realtek                           | 1         | 0.26%   |
| Nvidia                            | 1         | 0.26%   |
| HTC (High Tech Computer)          | 1         | 0.26%   |
| Hewlett-Packard                   | 1         | 0.26%   |
| Fibocom                           | 1         | 0.26%   |
| Ericsson Business Mobile Networks | 1         | 0.26%   |
| DisplayLink                       | 1         | 0.26%   |
| Dell                              | 1         | 0.26%   |
| ASIX Electronics                  | 1         | 0.26%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 106       | 23.66%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 4.46%   |
| Intel Wireless 8265 / 8275                                              | 18        | 4.02%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 15        | 3.35%   |
| Intel Wi-Fi 6 AX200                                                     | 14        | 3.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 2.9%    |
| Intel Ethernet Connection (4) I219-V                                    | 8         | 1.79%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 1.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 7         | 1.56%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 1.56%   |
| Intel Wireless 7260                                                     | 7         | 1.56%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 1.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 1.34%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 1.34%   |
| Intel Wireless 3165                                                     | 6         | 1.34%   |
| Intel Wireless 3160                                                     | 6         | 1.34%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 1.34%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.34%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 5         | 1.12%   |
| Intel Wireless 7265                                                     | 5         | 1.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 1.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 0.89%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 0.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 0.89%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 4         | 0.89%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 0.89%   |
| Intel Ethernet Connection I217-LM                                       | 4         | 0.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 0.89%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 3         | 0.67%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.67%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 3         | 0.67%   |
| Intel Wireless-AC 9260                                                  | 3         | 0.67%   |
| Intel WiFi Link 5100                                                    | 3         | 0.67%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 0.67%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 0.67%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 0.67%   |
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
| Intel Ethernet Connection (6) I219-V                                    | 2         | 0.45%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.45%   |
| Intel Centrino Wireless-N 100                                           | 2         | 0.45%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.45%   |
| Intel 82577LM Gigabit Network Connection                                | 2         | 0.45%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express                | 2         | 0.45%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 0.45%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.45%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 0.45%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 1         | 0.22%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                    | 1         | 0.22%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 117       | 49.58%  |
| Qualcomm Atheros                  | 55        | 23.31%  |
| Realtek Semiconductor             | 26        | 11.02%  |
| Broadcom                          | 14        | 5.93%   |
| MediaTek                          | 8         | 3.39%   |
| Broadcom Limited                  | 3         | 1.27%   |
| Ralink                            | 2         | 0.85%   |
| Qualcomm Atheros Communications   | 2         | 0.85%   |
| Qualcomm                          | 2         | 0.85%   |
| D-Link                            | 2         | 0.85%   |
| TP-Link                           | 1         | 0.42%   |
| Realtek                           | 1         | 0.42%   |
| Fibocom                           | 1         | 0.42%   |
| Ericsson Business Mobile Networks | 1         | 0.42%   |
| Dell                              | 1         | 0.42%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 20        | 8.47%   |
| Intel Wireless 8265 / 8275                                              | 18        | 7.63%   |
| Intel Wi-Fi 6 AX200                                                     | 14        | 5.93%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 13        | 5.51%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 2.97%   |
| Intel Wireless 7260                                                     | 7         | 2.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 7         | 2.97%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 2.54%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 6         | 2.54%   |
| Intel Wireless 3165                                                     | 6         | 2.54%   |
| Intel Wireless 3160                                                     | 6         | 2.54%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 6         | 2.54%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 2.54%   |
| Intel Wireless 7265                                                     | 5         | 2.12%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 4         | 1.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 1.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.69%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.69%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 1.69%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 4         | 1.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 4         | 1.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.27%   |
| Intel Wireless-AC 9260                                                  | 3         | 1.27%   |
| Intel WiFi Link 5100                                                    | 3         | 1.27%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.27%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.27%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.85%   |
| Qualcomm QCA6390 Wireless Network Adapter                               | 2         | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.85%   |
| Intel Wireless 8260                                                     | 2         | 0.85%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.85%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.85%   |
| Intel Centrino Wireless-N 100                                           | 2         | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.85%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 2         | 0.85%   |
| Broadcom BCM43224 802.11a/b/g/n                                         | 2         | 0.85%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 2         | 0.85%   |
| TP-Link TL-WN722N v2                                                    | 1         | 0.42%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.42%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.42%   |
| Realtek Realtek Network controller                                      | 1         | 0.42%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.42%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter                  | 1         | 0.42%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.42%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.42%   |
| Qualcomm Atheros AR5523                                                 | 1         | 0.42%   |
| MediaTek WiFi                                                           | 1         | 0.42%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 1         | 0.42%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1         | 0.42%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection               | 1         | 0.42%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 1         | 0.42%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 1         | 0.42%   |
| Intel Centrino Wireless-N 2230                                          | 1         | 0.42%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 1         | 0.42%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 1         | 0.42%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 0.42%   |
| Intel Centrino Advanced-N 6200                                          | 1         | 0.42%   |
| Fibocom L830-EB-00 LTE WWAN Modem                                       | 1         | 0.42%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 129       | 61.43%  |
| Intel                            | 37        | 17.62%  |
| Qualcomm Atheros                 | 18        | 8.57%   |
| Broadcom                         | 6         | 2.86%   |
| Samsung Electronics              | 4         | 1.9%    |
| Marvell Technology Group         | 3         | 1.43%   |
| Xiaomi                           | 2         | 0.95%   |
| Silicon Integrated Systems [SiS] | 2         | 0.95%   |
| Lenovo                           | 2         | 0.95%   |
| Broadcom Limited                 | 2         | 0.95%   |
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
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 106       | 50.48%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 7.14%   |
| Intel Ethernet Connection (4) I219-V                              | 8         | 3.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 3.33%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 5         | 2.38%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 5         | 2.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 4         | 1.9%    |
| Intel Ethernet Connection I217-LM                                 | 4         | 1.9%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.43%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 3         | 1.43%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.43%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 2         | 0.95%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.95%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.95%   |
| Lenovo USB-C Dock Ethernet                                        | 2         | 0.95%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.95%   |
| Intel Ethernet Connection (6) I219-V                              | 2         | 0.95%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.95%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 2         | 0.95%   |
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
| WiFi     | 229       | 53.26%  |
| Ethernet | 199       | 46.28%  |
| Modem    | 2         | 0.47%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 197       | 78.8%   |
| Ethernet | 53        | 21.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 186       | 80.52%  |
| 1     | 44        | 19.05%  |
| 0     | 1         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 222       | 95.69%  |
| Yes  | 10        | 4.31%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 92        | 47.42%  |
| Lite-On Technology              | 20        | 10.31%  |
| Qualcomm Atheros Communications | 19        | 9.79%   |
| Realtek Semiconductor           | 15        | 7.73%   |
| IMC Networks                    | 14        | 7.22%   |
| Foxconn / Hon Hai               | 7         | 3.61%   |
| Broadcom                        | 7         | 3.61%   |
| Hewlett-Packard                 | 5         | 2.58%   |
| Apple                           | 4         | 2.06%   |
| Toshiba                         | 3         | 1.55%   |
| Foxconn International           | 3         | 1.55%   |
| Cambridge Silicon Radio         | 3         | 1.55%   |
| Realtek                         | 1         | 0.52%   |
| Dell                            | 1         | 0.52%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 43        | 22.16%  |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 7.22%   |
| Intel AX200 Bluetooth                               | 14        | 7.22%   |
| Realtek Bluetooth Radio                             | 12        | 6.19%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 11        | 5.67%   |
| Intel AX201 Bluetooth                               | 11        | 5.67%   |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 3.61%   |
| IMC Networks Bluetooth Radio                        | 7         | 3.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 3.09%   |
| Intel Wireless-AC 3168 Bluetooth                    | 6         | 3.09%   |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 2.58%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.55%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 3         | 1.55%   |
| IMC Networks Wireless_Device                        | 3         | 1.55%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 1.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 3         | 1.55%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 1.03%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.03%   |
| Lite-On Wireless_Device                             | 2         | 1.03%   |
| Lite-On Bluetooth Device                            | 2         | 1.03%   |
| IMC Networks Bluetooth Device                       | 2         | 1.03%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 2         | 1.03%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 1.03%   |
| Broadcom BCM2045 Bluetooth                          | 2         | 1.03%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.03%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.52%   |
| Toshiba Integrated Bluetooth (Taiyo Yuden)          | 1         | 0.52%   |
| Toshiba Bluetooth Device                            | 1         | 0.52%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.52%   |
| Realtek Bluetooth Radio                             | 1         | 0.52%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.52%   |
| Qualcomm Atheros Bluetooth                          | 1         | 0.52%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.52%   |
| Qualcomm Atheros AR3012 Bluetooth                   | 1         | 0.52%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.52%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.52%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 1         | 0.52%   |
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
| Intel                            | 184       | 64.56%  |
| AMD                              | 46        | 16.14%  |
| Nvidia                           | 30        | 10.53%  |
| C-Media Electronics              | 4         | 1.4%    |
| Logitech                         | 3         | 1.05%   |
| Lenovo                           | 3         | 1.05%   |
| JMTek                            | 3         | 1.05%   |
| Silicon Integrated Systems [SiS] | 2         | 0.7%    |
| ZOOM                             | 1         | 0.35%   |
| YZ Technology                    | 1         | 0.35%   |
| VIA Technologies                 | 1         | 0.35%   |
| Trust                            | 1         | 0.35%   |
| Texas Instruments                | 1         | 0.35%   |
| SteelSeries ApS                  | 1         | 0.35%   |
| Realtek Semiconductor            | 1         | 0.35%   |
| Plantronics                      | 1         | 0.35%   |
| Pioneer DJ                       | 1         | 0.35%   |
| GN Netcom                        | 1         | 0.35%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 39        | 11.14%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 30        | 8.57%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 4.86%   |
| Intel Cannon Lake PCH cAVS                                                                        | 15        | 4.29%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 4%      |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 14        | 4%      |
| Intel 8 Series HD Audio Controller                                                                | 14        | 4%      |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 4%      |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 3.43%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 10        | 2.86%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 9         | 2.57%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 9         | 2.57%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 2.29%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 8         | 2.29%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 8         | 2.29%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.71%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.71%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 6         | 1.71%   |
| AMD High Definition Audio Controller                                                              | 6         | 1.71%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 1.71%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 5         | 1.43%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.43%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.14%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.14%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.14%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 4         | 1.14%   |
| JMTek USB PnP Audio Device                                                                        | 3         | 0.86%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 0.86%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.86%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.86%   |
| AMD FCH Azalia Controller                                                                         | 3         | 0.86%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 2         | 0.57%   |
| Nvidia TU104 HD Audio Controller                                                                  | 2         | 0.57%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 2         | 0.57%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.57%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 2         | 0.57%   |
| Nvidia Audio device                                                                               | 2         | 0.57%   |
| Lenovo ThinkPad USB-C Dock Gen2 USB Audio                                                         | 2         | 0.57%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 2         | 0.57%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 2         | 0.57%   |
| C-Media Electronics Audio Adapter                                                                 | 2         | 0.57%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 0.57%   |
| AMD Kabini HDMI/DP Audio                                                                          | 2         | 0.57%   |
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
| Samsung Electronics | 45        | 30.2%   |
| SK hynix            | 33        | 22.15%  |
| Kingston            | 23        | 15.44%  |
| Micron Technology   | 21        | 14.09%  |
| Crucial             | 7         | 4.7%    |
| Unknown             | 6         | 4.03%   |
| Ramaxel Technology  | 3         | 2.01%   |
| Patriot             | 2         | 1.34%   |
| Elpida              | 2         | 1.34%   |
| A-DATA Technology   | 2         | 1.34%   |
| Transcend           | 1         | 0.67%   |
| Qimonda             | 1         | 0.67%   |
| G.Skill             | 1         | 0.67%   |
| Corsair             | 1         | 0.67%   |
| 48spaces            | 1         | 0.67%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 3.68%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 3.07%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 2.45%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 1.84%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 3         | 1.84%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.84%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 1.84%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.84%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 3         | 1.84%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 2         | 1.23%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.23%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 2         | 1.23%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 2         | 1.23%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s     | 2         | 1.23%   |
| Samsung RAM M471A2G43AB2-CWE 16384MB SODIMM DDR4 3200MT/s        | 2         | 1.23%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.23%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 2         | 1.23%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4GB SODIMM DDR4 2133MT/s            | 2         | 1.23%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 2         | 1.23%   |
| Kingston RAM 9905712-034.A00G 16GB SODIMM DDR4 2400MT/s          | 2         | 1.23%   |
| Kingston RAM 9905700-047.A00G 16384MB SODIMM DDR4 2667MT/s       | 2         | 1.23%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR3 1867MT/s              | 1         | 0.61%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2400MT/s                   | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.61%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 0.61%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 1         | 0.61%   |
| Transcend RAM TS128MSQ64V6J 1GB SODIMM DDR 667MT/s               | 1         | 0.61%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.61%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                  | 1         | 0.61%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 1         | 0.61%   |
| SK hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 0.61%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                       | 1         | 0.61%   |
| SK hynix RAM Module 16GB SODIMM DDR4 2667MT/s                    | 1         | 0.61%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                 | 1         | 0.61%   |
| SK hynix RAM HYMP512S64CP8-Y5 1GB SODIMM DDR2 667MT/s            | 1         | 0.61%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.61%   |
| SK hynix RAM HMT325S6CFR8A-PB 2GB SODIMM 1600MT/s                | 1         | 0.61%   |
| SK hynix RAM HMT125S6TFR8C-H9 2048MB SODIMM DDR3 1334MT/s        | 1         | 0.61%   |
| SK hynix RAM HMAA1GS6CMR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.61%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.61%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.61%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.61%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 1         | 0.61%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 0.61%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.61%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.61%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 1         | 0.61%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 1         | 0.61%   |
| SK hynix RAM GKE160SO102408-3000 16384MB SODIMM DDR4 3000MT/s    | 1         | 0.61%   |
| Samsung RAM Module 8192MB SODIMM DDR4 3200MT/s                   | 1         | 0.61%   |
| Samsung RAM Module 1024MB SODIMM DDR2 533MT/s                    | 1         | 0.61%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.61%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 1         | 0.61%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.61%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 1         | 0.61%   |
| Samsung RAM M471B5173CB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.61%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.61%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.61%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.61%   |
| Samsung RAM M471B1G73BH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 62        | 50.41%  |
| DDR3   | 40        | 32.52%  |
| LPDDR3 | 8         | 6.5%    |
| DDR2   | 7         | 5.69%   |
| LPDDR4 | 5         | 4.07%   |
| SDRAM  | 1         | 0.81%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 106       | 86.18%  |
| Row Of Chips | 15        | 12.2%   |
| DIMM         | 1         | 0.81%   |
| Chip         | 1         | 0.81%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 53        | 39.26%  |
| 4096  | 44        | 32.59%  |
| 16384 | 20        | 14.81%  |
| 2048  | 10        | 7.41%   |
| 1024  | 5         | 3.7%    |
| 32768 | 3         | 2.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 34        | 25.56%  |
| 1600  | 33        | 24.81%  |
| 3200  | 24        | 18.05%  |
| 2133  | 9         | 6.77%   |
| 2400  | 7         | 5.26%   |
| 667   | 6         | 4.51%   |
| 1334  | 5         | 3.76%   |
| 4267  | 2         | 1.5%    |
| 1867  | 2         | 1.5%    |
| 1333  | 2         | 1.5%    |
| 8400  | 1         | 0.75%   |
| 4266  | 1         | 0.75%   |
| 3266  | 1         | 0.75%   |
| 3000  | 1         | 0.75%   |
| 2048  | 1         | 0.75%   |
| 1067  | 1         | 0.75%   |
| 1066  | 1         | 0.75%   |
| 975   | 1         | 0.75%   |
| 533   | 1         | 0.75%   |

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
| Chicony Electronics                    | 62        | 28.57%  |
| IMC Networks                           | 26        | 11.98%  |
| Quanta                                 | 21        | 9.68%   |
| Realtek Semiconductor                  | 20        | 9.22%   |
| Microdia                               | 15        | 6.91%   |
| Acer                                   | 14        | 6.45%   |
| Suyin                                  | 10        | 4.61%   |
| Lite-On Technology                     | 8         | 3.69%   |
| Syntek                                 | 7         | 3.23%   |
| Sunplus Innovation Technology          | 7         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 2.76%   |
| Luxvisions Innotech Limited            | 3         | 1.38%   |
| Apple                                  | 3         | 1.38%   |
| Silicon Motion                         | 2         | 0.92%   |
| Primax Electronics                     | 2         | 0.92%   |
| Logitech                               | 2         | 0.92%   |
| Jieli Technology                       | 2         | 0.92%   |
| Anker                                  | 2         | 0.92%   |
| Z-Star Microelectronics                | 1         | 0.46%   |
| Goertek Electronics                    | 1         | 0.46%   |
| Genesys Logic                          | 1         | 0.46%   |
| Cubeternet                             | 1         | 0.46%   |
| AVerMedia Technologies                 | 1         | 0.46%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 12        | 5.53%   |
| Chicony HD WebCam                                   | 12        | 5.53%   |
| IMC Networks Integrated Camera                      | 10        | 4.61%   |
| Quanta VGA WebCam                                   | 8         | 3.69%   |
| Microdia Integrated_Webcam_HD                       | 8         | 3.69%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 7         | 3.23%   |
| Realtek Integrated_Webcam_HD                        | 5         | 2.3%    |
| Lite-On HP HD Camera                                | 5         | 2.3%    |
| Acer Lenovo EasyCamera                              | 5         | 2.3%    |
| Quanta HD Webcam                                    | 4         | 1.84%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 4         | 1.84%   |
| Syntek Integrated Camera                            | 3         | 1.38%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 3         | 1.38%   |
| Realtek Lenovo EasyCamera                           | 3         | 1.38%   |
| Quanta HP TrueVision HD Camera                      | 3         | 1.38%   |
| Quanta HD User Facing                               | 3         | 1.38%   |
| Chicony USB2.0 VGA UVC WebCam                       | 3         | 1.38%   |
| Chicony USB2.0 HD UVC WebCam                        | 3         | 1.38%   |
| Chicony Integrated HP HD Webcam                     | 3         | 1.38%   |
| Chicony HP Wide Vision HD Camera                    | 3         | 1.38%   |
| Chicony HP Webcam                                   | 3         | 1.38%   |
| Suyin WebCam                                        | 2         | 0.92%   |
| Suyin HP TrueVision HD Integrated Webcam            | 2         | 0.92%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 0.92%   |
| Sunplus HD WebCam                                   | 2         | 0.92%   |
| Realtek USB Camera                                  | 2         | 0.92%   |
| Realtek Integrated Webcam                           | 2         | 0.92%   |
| Realtek EasyCamera                                  | 2         | 0.92%   |
| Realtek Acer 640 x 480 laptop camera                | 2         | 0.92%   |
| Quanta HP HD Camera                                 | 2         | 0.92%   |
| Primax HP HD Webcam [Fixed]                         | 2         | 0.92%   |
| Microdia Laptop_Integrated_Webcam_HD                | 2         | 0.92%   |
| Microdia Integrated Webcam                          | 2         | 0.92%   |
| Luxvisions Innotech Limited Integrated Camera       | 2         | 0.92%   |
| Lite-On Integrated Camera                           | 2         | 0.92%   |
| Jieli USB PHY 2.0                                   | 2         | 0.92%   |
| IMC Networks HD Camera                              | 2         | 0.92%   |
| Chicony USB 2.0 Camera                              | 2         | 0.92%   |
| Chicony ThinkPad T490 Webcam                        | 2         | 0.92%   |
| Chicony Integrated Camera (1280x720@30)             | 2         | 0.92%   |
| Chicony HP Wide Vision HD                           | 2         | 0.92%   |
| Chicony EasyCamera                                  | 2         | 0.92%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 2         | 0.92%   |
| Anker PowerConf C300                                | 2         | 0.92%   |
| Acer Lenovo Integrated Webcam                       | 2         | 0.92%   |
| Acer Integrated Camera                              | 2         | 0.92%   |
| Acer BisonCam,NB Pro                                | 2         | 0.92%   |
| Z-Star Webcam                                       | 1         | 0.46%   |
| Syntek Sonix USB 2.0 Camera                         | 1         | 0.46%   |
| Syntek Sonix 1.3MPixel USB 2.0 Camera               | 1         | 0.46%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.46%   |
| Syntek EasyCamera                                   | 1         | 0.46%   |
| Suyin Laptop_Integrated_Webcam_HD                   | 1         | 0.46%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.46%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.46%   |
| Sunplus Integrated Camera                           | 1         | 0.46%   |
| Sunplus ASUS Webcam                                 | 1         | 0.46%   |
| Sunplus ASUS USB2.0 Webcam                          | 1         | 0.46%   |
| Silicon Motion WebCam SC-03FFL11939N                | 1         | 0.46%   |
| Silicon Motion WebCam SC-0311139N                   | 1         | 0.46%   |

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
| Alcor Micro           | 4         | 50%     |
| Broadcom              | 2         | 25%     |
| Realtek Semiconductor | 1         | 12.5%   |
| Lenovo                | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader               | 4         | 50%     |
| Realtek Semiconductor Smart Card Reader Interface | 1         | 12.5%   |
| Lenovo Integrated Smart Card Reader               | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor    | 1         | 12.5%   |
| Broadcom 5880                                     | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 147       | 61.51%  |
| 1     | 74        | 30.96%  |
| 2     | 16        | 6.69%   |
| 3     | 2         | 0.84%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 51        | 46.36%  |
| Graphics card            | 24        | 21.82%  |
| Net/wireless             | 11        | 10%     |
| Chipcard                 | 7         | 6.36%   |
| Multimedia controller    | 6         | 5.45%   |
| Card reader              | 3         | 2.73%   |
| Communication controller | 2         | 1.82%   |
| Camera                   | 2         | 1.82%   |
| Storage/ide              | 1         | 0.91%   |
| Storage                  | 1         | 0.91%   |
| Sound                    | 1         | 0.91%   |
| Modem                    | 1         | 0.91%   |

