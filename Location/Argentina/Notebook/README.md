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

Total: 1483

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Exo           | Smart Serie LT              | [08d7c1d923](https://linux-hardware.org/?probe=08d7c1d923) | Aug 09, 2023 |
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
| Sony          | SVF14214CLW                 | [10c62e635e](https://linux-hardware.org/?probe=10c62e635e) | Mar 17, 2021 |
| ASUSTek       | K53E                        | [9f263fff1b](https://linux-hardware.org/?probe=9f263fff1b) | Mar 16, 2021 |
| Clevo         | M7x0S                       | [3a372bea27](https://linux-hardware.org/?probe=3a372bea27) | Mar 15, 2021 |
| Clevo         | M7x0S                       | [7d9fca62d2](https://linux-hardware.org/?probe=7d9fca62d2) | Mar 15, 2021 |
| ASUSTek       | K53E                        | [00b42a225f](https://linux-hardware.org/?probe=00b42a225f) | Mar 14, 2021 |
| Lenovo        | G560 0679                   | [e3e4d139c9](https://linux-hardware.org/?probe=e3e4d139c9) | Mar 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1c68dc36aa](https://linux-hardware.org/?probe=1c68dc36aa) | Mar 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e3489945bc](https://linux-hardware.org/?probe=e3489945bc) | Mar 13, 2021 |
| Exo           | C14C                        | [21f9a60600](https://linux-hardware.org/?probe=21f9a60600) | Mar 12, 2021 |
| HP            | Pavilion dv7                | [c358c5da72](https://linux-hardware.org/?probe=c358c5da72) | Mar 12, 2021 |
| Lenovo        | V330-15IKB 81AX             | [cd79de8b59](https://linux-hardware.org/?probe=cd79de8b59) | Mar 06, 2021 |
| HP            | 15                          | [5a6c144963](https://linux-hardware.org/?probe=5a6c144963) | Mar 03, 2021 |
| Compal        | PCW20                       | [687204c549](https://linux-hardware.org/?probe=687204c549) | Feb 28, 2021 |
| Dell          | Inspiron 3442               | [93cdabaff0](https://linux-hardware.org/?probe=93cdabaff0) | Feb 27, 2021 |
| Lenovo        | G480 20150                  | [fd423f422e](https://linux-hardware.org/?probe=fd423f422e) | Feb 27, 2021 |
| ASUSTek       | UX303UA                     | [4f9e891679](https://linux-hardware.org/?probe=4f9e891679) | Feb 27, 2021 |
| Acer          | Aspire 7560                 | [4a4a042dd5](https://linux-hardware.org/?probe=4a4a042dd5) | Feb 26, 2021 |
| Dell          | Latitude 7490               | [c72d91886b](https://linux-hardware.org/?probe=c72d91886b) | Feb 25, 2021 |
| HP            | 15                          | [2bccfa19ed](https://linux-hardware.org/?probe=2bccfa19ed) | Feb 25, 2021 |
| HP            | 15                          | [26e1784265](https://linux-hardware.org/?probe=26e1784265) | Feb 24, 2021 |
| Acer          | Aspire V3-471G              | [9679f4b721](https://linux-hardware.org/?probe=9679f4b721) | Feb 23, 2021 |
| Dell          | Latitude 7490               | [54e871ca5d](https://linux-hardware.org/?probe=54e871ca5d) | Feb 23, 2021 |
| Dell          | Latitude 7490               | [c8060ae48c](https://linux-hardware.org/?probe=c8060ae48c) | Feb 23, 2021 |
| Lenovo        | G50-80 Touch 80KR           | [857e2d24ec](https://linux-hardware.org/?probe=857e2d24ec) | Feb 22, 2021 |
| Lenovo        | 3000 N100 0689A31           | [2e87cb3413](https://linux-hardware.org/?probe=2e87cb3413) | Feb 21, 2021 |
| HP            | Pavilion 17                 | [690ee9606a](https://linux-hardware.org/?probe=690ee9606a) | Feb 19, 2021 |
| Compal        | PCW20                       | [59e7060e52](https://linux-hardware.org/?probe=59e7060e52) | Feb 17, 2021 |
| Lenovo        | ThinkPad P52 20MAS2NV00     | [fd1c22df8f](https://linux-hardware.org/?probe=fd1c22df8f) | Feb 16, 2021 |
| Dell          | Inspiron 1525               | [30d9ab855e](https://linux-hardware.org/?probe=30d9ab855e) | Feb 16, 2021 |
| Dell          | Inspiron 1525               | [a37ef6324c](https://linux-hardware.org/?probe=a37ef6324c) | Feb 16, 2021 |
| Sony          | SVF14214CLW                 | [939765811b](https://linux-hardware.org/?probe=939765811b) | Feb 15, 2021 |
| Dell          | Precision M4500             | [4afe123de3](https://linux-hardware.org/?probe=4afe123de3) | Feb 14, 2021 |
| Sony          | SVF14214CLW                 | [ff19a2061a](https://linux-hardware.org/?probe=ff19a2061a) | Feb 14, 2021 |
| HP            | Pavilion dm1                | [89fba540d9](https://linux-hardware.org/?probe=89fba540d9) | Feb 14, 2021 |
| Intel         | powered classmate PC        | [dd8b22c3e5](https://linux-hardware.org/?probe=dd8b22c3e5) | Feb 13, 2021 |
| ASUSTek       | K53E                        | [87f7d00f4b](https://linux-hardware.org/?probe=87f7d00f4b) | Feb 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [4ee1be31aa](https://linux-hardware.org/?probe=4ee1be31aa) | Feb 12, 2021 |
| Lenovo        | ThinkPad T430 2349DS5       | [11bb3b276a](https://linux-hardware.org/?probe=11bb3b276a) | Feb 11, 2021 |
| Lenovo        | ThinkPad T430 2349DS5       | [9b5e541bad](https://linux-hardware.org/?probe=9b5e541bad) | Feb 11, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [e0e0f96ce4](https://linux-hardware.org/?probe=e0e0f96ce4) | Feb 11, 2021 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [8f7b8ab812](https://linux-hardware.org/?probe=8f7b8ab812) | Feb 11, 2021 |
| ASUSTek       | X541NA                      | [e8ed6f17a3](https://linux-hardware.org/?probe=e8ed6f17a3) | Feb 07, 2021 |
| Dell          | Inspiron 3442               | [219cd8abba](https://linux-hardware.org/?probe=219cd8abba) | Feb 04, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [5d33c20e50](https://linux-hardware.org/?probe=5d33c20e50) | Feb 03, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | [a6879fb982](https://linux-hardware.org/?probe=a6879fb982) | Feb 02, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [71d08f3561](https://linux-hardware.org/?probe=71d08f3561) | Feb 01, 2021 |
| Acer          | Aspire ES1-572              | [09f8b1e97b](https://linux-hardware.org/?probe=09f8b1e97b) | Jan 31, 2021 |
| HP            | 250 G7 Notebook PC          | [0aeff90461](https://linux-hardware.org/?probe=0aeff90461) | Jan 31, 2021 |
| Lenovo        | G550 2958                   | [bef495cadc](https://linux-hardware.org/?probe=bef495cadc) | Jan 30, 2021 |
| Acer          | Aspire 5733Z                | [b15b48fb21](https://linux-hardware.org/?probe=b15b48fb21) | Jan 29, 2021 |
| Olidata       | U40SI1                      | [60dd97276a](https://linux-hardware.org/?probe=60dd97276a) | Jan 28, 2021 |
| Olidata       | U40SI1                      | [cca9468e85](https://linux-hardware.org/?probe=cca9468e85) | Jan 28, 2021 |
| Dell          | Latitude E6510              | [08ac5e5f3c](https://linux-hardware.org/?probe=08ac5e5f3c) | Jan 27, 2021 |
| Dell          | Latitude E6510              | [b65c6893f4](https://linux-hardware.org/?probe=b65c6893f4) | Jan 27, 2021 |
| BANGHO        | W240HU/W250HUQ              | [d962a9f838](https://linux-hardware.org/?probe=d962a9f838) | Jan 26, 2021 |
| ASUSTek       | N53SM                       | [197a025cca](https://linux-hardware.org/?probe=197a025cca) | Jan 24, 2021 |
| HP            | EliteBook 840 G1            | [e3a3b60c09](https://linux-hardware.org/?probe=e3a3b60c09) | Jan 23, 2021 |
| Dell          | Latitude 7400               | [36a1fc3e55](https://linux-hardware.org/?probe=36a1fc3e55) | Jan 18, 2021 |
| HP            | Pavilion 17                 | [1eaf2b8cd5](https://linux-hardware.org/?probe=1eaf2b8cd5) | Jan 17, 2021 |
| BANGHO        | CLOUD                       | [0c28cb5279](https://linux-hardware.org/?probe=0c28cb5279) | Jan 17, 2021 |
| BANGHO        | CLOUD                       | [be4e793cc7](https://linux-hardware.org/?probe=be4e793cc7) | Jan 15, 2021 |
| Lenovo        | ThinkBook 15-IML 20RW       | [8b6ac084cb](https://linux-hardware.org/?probe=8b6ac084cb) | Jan 12, 2021 |
| Dell          | Inspiron 3421               | [e8894b6d12](https://linux-hardware.org/?probe=e8894b6d12) | Jan 11, 2021 |
| HP            | Pavilion dv6700             | [a0dd739d75](https://linux-hardware.org/?probe=a0dd739d75) | Jan 09, 2021 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [2f225d37e0](https://linux-hardware.org/?probe=2f225d37e0) | Jan 04, 2021 |
| HP            | Pavilion Laptop 15-cw1xx... | [e253bc608d](https://linux-hardware.org/?probe=e253bc608d) | Jan 03, 2021 |
| Sony          | VPCYB35AL                   | [f82ea2b0dc](https://linux-hardware.org/?probe=f82ea2b0dc) | Jan 03, 2021 |
| Dell          | Inspiron 5559               | [d5fb3b86bb](https://linux-hardware.org/?probe=d5fb3b86bb) | Jan 02, 2021 |
| Insyde        | CherryTrail                 | [5e23a44a4b](https://linux-hardware.org/?probe=5e23a44a4b) | Jan 02, 2021 |
| Insyde        | CherryTrail                 | [d672afb37f](https://linux-hardware.org/?probe=d672afb37f) | Jan 02, 2021 |
| BGH           | C46G                        | [e61ae53564](https://linux-hardware.org/?probe=e61ae53564) | Dec 29, 2020 |
| ASUSTek       | X541UAK                     | [87ed604a48](https://linux-hardware.org/?probe=87ed604a48) | Dec 29, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [ca0a06995e](https://linux-hardware.org/?probe=ca0a06995e) | Dec 28, 2020 |
| ASUSTek       | X541UAK                     | [e77cde62a0](https://linux-hardware.org/?probe=e77cde62a0) | Dec 27, 2020 |
| BGH           | C46G                        | [515be17b75](https://linux-hardware.org/?probe=515be17b75) | Dec 26, 2020 |
| HP            | 250 G7 Notebook PC          | [d0c7e162ef](https://linux-hardware.org/?probe=d0c7e162ef) | Dec 24, 2020 |
| HP            | 250 G7 Notebook PC          | [d20e564de9](https://linux-hardware.org/?probe=d20e564de9) | Dec 24, 2020 |
| Sony          | VPCYB35AL                   | [490e3a1b0a](https://linux-hardware.org/?probe=490e3a1b0a) | Dec 23, 2020 |
| HP            | 250 G7 Notebook PC          | [c282c0612b](https://linux-hardware.org/?probe=c282c0612b) | Dec 22, 2020 |
| HP            | 250 G7 Notebook PC          | [b69724eac9](https://linux-hardware.org/?probe=b69724eac9) | Dec 22, 2020 |
| Apple         | MacBookAir6,1               | [19e45fe217](https://linux-hardware.org/?probe=19e45fe217) | Dec 20, 2020 |
| Exo           | Unknown                     | [a6c445344b](https://linux-hardware.org/?probe=a6c445344b) | Dec 17, 2020 |
| Lenovo        | ThinkPad E470 20H1S0C500    | [84b6435606](https://linux-hardware.org/?probe=84b6435606) | Dec 16, 2020 |
| Lenovo        | ThinkPad E470 20H1S0C500    | [5b00f8ad25](https://linux-hardware.org/?probe=5b00f8ad25) | Dec 16, 2020 |
| Lenovo        | ThinkPad T430 2349DS5       | [806ce0429e](https://linux-hardware.org/?probe=806ce0429e) | Dec 16, 2020 |
| ASUSTek       | X455LJ                      | [54683be664](https://linux-hardware.org/?probe=54683be664) | Dec 15, 2020 |
| ASUSTek       | N56JN                       | [9ef963fbfe](https://linux-hardware.org/?probe=9ef963fbfe) | Dec 14, 2020 |
| Apple         | MacBook3,1                  | [12c6cc3bbb](https://linux-hardware.org/?probe=12c6cc3bbb) | Dec 13, 2020 |
| Apple         | MacBook3,1                  | [7a4425e392](https://linux-hardware.org/?probe=7a4425e392) | Dec 13, 2020 |
| ASUSTek       | X455LJ                      | [9938aa76cf](https://linux-hardware.org/?probe=9938aa76cf) | Dec 10, 2020 |
| Dell          | Latitude 5510               | [0911fc0b09](https://linux-hardware.org/?probe=0911fc0b09) | Dec 10, 2020 |
| Dell          | Inspiron 5567               | [ea61f719d6](https://linux-hardware.org/?probe=ea61f719d6) | Dec 09, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [9114238a33](https://linux-hardware.org/?probe=9114238a33) | Dec 08, 2020 |
| Lenovo        | G70-35 80Q5                 | [4f81abcc73](https://linux-hardware.org/?probe=4f81abcc73) | Dec 07, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [dc0106061d](https://linux-hardware.org/?probe=dc0106061d) | Dec 07, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [0c33131abc](https://linux-hardware.org/?probe=0c33131abc) | Dec 07, 2020 |
| Lenovo        | IdeaPad Z470                | [f09e882b17](https://linux-hardware.org/?probe=f09e882b17) | Dec 07, 2020 |
| Toshiba       | Unknown                     | [dff44dc3ed](https://linux-hardware.org/?probe=dff44dc3ed) | Dec 05, 2020 |
| Samsung       | 550P5C/550P7C               | [452ab979b9](https://linux-hardware.org/?probe=452ab979b9) | Dec 05, 2020 |
| Dell          | Latitude 3410               | [c7c26cc9e6](https://linux-hardware.org/?probe=c7c26cc9e6) | Dec 03, 2020 |
| BANGHO        | MOV                         | [237e3b0449](https://linux-hardware.org/?probe=237e3b0449) | Dec 03, 2020 |
| Lenovo        | G580 20150                  | [c5a6c5f7b8](https://linux-hardware.org/?probe=c5a6c5f7b8) | Nov 30, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [29f2114ef7](https://linux-hardware.org/?probe=29f2114ef7) | Nov 30, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [16c932a6df](https://linux-hardware.org/?probe=16c932a6df) | Nov 29, 2020 |
| Acer          | Aspire A315-54              | [c50041e542](https://linux-hardware.org/?probe=c50041e542) | Nov 28, 2020 |
| System76      | Galago Pro                  | [00eb3fca1a](https://linux-hardware.org/?probe=00eb3fca1a) | Nov 27, 2020 |
| Dell          | Inspiron 5575               | [269f2e1ac1](https://linux-hardware.org/?probe=269f2e1ac1) | Nov 27, 2020 |
| Lenovo        | IdeaPad L340-15API 81LW     | [7d63976540](https://linux-hardware.org/?probe=7d63976540) | Nov 27, 2020 |
| ASUSTek       | GL553VD                     | [46d4c1f45d](https://linux-hardware.org/?probe=46d4c1f45d) | Nov 26, 2020 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | [05988a9297](https://linux-hardware.org/?probe=05988a9297) | Nov 26, 2020 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | [4516048552](https://linux-hardware.org/?probe=4516048552) | Nov 26, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | [cd48e9d406](https://linux-hardware.org/?probe=cd48e9d406) | Nov 25, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | [3c69cde3bb](https://linux-hardware.org/?probe=3c69cde3bb) | Nov 24, 2020 |
| BANGHO        | MOV                         | [466365322d](https://linux-hardware.org/?probe=466365322d) | Nov 20, 2020 |
| HP            | Pavilion x2 Detachable      | [742f34e12f](https://linux-hardware.org/?probe=742f34e12f) | Nov 19, 2020 |
| Sony          | SVF14N11CXB                 | [9f41b6e7c9](https://linux-hardware.org/?probe=9f41b6e7c9) | Nov 19, 2020 |
| HP            | Laptop 15-bs0xx             | [1119089279](https://linux-hardware.org/?probe=1119089279) | Nov 19, 2020 |
| Intel         | H81U                        | [1ce903f88c](https://linux-hardware.org/?probe=1ce903f88c) | Nov 18, 2020 |
| Intel         | H81U                        | [b36636a1c9](https://linux-hardware.org/?probe=b36636a1c9) | Nov 18, 2020 |
| HP            | EliteBook 840 G6            | [790941d1cf](https://linux-hardware.org/?probe=790941d1cf) | Nov 18, 2020 |
| Lenovo        | ThinkPad X200 7459H92       | [242193b8bc](https://linux-hardware.org/?probe=242193b8bc) | Nov 17, 2020 |
| HP            | Pavilion x2 Detachable      | [14c5b0631b](https://linux-hardware.org/?probe=14c5b0631b) | Nov 17, 2020 |
| Apple         | MacBookPro9,2               | [b2fdafbfe7](https://linux-hardware.org/?probe=b2fdafbfe7) | Nov 15, 2020 |
| Dell          | Latitude 3410               | [f5b5e90105](https://linux-hardware.org/?probe=f5b5e90105) | Nov 14, 2020 |
| Dell          | Latitude 3410               | [a3c8f5e5e7](https://linux-hardware.org/?probe=a3c8f5e5e7) | Nov 14, 2020 |
| Dell          | Inspiron 1545               | [3a0512d317](https://linux-hardware.org/?probe=3a0512d317) | Nov 13, 2020 |
| Dell          | Inspiron 1545               | [0c78c7bd9e](https://linux-hardware.org/?probe=0c78c7bd9e) | Nov 13, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [83134c6b81](https://linux-hardware.org/?probe=83134c6b81) | Nov 09, 2020 |
| ASUSTek       | X455LJ                      | [d0085b85ad](https://linux-hardware.org/?probe=d0085b85ad) | Nov 09, 2020 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | [d7328f9c49](https://linux-hardware.org/?probe=d7328f9c49) | Nov 09, 2020 |
| Acer          | Aspire E5-575G              | [a80c58afbd](https://linux-hardware.org/?probe=a80c58afbd) | Nov 08, 2020 |
| HP            | 650                         | [b1b8a15b0c](https://linux-hardware.org/?probe=b1b8a15b0c) | Nov 08, 2020 |
| ASUSTek       | X455LJ                      | [992a71f58b](https://linux-hardware.org/?probe=992a71f58b) | Nov 07, 2020 |
| HP            | Pavilion 17                 | [71e4c06fe1](https://linux-hardware.org/?probe=71e4c06fe1) | Nov 07, 2020 |
| Lenovo        | ThinkPad T470 20HES07C14    | [2892878624](https://linux-hardware.org/?probe=2892878624) | Nov 06, 2020 |
| HP            | Notebook                    | [f62f2870d6](https://linux-hardware.org/?probe=f62f2870d6) | Nov 05, 2020 |
| HP            | Pavilion 17                 | [4749f187d8](https://linux-hardware.org/?probe=4749f187d8) | Nov 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [84d7d9f750](https://linux-hardware.org/?probe=84d7d9f750) | Nov 05, 2020 |
| Sony          | SVS15125PLB                 | [04e1f4654a](https://linux-hardware.org/?probe=04e1f4654a) | Nov 05, 2020 |
| BANGHO        | MAX G0101                   | [59451b99e9](https://linux-hardware.org/?probe=59451b99e9) | Nov 05, 2020 |
| BANGHO        | MAX G0101                   | [0a30aa6677](https://linux-hardware.org/?probe=0a30aa6677) | Nov 05, 2020 |
| Dell          | Latitude 5400               | [014e9b7e76](https://linux-hardware.org/?probe=014e9b7e76) | Nov 04, 2020 |
| HP            | ENVY Notebook               | [19e6729b93](https://linux-hardware.org/?probe=19e6729b93) | Nov 04, 2020 |
| Apple         | MacBookPro8,1               | [c41ddc2f73](https://linux-hardware.org/?probe=c41ddc2f73) | Nov 03, 2020 |
| Apple         | MacBookPro8,1               | [321bdb49c4](https://linux-hardware.org/?probe=321bdb49c4) | Nov 02, 2020 |
| Apple         | MacBookPro9,2               | [7ac11599ba](https://linux-hardware.org/?probe=7ac11599ba) | Nov 02, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [c45660f01d](https://linux-hardware.org/?probe=c45660f01d) | Oct 31, 2020 |
| Lenovo        | IdeaPad 520-15IKB 80YL      | [6ddb0983ac](https://linux-hardware.org/?probe=6ddb0983ac) | Oct 31, 2020 |
| Lenovo        | B50-10 80QR                 | [bd5fbf5911](https://linux-hardware.org/?probe=bd5fbf5911) | Oct 31, 2020 |
| Lenovo        | B50-10 80QR                 | [d40e3d6a1d](https://linux-hardware.org/?probe=d40e3d6a1d) | Oct 31, 2020 |
| ASUSTek       | GL553VD                     | [1ce30fc6e2](https://linux-hardware.org/?probe=1ce30fc6e2) | Oct 31, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Argentina/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 129       | 12.12%  |
| Ubuntu 18.04       | 100       | 9.4%    |
| Ubuntu 22.04       | 69        | 6.48%   |
| Debian 11          | 36        | 3.38%   |
| OpenMandriva 4.2   | 24        | 2.26%   |
| Zorin 15           | 21        | 1.97%   |
| OpenMandriva 4.3   | 20        | 1.88%   |
| Zorin 16           | 17        | 1.6%    |
| BlackPanther 18.1  | 17        | 1.6%    |
| Arch Rolling       | 17        | 1.6%    |
| Pop!_OS 22.04      | 16        | 1.5%    |
| Linux Mint 20.2    | 15        | 1.41%   |
| Fedora 36          | 15        | 1.41%   |
| Arch               | 15        | 1.41%   |
| Manjaro            | 14        | 1.32%   |
| Linux Mint 21.1    | 14        | 1.32%   |
| Linux Mint 20.3    | 14        | 1.32%   |
| Linux Mint 20.1    | 14        | 1.32%   |
| Linux Mint 20      | 14        | 1.32%   |
| Fedora 33          | 13        | 1.22%   |
| Xubuntu 20.04      | 12        | 1.13%   |
| Ubuntu 19.04       | 12        | 1.13%   |
| OpenMandriva 23.03 | 12        | 1.13%   |
| Linux Mint 19.3    | 12        | 1.13%   |
| Debian 10          | 12        | 1.13%   |
| ArcoLinux Rolling  | 11        | 1.03%   |
| Ubuntu 18.10       | 10        | 0.94%   |
| Fedora 37          | 10        | 0.94%   |
| Fedora 34          | 10        | 0.94%   |
| Fedora 32          | 9         | 0.85%   |
| Ubuntu 19.10       | 8         | 0.75%   |
| KDE neon 20.04     | 8         | 0.75%   |
| Fedora 35          | 8         | 0.75%   |
| Xubuntu 18.04      | 7         | 0.66%   |
| Ubuntu 22.10       | 7         | 0.66%   |
| Ubuntu 21.10       | 7         | 0.66%   |
| Pop!_OS 20.04      | 7         | 0.66%   |
| Fedora 38          | 7         | 0.66%   |
| Ubuntu MATE 20.04  | 6         | 0.56%   |
| Ubuntu 20.10       | 6         | 0.56%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 348       | 34.46%  |
| Linux Mint    | 94        | 9.31%   |
| Fedora        | 64        | 6.34%   |
| OpenMandriva  | 61        | 6.04%   |
| Debian        | 60        | 5.94%   |
| Zorin         | 39        | 3.86%   |
| Pop!_OS       | 38        | 3.76%   |
| Endless       | 34        | 3.37%   |
| Arch          | 30        | 2.97%   |
| Xubuntu       | 25        | 2.48%   |
| Manjaro       | 25        | 2.48%   |
| BlackPanther  | 17        | 1.68%   |
| Elementary    | 15        | 1.49%   |
| Kubuntu       | 13        | 1.29%   |
| KDE neon      | 12        | 1.19%   |
| ArcoLinux     | 12        | 1.19%   |
| Lubuntu       | 11        | 1.09%   |
| Ubuntu Budgie | 10        | 0.99%   |
| ROSA          | 10        | 0.99%   |
| openSUSE      | 8         | 0.79%   |
| LMDE          | 7         | 0.69%   |
| EndeavourOS   | 7         | 0.69%   |
| Ubuntu MATE   | 6         | 0.59%   |
| Peppermint    | 6         | 0.59%   |
| Kali          | 5         | 0.5%    |
| Huayra        | 5         | 0.5%    |
| Ubuntu Unity  | 4         | 0.4%    |
| Nobara        | 4         | 0.4%    |
| Gentoo        | 4         | 0.4%    |
| Parrot        | 3         | 0.3%    |
| LinuxFX       | 3         | 0.3%    |
| Clear Linux   | 3         | 0.3%    |
| Void Linux    | 2         | 0.2%    |
| UbuntuDDE     | 2         | 0.2%    |
| CentOS        | 2         | 0.2%    |
| Artix         | 2         | 0.2%    |
| Xero          | 1         | 0.1%    |
| Ultramarine   | 1         | 0.1%    |
| Ubuntu Studio | 1         | 0.1%    |
| SteamOS       | 1         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 23        | 1.98%   |
| 5.4.0-42-generic         | 21        | 1.81%   |
| 5.16.7-desktop-1omv4003  | 20        | 1.73%   |
| 4.18.16-desktop-1bP      | 17        | 1.47%   |
| 5.4.0-26-generic         | 15        | 1.29%   |
| 5.3.0-40-generic         | 12        | 1.04%   |
| 6.2.6-desktop-1omv2390   | 11        | 0.95%   |
| 5.4.0-52-generic         | 11        | 0.95%   |
| 5.4.0-19-generic         | 10        | 0.86%   |
| 5.15.0-52-generic        | 10        | 0.86%   |
| 5.8.0-14-generic         | 9         | 0.78%   |
| 5.4.0-29-generic         | 9         | 0.78%   |
| 5.4.0-48-generic         | 8         | 0.69%   |
| 5.4.0-40-generic         | 8         | 0.69%   |
| 5.11.0-37-generic        | 8         | 0.69%   |
| 4.18.0-15-generic        | 8         | 0.69%   |
| 5.8.0-43-generic         | 7         | 0.6%    |
| 5.4.0-91-generic         | 7         | 0.6%    |
| 5.4.0-72-generic         | 7         | 0.6%    |
| 5.4.0-58-generic         | 7         | 0.6%    |
| 5.3.0-46-generic         | 7         | 0.6%    |
| 5.3.0-28-generic         | 7         | 0.6%    |
| 5.15.0-46-generic        | 7         | 0.6%    |
| 5.15.0-41-generic        | 7         | 0.6%    |
| 5.11.0-27-generic        | 7         | 0.6%    |
| 6.2.0-26-generic         | 6         | 0.52%   |
| 5.8.0-7630-generic       | 6         | 0.52%   |
| 5.4.0-73-generic         | 6         | 0.52%   |
| 5.4.0-47-generic         | 6         | 0.52%   |
| 5.4.0-45-generic         | 6         | 0.52%   |
| 5.4.0-37-generic         | 6         | 0.52%   |
| 5.3.0-42-generic         | 6         | 0.52%   |
| 5.15.0-48-generic        | 6         | 0.52%   |
| 5.13.0-40-generic        | 6         | 0.52%   |
| 5.13.0-35-generic        | 6         | 0.52%   |
| 5.10.0-21-amd64          | 6         | 0.52%   |
| 4.18.0-17-generic        | 6         | 0.52%   |
| 6.1.1-desktop-1omv2290   | 5         | 0.43%   |
| 5.8.0-59-generic         | 5         | 0.43%   |
| 5.4.0-74-generic         | 5         | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 193       | 17.58%  |
| 5.15.0  | 93        | 8.47%   |
| 4.15.0  | 63        | 5.74%   |
| 5.3.0   | 58        | 5.28%   |
| 5.8.0   | 55        | 5.01%   |
| 5.11.0  | 40        | 3.64%   |
| 5.10.0  | 39        | 3.55%   |
| 5.19.0  | 35        | 3.19%   |
| 5.13.0  | 34        | 3.1%    |
| 5.0.0   | 31        | 2.82%   |
| 4.18.0  | 28        | 2.55%   |
| 5.10.14 | 23        | 2.09%   |
| 5.16.7  | 20        | 1.82%   |
| 4.19.0  | 20        | 1.82%   |
| 4.18.16 | 17        | 1.55%   |
| 6.2.6   | 15        | 1.37%   |
| 6.2.0   | 12        | 1.09%   |
| 6.1.0   | 9         | 0.82%   |
| 5.14.0  | 7         | 0.64%   |
| 6.1.1   | 6         | 0.55%   |
| 5.17.5  | 6         | 0.55%   |
| 5.18.16 | 5         | 0.46%   |
| 5.18.0  | 5         | 0.46%   |
| 5.15.5  | 5         | 0.46%   |
| 5.9.10  | 4         | 0.36%   |
| 5.18.5  | 4         | 0.36%   |
| 5.15.8  | 4         | 0.36%   |
| 5.11.12 | 4         | 0.36%   |
| 4.9.20  | 4         | 0.36%   |
| 6.4.9   | 3         | 0.27%   |
| 6.4.2   | 3         | 0.27%   |
| 6.4.11  | 3         | 0.27%   |
| 6.3.5   | 3         | 0.27%   |
| 6.2.8   | 3         | 0.27%   |
| 6.0.8   | 3         | 0.27%   |
| 6.0.15  | 3         | 0.27%   |
| 6.0.12  | 3         | 0.27%   |
| 5.8.6   | 3         | 0.27%   |
| 5.8.16  | 3         | 0.27%   |
| 5.19.14 | 3         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 200       | 18.5%   |
| 5.15    | 120       | 11.1%   |
| 5.10    | 73        | 6.75%   |
| 5.8     | 68        | 6.29%   |
| 4.15    | 63        | 5.83%   |
| 5.3     | 58        | 5.37%   |
| 5.11    | 53        | 4.9%    |
| 5.19    | 50        | 4.63%   |
| 4.18    | 47        | 4.35%   |
| 5.13    | 44        | 4.07%   |
| 6.2     | 38        | 3.52%   |
| 5.16    | 33        | 3.05%   |
| 5.0     | 33        | 3.05%   |
| 6.1     | 27        | 2.5%    |
| 5.18    | 26        | 2.41%   |
| 4.19    | 22        | 2.04%   |
| 6.0     | 19        | 1.76%   |
| 5.14    | 15        | 1.39%   |
| 5.17    | 13        | 1.2%    |
| 5.9     | 12        | 1.11%   |
| 6.4     | 11        | 1.02%   |
| 6.3     | 11        | 1.02%   |
| 5.6     | 9         | 0.83%   |
| 4.9     | 8         | 0.74%   |
| 5.7     | 7         | 0.65%   |
| 5.12    | 6         | 0.56%   |
| 5.5     | 3         | 0.28%   |
| 6.5     | 2         | 0.19%   |
| 4.13    | 2         | 0.19%   |
| 4.1     | 2         | 0.19%   |
| 3.10    | 2         | 0.19%   |
| 4.4     | 1         | 0.09%   |
| 4.17    | 1         | 0.09%   |
| 4.10    | 1         | 0.09%   |
| 3.16    | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 937       | 94.74%  |
| i686   | 52        | 5.26%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| GNOME            | 446       | 43.77%  |
| KDE5             | 148       | 14.52%  |
| Unknown          | 109       | 10.7%   |
| XFCE             | 96        | 9.42%   |
| X-Cinnamon       | 63        | 6.18%   |
| MATE             | 44        | 4.32%   |
| KDE              | 17        | 1.67%   |
| Pantheon         | 14        | 1.37%   |
| LXDE             | 13        | 1.28%   |
| LXQt             | 12        | 1.18%   |
| Budgie           | 12        | 1.18%   |
| Cinnamon         | 10        | 0.98%   |
| i3               | 7         | 0.69%   |
| KDE4             | 6         | 0.59%   |
| Unity            | 4         | 0.39%   |
| Deepin           | 4         | 0.39%   |
| xmonad           | 2         | 0.2%    |
| GNOME Flashback  | 2         | 0.2%    |
| bspwm            | 2         | 0.2%    |
| sway             | 1         | 0.1%    |
| qtile            | 1         | 0.1%    |
| openbox          | 1         | 0.1%    |
| lightdm-xsession | 1         | 0.1%    |
| i3-with-shmlog   | 1         | 0.1%    |
| Hyprland         | 1         | 0.1%    |
| Cutefish         | 1         | 0.1%    |
| awesome          | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 774       | 76.56%  |
| Wayland | 161       | 15.92%  |
| Unknown | 69        | 6.82%   |
| Tty     | 7         | 0.69%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 523       | 51.53%  |
| SDDM    | 129       | 12.71%  |
| GDM3    | 112       | 11.03%  |
| GDM     | 110       | 10.84%  |
| LightDM | 95        | 9.36%   |
| TDM     | 32        | 3.15%   |
| KDM     | 6         | 0.59%   |
| LXDM    | 3         | 0.3%    |
| XDM     | 2         | 0.2%    |
| GREETD  | 2         | 0.2%    |
| SLiM    | 1         | 0.1%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| es_AR       | 521       | 51.38%  |
| en_US       | 248       | 24.46%  |
| Unknown     | 120       | 11.83%  |
| es_ES       | 61        | 6.02%   |
| es_MX       | 24        | 2.37%   |
| C           | 14        | 1.38%   |
| en_GB       | 9         | 0.89%   |
| pt_BR       | 5         | 0.49%   |
| it_IT       | 2         | 0.2%    |
| es_US       | 2         | 0.2%    |
| es_CL       | 2         | 0.2%    |
| POSIX       | 1         | 0.1%    |
| fr_FR       | 1         | 0.1%    |
| es_UY       | 1         | 0.1%    |
| es_AR.UtF-8 | 1         | 0.1%    |
| en_CA       | 1         | 0.1%    |
| en_AG       | 1         | 0.1%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 506       | 50.2%   |
| EFI  | 502       | 49.8%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 786       | 77.82%  |
| Overlay | 85        | 8.42%   |
| Btrfs   | 76        | 7.52%   |
| Unknown | 31        | 3.07%   |
| Tmpfs   | 15        | 1.49%   |
| Xfs     | 8         | 0.79%   |
| Zfs     | 4         | 0.4%    |
| Ext2    | 3         | 0.3%    |
| Ext3    | 1         | 0.1%    |
| Aufs    | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 558       | 55.36%  |
| GPT     | 339       | 33.63%  |
| MBR     | 111       | 11.01%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 889       | 88.99%  |
| Yes       | 110       | 11.01%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 713       | 71.44%  |
| Yes       | 285       | 28.56%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 223       | 22.55%  |
| Hewlett-Packard         | 134       | 13.55%  |
| Dell                    | 128       | 12.94%  |
| ASUSTek Computer        | 119       | 12.03%  |
| Acer                    | 52        | 5.26%   |
| BANGHO                  | 40        | 4.04%   |
| Toshiba                 | 33        | 3.34%   |
| Exo                     | 29        | 2.93%   |
| Samsung Electronics     | 28        | 2.83%   |
| Positivo                | 25        | 2.53%   |
| Sony                    | 17        | 1.72%   |
| Intel                   | 14        | 1.42%   |
| MSI                     | 13        | 1.31%   |
| Apple                   | 13        | 1.31%   |
| Compal                  | 8         | 0.81%   |
| Unknown                 | 8         | 0.81%   |
| Coradir                 | 7         | 0.71%   |
| Clevo                   | 7         | 0.71%   |
| Standard                | 5         | 0.51%   |
| NSX                     | 5         | 0.51%   |
| NOBLEX                  | 5         | 0.51%   |
| System76                | 4         | 0.4%    |
| Juana Manso             | 4         | 0.4%    |
| HUAWEI                  | 4         | 0.4%    |
| Advantec                | 4         | 0.4%    |
| A-DATA Technology       | 4         | 0.4%    |
| PCBOX                   | 3         | 0.3%    |
| Gigabyte Technology     | 3         | 0.3%    |
| Radio Victoria Fueguina | 2         | 0.2%    |
| Quanta                  | 2         | 0.2%    |
| Packard Bell            | 2         | 0.2%    |
| Novatech                | 2         | 0.2%    |
| LG Electronics          | 2         | 0.2%    |
| Kelyx Argentina         | 2         | 0.2%    |
| iQual                   | 2         | 0.2%    |
| Garbarino SAIC          | 2         | 0.2%    |
| Compaq                  | 2         | 0.2%    |
| BGH                     | 2         | 0.2%    |
| AIR                     | 2         | 0.2%    |
| SiS                     | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 22        | 2.22%   |
| BANGHO MOV                                 | 10        | 1.01%   |
| Lenovo V330-15IKB 81AX                     | 9         | 0.91%   |
| HP Notebook                                | 8         | 0.81%   |
| Lenovo ThinkPad L15 Gen 2 20X4S27200       | 7         | 0.71%   |
| Lenovo G470 20078                          | 7         | 0.71%   |
| HP Laptop 15-bs0xx                         | 7         | 0.71%   |
| Coradir Coradir/ES10IS5                    | 7         | 0.71%   |
| BANGHO MAX G0101                           | 6         | 0.61%   |
| ASUS VivoBook_ASUSLaptop X509JA_X509JA     | 6         | 0.61%   |
| Intel powered classmate PC                 | 5         | 0.51%   |
| HP Pavilion dv6                            | 5         | 0.51%   |
| Exo CloudbookE15                           | 5         | 0.51%   |
| Dell Latitude 3520                         | 5         | 0.51%   |
| Dell Inspiron 1525                         | 5         | 0.51%   |
| BANGHO W240HU/W250HUQ                      | 5         | 0.51%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 5         | 0.51%   |
| ASUS K53E                                  | 5         | 0.51%   |
| Samsung 300E4C/300E5C/300E7C               | 4         | 0.4%    |
| Lenovo ThinkPad T430 2349DS5               | 4         | 0.4%    |
| Lenovo IdeaPad 320-15ABR 80XS              | 4         | 0.4%    |
| Lenovo G550 2958                           | 4         | 0.4%    |
| Juana Manso SF20GM7                        | 4         | 0.4%    |
| HP Pavilion Notebook                       | 4         | 0.4%    |
| HP OMEN by Laptop 15-ce0xx                 | 4         | 0.4%    |
| HP G42                                     | 4         | 0.4%    |
| HP 250 G7 Notebook PC                      | 4         | 0.4%    |
| HP 250 G6 Notebook PC                      | 4         | 0.4%    |
| Dell Latitude 7490                         | 4         | 0.4%    |
| Dell Inspiron 3505                         | 4         | 0.4%    |
| Dell Inspiron 3421                         | 4         | 0.4%    |
| ASUS X555LAB                               | 4         | 0.4%    |
| ASUS X541UAK                               | 4         | 0.4%    |
| ASUS VivoBook_ASUSLaptop X515EA_X515EA     | 4         | 0.4%    |
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 4         | 0.4%    |
| Apple MacBookPro9,2                        | 4         | 0.4%    |
| Toshiba Satellite-L845                     | 3         | 0.3%    |
| Samsung R430/P430/R480                     | 3         | 0.3%    |
| Samsung 300E4A/300E5A/300E7A/3430EA/3530EA | 3         | 0.3%    |
| Samsung 300E4A/300E5A/300E7A               | 3         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 85        | 8.59%   |
| Dell Inspiron       | 65        | 6.57%   |
| Lenovo IdeaPad      | 47        | 4.75%   |
| Dell Latitude       | 47        | 4.75%   |
| Acer Aspire         | 43        | 4.35%   |
| ASUS VivoBook       | 40        | 4.04%   |
| HP Pavilion         | 38        | 3.84%   |
| HP Laptop           | 22        | 2.22%   |
| Unknown             | 22        | 2.22%   |
| Toshiba Satellite   | 20        | 2.02%   |
| Exo Smart           | 14        | 1.42%   |
| Lenovo ThinkBook    | 13        | 1.31%   |
| HP 250              | 11        | 1.11%   |
| BANGHO MAX          | 11        | 1.11%   |
| BANGHO MOV          | 10        | 1.01%   |
| Lenovo V330-15IKB   | 9         | 0.91%   |
| HP Compaq           | 9         | 0.91%   |
| HP Notebook         | 8         | 0.81%   |
| HP EliteBook        | 8         | 0.81%   |
| Lenovo G470         | 7         | 0.71%   |
| Coradir Coradir     | 7         | 0.71%   |
| ASUS ZenBook        | 7         | 0.71%   |
| Samsung 300E4A      | 6         | 0.61%   |
| HP ProBook          | 6         | 0.61%   |
| ASUS ASUS           | 6         | 0.61%   |
| Samsung R430        | 5         | 0.51%   |
| Lenovo Legion       | 5         | 0.51%   |
| Intel powered       | 5         | 0.51%   |
| HP OMEN             | 5         | 0.51%   |
| Exo CloudbookE15    | 5         | 0.51%   |
| Dell XPS            | 5         | 0.51%   |
| BANGHO W240HU       | 5         | 0.51%   |
| ASUS K53E           | 5         | 0.51%   |
| Samsung 300E4C      | 4         | 0.4%    |
| Lenovo Yoga         | 4         | 0.4%    |
| Lenovo G550         | 4         | 0.4%    |
| Juana Manso SF20GM7 | 4         | 0.4%    |
| HP G42              | 4         | 0.4%    |
| HP ENVY             | 4         | 0.4%    |
| HP 240              | 4         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 99        | 10.01%  |
| 2017    | 99        | 10.01%  |
| 2012    | 95        | 9.61%   |
| 2019    | 85        | 8.59%   |
| 2011    | 76        | 7.68%   |
| 2020    | 75        | 7.58%   |
| 2010    | 64        | 6.47%   |
| 2014    | 61        | 6.17%   |
| 2018    | 60        | 6.07%   |
| 2013    | 57        | 5.76%   |
| 2016    | 52        | 5.26%   |
| 2015    | 48        | 4.85%   |
| 2008    | 39        | 3.94%   |
| 2009    | 28        | 2.83%   |
| 2007    | 17        | 1.72%   |
| 2022    | 15        | 1.52%   |
| 2006    | 10        | 1.01%   |
| Unknown | 6         | 0.61%   |
| 2023    | 1         | 0.1%    |
| 2005    | 1         | 0.1%    |
| 2004    | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 989       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 901       | 90.46%  |
| Enabled  | 95        | 9.54%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 987       | 99.8%   |
| Yes  | 2         | 0.2%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 279       | 27.93%  |
| 3.01-4.0    | 258       | 25.83%  |
| 8.01-16.0   | 170       | 17.02%  |
| 16.01-24.0  | 111       | 11.11%  |
| 1.01-2.0    | 91        | 9.11%   |
| 32.01-64.0  | 37        | 3.7%    |
| 2.01-3.0    | 23        | 2.3%    |
| 0.51-1.0    | 17        | 1.7%    |
| 24.01-32.0  | 9         | 0.9%    |
| 64.01-256.0 | 4         | 0.4%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 393       | 36.29%  |
| 2.01-3.0   | 266       | 24.56%  |
| 4.01-8.0   | 139       | 12.83%  |
| 3.01-4.0   | 127       | 11.73%  |
| 0.51-1.0   | 93        | 8.59%   |
| 8.01-16.0  | 50        | 4.62%   |
| 0.01-0.5   | 11        | 1.02%   |
| 16.01-24.0 | 3         | 0.28%   |
| 24.01-32.0 | 1         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 753       | 75.22%  |
| 2      | 221       | 22.08%  |
| 3      | 19        | 1.9%    |
| 0      | 8         | 0.8%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 640       | 64.32%  |
| Yes       | 355       | 35.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 828       | 83.55%  |
| No        | 163       | 16.45%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 969       | 97.88%  |
| No        | 21        | 2.12%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 689       | 69.39%  |
| No        | 304       | 30.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country   | Notebooks | Percent |
|-----------|-----------|---------|
| Argentina | 989       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                        | Notebooks | Percent |
|-----------------------------|-----------|---------|
| Buenos Aires                | 224       | 21.58%  |
| Córdoba                    | 77        | 7.42%   |
| Rosario                     | 36        | 3.47%   |
| La Plata                    | 29        | 2.79%   |
| Mar del Plata               | 26        | 2.5%    |
| Mendoza                     | 18        | 1.73%   |
| Corrientes                  | 15        | 1.45%   |
| San Miguel de Tucumán      | 14        | 1.35%   |
| Lanus                       | 13        | 1.25%   |
| Avellaneda                  | 12        | 1.16%   |
| Ituzaingo                   | 10        | 0.96%   |
| Villa Ballester             | 9         | 0.87%   |
| Santa Fe                    | 9         | 0.87%   |
| San Martín de los Andes    | 9         | 0.87%   |
| Salta                       | 9         | 0.87%   |
| Quilmes                     | 9         | 0.87%   |
| Olivos                      | 9         | 0.87%   |
| Tandil                      | 8         | 0.77%   |
| Resistencia                 | 8         | 0.77%   |
| Ramos Mejia                 | 8         | 0.77%   |
| Posadas                     | 8         | 0.77%   |
| Paraná                     | 8         | 0.77%   |
| Bariloche                   | 8         | 0.77%   |
| San Francisco               | 7         | 0.67%   |
| Florencio Varela            | 7         | 0.67%   |
| Bahía Blanca               | 7         | 0.67%   |
| Vicente Lopez               | 6         | 0.58%   |
| San Nicolás de los Arroyos | 6         | 0.58%   |
| San Juan                    | 6         | 0.58%   |
| Río Gallegos               | 6         | 0.58%   |
| Lomas de Zamora             | 6         | 0.58%   |
| Burzaco                     | 6         | 0.58%   |
| Villa Carlos Paz            | 5         | 0.48%   |
| Viedma                      | 5         | 0.48%   |
| Tigre                       | 5         | 0.48%   |
| Santa Rosa                  | 5         | 0.48%   |
| San Isidro                  | 5         | 0.48%   |
| Rio Tercero                 | 5         | 0.48%   |
| Necochea                    | 5         | 0.48%   |
| Mariano Moreno              | 5         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 220       | 269    | 18.69%  |
| Seagate                     | 160       | 187    | 13.59%  |
| Kingston                    | 160       | 193    | 13.59%  |
| Toshiba                     | 132       | 167    | 11.21%  |
| Samsung Electronics         | 107       | 136    | 9.09%   |
| Unknown                     | 54        | 67     | 4.59%   |
| HGST                        | 41        | 44     | 3.48%   |
| SK hynix                    | 39        | 44     | 3.31%   |
| Sandisk                     | 38        | 60     | 3.23%   |
| Hitachi                     | 35        | 40     | 2.97%   |
| Crucial                     | 20        | 25     | 1.7%    |
| Micron Technology           | 19        | 23     | 1.61%   |
| Intel                       | 16        | 32     | 1.36%   |
| A-DATA Technology           | 16        | 17     | 1.36%   |
| Gigabyte Technology         | 11        | 19     | 0.93%   |
| KIOXIA                      | 9         | 9      | 0.76%   |
| Hewlett-Packard             | 7         | 9      | 0.59%   |
| China                       | 7         | 7      | 0.59%   |
| PNY                         | 5         | 8      | 0.42%   |
| Patriot                     | 5         | 6      | 0.42%   |
| Kimtigo                     | 5         | 5      | 0.42%   |
| XPG                         | 4         | 5      | 0.34%   |
| Neo                         | 4         | 4      | 0.34%   |
| Kingston Technology Company | 4         | 4      | 0.34%   |
| HS-SSD-C100                 | 4         | 7      | 0.34%   |
| Unknown                     | 4         | 4      | 0.34%   |
| Union Memory                | 3         | 3      | 0.25%   |
| Lexar                       | 3         | 3      | 0.25%   |
| Apple                       | 3         | 3      | 0.25%   |
| Union Memory (Shenzhen)     | 2         | 2      | 0.17%   |
| SPCC                        | 2         | 2      | 0.17%   |
| Silicon Motion              | 2         | 2      | 0.17%   |
| Realtek Semiconductor       | 2         | 2      | 0.17%   |
| LITEONIT                    | 2         | 2      | 0.17%   |
| LITEON                      | 2         | 2      | 0.17%   |
| FORESEE                     | 2         | 2      | 0.17%   |
| Corsair                     | 2         | 2      | 0.17%   |
| Colorful                    | 2         | 2      | 0.17%   |
| ADATA Technology            | 2         | 2      | 0.17%   |
| ZTE                         | 1         | 1      | 0.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD     | 54        | 4.47%   |
| Seagate ST1000LM035-1RK172 1TB      | 41        | 3.39%   |
| Toshiba MQ01ABF050 500GB            | 27        | 2.24%   |
| Kingston SA400S37480G 480GB SSD     | 27        | 2.24%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 26        | 2.15%   |
| Toshiba MQ01ABD100 1TB              | 24        | 1.99%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 17        | 1.41%   |
| Unknown MMC Card  32GB              | 17        | 1.41%   |
| Toshiba MQ04ABF100 1TB              | 14        | 1.16%   |
| Seagate ST500LT012-1DG142 500GB     | 11        | 0.91%   |
| HGST HTS721010A9E630 1TB            | 10        | 0.83%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD    | 9         | 0.75%   |
| WDC WD10JPVX-60JC3T1 1TB            | 9         | 0.75%   |
| Seagate ST9500325AS 500GB           | 8         | 0.66%   |
| Seagate ST500LM030-2E717D 500GB     | 8         | 0.66%   |
| Kingston SNVS500G 500GB             | 8         | 0.66%   |
| Kingston SA400S37960G 960GB SSD     | 8         | 0.66%   |
| Kingston SA400S37120G 120GB SSD     | 8         | 0.66%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 7         | 0.58%   |
| Toshiba MQ01ABD032 320GB            | 7         | 0.58%   |
| Seagate ST320LM001 HN-M320MBB 320GB | 7         | 0.58%   |
| Seagate ST1000LM048-2E7172 1TB      | 7         | 0.58%   |
| Samsung MZALQ256HBJD-00BL1 256GB    | 7         | 0.58%   |
| Kingston SV300S37A240G 240GB SSD    | 7         | 0.58%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 6         | 0.5%    |
| Unknown MMC Card  64GB              | 6         | 0.5%    |
| Toshiba MK6475GSX 640GB             | 6         | 0.5%    |
| Samsung NVMe SSD Drive 512GB        | 6         | 0.5%    |
| Kingston SUV400S37240G 240GB SSD    | 6         | 0.5%    |
| HGST HTS725050A7E630 500GB          | 6         | 0.5%    |
| Crucial CT240BX500SSD1 240GB        | 6         | 0.5%    |
| A-DATA SU630 240GB SSD              | 6         | 0.5%    |
| WDC WDS500G2B0A-00SM50 500GB SSD    | 5         | 0.41%   |
| Seagate ST500LT012-9WS142 500GB     | 5         | 0.41%   |
| Hitachi HTS545050B9A300 500GB       | 5         | 0.41%   |
| HGST HTS545050A7E680 500GB          | 5         | 0.41%   |
| HGST HTS545050A7E380 500GB          | 5         | 0.41%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 4         | 0.33%   |
| WDC WD5000LPCX-22VHAT0 500GB        | 4         | 0.33%   |
| WDC WD5000BPVT-22HXZT3 500GB        | 4         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 156       | 181    | 29.55%  |
| WDC                 | 151       | 176    | 28.6%   |
| Toshiba             | 115       | 147    | 21.78%  |
| HGST                | 41        | 44     | 7.77%   |
| Hitachi             | 35        | 40     | 6.63%   |
| Samsung Electronics | 24        | 27     | 4.55%   |
| Unknown             | 4         | 4      | 0.76%   |
| USB3.0              | 1         | 1      | 0.19%   |
| Fujitsu             | 1         | 1      | 0.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 137       | 168    | 38.59%  |
| WDC                 | 51        | 63     | 14.37%  |
| Samsung Electronics | 24        | 39     | 6.76%   |
| SanDisk             | 20        | 26     | 5.63%   |
| Crucial             | 19        | 24     | 5.35%   |
| A-DATA Technology   | 13        | 13     | 3.66%   |
| Gigabyte Technology | 10        | 18     | 2.82%   |
| SK hynix            | 8         | 9      | 2.25%   |
| Micron Technology   | 6         | 8      | 1.69%   |
| Toshiba             | 5         | 5      | 1.41%   |
| PNY                 | 5         | 8      | 1.41%   |
| Kimtigo             | 5         | 5      | 1.41%   |
| Patriot             | 4         | 5      | 1.13%   |
| Intel               | 4         | 4      | 1.13%   |
| Hewlett-Packard     | 4         | 7      | 1.13%   |
| China               | 4         | 4      | 1.13%   |
| Seagate             | 3         | 5      | 0.85%   |
| Lexar               | 3         | 3      | 0.85%   |
| SPCC                | 2         | 2      | 0.56%   |
| LITEONIT            | 2         | 2      | 0.56%   |
| HS-SSD-C100         | 2         | 5      | 0.56%   |
| FORESEE             | 2         | 2      | 0.56%   |
| Corsair             | 2         | 2      | 0.56%   |
| Colorful            | 2         | 2      | 0.56%   |
| Apple               | 2         | 2      | 0.56%   |
| Unknown             | 2         | 2      | 0.56%   |
| XrayDisk            | 1         | 1      | 0.28%   |
| WDC WDS2            | 1         | 1      | 0.28%   |
| Transcend           | 1         | 1      | 0.28%   |
| Team                | 1         | 1      | 0.28%   |
| SMI                 | 1         | 1      | 0.28%   |
| Ramaxel Technology  | 1         | 1      | 0.28%   |
| OCZ                 | 1         | 1      | 0.28%   |
| NGFF                | 1         | 2      | 0.28%   |
| Netac               | 1         | 2      | 0.28%   |
| Neo                 | 1         | 1      | 0.28%   |
| Mushkin             | 1         | 1      | 0.28%   |
| MMY                 | 1         | 1      | 0.28%   |
| LITEON              | 1         | 1      | 0.28%   |
| JMicron Technology  | 1         | 1      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 518       | 621    | 45.68%  |
| SSD     | 335       | 449    | 29.54%  |
| NVMe    | 218       | 300    | 19.22%  |
| MMC     | 50        | 64     | 4.41%   |
| Unknown | 13        | 12     | 1.15%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 772       | 1069   | 73.31%  |
| NVMe | 218       | 300    | 20.7%   |
| MMC  | 50        | 64     | 4.75%   |
| SAS  | 13        | 13     | 1.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 567       | 739    | 68.81%  |
| 0.51-1.0   | 248       | 321    | 30.1%   |
| 1.01-2.0   | 9         | 10     | 1.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 321       | 31.07%  |
| 251-500        | 270       | 26.14%  |
| 501-1000       | 165       | 15.97%  |
| 1-20           | 69        | 6.68%   |
| 51-100         | 64        | 6.2%    |
| 1001-2000      | 53        | 5.13%   |
| 21-50          | 49        | 4.74%   |
| Unknown        | 29        | 2.81%   |
| More than 3000 | 8         | 0.77%   |
| 2001-3000      | 5         | 0.48%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 432       | 40.26%  |
| 21-50     | 210       | 19.57%  |
| 101-250   | 153       | 14.26%  |
| 51-100    | 134       | 12.49%  |
| 251-500   | 70        | 6.52%   |
| 501-1000  | 34        | 3.17%   |
| Unknown   | 29        | 2.7%    |
| 1001-2000 | 9         | 0.84%   |
| 2001-3000 | 2         | 0.19%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 6         | 6      | 7.23%   |
| WDC WD5000BPVT-22HXZT3 500GB        | 3         | 3      | 3.61%   |
| Toshiba MQ01ABF050 500GB            | 3         | 3      | 3.61%   |
| Toshiba MQ01ABD100 1TB              | 3         | 6      | 3.61%   |
| HGST HTS541010A9E680 1TB            | 3         | 3      | 3.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 2         | 2      | 2.41%   |
| Toshiba MQ01ABD050 500GB            | 2         | 2      | 2.41%   |
| Toshiba MK7559GSXP 752GB            | 2         | 2      | 2.41%   |
| Toshiba MK1665GSX 160GB             | 2         | 2      | 2.41%   |
| Seagate ST9500325AS 500GB           | 2         | 2      | 2.41%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 5      | 2.41%   |
| Samsung Electronics HN-M101MBB 1TB  | 2         | 2      | 2.41%   |
| Kingston SA400S37240G 240GB SSD     | 2         | 2      | 2.41%   |
| HGST HTS725050A7E630 500GB          | 2         | 2      | 2.41%   |
| HGST HTS721010A9E630 1TB            | 2         | 4      | 2.41%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 1         | 1      | 1.2%    |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 1         | 1      | 1.2%    |
| WDC WD5000BEVT-22A0RT0 500GB        | 1         | 1      | 1.2%    |
| WDC WD3200BPVT-00JJ5T0 320GB        | 1         | 1      | 1.2%    |
| WDC WD3200BEKT-60F3T1 320GB         | 1         | 1      | 1.2%    |
| WDC WD2500BEVT-75A23T0 250GB        | 1         | 1      | 1.2%    |
| WDC WD2500BEKT-75PVMT0 250GB        | 1         | 2      | 1.2%    |
| WDC WD1200BEVS-60UST0 120GB         | 1         | 1      | 1.2%    |
| WDC WD10JPVX-22JC3T0 1TB            | 1         | 1      | 1.2%    |
| WDC WD Green 2.5 240GB SSD          | 1         | 1      | 1.2%    |
| Toshiba MQ04ABF100 1TB              | 1         | 1      | 1.2%    |
| Toshiba MQ01ABD032 320GB            | 1         | 1      | 1.2%    |
| Toshiba MK6475GSX 640GB             | 1         | 1      | 1.2%    |
| Toshiba MK3265GSXN 320GB            | 1         | 1      | 1.2%    |
| Toshiba MK2576GSX 250GB             | 1         | 1      | 1.2%    |
| Toshiba MK2556GSY 250GB             | 1         | 1      | 1.2%    |
| SMI SSD DISK 512GB                  | 1         | 1      | 1.2%    |
| Seagate ST960813AS 64GB             | 1         | 1      | 1.2%    |
| Seagate ST960812A 64GB              | 1         | 1      | 1.2%    |
| Seagate ST9320325AS 320GB           | 1         | 1      | 1.2%    |
| Seagate ST9160314AS 160GB           | 1         | 1      | 1.2%    |
| Seagate ST500LT012-9WS142 500GB     | 1         | 1      | 1.2%    |
| Seagate ST320LT020-9YG142 320GB     | 1         | 1      | 1.2%    |
| Seagate ST320LM001 HN-M320MBB 320GB | 1         | 1      | 1.2%    |
| Seagate ST250LM004 HN-M250MBB 250GB | 1         | 1      | 1.2%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 23     | 24.1%   |
| Toshiba             | 18        | 21     | 21.69%  |
| WDC                 | 15        | 16     | 18.07%  |
| HGST                | 9         | 11     | 10.84%  |
| Hitachi             | 7         | 9      | 8.43%   |
| Samsung Electronics | 6         | 6      | 7.23%   |
| Kingston            | 5         | 5      | 6.02%   |
| SMI                 | 1         | 1      | 1.2%    |
| LITEONIT            | 1         | 1      | 1.2%    |
| A-DATA Technology   | 1         | 1      | 1.2%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 23     | 29.85%  |
| Toshiba             | 18        | 21     | 26.87%  |
| WDC                 | 10        | 11     | 14.93%  |
| HGST                | 9         | 11     | 13.43%  |
| Hitachi             | 7         | 9      | 10.45%  |
| Samsung Electronics | 3         | 3      | 4.48%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 66        | 78     | 80.49%  |
| SSD  | 15        | 15     | 18.29%  |
| NVMe | 1         | 1      | 1.22%   |

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
| Detected | 592       | 827    | 57.03%  |
| Works    | 362       | 521    | 34.87%  |
| Malfunc  | 80        | 94     | 7.71%   |
| Failed   | 4         | 4      | 0.39%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 741       | 68.36%  |
| AMD                              | 104       | 9.59%   |
| Samsung Electronics              | 60        | 5.54%   |
| SanDisk                          | 38        | 3.51%   |
| SK hynix                         | 31        | 2.86%   |
| Kingston Technology Company      | 27        | 2.49%   |
| Toshiba America Info Systems     | 12        | 1.11%   |
| Silicon Integrated Systems [SiS] | 12        | 1.11%   |
| Micron Technology                | 12        | 1.11%   |
| KIOXIA                           | 11        | 1.01%   |
| Union Memory (Shenzhen)          | 5         | 0.46%   |
| Realtek Semiconductor            | 5         | 0.46%   |
| Silicon Motion                   | 4         | 0.37%   |
| Nvidia                           | 4         | 0.37%   |
| ADATA Technology                 | 4         | 0.37%   |
| Phison Electronics               | 3         | 0.28%   |
| VIA Technologies                 | 2         | 0.18%   |
| Micron/Crucial Technology        | 2         | 0.18%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.18%   |
| Marvell Technology Group         | 1         | 0.09%   |
| Lite-On Technology               | 1         | 0.09%   |
| INNOGRIT                         | 1         | 0.09%   |
| Biwin Storage Technology         | 1         | 0.09%   |
| Apple                            | 1         | 0.09%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 111       | 9.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 94        | 8.02%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 85        | 7.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 57        | 4.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 55        | 4.69%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 32        | 2.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 30        | 2.56%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 30        | 2.56%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 30        | 2.56%   |
| Samsung NVMe SSD Controller 980                                                  | 28        | 2.39%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                               | 28        | 2.39%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 28        | 2.39%   |
| Intel Comet Lake SATA AHCI Controller                                            | 24        | 2.05%   |
| Intel Tiger Lake-LP SATA Controller                                              | 23        | 1.96%   |
| Intel Volume Management Device NVMe RAID Controller                              | 22        | 1.88%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 20        | 1.71%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 20        | 1.71%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 18        | 1.54%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 17        | 1.45%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 17        | 1.45%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 16        | 1.37%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 15        | 1.28%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 14        | 1.19%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 12        | 1.02%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                             | 12        | 1.02%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 11        | 0.94%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                      | 10        | 0.85%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 10        | 0.85%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 10        | 0.85%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 10        | 0.85%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 10        | 0.85%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 9         | 0.77%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 9         | 0.77%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 8         | 0.68%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                       | 8         | 0.68%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 8         | 0.68%   |
| Kingston Company NVMe Controller                                                 | 8         | 0.68%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 8         | 0.68%   |
| SK hynix BC511 NVMe SSD                                                          | 7         | 0.6%    |
| Intel SSD 660P Series                                                            | 7         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 741       | 66.16%  |
| NVMe | 219       | 19.55%  |
| IDE  | 86        | 7.68%   |
| RAID | 74        | 6.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 844       | 85.34%  |
| AMD    | 145       | 14.66%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 28        | 2.83%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 24        | 2.42%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 17        | 1.72%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 16        | 1.62%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 15        | 1.52%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 15        | 1.52%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 15        | 1.52%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 15        | 1.52%   |
| Intel Atom CPU N2600 @ 1.60GHz                | 15        | 1.52%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 1.41%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 14        | 1.41%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 14        | 1.41%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 14        | 1.41%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 14        | 1.41%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 13        | 1.31%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 13        | 1.31%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 13        | 1.31%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 12        | 1.21%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 11        | 1.11%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 11        | 1.11%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 10        | 1.01%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 9         | 0.91%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.91%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 9         | 0.91%   |
| Intel Core i3-2330M CPU @ 2.20GHz             | 9         | 0.91%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 9         | 0.91%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 0.91%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 9         | 0.91%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 8         | 0.81%   |
| Intel Core i5-3317U CPU @ 1.70GHz             | 8         | 0.81%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 8         | 0.81%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 8         | 0.81%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 8         | 0.81%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 7         | 0.71%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 7         | 0.71%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 7         | 0.71%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 7         | 0.71%   |
| Intel Core i3-2370M CPU @ 2.40GHz             | 7         | 0.71%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 7         | 0.71%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 7         | 0.71%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 228       | 23.03%  |
| Intel Core i7           | 166       | 16.77%  |
| Intel Core i3           | 123       | 12.42%  |
| Intel Celeron           | 90        | 9.09%   |
| Other                   | 75        | 7.58%   |
| Intel Atom              | 53        | 5.35%   |
| Intel Pentium           | 34        | 3.43%   |
| AMD Ryzen 5             | 34        | 3.43%   |
| AMD Ryzen 7             | 29        | 2.93%   |
| Intel Core 2 Duo        | 28        | 2.83%   |
| Intel Pentium Dual-Core | 22        | 2.22%   |
| Intel Pentium Dual      | 14        | 1.41%   |
| AMD A6                  | 13        | 1.31%   |
| Intel Genuine           | 9         | 0.91%   |
| AMD A8                  | 7         | 0.71%   |
| AMD A10                 | 7         | 0.71%   |
| AMD A12                 | 6         | 0.61%   |
| Intel Core 2            | 5         | 0.51%   |
| AMD Athlon II           | 5         | 0.51%   |
| AMD A4                  | 5         | 0.51%   |
| AMD Ryzen 9             | 4         | 0.4%    |
| AMD Ryzen 3             | 4         | 0.4%    |
| AMD Ryzen 7 PRO         | 3         | 0.3%    |
| AMD E                   | 3         | 0.3%    |
| Intel Pentium M         | 2         | 0.2%    |
| Intel Celeron M         | 2         | 0.2%    |
| AMD Turion II           | 2         | 0.2%    |
| AMD Turion 64 X2 Mobile | 2         | 0.2%    |
| AMD C-70                | 2         | 0.2%    |
| AMD Athlon              | 2         | 0.2%    |
| Intel Core Duo          | 1         | 0.1%    |
| Intel Celeron Dual-Core | 1         | 0.1%    |
| AMD Z                   | 1         | 0.1%    |
| AMD V120                | 1         | 0.1%    |
| AMD Turion 64 Mobile    | 1         | 0.1%    |
| AMD Phenom II           | 1         | 0.1%    |
| AMD E2                  | 1         | 0.1%    |
| AMD E1                  | 1         | 0.1%    |
| AMD C-60                | 1         | 0.1%    |
| AMD Athlon X2           | 1         | 0.1%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 602       | 60.81%  |
| 4       | 281       | 28.38%  |
| 1       | 40        | 4.04%   |
| 8       | 35        | 3.54%   |
| 6       | 21        | 2.12%   |
| 10      | 4         | 0.4%    |
| 14      | 2         | 0.2%    |
| Unknown | 2         | 0.2%    |
| 16      | 1         | 0.1%    |
| 12      | 1         | 0.1%    |
| 3       | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 988       | 99.9%   |
| Unknown | 1         | 0.1%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 692       | 69.9%   |
| 1       | 296       | 29.9%   |
| Unknown | 2         | 0.2%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 958       | 96.57%  |
| 32-bit         | 15        | 1.51%   |
| Unknown        | 15        | 1.51%   |
| 64-bit         | 4         | 0.4%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 223       | 21.8%   |
| 0x206a7    | 72        | 7.04%   |
| 0x306a9    | 67        | 6.55%   |
| 0x806ec    | 43        | 4.2%    |
| 0x806e9    | 42        | 4.11%   |
| 0x806c1    | 35        | 3.42%   |
| 0x406e3    | 33        | 3.23%   |
| 0x1067a    | 31        | 3.03%   |
| 0x306d4    | 29        | 2.83%   |
| 0x806ea    | 28        | 2.74%   |
| 0x40651    | 26        | 2.54%   |
| 0x20655    | 24        | 2.35%   |
| 0x6fd      | 22        | 2.15%   |
| 0x706e5    | 20        | 1.96%   |
| 0x406c4    | 20        | 1.96%   |
| 0x30678    | 18        | 1.76%   |
| 0x706a1    | 16        | 1.56%   |
| 0x306c3    | 16        | 1.56%   |
| 0x30661    | 15        | 1.47%   |
| 0x106ca    | 15        | 1.47%   |
| 0x08108109 | 13        | 1.27%   |
| 0x506c9    | 12        | 1.17%   |
| 0x706a8    | 11        | 1.08%   |
| 0x06006705 | 11        | 1.08%   |
| 0x20652    | 9         | 0.88%   |
| 0x08608103 | 9         | 0.88%   |
| 0x906e9    | 8         | 0.78%   |
| 0x0a50000c | 8         | 0.78%   |
| 0xa0652    | 7         | 0.68%   |
| 0x08108102 | 7         | 0.68%   |
| 0x906ea    | 6         | 0.59%   |
| 0x6e8      | 6         | 0.59%   |
| 0x10661    | 6         | 0.59%   |
| 0x08600104 | 6         | 0.59%   |
| 0x0810100b | 6         | 0.59%   |
| 0x06006118 | 6         | 0.59%   |
| 0x06001119 | 6         | 0.59%   |
| 0x806eb    | 5         | 0.49%   |
| 0x406c3    | 5         | 0.49%   |
| 0x010000c8 | 5         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 170       | 17.19%  |
| SandyBridge      | 88        | 8.9%    |
| IvyBridge        | 79        | 7.99%   |
| Silvermont       | 53        | 5.36%   |
| TigerLake        | 52        | 5.26%   |
| Skylake          | 51        | 5.16%   |
| Haswell          | 51        | 5.16%   |
| Penryn           | 42        | 4.25%   |
| Westmere         | 40        | 4.04%   |
| Core             | 37        | 3.74%   |
| Bonnell          | 34        | 3.44%   |
| Goldmont plus    | 33        | 3.34%   |
| Broadwell        | 33        | 3.34%   |
| Icelake          | 32        | 3.24%   |
| Zen+             | 24        | 2.43%   |
| Excavator        | 24        | 2.43%   |
| Unknown          | 19        | 1.92%   |
| Zen 2            | 15        | 1.52%   |
| Goldmont         | 14        | 1.42%   |
| Zen              | 12        | 1.21%   |
| P6               | 11        | 1.11%   |
| Zen 3            | 9         | 0.91%   |
| K10              | 9         | 0.91%   |
| CometLake        | 9         | 0.91%   |
| Piledriver       | 8         | 0.81%   |
| Bobcat           | 8         | 0.81%   |
| K10 Llano        | 6         | 0.61%   |
| Alderlake Hybrid | 6         | 0.61%   |
| Nehalem          | 5         | 0.51%   |
| Puma             | 4         | 0.4%    |
| K8 Hammer        | 4         | 0.4%    |
| Steamroller      | 3         | 0.3%    |
| K8 & K10 hybrid  | 2         | 0.2%    |
| Jaguar           | 2         | 0.2%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 805       | 71.18%  |
| AMD                              | 179       | 15.83%  |
| Nvidia                           | 133       | 11.76%  |
| Silicon Integrated Systems [SiS] | 12        | 1.06%   |
| VIA Technologies                 | 2         | 0.18%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 87        | 7.4%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 76        | 6.46%   |
| Intel HD Graphics 620                                                                    | 52        | 4.42%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 47        | 4%      |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 43        | 3.66%   |
| Intel Core Processor Integrated Graphics Controller                                      | 39        | 3.32%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 36        | 3.06%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 36        | 3.06%   |
| Intel UHD Graphics 620                                                                   | 34        | 2.89%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 33        | 2.81%   |
| Intel HD Graphics 5500                                                                   | 31        | 2.64%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 31        | 2.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 31        | 2.64%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 27        | 2.3%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 24        | 2.04%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 22        | 1.87%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 22        | 1.87%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 18        | 1.53%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 18        | 1.53%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 16        | 1.36%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 16        | 1.36%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 16        | 1.36%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 15        | 1.28%   |
| Intel Atom Processor D2xxx/N2xxx Integrated Graphics Controller                          | 15        | 1.28%   |
| Intel HD Graphics 500                                                                    | 14        | 1.19%   |
| AMD Renoir                                                                               | 14        | 1.19%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 12        | 1.02%   |
| AMD Lucienne                                                                             | 12        | 1.02%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 0.94%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 11        | 0.94%   |
| Intel HD Graphics 630                                                                    | 11        | 0.94%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 11        | 0.94%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 11        | 0.94%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 9         | 0.77%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 8         | 0.68%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 0.68%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 8         | 0.68%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 8         | 0.68%   |
| Nvidia GP108M [GeForce MX150]                                                            | 7         | 0.6%    |
| Nvidia GM108M [GeForce 940M]                                                             | 7         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 677       | 68.38%  |
| 1 x AMD        | 122       | 12.32%  |
| Intel + Nvidia | 97        | 9.8%    |
| Intel + AMD    | 30        | 3.03%   |
| 1 x Nvidia     | 22        | 2.22%   |
| AMD + Nvidia   | 15        | 1.52%   |
| 2 x AMD        | 12        | 1.21%   |
| 1 x SiS        | 12        | 1.21%   |
| 1 x VIA        | 2         | 0.2%    |
| 2 x Intel      | 1         | 0.1%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 897       | 90.33%  |
| Proprietary | 62        | 6.24%   |
| Unknown     | 34        | 3.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 739       | 73.31%  |
| 1.01-2.0   | 94        | 9.33%   |
| 0.01-0.5   | 94        | 9.33%   |
| 0.51-1.0   | 34        | 3.37%   |
| 3.01-4.0   | 33        | 3.27%   |
| 5.01-6.0   | 10        | 0.99%   |
| 2.01-3.0   | 3         | 0.3%    |
| 8.01-16.0  | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 186       | 16.8%   |
| Samsung Electronics     | 176       | 15.9%   |
| Chimei Innolux          | 171       | 15.45%  |
| BOE                     | 161       | 14.54%  |
| LG Display              | 128       | 11.56%  |
| Goldstar                | 38        | 3.43%   |
| InfoVision              | 33        | 2.98%   |
| Chi Mei Optoelectronics | 22        | 1.99%   |
| PANDA                   | 16        | 1.45%   |
| Apple                   | 14        | 1.26%   |
| LG Philips              | 12        | 1.08%   |
| Lenovo                  | 11        | 0.99%   |
| InnoLux Display         | 11        | 0.99%   |
| Philips                 | 10        | 0.9%    |
| Sharp                   | 9         | 0.81%   |
| Dell                    | 9         | 0.81%   |
| BenQ                    | 9         | 0.81%   |
| ViewSonic               | 8         | 0.72%   |
| STA                     | 8         | 0.72%   |
| HannStar                | 8         | 0.72%   |
| CPT                     | 7         | 0.63%   |
| KDC                     | 5         | 0.45%   |
| Hitachi                 | 5         | 0.45%   |
| Hewlett-Packard         | 5         | 0.45%   |
| SKY                     | 4         | 0.36%   |
| Pixio                   | 3         | 0.27%   |
| ASUSTek Computer        | 3         | 0.27%   |
| ZTR                     | 2         | 0.18%   |
| Unknown                 | 2         | 0.18%   |
| MTD                     | 2         | 0.18%   |
| iQual                   | 2         | 0.18%   |
| HKC                     | 2         | 0.18%   |
| Gigabyte Technology     | 2         | 0.18%   |
| Daewoo                  | 2         | 0.18%   |
| CSO                     | 2         | 0.18%   |
| AOC                     | 2         | 0.18%   |
| Xiaomi                  | 1         | 0.09%   |
| UTV                     | 1         | 0.09%   |
| Toshiba                 | 1         | 0.09%   |
| SNT                     | 1         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Notebooks | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 23        | 2.04%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 21        | 1.86%   |
| InfoVision LCD Monitor IVO03F4 1920x1200 263x164mm 12.2-inch         | 18        | 1.6%    |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch | 14        | 1.24%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 11        | 0.98%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 11        | 0.98%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 11        | 0.98%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 9         | 0.8%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 9         | 0.8%    |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch        | 9         | 0.8%    |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 8         | 0.71%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 8         | 0.71%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 8         | 0.71%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 7         | 0.62%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                 | 7         | 0.62%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 7         | 0.62%   |
| Samsung Electronics LCD Monitor SEC4145 1366x768 309x174mm 14.0-inch | 6         | 0.53%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 6         | 0.53%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 6         | 0.53%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 6         | 0.53%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 6         | 0.53%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 6         | 0.53%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch        | 6         | 0.53%   |
| PANDA LCD Monitor NCP004A 1920x1080 309x174mm 14.0-inch              | 5         | 0.44%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch          | 5         | 0.44%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch            | 5         | 0.44%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 5         | 0.44%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch     | 5         | 0.44%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 5         | 0.44%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch        | 5         | 0.44%   |
| AU Optronics LCD Monitor AUO303E 1600x900 309x174mm 14.0-inch        | 5         | 0.44%   |
| Samsung Electronics LCD Monitor SEC4141 1366x768 344x193mm 15.5-inch | 4         | 0.35%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch | 4         | 0.35%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 4         | 0.35%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch        | 4         | 0.35%   |
| LG Display LCD Monitor LGD070C 1920x1080 309x174mm 14.0-inch         | 4         | 0.35%   |
| LG Display LCD Monitor LGD0335 1366x768 310x174mm 14.0-inch          | 4         | 0.35%   |
| InnoLux Display LCD Monitor INL000A 1366x768 344x194mm 15.5-inch     | 4         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 4         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 4         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 540       | 50.7%   |
| 1920x1080 (FHD)    | 316       | 29.67%  |
| 1280x800 (WXGA)    | 48        | 4.51%   |
| 1600x900 (HD+)     | 27        | 2.54%   |
| 1920x1200 (WUXGA)  | 21        | 1.97%   |
| 3840x2160 (4K)     | 20        | 1.88%   |
| 1440x900 (WXGA+)   | 17        | 1.6%    |
| 1024x600           | 13        | 1.22%   |
| 1280x1024 (SXGA)   | 9         | 0.85%   |
| 1680x1050 (WSXGA+) | 8         | 0.75%   |
| 1360x768           | 6         | 0.56%   |
| 3200x1800 (QHD+)   | 5         | 0.47%   |
| 2560x1080          | 5         | 0.47%   |
| 3840x2400          | 3         | 0.28%   |
| 2880x1800          | 3         | 0.28%   |
| 2560x1600          | 3         | 0.28%   |
| 2560x1440 (QHD)    | 3         | 0.28%   |
| 1920x540           | 3         | 0.28%   |
| 2288x1287          | 2         | 0.19%   |
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
| 15      | 479       | 42.77%  |
| 14      | 190       | 16.96%  |
| 13      | 167       | 14.91%  |
| 23      | 36        | 3.21%   |
| 17      | 34        | 3.04%   |
| 21      | 24        | 2.14%   |
| 27      | 23        | 2.05%   |
| 18      | 23        | 2.05%   |
| 10      | 18        | 1.61%   |
| 11      | 17        | 1.52%   |
| 40      | 15        | 1.34%   |
| 24      | 13        | 1.16%   |
| 12      | 13        | 1.16%   |
| 19      | 12        | 1.07%   |
| 20      | 11        | 0.98%   |
| 16      | 8         | 0.71%   |
| 34      | 6         | 0.54%   |
| 46      | 5         | 0.45%   |
| 52      | 4         | 0.36%   |
| 84      | 3         | 0.27%   |
| 48      | 3         | 0.27%   |
| 31      | 3         | 0.27%   |
| 142     | 2         | 0.18%   |
| 54      | 2         | 0.18%   |
| 32      | 2         | 0.18%   |
| 22      | 2         | 0.18%   |
| Unknown | 2         | 0.18%   |
| 65      | 1         | 0.09%   |
| 37      | 1         | 0.09%   |
| 26      | 1         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 784       | 70.5%   |
| 201-300        | 85        | 7.64%   |
| 401-500        | 73        | 6.56%   |
| 501-600        | 67        | 6.03%   |
| 351-400        | 51        | 4.59%   |
| 801-900        | 16        | 1.44%   |
| 1001-1500      | 15        | 1.35%   |
| 701-800        | 8         | 0.72%   |
| 601-700        | 6         | 0.54%   |
| 1501-2000      | 3         | 0.27%   |
| More than 2000 | 2         | 0.18%   |
| Unknown        | 2         | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 853       | 87.04%  |
| 16/10   | 96        | 9.8%    |
| 5/4     | 7         | 0.71%   |
| 21/9    | 6         | 0.61%   |
| 4/3     | 5         | 0.51%   |
| 3/2     | 5         | 0.51%   |
| 1.96    | 2         | 0.2%    |
| 1.00    | 2         | 0.2%    |
| 32/9    | 1         | 0.1%    |
| 3.40    | 1         | 0.1%    |
| 0.89    | 1         | 0.1%    |
| Unknown | 1         | 0.1%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 477       | 42.48%  |
| 81-90          | 327       | 29.12%  |
| 201-250        | 71        | 6.32%   |
| 151-200        | 28        | 2.49%   |
| 141-150        | 27        | 2.4%    |
| 71-80          | 26        | 2.32%   |
| 121-130        | 26        | 2.32%   |
| 501-1000       | 24        | 2.14%   |
| 301-350        | 23        | 2.05%   |
| 51-60          | 18        | 1.6%    |
| 41-50          | 18        | 1.6%    |
| 61-70          | 13        | 1.16%   |
| More than 1000 | 12        | 1.07%   |
| 351-500        | 12        | 1.07%   |
| 111-120        | 11        | 0.98%   |
| 91-100         | 4         | 0.36%   |
| 131-140        | 3         | 0.27%   |
| Unknown        | 2         | 0.18%   |
| 251-300        | 1         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 569       | 51.77%  |
| 121-160       | 273       | 24.84%  |
| 51-100        | 191       | 17.38%  |
| 161-240       | 26        | 2.37%   |
| 1-50          | 22        | 2%      |
| More than 240 | 16        | 1.46%   |
| Unknown       | 2         | 0.18%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 802       | 78.94%  |
| 2     | 171       | 16.83%  |
| 0     | 30        | 2.95%   |
| 3     | 12        | 1.18%   |
| 5     | 1         | 0.1%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 622       | 40.21%  |
| Intel                                 | 398       | 25.73%  |
| Qualcomm Atheros                      | 229       | 14.8%   |
| Broadcom                              | 85        | 5.49%   |
| Broadcom Limited                      | 29        | 1.87%   |
| JMicron Technology                    | 24        | 1.55%   |
| Marvell Technology Group              | 21        | 1.36%   |
| TP-Link                               | 20        | 1.29%   |
| Ralink Technology                     | 15        | 0.97%   |
| Ralink                                | 15        | 0.97%   |
| MediaTek                              | 14        | 0.9%    |
| Silicon Integrated Systems [SiS]      | 12        | 0.78%   |
| Samsung Electronics                   | 10        | 0.65%   |
| Motorola PCS                          | 8         | 0.52%   |
| Qualcomm Atheros Communications       | 7         | 0.45%   |
| ASIX Electronics                      | 7         | 0.45%   |
| Nvidia                                | 4         | 0.26%   |
| Ericsson Business Mobile Networks     | 3         | 0.19%   |
| DisplayLink                           | 3         | 0.19%   |
| Xiaomi                                | 2         | 0.13%   |
| VIA Technologies                      | 2         | 0.13%   |
| Lenovo                                | 2         | 0.13%   |
| ICS Advent                            | 2         | 0.13%   |
| Encore Electronics                    | 2         | 0.13%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.06%   |
| T & A Mobile Phones                   | 1         | 0.06%   |
| Spreadtrum Communications             | 1         | 0.06%   |
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


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 336       | 17.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 145       | 7.66%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 45        | 2.38%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 41        | 2.17%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 41        | 2.17%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 41        | 2.17%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 39        | 2.06%   |
| Intel Wi-Fi 6 AX201                                                     | 35        | 1.85%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 34        | 1.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 33        | 1.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 31        | 1.64%   |
| Intel Wireless 3160                                                     | 30        | 1.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 30        | 1.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 24        | 1.27%   |
| Intel Wireless 8265 / 8275                                              | 23        | 1.22%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                              | 22        | 1.16%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                  | 22        | 1.16%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 21        | 1.11%   |
| Intel Wireless 3165                                                     | 21        | 1.11%   |
| Intel Wireless 7260                                                     | 19        | 1%      |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 19        | 1%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 17        | 0.9%    |
| Intel Wi-Fi 6 AX200                                                     | 17        | 0.9%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 16        | 0.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 16        | 0.85%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 15        | 0.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 0.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 0.79%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 14        | 0.74%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 13        | 0.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 13        | 0.69%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 13        | 0.69%   |
| Intel Wireless 7265                                                     | 13        | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                           | 13        | 0.69%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 13        | 0.69%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 12        | 0.63%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 12        | 0.63%   |
| Realtek 802.11n WLAN Adapter                                            | 12        | 0.63%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 0.63%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 12        | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 375       | 36.98%  |
| Realtek Semiconductor                 | 277       | 27.32%  |
| Qualcomm Atheros                      | 199       | 19.63%  |
| Broadcom                              | 74        | 7.3%    |
| Broadcom Limited                      | 18        | 1.78%   |
| Ralink Technology                     | 15        | 1.48%   |
| Ralink                                | 15        | 1.48%   |
| TP-Link                               | 14        | 1.38%   |
| MediaTek                              | 12        | 1.18%   |
| Qualcomm Atheros Communications       | 7         | 0.69%   |
| Encore Electronics                    | 2         | 0.2%    |
| Sierra Wireless                       | 1         | 0.1%    |
| Ovislink                              | 1         | 0.1%    |
| Ericsson Business Mobile Networks     | 1         | 0.1%    |
| Dell                                  | 1         | 0.1%    |
| Cisco Aironet Wireless Communications | 1         | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 45        | 4.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 41        | 4.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 41        | 4.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 41        | 4.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 39        | 3.81%   |
| Intel Wi-Fi 6 AX201                                                     | 35        | 3.42%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 34        | 3.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 33        | 3.23%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 31        | 3.03%   |
| Intel Wireless 3160                                                     | 30        | 2.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 30        | 2.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 24        | 2.35%   |
| Intel Wireless 8265 / 8275                                              | 23        | 2.25%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 21        | 2.05%   |
| Intel Wireless 3165                                                     | 21        | 2.05%   |
| Intel Wireless 7260                                                     | 19        | 1.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 19        | 1.86%   |
| Intel Wi-Fi 6 AX200                                                     | 17        | 1.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 16        | 1.56%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 15        | 1.47%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 1.47%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 15        | 1.47%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 14        | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 13        | 1.27%   |
| Intel Wireless 7265                                                     | 13        | 1.27%   |
| Broadcom BCM43142 802.11b/g/n                                           | 13        | 1.27%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 13        | 1.27%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 12        | 1.17%   |
| Realtek 802.11n WLAN Adapter                                            | 12        | 1.17%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 12        | 1.17%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 12        | 1.17%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 12        | 1.17%   |
| Intel Wireless 8260                                                     | 11        | 1.08%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 10        | 0.98%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 10        | 0.98%   |
| Ralink MT7601U Wireless Adapter                                         | 9         | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 7         | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 7         | 0.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 7         | 0.68%   |
| Qualcomm Atheros AR9271 802.11n                                         | 7         | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 517       | 60.12%  |
| Intel                            | 121       | 14.07%  |
| Qualcomm Atheros                 | 80        | 9.3%    |
| JMicron Technology               | 24        | 2.79%   |
| Broadcom                         | 23        | 2.67%   |
| Marvell Technology Group         | 21        | 2.44%   |
| Silicon Integrated Systems [SiS] | 12        | 1.4%    |
| Broadcom Limited                 | 11        | 1.28%   |
| Samsung Electronics              | 10        | 1.16%   |
| Motorola PCS                     | 7         | 0.81%   |
| ASIX Electronics                 | 7         | 0.81%   |
| TP-Link                          | 6         | 0.7%    |
| Nvidia                           | 4         | 0.47%   |
| DisplayLink                      | 3         | 0.35%   |
| Xiaomi                           | 2         | 0.23%   |
| VIA Technologies                 | 2         | 0.23%   |
| MediaTek                         | 2         | 0.23%   |
| Lenovo                           | 2         | 0.23%   |
| ICS Advent                       | 2         | 0.23%   |
| T & A Mobile Phones              | 1         | 0.12%   |
| Spreadtrum Communications        | 1         | 0.12%   |
| Digitech Systems                 | 1         | 0.12%   |
| 3DSP                             | 1         | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 336       | 38.98%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 145       | 16.82%  |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 22        | 2.55%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 22        | 2.55%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17        | 1.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 16        | 1.86%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 13        | 1.51%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 13        | 1.51%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 12        | 1.39%   |
| Intel Ethernet Connection (13) I219-V                             | 12        | 1.39%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 11        | 1.28%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 11        | 1.28%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 10        | 1.16%   |
| Intel Ethernet Connection (4) I219-LM                             | 10        | 1.16%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 9         | 1.04%   |
| Intel Ethernet Connection (10) I219-V                             | 9         | 1.04%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 0.93%   |
| Motorola PCS motorola edge 20 lite                                | 7         | 0.81%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.81%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.7%    |
| Intel Ethernet Connection I219-LM                                 | 6         | 0.7%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 5         | 0.58%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 5         | 0.58%   |
| Intel Ethernet Controller I225-V                                  | 5         | 0.58%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 5         | 0.58%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 0.58%   |
| TP-Link USB 10/100 LAN                                            | 4         | 0.46%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 0.46%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 4         | 0.46%   |
| Intel PRO/100 VE Network Connection                               | 4         | 0.46%   |
| Intel Ethernet Connection I217-LM                                 | 4         | 0.46%   |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.46%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.46%   |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.46%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 4         | 0.46%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe           | 4         | 0.46%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.35%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 3         | 0.35%   |
| Marvell Group 88E8039 PCI-E Fast Ethernet Controller              | 3         | 0.35%   |
| Intel WiMAX Connection 2400m                                      | 3         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 969       | 53.74%  |
| Ethernet | 827       | 45.87%  |
| Modem    | 7         | 0.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 824       | 80.63%  |
| Ethernet | 198       | 19.37%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 756       | 76.36%  |
| 1     | 190       | 19.19%  |
| 0     | 39        | 3.94%   |
| 3     | 4         | 0.4%    |
| 4     | 1         | 0.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 868       | 86.63%  |
| Yes  | 134       | 13.37%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 292       | 42.26%  |
| Realtek Semiconductor           | 130       | 18.81%  |
| Qualcomm Atheros Communications | 63        | 9.12%   |
| IMC Networks                    | 45        | 6.51%   |
| Broadcom                        | 39        | 5.64%   |
| Lite-On Technology              | 34        | 4.92%   |
| Foxconn / Hon Hai               | 23        | 3.33%   |
| Dell                            | 13        | 1.88%   |
| Apple                           | 12        | 1.74%   |
| Toshiba                         | 10        | 1.45%   |
| Cambridge Silicon Radio         | 10        | 1.45%   |
| Ralink                          | 7         | 1.01%   |
| USI                             | 2         | 0.29%   |
| Qcom                            | 2         | 0.29%   |
| ASUSTek Computer                | 2         | 0.29%   |
| Syntek                          | 1         | 0.14%   |
| Realtek                         | 1         | 0.14%   |
| Ralink Technology               | 1         | 0.14%   |
| Integrated System Solution      | 1         | 0.14%   |
| Hewlett-Packard                 | 1         | 0.14%   |
| Foxconn International           | 1         | 0.14%   |
| Alps Electric                   | 1         | 0.14%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 122       | 17.63%  |
| Realtek Bluetooth Radio                                                             | 79        | 11.42%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 59        | 8.53%   |
| Intel AX201 Bluetooth                                                               | 53        | 7.66%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 41        | 5.92%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 33        | 4.77%   |
| Intel AX200 Bluetooth                                                               | 17        | 2.46%   |
| IMC Networks Bluetooth Radio                                                        | 17        | 2.46%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 15        | 2.17%   |
| Intel Bluetooth Device                                                              | 15        | 2.17%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 12        | 1.73%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 12        | 1.73%   |
| IMC Networks Bluetooth Device                                                       | 12        | 1.73%   |
| Lite-On Bluetooth Device                                                            | 11        | 1.59%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 10        | 1.45%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 9         | 1.3%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 8         | 1.16%   |
| Toshiba Bluetooth USB Host Controller                                               | 7         | 1.01%   |
| Ralink RT3290 Bluetooth                                                             | 7         | 1.01%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 7         | 1.01%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 7         | 1.01%   |
| IMC Networks Wireless_Device                                                        | 6         | 0.87%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 6         | 0.87%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 0.87%   |
| Apple Bluetooth USB Host Controller                                                 | 6         | 0.87%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 5         | 0.72%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 5         | 0.72%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 5         | 0.72%   |
| Dell Wireless 365 Bluetooth                                                         | 5         | 0.72%   |
| Realtek RTL8821A Bluetooth                                                          | 4         | 0.58%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 0.58%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 4         | 0.58%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 4         | 0.58%   |
| Dell DW375 Bluetooth Module                                                         | 4         | 0.58%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 3         | 0.43%   |
| Lite-On Bluetooth Radio                                                             | 3         | 0.43%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 0.43%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 3         | 0.43%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.43%   |
| Broadcom Bluetooth 2.1 Device                                                       | 3         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 811       | 74.13%  |
| AMD                              | 150       | 13.71%  |
| Nvidia                           | 67        | 6.12%   |
| Logitech                         | 13        | 1.19%   |
| Silicon Integrated Systems [SiS] | 12        | 1.1%    |
| C-Media Electronics              | 8         | 0.73%   |
| GN Netcom                        | 4         | 0.37%   |
| Plantronics                      | 3         | 0.27%   |
| Kingston Technology              | 3         | 0.27%   |
| VIA Technologies                 | 2         | 0.18%   |
| Texas Instruments                | 2         | 0.18%   |
| Lenovo                           | 2         | 0.18%   |
| Generalplus Technology           | 2         | 0.18%   |
| Focusrite-Novation               | 2         | 0.18%   |
| Samsung Electronics              | 1         | 0.09%   |
| Samson Technologies              | 1         | 0.09%   |
| Realtek Semiconductor            | 1         | 0.09%   |
| Microsoft                        | 1         | 0.09%   |
| Hewlett-Packard                  | 1         | 0.09%   |
| FiiO Electronics Technology      | 1         | 0.09%   |
| ESI Audiotechnik                 | 1         | 0.09%   |
| Creative Technology              | 1         | 0.09%   |
| Corsair                          | 1         | 0.09%   |
| BEHRINGER International          | 1         | 0.09%   |
| ATI Technologies                 | 1         | 0.09%   |
| ASUSTek Computer                 | 1         | 0.09%   |
| Astro Gaming                     | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 131       | 10.05%  |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 106       | 8.14%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 74        | 5.68%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 61        | 4.68%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 52        | 3.99%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 48        | 3.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 45        | 3.45%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 40        | 3.07%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 37        | 2.84%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 34        | 2.61%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 33        | 2.53%   |
| Intel Broadwell-U Audio Controller                                                                | 33        | 2.53%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 32        | 2.46%   |
| Intel 8 Series HD Audio Controller                                                                | 32        | 2.46%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 30        | 2.3%    |
| AMD Renoir Radeon High Definition Audio Controller                                                | 28        | 2.15%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 27        | 2.07%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 26        | 2%      |
| AMD FCH Azalia Controller                                                                         | 25        | 1.92%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 24        | 1.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 20        | 1.53%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 19        | 1.46%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 19        | 1.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 18        | 1.38%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 17        | 1.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 15        | 1.15%   |
| AMD High Definition Audio Controller                                                              | 15        | 1.15%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 14        | 1.07%   |
| AMD Kabini HDMI/DP Audio                                                                          | 14        | 1.07%   |
| Intel CM238 HD Audio Controller                                                                   | 13        | 1%      |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 12        | 0.92%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 9         | 0.69%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 8         | 0.61%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 8         | 0.61%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 8         | 0.61%   |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 0.61%   |
| AMD Trinity HDMI Audio Controller                                                                 | 8         | 0.61%   |
| Logitech H390 headset with microphone                                                             | 7         | 0.54%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 0.54%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 7         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                           | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Samsung Electronics                              | 173       | 25.78%  |
| SK hynix                                         | 127       | 18.93%  |
| Kingston                                         | 97        | 14.46%  |
| Micron Technology                                | 52        | 7.75%   |
| Unknown                                          | 36        | 5.37%   |
| A-DATA Technology                                | 30        | 4.47%   |
| Crucial                                          | 22        | 3.28%   |
| Nanya Technology                                 | 14        | 2.09%   |
| Unknown (ABCD)                                   | 13        | 1.94%   |
| Magnum Tech                                      | 12        | 1.79%   |
| Corsair                                          | 10        | 1.49%   |
| Elpida                                           | 9         | 1.34%   |
| Novatech                                         | 7         | 1.04%   |
| Ramaxel Technology                               | 6         | 0.89%   |
| Goldkey                                          | 6         | 0.89%   |
| Saikano                                          | 5         | 0.75%   |
| Memox                                            | 5         | 0.75%   |
| Unknown                                          | 4         | 0.6%    |
| Transcend                                        | 3         | 0.45%   |
| Super Talent                                     | 3         | 0.45%   |
| Neo Forza                                        | 3         | 0.45%   |
| Kingmax                                          | 3         | 0.45%   |
| Avant                                            | 3         | 0.45%   |
| Apacer                                           | 3         | 0.45%   |
| 48spaces                                         | 3         | 0.45%   |
| Teikon                                           | 2         | 0.3%    |
| Netac                                            | 2         | 0.3%    |
| Innodisk                                         | 2         | 0.3%    |
| G.Skill                                          | 2         | 0.3%    |
| CSX                                              | 2         | 0.3%    |
| Unknown (0x4E41324D3030314733374455202020202020) | 1         | 0.15%   |
| Unknown (0x4D342037305432393533455A332D43453620) | 1         | 0.15%   |
| Unknown (07D5)                                   | 1         | 0.15%   |
| Team                                             | 1         | 0.15%   |
| SHARETRONIC                                      | 1         | 0.15%   |
| Qimonda                                          | 1         | 0.15%   |
| PNY                                              | 1         | 0.15%   |
| Patriot                                          | 1         | 0.15%   |
| Lexar                                            | 1         | 0.15%   |
| High Bridge                                      | 1         | 0.15%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                        | 16        | 2.24%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s                       | 15        | 2.1%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                       | 14        | 1.96%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s             | 13        | 1.82%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                        | 13        | 1.82%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 12        | 1.68%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                        | 12        | 1.68%   |
| Magnum Tech RAM MAGNUMTECH 4GB SODIMM DDR3 1600MT/s                          | 12        | 1.68%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s                        | 8         | 1.12%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                        | 7         | 0.98%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s                         | 7         | 0.98%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                       | 6         | 0.84%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                        | 6         | 0.84%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                        | 6         | 0.84%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s                     | 5         | 0.7%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s                        | 5         | 0.7%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s                        | 5         | 0.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s                        | 5         | 0.7%    |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s                        | 5         | 0.7%    |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                        | 5         | 0.7%    |
| Saikano RAM Memory 4GB SODIMM DDR3 1333MT/s                                  | 5         | 0.7%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s                       | 4         | 0.56%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s                       | 4         | 0.56%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                        | 4         | 0.56%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                        | 4         | 0.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                        | 4         | 0.56%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s                        | 4         | 0.56%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s                  | 4         | 0.56%   |
| Micron RAM 4ATF51264HZ-2G6E! 4GB SODIMM DDR4 2400MT/s                        | 4         | 0.56%   |
| Unknown                                                                      | 4         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                                  | 3         | 0.42%   |
| Super Talent RAM SUPERTALENT02 8GB SODIMM DDR3 1600MT/s                      | 3         | 0.42%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s                       | 3         | 0.42%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s                       | 3         | 0.42%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s                       | 3         | 0.42%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s                       | 3         | 0.42%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s                       | 3         | 0.42%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s                      | 3         | 0.42%   |
| SK hynix RAM 212121212121212121212121212121212121 2048MB SODIMM DDR2 667MT/s | 3         | 0.42%   |
| SK hynix RAM 202020202020202020202020202020202020 2048MB SODIMM DDR2 667MT/s | 3         | 0.42%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 241       | 45.3%   |
| DDR3    | 209       | 39.29%  |
| LPDDR4  | 23        | 4.32%   |
| DDR2    | 23        | 4.32%   |
| SDRAM   | 10        | 1.88%   |
| LPDDR3  | 10        | 1.88%   |
| DRAM    | 5         | 0.94%   |
| DDR     | 4         | 0.75%   |
| LPDDR5  | 3         | 0.56%   |
| DDR5    | 3         | 0.56%   |
| Unknown | 1         | 0.19%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 495       | 92.35%  |
| Row Of Chips | 35        | 6.53%   |
| DIMM         | 3         | 0.56%   |
| Chip         | 2         | 0.37%   |
| Unknown      | 1         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 227       | 36.67%  |
| 4096  | 200       | 32.31%  |
| 2048  | 93        | 15.02%  |
| 16384 | 71        | 11.47%  |
| 1024  | 15        | 2.42%   |
| 32768 | 10        | 1.62%   |
| 512   | 2         | 0.32%   |
| 6144  | 1         | 0.16%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 131       | 21.55%  |
| 1600    | 126       | 20.72%  |
| 3200    | 102       | 16.78%  |
| 1333    | 48        | 7.89%   |
| 2400    | 47        | 7.73%   |
| 1334    | 35        | 5.76%   |
| 2133    | 25        | 4.11%   |
| Unknown | 15        | 2.47%   |
| 667     | 14        | 2.3%    |
| 3266    | 12        | 1.97%   |
| 1067    | 12        | 1.97%   |
| 4199    | 7         | 1.15%   |
| 800     | 5         | 0.82%   |
| 1066    | 4         | 0.66%   |
| 975     | 4         | 0.66%   |
| 6400    | 3         | 0.49%   |
| 4800    | 3         | 0.49%   |
| 4267    | 3         | 0.49%   |
| 2048    | 3         | 0.49%   |
| 533     | 3         | 0.49%   |
| 1867    | 2         | 0.33%   |
| 8400    | 1         | 0.16%   |
| 4266    | 1         | 0.16%   |
| 2933    | 1         | 0.16%   |
| 400     | 1         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 3         | 37.5%   |
| Hewlett-Packard     | 2         | 25%     |
| Seiko Epson         | 1         | 12.5%   |
| QinHeng Electronics | 1         | 12.5%   |
| Kyocera             | 1         | 12.5%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Seiko Epson L120 Series | 1         | 12.5%   |
| QinHeng CH340S          | 1         | 12.5%   |
| Kyocera ECOSYS M3550idn | 1         | 12.5%   |
| HP LaserJet 1020        | 1         | 12.5%   |
| HP DeskJet F300 series  | 1         | 12.5%   |
| Brother HL-1200 series  | 1         | 12.5%   |
| Brother HL-1110 series  | 1         | 12.5%   |
| Brother DCP-1600        | 1         | 12.5%   |

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
| Chicony Electronics                    | 197       | 22.01%  |
| IMC Networks                           | 98        | 10.95%  |
| Bison Electronics                      | 83        | 9.27%   |
| Realtek Semiconductor                  | 77        | 8.6%    |
| Microdia                               | 71        | 7.93%   |
| Sunplus Innovation Technology          | 39        | 4.36%   |
| Suyin                                  | 38        | 4.25%   |
| Syntek                                 | 37        | 4.13%   |
| Quanta                                 | 36        | 4.02%   |
| Cheng Uei Precision Industry (Foxlink) | 31        | 3.46%   |
| Alcor Micro                            | 28        | 3.13%   |
| Silicon Motion                         | 25        | 2.79%   |
| Acer                                   | 17        | 1.9%    |
| Luxvisions Innotech Limited            | 13        | 1.45%   |
| Logitech                               | 12        | 1.34%   |
| Apple                                  | 12        | 1.34%   |
| Ricoh                                  | 11        | 1.23%   |
| Lite-On Technology                     | 11        | 1.23%   |
| Z-Star Microelectronics                | 6         | 0.67%   |
| Sonix Technology                       | 6         | 0.67%   |
| Samsung Electronics                    | 6         | 0.67%   |
| SunplusIT                              | 5         | 0.56%   |
| OmniVision Technologies                | 5         | 0.56%   |
| icSpring                               | 5         | 0.56%   |
| GEMBIRD                                | 4         | 0.45%   |
| ALi                                    | 4         | 0.45%   |
| Y Media                                | 3         | 0.34%   |
| Lenovo                                 | 2         | 0.22%   |
| Intel                                  | 2         | 0.22%   |
| Cubeternet                             | 2         | 0.22%   |
| Sunplus Technology                     | 1         | 0.11%   |
| Microsoft                              | 1         | 0.11%   |
| KYE Systems (Mouse Systems)            | 1         | 0.11%   |
| Importek                               | 1         | 0.11%   |
| HRY                                    | 1         | 0.11%   |
| Google                                 | 1         | 0.11%   |
| Genesys Logic                          | 1         | 0.11%   |
| Aveo Technology                        | 1         | 0.11%   |
| Allwinner Technology                   | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                             | 33        | 3.67%   |
| Bison Integrated Camera                                        | 32        | 3.56%   |
| Chicony USB 2.0 Camera                                         | 27        | 3.01%   |
| IMC Networks Integrated Camera                                 | 26        | 2.9%    |
| Microdia Integrated_Webcam_HD                                  | 23        | 2.56%   |
| Alcor Micro USB 2.0 PC cam                                     | 21        | 2.34%   |
| Chicony Integrated Camera                                      | 20        | 2.23%   |
| Realtek Integrated_Webcam_HD                                   | 19        | 2.12%   |
| Chicony Lenovo EasyCamera                                      | 15        | 1.67%   |
| Chicony USB2.0 Camera                                          | 14        | 1.56%   |
| Syntek Integrated Camera                                       | 13        | 1.45%   |
| Sunplus Integrated_Webcam_HD                                   | 13        | 1.45%   |
| Chicony HD Webcam                                              | 13        | 1.45%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 12        | 1.34%   |
| Chicony TOSHIBA Web Camera - HD                                | 11        | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 10        | 1.11%   |
| Realtek USB Camera                                             | 9         | 1%      |
| Luxvisions Innotech Limited Integrated Camera                  | 9         | 1%      |
| Silicon Motion WebCam SC-0311139N                              | 8         | 0.89%   |
| Chicony USB2.0 VGA UVC WebCam                                  | 8         | 0.89%   |
| Bison SunplusIT Integrated Camera                              | 8         | 0.89%   |
| Bison Lenovo EasyCamera                                        | 8         | 0.89%   |
| Syntek EasyCamera                                              | 7         | 0.78%   |
| Realtek MTD camera                                             | 7         | 0.78%   |
| Chicony Integrated Camera (1280x720@30)                        | 7         | 0.78%   |
| Chicony HP TrueVision HD Camera                                | 7         | 0.78%   |
| Bison HD Webcam                                                | 7         | 0.78%   |
| Bison BisonCam, NB Pro                                         | 7         | 0.78%   |
| Z-Star Webcam                                                  | 6         | 0.67%   |
| Syntek Lenovo EasyCamera                                       | 6         | 0.67%   |
| Sunplus Asus Webcam                                            | 6         | 0.67%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 6         | 0.67%   |
| Microdia Laptop_Integrated_Webcam_HD                           | 6         | 0.67%   |
| Microdia Integrated Webcam                                     | 6         | 0.67%   |
| IMC Networks UVC VGA Webcam                                    | 6         | 0.67%   |
| Chicony HP Wide Vision HD Camera                               | 6         | 0.67%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam               | 6         | 0.67%   |
| Suyin 1.3M WebCam (notebook emachines E730, Acer sub-brand)    | 5         | 0.56%   |
| Realtek USB2.0 HD UVC WebCam                                   | 5         | 0.56%   |
| OmniVision OV2640 Webcam                                       | 5         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 40        | 32.52%  |
| Validity Sensors                   | 33        | 26.83%  |
| Shenzhen Goodix Technology         | 23        | 18.7%   |
| AuthenTec                          | 7         | 5.69%   |
| Upek                               | 6         | 4.88%   |
| Elan Microelectronics              | 6         | 4.88%   |
| LighTuning Technology              | 5         | 4.07%   |
| STMicroelectronics                 | 1         | 0.81%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.81%   |
| Focal-systems.Corp                 | 1         | 0.81%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 20        | 16.26%  |
| Shenzhen Goodix  FingerPrint Device                                        | 18        | 14.63%  |
| Synaptics  WBDI                                                            | 12        | 9.76%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 10        | 8.13%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 6         | 4.88%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 4.07%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 3.25%   |
| Shenzhen Goodix Fingerprint Reader                                         | 4         | 3.25%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.44%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 2.44%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 2.44%   |
| Elan ELAN:Fingerprint                                                      | 3         | 2.44%   |
| Elan ELAN:ARM-M4                                                           | 3         | 2.44%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.63%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.63%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.63%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.63%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.63%   |
| AuthenTec AES2810                                                          | 2         | 1.63%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.63%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.81%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.81%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 0.81%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.81%   |
| Synaptics UWP WBDI                                                         | 1         | 0.81%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.81%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.81%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.81%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.81%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.81%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.81%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.81%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.81%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.81%   |
| Unknown                                                                    | 1         | 0.81%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 22        | 62.86%  |
| Upek        | 9         | 25.71%  |
| Lenovo      | 2         | 5.71%   |
| O2 Micro    | 1         | 2.86%   |
| Alcor Micro | 1         | 2.86%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 25.71%  |
| Broadcom BCM5880 Secure Applications Processor                               | 7         | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 17.14%  |
| Broadcom 58200                                                               | 6         | 17.14%  |
| Broadcom 5880                                                                | 3         | 8.57%   |
| Lenovo Integrated Smart Card Reader                                          | 2         | 5.71%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.86%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 2.86%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 697       | 69.15%  |
| 1     | 277       | 27.48%  |
| 2     | 30        | 2.98%   |
| 3     | 3         | 0.3%    |
| 8     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 122       | 35.06%  |
| Graphics card            | 86        | 24.71%  |
| Net/wireless             | 45        | 12.93%  |
| Chipcard                 | 33        | 9.48%   |
| Camera                   | 15        | 4.31%   |
| Multimedia controller    | 13        | 3.74%   |
| Bluetooth                | 12        | 3.45%   |
| Communication controller | 6         | 1.72%   |
| Sound                    | 4         | 1.15%   |
| Net/ethernet             | 4         | 1.15%   |
| Network                  | 2         | 0.57%   |
| Modem                    | 2         | 0.57%   |
| Flash memory             | 2         | 0.57%   |
| Card reader              | 2         | 0.57%   |

