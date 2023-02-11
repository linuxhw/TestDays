ALT Linux - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for ALT Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ALT_Linux/Desktop/README.md) and [notebooks](/Dist/ALT_Linux/Notebook/README.md).

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

Total: 666

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Clevo         | NL41MU2                     | Notebook    | [95dac05397](https://linux-hardware.org/?probe=95dac05397) | Jan 31, 2023 |
| ASUSTek       | N53Ta                       | Notebook    | [30131c7409](https://linux-hardware.org/?probe=30131c7409) | Jan 31, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [ab13127567](https://linux-hardware.org/?probe=ab13127567) | Jan 29, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [86e493728f](https://linux-hardware.org/?probe=86e493728f) | Jan 27, 2023 |
| Intel         | X99 V1.0                    | Desktop     | [560cc09a5a](https://linux-hardware.org/?probe=560cc09a5a) | Jan 26, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [82e558cf16](https://linux-hardware.org/?probe=82e558cf16) | Jan 25, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [347446f16f](https://linux-hardware.org/?probe=347446f16f) | Jan 25, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [831e02a268](https://linux-hardware.org/?probe=831e02a268) | Jan 24, 2023 |
| Lenovo        | B560                        | Notebook    | [b474faa82b](https://linux-hardware.org/?probe=b474faa82b) | Jan 23, 2023 |
| Intel         | SKYBAY                      | Desktop     | [0d2187e1bd](https://linux-hardware.org/?probe=0d2187e1bd) | Jan 23, 2023 |
| Intel         | SKYBAY                      | Desktop     | [1781c6451f](https://linux-hardware.org/?probe=1781c6451f) | Jan 23, 2023 |
| Acer          | Aspire E1-530G              | Notebook    | [b4f6567b3f](https://linux-hardware.org/?probe=b4f6567b3f) | Jan 22, 2023 |
| Dell          | Latitude 5580               | Notebook    | [9cfd456bd4](https://linux-hardware.org/?probe=9cfd456bd4) | Jan 22, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [43b8eec1e2](https://linux-hardware.org/?probe=43b8eec1e2) | Jan 18, 2023 |
| Eii           | P612F                       | All in one  | [29acda8f67](https://linux-hardware.org/?probe=29acda8f67) | Jan 18, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [bb4c5c0f73](https://linux-hardware.org/?probe=bb4c5c0f73) | Jan 18, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [c1c0617217](https://linux-hardware.org/?probe=c1c0617217) | Jan 17, 2023 |
| Intel         | X99 V1.0                    | Desktop     | [c531fbad47](https://linux-hardware.org/?probe=c531fbad47) | Jan 14, 2023 |
| Timi          | Redmi Book Pro 14S          | Notebook    | [911075716c](https://linux-hardware.org/?probe=911075716c) | Jan 13, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [fdf24274c5](https://linux-hardware.org/?probe=fdf24274c5) | Jan 13, 2023 |
| Intel         | X79G V2.x                   | Desktop     | [8228b94c50](https://linux-hardware.org/?probe=8228b94c50) | Jan 11, 2023 |
| Yadro         | YadroB560                   | Desktop     | [9d45ee1c8c](https://linux-hardware.org/?probe=9d45ee1c8c) | Jan 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [45ea0a8983](https://linux-hardware.org/?probe=45ea0a8983) | Jan 11, 2023 |
| Intel         | Jasper Lake Client Platf... | Notebook    | [3000408196](https://linux-hardware.org/?probe=3000408196) | Jan 11, 2023 |
| Intel         | SKYBAY                      | Desktop     | [b6402cdd5e](https://linux-hardware.org/?probe=b6402cdd5e) | Jan 11, 2023 |
| Intel         | SKYBAY                      | Desktop     | [c896f4d5ee](https://linux-hardware.org/?probe=c896f4d5ee) | Jan 11, 2023 |
| ASUSTek       | P7H55-M                     | Desktop     | [808e7e41c5](https://linux-hardware.org/?probe=808e7e41c5) | Jan 10, 2023 |
| Gigabyte      | Z490 AORUS PRO AX           | Desktop     | [914e3f30cc](https://linux-hardware.org/?probe=914e3f30cc) | Jan 08, 2023 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [bed374999d](https://linux-hardware.org/?probe=bed374999d) | Jan 06, 2023 |
| Gigabyte      | H55M-USB3                   | Desktop     | [2952e11cdb](https://linux-hardware.org/?probe=2952e11cdb) | Jan 01, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [6aaaf2e570](https://linux-hardware.org/?probe=6aaaf2e570) | Dec 28, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [4d7e3586e2](https://linux-hardware.org/?probe=4d7e3586e2) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [0c71831ff4](https://linux-hardware.org/?probe=0c71831ff4) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [50c31f6b47](https://linux-hardware.org/?probe=50c31f6b47) | Dec 27, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [190bb1537d](https://linux-hardware.org/?probe=190bb1537d) | Dec 26, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [0574ad6c44](https://linux-hardware.org/?probe=0574ad6c44) | Dec 26, 2022 |
| ICL           | H510SB-TM v2.0              | All in one  | [9a8967485d](https://linux-hardware.org/?probe=9a8967485d) | Dec 26, 2022 |
| LTD Delovo... | 15Y                         | Notebook    | [286aa3fb96](https://linux-hardware.org/?probe=286aa3fb96) | Dec 25, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [f9b6dc975b](https://linux-hardware.org/?probe=f9b6dc975b) | Dec 23, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [c93f96de9e](https://linux-hardware.org/?probe=c93f96de9e) | Dec 22, 2022 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [0456782550](https://linux-hardware.org/?probe=0456782550) | Dec 21, 2022 |
| Unknown       | Unknown                     | Desktop     | [5ad56cab50](https://linux-hardware.org/?probe=5ad56cab50) | Dec 19, 2022 |
| Unknown       | Unknown                     | Desktop     | [e06ebbd650](https://linux-hardware.org/?probe=e06ebbd650) | Dec 19, 2022 |
| Pegatron      | C15B                        | Notebook    | [865b882e8a](https://linux-hardware.org/?probe=865b882e8a) | Dec 18, 2022 |
| Biostar       | TB250-BTC                   | Desktop     | [00dd0bc59e](https://linux-hardware.org/?probe=00dd0bc59e) | Dec 18, 2022 |
| Aquarius      | Pro, Std, Elt Series        | Notebook    | [59b7fca136](https://linux-hardware.org/?probe=59b7fca136) | Dec 18, 2022 |
| ASUSTek       | M3N78-VM                    | Desktop     | [afd0404144](https://linux-hardware.org/?probe=afd0404144) | Dec 17, 2022 |
| ASUSTek       | M3N78-VM                    | Desktop     | [e7e9b42211](https://linux-hardware.org/?probe=e7e9b42211) | Dec 16, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [26bb5af1a4](https://linux-hardware.org/?probe=26bb5af1a4) | Dec 16, 2022 |
| Irbis         | NB264                       | Notebook    | [14764ec4e5](https://linux-hardware.org/?probe=14764ec4e5) | Dec 15, 2022 |
| Unknown       | Unknown                     | Notebook    | [24bebac773](https://linux-hardware.org/?probe=24bebac773) | Dec 15, 2022 |
| Unknown       | Unknown                     | Notebook    | [643cb41a84](https://linux-hardware.org/?probe=643cb41a84) | Dec 15, 2022 |
| ICL           | H510SB-TM v2.0              | All in one  | [25e63313c0](https://linux-hardware.org/?probe=25e63313c0) | Dec 13, 2022 |
| ICL           | H510SB-TM v2.0              | All in one  | [b58d61f85f](https://linux-hardware.org/?probe=b58d61f85f) | Dec 13, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [2f5b88399a](https://linux-hardware.org/?probe=2f5b88399a) | Dec 13, 2022 |
| Graviton      | DMB-H610-TMI01              | All in one  | [0b2b77d521](https://linux-hardware.org/?probe=0b2b77d521) | Dec 12, 2022 |
| Dell          | Vostro 14 5410              | Notebook    | [af22c1db61](https://linux-hardware.org/?probe=af22c1db61) | Dec 08, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [317fdfd70b](https://linux-hardware.org/?probe=317fdfd70b) | Dec 08, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [619fd919a1](https://linux-hardware.org/?probe=619fd919a1) | Dec 07, 2022 |
| HP            | 255 G4                      | Notebook    | [33b2fb7f31](https://linux-hardware.org/?probe=33b2fb7f31) | Nov 30, 2022 |
| Pegatron      | C15B                        | Notebook    | [92271ab582](https://linux-hardware.org/?probe=92271ab582) | Nov 30, 2022 |
| Graviton      | DMB-H510-MCA01              | Desktop     | [4dbcbc3b7a](https://linux-hardware.org/?probe=4dbcbc3b7a) | Nov 30, 2022 |
| Samsung       | R560                        | Notebook    | [936ae4b775](https://linux-hardware.org/?probe=936ae4b775) | Nov 29, 2022 |
| Timi          | TM1701                      | Notebook    | [64ee057496](https://linux-hardware.org/?probe=64ee057496) | Nov 28, 2022 |
| Acer          | TravelMate 4200             | Notebook    | [14b60c4afa](https://linux-hardware.org/?probe=14b60c4afa) | Nov 26, 2022 |
| MSI           | J1800I                      | Desktop     | [156269ae8c](https://linux-hardware.org/?probe=156269ae8c) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [52da79e88f](https://linux-hardware.org/?probe=52da79e88f) | Nov 25, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4a758bfcc8](https://linux-hardware.org/?probe=4a758bfcc8) | Nov 25, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [0736d8a48f](https://linux-hardware.org/?probe=0736d8a48f) | Nov 24, 2022 |
| Panasonic     | CF-C2CH2CBMG                | Notebook    | [cf87bdba01](https://linux-hardware.org/?probe=cf87bdba01) | Nov 24, 2022 |
| Acer          | Aspire 5940                 | Notebook    | [33325564e7](https://linux-hardware.org/?probe=33325564e7) | Nov 22, 2022 |
| Samsung       | SR70S/SR71S                 | Notebook    | [27c34cd9df](https://linux-hardware.org/?probe=27c34cd9df) | Nov 22, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [bd18dfe05f](https://linux-hardware.org/?probe=bd18dfe05f) | Nov 20, 2022 |
| Intel         | H510SB-TM v2.0              | All in one  | [ece886e874](https://linux-hardware.org/?probe=ece886e874) | Nov 17, 2022 |
| Timi          | TM1701                      | Notebook    | [e77b655bb8](https://linux-hardware.org/?probe=e77b655bb8) | Nov 16, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [72ebef559b](https://linux-hardware.org/?probe=72ebef559b) | Nov 16, 2022 |
| HP            | Mini 110-3700               | Notebook    | [8ca62a1880](https://linux-hardware.org/?probe=8ca62a1880) | Nov 15, 2022 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [1a09a9bb5c](https://linux-hardware.org/?probe=1a09a9bb5c) | Nov 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6e9bc709d9](https://linux-hardware.org/?probe=6e9bc709d9) | Nov 13, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [49162725d5](https://linux-hardware.org/?probe=49162725d5) | Nov 13, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [65226dd80a](https://linux-hardware.org/?probe=65226dd80a) | Nov 11, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [a25dd1174c](https://linux-hardware.org/?probe=a25dd1174c) | Nov 11, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [b5965fce49](https://linux-hardware.org/?probe=b5965fce49) | Nov 11, 2022 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [d3d30c473e](https://linux-hardware.org/?probe=d3d30c473e) | Nov 10, 2022 |
| Gigabyte      | 8I915GMF                    | Desktop     | [76f5cb17ad](https://linux-hardware.org/?probe=76f5cb17ad) | Nov 10, 2022 |
| Acer          | TravelMate 6292             | Notebook    | [c7dcad2d0f](https://linux-hardware.org/?probe=c7dcad2d0f) | Nov 10, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [cc051268d8](https://linux-hardware.org/?probe=cc051268d8) | Nov 05, 2022 |
| ASUSTek       | T100TAM                     | Notebook    | [d409557d4b](https://linux-hardware.org/?probe=d409557d4b) | Nov 03, 2022 |
| ASUSTek       | T100TAM                     | Notebook    | [a2a70b919d](https://linux-hardware.org/?probe=a2a70b919d) | Oct 31, 2022 |
| ASUSTek       | P7H55-M/USB3                | Desktop     | [8983159779](https://linux-hardware.org/?probe=8983159779) | Oct 30, 2022 |
| ASRock        | Z77 Pro4-M                  | Desktop     | [b388ac6776](https://linux-hardware.org/?probe=b388ac6776) | Oct 27, 2022 |
| Biostar       | TB250-BTC                   | Desktop     | [89e7931244](https://linux-hardware.org/?probe=89e7931244) | Oct 27, 2022 |
| Intel         | D34010WYK H14771-301        | Desktop     | [cea24a780a](https://linux-hardware.org/?probe=cea24a780a) | Oct 26, 2022 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [a876af89ec](https://linux-hardware.org/?probe=a876af89ec) | Oct 24, 2022 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [25db5739b7](https://linux-hardware.org/?probe=25db5739b7) | Oct 24, 2022 |
| Toshiba       | dynabook Satellite T87/8... | Notebook    | [10f344a2b3](https://linux-hardware.org/?probe=10f344a2b3) | Oct 24, 2022 |
| Intel         | D34010WYK H14771-301        | Desktop     | [18d8d35afa](https://linux-hardware.org/?probe=18d8d35afa) | Oct 24, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [bfb6c03047](https://linux-hardware.org/?probe=bfb6c03047) | Oct 22, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ae13c0bb6b](https://linux-hardware.org/?probe=ae13c0bb6b) | Oct 20, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [5a8ac06ce5](https://linux-hardware.org/?probe=5a8ac06ce5) | Oct 19, 2022 |
| DEPO Compu... | DPC156                      | Notebook    | [4820b94a4a](https://linux-hardware.org/?probe=4820b94a4a) | Oct 18, 2022 |
| Samsung       | R509                        | Notebook    | [ce3166845f](https://linux-hardware.org/?probe=ce3166845f) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [73145a883c](https://linux-hardware.org/?probe=73145a883c) | Oct 17, 2022 |
| Huanan        | H97-ZD3 V2.0                | Desktop     | [d0d194fbdc](https://linux-hardware.org/?probe=d0d194fbdc) | Oct 15, 2022 |
| Graviton      | DMB-H510-MCA01              | Desktop     | [355974871d](https://linux-hardware.org/?probe=355974871d) | Oct 12, 2022 |
| Supermicro    | X11SCL-F                    | Server      | [a28efd61d1](https://linux-hardware.org/?probe=a28efd61d1) | Oct 11, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [fd73da4fee](https://linux-hardware.org/?probe=fd73da4fee) | Oct 11, 2022 |
| Graviton      | DMB-H510-MCA01              | Desktop     | [02395d2c6f](https://linux-hardware.org/?probe=02395d2c6f) | Oct 07, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [79b160283f](https://linux-hardware.org/?probe=79b160283f) | Oct 05, 2022 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [8e3ee86b79](https://linux-hardware.org/?probe=8e3ee86b79) | Oct 05, 2022 |
| ASUSTek       | D300TA                      | Desktop     | [7c175e4db4](https://linux-hardware.org/?probe=7c175e4db4) | Oct 03, 2022 |
| Acer          | AOA150                      | Notebook    | [b8780da9ef](https://linux-hardware.org/?probe=b8780da9ef) | Oct 02, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [c1c976ba69](https://linux-hardware.org/?probe=c1c976ba69) | Sep 27, 2022 |
| Lenovo        | IdeaPad Y700-15ACZ 80NY     | Notebook    | [b47b842550](https://linux-hardware.org/?probe=b47b842550) | Sep 25, 2022 |
| Acer          | AO722                       | Notebook    | [f2c6378873](https://linux-hardware.org/?probe=f2c6378873) | Sep 25, 2022 |
| ICL           | NLx0MU                      | Notebook    | [d8e7f39201](https://linux-hardware.org/?probe=d8e7f39201) | Sep 23, 2022 |
| Clevo         | NL41MU2                     | Notebook    | [226bbaa11e](https://linux-hardware.org/?probe=226bbaa11e) | Sep 23, 2022 |
| MSI           | B560M PRO-VDH               | Desktop     | [34db101d55](https://linux-hardware.org/?probe=34db101d55) | Sep 22, 2022 |
| ASUSTek       | T100TAM                     | Notebook    | [65a37e4802](https://linux-hardware.org/?probe=65a37e4802) | Sep 19, 2022 |
| ASUSTek       | C8HM70-I/HDMI               | Desktop     | [b8609443fe](https://linux-hardware.org/?probe=b8609443fe) | Sep 17, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [8391d18411](https://linux-hardware.org/?probe=8391d18411) | Sep 05, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [aee6f1bdbb](https://linux-hardware.org/?probe=aee6f1bdbb) | Sep 05, 2022 |
| Gigabyte      | M57SLI-S4                   | Desktop     | [0384b171c7](https://linux-hardware.org/?probe=0384b171c7) | Sep 03, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [899d0fc360](https://linux-hardware.org/?probe=899d0fc360) | Aug 30, 2022 |
| Compumax C... | ONIX-CEL-0001               | Notebook    | [272ca2c7b7](https://linux-hardware.org/?probe=272ca2c7b7) | Aug 27, 2022 |
| DEPO Compu... | DPC156                      | Notebook    | [7c97a519fe](https://linux-hardware.org/?probe=7c97a519fe) | Aug 26, 2022 |
| Lenovo        | G460 20041                  | Notebook    | [ac9bf296d8](https://linux-hardware.org/?probe=ac9bf296d8) | Aug 25, 2022 |
| IP3 Tech      | TGLUP3                      | Notebook    | [a4f803f8a1](https://linux-hardware.org/?probe=a4f803f8a1) | Aug 24, 2022 |
| Unknown       | Unknown                     | Notebook    | [57d5700736](https://linux-hardware.org/?probe=57d5700736) | Aug 21, 2022 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [cfa6cef53d](https://linux-hardware.org/?probe=cfa6cef53d) | Aug 18, 2022 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [840fa733f4](https://linux-hardware.org/?probe=840fa733f4) | Aug 18, 2022 |
| ASUSTek       | F2A85-V                     | Desktop     | [a6a798ce96](https://linux-hardware.org/?probe=a6a798ce96) | Aug 16, 2022 |
| ASUSTek       | X550ZE                      | Notebook    | [3a9d682c2f](https://linux-hardware.org/?probe=3a9d682c2f) | Aug 16, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [315c1df30c](https://linux-hardware.org/?probe=315c1df30c) | Aug 16, 2022 |
| HP            | Pavilion g7                 | Notebook    | [93adb73648](https://linux-hardware.org/?probe=93adb73648) | Aug 08, 2022 |
| HP            | 83EB                        | All in one  | [beb4a8d108](https://linux-hardware.org/?probe=beb4a8d108) | Aug 03, 2022 |
| Dell          | 0W0CHX A00                  | Desktop     | [7d9b8e0f96](https://linux-hardware.org/?probe=7d9b8e0f96) | Aug 01, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [982a6e3241](https://linux-hardware.org/?probe=982a6e3241) | Jul 30, 2022 |
| ICL           | NLx0MU                      | Notebook    | [af0922946a](https://linux-hardware.org/?probe=af0922946a) | Jul 25, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [f870753f2f](https://linux-hardware.org/?probe=f870753f2f) | Jul 21, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [42a2639fcf](https://linux-hardware.org/?probe=42a2639fcf) | Jul 20, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [337e6e0efa](https://linux-hardware.org/?probe=337e6e0efa) | Jul 18, 2022 |
| OEM           | KX-18 V1.0                  | Desktop     | [a68e653aa9](https://linux-hardware.org/?probe=a68e653aa9) | Jul 14, 2022 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [5df194f626](https://linux-hardware.org/?probe=5df194f626) | Jul 13, 2022 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [c8051cd18e](https://linux-hardware.org/?probe=c8051cd18e) | Jul 13, 2022 |
| Dell          | Vostro 14 5410              | Notebook    | [2faa8bf726](https://linux-hardware.org/?probe=2faa8bf726) | Jul 12, 2022 |
| HP            | ProBook 4710s               | Notebook    | [4fe41da4e8](https://linux-hardware.org/?probe=4fe41da4e8) | Jul 09, 2022 |
| HP            | ProBook 4710s               | Notebook    | [932822fdc7](https://linux-hardware.org/?probe=932822fdc7) | Jul 09, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [5d2d940ec2](https://linux-hardware.org/?probe=5d2d940ec2) | Jul 07, 2022 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [7a95d588c4](https://linux-hardware.org/?probe=7a95d588c4) | Jul 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [a8888a6627](https://linux-hardware.org/?probe=a8888a6627) | Jul 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [b3da1e4cdb](https://linux-hardware.org/?probe=b3da1e4cdb) | Jul 05, 2022 |
| Intel         | H510SB-TM v2.0              | All in one  | [8598f1f5ee](https://linux-hardware.org/?probe=8598f1f5ee) | Jun 30, 2022 |
| Gigabyte      | GA-A75M-D2H                 | Desktop     | [7411d7a561](https://linux-hardware.org/?probe=7411d7a561) | Jun 23, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [3a07a4c8db](https://linux-hardware.org/?probe=3a07a4c8db) | Jun 21, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [2724c1558a](https://linux-hardware.org/?probe=2724c1558a) | Jun 20, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [8fe4a74fa3](https://linux-hardware.org/?probe=8fe4a74fa3) | Jun 10, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [7c16967701](https://linux-hardware.org/?probe=7c16967701) | Jun 10, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [31ab5150ea](https://linux-hardware.org/?probe=31ab5150ea) | Jun 06, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [4fa81ba66a](https://linux-hardware.org/?probe=4fa81ba66a) | Jun 06, 2022 |
| HP            | Pavilion dv7                | Notebook    | [19be007666](https://linux-hardware.org/?probe=19be007666) | Jun 04, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [fb935ea1d0](https://linux-hardware.org/?probe=fb935ea1d0) | Jun 03, 2022 |
| ASUSTek       | M4A78-EM                    | Desktop     | [7bfddcecee](https://linux-hardware.org/?probe=7bfddcecee) | Jun 03, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [33201d3794](https://linux-hardware.org/?probe=33201d3794) | Jun 02, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [acc0a6ae9c](https://linux-hardware.org/?probe=acc0a6ae9c) | May 31, 2022 |
| Kraftway      | ACCORD                      | Notebook    | [bc4e085e40](https://linux-hardware.org/?probe=bc4e085e40) | May 31, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [4ad9ca01bd](https://linux-hardware.org/?probe=4ad9ca01bd) | May 31, 2022 |
| Panasonic     | CF-20-1                     | Notebook    | [a0a97f2bd1](https://linux-hardware.org/?probe=a0a97f2bd1) | May 27, 2022 |
| IP3 Techno... | APN23                       | Notebook    | [4395a91f24](https://linux-hardware.org/?probe=4395a91f24) | May 25, 2022 |
| IP3 Techno... | APN23                       | Notebook    | [281f1263dc](https://linux-hardware.org/?probe=281f1263dc) | May 25, 2022 |
| ASUSTek       | PRO H410T                   | Desktop     | [7d7a4c7536](https://linux-hardware.org/?probe=7d7a4c7536) | May 25, 2022 |
| ASUSTek       | M4A78-EM                    | Desktop     | [37a8e41d00](https://linux-hardware.org/?probe=37a8e41d00) | May 25, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [692cdfaf7e](https://linux-hardware.org/?probe=692cdfaf7e) | May 24, 2022 |
| Gigabyte      | EP45-UD3LR                  | Desktop     | [ea7f269697](https://linux-hardware.org/?probe=ea7f269697) | May 24, 2022 |
| ICL           | Unknown                     | Notebook    | [07ff87175d](https://linux-hardware.org/?probe=07ff87175d) | May 24, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [9450237ae3](https://linux-hardware.org/?probe=9450237ae3) | May 23, 2022 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [9fbbff1973](https://linux-hardware.org/?probe=9fbbff1973) | May 21, 2022 |
| MAINBRD       | OPS62A-SHA                  | Desktop     | [ad85836549](https://linux-hardware.org/?probe=ad85836549) | May 20, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [de4e9f2e03](https://linux-hardware.org/?probe=de4e9f2e03) | May 20, 2022 |
| Sony          | SVE1512H1RB                 | Notebook    | [3894ca4fe2](https://linux-hardware.org/?probe=3894ca4fe2) | May 19, 2022 |
| iRU           | LPGR.469559.012             | Desktop     | [9163b267bc](https://linux-hardware.org/?probe=9163b267bc) | May 19, 2022 |
| ICL           | H310SB-TM                   | All in one  | [72c2889a81](https://linux-hardware.org/?probe=72c2889a81) | May 18, 2022 |
| ICL           | NJ50_70CU                   | Notebook    | [c16ccbe95b](https://linux-hardware.org/?probe=c16ccbe95b) | May 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [f512156dc8](https://linux-hardware.org/?probe=f512156dc8) | May 16, 2022 |
| ASUSTek       | PRO H410T                   | Desktop     | [8ededa12ef](https://linux-hardware.org/?probe=8ededa12ef) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [6767fef6cf](https://linux-hardware.org/?probe=6767fef6cf) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [28c62dd04c](https://linux-hardware.org/?probe=28c62dd04c) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [f37b79c82d](https://linux-hardware.org/?probe=f37b79c82d) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [086e18d971](https://linux-hardware.org/?probe=086e18d971) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [75dc798956](https://linux-hardware.org/?probe=75dc798956) | May 16, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [6881a4923e](https://linux-hardware.org/?probe=6881a4923e) | May 16, 2022 |
| Sony          | SVE1512H1RB                 | Notebook    | [60dba4994d](https://linux-hardware.org/?probe=60dba4994d) | May 16, 2022 |
| ASUSTek       | M4A78-EM                    | Desktop     | [bedc08df5b](https://linux-hardware.org/?probe=bedc08df5b) | May 15, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ce128aaf56](https://linux-hardware.org/?probe=ce128aaf56) | May 15, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [b1ef2f3b4f](https://linux-hardware.org/?probe=b1ef2f3b4f) | May 12, 2022 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | Desktop     | [cfb12880a5](https://linux-hardware.org/?probe=cfb12880a5) | May 11, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [eb70f159f4](https://linux-hardware.org/?probe=eb70f159f4) | May 06, 2022 |
| Acer          | Aspire C27-1655             | All in one  | [96e5d68181](https://linux-hardware.org/?probe=96e5d68181) | May 06, 2022 |
| ASRock        | H61M-GE                     | Desktop     | [fefe67c0d4](https://linux-hardware.org/?probe=fefe67c0d4) | May 05, 2022 |
| ICL           | H310SB-TM                   | All in one  | [8aca897292](https://linux-hardware.org/?probe=8aca897292) | May 05, 2022 |
| Intel         | SKYBAY                      | Desktop     | [4891bdbd5c](https://linux-hardware.org/?probe=4891bdbd5c) | May 04, 2022 |
| ICL           | H310SB-TM                   | All in one  | [5e24e4a45d](https://linux-hardware.org/?probe=5e24e4a45d) | May 04, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [48af028244](https://linux-hardware.org/?probe=48af028244) | Apr 29, 2022 |
| Lenovo        | NOK                         | Desktop     | [4ea735896c](https://linux-hardware.org/?probe=4ea735896c) | Apr 28, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [c75ef7f42d](https://linux-hardware.org/?probe=c75ef7f42d) | Apr 28, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [af1b36d1f6](https://linux-hardware.org/?probe=af1b36d1f6) | Apr 28, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [9bf9254f54](https://linux-hardware.org/?probe=9bf9254f54) | Apr 28, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [e612a2bab1](https://linux-hardware.org/?probe=e612a2bab1) | Apr 27, 2022 |
| Lenovo        | NOK                         | Desktop     | [6d17068770](https://linux-hardware.org/?probe=6d17068770) | Apr 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [6c1227313d](https://linux-hardware.org/?probe=6c1227313d) | Apr 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [4f49f3d6c2](https://linux-hardware.org/?probe=4f49f3d6c2) | Apr 27, 2022 |
| ICL           | H310SB-TM                   | All in one  | [11db07be56](https://linux-hardware.org/?probe=11db07be56) | Apr 25, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [a1b9c91836](https://linux-hardware.org/?probe=a1b9c91836) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [f1e5d5715f](https://linux-hardware.org/?probe=f1e5d5715f) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [a0e3085b4c](https://linux-hardware.org/?probe=a0e3085b4c) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [9819b3fc78](https://linux-hardware.org/?probe=9819b3fc78) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [d27d03b7e4](https://linux-hardware.org/?probe=d27d03b7e4) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [a8784c861a](https://linux-hardware.org/?probe=a8784c861a) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [b970feef75](https://linux-hardware.org/?probe=b970feef75) | Apr 25, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [6bfffcf96a](https://linux-hardware.org/?probe=6bfffcf96a) | Apr 25, 2022 |
| Unknown       | Unknown                     | Desktop     | [c7c9ed4c0e](https://linux-hardware.org/?probe=c7c9ed4c0e) | Apr 21, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a58503065e](https://linux-hardware.org/?probe=a58503065e) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c9f37aca9b](https://linux-hardware.org/?probe=c9f37aca9b) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [4505d43267](https://linux-hardware.org/?probe=4505d43267) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [bc8b33e0d2](https://linux-hardware.org/?probe=bc8b33e0d2) | Apr 20, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [fa53bb24d9](https://linux-hardware.org/?probe=fa53bb24d9) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [9590ee5812](https://linux-hardware.org/?probe=9590ee5812) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [ccf6fb39e5](https://linux-hardware.org/?probe=ccf6fb39e5) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [ca58a7218c](https://linux-hardware.org/?probe=ca58a7218c) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [2da4cb3427](https://linux-hardware.org/?probe=2da4cb3427) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [77b103e672](https://linux-hardware.org/?probe=77b103e672) | Apr 19, 2022 |
| Intel         | SKYBAY                      | Desktop     | [ec99a4a73b](https://linux-hardware.org/?probe=ec99a4a73b) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [25b490f8a8](https://linux-hardware.org/?probe=25b490f8a8) | Apr 19, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [f31bad1291](https://linux-hardware.org/?probe=f31bad1291) | Apr 19, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [1f7e277528](https://linux-hardware.org/?probe=1f7e277528) | Apr 19, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e03dec259a](https://linux-hardware.org/?probe=e03dec259a) | Apr 19, 2022 |
| Intel         | SKYBAY                      | Desktop     | [807bf178aa](https://linux-hardware.org/?probe=807bf178aa) | Apr 19, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [651d569b66](https://linux-hardware.org/?probe=651d569b66) | Apr 18, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [b97ab9e5ca](https://linux-hardware.org/?probe=b97ab9e5ca) | Apr 18, 2022 |
| ICL           | H310SB-TM                   | All in one  | [75dab395ac](https://linux-hardware.org/?probe=75dab395ac) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [39189517e8](https://linux-hardware.org/?probe=39189517e8) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [d0a06db2b3](https://linux-hardware.org/?probe=d0a06db2b3) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [33a738be3b](https://linux-hardware.org/?probe=33a738be3b) | Apr 18, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [a5bb696691](https://linux-hardware.org/?probe=a5bb696691) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a6631d6c9a](https://linux-hardware.org/?probe=a6631d6c9a) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [7b60ea8e45](https://linux-hardware.org/?probe=7b60ea8e45) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [d78747839a](https://linux-hardware.org/?probe=d78747839a) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [faeb46556e](https://linux-hardware.org/?probe=faeb46556e) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [65fa83d729](https://linux-hardware.org/?probe=65fa83d729) | Apr 18, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [aa2de26f4f](https://linux-hardware.org/?probe=aa2de26f4f) | Apr 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [41a7060cbe](https://linux-hardware.org/?probe=41a7060cbe) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5ce5f89e30](https://linux-hardware.org/?probe=5ce5f89e30) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [016707b662](https://linux-hardware.org/?probe=016707b662) | Apr 18, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6225568c92](https://linux-hardware.org/?probe=6225568c92) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [1ec31e58eb](https://linux-hardware.org/?probe=1ec31e58eb) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [558e7d71c5](https://linux-hardware.org/?probe=558e7d71c5) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [58d8d12597](https://linux-hardware.org/?probe=58d8d12597) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [352ed8f1aa](https://linux-hardware.org/?probe=352ed8f1aa) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [f23db30412](https://linux-hardware.org/?probe=f23db30412) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [3fa8965015](https://linux-hardware.org/?probe=3fa8965015) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [287eb4cfbb](https://linux-hardware.org/?probe=287eb4cfbb) | Apr 18, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [8c69097ae0](https://linux-hardware.org/?probe=8c69097ae0) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [be57c6ecd1](https://linux-hardware.org/?probe=be57c6ecd1) | Apr 18, 2022 |
| Acer          | Veriton X2640G V:1.0        | Desktop     | [472e946f77](https://linux-hardware.org/?probe=472e946f77) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [9202f2e9ef](https://linux-hardware.org/?probe=9202f2e9ef) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [f51e697243](https://linux-hardware.org/?probe=f51e697243) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [7e24715646](https://linux-hardware.org/?probe=7e24715646) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f227fe1fc7](https://linux-hardware.org/?probe=f227fe1fc7) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [a739d61b7b](https://linux-hardware.org/?probe=a739d61b7b) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [86a59150d4](https://linux-hardware.org/?probe=86a59150d4) | Apr 18, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [e83eeef31e](https://linux-hardware.org/?probe=e83eeef31e) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [49039d6324](https://linux-hardware.org/?probe=49039d6324) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [39553516dd](https://linux-hardware.org/?probe=39553516dd) | Apr 18, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [a0246c4b50](https://linux-hardware.org/?probe=a0246c4b50) | Apr 18, 2022 |
| Intel         | SKYBAY                      | Desktop     | [9f87ee8978](https://linux-hardware.org/?probe=9f87ee8978) | Apr 18, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [bf274bc0f4](https://linux-hardware.org/?probe=bf274bc0f4) | Apr 15, 2022 |
| Timi          | TM1701                      | Notebook    | [1eb7df8700](https://linux-hardware.org/?probe=1eb7df8700) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [f9202afa63](https://linux-hardware.org/?probe=f9202afa63) | Apr 15, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [c5048041ee](https://linux-hardware.org/?probe=c5048041ee) | Apr 15, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [53137ae702](https://linux-hardware.org/?probe=53137ae702) | Apr 14, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [ee523553f4](https://linux-hardware.org/?probe=ee523553f4) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [efa4160e79](https://linux-hardware.org/?probe=efa4160e79) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [d2c072abdf](https://linux-hardware.org/?probe=d2c072abdf) | Apr 14, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [3cde2f0fd5](https://linux-hardware.org/?probe=3cde2f0fd5) | Apr 14, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [a98b8b4304](https://linux-hardware.org/?probe=a98b8b4304) | Apr 14, 2022 |
| Intel         | SKYBAY                      | Desktop     | [0d3978670a](https://linux-hardware.org/?probe=0d3978670a) | Apr 14, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [3829d7dfca](https://linux-hardware.org/?probe=3829d7dfca) | Apr 14, 2022 |
| Intel         | SKYBAY                      | Desktop     | [13122b16be](https://linux-hardware.org/?probe=13122b16be) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [86164212e5](https://linux-hardware.org/?probe=86164212e5) | Apr 14, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [37ebd7e15e](https://linux-hardware.org/?probe=37ebd7e15e) | Apr 14, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [567d83946c](https://linux-hardware.org/?probe=567d83946c) | Apr 13, 2022 |
| Dell          | Latitude 3420               | Notebook    | [f3278afeb0](https://linux-hardware.org/?probe=f3278afeb0) | Apr 13, 2022 |
| Dell          | Latitude 3420               | Notebook    | [2388ba39b8](https://linux-hardware.org/?probe=2388ba39b8) | Apr 13, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [87deb321d4](https://linux-hardware.org/?probe=87deb321d4) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [82df5d5154](https://linux-hardware.org/?probe=82df5d5154) | Apr 13, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [2b8e6fdd29](https://linux-hardware.org/?probe=2b8e6fdd29) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [c55e8d0780](https://linux-hardware.org/?probe=c55e8d0780) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [46344da31f](https://linux-hardware.org/?probe=46344da31f) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [906a9f0a46](https://linux-hardware.org/?probe=906a9f0a46) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [482922befd](https://linux-hardware.org/?probe=482922befd) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [2cb7352d17](https://linux-hardware.org/?probe=2cb7352d17) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [54f3bbf0af](https://linux-hardware.org/?probe=54f3bbf0af) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f7d3604a6b](https://linux-hardware.org/?probe=f7d3604a6b) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [40083e1990](https://linux-hardware.org/?probe=40083e1990) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [ecf34aa4f0](https://linux-hardware.org/?probe=ecf34aa4f0) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [c2e18d9346](https://linux-hardware.org/?probe=c2e18d9346) | Apr 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [0e2380e59d](https://linux-hardware.org/?probe=0e2380e59d) | Apr 13, 2022 |
| Intel         | SKYBAY                      | Desktop     | [baf8cdeb1a](https://linux-hardware.org/?probe=baf8cdeb1a) | Apr 13, 2022 |
| Gigabyte      | G31M-ES2L                   | Desktop     | [1eacb6915d](https://linux-hardware.org/?probe=1eacb6915d) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [84e70046d5](https://linux-hardware.org/?probe=84e70046d5) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [92f6d24bde](https://linux-hardware.org/?probe=92f6d24bde) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [8e924a50c1](https://linux-hardware.org/?probe=8e924a50c1) | Apr 12, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [0fecbe6cdc](https://linux-hardware.org/?probe=0fecbe6cdc) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [99d19658b8](https://linux-hardware.org/?probe=99d19658b8) | Apr 12, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [b6bcbc6a65](https://linux-hardware.org/?probe=b6bcbc6a65) | Apr 12, 2022 |
| Dell          | Latitude 3420               | Notebook    | [ecdf7b8de0](https://linux-hardware.org/?probe=ecdf7b8de0) | Apr 12, 2022 |
| Dell          | Latitude 3420               | Notebook    | [4361233072](https://linux-hardware.org/?probe=4361233072) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [19f3a71bf4](https://linux-hardware.org/?probe=19f3a71bf4) | Apr 12, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [0860ee5a64](https://linux-hardware.org/?probe=0860ee5a64) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [97d94278ea](https://linux-hardware.org/?probe=97d94278ea) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [4f1aa9470b](https://linux-hardware.org/?probe=4f1aa9470b) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [7537241f1d](https://linux-hardware.org/?probe=7537241f1d) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [d6792fe869](https://linux-hardware.org/?probe=d6792fe869) | Apr 12, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [e3236de077](https://linux-hardware.org/?probe=e3236de077) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5ebaca158a](https://linux-hardware.org/?probe=5ebaca158a) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [7e40f60767](https://linux-hardware.org/?probe=7e40f60767) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [ce83b095fe](https://linux-hardware.org/?probe=ce83b095fe) | Apr 12, 2022 |
| Lenovo        | 3145 No DPK                 | All in one  | [3e7d8951a2](https://linux-hardware.org/?probe=3e7d8951a2) | Apr 12, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [105088d6de](https://linux-hardware.org/?probe=105088d6de) | Apr 12, 2022 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [126b987221](https://linux-hardware.org/?probe=126b987221) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5d59afae00](https://linux-hardware.org/?probe=5d59afae00) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [442de26b34](https://linux-hardware.org/?probe=442de26b34) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [9d7fc26276](https://linux-hardware.org/?probe=9d7fc26276) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e07ab03ffb](https://linux-hardware.org/?probe=e07ab03ffb) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [b4b977309d](https://linux-hardware.org/?probe=b4b977309d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [bff39744bc](https://linux-hardware.org/?probe=bff39744bc) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [01cd534e80](https://linux-hardware.org/?probe=01cd534e80) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [2d62dd7b61](https://linux-hardware.org/?probe=2d62dd7b61) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [0eae0dfd04](https://linux-hardware.org/?probe=0eae0dfd04) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [669e6289c0](https://linux-hardware.org/?probe=669e6289c0) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d49df4c170](https://linux-hardware.org/?probe=d49df4c170) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [01aa1a4299](https://linux-hardware.org/?probe=01aa1a4299) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [65b8e561ab](https://linux-hardware.org/?probe=65b8e561ab) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [a85817bb6d](https://linux-hardware.org/?probe=a85817bb6d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [25955c9bb1](https://linux-hardware.org/?probe=25955c9bb1) | Apr 12, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [b95e628a8f](https://linux-hardware.org/?probe=b95e628a8f) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [0c81aeca67](https://linux-hardware.org/?probe=0c81aeca67) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e72fe0a0a9](https://linux-hardware.org/?probe=e72fe0a0a9) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [33b61b457e](https://linux-hardware.org/?probe=33b61b457e) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d6c6259cc0](https://linux-hardware.org/?probe=d6c6259cc0) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f2444b315d](https://linux-hardware.org/?probe=f2444b315d) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [aa745aba70](https://linux-hardware.org/?probe=aa745aba70) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [d05023771a](https://linux-hardware.org/?probe=d05023771a) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [655584ea45](https://linux-hardware.org/?probe=655584ea45) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [a6527519c6](https://linux-hardware.org/?probe=a6527519c6) | Apr 12, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [b6f41e002d](https://linux-hardware.org/?probe=b6f41e002d) | Apr 12, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [f8931a9e1e](https://linux-hardware.org/?probe=f8931a9e1e) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [3b73c79a3c](https://linux-hardware.org/?probe=3b73c79a3c) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d1a4cd1698](https://linux-hardware.org/?probe=d1a4cd1698) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [54713393ec](https://linux-hardware.org/?probe=54713393ec) | Apr 12, 2022 |
| Intel         | SKYBAY                      | Desktop     | [56d2022832](https://linux-hardware.org/?probe=56d2022832) | Apr 12, 2022 |
| Acer          | Aspire A514-52K             | Notebook    | [085e03c893](https://linux-hardware.org/?probe=085e03c893) | Apr 11, 2022 |
| Acer          | Aspire A514-52K             | Notebook    | [0157eea2f6](https://linux-hardware.org/?probe=0157eea2f6) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [71dfb9a346](https://linux-hardware.org/?probe=71dfb9a346) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [7cf5bcdb89](https://linux-hardware.org/?probe=7cf5bcdb89) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [efbe0a9eca](https://linux-hardware.org/?probe=efbe0a9eca) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [60fbf7929d](https://linux-hardware.org/?probe=60fbf7929d) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [6aaab98810](https://linux-hardware.org/?probe=6aaab98810) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e9a0bae6e6](https://linux-hardware.org/?probe=e9a0bae6e6) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [4fb63d6dfe](https://linux-hardware.org/?probe=4fb63d6dfe) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [dde0916ae5](https://linux-hardware.org/?probe=dde0916ae5) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [8ee5753b25](https://linux-hardware.org/?probe=8ee5753b25) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [6fb5a857e1](https://linux-hardware.org/?probe=6fb5a857e1) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [613ea0ab6b](https://linux-hardware.org/?probe=613ea0ab6b) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [2aeec4566f](https://linux-hardware.org/?probe=2aeec4566f) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [7289268e39](https://linux-hardware.org/?probe=7289268e39) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5751abaf6c](https://linux-hardware.org/?probe=5751abaf6c) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [31b40a1aa0](https://linux-hardware.org/?probe=31b40a1aa0) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d3bbe595ba](https://linux-hardware.org/?probe=d3bbe595ba) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [24d5b7f6c6](https://linux-hardware.org/?probe=24d5b7f6c6) | Apr 11, 2022 |
| Dell          | Latitude 3420               | Notebook    | [d436f78355](https://linux-hardware.org/?probe=d436f78355) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [f94dbbfc1f](https://linux-hardware.org/?probe=f94dbbfc1f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [960168908f](https://linux-hardware.org/?probe=960168908f) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [71610e6e10](https://linux-hardware.org/?probe=71610e6e10) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d2407bd778](https://linux-hardware.org/?probe=d2407bd778) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [88fc4d57ec](https://linux-hardware.org/?probe=88fc4d57ec) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [a1cbc192aa](https://linux-hardware.org/?probe=a1cbc192aa) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [66d94b1220](https://linux-hardware.org/?probe=66d94b1220) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [e8c2f02ba1](https://linux-hardware.org/?probe=e8c2f02ba1) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [7ef15ed6c9](https://linux-hardware.org/?probe=7ef15ed6c9) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [8bcad9c229](https://linux-hardware.org/?probe=8bcad9c229) | Apr 11, 2022 |
| Acer          | TravelMate 5760             | Notebook    | [958de67015](https://linux-hardware.org/?probe=958de67015) | Apr 11, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [a03ff53e01](https://linux-hardware.org/?probe=a03ff53e01) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [5486388fa0](https://linux-hardware.org/?probe=5486388fa0) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [68041f0a96](https://linux-hardware.org/?probe=68041f0a96) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [87858c448c](https://linux-hardware.org/?probe=87858c448c) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [a7e615a620](https://linux-hardware.org/?probe=a7e615a620) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [5b340e2b7f](https://linux-hardware.org/?probe=5b340e2b7f) | Apr 11, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [237634ce8d](https://linux-hardware.org/?probe=237634ce8d) | Apr 11, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [e027a7672d](https://linux-hardware.org/?probe=e027a7672d) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [83b01e222e](https://linux-hardware.org/?probe=83b01e222e) | Apr 11, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [5f90eb0f80](https://linux-hardware.org/?probe=5f90eb0f80) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [a20cfb8d86](https://linux-hardware.org/?probe=a20cfb8d86) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [c6f290816a](https://linux-hardware.org/?probe=c6f290816a) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [60c4fc315b](https://linux-hardware.org/?probe=60c4fc315b) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [faad64ac67](https://linux-hardware.org/?probe=faad64ac67) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [19d0ee846e](https://linux-hardware.org/?probe=19d0ee846e) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [9e2f7749b8](https://linux-hardware.org/?probe=9e2f7749b8) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [f3fe662dcb](https://linux-hardware.org/?probe=f3fe662dcb) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [5293db1b11](https://linux-hardware.org/?probe=5293db1b11) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [7d3b364ff0](https://linux-hardware.org/?probe=7d3b364ff0) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d8307a4138](https://linux-hardware.org/?probe=d8307a4138) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [bffde28b59](https://linux-hardware.org/?probe=bffde28b59) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7d31dd74d7](https://linux-hardware.org/?probe=7d31dd74d7) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7d03a291a2](https://linux-hardware.org/?probe=7d03a291a2) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [91f33b247d](https://linux-hardware.org/?probe=91f33b247d) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [2628069096](https://linux-hardware.org/?probe=2628069096) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [7c2a257e92](https://linux-hardware.org/?probe=7c2a257e92) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [868b030342](https://linux-hardware.org/?probe=868b030342) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [4088112a18](https://linux-hardware.org/?probe=4088112a18) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [68820282cb](https://linux-hardware.org/?probe=68820282cb) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [5a5a1a7ae6](https://linux-hardware.org/?probe=5a5a1a7ae6) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [936252dfca](https://linux-hardware.org/?probe=936252dfca) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [67ed2ddd29](https://linux-hardware.org/?probe=67ed2ddd29) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [fde95ea3ed](https://linux-hardware.org/?probe=fde95ea3ed) | Apr 11, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5dbdb89f95](https://linux-hardware.org/?probe=5dbdb89f95) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [de01821ecf](https://linux-hardware.org/?probe=de01821ecf) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [67f41bf764](https://linux-hardware.org/?probe=67f41bf764) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [77aadf6511](https://linux-hardware.org/?probe=77aadf6511) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [cb9ae4e880](https://linux-hardware.org/?probe=cb9ae4e880) | Apr 11, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [0199b0b388](https://linux-hardware.org/?probe=0199b0b388) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [d2a24f0327](https://linux-hardware.org/?probe=d2a24f0327) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [498dd8c409](https://linux-hardware.org/?probe=498dd8c409) | Apr 11, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [a473baa2ff](https://linux-hardware.org/?probe=a473baa2ff) | Apr 11, 2022 |
| Acer          | Veriton Z4820G              | All in one  | [12009b21d8](https://linux-hardware.org/?probe=12009b21d8) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [fa2978c8db](https://linux-hardware.org/?probe=fa2978c8db) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [150ce1c4dd](https://linux-hardware.org/?probe=150ce1c4dd) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [76e9ddaa30](https://linux-hardware.org/?probe=76e9ddaa30) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [43c08af7bf](https://linux-hardware.org/?probe=43c08af7bf) | Apr 11, 2022 |
| Intel         | SKYBAY                      | Desktop     | [093a6488c3](https://linux-hardware.org/?probe=093a6488c3) | Apr 11, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [730280aef1](https://linux-hardware.org/?probe=730280aef1) | Apr 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [3f2bf77788](https://linux-hardware.org/?probe=3f2bf77788) | Apr 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [679df55359](https://linux-hardware.org/?probe=679df55359) | Apr 06, 2022 |
| Unknown       | S074VI5R8                   | Desktop     | [3fd567de05](https://linux-hardware.org/?probe=3fd567de05) | Apr 06, 2022 |
| 3Logic Gro... | DMB-H510-MCA01              | Desktop     | [7e10ceda79](https://linux-hardware.org/?probe=7e10ceda79) | Apr 06, 2022 |
| Acer          | Aspire 5745G                | Notebook    | [4a6e981204](https://linux-hardware.org/?probe=4a6e981204) | Apr 04, 2022 |
| Lenovo        | V510-15IKB 80WQ             | Notebook    | [dfdb44695a](https://linux-hardware.org/?probe=dfdb44695a) | Apr 01, 2022 |
| HP            | Unknown                     | Notebook    | [e989736b06](https://linux-hardware.org/?probe=e989736b06) | Mar 30, 2022 |
| HP            | Unknown                     | Notebook    | [672d3c8b62](https://linux-hardware.org/?probe=672d3c8b62) | Mar 29, 2022 |
| ASRock        | M3N78D FX                   | Desktop     | [66bb134c6c](https://linux-hardware.org/?probe=66bb134c6c) | Mar 29, 2022 |
| HP            | 250 G3                      | Notebook    | [22f691edac](https://linux-hardware.org/?probe=22f691edac) | Mar 29, 2022 |
| ASRock        | N68-GS4 FX R2.0             | Desktop     | [d01df98d83](https://linux-hardware.org/?probe=d01df98d83) | Mar 28, 2022 |
| ASRock        | M3N78D FX                   | Desktop     | [3ebcef4241](https://linux-hardware.org/?probe=3ebcef4241) | Mar 28, 2022 |
| Unknown       | Unknown                     | Desktop     | [95628eab40](https://linux-hardware.org/?probe=95628eab40) | Mar 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e4b8a2cc11](https://linux-hardware.org/?probe=e4b8a2cc11) | Mar 23, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [64baae5b88](https://linux-hardware.org/?probe=64baae5b88) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | Notebook    | [247859eb78](https://linux-hardware.org/?probe=247859eb78) | Mar 22, 2022 |
| ICL           | NJ50_70CU                   | Notebook    | [b9e82b8490](https://linux-hardware.org/?probe=b9e82b8490) | Mar 22, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [1fb2262bcc](https://linux-hardware.org/?probe=1fb2262bcc) | Mar 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [58fdf49095](https://linux-hardware.org/?probe=58fdf49095) | Mar 17, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [eaa9fb6aad](https://linux-hardware.org/?probe=eaa9fb6aad) | Mar 14, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | Notebook    | [72eefd2811](https://linux-hardware.org/?probe=72eefd2811) | Mar 14, 2022 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | All in one  | [83881d4eb6](https://linux-hardware.org/?probe=83881d4eb6) | Mar 11, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [2379c7546f](https://linux-hardware.org/?probe=2379c7546f) | Mar 09, 2022 |
| Gigabyte      | G41MT-D3                    | Desktop     | [92fc99440a](https://linux-hardware.org/?probe=92fc99440a) | Mar 08, 2022 |
| Dell          | G5 5590                     | Notebook    | [9b95f2ae1d](https://linux-hardware.org/?probe=9b95f2ae1d) | Mar 06, 2022 |
| 3Logic Gro... | DMB-H310-TMI01              | All in one  | [4f93db2c52](https://linux-hardware.org/?probe=4f93db2c52) | Mar 05, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [13bc7e73f1](https://linux-hardware.org/?probe=13bc7e73f1) | Mar 02, 2022 |
| 3Logic Gro... | AMUR DMB-H310-MCA01         | All in one  | [04a1a09e43](https://linux-hardware.org/?probe=04a1a09e43) | Feb 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ef592cb1a7](https://linux-hardware.org/?probe=ef592cb1a7) | Feb 26, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c907453bf5](https://linux-hardware.org/?probe=c907453bf5) | Feb 18, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [f7f470651e](https://linux-hardware.org/?probe=f7f470651e) | Feb 17, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [3986a62bca](https://linux-hardware.org/?probe=3986a62bca) | Feb 15, 2022 |
| Gigabyte      | X79-UD3                     | Desktop     | [452ebf6a67](https://linux-hardware.org/?probe=452ebf6a67) | Feb 12, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [921e224ec5](https://linux-hardware.org/?probe=921e224ec5) | Feb 12, 2022 |
| ASUSTek       | X200MA                      | Notebook    | [b2f1d59884](https://linux-hardware.org/?probe=b2f1d59884) | Feb 12, 2022 |
| Timi          | TM1701                      | Notebook    | [4edeb14964](https://linux-hardware.org/?probe=4edeb14964) | Feb 05, 2022 |
| DEPO Compu... | DPC156                      | Notebook    | [4fb49336e5](https://linux-hardware.org/?probe=4fb49336e5) | Feb 03, 2022 |
| T-Platform... | TF307-MB                    | Soc         | [c34cd190e4](https://linux-hardware.org/?probe=c34cd190e4) | Feb 01, 2022 |
| Aquarius      | AQH410T                     | Desktop     | [351b2e5344](https://linux-hardware.org/?probe=351b2e5344) | Jan 31, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [481e745592](https://linux-hardware.org/?probe=481e745592) | Jan 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [a08b9de6fa](https://linux-hardware.org/?probe=a08b9de6fa) | Jan 28, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [8c31667834](https://linux-hardware.org/?probe=8c31667834) | Jan 20, 2022 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [edd6464f18](https://linux-hardware.org/?probe=edd6464f18) | Jan 19, 2022 |
| Graviton      | DMB-A520-MCA01              | Desktop     | [93fef2e073](https://linux-hardware.org/?probe=93fef2e073) | Jan 19, 2022 |
| Dell          | Latitude 3590               | Notebook    | [e2a6ef3266](https://linux-hardware.org/?probe=e2a6ef3266) | Jan 18, 2022 |
| MSI           | MS-AC16 100                 | All in one  | [3a3bfc48f7](https://linux-hardware.org/?probe=3a3bfc48f7) | Jan 17, 2022 |
| MSI           | A68HM-P33 V2                | Desktop     | [98e05db690](https://linux-hardware.org/?probe=98e05db690) | Jan 17, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [0c802de596](https://linux-hardware.org/?probe=0c802de596) | Jan 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [00f8c9d649](https://linux-hardware.org/?probe=00f8c9d649) | Jan 02, 2022 |
| Gigabyte      | H77M-D3H                    | Desktop     | [c8ff16f0ed](https://linux-hardware.org/?probe=c8ff16f0ed) | Dec 24, 2021 |
| Supermicro    | X11SDW-14CNT-TP13F          | Desktop     | [4d8499f8ba](https://linux-hardware.org/?probe=4d8499f8ba) | Dec 23, 2021 |
| Supermicro    | X10SDV-TP8F                 | Server      | [adc426b903](https://linux-hardware.org/?probe=adc426b903) | Dec 23, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [9180a824d8](https://linux-hardware.org/?probe=9180a824d8) | Dec 23, 2021 |
| Samsung       | 750XDA                      | Notebook    | [8fe8612ccb](https://linux-hardware.org/?probe=8fe8612ccb) | Dec 21, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [58cdbcf87e](https://linux-hardware.org/?probe=58cdbcf87e) | Dec 18, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [7ef05a32a9](https://linux-hardware.org/?probe=7ef05a32a9) | Dec 17, 2021 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [2aff2121af](https://linux-hardware.org/?probe=2aff2121af) | Dec 16, 2021 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [30eab5f54f](https://linux-hardware.org/?probe=30eab5f54f) | Dec 15, 2021 |
| Unknown       | Baikal Electronics Baika... | Soc         | [b4e6606b42](https://linux-hardware.org/?probe=b4e6606b42) | Dec 10, 2021 |
| Gigabyte      | B550 GAMING X               | Desktop     | [c853f62ddd](https://linux-hardware.org/?probe=c853f62ddd) | Dec 06, 2021 |
| Unknown       | Unknown                     | Desktop     | [0f5c69902a](https://linux-hardware.org/?probe=0f5c69902a) | Dec 01, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [68a1f83b4f](https://linux-hardware.org/?probe=68a1f83b4f) | Nov 28, 2021 |
| Gigabyte      | B550 GAMING X               | Desktop     | [058d8a0404](https://linux-hardware.org/?probe=058d8a0404) | Nov 19, 2021 |
| ASUSTek       | P5Q                         | Desktop     | [70ee05a53e](https://linux-hardware.org/?probe=70ee05a53e) | Oct 28, 2021 |
| HUAWEI        | BC11SPSCB0 V100R005         | Server      | [ad903545ce](https://linux-hardware.org/?probe=ad903545ce) | Oct 14, 2021 |
| ASUSTek       | N46VZ                       | Notebook    | [aaf9eff6bd](https://linux-hardware.org/?probe=aaf9eff6bd) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [2839eb3d12](https://linux-hardware.org/?probe=2839eb3d12) | Oct 09, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d9dd1b763b](https://linux-hardware.org/?probe=d9dd1b763b) | Oct 08, 2021 |
| Dell          | 0U649C                      | Desktop     | [80e138d949](https://linux-hardware.org/?probe=80e138d949) | Sep 24, 2021 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [516882d907](https://linux-hardware.org/?probe=516882d907) | Sep 23, 2021 |
| Edelweiss     | TF307-MB-S-D                | Soc         | [92829c951d](https://linux-hardware.org/?probe=92829c951d) | Sep 21, 2021 |
| ASRock        | X300M-STX                   | Desktop     | [da7d22c384](https://linux-hardware.org/?probe=da7d22c384) | Sep 16, 2021 |
| Timi          | TM1701                      | Notebook    | [b13b26d7ca](https://linux-hardware.org/?probe=b13b26d7ca) | Sep 16, 2021 |
| ASUSTek       | N46VZ                       | Notebook    | [40c97b439e](https://linux-hardware.org/?probe=40c97b439e) | Sep 12, 2021 |
| Acer          | Aspire A317-32              | Notebook    | [09342414f3](https://linux-hardware.org/?probe=09342414f3) | Sep 09, 2021 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [6648ff785e](https://linux-hardware.org/?probe=6648ff785e) | Sep 08, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [132286ab64](https://linux-hardware.org/?probe=132286ab64) | Aug 17, 2021 |
| Gigabyte      | H77M-D3H                    | Desktop     | [85ce2f74c4](https://linux-hardware.org/?probe=85ce2f74c4) | Aug 17, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [624e92e15e](https://linux-hardware.org/?probe=624e92e15e) | Aug 11, 2021 |
| ASUSTek       | N46VZ                       | Notebook    | [eb37b7db1e](https://linux-hardware.org/?probe=eb37b7db1e) | Aug 11, 2021 |
| Acer          | Swift SF314-57              | Notebook    | [2872bd6b13](https://linux-hardware.org/?probe=2872bd6b13) | Aug 05, 2021 |
| Gigabyte      | H510M S2H                   | Desktop     | [db68dde16d](https://linux-hardware.org/?probe=db68dde16d) | Aug 04, 2021 |
| Durabook      | Z14                         | Notebook    | [7abdb375e2](https://linux-hardware.org/?probe=7abdb375e2) | Jul 27, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [b01641d467](https://linux-hardware.org/?probe=b01641d467) | Jul 25, 2021 |
| Aquarius      | NS483                       | Convertible | [bc5d045def](https://linux-hardware.org/?probe=bc5d045def) | Jul 20, 2021 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [8687a8809b](https://linux-hardware.org/?probe=8687a8809b) | Jul 14, 2021 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | Notebook    | [a85464aae6](https://linux-hardware.org/?probe=a85464aae6) | Jul 06, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | Desktop     | [05be9fcdec](https://linux-hardware.org/?probe=05be9fcdec) | Jul 03, 2021 |
| Aquarius      | NS585                       | Notebook    | [bc10f2ffbd](https://linux-hardware.org/?probe=bc10f2ffbd) | Jun 27, 2021 |
| Gigabyte      | H110M-S2V-CF                | Desktop     | [24bd5ac93f](https://linux-hardware.org/?probe=24bd5ac93f) | Jun 27, 2021 |
| Kraftway      | KWH310                      | Desktop     | [f470a86a1c](https://linux-hardware.org/?probe=f470a86a1c) | Jun 26, 2021 |
| ASRock        | H110M-DGS R3.0              | Desktop     | [87ab7018c4](https://linux-hardware.org/?probe=87ab7018c4) | Jun 24, 2021 |
| Edelweiss     | TF307-MB-S-D                | Soc         | [d31e4518a6](https://linux-hardware.org/?probe=d31e4518a6) | Jun 22, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [21a019dcb3](https://linux-hardware.org/?probe=21a019dcb3) | Jun 14, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | Desktop     | [8325754280](https://linux-hardware.org/?probe=8325754280) | Jun 13, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [96cc5b470f](https://linux-hardware.org/?probe=96cc5b470f) | Jun 12, 2021 |
| MSI           | H110M PRO-VD                | Desktop     | [cfeb0493d3](https://linux-hardware.org/?probe=cfeb0493d3) | Jun 11, 2021 |
| Dell          | G3 3779                     | Notebook    | [eaf53820e5](https://linux-hardware.org/?probe=eaf53820e5) | Jun 02, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9908ba82e9](https://linux-hardware.org/?probe=9908ba82e9) | May 31, 2021 |
| Lenovo        | ThinkPad L13 Gen 2 20VH0... | Notebook    | [9f3a13c865](https://linux-hardware.org/?probe=9f3a13c865) | May 27, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [a3f263e12b](https://linux-hardware.org/?probe=a3f263e12b) | May 26, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [e1a816cc42](https://linux-hardware.org/?probe=e1a816cc42) | May 25, 2021 |
| MSI           | GE72 7RE                    | Notebook    | [a6a5258971](https://linux-hardware.org/?probe=a6a5258971) | May 20, 2021 |
| ASRock        | J3455B-ITX                  | Desktop     | [13396a7347](https://linux-hardware.org/?probe=13396a7347) | May 19, 2021 |
| DEPO Compu... | T09-D                       | Stick pc    | [678542f4fe](https://linux-hardware.org/?probe=678542f4fe) | May 18, 2021 |
| DEPO Compu... | DPH410S                     | Desktop     | [0d1000e904](https://linux-hardware.org/?probe=0d1000e904) | May 14, 2021 |
| DEPO Compu... | DPA320S G10g                | Desktop     | [5ecc011c34](https://linux-hardware.org/?probe=5ecc011c34) | May 14, 2021 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [59740e6ccf](https://linux-hardware.org/?probe=59740e6ccf) | Apr 29, 2021 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | Desktop     | [97b70c1bac](https://linux-hardware.org/?probe=97b70c1bac) | Apr 17, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [632deaf397](https://linux-hardware.org/?probe=632deaf397) | Apr 16, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [8185306af7](https://linux-hardware.org/?probe=8185306af7) | Apr 16, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ea2ab7cbc7](https://linux-hardware.org/?probe=ea2ab7cbc7) | Apr 07, 2021 |
| Lenovo        | 3184 No DPK                 | All in one  | [bd5551c49a](https://linux-hardware.org/?probe=bd5551c49a) | Mar 31, 2021 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [34997240d5](https://linux-hardware.org/?probe=34997240d5) | Mar 30, 2021 |
| ECS           | BAT-I2                      | Desktop     | [037e6e58e6](https://linux-hardware.org/?probe=037e6e58e6) | Mar 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3afcb7ca65](https://linux-hardware.org/?probe=3afcb7ca65) | Mar 29, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [f0c7659cf9](https://linux-hardware.org/?probe=f0c7659cf9) | Mar 29, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [66f3887fa2](https://linux-hardware.org/?probe=66f3887fa2) | Mar 20, 2021 |
| Gigabyte      | P35-S3G                     | Desktop     | [8e53d68603](https://linux-hardware.org/?probe=8e53d68603) | Mar 20, 2021 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [2c576fb8a9](https://linux-hardware.org/?probe=2c576fb8a9) | Mar 17, 2021 |
| ASUSTek       | N3150M-E                    | Desktop     | [7467b59c82](https://linux-hardware.org/?probe=7467b59c82) | Mar 17, 2021 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [c62af0239b](https://linux-hardware.org/?probe=c62af0239b) | Mar 17, 2021 |
| iRU           | IRUB365M                    | Desktop     | [b7d5dda036](https://linux-hardware.org/?probe=b7d5dda036) | Mar 11, 2021 |
| Dell          | 04G47W A00                  | All in one  | [3a565370de](https://linux-hardware.org/?probe=3a565370de) | Feb 15, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [2d8bd02af5](https://linux-hardware.org/?probe=2d8bd02af5) | Feb 09, 2021 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [6651c76da3](https://linux-hardware.org/?probe=6651c76da3) | Feb 07, 2021 |
| Gigabyte      | GA-MA69VM-S2                | Desktop     | [d63a1e9eef](https://linux-hardware.org/?probe=d63a1e9eef) | Feb 02, 2021 |
| ASUSTek       | P5B                         | Desktop     | [e0fc318a34](https://linux-hardware.org/?probe=e0fc318a34) | Jan 28, 2021 |
| Supermicro    | X11DPH-i                    | Server      | [8d109ac7b4](https://linux-hardware.org/?probe=8d109ac7b4) | Jan 26, 2021 |
| EPoX Compu... | GeForce6100 + nForce410 ... | Desktop     | [99f734d52e](https://linux-hardware.org/?probe=99f734d52e) | Jan 18, 2021 |
| Lenovo        | B50-10 80QR                 | Notebook    | [211bf1a4b4](https://linux-hardware.org/?probe=211bf1a4b4) | Jan 15, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [38ae5dd532](https://linux-hardware.org/?probe=38ae5dd532) | Jan 14, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [593a489e8d](https://linux-hardware.org/?probe=593a489e8d) | Jan 13, 2021 |
| Intel         | B75                         | Desktop     | [34d29fb066](https://linux-hardware.org/?probe=34d29fb066) | Jan 12, 2021 |
| Acer          | NC-ES1-131-C1NL             | Notebook    | [1cae46f14f](https://linux-hardware.org/?probe=1cae46f14f) | Jan 09, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [2c49129777](https://linux-hardware.org/?probe=2c49129777) | Jan 09, 2021 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [2437a45956](https://linux-hardware.org/?probe=2437a45956) | Jan 07, 2021 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [31d84f6485](https://linux-hardware.org/?probe=31d84f6485) | Dec 31, 2020 |
| Irbis         | TW100                       | Tablet      | [23c593482c](https://linux-hardware.org/?probe=23c593482c) | Dec 28, 2020 |
| SYS           | H310SB                      | Desktop     | [ba93a151f2](https://linux-hardware.org/?probe=ba93a151f2) | Dec 24, 2020 |
| HP            | 877E A                      | Desktop     | [4456ec4081](https://linux-hardware.org/?probe=4456ec4081) | Dec 23, 2020 |
| MSI           | MS-AC16 100                 | All in one  | [8df63d744b](https://linux-hardware.org/?probe=8df63d744b) | Dec 23, 2020 |
| HP            | 877E A                      | Desktop     | [145b54d631](https://linux-hardware.org/?probe=145b54d631) | Dec 23, 2020 |
| VIA Techno... | P4M266A-8235                | Desktop     | [c560d2aa9b](https://linux-hardware.org/?probe=c560d2aa9b) | Dec 23, 2020 |
| VIA Techno... | P4M266A-8235                | Desktop     | [8286c6ca5c](https://linux-hardware.org/?probe=8286c6ca5c) | Dec 23, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [ed90389918](https://linux-hardware.org/?probe=ed90389918) | Dec 22, 2020 |
| Lenovo        | ThinkPad X220 4291M85       | Notebook    | [f2c165b2d8](https://linux-hardware.org/?probe=f2c165b2d8) | Dec 22, 2020 |
| ASUSTek       | X510UNR                     | Notebook    | [53ef89172e](https://linux-hardware.org/?probe=53ef89172e) | Dec 21, 2020 |
| Irbis         | TW100                       | Tablet      | [5ebe1b6e89](https://linux-hardware.org/?probe=5ebe1b6e89) | Dec 19, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [dbc40fef9d](https://linux-hardware.org/?probe=dbc40fef9d) | Dec 18, 2020 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [bb4bd8f82f](https://linux-hardware.org/?probe=bb4bd8f82f) | Dec 09, 2020 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5cf089cfa1](https://linux-hardware.org/?probe=5cf089cfa1) | Dec 07, 2020 |
| ASRock        | X299 Steel Legend           | Desktop     | [fdfcfb17c6](https://linux-hardware.org/?probe=fdfcfb17c6) | Dec 03, 2020 |
| ASRock        | X299 Steel Legend           | Desktop     | [98800b881c](https://linux-hardware.org/?probe=98800b881c) | Dec 03, 2020 |
| Gigabyte      | H310N x.x                   | Desktop     | [b0ca19ee36](https://linux-hardware.org/?probe=b0ca19ee36) | Dec 02, 2020 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [4ec24e5c24](https://linux-hardware.org/?probe=4ec24e5c24) | Nov 27, 2020 |
| ASUSTek       | Z8NR-D12                    | Desktop     | [2758f1ff94](https://linux-hardware.org/?probe=2758f1ff94) | Nov 21, 2020 |
| Acer          | Veriton Z4860G              | All in one  | [8adebb44d3](https://linux-hardware.org/?probe=8adebb44d3) | Nov 20, 2020 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [00824d4fae](https://linux-hardware.org/?probe=00824d4fae) | Nov 19, 2020 |
| iRU           | IRUB365M                    | Desktop     | [ab7e110c9a](https://linux-hardware.org/?probe=ab7e110c9a) | Nov 17, 2020 |
| HP            | Laptop 14s-dq1xxx           | Notebook    | [f6e0ab4b2b](https://linux-hardware.org/?probe=f6e0ab4b2b) | Nov 13, 2020 |
| iRU           | IRUB365M                    | Desktop     | [ed5fee32dd](https://linux-hardware.org/?probe=ed5fee32dd) | Nov 13, 2020 |
| Gigabyte      | H77M-D3H                    | Desktop     | [c878b046bc](https://linux-hardware.org/?probe=c878b046bc) | Nov 13, 2020 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [5ad12e4b3b](https://linux-hardware.org/?probe=5ad12e4b3b) | Nov 12, 2020 |
| Toshiba       | Satellite A100              | Notebook    | [f09cd03fff](https://linux-hardware.org/?probe=f09cd03fff) | Nov 09, 2020 |
| Gigabyte      | J1800N-D2H                  | Desktop     | [e25041fb04](https://linux-hardware.org/?probe=e25041fb04) | Nov 09, 2020 |
| ASUSTek       | A8N-E                       | Desktop     | [f716673893](https://linux-hardware.org/?probe=f716673893) | Oct 24, 2020 |
| ASUSTek       | P5B-MX                      | Desktop     | [0779d0f18c](https://linux-hardware.org/?probe=0779d0f18c) | Oct 24, 2020 |
| MSI           | X300/X340/X400 series       | Notebook    | [1fd45a8e47](https://linux-hardware.org/?probe=1fd45a8e47) | Oct 23, 2020 |
| Lenovo        | B50-10 80QR                 | Notebook    | [ae14993850](https://linux-hardware.org/?probe=ae14993850) | Sep 28, 2020 |
| ASUSTek       | N46VZ                       | Notebook    | [d1ba7fa191](https://linux-hardware.org/?probe=d1ba7fa191) | Sep 23, 2020 |
| ASUSTek       | N46VZ                       | Notebook    | [ee23f7cefc](https://linux-hardware.org/?probe=ee23f7cefc) | Sep 14, 2020 |
| Acer          | Aspire XC-885 V:1.1         | Desktop     | [f587011ab7](https://linux-hardware.org/?probe=f587011ab7) | Sep 10, 2020 |
| ASUSTek       | N46VZ                       | Notebook    | [52930a9597](https://linux-hardware.org/?probe=52930a9597) | Sep 03, 2020 |
| ASRock        | G31M-VS                     | Desktop     | [fb4e557598](https://linux-hardware.org/?probe=fb4e557598) | Aug 16, 2020 |
| ASRock        | 4CoreN73PV-HD720p           | Desktop     | [ac70970005](https://linux-hardware.org/?probe=ac70970005) | Aug 16, 2020 |
| ASUSTek       | N46VZ                       | Notebook    | [9998e51d1c](https://linux-hardware.org/?probe=9998e51d1c) | Aug 14, 2020 |
| Gigabyte      | EP35C-DS3R                  | Desktop     | [4c98d77a2f](https://linux-hardware.org/?probe=4c98d77a2f) | Aug 07, 2020 |
| Samsung       | R510/P510                   | Notebook    | [e20ff4ae24](https://linux-hardware.org/?probe=e20ff4ae24) | Jul 12, 2020 |
| Lenovo        | B50-10 80QR                 | Notebook    | [a50e0f999e](https://linux-hardware.org/?probe=a50e0f999e) | Jul 07, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [cee7ed2ce9](https://linux-hardware.org/?probe=cee7ed2ce9) | Jun 23, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [f31ffbf544](https://linux-hardware.org/?probe=f31ffbf544) | Jun 23, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [72c1d1ffca](https://linux-hardware.org/?probe=72c1d1ffca) | Jun 23, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [298376a45e](https://linux-hardware.org/?probe=298376a45e) | Jun 23, 2020 |
| Intel         | NUC5CPYB H61145-413         | Mini pc     | [b03abee3fb](https://linux-hardware.org/?probe=b03abee3fb) | Jun 12, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [70139de021](https://linux-hardware.org/?probe=70139de021) | Jun 10, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [ee83d50faa](https://linux-hardware.org/?probe=ee83d50faa) | Jun 10, 2020 |
| ASRock        | G31M-VS                     | Desktop     | [c4c8bad6ca](https://linux-hardware.org/?probe=c4c8bad6ca) | May 31, 2020 |
| HP            | 255 G2                      | Notebook    | [3d4e8b4672](https://linux-hardware.org/?probe=3d4e8b4672) | May 27, 2020 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [74899486ac](https://linux-hardware.org/?probe=74899486ac) | May 26, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [861b6c69a0](https://linux-hardware.org/?probe=861b6c69a0) | May 21, 2020 |
| Lenovo        | 7X99CTO1WW                  | Server      | [ae09cd2a40](https://linux-hardware.org/?probe=ae09cd2a40) | May 21, 2020 |
| ASUSTek       | PRIME B250-PRO              | Desktop     | [8dddac7046](https://linux-hardware.org/?probe=8dddac7046) | Mar 25, 2020 |
| Acer          | Aspire E1-571G              | Notebook    | [3290540c34](https://linux-hardware.org/?probe=3290540c34) | Mar 13, 2020 |
| Lenovo        | 3000 G430 4153/200          | Notebook    | [0315e41f8c](https://linux-hardware.org/?probe=0315e41f8c) | Dec 26, 2019 |
| Gigabyte      | H77M-D3H                    | Desktop     | [a644a3a3ad](https://linux-hardware.org/?probe=a644a3a3ad) | Nov 24, 2019 |
| HP            | Pavilion dv6700             | Notebook    | [1031d661db](https://linux-hardware.org/?probe=1031d661db) | Nov 24, 2019 |
| HP            | Pavilion dv6700             | Notebook    | [c2fc59b6de](https://linux-hardware.org/?probe=c2fc59b6de) | Nov 23, 2019 |
| ASUSTek       | N46VZ                       | Notebook    | [bee323a814](https://linux-hardware.org/?probe=bee323a814) | Oct 29, 2019 |
| eMachines     | eME728                      | Notebook    | [83010f511e](https://linux-hardware.org/?probe=83010f511e) | Oct 25, 2019 |
| ASUSTek       | X200MA                      | Notebook    | [595d1ddd1b](https://linux-hardware.org/?probe=595d1ddd1b) | Oct 25, 2019 |
| HP            | 09F0h                       | Desktop     | [7f6c26af5d](https://linux-hardware.org/?probe=7f6c26af5d) | Oct 25, 2019 |
| HUAWEI        | BC11HGSB0 V100R003          | Server      | [5eb4dfc951](https://linux-hardware.org/?probe=5eb4dfc951) | Oct 22, 2019 |
| Dell          | 0F96C8 A00                  | All in one  | [29d0ad2441](https://linux-hardware.org/?probe=29d0ad2441) | Oct 22, 2019 |
| MSI           | B350M PRO-VDH               | Desktop     | [525f09653e](https://linux-hardware.org/?probe=525f09653e) | Oct 08, 2019 |
| MSI           | MEGA BOOK S430              | Notebook    | [6380916978](https://linux-hardware.org/?probe=6380916978) | Sep 15, 2019 |
| Gigabyte      | GA-890XA-UD3                | Desktop     | [1536999c3e](https://linux-hardware.org/?probe=1536999c3e) | Sep 13, 2019 |
| ASRock        | Z77 Pro3                    | Desktop     | [a1db2eb143](https://linux-hardware.org/?probe=a1db2eb143) | Sep 13, 2019 |
| ASRock        | B85M                        | Desktop     | [5a36ce2620](https://linux-hardware.org/?probe=5a36ce2620) | Sep 13, 2019 |
| Lenovo        | G505s 20255                 | Notebook    | [46308d3b71](https://linux-hardware.org/?probe=46308d3b71) | Aug 30, 2019 |
| Lenovo        | G505s 20255                 | Notebook    | [c840002848](https://linux-hardware.org/?probe=c840002848) | Aug 30, 2019 |
| ASUSTek       | 1101HA                      | Notebook    | [f221bcd7e4](https://linux-hardware.org/?probe=f221bcd7e4) | Aug 16, 2019 |
| ASUSTek       | N46VZ                       | Notebook    | [aec6cff1b5](https://linux-hardware.org/?probe=aec6cff1b5) | Aug 15, 2019 |
| ASUSTek       | Z97-A                       | Desktop     | [68dbf33470](https://linux-hardware.org/?probe=68dbf33470) | Aug 03, 2019 |
| Samsung       | RV413/RV513/E3413           | Notebook    | [3e37ab573a](https://linux-hardware.org/?probe=3e37ab573a) | Apr 24, 2019 |
| Samsung       | RV413/RV513/E3413           | Notebook    | [447cdad389](https://linux-hardware.org/?probe=447cdad389) | Apr 23, 2019 |
| ASUSTek       | A8N-VM CSM                  | Desktop     | [5814b6a2af](https://linux-hardware.org/?probe=5814b6a2af) | Mar 28, 2019 |
| Acer          | Aspire ES1-523              | Notebook    | [0f6abd34f2](https://linux-hardware.org/?probe=0f6abd34f2) | Dec 17, 2018 |
| ASUSTek       | H110M-R                     | Desktop     | [34b40d93fc](https://linux-hardware.org/?probe=34b40d93fc) | Oct 30, 2018 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [d55532d7a9](https://linux-hardware.org/?probe=d55532d7a9) | Oct 29, 2018 |
| ASUSTek       | 1001PXD                     | Notebook    | [1a4aa87d78](https://linux-hardware.org/?probe=1a4aa87d78) | Oct 29, 2018 |
| Biostar       | NF720D A2G+                 | Desktop     | [ef09cb18cc](https://linux-hardware.org/?probe=ef09cb18cc) | Oct 29, 2018 |
| ASUSTek       | H110M-R                     | Desktop     | [572c918e8a](https://linux-hardware.org/?probe=572c918e8a) | Oct 27, 2018 |
| Acer          | Aspire ES1-523              | Notebook    | [5e9a049dce](https://linux-hardware.org/?probe=5e9a049dce) | Oct 08, 2018 |
| ASUSTek       | K52JT                       | Notebook    | [7fdee4e7bb](https://linux-hardware.org/?probe=7fdee4e7bb) | Jun 18, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ALT_Linux/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Kometa P10         | 165       | 33.2%   |
| ALT Linux 10.1     | 68        | 13.68%  |
| ALT Linux 9.1      | 65        | 13.08%  |
| ALT Linux 10.0     | 55        | 11.07%  |
| MOS 10             | 35        | 7.04%   |
| ALT Linux 9.0      | 31        | 6.24%   |
| ALT Linux 9.2      | 18        | 3.62%   |
| ALT Linux P10      | 10        | 2.01%   |
| ALT Linux 8.4      | 6         | 1.21%   |
| ALT Linux 10.0.900 | 6         | 1.21%   |
| ALT Linux P8       | 5         | 1.01%   |
| ALT Linux 8.2      | 5         | 1.01%   |
| ALT Linux P9       | 4         | 0.8%    |
| ALT Linux 20201124 | 3         | 0.6%    |
| ALT Linux 7.0.5    | 2         | 0.4%    |
| ALT Linux 20220110 | 2         | 0.4%    |
| ALT Linux 20191026 | 2         | 0.4%    |
| Kometa 1           | 1         | 0.2%    |
| ALT Linux 9.1.990  | 1         | 0.2%    |
| ALT Linux 9        | 1         | 0.2%    |
| ALT Linux 8.990    | 1         | 0.2%    |
| ALT Linux 8.93     | 1         | 0.2%    |
| ALT Linux 8.920    | 1         | 0.2%    |
| ALT Linux 8.3      | 1         | 0.2%    |
| ALT Linux 8.2.0    | 1         | 0.2%    |
| ALT Linux 8.0.0    | 1         | 0.2%    |
| ALT Linux 8.0      | 1         | 0.2%    |
| ALT Linux 20190624 | 1         | 0.2%    |
| ALT Linux 20190303 | 1         | 0.2%    |
| ALT Linux 10.0.920 | 1         | 0.2%    |
| ALT Linux 10.0.910 | 1         | 0.2%    |
| ALT Linux          | 1         | 0.2%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ALT Linux | 470       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                    | Computers | Percent |
|----------------------------|-----------|---------|
| 5.10.109-std-def-alt1      | 85        | 16.41%  |
| 5.10.102-std-def-alt1      | 79        | 15.25%  |
| 5.15.34-un-def-alt1        | 17        | 3.28%   |
| 5.10.82-std-def-alt1       | 15        | 2.9%    |
| 5.15.80-un-def-alt1        | 13        | 2.51%   |
| 5.10.156-std-def-alt1      | 13        | 2.51%   |
| 5.4.51-std-def-alt1        | 12        | 2.32%   |
| 4.19.79-std-def-alt1       | 11        | 2.12%   |
| 5.4.68-std-def-alt1.1      | 10        | 1.93%   |
| 5.10.88-std-def-alt1       | 10        | 1.93%   |
| 5.10.139-std-def-alt1      | 10        | 1.93%   |
| 5.10.123-std-def-alt1      | 8         | 1.54%   |
| 5.4.28-std-def-alt1        | 6         | 1.16%   |
| 5.15.72-un-def-alt1        | 6         | 1.16%   |
| 5.15.76-un-def-alt1        | 5         | 0.97%   |
| 5.15.32-un-def-alt1        | 5         | 0.97%   |
| 5.10.93-std-def-alt1       | 5         | 0.97%   |
| 5.10.32-un-def-alt1        | 5         | 0.97%   |
| 5.10.145-std-def-alt1      | 5         | 0.97%   |
| 5.7.19-un-def-alt1         | 4         | 0.77%   |
| 5.4.62-std-def-alt1        | 4         | 0.77%   |
| 5.4.41-std-def-alt1        | 4         | 0.77%   |
| 5.10.35-un-def-alt1        | 4         | 0.77%   |
| 5.10.17-un-def-alt1        | 4         | 0.77%   |
| 5.10.152-std-def-alt1      | 4         | 0.77%   |
| 5.4.85-std-def-alt1        | 3         | 0.58%   |
| 5.4.127-std-def-alt1       | 3         | 0.58%   |
| 5.15.79-un-def-alt1        | 3         | 0.58%   |
| 5.15.74-un-def-alt1        | 3         | 0.58%   |
| 5.15.73-un-def-alt1        | 3         | 0.58%   |
| 5.15.70-un-def-alt1        | 3         | 0.58%   |
| 5.15.63-un-def-alt1        | 3         | 0.58%   |
| 5.15.15-un-def-alt1        | 3         | 0.58%   |
| 5.10.83-std-def-alt0.c9f.2 | 3         | 0.58%   |
| 5.10.72-std-def-alt1       | 3         | 0.58%   |
| 5.10.118-std-def-alt1      | 3         | 0.58%   |
| 5.10.113-std-def-alt1      | 3         | 0.58%   |
| 5.10.111-std-def-alt1      | 3         | 0.58%   |
| 4.19.102-std-def-alt1      | 3         | 0.58%   |
| 5.4.181-std-def-alt1       | 2         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.109 | 85        | 16.41%  |
| 5.10.102 | 79        | 15.25%  |
| 5.15.34  | 17        | 3.28%   |
| 5.10.82  | 15        | 2.9%    |
| 5.15.80  | 14        | 2.7%    |
| 5.10.156 | 13        | 2.51%   |
| 5.4.51   | 12        | 2.32%   |
| 4.19.79  | 11        | 2.12%   |
| 5.4.68   | 10        | 1.93%   |
| 5.10.88  | 10        | 1.93%   |
| 5.10.139 | 10        | 1.93%   |
| 5.10.123 | 8         | 1.54%   |
| 5.4.28   | 6         | 1.16%   |
| 5.15.72  | 6         | 1.16%   |
| 5.15.76  | 5         | 0.97%   |
| 5.15.32  | 5         | 0.97%   |
| 5.10.93  | 5         | 0.97%   |
| 5.10.35  | 5         | 0.97%   |
| 5.10.32  | 5         | 0.97%   |
| 5.10.145 | 5         | 0.97%   |
| 5.7.19   | 4         | 0.77%   |
| 5.4.62   | 4         | 0.77%   |
| 5.4.41   | 4         | 0.77%   |
| 5.10.17  | 4         | 0.77%   |
| 5.10.152 | 4         | 0.77%   |
| 5.10.118 | 4         | 0.77%   |
| 5.4.85   | 3         | 0.58%   |
| 5.4.127  | 3         | 0.58%   |
| 5.15.79  | 3         | 0.58%   |
| 5.15.74  | 3         | 0.58%   |
| 5.15.73  | 3         | 0.58%   |
| 5.15.70  | 3         | 0.58%   |
| 5.15.63  | 3         | 0.58%   |
| 5.15.15  | 3         | 0.58%   |
| 5.10.83  | 3         | 0.58%   |
| 5.10.72  | 3         | 0.58%   |
| 5.10.54  | 3         | 0.58%   |
| 5.10.113 | 3         | 0.58%   |
| 5.10.111 | 3         | 0.58%   |
| 4.19.102 | 3         | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 294       | 60.37%  |
| 5.15    | 72        | 14.78%  |
| 5.4     | 64        | 13.14%  |
| 4.19    | 26        | 5.34%   |
| 4.9     | 7         | 1.44%   |
| 5.7     | 5         | 1.03%   |
| 5.2     | 3         | 0.62%   |
| 5.18    | 3         | 0.62%   |
| 5.13    | 3         | 0.62%   |
| 5.14    | 2         | 0.41%   |
| 4.14    | 2         | 0.41%   |
| 5.9     | 1         | 0.21%   |
| 5.3     | 1         | 0.21%   |
| 5.16    | 1         | 0.21%   |
| 5.12    | 1         | 0.21%   |
| 4.4     | 1         | 0.21%   |
| 4.20    | 1         | 0.21%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 448       | 95.32%  |
| i686    | 15        | 3.19%   |
| aarch64 | 4         | 0.85%   |
| e2k     | 3         | 0.64%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 319       | 66.6%   |
| XFCE            | 71        | 14.82%  |
| Unknown         | 66        | 13.78%  |
| LXQt            | 7         | 1.46%   |
| MATE            | 5         | 1.04%   |
| Cinnamon        | 5         | 1.04%   |
| GNOME           | 3         | 0.63%   |
| KDE             | 2         | 0.42%   |
| GNOME Flashback | 1         | 0.21%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 455       | 96.4%   |
| Unknown | 9         | 1.91%   |
| Tty     | 5         | 1.06%   |
| Wayland | 3         | 0.64%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 271       | 56.58%  |
| LightDM | 96        | 20.04%  |
| TDM     | 62        | 12.94%  |
| Unknown | 47        | 9.81%   |
| XDM     | 1         | 0.21%   |
| WDM     | 1         | 0.21%   |
| GDM     | 1         | 0.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| ru_RU      | 385       | 79.88%  |
| Unknown    | 76        | 15.77%  |
| en_US      | 13        | 2.7%    |
| POSIX      | 5         | 1.04%   |
| it_IT@euro | 1         | 0.21%   |
| el_GR      | 1         | 0.21%   |
| C          | 1         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 314       | 66.24%  |
| BIOS | 160       | 33.76%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 426       | 90.06%  |
| Overlay | 35        | 7.4%    |
| Btrfs   | 10        | 2.11%   |
| Unknown | 2         | 0.42%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 313       | 65.62%  |
| MBR     | 114       | 23.9%   |
| Unknown | 50        | 10.48%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 424       | 89.26%  |
| Yes       | 51        | 10.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 306       | 64.56%  |
| Yes       | 168       | 35.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 61        | 12.98%  |
| ASUSTek Computer        | 58        | 12.34%  |
| Intel                   | 51        | 10.85%  |
| Lenovo                  | 38        | 8.09%   |
| Gigabyte Technology     | 35        | 7.45%   |
| Acer                    | 33        | 7.02%   |
| 3Logic Group            | 26        | 5.53%   |
| ASRock                  | 19        | 4.04%   |
| MSI                     | 16        | 3.4%    |
| ICL                     | 15        | 3.19%   |
| Unknown                 | 15        | 3.19%   |
| Dell                    | 13        | 2.77%   |
| Clevo                   | 13        | 2.77%   |
| HUAWEI                  | 10        | 2.13%   |
| Samsung Electronics     | 6         | 1.28%   |
| DEPO Computers          | 6         | 1.28%   |
| Apple                   | 5         | 1.06%   |
| Supermicro              | 4         | 0.85%   |
| Aquarius                | 4         | 0.85%   |
| MAINBRD                 | 3         | 0.64%   |
| iRU                     | 3         | 0.64%   |
| Graviton                | 3         | 0.64%   |
| Toshiba                 | 2         | 0.43%   |
| Timi                    | 2         | 0.43%   |
| Panasonic               | 2         | 0.43%   |
| Kraftway                | 2         | 0.43%   |
| Irbis                   | 2         | 0.43%   |
| Biostar                 | 2         | 0.43%   |
| Yadro                   | 1         | 0.21%   |
| VIA Technologies        | 1         | 0.21%   |
| T-Platforms             | 1         | 0.21%   |
| SYS                     | 1         | 0.21%   |
| Sony                    | 1         | 0.21%   |
| Raspberry Pi Foundation | 1         | 0.21%   |
| Pegatron                | 1         | 0.21%   |
| OEM                     | 1         | 0.21%   |
| LTD Delovoy Office      | 1         | 0.21%   |
| IP3 Technology          | 1         | 0.21%   |
| IP3 Tech                | 1         | 0.21%   |
| Huanan                  | 1         | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Intel SKYBAY                              | 44        | 9.36%   |
| 3Logic Group Graviton                     | 20        | 4.26%   |
| Unknown                                   | 17        | 3.62%   |
| Clevo NL41MU2                             | 13        | 2.77%   |
| HP 250 G7 Notebook PC                     | 12        | 2.55%   |
| ASUS PRIME B450-PLUS                      | 12        | 2.55%   |
| Lenovo V540-24IWL AIO 10YS0031RU          | 10        | 2.13%   |
| Acer Veriton X2640G                       | 10        | 2.13%   |
| HP ZBook 17 G5                            | 9         | 1.91%   |
| HP ProBook 440 G5                         | 8         | 1.7%    |
| ICL RAYbook Si1512                        | 6         | 1.28%   |
| Lenovo ThinkSystem SR590 -[7X99CTO1WW]-   | 5         | 1.06%   |
| Gigabyte H110M-S2H                        | 4         | 0.85%   |
| MAINBRD OPS62A-SHA                        | 3         | 0.64%   |
| Lenovo ThinkBook 15 G2 ITL 20VE           | 3         | 0.64%   |
| ICL RAY S122.Mi                           | 3         | 0.64%   |
| HUAWEI NBD-WXX9                           | 3         | 0.64%   |
| HP EliteBook 840 G4                       | 3         | 0.64%   |
| HP 250 G6 Notebook PC                     | 3         | 0.64%   |
| DEPO Computers DPC156                     | 3         | 0.64%   |
| Dell Latitude 3420                        | 3         | 0.64%   |
| 3Logic Group Graviton N15i-K2             | 3         | 0.64%   |
| Supermicro Super Server                   | 2         | 0.43%   |
| MSI MS-7D46                               | 2         | 0.43%   |
| MSI MPG B560 Trident A (MS-B926)          | 2         | 0.43%   |
| Lenovo ThinkPad L13 Gen 2 20VH001WRT      | 2         | 0.43%   |
| iRU 515                                   | 2         | 0.43%   |
| Irbis TW100                               | 2         | 0.43%   |
| ICL RAY Si105.Mi                          | 2         | 0.43%   |
| ICL NJ50_70CU                             | 2         | 0.43%   |
| HUAWEI KLVL-WXXW                          | 2         | 0.43%   |
| HP ProBook 440 G4                         | 2         | 0.43%   |
| HP EliteBook 8470p                        | 2         | 0.43%   |
| Gigabyte H77M-D3H                         | 2         | 0.43%   |
| ASUS N46VZ                                | 2         | 0.43%   |
| ASUS H110M-R                              | 2         | 0.43%   |
| ASUS ASUS EXPERTBOOK B1500CEAEY_B1500CEAE | 2         | 0.43%   |
| ASRock B450M Pro4                         | 2         | 0.43%   |
| Apple MacBook7,1                          | 2         | 0.43%   |
| Acer Veriton Z4820G                       | 2         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Intel SKYBAY          | 44        | 9.36%   |
| 3Logic Group Graviton | 26        | 5.53%   |
| ASUS PRIME            | 17        | 3.62%   |
| Unknown               | 17        | 3.62%   |
| HP 250                | 16        | 3.4%    |
| Acer Veriton          | 15        | 3.19%   |
| Clevo NL41MU2         | 13        | 2.77%   |
| HP ProBook            | 12        | 2.55%   |
| Lenovo V540-24IWL     | 10        | 2.13%   |
| Acer Aspire           | 10        | 2.13%   |
| HP ZBook              | 9         | 1.91%   |
| HP Pavilion           | 7         | 1.49%   |
| ICL RAYbook           | 6         | 1.28%   |
| HP EliteBook          | 6         | 1.28%   |
| ASUS ASUS             | 6         | 1.28%   |
| Lenovo ThinkSystem    | 5         | 1.06%   |
| Lenovo IdeaPad        | 5         | 1.06%   |
| ICL RAY               | 5         | 1.06%   |
| Dell Latitude         | 5         | 1.06%   |
| Lenovo ThinkPad       | 4         | 0.85%   |
| HP Laptop             | 4         | 0.85%   |
| Gigabyte H110M-S2H    | 4         | 0.85%   |
| Dell OptiPlex         | 4         | 0.85%   |
| ASUS VivoBook         | 4         | 0.85%   |
| Acer TravelMate       | 4         | 0.85%   |
| MAINBRD OPS62A-SHA    | 3         | 0.64%   |
| Lenovo ThinkBook      | 3         | 0.64%   |
| HUAWEI NBD-WXX9       | 3         | 0.64%   |
| DEPO Computers DPC156 | 3         | 0.64%   |
| Supermicro Super      | 2         | 0.43%   |
| MSI MS-7D46           | 2         | 0.43%   |
| MSI MPG               | 2         | 0.43%   |
| iRU 515               | 2         | 0.43%   |
| Irbis TW100           | 2         | 0.43%   |
| ICL NJ50              | 2         | 0.43%   |
| HUAWEI KLVL-WXXW      | 2         | 0.43%   |
| HP 255                | 2         | 0.43%   |
| Gigabyte H77M-D3H     | 2         | 0.43%   |
| Gigabyte B550         | 2         | 0.43%   |
| Gigabyte B450         | 2         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 76        | 16.17%  |
| 2020    | 58        | 12.34%  |
| 2017    | 56        | 11.91%  |
| 2021    | 47        | 10%     |
| 2019    | 40        | 8.51%   |
| 2022    | 39        | 8.3%    |
| 2016    | 30        | 6.38%   |
| 2012    | 19        | 4.04%   |
| 2010    | 15        | 3.19%   |
| 2011    | 14        | 2.98%   |
| 2008    | 14        | 2.98%   |
| 2014    | 13        | 2.77%   |
| 2015    | 11        | 2.34%   |
| 2009    | 10        | 2.13%   |
| 2007    | 7         | 1.49%   |
| 2013    | 6         | 1.28%   |
| 2006    | 5         | 1.06%   |
| Unknown | 5         | 1.06%   |
| 2005    | 3         | 0.64%   |
| 2004    | 1         | 0.21%   |
| 2003    | 1         | 0.21%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Desktop        | 206       | 43.83%  |
| Notebook       | 198       | 42.13%  |
| All in one     | 45        | 9.57%   |
| Server         | 10        | 2.13%   |
| System on chip | 4         | 0.85%   |
| Tablet         | 2         | 0.43%   |
| Convertible    | 2         | 0.43%   |
| Mini pc        | 2         | 0.43%   |
| Stick pc       | 1         | 0.21%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 419       | 88.58%  |
| Enabled  | 54        | 11.42%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 470       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 170       | 36.09%  |
| 8.01-16.0       | 98        | 20.81%  |
| 16.01-24.0      | 80        | 16.99%  |
| 3.01-4.0        | 71        | 15.07%  |
| 1.01-2.0        | 19        | 4.03%   |
| 64.01-256.0     | 12        | 2.55%   |
| 32.01-64.0      | 9         | 1.91%   |
| 2.01-3.0        | 7         | 1.49%   |
| 0.51-1.0        | 3         | 0.64%   |
| More than 256.0 | 1         | 0.21%   |
| 24.01-32.0      | 1         | 0.21%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 249       | 50.2%   |
| 2.01-3.0   | 84        | 16.94%  |
| 0.51-1.0   | 73        | 14.72%  |
| 4.01-8.0   | 40        | 8.06%   |
| 3.01-4.0   | 34        | 6.85%   |
| 0.01-0.5   | 10        | 2.02%   |
| 8.01-16.0  | 5         | 1.01%   |
| 16.01-24.0 | 1         | 0.2%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 350       | 73.07%  |
| 2       | 86        | 17.95%  |
| 3       | 22        | 4.59%   |
| 4       | 8         | 1.67%   |
| 5       | 5         | 1.04%   |
| 0       | 4         | 0.84%   |
| 8       | 2         | 0.42%   |
| 6       | 1         | 0.21%   |
| Unknown | 1         | 0.21%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 317       | 67.02%  |
| Yes       | 156       | 32.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 435       | 92.55%  |
| No        | 35        | 7.45%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 284       | 60.43%  |
| No        | 186       | 39.57%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 237       | 50.21%  |
| No        | 235       | 49.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Computers | Percent |
|------------|-----------|---------|
| Russia     | 449       | 95.53%  |
| Greece     | 6         | 1.28%   |
| Ukraine    | 3         | 0.64%   |
| Egypt      | 2         | 0.43%   |
| Belarus    | 2         | 0.43%   |
| Uzbekistan | 1         | 0.21%   |
| Kazakhstan | 1         | 0.21%   |
| Italy      | 1         | 0.21%   |
| France     | 1         | 0.21%   |
| Czechia    | 1         | 0.21%   |
| Costa Rica | 1         | 0.21%   |
| Colombia   | 1         | 0.21%   |
| China      | 1         | 0.21%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 299       | 62.29%  |
| St Petersburg     | 28        | 5.83%   |
| Samara            | 11        | 2.29%   |
| Barnaul           | 8         | 1.67%   |
| Novosibirsk       | 5         | 1.04%   |
| Irkutsk           | 5         | 1.04%   |
| Yekaterinburg     | 4         | 0.83%   |
| Saratov           | 4         | 0.83%   |
| Perm              | 4         | 0.83%   |
| Obninsk           | 4         | 0.83%   |
| Chelyabinsk       | 4         | 0.83%   |
| Sevastopol        | 3         | 0.63%   |
| Rostov-on-Don     | 3         | 0.63%   |
| Krasnoyarsk       | 3         | 0.63%   |
| Korolyov          | 3         | 0.63%   |
| Kaliningrad       | 3         | 0.63%   |
| Belgorod          | 3         | 0.63%   |
| Astrakhan         | 3         | 0.63%   |
| Verkhnyaya Pyshma | 2         | 0.42%   |
| Vergina           | 2         | 0.42%   |
| Tyumen            | 2         | 0.42%   |
| Thessaloniki      | 2         | 0.42%   |
| Surgut            | 2         | 0.42%   |
| Nizhny Tagil      | 2         | 0.42%   |
| Krasnodar         | 2         | 0.42%   |
| Kostroma          | 2         | 0.42%   |
| Kirov             | 2         | 0.42%   |
| Kazan’          | 2         | 0.42%   |
| Zelenodolsk       | 1         | 0.21%   |
| Yessentuki        | 1         | 0.21%   |
| Voronezh          | 1         | 0.21%   |
| Vologda           | 1         | 0.21%   |
| Vladivostok       | 1         | 0.21%   |
| Vladimir          | 1         | 0.21%   |
| Vikhorevka        | 1         | 0.21%   |
| Valuyki           | 1         | 0.21%   |
| Ulyanovsk         | 1         | 0.21%   |
| Tula              | 1         | 0.21%   |
| Troitsk           | 1         | 0.21%   |
| Tolyatti          | 1         | 0.21%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 85        | 119    | 14.33%  |
| Seagate                     | 75        | 106    | 12.65%  |
| Samsung Electronics         | 63        | 80     | 10.62%  |
| Toshiba                     | 42        | 62     | 7.08%   |
| Kingston                    | 36        | 39     | 6.07%   |
| SK hynix                    | 28        | 30     | 4.72%   |
| Intel                       | 27        | 35     | 4.55%   |
| AXIOMTEK                    | 26        | 28     | 4.38%   |
| Apacer                      | 26        | 29     | 4.38%   |
| A-DATA Technology           | 15        | 16     | 2.53%   |
| Hitachi                     | 14        | 15     | 2.36%   |
| BIWIN                       | 14        | 15     | 2.36%   |
| Foxline                     | 10        | 10     | 1.69%   |
| China                       | 10        | 10     | 1.69%   |
| Phison                      | 9         | 10     | 1.52%   |
| SanDisk                     | 8         | 8      | 1.35%   |
| HGST                        | 7         | 7      | 1.18%   |
| Crucial                     | 7         | 8      | 1.18%   |
| XPG                         | 6         | 7      | 1.01%   |
| Unknown                     | 6         | 12     | 1.01%   |
| Gigabyte Technology         | 5         | 5      | 0.84%   |
| Plextor                     | 4         | 4      | 0.67%   |
| Micron Technology           | 4         | 9      | 0.67%   |
| KingSpec                    | 4         | 4      | 0.67%   |
| Fujitsu                     | 4         | 4      | 0.67%   |
| AMD                         | 4         | 4      | 0.67%   |
| Unknown                     | 4         | 4      | 0.67%   |
| Transcend                   | 3         | 4      | 0.51%   |
| Smartbuy                    | 3         | 3      | 0.51%   |
| Patriot                     | 3         | 4      | 0.51%   |
| XrayDisk                    | 2         | 2      | 0.34%   |
| Team                        | 2         | 2      | 0.34%   |
| SSSTC                       | 2         | 2      | 0.34%   |
| SPCC                        | 2         | 2      | 0.34%   |
| PNY                         | 2         | 2      | 0.34%   |
| Netac                       | 2         | 2      | 0.34%   |
| JMicron Technology          | 2         | 2      | 0.34%   |
| DEPO                        | 2         | 2      | 0.34%   |
| Yangtze Memory Technologies | 1         | 1      | 0.17%   |
| TMI                         | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| AXIOMTEK Corp.-FSA128GMC2T 128GB SSD      | 26        | 4.17%   |
| Samsung MZVLW128HEGR-00000 128GB          | 18        | 2.88%   |
| Apacer AS2280P4 256GB                     | 16        | 2.56%   |
| BIWIN CE480T5D101-256 256GB               | 14        | 2.24%   |
| Toshiba HDWD120 2TB                       | 13        | 2.08%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB   | 12        | 1.92%   |
| WDC WD5000AZLX-21K2TA0 500GB              | 10        | 1.6%    |
| Seagate ST1000LM049-2GH172 1TB            | 10        | 1.6%    |
| SK hynix SKHynix_HFS256GD9TNG-L5B0B 256GB | 9         | 1.44%   |
| Foxline FLSSD256M80E13TCX5 256GB          | 9         | 1.44%   |
| Intel SSDPEMKF256G8H 256GB                | 8         | 1.28%   |
| Intel SSDPEKKF256G7H 256GB                | 8         | 1.28%   |
| Toshiba DT01ACA100 1TB                    | 6         | 0.96%   |
| Toshiba HDWD110 1TB                       | 5         | 0.8%    |
| Seagate ST1000DM010-2EP102 1TB            | 5         | 0.8%    |
| Samsung SSD 860 EVO 250GB                 | 5         | 0.8%    |
| Phison 311CD0512GB                        | 5         | 0.8%    |
| Kingston RBUSC180S37256GJ 256GB SSD       | 5         | 0.8%    |
| Apacer AS350 256GB SSD                    | 5         | 0.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 4         | 0.64%   |
| Samsung MZALQ256HAJD-000L2 256GB          | 4         | 0.64%   |
| Kingston SV300S37A120G 120GB SSD          | 4         | 0.64%   |
| Kingston SA400S37240G 240GB SSD           | 4         | 0.64%   |
| Kingston SA400S37120G 120GB SSD           | 4         | 0.64%   |
| Crucial CT240BX500SSD1 240GB              | 4         | 0.64%   |
| Unknown                                   | 4         | 0.64%   |
| XPG SPECTRIX S40G 1TB                     | 3         | 0.48%   |
| WDC WDS240G1G0A-00SS50 240GB SSD          | 3         | 0.48%   |
| WDC WDS120G2G0A-00JH30 120GB SSD          | 3         | 0.48%   |
| WDC WD10EZEX-08WN4A0 1TB                  | 3         | 0.48%   |
| Toshiba MQ04ABF100 1TB                    | 3         | 0.48%   |
| Seagate ST9250315AS 250GB                 | 3         | 0.48%   |
| Seagate ST500LM030-2E717D 500GB           | 3         | 0.48%   |
| Seagate ST380815AS 80GB                   | 3         | 0.48%   |
| Samsung SSD 860 EVO M.2 250GB             | 3         | 0.48%   |
| Samsung SSD 860 EVO 500GB                 | 3         | 0.48%   |
| Kingston OM8PDP3256B-A01 256GB            | 3         | 0.48%   |
| HGST HTS721010A9E630 1TB                  | 3         | 0.48%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB          | 3         | 0.48%   |
| XPG GAMMIX S5 256GB                       | 2         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 73        | 100    | 34.76%  |
| WDC                 | 66        | 96     | 31.43%  |
| Toshiba             | 40        | 59     | 19.05%  |
| Hitachi             | 14        | 15     | 6.67%   |
| HGST                | 7         | 7      | 3.33%   |
| Fujitsu             | 4         | 4      | 1.9%    |
| Samsung Electronics | 3         | 3      | 1.43%   |
| SINTECHI            | 1         | 1      | 0.48%   |
| Maxtor              | 1         | 1      | 0.48%   |
| FreeBSD             | 1         | 1      | 0.48%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 27        | 29     | 14.44%  |
| AXIOMTEK            | 26        | 28     | 13.9%   |
| Samsung Electronics | 16        | 19     | 8.56%   |
| WDC                 | 12        | 15     | 6.42%   |
| A-DATA Technology   | 12        | 13     | 6.42%   |
| China               | 10        | 10     | 5.35%   |
| Apacer              | 9         | 12     | 4.81%   |
| Crucial             | 7         | 8      | 3.74%   |
| SanDisk             | 5         | 5      | 2.67%   |
| Plextor             | 4         | 4      | 2.14%   |
| KingSpec            | 4         | 4      | 2.14%   |
| Intel               | 4         | 8      | 2.14%   |
| Transcend           | 3         | 4      | 1.6%    |
| Smartbuy            | 3         | 3      | 1.6%    |
| Patriot             | 3         | 4      | 1.6%    |
| Micron Technology   | 3         | 8      | 1.6%    |
| AMD                 | 3         | 3      | 1.6%    |
| Unknown             | 3         | 3      | 1.6%    |
| XrayDisk            | 2         | 2      | 1.07%   |
| Team                | 2         | 2      | 1.07%   |
| SK hynix            | 2         | 2      | 1.07%   |
| Seagate             | 2         | 6      | 1.07%   |
| PNY                 | 2         | 2      | 1.07%   |
| Phison              | 2         | 2      | 1.07%   |
| JMicron Technology  | 2         | 2      | 1.07%   |
| Gigabyte Technology | 2         | 2      | 1.07%   |
| Foxline             | 2         | 2      | 1.07%   |
| DEPO                | 2         | 2      | 1.07%   |
| TMI                 | 1         | 1      | 0.53%   |
| SP-8                | 1         | 1      | 0.53%   |
| OCZ                 | 1         | 1      | 0.53%   |
| Netac               | 1         | 1      | 0.53%   |
| LuminouTek          | 1         | 1      | 0.53%   |
| LITEON              | 1         | 1      | 0.53%   |
| KingDian            | 1         | 1      | 0.53%   |
| HEORIADY            | 1         | 1      | 0.53%   |
| GS Nanotech         | 1         | 1      | 0.53%   |
| GOODRAM             | 1         | 1      | 0.53%   |
| Corsair             | 1         | 2      | 0.53%   |
| BaseTech            | 1         | 1      | 0.53%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 187       | 287    | 33.88%  |
| NVMe | 183       | 214    | 33.15%  |
| SSD  | 172       | 218    | 31.16%  |
| MMC  | 10        | 16     | 1.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 302       | 495    | 60.04%  |
| NVMe | 182       | 212    | 36.18%  |
| MMC  | 10        | 16     | 1.99%   |
| SAS  | 9         | 12     | 1.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 240       | 308    | 66.12%  |
| 0.51-1.0   | 82        | 122    | 22.59%  |
| 1.01-2.0   | 33        | 65     | 9.09%   |
| 2.01-3.0   | 3         | 4      | 0.83%   |
| 4.01-10.0  | 3         | 4      | 0.83%   |
| 3.01-4.0   | 1         | 1      | 0.28%   |
| 0          | 1         | 1      | 0.28%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 249       | 51.45%  |
| 251-500        | 70        | 14.46%  |
| 1001-2000      | 38        | 7.85%   |
| 51-100         | 33        | 6.82%   |
| 501-1000       | 27        | 5.58%   |
| 21-50          | 25        | 5.17%   |
| 1-20           | 23        | 4.75%   |
| 2001-3000      | 9         | 1.86%   |
| More than 3000 | 8         | 1.65%   |
| Unknown        | 2         | 0.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 292       | 59.59%  |
| 21-50          | 78        | 15.92%  |
| 51-100         | 36        | 7.35%   |
| 101-250        | 34        | 6.94%   |
| 251-500        | 19        | 3.88%   |
| 501-1000       | 18        | 3.67%   |
| 1001-2000      | 6         | 1.22%   |
| More than 3000 | 3         | 0.61%   |
| 2001-3000      | 2         | 0.41%   |
| Unknown        | 2         | 0.41%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                  | Computers | Drives | Percent |
|--------------------------------------------------------|-----------|--------|---------|
| Seagate ST9250315AS 250GB                              | 3         | 3      | 5.88%   |
| Seagate ST380815AS 80GB                                | 2         | 2      | 3.92%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                     | 2         | 7      | 3.92%   |
| XrayDisk 512GB SSD                                     | 1         | 1      | 1.96%   |
| XrayDisk 240GB SSD                                     | 1         | 1      | 1.96%   |
| WDC WD7501AALS-00E3A0 752GB                            | 1         | 1      | 1.96%   |
| WDC WD7500AAKS-00RBA0 752GB                            | 1         | 2      | 1.96%   |
| WDC WD5000LPVX-60V0TT0 500GB                           | 1         | 1      | 1.96%   |
| WDC WD5000LPLX-60ZNTT2 500GB                           | 1         | 1      | 1.96%   |
| WDC WD3200AAKS-00V1A0 320GB                            | 1         | 1      | 1.96%   |
| WDC WD2500KS-00MJB0 250GB                              | 1         | 1      | 1.96%   |
| WDC WD2500BEVT-60ZCT1 250GB                            | 1         | 3      | 1.96%   |
| WDC WD20EARX-008FB0 2TB                                | 1         | 1      | 1.96%   |
| WDC WD2005FBYZ-01YCBB3 2TB                             | 1         | 1      | 1.96%   |
| WDC WD1200BEVS-60UST0 120GB                            | 1         | 1      | 1.96%   |
| WDC WD1003FBYX-01Y7B0 1TB                              | 1         | 1      | 1.96%   |
| Toshiba MQ01ABD050 500GB                               | 1         | 1      | 1.96%   |
| Toshiba MK1637GSX 160GB                                | 1         | 1      | 1.96%   |
| Toshiba DT01ACA050 500GB                               | 1         | 1      | 1.96%   |
| SK hynix HFS128G39TND-N210A 128GB SSD                  | 1         | 1      | 1.96%   |
| SK hynix BC501 HFM256GDJTNG-8310A 256GB                | 1         | 1      | 1.96%   |
| Shenzhen Longsys Electronics FORESEE XP1000F512G 512GB | 1         | 1      | 1.96%   |
| Seagate ST9640320AS 640GB                              | 1         | 1      | 1.96%   |
| Seagate ST9500530NS 42D0743 42D0746IBM 500GB           | 1         | 1      | 1.96%   |
| Seagate ST9500325AS 500GB                              | 1         | 1      | 1.96%   |
| Seagate ST380811AS 80GB                                | 1         | 1      | 1.96%   |
| Seagate ST3320418AS 320GB                              | 1         | 1      | 1.96%   |
| Seagate ST32000641AS 2TB                               | 1         | 2      | 1.96%   |
| Seagate ST3000DM001-1CH166 3TB                         | 1         | 1      | 1.96%   |
| Seagate ST250DM000-1BD141 250GB                        | 1         | 2      | 1.96%   |
| Seagate ST1000DL004 HD105SI 1TB                        | 1         | 1      | 1.96%   |
| Samsung Electronics SSD 870 EVO 500GB                  | 1         | 1      | 1.96%   |
| Intel SSDSCKKF256H6H 256GB                             | 1         | 1      | 1.96%   |
| Hitachi HUA722010CLA330 1TB                            | 1         | 1      | 1.96%   |
| Hitachi HTS725050A9A364 500GB                          | 1         | 1      | 1.96%   |
| Hitachi HTS545050KTA300 500GB                          | 1         | 2      | 1.96%   |
| Hitachi HTS543225L9A300 250GB                          | 1         | 1      | 1.96%   |
| Hitachi HTS542525K9A300 250GB                          | 1         | 1      | 1.96%   |
| Hitachi HTS541610J9SA00 100GB                          | 1         | 1      | 1.96%   |
| Hitachi HDS723020BLA642 2TB                            | 1         | 1      | 1.96%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Seagate                      | 16        | 23     | 31.37%  |
| WDC                          | 11        | 14     | 21.57%  |
| Hitachi                      | 8         | 9      | 15.69%  |
| Toshiba                      | 3         | 3      | 5.88%   |
| XrayDisk                     | 2         | 2      | 3.92%   |
| SK hynix                     | 2         | 2      | 3.92%   |
| HGST                         | 2         | 2      | 3.92%   |
| Shenzhen Longsys Electronics | 1         | 1      | 1.96%   |
| Samsung Electronics          | 1         | 1      | 1.96%   |
| Intel                        | 1         | 1      | 1.96%   |
| Fujitsu                      | 1         | 1      | 1.96%   |
| DEPO                         | 1         | 1      | 1.96%   |
| Corsair                      | 1         | 2      | 1.96%   |
| AMD                          | 1         | 1      | 1.96%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 16        | 23     | 39.02%  |
| WDC     | 11        | 14     | 26.83%  |
| Hitachi | 8         | 9      | 19.51%  |
| Toshiba | 3         | 3      | 7.32%   |
| HGST    | 2         | 2      | 4.88%   |
| Fujitsu | 1         | 1      | 2.44%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 38        | 52     | 79.17%  |
| SSD  | 8         | 9      | 16.67%  |
| NVMe | 2         | 2      | 4.17%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD5001AALS-00E3A0 500GB     | 1         | 1      | 50%     |
| Seagate ST250DM000-1BD141 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 50%     |
| Seagate | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 375       | 537    | 75.91%  |
| Detected | 70        | 133    | 14.17%  |
| Malfunc  | 47        | 63     | 9.51%   |
| Failed   | 2         | 2      | 0.4%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 365       | 57.75%  |
| AMD                            | 59        | 9.34%   |
| Samsung Electronics            | 44        | 6.96%   |
| Phison Electronics             | 35        | 5.54%   |
| SK hynix                       | 25        | 3.96%   |
| Nvidia                         | 14        | 2.22%   |
| INNOGRIT                       | 14        | 2.22%   |
| Kingston Technology Company    | 11        | 1.74%   |
| SanDisk                        | 10        | 1.58%   |
| JMicron Technology             | 7         | 1.11%   |
| Broadcom / LSI                 | 7         | 1.11%   |
| Realtek Semiconductor          | 6         | 0.95%   |
| Silicon Motion                 | 4         | 0.63%   |
| ASMedia Technology             | 4         | 0.63%   |
| Toshiba America Info Systems   | 3         | 0.47%   |
| MCST                           | 3         | 0.47%   |
| Marvell Technology Group       | 3         | 0.47%   |
| VIA Technologies               | 2         | 0.32%   |
| Solid State Storage Technology | 2         | 0.32%   |
| Shenzhen Longsys Electronics   | 2         | 0.32%   |
| LSI Logic / Symbios Logic      | 2         | 0.32%   |
| ADATA Technology               | 2         | 0.32%   |
| Zhaoxin                        | 1         | 0.16%   |
| Yangtze Memory Technologies    | 1         | 0.16%   |
| Micron/Crucial Technology      | 1         | 0.16%   |
| Micron Technology              | 1         | 0.16%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.16%   |
| KIOXIA                         | 1         | 0.16%   |
| Apple                          | 1         | 0.16%   |
| Adaptec                        | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 68        | 9.34%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 47        | 6.46%   |
| Phison PS5013 E13 NVMe Controller                                              | 34        | 4.67%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 32        | 4.4%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 31        | 4.26%   |
| Intel Tiger Lake-LP SATA Controller                                            | 27        | 3.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 18        | 2.47%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 18        | 2.47%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 18        | 2.47%   |
| AMD 400 Series Chipset SATA Controller                                         | 18        | 2.47%   |
| Intel Comet Lake SATA AHCI Controller                                          | 15        | 2.06%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 14        | 1.92%   |
| INNOGRIT Non-Volatile memory controller                                        | 14        | 1.92%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 13        | 1.79%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 12        | 1.65%   |
| Samsung NVMe SSD Controller 980                                                | 10        | 1.37%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 10        | 1.37%   |
| SK hynix Non-Volatile memory controller                                        | 9         | 1.24%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                        | 9         | 1.24%   |
| Intel SSD 600P Series                                                          | 9         | 1.24%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 9         | 1.24%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 9         | 1.24%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 1.1%    |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                  | 8         | 1.1%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 7         | 0.96%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                   | 7         | 0.96%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 0.96%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 0.82%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 0.69%   |
| JMicron JMB363 SATA/IDE Controller                                             | 5         | 0.69%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 0.69%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 5         | 0.69%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 5         | 0.69%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 0.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 5         | 0.69%   |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 0.69%   |
| Realtek RTS5763DL NVMe SSD Controller                                          | 4         | 0.55%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 0.55%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 0.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 0.55%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 380       | 58.02%  |
| NVMe | 182       | 27.79%  |
| IDE  | 56        | 8.55%   |
| RAID | 37        | 5.65%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 386       | 82.13%  |
| AMD          | 75        | 15.96%  |
| ARM          | 4         | 0.85%   |
| CentaurHauls | 2         | 0.43%   |
| Elbrus-MCST  | 1         | 0.21%   |
| E8C/EATX     | 1         | 0.21%   |
| E8C-SWTX     | 1         | 0.21%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i3-6100TE CPU @ 2.70GHz            | 44        | 9.32%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 30        | 6.36%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 23        | 4.87%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 19        | 4.03%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 13        | 2.75%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 12        | 2.54%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 11        | 2.33%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 10        | 2.12%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 2.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 1.69%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 6         | 1.27%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 6         | 1.27%   |
| Intel Xeon Silver 4210 CPU @ 2.20GHz          | 5         | 1.06%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 5         | 1.06%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 4         | 0.85%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 4         | 0.85%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 4         | 0.85%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 4         | 0.85%   |
| ARM Processor                                 | 4         | 0.85%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 4         | 0.85%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 3         | 0.64%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 0.64%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 3         | 0.64%   |
| Intel Celeron CPU G3900 @ 2.80GHz             | 3         | 0.64%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 0.64%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.64%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 0.64%   |
| Intel Pentium Dual-Core CPU E6600 @ 3.06GHz   | 2         | 0.42%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 2         | 0.42%   |
| Intel Genuine CPU 0000 @ 2.40GHz              | 2         | 0.42%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.42%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.42%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.42%   |
| Intel Core i5-8279U CPU @ 2.40GHz             | 2         | 0.42%   |
| Intel Core i5-7600 CPU @ 3.50GHz              | 2         | 0.42%   |
| Intel Core i5-7400 CPU @ 3.00GHz              | 2         | 0.42%   |
| Intel Core i5-3450 CPU @ 3.10GHz              | 2         | 0.42%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 0.42%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 2         | 0.42%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 2         | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 111       | 23.57%  |
| Intel Core i3           | 97        | 20.59%  |
| Other                   | 53        | 11.25%  |
| Intel Core i7           | 26        | 5.52%   |
| AMD Ryzen 5             | 25        | 5.31%   |
| Intel Celeron           | 23        | 4.88%   |
| Intel Pentium           | 19        | 4.03%   |
| Intel Core 2 Duo        | 14        | 2.97%   |
| AMD Ryzen 7             | 13        | 2.76%   |
| Intel Xeon              | 8         | 1.7%    |
| AMD A8                  | 7         | 1.49%   |
| Intel Xeon Silver       | 6         | 1.27%   |
| Intel Pentium Gold      | 6         | 1.27%   |
| Intel Pentium Dual-Core | 6         | 1.27%   |
| Intel Atom              | 6         | 1.27%   |
| AMD Athlon 64 X2        | 5         | 1.06%   |
| Intel Genuine           | 4         | 0.85%   |
| AMD FX                  | 3         | 0.64%   |
| AMD A10                 | 3         | 0.64%   |
| Intel Pentium Silver    | 2         | 0.42%   |
| Intel Core i9           | 2         | 0.42%   |
| Intel Core 2 Quad       | 2         | 0.42%   |
| AMD Ryzen 3             | 2         | 0.42%   |
| AMD Phenom II X4        | 2         | 0.42%   |
| AMD E1                  | 2         | 0.42%   |
| AMD Athlon              | 2         | 0.42%   |
| AMD A6                  | 2         | 0.42%   |
| Intel Xeon Gold         | 1         | 0.21%   |
| Intel Pentium Dual      | 1         | 0.21%   |
| Intel Pentium D         | 1         | 0.21%   |
| Intel Pentium 4         | 1         | 0.21%   |
| Intel Core m5           | 1         | 0.21%   |
| Intel Core Duo          | 1         | 0.21%   |
| Intel Core 2 Solo       | 1         | 0.21%   |
| Intel Celeron Dual-Core | 1         | 0.21%   |
| Intel Celeron D         | 1         | 0.21%   |
| CentaurHauls VIA C7     | 1         | 0.21%   |
| AMD Turion 64 X2 Mobile | 1         | 0.21%   |
| AMD Sempron             | 1         | 0.21%   |
| AMD Ryzen 9             | 1         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 196       | 41.61%  |
| 4      | 157       | 33.33%  |
| 6      | 65        | 13.8%   |
| 8      | 23        | 4.88%   |
| 1      | 11        | 2.34%   |
| 20     | 5         | 1.06%   |
| 12     | 4         | 0.85%   |
| 16     | 3         | 0.64%   |
| 32     | 2         | 0.42%   |
| 3      | 2         | 0.42%   |
| 18     | 1         | 0.21%   |
| 14     | 1         | 0.21%   |
| 10     | 1         | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 459       | 97.66%  |
| 2      | 9         | 1.91%   |
| 4      | 2         | 0.43%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 329       | 70%     |
| 1      | 141       | 30%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 458       | 97.45%  |
| 32-bit         | 6         | 1.28%   |
| Unknown        | 6         | 1.28%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 83        | 17.47%  |
| 0x506e3    | 51        | 10.74%  |
| 0x906ea    | 34        | 7.16%   |
| 0x806c1    | 34        | 7.16%   |
| 0x806e9    | 21        | 4.42%   |
| 0x806ec    | 16        | 3.37%   |
| 0x1067a    | 16        | 3.37%   |
| 0x806ea    | 14        | 2.95%   |
| 0x906e9    | 13        | 2.74%   |
| 0x08001138 | 13        | 2.74%   |
| 0xa0653    | 12        | 2.53%   |
| 0x806eb    | 10        | 2.11%   |
| 0x306a9    | 10        | 2.11%   |
| 0xa0660    | 8         | 1.68%   |
| 0x50657    | 8         | 1.68%   |
| 0x08108109 | 8         | 1.68%   |
| 0x206a7    | 7         | 1.47%   |
| 0x906eb    | 6         | 1.26%   |
| 0xa0671    | 5         | 1.05%   |
| 0x906ed    | 5         | 1.05%   |
| 0x706e5    | 5         | 1.05%   |
| 0x506c9    | 5         | 1.05%   |
| 0x306c3    | 5         | 1.05%   |
| 0x406e3    | 4         | 0.84%   |
| 0x0a50000c | 4         | 0.84%   |
| 0x06001119 | 4         | 0.84%   |
| 0x40651    | 3         | 0.63%   |
| 0x20655    | 3         | 0.63%   |
| 0x08600106 | 3         | 0.63%   |
| 0x906c0    | 2         | 0.42%   |
| 0x706a8    | 2         | 0.42%   |
| 0x6fd      | 2         | 0.42%   |
| 0x406c4    | 2         | 0.42%   |
| 0x406c3    | 2         | 0.42%   |
| 0x306e4    | 2         | 0.42%   |
| 0x30679    | 2         | 0.42%   |
| 0x30678    | 2         | 0.42%   |
| 0x106e5    | 2         | 0.42%   |
| 0x106ca    | 2         | 0.42%   |
| 0x106c2    | 2         | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 134       | 28.45%  |
| Skylake          | 68        | 14.44%  |
| TigerLake        | 38        | 8.07%   |
| CometLake        | 24        | 5.1%    |
| Penryn           | 20        | 4.25%   |
| Unknown          | 19        | 4.03%   |
| IvyBridge        | 16        | 3.4%    |
| Zen              | 15        | 3.18%   |
| SandyBridge      | 13        | 2.76%   |
| Zen+             | 12        | 2.55%   |
| Haswell          | 12        | 2.55%   |
| Silvermont       | 11        | 2.34%   |
| K8 Hammer        | 8         | 1.7%    |
| Zen 3            | 7         | 1.49%   |
| Zen 2            | 7         | 1.49%   |
| Westmere         | 7         | 1.49%   |
| Piledriver       | 7         | 1.49%   |
| IceLake          | 7         | 1.49%   |
| Core             | 6         | 1.27%   |
| Goldmont         | 5         | 1.06%   |
| K10              | 4         | 0.85%   |
| Goldmont plus    | 4         | 0.85%   |
| Bonnell          | 4         | 0.85%   |
| Steamroller      | 3         | 0.64%   |
| NetBurst         | 3         | 0.64%   |
| K10 Llano        | 3         | 0.64%   |
| Tremont          | 2         | 0.42%   |
| P6               | 2         | 0.42%   |
| Nehalem          | 2         | 0.42%   |
| Jaguar           | 2         | 0.42%   |
| Bobcat           | 2         | 0.42%   |
| Puma             | 1         | 0.21%   |
| Excavator        | 1         | 0.21%   |
| Broadwell        | 1         | 0.21%   |
| Alderlake Hybrid | 1         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 327       | 64.37%  |
| Nvidia                     | 96        | 18.9%   |
| AMD                        | 69        | 13.58%  |
| Matrox Electronics Systems | 5         | 0.98%   |
| ASPEED Technology          | 5         | 0.98%   |
| Silicon Motion             | 2         | 0.39%   |
| Huawei Technologies        | 2         | 0.39%   |
| Zhaoxin                    | 1         | 0.2%    |
| VIA Technologies           | 1         | 0.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel HD Graphics 530                                                                    | 48        | 9.18%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 34        | 6.5%    |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 30        | 5.74%   |
| Intel HD Graphics 620                                                                    | 28        | 5.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 24        | 4.59%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 18        | 3.44%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 12        | 2.29%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 2.1%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 2.1%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 11        | 2.1%    |
| Intel HD Graphics 610                                                                    | 10        | 1.91%   |
| Nvidia GP107GLM [Quadro P1000 Mobile]                                                    | 9         | 1.72%   |
| Intel Comet Lake UHD Graphics                                                            | 8         | 1.53%   |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 8         | 1.53%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 1.34%   |
| Intel UHD Graphics 620                                                                   | 6         | 1.15%   |
| Intel HD Graphics 510                                                                    | 6         | 1.15%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 1.15%   |
| Matrox Electronics Systems MGA G200e [Pilot] ServerEngines (SEP1)                        | 5         | 0.96%   |
| Intel HD Graphics 630                                                                    | 5         | 0.96%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 5         | 0.96%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 5         | 0.96%   |
| AMD Renoir                                                                               | 5         | 0.96%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.76%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 4         | 0.76%   |
| Intel HD Graphics 500                                                                    | 4         | 0.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 4         | 0.76%   |
| Intel CoffeeLake-S GT1 [UHD Graphics 610]                                                | 4         | 0.76%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 3         | 0.57%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.57%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 0.57%   |
| Intel Core Processor Integrated Graphics Controller                                      | 3         | 0.57%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 3         | 0.57%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M]                                     | 3         | 0.57%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 0.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 0.57%   |
| AMD Cape Verde XT [Radeon HD 7770/8760 / R7 250X]                                        | 3         | 0.57%   |
| Silicon Motion SM718 LynxSE+                                                             | 2         | 0.38%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 2         | 0.38%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 290       | 61.57%  |
| 1 x Nvidia              | 64        | 13.59%  |
| 1 x AMD                 | 49        | 10.4%   |
| Intel + Nvidia          | 27        | 5.73%   |
| 2 x AMD                 | 10        | 2.12%   |
| Other                   | 5         | 1.06%   |
| 1 x Matrox              | 5         | 1.06%   |
| Intel + AMD             | 5         | 1.06%   |
| 1 x ASPEED              | 5         | 1.06%   |
| AMD + Nvidia            | 4         | 0.85%   |
| 1 x Silicon Motion      | 2         | 0.42%   |
| 1 x Huawei Technologies | 2         | 0.42%   |
| 2 x Intel               | 1         | 0.21%   |
| 1 x VIA                 | 1         | 0.21%   |
| Nvidia + Zhaoxin        | 1         | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 398       | 83.97%  |
| Proprietary | 55        | 11.6%   |
| Unknown     | 21        | 4.43%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 354       | 74.53%  |
| 3.01-4.0   | 33        | 6.95%   |
| 0.01-0.5   | 33        | 6.95%   |
| 1.01-2.0   | 24        | 5.05%   |
| 0.51-1.0   | 23        | 4.84%   |
| 8.01-16.0  | 4         | 0.84%   |
| 7.01-8.0   | 2         | 0.42%   |
| 5.01-6.0   | 1         | 0.21%   |
| 2.01-3.0   | 1         | 0.21%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| BOE                     | 51        | 10.56%  |
| HHT                     | 45        | 9.32%   |
| Samsung Electronics     | 43        | 8.9%    |
| Chimei Innolux          | 41        | 8.49%   |
| AU Optronics            | 34        | 7.04%   |
| Acer                    | 28        | 5.8%    |
| AOC                     | 26        | 5.38%   |
| BenQ                    | 24        | 4.97%   |
| LG Display              | 21        | 4.35%   |
| ECS                     | 21        | 4.35%   |
| Goldstar                | 13        | 2.69%   |
| Philips                 | 12        | 2.48%   |
| Lenovo                  | 12        | 2.48%   |
| ViewSonic               | 10        | 2.07%   |
| PANDA                   | 10        | 2.07%   |
| Dell                    | 8         | 1.66%   |
| Sharp                   | 6         | 1.24%   |
| Chi Mei Optoelectronics | 6         | 1.24%   |
| Apple                   | 6         | 1.24%   |
| Ancor Communications    | 6         | 1.24%   |
| PRW                     | 4         | 0.83%   |
| PRM                     | 4         | 0.83%   |
| CHR                     | 4         | 0.83%   |
| WBT                     | 3         | 0.62%   |
| VIE                     | 3         | 0.62%   |
| LG Electronics          | 3         | 0.62%   |
| Iiyama                  | 3         | 0.62%   |
| Toshiba                 | 2         | 0.41%   |
| STD                     | 2         | 0.41%   |
| STA                     | 2         | 0.41%   |
| MSI                     | 2         | 0.41%   |
| JRY                     | 2         | 0.41%   |
| Hewlett-Packard         | 2         | 0.41%   |
| HannStar                | 2         | 0.41%   |
| AGO                     | 2         | 0.41%   |
| ZCS                     | 1         | 0.21%   |
| TR_                     | 1         | 0.21%   |
| SKM                     | 1         | 0.21%   |
| SKG                     | 1         | 0.21%   |
| RTK                     | 1         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| HHT ActivPanel V6 HHT0030 3840x2160 944x398mm 40.3-inch               | 45        | 9.16%   |
| ECS AIO PC ECS2486 1920x1080 520x300mm 23.6-inch                      | 21        | 4.28%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 12        | 2.44%   |
| AOC LCD Monitor 2778X 2560x1440                                       | 11        | 2.24%   |
| Lenovo LEN-V5S5W-B-A LENE288 1920x1080 527x296mm 23.8-inch            | 10        | 2.04%   |
| Acer V246HL ACR0336 1920x1080 531x299mm 24.0-inch                     | 10        | 2.04%   |
| Chimei Innolux LCD Monitor CMN175A 1920x1080 381x214mm 17.2-inch      | 9         | 1.83%   |
| BenQ LCD BNQ801B 2560x1440 530x300mm 24.0-inch                        | 8         | 1.63%   |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch               | 6         | 1.22%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch      | 6         | 1.22%   |
| BOE LCD Monitor BOE09EF 1920x1080 344x194mm 15.5-inch                 | 6         | 1.22%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch  | 5         | 1.02%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                     | 5         | 1.02%   |
| AU Optronics LCD Monitor AUO213D 1920x1080 309x173mm 13.9-inch        | 5         | 1.02%   |
| ViewSonic VA2407 SERIES VSC8C31 1920x1080 521x293mm 23.5-inch         | 4         | 0.81%   |
| PRW AP7_Titanium PRW4200 3840x2160                                    | 4         | 0.81%   |
| BOE LCD Monitor BOE09C5 1920x1080 345x195mm 15.6-inch                 | 4         | 0.81%   |
| WBT AIO215 WBTF017 1920x1200 580x360mm 26.9-inch                      | 3         | 0.61%   |
| Sharp LCD Monitor SHP1542 1920x1080 309x174mm 14.0-inch               | 3         | 0.61%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch   | 3         | 0.61%   |
| LG Display LCD Monitor LGD04B2 1920x1080 309x175mm 14.0-inch          | 3         | 0.61%   |
| CHR CH7511B CHR7511 1920x1080 519x324mm 24.1-inch                     | 3         | 0.61%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 0.61%   |
| Chimei Innolux LCD Monitor CMN1404 1920x1080 309x173mm 13.9-inch      | 3         | 0.61%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 3         | 0.61%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 3         | 0.61%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 3         | 0.61%   |
| AOC 2490W1 AOC2490 1920x1080 527x296mm 23.8-inch                      | 3         | 0.61%   |
| Acer AIO LCD ACRF132 1920x1080 509x286mm 23.0-inch                    | 3         | 0.61%   |
| ViewSonic VA703-3Series VSC631E 1280x1024 338x270mm 17.0-inch         | 2         | 0.41%   |
| ViewSonic LCD Monitor VSC6C2E 1920x1080 520x290mm 23.4-inch           | 2         | 0.41%   |
| VIE IM27VL1 VIE2120 1920x1080 600x330mm 27.0-inch                     | 2         | 0.41%   |
| STD LCD Monitor STD0001 1920x1080                                     | 2         | 0.41%   |
| STA LCD Monitor STAAFC9 1920x1080 344x194mm 15.5-inch                 | 2         | 0.41%   |
| Samsung Electronics SyncMaster SAM0580 1280x1024 376x301mm 19.0-inch  | 2         | 0.41%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch  | 2         | 0.41%   |
| Samsung Electronics S22E391 SAM0C0E 1920x1080 477x268mm 21.5-inch     | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3646 1680x1050 330x210mm 15.4-inch | 2         | 0.41%   |
| PRM 35 PRM2733 1280x1024                                              | 2         | 0.41%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch           | 2         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 257       | 55.27%  |
| 3840x2160 (4K)     | 59        | 12.69%  |
| 1366x768 (WXGA)    | 41        | 8.82%   |
| 2560x1440 (QHD)    | 28        | 6.02%   |
| 1280x1024 (SXGA)   | 27        | 5.81%   |
| 1600x900 (HD+)     | 11        | 2.37%   |
| 1280x800 (WXGA)    | 11        | 2.37%   |
| 1680x1050 (WSXGA+) | 7         | 1.51%   |
| 1440x900 (WXGA+)   | 5         | 1.08%   |
| 2560x1600          | 3         | 0.65%   |
| 2160x1440          | 2         | 0.43%   |
| 1920x1200 (WUXGA)  | 2         | 0.43%   |
| 1024x600           | 2         | 0.43%   |
| Unknown            | 2         | 0.43%   |
| 4480x1440          | 1         | 0.22%   |
| 3840x1600          | 1         | 0.22%   |
| 3200x1800 (QHD+)   | 1         | 0.22%   |
| 2880x1620          | 1         | 0.22%   |
| 1600x1200          | 1         | 0.22%   |
| 1400x1050          | 1         | 0.22%   |
| 1360x768           | 1         | 0.22%   |
| 1280x720 (HD)      | 1         | 0.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 95        | 19.79%  |
| 23      | 61        | 12.71%  |
| 40      | 47        | 9.79%   |
| 24      | 41        | 8.54%   |
| 17      | 35        | 7.29%   |
| 13      | 34        | 7.08%   |
| 14      | 33        | 6.88%   |
| Unknown | 31        | 6.46%   |
| 21      | 27        | 5.63%   |
| 27      | 22        | 4.58%   |
| 19      | 15        | 3.13%   |
| 26      | 6         | 1.25%   |
| 12      | 6         | 1.25%   |
| 31      | 5         | 1.04%   |
| 11      | 5         | 1.04%   |
| 22      | 2         | 0.42%   |
| 20      | 2         | 0.42%   |
| 10      | 2         | 0.42%   |
| 74      | 1         | 0.21%   |
| 72      | 1         | 0.21%   |
| 59      | 1         | 0.21%   |
| 52      | 1         | 0.21%   |
| 46      | 1         | 0.21%   |
| 37      | 1         | 0.21%   |
| 33      | 1         | 0.21%   |
| 32      | 1         | 0.21%   |
| 28      | 1         | 0.21%   |
| 18      | 1         | 0.21%   |
| 8       | 1         | 0.21%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 164       | 34.53%  |
| 501-600     | 122       | 25.68%  |
| 901-1000    | 45        | 9.47%   |
| 401-500     | 38        | 8%      |
| Unknown     | 31        | 6.53%   |
| 351-400     | 28        | 5.89%   |
| 201-300     | 25        | 5.26%   |
| 601-700     | 11        | 2.32%   |
| 801-900     | 3         | 0.63%   |
| 1001-1500   | 3         | 0.63%   |
| 701-800     | 2         | 0.42%   |
| 1501-2000   | 2         | 0.42%   |
| 101-200     | 1         | 0.21%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 322       | 70.15%  |
| 21/9    | 46        | 10.02%  |
| 16/10   | 34        | 7.41%   |
| 5/4     | 25        | 5.45%   |
| Unknown | 21        | 4.58%   |
| 4/3     | 5         | 1.09%   |
| 3/2     | 5         | 1.09%   |
| 6/5     | 1         | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 201-250        | 112       | 23.48%  |
| 101-110        | 95        | 19.92%  |
| 81-90          | 61        | 12.79%  |
| 501-1000       | 49        | 10.27%  |
| Unknown        | 31        | 6.5%    |
| 301-350        | 28        | 5.87%   |
| 151-200        | 23        | 4.82%   |
| 121-130        | 19        | 3.98%   |
| 141-150        | 16        | 3.35%   |
| 251-300        | 10        | 2.1%    |
| 71-80          | 8         | 1.68%   |
| 351-500        | 8         | 1.68%   |
| 51-60          | 5         | 1.05%   |
| More than 1000 | 4         | 0.84%   |
| 61-70          | 4         | 0.84%   |
| 41-50          | 2         | 0.42%   |
| 1-40           | 1         | 0.21%   |
| 131-140        | 1         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 155       | 32.7%   |
| 121-160       | 148       | 31.22%  |
| 101-120       | 119       | 25.11%  |
| Unknown       | 31        | 6.54%   |
| 161-240       | 13        | 2.74%   |
| 1-50          | 6         | 1.27%   |
| More than 240 | 2         | 0.42%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 415       | 87.37%  |
| 2     | 38        | 8%      |
| 0     | 20        | 4.21%   |
| 3     | 2         | 0.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 298       | 43.7%   |
| Intel                           | 246       | 36.07%  |
| Qualcomm Atheros                | 45        | 6.6%    |
| Broadcom                        | 22        | 3.23%   |
| Nvidia                          | 13        | 1.91%   |
| D-Link                          | 8         | 1.17%   |
| Marvell Technology Group        | 6         | 0.88%   |
| IBM                             | 5         | 0.73%   |
| TP-Link                         | 4         | 0.59%   |
| Ralink                          | 3         | 0.44%   |
| Microchip Technology            | 3         | 0.44%   |
| MediaTek                        | 3         | 0.44%   |
| MCST                            | 3         | 0.44%   |
| Xiaomi                          | 2         | 0.29%   |
| VIA Technologies                | 2         | 0.29%   |
| Sierra Wireless                 | 2         | 0.29%   |
| Ralink Technology               | 2         | 0.29%   |
| JMicron Technology              | 2         | 0.29%   |
| Broadcom Limited                | 2         | 0.29%   |
| ASUSTek Computer                | 2         | 0.29%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.15%   |
| Vimtron Electronics             | 1         | 0.15%   |
| U-Blox                          | 1         | 0.15%   |
| Qualcomm Atheros Communications | 1         | 0.15%   |
| Micro Star International        | 1         | 0.15%   |
| Huawei Technologies             | 1         | 0.15%   |
| Exar                            | 1         | 0.15%   |
| DisplayLink                     | 1         | 0.15%   |
| ASIX Electronics                | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 208       | 25.15%  |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 45        | 5.44%   |
| Intel Ethernet Connection I219-LM                                       | 33        | 3.99%   |
| Intel Wi-Fi 6 AX201                                                     | 32        | 3.87%   |
| Intel Ethernet Connection (13) I219-V                                   | 24        | 2.9%    |
| Intel Ethernet Connection (2) I219-LM                                   | 18        | 2.18%   |
| Intel Wireless 8265 / 8275                                              | 17        | 2.06%   |
| Intel Wi-Fi 6 AX200                                                     | 17        | 2.06%   |
| Intel Wireless 3165                                                     | 16        | 1.93%   |
| Intel Ethernet Connection (10) I219-V                                   | 13        | 1.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 13        | 1.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 1.45%   |
| Intel Wireless 7265                                                     | 12        | 1.45%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 11        | 1.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 1.33%   |
| Intel Ethernet Connection (7) I219-LM                                   | 10        | 1.21%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 10        | 1.21%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 1.09%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 0.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 8         | 0.97%   |
| Intel Ethernet Connection X722 for 1GbE                                 | 7         | 0.85%   |
| Intel Ethernet Connection (6) I219-V                                    | 7         | 0.85%   |
| Realtek RTL8125 2.5GbE Controller                                       | 6         | 0.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 0.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 0.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 0.73%   |
| Intel Ethernet Connection X722 for 10GBASE-T                            | 6         | 0.73%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 0.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.6%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 5         | 0.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 0.6%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 5         | 0.6%    |
| Intel I210 Gigabit Network Connection                                   | 5         | 0.6%    |
| Intel Ethernet Controller X710 for 10GbE SFP+                           | 5         | 0.6%    |
| Intel Ethernet Connection (14) I219-V                                   | 5         | 0.6%    |
| IBM RNDIS/CDC ETHER                                                     | 5         | 0.6%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.48%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                 | 4         | 0.48%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.48%   |
| Intel I350 Gigabit Network Connection                                   | 4         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 172       | 58.9%   |
| Realtek Semiconductor           | 51        | 17.47%  |
| Qualcomm Atheros                | 33        | 11.3%   |
| Broadcom                        | 17        | 5.82%   |
| TP-Link                         | 4         | 1.37%   |
| Ralink                          | 3         | 1.03%   |
| MediaTek                        | 3         | 1.03%   |
| Sierra Wireless                 | 2         | 0.68%   |
| Ralink Technology               | 2         | 0.68%   |
| ASUSTek Computer                | 2         | 0.68%   |
| Qualcomm Atheros Communications | 1         | 0.34%   |
| Micro Star International        | 1         | 0.34%   |
| D-Link                          | 1         | 0.34%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                     | 32        | 10.92%  |
| Intel Wireless 8265 / 8275                                              | 17        | 5.8%    |
| Intel Wi-Fi 6 AX200                                                     | 17        | 5.8%    |
| Intel Wireless 3165                                                     | 16        | 5.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 13        | 4.44%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 4.1%    |
| Intel Wireless 7265                                                     | 12        | 4.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 11        | 3.75%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 10        | 3.41%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 9         | 3.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 2.73%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 2.05%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 2.05%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 6         | 2.05%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 6         | 2.05%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.71%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 5         | 1.71%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 1.71%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.37%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 1.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.02%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 3         | 1.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 3         | 1.02%   |
| Intel Wireless-AC 9260                                                  | 3         | 1.02%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 1.02%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 3         | 1.02%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 3         | 1.02%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 3         | 1.02%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 2         | 0.68%   |
| Sierra Wireless EM7305 Modem                                            | 2         | 0.68%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.68%   |
| Realtek Realtek Network controller                                      | 2         | 0.68%   |
| Realtek 802.11ac NIC                                                    | 2         | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.68%   |
| Intel Wireless 7260                                                     | 2         | 0.68%   |
| Intel WiMAX/WiFi Link 5150                                              | 2         | 0.68%   |
| Intel WiFi Link 5100                                                    | 2         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 281       | 55.64%  |
| Intel                      | 149       | 29.5%   |
| Qualcomm Atheros           | 20        | 3.96%   |
| Nvidia                     | 13        | 2.57%   |
| D-Link                     | 7         | 1.39%   |
| Broadcom                   | 7         | 1.39%   |
| Marvell Technology Group   | 6         | 1.19%   |
| IBM                        | 5         | 0.99%   |
| MCST                       | 3         | 0.59%   |
| Xiaomi                     | 2         | 0.4%    |
| VIA Technologies           | 2         | 0.4%    |
| JMicron Technology         | 2         | 0.4%    |
| Broadcom Limited           | 2         | 0.4%    |
| ZTE WCDMA Technologies MSM | 1         | 0.2%    |
| Vimtron Electronics        | 1         | 0.2%    |
| TP-Link                    | 1         | 0.2%    |
| Huawei Technologies        | 1         | 0.2%    |
| DisplayLink                | 1         | 0.2%    |
| ASIX Electronics           | 1         | 0.2%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 208       | 39.39%  |
| Realtek RTL8152 Fast Ethernet Adapter                             | 45        | 8.52%   |
| Intel Ethernet Connection I219-LM                                 | 33        | 6.25%   |
| Intel Ethernet Connection (13) I219-V                             | 24        | 4.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 18        | 3.41%   |
| Intel Ethernet Connection (10) I219-V                             | 13        | 2.46%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 11        | 2.08%   |
| Intel Ethernet Connection (7) I219-LM                             | 10        | 1.89%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 1.52%   |
| Intel Ethernet Connection X722 for 1GbE                           | 7         | 1.33%   |
| Intel Ethernet Connection (6) I219-V                              | 7         | 1.33%   |
| Realtek RTL8125 2.5GbE Controller                                 | 6         | 1.14%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 6         | 1.14%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5         | 0.95%   |
| Intel I210 Gigabit Network Connection                             | 5         | 0.95%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 5         | 0.95%   |
| Intel Ethernet Connection (14) I219-V                             | 5         | 0.95%   |
| IBM RNDIS/CDC ETHER                                               | 5         | 0.95%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 4         | 0.76%   |
| Intel I350 Gigabit Network Connection                             | 4         | 0.76%   |
| Intel Ethernet Connection (4) I219-V                              | 4         | 0.76%   |
| D-Link DUB-1312 Gigabit Ethernet Adapter                          | 4         | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 3         | 0.57%   |
| Nvidia MCP51 Ethernet Controller                                  | 3         | 0.57%   |
| Intel I211 Gigabit Network Connection                             | 3         | 0.57%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.57%   |
| Intel Ethernet Connection (17) I219-V                             | 3         | 0.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 0.57%   |
| D-Link DUB-E100 Fast Ethernet Adapter(rev.C1) [ASIX AX88772]      | 3         | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.38%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 0.38%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.38%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.38%   |
| Nvidia MCP89 Ethernet                                             | 2         | 0.38%   |
| Nvidia MCP77 Ethernet                                             | 2         | 0.38%   |
| MCST Gigabit Ethernet Controller                                  | 2         | 0.38%   |
| Intel WiMAX Connection 2400m                                      | 2         | 0.38%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                     | 2         | 0.38%   |
| Intel 82599ES 10-Gigabit SFI/SFP+ Network Connection              | 2         | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 435       | 60%     |
| WiFi     | 284       | 39.17%  |
| Modem    | 5         | 0.69%   |
| Unknown  | 1         | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 255       | 53.35%  |
| WiFi     | 223       | 46.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 241       | 51.28%  |
| 1     | 204       | 43.4%   |
| 0     | 11        | 2.34%   |
| 6     | 5         | 1.06%   |
| 4     | 3         | 0.64%   |
| 3     | 3         | 0.64%   |
| 13    | 1         | 0.21%   |
| 12    | 1         | 0.21%   |
| 8     | 1         | 0.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 456       | 97.02%  |
| Yes  | 14        | 2.98%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 160       | 66.95%  |
| Realtek Semiconductor           | 14        | 5.86%   |
| IMC Networks                    | 11        | 4.6%    |
| Cambridge Silicon Radio         | 10        | 4.18%   |
| Broadcom                        | 10        | 4.18%   |
| Qualcomm Atheros Communications | 6         | 2.51%   |
| Lite-On Technology              | 6         | 2.51%   |
| Foxconn / Hon Hai               | 4         | 1.67%   |
| Apple                           | 4         | 1.67%   |
| Realtek                         | 3         | 1.26%   |
| Hewlett-Packard                 | 3         | 1.26%   |
| ASUSTek Computer                | 2         | 0.84%   |
| USI                             | 1         | 0.42%   |
| Toshiba                         | 1         | 0.42%   |
| Ralink                          | 1         | 0.42%   |
| Opticis                         | 1         | 0.42%   |
| Logitech                        | 1         | 0.42%   |
| Chicony Electronics             | 1         | 0.42%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 54        | 22.59%  |
| Intel Bluetooth Device                              | 37        | 15.48%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 36        | 15.06%  |
| Intel AX200 Bluetooth                               | 17        | 7.11%   |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 4.18%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 10        | 4.18%   |
| Realtek Bluetooth Radio                             | 8         | 3.35%   |
| Realtek  Bluetooth 4.2 Adapter                      | 5         | 2.09%   |
| IMC Networks Bluetooth Device                       | 4         | 1.67%   |
| Broadcom BCM2045 Bluetooth                          | 4         | 1.67%   |
| Realtek Bluetooth Radio                             | 3         | 1.26%   |
| Qualcomm Atheros  Bluetooth Device                  | 3         | 1.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.26%   |
| IMC Networks Wireless_Device                        | 3         | 1.26%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 3         | 1.26%   |
| Apple Bluetooth Host Controller                     | 3         | 1.26%   |
| Lite-On Bluetooth Device                            | 2         | 0.84%   |
| Intel AX210 Bluetooth                               | 2         | 0.84%   |
| IMC Networks Bluetooth Radio                        | 2         | 0.84%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 2         | 0.84%   |
| HP Broadcom 2070 Bluetooth Combo                    | 2         | 0.84%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.84%   |
| USI Bluetooth Module BCM92070                       | 1         | 0.42%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.42%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.42%   |
| Ralink RT3290 Bluetooth                             | 1         | 0.42%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.42%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.42%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.42%   |
| Opticis Bluetooth Radio                             | 1         | 0.42%   |
| Logitech BT Mini-Receiver (HCI mode)                | 1         | 0.42%   |
| Lite-On Qualcomm Atheros Bluetooth                  | 1         | 0.42%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.42%   |
| Lite-On Bluetooth Radio                             | 1         | 0.42%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.42%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 1         | 0.42%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 1         | 0.42%   |
| Foxconn / Hon Hai Acer Bluetooth module             | 1         | 0.42%   |
| Chicony Bluetooth (RTL8723BE)                       | 1         | 0.42%   |
| Broadcom HP Portable Bumble Bee                     | 1         | 0.42%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 367       | 64.27%  |
| AMD                                          | 80        | 14.01%  |
| Nvidia                                       | 78        | 13.66%  |
| C-Media Electronics                          | 21        | 3.68%   |
| Promethean Limited                           | 5         | 0.88%   |
| MCST                                         | 3         | 0.53%   |
| VIA Technologies                             | 2         | 0.35%   |
| Realtek Semiconductor                        | 2         | 0.35%   |
| JMTek                                        | 2         | 0.35%   |
| Creative Technology                          | 2         | 0.35%   |
| Apple                                        | 2         | 0.35%   |
| Zoran Co. Personal Media Division (Nogatech) | 1         | 0.18%   |
| Zhaoxin                                      | 1         | 0.18%   |
| Generalplus Technology                       | 1         | 0.18%   |
| EasyPass Industrial                          | 1         | 0.18%   |
| Creative Labs                                | 1         | 0.18%   |
| ASUSTek Computer                             | 1         | 0.18%   |
| A4Tech                                       | 1         | 0.18%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 68        | 10.93%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 38        | 6.11%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 38        | 6.11%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 32        | 5.14%   |
| Intel 200 Series PCH HD Audio                                                                     | 31        | 4.98%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 29        | 4.66%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 22        | 3.54%   |
| Intel Cannon Lake PCH cAVS                                                                        | 18        | 2.89%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 2.73%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 15        | 2.41%   |
| C-Media Electronics USB Advanced Audio Device                                                     | 14        | 2.25%   |
| AMD FCH Azalia Controller                                                                         | 14        | 2.25%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 13        | 2.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 12        | 1.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 12        | 1.93%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 1.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 1.61%   |
| Intel Audio device                                                                                | 8         | 1.29%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 1.29%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 0.96%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 6         | 0.96%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 0.96%   |
| Promethean Limited Audio                                                                          | 5         | 0.8%    |
| Intel Tiger Lake-H HD Audio Controller                                                            | 5         | 0.8%    |
| Intel Comet Lake PCH-V cAVS                                                                       | 5         | 0.8%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 0.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 0.8%    |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 5         | 0.8%    |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 5         | 0.8%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 0.64%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 0.64%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 0.64%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 4         | 0.64%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.64%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 0.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 0.64%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 0.64%   |
| Intel 8 Series HD Audio Controller                                                                | 4         | 0.64%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 77        | 19.44%  |
| Crucial             | 66        | 16.67%  |
| SK hynix            | 50        | 12.63%  |
| Kingston            | 41        | 10.35%  |
| Unknown             | 39        | 9.85%   |
| Micron Technology   | 27        | 6.82%   |
| Ramaxel Technology  | 14        | 3.54%   |
| ACPI Digital        | 14        | 3.54%   |
| Foxline             | 11        | 2.78%   |
| A-DATA Technology   | 9         | 2.27%   |
| Apacer              | 5         | 1.26%   |
| Unknown (ABCD)      | 4         | 1.01%   |
| Patriot             | 4         | 1.01%   |
| Elpida              | 4         | 1.01%   |
| Corsair             | 4         | 1.01%   |
| AMD                 | 4         | 1.01%   |
| Unknown             | 4         | 1.01%   |
| ChangXin Memory     | 3         | 0.76%   |
| Shenzhen Longsys    | 2         | 0.51%   |
| GOODRAM             | 2         | 0.51%   |
| Goldkey             | 2         | 0.51%   |
| Wilk                | 1         | 0.25%   |
| Unknown (0x0B7A)    | 1         | 0.25%   |
| tigo                | 1         | 0.25%   |
| SHARETRONIC         | 1         | 0.25%   |
| Qumo                | 1         | 0.25%   |
| Kimtigo             | 1         | 0.25%   |
| Juhor               | 1         | 0.25%   |
| Golden Empire       | 1         | 0.25%   |
| G.Skill             | 1         | 0.25%   |
| ATLA                | 1         | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Crucial RAM CT8G4SFRA266.M8FRS 8GB SODIMM DDR4 2667MT/s          | 17        | 4.12%   |
| ACPI Digital RAM CMB6-DHDA1BAR08D00 16GB SODIMM DDR4 3200MT/s    | 14        | 3.39%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 13        | 3.15%   |
| Crucial RAM CT4G4DFS824A.M8FF 4GB DIMM DDR4 2400MT/s             | 13        | 3.15%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8192MB SODIMM DDR4 2667MT/s     | 10        | 2.42%   |
| Micron RAM Module 4GB DIMM DDR4 2400MT/s                         | 10        | 2.42%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 9         | 2.18%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2133MT/s                     | 7         | 1.69%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s              | 7         | 1.69%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 5         | 1.21%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 5         | 1.21%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.97%   |
| Samsung RAM M393A2K43CB2-CVF 16384MB DIMM DDR4 2933MT/s          | 4         | 0.97%   |
| Kingston RAM CBD24D4S7S8K1A-8 8GB SODIMM DDR4 2400MT/s           | 4         | 0.97%   |
| Crucial RAM CT8G4SFRA266.C4FE 8GB SODIMM DDR4 2667MT/s           | 4         | 0.97%   |
| Unknown                                                          | 4         | 0.97%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 3         | 0.73%   |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 3         | 0.73%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.73%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.73%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.73%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.73%   |
| SK hynix RAM HMA81GU6CJR8N-XN 8GB DIMM DDR4 3200MT/s             | 3         | 0.73%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 3         | 0.73%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.73%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.73%   |
| Kingston RAM CBD26D4S9S8K1C-8 8GB SODIMM DDR4 2667MT/s           | 3         | 0.73%   |
| Crucial RAM CT8G4SFRA266.C16FG 8GB SODIMM DDR4 2667MT/s          | 3         | 0.73%   |
| Crucial RAM CT8G4DFS8213.C8FDR1 8GB DIMM DDR4 2133MT/s           | 3         | 0.73%   |
| ChangXin Memory RAM DB4ABAM-MK 1GB Row Of Chips LPDDR4 3733MT/s  | 3         | 0.73%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 0.48%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.48%   |
| Unknown RAM Module 2GB DIMM 800MT/s                              | 2         | 0.48%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 2         | 0.48%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.48%   |
| Unknown RAM Module 1024MB DIMM                                   | 2         | 0.48%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.48%   |
| Samsung RAM Module 2GB SODIMM DDR3 1067MT/s                      | 2         | 0.48%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.48%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.48%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 256       | 68.82%  |
| DDR3    | 61        | 16.4%   |
| DDR2    | 20        | 5.38%   |
| Unknown | 14        | 3.76%   |
| LPDDR4  | 13        | 3.49%   |
| SDRAM   | 4         | 1.08%   |
| DDR     | 2         | 0.54%   |
| LPDDR3  | 1         | 0.27%   |
| DRAM    | 1         | 0.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 222       | 59.68%  |
| DIMM         | 132       | 35.48%  |
| Row Of Chips | 18        | 4.84%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 168       | 43.98%  |
| 4096  | 112       | 29.32%  |
| 16384 | 45        | 11.78%  |
| 2048  | 29        | 7.59%   |
| 1024  | 18        | 4.71%   |
| 512   | 5         | 1.31%   |
| 32768 | 3         | 0.79%   |
| 65536 | 1         | 0.26%   |
| 1536  | 1         | 0.26%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 103       | 26.34%  |
| 3200    | 61        | 15.6%   |
| 2400    | 55        | 14.07%  |
| 1600    | 39        | 9.97%   |
| 2133    | 25        | 6.39%   |
| 2933    | 14        | 3.58%   |
| 667     | 13        | 3.32%   |
| 1333    | 11        | 2.81%   |
| Unknown | 10        | 2.56%   |
| 1334    | 7         | 1.79%   |
| 3266    | 5         | 1.28%   |
| 800     | 5         | 1.28%   |
| 3733    | 4         | 1.02%   |
| 3600    | 3         | 0.77%   |
| 1067    | 3         | 0.77%   |
| 533     | 3         | 0.77%   |
| 400     | 3         | 0.77%   |
| 333     | 3         | 0.77%   |
| 4267    | 2         | 0.51%   |
| 3466    | 2         | 0.51%   |
| 3066    | 2         | 0.51%   |
| 2866    | 2         | 0.51%   |
| 1867    | 2         | 0.51%   |
| 1866    | 2         | 0.51%   |
| 4800    | 1         | 0.26%   |
| 4333    | 1         | 0.26%   |
| 4199    | 1         | 0.26%   |
| 3534    | 1         | 0.26%   |
| 3333    | 1         | 0.26%   |
| 3151    | 1         | 0.26%   |
| 3000    | 1         | 0.26%   |
| 2800    | 1         | 0.26%   |
| 2666    | 1         | 0.26%   |
| 1648    | 1         | 0.26%   |
| 1066    | 1         | 0.26%   |
| 32      | 1         | 0.26%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 5         | 26.32%  |
| Canon                  | 5         | 26.32%  |
| Samsung Electronics    | 4         | 21.05%  |
| Xerox                  | 1         | 5.26%   |
| QinHeng Electronics    | 1         | 5.26%   |
| Pantum                 | 1         | 5.26%   |
| Panasonic (Matsushita) | 1         | 5.26%   |
| Brother Industries     | 1         | 5.26%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                             | Computers | Percent |
|-----------------------------------|-----------|---------|
| HP LaserJet P1102                 | 2         | 10.53%  |
| HP LaserJet 1010                  | 2         | 10.53%  |
| Xerox WorkCentre 3220             | 1         | 5.26%   |
| Samsung SCX-4200 series           | 1         | 5.26%   |
| Samsung SCX-3400 Series           | 1         | 5.26%   |
| Samsung SCX-3200 Series           | 1         | 5.26%   |
| Samsung M332x 382x 402x Series    | 1         | 5.26%   |
| QinHeng CH340S                    | 1         | 5.26%   |
| Pantum P2200 series               | 1         | 5.26%   |
| Panasonic (Matsushita) KX-MB283RU | 1         | 5.26%   |
| HP LaserJet M402dn                | 1         | 5.26%   |
| Canon MF4410                      | 1         | 5.26%   |
| Canon MF4010 series               | 1         | 5.26%   |
| Canon MF3110                      | 1         | 5.26%   |
| Canon imageRUNNER1133 series      | 1         | 5.26%   |
| Canon G1010 series                | 1         | 5.26%   |
| Brother HL-L2300D series          | 1         | 5.26%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LIDE 25  | 1         | 50%     |
| Canon CanoScan LiDE 110 | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 58        | 21.97%  |
| Cheng Uei Precision Industry (Foxlink) | 31        | 11.74%  |
| Alcor Micro                            | 24        | 9.09%   |
| Acer                                   | 24        | 9.09%   |
| IMC Networks                           | 21        | 7.95%   |
| Logitech                               | 16        | 6.06%   |
| Realtek Semiconductor                  | 14        | 5.3%    |
| Sunplus Innovation Technology          | 13        | 4.92%   |
| Quanta                                 | 10        | 3.79%   |
| Microdia                               | 9         | 3.41%   |
| Suyin                                  | 7         | 2.65%   |
| Syntek                                 | 6         | 2.27%   |
| Apple                                  | 6         | 2.27%   |
| Z-Star Microelectronics                | 4         | 1.52%   |
| lihappe8                               | 3         | 1.14%   |
| Unknown                                | 2         | 0.76%   |
| Sonix Technology                       | 2         | 0.76%   |
| Lite-On Technology                     | 2         | 0.76%   |
| Y Media                                | 1         | 0.38%   |
| SunplusIT                              | 1         | 0.38%   |
| Silicon Motion                         | 1         | 0.38%   |
| Ricoh                                  | 1         | 0.38%   |
| Primax Electronics                     | 1         | 0.38%   |
| Microsoft                              | 1         | 0.38%   |
| Importek                               | 1         | 0.38%   |
| icSpring                               | 1         | 0.38%   |
| Hewlett-Packard                        | 1         | 0.38%   |
| GEMBIRD                                | 1         | 0.38%   |
| ALi                                    | 1         | 0.38%   |
| Unknown                                | 1         | 0.38%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Alcor Micro USB 2.0 PC Camera                                  | 21        | 7.84%   |
| Acer BisonCam,NB Pro                                           | 16        | 5.97%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 15        | 5.6%    |
| Chicony Integrated Camera                                      | 14        | 5.22%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera            | 12        | 4.48%   |
| Chicony HP HD Camera                                           | 11        | 4.1%    |
| Logitech Webcam C270                                           | 10        | 3.73%   |
| Sunplus Integrated_Webcam_HD                                   | 7         | 2.61%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 7         | 2.61%   |
| Chicony USB2.0 Camera                                          | 6         | 2.24%   |
| Realtek MTD camera                                             | 5         | 1.87%   |
| Microdia Webcam Vitade AF                                      | 5         | 1.87%   |
| Chicony USB camera                                             | 5         | 1.87%   |
| Realtek USB Camera                                             | 4         | 1.49%   |
| IMC Networks Integrated Camera                                 | 4         | 1.49%   |
| IMC Networks HD Camera                                         | 4         | 1.49%   |
| Syntek Integrated Camera                                       | 3         | 1.12%   |
| Sunplus BKX Usb FHD Camera                                     | 3         | 1.12%   |
| Quanta ov9734_techfront_camera                                 | 3         | 1.12%   |
| Quanta HP TrueVision HD Camera                                 | 3         | 1.12%   |
| Microdia USB 2.0 Camera                                        | 3         | 1.12%   |
| lihappe8 USB 2.0 Camera                                        | 3         | 1.12%   |
| Chicony USB2.0 FHD Camera                                      | 3         | 1.12%   |
| Chicony HD WebCam                                              | 3         | 1.12%   |
| Apple Built-in iSight                                          | 3         | 1.12%   |
| Acer BisonCam, NB Pro                                          | 3         | 1.12%   |
| Z-Star Vega USB 2.0 Camera                                     | 2         | 0.75%   |
| Syntek Lenovo EasyCamera                                       | 2         | 0.75%   |
| Suyin 1.3M HD WebCam                                           | 2         | 0.75%   |
| Sunplus Asus Webcam                                            | 2         | 0.75%   |
| Sonix USB2.0 HD UVC WebCam                                     | 2         | 0.75%   |
| Logitech C505 HD Webcam                                        | 2         | 0.75%   |
| Chicony VGA Webcam                                             | 2         | 0.75%   |
| Chicony Lenovo EasyCamera                                      | 2         | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 2         | 0.75%   |
| Alcor Micro USB Camera                                         | 2         | 0.75%   |
| Acer USB HD Webcam                                             | 2         | 0.75%   |
| Z-Star Venus USB2.0 Camera                                     | 1         | 0.37%   |
| Z-Star Namuga 1.3M Webcam                                      | 1         | 0.37%   |
| Y Media USB Camera                                             | 1         | 0.37%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 8         | 32%     |
| Validity Sensors           | 6         | 24%     |
| Synaptics                  | 3         | 12%     |
| LighTuning Technology      | 3         | 12%     |
| Elan Microelectronics      | 3         | 12%     |
| Upek                       | 1         | 4%      |
| Focal-systems.Corp         | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                    | 8         | 32%     |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 8%      |
| Validity Sensors VFS491                                | 2         | 8%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 2         | 8%      |
| LighTuning Fingerprint Reader                          | 2         | 8%      |
| Elan ELAN:Fingerprint                                  | 2         | 8%      |
| Validity Sensors VFS495 Fingerprint Reader             | 1         | 4%      |
| Validity Sensors Fingerprint scanner                   | 1         | 4%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 1         | 4%      |
| LighTuning EgisTec Touch Fingerprint Sensor            | 1         | 4%      |
| Focal-systems.Corp FT9201Fingerprint.                  | 1         | 4%      |
| Elan ELAN:ARM-M4                                       | 1         | 4%      |
| Unknown                                                | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Alcor Micro | 3         | 60%     |
| Broadcom    | 1         | 20%     |
| Aktiv       | 1         | 20%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader | 3         | 60%     |
| Broadcom 5880                       | 1         | 20%     |
| Aktiv Rutoken lite                  | 1         | 20%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 395       | 82.98%  |
| 1     | 54        | 11.34%  |
| 2     | 13        | 2.73%   |
| 4     | 6         | 1.26%   |
| 5     | 4         | 0.84%   |
| 3     | 4         | 0.84%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 27        | 24.55%  |
| Fingerprint reader       | 25        | 22.73%  |
| Graphics card            | 22        | 20%     |
| Unassigned class         | 9         | 8.18%   |
| Net/ethernet             | 6         | 5.45%   |
| Multimedia controller    | 5         | 4.55%   |
| Chipcard                 | 5         | 4.55%   |
| Sound                    | 3         | 2.73%   |
| Net/wireless             | 3         | 2.73%   |
| Camera                   | 2         | 1.82%   |
| Bluetooth                | 2         | 1.82%   |
| Flash memory             | 1         | 0.91%   |

