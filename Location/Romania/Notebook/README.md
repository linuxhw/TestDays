Linux in Romania - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Romania.

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

Total: 2028

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Acer          | Aspire A515-57              | [c7471afead](https://linux-hardware.org/?probe=c7471afead) | May 07, 2024 |
| HP            | EliteBook 840 G6            | [504b36774f](https://linux-hardware.org/?probe=504b36774f) | May 07, 2024 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [afb966db9e](https://linux-hardware.org/?probe=afb966db9e) | May 04, 2024 |
| ASUSTek       | ROG Strix G513RC_G513RC     | [c41b2ac54b](https://linux-hardware.org/?probe=c41b2ac54b) | May 04, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [ea3a8f97a7](https://linux-hardware.org/?probe=ea3a8f97a7) | May 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [ad6d7c5f93](https://linux-hardware.org/?probe=ad6d7c5f93) | May 03, 2024 |
| ASUSTek       | X553MA                      | [1aaeefe305](https://linux-hardware.org/?probe=1aaeefe305) | May 02, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [c23a3238c0](https://linux-hardware.org/?probe=c23a3238c0) | May 02, 2024 |
| Dell          | Inspiron 5567               | [caf8879e78](https://linux-hardware.org/?probe=caf8879e78) | Apr 27, 2024 |
| Toshiba       | Satellite C660              | [c2513f220d](https://linux-hardware.org/?probe=c2513f220d) | Apr 27, 2024 |
| Google        | Laser14                     | [5addd4566a](https://linux-hardware.org/?probe=5addd4566a) | Apr 27, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [86305e383e](https://linux-hardware.org/?probe=86305e383e) | Apr 25, 2024 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [113c93d444](https://linux-hardware.org/?probe=113c93d444) | Apr 25, 2024 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | [f537e8aab2](https://linux-hardware.org/?probe=f537e8aab2) | Apr 24, 2024 |
| Lenovo        | ThinkPad T480 20L6S0DH0V    | [28d54c7e4d](https://linux-hardware.org/?probe=28d54c7e4d) | Apr 22, 2024 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [a206f7f2d5](https://linux-hardware.org/?probe=a206f7f2d5) | Apr 21, 2024 |
| TUXEDO        | Stellaris/Polaris AMD Ge... | [bb18adad6a](https://linux-hardware.org/?probe=bb18adad6a) | Apr 19, 2024 |
| HP            | Pavilion Notebook           | [cee4508310](https://linux-hardware.org/?probe=cee4508310) | Apr 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [983a566cbf](https://linux-hardware.org/?probe=983a566cbf) | Apr 13, 2024 |
| BESSTAR Te... | X400                        | [0701fdbfed](https://linux-hardware.org/?probe=0701fdbfed) | Apr 12, 2024 |
| Lenovo        | ThinkPad E15 20RD005VRI     | [d7f5702701](https://linux-hardware.org/?probe=d7f5702701) | Apr 12, 2024 |
| HP            | Pavilion Notebook           | [07ccfe7f99](https://linux-hardware.org/?probe=07ccfe7f99) | Apr 11, 2024 |
| Lenovo        | Yoga Pro 7 14APH8 82Y8      | [85d3c8baf5](https://linux-hardware.org/?probe=85d3c8baf5) | Apr 10, 2024 |
| ASUSTek       | ROG Strix G531GU_G531GU     | [b264255cbe](https://linux-hardware.org/?probe=b264255cbe) | Apr 07, 2024 |
| ASUSTek       | ROG Strix G531GU_G531GU     | [65f080ba2d](https://linux-hardware.org/?probe=65f080ba2d) | Apr 06, 2024 |
| Google        | Landrid                     | [d4b1948b6a](https://linux-hardware.org/?probe=d4b1948b6a) | Apr 04, 2024 |
| ASUSTek       | ROG Zephyrus G16 GU605MI... | [4581288732](https://linux-hardware.org/?probe=4581288732) | Apr 04, 2024 |
| Acer          | Aspire E1-572G              | [7a19eed833](https://linux-hardware.org/?probe=7a19eed833) | Apr 03, 2024 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [054b7415b5](https://linux-hardware.org/?probe=054b7415b5) | Apr 01, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [0f82bff1ce](https://linux-hardware.org/?probe=0f82bff1ce) | Apr 01, 2024 |
| Dell          | Inspiron 5570               | [57667ea730](https://linux-hardware.org/?probe=57667ea730) | Mar 29, 2024 |
| Dell          | Inspiron 1520               | [1a4ee5c6ab](https://linux-hardware.org/?probe=1a4ee5c6ab) | Mar 27, 2024 |
| ASUSTek       | UX550VE                     | [25985cf7e8](https://linux-hardware.org/?probe=25985cf7e8) | Mar 27, 2024 |
| ASUSTek       | UX550VE                     | [433914ac7c](https://linux-hardware.org/?probe=433914ac7c) | Mar 27, 2024 |
| Acer          | Swift SF514-56T             | [37cec8bd6a](https://linux-hardware.org/?probe=37cec8bd6a) | Mar 24, 2024 |
| Lenovo        | G550 2958                   | [91d2b11e4d](https://linux-hardware.org/?probe=91d2b11e4d) | Mar 24, 2024 |
| Dell          | Inspiron 14-3452            | [1d762c03e9](https://linux-hardware.org/?probe=1d762c03e9) | Mar 21, 2024 |
| Dell          | Inspiron 14-3452            | [2951df6391](https://linux-hardware.org/?probe=2951df6391) | Mar 21, 2024 |
| Dell          | G7 7790                     | [6488d5dbe5](https://linux-hardware.org/?probe=6488d5dbe5) | Mar 21, 2024 |
| Dell          | G7 7790                     | [58718acc5f](https://linux-hardware.org/?probe=58718acc5f) | Mar 19, 2024 |
| Lenovo        | ThinkPad T480 20L6S4G72S    | [301d6aad48](https://linux-hardware.org/?probe=301d6aad48) | Mar 19, 2024 |
| HP            | ProBook 430 G5              | [cbe9e1dc0f](https://linux-hardware.org/?probe=cbe9e1dc0f) | Mar 16, 2024 |
| Dell          | Vostro 3525                 | [25cd61c444](https://linux-hardware.org/?probe=25cd61c444) | Mar 16, 2024 |
| ASUSTek       | ROG Strix G713PU_G713PU     | [307decbb24](https://linux-hardware.org/?probe=307decbb24) | Mar 16, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | [18da3a8d78](https://linux-hardware.org/?probe=18da3a8d78) | Mar 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [850ae02029](https://linux-hardware.org/?probe=850ae02029) | Mar 13, 2024 |
| Acer          | Aspire A315-59              | [f1c498121d](https://linux-hardware.org/?probe=f1c498121d) | Mar 13, 2024 |
| Lenovo        | ThinkPad L14 Gen 4 21H6S... | [de4a81edcc](https://linux-hardware.org/?probe=de4a81edcc) | Mar 12, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [879e485252](https://linux-hardware.org/?probe=879e485252) | Mar 11, 2024 |
| Alienware     | m15 R7 AMD                  | [e6f85671a4](https://linux-hardware.org/?probe=e6f85671a4) | Mar 10, 2024 |
| ASUSTek       | X550JX                      | [5b8d7edfa8](https://linux-hardware.org/?probe=5b8d7edfa8) | Mar 10, 2024 |
| ASUSTek       | X550JX                      | [0fd5f29628](https://linux-hardware.org/?probe=0fd5f29628) | Mar 09, 2024 |
| ASUSTek       | X205TAW                     | [6ed323ca5c](https://linux-hardware.org/?probe=6ed323ca5c) | Mar 07, 2024 |
| ASUSTek       | X205TAW                     | [2dd874e62c](https://linux-hardware.org/?probe=2dd874e62c) | Mar 07, 2024 |
| HP            | ProBook 450 G5              | [7e89a95523](https://linux-hardware.org/?probe=7e89a95523) | Mar 06, 2024 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [23a8bcc014](https://linux-hardware.org/?probe=23a8bcc014) | Mar 06, 2024 |
| Lenovo        | V15 G3 ABA 82TV             | [e25dd52aab](https://linux-hardware.org/?probe=e25dd52aab) | Mar 06, 2024 |
| HP            | Pavilion dv6000 (GH906EA... | [be0ca4a00c](https://linux-hardware.org/?probe=be0ca4a00c) | Mar 06, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [831ff2cb1b](https://linux-hardware.org/?probe=831ff2cb1b) | Mar 02, 2024 |
| Dell          | Latitude E6420              | [bfa7f2e249](https://linux-hardware.org/?probe=bfa7f2e249) | Feb 29, 2024 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | [b5cd8e1e86](https://linux-hardware.org/?probe=b5cd8e1e86) | Feb 28, 2024 |
| Toshiba       | Satellite C660              | [8a559e94c0](https://linux-hardware.org/?probe=8a559e94c0) | Feb 27, 2024 |
| HP            | OMEN by Laptop 15-dc0xxx    | [ce35471f83](https://linux-hardware.org/?probe=ce35471f83) | Feb 27, 2024 |
| Dell          | Precision M4500             | [9eb2dd262d](https://linux-hardware.org/?probe=9eb2dd262d) | Feb 26, 2024 |
| Acer          | TravelMate P256-MG          | [abcfd5362f](https://linux-hardware.org/?probe=abcfd5362f) | Feb 25, 2024 |
| Toshiba       | Satellite A500              | [ff10d941c4](https://linux-hardware.org/?probe=ff10d941c4) | Feb 25, 2024 |
| Dell          | Latitude E6510              | [a8457cc11f](https://linux-hardware.org/?probe=a8457cc11f) | Feb 25, 2024 |
| Lenovo        | ThinkPad T420 4236C92       | [57a7f3d065](https://linux-hardware.org/?probe=57a7f3d065) | Feb 25, 2024 |
| Dell          | Precision M4500             | [f6cefd913d](https://linux-hardware.org/?probe=f6cefd913d) | Feb 24, 2024 |
| Dell          | XPS 13 9370                 | [e94228e06b](https://linux-hardware.org/?probe=e94228e06b) | Feb 22, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [416de2c634](https://linux-hardware.org/?probe=416de2c634) | Feb 21, 2024 |
| Lenovo        | Legion Slim 7 16APH8 82Y... | [b8151c46bb](https://linux-hardware.org/?probe=b8151c46bb) | Feb 20, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | [3260a2265c](https://linux-hardware.org/?probe=3260a2265c) | Feb 18, 2024 |
| HP            | EliteBook 850 G2            | [a398d0bc5e](https://linux-hardware.org/?probe=a398d0bc5e) | Feb 16, 2024 |
| Google        | Berknip                     | [cab3f6a686](https://linux-hardware.org/?probe=cab3f6a686) | Feb 13, 2024 |
| Dell          | XPS 13 9370                 | [11b5a42b88](https://linux-hardware.org/?probe=11b5a42b88) | Feb 11, 2024 |
| Google        | Berknip                     | [b39f5eec0b](https://linux-hardware.org/?probe=b39f5eec0b) | Feb 11, 2024 |
| HP            | ENVY Laptop 16-h1xxx        | [5690cf9537](https://linux-hardware.org/?probe=5690cf9537) | Feb 10, 2024 |
| ASUSTek       | G750JM                      | [91c1ae83cb](https://linux-hardware.org/?probe=91c1ae83cb) | Feb 10, 2024 |
| HP            | ZBook Studio G5             | [ac8738f9d5](https://linux-hardware.org/?probe=ac8738f9d5) | Feb 09, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [6700a2fd4d](https://linux-hardware.org/?probe=6700a2fd4d) | Feb 09, 2024 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [238b0e7660](https://linux-hardware.org/?probe=238b0e7660) | Feb 09, 2024 |
| ASUSTek       | K54C                        | [56b8a644da](https://linux-hardware.org/?probe=56b8a644da) | Feb 08, 2024 |
| ASUSTek       | X550VC                      | [424775f910](https://linux-hardware.org/?probe=424775f910) | Feb 07, 2024 |
| Dell          | G15 5520                    | [1e1e027895](https://linux-hardware.org/?probe=1e1e027895) | Feb 07, 2024 |
| HP            | Laptop 14s-fq0xxx           | [6ae9e4d70e](https://linux-hardware.org/?probe=6ae9e4d70e) | Feb 06, 2024 |
| Dell          | Vostro 3525                 | [655a24d376](https://linux-hardware.org/?probe=655a24d376) | Feb 06, 2024 |
| Dell          | Vostro 3525                 | [7c0c3cb665](https://linux-hardware.org/?probe=7c0c3cb665) | Feb 06, 2024 |
| Dell          | Latitude E5430 non-vPro     | [3d2ef5ec7e](https://linux-hardware.org/?probe=3d2ef5ec7e) | Feb 05, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b663434440](https://linux-hardware.org/?probe=b663434440) | Feb 04, 2024 |
| ASUSTek       | X550VC                      | [274a4704a0](https://linux-hardware.org/?probe=274a4704a0) | Feb 02, 2024 |
| ASUSTek       | ROG Strix G634JZ_G634JZ     | [4b8399084a](https://linux-hardware.org/?probe=4b8399084a) | Feb 01, 2024 |
| Acer          | Nitro AN515-58              | [84c37d0192](https://linux-hardware.org/?probe=84c37d0192) | Feb 01, 2024 |
| HP            | Elite x2 1012 G1            | [44bbb3b748](https://linux-hardware.org/?probe=44bbb3b748) | Jan 31, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [16922386a7](https://linux-hardware.org/?probe=16922386a7) | Jan 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [028ce3b254](https://linux-hardware.org/?probe=028ce3b254) | Jan 29, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [91fddd3173](https://linux-hardware.org/?probe=91fddd3173) | Jan 28, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [f05cba633f](https://linux-hardware.org/?probe=f05cba633f) | Jan 28, 2024 |
| ASUSTek       | N551JX                      | [6a0be842aa](https://linux-hardware.org/?probe=6a0be842aa) | Jan 27, 2024 |
| Dell          | Inspiron N5040              | [7cd09c7dde](https://linux-hardware.org/?probe=7cd09c7dde) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [81338699ce](https://linux-hardware.org/?probe=81338699ce) | Jan 25, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [9f021a2102](https://linux-hardware.org/?probe=9f021a2102) | Jan 25, 2024 |
| Acer          | Aspire E1-572G              | [d94fb0b47b](https://linux-hardware.org/?probe=d94fb0b47b) | Jan 24, 2024 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [4b9301ae7f](https://linux-hardware.org/?probe=4b9301ae7f) | Jan 24, 2024 |
| Acer          | Aspire A315-35              | [40bb0f1f4d](https://linux-hardware.org/?probe=40bb0f1f4d) | Jan 24, 2024 |
| Dell          | Inspiron N5040              | [79bca2224b](https://linux-hardware.org/?probe=79bca2224b) | Jan 24, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [318e16ffb6](https://linux-hardware.org/?probe=318e16ffb6) | Jan 22, 2024 |
| Acer          | Aspire SW3-016              | [01ee7724e0](https://linux-hardware.org/?probe=01ee7724e0) | Jan 21, 2024 |
| Acer          | Aspire A315-35              | [baff1b7c03](https://linux-hardware.org/?probe=baff1b7c03) | Jan 20, 2024 |
| Acer          | Aspire A315-35              | [dafaf99dd0](https://linux-hardware.org/?probe=dafaf99dd0) | Jan 19, 2024 |
| Dell          | Latitude E6230              | [421a0c04cf](https://linux-hardware.org/?probe=421a0c04cf) | Jan 19, 2024 |
| Dell          | Latitude E6230              | [c5602b88c7](https://linux-hardware.org/?probe=c5602b88c7) | Jan 18, 2024 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [ca16a763c8](https://linux-hardware.org/?probe=ca16a763c8) | Jan 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [5ea527f9cc](https://linux-hardware.org/?probe=5ea527f9cc) | Jan 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [3c8a40dcc2](https://linux-hardware.org/?probe=3c8a40dcc2) | Jan 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [4a57c65ec3](https://linux-hardware.org/?probe=4a57c65ec3) | Jan 15, 2024 |
| Lenovo        | ThinkPad T440 20B7S1WJ00    | [215c45abef](https://linux-hardware.org/?probe=215c45abef) | Jan 11, 2024 |
| HP            | Laptop 15s-fq1xxx           | [9960b657ec](https://linux-hardware.org/?probe=9960b657ec) | Jan 11, 2024 |
| HP            | Laptop 15s-fq1xxx           | [d1041fde50](https://linux-hardware.org/?probe=d1041fde50) | Jan 11, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [a4897703b1](https://linux-hardware.org/?probe=a4897703b1) | Jan 10, 2024 |
| Complet       | MY8315XX                    | [cb08af3409](https://linux-hardware.org/?probe=cb08af3409) | Jan 07, 2024 |
| HP            | Pavilion Laptop 15-eg3xx... | [61066d4150](https://linux-hardware.org/?probe=61066d4150) | Jan 07, 2024 |
| Lenovo        | ThinkPad T480s 20L8S0R30... | [9cfe296019](https://linux-hardware.org/?probe=9cfe296019) | Jan 07, 2024 |
| HP            | 250 G7 Notebook PC          | [7f25d85205](https://linux-hardware.org/?probe=7f25d85205) | Jan 07, 2024 |
| Sony          | SVF1521H1EW                 | [1939183179](https://linux-hardware.org/?probe=1939183179) | Jan 07, 2024 |
| Sony          | SVF1521H1EW                 | [f73763fd0c](https://linux-hardware.org/?probe=f73763fd0c) | Jan 06, 2024 |
| Lenovo        | ThinkPad T410 2518FMG       | [d2e50fca98](https://linux-hardware.org/?probe=d2e50fca98) | Jan 03, 2024 |
| Lenovo        | ThinkPad T410 2518FMG       | [e1d4b75f1c](https://linux-hardware.org/?probe=e1d4b75f1c) | Jan 03, 2024 |
| HUAWEI        | KLVL-WXX9                   | [28ad8513b4](https://linux-hardware.org/?probe=28ad8513b4) | Dec 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [8f3ab867ea](https://linux-hardware.org/?probe=8f3ab867ea) | Dec 30, 2023 |
| MSI           | GP75 Leopard 9SE            | [29e0740b9d](https://linux-hardware.org/?probe=29e0740b9d) | Dec 29, 2023 |
| Fujitsu       | LIFEBOOK T902               | [050f6ca09e](https://linux-hardware.org/?probe=050f6ca09e) | Dec 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [58080b01c8](https://linux-hardware.org/?probe=58080b01c8) | Dec 27, 2023 |
| ASUSTek       | G750JM                      | [fcda025864](https://linux-hardware.org/?probe=fcda025864) | Dec 26, 2023 |
| Acer          | Aspire A315-35              | [a3c4869087](https://linux-hardware.org/?probe=a3c4869087) | Dec 24, 2023 |
| ASUSTek       | G750JM                      | [e53cfaf52c](https://linux-hardware.org/?probe=e53cfaf52c) | Dec 24, 2023 |
| Acer          | Aspire 5742Z                | [ddf1553f4b](https://linux-hardware.org/?probe=ddf1553f4b) | Dec 24, 2023 |
| HP            | EliteBook 840 G5            | [6406b552c4](https://linux-hardware.org/?probe=6406b552c4) | Dec 23, 2023 |
| Allview       | Allbook I/1                 | [960dfde4cd](https://linux-hardware.org/?probe=960dfde4cd) | Dec 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | [9e521ad3e9](https://linux-hardware.org/?probe=9e521ad3e9) | Dec 22, 2023 |
| Acer          | Aspire A315-35              | [52af26d8a1](https://linux-hardware.org/?probe=52af26d8a1) | Dec 21, 2023 |
| HP            | EliteBook 840 G6            | [64ec373e84](https://linux-hardware.org/?probe=64ec373e84) | Dec 20, 2023 |
| Lenovo        | Legion 5 15IMH6 82NL        | [e54630a5d8](https://linux-hardware.org/?probe=e54630a5d8) | Dec 18, 2023 |
| Dell          | Vostro 15 3515              | [baf5b47a47](https://linux-hardware.org/?probe=baf5b47a47) | Dec 18, 2023 |
| ASUSTek       | X541UVK                     | [a6ae535887](https://linux-hardware.org/?probe=a6ae535887) | Dec 18, 2023 |
| Lenovo        | ThinkPad P52 20MAS19500     | [7067fb02ed](https://linux-hardware.org/?probe=7067fb02ed) | Dec 18, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [8507460974](https://linux-hardware.org/?probe=8507460974) | Dec 18, 2023 |
| PC Special... | MP 17 Recoil Master         | [f199dc6e36](https://linux-hardware.org/?probe=f199dc6e36) | Dec 17, 2023 |
| Toshiba       | Satellite C50-A-1HF         | [ac7985ff69](https://linux-hardware.org/?probe=ac7985ff69) | Dec 17, 2023 |
| Dell          | Inspiron 5559               | [6920e9d7c2](https://linux-hardware.org/?probe=6920e9d7c2) | Dec 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [6d72d7366b](https://linux-hardware.org/?probe=6d72d7366b) | Dec 15, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [d8a98a209a](https://linux-hardware.org/?probe=d8a98a209a) | Dec 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [c839de638b](https://linux-hardware.org/?probe=c839de638b) | Dec 15, 2023 |
| Acer          | Aspire A315-35              | [f7b0d4b746](https://linux-hardware.org/?probe=f7b0d4b746) | Dec 14, 2023 |
| HP            | Pavilion dv6500             | [cdde8c0b3f](https://linux-hardware.org/?probe=cdde8c0b3f) | Dec 13, 2023 |
| Lenovo        | Z710 20250                  | [0ffc45c096](https://linux-hardware.org/?probe=0ffc45c096) | Dec 13, 2023 |
| HP            | Laptop 15-fc0xxx            | [0ad101e0f2](https://linux-hardware.org/?probe=0ad101e0f2) | Dec 12, 2023 |
| HP            | Presario CQ58               | [b23d694ab4](https://linux-hardware.org/?probe=b23d694ab4) | Dec 11, 2023 |
| Dell          | Precision 5530              | [eee9114e4b](https://linux-hardware.org/?probe=eee9114e4b) | Dec 10, 2023 |
| Acer          | Aspire E5-575G              | [48fffc72b6](https://linux-hardware.org/?probe=48fffc72b6) | Dec 10, 2023 |
| ASUSTek       | X550VC                      | [e2c932c285](https://linux-hardware.org/?probe=e2c932c285) | Dec 09, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [baa82e571f](https://linux-hardware.org/?probe=baa82e571f) | Dec 09, 2023 |
| HP            | Victus by Laptop 16-e0xx... | [551b412a34](https://linux-hardware.org/?probe=551b412a34) | Dec 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [587ff35c26](https://linux-hardware.org/?probe=587ff35c26) | Dec 08, 2023 |
| Dell          | Vostro 15 3515              | [0257ed619f](https://linux-hardware.org/?probe=0257ed619f) | Dec 08, 2023 |
| Lenovo        | Z50-70 20354                | [ba354037ff](https://linux-hardware.org/?probe=ba354037ff) | Dec 07, 2023 |
| Acer          | TravelMate P645-S           | [e44f06b326](https://linux-hardware.org/?probe=e44f06b326) | Dec 07, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [46bc5ee727](https://linux-hardware.org/?probe=46bc5ee727) | Dec 06, 2023 |
| Acer          | Aspire A314-23P             | [ad97d6f3c6](https://linux-hardware.org/?probe=ad97d6f3c6) | Dec 05, 2023 |
| HP            | 550                         | [a3dc2d4062](https://linux-hardware.org/?probe=a3dc2d4062) | Dec 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [8463f6c28f](https://linux-hardware.org/?probe=8463f6c28f) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [f8a528e1d6](https://linux-hardware.org/?probe=f8a528e1d6) | Dec 03, 2023 |
| Acer          | Aspire 8951G                | [f98b449dba](https://linux-hardware.org/?probe=f98b449dba) | Dec 03, 2023 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [20a5a6a137](https://linux-hardware.org/?probe=20a5a6a137) | Dec 03, 2023 |
| Lenovo        | IdeaPad Slim 5 14IRL8 82... | [49c0a7990e](https://linux-hardware.org/?probe=49c0a7990e) | Dec 01, 2023 |
| Acer          | Aspire ES1-523              | [10c0db94d1](https://linux-hardware.org/?probe=10c0db94d1) | Nov 29, 2023 |
| Dell          | Inspiron N5030              | [cf3da3211d](https://linux-hardware.org/?probe=cf3da3211d) | Nov 28, 2023 |
| MSI           | GP75 Leopard 9SE            | [60c7835d8c](https://linux-hardware.org/?probe=60c7835d8c) | Nov 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | [5fabcb33c4](https://linux-hardware.org/?probe=5fabcb33c4) | Nov 27, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [0ddcbc9eb9](https://linux-hardware.org/?probe=0ddcbc9eb9) | Nov 27, 2023 |
| Lenovo        | 15ARE05 81W4                | [c3763733da](https://linux-hardware.org/?probe=c3763733da) | Nov 27, 2023 |
| Lenovo        | 15ARE05 81W4                | [4fa9ab8a76](https://linux-hardware.org/?probe=4fa9ab8a76) | Nov 27, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [c887e86fe4](https://linux-hardware.org/?probe=c887e86fe4) | Nov 25, 2023 |
| Dell          | Latitude 7400               | [86a9de8212](https://linux-hardware.org/?probe=86a9de8212) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [7478563980](https://linux-hardware.org/?probe=7478563980) | Nov 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a8b99ab7f3](https://linux-hardware.org/?probe=a8b99ab7f3) | Nov 23, 2023 |
| Acer          | Aspire A315-35              | [6115c9c76e](https://linux-hardware.org/?probe=6115c9c76e) | Nov 23, 2023 |
| Valve         | Jupiter                     | [0454a567a0](https://linux-hardware.org/?probe=0454a567a0) | Nov 21, 2023 |
| Dell          | Vostro 3525                 | [2995eb87c1](https://linux-hardware.org/?probe=2995eb87c1) | Nov 21, 2023 |
| Acer          | Aspire A315-35              | [78dac027a1](https://linux-hardware.org/?probe=78dac027a1) | Nov 19, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | [cc9d93b28f](https://linux-hardware.org/?probe=cc9d93b28f) | Nov 19, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [f5c9812962](https://linux-hardware.org/?probe=f5c9812962) | Nov 19, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [6e4144386d](https://linux-hardware.org/?probe=6e4144386d) | Nov 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [55df37c5d0](https://linux-hardware.org/?probe=55df37c5d0) | Nov 17, 2023 |
| HP            | EliteBook 735 G5            | [49ea9a3b35](https://linux-hardware.org/?probe=49ea9a3b35) | Nov 15, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D40... | [ffc320e32c](https://linux-hardware.org/?probe=ffc320e32c) | Nov 15, 2023 |
| Dell          | Latitude 5521               | [2cd2e72764](https://linux-hardware.org/?probe=2cd2e72764) | Nov 15, 2023 |
| Lenovo        | IdeaPad Slim 5 14IAH8 83... | [e33ce14e30](https://linux-hardware.org/?probe=e33ce14e30) | Nov 14, 2023 |
| Dell          | XPS 15 7590                 | [da50e3550f](https://linux-hardware.org/?probe=da50e3550f) | Nov 14, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | [e8803a2d63](https://linux-hardware.org/?probe=e8803a2d63) | Nov 13, 2023 |
| Allview       | Allbook I/1                 | [2da284e5a6](https://linux-hardware.org/?probe=2da284e5a6) | Nov 11, 2023 |
| Jumper        | EZbook                      | [f7f10f7817](https://linux-hardware.org/?probe=f7f10f7817) | Nov 11, 2023 |
| Allview       | Allbook I/1                 | [4ea9038785](https://linux-hardware.org/?probe=4ea9038785) | Nov 10, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | [ea4a2b9084](https://linux-hardware.org/?probe=ea4a2b9084) | Nov 07, 2023 |
| Acer          | Aspire A315-35              | [61fdbe9ec2](https://linux-hardware.org/?probe=61fdbe9ec2) | Nov 07, 2023 |
| ASUSTek       | G750JS                      | [b64eb3798d](https://linux-hardware.org/?probe=b64eb3798d) | Nov 07, 2023 |
| ASUSTek       | N552VW                      | [b8f226f7f0](https://linux-hardware.org/?probe=b8f226f7f0) | Nov 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [ce00056643](https://linux-hardware.org/?probe=ce00056643) | Nov 07, 2023 |
| Acer          | Aspire A314-23P             | [1e3cdf0bf2](https://linux-hardware.org/?probe=1e3cdf0bf2) | Nov 04, 2023 |
| Dell          | Vostro 3525                 | [48103e7e91](https://linux-hardware.org/?probe=48103e7e91) | Nov 03, 2023 |
| Dell          | Latitude 7370               | [b16724db59](https://linux-hardware.org/?probe=b16724db59) | Nov 01, 2023 |
| Google        | Akemi                       | [75082d5cf9](https://linux-hardware.org/?probe=75082d5cf9) | Nov 01, 2023 |
| ASUSTek       | X541UAK                     | [d4630a5c8b](https://linux-hardware.org/?probe=d4630a5c8b) | Nov 01, 2023 |
| Acer          | Aspire A315-35              | [c26ec81fab](https://linux-hardware.org/?probe=c26ec81fab) | Oct 31, 2023 |
| HP            | 255 G8 Notebook PC          | [941ca289ce](https://linux-hardware.org/?probe=941ca289ce) | Oct 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9f0452aba6](https://linux-hardware.org/?probe=9f0452aba6) | Oct 29, 2023 |
| ASUSTek       | G750JM                      | [01e0620386](https://linux-hardware.org/?probe=01e0620386) | Oct 29, 2023 |
| ASUSTek       | G56JR                       | [8e871997f7](https://linux-hardware.org/?probe=8e871997f7) | Oct 29, 2023 |
| ASUSTek       | G56JR                       | [f8e77bd53a](https://linux-hardware.org/?probe=f8e77bd53a) | Oct 28, 2023 |
| Lenovo        | ThinkPad T480 20L6S5FF0S    | [4a4fe99b2d](https://linux-hardware.org/?probe=4a4fe99b2d) | Oct 23, 2023 |
| Dell          | XPS 13 9370                 | [f45a5143fc](https://linux-hardware.org/?probe=f45a5143fc) | Oct 23, 2023 |
| ASUSTek       | ZenBook UX534FTC            | [a268a7a10e](https://linux-hardware.org/?probe=a268a7a10e) | Oct 22, 2023 |
| Acer          | Aspire A315-35              | [ee15c1dbea](https://linux-hardware.org/?probe=ee15c1dbea) | Oct 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [77fb62615e](https://linux-hardware.org/?probe=77fb62615e) | Oct 22, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [43f9375597](https://linux-hardware.org/?probe=43f9375597) | Oct 21, 2023 |
| ASUSTek       | G750JM                      | [0f5885bc27](https://linux-hardware.org/?probe=0f5885bc27) | Oct 17, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [9f9777f778](https://linux-hardware.org/?probe=9f9777f778) | Oct 17, 2023 |
| Lenovo        | 15ARE05 81W4                | [dcb09acd04](https://linux-hardware.org/?probe=dcb09acd04) | Oct 17, 2023 |
| ASUSTek       | X556UQK                     | [c430358d6a](https://linux-hardware.org/?probe=c430358d6a) | Oct 17, 2023 |
| Toshiba       | Satellite C660              | [b96d2e0be9](https://linux-hardware.org/?probe=b96d2e0be9) | Oct 16, 2023 |
| HP            | 2000                        | [c2669ff6cb](https://linux-hardware.org/?probe=c2669ff6cb) | Oct 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [471a6f3119](https://linux-hardware.org/?probe=471a6f3119) | Oct 16, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [f16973062f](https://linux-hardware.org/?probe=f16973062f) | Oct 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [66a5a05425](https://linux-hardware.org/?probe=66a5a05425) | Oct 15, 2023 |
| Toshiba       | Satellite CL10-C-102        | [cdaab4e230](https://linux-hardware.org/?probe=cdaab4e230) | Oct 15, 2023 |
| Acer          | Aspire A515-57              | [ca520343c8](https://linux-hardware.org/?probe=ca520343c8) | Oct 13, 2023 |
| Lenovo        | 15ARE05 81W4                | [c0066cda83](https://linux-hardware.org/?probe=c0066cda83) | Oct 13, 2023 |
| HP            | 470 17 inch G9              | [d138f8f9f3](https://linux-hardware.org/?probe=d138f8f9f3) | Oct 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [662b033cee](https://linux-hardware.org/?probe=662b033cee) | Oct 12, 2023 |
| Acer          | Aspire A315-35              | [3069c746fd](https://linux-hardware.org/?probe=3069c746fd) | Oct 12, 2023 |
| BESSTAR Te... | X400                        | [c955c44ef3](https://linux-hardware.org/?probe=c955c44ef3) | Oct 10, 2023 |
| Dell          | Vostro 3525                 | [cb78c82e7a](https://linux-hardware.org/?probe=cb78c82e7a) | Oct 09, 2023 |
| Lenovo        | G580 20150                  | [fa47449843](https://linux-hardware.org/?probe=fa47449843) | Oct 08, 2023 |
| Dell          | Vostro 3525                 | [cad844c720](https://linux-hardware.org/?probe=cad844c720) | Oct 07, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [60d5b8f4c0](https://linux-hardware.org/?probe=60d5b8f4c0) | Oct 06, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [99f8282319](https://linux-hardware.org/?probe=99f8282319) | Oct 06, 2023 |
| HP            | ProBook 6450b               | [f597cfe9d1](https://linux-hardware.org/?probe=f597cfe9d1) | Oct 05, 2023 |
| Google        | Magpie                      | [91fa583b13](https://linux-hardware.org/?probe=91fa583b13) | Oct 05, 2023 |
| HP            | OMEN by Laptop 17-an0xx     | [02ff66cc0c](https://linux-hardware.org/?probe=02ff66cc0c) | Oct 05, 2023 |
| Acer          | Aspire V5-531               | [555d578f86](https://linux-hardware.org/?probe=555d578f86) | Oct 05, 2023 |
| Dell          | Latitude E6420              | [504010f96c](https://linux-hardware.org/?probe=504010f96c) | Oct 04, 2023 |
| Acer          | Aspire V5-531               | [b6a9eaaec5](https://linux-hardware.org/?probe=b6a9eaaec5) | Oct 03, 2023 |
| Acer          | Aspire A715-51G             | [6bc4edfef5](https://linux-hardware.org/?probe=6bc4edfef5) | Oct 02, 2023 |
| Acer          | Aspire A715-51G             | [a9b3098036](https://linux-hardware.org/?probe=a9b3098036) | Oct 02, 2023 |
| Google        | Magpie                      | [32a7bba307](https://linux-hardware.org/?probe=32a7bba307) | Oct 01, 2023 |
| HP            | 470 17 inch G9              | [c6043cc6cc](https://linux-hardware.org/?probe=c6043cc6cc) | Oct 01, 2023 |
| Toshiba       | Satellite C850-D4K          | [47d93b3030](https://linux-hardware.org/?probe=47d93b3030) | Oct 01, 2023 |
| HUAWEI        | NBD-WXX9                    | [c8a525522f](https://linux-hardware.org/?probe=c8a525522f) | Sep 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [fb4cde69b8](https://linux-hardware.org/?probe=fb4cde69b8) | Sep 28, 2023 |
| Lenovo        | LOQ 15IRH8 82XV             | [a1e01ab80d](https://linux-hardware.org/?probe=a1e01ab80d) | Sep 25, 2023 |
| ASUSTek       | K53TK                       | [65e95a03e9](https://linux-hardware.org/?probe=65e95a03e9) | Sep 22, 2023 |
| ASUSTek       | K53TK                       | [34857762c0](https://linux-hardware.org/?probe=34857762c0) | Sep 21, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | [45f00aaf92](https://linux-hardware.org/?probe=45f00aaf92) | Sep 21, 2023 |
| Dell          | Latitude 5420               | [c40b9df526](https://linux-hardware.org/?probe=c40b9df526) | Sep 21, 2023 |
| Dell          | Latitude 5420               | [9caba9ee44](https://linux-hardware.org/?probe=9caba9ee44) | Sep 21, 2023 |
| MSI           | GP75 Leopard 9SE            | [07431109a7](https://linux-hardware.org/?probe=07431109a7) | Sep 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [365a5e674f](https://linux-hardware.org/?probe=365a5e674f) | Sep 15, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [eaa723190d](https://linux-hardware.org/?probe=eaa723190d) | Sep 15, 2023 |
| Acer          | Aspire A315-35              | [356d6d3e13](https://linux-hardware.org/?probe=356d6d3e13) | Sep 15, 2023 |
| Acer          | Aspire A315-35              | [7ae470ffa8](https://linux-hardware.org/?probe=7ae470ffa8) | Sep 14, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [d27fa5404b](https://linux-hardware.org/?probe=d27fa5404b) | Sep 14, 2023 |
| Acer          | Nitro AN515-58              | [78a9c8ba47](https://linux-hardware.org/?probe=78a9c8ba47) | Sep 12, 2023 |
| Acer          | Nitro AN515-58              | [a8f64806fe](https://linux-hardware.org/?probe=a8f64806fe) | Sep 12, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [e1b135961f](https://linux-hardware.org/?probe=e1b135961f) | Sep 12, 2023 |
| ASUSTek       | X550VX                      | [b1b59ca70c](https://linux-hardware.org/?probe=b1b59ca70c) | Sep 10, 2023 |
| HP            | ProBook 6570b               | [f66ec50e55](https://linux-hardware.org/?probe=f66ec50e55) | Sep 05, 2023 |
| HP            | ProBook 6570b               | [9a31047350](https://linux-hardware.org/?probe=9a31047350) | Sep 05, 2023 |
| Acer          | Nitro AN515-41              | [8d55fa5be4](https://linux-hardware.org/?probe=8d55fa5be4) | Sep 03, 2023 |
| HP            | 15                          | [db9d960b39](https://linux-hardware.org/?probe=db9d960b39) | Sep 03, 2023 |
| HP            | 250 G5 Notebook PC          | [66df65e0f0](https://linux-hardware.org/?probe=66df65e0f0) | Sep 02, 2023 |
| Toshiba       | Satellite C660              | [d3c3b72e39](https://linux-hardware.org/?probe=d3c3b72e39) | Sep 01, 2023 |
| Acer          | TMP645-M                    | [17838ce9b0](https://linux-hardware.org/?probe=17838ce9b0) | Aug 30, 2023 |
| ASUSTek       | G750JM                      | [ca4dd5a11e](https://linux-hardware.org/?probe=ca4dd5a11e) | Aug 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d036282290](https://linux-hardware.org/?probe=d036282290) | Aug 29, 2023 |
| ASUSTek       | X550LD                      | [b866599fbc](https://linux-hardware.org/?probe=b866599fbc) | Aug 29, 2023 |
| MSI           | GP75 Leopard 9SE            | [a8a97f9555](https://linux-hardware.org/?probe=a8a97f9555) | Aug 27, 2023 |
| HP            | 250 G7 Notebook PC          | [c4be1d7e95](https://linux-hardware.org/?probe=c4be1d7e95) | Aug 27, 2023 |
| MSI           | GP75 Leopard 9SE            | [db9336b4db](https://linux-hardware.org/?probe=db9336b4db) | Aug 26, 2023 |
| ASUSTek       | K73SV                       | [7aca2d97c0](https://linux-hardware.org/?probe=7aca2d97c0) | Aug 25, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b3f1d927a1](https://linux-hardware.org/?probe=b3f1d927a1) | Aug 21, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [d7b6d2a997](https://linux-hardware.org/?probe=d7b6d2a997) | Aug 21, 2023 |
| Acer          | Aspire A315-59              | [8946b925ea](https://linux-hardware.org/?probe=8946b925ea) | Aug 18, 2023 |
| Acer          | Aspire ES1-311              | [3fa65d407a](https://linux-hardware.org/?probe=3fa65d407a) | Aug 17, 2023 |
| HP            | Compaq 6710b (FG040EC#AB... | [a0cd8c1b40](https://linux-hardware.org/?probe=a0cd8c1b40) | Aug 16, 2023 |
| Toshiba       | Satellite C660              | [8bc67959d1](https://linux-hardware.org/?probe=8bc67959d1) | Aug 16, 2023 |
| ASUSTek       | GL552JX                     | [9594a231bd](https://linux-hardware.org/?probe=9594a231bd) | Aug 16, 2023 |
| Lenovo        | ThinkPad T560 20FJS1J200    | [f0d90b715d](https://linux-hardware.org/?probe=f0d90b715d) | Aug 15, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [18d3d9a7c1](https://linux-hardware.org/?probe=18d3d9a7c1) | Aug 14, 2023 |
| Allview       | Allbook H                   | [1a8e5e7f8f](https://linux-hardware.org/?probe=1a8e5e7f8f) | Aug 13, 2023 |
| HP            | Pavilion Notebook           | [7fd3205fde](https://linux-hardware.org/?probe=7fd3205fde) | Aug 11, 2023 |
| ASUSTek       | X541UVK                     | [77ec1f7364](https://linux-hardware.org/?probe=77ec1f7364) | Aug 09, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [ce593ff6c7](https://linux-hardware.org/?probe=ce593ff6c7) | Aug 07, 2023 |
| Acer          | AO756                       | [60475c9d52](https://linux-hardware.org/?probe=60475c9d52) | Aug 06, 2023 |
| WEIGO         | CDA-141AU                   | [35c705bd70](https://linux-hardware.org/?probe=35c705bd70) | Aug 05, 2023 |
| HP            | Laptop 14s-fq0xxx           | [0a7b2a3fcc](https://linux-hardware.org/?probe=0a7b2a3fcc) | Aug 03, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [9171e8e6b9](https://linux-hardware.org/?probe=9171e8e6b9) | Aug 03, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [8de1f944a7](https://linux-hardware.org/?probe=8de1f944a7) | Jul 30, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [d1bf55b135](https://linux-hardware.org/?probe=d1bf55b135) | Jul 29, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [ea8a893b11](https://linux-hardware.org/?probe=ea8a893b11) | Jul 29, 2023 |
| Lenovo        | ThinkPad W541 20EFS00N00    | [c9f80b56fc](https://linux-hardware.org/?probe=c9f80b56fc) | Jul 28, 2023 |
| ASUSTek       | X540LJ                      | [798cadd754](https://linux-hardware.org/?probe=798cadd754) | Jul 25, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [e9a58d14e7](https://linux-hardware.org/?probe=e9a58d14e7) | Jul 20, 2023 |
| Dell          | Latitude 5590               | [93857a3b66](https://linux-hardware.org/?probe=93857a3b66) | Jul 18, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [dac4434339](https://linux-hardware.org/?probe=dac4434339) | Jul 18, 2023 |
| HP            | ProBook 450 G5              | [3dfd41fda9](https://linux-hardware.org/?probe=3dfd41fda9) | Jul 17, 2023 |
| HP            | ProBook 450 G5              | [c5bee4d8fe](https://linux-hardware.org/?probe=c5bee4d8fe) | Jul 17, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [501969ed00](https://linux-hardware.org/?probe=501969ed00) | Jul 15, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [052b5c1741](https://linux-hardware.org/?probe=052b5c1741) | Jul 12, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | [9fc68063e3](https://linux-hardware.org/?probe=9fc68063e3) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [f35543549c](https://linux-hardware.org/?probe=f35543549c) | Jul 11, 2023 |
| Unknown       | HP Chromebook 14            | [63b183aa51](https://linux-hardware.org/?probe=63b183aa51) | Jul 11, 2023 |
| Fujitsu       | LIFEBOOK LH532              | [3cad86057a](https://linux-hardware.org/?probe=3cad86057a) | Jul 09, 2023 |
| Lenovo        | V145-15AST 81MT             | [a29509646a](https://linux-hardware.org/?probe=a29509646a) | Jul 08, 2023 |
| Dell          | Latitude 3500               | [38a0d6b099](https://linux-hardware.org/?probe=38a0d6b099) | Jul 08, 2023 |
| Dell          | Studio 1749                 | [fe1e5d7b8f](https://linux-hardware.org/?probe=fe1e5d7b8f) | Jul 05, 2023 |
| HP            | OMEN by Laptop 17-cb1xxx    | [dbf87e0eec](https://linux-hardware.org/?probe=dbf87e0eec) | Jul 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [8862b2d8db](https://linux-hardware.org/?probe=8862b2d8db) | Jun 25, 2023 |
| Acer          | Aspire A517-51G             | [dc2aebbc48](https://linux-hardware.org/?probe=dc2aebbc48) | Jun 24, 2023 |
| Lenovo        | Yoga Pro 7 14IRH8 82Y7      | [a74b5c2880](https://linux-hardware.org/?probe=a74b5c2880) | Jun 24, 2023 |
| Acer          | Aspire A315-58G             | [ea2b8a58b1](https://linux-hardware.org/?probe=ea2b8a58b1) | Jun 22, 2023 |
| Acer          | Swift SF314-52G             | [4eab971a60](https://linux-hardware.org/?probe=4eab971a60) | Jun 21, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [1c9456fd1d](https://linux-hardware.org/?probe=1c9456fd1d) | Jun 20, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [530f6272c9](https://linux-hardware.org/?probe=530f6272c9) | Jun 20, 2023 |
| ASUSTek       | G750JM                      | [928b30815b](https://linux-hardware.org/?probe=928b30815b) | Jun 18, 2023 |
| Acer          | Aspire A315-33              | [c6a929a9ec](https://linux-hardware.org/?probe=c6a929a9ec) | Jun 17, 2023 |
| Acer          | Aspire A315-33              | [d72b8e616f](https://linux-hardware.org/?probe=d72b8e616f) | Jun 17, 2023 |
| Acer          | Aspire A715-71G             | [0ef00ccccc](https://linux-hardware.org/?probe=0ef00ccccc) | Jun 16, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [2346d706e3](https://linux-hardware.org/?probe=2346d706e3) | Jun 15, 2023 |
| Dell          | Inspiron 5505               | [7747deeb57](https://linux-hardware.org/?probe=7747deeb57) | Jun 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [e073b99b63](https://linux-hardware.org/?probe=e073b99b63) | Jun 13, 2023 |
| ASUSTek       | G750JM                      | [e722fda49e](https://linux-hardware.org/?probe=e722fda49e) | Jun 13, 2023 |
| MSI           | GP75 Leopard 9SE            | [9e763f2e63](https://linux-hardware.org/?probe=9e763f2e63) | Jun 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [b7ab29fbb5](https://linux-hardware.org/?probe=b7ab29fbb5) | Jun 06, 2023 |
| MSI           | GP75 Leopard 9SE            | [05530e670e](https://linux-hardware.org/?probe=05530e670e) | Jun 06, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [ea07821e39](https://linux-hardware.org/?probe=ea07821e39) | Jun 05, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [1285aacf1b](https://linux-hardware.org/?probe=1285aacf1b) | Jun 04, 2023 |
| ASUSTek       | Zenbook UM5401RA_RM5401R... | [763a52f3e8](https://linux-hardware.org/?probe=763a52f3e8) | Jun 03, 2023 |
| HP            | ENVY 17                     | [79fd438f05](https://linux-hardware.org/?probe=79fd438f05) | Jun 03, 2023 |
| Dell          | Vostro 1015                 | [055866f703](https://linux-hardware.org/?probe=055866f703) | Jun 02, 2023 |
| Dell          | Inspiron 5567               | [bd3a6c5bd8](https://linux-hardware.org/?probe=bd3a6c5bd8) | Jun 02, 2023 |
| Acer          | Aspire A517-51G             | [dc0e29f0bb](https://linux-hardware.org/?probe=dc0e29f0bb) | Jun 02, 2023 |
| Acer          | Aspire A517-51G             | [693005f5b4](https://linux-hardware.org/?probe=693005f5b4) | Jun 02, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | [1f18cef2df](https://linux-hardware.org/?probe=1f18cef2df) | Jun 01, 2023 |
| Lenovo        | ThinkPad T430s 2352CTO      | [7ae3edd73e](https://linux-hardware.org/?probe=7ae3edd73e) | Jun 01, 2023 |
| Acer          | Aspire A515-45              | [f93dd394e8](https://linux-hardware.org/?probe=f93dd394e8) | May 31, 2023 |
| Dell          | Vostro 15 3515              | [6bec5a03df](https://linux-hardware.org/?probe=6bec5a03df) | May 30, 2023 |
| Dell          | Latitude E6440              | [821e3e3246](https://linux-hardware.org/?probe=821e3e3246) | May 27, 2023 |
| HP            | Laptop 17-cn0xxx            | [c8c9f63237](https://linux-hardware.org/?probe=c8c9f63237) | May 25, 2023 |
| Dell          | G15 5510                    | [325fcf6e78](https://linux-hardware.org/?probe=325fcf6e78) | May 25, 2023 |
| HP            | ProBook 6440b               | [5ed14b01a3](https://linux-hardware.org/?probe=5ed14b01a3) | May 25, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [61b85cdced](https://linux-hardware.org/?probe=61b85cdced) | May 24, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | [b167237d46](https://linux-hardware.org/?probe=b167237d46) | May 24, 2023 |
| Valve         | Jupiter                     | [117db8031d](https://linux-hardware.org/?probe=117db8031d) | May 24, 2023 |
| Dell          | Precision 7540              | [65605ee5e8](https://linux-hardware.org/?probe=65605ee5e8) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [a1e2fa6222](https://linux-hardware.org/?probe=a1e2fa6222) | May 24, 2023 |
| Lenovo        | V130-15IGM 81HL             | [504a24887e](https://linux-hardware.org/?probe=504a24887e) | May 24, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | [cb3e4d2c2b](https://linux-hardware.org/?probe=cb3e4d2c2b) | May 24, 2023 |
| Allview       | Allbook H                   | [8b0c0a3436](https://linux-hardware.org/?probe=8b0c0a3436) | May 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [64ceddcdd4](https://linux-hardware.org/?probe=64ceddcdd4) | May 24, 2023 |
| Dell          | G15 5510                    | [730985e467](https://linux-hardware.org/?probe=730985e467) | May 24, 2023 |
| Dell          | Inspiron 1501               | [4703a17f03](https://linux-hardware.org/?probe=4703a17f03) | May 23, 2023 |
| MSI           | Modern 14 B10MW             | [319f4883aa](https://linux-hardware.org/?probe=319f4883aa) | May 22, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [ceeff309eb](https://linux-hardware.org/?probe=ceeff309eb) | May 18, 2023 |
| ASUSTek       | X541UAK                     | [00685614c4](https://linux-hardware.org/?probe=00685614c4) | May 16, 2023 |
| ASUSTek       | N76VZ                       | [fc6d34934a](https://linux-hardware.org/?probe=fc6d34934a) | May 14, 2023 |
| Razer         | Blade 15 Studio Edition ... | [f1884eebc6](https://linux-hardware.org/?probe=f1884eebc6) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [729a4181de](https://linux-hardware.org/?probe=729a4181de) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [3010c8760e](https://linux-hardware.org/?probe=3010c8760e) | May 12, 2023 |
| Acer          | Extensa 5220                | [935b52f12c](https://linux-hardware.org/?probe=935b52f12c) | May 12, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [af96be2497](https://linux-hardware.org/?probe=af96be2497) | May 11, 2023 |
| Acer          | Aspire A515-45              | [8f9a64c245](https://linux-hardware.org/?probe=8f9a64c245) | May 08, 2023 |
| Dell          | Inspiron 11-3162            | [62813124bb](https://linux-hardware.org/?probe=62813124bb) | May 08, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [a312f0545f](https://linux-hardware.org/?probe=a312f0545f) | May 07, 2023 |
| Acer          | Aspire 5742G                | [2a321db63e](https://linux-hardware.org/?probe=2a321db63e) | May 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [85648a82df](https://linux-hardware.org/?probe=85648a82df) | May 06, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [af9c3172bc](https://linux-hardware.org/?probe=af9c3172bc) | May 05, 2023 |
| MSI           | GP75 Leopard 9SE            | [425ecbf896](https://linux-hardware.org/?probe=425ecbf896) | May 04, 2023 |
| ASUSTek       | 1001PX                      | [7a04e30859](https://linux-hardware.org/?probe=7a04e30859) | May 03, 2023 |
| HP            | Notebook                    | [c6316b5a64](https://linux-hardware.org/?probe=c6316b5a64) | May 03, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | [7c56fae21c](https://linux-hardware.org/?probe=7c56fae21c) | May 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [3b04b16c3e](https://linux-hardware.org/?probe=3b04b16c3e) | May 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1234a4cf5a](https://linux-hardware.org/?probe=1234a4cf5a) | May 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [5101f4e19d](https://linux-hardware.org/?probe=5101f4e19d) | May 02, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | [2a4cf994ac](https://linux-hardware.org/?probe=2a4cf994ac) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [ed2a323b49](https://linux-hardware.org/?probe=ed2a323b49) | May 01, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [4607549f5a](https://linux-hardware.org/?probe=4607549f5a) | May 01, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [754b22a59c](https://linux-hardware.org/?probe=754b22a59c) | May 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d1b974c33a](https://linux-hardware.org/?probe=d1b974c33a) | May 01, 2023 |
| Acer          | Aspire 5110                 | [b43b059257](https://linux-hardware.org/?probe=b43b059257) | Apr 28, 2023 |
| Dell          | Vostro 15 3515              | [f58ab8b9c4](https://linux-hardware.org/?probe=f58ab8b9c4) | Apr 27, 2023 |
| Acer          | Aspire A515-57              | [86dad710fa](https://linux-hardware.org/?probe=86dad710fa) | Apr 26, 2023 |
| Acer          | Aspire A315-35              | [33fac6ec40](https://linux-hardware.org/?probe=33fac6ec40) | Apr 26, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [e7fb8c3e44](https://linux-hardware.org/?probe=e7fb8c3e44) | Apr 26, 2023 |
| ASUSTek       | K53SM                       | [92ac292547](https://linux-hardware.org/?probe=92ac292547) | Apr 24, 2023 |
| Acer          | Aspire V5-122P              | [baf567c71f](https://linux-hardware.org/?probe=baf567c71f) | Apr 23, 2023 |
| HP            | ProBook 450 G3              | [6e52b3ea77](https://linux-hardware.org/?probe=6e52b3ea77) | Apr 22, 2023 |
| Allview       | Allbook J                   | [96a3d7d3ef](https://linux-hardware.org/?probe=96a3d7d3ef) | Apr 22, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | [3f01c5df6e](https://linux-hardware.org/?probe=3f01c5df6e) | Apr 21, 2023 |
| Lenovo        | ThinkPad T530 24297ZG       | [a5ef39681b](https://linux-hardware.org/?probe=a5ef39681b) | Apr 21, 2023 |
| Allview       | Allbook J                   | [4ff8627338](https://linux-hardware.org/?probe=4ff8627338) | Apr 18, 2023 |
| Acer          | Aspire E5-575G              | [39afaea9e3](https://linux-hardware.org/?probe=39afaea9e3) | Apr 14, 2023 |
| Lenovo        | ThinkPad T420 4236WR1       | [0c4578a674](https://linux-hardware.org/?probe=0c4578a674) | Apr 14, 2023 |
| Dell          | Inspiron 1545               | [653a25793d](https://linux-hardware.org/?probe=653a25793d) | Apr 12, 2023 |
| Dell          | Inspiron 1545               | [dccecbecf9](https://linux-hardware.org/?probe=dccecbecf9) | Apr 12, 2023 |
| HP            | EliteBook 840 G5            | [da4c241466](https://linux-hardware.org/?probe=da4c241466) | Apr 10, 2023 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [5244868737](https://linux-hardware.org/?probe=5244868737) | Apr 09, 2023 |
| Lenovo        | ThinkPad T480 20L6S4G72S    | [ae8c333d72](https://linux-hardware.org/?probe=ae8c333d72) | Apr 07, 2023 |
| ASUSTek       | X55U                        | [0abf7df439](https://linux-hardware.org/?probe=0abf7df439) | Apr 06, 2023 |
| ASUSTek       | X550CL                      | [5d5862d22a](https://linux-hardware.org/?probe=5d5862d22a) | Mar 31, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [5be11a9a6e](https://linux-hardware.org/?probe=5be11a9a6e) | Mar 29, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | [bfa850ddad](https://linux-hardware.org/?probe=bfa850ddad) | Mar 29, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [577947c9d3](https://linux-hardware.org/?probe=577947c9d3) | Mar 28, 2023 |
| Toshiba       | Satellite C55-A-1J8         | [c6ba40cd5c](https://linux-hardware.org/?probe=c6ba40cd5c) | Mar 27, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [08e7388619](https://linux-hardware.org/?probe=08e7388619) | Mar 27, 2023 |
| ASUSTek       | X751SA                      | [bef27b5a10](https://linux-hardware.org/?probe=bef27b5a10) | Mar 26, 2023 |
| ASUSTek       | X751SA                      | [daac2899b2](https://linux-hardware.org/?probe=daac2899b2) | Mar 26, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [84af25ca8c](https://linux-hardware.org/?probe=84af25ca8c) | Mar 26, 2023 |
| Acer          | Aspire 7750G                | [f99591fe95](https://linux-hardware.org/?probe=f99591fe95) | Mar 26, 2023 |
| Acer          | V5-131                      | [f35bd55401](https://linux-hardware.org/?probe=f35bd55401) | Mar 26, 2023 |
| Acer          | TravelMate 5744             | [3ad8bf7639](https://linux-hardware.org/?probe=3ad8bf7639) | Mar 22, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [c5b2997e80](https://linux-hardware.org/?probe=c5b2997e80) | Mar 21, 2023 |
| HP            | 250 G5 Notebook PC          | [4a4c44f0dd](https://linux-hardware.org/?probe=4a4c44f0dd) | Mar 18, 2023 |
| HP            | ZBook 15                    | [ebc4b1e01e](https://linux-hardware.org/?probe=ebc4b1e01e) | Mar 14, 2023 |
| Valve         | Jupiter                     | [d56d3939f9](https://linux-hardware.org/?probe=d56d3939f9) | Mar 14, 2023 |
| MSI           | GF63 Thin 11UC              | [7c96c962f0](https://linux-hardware.org/?probe=7c96c962f0) | Mar 13, 2023 |
| SLIMBOOK      | PROX-AMD5                   | [4492e72dd8](https://linux-hardware.org/?probe=4492e72dd8) | Mar 10, 2023 |
| HP            | Compaq nx9420 (ES446EA#A... | [b876c92a6e](https://linux-hardware.org/?probe=b876c92a6e) | Mar 09, 2023 |
| HP            | Compaq 6735b                | [8c664182a2](https://linux-hardware.org/?probe=8c664182a2) | Mar 05, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4fc82abdeb](https://linux-hardware.org/?probe=4fc82abdeb) | Mar 04, 2023 |
| Dell          | Inspiron 3593               | [4e2f59d17e](https://linux-hardware.org/?probe=4e2f59d17e) | Mar 04, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4c25c88937](https://linux-hardware.org/?probe=4c25c88937) | Mar 03, 2023 |
| Chuwi         | GemiBook Pro                | [1b68738664](https://linux-hardware.org/?probe=1b68738664) | Mar 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [2dea6717ae](https://linux-hardware.org/?probe=2dea6717ae) | Mar 02, 2023 |
| ASUSTek       | FX503VD                     | [46954919f7](https://linux-hardware.org/?probe=46954919f7) | Feb 27, 2023 |
| ASUSTek       | FX503VD                     | [60e1742e7e](https://linux-hardware.org/?probe=60e1742e7e) | Feb 27, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | [bd2c3ecd74](https://linux-hardware.org/?probe=bd2c3ecd74) | Feb 25, 2023 |
| ASUSTek       | X541UV                      | [6765309d07](https://linux-hardware.org/?probe=6765309d07) | Feb 25, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [562517eab4](https://linux-hardware.org/?probe=562517eab4) | Feb 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [22cf774ac0](https://linux-hardware.org/?probe=22cf774ac0) | Feb 25, 2023 |
| Timi          | Xiaomi Book Pro 14 2022     | [46aedb5579](https://linux-hardware.org/?probe=46aedb5579) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | [277834a459](https://linux-hardware.org/?probe=277834a459) | Feb 24, 2023 |
| Lenovo        | ThinkPad X230 2325CS6       | [ed9501bbcb](https://linux-hardware.org/?probe=ed9501bbcb) | Feb 23, 2023 |
| ASUSTek       | X553SA                      | [bf6718f1d0](https://linux-hardware.org/?probe=bf6718f1d0) | Feb 22, 2023 |
| Dell          | Latitude 5580               | [91567566be](https://linux-hardware.org/?probe=91567566be) | Feb 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [c205da78c9](https://linux-hardware.org/?probe=c205da78c9) | Feb 19, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | [8942075e7b](https://linux-hardware.org/?probe=8942075e7b) | Feb 18, 2023 |
| ASUSTek       | X553SA                      | [dc294f018e](https://linux-hardware.org/?probe=dc294f018e) | Feb 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [e614d24613](https://linux-hardware.org/?probe=e614d24613) | Feb 17, 2023 |
| Toshiba       | Satellite L650              | [553bddf256](https://linux-hardware.org/?probe=553bddf256) | Feb 15, 2023 |
| HP            | EliteBook 850 G2            | [ed0641ce38](https://linux-hardware.org/?probe=ed0641ce38) | Feb 15, 2023 |
| Dell          | Inspiron 16 5625            | [d4951f7e68](https://linux-hardware.org/?probe=d4951f7e68) | Feb 11, 2023 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | [6047c68386](https://linux-hardware.org/?probe=6047c68386) | Feb 11, 2023 |
| ASUSTek       | G73Sw                       | [199c8805ee](https://linux-hardware.org/?probe=199c8805ee) | Feb 10, 2023 |
| ASUSTek       | GL753VD                     | [e7b8536ad4](https://linux-hardware.org/?probe=e7b8536ad4) | Feb 09, 2023 |
| Dell          | Inspiron 15 3525            | [2f47f8d73d](https://linux-hardware.org/?probe=2f47f8d73d) | Feb 05, 2023 |
| Toshiba       | Satellite C55-A-168         | [e92c2babc4](https://linux-hardware.org/?probe=e92c2babc4) | Feb 05, 2023 |
| Dell          | Vostro 15 3515              | [c4c5c0888a](https://linux-hardware.org/?probe=c4c5c0888a) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [0b1fbca173](https://linux-hardware.org/?probe=0b1fbca173) | Feb 03, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ab31f6153e](https://linux-hardware.org/?probe=ab31f6153e) | Feb 01, 2023 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [6ed194a014](https://linux-hardware.org/?probe=6ed194a014) | Feb 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [e2ad5b033f](https://linux-hardware.org/?probe=e2ad5b033f) | Jan 31, 2023 |
| ASUSTek       | X556UQK                     | [6c3dd54582](https://linux-hardware.org/?probe=6c3dd54582) | Jan 30, 2023 |
| ASUSTek       | G73Sw                       | [b8891cfc9b](https://linux-hardware.org/?probe=b8891cfc9b) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | [fb0a23c0e6](https://linux-hardware.org/?probe=fb0a23c0e6) | Jan 27, 2023 |
| ASUSTek       | G73Sw                       | [24b6a47ebb](https://linux-hardware.org/?probe=24b6a47ebb) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [5d58c53672](https://linux-hardware.org/?probe=5d58c53672) | Jan 27, 2023 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [b352f0af44](https://linux-hardware.org/?probe=b352f0af44) | Jan 27, 2023 |
| ASUSTek       | X541UVK                     | [64810b20c3](https://linux-hardware.org/?probe=64810b20c3) | Jan 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [e030231e2c](https://linux-hardware.org/?probe=e030231e2c) | Jan 25, 2023 |
| Lenovo        | B50-80 80EW                 | [5f584c387e](https://linux-hardware.org/?probe=5f584c387e) | Jan 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [ec369b35a4](https://linux-hardware.org/?probe=ec369b35a4) | Jan 24, 2023 |
| Lenovo        | B50-80 80EW                 | [61932dd31a](https://linux-hardware.org/?probe=61932dd31a) | Jan 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [62ac206f7e](https://linux-hardware.org/?probe=62ac206f7e) | Jan 23, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [8cb10f3212](https://linux-hardware.org/?probe=8cb10f3212) | Jan 23, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [36d99ec94e](https://linux-hardware.org/?probe=36d99ec94e) | Jan 22, 2023 |
| ASUSTek       | G73Sw                       | [adbc469f95](https://linux-hardware.org/?probe=adbc469f95) | Jan 22, 2023 |
| ASUSTek       | G73Sw                       | [9249ff32b3](https://linux-hardware.org/?probe=9249ff32b3) | Jan 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [523d0331a1](https://linux-hardware.org/?probe=523d0331a1) | Jan 21, 2023 |
| HP            | EliteBook 850 G2            | [a7ba34fed5](https://linux-hardware.org/?probe=a7ba34fed5) | Jan 21, 2023 |
| Lenovo        | ThinkPad T560 20FJS1J200    | [de713cedce](https://linux-hardware.org/?probe=de713cedce) | Jan 21, 2023 |
| Acer          | V5WE2                       | [021281441e](https://linux-hardware.org/?probe=021281441e) | Jan 20, 2023 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [be320f363d](https://linux-hardware.org/?probe=be320f363d) | Jan 19, 2023 |
| Dell          | Precision M6600             | [478f51f2be](https://linux-hardware.org/?probe=478f51f2be) | Jan 17, 2023 |
| Dell          | Precision M6600             | [7511681884](https://linux-hardware.org/?probe=7511681884) | Jan 16, 2023 |
| Dell          | Inspiron 15-3567            | [020e19b05d](https://linux-hardware.org/?probe=020e19b05d) | Jan 16, 2023 |
| Dell          | Inspiron 15-3567            | [5426686264](https://linux-hardware.org/?probe=5426686264) | Jan 15, 2023 |
| Valve         | Jupiter                     | [020abf67f6](https://linux-hardware.org/?probe=020abf67f6) | Jan 14, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [f32463429a](https://linux-hardware.org/?probe=f32463429a) | Jan 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [6f39a15710](https://linux-hardware.org/?probe=6f39a15710) | Jan 13, 2023 |
| ASUSTek       | X406UAR                     | [68da6f6220](https://linux-hardware.org/?probe=68da6f6220) | Jan 13, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [0eb36758be](https://linux-hardware.org/?probe=0eb36758be) | Jan 13, 2023 |
| ASUSTek       | X406UAR                     | [729e2e0d41](https://linux-hardware.org/?probe=729e2e0d41) | Jan 12, 2023 |
| Lenovo        | B50-80 80EW                 | [7bf9c1c7f4](https://linux-hardware.org/?probe=7bf9c1c7f4) | Jan 10, 2023 |
| Acer          | TMP645-M                    | [8e0b2f5e90](https://linux-hardware.org/?probe=8e0b2f5e90) | Jan 10, 2023 |
| VALE          | Notebook Classic C140       | [afe262fc54](https://linux-hardware.org/?probe=afe262fc54) | Jan 09, 2023 |
| ASUSTek       | K50IE                       | [4fdb15502c](https://linux-hardware.org/?probe=4fdb15502c) | Jan 09, 2023 |
| Lenovo        | ThinkPad A275 20KCS0FT02    | [fc35d7e62b](https://linux-hardware.org/?probe=fc35d7e62b) | Jan 09, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [69cda32447](https://linux-hardware.org/?probe=69cda32447) | Jan 08, 2023 |
| Acer          | Aspire A315-21G             | [cc98c43ea0](https://linux-hardware.org/?probe=cc98c43ea0) | Jan 07, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [9320df061f](https://linux-hardware.org/?probe=9320df061f) | Jan 06, 2023 |
| Neousys Te... | POC-200 Series              | [7c37ff8631](https://linux-hardware.org/?probe=7c37ff8631) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | [0042419ccb](https://linux-hardware.org/?probe=0042419ccb) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | [82e42c0d42](https://linux-hardware.org/?probe=82e42c0d42) | Jan 04, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [bb1b612416](https://linux-hardware.org/?probe=bb1b612416) | Dec 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8702939897](https://linux-hardware.org/?probe=8702939897) | Dec 29, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [8db34630c3](https://linux-hardware.org/?probe=8db34630c3) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1ff4c4bf09](https://linux-hardware.org/?probe=1ff4c4bf09) | Dec 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ad33bb0d6f](https://linux-hardware.org/?probe=ad33bb0d6f) | Dec 28, 2022 |
| Dell          | Latitude 7480               | [45b0f992f6](https://linux-hardware.org/?probe=45b0f992f6) | Dec 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [62869e3d8c](https://linux-hardware.org/?probe=62869e3d8c) | Dec 26, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [5aa14f474e](https://linux-hardware.org/?probe=5aa14f474e) | Dec 25, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [098390e03e](https://linux-hardware.org/?probe=098390e03e) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [9ea4a13b0f](https://linux-hardware.org/?probe=9ea4a13b0f) | Dec 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fa7183c982](https://linux-hardware.org/?probe=fa7183c982) | Dec 25, 2022 |
| Acer          | Aspire VX5-591G             | [7defe87998](https://linux-hardware.org/?probe=7defe87998) | Dec 23, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [fe159bf4ca](https://linux-hardware.org/?probe=fe159bf4ca) | Dec 23, 2022 |
| Samsung       | RV420/RV520/RV720/E3530/... | [81f7e4d804](https://linux-hardware.org/?probe=81f7e4d804) | Dec 22, 2022 |
| Acer          | Nitro AN515-58              | [041cd6f9bd](https://linux-hardware.org/?probe=041cd6f9bd) | Dec 22, 2022 |
| Lenovo        | ThinkPad X201 3680AA4       | [6306be2273](https://linux-hardware.org/?probe=6306be2273) | Dec 22, 2022 |
| Lenovo        | ThinkPad X201 3680AA4       | [cf8576151f](https://linux-hardware.org/?probe=cf8576151f) | Dec 22, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [721bc5f662](https://linux-hardware.org/?probe=721bc5f662) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d9db7be046](https://linux-hardware.org/?probe=d9db7be046) | Dec 21, 2022 |
| ASUSTek       | N53SM                       | [9c9b1d3f5b](https://linux-hardware.org/?probe=9c9b1d3f5b) | Dec 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [89b8982148](https://linux-hardware.org/?probe=89b8982148) | Dec 20, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [082a1fb19e](https://linux-hardware.org/?probe=082a1fb19e) | Dec 20, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [20544e55bb](https://linux-hardware.org/?probe=20544e55bb) | Dec 14, 2022 |
| TUXEDO        | Polaris Intel Gen3 (TGL)    | [7da34e4f7f](https://linux-hardware.org/?probe=7da34e4f7f) | Dec 14, 2022 |
| ASUSTek       | G75VW                       | [8d2a0ec4e4](https://linux-hardware.org/?probe=8d2a0ec4e4) | Dec 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [a1f1288337](https://linux-hardware.org/?probe=a1f1288337) | Dec 13, 2022 |
| ASUSTek       | GL752VW                     | [05c7382806](https://linux-hardware.org/?probe=05c7382806) | Dec 11, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [a7a3ccf712](https://linux-hardware.org/?probe=a7a3ccf712) | Dec 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1a7d599cd5](https://linux-hardware.org/?probe=1a7d599cd5) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [83b02f1ffb](https://linux-hardware.org/?probe=83b02f1ffb) | Dec 10, 2022 |
| Dell          | Latitude E6520              | [ec32b72261](https://linux-hardware.org/?probe=ec32b72261) | Dec 09, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [ea7638c0f9](https://linux-hardware.org/?probe=ea7638c0f9) | Dec 07, 2022 |
| Acer          | Aspire A515-51G             | [10f8aab734](https://linux-hardware.org/?probe=10f8aab734) | Dec 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [a35bac4078](https://linux-hardware.org/?probe=a35bac4078) | Dec 06, 2022 |
| ASUSTek       | X556UQK                     | [2f693620e1](https://linux-hardware.org/?probe=2f693620e1) | Dec 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [b387887bb6](https://linux-hardware.org/?probe=b387887bb6) | Dec 03, 2022 |
| Acer          | Nitro AN515-44              | [56a2d42adc](https://linux-hardware.org/?probe=56a2d42adc) | Dec 02, 2022 |
| HUAWEI        | BOHB-WAX9                   | [3d64de28f5](https://linux-hardware.org/?probe=3d64de28f5) | Dec 01, 2022 |
| Lenovo        | ThinkPad T530 24297ZG       | [422f84a794](https://linux-hardware.org/?probe=422f84a794) | Nov 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S1FR0... | [517347d2cf](https://linux-hardware.org/?probe=517347d2cf) | Nov 30, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [8e6e8471a7](https://linux-hardware.org/?probe=8e6e8471a7) | Nov 29, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [972f6f4355](https://linux-hardware.org/?probe=972f6f4355) | Nov 28, 2022 |
| HUAWEI        | BOD-WXX9                    | [5b2f9bfd5c](https://linux-hardware.org/?probe=5b2f9bfd5c) | Nov 28, 2022 |
| HP            | EliteBook 8460p             | [a39632439e](https://linux-hardware.org/?probe=a39632439e) | Nov 27, 2022 |
| Acer          | Nitro AN515-58              | [4916981641](https://linux-hardware.org/?probe=4916981641) | Nov 26, 2022 |
| HP            | ProBook 450 G7              | [52d46ed47e](https://linux-hardware.org/?probe=52d46ed47e) | Nov 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [0565ef1a0d](https://linux-hardware.org/?probe=0565ef1a0d) | Nov 22, 2022 |
| Dell          | Latitude E6410              | [22585074f3](https://linux-hardware.org/?probe=22585074f3) | Nov 21, 2022 |
| ASUSTek       | X541UAK                     | [75af06e026](https://linux-hardware.org/?probe=75af06e026) | Nov 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [c5ec7b9dcc](https://linux-hardware.org/?probe=c5ec7b9dcc) | Nov 20, 2022 |
| Lenovo        | V15 G1 IML 82NB             | [a120cac88b](https://linux-hardware.org/?probe=a120cac88b) | Nov 18, 2022 |
| Allview       | Allbook H                   | [4de72c8cba](https://linux-hardware.org/?probe=4de72c8cba) | Nov 17, 2022 |
| ASUSTek       | X550VX                      | [a1e3d4527c](https://linux-hardware.org/?probe=a1e3d4527c) | Nov 15, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [fef97563a0](https://linux-hardware.org/?probe=fef97563a0) | Nov 13, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [61bcea3891](https://linux-hardware.org/?probe=61bcea3891) | Nov 13, 2022 |
| Alienware     | Area-51m                    | [11c59a838f](https://linux-hardware.org/?probe=11c59a838f) | Nov 12, 2022 |
| Dell          | Latitude E7270              | [629a581a22](https://linux-hardware.org/?probe=629a581a22) | Nov 12, 2022 |
| Dell          | Latitude E7470              | [e80d2221f5](https://linux-hardware.org/?probe=e80d2221f5) | Nov 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QH... | [0144bb5a89](https://linux-hardware.org/?probe=0144bb5a89) | Nov 08, 2022 |
| Toshiba       | Satellite C50-A-1HF         | [8384350121](https://linux-hardware.org/?probe=8384350121) | Nov 08, 2022 |
| Acer          | Aspire A314-35              | [14751e1ae3](https://linux-hardware.org/?probe=14751e1ae3) | Nov 08, 2022 |
| Lenovo        | B590 20206                  | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| Valve         | Jupiter                     | [5800bb0b18](https://linux-hardware.org/?probe=5800bb0b18) | Nov 06, 2022 |
| HP            | Laptop 15-da0xxx            | [f8d2bbf15a](https://linux-hardware.org/?probe=f8d2bbf15a) | Nov 06, 2022 |
| Valve         | Jupiter                     | [55293ff823](https://linux-hardware.org/?probe=55293ff823) | Nov 05, 2022 |
| Dell          | XPS 15 9530                 | [5ffd5ed23d](https://linux-hardware.org/?probe=5ffd5ed23d) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [7dc3ed5f76](https://linux-hardware.org/?probe=7dc3ed5f76) | Nov 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [f5060f0a8d](https://linux-hardware.org/?probe=f5060f0a8d) | Nov 01, 2022 |
| HP            | Pavilion Laptop 14-ec1xx... | [1563c60737](https://linux-hardware.org/?probe=1563c60737) | Oct 31, 2022 |
| Lenovo        | IdeaPad 720S-13IKB 81A8     | [85efda7536](https://linux-hardware.org/?probe=85efda7536) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Dell          | XPS 15 9530                 | [fc7ef1ce9a](https://linux-hardware.org/?probe=fc7ef1ce9a) | Oct 29, 2022 |
| HP            | Pavilion Laptop 15-eh2xx... | [f9238c2035](https://linux-hardware.org/?probe=f9238c2035) | Oct 28, 2022 |
| Samsung       | 550P5C/550P7C               | [7dca4296ee](https://linux-hardware.org/?probe=7dca4296ee) | Oct 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [7274eca48b](https://linux-hardware.org/?probe=7274eca48b) | Oct 23, 2022 |
| Timi          | Xiaomi Book Pro 14 2022     | [18e52559a4](https://linux-hardware.org/?probe=18e52559a4) | Oct 17, 2022 |
| MSI           | GV72 7RE                    | [84941aaa84](https://linux-hardware.org/?probe=84941aaa84) | Oct 14, 2022 |
| ASUSTek       | N53Jf                       | [a6a5cdbf04](https://linux-hardware.org/?probe=a6a5cdbf04) | Oct 13, 2022 |
| Acer          | Aspire E5-573G              | [bccf0a4ebe](https://linux-hardware.org/?probe=bccf0a4ebe) | Oct 13, 2022 |
| Dell          | XPS 15 9530                 | [ad2b1ab7b8](https://linux-hardware.org/?probe=ad2b1ab7b8) | Oct 12, 2022 |
| Medion        | Akoya E6239                 | [46ce690b32](https://linux-hardware.org/?probe=46ce690b32) | Oct 10, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [ef1974cfc8](https://linux-hardware.org/?probe=ef1974cfc8) | Oct 10, 2022 |
| Dell          | Latitude E6410              | [4f6730e0f2](https://linux-hardware.org/?probe=4f6730e0f2) | Oct 09, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| Valve         | Jupiter                     | [889099ff63](https://linux-hardware.org/?probe=889099ff63) | Oct 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d9474bd3b9](https://linux-hardware.org/?probe=d9474bd3b9) | Oct 03, 2022 |
| Dell          | XPS 15 9530                 | [abfab502a6](https://linux-hardware.org/?probe=abfab502a6) | Oct 02, 2022 |
| Medion        | Akoya P2214T                | [428205d2a5](https://linux-hardware.org/?probe=428205d2a5) | Oct 02, 2022 |
| HP            | Laptop 15-da0xxx            | [176695aa20](https://linux-hardware.org/?probe=176695aa20) | Sep 30, 2022 |
| HP            | 250 G5 Notebook PC          | [26961d1b30](https://linux-hardware.org/?probe=26961d1b30) | Sep 29, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | [3e92ba3812](https://linux-hardware.org/?probe=3e92ba3812) | Sep 29, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [96c4c8ba02](https://linux-hardware.org/?probe=96c4c8ba02) | Sep 28, 2022 |
| Dell          | System Inspiron N7110       | [016d5e3146](https://linux-hardware.org/?probe=016d5e3146) | Sep 27, 2022 |
| Lenovo        | ThinkPad T420 4236C53       | [e0983b35fa](https://linux-hardware.org/?probe=e0983b35fa) | Sep 25, 2022 |
| Acer          | Aspire 5750Z                | [38e1cc9153](https://linux-hardware.org/?probe=38e1cc9153) | Sep 22, 2022 |
| Fusion5       | S14                         | [9b3e06c4e4](https://linux-hardware.org/?probe=9b3e06c4e4) | Sep 22, 2022 |
| Acer          | Aspire 5750Z                | [b673d5cfe9](https://linux-hardware.org/?probe=b673d5cfe9) | Sep 22, 2022 |
| Dell          | Precision 3561              | [b924a86b79](https://linux-hardware.org/?probe=b924a86b79) | Sep 21, 2022 |
| Acer          | Aspire A515-45              | [6fb7c9c27a](https://linux-hardware.org/?probe=6fb7c9c27a) | Sep 21, 2022 |
| HP            | ProBook 640 G4              | [41cb2444c5](https://linux-hardware.org/?probe=41cb2444c5) | Sep 20, 2022 |
| HP            | ProBook 640 G4              | [a93242008f](https://linux-hardware.org/?probe=a93242008f) | Sep 20, 2022 |
| Acer          | Aspire A515-45              | [5b0c60618f](https://linux-hardware.org/?probe=5b0c60618f) | Sep 20, 2022 |
| Acer          | Aspire 5349                 | [39f83f7692](https://linux-hardware.org/?probe=39f83f7692) | Sep 13, 2022 |
| Dell          | XPS 15 9530                 | [fbb3c09289](https://linux-hardware.org/?probe=fbb3c09289) | Sep 12, 2022 |
| Dell          | XPS 15 9530                 | [fccf3eb345](https://linux-hardware.org/?probe=fccf3eb345) | Sep 12, 2022 |
| Samsung       | R530/R730/R540              | [72aea277e6](https://linux-hardware.org/?probe=72aea277e6) | Sep 10, 2022 |
| HP            | Pavilion g6                 | [0774a3c97d](https://linux-hardware.org/?probe=0774a3c97d) | Sep 10, 2022 |
| Lenovo        | Legion Y7000P-1060 81LF     | [b018911117](https://linux-hardware.org/?probe=b018911117) | Sep 09, 2022 |
| HP            | EliteBook 8440p             | [3474424d64](https://linux-hardware.org/?probe=3474424d64) | Sep 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | [e47c8e6967](https://linux-hardware.org/?probe=e47c8e6967) | Sep 04, 2022 |
| HUAWEI        | KLVL-WXXW                   | [3f805d59b5](https://linux-hardware.org/?probe=3f805d59b5) | Sep 04, 2022 |
| Acer          | Extensa 5635ZG              | [f79a7aaa6f](https://linux-hardware.org/?probe=f79a7aaa6f) | Sep 03, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [b91c67af87](https://linux-hardware.org/?probe=b91c67af87) | Sep 02, 2022 |
| Dell          | Latitude 5521               | [dcf7869cf6](https://linux-hardware.org/?probe=dcf7869cf6) | Sep 01, 2022 |
| Valve         | Jupiter                     | [6e9790c5e7](https://linux-hardware.org/?probe=6e9790c5e7) | Sep 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [b4a9d1fecc](https://linux-hardware.org/?probe=b4a9d1fecc) | Aug 30, 2022 |
| Dell          | Latitude E7470              | [568c9bfd40](https://linux-hardware.org/?probe=568c9bfd40) | Aug 28, 2022 |
| Acer          | Aspire A315-23              | [4c16a58579](https://linux-hardware.org/?probe=4c16a58579) | Aug 28, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | [fbf3d4a87a](https://linux-hardware.org/?probe=fbf3d4a87a) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [02c6bde77b](https://linux-hardware.org/?probe=02c6bde77b) | Aug 27, 2022 |
| ASUSTek       | X550CC                      | [8b85141416](https://linux-hardware.org/?probe=8b85141416) | Aug 26, 2022 |
| Complet       | MY8312                      | [4db1527bde](https://linux-hardware.org/?probe=4db1527bde) | Aug 26, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [c8b4d18767](https://linux-hardware.org/?probe=c8b4d18767) | Aug 25, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | [09feb7053d](https://linux-hardware.org/?probe=09feb7053d) | Aug 25, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [69281b6cc3](https://linux-hardware.org/?probe=69281b6cc3) | Aug 24, 2022 |
| Dell          | Latitude 7410               | [ae90ce90ed](https://linux-hardware.org/?probe=ae90ce90ed) | Aug 22, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [9c31fff4b2](https://linux-hardware.org/?probe=9c31fff4b2) | Aug 20, 2022 |
| Dell          | Latitude 7420               | [d599ef65fd](https://linux-hardware.org/?probe=d599ef65fd) | Aug 20, 2022 |
| Lenovo        | ThinkPad L440 20ASS3A300    | [1a0800fc4a](https://linux-hardware.org/?probe=1a0800fc4a) | Aug 19, 2022 |
| Dell          | Inspiron 5558               | [b4bc42c01c](https://linux-hardware.org/?probe=b4bc42c01c) | Aug 18, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [97fb16fc3f](https://linux-hardware.org/?probe=97fb16fc3f) | Aug 17, 2022 |
| Dell          | XPS 15 9530                 | [71f62cef7a](https://linux-hardware.org/?probe=71f62cef7a) | Aug 16, 2022 |
| Dell          | Inspiron 1501               | [11b4c83b79](https://linux-hardware.org/?probe=11b4c83b79) | Aug 15, 2022 |
| Acer          | Aspire V3-571G              | [f45a97ca40](https://linux-hardware.org/?probe=f45a97ca40) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [9e77f6044a](https://linux-hardware.org/?probe=9e77f6044a) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [eb79423b1d](https://linux-hardware.org/?probe=eb79423b1d) | Aug 12, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cc51e49c51](https://linux-hardware.org/?probe=cc51e49c51) | Aug 10, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | [6826a8d40d](https://linux-hardware.org/?probe=6826a8d40d) | Aug 08, 2022 |
| ASUSTek       | X550CL                      | [83626d765b](https://linux-hardware.org/?probe=83626d765b) | Aug 08, 2022 |
| Dell          | Latitude E6540              | [d47b2c5c2b](https://linux-hardware.org/?probe=d47b2c5c2b) | Aug 06, 2022 |
| Acer          | Aspire A515-45              | [ddd717c7e6](https://linux-hardware.org/?probe=ddd717c7e6) | Aug 05, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [3025bd4ded](https://linux-hardware.org/?probe=3025bd4ded) | Aug 05, 2022 |
| ASUSTek       | ROG Strix G713RS_G713RS     | [707ab083b3](https://linux-hardware.org/?probe=707ab083b3) | Aug 04, 2022 |
| HP            | Pavilion 15                 | [e6bfde2a29](https://linux-hardware.org/?probe=e6bfde2a29) | Jul 29, 2022 |
| Dell          | System Inspiron N7110       | [d2cbf8528a](https://linux-hardware.org/?probe=d2cbf8528a) | Jul 28, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8b3fd99e18](https://linux-hardware.org/?probe=8b3fd99e18) | Jul 27, 2022 |
| HP            | EliteBook 8460p             | [7b2de05256](https://linux-hardware.org/?probe=7b2de05256) | Jul 27, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4ee4fc0689](https://linux-hardware.org/?probe=4ee4fc0689) | Jul 26, 2022 |
| Lenovo        | ThinkPad P52 20MAS1R100     | [7a01b8819c](https://linux-hardware.org/?probe=7a01b8819c) | Jul 21, 2022 |
| HP            | ZBook Power G7 Mobile Wo... | [9a5f11c4b9](https://linux-hardware.org/?probe=9a5f11c4b9) | Jul 19, 2022 |
| HP            | EliteBook 850 G1            | [383ec7a7fd](https://linux-hardware.org/?probe=383ec7a7fd) | Jul 18, 2022 |
| Acer          | Aspire SW3-016              | [c48cdf5576](https://linux-hardware.org/?probe=c48cdf5576) | Jul 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [55efce6cdc](https://linux-hardware.org/?probe=55efce6cdc) | Jul 13, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [be909dd3b4](https://linux-hardware.org/?probe=be909dd3b4) | Jul 12, 2022 |
| HP            | 355 G2                      | [55239c5062](https://linux-hardware.org/?probe=55239c5062) | Jul 11, 2022 |
| HP            | 355 G2                      | [9b5e64b838](https://linux-hardware.org/?probe=9b5e64b838) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [e7b17323df](https://linux-hardware.org/?probe=e7b17323df) | Jul 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [8f36480ad7](https://linux-hardware.org/?probe=8f36480ad7) | Jul 10, 2022 |
| HP            | 250 G4                      | [33dcd9203d](https://linux-hardware.org/?probe=33dcd9203d) | Jul 09, 2022 |
| Acer          | Nitro AN515-45              | [a9dd7c4072](https://linux-hardware.org/?probe=a9dd7c4072) | Jul 08, 2022 |
| ASUSTek       | ZenBook UX434FLC_UX434FL    | [99172a6e6f](https://linux-hardware.org/?probe=99172a6e6f) | Jul 08, 2022 |
| Dell          | Latitude 5420               | [cb302e010e](https://linux-hardware.org/?probe=cb302e010e) | Jul 08, 2022 |
| HP            | ProBook 4310s               | [86ae79b260](https://linux-hardware.org/?probe=86ae79b260) | Jul 07, 2022 |
| Acer          | Aspire A515-51G             | [3ab547df65](https://linux-hardware.org/?probe=3ab547df65) | Jul 04, 2022 |
| Acer          | Aspire A515-51G             | [98ef915ec8](https://linux-hardware.org/?probe=98ef915ec8) | Jul 03, 2022 |
| Dell          | Latitude 5521               | [2fda374f06](https://linux-hardware.org/?probe=2fda374f06) | Jun 24, 2022 |
| Dell          | Inspiron 5567               | [2791443b0d](https://linux-hardware.org/?probe=2791443b0d) | Jun 22, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [fc053b8a95](https://linux-hardware.org/?probe=fc053b8a95) | Jun 20, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [70d6947d54](https://linux-hardware.org/?probe=70d6947d54) | Jun 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | [1e88796016](https://linux-hardware.org/?probe=1e88796016) | Jun 15, 2022 |
| Acer          | Aspire One 522              | [7f4af0143d](https://linux-hardware.org/?probe=7f4af0143d) | Jun 11, 2022 |
| ASUSTek       | K50IJ                       | [c8bac63870](https://linux-hardware.org/?probe=c8bac63870) | Jun 10, 2022 |
| ASUSTek       | K50IJ                       | [addb86fcb0](https://linux-hardware.org/?probe=addb86fcb0) | Jun 10, 2022 |
| Dell          | Latitude E6440              | [63238f8fe9](https://linux-hardware.org/?probe=63238f8fe9) | Jun 09, 2022 |
| HUAWEI        | KLVL-WXX9                   | [992f232db5](https://linux-hardware.org/?probe=992f232db5) | Jun 08, 2022 |
| Dell          | Latitude D520               | [285ab7b873](https://linux-hardware.org/?probe=285ab7b873) | Jun 01, 2022 |
| Prestigio     | PSB141C04CGP                | [4fa2ee47c0](https://linux-hardware.org/?probe=4fa2ee47c0) | Jun 01, 2022 |
| Acer          | Aspire A315-51              | [083e3a354a](https://linux-hardware.org/?probe=083e3a354a) | May 29, 2022 |
| ASUSTek       | N53SM                       | [83209051cb](https://linux-hardware.org/?probe=83209051cb) | May 29, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [caaf2a56b6](https://linux-hardware.org/?probe=caaf2a56b6) | May 26, 2022 |
| Lenovo        | Legion Y740-15IRHg 81UH     | [74c64ebe72](https://linux-hardware.org/?probe=74c64ebe72) | May 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RS... | [940a448ea6](https://linux-hardware.org/?probe=940a448ea6) | May 24, 2022 |
| ASUSTek       | N53SM                       | [3115570400](https://linux-hardware.org/?probe=3115570400) | May 24, 2022 |
| Allview       | Allbook H                   | [9ea4897c6b](https://linux-hardware.org/?probe=9ea4897c6b) | May 24, 2022 |
| Dell          | Latitude E7470              | [b01633e1ae](https://linux-hardware.org/?probe=b01633e1ae) | May 24, 2022 |
| Dell          | Latitude E7470              | [815dbb114b](https://linux-hardware.org/?probe=815dbb114b) | May 23, 2022 |
| Dell          | Latitude E7470              | [9a6c29a243](https://linux-hardware.org/?probe=9a6c29a243) | May 21, 2022 |
| Acer          | Aspire One 522              | [0ac567a5cf](https://linux-hardware.org/?probe=0ac567a5cf) | May 21, 2022 |
| Dell          | Latitude E6410              | [739ffac681](https://linux-hardware.org/?probe=739ffac681) | May 21, 2022 |
| Dell          | Inspiron 3542               | [949f8f3e50](https://linux-hardware.org/?probe=949f8f3e50) | May 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [4d2d33c41c](https://linux-hardware.org/?probe=4d2d33c41c) | May 20, 2022 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | [59d945a9b3](https://linux-hardware.org/?probe=59d945a9b3) | May 19, 2022 |
| Lenovo        | ThinkPad P53 20QNS01900     | [158f212b30](https://linux-hardware.org/?probe=158f212b30) | May 13, 2022 |
| Dell          | Inspiron 3542               | [550824d592](https://linux-hardware.org/?probe=550824d592) | May 12, 2022 |
| Dell          | Inspiron 3542               | [324d1abe3b](https://linux-hardware.org/?probe=324d1abe3b) | May 08, 2022 |
| HP            | ProBook 4520s               | [06e044a425](https://linux-hardware.org/?probe=06e044a425) | May 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [52c2a321a4](https://linux-hardware.org/?probe=52c2a321a4) | May 07, 2022 |
| Acer          | Aspire E1-570               | [53ddeaa413](https://linux-hardware.org/?probe=53ddeaa413) | May 07, 2022 |
| HP            | Laptop 14s-dq1xxx           | [713358f855](https://linux-hardware.org/?probe=713358f855) | May 02, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [6537fb670a](https://linux-hardware.org/?probe=6537fb670a) | May 01, 2022 |
| Toshiba       | Satellite C55-A-1J8         | [26cd3478c5](https://linux-hardware.org/?probe=26cd3478c5) | Apr 30, 2022 |
| HP            | ProBook 4520s               | [60eab2c6c5](https://linux-hardware.org/?probe=60eab2c6c5) | Apr 30, 2022 |
| Pegatron      | Spring Peak                 | [66a1692171](https://linux-hardware.org/?probe=66a1692171) | Apr 30, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | [495a74c914](https://linux-hardware.org/?probe=495a74c914) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | [efcd6be006](https://linux-hardware.org/?probe=efcd6be006) | Apr 27, 2022 |
| Dell          | Latitude E4310              | [41db45879c](https://linux-hardware.org/?probe=41db45879c) | Apr 27, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | [afe44fa080](https://linux-hardware.org/?probe=afe44fa080) | Apr 27, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [8ece944a7b](https://linux-hardware.org/?probe=8ece944a7b) | Apr 27, 2022 |
| Dell          | Latitude E6520              | [1ca407a69f](https://linux-hardware.org/?probe=1ca407a69f) | Apr 27, 2022 |
| Acer          | Aspire E1-570               | [1621e22812](https://linux-hardware.org/?probe=1621e22812) | Apr 26, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bcc0c7612d](https://linux-hardware.org/?probe=bcc0c7612d) | Apr 26, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1EH0... | [fae5ee6551](https://linux-hardware.org/?probe=fae5ee6551) | Apr 26, 2022 |
| Dell          | XPS 17 9710                 | [c7dfc69b32](https://linux-hardware.org/?probe=c7dfc69b32) | Apr 26, 2022 |
| HP            | ProBook 4520s               | [1621eddc70](https://linux-hardware.org/?probe=1621eddc70) | Apr 25, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [1d1c33575f](https://linux-hardware.org/?probe=1d1c33575f) | Apr 24, 2022 |
| Lenovo        | ThinkPad T540p 20BES05A0... | [41276f12db](https://linux-hardware.org/?probe=41276f12db) | Apr 23, 2022 |
| Lenovo        | ThinkPad T540p 20BES05A0... | [55733b5ae3](https://linux-hardware.org/?probe=55733b5ae3) | Apr 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [a551ef1ec7](https://linux-hardware.org/?probe=a551ef1ec7) | Apr 23, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [fd6718859d](https://linux-hardware.org/?probe=fd6718859d) | Apr 23, 2022 |
| ASUSTek       | X450CP                      | [2518b6daad](https://linux-hardware.org/?probe=2518b6daad) | Apr 22, 2022 |
| ASUSTek       | X450CP                      | [17d51c502f](https://linux-hardware.org/?probe=17d51c502f) | Apr 22, 2022 |
| HP            | Laptop 15-ra0xx             | [bc175803f2](https://linux-hardware.org/?probe=bc175803f2) | Apr 22, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1Y90... | [de746c72d1](https://linux-hardware.org/?probe=de746c72d1) | Apr 20, 2022 |
| HP            | ENVY Laptop 14-eb0xxx       | [5d95841f54](https://linux-hardware.org/?probe=5d95841f54) | Apr 20, 2022 |
| Lenovo        | ThinkPad T560 20FJS0NT04    | [19ebdf705a](https://linux-hardware.org/?probe=19ebdf705a) | Apr 20, 2022 |
| ASUSTek       | X541UAK                     | [8b54af493a](https://linux-hardware.org/?probe=8b54af493a) | Apr 19, 2022 |
| Dell          | Latitude E6440              | [33955db41e](https://linux-hardware.org/?probe=33955db41e) | Apr 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [1825f45bfa](https://linux-hardware.org/?probe=1825f45bfa) | Apr 17, 2022 |
| MSI           | Modern 14 B4MW              | [5d8e6ca082](https://linux-hardware.org/?probe=5d8e6ca082) | Apr 16, 2022 |
| HP            | Pavilion 17                 | [acb0c7fd0e](https://linux-hardware.org/?probe=acb0c7fd0e) | Apr 16, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1Y90... | [a572c901ca](https://linux-hardware.org/?probe=a572c901ca) | Apr 15, 2022 |
| HP            | Pavilion 17                 | [014f42ecee](https://linux-hardware.org/?probe=014f42ecee) | Apr 15, 2022 |
| Acer          | Aspire 5750G                | [73d1368d93](https://linux-hardware.org/?probe=73d1368d93) | Apr 15, 2022 |
| Dell          | System XPS L702X            | [9ed530100f](https://linux-hardware.org/?probe=9ed530100f) | Apr 13, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | [95ddaa1dae](https://linux-hardware.org/?probe=95ddaa1dae) | Apr 13, 2022 |
| Dell          | Inspiron 5570               | [ba6f51707b](https://linux-hardware.org/?probe=ba6f51707b) | Apr 13, 2022 |
| HP            | EliteBook 2540p             | [a06e300bfd](https://linux-hardware.org/?probe=a06e300bfd) | Apr 12, 2022 |
| ASUSTek       | X541UAK                     | [ffb5635168](https://linux-hardware.org/?probe=ffb5635168) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | [5b1a24bf51](https://linux-hardware.org/?probe=5b1a24bf51) | Apr 10, 2022 |
| Dell          | Vostro 3500                 | [b2adbbe7d0](https://linux-hardware.org/?probe=b2adbbe7d0) | Apr 10, 2022 |
| Dell          | Vostro 15 3515              | [5fea9b2c3a](https://linux-hardware.org/?probe=5fea9b2c3a) | Apr 08, 2022 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [8cdcd8d130](https://linux-hardware.org/?probe=8cdcd8d130) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | [d49b3ef408](https://linux-hardware.org/?probe=d49b3ef408) | Apr 08, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [9cbf0f3aad](https://linux-hardware.org/?probe=9cbf0f3aad) | Apr 04, 2022 |
| Lenovo        | G510 20238                  | [beeceac759](https://linux-hardware.org/?probe=beeceac759) | Apr 04, 2022 |
| Lenovo        | B590 37612LG                | [153a6c2343](https://linux-hardware.org/?probe=153a6c2343) | Apr 04, 2022 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | [4c96d9df2f](https://linux-hardware.org/?probe=4c96d9df2f) | Apr 02, 2022 |
| HP            | 250 G4                      | [69a3535c1a](https://linux-hardware.org/?probe=69a3535c1a) | Mar 30, 2022 |
| Acer          | Aspire 5920G                | [c2d3fbb93e](https://linux-hardware.org/?probe=c2d3fbb93e) | Mar 30, 2022 |
| Acer          | Swift SF314-511             | [ffde31bd20](https://linux-hardware.org/?probe=ffde31bd20) | Mar 26, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [a05a647662](https://linux-hardware.org/?probe=a05a647662) | Mar 25, 2022 |
| Dell          | Inspiron 15-3567            | [2bbea411a6](https://linux-hardware.org/?probe=2bbea411a6) | Mar 24, 2022 |
| Dell          | Inspiron 15-3567            | [c55e29b1e9](https://linux-hardware.org/?probe=c55e29b1e9) | Mar 22, 2022 |
| Gigabyte      | AERO 15 YD                  | [ce6cc28ca1](https://linux-hardware.org/?probe=ce6cc28ca1) | Mar 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [8d1c371df2](https://linux-hardware.org/?probe=8d1c371df2) | Mar 21, 2022 |
| Gigabyte      | AERO 15 YD                  | [35da4bbe2c](https://linux-hardware.org/?probe=35da4bbe2c) | Mar 21, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [626ee37f9b](https://linux-hardware.org/?probe=626ee37f9b) | Mar 21, 2022 |
| Acer          | Swift SF314-57              | [a93c59159d](https://linux-hardware.org/?probe=a93c59159d) | Mar 20, 2022 |
| Acer          | Swift SF514-55GT            | [ae09c5da41](https://linux-hardware.org/?probe=ae09c5da41) | Mar 20, 2022 |
| Acer          | Swift SF114-33              | [7e8098be12](https://linux-hardware.org/?probe=7e8098be12) | Mar 20, 2022 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [b8b480e048](https://linux-hardware.org/?probe=b8b480e048) | Mar 20, 2022 |
| Dell          | Inspiron 3583               | [a3a8154156](https://linux-hardware.org/?probe=a3a8154156) | Mar 17, 2022 |
| HP            | ProBook 450 G2              | [177d9b8820](https://linux-hardware.org/?probe=177d9b8820) | Mar 16, 2022 |
| Dell          | Inspiron 15-3567            | [5da90f10f4](https://linux-hardware.org/?probe=5da90f10f4) | Mar 15, 2022 |
| ASUSTek       | X540YA                      | [0cd3840828](https://linux-hardware.org/?probe=0cd3840828) | Mar 14, 2022 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [1b57f1f410](https://linux-hardware.org/?probe=1b57f1f410) | Mar 13, 2022 |
| Lenovo        | G510 20238                  | [c82a0d33a2](https://linux-hardware.org/?probe=c82a0d33a2) | Mar 12, 2022 |
| Dell          | Inspiron MM061              | [ad5413d163](https://linux-hardware.org/?probe=ad5413d163) | Mar 06, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | [3b3220eeee](https://linux-hardware.org/?probe=3b3220eeee) | Mar 06, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [f89153c3e1](https://linux-hardware.org/?probe=f89153c3e1) | Mar 05, 2022 |
| Acer          | Aspire A315-41              | [6d26072b9e](https://linux-hardware.org/?probe=6d26072b9e) | Mar 03, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [53d74176e9](https://linux-hardware.org/?probe=53d74176e9) | Mar 03, 2022 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [73881ad12e](https://linux-hardware.org/?probe=73881ad12e) | Mar 03, 2022 |
| MSI           | GP75 Leopard 9SE            | [6090fb66ea](https://linux-hardware.org/?probe=6090fb66ea) | Mar 02, 2022 |
| MSI           | GP75 Leopard 9SE            | [c56a98389f](https://linux-hardware.org/?probe=c56a98389f) | Mar 01, 2022 |
| Medion        | E16402                      | [1622ca8570](https://linux-hardware.org/?probe=1622ca8570) | Feb 27, 2022 |
| Acer          | Aspire E1-571               | [c8dd47fb82](https://linux-hardware.org/?probe=c8dd47fb82) | Feb 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [402a27e190](https://linux-hardware.org/?probe=402a27e190) | Feb 24, 2022 |
| ASUSTek       | X55U                        | [c7c38f077d](https://linux-hardware.org/?probe=c7c38f077d) | Feb 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [6083eed5da](https://linux-hardware.org/?probe=6083eed5da) | Feb 21, 2022 |
| Lenovo        | ThinkPad T430 2349U15       | [38a194c33d](https://linux-hardware.org/?probe=38a194c33d) | Feb 20, 2022 |
| Dell          | Latitude E6540              | [dfc7dad0ee](https://linux-hardware.org/?probe=dfc7dad0ee) | Feb 17, 2022 |
| Lenovo        | ThinkPad P50 20ENS0FQ00     | [8d8e30fdfb](https://linux-hardware.org/?probe=8d8e30fdfb) | Feb 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [5d2de5cd73](https://linux-hardware.org/?probe=5d2de5cd73) | Feb 17, 2022 |
| Acer          | Aspire A315-34              | [f6383e06d7](https://linux-hardware.org/?probe=f6383e06d7) | Feb 16, 2022 |
| MSI           | EX620                       | [8eda01e2a8](https://linux-hardware.org/?probe=8eda01e2a8) | Feb 14, 2022 |
| HP            | EliteBook 8530p             | [6b45115b9e](https://linux-hardware.org/?probe=6b45115b9e) | Feb 13, 2022 |
| Lenovo        | ThinkPad T410 2522Y15       | [66a496ba4c](https://linux-hardware.org/?probe=66a496ba4c) | Feb 09, 2022 |
| Chuwi         | GemiBook Pro                | [7d600bcdc7](https://linux-hardware.org/?probe=7d600bcdc7) | Feb 08, 2022 |
| Lenovo        | ThinkPad L380 20M5003FUK    | [fe486b4de6](https://linux-hardware.org/?probe=fe486b4de6) | Feb 08, 2022 |
| Lenovo        | ThinkPad T460 20FMS3W300    | [a49c14ab70](https://linux-hardware.org/?probe=a49c14ab70) | Feb 06, 2022 |
| Allview       | Allbook H                   | [f1ba3f22c4](https://linux-hardware.org/?probe=f1ba3f22c4) | Feb 05, 2022 |
| Lenovo        | G510 20238                  | [4975c3b6b7](https://linux-hardware.org/?probe=4975c3b6b7) | Feb 05, 2022 |
| HP            | Pavilion dv6                | [63c8ab5447](https://linux-hardware.org/?probe=63c8ab5447) | Feb 03, 2022 |
| HP            | EliteBook x360 1040 G5      | [4aa3aa1f30](https://linux-hardware.org/?probe=4aa3aa1f30) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | [1e330f1e0e](https://linux-hardware.org/?probe=1e330f1e0e) | Feb 02, 2022 |
| HP            | Laptop 15s-fq1xxx           | [7c2762f41c](https://linux-hardware.org/?probe=7c2762f41c) | Jan 31, 2022 |
| HP            | Laptop 15s-fq1xxx           | [2aa45a8d1b](https://linux-hardware.org/?probe=2aa45a8d1b) | Jan 31, 2022 |
| Lenovo        | G510 20238                  | [b61bba90ad](https://linux-hardware.org/?probe=b61bba90ad) | Jan 30, 2022 |
| Acer          | Extensa 2510                | [1fcabc0254](https://linux-hardware.org/?probe=1fcabc0254) | Jan 26, 2022 |
| Lenovo        | V330-15IKB 81AX             | [3bcb1d5f53](https://linux-hardware.org/?probe=3bcb1d5f53) | Jan 25, 2022 |
| HP            | Pavilion TS 11              | [6d62bb9596](https://linux-hardware.org/?probe=6d62bb9596) | Jan 24, 2022 |
| Dell          | Inspiron 5567               | [0e47f03d64](https://linux-hardware.org/?probe=0e47f03d64) | Jan 24, 2022 |
| HP            | EliteBook 840 G6            | [ded9015aff](https://linux-hardware.org/?probe=ded9015aff) | Jan 23, 2022 |
| Acer          | Aspire E1-531               | [d90de3e8f7](https://linux-hardware.org/?probe=d90de3e8f7) | Jan 21, 2022 |
| HP            | Pavilion TS 11              | [d4187f35fd](https://linux-hardware.org/?probe=d4187f35fd) | Jan 19, 2022 |
| ASUSTek       | X541UAK                     | [2f55e0a142](https://linux-hardware.org/?probe=2f55e0a142) | Jan 19, 2022 |
| Dell          | MXG071                      | [cd914ee2f0](https://linux-hardware.org/?probe=cd914ee2f0) | Jan 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [d786a0b993](https://linux-hardware.org/?probe=d786a0b993) | Jan 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [6af6121c33](https://linux-hardware.org/?probe=6af6121c33) | Jan 17, 2022 |
| Dell          | Inspiron 5567               | [4b51693e30](https://linux-hardware.org/?probe=4b51693e30) | Jan 17, 2022 |
| Lenovo        | ThinkPad X61s 7666WCQ       | [7e1d764ca8](https://linux-hardware.org/?probe=7e1d764ca8) | Jan 16, 2022 |
| Samsung       | R580/R590                   | [be1e77de84](https://linux-hardware.org/?probe=be1e77de84) | Jan 16, 2022 |
| Acer          | Aspire E1-531               | [342f6f2beb](https://linux-hardware.org/?probe=342f6f2beb) | Jan 16, 2022 |
| Acer          | Aspire E1-531               | [34f103b8d2](https://linux-hardware.org/?probe=34f103b8d2) | Jan 16, 2022 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [efe75d8f3f](https://linux-hardware.org/?probe=efe75d8f3f) | Jan 14, 2022 |
| Lenovo        | ThinkPad T420 4236WR1       | [15dd95fdfd](https://linux-hardware.org/?probe=15dd95fdfd) | Jan 14, 2022 |
| Lenovo        | G50-70 20351                | [615ed31a98](https://linux-hardware.org/?probe=615ed31a98) | Jan 13, 2022 |
| Dell          | Inspiron 5570               | [5f41c8e050](https://linux-hardware.org/?probe=5f41c8e050) | Jan 12, 2022 |
| HP            | ProBook 450 G2              | [7ace73b9e5](https://linux-hardware.org/?probe=7ace73b9e5) | Jan 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [56d6ea164b](https://linux-hardware.org/?probe=56d6ea164b) | Jan 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [d9bd1bab23](https://linux-hardware.org/?probe=d9bd1bab23) | Jan 09, 2022 |
| ASUSTek       | X541UAK                     | [353534e82a](https://linux-hardware.org/?probe=353534e82a) | Jan 08, 2022 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [ba78c8aef3](https://linux-hardware.org/?probe=ba78c8aef3) | Jan 07, 2022 |
| Hungaro Fl... | Navon Loop 360              | [3e7d72e09a](https://linux-hardware.org/?probe=3e7d72e09a) | Jan 06, 2022 |
| Chuwi         | Hero Book                   | [b111f44fad](https://linux-hardware.org/?probe=b111f44fad) | Jan 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [6eab59bbbf](https://linux-hardware.org/?probe=6eab59bbbf) | Jan 05, 2022 |
| ASUSTek       | X550VL                      | [46ed51f6ef](https://linux-hardware.org/?probe=46ed51f6ef) | Jan 04, 2022 |
| MSI           | Prestige 15 A10SC           | [0132076c85](https://linux-hardware.org/?probe=0132076c85) | Jan 04, 2022 |
| ASUSTek       | X550VX                      | [d7ef034908](https://linux-hardware.org/?probe=d7ef034908) | Jan 03, 2022 |
| ASUSTek       | N53Jf                       | [3f0e64b85e](https://linux-hardware.org/?probe=3f0e64b85e) | Jan 03, 2022 |
| ASUSTek       | N53Jf                       | [6d7b0abdfa](https://linux-hardware.org/?probe=6d7b0abdfa) | Jan 03, 2022 |
| Lenovo        | ThinkPad X220 4291B78       | [76350af57f](https://linux-hardware.org/?probe=76350af57f) | Jan 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [a7217db810](https://linux-hardware.org/?probe=a7217db810) | Jan 02, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [286ce69daf](https://linux-hardware.org/?probe=286ce69daf) | Jan 02, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [f5eafcc9e4](https://linux-hardware.org/?probe=f5eafcc9e4) | Jan 02, 2022 |
| HP            | Laptop 15-da0xxx            | [50a5dc78eb](https://linux-hardware.org/?probe=50a5dc78eb) | Jan 02, 2022 |
| MSI           | EX705                       | [a969bd4369](https://linux-hardware.org/?probe=a969bd4369) | Dec 31, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | [64743b9e56](https://linux-hardware.org/?probe=64743b9e56) | Dec 30, 2021 |
| MSI           | GP75 Leopard 9SE            | [af923f06cc](https://linux-hardware.org/?probe=af923f06cc) | Dec 29, 2021 |
| Dell          | Latitude E5420m             | [6f5af5da5c](https://linux-hardware.org/?probe=6f5af5da5c) | Dec 29, 2021 |
| MSI           | GP75 Leopard 9SE            | [a7a37c26c7](https://linux-hardware.org/?probe=a7a37c26c7) | Dec 29, 2021 |
| Dream Mach... | NH5x_NH7x_HHx_HJx_HKx       | [c3f88b03df](https://linux-hardware.org/?probe=c3f88b03df) | Dec 28, 2021 |
| HP            | EliteBook 850 G2            | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b2b9ea9e60](https://linux-hardware.org/?probe=b2b9ea9e60) | Dec 24, 2021 |
| Lenovo        | ThinkPad X220 4291B78       | [2c8a912b3e](https://linux-hardware.org/?probe=2c8a912b3e) | Dec 24, 2021 |
| HP            | EliteBook 850 G2            | [e4dc4b8711](https://linux-hardware.org/?probe=e4dc4b8711) | Dec 23, 2021 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [d6d85114b6](https://linux-hardware.org/?probe=d6d85114b6) | Dec 23, 2021 |
| Acer          | Aspire A315-41              | [85da21d9e9](https://linux-hardware.org/?probe=85da21d9e9) | Dec 22, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [6748ebc68a](https://linux-hardware.org/?probe=6748ebc68a) | Dec 20, 2021 |
| MSI           | Modern 14 B5M               | [3e8138c5b4](https://linux-hardware.org/?probe=3e8138c5b4) | Dec 18, 2021 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | [00868d9166](https://linux-hardware.org/?probe=00868d9166) | Dec 17, 2021 |
| Timi          | TM1701                      | [f063712cce](https://linux-hardware.org/?probe=f063712cce) | Dec 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [ac40d89d27](https://linux-hardware.org/?probe=ac40d89d27) | Dec 16, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | [7da5a1020d](https://linux-hardware.org/?probe=7da5a1020d) | Dec 15, 2021 |
| Chuwi         | Hero Book                   | [27e37e5a15](https://linux-hardware.org/?probe=27e37e5a15) | Dec 14, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | [85770fb8f5](https://linux-hardware.org/?probe=85770fb8f5) | Dec 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X545... | [b68de5799e](https://linux-hardware.org/?probe=b68de5799e) | Dec 12, 2021 |
| MSI           | Modern 14 B4MW              | [5d06e53d08](https://linux-hardware.org/?probe=5d06e53d08) | Dec 12, 2021 |
| ASUSTek       | X550LD                      | [5be7aac3a2](https://linux-hardware.org/?probe=5be7aac3a2) | Dec 09, 2021 |
| Hungaro Fl... | Navon Loop 360              | [96b150762b](https://linux-hardware.org/?probe=96b150762b) | Dec 08, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | [98f25277f5](https://linux-hardware.org/?probe=98f25277f5) | Dec 08, 2021 |
| Lenovo        | Y520-15IKBM 80YY            | [902395fcce](https://linux-hardware.org/?probe=902395fcce) | Dec 03, 2021 |
| HP            | ZBook 15 G5                 | [b42c2359f4](https://linux-hardware.org/?probe=b42c2359f4) | Dec 03, 2021 |
| Lenovo        | G510 20238                  | [d3040ac7d5](https://linux-hardware.org/?probe=d3040ac7d5) | Nov 30, 2021 |
| Allview       | Allbook J                   | [957074dbe3](https://linux-hardware.org/?probe=957074dbe3) | Nov 30, 2021 |
| Sony          | SVE1713Y1EB                 | [317b686b33](https://linux-hardware.org/?probe=317b686b33) | Nov 29, 2021 |
| Dell          | Vostro 3500                 | [c323b490bf](https://linux-hardware.org/?probe=c323b490bf) | Nov 26, 2021 |
| ASUSTek       | K53SD                       | [b2826b96f2](https://linux-hardware.org/?probe=b2826b96f2) | Nov 24, 2021 |
| Sony          | SVE1713Y1EB                 | [755b7b85f5](https://linux-hardware.org/?probe=755b7b85f5) | Nov 24, 2021 |
| Medion        | E7218                       | [e4a790a38d](https://linux-hardware.org/?probe=e4a790a38d) | Nov 23, 2021 |
| HP            | Compaq 2510p                | [8bc24dae3e](https://linux-hardware.org/?probe=8bc24dae3e) | Nov 23, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [eb7191f8cb](https://linux-hardware.org/?probe=eb7191f8cb) | Nov 22, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [1169bef865](https://linux-hardware.org/?probe=1169bef865) | Nov 22, 2021 |
| HP            | Compaq 2510p                | [c76241a894](https://linux-hardware.org/?probe=c76241a894) | Nov 22, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [bb48a45349](https://linux-hardware.org/?probe=bb48a45349) | Nov 22, 2021 |
| Lenovo        | Legion Y540-17IRH-PG0 81... | [898f3db0ed](https://linux-hardware.org/?probe=898f3db0ed) | Nov 22, 2021 |
| Acer          | Aspire E1-531               | [9a83e53e34](https://linux-hardware.org/?probe=9a83e53e34) | Nov 22, 2021 |
| ASUSTek       | X450CP                      | [7228a5157c](https://linux-hardware.org/?probe=7228a5157c) | Nov 20, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [04fa536869](https://linux-hardware.org/?probe=04fa536869) | Nov 20, 2021 |
| Lenovo        | IdeaPad 330S-14IKB 81F4     | [097de81570](https://linux-hardware.org/?probe=097de81570) | Nov 20, 2021 |
| Sony          | SVE1713Y1EB                 | [4a77a751d9](https://linux-hardware.org/?probe=4a77a751d9) | Nov 20, 2021 |
| Dell          | Latitude 7410               | [226f912726](https://linux-hardware.org/?probe=226f912726) | Nov 18, 2021 |
| ASUSTek       | K53U                        | [8b542e61d9](https://linux-hardware.org/?probe=8b542e61d9) | Nov 18, 2021 |
| Dell          | Latitude E7470              | [0358863974](https://linux-hardware.org/?probe=0358863974) | Nov 16, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [6677eae4da](https://linux-hardware.org/?probe=6677eae4da) | Nov 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | [48f29ffe3a](https://linux-hardware.org/?probe=48f29ffe3a) | Nov 14, 2021 |
| ASUSTek       | X540SA                      | [1292ab6f15](https://linux-hardware.org/?probe=1292ab6f15) | Nov 14, 2021 |
| Dell          | Latitude E6410              | [1a31fa8433](https://linux-hardware.org/?probe=1a31fa8433) | Nov 13, 2021 |
| ASUSTek       | X540SA                      | [463e1f35a9](https://linux-hardware.org/?probe=463e1f35a9) | Nov 13, 2021 |
| Sony          | SVF14N1E2ES                 | [a04441e5cd](https://linux-hardware.org/?probe=a04441e5cd) | Nov 13, 2021 |
| Dell          | Precision 3541              | [8f6085ab9d](https://linux-hardware.org/?probe=8f6085ab9d) | Nov 12, 2021 |
| Packard Be... | EasyNote TN36               | [17ebc64721](https://linux-hardware.org/?probe=17ebc64721) | Nov 11, 2021 |
| Dell          | XPS 13 9350                 | [e70882b3fd](https://linux-hardware.org/?probe=e70882b3fd) | Nov 11, 2021 |
| Notebook      | N85_N87HCHNHZ               | [32988fae95](https://linux-hardware.org/?probe=32988fae95) | Nov 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [b79aef683b](https://linux-hardware.org/?probe=b79aef683b) | Nov 11, 2021 |
| HP            | EliteBook 850 G2            | [c1bd9abdd2](https://linux-hardware.org/?probe=c1bd9abdd2) | Nov 03, 2021 |
| Dell          | G3 3579                     | [f9fdeb003b](https://linux-hardware.org/?probe=f9fdeb003b) | Nov 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [8cdb34dbc8](https://linux-hardware.org/?probe=8cdb34dbc8) | Nov 01, 2021 |
| Lenovo        | ThinkPad T430 2349U15       | [c9d8efc9b9](https://linux-hardware.org/?probe=c9d8efc9b9) | Oct 31, 2021 |
| Lenovo        | G510 20238                  | [60fa5ff04c](https://linux-hardware.org/?probe=60fa5ff04c) | Oct 28, 2021 |
| Dell          | Latitude E5450              | [fb61a77e5c](https://linux-hardware.org/?probe=fb61a77e5c) | Oct 26, 2021 |
| Lenovo        | ThinkPad X230 2325SWF       | [64f9882936](https://linux-hardware.org/?probe=64f9882936) | Oct 25, 2021 |
| Apple         | MacBookPro14,3              | [69a5d79a58](https://linux-hardware.org/?probe=69a5d79a58) | Oct 24, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [9b3e361eb7](https://linux-hardware.org/?probe=9b3e361eb7) | Oct 24, 2021 |
| Dell          | Latitude E7470              | [69a251cc1f](https://linux-hardware.org/?probe=69a251cc1f) | Oct 22, 2021 |
| Dell          | Latitude E7470              | [96ef0ee68c](https://linux-hardware.org/?probe=96ef0ee68c) | Oct 22, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [21379aad70](https://linux-hardware.org/?probe=21379aad70) | Oct 21, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [f0c049fc34](https://linux-hardware.org/?probe=f0c049fc34) | Oct 20, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [d550d04ac7](https://linux-hardware.org/?probe=d550d04ac7) | Oct 20, 2021 |
| HUAWEI        | MACHD-WXX9                  | [8563f3786e](https://linux-hardware.org/?probe=8563f3786e) | Oct 19, 2021 |
| Lenovo        | ThinkPad L440 20ASS3A300    | [ac37b3fd23](https://linux-hardware.org/?probe=ac37b3fd23) | Oct 18, 2021 |
| MSI           | GE66 Raider 11UH            | [cbf3c67be2](https://linux-hardware.org/?probe=cbf3c67be2) | Oct 18, 2021 |
| Lenovo        | IdeaPad L340-17API 81LY     | [cc0290a8df](https://linux-hardware.org/?probe=cc0290a8df) | Oct 18, 2021 |
| MSI           | GE66 Raider 11UH            | [0b2123c367](https://linux-hardware.org/?probe=0b2123c367) | Oct 16, 2021 |
| Dell          | Latitude E7470              | [3bbcb85b9f](https://linux-hardware.org/?probe=3bbcb85b9f) | Oct 16, 2021 |
| HP            | 255 G7 Notebook PC          | [28930b356e](https://linux-hardware.org/?probe=28930b356e) | Oct 16, 2021 |
| Sony          | SVE1713Y1EB                 | [b59de957b3](https://linux-hardware.org/?probe=b59de957b3) | Oct 11, 2021 |
| Sony          | SVE1713Y1EB                 | [a427a26f34](https://linux-hardware.org/?probe=a427a26f34) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [1965a71536](https://linux-hardware.org/?probe=1965a71536) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6166a72ec2](https://linux-hardware.org/?probe=6166a72ec2) | Oct 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [0acb396573](https://linux-hardware.org/?probe=0acb396573) | Oct 11, 2021 |
| Acer          | Aspire 5741G                | [ea162f9171](https://linux-hardware.org/?probe=ea162f9171) | Oct 10, 2021 |
| Acer          | Aspire A315-51              | [d79188a009](https://linux-hardware.org/?probe=d79188a009) | Oct 10, 2021 |
| Acer          | Aspire A315-51              | [aae51881da](https://linux-hardware.org/?probe=aae51881da) | Oct 10, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [efb88027ec](https://linux-hardware.org/?probe=efb88027ec) | Oct 09, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [2236b91c55](https://linux-hardware.org/?probe=2236b91c55) | Oct 05, 2021 |
| HP            | EliteBook 8770w             | [d23574ecf1](https://linux-hardware.org/?probe=d23574ecf1) | Oct 04, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [2f89b6fcf1](https://linux-hardware.org/?probe=2f89b6fcf1) | Oct 03, 2021 |
| Lenovo        | ThinkPad T470 20HES0FA02    | [b368193a4e](https://linux-hardware.org/?probe=b368193a4e) | Oct 02, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [3f4fe97a8a](https://linux-hardware.org/?probe=3f4fe97a8a) | Sep 30, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [032d34e75b](https://linux-hardware.org/?probe=032d34e75b) | Sep 28, 2021 |
| Acer          | Aspire A315-42              | [3cbca1757f](https://linux-hardware.org/?probe=3cbca1757f) | Sep 26, 2021 |
| Alienware     | 17 R2                       | [cbe7430492](https://linux-hardware.org/?probe=cbe7430492) | Sep 26, 2021 |
| ASUSTek       | FX503VD                     | [c91cad59c2](https://linux-hardware.org/?probe=c91cad59c2) | Sep 25, 2021 |
| Acer          | Aspire 5715Z                | [a44995aac4](https://linux-hardware.org/?probe=a44995aac4) | Sep 25, 2021 |
| HP            | Pavilion dv6                | [a97e17fc48](https://linux-hardware.org/?probe=a97e17fc48) | Sep 25, 2021 |
| HP            | EliteBook 8530p             | [8002401481](https://linux-hardware.org/?probe=8002401481) | Sep 23, 2021 |
| HP            | Pavilion dv6                | [72f179ec58](https://linux-hardware.org/?probe=72f179ec58) | Sep 22, 2021 |
| Lenovo        | ThinkPad X260 20F5S08Q00    | [f6dfc42935](https://linux-hardware.org/?probe=f6dfc42935) | Sep 22, 2021 |
| ASUSTek       | UX550VE                     | [72925fef5d](https://linux-hardware.org/?probe=72925fef5d) | Sep 21, 2021 |
| ASUSTek       | GL752VW                     | [ec4b89fd42](https://linux-hardware.org/?probe=ec4b89fd42) | Sep 20, 2021 |
| Lenovo        | Legion Y7000 2019 PG0 81... | [75c71d1f1e](https://linux-hardware.org/?probe=75c71d1f1e) | Sep 20, 2021 |
| Acer          | Aspire A515-56              | [7b95b06b4d](https://linux-hardware.org/?probe=7b95b06b4d) | Sep 20, 2021 |
| Dell          | Inspiron 1564               | [3a0a2208fb](https://linux-hardware.org/?probe=3a0a2208fb) | Sep 20, 2021 |
| ASUSTek       | X540YA                      | [c0b5da7979](https://linux-hardware.org/?probe=c0b5da7979) | Sep 19, 2021 |
| Acer          | AOA110                      | [a54c248743](https://linux-hardware.org/?probe=a54c248743) | Sep 19, 2021 |
| HP            | Pavilion dv6                | [b4d25f6f3a](https://linux-hardware.org/?probe=b4d25f6f3a) | Sep 19, 2021 |
| Sony          | VGN-CR21Z_N                 | [6fc19f4c67](https://linux-hardware.org/?probe=6fc19f4c67) | Sep 19, 2021 |
| Dell          | Inspiron 1564               | [252914c6d3](https://linux-hardware.org/?probe=252914c6d3) | Sep 16, 2021 |
| Dell          | Inspiron 7537               | [1493a2eae1](https://linux-hardware.org/?probe=1493a2eae1) | Sep 15, 2021 |
| Toshiba       | Satellite C55-C             | [8966b3a7b5](https://linux-hardware.org/?probe=8966b3a7b5) | Sep 14, 2021 |
| HP            | EliteBook 840 G4            | [8bd6acee77](https://linux-hardware.org/?probe=8bd6acee77) | Sep 13, 2021 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [bc6963f758](https://linux-hardware.org/?probe=bc6963f758) | Sep 11, 2021 |
| Packard Be... | EasyNote MV86               | [ea018cddf2](https://linux-hardware.org/?probe=ea018cddf2) | Sep 10, 2021 |
| Dell          | Inspiron 5520               | [835f9cb8a1](https://linux-hardware.org/?probe=835f9cb8a1) | Sep 07, 2021 |
| Dell          | Latitude 7410               | [8f1a1a4798](https://linux-hardware.org/?probe=8f1a1a4798) | Sep 06, 2021 |
| Dell          | Latitude 7410               | [b03a0e0152](https://linux-hardware.org/?probe=b03a0e0152) | Sep 06, 2021 |
| Lenovo        | G50-70 20351                | [576b96b6da](https://linux-hardware.org/?probe=576b96b6da) | Sep 06, 2021 |
| Lenovo        | ThinkPad W520 4284AW3       | [6647a6a4b4](https://linux-hardware.org/?probe=6647a6a4b4) | Sep 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [47c2053681](https://linux-hardware.org/?probe=47c2053681) | Sep 02, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5515        | [fdb725803b](https://linux-hardware.org/?probe=fdb725803b) | Sep 01, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [4765b87a68](https://linux-hardware.org/?probe=4765b87a68) | Sep 01, 2021 |
| ASUSTek       | K52F                        | [743e5c8059](https://linux-hardware.org/?probe=743e5c8059) | Sep 01, 2021 |
| ASUSTek       | K52F                        | [54d5076bc6](https://linux-hardware.org/?probe=54d5076bc6) | Sep 01, 2021 |
| ASUSTek       | UX550VE                     | [cd80e1ebb2](https://linux-hardware.org/?probe=cd80e1ebb2) | Aug 31, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [c2b7f1ee7c](https://linux-hardware.org/?probe=c2b7f1ee7c) | Aug 30, 2021 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | [301be6f800](https://linux-hardware.org/?probe=301be6f800) | Aug 30, 2021 |
| MSI           | MS-16Y1                     | [a9801b616e](https://linux-hardware.org/?probe=a9801b616e) | Aug 29, 2021 |
| Lenovo        | ThinkPad L440 20ASS3A300    | [0a9f1f10d8](https://linux-hardware.org/?probe=0a9f1f10d8) | Aug 29, 2021 |
| ASUSTek       | X450CP                      | [d646ffd8db](https://linux-hardware.org/?probe=d646ffd8db) | Aug 29, 2021 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | [954900ccc6](https://linux-hardware.org/?probe=954900ccc6) | Aug 28, 2021 |
| Acer          | Aspire 5750G                | [03a89677c0](https://linux-hardware.org/?probe=03a89677c0) | Aug 26, 2021 |
| HP            | Presario CQ57               | [4b863ffc87](https://linux-hardware.org/?probe=4b863ffc87) | Aug 25, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [f534340eab](https://linux-hardware.org/?probe=f534340eab) | Aug 22, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [4f6bd2a75e](https://linux-hardware.org/?probe=4f6bd2a75e) | Aug 22, 2021 |
| HP            | Presario CQ57               | [a45389ec74](https://linux-hardware.org/?probe=a45389ec74) | Aug 21, 2021 |
| Dell          | Inspiron 5558               | [eb664f1a19](https://linux-hardware.org/?probe=eb664f1a19) | Aug 20, 2021 |
| ASUSTek       | N53SM                       | [cf9c1726af](https://linux-hardware.org/?probe=cf9c1726af) | Aug 19, 2021 |
| HP            | Pavilion dv6                | [40cd012d76](https://linux-hardware.org/?probe=40cd012d76) | Aug 18, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7465dcb16d](https://linux-hardware.org/?probe=7465dcb16d) | Aug 17, 2021 |
| HP            | Pavilion dv6                | [8bf5049adc](https://linux-hardware.org/?probe=8bf5049adc) | Aug 17, 2021 |
| HP            | Pavilion dv6                | [92e25a1c2c](https://linux-hardware.org/?probe=92e25a1c2c) | Aug 15, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | [f3506aaa1c](https://linux-hardware.org/?probe=f3506aaa1c) | Aug 14, 2021 |
| HP            | 630                         | [eda8d23dba](https://linux-hardware.org/?probe=eda8d23dba) | Aug 13, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [c8b1a45676](https://linux-hardware.org/?probe=c8b1a45676) | Aug 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [20a828b938](https://linux-hardware.org/?probe=20a828b938) | Aug 11, 2021 |
| ASUSTek       | X550JX                      | [da2cacc763](https://linux-hardware.org/?probe=da2cacc763) | Aug 11, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Romania/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 142       | 9.5%    |
| Ubuntu 22.04                 | 85        | 5.69%   |
| Ubuntu 18.04                 | 66        | 4.41%   |
| BlackPanther 18.1            | 30        | 2.01%   |
| OpenMandriva 4.3             | 29        | 1.94%   |
| Arch Rolling                 | 27        | 1.81%   |
| Fedora 39                    | 25        | 1.67%   |
| Manjaro                      | 24        | 1.61%   |
| OpenMandriva 4.2             | 23        | 1.54%   |
| Zorin 16                     | 20        | 1.34%   |
| Pop!_OS 21.04                | 19        | 1.27%   |
| Ubuntu 21.10                 | 18        | 1.2%    |
| Pop!_OS 22.04                | 18        | 1.2%    |
| ArcoLinux Rolling            | 18        | 1.2%    |
| openSUSE Tumbleweed-XXXXXXXX | 17        | 1.14%   |
| KDE neon 20.04               | 17        | 1.14%   |
| Debian 11                    | 17        | 1.14%   |
| Arch                         | 17        | 1.14%   |
| ROSA R10                     | 16        | 1.07%   |
| Endless 3.7.8                | 16        | 1.07%   |
| Zorin 15                     | 15        | 1%      |
| Linux Mint 21.1              | 15        | 1%      |
| Endless 3.9.5                | 15        | 1%      |
| Endless 3.9.1                | 15        | 1%      |
| Debian 12                    | 15        | 1%      |
| OpenMandriva 23.08           | 14        | 0.94%   |
| Linux Mint 21.2              | 14        | 0.94%   |
| Fedora 38                    | 14        | 0.94%   |
| Ubuntu 23.04                 | 12        | 0.8%    |
| Pop!_OS 20.04                | 12        | 0.8%    |
| Endless 3.8.6                | 12        | 0.8%    |
| Endless 3.8.0                | 12        | 0.8%    |
| Linux Mint 20.3              | 11        | 0.74%   |
| Fedora 35                    | 11        | 0.74%   |
| Ubuntu 20.10                 | 10        | 0.67%   |
| Ubuntu 19.10                 | 10        | 0.67%   |
| Fedora 36                    | 10        | 0.67%   |
| Fedora 34                    | 10        | 0.67%   |
| Endless 3.9.0                | 10        | 0.67%   |
| Ubuntu 23.10                 | 9         | 0.6%    |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 374       | 27.08%  |
| Endless       | 212       | 15.35%  |
| OpenMandriva  | 94        | 6.81%   |
| Fedora        | 94        | 6.81%   |
| Linux Mint    | 85        | 6.15%   |
| Pop!_OS       | 60        | 4.34%   |
| Manjaro       | 43        | 3.11%   |
| Arch          | 43        | 3.11%   |
| Debian        | 42        | 3.04%   |
| Zorin         | 40        | 2.9%    |
| ROSA          | 34        | 2.46%   |
| BlackPanther  | 31        | 2.24%   |
| KDE neon      | 22        | 1.59%   |
| ArcoLinux     | 20        | 1.45%   |
| openSUSE      | 19        | 1.38%   |
| Kubuntu       | 18        | 1.3%    |
| Xubuntu       | 17        | 1.23%   |
| Kali          | 13        | 0.94%   |
| Ubuntu Unity  | 10        | 0.72%   |
| Elementary    | 10        | 0.72%   |
| Ubuntu MATE   | 8         | 0.58%   |
| SteamOS       | 8         | 0.58%   |
| EndeavourOS   | 8         | 0.58%   |
| Clear Linux   | 8         | 0.58%   |
| MX            | 7         | 0.51%   |
| Gentoo        | 6         | 0.43%   |
| Linux Lite    | 5         | 0.36%   |
| Peppermint    | 4         | 0.29%   |
| Nobara        | 4         | 0.29%   |
| Lubuntu       | 4         | 0.29%   |
| LMDE          | 4         | 0.29%   |
| Garuda Linux  | 4         | 0.29%   |
| Artix         | 4         | 0.29%   |
| RHEL          | 3         | 0.22%   |
| Xero          | 2         | 0.14%   |
| Slackware     | 2         | 0.14%   |
| Q4OS          | 2         | 0.14%   |
| NixOS         | 2         | 0.14%   |
| Mageia        | 2         | 0.14%   |
| Ubuntu Budgie | 1         | 0.07%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 5.8.0-14-generic         | 56        | 3.6%    |
| 5.4.0-42-generic         | 39        | 2.51%   |
| 5.4.0-19-generic         | 26        | 1.67%   |
| 5.16.7-desktop-1omv4003  | 25        | 1.61%   |
| 5.10.14-desktop-1omv4002 | 23        | 1.48%   |
| 5.3.0-28-generic         | 21        | 1.35%   |
| 4.18.16-desktop-1bP      | 21        | 1.35%   |
| 5.11.0-35-generic        | 16        | 1.03%   |
| 4.18.0-15-generic        | 14        | 0.9%    |
| 5.3.0-23-generic         | 13        | 0.84%   |
| 5.0.0-25-generic         | 13        | 0.84%   |
| 6.4.11-desktop-1omv2390  | 11        | 0.71%   |
| 5.0.0-20-generic         | 10        | 0.64%   |
| 4.15.0-15-generic        | 10        | 0.64%   |
| 6.1.1-desktop-1omv2290   | 9         | 0.58%   |
| 6.2.6-desktop-1omv2390   | 8         | 0.51%   |
| 5.6.14-desktop-2bP       | 8         | 0.51%   |
| 5.3.0-46-generic         | 8         | 0.51%   |
| 5.15.0-56-generic        | 8         | 0.51%   |
| 5.15.0-52-generic        | 8         | 0.51%   |
| 5.13.0-7614-generic      | 8         | 0.51%   |
| 5.0.0-37-generic         | 8         | 0.51%   |
| 5.8.0-50-generic         | 7         | 0.45%   |
| 5.4.0-56-generic         | 7         | 0.45%   |
| 5.4.0-54-generic         | 7         | 0.45%   |
| 5.4.0-40-generic         | 7         | 0.45%   |
| 5.4.0-26-generic         | 7         | 0.45%   |
| 5.3.0-51-generic         | 7         | 0.45%   |
| 5.3.0-19-generic         | 7         | 0.45%   |
| 5.3.0-12-generic         | 7         | 0.45%   |
| 5.19.0-32-generic        | 7         | 0.45%   |
| 5.15.0-71-generic        | 7         | 0.45%   |
| 5.15.0-48-generic        | 7         | 0.45%   |
| 5.11.0-7620-generic      | 7         | 0.45%   |
| 5.0.0-7-generic          | 7         | 0.45%   |
| 6.5.11-300.fc39.x86_64   | 6         | 0.39%   |
| 6.5.0-21-generic         | 6         | 0.39%   |
| 6.2.0-36-generic         | 6         | 0.39%   |
| 6.2.0-34-generic         | 6         | 0.39%   |
| 5.4.0-37-generic         | 6         | 0.39%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 202       | 13.48%  |
| 5.15.0  | 110       | 7.34%   |
| 5.8.0   | 108       | 7.2%    |
| 5.3.0   | 87        | 5.8%    |
| 5.11.0  | 69        | 4.6%    |
| 5.0.0   | 63        | 4.2%    |
| 4.15.0  | 59        | 3.94%   |
| 5.13.0  | 54        | 3.6%    |
| 6.5.0   | 41        | 2.74%   |
| 4.18.0  | 40        | 2.67%   |
| 6.2.0   | 39        | 2.6%    |
| 5.19.0  | 33        | 2.2%    |
| 5.16.7  | 25        | 1.67%   |
| 5.10.14 | 24        | 1.6%    |
| 5.10.0  | 23        | 1.53%   |
| 6.1.0   | 22        | 1.47%   |
| 4.18.16 | 21        | 1.4%    |
| 6.4.11  | 13        | 0.87%   |
| 6.2.6   | 13        | 0.87%   |
| 6.1.1   | 11        | 0.73%   |
| 5.6.14  | 9         | 0.6%    |
| 6.6.2   | 8         | 0.53%   |
| 4.9.60  | 8         | 0.53%   |
| 4.9.20  | 8         | 0.53%   |
| 6.5.6   | 7         | 0.47%   |
| 6.5.5   | 7         | 0.47%   |
| 4.13.0  | 7         | 0.47%   |
| 6.5.9   | 6         | 0.4%    |
| 6.5.11  | 6         | 0.4%    |
| 6.1.12  | 6         | 0.4%    |
| 4.19.0  | 6         | 0.4%    |
| 6.4.8   | 5         | 0.33%   |
| 6.3.5   | 5         | 0.33%   |
| 5.17.0  | 5         | 0.33%   |
| 4.9.76  | 5         | 0.33%   |
| 6.3.2   | 4         | 0.27%   |
| 6.0.6   | 4         | 0.27%   |
| 6.0.0   | 4         | 0.27%   |
| 5.9.0   | 4         | 0.27%   |
| 5.16.13 | 4         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 208       | 13.98%  |
| 5.15    | 139       | 9.34%   |
| 5.8     | 121       | 8.13%   |
| 5.3     | 94        | 6.32%   |
| 5.11    | 79        | 5.31%   |
| 6.5     | 71        | 4.77%   |
| 5.0     | 65        | 4.37%   |
| 6.2     | 63        | 4.23%   |
| 4.18    | 63        | 4.23%   |
| 5.10    | 62        | 4.17%   |
| 4.15    | 59        | 3.97%   |
| 6.1     | 58        | 3.9%    |
| 5.13    | 58        | 3.9%    |
| 5.19    | 47        | 3.16%   |
| 5.16    | 43        | 2.89%   |
| 6.6     | 34        | 2.28%   |
| 4.9     | 27        | 1.81%   |
| 6.4     | 22        | 1.48%   |
| 6.0     | 18        | 1.21%   |
| 5.6     | 17        | 1.14%   |
| 5.9     | 15        | 1.01%   |
| 5.17    | 15        | 1.01%   |
| 5.18    | 14        | 0.94%   |
| 6.3     | 13        | 0.87%   |
| 6.7     | 12        | 0.81%   |
| 5.14    | 11        | 0.74%   |
| 5.12    | 10        | 0.67%   |
| 6.8     | 9         | 0.6%    |
| 4.19    | 7         | 0.47%   |
| 4.13    | 7         | 0.47%   |
| 5.7     | 6         | 0.4%    |
| 5.5     | 5         | 0.34%   |
| 5.1     | 3         | 0.2%    |
| 4.1     | 3         | 0.2%    |
| 5.2     | 2         | 0.13%   |
| 4.12    | 2         | 0.13%   |
| 6.9     | 1         | 0.07%   |
| 4.8     | 1         | 0.07%   |
| 4.17    | 1         | 0.07%   |
| 4.16    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1291      | 97.73%  |
| i686   | 29        | 2.2%    |
| armv7l | 1         | 0.08%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 682       | 49.56%  |
| KDE5            | 239       | 17.37%  |
| Unknown         | 151       | 10.97%  |
| XFCE            | 88        | 6.4%    |
| X-Cinnamon      | 66        | 4.8%    |
| KDE4            | 24        | 1.74%   |
| MATE            | 22        | 1.6%    |
| KDE             | 22        | 1.6%    |
| Unity           | 10        | 0.73%   |
| LXQt            | 10        | 0.73%   |
| Pantheon        | 9         | 0.65%   |
| LXDE            | 8         | 0.58%   |
| Cinnamon        | 8         | 0.58%   |
| i3              | 6         | 0.44%   |
| Hyprland        | 5         | 0.36%   |
| sway            | 4         | 0.29%   |
| GNOME Classic   | 3         | 0.22%   |
| Endless:GNOME   | 3         | 0.22%   |
| xmonad          | 2         | 0.15%   |
| KDE6            | 2         | 0.15%   |
| Deepin          | 2         | 0.15%   |
| Budgie          | 2         | 0.15%   |
| ubuntu          | 1         | 0.07%   |
| qtile           | 1         | 0.07%   |
| jwm             | 1         | 0.07%   |
| GNOME Flashback | 1         | 0.07%   |
| Enlightenment   | 1         | 0.07%   |
| DWM             | 1         | 0.07%   |
| bspwm           | 1         | 0.07%   |
| awesome         | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 984       | 72.57%  |
| Wayland | 253       | 18.66%  |
| Unknown | 106       | 7.82%   |
| Tty     | 13        | 0.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 712       | 51.74%  |
| SDDM    | 210       | 15.26%  |
| GDM3    | 156       | 11.34%  |
| GDM     | 133       | 9.67%   |
| LightDM | 110       | 7.99%   |
| TDM     | 24        | 1.74%   |
| KDM     | 23        | 1.67%   |
| XDM     | 4         | 0.29%   |
| SLiM    | 3         | 0.22%   |
| GREETD  | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Notebooks | Percent |
|-------------|-----------|---------|
| en_US       | 845       | 61.95%  |
| ro_RO       | 219       | 16.06%  |
| Unknown     | 195       | 14.3%   |
| en_GB       | 30        | 2.2%    |
| C           | 24        | 1.76%   |
| hu_HU       | 11        | 0.81%   |
| it_IT       | 10        | 0.73%   |
| fr_FR       | 6         | 0.44%   |
| es_ES       | 6         | 0.44%   |
| en_IL       | 3         | 0.22%   |
| de_DE       | 3         | 0.22%   |
| uk_UA       | 1         | 0.07%   |
| ru_RU       | 1         | 0.07%   |
| fr_CH       | 1         | 0.07%   |
| en_US.UTF.8 | 1         | 0.07%   |
| en_IN       | 1         | 0.07%   |
| en_IE       | 1         | 0.07%   |
| en_DK       | 1         | 0.07%   |
| en_CA       | 1         | 0.07%   |
| en_AG       | 1         | 0.07%   |
| en_001      | 1         | 0.07%   |
| de_IT       | 1         | 0.07%   |
| C.UTF8      | 1         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 772       | 56.97%  |
| BIOS | 583       | 43.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 955       | 70.27%  |
| Btrfs   | 128       | 9.42%   |
| Overlay | 113       | 8.31%   |
| Unknown | 110       | 8.09%   |
| Tmpfs   | 38        | 2.8%    |
| Xfs     | 7         | 0.52%   |
| Zfs     | 5         | 0.37%   |
| Ext2    | 2         | 0.15%   |
| F2fs    | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 740       | 54.94%  |
| GPT     | 462       | 34.3%   |
| MBR     | 145       | 10.76%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1190      | 88.87%  |
| Yes       | 149       | 11.13%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 997       | 74.24%  |
| Yes       | 346       | 25.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| ASUSTek Computer               | 371       | 28.11%  |
| Lenovo                         | 290       | 21.97%  |
| Hewlett-Packard                | 179       | 13.56%  |
| Dell                           | 171       | 12.95%  |
| Acer                           | 125       | 9.47%   |
| Toshiba                        | 29        | 2.2%    |
| MSI                            | 17        | 1.29%   |
| Sony                           | 11        | 0.83%   |
| HUAWEI                         | 10        | 0.76%   |
| Complet                        | 10        | 0.76%   |
| Allview                        | 9         | 0.68%   |
| Valve                          | 8         | 0.61%   |
| Medion                         | 8         | 0.61%   |
| Fujitsu Siemens                | 8         | 0.61%   |
| Apple                          | 7         | 0.53%   |
| Samsung Electronics            | 6         | 0.45%   |
| Fujitsu                        | 6         | 0.45%   |
| Unknown                        | 6         | 0.45%   |
| Google                         | 5         | 0.38%   |
| Chuwi                          | 4         | 0.3%    |
| Alienware                      | 4         | 0.3%    |
| TUXEDO                         | 3         | 0.23%   |
| Packard Bell                   | 3         | 0.23%   |
| Timi                           | 2         | 0.15%   |
| WEIGO                          | 1         | 0.08%   |
| Visual Fan                     | 1         | 0.08%   |
| VALE                           | 1         | 0.08%   |
| Thomson                        | 1         | 0.08%   |
| SLIMBOOK                       | 1         | 0.08%   |
| Razer                          | 1         | 0.08%   |
| Prestigio                      | 1         | 0.08%   |
| Pegatron                       | 1         | 0.08%   |
| PC Specialist                  | 1         | 0.08%   |
| Panasonic                      | 1         | 0.08%   |
| Notebook                       | 1         | 0.08%   |
| nJoy Romania                   | 1         | 0.08%   |
| Neousys Technology             | 1         | 0.08%   |
| NEC Computers                  | 1         | 0.08%   |
| Mediacom                       | 1         | 0.08%   |
| Matsushita Electric Industrial | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| ASUS VivoBook 15_ASUS Laptop X540MA_X543MA | 18        | 1.36%   |
| ASUS X541NA                                | 17        | 1.29%   |
| ASUS VivoBook_ASUSLaptop X509FA_X509FA     | 10        | 0.76%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 10        | 0.76%   |
| Unknown                                    | 9         | 0.68%   |
| Valve Jupiter                              | 8         | 0.61%   |
| Dell XPS 15 9530                           | 7         | 0.53%   |
| Complet MY8312                             | 7         | 0.53%   |
| ASUS X541UVK                               | 7         | 0.53%   |
| ASUS X541UAK                               | 7         | 0.53%   |
| ASUS X406UAR                               | 7         | 0.53%   |
| Lenovo Legion Y530-15ICH 81FV              | 6         | 0.45%   |
| ASUS VivoBook_ASUSLaptop X509FB_X509FB     | 6         | 0.45%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_A540MA | 6         | 0.45%   |
| Lenovo V330-15IKB 81AX                     | 5         | 0.38%   |
| HP Notebook                                | 5         | 0.38%   |
| ASUS VivoBook_ASUSLaptop X512DA_X512DA     | 5         | 0.38%   |
| ASUS VivoBook_ASUSLaptop X509DAP_M509DA    | 5         | 0.38%   |
| ASUS VivoBook_ASUS Laptop X505ZA_A505ZA    | 5         | 0.38%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR       | 5         | 0.38%   |
| ASUS GL552JX                               | 5         | 0.38%   |
| Allview Allbook H                          | 5         | 0.38%   |
| Acer Aspire A315-21G                       | 5         | 0.38%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 4         | 0.3%    |
| Lenovo IdeaPad 330-15IKB 81DE              | 4         | 0.3%    |
| Lenovo IdeaPad 100-15IBD 80QQ              | 4         | 0.3%    |
| Lenovo G510 20238                          | 4         | 0.3%    |
| HP ProBook 450 G5                          | 4         | 0.3%    |
| Dell Latitude E6420                        | 4         | 0.3%    |
| Dell Latitude E6410                        | 4         | 0.3%    |
| Dell Inspiron 5558                         | 4         | 0.3%    |
| Dell Inspiron 1545                         | 4         | 0.3%    |
| ASUS ZenBook UX431DA_UM431DA               | 4         | 0.3%    |
| ASUS X542UAR                               | 4         | 0.3%    |
| ASUS VivoBook_ASUSLaptop X530FA_S530FA     | 4         | 0.3%    |
| ASUS VivoBook_ASUSLaptop X513EA_K513EA     | 4         | 0.3%    |
| ASUS VivoBook_ASUSLaptop X1504ZA_R1504ZA   | 4         | 0.3%    |
| Acer Aspire E5-573G                        | 4         | 0.3%    |
| Acer Aspire E1-531                         | 4         | 0.3%    |
| Lenovo V110-15ISK 80TL                     | 3         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| ASUS VivoBook     | 137       | 10.38%  |
| Lenovo ThinkPad   | 97        | 7.35%   |
| Lenovo IdeaPad    | 96        | 7.27%   |
| Acer Aspire       | 90        | 6.82%   |
| Dell Latitude     | 62        | 4.7%    |
| Dell Inspiron     | 52        | 3.94%   |
| HP EliteBook      | 34        | 2.58%   |
| HP ProBook        | 33        | 2.5%    |
| Lenovo Legion     | 30        | 2.27%   |
| Toshiba Satellite | 28        | 2.12%   |
| HP Pavilion       | 25        | 1.89%   |
| ASUS ROG          | 22        | 1.67%   |
| ASUS ASUS         | 22        | 1.67%   |
| Dell XPS          | 20        | 1.52%   |
| HP Laptop         | 19        | 1.44%   |
| ASUS X541NA       | 17        | 1.29%   |
| ASUS ZenBook      | 15        | 1.14%   |
| Lenovo ThinkBook  | 12        | 0.91%   |
| Dell Vostro       | 12        | 0.91%   |
| HP 250            | 11        | 0.83%   |
| ASUS TUF          | 10        | 0.76%   |
| Allview Allbook   | 9         | 0.68%   |
| Unknown           | 9         | 0.68%   |
| Valve Jupiter     | 8         | 0.61%   |
| Lenovo Yoga       | 8         | 0.61%   |
| HP ZBook          | 8         | 0.61%   |
| Acer Swift        | 8         | 0.61%   |
| HP Compaq         | 7         | 0.53%   |
| Dell Precision    | 7         | 0.53%   |
| Complet MY8312    | 7         | 0.53%   |
| ASUS X541UVK      | 7         | 0.53%   |
| ASUS X541UAK      | 7         | 0.53%   |
| ASUS X406UAR      | 7         | 0.53%   |
| Acer Nitro        | 7         | 0.53%   |
| Acer Extensa      | 7         | 0.53%   |
| HP ENVY           | 6         | 0.45%   |
| Fujitsu LIFEBOOK  | 6         | 0.45%   |
| Dell System       | 6         | 0.45%   |
| Lenovo V330-15IKB | 5         | 0.38%   |
| HP OMEN           | 5         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2019    | 180       | 13.64%  |
| 2018    | 133       | 10.08%  |
| 2020    | 120       | 9.09%   |
| 2017    | 118       | 8.94%   |
| 2021    | 103       | 7.8%    |
| 2015    | 89        | 6.74%   |
| 2013    | 73        | 5.53%   |
| 2011    | 70        | 5.3%    |
| 2012    | 64        | 4.85%   |
| 2014    | 62        | 4.7%    |
| 2010    | 60        | 4.55%   |
| 2022    | 50        | 3.79%   |
| 2016    | 49        | 3.71%   |
| 2008    | 36        | 2.73%   |
| 2023    | 33        | 2.5%    |
| 2007    | 32        | 2.42%   |
| 2009    | 29        | 2.2%    |
| 2006    | 13        | 0.98%   |
| 2024    | 2         | 0.15%   |
| Unknown | 2         | 0.15%   |
| 2005    | 1         | 0.08%   |
| 2004    | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1320      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1242      | 93.38%  |
| Enabled  | 88        | 6.62%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1315      | 99.62%  |
| Yes  | 5         | 0.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 378       | 28.21%  |
| 4.01-8.0    | 368       | 27.46%  |
| 8.01-16.0   | 223       | 16.64%  |
| 16.01-24.0  | 198       | 14.78%  |
| 32.01-64.0  | 73        | 5.45%   |
| 1.01-2.0    | 51        | 3.81%   |
| 24.01-32.0  | 16        | 1.19%   |
| 2.01-3.0    | 14        | 1.04%   |
| 0.51-1.0    | 10        | 0.75%   |
| 64.01-256.0 | 9         | 0.67%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 542       | 36.75%  |
| 2.01-3.0   | 392       | 26.58%  |
| 3.01-4.0   | 178       | 12.07%  |
| 4.01-8.0   | 166       | 11.25%  |
| 0.51-1.0   | 133       | 9.02%   |
| 8.01-16.0  | 46        | 3.12%   |
| 0.01-0.5   | 13        | 0.88%   |
| 24.01-32.0 | 3         | 0.2%    |
| 32.01-64.0 | 1         | 0.07%   |
| 16.01-24.0 | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1018      | 75.74%  |
| 2      | 277       | 20.61%  |
| 3      | 40        | 2.98%   |
| 0      | 6         | 0.45%   |
| 4      | 2         | 0.15%   |
| 5      | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 872       | 65.66%  |
| Yes       | 456       | 34.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 995       | 75.09%  |
| No        | 330       | 24.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1308      | 98.94%  |
| No        | 14        | 1.06%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1085      | 81.15%  |
| No        | 252       | 18.85%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Romania | 1320      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Bucharest             | 432       | 30.7%   |
| Cluj-Napoca           | 88        | 6.25%   |
| Iasi                  | 65        | 4.62%   |
| Timișoara            | 52        | 3.7%    |
| Târgu Mureş         | 40        | 2.84%   |
| Ploieşti             | 40        | 2.84%   |
| Brasov                | 39        | 2.77%   |
| Constanța            | 30        | 2.13%   |
| Sibiu                 | 25        | 1.78%   |
| Piteşti              | 22        | 1.56%   |
| Oradea                | 19        | 1.35%   |
| Arad                  | 19        | 1.35%   |
| Craiova               | 18        | 1.28%   |
| Popesti-Leordeni      | 15        | 1.07%   |
| Galati                | 14        | 1%      |
| Voluntari             | 13        | 0.92%   |
| Râmnicu Vâlcea      | 13        | 0.92%   |
| Baia Mare             | 13        | 0.92%   |
| Botosani              | 12        | 0.85%   |
| Bacau                 | 12        | 0.85%   |
| Miercurea-Ciuc        | 11        | 0.78%   |
| Deva                  | 10        | 0.71%   |
| Zalău                | 9         | 0.64%   |
| Targoviste            | 9         | 0.64%   |
| Tulcea                | 8         | 0.57%   |
| Roman                 | 8         | 0.57%   |
| Reşiţa              | 8         | 0.57%   |
| Mediaş               | 8         | 0.57%   |
| Focşani              | 8         | 0.57%   |
| Floresti              | 8         | 0.57%   |
| Buzau                 | 8         | 0.57%   |
| Alba Iulia            | 8         | 0.57%   |
| Suceava               | 7         | 0.5%    |
| Mangalia              | 7         | 0.5%    |
| Braila                | 7         | 0.5%    |
| Târgu Jiu            | 6         | 0.43%   |
| Slatina               | 6         | 0.43%   |
| Sighetu Marmaţiei    | 6         | 0.43%   |
| Drobeta-Turnu Severin | 6         | 0.43%   |
| Sfantu Gheorghe       | 5         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 231       | 305    | 14.15%  |
| Seagate                     | 188       | 253    | 11.51%  |
| WDC                         | 174       | 204    | 10.66%  |
| Kingston                    | 165       | 203    | 10.1%   |
| Toshiba                     | 133       | 162    | 8.14%   |
| SanDisk                     | 92        | 107    | 5.63%   |
| SK hynix                    | 79        | 106    | 4.84%   |
| Unknown                     | 75        | 97     | 4.59%   |
| Intel                       | 73        | 96     | 4.47%   |
| Micron Technology           | 56        | 75     | 3.43%   |
| A-DATA Technology           | 55        | 61     | 3.37%   |
| HGST                        | 52        | 62     | 3.18%   |
| Hitachi                     | 37        | 40     | 2.27%   |
| Crucial                     | 17        | 22     | 1.04%   |
| KIOXIA                      | 16        | 16     | 0.98%   |
| Kingston Technology Company | 13        | 15     | 0.8%    |
| Phison                      | 10        | 11     | 0.61%   |
| Patriot                     | 10        | 10     | 0.61%   |
| Netac                       | 9         | 11     | 0.55%   |
| FORESEE                     | 9         | 10     | 0.55%   |
| SPCC                        | 8         | 9      | 0.49%   |
| Fujitsu                     | 8         | 9      | 0.49%   |
| Hewlett-Packard             | 7         | 7      | 0.43%   |
| Corsair                     | 6         | 7      | 0.37%   |
| Realtek Semiconductor       | 5         | 5      | 0.31%   |
| Phison Electronics          | 5         | 5      | 0.31%   |
| Unknown                     | 5         | 5      | 0.31%   |
| XPG                         | 4         | 5      | 0.24%   |
| OCZ                         | 4         | 6      | 0.24%   |
| LITEON                      | 4         | 4      | 0.24%   |
| Gigabyte Technology         | 4         | 4      | 0.24%   |
| China                       | 4         | 4      | 0.24%   |
| ADATA Technology            | 4         | 5      | 0.24%   |
| Transcend                   | 3         | 4      | 0.18%   |
| Silicon Motion              | 3         | 3      | 0.18%   |
| GOODRAM                     | 3         | 3      | 0.18%   |
| ASMT                        | 3         | 3      | 0.18%   |
| Apple                       | 3         | 3      | 0.18%   |
| XrayDisk                    | 2         | 2      | 0.12%   |
| Verbatim                    | 2         | 2      | 0.12%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABF050 500GB                           | 47        | 2.79%   |
| Seagate ST1000LM035-1RK172 1TB                     | 42        | 2.49%   |
| Kingston SA400S37240G 240GB SSD                    | 31        | 1.84%   |
| Seagate ST500LT012-1DG142 500GB                    | 30        | 1.78%   |
| Toshiba MQ04ABF100 1TB                             | 22        | 1.31%   |
| Unknown MMC Card  32GB                             | 21        | 1.25%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 21        | 1.25%   |
| Kingston SA400S37480G 480GB SSD                    | 20        | 1.19%   |
| HGST HTS721010A9E630 1TB                           | 20        | 1.19%   |
| SanDisk NVMe SSD Drive 512GB                       | 17        | 1.01%   |
| SanDisk NVMe SSD Drive 256GB                       | 17        | 1.01%   |
| Samsung NVMe SSD Drive 512GB                       | 17        | 1.01%   |
| Toshiba MQ01ABD100 1TB                             | 14        | 0.83%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 13        | 0.77%   |
| SK hynix NVMe SSD Drive 512GB                      | 11        | 0.65%   |
| SK hynix HFS256G39TND-N210A 256GB SSD              | 11        | 0.65%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 11        | 0.65%   |
| Kingston SV300S37A240G 240GB SSD                   | 11        | 0.65%   |
| HGST HTS545050A7E680 500GB                         | 11        | 0.65%   |
| Intel NVMe SSD Drive 512GB                         | 10        | 0.59%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 9         | 0.53%   |
| SK hynix HFM001TD3JX013N 1024GB                    | 9         | 0.53%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 9         | 0.53%   |
| HGST HTS541010A9E680 1TB                           | 9         | 0.53%   |
| Seagate Expansion 2TB                              | 8         | 0.47%   |
| Samsung SSD 860 EVO 500GB                          | 8         | 0.47%   |
| Netac SSD 256GB                                    | 8         | 0.47%   |
| Kingston SUV500MS480G 480GB SSD                    | 8         | 0.47%   |
| Kingston SA400S37120G 120GB SSD                    | 8         | 0.47%   |
| Kingston RBUSNS8180DS3256GJ 256GB SSD              | 8         | 0.47%   |
| A-DATA SU650 240GB SSD                             | 8         | 0.47%   |
| WDC WD10JPCX-24UE4T0 1TB                           | 7         | 0.42%   |
| Unknown MMC Card  64GB                             | 7         | 0.42%   |
| Unknown MMC Card  128GB                            | 7         | 0.42%   |
| Seagate ST9500325AS 500GB                          | 7         | 0.42%   |
| Seagate ST2000LM007-1R8174 2TB                     | 7         | 0.42%   |
| Sandisk WD Blue SN550 NVMe SSD 2TB                 | 7         | 0.42%   |
| Samsung SSD 870 EVO 1TB                            | 7         | 0.42%   |
| Samsung SSD 850 EVO 250GB                          | 7         | 0.42%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                | 7         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 186       | 251    | 35.23%  |
| WDC                 | 119       | 141    | 22.54%  |
| Toshiba             | 109       | 134    | 20.64%  |
| HGST                | 52        | 62     | 9.85%   |
| Hitachi             | 37        | 40     | 7.01%   |
| Fujitsu             | 8         | 9      | 1.52%   |
| Samsung Electronics | 5         | 6      | 0.95%   |
| Unknown             | 3         | 3      | 0.57%   |
| TO Exter            | 2         | 4      | 0.38%   |
| IBM/Hitachi         | 2         | 2      | 0.38%   |
| XrayDisk            | 1         | 1      | 0.19%   |
| SABRENT             | 1         | 1      | 0.19%   |
| HGST HTS            | 1         | 1      | 0.19%   |
| ASMT                | 1         | 1      | 0.19%   |
| Apple               | 1         | 1      | 0.19%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 140       | 176    | 27.56%  |
| Samsung Electronics | 84        | 116    | 16.54%  |
| A-DATA Technology   | 48        | 54     | 9.45%   |
| SanDisk             | 33        | 40     | 6.5%    |
| SK hynix            | 23        | 32     | 4.53%   |
| Micron Technology   | 21        | 25     | 4.13%   |
| Crucial             | 17        | 22     | 3.35%   |
| WDC                 | 15        | 15     | 2.95%   |
| Intel               | 14        | 15     | 2.76%   |
| Patriot             | 9         | 9      | 1.77%   |
| Netac               | 9         | 11     | 1.77%   |
| FORESEE             | 9         | 10     | 1.77%   |
| SPCC                | 8         | 9      | 1.57%   |
| Toshiba             | 7         | 7      | 1.38%   |
| Hewlett-Packard     | 7         | 7      | 1.38%   |
| Corsair             | 5         | 6      | 0.98%   |
| OCZ                 | 4         | 6      | 0.79%   |
| LITEON              | 4         | 4      | 0.79%   |
| Gigabyte Technology | 4         | 4      | 0.79%   |
| China               | 4         | 4      | 0.79%   |
| Transcend           | 3         | 4      | 0.59%   |
| GOODRAM             | 3         | 3      | 0.59%   |
| Verbatim            | 2         | 2      | 0.39%   |
| Teclast             | 2         | 2      | 0.39%   |
| LITEONIT            | 2         | 2      | 0.39%   |
| Lite-On             | 2         | 2      | 0.39%   |
| Kingmax             | 2         | 2      | 0.39%   |
| Intenso             | 2         | 2      | 0.39%   |
| ASMT                | 2         | 2      | 0.39%   |
| Apacer              | 2         | 2      | 0.39%   |
| XrayDisk            | 1         | 1      | 0.2%    |
| Wibtek              | 1         | 1      | 0.2%    |
| W800S               | 1         | 1      | 0.2%    |
| Unknown             | 1         | 1      | 0.2%    |
| sobetter            | 1         | 1      | 0.2%    |
| PNY                 | 1         | 2      | 0.2%    |
| Plextor             | 1         | 2      | 0.2%    |
| MicroFrom           | 1         | 1      | 0.2%    |
| Maxtor              | 1         | 1      | 0.2%    |
| M.2 2280            | 1         | 1      | 0.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 514       | 657    | 33.16%  |
| NVMe    | 486       | 640    | 31.35%  |
| SSD     | 471       | 619    | 30.39%  |
| MMC     | 69        | 91     | 4.45%   |
| Unknown | 10        | 12     | 0.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 860       | 1233   | 58.7%   |
| NVMe | 486       | 639    | 33.17%  |
| MMC  | 69        | 91     | 4.71%   |
| SAS  | 50        | 56     | 3.41%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 659       | 881    | 68.5%   |
| 0.51-1.0   | 268       | 335    | 27.86%  |
| 1.01-2.0   | 32        | 57     | 3.33%   |
| 3.01-4.0   | 1         | 1      | 0.1%    |
| 10.01-20.0 | 1         | 1      | 0.1%    |
| 4.01-10.0  | 1         | 1      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 409       | 29.13%  |
| 251-500        | 342       | 24.36%  |
| 501-1000       | 233       | 16.6%   |
| 1-20           | 123       | 8.76%   |
| 51-100         | 86        | 6.13%   |
| 1001-2000      | 71        | 5.06%   |
| 21-50          | 61        | 4.34%   |
| Unknown        | 39        | 2.78%   |
| 2001-3000      | 23        | 1.64%   |
| More than 3000 | 17        | 1.21%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 570       | 39.23%  |
| 21-50          | 328       | 22.57%  |
| 101-250        | 177       | 12.18%  |
| 51-100         | 160       | 11.01%  |
| 251-500        | 85        | 5.85%   |
| 501-1000       | 64        | 4.4%    |
| Unknown        | 39        | 2.68%   |
| 1001-2000      | 25        | 1.72%   |
| More than 3000 | 3         | 0.21%   |
| 2001-3000      | 2         | 0.14%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Hitachi HTS725032A7E630 320GB            | 7         | 7      | 7.37%   |
| HGST HTS541010A9E680 1TB                 | 5         | 5      | 5.26%   |
| Seagate ST9500420AS 500GB                | 3         | 3      | 3.16%   |
| HGST HTS545050A7E680 500GB               | 3         | 3      | 3.16%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB SSD | 2         | 2      | 2.11%   |
| Toshiba MQ01ABF050 500GB                 | 2         | 2      | 2.11%   |
| Seagate ST95005620AS 500GB               | 2         | 5      | 2.11%   |
| Seagate ST9500325AS 500GB                | 2         | 2      | 2.11%   |
| Seagate ST9160821AS 160GB                | 2         | 2      | 2.11%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 3      | 2.11%   |
| Seagate ST500LM000-1EJ162 500GB          | 2         | 3      | 2.11%   |
| Seagate ST1000LX015-1U7172 1TB           | 2         | 2      | 2.11%   |
| Hitachi HTS545016B9A300 160GB            | 2         | 2      | 2.11%   |
| HGST HTS725050A7E630 500GB               | 2         | 2      | 2.11%   |
| XrayDisk 240GB SSD                       | 1         | 1      | 1.05%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 1.05%   |
| WDC WD7500BPVT-60HXZT3 752GB             | 1         | 2      | 1.05%   |
| WDC WD7500BPVT-22HXZT3 752GB             | 1         | 1      | 1.05%   |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 1.05%   |
| WDC WD5000BPKT-60PK4T0 500GB             | 1         | 2      | 1.05%   |
| WDC WD5000BEVT-60A0RT0 500GB             | 1         | 1      | 1.05%   |
| WDC WD3200BPVT-22JJ5T0 320GB             | 1         | 1      | 1.05%   |
| WDC WD1600BEVS-60RST0 160GB              | 1         | 1      | 1.05%   |
| WDC WD1600BEVS-07RST0 160GB              | 1         | 1      | 1.05%   |
| WDC WD10SPZX-21Z10T0 1TB                 | 1         | 1      | 1.05%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 1.05%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1      | 1.05%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 1      | 1.05%   |
| Toshiba MK6476GSX 640GB                  | 1         | 1      | 1.05%   |
| Toshiba MK5076GSX 500GB                  | 1         | 1      | 1.05%   |
| Toshiba MK3252GSX 320GB                  | 1         | 2      | 1.05%   |
| Toshiba MK2556GSY 250GB                  | 1         | 1      | 1.05%   |
| Toshiba MK2035GSS 200GB                  | 1         | 1      | 1.05%   |
| Teclast 360GB A850 SSD                   | 1         | 1      | 1.05%   |
| SK hynix SC210 2.5 7MM 256GB SSD         | 1         | 1      | 1.05%   |
| SK hynix HFS256G3BTND-N210A 256GB SSD    | 1         | 1      | 1.05%   |
| SK hynix HFS256G39TND-N210A 256GB SSD    | 1         | 1      | 1.05%   |
| SK hynix HFS256G39MND-2300A 256GB SSD    | 1         | 1      | 1.05%   |
| SK hynix HFS128G39TND-N210A 128GB SSD    | 1         | 1      | 1.05%   |
| SK hynix HFS128G32TND-N210A 128GB SSD    | 1         | 1      | 1.05%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 26     | 22.58%  |
| Hitachi             | 16        | 18     | 17.2%   |
| WDC                 | 13        | 15     | 13.98%  |
| HGST                | 12        | 12     | 12.9%   |
| Toshiba             | 9         | 10     | 9.68%   |
| SK hynix            | 6         | 6      | 6.45%   |
| Kingston            | 3         | 3      | 3.23%   |
| Fujitsu             | 3         | 3      | 3.23%   |
| Hewlett-Packard     | 2         | 2      | 2.15%   |
| XrayDisk            | 1         | 1      | 1.08%   |
| Teclast             | 1         | 1      | 1.08%   |
| SanDisk             | 1         | 1      | 1.08%   |
| Samsung Electronics | 1         | 1      | 1.08%   |
| Patriot             | 1         | 1      | 1.08%   |
| Micron Technology   | 1         | 1      | 1.08%   |
| LITEONIT            | 1         | 1      | 1.08%   |
| Intel               | 1         | 1      | 1.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 21        | 26     | 29.58%  |
| Hitachi | 16        | 18     | 22.54%  |
| HGST    | 12        | 12     | 16.9%   |
| WDC     | 10        | 12     | 14.08%  |
| Toshiba | 9         | 10     | 12.68%  |
| Fujitsu | 3         | 3      | 4.23%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 71        | 81     | 76.34%  |
| SSD  | 22        | 22     | 23.66%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                        | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD3200BEKT-60KA9T0 320GB | 1         | 1      | 50%     |
| WDC WD2500BEVS-22UST0 250GB  | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor | Notebooks | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 851       | 1260   | 60.27%  |
| Works    | 466       | 654    | 33%     |
| Malfunc  | 93        | 103    | 6.59%   |
| Failed   | 2         | 2      | 0.14%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 981       | 61.43%  |
| Samsung Electronics              | 150       | 9.39%   |
| AMD                              | 142       | 8.89%   |
| SanDisk                          | 97        | 6.07%   |
| SK hynix                         | 55        | 3.44%   |
| Kingston Technology Company      | 39        | 2.44%   |
| Micron Technology                | 35        | 2.19%   |
| KIOXIA                           | 18        | 1.13%   |
| Toshiba America Info Systems     | 17        | 1.06%   |
| Phison Electronics               | 14        | 0.88%   |
| ADATA Technology                 | 12        | 0.75%   |
| Realtek Semiconductor            | 9         | 0.56%   |
| Silicon Integrated Systems [SiS] | 5         | 0.31%   |
| Silicon Motion                   | 4         | 0.25%   |
| Solidigm                         | 3         | 0.19%   |
| Nvidia                           | 3         | 0.19%   |
| Union Memory (Shenzhen)          | 2         | 0.13%   |
| Solid State Storage Technology   | 2         | 0.13%   |
| Lenovo                           | 2         | 0.13%   |
| JMicron Technology               | 2         | 0.13%   |
| VIA Technologies                 | 1         | 0.06%   |
| Silicon Image                    | 1         | 0.06%   |
| Seagate Technology               | 1         | 0.06%   |
| Micron/Crucial Technology        | 1         | 0.06%   |
| Lite-On Technology               | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 125       | 7.23%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 115       | 6.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 92        | 5.32%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 71        | 4.1%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 66        | 3.82%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 64        | 3.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 54        | 3.12%   |
| Intel Volume Management Device NVMe RAID Controller                              | 53        | 3.06%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 51        | 2.95%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 48        | 2.77%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 44        | 2.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 40        | 2.31%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 39        | 2.25%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 37        | 2.14%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 34        | 1.97%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 31        | 1.79%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 28        | 1.62%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                        | 27        | 1.56%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 26        | 1.5%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 25        | 1.45%   |
| SanDisk WD Blue SN500 / PC SN520 x2 M.2 2280 NVMe SSD                            | 23        | 1.33%   |
| Intel SSD 660P Series                                                            | 23        | 1.33%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 23        | 1.33%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 23        | 1.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 22        | 1.27%   |
| Intel Tiger Lake-LP SATA Controller                                              | 22        | 1.27%   |
| Intel Comet Lake SATA AHCI Controller                                            | 18        | 1.04%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 18        | 1.04%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 16        | 0.92%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 15        | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 14        | 0.81%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                    | 13        | 0.75%   |
| Micron 2210 NVMe SSD [Cobain]                                                    | 12        | 0.69%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 11        | 0.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 11        | 0.64%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                    | 10        | 0.58%   |
| Intel 82801G (ICH7 Family) IDE Controller                                        | 10        | 0.58%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                            | 9         | 0.52%   |
| Kingston Company OM3PDP3 NVMe SSD                                                | 9         | 0.52%   |
| Intel SSD DC P4101/Pro 7600p/760p/E 6100p Series                                 | 9         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 937       | 56.38%  |
| NVMe | 489       | 29.42%  |
| RAID | 152       | 9.15%   |
| IDE  | 84        | 5.05%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 1082      | 81.97%  |
| AMD    | 237       | 17.95%  |
| ARM    | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4000 CPU @ 1.10GHz             | 44        | 3.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 30        | 2.27%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 26        | 1.97%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 24        | 1.82%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 22        | 1.66%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 18        | 1.36%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 1.29%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 17        | 1.29%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 17        | 1.29%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 16        | 1.21%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 16        | 1.21%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 16        | 1.21%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 15        | 1.13%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 14        | 1.06%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 14        | 1.06%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 13        | 0.98%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 13        | 0.98%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 12        | 0.91%   |
| Intel Core i3-7100U CPU @ 2.40GHz             | 12        | 0.91%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 11        | 0.83%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 10        | 0.76%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 10        | 0.76%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 10        | 0.76%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 10        | 0.76%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 10        | 0.76%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 10        | 0.76%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz            | 9         | 0.68%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 9         | 0.68%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 9         | 0.68%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 9         | 0.68%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 9         | 0.68%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 8         | 0.61%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 8         | 0.61%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 8         | 0.61%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 8         | 0.61%   |
| Intel Core i5 CPU M 560 @ 2.67GHz             | 8         | 0.61%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 8         | 0.61%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 8         | 0.61%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 8         | 0.61%   |
| AMD Ryzen 3 3250U with Radeon Graphics        | 8         | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i7                  | 293       | 22.16%  |
| Intel Core i5                  | 254       | 19.21%  |
| Intel Core i3                  | 140       | 10.59%  |
| Intel Celeron                  | 135       | 10.21%  |
| Other                          | 117       | 8.85%   |
| AMD Ryzen 7                    | 64        | 4.84%   |
| AMD Ryzen 5                    | 60        | 4.54%   |
| Intel Core 2 Duo               | 47        | 3.56%   |
| Intel Pentium                  | 42        | 3.18%   |
| AMD Ryzen 3                    | 19        | 1.44%   |
| Intel Atom                     | 18        | 1.36%   |
| AMD Ryzen 9                    | 13        | 0.98%   |
| Intel Pentium Dual-Core        | 10        | 0.76%   |
| AMD A4                         | 10        | 0.76%   |
| Intel Genuine                  | 8         | 0.61%   |
| AMD Ryzen 7 PRO                | 8         | 0.61%   |
| Intel Core 2                   | 7         | 0.53%   |
| AMD E                          | 6         | 0.45%   |
| AMD A6                         | 6         | 0.45%   |
| Intel Pentium Dual             | 5         | 0.38%   |
| Intel Core i9                  | 5         | 0.38%   |
| AMD E2                         | 5         | 0.38%   |
| Intel Celeron M                | 4         | 0.3%    |
| AMD Athlon                     | 4         | 0.3%    |
| Intel Pentium Silver           | 3         | 0.23%   |
| AMD Turion 64 X2 Mobile        | 3         | 0.23%   |
| AMD A8                         | 3         | 0.23%   |
| AMD A10                        | 3         | 0.23%   |
| Intel Core m5                  | 2         | 0.15%   |
| Intel Core Duo                 | 2         | 0.15%   |
| Intel Celeron Dual-Core        | 2         | 0.15%   |
| AMD V140                       | 2         | 0.15%   |
| AMD Turion X2 Dual-Core Mobile | 2         | 0.15%   |
| AMD Ryzen 5 PRO                | 2         | 0.15%   |
| AMD FX                         | 2         | 0.15%   |
| AMD E1                         | 2         | 0.15%   |
| Intel Xeon                     | 1         | 0.08%   |
| Intel Pentium M                | 1         | 0.08%   |
| Intel Mobile Pentium 4         | 1         | 0.08%   |
| Intel Core 2 Extreme           | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 660       | 49.92%  |
| 4      | 409       | 30.94%  |
| 6      | 98        | 7.41%   |
| 8      | 97        | 7.34%   |
| 1      | 24        | 1.82%   |
| 10     | 14        | 1.06%   |
| 14     | 9         | 0.68%   |
| 12     | 6         | 0.45%   |
| 16     | 3         | 0.23%   |
| 24     | 2         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1320      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 965       | 73%     |
| 1      | 356       | 26.93%  |
| 4      | 1         | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1244      | 93.89%  |
| Unknown        | 67        | 5.06%   |
| 32-bit         | 14        | 1.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 377       | 27.58%  |
| 0x206a7    | 57        | 4.17%   |
| 0x806ea    | 55        | 4.02%   |
| 0x806ec    | 54        | 3.95%   |
| 0x306a9    | 53        | 3.88%   |
| 0x706a1    | 47        | 3.44%   |
| 0x40651    | 39        | 2.85%   |
| 0x306c3    | 38        | 2.78%   |
| 0x906ea    | 34        | 2.49%   |
| 0x806c1    | 33        | 2.41%   |
| 0x806e9    | 31        | 2.27%   |
| 0x506c9    | 30        | 2.19%   |
| 0x306d4    | 30        | 2.19%   |
| 0x1067a    | 28        | 2.05%   |
| 0x20655    | 27        | 1.98%   |
| 0x406e3    | 23        | 1.68%   |
| 0x0a50000c | 22        | 1.61%   |
| 0x806eb    | 21        | 1.54%   |
| 0x08108109 | 21        | 1.54%   |
| 0x906e9    | 20        | 1.46%   |
| 0x08108102 | 18        | 1.32%   |
| 0x706e5    | 17        | 1.24%   |
| 0x08600106 | 16        | 1.17%   |
| 0xa0652    | 13        | 0.95%   |
| 0x506e3    | 13        | 0.95%   |
| 0x08600104 | 13        | 0.95%   |
| 0x6fd      | 12        | 0.88%   |
| 0x10676    | 12        | 0.88%   |
| 0x406c3    | 11        | 0.8%    |
| 0x806d1    | 10        | 0.73%   |
| 0x906ed    | 9         | 0.66%   |
| 0x406c4    | 9         | 0.66%   |
| 0x20652    | 9         | 0.66%   |
| 0x706a8    | 8         | 0.59%   |
| 0x906a4    | 7         | 0.51%   |
| 0x906a3    | 7         | 0.51%   |
| 0x106ca    | 7         | 0.51%   |
| 0x06006705 | 7         | 0.51%   |
| 0x6e8      | 6         | 0.44%   |
| 0x30678    | 6         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 289       | 21.83%  |
| Haswell           | 105       | 7.93%   |
| SandyBridge       | 73        | 5.51%   |
| IvyBridge         | 68        | 5.14%   |
| Goldmont plus     | 65        | 4.91%   |
| Unknown           | 57        | 4.31%   |
| Westmere          | 54        | 4.08%   |
| Skylake           | 53        | 4%      |
| TigerLake         | 47        | 3.55%   |
| Zen+              | 46        | 3.47%   |
| Penryn            | 43        | 3.25%   |
| Broadwell         | 42        | 3.17%   |
| Zen 2             | 41        | 3.1%    |
| Zen 3             | 38        | 2.87%   |
| Silvermont        | 37        | 2.79%   |
| Goldmont          | 37        | 2.79%   |
| Core              | 36        | 2.72%   |
| Icelake           | 35        | 2.64%   |
| Alderlake Hybrid  | 31        | 2.34%   |
| CometLake         | 22        | 1.66%   |
| Excavator         | 19        | 1.44%   |
| Zen               | 15        | 1.13%   |
| P6                | 12        | 0.91%   |
| Bonnell           | 10        | 0.76%   |
| Bobcat            | 8         | 0.6%    |
| Puma              | 7         | 0.53%   |
| Tremont           | 5         | 0.38%   |
| K8 Hammer         | 5         | 0.38%   |
| K8 & K10 hybrid   | 4         | 0.3%    |
| K10               | 4         | 0.3%    |
| Jaguar            | 4         | 0.3%    |
| Piledriver        | 3         | 0.23%   |
| Nehalem           | 3         | 0.23%   |
| K10 Llano         | 3         | 0.23%   |
| Steamroller       | 1         | 0.08%   |
| NetBurst          | 1         | 0.08%   |
| Meteorlake Hybrid | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1002      | 57.26%  |
| Nvidia                           | 425       | 24.29%  |
| AMD                              | 317       | 18.11%  |
| Silicon Integrated Systems [SiS] | 5         | 0.29%   |
| VIA Technologies                 | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 67        | 3.73%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 64        | 3.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 63        | 3.51%   |
| Intel UHD Graphics 620                                                                   | 62        | 3.45%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 59        | 3.28%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 54        | 3.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 51        | 2.84%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 49        | 2.73%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 47        | 2.62%   |
| Intel HD Graphics 620                                                                    | 44        | 2.45%   |
| Intel Core Processor Integrated Graphics Controller                                      | 41        | 2.28%   |
| Intel HD Graphics 5500                                                                   | 40        | 2.23%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 37        | 2.06%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 33        | 1.84%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 29        | 1.61%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 28        | 1.56%   |
| Intel HD Graphics 500                                                                    | 27        | 1.5%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 26        | 1.45%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 24        | 1.34%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 24        | 1.34%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 23        | 1.28%   |
| Intel HD Graphics 630                                                                    | 23        | 1.28%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 21        | 1.17%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 19        | 1.06%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 18        | 1%      |
| Intel HD Graphics 530                                                                    | 18        | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 17        | 0.95%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 17        | 0.95%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 17        | 0.95%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 15        | 0.83%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 15        | 0.83%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 15        | 0.83%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 15        | 0.83%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 14        | 0.78%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 14        | 0.78%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 14        | 0.78%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 14        | 0.78%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 14        | 0.78%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 14        | 0.78%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 14        | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 618       | 46.75%  |
| Intel + Nvidia | 322       | 24.36%  |
| 1 x AMD        | 192       | 14.52%  |
| Intel + AMD    | 59        | 4.46%   |
| 1 x Nvidia     | 55        | 4.16%   |
| AMD + Nvidia   | 48        | 3.63%   |
| 2 x AMD        | 18        | 1.36%   |
| 1 x SiS        | 5         | 0.38%   |
| Other          | 2         | 0.15%   |
| 2 x Intel      | 2         | 0.15%   |
| 1 x VIA        | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1064      | 79.7%   |
| Proprietary | 246       | 18.43%  |
| Unknown     | 25        | 1.87%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 839       | 61.78%  |
| 1.01-2.0   | 181       | 13.33%  |
| 0.01-0.5   | 156       | 11.49%  |
| 3.01-4.0   | 91        | 6.7%    |
| 0.51-1.0   | 53        | 3.9%    |
| 5.01-6.0   | 23        | 1.69%   |
| 7.01-8.0   | 9         | 0.66%   |
| 2.01-3.0   | 5         | 0.37%   |
| 0          | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 262       | 18.23%  |
| BOE                     | 237       | 16.49%  |
| Chimei Innolux          | 236       | 16.42%  |
| LG Display              | 199       | 13.85%  |
| Samsung Electronics     | 136       | 9.46%   |
| PANDA                   | 55        | 3.83%   |
| Dell                    | 47        | 3.27%   |
| Chi Mei Optoelectronics | 38        | 2.64%   |
| Sharp                   | 31        | 2.16%   |
| Lenovo                  | 22        | 1.53%   |
| Goldstar                | 22        | 1.53%   |
| LG Philips              | 16        | 1.11%   |
| BenQ                    | 13        | 0.9%    |
| CSO                     | 11        | 0.77%   |
| Philips                 | 10        | 0.7%    |
| Acer                    | 10        | 0.7%    |
| InfoVision              | 8         | 0.56%   |
| Hewlett-Packard         | 7         | 0.49%   |
| Apple                   | 7         | 0.49%   |
| AOC                     | 7         | 0.49%   |
| Ancor Communications    | 5         | 0.35%   |
| Valve                   | 4         | 0.28%   |
| LGD                     | 4         | 0.28%   |
| InnoLux Display         | 4         | 0.28%   |
| Fujitsu Siemens         | 4         | 0.28%   |
| CPT                     | 4         | 0.28%   |
| Vestel Elektronik       | 3         | 0.21%   |
| Sony                    | 3         | 0.21%   |
| Lenovo Group Limited    | 3         | 0.21%   |
| ASUSTek Computer        | 3         | 0.21%   |
| Analogix                | 3         | 0.21%   |
| Quanta Display          | 2         | 0.14%   |
| ITE                     | 2         | 0.14%   |
| HannStar                | 2         | 0.14%   |
| ViewSonic               | 1         | 0.07%   |
| Toshiba                 | 1         | 0.07%   |
| TMX                     | 1         | 0.07%   |
| Seiko/Epson             | 1         | 0.07%   |
| Panasonic               | 1         | 0.07%   |
| Nvidia                  | 1         | 0.07%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 27        | 1.86%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 26        | 1.79%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 23        | 1.59%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 21        | 1.45%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 17        | 1.17%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 15        | 1.03%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 12        | 0.83%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 12        | 0.83%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.83%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 11        | 0.76%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 11        | 0.76%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 11        | 0.76%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 11        | 0.76%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 11        | 0.76%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 11        | 0.76%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 10        | 0.69%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 9         | 0.62%   |
| PANDA LCD Monitor NCP0046 1920x1080 344x194mm 15.5-inch                  | 9         | 0.62%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 9         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 9         | 0.62%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 9         | 0.62%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 8         | 0.55%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 8         | 0.55%   |
| Sharp LCD Monitor SHP13F8 3200x1800 346x194mm 15.6-inch                  | 7         | 0.48%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 7         | 0.48%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 7         | 0.48%   |
| BOE LCD Monitor BOE0718 1920x1080 309x173mm 13.9-inch                    | 7         | 0.48%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 7         | 0.48%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                  | 6         | 0.41%   |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 6         | 0.41%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 0.41%   |
| BOE LCD Monitor BOE07F1 1920x1080 344x193mm 15.5-inch                    | 6         | 0.41%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 6         | 0.41%   |
| BOE LCD Monitor BOE0615 1366x768 309x173mm 13.9-inch                     | 6         | 0.41%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 6         | 0.41%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 5         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch    | 5         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch    | 5         | 0.34%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 5         | 0.34%   |
| PANDA LC133LF2L03 NCP0015 1920x1080 294x165mm 13.3-inch                  | 5         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 647       | 47.47%  |
| 1366x768 (WXGA)    | 403       | 29.57%  |
| 1600x900 (HD+)     | 56        | 4.11%   |
| 1280x800 (WXGA)    | 43        | 3.15%   |
| 3840x2160 (4K)     | 37        | 2.71%   |
| 2560x1440 (QHD)    | 23        | 1.69%   |
| 2560x1600          | 19        | 1.39%   |
| 1920x1200 (WUXGA)  | 18        | 1.32%   |
| 1440x900 (WXGA+)   | 15        | 1.1%    |
| 2880x1800          | 14        | 1.03%   |
| 1680x1050 (WSXGA+) | 12        | 0.88%   |
| 3200x1800 (QHD+)   | 11        | 0.81%   |
| 2560x1080          | 8         | 0.59%   |
| 1024x600           | 8         | 0.59%   |
| 800x1280           | 7         | 0.51%   |
| 2160x1440          | 7         | 0.51%   |
| 1280x1024 (SXGA)   | 7         | 0.51%   |
| 1360x768           | 4         | 0.29%   |
| 3440x1440          | 3         | 0.22%   |
| 3200x2000          | 3         | 0.22%   |
| Unknown            | 3         | 0.22%   |
| 3840x2400          | 2         | 0.15%   |
| 1400x1050          | 2         | 0.15%   |
| 1024x768 (XGA)     | 2         | 0.15%   |
| 3926x1440          | 1         | 0.07%   |
| 3840x1080          | 1         | 0.07%   |
| 3000x2000          | 1         | 0.07%   |
| 2880x1620          | 1         | 0.07%   |
| 2240x1400          | 1         | 0.07%   |
| 2048x1152          | 1         | 0.07%   |
| 1920x1280          | 1         | 0.07%   |
| 1680x945           | 1         | 0.07%   |
| 1280x720 (HD)      | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 780       | 54.55%  |
| 14      | 150       | 10.49%  |
| 13      | 135       | 9.44%   |
| 17      | 101       | 7.06%   |
| 24      | 43        | 3.01%   |
| 27      | 27        | 1.89%   |
| 16      | 26        | 1.82%   |
| 23      | 25        | 1.75%   |
| 21      | 20        | 1.4%    |
| 12      | 19        | 1.33%   |
| Unknown | 16        | 1.12%   |
| 34      | 11        | 0.77%   |
| 11      | 10        | 0.7%    |
| 31      | 8         | 0.56%   |
| 19      | 8         | 0.56%   |
| 10      | 8         | 0.56%   |
| 84      | 6         | 0.42%   |
| 22      | 6         | 0.42%   |
| 32      | 4         | 0.28%   |
| 18      | 4         | 0.28%   |
| 7       | 4         | 0.28%   |
| 54      | 3         | 0.21%   |
| 3       | 3         | 0.21%   |
| 20      | 2         | 0.14%   |
| 8       | 2         | 0.14%   |
| 86      | 1         | 0.07%   |
| 72      | 1         | 0.07%   |
| 58      | 1         | 0.07%   |
| 52      | 1         | 0.07%   |
| 48      | 1         | 0.07%   |
| 47      | 1         | 0.07%   |
| 42      | 1         | 0.07%   |
| 40      | 1         | 0.07%   |
| 25      | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1016      | 71.3%   |
| 351-400     | 124       | 8.7%    |
| 501-600     | 93        | 6.53%   |
| 201-300     | 91        | 6.39%   |
| 401-500     | 35        | 2.46%   |
| Unknown     | 16        | 1.12%   |
| 701-800     | 15        | 1.05%   |
| 601-700     | 9         | 0.63%   |
| 1001-1500   | 8         | 0.56%   |
| 1501-2000   | 7         | 0.49%   |
| 1-100       | 7         | 0.49%   |
| 101-200     | 2         | 0.14%   |
| 801-900     | 1         | 0.07%   |
| 901-1000    | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1135      | 86.38%  |
| 16/10   | 123       | 9.36%   |
| Unknown | 14        | 1.07%   |
| 3/2     | 11        | 0.84%   |
| 21/9    | 11        | 0.84%   |
| 5/4     | 7         | 0.53%   |
| 6/5     | 4         | 0.3%    |
| 4/3     | 4         | 0.3%    |
| 0.67    | 4         | 0.3%    |
| 0.56    | 1         | 0.08%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 783       | 54.76%  |
| 81-90          | 241       | 16.85%  |
| 121-130        | 93        | 6.5%    |
| 201-250        | 77        | 5.38%   |
| 71-80          | 39        | 2.73%   |
| 301-350        | 27        | 1.89%   |
| 351-500        | 23        | 1.61%   |
| 111-120        | 20        | 1.4%    |
| 61-70          | 18        | 1.26%   |
| 151-200        | 16        | 1.12%   |
| Unknown        | 16        | 1.12%   |
| More than 1000 | 14        | 0.98%   |
| 251-300        | 13        | 0.91%   |
| 51-60          | 10        | 0.7%    |
| 1-40           | 9         | 0.63%   |
| 131-140        | 9         | 0.63%   |
| 41-50          | 8         | 0.56%   |
| 91-100         | 6         | 0.42%   |
| 141-150        | 5         | 0.35%   |
| 501-1000       | 3         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 625       | 44.11%  |
| 101-120       | 446       | 31.47%  |
| 51-100        | 198       | 13.97%  |
| 161-240       | 87        | 6.14%   |
| More than 240 | 36        | 2.54%   |
| Unknown       | 16        | 1.13%   |
| 1-50          | 9         | 0.64%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1158      | 85.97%  |
| 2     | 149       | 11.06%  |
| 0     | 23        | 1.71%   |
| 3     | 15        | 1.11%   |
| 4     | 2         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 785       | 38.39%  |
| Intel                                  | 598       | 29.24%  |
| Qualcomm Atheros                       | 284       | 13.89%  |
| Broadcom                               | 118       | 5.77%   |
| MediaTek                               | 68        | 3.33%   |
| TP-Link                                | 28        | 1.37%   |
| Broadcom Limited                       | 22        | 1.08%   |
| Marvell Technology Group               | 17        | 0.83%   |
| Ralink                                 | 16        | 0.78%   |
| Ralink Technology                      | 11        | 0.54%   |
| Huawei Technologies                    | 10        | 0.49%   |
| ASIX Electronics                       | 9         | 0.44%   |
| Samsung Electronics                    | 8         | 0.39%   |
| Xiaomi                                 | 7         | 0.34%   |
| Ericsson Business Mobile Networks      | 7         | 0.34%   |
| Hewlett-Packard                        | 6         | 0.29%   |
| ASUSTek Computer                       | 6         | 0.29%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.2%    |
| Lenovo                                 | 4         | 0.2%    |
| JMicron Technology                     | 4         | 0.2%    |
| ZTE WCDMA Technologies MSM             | 3         | 0.15%   |
| Sierra Wireless                        | 3         | 0.15%   |
| Qualcomm Atheros Communications        | 3         | 0.15%   |
| Google                                 | 3         | 0.15%   |
| D-Link                                 | 3         | 0.15%   |
| Dell                                   | 2         | 0.1%    |
| VIA Technologies                       | 1         | 0.05%   |
| U-Blox                                 | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| Sitecom Europe                         | 1         | 0.05%   |
| Qualcomm                               | 1         | 0.05%   |
| Qcom                                   | 1         | 0.05%   |
| Nvidia                                 | 1         | 0.05%   |
| Motorola PCS                           | 1         | 0.05%   |
| Microsoft                              | 1         | 0.05%   |
| Microchip Technology                   | 1         | 0.05%   |
| FIBOCOM                                | 1         | 0.05%   |
| Edimax Technology                      | 1         | 0.05%   |
| DisplayLink                            | 1         | 0.05%   |
| D-Link System                          | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 432       | 17.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 128       | 5.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 83        | 3.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 76        | 3.13%   |
| Intel Wireless 8265 / 8275                                             | 63        | 2.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 56        | 2.3%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 53        | 2.18%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 50        | 2.06%   |
| Intel Wi-Fi 6 AX200                                                    | 49        | 2.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 40        | 1.64%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 39        | 1.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 39        | 1.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                        | 39        | 1.6%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 35        | 1.44%   |
| Intel Wi-Fi 6 AX201                                                    | 35        | 1.44%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 34        | 1.4%    |
| Intel Wireless 7260                                                    | 32        | 1.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 29        | 1.19%   |
| Intel Wireless 7265                                                    | 28        | 1.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 26        | 1.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 24        | 0.99%   |
| Intel Wireless 8260                                                    | 23        | 0.95%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 22        | 0.9%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 21        | 0.86%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 21        | 0.86%   |
| Broadcom BCM43142 802.11b/g/n                                          | 20        | 0.82%   |
| Intel Wireless 3160                                                    | 19        | 0.78%   |
| Intel 82577LM Gigabit Network Connection                               | 19        | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 19        | 0.78%   |
| Intel Wireless 3165                                                    | 18        | 0.74%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 18        | 0.74%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 17        | 0.7%    |
| Intel Centrino Advanced-N 6200                                         | 17        | 0.7%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 16        | 0.66%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 15        | 0.62%   |
| Intel Ethernet Connection (4) I219-LM                                  | 14        | 0.58%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 14        | 0.58%   |
| Intel Ethernet Connection I217-LM                                      | 13        | 0.53%   |
| Intel Centrino Ultimate-N 6300                                         | 13        | 0.53%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 12        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 573       | 41.86%  |
| Realtek Semiconductor           | 305       | 22.28%  |
| Qualcomm Atheros                | 252       | 18.41%  |
| Broadcom                        | 90        | 6.57%   |
| MediaTek                        | 63        | 4.6%    |
| TP-Link                         | 21        | 1.53%   |
| Ralink                          | 16        | 1.17%   |
| Broadcom Limited                | 14        | 1.02%   |
| Ralink Technology               | 11        | 0.8%    |
| ASUSTek Computer                | 6         | 0.44%   |
| Sierra Wireless                 | 3         | 0.22%   |
| Qualcomm Atheros Communications | 3         | 0.22%   |
| D-Link                          | 3         | 0.22%   |
| Sitecom Europe                  | 1         | 0.07%   |
| Qualcomm                        | 1         | 0.07%   |
| Qcom                            | 1         | 0.07%   |
| Microsoft                       | 1         | 0.07%   |
| FIBOCOM                         | 1         | 0.07%   |
| Edimax Technology               | 1         | 0.07%   |
| D-Link System                   | 1         | 0.07%   |
| Belkin                          | 1         | 0.07%   |
| Accton Technology               | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 83        | 6.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 76        | 5.52%   |
| Intel Wireless 8265 / 8275                                              | 63        | 4.58%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 56        | 4.07%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 53        | 3.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 50        | 3.63%   |
| Intel Wi-Fi 6 AX200                                                     | 49        | 3.56%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 40        | 2.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 39        | 2.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 39        | 2.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 35        | 2.54%   |
| Intel Wi-Fi 6 AX201                                                     | 35        | 2.54%   |
| Intel Wireless 7260                                                     | 32        | 2.33%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 29        | 2.11%   |
| Intel Wireless 7265                                                     | 28        | 2.03%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 26        | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 24        | 1.74%   |
| Intel Wireless 8260                                                     | 23        | 1.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 22        | 1.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 21        | 1.53%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 21        | 1.53%   |
| Broadcom BCM43142 802.11b/g/n                                           | 20        | 1.45%   |
| Intel Wireless 3160                                                     | 19        | 1.38%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 19        | 1.38%   |
| Intel Wireless 3165                                                     | 18        | 1.31%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 18        | 1.31%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 17        | 1.24%   |
| Intel Centrino Advanced-N 6200                                          | 17        | 1.24%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 16        | 1.16%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 15        | 1.09%   |
| Intel Centrino Ultimate-N 6300                                          | 13        | 0.94%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 11        | 0.8%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 10        | 0.73%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 10        | 0.73%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 10        | 0.73%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 10        | 0.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 0.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 9         | 0.65%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 8         | 0.58%   |
| Intel Centrino Advanced-N 6235                                          | 8         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 624       | 60.52%  |
| Intel                                  | 202       | 19.59%  |
| Qualcomm Atheros                       | 65        | 6.3%    |
| Broadcom                               | 49        | 4.75%   |
| Marvell Technology Group               | 17        | 1.65%   |
| ASIX Electronics                       | 9         | 0.87%   |
| Samsung Electronics                    | 8         | 0.78%   |
| Huawei Technologies                    | 8         | 0.78%   |
| Broadcom Limited                       | 8         | 0.78%   |
| Xiaomi                                 | 7         | 0.68%   |
| TP-Link                                | 7         | 0.68%   |
| MediaTek                               | 5         | 0.48%   |
| Silicon Integrated Systems [SiS]       | 4         | 0.39%   |
| Lenovo                                 | 4         | 0.39%   |
| JMicron Technology                     | 4         | 0.39%   |
| Google                                 | 3         | 0.29%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.1%    |
| VIA Technologies                       | 1         | 0.1%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.1%    |
| Nvidia                                 | 1         | 0.1%    |
| Motorola PCS                           | 1         | 0.1%    |
| Hewlett-Packard                        | 1         | 0.1%    |
| DisplayLink                            | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 432       | 41.78%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 128       | 12.38%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 39        | 3.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 34        | 3.29%   |
| Intel 82577LM Gigabit Network Connection                               | 19        | 1.84%   |
| Intel Ethernet Connection (4) I219-LM                                  | 14        | 1.35%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 14        | 1.35%   |
| Intel Ethernet Connection I217-LM                                      | 13        | 1.26%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 12        | 1.16%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 12        | 1.16%   |
| Realtek RTL8125 2.5GbE Controller                                      | 11        | 1.06%   |
| Intel Ethernet Connection I218-LM                                      | 11        | 1.06%   |
| Intel Ethernet Connection (3) I218-LM                                  | 10        | 0.97%   |
| Intel Ethernet Connection (7) I219-LM                                  | 9         | 0.87%   |
| ASIX AX88179 Gigabit Ethernet                                          | 9         | 0.87%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 8         | 0.77%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 8         | 0.77%   |
| Intel Ethernet Connection I219-LM                                      | 8         | 0.77%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 8         | 0.77%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 7         | 0.68%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 7         | 0.68%   |
| Intel 82567LM Gigabit Network Connection                               | 7         | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 6         | 0.58%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 6         | 0.58%   |
| Intel Ethernet Connection (6) I219-V                                   | 6         | 0.58%   |
| Intel Ethernet Connection (13) I219-V                                  | 6         | 0.58%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 6         | 0.58%   |
| Realtek PCIe GbE Family Controller                                     | 5         | 0.48%   |
| Realtek Killer E2600 GbE Controller                                    | 5         | 0.48%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 5         | 0.48%   |
| MediaTek RMX3085                                                       | 5         | 0.48%   |
| Intel Ethernet Connection (4) I219-V                                   | 5         | 0.48%   |
| Huawei VTR-L09                                                         | 5         | 0.48%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 4         | 0.39%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 4         | 0.39%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 4         | 0.39%   |
| Intel PRO/100 VE Network Connection                                    | 4         | 0.39%   |
| Intel Ethernet Connection (7) I219-V                                   | 4         | 0.39%   |
| Intel Ethernet Connection (14) I219-LM                                 | 4         | 0.39%   |
| Intel 82577LC Gigabit Network Connection                               | 4         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1308      | 56.31%  |
| Ethernet | 993       | 42.75%  |
| Modem    | 21        | 0.9%    |
| Unknown  | 1         | 0.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1101      | 79.09%  |
| Ethernet | 291       | 20.91%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 909       | 68.81%  |
| 1     | 383       | 28.99%  |
| 0     | 21        | 1.59%   |
| 3     | 8         | 0.61%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1094      | 81.04%  |
| Yes  | 256       | 18.96%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 449       | 41.15%  |
| IMC Networks                    | 174       | 15.95%  |
| Realtek Semiconductor           | 146       | 13.38%  |
| Qualcomm Atheros Communications | 79        | 7.24%   |
| Lite-On Technology              | 66        | 6.05%   |
| Broadcom                        | 40        | 3.67%   |
| Foxconn / Hon Hai               | 39        | 3.57%   |
| Dell                            | 23        | 2.11%   |
| Hewlett-Packard                 | 16        | 1.47%   |
| Toshiba                         | 15        | 1.37%   |
| Ralink                          | 9         | 0.82%   |
| Cambridge Silicon Radio         | 6         | 0.55%   |
| ASUSTek Computer                | 6         | 0.55%   |
| Apple                           | 5         | 0.46%   |
| Realtek                         | 4         | 0.37%   |
| Alps Electric                   | 3         | 0.27%   |
| USI                             | 2         | 0.18%   |
| Chicony Electronics             | 2         | 0.18%   |
| SINO WEALTH                     | 1         | 0.09%   |
| Ralink Technology               | 1         | 0.09%   |
| Opticis                         | 1         | 0.09%   |
| MediaTek                        | 1         | 0.09%   |
| Foxconn International           | 1         | 0.09%   |
| Askey Computer                  | 1         | 0.09%   |
| Unknown                         | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 110       | 10.08%  |
| IMC Networks Bluetooth Radio                        | 99        | 9.07%   |
| Realtek Bluetooth Radio                             | 97        | 8.89%   |
| Intel AX201 Bluetooth                               | 85        | 7.79%   |
| Intel Bluetooth Device                              | 77        | 7.06%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 76        | 6.97%   |
| Intel AX200 Bluetooth                               | 49        | 4.49%   |
| Qualcomm Atheros  Bluetooth Device                  | 44        | 4.03%   |
| IMC Networks Wireless_Device                        | 35        | 3.21%   |
| IMC Networks Bluetooth Device                       | 32        | 2.93%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 26        | 2.38%   |
| Realtek  Bluetooth 4.2 Adapter                      | 20        | 1.83%   |
| Lite-On Bluetooth Device                            | 13        | 1.19%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 12        | 1.1%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 12        | 1.1%    |
| Intel AX211 Bluetooth                               | 12        | 1.1%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 11        | 1.01%   |
| Foxconn / Hon Hai Wireless_Device                   | 11        | 1.01%   |
| Dell DW375 Bluetooth Module                         | 11        | 1.01%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 10        | 0.92%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 10        | 0.92%   |
| Lite-On Atheros AR3012 Bluetooth                    | 10        | 0.92%   |
| Ralink RT3290 Bluetooth                             | 9         | 0.82%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 0.82%   |
| Toshiba Bluetooth Device                            | 7         | 0.64%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 0.64%   |
| Lite-On Wireless_Device                             | 7         | 0.64%   |
| Intel AX210 Bluetooth                               | 7         | 0.64%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 0.64%   |
| Broadcom BCM2045A0                                  | 7         | 0.64%   |
| Realtek RTL8723B Bluetooth                          | 6         | 0.55%   |
| Realtek 802.11ac WLAN Adapter                       | 6         | 0.55%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 6         | 0.55%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 0.55%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 6         | 0.55%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 0.55%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 0.55%   |
| Broadcom BCM2045B (BDC-2.1)                         | 6         | 0.55%   |
| Dell Wireless 365 Bluetooth                         | 5         | 0.46%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 5         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1070      | 66.34%  |
| AMD                              | 257       | 15.93%  |
| Nvidia                           | 215       | 13.33%  |
| GN Netcom                        | 9         | 0.56%   |
| C-Media Electronics              | 9         | 0.56%   |
| Logitech                         | 6         | 0.37%   |
| Lenovo                           | 6         | 0.37%   |
| Silicon Integrated Systems [SiS] | 5         | 0.31%   |
| Realtek Semiconductor            | 5         | 0.31%   |
| ASUSTek Computer                 | 5         | 0.31%   |
| XMOS                             | 3         | 0.19%   |
| VIA Technologies                 | 2         | 0.12%   |
| Plantronics                      | 2         | 0.12%   |
| Kingston Technology              | 2         | 0.12%   |
| Dell                             | 2         | 0.12%   |
| Creative Technology              | 2         | 0.12%   |
| Unknown                          | 1         | 0.06%   |
| Trust                            | 1         | 0.06%   |
| Sony                             | 1         | 0.06%   |
| Sennheiser Communications        | 1         | 0.06%   |
| Samsung Electronics              | 1         | 0.06%   |
| RME                              | 1         | 0.06%   |
| Razer USA                        | 1         | 0.06%   |
| Hewlett-Packard                  | 1         | 0.06%   |
| Focusrite-Novation               | 1         | 0.06%   |
| FiiO Electronics Technology      | 1         | 0.06%   |
| DSEA A/S                         | 1         | 0.06%   |
| CMX Systems                      | 1         | 0.06%   |
| Bose                             | 1         | 0.06%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 168       | 8.65%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 144       | 7.41%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 81        | 4.17%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 71        | 3.65%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 65        | 3.35%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 64        | 3.29%   |
| Intel Cannon Lake PCH cAVS                                                                        | 61        | 3.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 60        | 3.09%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 57        | 2.93%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 54        | 2.78%   |
| Intel 8 Series HD Audio Controller                                                                | 53        | 2.73%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 53        | 2.73%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 51        | 2.62%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 49        | 2.52%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 47        | 2.42%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 42        | 2.16%   |
| Intel Broadwell-U Audio Controller                                                                | 42        | 2.16%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 37        | 1.9%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 36        | 1.85%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 31        | 1.6%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 30        | 1.54%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 27        | 1.39%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 26        | 1.34%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 26        | 1.34%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 24        | 1.24%   |
| Nvidia Audio device                                                                               | 23        | 1.18%   |
| Intel CM238 HD Audio Controller                                                                   | 23        | 1.18%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 22        | 1.13%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 21        | 1.08%   |
| Intel Comet Lake PCH cAVS                                                                         | 21        | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 21        | 1.08%   |
| AMD FCH Azalia Controller                                                                         | 21        | 1.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 20        | 1.03%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 19        | 0.98%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 19        | 0.98%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 18        | 0.93%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 16        | 0.82%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 16        | 0.82%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 15        | 0.77%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 15        | 0.77%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 238       | 31.61%  |
| SK hynix                     | 162       | 21.51%  |
| Micron Technology            | 96        | 12.75%  |
| Kingston                     | 83        | 11.02%  |
| Unknown                      | 36        | 4.78%   |
| Corsair                      | 23        | 3.05%   |
| Ramaxel Technology           | 21        | 2.79%   |
| A-DATA Technology            | 17        | 2.26%   |
| Elpida                       | 16        | 2.12%   |
| Crucial                      | 16        | 2.12%   |
| Nanya Technology             | 13        | 1.73%   |
| Unknown (ABCD)               | 11        | 1.46%   |
| Kingmax                      | 4         | 0.53%   |
| Transcend                    | 2         | 0.27%   |
| Kingmax Semiconductor        | 2         | 0.27%   |
| Apacer                       | 2         | 0.27%   |
| Unknown                      | 2         | 0.27%   |
| Unknown (0x7FDA000000000000) | 1         | 0.13%   |
| Unknown (0B45)               | 1         | 0.13%   |
| Silicon Power                | 1         | 0.13%   |
| SHARETRONIC                  | 1         | 0.13%   |
| Patriot                      | 1         | 0.13%   |
| KingFast                     | 1         | 0.13%   |
| Infineon                     | 1         | 0.13%   |
| Avant                        | 1         | 0.13%   |
| ASint Technology             | 1         | 0.13%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 17        | 2.1%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 1.48%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 12        | 1.48%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 1.36%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 1.36%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 11        | 1.36%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 11        | 1.36%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 10        | 1.23%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 1.23%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 1.23%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 0.99%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.99%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.99%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 7         | 0.86%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.86%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.86%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.74%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.74%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.74%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.74%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.74%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.62%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2400MT/s           | 5         | 0.62%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.62%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.62%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.62%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.62%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 5         | 0.62%   |
| Micron RAM 16JSF51264HZ-1G4D1 4GB SODIMM DDR3 1334MT/s           | 5         | 0.62%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 4         | 0.49%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 4         | 0.49%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 4         | 0.49%   |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s            | 4         | 0.49%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.49%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.49%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 4         | 0.49%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 0.49%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 4         | 0.49%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 4         | 0.49%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s            | 4         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 315       | 50.4%   |
| DDR3    | 194       | 31.04%  |
| DDR2    | 35        | 5.6%    |
| LPDDR4  | 22        | 3.52%   |
| LPDDR3  | 18        | 2.88%   |
| LPDDR5  | 13        | 2.08%   |
| DDR5    | 12        | 1.92%   |
| SDRAM   | 11        | 1.76%   |
| DRAM    | 2         | 0.32%   |
| Unknown | 2         | 0.32%   |
| DDR     | 1         | 0.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 570       | 90.62%  |
| Row Of Chips | 53        | 8.43%   |
| Chip         | 5         | 0.79%   |
| DIMM         | 1         | 0.16%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 276       | 40.29%  |
| 4096  | 207       | 30.22%  |
| 16384 | 99        | 14.45%  |
| 2048  | 66        | 9.64%   |
| 1024  | 25        | 3.65%   |
| 32768 | 10        | 1.46%   |
| 512   | 2         | 0.29%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 151       | 21.79%  |
| 1600    | 144       | 20.78%  |
| 2667    | 122       | 17.6%   |
| 2400    | 67        | 9.67%   |
| 1334    | 40        | 5.77%   |
| 2133    | 29        | 4.18%   |
| 3266    | 17        | 2.45%   |
| 667     | 14        | 2.02%   |
| 6400    | 12        | 1.73%   |
| 1333    | 12        | 1.73%   |
| Unknown | 11        | 1.59%   |
| 1067    | 10        | 1.44%   |
| 4800    | 9         | 1.3%    |
| 975     | 9         | 1.3%    |
| 800     | 7         | 1.01%   |
| 4199    | 5         | 0.72%   |
| 1867    | 5         | 0.72%   |
| 4267    | 4         | 0.58%   |
| 4266    | 4         | 0.58%   |
| 1066    | 4         | 0.58%   |
| 5600    | 3         | 0.43%   |
| 2933    | 3         | 0.43%   |
| 2048    | 3         | 0.43%   |
| 533     | 3         | 0.43%   |
| 7467    | 1         | 0.14%   |
| 2666    | 1         | 0.14%   |
| 1639    | 1         | 0.14%   |
| 400     | 1         | 0.14%   |
| 333     | 1         | 0.14%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 6         | 27.27%  |
| Canon                 | 6         | 27.27%  |
| Seiko Epson           | 3         | 13.64%  |
| Samsung Electronics   | 3         | 13.64%  |
| Brother Industries    | 2         | 9.09%   |
| Xerox                 | 1         | 4.55%   |
| Lexmark International | 1         | 4.55%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Seiko Epson L3110 Series                   | 2         | 9.09%   |
| Samsung Composite Device                   | 2         | 9.09%   |
| Xerox Phaser 3020                          | 1         | 4.55%   |
| Seiko Epson ET-2710 Series                 | 1         | 4.55%   |
| Samsung M2070 Series                       | 1         | 4.55%   |
| Lexmark International InkJet Color Printer | 1         | 4.55%   |
| HP LaserJet 1022                           | 1         | 4.55%   |
| HP LaserJet 1018                           | 1         | 4.55%   |
| HP Laser 107w                              | 1         | 4.55%   |
| HP Deskjet F4500 series                    | 1         | 4.55%   |
| HP DeskJet 2300 series                     | 1         | 4.55%   |
| HP Deskjet 2050 J510                       | 1         | 4.55%   |
| Canon PIXMA MP250                          | 1         | 4.55%   |
| Canon MF4320-4350                          | 1         | 4.55%   |
| Canon MF3200 series                        | 1         | 4.55%   |
| Canon LiDE 300                             | 1         | 4.55%   |
| Canon LBP2900                              | 1         | 4.55%   |
| Canon iP7200 series                        | 1         | 4.55%   |
| Brother HL-1110 series                     | 1         | 4.55%   |
| Brother DCP-T310                           | 1         | 4.55%   |

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
| IMC Networks                           | 273       | 23.06%  |
| Chicony Electronics                    | 265       | 22.38%  |
| Realtek Semiconductor                  | 103       | 8.7%    |
| Microdia                               | 78        | 6.59%   |
| Quanta                                 | 61        | 5.15%   |
| Sunplus Innovation Technology          | 59        | 4.98%   |
| Bison Electronics                      | 56        | 4.73%   |
| Syntek                                 | 33        | 2.79%   |
| Cheng Uei Precision Industry (Foxlink) | 33        | 2.79%   |
| Acer                                   | 29        | 2.45%   |
| Alcor Micro                            | 28        | 2.36%   |
| Lite-On Technology                     | 26        | 2.2%    |
| Sonix Technology                       | 25        | 2.11%   |
| Suyin                                  | 23        | 1.94%   |
| Luxvisions Innotech Limited            | 17        | 1.44%   |
| Ricoh                                  | 11        | 0.93%   |
| Silicon Motion                         | 8         | 0.68%   |
| ShineTech                              | 7         | 0.59%   |
| Samsung Electronics                    | 7         | 0.59%   |
| OmniVision Technologies                | 6         | 0.51%   |
| Apple                                  | 6         | 0.51%   |
| ALi                                    | 4         | 0.34%   |
| Primax Electronics                     | 3         | 0.25%   |
| Z-Star Microelectronics                | 2         | 0.17%   |
| Sunplus Technology                     | 2         | 0.17%   |
| Microsoft                              | 2         | 0.17%   |
| Lenovo                                 | 2         | 0.17%   |
| Importek                               | 2         | 0.17%   |
| Genesys Logic                          | 2         | 0.17%   |
| Y Media                                | 1         | 0.08%   |
| Trust                                  | 1         | 0.08%   |
| Razer USA                              | 1         | 0.08%   |
| Philips (or NXP)                       | 1         | 0.08%   |
| Logitech                               | 1         | 0.08%   |
| Intel                                  | 1         | 0.08%   |
| Google                                 | 1         | 0.08%   |
| Epiphan Systems                        | 1         | 0.08%   |
| DigiTech                               | 1         | 0.08%   |
| Cubeternet                             | 1         | 0.08%   |
| BKX-210918                             | 1         | 0.08%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                  | 112       | 9.44%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 83        | 7%      |
| Chicony Integrated Camera                           | 61        | 5.14%   |
| IMC Networks Integrated Camera                      | 39        | 3.29%   |
| Realtek Integrated_Webcam_HD                        | 34        | 2.87%   |
| Microdia Integrated_Webcam_HD                       | 27        | 2.28%   |
| Chicony HD WebCam                                   | 22        | 1.85%   |
| Chicony USB2.0 VGA UVC WebCam                       | 21        | 1.77%   |
| Realtek USB Camera                                  | 20        | 1.69%   |
| Sonix USB2.0 HD UVC WebCam                          | 19        | 1.6%    |
| Syntek Integrated Camera                            | 18        | 1.52%   |
| Chicony USB2.0 HD UVC WebCam                        | 17        | 1.43%   |
| Sunplus HD WebCam                                   | 14        | 1.18%   |
| Quanta VGA WebCam                                   | 14        | 1.18%   |
| Bison Integrated Camera                             | 14        | 1.18%   |
| Acer Integrated Camera                              | 12        | 1.01%   |
| Chicony TOSHIBA Web Camera - HD                     | 11        | 0.93%   |
| Bison SunplusIT Integrated Camera                   | 11        | 0.93%   |
| Lite-On Integrated Camera                           | 10        | 0.84%   |
| Chicony EasyCamera                                  | 10        | 0.84%   |
| Sunplus Integrated_Webcam_HD                        | 9         | 0.76%   |
| Microdia Integrated Webcam                          | 9         | 0.76%   |
| Chicony VGA Webcam                                  | 9         | 0.76%   |
| Chicony HP Webcam                                   | 9         | 0.76%   |
| Alcor Micro USB 2.0 PC cam                          | 9         | 0.76%   |
| Quanta ACER HD User Facing                          | 8         | 0.67%   |
| Bison EasyCamera                                    | 8         | 0.67%   |
| Alcor Micro USB 2.0 PC Camera                       | 8         | 0.67%   |
| Syntek Lenovo EasyCamera                            | 7         | 0.59%   |
| Syntek EasyCamera                                   | 7         | 0.59%   |
| Samsung Galaxy series, misc. (MTP mode)             | 7         | 0.59%   |
| Realtek USB2.0 VGA UVC WebCam                       | 7         | 0.59%   |
| Realtek USB2.0 HD UVC WebCam                        | 7         | 0.59%   |
| Realtek Integrated Webcam                           | 7         | 0.59%   |
| IMC Networks USB2.0 UVC HD Webcam                   | 7         | 0.59%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 7         | 0.59%   |
| Acer Lenovo EasyCamera                              | 7         | 0.59%   |
| Sunplus ASUS Webcam                                 | 6         | 0.51%   |
| ShineTech USB2.0 HD UVC WebCam                      | 6         | 0.51%   |
| Realtek Lenovo EasyCamera                           | 6         | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 61        | 33.33%  |
| Synaptics                          | 48        | 26.23%  |
| Shenzhen Goodix Technology         | 23        | 12.57%  |
| Elan Microelectronics              | 16        | 8.74%   |
| Upek                               | 12        | 6.56%   |
| AuthenTec                          | 10        | 5.46%   |
| LighTuning Technology              | 9         | 4.92%   |
| STMicroelectronics                 | 1         | 0.55%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.55%   |
| GDMicroelectronics                 | 1         | 0.55%   |
| Focal-systems.Corp                 | 1         | 0.55%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 17        | 9.29%   |
| Shenzhen Goodix  FingerPrint Device                                        | 16        | 8.74%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 15        | 8.2%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 6.01%   |
| Elan ELAN:Fingerprint                                                      | 10        | 5.46%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 4.92%   |
| Synaptics  WBDI                                                            | 9         | 4.92%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 4.37%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 6         | 3.28%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 6         | 3.28%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 3.28%   |
| Elan ELAN:ARM-M4                                                           | 6         | 3.28%   |
| AuthenTec AES2810                                                          | 6         | 3.28%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 2.73%   |
| Validity Sensors Synaptics WBDI                                            | 5         | 2.73%   |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 2.73%   |
| Validity Sensors VFS491                                                    | 4         | 2.19%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 4         | 2.19%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 1.64%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 1.64%   |
| LighTuning Fingerprint Reader                                              | 3         | 1.64%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 1.64%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 1.64%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 2         | 1.09%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 2         | 1.09%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.09%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.09%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 1.09%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.55%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.55%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.55%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.55%   |
| Synaptics WBDI                                                             | 1         | 0.55%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.55%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.55%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.55%   |
| GDMicroelectronics Touch Fingerprint Sensor                                | 1         | 0.55%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 0.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 46        | 56.1%   |
| Alcor Micro               | 20        | 24.39%  |
| Upek                      | 5         | 6.1%    |
| Lenovo                    | 5         | 6.1%    |
| O2 Micro                  | 4         | 4.88%   |
| Gemalto (was Gemplus)     | 1         | 1.22%   |
| Aladdin Knowledge Systems | 1         | 1.22%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 20        | 24.39%  |
| Broadcom BCM5880 Secure Applications Processor                               | 13        | 15.85%  |
| Broadcom 58200                                                               | 13        | 15.85%  |
| Broadcom 5880                                                                | 11        | 13.41%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 10.98%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 6.1%    |
| Lenovo Integrated Smart Card Reader                                          | 5         | 6.1%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 4.88%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 1.22%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 1.22%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 883       | 65.6%   |
| 1     | 368       | 27.34%  |
| 2     | 84        | 6.24%   |
| 3     | 9         | 0.67%   |
| 10    | 1         | 0.07%   |
| 4     | 1         | 0.07%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 181       | 32.38%  |
| Graphics card            | 114       | 20.39%  |
| Chipcard                 | 75        | 13.42%  |
| Net/wireless             | 60        | 10.73%  |
| Multimedia controller    | 35        | 6.26%   |
| Camera                   | 23        | 4.11%   |
| Storage                  | 16        | 2.86%   |
| Bluetooth                | 16        | 2.86%   |
| Communication controller | 14        | 2.5%    |
| Card reader              | 8         | 1.43%   |
| Net/ethernet             | 4         | 0.72%   |
| Sound                    | 3         | 0.54%   |
| Modem                    | 3         | 0.54%   |
| Network                  | 2         | 0.36%   |
| Flash memory             | 2         | 0.36%   |
| Storage/nvme             | 1         | 0.18%   |
| Firewire controller      | 1         | 0.18%   |
| Dvb card                 | 1         | 0.18%   |

