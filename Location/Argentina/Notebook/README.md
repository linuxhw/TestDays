Linux in Argentina - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Argentina.

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

Total: 1634

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad S340-15API 81NC     | [7340c4abd7](https://linux-hardware.org/?probe=7340c4abd7) | Feb 01, 2024 |
| Lenovo        | V310-15ISK 80SY             | [a72292c97b](https://linux-hardware.org/?probe=a72292c97b) | Jan 31, 2024 |
| Dell          | Latitude 3420               | [100cfc0b60](https://linux-hardware.org/?probe=100cfc0b60) | Jan 29, 2024 |
| Positivo      | SF37405                     | [5955478d22](https://linux-hardware.org/?probe=5955478d22) | Jan 28, 2024 |
| Dell          | Latitude 5490               | [02270e4c1f](https://linux-hardware.org/?probe=02270e4c1f) | Jan 28, 2024 |
| Dell          | Latitude 5490               | [6e91f2be02](https://linux-hardware.org/?probe=6e91f2be02) | Jan 28, 2024 |
| NVN-ED01      | Unknown                     | [d97aa8bd00](https://linux-hardware.org/?probe=d97aa8bd00) | Jan 27, 2024 |
| Acer          | Aspire VX5-591G             | [3e5671c66a](https://linux-hardware.org/?probe=3e5671c66a) | Jan 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [2e2349c377](https://linux-hardware.org/?probe=2e2349c377) | Jan 24, 2024 |
| Novatech      | C141EK3-CI3TX               | [72b4b6b3ff](https://linux-hardware.org/?probe=72b4b6b3ff) | Jan 23, 2024 |
| Apple         | MacBookPro14,1              | [2be86e592f](https://linux-hardware.org/?probe=2be86e592f) | Jan 22, 2024 |
| HP            | Victus by Laptop 16-d0xx... | [11e78ca269](https://linux-hardware.org/?probe=11e78ca269) | Jan 20, 2024 |
| Lenovo        | V330-15IKB 81AX             | [b1151b6885](https://linux-hardware.org/?probe=b1151b6885) | Jan 19, 2024 |
| SPA CONDOR    | WM15-CCLPRO                 | [ad4f96e106](https://linux-hardware.org/?probe=ad4f96e106) | Jan 15, 2024 |
| Dell          | Latitude E5440              | [1af18a83ab](https://linux-hardware.org/?probe=1af18a83ab) | Jan 13, 2024 |
| ASRock        | X570 Steel Legend           | [2dc1dca01f](https://linux-hardware.org/?probe=2dc1dca01f) | Jan 13, 2024 |
| HP            | Laptop 15s-eq2xxx           | [b0705704b0](https://linux-hardware.org/?probe=b0705704b0) | Jan 11, 2024 |
| HP            | Laptop 15-bs0xx             | [c3c89654b8](https://linux-hardware.org/?probe=c3c89654b8) | Jan 10, 2024 |
| Sony          | VGN-CS190N                  | [2ac26516a6](https://linux-hardware.org/?probe=2ac26516a6) | Jan 09, 2024 |
| Samsung       | RV420/RV520/RV720/E3530/... | [565c995910](https://linux-hardware.org/?probe=565c995910) | Jan 08, 2024 |
| PCBOX         | PCB-GLW2                    | [bfc329b172](https://linux-hardware.org/?probe=bfc329b172) | Jan 08, 2024 |
| Samsung       | 940XFG                      | [9f39debbee](https://linux-hardware.org/?probe=9f39debbee) | Jan 07, 2024 |
| Gigabyte      | B660M DS3H DDR4             | [3e8e2de847](https://linux-hardware.org/?probe=3e8e2de847) | Jan 06, 2024 |
| Dell          | G5 5505                     | [fd284cda8a](https://linux-hardware.org/?probe=fd284cda8a) | Jan 04, 2024 |
| HP            | Pavilion dv7                | [dc31f854de](https://linux-hardware.org/?probe=dc31f854de) | Jan 04, 2024 |
| Dell          | Latitude 3420               | [2a844ff0bf](https://linux-hardware.org/?probe=2a844ff0bf) | Jan 03, 2024 |
| Lenovo        | IdeaPad Slim 3 14IAN8 82... | [c9c25e51c8](https://linux-hardware.org/?probe=c9c25e51c8) | Jan 02, 2024 |
| iQual         | NQ4X                        | [5c66dfd710](https://linux-hardware.org/?probe=5c66dfd710) | Jan 02, 2024 |
| HP            | Notebook                    | [f6e5af2da0](https://linux-hardware.org/?probe=f6e5af2da0) | Jan 02, 2024 |
| Dell          | Latitude 3420               | [775325daa6](https://linux-hardware.org/?probe=775325daa6) | Dec 31, 2023 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | [a55f917cf6](https://linux-hardware.org/?probe=a55f917cf6) | Dec 29, 2023 |
| Lenovo        | ThinkPad T410 2537BY8       | [0117a0ab48](https://linux-hardware.org/?probe=0117a0ab48) | Dec 29, 2023 |
| HP            | Pavilion dv7                | [c84d0249b0](https://linux-hardware.org/?probe=c84d0249b0) | Dec 27, 2023 |
| HP            | Pavilion dv7                | [a5fde2f725](https://linux-hardware.org/?probe=a5fde2f725) | Dec 27, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [925fd30c8a](https://linux-hardware.org/?probe=925fd30c8a) | Dec 27, 2023 |
| Dell          | Latitude 3420               | [d17deb16ca](https://linux-hardware.org/?probe=d17deb16ca) | Dec 26, 2023 |
| Juana Mans... | SF20GM7                     | [697c873386](https://linux-hardware.org/?probe=697c873386) | Dec 26, 2023 |
| Valve         | Jupiter                     | [6117a0c576](https://linux-hardware.org/?probe=6117a0c576) | Dec 25, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [771d35e2bc](https://linux-hardware.org/?probe=771d35e2bc) | Dec 25, 2023 |
| Lenovo        | G450 2949                   | [c8c0737175](https://linux-hardware.org/?probe=c8c0737175) | Dec 20, 2023 |
| Dell          | Latitude 3420               | [35a3241602](https://linux-hardware.org/?probe=35a3241602) | Dec 20, 2023 |
| Clevo         | W240BU                      | [a0d883bb3d](https://linux-hardware.org/?probe=a0d883bb3d) | Dec 20, 2023 |
| Dell          | Inspiron 5570               | [55a83cf2cb](https://linux-hardware.org/?probe=55a83cf2cb) | Dec 19, 2023 |
| System76      | Lemur Pro                   | [85b70f2fdb](https://linux-hardware.org/?probe=85b70f2fdb) | Dec 18, 2023 |
| Dell          | Latitude 3420               | [59784d2788](https://linux-hardware.org/?probe=59784d2788) | Dec 18, 2023 |
| Dell          | Inspiron 7375               | [52f641256c](https://linux-hardware.org/?probe=52f641256c) | Dec 18, 2023 |
| System76      | Lemur Pro                   | [6ec95bc2bc](https://linux-hardware.org/?probe=6ec95bc2bc) | Dec 17, 2023 |
| Lenovo        | ThinkPad T440p 20AWA0W9A... | [e97e362650](https://linux-hardware.org/?probe=e97e362650) | Dec 17, 2023 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | [3834ee3d70](https://linux-hardware.org/?probe=3834ee3d70) | Dec 15, 2023 |
| Acer          | Aspire A315-22              | [e1deaf47e9](https://linux-hardware.org/?probe=e1deaf47e9) | Dec 14, 2023 |
| Lenovo        | ThinkPad X201 3626W1P       | [bf54dfd215](https://linux-hardware.org/?probe=bf54dfd215) | Dec 13, 2023 |
| Lenovo        | ThinkPad X201 3626W1P       | [695a85cd79](https://linux-hardware.org/?probe=695a85cd79) | Dec 12, 2023 |
| NVN-ED01      | Unknown                     | [3705f36f2b](https://linux-hardware.org/?probe=3705f36f2b) | Dec 11, 2023 |
| HP            | Compaq 515                  | [025d4116ed](https://linux-hardware.org/?probe=025d4116ed) | Dec 09, 2023 |
| Lenovo        | G470 20078                  | [190ba583a3](https://linux-hardware.org/?probe=190ba583a3) | Dec 09, 2023 |
| System76      | Lemur Pro                   | [c8313d9e6f](https://linux-hardware.org/?probe=c8313d9e6f) | Dec 07, 2023 |
| Exo           | Smart XQ7                   | [f1ebc77dfc](https://linux-hardware.org/?probe=f1ebc77dfc) | Dec 05, 2023 |
| Exo           | Smart XQ7                   | [3d56eb720e](https://linux-hardware.org/?probe=3d56eb720e) | Dec 05, 2023 |
| Lenovo        | IdeaPad Yoga 13 20175       | [8d46bb6a3c](https://linux-hardware.org/?probe=8d46bb6a3c) | Dec 05, 2023 |
| ASUSTek       | GL553VD                     | [578cbbda94](https://linux-hardware.org/?probe=578cbbda94) | Dec 05, 2023 |
| Lenovo        | ThinkPad T480 20L6S3ED18    | [03866b12cd](https://linux-hardware.org/?probe=03866b12cd) | Dec 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d25f6b4dd3](https://linux-hardware.org/?probe=d25f6b4dd3) | Dec 02, 2023 |
| Kelyx Arge... | Kelyx KL3450                | [0d6ca3bd1a](https://linux-hardware.org/?probe=0d6ca3bd1a) | Nov 30, 2023 |
| Lenovo        | IdeaPad Slim 3 14IAN8 82... | [7eed706de5](https://linux-hardware.org/?probe=7eed706de5) | Nov 26, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BV0... | [06170c8841](https://linux-hardware.org/?probe=06170c8841) | Nov 25, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [be0df0a38d](https://linux-hardware.org/?probe=be0df0a38d) | Nov 25, 2023 |
| System76      | Lemur Pro                   | [45a6298cb5](https://linux-hardware.org/?probe=45a6298cb5) | Nov 22, 2023 |
| Grupo Nucl... | Eurocase MB40               | [aaedd81604](https://linux-hardware.org/?probe=aaedd81604) | Nov 21, 2023 |
| Grupo Nucl... | Eurocase MB40               | [6c601d96d9](https://linux-hardware.org/?probe=6c601d96d9) | Nov 21, 2023 |
| Juana Mans... | SF20GM7                     | [82c49fc608](https://linux-hardware.org/?probe=82c49fc608) | Nov 19, 2023 |
| ASUSTek       | N56VB                       | [3c0851b65b](https://linux-hardware.org/?probe=3c0851b65b) | Nov 17, 2023 |
| Samsung       | R430/R480/R440              | [0c90ddcfcf](https://linux-hardware.org/?probe=0c90ddcfcf) | Nov 15, 2023 |
| BANGHO        | 1025                        | [d1d51fc17a](https://linux-hardware.org/?probe=d1d51fc17a) | Nov 15, 2023 |
| Lenovo        | G550 2958                   | [b158de590e](https://linux-hardware.org/?probe=b158de590e) | Nov 14, 2023 |
| Lenovo        | G550 2958                   | [25455f055b](https://linux-hardware.org/?probe=25455f055b) | Nov 14, 2023 |
| BANGHO        | 1025                        | [97b39ed05d](https://linux-hardware.org/?probe=97b39ed05d) | Nov 13, 2023 |
| Advantec      | CX23500W                    | [30382192a1](https://linux-hardware.org/?probe=30382192a1) | Nov 11, 2023 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | [46e69016d1](https://linux-hardware.org/?probe=46e69016d1) | Nov 11, 2023 |
| ASUSTek       | N56VB                       | [2b545ce55f](https://linux-hardware.org/?probe=2b545ce55f) | Nov 10, 2023 |
| Lenovo        | IdeaPad 300-15IBR 80M3      | [1e2c26c06a](https://linux-hardware.org/?probe=1e2c26c06a) | Nov 09, 2023 |
| Exo           | Intel powered classmate ... | [135b2008b7](https://linux-hardware.org/?probe=135b2008b7) | Nov 09, 2023 |
| Sony          | SVF15N17CXB                 | [e8497bf6f6](https://linux-hardware.org/?probe=e8497bf6f6) | Nov 08, 2023 |
| System76      | Lemur Pro                   | [92d1345459](https://linux-hardware.org/?probe=92d1345459) | Nov 07, 2023 |
| Lenovo        | S145-15IWL 81MV             | [d38fdaf0eb](https://linux-hardware.org/?probe=d38fdaf0eb) | Nov 04, 2023 |
| Lenovo        | G450 2949                   | [3f631dfb6e](https://linux-hardware.org/?probe=3f631dfb6e) | Nov 04, 2023 |
| ASUSTek       | X551MA                      | [43a85c50bf](https://linux-hardware.org/?probe=43a85c50bf) | Nov 02, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [2d1120d99a](https://linux-hardware.org/?probe=2d1120d99a) | Nov 02, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [59d963de5b](https://linux-hardware.org/?probe=59d963de5b) | Nov 02, 2023 |
| HP            | Pavilion g6                 | [8c9de8be4f](https://linux-hardware.org/?probe=8c9de8be4f) | Nov 02, 2023 |
| HP            | Pavilion g6                 | [c35f9a55aa](https://linux-hardware.org/?probe=c35f9a55aa) | Nov 02, 2023 |
| Novatech      | C141EK5-CI5TX               | [ee65041e06](https://linux-hardware.org/?probe=ee65041e06) | Nov 01, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [af59fd3af9](https://linux-hardware.org/?probe=af59fd3af9) | Nov 01, 2023 |
| System76      | Lemur Pro                   | [847ae1ea8d](https://linux-hardware.org/?probe=847ae1ea8d) | Nov 01, 2023 |
| ASUSTek       | N56VB                       | [9775caad00](https://linux-hardware.org/?probe=9775caad00) | Oct 31, 2023 |
| ASUSTek       | N56VB                       | [45280b44d0](https://linux-hardware.org/?probe=45280b44d0) | Oct 31, 2023 |
| Lenovo        | ThinkPad X230 2325T55       | [bb4d04c61d](https://linux-hardware.org/?probe=bb4d04c61d) | Oct 31, 2023 |
| Dell          | Precision M6800             | [a5e2100522](https://linux-hardware.org/?probe=a5e2100522) | Oct 29, 2023 |
| System76      | Lemur Pro                   | [e5b2c76907](https://linux-hardware.org/?probe=e5b2c76907) | Oct 27, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [acc4051b9c](https://linux-hardware.org/?probe=acc4051b9c) | Oct 26, 2023 |
| Exo           | Smart Serie R               | [d68b300ca7](https://linux-hardware.org/?probe=d68b300ca7) | Oct 26, 2023 |
| Novatech      | C141EK5-CI5TX               | [71f7f1372a](https://linux-hardware.org/?probe=71f7f1372a) | Oct 26, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [a71b3ca73a](https://linux-hardware.org/?probe=a71b3ca73a) | Oct 24, 2023 |
| Toshiba       | Satellite L635              | [6bc7726e0e](https://linux-hardware.org/?probe=6bc7726e0e) | Oct 22, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [2fb4202e3f](https://linux-hardware.org/?probe=2fb4202e3f) | Oct 21, 2023 |
| BANGHO        | M7x0K                       | [1f72eb6b91](https://linux-hardware.org/?probe=1f72eb6b91) | Oct 20, 2023 |
| Positivo      | AT300b                      | [a39989b55b](https://linux-hardware.org/?probe=a39989b55b) | Oct 18, 2023 |
| Juana Mans... | SF20GM7                     | [ea7e37eb5d](https://linux-hardware.org/?probe=ea7e37eb5d) | Oct 17, 2023 |
| BANGHO        | MAX G0101                   | [b0adb13b97](https://linux-hardware.org/?probe=b0adb13b97) | Oct 16, 2023 |
| System76      | Lemur Pro                   | [f969d7a459](https://linux-hardware.org/?probe=f969d7a459) | Oct 15, 2023 |
| Valve         | Jupiter                     | [0d088b07f0](https://linux-hardware.org/?probe=0d088b07f0) | Oct 14, 2023 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [a03109d57a](https://linux-hardware.org/?probe=a03109d57a) | Oct 14, 2023 |
| Novatech      | C141EK5-CI5TX               | [798d514e79](https://linux-hardware.org/?probe=798d514e79) | Oct 13, 2023 |
| Compal        | PCW20                       | [94330b69a9](https://linux-hardware.org/?probe=94330b69a9) | Oct 11, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [801a2a4abf](https://linux-hardware.org/?probe=801a2a4abf) | Oct 09, 2023 |
| HP            | Laptop 15-ef2xxx            | [ad00ca7536](https://linux-hardware.org/?probe=ad00ca7536) | Oct 07, 2023 |
| Lenovo        | 100-14IBY 80R7              | [f6389f0244](https://linux-hardware.org/?probe=f6389f0244) | Oct 06, 2023 |
| Exo           | Smart Serie L               | [812041d985](https://linux-hardware.org/?probe=812041d985) | Oct 05, 2023 |
| Unknown       | Unknown                     | [a6849f7516](https://linux-hardware.org/?probe=a6849f7516) | Oct 03, 2023 |
| HUAWEI        | NBD-WXX9                    | [b978b6c62f](https://linux-hardware.org/?probe=b978b6c62f) | Oct 03, 2023 |
| ASUSTek       | X541UAK                     | [a8875273fb](https://linux-hardware.org/?probe=a8875273fb) | Oct 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [4462bfcb6d](https://linux-hardware.org/?probe=4462bfcb6d) | Oct 02, 2023 |
| System76      | Lemur Pro                   | [8486fb3080](https://linux-hardware.org/?probe=8486fb3080) | Oct 02, 2023 |
| Juana Mans... | SF20GM7                     | [b2b359c659](https://linux-hardware.org/?probe=b2b359c659) | Sep 30, 2023 |
| ASUSTek       | Z450LA                      | [afa96a084e](https://linux-hardware.org/?probe=afa96a084e) | Sep 30, 2023 |
| Juana Mans... | SF20GM7                     | [b4a58da74c](https://linux-hardware.org/?probe=b4a58da74c) | Sep 30, 2023 |
| Juana Mans... | SF20GM7                     | [ccb9b4e795](https://linux-hardware.org/?probe=ccb9b4e795) | Sep 30, 2023 |
| BANGHO        | MAX G0101                   | [b867aa1824](https://linux-hardware.org/?probe=b867aa1824) | Sep 30, 2023 |
| HP            | Pavilion dv6                | [e2560d6378](https://linux-hardware.org/?probe=e2560d6378) | Sep 30, 2023 |
| ASUSTek       | ZenBook UX425QA_UM425QA     | [306bc123c4](https://linux-hardware.org/?probe=306bc123c4) | Sep 29, 2023 |
| HP            | 240 G8 Notebook PC          | [af9350dd38](https://linux-hardware.org/?probe=af9350dd38) | Sep 28, 2023 |
| HP            | 240 G8 Notebook PC          | [d40624877e](https://linux-hardware.org/?probe=d40624877e) | Sep 28, 2023 |
| System76      | Lemur Pro                   | [6013ab7f8a](https://linux-hardware.org/?probe=6013ab7f8a) | Sep 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [92eb612b66](https://linux-hardware.org/?probe=92eb612b66) | Sep 26, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [742cfeafb0](https://linux-hardware.org/?probe=742cfeafb0) | Sep 26, 2023 |
| AIR           | CX28000W                    | [b4a65a0403](https://linux-hardware.org/?probe=b4a65a0403) | Sep 26, 2023 |
| Juana Mans... | SF20GM7                     | [355aaa1b07](https://linux-hardware.org/?probe=355aaa1b07) | Sep 26, 2023 |
| Dell          | Inspiron 5459               | [1095c770f0](https://linux-hardware.org/?probe=1095c770f0) | Sep 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [a834cee874](https://linux-hardware.org/?probe=a834cee874) | Sep 24, 2023 |
| Dell          | Latitude 5420               | [0e22f551b9](https://linux-hardware.org/?probe=0e22f551b9) | Sep 24, 2023 |
| Dell          | Latitude 3410               | [c5473f5f6c](https://linux-hardware.org/?probe=c5473f5f6c) | Sep 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [c4b66b8208](https://linux-hardware.org/?probe=c4b66b8208) | Sep 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [290e0fd96b](https://linux-hardware.org/?probe=290e0fd96b) | Sep 21, 2023 |
| ASUSTek       | X455LD                      | [1e79e3536c](https://linux-hardware.org/?probe=1e79e3536c) | Sep 20, 2023 |
| Apple         | MacBookPro12,1              | [0c71c0240e](https://linux-hardware.org/?probe=0c71c0240e) | Sep 20, 2023 |
| ASUSTek       | N56VB                       | [e4dae2f7c8](https://linux-hardware.org/?probe=e4dae2f7c8) | Sep 19, 2023 |
| ASUSTek       | N56VB                       | [79e8bd0911](https://linux-hardware.org/?probe=79e8bd0911) | Sep 19, 2023 |
| Lenovo        | G50-30 80G0                 | [fa9bd484cd](https://linux-hardware.org/?probe=fa9bd484cd) | Sep 17, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [2d0ccc33ef](https://linux-hardware.org/?probe=2d0ccc33ef) | Sep 15, 2023 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [e793b9e3d9](https://linux-hardware.org/?probe=e793b9e3d9) | Sep 12, 2023 |
| Acer          | Aspire A315-33              | [7c04fe4f52](https://linux-hardware.org/?probe=7c04fe4f52) | Sep 10, 2023 |
| Lenovo        | V330-15IKB 81AX             | [edb578f198](https://linux-hardware.org/?probe=edb578f198) | Sep 09, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [2385447c50](https://linux-hardware.org/?probe=2385447c50) | Sep 07, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [eb05baece5](https://linux-hardware.org/?probe=eb05baece5) | Sep 05, 2023 |
| System76      | Lemur Pro                   | [9ea11da090](https://linux-hardware.org/?probe=9ea11da090) | Sep 04, 2023 |
| Dell          | Latitude 5285               | [f1f48163f3](https://linux-hardware.org/?probe=f1f48163f3) | Sep 02, 2023 |
| SiS           | M672 Board SI94B-20+SI96... | [4b309ad43c](https://linux-hardware.org/?probe=4b309ad43c) | Sep 02, 2023 |
| Intel         | powered classmate PC        | [f852524db2](https://linux-hardware.org/?probe=f852524db2) | Sep 01, 2023 |
| BGH           | C46G                        | [c56474510e](https://linux-hardware.org/?probe=c56474510e) | Sep 01, 2023 |
| BANGHO        | GM-15Z12 RTX3060 i7         | [4e77460452](https://linux-hardware.org/?probe=4e77460452) | Aug 31, 2023 |
| HP            | 3115m                       | [85325be2ba](https://linux-hardware.org/?probe=85325be2ba) | Aug 31, 2023 |
| Dell          | System Inspiron N7110       | [c222da255e](https://linux-hardware.org/?probe=c222da255e) | Aug 31, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [33b5107930](https://linux-hardware.org/?probe=33b5107930) | Aug 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [d169572a6b](https://linux-hardware.org/?probe=d169572a6b) | Aug 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2bd35d44f1](https://linux-hardware.org/?probe=2bd35d44f1) | Aug 29, 2023 |
| ASUSTek       | X580VD                      | [c8bed4c7e6](https://linux-hardware.org/?probe=c8bed4c7e6) | Aug 29, 2023 |
| NSX           | SB142G                      | [43b576c576](https://linux-hardware.org/?probe=43b576c576) | Aug 27, 2023 |
| Lenovo        | ThinkPad E495 20NES0KM00    | [783db5b84d](https://linux-hardware.org/?probe=783db5b84d) | Aug 23, 2023 |
| Lenovo        | G450 2949                   | [a8ec62d51f](https://linux-hardware.org/?probe=a8ec62d51f) | Aug 21, 2023 |
| Lenovo        | G450 2949                   | [64d2950d7a](https://linux-hardware.org/?probe=64d2950d7a) | Aug 21, 2023 |
| Dell          | Inspiron 5447               | [811b2451ba](https://linux-hardware.org/?probe=811b2451ba) | Aug 20, 2023 |
| Dell          | Vostro 3405                 | [2ba4151315](https://linux-hardware.org/?probe=2ba4151315) | Aug 19, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [6249529a81](https://linux-hardware.org/?probe=6249529a81) | Aug 18, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [0ba07cce6b](https://linux-hardware.org/?probe=0ba07cce6b) | Aug 17, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [06aebc0204](https://linux-hardware.org/?probe=06aebc0204) | Aug 17, 2023 |
| System76      | Lemur Pro                   | [af3b387574](https://linux-hardware.org/?probe=af3b387574) | Aug 16, 2023 |
| Acer          | Aspire A315-33              | [19221dff96](https://linux-hardware.org/?probe=19221dff96) | Aug 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [15b52f0cde](https://linux-hardware.org/?probe=15b52f0cde) | Aug 14, 2023 |
| BANGHO        | MOV                         | [db4769bd96](https://linux-hardware.org/?probe=db4769bd96) | Aug 13, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | [3bb3eaed7b](https://linux-hardware.org/?probe=3bb3eaed7b) | Aug 13, 2023 |
| BANGHO        | BES T5                      | [9631e13d8b](https://linux-hardware.org/?probe=9631e13d8b) | Aug 12, 2023 |
| A-DATA Tec... | XENIA 15                    | [73f0314b31](https://linux-hardware.org/?probe=73f0314b31) | Aug 12, 2023 |
| A-DATA Tec... | XENIA 15                    | [d1a19f992d](https://linux-hardware.org/?probe=d1a19f992d) | Aug 12, 2023 |
| Lenovo        | B50-70 20384                | [607103b8f5](https://linux-hardware.org/?probe=607103b8f5) | Aug 11, 2023 |
| Lenovo        | V310-15ISK 80SY             | [88fcbf292a](https://linux-hardware.org/?probe=88fcbf292a) | Aug 10, 2023 |
| BANGHO        | MAX L5                      | [4661b7a0f7](https://linux-hardware.org/?probe=4661b7a0f7) | Aug 10, 2023 |
| Acer          | Aspire A515-57              | [b95e28ab5d](https://linux-hardware.org/?probe=b95e28ab5d) | Aug 09, 2023 |
| DEXP          | Aquilon C14                 | [08d7c1d923](https://linux-hardware.org/?probe=08d7c1d923) | Aug 09, 2023 |
| BANGHO        | MAX L5                      | [b21781af81](https://linux-hardware.org/?probe=b21781af81) | Aug 08, 2023 |
| Acer          | Aspire 5551                 | [4db1866796](https://linux-hardware.org/?probe=4db1866796) | Aug 06, 2023 |
| Lenovo        | ThinkPad T430 2349DS5       | [763d98ad86](https://linux-hardware.org/?probe=763d98ad86) | Aug 06, 2023 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [dbbf788e9d](https://linux-hardware.org/?probe=dbbf788e9d) | Aug 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | [e2dee68ce7](https://linux-hardware.org/?probe=e2dee68ce7) | Aug 05, 2023 |
| HP            | Pavilion g6                 | [fafbd706de](https://linux-hardware.org/?probe=fafbd706de) | Aug 05, 2023 |
| Toshiba       | Satellite L505              | [bab52bec2c](https://linux-hardware.org/?probe=bab52bec2c) | Aug 04, 2023 |
| GFAST         | N150                        | [bccc2874df](https://linux-hardware.org/?probe=bccc2874df) | Aug 04, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [8767df67f4](https://linux-hardware.org/?probe=8767df67f4) | Aug 02, 2023 |
| System76      | Lemur Pro                   | [1ba844bc69](https://linux-hardware.org/?probe=1ba844bc69) | Aug 01, 2023 |
| System76      | Lemur Pro                   | [e019d33faf](https://linux-hardware.org/?probe=e019d33faf) | Aug 01, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [483fbca861](https://linux-hardware.org/?probe=483fbca861) | Jul 31, 2023 |
| HP            | Pavilion g7                 | [18eb2a894b](https://linux-hardware.org/?probe=18eb2a894b) | Jul 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | [f321614376](https://linux-hardware.org/?probe=f321614376) | Jul 25, 2023 |
| Positivo      | G800                        | [5dd0f188f8](https://linux-hardware.org/?probe=5dd0f188f8) | Jul 25, 2023 |
| Dell          | Latitude E5410              | [e26148754b](https://linux-hardware.org/?probe=e26148754b) | Jul 25, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | [fe2ff0c21f](https://linux-hardware.org/?probe=fe2ff0c21f) | Jul 23, 2023 |
| A-DATA Tec... | XENIA 15                    | [21edb88f94](https://linux-hardware.org/?probe=21edb88f94) | Jul 23, 2023 |
| A-DATA Tec... | XENIA 15                    | [9c64742080](https://linux-hardware.org/?probe=9c64742080) | Jul 23, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [be58f943df](https://linux-hardware.org/?probe=be58f943df) | Jul 22, 2023 |
| Acer          | Aspire A515-52              | [243f0a8cab](https://linux-hardware.org/?probe=243f0a8cab) | Jul 20, 2023 |
| Acer          | Aspire A515-52              | [f310abe0bb](https://linux-hardware.org/?probe=f310abe0bb) | Jul 20, 2023 |
| Dell          | Latitude 3520               | [7037e164fd](https://linux-hardware.org/?probe=7037e164fd) | Jul 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a5359c62e0](https://linux-hardware.org/?probe=a5359c62e0) | Jul 20, 2023 |
| Dell          | Latitude 3520               | [e41e794381](https://linux-hardware.org/?probe=e41e794381) | Jul 20, 2023 |
| Dell          | Latitude 3520               | [bd2589c749](https://linux-hardware.org/?probe=bd2589c749) | Jul 20, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [2f067394f6](https://linux-hardware.org/?probe=2f067394f6) | Jul 19, 2023 |
| Dell          | XPS L501X                   | [0879ff6b9d](https://linux-hardware.org/?probe=0879ff6b9d) | Jul 18, 2023 |
| Lenovo        | ThinkPad Edge E430 3254T... | [2294cf035b](https://linux-hardware.org/?probe=2294cf035b) | Jul 16, 2023 |
| Lenovo        | ThinkPad Edge E430 3254T... | [b26a172e92](https://linux-hardware.org/?probe=b26a172e92) | Jul 16, 2023 |
| Coradir       | Coradir/ES10IS5             | [571080a9d5](https://linux-hardware.org/?probe=571080a9d5) | Jul 14, 2023 |
| AIR           | CX30500                     | [ee0b27d980](https://linux-hardware.org/?probe=ee0b27d980) | Jul 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d16093199e](https://linux-hardware.org/?probe=d16093199e) | Jul 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1a0add8887](https://linux-hardware.org/?probe=1a0add8887) | Jul 11, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [0549d09ceb](https://linux-hardware.org/?probe=0549d09ceb) | Jul 11, 2023 |
| Acer          | SF714-52T                   | [97b079be51](https://linux-hardware.org/?probe=97b079be51) | Jul 10, 2023 |
| Dell          | Latitude 3490               | [67de502259](https://linux-hardware.org/?probe=67de502259) | Jul 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | [978a7ef06f](https://linux-hardware.org/?probe=978a7ef06f) | Jul 08, 2023 |
| Alienware     | 17                          | [b8b8032da9](https://linux-hardware.org/?probe=b8b8032da9) | Jul 08, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [7cbaa33271](https://linux-hardware.org/?probe=7cbaa33271) | Jul 07, 2023 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | [dcf48c7be4](https://linux-hardware.org/?probe=dcf48c7be4) | Jul 07, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | [ab0a17ec87](https://linux-hardware.org/?probe=ab0a17ec87) | Jul 04, 2023 |
| Lenovo        | IdeaPad 310S-14AST 80UL     | [f897f42089](https://linux-hardware.org/?probe=f897f42089) | Jul 03, 2023 |
| Acer          | Aspire A515-52              | [3861c91dd4](https://linux-hardware.org/?probe=3861c91dd4) | Jul 02, 2023 |
| Acer          | Aspire A515-52              | [ab8898b9f3](https://linux-hardware.org/?probe=ab8898b9f3) | Jul 02, 2023 |
| HP            | Pavilion g6                 | [5d632e53c6](https://linux-hardware.org/?probe=5d632e53c6) | Jun 30, 2023 |
| Acer          | Aspire 5551                 | [0b4df3165f](https://linux-hardware.org/?probe=0b4df3165f) | Jun 30, 2023 |
| BANGHO        | BES G0304                   | [7b9e2a7570](https://linux-hardware.org/?probe=7b9e2a7570) | Jun 30, 2023 |
| Dell          | Latitude E6400              | [a5af3e134e](https://linux-hardware.org/?probe=a5af3e134e) | Jun 30, 2023 |
| Acer          | Aspire 5551                 | [73a0f2fd37](https://linux-hardware.org/?probe=73a0f2fd37) | Jun 30, 2023 |
| Dell          | Latitude E4310              | [725b89a524](https://linux-hardware.org/?probe=725b89a524) | Jun 30, 2023 |
| HP            | Pavilion g6                 | [ef275e1249](https://linux-hardware.org/?probe=ef275e1249) | Jun 29, 2023 |
| Lenovo        | ThinkBook 14s-IML 20RS      | [e3d095fc9f](https://linux-hardware.org/?probe=e3d095fc9f) | Jun 29, 2023 |
| ASUSTek       | K53E                        | [8e1f4ee31f](https://linux-hardware.org/?probe=8e1f4ee31f) | Jun 27, 2023 |
| Coradir       | Coradir/ES10IS5             | [d2d1f5b2a5](https://linux-hardware.org/?probe=d2d1f5b2a5) | Jun 27, 2023 |
| Coradir       | Coradir/ES10IS5             | [d6a1e61945](https://linux-hardware.org/?probe=d6a1e61945) | Jun 26, 2023 |
| Lenovo        | V310-15ISK 80SY             | [824c084cce](https://linux-hardware.org/?probe=824c084cce) | Jun 26, 2023 |
| Dell          | Inspiron N4030              | [a6c7992001](https://linux-hardware.org/?probe=a6c7992001) | Jun 24, 2023 |
| Dell          | Inspiron N4030              | [89116ab6be](https://linux-hardware.org/?probe=89116ab6be) | Jun 24, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [798efb2213](https://linux-hardware.org/?probe=798efb2213) | Jun 24, 2023 |
| Acer          | Aspire A315-59              | [bd39971c52](https://linux-hardware.org/?probe=bd39971c52) | Jun 23, 2023 |
| Dell          | Latitude 3520               | [ada304545e](https://linux-hardware.org/?probe=ada304545e) | Jun 22, 2023 |
| Acer          | Aspire A515-52              | [43ee82258d](https://linux-hardware.org/?probe=43ee82258d) | Jun 21, 2023 |
| Acer          | Aspire A515-52              | [b2d464d2bc](https://linux-hardware.org/?probe=b2d464d2bc) | Jun 21, 2023 |
| Toshiba       | Satellite-L845              | [cfe5a81354](https://linux-hardware.org/?probe=cfe5a81354) | Jun 18, 2023 |
| Dell          | Inspiron 5535               | [88a1d18ea0](https://linux-hardware.org/?probe=88a1d18ea0) | Jun 17, 2023 |
| BANGHO        | MAX L5                      | [47f4fd7822](https://linux-hardware.org/?probe=47f4fd7822) | Jun 17, 2023 |
| BANGHO        | MAX L5                      | [5027ce5059](https://linux-hardware.org/?probe=5027ce5059) | Jun 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [fe65868ffe](https://linux-hardware.org/?probe=fe65868ffe) | Jun 15, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [affb2b7e01](https://linux-hardware.org/?probe=affb2b7e01) | Jun 15, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | [850c71b72c](https://linux-hardware.org/?probe=850c71b72c) | Jun 15, 2023 |
| Lenovo        | G470 20078                  | [cc77cad35d](https://linux-hardware.org/?probe=cc77cad35d) | Jun 14, 2023 |
| Juana Mans... | SF20GM7                     | [7ffe62cc40](https://linux-hardware.org/?probe=7ffe62cc40) | Jun 14, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [e676294e36](https://linux-hardware.org/?probe=e676294e36) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0d07b35562](https://linux-hardware.org/?probe=0d07b35562) | Jun 11, 2023 |
| Exo           | Smart Serie LT              | [bbecad1cea](https://linux-hardware.org/?probe=bbecad1cea) | Jun 10, 2023 |
| HP            | OMEN by Laptop 15-ce0xx     | [fd3b70424a](https://linux-hardware.org/?probe=fd3b70424a) | Jun 09, 2023 |
| HP            | Notebook                    | [e292bb9d5a](https://linux-hardware.org/?probe=e292bb9d5a) | Jun 09, 2023 |
| HP            | Laptop 15-ef1xxx            | [931b9e2b05](https://linux-hardware.org/?probe=931b9e2b05) | Jun 08, 2023 |
| Intel         | HURONRIVER                  | [57035a777c](https://linux-hardware.org/?probe=57035a777c) | Jun 07, 2023 |
| Lenovo        | B570 HuronRiver Platform    | [43cffb0d0f](https://linux-hardware.org/?probe=43cffb0d0f) | Jun 04, 2023 |
| Lenovo        | B570 HuronRiver Platform    | [cef2bf28c9](https://linux-hardware.org/?probe=cef2bf28c9) | Jun 04, 2023 |
| Lenovo        | ThinkPad T430 2349DS5       | [e6492d37d8](https://linux-hardware.org/?probe=e6492d37d8) | Jun 03, 2023 |
| HP            | Split 13 x2 PC              | [5e3ae671cc](https://linux-hardware.org/?probe=5e3ae671cc) | Jun 01, 2023 |
| ASUSTek       | GL553VD                     | [4a2e70149f](https://linux-hardware.org/?probe=4a2e70149f) | Jun 01, 2023 |
| ASUSTek       | GL553VD                     | [b8fb5e55bc](https://linux-hardware.org/?probe=b8fb5e55bc) | Jun 01, 2023 |
| Positivo      | C500                        | [8dba4589fe](https://linux-hardware.org/?probe=8dba4589fe) | Jun 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [1ea9c869ff](https://linux-hardware.org/?probe=1ea9c869ff) | May 31, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [b8e68f9227](https://linux-hardware.org/?probe=b8e68f9227) | May 29, 2023 |
| PCBOX         | Kant                        | [1e2f772d05](https://linux-hardware.org/?probe=1e2f772d05) | May 29, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [184afbb9c3](https://linux-hardware.org/?probe=184afbb9c3) | May 26, 2023 |
| Lenovo        | ThinkPad E495 20NES0RS00    | [6f507e12bc](https://linux-hardware.org/?probe=6f507e12bc) | May 25, 2023 |
| Dell          | Latitude 5420               | [a4690b7476](https://linux-hardware.org/?probe=a4690b7476) | May 25, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | [82183f4762](https://linux-hardware.org/?probe=82183f4762) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [8fb981666f](https://linux-hardware.org/?probe=8fb981666f) | May 24, 2023 |
| Lenovo        | IdeaPad Y700-17ISK 80Q0     | [e250801798](https://linux-hardware.org/?probe=e250801798) | May 23, 2023 |
| Lenovo        | ThinkPad T450 20BUS0100G    | [069d442d0d](https://linux-hardware.org/?probe=069d442d0d) | May 22, 2023 |
| Lenovo        | G550 2958                   | [cb61728cb7](https://linux-hardware.org/?probe=cb61728cb7) | May 22, 2023 |
| HP            | Laptop 14-cf2xxx            | [c2d03bd839](https://linux-hardware.org/?probe=c2d03bd839) | May 22, 2023 |
| Lenovo        | G550 2958                   | [1dda8d01ad](https://linux-hardware.org/?probe=1dda8d01ad) | May 20, 2023 |
| Lenovo        | G550 2958                   | [fe4d0a2ec3](https://linux-hardware.org/?probe=fe4d0a2ec3) | May 20, 2023 |
| ASUSTek       | N56VB                       | [b7655822d2](https://linux-hardware.org/?probe=b7655822d2) | May 19, 2023 |
| Lenovo        | IdeaPad U530 Touch 20289    | [72e254e4ee](https://linux-hardware.org/?probe=72e254e4ee) | May 19, 2023 |
| Philco        | PHN14C                      | [4efea72b8f](https://linux-hardware.org/?probe=4efea72b8f) | May 18, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [1713b94d26](https://linux-hardware.org/?probe=1713b94d26) | May 12, 2023 |
| Unknown       | M-140BI3                    | [eb6507c151](https://linux-hardware.org/?probe=eb6507c151) | May 11, 2023 |
| ASUSTek       | N56VB                       | [e914b76fef](https://linux-hardware.org/?probe=e914b76fef) | May 10, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [35750a650a](https://linux-hardware.org/?probe=35750a650a) | May 10, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [813acd1225](https://linux-hardware.org/?probe=813acd1225) | May 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [8d1f016621](https://linux-hardware.org/?probe=8d1f016621) | May 08, 2023 |
| Toshiba       | Satellite L50-C             | [67b9224d87](https://linux-hardware.org/?probe=67b9224d87) | May 07, 2023 |
| Acer          | Aspire A315-23              | [2e4e7c801d](https://linux-hardware.org/?probe=2e4e7c801d) | May 05, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [218ba5d6a5](https://linux-hardware.org/?probe=218ba5d6a5) | May 04, 2023 |
| iQual         | NQ4X                        | [256ae92f40](https://linux-hardware.org/?probe=256ae92f40) | May 02, 2023 |
| HP            | Unknown                     | [bba45b8ff0](https://linux-hardware.org/?probe=bba45b8ff0) | Apr 27, 2023 |
| Dell          | Latitude E5410              | [1efb62110c](https://linux-hardware.org/?probe=1efb62110c) | Apr 27, 2023 |
| Dell          | Latitude E5410              | [02be2c8f0b](https://linux-hardware.org/?probe=02be2c8f0b) | Apr 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9e926f5c65](https://linux-hardware.org/?probe=9e926f5c65) | Apr 24, 2023 |
| Dell          | Inspiron 5537               | [971055139b](https://linux-hardware.org/?probe=971055139b) | Apr 24, 2023 |
| Lenovo        | G550 2958                   | [7a1a8bb421](https://linux-hardware.org/?probe=7a1a8bb421) | Apr 23, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [c8ec222920](https://linux-hardware.org/?probe=c8ec222920) | Apr 23, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [2a02b4695b](https://linux-hardware.org/?probe=2a02b4695b) | Apr 23, 2023 |
| Unknown       | M-140BI5                    | [32ba023e2a](https://linux-hardware.org/?probe=32ba023e2a) | Apr 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [5f61e3a174](https://linux-hardware.org/?probe=5f61e3a174) | Apr 21, 2023 |
| MSI           | GE62 6QD                    | [785d4c1655](https://linux-hardware.org/?probe=785d4c1655) | Apr 20, 2023 |
| Dell          | Latitude E6440              | [027d51d72d](https://linux-hardware.org/?probe=027d51d72d) | Apr 19, 2023 |
| HP            | 250 G7 Notebook PC          | [6696ce8fd6](https://linux-hardware.org/?probe=6696ce8fd6) | Apr 17, 2023 |
| iQual         | NQ4X                        | [425ccf4057](https://linux-hardware.org/?probe=425ccf4057) | Apr 16, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [9b23be6c48](https://linux-hardware.org/?probe=9b23be6c48) | Apr 16, 2023 |
| BANGHO        | MAX G0101                   | [d1ed9e6040](https://linux-hardware.org/?probe=d1ed9e6040) | Apr 14, 2023 |
| HP            | Compaq Presario F700        | [2ae0d7557b](https://linux-hardware.org/?probe=2ae0d7557b) | Apr 13, 2023 |
| Dell          | Latitude 5490               | [38ebdedf58](https://linux-hardware.org/?probe=38ebdedf58) | Apr 12, 2023 |
| Lenovo        | ThinkPad T480 20L6S0CE1M    | [eb794b0dc7](https://linux-hardware.org/?probe=eb794b0dc7) | Apr 10, 2023 |
| Positivo      | A1000BW                     | [02295facdc](https://linux-hardware.org/?probe=02295facdc) | Apr 09, 2023 |
| Apple         | MacBook5,2                  | [916db99ea5](https://linux-hardware.org/?probe=916db99ea5) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5a900adcdc](https://linux-hardware.org/?probe=5a900adcdc) | Apr 07, 2023 |
| Samsung       | NC110P/NC108P/NC111P        | [91fcea0b0f](https://linux-hardware.org/?probe=91fcea0b0f) | Apr 07, 2023 |
| Gigabyte      | AORUS 15P KD                | [0b53411753](https://linux-hardware.org/?probe=0b53411753) | Apr 07, 2023 |
| Acer          | Aspire ES1-572              | [bb95a52e54](https://linux-hardware.org/?probe=bb95a52e54) | Apr 05, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | [58f5904dec](https://linux-hardware.org/?probe=58f5904dec) | Apr 04, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [676156b5df](https://linux-hardware.org/?probe=676156b5df) | Apr 02, 2023 |
| Exo           | Smart XL4                   | [6421142cb6](https://linux-hardware.org/?probe=6421142cb6) | Mar 31, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [2ca1607b80](https://linux-hardware.org/?probe=2ca1607b80) | Mar 30, 2023 |
| AIR           | CX30500                     | [2ea4d0ec83](https://linux-hardware.org/?probe=2ea4d0ec83) | Mar 30, 2023 |
| Lenovo        | G470 20078                  | [1e510aad42](https://linux-hardware.org/?probe=1e510aad42) | Mar 30, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [25cc7bfca2](https://linux-hardware.org/?probe=25cc7bfca2) | Mar 28, 2023 |
| Acer          | TravelMate P215-52          | [b6184e813b](https://linux-hardware.org/?probe=b6184e813b) | Mar 28, 2023 |
| ASUSTek       | X541SA                      | [f281edd494](https://linux-hardware.org/?probe=f281edd494) | Mar 28, 2023 |
| Sony          | VJFE52A0711H                | [f2186a4bc4](https://linux-hardware.org/?probe=f2186a4bc4) | Mar 27, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [dca4079e12](https://linux-hardware.org/?probe=dca4079e12) | Mar 26, 2023 |
| HP            | G42                         | [f1b5695907](https://linux-hardware.org/?probe=f1b5695907) | Mar 25, 2023 |
| Dell          | Latitude 5480               | [5886784510](https://linux-hardware.org/?probe=5886784510) | Mar 22, 2023 |
| Juana Mans... | SF20GM7                     | [708f22e8d7](https://linux-hardware.org/?probe=708f22e8d7) | Mar 19, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [eea214ee38](https://linux-hardware.org/?probe=eea214ee38) | Mar 18, 2023 |
| Lenovo        | ThinkPad T430 23492D1       | [34e2b05336](https://linux-hardware.org/?probe=34e2b05336) | Mar 14, 2023 |
| Exo           | Smart XS1                   | [e1e04684eb](https://linux-hardware.org/?probe=e1e04684eb) | Mar 14, 2023 |
| Dell          | Inspiron 15-3567            | [97504eea44](https://linux-hardware.org/?probe=97504eea44) | Mar 13, 2023 |
| MSI           | Alpha 15 A3DDK              | [1815783cfe](https://linux-hardware.org/?probe=1815783cfe) | Mar 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [7236313c80](https://linux-hardware.org/?probe=7236313c80) | Mar 09, 2023 |
| Unknown       | M-140BI5                    | [bb3776e45d](https://linux-hardware.org/?probe=bb3776e45d) | Mar 09, 2023 |
| eMachines     | eME730                      | [0e1683ee34](https://linux-hardware.org/?probe=0e1683ee34) | Mar 08, 2023 |
| eMachines     | eME730                      | [db15f88805](https://linux-hardware.org/?probe=db15f88805) | Mar 08, 2023 |
| Lenovo        | ThinkPad X240 20AMA3PVAR    | [367f53195a](https://linux-hardware.org/?probe=367f53195a) | Mar 07, 2023 |
| Exo           | Smart Serie M               | [99c93d693a](https://linux-hardware.org/?probe=99c93d693a) | Mar 04, 2023 |
| Exo           | Smart Serie M               | [e7b817f5ed](https://linux-hardware.org/?probe=e7b817f5ed) | Mar 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [83a611b1ab](https://linux-hardware.org/?probe=83a611b1ab) | Feb 27, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [c19b7cd0f5](https://linux-hardware.org/?probe=c19b7cd0f5) | Feb 24, 2023 |
| Acer          | Aspire E5-575G              | [f7d34fdd3a](https://linux-hardware.org/?probe=f7d34fdd3a) | Feb 24, 2023 |
| Dell          | Vostro 3700                 | [a37b20471b](https://linux-hardware.org/?probe=a37b20471b) | Feb 23, 2023 |
| HP            | EliteBook 830 G5            | [a5f65720f5](https://linux-hardware.org/?probe=a5f65720f5) | Feb 22, 2023 |
| Exo           | Smart XL4                   | [6e97a3ff67](https://linux-hardware.org/?probe=6e97a3ff67) | Feb 21, 2023 |
| Dell          | Inspiron 3502               | [224f4edab7](https://linux-hardware.org/?probe=224f4edab7) | Feb 20, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | [008d5e19e1](https://linux-hardware.org/?probe=008d5e19e1) | Feb 20, 2023 |
| Acer          | Aspire 5738                 | [48bbbc04c4](https://linux-hardware.org/?probe=48bbbc04c4) | Feb 17, 2023 |
| Acer          | Aspire A315-33              | [38a92c4ace](https://linux-hardware.org/?probe=38a92c4ace) | Feb 15, 2023 |
| Dell          | Inspiron 3505               | [ba53e8885b](https://linux-hardware.org/?probe=ba53e8885b) | Feb 13, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [20a75bea61](https://linux-hardware.org/?probe=20a75bea61) | Feb 11, 2023 |
| BANGHO        | GM-15Z11 GF1650 i5          | [6cdb04950c](https://linux-hardware.org/?probe=6cdb04950c) | Feb 10, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [a64bb02ece](https://linux-hardware.org/?probe=a64bb02ece) | Feb 10, 2023 |
| Unknown       | M-140BI5                    | [a07b2a4444](https://linux-hardware.org/?probe=a07b2a4444) | Feb 09, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [f8de6e450a](https://linux-hardware.org/?probe=f8de6e450a) | Feb 08, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | [9f6079baf2](https://linux-hardware.org/?probe=9f6079baf2) | Feb 08, 2023 |
| Intel         | Calistoga & ICH7M Chipse... | [db2f72084a](https://linux-hardware.org/?probe=db2f72084a) | Feb 07, 2023 |
| Lenovo        | G470 20078                  | [eca9b95b61](https://linux-hardware.org/?probe=eca9b95b61) | Feb 07, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [a1f33b7267](https://linux-hardware.org/?probe=a1f33b7267) | Feb 06, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [5ae73f08c5](https://linux-hardware.org/?probe=5ae73f08c5) | Feb 06, 2023 |
| Unknown       | M-140BI5                    | [32f4028033](https://linux-hardware.org/?probe=32f4028033) | Feb 05, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [86667a843f](https://linux-hardware.org/?probe=86667a843f) | Feb 03, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [03540bd8e5](https://linux-hardware.org/?probe=03540bd8e5) | Feb 02, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [a6584159ac](https://linux-hardware.org/?probe=a6584159ac) | Feb 02, 2023 |
| Dell          | XPS 17 9710                 | [f6d37d568c](https://linux-hardware.org/?probe=f6d37d568c) | Feb 01, 2023 |
| Dell          | XPS 17 9710                 | [9fab32d6a5](https://linux-hardware.org/?probe=9fab32d6a5) | Feb 01, 2023 |
| Samsung       | SQ35S                       | [7ad1c8a94b](https://linux-hardware.org/?probe=7ad1c8a94b) | Feb 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | [5122097b1e](https://linux-hardware.org/?probe=5122097b1e) | Jan 29, 2023 |
| Lenovo        | ThinkPad X230 23254UY       | [130aeb9cc4](https://linux-hardware.org/?probe=130aeb9cc4) | Jan 27, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [055d033d99](https://linux-hardware.org/?probe=055d033d99) | Jan 24, 2023 |
| Sony          | VPCEA30EL                   | [7de250ffe6](https://linux-hardware.org/?probe=7de250ffe6) | Jan 24, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [7ecc4d20c3](https://linux-hardware.org/?probe=7ecc4d20c3) | Jan 19, 2023 |
| ASUSTek       | X556UQK                     | [b0716d3518](https://linux-hardware.org/?probe=b0716d3518) | Jan 19, 2023 |
| BANGHO        | MOV                         | [bc4f98d4ff](https://linux-hardware.org/?probe=bc4f98d4ff) | Jan 17, 2023 |
| Chuwi         | GemiBook Pro                | [b51cc41cb3](https://linux-hardware.org/?probe=b51cc41cb3) | Jan 16, 2023 |
| Lenovo        | ThinkPad P15v Gen 2i 21A... | [ca60f249a9](https://linux-hardware.org/?probe=ca60f249a9) | Jan 13, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | [86a6601ce5](https://linux-hardware.org/?probe=86a6601ce5) | Jan 12, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [d4691b9969](https://linux-hardware.org/?probe=d4691b9969) | Jan 12, 2023 |
| HP            | Pavilion Laptop 13-bb0xx... | [790736a10e](https://linux-hardware.org/?probe=790736a10e) | Jan 11, 2023 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | [ff6c949737](https://linux-hardware.org/?probe=ff6c949737) | Jan 09, 2023 |
| Dell          | Latitude 3490               | [7cf81f6b69](https://linux-hardware.org/?probe=7cf81f6b69) | Jan 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [4334ec8d00](https://linux-hardware.org/?probe=4334ec8d00) | Jan 08, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [7ce97bb3ec](https://linux-hardware.org/?probe=7ce97bb3ec) | Jan 08, 2023 |
| HP            | 240 G8                      | [efc7e61483](https://linux-hardware.org/?probe=efc7e61483) | Jan 06, 2023 |
| BANGHO        | MAX G0101                   | [290ccc3261](https://linux-hardware.org/?probe=290ccc3261) | Jan 06, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cddb2a7b81](https://linux-hardware.org/?probe=cddb2a7b81) | Jan 06, 2023 |
| HP            | EliteBook 830 G5            | [a4473dafda](https://linux-hardware.org/?probe=a4473dafda) | Jan 03, 2023 |
| Positivo      | Z100                        | [58b7c4d1ff](https://linux-hardware.org/?probe=58b7c4d1ff) | Jan 02, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [5fbe1632b0](https://linux-hardware.org/?probe=5fbe1632b0) | Dec 31, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [5a479fed95](https://linux-hardware.org/?probe=5a479fed95) | Dec 31, 2022 |
| Dell          | Latitude E6430              | [de9b03cf29](https://linux-hardware.org/?probe=de9b03cf29) | Dec 31, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [ed5315b768](https://linux-hardware.org/?probe=ed5315b768) | Dec 29, 2022 |
| Acer          | AO756                       | [d0cf64acd1](https://linux-hardware.org/?probe=d0cf64acd1) | Dec 28, 2022 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | [e12c24fd74](https://linux-hardware.org/?probe=e12c24fd74) | Dec 28, 2022 |
| Lenovo        | G470 20078                  | [8cbb4aa960](https://linux-hardware.org/?probe=8cbb4aa960) | Dec 28, 2022 |
| Lenovo        | G470 20078                  | [d6e7a07be2](https://linux-hardware.org/?probe=d6e7a07be2) | Dec 28, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [2195143f19](https://linux-hardware.org/?probe=2195143f19) | Dec 27, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [73e9da47ae](https://linux-hardware.org/?probe=73e9da47ae) | Dec 27, 2022 |
| Exo           | Smart Serie M               | [942ee3b035](https://linux-hardware.org/?probe=942ee3b035) | Dec 26, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [c7babe827f](https://linux-hardware.org/?probe=c7babe827f) | Dec 26, 2022 |
| ASUSTek       | ZenBook S UX391UA           | [5004189ba4](https://linux-hardware.org/?probe=5004189ba4) | Dec 26, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [668dac3d4c](https://linux-hardware.org/?probe=668dac3d4c) | Dec 23, 2022 |
| Chuwi         | GemiBook Pro                | [aaaf436994](https://linux-hardware.org/?probe=aaaf436994) | Dec 19, 2022 |
| Chuwi         | GemiBook Pro                | [b34ce3474d](https://linux-hardware.org/?probe=b34ce3474d) | Dec 19, 2022 |
| Samsung       | R430/P430/R480              | [ae3789203b](https://linux-hardware.org/?probe=ae3789203b) | Dec 18, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [04cc986bf6](https://linux-hardware.org/?probe=04cc986bf6) | Dec 15, 2022 |
| Dell          | Latitude 5520               | [7e5d86eaaf](https://linux-hardware.org/?probe=7e5d86eaaf) | Dec 13, 2022 |
| Exo           | Smart Serie M               | [7fcf3d09bb](https://linux-hardware.org/?probe=7fcf3d09bb) | Dec 13, 2022 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | [9866855d37](https://linux-hardware.org/?probe=9866855d37) | Dec 13, 2022 |
| Clevo         | M740TU/M760TU               | [5f1a4b58fb](https://linux-hardware.org/?probe=5f1a4b58fb) | Dec 13, 2022 |
| Dell          | Latitude E6430              | [f28775142d](https://linux-hardware.org/?probe=f28775142d) | Dec 09, 2022 |
| Dell          | G15 5515                    | [861bd0cabf](https://linux-hardware.org/?probe=861bd0cabf) | Dec 08, 2022 |
| HP            | Notebook                    | [37eead7e86](https://linux-hardware.org/?probe=37eead7e86) | Dec 07, 2022 |
| BANGHO        | BES T5                      | [db1db74a86](https://linux-hardware.org/?probe=db1db74a86) | Dec 06, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [3b87d266c2](https://linux-hardware.org/?probe=3b87d266c2) | Dec 02, 2022 |
| Dell          | Latitude E5450              | [305bf364f6](https://linux-hardware.org/?probe=305bf364f6) | Dec 01, 2022 |
| Dell          | Latitude E5450              | [2b934a729c](https://linux-hardware.org/?probe=2b934a729c) | Dec 01, 2022 |
| Lenovo        | V330-15IKB 81AX             | [becc2328fd](https://linux-hardware.org/?probe=becc2328fd) | Dec 01, 2022 |
| PCBOX-H       | BayTrail                    | [81eca2f60e](https://linux-hardware.org/?probe=81eca2f60e) | Nov 30, 2022 |
| PCBOX-H       | BayTrail                    | [5841aa11f1](https://linux-hardware.org/?probe=5841aa11f1) | Nov 30, 2022 |
| Positivo      | i500pro                     | [4a79aa2383](https://linux-hardware.org/?probe=4a79aa2383) | Nov 30, 2022 |
| HP            | EliteBook 840 G6            | [3f545fe7c9](https://linux-hardware.org/?probe=3f545fe7c9) | Nov 29, 2022 |
| Lenovo        | ThinkPad T430 2349DS5       | [f52677ec2e](https://linux-hardware.org/?probe=f52677ec2e) | Nov 27, 2022 |
| Lenovo        | ThinkPad E14 20RBS3LE00     | [83203a04f2](https://linux-hardware.org/?probe=83203a04f2) | Nov 25, 2022 |
| Coradir       | Coradir/ES10IS5             | [a1fb1953ad](https://linux-hardware.org/?probe=a1fb1953ad) | Nov 22, 2022 |
| HP            | Notebook                    | [ab824250b9](https://linux-hardware.org/?probe=ab824250b9) | Nov 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [7ffd8149f4](https://linux-hardware.org/?probe=7ffd8149f4) | Nov 21, 2022 |
| Dell          | Latitude E6510              | [c8b9fa9d0a](https://linux-hardware.org/?probe=c8b9fa9d0a) | Nov 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [ebceee7ddf](https://linux-hardware.org/?probe=ebceee7ddf) | Nov 18, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [d22a7fff30](https://linux-hardware.org/?probe=d22a7fff30) | Nov 18, 2022 |
| ASUSTek       | K52Jc                       | [375bc280d3](https://linux-hardware.org/?probe=375bc280d3) | Nov 18, 2022 |
| Exo           | Smart XS1                   | [d51bf05ac5](https://linux-hardware.org/?probe=d51bf05ac5) | Nov 17, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [3964f95a8c](https://linux-hardware.org/?probe=3964f95a8c) | Nov 17, 2022 |
| Dell          | G15 5515                    | [bb76ce58ad](https://linux-hardware.org/?probe=bb76ce58ad) | Nov 17, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [d82617ae65](https://linux-hardware.org/?probe=d82617ae65) | Nov 15, 2022 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | [c6e254c4ed](https://linux-hardware.org/?probe=c6e254c4ed) | Nov 14, 2022 |
| ASUSTek       | K53Z                        | [7eb8b08a75](https://linux-hardware.org/?probe=7eb8b08a75) | Nov 13, 2022 |
| HP            | 250 G8 Notebook PC          | [7e9c7562d6](https://linux-hardware.org/?probe=7e9c7562d6) | Nov 13, 2022 |
| ASUSTek       | UX410UAK                    | [6653b6c4a5](https://linux-hardware.org/?probe=6653b6c4a5) | Nov 13, 2022 |
| Lenovo        | ThinkPad W541 20EGS0V700    | [d03ec65abc](https://linux-hardware.org/?probe=d03ec65abc) | Nov 08, 2022 |
| HP            | 240 G8                      | [cbeff38360](https://linux-hardware.org/?probe=cbeff38360) | Nov 07, 2022 |
| HP            | 240 G8                      | [0fadcc21ac](https://linux-hardware.org/?probe=0fadcc21ac) | Nov 07, 2022 |
| BANGHO        | W240HU/W250HUQ              | [82bafb1ca4](https://linux-hardware.org/?probe=82bafb1ca4) | Nov 04, 2022 |
| Juana Mans... | SF20GM7                     | [8e8c4f52f4](https://linux-hardware.org/?probe=8e8c4f52f4) | Nov 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [c90b358eb5](https://linux-hardware.org/?probe=c90b358eb5) | Nov 01, 2022 |
| Acer          | Nitro AN515-42              | [3a00ca53c8](https://linux-hardware.org/?probe=3a00ca53c8) | Oct 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [deac1b706f](https://linux-hardware.org/?probe=deac1b706f) | Oct 31, 2022 |
| Intel         | powered classmate PC        | [5555da7553](https://linux-hardware.org/?probe=5555da7553) | Oct 31, 2022 |
| Lenovo        | ThinkPad T440 20B7S18Y0Y    | [9cf3beb13f](https://linux-hardware.org/?probe=9cf3beb13f) | Oct 30, 2022 |
| Lenovo        | ThinkPad T440 20B7S18Y0Y    | [36b3303b35](https://linux-hardware.org/?probe=36b3303b35) | Oct 30, 2022 |
| Compaq        | Presario 21 VerX            | [97ee92b9d1](https://linux-hardware.org/?probe=97ee92b9d1) | Oct 28, 2022 |
| Dell          | Inspiron 3558               | [3eeb2624bf](https://linux-hardware.org/?probe=3eeb2624bf) | Oct 27, 2022 |
| Lenovo        | G470 20078                  | [c923b6d506](https://linux-hardware.org/?probe=c923b6d506) | Oct 27, 2022 |
| ASUSTek       | X541UAK                     | [87ee863ba2](https://linux-hardware.org/?probe=87ee863ba2) | Oct 26, 2022 |
| Dell          | Latitude E6510              | [1949f78888](https://linux-hardware.org/?probe=1949f78888) | Oct 26, 2022 |
| Dell          | Precision 5560              | [c6cfa3f96d](https://linux-hardware.org/?probe=c6cfa3f96d) | Oct 25, 2022 |
| Dell          | Precision 5560              | [e0dce17c1f](https://linux-hardware.org/?probe=e0dce17c1f) | Oct 25, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [0c60239460](https://linux-hardware.org/?probe=0c60239460) | Oct 25, 2022 |
| Lenovo        | Legion 5 15IAH7 82RC        | [8f793706c2](https://linux-hardware.org/?probe=8f793706c2) | Oct 23, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T7S... | [4a17b0a89d](https://linux-hardware.org/?probe=4a17b0a89d) | Oct 22, 2022 |
| Intel         | Montevina CRB               | [11cb344c52](https://linux-hardware.org/?probe=11cb344c52) | Oct 22, 2022 |
| A-DATA Tec... | XENIA 14                    | [c8a0b8e94f](https://linux-hardware.org/?probe=c8a0b8e94f) | Oct 20, 2022 |
| MSI           | Modern 15 A11MU             | [2413dd813b](https://linux-hardware.org/?probe=2413dd813b) | Oct 19, 2022 |
| Acer          | Aspire A315-21              | [3b8ac4e243](https://linux-hardware.org/?probe=3b8ac4e243) | Oct 19, 2022 |
| Positivo      | AT300i                      | [02190f570b](https://linux-hardware.org/?probe=02190f570b) | Oct 16, 2022 |
| Dell          | Latitude E5450              | [68e2c17e2f](https://linux-hardware.org/?probe=68e2c17e2f) | Oct 15, 2022 |
| A-DATA Tec... | XENIA 14                    | [85f4236c50](https://linux-hardware.org/?probe=85f4236c50) | Oct 15, 2022 |
| KELYX ARGE... | KL9120                      | [a14b57c22c](https://linux-hardware.org/?probe=a14b57c22c) | Oct 14, 2022 |
| Lenovo        | B51-30 80LK                 | [13e68d4364](https://linux-hardware.org/?probe=13e68d4364) | Oct 12, 2022 |
| Lenovo        | B51-30 80LK                 | [1444f8cc5b](https://linux-hardware.org/?probe=1444f8cc5b) | Oct 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [e2deb8e15e](https://linux-hardware.org/?probe=e2deb8e15e) | Oct 11, 2022 |
| KELYX ARGE... | KL9120                      | [477851891a](https://linux-hardware.org/?probe=477851891a) | Oct 11, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [7dcd7050ae](https://linux-hardware.org/?probe=7dcd7050ae) | Oct 10, 2022 |
| Positivo      | AT300i                      | [62b9d61028](https://linux-hardware.org/?probe=62b9d61028) | Oct 09, 2022 |
| Positivo      | AT300i                      | [8bbd312832](https://linux-hardware.org/?probe=8bbd312832) | Oct 09, 2022 |
| ASUSTek       | X505BP                      | [3ebba89d5e](https://linux-hardware.org/?probe=3ebba89d5e) | Oct 07, 2022 |
| Samsung       | 530U4E/540U4E               | [11ed7b9f37](https://linux-hardware.org/?probe=11ed7b9f37) | Oct 07, 2022 |
| KELYX ARGE... | KL9120                      | [faa5f13391](https://linux-hardware.org/?probe=faa5f13391) | Oct 06, 2022 |
| BANGHO        | GAMER GM-X 15s              | [d3e2d5452a](https://linux-hardware.org/?probe=d3e2d5452a) | Oct 03, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [0a022a22c6](https://linux-hardware.org/?probe=0a022a22c6) | Oct 01, 2022 |
| HP            | Laptop 15-bs0xx             | [7ed786bee9](https://linux-hardware.org/?probe=7ed786bee9) | Sep 30, 2022 |
| Lenovo        | V330-15IKB 81AX             | [0360123f76](https://linux-hardware.org/?probe=0360123f76) | Sep 29, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | [d5a4d2ae41](https://linux-hardware.org/?probe=d5a4d2ae41) | Sep 28, 2022 |
| Positivo      | SW6H                        | [4cfa6665bb](https://linux-hardware.org/?probe=4cfa6665bb) | Sep 27, 2022 |
| System76      | Lemur Pro                   | [35340e6221](https://linux-hardware.org/?probe=35340e6221) | Sep 26, 2022 |
| NSX           | Celeron 14                  | [b8fdb14beb](https://linux-hardware.org/?probe=b8fdb14beb) | Sep 25, 2022 |
| NSX           | Celeron 14                  | [1d358a2828](https://linux-hardware.org/?probe=1d358a2828) | Sep 25, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [850b486cff](https://linux-hardware.org/?probe=850b486cff) | Sep 25, 2022 |
| Lenovo        | Y50-70 Touch 20349          | [f038a5908f](https://linux-hardware.org/?probe=f038a5908f) | Sep 23, 2022 |
| HP            | OMEN by Laptop 15-ce0xx     | [2250b3380d](https://linux-hardware.org/?probe=2250b3380d) | Sep 22, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [628fd0d32d](https://linux-hardware.org/?probe=628fd0d32d) | Sep 21, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [b07937de6a](https://linux-hardware.org/?probe=b07937de6a) | Sep 20, 2022 |
| BANGHO        | BES G1529                   | [ce0db88361](https://linux-hardware.org/?probe=ce0db88361) | Sep 20, 2022 |
| HP            | Laptop 15-ef2xxx            | [c9ab60a094](https://linux-hardware.org/?probe=c9ab60a094) | Sep 19, 2022 |
| Acer          | Swift SF314-42              | [f52b35d82d](https://linux-hardware.org/?probe=f52b35d82d) | Sep 19, 2022 |
| Dell          | Latitude E6510              | [ee09885560](https://linux-hardware.org/?probe=ee09885560) | Sep 16, 2022 |
| Exo           | Smart XL4                   | [96f159b86f](https://linux-hardware.org/?probe=96f159b86f) | Sep 14, 2022 |
| HP            | Pavilion 17                 | [5d9be9b086](https://linux-hardware.org/?probe=5d9be9b086) | Sep 13, 2022 |
| Dell          | Precision 5550              | [82eebd67fd](https://linux-hardware.org/?probe=82eebd67fd) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [89339e48f1](https://linux-hardware.org/?probe=89339e48f1) | Sep 13, 2022 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | [d39dcbc8ed](https://linux-hardware.org/?probe=d39dcbc8ed) | Sep 13, 2022 |
| Toshiba       | Satellite C55-C             | [c9b78bb640](https://linux-hardware.org/?probe=c9b78bb640) | Sep 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [1f2be56ed4](https://linux-hardware.org/?probe=1f2be56ed4) | Sep 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [31717bdcb1](https://linux-hardware.org/?probe=31717bdcb1) | Sep 09, 2022 |
| ASUSTek       | X555LAB                     | [7d108d27ee](https://linux-hardware.org/?probe=7d108d27ee) | Sep 09, 2022 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | [a877bbf17d](https://linux-hardware.org/?probe=a877bbf17d) | Sep 09, 2022 |
| HP            | 245 G6                      | [054d226709](https://linux-hardware.org/?probe=054d226709) | Sep 07, 2022 |
| Samsung       | 300E4A/300E5A/300E7A        | [35ead5350d](https://linux-hardware.org/?probe=35ead5350d) | Sep 07, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c905c86c47](https://linux-hardware.org/?probe=c905c86c47) | Sep 07, 2022 |
| Unknown       | Unknown                     | [efb1e9883d](https://linux-hardware.org/?probe=efb1e9883d) | Sep 05, 2022 |
| Unknown       | Unknown                     | [20178af23f](https://linux-hardware.org/?probe=20178af23f) | Sep 05, 2022 |
| Intel         | powered classmate PC        | [ed36baccf9](https://linux-hardware.org/?probe=ed36baccf9) | Aug 31, 2022 |
| MSI           | Modern 14 B10MW             | [c107217cf8](https://linux-hardware.org/?probe=c107217cf8) | Aug 28, 2022 |
| BANGHO        | AERO X2 I1002               | [f24ddb9619](https://linux-hardware.org/?probe=f24ddb9619) | Aug 28, 2022 |
| Exo           | Smart Serie L               | [5cbaef571b](https://linux-hardware.org/?probe=5cbaef571b) | Aug 27, 2022 |
| HP            | Notebook                    | [2d11bc2975](https://linux-hardware.org/?probe=2d11bc2975) | Aug 26, 2022 |
| Standard      | AHV                         | [1a4d477350](https://linux-hardware.org/?probe=1a4d477350) | Aug 24, 2022 |
| Lenovo        | V330-15IKB 81AX             | [c3ddddae2c](https://linux-hardware.org/?probe=c3ddddae2c) | Aug 24, 2022 |
| Lenovo        | G580 20150                  | [6c0183592b](https://linux-hardware.org/?probe=6c0183592b) | Aug 23, 2022 |
| Sony          | VGN-NR210FH                 | [8c007bfa55](https://linux-hardware.org/?probe=8c007bfa55) | Aug 23, 2022 |
| ASUSTek       | ZenBook UX534FTC_UX534FT    | [d4a7a111a7](https://linux-hardware.org/?probe=d4a7a111a7) | Aug 21, 2022 |
| Novatech      | C141WP-I5HS                 | [767c02caeb](https://linux-hardware.org/?probe=767c02caeb) | Aug 20, 2022 |
| Compaq        | Presario 21 VerX            | [97aa39b2ca](https://linux-hardware.org/?probe=97aa39b2ca) | Aug 19, 2022 |
| Lenovo        | ThinkPad W510 4391F66       | [a92e3ba61f](https://linux-hardware.org/?probe=a92e3ba61f) | Aug 19, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [0dbc32a26d](https://linux-hardware.org/?probe=0dbc32a26d) | Aug 17, 2022 |
| HP            | Notebook                    | [784ad31f68](https://linux-hardware.org/?probe=784ad31f68) | Aug 17, 2022 |
| HP            | Pavilion dv9700             | [7c3e324e4f](https://linux-hardware.org/?probe=7c3e324e4f) | Aug 16, 2022 |
| PCBOX         | Kant                        | [1b5c160d93](https://linux-hardware.org/?probe=1b5c160d93) | Aug 16, 2022 |
| Dell          | Latitude E6510              | [2a4c496cce](https://linux-hardware.org/?probe=2a4c496cce) | Aug 15, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [d5862f21f5](https://linux-hardware.org/?probe=d5862f21f5) | Aug 14, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | [d08cbbc3d8](https://linux-hardware.org/?probe=d08cbbc3d8) | Aug 12, 2022 |
| HP            | Pavilion 17                 | [25a07691ec](https://linux-hardware.org/?probe=25a07691ec) | Aug 12, 2022 |
| Acer          | Predator PH315-52           | [fad6aace6a](https://linux-hardware.org/?probe=fad6aace6a) | Aug 11, 2022 |
| Lenovo        | IdeaPad S145-14AST 81ST     | [cac00fb432](https://linux-hardware.org/?probe=cac00fb432) | Aug 11, 2022 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | [15488377fb](https://linux-hardware.org/?probe=15488377fb) | Aug 10, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [5484873fd7](https://linux-hardware.org/?probe=5484873fd7) | Aug 10, 2022 |
| ASUSTek       | X510UNR                     | [a6f68827fb](https://linux-hardware.org/?probe=a6f68827fb) | Aug 09, 2022 |
| NVN-ED01      | Unknown                     | [0a677cad6c](https://linux-hardware.org/?probe=0a677cad6c) | Aug 09, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | [b8ae818291](https://linux-hardware.org/?probe=b8ae818291) | Aug 08, 2022 |
| Toshiba       | Satellite Pro L300D         | [b3ed30ac52](https://linux-hardware.org/?probe=b3ed30ac52) | Aug 07, 2022 |
| MSI           | CR620                       | [517b816cd7](https://linux-hardware.org/?probe=517b816cd7) | Aug 06, 2022 |
| Lenovo        | ThinkPad T450 20BUS0100G    | [0b4eaa2b43](https://linux-hardware.org/?probe=0b4eaa2b43) | Aug 03, 2022 |
| Lenovo        | ThinkPad T450 20BUS0100G    | [beaaaa6f6e](https://linux-hardware.org/?probe=beaaaa6f6e) | Aug 03, 2022 |
| LG Electro... | R480-L.B211P1               | [307f422c53](https://linux-hardware.org/?probe=307f422c53) | Aug 03, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | [e586e6ee53](https://linux-hardware.org/?probe=e586e6ee53) | Aug 02, 2022 |
| Exo           | Exomate X352                | [3be8045452](https://linux-hardware.org/?probe=3be8045452) | Aug 02, 2022 |
| IFSA          | Positivo BGH                | [ec0aa9bc36](https://linux-hardware.org/?probe=ec0aa9bc36) | Aug 02, 2022 |
| Lenovo        | Legion 5 15ITH6H 82JH       | [0b8452087a](https://linux-hardware.org/?probe=0b8452087a) | Aug 02, 2022 |
| Toshiba       | Satellite-C845              | [6ee9ea90a5](https://linux-hardware.org/?probe=6ee9ea90a5) | Aug 01, 2022 |
| GPU Compan... | GWNR71517                   | [72278643e8](https://linux-hardware.org/?probe=72278643e8) | Aug 01, 2022 |
| Apple         | MacBook4,1                  | [b72463cb79](https://linux-hardware.org/?probe=b72463cb79) | Jul 28, 2022 |
| Lenovo        | ThinkPad T480s 20L8S31T0... | [60449c872b](https://linux-hardware.org/?probe=60449c872b) | Jul 27, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [a2c2f04e29](https://linux-hardware.org/?probe=a2c2f04e29) | Jul 26, 2022 |
| ASUSTek       | X550ZA                      | [00126a3052](https://linux-hardware.org/?probe=00126a3052) | Jul 25, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [7ffde486ac](https://linux-hardware.org/?probe=7ffde486ac) | Jul 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [f84af529bb](https://linux-hardware.org/?probe=f84af529bb) | Jul 24, 2022 |
| Lenovo        | B40-70 80F3                 | [6f5d960fdc](https://linux-hardware.org/?probe=6f5d960fdc) | Jul 21, 2022 |
| Lenovo        | B40-70 80F3                 | [2543aa4d88](https://linux-hardware.org/?probe=2543aa4d88) | Jul 21, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [dca2e009f0](https://linux-hardware.org/?probe=dca2e009f0) | Jul 20, 2022 |
| Acer          | Aspire E3-112               | [475d626fd5](https://linux-hardware.org/?probe=475d626fd5) | Jul 19, 2022 |
| Toshiba       | Satellite C55-B             | [70c17c522d](https://linux-hardware.org/?probe=70c17c522d) | Jul 18, 2022 |
| ASUSTek       | X555LAB                     | [8ae373a79c](https://linux-hardware.org/?probe=8ae373a79c) | Jul 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [5089cb3d81](https://linux-hardware.org/?probe=5089cb3d81) | Jul 17, 2022 |
| NSX           | SB142G                      | [12329702b6](https://linux-hardware.org/?probe=12329702b6) | Jul 15, 2022 |
| ASUSTek       | X455LJ                      | [0c08648c4d](https://linux-hardware.org/?probe=0c08648c4d) | Jul 15, 2022 |
| ASUSTek       | X555LAB                     | [5c5b387f6c](https://linux-hardware.org/?probe=5c5b387f6c) | Jul 14, 2022 |
| Standard      | AHV                         | [2499cab6bd](https://linux-hardware.org/?probe=2499cab6bd) | Jul 12, 2022 |
| Lenovo        | ThinkPad L470 20J5S01L00    | [401e13e2a6](https://linux-hardware.org/?probe=401e13e2a6) | Jul 12, 2022 |
| Dell          | Inspiron 5520               | [67d1588e47](https://linux-hardware.org/?probe=67d1588e47) | Jul 12, 2022 |
| BANGHO        | W240HU/W250HUQ              | [4f064a8dbc](https://linux-hardware.org/?probe=4f064a8dbc) | Jul 10, 2022 |
| Dell          | Latitude 3520               | [8439c98834](https://linux-hardware.org/?probe=8439c98834) | Jul 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [244b168c32](https://linux-hardware.org/?probe=244b168c32) | Jul 06, 2022 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | [a9d516466a](https://linux-hardware.org/?probe=a9d516466a) | Jul 06, 2022 |
| NSX           | SB142G                      | [58158ab261](https://linux-hardware.org/?probe=58158ab261) | Jul 04, 2022 |
| Dell          | Inspiron 5570               | [2a161e0d10](https://linux-hardware.org/?probe=2a161e0d10) | Jul 04, 2022 |
| Novatech      | C141WP-I5HS                 | [c487164618](https://linux-hardware.org/?probe=c487164618) | Jul 04, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ad993981af](https://linux-hardware.org/?probe=ad993981af) | Jul 02, 2022 |
| MSI           | CR620                       | [0968b18823](https://linux-hardware.org/?probe=0968b18823) | Jun 30, 2022 |
| HUAWEI        | MACH-WX9                    | [329e3a150f](https://linux-hardware.org/?probe=329e3a150f) | Jun 30, 2022 |
| ASUSTek       | UX302LA                     | [6092e85ae8](https://linux-hardware.org/?probe=6092e85ae8) | Jun 29, 2022 |
| Dell          | Latitude 3410               | [050678128c](https://linux-hardware.org/?probe=050678128c) | Jun 29, 2022 |
| Dell          | Latitude 3590               | [b5d4509068](https://linux-hardware.org/?probe=b5d4509068) | Jun 29, 2022 |
| HP            | ProBook 455 G4              | [f54297787f](https://linux-hardware.org/?probe=f54297787f) | Jun 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [ec155fca3f](https://linux-hardware.org/?probe=ec155fca3f) | Jun 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [016ee6ec73](https://linux-hardware.org/?probe=016ee6ec73) | Jun 28, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [579410b791](https://linux-hardware.org/?probe=579410b791) | Jun 28, 2022 |
| HP            | Laptop 15-ef2xxx            | [3e16709617](https://linux-hardware.org/?probe=3e16709617) | Jun 24, 2022 |
| Positivo      | VJF155F11UAR                | [77c5ca4f1e](https://linux-hardware.org/?probe=77c5ca4f1e) | Jun 22, 2022 |
| HP            | 255 G3                      | [def96ad707](https://linux-hardware.org/?probe=def96ad707) | Jun 21, 2022 |
| Dell          | Latitude 3590               | [fdfd4be1e2](https://linux-hardware.org/?probe=fdfd4be1e2) | Jun 21, 2022 |
| System76      | Lemur Pro                   | [38b04af23d](https://linux-hardware.org/?probe=38b04af23d) | Jun 20, 2022 |
| ASUSTek       | UX410UAK                    | [0d2e384ebf](https://linux-hardware.org/?probe=0d2e384ebf) | Jun 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [4e35a154b5](https://linux-hardware.org/?probe=4e35a154b5) | Jun 18, 2022 |
| Toshiba       | Satellite-L845              | [d617282ee0](https://linux-hardware.org/?probe=d617282ee0) | Jun 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [a56ff0b014](https://linux-hardware.org/?probe=a56ff0b014) | Jun 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | [9481bad179](https://linux-hardware.org/?probe=9481bad179) | Jun 17, 2022 |
| ASUSTek       | N56VB                       | [a87c22baee](https://linux-hardware.org/?probe=a87c22baee) | Jun 16, 2022 |
| HP            | Laptop 15-dw2xxx            | [7eee6145a1](https://linux-hardware.org/?probe=7eee6145a1) | Jun 16, 2022 |
| Lenovo        | B40-70 80F3                 | [41495c085a](https://linux-hardware.org/?probe=41495c085a) | Jun 16, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | [a3f29fd594](https://linux-hardware.org/?probe=a3f29fd594) | Jun 14, 2022 |
| HP            | Laptop 15-dw2xxx            | [cdc0b49b72](https://linux-hardware.org/?probe=cdc0b49b72) | Jun 13, 2022 |
| HP            | ProBook 440 G4              | [52efea465c](https://linux-hardware.org/?probe=52efea465c) | Jun 12, 2022 |
| HP            | ProBook 440 G4              | [731e6f4aa8](https://linux-hardware.org/?probe=731e6f4aa8) | Jun 12, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [cae8181e7d](https://linux-hardware.org/?probe=cae8181e7d) | Jun 11, 2022 |
| Gadnic        | NOT00A1                     | [d63fbf4c2e](https://linux-hardware.org/?probe=d63fbf4c2e) | Jun 10, 2022 |
| Dell          | Inspiron 3505               | [9ae6cc8594](https://linux-hardware.org/?probe=9ae6cc8594) | Jun 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [ea589a3279](https://linux-hardware.org/?probe=ea589a3279) | Jun 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [09d190612b](https://linux-hardware.org/?probe=09d190612b) | Jun 06, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [5e57fb2871](https://linux-hardware.org/?probe=5e57fb2871) | Jun 04, 2022 |
| HP            | Pavilion g4                 | [321300f927](https://linux-hardware.org/?probe=321300f927) | Jun 01, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | [ec364402d8](https://linux-hardware.org/?probe=ec364402d8) | May 31, 2022 |
| Lenovo        | ThinkPad T400 6474ES3       | [cf8b67714d](https://linux-hardware.org/?probe=cf8b67714d) | May 27, 2022 |
| Juana Mans... | SF20GM7                     | [2078b0ab3f](https://linux-hardware.org/?probe=2078b0ab3f) | May 26, 2022 |
| Positivo      | AT510                       | [2845c5ebd6](https://linux-hardware.org/?probe=2845c5ebd6) | May 25, 2022 |
| Dell          | Inspiron M5030              | [e59616f367](https://linux-hardware.org/?probe=e59616f367) | May 23, 2022 |
| Toshiba       | Unknown                     | [56ac954440](https://linux-hardware.org/?probe=56ac954440) | May 23, 2022 |
| Dell          | Inspiron 3502               | [0d26fe46da](https://linux-hardware.org/?probe=0d26fe46da) | May 19, 2022 |
| ASUSTek       | X555LD                      | [66a07f5e71](https://linux-hardware.org/?probe=66a07f5e71) | May 18, 2022 |
| ASUSTek       | X555LD                      | [3856a337bb](https://linux-hardware.org/?probe=3856a337bb) | May 18, 2022 |
| HP            | Pavilion Notebook           | [2b8318661b](https://linux-hardware.org/?probe=2b8318661b) | May 17, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | [09c8ff393f](https://linux-hardware.org/?probe=09c8ff393f) | May 16, 2022 |
| Acer          | Swift SF515-51T             | [3e3380c801](https://linux-hardware.org/?probe=3e3380c801) | May 15, 2022 |
| Lenovo        | IdeaPad S400 VIUS3          | [40d9831b29](https://linux-hardware.org/?probe=40d9831b29) | May 12, 2022 |
| Positivo      | AT300b                      | [7f5c5ceed4](https://linux-hardware.org/?probe=7f5c5ceed4) | May 11, 2022 |
| Dell          | Latitude E6430              | [a188e200b3](https://linux-hardware.org/?probe=a188e200b3) | May 10, 2022 |
| HP            | Laptop 15-bs0xx             | [ed1e3083d6](https://linux-hardware.org/?probe=ed1e3083d6) | May 09, 2022 |
| HP            | ProBook 440 G4              | [1f0811673a](https://linux-hardware.org/?probe=1f0811673a) | May 09, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5a8fc607c4](https://linux-hardware.org/?probe=5a8fc607c4) | May 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [3be0a0d66d](https://linux-hardware.org/?probe=3be0a0d66d) | May 03, 2022 |
| Packard Be... | EasyNote ENTG81BA           | [f3791f34b1](https://linux-hardware.org/?probe=f3791f34b1) | May 02, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [dc1b877e42](https://linux-hardware.org/?probe=dc1b877e42) | May 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [48d3759522](https://linux-hardware.org/?probe=48d3759522) | Apr 30, 2022 |
| NSX           | SB1402                      | [c9d79a4fe5](https://linux-hardware.org/?probe=c9d79a4fe5) | Apr 30, 2022 |
| Dell          | XPS 15 9510                 | [b92517268e](https://linux-hardware.org/?probe=b92517268e) | Apr 30, 2022 |
| Dell          | Latitude 5411               | [34c470e595](https://linux-hardware.org/?probe=34c470e595) | Apr 28, 2022 |
| NOBLEX        | N14WD21                     | [a8a7a4e1d5](https://linux-hardware.org/?probe=a8a7a4e1d5) | Apr 27, 2022 |
| HP            | EliteBook 840 G1            | [74c6e22c86](https://linux-hardware.org/?probe=74c6e22c86) | Apr 27, 2022 |
| Lenovo        | ThinkPad E470 20H1A01YAC    | [cd8726de3c](https://linux-hardware.org/?probe=cd8726de3c) | Apr 26, 2022 |
| Dell          | Studio 1558                 | [b31435ef0c](https://linux-hardware.org/?probe=b31435ef0c) | Apr 24, 2022 |
| HP            | Notebook                    | [339f862ddd](https://linux-hardware.org/?probe=339f862ddd) | Apr 24, 2022 |
| ASUSTek       | X556UB                      | [a9d2922649](https://linux-hardware.org/?probe=a9d2922649) | Apr 23, 2022 |
| ASUSTek       | K53E                        | [14e628cbba](https://linux-hardware.org/?probe=14e628cbba) | Apr 22, 2022 |
| MSI           | GE62 6QD                    | [d66e41c50e](https://linux-hardware.org/?probe=d66e41c50e) | Apr 22, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6454c55f08](https://linux-hardware.org/?probe=6454c55f08) | Apr 16, 2022 |
| HP            | Pavilion Notebook           | [8ea3af9aca](https://linux-hardware.org/?probe=8ea3af9aca) | Apr 14, 2022 |
| HP            | Pavilion Notebook           | [e2a600db96](https://linux-hardware.org/?probe=e2a600db96) | Apr 14, 2022 |
| Dell          | Latitude E7250              | [2d0ac286da](https://linux-hardware.org/?probe=2d0ac286da) | Apr 14, 2022 |
| Dell          | Latitude 3520               | [8003f0258a](https://linux-hardware.org/?probe=8003f0258a) | Apr 14, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [9bcf0f1e4f](https://linux-hardware.org/?probe=9bcf0f1e4f) | Apr 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [52e0e2e934](https://linux-hardware.org/?probe=52e0e2e934) | Apr 12, 2022 |
| Acer          | Aspire E5-575G              | [de3e230ca3](https://linux-hardware.org/?probe=de3e230ca3) | Apr 10, 2022 |
| Advantec      | CX23500W                    | [a3152e0a0f](https://linux-hardware.org/?probe=a3152e0a0f) | Apr 02, 2022 |
| Advantec      | CX23500W                    | [feb5c20169](https://linux-hardware.org/?probe=feb5c20169) | Apr 02, 2022 |
| Exo           | Smart XQ5c                  | [5653a02bd3](https://linux-hardware.org/?probe=5653a02bd3) | Mar 31, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [14bd2cc137](https://linux-hardware.org/?probe=14bd2cc137) | Mar 31, 2022 |
| Dell          | Latitude 3410               | [fd37f4137d](https://linux-hardware.org/?probe=fd37f4137d) | Mar 30, 2022 |
| HP            | Pavilion 17                 | [f815e79449](https://linux-hardware.org/?probe=f815e79449) | Mar 30, 2022 |
| Lenovo        | V15-G2-ITL 82KB             | [38700103d3](https://linux-hardware.org/?probe=38700103d3) | Mar 29, 2022 |
| Toshiba       | PORTEGE R935                | [b209a8e000](https://linux-hardware.org/?probe=b209a8e000) | Mar 28, 2022 |
| Coradir       | Coradir/ES10IS5             | [dfc5a02c31](https://linux-hardware.org/?probe=dfc5a02c31) | Mar 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [92bbba70b0](https://linux-hardware.org/?probe=92bbba70b0) | Mar 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [981757ce36](https://linux-hardware.org/?probe=981757ce36) | Mar 28, 2022 |
| Positivo      | Z100                        | [5577927db3](https://linux-hardware.org/?probe=5577927db3) | Mar 27, 2022 |
| ASUSTek       | G75VW                       | [2e006b534b](https://linux-hardware.org/?probe=2e006b534b) | Mar 25, 2022 |
| HP            | Pavilion g6                 | [984b59ccb9](https://linux-hardware.org/?probe=984b59ccb9) | Mar 24, 2022 |
| BGH e-Nova    | Unknown                     | [408be10e82](https://linux-hardware.org/?probe=408be10e82) | Mar 22, 2022 |
| Packard Be... | EasyNote_MX45               | [b7444c471c](https://linux-hardware.org/?probe=b7444c471c) | Mar 21, 2022 |
| Packard Be... | EasyNote_MX45               | [1fbe976538](https://linux-hardware.org/?probe=1fbe976538) | Mar 21, 2022 |
| Packard Be... | EasyNote_MX45               | [b664a23750](https://linux-hardware.org/?probe=b664a23750) | Mar 21, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [c845b9c738](https://linux-hardware.org/?probe=c845b9c738) | Mar 21, 2022 |
| BANGHO        | MAX G0101                   | [b40c195d54](https://linux-hardware.org/?probe=b40c195d54) | Mar 20, 2022 |
| HUAWEI        | KPL-W0X                     | [bd7accdfd5](https://linux-hardware.org/?probe=bd7accdfd5) | Mar 20, 2022 |
| NSX           | SB142G                      | [0a13591ca3](https://linux-hardware.org/?probe=0a13591ca3) | Mar 18, 2022 |
| ASUSTek       | X505BP                      | [3dc5b19d13](https://linux-hardware.org/?probe=3dc5b19d13) | Mar 17, 2022 |
| Positivo      | VJF155F11UAR                | [39b60a2ef4](https://linux-hardware.org/?probe=39b60a2ef4) | Mar 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [25c0bbffe2](https://linux-hardware.org/?probe=25c0bbffe2) | Mar 15, 2022 |
| Lenovo        | Edge 15 80H1                | [bd2b981053](https://linux-hardware.org/?probe=bd2b981053) | Mar 14, 2022 |
| Dell          | Inspiron 5520               | [5d8f77310a](https://linux-hardware.org/?probe=5d8f77310a) | Mar 11, 2022 |
| Dell          | Inspiron 15-5578            | [c31b5d363f](https://linux-hardware.org/?probe=c31b5d363f) | Mar 10, 2022 |
| NOBLEX        | N14WD21                     | [c166ec8175](https://linux-hardware.org/?probe=c166ec8175) | Mar 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [96833919d2](https://linux-hardware.org/?probe=96833919d2) | Mar 08, 2022 |
| Lenovo        | ThinkPad T60 6370A55        | [3a01549416](https://linux-hardware.org/?probe=3a01549416) | Mar 06, 2022 |
| Lenovo        | ThinkPad T60 6370A55        | [48d2d5d234](https://linux-hardware.org/?probe=48d2d5d234) | Mar 06, 2022 |
| Dell          | Latitude E5540              | [52a16c13b1](https://linux-hardware.org/?probe=52a16c13b1) | Mar 06, 2022 |
| Dell          | Inspiron 5593               | [eca1413f3f](https://linux-hardware.org/?probe=eca1413f3f) | Mar 04, 2022 |
| HP            | Pavilion 17                 | [d4a3fb2dfc](https://linux-hardware.org/?probe=d4a3fb2dfc) | Feb 26, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [bf565614ca](https://linux-hardware.org/?probe=bf565614ca) | Feb 24, 2022 |
| Lenovo        | V15-G2-ITL 82KB             | [6d10cb57e1](https://linux-hardware.org/?probe=6d10cb57e1) | Feb 23, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | [1391579931](https://linux-hardware.org/?probe=1391579931) | Feb 21, 2022 |
| HP            | Compaq Presario C700        | [52cff70be5](https://linux-hardware.org/?probe=52cff70be5) | Feb 21, 2022 |
| ASUSTek       | X55C                        | [ae05784a4a](https://linux-hardware.org/?probe=ae05784a4a) | Feb 19, 2022 |
| Samsung       | SQ35S                       | [7f4f9ad483](https://linux-hardware.org/?probe=7f4f9ad483) | Feb 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TES... | [da103e44c5](https://linux-hardware.org/?probe=da103e44c5) | Feb 17, 2022 |
| ASUSTek       | X540UA                      | [681b4aca6f](https://linux-hardware.org/?probe=681b4aca6f) | Feb 16, 2022 |
| Radio Vict... | B34 SLIM                    | [8a100feae7](https://linux-hardware.org/?probe=8a100feae7) | Feb 16, 2022 |
| MSI           | Delta 15 A5EFK              | [0937e1da6a](https://linux-hardware.org/?probe=0937e1da6a) | Feb 14, 2022 |
| MSI           | Delta 15 A5EFK              | [581ebd9976](https://linux-hardware.org/?probe=581ebd9976) | Feb 13, 2022 |
| MSI           | GE62 6QD                    | [fc4efd1eff](https://linux-hardware.org/?probe=fc4efd1eff) | Feb 13, 2022 |
| MSI           | GP72 6QE                    | [d4a2d3bb85](https://linux-hardware.org/?probe=d4a2d3bb85) | Feb 12, 2022 |
| MSI           | GP72 6QE                    | [9409e22a95](https://linux-hardware.org/?probe=9409e22a95) | Feb 12, 2022 |
| Dell          | Inspiron N4010              | [b04de36c04](https://linux-hardware.org/?probe=b04de36c04) | Feb 11, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [0f65488b54](https://linux-hardware.org/?probe=0f65488b54) | Feb 11, 2022 |
| MSI           | GS63VR 6RF                  | [c20c87027e](https://linux-hardware.org/?probe=c20c87027e) | Feb 10, 2022 |
| Sony          | VJFE52A0711H                | [0a29c49c46](https://linux-hardware.org/?probe=0a29c49c46) | Feb 09, 2022 |
| Dell          | Latitude E6410              | [c71db9d118](https://linux-hardware.org/?probe=c71db9d118) | Feb 08, 2022 |
| Dell          | Latitude E6410              | [61aae88463](https://linux-hardware.org/?probe=61aae88463) | Feb 08, 2022 |
| HP            | Pavilion dv6                | [0ba10bc3bb](https://linux-hardware.org/?probe=0ba10bc3bb) | Feb 07, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [c1fe9c81a0](https://linux-hardware.org/?probe=c1fe9c81a0) | Feb 06, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [f92b5e4b44](https://linux-hardware.org/?probe=f92b5e4b44) | Feb 06, 2022 |
| HP            | Laptop 14-bw0xx             | [fa4a95f3a5](https://linux-hardware.org/?probe=fa4a95f3a5) | Feb 03, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [88085159bf](https://linux-hardware.org/?probe=88085159bf) | Jan 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c1494af863](https://linux-hardware.org/?probe=c1494af863) | Jan 30, 2022 |
| Dell          | Inspiron 3505               | [343ab23f97](https://linux-hardware.org/?probe=343ab23f97) | Jan 27, 2022 |
| Lenovo        | G40-80 80E4                 | [4c27ace709](https://linux-hardware.org/?probe=4c27ace709) | Jan 26, 2022 |
| Samsung       | N150P/N210P/N220P           | [72a04dc661](https://linux-hardware.org/?probe=72a04dc661) | Jan 22, 2022 |
| Standard      | MB50II                      | [aa719e1665](https://linux-hardware.org/?probe=aa719e1665) | Jan 22, 2022 |
| Dell          | Latitude 5510               | [ab7eee3de9](https://linux-hardware.org/?probe=ab7eee3de9) | Jan 21, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | [0f956f27ad](https://linux-hardware.org/?probe=0f956f27ad) | Jan 20, 2022 |
| Gadnic        | NOT00A1                     | [f1c6b56aa2](https://linux-hardware.org/?probe=f1c6b56aa2) | Jan 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [b2ac4f1622](https://linux-hardware.org/?probe=b2ac4f1622) | Jan 13, 2022 |
| BANGHO        | MAX G0101                   | [0e5d4dfabf](https://linux-hardware.org/?probe=0e5d4dfabf) | Jan 13, 2022 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | [b5437027b1](https://linux-hardware.org/?probe=b5437027b1) | Jan 12, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [2b44f3e733](https://linux-hardware.org/?probe=2b44f3e733) | Jan 12, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [137736d936](https://linux-hardware.org/?probe=137736d936) | Jan 11, 2022 |
| HUAWEI        | MACH-WX9                    | [1c3636c882](https://linux-hardware.org/?probe=1c3636c882) | Jan 11, 2022 |
| Samsung       | N150P/N210P/N220P           | [7d5ceb70bb](https://linux-hardware.org/?probe=7d5ceb70bb) | Jan 10, 2022 |
| HUAWEI        | MACH-WX9                    | [2e91b4b88c](https://linux-hardware.org/?probe=2e91b4b88c) | Jan 10, 2022 |
| Apple         | MacBookPro13,3              | [6b1eb1745e](https://linux-hardware.org/?probe=6b1eb1745e) | Jan 10, 2022 |
| Positivo      | VJF155F11UAR                | [9ac42b2131](https://linux-hardware.org/?probe=9ac42b2131) | Jan 04, 2022 |
| Positivo      | VJF155F11UAR                | [e8bc9392ff](https://linux-hardware.org/?probe=e8bc9392ff) | Jan 04, 2022 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | [b6b0572310](https://linux-hardware.org/?probe=b6b0572310) | Jan 02, 2022 |
| HUAWEI        | MACH-WX9                    | [dfa1412d12](https://linux-hardware.org/?probe=dfa1412d12) | Jan 01, 2022 |
| Dell          | Latitude E5540              | [1a112d75bc](https://linux-hardware.org/?probe=1a112d75bc) | Jan 01, 2022 |
| Exo           | HR14                        | [3a16049e36](https://linux-hardware.org/?probe=3a16049e36) | Dec 31, 2021 |
| Exo           | HR14                        | [8c3bf46eb1](https://linux-hardware.org/?probe=8c3bf46eb1) | Dec 31, 2021 |
| Dell          | Inspiron 3505               | [c05333a0bc](https://linux-hardware.org/?probe=c05333a0bc) | Dec 31, 2021 |
| Intel         | Crestline & ICH8M Chipse... | [286566a874](https://linux-hardware.org/?probe=286566a874) | Dec 31, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9d60e196d4](https://linux-hardware.org/?probe=9d60e196d4) | Dec 31, 2021 |
| Lenovo        | G40-80 80E4                 | [993fe7cef6](https://linux-hardware.org/?probe=993fe7cef6) | Dec 30, 2021 |
| HP            | 15                          | [e0d79905e2](https://linux-hardware.org/?probe=e0d79905e2) | Dec 29, 2021 |
| Lenovo        | G470 20078                  | [d860437585](https://linux-hardware.org/?probe=d860437585) | Dec 28, 2021 |
| Samsung       | 300E4A/300E5A/300E7A        | [8c9f72d757](https://linux-hardware.org/?probe=8c9f72d757) | Dec 27, 2021 |
| System76      | Lemur Pro                   | [6dbfd95ccb](https://linux-hardware.org/?probe=6dbfd95ccb) | Dec 27, 2021 |
| HP            | Laptop 14-dk1xxx            | [ab7902b875](https://linux-hardware.org/?probe=ab7902b875) | Dec 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [da08b0d873](https://linux-hardware.org/?probe=da08b0d873) | Dec 22, 2021 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [64492ac63b](https://linux-hardware.org/?probe=64492ac63b) | Dec 22, 2021 |
| Dell          | Inspiron 3583               | [aaab97a820](https://linux-hardware.org/?probe=aaab97a820) | Dec 19, 2021 |
| System76      | Lemur Pro                   | [aebe0acb39](https://linux-hardware.org/?probe=aebe0acb39) | Dec 18, 2021 |
| Compaq        | Presario 21                 | [86e7a85db3](https://linux-hardware.org/?probe=86e7a85db3) | Dec 16, 2021 |
| Samsung       | 300E4A/300E5A/300E7A        | [915303d28d](https://linux-hardware.org/?probe=915303d28d) | Dec 16, 2021 |
| HP            | Compaq Presario CQ40        | [15d1b4bba5](https://linux-hardware.org/?probe=15d1b4bba5) | Dec 16, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [4c02cd3e26](https://linux-hardware.org/?probe=4c02cd3e26) | Dec 15, 2021 |
| Lenovo        | ThinkPad X230 23254UY       | [99dbb19723](https://linux-hardware.org/?probe=99dbb19723) | Dec 15, 2021 |
| HONOR         | HLYL-WXX9                   | [0b6a9394b4](https://linux-hardware.org/?probe=0b6a9394b4) | Dec 15, 2021 |
| Lenovo        | ThinkPad X230 23252CG       | [e2ed9e27c3](https://linux-hardware.org/?probe=e2ed9e27c3) | Dec 14, 2021 |
| ASUSTek       | X541UAK                     | [9c83d97134](https://linux-hardware.org/?probe=9c83d97134) | Dec 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [6df961216e](https://linux-hardware.org/?probe=6df961216e) | Dec 12, 2021 |
| Toshiba       | TE5                         | [fb39721f00](https://linux-hardware.org/?probe=fb39721f00) | Dec 10, 2021 |
| Lenovo        | ThinkPad T450 20BUS0100G    | [44fb1a2d77](https://linux-hardware.org/?probe=44fb1a2d77) | Dec 09, 2021 |
| System76      | Lemur Pro                   | [6e54a15cf2](https://linux-hardware.org/?probe=6e54a15cf2) | Dec 08, 2021 |
| Exo           | C14C                        | [2e0765b245](https://linux-hardware.org/?probe=2e0765b245) | Dec 08, 2021 |
| Exo           | C14C                        | [1d4221ab9e](https://linux-hardware.org/?probe=1d4221ab9e) | Dec 06, 2021 |
| Positivo      | AT300b                      | [20b3635188](https://linux-hardware.org/?probe=20b3635188) | Dec 06, 2021 |
| Acer          | Aspire 5251                 | [30ef0eefda](https://linux-hardware.org/?probe=30ef0eefda) | Dec 04, 2021 |
| HP            | 250 G7 Notebook PC          | [3f21e28b42](https://linux-hardware.org/?probe=3f21e28b42) | Dec 03, 2021 |
| BANGHO        | CLOUD                       | [214c91e455](https://linux-hardware.org/?probe=214c91e455) | Dec 01, 2021 |
| BANGHO        | MOV                         | [3e5867cd6a](https://linux-hardware.org/?probe=3e5867cd6a) | Dec 01, 2021 |
| Exo           | Smart Serie M               | [cbf705cf51](https://linux-hardware.org/?probe=cbf705cf51) | Nov 22, 2021 |
| ASUSTek       | G551JW                      | [5f018a92ee](https://linux-hardware.org/?probe=5f018a92ee) | Nov 21, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [8dfec492a4](https://linux-hardware.org/?probe=8dfec492a4) | Nov 19, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [78341a1a16](https://linux-hardware.org/?probe=78341a1a16) | Nov 19, 2021 |
| Acer          | Aspire ES1-572              | [871bd7121a](https://linux-hardware.org/?probe=871bd7121a) | Nov 11, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [c282ff2172](https://linux-hardware.org/?probe=c282ff2172) | Nov 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [eb66540889](https://linux-hardware.org/?probe=eb66540889) | Nov 10, 2021 |
| Lenovo        | 14w 81MQ00AHAR              | [17785cda04](https://linux-hardware.org/?probe=17785cda04) | Nov 09, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [fbc9822ad6](https://linux-hardware.org/?probe=fbc9822ad6) | Nov 09, 2021 |
| Quanta        | TW9/SW9                     | [86643edf2a](https://linux-hardware.org/?probe=86643edf2a) | Nov 06, 2021 |
| BANGHO        | MOV                         | [9c2b56129e](https://linux-hardware.org/?probe=9c2b56129e) | Nov 06, 2021 |
| Lenovo        | G40-80 80E4                 | [57b9418a9c](https://linux-hardware.org/?probe=57b9418a9c) | Nov 05, 2021 |
| ASUSTek       | K52JT                       | [1f65cc3bef](https://linux-hardware.org/?probe=1f65cc3bef) | Nov 05, 2021 |
| HP            | 15                          | [0719e191d4](https://linux-hardware.org/?probe=0719e191d4) | Nov 04, 2021 |
| HP            | 630                         | [f01c95d959](https://linux-hardware.org/?probe=f01c95d959) | Nov 03, 2021 |
| Lenovo        | ThinkPad Edge E430 3254T... | [f9fbde199a](https://linux-hardware.org/?probe=f9fbde199a) | Nov 02, 2021 |
| Lenovo        | G40-80 80E4                 | [f89ddc0ebd](https://linux-hardware.org/?probe=f89ddc0ebd) | Nov 02, 2021 |
| Intel         | HURONRIVER                  | [5ded89b4a5](https://linux-hardware.org/?probe=5ded89b4a5) | Nov 02, 2021 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | [3da20846f5](https://linux-hardware.org/?probe=3da20846f5) | Oct 26, 2021 |
| Notebook      | W94_95_97SU2,SUY,-C,-T      | [2d19155e7f](https://linux-hardware.org/?probe=2d19155e7f) | Oct 26, 2021 |
| HP            | Pavilion dv4                | [f0ae431e2c](https://linux-hardware.org/?probe=f0ae431e2c) | Oct 26, 2021 |
| Apple         | MacBookPro9,2               | [c739ed76e3](https://linux-hardware.org/?probe=c739ed76e3) | Oct 26, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [7877fc09ba](https://linux-hardware.org/?probe=7877fc09ba) | Oct 22, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [3115478a9b](https://linux-hardware.org/?probe=3115478a9b) | Oct 20, 2021 |
| Apple         | MacBookAir4,2               | [f092832b93](https://linux-hardware.org/?probe=f092832b93) | Oct 19, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [0290c2ca6d](https://linux-hardware.org/?probe=0290c2ca6d) | Oct 19, 2021 |
| Toshiba       | Satellite A505              | [a955d2e293](https://linux-hardware.org/?probe=a955d2e293) | Oct 18, 2021 |
| Dell          | Inspiron 5423               | [f31078afd8](https://linux-hardware.org/?probe=f31078afd8) | Oct 18, 2021 |
| Apple         | MacBook3,1                  | [34fc60e37e](https://linux-hardware.org/?probe=34fc60e37e) | Oct 16, 2021 |
| HP            | Pavilion dv2000 (RD261LA... | [9f722a52d9](https://linux-hardware.org/?probe=9f722a52d9) | Oct 15, 2021 |
| HP            | Mini 110-3000               | [ee2ce4e3b9](https://linux-hardware.org/?probe=ee2ce4e3b9) | Oct 14, 2021 |
| NOBLEX        | E11IS2                      | [463e1f38e8](https://linux-hardware.org/?probe=463e1f38e8) | Oct 14, 2021 |
| Lenovo        | V330-15IKB 81AX             | [000ac750e0](https://linux-hardware.org/?probe=000ac750e0) | Oct 13, 2021 |
| Lenovo        | Z50-70 20354                | [a852927b57](https://linux-hardware.org/?probe=a852927b57) | Oct 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [1bea81fd91](https://linux-hardware.org/?probe=1bea81fd91) | Oct 10, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [d5ea22ef16](https://linux-hardware.org/?probe=d5ea22ef16) | Oct 09, 2021 |
| Dell          | Latitude 5480               | [3ed90a1781](https://linux-hardware.org/?probe=3ed90a1781) | Oct 07, 2021 |
| Apple         | MacBookAir4,2               | [8163e064d3](https://linux-hardware.org/?probe=8163e064d3) | Oct 07, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [c111f21064](https://linux-hardware.org/?probe=c111f21064) | Oct 05, 2021 |
| Lenovo        | Z50-70 20354                | [beda62c6f4](https://linux-hardware.org/?probe=beda62c6f4) | Oct 05, 2021 |
| Dell          | G3 3779                     | [0257eadb71](https://linux-hardware.org/?probe=0257eadb71) | Oct 04, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [bea39ba8be](https://linux-hardware.org/?probe=bea39ba8be) | Oct 03, 2021 |
| Dell          | Inspiron 15-3552            | [f1b660b91c](https://linux-hardware.org/?probe=f1b660b91c) | Oct 02, 2021 |
| Acer          | Aspire E5-432               | [2d6ea0cb46](https://linux-hardware.org/?probe=2d6ea0cb46) | Oct 02, 2021 |
| Lenovo        | ThinkPad E495 20NES0RR00    | [016f532a15](https://linux-hardware.org/?probe=016f532a15) | Oct 02, 2021 |
| HP            | EliteBook 840 G6            | [cd2412d37e](https://linux-hardware.org/?probe=cd2412d37e) | Oct 01, 2021 |
| ASUSTek       | K53E                        | [c98e6e26ce](https://linux-hardware.org/?probe=c98e6e26ce) | Oct 01, 2021 |
| Exo           | SmartPro Q6                 | [5986a21d65](https://linux-hardware.org/?probe=5986a21d65) | Sep 30, 2021 |
| Lenovo        | ThinkPad T470 20HES57W00    | [482453f90b](https://linux-hardware.org/?probe=482453f90b) | Sep 30, 2021 |
| Lenovo        | V15-IIL 82C5                | [781b63209d](https://linux-hardware.org/?probe=781b63209d) | Sep 28, 2021 |
| Acer          | Aspire 2930Z                | [95cf81718f](https://linux-hardware.org/?probe=95cf81718f) | Sep 28, 2021 |
| Dell          | Inspiron 3583               | [f936e50be4](https://linux-hardware.org/?probe=f936e50be4) | Sep 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [445b864b6e](https://linux-hardware.org/?probe=445b864b6e) | Sep 25, 2021 |
| HUAWEI        | NBLB-WAX9N                  | [9d25d0c5c7](https://linux-hardware.org/?probe=9d25d0c5c7) | Sep 21, 2021 |
| Acer          | Aspire 2930Z                | [837506804e](https://linux-hardware.org/?probe=837506804e) | Sep 20, 2021 |
| Acer          | Aspire 2930Z                | [720324554e](https://linux-hardware.org/?probe=720324554e) | Sep 20, 2021 |
| Acer          | Aspire 2930Z                | [85e19ff9ba](https://linux-hardware.org/?probe=85e19ff9ba) | Sep 20, 2021 |
| Lenovo        | V330-15IKB 81AX             | [9d10bffde2](https://linux-hardware.org/?probe=9d10bffde2) | Sep 18, 2021 |
| Lenovo        | ThinkPad E460 20EUA00AAC    | [c7d8dc11ca](https://linux-hardware.org/?probe=c7d8dc11ca) | Sep 15, 2021 |
| Lenovo        | G480 20150                  | [d7d8be3a08](https://linux-hardware.org/?probe=d7d8be3a08) | Sep 15, 2021 |
| Lenovo        | V330-15IKB 81AX             | [a062985645](https://linux-hardware.org/?probe=a062985645) | Sep 14, 2021 |
| Toshiba       | QOSMIO X75-A                | [8c87a96580](https://linux-hardware.org/?probe=8c87a96580) | Sep 14, 2021 |
| Toshiba       | QOSMIO X75-A                | [7fbbeca526](https://linux-hardware.org/?probe=7fbbeca526) | Sep 13, 2021 |
| Positivo      | SW6H                        | [2653f4ff4b](https://linux-hardware.org/?probe=2653f4ff4b) | Sep 12, 2021 |
| Dell          | Inspiron 1525               | [c9a8c369e7](https://linux-hardware.org/?probe=c9a8c369e7) | Sep 10, 2021 |
| IBM           | ThinkPad T41 23737JY        | [86cf78a3cf](https://linux-hardware.org/?probe=86cf78a3cf) | Sep 09, 2021 |
| HP            | Laptop 15s-eq0xxx           | [361beeda3d](https://linux-hardware.org/?probe=361beeda3d) | Sep 08, 2021 |
| Lenovo        | ThinkPad T430 2349D10       | [11ab5d413d](https://linux-hardware.org/?probe=11ab5d413d) | Sep 08, 2021 |
| Intel         | Pine Trail - M Revision ... | [147f6959ad](https://linux-hardware.org/?probe=147f6959ad) | Sep 08, 2021 |
| Sony          | Serie VJC14                 | [27828e1dfb](https://linux-hardware.org/?probe=27828e1dfb) | Sep 07, 2021 |
| Sony          | Serie VJC14                 | [4c1200e7cf](https://linux-hardware.org/?probe=4c1200e7cf) | Sep 07, 2021 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [409ed1f8a4](https://linux-hardware.org/?probe=409ed1f8a4) | Sep 06, 2021 |
| Lenovo        | V330-15IKB 81AX             | [797db05baf](https://linux-hardware.org/?probe=797db05baf) | Sep 06, 2021 |
| Lenovo        | ThinkPad E15 20RD002RUS     | [2140460960](https://linux-hardware.org/?probe=2140460960) | Sep 03, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0e9da9320c](https://linux-hardware.org/?probe=0e9da9320c) | Sep 03, 2021 |
| Lenovo        | G470 20078                  | [b480871bf8](https://linux-hardware.org/?probe=b480871bf8) | Sep 02, 2021 |
| BANGHO        | MAX G0101                   | [88ac236a11](https://linux-hardware.org/?probe=88ac236a11) | Aug 29, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V6545        | [f597bdfe1a](https://linux-hardware.org/?probe=f597bdfe1a) | Aug 29, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [97afdfd346](https://linux-hardware.org/?probe=97afdfd346) | Aug 29, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [50477e1758](https://linux-hardware.org/?probe=50477e1758) | Aug 27, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | [d51c8093ec](https://linux-hardware.org/?probe=d51c8093ec) | Aug 27, 2021 |
| BANGHO        | MOV                         | [9bacff92e1](https://linux-hardware.org/?probe=9bacff92e1) | Aug 25, 2021 |
| Positivo      | Unknown                     | [28bac734c5](https://linux-hardware.org/?probe=28bac734c5) | Aug 24, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [be114a1393](https://linux-hardware.org/?probe=be114a1393) | Aug 23, 2021 |
| Dell          | Latitude 7400               | [61fd9efe24](https://linux-hardware.org/?probe=61fd9efe24) | Aug 21, 2021 |
| Dell          | Inspiron 5559               | [768bf35df4](https://linux-hardware.org/?probe=768bf35df4) | Aug 20, 2021 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [6d7fb6d592](https://linux-hardware.org/?probe=6d7fb6d592) | Aug 19, 2021 |
| Dell          | Inspiron N4010              | [c83e0428a8](https://linux-hardware.org/?probe=c83e0428a8) | Aug 17, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | [6e32aa4ffd](https://linux-hardware.org/?probe=6e32aa4ffd) | Aug 17, 2021 |
| Lenovo        | B50-80 80EW                 | [f8af262ae5](https://linux-hardware.org/?probe=f8af262ae5) | Aug 13, 2021 |
| Lenovo        | V330-15IKB 81AX             | [668328ae19](https://linux-hardware.org/?probe=668328ae19) | Aug 12, 2021 |
| Lenovo        | G40-80 80E4                 | [acd155c49f](https://linux-hardware.org/?probe=acd155c49f) | Aug 11, 2021 |
| Lenovo        | ThinkPad X250 20CMCTO1WW    | [c3b36c30d8](https://linux-hardware.org/?probe=c3b36c30d8) | Aug 09, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [76ee9bfbac](https://linux-hardware.org/?probe=76ee9bfbac) | Aug 06, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [8f1124f1fd](https://linux-hardware.org/?probe=8f1124f1fd) | Aug 06, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [a4ba68cc4e](https://linux-hardware.org/?probe=a4ba68cc4e) | Aug 06, 2021 |
| Lenovo        | IdeaPad U310                | [f57c372664](https://linux-hardware.org/?probe=f57c372664) | Aug 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [d09a20ffb6](https://linux-hardware.org/?probe=d09a20ffb6) | Aug 02, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | [9452fd6e14](https://linux-hardware.org/?probe=9452fd6e14) | Aug 02, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [d1450d6167](https://linux-hardware.org/?probe=d1450d6167) | Jul 30, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [c5adb7024d](https://linux-hardware.org/?probe=c5adb7024d) | Jul 30, 2021 |
| Lenovo        | G485                        | [1b8322cbee](https://linux-hardware.org/?probe=1b8322cbee) | Jul 29, 2021 |
| Lenovo        | G485                        | [19fb967e90](https://linux-hardware.org/?probe=19fb967e90) | Jul 29, 2021 |
| HP            | Compaq Presario CQ40        | [14b629549c](https://linux-hardware.org/?probe=14b629549c) | Jul 27, 2021 |
| Positivo      | Unknown                     | [f64cbc61eb](https://linux-hardware.org/?probe=f64cbc61eb) | Jul 26, 2021 |
| HP            | Compaq Presario CQ40        | [b82622eb33](https://linux-hardware.org/?probe=b82622eb33) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [bd29e505b9](https://linux-hardware.org/?probe=bd29e505b9) | Jul 24, 2021 |
| Lenovo        | G485                        | [0810c75be3](https://linux-hardware.org/?probe=0810c75be3) | Jul 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [87370c4ac2](https://linux-hardware.org/?probe=87370c4ac2) | Jul 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [b5194fe4e7](https://linux-hardware.org/?probe=b5194fe4e7) | Jul 20, 2021 |
| Lenovo        | G485                        | [aa805dfe8d](https://linux-hardware.org/?probe=aa805dfe8d) | Jul 20, 2021 |
| HP            | ENVY Spectre XT Ultraboo... | [bf877db72a](https://linux-hardware.org/?probe=bf877db72a) | Jul 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [03ffd337ec](https://linux-hardware.org/?probe=03ffd337ec) | Jul 16, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [2d432c99d0](https://linux-hardware.org/?probe=2d432c99d0) | Jul 13, 2021 |
| HP            | 250 G5 Notebook PC          | [f7013f52d0](https://linux-hardware.org/?probe=f7013f52d0) | Jul 12, 2021 |
| ASUSTek       | N53SV                       | [8044015dd8](https://linux-hardware.org/?probe=8044015dd8) | Jul 12, 2021 |
| HP            | ProBook 445 G7              | [4f0ee9421b](https://linux-hardware.org/?probe=4f0ee9421b) | Jul 12, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [8f5ed33e46](https://linux-hardware.org/?probe=8f5ed33e46) | Jul 12, 2021 |
| Dell          | G3 3779                     | [2b3dc1130d](https://linux-hardware.org/?probe=2b3dc1130d) | Jul 09, 2021 |
| Dell          | G3 3779                     | [a7bcade120](https://linux-hardware.org/?probe=a7bcade120) | Jul 09, 2021 |
| Dell          | Latitude 3510               | [c98fdfc9bc](https://linux-hardware.org/?probe=c98fdfc9bc) | Jul 06, 2021 |
| Toshiba       | Unknown                     | [fd862ec37e](https://linux-hardware.org/?probe=fd862ec37e) | Jul 05, 2021 |
| Dell          | Latitude 3510               | [0b97d64290](https://linux-hardware.org/?probe=0b97d64290) | Jul 03, 2021 |
| Dell          | Latitude 7490               | [a57352ca65](https://linux-hardware.org/?probe=a57352ca65) | Jul 02, 2021 |
| System76      | Oryx Pro                    | [7ccf59ae28](https://linux-hardware.org/?probe=7ccf59ae28) | Jun 28, 2021 |
| Dell          | Latitude E6400              | [d638a1b2b6](https://linux-hardware.org/?probe=d638a1b2b6) | Jun 28, 2021 |
| Dell          | Inspiron 7773               | [fb0644646a](https://linux-hardware.org/?probe=fb0644646a) | Jun 28, 2021 |
| ASUSTek       | X455LJ                      | [b8a939ca9c](https://linux-hardware.org/?probe=b8a939ca9c) | Jun 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T9S... | [795eda0f4c](https://linux-hardware.org/?probe=795eda0f4c) | Jun 27, 2021 |
| HP            | Pavilion dv6                | [13f36adbb0](https://linux-hardware.org/?probe=13f36adbb0) | Jun 27, 2021 |
| Lenovo        | ThinkPad E14 20RBS1RA00     | [d555c56ade](https://linux-hardware.org/?probe=d555c56ade) | Jun 27, 2021 |
| HP            | Pavilion dv7                | [590ba6b3a3](https://linux-hardware.org/?probe=590ba6b3a3) | Jun 23, 2021 |
| Acer          | Aspire E5-573               | [22e59e4d90](https://linux-hardware.org/?probe=22e59e4d90) | Jun 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3489fe1584](https://linux-hardware.org/?probe=3489fe1584) | Jun 18, 2021 |
| BANGHO        | MAX G5 i1                   | [ca05e3a059](https://linux-hardware.org/?probe=ca05e3a059) | Jun 15, 2021 |
| HP            | 250 G5 Notebook PC          | [4699d3c195](https://linux-hardware.org/?probe=4699d3c195) | Jun 10, 2021 |
| Pegatron      | A15                         | [9156525a1e](https://linux-hardware.org/?probe=9156525a1e) | Jun 06, 2021 |
| Acer          | Aspire V3-551               | [ba274d73f0](https://linux-hardware.org/?probe=ba274d73f0) | Jun 04, 2021 |
| HP            | Pavilion Notebook           | [a4feb93464](https://linux-hardware.org/?probe=a4feb93464) | Jun 02, 2021 |
| ASUSTek       | X541NA                      | [daad255c87](https://linux-hardware.org/?probe=daad255c87) | Jun 01, 2021 |
| Sony          | VGN-NR230FE                 | [b97d7a8c66](https://linux-hardware.org/?probe=b97d7a8c66) | Jun 01, 2021 |
| HP            | Compaq tc4400 (GE179UP#A... | [eeaee9f1ad](https://linux-hardware.org/?probe=eeaee9f1ad) | Jun 01, 2021 |
| ADMIRAL       | ADC14                       | [1cd2066013](https://linux-hardware.org/?probe=1cd2066013) | May 29, 2021 |
| ADMIRAL       | ADC14                       | [d3955b8ca9](https://linux-hardware.org/?probe=d3955b8ca9) | May 29, 2021 |
| A-DATA Tec... | XENIA159GENI72060           | [eee4dbbb99](https://linux-hardware.org/?probe=eee4dbbb99) | May 28, 2021 |
| Acer          | Aspire ES1-572              | [2dd5a68280](https://linux-hardware.org/?probe=2dd5a68280) | May 27, 2021 |
| Sony          | VPCEH35FM                   | [f88d733f75](https://linux-hardware.org/?probe=f88d733f75) | May 27, 2021 |
| Sony          | VPCEH35FM                   | [309cc53bcf](https://linux-hardware.org/?probe=309cc53bcf) | May 27, 2021 |
| Lenovo        | G40-30 80FY                 | [a890a2c019](https://linux-hardware.org/?probe=a890a2c019) | May 26, 2021 |
| ASUSTek       | X555UJ                      | [9c148a1665](https://linux-hardware.org/?probe=9c148a1665) | May 25, 2021 |
| A-DATA Tec... | XENIA159GENI72060           | [e4c4563465](https://linux-hardware.org/?probe=e4c4563465) | May 24, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [f8b9508953](https://linux-hardware.org/?probe=f8b9508953) | May 24, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [170b220f5b](https://linux-hardware.org/?probe=170b220f5b) | May 23, 2021 |
| Samsung       | N150P/N210P/N220P           | [d4548d357f](https://linux-hardware.org/?probe=d4548d357f) | May 22, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [5756ecab4b](https://linux-hardware.org/?probe=5756ecab4b) | May 22, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [0f8deb2aeb](https://linux-hardware.org/?probe=0f8deb2aeb) | May 21, 2021 |
| Lenovo        | V15-ADA 82C7                | [a36a726bba](https://linux-hardware.org/?probe=a36a726bba) | May 18, 2021 |
| Dell          | Latitude 7490               | [b3010001a3](https://linux-hardware.org/?probe=b3010001a3) | May 18, 2021 |
| Dell          | Inspiron 1440               | [d0f761fa17](https://linux-hardware.org/?probe=d0f761fa17) | May 17, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [e32d9effa0](https://linux-hardware.org/?probe=e32d9effa0) | May 17, 2021 |
| Coradir       | Coradir/ES10IS5             | [60844ab595](https://linux-hardware.org/?probe=60844ab595) | May 17, 2021 |
| Coradir       | Coradir/ES10IS5             | [acae784622](https://linux-hardware.org/?probe=acae784622) | May 17, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [df1bd5c40d](https://linux-hardware.org/?probe=df1bd5c40d) | May 16, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [86de26c862](https://linux-hardware.org/?probe=86de26c862) | May 16, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [1ce350fb27](https://linux-hardware.org/?probe=1ce350fb27) | May 16, 2021 |
| Sony          | VPCEG11FX                   | [b17f63c46c](https://linux-hardware.org/?probe=b17f63c46c) | May 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [d311e9743d](https://linux-hardware.org/?probe=d311e9743d) | May 15, 2021 |
| Dell          | Inspiron 14-3467            | [511f638394](https://linux-hardware.org/?probe=511f638394) | May 14, 2021 |
| Lenovo        | G40-30 80FY                 | [822f3e9a7d](https://linux-hardware.org/?probe=822f3e9a7d) | May 13, 2021 |
| HP            | ENVY Spectre XT Ultraboo... | [b59cb43ed6](https://linux-hardware.org/?probe=b59cb43ed6) | May 13, 2021 |
| Lenovo        | ThinkPad T490s 20NYS04V0... | [18da93a841](https://linux-hardware.org/?probe=18da93a841) | May 12, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [942ece6e49](https://linux-hardware.org/?probe=942ece6e49) | May 12, 2021 |
| HP            | Pavilion Notebook           | [435e18816a](https://linux-hardware.org/?probe=435e18816a) | May 12, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [c9b4ee21fd](https://linux-hardware.org/?probe=c9b4ee21fd) | May 10, 2021 |
| Dell          | Inspiron 14-3467            | [2fd207a33d](https://linux-hardware.org/?probe=2fd207a33d) | May 10, 2021 |
| Dell          | Inspiron 14-3467            | [173baf5fdb](https://linux-hardware.org/?probe=173baf5fdb) | May 09, 2021 |
| Toshiba       | Satellite P55t-B            | [e7f87f2061](https://linux-hardware.org/?probe=e7f87f2061) | May 08, 2021 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [e313b9e956](https://linux-hardware.org/?probe=e313b9e956) | May 06, 2021 |
| Acer          | AOD255E                     | [202573d3f1](https://linux-hardware.org/?probe=202573d3f1) | May 02, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3401ccaf08](https://linux-hardware.org/?probe=3401ccaf08) | Apr 30, 2021 |
| Acer          | Aspire A315-56              | [ab06ace460](https://linux-hardware.org/?probe=ab06ace460) | Apr 29, 2021 |
| Samsung       | 300E4A/300E5A/300E7A        | [b4ec0e1cfe](https://linux-hardware.org/?probe=b4ec0e1cfe) | Apr 29, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | [c5ed725f00](https://linux-hardware.org/?probe=c5ed725f00) | Apr 29, 2021 |
| HP            | EliteBook 820 G3            | [26c2c579ee](https://linux-hardware.org/?probe=26c2c579ee) | Apr 28, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [90bc32f31e](https://linux-hardware.org/?probe=90bc32f31e) | Apr 27, 2021 |
| Unknown       | Unknown                     | [e45a412c3d](https://linux-hardware.org/?probe=e45a412c3d) | Apr 26, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [323f443cc2](https://linux-hardware.org/?probe=323f443cc2) | Apr 26, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [5e53a72f7f](https://linux-hardware.org/?probe=5e53a72f7f) | Apr 25, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [32062fd103](https://linux-hardware.org/?probe=32062fd103) | Apr 25, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [fab2c07bc0](https://linux-hardware.org/?probe=fab2c07bc0) | Apr 24, 2021 |
| Dell          | Inspiron 7375               | [94102dff26](https://linux-hardware.org/?probe=94102dff26) | Apr 24, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d6081e3a7f](https://linux-hardware.org/?probe=d6081e3a7f) | Apr 24, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [c76e692770](https://linux-hardware.org/?probe=c76e692770) | Apr 23, 2021 |
| HP            | G42                         | [3f45a4f9fb](https://linux-hardware.org/?probe=3f45a4f9fb) | Apr 21, 2021 |
| HP            | G42                         | [053f83f355](https://linux-hardware.org/?probe=053f83f355) | Apr 20, 2021 |
| Coradir       | Coradir/ES10IS5             | [74f5215b3f](https://linux-hardware.org/?probe=74f5215b3f) | Apr 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [81567e2bff](https://linux-hardware.org/?probe=81567e2bff) | Apr 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e813571c48](https://linux-hardware.org/?probe=e813571c48) | Apr 20, 2021 |
| NOBLEX        | SF20BA                      | [565b65be26](https://linux-hardware.org/?probe=565b65be26) | Apr 18, 2021 |
| Lenovo        | V330-14ARR 81B1             | [d79109ba72](https://linux-hardware.org/?probe=d79109ba72) | Apr 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [530547c053](https://linux-hardware.org/?probe=530547c053) | Apr 14, 2021 |
| ASHI          | Unknown                     | [68a2b34c2f](https://linux-hardware.org/?probe=68a2b34c2f) | Apr 12, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [76b41f73e8](https://linux-hardware.org/?probe=76b41f73e8) | Apr 11, 2021 |
| HP            | Pavilion 17                 | [d2e2723620](https://linux-hardware.org/?probe=d2e2723620) | Apr 09, 2021 |
| HP            | Pavilion dv2000 (RD261LA... | [c3c1aa5184](https://linux-hardware.org/?probe=c3c1aa5184) | Apr 05, 2021 |
| HP            | Pavilion dv2000 (RD261LA... | [8d8f1e3c82](https://linux-hardware.org/?probe=8d8f1e3c82) | Apr 05, 2021 |
| PCBOX         | Kant                        | [b7f72a7573](https://linux-hardware.org/?probe=b7f72a7573) | Apr 02, 2021 |
| Dell          | Latitude 5510               | [a7de662ab0](https://linux-hardware.org/?probe=a7de662ab0) | Mar 29, 2021 |
| Dell          | Latitude 5510               | [90267d4625](https://linux-hardware.org/?probe=90267d4625) | Mar 29, 2021 |
| Compal        | NBLBX                       | [37080a9fbd](https://linux-hardware.org/?probe=37080a9fbd) | Mar 29, 2021 |
| Lenovo        | V330-15IKB 81AX             | [efff6e4c8c](https://linux-hardware.org/?probe=efff6e4c8c) | Mar 28, 2021 |
| Compal        | NBLBX                       | [3dcb5c4719](https://linux-hardware.org/?probe=3dcb5c4719) | Mar 27, 2021 |
| Coradir       | Coradir/ES10IS5             | [da31536305](https://linux-hardware.org/?probe=da31536305) | Mar 26, 2021 |
| Dell          | Inspiron 5558               | [49c7a18f18](https://linux-hardware.org/?probe=49c7a18f18) | Mar 25, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | [78d08afb9f](https://linux-hardware.org/?probe=78d08afb9f) | Mar 23, 2021 |
| Lenovo        | ThinkPad X390 20Q1S01J00    | [a67fd9412a](https://linux-hardware.org/?probe=a67fd9412a) | Mar 21, 2021 |
| Lenovo        | V330-15IKB 81AX             | [dde152f842](https://linux-hardware.org/?probe=dde152f842) | Mar 19, 2021 |
| Exo           | Smart Serie C               | [ac4e591b39](https://linux-hardware.org/?probe=ac4e591b39) | Mar 18, 2021 |
| HP            | Compaq Presario CQ50        | [d548875719](https://linux-hardware.org/?probe=d548875719) | Mar 18, 2021 |
| Compal        | QAT10                       | [e0096fed67](https://linux-hardware.org/?probe=e0096fed67) | Mar 17, 2021 |
| Compal        | QAT10                       | [9886710c4a](https://linux-hardware.org/?probe=9886710c4a) | Mar 17, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Argentina/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 130       | 11.1%   |
| Ubuntu 18.04                 | 100       | 8.54%   |
| Ubuntu 22.04                 | 83        | 7.09%   |
| Debian 11                    | 42        | 3.59%   |
| OpenMandriva 4.2             | 24        | 2.05%   |
| Zorin 15                     | 21        | 1.79%   |
| Arch Rolling                 | 21        | 1.79%   |
| OpenMandriva 4.3             | 20        | 1.71%   |
| Zorin 16                     | 18        | 1.54%   |
| Pop!_OS 22.04                | 17        | 1.45%   |
| BlackPanther 18.1            | 17        | 1.45%   |
| Manjaro                      | 15        | 1.28%   |
| Linux Mint 21.1              | 15        | 1.28%   |
| Linux Mint 20.2              | 15        | 1.28%   |
| Fedora 36                    | 15        | 1.28%   |
| Arch                         | 15        | 1.28%   |
| Linux Mint 20.3              | 14        | 1.2%    |
| Linux Mint 20.1              | 14        | 1.2%    |
| Linux Mint 20                | 14        | 1.2%    |
| OpenMandriva 23.03           | 13        | 1.11%   |
| Fedora 38                    | 13        | 1.11%   |
| Fedora 33                    | 13        | 1.11%   |
| ArcoLinux Rolling            | 13        | 1.11%   |
| Xubuntu 20.04                | 12        | 1.02%   |
| Ubuntu 19.04                 | 12        | 1.02%   |
| Linux Mint 19.3              | 12        | 1.02%   |
| Debian 10                    | 12        | 1.02%   |
| Linux Mint 21.2              | 11        | 0.94%   |
| Ubuntu 18.10                 | 10        | 0.85%   |
| Fedora 37                    | 10        | 0.85%   |
| Fedora 34                    | 10        | 0.85%   |
| openSUSE Tumbleweed-XXXXXXXX | 9         | 0.77%   |
| Fedora 32                    | 9         | 0.77%   |
| Ubuntu 19.10                 | 8         | 0.68%   |
| Kubuntu 22.04                | 8         | 0.68%   |
| KDE neon 20.04               | 8         | 0.68%   |
| Fedora 35                    | 8         | 0.68%   |
| Xubuntu 18.04                | 7         | 0.6%    |
| Ubuntu 22.10                 | 7         | 0.6%    |
| Ubuntu 21.10                 | 7         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 367       | 32.94%  |
| Linux Mint    | 103       | 9.25%   |
| Fedora        | 77        | 6.91%   |
| Debian        | 70        | 6.28%   |
| OpenMandriva  | 67        | 6.01%   |
| Zorin         | 43        | 3.86%   |
| Pop!_OS       | 39        | 3.5%    |
| Endless       | 35        | 3.14%   |
| Arch          | 34        | 3.05%   |
| Manjaro       | 27        | 2.42%   |
| Xubuntu       | 26        | 2.33%   |
| Kubuntu       | 18        | 1.62%   |
| BlackPanther  | 17        | 1.53%   |
| Elementary    | 16        | 1.44%   |
| ArcoLinux     | 14        | 1.26%   |
| openSUSE      | 12        | 1.08%   |
| Lubuntu       | 12        | 1.08%   |
| KDE neon      | 12        | 1.08%   |
| Ubuntu Budgie | 10        | 0.9%    |
| ROSA          | 10        | 0.9%    |
| EndeavourOS   | 9         | 0.81%   |
| Ubuntu MATE   | 7         | 0.63%   |
| Nobara        | 7         | 0.63%   |
| LMDE          | 7         | 0.63%   |
| Xero          | 6         | 0.54%   |
| Peppermint    | 6         | 0.54%   |
| Kali          | 6         | 0.54%   |
| Huayra        | 5         | 0.45%   |
| Ubuntu Unity  | 4         | 0.36%   |
| Gentoo        | 4         | 0.36%   |
| Clear Linux   | 4         | 0.36%   |
| UbuntuDDE     | 3         | 0.27%   |
| SteamOS       | 3         | 0.27%   |
| Parrot        | 3         | 0.27%   |
| LinuxFX       | 3         | 0.27%   |
| CentOS        | 3         | 0.27%   |
| Void Linux    | 2         | 0.18%   |
| Rocky Linux   | 2         | 0.18%   |
| Garuda Linux  | 2         | 0.18%   |
| Artix         | 2         | 0.18%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 23        | 1.8%    |
| 5.4.0-42-generic         | 21        | 1.64%   |
| 5.16.7-desktop-1omv4003  | 20        | 1.56%   |
| 4.18.16-desktop-1bP      | 17        | 1.33%   |
| 5.4.0-26-generic         | 15        | 1.17%   |
| 6.2.6-desktop-1omv2390   | 12        | 0.94%   |
| 5.3.0-40-generic         | 12        | 0.94%   |
| 5.4.0-52-generic         | 11        | 0.86%   |
| 5.4.0-19-generic         | 10        | 0.78%   |
| 5.15.0-52-generic        | 10        | 0.78%   |
| 5.8.0-14-generic         | 9         | 0.7%    |
| 5.4.0-29-generic         | 9         | 0.7%    |
| 5.4.0-48-generic         | 8         | 0.63%   |
| 5.4.0-40-generic         | 8         | 0.63%   |
| 5.15.0-76-generic        | 8         | 0.63%   |
| 5.11.0-37-generic        | 8         | 0.63%   |
| 4.18.0-15-generic        | 8         | 0.63%   |
| 6.2.0-26-generic         | 7         | 0.55%   |
| 5.8.0-43-generic         | 7         | 0.55%   |
| 5.4.0-91-generic         | 7         | 0.55%   |
| 5.4.0-72-generic         | 7         | 0.55%   |
| 5.4.0-58-generic         | 7         | 0.55%   |
| 5.3.0-46-generic         | 7         | 0.55%   |
| 5.3.0-28-generic         | 7         | 0.55%   |
| 5.15.0-46-generic        | 7         | 0.55%   |
| 5.15.0-41-generic        | 7         | 0.55%   |
| 5.11.0-27-generic        | 7         | 0.55%   |
| 6.2.0-39-generic         | 6         | 0.47%   |
| 6.2.0-35-generic         | 6         | 0.47%   |
| 5.8.0-7630-generic       | 6         | 0.47%   |
| 5.4.0-73-generic         | 6         | 0.47%   |
| 5.4.0-47-generic         | 6         | 0.47%   |
| 5.4.0-45-generic         | 6         | 0.47%   |
| 5.4.0-37-generic         | 6         | 0.47%   |
| 5.3.0-42-generic         | 6         | 0.47%   |
| 5.15.0-48-generic        | 6         | 0.47%   |
| 5.13.0-40-generic        | 6         | 0.47%   |
| 5.13.0-35-generic        | 6         | 0.47%   |
| 5.10.0-21-amd64          | 6         | 0.47%   |
| 4.18.0-17-generic        | 6         | 0.47%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 194       | 16.02%  |
| 5.15.0  | 104       | 8.59%   |
| 4.15.0  | 63        | 5.2%    |
| 5.3.0   | 58        | 4.79%   |
| 5.8.0   | 55        | 4.54%   |
| 5.10.0  | 46        | 3.8%    |
| 5.11.0  | 41        | 3.39%   |
| 6.2.0   | 39        | 3.22%   |
| 5.19.0  | 35        | 2.89%   |
| 5.13.0  | 35        | 2.89%   |
| 5.0.0   | 31        | 2.56%   |
| 4.18.0  | 29        | 2.39%   |
| 5.10.14 | 23        | 1.9%    |
| 5.16.7  | 20        | 1.65%   |
| 4.19.0  | 20        | 1.65%   |
| 6.2.6   | 17        | 1.4%    |
| 4.18.16 | 17        | 1.4%    |
| 6.1.0   | 12        | 0.99%   |
| 6.5.0   | 9         | 0.74%   |
| 5.14.0  | 8         | 0.66%   |
| 6.4.11  | 6         | 0.5%    |
| 6.1.1   | 6         | 0.5%    |
| 5.17.5  | 6         | 0.5%    |
| 6.6.8   | 5         | 0.41%   |
| 5.18.16 | 5         | 0.41%   |
| 5.18.0  | 5         | 0.41%   |
| 5.15.5  | 5         | 0.41%   |
| 6.5.5   | 4         | 0.33%   |
| 5.9.10  | 4         | 0.33%   |
| 5.18.5  | 4         | 0.33%   |
| 5.15.8  | 4         | 0.33%   |
| 5.11.12 | 4         | 0.33%   |
| 4.9.20  | 4         | 0.33%   |
| 6.6.6   | 3         | 0.25%   |
| 6.6.1   | 3         | 0.25%   |
| 6.5.9   | 3         | 0.25%   |
| 6.4.9   | 3         | 0.25%   |
| 6.4.2   | 3         | 0.25%   |
| 6.4.12  | 3         | 0.25%   |
| 6.3.9   | 3         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 201       | 16.88%  |
| 5.15    | 131       | 11%     |
| 5.10    | 80        | 6.72%   |
| 6.2     | 68        | 5.71%   |
| 5.8     | 68        | 5.71%   |
| 4.15    | 63        | 5.29%   |
| 5.3     | 58        | 4.87%   |
| 5.11    | 54        | 4.53%   |
| 5.19    | 50        | 4.2%    |
| 4.18    | 48        | 4.03%   |
| 5.13    | 45        | 3.78%   |
| 6.1     | 33        | 2.77%   |
| 5.16    | 33        | 2.77%   |
| 5.0     | 33        | 2.77%   |
| 5.18    | 26        | 2.18%   |
| 4.19    | 22        | 1.85%   |
| 6.5     | 21        | 1.76%   |
| 6.4     | 20        | 1.68%   |
| 6.0     | 19        | 1.6%    |
| 5.14    | 18        | 1.51%   |
| 6.6     | 16        | 1.34%   |
| 6.3     | 13        | 1.09%   |
| 5.17    | 13        | 1.09%   |
| 5.9     | 12        | 1.01%   |
| 5.6     | 9         | 0.76%   |
| 4.9     | 8         | 0.67%   |
| 5.7     | 7         | 0.59%   |
| 5.12    | 6         | 0.5%    |
| 6.7     | 3         | 0.25%   |
| 5.5     | 3         | 0.25%   |
| 4.13    | 2         | 0.17%   |
| 4.1     | 2         | 0.17%   |
| 3.10    | 2         | 0.17%   |
| 4.4     | 1         | 0.08%   |
| 4.17    | 1         | 0.08%   |
| 4.10    | 1         | 0.08%   |
| 3.16    | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1034      | 95.21%  |
| i686   | 52        | 4.79%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 495       | 44.24%  |
| KDE5             | 174       | 15.55%  |
| Unknown          | 111       | 9.92%   |
| XFCE             | 101       | 9.03%   |
| X-Cinnamon       | 69        | 6.17%   |
| MATE             | 49        | 4.38%   |
| KDE              | 17        | 1.52%   |
| Pantheon         | 16        | 1.43%   |
| LXQt             | 15        | 1.34%   |
| LXDE             | 13        | 1.16%   |
| Budgie           | 12        | 1.07%   |
| Cinnamon         | 10        | 0.89%   |
| i3               | 7         | 0.63%   |
| KDE4             | 6         | 0.54%   |
| Deepin           | 5         | 0.45%   |
| Unity            | 4         | 0.36%   |
| xmonad           | 2         | 0.18%   |
| GNOME Flashback  | 2         | 0.18%   |
| bspwm            | 2         | 0.18%   |
| sway             | 1         | 0.09%   |
| qtile            | 1         | 0.09%   |
| openbox          | 1         | 0.09%   |
| lightdm-xsession | 1         | 0.09%   |
| i3-with-shmlog   | 1         | 0.09%   |
| Hyprland         | 1         | 0.09%   |
| Endless:GNOME    | 1         | 0.09%   |
| Cutefish         | 1         | 0.09%   |
| awesome          | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 826       | 74.28%  |
| Wayland | 207       | 18.62%  |
| Unknown | 71        | 6.38%   |
| Tty     | 8         | 0.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 565       | 50.63%  |
| SDDM    | 148       | 13.26%  |
| GDM3    | 131       | 11.74%  |
| GDM     | 117       | 10.48%  |
| LightDM | 109       | 9.77%   |
| TDM     | 32        | 2.87%   |
| KDM     | 6         | 0.54%   |
| LXDM    | 3         | 0.27%   |
| XDM     | 2         | 0.18%   |
| GREETD  | 2         | 0.18%   |
| SLiM    | 1         | 0.09%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| es_AR       | 571       | 51.21%  |
| en_US       | 278       | 24.93%  |
| Unknown     | 122       | 10.94%  |
| es_ES       | 67        | 6.01%   |
| es_MX       | 33        | 2.96%   |
| C           | 15        | 1.35%   |
| en_GB       | 9         | 0.81%   |
| pt_BR       | 5         | 0.45%   |
| es_US       | 3         | 0.27%   |
| POSIX       | 2         | 0.18%   |
| it_IT       | 2         | 0.18%   |
| es_CL       | 2         | 0.18%   |
| en_AG       | 2         | 0.18%   |
| fr_FR       | 1         | 0.09%   |
| es_UY       | 1         | 0.09%   |
| es_AR.UtF-8 | 1         | 0.09%   |
| en_CA       | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 555       | 50.09%  |
| BIOS | 553       | 49.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 847       | 76.38%  |
| Btrfs   | 99        | 8.93%   |
| Overlay | 88        | 7.94%   |
| Unknown | 31        | 2.8%    |
| Tmpfs   | 25        | 2.25%   |
| Xfs     | 9         | 0.81%   |
| Zfs     | 5         | 0.45%   |
| Ext2    | 3         | 0.27%   |
| Ext3    | 1         | 0.09%   |
| Aufs    | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 600       | 54.15%  |
| GPT     | 389       | 35.11%  |
| MBR     | 119       | 10.74%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 976       | 88.97%  |
| Yes       | 121       | 11.03%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 791       | 72.17%  |
| Yes       | 305       | 27.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 247       | 22.74%  |
| Hewlett-Packard         | 145       | 13.35%  |
| Dell                    | 137       | 12.62%  |
| ASUSTek Computer        | 129       | 11.88%  |
| Acer                    | 54        | 4.97%   |
| BANGHO                  | 43        | 3.96%   |
| Toshiba                 | 34        | 3.13%   |
| Exo                     | 32        | 2.95%   |
| Samsung Electronics     | 31        | 2.85%   |
| Positivo                | 26        | 2.39%   |
| Sony                    | 19        | 1.75%   |
| Apple                   | 15        | 1.38%   |
| Intel                   | 14        | 1.29%   |
| MSI                     | 13        | 1.2%    |
| Juana Manso             | 9         | 0.83%   |
| Compal                  | 9         | 0.83%   |
| Unknown                 | 9         | 0.83%   |
| Clevo                   | 8         | 0.74%   |
| Coradir                 | 7         | 0.64%   |
| Novatech                | 6         | 0.55%   |
| Standard                | 5         | 0.46%   |
| NSX                     | 5         | 0.46%   |
| NOBLEX                  | 5         | 0.46%   |
| HUAWEI                  | 5         | 0.46%   |
| Advantec                | 5         | 0.46%   |
| System76                | 4         | 0.37%   |
| PCBOX                   | 4         | 0.37%   |
| Gigabyte Technology     | 4         | 0.37%   |
| A-DATA Technology       | 4         | 0.37%   |
| Kelyx Argentina         | 3         | 0.28%   |
| iQual                   | 3         | 0.28%   |
| AIR                     | 3         | 0.28%   |
| Valve                   | 2         | 0.18%   |
| Radio Victoria Fueguina | 2         | 0.18%   |
| Quanta                  | 2         | 0.18%   |
| Packard Bell            | 2         | 0.18%   |
| NVN-ED01                | 2         | 0.18%   |
| LG Electronics          | 2         | 0.18%   |
| Garbarino SAIC          | 2         | 0.18%   |
| Compaq                  | 2         | 0.18%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 24        | 2.21%   |
| Lenovo V330-15IKB 81AX                     | 11        | 1.01%   |
| BANGHO MOV                                 | 10        | 0.92%   |
| Juana Manso SF20GM7                        | 9         | 0.83%   |
| HP Notebook                                | 9         | 0.83%   |
| HP Laptop 15-bs0xx                         | 8         | 0.74%   |
| Lenovo ThinkPad L15 Gen 2 20X4S27200       | 7         | 0.64%   |
| Lenovo G470 20078                          | 7         | 0.64%   |
| Coradir Coradir/ES10IS5                    | 7         | 0.64%   |
| BANGHO MAX G0101                           | 7         | 0.64%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA     | 7         | 0.64%   |
| HP Pavilion dv6                            | 6         | 0.55%   |
| Lenovo G550 2958                           | 5         | 0.46%   |
| Intel powered classmate PC                 | 5         | 0.46%   |
| Exo CloudbookE15                           | 5         | 0.46%   |
| Dell Latitude 3520                         | 5         | 0.46%   |
| Dell Inspiron 1525                         | 5         | 0.46%   |
| BANGHO W240HU/W250HUQ                      | 5         | 0.46%   |
| ASUS X541UAK                               | 5         | 0.46%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 5         | 0.46%   |
| ASUS K53E                                  | 5         | 0.46%   |
| Samsung 300E4C/300E5C/300E7C               | 4         | 0.37%   |
| Lenovo V310-15ISK 80SY                     | 4         | 0.37%   |
| Lenovo ThinkPad T430 2349DS5               | 4         | 0.37%   |
| Lenovo ThinkBook 15 G2 ITL 20VE            | 4         | 0.37%   |
| Lenovo IdeaPad 320-15ABR 80XS              | 4         | 0.37%   |
| HP Pavilion Notebook                       | 4         | 0.37%   |
| HP Pavilion dv7                            | 4         | 0.37%   |
| HP OMEN by Laptop 15-ce0xx                 | 4         | 0.37%   |
| HP G42                                     | 4         | 0.37%   |
| HP 250 G7 Notebook PC                      | 4         | 0.37%   |
| HP 250 G6 Notebook PC                      | 4         | 0.37%   |
| Dell Latitude 7490                         | 4         | 0.37%   |
| Dell Inspiron 3505                         | 4         | 0.37%   |
| Dell Inspiron 3421                         | 4         | 0.37%   |
| ASUS X555LAB                               | 4         | 0.37%   |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA     | 4         | 0.37%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 4         | 0.37%   |
| ASUS GL553VD                               | 4         | 0.37%   |
| Apple MacBookPro9,2                        | 4         | 0.37%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 91        | 8.38%   |
| Dell Inspiron       | 67        | 6.17%   |
| Lenovo IdeaPad      | 55        | 5.06%   |
| Dell Latitude       | 52        | 4.79%   |
| Acer Aspire         | 45        | 4.14%   |
| ASUS VivoBook       | 43        | 3.96%   |
| HP Pavilion         | 42        | 3.87%   |
| HP Laptop           | 25        | 2.3%    |
| Unknown             | 24        | 2.21%   |
| Toshiba Satellite   | 21        | 1.93%   |
| Exo Smart           | 16        | 1.47%   |
| Lenovo ThinkBook    | 15        | 1.38%   |
| BANGHO MAX          | 12        | 1.1%    |
| Lenovo V330-15IKB   | 11        | 1.01%   |
| HP 250              | 11        | 1.01%   |
| HP Compaq           | 10        | 0.92%   |
| BANGHO MOV          | 10        | 0.92%   |
| Juana Manso SF20GM7 | 9         | 0.83%   |
| HP Notebook         | 9         | 0.83%   |
| ASUS ZenBook        | 9         | 0.83%   |
| HP EliteBook        | 8         | 0.74%   |
| Lenovo G470         | 7         | 0.64%   |
| Coradir Coradir     | 7         | 0.64%   |
| Samsung R430        | 6         | 0.55%   |
| Samsung 300E4A      | 6         | 0.55%   |
| HP ProBook          | 6         | 0.55%   |
| ASUS ASUS           | 6         | 0.55%   |
| Lenovo Legion       | 5         | 0.46%   |
| Lenovo G550         | 5         | 0.46%   |
| Intel powered       | 5         | 0.46%   |
| HP OMEN             | 5         | 0.46%   |
| HP 240              | 5         | 0.46%   |
| Exo CloudbookE15    | 5         | 0.46%   |
| Dell XPS            | 5         | 0.46%   |
| BANGHO W240HU       | 5         | 0.46%   |
| ASUS X541UAK        | 5         | 0.46%   |
| ASUS K53E           | 5         | 0.46%   |
| Samsung 300E4C      | 4         | 0.37%   |
| Lenovo Yoga         | 4         | 0.37%   |
| Lenovo V310-15ISK   | 4         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 119       | 10.96%  |
| 2017    | 107       | 9.85%   |
| 2012    | 95        | 8.75%   |
| 2019    | 91        | 8.38%   |
| 2020    | 83        | 7.64%   |
| 2011    | 81        | 7.46%   |
| 2010    | 68        | 6.26%   |
| 2014    | 64        | 5.89%   |
| 2018    | 62        | 5.71%   |
| 2013    | 62        | 5.71%   |
| 2016    | 57        | 5.25%   |
| 2015    | 53        | 4.88%   |
| 2008    | 46        | 4.24%   |
| 2009    | 33        | 3.04%   |
| 2022    | 20        | 1.84%   |
| 2007    | 17        | 1.57%   |
| 2006    | 10        | 0.92%   |
| 2023    | 9         | 0.83%   |
| Unknown | 7         | 0.64%   |
| 2005    | 1         | 0.09%   |
| 2004    | 1         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1086      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 993       | 90.68%  |
| Enabled  | 102       | 9.32%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1084      | 99.82%  |
| Yes  | 2         | 0.18%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 313       | 28.51%  |
| 3.01-4.0    | 288       | 26.23%  |
| 8.01-16.0   | 183       | 16.67%  |
| 16.01-24.0  | 117       | 10.66%  |
| 1.01-2.0    | 96        | 8.74%   |
| 32.01-64.0  | 45        | 4.1%    |
| 2.01-3.0    | 24        | 2.19%   |
| 0.51-1.0    | 17        | 1.55%   |
| 24.01-32.0  | 11        | 1%      |
| 64.01-256.0 | 4         | 0.36%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 420       | 35.18%  |
| 2.01-3.0   | 298       | 24.96%  |
| 4.01-8.0   | 155       | 12.98%  |
| 3.01-4.0   | 153       | 12.81%  |
| 0.51-1.0   | 97        | 8.12%   |
| 8.01-16.0  | 54        | 4.52%   |
| 0.01-0.5   | 12        | 1.01%   |
| 16.01-24.0 | 4         | 0.34%   |
| 24.01-32.0 | 1         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 825       | 75.07%  |
| 2      | 245       | 22.29%  |
| 3      | 19        | 1.73%   |
| 0      | 8         | 0.73%   |
| 4      | 2         | 0.18%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 713       | 65.17%  |
| Yes       | 381       | 34.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 894       | 82.17%  |
| No        | 194       | 17.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1062      | 97.7%   |
| No        | 25        | 2.3%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 761       | 69.75%  |
| No        | 330       | 30.25%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Argentina | 1086      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Buenos Aires                | 244       | 21.5%   |
| Córdoba                    | 83        | 7.31%   |
| Rosario                     | 41        | 3.61%   |
| La Plata                    | 33        | 2.91%   |
| Mar del Plata               | 27        | 2.38%   |
| Mendoza                     | 18        | 1.59%   |
| Corrientes                  | 17        | 1.5%    |
| San Miguel de Tucumán      | 15        | 1.32%   |
| Avellaneda                  | 14        | 1.23%   |
| Lanus                       | 13        | 1.15%   |
| Quilmes                     | 11        | 0.97%   |
| Ituzaingo                   | 11        | 0.97%   |
| Bariloche                   | 11        | 0.97%   |
| Villa Ballester             | 10        | 0.88%   |
| Santa Fe                    | 10        | 0.88%   |
| Salta                       | 10        | 0.88%   |
| Resistencia                 | 10        | 0.88%   |
| Posadas                     | 10        | 0.88%   |
| Olivos                      | 10        | 0.88%   |
| San Martín de los Andes    | 9         | 0.79%   |
| Paraná                     | 9         | 0.79%   |
| Tandil                      | 8         | 0.7%    |
| Ramos Mejia                 | 8         | 0.7%    |
| Bahía Blanca               | 8         | 0.7%    |
| San Juan                    | 7         | 0.62%   |
| San Francisco               | 7         | 0.62%   |
| Lomas de Zamora             | 7         | 0.62%   |
| Florencio Varela            | 7         | 0.62%   |
| Burzaco                     | 7         | 0.62%   |
| Vicente Lopez               | 6         | 0.53%   |
| Tigre                       | 6         | 0.53%   |
| Santiago del Estero         | 6         | 0.53%   |
| San Nicolás de los Arroyos | 6         | 0.53%   |
| San Isidro                  | 6         | 0.53%   |
| Rio Tercero                 | 6         | 0.53%   |
| Río Gallegos               | 6         | 0.53%   |
| Isidro Casanova             | 6         | 0.53%   |
| Godoy Cruz                  | 6         | 0.53%   |
| Villa Carlos Paz            | 5         | 0.44%   |
| Viedma                      | 5         | 0.44%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 233       | 291    | 17.96%  |
| Kingston                    | 176       | 213    | 13.57%  |
| Seagate                     | 173       | 202    | 13.34%  |
| Toshiba                     | 140       | 177    | 10.79%  |
| Samsung Electronics         | 117       | 151    | 9.02%   |
| Unknown                     | 59        | 74     | 4.55%   |
| HGST                        | 45        | 48     | 3.47%   |
| SanDisk                     | 43        | 67     | 3.32%   |
| SK hynix                    | 42        | 50     | 3.24%   |
| Hitachi                     | 37        | 42     | 2.85%   |
| Micron Technology           | 21        | 26     | 1.62%   |
| Crucial                     | 20        | 29     | 1.54%   |
| Intel                       | 19        | 35     | 1.46%   |
| A-DATA Technology           | 16        | 17     | 1.23%   |
| Gigabyte Technology         | 14        | 22     | 1.08%   |
| KIOXIA                      | 10        | 10     | 0.77%   |
| Unknown                     | 9         | 9      | 0.69%   |
| Hewlett-Packard             | 8         | 10     | 0.62%   |
| China                       | 8         | 9      | 0.62%   |
| PNY                         | 7         | 11     | 0.54%   |
| Patriot                     | 6         | 7      | 0.46%   |
| Lexar                       | 6         | 6      | 0.46%   |
| Kingston Technology Company | 5         | 5      | 0.39%   |
| Kimtigo                     | 5         | 5      | 0.39%   |
| XPG                         | 4         | 5      | 0.31%   |
| Wodposit                    | 4         | 4      | 0.31%   |
| Neo                         | 4         | 4      | 0.31%   |
| HS-SSD-C100                 | 4         | 7      | 0.31%   |
| Apple                       | 4         | 5      | 0.31%   |
| ADATA Technology            | 4         | 4      | 0.31%   |
| Union Memory                | 3         | 3      | 0.23%   |
| Phison Electronics          | 3         | 3      | 0.23%   |
| Union Memory (Shenzhen)     | 2         | 2      | 0.15%   |
| SPCC                        | 2         | 2      | 0.15%   |
| Silicon Motion              | 2         | 2      | 0.15%   |
| Realtek Semiconductor       | 2         | 2      | 0.15%   |
| MAXIO Technology (Hangzhou) | 2         | 2      | 0.15%   |
| LITEONIT                    | 2         | 2      | 0.15%   |
| LITEON                      | 2         | 2      | 0.15%   |
| GLOWAY                      | 2         | 3      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 61        | 4.58%   |
| Seagate ST1000LM035-1RK172 1TB      | 43        | 3.23%   |
| Kingston SA400S37480G 480GB SSD     | 30        | 2.25%   |
| Toshiba MQ01ABF050 500GB            | 28        | 2.1%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 27        | 2.03%   |
| Toshiba MQ01ABD100 1TB              | 25        | 1.88%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 18        | 1.35%   |
| Unknown MMC Card  32GB              | 18        | 1.35%   |
| Toshiba MQ04ABF100 1TB              | 15        | 1.13%   |
| HGST HTS721010A9E630 1TB            | 12        | 0.9%    |
| Seagate ST500LT012-1DG142 500GB     | 11        | 0.83%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 10        | 0.75%   |
| WDC WD10JPVX-60JC3T1 1TB            | 9         | 0.68%   |
| Seagate ST9500325AS 500GB           | 9         | 0.68%   |
| Kingston SA400S37960G 960GB SSD     | 9         | 0.68%   |
| Unknown                             | 9         | 0.68%   |
| Seagate ST500LM030-2E717D 500GB     | 8         | 0.6%    |
| Kingston SNVS500G 500GB             | 8         | 0.6%    |
| Kingston SA400S37120G 120GB SSD     | 8         | 0.6%    |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 7         | 0.53%   |
| Unknown MMC Card  64GB              | 7         | 0.53%   |
| Toshiba MQ01ABD032 320GB            | 7         | 0.53%   |
| Toshiba MK6475GSX 640GB             | 7         | 0.53%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 7         | 0.53%   |
| Seagate ST1000LM048-2E7172 1TB      | 7         | 0.53%   |
| Samsung MZALQ256HBJD-00BL1 256GB    | 7         | 0.53%   |
| Kingston SV300S37A240G 240GB SSD    | 7         | 0.53%   |
| HGST HTS725050A7E630 500GB          | 7         | 0.53%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 6         | 0.45%   |
| WDC WD5000LPCX-22VHAT0 500GB        | 6         | 0.45%   |
| Samsung NVMe SSD Drive 512GB        | 6         | 0.45%   |
| Kingston SUV400S37240G 240GB SSD    | 6         | 0.45%   |
| HGST HTS545050A7E380 500GB          | 6         | 0.45%   |
| Crucial CT240BX500SSD1 240GB        | 6         | 0.45%   |
| A-DATA SU630 240GB SSD              | 6         | 0.45%   |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 5         | 0.38%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 5         | 0.38%   |
| Seagate ST500LT012-9WS142 500GB     | 5         | 0.38%   |
| Samsung HM250HI 250GB               | 5         | 0.38%   |
| Lexar 240GB SSD                     | 5         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 169       | 196    | 30.07%  |
| WDC                 | 158       | 187    | 28.11%  |
| Toshiba             | 121       | 154    | 21.53%  |
| HGST                | 45        | 48     | 8.01%   |
| Hitachi             | 37        | 42     | 6.58%   |
| Samsung Electronics | 25        | 28     | 4.45%   |
| Unknown             | 4         | 4      | 0.71%   |
| JMicron Technology  | 1         | 1      | 0.18%   |
| Inateck             | 1         | 1      | 0.18%   |
| Fujitsu             | 1         | 1      | 0.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 151       | 185    | 38.04%  |
| WDC                 | 55        | 68     | 13.85%  |
| Samsung Electronics | 25        | 40     | 6.3%    |
| SanDisk             | 20        | 26     | 5.04%   |
| Crucial             | 19        | 28     | 4.79%   |
| Gigabyte Technology | 13        | 21     | 3.27%   |
| A-DATA Technology   | 13        | 13     | 3.27%   |
| SK hynix            | 8         | 9      | 2.02%   |
| Toshiba             | 7         | 7      | 1.76%   |
| PNY                 | 7         | 11     | 1.76%   |
| Micron Technology   | 7         | 9      | 1.76%   |
| Lexar               | 6         | 6      | 1.51%   |
| Intel               | 6         | 6      | 1.51%   |
| Patriot             | 5         | 6      | 1.26%   |
| Kimtigo             | 5         | 5      | 1.26%   |
| Hewlett-Packard     | 5         | 8      | 1.26%   |
| China               | 5         | 6      | 1.26%   |
| Wodposit            | 4         | 4      | 1.01%   |
| Seagate             | 3         | 5      | 0.76%   |
| SPCC                | 2         | 2      | 0.5%    |
| LITEONIT            | 2         | 2      | 0.5%    |
| HS-SSD-C100         | 2         | 5      | 0.5%    |
| GLOWAY              | 2         | 3      | 0.5%    |
| FORESEE             | 2         | 2      | 0.5%    |
| Corsair             | 2         | 2      | 0.5%    |
| Colorful            | 2         | 2      | 0.5%    |
| Apple               | 2         | 2      | 0.5%    |
| Unknown             | 2         | 2      | 0.5%    |
| XrayDisk            | 1         | 1      | 0.25%   |
| WDC WDS2            | 1         | 1      | 0.25%   |
| USB3.0              | 1         | 1      | 0.25%   |
| Transcend           | 1         | 1      | 0.25%   |
| Team                | 1         | 1      | 0.25%   |
| Super Talent        | 1         | 1      | 0.25%   |
| SMI                 | 1         | 1      | 0.25%   |
| Ramaxel Technology  | 1         | 1      | 0.25%   |
| OCZ                 | 1         | 1      | 0.25%   |
| NGFF                | 1         | 2      | 0.25%   |
| Netac               | 1         | 2      | 0.25%   |
| Neo                 | 1         | 1      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 551       | 662    | 44.15%  |
| SSD     | 376       | 502    | 30.13%  |
| NVMe    | 247       | 351    | 19.79%  |
| MMC     | 58        | 74     | 4.65%   |
| Unknown | 16        | 15     | 1.28%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 841       | 1163   | 72.38%  |
| NVMe | 247       | 350    | 21.26%  |
| MMC  | 58        | 74     | 4.99%   |
| SAS  | 16        | 17     | 1.38%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 620       | 805    | 68.97%  |
| 0.51-1.0   | 269       | 348    | 29.92%  |
| 1.01-2.0   | 9         | 10     | 1%      |
| 3.01-4.0   | 1         | 1      | 0.11%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 357       | 31.51%  |
| 251-500        | 292       | 25.77%  |
| 501-1000       | 176       | 15.53%  |
| 1-20           | 73        | 6.44%   |
| 51-100         | 71        | 6.27%   |
| 1001-2000      | 61        | 5.38%   |
| 21-50          | 52        | 4.59%   |
| Unknown        | 31        | 2.74%   |
| More than 3000 | 12        | 1.06%   |
| 2001-3000      | 8         | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 469       | 39.78%  |
| 21-50     | 233       | 19.76%  |
| 101-250   | 176       | 14.93%  |
| 51-100    | 143       | 12.13%  |
| 251-500   | 75        | 6.36%   |
| 501-1000  | 39        | 3.31%   |
| Unknown   | 31        | 2.63%   |
| 1001-2000 | 11        | 0.93%   |
| 2001-3000 | 2         | 0.17%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 6         | 6      | 6.82%   |
| WDC WD5000BPVT-22HXZT3 500GB        | 3         | 3      | 3.41%   |
| Toshiba MQ01ABF050 500GB            | 3         | 3      | 3.41%   |
| Toshiba MQ01ABD100 1TB              | 3         | 6      | 3.41%   |
| HGST HTS721010A9E630 1TB            | 3         | 5      | 3.41%   |
| HGST HTS541010A9E680 1TB            | 3         | 3      | 3.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2         | 2      | 2.27%   |
| Toshiba MQ01ABD050 500GB            | 2         | 2      | 2.27%   |
| Toshiba MK7559GSXP 752GB            | 2         | 2      | 2.27%   |
| Toshiba MK6475GSX 640GB             | 2         | 2      | 2.27%   |
| Toshiba MK1665GSX 160GB             | 2         | 2      | 2.27%   |
| Seagate ST9500325AS 500GB           | 2         | 2      | 2.27%   |
| Seagate ST9320325AS 320GB           | 2         | 2      | 2.27%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 5      | 2.27%   |
| Samsung Electronics HN-M101MBB 1TB  | 2         | 2      | 2.27%   |
| Kingston SA400S37240G 240GB SSD     | 2         | 2      | 2.27%   |
| HGST HTS725050A7E630 500GB          | 2         | 2      | 2.27%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 1         | 1      | 1.14%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1         | 1      | 1.14%   |
| WDC WD5000LPCX-22VHAT0 500GB        | 1         | 1      | 1.14%   |
| WDC WD5000BEVT-22A0RT0 500GB        | 1         | 1      | 1.14%   |
| WDC WD3200BPVT-00JJ5T0 320GB        | 1         | 1      | 1.14%   |
| WDC WD3200BEKT-60F3T1 320GB         | 1         | 1      | 1.14%   |
| WDC WD2500BEVT-75A23T0 250GB        | 1         | 1      | 1.14%   |
| WDC WD2500BEKT-75PVMT0 250GB        | 1         | 2      | 1.14%   |
| WDC WD1200BEVS-60UST0 120GB         | 1         | 1      | 1.14%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 1      | 1.14%   |
| WDC WD Green 2.5 240GB SSD          | 1         | 1      | 1.14%   |
| Toshiba MQ04ABF100 1TB              | 1         | 1      | 1.14%   |
| Toshiba MQ01ABD032 320GB            | 1         | 1      | 1.14%   |
| Toshiba MK3265GSXN 320GB            | 1         | 1      | 1.14%   |
| Toshiba MK2576GSX 250GB             | 1         | 1      | 1.14%   |
| Toshiba MK2556GSY 250GB             | 1         | 1      | 1.14%   |
| SMI SSD DISK 512GB                  | 1         | 1      | 1.14%   |
| Seagate ST960813AS 64GB             | 1         | 1      | 1.14%   |
| Seagate ST960812A 64GB              | 1         | 1      | 1.14%   |
| Seagate ST9160314AS 160GB           | 1         | 1      | 1.14%   |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 1.14%   |
| Seagate ST320LT020-9YG142 320GB     | 1         | 1      | 1.14%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1      | 1.14%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 24     | 23.86%  |
| Toshiba             | 19        | 22     | 21.59%  |
| WDC                 | 16        | 17     | 18.18%  |
| HGST                | 10        | 12     | 11.36%  |
| Samsung Electronics | 7         | 7      | 7.95%   |
| Hitachi             | 7         | 9      | 7.95%   |
| Kingston            | 5         | 5      | 5.68%   |
| SMI                 | 1         | 1      | 1.14%   |
| LITEONIT            | 1         | 1      | 1.14%   |
| A-DATA Technology   | 1         | 1      | 1.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 24     | 29.17%  |
| Toshiba             | 19        | 22     | 26.39%  |
| WDC                 | 11        | 12     | 15.28%  |
| HGST                | 10        | 12     | 13.89%  |
| Hitachi             | 7         | 9      | 9.72%   |
| Samsung Electronics | 4         | 4      | 5.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 71        | 83     | 81.61%  |
| SSD  | 15        | 15     | 17.24%  |
| NVMe | 1         | 1      | 1.15%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                       | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB | 2         | 2      | 50%     |
| Toshiba MK6475GSX 640GB     | 1         | 1      | 25%     |
| Toshiba MK1665GSX 160GB     | 1         | 1      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 2         | 2      | 50%     |
| Toshiba | 2         | 2      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 650       | 914    | 57.02%  |
| Works    | 401       | 587    | 35.18%  |
| Malfunc  | 85        | 99     | 7.46%   |
| Failed   | 4         | 4      | 0.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 808       | 67.79%  |
| AMD                              | 114       | 9.56%   |
| Samsung Electronics              | 68        | 5.7%    |
| SanDisk                          | 43        | 3.61%   |
| SK hynix                         | 34        | 2.85%   |
| Kingston Technology Company      | 30        | 2.52%   |
| Toshiba America Info Systems     | 13        | 1.09%   |
| Micron Technology                | 13        | 1.09%   |
| Silicon Integrated Systems [SiS] | 12        | 1.01%   |
| KIOXIA                           | 12        | 1.01%   |
| ADATA Technology                 | 6         | 0.5%    |
| Union Memory (Shenzhen)          | 5         | 0.42%   |
| Realtek Semiconductor            | 5         | 0.42%   |
| Phison Electronics               | 5         | 0.42%   |
| Silicon Motion                   | 4         | 0.34%   |
| Nvidia                           | 4         | 0.34%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.25%   |
| VIA Technologies                 | 2         | 0.17%   |
| Micron/Crucial Technology        | 2         | 0.17%   |
| Apple                            | 2         | 0.17%   |
| Solid State Storage Technology   | 1         | 0.08%   |
| O2 Micro                         | 1         | 0.08%   |
| Nextorage                        | 1         | 0.08%   |
| Marvell Technology Group         | 1         | 0.08%   |
| Lite-On Technology               | 1         | 0.08%   |
| INNOGRIT                         | 1         | 0.08%   |
| Biwin Storage Technology         | 1         | 0.08%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 122       | 9.52%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 96        | 7.49%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 91        | 7.1%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 61        | 4.76%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 59        | 4.6%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 40        | 3.12%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 35        | 2.73%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 33        | 2.57%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 31        | 2.42%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 31        | 2.42%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 31        | 2.42%   |
| Intel Tiger Lake-LP SATA Controller                                              | 29        | 2.26%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 29        | 2.26%   |
| Intel Comet Lake SATA AHCI Controller                                            | 26        | 2.03%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 24        | 1.87%   |
| Intel Volume Management Device NVMe RAID Controller                              | 23        | 1.79%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 20        | 1.56%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 20        | 1.56%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 20        | 1.56%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 17        | 1.33%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 17        | 1.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 16        | 1.25%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 14        | 1.09%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 14        | 1.09%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 12        | 0.94%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 12        | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 12        | 0.94%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 11        | 0.86%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 10        | 0.78%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 10        | 0.78%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 10        | 0.78%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 10        | 0.78%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 10        | 0.78%   |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                               | 9         | 0.7%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 9         | 0.7%    |
| SK hynix BC511 NVMe SSD                                                          | 8         | 0.62%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 8         | 0.62%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 8         | 0.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 8         | 0.62%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 8         | 0.62%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 805       | 65.66%  |
| NVMe | 248       | 20.23%  |
| IDE  | 88        | 7.18%   |
| RAID | 85        | 6.93%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 922       | 84.9%   |
| AMD    | 164       | 15.1%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 29        | 2.67%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 25        | 2.3%    |
| Intel Celeron N4020 CPU @ 1.10GHz             | 22        | 2.02%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 19        | 1.75%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 17        | 1.56%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 16        | 1.47%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 16        | 1.47%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 16        | 1.47%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 16        | 1.47%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 16        | 1.47%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 15        | 1.38%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 15        | 1.38%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 15        | 1.38%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 15        | 1.38%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 1.29%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 13        | 1.2%    |
| Intel Celeron CPU N3350 @ 1.10GHz             | 13        | 1.2%    |
| Intel Core i7-10510U CPU @ 1.80GHz            | 12        | 1.1%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 12        | 1.1%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 11        | 1.01%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 11        | 1.01%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 11        | 1.01%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 10        | 0.92%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 10        | 0.92%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 10        | 0.92%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 9         | 0.83%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 9         | 0.83%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 9         | 0.83%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 9         | 0.83%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 9         | 0.83%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 9         | 0.83%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 9         | 0.83%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 8         | 0.74%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 0.74%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 8         | 0.74%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 8         | 0.74%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 8         | 0.74%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 7         | 0.64%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 7         | 0.64%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 7         | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 244       | 22.45%  |
| Intel Core i7           | 180       | 16.56%  |
| Intel Core i3           | 136       | 12.51%  |
| Intel Celeron           | 105       | 9.66%   |
| Other                   | 90        | 8.28%   |
| Intel Atom              | 56        | 5.15%   |
| AMD Ryzen 5             | 41        | 3.77%   |
| Intel Pentium           | 36        | 3.31%   |
| AMD Ryzen 7             | 31        | 2.85%   |
| Intel Core 2 Duo        | 29        | 2.67%   |
| Intel Pentium Dual-Core | 24        | 2.21%   |
| Intel Pentium Dual      | 14        | 1.29%   |
| AMD A6                  | 13        | 1.2%    |
| Intel Genuine           | 9         | 0.83%   |
| AMD A8                  | 7         | 0.64%   |
| AMD A10                 | 7         | 0.64%   |
| AMD Ryzen 3             | 6         | 0.55%   |
| AMD A4                  | 6         | 0.55%   |
| AMD A12                 | 6         | 0.55%   |
| Intel Core 2            | 5         | 0.46%   |
| AMD Athlon II           | 5         | 0.46%   |
| AMD Ryzen 9             | 4         | 0.37%   |
| AMD Ryzen 7 PRO         | 3         | 0.28%   |
| AMD E                   | 3         | 0.28%   |
| AMD Athlon              | 3         | 0.28%   |
| Intel Pentium M         | 2         | 0.18%   |
| Intel Celeron M         | 2         | 0.18%   |
| AMD Turion II           | 2         | 0.18%   |
| AMD Turion 64 X2 Mobile | 2         | 0.18%   |
| AMD C-70                | 2         | 0.18%   |
| AMD C-60                | 2         | 0.18%   |
| AMD Athlon X2           | 2         | 0.18%   |
| Intel Core Duo          | 1         | 0.09%   |
| Intel Celeron Dual-Core | 1         | 0.09%   |
| AMD Z                   | 1         | 0.09%   |
| AMD V120                | 1         | 0.09%   |
| AMD Turion 64 Mobile    | 1         | 0.09%   |
| AMD Phenom II           | 1         | 0.09%   |
| AMD E2                  | 1         | 0.09%   |
| AMD E1                  | 1         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 657       | 60.44%  |
| 4       | 309       | 28.43%  |
| 1       | 42        | 3.86%   |
| 8       | 38        | 3.5%    |
| 6       | 28        | 2.58%   |
| 10      | 4         | 0.37%   |
| 12      | 3         | 0.28%   |
| 14      | 2         | 0.18%   |
| Unknown | 2         | 0.18%   |
| 16      | 1         | 0.09%   |
| 3       | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 1085      | 99.91%  |
| Unknown | 1         | 0.09%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 760       | 69.92%  |
| 1       | 325       | 29.9%   |
| Unknown | 2         | 0.18%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1055      | 96.88%  |
| 32-bit         | 15        | 1.38%   |
| Unknown        | 15        | 1.38%   |
| 64-bit         | 4         | 0.37%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 298       | 26.51%  |
| 0x206a7    | 73        | 6.49%   |
| 0x306a9    | 67        | 5.96%   |
| 0x806ec    | 43        | 3.83%   |
| 0x806e9    | 42        | 3.74%   |
| 0x806c1    | 37        | 3.29%   |
| 0x406e3    | 34        | 3.02%   |
| 0x1067a    | 32        | 2.85%   |
| 0x806ea    | 29        | 2.58%   |
| 0x306d4    | 29        | 2.58%   |
| 0x40651    | 27        | 2.4%    |
| 0x20655    | 24        | 2.14%   |
| 0x6fd      | 23        | 2.05%   |
| 0x406c4    | 23        | 2.05%   |
| 0x706e5    | 20        | 1.78%   |
| 0x30678    | 18        | 1.6%    |
| 0x306c3    | 17        | 1.51%   |
| 0x706a1    | 16        | 1.42%   |
| 0x30661    | 15        | 1.33%   |
| 0x106ca    | 15        | 1.33%   |
| 0x706a8    | 14        | 1.25%   |
| 0x08108109 | 13        | 1.16%   |
| 0x06006705 | 13        | 1.16%   |
| 0x506c9    | 12        | 1.07%   |
| 0x08608103 | 10        | 0.89%   |
| 0x20652    | 9         | 0.8%    |
| 0x0a50000c | 9         | 0.8%    |
| 0x906e9    | 8         | 0.71%   |
| 0x08108102 | 8         | 0.71%   |
| 0xa0652    | 7         | 0.62%   |
| 0x906ea    | 6         | 0.53%   |
| 0x6e8      | 6         | 0.53%   |
| 0x10661    | 6         | 0.53%   |
| 0x08600104 | 6         | 0.53%   |
| 0x0810100b | 6         | 0.53%   |
| 0x06006118 | 6         | 0.53%   |
| 0x06001119 | 6         | 0.53%   |
| 0x806eb    | 5         | 0.44%   |
| 0x406c3    | 5         | 0.44%   |
| 0x08600106 | 5         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 184       | 16.93%  |
| SandyBridge      | 93        | 8.56%   |
| IvyBridge        | 81        | 7.45%   |
| Silvermont       | 61        | 5.61%   |
| TigerLake        | 60        | 5.52%   |
| Haswell          | 58        | 5.34%   |
| Skylake          | 56        | 5.15%   |
| Westmere         | 45        | 4.14%   |
| Penryn           | 44        | 4.05%   |
| Goldmont plus    | 43        | 3.96%   |
| Core             | 38        | 3.5%    |
| IceLake          | 36        | 3.31%   |
| Broadwell        | 35        | 3.22%   |
| Bonnell          | 35        | 3.22%   |
| Unknown          | 27        | 2.48%   |
| Zen+             | 26        | 2.39%   |
| Excavator        | 26        | 2.39%   |
| Zen 2            | 16        | 1.47%   |
| Zen 3            | 14        | 1.29%   |
| Goldmont         | 14        | 1.29%   |
| Zen              | 12        | 1.1%    |
| P6               | 11        | 1.01%   |
| Bobcat           | 10        | 0.92%   |
| K10              | 9         | 0.83%   |
| CometLake        | 9         | 0.83%   |
| Piledriver       | 8         | 0.74%   |
| Alderlake Hybrid | 7         | 0.64%   |
| K10 Llano        | 6         | 0.55%   |
| Nehalem          | 5         | 0.46%   |
| K8 Hammer        | 5         | 0.46%   |
| Puma             | 4         | 0.37%   |
| Steamroller      | 3         | 0.28%   |
| K8 & K10 hybrid  | 3         | 0.28%   |
| Jaguar           | 2         | 0.18%   |
| Gracemont        | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 882       | 71.19%  |
| AMD                              | 202       | 16.3%   |
| Nvidia                           | 141       | 11.38%  |
| Silicon Integrated Systems [SiS] | 12        | 0.97%   |
| VIA Technologies                 | 2         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 92        | 7.16%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 78        | 6.07%   |
| Intel HD Graphics 620                                                                    | 57        | 4.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 54        | 4.2%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 46        | 3.58%   |
| Intel Core Processor Integrated Graphics Controller                                      | 44        | 3.42%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 43        | 3.35%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 39        | 3.04%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 38        | 2.96%   |
| Intel UHD Graphics 620                                                                   | 37        | 2.88%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 35        | 2.72%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 34        | 2.65%   |
| Intel HD Graphics 5500                                                                   | 32        | 2.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 28        | 2.18%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 26        | 2.02%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 26        | 2.02%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 24        | 1.87%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 20        | 1.56%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 18        | 1.4%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 18        | 1.4%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 18        | 1.4%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 17        | 1.32%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 15        | 1.17%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 15        | 1.17%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 15        | 1.17%   |
| AMD Lucienne                                                                             | 15        | 1.17%   |
| Intel HD Graphics 500                                                                    | 14        | 1.09%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 13        | 1.01%   |
| Intel HD Graphics 630                                                                    | 13        | 1.01%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 12        | 0.93%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 12        | 0.93%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 11        | 0.86%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 11        | 0.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 11        | 0.86%   |
| Nvidia GP108M [GeForce MX150]                                                            | 8         | 0.62%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 8         | 0.62%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 8         | 0.62%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 0.62%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 8         | 0.62%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 8         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 743       | 68.35%  |
| 1 x AMD        | 140       | 12.88%  |
| Intel + Nvidia | 104       | 9.57%   |
| Intel + AMD    | 33        | 3.04%   |
| 1 x Nvidia     | 22        | 2.02%   |
| AMD + Nvidia   | 16        | 1.47%   |
| 2 x AMD        | 13        | 1.2%    |
| 1 x SiS        | 12        | 1.1%    |
| 2 x Intel      | 2         | 0.18%   |
| 1 x VIA        | 2         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 991       | 90.75%  |
| Proprietary | 64        | 5.86%   |
| Unknown     | 37        | 3.39%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 817       | 73.74%  |
| 0.01-0.5   | 104       | 9.39%   |
| 1.01-2.0   | 99        | 8.94%   |
| 3.01-4.0   | 37        | 3.34%   |
| 0.51-1.0   | 34        | 3.07%   |
| 5.01-6.0   | 11        | 0.99%   |
| 2.01-3.0   | 3         | 0.27%   |
| 8.01-16.0  | 3         | 0.27%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| Chimei Innolux          | 196       | 16.08%  |
| AU Optronics            | 193       | 15.83%  |
| Samsung Electronics     | 191       | 15.67%  |
| BOE                     | 175       | 14.36%  |
| LG Display              | 142       | 11.65%  |
| Goldstar                | 43        | 3.53%   |
| InfoVision              | 38        | 3.12%   |
| Chi Mei Optoelectronics | 23        | 1.89%   |
| PANDA                   | 18        | 1.48%   |
| Apple                   | 16        | 1.31%   |
| Lenovo                  | 15        | 1.23%   |
| Philips                 | 13        | 1.07%   |
| LG Philips              | 12        | 0.98%   |
| STA                     | 11        | 0.9%    |
| InnoLux Display         | 11        | 0.9%    |
| BenQ                    | 11        | 0.9%    |
| Dell                    | 10        | 0.82%   |
| Sharp                   | 9         | 0.74%   |
| ViewSonic               | 8         | 0.66%   |
| HannStar                | 8         | 0.66%   |
| CPT                     | 7         | 0.57%   |
| Hitachi                 | 6         | 0.49%   |
| SKY                     | 5         | 0.41%   |
| KDC                     | 5         | 0.41%   |
| Hewlett-Packard         | 5         | 0.41%   |
| Pixio                   | 3         | 0.25%   |
| ASUSTek Computer        | 3         | 0.25%   |
| ZTR                     | 2         | 0.16%   |
| Valve                   | 2         | 0.16%   |
| Unknown                 | 2         | 0.16%   |
| MTD                     | 2         | 0.16%   |
| KIG                     | 2         | 0.16%   |
| KDB                     | 2         | 0.16%   |
| iQual                   | 2         | 0.16%   |
| HKC                     | 2         | 0.16%   |
| Gigabyte Technology     | 2         | 0.16%   |
| GDH                     | 2         | 0.16%   |
| Daewoo                  | 2         | 0.16%   |
| CSO                     | 2         | 0.16%   |
| AOC                     | 2         | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 25        | 2.02%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 23        | 1.85%   |
| InfoVision LCD Monitor IVO03F4 1366x768 344x193mm 15.5-inch          | 20        | 1.61%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 14        | 1.13%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 12        | 0.97%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 11        | 0.89%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 11        | 0.89%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 10        | 0.81%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 9         | 0.73%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 9         | 0.73%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 9         | 0.73%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 8         | 0.65%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 8         | 0.65%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 8         | 0.65%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 8         | 0.65%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 7         | 0.56%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 7         | 0.56%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 7         | 0.56%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 7         | 0.56%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch | 6         | 0.48%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 6         | 0.48%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 6         | 0.48%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 6         | 0.48%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 6         | 0.48%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 6         | 0.48%   |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch              | 5         | 0.4%    |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch        | 5         | 0.4%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 5         | 0.4%    |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 5         | 0.4%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 5         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch     | 5         | 0.4%    |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 5         | 0.4%    |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 5         | 0.4%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 340x190mm 15.3-inch        | 5         | 0.4%    |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch        | 5         | 0.4%    |
| STA XR140EA1T STA0450 1366x768 310x174mm 14.0-inch                   | 4         | 0.32%   |
| STA LCD Monitor STA8CA7 1366x768 256x144mm 11.6-inch                 | 4         | 0.32%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch | 4         | 0.32%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch | 4         | 0.32%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 4         | 0.32%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 587       | 50.04%  |
| 1920x1080 (FHD)    | 352       | 30.01%  |
| 1280x800 (WXGA)    | 50        | 4.26%   |
| 1600x900 (HD+)     | 30        | 2.56%   |
| 3840x2160 (4K)     | 27        | 2.3%    |
| 1920x1200 (WUXGA)  | 25        | 2.13%   |
| 1440x900 (WXGA+)   | 17        | 1.45%   |
| 1024x600           | 13        | 1.11%   |
| 1280x1024 (SXGA)   | 9         | 0.77%   |
| 1680x1050 (WSXGA+) | 8         | 0.68%   |
| 1360x768           | 8         | 0.68%   |
| 2560x1080          | 6         | 0.51%   |
| 3200x1800 (QHD+)   | 5         | 0.43%   |
| 2880x1800          | 5         | 0.43%   |
| 2560x1600          | 5         | 0.43%   |
| 3840x2400          | 3         | 0.26%   |
| 2560x1440 (QHD)    | 3         | 0.26%   |
| 1920x540           | 3         | 0.26%   |
| 800x1280           | 2         | 0.17%   |
| 2288x1287          | 2         | 0.17%   |
| 3840x1100          | 1         | 0.09%   |
| 3840x1080          | 1         | 0.09%   |
| 3456x2160          | 1         | 0.09%   |
| 3440x1440          | 1         | 0.09%   |
| 3072x1920          | 1         | 0.09%   |
| 3000x2000          | 1         | 0.09%   |
| 2880x1620          | 1         | 0.09%   |
| 2560x2880          | 1         | 0.09%   |
| 2160x1440          | 1         | 0.09%   |
| 1920x1280          | 1         | 0.09%   |
| 1680x945           | 1         | 0.09%   |
| 1280x768           | 1         | 0.09%   |
| 1024x768 (XGA)     | 1         | 0.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 509       | 41.31%  |
| 14      | 208       | 16.88%  |
| 13      | 189       | 15.34%  |
| 17      | 37        | 3%      |
| 23      | 36        | 2.92%   |
| 27      | 28        | 2.27%   |
| 21      | 28        | 2.27%   |
| 18      | 26        | 2.11%   |
| 11      | 22        | 1.79%   |
| 10      | 19        | 1.54%   |
| 24      | 17        | 1.38%   |
| 40      | 16        | 1.3%    |
| 12      | 15        | 1.22%   |
| 20      | 12        | 0.97%   |
| 19      | 12        | 0.97%   |
| 16      | 12        | 0.97%   |
| 34      | 7         | 0.57%   |
| 46      | 5         | 0.41%   |
| 84      | 4         | 0.32%   |
| 52      | 4         | 0.32%   |
| 31      | 4         | 0.32%   |
| 48      | 3         | 0.24%   |
| 32      | 3         | 0.24%   |
| 142     | 2         | 0.16%   |
| 54      | 2         | 0.16%   |
| 22      | 2         | 0.16%   |
| 7       | 2         | 0.16%   |
| Unknown | 2         | 0.16%   |
| 86      | 1         | 0.08%   |
| 72      | 1         | 0.08%   |
| 65      | 1         | 0.08%   |
| 43      | 1         | 0.08%   |
| 41      | 1         | 0.08%   |
| 37      | 1         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 852       | 69.72%  |
| 201-300        | 97        | 7.94%   |
| 401-500        | 80        | 6.55%   |
| 501-600        | 73        | 5.97%   |
| 351-400        | 56        | 4.58%   |
| 801-900        | 17        | 1.39%   |
| 1001-1500      | 16        | 1.31%   |
| 701-800        | 10        | 0.82%   |
| 601-700        | 8         | 0.65%   |
| 1501-2000      | 5         | 0.41%   |
| More than 2000 | 2         | 0.16%   |
| 901-1000       | 2         | 0.16%   |
| 1-100          | 2         | 0.16%   |
| Unknown        | 2         | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 935       | 86.9%   |
| 16/10   | 105       | 9.76%   |
| 5/4     | 7         | 0.65%   |
| 21/9    | 7         | 0.65%   |
| 3/2     | 6         | 0.56%   |
| 4/3     | 4         | 0.37%   |
| 1.96    | 2         | 0.19%   |
| 1.00    | 2         | 0.19%   |
| 0.67    | 2         | 0.19%   |
| 6/5     | 1         | 0.09%   |
| 32/9    | 1         | 0.09%   |
| 3.40    | 1         | 0.09%   |
| 0.89    | 1         | 0.09%   |
| 0.56    | 1         | 0.09%   |
| Unknown | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 508       | 41.17%  |
| 81-90          | 365       | 29.58%  |
| 201-250        | 78        | 6.32%   |
| 141-150        | 30        | 2.43%   |
| 121-130        | 30        | 2.43%   |
| 71-80          | 28        | 2.27%   |
| 151-200        | 28        | 2.27%   |
| 301-350        | 27        | 2.19%   |
| 501-1000       | 27        | 2.19%   |
| 51-60          | 23        | 1.86%   |
| 41-50          | 19        | 1.54%   |
| More than 1000 | 15        | 1.22%   |
| 61-70          | 15        | 1.22%   |
| 351-500        | 15        | 1.22%   |
| 111-120        | 13        | 1.05%   |
| 91-100         | 4         | 0.32%   |
| 131-140        | 3         | 0.24%   |
| 1-40           | 2         | 0.16%   |
| 251-300        | 2         | 0.16%   |
| Unknown        | 2         | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 613       | 50.7%   |
| 121-160       | 313       | 25.89%  |
| 51-100        | 204       | 16.87%  |
| 161-240       | 32        | 2.65%   |
| 1-50          | 27        | 2.23%   |
| More than 240 | 18        | 1.49%   |
| Unknown       | 2         | 0.17%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 880       | 78.99%  |
| 2     | 187       | 16.79%  |
| 0     | 32        | 2.87%   |
| 3     | 14        | 1.26%   |
| 5     | 1         | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 683       | 40.53%  |
| Intel                                 | 440       | 26.11%  |
| Qualcomm Atheros                      | 241       | 14.3%   |
| Broadcom                              | 94        | 5.58%   |
| Broadcom Limited                      | 29        | 1.72%   |
| JMicron Technology                    | 26        | 1.54%   |
| Marvell Technology Group              | 24        | 1.42%   |
| TP-Link                               | 20        | 1.19%   |
| MediaTek                              | 17        | 1.01%   |
| Ralink                                | 16        | 0.95%   |
| Ralink Technology                     | 15        | 0.89%   |
| Samsung Electronics                   | 13        | 0.77%   |
| Silicon Integrated Systems [SiS]      | 12        | 0.71%   |
| Motorola PCS                          | 9         | 0.53%   |
| Qualcomm Atheros Communications       | 7         | 0.42%   |
| ASIX Electronics                      | 7         | 0.42%   |
| Nvidia                                | 4         | 0.24%   |
| Ericsson Business Mobile Networks     | 3         | 0.18%   |
| DisplayLink                           | 3         | 0.18%   |
| Xiaomi                                | 2         | 0.12%   |
| VIA Technologies                      | 2         | 0.12%   |
| Spreadtrum Communications             | 2         | 0.12%   |
| Lenovo                                | 2         | 0.12%   |
| ICS Advent                            | 2         | 0.12%   |
| Encore Electronics                    | 2         | 0.12%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.06%   |
| T & A Mobile Phones                   | 1         | 0.06%   |
| Sierra Wireless                       | 1         | 0.06%   |
| Ovislink                              | 1         | 0.06%   |
| Digitech Systems                      | 1         | 0.06%   |
| Dell                                  | 1         | 0.06%   |
| Cisco Aironet Wireless Communications | 1         | 0.06%   |
| Arduino SA                            | 1         | 0.06%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.06%   |
| 3DSP                                  | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 365       | 17.74%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 156       | 7.58%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 51        | 2.48%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 47        | 2.28%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 44        | 2.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 42        | 2.04%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 40        | 1.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 39        | 1.9%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 39        | 1.9%    |
| Intel Wi-Fi 6 AX201                                                    | 39        | 1.9%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 33        | 1.6%    |
| Intel Wireless 3160                                                    | 32        | 1.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 31        | 1.51%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 27        | 1.31%   |
| Intel Wireless 8265 / 8275                                             | 25        | 1.21%   |
| Intel Wireless 3165                                                    | 24        | 1.17%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 22        | 1.07%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 22        | 1.07%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 22        | 1.07%   |
| Intel Wireless 7260                                                    | 21        | 1.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 21        | 1.02%   |
| Intel Wi-Fi 6 AX200                                                    | 19        | 0.92%   |
| Intel Wireless 7265                                                    | 18        | 0.87%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 17        | 0.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 17        | 0.83%   |
| Realtek RTL8191SEvB Wireless LAN Controller                            | 16        | 0.78%   |
| Realtek 802.11n WLAN Adapter                                           | 16        | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 16        | 0.78%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 16        | 0.78%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 15        | 0.73%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 15        | 0.73%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 15        | 0.73%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 15        | 0.73%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                      | 15        | 0.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 14        | 0.68%   |
| Broadcom BCM43142 802.11b/g/n                                          | 14        | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 13        | 0.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 13        | 0.63%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 13        | 0.63%   |
| Intel Ethernet Connection (13) I219-V                                  | 13        | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 415       | 37.42%  |
| Realtek Semiconductor                 | 310       | 27.95%  |
| Qualcomm Atheros                      | 210       | 18.94%  |
| Broadcom                              | 82        | 7.39%   |
| Broadcom Limited                      | 18        | 1.62%   |
| Ralink                                | 16        | 1.44%   |
| Ralink Technology                     | 15        | 1.35%   |
| TP-Link                               | 14        | 1.26%   |
| MediaTek                              | 14        | 1.26%   |
| Qualcomm Atheros Communications       | 7         | 0.63%   |
| Encore Electronics                    | 2         | 0.18%   |
| Sierra Wireless                       | 1         | 0.09%   |
| Ovislink                              | 1         | 0.09%   |
| Ericsson Business Mobile Networks     | 1         | 0.09%   |
| Dell                                  | 1         | 0.09%   |
| Cisco Aironet Wireless Communications | 1         | 0.09%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 51        | 4.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 47        | 4.2%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 44        | 3.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 42        | 3.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 40        | 3.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 39        | 3.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 39        | 3.49%   |
| Intel Wi-Fi 6 AX201                                                     | 39        | 3.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 33        | 2.95%   |
| Intel Wireless 3160                                                     | 32        | 2.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 31        | 2.77%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 27        | 2.41%   |
| Intel Wireless 8265 / 8275                                              | 25        | 2.23%   |
| Intel Wireless 3165                                                     | 24        | 2.14%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 22        | 1.97%   |
| Intel Wireless 7260                                                     | 21        | 1.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 21        | 1.88%   |
| Intel Wi-Fi 6 AX200                                                     | 19        | 1.7%    |
| Intel Wireless 7265                                                     | 18        | 1.61%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 16        | 1.43%   |
| Realtek 802.11n WLAN Adapter                                            | 16        | 1.43%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 16        | 1.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 16        | 1.43%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 15        | 1.34%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 1.34%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 15        | 1.34%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 15        | 1.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 14        | 1.25%   |
| Broadcom BCM43142 802.11b/g/n                                           | 14        | 1.25%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 12        | 1.07%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 1.07%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 12        | 1.07%   |
| Intel Wireless 8260                                                     | 11        | 0.98%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 10        | 0.89%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 10        | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 9         | 0.8%    |
| Ralink MT7601U Wireless Adapter                                         | 9         | 0.8%    |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 9         | 0.8%    |
| Intel Tiger Lake PCH CNVi WiFi                                          | 8         | 0.71%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 0.63%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 559       | 60.17%  |
| Intel                            | 134       | 14.42%  |
| Qualcomm Atheros                 | 81        | 8.72%   |
| JMicron Technology               | 26        | 2.8%    |
| Broadcom                         | 25        | 2.69%   |
| Marvell Technology Group         | 24        | 2.58%   |
| Samsung Electronics              | 13        | 1.4%    |
| Silicon Integrated Systems [SiS] | 12        | 1.29%   |
| Broadcom Limited                 | 11        | 1.18%   |
| Motorola PCS                     | 8         | 0.86%   |
| ASIX Electronics                 | 7         | 0.75%   |
| TP-Link                          | 6         | 0.65%   |
| Nvidia                           | 4         | 0.43%   |
| MediaTek                         | 3         | 0.32%   |
| DisplayLink                      | 3         | 0.32%   |
| Xiaomi                           | 2         | 0.22%   |
| VIA Technologies                 | 2         | 0.22%   |
| Spreadtrum Communications        | 2         | 0.22%   |
| Lenovo                           | 2         | 0.22%   |
| ICS Advent                       | 2         | 0.22%   |
| T & A Mobile Phones              | 1         | 0.11%   |
| Digitech Systems                 | 1         | 0.11%   |
| 3DSP                             | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 365       | 39.16%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 156       | 16.74%  |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 22        | 2.36%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 22        | 2.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 17        | 1.82%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 17        | 1.82%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 15        | 1.61%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 13        | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 13        | 1.39%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 13        | 1.39%   |
| Intel Ethernet Connection (13) I219-V                                  | 13        | 1.39%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 12        | 1.29%   |
| Intel Ethernet Connection (4) I219-LM                                  | 12        | 1.29%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 11        | 1.18%   |
| Intel 82577LM Gigabit Network Connection                               | 10        | 1.07%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 9         | 0.97%   |
| Intel Ethernet Connection (10) I219-V                                  | 9         | 0.97%   |
| Motorola PCS moto g52                                                  | 8         | 0.86%   |
| Intel Ethernet Connection I218-LM                                      | 8         | 0.86%   |
| Intel Ethernet Connection I217-LM                                      | 7         | 0.75%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 6         | 0.64%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 6         | 0.64%   |
| Intel Ethernet Connection I219-LM                                      | 6         | 0.64%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 6         | 0.64%   |
| Realtek RTL8125 2.5GbE Controller                                      | 5         | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 5         | 0.54%   |
| Intel Ethernet Controller I225-V                                       | 5         | 0.54%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 5         | 0.54%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 5         | 0.54%   |
| TP-Link USB 10/100 LAN                                                 | 4         | 0.43%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 4         | 0.43%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 4         | 0.43%   |
| Intel PRO/100 VE Network Connection                                    | 4         | 0.43%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 0.43%   |
| Intel Ethernet Connection (13) I219-LM                                 | 4         | 0.43%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 0.43%   |
| Intel 82567LM Gigabit Network Connection                               | 4         | 0.43%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 4         | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 3         | 0.32%   |
| MediaTek moto e22                                                      | 3         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1062      | 54.13%  |
| Ethernet | 893       | 45.51%  |
| Modem    | 7         | 0.36%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 903       | 80.77%  |
| Ethernet | 215       | 19.23%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 815       | 74.98%  |
| 1     | 222       | 20.42%  |
| 0     | 45        | 4.14%   |
| 3     | 4         | 0.37%   |
| 4     | 1         | 0.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 934       | 84.91%  |
| Yes  | 166       | 15.09%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 324       | 42.41%  |
| Realtek Semiconductor           | 145       | 18.98%  |
| Qualcomm Atheros Communications | 69        | 9.03%   |
| IMC Networks                    | 53        | 6.94%   |
| Broadcom                        | 42        | 5.5%    |
| Lite-On Technology              | 36        | 4.71%   |
| Foxconn / Hon Hai               | 24        | 3.14%   |
| Dell                            | 13        | 1.7%    |
| Cambridge Silicon Radio         | 13        | 1.7%    |
| Apple                           | 13        | 1.7%    |
| Toshiba                         | 11        | 1.44%   |
| Ralink                          | 7         | 0.92%   |
| USI                             | 2         | 0.26%   |
| Qcom                            | 2         | 0.26%   |
| ASUSTek Computer                | 2         | 0.26%   |
| Alps Electric                   | 2         | 0.26%   |
| Syntek                          | 1         | 0.13%   |
| Realtek                         | 1         | 0.13%   |
| Ralink Technology               | 1         | 0.13%   |
| Integrated System Solution      | 1         | 0.13%   |
| Hewlett-Packard                 | 1         | 0.13%   |
| Foxconn International           | 1         | 0.13%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 137       | 17.91%  |
| Realtek Bluetooth Radio                                                             | 92        | 12.03%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 65        | 8.5%    |
| Intel AX201 Bluetooth                                                               | 58        | 7.58%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 43        | 5.62%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 37        | 4.84%   |
| IMC Networks Bluetooth Radio                                                        | 22        | 2.88%   |
| Intel AX200 Bluetooth                                                               | 19        | 2.48%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 16        | 2.09%   |
| Intel Bluetooth Device                                                              | 14        | 1.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 13        | 1.7%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 13        | 1.7%    |
| IMC Networks Bluetooth Device                                                       | 13        | 1.7%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 13        | 1.7%    |
| Lite-On Bluetooth Device                                                            | 12        | 1.57%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 12        | 1.57%   |
| Realtek RTL8723B Bluetooth                                                          | 8         | 1.05%   |
| IMC Networks Wireless_Device                                                        | 8         | 1.05%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 8         | 1.05%   |
| Toshiba Bluetooth USB Host Controller                                               | 7         | 0.92%   |
| Ralink RT3290 Bluetooth                                                             | 7         | 0.92%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 7         | 0.92%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 7         | 0.92%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 7         | 0.92%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 6         | 0.78%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 6         | 0.78%   |
| Apple Bluetooth USB Host Controller                                                 | 6         | 0.78%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 0.65%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 5         | 0.65%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 5         | 0.65%   |
| Dell Wireless 365 Bluetooth                                                         | 5         | 0.65%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 4         | 0.52%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 4         | 0.52%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 0.52%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 4         | 0.52%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 0.39%   |
| Lite-On Bluetooth Radio                                                             | 3         | 0.39%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 0.39%   |
| Intel AX210 Bluetooth                                                               | 3         | 0.39%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 887       | 73.73%  |
| AMD                              | 170       | 14.13%  |
| Nvidia                           | 69        | 5.74%   |
| Logitech                         | 13        | 1.08%   |
| Silicon Integrated Systems [SiS] | 12        | 1%      |
| C-Media Electronics              | 12        | 1%      |
| Kingston Technology              | 5         | 0.42%   |
| GN Netcom                        | 4         | 0.33%   |
| Plantronics                      | 3         | 0.25%   |
| VIA Technologies                 | 2         | 0.17%   |
| Texas Instruments                | 2         | 0.17%   |
| Sony                             | 2         | 0.17%   |
| Lenovo                           | 2         | 0.17%   |
| Hewlett-Packard                  | 2         | 0.17%   |
| Generalplus Technology           | 2         | 0.17%   |
| Focusrite-Novation               | 2         | 0.17%   |
| TEAC                             | 1         | 0.08%   |
| Samsung Electronics              | 1         | 0.08%   |
| Samson Technologies              | 1         | 0.08%   |
| Realtek Semiconductor            | 1         | 0.08%   |
| Microsoft                        | 1         | 0.08%   |
| JBL                              | 1         | 0.08%   |
| FiiO Electronics Technology      | 1         | 0.08%   |
| ESI Audiotechnik                 | 1         | 0.08%   |
| Creative Technology              | 1         | 0.08%   |
| Corsair                          | 1         | 0.08%   |
| BEHRINGER International          | 1         | 0.08%   |
| ATI Technologies                 | 1         | 0.08%   |
| ASUSTek Computer                 | 1         | 0.08%   |
| Astro Gaming                     | 1         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 145       | 10.08%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 108       | 7.51%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 84        | 5.84%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 66        | 4.59%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 60        | 4.17%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 50        | 3.48%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 49        | 3.41%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 43        | 2.99%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 43        | 2.99%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 39        | 2.71%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 36        | 2.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 36        | 2.5%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 35        | 2.43%   |
| Intel Broadwell-U Audio Controller                                                                | 35        | 2.43%   |
| Intel 8 Series HD Audio Controller                                                                | 35        | 2.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 32        | 2.23%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 29        | 2.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 28        | 1.95%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 26        | 1.81%   |
| AMD FCH Azalia Controller                                                                         | 25        | 1.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 24        | 1.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 23        | 1.6%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 22        | 1.53%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 21        | 1.46%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 19        | 1.32%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 17        | 1.18%   |
| AMD High Definition Audio Controller                                                              | 17        | 1.18%   |
| Intel CM238 HD Audio Controller                                                                   | 15        | 1.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 14        | 0.97%   |
| AMD Kabini HDMI/DP Audio                                                                          | 14        | 0.97%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 12        | 0.83%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 9         | 0.63%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 9         | 0.63%   |
| AMD Wrestler HDMI Audio                                                                           | 9         | 0.63%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 0.56%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 8         | 0.56%   |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 0.56%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 8         | 0.56%   |
| C-Media Electronics USB Advanced Audio Device                                                     | 8         | 0.56%   |
| AMD Trinity HDMI Audio Controller                                                                 | 8         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 188       | 25.68%  |
| SK hynix                                         | 133       | 18.17%  |
| Kingston                                         | 107       | 14.62%  |
| Micron Technology                                | 61        | 8.33%   |
| Unknown                                          | 38        | 5.19%   |
| A-DATA Technology                                | 32        | 4.37%   |
| Crucial                                          | 24        | 3.28%   |
| Unknown (ABCD)                                   | 17        | 2.32%   |
| Nanya Technology                                 | 15        | 2.05%   |
| Magnum Tech                                      | 14        | 1.91%   |
| Corsair                                          | 10        | 1.37%   |
| Elpida                                           | 9         | 1.23%   |
| Novatech                                         | 7         | 0.96%   |
| Ramaxel Technology                               | 6         | 0.82%   |
| Goldkey                                          | 6         | 0.82%   |
| Saikano                                          | 5         | 0.68%   |
| Memox                                            | 5         | 0.68%   |
| Neo Forza                                        | 4         | 0.55%   |
| 48spaces                                         | 4         | 0.55%   |
| Unknown                                          | 4         | 0.55%   |
| Unknown (0x0B45)                                 | 3         | 0.41%   |
| Transcend                                        | 3         | 0.41%   |
| Super Talent                                     | 3         | 0.41%   |
| Kingmax                                          | 3         | 0.41%   |
| Avant                                            | 3         | 0.41%   |
| Apacer                                           | 3         | 0.41%   |
| Teikon                                           | 2         | 0.27%   |
| Netac                                            | 2         | 0.27%   |
| Lexar                                            | 2         | 0.27%   |
| Kimtigo                                          | 2         | 0.27%   |
| Innodisk                                         | 2         | 0.27%   |
| G.Skill                                          | 2         | 0.27%   |
| CSX                                              | 2         | 0.27%   |
| Unknown (0x4E41324D3030314733374455202020202020) | 1         | 0.14%   |
| Unknown (0x4D342037305432393533455A332D43453620) | 1         | 0.14%   |
| Unknown (07D5)                                   | 1         | 0.14%   |
| Team                                             | 1         | 0.14%   |
| SHARETRONIC                                      | 1         | 0.14%   |
| Qimonda                                          | 1         | 0.14%   |
| PNY                                              | 1         | 0.14%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                     | 18        | 2.32%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s       | 17        | 2.19%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                    | 15        | 1.93%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                    | 15        | 1.93%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                     | 14        | 1.8%    |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s                       | 14        | 1.8%    |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s                  | 13        | 1.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 12        | 1.54%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 9         | 1.16%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                     | 8         | 1.03%   |
| Nanya RAM NT2GC64B88B0NS-CG 2048MB SODIMM DDR3 1334MT/s                   | 8         | 1.03%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 7         | 0.9%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 6         | 0.77%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s                  | 6         | 0.77%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s                     | 6         | 0.77%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 6         | 0.77%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                     | 5         | 0.64%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                     | 5         | 0.64%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 5         | 0.64%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                     | 5         | 0.64%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                     | 5         | 0.64%   |
| Saikano RAM Memory 4GB SODIMM DDR3 1333MT/s                               | 5         | 0.64%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                     | 5         | 0.64%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                    | 4         | 0.51%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s                    | 4         | 0.51%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                    | 4         | 0.51%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s                    | 4         | 0.51%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                     | 4         | 0.51%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                     | 4         | 0.51%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s                     | 4         | 0.51%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s               | 4         | 0.51%   |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s                     | 4         | 0.51%   |
| 48spaces RAM 012345678901234567890123456789012345 2GB SODIMM DDR2 667MT/s | 4         | 0.51%   |
| Unknown                                                                   | 4         | 0.51%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                               | 3         | 0.39%   |
| Unknown (0x0B45) RAM WPBH32D408SWD-8G 8GB SODIMM DDR4 3200MT/s            | 3         | 0.39%   |
| Super Talent RAM SUPERTALENT02 8GB SODIMM DDR3 1600MT/s                   | 3         | 0.39%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 0.39%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                    | 3         | 0.39%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s                    | 3         | 0.39%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 266       | 45.7%   |
| DDR3    | 223       | 38.32%  |
| LPDDR4  | 29        | 4.98%   |
| DDR2    | 24        | 4.12%   |
| SDRAM   | 11        | 1.89%   |
| LPDDR3  | 11        | 1.89%   |
| LPDDR5  | 5         | 0.86%   |
| DRAM    | 5         | 0.86%   |
| DDR     | 4         | 0.69%   |
| DDR5    | 3         | 0.52%   |
| Unknown | 1         | 0.17%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 542       | 92.33%  |
| Row Of Chips | 39        | 6.64%   |
| DIMM         | 3         | 0.51%   |
| Chip         | 2         | 0.34%   |
| Unknown      | 1         | 0.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 249       | 36.78%  |
| 4096  | 217       | 32.05%  |
| 2048  | 101       | 14.92%  |
| 16384 | 79        | 11.67%  |
| 1024  | 16        | 2.36%   |
| 32768 | 12        | 1.77%   |
| 512   | 2         | 0.3%    |
| 6144  | 1         | 0.15%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 140       | 20.96%  |
| 1600    | 136       | 20.36%  |
| 3200    | 115       | 17.22%  |
| 2400    | 57        | 8.53%   |
| 1333    | 50        | 7.49%   |
| 1334    | 39        | 5.84%   |
| 2133    | 28        | 4.19%   |
| Unknown | 17        | 2.54%   |
| 667     | 15        | 2.25%   |
| 3266    | 13        | 1.95%   |
| 1067    | 12        | 1.8%    |
| 4199    | 8         | 1.2%    |
| 6400    | 5         | 0.75%   |
| 800     | 5         | 0.75%   |
| 1066    | 4         | 0.6%    |
| 975     | 4         | 0.6%    |
| 4800    | 3         | 0.45%   |
| 4267    | 3         | 0.45%   |
| 4266    | 3         | 0.45%   |
| 2048    | 3         | 0.45%   |
| 533     | 3         | 0.45%   |
| 1867    | 2         | 0.3%    |
| 8400    | 1         | 0.15%   |
| 2933    | 1         | 0.15%   |
| 400     | 1         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 33.33%  |
| Brother Industries  | 3         | 33.33%  |
| Seiko Epson         | 1         | 11.11%  |
| QinHeng Electronics | 1         | 11.11%  |
| Kyocera             | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| HP LaserJet 1020        | 2         | 22.22%  |
| Seiko Epson L120 Series | 1         | 11.11%  |
| QinHeng CH340S          | 1         | 11.11%  |
| Kyocera ECOSYS M3550idn | 1         | 11.11%  |
| HP DeskJet F300 series  | 1         | 11.11%  |
| Brother HL-1200 series  | 1         | 11.11%  |
| Brother HL-1110 series  | 1         | 11.11%  |
| Brother DCP-1600        | 1         | 11.11%  |

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
| Chicony Electronics                    | 211       | 21.46%  |
| IMC Networks                           | 106       | 10.78%  |
| Realtek Semiconductor                  | 84        | 8.55%   |
| Microdia                               | 81        | 8.24%   |
| Bison Electronics                      | 63        | 6.41%   |
| Acer                                   | 46        | 4.68%   |
| Suyin                                  | 41        | 4.17%   |
| Syntek                                 | 40        | 4.07%   |
| Sunplus Innovation Technology          | 40        | 4.07%   |
| Quanta                                 | 40        | 4.07%   |
| Cheng Uei Precision Industry (Foxlink) | 33        | 3.36%   |
| Alcor Micro                            | 30        | 3.05%   |
| Silicon Motion                         | 28        | 2.85%   |
| Logitech                               | 13        | 1.32%   |
| Ricoh                                  | 12        | 1.22%   |
| Lite-On Technology                     | 12        | 1.22%   |
| Apple                                  | 12        | 1.22%   |
| SunplusIT                              | 10        | 1.02%   |
| USB Camera                             | 8         | 0.81%   |
| Luxvisions Innotech Limited            | 8         | 0.81%   |
| Z-Star Microelectronics                | 7         | 0.71%   |
| Sonix Technology                       | 7         | 0.71%   |
| Samsung Electronics                    | 6         | 0.61%   |
| OmniVision Technologies                | 5         | 0.51%   |
| 8SSC20F27114V1SR0BK1X4S                | 5         | 0.51%   |
| Y Media                                | 4         | 0.41%   |
| GEMBIRD                                | 4         | 0.41%   |
| ALi                                    | 4         | 0.41%   |
| Lenovo                                 | 3         | 0.31%   |
| Jieli Technology                       | 2         | 0.2%    |
| Intel                                  | 2         | 0.2%    |
| Importek                               | 2         | 0.2%    |
| Cubeternet                             | 2         | 0.2%    |
| USB Camera CS                          | 1         | 0.1%    |
| Sunplus Technology                     | 1         | 0.1%    |
| ShineTech                              | 1         | 0.1%    |
| OYT Tech                               | 1         | 0.1%    |
| Microsoft                              | 1         | 0.1%    |
| KYE Systems (Mouse Systems)            | 1         | 0.1%    |
| HRY                                    | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                             | 35        | 3.55%   |
| IMC Networks Integrated Camera                                 | 31        | 3.14%   |
| Chicony USB 2.0 Camera                                         | 31        | 3.14%   |
| Microdia Integrated_Webcam_HD                                  | 26        | 2.63%   |
| Alcor Micro USB 2.0 Camera                                     | 26        | 2.63%   |
| Bison Integrated Camera                                        | 23        | 2.33%   |
| Realtek USB Camera                                             | 22        | 2.23%   |
| Chicony Integrated Camera                                      | 22        | 2.23%   |
| Realtek Integrated_Webcam_HD                                   | 21        | 2.13%   |
| Chicony Lenovo EasyCamera                                      | 16        | 1.62%   |
| Syntek Integrated Camera                                       | 15        | 1.52%   |
| Chicony HD WebCam                                              | 15        | 1.52%   |
| Chicony USB2.0 Camera                                          | 14        | 1.42%   |
| Sunplus Integrated_Webcam_HD                                   | 13        | 1.32%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 13        | 1.32%   |
| Bison Lenovo EasyCamera                                        | 12        | 1.22%   |
| Chicony TOSHIBA Web Camera - HD                                | 11        | 1.11%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 11        | 1.11%   |
| Acer Integrated Camera                                         | 10        | 1.01%   |
| SunplusIT USB 2M Camera                                        | 9         | 0.91%   |
| Silicon Motion WebCam SC-0311139N                              | 9         | 0.91%   |
| Microdia USB 2.0 Camera                                        | 9         | 0.91%   |
| Acer SunplusIT Integrated Camera                               | 9         | 0.91%   |
| USB Camera USB Camera                                          | 8         | 0.81%   |
| Microdia Integrated Webcam                                     | 8         | 0.81%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 8         | 0.81%   |
| Chicony Integrated Camera (1280x720@30)                        | 8         | 0.81%   |
| Chicony HP TrueVision HD Camera                                | 8         | 0.81%   |
| Acer BisonCam, NB Pro                                          | 8         | 0.81%   |
| Z-Star Webcam                                                  | 7         | 0.71%   |
| Syntek Lenovo EasyCamera                                       | 7         | 0.71%   |
| Syntek EasyCamera                                              | 7         | 0.71%   |
| Chicony EasyCamera                                             | 7         | 0.71%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 7         | 0.71%   |
| Sunplus Asus Webcam                                            | 6         | 0.61%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 6         | 0.61%   |
| Realtek USB2.0 HD UVC WebCam                                   | 6         | 0.61%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 6         | 0.61%   |
| Lite-On Integrated Camera                                      | 6         | 0.61%   |
| IMC Networks UVC VGA Webcam                                    | 6         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 44        | 32.12%  |
| Validity Sensors                   | 38        | 27.74%  |
| Shenzhen Goodix Technology         | 25        | 18.25%  |
| Upek                               | 8         | 5.84%   |
| AuthenTec                          | 7         | 5.11%   |
| LighTuning Technology              | 6         | 4.38%   |
| Elan Microelectronics              | 6         | 4.38%   |
| STMicroelectronics                 | 1         | 0.73%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.73%   |
| Focal-systems.Corp                 | 1         | 0.73%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 20        | 14.6%   |
| Shenzhen Goodix  FingerPrint Device                                        | 20        | 14.6%   |
| Synaptics  WBDI                                                            | 14        | 10.22%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 11        | 8.03%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 8         | 5.84%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 4.38%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 3.65%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 2.92%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 4         | 2.92%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 2.92%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 4         | 2.92%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 3         | 2.19%   |
| Elan ELAN:Fingerprint                                                      | 3         | 2.19%   |
| Elan ELAN:ARM-M4                                                           | 3         | 2.19%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.46%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.46%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.46%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.46%   |
| AuthenTec AES2810                                                          | 2         | 1.46%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.46%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.73%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.73%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 0.73%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.73%   |
| Synaptics UWP WBDI Device                                                  | 1         | 0.73%   |
| Synaptics TouchPad                                                         | 1         | 0.73%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.73%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.73%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.73%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.73%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.73%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.73%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.73%   |
| Focal-systems.Corp FT9201Fingerprint.Ì                                  | 1         | 0.73%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.73%   |
| Unknown                                                                    | 1         | 0.73%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 24        | 63.16%  |
| Upek        | 10        | 26.32%  |
| Lenovo      | 2         | 5.26%   |
| O2 Micro    | 1         | 2.63%   |
| Alcor Micro | 1         | 2.63%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 10        | 26.32%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 18.42%  |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 18.42%  |
| Broadcom 58200                                                               | 7         | 18.42%  |
| Broadcom 5880                                                                | 3         | 7.89%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.63%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 2.63%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 770       | 69.56%  |
| 1     | 298       | 26.92%  |
| 2     | 35        | 3.16%   |
| 3     | 3         | 0.27%   |
| 8     | 1         | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 136       | 35.88%  |
| Graphics card            | 92        | 24.27%  |
| Net/wireless             | 48        | 12.66%  |
| Chipcard                 | 35        | 9.23%   |
| Multimedia controller    | 18        | 4.75%   |
| Camera                   | 15        | 3.96%   |
| Bluetooth                | 12        | 3.17%   |
| Communication controller | 7         | 1.85%   |
| Sound                    | 4         | 1.06%   |
| Net/ethernet             | 4         | 1.06%   |
| Network                  | 2         | 0.53%   |
| Modem                    | 2         | 0.53%   |
| Flash memory             | 2         | 0.53%   |
| Card reader              | 2         | 0.53%   |

