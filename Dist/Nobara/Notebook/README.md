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

Total: 241

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | [b54238dc33](https://linux-hardware.org/?probe=b54238dc33) | May 01, 2023 |
| HP            | Unknown                     | [bba45b8ff0](https://linux-hardware.org/?probe=bba45b8ff0) | Apr 27, 2023 |
| Lenovo        | ThinkPad Edge E540 20C6C... | [fc22fb4921](https://linux-hardware.org/?probe=fc22fb4921) | Apr 23, 2023 |
| Acer          | Nitro AN515-52              | [e3dc4788e7](https://linux-hardware.org/?probe=e3dc4788e7) | Apr 22, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | [2727f5c463](https://linux-hardware.org/?probe=2727f5c463) | Apr 21, 2023 |
| Micro Elec... | MG-VCP2-17A3070T            | [edf0d6d941](https://linux-hardware.org/?probe=edf0d6d941) | Apr 21, 2023 |
| Apple         | MacBookPro8,3               | [4004491274](https://linux-hardware.org/?probe=4004491274) | Apr 21, 2023 |
| Fujitsu       | LIFEBOOK A557               | [712657fa81](https://linux-hardware.org/?probe=712657fa81) | Apr 20, 2023 |
| Dell          | Vostro 7590                 | [f759d8ab72](https://linux-hardware.org/?probe=f759d8ab72) | Apr 13, 2023 |
| GEO           | GeoBook 120                 | [2e51a1bab5](https://linux-hardware.org/?probe=2e51a1bab5) | Apr 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | [406c02acb0](https://linux-hardware.org/?probe=406c02acb0) | Apr 12, 2023 |
| Acer          | Nitro AN515-45              | [7b4e6e07cf](https://linux-hardware.org/?probe=7b4e6e07cf) | Apr 12, 2023 |
| Unknown       | ACB20                       | [16543ac693](https://linux-hardware.org/?probe=16543ac693) | Apr 12, 2023 |
| Unknown       | ACB20                       | [4c0422096b](https://linux-hardware.org/?probe=4c0422096b) | Apr 12, 2023 |
| ASUSTek       | GL752VW                     | [8abf9b082b](https://linux-hardware.org/?probe=8abf9b082b) | Apr 12, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [eb03b75c27](https://linux-hardware.org/?probe=eb03b75c27) | Apr 11, 2023 |
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
| Nobara 36 | 112       | 60.22%  |
| Nobara 37 | 74        | 39.78%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Nobara | 183       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Notebooks | Percent |
|-------------------------------|-----------|---------|
| 6.0.10-201.fc36.x86_64        | 19        | 9.95%   |
| 5.19.14-201.fsync.fc36.x86_64 | 16        | 8.38%   |
| 6.1.11-201.fsync.fc37.x86_64  | 12        | 6.28%   |
| 6.0.14-201.fsync.fc36.x86_64  | 10        | 5.24%   |
| 6.1.4-203.fsync.fc37.x86_64   | 9         | 4.71%   |
| 6.1.14-201.fsync.fc37.x86_64  | 9         | 4.71%   |
| 6.1.9-200.fsync.fc37.x86_64   | 7         | 3.66%   |
| 6.0.16-301.fsync.fc37.x86_64  | 7         | 3.66%   |
| 5.19.9-201.fsync.fc36.x86_64  | 7         | 3.66%   |
| 5.19.7-204.fsync.fc36.x86_64  | 7         | 3.66%   |
| 6.2.11-201.fsync.fc37.x86_64  | 6         | 3.14%   |
| 6.0.7-201.fsync.fc36.x86_64   | 6         | 3.14%   |
| 6.0.5-201.fsync.fc36.x86_64   | 5         | 2.62%   |
| 5.19.12-201.fsync.fc36.x86_64 | 5         | 2.62%   |
| 6.2.6-201.fsync.fc37.x86_64   | 4         | 2.09%   |
| 6.1.8-202.fsync.fc37.x86_64   | 4         | 2.09%   |
| 5.19.8-201.fsync.fc36.x86_64  | 4         | 2.09%   |
| 5.19.16-201.fsync.fc36.x86_64 | 4         | 2.09%   |
| 5.19.11-201.fsync.fc36.x86_64 | 4         | 2.09%   |
| 6.2.8-200.fsync.fc37.x86_64   | 3         | 1.57%   |
| 6.2.10-200.fsync.fc37.x86_64  | 3         | 1.57%   |
| 6.1.6-203.fsync.fc37.x86_64   | 3         | 1.57%   |
| 6.0.9-202.fc36.x86_64         | 3         | 1.57%   |
| 6.0.9-201.fc36.x86_64         | 3         | 1.57%   |
| 5.18.16-201.fsync.fc36.x86_64 | 3         | 1.57%   |
| 5.18.13-201.fsync.fc36.x86_64 | 3         | 1.57%   |
| 6.1.6-202.fsync.fc37.x86_64   | 2         | 1.05%   |
| 6.1.6-201.fsync.fc37.x86_64   | 2         | 1.05%   |
| 6.0.8-201.fsync.fc36.x86_64   | 2         | 1.05%   |
| 5.19.4-201.fsync.fc36.x86_64  | 2         | 1.05%   |
| 5.19.15-202.fsync.fc36.x86_64 | 2         | 1.05%   |
| 5.18.17-201.fsync.fc36.x86_64 | 2         | 1.05%   |
| 6.2.12-200.fsync.fc37.x86_64  | 1         | 0.52%   |
| 6.2.11-202.fsync.fc37.x86_64  | 1         | 0.52%   |
| 6.1.8-201.fsync.fc37.x86_64   | 1         | 0.52%   |
| 6.1.8-200.fsync.fc37.x86_64   | 1         | 0.52%   |
| 6.0.7-202.fsync.fc36.x86_64   | 1         | 0.52%   |
| 6.0.2-xm1.0.fc36.x86_64       | 1         | 0.52%   |
| 6.0.15-301.fsync.fc37.x86_64  | 1         | 0.52%   |
| 6.0.13-201.fsync.fc36.x86_64  | 1         | 0.52%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0.10  | 19        | 9.95%   |
| 5.19.14 | 16        | 8.38%   |
| 6.1.11  | 12        | 6.28%   |
| 6.0.14  | 10        | 5.24%   |
| 6.1.4   | 9         | 4.71%   |
| 6.1.14  | 9         | 4.71%   |
| 5.19.7  | 8         | 4.19%   |
| 6.2.11  | 7         | 3.66%   |
| 6.1.9   | 7         | 3.66%   |
| 6.1.6   | 7         | 3.66%   |
| 6.0.7   | 7         | 3.66%   |
| 6.0.16  | 7         | 3.66%   |
| 5.19.9  | 7         | 3.66%   |
| 6.1.8   | 6         | 3.14%   |
| 6.0.9   | 6         | 3.14%   |
| 6.0.5   | 5         | 2.62%   |
| 5.19.12 | 5         | 2.62%   |
| 6.2.6   | 4         | 2.09%   |
| 5.19.8  | 4         | 2.09%   |
| 5.19.16 | 4         | 2.09%   |
| 5.19.11 | 4         | 2.09%   |
| 6.2.8   | 3         | 1.57%   |
| 6.2.10  | 3         | 1.57%   |
| 5.18.16 | 3         | 1.57%   |
| 5.18.13 | 3         | 1.57%   |
| 6.0.8   | 2         | 1.05%   |
| 5.19.4  | 2         | 1.05%   |
| 5.19.15 | 2         | 1.05%   |
| 5.18.17 | 2         | 1.05%   |
| 6.2.12  | 1         | 0.52%   |
| 6.0.2   | 1         | 0.52%   |
| 6.0.15  | 1         | 0.52%   |
| 6.0.13  | 1         | 0.52%   |
| 5.19.13 | 1         | 0.52%   |
| 5.19.10 | 1         | 0.52%   |
| 5.18.19 | 1         | 0.52%   |
| 5.18.18 | 1         | 0.52%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 6.0     | 58        | 30.53%  |
| 5.19    | 54        | 28.42%  |
| 6.1     | 50        | 26.32%  |
| 6.2     | 18        | 9.47%   |
| 5.18    | 10        | 5.26%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 183       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GNOME   | 132       | 71.35%  |
| KDE5    | 49        | 26.49%  |
| Unknown | 4         | 2.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 148       | 80%     |
| X11     | 32        | 17.3%   |
| Unknown | 4         | 2.16%   |
| Tty     | 1         | 0.54%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 149       | 80.11%  |
| GDM     | 20        | 10.75%  |
| SDDM    | 15        | 8.06%   |
| LightDM | 2         | 1.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 94        | 51.09%  |
| es_ES   | 10        | 5.43%   |
| en_GB   | 10        | 5.43%   |
| ru_RU   | 6         | 3.26%   |
| pt_BR   | 6         | 3.26%   |
| pl_PL   | 6         | 3.26%   |
| de_DE   | 6         | 3.26%   |
| it_IT   | 5         | 2.72%   |
| es_MX   | 4         | 2.17%   |
| es_AR   | 4         | 2.17%   |
| en_IN   | 4         | 2.17%   |
| pt_PT   | 3         | 1.63%   |
| en_NZ   | 3         | 1.63%   |
| tr_TR   | 2         | 1.09%   |
| en_CA   | 2         | 1.09%   |
| en_AU   | 2         | 1.09%   |
| Unknown | 2         | 1.09%   |
| zh_TW   | 1         | 0.54%   |
| sv_SE   | 1         | 0.54%   |
| nb_NO   | 1         | 0.54%   |
| hu_HU   | 1         | 0.54%   |
| hr_HR   | 1         | 0.54%   |
| fr_FR   | 1         | 0.54%   |
| fi_FI   | 1         | 0.54%   |
| es_US   | 1         | 0.54%   |
| es_CR   | 1         | 0.54%   |
| es_CO   | 1         | 0.54%   |
| es_CL   | 1         | 0.54%   |
| en_ZA   | 1         | 0.54%   |
| en_PH   | 1         | 0.54%   |
| en_IE   | 1         | 0.54%   |
| de_AT   | 1         | 0.54%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 151       | 82.07%  |
| BIOS | 33        | 17.93%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Btrfs | 123       | 66.49%  |
| Ext4  | 61        | 32.97%  |
| Xfs   | 1         | 0.54%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 147       | 78.61%  |
| GPT     | 37        | 19.79%  |
| MBR     | 3         | 1.6%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 171       | 92.93%  |
| Yes       | 13        | 7.07%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 160       | 87.43%  |
| Yes       | 23        | 12.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 43        | 23.5%   |
| ASUSTek Computer    | 34        | 18.58%  |
| Hewlett-Packard     | 29        | 15.85%  |
| Dell                | 16        | 8.74%   |
| Acer                | 14        | 7.65%   |
| MSI                 | 8         | 4.37%   |
| Apple               | 8         | 4.37%   |
| Toshiba             | 3         | 1.64%   |
| Gigabyte Technology | 3         | 1.64%   |
| Positivo            | 2         | 1.09%   |
| Notebook            | 2         | 1.09%   |
| Valve               | 1         | 0.55%   |
| Sony                | 1         | 0.55%   |
| Schenker            | 1         | 0.55%   |
| Samsung Electronics | 1         | 0.55%   |
| Razer               | 1         | 0.55%   |
| ONE-NETBOOK         | 1         | 0.55%   |
| Monster             | 1         | 0.55%   |
| Micro Electronics   | 1         | 0.55%   |
| Medion              | 1         | 0.55%   |
| Intel               | 1         | 0.55%   |
| HUAWEI              | 1         | 0.55%   |
| GEO                 | 1         | 0.55%   |
| Gateway             | 1         | 0.55%   |
| Fujitsu             | 1         | 0.55%   |
| EVOO                | 1         | 0.55%   |
| Dynabook            | 1         | 0.55%   |
| Coradir             | 1         | 0.55%   |
| Casper              | 1         | 0.55%   |
| ASRock              | 1         | 0.55%   |
| Alienware           | 1         | 0.55%   |
| Unknown             | 1         | 0.55%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                                     | Notebooks | Percent |
|----------------------------------------------------------|-----------|---------|
| Unknown                                                  | 5         | 2.73%   |
| Lenovo Legion 5 15ARH05 82B5                             | 2         | 1.09%   |
| Lenovo IdeaPad Y700-15ISK 80NV                           | 2         | 1.09%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2                      | 2         | 1.09%   |
| Lenovo IdeaPad C340-14API 81N6                           | 2         | 1.09%   |
| HP ZBook 15u G3                                          | 2         | 1.09%   |
| HP Pavilion Gaming Laptop 15-ec1xxx                      | 2         | 1.09%   |
| Dell Vostro 3400                                         | 2         | 1.09%   |
| Dell Inspiron 3542                                       | 2         | 1.09%   |
| Acer Nitro AN515-52                                      | 2         | 1.09%   |
| Acer Aspire VX5-591G                                     | 2         | 1.09%   |
| Valve Jupiter                                            | 1         | 0.55%   |
| Toshiba TECRA A50-A                                      | 1         | 0.55%   |
| Toshiba Satellite L850                                   | 1         | 0.55%   |
| Toshiba Satellite L650                                   | 1         | 0.55%   |
| Sony SVF1521N6EW                                         | 1         | 0.55%   |
| Schenker XMG NEO (M19, RTX 2070)                         | 1         | 0.55%   |
| Samsung R520/R522/R620                                   | 1         | 0.55%   |
| Razer Blade                                              | 1         | 0.55%   |
| Positivo N1250                                           | 1         | 0.55%   |
| Positivo N1240                                           | 1         | 0.55%   |
| ONE-NETBOOK ONEXPLAYER 2 ARP23                           | 1         | 0.55%   |
| Notebook P7xxDM2(-G)                                     | 1         | 0.55%   |
| Notebook NP5x_NP6x_NP7xHP                                | 1         | 0.55%   |
| MSI Summit E14Evo A12M                                   | 1         | 0.55%   |
| MSI Pulse GL76 12UEK                                     | 1         | 0.55%   |
| MSI P65 Creator 8RD                                      | 1         | 0.55%   |
| MSI Katana GF76 11UD                                     | 1         | 0.55%   |
| MSI GT680R/GX680R/GT683R/GT683DXR/GT685R/GT687R/GX660DXR | 1         | 0.55%   |
| MSI GP65 Leopard 9SF                                     | 1         | 0.55%   |
| MSI GF63 Thin 10SC                                       | 1         | 0.55%   |
| MSI GE60 0NC/GE60 0ND                                    | 1         | 0.55%   |
| Monster ABRA A7 V12.1                                    | 1         | 0.55%   |
| Micro MG-VCP2-17A3070T                                   | 1         | 0.55%   |
| Medion GUARDIAN X10                                      | 1         | 0.55%   |
| Lenovo Z50-70 20354                                      | 1         | 0.55%   |
| Lenovo Yoga Slim 7 Pro 14ACH5 OD 82NK                    | 1         | 0.55%   |
| Lenovo V330-15IKB 81AX                                   | 1         | 0.55%   |
| Lenovo V14-IIL 82C4                                      | 1         | 0.55%   |
| Lenovo ThinkPad X240 20AMA0LTAU                          | 1         | 0.55%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo IdeaPad         | 15        | 8.2%    |
| Lenovo ThinkPad        | 10        | 5.46%   |
| ASUS ROG               | 10        | 5.46%   |
| ASUS VivoBook          | 8         | 4.37%   |
| Lenovo Legion          | 7         | 3.83%   |
| HP EliteBook           | 6         | 3.28%   |
| Acer Aspire            | 6         | 3.28%   |
| HP ZBook               | 5         | 2.73%   |
| HP Pavilion            | 5         | 2.73%   |
| Unknown                | 5         | 2.73%   |
| Dell Vostro            | 4         | 2.19%   |
| ASUS ASUS              | 4         | 2.19%   |
| Acer Nitro             | 4         | 2.19%   |
| Dell Precision         | 3         | 1.64%   |
| Dell Inspiron          | 3         | 1.64%   |
| ASUS TUF               | 3         | 1.64%   |
| Toshiba Satellite      | 2         | 1.09%   |
| Lenovo G580            | 2         | 1.09%   |
| HP OMEN                | 2         | 1.09%   |
| HP Laptop              | 2         | 1.09%   |
| HP ENVY                | 2         | 1.09%   |
| Gigabyte AERO          | 2         | 1.09%   |
| Dell G15               | 2         | 1.09%   |
| Apple MacBookPro8      | 2         | 1.09%   |
| Acer Swift             | 2         | 1.09%   |
| Valve Jupiter          | 1         | 0.55%   |
| Toshiba TECRA          | 1         | 0.55%   |
| Sony SVF1521N6EW       | 1         | 0.55%   |
| Schenker XMG           | 1         | 0.55%   |
| Samsung R520           | 1         | 0.55%   |
| Razer Blade            | 1         | 0.55%   |
| Positivo N1250         | 1         | 0.55%   |
| Positivo N1240         | 1         | 0.55%   |
| ONE-NETBOOK ONEXPLAYER | 1         | 0.55%   |
| Notebook P7xxDM2(-G)   | 1         | 0.55%   |
| Notebook NP5x          | 1         | 0.55%   |
| MSI Summit             | 1         | 0.55%   |
| MSI Pulse              | 1         | 0.55%   |
| MSI P65                | 1         | 0.55%   |
| MSI Katana             | 1         | 0.55%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2021 | 31        | 16.94%  |
| 2020 | 22        | 12.02%  |
| 2022 | 21        | 11.48%  |
| 2019 | 19        | 10.38%  |
| 2018 | 17        | 9.29%   |
| 2014 | 13        | 7.1%    |
| 2013 | 12        | 6.56%   |
| 2017 | 10        | 5.46%   |
| 2012 | 9         | 4.92%   |
| 2016 | 8         | 4.37%   |
| 2015 | 7         | 3.83%   |
| 2010 | 5         | 2.73%   |
| 2009 | 4         | 2.19%   |
| 2011 | 3         | 1.64%   |
| 2023 | 1         | 0.55%   |
| 2008 | 1         | 0.55%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 183       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 183       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 183       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 47        | 25.68%  |
| 8.01-16.0  | 42        | 22.95%  |
| 16.01-24.0 | 39        | 21.31%  |
| 3.01-4.0   | 24        | 13.11%  |
| 32.01-64.0 | 23        | 12.57%  |
| 24.01-32.0 | 6         | 3.28%   |
| 1.01-2.0   | 2         | 1.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 4.01-8.0  | 85        | 45.21%  |
| 2.01-3.0  | 45        | 23.94%  |
| 3.01-4.0  | 41        | 21.81%  |
| 8.01-16.0 | 11        | 5.85%   |
| 1.01-2.0  | 6         | 3.19%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 128       | 69.95%  |
| 2      | 50        | 27.32%  |
| 3      | 5         | 2.73%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 147       | 80.33%  |
| Yes       | 36        | 19.67%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 145       | 79.23%  |
| No        | 38        | 20.77%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 180       | 98.36%  |
| No        | 3         | 1.64%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 164       | 89.62%  |
| No        | 19        | 10.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 51        | 27.87%  |
| Spain        | 11        | 6.01%   |
| Poland       | 11        | 6.01%   |
| Germany      | 11        | 6.01%   |
| Brazil       | 8         | 4.37%   |
| Russia       | 6         | 3.28%   |
| Italy        | 6         | 3.28%   |
| India        | 6         | 3.28%   |
| UK           | 5         | 2.73%   |
| Mexico       | 5         | 2.73%   |
| Portugal     | 4         | 2.19%   |
| Argentina    | 4         | 2.19%   |
| Sweden       | 3         | 1.64%   |
| Romania      | 3         | 1.64%   |
| Philippines  | 3         | 1.64%   |
| New Zealand  | 3         | 1.64%   |
| Colombia     | 3         | 1.64%   |
| Chile        | 3         | 1.64%   |
| Vietnam      | 2         | 1.09%   |
| Turkey       | 2         | 1.09%   |
| Indonesia    | 2         | 1.09%   |
| Egypt        | 2         | 1.09%   |
| Croatia      | 2         | 1.09%   |
| Canada       | 2         | 1.09%   |
| Austria      | 2         | 1.09%   |
| Australia    | 2         | 1.09%   |
| Venezuela    | 1         | 0.55%   |
| Taiwan       | 1         | 0.55%   |
| South Africa | 1         | 0.55%   |
| Slovenia     | 1         | 0.55%   |
| Serbia       | 1         | 0.55%   |
| Panama       | 1         | 0.55%   |
| Pakistan     | 1         | 0.55%   |
| Norway       | 1         | 0.55%   |
| Morocco      | 1         | 0.55%   |
| Malaysia     | 1         | 0.55%   |
| Kenya        | 1         | 0.55%   |
| Ireland      | 1         | 0.55%   |
| Hungary      | 1         | 0.55%   |
| Hong Kong    | 1         | 0.55%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Notebooks | Percent |
|---------------------|-----------|---------|
| Wroclaw             | 3         | 1.57%   |
| Madrid              | 3         | 1.57%   |
| Auckland            | 3         | 1.57%   |
| Wasilla             | 2         | 1.05%   |
| Warsaw              | 2         | 1.05%   |
| Schmalkalden        | 2         | 1.05%   |
| Salem               | 2         | 1.05%   |
| Poznan              | 2         | 1.05%   |
| Perm                | 2         | 1.05%   |
| Panama City         | 2         | 1.05%   |
| Ochsenfurt          | 2         | 1.05%   |
| Mumbai              | 2         | 1.05%   |
| Milan               | 2         | 1.05%   |
| London              | 2         | 1.05%   |
| Guadalajara         | 2         | 1.05%   |
| Fortaleza           | 2         | 1.05%   |
| Bucharest           | 2         | 1.05%   |
| Zaragoza            | 1         | 0.52%   |
| Zamora              | 1         | 0.52%   |
| Zadar               | 1         | 0.52%   |
| Wesley Chapel       | 1         | 0.52%   |
| Wayne               | 1         | 0.52%   |
| Wabrzezno           | 1         | 0.52%   |
| Vladivostok         | 1         | 0.52%   |
| Villarrica          | 1         | 0.52%   |
| Villacarrillo       | 1         | 0.52%   |
| Villa Nueva         | 1         | 0.52%   |
| Vienna              | 1         | 0.52%   |
| Veszprém           | 1         | 0.52%   |
| Varaždin           | 1         | 0.52%   |
| Valladolid          | 1         | 0.52%   |
| Vagos               | 1         | 0.52%   |
| Ulm                 | 1         | 0.52%   |
| Uhldingen-Muhlhofen | 1         | 0.52%   |
| Tulsa               | 1         | 0.52%   |
| Tomah               | 1         | 0.52%   |
| Tenna               | 1         | 0.52%   |
| Temuco              | 1         | 0.52%   |
| Tampa               | 1         | 0.52%   |
| Sunnyvale           | 1         | 0.52%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 51        | 59     | 21.61%  |
| WDC                          | 17        | 19     | 7.2%    |
| SanDisk                      | 16        | 16     | 6.78%   |
| Toshiba                      | 15        | 19     | 6.36%   |
| SK hynix                     | 14        | 14     | 5.93%   |
| Seagate                      | 14        | 14     | 5.93%   |
| Kingston                     | 14        | 14     | 5.93%   |
| Intel                        | 13        | 13     | 5.51%   |
| Micron Technology            | 10        | 10     | 4.24%   |
| Crucial                      | 8         | 8      | 3.39%   |
| Micron/Crucial Technology    | 7         | 7      | 2.97%   |
| Unknown                      | 6         | 6      | 2.54%   |
| Phison Electronics           | 6         | 6      | 2.54%   |
| HGST                         | 5         | 5      | 2.12%   |
| KIOXIA                       | 4         | 4      | 1.69%   |
| Hitachi                      | 4         | 5      | 1.69%   |
| China                        | 4         | 4      | 1.69%   |
| Apple                        | 4         | 5      | 1.69%   |
| Team                         | 2         | 2      | 0.85%   |
| LITEON                       | 2         | 2      | 0.85%   |
| Kingston Technology Company  | 2         | 2      | 0.85%   |
| HS-SSD-C100                  | 2         | 2      | 0.85%   |
| Unknown                      | 2         | 2      | 0.85%   |
| Union Memory                 | 1         | 2      | 0.42%   |
| T-FORCE                      | 1         | 1      | 0.42%   |
| SPCC                         | 1         | 1      | 0.42%   |
| Solid State Storage          | 1         | 1      | 0.42%   |
| Silicon Motion               | 1         | 1      | 0.42%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.42%   |
| Ramsta                       | 1         | 1      | 0.42%   |
| PNY                          | 1         | 1      | 0.42%   |
| Mushkin                      | 1         | 1      | 0.42%   |
| HGST HTS                     | 1         | 1      | 0.42%   |
| Fujitsu                      | 1         | 1      | 0.42%   |
| Emtec                        | 1         | 1      | 0.42%   |
| ADATA Technology             | 1         | 1      | 0.42%   |
| A-DATA Technology            | 1         | 1      | 0.42%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 8         | 3.27%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB               | 6         | 2.45%   |
| Kingston SA400S37240G 240GB SSD                     | 6         | 2.45%   |
| Toshiba MQ04ABF100 1TB                              | 4         | 1.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 4         | 1.63%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 4         | 1.63%   |
| Intel SSDPEKNU512GZ 512GB                           | 4         | 1.63%   |
| SK hynix BC511 512GB                                | 3         | 1.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 3         | 1.22%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 3         | 1.22%   |
| Samsung SSD 980 1TB                                 | 3         | 1.22%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB | 3         | 1.22%   |
| Samsung NVMe SSD Controller SM951/PM951 256GB       | 3         | 1.22%   |
| Samsung MZALQ512HBLU-00BL2 512GB                    | 3         | 1.22%   |
| KIOXIA KBG40ZNS512G NVMe 512GB                      | 3         | 1.22%   |
| WDC WD10SPZX-21Z10T0 1TB                            | 2         | 0.82%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB                | 2         | 0.82%   |
| Unknown MMC Card  32GB                              | 2         | 0.82%   |
| Toshiba MQ01ABF050 500GB                            | 2         | 0.82%   |
| Toshiba MQ01ABD100 1TB                              | 2         | 0.82%   |
| Toshiba MQ01ABD050 500GB                            | 2         | 0.82%   |
| SK hynix SKHynix_HFS512GD9TNI-L2A0B 512GB           | 2         | 0.82%   |
| SK hynix HFS128G39TND-N210A 128GB SSD               | 2         | 0.82%   |
| Seagate ST500LT012-1DG142 500GB                     | 2         | 0.82%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD 512GB     | 2         | 0.82%   |
| Samsung SSD 850 EVO 250GB                           | 2         | 0.82%   |
| Samsung NVMe SSD Drive 1024GB                       | 2         | 0.82%   |
| Samsung MZVLQ1T0HBLB-00B00 1024GB                   | 2         | 0.82%   |
| Phison PS5013 E13 NVMe Controller 500GB             | 2         | 0.82%   |
| Phison E12 NVMe Controller 512GB                    | 2         | 0.82%   |
| Micron 2450_MTFDKBA1T0TFK 1TB                       | 2         | 0.82%   |
| Micron 2210_MTFDHBA512QFD 512GB                     | 2         | 0.82%   |
| Kingston NVMe SSD Drive 512GB                       | 2         | 0.82%   |
| Intel SSD 660P Series 512GB                         | 2         | 0.82%   |
| HS-SSD-C100 120G                                    | 2         | 0.82%   |
| Hitachi HTS547575A9E384 752GB                       | 2         | 0.82%   |
| Crucial CT500MX500SSD1 500GB                        | 2         | 0.82%   |
| China SATA SSD 120GB                                | 2         | 0.82%   |
| Unknown                                             | 2         | 0.82%   |
| WDC WDS500G3X0C-00SJG0 500GB                        | 1         | 0.41%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 14        | 14     | 28.57%  |
| Toshiba  | 12        | 15     | 24.49%  |
| WDC      | 10        | 11     | 20.41%  |
| HGST     | 5         | 5      | 10.2%   |
| Hitachi  | 4         | 5      | 8.16%   |
| Unknown  | 1         | 1      | 2.04%   |
| HGST HTS | 1         | 1      | 2.04%   |
| Fujitsu  | 1         | 1      | 2.04%   |
| Apple    | 1         | 1      | 2.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 14        | 15     | 24.14%  |
| Kingston            | 8         | 8      | 13.79%  |
| Crucial             | 7         | 7      | 12.07%  |
| SK hynix            | 4         | 4      | 6.9%    |
| China               | 4         | 4      | 6.9%    |
| SanDisk             | 3         | 3      | 5.17%   |
| Team                | 2         | 2      | 3.45%   |
| Micron Technology   | 2         | 2      | 3.45%   |
| LITEON              | 2         | 2      | 3.45%   |
| Intel               | 2         | 2      | 3.45%   |
| Apple               | 2         | 2      | 3.45%   |
| WDC                 | 1         | 2      | 1.72%   |
| Toshiba             | 1         | 1      | 1.72%   |
| SPCC                | 1         | 1      | 1.72%   |
| Ramsta              | 1         | 1      | 1.72%   |
| PNY                 | 1         | 1      | 1.72%   |
| Mushkin             | 1         | 1      | 1.72%   |
| Emtec               | 1         | 1      | 1.72%   |
| A-DATA Technology   | 1         | 1      | 1.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 104       | 129    | 47.71%  |
| SSD     | 56        | 60     | 25.69%  |
| HDD     | 48        | 54     | 22.02%  |
| MMC     | 5         | 5      | 2.29%   |
| Unknown | 5         | 5      | 2.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 104       | 129    | 49.29%  |
| SATA | 96        | 113    | 45.5%   |
| SAS  | 6         | 6      | 2.84%   |
| MMC  | 5         | 5      | 2.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 61        | 66     | 58.1%   |
| 0.51-1.0   | 39        | 42     | 37.14%  |
| 1.01-2.0   | 3         | 4      | 2.86%   |
| 3.01-4.0   | 1         | 1      | 0.95%   |
| 4.01-10.0  | 1         | 1      | 0.95%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 501-1000       | 48        | 25.67%  |
| 251-500        | 41        | 21.93%  |
| 101-250        | 41        | 21.93%  |
| 1001-2000      | 23        | 12.3%   |
| Unknown        | 9         | 4.81%   |
| More than 3000 | 7         | 3.74%   |
| 51-100         | 7         | 3.74%   |
| 21-50          | 6         | 3.21%   |
| 2001-3000      | 4         | 2.14%   |
| 1-20           | 1         | 0.53%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 21-50          | 54        | 28.57%  |
| 1-20           | 42        | 22.22%  |
| 101-250        | 27        | 14.29%  |
| 251-500        | 22        | 11.64%  |
| 51-100         | 19        | 10.05%  |
| 501-1000       | 10        | 5.29%   |
| Unknown        | 9         | 4.76%   |
| 1001-2000      | 4         | 2.12%   |
| More than 3000 | 1         | 0.53%   |
| 2001-3000      | 1         | 0.53%   |

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
| Detected | 150       | 197    | 78.13%  |
| Works    | 39        | 52     | 20.31%  |
| Malfunc  | 3         | 4      | 1.56%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 112       | 43.92%  |
| Samsung Electronics            | 39        | 15.29%  |
| AMD                            | 31        | 12.16%  |
| SanDisk                        | 18        | 7.06%   |
| SK hynix                       | 10        | 3.92%   |
| Micron/Crucial Technology      | 8         | 3.14%   |
| Micron Technology              | 8         | 3.14%   |
| Kingston Technology Company    | 8         | 3.14%   |
| Phison Electronics             | 6         | 2.35%   |
| KIOXIA                         | 4         | 1.57%   |
| Toshiba America Info Systems   | 2         | 0.78%   |
| Nvidia                         | 2         | 0.78%   |
| Union Memory (Shenzhen)        | 1         | 0.39%   |
| Solid State Storage Technology | 1         | 0.39%   |
| Silicon Motion                 | 1         | 0.39%   |
| Shenzhen Longsys Electronics   | 1         | 0.39%   |
| Marvell Technology Group       | 1         | 0.39%   |
| Apple                          | 1         | 0.39%   |
| ADATA Technology               | 1         | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 31        | 11.65%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 13        | 4.89%   |
| Samsung NVMe SSD Controller 980                                                | 13        | 4.89%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 12        | 4.51%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 3.76%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 10        | 3.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 9         | 3.38%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 9         | 3.38%   |
| Micron NVMe Storage Controller                                                 | 8         | 3.01%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 8         | 3.01%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 7         | 2.63%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 7         | 2.63%   |
| Intel Volume Management Device NVMe RAID Controller                            | 7         | 2.63%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 7         | 2.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 6         | 2.26%   |
| Intel Non-Volatile memory controller                                           | 5         | 1.88%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 1.88%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 4         | 1.5%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 4         | 1.5%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 4         | 1.5%    |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 1.5%    |
| Intel SSD 660P Series                                                          | 4         | 1.5%    |
| SK hynix BC511                                                                 | 3         | 1.13%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 3         | 1.13%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.13%   |
| Samsung NVMe SSD Controller SM951/PM951                                        | 3         | 1.13%   |
| Micron/Crucial NVMe Storage Controller                                         | 3         | 1.13%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 3         | 1.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.13%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 3         | 1.13%   |
| SK hynix Non-Volatile memory controller                                        | 2         | 0.75%   |
| SanDisk NVMe Controller                                                        | 2         | 0.75%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 0.75%   |
| Phison PS5013 E13 NVMe Controller                                              | 2         | 0.75%   |
| Phison E12 NVMe Controller                                                     | 2         | 0.75%   |
| Nvidia MCP79 AHCI Controller                                                   | 2         | 0.75%   |
| Kingston Company Company Non-Volatile memory controller                        | 2         | 0.75%   |
| Kingston Company A2000 NVMe SSD                                                | 2         | 0.75%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 2         | 0.75%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 2         | 0.75%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 124       | 50.2%   |
| NVMe | 104       | 42.11%  |
| RAID | 18        | 7.29%   |
| IDE  | 1         | 0.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 130       | 71.04%  |
| AMD    | 53        | 28.96%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 5         | 2.73%   |
| Intel Core i7-10750H CPU @ 2.60GHz              | 5         | 2.73%   |
| Intel Core i5-10300H CPU @ 2.50GHz              | 5         | 2.73%   |
| AMD Ryzen 7 5800H with Radeon Graphics          | 5         | 2.73%   |
| AMD Ryzen 5 4600H with Radeon Graphics          | 5         | 2.73%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 4         | 2.19%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz              | 4         | 2.19%   |
| Intel Core i5-8300H CPU @ 2.30GHz               | 4         | 2.19%   |
| Intel Core i3-4005U CPU @ 1.70GHz               | 4         | 2.19%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz         | 4         | 2.19%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 3         | 1.64%   |
| Intel Core i3-4030U CPU @ 1.90GHz               | 3         | 1.64%   |
| Intel 12th Gen Core i7-12700H                   | 3         | 1.64%   |
| AMD Ryzen 7 5700U with Radeon Graphics          | 3         | 1.64%   |
| AMD Ryzen 5 5500U with Radeon Graphics          | 3         | 1.64%   |
| Intel Pentium CPU B960 @ 2.20GHz                | 2         | 1.09%   |
| Intel Core i7-8850H CPU @ 2.60GHz               | 2         | 1.09%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz              | 2         | 1.09%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 1.09%   |
| Intel Core i5-4300U CPU @ 1.90GHz               | 2         | 1.09%   |
| Intel Core i5-4200M CPU @ 2.50GHz               | 2         | 1.09%   |
| Intel Core i5-3210M CPU @ 2.50GHz               | 2         | 1.09%   |
| Intel Celeron N4020 CPU @ 1.10GHz               | 2         | 1.09%   |
| Intel 12th Gen Core i7-12650H                   | 2         | 1.09%   |
| Intel 12th Gen Core i5-1240P                    | 2         | 1.09%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 2         | 1.09%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 2         | 1.09%   |
| Intel 11th Gen Core i5-11300H @ 3.10GHz         | 2         | 1.09%   |
| AMD Ryzen 9 6900HX with Radeon Graphics         | 2         | 1.09%   |
| AMD Ryzen 9 5900HS with Radeon Graphics         | 2         | 1.09%   |
| AMD Ryzen 7 6800H with Radeon Graphics          | 2         | 1.09%   |
| AMD Ryzen 7 4800H with Radeon Graphics          | 2         | 1.09%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx   | 2         | 1.09%   |
| AMD Ryzen 5 5600U with Radeon Graphics          | 2         | 1.09%   |
| AMD Ryzen 5 5600H with Radeon Graphics          | 2         | 1.09%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx   | 2         | 1.09%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 2         | 1.09%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 2         | 1.09%   |
| AMD A10-8700P Radeon R6, 10 Compute Cores 4C+6G | 2         | 1.09%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz     | 1         | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 51        | 27.87%  |
| Intel Core i5           | 32        | 17.49%  |
| Other                   | 21        | 11.48%  |
| AMD Ryzen 5             | 21        | 11.48%  |
| AMD Ryzen 7             | 19        | 10.38%  |
| Intel Core i3           | 10        | 5.46%   |
| Intel Celeron           | 8         | 4.37%   |
| AMD Ryzen 9             | 6         | 3.28%   |
| Intel Pentium           | 3         | 1.64%   |
| Intel Core 2 Duo        | 3         | 1.64%   |
| AMD A10                 | 2         | 1.09%   |
| Intel Pentium Dual-Core | 1         | 0.55%   |
| Intel Core 2 Extreme    | 1         | 0.55%   |
| Intel Atom              | 1         | 0.55%   |
| AMD Ryzen 3             | 1         | 0.55%   |
| AMD FX                  | 1         | 0.55%   |
| AMD E                   | 1         | 0.55%   |
| AMD A6                  | 1         | 0.55%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 59        | 32.24%  |
| 4      | 58        | 31.69%  |
| 8      | 29        | 15.85%  |
| 6      | 29        | 15.85%  |
| 14     | 3         | 1.64%   |
| 12     | 3         | 1.64%   |
| 10     | 2         | 1.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 183       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 164       | 89.62%  |
| 1      | 19        | 10.38%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 183       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 22        | 11.76%  |
| 0x0a50000c | 13        | 6.95%   |
| 0xa0652    | 12        | 6.42%   |
| 0x40651    | 11        | 5.88%   |
| 0x906ea    | 8         | 4.28%   |
| 0x906a3    | 8         | 4.28%   |
| 0x306a9    | 8         | 4.28%   |
| 0x206a7    | 8         | 4.28%   |
| 0x906e9    | 7         | 3.74%   |
| 0x806c1    | 7         | 3.74%   |
| 0x08608103 | 6         | 3.21%   |
| 0x806d1    | 5         | 2.67%   |
| 0x506e3    | 5         | 2.67%   |
| 0x306c3    | 5         | 2.67%   |
| 0x08108109 | 5         | 2.67%   |
| 0x806e9    | 4         | 2.14%   |
| 0x406e3    | 4         | 2.14%   |
| 0x08600106 | 4         | 2.14%   |
| 0x08600104 | 4         | 2.14%   |
| 0x806ea    | 3         | 1.6%    |
| 0x10676    | 3         | 1.6%    |
| 0x0a50000d | 3         | 1.6%    |
| 0x0a404102 | 3         | 1.6%    |
| 0x806ec    | 2         | 1.07%   |
| 0x706e5    | 2         | 1.07%   |
| 0x306d4    | 2         | 1.07%   |
| 0x30678    | 2         | 1.07%   |
| 0x1067a    | 2         | 1.07%   |
| 0x0a404101 | 2         | 1.07%   |
| 0x08108102 | 2         | 1.07%   |
| 0x06006110 | 2         | 1.07%   |
| 0xa0655    | 1         | 0.53%   |
| 0x906ed    | 1         | 0.53%   |
| 0x706a1    | 1         | 0.53%   |
| 0x506c9    | 1         | 0.53%   |
| 0x30661    | 1         | 0.53%   |
| 0x20655    | 1         | 0.53%   |
| 0x20652    | 1         | 0.53%   |
| 0x08900201 | 1         | 0.53%   |
| 0x08101007 | 1         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 31        | 16.94%  |
| Haswell          | 20        | 10.93%  |
| Zen 3            | 16        | 8.74%   |
| CometLake        | 14        | 7.65%   |
| Unknown          | 13        | 7.1%    |
| Skylake          | 10        | 5.46%   |
| Zen 2            | 9         | 4.92%   |
| SandyBridge      | 8         | 4.37%   |
| IvyBridge        | 8         | 4.37%   |
| Alderlake Hybrid | 8         | 4.37%   |
| Zen+             | 7         | 3.83%   |
| TigerLake        | 7         | 3.83%   |
| Icelake          | 7         | 3.83%   |
| Penryn           | 5         | 2.73%   |
| Zen              | 3         | 1.64%   |
| Silvermont       | 3         | 1.64%   |
| Goldmont plus    | 3         | 1.64%   |
| Westmere         | 2         | 1.09%   |
| Excavator        | 2         | 1.09%   |
| Broadwell        | 2         | 1.09%   |
| Steamroller      | 1         | 0.55%   |
| Puma             | 1         | 0.55%   |
| Goldmont         | 1         | 0.55%   |
| Bonnell          | 1         | 0.55%   |
| Bobcat           | 1         | 0.55%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 115       | 41.67%  |
| Nvidia | 96        | 34.78%  |
| AMD    | 65        | 23.55%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 14        | 4.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 13        | 4.59%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 13        | 4.59%   |
| Intel CometLake-H GT2 [UHD Graphics]                                      | 11        | 3.89%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 9         | 3.18%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 8         | 2.83%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 7         | 2.47%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 7         | 2.47%   |
| AMD Renoir                                                                | 7         | 2.47%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 7         | 2.47%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                | 6         | 2.12%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 6         | 2.12%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 6         | 2.12%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 2.12%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 6         | 2.12%   |
| AMD Rembrandt [Radeon 680M]                                               | 6         | 2.12%   |
| AMD Lucienne                                                              | 6         | 2.12%   |
| Nvidia TU117M                                                             | 5         | 1.77%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 5         | 1.77%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 5         | 1.77%   |
| Intel HD Graphics 630                                                     | 5         | 1.77%   |
| Intel HD Graphics 530                                                     | 5         | 1.77%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 4         | 1.41%   |
| Intel HD Graphics 620                                                     | 4         | 1.41%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                   | 3         | 1.06%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 3         | 1.06%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 3         | 1.06%   |
| Intel UHD Graphics 620                                                    | 3         | 1.06%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 3         | 1.06%   |
| AMD Opal XT [Radeon R7 M265/M365X/M465]                                   | 3         | 1.06%   |
| Nvidia TU117M [GeForce MX450]                                             | 2         | 0.71%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                   | 2         | 0.71%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                           | 2         | 0.71%   |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                             | 2         | 0.71%   |
| Nvidia C79 [GeForce 9400M]                                                | 2         | 0.71%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 2         | 0.71%   |
| Intel HD Graphics 5500                                                    | 2         | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display              | 2         | 0.71%   |
| Intel Alder Lake-P GT1 [UHD Graphics]                                     | 2         | 0.71%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                       | 2         | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel + Nvidia     | 63        | 34.43%  |
| 1 x Intel          | 42        | 22.95%  |
| 1 x AMD            | 31        | 16.94%  |
| AMD + Nvidia       | 20        | 10.93%  |
| 1 x Nvidia         | 12        | 6.56%   |
| Intel + AMD        | 8         | 4.37%   |
| 2 x AMD            | 6         | 3.28%   |
| Intel + 2 x Nvidia | 1         | 0.55%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 108       | 58.7%   |
| Proprietary | 75        | 40.76%  |
| Unknown     | 1         | 0.54%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 104       | 56.22%  |
| 0.01-0.5   | 31        | 16.76%  |
| 1.01-2.0   | 19        | 10.27%  |
| 0.51-1.0   | 12        | 6.49%   |
| 3.01-4.0   | 7         | 3.78%   |
| 7.01-8.0   | 5         | 2.7%    |
| 5.01-6.0   | 5         | 2.7%    |
| 8.01-16.0  | 2         | 1.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 47        | 21.96%  |
| BOE                     | 32        | 14.95%  |
| LG Display              | 25        | 11.68%  |
| Chimei Innolux          | 25        | 11.68%  |
| Samsung Electronics     | 21        | 9.81%   |
| PANDA                   | 12        | 5.61%   |
| Apple                   | 7         | 3.27%   |
| Sharp                   | 6         | 2.8%    |
| Goldstar                | 5         | 2.34%   |
| ViewSonic               | 3         | 1.4%    |
| MSI                     | 3         | 1.4%    |
| Hewlett-Packard         | 3         | 1.4%    |
| Dell                    | 3         | 1.4%    |
| Philips                 | 2         | 0.93%   |
| InfoVision              | 2         | 0.93%   |
| Eizo                    | 2         | 0.93%   |
| Chi Mei Optoelectronics | 2         | 0.93%   |
| AOC                     | 2         | 0.93%   |
| Acer                    | 2         | 0.93%   |
| ___                     | 1         | 0.47%   |
| Vizio                   | 1         | 0.47%   |
| Valve                   | 1         | 0.47%   |
| Unknown                 | 1         | 0.47%   |
| Sony                    | 1         | 0.47%   |
| Ruijiang                | 1         | 0.47%   |
| MLT                     | 1         | 0.47%   |
| Lenovo                  | 1         | 0.47%   |
| CSO                     | 1         | 0.47%   |
| CPT                     | 1         | 0.47%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 1.87%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 3         | 1.4%    |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch          | 3         | 1.4%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 3         | 1.4%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 3         | 1.4%    |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch         | 3         | 1.4%    |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch               | 2         | 0.93%   |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch          | 2         | 0.93%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch          | 2         | 0.93%   |
| Eizo EV2335W ENC2293 1920x1080 510x287mm 23.0-inch                    | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 2         | 0.93%   |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch       | 2         | 0.93%   |
| BOE LCD Monitor BOE0998 1920x1080 344x194mm 15.5-inch                 | 2         | 0.93%   |
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch        | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch        | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 2         | 0.93%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.93%   |
| ___ LCD TV ___9000 1360x768                                           | 1         | 0.47%   |
| Vizio E241i-B1 VIZ1005 1920x1080 521x293mm 23.5-inch                  | 1         | 0.47%   |
| ViewSonic VX2768-2KP VSC0A3B 2560x1440 597x336mm 27.0-inch            | 1         | 0.47%   |
| ViewSonic VX2452 Series VSCDE2E 1920x1080 521x293mm 23.5-inch         | 1         | 0.47%   |
| ViewSonic VA2446 SERIES VSC732E 1920x1080 521x293mm 23.5-inch         | 1         | 0.47%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                   | 1         | 0.47%   |
| Unknown LCDTV 9000 1360x768 1600x900mm 72.3-inch                      | 1         | 0.47%   |
| Sony TV SNY1B02 1360x768                                              | 1         | 0.47%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch               | 1         | 0.47%   |
| Sharp LQ140Z1JW01 SHP1401 3200x1800 310x174mm 14.0-inch               | 1         | 0.47%   |
| Sharp LQ140M1JW49 SHP1523 1920x1080 309x174mm 14.0-inch               | 1         | 0.47%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch               | 1         | 0.47%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 1         | 0.47%   |
| Samsung Electronics U32J59x SAM0F52 3840x2160 697x392mm 31.5-inch     | 1         | 0.47%   |
| Samsung Electronics SMB2440MH SAM06DD 1920x1080                       | 1         | 0.47%   |
| Samsung Electronics S24D390 SAM0B65 1920x1080 521x293mm 23.5-inch     | 1         | 0.47%   |
| Samsung Electronics Odyssey G8 SAM71EC 3840x2160 697x392mm 31.5-inch  | 1         | 0.47%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch     | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC5442 1440x900 303x190mm 14.1-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC334A 1366x768 344x194mm 15.5-inch  | 1         | 0.47%   |
| Samsung Electronics LCD Monitor SEC3030 1024x600 223x125mm 10.1-inch  | 1         | 0.47%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 104       | 53.06%  |
| 1366x768 (WXGA)    | 41        | 20.92%  |
| 3840x2160 (4K)     | 9         | 4.59%   |
| 2560x1440 (QHD)    | 6         | 3.06%   |
| 1920x1200 (WUXGA)  | 6         | 3.06%   |
| 2560x1600          | 5         | 2.55%   |
| 2880x1800          | 4         | 2.04%   |
| 1440x900 (WXGA+)   | 4         | 2.04%   |
| 1280x800 (WXGA)    | 3         | 1.53%   |
| 2560x1080          | 2         | 1.02%   |
| 2240x1400          | 2         | 1.02%   |
| 1360x768           | 2         | 1.02%   |
| 800x1280           | 1         | 0.51%   |
| 3840x2400          | 1         | 0.51%   |
| 3840x1100          | 1         | 0.51%   |
| 3200x1800 (QHD+)   | 1         | 0.51%   |
| 2520x1680          | 1         | 0.51%   |
| 1680x1050 (WSXGA+) | 1         | 0.51%   |
| 1600x900 (HD+)     | 1         | 0.51%   |
| 1600x2560          | 1         | 0.51%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 106       | 49.53%  |
| 13      | 20        | 9.35%   |
| 17      | 19        | 8.88%   |
| 14      | 18        | 8.41%   |
| 23      | 9         | 4.21%   |
| 31      | 7         | 3.27%   |
| 27      | 6         | 2.8%    |
| 16      | 6         | 2.8%    |
| 24      | 4         | 1.87%   |
| 72      | 2         | 0.93%   |
| 34      | 2         | 0.93%   |
| 18      | 2         | 0.93%   |
| Unknown | 2         | 0.93%   |
| 86      | 1         | 0.47%   |
| 84      | 1         | 0.47%   |
| 48      | 1         | 0.47%   |
| 26      | 1         | 0.47%   |
| 21      | 1         | 0.47%   |
| 20      | 1         | 0.47%   |
| 12      | 1         | 0.47%   |
| 11      | 1         | 0.47%   |
| 10      | 1         | 0.47%   |
| 8       | 1         | 0.47%   |
| 7       | 1         | 0.47%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 140       | 66.35%  |
| 351-400     | 19        | 9%      |
| 501-600     | 18        | 8.53%   |
| 201-300     | 12        | 5.69%   |
| 601-700     | 8         | 3.79%   |
| 401-500     | 4         | 1.9%    |
| 1501-2000   | 3         | 1.42%   |
| 701-800     | 2         | 0.95%   |
| Unknown     | 2         | 0.95%   |
| 101-200     | 1         | 0.47%   |
| 1001-1500   | 1         | 0.47%   |
| 1-100       | 1         | 0.47%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 153       | 83.15%  |
| 16/10 | 25        | 13.59%  |
| 21/9  | 2         | 1.09%   |
| 3/2   | 1         | 0.54%   |
| 3.40  | 1         | 0.54%   |
| 0.67  | 1         | 0.54%   |
| 0.62  | 1         | 0.54%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 106       | 50%     |
| 81-90          | 32        | 15.09%  |
| 121-130        | 17        | 8.02%   |
| 201-250        | 10        | 4.72%   |
| 351-500        | 9         | 4.25%   |
| 301-350        | 6         | 2.83%   |
| 111-120        | 6         | 2.83%   |
| 71-80          | 5         | 2.36%   |
| More than 1000 | 4         | 1.89%   |
| 251-300        | 4         | 1.89%   |
| 51-60          | 2         | 0.94%   |
| 1-40           | 2         | 0.94%   |
| 141-150        | 2         | 0.94%   |
| 131-140        | 2         | 0.94%   |
| Unknown        | 2         | 0.94%   |
| 61-70          | 1         | 0.47%   |
| 41-50          | 1         | 0.47%   |
| 151-200        | 1         | 0.47%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 104       | 49.76%  |
| 101-120       | 42        | 20.1%   |
| 51-100        | 29        | 13.88%  |
| 161-240       | 17        | 8.13%   |
| More than 240 | 11        | 5.26%   |
| 1-50          | 4         | 1.91%   |
| Unknown       | 2         | 0.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 143       | 78.14%  |
| 2     | 31        | 16.94%  |
| 0     | 5         | 2.73%   |
| 3     | 4         | 2.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 113       | 37.67%  |
| Intel                           | 99        | 33%     |
| Qualcomm Atheros                | 28        | 9.33%   |
| Broadcom                        | 19        | 6.33%   |
| MediaTek                        | 14        | 4.67%   |
| ASIX Electronics                | 4         | 1.33%   |
| Samsung Electronics             | 3         | 1%      |
| Broadcom Limited                | 3         | 1%      |
| Xiaomi                          | 2         | 0.67%   |
| Qualcomm                        | 2         | 0.67%   |
| Nvidia                          | 2         | 0.67%   |
| Sierra Wireless                 | 1         | 0.33%   |
| Ralink                          | 1         | 0.33%   |
| Qualcomm Atheros Communications | 1         | 0.33%   |
| Panasonic (Matsushita)          | 1         | 0.33%   |
| Motorola PCS                    | 1         | 0.33%   |
| Marvell Technology Group        | 1         | 0.33%   |
| Lenovo                          | 1         | 0.33%   |
| JMicron Technology              | 1         | 0.33%   |
| Google                          | 1         | 0.33%   |
| ASUSTek Computer                | 1         | 0.33%   |
| Afatech                         | 1         | 0.33%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 81        | 23.75%  |
| Intel Wi-Fi 6 AX200                                               | 13        | 3.81%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 13        | 3.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 10        | 2.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 10        | 2.93%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 9         | 2.64%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 2.35%   |
| Intel Wireless 7260                                               | 8         | 2.35%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 7         | 2.05%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 6         | 1.76%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.76%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 1.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.76%   |
| Intel Wireless 8265 / 8275                                        | 6         | 1.76%   |
| Intel Wireless 8260                                               | 6         | 1.76%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 1.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 1.47%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.17%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 1.17%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.17%   |
| Intel Wireless 7265                                               | 4         | 1.17%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3         | 0.88%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 3         | 0.88%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 3         | 0.88%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 0.88%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.88%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 2         | 0.59%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 2         | 0.59%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.59%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.59%   |
| Intel Wireless-AC 9260                                            | 2         | 0.59%   |
| Intel Wireless 3160                                               | 2         | 0.59%   |
| Intel WiFi Link 5100                                              | 2         | 0.59%   |
| Intel I211 Gigabit Network Connection                             | 2         | 0.59%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.59%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.59%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 96        | 52.17%  |
| Realtek Semiconductor           | 28        | 15.22%  |
| Qualcomm Atheros                | 23        | 12.5%   |
| Broadcom                        | 16        | 8.7%    |
| MediaTek                        | 14        | 7.61%   |
| Broadcom Limited                | 2         | 1.09%   |
| Sierra Wireless                 | 1         | 0.54%   |
| Ralink                          | 1         | 0.54%   |
| Qualcomm Atheros Communications | 1         | 0.54%   |
| Panasonic (Matsushita)          | 1         | 0.54%   |
| ASUSTek Computer                | 1         | 0.54%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 13        | 7.07%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 13        | 7.07%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 10        | 5.43%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 10        | 5.43%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 9         | 4.89%   |
| Intel Wireless 7260                                                     | 8         | 4.35%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 7         | 3.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 6         | 3.26%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 6         | 3.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 3.26%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 3.26%   |
| Intel Wireless 8265 / 8275                                              | 6         | 3.26%   |
| Intel Wireless 8260                                                     | 6         | 3.26%   |
| Intel Wi-Fi 6 AX201                                                     | 6         | 3.26%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 5         | 2.72%   |
| Broadcom BCM43142 802.11b/g/n                                           | 5         | 2.72%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.17%   |
| Intel Wireless 7265                                                     | 4         | 2.17%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3         | 1.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 3         | 1.63%   |
| Intel Tiger Lake PCH CNVi WiFi                                          | 3         | 1.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 3         | 1.63%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.09%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 1.09%   |
| Intel Wireless-AC 9260                                                  | 2         | 1.09%   |
| Intel Wireless 3160                                                     | 2         | 1.09%   |
| Intel WiFi Link 5100                                                    | 2         | 1.09%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 2         | 1.09%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 2         | 1.09%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 2         | 1.09%   |
| Sierra Wireless EM7455                                                  | 1         | 0.54%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 1         | 0.54%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.54%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 1         | 0.54%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1         | 0.54%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.54%   |
| Qualcomm Atheros AR9271 802.11n                                         | 1         | 0.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 1         | 0.54%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1         | 0.54%   |
| Panasonic (Matsushita) DY-WL10 802.11abgn Adapter [Broadcom BCM4323]    | 1         | 0.54%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Notebooks | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 101       | 66.01%  |
| Intel                    | 23        | 15.03%  |
| Qualcomm Atheros         | 7         | 4.58%   |
| Broadcom                 | 5         | 3.27%   |
| ASIX Electronics         | 4         | 2.61%   |
| Xiaomi                   | 2         | 1.31%   |
| Qualcomm                 | 2         | 1.31%   |
| Nvidia                   | 2         | 1.31%   |
| Samsung Electronics      | 1         | 0.65%   |
| Motorola PCS             | 1         | 0.65%   |
| Marvell Technology Group | 1         | 0.65%   |
| Lenovo                   | 1         | 0.65%   |
| JMicron Technology       | 1         | 0.65%   |
| Google                   | 1         | 0.65%   |
| Broadcom Limited         | 1         | 0.65%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 81        | 52.6%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 5.19%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 2.6%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 1.95%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 1.95%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.95%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 1.95%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 1.3%    |
| Nvidia MCP79 Ethernet                                             | 2         | 1.3%    |
| Intel I211 Gigabit Network Connection                             | 2         | 1.3%    |
| Intel Ethernet Connection I217-V                                  | 2         | 1.3%    |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.3%    |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 1.3%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 1.3%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.65%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.65%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.65%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.65%   |
| Qualcomm Nokia XR20                                               | 1         | 0.65%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1         | 0.65%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 1         | 0.65%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1         | 0.65%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.65%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 1         | 0.65%   |
| Qualcomm Android                                                  | 1         | 0.65%   |
| Motorola PCS motorola razr 2022                                   | 1         | 0.65%   |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 1         | 0.65%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.65%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.65%   |
| Intel Ethernet Controller I225-V                                  | 1         | 0.65%   |
| Intel Ethernet Connection I219-V                                  | 1         | 0.65%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.65%   |
| Intel Ethernet Connection (5) I219-LM                             | 1         | 0.65%   |
| Intel Ethernet Connection (4) I219-LM                             | 1         | 0.65%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.65%   |
| Intel Ethernet Connection (2) I219-LM                             | 1         | 0.65%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 0.65%   |
| Intel Ethernet Connection (10) I219-V                             | 1         | 0.65%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 180       | 54.71%  |
| Ethernet | 146       | 44.38%  |
| Modem    | 2         | 0.61%   |
| Unknown  | 1         | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 144       | 74.23%  |
| Ethernet | 50        | 25.77%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 134       | 73.22%  |
| 1     | 47        | 25.68%  |
| 0     | 2         | 1.09%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 135       | 73.37%  |
| Yes  | 49        | 26.63%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 92        | 56.1%   |
| Realtek Semiconductor           | 18        | 10.98%  |
| Lite-On Technology              | 10        | 6.1%    |
| Qualcomm Atheros Communications | 9         | 5.49%   |
| IMC Networks                    | 9         | 5.49%   |
| Foxconn / Hon Hai               | 9         | 5.49%   |
| Broadcom                        | 6         | 3.66%   |
| Apple                           | 6         | 3.66%   |
| Toshiba                         | 1         | 0.61%   |
| Realtek                         | 1         | 0.61%   |
| Ralink                          | 1         | 0.61%   |
| MediaTek                        | 1         | 0.61%   |
| Foxconn International           | 1         | 0.61%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                | 32        | 19.51%  |
| Intel AX201 Bluetooth                             | 22        | 13.41%  |
| Realtek Bluetooth Radio                           | 15        | 9.15%   |
| Intel AX200 Bluetooth                             | 13        | 7.93%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)    | 12        | 7.32%   |
| Qualcomm Atheros  Bluetooth Device                | 5         | 3.05%   |
| Intel Bluetooth Device                            | 5         | 3.05%   |
| Foxconn / Hon Hai Wireless_Device                 | 5         | 3.05%   |
| Apple Bluetooth Host Controller                   | 5         | 3.05%   |
| IMC Networks Wireless_Device                      | 4         | 2.44%   |
| IMC Networks Bluetooth Radio                      | 4         | 2.44%   |
| Intel AX210 Bluetooth                             | 3         | 1.83%   |
| Realtek  Bluetooth 4.2 Adapter                    | 2         | 1.22%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0             | 2         | 1.22%   |
| Lite-On Wireless_Device                           | 2         | 1.22%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth        | 2         | 1.22%   |
| Lite-On Bluetooth Device                          | 2         | 1.22%   |
| Lite-On Atheros AR3012 Bluetooth                  | 2         | 1.22%   |
| Intel Wireless-AC 9260 Bluetooth Adapter          | 2         | 1.22%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth     | 2         | 1.22%   |
| Toshiba Askey Bluetooth Module                    | 1         | 0.61%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter           | 1         | 0.61%   |
| Realtek 802.11ac WLAN Adapter                     | 1         | 0.61%   |
| Ralink RT3290 Bluetooth                           | 1         | 0.61%   |
| Qualcomm Atheros Bluetooth (AR3011)               | 1         | 0.61%   |
| Qualcomm Atheros AR9462 Bluetooth                 | 1         | 0.61%   |
| MediaTek Wireless_Device                          | 1         | 0.61%   |
| Lite-On Bluetooth Radio                           | 1         | 0.61%   |
| Lite-On BCM43142A0                                | 1         | 0.61%   |
| Intel Wireless-AC 3168 Bluetooth                  | 1         | 0.61%   |
| Intel Centrino Bluetooth Wireless Transceiver     | 1         | 0.61%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter  | 1         | 0.61%   |
| IMC Networks Bluetooth Device                     | 1         | 0.61%   |
| Foxconn International BCM43142A0 Bluetooth module | 1         | 0.61%   |
| Foxconn / Hon Hai BT                              | 1         | 0.61%   |
| Foxconn / Hon Hai BCM43142A0 broadcom bluetooth   | 1         | 0.61%   |
| Broadcom HP Portable SoftSailing                  | 1         | 0.61%   |
| Broadcom HP Portable Bumble Bee                   | 1         | 0.61%   |
| Broadcom BCM43142A0 Bluetooth Device              | 1         | 0.61%   |
| Broadcom BCM43142A0 Bluetooth 4.0                 | 1         | 0.61%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 128       | 47.94%  |
| Nvidia                 | 61        | 22.85%  |
| AMD                    | 61        | 22.85%  |
| C-Media Electronics    | 3         | 1.12%   |
| TTGK Technology        | 2         | 0.75%   |
| Sony                   | 2         | 0.75%   |
| SteelSeries ApS        | 1         | 0.37%   |
| Samsung Electronics    | 1         | 0.37%   |
| Logitech               | 1         | 0.37%   |
| Lenovo                 | 1         | 0.37%   |
| Hewlett-Packard        | 1         | 0.37%   |
| GN Netcom              | 1         | 0.37%   |
| Generalplus Technology | 1         | 0.37%   |
| Corsair                | 1         | 0.37%   |
| Blue Microphones       | 1         | 0.37%   |
| ASUSTek Computer       | 1         | 0.37%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 45        | 13.72%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 22        | 6.71%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 14        | 4.27%   |
| Intel Comet Lake PCH cAVS                                                  | 14        | 4.27%   |
| Intel Haswell-ULT HD Audio Controller                                      | 13        | 3.96%   |
| Intel Cannon Lake PCH cAVS                                                 | 13        | 3.96%   |
| Intel 8 Series HD Audio Controller                                         | 13        | 3.96%   |
| Intel Sunrise Point-LP HD Audio                                            | 12        | 3.66%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11        | 3.35%   |
| Nvidia GA106 High Definition Audio Controller                              | 9         | 2.74%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 8         | 2.44%   |
| Nvidia TU106 High Definition Audio Controller                              | 7         | 2.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 7         | 2.13%   |
| Intel CM238 HD Audio Controller                                            | 7         | 2.13%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 2.13%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7         | 2.13%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 7         | 2.13%   |
| Nvidia GA104 High Definition Audio Controller                              | 5         | 1.52%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 1.52%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 5         | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 1.52%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.22%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 4         | 1.22%   |
| Nvidia TU116 High Definition Audio Controller                              | 3         | 0.91%   |
| Nvidia TU104 HD Audio Controller                                           | 3         | 0.91%   |
| Nvidia Audio device                                                        | 3         | 0.91%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 0.91%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 0.91%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 3         | 0.91%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 3         | 0.91%   |
| AMD Kabini HDMI/DP Audio                                                   | 3         | 0.91%   |
| AMD FCH Azalia Controller                                                  | 3         | 0.91%   |
| TTGK Technology Audio                                                      | 2         | 0.61%   |
| Sony DualSense wireless controller (PS5)                                   | 2         | 0.61%   |
| Nvidia MCP79 High Definition Audio                                         | 2         | 0.61%   |
| Nvidia GP106 High Definition Audio Controller                              | 2         | 0.61%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.61%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 2         | 0.61%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 2         | 0.61%   |
| Intel Broadwell-U Audio Controller                                         | 2         | 0.61%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 20        | 37.74%  |
| SK hynix            | 11        | 20.75%  |
| Micron Technology   | 11        | 20.75%  |
| Kingston            | 3         | 5.66%   |
| Unknown (ABCD)      | 2         | 3.77%   |
| Transcend           | 1         | 1.89%   |
| Team                | 1         | 1.89%   |
| Nanya Technology    | 1         | 1.89%   |
| Elpida              | 1         | 1.89%   |
| Crucial             | 1         | 1.89%   |
| Corsair             | 1         | 1.89%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 5.26%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 3.51%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 3.51%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 3.51%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 3.51%   |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 2         | 3.51%   |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s          | 2         | 3.51%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 3.51%   |
| Transcend RAM JM2666HSH-4G 4GB SODIMM DDR4 2667MT/s              | 1         | 1.75%   |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 1.75%   |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 1         | 1.75%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.75%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.75%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.75%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.75%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.75%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.75%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.75%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.75%   |
| SK hynix RAM HMA425S6AFR6N-UH 2GB SODIMM DDR4 2400MT/s           | 1         | 1.75%   |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 1.75%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.75%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.75%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 1.75%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.75%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.75%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.75%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 1         | 1.75%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 1         | 1.75%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.75%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 1         | 1.75%   |
| Samsung RAM M4 70T5663RZ3-CF7 2GB SODIMM DDR 975MT/s             | 1         | 1.75%   |
| Samsung RAM K4UBE3D4AA-MGCR 8GB SODIMM LPDDR4 4266MT/s           | 1         | 1.75%   |
| Nanya RAM M2S4G64CB8HG4N-DI 4GB SODIMM DDR3 1600MT/s             | 1         | 1.75%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                       | 1         | 1.75%   |
| Micron RAM Module 2GB Row Of Chips 6400MT/s                      | 1         | 1.75%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.75%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.75%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 1         | 1.75%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 1         | 1.75%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 28        | 66.67%  |
| DDR3    | 5         | 11.9%   |
| LPDDR4  | 4         | 9.52%   |
| DDR5    | 3         | 7.14%   |
| DDR2    | 1         | 2.38%   |
| Unknown | 1         | 2.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 38        | 86.36%  |
| Row Of Chips | 6         | 13.64%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 24        | 52.17%  |
| 4096  | 9         | 19.57%  |
| 16384 | 6         | 13.04%  |
| 2048  | 4         | 8.7%    |
| 32768 | 3         | 6.52%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 17        | 37.78%  |
| 2667  | 10        | 22.22%  |
| 1600  | 4         | 8.89%   |
| 4800  | 3         | 6.67%   |
| 2400  | 3         | 6.67%   |
| 3266  | 2         | 4.44%   |
| 6400  | 1         | 2.22%   |
| 4267  | 1         | 2.22%   |
| 4266  | 1         | 2.22%   |
| 2133  | 1         | 2.22%   |
| 1333  | 1         | 2.22%   |
| 975   | 1         | 2.22%   |

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
| Chicony Electronics                    | 37        | 22.7%   |
| IMC Networks                           | 25        | 15.34%  |
| Sunplus Innovation Technology          | 10        | 6.13%   |
| Realtek Semiconductor                  | 10        | 6.13%   |
| Quanta                                 | 9         | 5.52%   |
| Syntek                                 | 8         | 4.91%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 4.91%   |
| Acer                                   | 8         | 4.91%   |
| Microdia                               | 7         | 4.29%   |
| Apple                                  | 6         | 3.68%   |
| Sonix Technology                       | 5         | 3.07%   |
| Bison Electronics                      | 5         | 3.07%   |
| Suyin                                  | 4         | 2.45%   |
| Luxvisions Innotech Limited            | 4         | 2.45%   |
| Logitech                               | 4         | 2.45%   |
| Lite-On Technology                     | 4         | 2.45%   |
| SunplusIT                              | 2         | 1.23%   |
| Z-Star Microelectronics                | 1         | 0.61%   |
| Tobii Technology AB                    | 1         | 0.61%   |
| Silicon Motion                         | 1         | 0.61%   |
| Samsung Electronics                    | 1         | 0.61%   |
| Intel                                  | 1         | 0.61%   |
| Importek                               | 1         | 0.61%   |
| Goodong Industry                       | 1         | 0.61%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 12        | 7.32%   |
| Chicony Integrated Camera                           | 9         | 5.49%   |
| Syntek Integrated Camera                            | 6         | 3.66%   |
| IMC Networks Integrated Camera                      | 6         | 3.66%   |
| Chicony HD WebCam                                   | 6         | 3.66%   |
| Sunplus Integrated_Webcam_HD                        | 5         | 3.05%   |
| Microdia Integrated_Webcam_HD                       | 4         | 2.44%   |
| Sonix USB2.0 HD UVC WebCam                          | 3         | 1.83%   |
| Realtek USB Camera                                  | 3         | 1.83%   |
| Realtek Integrated_Webcam_HD                        | 3         | 1.83%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 3         | 1.83%   |
| Chicony USB 2.0 Camera                              | 3         | 1.83%   |
| Chicony HP Truevision HD                            | 3         | 1.83%   |
| Bison HD Webcam                                     | 3         | 1.83%   |
| Acer Integrated Camera                              | 3         | 1.83%   |
| Sunplus HD WebCam                                   | 2         | 1.22%   |
| Sonix USB2.0 FHD UVC WebCam                         | 2         | 1.22%   |
| Quanta HD Webcam                                    | 2         | 1.22%   |
| Quanta HD User Facing                               | 2         | 1.22%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 1.22%   |
| Lite-On HP HD Webcam                                | 2         | 1.22%   |
| Lite-On HP HD Camera                                | 2         | 1.22%   |
| Chicony USB2.0 HD UVC WebCam                        | 2         | 1.22%   |
| Chicony USB2.0 Camera                               | 2         | 1.22%   |
| Chicony EasyCamera                                  | 2         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 2         | 1.22%   |
| Apple FaceTime HD Camera                            | 2         | 1.22%   |
| Apple Built-in iSight                               | 2         | 1.22%   |
| Acer Lenovo Integrated Webcam                       | 2         | 1.22%   |
| Z-Star Namuga 1.3M Webcam                           | 1         | 0.61%   |
| Tobii AB EyeChip                                    | 1         | 0.61%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.61%   |
| Syntek EasyCamera                                   | 1         | 0.61%   |
| Suyin Integrated_Webcam_HD                          | 1         | 0.61%   |
| Suyin HP Wide Vision FHD Camera                     | 1         | 0.61%   |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 0.61%   |
| Suyin HP Truevision HD                              | 1         | 0.61%   |
| SunplusIT USB camera                                | 1         | 0.61%   |
| SunplusIT MTD camera                                | 1         | 0.61%   |

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
| 0     | 123       | 66.13%  |
| 1     | 47        | 25.27%  |
| 2     | 15        | 8.06%   |
| 3     | 1         | 0.54%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 27        | 33.33%  |
| Graphics card            | 20        | 24.69%  |
| Multimedia controller    | 16        | 19.75%  |
| Net/wireless             | 13        | 16.05%  |
| Bluetooth                | 2         | 2.47%   |
| Modem                    | 1         | 1.23%   |
| Communication controller | 1         | 1.23%   |
| Chipcard                 | 1         | 1.23%   |

