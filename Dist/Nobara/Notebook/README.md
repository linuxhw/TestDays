Nobara - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Nobara.

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

Total: 225

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Unknown       | ACB20                       | [6e70bacda5](https://linux-hardware.org/?probe=6e70bacda5) | Apr 01, 2023 |
| Gigabyte      | AERO 15 XD                  | [51fd5b8510](https://linux-hardware.org/?probe=51fd5b8510) | Mar 25, 2023 |
| ASUSTek       | GL752VW                     | [8e1cd2ea46](https://linux-hardware.org/?probe=8e1cd2ea46) | Mar 24, 2023 |
| Intel         | powered classmate PC        | [0d64280b6d](https://linux-hardware.org/?probe=0d64280b6d) | Mar 22, 2023 |
| Lenovo        | Unknown                     | [121f022799](https://linux-hardware.org/?probe=121f022799) | Mar 21, 2023 |
| Acer          | Extensa 2510G               | [1ac79f58a4](https://linux-hardware.org/?probe=1ac79f58a4) | Mar 21, 2023 |
| Lenovo        | IP 5-14ALC05 82LM           | [5bacaa401a](https://linux-hardware.org/?probe=5bacaa401a) | Mar 21, 2023 |
| Acer          | Nitro AN515-52              | [6ad4034797](https://linux-hardware.org/?probe=6ad4034797) | Mar 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [7e6ae6ba16](https://linux-hardware.org/?probe=7e6ae6ba16) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [2530e262d2](https://linux-hardware.org/?probe=2530e262d2) | Mar 17, 2023 |
| ASUSTek       | X580VD                      | [8c4023bd5d](https://linux-hardware.org/?probe=8c4023bd5d) | Mar 16, 2023 |
| ASUSTek       | X580VD                      | [26b62abfc9](https://linux-hardware.org/?probe=26b62abfc9) | Mar 16, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | [7637d41bf3](https://linux-hardware.org/?probe=7637d41bf3) | Mar 14, 2023 |
| Dell          | Vostro 3400                 | [01bfc3e026](https://linux-hardware.org/?probe=01bfc3e026) | Mar 13, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | [9b021e4844](https://linux-hardware.org/?probe=9b021e4844) | Mar 11, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [126b4a73a2](https://linux-hardware.org/?probe=126b4a73a2) | Mar 11, 2023 |
| Dell          | Vostro 3400                 | [ed7724b921](https://linux-hardware.org/?probe=ed7724b921) | Mar 10, 2023 |
| Dell          | Vostro 3400                 | [6605d9e257](https://linux-hardware.org/?probe=6605d9e257) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [87eec74772](https://linux-hardware.org/?probe=87eec74772) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [38599c9b97](https://linux-hardware.org/?probe=38599c9b97) | Mar 10, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [0c14a418fb](https://linux-hardware.org/?probe=0c14a418fb) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [aa31db4d3f](https://linux-hardware.org/?probe=aa31db4d3f) | Mar 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [796b1ad7cb](https://linux-hardware.org/?probe=796b1ad7cb) | Mar 09, 2023 |
| HP            | ZBook 17                    | [e3fb994c04](https://linux-hardware.org/?probe=e3fb994c04) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [15cd198548](https://linux-hardware.org/?probe=15cd198548) | Mar 07, 2023 |
| Acer          | Aspire A515-51              | [ebf75e7be8](https://linux-hardware.org/?probe=ebf75e7be8) | Mar 06, 2023 |
| Acer          | Aspire A515-51              | [ef186545cb](https://linux-hardware.org/?probe=ef186545cb) | Mar 06, 2023 |
| HP            | ZBook 17 G2                 | [6efd61c4e0](https://linux-hardware.org/?probe=6efd61c4e0) | Mar 05, 2023 |
| Dell          | Latitude 7390               | [892100e074](https://linux-hardware.org/?probe=892100e074) | Mar 05, 2023 |
| Acer          | Aspire VX5-591G             | [e5e134cc80](https://linux-hardware.org/?probe=e5e134cc80) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [582bc638e0](https://linux-hardware.org/?probe=582bc638e0) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [25d1509478](https://linux-hardware.org/?probe=25d1509478) | Mar 03, 2023 |
| MSI           | GP65 Leopard 9SF            | [45f56a0c5b](https://linux-hardware.org/?probe=45f56a0c5b) | Mar 03, 2023 |
| Schenker      | XMG NEO (M19, RTX 2070)     | [c45dbeb188](https://linux-hardware.org/?probe=c45dbeb188) | Mar 02, 2023 |
| MSI           | P65 Creator 8RD             | [ea8be773a9](https://linux-hardware.org/?probe=ea8be773a9) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | [2b97507181](https://linux-hardware.org/?probe=2b97507181) | Mar 01, 2023 |
| ASUSTek       | GL752VW                     | [a3e7201f2e](https://linux-hardware.org/?probe=a3e7201f2e) | Mar 01, 2023 |
| Dell          | Inspiron 3542               | [686db926da](https://linux-hardware.org/?probe=686db926da) | Mar 01, 2023 |
| MSI           | Summit E14Evo A12M          | [ad389112d3](https://linux-hardware.org/?probe=ad389112d3) | Mar 01, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | [08f2d1cca5](https://linux-hardware.org/?probe=08f2d1cca5) | Feb 28, 2023 |
| HP            | ZBook 15u G3                | [9c49a1748b](https://linux-hardware.org/?probe=9c49a1748b) | Feb 28, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [5d17500c5d](https://linux-hardware.org/?probe=5d17500c5d) | Feb 25, 2023 |
| MSI           | GF63 Thin 10SC              | [824f4eafd0](https://linux-hardware.org/?probe=824f4eafd0) | Feb 25, 2023 |
| Gigabyte      | AERO 15 Classic-SA          | [bc6078dda0](https://linux-hardware.org/?probe=bc6078dda0) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | [92879d708d](https://linux-hardware.org/?probe=92879d708d) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | [8a698df80f](https://linux-hardware.org/?probe=8a698df80f) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [012415eb50](https://linux-hardware.org/?probe=012415eb50) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | [e1c3e1611f](https://linux-hardware.org/?probe=e1c3e1611f) | Feb 24, 2023 |
| Sony          | SVF1521N6EW                 | [41e45075c4](https://linux-hardware.org/?probe=41e45075c4) | Feb 22, 2023 |
| Dell          | G3 3590                     | [1a4fd9ed07](https://linux-hardware.org/?probe=1a4fd9ed07) | Feb 18, 2023 |
| HP            | ENVY 15                     | [bcdc62a706](https://linux-hardware.org/?probe=bcdc62a706) | Feb 18, 2023 |
| HP            | EliteBook Revolve 810 G1    | [a32189e068](https://linux-hardware.org/?probe=a32189e068) | Feb 16, 2023 |
| Dell          | Inspiron 5555               | [395077145c](https://linux-hardware.org/?probe=395077145c) | Feb 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [a54bcd6d70](https://linux-hardware.org/?probe=a54bcd6d70) | Feb 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [28e98cf31f](https://linux-hardware.org/?probe=28e98cf31f) | Feb 12, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | [6c8760114a](https://linux-hardware.org/?probe=6c8760114a) | Feb 11, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [9de8235ca5](https://linux-hardware.org/?probe=9de8235ca5) | Feb 10, 2023 |
| Acer          | TravelMate P256-M           | [add8ce8459](https://linux-hardware.org/?probe=add8ce8459) | Feb 06, 2023 |
| ASUSTek       | K52Jc                       | [464b35f82b](https://linux-hardware.org/?probe=464b35f82b) | Feb 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | [4ff2fc81bc](https://linux-hardware.org/?probe=4ff2fc81bc) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [0b1fbca173](https://linux-hardware.org/?probe=0b1fbca173) | Feb 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [c1862b275d](https://linux-hardware.org/?probe=c1862b275d) | Feb 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [1aa5d63f0c](https://linux-hardware.org/?probe=1aa5d63f0c) | Feb 01, 2023 |
| HP            | ZBook 15u G3                | [7f985597d7](https://linux-hardware.org/?probe=7f985597d7) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | [7a35a6d886](https://linux-hardware.org/?probe=7a35a6d886) | Jan 30, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [87502e1eb2](https://linux-hardware.org/?probe=87502e1eb2) | Jan 29, 2023 |
| Lenovo        | ThinkPad T460 20FMS79000    | [2b397905e1](https://linux-hardware.org/?probe=2b397905e1) | Jan 29, 2023 |
| Samsung       | R520/R522/R620              | [8c5c4fecfe](https://linux-hardware.org/?probe=8c5c4fecfe) | Jan 28, 2023 |
| Notebook      | NP5x_NP6x_NP7xHP            | [3b7c64dc34](https://linux-hardware.org/?probe=3b7c64dc34) | Jan 26, 2023 |
| Monster       | ABRA A7 V12.1               | [1882db09fe](https://linux-hardware.org/?probe=1882db09fe) | Jan 25, 2023 |
| MSI           | Katana GF76 11UD            | [5a5a26c29e](https://linux-hardware.org/?probe=5a5a26c29e) | Jan 24, 2023 |
| Positivo      | N1240                       | [e938a6c0b0](https://linux-hardware.org/?probe=e938a6c0b0) | Jan 24, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [8cb10f3212](https://linux-hardware.org/?probe=8cb10f3212) | Jan 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [bc070879ba](https://linux-hardware.org/?probe=bc070879ba) | Jan 22, 2023 |
| Medion        | GUARDIAN X10                | [4807ed03d5](https://linux-hardware.org/?probe=4807ed03d5) | Jan 22, 2023 |
| Apple         | MacBook5,1                  | [9732bb65cd](https://linux-hardware.org/?probe=9732bb65cd) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [844d97dd92](https://linux-hardware.org/?probe=844d97dd92) | Jan 20, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [87f11d2b18](https://linux-hardware.org/?probe=87f11d2b18) | Jan 19, 2023 |
| HP            | Pavilion Notebook           | [9a0b1c62f5](https://linux-hardware.org/?probe=9a0b1c62f5) | Jan 18, 2023 |
| Acer          | Swift SFX14-51G             | [f0137b1f08](https://linux-hardware.org/?probe=f0137b1f08) | Jan 17, 2023 |
| MSI           | Katana GF76 11UD            | [dcc8c2a63b](https://linux-hardware.org/?probe=dcc8c2a63b) | Jan 17, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | [b49ce7a30a](https://linux-hardware.org/?probe=b49ce7a30a) | Jan 15, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | [ab26ff36b1](https://linux-hardware.org/?probe=ab26ff36b1) | Jan 14, 2023 |
| Medion        | GUARDIAN X10                | [ef011d0700](https://linux-hardware.org/?probe=ef011d0700) | Jan 10, 2023 |
| HP            | Pavilion 15                 | [e60b327d4c](https://linux-hardware.org/?probe=e60b327d4c) | Jan 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [899e519abe](https://linux-hardware.org/?probe=899e519abe) | Jan 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [9f368d248b](https://linux-hardware.org/?probe=9f368d248b) | Jan 10, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | [d679fb0fd0](https://linux-hardware.org/?probe=d679fb0fd0) | Jan 10, 2023 |
| MSI           | GT680R/GX680R/GT683R/GT6... | [0b23cb61e0](https://linux-hardware.org/?probe=0b23cb61e0) | Jan 09, 2023 |
| HP            | EliteBook 840 G1            | [6f4cc6e4c7](https://linux-hardware.org/?probe=6f4cc6e4c7) | Jan 05, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | [f097aa1c92](https://linux-hardware.org/?probe=f097aa1c92) | Jan 03, 2023 |
| Apple         | MacBookPro8,1               | [97f93aa235](https://linux-hardware.org/?probe=97f93aa235) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | [7ef5d874e9](https://linux-hardware.org/?probe=7ef5d874e9) | Dec 28, 2022 |
| HP            | ENVY Notebook               | [8c7d592182](https://linux-hardware.org/?probe=8c7d592182) | Dec 26, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | [978bb114dc](https://linux-hardware.org/?probe=978bb114dc) | Dec 23, 2022 |
| Dell          | G15 5510                    | [86d0642973](https://linux-hardware.org/?probe=86d0642973) | Dec 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [03da9468fc](https://linux-hardware.org/?probe=03da9468fc) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [2a1a679e03](https://linux-hardware.org/?probe=2a1a679e03) | Dec 18, 2022 |
| Apple         | MacBookPro11,1              | [d3517edb25](https://linux-hardware.org/?probe=d3517edb25) | Dec 17, 2022 |
| Acer          | Aspire E5-551G              | [56f5130537](https://linux-hardware.org/?probe=56f5130537) | Dec 17, 2022 |
| HP            | EliteBook 8460p             | [0a2731119d](https://linux-hardware.org/?probe=0a2731119d) | Dec 16, 2022 |
| Dynabook      | PORTEGE X30L-K              | [6f9a9428b6](https://linux-hardware.org/?probe=6f9a9428b6) | Dec 16, 2022 |
| Dynabook      | PORTEGE X30L-K              | [28c00eabe8](https://linux-hardware.org/?probe=28c00eabe8) | Dec 14, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [6177c6a156](https://linux-hardware.org/?probe=6177c6a156) | Dec 13, 2022 |
| HP            | EliteBook 8570p             | [52f0fae7e4](https://linux-hardware.org/?probe=52f0fae7e4) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | [be0c42b073](https://linux-hardware.org/?probe=be0c42b073) | Dec 12, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [52a8f66027](https://linux-hardware.org/?probe=52a8f66027) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [febce6b929](https://linux-hardware.org/?probe=febce6b929) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | [4fd43d5aff](https://linux-hardware.org/?probe=4fd43d5aff) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | [13e9fa6c58](https://linux-hardware.org/?probe=13e9fa6c58) | Dec 09, 2022 |
| Dynabook      | PORTEGE X30L-K              | [75a8aa38fc](https://linux-hardware.org/?probe=75a8aa38fc) | Dec 08, 2022 |
| Lenovo        | Z50-70 20354                | [07bf98d8f7](https://linux-hardware.org/?probe=07bf98d8f7) | Dec 07, 2022 |
| HP            | Laptop 14-cm1xxx            | [6fbbd3608f](https://linux-hardware.org/?probe=6fbbd3608f) | Dec 06, 2022 |
| Lenovo        | V14-IIL 82C4                | [e23dd27dc9](https://linux-hardware.org/?probe=e23dd27dc9) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [5ce6793478](https://linux-hardware.org/?probe=5ce6793478) | Dec 06, 2022 |
| Valve         | Jupiter                     | [ef85b8ab38](https://linux-hardware.org/?probe=ef85b8ab38) | Nov 28, 2022 |
| Valve         | Jupiter                     | [622315486c](https://linux-hardware.org/?probe=622315486c) | Nov 28, 2022 |
| Lenovo        | V14-IIL 82C4                | [407b574c57](https://linux-hardware.org/?probe=407b574c57) | Nov 28, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [91fa73480c](https://linux-hardware.org/?probe=91fa73480c) | Nov 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | [93576caa19](https://linux-hardware.org/?probe=93576caa19) | Nov 26, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | [eded61b721](https://linux-hardware.org/?probe=eded61b721) | Nov 25, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [be2f8c9fd3](https://linux-hardware.org/?probe=be2f8c9fd3) | Nov 24, 2022 |
| HP            | ProBook 445 14 inch G9 N... | [a20535bd66](https://linux-hardware.org/?probe=a20535bd66) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [9324629428](https://linux-hardware.org/?probe=9324629428) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | [22a1c81a68](https://linux-hardware.org/?probe=22a1c81a68) | Nov 24, 2022 |
| Coradir       | Coradir/ES10IS5             | [a1fb1953ad](https://linux-hardware.org/?probe=a1fb1953ad) | Nov 22, 2022 |
| Lenovo        | G580 20150                  | [6e28c07a6c](https://linux-hardware.org/?probe=6e28c07a6c) | Nov 22, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| HP            | Unknown                     | [9b1181bc4b](https://linux-hardware.org/?probe=9b1181bc4b) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [93ad560f52](https://linux-hardware.org/?probe=93ad560f52) | Nov 17, 2022 |
| Dell          | Studio 1737                 | [883ac54ca7](https://linux-hardware.org/?probe=883ac54ca7) | Nov 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | [3ee89779cd](https://linux-hardware.org/?probe=3ee89779cd) | Nov 15, 2022 |
| Lenovo        | G50-30 80G0                 | [978fdef2f8](https://linux-hardware.org/?probe=978fdef2f8) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | [b33f7744b5](https://linux-hardware.org/?probe=b33f7744b5) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | [9d7853c05b](https://linux-hardware.org/?probe=9d7853c05b) | Nov 13, 2022 |
| Acer          | Swift SFX14-41G             | [a8023a34a0](https://linux-hardware.org/?probe=a8023a34a0) | Nov 11, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | [3d53644c05](https://linux-hardware.org/?probe=3d53644c05) | Nov 08, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [c6460ff904](https://linux-hardware.org/?probe=c6460ff904) | Nov 07, 2022 |
| Dell          | Studio 1737                 | [d286ea1b6c](https://linux-hardware.org/?probe=d286ea1b6c) | Nov 07, 2022 |
| ASUSTek       | GL753VD                     | [97e2ee4ee1](https://linux-hardware.org/?probe=97e2ee4ee1) | Nov 01, 2022 |
| HP            | Unknown                     | [1ca885060e](https://linux-hardware.org/?probe=1ca885060e) | Nov 01, 2022 |
| Acer          | Nitro AN515-42              | [3a00ca53c8](https://linux-hardware.org/?probe=3a00ca53c8) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Apple         | MacBookPro13,3              | [b028075707](https://linux-hardware.org/?probe=b028075707) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | [4fdbc3c415](https://linux-hardware.org/?probe=4fdbc3c415) | Oct 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [50a8c356f0](https://linux-hardware.org/?probe=50a8c356f0) | Oct 28, 2022 |
| ASUSTek       | GL502VMK                    | [9a18ff1b13](https://linux-hardware.org/?probe=9a18ff1b13) | Oct 25, 2022 |
| Toshiba       | Satellite L850              | [8bfeff52e6](https://linux-hardware.org/?probe=8bfeff52e6) | Oct 24, 2022 |
| ASUSTek       | S550CB                      | [a81f0ecac8](https://linux-hardware.org/?probe=a81f0ecac8) | Oct 24, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [3912d818bd](https://linux-hardware.org/?probe=3912d818bd) | Oct 23, 2022 |
| HP            | OMEN Notebook PC 15         | [1d5ebc92c4](https://linux-hardware.org/?probe=1d5ebc92c4) | Oct 23, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [eaecfdf473](https://linux-hardware.org/?probe=eaecfdf473) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [c044987599](https://linux-hardware.org/?probe=c044987599) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | [b6fd429ceb](https://linux-hardware.org/?probe=b6fd429ceb) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | [f33baf66a9](https://linux-hardware.org/?probe=f33baf66a9) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [e5a34da4a2](https://linux-hardware.org/?probe=e5a34da4a2) | Oct 19, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [829326a8e5](https://linux-hardware.org/?probe=829326a8e5) | Oct 18, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | [697ccec46b](https://linux-hardware.org/?probe=697ccec46b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | [dfeb98414b](https://linux-hardware.org/?probe=dfeb98414b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | [7f8c9d778c](https://linux-hardware.org/?probe=7f8c9d778c) | Oct 18, 2022 |
| Casper        | EXCALIBUR G770              | [7961a3ca3e](https://linux-hardware.org/?probe=7961a3ca3e) | Oct 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [5f013faf39](https://linux-hardware.org/?probe=5f013faf39) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | [89f43e5484](https://linux-hardware.org/?probe=89f43e5484) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | [43f57daebb](https://linux-hardware.org/?probe=43f57daebb) | Oct 12, 2022 |
| MSI           | Pulse GL76 12UEK            | [6a2be4d08c](https://linux-hardware.org/?probe=6a2be4d08c) | Oct 12, 2022 |
| EVOO          | EG-LP10                     | [f8895e9483](https://linux-hardware.org/?probe=f8895e9483) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | [2aa595867e](https://linux-hardware.org/?probe=2aa595867e) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | [bd224480a9](https://linux-hardware.org/?probe=bd224480a9) | Oct 10, 2022 |
| HP            | 2000                        | [3341a26d0c](https://linux-hardware.org/?probe=3341a26d0c) | Oct 10, 2022 |
| ASUSTek       | GL503VD                     | [1405b367c2](https://linux-hardware.org/?probe=1405b367c2) | Oct 09, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [94ccd99c78](https://linux-hardware.org/?probe=94ccd99c78) | Oct 09, 2022 |
| Apple         | MacBookPro5,5               | [faef78b510](https://linux-hardware.org/?probe=faef78b510) | Oct 08, 2022 |
| HP            | Laptop 15-dw0xxx            | [3427421197](https://linux-hardware.org/?probe=3427421197) | Oct 08, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [2d464da9c8](https://linux-hardware.org/?probe=2d464da9c8) | Oct 07, 2022 |
| HP            | ZBook 17 G6                 | [c215e9e17e](https://linux-hardware.org/?probe=c215e9e17e) | Oct 07, 2022 |
| Dell          | Precision 5530              | [db48ac269b](https://linux-hardware.org/?probe=db48ac269b) | Oct 07, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | [9ccbc0ed3c](https://linux-hardware.org/?probe=9ccbc0ed3c) | Oct 07, 2022 |
| KELYX ARGE... | KL9120                      | [faa5f13391](https://linux-hardware.org/?probe=faa5f13391) | Oct 06, 2022 |
| Positivo      | N1250                       | [9845103c14](https://linux-hardware.org/?probe=9845103c14) | Oct 05, 2022 |
| HP            | 2000                        | [e6f8f7196d](https://linux-hardware.org/?probe=e6f8f7196d) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [3ec3f59233](https://linux-hardware.org/?probe=3ec3f59233) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [5ed7136249](https://linux-hardware.org/?probe=5ed7136249) | Oct 03, 2022 |
| HP            | 240 G7 Notebook PC          | [05b4e2117b](https://linux-hardware.org/?probe=05b4e2117b) | Oct 03, 2022 |
| Toshiba       | Satellite L850              | [0e57d064b0](https://linux-hardware.org/?probe=0e57d064b0) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [05e921b4aa](https://linux-hardware.org/?probe=05e921b4aa) | Oct 02, 2022 |
| EVOO          | EG-LP10                     | [32c1a174d1](https://linux-hardware.org/?probe=32c1a174d1) | Oct 01, 2022 |
| Acer          | Aspire VX5-591G             | [b321f4561b](https://linux-hardware.org/?probe=b321f4561b) | Sep 29, 2022 |
| Lenovo        | V330-15IKB 81AX             | [0360123f76](https://linux-hardware.org/?probe=0360123f76) | Sep 29, 2022 |
| Lenovo        | G580 20157                  | [2b34d591ab](https://linux-hardware.org/?probe=2b34d591ab) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | [a423006d4c](https://linux-hardware.org/?probe=a423006d4c) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | [5dba6cf7fd](https://linux-hardware.org/?probe=5dba6cf7fd) | Sep 29, 2022 |
| Dell          | Inspiron 3542               | [6d35107941](https://linux-hardware.org/?probe=6d35107941) | Sep 28, 2022 |
| Apple         | MacBookPro8,3               | [74927fc7d2](https://linux-hardware.org/?probe=74927fc7d2) | Sep 27, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | [65f896ddab](https://linux-hardware.org/?probe=65f896ddab) | Sep 27, 2022 |
| Gateway       | NE56R                       | [f603edd045](https://linux-hardware.org/?probe=f603edd045) | Sep 23, 2022 |
| Toshiba       | TECRA A50-A                 | [6ef2538a5a](https://linux-hardware.org/?probe=6ef2538a5a) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [605e97df5c](https://linux-hardware.org/?probe=605e97df5c) | Sep 22, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [94e6332c62](https://linux-hardware.org/?probe=94e6332c62) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [2e36489a4b](https://linux-hardware.org/?probe=2e36489a4b) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [8705683c6f](https://linux-hardware.org/?probe=8705683c6f) | Sep 22, 2022 |
| Alienware     | Area-51m R2 A00             | [0ebdec6dd0](https://linux-hardware.org/?probe=0ebdec6dd0) | Sep 20, 2022 |
| ASUSTek       | N56VZ                       | [ce162c52c0](https://linux-hardware.org/?probe=ce162c52c0) | Sep 19, 2022 |
| Lenovo        | IdeaPadFlex 10 20324        | [4e7f3b7bac](https://linux-hardware.org/?probe=4e7f3b7bac) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [854a0d4410](https://linux-hardware.org/?probe=854a0d4410) | Sep 19, 2022 |
| Dell          | Precision M6400             | [67924c5333](https://linux-hardware.org/?probe=67924c5333) | Sep 19, 2022 |
| Dell          | Precision M6400             | [27a55639e4](https://linux-hardware.org/?probe=27a55639e4) | Sep 19, 2022 |
| HUAWEI        | KLVL-WXXW                   | [e0e49d51d0](https://linux-hardware.org/?probe=e0e49d51d0) | Sep 18, 2022 |
| HUAWEI        | KLVL-WXXW                   | [812ea842dc](https://linux-hardware.org/?probe=812ea842dc) | Sep 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [004d0a2b9d](https://linux-hardware.org/?probe=004d0a2b9d) | Sep 17, 2022 |
| Lenovo        | ThinkPad P1 20MD0020US      | [a701fed148](https://linux-hardware.org/?probe=a701fed148) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [5ffc7d13ac](https://linux-hardware.org/?probe=5ffc7d13ac) | Sep 16, 2022 |
| Dell          | G5 5505                     | [25755e8605](https://linux-hardware.org/?probe=25755e8605) | Sep 16, 2022 |
| HP            | 15                          | [79aa0d618f](https://linux-hardware.org/?probe=79aa0d618f) | Sep 14, 2022 |
| Acer          | Aspire A315-42              | [820c1e2ac6](https://linux-hardware.org/?probe=820c1e2ac6) | Sep 11, 2022 |
| Dell          | Precision 3510              | [4337a8e018](https://linux-hardware.org/?probe=4337a8e018) | Sep 11, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0ca693e2dd](https://linux-hardware.org/?probe=0ca693e2dd) | Aug 31, 2022 |
| ASUSTek       | TP500LA                     | [de395dddd8](https://linux-hardware.org/?probe=de395dddd8) | Aug 28, 2022 |
| Dell          | G15 5511                    | [44fa9bf084](https://linux-hardware.org/?probe=44fa9bf084) | Aug 21, 2022 |
| Notebook      | P7xxDM2(-G)                 | [f074899985](https://linux-hardware.org/?probe=f074899985) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [315da58d24](https://linux-hardware.org/?probe=315da58d24) | Aug 16, 2022 |
| Apple         | MacBookPro14,2              | [c66d476513](https://linux-hardware.org/?probe=c66d476513) | Aug 13, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [df2cc1a299](https://linux-hardware.org/?probe=df2cc1a299) | Aug 12, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [6beddf67f5](https://linux-hardware.org/?probe=6beddf67f5) | Aug 06, 2022 |
| Razer         | Blade                       | [cc3ce45956](https://linux-hardware.org/?probe=cc3ce45956) | Jul 31, 2022 |
| HP            | ZBook 15 G2                 | [3aa2fda09a](https://linux-hardware.org/?probe=3aa2fda09a) | Jul 26, 2022 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Notebooks | Percent |
|-----------|-----------|---------|
| Nobara 36 | 111       | 63.79%  |
| Nobara 37 | 63        | 36.21%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Nobara | 172       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Notebooks | Percent |
|-------------------------------|-----------|---------|
| 6.0.10-201.fc36.x86_64        | 19        | 10.73%  |
| 5.19.14-201.fsync.fc36.x86_64 | 16        | 9.04%   |
| 6.1.11-201.fsync.fc37.x86_64  | 12        | 6.78%   |
| 6.1.4-203.fsync.fc37.x86_64   | 9         | 5.08%   |
| 6.1.14-201.fsync.fc37.x86_64  | 9         | 5.08%   |
| 6.0.14-201.fsync.fc36.x86_64  | 9         | 5.08%   |
| 6.1.9-200.fsync.fc37.x86_64   | 7         | 3.95%   |
| 6.0.16-301.fsync.fc37.x86_64  | 7         | 3.95%   |
| 5.19.9-201.fsync.fc36.x86_64  | 7         | 3.95%   |
| 5.19.7-204.fsync.fc36.x86_64  | 7         | 3.95%   |
| 6.0.7-201.fsync.fc36.x86_64   | 6         | 3.39%   |
| 6.0.5-201.fsync.fc36.x86_64   | 5         | 2.82%   |
| 5.19.12-201.fsync.fc36.x86_64 | 5         | 2.82%   |
| 6.2.6-201.fsync.fc37.x86_64   | 4         | 2.26%   |
| 6.1.8-202.fsync.fc37.x86_64   | 4         | 2.26%   |
| 5.19.8-201.fsync.fc36.x86_64  | 4         | 2.26%   |
| 5.19.16-201.fsync.fc36.x86_64 | 4         | 2.26%   |
| 5.19.11-201.fsync.fc36.x86_64 | 4         | 2.26%   |
| 6.1.6-203.fsync.fc37.x86_64   | 3         | 1.69%   |
| 6.0.9-202.fc36.x86_64         | 3         | 1.69%   |
| 6.0.9-201.fc36.x86_64         | 3         | 1.69%   |
| 5.18.16-201.fsync.fc36.x86_64 | 3         | 1.69%   |
| 5.18.13-201.fsync.fc36.x86_64 | 3         | 1.69%   |
| 6.1.6-202.fsync.fc37.x86_64   | 2         | 1.13%   |
| 6.1.6-201.fsync.fc37.x86_64   | 2         | 1.13%   |
| 6.0.8-201.fsync.fc36.x86_64   | 2         | 1.13%   |
| 5.19.4-201.fsync.fc36.x86_64  | 2         | 1.13%   |
| 5.19.15-202.fsync.fc36.x86_64 | 2         | 1.13%   |
| 5.18.17-201.fsync.fc36.x86_64 | 2         | 1.13%   |
| 6.2.8-200.fsync.fc37.x86_64   | 1         | 0.56%   |
| 6.1.8-201.fsync.fc37.x86_64   | 1         | 0.56%   |
| 6.1.8-200.fsync.fc37.x86_64   | 1         | 0.56%   |
| 6.0.7-202.fsync.fc36.x86_64   | 1         | 0.56%   |
| 6.0.2-xm1.0.fc36.x86_64       | 1         | 0.56%   |
| 6.0.15-301.fsync.fc37.x86_64  | 1         | 0.56%   |
| 6.0.13-201.fsync.fc36.x86_64  | 1         | 0.56%   |
| 5.19.7-203.fsync.fc36.x86_64  | 1         | 0.56%   |
| 5.19.13-202.fsync.fc36.x86_64 | 1         | 0.56%   |
| 5.19.10-201.fsync.fc36.x86_64 | 1         | 0.56%   |
| 5.18.19-201.fsync.fc36.x86_64 | 1         | 0.56%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0.10  | 19        | 10.73%  |
| 5.19.14 | 16        | 9.04%   |
| 6.1.11  | 12        | 6.78%   |
| 6.1.4   | 9         | 5.08%   |
| 6.1.14  | 9         | 5.08%   |
| 6.0.14  | 9         | 5.08%   |
| 5.19.7  | 8         | 4.52%   |
| 6.1.9   | 7         | 3.95%   |
| 6.1.6   | 7         | 3.95%   |
| 6.0.7   | 7         | 3.95%   |
| 6.0.16  | 7         | 3.95%   |
| 5.19.9  | 7         | 3.95%   |
| 6.1.8   | 6         | 3.39%   |
| 6.0.9   | 6         | 3.39%   |
| 6.0.5   | 5         | 2.82%   |
| 5.19.12 | 5         | 2.82%   |
| 6.2.6   | 4         | 2.26%   |
| 5.19.8  | 4         | 2.26%   |
| 5.19.16 | 4         | 2.26%   |
| 5.19.11 | 4         | 2.26%   |
| 5.18.16 | 3         | 1.69%   |
| 5.18.13 | 3         | 1.69%   |
| 6.0.8   | 2         | 1.13%   |
| 5.19.4  | 2         | 1.13%   |
| 5.19.15 | 2         | 1.13%   |
| 5.18.17 | 2         | 1.13%   |
| 6.2.8   | 1         | 0.56%   |
| 6.0.2   | 1         | 0.56%   |
| 6.0.15  | 1         | 0.56%   |
| 6.0.13  | 1         | 0.56%   |
| 5.19.13 | 1         | 0.56%   |
| 5.19.10 | 1         | 0.56%   |
| 5.18.19 | 1         | 0.56%   |
| 5.18.18 | 1         | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0     | 57        | 32.39%  |
| 5.19    | 54        | 30.68%  |
| 6.1     | 50        | 28.41%  |
| 5.18    | 10        | 5.68%   |
| 6.2     | 5         | 2.84%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 172       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 122       | 70.11%  |
| KDE5    | 48        | 27.59%  |
| Unknown | 4         | 2.3%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 139       | 79.89%  |
| X11     | 30        | 17.24%  |
| Unknown | 4         | 2.3%    |
| Tty     | 1         | 0.57%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 140       | 80%     |
| GDM     | 18        | 10.29%  |
| SDDM    | 15        | 8.57%   |
| LightDM | 2         | 1.14%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 89        | 51.45%  |
| es_ES   | 10        | 5.78%   |
| en_GB   | 9         | 5.2%    |
| ru_RU   | 6         | 3.47%   |
| pl_PL   | 6         | 3.47%   |
| pt_BR   | 5         | 2.89%   |
| it_IT   | 5         | 2.89%   |
| es_MX   | 4         | 2.31%   |
| en_IN   | 4         | 2.31%   |
| de_DE   | 4         | 2.31%   |
| pt_PT   | 3         | 1.73%   |
| es_AR   | 3         | 1.73%   |
| en_NZ   | 3         | 1.73%   |
| tr_TR   | 2         | 1.16%   |
| en_CA   | 2         | 1.16%   |
| Unknown | 2         | 1.16%   |
| zh_TW   | 1         | 0.58%   |
| sv_SE   | 1         | 0.58%   |
| nb_NO   | 1         | 0.58%   |
| hu_HU   | 1         | 0.58%   |
| hr_HR   | 1         | 0.58%   |
| fr_FR   | 1         | 0.58%   |
| fi_FI   | 1         | 0.58%   |
| es_US   | 1         | 0.58%   |
| es_CR   | 1         | 0.58%   |
| es_CO   | 1         | 0.58%   |
| es_CL   | 1         | 0.58%   |
| en_ZA   | 1         | 0.58%   |
| en_PH   | 1         | 0.58%   |
| en_IE   | 1         | 0.58%   |
| en_AU   | 1         | 0.58%   |
| de_AT   | 1         | 0.58%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 143       | 82.66%  |
| BIOS | 30        | 17.34%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 113       | 65.32%  |
| Ext4  | 59        | 34.1%   |
| Xfs   | 1         | 0.58%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 138       | 78.41%  |
| GPT     | 35        | 19.89%  |
| MBR     | 3         | 1.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 162       | 93.64%  |
| Yes       | 11        | 6.36%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 151       | 87.79%  |
| Yes       | 21        | 12.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 40        | 23.26%  |
| ASUSTek Computer    | 33        | 19.19%  |
| Hewlett-Packard     | 28        | 16.28%  |
| Dell                | 15        | 8.72%   |
| Acer                | 12        | 6.98%   |
| MSI                 | 8         | 4.65%   |
| Apple               | 8         | 4.65%   |
| Toshiba             | 3         | 1.74%   |
| Gigabyte Technology | 3         | 1.74%   |
| Positivo            | 2         | 1.16%   |
| Notebook            | 2         | 1.16%   |
| Valve               | 1         | 0.58%   |
| Sony                | 1         | 0.58%   |
| Schenker            | 1         | 0.58%   |
| Samsung Electronics | 1         | 0.58%   |
| Razer               | 1         | 0.58%   |
| ONE-NETBOOK         | 1         | 0.58%   |
| Monster             | 1         | 0.58%   |
| Medion              | 1         | 0.58%   |
| Intel               | 1         | 0.58%   |
| HUAWEI              | 1         | 0.58%   |
| Gateway             | 1         | 0.58%   |
| EVOO                | 1         | 0.58%   |
| Dynabook            | 1         | 0.58%   |
| Coradir             | 1         | 0.58%   |
| Casper              | 1         | 0.58%   |
| ASRock              | 1         | 0.58%   |
| Alienware           | 1         | 0.58%   |
| Unknown             | 1         | 0.58%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                     | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Unknown                                                  | 4         | 2.33%   |
| Lenovo Legion 5 15ARH05 82B5                             | 2         | 1.16%   |
| Lenovo IdeaPad Y700-15ISK 80NV                           | 2         | 1.16%   |
| Lenovo IdeaPad C340-14API 81N6                           | 2         | 1.16%   |
| HP ZBook 15u G3                                          | 2         | 1.16%   |
| HP Pavilion Gaming Laptop 15-ec1xxx                      | 2         | 1.16%   |
| Dell Vostro 3400                                         | 2         | 1.16%   |
| Dell Inspiron 3542                                       | 2         | 1.16%   |
| Acer Aspire VX5-591G                                     | 2         | 1.16%   |
| Valve Jupiter                                            | 1         | 0.58%   |
| Toshiba TECRA A50-A                                      | 1         | 0.58%   |
| Toshiba Satellite L850                                   | 1         | 0.58%   |
| Toshiba Satellite L650                                   | 1         | 0.58%   |
| Sony SVF1521N6EW                                         | 1         | 0.58%   |
| Schenker XMG NEO (M19, RTX 2070)                         | 1         | 0.58%   |
| Samsung R520/R522/R620                                   | 1         | 0.58%   |
| Razer Blade                                              | 1         | 0.58%   |
| Positivo N1250                                           | 1         | 0.58%   |
| Positivo N1240                                           | 1         | 0.58%   |
| ONE-NETBOOK ONEXPLAYER 2 ARP23                           | 1         | 0.58%   |
| Notebook P7xxDM2(-G)                                     | 1         | 0.58%   |
| Notebook NP5x_NP6x_NP7xHP                                | 1         | 0.58%   |
| MSI Summit E14Evo A12M                                   | 1         | 0.58%   |
| MSI Pulse GL76 12UEK                                     | 1         | 0.58%   |
| MSI P65 Creator 8RD                                      | 1         | 0.58%   |
| MSI Katana GF76 11UD                                     | 1         | 0.58%   |
| MSI GT680R/GX680R/GT683R/GT683DXR/GT685R/GT687R/GX660DXR | 1         | 0.58%   |
| MSI GP65 Leopard 9SF                                     | 1         | 0.58%   |
| MSI GF63 Thin 10SC                                       | 1         | 0.58%   |
| MSI GE60 0NC/GE60 0ND                                    | 1         | 0.58%   |
| Monster ABRA A7 V12.1                                    | 1         | 0.58%   |
| Medion GUARDIAN X10                                      | 1         | 0.58%   |
| Lenovo Z50-70 20354                                      | 1         | 0.58%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 OD 82NK                    | 1         | 0.58%   |
| Lenovo V330-15IKB 81AX                                   | 1         | 0.58%   |
| Lenovo V14-IIL 82C4                                      | 1         | 0.58%   |
| Lenovo ThinkPad X240 20AMA0LTAU                          | 1         | 0.58%   |
| Lenovo ThinkPad X1 Extreme Gen 5 21DECTO1WW              | 1         | 0.58%   |
| Lenovo ThinkPad X1 Extreme Gen 3 20TK0047US              | 1         | 0.58%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWS0ME00               | 1         | 0.58%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo IdeaPad         | 14        | 8.14%   |
| Lenovo ThinkPad        | 9         | 5.23%   |
| ASUS ROG               | 9         | 5.23%   |
| ASUS VivoBook          | 8         | 4.65%   |
| Lenovo Legion          | 6         | 3.49%   |
| HP EliteBook           | 6         | 3.49%   |
| Acer Aspire            | 6         | 3.49%   |
| HP ZBook               | 5         | 2.91%   |
| HP Pavilion            | 5         | 2.91%   |
| ASUS ASUS              | 4         | 2.33%   |
| Unknown                | 4         | 2.33%   |
| Dell Vostro            | 3         | 1.74%   |
| Dell Precision         | 3         | 1.74%   |
| Dell Inspiron          | 3         | 1.74%   |
| ASUS TUF               | 3         | 1.74%   |
| Toshiba Satellite      | 2         | 1.16%   |
| Lenovo G580            | 2         | 1.16%   |
| HP OMEN                | 2         | 1.16%   |
| HP Laptop              | 2         | 1.16%   |
| HP ENVY                | 2         | 1.16%   |
| Gigabyte AERO          | 2         | 1.16%   |
| Dell G15               | 2         | 1.16%   |
| Apple MacBookPro8      | 2         | 1.16%   |
| Acer Swift             | 2         | 1.16%   |
| Acer Nitro             | 2         | 1.16%   |
| Valve Jupiter          | 1         | 0.58%   |
| Toshiba TECRA          | 1         | 0.58%   |
| Sony SVF1521N6EW       | 1         | 0.58%   |
| Schenker XMG           | 1         | 0.58%   |
| Samsung R520           | 1         | 0.58%   |
| Razer Blade            | 1         | 0.58%   |
| Positivo N1250         | 1         | 0.58%   |
| Positivo N1240         | 1         | 0.58%   |
| ONE-NETBOOK ONEXPLAYER | 1         | 0.58%   |
| Notebook P7xxDM2(-G)   | 1         | 0.58%   |
| Notebook NP5x          | 1         | 0.58%   |
| MSI Summit             | 1         | 0.58%   |
| MSI Pulse              | 1         | 0.58%   |
| MSI P65                | 1         | 0.58%   |
| MSI Katana             | 1         | 0.58%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 28        | 16.28%  |
| 2020 | 22        | 12.79%  |
| 2022 | 19        | 11.05%  |
| 2019 | 17        | 9.88%   |
| 2018 | 15        | 8.72%   |
| 2014 | 13        | 7.56%   |
| 2013 | 11        | 6.4%    |
| 2017 | 10        | 5.81%   |
| 2012 | 9         | 5.23%   |
| 2016 | 7         | 4.07%   |
| 2015 | 7         | 4.07%   |
| 2010 | 5         | 2.91%   |
| 2009 | 4         | 2.33%   |
| 2011 | 3         | 1.74%   |
| 2023 | 1         | 0.58%   |
| 2008 | 1         | 0.58%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 172       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 172       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 172       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 44        | 25.58%  |
| 8.01-16.0  | 41        | 23.84%  |
| 16.01-24.0 | 38        | 22.09%  |
| 3.01-4.0   | 22        | 12.79%  |
| 32.01-64.0 | 20        | 11.63%  |
| 24.01-32.0 | 5         | 2.91%   |
| 1.01-2.0   | 2         | 1.16%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 79        | 45.4%   |
| 2.01-3.0  | 42        | 24.14%  |
| 3.01-4.0  | 39        | 22.41%  |
| 8.01-16.0 | 10        | 5.75%   |
| 1.01-2.0  | 4         | 2.3%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 123       | 71.51%  |
| 2      | 44        | 25.58%  |
| 3      | 5         | 2.91%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 138       | 80.23%  |
| Yes       | 34        | 19.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 136       | 79.07%  |
| No        | 36        | 20.93%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 170       | 98.84%  |
| No        | 2         | 1.16%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 154       | 89.53%  |
| No        | 18        | 10.47%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 48        | 27.91%  |
| Spain        | 11        | 6.4%    |
| Poland       | 11        | 6.4%    |
| Germany      | 9         | 5.23%   |
| Brazil       | 7         | 4.07%   |
| Russia       | 6         | 3.49%   |
| Italy        | 6         | 3.49%   |
| India        | 6         | 3.49%   |
| Mexico       | 5         | 2.91%   |
| UK           | 4         | 2.33%   |
| Portugal     | 4         | 2.33%   |
| Sweden       | 3         | 1.74%   |
| Romania      | 3         | 1.74%   |
| Philippines  | 3         | 1.74%   |
| New Zealand  | 3         | 1.74%   |
| Chile        | 3         | 1.74%   |
| Argentina    | 3         | 1.74%   |
| Vietnam      | 2         | 1.16%   |
| Turkey       | 2         | 1.16%   |
| Indonesia    | 2         | 1.16%   |
| Egypt        | 2         | 1.16%   |
| Croatia      | 2         | 1.16%   |
| Colombia     | 2         | 1.16%   |
| Canada       | 2         | 1.16%   |
| Austria      | 2         | 1.16%   |
| Venezuela    | 1         | 0.58%   |
| Taiwan       | 1         | 0.58%   |
| South Africa | 1         | 0.58%   |
| Slovenia     | 1         | 0.58%   |
| Serbia       | 1         | 0.58%   |
| Panama       | 1         | 0.58%   |
| Pakistan     | 1         | 0.58%   |
| Norway       | 1         | 0.58%   |
| Morocco      | 1         | 0.58%   |
| Kenya        | 1         | 0.58%   |
| Ireland      | 1         | 0.58%   |
| Hungary      | 1         | 0.58%   |
| Hong Kong    | 1         | 0.58%   |
| France       | 1         | 0.58%   |
| Finland      | 1         | 0.58%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Wroclaw             | 3         | 1.69%   |
| Auckland            | 3         | 1.69%   |
| Wasilla             | 2         | 1.13%   |
| Warsaw              | 2         | 1.13%   |
| Schmalkalden        | 2         | 1.13%   |
| Salem               | 2         | 1.13%   |
| Poznan              | 2         | 1.13%   |
| Perm                | 2         | 1.13%   |
| Panama City         | 2         | 1.13%   |
| Ochsenfurt          | 2         | 1.13%   |
| Mumbai              | 2         | 1.13%   |
| Milan               | 2         | 1.13%   |
| Madrid              | 2         | 1.13%   |
| London              | 2         | 1.13%   |
| Guadalajara         | 2         | 1.13%   |
| Fortaleza           | 2         | 1.13%   |
| Bucharest           | 2         | 1.13%   |
| Zaragoza            | 1         | 0.56%   |
| Zamora              | 1         | 0.56%   |
| Zadar               | 1         | 0.56%   |
| Wesley Chapel       | 1         | 0.56%   |
| Wayne               | 1         | 0.56%   |
| Wabrzezno           | 1         | 0.56%   |
| Vladivostok         | 1         | 0.56%   |
| Villarrica          | 1         | 0.56%   |
| Villacarrillo       | 1         | 0.56%   |
| Villa Nueva         | 1         | 0.56%   |
| Vienna              | 1         | 0.56%   |
| Veszprém           | 1         | 0.56%   |
| Varaždin           | 1         | 0.56%   |
| Valladolid          | 1         | 0.56%   |
| Vagos               | 1         | 0.56%   |
| Ulm                 | 1         | 0.56%   |
| Uhldingen-Muhlhofen | 1         | 0.56%   |
| Tulsa               | 1         | 0.56%   |
| Tomah               | 1         | 0.56%   |
| Tenna               | 1         | 0.56%   |
| Temuco              | 1         | 0.56%   |
| Tampa               | 1         | 0.56%   |
| Sunnyvale           | 1         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 47        | 55     | 21.46%  |
| WDC                          | 16        | 17     | 7.31%   |
| Toshiba                      | 14        | 16     | 6.39%   |
| Seagate                      | 14        | 14     | 6.39%   |
| Sandisk                      | 14        | 14     | 6.39%   |
| SK hynix                     | 13        | 13     | 5.94%   |
| Kingston                     | 13        | 13     | 5.94%   |
| Intel                        | 13        | 13     | 5.94%   |
| Micron Technology            | 9         | 9      | 4.11%   |
| Crucial                      | 8         | 8      | 3.65%   |
| Phison Electronics           | 6         | 6      | 2.74%   |
| Micron/Crucial Technology    | 6         | 6      | 2.74%   |
| HGST                         | 5         | 5      | 2.28%   |
| KIOXIA                       | 4         | 4      | 1.83%   |
| Hitachi                      | 4         | 5      | 1.83%   |
| China                        | 4         | 4      | 1.83%   |
| Apple                        | 4         | 5      | 1.83%   |
| Unknown                      | 3         | 3      | 1.37%   |
| LITEON                       | 2         | 2      | 0.91%   |
| Kingston Technology Company  | 2         | 2      | 0.91%   |
| HS-SSD-C100                  | 2         | 2      | 0.91%   |
| Unknown                      | 2         | 2      | 0.91%   |
| Union Memory                 | 1         | 1      | 0.46%   |
| Team                         | 1         | 1      | 0.46%   |
| T-FORCE                      | 1         | 1      | 0.46%   |
| Solid State Storage          | 1         | 1      | 0.46%   |
| Silicon Motion               | 1         | 1      | 0.46%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.46%   |
| Ramsta                       | 1         | 1      | 0.46%   |
| PNY                          | 1         | 1      | 0.46%   |
| Mushkin                      | 1         | 1      | 0.46%   |
| HGST HTS                     | 1         | 1      | 0.46%   |
| Fujitsu                      | 1         | 1      | 0.46%   |
| Emtec                        | 1         | 1      | 0.46%   |
| ADATA Technology             | 1         | 1      | 0.46%   |
| A-DATA Technology            | 1         | 1      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 7         | 3.07%   |
| Kingston SA400S37240G 240GB SSD                     | 5         | 2.19%   |
| Sandisk WD Blue SN550 NVMe SSD 256GB                | 4         | 1.75%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 4         | 1.75%   |
| Intel SSDPEKNU512GZ 512GB                           | 4         | 1.75%   |
| Toshiba MQ04ABF100 1TB                              | 3         | 1.32%   |
| SK hynix BC511 512GB                                | 3         | 1.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 1.32%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 1TB      | 3         | 1.32%   |
| Samsung SSD 980 1TB                                 | 3         | 1.32%   |
| Samsung NVMe SSD Controller SM951/PM951 128GB       | 3         | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 3         | 1.32%   |
| Samsung MZALQ512HBLU-00BL2 512GB                    | 3         | 1.32%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                      | 3         | 1.32%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 2         | 0.88%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 0.88%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 0.88%   |
| Toshiba MQ01ABD050 500GB                            | 2         | 0.88%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 2         | 0.88%   |
| Seagate ST500LT012-1DG142 500GB                     | 2         | 0.88%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB     | 2         | 0.88%   |
| Samsung SSD 850 EVO 250GB                           | 2         | 0.88%   |
| Samsung NVMe SSD Drive 1024GB                       | 2         | 0.88%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 2         | 0.88%   |
| Samsung MZVLQ1T0HBLB-00B00 1024GB                   | 2         | 0.88%   |
| Phison PS5013 E13 NVMe Controller 256GB             | 2         | 0.88%   |
| Phison E12 NVMe Controller 256GB                    | 2         | 0.88%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                       | 2         | 0.88%   |
| Micron 2210_MTFDHBA512QFD 512GB                     | 2         | 0.88%   |
| Kingston NVMe SSD Drive 512GB                       | 2         | 0.88%   |
| Intel SSD 660P Series 512GB                         | 2         | 0.88%   |
| HS-SSD-C100 120G                                    | 2         | 0.88%   |
| Hitachi HTS547575A9E384 752GB                       | 2         | 0.88%   |
| Crucial CT500MX500SSD1 500GB                        | 2         | 0.88%   |
| China SATA SSD 120GB                                | 2         | 0.88%   |
| Unknown                                             | 2         | 0.88%   |
| WDC WDS500G3X0C-00SJG0 500GB                        | 1         | 0.44%   |
| WDC WDS100T2B0C-00PXH0 1TB                          | 1         | 0.44%   |
| WDC WDS100T1R0B-68A4Z0 1TB SSD                      | 1         | 0.44%   |
| WDC WD5000LPCX-24VHAT0 500GB                        | 1         | 0.44%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 14        | 14     | 29.17%  |
| Toshiba  | 11        | 12     | 22.92%  |
| WDC      | 10        | 11     | 20.83%  |
| HGST     | 5         | 5      | 10.42%  |
| Hitachi  | 4         | 5      | 8.33%   |
| Unknown  | 1         | 1      | 2.08%   |
| HGST HTS | 1         | 1      | 2.08%   |
| Fujitsu  | 1         | 1      | 2.08%   |
| Apple    | 1         | 1      | 2.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 13        | 14     | 24.07%  |
| Kingston            | 7         | 7      | 12.96%  |
| Crucial             | 7         | 7      | 12.96%  |
| SK hynix            | 4         | 4      | 7.41%   |
| China               | 4         | 4      | 7.41%   |
| SanDisk             | 3         | 3      | 5.56%   |
| Micron Technology   | 2         | 2      | 3.7%    |
| LITEON              | 2         | 2      | 3.7%    |
| Intel               | 2         | 2      | 3.7%    |
| Apple               | 2         | 2      | 3.7%    |
| WDC                 | 1         | 1      | 1.85%   |
| Toshiba             | 1         | 1      | 1.85%   |
| Team                | 1         | 1      | 1.85%   |
| Ramsta              | 1         | 1      | 1.85%   |
| PNY                 | 1         | 1      | 1.85%   |
| Mushkin             | 1         | 1      | 1.85%   |
| Emtec               | 1         | 1      | 1.85%   |
| A-DATA Technology   | 1         | 1      | 1.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 97        | 119    | 47.78%  |
| SSD     | 52        | 55     | 25.62%  |
| HDD     | 47        | 51     | 23.15%  |
| Unknown | 5         | 5      | 2.46%   |
| MMC     | 2         | 2      | 0.99%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 97        | 119    | 49.49%  |
| SATA | 91        | 105    | 46.43%  |
| SAS  | 6         | 6      | 3.06%   |
| MMC  | 2         | 2      | 1.02%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 59        | 63     | 59%     |
| 0.51-1.0   | 37        | 38     | 37%     |
| 1.01-2.0   | 3         | 4      | 3%      |
| 4.01-10.0  | 1         | 1      | 1%      |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 47        | 26.86%  |
| 101-250        | 39        | 22.29%  |
| 251-500        | 38        | 21.71%  |
| 1001-2000      | 22        | 12.57%  |
| Unknown        | 9         | 5.14%   |
| More than 3000 | 6         | 3.43%   |
| 21-50          | 5         | 2.86%   |
| 51-100         | 5         | 2.86%   |
| 2001-3000      | 3         | 1.71%   |
| 1-20           | 1         | 0.57%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 52        | 29.38%  |
| 1-20           | 39        | 22.03%  |
| 101-250        | 23        | 12.99%  |
| 251-500        | 22        | 12.43%  |
| 51-100         | 18        | 10.17%  |
| 501-1000       | 9         | 5.08%   |
| Unknown        | 9         | 5.08%   |
| 1001-2000      | 3         | 1.69%   |
| More than 3000 | 1         | 0.56%   |
| 2001-3000      | 1         | 0.56%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Notebooks | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| SK hynix HFS128G39TND-N210A 128GB SSD | 1         | 1      | 25%     |
| Ramsta SSD S800 240GB                 | 1         | 1      | 25%     |
| Hitachi HTS54323 320GB                | 1         | 1      | 25%     |
| HGST HTS721010A9E630 1TB              | 1         | 1      | 25%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| SK hynix | 1         | 1      | 25%     |
| Ramsta   | 1         | 1      | 25%     |
| Hitachi  | 1         | 1      | 25%     |
| HGST     | 1         | 1      | 25%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Hitachi | 1         | 1      | 50%     |
| HGST    | 1         | 1      | 50%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 2         | 2      | 50%     |
| HDD  | 2         | 2      | 50%     |

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
| Detected | 141       | 179    | 77.9%   |
| Works    | 37        | 49     | 20.44%  |
| Malfunc  | 3         | 4      | 1.66%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 107       | 44.77%  |
| Samsung Electronics            | 36        | 15.06%  |
| AMD                            | 29        | 12.13%  |
| SanDisk                        | 15        | 6.28%   |
| SK hynix                       | 9         | 3.77%   |
| Kingston Technology Company    | 8         | 3.35%   |
| Micron/Crucial Technology      | 7         | 2.93%   |
| Micron Technology              | 7         | 2.93%   |
| Phison Electronics             | 6         | 2.51%   |
| KIOXIA                         | 4         | 1.67%   |
| Toshiba America Info Systems   | 2         | 0.84%   |
| Nvidia                         | 2         | 0.84%   |
| Union Memory (Shenzhen)        | 1         | 0.42%   |
| Solid State Storage Technology | 1         | 0.42%   |
| Silicon Motion                 | 1         | 0.42%   |
| Shenzhen Longsys Electronics   | 1         | 0.42%   |
| Marvell Technology Group       | 1         | 0.42%   |
| Apple                          | 1         | 0.42%   |
| ADATA Technology               | 1         | 0.42%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 29        | 11.6%   |
| Samsung NVMe SSD Controller 980                                                | 13        | 5.2%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 12        | 4.8%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 12        | 4.8%    |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 4%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 4%      |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 9         | 3.6%    |
| Micron NVMe Storage Controller                                                 | 7         | 2.8%    |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 2.8%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 7         | 2.8%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 7         | 2.8%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 2.4%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 2.4%    |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 2.4%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 5         | 2%      |
| Intel Non-Volatile memory controller                                           | 5         | 2%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 2%      |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 4         | 1.6%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4         | 1.6%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 4         | 1.6%    |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 1.6%    |
| Intel SSD 660P Series                                                          | 4         | 1.6%    |
| SK hynix BC511                                                                 | 3         | 1.2%    |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 3         | 1.2%    |
| Samsung NVMe SSD Controller SM951/PM951                                        | 3         | 1.2%    |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 1.2%    |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 1.2%    |
| SanDisk Non-Volatile memory controller                                         | 2         | 0.8%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 2         | 0.8%    |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 0.8%    |
| Phison E12 NVMe Controller                                                     | 2         | 0.8%    |
| Nvidia MCP79 AHCI Controller                                                   | 2         | 0.8%    |
| Micron/Crucial NVMe Storage Controller                                         | 2         | 0.8%    |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 0.8%    |
| Kingston Company A2000 NVMe SSD                                                | 2         | 0.8%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 0.8%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 0.8%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 0.8%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 0.8%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 2         | 0.8%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 117       | 50.21%  |
| NVMe | 97        | 41.63%  |
| RAID | 18        | 7.73%   |
| IDE  | 1         | 0.43%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 123       | 71.51%  |
| AMD    | 49        | 28.49%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 5         | 2.91%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 5         | 2.91%   |
| AMD Ryzen 5 4600H with Radeon Graphics          | 5         | 2.91%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 4         | 2.33%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 4         | 2.33%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 4         | 2.33%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 4         | 2.33%   |
| AMD Ryzen 7 5800H with Radeon Graphics          | 4         | 2.33%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 3         | 1.74%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 3         | 1.74%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 3         | 1.74%   |
| Intel Core i3-4030U CPU @ 1.90GHz               | 3         | 1.74%   |
| Intel 12th Gen Core i7-12700H                   | 3         | 1.74%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 3         | 1.74%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 3         | 1.74%   |
| Intel Pentium CPU B960 @ 2.20GHz                | 2         | 1.16%   |
| Intel Core i7-8850H CPU @ 2.60GHz               | 2         | 1.16%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz              | 2         | 1.16%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 2         | 1.16%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 1.16%   |
| Intel 12th Gen Core i7-12650H                   | 2         | 1.16%   |
| Intel 12th Gen Core i5-1240P                    | 2         | 1.16%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 1.16%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 2         | 1.16%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz         | 2         | 1.16%   |
| AMD Ryzen 9 5900HS with Radeon Graphics         | 2         | 1.16%   |
| AMD Ryzen 7 6800H with Radeon Graphics          | 2         | 1.16%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 1.16%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 2         | 1.16%   |
| AMD Ryzen 5 5600U with Radeon Graphics          | 2         | 1.16%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx   | 2         | 1.16%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 1.16%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 2         | 1.16%   |
| AMD A10-8700P Radeon R6, 10 Compute Cores 4C+6G | 2         | 1.16%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz     | 1         | 0.58%   |
| Intel Pentium CPU N4200 @ 1.10GHz               | 1         | 0.58%   |
| Intel Core i7-9850H CPU @ 2.60GHz               | 1         | 0.58%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 1         | 0.58%   |
| Intel Core i7-8565U CPU @ 1.80GHz               | 1         | 0.58%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 1         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 49        | 28.49%  |
| Intel Core i5           | 29        | 16.86%  |
| Other                   | 21        | 12.21%  |
| AMD Ryzen 5             | 20        | 11.63%  |
| AMD Ryzen 7             | 18        | 10.47%  |
| Intel Core i3           | 10        | 5.81%   |
| Intel Celeron           | 6         | 3.49%   |
| AMD Ryzen 9             | 4         | 2.33%   |
| Intel Pentium           | 3         | 1.74%   |
| Intel Core 2 Duo        | 3         | 1.74%   |
| AMD A10                 | 2         | 1.16%   |
| Intel Pentium Dual-Core | 1         | 0.58%   |
| Intel Core 2 Extreme    | 1         | 0.58%   |
| Intel Atom              | 1         | 0.58%   |
| AMD Ryzen 3             | 1         | 0.58%   |
| AMD FX                  | 1         | 0.58%   |
| AMD E                   | 1         | 0.58%   |
| AMD A6                  | 1         | 0.58%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 57        | 33.14%  |
| 2      | 55        | 31.98%  |
| 8      | 26        | 15.12%  |
| 6      | 26        | 15.12%  |
| 14     | 3         | 1.74%   |
| 12     | 3         | 1.74%   |
| 10     | 2         | 1.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 172       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 155       | 90.12%  |
| 1      | 17        | 9.88%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 172       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0xa0652    | 12        | 6.94%   |
| 0x0a50000c | 12        | 6.94%   |
| 0x40651    | 11        | 6.36%   |
| Unknown    | 11        | 6.36%   |
| 0x906ea    | 8         | 4.62%   |
| 0x906a3    | 8         | 4.62%   |
| 0x306a9    | 8         | 4.62%   |
| 0x206a7    | 8         | 4.62%   |
| 0x906e9    | 7         | 4.05%   |
| 0x806c1    | 7         | 4.05%   |
| 0x08608103 | 6         | 3.47%   |
| 0x806d1    | 5         | 2.89%   |
| 0x506e3    | 5         | 2.89%   |
| 0x306c3    | 5         | 2.89%   |
| 0x08108109 | 5         | 2.89%   |
| 0x806e9    | 4         | 2.31%   |
| 0x406e3    | 4         | 2.31%   |
| 0x08600106 | 4         | 2.31%   |
| 0x08600104 | 4         | 2.31%   |
| 0x806ea    | 3         | 1.73%   |
| 0x10676    | 3         | 1.73%   |
| 0x806ec    | 2         | 1.16%   |
| 0x706e5    | 2         | 1.16%   |
| 0x306d4    | 2         | 1.16%   |
| 0x30678    | 2         | 1.16%   |
| 0x1067a    | 2         | 1.16%   |
| 0x0a50000d | 2         | 1.16%   |
| 0x0a404102 | 2         | 1.16%   |
| 0x0a404101 | 2         | 1.16%   |
| 0x08108102 | 2         | 1.16%   |
| 0x06006110 | 2         | 1.16%   |
| 0xa0655    | 1         | 0.58%   |
| 0x906ed    | 1         | 0.58%   |
| 0x706a1    | 1         | 0.58%   |
| 0x506c9    | 1         | 0.58%   |
| 0x30661    | 1         | 0.58%   |
| 0x20655    | 1         | 0.58%   |
| 0x20652    | 1         | 0.58%   |
| 0x08900201 | 1         | 0.58%   |
| 0x08101007 | 1         | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 28        | 16.28%  |
| Haswell          | 19        | 11.05%  |
| Zen 3            | 14        | 8.14%   |
| CometLake        | 13        | 7.56%   |
| Unknown          | 11        | 6.4%    |
| Skylake          | 10        | 5.81%   |
| Zen 2            | 9         | 5.23%   |
| SandyBridge      | 8         | 4.65%   |
| IvyBridge        | 8         | 4.65%   |
| Alderlake Hybrid | 8         | 4.65%   |
| Zen+             | 7         | 4.07%   |
| TigerLake        | 7         | 4.07%   |
| Icelake          | 7         | 4.07%   |
| Penryn           | 5         | 2.91%   |
| Zen              | 3         | 1.74%   |
| Westmere         | 2         | 1.16%   |
| Silvermont       | 2         | 1.16%   |
| Goldmont plus    | 2         | 1.16%   |
| Excavator        | 2         | 1.16%   |
| Broadwell        | 2         | 1.16%   |
| Steamroller      | 1         | 0.58%   |
| Puma             | 1         | 0.58%   |
| Goldmont         | 1         | 0.58%   |
| Bonnell          | 1         | 0.58%   |
| Bobcat           | 1         | 0.58%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 109       | 41.92%  |
| Nvidia | 90        | 34.62%  |
| AMD    | 61        | 23.46%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Haswell-ULT Integrated Graphics Controller                              | 13        | 4.87%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                  | 12        | 4.49%   |
| Intel CometLake-H GT2 [UHD Graphics]                                          | 11        | 4.12%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                     | 11        | 4.12%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                               | 9         | 3.37%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                       | 7         | 2.62%   |
| AMD Renoir                                                                    | 7         | 2.62%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]          | 7         | 2.62%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                    | 6         | 2.25%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                     | 6         | 2.25%   |
| Intel Alder Lake-P Integrated Graphics Controller                             | 6         | 2.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                   | 6         | 2.25%   |
| Intel 3rd Gen Core processor Graphics Controller                              | 6         | 2.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller     | 6         | 2.25%   |
| AMD Lucienne                                                                  | 6         | 2.25%   |
| Nvidia TU117M                                                                 | 5         | 1.87%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                       | 5         | 1.87%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                          | 5         | 1.87%   |
| Intel HD Graphics 630                                                         | 5         | 1.87%   |
| Intel HD Graphics 530                                                         | 5         | 1.87%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                               | 4         | 1.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                           | 4         | 1.5%    |
| AMD Rembrandt [Radeon 680M]                                                   | 4         | 1.5%    |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                       | 3         | 1.12%   |
| Nvidia GM107M [GeForce GTX 960M]                                              | 3         | 1.12%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                    | 3         | 1.12%   |
| Intel UHD Graphics 620                                                        | 3         | 1.12%   |
| Intel HD Graphics 620                                                         | 3         | 1.12%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                       | 3         | 1.12%   |
| Nvidia TU117M [GeForce MX450]                                                 | 2         | 0.75%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                       | 2         | 0.75%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                               | 2         | 0.75%   |
| Nvidia C79 [GeForce 9400M]                                                    | 2         | 0.75%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                        | 2         | 0.75%   |
| Intel HD Graphics 5500                                                        | 2         | 0.75%   |
| Intel GeminiLake [UHD Graphics 600]                                           | 2         | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                  | 2         | 0.75%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                         | 2         | 0.75%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                           | 2         | 0.75%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile] | 2         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel + Nvidia     | 61        | 35.47%  |
| 1 x Intel          | 38        | 22.09%  |
| 1 x AMD            | 30        | 17.44%  |
| AMD + Nvidia       | 17        | 9.88%   |
| 1 x Nvidia         | 11        | 6.4%    |
| Intel + AMD        | 8         | 4.65%   |
| 2 x AMD            | 6         | 3.49%   |
| Intel + 2 x Nvidia | 1         | 0.58%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 102       | 58.96%  |
| Proprietary | 70        | 40.46%  |
| Unknown     | 1         | 0.58%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 97        | 55.75%  |
| 0.01-0.5   | 29        | 16.67%  |
| 1.01-2.0   | 18        | 10.34%  |
| 0.51-1.0   | 12        | 6.9%    |
| 3.01-4.0   | 6         | 3.45%   |
| 7.01-8.0   | 5         | 2.87%   |
| 5.01-6.0   | 5         | 2.87%   |
| 8.01-16.0  | 2         | 1.15%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 43        | 21.72%  |
| BOE                     | 27        | 13.64%  |
| Chimei Innolux          | 24        | 12.12%  |
| LG Display              | 23        | 11.62%  |
| Samsung Electronics     | 20        | 10.1%   |
| PANDA                   | 12        | 6.06%   |
| Apple                   | 7         | 3.54%   |
| Sharp                   | 6         | 3.03%   |
| Goldstar                | 5         | 2.53%   |
| ViewSonic               | 3         | 1.52%   |
| MSI                     | 3         | 1.52%   |
| Dell                    | 3         | 1.52%   |
| InfoVision              | 2         | 1.01%   |
| Hewlett-Packard         | 2         | 1.01%   |
| Eizo                    | 2         | 1.01%   |
| Chi Mei Optoelectronics | 2         | 1.01%   |
| AOC                     | 2         | 1.01%   |
| Acer                    | 2         | 1.01%   |
| ___                     | 1         | 0.51%   |
| Vizio                   | 1         | 0.51%   |
| Valve                   | 1         | 0.51%   |
| Unknown                 | 1         | 0.51%   |
| Sony                    | 1         | 0.51%   |
| Philips                 | 1         | 0.51%   |
| MLT                     | 1         | 0.51%   |
| Lenovo                  | 1         | 0.51%   |
| CSO                     | 1         | 0.51%   |
| CPT                     | 1         | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 2.02%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 3         | 1.52%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 3         | 1.52%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 1.52%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch         | 3         | 1.52%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch               | 2         | 1.01%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch          | 2         | 1.01%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 2         | 1.01%   |
| Eizo EV2335W ENC2293 1920x1080 510x287mm 23.0-inch                    | 2         | 1.01%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 1.01%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 1.01%   |
| BOE LCD Monitor BOE0998 1920x1080 344x194mm 15.5-inch                 | 2         | 1.01%   |
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch        | 2         | 1.01%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch        | 2         | 1.01%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.01%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 1.01%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 2         | 1.01%   |
| ___ LCD TV ___9000 1360x768                                           | 1         | 0.51%   |
| Vizio E241i-A1 VIZ1005 1920x1080 521x293mm 23.5-inch                  | 1         | 0.51%   |
| ViewSonic VX2768-2KP VSC0A3B 2560x1440 597x336mm 27.0-inch            | 1         | 0.51%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch         | 1         | 0.51%   |
| ViewSonic VA2446 SERIES VSC732E 1920x1080 521x293mm 23.5-inch         | 1         | 0.51%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.51%   |
| Unknown LCDTV 9000 1360x768 1600x900mm 72.3-inch                      | 1         | 0.51%   |
| Sony TV SNY1B02 1360x768                                              | 1         | 0.51%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch               | 1         | 0.51%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch               | 1         | 0.51%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch               | 1         | 0.51%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 0.51%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.51%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.51%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch     | 1         | 0.51%   |
| Samsung Electronics SMB2440MH SAM06DD 1920x1080                       | 1         | 0.51%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch     | 1         | 0.51%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 331x207mm 15.4-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch  | 1         | 0.51%   |
| Samsung Electronics LCD Monitor SDC4852 3840x2160 344x194mm 15.5-inch | 1         | 0.51%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 96        | 52.75%  |
| 1366x768 (WXGA)    | 39        | 21.43%  |
| 3840x2160 (4K)     | 8         | 4.4%    |
| 1920x1200 (WUXGA)  | 6         | 3.3%    |
| 2560x1440 (QHD)    | 5         | 2.75%   |
| 2880x1800          | 4         | 2.2%    |
| 2560x1600          | 4         | 2.2%    |
| 1440x900 (WXGA+)   | 4         | 2.2%    |
| 1280x800 (WXGA)    | 3         | 1.65%   |
| 2560x1080          | 2         | 1.1%    |
| 2240x1400          | 2         | 1.1%    |
| 1360x768           | 2         | 1.1%    |
| 800x1280           | 1         | 0.55%   |
| 3840x2400          | 1         | 0.55%   |
| 3200x1800 (QHD+)   | 1         | 0.55%   |
| 2520x1680          | 1         | 0.55%   |
| 1680x1050 (WSXGA+) | 1         | 0.55%   |
| 1600x900 (HD+)     | 1         | 0.55%   |
| 1600x2560          | 1         | 0.55%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 98        | 49.49%  |
| 13      | 19        | 9.6%    |
| 17      | 18        | 9.09%   |
| 14      | 17        | 8.59%   |
| 23      | 8         | 4.04%   |
| 31      | 6         | 3.03%   |
| 27      | 5         | 2.53%   |
| 16      | 5         | 2.53%   |
| 24      | 4         | 2.02%   |
| 72      | 2         | 1.01%   |
| 34      | 2         | 1.01%   |
| 18      | 2         | 1.01%   |
| Unknown | 2         | 1.01%   |
| 84      | 1         | 0.51%   |
| 48      | 1         | 0.51%   |
| 26      | 1         | 0.51%   |
| 21      | 1         | 0.51%   |
| 20      | 1         | 0.51%   |
| 12      | 1         | 0.51%   |
| 11      | 1         | 0.51%   |
| 10      | 1         | 0.51%   |
| 8       | 1         | 0.51%   |
| 7       | 1         | 0.51%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 130       | 65.99%  |
| 351-400     | 18        | 9.14%   |
| 501-600     | 16        | 8.12%   |
| 201-300     | 12        | 6.09%   |
| 601-700     | 7         | 3.55%   |
| 401-500     | 4         | 2.03%   |
| 1501-2000   | 3         | 1.52%   |
| 701-800     | 2         | 1.02%   |
| Unknown     | 2         | 1.02%   |
| 101-200     | 1         | 0.51%   |
| 1001-1500   | 1         | 0.51%   |
| 1-100       | 1         | 0.51%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 143       | 83.14%  |
| 16/10 | 24        | 13.95%  |
| 21/9  | 2         | 1.16%   |
| 3/2   | 1         | 0.58%   |
| 0.67  | 1         | 0.58%   |
| 0.62  | 1         | 0.58%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 98        | 49.75%  |
| 81-90          | 31        | 15.74%  |
| 121-130        | 16        | 8.12%   |
| 201-250        | 9         | 4.57%   |
| 351-500        | 8         | 4.06%   |
| 71-80          | 5         | 2.54%   |
| 301-350        | 5         | 2.54%   |
| 111-120        | 5         | 2.54%   |
| More than 1000 | 4         | 2.03%   |
| 251-300        | 4         | 2.03%   |
| 1-40           | 2         | 1.02%   |
| 141-150        | 2         | 1.02%   |
| 131-140        | 2         | 1.02%   |
| Unknown        | 2         | 1.02%   |
| 61-70          | 1         | 0.51%   |
| 51-60          | 1         | 0.51%   |
| 41-50          | 1         | 0.51%   |
| 151-200        | 1         | 0.51%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 96        | 49.74%  |
| 101-120       | 40        | 20.73%  |
| 51-100        | 27        | 13.99%  |
| 161-240       | 15        | 7.77%   |
| More than 240 | 10        | 5.18%   |
| 1-50          | 3         | 1.55%   |
| Unknown       | 2         | 1.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 137       | 79.65%  |
| 2     | 26        | 15.12%  |
| 0     | 5         | 2.91%   |
| 3     | 4         | 2.33%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 102       | 36.3%   |
| Intel                           | 94        | 33.45%  |
| Qualcomm Atheros                | 28        | 9.96%   |
| Broadcom                        | 19        | 6.76%   |
| MediaTek                        | 11        | 3.91%   |
| ASIX Electronics                | 4         | 1.42%   |
| Samsung Electronics             | 3         | 1.07%   |
| Broadcom Limited                | 3         | 1.07%   |
| Xiaomi                          | 2         | 0.71%   |
| Qualcomm                        | 2         | 0.71%   |
| Nvidia                          | 2         | 0.71%   |
| Sierra Wireless                 | 1         | 0.36%   |
| Ralink                          | 1         | 0.36%   |
| Qualcomm Atheros Communications | 1         | 0.36%   |
| Panasonic (Matsushita)          | 1         | 0.36%   |
| Motorola PCS                    | 1         | 0.36%   |
| Marvell Technology Group        | 1         | 0.36%   |
| Lenovo                          | 1         | 0.36%   |
| JMicron Technology              | 1         | 0.36%   |
| Google                          | 1         | 0.36%   |
| ASUSTek Computer                | 1         | 0.36%   |
| Afatech                         | 1         | 0.36%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 76        | 23.6%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 12        | 3.73%   |
| Intel Wi-Fi 6 AX200                                               | 11        | 3.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 10        | 3.11%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 2.48%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 8         | 2.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8         | 2.48%   |
| Intel Wireless 7260                                               | 7         | 2.17%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 7         | 2.17%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 6         | 1.86%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 1.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.86%   |
| Intel Wireless 8265 / 8275                                        | 6         | 1.86%   |
| Intel Wireless 8260                                               | 6         | 1.86%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 1.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 1.55%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.55%   |
| Intel Wireless 7265                                               | 4         | 1.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 3         | 0.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.93%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.93%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.93%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.93%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.93%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 0.93%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.93%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.93%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 2         | 0.62%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.62%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.62%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.62%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.62%   |
| Intel Wireless-AC 9260                                            | 2         | 0.62%   |
| Intel Wireless 3160                                               | 2         | 0.62%   |
| Intel WiFi Link 5100                                              | 2         | 0.62%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.62%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.62%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.62%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.62%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 91        | 52.3%   |
| Realtek Semiconductor           | 26        | 14.94%  |
| Qualcomm Atheros                | 23        | 13.22%  |
| Broadcom                        | 16        | 9.2%    |
| MediaTek                        | 11        | 6.32%   |
| Broadcom Limited                | 2         | 1.15%   |
| Sierra Wireless                 | 1         | 0.57%   |
| Ralink                          | 1         | 0.57%   |
| Qualcomm Atheros Communications | 1         | 0.57%   |
| Panasonic (Matsushita)          | 1         | 0.57%   |
| ASUSTek Computer                | 1         | 0.57%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Comet Lake PCH CNVi WiFi                                          | 12        | 6.9%    |
| Intel Wi-Fi 6 AX200                                                     | 11        | 6.32%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 5.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 8         | 4.6%    |
| Intel Cannon Lake PCH CNVi WiFi                                         | 8         | 4.6%    |
| Intel Wireless 7260                                                     | 7         | 4.02%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 7         | 4.02%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 6         | 3.45%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 3.45%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 3.45%   |
| Intel Wireless 8265 / 8275                                              | 6         | 3.45%   |
| Intel Wireless 8260                                                     | 6         | 3.45%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 3.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 2.87%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 2.87%   |
| Intel Wireless 7265                                                     | 4         | 2.3%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 3         | 1.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.72%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 1.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 1.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.72%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 1.15%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.15%   |
| Intel Wireless 3160                                                     | 2         | 1.15%   |
| Intel WiFi Link 5100                                                    | 2         | 1.15%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 1.15%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.15%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 1.15%   |
| Sierra Wireless EM7455                                                  | 1         | 0.57%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 1         | 0.57%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1         | 0.57%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.57%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.57%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.57%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.57%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.57%   |
| Panasonic (Matsushita) DY-WL10 802.11abgn Adapter [Broadcom BCM4323]    | 1         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 92        | 63.45%  |
| Intel                    | 23        | 15.86%  |
| Qualcomm Atheros         | 7         | 4.83%   |
| Broadcom                 | 5         | 3.45%   |
| ASIX Electronics         | 4         | 2.76%   |
| Xiaomi                   | 2         | 1.38%   |
| Samsung Electronics      | 2         | 1.38%   |
| Qualcomm                 | 2         | 1.38%   |
| Nvidia                   | 2         | 1.38%   |
| Motorola PCS             | 1         | 0.69%   |
| Marvell Technology Group | 1         | 0.69%   |
| Lenovo                   | 1         | 0.69%   |
| JMicron Technology       | 1         | 0.69%   |
| Google                   | 1         | 0.69%   |
| Broadcom Limited         | 1         | 0.69%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 76        | 52.05%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 5.48%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.05%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 2.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 2.05%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 2.05%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.37%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 1.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.37%   |
| Nvidia MCP79 Ethernet                                             | 2         | 1.37%   |
| Intel I211 Gigabit Network Connection                             | 2         | 1.37%   |
| Intel Ethernet Connection I217-V                                  | 2         | 1.37%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.37%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.37%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.68%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.68%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.68%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.68%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.68%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.68%   |
| Qualcomm Fairphone 4 5G                                           | 1         | 0.68%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.68%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.68%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.68%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.68%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.68%   |
| Qualcomm Android                                                  | 1         | 0.68%   |
| Motorola PCS moto g pure                                          | 1         | 0.68%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.68%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.68%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.68%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.68%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.68%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.68%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.68%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 0.68%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 170       | 55.02%  |
| Ethernet | 137       | 44.34%  |
| Modem    | 1         | 0.32%   |
| Unknown  | 1         | 0.32%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 133       | 74.3%   |
| Ethernet | 46        | 25.7%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 127       | 73.84%  |
| 1     | 43        | 25%     |
| 0     | 2         | 1.16%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 127       | 73.41%  |
| Yes  | 46        | 26.59%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 87        | 56.49%  |
| Realtek Semiconductor           | 16        | 10.39%  |
| Qualcomm Atheros Communications | 9         | 5.84%   |
| Lite-On Technology              | 9         | 5.84%   |
| IMC Networks                    | 9         | 5.84%   |
| Foxconn / Hon Hai               | 7         | 4.55%   |
| Broadcom                        | 6         | 3.9%    |
| Apple                           | 6         | 3.9%    |
| Toshiba                         | 1         | 0.65%   |
| Realtek                         | 1         | 0.65%   |
| Ralink                          | 1         | 0.65%   |
| MediaTek                        | 1         | 0.65%   |
| Foxconn International           | 1         | 0.65%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 31        | 20.13%  |
| Intel AX201 Bluetooth                             | 21        | 13.64%  |
| Realtek Bluetooth Radio                           | 14        | 9.09%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 11        | 7.14%   |
| Intel AX200 Bluetooth                             | 11        | 7.14%   |
| Intel Bluetooth Device                            | 5         | 3.25%   |
| Apple Bluetooth Host Controller                   | 5         | 3.25%   |
| Qualcomm Atheros  Bluetooth Device                | 4         | 2.6%    |
| IMC Networks Wireless_Device                      | 4         | 2.6%    |
| IMC Networks Bluetooth Radio                      | 4         | 2.6%    |
| Intel AX210 Bluetooth                             | 3         | 1.95%   |
| Foxconn / Hon Hai Wireless_Device                 | 3         | 1.95%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 2         | 1.3%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 2         | 1.3%    |
| Lite-On Bluetooth Device                          | 2         | 1.3%    |
| Lite-On Atheros AR3012 Bluetooth                  | 2         | 1.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 2         | 1.3%    |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth     | 2         | 1.3%    |
| Toshiba Askey Bluetooth Module                    | 1         | 0.65%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter           | 1         | 0.65%   |
| Realtek  Bluetooth 4.2 Adapter                    | 1         | 0.65%   |
| Realtek Bluetooth Radio                           | 1         | 0.65%   |
| Ralink RT3290 Bluetooth                           | 1         | 0.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0            | 1         | 0.65%   |
| Qualcomm Atheros Bluetooth (AR3011)               | 1         | 0.65%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 1         | 0.65%   |
| MediaTek Wireless_Device                          | 1         | 0.65%   |
| Lite-On Wireless_Device                           | 1         | 0.65%   |
| Lite-On Bluetooth Radio                           | 1         | 0.65%   |
| Lite-On BCM43142A0                                | 1         | 0.65%   |
| Intel Wireless-AC 3168 Bluetooth                  | 1         | 0.65%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 1         | 0.65%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 0.65%   |
| IMC Networks Bluetooth Device                     | 1         | 0.65%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 0.65%   |
| Foxconn / Hon Hai BT                              | 1         | 0.65%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth   | 1         | 0.65%   |
| Broadcom HP Portable SoftSailing                  | 1         | 0.65%   |
| Broadcom HP Portable Bumble Bee                   | 1         | 0.65%   |
| Broadcom BCM43142A0 Bluetooth Device              | 1         | 0.65%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 121       | 48.02%  |
| Nvidia                 | 57        | 22.62%  |
| AMD                    | 57        | 22.62%  |
| C-Media Electronics    | 3         | 1.19%   |
| TTGK Technology        | 2         | 0.79%   |
| Sony                   | 2         | 0.79%   |
| SteelSeries ApS        | 1         | 0.4%    |
| Samsung Electronics    | 1         | 0.4%    |
| Logitech               | 1         | 0.4%    |
| Lenovo                 | 1         | 0.4%    |
| Hewlett-Packard        | 1         | 0.4%    |
| GN Netcom              | 1         | 0.4%    |
| Generalplus Technology | 1         | 0.4%    |
| Corsair                | 1         | 0.4%    |
| Blue Microphones       | 1         | 0.4%    |
| ASUSTek Computer       | 1         | 0.4%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 41        | 13.23%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 21        | 6.77%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 13        | 4.19%   |
| Intel Haswell-ULT HD Audio Controller                                      | 13        | 4.19%   |
| Intel Comet Lake PCH cAVS                                                  | 13        | 4.19%   |
| Intel 8 Series HD Audio Controller                                         | 13        | 4.19%   |
| Intel Sunrise Point-LP HD Audio                                            | 11        | 3.55%   |
| Intel Cannon Lake PCH cAVS                                                 | 11        | 3.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 3.55%   |
| Nvidia GA106 High Definition Audio Controller                              | 9         | 2.9%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 8         | 2.58%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 2.26%   |
| Intel CM238 HD Audio Controller                                            | 7         | 2.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 2.26%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 2.26%   |
| Nvidia TU106 High Definition Audio Controller                              | 6         | 1.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 6         | 1.94%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 1.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 1.61%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 1.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 1.29%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.97%   |
| Nvidia TU104 HD Audio Controller                                           | 3         | 0.97%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 0.97%   |
| Nvidia Audio device                                                        | 3         | 0.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 0.97%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 0.97%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 0.97%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 0.97%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 0.97%   |
| AMD FCH Azalia Controller                                                  | 3         | 0.97%   |
| TTGK Technology Audio                                                      | 2         | 0.65%   |
| Sony DualSense wireless controller (PS5)                                   | 2         | 0.65%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.65%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.65%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.65%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 0.65%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.65%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.65%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 0.65%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 39.22%  |
| Micron Technology   | 11        | 21.57%  |
| SK hynix            | 10        | 19.61%  |
| Unknown (ABCD)      | 2         | 3.92%   |
| Kingston            | 2         | 3.92%   |
| Transcend           | 1         | 1.96%   |
| Team                | 1         | 1.96%   |
| Nanya Technology    | 1         | 1.96%   |
| Elpida              | 1         | 1.96%   |
| Crucial             | 1         | 1.96%   |
| Corsair             | 1         | 1.96%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 5.45%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 3.64%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 3.64%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 3.64%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 3.64%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 2         | 3.64%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM 4800MT/s               | 2         | 3.64%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 3.64%   |
| Transcend RAM JM2666HSH-4G 4GB SODIMM DDR4 2667MT/s              | 1         | 1.82%   |
| Team RAM TEAMGROUP-SD4-3200 8GB SODIMM DDR4 3200MT/s             | 1         | 1.82%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 1         | 1.82%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.82%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.82%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.82%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.82%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.82%   |
| SK hynix RAM HMA851S6CJR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.82%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.82%   |
| SK hynix RAM HMA425S6AFR6N-UH 2GB SODIMM DDR4 2400MT/s           | 1         | 1.82%   |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.82%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.82%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.82%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.82%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.82%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.82%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.82%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.82%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 1.82%   |
| Samsung RAM M4 70T5663RZ3-CF7 2GB SODIMM DDR 975MT/s             | 1         | 1.82%   |
| Samsung RAM K4UBE3D4AA-MGCR 8GB SODIMM LPDDR4 4266MT/s           | 1         | 1.82%   |
| Nanya RAM M2S4G64CB8HG4N-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 1.82%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                       | 1         | 1.82%   |
| Micron RAM Module 2GB Row Of Chips 6400MT/s                      | 1         | 1.82%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.82%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.82%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 1         | 1.82%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.82%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 1.82%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 26        | 65%     |
| DDR3    | 5         | 12.5%   |
| LPDDR4  | 4         | 10%     |
| DDR5    | 3         | 7.5%    |
| DDR2    | 1         | 2.5%    |
| Unknown | 1         | 2.5%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 36        | 85.71%  |
| Row Of Chips | 6         | 14.29%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 23        | 52.27%  |
| 4096  | 9         | 20.45%  |
| 16384 | 6         | 13.64%  |
| 2048  | 4         | 9.09%   |
| 32768 | 2         | 4.55%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 15        | 34.88%  |
| 2667  | 10        | 23.26%  |
| 1600  | 4         | 9.3%    |
| 4800  | 3         | 6.98%   |
| 2400  | 3         | 6.98%   |
| 3266  | 2         | 4.65%   |
| 6400  | 1         | 2.33%   |
| 4267  | 1         | 2.33%   |
| 4266  | 1         | 2.33%   |
| 2133  | 1         | 2.33%   |
| 1333  | 1         | 2.33%   |
| 975   | 1         | 2.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                    | Notebooks | Percent |
|--------------------------|-----------|---------|
| Samsung Composite Device | 1         | 100%    |

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
| Chicony Electronics                    | 36        | 23.53%  |
| IMC Networks                           | 24        | 15.69%  |
| Acer                                   | 13        | 8.5%    |
| Sunplus Innovation Technology          | 10        | 6.54%   |
| Realtek Semiconductor                  | 8         | 5.23%   |
| Syntek                                 | 7         | 4.58%   |
| Microdia                               | 7         | 4.58%   |
| Cheng Uei Precision Industry (Foxlink) | 7         | 4.58%   |
| Quanta                                 | 6         | 3.92%   |
| Apple                                  | 6         | 3.92%   |
| Sonix Technology                       | 5         | 3.27%   |
| Suyin                                  | 4         | 2.61%   |
| Luxvisions Innotech Limited            | 4         | 2.61%   |
| Logitech                               | 4         | 2.61%   |
| Lite-On Technology                     | 4         | 2.61%   |
| Z-Star Microelectronics                | 1         | 0.65%   |
| Tobii Technology AB                    | 1         | 0.65%   |
| SunplusIT                              | 1         | 0.65%   |
| Silicon Motion                         | 1         | 0.65%   |
| Samsung Electronics                    | 1         | 0.65%   |
| Intel                                  | 1         | 0.65%   |
| Importek                               | 1         | 0.65%   |
| Goodong Industry                       | 1         | 0.65%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 12        | 7.79%   |
| Chicony Integrated Camera                           | 9         | 5.84%   |
| Chicony HD WebCam                                   | 6         | 3.9%    |
| Syntek Integrated Camera                            | 5         | 3.25%   |
| Sunplus Integrated_Webcam_HD                        | 5         | 3.25%   |
| IMC Networks Integrated Camera                      | 5         | 3.25%   |
| Microdia Integrated_Webcam_HD                       | 4         | 2.6%    |
| Acer Integrated Camera                              | 4         | 2.6%    |
| Acer HD Webcam                                      | 4         | 2.6%    |
| Sonix USB2.0 HD UVC WebCam                          | 3         | 1.95%   |
| Realtek USB Camera                                  | 3         | 1.95%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 3         | 1.95%   |
| Chicony USB 2.0 Camera                              | 3         | 1.95%   |
| Chicony HP Truevision HD                            | 3         | 1.95%   |
| Sunplus HD WebCam                                   | 2         | 1.3%    |
| Sonix USB2.0 FHD UVC WebCam                         | 2         | 1.3%    |
| Realtek Integrated_Webcam_HD                        | 2         | 1.3%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 1.3%    |
| Lite-On HP HD Webcam                                | 2         | 1.3%    |
| Lite-On HP HD Camera                                | 2         | 1.3%    |
| Chicony USB2.0 HD UVC WebCam                        | 2         | 1.3%    |
| Chicony USB2.0 Camera                               | 2         | 1.3%    |
| Chicony EasyCamera                                  | 2         | 1.3%    |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 2         | 1.3%    |
| Apple FaceTime HD Camera                            | 2         | 1.3%    |
| Apple Built-in iSight                               | 2         | 1.3%    |
| Acer Lenovo Integrated Webcam                       | 2         | 1.3%    |
| Z-Star Namuga 1.3M Webcam                           | 1         | 0.65%   |
| Tobii AB EyeChip                                    | 1         | 0.65%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.65%   |
| Syntek EasyCamera                                   | 1         | 0.65%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.65%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 0.65%   |
| Suyin HP Truevision HD                              | 1         | 0.65%   |
| Suyin HP TrueVision Full HD                         | 1         | 0.65%   |
| SunplusIT MTD camera                                | 1         | 0.65%   |
| Sunplus Laptop Integrated WebCam HD                 | 1         | 0.65%   |
| Sunplus HP HD Webcam [Fixed]                        | 1         | 0.65%   |
| Sunplus Asus Webcam                                 | 1         | 0.65%   |
| Silicon Motion 300k Pixel Camera                    | 1         | 0.65%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 10        | 37.04%  |
| Synaptics                          | 7         | 25.93%  |
| Shenzhen Goodix Technology         | 4         | 14.81%  |
| Elan Microelectronics              | 4         | 14.81%  |
| Realtek USB2.0 Finger Print Bridge | 2         | 7.41%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Notebooks | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 6         | 22.22%  |
| Shenzhen Goodix  Fingerprint Device                             | 3         | 11.11%  |
| Validity Sensors VFS 5011 fingerprint sensor                    | 2         | 7.41%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 7.41%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 7.41%   |
| Elan ELAN:Fingerprint                                           | 2         | 7.41%   |
| Elan ELAN:ARM-M4                                                | 2         | 7.41%   |
| Validity Sensors Synaptics WBDI                                 | 1         | 3.7%    |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 3.7%    |
| Synaptics WBDI Device                                           | 1         | 3.7%    |
| Synaptics UWP WBDI Device                                       | 1         | 3.7%    |
| Synaptics  WBDI                                                 | 1         | 3.7%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint      | 1         | 3.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 1         | 3.7%    |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 3.7%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 2         | 66.67%  |
| Alcor Micro | 1         | 33.33%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 33.33%  |
| Broadcom 5880                                                                | 1         | 33.33%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 33.33%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 112       | 64.37%  |
| 1     | 46        | 26.44%  |
| 2     | 15        | 8.62%   |
| 3     | 1         | 0.57%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 27        | 33.75%  |
| Graphics card            | 20        | 25%     |
| Multimedia controller    | 15        | 18.75%  |
| Net/wireless             | 13        | 16.25%  |
| Bluetooth                | 2         | 2.5%    |
| Modem                    | 1         | 1.25%   |
| Communication controller | 1         | 1.25%   |
| Chipcard                 | 1         | 1.25%   |

