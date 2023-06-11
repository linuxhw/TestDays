Elementary 7 - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Elementary 7.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary_7/Desktop/README.md) and [notebooks](/Dist/Elementary_7/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 228

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [08114e8a97](https://linux-hardware.org/?probe=08114e8a97) | Jun 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [93555cfd25](https://linux-hardware.org/?probe=93555cfd25) | Jun 10, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [2e6d82c14f](https://linux-hardware.org/?probe=2e6d82c14f) | Jun 10, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [604f40e700](https://linux-hardware.org/?probe=604f40e700) | Jun 09, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [d001c4cf1c](https://linux-hardware.org/?probe=d001c4cf1c) | Jun 09, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d487214e2a](https://linux-hardware.org/?probe=d487214e2a) | Jun 08, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [ddefeff960](https://linux-hardware.org/?probe=ddefeff960) | Jun 08, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [6c62565787](https://linux-hardware.org/?probe=6c62565787) | Jun 07, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [b2281ad2cb](https://linux-hardware.org/?probe=b2281ad2cb) | Jun 06, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [77fe6db865](https://linux-hardware.org/?probe=77fe6db865) | Jun 06, 2023 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [1ebf23281e](https://linux-hardware.org/?probe=1ebf23281e) | Jun 04, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [274b78cda3](https://linux-hardware.org/?probe=274b78cda3) | Jun 03, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [119fd5249f](https://linux-hardware.org/?probe=119fd5249f) | Jun 03, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [532dea434a](https://linux-hardware.org/?probe=532dea434a) | Jun 02, 2023 |
| HP            | G62                         | Notebook    | [f2600c2f4b](https://linux-hardware.org/?probe=f2600c2f4b) | Jun 01, 2023 |
| Lenovo        | ThinkPad T460 20FMS08H00    | Notebook    | [71208c2344](https://linux-hardware.org/?probe=71208c2344) | Jun 01, 2023 |
| Lenovo        | ThinkBook 13s G3 ACN 20Y... | Notebook    | [827e0203ac](https://linux-hardware.org/?probe=827e0203ac) | May 31, 2023 |
| Gigabyte      | GA-E6010N                   | Desktop     | [563074319d](https://linux-hardware.org/?probe=563074319d) | May 31, 2023 |
| Lenovo        | 36C5 SDK0Q55724 WIN 3273... | Desktop     | [01076d8e8b](https://linux-hardware.org/?probe=01076d8e8b) | May 30, 2023 |
| ASUSTek       | X550WA                      | Notebook    | [864236b0c9](https://linux-hardware.org/?probe=864236b0c9) | May 29, 2023 |
| PCBOX         | Kant                        | Notebook    | [1e2f772d05](https://linux-hardware.org/?probe=1e2f772d05) | May 29, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [16b9dfbbe0](https://linux-hardware.org/?probe=16b9dfbbe0) | May 29, 2023 |
| HP            | ProBook 440 G6              | Notebook    | [35d14ed328](https://linux-hardware.org/?probe=35d14ed328) | May 29, 2023 |
| HP            | ProBook 440 G6              | Notebook    | [36a3563566](https://linux-hardware.org/?probe=36a3563566) | May 29, 2023 |
| Chuwi         | UBook Pro                   | Tablet      | [190fe84e14](https://linux-hardware.org/?probe=190fe84e14) | May 27, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e29fb14e81](https://linux-hardware.org/?probe=e29fb14e81) | May 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [84d0d9807f](https://linux-hardware.org/?probe=84d0d9807f) | May 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [124c8183a8](https://linux-hardware.org/?probe=124c8183a8) | May 26, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [1ddb5fe9a0](https://linux-hardware.org/?probe=1ddb5fe9a0) | May 26, 2023 |
| Dell          | Precision 5530              | Notebook    | [702b4d7914](https://linux-hardware.org/?probe=702b4d7914) | May 26, 2023 |
| Dell          | Latitude E5470              | Notebook    | [6054d2ee2b](https://linux-hardware.org/?probe=6054d2ee2b) | May 25, 2023 |
| Unknown       | Unknown                     | Tablet      | [8a83b799d5](https://linux-hardware.org/?probe=8a83b799d5) | May 24, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [4ddad1d733](https://linux-hardware.org/?probe=4ddad1d733) | May 24, 2023 |
| HP            | ProBook 4310s               | Notebook    | [1a32d434c0](https://linux-hardware.org/?probe=1a32d434c0) | May 21, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [61ebf173dc](https://linux-hardware.org/?probe=61ebf173dc) | May 21, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [7f15c1b9e3](https://linux-hardware.org/?probe=7f15c1b9e3) | May 21, 2023 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [ff730fcbf6](https://linux-hardware.org/?probe=ff730fcbf6) | May 20, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [73d62695e4](https://linux-hardware.org/?probe=73d62695e4) | May 18, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [56aa17165e](https://linux-hardware.org/?probe=56aa17165e) | May 18, 2023 |
| HP            | ProBook 4310s               | Notebook    | [dfcb51e697](https://linux-hardware.org/?probe=dfcb51e697) | May 17, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [004f548439](https://linux-hardware.org/?probe=004f548439) | May 17, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [8fb1a89166](https://linux-hardware.org/?probe=8fb1a89166) | May 17, 2023 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [3776285fc1](https://linux-hardware.org/?probe=3776285fc1) | May 16, 2023 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [155b921e10](https://linux-hardware.org/?probe=155b921e10) | May 13, 2023 |
| HP            | 1998                        | Desktop     | [b806151d9f](https://linux-hardware.org/?probe=b806151d9f) | May 12, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [81e3161a34](https://linux-hardware.org/?probe=81e3161a34) | May 11, 2023 |
| Acer          | Aspire E3-111               | Notebook    | [1060697095](https://linux-hardware.org/?probe=1060697095) | May 10, 2023 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [58000b3a57](https://linux-hardware.org/?probe=58000b3a57) | May 09, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [1b0786ec5e](https://linux-hardware.org/?probe=1b0786ec5e) | May 07, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [ea0b55ed61](https://linux-hardware.org/?probe=ea0b55ed61) | May 07, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [df06b3c5b3](https://linux-hardware.org/?probe=df06b3c5b3) | May 07, 2023 |
| MSI           | GE62VR 6RF                  | Notebook    | [bac71eb24d](https://linux-hardware.org/?probe=bac71eb24d) | May 06, 2023 |
| Lenovo        | ThinkPad P51s 20HB001TUS    | Notebook    | [eac4ebdef0](https://linux-hardware.org/?probe=eac4ebdef0) | May 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [834d2304aa](https://linux-hardware.org/?probe=834d2304aa) | May 06, 2023 |
| Intel         | JSL MRD                     | Desktop     | [76ff5c3bd7](https://linux-hardware.org/?probe=76ff5c3bd7) | May 05, 2023 |
| Clevo         | NL41MU2                     | Notebook    | [6a80029392](https://linux-hardware.org/?probe=6a80029392) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [fe61386871](https://linux-hardware.org/?probe=fe61386871) | May 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [764f38bb65](https://linux-hardware.org/?probe=764f38bb65) | May 05, 2023 |
| Dell          | 02N3WF A02                  | Desktop     | [3f10b3ca43](https://linux-hardware.org/?probe=3f10b3ca43) | May 04, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [c5927045a3](https://linux-hardware.org/?probe=c5927045a3) | May 04, 2023 |
| HP            | 1998                        | Desktop     | [6f816ac95a](https://linux-hardware.org/?probe=6f816ac95a) | Apr 29, 2023 |
| MSI           | GE62VR 6RF                  | Notebook    | [97acececd3](https://linux-hardware.org/?probe=97acececd3) | Apr 28, 2023 |
| Apple         | MacBookPro5,2               | Notebook    | [c188ae4d7d](https://linux-hardware.org/?probe=c188ae4d7d) | Apr 28, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [7aa3832621](https://linux-hardware.org/?probe=7aa3832621) | Apr 28, 2023 |
| MSI           | GE62VR 6RF                  | Notebook    | [2a9fcae8c3](https://linux-hardware.org/?probe=2a9fcae8c3) | Apr 28, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [0f8543fc85](https://linux-hardware.org/?probe=0f8543fc85) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6704ecd3d3](https://linux-hardware.org/?probe=6704ecd3d3) | Apr 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [4e8b00c534](https://linux-hardware.org/?probe=4e8b00c534) | Apr 27, 2023 |
| MSI           | PE70 6QE                    | Notebook    | [87c8761eff](https://linux-hardware.org/?probe=87c8761eff) | Apr 27, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [b03cd2f2d2](https://linux-hardware.org/?probe=b03cd2f2d2) | Apr 26, 2023 |
| MSI           | PE70 6QE                    | Notebook    | [53dd8334ac](https://linux-hardware.org/?probe=53dd8334ac) | Apr 26, 2023 |
| HP            | 8055                        | Desktop     | [a897208085](https://linux-hardware.org/?probe=a897208085) | Apr 26, 2023 |
| Lenovo        | G580 20150                  | Notebook    | [5d8b07dbbd](https://linux-hardware.org/?probe=5d8b07dbbd) | Apr 25, 2023 |
| ASRock        | B660M-C                     | Desktop     | [849fc5d462](https://linux-hardware.org/?probe=849fc5d462) | Apr 25, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [8fd18554d1](https://linux-hardware.org/?probe=8fd18554d1) | Apr 24, 2023 |
| MACHINIST     | E5-MR9A PRO V1.1            | Desktop     | [eebce73217](https://linux-hardware.org/?probe=eebce73217) | Apr 23, 2023 |
| Dell          | Latitude E4300              | Notebook    | [f58f44d242](https://linux-hardware.org/?probe=f58f44d242) | Apr 22, 2023 |
| Lenovo        | V14 G2 ITL 82KA             | Notebook    | [763953fb60](https://linux-hardware.org/?probe=763953fb60) | Apr 22, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [50a18b5e94](https://linux-hardware.org/?probe=50a18b5e94) | Apr 19, 2023 |
| Foxconn       | A76GMV                      | Desktop     | [bafa62c759](https://linux-hardware.org/?probe=bafa62c759) | Apr 18, 2023 |
| Foxconn       | A76GMV                      | Desktop     | [f129cb2de1](https://linux-hardware.org/?probe=f129cb2de1) | Apr 18, 2023 |
| HP            | Pavilion g6                 | Notebook    | [4d60e2b7da](https://linux-hardware.org/?probe=4d60e2b7da) | Apr 17, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [94bf014457](https://linux-hardware.org/?probe=94bf014457) | Apr 17, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [2ebc6a2f61](https://linux-hardware.org/?probe=2ebc6a2f61) | Apr 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [ff6dbdcc10](https://linux-hardware.org/?probe=ff6dbdcc10) | Apr 15, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [845e7bfdd1](https://linux-hardware.org/?probe=845e7bfdd1) | Apr 15, 2023 |
| MSI           | PE70 6QE                    | Notebook    | [936a7d1fe3](https://linux-hardware.org/?probe=936a7d1fe3) | Apr 15, 2023 |
| Dell          | Latitude 5420               | Notebook    | [4c6427b3fc](https://linux-hardware.org/?probe=4c6427b3fc) | Apr 14, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [e311d21def](https://linux-hardware.org/?probe=e311d21def) | Apr 13, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | Desktop     | [8e05a5e529](https://linux-hardware.org/?probe=8e05a5e529) | Apr 13, 2023 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [0c03014734](https://linux-hardware.org/?probe=0c03014734) | Apr 12, 2023 |
| Apple         | MacBookAir3,2               | Notebook    | [c750ece414](https://linux-hardware.org/?probe=c750ece414) | Apr 12, 2023 |
| Dell          | Latitude E5570              | Notebook    | [81eaf54f19](https://linux-hardware.org/?probe=81eaf54f19) | Apr 07, 2023 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [5c12ed53b7](https://linux-hardware.org/?probe=5c12ed53b7) | Apr 05, 2023 |
| Lenovo        | Aptio CRB SDK0F82993 WIN    | Mini pc     | [6896e5d9e2](https://linux-hardware.org/?probe=6896e5d9e2) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [473a8c1d7b](https://linux-hardware.org/?probe=473a8c1d7b) | Apr 05, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [56079f49e3](https://linux-hardware.org/?probe=56079f49e3) | Apr 04, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [3f9238067d](https://linux-hardware.org/?probe=3f9238067d) | Apr 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [1a3e968dff](https://linux-hardware.org/?probe=1a3e968dff) | Apr 03, 2023 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [d3bd81c4fd](https://linux-hardware.org/?probe=d3bd81c4fd) | Apr 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [f7f207f61c](https://linux-hardware.org/?probe=f7f207f61c) | Apr 02, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [e06d57c27a](https://linux-hardware.org/?probe=e06d57c27a) | Apr 01, 2023 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [d4c718bdab](https://linux-hardware.org/?probe=d4c718bdab) | Apr 01, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [5a83c18a3e](https://linux-hardware.org/?probe=5a83c18a3e) | Apr 01, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [94f75ee798](https://linux-hardware.org/?probe=94f75ee798) | Apr 01, 2023 |
| ASUSTek       | Zenbook UN5401QAB_UN5401... | Convertible | [448d1a491c](https://linux-hardware.org/?probe=448d1a491c) | Mar 31, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [a967e73159](https://linux-hardware.org/?probe=a967e73159) | Mar 30, 2023 |
| Dell          | Latitude E7440              | Notebook    | [1159c854cd](https://linux-hardware.org/?probe=1159c854cd) | Mar 29, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [a9a8004509](https://linux-hardware.org/?probe=a9a8004509) | Mar 29, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [1dccfbe9f4](https://linux-hardware.org/?probe=1dccfbe9f4) | Mar 29, 2023 |
| Dell          | Latitude 5420               | Notebook    | [d714c46c4f](https://linux-hardware.org/?probe=d714c46c4f) | Mar 29, 2023 |
| Unknown       | Unknown                     | Desktop     | [fb22157f03](https://linux-hardware.org/?probe=fb22157f03) | Mar 28, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [5590ec1365](https://linux-hardware.org/?probe=5590ec1365) | Mar 28, 2023 |
| AZW           | U59                         | Desktop     | [7674bb8dc9](https://linux-hardware.org/?probe=7674bb8dc9) | Mar 27, 2023 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [39995c1c00](https://linux-hardware.org/?probe=39995c1c00) | Mar 24, 2023 |
| Dell          | Latitude E7440              | Notebook    | [1a986dbeb8](https://linux-hardware.org/?probe=1a986dbeb8) | Mar 24, 2023 |
| HONOR         | HYM-WXX                     | Notebook    | [df318ed208](https://linux-hardware.org/?probe=df318ed208) | Mar 21, 2023 |
| Fujitsu       | LIFEBOOK AH530              | Notebook    | [e40cf4f577](https://linux-hardware.org/?probe=e40cf4f577) | Mar 18, 2023 |
| Dell          | Latitude E5570              | Notebook    | [a15d1b43ca](https://linux-hardware.org/?probe=a15d1b43ca) | Mar 17, 2023 |
| Dell          | Latitude E5570              | Notebook    | [dd07b0c3b3](https://linux-hardware.org/?probe=dd07b0c3b3) | Mar 17, 2023 |
| Dell          | G3 3590                     | Notebook    | [9ef42643d8](https://linux-hardware.org/?probe=9ef42643d8) | Mar 16, 2023 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [1674c37cf9](https://linux-hardware.org/?probe=1674c37cf9) | Mar 16, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [03e5d43f27](https://linux-hardware.org/?probe=03e5d43f27) | Mar 15, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [4c49d73583](https://linux-hardware.org/?probe=4c49d73583) | Mar 15, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [c6ff6d14a0](https://linux-hardware.org/?probe=c6ff6d14a0) | Mar 15, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [28f8273eb5](https://linux-hardware.org/?probe=28f8273eb5) | Mar 15, 2023 |
| HP            | 805A                        | Desktop     | [5401e12606](https://linux-hardware.org/?probe=5401e12606) | Mar 14, 2023 |
| HP            | 3033h                       | Desktop     | [ab5e388ea9](https://linux-hardware.org/?probe=ab5e388ea9) | Mar 14, 2023 |
| HP            | 3033h                       | Desktop     | [38ac77726b](https://linux-hardware.org/?probe=38ac77726b) | Mar 13, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [39d0e8595c](https://linux-hardware.org/?probe=39d0e8595c) | Mar 12, 2023 |
| MSI           | GT72 2QE                    | Notebook    | [b3c4766473](https://linux-hardware.org/?probe=b3c4766473) | Mar 12, 2023 |
| Lenovo        | ThinkPad X240 20AMS0XP0S    | Notebook    | [a2ee9a2818](https://linux-hardware.org/?probe=a2ee9a2818) | Mar 12, 2023 |
| MSI           | B365M PRO-VH                | Desktop     | [023f42d6d1](https://linux-hardware.org/?probe=023f42d6d1) | Mar 12, 2023 |
| Fujitsu       | LIFEBOOK A359               | Notebook    | [0fa1ebbc11](https://linux-hardware.org/?probe=0fa1ebbc11) | Mar 11, 2023 |
| Fujitsu       | LIFEBOOK A359               | Notebook    | [f977012127](https://linux-hardware.org/?probe=f977012127) | Mar 11, 2023 |
| Apple         | MacBookPro11,2              | Notebook    | [fce6120754](https://linux-hardware.org/?probe=fce6120754) | Mar 11, 2023 |
| Acer          | Aspire A715-72G             | Notebook    | [32b2d1b194](https://linux-hardware.org/?probe=32b2d1b194) | Mar 11, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [82b5297ab8](https://linux-hardware.org/?probe=82b5297ab8) | Mar 11, 2023 |
| Toshiba       | TECRA Z40-C                 | Notebook    | [a4ba2ff90e](https://linux-hardware.org/?probe=a4ba2ff90e) | Mar 10, 2023 |
| MSI           | CX61 2PC                    | Notebook    | [cb9f5fa992](https://linux-hardware.org/?probe=cb9f5fa992) | Mar 10, 2023 |
| Sony          | VPCEH2C5E                   | Notebook    | [adf4a69310](https://linux-hardware.org/?probe=adf4a69310) | Mar 07, 2023 |
| Sony          | VPCEH2C5E                   | Notebook    | [9e5b625dda](https://linux-hardware.org/?probe=9e5b625dda) | Mar 07, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [3547dd712b](https://linux-hardware.org/?probe=3547dd712b) | Mar 07, 2023 |
| Inventec      | Z CLASS A02                 | Desktop     | [c45e770987](https://linux-hardware.org/?probe=c45e770987) | Mar 06, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [4ecfeecd31](https://linux-hardware.org/?probe=4ecfeecd31) | Mar 06, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [5afd8e3f42](https://linux-hardware.org/?probe=5afd8e3f42) | Mar 04, 2023 |
| Microsoft     | Surface Book                | Tablet      | [cc3ad3e0d2](https://linux-hardware.org/?probe=cc3ad3e0d2) | Mar 02, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [817b72f78f](https://linux-hardware.org/?probe=817b72f78f) | Mar 02, 2023 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [053c6d5368](https://linux-hardware.org/?probe=053c6d5368) | Mar 02, 2023 |
| Microsoft     | Surface Book                | Tablet      | [d58385d1e6](https://linux-hardware.org/?probe=d58385d1e6) | Mar 01, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [fa757fb12a](https://linux-hardware.org/?probe=fa757fb12a) | Mar 01, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [1025a9748f](https://linux-hardware.org/?probe=1025a9748f) | Mar 01, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [dabd3e0232](https://linux-hardware.org/?probe=dabd3e0232) | Mar 01, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [e189c60b09](https://linux-hardware.org/?probe=e189c60b09) | Mar 01, 2023 |
| GPU Compan... | GWTN156-11                  | Notebook    | [3883ba28c7](https://linux-hardware.org/?probe=3883ba28c7) | Mar 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [1c5f8fef49](https://linux-hardware.org/?probe=1c5f8fef49) | Feb 28, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [216ad20179](https://linux-hardware.org/?probe=216ad20179) | Feb 28, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [573644760d](https://linux-hardware.org/?probe=573644760d) | Feb 28, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [371a95fb3d](https://linux-hardware.org/?probe=371a95fb3d) | Feb 28, 2023 |
| Fujitsu       | LIFEBOOK E744               | Notebook    | [e331c5e257](https://linux-hardware.org/?probe=e331c5e257) | Feb 27, 2023 |
| Acer          | Predator G3620              | Desktop     | [72f3382b60](https://linux-hardware.org/?probe=72f3382b60) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [2071bc50ce](https://linux-hardware.org/?probe=2071bc50ce) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [472c035387](https://linux-hardware.org/?probe=472c035387) | Feb 27, 2023 |
| Dell          | 07PR60 A01                  | Desktop     | [c071b7ef1c](https://linux-hardware.org/?probe=c071b7ef1c) | Feb 27, 2023 |
| Acer          | Aspire E5-771               | Notebook    | [73c974942f](https://linux-hardware.org/?probe=73c974942f) | Feb 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [a66f75c107](https://linux-hardware.org/?probe=a66f75c107) | Feb 26, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [ce9dda227f](https://linux-hardware.org/?probe=ce9dda227f) | Feb 25, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [50a16e7924](https://linux-hardware.org/?probe=50a16e7924) | Feb 25, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [b815c24c07](https://linux-hardware.org/?probe=b815c24c07) | Feb 24, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [e578b951f9](https://linux-hardware.org/?probe=e578b951f9) | Feb 24, 2023 |
| HP            | ProBook 430 G4              | Notebook    | [0dc5add67b](https://linux-hardware.org/?probe=0dc5add67b) | Feb 24, 2023 |
| Lenovo        | ThinkPad T400s 2808D9G      | Notebook    | [b101883e65](https://linux-hardware.org/?probe=b101883e65) | Feb 24, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [6db3a90234](https://linux-hardware.org/?probe=6db3a90234) | Feb 24, 2023 |
| Lenovo        | V14 G2 ITL 82KA             | Notebook    | [0a3d750f36](https://linux-hardware.org/?probe=0a3d750f36) | Feb 23, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [ddd8c34644](https://linux-hardware.org/?probe=ddd8c34644) | Feb 22, 2023 |
| Lenovo        | ThinkPad T440p 20AWS38H0... | Notebook    | [c79a8f48f9](https://linux-hardware.org/?probe=c79a8f48f9) | Feb 20, 2023 |
| Lenovo        | V14 G2 ITL 82KA             | Notebook    | [7ee9e59831](https://linux-hardware.org/?probe=7ee9e59831) | Feb 20, 2023 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [13a132516b](https://linux-hardware.org/?probe=13a132516b) | Feb 18, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [2751aac3e0](https://linux-hardware.org/?probe=2751aac3e0) | Feb 16, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [76ab936a75](https://linux-hardware.org/?probe=76ab936a75) | Feb 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [68f0415788](https://linux-hardware.org/?probe=68f0415788) | Feb 16, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [2560ba7644](https://linux-hardware.org/?probe=2560ba7644) | Feb 16, 2023 |
| Foxconn       | 2ADA                        | Desktop     | [e0f89bbca1](https://linux-hardware.org/?probe=e0f89bbca1) | Feb 16, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [535eda0feb](https://linux-hardware.org/?probe=535eda0feb) | Feb 16, 2023 |
| HP            | 550                         | Notebook    | [81b67f211d](https://linux-hardware.org/?probe=81b67f211d) | Feb 15, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [150c1de326](https://linux-hardware.org/?probe=150c1de326) | Feb 15, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [e8a460c42c](https://linux-hardware.org/?probe=e8a460c42c) | Feb 15, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [a92df0196e](https://linux-hardware.org/?probe=a92df0196e) | Feb 15, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [92ab9b2e0d](https://linux-hardware.org/?probe=92ab9b2e0d) | Feb 14, 2023 |
| HP            | 805D                        | Desktop     | [217784712c](https://linux-hardware.org/?probe=217784712c) | Feb 14, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [f22c83d683](https://linux-hardware.org/?probe=f22c83d683) | Feb 14, 2023 |
| HP            | OMEN by Laptop 17-ck0xxx    | Notebook    | [12431d8083](https://linux-hardware.org/?probe=12431d8083) | Feb 14, 2023 |
| MSI           | B85-G43 GAMING              | Desktop     | [b2b66e40e1](https://linux-hardware.org/?probe=b2b66e40e1) | Feb 14, 2023 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [f0899499e5](https://linux-hardware.org/?probe=f0899499e5) | Feb 13, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [537d29b0d5](https://linux-hardware.org/?probe=537d29b0d5) | Feb 12, 2023 |
| Acer          | Extensa 5230                | Notebook    | [f27f478fa5](https://linux-hardware.org/?probe=f27f478fa5) | Feb 12, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [97bf2aa6a5](https://linux-hardware.org/?probe=97bf2aa6a5) | Feb 12, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | Notebook    | [a1d85b3098](https://linux-hardware.org/?probe=a1d85b3098) | Feb 10, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [76711a4e32](https://linux-hardware.org/?probe=76711a4e32) | Feb 10, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [9de542dff7](https://linux-hardware.org/?probe=9de542dff7) | Feb 09, 2023 |
| ASUSTek       | ZenBook UX434FAC_UX434FA... | Notebook    | [6e8ed5d5d6](https://linux-hardware.org/?probe=6e8ed5d5d6) | Feb 09, 2023 |
| Lenovo        | ThinkPad E560 20EV003DSP    | Notebook    | [27731362e2](https://linux-hardware.org/?probe=27731362e2) | Feb 09, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [b906f960a0](https://linux-hardware.org/?probe=b906f960a0) | Feb 08, 2023 |
| Apple         | Mac-F42386C8 PVT            | All in one  | [1e6a345b00](https://linux-hardware.org/?probe=1e6a345b00) | Feb 07, 2023 |
| HP            | Laptop 14-bs0xx             | Notebook    | [c3607bb4c2](https://linux-hardware.org/?probe=c3607bb4c2) | Feb 07, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [73b3c1c661](https://linux-hardware.org/?probe=73b3c1c661) | Feb 06, 2023 |
| HP            | Laptop 17-by3xxx            | Notebook    | [07ea9d3c2f](https://linux-hardware.org/?probe=07ea9d3c2f) | Feb 06, 2023 |
| Gigabyte      | F2A88XM-DS2                 | Desktop     | [d9313ff1c1](https://linux-hardware.org/?probe=d9313ff1c1) | Feb 05, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [30e2a88930](https://linux-hardware.org/?probe=30e2a88930) | Feb 05, 2023 |
| Acer          | Aspire 8935G                | Notebook    | [10f8560601](https://linux-hardware.org/?probe=10f8560601) | Feb 05, 2023 |
| Acer          | Aspire 8935G                | Notebook    | [be37cc70f5](https://linux-hardware.org/?probe=be37cc70f5) | Feb 05, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [8d67e1438d](https://linux-hardware.org/?probe=8d67e1438d) | Feb 05, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [8bdb86b164](https://linux-hardware.org/?probe=8bdb86b164) | Feb 04, 2023 |
| ASUSTek       | P7P55 LX                    | Desktop     | [3786e7a211](https://linux-hardware.org/?probe=3786e7a211) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [9d397c2187](https://linux-hardware.org/?probe=9d397c2187) | Feb 04, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [7b676dec23](https://linux-hardware.org/?probe=7b676dec23) | Feb 04, 2023 |
| Dell          | Vostro 3460                 | Notebook    | [8aa57f1d6d](https://linux-hardware.org/?probe=8aa57f1d6d) | Feb 03, 2023 |
| Dell          | Vostro 3460                 | Notebook    | [78919f6127](https://linux-hardware.org/?probe=78919f6127) | Feb 03, 2023 |
| Alienware     | x17 R2                      | Notebook    | [474a70c148](https://linux-hardware.org/?probe=474a70c148) | Feb 03, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [42c3899a37](https://linux-hardware.org/?probe=42c3899a37) | Feb 02, 2023 |
| Sony          | SVF1521O4E                  | Notebook    | [e2d47879d4](https://linux-hardware.org/?probe=e2d47879d4) | Feb 02, 2023 |
| Dell          | XPS 13 7390 2-in-1          | Convertible | [fdf7b5e80e](https://linux-hardware.org/?probe=fdf7b5e80e) | Feb 02, 2023 |
| Lenovo        | ThinkPad X230 23259S9       | Notebook    | [3d9e74535f](https://linux-hardware.org/?probe=3d9e74535f) | Feb 01, 2023 |
| Dell          | 0GDJXY A00                  | All in one  | [1ce7db78c1](https://linux-hardware.org/?probe=1ce7db78c1) | Feb 01, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [c2a4529e33](https://linux-hardware.org/?probe=c2a4529e33) | Jan 30, 2023 |
| Star Labs     | StarBook                    | Notebook    | [784ae24356](https://linux-hardware.org/?probe=784ae24356) | Jan 15, 2023 |
| Unknown       | HX90                        | Desktop     | [af144f98b6](https://linux-hardware.org/?probe=af144f98b6) | Jan 05, 2023 |
| Lenovo        | ThinkPad T495 20NKS01W02    | Notebook    | [cc7b02033a](https://linux-hardware.org/?probe=cc7b02033a) | Dec 24, 2022 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.0-58-generic      | 42        | 25.93%  |
| 5.19.0-35-generic      | 23        | 14.2%   |
| 5.19.0-41-generic      | 22        | 13.58%  |
| 5.19.0-32-generic      | 22        | 13.58%  |
| 5.19.0-38-generic      | 16        | 9.88%   |
| 5.19.0-43-generic      | 9         | 5.56%   |
| 5.15.0-60-generic      | 9         | 5.56%   |
| 5.19.0-40-generic      | 6         | 3.7%    |
| 5.19.0-42-generic      | 4         | 2.47%   |
| 5.15.0-56-generic      | 2         | 1.23%   |
| 6.2.8-3-liquorix-amd64 | 1         | 0.62%   |
| 6.2.7-060207-generic   | 1         | 0.62%   |
| 6.2.2-surface          | 1         | 0.62%   |
| 6.2.14-surface         | 1         | 0.62%   |
| 6.1.9-060109-generic   | 1         | 0.62%   |
| 6.1.6-060106-generic   | 1         | 0.62%   |
| 6.1.0-1013-oem         | 1         | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19.0  | 96        | 61.54%  |
| 5.15.0  | 53        | 33.97%  |
| 6.2.8   | 1         | 0.64%   |
| 6.2.7   | 1         | 0.64%   |
| 6.2.2   | 1         | 0.64%   |
| 6.2.14  | 1         | 0.64%   |
| 6.1.9   | 1         | 0.64%   |
| 6.1.6   | 1         | 0.64%   |
| 6.1.0   | 1         | 0.64%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.19    | 96        | 61.94%  |
| 5.15    | 53        | 34.19%  |
| 6.2     | 3         | 1.94%   |
| 6.1     | 3         | 1.94%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 153       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Pantheon | 153       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 153       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 123       | 80.39%  |
| LightDM | 30        | 19.61%  |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 63        | 40.91%  |
| de_DE | 25        | 16.23%  |
| es_ES | 13        | 8.44%   |
| ru_RU | 12        | 7.79%   |
| fr_FR | 6         | 3.9%    |
| en_GB | 5         | 3.25%   |
| pl_PL | 4         | 2.6%    |
| it_IT | 4         | 2.6%    |
| sv_SE | 3         | 1.95%   |
| pt_BR | 3         | 1.95%   |
| pt_PT | 2         | 1.3%    |
| nl_NL | 2         | 1.3%    |
| en_AU | 2         | 1.3%    |
| uk_UA | 1         | 0.65%   |
| sk_SK | 1         | 0.65%   |
| nb_NO | 1         | 0.65%   |
| ja_JP | 1         | 0.65%   |
| hu_HU | 1         | 0.65%   |
| fi_FI | 1         | 0.65%   |
| en_CA | 1         | 0.65%   |
| el_GR | 1         | 0.65%   |
| da_DK | 1         | 0.65%   |
| cs_CZ | 1         | 0.65%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 131       | 85.62%  |
| EFI  | 22        | 14.38%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 145       | 94.16%  |
| Tmpfs   | 3         | 1.95%   |
| Btrfs   | 3         | 1.95%   |
| Xfs     | 2         | 1.3%    |
| Overlay | 1         | 0.65%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 123       | 80.39%  |
| GPT     | 26        | 16.99%  |
| MBR     | 4         | 2.61%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 151       | 98.69%  |
| Yes       | 2         | 1.31%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 142       | 92.81%  |
| Yes       | 11        | 7.19%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 25        | 16.34%  |
| ASUSTek Computer    | 22        | 14.38%  |
| Lenovo              | 20        | 13.07%  |
| Apple               | 19        | 12.42%  |
| Dell                | 13        | 8.5%    |
| MSI                 | 9         | 5.88%   |
| Acer                | 8         | 5.23%   |
| Gigabyte Technology | 6         | 3.92%   |
| HUAWEI              | 4         | 2.61%   |
| Fujitsu             | 3         | 1.96%   |
| Unknown             | 3         | 1.96%   |
| Toshiba             | 2         | 1.31%   |
| Sony                | 2         | 1.31%   |
| HONOR               | 2         | 1.31%   |
| Foxconn             | 2         | 1.31%   |
| Star Labs           | 1         | 0.65%   |
| Samsung Electronics | 1         | 0.65%   |
| PCBOX               | 1         | 0.65%   |
| Microsoft           | 1         | 0.65%   |
| MACHINIST           | 1         | 0.65%   |
| Inventec            | 1         | 0.65%   |
| Intel               | 1         | 0.65%   |
| GPU Company         | 1         | 0.65%   |
| Clevo               | 1         | 0.65%   |
| Chuwi               | 1         | 0.65%   |
| AZW                 | 1         | 0.65%   |
| ASRock              | 1         | 0.65%   |
| Alienware           | 1         | 0.65%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 3         | 1.96%   |
| HUAWEI BOD-WXX9                            | 2         | 1.31%   |
| HP 255 G7 Notebook PC                      | 2         | 1.31%   |
| ASUS H110M-A/M.2                           | 2         | 1.31%   |
| Apple iMac12,1                             | 2         | 1.31%   |
| Toshiba TECRA Z40-C                        | 1         | 0.65%   |
| Toshiba Satellite C660                     | 1         | 0.65%   |
| Star Labs StarBook                         | 1         | 0.65%   |
| Sony VPCEH2C5E                             | 1         | 0.65%   |
| Sony SVF1521O4E                            | 1         | 0.65%   |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 1         | 0.65%   |
| PCBOX Kant                                 | 1         | 0.65%   |
| MSI PE70 6QE                               | 1         | 0.65%   |
| MSI MS-7C31                                | 1         | 0.65%   |
| MSI MS-7C02                                | 1         | 0.65%   |
| MSI MS-7B84                                | 1         | 0.65%   |
| MSI MS-7B17                                | 1         | 0.65%   |
| MSI MS-7816                                | 1         | 0.65%   |
| MSI GT72 2QE                               | 1         | 0.65%   |
| MSI GE62VR 6RF                             | 1         | 0.65%   |
| MSI CX61 2PC                               | 1         | 0.65%   |
| Microsoft Surface Pro 7                    | 1         | 0.65%   |
| MACHINIST E5-MR9A PRO V1.1                 | 1         | 0.65%   |
| Lenovo Yoga 6 13ALC7 82UD                  | 1         | 0.65%   |
| Lenovo V14 G2 ITL 82KA                     | 1         | 0.65%   |
| Lenovo ThinkPad X240 20AMS0XP0S            | 1         | 0.65%   |
| Lenovo ThinkPad X230 23259S9               | 1         | 0.65%   |
| Lenovo ThinkPad X13 Gen 1 20T3S3SH0U       | 1         | 0.65%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BSCTO1WW   | 1         | 0.65%   |
| Lenovo ThinkPad T495 20NKS01W02            | 1         | 0.65%   |
| Lenovo ThinkPad T460 20FMS08H00            | 1         | 0.65%   |
| Lenovo ThinkPad T440p 20AWS38H0G           | 1         | 0.65%   |
| Lenovo ThinkPad T400s 2808D9G              | 1         | 0.65%   |
| Lenovo ThinkPad P51s 20HB001TUS            | 1         | 0.65%   |
| Lenovo ThinkPad E560 20EV003DSP            | 1         | 0.65%   |
| Lenovo ThinkBook 13s G3 ACN 20YA           | 1         | 0.65%   |
| Lenovo Legion 5 15ARH05H 82B1              | 1         | 0.65%   |
| Lenovo IdeaPad 320-15IKB 80XL              | 1         | 0.65%   |
| Lenovo IdeaPad 320-15ABR 80XS              | 1         | 0.65%   |
| Lenovo IdeaPad 3 15ALC6 82KU               | 1         | 0.65%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 10        | 6.54%   |
| Acer Aspire        | 7         | 4.58%   |
| HP ProBook         | 5         | 3.27%   |
| HP Pavilion        | 5         | 3.27%   |
| Dell Latitude      | 5         | 3.27%   |
| ASUS ZenBook       | 5         | 3.27%   |
| Lenovo IdeaPad     | 3         | 1.96%   |
| HP Laptop          | 3         | 1.96%   |
| Fujitsu LIFEBOOK   | 3         | 1.96%   |
| Dell XPS           | 3         | 1.96%   |
| Apple MacBookPro11 | 3         | 1.96%   |
| Unknown            | 3         | 1.96%   |
| HUAWEI BOD-WXX9    | 2         | 1.31%   |
| HP EliteDesk       | 2         | 1.31%   |
| HP 255             | 2         | 1.31%   |
| ASUS VivoBook      | 2         | 1.31%   |
| ASUS ROG           | 2         | 1.31%   |
| ASUS PRIME         | 2         | 1.31%   |
| ASUS H110M-A       | 2         | 1.31%   |
| Apple MacBookPro5  | 2         | 1.31%   |
| Apple MacBookAir3  | 2         | 1.31%   |
| Apple iMac12       | 2         | 1.31%   |
| Toshiba TECRA      | 1         | 0.65%   |
| Toshiba Satellite  | 1         | 0.65%   |
| Star Labs StarBook | 1         | 0.65%   |
| Sony VPCEH2C5E     | 1         | 0.65%   |
| Sony SVF1521O4E    | 1         | 0.65%   |
| Samsung 300E4A     | 1         | 0.65%   |
| PCBOX Kant         | 1         | 0.65%   |
| MSI PE70           | 1         | 0.65%   |
| MSI MS-7C31        | 1         | 0.65%   |
| MSI MS-7C02        | 1         | 0.65%   |
| MSI MS-7B84        | 1         | 0.65%   |
| MSI MS-7B17        | 1         | 0.65%   |
| MSI MS-7816        | 1         | 0.65%   |
| MSI GT72           | 1         | 0.65%   |
| MSI GE62VR         | 1         | 0.65%   |
| MSI CX61           | 1         | 0.65%   |
| Microsoft Surface  | 1         | 0.65%   |
| MACHINIST E5-MR9A  | 1         | 0.65%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 15        | 9.8%    |
| 2021 | 14        | 9.15%   |
| 2020 | 13        | 8.5%    |
| 2012 | 13        | 8.5%    |
| 2022 | 12        | 7.84%   |
| 2016 | 12        | 7.84%   |
| 2015 | 11        | 7.19%   |
| 2018 | 10        | 6.54%   |
| 2013 | 10        | 6.54%   |
| 2014 | 9         | 5.88%   |
| 2009 | 8         | 5.23%   |
| 2008 | 7         | 4.58%   |
| 2017 | 6         | 3.92%   |
| 2010 | 6         | 3.92%   |
| 2011 | 5         | 3.27%   |
| 2023 | 2         | 1.31%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 98        | 64.05%  |
| Desktop     | 41        | 26.8%   |
| All in one  | 6         | 3.92%   |
| Tablet      | 3         | 1.96%   |
| Convertible | 3         | 1.96%   |
| Mini pc     | 2         | 1.31%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 147       | 96.08%  |
| Enabled  | 6         | 3.92%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 152       | 99.35%  |
| Yes  | 1         | 0.65%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 48        | 31.37%  |
| 8.01-16.0   | 31        | 20.26%  |
| 16.01-24.0  | 30        | 19.61%  |
| 3.01-4.0    | 24        | 15.69%  |
| 32.01-64.0  | 13        | 8.5%    |
| 64.01-256.0 | 3         | 1.96%   |
| 1.01-2.0    | 2         | 1.31%   |
| 24.01-32.0  | 1         | 0.65%   |
| 2.01-3.0    | 1         | 0.65%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 74        | 45.68%  |
| 1.01-2.0  | 33        | 20.37%  |
| 3.01-4.0  | 29        | 17.9%   |
| 4.01-8.0  | 22        | 13.58%  |
| 8.01-16.0 | 3         | 1.85%   |
| 0.51-1.0  | 1         | 0.62%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 106       | 68.83%  |
| 2      | 37        | 24.03%  |
| 3      | 5         | 3.25%   |
| 5      | 3         | 1.95%   |
| 4      | 3         | 1.95%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 101       | 66.01%  |
| Yes       | 52        | 33.99%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 126       | 82.35%  |
| No        | 27        | 17.65%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 131       | 85.62%  |
| No        | 22        | 14.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 77.12%  |
| No        | 35        | 22.88%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 30        | 19.61%  |
| USA          | 27        | 17.65%  |
| Russia       | 12        | 7.84%   |
| France       | 6         | 3.92%   |
| UK           | 5         | 3.27%   |
| Spain        | 5         | 3.27%   |
| Poland       | 5         | 3.27%   |
| Netherlands  | 5         | 3.27%   |
| Italy        | 4         | 2.61%   |
| India        | 4         | 2.61%   |
| Brazil       | 4         | 2.61%   |
| Mexico       | 3         | 1.96%   |
| Australia    | 3         | 1.96%   |
| Thailand     | 2         | 1.31%   |
| Sweden       | 2         | 1.31%   |
| Portugal     | 2         | 1.31%   |
| Norway       | 2         | 1.31%   |
| Ireland      | 2         | 1.31%   |
| Greece       | 2         | 1.31%   |
| Czechia      | 2         | 1.31%   |
| China        | 2         | 1.31%   |
| Canada       | 2         | 1.31%   |
| Tunisia      | 1         | 0.65%   |
| South Africa | 1         | 0.65%   |
| Slovakia     | 1         | 0.65%   |
| Saudi Arabia | 1         | 0.65%   |
| Puerto Rico  | 1         | 0.65%   |
| Kazakhstan   | 1         | 0.65%   |
| Japan        | 1         | 0.65%   |
| Israel       | 1         | 0.65%   |
| Indonesia    | 1         | 0.65%   |
| Hungary      | 1         | 0.65%   |
| Hong Kong    | 1         | 0.65%   |
| Georgia      | 1         | 0.65%   |
| Finland      | 1         | 0.65%   |
| Ecuador      | 1         | 0.65%   |
| Denmark      | 1         | 0.65%   |
| Cyprus       | 1         | 0.65%   |
| Colombia     | 1         | 0.65%   |
| Chile        | 1         | 0.65%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Moscow                  | 5         | 3.18%   |
| Stuttgart               | 3         | 1.91%   |
| Warsaw                  | 2         | 1.27%   |
| Stockholm               | 2         | 1.27%   |
| St Petersburg           | 2         | 1.27%   |
| Munich                  | 2         | 1.27%   |
| Melbourne               | 2         | 1.27%   |
| Madrid                  | 2         | 1.27%   |
| Las Vegas               | 2         | 1.27%   |
| Hamm                    | 2         | 1.27%   |
| Brampton                | 2         | 1.27%   |
| Berlin                  | 2         | 1.27%   |
| Bangkok                 | 2         | 1.27%   |
| Aubagne                 | 2         | 1.27%   |
| Athens                  | 2         | 1.27%   |
| Znojmo                  | 1         | 0.64%   |
| Zhuantang               | 1         | 0.64%   |
| Worcestershire          | 1         | 0.64%   |
| Wilster                 | 1         | 0.64%   |
| Wiesbaden               | 1         | 0.64%   |
| West Jordan             | 1         | 0.64%   |
| Villingen-Schwenningen  | 1         | 0.64%   |
| Villefranche-sur-Saône | 1         | 0.64%   |
| Vigo                    | 1         | 0.64%   |
| Vienna                  | 1         | 0.64%   |
| Viareggio               | 1         | 0.64%   |
| Valencia                | 1         | 0.64%   |
| Twickenham              | 1         | 0.64%   |
| Tucson                  | 1         | 0.64%   |
| Tuam                    | 1         | 0.64%   |
| Tromsø                 | 1         | 0.64%   |
| Troisdorf               | 1         | 0.64%   |
| Tirana                  | 1         | 0.64%   |
| The Hague               | 1         | 0.64%   |
| Tel Aviv                | 1         | 0.64%   |
| Tbilisi                 | 1         | 0.64%   |
| Steti                   | 1         | 0.64%   |
| Spaichingen             | 1         | 0.64%   |
| Slavyansk-na-Kubani     | 1         | 0.64%   |
| Shanghai                | 1         | 0.64%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 26        | 27     | 12.38%  |
| Samsung Electronics         | 26        | 31     | 12.38%  |
| Seagate                     | 17        | 23     | 8.1%    |
| Sandisk                     | 14        | 16     | 6.67%   |
| Toshiba                     | 12        | 15     | 5.71%   |
| Crucial                     | 12        | 14     | 5.71%   |
| Kingston                    | 10        | 11     | 4.76%   |
| Apple                       | 9         | 9      | 4.29%   |
| Unknown                     | 5         | 6      | 2.38%   |
| China                       | 5         | 5      | 2.38%   |
| PNY                         | 4         | 4      | 1.9%    |
| KIOXIA                      | 4         | 6      | 1.9%    |
| Hitachi                     | 4         | 5      | 1.9%    |
| SK hynix                    | 3         | 4      | 1.43%   |
| Phison Electronics          | 3         | 3      | 1.43%   |
| Netac                       | 3         | 4      | 1.43%   |
| Micron Technology           | 3         | 3      | 1.43%   |
| Intenso                     | 3         | 5      | 1.43%   |
| Intel                       | 3         | 4      | 1.43%   |
| Team                        | 2         | 3      | 0.95%   |
| Silicon Motion              | 2         | 2      | 0.95%   |
| Micron/Crucial Technology   | 2         | 2      | 0.95%   |
| JMicron Technology          | 2         | 2      | 0.95%   |
| HGST                        | 2         | 3      | 0.95%   |
| Fujitsu                     | 2         | 2      | 0.95%   |
| Yeestor                     | 1         | 1      | 0.48%   |
| XrayDisk                    | 1         | 1      | 0.48%   |
| USB 3.0                     | 1         | 1      | 0.48%   |
| Union Memory                | 1         | 2      | 0.48%   |
| T-FORCE                     | 1         | 1      | 0.48%   |
| Star Drive                  | 1         | 1      | 0.48%   |
| SPCC                        | 1         | 1      | 0.48%   |
| Solid State Storage         | 1         | 1      | 0.48%   |
| SD                          | 1         | 1      | 0.48%   |
| Realtek Semiconductor       | 1         | 2      | 0.48%   |
| OWC                         | 1         | 1      | 0.48%   |
| NGFF                        | 1         | 1      | 0.48%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.48%   |
| MaiChai                     | 1         | 1      | 0.48%   |
| LuminouTek                  | 1         | 1      | 0.48%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 5         | 2.27%   |
| Kingston SA400S37240G 240GB SSD                     | 5         | 2.27%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 4         | 1.82%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 3         | 1.36%   |
| Phison E12 NVMe Controller 256GB                    | 3         | 1.36%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 2         | 0.91%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 2         | 0.91%   |
| Unknown MMC Card  7GB                               | 2         | 0.91%   |
| Unknown MMC Card  32GB                              | 2         | 0.91%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 0.91%   |
| Seagate ST9500325AS 500GB                           | 2         | 0.91%   |
| Seagate Expansion 1TB                               | 2         | 0.91%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 2         | 0.91%   |
| Samsung SSD 860 EVO 1TB                             | 2         | 0.91%   |
| Samsung SSD 850 EVO 250GB                           | 2         | 0.91%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 2         | 0.91%   |
| Intenso SSD SATAIII 120GB                           | 2         | 0.91%   |
| HGST HTS721010A9E630 1TB                            | 2         | 0.91%   |
| Crucial CT500MX500SSD1 500GB                        | 2         | 0.91%   |
| Crucial CT250MX500SSD1 250GB                        | 2         | 0.91%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 0.91%   |
| Yeestor 512GB                                       | 1         | 0.45%   |
| XrayDisk 512GB SSD                                  | 1         | 0.45%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.45%   |
| WDC WDS480G2G0C-00AJM0 480GB                        | 1         | 0.45%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 0.45%   |
| WDC WDS100T2B0B-00YS70 1TB SSD                      | 1         | 0.45%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1         | 0.45%   |
| WDC WD5000LPVX-22V0TT0 500GB                        | 1         | 0.45%   |
| WDC WD5000AAKX-08U6AA0 500GB                        | 1         | 0.45%   |
| WDC WD40EZRZ-00GXCB0 4TB                            | 1         | 0.45%   |
| WDC WD2500JB-55GVA0 250GB                           | 1         | 0.45%   |
| WDC WD10SPZX-24Z10T0 1TB                            | 1         | 0.45%   |
| WDC WD10SPCX-08S8TT0 1TB                            | 1         | 0.45%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 1         | 0.45%   |
| WDC WD10EZEX-60ZF5A0 1TB                            | 1         | 0.45%   |
| WDC WD10EZEX-00BN5A0 1TB                            | 1         | 0.45%   |
| WDC WD10EZEX-00BBHA0 1TB                            | 1         | 0.45%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                | 1         | 0.45%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB                | 1         | 0.45%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 16     | 32.65%  |
| Seagate             | 15        | 19     | 30.61%  |
| Toshiba             | 7         | 8      | 14.29%  |
| Hitachi             | 4         | 5      | 8.16%   |
| HGST                | 2         | 3      | 4.08%   |
| Fujitsu             | 2         | 2      | 4.08%   |
| Samsung Electronics | 1         | 1      | 2.04%   |
| ASMT                | 1         | 1      | 2.04%   |
| Apple               | 1         | 1      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 12        | 15     | 13.04%  |
| Crucial             | 12        | 14     | 13.04%  |
| Kingston            | 10        | 11     | 10.87%  |
| SanDisk             | 8         | 9      | 8.7%    |
| Apple               | 7         | 7      | 7.61%   |
| WDC                 | 6         | 7      | 6.52%   |
| China               | 5         | 5      | 5.43%   |
| Toshiba             | 4         | 6      | 4.35%   |
| PNY                 | 4         | 4      | 4.35%   |
| Team                | 2         | 3      | 2.17%   |
| Seagate             | 2         | 2      | 2.17%   |
| Netac               | 2         | 2      | 2.17%   |
| Intenso             | 2         | 4      | 2.17%   |
| XrayDisk            | 1         | 1      | 1.09%   |
| SPCC                | 1         | 1      | 1.09%   |
| OWC                 | 1         | 1      | 1.09%   |
| NGFF                | 1         | 1      | 1.09%   |
| Micron Technology   | 1         | 1      | 1.09%   |
| MaiChai             | 1         | 1      | 1.09%   |
| LITEONIT            | 1         | 1      | 1.09%   |
| LITEON              | 1         | 1      | 1.09%   |
| KingDian            | 1         | 2      | 1.09%   |
| JMicron Technology  | 1         | 1      | 1.09%   |
| Inland              | 1         | 1      | 1.09%   |
| HS-SSD-E100         | 1         | 1      | 1.09%   |
| Hewlett-Packard     | 1         | 1      | 1.09%   |
| Corsair             | 1         | 1      | 1.09%   |
| Apacer              | 1         | 1      | 1.09%   |
| A-DATA Technology   | 1         | 1      | 1.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 85        | 106    | 43.15%  |
| NVMe    | 51        | 61     | 25.89%  |
| HDD     | 41        | 56     | 20.81%  |
| Unknown | 15        | 16     | 7.61%   |
| MMC     | 5         | 6      | 2.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 112       | 166    | 62.57%  |
| NVMe | 51        | 61     | 28.49%  |
| SAS  | 11        | 12     | 6.15%   |
| MMC  | 5         | 6      | 2.79%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 81        | 104    | 63.28%  |
| 0.51-1.0   | 35        | 45     | 27.34%  |
| 1.01-2.0   | 10        | 11     | 7.81%   |
| 3.01-4.0   | 2         | 2      | 1.56%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 69        | 44.52%  |
| 251-500        | 40        | 25.81%  |
| 501-1000       | 29        | 18.71%  |
| 51-100         | 9         | 5.81%   |
| 1001-2000      | 3         | 1.94%   |
| 2001-3000      | 2         | 1.29%   |
| More than 3000 | 1         | 0.65%   |
| 21-50          | 1         | 0.65%   |
| 1-20           | 1         | 0.65%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 77        | 48.73%  |
| 21-50          | 35        | 22.15%  |
| 101-250        | 20        | 12.66%  |
| 51-100         | 19        | 12.03%  |
| 251-500        | 4         | 2.53%   |
| 1001-2000      | 2         | 1.27%   |
| More than 3000 | 1         | 0.63%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HTS725050A7E630 500GB | 1         | 1      | 100%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 100%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1         | 1      | 100%    |

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
| Detected | 133       | 218    | 84.71%  |
| Works    | 23        | 26     | 14.65%  |
| Malfunc  | 1         | 1      | 0.64%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 99        | 53.23%  |
| AMD                            | 24        | 12.9%   |
| Samsung Electronics            | 18        | 9.68%   |
| SanDisk                        | 10        | 5.38%   |
| Nvidia                         | 5         | 2.69%   |
| Phison Electronics             | 4         | 2.15%   |
| KIOXIA                         | 4         | 2.15%   |
| SK hynix                       | 3         | 1.61%   |
| Marvell Technology Group       | 3         | 1.61%   |
| Silicon Motion                 | 2         | 1.08%   |
| Micron/Crucial Technology      | 2         | 1.08%   |
| Micron Technology              | 2         | 1.08%   |
| ASMedia Technology             | 2         | 1.08%   |
| Union Memory (Shenzhen)        | 1         | 0.54%   |
| Toshiba America Info Systems   | 1         | 0.54%   |
| Solid State Storage Technology | 1         | 0.54%   |
| Realtek Semiconductor          | 1         | 0.54%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.54%   |
| Kingston Technology Company    | 1         | 0.54%   |
| INNOGRIT                       | 1         | 0.54%   |
| Biwin Storage Technology       | 1         | 0.54%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 19        | 9.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 9         | 4.37%   |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 3.88%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 3.4%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 6         | 2.91%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 6         | 2.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 5         | 2.43%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 5         | 2.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 2.43%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 4         | 1.94%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 4         | 1.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 4         | 1.94%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 4         | 1.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 4         | 1.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 1.94%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 1.94%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 3         | 1.46%   |
| SanDisk Non-Volatile memory controller                                         | 3         | 1.46%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.46%   |
| Phison E12 NVMe Controller                                                     | 3         | 1.46%   |
| Nvidia MCP79 AHCI Controller                                                   | 3         | 1.46%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 1.46%   |
| Intel Tiger Lake-LP SATA Controller                                            | 3         | 1.46%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.46%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 3         | 1.46%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 3         | 1.46%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 3         | 1.46%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 3         | 1.46%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 3         | 1.46%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 3         | 1.46%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 2         | 0.97%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 2         | 0.97%   |
| Samsung NVMe SSD Controller 980                                                | 2         | 0.97%   |
| Samsung Apple PCIe SSD                                                         | 2         | 0.97%   |
| Nvidia MCP89 SATA Controller (AHCI mode)                                       | 2         | 0.97%   |
| Micron NVMe Storage Controller                                                 | 2         | 0.97%   |
| Intel SSD 660P Series                                                          | 2         | 0.97%   |
| Intel Jasper Lake SATA AHCI Controller                                         | 2         | 0.97%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 2         | 0.97%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 2         | 0.97%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 119       | 61.98%  |
| NVMe | 51        | 26.56%  |
| RAID | 14        | 7.29%   |
| IDE  | 8         | 4.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 120       | 78.43%  |
| AMD    | 33        | 21.57%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i9-9900K CPU @ 3.60GHz               | 3         | 1.96%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 3         | 1.96%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz         | 3         | 1.96%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 2         | 1.31%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 2         | 1.31%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 1.31%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 2         | 1.31%   |
| Intel Core i3-3120M CPU @ 2.50GHz               | 2         | 1.31%   |
| Intel Celeron N5105 @ 2.00GHz                   | 2         | 1.31%   |
| Intel Celeron J4125 CPU @ 2.00GHz               | 2         | 1.31%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 1.31%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 2         | 1.31%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 2         | 1.31%   |
| Intel Xeon CPU E5-2670 v3 @ 2.30GHz             | 1         | 0.65%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz        | 1         | 0.65%   |
| Intel Pentium CPU P6200 @ 2.13GHz               | 1         | 0.65%   |
| Intel Pentium CPU N3540 @ 2.16GHz               | 1         | 0.65%   |
| Intel Pentium CPU J2900 @ 2.41GHz               | 1         | 0.65%   |
| Intel Pentium CPU G2020 @ 2.90GHz               | 1         | 0.65%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 0.65%   |
| Intel Core i7-8850H CPU @ 2.60GHz               | 1         | 0.65%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 0.65%   |
| Intel Core i7-7700 CPU @ 3.60GHz                | 1         | 0.65%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 0.65%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 0.65%   |
| Intel Core i7-6700T CPU @ 2.80GHz               | 1         | 0.65%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1         | 0.65%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 1         | 0.65%   |
| Intel Core i7-5600U CPU @ 2.60GHz               | 1         | 0.65%   |
| Intel Core i7-4870HQ CPU @ 2.50GHz              | 1         | 0.65%   |
| Intel Core i7-4750HQ CPU @ 2.00GHz              | 1         | 0.65%   |
| Intel Core i7-4712MQ CPU @ 2.30GHz              | 1         | 0.65%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz              | 1         | 0.65%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz              | 1         | 0.65%   |
| Intel Core i7-4600U CPU @ 2.10GHz               | 1         | 0.65%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 1         | 0.65%   |
| Intel Core i7-3770S CPU @ 3.10GHz               | 1         | 0.65%   |
| Intel Core i7-3770K CPU @ 3.50GHz               | 1         | 0.65%   |
| Intel Core i7-3770 CPU @ 3.40GHz                | 1         | 0.65%   |
| Intel Core i7-3720QM CPU @ 2.60GHz              | 1         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Intel Core i5        | 34        | 22.22%  |
| Intel Core i7        | 29        | 18.95%  |
| Other                | 18        | 11.76%  |
| Intel Core 2 Duo     | 13        | 8.5%    |
| Intel Core i3        | 9         | 5.88%   |
| Intel Celeron        | 9         | 5.88%   |
| AMD Ryzen 7          | 7         | 4.58%   |
| AMD Ryzen 5          | 7         | 4.58%   |
| Intel Pentium        | 4         | 2.61%   |
| Intel Core i9        | 3         | 1.96%   |
| AMD Ryzen 5 PRO      | 2         | 1.31%   |
| AMD Ryzen 3          | 2         | 1.31%   |
| AMD Athlon           | 2         | 1.31%   |
| AMD A8               | 2         | 1.31%   |
| AMD A4               | 2         | 1.31%   |
| AMD A12              | 2         | 1.31%   |
| Intel Xeon           | 1         | 0.65%   |
| Intel Pentium Silver | 1         | 0.65%   |
| AMD Sempron          | 1         | 0.65%   |
| AMD Ryzen 9          | 1         | 0.65%   |
| AMD Phenom II X6     | 1         | 0.65%   |
| AMD G                | 1         | 0.65%   |
| AMD E1               | 1         | 0.65%   |
| AMD A6               | 1         | 0.65%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 59        | 38.31%  |
| 4      | 57        | 37.01%  |
| 8      | 13        | 8.44%   |
| 6      | 11        | 7.14%   |
| 1      | 5         | 3.25%   |
| 12     | 4         | 2.6%    |
| 10     | 2         | 1.3%    |
| 5      | 2         | 1.3%    |
| 14     | 1         | 0.65%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 153       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 106       | 69.28%  |
| 1      | 47        | 30.72%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 153       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 122       | 79.22%  |
| 0x806ec    | 3         | 1.95%   |
| 0x806c1    | 3         | 1.95%   |
| 0x906a4    | 2         | 1.3%    |
| 0x806d1    | 2         | 1.3%    |
| 0x706e5    | 2         | 1.3%    |
| 0x306a9    | 2         | 1.3%    |
| 0x0a50000c | 2         | 1.3%    |
| 0x906ec    | 1         | 0.65%   |
| 0x906e9    | 1         | 0.65%   |
| 0x906c0    | 1         | 0.65%   |
| 0x906a3    | 1         | 0.65%   |
| 0x806eb    | 1         | 0.65%   |
| 0x806ea    | 1         | 0.65%   |
| 0x706a1    | 1         | 0.65%   |
| 0x40661    | 1         | 0.65%   |
| 0x40651    | 1         | 0.65%   |
| 0x1067a    | 1         | 0.65%   |
| 0x10676    | 1         | 0.65%   |
| 0x0a50000d | 1         | 0.65%   |
| 0x08108109 | 1         | 0.65%   |
| 0x07030106 | 1         | 0.65%   |
| 0x0600611a | 1         | 0.65%   |
| 0x010000c8 | 1         | 0.65%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 22        | 14.38%  |
| Haswell          | 15        | 9.8%    |
| IvyBridge        | 14        | 9.15%   |
| Penryn           | 12        | 7.84%   |
| Skylake          | 11        | 7.19%   |
| TigerLake        | 9         | 5.88%   |
| Unknown          | 8         | 5.23%   |
| Zen+             | 6         | 3.92%   |
| Zen 3            | 6         | 3.92%   |
| SandyBridge      | 6         | 3.92%   |
| Goldmont plus    | 5         | 3.27%   |
| Zen 2            | 4         | 2.61%   |
| Silvermont       | 4         | 2.61%   |
| IceLake          | 4         | 2.61%   |
| Westmere         | 3         | 1.96%   |
| Puma             | 3         | 1.96%   |
| Excavator        | 3         | 1.96%   |
| Alderlake Hybrid | 3         | 1.96%   |
| Zen              | 2         | 1.31%   |
| Steamroller      | 2         | 1.31%   |
| K10              | 2         | 1.31%   |
| Core             | 2         | 1.31%   |
| Broadwell        | 2         | 1.31%   |
| Tremont          | 1         | 0.65%   |
| Piledriver       | 1         | 0.65%   |
| Nehalem          | 1         | 0.65%   |
| CometLake        | 1         | 0.65%   |
| Bobcat           | 1         | 0.65%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 92        | 50.83%  |
| AMD    | 45        | 24.86%  |
| Nvidia | 44        | 24.31%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 9         | 4.84%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 6         | 3.23%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                          | 6         | 3.23%   |
| Intel HD Graphics 530                                                                 | 5         | 2.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 5         | 2.69%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 5         | 2.69%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 4         | 2.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 4         | 2.15%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 4         | 2.15%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 4         | 2.15%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 3         | 1.61%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                             | 3         | 1.61%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 3         | 1.61%   |
| Intel HD Graphics 630                                                                 | 3         | 1.61%   |
| Intel HD Graphics 620                                                                 | 3         | 1.61%   |
| Intel Core Processor Integrated Graphics Controller                                   | 3         | 1.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 3         | 1.61%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 3         | 1.61%   |
| AMD Lucienne                                                                          | 3         | 1.61%   |
| Nvidia MCP89 [GeForce 320M]                                                           | 2         | 1.08%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 2         | 1.08%   |
| Nvidia GK107 [GeForce GT 640]                                                         | 2         | 1.08%   |
| Nvidia C79 [GeForce 9400M]                                                            | 2         | 1.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 2         | 1.08%   |
| Intel UHD Graphics 620                                                                | 2         | 1.08%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 2         | 1.08%   |
| Intel JasperLake [UHD Graphics]                                                       | 2         | 1.08%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 2         | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                          | 2         | 1.08%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 2         | 1.08%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                | 2         | 1.08%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                   | 2         | 1.08%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 2         | 1.08%   |
| AMD Renoir                                                                            | 2         | 1.08%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                            | 2         | 1.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 2         | 1.08%   |
| Nvidia TU117 [GeForce GTX 1650]                                                       | 1         | 0.54%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 1         | 0.54%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                 | 1         | 0.54%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 1         | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 66        | 43.14%  |
| 1 x AMD        | 36        | 23.53%  |
| 1 x Nvidia     | 21        | 13.73%  |
| Intel + Nvidia | 20        | 13.07%  |
| Intel + AMD    | 4         | 2.61%   |
| 2 x AMD        | 3         | 1.96%   |
| AMD + Nvidia   | 2         | 1.31%   |
| 2 x Nvidia     | 1         | 0.65%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 142       | 92.81%  |
| Proprietary | 9         | 5.88%   |
| Unknown     | 2         | 1.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 140       | 91.5%   |
| 7.01-8.0   | 3         | 1.96%   |
| 1.01-2.0   | 3         | 1.96%   |
| 0.51-1.0   | 3         | 1.96%   |
| 0.01-0.5   | 3         | 1.96%   |
| 3.01-4.0   | 1         | 0.65%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 19        | 11.24%  |
| BOE                     | 18        | 10.65%  |
| Apple                   | 18        | 10.65%  |
| AU Optronics            | 16        | 9.47%   |
| Samsung Electronics     | 15        | 8.88%   |
| Chimei Innolux          | 13        | 7.69%   |
| Goldstar                | 8         | 4.73%   |
| Dell                    | 8         | 4.73%   |
| Sharp                   | 5         | 2.96%   |
| Hewlett-Packard         | 4         | 2.37%   |
| Philips                 | 3         | 1.78%   |
| PANDA                   | 3         | 1.78%   |
| Lenovo                  | 3         | 1.78%   |
| BenQ                    | 3         | 1.78%   |
| Acer                    | 3         | 1.78%   |
| Vizio                   | 2         | 1.18%   |
| Sceptre Tech            | 2         | 1.18%   |
| Chi Mei Optoelectronics | 2         | 1.18%   |
| ___                     | 1         | 0.59%   |
| Unknown                 | 1         | 0.59%   |
| Toshiba                 | 1         | 0.59%   |
| Sony                    | 1         | 0.59%   |
| Positivo                | 1         | 0.59%   |
| Panasonic               | 1         | 0.59%   |
| NSL                     | 1         | 0.59%   |
| MYS                     | 1         | 0.59%   |
| MSI                     | 1         | 0.59%   |
| Mi                      | 1         | 0.59%   |
| LG Philips              | 1         | 0.59%   |
| Kogan                   | 1         | 0.59%   |
| InfoVision              | 1         | 0.59%   |
| Idek Iiyama             | 1         | 0.59%   |
| Hitachi                 | 1         | 0.59%   |
| HannStar                | 1         | 0.59%   |
| Fujitsu Siemens         | 1         | 0.59%   |
| Eizo                    | 1         | 0.59%   |
| CVT                     | 1         | 0.59%   |
| CPT                     | 1         | 0.59%   |
| Cisco                   | 1         | 0.59%   |
| ASUSTek Computer        | 1         | 0.59%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 3         | 1.73%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 3         | 1.73%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 1.16%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 2         | 1.16%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 2         | 1.16%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                 | 2         | 1.16%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                  | 2         | 1.16%   |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                      | 2         | 1.16%   |
| Apple Color LCD APP9C6C 1920x1200 520x320mm 24.0-inch                 | 2         | 1.16%   |
| ___ LCDTV16 ___3393 1366x768                                          | 1         | 0.58%   |
| Vizio E420VL VIZ0057 1920x1080 930x520mm 41.9-inch                    | 1         | 0.58%   |
| Vizio E221VA VIZ0070 1920x1080 476x268mm 21.5-inch                    | 1         | 0.58%   |
| Unknown LCDTV16 3393 1920x1080 1600x900mm 72.3-inch                   | 1         | 0.58%   |
| Toshiba ScreenXpert TSB8888 1080x2160                                 | 1         | 0.58%   |
| Sony TV SNY7A02 1360x768 708x398mm 32.0-inch                          | 1         | 0.58%   |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.58%   |
| Sharp LCD Monitor SHP14AF 1920x1200 288x180mm 13.4-inch               | 1         | 0.58%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.58%   |
| Sharp LCD Monitor SHP1482 2880x1920 259x173mm 12.3-inch               | 1         | 0.58%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.58%   |
| Sceptre Tech Sceptre Q27 SPT0AD2 2560x1440 597x336mm 27.0-inch        | 1         | 0.58%   |
| Sceptre Tech E24 SPT099D 1920x1080 521x293mm 23.5-inch                | 1         | 0.58%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch     | 1         | 0.58%   |
| Samsung Electronics SyncMaster SAM05CC 1920x1080 530x300mm 24.0-inch  | 1         | 0.58%   |
| Samsung Electronics SMB2030HD SAM0709 1600x900 443x249mm 20.0-inch    | 1         | 0.58%   |
| Samsung Electronics S27A950D SAM079F 1920x1080 598x336mm 27.0-inch    | 1         | 0.58%   |
| Samsung Electronics S24E450 SAM0C7F 1920x1080 521x293mm 23.5-inch     | 1         | 0.58%   |
| Samsung Electronics LS27AG55x SAM71E0 2560x1440 597x336mm 27.0-inch   | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC5641 1366x768 344x193mm 15.5-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC4249 1366x768 309x174mm 14.0-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 1         | 0.58%   |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 700x390mm 31.5-inch | 1         | 0.58%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 1         | 0.58%   |
| Positivo MC35120QWQHD NON3503 3440x1440 819x346mm 35.0-inch           | 1         | 0.58%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 1         | 0.58%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 76        | 46.34%  |
| 1366x768 (WXGA)    | 30        | 18.29%  |
| 1920x1200 (WUXGA)  | 9         | 5.49%   |
| 2560x1440 (QHD)    | 7         | 4.27%   |
| 3840x2160 (4K)     | 6         | 3.66%   |
| 1600x900 (HD+)     | 5         | 3.05%   |
| 1280x800 (WXGA)    | 5         | 3.05%   |
| 2880x1800          | 4         | 2.44%   |
| 1280x1024 (SXGA)   | 4         | 2.44%   |
| 3440x1440          | 3         | 1.83%   |
| 1440x900 (WXGA+)   | 3         | 1.83%   |
| 2560x1600          | 2         | 1.22%   |
| 1680x1050 (WSXGA+) | 2         | 1.22%   |
| 3840x2400          | 1         | 0.61%   |
| 3360x1080          | 1         | 0.61%   |
| 2880x1920          | 1         | 0.61%   |
| 2736x1824          | 1         | 0.61%   |
| 2560x1080          | 1         | 0.61%   |
| 1920x1280          | 1         | 0.61%   |
| 1360x768           | 1         | 0.61%   |
| Unknown            | 1         | 0.61%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 45        | 26.32%  |
| 13      | 19        | 11.11%  |
| 14      | 17        | 9.94%   |
| 24      | 14        | 8.19%   |
| 17      | 12        | 7.02%   |
| 27      | 11        | 6.43%   |
| 21      | 11        | 6.43%   |
| 31      | 4         | 2.34%   |
| 23      | 4         | 2.34%   |
| 12      | 4         | 2.34%   |
| Unknown | 4         | 2.34%   |
| 34      | 3         | 1.75%   |
| 18      | 3         | 1.75%   |
| 84      | 2         | 1.17%   |
| 26      | 2         | 1.17%   |
| 20      | 2         | 1.17%   |
| 19      | 2         | 1.17%   |
| 11      | 2         | 1.17%   |
| 72      | 1         | 0.58%   |
| 65      | 1         | 0.58%   |
| 60      | 1         | 0.58%   |
| 54      | 1         | 0.58%   |
| 42      | 1         | 0.58%   |
| 35      | 1         | 0.58%   |
| 32      | 1         | 0.58%   |
| 29      | 1         | 0.58%   |
| 22      | 1         | 0.58%   |
| 16      | 1         | 0.58%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 65        | 38.46%  |
| 501-600     | 29        | 17.16%  |
| 201-300     | 21        | 12.43%  |
| 401-500     | 17        | 10.06%  |
| 351-400     | 16        | 9.47%   |
| 601-700     | 5         | 2.96%   |
| 701-800     | 4         | 2.37%   |
| Unknown     | 4         | 2.37%   |
| 1501-2000   | 3         | 1.78%   |
| 1001-1500   | 3         | 1.78%   |
| 801-900     | 1         | 0.59%   |
| 901-1000    | 1         | 0.59%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 117       | 74.05%  |
| 16/10   | 26        | 16.46%  |
| 3/2     | 4         | 2.53%   |
| 21/9    | 4         | 2.53%   |
| Unknown | 3         | 1.9%    |
| 4/3     | 2         | 1.27%   |
| 6/5     | 1         | 0.63%   |
| 5/4     | 1         | 0.63%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 47        | 27.81%  |
| 81-90          | 23        | 13.61%  |
| 201-250        | 21        | 12.43%  |
| 71-80          | 13        | 7.69%   |
| 301-350        | 12        | 7.1%    |
| 351-500        | 10        | 5.92%   |
| 121-130        | 8         | 4.73%   |
| More than 1000 | 6         | 3.55%   |
| 251-300        | 6         | 3.55%   |
| 151-200        | 6         | 3.55%   |
| 131-140        | 4         | 2.37%   |
| Unknown        | 4         | 2.37%   |
| 61-70          | 3         | 1.78%   |
| 141-150        | 3         | 1.78%   |
| 51-60          | 2         | 1.18%   |
| 501-1000       | 1         | 0.59%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 52        | 31.9%   |
| 101-120       | 46        | 28.22%  |
| 51-100        | 41        | 25.15%  |
| 161-240       | 12        | 7.36%   |
| 1-50          | 5         | 3.07%   |
| Unknown       | 4         | 2.45%   |
| More than 240 | 3         | 1.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 129       | 83.77%  |
| 2     | 22        | 14.29%  |
| 0     | 2         | 1.3%    |
| 3     | 1         | 0.65%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 68        | 28.81%  |
| Intel                             | 68        | 28.81%  |
| Broadcom                          | 28        | 11.86%  |
| Qualcomm Atheros                  | 27        | 11.44%  |
| Marvell Technology Group          | 5         | 2.12%   |
| Samsung Electronics               | 4         | 1.69%   |
| Broadcom Limited                  | 4         | 1.69%   |
| Ralink Technology                 | 3         | 1.27%   |
| Qualcomm                          | 3         | 1.27%   |
| Nvidia                            | 3         | 1.27%   |
| Huawei Technologies               | 3         | 1.27%   |
| Xiaomi                            | 2         | 0.85%   |
| TP-Link                           | 2         | 0.85%   |
| NetGear                           | 2         | 0.85%   |
| MediaTek                          | 2         | 0.85%   |
| Ericsson Business Mobile Networks | 2         | 0.85%   |
| Dell                              | 2         | 0.85%   |
| ASIX Electronics                  | 2         | 0.85%   |
| Sierra Wireless                   | 1         | 0.42%   |
| Ralink                            | 1         | 0.42%   |
| OPPO Electronics                  | 1         | 0.42%   |
| Motorola PCS                      | 1         | 0.42%   |
| Linksys                           | 1         | 0.42%   |
| ASUSTek Computer                  | 1         | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 47        | 16.61%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 3.18%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 2.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 2.47%   |
| Intel Wireless 8260                                               | 6         | 2.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 5         | 1.77%   |
| Intel Wi-Fi 6 AX200                                               | 5         | 1.77%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 4         | 1.41%   |
| Intel Wireless 7260                                               | 4         | 1.41%   |
| Intel Wireless 3165                                               | 4         | 1.41%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 1.41%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 1.41%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 4         | 1.41%   |
| Broadcom BCM43142 802.11b/g/n                                     | 4         | 1.41%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 1.06%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                  | 3         | 1.06%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 1.06%   |
| Nvidia MCP79 Ethernet                                             | 3         | 1.06%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 1.06%   |
| Intel Ethernet Controller I225-V                                  | 3         | 1.06%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 1.06%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 1.06%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.06%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 3         | 1.06%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 3         | 1.06%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 3         | 1.06%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.71%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 2         | 0.71%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 2         | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2         | 0.71%   |
| Ralink RT5370 Wireless Adapter                                    | 2         | 0.71%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 2         | 0.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 2         | 0.71%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 0.71%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.71%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.71%   |
| Intel Wireless-AC 9260                                            | 2         | 0.71%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.71%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 56        | 40.29%  |
| Realtek Semiconductor    | 23        | 16.55%  |
| Broadcom                 | 23        | 16.55%  |
| Qualcomm Atheros         | 19        | 13.67%  |
| Ralink Technology        | 3         | 2.16%   |
| Broadcom Limited         | 3         | 2.16%   |
| Qualcomm                 | 2         | 1.44%   |
| MediaTek                 | 2         | 1.44%   |
| TP-Link                  | 1         | 0.72%   |
| Sierra Wireless          | 1         | 0.72%   |
| Ralink                   | 1         | 0.72%   |
| NetGear                  | 1         | 0.72%   |
| Marvell Technology Group | 1         | 0.72%   |
| Linksys                  | 1         | 0.72%   |
| Dell                     | 1         | 0.72%   |
| ASUSTek Computer         | 1         | 0.72%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 6.47%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 5.76%   |
| Intel Wireless 8260                                            | 6         | 4.32%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 5         | 3.6%    |
| Intel Wi-Fi 6 AX200                                            | 5         | 3.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 4         | 2.88%   |
| Intel Wireless 7260                                            | 4         | 2.88%   |
| Intel Wireless 3165                                            | 4         | 2.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4         | 2.88%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 4         | 2.88%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 2.88%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 3         | 2.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 2.16%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 3         | 2.16%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 3         | 2.16%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 3         | 2.16%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 2         | 1.44%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 1.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 2         | 1.44%   |
| Ralink RT5370 Wireless Adapter                                 | 2         | 1.44%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 2         | 1.44%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 2         | 1.44%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.44%   |
| Intel Wireless-AC 9260                                         | 2         | 1.44%   |
| Intel Wireless 8265 / 8275                                     | 2         | 1.44%   |
| Intel Wireless 7265                                            | 2         | 1.44%   |
| Intel Ultimate N WiFi Link 5300                                | 2         | 1.44%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 2         | 1.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 2         | 1.44%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 2         | 1.44%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 2         | 1.44%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 2         | 1.44%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 2         | 1.44%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 1         | 0.72%   |
| Sierra Wireless EM7455                                         | 1         | 0.72%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.72%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.72%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.72%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 0.72%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 60        | 43.17%  |
| Intel                    | 35        | 25.18%  |
| Qualcomm Atheros         | 12        | 8.63%   |
| Broadcom                 | 10        | 7.19%   |
| Marvell Technology Group | 4         | 2.88%   |
| Samsung Electronics      | 3         | 2.16%   |
| Nvidia                   | 3         | 2.16%   |
| Huawei Technologies      | 3         | 2.16%   |
| Xiaomi                   | 2         | 1.44%   |
| ASIX Electronics         | 2         | 1.44%   |
| TP-Link                  | 1         | 0.72%   |
| Qualcomm                 | 1         | 0.72%   |
| OPPO Electronics         | 1         | 0.72%   |
| NetGear                  | 1         | 0.72%   |
| Broadcom Limited         | 1         | 0.72%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 47        | 33.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 7         | 5.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.88%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 4         | 2.88%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 3         | 2.16%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 3         | 2.16%   |
| Nvidia MCP79 Ethernet                                             | 3         | 2.16%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 2.16%   |
| Intel Ethernet Controller I225-V                                  | 3         | 2.16%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 2.16%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 2.16%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 1.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 1.44%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 2         | 1.44%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 1.44%   |
| Intel Ethernet Connection I219-V                                  | 2         | 1.44%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 1.44%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 1.44%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.44%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 1.44%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 1.44%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 1.44%   |
| Huawei ANE-LX1                                                    | 2         | 1.44%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 1.44%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.72%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.72%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.72%   |
| Qualcomm Fairphone 4 5G                                           | 1         | 0.72%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.72%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.72%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 1         | 0.72%   |
| OPPO SM8350-MTP _SN:1518BD09                                      | 1         | 0.72%   |
| NetGear LB1120-100NAS                                             | 1         | 0.72%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.72%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.72%   |
| Intel Ethernet Connection I217-V                                  | 1         | 0.72%   |
| Intel Ethernet Connection (4) I219-V                              | 1         | 0.72%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.72%   |
| Intel Ethernet Connection (17) I219-V                             | 1         | 0.72%   |
| Intel Ethernet Connection (14) I219-V                             | 1         | 0.72%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 131       | 50%     |
| Ethernet | 126       | 48.09%  |
| Modem    | 4         | 1.53%   |
| Unknown  | 1         | 0.38%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 95        | 61.69%  |
| Ethernet | 59        | 38.31%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 91        | 59.48%  |
| 1     | 56        | 36.6%   |
| 3     | 4         | 2.61%   |
| 0     | 2         | 1.31%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 103       | 67.32%  |
| Yes  | 50        | 32.68%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 42.37%  |
| Realtek Semiconductor           | 17        | 14.41%  |
| Apple                           | 17        | 14.41%  |
| Qualcomm Atheros Communications | 9         | 7.63%   |
| Lite-On Technology              | 4         | 3.39%   |
| Foxconn / Hon Hai               | 4         | 3.39%   |
| Cambridge Silicon Radio         | 4         | 3.39%   |
| Broadcom                        | 4         | 3.39%   |
| IMC Networks                    | 3         | 2.54%   |
| ASUSTek Computer                | 2         | 1.69%   |
| Toshiba                         | 1         | 0.85%   |
| MediaTek                        | 1         | 0.85%   |
| Hewlett-Packard                 | 1         | 0.85%   |
| Askey Computer                  | 1         | 0.85%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 17        | 14.41%  |
| Intel AX201 Bluetooth                               | 14        | 11.86%  |
| Realtek  Bluetooth 4.2 Adapter                      | 8         | 6.78%   |
| Realtek Bluetooth Radio                             | 8         | 6.78%   |
| Apple Bluetooth Host Controller                     | 6         | 5.08%   |
| Qualcomm Atheros  Bluetooth Device                  | 5         | 4.24%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 4.24%   |
| Intel AX200 Bluetooth                               | 5         | 4.24%   |
| Apple Bluetooth USB Host Controller                 | 5         | 4.24%   |
| Intel AX210 Bluetooth                               | 4         | 3.39%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 4         | 3.39%   |
| Intel Bluetooth Device                              | 3         | 2.54%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 2.54%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 3         | 2.54%   |
| Apple Bluetooth HCI                                 | 3         | 2.54%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 1.69%   |
| Lite-On Bluetooth Device                            | 2         | 1.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 1.69%   |
| Toshiba Bluetooth Device                            | 1         | 0.85%   |
| Realtek RTL8821A Bluetooth                          | 1         | 0.85%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.85%   |
| MediaTek Wireless_Device                            | 1         | 0.85%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.85%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.85%   |
| IMC Networks Bluetooth Radio                        | 1         | 0.85%   |
| IMC Networks Bluetooth                              | 1         | 0.85%   |
| IMC Networks BCM20702A0                             | 1         | 0.85%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.85%   |
| Foxconn / Hon Hai BCM43142A0                        | 1         | 0.85%   |
| Broadcom Bluetooth 3.0 Dongle                       | 1         | 0.85%   |
| Broadcom BCM43142A0 Bluetooth Device                | 1         | 0.85%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 1         | 0.85%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 1         | 0.85%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 1         | 0.85%   |
| ASUS ASUS USB-BT500                                 | 1         | 0.85%   |
| Askey Bluetooth Device                              | 1         | 0.85%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 115       | 54.76%  |
| AMD                      | 44        | 20.95%  |
| Nvidia                   | 30        | 14.29%  |
| C-Media Electronics      | 7         | 3.33%   |
| Logitech                 | 4         | 1.9%    |
| Realtek Semiconductor    | 1         | 0.48%   |
| Razer USA                | 1         | 0.48%   |
| Nordic Semiconductor ASA | 1         | 0.48%   |
| KTMicro                  | 1         | 0.48%   |
| Hewlett-Packard          | 1         | 0.48%   |
| Goldvish                 | 1         | 0.48%   |
| GN Netcom                | 1         | 0.48%   |
| Generalplus Technology   | 1         | 0.48%   |
| Creative Labs            | 1         | 0.48%   |
| ASUSTek Computer         | 1         | 0.48%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 17        | 6.77%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 4.38%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 11        | 4.38%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 3.98%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 9         | 3.59%   |
| Intel Sunrise Point-LP HD Audio                                            | 9         | 3.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 9         | 3.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 3.19%   |
| Intel Cannon Lake PCH cAVS                                                 | 7         | 2.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 6         | 2.39%   |
| AMD FCH Azalia Controller                                                  | 6         | 2.39%   |
| Nvidia GK107 HDMI Audio Controller                                         | 5         | 1.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 1.99%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 1.99%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 5         | 1.99%   |
| Intel 8 Series HD Audio Controller                                         | 5         | 1.99%   |
| AMD Kabini HDMI/DP Audio                                                   | 5         | 1.99%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 1.59%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.59%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 4         | 1.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.59%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 4         | 1.59%   |
| Nvidia MCP79 High Definition Audio                                         | 3         | 1.2%    |
| Nvidia GA104 High Definition Audio Controller                              | 3         | 1.2%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.2%    |
| Intel Comet Lake PCH-LP cAVS                                               | 3         | 1.2%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 3         | 1.2%    |
| Intel 200 Series PCH HD Audio                                              | 3         | 1.2%    |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 1.2%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 1.2%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 3         | 1.2%    |
| Nvidia TU116 High Definition Audio Controller                              | 2         | 0.8%    |
| Nvidia MCP89 High Definition Audio                                         | 2         | 0.8%    |
| Nvidia GP107GL High Definition Audio Controller                            | 2         | 0.8%    |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 0.8%    |
| Nvidia Audio device                                                        | 2         | 0.8%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 0.8%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.8%    |
| Intel Jasper Lake HD Audio                                                 | 2         | 0.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 11        | 28.95%  |
| Micron Technology   | 8         | 21.05%  |
| SK hynix            | 6         | 15.79%  |
| Kingston            | 3         | 7.89%   |
| Unknown (ABCD)      | 1         | 2.63%   |
| Unknown (0x5846)    | 1         | 2.63%   |
| Ramaxel Technology  | 1         | 2.63%   |
| pqi                 | 1         | 2.63%   |
| GSkill              | 1         | 2.63%   |
| CSX                 | 1         | 2.63%   |
| Corsair             | 1         | 2.63%   |
| Apacer              | 1         | 2.63%   |
| A-DATA Technology   | 1         | 2.63%   |
| Unknown             | 1         | 2.63%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM U6E3S4AA-MGCR 1GB Row Of Chips LPDDR4 4267MT/s       | 2         | 5.26%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 2.63%   |
| Unknown (0x5846) RAM DDR4 NB 8G 2666 8GB SODIMM DDR4 2667MT/s    | 1         | 2.63%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2667MT/s                     | 1         | 2.63%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 2.63%   |
| SK hynix RAM HMT125S6BFR8C-H9 2GB SODIMM DDR3 1333MT/s           | 1         | 2.63%   |
| SK hynix RAM HMAA4GS6CJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 2.63%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 2.63%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 2.63%   |
| Samsung RAM UBE3D4AA-MGCR 2GB Row Of Chips LPDDR4 4267MT/s       | 1         | 2.63%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                     | 1         | 2.63%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 2.63%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 2.63%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 2.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 2.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 1         | 2.63%   |
| Samsung RAM M378B5273CH0-CK0 4GB DIMM DDR3 2000MT/s              | 1         | 2.63%   |
| Samsung RAM K4E6E304EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 2.63%   |
| Ramaxel RAM Module 16GB SODIMM DDR4 3200MT/s                     | 1         | 2.63%   |
| pqi RAM Module 2GB SODIMM DDR2 667MT/s                           | 1         | 2.63%   |
| Micron RAM MT53E1G32D4NQ-046 8GB Row Of Chips LPDDR4 4267MT/s    | 1         | 2.63%   |
| Micron RAM MT53E1G32D2NP-046 8GB Row Of Chips LPDDR4 4267MT/s    | 1         | 2.63%   |
| Micron RAM Module 8GB SODIMM DDR4 2667MT/s                       | 1         | 2.63%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 2.63%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 2.63%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 1         | 2.63%   |
| Micron RAM 16ATF4G64HZ-3G2E2 32GB SODIMM DDR4 3200MT/s           | 1         | 2.63%   |
| Micron RAM 16ATF2G64HZ-2G6E3 16GB SODIMM DDR4 2667MT/s           | 1         | 2.63%   |
| Kingston RAM HX426C16FB/4 4GB DIMM DDR4 2800MT/s                 | 1         | 2.63%   |
| Kingston RAM HX318C10F/8 8GB DIMM DDR3 1600MT/s                  | 1         | 2.63%   |
| Kingston RAM ASU16D3LU1KBG/4G 4GB DIMM DDR3 3200MT/s             | 1         | 2.63%   |
| GSkill RAM F4-3200C22-16GRS 16GB SODIMM DDR4 3200MT/s            | 1         | 2.63%   |
| CSX RAM V01D3L82GB26826813 2GB DIMM 1066MT/s                     | 1         | 2.63%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s             | 1         | 2.63%   |
| Apacer RAM 78.CAGP7.C7Z0B 8GB DIMM DDR4 2400MT/s                 | 1         | 2.63%   |
| A-DATA RAM Module 4GB DIMM DDR3 1600MT/s                         | 1         | 2.63%   |
| Unknown                                                          | 1         | 2.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 17        | 50%     |
| LPDDR4  | 6         | 17.65%  |
| DDR3    | 6         | 17.65%  |
| SDRAM   | 1         | 2.94%   |
| LPDDR3  | 1         | 2.94%   |
| DDR5    | 1         | 2.94%   |
| DDR2    | 1         | 2.94%   |
| Unknown | 1         | 2.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 20        | 58.82%  |
| Row Of Chips | 8         | 23.53%  |
| DIMM         | 6         | 17.65%  |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 20        | 57.14%  |
| 4096  | 7         | 20%     |
| 16384 | 4         | 11.43%  |
| 2048  | 3         | 8.57%   |
| 32768 | 1         | 2.86%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 9         | 25%     |
| 2667  | 8         | 22.22%  |
| 4267  | 5         | 13.89%  |
| 1600  | 3         | 8.33%   |
| 2800  | 2         | 5.56%   |
| 2400  | 2         | 5.56%   |
| 4800  | 1         | 2.78%   |
| 2133  | 1         | 2.78%   |
| 2000  | 1         | 2.78%   |
| 1333  | 1         | 2.78%   |
| 1066  | 1         | 2.78%   |
| 667   | 1         | 2.78%   |
| 533   | 1         | 2.78%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |
| Canon               | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Samsung M2020 Series   | 1         | 33.33%  |
| HP DeskJet 2600 series | 1         | 33.33%  |
| Canon MF4320-4350      | 1         | 33.33%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Seiko Epson ES-H300 [GT-2500] | 1         | 50%     |
| Canon CanoScan LiDE 100       | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 20        | 19.23%  |
| Apple                                  | 15        | 14.42%  |
| Quanta                                 | 11        | 10.58%  |
| IMC Networks                           | 10        | 9.62%   |
| Microdia                               | 9         | 8.65%   |
| Realtek Semiconductor                  | 8         | 7.69%   |
| Bison Electronics                      | 6         | 5.77%   |
| Sunplus Innovation Technology          | 4         | 3.85%   |
| Syntek                                 | 2         | 1.92%   |
| Samsung Electronics                    | 2         | 1.92%   |
| Generalplus Technology                 | 2         | 1.92%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 1.92%   |
| Suyin                                  | 1         | 0.96%   |
| SunplusIT                              | 1         | 0.96%   |
| Sunplus Technology                     | 1         | 0.96%   |
| Silicon Motion                         | 1         | 0.96%   |
| Luxvisions Innotech Limited            | 1         | 0.96%   |
| Logitech                               | 1         | 0.96%   |
| Lite-On Technology                     | 1         | 0.96%   |
| Lenovo                                 | 1         | 0.96%   |
| Intel                                  | 1         | 0.96%   |
| Cubeternet                             | 1         | 0.96%   |
| Cisco Systems                          | 1         | 0.96%   |
| Alcor Micro                            | 1         | 0.96%   |
| Acer                                   | 1         | 0.96%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 6         | 5.66%   |
| Apple Built-in iSight                   | 5         | 4.72%   |
| IMC Networks USB2.0 HD UVC WebCam       | 4         | 3.77%   |
| Apple FaceTime HD Camera (Built-in)     | 4         | 3.77%   |
| Realtek Integrated_Webcam_HD            | 3         | 2.83%   |
| Microdia Integrated_Webcam_HD           | 3         | 2.83%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 3         | 2.83%   |
| Samsung Galaxy series, misc. (MTP mode) | 2         | 1.89%   |
| Quanta USB2.0 HD UVC WebCam             | 2         | 1.89%   |
| Quanta HP HD Camera                     | 2         | 1.89%   |
| Microdia Webcam Vitade AF               | 2         | 1.89%   |
| Microdia Integrated Webcam              | 2         | 1.89%   |
| IMC Networks HD Camera                  | 2         | 1.89%   |
| Chicony HP TrueVision HD Camera         | 2         | 1.89%   |
| Chicony HP Truevision HD                | 2         | 1.89%   |
| Bison Integrated Camera                 | 2         | 1.89%   |
| Apple FaceTime HD Camera                | 2         | 1.89%   |
| Apple FaceTime Camera                   | 2         | 1.89%   |
| Syntek Lenovo EasyCamera                | 1         | 0.94%   |
| Syntek EasyCamera                       | 1         | 0.94%   |
| Suyin Acer HD Crystal Eye webcam        | 1         | 0.94%   |
| SunplusIT HD Camera                     | 1         | 0.94%   |
| Sunplus 1.3M HD WebCam                  | 1         | 0.94%   |
| Sunplus MTD Camera                      | 1         | 0.94%   |
| Sunplus HD WebCam                       | 1         | 0.94%   |
| Sunplus FHD Camera Microphone           | 1         | 0.94%   |
| Sunplus Dell E5570 integrated webcam    | 1         | 0.94%   |
| Silicon Motion WebCam SC-03FFL11939N    | 1         | 0.94%   |
| Realtek HP Webcam                       | 1         | 0.94%   |
| Realtek Front Camera                    | 1         | 0.94%   |
| Realtek EasyCamera                      | 1         | 0.94%   |
| Realtek Back Camera                     | 1         | 0.94%   |
| Realtek Acer 640 x 480 laptop camera    | 1         | 0.94%   |
| Realtek 2SF022                          | 1         | 0.94%   |
| Quanta VGA WebCam                       | 1         | 0.94%   |
| Quanta ov9734_techfront_camera          | 1         | 0.94%   |
| Quanta HP Wide Vision HD Camera         | 1         | 0.94%   |
| Quanta HP Webcam                        | 1         | 0.94%   |
| Quanta HP TrueVision HD Camera          | 1         | 0.94%   |
| Quanta HD Webcam                        | 1         | 0.94%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 8         | 32%     |
| Shenzhen Goodix Technology | 8         | 32%     |
| Synaptics                  | 4         | 16%     |
| Elan Microelectronics      | 3         | 12%     |
| Upek                       | 1         | 4%      |
| LighTuning Technology      | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 6         | 24%     |
| Validity Sensors VFS 5011 fingerprint sensor                               | 3         | 12%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 2         | 8%      |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 8%      |
| Elan ELAN:Fingerprint                                                      | 2         | 8%      |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 4%      |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 4%      |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 4%      |
| Validity Sensors Synaptics WBDI                                            | 1         | 4%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 4%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1         | 4%      |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 4%      |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 4%      |
| LighTuning Fingerprint Reader                                              | 1         | 4%      |
| Elan ELAN:ARM-M4                                                           | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 3         | 50%     |
| Upek        | 1         | 16.67%  |
| O2 Micro    | 1         | 16.67%  |
| Alcor Micro | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 16.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 16.67%  |
| Broadcom 5880                                                                | 1         | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 96        | 62.75%  |
| 1     | 48        | 31.37%  |
| 2     | 9         | 5.88%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 24        | 36.36%  |
| Net/wireless             | 13        | 19.7%   |
| Multimedia controller    | 13        | 19.7%   |
| Graphics card            | 6         | 9.09%   |
| Chipcard                 | 6         | 9.09%   |
| Net/ethernet             | 2         | 3.03%   |
| Storage                  | 1         | 1.52%   |
| Communication controller | 1         | 1.52%   |

