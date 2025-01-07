MX 23 - Tested Hardware & Statistics (Notebooks)
------------------------------------------------

A project to collect tested hardware configurations for MX 23.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

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

Total: 349

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | Latitude 5590               | [ac8442c3af](https://linux-hardware.org/?probe=ac8442c3af) | Jan 01, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | [cb43939fff](https://linux-hardware.org/?probe=cb43939fff) | Jan 01, 2025 |
| Sony          | VGN-FZ11M                   | [25ec238dec](https://linux-hardware.org/?probe=25ec238dec) | Dec 31, 2024 |
| Lenovo        | ThinkPad E570 20H5S0CF00    | [1b1018c49e](https://linux-hardware.org/?probe=1b1018c49e) | Dec 30, 2024 |
| Dell          | Latitude E7450              | [6677188d5d](https://linux-hardware.org/?probe=6677188d5d) | Dec 27, 2024 |
| Toshiba       | Satellite P870              | [a0e62c769c](https://linux-hardware.org/?probe=a0e62c769c) | Dec 24, 2024 |
| Toshiba       | Satellite P870              | [17c3c89a60](https://linux-hardware.org/?probe=17c3c89a60) | Dec 23, 2024 |
| Acer          | Aspire A315-510P            | [2bb943950c](https://linux-hardware.org/?probe=2bb943950c) | Dec 23, 2024 |
| Dell          | Latitude E6440              | [8ef2131731](https://linux-hardware.org/?probe=8ef2131731) | Dec 23, 2024 |
| ASUSTek       | Vivobook Go E1404FA_E140... | [117beaf6ca](https://linux-hardware.org/?probe=117beaf6ca) | Dec 22, 2024 |
| Apple         | MacBookPro12,1              | [80af2d46c0](https://linux-hardware.org/?probe=80af2d46c0) | Dec 21, 2024 |
| HP            | EliteBook 840 G3            | [dc74fc85f6](https://linux-hardware.org/?probe=dc74fc85f6) | Dec 14, 2024 |
| youyeetoo     | X1 SBC                      | [1abafad3a5](https://linux-hardware.org/?probe=1abafad3a5) | Dec 12, 2024 |
| HP            | Pavilion dv6700             | [1a8a388009](https://linux-hardware.org/?probe=1a8a388009) | Dec 11, 2024 |
| ASUSTek       | F5V                         | [fc57564f87](https://linux-hardware.org/?probe=fc57564f87) | Dec 09, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | [b5d4c3caa9](https://linux-hardware.org/?probe=b5d4c3caa9) | Dec 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [32ae181590](https://linux-hardware.org/?probe=32ae181590) | Dec 01, 2024 |
| Lenovo        | ThinkPad T14 Gen 5 21MMS... | [cf0dcbdaff](https://linux-hardware.org/?probe=cf0dcbdaff) | Nov 30, 2024 |
| HP            | 255 G1                      | [0dd46cadda](https://linux-hardware.org/?probe=0dd46cadda) | Nov 29, 2024 |
| Lenovo        | ThinkPad T440p 20AWA0N5R... | [af6d253f42](https://linux-hardware.org/?probe=af6d253f42) | Nov 25, 2024 |
| Lenovo        | ThinkPad Z61m 94529JG       | [2b158c1a28](https://linux-hardware.org/?probe=2b158c1a28) | Nov 19, 2024 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | [4b5de9a37a](https://linux-hardware.org/?probe=4b5de9a37a) | Nov 19, 2024 |
| Toshiba       | Satellite C55D-B            | [7c3fb96c09](https://linux-hardware.org/?probe=7c3fb96c09) | Nov 18, 2024 |
| Lenovo        | 3000 N200 0769BLG           | [d58726bb7b](https://linux-hardware.org/?probe=d58726bb7b) | Nov 18, 2024 |
| Insyde        | M1106BAP                    | [cad9f73269](https://linux-hardware.org/?probe=cad9f73269) | Nov 18, 2024 |
| Acer          | Aspire A515-54G             | [3b287d26d3](https://linux-hardware.org/?probe=3b287d26d3) | Nov 17, 2024 |
| Lenovo        | 3000 N200 0769BLG           | [60ef264f93](https://linux-hardware.org/?probe=60ef264f93) | Nov 16, 2024 |
| HP            | ENVY m7 Notebook            | [d38f15b4c6](https://linux-hardware.org/?probe=d38f15b4c6) | Nov 13, 2024 |
| Acer          | Aspire 5750G                | [554b0591cd](https://linux-hardware.org/?probe=554b0591cd) | Nov 05, 2024 |
| Dell          | Latitude E6440              | [04241680ab](https://linux-hardware.org/?probe=04241680ab) | Nov 03, 2024 |
| Dell          | Latitude E6440              | [651d5b49ad](https://linux-hardware.org/?probe=651d5b49ad) | Nov 03, 2024 |
| HP            | ProBook 645 G2              | [07452965ae](https://linux-hardware.org/?probe=07452965ae) | Nov 01, 2024 |
| HP            | ProBook 645 G2              | [9f82b3c340](https://linux-hardware.org/?probe=9f82b3c340) | Oct 31, 2024 |
| Acer          | Aspire Lite AL15-52         | [fe9498f7a0](https://linux-hardware.org/?probe=fe9498f7a0) | Oct 29, 2024 |
| HP            | Casablanca H710             | [f80673dbdc](https://linux-hardware.org/?probe=f80673dbdc) | Oct 28, 2024 |
| Apple         | MacBookAir1,1               | [3cf79323fc](https://linux-hardware.org/?probe=3cf79323fc) | Oct 28, 2024 |
| Toshiba       | PORTEGE X30-E               | [8171ac365f](https://linux-hardware.org/?probe=8171ac365f) | Oct 27, 2024 |
| Lenovo        | ThinkPad E470 20H1002FLM    | [7f9f628051](https://linux-hardware.org/?probe=7f9f628051) | Oct 25, 2024 |
| HP            | Pavilion g6                 | [b9c9cc3f65](https://linux-hardware.org/?probe=b9c9cc3f65) | Oct 25, 2024 |
| HP            | Pavilion g6                 | [76ff4ae74d](https://linux-hardware.org/?probe=76ff4ae74d) | Oct 25, 2024 |
| HP            | Laptop 15-dy5xxx            | [c030729a0e](https://linux-hardware.org/?probe=c030729a0e) | Oct 24, 2024 |
| HP            | Laptop 14-fq1xxx            | [4232854445](https://linux-hardware.org/?probe=4232854445) | Oct 23, 2024 |
| ASUSTek       | X551MA                      | [26585357e5](https://linux-hardware.org/?probe=26585357e5) | Oct 21, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [7ae8bf79b4](https://linux-hardware.org/?probe=7ae8bf79b4) | Oct 21, 2024 |
| HP            | Pavilion dv6700             | [082fa9dd81](https://linux-hardware.org/?probe=082fa9dd81) | Oct 17, 2024 |
| HP            | EliteBook 8440p             | [f977e8a7ce](https://linux-hardware.org/?probe=f977e8a7ce) | Oct 16, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [423cf5f3bd](https://linux-hardware.org/?probe=423cf5f3bd) | Oct 16, 2024 |
| HP            | 655                         | [44bcea3de2](https://linux-hardware.org/?probe=44bcea3de2) | Oct 14, 2024 |
| Dell          | Latitude E6430              | [bdebcd33a6](https://linux-hardware.org/?probe=bdebcd33a6) | Oct 12, 2024 |
| Framework     | Laptop                      | [ba5a1a5bfc](https://linux-hardware.org/?probe=ba5a1a5bfc) | Oct 11, 2024 |
| Apple         | MacBookPro7,1               | [292332c812](https://linux-hardware.org/?probe=292332c812) | Oct 08, 2024 |
| Acer          | Aspire 5738                 | [946c78abb8](https://linux-hardware.org/?probe=946c78abb8) | Oct 07, 2024 |
| Apple         | MacBookPro11,4              | [b373b972bf](https://linux-hardware.org/?probe=b373b972bf) | Oct 03, 2024 |
| HP            | ProBook 645 G2              | [07e2717694](https://linux-hardware.org/?probe=07e2717694) | Oct 02, 2024 |
| Medion        | E2215T MD60285              | [a3f12e9645](https://linux-hardware.org/?probe=a3f12e9645) | Oct 01, 2024 |
| MSI           | Prestige 16 AI Evo B1MG     | [e44bc0da2c](https://linux-hardware.org/?probe=e44bc0da2c) | Oct 01, 2024 |
| Lenovo        | ThinkPad T410 2522E34       | [22aef19581](https://linux-hardware.org/?probe=22aef19581) | Sep 30, 2024 |
| HP            | 255 15.6 inch G9 Noteboo... | [6526213a5a](https://linux-hardware.org/?probe=6526213a5a) | Sep 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | [1c28596af0](https://linux-hardware.org/?probe=1c28596af0) | Sep 28, 2024 |
| TECNO Mobi... | MEGABOOK T14TA              | [f42a3c6797](https://linux-hardware.org/?probe=f42a3c6797) | Sep 28, 2024 |
| Dell          | Latitude 7490               | [4fc1fc2d86](https://linux-hardware.org/?probe=4fc1fc2d86) | Sep 27, 2024 |
| Samsung       | 730U3E/740U3E               | [82cb5ef24c](https://linux-hardware.org/?probe=82cb5ef24c) | Sep 25, 2024 |
| Lenovo        | LOQ 15IRH8 82XV             | [a8db3428c3](https://linux-hardware.org/?probe=a8db3428c3) | Sep 25, 2024 |
| HP            | Pavilion g6                 | [e4085b23eb](https://linux-hardware.org/?probe=e4085b23eb) | Sep 24, 2024 |
| HP            | Pavilion 17                 | [6d532316c9](https://linux-hardware.org/?probe=6d532316c9) | Sep 22, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M360... | [ae73de44a9](https://linux-hardware.org/?probe=ae73de44a9) | Sep 22, 2024 |
| Dell          | System XPS L702X            | [d2662fe6a6](https://linux-hardware.org/?probe=d2662fe6a6) | Sep 20, 2024 |
| Acer          | Aspire A515-47              | [bf14576006](https://linux-hardware.org/?probe=bf14576006) | Sep 16, 2024 |
| Lenovo        | ThinkPad T410 2522G18       | [1165597d26](https://linux-hardware.org/?probe=1165597d26) | Sep 16, 2024 |
| System76      | Serval WS                   | [0da8d49168](https://linux-hardware.org/?probe=0da8d49168) | Sep 14, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [b105d16e70](https://linux-hardware.org/?probe=b105d16e70) | Sep 13, 2024 |
| HP            | EliteBook 840 G1            | [f8dd4f91b9](https://linux-hardware.org/?probe=f8dd4f91b9) | Sep 12, 2024 |
| Inter Sale... | NID-11125DE                 | [5f0390c58c](https://linux-hardware.org/?probe=5f0390c58c) | Sep 12, 2024 |
| HP            | Pavilion dv7                | [871aaa0215](https://linux-hardware.org/?probe=871aaa0215) | Sep 11, 2024 |
| HP            | Pavilion dv7                | [af8ba6a16b](https://linux-hardware.org/?probe=af8ba6a16b) | Sep 11, 2024 |
| Dell          | Latitude 7300               | [e7bf6cf5d8](https://linux-hardware.org/?probe=e7bf6cf5d8) | Sep 06, 2024 |
| HP            | Notebook                    | [4074a83837](https://linux-hardware.org/?probe=4074a83837) | Sep 01, 2024 |
| Dell          | System XPS 15Z              | [64925b60e9](https://linux-hardware.org/?probe=64925b60e9) | Aug 29, 2024 |
| Apple         | MacBookPro8,2               | [23e6c52258](https://linux-hardware.org/?probe=23e6c52258) | Aug 29, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [02c479ee0f](https://linux-hardware.org/?probe=02c479ee0f) | Aug 27, 2024 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [d4b46af5cb](https://linux-hardware.org/?probe=d4b46af5cb) | Aug 27, 2024 |
| Unknown       | AX16Pro                     | [091e76b6ed](https://linux-hardware.org/?probe=091e76b6ed) | Aug 27, 2024 |
| Lenovo        | B550 20053                  | [d7a362e8ae](https://linux-hardware.org/?probe=d7a362e8ae) | Aug 25, 2024 |
| HP            | Notebook                    | [51aefbbe02](https://linux-hardware.org/?probe=51aefbbe02) | Aug 24, 2024 |
| Dell          | Inspiron 15 3511            | [e9389eeab0](https://linux-hardware.org/?probe=e9389eeab0) | Aug 24, 2024 |
| HP            | ProBook 455 G8 Notebook ... | [5dd0130b6b](https://linux-hardware.org/?probe=5dd0130b6b) | Aug 21, 2024 |
| Dell          | XPS 15 9570                 | [561ce191e0](https://linux-hardware.org/?probe=561ce191e0) | Aug 19, 2024 |
| Dell          | XPS 15 9570                 | [6011f4954b](https://linux-hardware.org/?probe=6011f4954b) | Aug 19, 2024 |
| MSI           | Vector 16 HX A14VHG         | [00d080c251](https://linux-hardware.org/?probe=00d080c251) | Aug 17, 2024 |
| Dell          | Latitude D430               | [4346500f96](https://linux-hardware.org/?probe=4346500f96) | Aug 16, 2024 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | [9153a53950](https://linux-hardware.org/?probe=9153a53950) | Aug 16, 2024 |
| Lenovo        | V17 G3 IAP 82U1             | [1b19bfdd9a](https://linux-hardware.org/?probe=1b19bfdd9a) | Aug 15, 2024 |
| Dell          | XPS 16 9640                 | [4c6475c28e](https://linux-hardware.org/?probe=4c6475c28e) | Aug 12, 2024 |
| Acer          | TP-SW5-012P-18FQ            | [95f5359eb5](https://linux-hardware.org/?probe=95f5359eb5) | Aug 10, 2024 |
| Unknown       | E142                        | [9944efec2a](https://linux-hardware.org/?probe=9944efec2a) | Aug 07, 2024 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | [a4f8eaf4bc](https://linux-hardware.org/?probe=a4f8eaf4bc) | Aug 07, 2024 |
| ASUSTek       | T100TA                      | [087ac815ec](https://linux-hardware.org/?probe=087ac815ec) | Aug 06, 2024 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [1771fdc95b](https://linux-hardware.org/?probe=1771fdc95b) | Aug 06, 2024 |
| Acer          | Aspire A515-47              | [7e28f24801](https://linux-hardware.org/?probe=7e28f24801) | Jul 30, 2024 |
| Acer          | Aspire A315-510P            | [49a9d6c2e4](https://linux-hardware.org/?probe=49a9d6c2e4) | Jul 30, 2024 |
| Acer          | TP-SW5-012P-18FQ            | [0cd53c394b](https://linux-hardware.org/?probe=0cd53c394b) | Jul 26, 2024 |
| HP            | Compaq 6730s                | [2c89ca2d0d](https://linux-hardware.org/?probe=2c89ca2d0d) | Jul 25, 2024 |
| HP            | Compaq 6730s                | [5724e952f7](https://linux-hardware.org/?probe=5724e952f7) | Jul 25, 2024 |
| ASUSTek       | PU301LA                     | [4f9c3ff09f](https://linux-hardware.org/?probe=4f9c3ff09f) | Jul 23, 2024 |
| HP            | ProBook 455 G2              | [6e9b0d9256](https://linux-hardware.org/?probe=6e9b0d9256) | Jul 22, 2024 |
| HP            | ENVY m7 Notebook            | [b9f143068f](https://linux-hardware.org/?probe=b9f143068f) | Jul 21, 2024 |
| Lenovo        | ThinkPad L480 20LS001AGE    | [797eae789c](https://linux-hardware.org/?probe=797eae789c) | Jul 21, 2024 |
| Apple         | MacBookPro5,4               | [44267b835a](https://linux-hardware.org/?probe=44267b835a) | Jul 16, 2024 |
| Lenovo        | ThinkPad T500 20552CU       | [587f2d66e0](https://linux-hardware.org/?probe=587f2d66e0) | Jul 12, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [dd1cfc0693](https://linux-hardware.org/?probe=dd1cfc0693) | Jul 11, 2024 |
| Acer          | Aspire 5538                 | [209e123c1e](https://linux-hardware.org/?probe=209e123c1e) | Jul 08, 2024 |
| HP            | ProBook 455 15.6 inch G9... | [75ce86bf8e](https://linux-hardware.org/?probe=75ce86bf8e) | Jul 05, 2024 |
| Dell          | Latitude E5420              | [a140673eb6](https://linux-hardware.org/?probe=a140673eb6) | Jul 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [17c5c8cb74](https://linux-hardware.org/?probe=17c5c8cb74) | Jun 28, 2024 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | [64ca53d3d0](https://linux-hardware.org/?probe=64ca53d3d0) | Jun 27, 2024 |
| Razer         | Blade 18 - RZ09-0509        | [d0e4380367](https://linux-hardware.org/?probe=d0e4380367) | Jun 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | [c6bee0ad67](https://linux-hardware.org/?probe=c6bee0ad67) | Jun 23, 2024 |
| Lenovo        | ThinkPad T580 20LAS4KG0Q    | [9e222818ab](https://linux-hardware.org/?probe=9e222818ab) | Jun 22, 2024 |
| Lenovo        | ThinkPad T580 20LAS4KG0Q    | [d20044a0fc](https://linux-hardware.org/?probe=d20044a0fc) | Jun 22, 2024 |
| Acer          | Aspire ES1-572              | [3ed5118890](https://linux-hardware.org/?probe=3ed5118890) | Jun 21, 2024 |
| Dell          | XPS 14 9440                 | [b32c71b845](https://linux-hardware.org/?probe=b32c71b845) | Jun 14, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [386adc3726](https://linux-hardware.org/?probe=386adc3726) | Jun 13, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [8c44fcfe24](https://linux-hardware.org/?probe=8c44fcfe24) | Jun 08, 2024 |
| Dell          | Latitude 3190               | [931a3406c1](https://linux-hardware.org/?probe=931a3406c1) | Jun 06, 2024 |
| HP            | Compaq 6715s (KE068ET#AB... | [c823161b4d](https://linux-hardware.org/?probe=c823161b4d) | Jun 05, 2024 |
| HP            | Compaq 6715s (KE068ET#AB... | [bd5daadc8e](https://linux-hardware.org/?probe=bd5daadc8e) | Jun 05, 2024 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [8e15f36c9e](https://linux-hardware.org/?probe=8e15f36c9e) | Jun 02, 2024 |
| HP            | 255 G7 Notebook PC          | [a22a7ed64a](https://linux-hardware.org/?probe=a22a7ed64a) | May 30, 2024 |
| HP            | Laptop 15-dw1xxx            | [b1b2d6a841](https://linux-hardware.org/?probe=b1b2d6a841) | May 30, 2024 |
| Acer          | Aspire ES1-533              | [f308e9468f](https://linux-hardware.org/?probe=f308e9468f) | May 29, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [5d9d51e2c4](https://linux-hardware.org/?probe=5d9d51e2c4) | May 28, 2024 |
| HP            | ENVY Notebook               | [525b25d9db](https://linux-hardware.org/?probe=525b25d9db) | May 28, 2024 |
| Acer          | Aspire 8730                 | [9633277543](https://linux-hardware.org/?probe=9633277543) | May 27, 2024 |
| Dell          | Studio XPS 1645             | [e9eb7685bd](https://linux-hardware.org/?probe=e9eb7685bd) | May 27, 2024 |
| Dell          | Studio XPS 1645             | [d4926c0589](https://linux-hardware.org/?probe=d4926c0589) | May 26, 2024 |
| ASUSTek       | Vivobook Go E1504FA_E150... | [599aca7ecd](https://linux-hardware.org/?probe=599aca7ecd) | May 23, 2024 |
| Fujitsu Si... | AMILO Li 2727               | [730034178b](https://linux-hardware.org/?probe=730034178b) | May 22, 2024 |
| Dell          | Latitude 3190               | [744cbd30d7](https://linux-hardware.org/?probe=744cbd30d7) | May 21, 2024 |
| HP            | ProBook 455 G8 Notebook ... | [f7b6c908b5](https://linux-hardware.org/?probe=f7b6c908b5) | May 20, 2024 |
| HP            | 650                         | [4e91cb9494](https://linux-hardware.org/?probe=4e91cb9494) | May 19, 2024 |
| Lenovo        | B590 37613FG                | [34097ce34b](https://linux-hardware.org/?probe=34097ce34b) | May 16, 2024 |
| Lenovo        | ThinkPad T410s 2912BY8      | [6d19133fbd](https://linux-hardware.org/?probe=6d19133fbd) | May 16, 2024 |
| Dell          | Vostro 15 3515              | [a936d845d9](https://linux-hardware.org/?probe=a936d845d9) | May 14, 2024 |
| Lenovo        | ThinkPad T410s 2912BY8      | [ef78e9b672](https://linux-hardware.org/?probe=ef78e9b672) | May 13, 2024 |
| GFAST         | N-140                       | [5f9ab6d37e](https://linux-hardware.org/?probe=5f9ab6d37e) | May 13, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [ccf9b15f46](https://linux-hardware.org/?probe=ccf9b15f46) | May 13, 2024 |
| Toshiba       | Satellite C55D-B            | [916a3269bb](https://linux-hardware.org/?probe=916a3269bb) | May 11, 2024 |
| HP            | 250 G1                      | [d2f30faf8c](https://linux-hardware.org/?probe=d2f30faf8c) | May 11, 2024 |
| HP            | Laptop 14-bs0xx             | [67c81e68d4](https://linux-hardware.org/?probe=67c81e68d4) | May 09, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [413b207df0](https://linux-hardware.org/?probe=413b207df0) | May 09, 2024 |
| Dell          | Latitude 3190               | [102011a182](https://linux-hardware.org/?probe=102011a182) | May 07, 2024 |
| Toshiba       | Satellite C50-B             | [4037de5266](https://linux-hardware.org/?probe=4037de5266) | May 06, 2024 |
| Lenovo        | Yoga Slim 7-14ARE05 82A2    | [c931a1a446](https://linux-hardware.org/?probe=c931a1a446) | May 05, 2024 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [41e3014295](https://linux-hardware.org/?probe=41e3014295) | May 04, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [cbd3101c16](https://linux-hardware.org/?probe=cbd3101c16) | May 01, 2024 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [6aca55ce35](https://linux-hardware.org/?probe=6aca55ce35) | May 01, 2024 |
| Lenovo        | Yoga 710-11IKB 80V6         | [bac49afb7f](https://linux-hardware.org/?probe=bac49afb7f) | Apr 30, 2024 |
| Apple         | MacBookPro5,5               | [d1fbf194df](https://linux-hardware.org/?probe=d1fbf194df) | Apr 25, 2024 |
| Dell          | XPS 13 9305                 | [62621a436b](https://linux-hardware.org/?probe=62621a436b) | Apr 25, 2024 |
| Lenovo        | G505s 20255                 | [b7d2ec7d4d](https://linux-hardware.org/?probe=b7d2ec7d4d) | Apr 24, 2024 |
| Acer          | Aspire A515-47              | [dc0e4e49bb](https://linux-hardware.org/?probe=dc0e4e49bb) | Apr 24, 2024 |
| Acer          | Aspire A515-47              | [feba2802f3](https://linux-hardware.org/?probe=feba2802f3) | Apr 22, 2024 |
| Samsung       | N150/N210/N220              | [73f5edc5e5](https://linux-hardware.org/?probe=73f5edc5e5) | Apr 22, 2024 |
| SGIN          | M15                         | [68c2d94db7](https://linux-hardware.org/?probe=68c2d94db7) | Apr 20, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | [9e43e9df38](https://linux-hardware.org/?probe=9e43e9df38) | Apr 19, 2024 |
| HP            | Pavilion Aero Laptop 13-... | [b3e2fd82b1](https://linux-hardware.org/?probe=b3e2fd82b1) | Apr 18, 2024 |
| GPU Compan... | GWTN116-3                   | [30fba12411](https://linux-hardware.org/?probe=30fba12411) | Apr 18, 2024 |
| GPU Compan... | GWTN116-3                   | [a11ace542b](https://linux-hardware.org/?probe=a11ace542b) | Apr 18, 2024 |
| Toshiba       | Satellite C55D-B            | [0d2ecb9207](https://linux-hardware.org/?probe=0d2ecb9207) | Apr 17, 2024 |
| Acer          | Aspire E1-572               | [a91f9fc37a](https://linux-hardware.org/?probe=a91f9fc37a) | Apr 15, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [e717cc9856](https://linux-hardware.org/?probe=e717cc9856) | Apr 13, 2024 |
| Google        | Cyan                        | [46c86ddfe0](https://linux-hardware.org/?probe=46c86ddfe0) | Apr 12, 2024 |
| Google        | Cyan                        | [e2c458d3a7](https://linux-hardware.org/?probe=e2c458d3a7) | Apr 11, 2024 |
| Acer          | AO756                       | [79847ca0b1](https://linux-hardware.org/?probe=79847ca0b1) | Apr 11, 2024 |
| Dell          | Latitude 3190               | [4f2b2351b3](https://linux-hardware.org/?probe=4f2b2351b3) | Apr 09, 2024 |
| HP            | Notebook                    | [414230182b](https://linux-hardware.org/?probe=414230182b) | Apr 06, 2024 |
| Google        | Magolor                     | [36145fc673](https://linux-hardware.org/?probe=36145fc673) | Apr 06, 2024 |
| Lenovo        | IdeaPad 1 15IJL7 82LX       | [0852701d67](https://linux-hardware.org/?probe=0852701d67) | Apr 05, 2024 |
| Dell          | Latitude 3190               | [c15e7df670](https://linux-hardware.org/?probe=c15e7df670) | Apr 02, 2024 |
| Dell          | Inspiron 3185               | [80090c69a3](https://linux-hardware.org/?probe=80090c69a3) | Mar 31, 2024 |
| Lenovo        | ThinkPad X280 20KES6M100    | [07c23b72ec](https://linux-hardware.org/?probe=07c23b72ec) | Mar 25, 2024 |
| HP            | 250 G1                      | [1061b55594](https://linux-hardware.org/?probe=1061b55594) | Mar 25, 2024 |
| Apple         | MacBookPro7,1               | [bbfdefb7ef](https://linux-hardware.org/?probe=bbfdefb7ef) | Mar 25, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JT0... | [cc230156f7](https://linux-hardware.org/?probe=cc230156f7) | Mar 19, 2024 |
| Lenovo        | IdeaPad Slim 5 16ABR8 82... | [16070af93d](https://linux-hardware.org/?probe=16070af93d) | Mar 17, 2024 |
| Toshiba       | dynabook T552/36GB          | [9da00148f4](https://linux-hardware.org/?probe=9da00148f4) | Mar 14, 2024 |
| Medion        | Defender P30                | [34a9a3fde8](https://linux-hardware.org/?probe=34a9a3fde8) | Mar 13, 2024 |
| Medion        | Defender P30                | [459ac8cc46](https://linux-hardware.org/?probe=459ac8cc46) | Mar 13, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | [91114bc213](https://linux-hardware.org/?probe=91114bc213) | Mar 13, 2024 |
| Toshiba       | Satellite P875              | [e1b998e44b](https://linux-hardware.org/?probe=e1b998e44b) | Mar 09, 2024 |
| Lenovo        | G50-30 80G0                 | [be5e190ea5](https://linux-hardware.org/?probe=be5e190ea5) | Mar 08, 2024 |
| ASUSTek       | T100TA                      | [d723bb2900](https://linux-hardware.org/?probe=d723bb2900) | Mar 07, 2024 |
| HP            | EliteBook 840 G6            | [e61abe174c](https://linux-hardware.org/?probe=e61abe174c) | Mar 04, 2024 |
| Google        | Magolor                     | [bf456da608](https://linux-hardware.org/?probe=bf456da608) | Mar 04, 2024 |
| HP            | Pavilion g6                 | [fd797ba3af](https://linux-hardware.org/?probe=fd797ba3af) | Mar 04, 2024 |
| Alienware     | 18                          | [b7402f0c82](https://linux-hardware.org/?probe=b7402f0c82) | Mar 03, 2024 |
| HP            | Pavilion g6                 | [7e4412a097](https://linux-hardware.org/?probe=7e4412a097) | Mar 03, 2024 |
| HP            | Pavilion dv6                | [14e50b9c6c](https://linux-hardware.org/?probe=14e50b9c6c) | Mar 01, 2024 |
| PC Special... | Lafite Pro III 17           | [41f1e90fb9](https://linux-hardware.org/?probe=41f1e90fb9) | Feb 29, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | [c6209a30c6](https://linux-hardware.org/?probe=c6209a30c6) | Feb 28, 2024 |
| HP            | 250 15.6 inch G9 Noteboo... | [3d502260aa](https://linux-hardware.org/?probe=3d502260aa) | Feb 28, 2024 |
| Toshiba       | IS 1413G                    | [0f39b4b446](https://linux-hardware.org/?probe=0f39b4b446) | Feb 27, 2024 |
| Toshiba       | Satellite C55-A             | [9d0cd280a9](https://linux-hardware.org/?probe=9d0cd280a9) | Feb 27, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [527feb458b](https://linux-hardware.org/?probe=527feb458b) | Feb 26, 2024 |
| HP            | OMEN by Gaming Laptop 16... | [f31eac8a5d](https://linux-hardware.org/?probe=f31eac8a5d) | Feb 24, 2024 |
| Apple         | MacBookPro5,2               | [f34e05e096](https://linux-hardware.org/?probe=f34e05e096) | Feb 23, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [bb563ea8ac](https://linux-hardware.org/?probe=bb563ea8ac) | Feb 23, 2024 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [2c9ffa4b20](https://linux-hardware.org/?probe=2c9ffa4b20) | Feb 23, 2024 |
| Toshiba       | IS 1413G                    | [c88a0acd8e](https://linux-hardware.org/?probe=c88a0acd8e) | Feb 22, 2024 |
| Dell          | Vostro 1014                 | [5fcabcc564](https://linux-hardware.org/?probe=5fcabcc564) | Feb 22, 2024 |
| Dell          | Latitude 3190               | [1396b535bf](https://linux-hardware.org/?probe=1396b535bf) | Feb 20, 2024 |
| I-life        | ZEDNOTE                     | [172d63ec33](https://linux-hardware.org/?probe=172d63ec33) | Feb 19, 2024 |
| Dell          | Vostro 15-3568              | [75d09cfc27](https://linux-hardware.org/?probe=75d09cfc27) | Feb 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | [96859b01b7](https://linux-hardware.org/?probe=96859b01b7) | Feb 17, 2024 |
| HP            | Laptop 14-dk0xxx            | [9e494a90c5](https://linux-hardware.org/?probe=9e494a90c5) | Feb 17, 2024 |
| HP            | OMEN by Gaming Laptop 16... | [39da02c65d](https://linux-hardware.org/?probe=39da02c65d) | Feb 16, 2024 |
| Dell          | Inspiron 7566               | [9d3c279e4c](https://linux-hardware.org/?probe=9d3c279e4c) | Feb 16, 2024 |
| Lenovo        | ThinkPad P14s Gen 2i 20V... | [70a8707a5c](https://linux-hardware.org/?probe=70a8707a5c) | Feb 15, 2024 |
| Dell          | Latitude 3190               | [2f96d064fd](https://linux-hardware.org/?probe=2f96d064fd) | Feb 13, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [a7f40a3ffe](https://linux-hardware.org/?probe=a7f40a3ffe) | Feb 11, 2024 |
| Fujitsu Si... | AMILO Li 1818               | [1703fc6a96](https://linux-hardware.org/?probe=1703fc6a96) | Feb 11, 2024 |
| ASUSTek       | T100TAM                     | [2b6b08ce6c](https://linux-hardware.org/?probe=2b6b08ce6c) | Feb 10, 2024 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [de7b828cc8](https://linux-hardware.org/?probe=de7b828cc8) | Feb 10, 2024 |
| Dell          | XPS 13 9350                 | [24d22f38e9](https://linux-hardware.org/?probe=24d22f38e9) | Feb 08, 2024 |
| Dell          | Latitude 3190               | [f597a4ca06](https://linux-hardware.org/?probe=f597a4ca06) | Feb 06, 2024 |
| MSI           | GE63 Raider RGB 9SE         | [044863dd64](https://linux-hardware.org/?probe=044863dd64) | Feb 05, 2024 |
| Dell          | Latitude 120L               | [e5707dd6cb](https://linux-hardware.org/?probe=e5707dd6cb) | Feb 04, 2024 |
| Samsung       | 750XDA                      | [a7dd0472ed](https://linux-hardware.org/?probe=a7dd0472ed) | Feb 03, 2024 |
| VIT           | P3400                       | [036ee57838](https://linux-hardware.org/?probe=036ee57838) | Feb 02, 2024 |
| VIT           | P3400                       | [6b03e6574f](https://linux-hardware.org/?probe=6b03e6574f) | Feb 01, 2024 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [653f9c5fa5](https://linux-hardware.org/?probe=653f9c5fa5) | Feb 01, 2024 |
| Dell          | Latitude 3190               | [16f86af47d](https://linux-hardware.org/?probe=16f86af47d) | Jan 30, 2024 |
| Dell          | Latitude E6410              | [1b7b83010f](https://linux-hardware.org/?probe=1b7b83010f) | Jan 24, 2024 |
| Apple         | MacBookAir6,2               | [6eb8876e79](https://linux-hardware.org/?probe=6eb8876e79) | Jan 24, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [e03dc88f3e](https://linux-hardware.org/?probe=e03dc88f3e) | Jan 20, 2024 |
| HP            | Notebook                    | [0f5f8dd38d](https://linux-hardware.org/?probe=0f5f8dd38d) | Jan 17, 2024 |
| Google        | Barla                       | [f053c5164a](https://linux-hardware.org/?probe=f053c5164a) | Jan 16, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | [d0af07b360](https://linux-hardware.org/?probe=d0af07b360) | Jan 15, 2024 |
| Apple         | MacBookPro14,3              | [3b0c274172](https://linux-hardware.org/?probe=3b0c274172) | Jan 12, 2024 |
| Lenovo        | ThinkPad T470s W10DG 20J... | [f782b74751](https://linux-hardware.org/?probe=f782b74751) | Jan 12, 2024 |
| Dell          | Latitude 3190               | [afdd5a1dbe](https://linux-hardware.org/?probe=afdd5a1dbe) | Jan 09, 2024 |
| HP            | Pavilion dv2700             | [957ec4cc30](https://linux-hardware.org/?probe=957ec4cc30) | Jan 09, 2024 |
| Sony          | SVF1521H1EW                 | [1939183179](https://linux-hardware.org/?probe=1939183179) | Jan 07, 2024 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [71d03730b7](https://linux-hardware.org/?probe=71d03730b7) | Jan 03, 2024 |
| Dell          | Latitude 5400               | [9e318e9b78](https://linux-hardware.org/?probe=9e318e9b78) | Jan 03, 2024 |
| Dell          | Latitude 5400               | [59a90bd726](https://linux-hardware.org/?probe=59a90bd726) | Jan 03, 2024 |
| Google        | Barla                       | [585887bc42](https://linux-hardware.org/?probe=585887bc42) | Dec 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [8f3ab867ea](https://linux-hardware.org/?probe=8f3ab867ea) | Dec 30, 2023 |
| HP            | Pavilion dv6                | [39515c70db](https://linux-hardware.org/?probe=39515c70db) | Dec 27, 2023 |
| HP            | Pavilion dv6                | [c29956a752](https://linux-hardware.org/?probe=c29956a752) | Dec 27, 2023 |
| HONOR         | NMH-WCX9                    | [5647df79c0](https://linux-hardware.org/?probe=5647df79c0) | Dec 26, 2023 |
| Dell          | Latitude 3190               | [e0da711bcb](https://linux-hardware.org/?probe=e0da711bcb) | Dec 26, 2023 |
| Acer          | Aspire A315-24P             | [eade6242b7](https://linux-hardware.org/?probe=eade6242b7) | Dec 25, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [ab0b99f2f2](https://linux-hardware.org/?probe=ab0b99f2f2) | Dec 25, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [0da41c3e3b](https://linux-hardware.org/?probe=0da41c3e3b) | Dec 25, 2023 |
| Google        | Bobba                       | [c0e8038184](https://linux-hardware.org/?probe=c0e8038184) | Dec 22, 2023 |
| Google        | Bobba                       | [c03b219f2e](https://linux-hardware.org/?probe=c03b219f2e) | Dec 22, 2023 |
| ASUSTek       | X553MA                      | [bc7fc2be74](https://linux-hardware.org/?probe=bc7fc2be74) | Dec 20, 2023 |
| ASUSTek       | X553MA                      | [11f3b9c9d6](https://linux-hardware.org/?probe=11f3b9c9d6) | Dec 20, 2023 |
| Dell          | Latitude 3190               | [a7e488632e](https://linux-hardware.org/?probe=a7e488632e) | Dec 19, 2023 |
| HP            | Notebook                    | [d25691af9b](https://linux-hardware.org/?probe=d25691af9b) | Dec 13, 2023 |
| Dell          | Latitude 3190               | [faf8105e3c](https://linux-hardware.org/?probe=faf8105e3c) | Dec 12, 2023 |
| GPU Compan... | GWTC116-2                   | [10e35dbb2a](https://linux-hardware.org/?probe=10e35dbb2a) | Dec 12, 2023 |
| Dell          | Vostro 1320                 | [cf44765cd0](https://linux-hardware.org/?probe=cf44765cd0) | Dec 11, 2023 |
| Lenovo        | ThinkPad X201 3626GWG       | [023f7dd390](https://linux-hardware.org/?probe=023f7dd390) | Dec 11, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [6c558ca3cf](https://linux-hardware.org/?probe=6c558ca3cf) | Dec 06, 2023 |
| Apple         | MacBook3,1                  | [d536392d03](https://linux-hardware.org/?probe=d536392d03) | Nov 30, 2023 |
| Apple         | MacBook3,1                  | [bfe263dfe0](https://linux-hardware.org/?probe=bfe263dfe0) | Nov 30, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [339e20f716](https://linux-hardware.org/?probe=339e20f716) | Nov 24, 2023 |
| Mediacom      | FlexBook edge11 - M-FBE1... | [9b0835e62d](https://linux-hardware.org/?probe=9b0835e62d) | Nov 21, 2023 |
| Dell          | Latitude 3190               | [3c5b8541c7](https://linux-hardware.org/?probe=3c5b8541c7) | Nov 21, 2023 |
| Acer          | Extensa 215-55              | [e1a2307332](https://linux-hardware.org/?probe=e1a2307332) | Nov 18, 2023 |
| Dell          | Precision 5570              | [7cb435d2dc](https://linux-hardware.org/?probe=7cb435d2dc) | Nov 16, 2023 |
| Gateway       | NV57H                       | [e5f084f72c](https://linux-hardware.org/?probe=e5f084f72c) | Nov 11, 2023 |
| Dell          | Latitude 3190               | [309f968d10](https://linux-hardware.org/?probe=309f968d10) | Nov 07, 2023 |
| HP            | ProBook 6470b               | [50c1d43281](https://linux-hardware.org/?probe=50c1d43281) | Nov 05, 2023 |
| AMI           | Unknown                     | [2512404fd7](https://linux-hardware.org/?probe=2512404fd7) | Nov 05, 2023 |
| Dell          | Latitude 5490               | [fcee866d9a](https://linux-hardware.org/?probe=fcee866d9a) | Oct 31, 2023 |
| Dell          | Latitude 3190               | [dc68dc55c9](https://linux-hardware.org/?probe=dc68dc55c9) | Oct 31, 2023 |
| HONOR         | BMH-WDX9                    | [a1962fef8a](https://linux-hardware.org/?probe=a1962fef8a) | Oct 31, 2023 |
| HP            | EliteBook 840 G6            | [52786d6efa](https://linux-hardware.org/?probe=52786d6efa) | Oct 30, 2023 |
| Dell          | Latitude 3190               | [a26f69cb33](https://linux-hardware.org/?probe=a26f69cb33) | Oct 24, 2023 |
| Dell          | Inspiron 16 7610            | [36eb2472ca](https://linux-hardware.org/?probe=36eb2472ca) | Oct 20, 2023 |
| HP            | ZBook 17 G2                 | [6c7d912754](https://linux-hardware.org/?probe=6c7d912754) | Oct 20, 2023 |
| Sony          | SVF1521A6EW                 | [dada2b85e8](https://linux-hardware.org/?probe=dada2b85e8) | Oct 17, 2023 |
| Dell          | Inspiron 5448               | [5901b49079](https://linux-hardware.org/?probe=5901b49079) | Oct 17, 2023 |
| Dell          | Latitude 3190               | [6524dff50f](https://linux-hardware.org/?probe=6524dff50f) | Oct 17, 2023 |
| Apple         | MacBookPro5,3               | [60e2d65ac4](https://linux-hardware.org/?probe=60e2d65ac4) | Oct 16, 2023 |
| Apple         | MacBookPro8,1               | [df7395bd63](https://linux-hardware.org/?probe=df7395bd63) | Oct 16, 2023 |
| Google        | Celes                       | [914ad131fd](https://linux-hardware.org/?probe=914ad131fd) | Oct 13, 2023 |
| Dell          | Latitude E6410              | [d6db17e35f](https://linux-hardware.org/?probe=d6db17e35f) | Oct 06, 2023 |
| Dell          | Latitude 3190               | [21aac15234](https://linux-hardware.org/?probe=21aac15234) | Oct 03, 2023 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | [4b46fb8e6a](https://linux-hardware.org/?probe=4b46fb8e6a) | Oct 02, 2023 |
| Lenovo        | IdeaPad Pro 5 16APH8 83A... | [ee6e1996b9](https://linux-hardware.org/?probe=ee6e1996b9) | Sep 29, 2023 |
| Dell          | XPS 15 7590                 | [3c87964524](https://linux-hardware.org/?probe=3c87964524) | Sep 28, 2023 |
| Lenovo        | ThinkPad X240 20AMS1JQ11    | [2b7f074e47](https://linux-hardware.org/?probe=2b7f074e47) | Sep 27, 2023 |
| Dell          | Latitude 3190               | [8ebd8669f2](https://linux-hardware.org/?probe=8ebd8669f2) | Sep 26, 2023 |
| Apple         | MacBookAir5,2               | [55dec782e7](https://linux-hardware.org/?probe=55dec782e7) | Sep 25, 2023 |
| Apple         | MacBookPro8,1               | [0c1f872edb](https://linux-hardware.org/?probe=0c1f872edb) | Sep 23, 2023 |
| Dell          | Precision 5570              | [27b003d343](https://linux-hardware.org/?probe=27b003d343) | Sep 22, 2023 |
| HP            | EliteBook 735 G6            | [0ad032f320](https://linux-hardware.org/?probe=0ad032f320) | Sep 19, 2023 |
| Dell          | Latitude 3190               | [0a698044d8](https://linux-hardware.org/?probe=0a698044d8) | Sep 19, 2023 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [9e9652809d](https://linux-hardware.org/?probe=9e9652809d) | Sep 18, 2023 |
| HP            | Laptop 15-da0xxx            | [d66a3d9329](https://linux-hardware.org/?probe=d66a3d9329) | Sep 18, 2023 |
| Dell          | Latitude D620               | [65d2f56829](https://linux-hardware.org/?probe=65d2f56829) | Sep 18, 2023 |
| HP            | Pavilion dv2                | [ee227b3d35](https://linux-hardware.org/?probe=ee227b3d35) | Sep 16, 2023 |
| ASUSTek       | K55VJ                       | [82cae5303a](https://linux-hardware.org/?probe=82cae5303a) | Sep 16, 2023 |
| ASUSTek       | K55VJ                       | [db874f0737](https://linux-hardware.org/?probe=db874f0737) | Sep 16, 2023 |
| ASUSTek       | K54L                        | [4b62e4c882](https://linux-hardware.org/?probe=4b62e4c882) | Sep 15, 2023 |
| Dell          | Latitude 3190               | [a03ec42023](https://linux-hardware.org/?probe=a03ec42023) | Sep 12, 2023 |
| Dell          | XPS 17 9700                 | [e83ef4efd8](https://linux-hardware.org/?probe=e83ef4efd8) | Sep 11, 2023 |
| Lenovo        | ThinkPad L580 20LW000VFR    | [a7dfc5e0f5](https://linux-hardware.org/?probe=a7dfc5e0f5) | Sep 09, 2023 |
| Lenovo        | ThinkPad L580 20LW000VFR    | [e224a5dc53](https://linux-hardware.org/?probe=e224a5dc53) | Sep 09, 2023 |
| Lenovo        | V15 G3 ABA 82TV             | [b906e23303](https://linux-hardware.org/?probe=b906e23303) | Sep 08, 2023 |
| HP            | ProBook 640 G2              | [318f1010b6](https://linux-hardware.org/?probe=318f1010b6) | Sep 08, 2023 |
| Dell          | Latitude 3190               | [7be68f9c9a](https://linux-hardware.org/?probe=7be68f9c9a) | Sep 06, 2023 |
| Apple         | MacBookPro8,1               | [2e3c70287a](https://linux-hardware.org/?probe=2e3c70287a) | Aug 30, 2023 |
| Dell          | Latitude 3190               | [6e16da127a](https://linux-hardware.org/?probe=6e16da127a) | Aug 29, 2023 |
| Dell          | Latitude 3190               | [61ddf042df](https://linux-hardware.org/?probe=61ddf042df) | Aug 22, 2023 |
| Dell          | Latitude E6430              | [27d598d911](https://linux-hardware.org/?probe=27d598d911) | Aug 18, 2023 |
| Samsung       | RF511/RF411/RF711           | [b9134a5ee3](https://linux-hardware.org/?probe=b9134a5ee3) | Aug 16, 2023 |
| Beelink       | Gemini X                    | [d5c4e54794](https://linux-hardware.org/?probe=d5c4e54794) | Aug 14, 2023 |
| Dell          | Vostro 15-3568              | [b422d7c8cc](https://linux-hardware.org/?probe=b422d7c8cc) | Aug 12, 2023 |
| Toshiba       | Satellite T110              | [8180105119](https://linux-hardware.org/?probe=8180105119) | Aug 11, 2023 |
| Dell          | Inspiron 5415               | [69123aa283](https://linux-hardware.org/?probe=69123aa283) | Aug 10, 2023 |
| Dell          | Inspiron 5415               | [9c28979b9d](https://linux-hardware.org/?probe=9c28979b9d) | Aug 10, 2023 |
| Dell          | Latitude E6540              | [758d587fbb](https://linux-hardware.org/?probe=758d587fbb) | Aug 10, 2023 |
| ASUSTek       | UL30A                       | [11f3b9cfad](https://linux-hardware.org/?probe=11f3b9cfad) | Aug 08, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [f30c6c7bb5](https://linux-hardware.org/?probe=f30c6c7bb5) | Aug 08, 2023 |
| HP            | Laptop 15-dy2xxx            | [5777798e8f](https://linux-hardware.org/?probe=5777798e8f) | Aug 07, 2023 |
| ASUSTek       | ProArt StudioBook W5600Q... | [96211a5c87](https://linux-hardware.org/?probe=96211a5c87) | Aug 05, 2023 |
| Dell          | Latitude E6320              | [9b42be4945](https://linux-hardware.org/?probe=9b42be4945) | Aug 02, 2023 |
| Dell          | Latitude 3190               | [c88a2ad597](https://linux-hardware.org/?probe=c88a2ad597) | Aug 01, 2023 |
| Lenovo        | 3000 C100 07612GU           | [3941ecc4f2](https://linux-hardware.org/?probe=3941ecc4f2) | Aug 01, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [095890a440](https://linux-hardware.org/?probe=095890a440) | Jul 31, 2023 |
| Dell          | Latitude 5340               | [5ab5c25167](https://linux-hardware.org/?probe=5ab5c25167) | Jul 28, 2023 |
| Dell          | Inspiron 3583               | [e235fb3a23](https://linux-hardware.org/?probe=e235fb3a23) | Jul 26, 2023 |
| Dell          | Latitude 3190               | [b1730d834d](https://linux-hardware.org/?probe=b1730d834d) | Jul 25, 2023 |
| Dell          | Latitude 3510               | [e1eb8b885c](https://linux-hardware.org/?probe=e1eb8b885c) | Jul 21, 2023 |
| Dell          | Latitude 5530               | [235731a6f1](https://linux-hardware.org/?probe=235731a6f1) | Jul 20, 2023 |
| Dell          | Latitude 5310               | [5b81040709](https://linux-hardware.org/?probe=5b81040709) | Jul 20, 2023 |
| Dell          | Precision 5510              | [ff4ea6ba94](https://linux-hardware.org/?probe=ff4ea6ba94) | Jul 17, 2023 |
| Sony          | VGN-S3HP                    | [6e2c92c447](https://linux-hardware.org/?probe=6e2c92c447) | Jul 17, 2023 |
| Dell          | Latitude 5530               | [37681b3327](https://linux-hardware.org/?probe=37681b3327) | Jul 17, 2023 |
| Dell          | Precision 3571              | [2123567cb0](https://linux-hardware.org/?probe=2123567cb0) | Jul 16, 2023 |
| Dell          | Latitude 3190               | [f067ca0dbf](https://linux-hardware.org/?probe=f067ca0dbf) | Jul 11, 2023 |
| Dell          | Latitude 3190               | [b895b6dced](https://linux-hardware.org/?probe=b895b6dced) | Jul 04, 2023 |
| Dell          | Latitude 3190               | [5f68b5235f](https://linux-hardware.org/?probe=5f68b5235f) | Jun 27, 2023 |
| ASUSTek       | N56VB                       | [f47c68a2a7](https://linux-hardware.org/?probe=f47c68a2a7) | Jun 04, 2023 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 6.1.0-21-amd64           | 25        | 8.83%   |
| 6.1.0-17-amd64           | 20        | 7.07%   |
| 6.1.0-13-amd64           | 20        | 7.07%   |
| 6.1.0-10-amd64           | 20        | 7.07%   |
| 6.1.0-25-amd64           | 17        | 6.01%   |
| 6.1.0-26-amd64           | 15        | 5.3%    |
| 6.4.0-1mx-ahs-amd64      | 14        | 4.95%   |
| 6.5.0-1mx-ahs-amd64      | 13        | 4.59%   |
| 6.1.0-23-amd64           | 13        | 4.59%   |
| 6.1.0-18-amd64           | 9         | 3.18%   |
| 6.6.12-1-liquorix-amd64  | 8         | 2.83%   |
| 6.1.0-9-amd64            | 8         | 2.83%   |
| 6.1.0-28-amd64           | 7         | 2.47%   |
| 6.1.0-20-amd64           | 7         | 2.47%   |
| 6.1.0-17-686-pae         | 6         | 2.12%   |
| 6.8.9-3-liquorix-amd64   | 5         | 1.77%   |
| 6.1.0-12-amd64           | 5         | 1.77%   |
| 6.1.0-27-amd64           | 4         | 1.41%   |
| 6.1.0-22-amd64           | 4         | 1.41%   |
| 6.1.0-15-amd64           | 4         | 1.41%   |
| 6.10.10-1-liquorix-amd64 | 3         | 1.06%   |
| 6.1.0-16-amd64           | 3         | 1.06%   |
| 6.1.0-11-amd64           | 3         | 1.06%   |
| 6.9.12-2-liquorix-amd64  | 2         | 0.71%   |
| 6.7.5-1-liquorix-amd64   | 2         | 0.71%   |
| 6.6.9-1-liquorix-amd64   | 2         | 0.71%   |
| 6.6.11-amd64             | 2         | 0.71%   |
| 6.4.9-1-liquorix-amd64   | 2         | 0.71%   |
| 6.3.0-2mx-ahs-amd64      | 2         | 0.71%   |
| 6.12.6-1-liquorix-amd64  | 2         | 0.71%   |
| 6.11.10-1-liquorix-amd64 | 2         | 0.71%   |
| 6.1.0-28-686-pae         | 2         | 0.71%   |
| 6.1.0-21-686-pae         | 2         | 0.71%   |
| 6.1.0-10-686-pae         | 2         | 0.71%   |
| 6.9.7-1-liquorix-amd64   | 1         | 0.35%   |
| 6.9.7+bpo-amd64          | 1         | 0.35%   |
| 6.9.12-1-liquorix-amd64  | 1         | 0.35%   |
| 6.8.9-5-liquorix-amd64   | 1         | 0.35%   |
| 6.8.10-2-liquorix-amd64  | 1         | 0.35%   |
| 6.7.6-1-liquorix-amd64   | 1         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 6.1.0    | 189       | 70.79%  |
| 6.4.0    | 16        | 5.99%   |
| 6.5.0    | 13        | 4.87%   |
| 6.6.12   | 8         | 3%      |
| 6.8.9    | 6         | 2.25%   |
| 6.9.12   | 3         | 1.12%   |
| 6.10.10  | 3         | 1.12%   |
| 6.9.7    | 2         | 0.75%   |
| 6.7.5    | 2         | 0.75%   |
| 6.6.9    | 2         | 0.75%   |
| 6.6.11   | 2         | 0.75%   |
| 6.4.9    | 2         | 0.75%   |
| 6.3.0    | 2         | 0.75%   |
| 6.12.6   | 2         | 0.75%   |
| 6.11.10  | 2         | 0.75%   |
| 6.8.10   | 1         | 0.37%   |
| 6.7.6    | 1         | 0.37%   |
| 6.7.12   | 1         | 0.37%   |
| 6.7.11   | 1         | 0.37%   |
| 6.5.10   | 1         | 0.37%   |
| 6.2.14   | 1         | 0.37%   |
| 6.11.9   | 1         | 0.37%   |
| 6.11.7   | 1         | 0.37%   |
| 6.11.4   | 1         | 0.37%   |
| 6.10.6   | 1         | 0.37%   |
| 6.10.11  | 1         | 0.37%   |
| 6.1.77   | 1         | 0.37%   |
| 5.10.197 | 1         | 0.37%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.1     | 190       | 71.43%  |
| 6.4     | 18        | 6.77%   |
| 6.5     | 14        | 5.26%   |
| 6.6     | 12        | 4.51%   |
| 6.8     | 7         | 2.63%   |
| 6.9     | 5         | 1.88%   |
| 6.11    | 5         | 1.88%   |
| 6.10    | 5         | 1.88%   |
| 6.7     | 4         | 1.5%    |
| 6.3     | 2         | 0.75%   |
| 6.12    | 2         | 0.75%   |
| 6.2     | 1         | 0.38%   |
| 5.10    | 1         | 0.38%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 245       | 93.51%  |
| i686   | 17        | 6.49%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| XFCE            | 185       | 70.08%  |
| KDE5            | 67        | 25.38%  |
| fluxbox         | 7         | 2.65%   |
| X-Cinnamon      | 2         | 0.76%   |
| LXQt            | 1         | 0.38%   |
| GNOME Flashback | 1         | 0.38%   |
| GNOME           | 1         | 0.38%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 253       | 96.56%  |
| Wayland | 7         | 2.67%   |
| Tty     | 2         | 0.76%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| LightDM | 200       | 76.05%  |
| SDDM    | 62        | 23.57%  |
| GDM3    | 1         | 0.38%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 129       | 48.86%  |
| de_DE   | 23        | 8.71%   |
| it_IT   | 15        | 5.68%   |
| pl_PL   | 12        | 4.55%   |
| en_GB   | 12        | 4.55%   |
| fr_FR   | 9         | 3.41%   |
| ru_RU   | 7         | 2.65%   |
| en_CA   | 6         | 2.27%   |
| hu_HU   | 5         | 1.89%   |
| en_AU   | 5         | 1.89%   |
| pt_BR   | 4         | 1.52%   |
| tr_TR   | 3         | 1.14%   |
| es_ES   | 3         | 1.14%   |
| el_GR   | 3         | 1.14%   |
| nl_NL   | 2         | 0.76%   |
| fr_CH   | 2         | 0.76%   |
| es_VE   | 2         | 0.76%   |
| es_MX   | 2         | 0.76%   |
| en_IE   | 2         | 0.76%   |
| de_AT   | 2         | 0.76%   |
| C       | 2         | 0.76%   |
| zh_TW   | 1         | 0.38%   |
| zh_CN   | 1         | 0.38%   |
| uk_UA   | 1         | 0.38%   |
| sk_SK   | 1         | 0.38%   |
| nb_NO   | 1         | 0.38%   |
| ja_JP   | 1         | 0.38%   |
| hr_HR   | 1         | 0.38%   |
| fi_FI   | 1         | 0.38%   |
| es_US   | 1         | 0.38%   |
| es_CO   | 1         | 0.38%   |
| en_NZ   | 1         | 0.38%   |
| en_IL   | 1         | 0.38%   |
| bg_BG   | 1         | 0.38%   |
| Unknown | 1         | 0.38%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 195       | 74.43%  |
| BIOS | 67        | 25.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 220       | 83.97%  |
| Overlay | 29        | 11.07%  |
| Btrfs   | 11        | 4.2%    |
| Tmpfs   | 1         | 0.38%   |
| F2fs    | 1         | 0.38%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type | Notebooks | Percent |
|------|-----------|---------|
| GPT  | 206       | 78.33%  |
| MBR  | 57        | 21.67%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 223       | 85.11%  |
| Yes       | 39        | 14.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 180       | 68.18%  |
| Yes       | 84        | 31.82%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Hewlett-Packard      | 53        | 20.23%  |
| Lenovo               | 51        | 19.47%  |
| Dell                 | 48        | 18.32%  |
| ASUSTek Computer     | 29        | 11.07%  |
| Acer                 | 16        | 6.11%   |
| Apple                | 14        | 5.34%   |
| Toshiba              | 7         | 2.67%   |
| Samsung Electronics  | 5         | 1.91%   |
| Google               | 5         | 1.91%   |
| Sony                 | 4         | 1.53%   |
| MSI                  | 3         | 1.15%   |
| Medion               | 2         | 0.76%   |
| HONOR                | 2         | 0.76%   |
| GPU Company          | 2         | 0.76%   |
| Fujitsu Siemens      | 2         | 0.76%   |
| Unknown              | 2         | 0.76%   |
| youyeetoo            | 1         | 0.38%   |
| VIT                  | 1         | 0.38%   |
| TECNO Mobile Limited | 1         | 0.38%   |
| System76             | 1         | 0.38%   |
| SGIN                 | 1         | 0.38%   |
| Semp Toshiba         | 1         | 0.38%   |
| Razer                | 1         | 0.38%   |
| PC Specialist        | 1         | 0.38%   |
| Mediacom             | 1         | 0.38%   |
| Inter Sales A/S      | 1         | 0.38%   |
| Insyde               | 1         | 0.38%   |
| I-life               | 1         | 0.38%   |
| Gateway              | 1         | 0.38%   |
| Framework            | 1         | 0.38%   |
| Beelink              | 1         | 0.38%   |
| AMI                  | 1         | 0.38%   |
| Alienware            | 1         | 0.38%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| HP Notebook                         | 4         | 1.53%   |
| Unknown                             | 3         | 1.15%   |
| HP ProBook 455 G8 Notebook PC       | 2         | 0.76%   |
| HP Pavilion g6                      | 2         | 0.76%   |
| HP Pavilion dv6                     | 2         | 0.76%   |
| HP EliteBook 840 G6                 | 2         | 0.76%   |
| HP 255 15.6 inch G9 Notebook PC     | 2         | 0.76%   |
| HP 250 G1                           | 2         | 0.76%   |
| HP 250 15.6 inch G9 Notebook PC     | 2         | 0.76%   |
| Dell Latitude E6440                 | 2         | 0.76%   |
| Dell Latitude E6430                 | 2         | 0.76%   |
| Dell Latitude E6410                 | 2         | 0.76%   |
| Dell Latitude 5530                  | 2         | 0.76%   |
| ASUS T100TA                         | 2         | 0.76%   |
| Apple MacBookPro7,1                 | 2         | 0.76%   |
| Acer Aspire A315-510P               | 2         | 0.76%   |
| youyeetoo X1 SBC                    | 1         | 0.38%   |
| VIT P3400                           | 1         | 0.38%   |
| Toshiba Satellite P875              | 1         | 0.38%   |
| Toshiba Satellite P870              | 1         | 0.38%   |
| Toshiba Satellite C55D-B            | 1         | 0.38%   |
| Toshiba Satellite C55-A             | 1         | 0.38%   |
| Toshiba Satellite C50-B             | 1         | 0.38%   |
| Toshiba PORTEGE X30-E               | 1         | 0.38%   |
| Toshiba dynabook T552/36GB          | 1         | 0.38%   |
| TECNO Mobile Limited MEGABOOK T14TA | 1         | 0.38%   |
| System76 Serval WS                  | 1         | 0.38%   |
| Sony VGN-S3HP                       | 1         | 0.38%   |
| Sony VGN-FZ11M                      | 1         | 0.38%   |
| Sony SVF1521H1EW                    | 1         | 0.38%   |
| Sony SVF1521A6EW                    | 1         | 0.38%   |
| SGIN M15                            | 1         | 0.38%   |
| Semp Toshiba IS 1413G               | 1         | 0.38%   |
| Samsung RF511/RF411/RF711           | 1         | 0.38%   |
| Samsung N150/N210/N220              | 1         | 0.38%   |
| Samsung 750XDA                      | 1         | 0.38%   |
| Samsung 730U3E/740U3E               | 1         | 0.38%   |
| Samsung 305E4A/305E5A/305E7A        | 1         | 0.38%   |
| Razer Blade 18 - RZ09-0509          | 1         | 0.38%   |
| PC Specialist Lafite Pro III 17     | 1         | 0.38%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                          | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 25        | 9.54%   |
| Dell Latitude                 | 24        | 9.16%   |
| ASUS Vivobook                 | 15        | 5.73%   |
| Acer Aspire                   | 13        | 4.96%   |
| Lenovo IdeaPad                | 11        | 4.2%    |
| HP Pavilion                   | 11        | 4.2%    |
| HP ProBook                    | 7         | 2.67%   |
| HP Laptop                     | 7         | 2.67%   |
| HP EliteBook                  | 7         | 2.67%   |
| Dell XPS                      | 7         | 2.67%   |
| Dell Inspiron                 | 7         | 2.67%   |
| Toshiba Satellite             | 5         | 1.91%   |
| HP Notebook                   | 4         | 1.53%   |
| HP 255                        | 4         | 1.53%   |
| HP 250                        | 4         | 1.53%   |
| Dell Vostro                   | 4         | 1.53%   |
| Apple MacBookPro5             | 4         | 1.53%   |
| Dell Precision                | 3         | 1.15%   |
| Unknown                       | 3         | 1.15%   |
| Lenovo Yoga                   | 2         | 0.76%   |
| Lenovo LOQ                    | 2         | 0.76%   |
| Lenovo Legion                 | 2         | 0.76%   |
| Lenovo 3000                   | 2         | 0.76%   |
| HP ENVY                       | 2         | 0.76%   |
| HP Compaq                     | 2         | 0.76%   |
| Fujitsu Siemens AMILO         | 2         | 0.76%   |
| Dell System                   | 2         | 0.76%   |
| ASUS T100TA                   | 2         | 0.76%   |
| Apple MacBookPro8             | 2         | 0.76%   |
| Apple MacBookPro7             | 2         | 0.76%   |
| youyeetoo X1                  | 1         | 0.38%   |
| VIT P3400                     | 1         | 0.38%   |
| Toshiba PORTEGE               | 1         | 0.38%   |
| Toshiba dynabook              | 1         | 0.38%   |
| TECNO Mobile Limited MEGABOOK | 1         | 0.38%   |
| System76 Serval               | 1         | 0.38%   |
| Sony VGN-S3HP                 | 1         | 0.38%   |
| Sony VGN-FZ11M                | 1         | 0.38%   |
| Sony SVF1521H1EW              | 1         | 0.38%   |
| Sony SVF1521A6EW              | 1         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2023 | 26        | 9.92%   |
| 2022 | 26        | 9.92%   |
| 2021 | 26        | 9.92%   |
| 2013 | 25        | 9.54%   |
| 2019 | 17        | 6.49%   |
| 2018 | 16        | 6.11%   |
| 2016 | 15        | 5.73%   |
| 2011 | 14        | 5.34%   |
| 2009 | 14        | 5.34%   |
| 2012 | 12        | 4.58%   |
| 2020 | 10        | 3.82%   |
| 2015 | 9         | 3.44%   |
| 2014 | 9         | 3.44%   |
| 2010 | 9         | 3.44%   |
| 2008 | 9         | 3.44%   |
| 2024 | 7         | 2.67%   |
| 2007 | 7         | 2.67%   |
| 2017 | 6         | 2.29%   |
| 2006 | 4         | 1.53%   |
| 2005 | 1         | 0.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 262       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 254       | 96.95%  |
| Enabled  | 8         | 3.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 256       | 97.71%  |
| Yes  | 6         | 2.29%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 78        | 29.77%  |
| 3.01-4.0    | 44        | 16.79%  |
| 8.01-16.0   | 43        | 16.41%  |
| 16.01-24.0  | 36        | 13.74%  |
| 32.01-64.0  | 28        | 10.69%  |
| 1.01-2.0    | 17        | 6.49%   |
| 2.01-3.0    | 7         | 2.67%   |
| 64.01-256.0 | 4         | 1.53%   |
| 24.01-32.0  | 3         | 1.15%   |
| 0.51-1.0    | 2         | 0.76%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 107       | 39.48%  |
| 1.01-2.0   | 94        | 34.69%  |
| 4.01-8.0   | 33        | 12.18%  |
| 3.01-4.0   | 29        | 10.7%   |
| 0.51-1.0   | 5         | 1.85%   |
| 8.01-16.0  | 2         | 0.74%   |
| 16.01-24.0 | 1         | 0.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 209       | 79.47%  |
| 2      | 46        | 17.49%  |
| 3      | 7         | 2.66%   |
| 4      | 1         | 0.38%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 187       | 71.37%  |
| Yes       | 75        | 28.63%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 199       | 75.95%  |
| No        | 63        | 24.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 244       | 93.13%  |
| No        | 18        | 6.87%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 208       | 79.09%  |
| No        | 55        | 20.91%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| USA         | 54        | 20.45%  |
| Germany     | 29        | 10.98%  |
| Greece      | 15        | 5.68%   |
| Poland      | 14        | 5.3%    |
| Italy       | 14        | 5.3%    |
| UK          | 10        | 3.79%   |
| Russia      | 10        | 3.79%   |
| Canada      | 10        | 3.79%   |
| France      | 9         | 3.41%   |
| Brazil      | 8         | 3.03%   |
| Australia   | 6         | 2.27%   |
| Turkey      | 5         | 1.89%   |
| Mexico      | 5         | 1.89%   |
| Netherlands | 4         | 1.52%   |
| India       | 4         | 1.52%   |
| Hungary     | 4         | 1.52%   |
| Spain       | 3         | 1.14%   |
| Serbia      | 3         | 1.14%   |
| Romania     | 3         | 1.14%   |
| Egypt       | 3         | 1.14%   |
| Venezuela   | 2         | 0.76%   |
| Thailand    | 2         | 0.76%   |
| Switzerland | 2         | 0.76%   |
| Sweden      | 2         | 0.76%   |
| Portugal    | 2         | 0.76%   |
| Norway      | 2         | 0.76%   |
| Japan       | 2         | 0.76%   |
| Israel      | 2         | 0.76%   |
| Ireland     | 2         | 0.76%   |
| Indonesia   | 2         | 0.76%   |
| Colombia    | 2         | 0.76%   |
| Austria     | 2         | 0.76%   |
| Argentina   | 2         | 0.76%   |
| Algeria     | 2         | 0.76%   |
| Ukraine     | 1         | 0.38%   |
| Türkiye    | 1         | 0.38%   |
| Taiwan      | 1         | 0.38%   |
| Slovakia    | 1         | 0.38%   |
| Singapore   | 1         | 0.38%   |
| Philippines | 1         | 0.38%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Athens         | 11        | 4.09%   |
| Moscow         | 5         | 1.86%   |
| Paris          | 4         | 1.49%   |
| Milan          | 4         | 1.49%   |
| Warsaw         | 3         | 1.12%   |
| Sydney         | 3         | 1.12%   |
| Seattle        | 3         | 1.12%   |
| Otwock         | 3         | 1.12%   |
| Krakow         | 3         | 1.12%   |
| Budapest       | 3         | 1.12%   |
| Stuttgart      | 2         | 0.74%   |
| St Petersburg  | 2         | 0.74%   |
| Salt Lake City | 2         | 0.74%   |
| Salamina       | 2         | 0.74%   |
| Rio de Janeiro | 2         | 0.74%   |
| Ravensburg     | 2         | 0.74%   |
| Oslo           | 2         | 0.74%   |
| Mexico City    | 2         | 0.74%   |
| Los Angeles    | 2         | 0.74%   |
| London         | 2         | 0.74%   |
| Le Haillan     | 2         | 0.74%   |
| Florence       | 2         | 0.74%   |
| Dublin         | 2         | 0.74%   |
| Cairo          | 2         | 0.74%   |
| Bengaluru      | 2         | 0.74%   |
| Bangkok        | 2         | 0.74%   |
| Zagreb         | 1         | 0.37%   |
| Yokohama       | 1         | 0.37%   |
| Yeovil         | 1         | 0.37%   |
| Yekaterinburg  | 1         | 0.37%   |
| Września      | 1         | 0.37%   |
| Woodbridge     | 1         | 0.37%   |
| Winston-Salem  | 1         | 0.37%   |
| Willoughby     | 1         | 0.37%   |
| Weston         | 1         | 0.37%   |
| Westminster    | 1         | 0.37%   |
| Wandsworth     | 1         | 0.37%   |
| Vranje         | 1         | 0.37%   |
| Vlotho         | 1         | 0.37%   |
| Vitebsk        | 1         | 0.37%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 51        | 55     | 16.04%  |
| WDC                          | 27        | 31     | 8.49%   |
| SanDisk                      | 27        | 30     | 8.49%   |
| Seagate                      | 21        | 23     | 6.6%    |
| Unknown                      | 16        | 20     | 5.03%   |
| SK hynix                     | 15        | 15     | 4.72%   |
| Toshiba                      | 13        | 13     | 4.09%   |
| Kingston                     | 13        | 13     | 4.09%   |
| Intel                        | 13        | 15     | 4.09%   |
| Crucial                      | 13        | 26     | 4.09%   |
| Micron Technology            | 10        | 11     | 3.14%   |
| Unknown                      | 8         | 8      | 2.52%   |
| KIOXIA                       | 7         | 8      | 2.2%    |
| China                        | 7         | 9      | 2.2%    |
| Hitachi                      | 6         | 6      | 1.89%   |
| HGST                         | 5         | 7      | 1.57%   |
| Apple                        | 5         | 5      | 1.57%   |
| Fujitsu                      | 4         | 4      | 1.26%   |
| SPCC                         | 3         | 3      | 0.94%   |
| LITEONIT                     | 3         | 3      | 0.94%   |
| Intenso                      | 3         | 3      | 0.94%   |
| A-DATA Technology            | 3         | 3      | 0.94%   |
| Verbatim                     | 2         | 2      | 0.63%   |
| UMIS                         | 2         | 2      | 0.63%   |
| PNY                          | 2         | 2      | 0.63%   |
| Phison Electronics           | 2         | 2      | 0.63%   |
| Patriot                      | 2         | 2      | 0.63%   |
| Netac                        | 2         | 2      | 0.63%   |
| Kingston Technology Company  | 2         | 2      | 0.63%   |
| FORESEE                      | 2         | 2      | 0.63%   |
| Fanxiang                     | 2         | 3      | 0.63%   |
| WALRAM                       | 1         | 1      | 0.31%   |
| V-GeN                        | 1         | 1      | 0.31%   |
| Transcend                    | 1         | 1      | 0.31%   |
| Timetec                      | 1         | 1      | 0.31%   |
| Team                         | 1         | 1      | 0.31%   |
| Super Talent                 | 1         | 1      | 0.31%   |
| SSSTC                        | 1         | 1      | 0.31%   |
| Silicon Motion               | 1         | 1      | 0.31%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.31%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown                                             | 8         | 2.45%   |
| SanDisk NVMe SSD Drive 512GB                        | 7         | 2.15%   |
| Toshiba MQ01ABF050 500GB                            | 4         | 1.23%   |
| Kingston SA400S37240G 240GB SSD                     | 4         | 1.23%   |
| Toshiba MQ01ABD100 1TB                              | 3         | 0.92%   |
| Samsung SSD 870 EVO 500GB                           | 3         | 0.92%   |
| Samsung MZVL4512HBLU-00BTW 512GB                    | 3         | 0.92%   |
| Samsung MZALQ512HBLU-00BL2 512GB                    | 3         | 0.92%   |
| Intel SSDPEKNU512GZ 512GB                           | 3         | 0.92%   |
| WDC WD10JPVX-60JC3T0 1TB                            | 2         | 0.61%   |
| WDC PC SN810 NVMe 1024GB                            | 2         | 0.61%   |
| SK hynix HCG8e  64GB                                | 2         | 0.61%   |
| SK hynix HBG4e  32GB                                | 2         | 0.61%   |
| SK hynix BC711 NVMe 256GB                           | 2         | 0.61%   |
| Seagate ST9500325AS 500GB                           | 2         | 0.61%   |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 2         | 0.61%   |
| Seagate ST500LM000-1EJ162 500GB                     | 2         | 0.61%   |
| Seagate ST320LT012-9WS14C 320GB                     | 2         | 0.61%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 0.61%   |
| SanDisk NVMe SSD Drive 2TB                          | 2         | 0.61%   |
| SanDisk NVMe SSD Drive 256GB                        | 2         | 0.61%   |
| SanDisk NVMe SSD Drive 1TB                          | 2         | 0.61%   |
| Samsung SSD 970 EVO Plus 2TB                        | 2         | 0.61%   |
| Samsung SSD 850 PRO 256GB                           | 2         | 0.61%   |
| Samsung SSD 850 EVO 250GB                           | 2         | 0.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 2         | 0.61%   |
| Samsung MZVLB256HBHQ-000L2 256GB                    | 2         | 0.61%   |
| Samsung MZAL4512HBLU-00BL2 512GB                    | 2         | 0.61%   |
| Samsung HM250HI 250GB                               | 2         | 0.61%   |
| Micron MTFDKCD512TFK 512GB                          | 2         | 0.61%   |
| Micron 2450_MTFDKBA512TFK 512GB                     | 2         | 0.61%   |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 0.61%   |
| Intel SSDPEKNW010T8 1TB                             | 2         | 0.61%   |
| HGST HTS721010A9E630 1TB                            | 2         | 0.61%   |
| HGST HTS545050A7E680 500GB                          | 2         | 0.61%   |
| Crucial CT500P3SSD8 500GB                           | 2         | 0.61%   |
| Crucial CT1000P3SSD8 1TB                            | 2         | 0.61%   |
| China SSD 256GB                                     | 2         | 0.61%   |
| China SSD 240GB                                     | 2         | 0.61%   |
| WDC WDS250G2B0A-00SM50 250GB SSD                    | 1         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 22     | 32.81%  |
| WDC                 | 13        | 15     | 20.31%  |
| Toshiba             | 11        | 11     | 17.19%  |
| Hitachi             | 6         | 6      | 9.38%   |
| HGST                | 5         | 7      | 7.81%   |
| Fujitsu             | 4         | 4      | 6.25%   |
| Samsung Electronics | 3         | 3      | 4.69%   |
| External            | 1         | 1      | 1.56%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 19        | 21     | 18.27%  |
| Kingston            | 10        | 10     | 9.62%   |
| SanDisk             | 9         | 9      | 8.65%   |
| Crucial             | 7         | 19     | 6.73%   |
| China               | 7         | 9      | 6.73%   |
| WDC                 | 6         | 6      | 5.77%   |
| Apple               | 4         | 4      | 3.85%   |
| Micron Technology   | 3         | 4      | 2.88%   |
| LITEONIT            | 3         | 3      | 2.88%   |
| Intenso             | 3         | 3      | 2.88%   |
| Intel               | 3         | 3      | 2.88%   |
| A-DATA Technology   | 3         | 3      | 2.88%   |
| Verbatim            | 2         | 2      | 1.92%   |
| SPCC                | 2         | 2      | 1.92%   |
| Patriot             | 2         | 2      | 1.92%   |
| Netac               | 2         | 2      | 1.92%   |
| WALRAM              | 1         | 1      | 0.96%   |
| Transcend           | 1         | 1      | 0.96%   |
| Super Talent        | 1         | 1      | 0.96%   |
| Seagate             | 1         | 1      | 0.96%   |
| PNY                 | 1         | 1      | 0.96%   |
| OCZ                 | 1         | 1      | 0.96%   |
| MG                  | 1         | 1      | 0.96%   |
| LITEON              | 1         | 1      | 0.96%   |
| Gigabyte Technology | 1         | 1      | 0.96%   |
| GeIL                | 1         | 1      | 0.96%   |
| FORESEE             | 1         | 1      | 0.96%   |
| Fanxiang            | 1         | 1      | 0.96%   |
| Emtec               | 1         | 1      | 0.96%   |
| CF400               | 1         | 1      | 0.96%   |
| ASMT109x            | 1         | 1      | 0.96%   |
| addlink             | 1         | 1      | 0.96%   |
| Acer                | 1         | 1      | 0.96%   |
| 2.5"                | 1         | 1      | 0.96%   |
| Unknown             | 1         | 1      | 0.96%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 112       | 134    | 37.58%  |
| SSD     | 97        | 121    | 32.55%  |
| HDD     | 63        | 69     | 21.14%  |
| MMC     | 25        | 32     | 8.39%   |
| Unknown | 1         | 1      | 0.34%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 140       | 181    | 48.95%  |
| NVMe | 111       | 133    | 38.81%  |
| MMC  | 25        | 32     | 8.74%   |
| SAS  | 10        | 11     | 3.5%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 108       | 128    | 70.59%  |
| 0.51-1.0   | 38        | 54     | 24.84%  |
| 1.01-2.0   | 5         | 6      | 3.27%   |
| 3.01-4.0   | 1         | 1      | 0.65%   |
| 10.01-20.0 | 1         | 1      | 0.65%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 87        | 32.58%  |
| 251-500        | 54        | 20.22%  |
| 1-20           | 41        | 15.36%  |
| 501-1000       | 31        | 11.61%  |
| 51-100         | 24        | 8.99%   |
| 21-50          | 18        | 6.74%   |
| 1001-2000      | 9         | 3.37%   |
| More than 3000 | 3         | 1.12%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 141       | 52.81%  |
| 21-50          | 51        | 19.1%   |
| 51-100         | 26        | 9.74%   |
| 101-250        | 25        | 9.36%   |
| 251-500        | 12        | 4.49%   |
| 501-1000       | 6         | 2.25%   |
| 1001-2000      | 4         | 1.5%    |
| More than 3000 | 2         | 0.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 4.76%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 4.76%   |
| Seagate ST500LM000-1EJ162 500GB       | 2         | 2      | 4.76%   |
| HGST HTS545050A7E680 500GB            | 2         | 2      | 4.76%   |
| WDC WD32 00BEKT-75PVMT0 320GB         | 1         | 1      | 2.38%   |
| WDC WD1600BEKT-75PVMT0 160GB          | 1         | 1      | 2.38%   |
| WDC WD Green 2.5 240GB SSD            | 1         | 1      | 2.38%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 2.38%   |
| Toshiba MQ01ABD050 500GB              | 1         | 1      | 2.38%   |
| Toshiba MK8009GAH 80GB                | 1         | 1      | 2.38%   |
| Seagate ST9320423AS 320GB             | 1         | 1      | 2.38%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 1         | 1      | 2.38%   |
| Seagate ST320LT012-9WS14C 320GB       | 1         | 1      | 2.38%   |
| Seagate ST320LT009-9WC142 320GB       | 1         | 1      | 2.38%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 2.38%   |
| SanDisk SSD PLUS 480GB                | 1         | 1      | 2.38%   |
| SanDisk SSD PLUS 1000GB               | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 970 EVO 500GB | 1         | 1      | 2.38%   |
| Samsung Electronics SSD 870 EVO 250GB | 1         | 2      | 2.38%   |
| Samsung Electronics HM321HI 320GB     | 1         | 1      | 2.38%   |
| Samsung Electronics HM250HI 250GB     | 1         | 1      | 2.38%   |
| Netac SSD 512GB                       | 1         | 1      | 2.38%   |
| Netac SSD 240GB                       | 1         | 1      | 2.38%   |
| LITEONIT L8T-256L6G-HP 256GB SSD      | 1         | 1      | 2.38%   |
| Intel SSDSC2BF180A4H 180GB            | 1         | 1      | 2.38%   |
| Intel SSDSA1M160G2LE 160GB            | 1         | 1      | 2.38%   |
| Hitachi HTS722010K9SA00 100GB         | 1         | 1      | 2.38%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 2.38%   |
| Hitachi HTS542525K9SA00 250GB         | 1         | 1      | 2.38%   |
| Hitachi HTS541612J9SA00 120GB         | 1         | 1      | 2.38%   |
| Hitachi HTS541080G9AT00 80GB          | 1         | 1      | 2.38%   |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 2.38%   |
| HGST HTS545050A7E380 500GB            | 1         | 3      | 2.38%   |
| Fujitsu MHZ2320BH G2 320GB            | 1         | 1      | 2.38%   |
| Fujitsu MHW2120BJ G2 120GB            | 1         | 1      | 2.38%   |
| Crucial CT1000MX500SSD4 1TB           | 1         | 12     | 2.38%   |
| China SSD 240GB                       | 1         | 1      | 2.38%   |
| China SSD 128GB                       | 1         | 1      | 2.38%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 21.43%  |
| Toshiba             | 5         | 5      | 11.9%   |
| Hitachi             | 5         | 5      | 11.9%   |
| Samsung Electronics | 4         | 5      | 9.52%   |
| HGST                | 4         | 6      | 9.52%   |
| WDC                 | 3         | 3      | 7.14%   |
| SanDisk             | 2         | 2      | 4.76%   |
| Netac               | 2         | 2      | 4.76%   |
| Intel               | 2         | 2      | 4.76%   |
| Fujitsu             | 2         | 2      | 4.76%   |
| China               | 2         | 2      | 4.76%   |
| LITEONIT            | 1         | 1      | 2.38%   |
| Crucial             | 1         | 12     | 2.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9         | 9      | 31.03%  |
| Toshiba             | 5         | 5      | 17.24%  |
| Hitachi             | 5         | 5      | 17.24%  |
| HGST                | 4         | 6      | 13.79%  |
| WDC                 | 2         | 2      | 6.9%    |
| Samsung Electronics | 2         | 2      | 6.9%    |
| Fujitsu             | 2         | 2      | 6.9%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 29        | 31     | 69.05%  |
| SSD  | 12        | 24     | 28.57%  |
| NVMe | 1         | 1      | 2.38%   |

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
| Works    | 202       | 241    | 70.14%  |
| Detected | 45        | 60     | 15.63%  |
| Malfunc  | 41        | 56     | 14.24%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 153       | 50.5%   |
| Samsung Electronics              | 31        | 10.23%  |
| AMD                              | 30        | 9.9%    |
| SanDisk                          | 25        | 8.25%   |
| SK hynix                         | 11        | 3.63%   |
| Micron Technology                | 9         | 2.97%   |
| Nvidia                           | 7         | 2.31%   |
| KIOXIA                           | 7         | 2.31%   |
| Kingston Technology Company      | 5         | 1.65%   |
| Silicon Motion                   | 4         | 1.32%   |
| Phison Electronics               | 4         | 1.32%   |
| Micron/Crucial Technology        | 4         | 1.32%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.99%   |
| Union Memory (Shenzhen)          | 2         | 0.66%   |
| Toshiba America Info Systems     | 2         | 0.66%   |
| Shenzhen Longsys Electronics     | 2         | 0.66%   |
| Solid State Storage Technology   | 1         | 0.33%   |
| Silicon Integrated Systems [SiS] | 1         | 0.33%   |
| Realtek Semiconductor            | 1         | 0.33%   |
| Biwin Storage Technology         | 1         | 0.33%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 27        | 8.16%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 17        | 5.14%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 4.53%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 12        | 3.63%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 11        | 3.32%   |
| Intel Volume Management Device NVMe RAID Controller                            | 11        | 3.32%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 9         | 2.72%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 2.42%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 7         | 2.11%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 7         | 2.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 2.11%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 6         | 1.81%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 6         | 1.81%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                  | 6         | 1.81%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 6         | 1.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 6         | 1.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 6         | 1.81%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 5         | 1.51%   |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation          | 5         | 1.51%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 1.51%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 5         | 1.51%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 4         | 1.21%   |
| Nvidia MCP79 AHCI Controller                                                   | 4         | 1.21%   |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 1.21%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 4         | 1.21%   |
| Intel SSD 660P Series                                                          | 4         | 1.21%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 4         | 1.21%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 4         | 1.21%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 4         | 1.21%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 4         | 1.21%   |
| SK hynix BC901 NVMe Solid State Drive (DRAM-less)                              | 3         | 0.91%   |
| Sandisk WD PC SN740 NVMe SSD 512GB (DRAM-less)                                 | 3         | 0.91%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 0.91%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 3         | 0.91%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 3         | 0.91%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 0.91%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 3         | 0.91%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 3         | 0.91%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 3         | 0.91%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 2         | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 154       | 49.2%   |
| NVMe | 109       | 34.82%  |
| RAID | 29        | 9.27%   |
| IDE  | 21        | 6.71%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 200       | 76.34%  |
| AMD    | 62        | 23.66%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| AMD Ryzen 7 5700U with Radeon Graphics   | 7         | 2.67%   |
| Intel 12th Gen Core i5-1235U             | 5         | 1.91%   |
| Intel Core i5-8350U CPU @ 1.70GHz        | 4         | 1.53%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 4         | 1.53%   |
| Intel Core i5 CPU M 560 @ 2.67GHz        | 4         | 1.53%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz  | 4         | 1.53%   |
| Intel Core Ultra 7 155H                  | 3         | 1.15%   |
| Intel Core i9-14900HX                    | 3         | 1.15%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 3         | 1.15%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 3         | 1.15%   |
| Intel Core i5-8365U CPU @ 1.60GHz        | 3         | 1.15%   |
| Intel Core i5-2520M CPU @ 2.50GHz        | 3         | 1.15%   |
| Intel Celeron N4020 CPU @ 1.10GHz        | 3         | 1.15%   |
| Intel Celeron CPU N3350 @ 1.10GHz        | 3         | 1.15%   |
| Intel Atom CPU Z3735F @ 1.33GHz          | 3         | 1.15%   |
| Intel 12th Gen Core i5-12450H            | 3         | 1.15%   |
| Intel 12th Gen Core i3-1215U             | 3         | 1.15%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz  | 3         | 1.15%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz  | 3         | 1.15%   |
| AMD Ryzen 7 5825U with Radeon Graphics   | 3         | 1.15%   |
| AMD Ryzen 5 5500U with Radeon Graphics   | 3         | 1.15%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 2         | 0.76%   |
| Intel Pentium CPU N3710 @ 1.60GHz        | 2         | 0.76%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 2         | 0.76%   |
| Intel Core i7-8650U CPU @ 1.90GHz        | 2         | 0.76%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 2         | 0.76%   |
| Intel Core i7-6600U CPU @ 2.60GHz        | 2         | 0.76%   |
| Intel Core i7-6500U CPU @ 2.50GHz        | 2         | 0.76%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz       | 2         | 0.76%   |
| Intel Core i7-2670QM CPU @ 2.20GHz       | 2         | 0.76%   |
| Intel Core i5-4310M CPU @ 2.70GHz        | 2         | 0.76%   |
| Intel Core i5-4300U CPU @ 1.90GHz        | 2         | 0.76%   |
| Intel Core i5-10210U CPU @ 1.60GHz       | 2         | 0.76%   |
| Intel Core i5 CPU M 540 @ 2.53GHz        | 2         | 0.76%   |
| Intel Core i3-N305                       | 2         | 0.76%   |
| Intel Core i3-7100U CPU @ 2.40GHz        | 2         | 0.76%   |
| Intel Core i3-2330M CPU @ 2.20GHz        | 2         | 0.76%   |
| Intel Core 2 Duo CPU T5870 @ 2.00GHz     | 2         | 0.76%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 2         | 0.76%   |
| Intel Celeron M processor 1.50GHz        | 2         | 0.76%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 44        | 16.79%  |
| Intel Core i7           | 36        | 13.74%  |
| Other                   | 33        | 12.6%   |
| Intel Core 2 Duo        | 19        | 7.25%   |
| Intel Celeron           | 17        | 6.49%   |
| AMD Ryzen 7             | 17        | 6.49%   |
| Intel Core i3           | 13        | 4.96%   |
| AMD Ryzen 5             | 13        | 4.96%   |
| Intel Atom              | 10        | 3.82%   |
| Intel Pentium           | 8         | 3.05%   |
| AMD Ryzen 9             | 5         | 1.91%   |
| AMD Ryzen 3             | 5         | 1.91%   |
| Intel Core              | 4         | 1.53%   |
| Intel Pentium Silver    | 3         | 1.15%   |
| Intel Genuine           | 3         | 1.15%   |
| Intel Core i9           | 3         | 1.15%   |
| AMD A8                  | 3         | 1.15%   |
| AMD A10                 | 3         | 1.15%   |
| Intel Celeron M         | 2         | 0.76%   |
| AMD Ryzen 3 PRO         | 2         | 0.76%   |
| AMD E2                  | 2         | 0.76%   |
| AMD Athlon              | 2         | 0.76%   |
| AMD A6                  | 2         | 0.76%   |
| AMD A4                  | 2         | 0.76%   |
| Intel Xeon              | 1         | 0.38%   |
| Intel Pentium M         | 1         | 0.38%   |
| Intel Pentium Gold      | 1         | 0.38%   |
| Intel Pentium Dual-Core | 1         | 0.38%   |
| Intel Pentium Dual      | 1         | 0.38%   |
| Intel Core Duo          | 1         | 0.38%   |
| Intel Core 2            | 1         | 0.38%   |
| AMD Turion Neo X2       | 1         | 0.38%   |
| AMD Turion 64 X2 Mobile | 1         | 0.38%   |
| AMD Turion 64 X2        | 1         | 0.38%   |
| AMD PRO A8              | 1         | 0.38%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 115       | 43.89%  |
| 4      | 76        | 29.01%  |
| 8      | 28        | 10.69%  |
| 6      | 19        | 7.25%   |
| 10     | 7         | 2.67%   |
| 1      | 5         | 1.91%   |
| 16     | 4         | 1.53%   |
| 24     | 3         | 1.15%   |
| 14     | 2         | 0.76%   |
| 12     | 2         | 0.76%   |
| 5      | 1         | 0.38%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 262       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 176       | 67.18%  |
| 1      | 86        | 32.82%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 256       | 97.71%  |
| 32-bit         | 6         | 2.29%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 68        | 25.76%  |
| 0x206a7    | 18        | 6.82%   |
| 0x306a9    | 12        | 4.55%   |
| 0x1067a    | 10        | 3.79%   |
| 0x30678    | 9         | 3.41%   |
| 0x906a4    | 7         | 2.65%   |
| 0x806ec    | 7         | 2.65%   |
| 0x08608103 | 7         | 2.65%   |
| 0x6fd      | 6         | 2.27%   |
| 0x806c1    | 5         | 1.89%   |
| 0x406c4    | 5         | 1.89%   |
| 0x306c3    | 5         | 1.89%   |
| 0x20655    | 5         | 1.89%   |
| 0x806ea    | 4         | 1.52%   |
| 0x706a1    | 4         | 1.52%   |
| 0x506e3    | 4         | 1.52%   |
| 0x40651    | 4         | 1.52%   |
| 0x306d4    | 4         | 1.52%   |
| 0x0a50000f | 4         | 1.52%   |
| 0x0a50000c | 4         | 1.52%   |
| 0x08108109 | 4         | 1.52%   |
| 0x906a3    | 3         | 1.14%   |
| 0x806e9    | 3         | 1.14%   |
| 0x806c2    | 3         | 1.14%   |
| 0x6d8      | 3         | 1.14%   |
| 0x506c9    | 3         | 1.14%   |
| 0x406e3    | 3         | 1.14%   |
| 0x0600611a | 3         | 1.14%   |
| 0xb06e0    | 2         | 0.76%   |
| 0xb0671    | 2         | 0.76%   |
| 0x906ea    | 2         | 0.76%   |
| 0x706a8    | 2         | 0.76%   |
| 0x6fb      | 2         | 0.76%   |
| 0x6e8      | 2         | 0.76%   |
| 0x10676    | 2         | 0.76%   |
| 0x0a404105 | 2         | 0.76%   |
| 0x06006704 | 2         | 0.76%   |
| 0xb06a3    | 1         | 0.38%   |
| 0xa06a4    | 1         | 0.38%   |
| 0x906c0    | 1         | 0.38%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 28        | 10.69%  |
| Unknown           | 23        | 8.78%   |
| Alderlake Hybrid  | 21        | 8.02%   |
| SandyBridge       | 19        | 7.25%   |
| Silvermont        | 17        | 6.49%   |
| IvyBridge         | 16        | 6.11%   |
| Zen 3             | 14        | 5.34%   |
| Penryn            | 14        | 5.34%   |
| TigerLake         | 13        | 4.96%   |
| Haswell           | 12        | 4.58%   |
| Skylake           | 10        | 3.82%   |
| Core              | 9         | 3.44%   |
| Westmere          | 7         | 2.67%   |
| Goldmont plus     | 7         | 2.67%   |
| Excavator         | 7         | 2.67%   |
| P6                | 6         | 2.29%   |
| Zen+              | 5         | 1.91%   |
| K8 Hammer         | 4         | 1.53%   |
| Goldmont          | 4         | 1.53%   |
| Broadwell         | 4         | 1.53%   |
| Meteorlake Hybrid | 3         | 1.15%   |
| Zen 2             | 2         | 0.76%   |
| Puma              | 2         | 0.76%   |
| IceLake           | 2         | 0.76%   |
| Gracemont         | 2         | 0.76%   |
| Bobcat            | 2         | 0.76%   |
| Zen               | 1         | 0.38%   |
| Tremont           | 1         | 0.38%   |
| Steamroller       | 1         | 0.38%   |
| Piledriver        | 1         | 0.38%   |
| Nehalem           | 1         | 0.38%   |
| K10 Llano         | 1         | 0.38%   |
| Jaguar            | 1         | 0.38%   |
| CometLake         | 1         | 0.38%   |
| Bonnell           | 1         | 0.38%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 183       | 59.03%  |
| AMD    | 74        | 23.87%  |
| Nvidia | 53        | 17.1%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 5.88%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 16        | 4.95%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 11        | 3.41%   |
| AMD Lucienne                                                                             | 11        | 3.41%   |
| Intel UHD Graphics 620                                                                   | 10        | 3.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 10        | 3.1%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 8         | 2.48%   |
| AMD Barcelo                                                                              | 8         | 2.48%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 6         | 1.86%   |
| Intel Core Processor Integrated Graphics Controller                                      | 6         | 1.86%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 6         | 1.86%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 1.55%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 1.55%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 1.55%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 1.55%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 5         | 1.55%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.55%   |
| Nvidia C79 [GeForce 9400M]                                                               | 4         | 1.24%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.24%   |
| Intel Alder Lake-UP3 GT1 [UHD Graphics]                                                  | 4         | 1.24%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 4         | 1.24%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 4         | 1.24%   |
| AMD Phoenix1                                                                             | 4         | 1.24%   |
| Nvidia AD107M [GeForce RTX 4060 Max-Q / Mobile]                                          | 3         | 0.93%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 3         | 0.93%   |
| Intel Raptor Lake-S UHD Graphics                                                         | 3         | 0.93%   |
| Intel Meteor Lake-P [Intel Arc Graphics]                                                 | 3         | 0.93%   |
| Intel HD Graphics 620                                                                    | 3         | 0.93%   |
| Intel HD Graphics 5500                                                                   | 3         | 0.93%   |
| Intel HD Graphics 530                                                                    | 3         | 0.93%   |
| Intel HD Graphics 500                                                                    | 3         | 0.93%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 0.93%   |
| Intel Alder Lake-UP3 GT2 [UHD Graphics]                                                  | 3         | 0.93%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 3         | 0.93%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                                    | 3         | 0.93%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.93%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 3         | 0.93%   |
| AMD Mendocino                                                                            | 3         | 0.93%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 123       | 46.95%  |
| 1 x AMD        | 54        | 20.61%  |
| Intel + Nvidia | 32        | 12.21%  |
| 2 x Intel      | 18        | 6.87%   |
| 1 x Nvidia     | 13        | 4.96%   |
| Intel + AMD    | 10        | 3.82%   |
| AMD + Nvidia   | 6         | 2.29%   |
| 2 x AMD        | 4         | 1.53%   |
| 2 x Nvidia     | 2         | 0.76%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 241       | 91.98%  |
| Proprietary | 14        | 5.34%   |
| Unknown     | 7         | 2.67%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 180       | 68.7%   |
| 0.01-0.5   | 53        | 20.23%  |
| 1.01-2.0   | 12        | 4.58%   |
| 0.51-1.0   | 12        | 4.58%   |
| 3.01-4.0   | 3         | 1.15%   |
| 7.01-8.0   | 1         | 0.38%   |
| 5.01-6.0   | 1         | 0.38%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 55        | 19.23%  |
| BOE                     | 43        | 15.03%  |
| Chimei Innolux          | 35        | 12.24%  |
| Samsung Electronics     | 33        | 11.54%  |
| LG Display              | 31        | 10.84%  |
| Apple                   | 13        | 4.55%   |
| Chi Mei Optoelectronics | 10        | 3.5%    |
| Sharp                   | 7         | 2.45%   |
| LG Philips              | 6         | 2.1%    |
| Lenovo                  | 6         | 2.1%    |
| Dell                    | 5         | 1.75%   |
| BenQ                    | 5         | 1.75%   |
| InfoVision              | 4         | 1.4%    |
| Hewlett-Packard         | 4         | 1.4%    |
| Goldstar                | 4         | 1.4%    |
| HKC                     | 3         | 1.05%   |
| ViewSonic               | 2         | 0.7%    |
| Quanta Display          | 2         | 0.7%    |
| IBM                     | 2         | 0.7%    |
| ASUSTek Computer        | 2         | 0.7%    |
| Ancor Communications    | 2         | 0.7%    |
| Vizio                   | 1         | 0.35%   |
| Unknown (XXX)           | 1         | 0.35%   |
| RTK                     | 1         | 0.35%   |
| Philips                 | 1         | 0.35%   |
| PANDA                   | 1         | 0.35%   |
| Nvidia                  | 1         | 0.35%   |
| KDC                     | 1         | 0.35%   |
| InnoView                | 1         | 0.35%   |
| InnoLux Display         | 1         | 0.35%   |
| HJW                     | 1         | 0.35%   |
| CSO                     | 1         | 0.35%   |
| AOC                     | 1         | 0.35%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 4         | 1.4%    |
| Samsung Electronics LCD Monitor SEC4251 1366x768 344x194mm 15.5-inch     | 3         | 1.05%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 3         | 1.05%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch    | 3         | 1.05%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch         | 3         | 1.05%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 3         | 1.05%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 3         | 1.05%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 3         | 1.05%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 3         | 1.05%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 0.7%    |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 2         | 0.7%    |
| LG Display LCD Monitor LGD0709 1920x1080 344x194mm 15.5-inch             | 2         | 0.7%    |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 2         | 0.7%    |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch             | 2         | 0.7%    |
| Lenovo LCD Monitor LEN4036 1440x900 303x189mm 14.1-inch                  | 2         | 0.7%    |
| IBM LCD Monitor IBM2887 1680x1050 331x207mm 15.4-inch                    | 2         | 0.7%    |
| Goldstar LG FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                | 2         | 0.7%    |
| Chimei Innolux LCD Monitor CMN15E5 1920x1080 344x193mm 15.5-inch         | 2         | 0.7%    |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch         | 2         | 0.7%    |
| Chi Mei Optoelectronics LCD Monitor CMO15AB 1366x768 340x190mm 15.3-inch | 2         | 0.7%    |
| BOE LCD Monitor BOE08C2 1920x1080 344x194mm 15.5-inch                    | 2         | 0.7%    |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch                    | 2         | 0.7%    |
| BOE LCD Monitor BOE0697 1366x768 309x173mm 13.9-inch                     | 2         | 0.7%    |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 2         | 0.7%    |
| AU Optronics LCD Monitor AUO209D 1920x1080 381x214mm 17.2-inch           | 2         | 0.7%    |
| Vizio D48-D0 VIZ1004 1920x1080 1070x610mm 48.5-inch                      | 1         | 0.35%   |
| ViewSonic VX3276-UHD VSC5138 3840x2160 697x392mm 31.5-inch               | 1         | 0.35%   |
| ViewSonic VG2228 SERIES VSCEE29 1920x1080 477x268mm 21.5-inch            | 1         | 0.35%   |
| Unknown (XXX) Beyond TV XXX2851 3840x2160 1210x680mm 54.6-inch           | 1         | 0.35%   |
| Sharp LCD Monitor SHP1515 1920x1200 336x210mm 15.6-inch                  | 1         | 0.35%   |
| Sharp LCD Monitor SHP14D6 3840x2400 366x229mm 17.0-inch                  | 1         | 0.35%   |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch                  | 1         | 0.35%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                  | 1         | 0.35%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 1         | 0.35%   |
| Sharp LCD Monitor SHP144A 3200x1800 294x165mm 13.3-inch                  | 1         | 0.35%   |
| Sharp LCD Monitor SHP143B 3840x2160 346x194mm 15.6-inch                  | 1         | 0.35%   |
| Samsung Electronics SyncMaster SAM0609 1920x1080 510x290mm 23.1-inch     | 1         | 0.35%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch        | 1         | 0.35%   |
| Samsung Electronics S22E450 SAM0C98 1680x1050 473x291mm 21.9-inch        | 1         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 114       | 41.61%  |
| 1366x768 (WXGA)    | 79        | 28.83%  |
| 1280x800 (WXGA)    | 21        | 7.66%   |
| 1920x1200 (WUXGA)  | 12        | 4.38%   |
| 1600x900 (HD+)     | 8         | 2.92%   |
| 1440x900 (WXGA+)   | 8         | 2.92%   |
| 3840x2160 (4K)     | 7         | 2.55%   |
| 2560x1440 (QHD)    | 7         | 2.55%   |
| 2560x1600          | 5         | 1.82%   |
| 1680x1050 (WSXGA+) | 4         | 1.46%   |
| 3840x2400          | 2         | 0.73%   |
| 3440x1440          | 1         | 0.36%   |
| 3200x1800 (QHD+)   | 1         | 0.36%   |
| 3072x1920          | 1         | 0.36%   |
| 2880x1800          | 1         | 0.36%   |
| 2256x1504          | 1         | 0.36%   |
| 1360x768           | 1         | 0.36%   |
| 1024x768 (XGA)     | 1         | 0.36%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Notebooks | Percent |
|--------|-----------|---------|
| 15     | 118       | 41.26%  |
| 14     | 35        | 12.24%  |
| 13     | 35        | 12.24%  |
| 17     | 20        | 6.99%   |
| 16     | 15        | 5.24%   |
| 11     | 13        | 4.55%   |
| 21     | 9         | 3.15%   |
| 24     | 7         | 2.45%   |
| 27     | 6         | 2.1%    |
| 18     | 6         | 2.1%    |
| 23     | 5         | 1.75%   |
| 12     | 5         | 1.75%   |
| 54     | 4         | 1.4%    |
| 31     | 3         | 1.05%   |
| 57     | 1         | 0.35%   |
| 34     | 1         | 0.35%   |
| 32     | 1         | 0.35%   |
| 22     | 1         | 0.35%   |
| 19     | 1         | 0.35%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 174       | 61.05%  |
| 201-300     | 39        | 13.68%  |
| 351-400     | 28        | 9.82%   |
| 501-600     | 18        | 6.32%   |
| 401-500     | 16        | 5.61%   |
| 1001-1500   | 4         | 1.4%    |
| 701-800     | 3         | 1.05%   |
| 601-700     | 3         | 1.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 199       | 77.43%  |
| 16/10 | 52        | 20.23%  |
| 3/2   | 3         | 1.17%   |
| 4/3   | 1         | 0.39%   |
| 21/9  | 1         | 0.39%   |
| 0.56  | 1         | 0.39%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 120       | 41.96%  |
| 81-90          | 57        | 19.93%  |
| 121-130        | 18        | 6.29%   |
| 201-250        | 16        | 5.59%   |
| 51-60          | 13        | 4.55%   |
| 71-80          | 12        | 4.2%    |
| 111-120        | 12        | 4.2%    |
| 301-350        | 6         | 2.1%    |
| 141-150        | 6         | 2.1%    |
| More than 1000 | 5         | 1.75%   |
| 61-70          | 5         | 1.75%   |
| 351-500        | 5         | 1.75%   |
| 151-200        | 5         | 1.75%   |
| 131-140        | 3         | 1.05%   |
| 251-300        | 2         | 0.7%    |
| 91-100         | 1         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 119       | 42.2%   |
| 101-120       | 89        | 31.56%  |
| 51-100        | 39        | 13.83%  |
| 161-240       | 25        | 8.87%   |
| More than 240 | 5         | 1.77%   |
| 1-50          | 5         | 1.77%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 224       | 84.53%  |
| 2     | 37        | 13.96%  |
| 0     | 4         | 1.51%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 129       | 32.01%  |
| Intel                         | 111       | 27.54%  |
| Broadcom                      | 48        | 11.91%  |
| Qualcomm Atheros              | 37        | 9.18%   |
| MediaTek                      | 19        | 4.71%   |
| Broadcom Limited              | 8         | 1.99%   |
| Nvidia                        | 5         | 1.24%   |
| Ralink                        | 4         | 0.99%   |
| OPPO Electronics              | 4         | 0.99%   |
| Marvell Technology Group      | 4         | 0.99%   |
| TP-Link                       | 3         | 0.74%   |
| Samsung Electronics           | 3         | 0.74%   |
| Dell                          | 3         | 0.74%   |
| ASIX Electronics              | 3         | 0.74%   |
| Xiaomi                        | 2         | 0.5%    |
| Ralink Technology             | 2         | 0.5%    |
| Qualcomm                      | 2         | 0.5%    |
| Motorola PCS                  | 2         | 0.5%    |
| Huawei Technologies           | 2         | 0.5%    |
| D-Link                        | 2         | 0.5%    |
| ASUSTek Computer              | 2         | 0.5%    |
| ZyDAS                         | 1         | 0.25%   |
| Spreadtrum Communications     | 1         | 0.25%   |
| SEGGER                        | 1         | 0.25%   |
| OnePlus Technology (Shenzhen) | 1         | 0.25%   |
| NetGear                       | 1         | 0.25%   |
| Fujitsu Siemens Computers     | 1         | 0.25%   |
| DisplayLink                   | 1         | 0.25%   |
| Belkin Components             | 1         | 0.25%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 69        | 14.38%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 16        | 3.33%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 13        | 2.71%   |
| Intel Wireless 8265 / 8275                                             | 13        | 2.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 2.08%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 10        | 2.08%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 9         | 1.88%   |
| Intel Wireless 7265                                                    | 8         | 1.67%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                 | 8         | 1.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 7         | 1.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 7         | 1.46%   |
| Intel Wi-Fi 6 AX201                                                    | 7         | 1.46%   |
| Intel Wi-Fi 6 AX200                                                    | 7         | 1.46%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 7         | 1.46%   |
| Intel 82577LM Gigabit Network Connection                               | 7         | 1.46%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 7         | 1.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 6         | 1.25%   |
| Broadcom BCM43142 802.11b/g/n                                          | 6         | 1.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 5         | 1.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 1.04%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2        | 5         | 1.04%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 1.04%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 1.04%   |
| Realtek 802.11ac NIC                                                   | 4         | 0.83%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 4         | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 0.83%   |
| Nvidia MCP79 Ethernet                                                  | 4         | 0.83%   |
| Intel Wireless 8260                                                    | 4         | 0.83%   |
| Intel Wireless 7260                                                    | 4         | 0.83%   |
| Intel Wireless 3165                                                    | 4         | 0.83%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 0.63%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 0.63%   |
| Realtek 802.11n WLAN Adapter                                           | 3         | 0.63%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 0.63%   |
| OPPO OnePlus Nord 4                                                    | 3         | 0.63%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 3         | 0.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                  | 3         | 0.63%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 0.63%   |
| Intel Ethernet Connection (16) I219-LM                                 | 3         | 0.63%   |
| Intel Centrino Advanced-N 6235                                         | 3         | 0.63%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Intel                     | 99        | 38.52%  |
| Realtek Semiconductor     | 48        | 18.68%  |
| Broadcom                  | 39        | 15.18%  |
| Qualcomm Atheros          | 29        | 11.28%  |
| MediaTek                  | 18        | 7%      |
| Broadcom Limited          | 5         | 1.95%   |
| Ralink                    | 4         | 1.56%   |
| TP-Link                   | 2         | 0.78%   |
| Ralink Technology         | 2         | 0.78%   |
| Dell                      | 2         | 0.78%   |
| D-Link                    | 2         | 0.78%   |
| ASUSTek Computer          | 2         | 0.78%   |
| ZyDAS                     | 1         | 0.39%   |
| Qualcomm                  | 1         | 0.39%   |
| NetGear                   | 1         | 0.39%   |
| Fujitsu Siemens Computers | 1         | 0.39%   |
| Belkin Components         | 1         | 0.39%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 13        | 5%      |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 12        | 4.62%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 10        | 3.85%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 3.46%   |
| Intel Wireless 7265                                                     | 8         | 3.08%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 8         | 3.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 7         | 2.69%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 2.69%   |
| Intel Wi-Fi 6 AX200                                                     | 7         | 2.69%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 7         | 2.69%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 7         | 2.69%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 2.31%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 2.31%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 5         | 1.92%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5         | 1.92%   |
| Realtek 802.11ac NIC                                                    | 4         | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.54%   |
| Intel Wireless 8260                                                     | 4         | 1.54%   |
| Intel Wireless 7260                                                     | 4         | 1.54%   |
| Intel Wireless 3165                                                     | 4         | 1.54%   |
| Realtek 802.11n WLAN Adapter                                            | 3         | 1.15%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2         | 3         | 1.15%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 3         | 1.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.15%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.15%   |
| Intel Centrino Advanced-N 6200                                          | 3         | 1.15%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.15%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 3         | 1.15%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 2         | 0.77%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.77%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 2         | 0.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.77%   |
| Ralink MT7601U Wireless Adapter                                         | 2         | 0.77%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 2         | 0.77%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.77%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 2         | 0.77%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 2         | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Notebooks | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 105       | 49.3%   |
| Intel                         | 48        | 22.54%  |
| Broadcom                      | 15        | 7.04%   |
| Qualcomm Atheros              | 12        | 5.63%   |
| Nvidia                        | 5         | 2.35%   |
| OPPO Electronics              | 4         | 1.88%   |
| Marvell Technology Group      | 4         | 1.88%   |
| Broadcom Limited              | 3         | 1.41%   |
| ASIX Electronics              | 3         | 1.41%   |
| Xiaomi                        | 2         | 0.94%   |
| Samsung Electronics           | 2         | 0.94%   |
| Motorola PCS                  | 2         | 0.94%   |
| Huawei Technologies           | 2         | 0.94%   |
| TP-Link                       | 1         | 0.47%   |
| Spreadtrum Communications     | 1         | 0.47%   |
| Qualcomm                      | 1         | 0.47%   |
| OnePlus Technology (Shenzhen) | 1         | 0.47%   |
| MediaTek                      | 1         | 0.47%   |
| DisplayLink                   | 1         | 0.47%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 69        | 31.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 16        | 7.41%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 10        | 4.63%   |
| Intel 82577LM Gigabit Network Connection                               | 7         | 3.24%   |
| Intel Ethernet Connection I217-LM                                      | 5         | 2.31%   |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 2.31%   |
| Nvidia MCP79 Ethernet                                                  | 4         | 1.85%   |
| Realtek RTL8125 2.5GbE Controller                                      | 3         | 1.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 1.39%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 1.39%   |
| OPPO OnePlus Nord 4                                                    | 3         | 1.39%   |
| Intel Ethernet Connection I219-LM                                      | 3         | 1.39%   |
| Intel Ethernet Connection (16) I219-LM                                 | 3         | 1.39%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 3         | 1.39%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                      | 3         | 1.39%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 3         | 1.39%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2         | 0.93%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.93%   |
| Realtek RTL8852CE PCIe 802.11ax Wireless Network Controller            | 2         | 0.93%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 2         | 0.93%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 2         | 0.93%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.93%   |
| Motorola PCS moto g84 5G                                               | 2         | 0.93%   |
| Intel Wi-Fi 7(802.11be) AX1775*/AX1790*/BE20*/BE401/BE1750* 2x2        | 2         | 0.93%   |
| Intel Ethernet Connection I218-LM                                      | 2         | 0.93%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 0.93%   |
| Intel Ethernet Connection (4) I219-V                                   | 2         | 0.93%   |
| Intel Ethernet Connection (3) I218-LM                                  | 2         | 0.93%   |
| Intel CNVi: Wi-Fi                                                      | 2         | 0.93%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 2         | 0.93%   |
| Broadcom NetXtreme BCM5752 Gigabit Ethernet PCI Express                | 2         | 0.93%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 2         | 0.93%   |
| ASIX AX88179 Gigabit Ethernet                                          | 2         | 0.93%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.46%   |
| Spreadtrum Unisoc Phone                                                | 1         | 0.46%   |
| Realtek USB 10/100/1G/2.5G LAN                                         | 1         | 0.46%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.46%   |
| Realtek PCIe GbE Family Controller                                     | 1         | 0.46%   |
| Qualcomm POCO F3                                                       | 1         | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 244       | 54.71%  |
| Ethernet | 198       | 44.39%  |
| Modem    | 4         | 0.9%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 183       | 68.8%   |
| Ethernet | 83        | 31.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 166       | 63.36%  |
| 1     | 82        | 31.3%   |
| 0     | 14        | 5.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 186       | 70.72%  |
| Yes  | 77        | 29.28%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 85        | 39.35%  |
| Realtek Semiconductor           | 30        | 13.89%  |
| IMC Networks                    | 19        | 8.8%    |
| Qualcomm Atheros Communications | 15        | 6.94%   |
| Apple                           | 14        | 6.48%   |
| Broadcom                        | 13        | 6.02%   |
| Dell                            | 7         | 3.24%   |
| Foxconn / Hon Hai               | 6         | 2.78%   |
| Cambridge Silicon Radio         | 6         | 2.78%   |
| Toshiba                         | 4         | 1.85%   |
| Lite-On Technology              | 4         | 1.85%   |
| Hewlett-Packard                 | 4         | 1.85%   |
| Ralink                          | 2         | 0.93%   |
| ASUSTek Computer                | 2         | 0.93%   |
| Alps Electric                   | 2         | 0.93%   |
| MediaTek                        | 1         | 0.46%   |
| Foxconn International           | 1         | 0.46%   |
| Edimax Technology               | 1         | 0.46%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 32        | 14.81%  |
| Realtek Bluetooth Radio                             | 22        | 10.19%  |
| Intel AX201 Bluetooth                               | 15        | 6.94%   |
| IMC Networks Wireless_Device                        | 15        | 6.94%   |
| Apple Bluetooth Host Controller                     | 9         | 4.17%   |
| Qualcomm Atheros  Bluetooth Device                  | 8         | 3.7%    |
| Intel AX211 Bluetooth                               | 8         | 3.7%    |
| Intel AX200 Bluetooth                               | 7         | 3.24%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 2.78%   |
| Intel Bluetooth Device                              | 5         | 2.31%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 5         | 2.31%   |
| Realtek 802.11ac WLAN Adapter                       | 4         | 1.85%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.85%   |
| Realtek  Bluetooth 4.2 Adapter                      | 3         | 1.39%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 1.39%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 3         | 1.39%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.39%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 3         | 1.39%   |
| Dell DW375 Bluetooth Module                         | 3         | 1.39%   |
| Apple Bluetooth USB Host Controller                 | 3         | 1.39%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.93%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.93%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 2         | 0.93%   |
| Intel AX210 Bluetooth                               | 2         | 0.93%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.93%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 2         | 0.93%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.93%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.93%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.46%   |
| Toshiba Bluetooth Device                            | 1         | 0.46%   |
| Toshiba BCM43142A0                                  | 1         | 0.46%   |
| Toshiba Askey for                                   | 1         | 0.46%   |
| Realtek Bluetooth 5.4 Radio                         | 1         | 0.46%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1         | 0.46%   |
| MediaTek Wireless_Device                            | 1         | 0.46%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.46%   |
| Lite-On Bluetooth Radio                             | 1         | 0.46%   |
| Lite-On Bluetooth Device                            | 1         | 0.46%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.46%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 184       | 61.54%  |
| AMD                              | 64        | 21.4%   |
| Nvidia                           | 34        | 11.37%  |
| Realtek Semiconductor            | 3         | 1%      |
| Texas Instruments                | 2         | 0.67%   |
| Philips (or NXP)                 | 2         | 0.67%   |
| Silicon Integrated Systems [SiS] | 1         | 0.33%   |
| Nordic Semiconductor ASA         | 1         | 0.33%   |
| Lenovo                           | 1         | 0.33%   |
| JMTek                            | 1         | 0.33%   |
| Jieli Technology                 | 1         | 0.33%   |
| GN Netcom                        | 1         | 0.33%   |
| Dell                             | 1         | 0.33%   |
| BEHRINGER International          | 1         | 0.33%   |
| AKAI Professional M.I.           | 1         | 0.33%   |
| Actions Semiconductor            | 1         | 0.33%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 43        | 11.65%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 26        | 7.05%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 5.42%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 19        | 5.15%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 16        | 4.34%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 15        | 4.07%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 13        | 3.52%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 9         | 2.44%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 8         | 2.17%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 8         | 2.17%   |
| AMD FCH Azalia Controller                                                                         | 8         | 2.17%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 1.9%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 7         | 1.9%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 1.63%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 6         | 1.63%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.63%   |
| AMD Kabini HDMI/DP Audio                                                                          | 6         | 1.63%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 6         | 1.63%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.36%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 1.36%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.36%   |
| Intel Cannon Lake PCH cAVS                                                                        | 5         | 1.36%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 1.36%   |
| Nvidia MCP79 High Definition Audio                                                                | 4         | 1.08%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 1.08%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.08%   |
| Intel Meteor Lake-P HD Audio Controller                                                           | 4         | 1.08%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 1.08%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 4         | 1.08%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.08%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.08%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 4         | 1.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 4         | 1.08%   |
| AMD High Definition Audio Controller                                                              | 4         | 1.08%   |
| Nvidia AD107 High Definition Audio Controller                                                     | 3         | 0.81%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 3         | 0.81%   |
| Intel Raptor Lake High Definition Audio Controller                                                | 3         | 0.81%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.81%   |
| Texas Instruments PCM2704 16-bit stereo audio DAC                                                 | 2         | 0.54%   |
| Realtek Semiconductor USB Audio                                                                   | 2         | 0.54%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 76        | 25.08%  |
| Samsung Electronics | 73        | 24.09%  |
| Micron Technology   | 34        | 11.22%  |
| Unknown             | 28        | 9.24%   |
| Kingston            | 18        | 5.94%   |
| Crucial             | 11        | 3.63%   |
| Ramaxel Technology  | 9         | 2.97%   |
| Unknown             | 9         | 2.97%   |
| Unknown (ABCD)      | 7         | 2.31%   |
| Elpida              | 7         | 2.31%   |
| A-DATA Technology   | 7         | 2.31%   |
| Corsair             | 5         | 1.65%   |
| Team                | 3         | 0.99%   |
| G.Skill             | 3         | 0.99%   |
| Smart               | 2         | 0.66%   |
| Patriot             | 2         | 0.66%   |
| Nanya Technology    | 2         | 0.66%   |
| Transcend           | 1         | 0.33%   |
| Qimonda             | 1         | 0.33%   |
| Netlist             | 1         | 0.33%   |
| ff                  | 1         | 0.33%   |
| ACPI Digital        | 1         | 0.33%   |
| 4ea5                | 1         | 0.33%   |
| 48spaces            | 1         | 0.33%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 9         | 2.81%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 7         | 2.19%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 2.19%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 1.88%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 1.56%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 1.56%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 1.25%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 4         | 1.25%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 1.25%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.25%   |
| Unknown RAM Module 2GB SODIMM DDR3 1333MT/s                      | 3         | 0.94%   |
| Unknown RAM Module 1GB SODIMM DDR3 1066MT/s                      | 3         | 0.94%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 3         | 0.94%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.94%   |
| SK hynix RAM HMA82GS6DJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 3         | 0.94%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.94%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.94%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.94%   |
| Samsung RAM M471A1G44CB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.94%   |
| Micron RAM 4ATF1G64HZ-3G2F1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.94%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 2         | 0.63%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 0.63%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.63%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 2         | 0.63%   |
| Unknown RAM Module 1GB SODIMM DDR2                               | 2         | 0.63%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 2         | 0.63%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.63%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s         | 2         | 0.63%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.63%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 2         | 0.63%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 0.63%   |
| SK hynix RAM HMA82GS6DJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.63%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2400MT/s           | 2         | 0.63%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.63%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB SODIMM LPDDR5 6400MT/s       | 2         | 0.63%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.63%   |
| Samsung RAM M471B5173BH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.63%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 2         | 0.63%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.63%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 2         | 0.63%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 97        | 36.6%   |
| DDR3    | 92        | 34.72%  |
| LPDDR4  | 15        | 5.66%   |
| DDR2    | 15        | 5.66%   |
| DDR5    | 14        | 5.28%   |
| LPDDR5  | 11        | 4.15%   |
| SDRAM   | 8         | 3.02%   |
| LPDDR3  | 5         | 1.89%   |
| DDR     | 5         | 1.89%   |
| Unknown | 3         | 1.13%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 230       | 86.79%  |
| Row Of Chips | 26        | 9.81%   |
| Unknown      | 5         | 1.89%   |
| Chip         | 3         | 1.13%   |
| DIMM         | 1         | 0.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 104       | 37.41%  |
| 4096  | 75        | 26.98%  |
| 2048  | 37        | 13.31%  |
| 16384 | 32        | 11.51%  |
| 1024  | 16        | 5.76%   |
| 32768 | 12        | 4.32%   |
| 512   | 2         | 0.72%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 60        | 21.35%  |
| 1600    | 56        | 19.93%  |
| 2667    | 30        | 10.68%  |
| 2400    | 21        | 7.47%   |
| 1333    | 13        | 4.63%   |
| 1334    | 12        | 4.27%   |
| 4800    | 9         | 3.2%    |
| 1067    | 8         | 2.85%   |
| 667     | 8         | 2.85%   |
| 6400    | 7         | 2.49%   |
| 800     | 6         | 2.14%   |
| Unknown | 6         | 2.14%   |
| 4267    | 5         | 1.78%   |
| 2133    | 5         | 1.78%   |
| 5600    | 4         | 1.42%   |
| 1867    | 4         | 1.42%   |
| 1066    | 4         | 1.42%   |
| 4199    | 3         | 1.07%   |
| 2048    | 3         | 1.07%   |
| 975     | 3         | 1.07%   |
| 7467    | 2         | 0.71%   |
| 3266    | 2         | 0.71%   |
| 533     | 2         | 0.71%   |
| 7500    | 1         | 0.36%   |
| 5500    | 1         | 0.36%   |
| 5200    | 1         | 0.36%   |
| 3733    | 1         | 0.36%   |
| 2933    | 1         | 0.36%   |
| 1639    | 1         | 0.36%   |
| 400     | 1         | 0.36%   |
| 100     | 1         | 0.36%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 50%     |
| Dymo-CoStar     | 1         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                       | Notebooks | Percent |
|-----------------------------|-----------|---------|
| HP LaserJet P1006           | 1         | 50%     |
| Dymo-CoStar LabelWriter 450 | 1         | 50%     |

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
| Chicony Electronics                    | 44        | 19.47%  |
| Microdia                               | 20        | 8.85%   |
| IMC Networks                           | 20        | 8.85%   |
| Realtek Semiconductor                  | 17        | 7.52%   |
| Bison Electronics                      | 14        | 6.19%   |
| Quanta                                 | 12        | 5.31%   |
| Apple                                  | 12        | 5.31%   |
| Luxvisions Innotech Limited            | 10        | 4.42%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 4.42%   |
| Sunplus Innovation Technology          | 9         | 3.98%   |
| Suyin                                  | 8         | 3.54%   |
| Lite-On Technology                     | 7         | 3.1%    |
| Syntek                                 | 6         | 2.65%   |
| Alcor Micro                            | 6         | 2.65%   |
| Silicon Motion                         | 4         | 1.77%   |
| Importek                               | 4         | 1.77%   |
| Ricoh                                  | 3         | 1.33%   |
| Lenovo                                 | 3         | 1.33%   |
| Acer                                   | 3         | 1.33%   |
| Sonix Technology                       | 2         | 0.88%   |
| Intel                                  | 2         | 0.88%   |
| icSpring                               | 2         | 0.88%   |
| Z-Star Microelectronics                | 1         | 0.44%   |
| SunplusIT                              | 1         | 0.44%   |
| ShineTech                              | 1         | 0.44%   |
| Samsung Electronics                    | 1         | 0.44%   |
| Logitech                               | 1         | 0.44%   |
| KYT-221229-A                           | 1         | 0.44%   |
| Cubeternet                             | 1         | 0.44%   |
| BillionPixels                          | 1         | 0.44%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                                              | 11        | 4.87%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 11        | 4.87%   |
| Realtek Integrated_Webcam_HD                                               | 9         | 3.98%   |
| Chicony Integrated Camera                                                  | 8         | 3.54%   |
| Apple Built-in iSight                                                      | 7         | 3.1%    |
| Syntek Integrated Camera                                                   | 4         | 1.77%   |
| Luxvisions Innotech Limited Integrated Camera                              | 4         | 1.77%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 4         | 1.77%   |
| Lite-On Integrated Camera                                                  | 4         | 1.77%   |
| Importek TOSHIBA Web Camera - HD                                           | 4         | 1.77%   |
| IMC Networks Integrated Camera                                             | 4         | 1.77%   |
| Chicony HP Truevision HD                                                   | 4         | 1.77%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 3         | 1.33%   |
| Microdia Integrated_Webcam_FHD                                             | 3         | 1.33%   |
| Chicony TOSHIBA Web Camera - HD                                            | 3         | 1.33%   |
| Chicony HP HD Camera                                                       | 3         | 1.33%   |
| Chicony ACER HD User Facing                                                | 3         | 1.33%   |
| Bison Lenovo EasyCamera                                                    | 3         | 1.33%   |
| Acer Integrated Camera                                                     | 3         | 1.33%   |
| Suyin HP Truevision HD                                                     | 2         | 0.88%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 2         | 0.88%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 0.88%   |
| Ricoh HD Webcam                                                            | 2         | 0.88%   |
| Realtek Bluetooth Radio                                                    | 2         | 0.88%   |
| Quanta ov9734_techfront_camera                                             | 2         | 0.88%   |
| Quanta HP TrueVision HD Camera                                             | 2         | 0.88%   |
| Quanta ACER HD User Facing                                                 | 2         | 0.88%   |
| Lenovo Integrated Webcam [R5U877]                                          | 2         | 0.88%   |
| Intel RealSense 3D Camera (Front F200)                                     | 2         | 0.88%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 2         | 0.88%   |
| IMC Networks EasyCamera                                                    | 2         | 0.88%   |
| icSpring camera                                                            | 2         | 0.88%   |
| Chicony VGA Webcam                                                         | 2         | 0.88%   |
| Chicony HP TrueVision HD Camera                                            | 2         | 0.88%   |
| Chicony HP HD Webcam                                                       | 2         | 0.88%   |
| Chicony HD WebCam                                                          | 2         | 0.88%   |
| Chicony Chicony USB2.0 Camera                                              | 2         | 0.88%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 0.88%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera             | 2         | 0.88%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera                        | 2         | 0.88%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 16        | 37.21%  |
| Synaptics                  | 8         | 18.6%   |
| Elan Microelectronics      | 6         | 13.95%  |
| Shenzhen Goodix Technology | 5         | 11.63%  |
| Upek                       | 4         | 9.3%    |
| STMicroelectronics         | 2         | 4.65%   |
| AuthenTec                  | 2         | 4.65%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Notebooks | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader             | 4         | 9.3%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 4         | 9.3%    |
| Shenzhen Goodix  Fingerprint Device                    | 4         | 9.3%    |
| Validity Sensors Fingerprint scanner                   | 3         | 6.98%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 3         | 6.98%   |
| Elan ELAN:Fingerprint                                  | 3         | 6.98%   |
| Validity Sensors VFS5011 Fingerprint Reader            | 2         | 4.65%   |
| Synaptics UWP WBDI Device                              | 2         | 4.65%   |
| STMicroelectronics Fingerprint Reader                  | 2         | 4.65%   |
| Elan ELAN:ARM-M4                                       | 2         | 4.65%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 2         | 4.65%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 2.33%   |
| Validity Sensors VFS491                                | 1         | 2.33%   |
| Validity Sensors VFS451 Fingerprint Reader             | 1         | 2.33%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 2.33%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 2.33%   |
| Validity Sensors Synaptics WBDI                        | 1         | 2.33%   |
| Validity Sensors Swipe Fingerprint Sensor              | 1         | 2.33%   |
| Synaptics  WBDI                                        | 1         | 2.33%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 2.33%   |
| Synaptics Fingerprint reader [HP G6]                   | 1         | 2.33%   |
| Shenzhen Goodix FingerPrint                            | 1         | 2.33%   |
| Elan WBF Fingerprint Sensor                            | 1         | 2.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 13        | 61.9%   |
| Alcor Micro | 5         | 23.81%  |
| O2 Micro    | 2         | 9.52%   |
| Lenovo      | 1         | 4.76%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 7         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 23.81%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 14.29%  |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 9.52%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 9.52%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 4.76%   |
| Broadcom 5880                                                                | 1         | 4.76%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 155       | 58.94%  |
| 1     | 83        | 31.56%  |
| 2     | 21        | 7.98%   |
| 3     | 3         | 1.14%   |
| 4     | 1         | 0.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 42        | 31.82%  |
| Graphics card         | 41        | 31.06%  |
| Chipcard              | 20        | 15.15%  |
| Net/wireless          | 7         | 5.3%    |
| Camera                | 7         | 5.3%    |
| Multimedia controller | 6         | 4.55%   |
| Storage               | 2         | 1.52%   |
| Bluetooth             | 2         | 1.52%   |
| Wireless              | 1         | 0.76%   |
| Sound                 | 1         | 0.76%   |
| Network               | 1         | 0.76%   |
| Flash memory          | 1         | 0.76%   |
| Card reader           | 1         | 0.76%   |

