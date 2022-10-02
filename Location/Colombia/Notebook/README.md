Linux in Colombia - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Colombia.

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

Total: 775

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | EliteBook 840 G3            | [ddf1904011](https://linux-hardware.org/?probe=ddf1904011) | Oct 01, 2022 |
| HP            | Pavilion 10 TS              | [28003748e6](https://linux-hardware.org/?probe=28003748e6) | Sep 27, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [56e06deea2](https://linux-hardware.org/?probe=56e06deea2) | Sep 26, 2022 |
| HP            | Pavilion 10 TS              | [1186e5b5d8](https://linux-hardware.org/?probe=1186e5b5d8) | Sep 23, 2022 |
| Dell          | XPS 15 9550                 | [acf36b1555](https://linux-hardware.org/?probe=acf36b1555) | Sep 20, 2022 |
| Acer          | Aspire V3-471               | [b04cc2ea05](https://linux-hardware.org/?probe=b04cc2ea05) | Sep 20, 2022 |
| ASUSTek       | X455LAB                     | [4a71131e80](https://linux-hardware.org/?probe=4a71131e80) | Sep 19, 2022 |
| ASUSTek       | X455LAB                     | [f7c5412964](https://linux-hardware.org/?probe=f7c5412964) | Sep 19, 2022 |
| ASUSTek       | X441NA                      | [282f984233](https://linux-hardware.org/?probe=282f984233) | Sep 19, 2022 |
| Dell          | Latitude E5420              | [7416dc3fb1](https://linux-hardware.org/?probe=7416dc3fb1) | Sep 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [a26e1ad502](https://linux-hardware.org/?probe=a26e1ad502) | Sep 15, 2022 |
| HP            | 240 G7 Notebook PC          | [09f7be676c](https://linux-hardware.org/?probe=09f7be676c) | Sep 15, 2022 |
| HP            | 240 G7 Notebook PC          | [2225605b31](https://linux-hardware.org/?probe=2225605b31) | Sep 15, 2022 |
| ASUSTek       | X405UA                      | [3b098addea](https://linux-hardware.org/?probe=3b098addea) | Sep 14, 2022 |
| MSI           | PS63 Modern 8RD             | [8fa2ea42ed](https://linux-hardware.org/?probe=8fa2ea42ed) | Sep 14, 2022 |
| HP            | Notebook                    | [2984aef090](https://linux-hardware.org/?probe=2984aef090) | Sep 11, 2022 |
| Dell          | Precision 3510              | [4337a8e018](https://linux-hardware.org/?probe=4337a8e018) | Sep 11, 2022 |
| Acer          | Aspire V3-472P              | [632117c524](https://linux-hardware.org/?probe=632117c524) | Sep 10, 2022 |
| Toshiba       | Satellite L635              | [6d0bbfb576](https://linux-hardware.org/?probe=6d0bbfb576) | Sep 07, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [cc43cdda9a](https://linux-hardware.org/?probe=cc43cdda9a) | Sep 04, 2022 |
| ASUSTek       | X455LJ                      | [b635e1c2ba](https://linux-hardware.org/?probe=b635e1c2ba) | Sep 01, 2022 |
| HP            | Laptop 14-fq1xxx            | [8ea91d6b4b](https://linux-hardware.org/?probe=8ea91d6b4b) | Aug 30, 2022 |
| Compumax C... | ONIX-CEL-0001               | [272ca2c7b7](https://linux-hardware.org/?probe=272ca2c7b7) | Aug 27, 2022 |
| ASUSTek       | X455LD                      | [5351e31366](https://linux-hardware.org/?probe=5351e31366) | Aug 26, 2022 |
| HP            | ENVY 15                     | [db06c354d4](https://linux-hardware.org/?probe=db06c354d4) | Aug 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [5028378988](https://linux-hardware.org/?probe=5028378988) | Aug 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d64f8a64fa](https://linux-hardware.org/?probe=d64f8a64fa) | Aug 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [bb928725a6](https://linux-hardware.org/?probe=bb928725a6) | Aug 23, 2022 |
| Dell          | XPS 15 9550                 | [8ab7fcb6ff](https://linux-hardware.org/?probe=8ab7fcb6ff) | Aug 21, 2022 |
| HP            | 240 G7 Notebook PC          | [24849a5c23](https://linux-hardware.org/?probe=24849a5c23) | Aug 15, 2022 |
| ASUSTek       | X550DP                      | [ce42b65252](https://linux-hardware.org/?probe=ce42b65252) | Aug 13, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [298cf4b527](https://linux-hardware.org/?probe=298cf4b527) | Aug 13, 2022 |
| HP            | 240 G7 Notebook PC          | [9321e2df1a](https://linux-hardware.org/?probe=9321e2df1a) | Aug 13, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [e71b330285](https://linux-hardware.org/?probe=e71b330285) | Aug 13, 2022 |
| ASUSTek       | X455LJ                      | [f90572b8e2](https://linux-hardware.org/?probe=f90572b8e2) | Aug 11, 2022 |
| HUAWEI        | BOHB-WAX9                   | [fcc8ebfb00](https://linux-hardware.org/?probe=fcc8ebfb00) | Aug 04, 2022 |
| HUAWEI        | BOHB-WAX9                   | [76087f7441](https://linux-hardware.org/?probe=76087f7441) | Aug 03, 2022 |
| HUAWEI        | BOHB-WAX9                   | [6d65ac3351](https://linux-hardware.org/?probe=6d65ac3351) | Aug 02, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [bdc243bf9f](https://linux-hardware.org/?probe=bdc243bf9f) | Jul 31, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | [41a0eba80f](https://linux-hardware.org/?probe=41a0eba80f) | Jul 31, 2022 |
| Sony          | VPCEG33FL                   | [6d371d6c32](https://linux-hardware.org/?probe=6d371d6c32) | Jul 31, 2022 |
| HP            | 245 G6                      | [ae4b0ce17e](https://linux-hardware.org/?probe=ae4b0ce17e) | Jul 28, 2022 |
| Sony          | VPCEG33FL                   | [886dfc7777](https://linux-hardware.org/?probe=886dfc7777) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | [c2fc2235eb](https://linux-hardware.org/?probe=c2fc2235eb) | Jul 27, 2022 |
| HUAWEI        | HVY-WXX9                    | [f18835e5a1](https://linux-hardware.org/?probe=f18835e5a1) | Jul 27, 2022 |
| Lenovo        | G410 20237                  | [c23a040e55](https://linux-hardware.org/?probe=c23a040e55) | Jul 25, 2022 |
| Sony          | VPCEG33FL                   | [8767e87e9e](https://linux-hardware.org/?probe=8767e87e9e) | Jul 24, 2022 |
| ASUSTek       | X455LJ                      | [49af56cbe0](https://linux-hardware.org/?probe=49af56cbe0) | Jul 24, 2022 |
| HP            | Victus by Laptop 16-d0xx... | [acdc35979c](https://linux-hardware.org/?probe=acdc35979c) | Jul 23, 2022 |
| ASUSTek       | N53SV                       | [635f096b70](https://linux-hardware.org/?probe=635f096b70) | Jul 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [9863a7ed67](https://linux-hardware.org/?probe=9863a7ed67) | Jul 20, 2022 |
| Unknown       | Unknown                     | [12ef7e83a2](https://linux-hardware.org/?probe=12ef7e83a2) | Jul 20, 2022 |
| Unknown       | Unknown                     | [ff3afb51a1](https://linux-hardware.org/?probe=ff3afb51a1) | Jul 20, 2022 |
| Sony          | VPCEH37FJ                   | [1cc39f5c15](https://linux-hardware.org/?probe=1cc39f5c15) | Jul 19, 2022 |
| Toshiba       | Satellite M645              | [0149367a4e](https://linux-hardware.org/?probe=0149367a4e) | Jul 12, 2022 |
| ASUSTek       | N53SV                       | [2af75f4744](https://linux-hardware.org/?probe=2af75f4744) | Jul 12, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [ebbc4ebc1d](https://linux-hardware.org/?probe=ebbc4ebc1d) | Jul 11, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | [d200cc6f06](https://linux-hardware.org/?probe=d200cc6f06) | Jul 11, 2022 |
| HP            | Laptop 15-dy1xxx            | [36b1a0480d](https://linux-hardware.org/?probe=36b1a0480d) | Jul 10, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [c7c8a9031c](https://linux-hardware.org/?probe=c7c8a9031c) | Jul 05, 2022 |
| Dell          | Latitude E7450              | [34913911ca](https://linux-hardware.org/?probe=34913911ca) | Jul 05, 2022 |
| Dell          | Latitude E7450              | [60e633e563](https://linux-hardware.org/?probe=60e633e563) | Jul 04, 2022 |
| Sony          | VPCEH37FJ                   | [509fe56362](https://linux-hardware.org/?probe=509fe56362) | Jul 01, 2022 |
| HP            | Pavilion g4                 | [3626d9afe4](https://linux-hardware.org/?probe=3626d9afe4) | Jul 01, 2022 |
| HP            | ProBook 445 G8 Notebook ... | [35ca7c4868](https://linux-hardware.org/?probe=35ca7c4868) | Jun 30, 2022 |
| Lenovo        | Z40-75 80DW                 | [1fc3b34132](https://linux-hardware.org/?probe=1fc3b34132) | Jun 27, 2022 |
| HP            | ProBook 440 G7              | [3bbbcaea72](https://linux-hardware.org/?probe=3bbbcaea72) | Jun 20, 2022 |
| HUAWEI        | WRTD-WXX9                   | [15d402e40c](https://linux-hardware.org/?probe=15d402e40c) | Jun 18, 2022 |
| HUAWEI        | KLVL-WXX9                   | [a71adbf68f](https://linux-hardware.org/?probe=a71adbf68f) | Jun 18, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [27d9d9e55e](https://linux-hardware.org/?probe=27d9d9e55e) | Jun 16, 2022 |
| Acer          | AO722                       | [29c2adc56d](https://linux-hardware.org/?probe=29c2adc56d) | Jun 13, 2022 |
| HP            | Laptop 14-cm1xxx            | [269af04437](https://linux-hardware.org/?probe=269af04437) | Jun 13, 2022 |
| Dell          | Vostro 3560                 | [170031499c](https://linux-hardware.org/?probe=170031499c) | Jun 12, 2022 |
| Lenovo        | IdeaPad S340-14IIL 81VV     | [5e7659e141](https://linux-hardware.org/?probe=5e7659e141) | Jun 11, 2022 |
| HP            | Laptop 14-cm1xxx            | [77e3d238c1](https://linux-hardware.org/?probe=77e3d238c1) | Jun 10, 2022 |
| Dell          | Vostro 3560                 | [0664b57ae1](https://linux-hardware.org/?probe=0664b57ae1) | Jun 09, 2022 |
| HP            | ProBook 440 G2              | [47ef7a04b9](https://linux-hardware.org/?probe=47ef7a04b9) | Jun 06, 2022 |
| HP            | Laptop 15-db0xxx            | [e5998cb70e](https://linux-hardware.org/?probe=e5998cb70e) | Jun 05, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [1368d41e8e](https://linux-hardware.org/?probe=1368d41e8e) | Jun 04, 2022 |
| Sony          | VGN-CS240T                  | [b25cbd1a6b](https://linux-hardware.org/?probe=b25cbd1a6b) | Jun 03, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | [b7e4b7a2ec](https://linux-hardware.org/?probe=b7e4b7a2ec) | Jun 03, 2022 |
| Acer          | AOD260                      | [f5c031faa5](https://linux-hardware.org/?probe=f5c031faa5) | Jun 02, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [883f055fb1](https://linux-hardware.org/?probe=883f055fb1) | May 30, 2022 |
| ASUSTek       | ROG Strix G713IH_G713IH     | [e475b560cf](https://linux-hardware.org/?probe=e475b560cf) | May 30, 2022 |
| MSI           | GE60 2PE                    | [1e15d749ee](https://linux-hardware.org/?probe=1e15d749ee) | May 30, 2022 |
| MSI           | GE60 2PE                    | [b52762040d](https://linux-hardware.org/?probe=b52762040d) | May 30, 2022 |
| Lenovo        | ThinkPad Edge E430 32543... | [dc9d61a80b](https://linux-hardware.org/?probe=dc9d61a80b) | May 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [33de40a2e1](https://linux-hardware.org/?probe=33de40a2e1) | May 29, 2022 |
| MSI           | GE60 2PE                    | [84d5af4ebe](https://linux-hardware.org/?probe=84d5af4ebe) | May 29, 2022 |
| MSI           | GE60 2PE                    | [c8d325a744](https://linux-hardware.org/?probe=c8d325a744) | May 29, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [159819d677](https://linux-hardware.org/?probe=159819d677) | May 26, 2022 |
| Dell          | Latitude E5410              | [fcb77d9c00](https://linux-hardware.org/?probe=fcb77d9c00) | May 26, 2022 |
| Acer          | Aspire E5-411               | [7c3a3077ff](https://linux-hardware.org/?probe=7c3a3077ff) | May 24, 2022 |
| HP            | Laptop 15-da2xxx            | [7dd1f5b528](https://linux-hardware.org/?probe=7dd1f5b528) | May 23, 2022 |
| HP            | ProBook 450 G1              | [0097404cab](https://linux-hardware.org/?probe=0097404cab) | May 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV    | [50a0ed5e81](https://linux-hardware.org/?probe=50a0ed5e81) | May 22, 2022 |
| HP            | Laptop 14-dk1xxx            | [f05080d3fd](https://linux-hardware.org/?probe=f05080d3fd) | May 22, 2022 |
| Toshiba       | Satellite C55-C             | [46f7672c43](https://linux-hardware.org/?probe=46f7672c43) | May 22, 2022 |
| Toshiba       | Satellite C55-C             | [6f6a96c1cb](https://linux-hardware.org/?probe=6f6a96c1cb) | May 22, 2022 |
| Timi          | A35S                        | [8278281113](https://linux-hardware.org/?probe=8278281113) | May 20, 2022 |
| Acer          | Aspire A314-22              | [b476e4fd95](https://linux-hardware.org/?probe=b476e4fd95) | May 20, 2022 |
| Dell          | Inspiron 3459               | [b36df0b4df](https://linux-hardware.org/?probe=b36df0b4df) | May 17, 2022 |
| MSI           | Katana GF76 12UE            | [460e78b93a](https://linux-hardware.org/?probe=460e78b93a) | May 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [f7d3a9220c](https://linux-hardware.org/?probe=f7d3a9220c) | May 13, 2022 |
| Lenovo        | V14-IGL 82C2                | [0d1e1d71ee](https://linux-hardware.org/?probe=0d1e1d71ee) | May 08, 2022 |
| Lenovo        | V14-IGL 82C2                | [3ad9fd00c2](https://linux-hardware.org/?probe=3ad9fd00c2) | May 08, 2022 |
| HP            | Compaq 6530b (WA484LA#AB... | [13cda8fea2](https://linux-hardware.org/?probe=13cda8fea2) | May 08, 2022 |
| ASUSTek       | K53Z                        | [0d68cb4fdd](https://linux-hardware.org/?probe=0d68cb4fdd) | May 04, 2022 |
| Toshiba       | Satellite L735              | [cb523c0933](https://linux-hardware.org/?probe=cb523c0933) | May 02, 2022 |
| Lenovo        | G450 2949                   | [8a97581747](https://linux-hardware.org/?probe=8a97581747) | May 02, 2022 |
| Dell          | Vostro 1510                 | [3b071a4b76](https://linux-hardware.org/?probe=3b071a4b76) | Apr 29, 2022 |
| Dell          | Vostro 1510                 | [483727ec47](https://linux-hardware.org/?probe=483727ec47) | Apr 29, 2022 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [8a8d7b120a](https://linux-hardware.org/?probe=8a8d7b120a) | Apr 24, 2022 |
| Acer          | Aspire A515-51              | [9f8f3a2eb5](https://linux-hardware.org/?probe=9f8f3a2eb5) | Apr 23, 2022 |
| Acer          | Aspire A515-51              | [738850499d](https://linux-hardware.org/?probe=738850499d) | Apr 23, 2022 |
| Acer          | Aspire A515-51              | [fd8cacef33](https://linux-hardware.org/?probe=fd8cacef33) | Apr 23, 2022 |
| Lenovo        | Z40-70 20366                | [c77a5735b7](https://linux-hardware.org/?probe=c77a5735b7) | Apr 20, 2022 |
| MSI           | Creator 15 A10SFS           | [42b2140343](https://linux-hardware.org/?probe=42b2140343) | Apr 15, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [1877553731](https://linux-hardware.org/?probe=1877553731) | Apr 15, 2022 |
| HP            | ProBook 4430s               | [79e30d321b](https://linux-hardware.org/?probe=79e30d321b) | Apr 15, 2022 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | [4a159b7cd8](https://linux-hardware.org/?probe=4a159b7cd8) | Apr 14, 2022 |
| Acer          | Aspire 4740                 | [d401412daa](https://linux-hardware.org/?probe=d401412daa) | Apr 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [ab7173f335](https://linux-hardware.org/?probe=ab7173f335) | Apr 10, 2022 |
| Lenovo        | ThinkPad X220 4291AN3       | [848b7902d8](https://linux-hardware.org/?probe=848b7902d8) | Apr 10, 2022 |
| ASUSTek       | X541SA                      | [1d7a301fe2](https://linux-hardware.org/?probe=1d7a301fe2) | Apr 08, 2022 |
| Toshiba       | Satellite L735              | [b7873249a4](https://linux-hardware.org/?probe=b7873249a4) | Apr 07, 2022 |
| Toshiba       | Satellite P755              | [b3601d9299](https://linux-hardware.org/?probe=b3601d9299) | Apr 05, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [38036fe92b](https://linux-hardware.org/?probe=38036fe92b) | Apr 05, 2022 |
| HP            | ProBook 430 G3              | [8623b2ac51](https://linux-hardware.org/?probe=8623b2ac51) | Mar 30, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [0e93a8600c](https://linux-hardware.org/?probe=0e93a8600c) | Mar 27, 2022 |
| Dell          | Vostro 1500                 | [dc0e34cb10](https://linux-hardware.org/?probe=dc0e34cb10) | Mar 26, 2022 |
| Lenovo        | Legion 7 16ACHg6 82N6       | [5b371c14a6](https://linux-hardware.org/?probe=5b371c14a6) | Mar 25, 2022 |
| Acer          | Aspire 3690                 | [76139c48e8](https://linux-hardware.org/?probe=76139c48e8) | Mar 25, 2022 |
| Acer          | Aspire 4738                 | [c809b67c9e](https://linux-hardware.org/?probe=c809b67c9e) | Mar 23, 2022 |
| HP            | Pavilion 10 TS              | [e149d7ed93](https://linux-hardware.org/?probe=e149d7ed93) | Mar 23, 2022 |
| Dell          | Latitude E5420              | [b15d85a6e9](https://linux-hardware.org/?probe=b15d85a6e9) | Mar 22, 2022 |
| Toshiba       | Satellite P755              | [f8d12d8ab9](https://linux-hardware.org/?probe=f8d12d8ab9) | Mar 22, 2022 |
| HP            | 550                         | [91f443bb06](https://linux-hardware.org/?probe=91f443bb06) | Mar 18, 2022 |
| HP            | 550                         | [8acaec9ff1](https://linux-hardware.org/?probe=8acaec9ff1) | Mar 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [8c94df31c1](https://linux-hardware.org/?probe=8c94df31c1) | Mar 16, 2022 |
| Lenovo        | N22 80S6                    | [279ca719c8](https://linux-hardware.org/?probe=279ca719c8) | Mar 16, 2022 |
| HP            | Laptop 15-da0xxx            | [51409532cc](https://linux-hardware.org/?probe=51409532cc) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [1b91ffaa87](https://linux-hardware.org/?probe=1b91ffaa87) | Mar 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [21dfbc138d](https://linux-hardware.org/?probe=21dfbc138d) | Mar 13, 2022 |
| Lenovo        | ThinkPad T430 2347AF3       | [8fa4355200](https://linux-hardware.org/?probe=8fa4355200) | Mar 08, 2022 |
| MSI           | Alpha 17 B5EEK              | [3298d34369](https://linux-hardware.org/?probe=3298d34369) | Mar 07, 2022 |
| Lenovo        | ThinkPad X201 3680DQ1       | [b1a7b4593a](https://linux-hardware.org/?probe=b1a7b4593a) | Mar 07, 2022 |
| MSI           | Alpha 17 B5EEK              | [1e54d4f165](https://linux-hardware.org/?probe=1e54d4f165) | Mar 06, 2022 |
| Lenovo        | ThinkPad X201 3680DQ1       | [f10cf42ebf](https://linux-hardware.org/?probe=f10cf42ebf) | Mar 06, 2022 |
| Apple         | MacBookAir3,1               | [b887ed3aa2](https://linux-hardware.org/?probe=b887ed3aa2) | Mar 06, 2022 |
| Apple         | MacBookAir3,1               | [07cade8a02](https://linux-hardware.org/?probe=07cade8a02) | Mar 06, 2022 |
| HP            | 245 G3                      | [879094e00f](https://linux-hardware.org/?probe=879094e00f) | Mar 02, 2022 |
| ASUSTek       | K43E                        | [484fd9a41a](https://linux-hardware.org/?probe=484fd9a41a) | Feb 27, 2022 |
| Dell          | Latitude 5179               | [b28766add3](https://linux-hardware.org/?probe=b28766add3) | Feb 18, 2022 |
| Lenovo        | ThinkPad X240 20AMA4V500    | [e6a94741de](https://linux-hardware.org/?probe=e6a94741de) | Feb 17, 2022 |
| Acer          | Swift SF314-56              | [a6c7102b14](https://linux-hardware.org/?probe=a6c7102b14) | Feb 14, 2022 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [e783775e08](https://linux-hardware.org/?probe=e783775e08) | Feb 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [8bcb36b8c7](https://linux-hardware.org/?probe=8bcb36b8c7) | Feb 09, 2022 |
| ASUSTek       | UX305FA                     | [ce2c94c97c](https://linux-hardware.org/?probe=ce2c94c97c) | Feb 07, 2022 |
| Sony          | VGN-FW170J                  | [edead40b0d](https://linux-hardware.org/?probe=edead40b0d) | Feb 07, 2022 |
| Framework     | Laptop                      | [55d5b56564](https://linux-hardware.org/?probe=55d5b56564) | Feb 07, 2022 |
| HP            | ProBook 440 G5              | [5f6a923aa2](https://linux-hardware.org/?probe=5f6a923aa2) | Feb 05, 2022 |
| HP            | ProBook 440 G5              | [6ff30e8299](https://linux-hardware.org/?probe=6ff30e8299) | Feb 05, 2022 |
| HP            | 240 G7                      | [48bc3b139b](https://linux-hardware.org/?probe=48bc3b139b) | Feb 03, 2022 |
| Lenovo        | ThinkPad X240 20AMA2AN00    | [3d321c7afd](https://linux-hardware.org/?probe=3d321c7afd) | Jan 28, 2022 |
| Lenovo        | ThinkPad X240 20AMA2AN00    | [dd9909e9f4](https://linux-hardware.org/?probe=dd9909e9f4) | Jan 28, 2022 |
| MSI           | GF75 Thin 10SER             | [2e94cc2b4c](https://linux-hardware.org/?probe=2e94cc2b4c) | Jan 22, 2022 |
| MSI           | GE72 2QE                    | [cbd609290e](https://linux-hardware.org/?probe=cbd609290e) | Jan 21, 2022 |
| MSI           | GE72 2QE                    | [72843af2fc](https://linux-hardware.org/?probe=72843af2fc) | Jan 14, 2022 |
| Acer          | Aspire V5-121               | [fb3b510c66](https://linux-hardware.org/?probe=fb3b510c66) | Jan 06, 2022 |
| Acer          | Aspire V5-121               | [be57155d1f](https://linux-hardware.org/?probe=be57155d1f) | Jan 06, 2022 |
| HP            | ProBook 450 G1              | [3a0d2d3754](https://linux-hardware.org/?probe=3a0d2d3754) | Jan 05, 2022 |
| HP            | ProBook 450 G1              | [4516e6113b](https://linux-hardware.org/?probe=4516e6113b) | Jan 05, 2022 |
| MSI           | PS63 Modern 8RD             | [1cd435c54f](https://linux-hardware.org/?probe=1cd435c54f) | Jan 04, 2022 |
| Dell          | XPS 13 7390                 | [36a412db42](https://linux-hardware.org/?probe=36a412db42) | Dec 29, 2021 |
| Acer          | Nitro AN515-44              | [8fba60c1a8](https://linux-hardware.org/?probe=8fba60c1a8) | Dec 28, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [9e022a2288](https://linux-hardware.org/?probe=9e022a2288) | Dec 26, 2021 |
| Lenovo        | Legion 5 17ARH05H 82GN      | [8ff8fb5efd](https://linux-hardware.org/?probe=8ff8fb5efd) | Dec 26, 2021 |
| ASUSTek       | ZenBook UX325JA_UX325JA     | [c9cffe7310](https://linux-hardware.org/?probe=c9cffe7310) | Dec 24, 2021 |
| HP            | Laptop 15-da0xxx            | [2b3ad3643a](https://linux-hardware.org/?probe=2b3ad3643a) | Dec 14, 2021 |
| HUAWEI        | BOHB-WAX9                   | [b3f7681477](https://linux-hardware.org/?probe=b3f7681477) | Dec 06, 2021 |
| HP            | ProBook 6450b               | [df1987d444](https://linux-hardware.org/?probe=df1987d444) | Dec 04, 2021 |
| HP            | 14                          | [d7cb66a845](https://linux-hardware.org/?probe=d7cb66a845) | Nov 28, 2021 |
| Dell          | Vostro 3400                 | [d8946eaf3c](https://linux-hardware.org/?probe=d8946eaf3c) | Nov 28, 2021 |
| Lenovo        | G40-45 80E1                 | [b3cdb202fc](https://linux-hardware.org/?probe=b3cdb202fc) | Nov 28, 2021 |
| ASUSTek       | X455LJ                      | [018d5bcbac](https://linux-hardware.org/?probe=018d5bcbac) | Nov 27, 2021 |
| HP            | Compaq CQ45                 | [7d66f3183b](https://linux-hardware.org/?probe=7d66f3183b) | Nov 24, 2021 |
| HP            | ProBook 440 G1              | [6159b4aa5a](https://linux-hardware.org/?probe=6159b4aa5a) | Nov 20, 2021 |
| HP            | ProBook 440 G1              | [42d0889355](https://linux-hardware.org/?probe=42d0889355) | Nov 20, 2021 |
| ASUSTek       | X441NA                      | [da21de67fb](https://linux-hardware.org/?probe=da21de67fb) | Nov 18, 2021 |
| HP            | Pavilion dv9700             | [2d4636d0ee](https://linux-hardware.org/?probe=2d4636d0ee) | Nov 17, 2021 |
| HP            | Pavilion dv9700             | [e5da3884b4](https://linux-hardware.org/?probe=e5da3884b4) | Nov 17, 2021 |
| ASUSTek       | X550ZE                      | [b98c646c47](https://linux-hardware.org/?probe=b98c646c47) | Nov 16, 2021 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [18152a84af](https://linux-hardware.org/?probe=18152a84af) | Nov 13, 2021 |
| Lenovo        | ThinkPad T495 20NKS0QN0V    | [ceab02dda1](https://linux-hardware.org/?probe=ceab02dda1) | Nov 07, 2021 |
| Dell          | Latitude 7490               | [43eeb8d632](https://linux-hardware.org/?probe=43eeb8d632) | Nov 06, 2021 |
| Dell          | Latitude 7490               | [209cc4c51e](https://linux-hardware.org/?probe=209cc4c51e) | Nov 06, 2021 |
| HP            | Pavilion dv4                | [7e9733638c](https://linux-hardware.org/?probe=7e9733638c) | Nov 04, 2021 |
| ASUSTek       | X550ZE                      | [dcd63f8987](https://linux-hardware.org/?probe=dcd63f8987) | Oct 31, 2021 |
| Dell          | Inspiron 5515               | [809fe8da11](https://linux-hardware.org/?probe=809fe8da11) | Oct 30, 2021 |
| Acer          | Nitro AN515-52              | [7f70de1771](https://linux-hardware.org/?probe=7f70de1771) | Oct 26, 2021 |
| Acer          | Nitro AN515-52              | [6777af6e6a](https://linux-hardware.org/?probe=6777af6e6a) | Oct 26, 2021 |
| Lenovo        | G40-45 80E1                 | [61b1e7901a](https://linux-hardware.org/?probe=61b1e7901a) | Oct 17, 2021 |
| Acer          | Aspire E1-522               | [dc7a02c862](https://linux-hardware.org/?probe=dc7a02c862) | Oct 15, 2021 |
| HP            | 240 G3                      | [a083502110](https://linux-hardware.org/?probe=a083502110) | Oct 11, 2021 |
| HP            | 240 G3                      | [1772f88ed6](https://linux-hardware.org/?probe=1772f88ed6) | Oct 11, 2021 |
| Toshiba       | Satellite C45-A             | [ee28fa6dfb](https://linux-hardware.org/?probe=ee28fa6dfb) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [b2a9183e6d](https://linux-hardware.org/?probe=b2a9183e6d) | Oct 09, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [330659159b](https://linux-hardware.org/?probe=330659159b) | Oct 07, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [14d286f67e](https://linux-hardware.org/?probe=14d286f67e) | Oct 07, 2021 |
| Acer          | Aspire E3-111               | [45a0e8618a](https://linux-hardware.org/?probe=45a0e8618a) | Sep 28, 2021 |
| Acer          | Aspire E3-111               | [f0100402ec](https://linux-hardware.org/?probe=f0100402ec) | Sep 28, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a451fc441b](https://linux-hardware.org/?probe=a451fc441b) | Sep 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [643c70dec0](https://linux-hardware.org/?probe=643c70dec0) | Sep 27, 2021 |
| ASUSTek       | K53SD                       | [0f6a772a44](https://linux-hardware.org/?probe=0f6a772a44) | Sep 25, 2021 |
| Dell          | XPS 15 9550                 | [6e9f3c8012](https://linux-hardware.org/?probe=6e9f3c8012) | Sep 22, 2021 |
| HP            | ProBook 450 G1              | [e6fbfad3de](https://linux-hardware.org/?probe=e6fbfad3de) | Sep 16, 2021 |
| Gateway       | NV47H                       | [8cef362c2e](https://linux-hardware.org/?probe=8cef362c2e) | Sep 15, 2021 |
| Gateway       | NV47H                       | [0ad04889c5](https://linux-hardware.org/?probe=0ad04889c5) | Sep 15, 2021 |
| Dell          | Latitude E7270              | [479b6d4aa9](https://linux-hardware.org/?probe=479b6d4aa9) | Sep 14, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [2300be2f19](https://linux-hardware.org/?probe=2300be2f19) | Sep 13, 2021 |
| HP            | 2000                        | [7d8cd719a2](https://linux-hardware.org/?probe=7d8cd719a2) | Sep 09, 2021 |
| Dell          | Inspiron 1110               | [890d9d9d24](https://linux-hardware.org/?probe=890d9d9d24) | Sep 08, 2021 |
| Dell          | Inspiron 1110               | [e299761316](https://linux-hardware.org/?probe=e299761316) | Sep 08, 2021 |
| ASUSTek       | X555QA                      | [043083e9e8](https://linux-hardware.org/?probe=043083e9e8) | Sep 04, 2021 |
| ASUSTek       | X555QG                      | [badf1b0736](https://linux-hardware.org/?probe=badf1b0736) | Aug 30, 2021 |
| Unknown       | Unknown                     | [33a8107059](https://linux-hardware.org/?probe=33a8107059) | Aug 28, 2021 |
| Unknown       | Unknown                     | [fe2ba9da7c](https://linux-hardware.org/?probe=fe2ba9da7c) | Aug 28, 2021 |
| HP            | EliteBook 840 G6            | [08c766b957](https://linux-hardware.org/?probe=08c766b957) | Aug 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [7e6a9f0430](https://linux-hardware.org/?probe=7e6a9f0430) | Aug 25, 2021 |
| HP            | 14                          | [6d84790759](https://linux-hardware.org/?probe=6d84790759) | Aug 23, 2021 |
| Fujitsu Si... | AMILO PRO V3515             | [e7f145f52b](https://linux-hardware.org/?probe=e7f145f52b) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [ad6e3e064f](https://linux-hardware.org/?probe=ad6e3e064f) | Aug 21, 2021 |
| Apple         | MacBook4,1                  | [9a5653e44d](https://linux-hardware.org/?probe=9a5653e44d) | Aug 21, 2021 |
| Timi          | A35S                        | [1f0e95ee1d](https://linux-hardware.org/?probe=1f0e95ee1d) | Aug 17, 2021 |
| ASUSTek       | X441SA                      | [f23d4d50be](https://linux-hardware.org/?probe=f23d4d50be) | Aug 16, 2021 |
| ASUSTek       | K53SD                       | [865c697e6a](https://linux-hardware.org/?probe=865c697e6a) | Aug 13, 2021 |
| Dell          | Precision 3551              | [da8459ac73](https://linux-hardware.org/?probe=da8459ac73) | Aug 10, 2021 |
| Dell          | Precision 3551              | [aeeeb63990](https://linux-hardware.org/?probe=aeeeb63990) | Aug 10, 2021 |
| Dell          | Latitude D630               | [ceb9ca591f](https://linux-hardware.org/?probe=ceb9ca591f) | Aug 05, 2021 |
| Dell          | XPS 13 9310                 | [20eabf2484](https://linux-hardware.org/?probe=20eabf2484) | Aug 02, 2021 |
| MSI           | MS-16GF                     | [ba0b532d35](https://linux-hardware.org/?probe=ba0b532d35) | Aug 01, 2021 |
| ASUSTek       | K46CM                       | [a627b4644e](https://linux-hardware.org/?probe=a627b4644e) | Jul 30, 2021 |
| ASUSTek       | K46CM                       | [ac14ce7f86](https://linux-hardware.org/?probe=ac14ce7f86) | Jul 30, 2021 |
| Lenovo        | ThinkPad X220 4293B43       | [7accb85da9](https://linux-hardware.org/?probe=7accb85da9) | Jul 30, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [efc844205b](https://linux-hardware.org/?probe=efc844205b) | Jul 27, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [2ce8f90f70](https://linux-hardware.org/?probe=2ce8f90f70) | Jul 26, 2021 |
| Acer          | Aspire A515-41G             | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| Lenovo        | G40-45 80E1                 | [fef67a0fc3](https://linux-hardware.org/?probe=fef67a0fc3) | Jul 24, 2021 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | [4a458edcf6](https://linux-hardware.org/?probe=4a458edcf6) | Jul 24, 2021 |
| HP            | Presario CQ42               | [fa65f13c3b](https://linux-hardware.org/?probe=fa65f13c3b) | Jul 23, 2021 |
| Dell          | Inspiron 3493               | [df4bedc1fd](https://linux-hardware.org/?probe=df4bedc1fd) | Jul 21, 2021 |
| HP            | Laptop 15-db0xxx            | [9182648939](https://linux-hardware.org/?probe=9182648939) | Jul 19, 2021 |
| Acer          | TravelMate P2410-G2-M       | [7088129430](https://linux-hardware.org/?probe=7088129430) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [36b0d241cd](https://linux-hardware.org/?probe=36b0d241cd) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [3c938f74fd](https://linux-hardware.org/?probe=3c938f74fd) | Jul 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [3508d853ae](https://linux-hardware.org/?probe=3508d853ae) | Jul 09, 2021 |
| ASUSTek       | K401UQ                      | [9f9a853e03](https://linux-hardware.org/?probe=9f9a853e03) | Jul 05, 2021 |
| Lenovo        | ThinkPad T460s 20FAA0860... | [850c33e5c3](https://linux-hardware.org/?probe=850c33e5c3) | Jul 04, 2021 |
| ASUSTek       | G73Jw                       | [b1d6609434](https://linux-hardware.org/?probe=b1d6609434) | Jul 03, 2021 |
| Lenovo        | ThinkPad W510 4391BY8       | [12d0ff5c27](https://linux-hardware.org/?probe=12d0ff5c27) | Jul 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [bc19b4b3bf](https://linux-hardware.org/?probe=bc19b4b3bf) | Jul 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [c1442501a0](https://linux-hardware.org/?probe=c1442501a0) | Jul 03, 2021 |
| Dell          | Latitude E6430              | [ce6bc6552c](https://linux-hardware.org/?probe=ce6bc6552c) | Jun 29, 2021 |
| Dell          | Latitude 7414               | [5557aada9a](https://linux-hardware.org/?probe=5557aada9a) | Jun 28, 2021 |
| ASUSTek       | X441UA                      | [3574e8459f](https://linux-hardware.org/?probe=3574e8459f) | Jun 25, 2021 |
| HP            | Pavilion 10 TS              | [1759d8d1f8](https://linux-hardware.org/?probe=1759d8d1f8) | Jun 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | [b845fbd6b0](https://linux-hardware.org/?probe=b845fbd6b0) | Jun 20, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [3eb01e93e5](https://linux-hardware.org/?probe=3eb01e93e5) | Jun 16, 2021 |
| Acer          | A315-41G                    | [c3b9603724](https://linux-hardware.org/?probe=c3b9603724) | Jun 15, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [bd7d3a3b09](https://linux-hardware.org/?probe=bd7d3a3b09) | Jun 11, 2021 |
| Acer          | Aspire E5-471               | [f15409e7cc](https://linux-hardware.org/?probe=f15409e7cc) | Jun 10, 2021 |
| Dell          | Vostro 3400                 | [2e841a4dc4](https://linux-hardware.org/?probe=2e841a4dc4) | Jun 09, 2021 |
| HP            | ProBook 440 G3              | [a5547e4146](https://linux-hardware.org/?probe=a5547e4146) | Jun 08, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [d15f22008c](https://linux-hardware.org/?probe=d15f22008c) | Jun 08, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [82dff2688d](https://linux-hardware.org/?probe=82dff2688d) | Jun 07, 2021 |
| HP            | Pavilion 10 TS              | [ad461cbf3e](https://linux-hardware.org/?probe=ad461cbf3e) | Jun 07, 2021 |
| HP            | 245 G6                      | [a3594ab925](https://linux-hardware.org/?probe=a3594ab925) | Jun 03, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [c72d3fa57d](https://linux-hardware.org/?probe=c72d3fa57d) | Jun 02, 2021 |
| Acer          | Aspire 4750                 | [499479904d](https://linux-hardware.org/?probe=499479904d) | May 27, 2021 |
| ASUSTek       | UX430UAR                    | [9f332f4fec](https://linux-hardware.org/?probe=9f332f4fec) | May 25, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [55abc8169d](https://linux-hardware.org/?probe=55abc8169d) | May 24, 2021 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | [f367112b19](https://linux-hardware.org/?probe=f367112b19) | May 22, 2021 |
| HP            | Notebook                    | [1ce5457d13](https://linux-hardware.org/?probe=1ce5457d13) | May 21, 2021 |
| HP            | Notebook                    | [42756549fb](https://linux-hardware.org/?probe=42756549fb) | May 21, 2021 |
| Toshiba       | Satellite C850-B797         | [834d15c08c](https://linux-hardware.org/?probe=834d15c08c) | May 16, 2021 |
| Toshiba       | Satellite C850-B797         | [0ece4b9e9e](https://linux-hardware.org/?probe=0ece4b9e9e) | May 16, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [00a8ed533c](https://linux-hardware.org/?probe=00a8ed533c) | May 15, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [14b8295348](https://linux-hardware.org/?probe=14b8295348) | May 15, 2021 |
| Apple         | MacBookAir7,2               | [df405076a1](https://linux-hardware.org/?probe=df405076a1) | May 14, 2021 |
| Toshiba       | Satellite C850-B797         | [1355c6e459](https://linux-hardware.org/?probe=1355c6e459) | May 13, 2021 |
| Lenovo        | ThinkPad T420 42363Y5       | [5a93fb1b0b](https://linux-hardware.org/?probe=5a93fb1b0b) | May 07, 2021 |
| Dell          | Inspiron 3480               | [5ad427cffb](https://linux-hardware.org/?probe=5ad427cffb) | May 04, 2021 |
| Dell          | XPS 15 9550                 | [30b952e127](https://linux-hardware.org/?probe=30b952e127) | May 02, 2021 |
| Notebook      | N150CU                      | [e62762a731](https://linux-hardware.org/?probe=e62762a731) | Apr 14, 2021 |
| Lenovo        | ThinkPad X260 20F5A0HB00    | [9163ce31dc](https://linux-hardware.org/?probe=9163ce31dc) | Apr 14, 2021 |
| Lenovo        | G40-45 80E1                 | [1263e938c8](https://linux-hardware.org/?probe=1263e938c8) | Apr 13, 2021 |
| Lenovo        | G40-45 80E1                 | [5fada7c64a](https://linux-hardware.org/?probe=5fada7c64a) | Apr 13, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [cdf6743f68](https://linux-hardware.org/?probe=cdf6743f68) | Apr 08, 2021 |
| Lenovo        | V330-14IKB 81B0             | [729cbf17a4](https://linux-hardware.org/?probe=729cbf17a4) | Apr 07, 2021 |
| Lenovo        | ThinkPad X230 2325BG3       | [90f6078b02](https://linux-hardware.org/?probe=90f6078b02) | Apr 04, 2021 |
| ASUSTek       | X555DG                      | [334a8d4184](https://linux-hardware.org/?probe=334a8d4184) | Apr 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [2af0a44c72](https://linux-hardware.org/?probe=2af0a44c72) | Apr 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [2c67d604ff](https://linux-hardware.org/?probe=2c67d604ff) | Mar 28, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [01ab712b94](https://linux-hardware.org/?probe=01ab712b94) | Mar 22, 2021 |
| ASUSTek       | N53SM                       | [87e7b3b248](https://linux-hardware.org/?probe=87e7b3b248) | Mar 22, 2021 |
| Toshiba       | Satellite U505              | [1d422767e1](https://linux-hardware.org/?probe=1d422767e1) | Mar 20, 2021 |
| Toshiba       | Satellite U505              | [ccb5c756ee](https://linux-hardware.org/?probe=ccb5c756ee) | Mar 20, 2021 |
| Acer          | AOD255                      | [2e5b228a04](https://linux-hardware.org/?probe=2e5b228a04) | Mar 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [843d061b78](https://linux-hardware.org/?probe=843d061b78) | Mar 15, 2021 |
| HP            | Laptop 14-cm1xxx            | [87cabd058e](https://linux-hardware.org/?probe=87cabd058e) | Mar 13, 2021 |
| HP            | 245 G7 Notebook PC          | [8cb18a4f6c](https://linux-hardware.org/?probe=8cb18a4f6c) | Mar 11, 2021 |
| HP            | 245 G7 Notebook PC          | [a6e9e8ea5e](https://linux-hardware.org/?probe=a6e9e8ea5e) | Mar 11, 2021 |
| Acer          | AOD255                      | [f3a5b4b0e4](https://linux-hardware.org/?probe=f3a5b4b0e4) | Mar 06, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [d9708c63f5](https://linux-hardware.org/?probe=d9708c63f5) | Mar 04, 2021 |
| Dell          | Precision 3551              | [d75a598209](https://linux-hardware.org/?probe=d75a598209) | Mar 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [bc879be58b](https://linux-hardware.org/?probe=bc879be58b) | Mar 03, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [27b7f94851](https://linux-hardware.org/?probe=27b7f94851) | Mar 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [935f9c5571](https://linux-hardware.org/?probe=935f9c5571) | Mar 03, 2021 |
| HP            | Pavilion 10 TS              | [5998c38555](https://linux-hardware.org/?probe=5998c38555) | Feb 26, 2021 |
| Dell          | Latitude E6220              | [1c0ab9fab1](https://linux-hardware.org/?probe=1c0ab9fab1) | Feb 23, 2021 |
| Dell          | Latitude E6220              | [19e1a4a1d6](https://linux-hardware.org/?probe=19e1a4a1d6) | Feb 23, 2021 |
| Dell          | Inspiron 3493               | [684245175e](https://linux-hardware.org/?probe=684245175e) | Feb 20, 2021 |
| Acer          | TravelMate P449-G2-M        | [7581904d41](https://linux-hardware.org/?probe=7581904d41) | Feb 20, 2021 |
| Apple         | MacBookPro15,1              | [a148b9034a](https://linux-hardware.org/?probe=a148b9034a) | Feb 19, 2021 |
| HP            | ProBook 440 G7              | [f6830c6ac2](https://linux-hardware.org/?probe=f6830c6ac2) | Feb 18, 2021 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | [ecddf05f3e](https://linux-hardware.org/?probe=ecddf05f3e) | Feb 16, 2021 |
| BAKED         | P7xxDM2(-G)                 | [824169b9f7](https://linux-hardware.org/?probe=824169b9f7) | Feb 16, 2021 |
| HP            | ProBook 440 G2              | [8be5048c51](https://linux-hardware.org/?probe=8be5048c51) | Feb 15, 2021 |
| Lenovo        | IdeaPad 520S-14IKB 80X2     | [8da12e7518](https://linux-hardware.org/?probe=8da12e7518) | Feb 14, 2021 |
| Inspur        | M11JB R2.0/R1.1             | [5e5731f2b0](https://linux-hardware.org/?probe=5e5731f2b0) | Feb 13, 2021 |
| Inspur        | M11JB R2.0/R1.1             | [90847dec81](https://linux-hardware.org/?probe=90847dec81) | Feb 12, 2021 |
| HP            | Notebook                    | [5224b13971](https://linux-hardware.org/?probe=5224b13971) | Feb 08, 2021 |
| Dell          | Inspiron 7586               | [7e6463f517](https://linux-hardware.org/?probe=7e6463f517) | Feb 05, 2021 |
| ASUSTek       | X505BA                      | [8059f98337](https://linux-hardware.org/?probe=8059f98337) | Feb 03, 2021 |
| HP            | Presario CQ43               | [13eb02bc61](https://linux-hardware.org/?probe=13eb02bc61) | Feb 02, 2021 |
| HP            | Presario CQ43               | [a6d1b8df1e](https://linux-hardware.org/?probe=a6d1b8df1e) | Feb 02, 2021 |
| Notebook      | N150CU                      | [7753afd04f](https://linux-hardware.org/?probe=7753afd04f) | Jan 29, 2021 |
| Lenovo        | ThinkPad L430 2466EC5       | [8f5111df1d](https://linux-hardware.org/?probe=8f5111df1d) | Jan 28, 2021 |
| Acer          | Aspire E5-575G              | [eac34165b9](https://linux-hardware.org/?probe=eac34165b9) | Jan 27, 2021 |
| HP            | Laptop 15-db0xxx            | [ab91702ac3](https://linux-hardware.org/?probe=ab91702ac3) | Jan 26, 2021 |
| GreatWall     | K41                         | [ddf99d904e](https://linux-hardware.org/?probe=ddf99d904e) | Jan 25, 2021 |
| ASUSTek       | X555LN                      | [e649cc1304](https://linux-hardware.org/?probe=e649cc1304) | Jan 24, 2021 |
| ASUSTek       | X441UVK                     | [c73eaa8a8f](https://linux-hardware.org/?probe=c73eaa8a8f) | Jan 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0ca25f14fb](https://linux-hardware.org/?probe=0ca25f14fb) | Jan 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [419800f72d](https://linux-hardware.org/?probe=419800f72d) | Jan 21, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [844d185dae](https://linux-hardware.org/?probe=844d185dae) | Jan 21, 2021 |
| Dell          | XPS 15 9550                 | [91a85ad436](https://linux-hardware.org/?probe=91a85ad436) | Jan 20, 2021 |
| Lenovo        | IdeaPad S340-14IWL 81N7     | [62de1cd91f](https://linux-hardware.org/?probe=62de1cd91f) | Jan 16, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [edcaecc674](https://linux-hardware.org/?probe=edcaecc674) | Jan 14, 2021 |
| ASUSTek       | K46CM                       | [e5d77ec648](https://linux-hardware.org/?probe=e5d77ec648) | Jan 14, 2021 |
| Dell          | Precision 3551              | [c6524a92a4](https://linux-hardware.org/?probe=c6524a92a4) | Jan 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6d637febe2](https://linux-hardware.org/?probe=6d637febe2) | Jan 10, 2021 |
| ASUSTek       | X455LJ                      | [05b3190864](https://linux-hardware.org/?probe=05b3190864) | Jan 08, 2021 |
| Lenovo        | Y720-15IKB 80VR             | [0d58fd33df](https://linux-hardware.org/?probe=0d58fd33df) | Jan 07, 2021 |
| Lenovo        | Y720-15IKB 80VR             | [d1947d8c18](https://linux-hardware.org/?probe=d1947d8c18) | Jan 07, 2021 |
| Dell          | System XPS L502X            | [6548d3214b](https://linux-hardware.org/?probe=6548d3214b) | Jan 06, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [4e9f49422a](https://linux-hardware.org/?probe=4e9f49422a) | Jan 04, 2021 |
| BAKED         | P7xxDM2(-G)                 | [c4206ecc26](https://linux-hardware.org/?probe=c4206ecc26) | Jan 04, 2021 |
| Lenovo        | B41-35 80LD                 | [f995163ff4](https://linux-hardware.org/?probe=f995163ff4) | Jan 04, 2021 |
| Lenovo        | B41-35 80LD                 | [2758658d90](https://linux-hardware.org/?probe=2758658d90) | Jan 04, 2021 |
| ASUSTek       | X555QG                      | [801defb54c](https://linux-hardware.org/?probe=801defb54c) | Jan 02, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | [6b7c6db0c5](https://linux-hardware.org/?probe=6b7c6db0c5) | Dec 30, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [10b0b04256](https://linux-hardware.org/?probe=10b0b04256) | Dec 30, 2020 |
| Notebook      | NB50TJ1_TK1                 | [10d64eecc5](https://linux-hardware.org/?probe=10d64eecc5) | Dec 30, 2020 |
| HP            | Laptop 14-cm1xxx            | [e850bec31a](https://linux-hardware.org/?probe=e850bec31a) | Dec 29, 2020 |
| Acer          | Aspire E5-575G              | [3c4ea54770](https://linux-hardware.org/?probe=3c4ea54770) | Dec 26, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d61f2aa238](https://linux-hardware.org/?probe=d61f2aa238) | Dec 26, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [bca2708dcd](https://linux-hardware.org/?probe=bca2708dcd) | Dec 25, 2020 |
| ASUSTek       | X450CP                      | [1d2d82e5ee](https://linux-hardware.org/?probe=1d2d82e5ee) | Dec 22, 2020 |
| Apple         | MacBookPro11,1              | [e395d72cbb](https://linux-hardware.org/?probe=e395d72cbb) | Dec 21, 2020 |
| HP            | Pavilion dv4                | [0f86ea7cab](https://linux-hardware.org/?probe=0f86ea7cab) | Dec 20, 2020 |
| HP            | ProBook 440 G3              | [ad30a7ae38](https://linux-hardware.org/?probe=ad30a7ae38) | Dec 20, 2020 |
| Notebook      | NB50TJ1_TK1                 | [c23ae5c475](https://linux-hardware.org/?probe=c23ae5c475) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y550P 3241          | [2475252354](https://linux-hardware.org/?probe=2475252354) | Dec 19, 2020 |
| Lenovo        | IdeaPad Y550P 3241          | [a08f4cf4e5](https://linux-hardware.org/?probe=a08f4cf4e5) | Dec 19, 2020 |
| ASUSTek       | X555QG                      | [263df4fa91](https://linux-hardware.org/?probe=263df4fa91) | Dec 19, 2020 |
| HP            | Laptop 15-da0xxx            | [73fa61c233](https://linux-hardware.org/?probe=73fa61c233) | Dec 15, 2020 |
| Lenovo        | IdeaPad Y410P 20216         | [dd0d449586](https://linux-hardware.org/?probe=dd0d449586) | Dec 14, 2020 |
| Notebook      | NB50TJ1_TK1                 | [246d659f60](https://linux-hardware.org/?probe=246d659f60) | Dec 11, 2020 |
| HP            | Laptop 15-da0xxx            | [fb4783aeba](https://linux-hardware.org/?probe=fb4783aeba) | Dec 10, 2020 |
| Lenovo        | Yoga 700-11ISK 80QE         | [1a353b9226](https://linux-hardware.org/?probe=1a353b9226) | Dec 08, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [3962cbfb58](https://linux-hardware.org/?probe=3962cbfb58) | Dec 05, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [3d5a1c07e6](https://linux-hardware.org/?probe=3d5a1c07e6) | Dec 05, 2020 |
| Lenovo        | IdeaPad S145-14API 81UV     | [02fb63a36f](https://linux-hardware.org/?probe=02fb63a36f) | Dec 04, 2020 |
| ASUSTek       | X555QG                      | [841208193d](https://linux-hardware.org/?probe=841208193d) | Dec 03, 2020 |
| ASUSTek       | K46CM                       | [490bae951e](https://linux-hardware.org/?probe=490bae951e) | Dec 01, 2020 |
| Lenovo        | G470 20078                  | [b0564c0e50](https://linux-hardware.org/?probe=b0564c0e50) | Dec 01, 2020 |
| ASUSTek       | X555QG                      | [e90cdb39ef](https://linux-hardware.org/?probe=e90cdb39ef) | Nov 30, 2020 |
| Lenovo        | IdeaPad U510 20191          | [895b641220](https://linux-hardware.org/?probe=895b641220) | Nov 30, 2020 |
| MSI           | PS63 Modern 8RC             | [0a4b399149](https://linux-hardware.org/?probe=0a4b399149) | Nov 26, 2020 |
| Notebook      | NB50TJ1_TK1                 | [0c9f7ea289](https://linux-hardware.org/?probe=0c9f7ea289) | Nov 26, 2020 |
| Notebook      | NB50TJ1_TK1                 | [a5f5b59788](https://linux-hardware.org/?probe=a5f5b59788) | Nov 26, 2020 |
| HP            | Laptop 15-db0xxx            | [503b8f9701](https://linux-hardware.org/?probe=503b8f9701) | Nov 25, 2020 |
| ASUSTek       | X441NA                      | [61a5d6947b](https://linux-hardware.org/?probe=61a5d6947b) | Nov 25, 2020 |
| Unknown       | Unknown                     | [73dc6959d6](https://linux-hardware.org/?probe=73dc6959d6) | Nov 23, 2020 |
| Unknown       | Unknown                     | [b0c0ef90cd](https://linux-hardware.org/?probe=b0c0ef90cd) | Nov 23, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [a997f8c186](https://linux-hardware.org/?probe=a997f8c186) | Nov 22, 2020 |
| Samsung       | 300V3A/300V4A/300V5A/200... | [e24dba10a2](https://linux-hardware.org/?probe=e24dba10a2) | Nov 22, 2020 |
| ASUSTek       | X441NA                      | [e301cabf95](https://linux-hardware.org/?probe=e301cabf95) | Nov 21, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [5021095fd1](https://linux-hardware.org/?probe=5021095fd1) | Nov 19, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [e5e8cfd574](https://linux-hardware.org/?probe=e5e8cfd574) | Nov 19, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [026fdce11f](https://linux-hardware.org/?probe=026fdce11f) | Nov 13, 2020 |
| Lenovo        | IdeaPad 110-14IBR 80T6      | [b3752255e5](https://linux-hardware.org/?probe=b3752255e5) | Nov 13, 2020 |
| HP            | ProBook 6450b               | [74c2b345b8](https://linux-hardware.org/?probe=74c2b345b8) | Nov 05, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [5efbf0cf43](https://linux-hardware.org/?probe=5efbf0cf43) | Nov 05, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [3f9b54f16c](https://linux-hardware.org/?probe=3f9b54f16c) | Nov 05, 2020 |
| Lenovo        | G450 2949                   | [f9bb66b7a2](https://linux-hardware.org/?probe=f9bb66b7a2) | Nov 03, 2020 |
| ASUSTek       | X411UQ                      | [f3e110826b](https://linux-hardware.org/?probe=f3e110826b) | Nov 01, 2020 |
| ASUSTek       | X411UQ                      | [9786cce501](https://linux-hardware.org/?probe=9786cce501) | Nov 01, 2020 |
| Lenovo        | Z50-70 20354                | [b252d0ad02](https://linux-hardware.org/?probe=b252d0ad02) | Oct 31, 2020 |
| Dell          | XPS 15 9550                 | [f08f791eaf](https://linux-hardware.org/?probe=f08f791eaf) | Oct 28, 2020 |
| Dell          | XPS 15 9550                 | [dcd8f2aa99](https://linux-hardware.org/?probe=dcd8f2aa99) | Oct 27, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [cafb41376f](https://linux-hardware.org/?probe=cafb41376f) | Oct 26, 2020 |
| HP            | Laptop 15-db0xxx            | [fa89c085cf](https://linux-hardware.org/?probe=fa89c085cf) | Oct 25, 2020 |
| Acer          | Aspire 4730Z                | [7157a6069b](https://linux-hardware.org/?probe=7157a6069b) | Oct 21, 2020 |
| Acer          | Aspire 4730Z                | [fb18c13ac7](https://linux-hardware.org/?probe=fb18c13ac7) | Oct 21, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [89c3fe76c0](https://linux-hardware.org/?probe=89c3fe76c0) | Oct 18, 2020 |
| Lenovo        | IdeaPad S340-14API 81NB     | [0a4d06561e](https://linux-hardware.org/?probe=0a4d06561e) | Oct 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [8fb2a0621d](https://linux-hardware.org/?probe=8fb2a0621d) | Oct 12, 2020 |
| Lenovo        | G40-45 80E1                 | [eefc7c92b2](https://linux-hardware.org/?probe=eefc7c92b2) | Oct 11, 2020 |
| Dell          | Latitude E7270              | [cff6ba0c00](https://linux-hardware.org/?probe=cff6ba0c00) | Oct 11, 2020 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [e04a055ab8](https://linux-hardware.org/?probe=e04a055ab8) | Oct 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [c376c39381](https://linux-hardware.org/?probe=c376c39381) | Oct 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [4e2c32a972](https://linux-hardware.org/?probe=4e2c32a972) | Oct 07, 2020 |
| Dell          | Inspiron 3480               | [243905bcf2](https://linux-hardware.org/?probe=243905bcf2) | Oct 06, 2020 |
| HP            | Laptop 15-db0xxx            | [eaeba54519](https://linux-hardware.org/?probe=eaeba54519) | Oct 05, 2020 |
| MPS Mayori... | COIN ST800EDU               | [11e4ae4bfe](https://linux-hardware.org/?probe=11e4ae4bfe) | Oct 03, 2020 |
| MPS Mayori... | COIN ST800EDU               | [38a7d9f974](https://linux-hardware.org/?probe=38a7d9f974) | Oct 03, 2020 |
| HP            | Laptop 15-db0xxx            | [eb0e17a039](https://linux-hardware.org/?probe=eb0e17a039) | Oct 01, 2020 |
| HP            | Laptop 15-db0xxx            | [e0afc29d83](https://linux-hardware.org/?probe=e0afc29d83) | Oct 01, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [4ff7a5528c](https://linux-hardware.org/?probe=4ff7a5528c) | Sep 29, 2020 |
| HP            | EliteBook 8440p             | [21ecdf1804](https://linux-hardware.org/?probe=21ecdf1804) | Sep 28, 2020 |
| HP            | Pavilion 10 TS              | [393e09d070](https://linux-hardware.org/?probe=393e09d070) | Sep 28, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [7ec7b7dbb0](https://linux-hardware.org/?probe=7ec7b7dbb0) | Sep 27, 2020 |
| Dell          | Inspiron 3493               | [be76b68bff](https://linux-hardware.org/?probe=be76b68bff) | Sep 25, 2020 |
| HP            | Notebook                    | [97099ba5b3](https://linux-hardware.org/?probe=97099ba5b3) | Sep 23, 2020 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | [4b3f7c31cc](https://linux-hardware.org/?probe=4b3f7c31cc) | Sep 21, 2020 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | [bf2a498d90](https://linux-hardware.org/?probe=bf2a498d90) | Sep 21, 2020 |
| ASUSTek       | X441UVK                     | [4be17c95ab](https://linux-hardware.org/?probe=4be17c95ab) | Sep 18, 2020 |
| Dell          | Latitude E7270              | [76c31048e9](https://linux-hardware.org/?probe=76c31048e9) | Sep 14, 2020 |
| Toshiba       | Satellite U505              | [20507a8670](https://linux-hardware.org/?probe=20507a8670) | Sep 14, 2020 |
| Dell          | Studio 1558                 | [bfa6ee72ad](https://linux-hardware.org/?probe=bfa6ee72ad) | Sep 11, 2020 |
| Dell          | Studio 1558                 | [09283ede94](https://linux-hardware.org/?probe=09283ede94) | Sep 11, 2020 |
| Acer          | TravelMate 5744             | [cd7e3646ff](https://linux-hardware.org/?probe=cd7e3646ff) | Sep 09, 2020 |
| HP            | EliteBook 840 G5            | [0a16cda83f](https://linux-hardware.org/?probe=0a16cda83f) | Sep 08, 2020 |
| Dell          | Inspiron N5040              | [7d81a97615](https://linux-hardware.org/?probe=7d81a97615) | Sep 07, 2020 |
| Dell          | Inspiron 5570               | [c184b08cc3](https://linux-hardware.org/?probe=c184b08cc3) | Sep 06, 2020 |
| Acer          | Aspire E5-575G              | [71698fa8ea](https://linux-hardware.org/?probe=71698fa8ea) | Sep 05, 2020 |
| Acer          | Aspire 7741                 | [e5914ee358](https://linux-hardware.org/?probe=e5914ee358) | Sep 05, 2020 |
| Dell          | Inspiron 3493               | [11adb16243](https://linux-hardware.org/?probe=11adb16243) | Sep 03, 2020 |
| ASUSTek       | X442UA                      | [cad592ae29](https://linux-hardware.org/?probe=cad592ae29) | Aug 31, 2020 |
| ASUSTek       | X442UA                      | [7697815bb5](https://linux-hardware.org/?probe=7697815bb5) | Aug 31, 2020 |
| HP            | EliteBook 840 G5            | [c020f92165](https://linux-hardware.org/?probe=c020f92165) | Aug 30, 2020 |
| HP            | ProBook 440 G3              | [1e65e31e23](https://linux-hardware.org/?probe=1e65e31e23) | Aug 30, 2020 |
| Samsung       | R430/R480/R440              | [c37003dbfc](https://linux-hardware.org/?probe=c37003dbfc) | Aug 30, 2020 |
| Lenovo        | IdeaPad Z480                | [c1fe24f51b](https://linux-hardware.org/?probe=c1fe24f51b) | Aug 28, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [eb0990afbe](https://linux-hardware.org/?probe=eb0990afbe) | Aug 23, 2020 |
| Lenovo        | IdeaPad Z480                | [f43e5244bc](https://linux-hardware.org/?probe=f43e5244bc) | Aug 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [7b4fcb3693](https://linux-hardware.org/?probe=7b4fcb3693) | Aug 21, 2020 |
| Lenovo        | IdeaPad S540-14IWL 81ND     | [27987ebfb1](https://linux-hardware.org/?probe=27987ebfb1) | Aug 17, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2151fb7ccb](https://linux-hardware.org/?probe=2151fb7ccb) | Aug 15, 2020 |
| Acer          | AOD255                      | [627daa28b5](https://linux-hardware.org/?probe=627daa28b5) | Aug 11, 2020 |
| HP            | Laptop 14-cm1xxx            | [95f6d41901](https://linux-hardware.org/?probe=95f6d41901) | Aug 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [c958c50dad](https://linux-hardware.org/?probe=c958c50dad) | Aug 07, 2020 |
| HP            | ENVY 15                     | [d2fab519a5](https://linux-hardware.org/?probe=d2fab519a5) | Aug 04, 2020 |
| Toshiba       | Satellite L645              | [2f81e753a6](https://linux-hardware.org/?probe=2f81e753a6) | Jul 31, 2020 |
| HP            | 245 G6                      | [eb51696edd](https://linux-hardware.org/?probe=eb51696edd) | Jul 29, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [1b4b43f382](https://linux-hardware.org/?probe=1b4b43f382) | Jul 29, 2020 |
| HP            | G42                         | [80828bd820](https://linux-hardware.org/?probe=80828bd820) | Jul 29, 2020 |
| HP            | Laptop 15-db0xxx            | [0928c9c524](https://linux-hardware.org/?probe=0928c9c524) | Jul 27, 2020 |
| HP            | Compaq CQ45                 | [26022f582b](https://linux-hardware.org/?probe=26022f582b) | Jul 26, 2020 |
| HP            | Compaq CQ45                 | [74cad2f13e](https://linux-hardware.org/?probe=74cad2f13e) | Jul 26, 2020 |
| HP            | Laptop 15-db0xxx            | [75928e5332](https://linux-hardware.org/?probe=75928e5332) | Jul 25, 2020 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b4f52ba1be](https://linux-hardware.org/?probe=b4f52ba1be) | Jul 25, 2020 |
| Lenovo        | IdeaPad Z480                | [17ecc94bc0](https://linux-hardware.org/?probe=17ecc94bc0) | Jul 24, 2020 |
| Toshiba       | Satellite M505              | [518faca568](https://linux-hardware.org/?probe=518faca568) | Jul 21, 2020 |
| Toshiba       | Satellite S75-A             | [a2fc5378af](https://linux-hardware.org/?probe=a2fc5378af) | Jul 21, 2020 |
| Toshiba       | Satellite M505              | [64f79b1c45](https://linux-hardware.org/?probe=64f79b1c45) | Jul 21, 2020 |
| Dell          | Latitude E7270              | [3240f0ae94](https://linux-hardware.org/?probe=3240f0ae94) | Jul 20, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1839ba41d3](https://linux-hardware.org/?probe=1839ba41d3) | Jul 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f179e69271](https://linux-hardware.org/?probe=f179e69271) | Jul 19, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [543185b30a](https://linux-hardware.org/?probe=543185b30a) | Jul 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e66cd74e47](https://linux-hardware.org/?probe=e66cd74e47) | Jul 18, 2020 |
| ASUSTek       | X456UA                      | [0bc503ae0b](https://linux-hardware.org/?probe=0bc503ae0b) | Jul 16, 2020 |
| HP            | Laptop 15-db0xxx            | [8a858d88d0](https://linux-hardware.org/?probe=8a858d88d0) | Jul 15, 2020 |
| HP            | Laptop 15-db0xxx            | [260563b336](https://linux-hardware.org/?probe=260563b336) | Jul 15, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [38242e89d2](https://linux-hardware.org/?probe=38242e89d2) | Jul 12, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [c4e21ddab2](https://linux-hardware.org/?probe=c4e21ddab2) | Jul 12, 2020 |
| ASUSTek       | X456UA                      | [6b61996456](https://linux-hardware.org/?probe=6b61996456) | Jul 12, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [858cd73913](https://linux-hardware.org/?probe=858cd73913) | Jul 11, 2020 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [fc5d45e94a](https://linux-hardware.org/?probe=fc5d45e94a) | Jul 10, 2020 |
| HP            | Compaq 6730s                | [e128a9542c](https://linux-hardware.org/?probe=e128a9542c) | Jul 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [dd5e302721](https://linux-hardware.org/?probe=dd5e302721) | Jul 03, 2020 |
| ASUSTek       | K46CM                       | [5260584205](https://linux-hardware.org/?probe=5260584205) | Jun 30, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [0999108dfb](https://linux-hardware.org/?probe=0999108dfb) | Jun 29, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [aba4b6462f](https://linux-hardware.org/?probe=aba4b6462f) | Jun 27, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [a54dfa2b8b](https://linux-hardware.org/?probe=a54dfa2b8b) | Jun 27, 2020 |
| Dell          | XPS 15 9550                 | [fae71e18b2](https://linux-hardware.org/?probe=fae71e18b2) | Jun 25, 2020 |
| Apple         | MacBookPro5,5               | [7e4c8ea12c](https://linux-hardware.org/?probe=7e4c8ea12c) | Jun 25, 2020 |
| Apple         | MacBookPro5,5               | [5e921d68ff](https://linux-hardware.org/?probe=5e921d68ff) | Jun 25, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [7e8026e797](https://linux-hardware.org/?probe=7e8026e797) | Jun 22, 2020 |
| Toshiba       | PORTEGE Z30-B               | [29f9ac42d8](https://linux-hardware.org/?probe=29f9ac42d8) | Jun 21, 2020 |
| Unknown       | Unknown                     | [73cda410f2](https://linux-hardware.org/?probe=73cda410f2) | Jun 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a7d7f2f4f3](https://linux-hardware.org/?probe=a7d7f2f4f3) | Jun 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d194146ff8](https://linux-hardware.org/?probe=d194146ff8) | Jun 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [5b4fdab686](https://linux-hardware.org/?probe=5b4fdab686) | Jun 18, 2020 |
| Dell          | Inspiron N4010              | [a1ae232e58](https://linux-hardware.org/?probe=a1ae232e58) | Jun 13, 2020 |
| Acer          | Aspire 5532                 | [ce8deb0caa](https://linux-hardware.org/?probe=ce8deb0caa) | Jun 12, 2020 |
| Acer          | Aspire 5532                 | [cc0f65e016](https://linux-hardware.org/?probe=cc0f65e016) | Jun 12, 2020 |
| Gateway       | M-6319                      | [5b3e8b9ef1](https://linux-hardware.org/?probe=5b3e8b9ef1) | Jun 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [52c8b6876e](https://linux-hardware.org/?probe=52c8b6876e) | Jun 08, 2020 |
| ASUSTek       | T100TA                      | [aad1de590c](https://linux-hardware.org/?probe=aad1de590c) | Jun 07, 2020 |
| Acer          | Aspire E1-421               | [81073e838e](https://linux-hardware.org/?probe=81073e838e) | Jun 05, 2020 |
| ASUSTek       | X455LJ                      | [e7901f9d16](https://linux-hardware.org/?probe=e7901f9d16) | Jun 05, 2020 |
| Sony          | VGN-NR310FH                 | [c774d0a51a](https://linux-hardware.org/?probe=c774d0a51a) | Jun 05, 2020 |
| ASUSTek       | X555LJ                      | [9585e46a59](https://linux-hardware.org/?probe=9585e46a59) | Jun 04, 2020 |
| Lenovo        | ThinkPad T430u 86143HU      | [5a3bf0a8f5](https://linux-hardware.org/?probe=5a3bf0a8f5) | Jun 03, 2020 |
| ASUSTek       | X555LJ                      | [d45d40decd](https://linux-hardware.org/?probe=d45d40decd) | Jun 03, 2020 |
| ASUSTek       | K46CM                       | [994e39c619](https://linux-hardware.org/?probe=994e39c619) | Jun 02, 2020 |
| Apple         | MacBook5,1                  | [841614c2d1](https://linux-hardware.org/?probe=841614c2d1) | Jun 01, 2020 |
| Apple         | MacBook5,1                  | [8126e4dea3](https://linux-hardware.org/?probe=8126e4dea3) | Jun 01, 2020 |
| Acer          | Aspire E1-421               | [618908f152](https://linux-hardware.org/?probe=618908f152) | May 27, 2020 |
| ASUSTek       | X411UQ                      | [a3e9e016a6](https://linux-hardware.org/?probe=a3e9e016a6) | May 27, 2020 |
| Lenovo        | ThinkPad A475 20KMS0NG00    | [4572fa1657](https://linux-hardware.org/?probe=4572fa1657) | May 27, 2020 |
| Dell          | Inspiron 5521               | [169492fdd8](https://linux-hardware.org/?probe=169492fdd8) | May 26, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [871784f430](https://linux-hardware.org/?probe=871784f430) | May 26, 2020 |
| HP            | 430                         | [54ba3df0c8](https://linux-hardware.org/?probe=54ba3df0c8) | May 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c4c76cecbd](https://linux-hardware.org/?probe=c4c76cecbd) | May 23, 2020 |
| HP            | Laptop 14-bw0xx             | [c9c485db32](https://linux-hardware.org/?probe=c9c485db32) | May 22, 2020 |
| Sony          | SVF14A15CLB                 | [7fb2e1bda0](https://linux-hardware.org/?probe=7fb2e1bda0) | May 20, 2020 |
| Samsung       | 535U3C                      | [b3983a1b17](https://linux-hardware.org/?probe=b3983a1b17) | May 20, 2020 |
| Dell          | Inspiron 1420               | [1269d54a19](https://linux-hardware.org/?probe=1269d54a19) | May 20, 2020 |
| Dell          | Inspiron N4010              | [fe9c89b85a](https://linux-hardware.org/?probe=fe9c89b85a) | May 17, 2020 |
| Lenovo        | G40-80 80E4                 | [70a6d29aa3](https://linux-hardware.org/?probe=70a6d29aa3) | May 15, 2020 |
| Samsung       | 535U3C                      | [fe2d93033d](https://linux-hardware.org/?probe=fe2d93033d) | May 13, 2020 |
| Lenovo        | V330-14IKB 81B0             | [5ed9a929ec](https://linux-hardware.org/?probe=5ed9a929ec) | May 10, 2020 |
| Sony          | SVE14121CLP                 | [df7e4c2b9f](https://linux-hardware.org/?probe=df7e4c2b9f) | May 09, 2020 |
| Lenovo        | IdeaPad S540-14API 81NH     | [69942e79bd](https://linux-hardware.org/?probe=69942e79bd) | May 02, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | [91627f8ac4](https://linux-hardware.org/?probe=91627f8ac4) | Apr 29, 2020 |
| Toshiba       | Satellite L515              | [c411228b1a](https://linux-hardware.org/?probe=c411228b1a) | Apr 28, 2020 |
| Inspur        | M11JB R2.0/R1.1             | [7f92b47ef4](https://linux-hardware.org/?probe=7f92b47ef4) | Apr 27, 2020 |
| HP            | Pavilion dv6                | [163dac19b3](https://linux-hardware.org/?probe=163dac19b3) | Apr 26, 2020 |
| HP            | Pavilion dv6                | [13cb9e8a90](https://linux-hardware.org/?probe=13cb9e8a90) | Apr 26, 2020 |
| Lenovo        | Z50-70 20354                | [f429ce4848](https://linux-hardware.org/?probe=f429ce4848) | Apr 22, 2020 |
| Dell          | G5 5587                     | [dd4521b554](https://linux-hardware.org/?probe=dd4521b554) | Apr 21, 2020 |
| HP            | Laptop 14-bs0xx             | [e5243ea838](https://linux-hardware.org/?probe=e5243ea838) | Apr 21, 2020 |
| HP            | Pavilion g4                 | [7e9785b653](https://linux-hardware.org/?probe=7e9785b653) | Apr 18, 2020 |
| ASUSTek       | X453SA                      | [ce1bd3affc](https://linux-hardware.org/?probe=ce1bd3affc) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | [d27bf3c005](https://linux-hardware.org/?probe=d27bf3c005) | Apr 18, 2020 |
| HP            | Pavilion g4                 | [3c6a4199c7](https://linux-hardware.org/?probe=3c6a4199c7) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | [5d25f725c9](https://linux-hardware.org/?probe=5d25f725c9) | Apr 18, 2020 |
| ASUSTek       | N46VB                       | [eae7b8a990](https://linux-hardware.org/?probe=eae7b8a990) | Apr 17, 2020 |
| ASUSTek       | N46VB                       | [ab1938abc6](https://linux-hardware.org/?probe=ab1938abc6) | Apr 17, 2020 |
| Acer          | Aspire V5-471               | [6540209d65](https://linux-hardware.org/?probe=6540209d65) | Apr 16, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [010fdcb7ab](https://linux-hardware.org/?probe=010fdcb7ab) | Apr 16, 2020 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [8eae2753ce](https://linux-hardware.org/?probe=8eae2753ce) | Apr 16, 2020 |
| HP            | Laptop 15-db0xxx            | [6ec2d663e5](https://linux-hardware.org/?probe=6ec2d663e5) | Apr 15, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [a4b76d231e](https://linux-hardware.org/?probe=a4b76d231e) | Apr 15, 2020 |
| Acer          | Aspire A515-51              | [cb760929c4](https://linux-hardware.org/?probe=cb760929c4) | Apr 14, 2020 |
| Samsung       | 530U4E/540U4E               | [33747354e3](https://linux-hardware.org/?probe=33747354e3) | Apr 13, 2020 |
| Samsung       | 530U4E/540U4E               | [06fa247c32](https://linux-hardware.org/?probe=06fa247c32) | Apr 13, 2020 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [25e23d0bf7](https://linux-hardware.org/?probe=25e23d0bf7) | Apr 13, 2020 |
| Lenovo        | ThinkPad E460 20ETA05Y00    | [823afb58b0](https://linux-hardware.org/?probe=823afb58b0) | Apr 12, 2020 |
| Lenovo        | ThinkPad E460 20ETA05Y00    | [90b23eb96e](https://linux-hardware.org/?probe=90b23eb96e) | Apr 12, 2020 |
| Dell          | System Inspiron 5420        | [f74d698b46](https://linux-hardware.org/?probe=f74d698b46) | Apr 11, 2020 |
| Toshiba       | Satellite A505              | [f7f3c03ad9](https://linux-hardware.org/?probe=f7f3c03ad9) | Apr 10, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [0248492e22](https://linux-hardware.org/?probe=0248492e22) | Apr 08, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [b19f7181b4](https://linux-hardware.org/?probe=b19f7181b4) | Apr 08, 2020 |
| HP            | Laptop 15-db0xxx            | [c4c866db0d](https://linux-hardware.org/?probe=c4c866db0d) | Apr 04, 2020 |
| HP            | Laptop 15-db0xxx            | [0bb263546b](https://linux-hardware.org/?probe=0bb263546b) | Apr 04, 2020 |
| ASUSTek       | X540YA                      | [2bfdde7714](https://linux-hardware.org/?probe=2bfdde7714) | Apr 03, 2020 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [f9921167fc](https://linux-hardware.org/?probe=f9921167fc) | Apr 02, 2020 |
| HP            | Mini 311-1100               | [d4918f7f3c](https://linux-hardware.org/?probe=d4918f7f3c) | Mar 27, 2020 |
| ASUSTek       | X455LD                      | [ec6c4486ca](https://linux-hardware.org/?probe=ec6c4486ca) | Mar 26, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [60f3879e96](https://linux-hardware.org/?probe=60f3879e96) | Mar 25, 2020 |
| Acer          | Aspire 4750                 | [4757577c86](https://linux-hardware.org/?probe=4757577c86) | Mar 23, 2020 |
| ASUSTek       | K52JT                       | [38330a61d2](https://linux-hardware.org/?probe=38330a61d2) | Mar 23, 2020 |
| Lenovo        | ThinkPad T480 20L6S0VE00    | [4d090cecde](https://linux-hardware.org/?probe=4d090cecde) | Mar 22, 2020 |
| Toshiba       | Satellite C645              | [38d4ca1005](https://linux-hardware.org/?probe=38d4ca1005) | Mar 20, 2020 |
| HP            | Compaq Presario F700        | [912c22a4fd](https://linux-hardware.org/?probe=912c22a4fd) | Mar 20, 2020 |
| HP            | Compaq Presario F700        | [3a11fa91b5](https://linux-hardware.org/?probe=3a11fa91b5) | Mar 20, 2020 |
| HP            | ProBook 440 G6              | [d42c9c08ee](https://linux-hardware.org/?probe=d42c9c08ee) | Mar 19, 2020 |
| Apple         | MacBookPro8,3               | [1279383fb8](https://linux-hardware.org/?probe=1279383fb8) | Mar 17, 2020 |
| ASUSTek       | X505BP                      | [11da78a649](https://linux-hardware.org/?probe=11da78a649) | Mar 16, 2020 |
| Google        | Pantheon                    | [20acb09771](https://linux-hardware.org/?probe=20acb09771) | Mar 09, 2020 |
| Sony          | VGN-SR51MF_S                | [8783bf4fe5](https://linux-hardware.org/?probe=8783bf4fe5) | Mar 09, 2020 |
| HP            | Laptop 15-db0xxx            | [def3aa7871](https://linux-hardware.org/?probe=def3aa7871) | Mar 07, 2020 |
| ASUSTek       | X555QG                      | [6dccf0159e](https://linux-hardware.org/?probe=6dccf0159e) | Mar 07, 2020 |
| ASUSTek       | X555QG                      | [6ec6d9847c](https://linux-hardware.org/?probe=6ec6d9847c) | Mar 07, 2020 |
| ASUSTek       | X555QG                      | [e5c1b0bdce](https://linux-hardware.org/?probe=e5c1b0bdce) | Mar 07, 2020 |
| Lenovo        | IdeaPad Z470                | [20a4bdc803](https://linux-hardware.org/?probe=20a4bdc803) | Mar 05, 2020 |
| Lenovo        | IdeaPad Z470                | [b4898d9e36](https://linux-hardware.org/?probe=b4898d9e36) | Mar 05, 2020 |
| ASUSTek       | X505BP                      | [88ec1bf424](https://linux-hardware.org/?probe=88ec1bf424) | Feb 29, 2020 |
| Toshiba       | Satellite L305              | [fd8dfe766e](https://linux-hardware.org/?probe=fd8dfe766e) | Feb 24, 2020 |
| Toshiba       | Satellite L305              | [96c28903af](https://linux-hardware.org/?probe=96c28903af) | Feb 24, 2020 |
| HP            | Pavilion 10 TS              | [1ee504b68f](https://linux-hardware.org/?probe=1ee504b68f) | Feb 24, 2020 |
| ASUSTek       | TUF Gaming FX504GE_FX80G... | [c74cb1d856](https://linux-hardware.org/?probe=c74cb1d856) | Feb 22, 2020 |
| HP            | Laptop 14-bp0xx             | [303f2ada85](https://linux-hardware.org/?probe=303f2ada85) | Feb 19, 2020 |
| Lenovo        | ThinkPad SL500 27468XU      | [968045d52d](https://linux-hardware.org/?probe=968045d52d) | Feb 19, 2020 |
| HP            | Pavilion 10 TS              | [ed95aa0537](https://linux-hardware.org/?probe=ed95aa0537) | Feb 16, 2020 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | [d0276ea845](https://linux-hardware.org/?probe=d0276ea845) | Feb 14, 2020 |
| Acer          | Aspire A315-51              | [1d69448de6](https://linux-hardware.org/?probe=1d69448de6) | Feb 09, 2020 |
| Acer          | Aspire A315-51              | [6d4ecdb510](https://linux-hardware.org/?probe=6d4ecdb510) | Feb 09, 2020 |
| Lenovo        | ThinkPad SL500 27468XU      | [30b395a14f](https://linux-hardware.org/?probe=30b395a14f) | Feb 08, 2020 |
| Dell          | Vostro 3400                 | [7ad384214e](https://linux-hardware.org/?probe=7ad384214e) | Feb 06, 2020 |
| Apple         | MacBookPro11,1              | [b3a11d5f5d](https://linux-hardware.org/?probe=b3a11d5f5d) | Jan 20, 2020 |
| Unknown       | Unknown                     | [25f6d11655](https://linux-hardware.org/?probe=25f6d11655) | Jan 11, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [94b406a65f](https://linux-hardware.org/?probe=94b406a65f) | Jan 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [cf5b83db0d](https://linux-hardware.org/?probe=cf5b83db0d) | Jan 08, 2020 |
| ASUSTek       | X550ZE                      | [e06f76becf](https://linux-hardware.org/?probe=e06f76becf) | Jan 08, 2020 |
| HP            | Laptop 14-bp0xx             | [30389049c2](https://linux-hardware.org/?probe=30389049c2) | Jan 07, 2020 |
| ASUSTek       | X555YI                      | [06421a5c44](https://linux-hardware.org/?probe=06421a5c44) | Jan 05, 2020 |
| HP            | Laptop 15-db0xxx            | [db9c0c83ce](https://linux-hardware.org/?probe=db9c0c83ce) | Jan 03, 2020 |
| HP            | Laptop 14-bs0xx             | [854604bdad](https://linux-hardware.org/?probe=854604bdad) | Dec 31, 2019 |
| Dell          | Inspiron 5423               | [ed50d52b54](https://linux-hardware.org/?probe=ed50d52b54) | Dec 28, 2019 |
| Dell          | Inspiron 5423               | [5b5632e40c](https://linux-hardware.org/?probe=5b5632e40c) | Dec 28, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [b6846dfd95](https://linux-hardware.org/?probe=b6846dfd95) | Dec 28, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [75a94cfe2f](https://linux-hardware.org/?probe=75a94cfe2f) | Dec 28, 2019 |
| Dell          | Inspiron 5748               | [17ed1f4194](https://linux-hardware.org/?probe=17ed1f4194) | Dec 22, 2019 |
| HP            | Laptop 14-bp0xx             | [c99b71d804](https://linux-hardware.org/?probe=c99b71d804) | Dec 18, 2019 |
| Lenovo        | G40-45 80E1                 | [b1f6e07d2b](https://linux-hardware.org/?probe=b1f6e07d2b) | Dec 09, 2019 |
| HP            | Pavilion 10 TS              | [fbe754b72c](https://linux-hardware.org/?probe=fbe754b72c) | Nov 29, 2019 |
| Lenovo        | Flex 2-14D 20376            | [d78bbdfa2a](https://linux-hardware.org/?probe=d78bbdfa2a) | Nov 18, 2019 |
| Lenovo        | Flex 2-14D 20376            | [7e957006e4](https://linux-hardware.org/?probe=7e957006e4) | Nov 18, 2019 |
| HP            | Laptop 15-da0xxx            | [cb6e592c0d](https://linux-hardware.org/?probe=cb6e592c0d) | Nov 18, 2019 |
| ASUSTek       | 1005HA                      | [bd953e0701](https://linux-hardware.org/?probe=bd953e0701) | Nov 17, 2019 |
| ASUSTek       | X550DP                      | [9515caaefa](https://linux-hardware.org/?probe=9515caaefa) | Nov 17, 2019 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | [4e2ba6330f](https://linux-hardware.org/?probe=4e2ba6330f) | Nov 09, 2019 |
| Lenovo        | ThinkPad E460 20EUA00900    | [a549aed5b4](https://linux-hardware.org/?probe=a549aed5b4) | Nov 08, 2019 |
| HP            | Laptop 14-bs0xx             | [36570780b5](https://linux-hardware.org/?probe=36570780b5) | Oct 30, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [5d4e6e95f1](https://linux-hardware.org/?probe=5d4e6e95f1) | Oct 30, 2019 |
| Dell          | XPS 15 9550                 | [7323abf391](https://linux-hardware.org/?probe=7323abf391) | Oct 29, 2019 |
| HP            | Laptop 14-bs0xx             | [4270a9638b](https://linux-hardware.org/?probe=4270a9638b) | Oct 29, 2019 |
| Dell          | XPS 15 9550                 | [c70f66f439](https://linux-hardware.org/?probe=c70f66f439) | Oct 29, 2019 |
| HP            | Laptop 15-db0xxx            | [666b6342e0](https://linux-hardware.org/?probe=666b6342e0) | Oct 29, 2019 |
| HP            | Laptop 15-db0xxx            | [36c76546e9](https://linux-hardware.org/?probe=36c76546e9) | Oct 29, 2019 |
| Lenovo        | IdeaPad 330S-14AST 81F8     | [3469bcd886](https://linux-hardware.org/?probe=3469bcd886) | Oct 28, 2019 |
| HP            | Laptop 14-bp0xx             | [2e6a129f3e](https://linux-hardware.org/?probe=2e6a129f3e) | Oct 24, 2019 |
| VIT           | P2412                       | [2604d0b890](https://linux-hardware.org/?probe=2604d0b890) | Oct 15, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [6206eb1a2f](https://linux-hardware.org/?probe=6206eb1a2f) | Oct 11, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [9a54660b4f](https://linux-hardware.org/?probe=9a54660b4f) | Oct 11, 2019 |
| Toshiba       | NB 105                      | [07f2ac3953](https://linux-hardware.org/?probe=07f2ac3953) | Oct 08, 2019 |
| Toshiba       | NB 105                      | [56d1fb0551](https://linux-hardware.org/?probe=56d1fb0551) | Oct 08, 2019 |
| ASUSTek       | X505BP                      | [147a0012a9](https://linux-hardware.org/?probe=147a0012a9) | Oct 08, 2019 |
| HP            | Pavilion 10 TS              | [f1d915aa56](https://linux-hardware.org/?probe=f1d915aa56) | Oct 06, 2019 |
| Acer          | Aspire E3-111               | [cb12dc0dcd](https://linux-hardware.org/?probe=cb12dc0dcd) | Sep 18, 2019 |
| Chuwi         | LapBook Plus                | [2cc2dc7812](https://linux-hardware.org/?probe=2cc2dc7812) | Sep 15, 2019 |
| Samsung       | 535U3C                      | [3605b4bcc2](https://linux-hardware.org/?probe=3605b4bcc2) | Sep 15, 2019 |
| Fujitsu       | LIFEBOOK T734               | [38a59cafac](https://linux-hardware.org/?probe=38a59cafac) | Sep 07, 2019 |
| Acer          | Aspire E1-571               | [f7809cd921](https://linux-hardware.org/?probe=f7809cd921) | Sep 06, 2019 |
| HP            | 240 G4 Notebook PC          | [c29c743021](https://linux-hardware.org/?probe=c29c743021) | Sep 06, 2019 |
| HP            | Laptop 15-db0xxx            | [47661b90c1](https://linux-hardware.org/?probe=47661b90c1) | Aug 31, 2019 |
| HP            | Laptop 14-ck0xxx            | [e4ca853a88](https://linux-hardware.org/?probe=e4ca853a88) | Aug 30, 2019 |
| HP            | Laptop 14-ck0xxx            | [ebb5e97cc6](https://linux-hardware.org/?probe=ebb5e97cc6) | Aug 30, 2019 |
| Samsung       | 535U3C                      | [05752face4](https://linux-hardware.org/?probe=05752face4) | Aug 29, 2019 |
| Lenovo        | G40-80 80E4                 | [386e041ee1](https://linux-hardware.org/?probe=386e041ee1) | Aug 27, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [934edb8a8d](https://linux-hardware.org/?probe=934edb8a8d) | Aug 19, 2019 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [d9d655f7eb](https://linux-hardware.org/?probe=d9d655f7eb) | Aug 19, 2019 |
| Lenovo        | IdeaPad S340-14API 81NB     | [c3f8c454d5](https://linux-hardware.org/?probe=c3f8c454d5) | Aug 17, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [60d6ad276f](https://linux-hardware.org/?probe=60d6ad276f) | Aug 16, 2019 |
| HP            | Laptop 15-db0xxx            | [9b10892d1f](https://linux-hardware.org/?probe=9b10892d1f) | Aug 12, 2019 |
| HP            | 240 G4 Notebook PC          | [8abebd7b2f](https://linux-hardware.org/?probe=8abebd7b2f) | Jul 31, 2019 |
| ASUSTek       | G73Jw                       | [34c2f4a1e6](https://linux-hardware.org/?probe=34c2f4a1e6) | Jul 31, 2019 |
| Acer          | Aspire V3-471               | [6e533b7623](https://linux-hardware.org/?probe=6e533b7623) | Jul 29, 2019 |
| Lenovo        | ThinkPad T440s 20AQ006HU... | [7637f3de5f](https://linux-hardware.org/?probe=7637f3de5f) | Jul 28, 2019 |
| Acer          | Aspire 4750                 | [481b67d08f](https://linux-hardware.org/?probe=481b67d08f) | Jul 22, 2019 |
| HP            | Pavilion tx1000             | [4a6a073320](https://linux-hardware.org/?probe=4a6a073320) | Jul 22, 2019 |
| Acer          | Aspire 4750                 | [bf530b04c7](https://linux-hardware.org/?probe=bf530b04c7) | Jul 22, 2019 |
| HP            | Presario CQ43               | [4201cdd966](https://linux-hardware.org/?probe=4201cdd966) | Jul 20, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [ca74df306b](https://linux-hardware.org/?probe=ca74df306b) | Jul 14, 2019 |
| HP            | Pavilion Laptop 15-cd0xx    | [c75d45bec4](https://linux-hardware.org/?probe=c75d45bec4) | Jul 14, 2019 |
| HP            | Laptop 14-ck0xxx            | [05497b6d61](https://linux-hardware.org/?probe=05497b6d61) | Jul 12, 2019 |
| HP            | Laptop 14-bs0xx             | [7a8cfa539b](https://linux-hardware.org/?probe=7a8cfa539b) | Jun 23, 2019 |
| HP            | ProBook 440 G2              | [592064f97e](https://linux-hardware.org/?probe=592064f97e) | Jun 23, 2019 |
| ASUSTek       | X542URR                     | [adf12d067f](https://linux-hardware.org/?probe=adf12d067f) | Jun 19, 2019 |
| Samsung       | 300E4C/300E5C/300E7C        | [3cecb13c13](https://linux-hardware.org/?probe=3cecb13c13) | Jun 18, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [af291d02cf](https://linux-hardware.org/?probe=af291d02cf) | Jun 17, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [7061046667](https://linux-hardware.org/?probe=7061046667) | Jun 15, 2019 |
| HP            | Pavilion dm1                | [01e9de8250](https://linux-hardware.org/?probe=01e9de8250) | Jun 13, 2019 |
| HP            | Pavilion dm1                | [40f5482a9d](https://linux-hardware.org/?probe=40f5482a9d) | Jun 13, 2019 |
| HP            | Laptop 15-db0xxx            | [f69654fec4](https://linux-hardware.org/?probe=f69654fec4) | Jun 13, 2019 |
| ASUSTek       | X455LAB                     | [6fc7fb8c0e](https://linux-hardware.org/?probe=6fc7fb8c0e) | Jun 12, 2019 |
| ASUSTek       | X455LAB                     | [a8004d007d](https://linux-hardware.org/?probe=a8004d007d) | Jun 12, 2019 |
| HP            | Laptop 15-db0xxx            | [cb1771b144](https://linux-hardware.org/?probe=cb1771b144) | Jun 12, 2019 |
| HP            | Laptop 15-db0xxx            | [ca315cb07b](https://linux-hardware.org/?probe=ca315cb07b) | Jun 12, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [5e80fdb647](https://linux-hardware.org/?probe=5e80fdb647) | Jun 11, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [8eaae370e1](https://linux-hardware.org/?probe=8eaae370e1) | Jun 10, 2019 |
| ASUSTek       | X450CC                      | [9604bdacb2](https://linux-hardware.org/?probe=9604bdacb2) | Jun 10, 2019 |
| Lenovo        | IdeaPadFlex 14 20308        | [23bd541bf1](https://linux-hardware.org/?probe=23bd541bf1) | Jun 10, 2019 |
| Dell          | Inspiron 1420               | [09ca7997ac](https://linux-hardware.org/?probe=09ca7997ac) | Jun 09, 2019 |
| HP            | Pavilion tx1000             | [a783eb7140](https://linux-hardware.org/?probe=a783eb7140) | Jun 08, 2019 |
| HP            | Notebook                    | [c428093164](https://linux-hardware.org/?probe=c428093164) | Jun 06, 2019 |
| HP            | EliteBook 840 G3            | [b828ffaace](https://linux-hardware.org/?probe=b828ffaace) | Jun 05, 2019 |
| HP            | ENVY 15                     | [f1ee36482d](https://linux-hardware.org/?probe=f1ee36482d) | Jun 03, 2019 |
| HP            | ENVY 15                     | [da05c24e64](https://linux-hardware.org/?probe=da05c24e64) | Jun 03, 2019 |
| HP            | ENVY 15                     | [b450947391](https://linux-hardware.org/?probe=b450947391) | Jun 03, 2019 |
| Acer          | Nitro AN515-52              | [30f1da590b](https://linux-hardware.org/?probe=30f1da590b) | Jun 03, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [e11ecb2f55](https://linux-hardware.org/?probe=e11ecb2f55) | May 26, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [5b282c8861](https://linux-hardware.org/?probe=5b282c8861) | May 26, 2019 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [48cc73875b](https://linux-hardware.org/?probe=48cc73875b) | May 26, 2019 |
| ASUSTek       | X555LN                      | [2022ef16da](https://linux-hardware.org/?probe=2022ef16da) | May 23, 2019 |
| Lenovo        | ThinkPad X230 2325P35       | [d666ba7823](https://linux-hardware.org/?probe=d666ba7823) | May 22, 2019 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [197946e655](https://linux-hardware.org/?probe=197946e655) | May 09, 2019 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [1700077449](https://linux-hardware.org/?probe=1700077449) | May 07, 2019 |
| Lenovo        | ThinkPad E560 20EV002FUS    | [0a5569615d](https://linux-hardware.org/?probe=0a5569615d) | May 07, 2019 |
| Acer          | Aspire E5-575G              | [253b707c92](https://linux-hardware.org/?probe=253b707c92) | May 05, 2019 |
| Toshiba       | NB 105                      | [4662d43a44](https://linux-hardware.org/?probe=4662d43a44) | Apr 29, 2019 |
| Toshiba       | NB 105                      | [65ef86cd1c](https://linux-hardware.org/?probe=65ef86cd1c) | Apr 29, 2019 |
| ASUSTek       | X705UDR                     | [32a2339838](https://linux-hardware.org/?probe=32a2339838) | Apr 27, 2019 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [a6a1ecf366](https://linux-hardware.org/?probe=a6a1ecf366) | Apr 24, 2019 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [b34ded162f](https://linux-hardware.org/?probe=b34ded162f) | Apr 22, 2019 |
| ASUSTek       | G73Jw                       | [2626377d36](https://linux-hardware.org/?probe=2626377d36) | Apr 20, 2019 |
| Apple         | MacBookAir6,2               | [a6dd71fdd3](https://linux-hardware.org/?probe=a6dd71fdd3) | Apr 19, 2019 |
| Lenovo        | ThinkPad T450 20BUS1S81F    | [c488c71bcd](https://linux-hardware.org/?probe=c488c71bcd) | Apr 17, 2019 |
| Lenovo        | ThinkPad T450 20BUS1S81F    | [f5fc1d9048](https://linux-hardware.org/?probe=f5fc1d9048) | Apr 17, 2019 |
| PCSMART       | AIRNOTE                     | [8ccaad6ff9](https://linux-hardware.org/?probe=8ccaad6ff9) | Apr 16, 2019 |
| PCSMART       | AIRNOTE                     | [fd6c64b14c](https://linux-hardware.org/?probe=fd6c64b14c) | Apr 16, 2019 |
| Acer          | Aspire A515-51              | [b1b58b7d6b](https://linux-hardware.org/?probe=b1b58b7d6b) | Apr 16, 2019 |
| ASUSTek       | X505BP                      | [dcaf818df8](https://linux-hardware.org/?probe=dcaf818df8) | Apr 16, 2019 |
| Fujitsu       | LIFEBOOK T734               | [06582bdb98](https://linux-hardware.org/?probe=06582bdb98) | Apr 13, 2019 |
| HP            | Laptop 14-bs0xx             | [73f15e5986](https://linux-hardware.org/?probe=73f15e5986) | Apr 12, 2019 |
| ASUSTek       | N56JRH                      | [5764250d85](https://linux-hardware.org/?probe=5764250d85) | Apr 03, 2019 |
| HP            | Pavilion Notebook           | [53fb4de336](https://linux-hardware.org/?probe=53fb4de336) | Mar 27, 2019 |
| HP            | Pavilion Notebook           | [9a4cbb7444](https://linux-hardware.org/?probe=9a4cbb7444) | Mar 27, 2019 |
| ASUSTek       | TAICHI21                    | [ceedb83caa](https://linux-hardware.org/?probe=ceedb83caa) | Mar 25, 2019 |
| HP            | 14                          | [3532a15338](https://linux-hardware.org/?probe=3532a15338) | Mar 19, 2019 |
| Sony          | SVE14A27CXH                 | [f8e75b8eca](https://linux-hardware.org/?probe=f8e75b8eca) | Mar 17, 2019 |
| Acer          | Aspire E3-111               | [e11f7a05d2](https://linux-hardware.org/?probe=e11f7a05d2) | Mar 14, 2019 |
| ASUSTek       | TAICHI21                    | [a90d891180](https://linux-hardware.org/?probe=a90d891180) | Mar 07, 2019 |
| ASUSTek       | X541NA                      | [4fb49f65ef](https://linux-hardware.org/?probe=4fb49f65ef) | Feb 28, 2019 |
| HP            | Laptop 15-da0xxx            | [e1e477a44d](https://linux-hardware.org/?probe=e1e477a44d) | Jan 24, 2019 |
| Dell          | Inspiron 5423               | [0ae4be99f8](https://linux-hardware.org/?probe=0ae4be99f8) | Jan 23, 2019 |
| Dell          | Inspiron 5423               | [0f80a72955](https://linux-hardware.org/?probe=0f80a72955) | Jan 23, 2019 |
| HP            | Laptop 15-da0xxx            | [2ec93c29be](https://linux-hardware.org/?probe=2ec93c29be) | Jan 08, 2019 |
| HP            | 245 G6                      | [feeb8ea6f8](https://linux-hardware.org/?probe=feeb8ea6f8) | Jan 03, 2019 |
| ASUSTek       | X505BP                      | [7f4192344e](https://linux-hardware.org/?probe=7f4192344e) | Dec 29, 2018 |
| ASUSTek       | X505BP                      | [0999f0abc7](https://linux-hardware.org/?probe=0999f0abc7) | Dec 29, 2018 |
| HP            | 245 G6                      | [4289ff0916](https://linux-hardware.org/?probe=4289ff0916) | Dec 28, 2018 |
| HP            | 14                          | [0fe4f88e5a](https://linux-hardware.org/?probe=0fe4f88e5a) | Dec 19, 2018 |
| Acer          | Aspire ES1-572              | [d6d801ec2b](https://linux-hardware.org/?probe=d6d801ec2b) | Dec 19, 2018 |
| Acer          | Aspire ES1-572              | [002ca9c182](https://linux-hardware.org/?probe=002ca9c182) | Dec 19, 2018 |
| ASUSTek       | X505BP                      | [1388526b7f](https://linux-hardware.org/?probe=1388526b7f) | Dec 17, 2018 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | [57ba3702e3](https://linux-hardware.org/?probe=57ba3702e3) | Dec 11, 2018 |
| Dell          | Latitude D620               | [81774e2415](https://linux-hardware.org/?probe=81774e2415) | Dec 07, 2018 |
| Acer          | Unknown                     | [02419cd635](https://linux-hardware.org/?probe=02419cd635) | Dec 03, 2018 |
| Samsung       | N148P                       | [629403b78b](https://linux-hardware.org/?probe=629403b78b) | Nov 25, 2018 |
| Acer          | Unknown                     | [e25ca67959](https://linux-hardware.org/?probe=e25ca67959) | Nov 20, 2018 |
| Acer          | Unknown                     | [f5a1c21578](https://linux-hardware.org/?probe=f5a1c21578) | Nov 18, 2018 |
| HP            | 1000                        | [e8425d849b](https://linux-hardware.org/?probe=e8425d849b) | Nov 10, 2018 |
| Toshiba       | Satellite C675D             | [aa4071d1df](https://linux-hardware.org/?probe=aa4071d1df) | Nov 05, 2018 |
| ASUSTek       | X542URR                     | [a5e2816233](https://linux-hardware.org/?probe=a5e2816233) | Nov 03, 2018 |
| ASUSTek       | X542URR                     | [2a42f7d935](https://linux-hardware.org/?probe=2a42f7d935) | Nov 03, 2018 |
| Acer          | Aspire 4736Z                | [0d5e0790a7](https://linux-hardware.org/?probe=0d5e0790a7) | Oct 30, 2018 |
| Acer          | Aspire 4736Z                | [17113b9ae5](https://linux-hardware.org/?probe=17113b9ae5) | Oct 30, 2018 |
| ASUSTek       | X505BP                      | [09546ff0fe](https://linux-hardware.org/?probe=09546ff0fe) | Oct 29, 2018 |
| ASUSTek       | X505BP                      | [24dffba93d](https://linux-hardware.org/?probe=24dffba93d) | Oct 29, 2018 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [890de967ad](https://linux-hardware.org/?probe=890de967ad) | Oct 26, 2018 |
| HP            | Pavilion 14                 | [a708531868](https://linux-hardware.org/?probe=a708531868) | Oct 25, 2018 |
| HP            | Pavilion 14                 | [dcd47dff54](https://linux-hardware.org/?probe=dcd47dff54) | Oct 25, 2018 |
| Toshiba       | Satellite C655              | [b158836f6e](https://linux-hardware.org/?probe=b158836f6e) | Oct 23, 2018 |
| Toshiba       | Satellite C655              | [347c50681c](https://linux-hardware.org/?probe=347c50681c) | Oct 23, 2018 |
| ASUSTek       | X455LD                      | [6224197a75](https://linux-hardware.org/?probe=6224197a75) | Oct 12, 2018 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [9f2347db71](https://linux-hardware.org/?probe=9f2347db71) | Oct 09, 2018 |
| ASUSTek       | G550JK                      | [af5510f93b](https://linux-hardware.org/?probe=af5510f93b) | Jun 19, 2018 |
| HP            | 14                          | [13f12e2f48](https://linux-hardware.org/?probe=13f12e2f48) | May 23, 2018 |
| HP            | Compaq Presario CQ45        | [762d293955](https://linux-hardware.org/?probe=762d293955) | May 12, 2018 |
| Acer          | Aspire 4739                 | [31eeafc656](https://linux-hardware.org/?probe=31eeafc656) | Jan 04, 2018 |
| Lenovo        | G40-80 80E4                 | [1855d90774](https://linux-hardware.org/?probe=1855d90774) | Dec 19, 2017 |
| Acer          | Aspire 4739                 | [dc6c363798](https://linux-hardware.org/?probe=dc6c363798) | Oct 02, 2017 |
| HP            | Compaq Presario CQ45        | [5c6365ef1a](https://linux-hardware.org/?probe=5c6365ef1a) | Jul 21, 2017 |
| HP            | Compaq Presario CQ45        | [909a456d4f](https://linux-hardware.org/?probe=909a456d4f) | Apr 21, 2017 |
| HP            | Compaq Presario CQ45        | [6571151136](https://linux-hardware.org/?probe=6571151136) | Apr 21, 2017 |
| HP            | Compaq Presario CQ45        | [dc632cca26](https://linux-hardware.org/?probe=dc632cca26) | Mar 18, 2017 |
| HP            | Compaq Presario CQ45        | [c8bbfe9037](https://linux-hardware.org/?probe=c8bbfe9037) | Jan 04, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Colombia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 79        | 14.34%  |
| Ubuntu 18.04       | 65        | 11.8%   |
| OpenMandriva 4.3   | 23        | 4.17%   |
| Ubuntu 22.04       | 11        | 2%      |
| Ubuntu 19.04       | 11        | 2%      |
| Debian 11          | 11        | 2%      |
| OpenMandriva 4.2   | 10        | 1.81%   |
| KDE neon 20.04     | 10        | 1.81%   |
| Arch               | 10        | 1.81%   |
| Manjaro            | 8         | 1.45%   |
| Fedora 34          | 8         | 1.45%   |
| Arch Rolling       | 8         | 1.45%   |
| Zorin 15           | 7         | 1.27%   |
| Ubuntu 20.10       | 7         | 1.27%   |
| Ubuntu 19.10       | 7         | 1.27%   |
| ROSA R10           | 7         | 1.27%   |
| Linux Mint 20.3    | 7         | 1.27%   |
| Linux Mint 20.1    | 7         | 1.27%   |
| Linux Mint 19.3    | 7         | 1.27%   |
| Zorin 16           | 6         | 1.09%   |
| Pop!_OS 22.04      | 6         | 1.09%   |
| Pop!_OS 20.04      | 6         | 1.09%   |
| Ubuntu 21.04       | 5         | 0.91%   |
| Linux Mint 20.2    | 5         | 0.91%   |
| Linux Mint 20      | 5         | 0.91%   |
| Kubuntu 20.04      | 5         | 0.91%   |
| Fedora 36          | 5         | 0.91%   |
| Fedora 33          | 5         | 0.91%   |
| Debian 10          | 5         | 0.91%   |
| Ubuntu 18.10       | 4         | 0.73%   |
| Linux Mint 19.2    | 4         | 0.73%   |
| Fedora 35          | 4         | 0.73%   |
| Fedora 31          | 4         | 0.73%   |
| Endless 3.8.3      | 4         | 0.73%   |
| Xubuntu 20.04      | 3         | 0.54%   |
| Xubuntu 18.04      | 3         | 0.54%   |
| Ubuntu Unity 16.04 | 3         | 0.54%   |
| Ubuntu 16.04       | 3         | 0.54%   |
| Pop!_OS 21.10      | 3         | 0.54%   |
| Pop!_OS 20.10      | 3         | 0.54%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 187       | 35.82%  |
| Endless       | 57        | 10.92%  |
| Linux Mint    | 39        | 7.47%   |
| OpenMandriva  | 33        | 6.32%   |
| Fedora        | 27        | 5.17%   |
| Manjaro       | 20        | 3.83%   |
| Pop!_OS       | 19        | 3.64%   |
| Debian        | 19        | 3.64%   |
| Arch          | 18        | 3.45%   |
| ROSA          | 14        | 2.68%   |
| Zorin         | 13        | 2.49%   |
| KDE neon      | 12        | 2.3%    |
| Kubuntu       | 9         | 1.72%   |
| Xubuntu       | 8         | 1.53%   |
| Kali          | 7         | 1.34%   |
| Elementary    | 5         | 0.96%   |
| Ubuntu Unity  | 4         | 0.77%   |
| Lubuntu       | 3         | 0.57%   |
| Clear Linux   | 3         | 0.57%   |
| ArcoLinux     | 3         | 0.57%   |
| Ubuntu Budgie | 2         | 0.38%   |
| openSUSE      | 2         | 0.38%   |
| MX            | 2         | 0.38%   |
| Garuda Linux  | 2         | 0.38%   |
| EndeavourOS   | 2         | 0.38%   |
| UbuntuDDE     | 1         | 0.19%   |
| Ubuntu MATE   | 1         | 0.19%   |
| RHEL          | 1         | 0.19%   |
| Parrot        | 1         | 0.19%   |
| Nobara        | 1         | 0.19%   |
| NixOS         | 1         | 0.19%   |
| Mageia        | 1         | 0.19%   |
| LinuxFX       | 1         | 0.19%   |
| Linux Lite    | 1         | 0.19%   |
| Deepin        | 1         | 0.19%   |
| CentOS        | 1         | 0.19%   |
| ALT Linux     | 1         | 0.19%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003         | 23        | 3.94%   |
| 5.4.0-42-generic                | 19        | 3.25%   |
| 5.8.0-14-generic                | 12        | 2.05%   |
| 5.4.0-19-generic                | 11        | 1.88%   |
| 5.4.0-58-generic                | 10        | 1.71%   |
| 5.10.14-desktop-1omv4002        | 10        | 1.71%   |
| 5.3.0-46-generic                | 7         | 1.2%    |
| 5.3.0-28-generic                | 6         | 1.03%   |
| 4.18.0-25-generic               | 6         | 1.03%   |
| 4.18.0-15-generic               | 6         | 1.03%   |
| 5.8.0-43-generic                | 5         | 0.86%   |
| 5.4.0-48-generic                | 5         | 0.86%   |
| 5.4.0-31-generic                | 5         | 0.86%   |
| 5.3.0-40-generic                | 5         | 0.86%   |
| 5.13.0-40-generic               | 5         | 0.86%   |
| 5.0.0-37-generic                | 5         | 0.86%   |
| 5.0.0-25-generic                | 5         | 0.86%   |
| 5.8.0-59-generic                | 4         | 0.68%   |
| 5.8.0-44-generic                | 4         | 0.68%   |
| 5.4.0-65-generic                | 4         | 0.68%   |
| 5.4.0-64-generic                | 4         | 0.68%   |
| 5.4.0-54-generic                | 4         | 0.68%   |
| 5.4.0-37-generic                | 4         | 0.68%   |
| 5.4.0-26-generic                | 4         | 0.68%   |
| 5.15.0-47-generic               | 4         | 0.68%   |
| 5.15.0-46-generic               | 4         | 0.68%   |
| 5.13.0-30-generic               | 4         | 0.68%   |
| 5.11.0-40-generic               | 4         | 0.68%   |
| 5.11.0-27-generic               | 4         | 0.68%   |
| 5.0.0-15-generic                | 4         | 0.68%   |
| 5.0.0-13-generic                | 4         | 0.68%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 4         | 0.68%   |
| 5.4.0-70-generic                | 3         | 0.51%   |
| 5.4.0-59-generic                | 3         | 0.51%   |
| 5.4.0-47-generic                | 3         | 0.51%   |
| 5.4.0-33-generic                | 3         | 0.51%   |
| 5.4.0-107-generic               | 3         | 0.51%   |
| 5.11.0-38-generic               | 3         | 0.51%   |
| 5.11.0-34-generic               | 3         | 0.51%   |
| 5.11.0-25-generic               | 3         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 113       | 20%     |
| 4.15.0  | 42        | 7.43%   |
| 5.8.0   | 41        | 7.26%   |
| 5.3.0   | 39        | 6.9%    |
| 5.0.0   | 33        | 5.84%   |
| 5.11.0  | 28        | 4.96%   |
| 5.13.0  | 26        | 4.6%    |
| 4.18.0  | 26        | 4.6%    |
| 5.16.7  | 23        | 4.07%   |
| 5.15.0  | 19        | 3.36%   |
| 5.10.0  | 12        | 2.12%   |
| 5.10.14 | 10        | 1.77%   |
| 4.9.60  | 5         | 0.88%   |
| 4.19.0  | 5         | 0.88%   |
| 4.13.0  | 4         | 0.71%   |
| 5.9.16  | 3         | 0.53%   |
| 5.18.10 | 3         | 0.53%   |
| 5.14.0  | 3         | 0.53%   |
| 5.1.0   | 3         | 0.53%   |
| 4.9.0   | 3         | 0.53%   |
| 4.4.0   | 3         | 0.53%   |
| 5.9.1   | 2         | 0.35%   |
| 5.7.19  | 2         | 0.35%   |
| 5.6.0   | 2         | 0.35%   |
| 5.4.32  | 2         | 0.35%   |
| 5.19.9  | 2         | 0.35%   |
| 5.19.4  | 2         | 0.35%   |
| 5.18.3  | 2         | 0.35%   |
| 5.17.5  | 2         | 0.35%   |
| 5.17.3  | 2         | 0.35%   |
| 5.17.15 | 2         | 0.35%   |
| 5.15.7  | 2         | 0.35%   |
| 5.15.28 | 2         | 0.35%   |
| 5.13.5  | 2         | 0.35%   |
| 5.13.4  | 2         | 0.35%   |
| 5.11.11 | 2         | 0.35%   |
| 5.10.74 | 2         | 0.35%   |
| 4.9.20  | 2         | 0.35%   |
| 5.9.6   | 1         | 0.18%   |
| 5.9.14  | 1         | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 116       | 20.75%  |
| 5.8     | 45        | 8.05%   |
| 5.3     | 43        | 7.69%   |
| 4.15    | 42        | 7.51%   |
| 5.13    | 35        | 6.26%   |
| 5.10    | 35        | 6.26%   |
| 5.0     | 34        | 6.08%   |
| 5.11    | 33        | 5.9%    |
| 5.15    | 29        | 5.19%   |
| 4.18    | 27        | 4.83%   |
| 5.16    | 26        | 4.65%   |
| 4.9     | 12        | 2.15%   |
| 5.6     | 10        | 1.79%   |
| 5.18    | 9         | 1.61%   |
| 5.17    | 9         | 1.61%   |
| 5.9     | 8         | 1.43%   |
| 5.7     | 6         | 1.07%   |
| 4.19    | 6         | 1.07%   |
| 5.19    | 5         | 0.89%   |
| 5.14    | 5         | 0.89%   |
| 5.5     | 4         | 0.72%   |
| 5.12    | 4         | 0.72%   |
| 4.13    | 4         | 0.72%   |
| 5.1     | 3         | 0.54%   |
| 4.4     | 3         | 0.54%   |
| 5.2     | 1         | 0.18%   |
| 4.20    | 1         | 0.18%   |
| 4.14    | 1         | 0.18%   |
| 4.12    | 1         | 0.18%   |
| 4.10    | 1         | 0.18%   |
| 4.1     | 1         | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 497       | 97.45%  |
| i686   | 13        | 2.55%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 248       | 46.97%  |
| Unknown    | 92        | 17.42%  |
| KDE5       | 67        | 12.69%  |
| XFCE       | 39        | 7.39%   |
| X-Cinnamon | 23        | 4.36%   |
| KDE        | 18        | 3.41%   |
| KDE4       | 8         | 1.52%   |
| MATE       | 6         | 1.14%   |
| Pantheon   | 5         | 0.95%   |
| Cinnamon   | 5         | 0.95%   |
| Unity      | 4         | 0.76%   |
| Budgie     | 4         | 0.76%   |
| LXDE       | 2         | 0.38%   |
| Deepin     | 2         | 0.38%   |
| bspwm      | 2         | 0.38%   |
| LXQt       | 1         | 0.19%   |
| ICEWM      | 1         | 0.19%   |
| awesome    | 1         | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 412       | 79.08%  |
| Unknown | 64        | 12.28%  |
| Wayland | 43        | 8.25%   |
| Tty     | 2         | 0.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 318       | 60.57%  |
| SDDM    | 59        | 11.24%  |
| GDM     | 51        | 9.71%   |
| LightDM | 42        | 8%      |
| GDM3    | 32        | 6.1%    |
| TDM     | 14        | 2.67%   |
| KDM     | 8         | 1.52%   |
| LXDM    | 1         | 0.19%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| es_CO   | 233       | 44.3%   |
| en_US   | 134       | 25.48%  |
| Unknown | 99        | 18.82%  |
| es_ES   | 31        | 5.89%   |
| es_MX   | 11        | 2.09%   |
| es_PE   | 3         | 0.57%   |
| en_GB   | 3         | 0.57%   |
| es_EC   | 2         | 0.38%   |
| pt_PT   | 1         | 0.19%   |
| pl_PL   | 1         | 0.19%   |
| it_IT   | 1         | 0.19%   |
| fr_FR   | 1         | 0.19%   |
| es_VE   | 1         | 0.19%   |
| es_CL   | 1         | 0.19%   |
| es_AR   | 1         | 0.19%   |
| en      | 1         | 0.19%   |
| de_DE   | 1         | 0.19%   |
| C       | 1         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 282       | 54.13%  |
| BIOS | 239       | 45.87%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 417       | 79.73%  |
| Unknown | 38        | 7.27%   |
| Overlay | 34        | 6.5%    |
| Btrfs   | 22        | 4.21%   |
| Xfs     | 8         | 1.53%   |
| Zfs     | 1         | 0.19%   |
| Tmpfs   | 1         | 0.19%   |
| F2fs    | 1         | 0.19%   |
| Ext2    | 1         | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 348       | 67.57%  |
| GPT     | 122       | 23.69%  |
| MBR     | 45        | 8.74%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 459       | 88.1%   |
| Yes       | 62        | 11.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 345       | 66.6%   |
| Yes       | 173       | 33.4%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| ASUSTek Computer             | 126       | 24.71%  |
| Hewlett-Packard              | 112       | 21.96%  |
| Lenovo                       | 92        | 18.04%  |
| Dell                         | 47        | 9.22%   |
| Acer                         | 46        | 9.02%   |
| Toshiba                      | 21        | 4.12%   |
| Samsung Electronics          | 12        | 2.35%   |
| Sony                         | 9         | 1.76%   |
| MSI                          | 9         | 1.76%   |
| Apple                        | 9         | 1.76%   |
| HUAWEI                       | 6         | 1.18%   |
| Unknown                      | 4         | 0.78%   |
| Notebook                     | 2         | 0.39%   |
| Gateway                      | 2         | 0.39%   |
| VIT                          | 1         | 0.2%    |
| Timi                         | 1         | 0.2%    |
| PCSMART                      | 1         | 0.2%    |
| MPS Mayorista de Colombia SA | 1         | 0.2%    |
| Inspur                       | 1         | 0.2%    |
| GreatWall                    | 1         | 0.2%    |
| Google                       | 1         | 0.2%    |
| Fujitsu Siemens              | 1         | 0.2%    |
| Fujitsu                      | 1         | 0.2%    |
| Framework                    | 1         | 0.2%    |
| Compumax Computer            | 1         | 0.2%    |
| Chuwi                        | 1         | 0.2%    |
| BAKED                        | 1         | 0.2%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| HP Laptop 15-db0xxx                        | 11        | 2.16%   |
| Samsung 300E4C/300E5C/300E7C               | 5         | 0.98%   |
| HP Notebook                                | 5         | 0.98%   |
| HP Laptop 14-bs0xx                         | 5         | 0.98%   |
| ASUS VivoBook_ASUS Laptop X505ZA_X505ZA    | 5         | 0.98%   |
| Unknown                                    | 5         | 0.98%   |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 4         | 0.78%   |
| HP Laptop 14-cm1xxx                        | 4         | 0.78%   |
| HP 245 G6                                  | 4         | 0.78%   |
| HP 14                                      | 4         | 0.78%   |
| Dell XPS 15 9550                           | 4         | 0.78%   |
| ASUS ZenBook UX431DA_UM431DA               | 4         | 0.78%   |
| ASUS X455LJ                                | 4         | 0.78%   |
| ASUS VivoBook_ASUSLaptop X512FB_X512FB     | 4         | 0.78%   |
| Lenovo IdeaPad S340-14API 81NB             | 3         | 0.59%   |
| Lenovo IdeaPad 320-15ABR 80XS              | 3         | 0.59%   |
| Lenovo G40-80 80E4                         | 3         | 0.59%   |
| Lenovo G40-45 80E1                         | 3         | 0.59%   |
| HP ProBook 450 G1                          | 3         | 0.59%   |
| HP Laptop 15-da0xxx                        | 3         | 0.59%   |
| HP ENVY 15                                 | 3         | 0.59%   |
| Dell Vostro 3400                           | 3         | 0.59%   |
| ASUS X555QG                                | 3         | 0.59%   |
| ASUS X505BP                                | 3         | 0.59%   |
| ASUS X455LD                                | 3         | 0.59%   |
| ASUS VivoBook_ASUSLaptop X509DA_M509DA     | 3         | 0.59%   |
| ASUS VivoBook_ASUSLaptop X409DA_M409DA     | 3         | 0.59%   |
| ASUS VivoBook 14_ASUS Laptop X441MA_X441MA | 3         | 0.59%   |
| Acer Aspire E5-575G                        | 3         | 0.59%   |
| Acer Aspire A515-51                        | 3         | 0.59%   |
| Acer Aspire 4750                           | 3         | 0.59%   |
| Toshiba Satellite U505                     | 2         | 0.39%   |
| Toshiba NB 105                             | 2         | 0.39%   |
| Lenovo Y520-15IKBN 80WK                    | 2         | 0.39%   |
| Lenovo V330-14IKB 81B0                     | 2         | 0.39%   |
| Lenovo ThinkPad X13 Gen 1 20UGS2B800       | 2         | 0.39%   |
| Lenovo ThinkBook 13s G2 ITL 20V9           | 2         | 0.39%   |
| Lenovo IdeaPad 330-15ARR 81D2              | 2         | 0.39%   |
| Lenovo IdeaPad 110-14IBR 80T6              | 2         | 0.39%   |
| HUAWEI BOHB-WAX9                           | 2         | 0.39%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| ASUS VivoBook      | 49        | 9.61%   |
| Lenovo IdeaPad     | 34        | 6.67%   |
| Acer Aspire        | 33        | 6.47%   |
| HP Laptop          | 32        | 6.27%   |
| Lenovo ThinkPad    | 30        | 5.88%   |
| HP Pavilion        | 21        | 4.12%   |
| Toshiba Satellite  | 18        | 3.53%   |
| Dell Inspiron      | 17        | 3.33%   |
| HP ProBook         | 16        | 3.14%   |
| Dell Latitude      | 11        | 2.16%   |
| HP Compaq          | 6         | 1.18%   |
| HP 245             | 6         | 1.18%   |
| Dell XPS           | 6         | 1.18%   |
| Dell Vostro        | 6         | 1.18%   |
| ASUS ZenBook       | 6         | 1.18%   |
| Samsung 300E4C     | 5         | 0.98%   |
| HP Notebook        | 5         | 0.98%   |
| HP EliteBook       | 5         | 0.98%   |
| Unknown            | 5         | 0.98%   |
| HP 240             | 4         | 0.78%   |
| HP 14              | 4         | 0.78%   |
| ASUS X455LJ        | 4         | 0.78%   |
| ASUS TUF           | 4         | 0.78%   |
| Lenovo G40-80      | 3         | 0.59%   |
| Lenovo G40-45      | 3         | 0.59%   |
| HP Presario        | 3         | 0.59%   |
| HP ENVY            | 3         | 0.59%   |
| Dell Precision     | 3         | 0.59%   |
| ASUS X555QG        | 3         | 0.59%   |
| ASUS X505BP        | 3         | 0.59%   |
| ASUS X455LD        | 3         | 0.59%   |
| ASUS ROG           | 3         | 0.59%   |
| Acer TravelMate    | 3         | 0.59%   |
| Acer Nitro         | 3         | 0.59%   |
| Toshiba NB         | 2         | 0.39%   |
| MSI PS63           | 2         | 0.39%   |
| MSI GE60           | 2         | 0.39%   |
| Lenovo Yoga        | 2         | 0.39%   |
| Lenovo Y520-15IKBN | 2         | 0.39%   |
| Lenovo V330-14IKB  | 2         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 69        | 13.53%  |
| 2017 | 56        | 10.98%  |
| 2018 | 55        | 10.78%  |
| 2015 | 40        | 7.84%   |
| 2012 | 37        | 7.25%   |
| 2020 | 34        | 6.67%   |
| 2014 | 34        | 6.67%   |
| 2011 | 34        | 6.67%   |
| 2010 | 34        | 6.67%   |
| 2013 | 29        | 5.69%   |
| 2021 | 23        | 4.51%   |
| 2009 | 21        | 4.12%   |
| 2016 | 19        | 3.73%   |
| 2008 | 13        | 2.55%   |
| 2007 | 7         | 1.37%   |
| 2006 | 3         | 0.59%   |
| 2022 | 2         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 510       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 455       | 88.87%  |
| Enabled  | 57        | 11.13%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 509       | 99.8%   |
| Yes  | 1         | 0.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 181       | 35.08%  |
| 3.01-4.0    | 139       | 26.94%  |
| 8.01-16.0   | 88        | 17.05%  |
| 16.01-24.0  | 46        | 8.91%   |
| 1.01-2.0    | 25        | 4.84%   |
| 2.01-3.0    | 16        | 3.1%    |
| 32.01-64.0  | 9         | 1.74%   |
| 24.01-32.0  | 6         | 1.16%   |
| 0.51-1.0    | 5         | 0.97%   |
| 64.01-256.0 | 1         | 0.19%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 199       | 35.99%  |
| 2.01-3.0  | 162       | 29.29%  |
| 3.01-4.0  | 79        | 14.29%  |
| 4.01-8.0  | 57        | 10.31%  |
| 0.51-1.0  | 36        | 6.51%   |
| 8.01-16.0 | 18        | 3.25%   |
| 0.01-0.5  | 2         | 0.36%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 422       | 81.62%  |
| 2      | 85        | 16.44%  |
| 3      | 8         | 1.55%   |
| 4      | 2         | 0.39%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 334       | 65.36%  |
| Yes       | 177       | 34.64%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 418       | 81.64%  |
| No        | 94        | 18.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 505       | 99.02%  |
| No        | 5         | 0.98%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 413       | 80.82%  |
| No        | 98        | 19.18%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country  | Notebooks | Percent |
|----------|-----------|---------|
| Colombia | 510       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Bogotá                     | 205       | 38.18%  |
| Medellín                   | 67        | 12.48%  |
| Santiago de Cali            | 45        | 8.38%   |
| Barranquilla                | 25        | 4.66%   |
| Bucaramanga                 | 21        | 3.91%   |
| Pereira                     | 17        | 3.17%   |
| Cartagena                   | 16        | 2.98%   |
| Manizales                   | 13        | 2.42%   |
| Envigado                    | 8         | 1.49%   |
| Popayán                    | 7         | 1.3%    |
| Cúcuta                     | 7         | 1.3%    |
| Villavicencio               | 6         | 1.12%   |
| Fusagasuga                  | 6         | 1.12%   |
| Santa Marta                 | 5         | 0.93%   |
| Ibague                      | 5         | 0.93%   |
| Montería                   | 4         | 0.74%   |
| Bello                       | 4         | 0.74%   |
| Armenia                     | 4         | 0.74%   |
| Tunja                       | 3         | 0.56%   |
| Sincelejo                   | 3         | 0.56%   |
| Neiva                       | 3         | 0.56%   |
| Yopal                       | 2         | 0.37%   |
| Valledupar                  | 2         | 0.37%   |
| Soacha                      | 2         | 0.37%   |
| Sabaneta                    | 2         | 0.37%   |
| Rionegro                    | 2         | 0.37%   |
| Los Patios                  | 2         | 0.37%   |
| La Estrella                 | 2         | 0.37%   |
| Itaguei                     | 2         | 0.37%   |
| Ipiales                     | 2         | 0.37%   |
| Floridablanca               | 2         | 0.37%   |
| Cota                        | 2         | 0.37%   |
| Chiquinquira                | 2         | 0.37%   |
| Chia                        | 2         | 0.37%   |
| BogotГЎ                   | 2         | 0.37%   |
| Barrancabermeja             | 2         | 0.37%   |
| Zarzal                      | 1         | 0.19%   |
| Villa de San Diego de Ubate | 1         | 0.19%   |
| Sogamoso                    | 1         | 0.19%   |
| San Vicente de Chucuri      | 1         | 0.19%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 121       | 145    | 20.07%  |
| Toshiba                   | 92        | 107    | 15.26%  |
| WDC                       | 78        | 96     | 12.94%  |
| Samsung Electronics       | 39        | 46     | 6.47%   |
| Kingston                  | 37        | 44     | 6.14%   |
| SanDisk                   | 36        | 41     | 5.97%   |
| HGST                      | 29        | 38     | 4.81%   |
| Crucial                   | 23        | 25     | 3.81%   |
| A-DATA Technology         | 22        | 25     | 3.65%   |
| Hitachi                   | 19        | 23     | 3.15%   |
| Unknown                   | 17        | 17     | 2.82%   |
| Intel                     | 14        | 16     | 2.32%   |
| SK hynix                  | 12        | 17     | 1.99%   |
| Micron Technology         | 8         | 8      | 1.33%   |
| China                     | 8         | 8      | 1.33%   |
| Apple                     | 6         | 6      | 1%      |
| Silicon Motion            | 4         | 4      | 0.66%   |
| Realtek Semiconductor     | 4         | 5      | 0.66%   |
| JMicron Technology        | 4         | 4      | 0.66%   |
| Fujitsu                   | 4         | 4      | 0.66%   |
| LITEONIT                  | 3         | 3      | 0.5%    |
| Phison                    | 2         | 3      | 0.33%   |
| Netac                     | 2         | 2      | 0.33%   |
| LITEON                    | 2         | 3      | 0.33%   |
| Hewlett-Packard           | 2         | 2      | 0.33%   |
| Zheino                    | 1         | 1      | 0.17%   |
| XPG                       | 1         | 1      | 0.17%   |
| Transcend                 | 1         | 1      | 0.17%   |
| SSSTC                     | 1         | 1      | 0.17%   |
| SATAFIRM                  | 1         | 1      | 0.17%   |
| RDM-II                    | 1         | 2      | 0.17%   |
| PNY                       | 1         | 1      | 0.17%   |
| Phison Electronics        | 1         | 1      | 0.17%   |
| Micron/Crucial Technology | 1         | 1      | 0.17%   |
| Lexar                     | 1         | 1      | 0.17%   |
| KIOXIA                    | 1         | 2      | 0.17%   |
| KingSpec                  | 1         | 1      | 0.17%   |
| Hjwdz                     | 1         | 1      | 0.17%   |
| Gigabyte Technology       | 1         | 1      | 0.17%   |
| ASMT                      | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 37        | 6.06%   |
| Toshiba MQ04ABF100 1TB              | 29        | 4.75%   |
| Toshiba MQ01ABF050 500GB            | 18        | 2.95%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 17        | 2.78%   |
| Toshiba MQ01ABD100 1TB              | 15        | 2.45%   |
| Seagate ST500LT012-1DG142 500GB     | 12        | 1.96%   |
| Crucial CT240BX500SSD1 240GB        | 9         | 1.47%   |
| HGST HTS541010A9E680 1TB            | 8         | 1.31%   |
| HGST HTS541010B7E610 1TB            | 7         | 1.15%   |
| WDC WD10SPZX-24Z10 1TB              | 6         | 0.98%   |
| Seagate ST500LT012-9WS142 500GB     | 6         | 0.98%   |
| SanDisk NVMe SSD Drive 512GB        | 6         | 0.98%   |
| SanDisk NVMe SSD Drive 256GB        | 6         | 0.98%   |
| Kingston SA400S37480G 480GB SSD     | 6         | 0.98%   |
| Kingston SA400S37240G 240GB SSD     | 6         | 0.98%   |
| HGST HTS545050A7E680 500GB          | 6         | 0.98%   |
| WDC WD10SPZX-60Z10T0 1TB            | 5         | 0.82%   |
| Seagate ST500LM030-1RK17D 500GB     | 5         | 0.82%   |
| Kingston SA400S37120G 120GB SSD     | 5         | 0.82%   |
| Intel NVMe SSD Drive 512GB          | 5         | 0.82%   |
| WDC WD10JPCX-24UE4T0 1TB            | 4         | 0.65%   |
| SK hynix NVMe SSD Drive 256GB       | 4         | 0.65%   |
| Seagate ST9500325AS 500GB           | 4         | 0.65%   |
| Seagate ST2000LM007-1R8174 2TB      | 4         | 0.65%   |
| SanDisk NVMe SSD Drive 1TB          | 4         | 0.65%   |
| Samsung NVMe SSD Drive 256GB        | 4         | 0.65%   |
| Crucial CT1000BX500SSD1 1TB         | 4         | 0.65%   |
| A-DATA SU650 120GB SSD              | 4         | 0.65%   |
| WDC WD1600BEVT-75ZCT2 160GB         | 3         | 0.49%   |
| Unknown MMC Card  64GB              | 3         | 0.49%   |
| Unknown MMC Card  32GB              | 3         | 0.49%   |
| Toshiba MQ01ABD050 500GB            | 3         | 0.49%   |
| Seagate ST9500420AS 500GB           | 3         | 0.49%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 3         | 0.49%   |
| Seagate ST320LT007-9ZV142 320GB     | 3         | 0.49%   |
| SanDisk NVMe SSD Drive 500GB        | 3         | 0.49%   |
| Samsung NVMe SSD Drive 512GB        | 3         | 0.49%   |
| Samsung NVMe SSD Drive 1024GB       | 3         | 0.49%   |
| Kingston SA400M8240G 240GB SSD      | 3         | 0.49%   |
| Kingston NVMe SSD Drive 512GB       | 3         | 0.49%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 121       | 145    | 35.8%   |
| Toshiba             | 88        | 101    | 26.04%  |
| WDC                 | 69        | 86     | 20.41%  |
| HGST                | 29        | 38     | 8.58%   |
| Hitachi             | 19        | 23     | 5.62%   |
| Samsung Electronics | 4         | 4      | 1.18%   |
| Fujitsu             | 4         | 4      | 1.18%   |
| Unknown             | 1         | 1      | 0.3%    |
| SATAFIRM            | 1         | 1      | 0.3%    |
| Phison              | 1         | 2      | 0.3%    |
| Apple               | 1         | 1      | 0.3%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 28        | 33     | 20.29%  |
| Crucial             | 21        | 23     | 15.22%  |
| A-DATA Technology   | 20        | 23     | 14.49%  |
| SanDisk             | 14        | 15     | 10.14%  |
| Samsung Electronics | 14        | 15     | 10.14%  |
| China               | 8         | 8      | 5.8%    |
| Toshiba             | 5         | 6      | 3.62%   |
| Intel               | 4         | 5      | 2.9%    |
| Apple               | 4         | 4      | 2.9%    |
| Micron Technology   | 3         | 3      | 2.17%   |
| LITEONIT            | 3         | 3      | 2.17%   |
| WDC                 | 2         | 2      | 1.45%   |
| SK hynix            | 2         | 5      | 1.45%   |
| LITEON              | 2         | 3      | 1.45%   |
| Zheino              | 1         | 1      | 0.72%   |
| Transcend           | 1         | 1      | 0.72%   |
| PNY                 | 1         | 1      | 0.72%   |
| Netac               | 1         | 1      | 0.72%   |
| Lexar               | 1         | 1      | 0.72%   |
| KingSpec            | 1         | 1      | 0.72%   |
| Hewlett-Packard     | 1         | 1      | 0.72%   |
| Gigabyte Technology | 1         | 1      | 0.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 332       | 406    | 56.27%  |
| SSD     | 134       | 156    | 22.71%  |
| NVMe    | 102       | 124    | 17.29%  |
| MMC     | 16        | 16     | 2.71%   |
| Unknown | 6         | 7      | 1.02%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 428       | 557    | 76.7%   |
| NVMe | 100       | 121    | 17.92%  |
| MMC  | 16        | 16     | 2.87%   |
| SAS  | 14        | 15     | 2.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 269       | 337    | 58.86%  |
| 0.51-1.0   | 181       | 214    | 39.61%  |
| 1.01-2.0   | 6         | 9      | 1.31%   |
| 0          | 1         | 2      | 0.22%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 152       | 28.57%  |
| 101-250        | 136       | 25.56%  |
| 501-1000       | 111       | 20.86%  |
| 1-20           | 42        | 7.89%   |
| 51-100         | 39        | 7.33%   |
| 21-50          | 23        | 4.32%   |
| 1001-2000      | 20        | 3.76%   |
| Unknown        | 5         | 0.94%   |
| More than 3000 | 2         | 0.38%   |
| 2001-3000      | 2         | 0.38%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 230       | 41.67%  |
| 21-50     | 120       | 21.74%  |
| 101-250   | 77        | 13.95%  |
| 51-100    | 62        | 11.23%  |
| 251-500   | 35        | 6.34%   |
| 501-1000  | 22        | 3.99%   |
| Unknown   | 5         | 0.91%   |
| 1001-2000 | 1         | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Notebooks | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB             | 3         | 3      | 7.5%    |
| Seagate ST9320423AS 320GB                      | 2         | 2      | 5%      |
| A-DATA Technology SU630 480GB SSD              | 2         | 2      | 5%      |
| WDC WD5000BPVT-22HXZT3 500GB                   | 1         | 1      | 2.5%    |
| WDC WD5000BEVT-22A0RT0 500GB                   | 1         | 1      | 2.5%    |
| WDC WD3200BPVT-24JJ5T0 320GB                   | 1         | 1      | 2.5%    |
| WDC WD3200BEKT-60F3T1 320GB                    | 1         | 1      | 2.5%    |
| WDC WD1600BEVT-22A23T0 160GB                   | 1         | 1      | 2.5%    |
| WDC WD1600BEKT-60V5T1 160GB                    | 1         | 1      | 2.5%    |
| Toshiba MQ04ABF100 1TB                         | 1         | 2      | 2.5%    |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 2.5%    |
| Toshiba MK7559GSXP 752GB                       | 1         | 1      | 2.5%    |
| Toshiba MK5076GSX 500GB                        | 1         | 1      | 2.5%    |
| Toshiba MK5065GSXN 500GB                       | 1         | 1      | 2.5%    |
| Toshiba MK3263GSX 320GB                        | 1         | 1      | 2.5%    |
| Seagate ST9500420AS 500GB                      | 1         | 1      | 2.5%    |
| Seagate ST9500325AS 500GB                      | 1         | 1      | 2.5%    |
| Seagate ST750LM022 HN-M750MBB 752GB            | 1         | 1      | 2.5%    |
| Seagate ST500LX012-1LM162-SSHD 500GB           | 1         | 1      | 2.5%    |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 2.5%    |
| Seagate ST500LT012-1DG142 500GB                | 1         | 1      | 2.5%    |
| Seagate ST500LM021-1KJ152 500GB                | 1         | 1      | 2.5%    |
| Seagate ST320LT007-9ZV142 320GB                | 1         | 1      | 2.5%    |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 2.5%    |
| Samsung Electronics SSD PM810 2.5 7mm 128GB    | 1         | 1      | 2.5%    |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 2.5%    |
| Intel SSDSC2BW240A4 240GB                      | 1         | 2      | 2.5%    |
| Hitachi HTS725032A9A364 320GB                  | 1         | 1      | 2.5%    |
| Hitachi HTS721080G9SA00 80GB                   | 1         | 1      | 2.5%    |
| Hitachi HTS545050B9A300 500GB                  | 1         | 1      | 2.5%    |
| Hitachi HTS545025B9A300 250GB                  | 1         | 1      | 2.5%    |
| Hitachi HTS543225L9A300 250GB                  | 1         | 5      | 2.5%    |
| Hitachi HTS542516K9SA00 160GB                  | 1         | 1      | 2.5%    |
| HGST HTS545050A7E680 500GB                     | 1         | 1      | 2.5%    |
| HGST HTS541075A9E680 752GB                     | 1         | 1      | 2.5%    |
| Crucial M4-CT128M4SSD2 128GB                   | 1         | 1      | 2.5%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 14     | 35%     |
| WDC                 | 6         | 6      | 15%     |
| Toshiba             | 6         | 7      | 15%     |
| Hitachi             | 6         | 10     | 15%     |
| HGST                | 2         | 2      | 5%      |
| A-DATA Technology   | 2         | 2      | 5%      |
| Samsung Electronics | 1         | 1      | 2.5%    |
| Micron Technology   | 1         | 1      | 2.5%    |
| Intel               | 1         | 2      | 2.5%    |
| Crucial             | 1         | 1      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 14        | 14     | 41.18%  |
| WDC     | 6         | 6      | 17.65%  |
| Toshiba | 6         | 7      | 17.65%  |
| Hitachi | 6         | 10     | 17.65%  |
| HGST    | 2         | 2      | 5.88%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 33        | 39     | 84.62%  |
| SSD  | 6         | 7      | 15.38%  |

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
| Detected | 362       | 505    | 68.3%   |
| Works    | 129       | 158    | 24.34%  |
| Malfunc  | 39        | 46     | 7.36%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 347       | 60.66%  |
| AMD                            | 121       | 21.15%  |
| SanDisk                        | 28        | 4.9%    |
| Samsung Electronics            | 21        | 3.67%   |
| SK hynix                       | 10        | 1.75%   |
| Kingston Technology Company    | 8         | 1.4%    |
| Nvidia                         | 7         | 1.22%   |
| Realtek Semiconductor          | 6         | 1.05%   |
| Micron Technology              | 6         | 1.05%   |
| Silicon Motion                 | 4         | 0.7%    |
| VIA Technologies               | 2         | 0.35%   |
| Phison Electronics             | 2         | 0.35%   |
| Micron/Crucial Technology      | 2         | 0.35%   |
| Marvell Technology Group       | 2         | 0.35%   |
| Union Memory (Shenzhen)        | 1         | 0.17%   |
| Solid State Storage Technology | 1         | 0.17%   |
| KIOXIA                         | 1         | 0.17%   |
| Biwin Storage Technology       | 1         | 0.17%   |
| Apple                          | 1         | 0.17%   |
| ADATA Technology               | 1         | 0.17%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 112       | 18.45%  |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 48        | 7.91%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 38        | 6.26%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 37        | 6.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 28        | 4.61%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 18        | 2.97%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 17        | 2.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 16        | 2.64%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 15        | 2.47%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 14        | 2.31%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 11        | 1.81%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 10        | 1.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 10        | 1.65%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 10        | 1.65%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 8         | 1.32%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 8         | 1.32%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 1.32%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 8         | 1.32%   |
| Samsung NVMe SSD Controller 980                                                  | 7         | 1.15%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 7         | 1.15%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 7         | 1.15%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 7         | 1.15%   |
| Realtek Realtek Non-Volatile memory controller                                   | 6         | 0.99%   |
| Micron Non-Volatile memory controller                                            | 6         | 0.99%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 0.99%   |
| SanDisk PC SN520 NVMe SSD                                                        | 5         | 0.82%   |
| Samsung NVMe SSD Controller SM951/PM951                                          | 5         | 0.82%   |
| Intel Volume Management Device NVMe RAID Controller                              | 5         | 0.82%   |
| Intel Tiger Lake-LP SATA Controller                                              | 5         | 0.82%   |
| Intel SSD 660P Series                                                            | 5         | 0.82%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 4         | 0.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 4         | 0.66%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 4         | 0.66%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 4         | 0.66%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 4         | 0.66%   |
| SK hynix Gold P31 SSD                                                            | 3         | 0.49%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                        | 3         | 0.49%   |
| SanDisk Non-Volatile memory controller                                           | 3         | 0.49%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                            | 3         | 0.49%   |
| Kingston Company Company Non-Volatile memory controller                          | 3         | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 416       | 70.39%  |
| NVMe | 99        | 16.75%  |
| RAID | 44        | 7.45%   |
| IDE  | 32        | 5.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 370       | 72.55%  |
| AMD    | 140       | 27.45%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 23        | 4.51%   |
| Intel Core i5-8265U CPU @ 1.60GHz               | 11        | 2.16%   |
| Intel Core i5-8250U CPU @ 1.60GHz               | 11        | 2.16%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 10        | 1.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 9         | 1.76%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 9         | 1.76%   |
| Intel Celeron N4000 CPU @ 1.10GHz               | 8         | 1.57%   |
| Intel Celeron CPU N3060 @ 1.60GHz               | 8         | 1.57%   |
| AMD A9-9425 RADEON R5, 5 COMPUTE CORES 2C+3G    | 8         | 1.57%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 7         | 1.37%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 7         | 1.37%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 7         | 1.37%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 6         | 1.18%   |
| Intel Core i7-4510U CPU @ 2.00GHz               | 6         | 1.18%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz              | 6         | 1.18%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 6         | 1.18%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 5         | 0.98%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 5         | 0.98%   |
| Intel Core i7-10510U CPU @ 1.80GHz              | 5         | 0.98%   |
| Intel Core i5-4210U CPU @ 1.70GHz               | 5         | 0.98%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 5         | 0.98%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx   | 5         | 0.98%   |
| AMD A9-9420 RADEON R5, 5 COMPUTE CORES 2C+3G    | 5         | 0.98%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 4         | 0.78%   |
| Intel Core i5-5200U CPU @ 2.20GHz               | 4         | 0.78%   |
| Intel Core i5-3337U CPU @ 1.80GHz               | 4         | 0.78%   |
| Intel Core i5-2410M CPU @ 2.30GHz               | 4         | 0.78%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz              | 4         | 0.78%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 4         | 0.78%   |
| Intel Core i3-7020U CPU @ 2.30GHz               | 4         | 0.78%   |
| Intel Core i3-6006U CPU @ 2.00GHz               | 4         | 0.78%   |
| Intel Core i3-5005U CPU @ 2.00GHz               | 4         | 0.78%   |
| Intel Core i3-3110M CPU @ 2.40GHz               | 4         | 0.78%   |
| Intel Core i3-2350M CPU @ 2.30GHz               | 4         | 0.78%   |
| Intel Core i3-2310M CPU @ 2.10GHz               | 4         | 0.78%   |
| Intel Atom CPU N450 @ 1.66GHz                   | 4         | 0.78%   |
| Intel Atom CPU N270 @ 1.60GHz                   | 4         | 0.78%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 4         | 0.78%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 4         | 0.78%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 4         | 0.78%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 114       | 22.35%  |
| Intel Core i7                  | 97        | 19.02%  |
| Intel Core i3                  | 56        | 10.98%  |
| AMD Ryzen 5                    | 37        | 7.25%   |
| Intel Celeron                  | 35        | 6.86%   |
| Other                          | 29        | 5.69%   |
| Intel Atom                     | 15        | 2.94%   |
| Intel Core 2 Duo               | 14        | 2.75%   |
| AMD Ryzen 3                    | 11        | 2.16%   |
| AMD A10                        | 10        | 1.96%   |
| AMD Ryzen 7                    | 9         | 1.76%   |
| AMD A12                        | 9         | 1.76%   |
| AMD E1                         | 8         | 1.57%   |
| Intel Pentium                  | 7         | 1.37%   |
| AMD Ryzen 7 PRO                | 6         | 1.18%   |
| Intel Pentium Dual-Core        | 5         | 0.98%   |
| Intel Pentium Dual             | 5         | 0.98%   |
| AMD A8                         | 5         | 0.98%   |
| AMD A6                         | 5         | 0.98%   |
| AMD A4                         | 5         | 0.98%   |
| AMD E2                         | 4         | 0.78%   |
| AMD E                          | 4         | 0.78%   |
| AMD Athlon                     | 3         | 0.59%   |
| Intel Core m5                  | 2         | 0.39%   |
| Intel Celeron M                | 2         | 0.39%   |
| AMD Turion 64 X2 Mobile        | 2         | 0.39%   |
| AMD Ryzen 9                    | 2         | 0.39%   |
| Intel Genuine                  | 1         | 0.2%    |
| Intel Core M                   | 1         | 0.2%    |
| Intel Core 2                   | 1         | 0.2%    |
| AMD V120                       | 1         | 0.2%    |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.2%    |
| AMD Mobile Sempron             | 1         | 0.2%    |
| AMD C-70                       | 1         | 0.2%    |
| AMD C-60                       | 1         | 0.2%    |
| AMD Athlon II Neo              | 1         | 0.2%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 302       | 59.1%   |
| 4       | 153       | 29.94%  |
| 1       | 22        | 4.31%   |
| 8       | 16        | 3.13%   |
| 6       | 15        | 2.94%   |
| 14      | 2         | 0.39%   |
| Unknown | 1         | 0.2%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 510       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 373       | 72.99%  |
| 1       | 135       | 26.42%  |
| 8       | 2         | 0.39%   |
| Unknown | 1         | 0.2%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 475       | 92.23%  |
| Unknown        | 31        | 6.02%   |
| 64-bit         | 6         | 1.17%   |
| 32-bit         | 3         | 0.58%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 88        | 16.86%  |
| 0x306a9    | 31        | 5.94%   |
| 0x206a7    | 29        | 5.56%   |
| 0x806ea    | 24        | 4.6%    |
| 0x406e3    | 21        | 4.02%   |
| 0x40651    | 18        | 3.45%   |
| 0x06006705 | 18        | 3.45%   |
| 0x306d4    | 17        | 3.26%   |
| 0x806ec    | 15        | 2.87%   |
| 0x08108109 | 15        | 2.87%   |
| 0x306c3    | 13        | 2.49%   |
| 0x08108102 | 13        | 2.49%   |
| 0x806c1    | 11        | 2.11%   |
| 0x20655    | 11        | 2.11%   |
| 0x906ea    | 10        | 1.92%   |
| 0x706e5    | 10        | 1.92%   |
| 0x1067a    | 10        | 1.92%   |
| 0x806e9    | 9         | 1.72%   |
| 0x6fd      | 9         | 1.72%   |
| 0x406c4    | 9         | 1.72%   |
| 0x806eb    | 8         | 1.53%   |
| 0x706a1    | 8         | 1.53%   |
| 0x06006118 | 7         | 1.34%   |
| 0x05000119 | 7         | 1.34%   |
| 0x106ca    | 6         | 1.15%   |
| 0x08101007 | 6         | 1.15%   |
| 0x0600611a | 6         | 1.15%   |
| 0x506e3    | 5         | 0.96%   |
| 0x30678    | 5         | 0.96%   |
| 0x20652    | 5         | 0.96%   |
| 0x08600106 | 5         | 0.96%   |
| 0xa0652    | 4         | 0.77%   |
| 0x106e5    | 4         | 0.77%   |
| 0x106c2    | 4         | 0.77%   |
| 0x0a50000c | 4         | 0.77%   |
| 0x0810100b | 4         | 0.77%   |
| 0x07030104 | 4         | 0.77%   |
| 0x06006704 | 4         | 0.77%   |
| 0x6f6      | 3         | 0.57%   |
| 0x10676    | 3         | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 84        | 16.47%  |
| Excavator        | 37        | 7.25%   |
| Zen+             | 36        | 7.06%   |
| SandyBridge      | 36        | 7.06%   |
| Haswell          | 36        | 7.06%   |
| IvyBridge        | 35        | 6.86%   |
| Skylake          | 30        | 5.88%   |
| Westmere         | 20        | 3.92%   |
| Silvermont       | 18        | 3.53%   |
| Broadwell        | 18        | 3.53%   |
| Core             | 17        | 3.33%   |
| Penryn           | 14        | 2.75%   |
| IceLake          | 13        | 2.55%   |
| TigerLake        | 12        | 2.35%   |
| Zen 2            | 11        | 2.16%   |
| Zen              | 11        | 2.16%   |
| Goldmont plus    | 11        | 2.16%   |
| Bonnell          | 11        | 2.16%   |
| Puma             | 8         | 1.57%   |
| Bobcat           | 8         | 1.57%   |
| Zen 3            | 5         | 0.98%   |
| Jaguar           | 5         | 0.98%   |
| CometLake        | 5         | 0.98%   |
| Piledriver       | 4         | 0.78%   |
| Nehalem          | 4         | 0.78%   |
| K8 Hammer        | 4         | 0.78%   |
| Goldmont         | 4         | 0.78%   |
| Unknown          | 4         | 0.78%   |
| Steamroller      | 3         | 0.59%   |
| K10              | 2         | 0.39%   |
| Alderlake Hybrid | 2         | 0.39%   |
| K8 & K10 hybrid  | 1         | 0.2%    |
| K10 Llano        | 1         | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Notebooks | Percent |
|------------------|-----------|---------|
| Intel            | 353       | 56.39%  |
| AMD              | 153       | 24.44%  |
| Nvidia           | 118       | 18.85%  |
| VIA Technologies | 2         | 0.32%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 36        | 5.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 35        | 5.25%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 34        | 5.1%    |
| Intel UHD Graphics 620                                                                   | 22        | 3.3%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 22        | 3.3%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 21        | 3.15%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 20        | 3%      |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 19        | 2.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 19        | 2.85%   |
| Intel HD Graphics 5500                                                                   | 16        | 2.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 16        | 2.4%    |
| Intel HD Graphics 620                                                                    | 15        | 2.25%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 15        | 2.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 13        | 1.95%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 1.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 11        | 1.65%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 11        | 1.65%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 1.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 1.65%   |
| AMD Renoir                                                                               | 11        | 1.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 11        | 1.65%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 10        | 1.5%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 1.35%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 1.2%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 1.2%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 8         | 1.2%    |
| Intel HD Graphics 530                                                                    | 7         | 1.05%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 1.05%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                   | 7         | 1.05%   |
| AMD Jet PRO [Radeon R5 M230 / R7 M260DX / Radeon 520 Mobile]                             | 7         | 1.05%   |
| Nvidia GM108M [GeForce MX110]                                                            | 6         | 0.9%    |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 6         | 0.9%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 6         | 0.9%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 6         | 0.9%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 5         | 0.75%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 5         | 0.75%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 5         | 0.75%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 5         | 0.75%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 5         | 0.75%   |
| Nvidia GP108M [GeForce MX230]                                                            | 4         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 247       | 48.34%  |
| 1 x AMD        | 103       | 20.16%  |
| Intel + Nvidia | 94        | 18.4%   |
| 2 x AMD        | 28        | 5.48%   |
| 1 x Nvidia     | 15        | 2.94%   |
| Intel + AMD    | 13        | 2.54%   |
| AMD + Nvidia   | 9         | 1.76%   |
| 1 x VIA        | 2         | 0.39%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 441       | 85.63%  |
| Proprietary | 53        | 10.29%  |
| Unknown     | 21        | 4.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 295       | 56.84%  |
| 1.01-2.0   | 89        | 17.15%  |
| 0.01-0.5   | 78        | 15.03%  |
| 3.01-4.0   | 26        | 5.01%   |
| 0.51-1.0   | 26        | 5.01%   |
| 5.01-6.0   | 3         | 0.58%   |
| 7.01-8.0   | 1         | 0.19%   |
| 8.01-16.0  | 1         | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 126       | 21.84%  |
| AU Optronics            | 103       | 17.85%  |
| BOE                     | 85        | 14.73%  |
| Samsung Electronics     | 68        | 11.79%  |
| LG Display              | 65        | 11.27%  |
| Goldstar                | 20        | 3.47%   |
| PANDA                   | 13        | 2.25%   |
| Chi Mei Optoelectronics | 13        | 2.25%   |
| Dell                    | 10        | 1.73%   |
| Apple                   | 10        | 1.73%   |
| Sharp                   | 8         | 1.39%   |
| Hewlett-Packard         | 7         | 1.21%   |
| InnoLux Display         | 5         | 0.87%   |
| Sony                    | 4         | 0.69%   |
| LG Philips              | 4         | 0.69%   |
| Lenovo                  | 4         | 0.69%   |
| InfoVision              | 4         | 0.69%   |
| AOC                     | 4         | 0.69%   |
| Acer                    | 4         | 0.69%   |
| CSO                     | 3         | 0.52%   |
| ViewSonic               | 2         | 0.35%   |
| HannStar                | 2         | 0.35%   |
| BenQ                    | 2         | 0.35%   |
| Sceptre Tech            | 1         | 0.17%   |
| MSI                     | 1         | 0.17%   |
| LTM                     | 1         | 0.17%   |
| KTC                     | 1         | 0.17%   |
| KDC                     | 1         | 0.17%   |
| HannStar Display        | 1         | 0.17%   |
| eMachines               | 1         | 0.17%   |
| ELD                     | 1         | 0.17%   |
| CS_                     | 1         | 0.17%   |
| CHO                     | 1         | 0.17%   |
| Ancor Communications    | 1         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch       | 15        | 2.57%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch       | 14        | 2.4%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch       | 10        | 1.72%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 9         | 1.54%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 9         | 1.54%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                  | 8         | 1.37%   |
| AU Optronics LCD Monitor AUO723C 1366x768 309x173mm 13.9-inch         | 8         | 1.37%   |
| AU Optronics LCD Monitor AUO2D3C 1366x768 309x173mm 13.9-inch         | 8         | 1.37%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 7         | 1.2%    |
| AU Optronics LCD Monitor AUO323C 1366x768 309x173mm 13.9-inch         | 7         | 1.2%    |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 6         | 1.03%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch               | 5         | 0.86%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 5         | 0.86%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 5         | 0.86%   |
| Chimei Innolux LCD Monitor CMN1491 1366x768 309x174mm 14.0-inch       | 5         | 0.86%   |
| BOE LCD Monitor BOE07AA 1366x768 344x194mm 15.5-inch                  | 5         | 0.86%   |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                  | 5         | 0.86%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch      | 4         | 0.69%   |
| Chimei Innolux LCD Monitor CMN1490 1366x768 309x173mm 13.9-inch       | 4         | 0.69%   |
| BOE LCD Monitor BOE0704 1366x768 344x194mm 15.5-inch                  | 4         | 0.69%   |
| BOE LCD Monitor BOE0644 1366x768 309x173mm 13.9-inch                  | 4         | 0.69%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 4         | 0.69%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 4         | 0.69%   |
| Sharp LCD Monitor SHP143E 3840x2160 346x194mm 15.6-inch               | 3         | 0.51%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch     | 3         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch  | 3         | 0.51%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch | 3         | 0.51%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 0.51%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch               | 3         | 0.51%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 3         | 0.51%   |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch           | 3         | 0.51%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch           | 3         | 0.51%   |
| LG Display LCD Monitor LGD02F8 1366x768 309x174mm 14.0-inch           | 3         | 0.51%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 3         | 0.51%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3         | 0.51%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 3         | 0.51%   |
| Chimei Innolux LCD Monitor CMN1495 1366x768 309x173mm 13.9-inch       | 3         | 0.51%   |
| BOE LCD Monitor BOE07F7 1920x1080 309x174mm 14.0-inch                 | 3         | 0.51%   |
| BOE LCD Monitor BOE05BA 1366x768 309x173mm 13.9-inch                  | 3         | 0.51%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 3         | 0.51%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 314       | 57.4%   |
| 1920x1080 (FHD)    | 128       | 23.4%   |
| 1600x900 (HD+)     | 21        | 3.84%   |
| 3840x2160 (4K)     | 18        | 3.29%   |
| 1280x800 (WXGA)    | 17        | 3.11%   |
| 1440x900 (WXGA+)   | 10        | 1.83%   |
| 1024x600           | 7         | 1.28%   |
| 1920x1200 (WUXGA)  | 6         | 1.1%    |
| 2560x1440 (QHD)    | 5         | 0.91%   |
| 1280x1024 (SXGA)   | 5         | 0.91%   |
| 2560x1600          | 3         | 0.55%   |
| 3456x2160          | 2         | 0.37%   |
| 2160x1440          | 2         | 0.37%   |
| 1360x768           | 2         | 0.37%   |
| 3840x1080          | 1         | 0.18%   |
| 3440x1440          | 1         | 0.18%   |
| 2880x1800          | 1         | 0.18%   |
| 2560x1080          | 1         | 0.18%   |
| 2256x1504          | 1         | 0.18%   |
| 1680x1050 (WSXGA+) | 1         | 0.18%   |
| 1024x768 (XGA)     | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 186       | 31.96%  |
| 13      | 137       | 23.54%  |
| 14      | 109       | 18.73%  |
| 17      | 22        | 3.78%   |
| 21      | 17        | 2.92%   |
| 23      | 16        | 2.75%   |
| 11      | 11        | 1.89%   |
| 27      | 10        | 1.72%   |
| 12      | 10        | 1.72%   |
| 24      | 9         | 1.55%   |
| 10      | 7         | 1.2%    |
| 19      | 6         | 1.03%   |
| 18      | 6         | 1.03%   |
| 72      | 4         | 0.69%   |
| 31      | 4         | 0.69%   |
| 20      | 4         | 0.69%   |
| 47      | 3         | 0.52%   |
| 16      | 3         | 0.52%   |
| Unknown | 3         | 0.52%   |
| 84      | 2         | 0.34%   |
| 54      | 2         | 0.34%   |
| 34      | 2         | 0.34%   |
| 8       | 2         | 0.34%   |
| 63      | 1         | 0.17%   |
| 61      | 1         | 0.17%   |
| 48      | 1         | 0.17%   |
| 43      | 1         | 0.17%   |
| 40      | 1         | 0.17%   |
| 26      | 1         | 0.17%   |
| 22      | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 406       | 70.61%  |
| 201-300     | 51        | 8.87%   |
| 401-500     | 34        | 5.91%   |
| 501-600     | 30        | 5.22%   |
| 351-400     | 22        | 3.83%   |
| 601-700     | 9         | 1.57%   |
| 1001-1500   | 8         | 1.39%   |
| 1501-2000   | 6         | 1.04%   |
| Unknown     | 3         | 0.52%   |
| 701-800     | 2         | 0.35%   |
| 101-200     | 2         | 0.35%   |
| 801-900     | 1         | 0.17%   |
| 901-1000    | 1         | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 450       | 88.58%  |
| 16/10   | 44        | 8.66%   |
| 5/4     | 5         | 0.98%   |
| 3/2     | 4         | 0.79%   |
| 21/9    | 2         | 0.39%   |
| 4/3     | 1         | 0.2%    |
| 32/9    | 1         | 0.2%    |
| Unknown | 1         | 0.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 81-90          | 228       | 39.38%  |
| 101-110        | 188       | 32.47%  |
| 201-250        | 34        | 5.87%   |
| 71-80          | 16        | 2.76%   |
| 121-130        | 13        | 2.25%   |
| 151-200        | 12        | 2.07%   |
| 51-60          | 11        | 1.9%    |
| 301-350        | 11        | 1.9%    |
| 141-150        | 11        | 1.9%    |
| More than 1000 | 10        | 1.73%   |
| 61-70          | 10        | 1.73%   |
| 41-50          | 7         | 1.21%   |
| 351-500        | 6         | 1.04%   |
| 251-300        | 6         | 1.04%   |
| 501-1000       | 6         | 1.04%   |
| 131-140        | 4         | 0.69%   |
| Unknown        | 3         | 0.52%   |
| 1-40           | 2         | 0.35%   |
| 111-120        | 1         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 316       | 55.73%  |
| 121-160       | 125       | 22.05%  |
| 51-100        | 82        | 14.46%  |
| 161-240       | 18        | 3.17%   |
| 1-50          | 12        | 2.12%   |
| More than 240 | 11        | 1.94%   |
| Unknown       | 3         | 0.53%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 407       | 77.23%  |
| 2     | 94        | 17.84%  |
| 0     | 21        | 3.98%   |
| 3     | 4         | 0.76%   |
| 4     | 1         | 0.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 336       | 41.28%  |
| Intel                           | 173       | 21.25%  |
| Qualcomm Atheros                | 149       | 18.3%   |
| Broadcom                        | 50        | 6.14%   |
| Broadcom Limited                | 24        | 2.95%   |
| Ralink                          | 12        | 1.47%   |
| TP-Link                         | 10        | 1.23%   |
| Marvell Technology Group        | 9         | 1.11%   |
| Samsung Electronics             | 6         | 0.74%   |
| Ralink Technology               | 6         | 0.74%   |
| Nvidia                          | 6         | 0.74%   |
| Qualcomm Atheros Communications | 4         | 0.49%   |
| MediaTek                        | 4         | 0.49%   |
| Huawei Technologies             | 4         | 0.49%   |
| ASIX Electronics                | 3         | 0.37%   |
| Xiaomi                          | 2         | 0.25%   |
| VIA Technologies                | 2         | 0.25%   |
| D-Link System                   | 2         | 0.25%   |
| T & A Mobile Phones             | 1         | 0.12%   |
| STMicroelectronics              | 1         | 0.12%   |
| Quanta                          | 1         | 0.12%   |
| Qualcomm                        | 1         | 0.12%   |
| Prolific Technology             | 1         | 0.12%   |
| Motorola PCS                    | 1         | 0.12%   |
| Lenovo                          | 1         | 0.12%   |
| JMicron Technology              | 1         | 0.12%   |
| Google                          | 1         | 0.12%   |
| DisplayLink                     | 1         | 0.12%   |
| Dell                            | 1         | 0.12%   |
| 3Com                            | 1         | 0.12%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 208       | 21.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 71        | 7.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 38        | 3.89%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 36        | 3.68%   |
| Intel Wireless 8265 / 8275                                              | 27        | 2.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 24        | 2.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 23        | 2.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 22        | 2.25%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 19        | 1.94%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 15        | 1.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 13        | 1.33%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 1.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 1.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 12        | 1.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 12        | 1.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 11        | 1.13%   |
| Intel Wireless 7260                                                     | 11        | 1.13%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 1.02%   |
| Intel Wireless 8260                                                     | 9         | 0.92%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 0.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 0.92%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 0.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 8         | 0.82%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 7         | 0.72%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.72%   |
| Intel Ethernet Connection I219-LM                                       | 7         | 0.72%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 7         | 0.72%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 6         | 0.61%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 6         | 0.61%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 6         | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 0.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 0.61%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 0.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 0.61%   |
| Broadcom Limited BCM43142 802.11b/g/n                                   | 6         | 0.61%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 5         | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 5         | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 0.51%   |
| Intel Wireless 7265                                                     | 5         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 167       | 31.21%  |
| Realtek Semiconductor           | 141       | 26.36%  |
| Qualcomm Atheros                | 130       | 24.3%   |
| Broadcom                        | 38        | 7.1%    |
| Broadcom Limited                | 18        | 3.36%   |
| Ralink                          | 12        | 2.24%   |
| TP-Link                         | 10        | 1.87%   |
| Ralink Technology               | 6         | 1.12%   |
| Qualcomm Atheros Communications | 4         | 0.75%   |
| MediaTek                        | 3         | 0.56%   |
| D-Link System                   | 2         | 0.37%   |
| Qualcomm                        | 1         | 0.19%   |
| Marvell Technology Group        | 1         | 0.19%   |
| Dell                            | 1         | 0.19%   |
| 3Com                            | 1         | 0.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 38        | 7.08%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 36        | 6.7%    |
| Intel Wireless 8265 / 8275                                              | 27        | 5.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 24        | 4.47%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 23        | 4.28%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 22        | 4.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 19        | 3.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 13        | 2.42%   |
| Intel Wi-Fi 6 AX200                                                     | 13        | 2.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 12        | 2.23%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 12        | 2.23%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 12        | 2.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 12        | 2.23%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 11        | 2.05%   |
| Intel Wireless 7260                                                     | 11        | 2.05%   |
| Broadcom BCM43142 802.11b/g/n                                           | 10        | 1.86%   |
| Intel Wireless 8260                                                     | 9         | 1.68%   |
| Intel Wi-Fi 6 AX201                                                     | 9         | 1.68%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 1.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 1.49%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 7         | 1.3%    |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 1.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 7         | 1.3%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 6         | 1.12%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 6         | 1.12%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 6         | 1.12%   |
| Intel Centrino Wireless-N 2230                                          | 6         | 1.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 6         | 1.12%   |
| Broadcom Limited BCM43142 802.11b/g/n                                   | 6         | 1.12%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]              | 5         | 0.93%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 5         | 0.93%   |
| Intel Wireless 7265                                                     | 5         | 0.93%   |
| Intel Wireless 3160                                                     | 5         | 0.93%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 5         | 0.93%   |
| Realtek 802.11ac NIC                                                    | 4         | 0.74%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 4         | 0.74%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 4         | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.74%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 3         | 0.56%   |
| Ralink MT7601U Wireless Adapter                                         | 3         | 0.56%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 298       | 68.51%  |
| Intel                    | 41        | 9.43%   |
| Qualcomm Atheros         | 36        | 8.28%   |
| Broadcom                 | 16        | 3.68%   |
| Marvell Technology Group | 8         | 1.84%   |
| Samsung Electronics      | 6         | 1.38%   |
| Nvidia                   | 6         | 1.38%   |
| Broadcom Limited         | 6         | 1.38%   |
| Huawei Technologies      | 4         | 0.92%   |
| ASIX Electronics         | 3         | 0.69%   |
| Xiaomi                   | 2         | 0.46%   |
| VIA Technologies         | 2         | 0.46%   |
| T & A Mobile Phones      | 1         | 0.23%   |
| Quanta                   | 1         | 0.23%   |
| Prolific Technology      | 1         | 0.23%   |
| MediaTek                 | 1         | 0.23%   |
| Lenovo                   | 1         | 0.23%   |
| JMicron Technology       | 1         | 0.23%   |
| DisplayLink              | 1         | 0.23%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 208       | 47.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 71        | 16.25%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 15        | 3.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 1.83%   |
| Intel Ethernet Connection I219-LM                                 | 7         | 1.6%    |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 6         | 1.37%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 1.37%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 1.14%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 5         | 1.14%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 4         | 0.92%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 4         | 0.92%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 4         | 0.92%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.92%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 4         | 0.92%   |
| Intel Ethernet Connection I219-V                                  | 4         | 0.92%   |
| Intel 82577LM Gigabit Network Connection                          | 4         | 0.92%   |
| Huawei YAL-L21                                                    | 4         | 0.92%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.69%   |
| Nvidia MCP79 Ethernet                                             | 3         | 0.69%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.69%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 0.69%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 3         | 0.69%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.46%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 2         | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.46%   |
| Nvidia MCP67 Ethernet                                             | 2         | 0.46%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.46%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.46%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 2         | 0.46%   |
| ASIX AX88772B                                                     | 2         | 0.46%   |
| T & A Mobile Phones ALCATEL ONETOUCH PIXI 3 (4)                   | 1         | 0.23%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.23%   |
| Realtek RTL8125 2.5GbE Controller                                 | 1         | 0.23%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.23%   |
| Quanta HSUSB Device                                               | 1         | 0.23%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 1         | 0.23%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.23%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 1         | 0.23%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 505       | 54.59%  |
| Ethernet | 417       | 45.08%  |
| Unknown  | 2         | 0.22%   |
| Modem    | 1         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 407       | 73.87%  |
| Ethernet | 143       | 25.95%  |
| Unknown  | 1         | 0.18%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 388       | 76.08%  |
| 1     | 117       | 22.94%  |
| 0     | 4         | 0.78%   |
| 3     | 1         | 0.2%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 475       | 92.23%  |
| Yes  | 40        | 7.77%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 137       | 32.93%  |
| Realtek Semiconductor           | 77        | 18.51%  |
| IMC Networks                    | 50        | 12.02%  |
| Qualcomm Atheros Communications | 45        | 10.82%  |
| Lite-On Technology              | 29        | 6.97%   |
| Broadcom                        | 18        | 4.33%   |
| Foxconn / Hon Hai               | 12        | 2.88%   |
| Ralink                          | 8         | 1.92%   |
| Cambridge Silicon Radio         | 8         | 1.92%   |
| Apple                           | 8         | 1.92%   |
| Hewlett-Packard                 | 6         | 1.44%   |
| Toshiba                         | 5         | 1.2%    |
| Realtek                         | 3         | 0.72%   |
| Foxconn International           | 3         | 0.72%   |
| Alps Electric                   | 3         | 0.72%   |
| Dell                            | 2         | 0.48%   |
| MediaTek                        | 1         | 0.24%   |
| ASUSTek Computer                | 1         | 0.24%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 63        | 15.14%  |
| Realtek  Bluetooth 4.2 Adapter                      | 42        | 10.1%   |
| Realtek Bluetooth Radio                             | 28        | 6.73%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 28        | 6.73%   |
| IMC Networks Bluetooth Radio                        | 28        | 6.73%   |
| Qualcomm Atheros  Bluetooth Device                  | 21        | 5.05%   |
| Intel AX201 Bluetooth                               | 17        | 4.09%   |
| IMC Networks Bluetooth Device                       | 15        | 3.61%   |
| Intel AX200 Bluetooth                               | 13        | 3.13%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 2.4%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 9         | 2.16%   |
| Ralink RT3290 Bluetooth                             | 8         | 1.92%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 8         | 1.92%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 8         | 1.92%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 7         | 1.68%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 7         | 1.68%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 5         | 1.2%    |
| Lite-On Bluetooth Device                            | 5         | 1.2%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 4         | 0.96%   |
| Lite-On Atheros AR3012 Bluetooth                    | 4         | 0.96%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 4         | 0.96%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 4         | 0.96%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 0.96%   |
| Apple Bluetooth Host Controller                     | 4         | 0.96%   |
| Realtek Bluetooth Radio                             | 3         | 0.72%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 3         | 0.72%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.72%   |
| Broadcom BCM20702A0                                 | 3         | 0.72%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 0.72%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.72%   |
| Apple Bluetooth USB Host Controller                 | 3         | 0.72%   |
| Alps Electric BCM2046 Bluetooth Device              | 3         | 0.72%   |
| Toshiba Askey Bluetooth Module                      | 2         | 0.48%   |
| Realtek RTL8723B Bluetooth                          | 2         | 0.48%   |
| Lite-On Bluetooth Radio                             | 2         | 0.48%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 2         | 0.48%   |
| IMC Networks Wireless_Device                        | 2         | 0.48%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 0.48%   |
| Foxconn / Hon Hai BCM20702A0                        | 2         | 0.48%   |
| Dell Wireless 360 Bluetooth                         | 2         | 0.48%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 359       | 62.43%  |
| AMD                       | 142       | 24.7%   |
| Nvidia                    | 50        | 8.7%    |
| Realtek Semiconductor     | 3         | 0.52%   |
| Logitech                  | 3         | 0.52%   |
| C-Media Electronics       | 3         | 0.52%   |
| VIA Technologies          | 2         | 0.35%   |
| Plantronics               | 2         | 0.35%   |
| JMTek                     | 2         | 0.35%   |
| Texas Instruments         | 1         | 0.17%   |
| Sennheiser Communications | 1         | 0.17%   |
| Microsoft                 | 1         | 0.17%   |
| Generalplus Technology    | 1         | 0.17%   |
| DCMT Technology           | 1         | 0.17%   |
| Corsair                   | 1         | 0.17%   |
| BEHRINGER International   | 1         | 0.17%   |
| Astro Gaming              | 1         | 0.17%   |
| Apple                     | 1         | 0.17%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 65        | 8.6%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 62        | 8.2%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 45        | 5.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 42        | 5.56%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 37        | 4.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 29        | 3.84%   |
| AMD Kabini HDMI/DP Audio                                                                          | 28        | 3.7%    |
| AMD FCH Azalia Controller                                                                         | 25        | 3.31%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 24        | 3.17%   |
| AMD High Definition Audio Controller                                                              | 22        | 2.91%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 20        | 2.65%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 20        | 2.65%   |
| Intel 8 Series HD Audio Controller                                                                | 19        | 2.51%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 18        | 2.38%   |
| Intel Broadwell-U Audio Controller                                                                | 18        | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 16        | 2.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 16        | 2.12%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 16        | 2.12%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 14        | 1.85%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 12        | 1.59%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 12        | 1.59%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 1.59%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 11        | 1.46%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 11        | 1.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 10        | 1.32%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 10        | 1.32%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 9         | 1.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 8         | 1.06%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 1.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 0.93%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 7         | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 0.93%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 5         | 0.66%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 0.66%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 0.66%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 0.53%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 0.53%   |
| AMD Trinity HDMI Audio Controller                                                                 | 4         | 0.53%   |
| Realtek Semiconductor USB Audio                                                                   | 3         | 0.4%    |
| Nvidia MCP79 High Definition Audio                                                                | 3         | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 83        | 29.86%  |
| SK hynix            | 63        | 22.66%  |
| Micron Technology   | 43        | 15.47%  |
| Kingston            | 19        | 6.83%   |
| Unknown             | 14        | 5.04%   |
| A-DATA Technology   | 13        | 4.68%   |
| Ramaxel Technology  | 9         | 3.24%   |
| Crucial             | 7         | 2.52%   |
| Elpida              | 5         | 1.8%    |
| Nanya Technology    | 3         | 1.08%   |
| Avant               | 3         | 1.08%   |
| Apacer              | 3         | 1.08%   |
| Unknown             | 2         | 0.72%   |
| Unknown (ABCD)      | 1         | 0.36%   |
| Unknown (08AE)      | 1         | 0.36%   |
| Team                | 1         | 0.36%   |
| Qimonda             | 1         | 0.36%   |
| PUSKILL             | 1         | 0.36%   |
| PNY                 | 1         | 0.36%   |
| Kllisre             | 1         | 0.36%   |
| Goldkey             | 1         | 0.36%   |
| ChangXin Memory     | 1         | 0.36%   |
| Centon              | 1         | 0.36%   |
| ASint Technology    | 1         | 0.36%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                        | Notebooks | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 9         | 3.13%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 7         | 2.43%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 6         | 2.08%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s        | 6         | 2.08%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s        | 5         | 1.74%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s    | 4         | 1.39%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s       | 4         | 1.39%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 4         | 1.39%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 4         | 1.39%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 1.39%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 1.39%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 3         | 1.04%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 1.04%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s    | 3         | 1.04%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s    | 3         | 1.04%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 1.04%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s        | 3         | 1.04%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s      | 3         | 1.04%   |
| Unknown RAM Module 2GB SODIMM DDR2                           | 2         | 0.69%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.69%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.69%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 2         | 0.69%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 2         | 0.69%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s       | 2         | 0.69%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s | 2         | 0.69%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s      | 2         | 0.69%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s       | 2         | 0.69%   |
| SK hynix RAM HMA451S6AFR8N-TF 4096MB SODIMM DDR4 2133MT/s    | 2         | 0.69%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s     | 2         | 0.69%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 2         | 0.69%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s        | 2         | 0.69%   |
| Samsung RAM K4A8G165WC-BCTD 4GB SODIMM DDR4 2667MT/s         | 2         | 0.69%   |
| Micron RAM Module 4GB SODIMM DDR3 1600MT/s                   | 2         | 0.69%   |
| Micron RAM Module 4096MB SODIMM DDR3 1600MT/s                | 2         | 0.69%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s        | 2         | 0.69%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s         | 2         | 0.69%   |
| Micron RAM 53E1G32D2NP-046 2GB Row Of Chips LPDDR4 4267MT/s  | 2         | 0.69%   |
| Micron RAM 4KTF25664HZ-1G9P1 2GB SODIMM DDR3 1776MT/s        | 2         | 0.69%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s        | 2         | 0.69%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s       | 2         | 0.69%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 100       | 46.73%  |
| DDR3   | 82        | 38.32%  |
| LPDDR4 | 11        | 5.14%   |
| DDR2   | 11        | 5.14%   |
| SDRAM  | 4         | 1.87%   |
| LPDDR3 | 4         | 1.87%   |
| DRAM   | 1         | 0.47%   |
| DDR5   | 1         | 0.47%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 200       | 94.79%  |
| Row Of Chips | 11        | 5.21%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 111       | 43.7%   |
| 8192  | 77        | 30.31%  |
| 2048  | 32        | 12.6%   |
| 16384 | 19        | 7.48%   |
| 1024  | 11        | 4.33%   |
| 32768 | 3         | 1.18%   |
| 512   | 1         | 0.39%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 61        | 25.85%  |
| 1600    | 60        | 25.42%  |
| 3200    | 27        | 11.44%  |
| 2400    | 19        | 8.05%   |
| 1334    | 12        | 5.08%   |
| 2133    | 9         | 3.81%   |
| 3266    | 7         | 2.97%   |
| 1333    | 6         | 2.54%   |
| 1067    | 5         | 2.12%   |
| Unknown | 5         | 2.12%   |
| 4267    | 4         | 1.69%   |
| 667     | 4         | 1.69%   |
| 4199    | 3         | 1.27%   |
| 800     | 3         | 1.27%   |
| 1776    | 2         | 0.85%   |
| 1066    | 2         | 0.85%   |
| 533     | 2         | 0.85%   |
| 8400    | 1         | 0.42%   |
| 4800    | 1         | 0.42%   |
| 4266    | 1         | 0.42%   |
| 3733    | 1         | 0.42%   |
| 975     | 1         | 0.42%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 1         | 33.33%  |
| Samsung Electronics | 1         | 33.33%  |
| Hewlett-Packard     | 1         | 33.33%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Seiko Epson L210 Series          | 1         | 33.33%  |
| Samsung M2020 Series             | 1         | 33.33%  |
| HP LaserJet Professional P 1102w | 1         | 33.33%  |

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
| Chicony Electronics                    | 102       | 21.29%  |
| IMC Networks                           | 97        | 20.25%  |
| Realtek Semiconductor                  | 40        | 8.35%   |
| Cheng Uei Precision Industry (Foxlink) | 33        | 6.89%   |
| Acer                                   | 32        | 6.68%   |
| Microdia                               | 27        | 5.64%   |
| Sunplus Innovation Technology          | 23        | 4.8%    |
| Quanta                                 | 22        | 4.59%   |
| Lite-On Technology                     | 17        | 3.55%   |
| Syntek                                 | 14        | 2.92%   |
| Silicon Motion                         | 14        | 2.92%   |
| Suyin                                  | 12        | 2.51%   |
| Ricoh                                  | 5         | 1.04%   |
| Logitech                               | 5         | 1.04%   |
| Apple                                  | 5         | 1.04%   |
| Alcor Micro                            | 5         | 1.04%   |
| Importek                               | 4         | 0.84%   |
| ALi                                    | 4         | 0.84%   |
| Z-Star Microelectronics                | 3         | 0.63%   |
| Samsung Electronics                    | 2         | 0.42%   |
| OmniVision Technologies                | 2         | 0.42%   |
| Lenovo                                 | 2         | 0.42%   |
| Y Media                                | 1         | 0.21%   |
| Sunplus Technology                     | 1         | 0.21%   |
| Sonix Technology                       | 1         | 0.21%   |
| Pixart Imaging                         | 1         | 0.21%   |
| KYE Systems (Mouse Systems)            | 1         | 0.21%   |
| Huawei Technologies                    | 1         | 0.21%   |
| Genesys Logic                          | 1         | 0.21%   |
| Arkmicro Technologies                  | 1         | 0.21%   |
| Alcorlink                              | 1         | 0.21%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                             | 42        | 8.77%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 25        | 5.22%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 16        | 3.34%   |
| Chicony Integrated Camera                                      | 12        | 2.51%   |
| Microdia Integrated_Webcam_HD                                  | 11        | 2.3%    |
| Chicony HP TrueVision HD Camera                                | 9         | 1.88%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 8         | 1.67%   |
| Realtek USB Camera                                             | 7         | 1.46%   |
| Lite-On HP Webcam                                              | 7         | 1.46%   |
| IMC Networks Integrated Camera                                 | 7         | 1.46%   |
| Chicony Lenovo EasyCamera                                      | 7         | 1.46%   |
| Acer Integrated Camera                                         | 7         | 1.46%   |
| Syntek Integrated Camera                                       | 6         | 1.25%   |
| Sunplus Integrated_Webcam_HD                                   | 6         | 1.25%   |
| Chicony HP Webcam                                              | 6         | 1.25%   |
| Chicony HD WebCam                                              | 6         | 1.25%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 6         | 1.25%   |
| Quanta HP Webcam                                               | 5         | 1.04%   |
| IMC Networks VGA UVC WebCam                                    | 5         | 1.04%   |
| Acer Lenovo EasyCamera                                         | 5         | 1.04%   |
| Syntek Lenovo EasyCamera                                       | 4         | 0.84%   |
| Syntek EasyCamera                                              | 4         | 0.84%   |
| Suyin 1.3M HD WebCam                                           | 4         | 0.84%   |
| Sunplus HD WebCam                                              | 4         | 0.84%   |
| Realtek USB2.0 VGA UVC WebCam                                  | 4         | 0.84%   |
| Realtek HP Truevision HD                                       | 4         | 0.84%   |
| Realtek HD WebCam                                              | 4         | 0.84%   |
| Lite-On HP HD Camera                                           | 4         | 0.84%   |
| IMC Networks EasyCamera                                        | 4         | 0.84%   |
| Acer HD Webcam                                                 | 4         | 0.84%   |
| Silicon Motion WebCam SC-13HDL11939N                           | 3         | 0.63%   |
| Realtek Lenovo EasyCamera                                      | 3         | 0.63%   |
| Realtek Integrated_Webcam_HD                                   | 3         | 0.63%   |
| Realtek Asus laptop camera                                     | 3         | 0.63%   |
| Quanta VGA WebCam                                              | 3         | 0.63%   |
| Quanta HD Webcam                                               | 3         | 0.63%   |
| Microdia Integrated Webcam                                     | 3         | 0.63%   |
| Lite-On Integrated Camera                                      | 3         | 0.63%   |
| IMC Networks HP TrueVision HD Camera                           | 3         | 0.63%   |
| Chicony HP Wide Vision HD Camera                               | 3         | 0.63%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 26        | 37.14%  |
| Synaptics                  | 15        | 21.43%  |
| Elan Microelectronics      | 12        | 17.14%  |
| Shenzhen Goodix Technology | 8         | 11.43%  |
| Upek                       | 4         | 5.71%   |
| LighTuning Technology      | 2         | 2.86%   |
| AuthenTec                  | 2         | 2.86%   |
| STMicroelectronics         | 1         | 1.43%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:Fingerprint                                                      | 11        | 15.71%  |
| Shenzhen Goodix  FingerPrint Device                                        | 6         | 8.57%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 7.14%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 5         | 7.14%   |
| Unknown                                                                    | 5         | 7.14%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 5.71%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 5.71%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 2.86%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.86%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 2.86%   |
| Synaptics  WBDI                                                            | 2         | 2.86%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 2.86%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 2.86%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 1.43%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.43%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.43%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 1.43%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 1.43%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 1.43%   |
| Synaptics WBDI Device                                                      | 1         | 1.43%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 1.43%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.43%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.43%   |
| Elan ELAN:ARM-M4                                                           | 1         | 1.43%   |
| AuthenTec AES2810                                                          | 1         | 1.43%   |
| AuthenTec AES1600                                                          | 1         | 1.43%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 6         | 40%     |
| Upek                  | 2         | 13.33%  |
| O2 Micro              | 2         | 13.33%  |
| Lenovo                | 2         | 13.33%  |
| Alcor Micro           | 2         | 13.33%  |
| Gemalto (was Gemplus) | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Broadcom 5880                                              | 4         | 26.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 2         | 13.33%  |
| Lenovo Integrated Smart Card Reader                        | 2         | 13.33%  |
| Broadcom BCM5880 Secure Applications Processor             | 2         | 13.33%  |
| Alcor Micro AU9540 Smartcard Reader                        | 2         | 13.33%  |
| O2 Micro Oz776 SmartCard Reader                            | 1         | 6.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 6.67%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer     | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 319       | 61.46%  |
| 1     | 169       | 32.56%  |
| 2     | 30        | 5.78%   |
| 7     | 1         | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 70        | 30.84%  |
| Net/wireless             | 48        | 21.15%  |
| Graphics card            | 39        | 17.18%  |
| Multimedia controller    | 20        | 8.81%   |
| Chipcard                 | 15        | 6.61%   |
| Bluetooth                | 13        | 5.73%   |
| Camera                   | 5         | 2.2%    |
| Communication controller | 4         | 1.76%   |
| Storage                  | 3         | 1.32%   |
| Sound                    | 3         | 1.32%   |
| Card reader              | 3         | 1.32%   |
| Net/ethernet             | 2         | 0.88%   |
| Flash memory             | 1         | 0.44%   |
| Firewire controller      | 1         | 0.44%   |

