Linux in Kazakhstan - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------------------

A project to collect tested hardware configurations for Linux in Kazakhstan.

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

Total: 414

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | VivoBook_ASUSLaptop K650... | [8a833d8c52](https://linux-hardware.org/?probe=8a833d8c52) | Jun 25, 2023 |
| Acer          | Aspire A315-51              | [0e6960c76b](https://linux-hardware.org/?probe=0e6960c76b) | Jun 22, 2023 |
| Acer          | Aspire A315-51              | [981385c200](https://linux-hardware.org/?probe=981385c200) | Jun 22, 2023 |
| HP            | Laptop 15-rb0xx             | [067eeb10e5](https://linux-hardware.org/?probe=067eeb10e5) | Jun 19, 2023 |
| HUAWEI        | BOM-WXX9                    | [130605379e](https://linux-hardware.org/?probe=130605379e) | Jun 15, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [dd2a8a9559](https://linux-hardware.org/?probe=dd2a8a9559) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | [a6d6fdfe4f](https://linux-hardware.org/?probe=a6d6fdfe4f) | Jun 02, 2023 |
| Acer          | Aspire ES1-523              | [bd06482a4e](https://linux-hardware.org/?probe=bd06482a4e) | May 27, 2023 |
| HP            | Notebook                    | [3467291a26](https://linux-hardware.org/?probe=3467291a26) | May 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [02df3a407e](https://linux-hardware.org/?probe=02df3a407e) | May 03, 2023 |
| HP            | Pavilion Notebook           | [168b3cf595](https://linux-hardware.org/?probe=168b3cf595) | Apr 29, 2023 |
| ASUSTek       | X55VD                       | [16ef8c0549](https://linux-hardware.org/?probe=16ef8c0549) | Apr 27, 2023 |
| Lenovo        | Legion 5P 15IMH05H 82AW     | [61408603be](https://linux-hardware.org/?probe=61408603be) | Apr 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [0187ac7a0c](https://linux-hardware.org/?probe=0187ac7a0c) | Apr 19, 2023 |
| Acer          | Aspire A515-57              | [ea0055d848](https://linux-hardware.org/?probe=ea0055d848) | Apr 14, 2023 |
| Dell          | G5 5590                     | [9c1f2f432b](https://linux-hardware.org/?probe=9c1f2f432b) | Apr 11, 2023 |
| HP            | Notebook                    | [41f9931a45](https://linux-hardware.org/?probe=41f9931a45) | Apr 07, 2023 |
| HP            | Notebook                    | [a344d6edef](https://linux-hardware.org/?probe=a344d6edef) | Apr 05, 2023 |
| GPD           | G1621-02                    | [7d000ab41b](https://linux-hardware.org/?probe=7d000ab41b) | Mar 31, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [252d340923](https://linux-hardware.org/?probe=252d340923) | Mar 30, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [3173dc99b6](https://linux-hardware.org/?probe=3173dc99b6) | Mar 27, 2023 |
| Lenovo        | G570 20079                  | [8657b8d645](https://linux-hardware.org/?probe=8657b8d645) | Mar 21, 2023 |
| ASUSTek       | X55VDR                      | [b4eb9dbf58](https://linux-hardware.org/?probe=b4eb9dbf58) | Mar 20, 2023 |
| ASUSTek       | N56DP                       | [c49dee996b](https://linux-hardware.org/?probe=c49dee996b) | Mar 19, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [f7727e4bcb](https://linux-hardware.org/?probe=f7727e4bcb) | Mar 17, 2023 |
| HP            | 245 14 inch G9 Notebook ... | [03edff3e6f](https://linux-hardware.org/?probe=03edff3e6f) | Mar 16, 2023 |
| HP            | Laptop 15s-eq3xxx           | [a08a3c36ab](https://linux-hardware.org/?probe=a08a3c36ab) | Feb 28, 2023 |
| ASUSTek       | ROG Strix G712LW_G712LW     | [ed67c567d2](https://linux-hardware.org/?probe=ed67c567d2) | Feb 28, 2023 |
| GPD           | G1621-02                    | [5d584fa1cf](https://linux-hardware.org/?probe=5d584fa1cf) | Feb 14, 2023 |
| HP            | Laptop 15s-eq3xxx           | [36dd5f42fc](https://linux-hardware.org/?probe=36dd5f42fc) | Feb 11, 2023 |
| Acer          | Aspire A315-51              | [b644932b49](https://linux-hardware.org/?probe=b644932b49) | Feb 06, 2023 |
| Acer          | Aspire E5-575G              | [30e2a88930](https://linux-hardware.org/?probe=30e2a88930) | Feb 05, 2023 |
| HP            | Laptop 15s-eq3xxx           | [ba7531b9db](https://linux-hardware.org/?probe=ba7531b9db) | Feb 05, 2023 |
| HP            | Laptop 15s-eq3xxx           | [72228118bb](https://linux-hardware.org/?probe=72228118bb) | Feb 05, 2023 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [bd19e14a45](https://linux-hardware.org/?probe=bd19e14a45) | Feb 02, 2023 |
| HP            | Laptop 15s-eq3xxx           | [e9525c9a86](https://linux-hardware.org/?probe=e9525c9a86) | Jan 31, 2023 |
| HP            | Laptop 15s-eq3xxx           | [e6cb9d8296](https://linux-hardware.org/?probe=e6cb9d8296) | Jan 31, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [a732875be3](https://linux-hardware.org/?probe=a732875be3) | Jan 29, 2023 |
| ASUSTek       | N56DP                       | [a746d3fd78](https://linux-hardware.org/?probe=a746d3fd78) | Jan 27, 2023 |
| HP            | Laptop 15s-eq3xxx           | [b00e46e17f](https://linux-hardware.org/?probe=b00e46e17f) | Jan 23, 2023 |
| HP            | Laptop 15s-eq3xxx           | [1a9aaa1cb2](https://linux-hardware.org/?probe=1a9aaa1cb2) | Jan 22, 2023 |
| HP            | Laptop 15s-eq3xxx           | [4ed27b0b56](https://linux-hardware.org/?probe=4ed27b0b56) | Jan 22, 2023 |
| HP            | Laptop 15s-eq3xxx           | [0ba680dd8f](https://linux-hardware.org/?probe=0ba680dd8f) | Jan 22, 2023 |
| HP            | Laptop 15s-eq3xxx           | [d2d30c8d6f](https://linux-hardware.org/?probe=d2d30c8d6f) | Jan 21, 2023 |
| HP            | Laptop 15s-eq3xxx           | [07cf342b4f](https://linux-hardware.org/?probe=07cf342b4f) | Jan 20, 2023 |
| HP            | Laptop 15s-eq3xxx           | [78791e5b9e](https://linux-hardware.org/?probe=78791e5b9e) | Jan 20, 2023 |
| Acer          | Swift SF113-31              | [de76cee99a](https://linux-hardware.org/?probe=de76cee99a) | Jan 16, 2023 |
| Lenovo        | IdeaPad Z510 20287          | [71f6d9b711](https://linux-hardware.org/?probe=71f6d9b711) | Jan 12, 2023 |
| Lenovo        | G500 20236                  | [6a873e3df8](https://linux-hardware.org/?probe=6a873e3df8) | Jan 12, 2023 |
| Unknown       | Unknown                     | [cbd401e3c6](https://linux-hardware.org/?probe=cbd401e3c6) | Jan 11, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [70d5242ad0](https://linux-hardware.org/?probe=70d5242ad0) | Jan 01, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | [3111141139](https://linux-hardware.org/?probe=3111141139) | Dec 26, 2022 |
| Acer          | Aspire A315-51              | [b53beddded](https://linux-hardware.org/?probe=b53beddded) | Dec 23, 2022 |
| Acer          | Aspire A315-51              | [4fc8630d91](https://linux-hardware.org/?probe=4fc8630d91) | Dec 22, 2022 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [bbc48ee483](https://linux-hardware.org/?probe=bbc48ee483) | Dec 20, 2022 |
| Acer          | Aspire A315-51              | [8777d682b0](https://linux-hardware.org/?probe=8777d682b0) | Dec 20, 2022 |
| Acer          | Aspire A315-51              | [faf7ad4c29](https://linux-hardware.org/?probe=faf7ad4c29) | Dec 19, 2022 |
| Acer          | Aspire A315-51              | [116b321e68](https://linux-hardware.org/?probe=116b321e68) | Dec 16, 2022 |
| Lenovo        | ThinkPad X240 20AL007AMZ    | [8290c7e597](https://linux-hardware.org/?probe=8290c7e597) | Dec 16, 2022 |
| Acer          | Aspire A315-51              | [5f2e420614](https://linux-hardware.org/?probe=5f2e420614) | Dec 15, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [6ae6d710b7](https://linux-hardware.org/?probe=6ae6d710b7) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [b56f450d6d](https://linux-hardware.org/?probe=b56f450d6d) | Dec 10, 2022 |
| Acer          | Aspire A315-51              | [1b1e1ae174](https://linux-hardware.org/?probe=1b1e1ae174) | Dec 08, 2022 |
| Acer          | Aspire A315-51              | [26828f578e](https://linux-hardware.org/?probe=26828f578e) | Dec 05, 2022 |
| Toshiba       | TECRA S11                   | [3d2414e47b](https://linux-hardware.org/?probe=3d2414e47b) | Nov 30, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [ef6247e6fd](https://linux-hardware.org/?probe=ef6247e6fd) | Nov 28, 2022 |
| Dell          | Precision M6400             | [05f69c6917](https://linux-hardware.org/?probe=05f69c6917) | Nov 28, 2022 |
| GPD           | G1621-02                    | [d6b679024c](https://linux-hardware.org/?probe=d6b679024c) | Nov 26, 2022 |
| GPD           | G1621-02                    | [f0e9e8442c](https://linux-hardware.org/?probe=f0e9e8442c) | Nov 26, 2022 |
| Acer          | Aspire A315-51              | [e08bf40900](https://linux-hardware.org/?probe=e08bf40900) | Nov 25, 2022 |
| Acer          | Aspire A315-51              | [a636cfb9ff](https://linux-hardware.org/?probe=a636cfb9ff) | Nov 24, 2022 |
| Acer          | Swift SF314-58G             | [9e729e43a7](https://linux-hardware.org/?probe=9e729e43a7) | Nov 20, 2022 |
| Dell          | Latitude 5520               | [c658158f10](https://linux-hardware.org/?probe=c658158f10) | Nov 15, 2022 |
| Dell          | Latitude 5520               | [6e0490d1bf](https://linux-hardware.org/?probe=6e0490d1bf) | Nov 14, 2022 |
| Lenovo        | Legion R9000P ARH7H 82RG    | [d584008808](https://linux-hardware.org/?probe=d584008808) | Nov 14, 2022 |
| Lenovo        | G500 20236                  | [b156c32896](https://linux-hardware.org/?probe=b156c32896) | Nov 12, 2022 |
| Chuwi         | CoreBook XPro               | [0a0932246f](https://linux-hardware.org/?probe=0a0932246f) | Nov 09, 2022 |
| Acer          | Aspire A315-51              | [d5c179046a](https://linux-hardware.org/?probe=d5c179046a) | Nov 07, 2022 |
| Lenovo        | G500 20236                  | [76d6e74fad](https://linux-hardware.org/?probe=76d6e74fad) | Nov 07, 2022 |
| Acer          | Aspire A315-51              | [eaa9bcaadb](https://linux-hardware.org/?probe=eaa9bcaadb) | Oct 31, 2022 |
| Acer          | Aspire A315-51              | [7b016c85d8](https://linux-hardware.org/?probe=7b016c85d8) | Oct 31, 2022 |
| Acer          | Aspire A315-51              | [17faa0d40a](https://linux-hardware.org/?probe=17faa0d40a) | Oct 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [8b68d25121](https://linux-hardware.org/?probe=8b68d25121) | Oct 26, 2022 |
| Acer          | Aspire A315-51              | [244d93ab06](https://linux-hardware.org/?probe=244d93ab06) | Oct 21, 2022 |
| Acer          | Aspire A315-51              | [dc26121480](https://linux-hardware.org/?probe=dc26121480) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [4c95f64c92](https://linux-hardware.org/?probe=4c95f64c92) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [2740d3c96e](https://linux-hardware.org/?probe=2740d3c96e) | Oct 16, 2022 |
| Lenovo        | ThinkPad X230 23257BG       | [6c8a42718a](https://linux-hardware.org/?probe=6c8a42718a) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [54d1a0ebb2](https://linux-hardware.org/?probe=54d1a0ebb2) | Oct 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [7969631063](https://linux-hardware.org/?probe=7969631063) | Oct 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [f5e933eaac](https://linux-hardware.org/?probe=f5e933eaac) | Oct 10, 2022 |
| Acer          | Swift SF314-511             | [6270245e93](https://linux-hardware.org/?probe=6270245e93) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [2ac8b7a157](https://linux-hardware.org/?probe=2ac8b7a157) | Oct 03, 2022 |
| ASUSTek       | X550CL                      | [ded047597e](https://linux-hardware.org/?probe=ded047597e) | Sep 28, 2022 |
| Sony          | VGN-FW245J                  | [ab3391f43e](https://linux-hardware.org/?probe=ab3391f43e) | Sep 18, 2022 |
| Chuwi         | UBook XPro                  | [b695b65d86](https://linux-hardware.org/?probe=b695b65d86) | Sep 10, 2022 |
| HP            | ProBook 640 G4              | [b76e5a62e8](https://linux-hardware.org/?probe=b76e5a62e8) | Sep 06, 2022 |
| HONOR         | NBR-WAX9                    | [7e2c842043](https://linux-hardware.org/?probe=7e2c842043) | Aug 25, 2022 |
| Lenovo        | ThinkPad E470 20H1006HRT    | [ff4adb2f7d](https://linux-hardware.org/?probe=ff4adb2f7d) | Jul 20, 2022 |
| Sony          | VPCEA3M1R                   | [0bdfc50874](https://linux-hardware.org/?probe=0bdfc50874) | Jul 16, 2022 |
| HP            | ProBook 645 G3              | [5c37a32531](https://linux-hardware.org/?probe=5c37a32531) | Jul 04, 2022 |
| Acer          | Aspire A315-55KG            | [223d853d4e](https://linux-hardware.org/?probe=223d853d4e) | Jun 29, 2022 |
| HP            | ProBook 430 G4              | [4b4944017c](https://linux-hardware.org/?probe=4b4944017c) | Jun 25, 2022 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | [83c0821672](https://linux-hardware.org/?probe=83c0821672) | Jun 25, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [822554f0be](https://linux-hardware.org/?probe=822554f0be) | Jun 23, 2022 |
| Lenovo        | IdeaPad S510p 20298         | [3ddae75872](https://linux-hardware.org/?probe=3ddae75872) | Jun 22, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [47b04cd99f](https://linux-hardware.org/?probe=47b04cd99f) | Jun 21, 2022 |
| Lenovo        | ThinkPad T430 2349NM8       | [44e08ed5c6](https://linux-hardware.org/?probe=44e08ed5c6) | Jun 04, 2022 |
| Dell          | Inspiron 7577               | [3709bf11a9](https://linux-hardware.org/?probe=3709bf11a9) | Jun 01, 2022 |
| Acer          | Aspire 5750G                | [e04f02de57](https://linux-hardware.org/?probe=e04f02de57) | May 23, 2022 |
| Acer          | Aspire 5750G                | [eb1685b47e](https://linux-hardware.org/?probe=eb1685b47e) | May 22, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | [a44f38fd50](https://linux-hardware.org/?probe=a44f38fd50) | May 21, 2022 |
| Acer          | Aspire 5750G                | [910cae5e1e](https://linux-hardware.org/?probe=910cae5e1e) | May 21, 2022 |
| IBM           | ThinkPad T43 2668F5G        | [af59841e31](https://linux-hardware.org/?probe=af59841e31) | May 18, 2022 |
| Lenovo        | V14-ADA 82C6                | [5f3fea62ab](https://linux-hardware.org/?probe=5f3fea62ab) | May 16, 2022 |
| Acer          | Aspire 5750G                | [d60d62217c](https://linux-hardware.org/?probe=d60d62217c) | May 10, 2022 |
| Acer          | Aspire 5750G                | [1c49000609](https://linux-hardware.org/?probe=1c49000609) | May 09, 2022 |
| Acer          | Aspire 5750G                | [7e229f1bb3](https://linux-hardware.org/?probe=7e229f1bb3) | May 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [20420f0426](https://linux-hardware.org/?probe=20420f0426) | May 02, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [f0f822fa1b](https://linux-hardware.org/?probe=f0f822fa1b) | Apr 25, 2022 |
| Fujitsu       | LIFEBOOK AH531              | [0324fe4cc6](https://linux-hardware.org/?probe=0324fe4cc6) | Apr 23, 2022 |
| Acer          | Aspire 5750G                | [37a57a968f](https://linux-hardware.org/?probe=37a57a968f) | Apr 19, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [32371c52a6](https://linux-hardware.org/?probe=32371c52a6) | Apr 13, 2022 |
| Dell          | Latitude 3520               | [4398aa2a03](https://linux-hardware.org/?probe=4398aa2a03) | Apr 06, 2022 |
| HP            | ProBook 6570b               | [cf1305eacc](https://linux-hardware.org/?probe=cf1305eacc) | Apr 06, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | [d406cb4819](https://linux-hardware.org/?probe=d406cb4819) | Apr 05, 2022 |
| HP            | Pavilion 17                 | [e3071e1f70](https://linux-hardware.org/?probe=e3071e1f70) | Apr 02, 2022 |
| Acer          | Aspire A315-34              | [6f53445c9d](https://linux-hardware.org/?probe=6f53445c9d) | Mar 05, 2022 |
| Acer          | Aspire A315-41G             | [565ef5309f](https://linux-hardware.org/?probe=565ef5309f) | Feb 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [823e19e6d3](https://linux-hardware.org/?probe=823e19e6d3) | Feb 19, 2022 |
| Acer          | Aspire A315-41G             | [21e91da000](https://linux-hardware.org/?probe=21e91da000) | Feb 19, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ed75c609e4](https://linux-hardware.org/?probe=ed75c609e4) | Feb 16, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [470a550d41](https://linux-hardware.org/?probe=470a550d41) | Feb 16, 2022 |
| Lenovo        | ThinkPad T460 20FMS2TG0D    | [f51933de6d](https://linux-hardware.org/?probe=f51933de6d) | Feb 10, 2022 |
| Lenovo        | ThinkPad T490 20N20009RT    | [538c4fb88c](https://linux-hardware.org/?probe=538c4fb88c) | Jan 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [a6a7106d83](https://linux-hardware.org/?probe=a6a7106d83) | Jan 26, 2022 |
| Samsung       | N100SP                      | [47ec2e67d9](https://linux-hardware.org/?probe=47ec2e67d9) | Jan 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0b4b86fd4d](https://linux-hardware.org/?probe=0b4b86fd4d) | Dec 30, 2021 |
| HP            | Pavilion 15                 | [7248fa574f](https://linux-hardware.org/?probe=7248fa574f) | Dec 20, 2021 |
| Fujitsu       | LIFEBOOK AH531              | [b294d0719f](https://linux-hardware.org/?probe=b294d0719f) | Dec 14, 2021 |
| Dell          | XPS 13 9310                 | [38cf5730b3](https://linux-hardware.org/?probe=38cf5730b3) | Dec 08, 2021 |
| Dell          | XPS 13 9310                 | [4501078e9a](https://linux-hardware.org/?probe=4501078e9a) | Dec 08, 2021 |
| ASUSTek       | K50IE                       | [985ed9e52c](https://linux-hardware.org/?probe=985ed9e52c) | Dec 05, 2021 |
| ASUSTek       | X51RL                       | [0aeee18806](https://linux-hardware.org/?probe=0aeee18806) | Nov 19, 2021 |
| HP            | Pavilion 15                 | [d6caf6dd12](https://linux-hardware.org/?probe=d6caf6dd12) | Nov 17, 2021 |
| HP            | Pavilion 15                 | [581a56e963](https://linux-hardware.org/?probe=581a56e963) | Nov 17, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [924d961707](https://linux-hardware.org/?probe=924d961707) | Nov 12, 2021 |
| HP            | Laptop 17-ca1xxx            | [61fe4e654d](https://linux-hardware.org/?probe=61fe4e654d) | Nov 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [67a9ba5988](https://linux-hardware.org/?probe=67a9ba5988) | Oct 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [9145964032](https://linux-hardware.org/?probe=9145964032) | Oct 30, 2021 |
| ASUSTek       | N56DP                       | [7332da68ec](https://linux-hardware.org/?probe=7332da68ec) | Oct 25, 2021 |
| HP            | Pavilion Sleekbook 15 PC    | [10a67c9e23](https://linux-hardware.org/?probe=10a67c9e23) | Oct 16, 2021 |
| Acer          | Aspire A315-55KG            | [79534f4c8c](https://linux-hardware.org/?probe=79534f4c8c) | Oct 10, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [1103bd0a01](https://linux-hardware.org/?probe=1103bd0a01) | Oct 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [008072f061](https://linux-hardware.org/?probe=008072f061) | Oct 05, 2021 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [96463d6903](https://linux-hardware.org/?probe=96463d6903) | Sep 16, 2021 |
| Lenovo        | ThinkPad T480 20L6SBGK00    | [fc6636e0b5](https://linux-hardware.org/?probe=fc6636e0b5) | Sep 09, 2021 |
| HP            | ProBook 4320s               | [94f189cea1](https://linux-hardware.org/?probe=94f189cea1) | Aug 29, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [45ec27282a](https://linux-hardware.org/?probe=45ec27282a) | Aug 23, 2021 |
| HP            | Pavilion dm1                | [ac0e534d86](https://linux-hardware.org/?probe=ac0e534d86) | Aug 01, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [2a645d9cba](https://linux-hardware.org/?probe=2a645d9cba) | Jul 27, 2021 |
| HP            | Laptop 15s-fq2xxx           | [2f259b4ae2](https://linux-hardware.org/?probe=2f259b4ae2) | Jul 26, 2021 |
| HP            | EliteBook 8470p             | [8bfc663f48](https://linux-hardware.org/?probe=8bfc663f48) | Jul 26, 2021 |
| HP            | 635                         | [06f1ff97b5](https://linux-hardware.org/?probe=06f1ff97b5) | Jul 24, 2021 |
| Elenberg      | EL_T1011                    | [c2e05805b1](https://linux-hardware.org/?probe=c2e05805b1) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | [d977beba9e](https://linux-hardware.org/?probe=d977beba9e) | Jul 22, 2021 |
| HP            | 15                          | [fcc367258f](https://linux-hardware.org/?probe=fcc367258f) | Jul 17, 2021 |
| Unknown       | Unknown                     | [b7fe3d0d08](https://linux-hardware.org/?probe=b7fe3d0d08) | Jul 16, 2021 |
| Lenovo        | ThinkPad T580 20L9S0D100    | [e7f9397916](https://linux-hardware.org/?probe=e7f9397916) | Jul 02, 2021 |
| Acer          | Aspire A715-75G             | [1d185733d4](https://linux-hardware.org/?probe=1d185733d4) | Jun 24, 2021 |
| Acer          | Mandolin                    | [c5a4b06851](https://linux-hardware.org/?probe=c5a4b06851) | Jun 13, 2021 |
| ASUSTek       | TUF Gaming FX504GM_FX80G... | [6b37e8a34b](https://linux-hardware.org/?probe=6b37e8a34b) | May 25, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [e74c6f6436](https://linux-hardware.org/?probe=e74c6f6436) | May 16, 2021 |
| Lenovo        | ThinkPad Edge E530 3259C... | [b79dcdb648](https://linux-hardware.org/?probe=b79dcdb648) | May 03, 2021 |
| Lenovo        | ThinkPad Edge E530 3259C... | [b02527f8e5](https://linux-hardware.org/?probe=b02527f8e5) | May 03, 2021 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [1a6e48b6a6](https://linux-hardware.org/?probe=1a6e48b6a6) | Apr 29, 2021 |
| ASUSTek       | GL553VE                     | [b4f123b6df](https://linux-hardware.org/?probe=b4f123b6df) | Apr 20, 2021 |
| Acer          | AO722                       | [6d09f4a364](https://linux-hardware.org/?probe=6d09f4a364) | Apr 20, 2021 |
| ASUSTek       | X550LA                      | [69647941af](https://linux-hardware.org/?probe=69647941af) | Apr 20, 2021 |
| Acer          | AOHAPPY2                    | [1ab9a823ac](https://linux-hardware.org/?probe=1ab9a823ac) | Apr 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [895cfbdea8](https://linux-hardware.org/?probe=895cfbdea8) | Mar 31, 2021 |
| HP            | ENVY m6                     | [1f794c0fc3](https://linux-hardware.org/?probe=1f794c0fc3) | Mar 29, 2021 |
| Dell          | Inspiron 3793               | [324235179d](https://linux-hardware.org/?probe=324235179d) | Mar 19, 2021 |
| ASUSTek       | S301LA                      | [c8c4934145](https://linux-hardware.org/?probe=c8c4934145) | Mar 17, 2021 |
| Acer          | Predator PH317-54           | [0e97801264](https://linux-hardware.org/?probe=0e97801264) | Mar 12, 2021 |
| Acer          | Nitro AN515-44              | [c58e02d129](https://linux-hardware.org/?probe=c58e02d129) | Mar 07, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [9924631e4c](https://linux-hardware.org/?probe=9924631e4c) | Feb 23, 2021 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [fb1f894d4f](https://linux-hardware.org/?probe=fb1f894d4f) | Feb 22, 2021 |
| Acer          | Aspire A715-75G             | [4e22c88014](https://linux-hardware.org/?probe=4e22c88014) | Feb 18, 2021 |
| Sony          | VGN-NR430E                  | [62beb0a340](https://linux-hardware.org/?probe=62beb0a340) | Feb 04, 2021 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [e5c078c0d7](https://linux-hardware.org/?probe=e5c078c0d7) | Jan 23, 2021 |
| Acer          | Aspire A315-55KG            | [c62e2ea4ae](https://linux-hardware.org/?probe=c62e2ea4ae) | Jan 22, 2021 |
| Acer          | Aspire V3-551G              | [16932ea052](https://linux-hardware.org/?probe=16932ea052) | Jan 13, 2021 |
| Acer          | Aspire V3-551G              | [b697976568](https://linux-hardware.org/?probe=b697976568) | Jan 13, 2021 |
| Acer          | Extensa 2519                | [bc19a19f7c](https://linux-hardware.org/?probe=bc19a19f7c) | Dec 22, 2020 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [cd5bccf387](https://linux-hardware.org/?probe=cd5bccf387) | Dec 13, 2020 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [f6edf147c0](https://linux-hardware.org/?probe=f6edf147c0) | Dec 13, 2020 |
| Acer          | Nitro AN515-52              | [7041c80e3b](https://linux-hardware.org/?probe=7041c80e3b) | Nov 28, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d081baf21f](https://linux-hardware.org/?probe=d081baf21f) | Nov 22, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f149c45438](https://linux-hardware.org/?probe=f149c45438) | Nov 21, 2020 |
| Dell          | G3 3500                     | [d6386ecea5](https://linux-hardware.org/?probe=d6386ecea5) | Nov 07, 2020 |
| Lenovo        | G580 20157                  | [29bf11dd7c](https://linux-hardware.org/?probe=29bf11dd7c) | Nov 03, 2020 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [fec4f6d683](https://linux-hardware.org/?probe=fec4f6d683) | Oct 31, 2020 |
| Acer          | Nitro AN515-52              | [f6e1215c02](https://linux-hardware.org/?probe=f6e1215c02) | Oct 22, 2020 |
| ASUSTek       | U47A                        | [b7c3bb57cf](https://linux-hardware.org/?probe=b7c3bb57cf) | Oct 20, 2020 |
| HP            | Pavilion 17                 | [d016742bce](https://linux-hardware.org/?probe=d016742bce) | Oct 20, 2020 |
| HP            | 250 G3                      | [100536aea2](https://linux-hardware.org/?probe=100536aea2) | Oct 17, 2020 |
| Lenovo        | Y720-15IKB 80VR             | [3ec85a9391](https://linux-hardware.org/?probe=3ec85a9391) | Oct 15, 2020 |
| ASUSTek       | X540SA                      | [1f6a3f87d7](https://linux-hardware.org/?probe=1f6a3f87d7) | Sep 29, 2020 |
| Dell          | Inspiron 3521               | [e9482aee87](https://linux-hardware.org/?probe=e9482aee87) | Sep 28, 2020 |
| HP            | 250 G3                      | [c0207d3878](https://linux-hardware.org/?probe=c0207d3878) | Sep 24, 2020 |
| HP            | 250 G6 Notebook PC          | [71b1302861](https://linux-hardware.org/?probe=71b1302861) | Sep 24, 2020 |
| Dell          | Inspiron 1420               | [4b713d932f](https://linux-hardware.org/?probe=4b713d932f) | Sep 10, 2020 |
| Lenovo        | ThinkPad E580 20KS004GRK    | [0a7dbcc4b4](https://linux-hardware.org/?probe=0a7dbcc4b4) | Sep 09, 2020 |
| HP            | Pavilion 17                 | [994f18c32f](https://linux-hardware.org/?probe=994f18c32f) | Sep 09, 2020 |
| Acer          | Aspire ES1-523              | [e335200dd8](https://linux-hardware.org/?probe=e335200dd8) | Sep 04, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [9968af0598](https://linux-hardware.org/?probe=9968af0598) | Aug 25, 2020 |
| ASUSTek       | 1001HA                      | [7935f0bc4a](https://linux-hardware.org/?probe=7935f0bc4a) | Aug 23, 2020 |
| MSI           | Prestige 14 A10SC           | [b6c1db4e4f](https://linux-hardware.org/?probe=b6c1db4e4f) | Aug 23, 2020 |
| MSI           | Prestige 14 A10SC           | [5b434b68bf](https://linux-hardware.org/?probe=5b434b68bf) | Aug 23, 2020 |
| Lenovo        | G580 20157                  | [db44f2aca3](https://linux-hardware.org/?probe=db44f2aca3) | Aug 22, 2020 |
| Packard Be... | EasyNote TE11HC             | [81c427fc6a](https://linux-hardware.org/?probe=81c427fc6a) | Aug 09, 2020 |
| Dell          | Latitude E6440              | [a023894374](https://linux-hardware.org/?probe=a023894374) | Aug 01, 2020 |
| MSI           | Prestige 14 A10SC           | [790a29d708](https://linux-hardware.org/?probe=790a29d708) | Jul 28, 2020 |
| HP            | ProBook 450 G7              | [10566660a8](https://linux-hardware.org/?probe=10566660a8) | Jul 17, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b762726155](https://linux-hardware.org/?probe=b762726155) | Jul 08, 2020 |
| Dell          | Inspiron 5567               | [812155ca3b](https://linux-hardware.org/?probe=812155ca3b) | Jun 29, 2020 |
| Acer          | Aspire A315-51              | [61c053a60a](https://linux-hardware.org/?probe=61c053a60a) | May 31, 2020 |
| Acer          | Aspire A315-51              | [b524806f7a](https://linux-hardware.org/?probe=b524806f7a) | May 31, 2020 |
| Acer          | Aspire A315-51              | [1509883885](https://linux-hardware.org/?probe=1509883885) | May 31, 2020 |
| Acer          | Aspire A315-51              | [5d042bc26a](https://linux-hardware.org/?probe=5d042bc26a) | May 31, 2020 |
| Acer          | Aspire A315-51              | [5c70b2f02d](https://linux-hardware.org/?probe=5c70b2f02d) | May 31, 2020 |
| Dell          | Inspiron N5110              | [d2c4164b1c](https://linux-hardware.org/?probe=d2c4164b1c) | May 24, 2020 |
| HP            | Pavilion g6                 | [470074b671](https://linux-hardware.org/?probe=470074b671) | May 14, 2020 |
| Acer          | TravelMate 5742G            | [3b5409d855](https://linux-hardware.org/?probe=3b5409d855) | May 08, 2020 |
| HP            | Pavilion g6                 | [c2f0ff23ad](https://linux-hardware.org/?probe=c2f0ff23ad) | May 02, 2020 |
| ASUSTek       | U47A                        | [3b85d1aeb4](https://linux-hardware.org/?probe=3b85d1aeb4) | Apr 20, 2020 |
| HP            | Compaq 6510b (GB867EA#AC... | [ebb74b0be7](https://linux-hardware.org/?probe=ebb74b0be7) | Apr 06, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | [b44935169f](https://linux-hardware.org/?probe=b44935169f) | Mar 31, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5505        | [57ade58668](https://linux-hardware.org/?probe=57ade58668) | Mar 22, 2020 |
| Lenovo        | V330-14IKB 81B0             | [7ad6b7b58b](https://linux-hardware.org/?probe=7ad6b7b58b) | Mar 22, 2020 |
| HP            | Laptop 15-da0xxx            | [d2ab3b608a](https://linux-hardware.org/?probe=d2ab3b608a) | Mar 07, 2020 |
| HP            | Laptop 15-bs0xx             | [c219a39d00](https://linux-hardware.org/?probe=c219a39d00) | Mar 05, 2020 |
| HP            | Laptop 15-bs0xx             | [6f409ce91c](https://linux-hardware.org/?probe=6f409ce91c) | Mar 05, 2020 |
| Dell          | Inspiron 5770               | [fd882c0a0a](https://linux-hardware.org/?probe=fd882c0a0a) | Mar 04, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [dc2a796221](https://linux-hardware.org/?probe=dc2a796221) | Mar 01, 2020 |
| HP            | Presario CQ57               | [3de9f386b3](https://linux-hardware.org/?probe=3de9f386b3) | Feb 19, 2020 |
| Acer          | Aspire V5-572P              | [e87893d9ae](https://linux-hardware.org/?probe=e87893d9ae) | Feb 17, 2020 |
| HP            | ProBook 430 G5              | [1a22c7e1bd](https://linux-hardware.org/?probe=1a22c7e1bd) | Feb 16, 2020 |
| HP            | Presario CQ57               | [e89b7e8846](https://linux-hardware.org/?probe=e89b7e8846) | Feb 14, 2020 |
| Acer          | Aspire XXXX                 | [ce7f974b21](https://linux-hardware.org/?probe=ce7f974b21) | Feb 11, 2020 |
| Packard Be... | EasyNote TE11HC             | [fc9249082d](https://linux-hardware.org/?probe=fc9249082d) | Feb 08, 2020 |
| HP            | Laptop 15-bw0xx             | [52e1f3b9aa](https://linux-hardware.org/?probe=52e1f3b9aa) | Feb 07, 2020 |
| HP            | Compaq nx6310 (EY512ES#A... | [7131bc7839](https://linux-hardware.org/?probe=7131bc7839) | Jan 29, 2020 |
| Fujitsu       | LIFEBOOK AH531              | [d48f36b5c1](https://linux-hardware.org/?probe=d48f36b5c1) | Jan 28, 2020 |
| HP            | Mini 110-3500               | [70d6715873](https://linux-hardware.org/?probe=70d6715873) | Jan 28, 2020 |
| HP            | Compaq nx6310 (EY512ES#A... | [5aa6704ff1](https://linux-hardware.org/?probe=5aa6704ff1) | Jan 16, 2020 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | [76fd2a40e6](https://linux-hardware.org/?probe=76fd2a40e6) | Jan 10, 2020 |
| ASUSTek       | G46VW                       | [17b6106770](https://linux-hardware.org/?probe=17b6106770) | Dec 27, 2019 |
| ASUSTek       | G46VW                       | [d589eb2b88](https://linux-hardware.org/?probe=d589eb2b88) | Dec 27, 2019 |
| Dell          | Inspiron 3521               | [a0554a7e66](https://linux-hardware.org/?probe=a0554a7e66) | Dec 25, 2019 |
| HP            | Pavilion g6                 | [2b1a415af5](https://linux-hardware.org/?probe=2b1a415af5) | Dec 12, 2019 |
| Lenovo        | V580c 20160                 | [a90c5bff19](https://linux-hardware.org/?probe=a90c5bff19) | Dec 11, 2019 |
| Acer          | Aspire A517-51G             | [73dafbb15e](https://linux-hardware.org/?probe=73dafbb15e) | Nov 25, 2019 |
| Acer          | Aspire A517-51G             | [73d25e486f](https://linux-hardware.org/?probe=73d25e486f) | Nov 25, 2019 |
| Lenovo        | G505s 20255                 | [f50938f6b5](https://linux-hardware.org/?probe=f50938f6b5) | Nov 24, 2019 |
| Dell          | Latitude 7280               | [d18e59c26a](https://linux-hardware.org/?probe=d18e59c26a) | Nov 23, 2019 |
| Dell          | Latitude 7280               | [53190bc040](https://linux-hardware.org/?probe=53190bc040) | Nov 23, 2019 |
| Lenovo        | G505s 20255                 | [d93b73ac97](https://linux-hardware.org/?probe=d93b73ac97) | Nov 22, 2019 |
| Acer          | TravelMate 7750G            | [51f6c04c3c](https://linux-hardware.org/?probe=51f6c04c3c) | Oct 30, 2019 |
| Sony          | VPCEH2M1R                   | [7f2ba2a282](https://linux-hardware.org/?probe=7f2ba2a282) | Oct 22, 2019 |
| HP            | Presario CQ57               | [fee13f8ed2](https://linux-hardware.org/?probe=fee13f8ed2) | Oct 08, 2019 |
| Fujitsu       | LIFEBOOK AH531              | [0aea361308](https://linux-hardware.org/?probe=0aea361308) | Sep 09, 2019 |
| Fujitsu       | LIFEBOOK AH531              | [65b6a535e2](https://linux-hardware.org/?probe=65b6a535e2) | Sep 09, 2019 |
| ASUSTek       | X540SA                      | [90108d8974](https://linux-hardware.org/?probe=90108d8974) | Sep 08, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [60161c7891](https://linux-hardware.org/?probe=60161c7891) | Aug 28, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [e79b69efe5](https://linux-hardware.org/?probe=e79b69efe5) | Aug 20, 2019 |
| ASUSTek       | X541SC                      | [6458c4f07b](https://linux-hardware.org/?probe=6458c4f07b) | Jul 22, 2019 |
| HP            | Compaq nc6320 (ES479EA#A... | [cf41ab5f1a](https://linux-hardware.org/?probe=cf41ab5f1a) | Jul 15, 2019 |
| Acer          | Aspire E5-575G              | [e4b342382f](https://linux-hardware.org/?probe=e4b342382f) | Jul 06, 2019 |
| Lenovo        | G500 20236                  | [166081ce08](https://linux-hardware.org/?probe=166081ce08) | Jul 04, 2019 |
| Acer          | Aspire E5-575G              | [0446579039](https://linux-hardware.org/?probe=0446579039) | Jun 26, 2019 |
| Dell          | Inspiron 3521               | [03073baad2](https://linux-hardware.org/?probe=03073baad2) | Jun 21, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [13304c8b21](https://linux-hardware.org/?probe=13304c8b21) | Jun 20, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [78913150c4](https://linux-hardware.org/?probe=78913150c4) | Jun 20, 2019 |
| ASUSTek       | X541SC                      | [021030c4a5](https://linux-hardware.org/?probe=021030c4a5) | May 26, 2019 |
| HP            | Pavilion dv6                | [7a702bbcca](https://linux-hardware.org/?probe=7a702bbcca) | May 18, 2019 |
| Acer          | Aspire E5-575G              | [933bd023a3](https://linux-hardware.org/?probe=933bd023a3) | May 07, 2019 |
| ASUSTek       | X550CA                      | [bee231aa07](https://linux-hardware.org/?probe=bee231aa07) | May 07, 2019 |
| Lenovo        | G500 20236                  | [780fb49d18](https://linux-hardware.org/?probe=780fb49d18) | May 04, 2019 |
| ASUSTek       | X102BA                      | [a7f7276e3d](https://linux-hardware.org/?probe=a7f7276e3d) | May 02, 2019 |
| Dell          | Inspiron 3521               | [d8da30496e](https://linux-hardware.org/?probe=d8da30496e) | May 01, 2019 |
| Dell          | Inspiron 3521               | [4030941deb](https://linux-hardware.org/?probe=4030941deb) | Apr 29, 2019 |
| ASUSTek       | X751LN                      | [9cf06d20fa](https://linux-hardware.org/?probe=9cf06d20fa) | Apr 24, 2019 |
| ASUSTek       | X541SC                      | [0837a78e1f](https://linux-hardware.org/?probe=0837a78e1f) | Apr 24, 2019 |
| Dell          | Inspiron 3521               | [5c7abc670f](https://linux-hardware.org/?probe=5c7abc670f) | Apr 22, 2019 |
| ASUSTek       | X751LN                      | [5ca452f41e](https://linux-hardware.org/?probe=5ca452f41e) | Apr 22, 2019 |
| HP            | ProBook 470 G4              | [5e83946400](https://linux-hardware.org/?probe=5e83946400) | Apr 12, 2019 |
| Fujitsu Si... | AMILO Li 1818               | [9a3017958a](https://linux-hardware.org/?probe=9a3017958a) | Apr 03, 2019 |
| Toshiba       | Satellite P105              | [fed8975477](https://linux-hardware.org/?probe=fed8975477) | Mar 04, 2019 |
| Lenovo        | IdeaPad Z500 20202          | [f100f0f205](https://linux-hardware.org/?probe=f100f0f205) | Feb 24, 2019 |
| Toshiba       | Satellite C660              | [6badaf723c](https://linux-hardware.org/?probe=6badaf723c) | Jan 20, 2019 |
| Toshiba       | Satellite C660              | [aa10ea857e](https://linux-hardware.org/?probe=aa10ea857e) | Jan 15, 2019 |
| ASUSTek       | K50IE                       | [82bb70f126](https://linux-hardware.org/?probe=82bb70f126) | Jan 02, 2019 |
| HP            | Pavilion g6                 | [dfee480fdd](https://linux-hardware.org/?probe=dfee480fdd) | Jan 01, 2019 |
| HP            | Pavilion g6                 | [00e7757462](https://linux-hardware.org/?probe=00e7757462) | Jan 01, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [88c4e3862d](https://linux-hardware.org/?probe=88c4e3862d) | Dec 27, 2018 |
| Acer          | Aspire E5-575G              | [7d028bb762](https://linux-hardware.org/?probe=7d028bb762) | Dec 25, 2018 |
| Acer          | Aspire E5-575G              | [14806ac400](https://linux-hardware.org/?probe=14806ac400) | Dec 14, 2018 |
| Packard Be... | DOT S                       | [a0fe87d229](https://linux-hardware.org/?probe=a0fe87d229) | Nov 24, 2018 |
| Packard Be... | DOT S                       | [6267c7c58d](https://linux-hardware.org/?probe=6267c7c58d) | Nov 24, 2018 |
| ASUSTek       | X540SA                      | [9f31b05c88](https://linux-hardware.org/?probe=9f31b05c88) | Nov 23, 2018 |
| Lenovo        | Yoga 300-11IBR 80M1         | [d07d21914f](https://linux-hardware.org/?probe=d07d21914f) | Oct 27, 2018 |
| ASUSTek       | U47A                        | [0d064a18d0](https://linux-hardware.org/?probe=0d064a18d0) | Oct 24, 2018 |
| ASUSTek       | U47A                        | [5171edd107](https://linux-hardware.org/?probe=5171edd107) | Oct 24, 2018 |
| HP            | EliteBook 6930p             | [3a9c8124dd](https://linux-hardware.org/?probe=3a9c8124dd) | Oct 23, 2018 |
| HP            | EliteBook 8530p             | [51ba7cee66](https://linux-hardware.org/?probe=51ba7cee66) | Oct 17, 2018 |
| HP            | Pavilion g6                 | [ffb346f134](https://linux-hardware.org/?probe=ffb346f134) | Sep 24, 2018 |
| HP            | Pavilion dv6                | [884d5eb5ec](https://linux-hardware.org/?probe=884d5eb5ec) | Sep 16, 2018 |
| HP            | Pavilion dv6                | [622662ba7d](https://linux-hardware.org/?probe=622662ba7d) | Sep 14, 2018 |
| Unknown       | Unknown                     | [f45f9ee7ff](https://linux-hardware.org/?probe=f45f9ee7ff) | Sep 05, 2018 |
| Unknown       | Unknown                     | [07345cdc85](https://linux-hardware.org/?probe=07345cdc85) | Aug 29, 2018 |
| Lenovo        | B50-70 20384                | [b89c577552](https://linux-hardware.org/?probe=b89c577552) | Aug 26, 2018 |
| HP            | ProBook 450 G5              | [8252f20153](https://linux-hardware.org/?probe=8252f20153) | Aug 18, 2018 |
| Dell          | Inspiron 3520               | [84a1a01ff9](https://linux-hardware.org/?probe=84a1a01ff9) | Aug 12, 2018 |
| Lenovo        | G580 20157                  | [b70545cbac](https://linux-hardware.org/?probe=b70545cbac) | Aug 02, 2018 |
| Toshiba       | Portable PC                 | [3f35fe94d9](https://linux-hardware.org/?probe=3f35fe94d9) | Jul 30, 2018 |
| Lenovo        | G510 20238                  | [71278987a9](https://linux-hardware.org/?probe=71278987a9) | Jul 20, 2018 |
| HP            | Compaq CQ58                 | [19369b35ae](https://linux-hardware.org/?probe=19369b35ae) | Jul 20, 2018 |
| Lenovo        | Y50-70 20378                | [62a23cd320](https://linux-hardware.org/?probe=62a23cd320) | Jul 11, 2018 |
| HP            | Compaq CQ58                 | [99fa20eba0](https://linux-hardware.org/?probe=99fa20eba0) | Jun 21, 2018 |
| Lenovo        | G580 20157                  | [a202b59883](https://linux-hardware.org/?probe=a202b59883) | Jun 19, 2018 |
| HP            | Compaq CQ58                 | [cb1791cebb](https://linux-hardware.org/?probe=cb1791cebb) | Jun 16, 2018 |
| Sony          | VPCEB1E1R                   | [a75927fc48](https://linux-hardware.org/?probe=a75927fc48) | Jun 03, 2018 |
| Sony          | VPCEB1E1R                   | [37813189cc](https://linux-hardware.org/?probe=37813189cc) | Jun 02, 2018 |
| Sony          | VPCEB1E1R                   | [408dcf71ce](https://linux-hardware.org/?probe=408dcf71ce) | May 25, 2018 |
| Lenovo        | B50-70 20384                | [c35dc55ced](https://linux-hardware.org/?probe=c35dc55ced) | May 22, 2018 |
| Samsung       | R518                        | [0e9bb77f12](https://linux-hardware.org/?probe=0e9bb77f12) | May 17, 2018 |
| Acer          | TravelMate 7750G            | [0d5442243c](https://linux-hardware.org/?probe=0d5442243c) | Apr 13, 2018 |
| HP            | EliteBook 2560p             | [2674660d30](https://linux-hardware.org/?probe=2674660d30) | Mar 18, 2018 |
| Acer          | Predator G3-572             | [c888fc259c](https://linux-hardware.org/?probe=c888fc259c) | Feb 28, 2018 |
| Acer          | Aspire E1-571G              | [ff7067b051](https://linux-hardware.org/?probe=ff7067b051) | Feb 24, 2018 |
| ASUSTek       | X550LA                      | [f416c6d195](https://linux-hardware.org/?probe=f416c6d195) | Feb 11, 2018 |
| Lenovo        | IdeaPad Y580                | [e648c1db32](https://linux-hardware.org/?probe=e648c1db32) | Feb 10, 2018 |
| Sony          | VGN-NW320F                  | [5b4a5cecc3](https://linux-hardware.org/?probe=5b4a5cecc3) | Jan 24, 2018 |
| Sony          | VGN-NW320F                  | [8d00903b16](https://linux-hardware.org/?probe=8d00903b16) | Jan 24, 2018 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [d9f6c2c974](https://linux-hardware.org/?probe=d9f6c2c974) | Jan 21, 2018 |
| HP            | EliteBook 8440p             | [0358601780](https://linux-hardware.org/?probe=0358601780) | Jan 18, 2018 |
| Lenovo        | V580c 20160                 | [4bc6c74b55](https://linux-hardware.org/?probe=4bc6c74b55) | Jan 13, 2018 |
| Acer          | Aspire E1-571G              | [b60cd6ffc3](https://linux-hardware.org/?probe=b60cd6ffc3) | Jan 12, 2018 |
| Dell          | Inspiron M5110              | [bbf43310e5](https://linux-hardware.org/?probe=bbf43310e5) | Jan 05, 2018 |
| Lenovo        | G510 20238                  | [e84d800dfe](https://linux-hardware.org/?probe=e84d800dfe) | Jan 03, 2018 |
| Lenovo        | G510 20238                  | [b322595c10](https://linux-hardware.org/?probe=b322595c10) | Jan 03, 2018 |
| Lenovo        | B590 20208                  | [519ce95e23](https://linux-hardware.org/?probe=519ce95e23) | Dec 27, 2017 |
| ASUSTek       | K52Jc                       | [ae0972b81d](https://linux-hardware.org/?probe=ae0972b81d) | Dec 27, 2017 |
| Lenovo        | V580c 20160                 | [973d383d71](https://linux-hardware.org/?probe=973d383d71) | Dec 27, 2017 |
| ASUSTek       | K52Jc                       | [ee5e52dede](https://linux-hardware.org/?probe=ee5e52dede) | Dec 26, 2017 |
| Dell          | Inspiron N5110              | [2045f82e75](https://linux-hardware.org/?probe=2045f82e75) | Dec 24, 2017 |
| Lenovo        | V580c 20160                 | [8b68d694a7](https://linux-hardware.org/?probe=8b68d694a7) | Dec 21, 2017 |
| HP            | ProBook 4720s               | [ab0b647716](https://linux-hardware.org/?probe=ab0b647716) | Dec 09, 2017 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [f2eec3b185](https://linux-hardware.org/?probe=f2eec3b185) | Dec 03, 2017 |
| ASUSTek       | X51RL                       | [701211da24](https://linux-hardware.org/?probe=701211da24) | Dec 02, 2017 |
| Dell          | Inspiron M5110              | [ee88f09ebb](https://linux-hardware.org/?probe=ee88f09ebb) | Nov 30, 2017 |
| Acer          | Aspire 5750G                | [9d18d205df](https://linux-hardware.org/?probe=9d18d205df) | Nov 11, 2017 |
| ASUSTek       | X58L                        | [de2da19087](https://linux-hardware.org/?probe=de2da19087) | Oct 20, 2017 |
| ASUSTek       | K55VD                       | [295b4e18de](https://linux-hardware.org/?probe=295b4e18de) | Sep 24, 2017 |
| Dell          | Inspiron N5050              | [072cf329f6](https://linux-hardware.org/?probe=072cf329f6) | Sep 22, 2017 |
| HP            | Pavilion 17                 | [5226a4b68c](https://linux-hardware.org/?probe=5226a4b68c) | Sep 12, 2017 |
| Dell          | Inspiron 3558               | [a10105f81f](https://linux-hardware.org/?probe=a10105f81f) | Sep 12, 2017 |
| ASUSTek       | K52JV                       | [786ab76c2d](https://linux-hardware.org/?probe=786ab76c2d) | Aug 09, 2017 |
| Sony          | VPCCB2S1R                   | [b5723ad5f5](https://linux-hardware.org/?probe=b5723ad5f5) | Aug 08, 2017 |
| Lenovo        | G580 20157                  | [a1a09287ab](https://linux-hardware.org/?probe=a1a09287ab) | Aug 06, 2017 |
| Lenovo        | IdeaPad Y580                | [258ed6aea6](https://linux-hardware.org/?probe=258ed6aea6) | Jul 27, 2017 |
| Lenovo        | IdeaPad Y580                | [493ba2eb0c](https://linux-hardware.org/?probe=493ba2eb0c) | Jul 27, 2017 |
| Lenovo        | G510 20238                  | [2613154d7e](https://linux-hardware.org/?probe=2613154d7e) | Jul 24, 2017 |
| eMachines     | E725                        | [05bce34fc0](https://linux-hardware.org/?probe=05bce34fc0) | Jul 23, 2017 |
| Acer          | Aspire V3-551G              | [92da3895dc](https://linux-hardware.org/?probe=92da3895dc) | Jul 18, 2017 |
| Dell          | Inspiron 5559               | [3753d1a422](https://linux-hardware.org/?probe=3753d1a422) | Jul 18, 2017 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [a62f8e0f39](https://linux-hardware.org/?probe=a62f8e0f39) | Jul 15, 2017 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [0a1ff9ae9c](https://linux-hardware.org/?probe=0a1ff9ae9c) | Jul 14, 2017 |
| Dell          | Inspiron 5759               | [40852e37a5](https://linux-hardware.org/?probe=40852e37a5) | Jul 12, 2017 |
| HP            | Pavilion dm3                | [008097ceb1](https://linux-hardware.org/?probe=008097ceb1) | May 30, 2017 |
| Dell          | Inspiron 3558               | [c7a96bfff1](https://linux-hardware.org/?probe=c7a96bfff1) | May 28, 2017 |
| Dell          | Inspiron 3558               | [11b4a60b6b](https://linux-hardware.org/?probe=11b4a60b6b) | May 28, 2017 |
| Lenovo        | G500 20236                  | [60a1eab059](https://linux-hardware.org/?probe=60a1eab059) | May 26, 2017 |
| HP            | Compaq 6710b (KE120EA#AC... | [278110b61f](https://linux-hardware.org/?probe=278110b61f) | May 22, 2017 |
| Fujitsu Si... | AMILO Pi 3540               | [e8829d83b4](https://linux-hardware.org/?probe=e8829d83b4) | May 05, 2017 |
| Fujitsu Si... | AMILO Pi 3540               | [dd2f72474b](https://linux-hardware.org/?probe=dd2f72474b) | May 02, 2017 |
| Acer          | Aspire E5-511G              | [0110e34364](https://linux-hardware.org/?probe=0110e34364) | May 01, 2017 |
| HP            | ENVY TS 17                  | [74e650e784](https://linux-hardware.org/?probe=74e650e784) | Apr 30, 2017 |
| Unknown       | Unknown                     | [f5351462b1](https://linux-hardware.org/?probe=f5351462b1) | Apr 28, 2017 |
| Dell          | Inspiron 5521               | [92a991bcec](https://linux-hardware.org/?probe=92a991bcec) | Apr 17, 2017 |
| Dell          | Inspiron 5521               | [534d340a7a](https://linux-hardware.org/?probe=534d340a7a) | Apr 17, 2017 |
| Dell          | Inspiron 5521               | [add5384359](https://linux-hardware.org/?probe=add5384359) | Apr 16, 2017 |
| Dell          | Inspiron M5110              | [331bda6305](https://linux-hardware.org/?probe=331bda6305) | Apr 01, 2017 |
| Dell          | Inspiron M5110              | [6d2fc341c7](https://linux-hardware.org/?probe=6d2fc341c7) | Apr 01, 2017 |
| ASUSTek       | N56DP                       | [c4a63674e5](https://linux-hardware.org/?probe=c4a63674e5) | Feb 18, 2017 |
| Fujitsu       | LIFEBOOK A530               | [a03d8130fe](https://linux-hardware.org/?probe=a03d8130fe) | Feb 06, 2017 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [c288b514d5](https://linux-hardware.org/?probe=c288b514d5) | Jan 22, 2017 |
| ASUSTek       | N53SM                       | [26849207d6](https://linux-hardware.org/?probe=26849207d6) | Jan 19, 2017 |
| Dell          | Inspiron 7720               | [7dff83e247](https://linux-hardware.org/?probe=7dff83e247) | Jan 04, 2017 |
| Lenovo        | ThinkPad Edge E530 3259C... | [58cb3c3ef1](https://linux-hardware.org/?probe=58cb3c3ef1) | Dec 23, 2016 |
| Lenovo        | ThinkPad Edge E530 3259C... | [8af0bb111e](https://linux-hardware.org/?probe=8af0bb111e) | Dec 20, 2016 |
| Lenovo        | G565 20071                  | [e6972d050f](https://linux-hardware.org/?probe=e6972d050f) | Dec 16, 2016 |
| Toshiba       | TECRA M5                    | [b4743ce437](https://linux-hardware.org/?probe=b4743ce437) | Dec 12, 2016 |
| Packard Be... | DOT S                       | [815f65352b](https://linux-hardware.org/?probe=815f65352b) | Dec 01, 2016 |
| Toshiba       | Satellite C650              | [06c50a161c](https://linux-hardware.org/?probe=06c50a161c) | Nov 29, 2016 |
| ASUSTek       | 1225C                       | [57787e36c2](https://linux-hardware.org/?probe=57787e36c2) | Nov 28, 2016 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [1ed00b7813](https://linux-hardware.org/?probe=1ed00b7813) | Nov 27, 2016 |
| Samsung       | 350V5C/350V5X/350V4C/350... | [45b5c7374e](https://linux-hardware.org/?probe=45b5c7374e) | Nov 27, 2016 |
| Lenovo        | ThinkPad X201 3626MJ5       | [e13b0d2ee7](https://linux-hardware.org/?probe=e13b0d2ee7) | Nov 25, 2016 |
| HP            | 530                         | [b4ade385fd](https://linux-hardware.org/?probe=b4ade385fd) | Nov 24, 2016 |
| Toshiba       | Satellite 5200              | [a79789524b](https://linux-hardware.org/?probe=a79789524b) | Nov 02, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| ROSA R11            | 27        | 9.54%   |
| ROSA R10            | 25        | 8.83%   |
| ROSA R8.1           | 24        | 8.48%   |
| ROSA R9             | 16        | 5.65%   |
| Ubuntu 20.04        | 14        | 4.95%   |
| ROSA R8             | 14        | 4.95%   |
| Ubuntu 22.04        | 11        | 3.89%   |
| KDE neon 20.04      | 9         | 3.18%   |
| Debian 11           | 8         | 2.83%   |
| Ubuntu 18.04        | 7         | 2.47%   |
| ROSA R11.1          | 7         | 2.47%   |
| Arch Rolling        | 6         | 2.12%   |
| OpenMandriva 4.2    | 5         | 1.77%   |
| ROSA 12.4           | 4         | 1.41%   |
| Slackware 15.0      | 3         | 1.06%   |
| ROSA 12.3           | 3         | 1.06%   |
| ROSA 12.2           | 3         | 1.06%   |
| Fedora 37           | 3         | 1.06%   |
| Fedora 36           | 3         | 1.06%   |
| Arch                | 3         | 1.06%   |
| Ubuntu 22.10        | 2         | 0.71%   |
| Ubuntu 18.10        | 2         | 0.71%   |
| Pop!_OS 22.04       | 2         | 0.71%   |
| Manjaro 22.0.0      | 2         | 0.71%   |
| Linux Mint 21.1     | 2         | 0.71%   |
| Linux Mint 20.3     | 2         | 0.71%   |
| Linux Mint 20.1     | 2         | 0.71%   |
| Kubuntu 22.10       | 2         | 0.71%   |
| KDE neon 18.04      | 2         | 0.71%   |
| Fedora 35           | 2         | 0.71%   |
| Fedora 34           | 2         | 0.71%   |
| EndeavourOS Rolling | 2         | 0.71%   |
| Debian 10           | 2         | 0.71%   |
| Zorin 15            | 1         | 0.35%   |
| Xubuntu 18.04       | 1         | 0.35%   |
| Ubuntu Unity 20.04  | 1         | 0.35%   |
| Ubuntu Unity 16.04  | 1         | 0.35%   |
| Ubuntu 23.04        | 1         | 0.35%   |
| Ubuntu 21.04        | 1         | 0.35%   |
| Ubuntu 20.10        | 1         | 0.35%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| ROSA         | 114       | 42.38%  |
| Ubuntu       | 40        | 14.87%  |
| Endless      | 18        | 6.69%   |
| KDE neon     | 12        | 4.46%   |
| Fedora       | 12        | 4.46%   |
| Debian       | 10        | 3.72%   |
| Manjaro      | 9         | 3.35%   |
| OpenMandriva | 8         | 2.97%   |
| Arch         | 7         | 2.6%    |
| Linux Mint   | 6         | 2.23%   |
| Kubuntu      | 5         | 1.86%   |
| Pop!_OS      | 4         | 1.49%   |
| Slackware    | 3         | 1.12%   |
| Elementary   | 3         | 1.12%   |
| CentOS       | 3         | 1.12%   |
| Ubuntu Unity | 2         | 0.74%   |
| EndeavourOS  | 2         | 0.74%   |
| Zorin        | 1         | 0.37%   |
| Xubuntu      | 1         | 0.37%   |
| Rocky Linux  | 1         | 0.37%   |
| Peppermint   | 1         | 0.37%   |
| openSUSE     | 1         | 0.37%   |
| LMDE         | 1         | 0.37%   |
| Gentoo       | 1         | 0.37%   |
| Finnix       | 1         | 0.37%   |
| Ctlos        | 1         | 0.37%   |
| Clear Linux  | 1         | 0.37%   |
| antiX        | 1         | 0.37%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| 4.15.0-desktop-45.1rosa-x86_64      | 17        | 5.63%   |
| 4.9.60-nrj-desktop-1rosa-x86_64     | 16        | 5.3%    |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 15        | 4.97%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 7         | 2.32%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 6         | 1.99%   |
| 5.10.14-desktop-1omv4002            | 5         | 1.66%   |
| 4.1.38-nrj-desktop-2rosa-x86_64     | 5         | 1.66%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 5         | 1.66%   |
| 5.10.0-8-amd64                      | 4         | 1.32%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 4         | 1.32%   |
| 4.9.9-nrj-desktop-1rosa-x86_64      | 4         | 1.32%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 4         | 1.32%   |
| 4.9.20-nrj-desktop-1rosa-i586       | 4         | 1.32%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 4         | 1.32%   |
| 5.11.0-35-generic                   | 3         | 0.99%   |
| 4.9.9-nrj-desktop-1rosa-i586        | 3         | 0.99%   |
| 4.9.111-nrj-desktop-2rosa-x86_64    | 3         | 0.99%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 3         | 0.99%   |
| 6.1.20-generic-2rosa2021.1-x86_64   | 2         | 0.66%   |
| 5.8.0-44-generic                    | 2         | 0.66%   |
| 5.8.0-14-generic                    | 2         | 0.66%   |
| 5.4.83-generic-2rosa-x86_64         | 2         | 0.66%   |
| 5.4.32-generic-2rosa-x86_64         | 2         | 0.66%   |
| 5.4.0-42-generic                    | 2         | 0.66%   |
| 5.4.0-39-generic                    | 2         | 0.66%   |
| 5.19.0-35-generic                   | 2         | 0.66%   |
| 5.19.0-23-generic                   | 2         | 0.66%   |
| 5.15.19                             | 2         | 0.66%   |
| 5.15.0-73-generic                   | 2         | 0.66%   |
| 5.15.0-56-generic                   | 2         | 0.66%   |
| 5.15.0-43-generic                   | 2         | 0.66%   |
| 5.11.0-34-generic                   | 2         | 0.66%   |
| 5.10.155-generic-1rosa2021.1-x86_64 | 2         | 0.66%   |
| 5.10.0-21-amd64                     | 2         | 0.66%   |
| 5.0.0-37-generic                    | 2         | 0.66%   |
| 4.9.34-nrj-desktop-1rosa-x86_64     | 2         | 0.66%   |
| 4.16.0-4-generic                    | 2         | 0.66%   |
| 4.15.0-desktop-45.1rosa-i586        | 2         | 0.66%   |
| 6.3.7-200.fc38.x86_64               | 1         | 0.33%   |
| 6.3.0-x64v1-xanmod1-2               | 1         | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 4.15.0   | 29        | 9.7%    |
| 4.9.20   | 19        | 6.35%   |
| 5.4.0    | 18        | 6.02%   |
| 4.9.60   | 17        | 5.69%   |
| 4.1.34   | 12        | 4.01%   |
| 5.15.0   | 11        | 3.68%   |
| 5.11.0   | 11        | 3.68%   |
| 5.10.0   | 9         | 3.01%   |
| 5.3.0    | 7         | 2.34%   |
| 5.19.0   | 7         | 2.34%   |
| 5.0.0    | 7         | 2.34%   |
| 4.9.9    | 6         | 2.01%   |
| 4.9.124  | 6         | 2.01%   |
| 4.1.38   | 6         | 2.01%   |
| 5.8.0    | 5         | 1.67%   |
| 5.10.14  | 5         | 1.67%   |
| 4.9.155  | 5         | 1.67%   |
| 4.18.0   | 5         | 1.67%   |
| 4.9.95   | 4         | 1.34%   |
| 4.9.41   | 4         | 1.34%   |
| 4.9.111  | 4         | 1.34%   |
| 5.4.32   | 3         | 1%      |
| 5.13.0   | 3         | 1%      |
| 4.19.0   | 3         | 1%      |
| 4.13.0   | 3         | 1%      |
| 6.3.0    | 2         | 0.67%   |
| 6.2.6    | 2         | 0.67%   |
| 6.1.20   | 2         | 0.67%   |
| 6.1.0    | 2         | 0.67%   |
| 6.0.10   | 2         | 0.67%   |
| 5.4.83   | 2         | 0.67%   |
| 5.16.7   | 2         | 0.67%   |
| 5.15.78  | 2         | 0.67%   |
| 5.15.19  | 2         | 0.67%   |
| 5.14.0   | 2         | 0.67%   |
| 5.10.155 | 2         | 0.67%   |
| 4.9.34   | 2         | 0.67%   |
| 4.16.0   | 2         | 0.67%   |
| 6.3.7    | 1         | 0.33%   |
| 6.2.8    | 1         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.9     | 58        | 20.49%  |
| 4.15    | 29        | 10.25%  |
| 5.4     | 26        | 9.19%   |
| 5.15    | 20        | 7.07%   |
| 5.10    | 20        | 7.07%   |
| 4.1     | 19        | 6.71%   |
| 5.11    | 11        | 3.89%   |
| 6.1     | 10        | 3.53%   |
| 5.19    | 10        | 3.53%   |
| 5.8     | 9         | 3.18%   |
| 5.3     | 7         | 2.47%   |
| 5.0     | 7         | 2.47%   |
| 4.18    | 6         | 2.12%   |
| 6.2     | 5         | 1.77%   |
| 5.17    | 4         | 1.41%   |
| 5.14    | 4         | 1.41%   |
| 5.13    | 4         | 1.41%   |
| 4.19    | 4         | 1.41%   |
| 6.3     | 3         | 1.06%   |
| 5.9     | 3         | 1.06%   |
| 5.16    | 3         | 1.06%   |
| 4.13    | 3         | 1.06%   |
| 6.0     | 2         | 0.71%   |
| 5.6     | 2         | 0.71%   |
| 5.18    | 2         | 0.71%   |
| 5.12    | 2         | 0.71%   |
| 4.16    | 2         | 0.71%   |
| 5.7     | 1         | 0.35%   |
| 5.1     | 1         | 0.35%   |
| 4.4     | 1         | 0.35%   |
| 4.20    | 1         | 0.35%   |
| 3.14    | 1         | 0.35%   |
| 3.10    | 1         | 0.35%   |
| 2.6     | 1         | 0.35%   |
| Unknown | 1         | 0.35%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 239       | 90.53%  |
| i686    | 24        | 9.09%   |
| Unknown | 1         | 0.38%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| KDE4            | 87        | 31.07%  |
| GNOME           | 75        | 26.79%  |
| KDE5            | 54        | 19.29%  |
| Unknown         | 19        | 6.79%   |
| KDE             | 12        | 4.29%   |
| XFCE            | 10        | 3.57%   |
| X-Cinnamon      | 6         | 2.14%   |
| LXQt            | 4         | 1.43%   |
| Unity           | 2         | 0.71%   |
| Pantheon        | 2         | 0.71%   |
| i3              | 2         | 0.71%   |
| sway            | 1         | 0.36%   |
| Openbox         | 1         | 0.36%   |
| MATE            | 1         | 0.36%   |
| LXDE            | 1         | 0.36%   |
| GNOME Flashback | 1         | 0.36%   |
| Cinnamon        | 1         | 0.36%   |
| awesome         | 1         | 0.36%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 222       | 82.22%  |
| Wayland | 37        | 13.7%   |
| Unknown | 8         | 2.96%   |
| Tty     | 3         | 1.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| KDM     | 87        | 31.41%  |
| Unknown | 73        | 26.35%  |
| SDDM    | 55        | 19.86%  |
| GDM     | 28        | 10.11%  |
| GDM3    | 17        | 6.14%   |
| LightDM | 11        | 3.97%   |
| TDM     | 4         | 1.44%   |
| XDM     | 1         | 0.36%   |
| SLiM    | 1         | 0.36%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| Unknown     | 117       | 43.17%  |
| ru_RU       | 79        | 29.15%  |
| en_US       | 62        | 22.88%  |
| C           | 5         | 1.85%   |
| ru_RU.UTF_8 | 4         | 1.48%   |
| en_GB       | 2         | 0.74%   |
| en_IN       | 1         | 0.37%   |
| en_IL       | 1         | 0.37%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 138       | 50.36%  |
| BIOS | 136       | 49.64%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 170       | 62.04%  |
| Unknown | 74        | 27.01%  |
| Btrfs   | 15        | 5.47%   |
| Overlay | 13        | 4.74%   |
| Xfs     | 2         | 0.73%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 102       | 37.09%  |
| GPT     | 94        | 34.18%  |
| MBR     | 79        | 28.73%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 241       | 88.28%  |
| Yes       | 32        | 11.72%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 200       | 73.26%  |
| Yes       | 73        | 26.74%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 59        | 22.43%  |
| Lenovo              | 57        | 21.67%  |
| ASUSTek Computer    | 45        | 17.11%  |
| Acer                | 37        | 14.07%  |
| Dell                | 24        | 9.13%   |
| Toshiba             | 7         | 2.66%   |
| Sony                | 7         | 2.66%   |
| Fujitsu             | 5         | 1.9%    |
| Unknown             | 4         | 1.52%   |
| Samsung Electronics | 3         | 1.14%   |
| Packard Bell        | 3         | 1.14%   |
| Fujitsu Siemens     | 3         | 1.14%   |
| Chuwi               | 2         | 0.76%   |
| MSI                 | 1         | 0.38%   |
| IBM                 | 1         | 0.38%   |
| HUAWEI              | 1         | 0.38%   |
| HONOR               | 1         | 0.38%   |
| GPD                 | 1         | 0.38%   |
| eMachines           | 1         | 0.38%   |
| Elenberg            | 1         | 0.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Lenovo G500 20236                        | 6         | 2.28%   |
| HP Pavilion g6                           | 5         | 1.9%    |
| Acer Aspire E5-575G                      | 4         | 1.52%   |
| Unknown                                  | 4         | 1.52%   |
| Lenovo G510 20238                        | 3         | 1.14%   |
| Fujitsu LIFEBOOK AH531                   | 3         | 1.14%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR     | 3         | 1.14%   |
| Packard Bell DOT S                       | 2         | 0.76%   |
| Lenovo ThinkPad Edge E530 3259CEG        | 2         | 0.76%   |
| Lenovo ThinkBook 15 G3 ACL 21A4          | 2         | 0.76%   |
| Lenovo ThinkBook 14 G2 ITL 20VD          | 2         | 0.76%   |
| Lenovo Legion Y540-15IRH-PG0 81SY        | 2         | 0.76%   |
| HP Presario CQ57                         | 2         | 0.76%   |
| HP Pavilion Gaming Laptop 15-cx0xxx      | 2         | 0.76%   |
| HP Pavilion dv6                          | 2         | 0.76%   |
| HP Compaq CQ58                           | 2         | 0.76%   |
| Dell Inspiron N5110                      | 2         | 0.76%   |
| ASUS X51RL                               | 2         | 0.76%   |
| ASUS VivoBook_ASUSLaptop K6500ZC_K6500ZC | 2         | 0.76%   |
| Acer Aspire V3-551G                      | 2         | 0.76%   |
| Acer Aspire ES1-523                      | 2         | 0.76%   |
| Acer Aspire A715-75G                     | 2         | 0.76%   |
| Acer Aspire A315-51                      | 2         | 0.76%   |
| Acer Aspire 5750G                        | 2         | 0.76%   |
| Toshiba TECRA S11                        | 1         | 0.38%   |
| Toshiba TECRA M5                         | 1         | 0.38%   |
| Toshiba Satellite P105                   | 1         | 0.38%   |
| Toshiba Satellite C660                   | 1         | 0.38%   |
| Toshiba Satellite C650                   | 1         | 0.38%   |
| Toshiba Satellite 5200                   | 1         | 0.38%   |
| Toshiba Portable PC                      | 1         | 0.38%   |
| Sony VPCEH2M1R                           | 1         | 0.38%   |
| Sony VPCEB1E1R                           | 1         | 0.38%   |
| Sony VPCEA3M1R                           | 1         | 0.38%   |
| Sony VPCCB2S1R                           | 1         | 0.38%   |
| Sony VGN-NW320F                          | 1         | 0.38%   |
| Sony VGN-NR430E                          | 1         | 0.38%   |
| Sony VGN-FW245J                          | 1         | 0.38%   |
| Samsung R518                             | 1         | 0.38%   |
| Samsung N100SP                           | 1         | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 24        | 9.13%   |
| ASUS VivoBook         | 18        | 6.84%   |
| HP Pavilion           | 16        | 6.08%   |
| Dell Inspiron         | 16        | 6.08%   |
| Lenovo IdeaPad        | 13        | 4.94%   |
| Lenovo ThinkPad       | 12        | 4.56%   |
| HP ProBook            | 11        | 4.18%   |
| HP Laptop             | 7         | 2.66%   |
| Lenovo G500           | 6         | 2.28%   |
| HP Compaq             | 6         | 2.28%   |
| Lenovo ThinkBook      | 5         | 1.9%    |
| Lenovo Legion         | 5         | 1.9%    |
| HP EliteBook          | 5         | 1.9%    |
| Fujitsu LIFEBOOK      | 5         | 1.9%    |
| Toshiba Satellite     | 4         | 1.52%   |
| Dell Latitude         | 4         | 1.52%   |
| Unknown               | 4         | 1.52%   |
| Lenovo G510           | 3         | 1.14%   |
| Acer Swift            | 3         | 1.14%   |
| Toshiba TECRA         | 2         | 0.76%   |
| Packard Bell DOT      | 2         | 0.76%   |
| HP Presario           | 2         | 0.76%   |
| HP ENVY               | 2         | 0.76%   |
| HP 250                | 2         | 0.76%   |
| Fujitsu Siemens AMILO | 2         | 0.76%   |
| ASUS X51RL            | 2         | 0.76%   |
| ASUS ROG              | 2         | 0.76%   |
| Acer TravelMate       | 2         | 0.76%   |
| Acer Predator         | 2         | 0.76%   |
| Acer Nitro            | 2         | 0.76%   |
| Toshiba Portable      | 1         | 0.38%   |
| Sony VPCEH2M1R        | 1         | 0.38%   |
| Sony VPCEB1E1R        | 1         | 0.38%   |
| Sony VPCEA3M1R        | 1         | 0.38%   |
| Sony VPCCB2S1R        | 1         | 0.38%   |
| Sony VGN-NW320F       | 1         | 0.38%   |
| Sony VGN-NR430E       | 1         | 0.38%   |
| Sony VGN-FW245J       | 1         | 0.38%   |
| Samsung R518          | 1         | 0.38%   |
| Samsung N100SP        | 1         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2012    | 33        | 12.55%  |
| 2011    | 29        | 11.03%  |
| 2013    | 25        | 9.51%   |
| 2020    | 24        | 9.13%   |
| 2017    | 20        | 7.6%    |
| 2018    | 17        | 6.46%   |
| 2021    | 16        | 6.08%   |
| 2019    | 16        | 6.08%   |
| 2016    | 15        | 5.7%    |
| 2010    | 14        | 5.32%   |
| 2008    | 12        | 4.56%   |
| 2015    | 11        | 4.18%   |
| 2022    | 8         | 3.04%   |
| 2009    | 7         | 2.66%   |
| 2007    | 7         | 2.66%   |
| 2014    | 5         | 1.9%    |
| 2006    | 1         | 0.38%   |
| 2005    | 1         | 0.38%   |
| 2003    | 1         | 0.38%   |
| Unknown | 1         | 0.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 263       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 243       | 91.7%   |
| Enabled  | 22        | 8.3%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 263       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 80        | 29.96%  |
| 3.01-4.0   | 72        | 26.97%  |
| 8.01-16.0  | 39        | 14.61%  |
| 16.01-24.0 | 31        | 11.61%  |
| 1.01-2.0   | 16        | 5.99%   |
| 2.01-3.0   | 15        | 5.62%   |
| 32.01-64.0 | 5         | 1.87%   |
| 0.51-1.0   | 5         | 1.87%   |
| 24.01-32.0 | 3         | 1.12%   |
| Unknown    | 1         | 0.37%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 103       | 35.52%  |
| 0.51-1.0   | 58        | 20%     |
| 2.01-3.0   | 56        | 19.31%  |
| 3.01-4.0   | 36        | 12.41%  |
| 4.01-8.0   | 24        | 8.28%   |
| 8.01-16.0  | 6         | 2.07%   |
| 0.01-0.5   | 4         | 1.38%   |
| Unknown    | 2         | 0.69%   |
| 16.01-24.0 | 1         | 0.34%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 211       | 78.73%  |
| 2      | 55        | 20.52%  |
| 3      | 2         | 0.75%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 147       | 55.89%  |
| Yes       | 116       | 44.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 233       | 88.59%  |
| No        | 30        | 11.41%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 261       | 99.24%  |
| No        | 2         | 0.76%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 206       | 77.15%  |
| No        | 61        | 22.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country    | Notebooks | Percent |
|------------|-----------|---------|
| Kazakhstan | 263       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Notebooks | Percent |
|-----------------|-----------|---------|
| Almaty          | 86        | 29.97%  |
| Nur-Sultan      | 47        | 16.38%  |
| Ust-Kamenogorsk | 16        | 5.57%   |
| Pavlodar        | 16        | 5.57%   |
| Karaganda       | 15        | 5.23%   |
| Kostanay        | 14        | 4.88%   |
| Aktobe          | 12        | 4.18%   |
| Astana          | 9         | 3.14%   |
| Taraz           | 8         | 2.79%   |
| Petropavl       | 7         | 2.44%   |
| Shymkent        | 6         | 2.09%   |
| Aktau           | 6         | 2.09%   |
| Semey           | 5         | 1.74%   |
| Rudnyy          | 5         | 1.74%   |
| Kyzylorda       | 5         | 1.74%   |
| Atyrau          | 4         | 1.39%   |
| Ridder          | 3         | 1.05%   |
| Oral            | 3         | 1.05%   |
| Temirtau        | 2         | 0.7%    |
| Taiynsha        | 2         | 0.7%    |
| Stepnogorsk     | 2         | 0.7%    |
| Soran           | 2         | 0.7%    |
| Shchūchīnsk   | 2         | 0.7%    |
| Ekibastuz       | 2         | 0.7%    |
| Balqash         | 2         | 0.7%    |
| Līsakovsk      | 1         | 0.35%   |
| Kaskelen        | 1         | 0.35%   |
| Karagandy       | 1         | 0.35%   |
| Kapshagay       | 1         | 0.35%   |
| GГјlshat      | 1         | 0.35%   |
| Chiili          | 1         | 0.35%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                   | Notebooks | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Seagate                  | 55        | 76     | 16.98%  |
| WDC                      | 54        | 68     | 16.67%  |
| Toshiba                  | 30        | 37     | 9.26%   |
| Samsung Electronics      | 28        | 31     | 8.64%   |
| Kingston                 | 18        | 19     | 5.56%   |
| Hitachi                  | 18        | 20     | 5.56%   |
| HGST                     | 16        | 18     | 4.94%   |
| Unknown                  | 14        | 17     | 4.32%   |
| SK hynix                 | 11        | 11     | 3.4%    |
| Transcend                | 10        | 10     | 3.09%   |
| Intel                    | 10        | 10     | 3.09%   |
| SanDisk                  | 7         | 8      | 2.16%   |
| Micron Technology        | 5         | 7      | 1.54%   |
| KIOXIA                   | 5         | 7      | 1.54%   |
| A-DATA Technology        | 5         | 6      | 1.54%   |
| Plextor                  | 4         | 4      | 1.23%   |
| GeIL                     | 4         | 4      | 1.23%   |
| Fujitsu                  | 4         | 5      | 1.23%   |
| China                    | 4         | 4      | 1.23%   |
| Apacer                   | 4         | 5      | 1.23%   |
| Crucial                  | 3         | 3      | 0.93%   |
| Phison                   | 2         | 2      | 0.62%   |
| Gigabyte Technology      | 2         | 2      | 0.62%   |
| BIWIN                    | 2         | 2      | 0.62%   |
| Team                     | 1         | 1      | 0.31%   |
| Netac                    | 1         | 1      | 0.31%   |
| KingDian                 | 1         | 1      | 0.31%   |
| Kingchuxing              | 1         | 2      | 0.31%   |
| JMicron Technology       | 1         | 1      | 0.31%   |
| HUAWEI                   | 1         | 1      | 0.31%   |
| HS-SSD-E100              | 1         | 1      | 0.31%   |
| HGST HTS                 | 1         | 1      | 0.31%   |
| Biwin Storage Technology | 1         | 2      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 16        | 4.86%   |
| Seagate ST1000LM035-1RK172 1TB                      | 11        | 3.34%   |
| Toshiba MQ04ABF100 1TB                              | 7         | 2.13%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 6         | 1.82%   |
| HGST HTS541010A9E680 1TB                            | 6         | 1.82%   |
| Toshiba MQ01ABF050 500GB                            | 5         | 1.52%   |
| Toshiba MQ01ABD100 1TB                              | 5         | 1.52%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 4         | 1.22%   |
| Seagate ST9320325AS 320GB                           | 4         | 1.22%   |
| Seagate ST500LT012-1DG142 500GB                     | 4         | 1.22%   |
| Kingston SA400S37120G 120GB SSD                     | 4         | 1.22%   |
| Intel SSDPEKNU512GZ 512GB                           | 4         | 1.22%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 3         | 0.91%   |
| Transcend TS120GSSD220S 120GB                       | 3         | 0.91%   |
| SK hynix NVMe SSD Drive 512GB                       | 3         | 0.91%   |
| Seagate ST500LT012-9WS142 500GB                     | 3         | 0.91%   |
| Samsung MZALQ512HALU-000L2 512GB                    | 3         | 0.91%   |
| Kingston SA400S37480G 480GB SSD                     | 3         | 0.91%   |
| Kingston SA400S37240G 240GB SSD                     | 3         | 0.91%   |
| Intel NVMe SSD Drive 512GB                          | 3         | 0.91%   |
| Hitachi HTS543232A7A384 320GB                       | 3         | 0.91%   |
| WDC WD7500BPVT-22HXZT3 752GB                        | 2         | 0.61%   |
| WDC WD7500BPVT-08HXZT3 752GB                        | 2         | 0.61%   |
| WDC WD5000LPCX-21VHAT0 500GB                        | 2         | 0.61%   |
| WDC WD3200BPVT-22ZEST0 320GB                        | 2         | 0.61%   |
| WDC WD10SPZX-24Z10 1TB                              | 2         | 0.61%   |
| Unknown SD32G  32GB                                 | 2         | 0.61%   |
| Unknown MMC Card  4GB                               | 2         | 0.61%   |
| Unknown MMC Card  16GB                              | 2         | 0.61%   |
| Transcend TS128GSSD230S 128GB                       | 2         | 0.61%   |
| Toshiba MK5059GSXP 500GB                            | 2         | 0.61%   |
| Seagate ST9750420AS 752GB                           | 2         | 0.61%   |
| Seagate ST750LM022 HN-M750MBB 752GB                 | 2         | 0.61%   |
| SanDisk NVMe SSD Drive 512GB                        | 2         | 0.61%   |
| Samsung NVMe SSD Drive 256GB                        | 2         | 0.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 2         | 0.61%   |
| Samsung MZVLB512HAJQ-000L7 512GB                    | 2         | 0.61%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                      | 2         | 0.61%   |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 0.61%   |
| Hitachi HTS547575A9E384 752GB                       | 2         | 0.61%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 55        | 76     | 31.79%  |
| WDC                 | 47        | 60     | 27.17%  |
| Toshiba             | 28        | 35     | 16.18%  |
| Hitachi             | 18        | 20     | 10.4%   |
| HGST                | 16        | 18     | 9.25%   |
| Samsung Electronics | 4         | 4      | 2.31%   |
| Fujitsu             | 4         | 5      | 2.31%   |
| HGST HTS            | 1         | 1      | 0.58%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 15        | 16     | 22.06%  |
| Transcend           | 10        | 10     | 14.71%  |
| SanDisk             | 4         | 4      | 5.88%   |
| Samsung Electronics | 4         | 5      | 5.88%   |
| Plextor             | 4         | 4      | 5.88%   |
| China               | 4         | 4      | 5.88%   |
| Crucial             | 3         | 3      | 4.41%   |
| Apacer              | 3         | 4      | 4.41%   |
| A-DATA Technology   | 3         | 4      | 4.41%   |
| WDC                 | 2         | 2      | 2.94%   |
| SK hynix            | 2         | 2      | 2.94%   |
| Micron Technology   | 2         | 2      | 2.94%   |
| Intel               | 2         | 2      | 2.94%   |
| Gigabyte Technology | 2         | 2      | 2.94%   |
| GeIL                | 2         | 2      | 2.94%   |
| Unknown             | 1         | 1      | 1.47%   |
| Team                | 1         | 1      | 1.47%   |
| Netac               | 1         | 1      | 1.47%   |
| KingDian            | 1         | 1      | 1.47%   |
| Kingchuxing         | 1         | 2      | 1.47%   |
| BIWIN               | 1         | 1      | 1.47%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 167       | 219    | 54.58%  |
| SSD     | 62        | 73     | 20.26%  |
| NVMe    | 60        | 75     | 19.61%  |
| MMC     | 13        | 16     | 4.25%   |
| Unknown | 4         | 4      | 1.31%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 211       | 290    | 73.01%  |
| NVMe | 60        | 74     | 20.76%  |
| MMC  | 13        | 16     | 4.5%    |
| SAS  | 5         | 7      | 1.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 145       | 190    | 64.44%  |
| 0.51-1.0   | 80        | 102    | 35.56%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 82        | 28.57%  |
| 101-250        | 67        | 23.34%  |
| 501-1000       | 50        | 17.42%  |
| 1-20           | 32        | 11.15%  |
| 51-100         | 26        | 9.06%   |
| 1001-2000      | 16        | 5.57%   |
| 21-50          | 10        | 3.48%   |
| Unknown        | 3         | 1.05%   |
| More than 3000 | 1         | 0.35%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 139       | 48.1%   |
| 21-50     | 48        | 16.61%  |
| 101-250   | 40        | 13.84%  |
| 51-100    | 25        | 8.65%   |
| 251-500   | 20        | 6.92%   |
| 501-1000  | 13        | 4.5%    |
| Unknown   | 3         | 1.04%   |
| 1001-2000 | 1         | 0.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 3      | 6.25%   |
| Hitachi HTS543232A7A384 320GB       | 3         | 3      | 6.25%   |
| Toshiba MQ01ABF050 500GB            | 2         | 2      | 4.17%   |
| Toshiba MK5059GSXP 500GB            | 2         | 3      | 4.17%   |
| Seagate ST500LT012-9WS142 500GB     | 2         | 9      | 4.17%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 4      | 4.17%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 2         | 2      | 4.17%   |
| HGST HTS541010A9E680 1TB            | 2         | 3      | 4.17%   |
| WDC WD7500BPVT-08HXZT3 752GB        | 1         | 1      | 2.08%   |
| WDC WD5000LPCX-21VHAT0 500GB        | 1         | 5      | 2.08%   |
| WDC WD3200BPVT-75ZEST0 320GB        | 1         | 1      | 2.08%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 1         | 1      | 2.08%   |
| WDC WD3200BEVT-80A0RT0 320GB        | 1         | 1      | 2.08%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 1         | 1      | 2.08%   |
| WDC WD10JPCX-24UE4T0 1TB            | 1         | 1      | 2.08%   |
| Toshiba MQ04ABF100 1TB              | 1         | 1      | 2.08%   |
| Toshiba MK3263GSX 320GB             | 1         | 1      | 2.08%   |
| Toshiba MK2552GSX 250GB             | 1         | 1      | 2.08%   |
| Toshiba MK1637GSX 160GB             | 1         | 1      | 2.08%   |
| Seagate ST9500325AS 500GB           | 1         | 1      | 2.08%   |
| Seagate ST9320325AS 320GB           | 1         | 1      | 2.08%   |
| Seagate ST9250410AS 250GB           | 1         | 1      | 2.08%   |
| Seagate ST9120822AS 120GB           | 1         | 1      | 2.08%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 2      | 2.08%   |
| Samsung Electronics HM321HI 320GB   | 1         | 1      | 2.08%   |
| Plextor PX-128M6S 128GB SSD         | 1         | 1      | 2.08%   |
| Hitachi HTS725050A9A364 500GB       | 1         | 1      | 2.08%   |
| Hitachi HTS722020K9SA00 200GB       | 1         | 1      | 2.08%   |
| Hitachi HTS547575A9E384 752GB       | 1         | 1      | 2.08%   |
| Hitachi HTS547550A9E384 500GB       | 1         | 2      | 2.08%   |
| Hitachi HTS545050A7E380 500GB       | 1         | 1      | 2.08%   |
| Hitachi HTS543216L9SA00 160GB       | 1         | 1      | 2.08%   |
| Hitachi HTS542512K9SA00 120GB       | 1         | 1      | 2.08%   |
| Hitachi HTS541612J9SA00 120GB       | 1         | 1      | 2.08%   |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 2.08%   |
| HGST HTS721010A9E630 1TB            | 1         | 1      | 2.08%   |
| HGST HTS545050A7E380 500GB          | 1         | 1      | 2.08%   |
| HGST HTS541010B7E610 1TB            | 1         | 1      | 2.08%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 24     | 29.17%  |
| Hitachi             | 11        | 12     | 22.92%  |
| Toshiba             | 8         | 9      | 16.67%  |
| WDC                 | 7         | 11     | 14.58%  |
| HGST                | 6         | 7      | 12.5%   |
| Samsung Electronics | 1         | 1      | 2.08%   |
| Plextor             | 1         | 1      | 2.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 14        | 24     | 29.79%  |
| Hitachi             | 11        | 12     | 23.4%   |
| Toshiba             | 8         | 9      | 17.02%  |
| WDC                 | 7         | 11     | 14.89%  |
| HGST                | 6         | 7      | 12.77%  |
| Samsung Electronics | 1         | 1      | 2.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 45        | 64     | 97.83%  |
| SSD  | 1         | 1      | 2.17%   |

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
| Works    | 151       | 203    | 52.61%  |
| Detected | 90        | 119    | 31.36%  |
| Malfunc  | 46        | 65     | 16.03%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 207       | 68.54%  |
| AMD                          | 38        | 12.58%  |
| Samsung Electronics          | 20        | 6.62%   |
| SK hynix                     | 9         | 2.98%   |
| SanDisk                      | 7         | 2.32%   |
| KIOXIA                       | 4         | 1.32%   |
| Toshiba America Info Systems | 3         | 0.99%   |
| Phison Electronics           | 3         | 0.99%   |
| Micron Technology            | 3         | 0.99%   |
| Kingston Technology Company  | 3         | 0.99%   |
| ADATA Technology             | 2         | 0.66%   |
| Union Memory (Shenzhen)      | 1         | 0.33%   |
| Nvidia                       | 1         | 0.33%   |
| Biwin Storage Technology     | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 33        | 9.91%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 30        | 9.01%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 28        | 8.41%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 17        | 5.11%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 13        | 3.9%    |
| Intel Volume Management Device NVMe RAID Controller                              | 11        | 3.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 10        | 3%      |
| Samsung NVMe SSD Controller 980                                                  | 9         | 2.7%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 9         | 2.7%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 8         | 2.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 8         | 2.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 7         | 2.1%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 7         | 2.1%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 6         | 1.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 6         | 1.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 6         | 1.8%    |
| Intel Tiger Lake-LP SATA Controller                                              | 5         | 1.5%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 5         | 1.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 5         | 1.5%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                   | 5         | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 5         | 1.5%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 4         | 1.2%    |
| KIOXIA NVMe SSD Controller BG4                                                   | 4         | 1.2%    |
| Intel Non-Volatile memory controller                                             | 4         | 1.2%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 4         | 1.2%    |
| Intel Comet Lake SATA AHCI Controller                                            | 4         | 1.2%    |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 4         | 1.2%    |
| SK hynix BC511 NVMe SSD                                                          | 3         | 0.9%    |
| Intel SSD 660P Series                                                            | 3         | 0.9%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 3         | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 3         | 0.9%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 3         | 0.9%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 0.6%    |
| SK hynix BC501 NVMe Solid State Drive                                            | 2         | 0.6%    |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 2         | 0.6%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 2         | 0.6%    |
| SanDisk PC SN520 NVMe SSD                                                        | 2         | 0.6%    |
| Phison PS5013 E13 NVMe Controller                                                | 2         | 0.6%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 2         | 0.6%    |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 2         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 212       | 65.43%  |
| NVMe | 61        | 18.83%  |
| IDE  | 27        | 8.33%   |
| RAID | 24        | 7.41%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 218       | 82.89%  |
| AMD    | 45        | 17.11%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 8         | 3.04%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 5         | 1.9%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 1.9%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 5         | 1.9%    |
| Intel Core i3-3110M CPU @ 2.40GHz             | 5         | 1.9%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 1.52%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 4         | 1.52%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 4         | 1.52%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 4         | 1.52%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 4         | 1.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 1.14%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 3         | 1.14%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 3         | 1.14%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 1.14%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 3         | 1.14%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 1.14%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 1.14%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 3         | 1.14%   |
| AMD Ryzen 3 3200U with Radeon Vega Mobile Gfx | 3         | 1.14%   |
| AMD A8-4500M APU with Radeon HD Graphics      | 3         | 1.14%   |
| AMD A10-4600M APU with Radeon HD Graphics     | 3         | 1.14%   |
| Intel Pentium CPU P6100 @ 2.00GHz             | 2         | 0.76%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 2         | 0.76%   |
| Intel Genuine CPU T2400 @ 1.83GHz             | 2         | 0.76%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.76%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 0.76%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.76%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 2         | 0.76%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.76%   |
| Intel Core i7-3610QM CPU @ 2.30GHz            | 2         | 0.76%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 0.76%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 0.76%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 2         | 0.76%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 0.76%   |
| Intel Core i5-4200M CPU @ 2.50GHz             | 2         | 0.76%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.76%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.76%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 2         | 0.76%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.76%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 2         | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 72        | 27.38%  |
| Intel Core i7           | 35        | 13.31%  |
| Intel Core i3           | 34        | 12.93%  |
| Intel Celeron           | 19        | 7.22%   |
| Other                   | 14        | 5.32%   |
| Intel Pentium           | 10        | 3.8%    |
| AMD Ryzen 5             | 10        | 3.8%    |
| Intel Core 2 Duo        | 9         | 3.42%   |
| Intel Atom              | 9         | 3.42%   |
| AMD Ryzen 7             | 5         | 1.9%    |
| Intel Genuine           | 4         | 1.52%   |
| AMD Ryzen 3             | 4         | 1.52%   |
| AMD E                   | 4         | 1.52%   |
| AMD A8                  | 4         | 1.52%   |
| AMD A10                 | 4         | 1.52%   |
| Intel Pentium Dual-Core | 3         | 1.14%   |
| AMD A4                  | 3         | 1.14%   |
| Intel Pentium Dual      | 2         | 0.76%   |
| Intel Core 2            | 2         | 0.76%   |
| AMD E1                  | 2         | 0.76%   |
| Intel Pentium Silver    | 1         | 0.38%   |
| Intel Pentium M         | 1         | 0.38%   |
| Intel Pentium Gold      | 1         | 0.38%   |
| Intel Mobile Pentium 4  | 1         | 0.38%   |
| Intel Core Duo          | 1         | 0.38%   |
| Intel Core 2 Quad       | 1         | 0.38%   |
| AMD Ryzen 9             | 1         | 0.38%   |
| AMD PRO A8              | 1         | 0.38%   |
| AMD E2                  | 1         | 0.38%   |
| AMD C-60                | 1         | 0.38%   |
| AMD Athlon II           | 1         | 0.38%   |
| AMD Athlon              | 1         | 0.38%   |
| AMD A6                  | 1         | 0.38%   |
| AMD A12                 | 1         | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 158       | 60.08%  |
| 4       | 67        | 25.48%  |
| 6       | 16        | 6.08%   |
| 1       | 11        | 4.18%   |
| 8       | 5         | 1.9%    |
| Unknown | 3         | 1.14%   |
| 12      | 2         | 0.76%   |
| 10      | 1         | 0.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 262       | 99.62%  |
| Unknown | 1         | 0.38%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 187       | 71.1%   |
| 1       | 73        | 27.76%  |
| Unknown | 3         | 1.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 248       | 94.3%   |
| 32-bit         | 8         | 3.04%   |
| Unknown        | 7         | 2.66%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 34        | 12.64%  |
| 0x306a9    | 29        | 10.78%  |
| 0x206a7    | 24        | 8.92%   |
| 0x806e9    | 13        | 4.83%   |
| 0x806ea    | 9         | 3.35%   |
| 0x806c1    | 9         | 3.35%   |
| 0x906ea    | 8         | 2.97%   |
| 0x40651    | 8         | 2.97%   |
| 0x306c3    | 8         | 2.97%   |
| 0x20655    | 8         | 2.97%   |
| 0x06001119 | 8         | 2.97%   |
| 0x806ec    | 6         | 2.23%   |
| 0x406e3    | 6         | 2.23%   |
| 0x1067a    | 6         | 2.23%   |
| 0xa0652    | 5         | 1.86%   |
| 0x0a50000c | 5         | 1.86%   |
| 0x706a1    | 4         | 1.49%   |
| 0x6fd      | 4         | 1.49%   |
| 0x406c4    | 4         | 1.49%   |
| 0x30661    | 4         | 1.49%   |
| 0x20652    | 4         | 1.49%   |
| 0x08608103 | 4         | 1.49%   |
| 0x706e5    | 3         | 1.12%   |
| 0x6e8      | 3         | 1.12%   |
| 0x30678    | 3         | 1.12%   |
| 0x10676    | 3         | 1.12%   |
| 0x08108102 | 3         | 1.12%   |
| 0x906e9    | 2         | 0.74%   |
| 0x806eb    | 2         | 0.74%   |
| 0x6ec      | 2         | 0.74%   |
| 0x306d4    | 2         | 0.74%   |
| 0x106ca    | 2         | 0.74%   |
| 0x10661    | 2         | 0.74%   |
| 0x0a50000d | 2         | 0.74%   |
| 0x08108109 | 2         | 0.74%   |
| 0x07030105 | 2         | 0.74%   |
| 0x0700010f | 2         | 0.74%   |
| 0x05000119 | 2         | 0.74%   |
| 0x05000029 | 2         | 0.74%   |
| 0x03000027 | 2         | 0.74%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 49        | 18.63%  |
| IvyBridge        | 30        | 11.41%  |
| SandyBridge      | 25        | 9.51%   |
| Haswell          | 16        | 6.08%   |
| Westmere         | 12        | 4.56%   |
| TigerLake        | 11        | 4.18%   |
| Penryn           | 11        | 4.18%   |
| Silvermont       | 10        | 3.8%    |
| Core             | 10        | 3.8%    |
| Skylake          | 8         | 3.04%   |
| Piledriver       | 8         | 3.04%   |
| Bonnell          | 7         | 2.66%   |
| Zen 3            | 6         | 2.28%   |
| P6               | 6         | 2.28%   |
| CometLake        | 6         | 2.28%   |
| Unknown          | 6         | 2.28%   |
| Zen+             | 5         | 1.9%    |
| IceLake          | 5         | 1.9%    |
| Goldmont plus    | 5         | 1.9%    |
| Bobcat           | 5         | 1.9%    |
| Excavator        | 4         | 1.52%   |
| Zen 2            | 3         | 1.14%   |
| Alderlake Hybrid | 3         | 1.14%   |
| Puma             | 2         | 0.76%   |
| K10 Llano        | 2         | 0.76%   |
| Jaguar           | 2         | 0.76%   |
| Broadwell        | 2         | 0.76%   |
| Zen              | 1         | 0.38%   |
| NetBurst         | 1         | 0.38%   |
| K10              | 1         | 0.38%   |
| Goldmont         | 1         | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 196       | 54.29%  |
| Nvidia | 90        | 24.93%  |
| AMD    | 75        | 20.78%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 28        | 7.29%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 23        | 5.99%   |
| Intel HD Graphics 620                                                                    | 14        | 3.65%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 11        | 2.86%   |
| Intel UHD Graphics 620                                                                   | 10        | 2.6%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 2.34%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 8         | 2.08%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 8         | 2.08%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 1.82%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 1.82%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 1.82%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 6         | 1.56%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.56%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.56%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 6         | 1.56%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 5         | 1.3%    |
| Nvidia GF119M [GeForce 610M]                                                             | 5         | 1.3%    |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 5         | 1.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 1.3%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 1.3%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 1.3%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 5         | 1.3%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 1.3%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 5         | 1.3%    |
| AMD Sun PRO [Radeon HD 8570A/8570M]                                                      | 5         | 1.3%    |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 5         | 1.3%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.3%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.04%   |
| Nvidia TU117M                                                                            | 4         | 1.04%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 4         | 1.04%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 4         | 1.04%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 4         | 1.04%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 4         | 1.04%   |
| Intel HD Graphics 630                                                                    | 4         | 1.04%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.04%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1.04%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 4         | 1.04%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 4         | 1.04%   |
| AMD Lucienne                                                                             | 4         | 1.04%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.04%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 107       | 40.38%  |
| Intel + Nvidia | 70        | 26.42%  |
| 1 x AMD        | 35        | 13.21%  |
| Intel + AMD    | 20        | 7.55%   |
| 1 x Nvidia     | 13        | 4.91%   |
| 2 x AMD        | 12        | 4.53%   |
| AMD + Nvidia   | 8         | 3.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 228       | 85.71%  |
| Proprietary | 34        | 12.78%  |
| Unknown     | 4         | 1.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 99        | 36.8%   |
| 1.01-2.0   | 83        | 30.86%  |
| 0.01-0.5   | 51        | 18.96%  |
| 3.01-4.0   | 18        | 6.69%   |
| 0.51-1.0   | 13        | 4.83%   |
| 5.01-6.0   | 4         | 1.49%   |
| 7.01-8.0   | 1         | 0.37%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 58        | 21.32%  |
| LG Display              | 52        | 19.12%  |
| BOE                     | 38        | 13.97%  |
| Samsung Electronics     | 35        | 12.87%  |
| Chimei Innolux          | 33        | 12.13%  |
| Chi Mei Optoelectronics | 15        | 5.51%   |
| Hewlett-Packard         | 5         | 1.84%   |
| Acer                    | 5         | 1.84%   |
| PANDA                   | 3         | 1.1%    |
| LG Philips              | 3         | 1.1%    |
| Lenovo                  | 3         | 1.1%    |
| Goldstar                | 3         | 1.1%    |
| Toshiba                 | 2         | 0.74%   |
| Sony                    | 2         | 0.74%   |
| Quanta Display          | 2         | 0.74%   |
| InfoVision              | 2         | 0.74%   |
| HannStar                | 2         | 0.74%   |
| CPT                     | 2         | 0.74%   |
| Unknown (XXX)           | 1         | 0.37%   |
| Sharp                   | 1         | 0.37%   |
| Seiko/Epson             | 1         | 0.37%   |
| Philips                 | 1         | 0.37%   |
| KDC                     | 1         | 0.37%   |
| Dell                    | 1         | 0.37%   |
| BenQ                    | 1         | 0.37%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 7         | 2.55%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch     | 5         | 1.82%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 5         | 1.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 1.46%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 4         | 1.46%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 4         | 1.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 4         | 1.46%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 1.09%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 3         | 1.09%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 3         | 1.09%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 3         | 1.09%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 3         | 1.09%   |
| Sony LCD Monitor SNY05FA 1366x768 310x170mm 13.9-inch                    | 2         | 0.73%   |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 2         | 0.73%   |
| Samsung Electronics LCD Monitor SEC3642 1366x768 309x174mm 14.0-inch     | 2         | 0.73%   |
| Samsung Electronics LCD Monitor SEC3253 1366x768 344x194mm 15.5-inch     | 2         | 0.73%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch     | 2         | 0.73%   |
| Samsung Electronics LCD Monitor SDC416E 2880x1620 344x194mm 15.5-inch    | 2         | 0.73%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 2         | 0.73%   |
| Samsung Electronics LCD Monitor SDC3654 1600x900 382x215mm 17.3-inch     | 2         | 0.73%   |
| Samsung Electronics LCD Monitor SAM0669 1920x1080                        | 2         | 0.73%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 2         | 0.73%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 2         | 0.73%   |
| LG Display LCD Monitor LGD0384 1366x768 344x194mm 15.5-inch              | 2         | 0.73%   |
| LG Display LCD Monitor LGD033B 1366x768 344x194mm 15.5-inch              | 2         | 0.73%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 2         | 0.73%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch         | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN15D3 1920x1080 344x193mm 15.5-inch         | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x194mm 15.5-inch          | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN15B6 1366x768 344x193mm 15.5-inch          | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 2         | 0.73%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 2         | 0.73%   |
| Chi Mei Optoelectronics LCD Monitor CMO1018 1024x600 222x125mm 10.0-inch | 2         | 0.73%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                    | 2         | 0.73%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                    | 2         | 0.73%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 2         | 0.73%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.73%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 120       | 45.45%  |
| 1920x1080 (FHD)    | 92        | 34.85%  |
| 1600x900 (HD+)     | 13        | 4.92%   |
| 1280x800 (WXGA)    | 11        | 4.17%   |
| 1024x600           | 5         | 1.89%   |
| 2560x1440 (QHD)    | 4         | 1.52%   |
| 1680x1050 (WSXGA+) | 3         | 1.14%   |
| 1440x900 (WXGA+)   | 3         | 1.14%   |
| 2880x1620          | 2         | 0.76%   |
| 2560x1600          | 2         | 0.76%   |
| 1920x1200 (WUXGA)  | 2         | 0.76%   |
| 1400x1050          | 2         | 0.76%   |
| 1280x1024 (SXGA)   | 2         | 0.76%   |
| 2160x1440          | 1         | 0.38%   |
| 1360x768           | 1         | 0.38%   |
| 1024x768 (XGA)     | 1         | 0.38%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 173       | 63.14%  |
| 17      | 20        | 7.3%    |
| 14      | 19        | 6.93%   |
| 13      | 18        | 6.57%   |
| 10      | 6         | 2.19%   |
| 21      | 5         | 1.82%   |
| 27      | 4         | 1.46%   |
| 24      | 4         | 1.46%   |
| 12      | 4         | 1.46%   |
| 18      | 3         | 1.09%   |
| 16      | 3         | 1.09%   |
| 11      | 3         | 1.09%   |
| Unknown | 3         | 1.09%   |
| 31      | 2         | 0.73%   |
| 19      | 2         | 0.73%   |
| 54      | 1         | 0.36%   |
| 43      | 1         | 0.36%   |
| 40      | 1         | 0.36%   |
| 23      | 1         | 0.36%   |
| 22      | 1         | 0.36%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 201       | 73.36%  |
| 351-400     | 25        | 9.12%   |
| 201-300     | 22        | 8.03%   |
| 501-600     | 9         | 3.28%   |
| 401-500     | 9         | 3.28%   |
| Unknown     | 3         | 1.09%   |
| 801-900     | 2         | 0.73%   |
| 601-700     | 2         | 0.73%   |
| 1001-1500   | 1         | 0.36%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 229       | 89.45%  |
| 16/10   | 18        | 7.03%   |
| 4/3     | 4         | 1.56%   |
| 3/2     | 2         | 0.78%   |
| 6/5     | 1         | 0.39%   |
| 5/4     | 1         | 0.39%   |
| Unknown | 1         | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 173       | 63.14%  |
| 81-90          | 28        | 10.22%  |
| 121-130        | 17        | 6.2%    |
| 201-250        | 10        | 3.65%   |
| 71-80          | 9         | 3.28%   |
| 41-50          | 6         | 2.19%   |
| 301-350        | 4         | 1.46%   |
| 151-200        | 4         | 1.46%   |
| 61-70          | 3         | 1.09%   |
| 51-60          | 3         | 1.09%   |
| 131-140        | 3         | 1.09%   |
| 91-100         | 3         | 1.09%   |
| Unknown        | 3         | 1.09%   |
| 351-500        | 2         | 0.73%   |
| 141-150        | 2         | 0.73%   |
| 501-1000       | 2         | 0.73%   |
| More than 1000 | 1         | 0.36%   |
| 111-120        | 1         | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 101-120 | 122       | 44.85%  |
| 121-160 | 95        | 34.93%  |
| 51-100  | 39        | 14.34%  |
| 161-240 | 10        | 3.68%   |
| 1-50    | 3         | 1.1%    |
| Unknown | 3         | 1.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 237       | 89.1%   |
| 2     | 26        | 9.77%   |
| 0     | 3         | 1.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 173       | 38.62%  |
| Intel                             | 105       | 23.44%  |
| Qualcomm Atheros                  | 85        | 18.97%  |
| Broadcom                          | 27        | 6.03%   |
| Broadcom Limited                  | 11        | 2.46%   |
| Ralink                            | 10        | 2.23%   |
| MediaTek                          | 10        | 2.23%   |
| Marvell Technology Group          | 6         | 1.34%   |
| Xiaomi                            | 4         | 0.89%   |
| Huawei Technologies               | 3         | 0.67%   |
| Hewlett-Packard                   | 3         | 0.67%   |
| Ralink Technology                 | 2         | 0.45%   |
| JMicron Technology                | 2         | 0.45%   |
| Qualcomm Atheros Communications   | 1         | 0.22%   |
| ICS Advent                        | 1         | 0.22%   |
| HTC (High Tech Computer)          | 1         | 0.22%   |
| Fujitsu Siemens Computers         | 1         | 0.22%   |
| Ericsson Business Mobile Networks | 1         | 0.22%   |
| DisplayLink                       | 1         | 0.22%   |
| Android                           | 1         | 0.22%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 102       | 19.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 47        | 9.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 19        | 3.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 18        | 3.5%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 2.91%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 15        | 2.91%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 2.72%   |
| Intel Wireless 8265 / 8275                                              | 11        | 2.14%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 1.94%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 10        | 1.94%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 1.55%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 1.55%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 1.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 6         | 1.17%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 1.17%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 0.97%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 5         | 0.97%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 0.97%   |
| Intel Centrino Wireless-N 2230                                          | 5         | 0.97%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 0.97%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 0.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 5         | 0.97%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 4         | 0.78%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 0.78%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 4         | 0.78%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 0.78%   |
| Intel Wireless 7260                                                     | 4         | 0.78%   |
| Intel Wireless 3160                                                     | 4         | 0.78%   |
| Intel WiFi Link 5100                                                    | 4         | 0.78%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 0.78%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 4         | 0.78%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 4         | 0.78%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 4         | 0.78%   |
| Broadcom BCM43227 802.11b/g/n                                           | 4         | 0.78%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 3         | 0.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 3         | 0.58%   |
| Intel Wireless 7265                                                     | 3         | 0.58%   |
| Intel Ethernet Connection (4) I219-LM                                   | 3         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 103       | 38.87%  |
| Qualcomm Atheros                | 72        | 27.17%  |
| Realtek Semiconductor           | 38        | 14.34%  |
| Broadcom                        | 24        | 9.06%   |
| Ralink                          | 10        | 3.77%   |
| MediaTek                        | 8         | 3.02%   |
| Broadcom Limited                | 6         | 2.26%   |
| Ralink Technology               | 2         | 0.75%   |
| Qualcomm Atheros Communications | 1         | 0.38%   |
| Fujitsu Siemens Computers       | 1         | 0.38%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 19        | 7.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 18        | 6.79%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 15        | 5.66%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 15        | 5.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 14        | 5.28%   |
| Intel Wireless 8265 / 8275                                              | 11        | 4.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 3.77%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 8         | 3.02%   |
| Intel Wi-Fi 6 AX201                                                     | 8         | 3.02%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 8         | 3.02%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 6         | 2.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.89%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 5         | 1.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 5         | 1.89%   |
| Intel Centrino Wireless-N 2230                                          | 5         | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 5         | 1.89%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 4         | 1.51%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.51%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 4         | 1.51%   |
| Intel Wireless 7260                                                     | 4         | 1.51%   |
| Intel Wireless 3160                                                     | 4         | 1.51%   |
| Intel WiFi Link 5100                                                    | 4         | 1.51%   |
| Intel Wi-Fi 6 AX200                                                     | 4         | 1.51%   |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                           | 4         | 1.51%   |
| Broadcom Limited BCM4313 802.11bgn Wireless Network Adapter             | 4         | 1.51%   |
| Broadcom BCM43227 802.11b/g/n                                           | 4         | 1.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.13%   |
| Intel Wireless 7265                                                     | 3         | 1.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 1.13%   |
| Intel Centrino Wireless-N 135                                           | 3         | 1.13%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.13%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 2         | 0.75%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.75%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.75%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 2         | 0.75%   |
| Intel Wireless 3165                                                     | 2         | 0.75%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 0.75%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 157       | 65.15%  |
| Qualcomm Atheros         | 28        | 11.62%  |
| Intel                    | 24        | 9.96%   |
| Marvell Technology Group | 6         | 2.49%   |
| Broadcom Limited         | 6         | 2.49%   |
| Broadcom                 | 6         | 2.49%   |
| Xiaomi                   | 4         | 1.66%   |
| MediaTek                 | 2         | 0.83%   |
| JMicron Technology       | 2         | 0.83%   |
| Huawei Technologies      | 2         | 0.83%   |
| ICS Advent               | 1         | 0.41%   |
| HTC (High Tech Computer) | 1         | 0.41%   |
| DisplayLink              | 1         | 0.41%   |
| Android                  | 1         | 0.41%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 102       | 41.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 47        | 19.34%  |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 10        | 4.12%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 6         | 2.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 5         | 2.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 4         | 1.65%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 4         | 1.65%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 1.23%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 3         | 1.23%   |
| Intel Ethernet Connection (4) I219-LM                                          | 3         | 1.23%   |
| Intel 82577LM Gigabit Network Connection                                       | 3         | 1.23%   |
| Intel 82573L Gigabit Ethernet Controller                                       | 3         | 1.23%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                          | 2         | 0.82%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 2         | 0.82%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 2         | 0.82%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 2         | 0.82%   |
| MediaTek Armor X10 Pro                                                         | 2         | 0.82%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.82%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller                        | 2         | 0.82%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 2         | 0.82%   |
| Intel 82567LM Gigabit Network Connection                                       | 2         | 0.82%   |
| Huawei E353/E3131                                                              | 2         | 0.82%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express                 | 2         | 0.82%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                           | 1         | 0.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.41%   |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.41%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 1         | 0.41%   |
| Realtek Killer E2500 Gigabit Ethernet Controller                               | 1         | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1         | 0.41%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                        | 1         | 0.41%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller                           | 1         | 0.41%   |
| Intel WiMAX Connection 2400m                                                   | 1         | 0.41%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.41%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.41%   |
| Intel Ethernet Connection I217-LM                                              | 1         | 0.41%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.41%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.41%   |
| Intel Ethernet Connection (13) I219-LM                                         | 1         | 0.41%   |
| Intel 82801CAM (ICH3) PRO/100 VE (LOM) Ethernet Controller                     | 1         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 261       | 52.2%   |
| Ethernet | 232       | 46.4%   |
| Modem    | 7         | 1.4%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 222       | 80.14%  |
| Ethernet | 55        | 19.86%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 226       | 85.93%  |
| 1     | 35        | 13.31%  |
| 0     | 2         | 0.76%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 260       | 98.48%  |
| Yes  | 4         | 1.52%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 71        | 34.47%  |
| Realtek Semiconductor           | 25        | 12.14%  |
| IMC Networks                    | 22        | 10.68%  |
| Qualcomm Atheros Communications | 18        | 8.74%   |
| Lite-On Technology              | 17        | 8.25%   |
| Broadcom                        | 16        | 7.77%   |
| Ralink                          | 8         | 3.88%   |
| Hewlett-Packard                 | 7         | 3.4%    |
| Foxconn / Hon Hai               | 7         | 3.4%    |
| Toshiba                         | 6         | 2.91%   |
| Foxconn International           | 3         | 1.46%   |
| ASUSTek Computer                | 2         | 0.97%   |
| Realtek                         | 1         | 0.49%   |
| Ralink Technology               | 1         | 0.49%   |
| Cambridge Silicon Radio         | 1         | 0.49%   |
| Askey Computer                  | 1         | 0.49%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 27        | 13.11%  |
| Realtek Bluetooth Radio                           | 16        | 7.77%   |
| Intel AX201 Bluetooth                             | 13        | 6.31%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 12        | 5.83%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 12        | 5.83%   |
| Ralink RT3290 Bluetooth                           | 8         | 3.88%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 8         | 3.88%   |
| IMC Networks Bluetooth Radio                      | 8         | 3.88%   |
| Realtek  Bluetooth 4.2 Adapter                    | 7         | 3.4%    |
| Qualcomm Atheros AR3011 Bluetooth                 | 6         | 2.91%   |
| IMC Networks Wireless_Device                      | 5         | 2.43%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]     | 5         | 2.43%   |
| Broadcom HP Portable Valentine                    | 5         | 2.43%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 4         | 1.94%   |
| Intel AX200 Bluetooth                             | 4         | 1.94%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter | 4         | 1.94%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR              | 4         | 1.94%   |
| Toshiba Integrated Bluetooth HCI                  | 3         | 1.46%   |
| Qualcomm Atheros  Bluetooth Device                | 3         | 1.46%   |
| Intel Wireless-AC 3168 Bluetooth                  | 3         | 1.46%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 3         | 1.46%   |
| IMC Networks Bluetooth Device                     | 3         | 1.46%   |
| Foxconn International BCM43142A0 Bluetooth module | 3         | 1.46%   |
| Realtek RTL8821A Bluetooth                        | 2         | 0.97%   |
| Qualcomm Atheros Bluetooth                        | 2         | 0.97%   |
| Lite-On Bluetooth Device                          | 2         | 0.97%   |
| Lite-On Atheros AR3012 Bluetooth                  | 2         | 0.97%   |
| HP Broadcom 2070 Bluetooth Combo                  | 2         | 0.97%   |
| Foxconn / Hon Hai Bluetooth Device                | 2         | 0.97%   |
| Broadcom HP Portable SoftSailing                  | 2         | 0.97%   |
| Broadcom BCM20702A0                               | 2         | 0.97%   |
| ASUS BT-270 Bluetooth Adapter                     | 2         | 0.97%   |
| Toshiba RT Bluetooth Radio                        | 1         | 0.49%   |
| Toshiba Integrated Bluetooth                      | 1         | 0.49%   |
| Toshiba Askey Bluetooth Module                    | 1         | 0.49%   |
| Realtek Bluetooth Radio                           | 1         | 0.49%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter      | 1         | 0.49%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 1         | 0.49%   |
| Qualcomm Atheros Bluetooth USB Host Controller    | 1         | 0.49%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 1         | 0.49%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Intel               | 213       | 68.93%  |
| AMD                 | 55        | 17.8%   |
| Nvidia              | 33        | 10.68%  |
| Focusrite-Novation  | 2         | 0.65%   |
| C-Media Electronics | 2         | 0.65%   |
| Pixart Imaging      | 1         | 0.32%   |
| Huawei Technologies | 1         | 0.32%   |
| GYROCOM C&C         | 1         | 0.32%   |
| ELMCU               | 1         | 0.32%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 38        | 10.41%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 34        | 9.32%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 5.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 17        | 4.66%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 14        | 3.84%   |
| AMD FCH Azalia Controller                                                                         | 14        | 3.84%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 3.29%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 3.01%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 3.01%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 3.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 10        | 2.74%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 8         | 2.19%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 2.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 2.19%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 2.19%   |
| AMD Trinity HDMI Audio Controller                                                                 | 8         | 2.19%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 8         | 2.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 1.92%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 7         | 1.92%   |
| Intel Comet Lake PCH cAVS                                                                         | 6         | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 6         | 1.64%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.64%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.64%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 5         | 1.37%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 5         | 1.37%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.37%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 1.1%    |
| Intel CM238 HD Audio Controller                                                                   | 4         | 1.1%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.1%    |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.82%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 3         | 0.82%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 3         | 0.82%   |
| AMD Wrestler HDMI Audio                                                                           | 3         | 0.82%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 0.82%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.55%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.55%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.55%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 2         | 0.55%   |
| Nvidia Audio device                                                                               | 2         | 0.55%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| SK hynix             | 60        | 25.21%  |
| Samsung Electronics  | 60        | 25.21%  |
| Micron Technology    | 24        | 10.08%  |
| Unknown              | 22        | 9.24%   |
| Kingston             | 19        | 7.98%   |
| Ramaxel Technology   | 12        | 5.04%   |
| A-DATA Technology    | 8         | 3.36%   |
| Nanya Technology     | 5         | 2.1%    |
| Crucial              | 4         | 1.68%   |
| Transcend            | 3         | 1.26%   |
| Elpida               | 3         | 1.26%   |
| Unknown (ABCD)       | 2         | 0.84%   |
| Qimonda              | 2         | 0.84%   |
| GeIL                 | 2         | 0.84%   |
| ASint Technology     | 2         | 0.84%   |
| V-Color              | 1         | 0.42%   |
| Unknown (D386)       | 1         | 0.42%   |
| Unknown (8CAB)       | 1         | 0.42%   |
| Toshiba              | 1         | 0.42%   |
| Team                 | 1         | 0.42%   |
| SHARETRONIC          | 1         | 0.42%   |
| Qumo                 | 1         | 0.42%   |
| ProMos/Mosel Vitelic | 1         | 0.42%   |
| Atermiter            | 1         | 0.42%   |
| Apacer               | 1         | 0.42%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 2.39%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 5         | 1.99%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 5         | 1.99%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 1.59%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 1.59%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.59%   |
| Samsung RAM M471B5173EB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 4         | 1.59%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s          | 4         | 1.59%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s             | 4         | 1.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.2%    |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s           | 3         | 1.2%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.2%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 1.2%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.2%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.2%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 1.2%    |
| Samsung RAM M4 70T5663QZ3-CF7 2GB SODIMM DDR2 2048MT/s           | 3         | 1.2%    |
| Ramaxel RAM RMT3170EB68F9W1600 4GB SODIMM DDR3 1600MT/s          | 3         | 1.2%    |
| A-DATA RAM AD73I1C1674EV 4GB SODIMM DDR3 1334MT/s                | 3         | 1.2%    |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 0.8%    |
| Unknown RAM Module 2048MB SODIMM DDR2                            | 2         | 0.8%    |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 2         | 0.8%    |
| Unknown RAM Module 1024MB SODIMM DDR                             | 2         | 0.8%    |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 0.8%    |
| SK hynix RAM HYMP512S64CP8-Y5 1024MB SODIMM DDR 667MT/s          | 2         | 0.8%    |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.8%    |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.8%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 2         | 0.8%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.8%    |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.8%    |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.8%    |
| SK hynix RAM HMT325S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s        | 2         | 0.8%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.8%    |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.8%    |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.8%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.8%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 0.8%    |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s            | 2         | 0.8%    |
| Kingston RAM ACR16D3LFS1KBG/2G 2GB SODIMM DDR3 1600MT/s          | 2         | 0.8%    |
| Elpida RAM EBJ20UF8BCS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 2         | 0.8%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR3   | 106       | 54.08%  |
| DDR4   | 56        | 28.57%  |
| DDR2   | 15        | 7.65%   |
| SDRAM  | 7         | 3.57%   |
| LPDDR4 | 5         | 2.55%   |
| LPDDR5 | 2         | 1.02%   |
| LPDDR3 | 2         | 1.02%   |
| DDR    | 2         | 1.02%   |
| DDR5   | 1         | 0.51%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 186       | 93.47%  |
| Row Of Chips | 12        | 6.03%   |
| DIMM         | 1         | 0.5%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 4096  | 89        | 39.73%  |
| 8192  | 55        | 24.55%  |
| 2048  | 49        | 21.88%  |
| 1024  | 18        | 8.04%   |
| 16384 | 12        | 5.36%   |
| 512   | 1         | 0.45%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 75        | 33.33%  |
| 2667    | 25        | 11.11%  |
| 1334    | 23        | 10.22%  |
| 3200    | 21        | 9.33%   |
| 2400    | 13        | 5.78%   |
| 1333    | 13        | 5.78%   |
| Unknown | 13        | 5.78%   |
| 667     | 7         | 3.11%   |
| 2133    | 5         | 2.22%   |
| 1067    | 4         | 1.78%   |
| 3266    | 3         | 1.33%   |
| 2048    | 3         | 1.33%   |
| 800     | 3         | 1.33%   |
| 6400    | 2         | 0.89%   |
| 4267    | 2         | 0.89%   |
| 4199    | 2         | 0.89%   |
| 1867    | 2         | 0.89%   |
| 975     | 2         | 0.89%   |
| 533     | 2         | 0.89%   |
| 8400    | 1         | 0.44%   |
| 4800    | 1         | 0.44%   |
| 4266    | 1         | 0.44%   |
| 1066    | 1         | 0.44%   |
| 666     | 1         | 0.44%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Samsung Electronics    | 2         | 28.57%  |
| Hewlett-Packard        | 2         | 28.57%  |
| Xerox                  | 1         | 14.29%  |
| Seiko Epson            | 1         | 14.29%  |
| Panasonic (Matsushita) | 1         | 14.29%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Xerox WorkCentre 6015B               | 1         | 14.29%  |
| Seiko Epson L805 Series              | 1         | 14.29%  |
| Samsung ML-1640 Series Laser Printer | 1         | 14.29%  |
| Samsung M2020 Series                 | 1         | 14.29%  |
| Panasonic (Matsushita) KX-MB1500RU   | 1         | 14.29%  |
| HP LaserJet 1020                     | 1         | 14.29%  |
| HP LaserJet 1018                     | 1         | 14.29%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model          | Notebooks | Percent |
|----------------|-----------|---------|
| HP Scanjet 200 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 56        | 24.56%  |
| IMC Networks                           | 30        | 13.16%  |
| Quanta                                 | 28        | 12.28%  |
| Realtek Semiconductor                  | 22        | 9.65%   |
| Suyin                                  | 12        | 5.26%   |
| Sunplus Innovation Technology          | 12        | 5.26%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 5.26%   |
| Microdia                               | 8         | 3.51%   |
| Acer                                   | 7         | 3.07%   |
| Syntek                                 | 6         | 2.63%   |
| Bison Electronics                      | 6         | 2.63%   |
| Lite-On Technology                     | 4         | 1.75%   |
| Samsung Electronics                    | 3         | 1.32%   |
| Ricoh                                  | 3         | 1.32%   |
| Sonix Technology                       | 2         | 0.88%   |
| Silicon Motion                         | 2         | 0.88%   |
| Primax Electronics                     | 2         | 0.88%   |
| Luxvisions Innotech Limited            | 2         | 0.88%   |
| ALi                                    | 2         | 0.88%   |
| Alcor Micro                            | 2         | 0.88%   |
| Z-Star Microelectronics                | 1         | 0.44%   |
| SiGma Micro                            | 1         | 0.44%   |
| Nebraska Furniture Mart                | 1         | 0.44%   |
| Lenovo                                 | 1         | 0.44%   |
| Importek                               | 1         | 0.44%   |
| GEMBIRD                                | 1         | 0.44%   |
| Apple                                  | 1         | 0.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam            | 10        | 4.37%   |
| Quanta VGA WebCam                             | 6         | 2.62%   |
| Chicony HD WebCam                             | 6         | 2.62%   |
| Quanta HD User Facing                         | 5         | 2.18%   |
| IMC Networks Integrated Camera                | 5         | 2.18%   |
| Chicony Integrated Camera                     | 5         | 2.18%   |
| Syntek Lenovo EasyCamera                      | 4         | 1.75%   |
| Realtek Lenovo EasyCamera                     | 4         | 1.75%   |
| Quanta HD Webcam                              | 4         | 1.75%   |
| IMC Networks USB2.0 HD UVC WebCam             | 4         | 1.75%   |
| Chicony Integrated Camera (1280x720@30)       | 4         | 1.75%   |
| Chicony HP Truevision HD                      | 4         | 1.75%   |
| Chicony Fujitsu Integrated Camera             | 4         | 1.75%   |
| Acer Lenovo Integrated Webcam                 | 4         | 1.75%   |
| Suyin HP Truevision HD                        | 3         | 1.31%   |
| Suyin 1.3M HD WebCam                          | 3         | 1.31%   |
| Sunplus HD WebCam                             | 3         | 1.31%   |
| Sunplus Asus Webcam                           | 3         | 1.31%   |
| Samsung Galaxy A5 (MTP)                       | 3         | 1.31%   |
| Realtek Acer 640 x 480 laptop camera          | 3         | 1.31%   |
| Quanta HP Wide Vision HD Camera               | 3         | 1.31%   |
| Microdia Laptop_Integrated_Webcam_HD          | 3         | 1.31%   |
| Microdia Integrated_Webcam_HD                 | 3         | 1.31%   |
| Lite-On Integrated Camera                     | 3         | 1.31%   |
| IMC Networks Lenovo EasyCamera                | 3         | 1.31%   |
| Chicony VGA WebCam                            | 3         | 1.31%   |
| Chicony USB2.0 HD UVC WebCam                  | 3         | 1.31%   |
| Chicony USB2.0 0.3M UVC WebCam                | 3         | 1.31%   |
| Chicony Lenovo EasyCamera                     | 3         | 1.31%   |
| Chicony EasyCamera                            | 3         | 1.31%   |
| Cheng Uei Precision Industry (Foxlink) Webcam | 3         | 1.31%   |
| Suyin Integrated_Webcam_HD                    | 2         | 0.87%   |
| Sunplus Dell HD Webcam                        | 2         | 0.87%   |
| Sonix USB2.0 FHD UVC WebCam                   | 2         | 0.87%   |
| Ricoh Sony Vaio Integrated Webcam             | 2         | 0.87%   |
| Realtek USB Camera                            | 2         | 0.87%   |
| Realtek Integrated_Webcam_HD                  | 2         | 0.87%   |
| Realtek Integrated Webcam                     | 2         | 0.87%   |
| Quanta USB2.0 HD UVC WebCam                   | 2         | 0.87%   |
| Quanta HP Webcam                              | 2         | 0.87%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 14        | 28%     |
| Synaptics                          | 7         | 14%     |
| Shenzhen Goodix Technology         | 7         | 14%     |
| AuthenTec                          | 6         | 12%     |
| Upek                               | 5         | 10%     |
| STMicroelectronics                 | 4         | 8%      |
| Elan Microelectronics              | 3         | 6%      |
| Realtek USB2.0 Finger Print Bridge | 2         | 4%      |
| LighTuning Technology              | 2         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 6         | 12%     |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 5         | 10%     |
| STMicroelectronics Fingerprint Reader                           | 4         | 8%      |
| Shenzhen Goodix  Fingerprint Device                             | 4         | 8%      |
| AuthenTec AES2501 Fingerprint Sensor                            | 3         | 6%      |
| Validity Sensors VFS5011 Fingerprint Reader                     | 2         | 4%      |
| Validity Sensors Swipe Fingerprint Sensor                       | 2         | 4%      |
| Validity Sensors Fingerprint scanner                            | 2         | 4%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 2         | 4%      |
| Shenzhen Goodix Fingerprint Reader                              | 2         | 4%      |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 4%      |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 2         | 4%      |
| Elan ELAN:Fingerprint                                           | 2         | 4%      |
| AuthenTec AES2810                                               | 2         | 4%      |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 2%      |
| Validity Sensors VFS 5011 fingerprint sensor                    | 1         | 2%      |
| Synaptics WBDI Fingerprint Reader USB 086                       | 1         | 2%      |
| Synaptics  WBDI                                                 | 1         | 2%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint       | 1         | 2%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 1         | 2%      |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 1         | 2%      |
| Shenzhen Goodix FingerPrint                                     | 1         | 2%      |
| Elan ELAN:ARM-M4                                                | 1         | 2%      |
| AuthenTec Fingerprint Sensor                                    | 1         | 2%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 28.57%  |
| Alcor Micro | 2         | 28.57%  |
| Upek        | 1         | 14.29%  |
| O2 Micro    | 1         | 14.29%  |
| Lenovo      | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                        | 2         | 28.57%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 14.29%  |
| O2 Micro OZ776 CCID Smartcard Reader                       | 1         | 14.29%  |
| Lenovo Integrated Smart Card Reader                        | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor             | 1         | 14.29%  |
| Broadcom 58200                                             | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 171       | 62.87%  |
| 1     | 85        | 31.25%  |
| 2     | 14        | 5.15%   |
| 4     | 1         | 0.37%   |
| 3     | 1         | 0.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 50        | 43.48%  |
| Graphics card            | 30        | 26.09%  |
| Net/wireless             | 12        | 10.43%  |
| Bluetooth                | 9         | 7.83%   |
| Chipcard                 | 6         | 5.22%   |
| Camera                   | 3         | 2.61%   |
| Communication controller | 2         | 1.74%   |
| Multimedia controller    | 1         | 0.87%   |
| Modem                    | 1         | 0.87%   |
| Card reader              | 1         | 0.87%   |

