Linux in Dominican Republic - Tested Hardware & Statistics
----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Dominican Republic.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Dominican_Republic/Desktop/README.md) and [notebooks](/Location/Dominican_Republic/Notebook/README.md).

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

Total: 328

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [476e287467](https://linux-hardware.org/?probe=476e287467) | Dec 21, 2024 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [faa62fd31d](https://linux-hardware.org/?probe=faa62fd31d) | Nov 27, 2024 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [66344f008f](https://linux-hardware.org/?probe=66344f008f) | Nov 20, 2024 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [cf55ce81fa](https://linux-hardware.org/?probe=cf55ce81fa) | Nov 20, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [f84abc56e9](https://linux-hardware.org/?probe=f84abc56e9) | Nov 08, 2024 |
| Lenovo        | Unknown                     | Notebook    | [18084edb88](https://linux-hardware.org/?probe=18084edb88) | Nov 06, 2024 |
| Intel         | TU45C                       | Notebook    | [f7640d1ac4](https://linux-hardware.org/?probe=f7640d1ac4) | Oct 31, 2024 |
| Lenovo        | Unknown                     | Notebook    | [0fdc4e7dac](https://linux-hardware.org/?probe=0fdc4e7dac) | Oct 31, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [c57cc10b49](https://linux-hardware.org/?probe=c57cc10b49) | Oct 11, 2024 |
| Gigabyte      | X99-UD4P-CF                 | Desktop     | [c8271ce4cb](https://linux-hardware.org/?probe=c8271ce4cb) | Oct 09, 2024 |
| Lenovo        | Bantry CRB SDK0J40705 WI... | Desktop     | [0af4bece40](https://linux-hardware.org/?probe=0af4bece40) | Sep 22, 2024 |
| Dell          | Inspiron 3520               | Notebook    | [f5cdd77427](https://linux-hardware.org/?probe=f5cdd77427) | Sep 17, 2024 |
| Dell          | Latitude E6420              | Notebook    | [a37423865a](https://linux-hardware.org/?probe=a37423865a) | Sep 15, 2024 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2d1f00b430](https://linux-hardware.org/?probe=2d1f00b430) | Sep 14, 2024 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [0886f6bb06](https://linux-hardware.org/?probe=0886f6bb06) | Sep 11, 2024 |
| Chuwi         | HeroBook Air                | Notebook    | [09a139dbbe](https://linux-hardware.org/?probe=09a139dbbe) | Sep 04, 2024 |
| Chuwi         | HeroBook Air                | Notebook    | [163bdd4e80](https://linux-hardware.org/?probe=163bdd4e80) | Sep 04, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [d738fd6aec](https://linux-hardware.org/?probe=d738fd6aec) | Sep 03, 2024 |
| HP            | Compaq Presario CQ60        | Notebook    | [4a61316ba0](https://linux-hardware.org/?probe=4a61316ba0) | Aug 25, 2024 |
| Lenovo        | 3733 SDK0R32862 WIN 3258... | Desktop     | [93496e0097](https://linux-hardware.org/?probe=93496e0097) | Aug 16, 2024 |
| Acer          | Aspire E5-576               | Notebook    | [50e12f89a7](https://linux-hardware.org/?probe=50e12f89a7) | Aug 15, 2024 |
| Lenovo        | ThinkPad T490 20N3S64200    | Notebook    | [14ae99c097](https://linux-hardware.org/?probe=14ae99c097) | Aug 14, 2024 |
| GPU Compan... | GWTC51427                   | Notebook    | [55c2e1921f](https://linux-hardware.org/?probe=55c2e1921f) | Aug 08, 2024 |
| Dell          | System XPS L321X            | Notebook    | [c8e8aa60ed](https://linux-hardware.org/?probe=c8e8aa60ed) | Jul 31, 2024 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | Notebook    | [49142dd027](https://linux-hardware.org/?probe=49142dd027) | Jul 27, 2024 |
| Dell          | Latitude 3330               | Notebook    | [bee203920a](https://linux-hardware.org/?probe=bee203920a) | Jul 27, 2024 |
| Dell          | Inspiron 3135               | Notebook    | [36c80b438d](https://linux-hardware.org/?probe=36c80b438d) | Jul 22, 2024 |
| Dell          | 00V62H A00                  | Desktop     | [d2ea46cd2d](https://linux-hardware.org/?probe=d2ea46cd2d) | Jul 21, 2024 |
| Lenovo        | IdeaPad Slim 9 14ITL5 82... | Notebook    | [4e94f5fb5f](https://linux-hardware.org/?probe=4e94f5fb5f) | Jul 20, 2024 |
| Dell          | Latitude E6430              | Notebook    | [ec7d5a0740](https://linux-hardware.org/?probe=ec7d5a0740) | Jul 14, 2024 |
| Unknown       | Unknown                     | Notebook    | [1b0d823c81](https://linux-hardware.org/?probe=1b0d823c81) | Jul 05, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [5d75a25d73](https://linux-hardware.org/?probe=5d75a25d73) | Jun 30, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [efce3d02b0](https://linux-hardware.org/?probe=efce3d02b0) | Jun 30, 2024 |
| ASUSTek       | G75VW                       | Notebook    | [7b448890f8](https://linux-hardware.org/?probe=7b448890f8) | Jun 22, 2024 |
| Dell          | OptiPlex 3020               | Desktop     | [5e05238389](https://linux-hardware.org/?probe=5e05238389) | Jun 20, 2024 |
| Foxconn       | H61MXE/-S/-V/-K             | Desktop     | [f315f67fd3](https://linux-hardware.org/?probe=f315f67fd3) | Jun 18, 2024 |
| Acer          | Aspire A515-45              | Notebook    | [f21d4210a9](https://linux-hardware.org/?probe=f21d4210a9) | Jun 14, 2024 |
| Dell          | Latitude E6430              | Notebook    | [042ef58af8](https://linux-hardware.org/?probe=042ef58af8) | May 30, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [594a2b53a8](https://linux-hardware.org/?probe=594a2b53a8) | May 25, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [194d8ef52c](https://linux-hardware.org/?probe=194d8ef52c) | May 25, 2024 |
| Dell          | OptiPlex 3020               | Desktop     | [4ce003cddc](https://linux-hardware.org/?probe=4ce003cddc) | May 23, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [74efedec18](https://linux-hardware.org/?probe=74efedec18) | May 15, 2024 |
| Dell          | Inspiron 5535               | Notebook    | [9d93f7fd83](https://linux-hardware.org/?probe=9d93f7fd83) | May 12, 2024 |
| Dell          | Inspiron 5535               | Notebook    | [d23167b52c](https://linux-hardware.org/?probe=d23167b52c) | May 09, 2024 |
| ASUSTek       | X550CA                      | Notebook    | [5038e329fc](https://linux-hardware.org/?probe=5038e329fc) | May 06, 2024 |
| Dell          | 0J3C2F A00                  | Desktop     | [7c98336737](https://linux-hardware.org/?probe=7c98336737) | Apr 29, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [5078c26f9c](https://linux-hardware.org/?probe=5078c26f9c) | Apr 24, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [f9582b6020](https://linux-hardware.org/?probe=f9582b6020) | Apr 24, 2024 |
| Apple         | MacBookPro8,1               | Notebook    | [60291310ee](https://linux-hardware.org/?probe=60291310ee) | Apr 22, 2024 |
| ASRock        | A620M Pro RS WiFi           | Desktop     | [d715b7146f](https://linux-hardware.org/?probe=d715b7146f) | Apr 20, 2024 |
| TODOS INDU... | Aprix_2022_V1               | Notebook    | [97ae5afa87](https://linux-hardware.org/?probe=97ae5afa87) | Apr 05, 2024 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [0ddecde36c](https://linux-hardware.org/?probe=0ddecde36c) | Apr 02, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [fd278af3a5](https://linux-hardware.org/?probe=fd278af3a5) | Mar 31, 2024 |
| TODOS INDU... | Aprix_2022_V1               | Notebook    | [e5e980e4f5](https://linux-hardware.org/?probe=e5e980e4f5) | Mar 30, 2024 |
| Acer          | Aspire 4752                 | Notebook    | [bb522b4ec1](https://linux-hardware.org/?probe=bb522b4ec1) | Mar 26, 2024 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [4bb4a14245](https://linux-hardware.org/?probe=4bb4a14245) | Feb 28, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [17be6d540f](https://linux-hardware.org/?probe=17be6d540f) | Feb 16, 2024 |
| ASUSTek       | X540YA                      | Notebook    | [8ab328c73b](https://linux-hardware.org/?probe=8ab328c73b) | Feb 15, 2024 |
| Google        | Lulu                        | Notebook    | [c081ea57a2](https://linux-hardware.org/?probe=c081ea57a2) | Feb 11, 2024 |
| HP            | 09E8h                       | Desktop     | [413788d555](https://linux-hardware.org/?probe=413788d555) | Feb 02, 2024 |
| ASUSTek       | Q87M-E                      | Desktop     | [318aab51d9](https://linux-hardware.org/?probe=318aab51d9) | Jan 15, 2024 |
| ASUSTek       | X540YA                      | Notebook    | [b3641f90e8](https://linux-hardware.org/?probe=b3641f90e8) | Jan 12, 2024 |
| Apple         | MacBookPro14,2              | Notebook    | [0d3413c236](https://linux-hardware.org/?probe=0d3413c236) | Jan 09, 2024 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [4434600249](https://linux-hardware.org/?probe=4434600249) | Jan 01, 2024 |
| HP            | ProBook 11 G2               | Notebook    | [6cf8228f10](https://linux-hardware.org/?probe=6cf8228f10) | Dec 31, 2023 |
| HP            | ProBook 11 G2               | Notebook    | [3ad144c68e](https://linux-hardware.org/?probe=3ad144c68e) | Dec 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [03b1209523](https://linux-hardware.org/?probe=03b1209523) | Dec 24, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [b7f3ca9ba4](https://linux-hardware.org/?probe=b7f3ca9ba4) | Dec 23, 2023 |
| VTEX          | NOTEBOOK                    | Notebook    | [972b407abc](https://linux-hardware.org/?probe=972b407abc) | Dec 22, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [e13dae2abd](https://linux-hardware.org/?probe=e13dae2abd) | Dec 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [176fc09667](https://linux-hardware.org/?probe=176fc09667) | Dec 08, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [f26cee0fe0](https://linux-hardware.org/?probe=f26cee0fe0) | Dec 08, 2023 |
| Unknown       | Unknown                     | Notebook    | [cbabf31d17](https://linux-hardware.org/?probe=cbabf31d17) | Dec 07, 2023 |
| HP            | 18E5                        | Desktop     | [7b54dc44b4](https://linux-hardware.org/?probe=7b54dc44b4) | Dec 06, 2023 |
| Dell          | Latitude E6420              | Notebook    | [dab1a90459](https://linux-hardware.org/?probe=dab1a90459) | Nov 22, 2023 |
| Unknown       | Unknown                     | Notebook    | [5e4b279442](https://linux-hardware.org/?probe=5e4b279442) | Nov 16, 2023 |
| Unknown       | Unknown                     | Notebook    | [2db8bb3ceb](https://linux-hardware.org/?probe=2db8bb3ceb) | Nov 14, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [547c61e762](https://linux-hardware.org/?probe=547c61e762) | Nov 06, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f23e44229f](https://linux-hardware.org/?probe=f23e44229f) | Nov 03, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [346fad17ff](https://linux-hardware.org/?probe=346fad17ff) | Oct 27, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [481d6c83fb](https://linux-hardware.org/?probe=481d6c83fb) | Oct 27, 2023 |
| Lenovo        | ThinkPad Yoga 11e 5th Ge... | Convertible | [f1b1a4603c](https://linux-hardware.org/?probe=f1b1a4603c) | Oct 25, 2023 |
| LG Electro... | 17ZT90P-G.AX33U1            | Notebook    | [0d53262cff](https://linux-hardware.org/?probe=0d53262cff) | Oct 23, 2023 |
| Unknown       | Unknown                     | Notebook    | [6fdc093168](https://linux-hardware.org/?probe=6fdc093168) | Oct 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [d14e5830b2](https://linux-hardware.org/?probe=d14e5830b2) | Oct 16, 2023 |
| Dell          | 0M5DCD A00                  | Desktop     | [02958738fb](https://linux-hardware.org/?probe=02958738fb) | Oct 14, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [305679af22](https://linux-hardware.org/?probe=305679af22) | Sep 14, 2023 |
| Dell          | Latitude E7440              | Notebook    | [7813372525](https://linux-hardware.org/?probe=7813372525) | Sep 11, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [74e5f6b8a5](https://linux-hardware.org/?probe=74e5f6b8a5) | Sep 08, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [d4df00af33](https://linux-hardware.org/?probe=d4df00af33) | Sep 08, 2023 |
| Dell          | XPS M1330                   | Notebook    | [ce3d41b222](https://linux-hardware.org/?probe=ce3d41b222) | Aug 27, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [945643bffa](https://linux-hardware.org/?probe=945643bffa) | Aug 16, 2023 |
| Dell          | Latitude E7250              | Notebook    | [7418a0dc06](https://linux-hardware.org/?probe=7418a0dc06) | Aug 12, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [522acc7a8e](https://linux-hardware.org/?probe=522acc7a8e) | Aug 02, 2023 |
| Dell          | Latitude 5590               | Notebook    | [466fdce7aa](https://linux-hardware.org/?probe=466fdce7aa) | Aug 01, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [e50470a456](https://linux-hardware.org/?probe=e50470a456) | Jul 22, 2023 |
| Acer          | AN515-44                    | Notebook    | [171bd20f26](https://linux-hardware.org/?probe=171bd20f26) | Jul 19, 2023 |
| Acer          | AN515-44                    | Notebook    | [c40876ce5f](https://linux-hardware.org/?probe=c40876ce5f) | Jul 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ebed32abef](https://linux-hardware.org/?probe=ebed32abef) | Jul 19, 2023 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [25f8458274](https://linux-hardware.org/?probe=25f8458274) | Jul 17, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [f687b7efe2](https://linux-hardware.org/?probe=f687b7efe2) | Jul 16, 2023 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [287b00885d](https://linux-hardware.org/?probe=287b00885d) | Jul 02, 2023 |
| HP            | 21EF                        | Desktop     | [6022eb31ff](https://linux-hardware.org/?probe=6022eb31ff) | Jun 21, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [93e28671fa](https://linux-hardware.org/?probe=93e28671fa) | Jun 18, 2023 |
| ASUSTek       | G750JM                      | Notebook    | [da1f33a87b](https://linux-hardware.org/?probe=da1f33a87b) | Jun 11, 2023 |
| Dell          | Latitude E6540              | Notebook    | [85520c9a0b](https://linux-hardware.org/?probe=85520c9a0b) | Jun 08, 2023 |
| Dell          | Latitude E6540              | Notebook    | [30f20f78ac](https://linux-hardware.org/?probe=30f20f78ac) | Jun 08, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [f9103674dc](https://linux-hardware.org/?probe=f9103674dc) | May 22, 2023 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [19416d3973](https://linux-hardware.org/?probe=19416d3973) | May 21, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [378acd7874](https://linux-hardware.org/?probe=378acd7874) | May 09, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [534af3636c](https://linux-hardware.org/?probe=534af3636c) | May 09, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [dd238f7e60](https://linux-hardware.org/?probe=dd238f7e60) | May 04, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [ea7f9b7eef](https://linux-hardware.org/?probe=ea7f9b7eef) | Apr 20, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [d3526466e8](https://linux-hardware.org/?probe=d3526466e8) | Apr 20, 2023 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [b7e04c4c41](https://linux-hardware.org/?probe=b7e04c4c41) | Apr 12, 2023 |
| ASRock        | H97M Pro4                   | Desktop     | [904fc9e194](https://linux-hardware.org/?probe=904fc9e194) | Apr 07, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [4b7801e829](https://linux-hardware.org/?probe=4b7801e829) | Mar 22, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [258c8aa62c](https://linux-hardware.org/?probe=258c8aa62c) | Mar 20, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [dca0487261](https://linux-hardware.org/?probe=dca0487261) | Mar 19, 2023 |
| Unknown       | Unknown                     | Notebook    | [7a44108d05](https://linux-hardware.org/?probe=7a44108d05) | Mar 16, 2023 |
| VTEX          | NOTEBOOK                    | Notebook    | [0b91c54846](https://linux-hardware.org/?probe=0b91c54846) | Mar 07, 2023 |
| VTEX          | NOTEBOOK                    | Notebook    | [4687219ca3](https://linux-hardware.org/?probe=4687219ca3) | Mar 07, 2023 |
| VTEX          | NOTEBOOK                    | Notebook    | [687328ccb0](https://linux-hardware.org/?probe=687328ccb0) | Mar 06, 2023 |
| VTEX          | NOTEBOOK                    | Notebook    | [b12a53ec1e](https://linux-hardware.org/?probe=b12a53ec1e) | Mar 06, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [0620aa7f6f](https://linux-hardware.org/?probe=0620aa7f6f) | Feb 25, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [df734c276f](https://linux-hardware.org/?probe=df734c276f) | Feb 25, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [00e573a880](https://linux-hardware.org/?probe=00e573a880) | Feb 23, 2023 |
| HP            | ProBook 4520s               | Notebook    | [8192287499](https://linux-hardware.org/?probe=8192287499) | Feb 19, 2023 |
| Dell          | Inspiron 5520               | Notebook    | [6de5bc549f](https://linux-hardware.org/?probe=6de5bc549f) | Jan 29, 2023 |
| Google        | Kip                         | Notebook    | [b450bb3bcf](https://linux-hardware.org/?probe=b450bb3bcf) | Jan 24, 2023 |
| Google        | Kip                         | Notebook    | [bf5c5ab5e6](https://linux-hardware.org/?probe=bf5c5ab5e6) | Jan 24, 2023 |
| Lenovo        | ThinkPad T420s 41732BU      | Notebook    | [fb42067a32](https://linux-hardware.org/?probe=fb42067a32) | Jan 20, 2023 |
| Google        | Kip                         | Notebook    | [e74935629a](https://linux-hardware.org/?probe=e74935629a) | Jan 17, 2023 |
| Google        | Kip                         | Notebook    | [558cff5048](https://linux-hardware.org/?probe=558cff5048) | Jan 17, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [4d2e9f3ee4](https://linux-hardware.org/?probe=4d2e9f3ee4) | Jan 16, 2023 |
| HP            | 18E5                        | Desktop     | [614faa708b](https://linux-hardware.org/?probe=614faa708b) | Jan 14, 2023 |
| Dell          | XPS M1330                   | Notebook    | [e3d66114f6](https://linux-hardware.org/?probe=e3d66114f6) | Jan 10, 2023 |
| Dell          | Latitude 5420               | Notebook    | [9fd9875465](https://linux-hardware.org/?probe=9fd9875465) | Dec 23, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [f9020b8dc6](https://linux-hardware.org/?probe=f9020b8dc6) | Dec 01, 2022 |
| Dell          | OptiPlex 3020               | Desktop     | [2adcd09348](https://linux-hardware.org/?probe=2adcd09348) | Nov 25, 2022 |
| Lenovo        | ThinkPad T420s 41732BU      | Notebook    | [ac7791c167](https://linux-hardware.org/?probe=ac7791c167) | Nov 24, 2022 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [1a1f5f8d90](https://linux-hardware.org/?probe=1a1f5f8d90) | Nov 22, 2022 |
| ASUSTek       | VivoBook 17_ASUS Laptop ... | Notebook    | [b2772ed1b3](https://linux-hardware.org/?probe=b2772ed1b3) | Nov 22, 2022 |
| Lenovo        | ThinkPad T490 20N3S7BC02    | Notebook    | [76a37f4e66](https://linux-hardware.org/?probe=76a37f4e66) | Nov 19, 2022 |
| Dell          | Latitude 5590               | Notebook    | [bbb332cf90](https://linux-hardware.org/?probe=bbb332cf90) | Nov 11, 2022 |
| Dell          | 0VNP2H A00                  | Desktop     | [dff6013531](https://linux-hardware.org/?probe=dff6013531) | Nov 09, 2022 |
| Eluktronic... | P670RE3                     | Notebook    | [d96ecdf7ab](https://linux-hardware.org/?probe=d96ecdf7ab) | Nov 08, 2022 |
| MSI           | GE62 6QC                    | Notebook    | [92ac4fbaa6](https://linux-hardware.org/?probe=92ac4fbaa6) | Oct 19, 2022 |
| EVOO          | EV-C-116-7                  | Notebook    | [ff4216edcd](https://linux-hardware.org/?probe=ff4216edcd) | Oct 18, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [240d883d49](https://linux-hardware.org/?probe=240d883d49) | Oct 12, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [cab829a52b](https://linux-hardware.org/?probe=cab829a52b) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [923a579655](https://linux-hardware.org/?probe=923a579655) | Oct 03, 2022 |
| Dell          | Latitude 2110               | Notebook    | [3fbbac2c8a](https://linux-hardware.org/?probe=3fbbac2c8a) | Oct 03, 2022 |
| Dell          | Latitude E6540              | Notebook    | [08bd609dbe](https://linux-hardware.org/?probe=08bd609dbe) | Sep 20, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [55cf772a79](https://linux-hardware.org/?probe=55cf772a79) | Sep 09, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3ea84baba3](https://linux-hardware.org/?probe=3ea84baba3) | Sep 09, 2022 |
| Dell          | Latitude E6420              | Notebook    | [78fd24b713](https://linux-hardware.org/?probe=78fd24b713) | Sep 09, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [9e48793165](https://linux-hardware.org/?probe=9e48793165) | Aug 18, 2022 |
| Gigabyte      | A520I AC                    | Desktop     | [0bf3f1a8a2](https://linux-hardware.org/?probe=0bf3f1a8a2) | Jul 31, 2022 |
| Gigabyte      | A520I AC                    | Desktop     | [f0d27ae2f0](https://linux-hardware.org/?probe=f0d27ae2f0) | Jul 30, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [2b09076619](https://linux-hardware.org/?probe=2b09076619) | Jul 30, 2022 |
| Dell          | OptiPlex 780                | Desktop     | [7a029315b9](https://linux-hardware.org/?probe=7a029315b9) | Jul 28, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [47dee227ba](https://linux-hardware.org/?probe=47dee227ba) | Jul 28, 2022 |
| Dell          | Latitude E5440              | Notebook    | [c8e68471c1](https://linux-hardware.org/?probe=c8e68471c1) | Jul 16, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [9cd0caeff2](https://linux-hardware.org/?probe=9cd0caeff2) | Jul 14, 2022 |
| ECS           | ClassMate                   | Notebook    | [c86fa72fe1](https://linux-hardware.org/?probe=c86fa72fe1) | Jun 13, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [fb6db84371](https://linux-hardware.org/?probe=fb6db84371) | Jun 11, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [578aee86ed](https://linux-hardware.org/?probe=578aee86ed) | May 27, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [e1e9853d49](https://linux-hardware.org/?probe=e1e9853d49) | May 26, 2022 |
| Dell          | 08NPPY A00                  | Desktop     | [62c1081de8](https://linux-hardware.org/?probe=62c1081de8) | May 23, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [3e9f067939](https://linux-hardware.org/?probe=3e9f067939) | May 13, 2022 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [c72447a3ea](https://linux-hardware.org/?probe=c72447a3ea) | May 03, 2022 |
| TODOS INDU... | Easytouch_2022_V1           | Notebook    | [efc26220c4](https://linux-hardware.org/?probe=efc26220c4) | May 01, 2022 |
| MSI           | CR70 2M/CX70 2OC/CX70 2O... | Notebook    | [454226474b](https://linux-hardware.org/?probe=454226474b) | Apr 29, 2022 |
| Gigabyte      | Z87X-UD5 TH-CF              | Desktop     | [5dc83ea64b](https://linux-hardware.org/?probe=5dc83ea64b) | Apr 24, 2022 |
| Unknown       | K8M800-8237                 | Desktop     | [791e4eeaae](https://linux-hardware.org/?probe=791e4eeaae) | Apr 07, 2022 |
| Unknown       | K8M800-8237                 | Desktop     | [3447b4c67a](https://linux-hardware.org/?probe=3447b4c67a) | Apr 07, 2022 |
| HP            | ENVY Laptop 13-ad0xx        | Notebook    | [9d5011b41d](https://linux-hardware.org/?probe=9d5011b41d) | Mar 23, 2022 |
| ASUSTek       | K53E                        | Notebook    | [3a0af085ae](https://linux-hardware.org/?probe=3a0af085ae) | Mar 17, 2022 |
| Dell          | 0CRH6C A02                  | Desktop     | [726633bbcc](https://linux-hardware.org/?probe=726633bbcc) | Feb 18, 2022 |
| Samsung       | 930QCG                      | Convertible | [fb417d6589](https://linux-hardware.org/?probe=fb417d6589) | Feb 18, 2022 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [2322337991](https://linux-hardware.org/?probe=2322337991) | Feb 15, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [507f27294e](https://linux-hardware.org/?probe=507f27294e) | Feb 15, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [b32bc24608](https://linux-hardware.org/?probe=b32bc24608) | Jan 26, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [53e23140c0](https://linux-hardware.org/?probe=53e23140c0) | Jan 23, 2022 |
| EVOO          | EV-C-116-7                  | Notebook    | [3fe03ac079](https://linux-hardware.org/?probe=3fe03ac079) | Jan 03, 2022 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [563f0e150e](https://linux-hardware.org/?probe=563f0e150e) | Dec 31, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [56d0201ca6](https://linux-hardware.org/?probe=56d0201ca6) | Dec 29, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [21f95ee091](https://linux-hardware.org/?probe=21f95ee091) | Dec 25, 2021 |
| Acer          | Aspire 5733Z                | Notebook    | [ea7511ce8d](https://linux-hardware.org/?probe=ea7511ce8d) | Dec 24, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [8e773bb4e5](https://linux-hardware.org/?probe=8e773bb4e5) | Dec 23, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [9f084a2062](https://linux-hardware.org/?probe=9f084a2062) | Dec 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9b89720cb4](https://linux-hardware.org/?probe=9b89720cb4) | Dec 14, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [b32fd5f07f](https://linux-hardware.org/?probe=b32fd5f07f) | Dec 07, 2021 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [d1843d03ba](https://linux-hardware.org/?probe=d1843d03ba) | Dec 04, 2021 |
| Lenovo        | ThinkPad T410 2537N99       | Notebook    | [a77255409f](https://linux-hardware.org/?probe=a77255409f) | Dec 02, 2021 |
| Lenovo        | ThinkPad T410 2537N99       | Notebook    | [ef02c2fb6c](https://linux-hardware.org/?probe=ef02c2fb6c) | Dec 02, 2021 |
| Dell          | 0T10XW A01                  | Desktop     | [9164883468](https://linux-hardware.org/?probe=9164883468) | Nov 27, 2021 |
| Dell          | 0T10XW A01                  | Desktop     | [b137bf3459](https://linux-hardware.org/?probe=b137bf3459) | Nov 27, 2021 |
| Lenovo        | G505s 20255                 | Notebook    | [8d3228452b](https://linux-hardware.org/?probe=8d3228452b) | Nov 20, 2021 |
| Lenovo        | ThinkPad T470 20HD004AUS    | Notebook    | [80fb4514c5](https://linux-hardware.org/?probe=80fb4514c5) | Oct 23, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [fb31c8d088](https://linux-hardware.org/?probe=fb31c8d088) | Oct 23, 2021 |
| Dell          | 0GTK4K A02                  | Desktop     | [044546d5fa](https://linux-hardware.org/?probe=044546d5fa) | Oct 19, 2021 |
| Dell          | Latitude E6410              | Notebook    | [bd65cdda08](https://linux-hardware.org/?probe=bd65cdda08) | Oct 08, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [7b2dcf44d9](https://linux-hardware.org/?probe=7b2dcf44d9) | Sep 08, 2021 |
| HP            | Pavilion dv6                | Notebook    | [5038083b91](https://linux-hardware.org/?probe=5038083b91) | Sep 07, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [e402a0b407](https://linux-hardware.org/?probe=e402a0b407) | Aug 31, 2021 |
| Dell          | Inspiron 5521               | Notebook    | [24bfc2b04a](https://linux-hardware.org/?probe=24bfc2b04a) | Aug 26, 2021 |
| HP            | 8265                        | Desktop     | [9a7e706a6b](https://linux-hardware.org/?probe=9a7e706a6b) | Aug 07, 2021 |
| Dell          | Inspiron 5521               | Notebook    | [8242b46551](https://linux-hardware.org/?probe=8242b46551) | Jul 29, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [7fc508d633](https://linux-hardware.org/?probe=7fc508d633) | Jul 19, 2021 |
| Google        | Winky                       | Notebook    | [696230b066](https://linux-hardware.org/?probe=696230b066) | Jul 14, 2021 |
| Google        | Winky                       | Notebook    | [6048ac2ff9](https://linux-hardware.org/?probe=6048ac2ff9) | Jul 14, 2021 |
| Acer          | Aspire 1810TZ               | Notebook    | [3ed828bab0](https://linux-hardware.org/?probe=3ed828bab0) | Jul 11, 2021 |
| Acer          | Aspire 1810TZ               | Notebook    | [9b650cfab3](https://linux-hardware.org/?probe=9b650cfab3) | Jul 11, 2021 |
| Dell          | Latitude E6420              | Notebook    | [fe42f53d85](https://linux-hardware.org/?probe=fe42f53d85) | Jul 11, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [772842d291](https://linux-hardware.org/?probe=772842d291) | Jul 06, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [891b06178e](https://linux-hardware.org/?probe=891b06178e) | Jun 29, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [cc6035ae99](https://linux-hardware.org/?probe=cc6035ae99) | Jun 28, 2021 |
| SAELITE       | ES1AU11                     | Notebook    | [267ea9c15e](https://linux-hardware.org/?probe=267ea9c15e) | Jun 26, 2021 |
| SAELITE       | ES1AU11                     | Notebook    | [25dc027ef1](https://linux-hardware.org/?probe=25dc027ef1) | Jun 26, 2021 |
| Dell          | Latitude E6530              | Notebook    | [fda4879b12](https://linux-hardware.org/?probe=fda4879b12) | Jun 19, 2021 |
| Dell          | Latitude E6530              | Notebook    | [40566262f5](https://linux-hardware.org/?probe=40566262f5) | Jun 11, 2021 |
| Dell          | Latitude E6430              | Notebook    | [9ec2685f9d](https://linux-hardware.org/?probe=9ec2685f9d) | Jun 04, 2021 |
| Dell          | Latitude E6430              | Notebook    | [6098210314](https://linux-hardware.org/?probe=6098210314) | Jun 04, 2021 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [5343885c32](https://linux-hardware.org/?probe=5343885c32) | May 17, 2021 |
| Dell          | Inspiron 3541               | Notebook    | [2170036527](https://linux-hardware.org/?probe=2170036527) | May 17, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [d310246b09](https://linux-hardware.org/?probe=d310246b09) | Apr 30, 2021 |
| Dell          | Latitude D830               | Notebook    | [f6f0884fca](https://linux-hardware.org/?probe=f6f0884fca) | Apr 28, 2021 |
| Dell          | Latitude E6540              | Notebook    | [522d36a07e](https://linux-hardware.org/?probe=522d36a07e) | Apr 21, 2021 |
| Dell          | Latitude E6540              | Notebook    | [3c76496221](https://linux-hardware.org/?probe=3c76496221) | Apr 21, 2021 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [dc8b47f73d](https://linux-hardware.org/?probe=dc8b47f73d) | Feb 14, 2021 |
| Dell          | 0F6X5P A00                  | Desktop     | [4adcccb57c](https://linux-hardware.org/?probe=4adcccb57c) | Feb 14, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [96d33743db](https://linux-hardware.org/?probe=96d33743db) | Jan 24, 2021 |
| Unknown       | Unknown                     | Desktop     | [2cf1c789ec](https://linux-hardware.org/?probe=2cf1c789ec) | Dec 29, 2020 |
| Lenovo        | ThinkPad E470 20H1006DUS    | Notebook    | [3c51b58a24](https://linux-hardware.org/?probe=3c51b58a24) | Dec 14, 2020 |
| Lenovo        | ThinkBook 14s-IWL 20RM      | Notebook    | [f18b7b439b](https://linux-hardware.org/?probe=f18b7b439b) | Dec 05, 2020 |
| Fujitsu       | LIFEBOOK AH562              | Notebook    | [68c670f9e0](https://linux-hardware.org/?probe=68c670f9e0) | Dec 01, 2020 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [012580c2a7](https://linux-hardware.org/?probe=012580c2a7) | Nov 10, 2020 |
| HP            | Notebook                    | Notebook    | [5176e73c5a](https://linux-hardware.org/?probe=5176e73c5a) | Oct 27, 2020 |
| ASUSTek       | X553MA                      | Notebook    | [d6729d6c6a](https://linux-hardware.org/?probe=d6729d6c6a) | Oct 17, 2020 |
| Samsung       | RV420/RV520/RV720/E3530/... | Notebook    | [907bc464e9](https://linux-hardware.org/?probe=907bc464e9) | Oct 13, 2020 |
| HP            | EliteBook 8540w             | Notebook    | [03c52e4d49](https://linux-hardware.org/?probe=03c52e4d49) | Oct 10, 2020 |
| Lenovo        | ThinkPad P43s 20RH0013US    | Notebook    | [e540cc2901](https://linux-hardware.org/?probe=e540cc2901) | Oct 09, 2020 |
| HP            | 3647h                       | Desktop     | [5788758b90](https://linux-hardware.org/?probe=5788758b90) | Oct 08, 2020 |
| Dell          | 0MM599                      | Desktop     | [fce90bd449](https://linux-hardware.org/?probe=fce90bd449) | Oct 06, 2020 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [fd73b699f6](https://linux-hardware.org/?probe=fd73b699f6) | Oct 05, 2020 |
| Dell          | Latitude D620               | Notebook    | [3832d0c33e](https://linux-hardware.org/?probe=3832d0c33e) | Sep 29, 2020 |
| Dell          | Inspiron 5555               | Notebook    | [a7be8edb39](https://linux-hardware.org/?probe=a7be8edb39) | Sep 28, 2020 |
| Dell          | Inspiron 5555               | Notebook    | [079a8b39a7](https://linux-hardware.org/?probe=079a8b39a7) | Sep 27, 2020 |
| HP            | Laptop 15-bw0xx             | Notebook    | [80611690cf](https://linux-hardware.org/?probe=80611690cf) | Sep 13, 2020 |
| Dell          | Latitude D620               | Notebook    | [d14cb277b7](https://linux-hardware.org/?probe=d14cb277b7) | Sep 12, 2020 |
| HP            | ProBook 6470b               | Notebook    | [c622e7298d](https://linux-hardware.org/?probe=c622e7298d) | Sep 07, 2020 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [9b34b0a6c3](https://linux-hardware.org/?probe=9b34b0a6c3) | Sep 03, 2020 |
| Dell          | Vostro 5471                 | Notebook    | [6d24c75bcf](https://linux-hardware.org/?probe=6d24c75bcf) | Sep 03, 2020 |
| MSI           | H81M-E33                    | Desktop     | [d24cd3858d](https://linux-hardware.org/?probe=d24cd3858d) | Aug 29, 2020 |
| Nuvision      | L1W6_I1101_G Reserved       | Notebook    | [b3e73aa9ba](https://linux-hardware.org/?probe=b3e73aa9ba) | Aug 29, 2020 |
| MSI           | H81M-E33                    | Desktop     | [9eda45f755](https://linux-hardware.org/?probe=9eda45f755) | Aug 20, 2020 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [d7d672869f](https://linux-hardware.org/?probe=d7d672869f) | Aug 16, 2020 |
| MSI           | H81M-E33                    | Desktop     | [ba3577fb00](https://linux-hardware.org/?probe=ba3577fb00) | Aug 14, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [081a2c3e4c](https://linux-hardware.org/?probe=081a2c3e4c) | Aug 03, 2020 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [8eb28a49c4](https://linux-hardware.org/?probe=8eb28a49c4) | Aug 03, 2020 |
| MSI           | H81M-E33                    | Desktop     | [6bedf88c28](https://linux-hardware.org/?probe=6bedf88c28) | Jul 30, 2020 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [fcbd102a50](https://linux-hardware.org/?probe=fcbd102a50) | Jul 30, 2020 |
| MSI           | B350 GAMING PLUS            | Desktop     | [ca22d3b169](https://linux-hardware.org/?probe=ca22d3b169) | Jul 24, 2020 |
| ASRock        | G41M-VS3                    | Desktop     | [4877877772](https://linux-hardware.org/?probe=4877877772) | Jul 04, 2020 |
| Dell          | Vostro A860                 | Notebook    | [16ded4e283](https://linux-hardware.org/?probe=16ded4e283) | Jun 28, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [093c4d226c](https://linux-hardware.org/?probe=093c4d226c) | Jun 28, 2020 |
| MSI           | H81M-E33                    | Desktop     | [2d531766ab](https://linux-hardware.org/?probe=2d531766ab) | Jun 26, 2020 |
| HP            | 250 G3                      | Notebook    | [1862b881c0](https://linux-hardware.org/?probe=1862b881c0) | Jun 23, 2020 |
| Acer          | Aspire one 1-431            | Notebook    | [80f65d1ab4](https://linux-hardware.org/?probe=80f65d1ab4) | Jun 23, 2020 |
| Biostar       | G41D3C                      | Desktop     | [15959c0828](https://linux-hardware.org/?probe=15959c0828) | Jun 15, 2020 |
| Acer          | Aspire one 1-431            | Notebook    | [5994ea3a38](https://linux-hardware.org/?probe=5994ea3a38) | Jun 09, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [4003a55819](https://linux-hardware.org/?probe=4003a55819) | Jun 03, 2020 |
| Samsung       | 905S3G/906S3G/915S3G/930... | Notebook    | [131d3a17f3](https://linux-hardware.org/?probe=131d3a17f3) | May 30, 2020 |
| Dell          | Vostro A860                 | Notebook    | [35d08abb65](https://linux-hardware.org/?probe=35d08abb65) | May 20, 2020 |
| Dell          | Latitude E6410              | Notebook    | [4e98eb67c5](https://linux-hardware.org/?probe=4e98eb67c5) | May 19, 2020 |
| Dell          | Latitude 3340               | Notebook    | [a8795064a1](https://linux-hardware.org/?probe=a8795064a1) | May 18, 2020 |
| Dell          | Latitude 3340               | Notebook    | [a07d882043](https://linux-hardware.org/?probe=a07d882043) | May 18, 2020 |
| Dell          | Latitude E6430              | Notebook    | [4316261d97](https://linux-hardware.org/?probe=4316261d97) | May 15, 2020 |
| Dell          | Latitude E6430              | Notebook    | [eef205a77d](https://linux-hardware.org/?probe=eef205a77d) | May 14, 2020 |
| HP            | G60                         | Notebook    | [90ec25f151](https://linux-hardware.org/?probe=90ec25f151) | May 13, 2020 |
| HP            | G60                         | Notebook    | [0b84216baf](https://linux-hardware.org/?probe=0b84216baf) | May 13, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [1b33a3d155](https://linux-hardware.org/?probe=1b33a3d155) | May 03, 2020 |
| Dell          | Latitude E6430              | Notebook    | [5a74b9f950](https://linux-hardware.org/?probe=5a74b9f950) | May 03, 2020 |
| Dell          | Latitude E6430              | Notebook    | [31e36437f4](https://linux-hardware.org/?probe=31e36437f4) | May 03, 2020 |
| Dell          | Latitude E6410              | Notebook    | [125cc5d7fd](https://linux-hardware.org/?probe=125cc5d7fd) | Apr 26, 2020 |
| HP            | 3031h                       | Desktop     | [0278ac4043](https://linux-hardware.org/?probe=0278ac4043) | Apr 07, 2020 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [87496c419f](https://linux-hardware.org/?probe=87496c419f) | Apr 07, 2020 |
| Dell          | 0WG864                      | Desktop     | [b7c74749f8](https://linux-hardware.org/?probe=b7c74749f8) | Mar 30, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [860893085c](https://linux-hardware.org/?probe=860893085c) | Mar 29, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [48e8186c4f](https://linux-hardware.org/?probe=48e8186c4f) | Mar 28, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [080f6bbb80](https://linux-hardware.org/?probe=080f6bbb80) | Mar 28, 2020 |
| ASUSTek       | V230IC-DDR4                 | All in one  | [740334eed7](https://linux-hardware.org/?probe=740334eed7) | Mar 28, 2020 |
| Dell          | Latitude 3330               | Notebook    | [4033fca5eb](https://linux-hardware.org/?probe=4033fca5eb) | Mar 22, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [44fe9bdc7d](https://linux-hardware.org/?probe=44fe9bdc7d) | Mar 20, 2020 |
| Foxconn       | 2ABF                        | Desktop     | [970faeadaf](https://linux-hardware.org/?probe=970faeadaf) | Mar 19, 2020 |
| HP            | 3031h                       | Desktop     | [3b10a92ee2](https://linux-hardware.org/?probe=3b10a92ee2) | Mar 19, 2020 |
| ASUSTek       | H170 PRO GAMING             | Desktop     | [4f152e3015](https://linux-hardware.org/?probe=4f152e3015) | Mar 06, 2020 |
| Dell          | 06D7TR A00                  | Desktop     | [4775efe228](https://linux-hardware.org/?probe=4775efe228) | Feb 27, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | Notebook    | [185bf79f49](https://linux-hardware.org/?probe=185bf79f49) | Feb 08, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | Notebook    | [cb7950841c](https://linux-hardware.org/?probe=cb7950841c) | Feb 07, 2020 |
| Lenovo        | ThinkPad W540 20BHS0GB06    | Notebook    | [3212549df1](https://linux-hardware.org/?probe=3212549df1) | Feb 05, 2020 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [661a8243a3](https://linux-hardware.org/?probe=661a8243a3) | Feb 01, 2020 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [ee353d9346](https://linux-hardware.org/?probe=ee353d9346) | Feb 01, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [51c3c0bb31](https://linux-hardware.org/?probe=51c3c0bb31) | Jan 07, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [4df330ed80](https://linux-hardware.org/?probe=4df330ed80) | Jan 07, 2020 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [a61df97ccd](https://linux-hardware.org/?probe=a61df97ccd) | Dec 19, 2019 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [4437a2deed](https://linux-hardware.org/?probe=4437a2deed) | Dec 18, 2019 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [edddb5eb5b](https://linux-hardware.org/?probe=edddb5eb5b) | Dec 18, 2019 |
| Apple         | MacBookPro5,5               | Notebook    | [e4a03527b5](https://linux-hardware.org/?probe=e4a03527b5) | Dec 11, 2019 |
| Toshiba       | Satellite C55-A             | Notebook    | [a760ea9cb2](https://linux-hardware.org/?probe=a760ea9cb2) | Nov 14, 2019 |
| Toshiba       | Satellite C55-A             | Notebook    | [b2477d7154](https://linux-hardware.org/?probe=b2477d7154) | Nov 07, 2019 |
| Gigabyte      | B450 AORUS M                | Desktop     | [628a2983df](https://linux-hardware.org/?probe=628a2983df) | Nov 05, 2019 |
| Apple         | MacBookPro5,5               | Notebook    | [cb7b5a4d2e](https://linux-hardware.org/?probe=cb7b5a4d2e) | Oct 13, 2019 |
| Dell          | Latitude E6430              | Notebook    | [49d71b26e7](https://linux-hardware.org/?probe=49d71b26e7) | Oct 08, 2019 |
| Dell          | Latitude E6430              | Notebook    | [b3ef7b4357](https://linux-hardware.org/?probe=b3ef7b4357) | Oct 06, 2019 |
| Dell          | 0M132G A00                  | Desktop     | [b79e419f05](https://linux-hardware.org/?probe=b79e419f05) | Aug 24, 2019 |
| Apple         | MacBookPro5,5               | Notebook    | [9a7d44bf28](https://linux-hardware.org/?probe=9a7d44bf28) | Aug 15, 2019 |
| HP            | Pavilion ze2000 (EC201UA... | Notebook    | [572baa05f4](https://linux-hardware.org/?probe=572baa05f4) | Jun 15, 2019 |
| HP            | 3397                        | Desktop     | [24770f4baf](https://linux-hardware.org/?probe=24770f4baf) | Jun 06, 2019 |
| ASUSTek       | T100TA                      | Notebook    | [412e4da0ce](https://linux-hardware.org/?probe=412e4da0ce) | May 21, 2019 |
| HP            | 3396                        | Desktop     | [46d189dc80](https://linux-hardware.org/?probe=46d189dc80) | May 20, 2019 |
| Lenovo        | G40-70 20369                | Notebook    | [1f456620db](https://linux-hardware.org/?probe=1f456620db) | May 05, 2019 |
| HP            | Laptop 15-bw0xx             | Notebook    | [0b9c00412b](https://linux-hardware.org/?probe=0b9c00412b) | Dec 14, 2018 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [e30bc2b8f2](https://linux-hardware.org/?probe=e30bc2b8f2) | Nov 02, 2018 |
| Dell          | 0PU052                      | Desktop     | [a5f063bc44](https://linux-hardware.org/?probe=a5f063bc44) | Apr 19, 2018 |
| Dell          | 0PU052                      | Desktop     | [e8fb115c06](https://linux-hardware.org/?probe=e8fb115c06) | Jan 25, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 22        | 9.57%   |
| Ubuntu 18.04                 | 17        | 7.39%   |
| Arch Rolling                 | 15        | 6.52%   |
| Ubuntu 22.04                 | 13        | 5.65%   |
| OpenMandriva 4.3             | 7         | 3.04%   |
| Fedora 40                    | 6         | 2.61%   |
| Fedora 38                    | 6         | 2.61%   |
| OpenMandriva 4.2             | 5         | 2.17%   |
| Ubuntu 24.04                 | 4         | 1.74%   |
| OpenMandriva 23.03           | 4         | 1.74%   |
| Manjaro                      | 4         | 1.74%   |
| Fedora 39                    | 4         | 1.74%   |
| Fedora 37                    | 4         | 1.74%   |
| Fedora 36                    | 4         | 1.74%   |
| Zorin 16                     | 3         | 1.3%    |
| Linux Mint 20.3              | 3         | 1.3%    |
| KDE neon 22.04               | 3         | 1.3%    |
| Kali 2023.3                  | 3         | 1.3%    |
| Fedora 34                    | 3         | 1.3%    |
| Debian 12                    | 3         | 1.3%    |
| Debian 11                    | 3         | 1.3%    |
| Arch                         | 3         | 1.3%    |
| Ubuntu 22.10                 | 2         | 0.87%   |
| Ubuntu 21.10                 | 2         | 0.87%   |
| Pop!_OS 22.04                | 2         | 0.87%   |
| Pop!_OS 20.10                | 2         | 0.87%   |
| openSUSE Tumbleweed-XXXXXXXX | 2         | 0.87%   |
| OpenMandriva 5.0             | 2         | 0.87%   |
| OpenMandriva 24.07           | 2         | 0.87%   |
| OpenMandriva 23.08           | 2         | 0.87%   |
| Linux Mint 21                | 2         | 0.87%   |
| Linux Mint 20.1              | 2         | 0.87%   |
| Linux Mint 19.3              | 2         | 0.87%   |
| Kali 2023.4                  | 2         | 0.87%   |
| Fedora 33                    | 2         | 0.87%   |
| ArcoLinux Rolling            | 2         | 0.87%   |
| Zorin 17                     | 1         | 0.43%   |
| Xubuntu 19.10                | 1         | 0.43%   |
| Xubuntu 18.04                | 1         | 0.43%   |
| Void Linux Rolling           | 1         | 0.43%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 60        | 27.4%   |
| Fedora        | 27        | 12.33%  |
| OpenMandriva  | 22        | 10.05%  |
| Arch          | 18        | 8.22%   |
| Linux Mint    | 13        | 5.94%   |
| Manjaro       | 10        | 4.57%   |
| Kali          | 9         | 4.11%   |
| Debian        | 8         | 3.65%   |
| Pop!_OS       | 6         | 2.74%   |
| KDE neon      | 5         | 2.28%   |
| Zorin         | 4         | 1.83%   |
| Ubuntu Budgie | 3         | 1.37%   |
| Lubuntu       | 3         | 1.37%   |
| Clear Linux   | 3         | 1.37%   |
| Xubuntu       | 2         | 0.91%   |
| ROSA          | 2         | 0.91%   |
| openSUSE      | 2         | 0.91%   |
| MX            | 2         | 0.91%   |
| LMDE          | 2         | 0.91%   |
| Kubuntu       | 2         | 0.91%   |
| Endless       | 2         | 0.91%   |
| ArcoLinux     | 2         | 0.91%   |
| Void Linux    | 1         | 0.46%   |
| Ubuntu MATE   | 1         | 0.46%   |
| Solus         | 1         | 0.46%   |
| Nobara        | 1         | 0.46%   |
| Garuda Linux  | 1         | 0.46%   |
| Gabian        | 1         | 0.46%   |
| Elementary    | 1         | 0.46%   |
| CentOS        | 1         | 0.46%   |
| CachyOS       | 1         | 0.46%   |
| blendOS       | 1         | 0.46%   |
| BlackPanther  | 1         | 0.46%   |
| Archcraft     | 1         | 0.46%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 7         | 2.77%   |
| 5.4.0-48-generic         | 4         | 1.58%   |
| 5.4.0-42-generic         | 4         | 1.58%   |
| 5.10.14-desktop-1omv4002 | 4         | 1.58%   |
| 6.2.6-desktop-1omv2390   | 3         | 1.19%   |
| 5.19.0-46-generic        | 3         | 1.19%   |
| 5.15.0-53-generic        | 3         | 1.19%   |
| 5.13.0-22-generic        | 3         | 1.19%   |
| 6.8.0-41-generic         | 2         | 0.79%   |
| 6.6.2-desktop-1omv2390   | 2         | 0.79%   |
| 6.6.15-amd64             | 2         | 0.79%   |
| 6.5.6-300.fc39.x86_64    | 2         | 0.79%   |
| 6.5.0-kali3-amd64        | 2         | 0.79%   |
| 6.5.0-kali2-amd64        | 2         | 0.79%   |
| 6.4.8-desktop-2omv2390   | 2         | 0.79%   |
| 6.1.1-desktop-1omv2290   | 2         | 0.79%   |
| 6.1.0-21-amd64           | 2         | 0.79%   |
| 5.4.0-77-generic         | 2         | 0.79%   |
| 5.4.0-52-generic         | 2         | 0.79%   |
| 5.4.0-33-generic         | 2         | 0.79%   |
| 5.3.0-51-generic         | 2         | 0.79%   |
| 5.3.0-46-generic         | 2         | 0.79%   |
| 5.3.0-42-generic         | 2         | 0.79%   |
| 5.19.0-32-generic        | 2         | 0.79%   |
| 5.15.0-76-generic        | 2         | 0.79%   |
| 5.15.0-58-generic        | 2         | 0.79%   |
| 5.15.0-50-generic        | 2         | 0.79%   |
| 5.15.0-41-generic        | 2         | 0.79%   |
| 5.11.0-40-generic        | 2         | 0.79%   |
| 5.11.0-25-generic        | 2         | 0.79%   |
| 5.0.0-32-generic         | 2         | 0.79%   |
| 6.9.9-amd64              | 1         | 0.4%    |
| 6.9.7-desktop-1omv2490   | 1         | 0.4%    |
| 6.9.4-200.fc40.x86_64    | 1         | 0.4%    |
| 6.9.10-200.fc40.x86_64   | 1         | 0.4%    |
| 6.8.7-zen1-2-zen         | 1         | 0.4%    |
| 6.8.7-arch1-1            | 1         | 0.4%    |
| 6.8.7-300.fc40.x86_64    | 1         | 0.4%    |
| 6.8.5-301.fc40.x86_64    | 1         | 0.4%    |
| 6.8.11-300.fc40.x86_64   | 1         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 25        | 10.46%  |
| 5.15.0  | 18        | 7.53%   |
| 5.13.0  | 11        | 4.6%    |
| 6.5.0   | 9         | 3.77%   |
| 5.3.0   | 9         | 3.77%   |
| 5.19.0  | 8         | 3.35%   |
| 5.11.0  | 8         | 3.35%   |
| 6.8.0   | 7         | 2.93%   |
| 5.16.7  | 7         | 2.93%   |
| 4.15.0  | 6         | 2.51%   |
| 5.0.0   | 5         | 2.09%   |
| 5.10.14 | 4         | 1.67%   |
| 5.10.0  | 4         | 1.67%   |
| 6.8.7   | 3         | 1.26%   |
| 6.5.6   | 3         | 1.26%   |
| 6.2.6   | 3         | 1.26%   |
| 6.1.0   | 3         | 1.26%   |
| 6.7.0   | 2         | 0.84%   |
| 6.6.8   | 2         | 0.84%   |
| 6.6.2   | 2         | 0.84%   |
| 6.6.15  | 2         | 0.84%   |
| 6.5.7   | 2         | 0.84%   |
| 6.4.8   | 2         | 0.84%   |
| 6.4.15  | 2         | 0.84%   |
| 6.3.7   | 2         | 0.84%   |
| 6.11.0  | 2         | 0.84%   |
| 6.1.1   | 2         | 0.84%   |
| 5.7.7   | 2         | 0.84%   |
| 4.19.0  | 2         | 0.84%   |
| 4.18.0  | 2         | 0.84%   |
| 6.9.9   | 1         | 0.42%   |
| 6.9.7   | 1         | 0.42%   |
| 6.9.4   | 1         | 0.42%   |
| 6.9.10  | 1         | 0.42%   |
| 6.8.5   | 1         | 0.42%   |
| 6.8.11  | 1         | 0.42%   |
| 6.6.9   | 1         | 0.42%   |
| 6.6.6   | 1         | 0.42%   |
| 6.6.26  | 1         | 0.42%   |
| 6.6.10  | 1         | 0.42%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 28        | 11.97%  |
| 5.15    | 21        | 8.97%   |
| 6.5     | 16        | 6.84%   |
| 5.13    | 12        | 5.13%   |
| 6.8     | 11        | 4.7%    |
| 5.19    | 11        | 4.7%    |
| 5.10    | 11        | 4.7%    |
| 6.6     | 10        | 4.27%   |
| 5.11    | 10        | 4.27%   |
| 5.3     | 9         | 3.85%   |
| 6.2     | 7         | 2.99%   |
| 6.1     | 7         | 2.99%   |
| 5.16    | 7         | 2.99%   |
| 6.4     | 6         | 2.56%   |
| 6.10    | 6         | 2.56%   |
| 5.0     | 6         | 2.56%   |
| 4.15    | 6         | 2.56%   |
| 5.8     | 5         | 2.14%   |
| 6.9     | 4         | 1.71%   |
| 6.11    | 4         | 1.71%   |
| 5.9     | 4         | 1.71%   |
| 5.18    | 4         | 1.71%   |
| 5.12    | 4         | 1.71%   |
| 4.18    | 4         | 1.71%   |
| 6.3     | 3         | 1.28%   |
| 5.7     | 3         | 1.28%   |
| 4.19    | 3         | 1.28%   |
| 6.7     | 2         | 0.85%   |
| 6.0     | 2         | 0.85%   |
| 5.17    | 2         | 0.85%   |
| 5.1     | 2         | 0.85%   |
| 5.6     | 1         | 0.43%   |
| 5.5     | 1         | 0.43%   |
| 5.14    | 1         | 0.43%   |
| 4.9     | 1         | 0.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 211       | 98.14%  |
| i686   | 4         | 1.86%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 98        | 43.75%  |
| KDE5          | 46        | 20.54%  |
| XFCE          | 20        | 8.93%   |
| Unknown       | 16        | 7.14%   |
| X-Cinnamon    | 12        | 5.36%   |
| KDE6          | 6         | 2.68%   |
| Budgie        | 5         | 2.23%   |
| MATE          | 4         | 1.79%   |
| LXQt          | 4         | 1.79%   |
| KDE           | 4         | 1.79%   |
| Hyprland      | 2         | 0.89%   |
| sway          | 1         | 0.45%   |
| qtile         | 1         | 0.45%   |
| LXDE          | 1         | 0.45%   |
| KDE4          | 1         | 0.45%   |
| GNOME Classic | 1         | 0.45%   |
| Endless:GNOME | 1         | 0.45%   |
| DWM           | 1         | 0.45%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 149       | 67.73%  |
| Wayland | 62        | 28.18%  |
| Unknown | 6         | 2.73%   |
| Tty     | 3         | 1.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 102       | 46.36%  |
| SDDM    | 44        | 20%     |
| GDM3    | 23        | 10.45%  |
| GDM     | 23        | 10.45%  |
| LightDM | 22        | 10%     |
| TDM     | 4         | 1.82%   |
| LY-DM   | 1         | 0.45%   |
| KDM     | 1         | 0.45%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 113       | 50.45%  |
| es_DO   | 60        | 26.79%  |
| Unknown | 14        | 6.25%   |
| es_ES   | 9         | 4.02%   |
| es_MX   | 8         | 3.57%   |
| C       | 8         | 3.57%   |
| es_US   | 6         | 2.68%   |
| en_CA   | 2         | 0.89%   |
| ru_RU   | 1         | 0.45%   |
| fr_HT   | 1         | 0.45%   |
| fr_FR   | 1         | 0.45%   |
| es_AR   | 1         | 0.45%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 122       | 54.95%  |
| EFI  | 100       | 45.05%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 150       | 67.57%  |
| Btrfs   | 32        | 14.41%  |
| Overlay | 21        | 9.46%   |
| Tmpfs   | 10        | 4.5%    |
| Xfs     | 4         | 1.8%    |
| Zfs     | 2         | 0.9%    |
| Unknown | 2         | 0.9%    |
| F2fs    | 1         | 0.45%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 107       | 48.42%  |
| GPT     | 92        | 41.63%  |
| MBR     | 22        | 9.95%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 183       | 84.33%  |
| Yes       | 34        | 15.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 155       | 70.78%  |
| Yes       | 64        | 29.22%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Dell                | 61        | 28.37%  |
| Hewlett-Packard     | 33        | 15.35%  |
| Lenovo              | 27        | 12.56%  |
| ASUSTek Computer    | 17        | 7.91%   |
| Gigabyte Technology | 14        | 6.51%   |
| Apple               | 10        | 4.65%   |
| Acer                | 8         | 3.72%   |
| Unknown             | 7         | 3.26%   |
| MSI                 | 5         | 2.33%   |
| ASRock              | 4         | 1.86%   |
| Samsung Electronics | 3         | 1.4%    |
| Google              | 3         | 1.4%    |
| VTEX                | 2         | 0.93%   |
| TODOS INDUSTRIAL    | 2         | 0.93%   |
| Foxconn             | 2         | 0.93%   |
| EVOO                | 2         | 0.93%   |
| Chuwi               | 2         | 0.93%   |
| Toshiba             | 1         | 0.47%   |
| SAELITE             | 1         | 0.47%   |
| Nuvision            | 1         | 0.47%   |
| Microsoft           | 1         | 0.47%   |
| LG Electronics      | 1         | 0.47%   |
| Intel               | 1         | 0.47%   |
| GPU Company         | 1         | 0.47%   |
| Fujitsu             | 1         | 0.47%   |
| Eluktronics         | 1         | 0.47%   |
| ECS                 | 1         | 0.47%   |
| Biostar             | 1         | 0.47%   |
| AZW                 | 1         | 0.47%   |
| AMI                 | 1         | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Unknown                                           | 8         | 3.72%   |
| Gigabyte GA-78LMT-USB3 6.0                        | 3         | 1.4%    |
| Dell Latitude E6430                               | 3         | 1.4%    |
| Dell Latitude E6420                               | 3         | 1.4%    |
| Apple MacBookPro8,1                               | 3         | 1.4%    |
| Apple MacBookAir7,2                               | 3         | 1.4%    |
| VTEX NOTEBOOK                                     | 2         | 0.93%   |
| Lenovo IdeaPad 330S-15IKB 81F5                    | 2         | 0.93%   |
| HP Pavilion Notebook                              | 2         | 0.93%   |
| HP Pavilion Gaming Laptop 15-dk0xxx               | 2         | 0.93%   |
| HP Laptop 15-dy1xxx                               | 2         | 0.93%   |
| HP EliteBook 8460p                                | 2         | 0.93%   |
| EVOO EV-C-116-7                                   | 2         | 0.93%   |
| Dell OptiPlex 990                                 | 2         | 0.93%   |
| Dell OptiPlex 9020                                | 2         | 0.93%   |
| Dell OptiPlex 390                                 | 2         | 0.93%   |
| Dell OptiPlex 3010                                | 2         | 0.93%   |
| Dell Latitude E6540                               | 2         | 0.93%   |
| Dell Latitude E6410                               | 2         | 0.93%   |
| Dell Latitude 5590                                | 2         | 0.93%   |
| Dell Latitude 3330                                | 2         | 0.93%   |
| Dell Inspiron 5570                                | 2         | 0.93%   |
| Dell Inspiron 5555                                | 2         | 0.93%   |
| Toshiba Satellite C55-A                           | 1         | 0.47%   |
| TODOS INDUSTRIAL Easytouch_2022_V1                | 1         | 0.47%   |
| TODOS INDUSTRIAL Aprix_2022_V1                    | 1         | 0.47%   |
| Samsung RV420/RV520/RV720/E3530/S3530/E3420/E3520 | 1         | 0.47%   |
| Samsung 930QCG                                    | 1         | 0.47%   |
| Samsung 905S3G/906S3G/915S3G/9305SG               | 1         | 0.47%   |
| SAELITE ES1AU11                                   | 1         | 0.47%   |
| Nuvision NES11                                    | 1         | 0.47%   |
| MSI MS-7C83                                       | 1         | 0.47%   |
| MSI MS-7A34                                       | 1         | 0.47%   |
| MSI MS-7817                                       | 1         | 0.47%   |
| MSI GE62 6QC                                      | 1         | 0.47%   |
| MSI CR70 2M/CX70 2OC/CX70 2OD                     | 1         | 0.47%   |
| Microsoft Surface Go                              | 1         | 0.47%   |
| LG 17ZT90P-G.AX33U1                               | 1         | 0.47%   |
| Lenovo Z50-75 80EC                                | 1         | 0.47%   |
| Lenovo Yoga 520-14IKB 80X8                        | 1         | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                       | Computers | Percent |
|----------------------------|-----------|---------|
| Dell Latitude              | 24        | 11.16%  |
| Dell OptiPlex              | 16        | 7.44%   |
| Dell Inspiron              | 14        | 6.51%   |
| Lenovo ThinkPad            | 11        | 5.12%   |
| Unknown                    | 8         | 3.72%   |
| Lenovo IdeaPad             | 7         | 3.26%   |
| Acer Aspire                | 7         | 3.26%   |
| HP Pavilion                | 6         | 2.79%   |
| HP Compaq                  | 6         | 2.79%   |
| HP Laptop                  | 5         | 2.33%   |
| Gigabyte GA-78LMT-USB3     | 4         | 1.86%   |
| ASUS VivoBook              | 4         | 1.86%   |
| HP ProBook                 | 3         | 1.4%    |
| HP EliteBook               | 3         | 1.4%    |
| Apple MacBookPro8          | 3         | 1.4%    |
| Apple MacBookAir7          | 3         | 1.4%    |
| VTEX NOTEBOOK              | 2         | 0.93%   |
| Lenovo Legion              | 2         | 0.93%   |
| HP EliteDesk               | 2         | 0.93%   |
| Gigabyte B450M             | 2         | 0.93%   |
| EVOO EV-C-116-7            | 2         | 0.93%   |
| Dell Vostro                | 2         | 0.93%   |
| Toshiba Satellite          | 1         | 0.47%   |
| TODOS INDUSTRIAL Easytouch | 1         | 0.47%   |
| TODOS INDUSTRIAL Aprix     | 1         | 0.47%   |
| Samsung RV420              | 1         | 0.47%   |
| Samsung 930QCG             | 1         | 0.47%   |
| Samsung 905S3G             | 1         | 0.47%   |
| SAELITE ES1AU11            | 1         | 0.47%   |
| Nuvision NES11             | 1         | 0.47%   |
| MSI MS-7C83                | 1         | 0.47%   |
| MSI MS-7A34                | 1         | 0.47%   |
| MSI MS-7817                | 1         | 0.47%   |
| MSI GE62                   | 1         | 0.47%   |
| MSI CR70                   | 1         | 0.47%   |
| Microsoft Surface          | 1         | 0.47%   |
| LG 17ZT90P-G.AX33U1        | 1         | 0.47%   |
| Lenovo Z50-75              | 1         | 0.47%   |
| Lenovo Yoga                | 1         | 0.47%   |
| Lenovo ThinkCentre         | 1         | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2013 | 22        | 10.23%  |
| 2011 | 21        | 9.77%   |
| 2019 | 19        | 8.84%   |
| 2021 | 18        | 8.37%   |
| 2014 | 18        | 8.37%   |
| 2017 | 16        | 7.44%   |
| 2012 | 16        | 7.44%   |
| 2016 | 13        | 6.05%   |
| 2020 | 12        | 5.58%   |
| 2018 | 11        | 5.12%   |
| 2015 | 8         | 3.72%   |
| 2008 | 8         | 3.72%   |
| 2007 | 8         | 3.72%   |
| 2010 | 7         | 3.26%   |
| 2022 | 5         | 2.33%   |
| 2009 | 5         | 2.33%   |
| 2023 | 4         | 1.86%   |
| 2006 | 2         | 0.93%   |
| 2005 | 2         | 0.93%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 149       | 69.3%   |
| Desktop     | 58        | 26.98%  |
| Convertible | 3         | 1.4%    |
| Tablet      | 2         | 0.93%   |
| Mini pc     | 2         | 0.93%   |
| All in one  | 1         | 0.47%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 208       | 96.74%  |
| Enabled  | 7         | 3.26%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 212       | 98.6%   |
| Yes  | 3         | 1.4%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 61        | 28.24%  |
| 4.01-8.0    | 56        | 25.93%  |
| 8.01-16.0   | 39        | 18.06%  |
| 16.01-24.0  | 31        | 14.35%  |
| 32.01-64.0  | 8         | 3.7%    |
| 24.01-32.0  | 6         | 2.78%   |
| 2.01-3.0    | 6         | 2.78%   |
| 1.01-2.0    | 6         | 2.78%   |
| 0.51-1.0    | 2         | 0.93%   |
| 64.01-256.0 | 1         | 0.46%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 81        | 34.03%  |
| 2.01-3.0  | 66        | 27.73%  |
| 3.01-4.0  | 47        | 19.75%  |
| 4.01-8.0  | 28        | 11.76%  |
| 0.51-1.0  | 10        | 4.2%    |
| 8.01-16.0 | 6         | 2.52%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 150       | 68.49%  |
| 2      | 53        | 24.2%   |
| 3      | 9         | 4.11%   |
| 4      | 6         | 2.74%   |
| 5      | 1         | 0.46%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 133       | 61.57%  |
| Yes       | 83        | 38.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 168       | 77.78%  |
| No        | 48        | 22.22%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 184       | 85.19%  |
| No        | 32        | 14.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 135       | 62.5%   |
| No        | 81        | 37.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country            | Computers | Percent |
|--------------------|-----------|---------|
| Dominican Republic | 215       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Computers | Percent |
|----------------------------|-----------|---------|
| Santo Domingo Este         | 108       | 46.75%  |
| Santo Domingo              | 36        | 15.58%  |
| Santiago de los Caballeros | 23        | 9.96%   |
| La Romana                  | 7         | 3.03%   |
| Concepción de la Vega     | 6         | 2.6%    |
| Santo Domingo Oeste        | 5         | 2.16%   |
| Cabarete                   | 4         | 1.73%   |
| Alejandro Bass             | 4         | 1.73%   |
| Santa Cruz de Barahona     | 3         | 1.3%    |
| San Pedro de Macorís      | 3         | 1.3%    |
| San Juan                   | 3         | 1.3%    |
| San Cristobal              | 3         | 1.3%    |
| Nagua                      | 3         | 1.3%    |
| Constanza                  | 3         | 1.3%    |
| Sosua, Cabarete            | 2         | 0.87%   |
| Puerto Plata               | 2         | 0.87%   |
| Nacional                   | 2         | 0.87%   |
| Bajos de Haina             | 2         | 0.87%   |
| San Isidro                 | 1         | 0.43%   |
| San Francisco de Macorís  | 1         | 0.43%   |
| Salcedo                    | 1         | 0.43%   |
| Sabaneta                   | 1         | 0.43%   |
| Punta Cana                 | 1         | 0.43%   |
| Monte Llano                | 1         | 0.43%   |
| Moca                       | 1         | 0.43%   |
| Los Hidalgos               | 1         | 0.43%   |
| Guaymate                   | 1         | 0.43%   |
| Cancino                    | 1         | 0.43%   |
| Boca Chica                 | 1         | 0.43%   |
| Baní                      | 1         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 53        | 72     | 18.53%  |
| Samsung Electronics         | 34        | 43     | 11.89%  |
| WDC                         | 25        | 34     | 8.74%   |
| Toshiba                     | 25        | 32     | 8.74%   |
| SanDisk                     | 19        | 25     | 6.64%   |
| Hitachi                     | 18        | 23     | 6.29%   |
| Kingston                    | 17        | 18     | 5.94%   |
| Unknown                     | 12        | 14     | 4.2%    |
| SK hynix                    | 7         | 9      | 2.45%   |
| China                       | 7         | 8      | 2.45%   |
| Intel                       | 6         | 8      | 2.1%    |
| Apple                       | 6         | 12     | 2.1%    |
| Crucial                     | 5         | 7      | 1.75%   |
| AirDisk                     | 4         | 4      | 1.4%    |
| Unknown                     | 4         | 4      | 1.4%    |
| SPCC                        | 3         | 3      | 1.05%   |
| Micron/Crucial Technology   | 3         | 3      | 1.05%   |
| FORESEE                     | 3         | 4      | 1.05%   |
| A-DATA Technology           | 3         | 3      | 1.05%   |
| Transcend                   | 2         | 2      | 0.7%    |
| PNY                         | 2         | 2      | 0.7%    |
| Micron Technology           | 2         | 2      | 0.7%    |
| KIOXIA                      | 2         | 3      | 0.7%    |
| Kingston Technology Company | 2         | 2      | 0.7%    |
| Indilinx                    | 2         | 2      | 0.7%    |
| HGST                        | 2         | 2      | 0.7%    |
| Wibtek                      | 1         | 1      | 0.35%   |
| UMIS                        | 1         | 1      | 0.35%   |
| Supersonic                  | 1         | 1      | 0.35%   |
| SABRENT                     | 1         | 1      | 0.35%   |
| Realtek Semiconductor       | 1         | 1      | 0.35%   |
| Phison Electronics          | 1         | 1      | 0.35%   |
| Patriot                     | 1         | 1      | 0.35%   |
| OCZ                         | 1         | 1      | 0.35%   |
| Netac                       | 1         | 1      | 0.35%   |
| MSI                         | 1         | 1      | 0.35%   |
| Maxtor                      | 1         | 1      | 0.35%   |
| MaiChai                     | 1         | 1      | 0.35%   |
| LITEONIT                    | 1         | 2      | 0.35%   |
| JMicron Technology          | 1         | 2      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 5         | 1.62%   |
| Seagate ST500DM002-1BD142 500GB                     | 5         | 1.62%   |
| Seagate ST500LM000-1EJ162 500GB                     | 4         | 1.29%   |
| Kingston SA400S37120G 120GB SSD                     | 4         | 1.29%   |
| AirDisk 128GB SSD                                   | 4         | 1.29%   |
| Unknown                                             | 4         | 1.29%   |
| Unknown MMC Card  16GB                              | 3         | 0.97%   |
| Toshiba MQ04ABF100 1TB                              | 3         | 0.97%   |
| Toshiba MQ01ACF050 500GB                            | 3         | 0.97%   |
| Toshiba MK3275GSX 320GB                             | 3         | 0.97%   |
| Seagate ST500LT012-1DG142 500GB                     | 3         | 0.97%   |
| Seagate ST500LM021-1KJ152 500GB                     | 3         | 0.97%   |
| Seagate ST1000LM035-1RK172 1TB                      | 3         | 0.97%   |
| Samsung SSD 860 EVO 500GB                           | 3         | 0.97%   |
| Samsung SSD 850 EVO 250GB                           | 3         | 0.97%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 512GB | 3         | 0.97%   |
| Hitachi HTS545050A7E380 500GB                       | 3         | 0.97%   |
| FORESEE 128GB SSD                                   | 3         | 0.97%   |
| Unknown MMC Card  64GB                              | 2         | 0.65%   |
| Unknown MMC Card  128GB                             | 2         | 0.65%   |
| Toshiba MQ01ABD050V 500GB                           | 2         | 0.65%   |
| Toshiba MK2556GSY 250GB                             | 2         | 0.65%   |
| Toshiba DT01ACA050 500GB                            | 2         | 0.65%   |
| Seagate ST9250315AS 250GB                           | 2         | 0.65%   |
| Seagate ST380815AS 80GB                             | 2         | 0.65%   |
| Seagate ST3500418AS 500GB                           | 2         | 0.65%   |
| Seagate ST3160815AS 160GB                           | 2         | 0.65%   |
| Seagate ST1000LM049-2GH172 1TB                      | 2         | 0.65%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 2         | 0.65%   |
| SanDisk SDSSDX120GG25 120GB                         | 2         | 0.65%   |
| SanDisk NVMe SSD Drive 256GB                        | 2         | 0.65%   |
| PNY CS900 240GB SSD                                 | 2         | 0.65%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB               | 2         | 0.65%   |
| Kingston SV300S37A120G 120GB SSD                    | 2         | 0.65%   |
| Kingston SA400S37480G 480GB SSD                     | 2         | 0.65%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 0.65%   |
| Kingston OM8PCP3512F-AB 512GB                       | 2         | 0.65%   |
| Intel HBRPEKNX0101AHO 16GB                          | 2         | 0.65%   |
| Intel HBRPEKNX0101AH 256GB                          | 2         | 0.65%   |
| Indilinx IND-S3N80P/128G 128GB                      | 2         | 0.65%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 52        | 70     | 41.94%  |
| Toshiba             | 23        | 29     | 18.55%  |
| WDC                 | 21        | 28     | 16.94%  |
| Hitachi             | 18        | 23     | 14.52%  |
| Samsung Electronics | 4         | 6      | 3.23%   |
| HGST                | 2         | 2      | 1.61%   |
| SABRENT             | 1         | 1      | 0.81%   |
| Maxtor              | 1         | 1      | 0.81%   |
| JMicron Technology  | 1         | 2      | 0.81%   |
| Apple               | 1         | 1      | 0.81%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21        | 23     | 21%     |
| Kingston            | 15        | 16     | 15%     |
| SanDisk             | 11        | 16     | 11%     |
| China               | 7         | 8      | 7%      |
| Crucial             | 5         | 7      | 5%      |
| Apple               | 4         | 5      | 4%      |
| AirDisk             | 4         | 4      | 4%      |
| WDC                 | 3         | 4      | 3%      |
| SPCC                | 3         | 3      | 3%      |
| FORESEE             | 3         | 4      | 3%      |
| A-DATA Technology   | 3         | 3      | 3%      |
| Transcend           | 2         | 2      | 2%      |
| SK hynix            | 2         | 2      | 2%      |
| PNY                 | 2         | 2      | 2%      |
| Intel               | 2         | 2      | 2%      |
| Wibtek              | 1         | 1      | 1%      |
| Supersonic          | 1         | 1      | 1%      |
| Seagate             | 1         | 2      | 1%      |
| Patriot             | 1         | 1      | 1%      |
| OCZ                 | 1         | 1      | 1%      |
| Netac               | 1         | 1      | 1%      |
| MSI                 | 1         | 1      | 1%      |
| MaiChai             | 1         | 1      | 1%      |
| LITEONIT            | 1         | 2      | 1%      |
| HS-SSD-C100         | 1         | 1      | 1%      |
| Hewlett-Packard     | 1         | 1      | 1%      |
| Eluktro             | 1         | 1      | 1%      |
| Unknown             | 1         | 1      | 1%      |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 110       | 163    | 41.83%  |
| SSD     | 91        | 116    | 34.6%   |
| NVMe    | 43        | 61     | 16.35%  |
| MMC     | 14        | 16     | 5.32%   |
| Unknown | 5         | 5      | 1.9%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 177       | 275    | 73.44%  |
| NVMe | 43        | 61     | 17.84%  |
| MMC  | 14        | 16     | 5.81%   |
| SAS  | 7         | 9      | 2.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 142       | 212    | 72.45%  |
| 0.51-1.0   | 40        | 51     | 20.41%  |
| 1.01-2.0   | 8         | 9      | 4.08%   |
| 3.01-4.0   | 3         | 4      | 1.53%   |
| 4.01-10.0  | 2         | 2      | 1.02%   |
| 2.01-3.0   | 1         | 1      | 0.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 71        | 30.74%  |
| 251-500        | 43        | 18.61%  |
| 501-1000       | 38        | 16.45%  |
| 51-100         | 23        | 9.96%   |
| 1-20           | 22        | 9.52%   |
| 1001-2000      | 11        | 4.76%   |
| 21-50          | 9         | 3.9%    |
| More than 3000 | 6         | 2.6%    |
| 2001-3000      | 4         | 1.73%   |
| Unknown        | 4         | 1.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 95        | 39.58%  |
| 21-50          | 42        | 17.5%   |
| 51-100         | 35        | 14.58%  |
| 101-250        | 26        | 10.83%  |
| 251-500        | 16        | 6.67%   |
| 501-1000       | 11        | 4.58%   |
| 1001-2000      | 6         | 2.5%    |
| 2001-3000      | 4         | 1.67%   |
| Unknown        | 4         | 1.67%   |
| More than 3000 | 1         | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500LM021-1KJ152 500GB   | 3         | 3      | 8.33%   |
| Toshiba MK3275GSX 320GB           | 2         | 2      | 5.56%   |
| Seagate ST500LM000-1EJ162 500GB   | 2         | 2      | 5.56%   |
| Seagate ST500DM002-1BD142 500GB   | 2         | 3      | 5.56%   |
| WDC WD6400AAKS-22A7B2 640GB       | 1         | 1      | 2.78%   |
| WDC WD5000BPVT-00HXZT1 500GB      | 1         | 1      | 2.78%   |
| WDC WD5000AZLX-60K2TA0 500GB      | 1         | 1      | 2.78%   |
| WDC WD2500BEKT-60A25T1 250GB      | 1         | 1      | 2.78%   |
| Toshiba MQ01ABD050V 500GB         | 1         | 1      | 2.78%   |
| Toshiba MK6465GSXN 640GB          | 1         | 1      | 2.78%   |
| Toshiba MK6034GSX 64GB            | 1         | 1      | 2.78%   |
| Toshiba MK3276GSX 320GB           | 1         | 1      | 2.78%   |
| Toshiba MK2556GSY 250GB           | 1         | 1      | 2.78%   |
| Toshiba MK1655GSX 160GB           | 1         | 1      | 2.78%   |
| Seagate ST9750420AS 752GB         | 1         | 1      | 2.78%   |
| Seagate ST500LT012-1DG142 500GB   | 1         | 1      | 2.78%   |
| Seagate ST3250318AS 250GB         | 1         | 1      | 2.78%   |
| Seagate ST2000LM007-1R8174 2TB    | 1         | 1      | 2.78%   |
| Samsung Electronics HM500LI 500GB | 1         | 1      | 2.78%   |
| Samsung Electronics HD154UI 1TB   | 1         | 1      | 2.78%   |
| Hitachi HTS727550A9E364 500GB     | 1         | 1      | 2.78%   |
| Hitachi HTS725032A9A364 320GB     | 1         | 1      | 2.78%   |
| Hitachi HTS722020K9SA00 200GB     | 1         | 1      | 2.78%   |
| Hitachi HTS547575A9E384 752GB     | 1         | 1      | 2.78%   |
| Hitachi HTS547564A9E384 640GB     | 1         | 1      | 2.78%   |
| Hitachi HTS545050A7E380 500GB     | 1         | 1      | 2.78%   |
| Hitachi HTS545016B9A300 160GB     | 1         | 1      | 2.78%   |
| Hitachi HTS542512K9SA00 120GB     | 1         | 1      | 2.78%   |
| Hitachi HDT721025SLA380 250GB     | 1         | 1      | 2.78%   |
| HGST HTS725050A7E630 500GB        | 1         | 1      | 2.78%   |
| Crucial CT240BX500SSD1 240GB      | 1         | 1      | 2.78%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 31.43%  |
| Toshiba             | 8         | 8      | 22.86%  |
| Hitachi             | 8         | 9      | 22.86%  |
| WDC                 | 4         | 4      | 11.43%  |
| Samsung Electronics | 2         | 2      | 5.71%   |
| HGST                | 1         | 1      | 2.86%   |
| Crucial             | 1         | 1      | 2.86%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 12     | 32.35%  |
| Toshiba             | 8         | 8      | 23.53%  |
| Hitachi             | 8         | 9      | 23.53%  |
| WDC                 | 4         | 4      | 11.76%  |
| Samsung Electronics | 2         | 2      | 5.88%   |
| HGST                | 1         | 1      | 2.94%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 30        | 36     | 96.77%  |
| SSD  | 1         | 1      | 3.23%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                         | Computers | Drives | Percent |
|-------------------------------|-----------|--------|---------|
| Hitachi HTS545050B9SA00 500GB | 1         | 1      | 50%     |
| Hitachi HDS721025CLA382 250GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 130       | 225    | 55.56%  |
| Works    | 72        | 97     | 30.77%  |
| Malfunc  | 30        | 37     | 12.82%  |
| Failed   | 2         | 2      | 0.85%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 145       | 60.92%  |
| AMD                              | 42        | 17.65%  |
| Samsung Electronics              | 14        | 5.88%   |
| SanDisk                          | 9         | 3.78%   |
| SK hynix                         | 4         | 1.68%   |
| Kingston Technology Company      | 4         | 1.68%   |
| Micron/Crucial Technology        | 3         | 1.26%   |
| Toshiba America Info Systems     | 2         | 0.84%   |
| Nvidia                           | 2         | 0.84%   |
| Micron Technology                | 2         | 0.84%   |
| Marvell Technology Group         | 2         | 0.84%   |
| KIOXIA                           | 2         | 0.84%   |
| VIA Technologies                 | 1         | 0.42%   |
| Union Memory (Shenzhen)          | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] | 1         | 0.42%   |
| Realtek Semiconductor            | 1         | 0.42%   |
| Phison Electronics               | 1         | 0.42%   |
| ASMedia Technology               | 1         | 0.42%   |
| Apple                            | 1         | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 31        | 11.36%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 19        | 6.96%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 14        | 5.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 13        | 4.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 10        | 3.66%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 10        | 3.66%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9         | 3.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6         | 2.2%    |
| Intel SATA Controller [RAID mode]                                                       | 6         | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 6         | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 1.83%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 1.47%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 1.47%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 4         | 1.47%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 4         | 1.47%   |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 1.47%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 3         | 1.1%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 3         | 1.1%    |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                              | 3         | 1.1%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 3         | 1.1%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 3         | 1.1%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 1.1%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 3         | 1.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3         | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 3         | 1.1%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 3         | 1.1%    |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                                   | 2         | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.73%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 2         | 0.73%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 2         | 0.73%   |
| Micron 2200S NVMe SSD [Cassandra]                                                       | 2         | 0.73%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                           | 2         | 0.73%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 2         | 0.73%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 0.73%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 2         | 0.73%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]                      | 2         | 0.73%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 2         | 0.73%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 2         | 0.73%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                            | 2         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 150       | 60%     |
| NVMe | 43        | 17.2%   |
| IDE  | 30        | 12%     |
| RAID | 27        | 10.8%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 168       | 78.14%  |
| AMD    | 47        | 21.86%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron N4120 CPU @ 1.10GHz             | 9         | 4.17%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 4         | 1.85%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 1.85%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 4         | 1.85%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.39%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 1.39%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 3         | 1.39%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 3         | 1.39%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 3         | 1.39%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.39%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.93%   |
| Intel Core i7-2640M CPU @ 2.80GHz             | 2         | 0.93%   |
| Intel Core i7-2620M CPU @ 2.70GHz             | 2         | 0.93%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 2         | 0.93%   |
| Intel Core i5-8365U CPU @ 1.60GHz             | 2         | 0.93%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 2         | 0.93%   |
| Intel Core i5-7300U CPU @ 2.60GHz             | 2         | 0.93%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 2         | 0.93%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 2         | 0.93%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 2         | 0.93%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 2         | 0.93%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 0.93%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 2         | 0.93%   |
| Intel Core i5-2415M CPU @ 2.30GHz             | 2         | 0.93%   |
| Intel Core i3-2375M CPU @ 1.50GHz             | 2         | 0.93%   |
| Intel Core 2 Duo CPU T8100 @ 2.10GHz          | 2         | 0.93%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.93%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.93%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 0.93%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 2         | 0.93%   |
| AMD FX-8320 Eight-Core Processor              | 2         | 0.93%   |
| AMD FX-4100 Quad-Core Processor               | 2         | 0.93%   |
| AMD A8-7410 APU with AMD Radeon R5 Graphics   | 2         | 0.93%   |
| AMD A4-6210 APU with AMD Radeon R3 Graphics   | 2         | 0.93%   |
| Intel Xeon E-2224G CPU @ 3.50GHz              | 1         | 0.46%   |
| Intel Xeon CPU X5675 @ 3.07GHz                | 1         | 0.46%   |
| Intel Xeon CPU E5-2680 v4 @ 2.40GHz           | 1         | 0.46%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.46%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 1         | 0.46%   |
| Intel Pentium Dual CPU T2390 @ 1.86GHz        | 1         | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 58        | 26.85%  |
| Intel Core i7           | 32        | 14.81%  |
| Intel Celeron           | 26        | 12.04%  |
| Intel Core i3           | 17        | 7.87%   |
| AMD Ryzen 5             | 12        | 5.56%   |
| Other                   | 7         | 3.24%   |
| Intel Core 2 Duo        | 7         | 3.24%   |
| AMD Ryzen 7             | 7         | 3.24%   |
| AMD FX                  | 5         | 2.31%   |
| Intel Pentium           | 4         | 1.85%   |
| Intel Atom              | 4         | 1.85%   |
| AMD A8                  | 4         | 1.85%   |
| Intel Xeon              | 3         | 1.39%   |
| AMD A6                  | 3         | 1.39%   |
| AMD A10                 | 3         | 1.39%   |
| Intel Pentium Dual-Core | 2         | 0.93%   |
| Intel Pentium 4         | 2         | 0.93%   |
| Intel Core 2            | 2         | 0.93%   |
| AMD Sempron             | 2         | 0.93%   |
| AMD Ryzen 3             | 2         | 0.93%   |
| AMD A4                  | 2         | 0.93%   |
| Intel Pentium Dual      | 1         | 0.46%   |
| Intel Pentium D         | 1         | 0.46%   |
| Intel Genuine           | 1         | 0.46%   |
| Intel Core i9           | 1         | 0.46%   |
| Intel Core 2 Quad       | 1         | 0.46%   |
| AMD Quad-Core           | 1         | 0.46%   |
| AMD PRO A10             | 1         | 0.46%   |
| AMD Phenom II X4        | 1         | 0.46%   |
| AMD Mobile Sempron      | 1         | 0.46%   |
| AMD GX                  | 1         | 0.46%   |
| AMD E2                  | 1         | 0.46%   |
| AMD A12                 | 1         | 0.46%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 107       | 49.54%  |
| 4      | 81        | 37.5%   |
| 6      | 10        | 4.63%   |
| 8      | 7         | 3.24%   |
| 1      | 7         | 3.24%   |
| 14     | 1         | 0.46%   |
| 12     | 1         | 0.46%   |
| 10     | 1         | 0.46%   |
| 3      | 1         | 0.46%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 214       | 99.53%  |
| 2      | 1         | 0.47%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 134       | 62.33%  |
| 1      | 81        | 37.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 213       | 98.61%  |
| 64-bit         | 1         | 0.46%   |
| 32-bit         | 1         | 0.46%   |
| Unknown        | 1         | 0.46%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 95        | 42.79%  |
| 0x206a7    | 15        | 6.76%   |
| 0x306a9    | 11        | 4.95%   |
| 0x306c3    | 8         | 3.6%    |
| 0x1067a    | 7         | 3.15%   |
| 0x806e9    | 6         | 2.7%    |
| 0x506e3    | 6         | 2.7%    |
| 0x40651    | 5         | 2.25%   |
| 0x806ea    | 4         | 1.8%    |
| 0x706a1    | 4         | 1.8%    |
| 0x706a8    | 3         | 1.35%   |
| 0x30678    | 3         | 1.35%   |
| 0x08108109 | 3         | 1.35%   |
| 0x0800820d | 3         | 1.35%   |
| 0x07030105 | 3         | 1.35%   |
| 0x06000852 | 3         | 1.35%   |
| 0x906ea    | 2         | 0.9%    |
| 0x806ec    | 2         | 0.9%    |
| 0x6fb      | 2         | 0.9%    |
| 0x6f6      | 2         | 0.9%    |
| 0x20655    | 2         | 0.9%    |
| 0x20652    | 2         | 0.9%    |
| 0x10676    | 2         | 0.9%    |
| 0x08600103 | 2         | 0.9%    |
| 0x0600611a | 2         | 0.9%    |
| 0x06003106 | 2         | 0.9%    |
| 0xf65      | 1         | 0.45%   |
| 0xf49      | 1         | 0.45%   |
| 0x906e9    | 1         | 0.45%   |
| 0x806c1    | 1         | 0.45%   |
| 0x706e5    | 1         | 0.45%   |
| 0x6fd      | 1         | 0.45%   |
| 0x506c9    | 1         | 0.45%   |
| 0x406c3    | 1         | 0.45%   |
| 0x30679    | 1         | 0.45%   |
| 0x106ca    | 1         | 0.45%   |
| 0x106c2    | 1         | 0.45%   |
| 0x10661    | 1         | 0.45%   |
| 0x08608103 | 1         | 0.45%   |
| 0x08608102 | 1         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KabyLake        | 27        | 12.56%  |
| SandyBridge     | 22        | 10.23%  |
| Haswell         | 20        | 9.3%    |
| IvyBridge       | 19        | 8.84%   |
| Goldmont plus   | 15        | 6.98%   |
| Zen+            | 10        | 4.65%   |
| Silvermont      | 9         | 4.19%   |
| Penryn          | 9         | 4.19%   |
| Skylake         | 8         | 3.72%   |
| Westmere        | 7         | 3.26%   |
| Broadwell       | 7         | 3.26%   |
| Puma            | 6         | 2.79%   |
| Core            | 6         | 2.79%   |
| TigerLake       | 5         | 2.33%   |
| Piledriver      | 5         | 2.33%   |
| Unknown         | 5         | 2.33%   |
| Zen 3           | 4         | 1.86%   |
| IceLake         | 4         | 1.86%   |
| Excavator       | 4         | 1.86%   |
| Zen 2           | 3         | 1.4%    |
| NetBurst        | 3         | 1.4%    |
| Steamroller     | 2         | 0.93%   |
| K8 Hammer       | 2         | 0.93%   |
| Jaguar          | 2         | 0.93%   |
| CometLake       | 2         | 0.93%   |
| Bulldozer       | 2         | 0.93%   |
| Bonnell         | 2         | 0.93%   |
| Zen             | 1         | 0.47%   |
| K8 & K10 hybrid | 1         | 0.47%   |
| K10 Llano       | 1         | 0.47%   |
| K10             | 1         | 0.47%   |
| Goldmont        | 1         | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 149       | 62.08%  |
| AMD                              | 51        | 21.25%  |
| Nvidia                           | 38        | 15.83%  |
| VIA Technologies                 | 1         | 0.42%   |
| Silicon Integrated Systems [SiS] | 1         | 0.42%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 7.72%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 15        | 6.1%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 12        | 4.88%   |
| Intel UHD Graphics 620                                                                   | 8         | 3.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 7         | 2.85%   |
| Intel HD Graphics 620                                                                    | 7         | 2.85%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 7         | 2.85%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 7         | 2.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6         | 2.44%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.03%   |
| Intel HD Graphics 530                                                                    | 5         | 2.03%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 2.03%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 4         | 1.63%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 1.63%   |
| Intel Iris Plus Graphics G7                                                              | 4         | 1.63%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.63%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 1.22%   |
| Intel HD Graphics 6000                                                                   | 3         | 1.22%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3         | 1.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3         | 1.22%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 1.22%   |
| AMD RS780L [Radeon 3000]                                                                 | 3         | 1.22%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 1.22%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 1.22%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.81%   |
| Nvidia GF119 [GeForce GT 520]                                                            | 2         | 0.81%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2         | 0.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 2         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.81%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 2         | 0.81%   |
| Intel HD Graphics 5500                                                                   | 2         | 0.81%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.81%   |
| AMD Temash [Radeon HD 8250/8280G]                                                        | 2         | 0.81%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 2         | 0.81%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.81%   |
| AMD Mullins [Radeon R3 Graphics]                                                         | 2         | 0.81%   |
| AMD Lucienne                                                                             | 2         | 0.81%   |
| VIA Technologies K8M800/K8N800/K8N800A [S3 UniChrome Pro]                                | 1         | 0.41%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 1         | 0.41%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 128       | 59.53%  |
| 1 x AMD        | 39        | 18.14%  |
| 1 x Nvidia     | 20        | 9.3%    |
| Intel + Nvidia | 14        | 6.51%   |
| Intel + AMD    | 5         | 2.33%   |
| AMD + Nvidia   | 4         | 1.86%   |
| 2 x AMD        | 3         | 1.4%    |
| 1 x VIA        | 1         | 0.47%   |
| 1 x SiS        | 1         | 0.47%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 190       | 87.16%  |
| Proprietary | 19        | 8.72%   |
| Unknown     | 9         | 4.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 158       | 71.49%  |
| 1.01-2.0   | 17        | 7.69%   |
| 0.01-0.5   | 17        | 7.69%   |
| 0.51-1.0   | 12        | 5.43%   |
| 7.01-8.0   | 7         | 3.17%   |
| 3.01-4.0   | 6         | 2.71%   |
| 2.01-3.0   | 2         | 0.9%    |
| 5.01-6.0   | 1         | 0.45%   |
| 8.01-16.0  | 1         | 0.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 37        | 16.82%  |
| LG Display              | 23        | 10.45%  |
| BOE                     | 23        | 10.45%  |
| Dell                    | 21        | 9.55%   |
| Chimei Innolux          | 20        | 9.09%   |
| Samsung Electronics     | 17        | 7.73%   |
| Hewlett-Packard         | 10        | 4.55%   |
| AOC                     | 10        | 4.55%   |
| Apple                   | 9         | 4.09%   |
| Goldstar                | 6         | 2.73%   |
| Chi Mei Optoelectronics | 5         | 2.27%   |
| InfoVision              | 4         | 1.82%   |
| Sony                    | 3         | 1.36%   |
| Acer                    | 3         | 1.36%   |
| Unknown (XXX)           | 2         | 0.91%   |
| Philips                 | 2         | 0.91%   |
| PANDA                   | 2         | 0.91%   |
| Lenovo                  | 2         | 0.91%   |
| KDC                     | 2         | 0.91%   |
| ZTR                     | 1         | 0.45%   |
| Westinghouse            | 1         | 0.45%   |
| Vizio                   | 1         | 0.45%   |
| Viotek                  | 1         | 0.45%   |
| ViewSonic               | 1         | 0.45%   |
| Unknown                 | 1         | 0.45%   |
| STA                     | 1         | 0.45%   |
| Sharp                   | 1         | 0.45%   |
| Panasonic               | 1         | 0.45%   |
| NEC Computers           | 1         | 0.45%   |
| MSI                     | 1         | 0.45%   |
| LG Philips              | 1         | 0.45%   |
| LG Electronics          | 1         | 0.45%   |
| KTC                     | 1         | 0.45%   |
| InnoLux Display         | 1         | 0.45%   |
| CSO                     | 1         | 0.45%   |
| CHR                     | 1         | 0.45%   |
| BenQ                    | 1         | 0.45%   |
| Ancor Communications    | 1         | 0.45%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch    | 4         | 1.79%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch             | 4         | 1.79%   |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch           | 4         | 1.79%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 3         | 1.35%   |
| Sony TV SNYDD02 1920x1080 708x398mm 32.0-inch                           | 2         | 0.9%    |
| LG Display LCD Monitor LGD02EB 1366x768 309x174mm 14.0-inch             | 2         | 0.9%    |
| KDC LCD Monitor KDC0109 1366x768 256x144mm 11.6-inch                    | 2         | 0.9%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                  | 2         | 0.9%    |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                         | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 2         | 0.9%    |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch          | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch          | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch           | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO11EC 1366x768 344x193mm 15.5-inch           | 2         | 0.9%    |
| AU Optronics LCD Monitor AUO105C 1366x768 256x144mm 11.6-inch           | 2         | 0.9%    |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                    | 2         | 0.9%    |
| AOC 2269WM AOC2269 1920x1080 477x268mm 21.5-inch                        | 2         | 0.9%    |
| ZTR LCD Monitor ZTR0001 1920x1080 344x194mm 15.5-inch                   | 1         | 0.45%   |
| Westinghouse EUM24F1G1 WDT1E64 1920x1080 530x300mm 24.0-inch            | 1         | 0.45%   |
| Vizio D32x-D1 VIZ1005 1920x1080 698x392mm 31.5-inch                     | 1         | 0.45%   |
| Viotek GN32DA VTK3200 2560x1440 698x393mm 31.5-inch                     | 1         | 0.45%   |
| ViewSonic VX2757 VSCF931 1920x1080 598x336mm 27.0-inch                  | 1         | 0.45%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch               | 1         | 0.45%   |
| Unknown (XXX) MS82P XXX001A 1360x768 330x210mm 15.4-inch                | 1         | 0.45%   |
| Unknown (XXX) DTV XXX0030 1600x1200 708x398mm 32.0-inch                 | 1         | 0.45%   |
| STA LCD Monitor STA0001 1366x768 256x144mm 11.6-inch                    | 1         | 0.45%   |
| Sony TV SNY1703 1360x768                                                | 1         | 0.45%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 211x141mm 10.0-inch                 | 1         | 0.45%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch       | 1         | 0.45%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch       | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch    | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SEC3451 1366x768 344x194mm 15.5-inch    | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC5544 1920x1080 344x194mm 15.5-inch   | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC4852 1366x768 344x194mm 15.5-inch    | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC4642 1366x768 309x174mm 14.0-inch    | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch    | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SDC354A 1366x768 344x194mm 15.5-inch    | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SAM0FEE 3840x2160 1872x1053mm 84.6-inch | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SAM0B32 1366x768 607x345mm 27.5-inch    | 1         | 0.45%   |
| Samsung Electronics LCD Monitor SAM0664 1360x768 410x256mm 19.0-inch    | 1         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 76        | 35.85%  |
| 1920x1080 (FHD)    | 68        | 32.08%  |
| 1600x900 (HD+)     | 10        | 4.72%   |
| 1280x1024 (SXGA)   | 9         | 4.25%   |
| 3840x2160 (4K)     | 8         | 3.77%   |
| 1680x1050 (WSXGA+) | 8         | 3.77%   |
| 1280x800 (WXGA)    | 8         | 3.77%   |
| 1440x900 (WXGA+)   | 6         | 2.83%   |
| 1360x768           | 4         | 1.89%   |
| 2560x1440 (QHD)    | 3         | 1.42%   |
| 2560x1600          | 2         | 0.94%   |
| 1024x768 (XGA)     | 2         | 0.94%   |
| 3840x1100          | 1         | 0.47%   |
| 3440x1440          | 1         | 0.47%   |
| 2288x1287          | 1         | 0.47%   |
| 1984x768           | 1         | 0.47%   |
| 1800x1200          | 1         | 0.47%   |
| 1280x768           | 1         | 0.47%   |
| 1024x600           | 1         | 0.47%   |
| Unknown            | 1         | 0.47%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 73        | 33.18%  |
| 13      | 30        | 13.64%  |
| 14      | 17        | 7.73%   |
| 11      | 14        | 6.36%   |
| 17      | 12        | 5.45%   |
| 22      | 9         | 4.09%   |
| 21      | 9         | 4.09%   |
| 19      | 9         | 4.09%   |
| 27      | 7         | 3.18%   |
| 24      | 7         | 3.18%   |
| 31      | 5         | 2.27%   |
| Unknown | 5         | 2.27%   |
| 18      | 4         | 1.82%   |
| 23      | 3         | 1.36%   |
| 50      | 2         | 0.91%   |
| 34      | 2         | 0.91%   |
| 32      | 2         | 0.91%   |
| 20      | 2         | 0.91%   |
| 10      | 2         | 0.91%   |
| 142     | 1         | 0.45%   |
| 84      | 1         | 0.45%   |
| 72      | 1         | 0.45%   |
| 41      | 1         | 0.45%   |
| 40      | 1         | 0.45%   |
| 12      | 1         | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 103       | 47.69%  |
| 201-300        | 34        | 15.74%  |
| 401-500        | 29        | 13.43%  |
| 501-600        | 16        | 7.41%   |
| 351-400        | 13        | 6.02%   |
| 601-700        | 5         | 2.31%   |
| Unknown        | 5         | 2.31%   |
| 701-800        | 4         | 1.85%   |
| 1501-2000      | 2         | 0.93%   |
| 1001-1500      | 2         | 0.93%   |
| More than 2000 | 1         | 0.46%   |
| 801-900        | 1         | 0.46%   |
| 901-1000       | 1         | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 157       | 77.72%  |
| 16/10   | 27        | 13.37%  |
| 5/4     | 9         | 4.46%   |
| Unknown | 4         | 1.98%   |
| 4/3     | 1         | 0.5%    |
| 3/2     | 1         | 0.5%    |
| 3.40    | 1         | 0.5%    |
| 21/9    | 1         | 0.5%    |
| 1.00    | 1         | 0.5%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 72        | 32.88%  |
| 81-90          | 36        | 16.44%  |
| 201-250        | 20        | 9.13%   |
| 151-200        | 17        | 7.76%   |
| 51-60          | 15        | 6.85%   |
| 71-80          | 10        | 4.57%   |
| 141-150        | 10        | 4.57%   |
| 351-500        | 8         | 3.65%   |
| 301-350        | 7         | 3.2%    |
| 121-130        | 6         | 2.74%   |
| More than 1000 | 5         | 2.28%   |
| Unknown        | 5         | 2.28%   |
| 501-1000       | 3         | 1.37%   |
| 41-50          | 2         | 0.91%   |
| 61-70          | 1         | 0.46%   |
| 251-300        | 1         | 0.46%   |
| 91-100         | 1         | 0.46%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 75        | 35.05%  |
| 121-160       | 59        | 27.57%  |
| 51-100        | 59        | 27.57%  |
| 1-50          | 7         | 3.27%   |
| 161-240       | 7         | 3.27%   |
| Unknown       | 5         | 2.34%   |
| More than 240 | 2         | 0.93%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 181       | 83.03%  |
| 2     | 27        | 12.39%  |
| 0     | 9         | 4.13%   |
| 3     | 1         | 0.46%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 108       | 33.03%  |
| Intel                           | 99        | 30.28%  |
| Qualcomm Atheros                | 41        | 12.54%  |
| Broadcom                        | 27        | 8.26%   |
| Ralink Technology               | 12        | 3.67%   |
| Broadcom Limited                | 8         | 2.45%   |
| Qualcomm Atheros Communications | 5         | 1.53%   |
| Linksys                         | 3         | 0.92%   |
| Nvidia                          | 2         | 0.61%   |
| MediaTek                        | 2         | 0.61%   |
| Marvell Technology Group        | 2         | 0.61%   |
| Lenovo                          | 2         | 0.61%   |
| Dell                            | 2         | 0.61%   |
| ZTopInc                         | 1         | 0.31%   |
| Xiaomi                          | 1         | 0.31%   |
| VIA Technologies                | 1         | 0.31%   |
| Tul Corporation / PowerColor    | 1         | 0.31%   |
| TP-Link                         | 1         | 0.31%   |
| Ralink                          | 1         | 0.31%   |
| JCM                             | 1         | 0.31%   |
| Huawei Technologies             | 1         | 0.31%   |
| HTC (High Tech Computer)        | 1         | 0.31%   |
| Google                          | 1         | 0.31%   |
| Edimax Technology               | 1         | 0.31%   |
| DisplayLink                     | 1         | 0.31%   |
| ASIX Electronics                | 1         | 0.31%   |
| AMD                             | 1         | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 57        | 14.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 21        | 5.48%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 17        | 4.44%   |
| Ralink MT7601U Wireless Adapter                                        | 10        | 2.61%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 9         | 2.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 8         | 2.09%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 8         | 2.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 8         | 2.09%   |
| Intel Wireless 7260                                                    | 7         | 1.83%   |
| Intel Ethernet Connection I217-LM                                      | 7         | 1.83%   |
| Intel Wi-Fi 6 AX200                                                    | 6         | 1.57%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 5         | 1.31%   |
| Qualcomm Atheros AR9271 802.11n                                        | 5         | 1.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5         | 1.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 5         | 1.31%   |
| Intel Wireless 7265                                                    | 5         | 1.31%   |
| Intel Wireless 3165                                                    | 5         | 1.31%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 5         | 1.31%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 4         | 1.04%   |
| Intel Wi-Fi 6 AX201                                                    | 4         | 1.04%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 4         | 1.04%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 1.04%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter   | 4         | 1.04%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 4         | 1.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3         | 0.78%   |
| Realtek 802.11n WLAN Adapter                                           | 3         | 0.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 3         | 0.78%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 0.78%   |
| Intel Wireless 8265 / 8275                                             | 3         | 0.78%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 0.78%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 0.78%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 0.78%   |
| Intel Centrino Ultimate-N 6300                                         | 3         | 0.78%   |
| Intel Centrino Advanced-N 6235                                         | 3         | 0.78%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 3         | 0.78%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 0.78%   |
| Broadcom BCM4331 802.11a/b/g/n                                         | 3         | 0.78%   |
| Broadcom BCM43142 802.11b/g/n                                          | 3         | 0.78%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 2         | 0.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 2         | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 75        | 37.13%  |
| Realtek Semiconductor           | 41        | 20.3%   |
| Qualcomm Atheros                | 34        | 16.83%  |
| Broadcom                        | 19        | 9.41%   |
| Ralink Technology               | 12        | 5.94%   |
| Qualcomm Atheros Communications | 5         | 2.48%   |
| Broadcom Limited                | 5         | 2.48%   |
| Linksys                         | 3         | 1.49%   |
| MediaTek                        | 2         | 0.99%   |
| Dell                            | 2         | 0.99%   |
| ZTopInc                         | 1         | 0.5%    |
| TP-Link                         | 1         | 0.5%    |
| Ralink                          | 1         | 0.5%    |
| Edimax Technology               | 1         | 0.5%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Ralink MT7601U Wireless Adapter                                         | 10        | 4.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 9         | 4.43%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 8         | 3.94%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 3.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 3.94%   |
| Intel Wireless 7260                                                     | 7         | 3.45%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 2.96%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 2.46%   |
| Qualcomm Atheros AR9271 802.11n                                         | 5         | 2.46%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 2.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5         | 2.46%   |
| Intel Wireless 7265                                                     | 5         | 2.46%   |
| Intel Wireless 3165                                                     | 5         | 2.46%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 2.46%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.97%   |
| Intel Wi-Fi 6 AX201                                                     | 4         | 1.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 4         | 1.97%   |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter    | 4         | 1.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.48%   |
| Realtek 802.11n WLAN Adapter                                            | 3         | 1.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.48%   |
| Intel Wireless 8265 / 8275                                              | 3         | 1.48%   |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.48%   |
| Intel Centrino Advanced-N 6235                                          | 3         | 1.48%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 1.48%   |
| Broadcom BCM43142 802.11b/g/n                                           | 3         | 1.48%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 2         | 0.99%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2         | 0.99%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 2         | 0.99%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 2         | 0.99%   |
| Ralink RT5370 Wireless Adapter                                          | 2         | 0.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.99%   |
| Linksys AE2500 802.11abgn Wireless Adapter [Broadcom BCM43236]          | 2         | 0.99%   |
| Intel Wireless 8260                                                     | 2         | 0.99%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 2         | 0.99%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 2         | 0.99%   |
| Intel Gemini Lake PCH CNVi WiFi                                         | 2         | 0.99%   |
| Intel Centrino Wireless-N 2230                                          | 2         | 0.99%   |
| Intel Centrino Advanced-N 6200                                          | 2         | 0.99%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 85        | 48.02%  |
| Intel                    | 54        | 30.51%  |
| Broadcom                 | 12        | 6.78%   |
| Qualcomm Atheros         | 10        | 5.65%   |
| Broadcom Limited         | 3         | 1.69%   |
| Nvidia                   | 2         | 1.13%   |
| Marvell Technology Group | 2         | 1.13%   |
| Lenovo                   | 2         | 1.13%   |
| Xiaomi                   | 1         | 0.56%   |
| VIA Technologies         | 1         | 0.56%   |
| Huawei Technologies      | 1         | 0.56%   |
| HTC (High Tech Computer) | 1         | 0.56%   |
| Google                   | 1         | 0.56%   |
| DisplayLink              | 1         | 0.56%   |
| ASIX Electronics         | 1         | 0.56%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 57        | 32.2%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 21        | 11.86%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 17        | 9.6%    |
| Intel Ethernet Connection I217-LM                                      | 7         | 3.95%   |
| Intel 82577LM Gigabit Network Connection                               | 4         | 2.26%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 1.69%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 1.69%   |
| Intel Ethernet Connection (6) I219-LM                                  | 3         | 1.69%   |
| Intel Ethernet Connection (4) I219-LM                                  | 3         | 1.69%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 3         | 1.69%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 1.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 2         | 1.13%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 1.13%   |
| Lenovo Thinkpad LAN                                                    | 2         | 1.13%   |
| Intel Ethernet Connection (2) I219-V                                   | 2         | 1.13%   |
| Intel Ethernet Connection (2) I218-V                                   | 2         | 1.13%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 2         | 1.13%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 1         | 0.56%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.56%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 1         | 0.56%   |
| Realtek RTL8125 2.5GbE Controller                                      | 1         | 0.56%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1         | 0.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 1         | 0.56%   |
| Realtek Killer E2600 GbE Controller                                    | 1         | 0.56%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.56%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 1         | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.56%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 1         | 0.56%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.56%   |
| Nvidia MCP77 Ethernet                                                  | 1         | 0.56%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 1         | 0.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 1         | 0.56%   |
| Intel I211 Gigabit Network Connection                                  | 1         | 0.56%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.56%   |
| Intel Ethernet Connection (7) I219-LM                                  | 1         | 0.56%   |
| Intel Ethernet Connection (6) I219-V                                   | 1         | 0.56%   |
| Intel Ethernet Connection (4) I219-V                                   | 1         | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 0.56%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 0.56%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 184       | 51.98%  |
| Ethernet | 167       | 47.18%  |
| Modem    | 2         | 0.56%   |
| Unknown  | 1         | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 147       | 67.12%  |
| Ethernet | 72        | 32.88%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 121       | 56.28%  |
| 1     | 86        | 40%     |
| 0     | 8         | 3.72%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 189       | 85.52%  |
| Yes  | 32        | 14.48%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 55        | 40.74%  |
| Qualcomm Atheros Communications | 18        | 13.33%  |
| IMC Networks                    | 14        | 10.37%  |
| Realtek Semiconductor           | 11        | 8.15%   |
| Cambridge Silicon Radio         | 9         | 6.67%   |
| Apple                           | 9         | 6.67%   |
| Dell                            | 7         | 5.19%   |
| Broadcom                        | 5         | 3.7%    |
| Lite-On Technology              | 3         | 2.22%   |
| MediaTek                        | 1         | 0.74%   |
| Hewlett-Packard                 | 1         | 0.74%   |
| Dynex                           | 1         | 0.74%   |
| ASUSTek Computer                | 1         | 0.74%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                       | 23        | 17.04%  |
| Qualcomm Atheros  Bluetooth Device                       | 10        | 7.41%   |
| IMC Networks Bluetooth Radio                             | 9         | 6.67%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 9         | 6.67%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 8         | 5.93%   |
| Intel AX201 Bluetooth                                    | 7         | 5.19%   |
| Realtek  Bluetooth 4.2 Adapter                           | 6         | 4.44%   |
| Intel AX200 Bluetooth                                    | 6         | 4.44%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 5         | 3.7%    |
| Apple Bluetooth Host Controller                          | 5         | 3.7%    |
| Intel Wireless-AC 3168 Bluetooth                         | 4         | 2.96%   |
| Realtek Bluetooth Radio                                  | 3         | 2.22%   |
| Qualcomm Atheros AR9462 Bluetooth                        | 3         | 2.22%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                    | 3         | 2.22%   |
| Dell BCM20702A0 Bluetooth Module                         | 3         | 2.22%   |
| Broadcom BCM43142 Bluetooth 4.0                          | 3         | 2.22%   |
| Apple Bluetooth USB Host Controller                      | 3         | 2.22%   |
| IMC Networks BCM20702A0                                  | 2         | 1.48%   |
| Realtek RTL8723B Bluetooth                               | 1         | 0.74%   |
| Realtek 802.11ac WLAN Adapter                            | 1         | 0.74%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                   | 1         | 0.74%   |
| Qualcomm Atheros Bluetooth USB Host Controller           | 1         | 0.74%   |
| MediaTek Wireless_Device                                 | 1         | 0.74%   |
| Lite-On Wireless_Device                                  | 1         | 0.74%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth               | 1         | 0.74%   |
| Lite-On Atheros AR3012 Bluetooth                         | 1         | 0.74%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 1         | 0.74%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter         | 1         | 0.74%   |
| IMC Networks Bluetooth Device                            | 1         | 0.74%   |
| IMC Networks Bluetooth                                   | 1         | 0.74%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter        | 1         | 0.74%   |
| HP Broadcom 2070 Bluetooth Combo                         | 1         | 0.74%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1         | 0.74%   |
| Dell Wireless 360 Bluetooth                              | 1         | 0.74%   |
| Dell Wireless 355 Bluetooth                              | 1         | 0.74%   |
| Dell Wireless 350 Bluetooth                              | 1         | 0.74%   |
| Dell DW375 Bluetooth Module                              | 1         | 0.74%   |
| Broadcom HP Portable SoftSailing                         | 1         | 0.74%   |
| Broadcom BCM2045B (BDC-2.1)                              | 1         | 0.74%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1         | 0.74%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 162       | 62.55%  |
| AMD                              | 51        | 19.69%  |
| Nvidia                           | 28        | 10.81%  |
| Logitech                         | 4         | 1.54%   |
| Creative Labs                    | 2         | 0.77%   |
| C-Media Electronics              | 2         | 0.77%   |
| VIA Technologies                 | 1         | 0.39%   |
| Texas Instruments                | 1         | 0.39%   |
| Sony                             | 1         | 0.39%   |
| Silicon Integrated Systems [SiS] | 1         | 0.39%   |
| M-Audio                          | 1         | 0.39%   |
| JMTek                            | 1         | 0.39%   |
| Generalplus Technology           | 1         | 0.39%   |
| fifine Microphones               | 1         | 0.39%   |
| Blue Microphones                 | 1         | 0.39%   |
| BigBen Interactive               | 1         | 0.39%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 23        | 7.19%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 5.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 18        | 5.63%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 16        | 5%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 15        | 4.69%   |
| AMD FCH Azalia Controller                                                                         | 13        | 4.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 12        | 3.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 12        | 3.75%   |
| AMD Kabini HDMI/DP Audio                                                                          | 11        | 3.44%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 7         | 2.19%   |
| Intel 8 Series HD Audio Controller                                                                | 7         | 2.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 7         | 2.19%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 6         | 1.88%   |
| Intel Broadwell-U Audio Controller                                                                | 6         | 1.88%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 1.88%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 1.88%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 6         | 1.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 5         | 1.56%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 5         | 1.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 5         | 1.56%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 5         | 1.56%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 4         | 1.25%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.25%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 4         | 1.25%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.94%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.94%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 3         | 0.94%   |
| Intel Cannon Lake PCH cAVS                                                                        | 3         | 0.94%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 0.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 0.94%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 2         | 0.63%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 2         | 0.63%   |
| Nvidia High Definition Audio Controller                                                           | 2         | 0.63%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 2         | 0.63%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 2         | 0.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 2         | 0.63%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 2         | 0.63%   |
| AMD Trinity HDMI Audio Controller                                                                 | 2         | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| SK hynix            | 35        | 24.31%  |
| Samsung Electronics | 33        | 22.92%  |
| Micron Technology   | 16        | 11.11%  |
| Unknown             | 8         | 5.56%   |
| Crucial             | 8         | 5.56%   |
| Unknown (ABCD)      | 7         | 4.86%   |
| Kingston            | 7         | 4.86%   |
| Ramaxel Technology  | 5         | 3.47%   |
| Nanya Technology    | 5         | 3.47%   |
| G.Skill             | 3         | 2.08%   |
| Corsair             | 3         | 2.08%   |
| Unknown             | 3         | 2.08%   |
| A-DATA Technology   | 2         | 1.39%   |
| V-Color             | 1         | 0.69%   |
| Timetec             | 1         | 0.69%   |
| Sesame              | 1         | 0.69%   |
| Qimonda             | 1         | 0.69%   |
| PNY                 | 1         | 0.69%   |
| Patriot             | 1         | 0.69%   |
| Heoriady            | 1         | 0.69%   |
| Elpida              | 1         | 0.69%   |
| Avant               | 1         | 0.69%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 7         | 4.61%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 1.97%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 3         | 1.97%   |
| Unknown                                                          | 3         | 1.97%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 2         | 1.32%   |
| SK hynix RAM HMT351U6BFR8C-H9 4GB DIMM DDR3 1333MT/s             | 2         | 1.32%   |
| SK hynix RAM HMT351S6EFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 1.32%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 1.32%   |
| SK hynix RAM HMT325U6CFR8C-PB 2GB DIMM DDR3 1600MT/s             | 2         | 1.32%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 2         | 1.32%   |
| Samsung RAM M471B5273EB0-CK0 4096MB SODIMM DDR3 4199MT/s         | 2         | 1.32%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.32%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.32%   |
| Samsung RAM M471A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 2         | 1.32%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s              | 2         | 1.32%   |
| Micron RAM 8ATF1G64HZ-2G6H1 8GB SODIMM DDR4 2667MT/s             | 2         | 1.32%   |
| A-DATA RAM AD73I1B1674EU 2GB SODIMM DDR3 1334MT/s                | 2         | 1.32%   |
| V-Color RAM TL48G32S8KGRGB16 8192MB DIMM DDR4 3200MT/s           | 1         | 0.66%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.66%   |
| Unknown RAM Module 8GB DIMM DDR4 2133MT/s                        | 1         | 0.66%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                          | 1         | 0.66%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.66%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.66%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.66%   |
| Unknown RAM Module 2GB SODIMM DRAM 667MT/s                       | 1         | 0.66%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.66%   |
| Timetec RAM U8G-1333 8GB DIMM DDR3 1333MT/s                      | 1         | 0.66%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 0.66%   |
| SK hynix RAM Module 8192MB DIMM DDR4 2400MT/s                    | 1         | 0.66%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.66%   |
| SK hynix RAM Module 2GB SODIMM DDR2 667MT/s                      | 1         | 0.66%   |
| SK hynix RAM HYMP512U64CP8-Y5 1GB DIMM DDR2 1331MT/s             | 1         | 0.66%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s         | 1         | 0.66%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.66%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.66%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT425S6CFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |
| SK hynix RAM HMT41GU6MFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 0.66%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 40        | 36.36%  |
| DDR4    | 37        | 33.64%  |
| LPDDR4  | 12        | 10.91%  |
| SDRAM   | 8         | 7.27%   |
| DDR2    | 4         | 3.64%   |
| Unknown | 3         | 2.73%   |
| LPDDR3  | 2         | 1.82%   |
| DRAM    | 2         | 1.82%   |
| DDR5    | 1         | 0.91%   |
| DDR     | 1         | 0.91%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 67        | 63.81%  |
| DIMM         | 32        | 30.48%  |
| Row Of Chips | 6         | 5.71%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 41        | 34.17%  |
| 8192  | 39        | 32.5%   |
| 2048  | 22        | 18.33%  |
| 16384 | 13        | 10.83%  |
| 1024  | 3         | 2.5%    |
| 512   | 2         | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 28        | 21.88%  |
| 1333    | 17        | 13.28%  |
| 2400    | 16        | 12.5%   |
| 2667    | 14        | 10.94%  |
| 2133    | 11        | 8.59%   |
| 3200    | 9         | 7.03%   |
| 4267    | 3         | 2.34%   |
| 4199    | 3         | 2.34%   |
| 1334    | 3         | 2.34%   |
| 1067    | 3         | 2.34%   |
| 667     | 3         | 2.34%   |
| 3600    | 2         | 1.56%   |
| 3266    | 2         | 1.56%   |
| 1867    | 2         | 1.56%   |
| 533     | 2         | 1.56%   |
| 49926   | 1         | 0.78%   |
| 6000    | 1         | 0.78%   |
| 2934    | 1         | 0.78%   |
| 2933    | 1         | 0.78%   |
| 2048    | 1         | 0.78%   |
| 1648    | 1         | 0.78%   |
| 1331    | 1         | 0.78%   |
| 975     | 1         | 0.78%   |
| 400     | 1         | 0.78%   |
| Unknown | 1         | 0.78%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 24        | 16.55%  |
| Microdia                               | 23        | 15.86%  |
| Sunplus Innovation Technology          | 15        | 10.34%  |
| IMC Networks                           | 14        | 9.66%   |
| Realtek Semiconductor                  | 10        | 6.9%    |
| Suyin                                  | 9         | 6.21%   |
| Apple                                  | 7         | 4.83%   |
| Syntek                                 | 4         | 2.76%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 2.76%   |
| Silicon Motion                         | 3         | 2.07%   |
| Ricoh                                  | 3         | 2.07%   |
| OmniVision Technologies                | 3         | 2.07%   |
| Microsoft                              | 3         | 2.07%   |
| Logitech                               | 3         | 2.07%   |
| Bison Electronics                      | 3         | 2.07%   |
| Samsung Electronics                    | 2         | 1.38%   |
| Quanta                                 | 2         | 1.38%   |
| Primax Electronics                     | 2         | 1.38%   |
| Lite-On Technology                     | 2         | 1.38%   |
| icSpring                               | 2         | 1.38%   |
| Sonix Technology                       | 1         | 0.69%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.69%   |
| MacroSilicon                           | 1         | 0.69%   |
| Jieli Technology                       | 1         | 0.69%   |
| globaloptics                           | 1         | 0.69%   |
| Generalplus Technology                 | 1         | 0.69%   |
| Alcor Micro                            | 1         | 0.69%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                      | 7         | 4.83%   |
| Sunplus Integrated_Webcam_HD                                   | 6         | 4.14%   |
| Microdia HP Integrated Webcam                                  | 6         | 4.14%   |
| IMC Networks Integrated Camera                                 | 5         | 3.45%   |
| IMC Networks USB2.0 HD UVC WebCam                              | 4         | 2.76%   |
| Chicony USB2.0 HD UVC WebCam                                   | 4         | 2.76%   |
| Microdia Integrated_Webcam_HD                                  | 3         | 2.07%   |
| Microdia Dell Integrated HD Webcam                             | 3         | 2.07%   |
| IMC Networks HP TrueVision HD Camera                           | 3         | 2.07%   |
| Chicony HP TrueVision HD                                       | 3         | 2.07%   |
| Apple FaceTime HD Camera                                       | 3         | 2.07%   |
| Syntek Lenovo EasyCamera                                       | 2         | 1.38%   |
| Suyin Laptop_Integrated_Webcam_HD                              | 2         | 1.38%   |
| Suyin Integrated_Webcam_HD                                     | 2         | 1.38%   |
| Sunplus Laptop_Integrated_Webcam_FHD                           | 2         | 1.38%   |
| Samsung Galaxy series, misc. (MTP mode)                        | 2         | 1.38%   |
| Realtek USB2.0 camera                                          | 2         | 1.38%   |
| Realtek Integrated Webcam HD                                   | 2         | 1.38%   |
| Realtek Integrated Webcam                                      | 2         | 1.38%   |
| Microsoft MicrosoftÂ LifeCam HD-5001                          | 2         | 1.38%   |
| Microdia Sonix USB 2.0 Camera                                  | 2         | 1.38%   |
| Microdia Integrated Webcam                                     | 2         | 1.38%   |
| Chicony Integrated HP HD Webcam                                | 2         | 1.38%   |
| Chicony HD User Facing                                         | 2         | 1.38%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD Camera | 2         | 1.38%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                             | 2         | 1.38%   |
| Syntek Integrated Camera                                       | 1         | 0.69%   |
| Syntek EasyCamera                                              | 1         | 0.69%   |
| Suyin VGA Webcam                                               | 1         | 0.69%   |
| Suyin TOSHIBA Web Camera - HD                                  | 1         | 0.69%   |
| Suyin HP TrueVision HD                                         | 1         | 0.69%   |
| Suyin Acer/Lenovo Webcam [CN0316]                              | 1         | 0.69%   |
| Suyin 1.3M HD WebCam                                           | 1         | 0.69%   |
| Sunplus Laptop_Integrated_Webcam_HD                            | 1         | 0.69%   |
| Sunplus Laptop_Integrated_Webcam_1.3M                          | 1         | 0.69%   |
| Sunplus Integrated_Webcam_FHD                                  | 1         | 0.69%   |
| Sunplus HP Wide Vision HD                                      | 1         | 0.69%   |
| Sunplus HD WebCam                                              | 1         | 0.69%   |
| Sunplus ASUS Webcam                                            | 1         | 0.69%   |
| Sunplus 1.3M HD WebCam                                         | 1         | 0.69%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 7         | 35%     |
| Synaptics                  | 6         | 30%     |
| Elan Microelectronics      | 3         | 15%     |
| STMicroelectronics         | 1         | 5%      |
| Shenzhen Goodix Technology | 1         | 5%      |
| Samsung Electronics        | 1         | 5%      |
| LighTuning Technology      | 1         | 5%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader | 4         | 20%     |
| Validity Sensors VFS471 Fingerprint Reader        | 2         | 10%     |
| Elan ELAN:ARM-M4                                  | 2         | 10%     |
| Validity Sensors VFS5011 Fingerprint Reader       | 1         | 5%      |
| Validity Sensors VFS491                           | 1         | 5%      |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 5%      |
| Validity Sensors Synaptics WBDI                   | 1         | 5%      |
| Validity Sensors Fingerprint scanner              | 1         | 5%      |
| Synaptics  WBDI                                   | 1         | 5%      |
| Synaptics Metallica MIS Touch Fingerprint Reader  | 1         | 5%      |
| STMicroelectronics Fingerprint Reader             | 1         | 5%      |
| Shenzhen Goodix  FingerPrint Device               | 1         | 5%      |
| Samsung Fingerprint Sensor Device - 730B          | 1         | 5%      |
| LighTuning ES603 Swipe Fingerprint Sensor         | 1         | 5%      |
| Elan ELAN:Fingerprint                             | 1         | 5%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 9         | 69.23%  |
| O2 Micro    | 2         | 15.38%  |
| Alcor Micro | 2         | 15.38%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 30.77%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 15.38%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 15.38%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 2         | 15.38%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 7.69%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 7.69%   |
| Broadcom 58200                                                               | 1         | 7.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 158       | 71.82%  |
| 1     | 52        | 23.64%  |
| 2     | 10        | 4.55%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 20        | 27.78%  |
| Graphics card         | 18        | 25%     |
| Chipcard              | 11        | 15.28%  |
| Multimedia controller | 7         | 9.72%   |
| Net/wireless          | 6         | 8.33%   |
| Storage               | 3         | 4.17%   |
| Card reader           | 2         | 2.78%   |
| Camera                | 2         | 2.78%   |
| Unassigned class      | 1         | 1.39%   |
| Network               | 1         | 1.39%   |
| Bluetooth             | 1         | 1.39%   |

