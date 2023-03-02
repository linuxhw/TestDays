Kubuntu - Tested Hardware & Statistics (Notebooks)
--------------------------------------------------

A project to collect tested hardware configurations for Kubuntu.

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

Total: 2676

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | XPS 15 9520                 | [ecfa5f6c27](https://linux-hardware.org/?probe=ecfa5f6c27) | Mar 01, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [41439f6b61](https://linux-hardware.org/?probe=41439f6b61) | Feb 28, 2023 |
| Dell          | Latitude 5530               | [f892221e4c](https://linux-hardware.org/?probe=f892221e4c) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [003aa3d3e9](https://linux-hardware.org/?probe=003aa3d3e9) | Feb 27, 2023 |
| HP            | EliteBook 835 G8 Noteboo... | [aa26becbb1](https://linux-hardware.org/?probe=aa26becbb1) | Feb 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ad20f98122](https://linux-hardware.org/?probe=ad20f98122) | Feb 27, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [a2af33e0e3](https://linux-hardware.org/?probe=a2af33e0e3) | Feb 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [a5f5bdc903](https://linux-hardware.org/?probe=a5f5bdc903) | Feb 26, 2023 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | [d6e0c6c0ac](https://linux-hardware.org/?probe=d6e0c6c0ac) | Feb 26, 2023 |
| Digibras      | NH4CU03                     | [8bfe7e434d](https://linux-hardware.org/?probe=8bfe7e434d) | Feb 26, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [b410d220e6](https://linux-hardware.org/?probe=b410d220e6) | Feb 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [67b8b5ad09](https://linux-hardware.org/?probe=67b8b5ad09) | Feb 26, 2023 |
| HP            | G62                         | [871207750c](https://linux-hardware.org/?probe=871207750c) | Feb 25, 2023 |
| HP            | Pavilion Laptop 15-cs3xx... | [0b9491b3a0](https://linux-hardware.org/?probe=0b9491b3a0) | Feb 25, 2023 |
| System76      | Gazelle                     | [64fcb063eb](https://linux-hardware.org/?probe=64fcb063eb) | Feb 25, 2023 |
| Alienware     | m15 R7 AMD                  | [0a44dcc29e](https://linux-hardware.org/?probe=0a44dcc29e) | Feb 24, 2023 |
| Dell          | Latitude 5530               | [8ad26dd8a0](https://linux-hardware.org/?probe=8ad26dd8a0) | Feb 24, 2023 |
| Alienware     | m15 R7 AMD                  | [3ba05d49d8](https://linux-hardware.org/?probe=3ba05d49d8) | Feb 24, 2023 |
| MSI           | GE75 Raider 9SE             | [6d0782da8e](https://linux-hardware.org/?probe=6d0782da8e) | Feb 24, 2023 |
| Dell          | System Inspiron N7110       | [4a3b8e0755](https://linux-hardware.org/?probe=4a3b8e0755) | Feb 22, 2023 |
| Acer          | Nitro AN515-55              | [acb8644ede](https://linux-hardware.org/?probe=acb8644ede) | Feb 21, 2023 |
| Lenovo        | ThinkPad T440p 20AWS3E20... | [012b54b31c](https://linux-hardware.org/?probe=012b54b31c) | Feb 21, 2023 |
| Dell          | Inspiron 7400               | [0d286f12f4](https://linux-hardware.org/?probe=0d286f12f4) | Feb 21, 2023 |
| GPU Compan... | GWTC116-2                   | [5fa20b737f](https://linux-hardware.org/?probe=5fa20b737f) | Feb 21, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [6033e6cb63](https://linux-hardware.org/?probe=6033e6cb63) | Feb 20, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [63de5bef96](https://linux-hardware.org/?probe=63de5bef96) | Feb 20, 2023 |
| Apple         | MacBookAir3,1               | [1e0de945b7](https://linux-hardware.org/?probe=1e0de945b7) | Feb 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [7e5327c1ed](https://linux-hardware.org/?probe=7e5327c1ed) | Feb 19, 2023 |
| HP            | ProBook 4730s               | [99232fe32d](https://linux-hardware.org/?probe=99232fe32d) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | X555LJ                      | [93f3ae1f77](https://linux-hardware.org/?probe=93f3ae1f77) | Feb 19, 2023 |
| HP            | Victus by Laptop 16z-e10... | [a48460122c](https://linux-hardware.org/?probe=a48460122c) | Feb 19, 2023 |
| Acer          | Aspire A515-46              | [46a8b61785](https://linux-hardware.org/?probe=46a8b61785) | Feb 18, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [eb64c99981](https://linux-hardware.org/?probe=eb64c99981) | Feb 18, 2023 |
| Dell          | System Inspiron N7110       | [542553dd55](https://linux-hardware.org/?probe=542553dd55) | Feb 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | [4baabf8013](https://linux-hardware.org/?probe=4baabf8013) | Feb 18, 2023 |
| Dell          | Precision 7540              | [2a511e3e78](https://linux-hardware.org/?probe=2a511e3e78) | Feb 17, 2023 |
| Alienware     | 17 R2                       | [a70da6118b](https://linux-hardware.org/?probe=a70da6118b) | Feb 16, 2023 |
| Dell          | System Inspiron N7110       | [a59b4a2c12](https://linux-hardware.org/?probe=a59b4a2c12) | Feb 16, 2023 |
| ASUSTek       | X75VD                       | [81c64d5916](https://linux-hardware.org/?probe=81c64d5916) | Feb 16, 2023 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | [6f0ca25023](https://linux-hardware.org/?probe=6f0ca25023) | Feb 16, 2023 |
| Lenovo        | ThinkPad L13 20R30006PB     | [aad1f06bb9](https://linux-hardware.org/?probe=aad1f06bb9) | Feb 16, 2023 |
| Acer          | Aspire A717-71G             | [488a80bcda](https://linux-hardware.org/?probe=488a80bcda) | Feb 16, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [a16c82308f](https://linux-hardware.org/?probe=a16c82308f) | Feb 16, 2023 |
| Lenovo        | ThinkPad E14 20RAS1AQ00     | [b534643d92](https://linux-hardware.org/?probe=b534643d92) | Feb 16, 2023 |
| Dell          | G15 5515                    | [17ff15f50e](https://linux-hardware.org/?probe=17ff15f50e) | Feb 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | [043e92c2ee](https://linux-hardware.org/?probe=043e92c2ee) | Feb 15, 2023 |
| HP            | Pavilion 11 x360 PC         | [b2a1267353](https://linux-hardware.org/?probe=b2a1267353) | Feb 15, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [832920f31b](https://linux-hardware.org/?probe=832920f31b) | Feb 14, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | [e6f972234b](https://linux-hardware.org/?probe=e6f972234b) | Feb 14, 2023 |
| HUAWEI        | CREM-WXX9                   | [02ae55d12c](https://linux-hardware.org/?probe=02ae55d12c) | Feb 13, 2023 |
| Dell          | Inspiron 7400               | [4cc741a70a](https://linux-hardware.org/?probe=4cc741a70a) | Feb 13, 2023 |
| Acer          | Swift SF314-512             | [08a9c049a1](https://linux-hardware.org/?probe=08a9c049a1) | Feb 13, 2023 |
| HP            | ProBook 6470b               | [e747086309](https://linux-hardware.org/?probe=e747086309) | Feb 13, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [920b8786c6](https://linux-hardware.org/?probe=920b8786c6) | Feb 13, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | [23eec2d2bc](https://linux-hardware.org/?probe=23eec2d2bc) | Feb 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [50163cfc72](https://linux-hardware.org/?probe=50163cfc72) | Feb 12, 2023 |
| HP            | ProBook 440 G5              | [566c6a5316](https://linux-hardware.org/?probe=566c6a5316) | Feb 12, 2023 |
| HP            | ProBook 440 G5              | [a833fa9a0c](https://linux-hardware.org/?probe=a833fa9a0c) | Feb 12, 2023 |
| HP            | 255 G8 Notebook PC          | [3542104e07](https://linux-hardware.org/?probe=3542104e07) | Feb 12, 2023 |
| MSI           | GE62VR 6RF                  | [89c148a5f9](https://linux-hardware.org/?probe=89c148a5f9) | Feb 12, 2023 |
| Lenovo        | ThinkPad T450 20BV0001US    | [d149fd1ed6](https://linux-hardware.org/?probe=d149fd1ed6) | Feb 12, 2023 |
| Google        | Blooguard                   | [b4cdae3965](https://linux-hardware.org/?probe=b4cdae3965) | Feb 11, 2023 |
| Gigabyte      | GB-BKi5(H)A-7200            | [57ff1b0fe3](https://linux-hardware.org/?probe=57ff1b0fe3) | Feb 11, 2023 |
| HP            | Notebook                    | [94c42af775](https://linux-hardware.org/?probe=94c42af775) | Feb 11, 2023 |
| Lenovo        | ZHAOYANG K4e-ITL 82Q1       | [4ab5181634](https://linux-hardware.org/?probe=4ab5181634) | Feb 11, 2023 |
| HP            | Notebook                    | [e19e0407ec](https://linux-hardware.org/?probe=e19e0407ec) | Feb 11, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [3af9191e4f](https://linux-hardware.org/?probe=3af9191e4f) | Feb 11, 2023 |
| HP            | Notebook                    | [4daf49165c](https://linux-hardware.org/?probe=4daf49165c) | Feb 10, 2023 |
| HP            | Laptop 15-da2xxx            | [200150e4e3](https://linux-hardware.org/?probe=200150e4e3) | Feb 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | [e3ea6ad8da](https://linux-hardware.org/?probe=e3ea6ad8da) | Feb 10, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [5b22c1a20a](https://linux-hardware.org/?probe=5b22c1a20a) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | [ccbec1376d](https://linux-hardware.org/?probe=ccbec1376d) | Feb 09, 2023 |
| MSI           | GS73 Stealth 8RF            | [0d5a38a089](https://linux-hardware.org/?probe=0d5a38a089) | Feb 09, 2023 |
| ASUSTek       | ASUS EXPERTBOOK P2451FA_... | [b79b2f3f75](https://linux-hardware.org/?probe=b79b2f3f75) | Feb 09, 2023 |
| Dell          | XPS 17 9720                 | [3d1b70c4af](https://linux-hardware.org/?probe=3d1b70c4af) | Feb 08, 2023 |
| Acer          | Swift SF314-512             | [556b064487](https://linux-hardware.org/?probe=556b064487) | Feb 07, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [c454139724](https://linux-hardware.org/?probe=c454139724) | Feb 06, 2023 |
| Lenovo        | ThinkPad T470 20HES3X300    | [6a77ec4c4f](https://linux-hardware.org/?probe=6a77ec4c4f) | Feb 06, 2023 |
| Acer          | Nitro AN515-45              | [bb420e8f71](https://linux-hardware.org/?probe=bb420e8f71) | Feb 05, 2023 |
| HP            | Pavilion Aero Laptop 13-... | [ce7bdb0a98](https://linux-hardware.org/?probe=ce7bdb0a98) | Feb 05, 2023 |
| Acer          | Swift SFX14-41G             | [5f59acbf0d](https://linux-hardware.org/?probe=5f59acbf0d) | Feb 05, 2023 |
| HP            | G60                         | [518195af9f](https://linux-hardware.org/?probe=518195af9f) | Feb 04, 2023 |
| Lenovo        | IdeaPad U310 Touch          | [6fd17687a4](https://linux-hardware.org/?probe=6fd17687a4) | Feb 04, 2023 |
| Acer          | Nitro AN515-55              | [27d852788e](https://linux-hardware.org/?probe=27d852788e) | Feb 03, 2023 |
| Acer          | Nitro AN515-55              | [2ed6b9969d](https://linux-hardware.org/?probe=2ed6b9969d) | Feb 03, 2023 |
| ASUSTek       | X550JK                      | [c42e4eb249](https://linux-hardware.org/?probe=c42e4eb249) | Feb 03, 2023 |
| Chuwi         | Hi10 Go                     | [a1b6911dc1](https://linux-hardware.org/?probe=a1b6911dc1) | Feb 02, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | [a84d546f50](https://linux-hardware.org/?probe=a84d546f50) | Feb 02, 2023 |
| Lenovo        | ThinkPad T460 20FMS66R00    | [293690383a](https://linux-hardware.org/?probe=293690383a) | Feb 02, 2023 |
| Dell          | Vostro 15-3568              | [caf63a9d0f](https://linux-hardware.org/?probe=caf63a9d0f) | Feb 02, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | [690d45db9f](https://linux-hardware.org/?probe=690d45db9f) | Feb 02, 2023 |
| Lenovo        | ThinkPad W530 2463A49       | [374c21a672](https://linux-hardware.org/?probe=374c21a672) | Feb 02, 2023 |
| Dell          | Inspiron 5570               | [d186290a3f](https://linux-hardware.org/?probe=d186290a3f) | Feb 01, 2023 |
| Dell          | Precision 7540              | [1d0d197808](https://linux-hardware.org/?probe=1d0d197808) | Feb 01, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [7e78833b8b](https://linux-hardware.org/?probe=7e78833b8b) | Feb 01, 2023 |
| Medion        | E15410                      | [24135c324e](https://linux-hardware.org/?probe=24135c324e) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [ebbe861495](https://linux-hardware.org/?probe=ebbe861495) | Jan 31, 2023 |
| HP            | Notebook                    | [f352309997](https://linux-hardware.org/?probe=f352309997) | Jan 31, 2023 |
| Google        | Lillipup                    | [45f9b8c3cf](https://linux-hardware.org/?probe=45f9b8c3cf) | Jan 31, 2023 |
| Acer          | Aspire AV14-51              | [fa801eea4b](https://linux-hardware.org/?probe=fa801eea4b) | Jan 31, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | [949ea399fb](https://linux-hardware.org/?probe=949ea399fb) | Jan 31, 2023 |
| Framework     | Laptop (12th Gen Intel C... | [96671141f9](https://linux-hardware.org/?probe=96671141f9) | Jan 30, 2023 |
| MSI           | GS66 Stealth 10SE           | [bf112866e3](https://linux-hardware.org/?probe=bf112866e3) | Jan 30, 2023 |
| MSI           | Bravo 15 B5DD               | [b3c357b53b](https://linux-hardware.org/?probe=b3c357b53b) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [942c001b11](https://linux-hardware.org/?probe=942c001b11) | Jan 30, 2023 |
| Acer          | Swift SF114-31              | [9d7f73242e](https://linux-hardware.org/?probe=9d7f73242e) | Jan 30, 2023 |
| ASUSTek       | ROG Strix G513RW_G513RW     | [2f0ffeb3be](https://linux-hardware.org/?probe=2f0ffeb3be) | Jan 29, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| Lenovo        | IdeaPad 720S-14IKB 81BD     | [50eb066d41](https://linux-hardware.org/?probe=50eb066d41) | Jan 29, 2023 |
| Acer          | Nitro AN517-41              | [ecb7c49d2e](https://linux-hardware.org/?probe=ecb7c49d2e) | Jan 29, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | [175211d52c](https://linux-hardware.org/?probe=175211d52c) | Jan 29, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a011ba3b9e](https://linux-hardware.org/?probe=a011ba3b9e) | Jan 28, 2023 |
| Dell          | Precision 7730              | [058f16ac84](https://linux-hardware.org/?probe=058f16ac84) | Jan 28, 2023 |
| Dell          | Inspiron 5593               | [36db3e5d78](https://linux-hardware.org/?probe=36db3e5d78) | Jan 27, 2023 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [b265f91d10](https://linux-hardware.org/?probe=b265f91d10) | Jan 27, 2023 |
| HP            | Laptop 15-da0xxx            | [32a666b611](https://linux-hardware.org/?probe=32a666b611) | Jan 27, 2023 |
| ASUSTek       | GL503VD                     | [f4095c61ff](https://linux-hardware.org/?probe=f4095c61ff) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [7273b8320c](https://linux-hardware.org/?probe=7273b8320c) | Jan 26, 2023 |
| Acer          | Nitro AN517-55              | [2de4e60fef](https://linux-hardware.org/?probe=2de4e60fef) | Jan 26, 2023 |
| Medion        | E15410                      | [5ba9ffd6a8](https://linux-hardware.org/?probe=5ba9ffd6a8) | Jan 26, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [7403ca2f73](https://linux-hardware.org/?probe=7403ca2f73) | Jan 25, 2023 |
| Lenovo        | ThinkPad L380 20M6S2YE00    | [e6c626133e](https://linux-hardware.org/?probe=e6c626133e) | Jan 25, 2023 |
| TrekStor      | Surfbook A13B               | [4306d9ba1c](https://linux-hardware.org/?probe=4306d9ba1c) | Jan 25, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [34882391f3](https://linux-hardware.org/?probe=34882391f3) | Jan 25, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [18d42efe40](https://linux-hardware.org/?probe=18d42efe40) | Jan 24, 2023 |
| Acer          | Predator G3-571             | [549910b197](https://linux-hardware.org/?probe=549910b197) | Jan 24, 2023 |
| Dell          | Latitude 5491               | [37746d7f71](https://linux-hardware.org/?probe=37746d7f71) | Jan 24, 2023 |
| Medion        | E15410                      | [f7e27f2ba9](https://linux-hardware.org/?probe=f7e27f2ba9) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [4f83721cab](https://linux-hardware.org/?probe=4f83721cab) | Jan 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [9e12a145fd](https://linux-hardware.org/?probe=9e12a145fd) | Jan 23, 2023 |
| HP            | ProBook 6470b               | [3319221b9c](https://linux-hardware.org/?probe=3319221b9c) | Jan 23, 2023 |
| MACHENIKE     | MACHCREATOR-16              | [df35617170](https://linux-hardware.org/?probe=df35617170) | Jan 22, 2023 |
| Acer          | Aspire E1-571               | [8d5c313d43](https://linux-hardware.org/?probe=8d5c313d43) | Jan 22, 2023 |
| HP            | ProBook 6570b               | [3bc0488b6d](https://linux-hardware.org/?probe=3bc0488b6d) | Jan 22, 2023 |
| Dell          | Latitude E6430s             | [8f9185a327](https://linux-hardware.org/?probe=8f9185a327) | Jan 22, 2023 |
| Carbon Sys... | Iridium 14                  | [7fcc79f37c](https://linux-hardware.org/?probe=7fcc79f37c) | Jan 22, 2023 |
| Dell          | Vostro 1014                 | [f7ff3312f2](https://linux-hardware.org/?probe=f7ff3312f2) | Jan 21, 2023 |
| Acer          | TravelMate B118-M           | [029850a46e](https://linux-hardware.org/?probe=029850a46e) | Jan 21, 2023 |
| Dell          | Vostro 1014                 | [724939f0cf](https://linux-hardware.org/?probe=724939f0cf) | Jan 21, 2023 |
| MSI           | Prestige 15 A12SC           | [b368e80a36](https://linux-hardware.org/?probe=b368e80a36) | Jan 21, 2023 |
| HP            | Laptop 15-ef2xxx            | [732a1b992a](https://linux-hardware.org/?probe=732a1b992a) | Jan 20, 2023 |
| Apple         | MacBookPro11,3              | [28b4d041ad](https://linux-hardware.org/?probe=28b4d041ad) | Jan 20, 2023 |
| Dell          | Latitude 5320               | [aaf625ee63](https://linux-hardware.org/?probe=aaf625ee63) | Jan 20, 2023 |
| Sony          | SVE1513B4E                  | [cbd9f98f30](https://linux-hardware.org/?probe=cbd9f98f30) | Jan 20, 2023 |
| Dell          | G3 3779                     | [c4c13ca86b](https://linux-hardware.org/?probe=c4c13ca86b) | Jan 19, 2023 |
| HP            | Laptop 15-ef2xxx            | [d9e9f47ad4](https://linux-hardware.org/?probe=d9e9f47ad4) | Jan 19, 2023 |
| HP            | Notebook                    | [1c935be3b1](https://linux-hardware.org/?probe=1c935be3b1) | Jan 18, 2023 |
| ASUSTek       | Zenbook UM6702RC_RM6702R... | [21ed6bd75d](https://linux-hardware.org/?probe=21ed6bd75d) | Jan 17, 2023 |
| HP            | Laptop 17-by3xxx            | [542c3d1ef4](https://linux-hardware.org/?probe=542c3d1ef4) | Jan 16, 2023 |
| Acer          | Aspire A515-56              | [3f24b17bd8](https://linux-hardware.org/?probe=3f24b17bd8) | Jan 16, 2023 |
| Acer          | Aspire V3-571G              | [3715650f46](https://linux-hardware.org/?probe=3715650f46) | Jan 16, 2023 |
| Acer          | Swift SF113-31              | [de76cee99a](https://linux-hardware.org/?probe=de76cee99a) | Jan 16, 2023 |
| Dynabook      | Satellite Pro C50-J         | [ba8e771128](https://linux-hardware.org/?probe=ba8e771128) | Jan 15, 2023 |
| Notebook      | W35xSS_370SS                | [2337667e0f](https://linux-hardware.org/?probe=2337667e0f) | Jan 15, 2023 |
| Acer          | Nitro AN515-43              | [4621c0d31b](https://linux-hardware.org/?probe=4621c0d31b) | Jan 15, 2023 |
| HUAWEI        | KLVL-WXX9                   | [2687f89612](https://linux-hardware.org/?probe=2687f89612) | Jan 14, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | [3a97589bc9](https://linux-hardware.org/?probe=3a97589bc9) | Jan 12, 2023 |
| HP            | 255 G8 Notebook PC          | [1b1fee733e](https://linux-hardware.org/?probe=1b1fee733e) | Jan 12, 2023 |
| Dell          | Latitude 3420               | [53b3f46e20](https://linux-hardware.org/?probe=53b3f46e20) | Jan 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E210... | [ed648f1f72](https://linux-hardware.org/?probe=ed648f1f72) | Jan 12, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [1987221c12](https://linux-hardware.org/?probe=1987221c12) | Jan 12, 2023 |
| MSI           | Bravo 17 A4DDK              | [ca27b9dd46](https://linux-hardware.org/?probe=ca27b9dd46) | Jan 10, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [c5e0e8163f](https://linux-hardware.org/?probe=c5e0e8163f) | Jan 10, 2023 |
| Google        | Rammus                      | [489d09eaa7](https://linux-hardware.org/?probe=489d09eaa7) | Jan 10, 2023 |
| Dell          | XPS 15 9560                 | [b9df733a47](https://linux-hardware.org/?probe=b9df733a47) | Jan 10, 2023 |
| Dell          | XPS 15 9560                 | [75209e7521](https://linux-hardware.org/?probe=75209e7521) | Jan 10, 2023 |
| HP            | ProBook 6570b               | [e5c0ea26d1](https://linux-hardware.org/?probe=e5c0ea26d1) | Jan 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [5d3f8e9948](https://linux-hardware.org/?probe=5d3f8e9948) | Jan 09, 2023 |
| Dell          | Inspiron 5575               | [5bc41d3659](https://linux-hardware.org/?probe=5bc41d3659) | Jan 09, 2023 |
| Dell          | Inspiron 5570               | [4ebc1e97c5](https://linux-hardware.org/?probe=4ebc1e97c5) | Jan 07, 2023 |
| Dell          | Inspiron 5570               | [86b0308f38](https://linux-hardware.org/?probe=86b0308f38) | Jan 07, 2023 |
| Acer          | Aspire A515-56              | [fc7a1958c4](https://linux-hardware.org/?probe=fc7a1958c4) | Jan 07, 2023 |
| HP            | EliteBook 845 14 inch G9... | [929ff5acbb](https://linux-hardware.org/?probe=929ff5acbb) | Jan 07, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [aae608e132](https://linux-hardware.org/?probe=aae608e132) | Jan 06, 2023 |
| Lenovo        | Legion 5 17ACH6 82K0        | [9a108faf93](https://linux-hardware.org/?probe=9a108faf93) | Jan 06, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [c19db82125](https://linux-hardware.org/?probe=c19db82125) | Jan 05, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | [697abed1c0](https://linux-hardware.org/?probe=697abed1c0) | Jan 05, 2023 |
| Acer          | Swift SF314-71              | [21ebb26df9](https://linux-hardware.org/?probe=21ebb26df9) | Jan 05, 2023 |
| HP            | 250 G4 Notebook PC          | [a6d6683371](https://linux-hardware.org/?probe=a6d6683371) | Jan 04, 2023 |
| HP            | 250 G4 Notebook PC          | [08526a890a](https://linux-hardware.org/?probe=08526a890a) | Jan 04, 2023 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [ace1cd7d4d](https://linux-hardware.org/?probe=ace1cd7d4d) | Jan 04, 2023 |
| Acer          | Aspire M5-583P              | [1182d7305d](https://linux-hardware.org/?probe=1182d7305d) | Jan 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [e24802533e](https://linux-hardware.org/?probe=e24802533e) | Jan 03, 2023 |
| Unknown       | Unknown                     | [7a85f424f5](https://linux-hardware.org/?probe=7a85f424f5) | Jan 03, 2023 |
| HUAWEI        | NBLL-WXX9                   | [7e5acbf050](https://linux-hardware.org/?probe=7e5acbf050) | Jan 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [059e72c9a0](https://linux-hardware.org/?probe=059e72c9a0) | Jan 03, 2023 |
| MSI           | Raider GE76 12UGS           | [8552e25872](https://linux-hardware.org/?probe=8552e25872) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | [2e2e7afb8a](https://linux-hardware.org/?probe=2e2e7afb8a) | Jan 03, 2023 |
| ASUSTek       | G56JR                       | [d8d521b964](https://linux-hardware.org/?probe=d8d521b964) | Jan 03, 2023 |
| Acer          | Aspire M5-481T              | [54bd1d5aae](https://linux-hardware.org/?probe=54bd1d5aae) | Jan 03, 2023 |
| Dell          | Inspiron 5515               | [27a4df28b2](https://linux-hardware.org/?probe=27a4df28b2) | Jan 03, 2023 |
| MSI           | Alpha 17 B5EEK              | [a5881c627c](https://linux-hardware.org/?probe=a5881c627c) | Jan 03, 2023 |
| ASUSTek       | G56JR                       | [ccebb5dd27](https://linux-hardware.org/?probe=ccebb5dd27) | Jan 02, 2023 |
| HP            | ENVY TS 15                  | [3140fe0512](https://linux-hardware.org/?probe=3140fe0512) | Jan 02, 2023 |
| MSI           | Prestige 14 A10RAS          | [fc119df9bc](https://linux-hardware.org/?probe=fc119df9bc) | Jan 02, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | [0fb41a5066](https://linux-hardware.org/?probe=0fb41a5066) | Jan 02, 2023 |
| MSI           | Raider GE67HX 12UGS         | [be85c7b42a](https://linux-hardware.org/?probe=be85c7b42a) | Jan 01, 2023 |
| HP            | Laptop 15-da2xxx            | [a96e5b892b](https://linux-hardware.org/?probe=a96e5b892b) | Jan 01, 2023 |
| Lenovo        | ThinkPad L430 24663D1       | [8eada9744e](https://linux-hardware.org/?probe=8eada9744e) | Jan 01, 2023 |
| Lenovo        | ThinkPad X230 23256N6       | [09d6510700](https://linux-hardware.org/?probe=09d6510700) | Jan 01, 2023 |
| HP            | Notebook                    | [d25df9daf4](https://linux-hardware.org/?probe=d25df9daf4) | Dec 31, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [d326e34afc](https://linux-hardware.org/?probe=d326e34afc) | Dec 31, 2022 |
| Acer          | Aspire A315-41              | [9cddb65ac1](https://linux-hardware.org/?probe=9cddb65ac1) | Dec 30, 2022 |
| Notebook      | P17SM                       | [18605208b6](https://linux-hardware.org/?probe=18605208b6) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1JN0... | [049bc54496](https://linux-hardware.org/?probe=049bc54496) | Dec 30, 2022 |
| ASUSTek       | UX31E                       | [5e6dc18098](https://linux-hardware.org/?probe=5e6dc18098) | Dec 30, 2022 |
| Apple         | MacBookPro14,3              | [fdd6af96b3](https://linux-hardware.org/?probe=fdd6af96b3) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [816ab16fd0](https://linux-hardware.org/?probe=816ab16fd0) | Dec 30, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [43e6103cd0](https://linux-hardware.org/?probe=43e6103cd0) | Dec 29, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [25183d70e2](https://linux-hardware.org/?probe=25183d70e2) | Dec 29, 2022 |
| Carbon Sys... | Iridium 14                  | [d2275f6785](https://linux-hardware.org/?probe=d2275f6785) | Dec 29, 2022 |
| Acer          | Aspire 5742G                | [f58bb411b8](https://linux-hardware.org/?probe=f58bb411b8) | Dec 28, 2022 |
| HP            | EliteBook 745 G3            | [1ca2f43148](https://linux-hardware.org/?probe=1ca2f43148) | Dec 27, 2022 |
| Acer          | Swift SF314-43              | [3d9a51ce6e](https://linux-hardware.org/?probe=3d9a51ce6e) | Dec 27, 2022 |
| MSI           | GP62 7QF                    | [3db82bd91e](https://linux-hardware.org/?probe=3db82bd91e) | Dec 27, 2022 |
| ASUSTek       | X550VXK                     | [301db79821](https://linux-hardware.org/?probe=301db79821) | Dec 27, 2022 |
| HP            | Beats 15                    | [d000f23d61](https://linux-hardware.org/?probe=d000f23d61) | Dec 27, 2022 |
| Dell          | Inspiron 5775               | [cfb1c3fcd6](https://linux-hardware.org/?probe=cfb1c3fcd6) | Dec 26, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNK_PNH_PN... | [792a203576](https://linux-hardware.org/?probe=792a203576) | Dec 26, 2022 |
| Acer          | Aspire A517-53              | [e440a77fa7](https://linux-hardware.org/?probe=e440a77fa7) | Dec 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [0413176ecc](https://linux-hardware.org/?probe=0413176ecc) | Dec 25, 2022 |
| HP            | EliteBook Folio 1040 G3     | [7b8e9fe353](https://linux-hardware.org/?probe=7b8e9fe353) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [f7011844b5](https://linux-hardware.org/?probe=f7011844b5) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [3f1acac04f](https://linux-hardware.org/?probe=3f1acac04f) | Dec 24, 2022 |
| Lenovo        | ThinkPad R61 8918DMG        | [d40595761e](https://linux-hardware.org/?probe=d40595761e) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [e439eb94d4](https://linux-hardware.org/?probe=e439eb94d4) | Dec 24, 2022 |
| Dell          | Latitude 5590               | [816056e28e](https://linux-hardware.org/?probe=816056e28e) | Dec 24, 2022 |
| Lenovo        | ThinkPad T510 4313CTO       | [a3db191efa](https://linux-hardware.org/?probe=a3db191efa) | Dec 24, 2022 |
| Samsung       | 550P5C/550P7C               | [780cc47e7f](https://linux-hardware.org/?probe=780cc47e7f) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [6b09c2afcf](https://linux-hardware.org/?probe=6b09c2afcf) | Dec 23, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [efc1b154fb](https://linux-hardware.org/?probe=efc1b154fb) | Dec 23, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [f2197bb9ec](https://linux-hardware.org/?probe=f2197bb9ec) | Dec 23, 2022 |
| Lenovo        | IdeaPad 700-17ISK 80RV      | [59bf9e85bf](https://linux-hardware.org/?probe=59bf9e85bf) | Dec 22, 2022 |
| HP            | Pavilion dv7                | [5e5eb2c983](https://linux-hardware.org/?probe=5e5eb2c983) | Dec 22, 2022 |
| SGIN          | laptop                      | [33b93cc75b](https://linux-hardware.org/?probe=33b93cc75b) | Dec 22, 2022 |
| Acer          | Nitro AN515-58              | [041cd6f9bd](https://linux-hardware.org/?probe=041cd6f9bd) | Dec 22, 2022 |
| Acer          | Aspire A515-47              | [0ec462e927](https://linux-hardware.org/?probe=0ec462e927) | Dec 21, 2022 |
| Notebook      | NL5xRU                      | [c32538c73b](https://linux-hardware.org/?probe=c32538c73b) | Dec 21, 2022 |
| HP            | Sona                        | [85c88dea70](https://linux-hardware.org/?probe=85c88dea70) | Dec 20, 2022 |
| Timi          | TM1701                      | [49f0865503](https://linux-hardware.org/?probe=49f0865503) | Dec 20, 2022 |
| HP            | Laptop 17-by3xxx            | [5bce63e8cb](https://linux-hardware.org/?probe=5bce63e8cb) | Dec 19, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [60a56500f1](https://linux-hardware.org/?probe=60a56500f1) | Dec 18, 2022 |
| Dell          | Precision 5540              | [0e2ce6eb28](https://linux-hardware.org/?probe=0e2ce6eb28) | Dec 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [fc473cc90f](https://linux-hardware.org/?probe=fc473cc90f) | Dec 17, 2022 |
| Lenovo        | G50-70 20351                | [4d39c63e0a](https://linux-hardware.org/?probe=4d39c63e0a) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| HUAWEI        | BOM-WXX9                    | [a1a11b56d0](https://linux-hardware.org/?probe=a1a11b56d0) | Dec 15, 2022 |
| Lenovo        | ThinkPad T530 24295XU       | [0ebd945403](https://linux-hardware.org/?probe=0ebd945403) | Dec 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [89166d1da4](https://linux-hardware.org/?probe=89166d1da4) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [76c76bdd82](https://linux-hardware.org/?probe=76c76bdd82) | Dec 14, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | [1db7d2fa59](https://linux-hardware.org/?probe=1db7d2fa59) | Dec 14, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [d8d72f23e6](https://linux-hardware.org/?probe=d8d72f23e6) | Dec 14, 2022 |
| Apple         | MacBookPro14,2              | [702a622854](https://linux-hardware.org/?probe=702a622854) | Dec 14, 2022 |
| Lenovo        | ThinkPad T61 7665VJM        | [f1ff113e65](https://linux-hardware.org/?probe=f1ff113e65) | Dec 14, 2022 |
| Fujitsu       | LIFEBOOK E734               | [5ac5b0aaa8](https://linux-hardware.org/?probe=5ac5b0aaa8) | Dec 14, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [c18a20ec35](https://linux-hardware.org/?probe=c18a20ec35) | Dec 13, 2022 |
| Acer          | Nitro AN517-54              | [3896296ad1](https://linux-hardware.org/?probe=3896296ad1) | Dec 12, 2022 |
| Dell          | Precision 5510              | [77b7f6dd95](https://linux-hardware.org/?probe=77b7f6dd95) | Dec 12, 2022 |
| Framework     | Laptop (12th Gen Intel C... | [dfa4685ecc](https://linux-hardware.org/?probe=dfa4685ecc) | Dec 12, 2022 |
| Acer          | Aspire A515-44              | [965817e5f0](https://linux-hardware.org/?probe=965817e5f0) | Dec 11, 2022 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [48e21506f4](https://linux-hardware.org/?probe=48e21506f4) | Dec 11, 2022 |
| HP            | Pavilion g7                 | [94cc8be22c](https://linux-hardware.org/?probe=94cc8be22c) | Dec 11, 2022 |
| Acer          | Predator PH317-52           | [e3236b49d3](https://linux-hardware.org/?probe=e3236b49d3) | Dec 10, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [d28d2da00b](https://linux-hardware.org/?probe=d28d2da00b) | Dec 09, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [c66f0c0c8d](https://linux-hardware.org/?probe=c66f0c0c8d) | Dec 08, 2022 |
| Lenovo        | ThinkPad T420 4236PZ0       | [603c3b47a9](https://linux-hardware.org/?probe=603c3b47a9) | Dec 08, 2022 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | [3a9774bdac](https://linux-hardware.org/?probe=3a9774bdac) | Dec 07, 2022 |
| Monster       | TULPAR T7 V21.6             | [1fb4eaf6d4](https://linux-hardware.org/?probe=1fb4eaf6d4) | Dec 06, 2022 |
| HP            | Beats 15                    | [5a09b2cb1d](https://linux-hardware.org/?probe=5a09b2cb1d) | Dec 06, 2022 |
| HP            | 550                         | [1090513329](https://linux-hardware.org/?probe=1090513329) | Dec 06, 2022 |
| Lenovo        | G700 20251                  | [8d5d04f931](https://linux-hardware.org/?probe=8d5d04f931) | Dec 05, 2022 |
| Lenovo        | G700 20251                  | [4e8f04ce8f](https://linux-hardware.org/?probe=4e8f04ce8f) | Dec 05, 2022 |
| Dell          | Inspiron 7577               | [cb376e265d](https://linux-hardware.org/?probe=cb376e265d) | Dec 05, 2022 |
| HUAWEI        | CREM-WXX9                   | [535444f416](https://linux-hardware.org/?probe=535444f416) | Dec 05, 2022 |
| Monster       | TULPAR T7 V21.6             | [8c2ed08d33](https://linux-hardware.org/?probe=8c2ed08d33) | Dec 04, 2022 |
| Dell          | Vostro 5471                 | [0bad01b327](https://linux-hardware.org/?probe=0bad01b327) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [2147d11bad](https://linux-hardware.org/?probe=2147d11bad) | Dec 04, 2022 |
| Acer          | Aspire VN7-572G             | [5a456d1825](https://linux-hardware.org/?probe=5a456d1825) | Dec 04, 2022 |
| HP            | ProBook 430 G2              | [a66be8f003](https://linux-hardware.org/?probe=a66be8f003) | Dec 03, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | [41824c584f](https://linux-hardware.org/?probe=41824c584f) | Dec 03, 2022 |
| Dell          | Vostro 5481                 | [6c58c07e64](https://linux-hardware.org/?probe=6c58c07e64) | Dec 03, 2022 |
| Dell          | Latitude E6220              | [8c99ad2bde](https://linux-hardware.org/?probe=8c99ad2bde) | Dec 02, 2022 |
| MSI           | Prestige 14 A12UC           | [7d88c55edb](https://linux-hardware.org/?probe=7d88c55edb) | Dec 02, 2022 |
| Google        | Kled                        | [06c52b65d2](https://linux-hardware.org/?probe=06c52b65d2) | Dec 02, 2022 |
| Dell          | XPS 15 9570                 | [867e3d70f0](https://linux-hardware.org/?probe=867e3d70f0) | Dec 02, 2022 |
| HP            | ProBook 450 G2              | [552ac907a0](https://linux-hardware.org/?probe=552ac907a0) | Dec 01, 2022 |
| Haier         | A1420EM                     | [6f18b3c1ce](https://linux-hardware.org/?probe=6f18b3c1ce) | Nov 30, 2022 |
| HUAWEI        | BOD-WXX9                    | [a2b8deb4e3](https://linux-hardware.org/?probe=a2b8deb4e3) | Nov 29, 2022 |
| Dell          | Inspiron 3521               | [2ecbfd5e39](https://linux-hardware.org/?probe=2ecbfd5e39) | Nov 29, 2022 |
| Razer         | Blade Stealth               | [e182c3c739](https://linux-hardware.org/?probe=e182c3c739) | Nov 29, 2022 |
| Acer          | Nitro AN517-51              | [c20385f7bd](https://linux-hardware.org/?probe=c20385f7bd) | Nov 29, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [8f17b6a915](https://linux-hardware.org/?probe=8f17b6a915) | Nov 29, 2022 |
| Dell          | G3 3779                     | [3e85396dae](https://linux-hardware.org/?probe=3e85396dae) | Nov 28, 2022 |
| MSI           | Prestige 15 A12SC           | [af2a404105](https://linux-hardware.org/?probe=af2a404105) | Nov 28, 2022 |
| Gigabyte      | RC14UD                      | [37c4b79c24](https://linux-hardware.org/?probe=37c4b79c24) | Nov 27, 2022 |
| Dell          | G3 3779                     | [2def46f37c](https://linux-hardware.org/?probe=2def46f37c) | Nov 27, 2022 |
| Lenovo        | ThinkPad T430 2349DS5       | [f52677ec2e](https://linux-hardware.org/?probe=f52677ec2e) | Nov 27, 2022 |
| Monster       | TULPAR T7                   | [6634421091](https://linux-hardware.org/?probe=6634421091) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [7a6ec88b73](https://linux-hardware.org/?probe=7a6ec88b73) | Nov 26, 2022 |
| Dell          | Vostro 5471                 | [b9bbfd7551](https://linux-hardware.org/?probe=b9bbfd7551) | Nov 26, 2022 |
| Toshiba       | Satellite C670D-126         | [6c2fc84bf2](https://linux-hardware.org/?probe=6c2fc84bf2) | Nov 26, 2022 |
| GPU Compan... | GWNR71517                   | [15173435f0](https://linux-hardware.org/?probe=15173435f0) | Nov 26, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | [fa21163ace](https://linux-hardware.org/?probe=fa21163ace) | Nov 26, 2022 |
| GPD           | G1621-02                    | [d6b679024c](https://linux-hardware.org/?probe=d6b679024c) | Nov 26, 2022 |
| Dell          | Latitude E6440              | [348f786878](https://linux-hardware.org/?probe=348f786878) | Nov 26, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a462983d82](https://linux-hardware.org/?probe=a462983d82) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [10186425ec](https://linux-hardware.org/?probe=10186425ec) | Nov 25, 2022 |
| Acer          | Nitro AN515-45              | [5a7b57dae6](https://linux-hardware.org/?probe=5a7b57dae6) | Nov 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [57c8d65b2e](https://linux-hardware.org/?probe=57c8d65b2e) | Nov 25, 2022 |
| ASUSTek       | X510UQ                      | [5972ededc2](https://linux-hardware.org/?probe=5972ededc2) | Nov 24, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [a4512e8a71](https://linux-hardware.org/?probe=a4512e8a71) | Nov 24, 2022 |
| Dell          | XPS 15 9510                 | [26fb968043](https://linux-hardware.org/?probe=26fb968043) | Nov 23, 2022 |
| Lenovo        | G40-45 80E1                 | [c50111eb6d](https://linux-hardware.org/?probe=c50111eb6d) | Nov 22, 2022 |
| Dell          | Latitude 5410               | [7fd0b3fca7](https://linux-hardware.org/?probe=7fd0b3fca7) | Nov 21, 2022 |
| Lenovo        | ThinkPad T440s 20AQ007SM... | [326b5bad4c](https://linux-hardware.org/?probe=326b5bad4c) | Nov 21, 2022 |
| HP            | Unknown                     | [4530507592](https://linux-hardware.org/?probe=4530507592) | Nov 20, 2022 |
| Acer          | Aspire ES1-711G             | [8852f94b38](https://linux-hardware.org/?probe=8852f94b38) | Nov 20, 2022 |
| Apple         | MacBookPro8,1               | [8a52f497b0](https://linux-hardware.org/?probe=8a52f497b0) | Nov 19, 2022 |
| Acer          | Nitro AN517-51              | [de8506cc0b](https://linux-hardware.org/?probe=de8506cc0b) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | [9aab7e297a](https://linux-hardware.org/?probe=9aab7e297a) | Nov 19, 2022 |
| MSI           | Vector GP66 12UGS           | [e10c2abc9b](https://linux-hardware.org/?probe=e10c2abc9b) | Nov 19, 2022 |
| HP            | Laptop 17-cp0xxx            | [a3fde1deaa](https://linux-hardware.org/?probe=a3fde1deaa) | Nov 19, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [36bc4b545f](https://linux-hardware.org/?probe=36bc4b545f) | Nov 19, 2022 |
| Toshiba       | Satellite C670D-126         | [17e464f802](https://linux-hardware.org/?probe=17e464f802) | Nov 19, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [53a2707274](https://linux-hardware.org/?probe=53a2707274) | Nov 18, 2022 |
| Dell          | Inspiron 7348               | [6a46a84480](https://linux-hardware.org/?probe=6a46a84480) | Nov 18, 2022 |
| HP            | Laptop 17-cp0xxx            | [f4c6260289](https://linux-hardware.org/?probe=f4c6260289) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | [6e0f255eeb](https://linux-hardware.org/?probe=6e0f255eeb) | Nov 18, 2022 |
| Dell          | Inspiron 5759               | [8cdba26964](https://linux-hardware.org/?probe=8cdba26964) | Nov 18, 2022 |
| Digma         | EVE 15 C423 ES5069EW        | [57cd27008a](https://linux-hardware.org/?probe=57cd27008a) | Nov 18, 2022 |
| Dell          | Inspiron 1545               | [dc9ddea189](https://linux-hardware.org/?probe=dc9ddea189) | Nov 17, 2022 |
| ASUSTek       | Zenbook Pro Duo UX582ZW_... | [cc20cc9828](https://linux-hardware.org/?probe=cc20cc9828) | Nov 16, 2022 |
| Dell          | Inspiron 1545               | [8b63918780](https://linux-hardware.org/?probe=8b63918780) | Nov 16, 2022 |
| HP            | Pavilion 15                 | [fbef42d1dc](https://linux-hardware.org/?probe=fbef42d1dc) | Nov 16, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [facd5aa317](https://linux-hardware.org/?probe=facd5aa317) | Nov 16, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [e7152e6cb3](https://linux-hardware.org/?probe=e7152e6cb3) | Nov 16, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | [a30ec58d99](https://linux-hardware.org/?probe=a30ec58d99) | Nov 16, 2022 |
| Dell          | Latitude E7250              | [907a7245b4](https://linux-hardware.org/?probe=907a7245b4) | Nov 15, 2022 |
| Acer          | TravelMate P633-M           | [2277ff1866](https://linux-hardware.org/?probe=2277ff1866) | Nov 15, 2022 |
| Acer          | Aspire V3-571G              | [ea0093a1f6](https://linux-hardware.org/?probe=ea0093a1f6) | Nov 15, 2022 |
| Dell          | Inspiron 3480               | [699e532a38](https://linux-hardware.org/?probe=699e532a38) | Nov 14, 2022 |
| Dell          | Inspiron 3480               | [3fca000783](https://linux-hardware.org/?probe=3fca000783) | Nov 14, 2022 |
| Dell          | Precision 7510              | [111903e578](https://linux-hardware.org/?probe=111903e578) | Nov 14, 2022 |
| HP            | Laptop 17-cp0xxx            | [fa8dcc3eed](https://linux-hardware.org/?probe=fa8dcc3eed) | Nov 13, 2022 |
| ASUSTek       | K53Z                        | [7eb8b08a75](https://linux-hardware.org/?probe=7eb8b08a75) | Nov 13, 2022 |
| Lenovo        | ThinkPad T430 2349P25       | [ba76ce6af6](https://linux-hardware.org/?probe=ba76ce6af6) | Nov 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S28R00    | [ac107ff6e8](https://linux-hardware.org/?probe=ac107ff6e8) | Nov 12, 2022 |
| Google        | Celes                       | [4b15e527d5](https://linux-hardware.org/?probe=4b15e527d5) | Nov 12, 2022 |
| Google        | Celes                       | [68323b0e01](https://linux-hardware.org/?probe=68323b0e01) | Nov 12, 2022 |
| Lenovo        | V14-IIL 82C4                | [ca336329c8](https://linux-hardware.org/?probe=ca336329c8) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [311c90573c](https://linux-hardware.org/?probe=311c90573c) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [1198a061e1](https://linux-hardware.org/?probe=1198a061e1) | Nov 12, 2022 |
| Timi          | TM1703                      | [b59fbfd729](https://linux-hardware.org/?probe=b59fbfd729) | Nov 11, 2022 |
| Lenovo        | IdeaPad Z510 20287          | [d020fa04fe](https://linux-hardware.org/?probe=d020fa04fe) | Nov 11, 2022 |
| Dell          | Latitude 12 Rugged Extre... | [d5b955a7b3](https://linux-hardware.org/?probe=d5b955a7b3) | Nov 11, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | [d8adeb01a9](https://linux-hardware.org/?probe=d8adeb01a9) | Nov 10, 2022 |
| HP            | EliteBook 8470p             | [45f26463b7](https://linux-hardware.org/?probe=45f26463b7) | Nov 10, 2022 |
| Acer          | Predator PT516-52s          | [b8ebbe76e8](https://linux-hardware.org/?probe=b8ebbe76e8) | Nov 10, 2022 |
| HP            | Pavilion g6                 | [e2a0a47587](https://linux-hardware.org/?probe=e2a0a47587) | Nov 10, 2022 |
| MSI           | GS75 Stealth 10SE           | [a13f6196b6](https://linux-hardware.org/?probe=a13f6196b6) | Nov 10, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | [ffa33ab238](https://linux-hardware.org/?probe=ffa33ab238) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | [fc8cf254ad](https://linux-hardware.org/?probe=fc8cf254ad) | Nov 10, 2022 |
| VALE          | Notebook Slim S132          | [720ddf5d0f](https://linux-hardware.org/?probe=720ddf5d0f) | Nov 10, 2022 |
| MSI           | GS75 Stealth 10SE           | [eaed1093a4](https://linux-hardware.org/?probe=eaed1093a4) | Nov 10, 2022 |
| Dell          | XPS 15 9560                 | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Timi          | TM1701                      | [917ec43bd1](https://linux-hardware.org/?probe=917ec43bd1) | Nov 09, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [de85ac10f6](https://linux-hardware.org/?probe=de85ac10f6) | Nov 09, 2022 |
| HP            | Laptop 17-cp0xxx            | [1c51983a67](https://linux-hardware.org/?probe=1c51983a67) | Nov 09, 2022 |
| HP            | Laptop 17-ca2xxx            | [a31e9f30cc](https://linux-hardware.org/?probe=a31e9f30cc) | Nov 09, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [a72c604f03](https://linux-hardware.org/?probe=a72c604f03) | Nov 09, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [5d479ec43f](https://linux-hardware.org/?probe=5d479ec43f) | Nov 08, 2022 |
| MSI           | Unknown                     | [76090d77bf](https://linux-hardware.org/?probe=76090d77bf) | Nov 08, 2022 |
| HP            | Laptop 17-cp0xxx            | [91355e2bd7](https://linux-hardware.org/?probe=91355e2bd7) | Nov 08, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [5584c6e2d1](https://linux-hardware.org/?probe=5584c6e2d1) | Nov 08, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [8ba7f1aa17](https://linux-hardware.org/?probe=8ba7f1aa17) | Nov 08, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [1a4822b860](https://linux-hardware.org/?probe=1a4822b860) | Nov 08, 2022 |
| Lenovo        | B590 20206                  | [d454a9a1e7](https://linux-hardware.org/?probe=d454a9a1e7) | Nov 07, 2022 |
| HP            | ProBook 5330m               | [7ddff41cb6](https://linux-hardware.org/?probe=7ddff41cb6) | Nov 07, 2022 |
| Lenovo        | G500 20236                  | [76d6e74fad](https://linux-hardware.org/?probe=76d6e74fad) | Nov 07, 2022 |
| Acer          | Aspire 5750                 | [83a24172bd](https://linux-hardware.org/?probe=83a24172bd) | Nov 06, 2022 |
| HP            | 250 G7 Notebook PC          | [d29197ed66](https://linux-hardware.org/?probe=d29197ed66) | Nov 06, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | [8090894691](https://linux-hardware.org/?probe=8090894691) | Nov 06, 2022 |
| Sony          | VGN-FW21E                   | [8be58df3e0](https://linux-hardware.org/?probe=8be58df3e0) | Nov 06, 2022 |
| HP            | Laptop 15-dw0xxx            | [46c9baf82c](https://linux-hardware.org/?probe=46c9baf82c) | Nov 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [5783283bd4](https://linux-hardware.org/?probe=5783283bd4) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | [58025a9d04](https://linux-hardware.org/?probe=58025a9d04) | Nov 05, 2022 |
| HP            | 250 G7 Notebook PC          | [e5684c9b19](https://linux-hardware.org/?probe=e5684c9b19) | Nov 05, 2022 |
| HP            | ZBook 15u G6                | [bd1a9c6659](https://linux-hardware.org/?probe=bd1a9c6659) | Nov 05, 2022 |
| HP            | Pavilion 17                 | [9dd715b48e](https://linux-hardware.org/?probe=9dd715b48e) | Nov 05, 2022 |
| Dell          | Latitude 3420               | [f30c035ae6](https://linux-hardware.org/?probe=f30c035ae6) | Nov 05, 2022 |
| PC Special... | PB50_70RF,RD,RC             | [c2e0841c46](https://linux-hardware.org/?probe=c2e0841c46) | Nov 05, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | [118a1f505b](https://linux-hardware.org/?probe=118a1f505b) | Nov 04, 2022 |
| AXIOO         | SlimBook 11                 | [ffc6980bf3](https://linux-hardware.org/?probe=ffc6980bf3) | Nov 03, 2022 |
| AXIOO         | SlimBook 11                 | [a16eac12d2](https://linux-hardware.org/?probe=a16eac12d2) | Nov 03, 2022 |
| Dell          | Latitude E6320              | [b66269072e](https://linux-hardware.org/?probe=b66269072e) | Nov 02, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | [623af75bb3](https://linux-hardware.org/?probe=623af75bb3) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | [52e7c62bae](https://linux-hardware.org/?probe=52e7c62bae) | Nov 02, 2022 |
| Notebook      | P65_P67SE                   | [9b99df1e15](https://linux-hardware.org/?probe=9b99df1e15) | Nov 02, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| HUAWEI        | KPL-W0X                     | [6d6a8caf61](https://linux-hardware.org/?probe=6d6a8caf61) | Nov 01, 2022 |
| HP            | Laptop 15-da2xxx            | [ea7591794a](https://linux-hardware.org/?probe=ea7591794a) | Nov 01, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | [80f6da5216](https://linux-hardware.org/?probe=80f6da5216) | Oct 31, 2022 |
| Acer          | Aspire 5732Z                | [df73e0ca67](https://linux-hardware.org/?probe=df73e0ca67) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [4b778e52ee](https://linux-hardware.org/?probe=4b778e52ee) | Oct 30, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [418b143f46](https://linux-hardware.org/?probe=418b143f46) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [293877c614](https://linux-hardware.org/?probe=293877c614) | Oct 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | [aea626acae](https://linux-hardware.org/?probe=aea626acae) | Oct 29, 2022 |
| Lenovo        | V15-IGL 82C3                | [5bd4292187](https://linux-hardware.org/?probe=5bd4292187) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [d7491bf8e7](https://linux-hardware.org/?probe=d7491bf8e7) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6bdf703faf](https://linux-hardware.org/?probe=6bdf703faf) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | [cfa027a9e2](https://linux-hardware.org/?probe=cfa027a9e2) | Oct 28, 2022 |
| Dell          | Latitude 5521               | [460057b367](https://linux-hardware.org/?probe=460057b367) | Oct 28, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| HP            | Laptop 15-da2xxx            | [071938b19a](https://linux-hardware.org/?probe=071938b19a) | Oct 28, 2022 |
| HP            | 255 G8 Notebook PC          | [ba5aec702a](https://linux-hardware.org/?probe=ba5aec702a) | Oct 27, 2022 |
| Acer          | Predator PT516-52s          | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | [a5c5f0ec1e](https://linux-hardware.org/?probe=a5c5f0ec1e) | Oct 27, 2022 |
| HP            | Pavilion dv6                | [ed392a140d](https://linux-hardware.org/?probe=ed392a140d) | Oct 27, 2022 |
| HP            | G62                         | [c9ba156401](https://linux-hardware.org/?probe=c9ba156401) | Oct 27, 2022 |
| Dell          | Inspiron 5515               | [74ad4c8c59](https://linux-hardware.org/?probe=74ad4c8c59) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [a308f68bce](https://linux-hardware.org/?probe=a308f68bce) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| Notebook      | PD5x_7xPNP_PNR_PNN_PNT      | [93229f0fab](https://linux-hardware.org/?probe=93229f0fab) | Oct 26, 2022 |
| Acer          | Aspire E5-571               | [2920658e38](https://linux-hardware.org/?probe=2920658e38) | Oct 25, 2022 |
| Samsung       | 767XCL                      | [17bd1b4506](https://linux-hardware.org/?probe=17bd1b4506) | Oct 25, 2022 |
| HP            | Pavilion g6                 | [448d52b32f](https://linux-hardware.org/?probe=448d52b32f) | Oct 25, 2022 |
| ASUSTek       | N751JK                      | [f6f0ff5048](https://linux-hardware.org/?probe=f6f0ff5048) | Oct 25, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [94fa6196b8](https://linux-hardware.org/?probe=94fa6196b8) | Oct 25, 2022 |
| Acer          | Aspire 5750                 | [20df7ad008](https://linux-hardware.org/?probe=20df7ad008) | Oct 25, 2022 |
| Dell          | Vostro 15 5501              | [3338297022](https://linux-hardware.org/?probe=3338297022) | Oct 25, 2022 |
| HP            | ProBook 640 G1              | [cfb2e32cea](https://linux-hardware.org/?probe=cfb2e32cea) | Oct 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | [fe222419ec](https://linux-hardware.org/?probe=fe222419ec) | Oct 25, 2022 |
| HP            | 470 G8 Notebook PC          | [1cae6fb5ac](https://linux-hardware.org/?probe=1cae6fb5ac) | Oct 24, 2022 |
| HP            | 470 G8 Notebook PC          | [4c3e8196af](https://linux-hardware.org/?probe=4c3e8196af) | Oct 24, 2022 |
| Acer          | Nitro AN517-51              | [7fed0ea2a9](https://linux-hardware.org/?probe=7fed0ea2a9) | Oct 24, 2022 |
| Dell          | XPS 15 9560                 | [37fc32cacd](https://linux-hardware.org/?probe=37fc32cacd) | Oct 24, 2022 |
| Lenovo        | ThinkPad P73 20QRS00100     | [532b112928](https://linux-hardware.org/?probe=532b112928) | Oct 24, 2022 |
| HP            | EliteBook 8470p             | [918b0ef1ab](https://linux-hardware.org/?probe=918b0ef1ab) | Oct 24, 2022 |
| HP            | Laptop 17-by0xxx            | [faedd5a008](https://linux-hardware.org/?probe=faedd5a008) | Oct 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [13c917aa38](https://linux-hardware.org/?probe=13c917aa38) | Oct 23, 2022 |
| Dell          | Latitude 7390               | [71f8a9e59b](https://linux-hardware.org/?probe=71f8a9e59b) | Oct 22, 2022 |
| Acer          | Predator PT516-52s          | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a8c892608e](https://linux-hardware.org/?probe=a8c892608e) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [20f991643f](https://linux-hardware.org/?probe=20f991643f) | Oct 21, 2022 |
| HP            | Laptop 17-by4xxx            | [6090ec7241](https://linux-hardware.org/?probe=6090ec7241) | Oct 21, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [0cf70c348b](https://linux-hardware.org/?probe=0cf70c348b) | Oct 21, 2022 |
| HP            | Laptop 15-da2xxx            | [a9de489f26](https://linux-hardware.org/?probe=a9de489f26) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [c8e47b28fe](https://linux-hardware.org/?probe=c8e47b28fe) | Oct 20, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [46cb50f2f6](https://linux-hardware.org/?probe=46cb50f2f6) | Oct 19, 2022 |
| Haier         | A1420EM                     | [62ce3535b2](https://linux-hardware.org/?probe=62ce3535b2) | Oct 19, 2022 |
| Haier         | A1420EM                     | [a50bc27e31](https://linux-hardware.org/?probe=a50bc27e31) | Oct 19, 2022 |
| Tactus        | GeoBook 140                 | [6d01f5c57b](https://linux-hardware.org/?probe=6d01f5c57b) | Oct 19, 2022 |
| Dell          | XPS 9320                    | [8dd41b53b6](https://linux-hardware.org/?probe=8dd41b53b6) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | [a2db8aeade](https://linux-hardware.org/?probe=a2db8aeade) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | [92957e0afc](https://linux-hardware.org/?probe=92957e0afc) | Oct 19, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | [431a84fc31](https://linux-hardware.org/?probe=431a84fc31) | Oct 18, 2022 |
| Dell          | Precision 3570              | [90711415f5](https://linux-hardware.org/?probe=90711415f5) | Oct 18, 2022 |
| HP            | ProBook 450 G5              | [a7ebb4b3c4](https://linux-hardware.org/?probe=a7ebb4b3c4) | Oct 16, 2022 |
| Lenovo        | Yoga 2 13 20344             | [f779ba08c9](https://linux-hardware.org/?probe=f779ba08c9) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| ASUSTek       | X455LD                      | [ae520872e3](https://linux-hardware.org/?probe=ae520872e3) | Oct 14, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Dell          | Latitude E6420              | [f39e0305c5](https://linux-hardware.org/?probe=f39e0305c5) | Oct 13, 2022 |
| Dell          | Precision M6700             | [e198a003b6](https://linux-hardware.org/?probe=e198a003b6) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | [1258429041](https://linux-hardware.org/?probe=1258429041) | Oct 13, 2022 |
| HP            | Laptop 15-da2xxx            | [2813d441b5](https://linux-hardware.org/?probe=2813d441b5) | Oct 13, 2022 |
| HP            | Laptop 15-da2xxx            | [4039ed6d6f](https://linux-hardware.org/?probe=4039ed6d6f) | Oct 13, 2022 |
| GPU Compan... | GWTC116-2                   | [93ee54a067](https://linux-hardware.org/?probe=93ee54a067) | Oct 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [125ad4881a](https://linux-hardware.org/?probe=125ad4881a) | Oct 11, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [7a11da121e](https://linux-hardware.org/?probe=7a11da121e) | Oct 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [5268977f64](https://linux-hardware.org/?probe=5268977f64) | Oct 09, 2022 |
| Gigabyte      | AERO 15-X9                  | [aad99b4421](https://linux-hardware.org/?probe=aad99b4421) | Oct 09, 2022 |
| ASUSTek       | X555UA                      | [9cf559ac01](https://linux-hardware.org/?probe=9cf559ac01) | Oct 08, 2022 |
| Gigabyte      | AERO 15-X9                  | [1f634e5071](https://linux-hardware.org/?probe=1f634e5071) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [1b90e3cfa5](https://linux-hardware.org/?probe=1b90e3cfa5) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [fddd82ba56](https://linux-hardware.org/?probe=fddd82ba56) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | [9a16ca15b3](https://linux-hardware.org/?probe=9a16ca15b3) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [9bb8f8e33b](https://linux-hardware.org/?probe=9bb8f8e33b) | Oct 07, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [e59c8f50b4](https://linux-hardware.org/?probe=e59c8f50b4) | Oct 07, 2022 |
| Apple         | MacBookPro16,1              | [865d1f0e6f](https://linux-hardware.org/?probe=865d1f0e6f) | Oct 07, 2022 |
| Lenovo        | ZHAOYANG E53-80 81CM        | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| Toshiba       | Satellite NB10t-A-102       | [0bf17a1e92](https://linux-hardware.org/?probe=0bf17a1e92) | Oct 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| HP            | Compaq 15                   | [bba22531ad](https://linux-hardware.org/?probe=bba22531ad) | Oct 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [e4df51e64f](https://linux-hardware.org/?probe=e4df51e64f) | Oct 05, 2022 |
| HUAWEI        | NBD-WXX9                    | [2513dfd51e](https://linux-hardware.org/?probe=2513dfd51e) | Oct 05, 2022 |
| HP            | Compaq 15                   | [0f48335990](https://linux-hardware.org/?probe=0f48335990) | Oct 05, 2022 |
| Intel         | W7645                       | [4f76b8b5ad](https://linux-hardware.org/?probe=4f76b8b5ad) | Oct 04, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [082814c248](https://linux-hardware.org/?probe=082814c248) | Oct 04, 2022 |
| Apple         | MacBookPro10,1              | [3bc5547f39](https://linux-hardware.org/?probe=3bc5547f39) | Oct 04, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [76709f5d09](https://linux-hardware.org/?probe=76709f5d09) | Oct 04, 2022 |
| HP            | ProBook 640 G2              | [2dc13504cf](https://linux-hardware.org/?probe=2dc13504cf) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | [28b873114a](https://linux-hardware.org/?probe=28b873114a) | Oct 03, 2022 |
| Acer          | Aspire E5-575G              | [330f866cf3](https://linux-hardware.org/?probe=330f866cf3) | Oct 03, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| Apple         | MacBookPro9,1               | [08db9e8d75](https://linux-hardware.org/?probe=08db9e8d75) | Oct 01, 2022 |
| HP            | EliteBook 840 G3            | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| ASUSTek       | N56VZ                       | [2b78a7c7f1](https://linux-hardware.org/?probe=2b78a7c7f1) | Sep 29, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | [4b198e87aa](https://linux-hardware.org/?probe=4b198e87aa) | Sep 28, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [ec59847e5b](https://linux-hardware.org/?probe=ec59847e5b) | Sep 27, 2022 |
| HP            | ZBook 15 G6                 | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| ASUSTek       | K93SV                       | [541a21ceb8](https://linux-hardware.org/?probe=541a21ceb8) | Sep 26, 2022 |
| Gigabyte      | AORUS 7 SB                  | [3e8222ad7c](https://linux-hardware.org/?probe=3e8222ad7c) | Sep 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Acer          | Aspire R3-131T              | [0d44032bc0](https://linux-hardware.org/?probe=0d44032bc0) | Sep 25, 2022 |
| Dell          | Latitude E5400              | [09be905a45](https://linux-hardware.org/?probe=09be905a45) | Sep 24, 2022 |
| HUAWEI        | BOHB-WAX9                   | [18a4d2bb72](https://linux-hardware.org/?probe=18a4d2bb72) | Sep 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | [6e943a4d35](https://linux-hardware.org/?probe=6e943a4d35) | Sep 23, 2022 |
| HP            | Pavilion 14                 | [277d97cc71](https://linux-hardware.org/?probe=277d97cc71) | Sep 23, 2022 |
| Lenovo        | G50-45 80E3                 | [3b1de255e3](https://linux-hardware.org/?probe=3b1de255e3) | Sep 22, 2022 |
| HP            | 255 G8 Notebook PC          | [20691b389b](https://linux-hardware.org/?probe=20691b389b) | Sep 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | [6352f6fb82](https://linux-hardware.org/?probe=6352f6fb82) | Sep 21, 2022 |
| Dell          | Inspiron 7559               | [4abbaf3df9](https://linux-hardware.org/?probe=4abbaf3df9) | Sep 19, 2022 |
| Acer          | Aspire A515-45              | [41b1b790fd](https://linux-hardware.org/?probe=41b1b790fd) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Google        | Blooglet                    | [971a174a56](https://linux-hardware.org/?probe=971a174a56) | Sep 18, 2022 |
| Acer          | Aspire S3-391               | [5aadfd37c5](https://linux-hardware.org/?probe=5aadfd37c5) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | [82a1f45915](https://linux-hardware.org/?probe=82a1f45915) | Sep 17, 2022 |
| MSI           | Delta 15 A5EFK              | [382e0f70a3](https://linux-hardware.org/?probe=382e0f70a3) | Sep 17, 2022 |
| Dell          | XPS 15 9560                 | [4a903b438f](https://linux-hardware.org/?probe=4a903b438f) | Sep 17, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [4ee2b37edf](https://linux-hardware.org/?probe=4ee2b37edf) | Sep 16, 2022 |
| ASUSTek       | G501VW                      | [cf04ceb420](https://linux-hardware.org/?probe=cf04ceb420) | Sep 15, 2022 |
| Dell          | Latitude 7430               | [4fdf1a303c](https://linux-hardware.org/?probe=4fdf1a303c) | Sep 15, 2022 |
| Google        | Treeya                      | [a2723e9afa](https://linux-hardware.org/?probe=a2723e9afa) | Sep 15, 2022 |
| Dell          | Inspiron 5567               | [3af5d11f3f](https://linux-hardware.org/?probe=3af5d11f3f) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Lenovo        | B40-70 80F30005BR           | [b899f1b7da](https://linux-hardware.org/?probe=b899f1b7da) | Sep 13, 2022 |
| Lenovo        | B40-70 80F30005BR           | [99be4451df](https://linux-hardware.org/?probe=99be4451df) | Sep 13, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [703c55185d](https://linux-hardware.org/?probe=703c55185d) | Sep 12, 2022 |
| Sony          | SVE1512J6EW                 | [69e2400606](https://linux-hardware.org/?probe=69e2400606) | Sep 11, 2022 |
| HP            | EliteBook 8470p             | [52f6655891](https://linux-hardware.org/?probe=52f6655891) | Sep 11, 2022 |
| Dell          | G15 5511                    | [b971c27fae](https://linux-hardware.org/?probe=b971c27fae) | Sep 10, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [50f39d7738](https://linux-hardware.org/?probe=50f39d7738) | Sep 09, 2022 |
| Dell          | Latitude 7430               | [b1cdbef6b2](https://linux-hardware.org/?probe=b1cdbef6b2) | Sep 09, 2022 |
| Acer          | Predator G3-571             | [553cf2f33f](https://linux-hardware.org/?probe=553cf2f33f) | Sep 08, 2022 |
| Dell          | Vostro 3700                 | [40e150eb3b](https://linux-hardware.org/?probe=40e150eb3b) | Sep 08, 2022 |
| Notebook      | NV4XMB,ME,MZ                | [0efc3cb183](https://linux-hardware.org/?probe=0efc3cb183) | Sep 07, 2022 |
| Dell          | Precision M4800             | [280ca4dce2](https://linux-hardware.org/?probe=280ca4dce2) | Sep 07, 2022 |
| Dell          | Precision M4800             | [9d494c5486](https://linux-hardware.org/?probe=9d494c5486) | Sep 07, 2022 |
| HP            | 255 G8 Notebook PC          | [5c53e30fe6](https://linux-hardware.org/?probe=5c53e30fe6) | Sep 06, 2022 |
| Samsung       | 270E5G/270E5U               | [0300dd1a2d](https://linux-hardware.org/?probe=0300dd1a2d) | Sep 05, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | [d496e01f0e](https://linux-hardware.org/?probe=d496e01f0e) | Sep 05, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | [85798fb011](https://linux-hardware.org/?probe=85798fb011) | Sep 05, 2022 |
| ASUSTek       | UX51VZA                     | [46aa1dbafa](https://linux-hardware.org/?probe=46aa1dbafa) | Sep 04, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [8eec266b41](https://linux-hardware.org/?probe=8eec266b41) | Sep 03, 2022 |
| HP            | Laptop 15-da0xxx            | [5c11f5477e](https://linux-hardware.org/?probe=5c11f5477e) | Sep 03, 2022 |
| HP            | Notebook                    | [a3b180cbb5](https://linux-hardware.org/?probe=a3b180cbb5) | Sep 03, 2022 |
| Lenovo        | G780 20138                  | [4a452f0874](https://linux-hardware.org/?probe=4a452f0874) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [a4290c0678](https://linux-hardware.org/?probe=a4290c0678) | Sep 03, 2022 |
| ASUSTek       | UX51VZA                     | [e93c1732ec](https://linux-hardware.org/?probe=e93c1732ec) | Sep 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | [a15c233224](https://linux-hardware.org/?probe=a15c233224) | Sep 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [e8b9bc90f3](https://linux-hardware.org/?probe=e8b9bc90f3) | Sep 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | [d34c9cb705](https://linux-hardware.org/?probe=d34c9cb705) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| HP            | Pavilion Gaming Laptop      | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | [0166c06969](https://linux-hardware.org/?probe=0166c06969) | Aug 30, 2022 |
| Dell          | Latitude 9420               | [0b8d883170](https://linux-hardware.org/?probe=0b8d883170) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| Google        | Eldrid                      | [ae53120bac](https://linux-hardware.org/?probe=ae53120bac) | Aug 28, 2022 |
| HP            | Pavilion dv6700             | [8fae050683](https://linux-hardware.org/?probe=8fae050683) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [20bea980d2](https://linux-hardware.org/?probe=20bea980d2) | Aug 28, 2022 |
| HP            | Pavilion dv6700             | [1912258e10](https://linux-hardware.org/?probe=1912258e10) | Aug 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| Dell          | Latitude E6400              | [8517e82248](https://linux-hardware.org/?probe=8517e82248) | Aug 26, 2022 |
| Sony          | VGN-NR11Z_T                 | [54c1e7c198](https://linux-hardware.org/?probe=54c1e7c198) | Aug 26, 2022 |
| HP            | ProBook 4540s               | [f082a7566a](https://linux-hardware.org/?probe=f082a7566a) | Aug 24, 2022 |
| HP            | ProBook 4540s               | [de08e9b296](https://linux-hardware.org/?probe=de08e9b296) | Aug 24, 2022 |
| Apple         | MacBookPro11,1              | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | [4c201d43d0](https://linux-hardware.org/?probe=4c201d43d0) | Aug 22, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | [29d7ac6ea6](https://linux-hardware.org/?probe=29d7ac6ea6) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | [c8f76780a1](https://linux-hardware.org/?probe=c8f76780a1) | Aug 21, 2022 |
| Toshiba       | Satellite P70-B             | [4e04d56e06](https://linux-hardware.org/?probe=4e04d56e06) | Aug 21, 2022 |
| Toshiba       | Satellite P70-B             | [402017a7ea](https://linux-hardware.org/?probe=402017a7ea) | Aug 21, 2022 |
| Dell          | G3 3500                     | [1e8edd3350](https://linux-hardware.org/?probe=1e8edd3350) | Aug 21, 2022 |
| Acer          | Nitro AN515-57              | [bdc4179004](https://linux-hardware.org/?probe=bdc4179004) | Aug 21, 2022 |
| HP            | ProBook 6570b               | [eba0cd02ec](https://linux-hardware.org/?probe=eba0cd02ec) | Aug 21, 2022 |
| Dell          | Inspiron 15-5578            | [a0ff8934e5](https://linux-hardware.org/?probe=a0ff8934e5) | Aug 21, 2022 |
| HP            | Pavilion g6                 | [8d5375bd39](https://linux-hardware.org/?probe=8d5375bd39) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | [45bac2f9d1](https://linux-hardware.org/?probe=45bac2f9d1) | Aug 20, 2022 |
| Dell          | G3 3779                     | [a2b721ca15](https://linux-hardware.org/?probe=a2b721ca15) | Aug 19, 2022 |
| MSI           | GF75 Thin 10SCXR            | [b75c38c8a5](https://linux-hardware.org/?probe=b75c38c8a5) | Aug 19, 2022 |
| Dell          | Latitude 7280               | [63e00d0c9d](https://linux-hardware.org/?probe=63e00d0c9d) | Aug 18, 2022 |
| Acer          | Nitro AN517-41              | [73649d898c](https://linux-hardware.org/?probe=73649d898c) | Aug 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| Apple         | MacBookPro11,1              | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| HP            | ProBook 6570b               | [b490a791c0](https://linux-hardware.org/?probe=b490a791c0) | Aug 15, 2022 |
| Dell          | Precision 3571              | [48c3133a7f](https://linux-hardware.org/?probe=48c3133a7f) | Aug 15, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [30820abfa2](https://linux-hardware.org/?probe=30820abfa2) | Aug 14, 2022 |
| HP            | ZBook 15 G4                 | [92cacb2a11](https://linux-hardware.org/?probe=92cacb2a11) | Aug 12, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | [ca96da9d08](https://linux-hardware.org/?probe=ca96da9d08) | Aug 12, 2022 |
| Panasonic     | CF-53JSWZGFF                | [88c83a7e28](https://linux-hardware.org/?probe=88c83a7e28) | Aug 11, 2022 |
| Dell          | Latitude 5590               | [a00272df56](https://linux-hardware.org/?probe=a00272df56) | Aug 11, 2022 |
| Timi          | TM1709                      | [26b592f734](https://linux-hardware.org/?probe=26b592f734) | Aug 11, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| HP            | ProBook 6570b               | [0acbdaf806](https://linux-hardware.org/?probe=0acbdaf806) | Aug 10, 2022 |
| Shanghai Z... | ZXE CRB                     | [9ac3c0b157](https://linux-hardware.org/?probe=9ac3c0b157) | Aug 09, 2022 |
| HP            | EliteBook 8470p             | [14aebc0034](https://linux-hardware.org/?probe=14aebc0034) | Aug 09, 2022 |
| HP            | G62                         | [430fe133db](https://linux-hardware.org/?probe=430fe133db) | Aug 09, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [4b74670050](https://linux-hardware.org/?probe=4b74670050) | Aug 08, 2022 |
| Lenovo        | V15-ADA 82C7                | [5b7d298ca6](https://linux-hardware.org/?probe=5b7d298ca6) | Aug 08, 2022 |
| Dell          | Latitude 5420               | [824404ee24](https://linux-hardware.org/?probe=824404ee24) | Aug 08, 2022 |
| HP            | ProBook 455 G7              | [b2e805c687](https://linux-hardware.org/?probe=b2e805c687) | Aug 07, 2022 |
| Dell          | XPS 15 9520                 | [7311161548](https://linux-hardware.org/?probe=7311161548) | Aug 07, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [9c77d1a0d5](https://linux-hardware.org/?probe=9c77d1a0d5) | Aug 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | [ea189dab70](https://linux-hardware.org/?probe=ea189dab70) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | [22e9ee373f](https://linux-hardware.org/?probe=22e9ee373f) | Aug 06, 2022 |
| Dell          | Precision 7530              | [40854a027f](https://linux-hardware.org/?probe=40854a027f) | Aug 05, 2022 |
| HP            | EliteBook 8470p             | [df685682b3](https://linux-hardware.org/?probe=df685682b3) | Aug 05, 2022 |
| Dell          | Latitude 5590               | [52f059849a](https://linux-hardware.org/?probe=52f059849a) | Aug 04, 2022 |
| Dell          | Latitude 5590               | [47292ecf57](https://linux-hardware.org/?probe=47292ecf57) | Aug 04, 2022 |
| VIT           | P2402                       | [895454e84f](https://linux-hardware.org/?probe=895454e84f) | Aug 03, 2022 |
| Fujitsu       | LIFEBOOK U758               | [3a73f1ffdd](https://linux-hardware.org/?probe=3a73f1ffdd) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f79a1d3402](https://linux-hardware.org/?probe=f79a1d3402) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [b2e4380743](https://linux-hardware.org/?probe=b2e4380743) | Aug 03, 2022 |
| Apple         | MacBookPro11,1              | [9814fa3bca](https://linux-hardware.org/?probe=9814fa3bca) | Aug 03, 2022 |
| ASUSTek       | X540SA                      | [6adb003f2e](https://linux-hardware.org/?probe=6adb003f2e) | Aug 01, 2022 |
| ASUSTek       | X540SA                      | [4dbed1e983](https://linux-hardware.org/?probe=4dbed1e983) | Aug 01, 2022 |
| VIT           | P2402                       | [fd1ab8ad90](https://linux-hardware.org/?probe=fd1ab8ad90) | Aug 01, 2022 |
| Intel         | Unknown                     | [9fce3597b9](https://linux-hardware.org/?probe=9fce3597b9) | Aug 01, 2022 |
| HP            | ProBook 6570b               | [b99b5ef83f](https://linux-hardware.org/?probe=b99b5ef83f) | Aug 01, 2022 |
| HP            | ProBook 6570b               | [3898ce2b5f](https://linux-hardware.org/?probe=3898ce2b5f) | Aug 01, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [09c15c1ed8](https://linux-hardware.org/?probe=09c15c1ed8) | Jul 31, 2022 |
| HP            | EliteBook 840 G6            | [1a2713a2b0](https://linux-hardware.org/?probe=1a2713a2b0) | Jul 31, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | [5dcf2bfdbd](https://linux-hardware.org/?probe=5dcf2bfdbd) | Jul 30, 2022 |
| Dell          | Latitude 5590               | [7fa93449bd](https://linux-hardware.org/?probe=7fa93449bd) | Jul 28, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [9c0b784d1d](https://linux-hardware.org/?probe=9c0b784d1d) | Jul 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| Dell          | Inspiron 15-3567            | [3e40b1abe6](https://linux-hardware.org/?probe=3e40b1abe6) | Jul 27, 2022 |
| Dell          | G5 5590                     | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| Unknown       | Unknown                     | [03fa847263](https://linux-hardware.org/?probe=03fa847263) | Jul 26, 2022 |
| Lenovo        | G570 20079                  | [50bab54f21](https://linux-hardware.org/?probe=50bab54f21) | Jul 26, 2022 |
| HP            | Laptop 15-da0xxx            | [6967eac391](https://linux-hardware.org/?probe=6967eac391) | Jul 26, 2022 |
| Lenovo        | G50-45 80E3                 | [df38a7a1ff](https://linux-hardware.org/?probe=df38a7a1ff) | Jul 25, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [2c515ee09a](https://linux-hardware.org/?probe=2c515ee09a) | Jul 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | [e24e72037a](https://linux-hardware.org/?probe=e24e72037a) | Jul 24, 2022 |
| Acer          | Aspire E5-575G              | [d404840b57](https://linux-hardware.org/?probe=d404840b57) | Jul 24, 2022 |
| HP            | EliteBook 8470p             | [ec23b6375e](https://linux-hardware.org/?probe=ec23b6375e) | Jul 24, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| HP            | G62                         | [418c1c572e](https://linux-hardware.org/?probe=418c1c572e) | Jul 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| Lenovo        | ThinkPad E570 20H5006TFR    | [1a1220dc79](https://linux-hardware.org/?probe=1a1220dc79) | Jul 21, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HONOR         | HYM-WXX                     | [654a2a5950](https://linux-hardware.org/?probe=654a2a5950) | Jul 17, 2022 |
| ASUSTek       | K53U                        | [20120e258a](https://linux-hardware.org/?probe=20120e258a) | Jul 16, 2022 |
| Standard      | Unknown                     | [3b4805163d](https://linux-hardware.org/?probe=3b4805163d) | Jul 15, 2022 |
| HP            | Laptop 15s-eq1xxx           | [57ef4db755](https://linux-hardware.org/?probe=57ef4db755) | Jul 14, 2022 |
| HP            | Laptop 17-cn0xxx            | [02a5205d57](https://linux-hardware.org/?probe=02a5205d57) | Jul 14, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | [41136553b2](https://linux-hardware.org/?probe=41136553b2) | Jul 13, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | [21ef2a8d9a](https://linux-hardware.org/?probe=21ef2a8d9a) | Jul 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [1bbf224b5c](https://linux-hardware.org/?probe=1bbf224b5c) | Jul 11, 2022 |
| Dell          | Latitude E5520              | [e04cdad7b7](https://linux-hardware.org/?probe=e04cdad7b7) | Jul 11, 2022 |
| HP            | EliteBook 840 G5            | [392310b916](https://linux-hardware.org/?probe=392310b916) | Jul 11, 2022 |
| System76      | Lemur Ultra                 | [10e8deaf3b](https://linux-hardware.org/?probe=10e8deaf3b) | Jul 11, 2022 |
| Lenovo        | IdeaPad Y430 2781           | [b8960364cb](https://linux-hardware.org/?probe=b8960364cb) | Jul 10, 2022 |
| Toshiba       | TECRA S11                   | [c33fa181ba](https://linux-hardware.org/?probe=c33fa181ba) | Jul 08, 2022 |
| Lenovo        | ThinkPad X200 7458FDG       | [435e7998bd](https://linux-hardware.org/?probe=435e7998bd) | Jul 08, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [6b007e333a](https://linux-hardware.org/?probe=6b007e333a) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [f09a1deecc](https://linux-hardware.org/?probe=f09a1deecc) | Jul 06, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [445bedc2c9](https://linux-hardware.org/?probe=445bedc2c9) | Jul 06, 2022 |
| HP            | G42                         | [4a57fd54c6](https://linux-hardware.org/?probe=4a57fd54c6) | Jul 06, 2022 |
| HUAWEI        | CREM-WXX9                   | [e7e175955d](https://linux-hardware.org/?probe=e7e175955d) | Jul 05, 2022 |
| Chuwi         | CoreBook X                  | [a23d0fe53d](https://linux-hardware.org/?probe=a23d0fe53d) | Jul 04, 2022 |
| Sony          | VPCSA3M9E                   | [b36435a1fd](https://linux-hardware.org/?probe=b36435a1fd) | Jul 03, 2022 |
| Chuwi         | CoreBook X                  | [a8d8dfc814](https://linux-hardware.org/?probe=a8d8dfc814) | Jul 03, 2022 |
| Lenovo        | G50-45 80E3                 | [0dfbfe1182](https://linux-hardware.org/?probe=0dfbfe1182) | Jul 03, 2022 |
| HP            | 620                         | [cc970fdd77](https://linux-hardware.org/?probe=cc970fdd77) | Jul 02, 2022 |
| Lenovo        | ThinkPad T420 4180M8P       | [8a94c5bc15](https://linux-hardware.org/?probe=8a94c5bc15) | Jul 02, 2022 |
| Dell          | Latitude 7530               | [a66aca8921](https://linux-hardware.org/?probe=a66aca8921) | Jul 01, 2022 |
| HP            | EliteBook 840 G1            | [b691598870](https://linux-hardware.org/?probe=b691598870) | Jul 01, 2022 |
| HONOR         | BOHK-WAX9X                  | [1647402099](https://linux-hardware.org/?probe=1647402099) | Jun 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | [4b04ded505](https://linux-hardware.org/?probe=4b04ded505) | Jun 30, 2022 |
| Jumper        | EZpad                       | [5d5f3980e1](https://linux-hardware.org/?probe=5d5f3980e1) | Jun 30, 2022 |
| Dell          | Latitude 3420               | [5fef19c107](https://linux-hardware.org/?probe=5fef19c107) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [6dc02ab574](https://linux-hardware.org/?probe=6dc02ab574) | Jun 29, 2022 |
| HP            | EliteBook 840 G6            | [faaa7b9c81](https://linux-hardware.org/?probe=faaa7b9c81) | Jun 29, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [d2f3d5aefd](https://linux-hardware.org/?probe=d2f3d5aefd) | Jun 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| Haier         | A1420EM                     | [3690a94424](https://linux-hardware.org/?probe=3690a94424) | Jun 28, 2022 |
| GPU Compan... | GWTC116-2                   | [183f3e59fb](https://linux-hardware.org/?probe=183f3e59fb) | Jun 28, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | [f39c4bd8a0](https://linux-hardware.org/?probe=f39c4bd8a0) | Jun 27, 2022 |
| HP            | 15                          | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| ASUSTek       | K46CB                       | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | [6afa74e5b6](https://linux-hardware.org/?probe=6afa74e5b6) | Jun 25, 2022 |
| Acer          | Nitro AN515-57              | [10d0c2a6ea](https://linux-hardware.org/?probe=10d0c2a6ea) | Jun 24, 2022 |
| Dell          | Latitude XT3                | [87377f03e2](https://linux-hardware.org/?probe=87377f03e2) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| HP            | EliteBook 820 G1            | [ff4b7698ed](https://linux-hardware.org/?probe=ff4b7698ed) | Jun 23, 2022 |
| Dell          | Latitude 5590               | [aa45d97e0b](https://linux-hardware.org/?probe=aa45d97e0b) | Jun 23, 2022 |
| Dell          | Latitude 5590               | [3745dfcae3](https://linux-hardware.org/?probe=3745dfcae3) | Jun 23, 2022 |
| Clevo         | Modified by dsanke          | [b88e7a22fe](https://linux-hardware.org/?probe=b88e7a22fe) | Jun 22, 2022 |
| Lenovo        | V130-15IGM 81HL             | [62f47da7d2](https://linux-hardware.org/?probe=62f47da7d2) | Jun 22, 2022 |
| Dell          | Precision 5540              | [d4a5611433](https://linux-hardware.org/?probe=d4a5611433) | Jun 22, 2022 |
| ASUSTek       | GR8                         | [90afe7bdd7](https://linux-hardware.org/?probe=90afe7bdd7) | Jun 20, 2022 |
| Apple         | MacBookPro15,2              | [c931d0e7bf](https://linux-hardware.org/?probe=c931d0e7bf) | Jun 20, 2022 |
| Dell          | XPS 17 9720                 | [2a36b8d90d](https://linux-hardware.org/?probe=2a36b8d90d) | Jun 20, 2022 |
| Toshiba       | Satellite L655              | [2e67542246](https://linux-hardware.org/?probe=2e67542246) | Jun 19, 2022 |
| Packard Be... | H17HV                       | [daa945363e](https://linux-hardware.org/?probe=daa945363e) | Jun 19, 2022 |
| ASUSTek       | X550JF                      | [be77e811e2](https://linux-hardware.org/?probe=be77e811e2) | Jun 18, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | [1dbf6320bc](https://linux-hardware.org/?probe=1dbf6320bc) | Jun 18, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| Apple         | MacBookPro5,3               | [aace637cfc](https://linux-hardware.org/?probe=aace637cfc) | Jun 17, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | [bf18000c3c](https://linux-hardware.org/?probe=bf18000c3c) | Jun 17, 2022 |
| MSI           | Raider GE66 12UGS           | [d69dc59622](https://linux-hardware.org/?probe=d69dc59622) | Jun 16, 2022 |
| Apple         | MacBookPro5,3               | [06bef31587](https://linux-hardware.org/?probe=06bef31587) | Jun 16, 2022 |
| Acer          | Aspire E1-570G              | [060b0319ff](https://linux-hardware.org/?probe=060b0319ff) | Jun 15, 2022 |
| Dell          | XPS 15 9560                 | [8faa0f9e6a](https://linux-hardware.org/?probe=8faa0f9e6a) | Jun 14, 2022 |
| ASUSTek       | UX51VZ                      | [d58122ba72](https://linux-hardware.org/?probe=d58122ba72) | Jun 13, 2022 |
| HP            | 620                         | [fe1a420f17](https://linux-hardware.org/?probe=fe1a420f17) | Jun 13, 2022 |
| HP            | EliteBook 2570p             | [8b6f8e8952](https://linux-hardware.org/?probe=8b6f8e8952) | Jun 13, 2022 |
| Jumper        | EZpad                       | [3a5e6bc998](https://linux-hardware.org/?probe=3a5e6bc998) | Jun 13, 2022 |
| Dell          | Inspiron 1428               | [e47c98983f](https://linux-hardware.org/?probe=e47c98983f) | Jun 13, 2022 |
| HP            | EliteBook 8460p             | [e65bd18434](https://linux-hardware.org/?probe=e65bd18434) | Jun 12, 2022 |
| Dell          | Inspiron 3521               | [13a04a66d8](https://linux-hardware.org/?probe=13a04a66d8) | Jun 12, 2022 |
| Dell          | Inspiron 15-3567            | [013de61252](https://linux-hardware.org/?probe=013de61252) | Jun 12, 2022 |
| HP            | Pavilion dv7                | [7f7678265b](https://linux-hardware.org/?probe=7f7678265b) | Jun 11, 2022 |
| HP            | Pavilion dv7                | [c8d1e1be32](https://linux-hardware.org/?probe=c8d1e1be32) | Jun 10, 2022 |
| TUXEDO        | Pulse 15 Gen1               | [2c789d1a84](https://linux-hardware.org/?probe=2c789d1a84) | Jun 10, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | [011acdab42](https://linux-hardware.org/?probe=011acdab42) | Jun 09, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | [c751dcffff](https://linux-hardware.org/?probe=c751dcffff) | Jun 09, 2022 |
| HP            | Pavilion dv6                | [88a92966a3](https://linux-hardware.org/?probe=88a92966a3) | Jun 09, 2022 |
| Dell          | Latitude 5590               | [befc14c3db](https://linux-hardware.org/?probe=befc14c3db) | Jun 09, 2022 |
| Dell          | Latitude 5590               | [0c8e1f9f23](https://linux-hardware.org/?probe=0c8e1f9f23) | Jun 09, 2022 |
| MSI           | GP76 Leopard 11UH           | [8a3c021b8a](https://linux-hardware.org/?probe=8a3c021b8a) | Jun 08, 2022 |
| System76      | Kudu Professional           | [4ffc6fc358](https://linux-hardware.org/?probe=4ffc6fc358) | Jun 08, 2022 |
| System76      | Kudu Professional           | [0c0e2ed5b2](https://linux-hardware.org/?probe=0c0e2ed5b2) | Jun 08, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [54a2c4fa94](https://linux-hardware.org/?probe=54a2c4fa94) | Jun 08, 2022 |
| HP            | 620                         | [1adcb99573](https://linux-hardware.org/?probe=1adcb99573) | Jun 07, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | [f4c82e1fb6](https://linux-hardware.org/?probe=f4c82e1fb6) | Jun 07, 2022 |
| HP            | OMEN by Laptop 17-cb0xxx    | [1dea88e6b2](https://linux-hardware.org/?probe=1dea88e6b2) | Jun 07, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [42aaad44bc](https://linux-hardware.org/?probe=42aaad44bc) | Jun 06, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| Toshiba       | Satellite C75D-A            | [a5aee20b56](https://linux-hardware.org/?probe=a5aee20b56) | Jun 06, 2022 |
| Positivo      | Q464C                       | [e00b91e529](https://linux-hardware.org/?probe=e00b91e529) | Jun 06, 2022 |
| Dell          | Latitude 5590               | [be30c04869](https://linux-hardware.org/?probe=be30c04869) | Jun 05, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [065dee2160](https://linux-hardware.org/?probe=065dee2160) | Jun 04, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | [de4976b9dd](https://linux-hardware.org/?probe=de4976b9dd) | Jun 04, 2022 |
| Dell          | Latitude 5590               | [cc94c06259](https://linux-hardware.org/?probe=cc94c06259) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [5e57fb2871](https://linux-hardware.org/?probe=5e57fb2871) | Jun 04, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | [11ec221a7e](https://linux-hardware.org/?probe=11ec221a7e) | Jun 04, 2022 |
| HP            | ProBook 650 G2              | [a580e923a7](https://linux-hardware.org/?probe=a580e923a7) | Jun 03, 2022 |
| Dell          | Latitude E5470              | [e858488f6f](https://linux-hardware.org/?probe=e858488f6f) | Jun 03, 2022 |
| MSI           | CX61 2PC                    | [d3decdad4c](https://linux-hardware.org/?probe=d3decdad4c) | Jun 03, 2022 |
| HP            | ProBook 650 G2              | [27063b3b3a](https://linux-hardware.org/?probe=27063b3b3a) | Jun 03, 2022 |
| Dell          | Latitude 7420               | [b2ba370a59](https://linux-hardware.org/?probe=b2ba370a59) | Jun 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | [66e01e7706](https://linux-hardware.org/?probe=66e01e7706) | Jun 02, 2022 |
| SK hynix      | Onnyx III                   | [a04d3f7fd9](https://linux-hardware.org/?probe=a04d3f7fd9) | Jun 01, 2022 |
| ASUSTek       | TX201LA                     | [ba677dadab](https://linux-hardware.org/?probe=ba677dadab) | Jun 01, 2022 |
| Toshiba       | Satellite L50-A-1D6         | [0436371728](https://linux-hardware.org/?probe=0436371728) | Jun 01, 2022 |
| Toshiba       | Satellite L50-A-1D6         | [20d1a7e37b](https://linux-hardware.org/?probe=20d1a7e37b) | Jun 01, 2022 |
| Dell          | Inspiron 7537               | [2861999420](https://linux-hardware.org/?probe=2861999420) | Jun 01, 2022 |
| Dell          | Inspiron 7537               | [103bb197fa](https://linux-hardware.org/?probe=103bb197fa) | Jun 01, 2022 |
| Dell          | G7 7588                     | [3e41b876c2](https://linux-hardware.org/?probe=3e41b876c2) | May 31, 2022 |
| Dell          | Vostro 5481                 | [5fd6fe3593](https://linux-hardware.org/?probe=5fd6fe3593) | May 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | [6378f52a92](https://linux-hardware.org/?probe=6378f52a92) | May 31, 2022 |
| Acer          | Aspire AV15-51              | [a9183103ee](https://linux-hardware.org/?probe=a9183103ee) | May 31, 2022 |
| Google        | Coral                       | [c517ad03c1](https://linux-hardware.org/?probe=c517ad03c1) | May 30, 2022 |
| Dell          | Precision 7710              | [f24e29d104](https://linux-hardware.org/?probe=f24e29d104) | May 30, 2022 |
| Dell          | Precision 7710              | [1bae5a0bf0](https://linux-hardware.org/?probe=1bae5a0bf0) | May 30, 2022 |
| ASUSTek       | X540LA                      | [57e0b15d17](https://linux-hardware.org/?probe=57e0b15d17) | May 30, 2022 |
| HP            | Pavilion g4                 | [39cdebfff4](https://linux-hardware.org/?probe=39cdebfff4) | May 29, 2022 |
| Medion        | S6445 MD61489               | [a933286b06](https://linux-hardware.org/?probe=a933286b06) | May 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [177e92d46b](https://linux-hardware.org/?probe=177e92d46b) | May 28, 2022 |
| TUXEDO        | Polaris 15 AMD Gen1         | [f592de92c2](https://linux-hardware.org/?probe=f592de92c2) | May 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Gigabyte      | AORUS 15 XE4                | [f56ba4f49d](https://linux-hardware.org/?probe=f56ba4f49d) | May 27, 2022 |
| HUAWEI        | CREM-WXX9                   | [5410acf8ab](https://linux-hardware.org/?probe=5410acf8ab) | May 25, 2022 |
| Dell          | Vostro 5625                 | [2ae97190b6](https://linux-hardware.org/?probe=2ae97190b6) | May 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | [887985e68a](https://linux-hardware.org/?probe=887985e68a) | May 24, 2022 |
| Acer          | Aspire M5-581TG             | [c6ffc6271c](https://linux-hardware.org/?probe=c6ffc6271c) | May 23, 2022 |
| HP            | 15                          | [a61f6dd1eb](https://linux-hardware.org/?probe=a61f6dd1eb) | May 23, 2022 |
| Acer          | Aspire A515-55              | [52dce4d0c3](https://linux-hardware.org/?probe=52dce4d0c3) | May 23, 2022 |
| Acer          | Swift SFX14-41G             | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| Lenovo        | ThinkPad T400 6474AL9       | [06ec4e94a2](https://linux-hardware.org/?probe=06ec4e94a2) | May 22, 2022 |
| Acer          | Aspire E5-573               | [dce8b618f8](https://linux-hardware.org/?probe=dce8b618f8) | May 22, 2022 |
| Toshiba       | PORTEGE Z10t-A              | [8266843e53](https://linux-hardware.org/?probe=8266843e53) | May 19, 2022 |
| Dell          | Inspiron 7572               | [b7747e3ea4](https://linux-hardware.org/?probe=b7747e3ea4) | May 19, 2022 |
| Dell          | Inspiron 5593               | [e08308603a](https://linux-hardware.org/?probe=e08308603a) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [0d4945774e](https://linux-hardware.org/?probe=0d4945774e) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | [e771dc589b](https://linux-hardware.org/?probe=e771dc589b) | May 18, 2022 |
| Acer          | Aspire A515-55              | [c01f14c77f](https://linux-hardware.org/?probe=c01f14c77f) | May 18, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | [0571b7cb83](https://linux-hardware.org/?probe=0571b7cb83) | May 18, 2022 |
| Acer          | Predator PH315-53           | [eb5d08e402](https://linux-hardware.org/?probe=eb5d08e402) | May 18, 2022 |
| Lenovo        | G780 20138                  | [ee6e90c751](https://linux-hardware.org/?probe=ee6e90c751) | May 17, 2022 |
| HP            | ProBook 6470b               | [0581bb1005](https://linux-hardware.org/?probe=0581bb1005) | May 17, 2022 |
| HP            | Unknown                     | [796c00a0cd](https://linux-hardware.org/?probe=796c00a0cd) | May 15, 2022 |
| HP            | ProBook 6570b               | [e8c38d4e97](https://linux-hardware.org/?probe=e8c38d4e97) | May 15, 2022 |
| Apple         | MacBookPro13,2              | [68e687c794](https://linux-hardware.org/?probe=68e687c794) | May 14, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [beaf18770e](https://linux-hardware.org/?probe=beaf18770e) | May 12, 2022 |
| HUAWEI        | CREM-WXX9                   | [dba988f81d](https://linux-hardware.org/?probe=dba988f81d) | May 10, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [2ba7ecdb55](https://linux-hardware.org/?probe=2ba7ecdb55) | May 10, 2022 |
| Dell          | Latitude E6540              | [a5bb9f2b58](https://linux-hardware.org/?probe=a5bb9f2b58) | May 10, 2022 |
| HP            | ProBook 470 G1              | [cb4ef48c3d](https://linux-hardware.org/?probe=cb4ef48c3d) | May 10, 2022 |
| Dell          | XPS 13 9370                 | [f90e5f669e](https://linux-hardware.org/?probe=f90e5f669e) | May 09, 2022 |
| Toshiba       | Satellite C650D             | [8aefcd7551](https://linux-hardware.org/?probe=8aefcd7551) | May 08, 2022 |
| HP            | ProBook 470 G1              | [a20a5df1ad](https://linux-hardware.org/?probe=a20a5df1ad) | May 06, 2022 |
| HP            | ProBook 6470b               | [7849fd57dc](https://linux-hardware.org/?probe=7849fd57dc) | May 06, 2022 |
| HUAWEI        | HVY-WXX9                    | [8eb673ec29](https://linux-hardware.org/?probe=8eb673ec29) | May 06, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | [ef836a5eca](https://linux-hardware.org/?probe=ef836a5eca) | May 06, 2022 |
| Acer          | Nitro AN515-45              | [aefe7a52e0](https://linux-hardware.org/?probe=aefe7a52e0) | May 06, 2022 |
| Apple         | MacBookPro11,2              | [0af35aa835](https://linux-hardware.org/?probe=0af35aa835) | May 06, 2022 |
| ASUSTek       | X550JX                      | [b420f9214c](https://linux-hardware.org/?probe=b420f9214c) | May 06, 2022 |
| HP            | 2000                        | [1616d82d8e](https://linux-hardware.org/?probe=1616d82d8e) | May 05, 2022 |
| HP            | 2000                        | [f6f20fd25e](https://linux-hardware.org/?probe=f6f20fd25e) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [df622f284f](https://linux-hardware.org/?probe=df622f284f) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | [d861de9453](https://linux-hardware.org/?probe=d861de9453) | May 04, 2022 |
| HP            | ProBook 6450b               | [0c23a5cbc2](https://linux-hardware.org/?probe=0c23a5cbc2) | May 04, 2022 |
| HP            | Pavilion dv7                | [978f98cef3](https://linux-hardware.org/?probe=978f98cef3) | May 04, 2022 |
| Alienware     | 17                          | [1a4cd056f8](https://linux-hardware.org/?probe=1a4cd056f8) | May 04, 2022 |
| Toshiba       | Satellite C650D             | [ce16326df2](https://linux-hardware.org/?probe=ce16326df2) | May 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [e126640b3b](https://linux-hardware.org/?probe=e126640b3b) | May 03, 2022 |
| Lenovo        | ThinkPad T400 6474AL9       | [b303038c87](https://linux-hardware.org/?probe=b303038c87) | May 01, 2022 |
| Lenovo        | ThinkPad X201 3680AC2       | [5c4515d51e](https://linux-hardware.org/?probe=5c4515d51e) | May 01, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | [d5b6bc1a67](https://linux-hardware.org/?probe=d5b6bc1a67) | May 01, 2022 |
| HP            | Pavilion Laptop 13-bb0xx... | [ae7d5dbb0c](https://linux-hardware.org/?probe=ae7d5dbb0c) | May 01, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [73ee1262a6](https://linux-hardware.org/?probe=73ee1262a6) | Apr 30, 2022 |
| Dell          | XPS 15 9510                 | [52609c3695](https://linux-hardware.org/?probe=52609c3695) | Apr 29, 2022 |
| Lenovo        | Z50-75 80EC                 | [f301c52b41](https://linux-hardware.org/?probe=f301c52b41) | Apr 29, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [9f7923bcd2](https://linux-hardware.org/?probe=9f7923bcd2) | Apr 29, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [12a0105da3](https://linux-hardware.org/?probe=12a0105da3) | Apr 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [57271a5f8b](https://linux-hardware.org/?probe=57271a5f8b) | Apr 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [382d77c2b0](https://linux-hardware.org/?probe=382d77c2b0) | Apr 28, 2022 |
| Acer          | Nitro AN515-57              | [3206e0f075](https://linux-hardware.org/?probe=3206e0f075) | Apr 27, 2022 |
| Unknown       | Unknown                     | [e77a313003](https://linux-hardware.org/?probe=e77a313003) | Apr 27, 2022 |
| HP            | 250 G5 Notebook PC          | [e4ecdec958](https://linux-hardware.org/?probe=e4ecdec958) | Apr 27, 2022 |
| Acer          | Aspire A515-55              | [fa33f58948](https://linux-hardware.org/?probe=fa33f58948) | Apr 27, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [9fffc0babc](https://linux-hardware.org/?probe=9fffc0babc) | Apr 26, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | [b5f175a650](https://linux-hardware.org/?probe=b5f175a650) | Apr 26, 2022 |
| HP            | ENVY 17                     | [c33b35becc](https://linux-hardware.org/?probe=c33b35becc) | Apr 26, 2022 |
| ASUSTek       | G750JS                      | [24dab87910](https://linux-hardware.org/?probe=24dab87910) | Apr 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [e466d79804](https://linux-hardware.org/?probe=e466d79804) | Apr 26, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | [89debf3e0e](https://linux-hardware.org/?probe=89debf3e0e) | Apr 25, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | [8e7b2c79a0](https://linux-hardware.org/?probe=8e7b2c79a0) | Apr 25, 2022 |
| Dell          | Studio 1558                 | [b31435ef0c](https://linux-hardware.org/?probe=b31435ef0c) | Apr 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | [a260bf9ce6](https://linux-hardware.org/?probe=a260bf9ce6) | Apr 24, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | [9877ddeaf6](https://linux-hardware.org/?probe=9877ddeaf6) | Apr 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [99e25e855e](https://linux-hardware.org/?probe=99e25e855e) | Apr 23, 2022 |
| Acer          | Swift SF314-43              | [9ba9e35d88](https://linux-hardware.org/?probe=9ba9e35d88) | Apr 23, 2022 |
| Acer          | Nitro AN515-57              | [848b9d8f5c](https://linux-hardware.org/?probe=848b9d8f5c) | Apr 22, 2022 |
| Acer          | Nitro AN515-57              | [da630d58cf](https://linux-hardware.org/?probe=da630d58cf) | Apr 22, 2022 |
| TUXEDO        | Aura 15 Gen1                | [8ee6cabf43](https://linux-hardware.org/?probe=8ee6cabf43) | Apr 22, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | [28690580aa](https://linux-hardware.org/?probe=28690580aa) | Apr 22, 2022 |
| Dynabook      | PORTEGE X30L-J              | [5894fd3a34](https://linux-hardware.org/?probe=5894fd3a34) | Apr 21, 2022 |
| ASUSTek       | G550JK                      | [566770a325](https://linux-hardware.org/?probe=566770a325) | Apr 21, 2022 |
| Positivo      | W940TU                      | [4d03effd28](https://linux-hardware.org/?probe=4d03effd28) | Apr 20, 2022 |
| Positivo      | W940TU                      | [971493b883](https://linux-hardware.org/?probe=971493b883) | Apr 20, 2022 |
| Dell          | Latitude XT3                | [6db9585e20](https://linux-hardware.org/?probe=6db9585e20) | Apr 20, 2022 |
| Lenovo        | ThinkPad T560 20FJS0NT04    | [19ebdf705a](https://linux-hardware.org/?probe=19ebdf705a) | Apr 20, 2022 |
| Dell          | XPS 15 7590                 | [ee7354dd8d](https://linux-hardware.org/?probe=ee7354dd8d) | Apr 19, 2022 |
| Dell          | Inspiron 15-3567            | [f8e7d70919](https://linux-hardware.org/?probe=f8e7d70919) | Apr 18, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | [4ed718df3e](https://linux-hardware.org/?probe=4ed718df3e) | Apr 18, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | [402c31b107](https://linux-hardware.org/?probe=402c31b107) | Apr 18, 2022 |
| ASUSTek       | S551LB                      | [bb1d6d3623](https://linux-hardware.org/?probe=bb1d6d3623) | Apr 17, 2022 |
| Shanghai Z... | ZXE CRB                     | [fe284f4173](https://linux-hardware.org/?probe=fe284f4173) | Apr 17, 2022 |
| Dell          | Latitude XT3                | [c4d7d751b7](https://linux-hardware.org/?probe=c4d7d751b7) | Apr 17, 2022 |
| Dell          | Latitude 7410               | [da82f8bba8](https://linux-hardware.org/?probe=da82f8bba8) | Apr 15, 2022 |
| Lenovo        | G40-45 80E1                 | [840ffde0c4](https://linux-hardware.org/?probe=840ffde0c4) | Apr 15, 2022 |
| Dell          | Latitude XT3                | [ce6c2e43a0](https://linux-hardware.org/?probe=ce6c2e43a0) | Apr 15, 2022 |
| Dell          | Latitude E6540              | [2ee68b5f38](https://linux-hardware.org/?probe=2ee68b5f38) | Apr 14, 2022 |
| Framework     | Laptop                      | [6846ee88e0](https://linux-hardware.org/?probe=6846ee88e0) | Apr 14, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [45b8eba74c](https://linux-hardware.org/?probe=45b8eba74c) | Apr 14, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | [3e09de906e](https://linux-hardware.org/?probe=3e09de906e) | Apr 14, 2022 |
| Lenovo        | ThinkPad T420 41786UU       | [2211278055](https://linux-hardware.org/?probe=2211278055) | Apr 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [4434290159](https://linux-hardware.org/?probe=4434290159) | Apr 14, 2022 |
| Lenovo        | ThinkPad P51 20HH000AUS     | [b7365a4abd](https://linux-hardware.org/?probe=b7365a4abd) | Apr 14, 2022 |
| Samsung       | R425D/R525D                 | [bd5a2f5943](https://linux-hardware.org/?probe=bd5a2f5943) | Apr 14, 2022 |
| Dell          | XPS 13 9300                 | [a21bd26d1e](https://linux-hardware.org/?probe=a21bd26d1e) | Apr 14, 2022 |
| HUAWEI        | KLVL-WXXW                   | [8888d86504](https://linux-hardware.org/?probe=8888d86504) | Apr 13, 2022 |
| Lenovo        | IdeaPad 710S Plus Touch-... | [f4578ea652](https://linux-hardware.org/?probe=f4578ea652) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [744144c472](https://linux-hardware.org/?probe=744144c472) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | [479b8d48fc](https://linux-hardware.org/?probe=479b8d48fc) | Apr 13, 2022 |
| Lenovo        | ThinkPad T530 24296HG       | [74191e7ffb](https://linux-hardware.org/?probe=74191e7ffb) | Apr 13, 2022 |
| Toshiba       | Satellite P70-B             | [6c01bb2cc3](https://linux-hardware.org/?probe=6c01bb2cc3) | Apr 13, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | [de2cf28654](https://linux-hardware.org/?probe=de2cf28654) | Apr 13, 2022 |
| Dell          | Latitude 5591               | [3f3f097a1a](https://linux-hardware.org/?probe=3f3f097a1a) | Apr 13, 2022 |
| Dell          | Latitude 7400               | [2c32d69a57](https://linux-hardware.org/?probe=2c32d69a57) | Apr 13, 2022 |
| HP            | Pavilion g6                 | [44035cfa83](https://linux-hardware.org/?probe=44035cfa83) | Apr 13, 2022 |
| Dell          | Precision 5520              | [eb5bfc87ed](https://linux-hardware.org/?probe=eb5bfc87ed) | Apr 12, 2022 |
| Lenovo        | ThinkPad T430 2349T2A       | [344710cc3a](https://linux-hardware.org/?probe=344710cc3a) | Apr 12, 2022 |
| HONOR         | NBD-WXX9                    | [090560f0c5](https://linux-hardware.org/?probe=090560f0c5) | Apr 12, 2022 |
| Lenovo        | IdeaPad Z585                | [5f84c70657](https://linux-hardware.org/?probe=5f84c70657) | Apr 10, 2022 |
| Notebook      | NS50_70MU                   | [cf76bb9e39](https://linux-hardware.org/?probe=cf76bb9e39) | Apr 10, 2022 |
| Dell          | G7 7790                     | [6cdb296d8e](https://linux-hardware.org/?probe=6cdb296d8e) | Apr 10, 2022 |
| Dell          | Vostro 15 3515              | [848a486145](https://linux-hardware.org/?probe=848a486145) | Apr 10, 2022 |
| eMachines     | G525                        | [6ba45c519c](https://linux-hardware.org/?probe=6ba45c519c) | Apr 09, 2022 |
| HP            | Laptop 14s-fq0xxx           | [18045cb759](https://linux-hardware.org/?probe=18045cb759) | Apr 09, 2022 |
| Positivo      | N1250                       | [c64a47d6fc](https://linux-hardware.org/?probe=c64a47d6fc) | Apr 09, 2022 |
| Sony          | VPCF236FM                   | [ea109b146b](https://linux-hardware.org/?probe=ea109b146b) | Apr 08, 2022 |
| Sony          | SVE1511W1ESI                | [403773664b](https://linux-hardware.org/?probe=403773664b) | Apr 08, 2022 |
| Dell          | Latitude 5480               | [6891954221](https://linux-hardware.org/?probe=6891954221) | Apr 08, 2022 |
| HP            | ENVY 15                     | [cdd8aea3c3](https://linux-hardware.org/?probe=cdd8aea3c3) | Apr 07, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [dea231bf61](https://linux-hardware.org/?probe=dea231bf61) | Apr 07, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | [b02ac7d8ce](https://linux-hardware.org/?probe=b02ac7d8ce) | Apr 07, 2022 |
| Dell          | XPS 13 9310                 | [64c2c15492](https://linux-hardware.org/?probe=64c2c15492) | Apr 05, 2022 |
| Wortmann      | TERRA_MOBILE_1749           | [ee8ada5124](https://linux-hardware.org/?probe=ee8ada5124) | Apr 05, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | [f72149904c](https://linux-hardware.org/?probe=f72149904c) | Apr 05, 2022 |
| Lenovo        | ThinkPad X260 20F5S0W22B    | [765eaec64d](https://linux-hardware.org/?probe=765eaec64d) | Apr 04, 2022 |
| Dell          | Latitude E6530              | [a63f363043](https://linux-hardware.org/?probe=a63f363043) | Apr 04, 2022 |
| Lenovo        | IdeaPadFlex 14 20308        | [9ecbc31fc2](https://linux-hardware.org/?probe=9ecbc31fc2) | Apr 04, 2022 |
| Dell          | Latitude E6540              | [e087a37f5f](https://linux-hardware.org/?probe=e087a37f5f) | Apr 02, 2022 |
| Lenovo        | ThinkPad T540p 20BEA00FR... | [c9323a9c40](https://linux-hardware.org/?probe=c9323a9c40) | Mar 31, 2022 |
| Dell          | XPS 13 9305                 | [946628cb20](https://linux-hardware.org/?probe=946628cb20) | Mar 30, 2022 |
| Dell          | Vostro 15 3515              | [b61b3e31e7](https://linux-hardware.org/?probe=b61b3e31e7) | Mar 30, 2022 |
| HUAWEI        | BOHB-WAX9                   | [f398041b40](https://linux-hardware.org/?probe=f398041b40) | Mar 29, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | [323ca65327](https://linux-hardware.org/?probe=323ca65327) | Mar 28, 2022 |
| HP            | Pavilion 14                 | [1b15a2e740](https://linux-hardware.org/?probe=1b15a2e740) | Mar 28, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [f457ad3a65](https://linux-hardware.org/?probe=f457ad3a65) | Mar 27, 2022 |
| HP            | Stream Notebook PC 14       | [9fc309dcaf](https://linux-hardware.org/?probe=9fc309dcaf) | Mar 27, 2022 |
| Positivo      | Q232A                       | [fe29ba6b10](https://linux-hardware.org/?probe=fe29ba6b10) | Mar 27, 2022 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | [a9a4291601](https://linux-hardware.org/?probe=a9a4291601) | Mar 26, 2022 |
| Dell          | Latitude 5290 2-in-1        | [f0a08eb35b](https://linux-hardware.org/?probe=f0a08eb35b) | Mar 25, 2022 |
| Dell          | Inspiron 5379               | [85c7a99f91](https://linux-hardware.org/?probe=85c7a99f91) | Mar 25, 2022 |
| Avell High... | B.ON                        | [19b689aa12](https://linux-hardware.org/?probe=19b689aa12) | Mar 25, 2022 |
| Apple         | MacBookPro14,1              | [a2db3c2cab](https://linux-hardware.org/?probe=a2db3c2cab) | Mar 24, 2022 |
| Razer         | Blade 15 Advanced Model ... | [cb089466a3](https://linux-hardware.org/?probe=cb089466a3) | Mar 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [c136393c4b](https://linux-hardware.org/?probe=c136393c4b) | Mar 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | [713ff9dcb8](https://linux-hardware.org/?probe=713ff9dcb8) | Mar 23, 2022 |
| Dell          | XPS 15 7590                 | [96244433f0](https://linux-hardware.org/?probe=96244433f0) | Mar 23, 2022 |
| Acer          | Swift SF314-54G             | [615009b8ee](https://linux-hardware.org/?probe=615009b8ee) | Mar 23, 2022 |
| ASUSTek       | N550LF                      | [5e5462ce64](https://linux-hardware.org/?probe=5e5462ce64) | Mar 23, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | [5b74db2557](https://linux-hardware.org/?probe=5b74db2557) | Mar 22, 2022 |
| MSI           | GP76 Leopard 11UH           | [d398e3284e](https://linux-hardware.org/?probe=d398e3284e) | Mar 22, 2022 |
| Dell          | XPS 13 9310                 | [c90c0f1819](https://linux-hardware.org/?probe=c90c0f1819) | Mar 22, 2022 |
| ASUSTek       | X555LNB                     | [ae49172b0f](https://linux-hardware.org/?probe=ae49172b0f) | Mar 21, 2022 |
| ASUSTek       | X555LNB                     | [33e081f100](https://linux-hardware.org/?probe=33e081f100) | Mar 21, 2022 |
| Dell          | System Inspiron N7110       | [d3b1757cf5](https://linux-hardware.org/?probe=d3b1757cf5) | Mar 21, 2022 |
| ASUSTek       | K73E                        | [75069bd642](https://linux-hardware.org/?probe=75069bd642) | Mar 20, 2022 |
| Apple         | MacBookPro12,1              | [0e4992c717](https://linux-hardware.org/?probe=0e4992c717) | Mar 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | [3607969e9d](https://linux-hardware.org/?probe=3607969e9d) | Mar 20, 2022 |
| Panasonic     | FZ-M1CC-51BE                | [94e014ee40](https://linux-hardware.org/?probe=94e014ee40) | Mar 18, 2022 |
| ASUSTek       | K52Jr                       | [b05ec1dbda](https://linux-hardware.org/?probe=b05ec1dbda) | Mar 18, 2022 |
| Dell          | Precision M6300             | [aac71b9e66](https://linux-hardware.org/?probe=aac71b9e66) | Mar 17, 2022 |
| ASUSTek       | K52Jr                       | [77c6485b0f](https://linux-hardware.org/?probe=77c6485b0f) | Mar 17, 2022 |
| HP            | EliteBook 850 G5            | [6d8c8748e2](https://linux-hardware.org/?probe=6d8c8748e2) | Mar 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [8713806c38](https://linux-hardware.org/?probe=8713806c38) | Mar 17, 2022 |
| HP            | ProBook 430 G2              | [e2ad81141c](https://linux-hardware.org/?probe=e2ad81141c) | Mar 16, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [8e9c955b47](https://linux-hardware.org/?probe=8e9c955b47) | Mar 15, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | [bf80f02a40](https://linux-hardware.org/?probe=bf80f02a40) | Mar 15, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | [95c6b15672](https://linux-hardware.org/?probe=95c6b15672) | Mar 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [96b413780f](https://linux-hardware.org/?probe=96b413780f) | Mar 13, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [8ab5133b14](https://linux-hardware.org/?probe=8ab5133b14) | Mar 13, 2022 |
| Lenovo        | B580 20144                  | [9918c132f0](https://linux-hardware.org/?probe=9918c132f0) | Mar 13, 2022 |
| Lenovo        | B580 20144                  | [fd9ec44205](https://linux-hardware.org/?probe=fd9ec44205) | Mar 13, 2022 |
| Dell          | Latitude E6430              | [bc21cb0e8b](https://linux-hardware.org/?probe=bc21cb0e8b) | Mar 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | [4998fff0f9](https://linux-hardware.org/?probe=4998fff0f9) | Mar 12, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [e39d0d9111](https://linux-hardware.org/?probe=e39d0d9111) | Mar 11, 2022 |
| Acer          | Nitro AN515-56              | [39cdee5411](https://linux-hardware.org/?probe=39cdee5411) | Mar 11, 2022 |
| Acer          | Aspire 5750G                | [066fecf595](https://linux-hardware.org/?probe=066fecf595) | Mar 10, 2022 |
| Dell          | XPS 13 9310                 | [e7a3d16cc0](https://linux-hardware.org/?probe=e7a3d16cc0) | Mar 09, 2022 |
| Lenovo        | ThinkPad X220 4290EC5       | [508a68f09e](https://linux-hardware.org/?probe=508a68f09e) | Mar 09, 2022 |
| ASUSTek       | ZenBook UX435EG_UX435EG     | [8dbe399133](https://linux-hardware.org/?probe=8dbe399133) | Mar 08, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | [c7025ac75e](https://linux-hardware.org/?probe=c7025ac75e) | Mar 08, 2022 |
| ASUSTek       | UX331UN                     | [f1cf640532](https://linux-hardware.org/?probe=f1cf640532) | Mar 06, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [052e483cb5](https://linux-hardware.org/?probe=052e483cb5) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | [949d0886a1](https://linux-hardware.org/?probe=949d0886a1) | Mar 06, 2022 |
| MSI           | Katana GF76 11UC            | [f5241bc829](https://linux-hardware.org/?probe=f5241bc829) | Mar 05, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [7a52c91d68](https://linux-hardware.org/?probe=7a52c91d68) | Mar 05, 2022 |
| Unknown       | KN12A                       | [3ba6165509](https://linux-hardware.org/?probe=3ba6165509) | Mar 05, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [1c879cd60e](https://linux-hardware.org/?probe=1c879cd60e) | Mar 04, 2022 |
| Dell          | Vostro 5470                 | [fda73ff759](https://linux-hardware.org/?probe=fda73ff759) | Mar 02, 2022 |
| Dell          | Latitude E6530              | [f13c84346e](https://linux-hardware.org/?probe=f13c84346e) | Mar 02, 2022 |
| ASUSTek       | UX331UN                     | [463899cdb7](https://linux-hardware.org/?probe=463899cdb7) | Mar 02, 2022 |
| ASUSTek       | K55N                        | [6143b27a96](https://linux-hardware.org/?probe=6143b27a96) | Mar 02, 2022 |
| MSI           | Katana GF76 11UC            | [880490eb1e](https://linux-hardware.org/?probe=880490eb1e) | Mar 01, 2022 |
| Schenker      | VIA 15                      | [c84aacc342](https://linux-hardware.org/?probe=c84aacc342) | Feb 28, 2022 |
| Acer          | Aspire A515-45              | [f2e18241da](https://linux-hardware.org/?probe=f2e18241da) | Feb 28, 2022 |
| MSI           | Katana GF76 11UC            | [79cc0b97a4](https://linux-hardware.org/?probe=79cc0b97a4) | Feb 28, 2022 |
| MSI           | Katana GF76 11UC            | [74bc866ab2](https://linux-hardware.org/?probe=74bc866ab2) | Feb 27, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [c7db8c9806](https://linux-hardware.org/?probe=c7db8c9806) | Feb 27, 2022 |
| HP            | Notebook                    | [bcc74ebe77](https://linux-hardware.org/?probe=bcc74ebe77) | Feb 27, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U5S... | [f86d99b8a1](https://linux-hardware.org/?probe=f86d99b8a1) | Feb 27, 2022 |
| Dell          | Inspiron 3583               | [83dec4f285](https://linux-hardware.org/?probe=83dec4f285) | Feb 26, 2022 |
| Acer          | Aspire E5-553G              | [17586d38de](https://linux-hardware.org/?probe=17586d38de) | Feb 26, 2022 |
| HUAWEI        | HVY-WXX9                    | [fb4c469104](https://linux-hardware.org/?probe=fb4c469104) | Feb 26, 2022 |
| HUAWEI        | HVY-WXX9                    | [9013eb37ee](https://linux-hardware.org/?probe=9013eb37ee) | Feb 25, 2022 |
| Dell          | XPS 15 9560                 | [4c72ebcb41](https://linux-hardware.org/?probe=4c72ebcb41) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | [7aa852e941](https://linux-hardware.org/?probe=7aa852e941) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | [67297aad2c](https://linux-hardware.org/?probe=67297aad2c) | Feb 25, 2022 |
| HP            | EliteBook 745 G3            | [eed2589bd2](https://linux-hardware.org/?probe=eed2589bd2) | Feb 25, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | [013e049a4d](https://linux-hardware.org/?probe=013e049a4d) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | [885239a137](https://linux-hardware.org/?probe=885239a137) | Feb 24, 2022 |
| Dell          | Inspiron 1525               | [904717059e](https://linux-hardware.org/?probe=904717059e) | Feb 24, 2022 |
| Toshiba       | IS 1412                     | [3621d1064d](https://linux-hardware.org/?probe=3621d1064d) | Feb 24, 2022 |
| ASUSTek       | X550JX                      | [ec93ded12b](https://linux-hardware.org/?probe=ec93ded12b) | Feb 23, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Kubuntu 20.04   | 737       | 37.66%  |
| Kubuntu 22.04   | 387       | 19.78%  |
| Kubuntu 21.10   | 151       | 7.72%   |
| Kubuntu 20.10   | 141       | 7.2%    |
| Kubuntu 21.04   | 126       | 6.44%   |
| Kubuntu 22.10   | 113       | 5.77%   |
| Kubuntu 19.10   | 105       | 5.37%   |
| Kubuntu 18.04   | 102       | 5.21%   |
| Kubuntu 11      | 44        | 2.25%   |
| Kubuntu 11.1    | 18        | 0.92%   |
| Kubuntu 19.04   | 9         | 0.46%   |
| Kubuntu 23.04   | 5         | 0.26%   |
| Kubuntu 2.0     | 4         | 0.2%    |
| Kubuntu 16.04   | 4         | 0.2%    |
| Kubuntu 18.10   | 3         | 0.15%   |
| Kubuntu         | 3         | 0.15%   |
| Kubuntu 14.04   | 2         | 0.1%    |
| Kubuntu 20.08.3 | 1         | 0.05%   |
| Kubuntu 17.10   | 1         | 0.05%   |
| Kubuntu 17.04   | 1         | 0.05%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Kubuntu | 1885      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 55        | 2.58%   |
| 5.15.0-52-generic | 51        | 2.39%   |
| 5.15.0-56-generic | 43        | 2.02%   |
| 5.4.0-52-generic  | 35        | 1.64%   |
| 5.13.0-39-generic | 35        | 1.64%   |
| 5.4.0-48-generic  | 34        | 1.59%   |
| 5.15.0-48-generic | 30        | 1.41%   |
| 5.15.0-58-generic | 28        | 1.31%   |
| 5.4.0-58-generic  | 27        | 1.27%   |
| 5.19.0-26-generic | 27        | 1.27%   |
| 5.13.0-28-generic | 27        | 1.27%   |
| 5.15.0-46-generic | 26        | 1.22%   |
| 5.13.0-30-generic | 26        | 1.22%   |
| 5.19.0-23-generic | 25        | 1.17%   |
| 5.11.0-25-generic | 25        | 1.17%   |
| 5.4.0-40-generic  | 24        | 1.13%   |
| 5.15.0-53-generic | 23        | 1.08%   |
| 5.3.0-40-generic  | 22        | 1.03%   |
| 5.19.0-31-generic | 21        | 0.98%   |
| 5.15.0-47-generic | 21        | 0.98%   |
| 5.15.0-43-generic | 21        | 0.98%   |
| 5.11.0-37-generic | 21        | 0.98%   |
| 5.15.0-60-generic | 20        | 0.94%   |
| 5.15.0-41-generic | 20        | 0.94%   |
| 5.4.0-47-generic  | 19        | 0.89%   |
| 5.4.0-29-generic  | 19        | 0.89%   |
| 5.13.0-22-generic | 19        | 0.89%   |
| 5.4.0-37-generic  | 18        | 0.84%   |
| 5.13.0-27-generic | 18        | 0.84%   |
| 5.4.0-65-generic  | 17        | 0.8%    |
| 5.3.0-42-generic  | 17        | 0.8%    |
| 5.13.0-40-generic | 17        | 0.8%    |
| 5.11.0-38-generic | 17        | 0.8%    |
| 5.8.0-63-generic  | 16        | 0.75%   |
| 5.8.0-48-generic  | 16        | 0.75%   |
| 5.8.0-44-generic  | 16        | 0.75%   |
| 5.15.0-50-generic | 16        | 0.75%   |
| 5.13.0-44-generic | 16        | 0.75%   |
| 5.13.0-35-generic | 16        | 0.75%   |
| 5.4.0-56-generic  | 15        | 0.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 478       | 24.01%  |
| 5.15.0  | 397       | 19.94%  |
| 5.13.0  | 259       | 13.01%  |
| 5.8.0   | 220       | 11.05%  |
| 5.11.0  | 184       | 9.24%   |
| 5.3.0   | 129       | 6.48%   |
| 5.19.0  | 105       | 5.27%   |
| 4.15.0  | 38        | 1.91%   |
| 5.0.0   | 17        | 0.85%   |
| 5.10.0  | 13        | 0.65%   |
| 5.17.0  | 10        | 0.5%    |
| 5.6.0   | 7         | 0.35%   |
| 6.0.0   | 6         | 0.3%    |
| 5.14.0  | 6         | 0.3%    |
| 6.1.0   | 4         | 0.2%    |
| 6.0.9   | 4         | 0.2%    |
| 5.7.0   | 4         | 0.2%    |
| 4.4.0   | 4         | 0.2%    |
| 4.18.0  | 4         | 0.2%    |
| 5.12.0  | 3         | 0.15%   |
| 6.1.8   | 2         | 0.1%    |
| 6.1.12  | 2         | 0.1%    |
| 6.0.7   | 2         | 0.1%    |
| 5.9.10  | 2         | 0.1%    |
| 5.9.0   | 2         | 0.1%    |
| 5.19.5  | 2         | 0.1%    |
| 5.18.10 | 2         | 0.1%    |
| 5.15.5  | 2         | 0.1%    |
| 5.15.34 | 2         | 0.1%    |
| 5.13.1  | 2         | 0.1%    |
| 5.12.8  | 2         | 0.1%    |
| 4.10.0  | 2         | 0.1%    |
| 6.1.9   | 1         | 0.05%   |
| 6.1.7   | 1         | 0.05%   |
| 6.1.6   | 1         | 0.05%   |
| 6.1.5   | 1         | 0.05%   |
| 6.1.11  | 1         | 0.05%   |
| 6.0.6   | 1         | 0.05%   |
| 6.0.1   | 1         | 0.05%   |
| 5.9.8   | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 481       | 24.2%   |
| 5.15    | 407       | 20.47%  |
| 5.13    | 265       | 13.33%  |
| 5.8     | 228       | 11.47%  |
| 5.11    | 188       | 9.46%   |
| 5.3     | 130       | 6.54%   |
| 5.19    | 109       | 5.48%   |
| 4.15    | 38        | 1.91%   |
| 5.10    | 17        | 0.86%   |
| 5.0     | 17        | 0.86%   |
| 6.1     | 13        | 0.65%   |
| 6.0     | 13        | 0.65%   |
| 5.17    | 13        | 0.65%   |
| 5.14    | 12        | 0.6%    |
| 5.12    | 9         | 0.45%   |
| 5.6     | 8         | 0.4%    |
| 5.9     | 7         | 0.35%   |
| 5.7     | 6         | 0.3%    |
| 5.18    | 5         | 0.25%   |
| 5.16    | 5         | 0.25%   |
| 4.18    | 5         | 0.25%   |
| 4.4     | 4         | 0.2%    |
| 5.5     | 3         | 0.15%   |
| 4.10    | 2         | 0.1%    |
| 5.1     | 1         | 0.05%   |
| 4.17    | 1         | 0.05%   |
| 4.13    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1882      | 99.84%  |
| i686   | 3         | 0.16%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| KDE5       | 1406      | 73.34%  |
| KDE        | 484       | 25.25%  |
| GNOME      | 10        | 0.52%   |
| Cinnamon   | 4         | 0.21%   |
| MATE       | 3         | 0.16%   |
| Budgie     | 3         | 0.16%   |
| KDE4       | 2         | 0.1%    |
| X-Cinnamon | 1         | 0.05%   |
| LXQt       | 1         | 0.05%   |
| i3         | 1         | 0.05%   |
| GNUstep    | 1         | 0.05%   |
| Unknown    | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1814      | 95.47%  |
| Wayland | 72        | 3.79%   |
| Tty     | 14        | 0.74%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 1139      | 59.45%  |
| Unknown | 654       | 34.13%  |
| GDM     | 58        | 3.03%   |
| GDM3    | 30        | 1.57%   |
| LightDM | 22        | 1.15%   |
| TDM     | 11        | 0.57%   |
| SLiM    | 1         | 0.05%   |
| LXDM    | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 797       | 41.9%   |
| de_DE   | 142       | 7.47%   |
| ru_RU   | 101       | 5.31%   |
| pt_BR   | 93        | 4.89%   |
| it_IT   | 86        | 4.52%   |
| fr_FR   | 77        | 4.05%   |
| en_GB   | 77        | 4.05%   |
| en_IN   | 47        | 2.47%   |
| es_ES   | 44        | 2.31%   |
| en_CA   | 43        | 2.26%   |
| Unknown | 43        | 2.26%   |
| pl_PL   | 34        | 1.79%   |
| en_AU   | 28        | 1.47%   |
| C       | 17        | 0.89%   |
| es_MX   | 16        | 0.84%   |
| hu_HU   | 15        | 0.79%   |
| ru_UA   | 14        | 0.74%   |
| cs_CZ   | 13        | 0.68%   |
| en_ZA   | 12        | 0.63%   |
| tr_TR   | 10        | 0.53%   |
| nl_NL   | 10        | 0.53%   |
| en_NZ   | 10        | 0.53%   |
| es_AR   | 7         | 0.37%   |
| en_IE   | 7         | 0.37%   |
| de_CH   | 7         | 0.37%   |
| zh_CN   | 6         | 0.32%   |
| sv_SE   | 6         | 0.32%   |
| pt_PT   | 6         | 0.32%   |
| es_CO   | 6         | 0.32%   |
| sk_SK   | 5         | 0.26%   |
| fr_BE   | 5         | 0.26%   |
| es_VE   | 5         | 0.26%   |
| es_CL   | 5         | 0.26%   |
| en_SG   | 5         | 0.26%   |
| de_AT   | 5         | 0.26%   |
| ca_ES   | 5         | 0.26%   |
| ro_RO   | 4         | 0.21%   |
| nl_BE   | 4         | 0.21%   |
| fr_CH   | 4         | 0.21%   |
| en_PH   | 4         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1176      | 61.44%  |
| BIOS | 738       | 38.56%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1742      | 91.97%  |
| Btrfs   | 66        | 3.48%   |
| Overlay | 52        | 2.75%   |
| Xfs     | 13        | 0.69%   |
| Zfs     | 10        | 0.53%   |
| Unknown | 6         | 0.32%   |
| Ext2    | 3         | 0.16%   |
| Ext3    | 2         | 0.11%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 979       | 51.28%  |
| Unknown | 775       | 40.6%   |
| MBR     | 155       | 8.12%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1705      | 89.97%  |
| Yes       | 190       | 10.03%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1174      | 61.85%  |
| Yes       | 724       | 38.15%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Lenovo                 | 428       | 22.71%  |
| Dell                   | 352       | 18.67%  |
| Hewlett-Packard        | 333       | 17.67%  |
| ASUSTek Computer       | 184       | 9.76%   |
| Acer                   | 146       | 7.75%   |
| MSI                    | 54        | 2.86%   |
| Samsung Electronics    | 38        | 2.02%   |
| HUAWEI                 | 33        | 1.75%   |
| Apple                  | 26        | 1.38%   |
| Toshiba                | 24        | 1.27%   |
| Notebook               | 21        | 1.11%   |
| TUXEDO                 | 19        | 1.01%   |
| Sony                   | 19        | 1.01%   |
| Google                 | 15        | 0.8%    |
| Unknown                | 14        | 0.74%   |
| Timi                   | 13        | 0.69%   |
| Positivo               | 10        | 0.53%   |
| Alienware              | 10        | 0.53%   |
| Gigabyte Technology    | 8         | 0.42%   |
| System76               | 7         | 0.37%   |
| PC Specialist          | 6         | 0.32%   |
| Medion                 | 6         | 0.32%   |
| GPU Company            | 6         | 0.32%   |
| Fujitsu                | 6         | 0.32%   |
| Chuwi                  | 6         | 0.32%   |
| Razer                  | 5         | 0.27%   |
| Panasonic              | 5         | 0.27%   |
| Packard Bell           | 5         | 0.27%   |
| LG Electronics         | 5         | 0.27%   |
| Intel                  | 5         | 0.27%   |
| Schenker               | 4         | 0.21%   |
| Framework              | 4         | 0.21%   |
| HONOR                  | 3         | 0.16%   |
| Haier                  | 3         | 0.16%   |
| Fujitsu Siemens        | 3         | 0.16%   |
| Digma                  | 3         | 0.16%   |
| Clevo                  | 3         | 0.16%   |
| Avell High Performance | 3         | 0.16%   |
| Standard               | 2         | 0.11%   |
| SLIMBOOK               | 2         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                            | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Unknown                         | 25        | 1.33%   |
| HP Notebook                     | 10        | 0.53%   |
| HP Pavilion g6                  | 9         | 0.48%   |
| HP Pavilion dv6                 | 9         | 0.48%   |
| Dell XPS 15 9560                | 9         | 0.48%   |
| HUAWEI NBLK-WAX9X               | 8         | 0.42%   |
| HP Pavilion dv7                 | 7         | 0.37%   |
| HP Pavilion 15                  | 6         | 0.32%   |
| HP EliteBook 840 G5             | 6         | 0.32%   |
| HP EliteBook 840 G3             | 6         | 0.32%   |
| Dell XPS 15 9570                | 6         | 0.32%   |
| HP EliteBook 840 G6             | 5         | 0.27%   |
| GPU Company GWTC116-2           | 5         | 0.27%   |
| Dell XPS 15 7590                | 5         | 0.27%   |
| Dell XPS 13 9310                | 5         | 0.27%   |
| Dell Latitude E6540             | 5         | 0.27%   |
| Dell Latitude 5480              | 5         | 0.27%   |
| Dell Inspiron 5570              | 5         | 0.27%   |
| Lenovo Legion Y530-15ICH 81FV   | 4         | 0.21%   |
| Lenovo IdeaPad S145-15API 81V7  | 4         | 0.21%   |
| Lenovo IdeaPad 5 15ARE05 81YQ   | 4         | 0.21%   |
| Lenovo IdeaPad 330-15IKB 81DE   | 4         | 0.21%   |
| Lenovo G50-70 20351             | 4         | 0.21%   |
| HUAWEI CREM-WXX9                | 4         | 0.21%   |
| HP ProBook 6470b                | 4         | 0.21%   |
| HP Laptop 15s-eq0xxx            | 4         | 0.21%   |
| HP Laptop 15-da0xxx             | 4         | 0.21%   |
| HP EliteBook 845 G7 Notebook PC | 4         | 0.21%   |
| HP 255 G8 Notebook PC           | 4         | 0.21%   |
| HP 2000                         | 4         | 0.21%   |
| HP 15                           | 4         | 0.21%   |
| Dell XPS 15 9500                | 4         | 0.21%   |
| Dell Vostro 5481                | 4         | 0.21%   |
| Dell Latitude 7480              | 4         | 0.21%   |
| Dell Latitude 5580              | 4         | 0.21%   |
| Dell Latitude 3420              | 4         | 0.21%   |
| Dell Inspiron 7577              | 4         | 0.21%   |
| Dell Inspiron 7559              | 4         | 0.21%   |
| Dell G3 3579                    | 4         | 0.21%   |
| Acer Aspire V3-571G             | 4         | 0.21%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 226       | 11.99%  |
| Dell Latitude         | 120       | 6.37%   |
| Acer Aspire           | 89        | 4.72%   |
| Lenovo IdeaPad        | 88        | 4.67%   |
| Dell Inspiron         | 88        | 4.67%   |
| HP Pavilion           | 79        | 4.19%   |
| Dell XPS              | 60        | 3.18%   |
| HP ProBook            | 57        | 3.02%   |
| HP EliteBook          | 50        | 2.65%   |
| HP Laptop             | 49        | 2.6%    |
| ASUS VivoBook         | 40        | 2.12%   |
| Dell Precision        | 32        | 1.7%    |
| Unknown               | 25        | 1.33%   |
| Dell Vostro           | 24        | 1.27%   |
| Acer Nitro            | 23        | 1.22%   |
| Lenovo Legion         | 21        | 1.11%   |
| Toshiba Satellite     | 20        | 1.06%   |
| Lenovo ThinkBook      | 19        | 1.01%   |
| Acer Swift            | 17        | 0.9%    |
| ASUS ASUS             | 15        | 0.8%    |
| ASUS Zenbook          | 14        | 0.74%   |
| HP ENVY               | 13        | 0.69%   |
| ASUS ROG              | 13        | 0.69%   |
| HP Notebook           | 10        | 0.53%   |
| ASUS TUF              | 10        | 0.53%   |
| HP ZBook              | 9         | 0.48%   |
| Dell G3               | 9         | 0.48%   |
| HUAWEI NBLK-WAX9X     | 8         | 0.42%   |
| HP 255                | 8         | 0.42%   |
| HP 250                | 8         | 0.42%   |
| MSI Prestige          | 7         | 0.37%   |
| Lenovo Yoga           | 7         | 0.37%   |
| Acer Predator         | 7         | 0.37%   |
| HP OMEN               | 6         | 0.32%   |
| HP 15                 | 6         | 0.32%   |
| Dell System           | 6         | 0.32%   |
| TUXEDO InfinityBook   | 5         | 0.27%   |
| Razer Blade           | 5         | 0.27%   |
| HP Compaq             | 5         | 0.27%   |
| GPU Company GWTC116-2 | 5         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 262       | 13.9%   |
| 2020 | 253       | 13.42%  |
| 2021 | 197       | 10.45%  |
| 2018 | 180       | 9.55%   |
| 2017 | 134       | 7.11%   |
| 2012 | 130       | 6.9%    |
| 2011 | 122       | 6.47%   |
| 2013 | 120       | 6.37%   |
| 2014 | 119       | 6.31%   |
| 2016 | 93        | 4.93%   |
| 2015 | 70        | 3.71%   |
| 2022 | 61        | 3.24%   |
| 2008 | 54        | 2.86%   |
| 2010 | 48        | 2.55%   |
| 2009 | 25        | 1.33%   |
| 2007 | 15        | 0.8%    |
| 2023 | 2         | 0.11%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1885      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1681      | 88.38%  |
| Enabled  | 221       | 11.62%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1864      | 98.89%  |
| Yes  | 21        | 1.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 553       | 29.18%  |
| 16.01-24.0  | 439       | 23.17%  |
| 8.01-16.0   | 351       | 18.52%  |
| 3.01-4.0    | 270       | 14.25%  |
| 32.01-64.0  | 173       | 9.13%   |
| 1.01-2.0    | 39        | 2.06%   |
| 64.01-256.0 | 30        | 1.58%   |
| 24.01-32.0  | 26        | 1.37%   |
| 2.01-3.0    | 14        | 0.74%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 554       | 27.3%   |
| 1.01-2.0   | 491       | 24.2%   |
| 4.01-8.0   | 444       | 21.88%  |
| 3.01-4.0   | 337       | 16.61%  |
| 8.01-16.0  | 142       | 7%      |
| 0.51-1.0   | 42        | 2.07%   |
| 16.01-24.0 | 14        | 0.69%   |
| 24.01-32.0 | 3         | 0.15%   |
| 32.01-64.0 | 2         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1322      | 69.18%  |
| 2      | 504       | 26.37%  |
| 3      | 59        | 3.09%   |
| 4      | 16        | 0.84%   |
| 0      | 8         | 0.42%   |
| 6      | 1         | 0.05%   |
| 5      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1377      | 72.78%  |
| Yes       | 515       | 27.22%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1484      | 78.56%  |
| No        | 405       | 21.44%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1854      | 98.36%  |
| No        | 31        | 1.64%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1582      | 83.31%  |
| No        | 317       | 16.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 305       | 16.15%  |
| Germany      | 196       | 10.38%  |
| Russia       | 138       | 7.31%   |
| Brazil       | 119       | 6.3%    |
| Italy        | 111       | 5.88%   |
| France       | 110       | 5.83%   |
| UK           | 71        | 3.76%   |
| Spain        | 64        | 3.39%   |
| Poland       | 49        | 2.6%    |
| India        | 47        | 2.49%   |
| Canada       | 46        | 2.44%   |
| Netherlands  | 40        | 2.12%   |
| Ukraine      | 36        | 1.91%   |
| Mexico       | 32        | 1.69%   |
| Australia    | 27        | 1.43%   |
| Hungary      | 24        | 1.27%   |
| Switzerland  | 23        | 1.22%   |
| Indonesia    | 23        | 1.22%   |
| Czechia      | 22        | 1.17%   |
| Belgium      | 22        | 1.17%   |
| Turkey       | 16        | 0.85%   |
| Bulgaria     | 15        | 0.79%   |
| South Africa | 14        | 0.74%   |
| Romania      | 14        | 0.74%   |
| Slovenia     | 13        | 0.69%   |
| Slovakia     | 12        | 0.64%   |
| Denmark      | 12        | 0.64%   |
| Belarus      | 12        | 0.64%   |
| Sweden       | 11        | 0.58%   |
| Portugal     | 11        | 0.58%   |
| Ireland      | 11        | 0.58%   |
| Greece       | 11        | 0.58%   |
| China        | 11        | 0.58%   |
| Austria      | 11        | 0.58%   |
| Argentina    | 11        | 0.58%   |
| New Zealand  | 9         | 0.48%   |
| Iran         | 9         | 0.48%   |
| Croatia      | 9         | 0.48%   |
| Colombia     | 9         | 0.48%   |
| Finland      | 8         | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Moscow            | 43        | 2.18%   |
| Berlin            | 23        | 1.16%   |
| Milan             | 20        | 1.01%   |
| St Petersburg     | 17        | 0.86%   |
| Paris             | 16        | 0.81%   |
| Madrid            | 16        | 0.81%   |
| Warsaw            | 13        | 0.66%   |
| Sofia             | 12        | 0.61%   |
| Sao Paulo         | 12        | 0.61%   |
| Rome              | 12        | 0.61%   |
| Hamburg           | 12        | 0.61%   |
| Budapest          | 12        | 0.61%   |
| Zurich            | 11        | 0.56%   |
| Minsk             | 11        | 0.56%   |
| Cologne           | 11        | 0.56%   |
| Jakarta           | 10        | 0.51%   |
| Kyiv              | 9         | 0.46%   |
| Amsterdam         | 9         | 0.46%   |
| Rio de Janeiro    | 8         | 0.4%    |
| Prague            | 8         | 0.4%    |
| Frankfurt am Main | 8         | 0.4%    |
| Vienna            | 7         | 0.35%   |
| Sydney            | 7         | 0.35%   |
| Phoenix           | 7         | 0.35%   |
| Los Angeles       | 7         | 0.35%   |
| Dublin            | 7         | 0.35%   |
| Wroclaw           | 6         | 0.3%    |
| Singapore         | 6         | 0.3%    |
| Seattle           | 6         | 0.3%    |
| Munich            | 6         | 0.3%    |
| Montreal          | 6         | 0.3%    |
| Marseille         | 6         | 0.3%    |
| Dallas            | 6         | 0.3%    |
| Chennai           | 6         | 0.3%    |
| Cape Town         | 6         | 0.3%    |
| Bucharest         | 6         | 0.3%    |
| Bratislava        | 6         | 0.3%    |
| Birmingham        | 6         | 0.3%    |
| Bengaluru         | 6         | 0.3%    |
| Athens            | 6         | 0.3%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                         | Notebooks | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 471       | 615    | 19.34%  |
| WDC                            | 277       | 334    | 11.38%  |
| Seagate                        | 226       | 274    | 9.28%   |
| Toshiba                        | 173       | 213    | 7.1%    |
| Kingston                       | 148       | 166    | 6.08%   |
| SanDisk                        | 141       | 172    | 5.79%   |
| Unknown                        | 119       | 146    | 4.89%   |
| SK hynix                       | 112       | 135    | 4.6%    |
| Intel                          | 93        | 121    | 3.82%   |
| Crucial                        | 89        | 107    | 3.66%   |
| HGST                           | 66        | 75     | 2.71%   |
| Micron Technology              | 59        | 64     | 2.42%   |
| Hitachi                        | 40        | 43     | 1.64%   |
| KIOXIA                         | 38        | 41     | 1.56%   |
| A-DATA Technology              | 35        | 36     | 1.44%   |
| Apple                          | 21        | 25     | 0.86%   |
| LITEON                         | 19        | 20     | 0.78%   |
| China                          | 18        | 24     | 0.74%   |
| SPCC                           | 14        | 15     | 0.57%   |
| Silicon Motion                 | 13        | 16     | 0.53%   |
| PNY                            | 12        | 12     | 0.49%   |
| Unknown                        | 12        | 12     | 0.49%   |
| Phison                         | 11        | 11     | 0.45%   |
| Transcend                      | 10        | 10     | 0.41%   |
| LITEONIT                       | 9         | 11     | 0.37%   |
| Intenso                        | 9         | 10     | 0.37%   |
| Micron/Crucial Technology      | 7         | 9      | 0.29%   |
| JMicron Technology             | 7         | 8      | 0.29%   |
| Apacer                         | 7         | 7      | 0.29%   |
| SSSTC                          | 6         | 6      | 0.25%   |
| Phison Electronics             | 6         | 6      | 0.25%   |
| KingSpec                       | 6         | 6      | 0.25%   |
| GOODRAM                        | 6         | 6      | 0.25%   |
| Union Memory                   | 5         | 5      | 0.21%   |
| Solid State Storage Technology | 5         | 9      | 0.21%   |
| SABRENT                        | 5         | 8      | 0.21%   |
| Patriot                        | 5         | 5      | 0.21%   |
| Fujitsu                        | 5         | 7      | 0.21%   |
| Corsair                        | 5         | 5      | 0.21%   |
| XPG                            | 4         | 4      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 34        | 1.34%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 25        | 0.98%   |
| Samsung SSD 860 EVO 500GB           | 25        | 0.98%   |
| Toshiba MQ01ABD100 1TB              | 23        | 0.91%   |
| HGST HTS721010A9E630 1TB            | 23        | 0.91%   |
| Toshiba MQ04ABF100 1TB              | 22        | 0.87%   |
| Unknown MMC Card  32GB              | 21        | 0.83%   |
| Samsung NVMe SSD Drive 512GB        | 21        | 0.83%   |
| Unknown MMC Card  64GB              | 18        | 0.71%   |
| Kingston SA400S37240G 240GB SSD     | 18        | 0.71%   |
| Seagate ST500LT012-1DG142 500GB     | 15        | 0.59%   |
| Samsung SSD 850 EVO 500GB           | 15        | 0.59%   |
| Samsung NVMe SSD Drive 1TB          | 14        | 0.55%   |
| Kingston SA400S37480G 480GB SSD     | 14        | 0.55%   |
| SanDisk NVMe SSD Drive 512GB        | 13        | 0.51%   |
| SanDisk NVMe SSD Drive 256GB        | 13        | 0.51%   |
| Samsung SSD 860 EVO M.2 500GB       | 13        | 0.51%   |
| Samsung SSD 850 EVO 250GB           | 13        | 0.51%   |
| SK hynix NVMe SSD Drive 512GB       | 12        | 0.47%   |
| Seagate ST2000LM007-1R8174 2TB      | 12        | 0.47%   |
| Samsung SSD 970 EVO Plus 500GB      | 12        | 0.47%   |
| Intel SSDPEKNW512G8 512GB           | 12        | 0.47%   |
| Unknown                             | 12        | 0.47%   |
| WDC WD10SPZX-21Z10T0 1TB            | 11        | 0.43%   |
| Unknown MMC Card  128GB             | 11        | 0.43%   |
| Toshiba MQ01ABF050 500GB            | 11        | 0.43%   |
| SanDisk SSD PLUS 240GB              | 11        | 0.43%   |
| Samsung SSD 860 EVO 1TB             | 11        | 0.43%   |
| Crucial CT500MX500SSD1 500GB        | 11        | 0.43%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 10        | 0.39%   |
| KIOXIA KBG40ZNS512G NVMe 512GB      | 10        | 0.39%   |
| Kingston SV300S37A120G 120GB SSD    | 10        | 0.39%   |
| HGST HTS541010A9E680 1TB            | 10        | 0.39%   |
| Crucial CT1000MX500SSD1 1TB         | 10        | 0.39%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 9         | 0.35%   |
| WDC WD10SPZX-24Z10 1TB              | 9         | 0.35%   |
| Seagate ST1000LM048-2E7172 1TB      | 9         | 0.35%   |
| Samsung SSD 970 EVO Plus 1TB        | 9         | 0.35%   |
| WDC WD10SPZX-60Z10T0 1TB            | 8         | 0.32%   |
| Seagate ST1000LX015-1U7172 1TB      | 8         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 223       | 270    | 36.14%  |
| WDC                 | 151       | 178    | 24.47%  |
| Toshiba             | 99        | 122    | 16.05%  |
| HGST                | 65        | 74     | 10.53%  |
| Hitachi             | 40        | 43     | 6.48%   |
| Samsung Electronics | 11        | 14     | 1.78%   |
| Unknown             | 5         | 7      | 0.81%   |
| SABRENT             | 5         | 8      | 0.81%   |
| JMicron Technology  | 5         | 5      | 0.81%   |
| Fujitsu             | 5         | 7      | 0.81%   |
| Apple               | 4         | 4      | 0.65%   |
| USB3.0              | 1         | 1      | 0.16%   |
| KESU                | 1         | 1      | 0.16%   |
| ipTIME              | 1         | 1      | 0.16%   |
| HGST HTS            | 1         | 1      | 0.16%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 225       | 296    | 27.99%  |
| Kingston            | 99        | 112    | 12.31%  |
| SanDisk             | 88        | 106    | 10.95%  |
| Crucial             | 75        | 93     | 9.33%   |
| WDC                 | 39        | 54     | 4.85%   |
| A-DATA Technology   | 21        | 21     | 2.61%   |
| Toshiba             | 20        | 29     | 2.49%   |
| Intel               | 19        | 21     | 2.36%   |
| SK hynix            | 17        | 17     | 2.11%   |
| China               | 17        | 23     | 2.11%   |
| Micron Technology   | 15        | 16     | 1.87%   |
| LITEON              | 14        | 14     | 1.74%   |
| SPCC                | 12        | 13     | 1.49%   |
| PNY                 | 10        | 10     | 1.24%   |
| Transcend           | 9         | 9      | 1.12%   |
| LITEONIT            | 9         | 11     | 1.12%   |
| Apple               | 9         | 9      | 1.12%   |
| Intenso             | 7         | 8      | 0.87%   |
| Apacer              | 7         | 7      | 0.87%   |
| KingSpec            | 6         | 6      | 0.75%   |
| GOODRAM             | 6         | 6      | 0.75%   |
| Patriot             | 5         | 5      | 0.62%   |
| Emtec               | 4         | 4      | 0.5%    |
| Dogfish             | 4         | 4      | 0.5%    |
| Zheino              | 3         | 5      | 0.37%   |
| TO Exter            | 3         | 3      | 0.37%   |
| Team                | 3         | 3      | 0.37%   |
| Netac               | 3         | 3      | 0.37%   |
| Corsair             | 3         | 3      | 0.37%   |
| ASMT                | 3         | 4      | 0.37%   |
| Verbatim            | 2         | 3      | 0.25%   |
| Smart               | 2         | 2      | 0.25%   |
| RZX                 | 2         | 3      | 0.25%   |
| Plextor             | 2         | 2      | 0.25%   |
| Mushkin             | 2         | 2      | 0.25%   |
| Lexar               | 2         | 2      | 0.25%   |
| FORESEE             | 2         | 2      | 0.25%   |
| Drevo               | 2         | 2      | 0.25%   |
| BHT                 | 2         | 3      | 0.25%   |
| Unknown             | 2         | 2      | 0.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 833       | 1049   | 35.95%  |
| SSD     | 734       | 972    | 31.68%  |
| HDD     | 600       | 736    | 25.9%   |
| MMC     | 123       | 147    | 5.31%   |
| Unknown | 27        | 31     | 1.17%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1151      | 1642   | 52.73%  |
| NVMe | 832       | 1045   | 38.11%  |
| MMC  | 123       | 147    | 5.63%   |
| SAS  | 77        | 101    | 3.53%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 805       | 1057   | 61.17%  |
| 0.51-1.0   | 438       | 553    | 33.28%  |
| 1.01-2.0   | 66        | 87     | 5.02%   |
| 4.01-10.0  | 6         | 10     | 0.46%   |
| 3.01-4.0   | 1         | 1      | 0.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 562       | 28.97%  |
| 101-250        | 554       | 28.56%  |
| 501-1000       | 360       | 18.56%  |
| 1001-2000      | 153       | 7.89%   |
| 51-100         | 117       | 6.03%   |
| 1-20           | 57        | 2.94%   |
| 21-50          | 54        | 2.78%   |
| More than 3000 | 38        | 1.96%   |
| 2001-3000      | 37        | 1.91%   |
| Unknown        | 8         | 0.41%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 520       | 25.88%  |
| 101-250        | 394       | 19.61%  |
| 21-50          | 349       | 17.37%  |
| 51-100         | 284       | 14.14%  |
| 251-500        | 249       | 12.39%  |
| 501-1000       | 130       | 6.47%   |
| 1001-2000      | 51        | 2.54%   |
| More than 3000 | 15        | 0.75%   |
| 2001-3000      | 9         | 0.45%   |
| Unknown        | 8         | 0.4%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB       | 5         | 11     | 3.57%   |
| HGST HTS721010A9E630 1TB                 | 5         | 6      | 3.57%   |
| Toshiba MQ04ABF100 1TB                   | 3         | 3      | 2.14%   |
| Toshiba MQ01ABD100 1TB                   | 3         | 5      | 2.14%   |
| Seagate ST500LT012-9WS142 500GB          | 3         | 3      | 2.14%   |
| Seagate ST1000LM048-2E7172 1TB           | 3         | 3      | 2.14%   |
| Seagate ST1000LM035-1RK172 1TB           | 3         | 3      | 2.14%   |
| Kingston SV300S37A120G 120GB SSD         | 3         | 3      | 2.14%   |
| Hitachi HTS547564A9E384 640GB            | 3         | 3      | 2.14%   |
| HGST HTS545050A7E680 500GB               | 3         | 3      | 2.14%   |
| SK hynix SC401 SATA 512GB SSD            | 2         | 2      | 1.43%   |
| SK hynix BC711 HFM512GD3JX013N 512GB     | 2         | 2      | 1.43%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 2      | 1.43%   |
| Seagate ST500LM012 HN-M500MBB 500GB      | 2         | 2      | 1.43%   |
| Seagate ST2000LM007-1R8174 2TB           | 2         | 2      | 1.43%   |
| SanDisk SSD PLUS 240GB                   | 2         | 2      | 1.43%   |
| Hitachi HTS547575A9E384 752GB            | 2         | 2      | 1.43%   |
| Hitachi HTS545050B9A300 500GB            | 2         | 2      | 1.43%   |
| HGST HTS541010A9E680 1TB                 | 2         | 2      | 1.43%   |
| Crucial CT500P1SSD8 500GB                | 2         | 2      | 1.43%   |
| Zheino CHN mSATA02M 256 256GB SSD        | 1         | 2      | 0.71%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD         | 1         | 1      | 0.71%   |
| WDC WD6400BEVT-22A0RT0 640GB             | 1         | 1      | 0.71%   |
| WDC WD6400BEVT-00A0RT0 640GB             | 1         | 1      | 0.71%   |
| WDC WD5000LPVX-75V0TT0 500GB             | 1         | 1      | 0.71%   |
| WDC WD5000LPVX-55V0TT0 500GB             | 1         | 1      | 0.71%   |
| WDC WD5000LPVT-24G33T1 500GB             | 1         | 1      | 0.71%   |
| WDC WD5000LPVT-22G33T0 500GB             | 1         | 1      | 0.71%   |
| WDC WD5000LPLX-00ZNTT0 500GB             | 1         | 1      | 0.71%   |
| WDC WD1600BJKT-75F4T0 160GB              | 1         | 1      | 0.71%   |
| WDC WD10JPVX-60JC3T1 1TB                 | 1         | 1      | 0.71%   |
| WDC PC SN520 SDAPMUW-512G-1001 512GB     | 1         | 1      | 0.71%   |
| VISIPRO SSD 256GB                        | 1         | 1      | 0.71%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.71%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 0.71%   |
| Toshiba MQ01ACF050 500GB                 | 1         | 1      | 0.71%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 2      | 0.71%   |
| Toshiba MK7575GSX 752GB                  | 1         | 1      | 0.71%   |
| Toshiba MK7559GSXP 752GB                 | 1         | 2      | 0.71%   |
| Toshiba MK6476GSX 640GB                  | 1         | 1      | 0.71%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 40     | 22.86%  |
| Toshiba             | 20        | 24     | 14.29%  |
| Hitachi             | 12        | 12     | 8.57%   |
| HGST                | 12        | 13     | 8.57%   |
| WDC                 | 11        | 11     | 7.86%   |
| Samsung Electronics | 10        | 11     | 7.14%   |
| SK hynix            | 8         | 8      | 5.71%   |
| Crucial             | 8         | 9      | 5.71%   |
| SanDisk             | 6         | 6      | 4.29%   |
| Kingston            | 6         | 6      | 4.29%   |
| A-DATA Technology   | 4         | 4      | 2.86%   |
| Micron Technology   | 3         | 3      | 2.14%   |
| Zheino              | 1         | 2      | 0.71%   |
| VISIPRO             | 1         | 1      | 0.71%   |
| R580                | 1         | 1      | 0.71%   |
| Mushkin             | 1         | 1      | 0.71%   |
| LITEONIT            | 1         | 1      | 0.71%   |
| Drevo               | 1         | 1      | 0.71%   |
| BAITITON            | 1         | 3      | 0.71%   |
| ASENNO              | 1         | 1      | 0.71%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 32        | 40     | 38.1%   |
| Toshiba             | 17        | 21     | 20.24%  |
| Hitachi             | 12        | 12     | 14.29%  |
| HGST                | 12        | 13     | 14.29%  |
| WDC                 | 9         | 9      | 10.71%  |
| Samsung Electronics | 2         | 2      | 2.38%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 83        | 97     | 60.14%  |
| SSD  | 42        | 48     | 30.43%  |
| NVMe | 13        | 13     | 9.42%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB | 1         | 1      | 50%     |
| Intel SSDSC2KB960G8 960GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| Intel   | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1008      | 1381   | 49.15%  |
| Detected | 904       | 1394   | 44.08%  |
| Malfunc  | 137       | 158    | 6.68%   |
| Failed   | 2         | 2      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1289      | 54.66%  |
| Samsung Electronics              | 255       | 10.81%  |
| AMD                              | 241       | 10.22%  |
| SanDisk                          | 145       | 6.15%   |
| SK hynix                         | 95        | 4.03%   |
| Toshiba America Info Systems     | 61        | 2.59%   |
| Kingston Technology Company      | 51        | 2.16%   |
| Micron Technology                | 44        | 1.87%   |
| KIOXIA                           | 35        | 1.48%   |
| Phison Electronics               | 21        | 0.89%   |
| Micron/Crucial Technology        | 21        | 0.89%   |
| ADATA Technology                 | 19        | 0.81%   |
| Silicon Motion                   | 18        | 0.76%   |
| Solid State Storage Technology   | 12        | 0.51%   |
| Union Memory (Shenzhen)          | 11        | 0.47%   |
| Realtek Semiconductor            | 9         | 0.38%   |
| Lite-On Technology               | 8         | 0.34%   |
| Apple                            | 6         | 0.25%   |
| Nvidia                           | 4         | 0.17%   |
| Lenovo                           | 4         | 0.17%   |
| Marvell Technology Group         | 3         | 0.13%   |
| Zhaoxin                          | 1         | 0.04%   |
| VIA Technologies                 | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| Shenzhen Longsys Electronics     | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |
| ASMedia Technology               | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 225       | 9.03%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 154       | 6.18%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 138       | 5.54%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 138       | 5.54%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 131       | 5.26%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 91        | 3.65%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 84        | 3.37%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 73        | 2.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 72        | 2.89%   |
| Intel Volume Management Device NVMe RAID Controller                            | 70        | 2.81%   |
| Samsung NVMe SSD Controller 980                                                | 58        | 2.33%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 48        | 1.93%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 48        | 1.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 45        | 1.81%   |
| Micron Non-Volatile memory controller                                          | 44        | 1.77%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 44        | 1.77%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 43        | 1.73%   |
| Intel SSD 660P Series                                                          | 42        | 1.69%   |
| Intel Comet Lake SATA AHCI Controller                                          | 34        | 1.36%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 33        | 1.32%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 32        | 1.28%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 30        | 1.2%    |
| Intel Tiger Lake-LP SATA Controller                                            | 28        | 1.12%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 27        | 1.08%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 27        | 1.08%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 26        | 1.04%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 25        | 1%      |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 23        | 0.92%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 22        | 0.88%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 21        | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 21        | 0.84%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 20        | 0.8%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 20        | 0.8%    |
| SanDisk Non-Volatile memory controller                                         | 18        | 0.72%   |
| Kingston Company Company Non-Volatile memory controller                        | 18        | 0.72%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 18        | 0.72%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 18        | 0.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 18        | 0.72%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                           | 15        | 0.6%    |
| SK hynix Non-Volatile memory controller                                        | 15        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1306      | 54.37%  |
| NVMe | 831       | 34.6%   |
| RAID | 206       | 8.58%   |
| IDE  | 59        | 2.46%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1518      | 80.53%  |
| AMD          | 366       | 19.42%  |
| CentaurHauls | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 44        | 2.33%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 37        | 1.96%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 37        | 1.96%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 36        | 1.91%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 34        | 1.8%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 33        | 1.75%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 32        | 1.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 31        | 1.64%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 31        | 1.64%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 31        | 1.64%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 29        | 1.54%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 29        | 1.54%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 29        | 1.54%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 26        | 1.38%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 26        | 1.38%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 25        | 1.33%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 23        | 1.22%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 23        | 1.22%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 20        | 1.06%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 19        | 1.01%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 17        | 0.9%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 17        | 0.9%    |
| Intel Core i5-4200U CPU @ 1.60GHz             | 16        | 0.85%   |
| Intel 12th Gen Core i7-12700H                 | 16        | 0.85%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 16        | 0.85%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 14        | 0.74%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 13        | 0.69%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 13        | 0.69%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 13        | 0.69%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 13        | 0.69%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 13        | 0.69%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 13        | 0.69%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 13        | 0.69%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 12        | 0.64%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 12        | 0.64%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 12        | 0.64%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 12        | 0.64%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 12        | 0.64%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 12        | 0.64%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 12        | 0.64%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 535       | 28.38%  |
| Intel Core i5           | 476       | 25.25%  |
| Other                   | 171       | 9.07%   |
| Intel Core i3           | 106       | 5.62%   |
| AMD Ryzen 7             | 105       | 5.57%   |
| AMD Ryzen 5             | 100       | 5.31%   |
| Intel Celeron           | 84        | 4.46%   |
| Intel Core 2 Duo        | 45        | 2.39%   |
| Intel Pentium           | 28        | 1.49%   |
| AMD A6                  | 22        | 1.17%   |
| AMD Ryzen 3             | 20        | 1.06%   |
| AMD Ryzen 7 PRO         | 16        | 0.85%   |
| AMD Ryzen 9             | 15        | 0.8%    |
| Intel Core i9           | 14        | 0.74%   |
| AMD A10                 | 14        | 0.74%   |
| Intel Pentium Dual-Core | 13        | 0.69%   |
| Intel Atom              | 13        | 0.69%   |
| Intel Pentium Silver    | 11        | 0.58%   |
| AMD A8                  | 10        | 0.53%   |
| AMD Ryzen 5 PRO         | 9         | 0.48%   |
| Intel Genuine           | 7         | 0.37%   |
| AMD E1                  | 7         | 0.37%   |
| AMD E                   | 7         | 0.37%   |
| AMD E2                  | 6         | 0.32%   |
| AMD A4                  | 6         | 0.32%   |
| Intel Pentium Dual      | 5         | 0.27%   |
| Intel Core m3           | 5         | 0.27%   |
| Intel Celeron Dual-Core | 5         | 0.27%   |
| AMD FX                  | 5         | 0.27%   |
| Intel Core 2            | 3         | 0.16%   |
| AMD Athlon              | 3         | 0.16%   |
| AMD A12                 | 3         | 0.16%   |
| Intel Xeon              | 2         | 0.11%   |
| AMD C-50                | 2         | 0.11%   |
| AMD Athlon II           | 2         | 0.11%   |
| Intel Pentium Gold      | 1         | 0.05%   |
| Intel Core 2 Quad       | 1         | 0.05%   |
| AMD Z                   | 1         | 0.05%   |
| AMD Turion II           | 1         | 0.05%   |
| AMD Sempron             | 1         | 0.05%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 780       | 41.36%  |
| 4      | 720       | 38.18%  |
| 6      | 197       | 10.45%  |
| 8      | 140       | 7.42%   |
| 14     | 21        | 1.11%   |
| 1      | 13        | 0.69%   |
| 12     | 7         | 0.37%   |
| 10     | 6         | 0.32%   |
| 16     | 1         | 0.05%   |
| 5      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1885      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1551      | 82.15%  |
| 1      | 337       | 17.85%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1885      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 448       | 23.2%   |
| 0x306a9    | 108       | 5.59%   |
| 0x206a7    | 94        | 4.87%   |
| 0x906ea    | 85        | 4.4%    |
| 0x806ec    | 85        | 4.4%    |
| 0x806c1    | 74        | 3.83%   |
| 0x806ea    | 72        | 3.73%   |
| 0x40651    | 71        | 3.68%   |
| 0x306c3    | 59        | 3.06%   |
| 0x806e9    | 58        | 3%      |
| 0x406e3    | 49        | 2.54%   |
| 0x306d4    | 42        | 2.18%   |
| 0x906e9    | 36        | 1.86%   |
| 0x08108109 | 36        | 1.86%   |
| 0xa0652    | 34        | 1.76%   |
| 0x08600106 | 34        | 1.76%   |
| 0x1067a    | 33        | 1.71%   |
| 0x08108102 | 33        | 1.71%   |
| 0x0a50000c | 30        | 1.55%   |
| 0x706e5    | 29        | 1.5%    |
| 0x806eb    | 26        | 1.35%   |
| 0x906a3    | 23        | 1.19%   |
| 0x506e3    | 23        | 1.19%   |
| 0x706a8    | 18        | 0.93%   |
| 0x706a1    | 18        | 0.93%   |
| 0x20655    | 18        | 0.93%   |
| 0x08608103 | 18        | 0.93%   |
| 0x806d1    | 17        | 0.88%   |
| 0x406c4    | 17        | 0.88%   |
| 0x30678    | 14        | 0.73%   |
| 0x08600104 | 14        | 0.73%   |
| 0x906ed    | 13        | 0.67%   |
| 0x07030105 | 13        | 0.67%   |
| 0x6fd      | 12        | 0.62%   |
| 0x08600103 | 12        | 0.62%   |
| 0x03000027 | 12        | 0.62%   |
| 0x20652    | 11        | 0.57%   |
| 0x06006705 | 9         | 0.47%   |
| 0x506c9    | 8         | 0.41%   |
| 0x10676    | 8         | 0.41%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 468       | 24.81%  |
| Haswell          | 165       | 8.75%   |
| IvyBridge        | 144       | 7.64%   |
| SandyBridge      | 115       | 6.1%    |
| TigerLake        | 107       | 5.67%   |
| Skylake          | 89        | 4.72%   |
| Zen+             | 80        | 4.24%   |
| Zen 2            | 80        | 4.24%   |
| Zen 3            | 55        | 2.92%   |
| Penryn           | 55        | 2.92%   |
| Unknown          | 54        | 2.86%   |
| IceLake          | 53        | 2.81%   |
| CometLake        | 51        | 2.7%    |
| Broadwell        | 50        | 2.65%   |
| Goldmont plus    | 49        | 2.6%    |
| Silvermont       | 43        | 2.28%   |
| Westmere         | 40        | 2.12%   |
| Excavator        | 29        | 1.54%   |
| Core             | 28        | 1.48%   |
| Alderlake Hybrid | 28        | 1.48%   |
| Zen              | 18        | 0.95%   |
| Puma             | 17        | 0.9%    |
| K10 Llano        | 13        | 0.69%   |
| Bobcat           | 12        | 0.64%   |
| Goldmont         | 10        | 0.53%   |
| Piledriver       | 8         | 0.42%   |
| Jaguar           | 7         | 0.37%   |
| Steamroller      | 4         | 0.21%   |
| Nehalem          | 4         | 0.21%   |
| K10              | 4         | 0.21%   |
| Bonnell          | 3         | 0.16%   |
| K8 & K10 hybrid  | 2         | 0.11%   |
| Tremont          | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1424      | 56.55%  |
| Nvidia                           | 614       | 24.38%  |
| AMD                              | 477       | 18.94%  |
| Zhaoxin                          | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| ATI Technologies                 | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 131       | 5.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 113       | 4.38%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 107       | 4.15%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 98        | 3.8%    |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 83        | 3.22%   |
| Intel UHD Graphics 620                                                                   | 82        | 3.18%   |
| AMD Renoir                                                                               | 79        | 3.06%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 78        | 3.02%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 78        | 3.02%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 74        | 2.87%   |
| Intel HD Graphics 620                                                                    | 69        | 2.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 58        | 2.25%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 56        | 2.17%   |
| Intel HD Graphics 5500                                                                   | 48        | 1.86%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 47        | 1.82%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 45        | 1.74%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 42        | 1.63%   |
| Intel HD Graphics 630                                                                    | 41        | 1.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 39        | 1.51%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 36        | 1.4%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 35        | 1.36%   |
| AMD Lucienne                                                                             | 27        | 1.05%   |
| Intel HD Graphics 530                                                                    | 26        | 1.01%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 26        | 1.01%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 23        | 0.89%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 23        | 0.89%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 23        | 0.89%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 20        | 0.78%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 20        | 0.78%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 20        | 0.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 20        | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 20        | 0.78%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                               | 19        | 0.74%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 19        | 0.74%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 19        | 0.74%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 18        | 0.7%    |
| Intel Iris Plus Graphics G7                                                              | 17        | 0.66%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 16        | 0.62%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 15        | 0.58%   |
| Nvidia GP108M [GeForce MX150]                                                            | 15        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 847       | 44.84%  |
| Intel + Nvidia | 487       | 25.78%  |
| 1 x AMD        | 291       | 15.4%   |
| Intel + AMD    | 88        | 4.66%   |
| 1 x Nvidia     | 70        | 3.71%   |
| AMD + Nvidia   | 55        | 2.91%   |
| 2 x AMD        | 44        | 2.33%   |
| Other          | 2         | 0.11%   |
| 2 x Nvidia     | 2         | 0.11%   |
| 2 x Intel      | 1         | 0.05%   |
| 1 x Zhaoxin    | 1         | 0.05%   |
| 1 x SiS        | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1476      | 77.4%   |
| Proprietary | 400       | 20.98%  |
| Unknown     | 31        | 1.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1215      | 63.02%  |
| 1.01-2.0   | 226       | 11.72%  |
| 0.01-0.5   | 193       | 10.01%  |
| 3.01-4.0   | 120       | 6.22%   |
| 0.51-1.0   | 99        | 5.13%   |
| 5.01-6.0   | 37        | 1.92%   |
| 7.01-8.0   | 24        | 1.24%   |
| 2.01-3.0   | 12        | 0.62%   |
| 8.01-16.0  | 2         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 409       | 18.04%  |
| LG Display              | 324       | 14.29%  |
| BOE                     | 315       | 13.9%   |
| Chimei Innolux          | 308       | 13.59%  |
| Samsung Electronics     | 214       | 9.44%   |
| Sharp                   | 91        | 4.01%   |
| Dell                    | 81        | 3.57%   |
| Goldstar                | 62        | 2.73%   |
| Lenovo                  | 43        | 1.9%    |
| PANDA                   | 40        | 1.76%   |
| Chi Mei Optoelectronics | 38        | 1.68%   |
| Hewlett-Packard         | 31        | 1.37%   |
| Acer                    | 30        | 1.32%   |
| Apple                   | 29        | 1.28%   |
| Philips                 | 24        | 1.06%   |
| InfoVision              | 20        | 0.88%   |
| BenQ                    | 20        | 0.88%   |
| Ancor Communications    | 19        | 0.84%   |
| AOC                     | 17        | 0.75%   |
| ASUSTek Computer        | 11        | 0.49%   |
| ViewSonic               | 10        | 0.44%   |
| CSO                     | 10        | 0.44%   |
| Iiyama                  | 9         | 0.4%    |
| Toshiba                 | 6         | 0.26%   |
| Panasonic               | 6         | 0.26%   |
| LG Philips              | 6         | 0.26%   |
| CPT                     | 5         | 0.22%   |
| Sony                    | 4         | 0.18%   |
| Seiko/Epson             | 4         | 0.18%   |
| Sceptre Tech            | 4         | 0.18%   |
| NEC Computers           | 4         | 0.18%   |
| MSI                     | 4         | 0.18%   |
| HannStar                | 4         | 0.18%   |
| Vizio                   | 3         | 0.13%   |
| Vestel Elektronik       | 3         | 0.13%   |
| Unknown                 | 3         | 0.13%   |
| SLD                     | 3         | 0.13%   |
| LGD                     | 3         | 0.13%   |
| HKC                     | 3         | 0.13%   |
| Medion                  | 2         | 0.09%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch            | 20        | 0.87%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 293x165mm 13.2-inch      | 18        | 0.78%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 18        | 0.78%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch            | 18        | 0.78%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch               | 14        | 0.61%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch          | 14        | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 14        | 0.61%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 11        | 0.48%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                     | 11        | 0.48%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 10        | 0.43%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch          | 10        | 0.43%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch             | 10        | 0.43%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 9         | 0.39%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                   | 8         | 0.35%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch              | 8         | 0.35%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                  | 8         | 0.35%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch           | 8         | 0.35%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x193mm 15.5-inch            | 8         | 0.35%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch            | 8         | 0.35%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 8         | 0.35%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch     | 7         | 0.3%    |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch              | 7         | 0.3%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch          | 7         | 0.3%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 7         | 0.3%    |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                     | 7         | 0.3%    |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                   | 6         | 0.26%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                   | 6         | 0.26%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                   | 6         | 0.26%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch              | 6         | 0.26%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 6         | 0.26%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch               | 6         | 0.26%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch          | 6         | 0.26%   |
| Chimei Innolux LCD Monitor CMN150C 1920x1080 344x193mm 15.5-inch          | 6         | 0.26%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 6         | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 6         | 0.26%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch  | 6         | 0.26%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                     | 6         | 0.26%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                     | 6         | 0.26%   |
| BOE LCD Monitor BOE06CB 1920x1080 344x194mm 15.5-inch                     | 6         | 0.26%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                      | 6         | 0.26%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1030      | 49.07%  |
| 1366x768 (WXGA)    | 507       | 24.15%  |
| 1600x900 (HD+)     | 107       | 5.1%    |
| 3840x2160 (4K)     | 104       | 4.95%   |
| 2560x1440 (QHD)    | 79        | 3.76%   |
| 1920x1200 (WUXGA)  | 41        | 1.95%   |
| 1280x800 (WXGA)    | 35        | 1.67%   |
| 1440x900 (WXGA+)   | 20        | 0.95%   |
| 2880x1800          | 19        | 0.91%   |
| 2560x1600          | 19        | 0.91%   |
| 3840x2400          | 14        | 0.67%   |
| 1680x1050 (WSXGA+) | 14        | 0.67%   |
| 2560x1080          | 13        | 0.62%   |
| 1280x1024 (SXGA)   | 13        | 0.62%   |
| 3440x1440          | 12        | 0.57%   |
| 2160x1440          | 11        | 0.52%   |
| 1360x768           | 8         | 0.38%   |
| 3200x1800 (QHD+)   | 7         | 0.33%   |
| 2256x1504          | 5         | 0.24%   |
| 3840x1080          | 4         | 0.19%   |
| 2520x1680          | 4         | 0.19%   |
| Unknown            | 4         | 0.19%   |
| 3456x2160          | 3         | 0.14%   |
| 2240x1400          | 3         | 0.14%   |
| 1600x1200          | 3         | 0.14%   |
| 1024x768 (XGA)     | 3         | 0.14%   |
| 3072x1920          | 2         | 0.1%    |
| 1920x540           | 2         | 0.1%    |
| 1920x1280          | 2         | 0.1%    |
| 1024x600           | 2         | 0.1%    |
| 5760x2160          | 1         | 0.05%   |
| 3840x1100          | 1         | 0.05%   |
| 3000x2000          | 1         | 0.05%   |
| 3000x1920          | 1         | 0.05%   |
| 2560x1700          | 1         | 0.05%   |
| 2288x1287          | 1         | 0.05%   |
| 2160x1350          | 1         | 0.05%   |
| 1680x945           | 1         | 0.05%   |
| 1080x1920          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 939       | 41.26%  |
| 13      | 285       | 12.52%  |
| 14      | 268       | 11.78%  |
| 17      | 194       | 8.52%   |
| 27      | 100       | 4.39%   |
| 24      | 80        | 3.51%   |
| 23      | 74        | 3.25%   |
| 21      | 57        | 2.5%    |
| 11      | 39        | 1.71%   |
| 12      | 38        | 1.67%   |
| 16      | 30        | 1.32%   |
| 34      | 23        | 1.01%   |
| Unknown | 21        | 0.92%   |
| 31      | 20        | 0.88%   |
| 18      | 15        | 0.66%   |
| 20      | 13        | 0.57%   |
| 19      | 9         | 0.4%    |
| 84      | 7         | 0.31%   |
| 32      | 7         | 0.31%   |
| 22      | 7         | 0.31%   |
| 25      | 6         | 0.26%   |
| 54      | 5         | 0.22%   |
| 40      | 5         | 0.22%   |
| 72      | 3         | 0.13%   |
| 47      | 3         | 0.13%   |
| 42      | 3         | 0.13%   |
| 26      | 3         | 0.13%   |
| 10      | 3         | 0.13%   |
| 49      | 2         | 0.09%   |
| 46      | 2         | 0.09%   |
| 78      | 1         | 0.04%   |
| 74      | 1         | 0.04%   |
| 65      | 1         | 0.04%   |
| 61      | 1         | 0.04%   |
| 60      | 1         | 0.04%   |
| 58      | 1         | 0.04%   |
| 52      | 1         | 0.04%   |
| 48      | 1         | 0.04%   |
| 39      | 1         | 0.04%   |
| 36      | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 1354      | 60.34%  |
| 501-600     | 233       | 10.38%  |
| 351-400     | 227       | 10.12%  |
| 201-300     | 209       | 9.31%   |
| 401-500     | 97        | 4.32%   |
| 601-700     | 31        | 1.38%   |
| 701-800     | 30        | 1.34%   |
| Unknown     | 21        | 0.94%   |
| 1001-1500   | 18        | 0.8%    |
| 1501-2000   | 12        | 0.53%   |
| 801-900     | 7         | 0.31%   |
| 901-1000    | 3         | 0.13%   |
| 101-200     | 1         | 0.04%   |
| 1-100       | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1669      | 86.57%  |
| 16/10   | 170       | 8.82%   |
| 3/2     | 27        | 1.4%    |
| 21/9    | 25        | 1.3%    |
| Unknown | 14        | 0.73%   |
| 5/4     | 11        | 0.57%   |
| 4/3     | 7         | 0.36%   |
| 32/9    | 2         | 0.1%    |
| 3.40    | 1         | 0.05%   |
| 0.62    | 1         | 0.05%   |
| 0.56    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 941       | 41.6%   |
| 81-90          | 442       | 19.54%  |
| 201-250        | 169       | 7.47%   |
| 121-130        | 168       | 7.43%   |
| 71-80          | 113       | 5%      |
| 301-350        | 104       | 4.6%    |
| 351-500        | 48        | 2.12%   |
| 51-60          | 40        | 1.77%   |
| 151-200        | 39        | 1.72%   |
| 61-70          | 34        | 1.5%    |
| 251-300        | 30        | 1.33%   |
| More than 1000 | 23        | 1.02%   |
| 111-120        | 21        | 0.93%   |
| Unknown        | 21        | 0.93%   |
| 131-140        | 19        | 0.84%   |
| 141-150        | 18        | 0.8%    |
| 501-1000       | 18        | 0.8%    |
| 91-100         | 9         | 0.4%    |
| 41-50          | 3         | 0.13%   |
| 1-40           | 2         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 1004      | 45.29%  |
| 101-120       | 572       | 25.8%   |
| 51-100        | 336       | 15.16%  |
| 161-240       | 159       | 7.17%   |
| More than 240 | 96        | 4.33%   |
| 1-50          | 29        | 1.31%   |
| Unknown       | 21        | 0.95%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1470      | 76.28%  |
| 2     | 365       | 18.94%  |
| 3     | 52        | 2.7%    |
| 0     | 33        | 1.71%   |
| 4     | 7         | 0.36%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1074      | 35.93%  |
| Intel                             | 1067      | 35.7%   |
| Qualcomm Atheros                  | 391       | 13.08%  |
| Broadcom                          | 151       | 5.05%   |
| MediaTek                          | 56        | 1.87%   |
| Broadcom Limited                  | 25        | 0.84%   |
| Ralink                            | 23        | 0.77%   |
| Marvell Technology Group          | 19        | 0.64%   |
| TP-Link                           | 14        | 0.47%   |
| ASIX Electronics                  | 13        | 0.43%   |
| DisplayLink                       | 12        | 0.4%    |
| Sierra Wireless                   | 11        | 0.37%   |
| Samsung Electronics               | 11        | 0.37%   |
| Ralink Technology                 | 11        | 0.37%   |
| Qualcomm                          | 11        | 0.37%   |
| Ericsson Business Mobile Networks | 10        | 0.33%   |
| Lenovo                            | 9         | 0.3%    |
| Huawei Technologies               | 9         | 0.3%    |
| Dell                              | 9         | 0.3%    |
| Xiaomi                            | 7         | 0.23%   |
| JMicron Technology                | 6         | 0.2%    |
| D-Link                            | 5         | 0.17%   |
| Hewlett-Packard                   | 4         | 0.13%   |
| Apple                             | 4         | 0.13%   |
| T & A Mobile Phones               | 3         | 0.1%    |
| Qualcomm Atheros Communications   | 3         | 0.1%    |
| Nvidia                            | 3         | 0.1%    |
| NetGear                           | 3         | 0.1%    |
| Google                            | 3         | 0.1%    |
| ZyDAS                             | 2         | 0.07%   |
| Motorola PCS                      | 2         | 0.07%   |
| Fibocom                           | 2         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.03%   |
| Toshiba                           | 1         | 0.03%   |
| Texas Instruments                 | 1         | 0.03%   |
| Silicon Integrated Systems [SiS]  | 1         | 0.03%   |
| SEGGER                            | 1         | 0.03%   |
| NIIMBOT                           | 1         | 0.03%   |
| Linksys                           | 1         | 0.03%   |
| HMD Global                        | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 682       | 19.15%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 148       | 4.15%   |
| Intel Wi-Fi 6 AX200                                               | 127       | 3.57%   |
| Intel Wireless 8265 / 8275                                        | 92        | 2.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 91        | 2.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 79        | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 76        | 2.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 76        | 2.13%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 75        | 2.11%   |
| Intel Wireless 7260                                               | 74        | 2.08%   |
| Intel Wi-Fi 6 AX201                                               | 71        | 1.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 63        | 1.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 62        | 1.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 57        | 1.6%    |
| Intel Wireless 7265                                               | 55        | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 52        | 1.46%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 50        | 1.4%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 50        | 1.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 42        | 1.18%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 40        | 1.12%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 38        | 1.07%   |
| Intel Wireless 8260                                               | 36        | 1.01%   |
| Intel Wireless 3165                                               | 34        | 0.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 32        | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 31        | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                             | 31        | 0.87%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 31        | 0.87%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 28        | 0.79%   |
| Intel Ethernet Connection (7) I219-LM                             | 23        | 0.65%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 23        | 0.65%   |
| Intel Ethernet Connection I218-LM                                 | 22        | 0.62%   |
| Intel Wireless-AC 9260                                            | 21        | 0.59%   |
| Broadcom BCM43142 802.11b/g/n                                     | 21        | 0.59%   |
| Intel Wireless 3160                                               | 20        | 0.56%   |
| Intel Ethernet Connection I217-LM                                 | 20        | 0.56%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 19        | 0.53%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 19        | 0.53%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 19        | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 17        | 0.48%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 17        | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Notebooks | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1018      | 52.69%  |
| Qualcomm Atheros                      | 328       | 16.98%  |
| Realtek Semiconductor                 | 313       | 16.2%   |
| Broadcom                              | 114       | 5.9%    |
| MediaTek                              | 41        | 2.12%   |
| Ralink                                | 23        | 1.19%   |
| Broadcom Limited                      | 22        | 1.14%   |
| TP-Link                               | 11        | 0.57%   |
| Sierra Wireless                       | 11        | 0.57%   |
| Ralink Technology                     | 11        | 0.57%   |
| Qualcomm                              | 8         | 0.41%   |
| D-Link                                | 5         | 0.26%   |
| Ericsson Business Mobile Networks     | 4         | 0.21%   |
| Dell                                  | 4         | 0.21%   |
| Qualcomm Atheros Communications       | 3         | 0.16%   |
| NetGear                               | 3         | 0.16%   |
| ZyDAS                                 | 2         | 0.1%    |
| Fibocom                               | 2         | 0.1%    |
| Texas Instruments                     | 1         | 0.05%   |
| Linksys                               | 1         | 0.05%   |
| Hewlett-Packard                       | 1         | 0.05%   |
| Edimax Technology                     | 1         | 0.05%   |
| D-Link System                         | 1         | 0.05%   |
| Belkin Components                     | 1         | 0.05%   |
| AVM                                   | 1         | 0.05%   |
| ASUSTek Computer                      | 1         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 127       | 6.53%   |
| Intel Wireless 8265 / 8275                                     | 92        | 4.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 79        | 4.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 76        | 3.91%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 76        | 3.91%   |
| Intel Wireless 7260                                            | 74        | 3.8%    |
| Intel Wi-Fi 6 AX201                                            | 71        | 3.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 63        | 3.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 62        | 3.19%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 57        | 2.93%   |
| Intel Wireless 7265                                            | 55        | 2.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 52        | 2.67%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 50        | 2.57%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 50        | 2.57%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 40        | 2.06%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 38        | 1.95%   |
| Intel Wireless 8260                                            | 36        | 1.85%   |
| Intel Wireless 3165                                            | 34        | 1.75%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 32        | 1.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 31        | 1.59%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 31        | 1.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 29        | 1.49%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 28        | 1.44%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 23        | 1.18%   |
| Intel Wireless-AC 9260                                         | 21        | 1.08%   |
| Broadcom BCM43142 802.11b/g/n                                  | 21        | 1.08%   |
| Intel Wireless 3160                                            | 20        | 1.03%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 19        | 0.98%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 19        | 0.98%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 19        | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 17        | 0.87%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 17        | 0.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 16        | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 16        | 0.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 16        | 0.82%   |
| Intel Centrino Advanced-N 6235                                 | 16        | 0.82%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 13        | 0.67%   |
| Realtek 802.11n WLAN Adapter                                   | 12        | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 12        | 0.62%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 12        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 946       | 60.41%  |
| Intel                            | 354       | 22.61%  |
| Qualcomm Atheros                 | 92        | 5.87%   |
| Broadcom                         | 48        | 3.07%   |
| Marvell Technology Group         | 19        | 1.21%   |
| MediaTek                         | 15        | 0.96%   |
| ASIX Electronics                 | 13        | 0.83%   |
| DisplayLink                      | 12        | 0.77%   |
| Samsung Electronics              | 11        | 0.7%    |
| Lenovo                           | 9         | 0.57%   |
| Xiaomi                           | 7         | 0.45%   |
| JMicron Technology               | 6         | 0.38%   |
| Huawei Technologies              | 6         | 0.38%   |
| Broadcom Limited                 | 4         | 0.26%   |
| Apple                            | 4         | 0.26%   |
| TP-Link                          | 3         | 0.19%   |
| T & A Mobile Phones              | 3         | 0.19%   |
| Qualcomm                         | 3         | 0.19%   |
| Nvidia                           | 3         | 0.19%   |
| Google                           | 3         | 0.19%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.06%   |
| Silicon Integrated Systems [SiS] | 1         | 0.06%   |
| Motorola PCS                     | 1         | 0.06%   |
| HMD Global                       | 1         | 0.06%   |
| Hewlett-Packard                  | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 682       | 42.76%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 148       | 9.28%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 91        | 5.71%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 75        | 4.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 31        | 1.94%   |
| Intel Ethernet Connection (7) I219-LM                             | 23        | 1.44%   |
| Intel Ethernet Connection I218-LM                                 | 22        | 1.38%   |
| Intel Ethernet Connection I217-LM                                 | 20        | 1.25%   |
| Intel Ethernet Connection I219-LM                                 | 16        | 1%      |
| Intel Ethernet Connection (3) I218-LM                             | 16        | 1%      |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 15        | 0.94%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 15        | 0.94%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 14        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14        | 0.88%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 13        | 0.82%   |
| Intel Ethernet Connection (6) I219-V                              | 13        | 0.82%   |
| Intel 82577LM Gigabit Network Connection                          | 13        | 0.82%   |
| ASIX AX88179 Gigabit Ethernet                                     | 13        | 0.82%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 12        | 0.75%   |
| Realtek RTL8125 2.5GbE Controller                                 | 12        | 0.75%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 12        | 0.75%   |
| Intel Ethernet Connection (10) I219-V                             | 12        | 0.75%   |
| Intel Ethernet Connection (4) I219-V                              | 11        | 0.69%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 10        | 0.63%   |
| Intel Ethernet Connection I219-V                                  | 10        | 0.63%   |
| Intel Ethernet Connection (13) I219-V                             | 10        | 0.63%   |
| Intel 82567LM Gigabit Network Connection                          | 10        | 0.63%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 8         | 0.5%    |
| Intel Ethernet Connection (7) I219-V                              | 8         | 0.5%    |
| Intel 82579V Gigabit Network Connection                           | 8         | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7         | 0.44%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 7         | 0.44%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 7         | 0.44%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 6         | 0.38%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 0.38%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 6         | 0.38%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.38%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 6         | 0.38%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 0.31%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1853      | 55.18%  |
| Ethernet | 1483      | 44.16%  |
| Modem    | 20        | 0.6%    |
| Unknown  | 2         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1563      | 77.65%  |
| Ethernet | 449       | 22.31%  |
| Modem    | 1         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1371      | 72.73%  |
| 1     | 467       | 24.77%  |
| 0     | 35        | 1.86%   |
| 3     | 12        | 0.64%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1571      | 82.6%   |
| Yes  | 331       | 17.4%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 840       | 52.66%  |
| Realtek Semiconductor           | 172       | 10.78%  |
| Qualcomm Atheros Communications | 155       | 9.72%   |
| Broadcom                        | 80        | 5.02%   |
| IMC Networks                    | 77        | 4.83%   |
| Lite-On Technology              | 72        | 4.51%   |
| Foxconn / Hon Hai               | 58        | 3.64%   |
| Dell                            | 30        | 1.88%   |
| Realtek                         | 22        | 1.38%   |
| Apple                           | 19        | 1.19%   |
| Cambridge Silicon Radio         | 13        | 0.82%   |
| Hewlett-Packard                 | 12        | 0.75%   |
| Toshiba                         | 10        | 0.63%   |
| Ralink                          | 10        | 0.63%   |
| Foxconn International           | 7         | 0.44%   |
| Ralink Technology               | 5         | 0.31%   |
| Alps Electric                   | 4         | 0.25%   |
| ASUSTek Computer                | 3         | 0.19%   |
| Unknown                         | 2         | 0.13%   |
| Taiyo Yuden                     | 2         | 0.13%   |
| TP-Link                         | 1         | 0.06%   |
| Edimax Technology               | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 301       | 18.85%  |
| Intel AX201 Bluetooth                               | 174       | 10.9%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 135       | 8.45%   |
| Intel AX200 Bluetooth                               | 123       | 7.7%    |
| Realtek Bluetooth Radio                             | 97        | 6.07%   |
| Qualcomm Atheros  Bluetooth Device                  | 84        | 5.26%   |
| Realtek  Bluetooth 4.2 Adapter                      | 54        | 3.38%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 27        | 1.69%   |
| Lite-On Bluetooth Device                            | 27        | 1.69%   |
| IMC Networks Bluetooth Radio                        | 26        | 1.63%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 24        | 1.5%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 23        | 1.44%   |
| Intel Bluetooth Device                              | 20        | 1.25%   |
| Foxconn / Hon Hai Wireless_Device                   | 20        | 1.25%   |
| Foxconn / Hon Hai Bluetooth Device                  | 20        | 1.25%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 20        | 1.25%   |
| Realtek 802.11ac WLAN Adapter                       | 19        | 1.19%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 19        | 1.19%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 18        | 1.13%   |
| IMC Networks Wireless_Device                        | 18        | 1.13%   |
| Intel AX210 Bluetooth                               | 15        | 0.94%   |
| Broadcom BCM2045B (BDC-2.1)                         | 15        | 0.94%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 0.88%   |
| IMC Networks Bluetooth Device                       | 14        | 0.88%   |
| Lite-On Wireless_Device                             | 13        | 0.81%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 0.81%   |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 0.75%   |
| Realtek RTL8723B Bluetooth                          | 11        | 0.69%   |
| Dell BCM20702A0 Bluetooth Module                    | 11        | 0.69%   |
| Apple Bluetooth Host Controller                     | 11        | 0.69%   |
| Ralink RT3290 Bluetooth                             | 10        | 0.63%   |
| Broadcom HP Portable SoftSailing                    | 9         | 0.56%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 8         | 0.5%    |
| HP Broadcom 2070 Bluetooth Combo                    | 8         | 0.5%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 7         | 0.44%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.44%   |
| IMC Networks Bluetooth USB Host Controller          | 7         | 0.44%   |
| Foxconn International BCM43142A0 Bluetooth module   | 7         | 0.44%   |
| Dell DW375 Bluetooth Module                         | 7         | 0.44%   |
| Apple Bluetooth USB Host Controller                 | 6         | 0.38%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1504      | 63.19%  |
| AMD                              | 401       | 16.85%  |
| Nvidia                           | 305       | 12.82%  |
| Realtek Semiconductor            | 22        | 0.92%   |
| GN Netcom                        | 16        | 0.67%   |
| C-Media Electronics              | 15        | 0.63%   |
| Logitech                         | 14        | 0.59%   |
| Plantronics                      | 9         | 0.38%   |
| Lenovo                           | 8         | 0.34%   |
| Hewlett-Packard                  | 7         | 0.29%   |
| Generalplus Technology           | 6         | 0.25%   |
| Texas Instruments                | 5         | 0.21%   |
| JMTek                            | 5         | 0.21%   |
| Creative Technology              | 5         | 0.21%   |
| Sony                             | 4         | 0.17%   |
| Razer USA                        | 4         | 0.17%   |
| Dell                             | 4         | 0.17%   |
| CMX Systems                      | 3         | 0.13%   |
| ZOOM                             | 2         | 0.08%   |
| Microsoft                        | 2         | 0.08%   |
| Kingston Technology              | 2         | 0.08%   |
| GYROCOM C&C                      | 2         | 0.08%   |
| Google                           | 2         | 0.08%   |
| Focusrite-Novation               | 2         | 0.08%   |
| Conexant Systems                 | 2         | 0.08%   |
| Blue Microphones                 | 2         | 0.08%   |
| Apple                            | 2         | 0.08%   |
| Zhaoxin                          | 1         | 0.04%   |
| YZ Technology                    | 1         | 0.04%   |
| Winbond Electronics              | 1         | 0.04%   |
| Trust                            | 1         | 0.04%   |
| TerraTec Electronic              | 1         | 0.04%   |
| SteelSeries ApS                  | 1         | 0.04%   |
| Silicon Motion                   | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| RODE Microphones                 | 1         | 0.04%   |
| QinHeng Electronics              | 1         | 0.04%   |
| Princeton Technology             | 1         | 0.04%   |
| Nordic Semiconductor ASA         | 1         | 0.04%   |
| NanosIC                          | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 263       | 9%      |
| Intel Sunrise Point-LP HD Audio                                            | 223       | 7.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 160       | 5.48%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 132       | 4.52%   |
| Intel Cannon Lake PCH cAVS                                                 | 124       | 4.25%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 107       | 3.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 99        | 3.39%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 93        | 3.18%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 85        | 2.91%   |
| Intel Haswell-ULT HD Audio Controller                                      | 79        | 2.7%    |
| Intel 8 Series HD Audio Controller                                         | 79        | 2.7%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 77        | 2.64%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 76        | 2.6%    |
| Intel Comet Lake PCH-LP cAVS                                               | 63        | 2.16%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 53        | 1.81%   |
| AMD FCH Azalia Controller                                                  | 52        | 1.78%   |
| Intel Broadwell-U Audio Controller                                         | 50        | 1.71%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 49        | 1.68%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 49        | 1.68%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 47        | 1.61%   |
| Intel Comet Lake PCH cAVS                                                  | 47        | 1.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 44        | 1.51%   |
| Intel CM238 HD Audio Controller                                            | 41        | 1.4%    |
| AMD Kabini HDMI/DP Audio                                                   | 39        | 1.34%   |
| Nvidia GP107GL High Definition Audio Controller                            | 36        | 1.23%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 36        | 1.23%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 34        | 1.16%   |
| Nvidia TU106 High Definition Audio Controller                              | 31        | 1.06%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 31        | 1.06%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 28        | 0.96%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 23        | 0.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 23        | 0.79%   |
| Nvidia GF108 High Definition Audio Controller                              | 22        | 0.75%   |
| Realtek Semiconductor USB Audio                                            | 21        | 0.72%   |
| Nvidia GA104 High Definition Audio Controller                              | 21        | 0.72%   |
| Nvidia GP106 High Definition Audio Controller                              | 20        | 0.68%   |
| Nvidia TU116 High Definition Audio Controller                              | 19        | 0.65%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 19        | 0.65%   |
| Nvidia GA106 High Definition Audio Controller                              | 17        | 0.58%   |
| Nvidia GK107 HDMI Audio Controller                                         | 15        | 0.51%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 449       | 29.68%  |
| SK hynix            | 315       | 20.82%  |
| Micron Technology   | 191       | 12.62%  |
| Kingston            | 150       | 9.91%   |
| Crucial             | 88        | 5.82%   |
| Unknown             | 56        | 3.7%    |
| A-DATA Technology   | 35        | 2.31%   |
| Ramaxel Technology  | 34        | 2.25%   |
| Elpida              | 28        | 1.85%   |
| Unknown (ABCD)      | 25        | 1.65%   |
| Nanya Technology    | 21        | 1.39%   |
| Corsair             | 18        | 1.19%   |
| Unknown             | 12        | 0.79%   |
| Smart               | 10        | 0.66%   |
| Transcend           | 9         | 0.59%   |
| G.Skill             | 7         | 0.46%   |
| Wilk                | 5         | 0.33%   |
| Smart Brazil        | 5         | 0.33%   |
| Teikon              | 4         | 0.26%   |
| Team                | 4         | 0.26%   |
| GOODRAM             | 4         | 0.26%   |
| Apacer              | 4         | 0.26%   |
| Silicon Power       | 3         | 0.2%    |
| SHARETRONIC         | 3         | 0.2%    |
| Goldkey             | 3         | 0.2%    |
| CSX                 | 2         | 0.13%   |
| ASint Technology    | 2         | 0.13%   |
| AMD                 | 2         | 0.13%   |
| V-GeN               | 1         | 0.07%   |
| V-Color             | 1         | 0.07%   |
| Unknown (8A02)      | 1         | 0.07%   |
| Unknown (08AE)      | 1         | 0.07%   |
| Super Talent        | 1         | 0.07%   |
| Shenzhen Zhongteng  | 1         | 0.07%   |
| Shenzhen WODPOSIT   | 1         | 0.07%   |
| Reboto              | 1         | 0.07%   |
| Qimonda             | 1         | 0.07%   |
| PUSKILL             | 1         | 0.07%   |
| Patriot             | 1         | 0.07%   |
| Magnum Tech         | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 24        | 1.5%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 23        | 1.44%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 23        | 1.44%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 22        | 1.38%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 20        | 1.25%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 17        | 1.07%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 17        | 1.07%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 16        | 1%      |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 14        | 0.88%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 14        | 0.88%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.88%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 14        | 0.88%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.82%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 13        | 0.82%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 13        | 0.82%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 12        | 0.75%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 12        | 0.75%   |
| Unknown                                                          | 12        | 0.75%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 11        | 0.69%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 11        | 0.69%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.69%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 11        | 0.69%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 11        | 0.69%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 11        | 0.69%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 0.63%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 10        | 0.63%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 10        | 0.63%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.63%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 10        | 0.63%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 10        | 0.63%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 9         | 0.56%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.5%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.5%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 8         | 0.5%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 0.5%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 8         | 0.5%    |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 8         | 0.5%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.5%    |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.44%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 747       | 59.47%  |
| DDR3    | 344       | 27.39%  |
| LPDDR4  | 65        | 5.18%   |
| LPDDR3  | 40        | 3.18%   |
| DDR2    | 18        | 1.43%   |
| DDR5    | 16        | 1.27%   |
| SDRAM   | 13        | 1.04%   |
| LPDDR5  | 7         | 0.56%   |
| Unknown | 5         | 0.4%    |
| DDR     | 1         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1127      | 88.81%  |
| Row Of Chips | 119       | 9.38%   |
| Chip         | 11        | 0.87%   |
| Unknown      | 7         | 0.55%   |
| DIMM         | 5         | 0.39%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 621       | 45.2%   |
| 4096  | 384       | 27.95%  |
| 16384 | 233       | 16.96%  |
| 2048  | 86        | 6.26%   |
| 32768 | 37        | 2.69%   |
| 1024  | 13        | 0.95%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 364       | 26.8%   |
| 3200    | 274       | 20.18%  |
| 1600    | 259       | 19.07%  |
| 2400    | 134       | 9.87%   |
| 2133    | 65        | 4.79%   |
| 1334    | 53        | 3.9%    |
| 1333    | 39        | 2.87%   |
| 4267    | 24        | 1.77%   |
| 1867    | 18        | 1.33%   |
| 3266    | 17        | 1.25%   |
| 4800    | 16        | 1.18%   |
| 8400    | 12        | 0.88%   |
| 1067    | 10        | 0.74%   |
| 667     | 10        | 0.74%   |
| Unknown | 10        | 0.74%   |
| 4199    | 9         | 0.66%   |
| 800     | 9         | 0.66%   |
| 6400    | 7         | 0.52%   |
| 4266    | 6         | 0.44%   |
| 2048    | 4         | 0.29%   |
| 1066    | 3         | 0.22%   |
| 975     | 3         | 0.22%   |
| 3000    | 2         | 0.15%   |
| 2933    | 2         | 0.15%   |
| 1866    | 2         | 0.15%   |
| 2666    | 1         | 0.07%   |
| 2000    | 1         | 0.07%   |
| 1776    | 1         | 0.07%   |
| 1200    | 1         | 0.07%   |
| 666     | 1         | 0.07%   |
| 533     | 1         | 0.07%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 23.53%  |
| Brother Industries  | 4         | 23.53%  |
| Samsung Electronics | 3         | 17.65%  |
| Canon               | 3         | 17.65%  |
| Seiko Epson         | 2         | 11.76%  |
| Xerox               | 1         | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Notebooks | Percent |
|-------------------------------------------------|-----------|---------|
| Xerox Phaser 6500DN                             | 1         | 5.88%   |
| Seiko Epson L3110 Series                        | 1         | 5.88%   |
| Seiko Epson ET-2700 Series                      | 1         | 5.88%   |
| Samsung Xerox Phaser 3117 Laser Printer         | 1         | 5.88%   |
| Samsung SCX-3200 Series                         | 1         | 5.88%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 1         | 5.88%   |
| HP LaserJet Professional P 1102w                | 1         | 5.88%   |
| HP LaserJet 1020                                | 1         | 5.88%   |
| HP DeskJet F300 series                          | 1         | 5.88%   |
| HP DeskJet 2300 series                          | 1         | 5.88%   |
| Canon PIXMA MP250                               | 1         | 5.88%   |
| Canon MF4800 Series                             | 1         | 5.88%   |
| Canon iP2600 series                             | 1         | 5.88%   |
| Brother MFC-J4340DW                             | 1         | 5.88%   |
| Brother HL-L2390DW                              | 1         | 5.88%   |
| Brother HL-5450DN series                        | 1         | 5.88%   |
| Brother HL-2230 series                          | 1         | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 50%     |
| Canon       | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 50%     |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 396       | 22.15%  |
| IMC Networks                           | 202       | 11.3%   |
| Microdia                               | 172       | 9.62%   |
| Acer                                   | 168       | 9.4%    |
| Realtek Semiconductor                  | 151       | 8.45%   |
| Quanta                                 | 115       | 6.43%   |
| Sunplus Innovation Technology          | 100       | 5.59%   |
| Cheng Uei Precision Industry (Foxlink) | 83        | 4.64%   |
| Suyin                                  | 44        | 2.46%   |
| Syntek                                 | 39        | 2.18%   |
| Silicon Motion                         | 38        | 2.13%   |
| Lite-On Technology                     | 37        | 2.07%   |
| Logitech                               | 32        | 1.79%   |
| Luxvisions Innotech Limited            | 25        | 1.4%    |
| Apple                                  | 24        | 1.34%   |
| Alcor Micro                            | 19        | 1.06%   |
| Ricoh                                  | 15        | 0.84%   |
| Samsung Electronics                    | 12        | 0.67%   |
| Lenovo                                 | 10        | 0.56%   |
| Sonix Technology                       | 7         | 0.39%   |
| Y Media                                | 6         | 0.34%   |
| SunplusIT                              | 6         | 0.34%   |
| Sunplus Technology                     | 5         | 0.28%   |
| Importek                               | 5         | 0.28%   |
| DLEQNA19IFK6G2                         | 5         | 0.28%   |
| Microsoft                              | 4         | 0.22%   |
| icSpring                               | 4         | 0.22%   |
| Generalplus Technology                 | 4         | 0.22%   |
| Bison Electronics                      | 4         | 0.22%   |
| Z-Star Microelectronics                | 3         | 0.17%   |
| ShineTech                              | 3         | 0.17%   |
| Intel                                  | 3         | 0.17%   |
| Genesys Logic                          | 3         | 0.17%   |
| USB Camera CS                          | 2         | 0.11%   |
| Novatek Microelectronics               | 2         | 0.11%   |
| MacroSilicon                           | 2         | 0.11%   |
| LG Electronics                         | 2         | 0.11%   |
| Google                                 | 2         | 0.11%   |
| GEMBIRD                                | 2         | 0.11%   |
| DigiTech                               | 2         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 89        | 4.94%   |
| Microdia Integrated_Webcam_HD                                              | 82        | 4.55%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 62        | 3.44%   |
| Realtek Integrated_Webcam_HD                                               | 61        | 3.39%   |
| IMC Networks Integrated Camera                                             | 60        | 3.33%   |
| Sunplus Integrated_Webcam_HD                                               | 50        | 2.78%   |
| Acer Integrated Camera                                                     | 48        | 2.67%   |
| Chicony HD Webcam                                                          | 45        | 2.5%    |
| Chicony USB2.0 Camera                                                      | 29        | 1.61%   |
| Syntek Integrated Camera                                                   | 26        | 1.44%   |
| Quanta HD User Facing                                                      | 25        | 1.39%   |
| Acer Lenovo EasyCamera                                                     | 24        | 1.33%   |
| Chicony HP HD Camera                                                       | 23        | 1.28%   |
| Chicony HD User Facing                                                     | 22        | 1.22%   |
| Microdia Integrated Webcam                                                 | 21        | 1.17%   |
| Acer HD Webcam                                                             | 21        | 1.17%   |
| Chicony Integrated Camera (1280x720@30)                                    | 16        | 0.89%   |
| Quanta HP TrueVision HD Camera                                             | 15        | 0.83%   |
| Quanta HP HD Camera                                                        | 15        | 0.83%   |
| Lite-On Integrated Camera                                                  | 15        | 0.83%   |
| Acer BisonCam, NB Pro                                                      | 15        | 0.83%   |
| Quanta HD Webcam                                                           | 14        | 0.78%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 13        | 0.72%   |
| Chicony HP Wide Vision HD Camera                                           | 13        | 0.72%   |
| Samsung Galaxy A5 (MTP)                                                    | 12        | 0.67%   |
| Realtek Integrated Webcam HD                                               | 12        | 0.67%   |
| Chicony HP TrueVision HD                                                   | 12        | 0.67%   |
| Realtek Integrated Webcam                                                  | 11        | 0.61%   |
| IMC Networks ov9734_azurewave_camera                                       | 11        | 0.61%   |
| Chicony HP Truevision HD camera                                            | 11        | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 11        | 0.61%   |
| Acer BisonCam,NB Pro                                                       | 11        | 0.61%   |
| Realtek USB Camera                                                         | 10        | 0.56%   |
| Microdia Webcam Vitade AF                                                  | 10        | 0.56%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 10        | 0.56%   |
| Logitech HD Pro Webcam C920                                                | 10        | 0.56%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera            | 10        | 0.56%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 10        | 0.56%   |
| Sunplus HD WebCam                                                          | 9         | 0.5%    |
| Quanta HP Webcam                                                           | 9         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 113       | 28.25%  |
| Validity Sensors                   | 111       | 27.75%  |
| Shenzhen Goodix Technology         | 80        | 20%     |
| Elan Microelectronics              | 33        | 8.25%   |
| Upek                               | 21        | 5.25%   |
| AuthenTec                          | 18        | 4.5%    |
| LighTuning Technology              | 16        | 4%      |
| STMicroelectronics                 | 5         | 1.25%   |
| Focal-systems.Corp                 | 2         | 0.5%    |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 48        | 12%     |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 46        | 11.5%   |
| Unknown                                                                    | 27        | 6.75%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 21        | 5.25%   |
| Elan ELAN:Fingerprint                                                      | 21        | 5.25%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 19        | 4.75%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 19        | 4.75%   |
| Shenzhen Goodix Fingerprint Reader                                         | 17        | 4.25%   |
| Shenzhen Goodix FingerPrint                                                | 15        | 3.75%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 3.25%   |
| Validity Sensors Synaptics WBDI                                            | 11        | 2.75%   |
| Elan ELAN:ARM-M4                                                           | 11        | 2.75%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 10        | 2.5%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 10        | 2.5%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 2.25%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 2.25%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 2.25%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 2%      |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 2%      |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.75%   |
| AuthenTec AES2810                                                          | 7         | 1.75%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 1.25%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.25%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 1.25%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 5         | 1.25%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.25%   |
| Validity Sensors VFS491                                                    | 4         | 1%      |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1%      |
| Synaptics  WBDI                                                            | 3         | 0.75%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.75%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 0.5%    |
| Synaptics WBDI Device                                                      | 2         | 0.5%    |
| Focal-systems.Corp FT9201Fingerprint.                                      | 2         | 0.5%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.5%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.25%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.25%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.25%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.25%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.25%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Notebooks | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 80        | 46.51%  |
| Alcor Micro               | 50        | 29.07%  |
| Upek                      | 13        | 7.56%   |
| O2 Micro                  | 8         | 4.65%   |
| Lenovo                    | 7         | 4.07%   |
| Yubico.com                | 2         | 1.16%   |
| Realtek Semiconductor     | 2         | 1.16%   |
| Watchdata                 | 1         | 0.58%   |
| SCM Microsystems          | 1         | 0.58%   |
| In Focus Systems          | 1         | 0.58%   |
| Giesecke & Devrient       | 1         | 0.58%   |
| Fujitsu Siemens Computers | 1         | 0.58%   |
| Clay Logic                | 1         | 0.58%   |
| Chicony Electronics       | 1         | 0.58%   |
| BIT4ID                    | 1         | 0.58%   |
| Aladdin Knowledge Systems | 1         | 0.58%   |
| Advanced Card Systems     | 1         | 0.58%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 50        | 29.07%  |
| Broadcom 5880                                                                | 23        | 13.37%  |
| Broadcom 58200                                                               | 21        | 12.21%  |
| Broadcom BCM5880 Secure Applications Processor                               | 20        | 11.63%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 14        | 8.14%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 13        | 7.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 4.65%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 4.07%   |
| Yubico.com Yubikey 4 U2F+CCID                                                | 2         | 1.16%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.16%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.16%   |
| Watchdata USB Key                                                            | 1         | 0.58%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.58%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.58%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.58%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.58%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.58%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.58%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.58%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.58%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.58%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1142      | 59.32%  |
| 1     | 626       | 32.52%  |
| 2     | 136       | 7.06%   |
| 3     | 10        | 0.52%   |
| 4     | 5         | 0.26%   |
| 7     | 3         | 0.16%   |
| 6     | 2         | 0.1%    |
| 9     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 393       | 41.15%  |
| Chipcard                 | 156       | 16.34%  |
| Graphics card            | 154       | 16.13%  |
| Net/wireless             | 83        | 8.69%   |
| Camera                   | 36        | 3.77%   |
| Multimedia controller    | 32        | 3.35%   |
| Bluetooth                | 27        | 2.83%   |
| Sound                    | 17        | 1.78%   |
| Card reader              | 15        | 1.57%   |
| Communication controller | 14        | 1.47%   |
| Storage                  | 13        | 1.36%   |
| Net/ethernet             | 6         | 0.63%   |
| Network                  | 4         | 0.42%   |
| Modem                    | 4         | 0.42%   |
| Firewire controller      | 1         | 0.1%    |

