Linux in Ecuador - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Ecuador.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Ecuador/Desktop/README.md) and [notebooks](/Location/Ecuador/Notebook/README.md).

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

Total: 508

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | X455LJ                      | Notebook    | [dae3d540f6](https://linux-hardware.org/?probe=dae3d540f6) | Dec 18, 2024 |
| ASUSTek       | E202SA                      | Notebook    | [b4fe788f4e](https://linux-hardware.org/?probe=b4fe788f4e) | Dec 17, 2024 |
| MSI           | B550-A PRO                  | Desktop     | [204aaa19ef](https://linux-hardware.org/?probe=204aaa19ef) | Dec 13, 2024 |
| Lenovo        | Y50-70 20378                | Notebook    | [c70be6f167](https://linux-hardware.org/?probe=c70be6f167) | Dec 04, 2024 |
| Dell          | Latitude E6440              | Notebook    | [2c75de8400](https://linux-hardware.org/?probe=2c75de8400) | Dec 01, 2024 |
| ASUSTek       | E202SA                      | Notebook    | [18a63b065d](https://linux-hardware.org/?probe=18a63b065d) | Nov 07, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [2264ba28f3](https://linux-hardware.org/?probe=2264ba28f3) | Oct 24, 2024 |
| Dell          | Latitude E6420              | Notebook    | [007ca74afb](https://linux-hardware.org/?probe=007ca74afb) | Oct 21, 2024 |
| Dell          | Latitude E6420              | Notebook    | [a6a2d8c1fe](https://linux-hardware.org/?probe=a6a2d8c1fe) | Oct 20, 2024 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [5820bd151b](https://linux-hardware.org/?probe=5820bd151b) | Oct 17, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [479b6dd12a](https://linux-hardware.org/?probe=479b6dd12a) | Oct 16, 2024 |
| Apple         | MacBookPro12,1              | Notebook    | [9b61bff954](https://linux-hardware.org/?probe=9b61bff954) | Oct 16, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [47f24a1302](https://linux-hardware.org/?probe=47f24a1302) | Oct 13, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [0b81ce4446](https://linux-hardware.org/?probe=0b81ce4446) | Oct 03, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [90af0212ea](https://linux-hardware.org/?probe=90af0212ea) | Sep 27, 2024 |
| Dell          | 0F3KHR A00                  | Desktop     | [0293193b5e](https://linux-hardware.org/?probe=0293193b5e) | Sep 26, 2024 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3be9ed3045](https://linux-hardware.org/?probe=3be9ed3045) | Sep 15, 2024 |
| Dell          | Inspiron 3458               | Notebook    | [79c31f85e1](https://linux-hardware.org/?probe=79c31f85e1) | Sep 13, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [b00cab52d1](https://linux-hardware.org/?probe=b00cab52d1) | Sep 05, 2024 |
| Dell          | 0VV4V0 A00                  | All in one  | [078a22f745](https://linux-hardware.org/?probe=078a22f745) | Sep 03, 2024 |
| HP            | Pavilion g4                 | Notebook    | [c9131e779e](https://linux-hardware.org/?probe=c9131e779e) | Aug 24, 2024 |
| Unknown       | Unknown                     | Notebook    | [bbbbf2ec13](https://linux-hardware.org/?probe=bbbbf2ec13) | Aug 13, 2024 |
| Acer          | Swift SFE16-43              | Notebook    | [083b0cac5f](https://linux-hardware.org/?probe=083b0cac5f) | Aug 12, 2024 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [cf835ce8d2](https://linux-hardware.org/?probe=cf835ce8d2) | Aug 11, 2024 |
| HP            | Notebook                    | Notebook    | [1a796d1daf](https://linux-hardware.org/?probe=1a796d1daf) | Aug 04, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [32d11d630e](https://linux-hardware.org/?probe=32d11d630e) | Aug 01, 2024 |
| Biostar       | H61MLB                      | Desktop     | [10f695fe18](https://linux-hardware.org/?probe=10f695fe18) | Jul 31, 2024 |
| HP            | Laptop 15-gw0xxx            | Notebook    | [f50ff2bcfb](https://linux-hardware.org/?probe=f50ff2bcfb) | Jul 31, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [5cd2fdb7f3](https://linux-hardware.org/?probe=5cd2fdb7f3) | Jul 23, 2024 |
| ASRock        | B650M PG Riptide            | Desktop     | [2672901369](https://linux-hardware.org/?probe=2672901369) | Jul 22, 2024 |
| HP            | Pavilion g4                 | Notebook    | [922cae179f](https://linux-hardware.org/?probe=922cae179f) | Jul 13, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [c802131da8](https://linux-hardware.org/?probe=c802131da8) | Jul 07, 2024 |
| ASUSTek       | TP410UAR                    | Convertible | [fb5a78c205](https://linux-hardware.org/?probe=fb5a78c205) | Jul 05, 2024 |
| Dell          | Vostro 5502                 | Notebook    | [02acef5e70](https://linux-hardware.org/?probe=02acef5e70) | Jul 04, 2024 |
| ASUSTek       | PRIME H610M-K D4            | Desktop     | [92ca1f097e](https://linux-hardware.org/?probe=92ca1f097e) | Jun 30, 2024 |
| Acer          | Aspire A315-44P             | Notebook    | [d139897a73](https://linux-hardware.org/?probe=d139897a73) | Jun 28, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [6fb2ca786a](https://linux-hardware.org/?probe=6fb2ca786a) | Jun 19, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [f5baa7dc23](https://linux-hardware.org/?probe=f5baa7dc23) | Jun 19, 2024 |
| Toshiba       | Satellite P855              | Notebook    | [e3c736f4b8](https://linux-hardware.org/?probe=e3c736f4b8) | Jun 18, 2024 |
| Dell          | Inspiron N4050              | Notebook    | [5d77f14b5f](https://linux-hardware.org/?probe=5d77f14b5f) | Jun 18, 2024 |
| Toshiba       | Satellite P855              | Notebook    | [71b541e230](https://linux-hardware.org/?probe=71b541e230) | Jun 16, 2024 |
| Gigabyte      | H81M-S1                     | Desktop     | [4852045434](https://linux-hardware.org/?probe=4852045434) | Jun 08, 2024 |
| Intel         | DH61BF AAG81311-102         | Desktop     | [e33f8a4718](https://linux-hardware.org/?probe=e33f8a4718) | Jun 01, 2024 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [d447330673](https://linux-hardware.org/?probe=d447330673) | Jun 01, 2024 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [ca35abddb1](https://linux-hardware.org/?probe=ca35abddb1) | May 30, 2024 |
| Lenovo        | V330-14ISK 81AY             | Notebook    | [fd2bdae039](https://linux-hardware.org/?probe=fd2bdae039) | May 24, 2024 |
| Lenovo        | ThinkPad S1 Yoga 20C0S0U... | Notebook    | [630273772a](https://linux-hardware.org/?probe=630273772a) | May 19, 2024 |
| Acer          | Aspire V5-471P              | Notebook    | [00d54a6432](https://linux-hardware.org/?probe=00d54a6432) | May 13, 2024 |
| Acer          | Aspire V5-471P              | Notebook    | [d9b4f36303](https://linux-hardware.org/?probe=d9b4f36303) | May 13, 2024 |
| HP            | 8299                        | Desktop     | [6024274be6](https://linux-hardware.org/?probe=6024274be6) | May 06, 2024 |
| ECS           | H61H2-TI                    | All in one  | [6a421efdca](https://linux-hardware.org/?probe=6a421efdca) | May 01, 2024 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [a823e9adf2](https://linux-hardware.org/?probe=a823e9adf2) | Apr 26, 2024 |
| Pegatron      | 2AA1h                       | Desktop     | [52b3bc466c](https://linux-hardware.org/?probe=52b3bc466c) | Apr 25, 2024 |
| HP            | 1000                        | Notebook    | [dee2aa2dd9](https://linux-hardware.org/?probe=dee2aa2dd9) | Apr 25, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [d4f3102f5c](https://linux-hardware.org/?probe=d4f3102f5c) | Apr 25, 2024 |
| MSI           | Stealth GS77 12UE           | Notebook    | [47ff584537](https://linux-hardware.org/?probe=47ff584537) | Apr 14, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [39dff10b12](https://linux-hardware.org/?probe=39dff10b12) | Apr 08, 2024 |
| ASRock        | Z790 Steel Legend WiFi      | Desktop     | [cdfa410878](https://linux-hardware.org/?probe=cdfa410878) | Apr 05, 2024 |
| ASRock        | Z790 Steel Legend WiFi      | Desktop     | [9e4b6c171a](https://linux-hardware.org/?probe=9e4b6c171a) | Apr 04, 2024 |
| Intel         | H55                         | Desktop     | [361d690313](https://linux-hardware.org/?probe=361d690313) | Mar 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [a95e92f1f5](https://linux-hardware.org/?probe=a95e92f1f5) | Mar 16, 2024 |
| Dell          | G15 5515                    | Notebook    | [527be515b4](https://linux-hardware.org/?probe=527be515b4) | Mar 12, 2024 |
| Toshiba       | Satellite P855              | Notebook    | [cb7eb1810c](https://linux-hardware.org/?probe=cb7eb1810c) | Feb 26, 2024 |
| HP            | OMEN by Laptop              | Notebook    | [68bbab3ac1](https://linux-hardware.org/?probe=68bbab3ac1) | Feb 19, 2024 |
| Google        | Blooglet                    | Notebook    | [66b986a87d](https://linux-hardware.org/?probe=66b986a87d) | Feb 19, 2024 |
| HP            | 245 G8                      | Notebook    | [c66563da68](https://linux-hardware.org/?probe=c66563da68) | Feb 14, 2024 |
| Google        | Blooglet                    | Notebook    | [34a54def3d](https://linux-hardware.org/?probe=34a54def3d) | Feb 13, 2024 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [f4f20111f0](https://linux-hardware.org/?probe=f4f20111f0) | Feb 12, 2024 |
| Toshiba       | Satellite C55-B             | Notebook    | [f9989aa45a](https://linux-hardware.org/?probe=f9989aa45a) | Feb 09, 2024 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [21be6e4ab5](https://linux-hardware.org/?probe=21be6e4ab5) | Feb 07, 2024 |
| ASUSTek       | H110M-D                     | Desktop     | [7f2b907eb8](https://linux-hardware.org/?probe=7f2b907eb8) | Jan 25, 2024 |
| Dell          | Latitude D630               | Notebook    | [bf9ce8c208](https://linux-hardware.org/?probe=bf9ce8c208) | Jan 21, 2024 |
| Dell          | Latitude D630               | Notebook    | [b2a68014db](https://linux-hardware.org/?probe=b2a68014db) | Jan 21, 2024 |
| Unknown       | Orange Pi 5 Plus            | Soc         | [c6ba3badcb](https://linux-hardware.org/?probe=c6ba3badcb) | Jan 18, 2024 |
| Unknown       | Orange Pi 5 Plus            | Soc         | [342f21a2ff](https://linux-hardware.org/?probe=342f21a2ff) | Jan 18, 2024 |
| Acer          | Aspire A715-51G             | Notebook    | [2a3ea77b7a](https://linux-hardware.org/?probe=2a3ea77b7a) | Jan 10, 2024 |
| Acer          | Aspire A715-51G             | Notebook    | [d4a9b3c259](https://linux-hardware.org/?probe=d4a9b3c259) | Jan 09, 2024 |
| Lenovo        | IdeaPad S145-14API 81UV     | Notebook    | [3a14a938f8](https://linux-hardware.org/?probe=3a14a938f8) | Jan 08, 2024 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [186230d9c6](https://linux-hardware.org/?probe=186230d9c6) | Jan 08, 2024 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [f8466df8c5](https://linux-hardware.org/?probe=f8466df8c5) | Dec 26, 2023 |
| HP            | 1000                        | Notebook    | [2279f68ba4](https://linux-hardware.org/?probe=2279f68ba4) | Dec 21, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [6a493a834d](https://linux-hardware.org/?probe=6a493a834d) | Dec 14, 2023 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [9d34609e0d](https://linux-hardware.org/?probe=9d34609e0d) | Dec 14, 2023 |
| HP            | Laptop 15-dw1xxx            | Notebook    | [d05f324edf](https://linux-hardware.org/?probe=d05f324edf) | Nov 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 16IHU6 82L... | Notebook    | [cc934b68d9](https://linux-hardware.org/?probe=cc934b68d9) | Nov 22, 2023 |
| HP            | Unknown                     | Notebook    | [d065dfae65](https://linux-hardware.org/?probe=d065dfae65) | Nov 19, 2023 |
| HP            | Unknown                     | Notebook    | [539958ff9d](https://linux-hardware.org/?probe=539958ff9d) | Nov 19, 2023 |
| MSI           | PRO H610M-G DDR4            | Notebook    | [5955e4e776](https://linux-hardware.org/?probe=5955e4e776) | Nov 15, 2023 |
| MSI           | PRO H610M-G DDR4            | Notebook    | [f41807e01e](https://linux-hardware.org/?probe=f41807e01e) | Nov 14, 2023 |
| Toshiba       | Satellite S55-B             | Notebook    | [bcc2e19a3a](https://linux-hardware.org/?probe=bcc2e19a3a) | Nov 12, 2023 |
| HP            | 245 G8                      | Notebook    | [0b471d312a](https://linux-hardware.org/?probe=0b471d312a) | Nov 11, 2023 |
| HP            | 245 G8                      | Notebook    | [b29efc88ec](https://linux-hardware.org/?probe=b29efc88ec) | Nov 11, 2023 |
| HP            | 245 G8                      | Notebook    | [e9c1cc78b8](https://linux-hardware.org/?probe=e9c1cc78b8) | Nov 06, 2023 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [810297d46b](https://linux-hardware.org/?probe=810297d46b) | Oct 30, 2023 |
| Razer         | Blade Stealth               | Notebook    | [0ebbfdba6a](https://linux-hardware.org/?probe=0ebbfdba6a) | Oct 26, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [21a31e5298](https://linux-hardware.org/?probe=21a31e5298) | Oct 21, 2023 |
| MSI           | Stealth 16Studio A13VG      | Notebook    | [46e4f7a743](https://linux-hardware.org/?probe=46e4f7a743) | Oct 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [3a6c620560](https://linux-hardware.org/?probe=3a6c620560) | Oct 13, 2023 |
| Alienware     | m15                         | Notebook    | [9ac9acc336](https://linux-hardware.org/?probe=9ac9acc336) | Oct 12, 2023 |
| Alienware     | m15                         | Notebook    | [8b4a8c8fc9](https://linux-hardware.org/?probe=8b4a8c8fc9) | Oct 12, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [bd6094c5cd](https://linux-hardware.org/?probe=bd6094c5cd) | Oct 08, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [d343f99b47](https://linux-hardware.org/?probe=d343f99b47) | Oct 06, 2023 |
| Toshiba       | Satellite A205              | Notebook    | [7b78b2ea5b](https://linux-hardware.org/?probe=7b78b2ea5b) | Oct 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9b1cc15d8a](https://linux-hardware.org/?probe=9b1cc15d8a) | Sep 30, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e2c6027a51](https://linux-hardware.org/?probe=e2c6027a51) | Sep 30, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGA... | Notebook    | [8c1d3fc469](https://linux-hardware.org/?probe=8c1d3fc469) | Sep 29, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20UGA... | Notebook    | [c38ca27643](https://linux-hardware.org/?probe=c38ca27643) | Sep 29, 2023 |
| Valve         | Jupiter                     | Notebook    | [f4582a5754](https://linux-hardware.org/?probe=f4582a5754) | Sep 22, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [5fac0d7732](https://linux-hardware.org/?probe=5fac0d7732) | Sep 20, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [09c45a1e2d](https://linux-hardware.org/?probe=09c45a1e2d) | Sep 17, 2023 |
| Lenovo        | ThinkPad E520 11433FU       | Notebook    | [eb0aa53dc9](https://linux-hardware.org/?probe=eb0aa53dc9) | Sep 08, 2023 |
| Toshiba       | Satellite A205              | Notebook    | [9a44e74608](https://linux-hardware.org/?probe=9a44e74608) | Sep 06, 2023 |
| Toshiba       | Satellite A205              | Notebook    | [a2b456886d](https://linux-hardware.org/?probe=a2b456886d) | Sep 05, 2023 |
| Lenovo        | ThinkPad E520 11433FU       | Notebook    | [ecc10a1197](https://linux-hardware.org/?probe=ecc10a1197) | Sep 04, 2023 |
| Toshiba       | Satellite L50-B             | Notebook    | [9dd40cd022](https://linux-hardware.org/?probe=9dd40cd022) | Sep 03, 2023 |
| HP            | Laptop 14-cm0xxx            | Notebook    | [a1caab6466](https://linux-hardware.org/?probe=a1caab6466) | Aug 27, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4ea732e404](https://linux-hardware.org/?probe=4ea732e404) | Aug 17, 2023 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | Notebook    | [bbf57bf744](https://linux-hardware.org/?probe=bbf57bf744) | Aug 17, 2023 |
| Gigabyte      | H270M-D3H-CF                | Desktop     | [5c8f4ac5c0](https://linux-hardware.org/?probe=5c8f4ac5c0) | Aug 16, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [ee72caa76d](https://linux-hardware.org/?probe=ee72caa76d) | Aug 16, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | Notebook    | [2a3b142ddd](https://linux-hardware.org/?probe=2a3b142ddd) | Aug 16, 2023 |
| Gigabyte      | B150M-D3H DDR3-CF           | Desktop     | [5df6fee2f9](https://linux-hardware.org/?probe=5df6fee2f9) | Aug 09, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [5bd12768fa](https://linux-hardware.org/?probe=5bd12768fa) | Aug 09, 2023 |
| Dell          | Vostro 3480                 | Notebook    | [78fbe42595](https://linux-hardware.org/?probe=78fbe42595) | Aug 07, 2023 |
| Toshiba       | Satellite A135              | Notebook    | [2eddaa2a26](https://linux-hardware.org/?probe=2eddaa2a26) | Jul 30, 2023 |
| Toshiba       | Satellite A135              | Notebook    | [5bd6d0c2d8](https://linux-hardware.org/?probe=5bd6d0c2d8) | Jul 20, 2023 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [d80699b846](https://linux-hardware.org/?probe=d80699b846) | Jul 13, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [602c50a904](https://linux-hardware.org/?probe=602c50a904) | Jul 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [7117d51b53](https://linux-hardware.org/?probe=7117d51b53) | Jun 21, 2023 |
| Biostar       | H61MGV3                     | Desktop     | [109f8064f6](https://linux-hardware.org/?probe=109f8064f6) | Jun 21, 2023 |
| Intel         | DG35EC AAE29266-209         | Desktop     | [bfdb13f626](https://linux-hardware.org/?probe=bfdb13f626) | Jun 20, 2023 |
| Gigabyte      | B150M-D3H DDR3-CF           | Desktop     | [3e5a0aac78](https://linux-hardware.org/?probe=3e5a0aac78) | Jun 19, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b05e4ee752](https://linux-hardware.org/?probe=b05e4ee752) | Jun 15, 2023 |
| Dell          | Inspiron 3493               | Notebook    | [ffcd21fc3b](https://linux-hardware.org/?probe=ffcd21fc3b) | Jun 09, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [f661806559](https://linux-hardware.org/?probe=f661806559) | Jun 02, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [a57949da97](https://linux-hardware.org/?probe=a57949da97) | Jun 01, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [7f0cf2e62d](https://linux-hardware.org/?probe=7f0cf2e62d) | Jun 01, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [e365621d30](https://linux-hardware.org/?probe=e365621d30) | May 31, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [5f8bd19e3d](https://linux-hardware.org/?probe=5f8bd19e3d) | May 31, 2023 |
| Lenovo        | ThinkPad L480 20LTA01LLM    | Notebook    | [ed45fc495a](https://linux-hardware.org/?probe=ed45fc495a) | May 22, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [8fb1a89166](https://linux-hardware.org/?probe=8fb1a89166) | May 17, 2023 |
| Acer          | Extensa 5220                | Notebook    | [261e743adc](https://linux-hardware.org/?probe=261e743adc) | May 11, 2023 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [1f232288d7](https://linux-hardware.org/?probe=1f232288d7) | May 07, 2023 |
| Sony          | VPCEG23EL                   | Notebook    | [c28e3338ce](https://linux-hardware.org/?probe=c28e3338ce) | Apr 28, 2023 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [76674fb178](https://linux-hardware.org/?probe=76674fb178) | Apr 26, 2023 |
| Lenovo        | IdeaPad S145-14IGM 81MW     | Notebook    | [5cb6709055](https://linux-hardware.org/?probe=5cb6709055) | Apr 20, 2023 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [d7d0bcde76](https://linux-hardware.org/?probe=d7d0bcde76) | Apr 15, 2023 |
| Biostar       | H81MHV3L                    | Desktop     | [8638a242be](https://linux-hardware.org/?probe=8638a242be) | Apr 10, 2023 |
| HP            | Notebook                    | Notebook    | [4a5d785f73](https://linux-hardware.org/?probe=4a5d785f73) | Apr 09, 2023 |
| HP            | 245 G6                      | Notebook    | [c6a1e2951c](https://linux-hardware.org/?probe=c6a1e2951c) | Apr 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [078e440a68](https://linux-hardware.org/?probe=078e440a68) | Mar 31, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [1812fe9a19](https://linux-hardware.org/?probe=1812fe9a19) | Mar 26, 2023 |
| Acer          | Aspire A515-43              | Notebook    | [a302d93972](https://linux-hardware.org/?probe=a302d93972) | Mar 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [9e45f992a1](https://linux-hardware.org/?probe=9e45f992a1) | Mar 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [34fd631d2b](https://linux-hardware.org/?probe=34fd631d2b) | Mar 22, 2023 |
| Samsung       | R519/R719                   | Notebook    | [9e1cdf3582](https://linux-hardware.org/?probe=9e1cdf3582) | Mar 17, 2023 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [bdb510861b](https://linux-hardware.org/?probe=bdb510861b) | Mar 16, 2023 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [75a93c0ac6](https://linux-hardware.org/?probe=75a93c0ac6) | Mar 16, 2023 |
| Dell          | 014GRG A01                  | Desktop     | [2e7b556001](https://linux-hardware.org/?probe=2e7b556001) | Mar 05, 2023 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [e828686fc3](https://linux-hardware.org/?probe=e828686fc3) | Mar 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [a84f4dbcbb](https://linux-hardware.org/?probe=a84f4dbcbb) | Feb 28, 2023 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [0cf17a3787](https://linux-hardware.org/?probe=0cf17a3787) | Feb 27, 2023 |
| Dell          | Inspiron 14-3467            | Notebook    | [5bf68a313d](https://linux-hardware.org/?probe=5bf68a313d) | Feb 27, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [72d2220b42](https://linux-hardware.org/?probe=72d2220b42) | Feb 07, 2023 |
| HP            | Setzer                      | Notebook    | [bd65b300ae](https://linux-hardware.org/?probe=bd65b300ae) | Feb 06, 2023 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [85dbbce597](https://linux-hardware.org/?probe=85dbbce597) | Jan 27, 2023 |
| Alienware     | 15 R3                       | Notebook    | [f70ed3a363](https://linux-hardware.org/?probe=f70ed3a363) | Jan 23, 2023 |
| Samsung       | N102SP/N100SP/N101SP        | Notebook    | [b4d38fb35a](https://linux-hardware.org/?probe=b4d38fb35a) | Jan 18, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a15e06403a](https://linux-hardware.org/?probe=a15e06403a) | Jan 15, 2023 |
| Gateway       | NV55C                       | Notebook    | [b8ae4adfdc](https://linux-hardware.org/?probe=b8ae4adfdc) | Jan 12, 2023 |
| Lenovo        | 300e 2nd Gen 81M9           | Convertible | [d36b6385d2](https://linux-hardware.org/?probe=d36b6385d2) | Jan 11, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [d7abd06e34](https://linux-hardware.org/?probe=d7abd06e34) | Jan 08, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [aa67834a96](https://linux-hardware.org/?probe=aa67834a96) | Jan 08, 2023 |
| HP            | ENVY 15                     | Notebook    | [e91c6321b3](https://linux-hardware.org/?probe=e91c6321b3) | Jan 04, 2023 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [93adad7445](https://linux-hardware.org/?probe=93adad7445) | Dec 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [cf4ba78c7d](https://linux-hardware.org/?probe=cf4ba78c7d) | Dec 24, 2022 |
| Unknown       | OA Q-ONE BRAND_V2.0         | Notebook    | [e554aa3d11](https://linux-hardware.org/?probe=e554aa3d11) | Dec 24, 2022 |
| Dell          | 00V62H A01                  | Desktop     | [296edfbde5](https://linux-hardware.org/?probe=296edfbde5) | Dec 22, 2022 |
| Dynabook      | PORTEGE X40-J               | Notebook    | [3f1fc426b0](https://linux-hardware.org/?probe=3f1fc426b0) | Dec 05, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [21d31ce6b0](https://linux-hardware.org/?probe=21d31ce6b0) | Nov 15, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [554f0e2130](https://linux-hardware.org/?probe=554f0e2130) | Oct 30, 2022 |
| HP            | EliteBook x360 1040 G6      | Convertible | [197c77e88c](https://linux-hardware.org/?probe=197c77e88c) | Oct 30, 2022 |
| HP            | EliteBook x360 1040 G6      | Convertible | [12e08a7d27](https://linux-hardware.org/?probe=12e08a7d27) | Oct 30, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [345683b134](https://linux-hardware.org/?probe=345683b134) | Oct 29, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [304a013939](https://linux-hardware.org/?probe=304a013939) | Oct 27, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [a782c95632](https://linux-hardware.org/?probe=a782c95632) | Oct 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [14830504a7](https://linux-hardware.org/?probe=14830504a7) | Oct 22, 2022 |
| Gateway       | NV510P                      | Notebook    | [13fe5a5e78](https://linux-hardware.org/?probe=13fe5a5e78) | Oct 16, 2022 |
| Gateway       | NV510P                      | Notebook    | [7cb93d25ac](https://linux-hardware.org/?probe=7cb93d25ac) | Oct 16, 2022 |
| Gigabyte      | H410M H                     | Desktop     | [71a25274d7](https://linux-hardware.org/?probe=71a25274d7) | Oct 16, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [32d74cab14](https://linux-hardware.org/?probe=32d74cab14) | Oct 10, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [abbdbe7e68](https://linux-hardware.org/?probe=abbdbe7e68) | Oct 10, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [7664f462d0](https://linux-hardware.org/?probe=7664f462d0) | Oct 09, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [ea7b836323](https://linux-hardware.org/?probe=ea7b836323) | Oct 08, 2022 |
| Lenovo        | ZHAOYANG E53-80 81CM        | Notebook    | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [c62874f456](https://linux-hardware.org/?probe=c62874f456) | Oct 04, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9386d6b529](https://linux-hardware.org/?probe=9386d6b529) | Sep 23, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [3ba944192e](https://linux-hardware.org/?probe=3ba944192e) | Sep 22, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [7299d75966](https://linux-hardware.org/?probe=7299d75966) | Sep 22, 2022 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [6b528465e2](https://linux-hardware.org/?probe=6b528465e2) | Sep 20, 2022 |
| HP            | 8768 A                      | Desktop     | [dd63bfb225](https://linux-hardware.org/?probe=dd63bfb225) | Sep 16, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [fbe2b37462](https://linux-hardware.org/?probe=fbe2b37462) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f3dcbfead7](https://linux-hardware.org/?probe=f3dcbfead7) | Sep 02, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [1f0f793a37](https://linux-hardware.org/?probe=1f0f793a37) | Sep 02, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [0bd08aee88](https://linux-hardware.org/?probe=0bd08aee88) | Aug 24, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [c084ff3123](https://linux-hardware.org/?probe=c084ff3123) | Aug 22, 2022 |
| HP            | Notebook                    | Notebook    | [487cfc16fc](https://linux-hardware.org/?probe=487cfc16fc) | Aug 10, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2d464fc182](https://linux-hardware.org/?probe=2d464fc182) | Aug 10, 2022 |
| Dell          | Inspiron 7472               | Notebook    | [eaab7f2460](https://linux-hardware.org/?probe=eaab7f2460) | Aug 09, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [2f628ea3bb](https://linux-hardware.org/?probe=2f628ea3bb) | Aug 09, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | Notebook    | [aed42791cd](https://linux-hardware.org/?probe=aed42791cd) | Aug 09, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3817e724ac](https://linux-hardware.org/?probe=3817e724ac) | Aug 08, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [2f565b89db](https://linux-hardware.org/?probe=2f565b89db) | Aug 06, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [f6caa753ba](https://linux-hardware.org/?probe=f6caa753ba) | Aug 04, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [6d42baa166](https://linux-hardware.org/?probe=6d42baa166) | Jul 26, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [1a2403b95a](https://linux-hardware.org/?probe=1a2403b95a) | Jul 24, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [63722e3660](https://linux-hardware.org/?probe=63722e3660) | Jul 23, 2022 |
| Dell          | Latitude 5520               | Notebook    | [6e9be54f47](https://linux-hardware.org/?probe=6e9be54f47) | Jul 09, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [bb42e29bbb](https://linux-hardware.org/?probe=bb42e29bbb) | Jun 28, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [570dd2f164](https://linux-hardware.org/?probe=570dd2f164) | Jun 28, 2022 |
| Google        | Delbin                      | Notebook    | [26becdfc83](https://linux-hardware.org/?probe=26becdfc83) | Jun 26, 2022 |
| ASUSTek       | X555QG                      | Notebook    | [53e208736b](https://linux-hardware.org/?probe=53e208736b) | Jun 25, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [05c977bf65](https://linux-hardware.org/?probe=05c977bf65) | Jun 22, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [c434320a62](https://linux-hardware.org/?probe=c434320a62) | Jun 19, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [ff0b730eed](https://linux-hardware.org/?probe=ff0b730eed) | Jun 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [edb1f4bda1](https://linux-hardware.org/?probe=edb1f4bda1) | Jun 14, 2022 |
| ASUSTek       | X411UN                      | Notebook    | [70d24e4237](https://linux-hardware.org/?probe=70d24e4237) | Jun 02, 2022 |
| ASUSTek       | UX360CA                     | Notebook    | [63fac2dc9b](https://linux-hardware.org/?probe=63fac2dc9b) | May 29, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [0aa77d107c](https://linux-hardware.org/?probe=0aa77d107c) | May 28, 2022 |
| Alienware     | 15 R3                       | Notebook    | [84df370117](https://linux-hardware.org/?probe=84df370117) | May 26, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [9e4cd6dab4](https://linux-hardware.org/?probe=9e4cd6dab4) | May 25, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [9f009d836c](https://linux-hardware.org/?probe=9f009d836c) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [be78ab6334](https://linux-hardware.org/?probe=be78ab6334) | May 23, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c21c66647d](https://linux-hardware.org/?probe=c21c66647d) | May 23, 2022 |
| Sony          | SVE14113ELW                 | Notebook    | [647c09a7be](https://linux-hardware.org/?probe=647c09a7be) | May 23, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [206aa9b805](https://linux-hardware.org/?probe=206aa9b805) | May 23, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [ec5867b2f7](https://linux-hardware.org/?probe=ec5867b2f7) | May 17, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [9b06242456](https://linux-hardware.org/?probe=9b06242456) | May 17, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [7f46e36f35](https://linux-hardware.org/?probe=7f46e36f35) | May 14, 2022 |
| Toshiba       | Satellite L45-B             | Notebook    | [81b3317aa8](https://linux-hardware.org/?probe=81b3317aa8) | May 14, 2022 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [9c54929196](https://linux-hardware.org/?probe=9c54929196) | May 11, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [f90e5f669e](https://linux-hardware.org/?probe=f90e5f669e) | May 09, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [0c05fbff9c](https://linux-hardware.org/?probe=0c05fbff9c) | May 07, 2022 |
| Toshiba       | Satellite L50-B             | Notebook    | [e559318a8b](https://linux-hardware.org/?probe=e559318a8b) | May 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [c8d977cf63](https://linux-hardware.org/?probe=c8d977cf63) | May 02, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [150f5a4bd0](https://linux-hardware.org/?probe=150f5a4bd0) | Apr 30, 2022 |
| Biostar       | G41D3C                      | Desktop     | [a6db6a2cdf](https://linux-hardware.org/?probe=a6db6a2cdf) | Apr 27, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [e049bbd414](https://linux-hardware.org/?probe=e049bbd414) | Apr 26, 2022 |
| Biostar       | G41D3C                      | Desktop     | [ac5c2d8b54](https://linux-hardware.org/?probe=ac5c2d8b54) | Apr 23, 2022 |
| Biostar       | G41D3C                      | Desktop     | [6fdf919c55](https://linux-hardware.org/?probe=6fdf919c55) | Apr 23, 2022 |
| HP            | Unknown                     | Notebook    | [0a47967da0](https://linux-hardware.org/?probe=0a47967da0) | Apr 23, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [01c63fa622](https://linux-hardware.org/?probe=01c63fa622) | Apr 22, 2022 |
| HP            | Unknown                     | Notebook    | [fa5bba3e33](https://linux-hardware.org/?probe=fa5bba3e33) | Apr 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [a0ad75fa4b](https://linux-hardware.org/?probe=a0ad75fa4b) | Apr 16, 2022 |
| Foxconn       | Cinema Series FAB           | Desktop     | [1e32228753](https://linux-hardware.org/?probe=1e32228753) | Apr 13, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [89dfde5c28](https://linux-hardware.org/?probe=89dfde5c28) | Apr 11, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [8ea4ee1c50](https://linux-hardware.org/?probe=8ea4ee1c50) | Apr 11, 2022 |
| HP            | Pavilion dv6                | Notebook    | [bacb1d04de](https://linux-hardware.org/?probe=bacb1d04de) | Apr 02, 2022 |
| Google        | Panther                     | Desktop     | [b1af725b7c](https://linux-hardware.org/?probe=b1af725b7c) | Mar 30, 2022 |
| Google        | Panther                     | Desktop     | [98185ea5bc](https://linux-hardware.org/?probe=98185ea5bc) | Mar 30, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [722eee0995](https://linux-hardware.org/?probe=722eee0995) | Mar 30, 2022 |
| Sony          | VPCEG30EL                   | Notebook    | [c19f1a4739](https://linux-hardware.org/?probe=c19f1a4739) | Mar 26, 2022 |
| Sony          | SVE14A25CLB                 | Notebook    | [2e6afba454](https://linux-hardware.org/?probe=2e6afba454) | Mar 25, 2022 |
| ASUSTek       | H81M-A                      | Desktop     | [1c1b20796d](https://linux-hardware.org/?probe=1c1b20796d) | Mar 24, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [a39345cbf9](https://linux-hardware.org/?probe=a39345cbf9) | Mar 22, 2022 |
| Dell          | Inspiron 7547               | Notebook    | [af0de64399](https://linux-hardware.org/?probe=af0de64399) | Mar 22, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [1ef1ffe2a3](https://linux-hardware.org/?probe=1ef1ffe2a3) | Mar 20, 2022 |
| Razer         | Blade Stealth               | Notebook    | [6b524f20d4](https://linux-hardware.org/?probe=6b524f20d4) | Mar 20, 2022 |
| TPV-INVENT... | 2AF2 A01                    | Desktop     | [1ab476e992](https://linux-hardware.org/?probe=1ab476e992) | Mar 18, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [faae36d70e](https://linux-hardware.org/?probe=faae36d70e) | Mar 17, 2022 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [4d5aa250a1](https://linux-hardware.org/?probe=4d5aa250a1) | Mar 17, 2022 |
| TrekStor      | Primebook C13               | Convertible | [2c908202fc](https://linux-hardware.org/?probe=2c908202fc) | Mar 17, 2022 |
| Toshiba       | Satellite C55D-A            | Notebook    | [fccc5b2ef5](https://linux-hardware.org/?probe=fccc5b2ef5) | Mar 16, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [c27fb51c94](https://linux-hardware.org/?probe=c27fb51c94) | Mar 13, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [15b0517729](https://linux-hardware.org/?probe=15b0517729) | Mar 13, 2022 |
| Biostar       | G31-M7 TE                   | Desktop     | [f08be29479](https://linux-hardware.org/?probe=f08be29479) | Mar 12, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [d9e67c0484](https://linux-hardware.org/?probe=d9e67c0484) | Mar 12, 2022 |
| HP            | EliteBook Folio 9470m       | Notebook    | [bd4f7daadb](https://linux-hardware.org/?probe=bd4f7daadb) | Mar 10, 2022 |
| Compal        | PBL2021                     | Notebook    | [4e367db737](https://linux-hardware.org/?probe=4e367db737) | Feb 28, 2022 |
| Intel         | H81                         | Desktop     | [a62759e3c8](https://linux-hardware.org/?probe=a62759e3c8) | Feb 27, 2022 |
| Intel         | H81                         | Desktop     | [d1f816774f](https://linux-hardware.org/?probe=d1f816774f) | Feb 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [14f2fcb8be](https://linux-hardware.org/?probe=14f2fcb8be) | Feb 16, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [b5ee6e292d](https://linux-hardware.org/?probe=b5ee6e292d) | Feb 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4cabeb69e3](https://linux-hardware.org/?probe=4cabeb69e3) | Feb 04, 2022 |
| Dell          | G5 5587                     | Notebook    | [5f51492976](https://linux-hardware.org/?probe=5f51492976) | Jan 29, 2022 |
| Dell          | Latitude 7280               | Notebook    | [fdf5a41dcc](https://linux-hardware.org/?probe=fdf5a41dcc) | Jan 25, 2022 |
| Dell          | Latitude 7280               | Notebook    | [b4c6f2fe35](https://linux-hardware.org/?probe=b4c6f2fe35) | Jan 25, 2022 |
| Dell          | Inspiron 3442               | Notebook    | [d8fc419747](https://linux-hardware.org/?probe=d8fc419747) | Jan 18, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [2f9b9ff8ee](https://linux-hardware.org/?probe=2f9b9ff8ee) | Jan 13, 2022 |
| Biostar       | H61MGV3                     | Desktop     | [332b6e1f8a](https://linux-hardware.org/?probe=332b6e1f8a) | Jan 12, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ddd3544bcf](https://linux-hardware.org/?probe=ddd3544bcf) | Jan 08, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [fbd40dba79](https://linux-hardware.org/?probe=fbd40dba79) | Dec 31, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9f2ba12e1f](https://linux-hardware.org/?probe=9f2ba12e1f) | Dec 31, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [82281b42b0](https://linux-hardware.org/?probe=82281b42b0) | Dec 29, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [359493a8bf](https://linux-hardware.org/?probe=359493a8bf) | Dec 27, 2021 |
| Biostar       | A68N-2100                   | Desktop     | [81f4a18209](https://linux-hardware.org/?probe=81f4a18209) | Dec 26, 2021 |
| Acer          | Aspire A515-56              | Notebook    | [54cb3818f3](https://linux-hardware.org/?probe=54cb3818f3) | Dec 20, 2021 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [aea3d82ee8](https://linux-hardware.org/?probe=aea3d82ee8) | Dec 15, 2021 |
| Intel         | DG41RQ AAE54511-205         | Desktop     | [d84eb83569](https://linux-hardware.org/?probe=d84eb83569) | Dec 08, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | Notebook    | [ef48db912e](https://linux-hardware.org/?probe=ef48db912e) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [c30cc4860b](https://linux-hardware.org/?probe=c30cc4860b) | Nov 24, 2021 |
| ASUSTek       | G750JX                      | Notebook    | [f503f26e28](https://linux-hardware.org/?probe=f503f26e28) | Nov 23, 2021 |
| ASUSTek       | H81M-A                      | Desktop     | [c7762271da](https://linux-hardware.org/?probe=c7762271da) | Nov 18, 2021 |
| Google        | Treeya                      | Notebook    | [a0ab206cd8](https://linux-hardware.org/?probe=a0ab206cd8) | Nov 09, 2021 |
| Dell          | Inspiron MP061              | Notebook    | [d6ed71bc78](https://linux-hardware.org/?probe=d6ed71bc78) | Nov 02, 2021 |
| HP            | G42                         | Notebook    | [5ee39658a8](https://linux-hardware.org/?probe=5ee39658a8) | Oct 28, 2021 |
| Timi          | RedmiBook 14-APCS           | Notebook    | [d31c8b483c](https://linux-hardware.org/?probe=d31c8b483c) | Oct 28, 2021 |
| HP            | G42                         | Notebook    | [a8181c9c9b](https://linux-hardware.org/?probe=a8181c9c9b) | Oct 24, 2021 |
| Gigabyte      | H310M H x.x                 | Desktop     | [419e0c7eb2](https://linux-hardware.org/?probe=419e0c7eb2) | Oct 21, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [b5d6c0ae9c](https://linux-hardware.org/?probe=b5d6c0ae9c) | Oct 20, 2021 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [177f79d880](https://linux-hardware.org/?probe=177f79d880) | Oct 18, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [70e96b19b2](https://linux-hardware.org/?probe=70e96b19b2) | Oct 17, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [2297765c40](https://linux-hardware.org/?probe=2297765c40) | Oct 14, 2021 |
| Gigabyte      | H310M H x.x                 | Desktop     | [3fe7cdd0f9](https://linux-hardware.org/?probe=3fe7cdd0f9) | Oct 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [da1bab4a9c](https://linux-hardware.org/?probe=da1bab4a9c) | Oct 13, 2021 |
| HP            | 240 G6 Notebook PC          | Notebook    | [87b00b0a80](https://linux-hardware.org/?probe=87b00b0a80) | Oct 12, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [0de7c95a46](https://linux-hardware.org/?probe=0de7c95a46) | Oct 12, 2021 |
| Acer          | Aspire R5-571TG             | Convertible | [6257ee6ddd](https://linux-hardware.org/?probe=6257ee6ddd) | Oct 07, 2021 |
| Acer          | Aspire R5-571TG             | Convertible | [5972d02719](https://linux-hardware.org/?probe=5972d02719) | Oct 07, 2021 |
| XTRATECH C... | MN-1022X                    | Tablet      | [2307619c77](https://linux-hardware.org/?probe=2307619c77) | Sep 27, 2021 |
| XTRATECH C... | MN-1022X                    | Tablet      | [d4cd8cbc7e](https://linux-hardware.org/?probe=d4cd8cbc7e) | Sep 27, 2021 |
| Foxconn       | H61MXL-K                    | Desktop     | [e776e3f647](https://linux-hardware.org/?probe=e776e3f647) | Sep 08, 2021 |
| ASUSTek       | P7P55D-E                    | Desktop     | [5e208c3927](https://linux-hardware.org/?probe=5e208c3927) | Sep 02, 2021 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [f667f32489](https://linux-hardware.org/?probe=f667f32489) | Aug 31, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [72cddcc75c](https://linux-hardware.org/?probe=72cddcc75c) | Aug 29, 2021 |
| Unknown       | Unknown                     | Notebook    | [449fdc2d2d](https://linux-hardware.org/?probe=449fdc2d2d) | Aug 23, 2021 |
| Unknown       | Unknown                     | Notebook    | [b1587c998f](https://linux-hardware.org/?probe=b1587c998f) | Aug 23, 2021 |
| Gigabyte      | H410M H V2                  | Desktop     | [84faf4af12](https://linux-hardware.org/?probe=84faf4af12) | Aug 22, 2021 |
| Gigabyte      | H410M H V2                  | Desktop     | [5e4047a59c](https://linux-hardware.org/?probe=5e4047a59c) | Aug 22, 2021 |
| Toshiba       | Satellite S55-B             | Notebook    | [c4ec7d25a7](https://linux-hardware.org/?probe=c4ec7d25a7) | Aug 21, 2021 |
| HP            | Pavilion g4                 | Notebook    | [3276092f1e](https://linux-hardware.org/?probe=3276092f1e) | Aug 15, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6909a1a841](https://linux-hardware.org/?probe=6909a1a841) | Aug 14, 2021 |
| Unknown       | Unknown                     | Notebook    | [008647318c](https://linux-hardware.org/?probe=008647318c) | Aug 09, 2021 |
| Unknown       | Unknown                     | Notebook    | [5de2d0ae61](https://linux-hardware.org/?probe=5de2d0ae61) | Aug 09, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [69c078f12b](https://linux-hardware.org/?probe=69c078f12b) | Aug 01, 2021 |
| Acer          | TravelMate X3410-M          | Notebook    | [18b5757039](https://linux-hardware.org/?probe=18b5757039) | Jul 29, 2021 |
| Gigabyte      | H97M-DS3P                   | Desktop     | [c5f1df2581](https://linux-hardware.org/?probe=c5f1df2581) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [33c83a65d8](https://linux-hardware.org/?probe=33c83a65d8) | Jul 24, 2021 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [a071db12c9](https://linux-hardware.org/?probe=a071db12c9) | Jul 12, 2021 |
| Google        | Banjo                       | Notebook    | [d451dcd617](https://linux-hardware.org/?probe=d451dcd617) | Jul 02, 2021 |
| Biostar       | A68N-2100                   | Desktop     | [bffed391bc](https://linux-hardware.org/?probe=bffed391bc) | Jul 02, 2021 |
| Google        | Grunt                       | Notebook    | [2bb0921a94](https://linux-hardware.org/?probe=2bb0921a94) | Jul 01, 2021 |
| Google        | Grunt                       | Notebook    | [4ea5c8f438](https://linux-hardware.org/?probe=4ea5c8f438) | Jul 01, 2021 |
| Pegatron      | 2ACC                        | Desktop     | [271f50a6ed](https://linux-hardware.org/?probe=271f50a6ed) | Jun 29, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [0f90b91804](https://linux-hardware.org/?probe=0f90b91804) | Jun 25, 2021 |
| Google        | Kip                         | Notebook    | [7634152b76](https://linux-hardware.org/?probe=7634152b76) | Jun 21, 2021 |
| Acer          | TravelMate B117-M           | Notebook    | [a5fc625cf2](https://linux-hardware.org/?probe=a5fc625cf2) | Jun 04, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [52fa7c5a31](https://linux-hardware.org/?probe=52fa7c5a31) | May 30, 2021 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [d8be675a5d](https://linux-hardware.org/?probe=d8be675a5d) | May 19, 2021 |
| MSI           | GF63 Thin 9SC               | Notebook    | [54a4075ac5](https://linux-hardware.org/?probe=54a4075ac5) | May 16, 2021 |
| HP            | 1000                        | Notebook    | [d23f6c89ad](https://linux-hardware.org/?probe=d23f6c89ad) | May 15, 2021 |
| HP            | 1000                        | Notebook    | [a1ff0a7b3d](https://linux-hardware.org/?probe=a1ff0a7b3d) | May 13, 2021 |
| Acer          | Aspire V5-121               | Notebook    | [cc73e2b026](https://linux-hardware.org/?probe=cc73e2b026) | May 13, 2021 |
| HP            | 1000                        | Notebook    | [4bbe06ec7a](https://linux-hardware.org/?probe=4bbe06ec7a) | May 13, 2021 |
| Lenovo        | ThinkPad E15 20REA00000     | Notebook    | [1ac42dd429](https://linux-hardware.org/?probe=1ac42dd429) | May 09, 2021 |
| MSI           | GF63 Thin 9SC               | Notebook    | [cd6a799646](https://linux-hardware.org/?probe=cd6a799646) | Apr 29, 2021 |
| ASRock        | B550M-HDV                   | Desktop     | [aaee9d166a](https://linux-hardware.org/?probe=aaee9d166a) | Apr 26, 2021 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [140e992105](https://linux-hardware.org/?probe=140e992105) | Apr 24, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [2a2a56b6d4](https://linux-hardware.org/?probe=2a2a56b6d4) | Apr 22, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [921cfbf363](https://linux-hardware.org/?probe=921cfbf363) | Apr 18, 2021 |
| Gigabyte      | H81M-H                      | Desktop     | [e34aa83281](https://linux-hardware.org/?probe=e34aa83281) | Apr 16, 2021 |
| Dell          | G5 5587                     | Notebook    | [c88e053304](https://linux-hardware.org/?probe=c88e053304) | Apr 07, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [0ba2e43e56](https://linux-hardware.org/?probe=0ba2e43e56) | Mar 24, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [39e97c482d](https://linux-hardware.org/?probe=39e97c482d) | Mar 24, 2021 |
| Lenovo        | ThinkPad T530 2429JB5       | Notebook    | [b3eee9be3e](https://linux-hardware.org/?probe=b3eee9be3e) | Mar 23, 2021 |
| Lenovo        | ThinkPad T530 2429JB5       | Notebook    | [e04914d4de](https://linux-hardware.org/?probe=e04914d4de) | Mar 23, 2021 |
| Intel         | DB75EN AAG39650-302         | Desktop     | [02f80c53ea](https://linux-hardware.org/?probe=02f80c53ea) | Mar 05, 2021 |
| Dell          | Inspiron 1420               | Notebook    | [7b12363b97](https://linux-hardware.org/?probe=7b12363b97) | Mar 04, 2021 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [d5ef689e13](https://linux-hardware.org/?probe=d5ef689e13) | Feb 27, 2021 |
| Dell          | Inspiron 7375               | Notebook    | [eea996c7d4](https://linux-hardware.org/?probe=eea996c7d4) | Feb 26, 2021 |
| Shuttle       | SFM27 V20                   | Desktop     | [14a841b718](https://linux-hardware.org/?probe=14a841b718) | Feb 21, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [35cc521571](https://linux-hardware.org/?probe=35cc521571) | Feb 08, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | Notebook    | [14a1f8c536](https://linux-hardware.org/?probe=14a1f8c536) | Feb 07, 2021 |
| Lenovo        | ThinkPad X201 3680PKS       | Notebook    | [f935adf770](https://linux-hardware.org/?probe=f935adf770) | Feb 07, 2021 |
| Dell          | Vostro 3480                 | Notebook    | [2162db2610](https://linux-hardware.org/?probe=2162db2610) | Feb 03, 2021 |
| Sony          | VPCCW1S1E                   | Notebook    | [f57d56b50e](https://linux-hardware.org/?probe=f57d56b50e) | Jan 31, 2021 |
| Biostar       | G31-M7 TE                   | Desktop     | [c30b6ae115](https://linux-hardware.org/?probe=c30b6ae115) | Jan 24, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [f4e1001265](https://linux-hardware.org/?probe=f4e1001265) | Jan 23, 2021 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [063b008ad5](https://linux-hardware.org/?probe=063b008ad5) | Jan 15, 2021 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [473e0472d5](https://linux-hardware.org/?probe=473e0472d5) | Jan 12, 2021 |
| HP            | EliteBook 2730p             | Notebook    | [5a7277af8b](https://linux-hardware.org/?probe=5a7277af8b) | Jan 08, 2021 |
| HP            | EliteBook 2730p             | Notebook    | [bbbf68f88b](https://linux-hardware.org/?probe=bbbf68f88b) | Jan 08, 2021 |
| Google        | Parrot                      | Notebook    | [a3a6c2f819](https://linux-hardware.org/?probe=a3a6c2f819) | Jan 04, 2021 |
| Google        | Parrot                      | Notebook    | [55b807260c](https://linux-hardware.org/?probe=55b807260c) | Jan 04, 2021 |
| HP            | Pavilion 14                 | Notebook    | [91b047b61a](https://linux-hardware.org/?probe=91b047b61a) | Dec 31, 2020 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [c0e2f63e04](https://linux-hardware.org/?probe=c0e2f63e04) | Dec 20, 2020 |
| Gateway       | NE56R                       | Notebook    | [6988a76879](https://linux-hardware.org/?probe=6988a76879) | Dec 11, 2020 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [3f61162824](https://linux-hardware.org/?probe=3f61162824) | Dec 07, 2020 |
| Dell          | Inspiron 1420               | Notebook    | [e5dab19c0f](https://linux-hardware.org/?probe=e5dab19c0f) | Dec 05, 2020 |
| Intel         | DP55KG AAE47218-404         | Desktop     | [5604be0f67](https://linux-hardware.org/?probe=5604be0f67) | Nov 25, 2020 |
| HP            | ProBook 4440s               | Notebook    | [b4747f87a1](https://linux-hardware.org/?probe=b4747f87a1) | Nov 24, 2020 |
| Dell          | Inspiron 1750               | Notebook    | [612608a41f](https://linux-hardware.org/?probe=612608a41f) | Nov 21, 2020 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [cffed87fd7](https://linux-hardware.org/?probe=cffed87fd7) | Nov 21, 2020 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [1505bb0505](https://linux-hardware.org/?probe=1505bb0505) | Nov 21, 2020 |
| Dell          | Latitude D430               | Notebook    | [77ef794b1d](https://linux-hardware.org/?probe=77ef794b1d) | Nov 21, 2020 |
| Dell          | Latitude D430               | Notebook    | [c028c146b6](https://linux-hardware.org/?probe=c028c146b6) | Nov 21, 2020 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [364a814fd0](https://linux-hardware.org/?probe=364a814fd0) | Nov 19, 2020 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [b0fbbd8176](https://linux-hardware.org/?probe=b0fbbd8176) | Nov 19, 2020 |
| HP            | 3115m                       | Notebook    | [1ae9651614](https://linux-hardware.org/?probe=1ae9651614) | Nov 17, 2020 |
| Gateway       | NE56R                       | Notebook    | [4e9bf51faa](https://linux-hardware.org/?probe=4e9bf51faa) | Nov 16, 2020 |
| ASUSTek       | X510UAR                     | Notebook    | [106453a877](https://linux-hardware.org/?probe=106453a877) | Oct 23, 2020 |
| ASUSTek       | X510UAR                     | Notebook    | [fea6f132fa](https://linux-hardware.org/?probe=fea6f132fa) | Oct 23, 2020 |
| Toshiba       | PORTEGE M805                | Notebook    | [cacfe4abd9](https://linux-hardware.org/?probe=cacfe4abd9) | Oct 22, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [146545f430](https://linux-hardware.org/?probe=146545f430) | Oct 17, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [61e809ea3a](https://linux-hardware.org/?probe=61e809ea3a) | Oct 12, 2020 |
| Toshiba       | Satellite C55-B             | Notebook    | [6353946b7e](https://linux-hardware.org/?probe=6353946b7e) | Oct 12, 2020 |
| Dell          | Inspiron 1420               | Notebook    | [03631f1005](https://linux-hardware.org/?probe=03631f1005) | Oct 08, 2020 |
| Dell          | Inspiron 1420               | Notebook    | [78e7085775](https://linux-hardware.org/?probe=78e7085775) | Oct 08, 2020 |
| MSI           | B75A-G43                    | Desktop     | [fd4f003fa9](https://linux-hardware.org/?probe=fd4f003fa9) | Sep 28, 2020 |
| MSI           | B75A-G43                    | Desktop     | [148c1711fe](https://linux-hardware.org/?probe=148c1711fe) | Sep 28, 2020 |
| Sony          | VGN-CR120E                  | Notebook    | [3e989ff916](https://linux-hardware.org/?probe=3e989ff916) | Sep 24, 2020 |
| Sony          | VGN-CR120E                  | Notebook    | [8569f91c17](https://linux-hardware.org/?probe=8569f91c17) | Sep 23, 2020 |
| ECS           | H61H2-MV                    | Desktop     | [0c5285cd22](https://linux-hardware.org/?probe=0c5285cd22) | Sep 20, 2020 |
| Toshiba       | Satellite C45-A             | Notebook    | [2774da64f6](https://linux-hardware.org/?probe=2774da64f6) | Sep 18, 2020 |
| HP            | Pavilion 15                 | Notebook    | [f824ed9d26](https://linux-hardware.org/?probe=f824ed9d26) | Sep 18, 2020 |
| HP            | Mini 210-1100               | Notebook    | [3b76e02a8f](https://linux-hardware.org/?probe=3b76e02a8f) | Sep 17, 2020 |
| HP            | Pavilion 15                 | Notebook    | [d95e413136](https://linux-hardware.org/?probe=d95e413136) | Sep 16, 2020 |
| HP            | 1497                        | Desktop     | [02645aa87a](https://linux-hardware.org/?probe=02645aa87a) | Sep 15, 2020 |
| Intel         | NUC8BEB J72693-306          | Mini pc     | [40aeea62f1](https://linux-hardware.org/?probe=40aeea62f1) | Sep 13, 2020 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [489cee4d9a](https://linux-hardware.org/?probe=489cee4d9a) | Sep 12, 2020 |
| Toshiba       | Satellite P775              | Notebook    | [d71ccb1065](https://linux-hardware.org/?probe=d71ccb1065) | Sep 10, 2020 |
| HP            | Pavilion dv2500             | Notebook    | [8626b52852](https://linux-hardware.org/?probe=8626b52852) | Sep 08, 2020 |
| Biostar       | P4M90-M7 Ver:1.0            | Desktop     | [cb7ecd71b1](https://linux-hardware.org/?probe=cb7ecd71b1) | Sep 07, 2020 |
| Biostar       | P4M90-M7 Ver:1.0            | Desktop     | [917f5d9bd0](https://linux-hardware.org/?probe=917f5d9bd0) | Sep 07, 2020 |
| Samsung       | 530U4E/540U4E               | Notebook    | [31a023d519](https://linux-hardware.org/?probe=31a023d519) | Sep 06, 2020 |
| Samsung       | 530U4E/540U4E               | Notebook    | [d94a252a6f](https://linux-hardware.org/?probe=d94a252a6f) | Sep 06, 2020 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [c3f5f6d566](https://linux-hardware.org/?probe=c3f5f6d566) | Sep 06, 2020 |
| HP            | Laptop 14-cf3xxx            | Notebook    | [4e0f1689a3](https://linux-hardware.org/?probe=4e0f1689a3) | Sep 06, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [8eb7cfa128](https://linux-hardware.org/?probe=8eb7cfa128) | Sep 05, 2020 |
| HP            | Laptop 14-df0xxx            | Notebook    | [1b11abd994](https://linux-hardware.org/?probe=1b11abd994) | Sep 04, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [21f0c0015c](https://linux-hardware.org/?probe=21f0c0015c) | Aug 26, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [29f01daf9e](https://linux-hardware.org/?probe=29f01daf9e) | Aug 26, 2020 |
| Dell          | Inspiron N4050              | Notebook    | [e39ccc961c](https://linux-hardware.org/?probe=e39ccc961c) | Aug 20, 2020 |
| Lenovo        | ThinkPad P40 Yoga 20GQ00... | Convertible | [1f4ef5bb49](https://linux-hardware.org/?probe=1f4ef5bb49) | Aug 19, 2020 |
| Biostar       | A68N-2100                   | Desktop     | [27b74a4963](https://linux-hardware.org/?probe=27b74a4963) | Aug 16, 2020 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [dd8aa75b79](https://linux-hardware.org/?probe=dd8aa75b79) | Aug 16, 2020 |
| ASUSTek       | X502CA                      | Notebook    | [7876d4c48d](https://linux-hardware.org/?probe=7876d4c48d) | Aug 14, 2020 |
| Gigabyte      | H81M-H                      | Desktop     | [ca4fa8777d](https://linux-hardware.org/?probe=ca4fa8777d) | Aug 10, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [9bcbc98b0f](https://linux-hardware.org/?probe=9bcbc98b0f) | Jul 26, 2020 |
| Lenovo        | IdeaPad 330-14IGM 81D0      | Notebook    | [c32745014a](https://linux-hardware.org/?probe=c32745014a) | Jul 22, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [a70d38c48c](https://linux-hardware.org/?probe=a70d38c48c) | Jul 20, 2020 |
| Acer          | AO722                       | Notebook    | [90943ce018](https://linux-hardware.org/?probe=90943ce018) | Jul 10, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [87be3f63a0](https://linux-hardware.org/?probe=87be3f63a0) | Jul 09, 2020 |
| HP            | ProLiant MicroServer        | Desktop     | [82f2a3732c](https://linux-hardware.org/?probe=82f2a3732c) | Jul 09, 2020 |
| Dell          | Inspiron 7375               | Notebook    | [e4318a8dea](https://linux-hardware.org/?probe=e4318a8dea) | Jul 04, 2020 |
| Dell          | Inspiron 7375               | Notebook    | [ba6d8528e9](https://linux-hardware.org/?probe=ba6d8528e9) | Jul 04, 2020 |
| Biostar       | A68N-2100                   | Desktop     | [07e923d97c](https://linux-hardware.org/?probe=07e923d97c) | Jul 04, 2020 |
| HP            | Notebook                    | Notebook    | [b646ab05a7](https://linux-hardware.org/?probe=b646ab05a7) | Jun 30, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [0a4363a1ba](https://linux-hardware.org/?probe=0a4363a1ba) | Jun 28, 2020 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [853f76e35e](https://linux-hardware.org/?probe=853f76e35e) | Jun 23, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [56a67b5ddc](https://linux-hardware.org/?probe=56a67b5ddc) | Jun 22, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [b8b588701d](https://linux-hardware.org/?probe=b8b588701d) | Jun 22, 2020 |
| Lenovo        | 3000 V200 076433G           | Notebook    | [3d55960409](https://linux-hardware.org/?probe=3d55960409) | Jun 13, 2020 |
| Lenovo        | 3000 V200 076433G           | Notebook    | [1de1a4dbc4](https://linux-hardware.org/?probe=1de1a4dbc4) | Jun 13, 2020 |
| ASRock        | H61M-VS                     | Desktop     | [87788ef1c8](https://linux-hardware.org/?probe=87788ef1c8) | Jun 11, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [87e6d2f056](https://linux-hardware.org/?probe=87e6d2f056) | May 30, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [7332f612bc](https://linux-hardware.org/?probe=7332f612bc) | May 30, 2020 |
| HP            | ProBook 4440s               | Notebook    | [5442b989be](https://linux-hardware.org/?probe=5442b989be) | May 30, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [15c3385fcd](https://linux-hardware.org/?probe=15c3385fcd) | May 30, 2020 |
| Biostar       | H81MLV3                     | Desktop     | [d912bc8bdc](https://linux-hardware.org/?probe=d912bc8bdc) | May 12, 2020 |
| Biostar       | G31-M7 TE                   | Desktop     | [21283d29b3](https://linux-hardware.org/?probe=21283d29b3) | May 10, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [84339f57da](https://linux-hardware.org/?probe=84339f57da) | May 09, 2020 |
| Foxconn       | H61MXE/-S/-V/-K             | Desktop     | [f43cc5765b](https://linux-hardware.org/?probe=f43cc5765b) | Apr 25, 2020 |
| Apple         | MacBookPro13,3              | Notebook    | [81946cb76f](https://linux-hardware.org/?probe=81946cb76f) | Apr 17, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [df8a7bcad8](https://linux-hardware.org/?probe=df8a7bcad8) | Mar 26, 2020 |
| Lenovo        | G710 20252                  | Notebook    | [2971fd6031](https://linux-hardware.org/?probe=2971fd6031) | Mar 26, 2020 |
| HP            | 15                          | Notebook    | [cb0cf73a5d](https://linux-hardware.org/?probe=cb0cf73a5d) | Mar 04, 2020 |
| HP            | 15                          | Notebook    | [687592ff11](https://linux-hardware.org/?probe=687592ff11) | Mar 04, 2020 |
| Acer          | AO722                       | Notebook    | [08d71a347b](https://linux-hardware.org/?probe=08d71a347b) | Feb 29, 2020 |
| Acer          | AO722                       | Notebook    | [291cea2763](https://linux-hardware.org/?probe=291cea2763) | Feb 29, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [108b4a03ac](https://linux-hardware.org/?probe=108b4a03ac) | Feb 26, 2020 |
| ASUSTek       | UX303LA                     | Notebook    | [5ae0871de5](https://linux-hardware.org/?probe=5ae0871de5) | Feb 23, 2020 |
| ASUSTek       | UX303LA                     | Notebook    | [cfc85f91d5](https://linux-hardware.org/?probe=cfc85f91d5) | Feb 22, 2020 |
| ASUSTek       | UX303LA                     | Notebook    | [ab03f678e6](https://linux-hardware.org/?probe=ab03f678e6) | Feb 22, 2020 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [b37b6efdf7](https://linux-hardware.org/?probe=b37b6efdf7) | Feb 18, 2020 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [f8c6ef3229](https://linux-hardware.org/?probe=f8c6ef3229) | Feb 17, 2020 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [0893b14338](https://linux-hardware.org/?probe=0893b14338) | Feb 17, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [d2b7a56172](https://linux-hardware.org/?probe=d2b7a56172) | Jan 14, 2020 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [30baa09d89](https://linux-hardware.org/?probe=30baa09d89) | Jan 14, 2020 |
| Acer          | Aspire ES1-131              | Notebook    | [fcb74db0f2](https://linux-hardware.org/?probe=fcb74db0f2) | Jan 14, 2020 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [ca1baf42c2](https://linux-hardware.org/?probe=ca1baf42c2) | Dec 18, 2019 |
| Intel         | DH61WW AAG23116-203         | Desktop     | [b3270b7077](https://linux-hardware.org/?probe=b3270b7077) | Dec 05, 2019 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [5097027e46](https://linux-hardware.org/?probe=5097027e46) | Dec 05, 2019 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [3fc475bd40](https://linux-hardware.org/?probe=3fc475bd40) | Dec 05, 2019 |
| HP            | Laptop 14-bs0xx             | Notebook    | [bd6b795d81](https://linux-hardware.org/?probe=bd6b795d81) | Nov 09, 2019 |
| Dell          | System XPS L502X            | Notebook    | [d43cf2a533](https://linux-hardware.org/?probe=d43cf2a533) | Sep 12, 2019 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [a4264e7371](https://linux-hardware.org/?probe=a4264e7371) | Sep 12, 2019 |
| HP            | 18E7                        | Desktop     | [2d2bb51f61](https://linux-hardware.org/?probe=2d2bb51f61) | Aug 27, 2019 |
| Toshiba       | Satellite E45t-B            | Notebook    | [156d965d57](https://linux-hardware.org/?probe=156d965d57) | Aug 14, 2019 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [29c5995612](https://linux-hardware.org/?probe=29c5995612) | Jul 29, 2019 |
| Toshiba       | Satellite P55W-C            | Notebook    | [cc12571867](https://linux-hardware.org/?probe=cc12571867) | Jul 27, 2019 |
| HP            | Laptop 15-da0xxx            | Notebook    | [76dbbe880b](https://linux-hardware.org/?probe=76dbbe880b) | Jul 10, 2019 |
| HP            | Pavilion 14                 | Notebook    | [6dde2ab979](https://linux-hardware.org/?probe=6dde2ab979) | Jun 08, 2019 |
| Apple         | MacBook1,1                  | Notebook    | [57ca5e1449](https://linux-hardware.org/?probe=57ca5e1449) | Jun 02, 2019 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [a4d0b9a0cc](https://linux-hardware.org/?probe=a4d0b9a0cc) | May 27, 2019 |
| Dell          | 0CRH6C A02                  | Desktop     | [9bfbd0c2f6](https://linux-hardware.org/?probe=9bfbd0c2f6) | May 16, 2019 |
| Intel         | DZ68DB AAG27985-101         | Desktop     | [ebe6dcff50](https://linux-hardware.org/?probe=ebe6dcff50) | May 05, 2019 |
| Intel         | DZ68DB AAG27985-101         | Desktop     | [2d6ea0b597](https://linux-hardware.org/?probe=2d6ea0b597) | May 05, 2019 |
| HP            | Pavilion Laptop 15-cc1xx    | Notebook    | [6abf9ea94e](https://linux-hardware.org/?probe=6abf9ea94e) | Apr 17, 2019 |
| HP            | ENVY Notebook               | Notebook    | [4d812e744e](https://linux-hardware.org/?probe=4d812e744e) | Apr 17, 2019 |
| Cartimex      | H61H2-MV                    | Desktop     | [aa36029d7f](https://linux-hardware.org/?probe=aa36029d7f) | Apr 09, 2019 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [d857fd97fd](https://linux-hardware.org/?probe=d857fd97fd) | Mar 11, 2019 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [4b50a9d6a2](https://linux-hardware.org/?probe=4b50a9d6a2) | Jan 08, 2019 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [91f58fec26](https://linux-hardware.org/?probe=91f58fec26) | Jan 08, 2019 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Ecuador/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 40        | 10.9%   |
| Ubuntu 22.04                 | 22        | 5.99%   |
| Ubuntu 18.04                 | 22        | 5.99%   |
| Debian 11                    | 11        | 3%      |
| OpenMandriva 4.3             | 9         | 2.45%   |
| Ubuntu 24.04                 | 8         | 2.18%   |
| Linux Mint 20.3              | 8         | 2.18%   |
| Fedora 38                    | 8         | 2.18%   |
| Zorin 17                     | 7         | 1.91%   |
| Linux Mint 21.1              | 7         | 1.91%   |
| Debian 12                    | 7         | 1.91%   |
| Zorin 16                     | 6         | 1.63%   |
| KDE neon 20.04               | 6         | 1.63%   |
| openSUSE Tumbleweed-XXXXXXXX | 5         | 1.36%   |
| Linux Mint 19.3              | 5         | 1.36%   |
| Fedora 36                    | 5         | 1.36%   |
| Fedora 34                    | 5         | 1.36%   |
| Arch Rolling                 | 5         | 1.36%   |
| Zorin 15                     | 4         | 1.09%   |
| Ubuntu 23.10                 | 4         | 1.09%   |
| Pop!_OS 21.10                | 4         | 1.09%   |
| Pop!_OS 21.04                | 4         | 1.09%   |
| OpenMandriva 4.2             | 4         | 1.09%   |
| OpenMandriva 23.03           | 4         | 1.09%   |
| LMDE 4                       | 4         | 1.09%   |
| Fedora 37                    | 4         | 1.09%   |
| Fedora 33                    | 4         | 1.09%   |
| Ubuntu 22.10                 | 3         | 0.82%   |
| Ubuntu 21.10                 | 3         | 0.82%   |
| Pop!_OS 22.04                | 3         | 0.82%   |
| Pop!_OS 20.04                | 3         | 0.82%   |
| OpenMandriva 23.01           | 3         | 0.82%   |
| LMDE 5                       | 3         | 0.82%   |
| Linux Mint 21.3              | 3         | 0.82%   |
| Linux Mint 21.2              | 3         | 0.82%   |
| Linux Mint 20.1              | 3         | 0.82%   |
| Kubuntu 22.04                | 3         | 0.82%   |
| Garuda Linux Soaring         | 3         | 0.82%   |
| Fedora 39                    | 3         | 0.82%   |
| Elementary 5.1.7             | 3         | 0.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 108       | 30.34%  |
| Linux Mint    | 36        | 10.11%  |
| Fedora        | 36        | 10.11%  |
| OpenMandriva  | 27        | 7.58%   |
| Debian        | 22        | 6.18%   |
| Zorin         | 17        | 4.78%   |
| Pop!_OS       | 14        | 3.93%   |
| Manjaro       | 8         | 2.25%   |
| KDE neon      | 8         | 2.25%   |
| Arch          | 8         | 2.25%   |
| Lubuntu       | 7         | 1.97%   |
| LMDE          | 7         | 1.97%   |
| Xubuntu       | 6         | 1.69%   |
| openSUSE      | 6         | 1.69%   |
| Elementary    | 6         | 1.69%   |
| Kubuntu       | 4         | 1.12%   |
| Kali          | 4         | 1.12%   |
| Ubuntu MATE   | 3         | 0.84%   |
| Garuda Linux  | 3         | 0.84%   |
| CentOS        | 3         | 0.84%   |
| ArcoLinux     | 3         | 0.84%   |
| Ubuntu Budgie | 2         | 0.56%   |
| SteamOS       | 2         | 0.56%   |
| Endless       | 2         | 0.56%   |
| EndeavourOS   | 2         | 0.56%   |
| Clear Linux   | 2         | 0.56%   |
| BlackPanther  | 2         | 0.56%   |
| Xero          | 1         | 0.28%   |
| Void Linux    | 1         | 0.28%   |
| ROSA          | 1         | 0.28%   |
| RHEL          | 1         | 0.28%   |
| Peppermint    | 1         | 0.28%   |
| Parrot        | 1         | 0.28%   |
| Nobara        | 1         | 0.28%   |
| Deepin        | 1         | 0.28%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 8         | 2.04%   |
| 5.4.0-54-generic         | 6         | 1.53%   |
| 5.4.0-42-generic         | 5         | 1.27%   |
| 5.15.0-56-generic        | 5         | 1.27%   |
| 5.13.0-35-generic        | 5         | 1.27%   |
| 6.8.0-31-generic         | 4         | 1.02%   |
| 6.5.0-35-generic         | 4         | 1.02%   |
| 5.4.0-45-generic         | 4         | 1.02%   |
| 5.15.0-33-generic        | 4         | 1.02%   |
| 5.10.14-desktop-1omv4002 | 4         | 1.02%   |
| 6.5.0-41-generic         | 3         | 0.76%   |
| 6.2.6-desktop-1omv2390   | 3         | 0.76%   |
| 6.1.1-desktop-1omv2290   | 3         | 0.76%   |
| 6.1.0-13-amd64           | 3         | 0.76%   |
| 5.8.0-41-generic         | 3         | 0.76%   |
| 5.4.0-7634-generic       | 3         | 0.76%   |
| 5.4.0-58-generic         | 3         | 0.76%   |
| 5.4.0-56-generic         | 3         | 0.76%   |
| 5.4.0-48-generic         | 3         | 0.76%   |
| 5.4.0-37-generic         | 3         | 0.76%   |
| 5.4.0-26-generic         | 3         | 0.76%   |
| 5.16.11-76051611-generic | 3         | 0.76%   |
| 5.13.0-7614-generic      | 3         | 0.76%   |
| 5.0.0-37-generic         | 3         | 0.76%   |
| 5.0.0-23-generic         | 3         | 0.76%   |
| 6.9.3-76060903-generic   | 2         | 0.51%   |
| 6.8.0-47-generic         | 2         | 0.51%   |
| 6.6.2-desktop-1omv2390   | 2         | 0.51%   |
| 6.5.0-26-generic         | 2         | 0.51%   |
| 6.5.0-14-generic         | 2         | 0.51%   |
| 6.2.9-300.fc38.x86_64    | 2         | 0.51%   |
| 6.2.15-300.fc38.x86_64   | 2         | 0.51%   |
| 6.2.0-33-generic         | 2         | 0.51%   |
| 6.10.0-desktop-1omv2490  | 2         | 0.51%   |
| 6.1.0-9-amd64            | 2         | 0.51%   |
| 6.1.0-21-amd64           | 2         | 0.51%   |
| 5.8.0-50-generic         | 2         | 0.51%   |
| 5.8.0-43-generic         | 2         | 0.51%   |
| 5.8.0-14-generic         | 2         | 0.51%   |
| 5.4.0-77-generic         | 2         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 57        | 15.24%  |
| 5.15.0  | 32        | 8.56%   |
| 6.5.0   | 21        | 5.61%   |
| 5.13.0  | 19        | 5.08%   |
| 4.15.0  | 18        | 4.81%   |
| 6.8.0   | 12        | 3.21%   |
| 5.8.0   | 12        | 3.21%   |
| 6.1.0   | 11        | 2.94%   |
| 5.16.7  | 9         | 2.41%   |
| 5.11.0  | 9         | 2.41%   |
| 5.10.0  | 9         | 2.41%   |
| 5.0.0   | 9         | 2.41%   |
| 5.19.0  | 7         | 1.87%   |
| 5.3.0   | 6         | 1.6%    |
| 6.2.0   | 5         | 1.34%   |
| 5.10.14 | 4         | 1.07%   |
| 6.2.6   | 3         | 0.8%    |
| 6.1.1   | 3         | 0.8%    |
| 5.17.5  | 3         | 0.8%    |
| 5.16.11 | 3         | 0.8%    |
| 4.19.0  | 3         | 0.8%    |
| 4.18.0  | 3         | 0.8%    |
| 3.10.0  | 3         | 0.8%    |
| 6.9.3   | 2         | 0.53%   |
| 6.8.5   | 2         | 0.53%   |
| 6.7.5   | 2         | 0.53%   |
| 6.6.2   | 2         | 0.53%   |
| 6.5.9   | 2         | 0.53%   |
| 6.4.10  | 2         | 0.53%   |
| 6.3.5   | 2         | 0.53%   |
| 6.2.9   | 2         | 0.53%   |
| 6.2.2   | 2         | 0.53%   |
| 6.2.15  | 2         | 0.53%   |
| 6.10.0  | 2         | 0.53%   |
| 5.16.13 | 2         | 0.53%   |
| 5.16.0  | 2         | 0.53%   |
| 5.15.59 | 2         | 0.53%   |
| 5.11.16 | 2         | 0.53%   |
| 4.18.16 | 2         | 0.53%   |
| 6.8.11  | 1         | 0.27%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 60        | 16.3%   |
| 5.15    | 39        | 10.6%   |
| 6.5     | 26        | 7.07%   |
| 5.13    | 20        | 5.43%   |
| 5.10    | 20        | 5.43%   |
| 4.15    | 18        | 4.89%   |
| 6.1     | 17        | 4.62%   |
| 5.16    | 17        | 4.62%   |
| 6.2     | 16        | 4.35%   |
| 6.8     | 15        | 4.08%   |
| 5.8     | 14        | 3.8%    |
| 5.19    | 12        | 3.26%   |
| 5.11    | 12        | 3.26%   |
| 5.0     | 10        | 2.72%   |
| 5.3     | 8         | 2.17%   |
| 6.10    | 7         | 1.9%    |
| 6.4     | 6         | 1.63%   |
| 5.17    | 6         | 1.63%   |
| 4.18    | 5         | 1.36%   |
| 6.6     | 4         | 1.09%   |
| 6.0     | 4         | 1.09%   |
| 5.18    | 4         | 1.09%   |
| 6.7     | 3         | 0.82%   |
| 6.11    | 3         | 0.82%   |
| 5.7     | 3         | 0.82%   |
| 5.14    | 3         | 0.82%   |
| 4.19    | 3         | 0.82%   |
| 3.10    | 3         | 0.82%   |
| 6.9     | 2         | 0.54%   |
| 6.3     | 2         | 0.54%   |
| 5.5     | 2         | 0.54%   |
| 5.12    | 2         | 0.54%   |
| 5.9     | 1         | 0.27%   |
| 4.9     | 1         | 0.27%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 321       | 96.11%  |
| i686    | 12        | 3.59%   |
| aarch64 | 1         | 0.3%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 157       | 44.99%  |
| KDE5       | 56        | 16.05%  |
| Unknown    | 34        | 9.74%   |
| X-Cinnamon | 32        | 9.17%   |
| XFCE       | 24        | 6.88%   |
| MATE       | 11        | 3.15%   |
| Pantheon   | 6         | 1.72%   |
| LXQt       | 6         | 1.72%   |
| LXDE       | 6         | 1.72%   |
| KDE        | 6         | 1.72%   |
| qtile      | 2         | 0.57%   |
| KDE6       | 2         | 0.57%   |
| Deepin     | 2         | 0.57%   |
| Budgie     | 2         | 0.57%   |
| jwm        | 1         | 0.29%   |
| ICEWM      | 1         | 0.29%   |
| Cinnamon   | 1         | 0.29%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 251       | 72.33%  |
| Wayland | 81        | 23.34%  |
| Unknown | 14        | 4.03%   |
| Tty     | 1         | 0.29%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 176       | 49.72%  |
| SDDM    | 55        | 15.54%  |
| GDM3    | 48        | 13.56%  |
| GDM     | 38        | 10.73%  |
| LightDM | 32        | 9.04%   |
| TDM     | 5         | 1.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| es_EC   | 156       | 45.22%  |
| en_US   | 93        | 26.96%  |
| es_ES   | 34        | 9.86%   |
| Unknown | 21        | 6.09%   |
| es_MX   | 12        | 3.48%   |
| es_CO   | 6         | 1.74%   |
| C       | 6         | 1.74%   |
| de_DE   | 4         | 1.16%   |
| es_US   | 3         | 0.87%   |
| es_PE   | 3         | 0.87%   |
| ru_RU   | 2         | 0.58%   |
| fr_FR   | 2         | 0.58%   |
| en_GB   | 2         | 0.58%   |
| en_AG   | 1         | 0.29%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 173       | 50.29%  |
| BIOS | 171       | 49.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 242       | 69.94%  |
| Btrfs   | 42        | 12.14%  |
| Overlay | 31        | 8.96%   |
| Tmpfs   | 16        | 4.62%   |
| Xfs     | 8         | 2.31%   |
| Unknown | 4         | 1.16%   |
| Zfs     | 2         | 0.58%   |
| Ext2    | 1         | 0.29%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 182       | 52.91%  |
| GPT     | 129       | 37.5%   |
| MBR     | 33        | 9.59%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 293       | 86.18%  |
| Yes       | 47        | 13.82%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 234       | 68.22%  |
| Yes       | 109       | 31.78%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 61        | 18.26%  |
| ASUSTek Computer      | 51        | 15.27%  |
| Lenovo                | 40        | 11.98%  |
| Dell                  | 40        | 11.98%  |
| Toshiba               | 16        | 4.79%   |
| Gigabyte Technology   | 15        | 4.49%   |
| Acer                  | 14        | 4.19%   |
| Intel                 | 12        | 3.59%   |
| Apple                 | 11        | 3.29%   |
| Biostar               | 10        | 2.99%   |
| Google                | 8         | 2.4%    |
| MSI                   | 7         | 2.1%    |
| Sony                  | 6         | 1.8%    |
| ASRock                | 6         | 1.8%    |
| Unknown               | 5         | 1.5%    |
| Samsung Electronics   | 4         | 1.2%    |
| Gateway               | 3         | 0.9%    |
| Foxconn               | 3         | 0.9%    |
| Valve                 | 2         | 0.6%    |
| Razer                 | 2         | 0.6%    |
| Pegatron              | 2         | 0.6%    |
| ECS                   | 2         | 0.6%    |
| Alienware             | 2         | 0.6%    |
| XTRATECH COMPUTERS SA | 1         | 0.3%    |
| TrekStor              | 1         | 0.3%    |
| TPV-INVENTA           | 1         | 0.3%    |
| Timi                  | 1         | 0.3%    |
| Shuttle               | 1         | 0.3%    |
| HUAWEI                | 1         | 0.3%    |
| Fujitsu               | 1         | 0.3%    |
| Dynabook              | 1         | 0.3%    |
| Compal                | 1         | 0.3%    |
| Chuwi                 | 1         | 0.3%    |
| Cartimex              | 1         | 0.3%    |
| AMI                   | 1         | 0.3%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 7         | 2.1%    |
| HP Notebook                              | 4         | 1.2%    |
| ASUS All Series                          | 4         | 1.2%    |
| HP Pavilion Laptop 15-cw1xxx             | 3         | 0.9%    |
| HP Pavilion g4                           | 3         | 0.9%    |
| ASUS PRIME A320M-A                       | 3         | 0.9%    |
| Apple MacBookPro9,2                      | 3         | 0.9%    |
| Apple MacBookPro12,1                     | 3         | 0.9%    |
| Valve Jupiter                            | 2         | 0.6%    |
| Toshiba Satellite S55-B                  | 2         | 0.6%    |
| Toshiba Satellite C55-B                  | 2         | 0.6%    |
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 2         | 0.6%    |
| Lenovo IdeaPad 330S-15IKB 81F5           | 2         | 0.6%    |
| Lenovo IdeaPad 320-15ABR 80XS            | 2         | 0.6%    |
| HP ProBook 4440s                         | 2         | 0.6%    |
| HP Pavilion Laptop 15-cw0xxx             | 2         | 0.6%    |
| HP Laptop 15-da0xxx                      | 2         | 0.6%    |
| HP 1000                                  | 2         | 0.6%    |
| Gigabyte H81M-H                          | 2         | 0.6%    |
| Dell Vostro 3480                         | 2         | 0.6%    |
| Dell OptiPlex 9020                       | 2         | 0.6%    |
| Dell Latitude E6420                      | 2         | 0.6%    |
| Dell Inspiron N4050                      | 2         | 0.6%    |
| Dell Inspiron 5570                       | 2         | 0.6%    |
| Dell Inspiron 3442                       | 2         | 0.6%    |
| Dell Inspiron 1420                       | 2         | 0.6%    |
| Dell G5 5587                             | 2         | 0.6%    |
| Biostar H61MGV3                          | 2         | 0.6%    |
| Biostar G31-M7 TE                        | 2         | 0.6%    |
| ASUS VivoBook_ASUSLaptop X1605VA_X1605VA | 2         | 0.6%    |
| ASUS E202SA                              | 2         | 0.6%    |
| ASUS ASUS TUF Gaming A15 FA506II_FA506II | 2         | 0.6%    |
| XTRATECH COMPUTERS SA MN-1022X           | 1         | 0.3%    |
| TrekStor Primebook C13                   | 1         | 0.3%    |
| TPV-INVENTA 2AF2 A01                     | 1         | 0.3%    |
| Toshiba Satellite S55-A                  | 1         | 0.3%    |
| Toshiba Satellite P855                   | 1         | 0.3%    |
| Toshiba Satellite P775                   | 1         | 0.3%    |
| Toshiba Satellite P55W-C                 | 1         | 0.3%    |
| Toshiba Satellite L50-B                  | 1         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell Inspiron      | 20        | 5.99%   |
| Lenovo IdeaPad     | 17        | 5.09%   |
| Toshiba Satellite  | 15        | 4.49%   |
| HP Pavilion        | 15        | 4.49%   |
| ASUS VivoBook      | 11        | 3.29%   |
| ASUS PRIME         | 11        | 3.29%   |
| Lenovo ThinkPad    | 9         | 2.69%   |
| HP Laptop          | 9         | 2.69%   |
| Acer Aspire        | 9         | 2.69%   |
| Dell Latitude      | 8         | 2.4%    |
| Unknown            | 7         | 2.1%    |
| HP ENVY            | 6         | 1.8%    |
| HP Notebook        | 4         | 1.2%    |
| ASUS All           | 4         | 1.2%    |
| HP ProBook         | 3         | 0.9%    |
| HP EliteBook       | 3         | 0.9%    |
| Dell Vostro        | 3         | 0.9%    |
| Dell OptiPlex      | 3         | 0.9%    |
| ASUS TUF           | 3         | 0.9%    |
| Apple MacBookPro9  | 3         | 0.9%    |
| Apple MacBookPro12 | 3         | 0.9%    |
| Valve Jupiter      | 2         | 0.6%    |
| Razer Blade        | 2         | 0.6%    |
| MSI Stealth        | 2         | 0.6%    |
| Lenovo Yoga        | 2         | 0.6%    |
| Lenovo ThinkBook   | 2         | 0.6%    |
| Intel DH61BF       | 2         | 0.6%    |
| HP OMEN            | 2         | 0.6%    |
| HP 245             | 2         | 0.6%    |
| HP 15              | 2         | 0.6%    |
| HP 1000            | 2         | 0.6%    |
| Gigabyte H81M-H    | 2         | 0.6%    |
| Gigabyte H410M     | 2         | 0.6%    |
| Dell G5            | 2         | 0.6%    |
| Biostar H61MGV3    | 2         | 0.6%    |
| Biostar G31-M7     | 2         | 0.6%    |
| ASUS ROG           | 2         | 0.6%    |
| ASUS E202SA        | 2         | 0.6%    |
| ASUS ASUS          | 2         | 0.6%    |
| Acer TravelMate    | 2         | 0.6%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 31        | 9.28%   |
| 2018    | 31        | 9.28%   |
| 2019    | 30        | 8.98%   |
| 2013    | 28        | 8.38%   |
| 2012    | 28        | 8.38%   |
| 2017    | 26        | 7.78%   |
| 2021    | 25        | 7.49%   |
| 2011    | 21        | 6.29%   |
| 2014    | 20        | 5.99%   |
| 2015    | 18        | 5.39%   |
| 2016    | 15        | 4.49%   |
| 2022    | 14        | 4.19%   |
| 2009    | 11        | 3.29%   |
| 2007    | 11        | 3.29%   |
| 2010    | 10        | 2.99%   |
| 2008    | 5         | 1.5%    |
| 2023    | 4         | 1.2%    |
| 2006    | 3         | 0.9%    |
| 2024    | 1         | 0.3%    |
| 2005    | 1         | 0.3%    |
| Unknown | 1         | 0.3%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 224       | 67.07%  |
| Desktop        | 90        | 26.95%  |
| Convertible    | 14        | 4.19%   |
| Mini pc        | 2         | 0.6%    |
| All in one     | 2         | 0.6%    |
| System on chip | 1         | 0.3%    |
| Tablet         | 1         | 0.3%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 316       | 93.77%  |
| Enabled  | 21        | 6.23%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 325       | 97.31%  |
| Yes  | 9         | 2.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 100       | 29.07%  |
| 8.01-16.0   | 69        | 20.06%  |
| 3.01-4.0    | 66        | 19.19%  |
| 16.01-24.0  | 51        | 14.83%  |
| 32.01-64.0  | 20        | 5.81%   |
| 1.01-2.0    | 20        | 5.81%   |
| 24.01-32.0  | 9         | 2.62%   |
| 2.01-3.0    | 4         | 1.16%   |
| 64.01-256.0 | 4         | 1.16%   |
| 0.51-1.0    | 1         | 0.29%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 106       | 28.57%  |
| 2.01-3.0   | 103       | 27.76%  |
| 4.01-8.0   | 68        | 18.33%  |
| 3.01-4.0   | 62        | 16.71%  |
| 8.01-16.0  | 13        | 3.5%    |
| 0.51-1.0   | 13        | 3.5%    |
| 0.01-0.5   | 5         | 1.35%   |
| 24.01-32.0 | 1         | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 233       | 68.13%  |
| 2      | 87        | 25.44%  |
| 3      | 17        | 4.97%   |
| 5      | 2         | 0.58%   |
| 4      | 2         | 0.58%   |
| 6      | 1         | 0.29%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 220       | 65.09%  |
| Yes       | 118       | 34.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 275       | 82.34%  |
| No        | 59        | 17.66%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 272       | 80.95%  |
| No        | 64        | 19.05%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 216       | 64.29%  |
| No        | 120       | 35.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Ecuador | 334       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Quito                          | 137       | 39.71%  |
| Guayaquil                      | 97        | 28.12%  |
| Cuenca                         | 30        | 8.7%    |
| Loja                           | 11        | 3.19%   |
| Manta                          | 7         | 2.03%   |
| Ambato                         | 6         | 1.74%   |
| Riobamba                       | 5         | 1.45%   |
| Santo Domingo de los Colorados | 4         | 1.16%   |
| Portoviejo                     | 4         | 1.16%   |
| Machala                        | 4         | 1.16%   |
| Hacienda Ibarra                | 4         | 1.16%   |
| Puyo                           | 3         | 0.87%   |
| Latacunga                      | 3         | 0.87%   |
| Otavalo                        | 2         | 0.58%   |
| Ibarra                         | 2         | 0.58%   |
| Cotacachi                      | 2         | 0.58%   |
| Ayacucho                       | 2         | 0.58%   |
| Vinces                         | 1         | 0.29%   |
| Uyumbicho                      | 1         | 0.29%   |
| Samborondon                    | 1         | 0.29%   |
| Quevedo                        | 1         | 0.29%   |
| Provincia del Chimborazo       | 1         | 0.29%   |
| Nueva Loja                     | 1         | 0.29%   |
| Montecristi                    | 1         | 0.29%   |
| Las Pinas                      | 1         | 0.29%   |
| La Troncal                     | 1         | 0.29%   |
| La Providencia                 | 1         | 0.29%   |
| La Mana                        | 1         | 0.29%   |
| La Concordia Numero Uno        | 1         | 0.29%   |
| Huaquillas                     | 1         | 0.29%   |
| Hacienda San Sebastian         | 1         | 0.29%   |
| Hacienda La Libertad           | 1         | 0.29%   |
| Guanujo                        | 1         | 0.29%   |
| Guamani                        | 1         | 0.29%   |
| Febres Cordero                 | 1         | 0.29%   |
| Cayambe                        | 1         | 0.29%   |
| Cariamanga                     | 1         | 0.29%   |
| Babahoyo                       | 1         | 0.29%   |
| Azogues                        | 1         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 90        | 124    | 20.36%  |
| Seagate                     | 57        | 83     | 12.9%   |
| Toshiba                     | 55        | 65     | 12.44%  |
| Kingston                    | 40        | 61     | 9.05%   |
| Samsung Electronics         | 33        | 37     | 7.47%   |
| Hitachi                     | 18        | 21     | 4.07%   |
| Unknown                     | 17        | 26     | 3.85%   |
| A-DATA Technology           | 14        | 19     | 3.17%   |
| SK hynix                    | 12        | 14     | 2.71%   |
| SanDisk                     | 10        | 14     | 2.26%   |
| Hewlett-Packard             | 9         | 10     | 2.04%   |
| Micron Technology           | 8         | 8      | 1.81%   |
| Kingston Technology Company | 8         | 10     | 1.81%   |
| HGST                        | 8         | 10     | 1.81%   |
| Intel                       | 7         | 14     | 1.58%   |
| Apple                       | 6         | 7      | 1.36%   |
| KIOXIA                      | 5         | 6      | 1.13%   |
| JMicron Technology          | 5         | 5      | 1.13%   |
| PNY                         | 3         | 3      | 0.68%   |
| Gigabyte Technology         | 3         | 3      | 0.68%   |
| Fujitsu                     | 3         | 3      | 0.68%   |
| Crucial                     | 3         | 3      | 0.68%   |
| SPCC                        | 2         | 2      | 0.45%   |
| Phison Electronics          | 2         | 2      | 0.45%   |
| Unknown                     | 2         | 2      | 0.45%   |
| USB3.0                      | 1         | 1      | 0.23%   |
| Union Memory (Shenzhen)     | 1         | 1      | 0.23%   |
| UMIS                        | 1         | 1      | 0.23%   |
| SABRENT                     | 1         | 1      | 0.23%   |
| Realtek Semiconductor       | 1         | 1      | 0.23%   |
| Phison                      | 1         | 1      | 0.23%   |
| Patriot                     | 1         | 1      | 0.23%   |
| OWC                         | 1         | 1      | 0.23%   |
| Netac                       | 1         | 1      | 0.23%   |
| Micron/Crucial Technology   | 1         | 1      | 0.23%   |
| Micro Center                | 1         | 1      | 0.23%   |
| Maxtor                      | 1         | 1      | 0.23%   |
| LITEON                      | 1         | 1      | 0.23%   |
| Lite-On                     | 1         | 1      | 0.23%   |
| KINGPAN                     | 1         | 1      | 0.23%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD  | 15        | 3.17%   |
| Toshiba MQ04ABF100 1TB           | 8         | 1.69%   |
| Seagate ST500DM002-1BD142 500GB  | 7         | 1.48%   |
| Seagate ST1000LM035-1RK172 1TB   | 7         | 1.48%   |
| Toshiba MQ01ABF050 500GB         | 6         | 1.27%   |
| Kingston SA400S37480G 480GB SSD  | 6         | 1.27%   |
| WDC WDS480G2G0A-00JH30 480GB SSD | 5         | 1.06%   |
| WDC WDS240G2G0A-00JH30 240GB SSD | 5         | 1.06%   |
| Toshiba DT01ACA100 1TB           | 5         | 1.06%   |
| HP SSD S700 500GB                | 5         | 1.06%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 4         | 0.85%   |
| WDC WD10SPZX-24Z10 1TB           | 4         | 0.85%   |
| WDC WD10EZEX-08WN4A0 1TB         | 4         | 0.85%   |
| Unknown MMC Card  64GB           | 4         | 0.85%   |
| Unknown MMC Card  16GB           | 4         | 0.85%   |
| Seagate ST2000LM007-1R8174 2TB   | 4         | 0.85%   |
| Kingston SNVS500G 500GB          | 4         | 0.85%   |
| Kingston SA400S37960G 960GB SSD  | 4         | 0.85%   |
| WDC WD10EZEX-00BN5A0 1TB         | 3         | 0.63%   |
| Unknown MMC Card  32GB           | 3         | 0.63%   |
| Toshiba MQ01ABD100 1TB           | 3         | 0.63%   |
| Toshiba MQ01ABD075 752GB         | 3         | 0.63%   |
| Toshiba DT01ACA200 2TB           | 3         | 0.63%   |
| Seagate ST1000DM010-2EP102 1TB   | 3         | 0.63%   |
| SanDisk NVMe SSD Drive 1TB       | 3         | 0.63%   |
| Samsung HD502HJ 500GB            | 3         | 0.63%   |
| Micron 3400_MTFDKBA1T0TFH 1TB    | 3         | 0.63%   |
| Kingston Company SNV2S2000G 2TB  | 3         | 0.63%   |
| Kingston SV300S37A60G 64GB SSD   | 3         | 0.63%   |
| JMicron Tech 250GB               | 3         | 0.63%   |
| Hitachi HDS721050CLA660 500GB    | 3         | 0.63%   |
| HGST HTS541010A9E680 1TB         | 3         | 0.63%   |
| A-DATA SU650 120GB SSD           | 3         | 0.63%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD | 2         | 0.42%   |
| WDC WDS100T2B0A-00SM50 1TB SSD   | 2         | 0.42%   |
| WDC WD6400BEVT-22A0RT0 640GB     | 2         | 0.42%   |
| WDC WD5000LPVX-22V0TT0 500GB     | 2         | 0.42%   |
| WDC WD40EFAX-68JH4N1 4TB         | 2         | 0.42%   |
| WDC WD1600BEVT-22ZCT0 160GB      | 2         | 0.42%   |
| WDC WD10SPZX-60Z10T0 1TB         | 2         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 64        | 93     | 29.09%  |
| Seagate             | 57        | 83     | 25.91%  |
| Toshiba             | 50        | 59     | 22.73%  |
| Hitachi             | 18        | 21     | 8.18%   |
| Samsung Electronics | 12        | 14     | 5.45%   |
| HGST                | 8         | 10     | 3.64%   |
| Fujitsu             | 3         | 3      | 1.36%   |
| Unknown             | 2         | 4      | 0.91%   |
| JMicron Technology  | 2         | 2      | 0.91%   |
| SABRENT             | 1         | 1      | 0.45%   |
| Maxtor              | 1         | 1      | 0.45%   |
| HPE                 | 1         | 1      | 0.45%   |
| Apple               | 1         | 1      | 0.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 32        | 43     | 27.83%  |
| WDC                 | 22        | 24     | 19.13%  |
| A-DATA Technology   | 12        | 16     | 10.43%  |
| Hewlett-Packard     | 8         | 9      | 6.96%   |
| SanDisk             | 5         | 5      | 4.35%   |
| Samsung Electronics | 5         | 5      | 4.35%   |
| Apple               | 4         | 5      | 3.48%   |
| Toshiba             | 3         | 4      | 2.61%   |
| PNY                 | 3         | 3      | 2.61%   |
| Crucial             | 3         | 3      | 2.61%   |
| SPCC                | 2         | 2      | 1.74%   |
| SK hynix            | 2         | 2      | 1.74%   |
| Intel               | 2         | 2      | 1.74%   |
| Gigabyte Technology | 2         | 2      | 1.74%   |
| USB3.0              | 1         | 1      | 0.87%   |
| Patriot             | 1         | 1      | 0.87%   |
| OWC                 | 1         | 1      | 0.87%   |
| Netac               | 1         | 1      | 0.87%   |
| Micron Technology   | 1         | 1      | 0.87%   |
| Micro Center        | 1         | 1      | 0.87%   |
| LITEON              | 1         | 1      | 0.87%   |
| KINGPAN             | 1         | 1      | 0.87%   |
| HS-SSD-E100N        | 1         | 1      | 0.87%   |
| Golden              | 1         | 1      | 0.87%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 197       | 293    | 48.17%  |
| SSD     | 105       | 135    | 25.67%  |
| NVMe    | 86        | 118    | 21.03%  |
| MMC     | 15        | 23     | 3.67%   |
| Unknown | 6         | 6      | 1.47%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 266       | 413    | 69.82%  |
| NVMe | 86        | 118    | 22.57%  |
| MMC  | 15        | 23     | 3.94%   |
| SAS  | 14        | 21     | 3.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 180       | 242    | 57.32%  |
| 0.51-1.0   | 108       | 150    | 34.39%  |
| 1.01-2.0   | 21        | 27     | 6.69%   |
| 3.01-4.0   | 3         | 6      | 0.96%   |
| 2.01-3.0   | 2         | 3      | 0.64%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 89        | 24.86%  |
| 101-250        | 82        | 22.91%  |
| 501-1000       | 57        | 15.92%  |
| 1001-2000      | 39        | 10.89%  |
| 1-20           | 28        | 7.82%   |
| 51-100         | 22        | 6.15%   |
| 21-50          | 17        | 4.75%   |
| More than 3000 | 12        | 3.35%   |
| Unknown        | 9         | 2.51%   |
| 2001-3000      | 3         | 0.84%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 129       | 35.15%  |
| 21-50          | 73        | 19.89%  |
| 101-250        | 54        | 14.71%  |
| 51-100         | 37        | 10.08%  |
| 251-500        | 33        | 8.99%   |
| 501-1000       | 18        | 4.9%    |
| 1001-2000      | 9         | 2.45%   |
| Unknown        | 9         | 2.45%   |
| More than 3000 | 3         | 0.82%   |
| 2001-3000      | 2         | 0.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                   | Computers | Drives | Percent |
|-----------------------------------------|-----------|--------|---------|
| Hitachi HDS721050CLA660 500GB           | 3         | 3      | 6.98%   |
| WDC WD6400BEVT-22A0RT0 640GB            | 2         | 2      | 4.65%   |
| WDC WD10EZEX-00BN5A0 1TB                | 2         | 2      | 4.65%   |
| Toshiba MQ01ABF050 500GB                | 2         | 3      | 4.65%   |
| Seagate ST500DM002-1BD142 500GB         | 2         | 3      | 4.65%   |
| WDC WD5000LPVT-00G33T0 500GB            | 1         | 1      | 2.33%   |
| WDC WD5000LPCX-24VHAT0 500GB            | 1         | 2      | 2.33%   |
| WDC WD5000AAKX-00ERMA0 500GB            | 1         | 1      | 2.33%   |
| WDC WD3200AAKS-00L9A0 320GB             | 1         | 1      | 2.33%   |
| WDC WD1200BEVS-22UST0 120GB             | 1         | 1      | 2.33%   |
| WDC WD10EZEX-60ZF5A0 1TB                | 1         | 1      | 2.33%   |
| WDC WD10EZEX-00WN4A0 1TB                | 1         | 1      | 2.33%   |
| Toshiba MQ01ABD100M 1TB                 | 1         | 1      | 2.33%   |
| Toshiba MQ01ABD100 1TB                  | 1         | 1      | 2.33%   |
| Toshiba MQ01ABD075 752GB                | 1         | 1      | 2.33%   |
| Toshiba MK7559GSXP 752GB                | 1         | 1      | 2.33%   |
| Toshiba MK3265GSXN 320GB                | 1         | 1      | 2.33%   |
| Toshiba MK3259GSXP 320GB                | 1         | 1      | 2.33%   |
| Toshiba MK2561GSYN 250GB                | 1         | 2      | 2.33%   |
| Toshiba DT01ACA300 3TB                  | 1         | 2      | 2.33%   |
| Seagate ST3750330AS 752GB               | 1         | 1      | 2.33%   |
| Seagate ST3500630AS 500GB               | 1         | 1      | 2.33%   |
| Seagate ST31000333AS 1TB                | 1         | 2      | 2.33%   |
| Seagate ST2000DL003-9VT166 2TB          | 1         | 1      | 2.33%   |
| Seagate ST1000LX015-1U7172 1TB          | 1         | 3      | 2.33%   |
| Seagate ST1000LM035-1RK172 1TB          | 1         | 1      | 2.33%   |
| Seagate ST1000DM010-2EP102 1TB          | 1         | 2      | 2.33%   |
| Samsung Electronics HD501LJ 500GB       | 1         | 1      | 2.33%   |
| Samsung Electronics HD322HJ 320GB       | 1         | 1      | 2.33%   |
| Kingston SNS4151S316GD 16GB SSD         | 1         | 1      | 2.33%   |
| Kingston RBU-SNS8350DES3128GP 128GB SSD | 1         | 1      | 2.33%   |
| HPE MB0500EAMZD 500GB                   | 1         | 1      | 2.33%   |
| Hitachi HTS547550A9E384 500GB           | 1         | 1      | 2.33%   |
| Hitachi HTS543232L9SA00 320GB           | 1         | 1      | 2.33%   |
| HGST HTS545050A7E380 500GB              | 1         | 1      | 2.33%   |
| Fujitsu MHZ2160BH G1 160GB              | 1         | 1      | 2.33%   |
| Fujitsu MHY2250BH 250GB                 | 1         | 1      | 2.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 12     | 23.81%  |
| Toshiba             | 10        | 13     | 23.81%  |
| Seagate             | 9         | 14     | 21.43%  |
| Hitachi             | 5         | 5      | 11.9%   |
| Samsung Electronics | 2         | 2      | 4.76%   |
| Kingston            | 2         | 2      | 4.76%   |
| Fujitsu             | 2         | 2      | 4.76%   |
| HPE                 | 1         | 1      | 2.38%   |
| HGST                | 1         | 1      | 2.38%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 10        | 12     | 25%     |
| Toshiba             | 10        | 13     | 25%     |
| Seagate             | 9         | 14     | 22.5%   |
| Hitachi             | 5         | 5      | 12.5%   |
| Samsung Electronics | 2         | 2      | 5%      |
| Fujitsu             | 2         | 2      | 5%      |
| HPE                 | 1         | 1      | 2.5%    |
| HGST                | 1         | 1      | 2.5%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 50     | 94.44%  |
| SSD  | 2         | 2      | 5.56%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 214       | 366    | 58.63%  |
| Works    | 115       | 157    | 31.51%  |
| Malfunc  | 36        | 52     | 9.86%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 229       | 57.83%  |
| AMD                          | 62        | 15.66%  |
| Samsung Electronics          | 20        | 5.05%   |
| Kingston Technology Company  | 18        | 4.55%   |
| SanDisk                      | 12        | 3.03%   |
| SK hynix                     | 10        | 2.53%   |
| Micron Technology            | 7         | 1.77%   |
| Phison Electronics           | 5         | 1.26%   |
| KIOXIA                       | 5         | 1.26%   |
| Marvell Technology Group     | 4         | 1.01%   |
| Nvidia                       | 3         | 0.76%   |
| JMicron Technology           | 3         | 0.76%   |
| ASMedia Technology           | 3         | 0.76%   |
| VIA Technologies             | 2         | 0.51%   |
| Union Memory (Shenzhen)      | 2         | 0.51%   |
| Toshiba America Info Systems | 2         | 0.51%   |
| ADATA Technology             | 2         | 0.51%   |
| Silicon Motion               | 1         | 0.25%   |
| Realtek Semiconductor        | 1         | 0.25%   |
| Micron/Crucial Technology    | 1         | 0.25%   |
| Lite-On Technology           | 1         | 0.25%   |
| INNOGRIT                     | 1         | 0.25%   |
| Broadcom / LSI               | 1         | 0.25%   |
| Apple                        | 1         | 0.25%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 49        | 11.04%  |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 24        | 5.41%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 21        | 4.73%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 18        | 4.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16        | 3.6%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 12        | 2.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 10        | 2.25%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 9         | 2.03%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 8         | 1.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 8         | 1.8%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 8         | 1.8%    |
| Kingston Company NV2 NVMe SSD [SM2267XT] (DRAM-less)                                    | 7         | 1.58%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 7         | 1.58%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 7         | 1.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6         | 1.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 6         | 1.35%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 6         | 1.35%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6         | 1.35%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6         | 1.35%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 1.13%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 1.13%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 5         | 1.13%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)               | 4         | 0.9%    |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                              | 4         | 0.9%    |
| Kingston Company NV1 NVMe SSD [SM2263XT] (DRAM-less)                                    | 4         | 0.9%    |
| Intel Volume Management Device NVMe RAID Controller Intel Corporation                   | 4         | 0.9%    |
| Intel Tiger Lake-LP SATA Controller                                                     | 4         | 0.9%    |
| Intel SATA Controller [RAID mode]                                                       | 4         | 0.9%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 4         | 0.9%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 4         | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 4         | 0.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 0.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 4         | 0.9%    |
| AMD A320 Chipset SATA Controller [AHCI mode]                                            | 4         | 0.9%    |
| AMD 500 Series Chipset SATA Controller                                                  | 4         | 0.9%    |
| AMD 400 Series Chipset SATA Controller                                                  | 4         | 0.9%    |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 3         | 0.68%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 3         | 0.68%   |
| Samsung S4LN058A01[SSUBX] AHCI SSD Controller (Apple slot)                              | 3         | 0.68%   |
| Micron 3400 NVMe SSD [Hendrix]                                                          | 3         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 234       | 58.35%  |
| NVMe | 86        | 21.45%  |
| RAID | 41        | 10.22%  |
| IDE  | 40        | 9.98%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 256       | 76.65%  |
| AMD    | 77        | 23.05%  |
| ARM    | 1         | 0.3%    |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 11        | 3.29%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 9         | 2.69%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 6         | 1.8%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 6         | 1.8%    |
| Intel Core i7-4510U CPU @ 2.00GHz             | 4         | 1.2%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 1.2%    |
| Intel Core i5-4440 CPU @ 3.10GHz              | 4         | 1.2%    |
| Intel Core i5-3330 CPU @ 3.00GHz              | 4         | 1.2%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 0.9%    |
| Intel Core i7-6600U CPU @ 2.60GHz             | 3         | 0.9%    |
| Intel Core i7-5500U CPU @ 2.40GHz             | 3         | 0.9%    |
| Intel Core i7-3520M CPU @ 2.90GHz             | 3         | 0.9%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 0.9%    |
| Intel Core i5-5257U CPU @ 2.70GHz             | 3         | 0.9%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 0.9%    |
| Intel Core i5-4210U CPU @ 1.70GHz             | 3         | 0.9%    |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 0.9%    |
| Intel Core i3-4005U CPU @ 1.70GHz             | 3         | 0.9%    |
| Intel Core i3-3110M CPU @ 2.40GHz             | 3         | 0.9%    |
| Intel Celeron CPU N3050 @ 1.60GHz             | 3         | 0.9%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 0.9%    |
| AMD Ryzen 5 3600 6-Core Processor             | 3         | 0.9%    |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 3         | 0.9%    |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 3         | 0.9%    |
| AMD Ryzen 3 3250U with Radeon Graphics        | 3         | 0.9%    |
| AMD A6-9225 RADEON R4, 5 COMPUTE CORES 2C+3G  | 3         | 0.9%    |
| Intel Pentium CPU G2030 @ 3.00GHz             | 2         | 0.6%    |
| Intel Pentium CPU G2020 @ 2.90GHz             | 2         | 0.6%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 2         | 0.6%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 2         | 0.6%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.6%    |
| Intel Core i7-7700 CPU @ 3.60GHz              | 2         | 0.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz             | 2         | 0.6%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 2         | 0.6%    |
| Intel Core i7-6700 CPU @ 3.40GHz              | 2         | 0.6%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 0.6%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.6%    |
| Intel Core i7-4700HQ CPU @ 2.40GHz            | 2         | 0.6%    |
| Intel Core i7-10750H CPU @ 2.60GHz            | 2         | 0.6%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 0.6%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 70        | 20.96%  |
| Intel Core i5           | 66        | 19.76%  |
| Intel Core i3           | 30        | 8.98%   |
| AMD Ryzen 5             | 27        | 8.08%   |
| Other                   | 26        | 7.78%   |
| Intel Celeron           | 25        | 7.49%   |
| Intel Core 2 Duo        | 15        | 4.49%   |
| AMD Ryzen 7             | 13        | 3.89%   |
| Intel Pentium           | 10        | 2.99%   |
| Intel Atom              | 7         | 2.1%    |
| AMD Ryzen 3             | 4         | 1.2%    |
| AMD E2                  | 4         | 1.2%    |
| AMD E1                  | 4         | 1.2%    |
| Intel Pentium Dual-Core | 3         | 0.9%    |
| AMD A6                  | 3         | 0.9%    |
| Intel Genuine           | 2         | 0.6%    |
| Intel Core 2 Quad       | 2         | 0.6%    |
| AMD E                   | 2         | 0.6%    |
| AMD Athlon II X2        | 2         | 0.6%    |
| AMD A8                  | 2         | 0.6%    |
| AMD A4                  | 2         | 0.6%    |
| AMD A12                 | 2         | 0.6%    |
| Intel Xeon              | 1         | 0.3%    |
| Intel Pentium Silver    | 1         | 0.3%    |
| Intel Pentium M         | 1         | 0.3%    |
| Intel Core m3           | 1         | 0.3%    |
| Intel Celeron M         | 1         | 0.3%    |
| AMD Ryzen 7 PRO         | 1         | 0.3%    |
| AMD Phenom II X6        | 1         | 0.3%    |
| AMD Phenom II X2        | 1         | 0.3%    |
| AMD FX                  | 1         | 0.3%    |
| AMD C-70                | 1         | 0.3%    |
| AMD C-60                | 1         | 0.3%    |
| AMD Athlon II Neo       | 1         | 0.3%    |
| AMD A10                 | 1         | 0.3%    |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 158       | 47.31%  |
| 4      | 117       | 35.03%  |
| 6      | 27        | 8.08%   |
| 8      | 15        | 4.49%   |
| 1      | 8         | 2.4%    |
| 14     | 5         | 1.5%    |
| 10     | 2         | 0.6%    |
| 24     | 1         | 0.3%    |
| 12     | 1         | 0.3%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 333       | 99.7%   |
| 2      | 1         | 0.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 215       | 64.37%  |
| 1      | 119       | 35.63%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 328       | 98.2%   |
| 32-bit         | 3         | 0.9%    |
| Unknown        | 2         | 0.6%    |
| 64-bit         | 1         | 0.3%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 118       | 34.01%  |
| 0x306a9    | 19        | 5.48%   |
| 0x206a7    | 16        | 4.61%   |
| 0x806ea    | 15        | 4.32%   |
| 0x306c3    | 14        | 4.03%   |
| 0x306d4    | 9         | 2.59%   |
| 0x1067a    | 9         | 2.59%   |
| 0x6fd      | 8         | 2.31%   |
| 0x40651    | 8         | 2.31%   |
| 0x08108109 | 7         | 2.02%   |
| 0xa0653    | 5         | 1.44%   |
| 0x06006705 | 5         | 1.44%   |
| 0x906ed    | 4         | 1.15%   |
| 0x906ea    | 4         | 1.15%   |
| 0x806c1    | 4         | 1.15%   |
| 0x706e5    | 4         | 1.15%   |
| 0x0810100b | 4         | 1.15%   |
| 0x05000119 | 4         | 1.15%   |
| 0x806ec    | 3         | 0.86%   |
| 0x806eb    | 3         | 0.86%   |
| 0x806e9    | 3         | 0.86%   |
| 0x706a1    | 3         | 0.86%   |
| 0x406e3    | 3         | 0.86%   |
| 0x406c4    | 3         | 0.86%   |
| 0x30678    | 3         | 0.86%   |
| 0x106ca    | 3         | 0.86%   |
| 0x08600104 | 3         | 0.86%   |
| 0x06006704 | 3         | 0.86%   |
| 0x0600611a | 3         | 0.86%   |
| 0x010000c8 | 3         | 0.86%   |
| 0x706a8    | 2         | 0.58%   |
| 0x6e8      | 2         | 0.58%   |
| 0x506e3    | 2         | 0.58%   |
| 0x20655    | 2         | 0.58%   |
| 0x106e5    | 2         | 0.58%   |
| 0x0a201005 | 2         | 0.58%   |
| 0x08701021 | 2         | 0.58%   |
| 0x08608104 | 2         | 0.58%   |
| 0x08108102 | 2         | 0.58%   |
| 0x0700010f | 2         | 0.58%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 49        | 14.63%  |
| Haswell          | 34        | 10.15%  |
| IvyBridge        | 31        | 9.25%   |
| SandyBridge      | 20        | 5.97%   |
| Zen+             | 14        | 4.18%   |
| Skylake          | 14        | 4.18%   |
| Unknown          | 14        | 4.18%   |
| Penryn           | 12        | 3.58%   |
| Excavator        | 12        | 3.58%   |
| Core             | 12        | 3.58%   |
| Broadwell        | 12        | 3.58%   |
| Zen 2            | 10        | 2.99%   |
| TigerLake        | 10        | 2.99%   |
| Silvermont       | 10        | 2.99%   |
| CometLake        | 9         | 2.69%   |
| Alderlake Hybrid | 9         | 2.69%   |
| Zen 3            | 7         | 2.09%   |
| Zen              | 7         | 2.09%   |
| IceLake          | 7         | 2.09%   |
| Goldmont plus    | 7         | 2.09%   |
| Bobcat           | 7         | 2.09%   |
| Westmere         | 5         | 1.49%   |
| K10              | 5         | 1.49%   |
| Bonnell          | 5         | 1.49%   |
| P6               | 3         | 0.9%    |
| Nehalem          | 3         | 0.9%    |
| Puma             | 2         | 0.6%    |
| Jaguar           | 2         | 0.6%    |
| Goldmont         | 2         | 0.6%    |
| K10 Llano        | 1         | 0.3%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 227       | 58.81%  |
| AMD              | 90        | 23.32%  |
| Nvidia           | 68        | 17.62%  |
| VIA Technologies | 1         | 0.26%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 19        | 4.76%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 19        | 4.76%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 18        | 4.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 3.76%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 3.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12        | 3.01%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11        | 2.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 9         | 2.26%   |
| Intel HD Graphics 5500                                                                   | 9         | 2.26%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 2.01%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 2.01%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 8         | 2.01%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 7         | 1.75%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 6         | 1.5%    |
| Intel HD Graphics 620                                                                    | 6         | 1.5%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 6         | 1.5%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 1.5%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 6         | 1.5%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 6         | 1.5%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 5         | 1.25%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.25%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.25%   |
| AMD Lucienne                                                                             | 5         | 1.25%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 4         | 1%      |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1%      |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 1%      |
| Intel HD Graphics 630                                                                    | 4         | 1%      |
| Intel HD Graphics 530                                                                    | 4         | 1%      |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 1%      |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 4         | 1%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.75%   |
| Nvidia GT218 [GeForce 210]                                                               | 3         | 0.75%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 0.75%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 3         | 0.75%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 3         | 0.75%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 3         | 0.75%   |
| Intel Iris Plus Graphics G7                                                              | 3         | 0.75%   |
| Intel Iris Graphics 6100                                                                 | 3         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 178       | 52.82%  |
| 1 x AMD                  | 71        | 21.07%  |
| Intel + Nvidia           | 32        | 9.5%    |
| 1 x Nvidia               | 31        | 9.2%    |
| Intel + AMD              | 12        | 3.56%   |
| AMD + Nvidia             | 5         | 1.48%   |
| Other                    | 2         | 0.59%   |
| 2 x Intel                | 2         | 0.59%   |
| 2 x AMD                  | 2         | 0.59%   |
| 1 x VIA                  | 1         | 0.3%    |
| Intel + AMD + 1 x Nvidia | 1         | 0.3%    |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 284       | 83.78%  |
| Proprietary | 42        | 12.39%  |
| Unknown     | 13        | 3.83%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 226       | 64.94%  |
| 1.01-2.0   | 40        | 11.49%  |
| 0.01-0.5   | 39        | 11.21%  |
| 3.01-4.0   | 15        | 4.31%   |
| 0.51-1.0   | 13        | 3.74%   |
| 7.01-8.0   | 6         | 1.72%   |
| 5.01-6.0   | 5         | 1.44%   |
| 8.01-16.0  | 3         | 0.86%   |
| 2.01-3.0   | 1         | 0.29%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Goldstar                | 46        | 12.71%  |
| BOE                     | 46        | 12.71%  |
| AU Optronics            | 45        | 12.43%  |
| Chimei Innolux          | 44        | 12.15%  |
| LG Display              | 35        | 9.67%   |
| Samsung Electronics     | 34        | 9.39%   |
| AOC                     | 14        | 3.87%   |
| Apple                   | 11        | 3.04%   |
| BenQ                    | 10        | 2.76%   |
| Hewlett-Packard         | 9         | 2.49%   |
| Chi Mei Optoelectronics | 8         | 2.21%   |
| Dell                    | 6         | 1.66%   |
| PANDA                   | 4         | 1.1%    |
| LG Electronics          | 4         | 1.1%    |
| Acer                    | 4         | 1.1%    |
| LG Philips              | 3         | 0.83%   |
| InfoVision              | 3         | 0.83%   |
| Valve                   | 2         | 0.55%   |
| Unknown (XXX)           | 2         | 0.55%   |
| Sony                    | 2         | 0.55%   |
| Sharp                   | 2         | 0.55%   |
| Philips                 | 2         | 0.55%   |
| KTC                     | 2         | 0.55%   |
| InnoLux Display         | 2         | 0.55%   |
| ASUSTek Computer        | 2         | 0.55%   |
| ViewSonic               | 1         | 0.28%   |
| Unknown (CEA)           | 1         | 0.28%   |
| Toshiba                 | 1         | 0.28%   |
| TES                     | 1         | 0.28%   |
| TCL                     | 1         | 0.28%   |
| SKY                     | 1         | 0.28%   |
| RTK                     | 1         | 0.28%   |
| NEC Computers           | 1         | 0.28%   |
| MStar                   | 1         | 0.28%   |
| MSI                     | 1         | 0.28%   |
| Lenovo                  | 1         | 0.28%   |
| Huion                   | 1         | 0.28%   |
| HKC                     | 1         | 0.28%   |
| HIC                     | 1         | 0.28%   |
| Gigabyte Technology     | 1         | 0.28%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Goldstar HD GSM5ACD 1366x768 410x230mm 18.5-inch                     | 9         | 2.43%   |
| AOC 2070W AOC2070 1600x900 434x236mm 19.4-inch                       | 5         | 1.35%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                  | 4         | 1.08%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 4         | 1.08%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 4         | 1.08%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch | 3         | 0.81%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 3         | 0.81%   |
| Goldstar W2243 GSM56FE 1920x1080 477x268mm 21.5-inch                 | 3         | 0.81%   |
| Goldstar L192WS GSM4B32 1440x900 410x256mm 19.0-inch                 | 3         | 0.81%   |
| Goldstar 20M35 GSM4EED 1600x900 433x236mm 19.4-inch                  | 3         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15FD 1366x768 344x193mm 15.5-inch      | 3         | 0.81%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 3         | 0.81%   |
| BenQ G2420HDBL BNQ785E 1920x1080 477x268mm 21.5-inch                 | 3         | 0.81%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 3         | 0.81%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch        | 3         | 0.81%   |
| Apple Color LCD APPA029 2560x1600 286x179mm 13.3-inch                | 3         | 0.81%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 2         | 0.54%   |
| Unknown (XXX) Union TV XXX2841 1920x1080 1209x680mm 54.6-inch        | 2         | 0.54%   |
| Samsung Electronics SMB1930N SAM0632 1360x768 410x230mm 18.5-inch    | 2         | 0.54%   |
| Samsung Electronics SA300/SA350 SAM0788 1366x768 410x230mm 18.5-inch | 2         | 0.54%   |
| Samsung Electronics S19C150 SAM0AE6 1366x768 410x230mm 18.5-inch     | 2         | 0.54%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch | 2         | 0.54%   |
| LG Electronics LCD Monitor LG TV 1360x768                            | 2         | 0.54%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch          | 2         | 0.54%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 2         | 0.54%   |
| LG Display LCD Monitor LGD02B2 1366x768 310x174mm 14.0-inch          | 2         | 0.54%   |
| Goldstar IPS WSXGA GSM5B20 1440x900 419x262mm 19.5-inch              | 2         | 0.54%   |
| Goldstar E1942 GSM4C09 1366x768 410x230mm 18.5-inch                  | 2         | 0.54%   |
| Goldstar 20EN33 GSM4EE1 1600x900 443x249mm 20.0-inch                 | 2         | 0.54%   |
| Goldstar 19EN33 GSM4C18 1366x768 410x230mm 18.5-inch                 | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN1618 1920x1200 344x215mm 16.0-inch     | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN15CC 1366x768 344x193mm 15.5-inch      | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN1496 1366x768 309x173mm 13.9-inch      | 2         | 0.54%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 2         | 0.54%   |
| BOE LCD Monitor BOE0A56 1920x1080 344x194mm 15.5-inch                | 2         | 0.54%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                | 2         | 0.54%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 2         | 0.54%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 2         | 0.54%   |
| BOE LCD Monitor BOE06A9 1920x1080 344x193mm 15.5-inch                | 2         | 0.54%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 134       | 38.29%  |
| 1920x1080 (FHD)    | 110       | 31.43%  |
| 1600x900 (HD+)     | 20        | 5.71%   |
| 1280x800 (WXGA)    | 14        | 4%      |
| 3840x2160 (4K)     | 10        | 2.86%   |
| 1440x900 (WXGA+)   | 10        | 2.86%   |
| 1920x1200 (WUXGA)  | 8         | 2.29%   |
| 2560x1600          | 7         | 2%      |
| 1360x768           | 7         | 2%      |
| 1024x768 (XGA)     | 5         | 1.43%   |
| 2560x1440 (QHD)    | 4         | 1.14%   |
| 1280x1024 (SXGA)   | 4         | 1.14%   |
| 1024x600           | 3         | 0.86%   |
| 800x1280           | 2         | 0.57%   |
| 1680x1050 (WSXGA+) | 2         | 0.57%   |
| Unknown            | 2         | 0.57%   |
| 4093x4093          | 1         | 0.29%   |
| 3520x1080          | 1         | 0.29%   |
| 3440x1440          | 1         | 0.29%   |
| 3200x2000          | 1         | 0.29%   |
| 2880x1800          | 1         | 0.29%   |
| 2646x1024          | 1         | 0.29%   |
| 2256x1504          | 1         | 0.29%   |
| 1600x1200          | 1         | 0.29%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 114       | 31.23%  |
| 13      | 47        | 12.88%  |
| 14      | 39        | 10.68%  |
| 18      | 36        | 9.86%   |
| 19      | 23        | 6.3%    |
| 21      | 17        | 4.66%   |
| 23      | 14        | 3.84%   |
| 11      | 12        | 3.29%   |
| 17      | 9         | 2.47%   |
| Unknown | 9         | 2.47%   |
| 12      | 8         | 2.19%   |
| 31      | 5         | 1.37%   |
| 16      | 5         | 1.37%   |
| 24      | 4         | 1.1%    |
| 20      | 4         | 1.1%    |
| 54      | 3         | 0.82%   |
| 32      | 3         | 0.82%   |
| 10      | 3         | 0.82%   |
| 52      | 2         | 0.55%   |
| 27      | 2         | 0.55%   |
| 7       | 2         | 0.55%   |
| 72      | 1         | 0.27%   |
| 40      | 1         | 0.27%   |
| 39      | 1         | 0.27%   |
| 34      | 1         | 0.27%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 183       | 50.97%  |
| 401-500     | 73        | 20.33%  |
| 201-300     | 41        | 11.42%  |
| 501-600     | 19        | 5.29%   |
| 351-400     | 14        | 3.9%    |
| Unknown     | 9         | 2.51%   |
| 601-700     | 6         | 1.67%   |
| 1001-1500   | 5         | 1.39%   |
| 701-800     | 4         | 1.11%   |
| 801-900     | 2         | 0.56%   |
| 1-100       | 2         | 0.56%   |
| 1501-2000   | 1         | 0.28%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 262       | 81.11%  |
| 16/10   | 37        | 11.46%  |
| Unknown | 9         | 2.79%   |
| 4/3     | 7         | 2.17%   |
| 5/4     | 4         | 1.24%   |
| 0.67    | 2         | 0.62%   |
| 3/2     | 1         | 0.31%   |
| 21/9    | 1         | 0.31%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 112       | 30.68%  |
| 81-90          | 76        | 20.82%  |
| 141-150        | 36        | 9.86%   |
| 151-200        | 35        | 9.59%   |
| 201-250        | 27        | 7.4%    |
| 51-60          | 12        | 3.29%   |
| 71-80          | 11        | 3.01%   |
| 351-500        | 9         | 2.47%   |
| Unknown        | 9         | 2.47%   |
| 61-70          | 7         | 1.92%   |
| More than 1000 | 6         | 1.64%   |
| 121-130        | 6         | 1.64%   |
| 111-120        | 6         | 1.64%   |
| 41-50          | 3         | 0.82%   |
| 1-40           | 2         | 0.55%   |
| 301-350        | 2         | 0.55%   |
| 131-140        | 2         | 0.55%   |
| 501-1000       | 2         | 0.55%   |
| 251-300        | 1         | 0.27%   |
| 91-100         | 1         | 0.27%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 122       | 34.27%  |
| 51-100        | 101       | 28.37%  |
| 121-160       | 94        | 26.4%   |
| 161-240       | 20        | 5.62%   |
| Unknown       | 9         | 2.53%   |
| 1-50          | 8         | 2.25%   |
| More than 240 | 2         | 0.56%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 279       | 81.82%  |
| 2     | 51        | 14.96%  |
| 0     | 9         | 2.64%   |
| 3     | 2         | 0.59%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 213       | 42.09%  |
| Intel                           | 110       | 21.74%  |
| Qualcomm Atheros                | 73        | 14.43%  |
| Broadcom                        | 34        | 6.72%   |
| TP-Link                         | 14        | 2.77%   |
| MediaTek                        | 10        | 1.98%   |
| Ralink                          | 9         | 1.78%   |
| Ralink Technology               | 8         | 1.58%   |
| Marvell Technology Group        | 5         | 0.99%   |
| Broadcom Limited                | 5         | 0.99%   |
| Xiaomi                          | 4         | 0.79%   |
| ASIX Electronics                | 4         | 0.79%   |
| Samsung Electronics             | 3         | 0.59%   |
| Qualcomm Atheros Communications | 3         | 0.59%   |
| Nvidia                          | 2         | 0.4%    |
| D-Link System                   | 2         | 0.4%    |
| VIA Technologies                | 1         | 0.2%    |
| TRENDnet                        | 1         | 0.2%    |
| Qualcomm                        | 1         | 0.2%    |
| OPPO Electronics                | 1         | 0.2%    |
| NetGear                         | 1         | 0.2%    |
| Hewlett-Packard                 | 1         | 0.2%    |
| Arduino SA                      | 1         | 0.2%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 121       | 20.75%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 48        | 8.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 18        | 3.09%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 16        | 2.74%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 13        | 2.23%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 11        | 1.89%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 9         | 1.54%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 8         | 1.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 8         | 1.37%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 7         | 1.2%    |
| Realtek RTL8125 2.5GbE Controller                                      | 7         | 1.2%    |
| Intel Wireless 8265 / 8275                                             | 7         | 1.2%    |
| Intel Wireless 3160                                                    | 7         | 1.2%    |
| Intel Wi-Fi 6 AX201                                                    | 7         | 1.2%    |
| Intel Wireless 7260                                                    | 6         | 1.03%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 1.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 0.86%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 5         | 0.86%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 5         | 0.86%   |
| Intel Wi-Fi 6 AX200                                                    | 5         | 0.86%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 4         | 0.69%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 4         | 0.69%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter               | 4         | 0.69%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 4         | 0.69%   |
| Ralink MT7601U Wireless Adapter                                        | 4         | 0.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 4         | 0.69%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 4         | 0.69%   |
| Intel Wireless 7265                                                    | 4         | 0.69%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 0.69%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 0.69%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                            | 4         | 0.69%   |
| Broadcom BCM43142 802.11b/g/n                                          | 4         | 0.69%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 0.69%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 3         | 0.51%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                        | 3         | 0.51%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                             | 3         | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3         | 0.51%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 3         | 0.51%   |
| Qualcomm Atheros AR9271 802.11n                                        | 3         | 0.51%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                       | 3         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 88        | 30.66%  |
| Realtek Semiconductor           | 65        | 22.65%  |
| Qualcomm Atheros                | 60        | 20.91%  |
| Broadcom                        | 27        | 9.41%   |
| TP-Link                         | 13        | 4.53%   |
| Ralink                          | 9         | 3.14%   |
| MediaTek                        | 9         | 3.14%   |
| Ralink Technology               | 8         | 2.79%   |
| Qualcomm Atheros Communications | 3         | 1.05%   |
| Broadcom Limited                | 3         | 1.05%   |
| TRENDnet                        | 1         | 0.35%   |
| NetGear                         | 1         | 0.35%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 18        | 6.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 16        | 5.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 13        | 4.5%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 11        | 3.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 9         | 3.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 8         | 2.77%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 8         | 2.77%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 7         | 2.42%   |
| Intel Wireless 8265 / 8275                                              | 7         | 2.42%   |
| Intel Wireless 3160                                                     | 7         | 2.42%   |
| Intel Wi-Fi 6 AX201                                                     | 7         | 2.42%   |
| Intel Wireless 7260                                                     | 6         | 2.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 5         | 1.73%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.73%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 4         | 1.38%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.38%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 4         | 1.38%   |
| Ralink MT7601U Wireless Adapter                                         | 4         | 1.38%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 4         | 1.38%   |
| Intel Wireless 7265                                                     | 4         | 1.38%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                             | 4         | 1.38%   |
| Broadcom BCM43142 802.11b/g/n                                           | 4         | 1.38%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 1.04%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.04%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                              | 3         | 1.04%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 3         | 1.04%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 3         | 1.04%   |
| Qualcomm Atheros AR9271 802.11n                                         | 3         | 1.04%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 1.04%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 3         | 1.04%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                       | 3         | 1.04%   |
| Intel Wireless 8260                                                     | 3         | 1.04%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 3         | 1.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 3         | 1.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 3         | 1.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.04%   |
| Broadcom BCM4331 802.11a/b/g/n                                          | 3         | 1.04%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                     | 2         | 0.69%   |
| TP-Link 802.11ac WLAN Adapter                                           | 2         | 0.69%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 189       | 66.55%  |
| Intel                    | 37        | 13.03%  |
| Qualcomm Atheros         | 19        | 6.69%   |
| Broadcom                 | 15        | 5.28%   |
| Marvell Technology Group | 5         | 1.76%   |
| Xiaomi                   | 4         | 1.41%   |
| ASIX Electronics         | 4         | 1.41%   |
| Nvidia                   | 2         | 0.7%    |
| D-Link System            | 2         | 0.7%    |
| Broadcom Limited         | 2         | 0.7%    |
| VIA Technologies         | 1         | 0.35%   |
| TP-Link                  | 1         | 0.35%   |
| Qualcomm                 | 1         | 0.35%   |
| OPPO Electronics         | 1         | 0.35%   |
| MediaTek                 | 1         | 0.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 121       | 42.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 48        | 16.67%  |
| Realtek RTL8125 2.5GbE Controller                                      | 7         | 2.43%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 2.08%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 5         | 1.74%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 5         | 1.74%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 4         | 1.39%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 4         | 1.39%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 1.39%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 1.39%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 1.39%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 3         | 1.04%   |
| Intel Ethernet Connection (2) I219-V                                   | 3         | 1.04%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 3         | 1.04%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 3         | 1.04%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 2         | 0.69%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 2         | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.69%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2         | 0.69%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 2         | 0.69%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 2         | 0.69%   |
| Intel I211 Gigabit Network Connection                                  | 2         | 0.69%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.69%   |
| Intel Ethernet Connection (17) I219-V                                  | 2         | 0.69%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                        | 2         | 0.69%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 2         | 0.69%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 2         | 0.69%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 1         | 0.35%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]        | 1         | 0.35%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 1         | 0.35%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller      | 1         | 0.35%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 1         | 0.35%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.35%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.35%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 1         | 0.35%   |
| Qualcomm Airtel 4G                                                     | 1         | 0.35%   |
| OPPO OnePlus Nord 4                                                    | 1         | 0.35%   |
| Nvidia MCP79 Ethernet                                                  | 1         | 0.35%   |
| Nvidia MCP61 Ethernet                                                  | 1         | 0.35%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1         | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 275       | 49.73%  |
| WiFi     | 272       | 49.19%  |
| Modem    | 6         | 1.08%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 207       | 59.31%  |
| Ethernet | 142       | 40.69%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 184       | 54.93%  |
| 1     | 145       | 43.28%  |
| 0     | 4         | 1.19%   |
| 3     | 2         | 0.6%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 277       | 80.99%  |
| Yes  | 65        | 19.01%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 70        | 32.26%  |
| Realtek Semiconductor           | 34        | 15.67%  |
| Qualcomm Atheros Communications | 28        | 12.9%   |
| IMC Networks                    | 14        | 6.45%   |
| Cambridge Silicon Radio         | 13        | 5.99%   |
| Lite-On Technology              | 12        | 5.53%   |
| Foxconn / Hon Hai               | 10        | 4.61%   |
| Broadcom                        | 10        | 4.61%   |
| Apple                           | 9         | 4.15%   |
| Toshiba                         | 3         | 1.38%   |
| Ralink                          | 3         | 1.38%   |
| Ralink Technology               | 2         | 0.92%   |
| Dell                            | 2         | 0.92%   |
| TP-Link                         | 1         | 0.46%   |
| Realtek                         | 1         | 0.46%   |
| Hewlett-Packard                 | 1         | 0.46%   |
| Foxconn International           | 1         | 0.46%   |
| D-Link System                   | 1         | 0.46%   |
| ASUSTek Computer                | 1         | 0.46%   |
| Alps Electric                   | 1         | 0.46%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 30        | 13.82%  |
| Qualcomm Atheros  Bluetooth Device                  | 19        | 8.76%   |
| Realtek  Bluetooth 4.2 Adapter                      | 16        | 7.37%   |
| Intel AX201 Bluetooth                               | 14        | 6.45%   |
| Realtek Bluetooth Radio                             | 13        | 5.99%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 13        | 5.99%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 8         | 3.69%   |
| IMC Networks Bluetooth Radio                        | 8         | 3.69%   |
| Intel AX200 Bluetooth                               | 5         | 2.3%    |
| Foxconn / Hon Hai Bluetooth Device                  | 5         | 2.3%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.84%   |
| Lite-On Wireless_Device                             | 4         | 1.84%   |
| Lite-On Bluetooth Device                            | 4         | 1.84%   |
| Intel AX211 Bluetooth                               | 4         | 1.84%   |
| IMC Networks Wireless_Device                        | 4         | 1.84%   |
| Apple Bluetooth USB Host Controller                 | 4         | 1.84%   |
| Apple Bluetooth Host Controller                     | 4         | 1.84%   |
| Toshiba Bluetooth Device                            | 3         | 1.38%   |
| Realtek RTL8821A Bluetooth                          | 3         | 1.38%   |
| Ralink RT3290 Bluetooth                             | 3         | 1.38%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 3         | 1.38%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 3         | 1.38%   |
| Lite-On Bluetooth Radio                             | 2         | 0.92%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 0.92%   |
| Intel AX210 Bluetooth                               | 2         | 0.92%   |
| Foxconn / Hon Hai Wireless_Device                   | 2         | 0.92%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 2         | 0.92%   |
| Dell DW375 Bluetooth Module                         | 2         | 0.92%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 2         | 0.92%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 2         | 0.92%   |
| TP-Link TP-Link Bluetooth USB Adapter               | 1         | 0.46%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.46%   |
| Realtek 802.11ac WLAN Adapter                       | 1         | 0.46%   |
| Realtek Bluetooth Radio                             | 1         | 0.46%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter        | 1         | 0.46%   |
| Ralink CSR BS8510                                   | 1         | 0.46%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 1         | 0.46%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1         | 0.46%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.46%   |
| Lite-On Atheros AR3012 Bluetooth                    | 1         | 0.46%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Intel               | 253       | 63.73%  |
| AMD                 | 84        | 21.16%  |
| Nvidia              | 48        | 12.09%  |
| Sony                | 2         | 0.5%    |
| VIA Technologies    | 1         | 0.25%   |
| Samson Technologies | 1         | 0.25%   |
| M-Audio             | 1         | 0.25%   |
| Kingston Technology | 1         | 0.25%   |
| GN Netcom           | 1         | 0.25%   |
| Focusrite-Novation  | 1         | 0.25%   |
| Corsair             | 1         | 0.25%   |
| C-Media Electronics | 1         | 0.25%   |
| Audient             | 1         | 0.25%   |
| Apple               | 1         | 0.25%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 39        | 7.71%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 32        | 6.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 26        | 5.14%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 24        | 4.74%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 21        | 4.15%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 19        | 3.75%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 17        | 3.36%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 2.77%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 13        | 2.57%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 13        | 2.57%   |
| Intel 8 Series HD Audio Controller                                                                | 13        | 2.57%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 12        | 2.37%   |
| Intel Broadwell-U Audio Controller                                                                | 12        | 2.37%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 1.98%   |
| AMD FCH Azalia Controller                                                                         | 10        | 1.98%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 10        | 1.98%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 9         | 1.78%   |
| AMD Kabini HDMI/DP Audio                                                                          | 8         | 1.58%   |
| AMD High Definition Audio Controller                                                              | 8         | 1.58%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 7         | 1.38%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 1.38%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 1.38%   |
| Intel Cannon Lake PCH cAVS                                                                        | 7         | 1.38%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 7         | 1.38%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 6         | 1.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 6         | 1.19%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 6         | 1.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 1.19%   |
| Intel 200 Series PCH HD Audio                                                                     | 6         | 1.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 6         | 1.19%   |
| AMD Wrestler HDMI Audio                                                                           | 6         | 1.19%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 5         | 0.99%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 5         | 0.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 0.99%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 0.99%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 5         | 0.99%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 4         | 0.79%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 0.79%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 3         | 0.59%   |
| Nvidia High Definition Audio Controller                                                           | 3         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 56        | 25.81%  |
| Kingston            | 36        | 16.59%  |
| SK hynix            | 35        | 16.13%  |
| Micron Technology   | 23        | 10.6%   |
| Unknown             | 16        | 7.37%   |
| A-DATA Technology   | 10        | 4.61%   |
| Corsair             | 9         | 4.15%   |
| Crucial             | 7         | 3.23%   |
| Ramaxel Technology  | 6         | 2.76%   |
| Avant               | 4         | 1.84%   |
| Nanya Technology    | 3         | 1.38%   |
| Unknown (ABCD)      | 2         | 0.92%   |
| Team                | 2         | 0.92%   |
| Unknown             | 2         | 0.92%   |
| PNY                 | 1         | 0.46%   |
| Hikvision           | 1         | 0.46%   |
| Hewlett-Packard     | 1         | 0.46%   |
| GOODRAM             | 1         | 0.46%   |
| Gold Key            | 1         | 0.46%   |
| Elpida              | 1         | 0.46%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 3.42%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.71%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 1.28%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 3         | 1.28%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 1.28%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 1.28%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 1.28%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 2         | 0.85%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 2         | 0.85%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.85%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 2         | 0.85%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.85%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 0.85%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.85%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.85%   |
| Samsung RAM M471A5244CB0-CWE 4096MB SODIMM DDR4 3200MT/s         | 2         | 0.85%   |
| Samsung RAM M471A2G44BM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.85%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.85%   |
| Ramaxel RAM RMT3020EC58E9F1333 4GB SODIMM DDR3 4199MT/s          | 2         | 0.85%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 2         | 0.85%   |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s             | 2         | 0.85%   |
| Micron RAM 8KTF51264HDZ-1G6E1 4GB SODIMM DDR3 1600MT/s           | 2         | 0.85%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 0.85%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s          | 2         | 0.85%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 0.85%   |
| Kingston RAM 9905744-077.A00G 16GB SODIMM DDR4 3200MT/s          | 2         | 0.85%   |
| Unknown                                                          | 2         | 0.85%   |
| Unknown RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.43%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 0.43%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                       | 1         | 0.43%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.43%   |
| Unknown RAM Module 2GB DIMM DDR3 1333MT/s                        | 1         | 0.43%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.43%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 0.43%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                         | 1         | 0.43%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 1         | 0.43%   |
| Unknown RAM Module 2048MB DIMM DDR2                              | 1         | 0.43%   |
| Unknown RAM Module 1GB SODIMM DDR2 533MT/s                       | 1         | 0.43%   |
| Unknown RAM Module 1GB SODIMM DDR                                | 1         | 0.43%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 93        | 52.54%  |
| DDR3    | 53        | 29.94%  |
| DDR2    | 8         | 4.52%   |
| LPDDR4  | 7         | 3.95%   |
| SDRAM   | 4         | 2.26%   |
| DDR5    | 4         | 2.26%   |
| Unknown | 4         | 2.26%   |
| LPDDR3  | 3         | 1.69%   |
| DDR     | 1         | 0.56%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 121       | 68.75%  |
| DIMM         | 43        | 24.43%  |
| Row Of Chips | 9         | 5.11%   |
| Chip         | 2         | 1.14%   |
| Unknown      | 1         | 0.57%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 69        | 34.67%  |
| 8192  | 65        | 32.66%  |
| 16384 | 33        | 16.58%  |
| 2048  | 20        | 10.05%  |
| 1024  | 7         | 3.52%   |
| 32768 | 5         | 2.51%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 48        | 23.53%  |
| 1600    | 41        | 20.1%   |
| 3200    | 28        | 13.73%  |
| 1333    | 15        | 7.35%   |
| 2400    | 10        | 4.9%    |
| 2133    | 9         | 4.41%   |
| 3266    | 8         | 3.92%   |
| 1334    | 5         | 2.45%   |
| Unknown | 5         | 2.45%   |
| 3733    | 3         | 1.47%   |
| 1867    | 3         | 1.47%   |
| 667     | 3         | 1.47%   |
| 4199    | 2         | 0.98%   |
| 3600    | 2         | 0.98%   |
| 3466    | 2         | 0.98%   |
| 800     | 2         | 0.98%   |
| 8400    | 1         | 0.49%   |
| 6000    | 1         | 0.49%   |
| 5600    | 1         | 0.49%   |
| 5200    | 1         | 0.49%   |
| 4800    | 1         | 0.49%   |
| 4267    | 1         | 0.49%   |
| 3933    | 1         | 0.49%   |
| 3534    | 1         | 0.49%   |
| 3400    | 1         | 0.49%   |
| 3000    | 1         | 0.49%   |
| 2666    | 1         | 0.49%   |
| 1866    | 1         | 0.49%   |
| 1776    | 1         | 0.49%   |
| 1067    | 1         | 0.49%   |
| 1066    | 1         | 0.49%   |
| 975     | 1         | 0.49%   |
| 933     | 1         | 0.49%   |
| 533     | 1         | 0.49%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Seiko Epson         | 2         | 33.33%  |
| Hewlett-Packard     | 2         | 33.33%  |
| Samsung Electronics | 1         | 16.67%  |
| Prolific Technology | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Seiko Epson L382 Series            | 1         | 16.67%  |
| Seiko Epson L3110 Series           | 1         | 16.67%  |
| Samsung ML-1610 Mono Laser Printer | 1         | 16.67%  |
| Prolific PL2305 Parallel Port      | 1         | 16.67%  |
| HP Ink Tank Wireless 410 series    | 1         | 16.67%  |
| HP Deskjet 2050 J510               | 1         | 16.67%  |

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
| Chicony Electronics                    | 55        | 22.63%  |
| IMC Networks                           | 29        | 11.93%  |
| Microdia                               | 18        | 7.41%   |
| Quanta                                 | 16        | 6.58%   |
| Realtek Semiconductor                  | 15        | 6.17%   |
| Cheng Uei Precision Industry (Foxlink) | 12        | 4.94%   |
| Suyin                                  | 11        | 4.53%   |
| Sunplus Innovation Technology          | 9         | 3.7%    |
| Syntek                                 | 8         | 3.29%   |
| Bison Electronics                      | 6         | 2.47%   |
| Apple                                  | 6         | 2.47%   |
| Luxvisions Innotech Limited            | 5         | 2.06%   |
| Lite-On Technology                     | 5         | 2.06%   |
| Silicon Motion                         | 3         | 1.23%   |
| Ricoh                                  | 3         | 1.23%   |
| Logitech                               | 3         | 1.23%   |
| KYE Systems (Mouse Systems)            | 3         | 1.23%   |
| Generalplus Technology                 | 3         | 1.23%   |
| Alcor Micro                            | 3         | 1.23%   |
| Sonix Technology                       | 2         | 0.82%   |
| Pixart Imaging                         | 2         | 0.82%   |
| OmniVision Technologies                | 2         | 0.82%   |
| Microsoft                              | 2         | 0.82%   |
| Jieli Technology                       | 2         | 0.82%   |
| icSpring                               | 2         | 0.82%   |
| Acer                                   | 2         | 0.82%   |
| Z-Star Microelectronics                | 1         | 0.41%   |
| Unknown                                | 1         | 0.41%   |
| Trust                                  | 1         | 0.41%   |
| ShineTech                              | 1         | 0.41%   |
| Shine-optics                           | 1         | 0.41%   |
| Samsung Electronics                    | 1         | 0.41%   |
| Novatek Microelectronics               | 1         | 0.41%   |
| MacroSilicon                           | 1         | 0.41%   |
| Lenovo                                 | 1         | 0.41%   |
| Importek                               | 1         | 0.41%   |
| Genesys Logic                          | 1         | 0.41%   |
| GEMBIRD                                | 1         | 0.41%   |
| Foxconn / Hon Hai                      | 1         | 0.41%   |
| eMeet                                  | 1         | 0.41%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD                           | 9         | 3.7%    |
| Chicony Integrated Camera                               | 9         | 3.7%    |
| IMC Networks Integrated Camera                          | 8         | 3.29%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 7         | 2.88%   |
| Chicony HP Truevision HD                                | 6         | 2.47%   |
| Realtek Integrated_Webcam_HD                            | 5         | 2.06%   |
| Chicony TOSHIBA Web Camera - HD                         | 5         | 2.06%   |
| Chicony USB2.0 VGA UVC WebCam                           | 4         | 1.65%   |
| Syntek Integrated Camera                                | 3         | 1.23%   |
| Suyin Integrated_Webcam_HD                              | 3         | 1.23%   |
| Suyin HD WebCam                                         | 3         | 1.23%   |
| Quanta HP Wide Vision HD Camera                         | 3         | 1.23%   |
| Logitech Webcam C270                                    | 3         | 1.23%   |
| IMC Networks VGA UVC WebCam                             | 3         | 1.23%   |
| IMC Networks TOSHIBA Web Camera - HD                    | 3         | 1.23%   |
| Chicony HD User Facing                                  | 3         | 1.23%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 3         | 1.23%   |
| Apple FaceTime HD Camera                                | 3         | 1.23%   |
| Syntek Lenovo EasyCamera                                | 2         | 0.82%   |
| Syntek EasyCamera                                       | 2         | 0.82%   |
| Suyin HP Truevision HD                                  | 2         | 0.82%   |
| Sunplus Laptop_Integrated_Webcam_FHD                    | 2         | 0.82%   |
| Sunplus Integrated_Webcam_HD                            | 2         | 0.82%   |
| Sunplus Integrated_Webcam_FHD                           | 2         | 0.82%   |
| Sonix USB2.0 HD UVC WebCam                              | 2         | 0.82%   |
| Realtek Integrated Webcam                               | 2         | 0.82%   |
| Realtek HP Truevision HD                                | 2         | 0.82%   |
| Realtek HP "Truevision HD" laptop camera                | 2         | 0.82%   |
| Realtek HD WebCam                                       | 2         | 0.82%   |
| Quanta HP Webcam-50                                     | 2         | 0.82%   |
| Quanta HP Webcam                                        | 2         | 0.82%   |
| Quanta HP TrueVision HD Camera                          | 2         | 0.82%   |
| Quanta ACER HD User Facing                              | 2         | 0.82%   |
| OmniVision OV2640 Webcam                                | 2         | 0.82%   |
| Microsoft LifeCam VX-5000                               | 2         | 0.82%   |
| Microdia USB 2.0 Camera                                 | 2         | 0.82%   |
| Microdia Camera                                         | 2         | 0.82%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera    | 2         | 0.82%   |
| Lite-On TOSHIBA Web Camera - HD                         | 2         | 0.82%   |
| Lite-On HP TrueVision HD Camera                         | 2         | 0.82%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 7         | 26.92%  |
| Validity Sensors           | 4         | 15.38%  |
| Elan Microelectronics      | 4         | 15.38%  |
| AuthenTec                  | 4         | 15.38%  |
| Shenzhen Goodix Technology | 3         | 11.54%  |
| Upek                       | 2         | 7.69%   |
| STMicroelectronics         | 1         | 3.85%   |
| LighTuning Technology      | 1         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                    | 3         | 11.54%  |
| AuthenTec AES1600                                      | 3         | 11.54%  |
| Validity Sensors Swipe Fingerprint Sensor              | 2         | 7.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 2         | 7.69%   |
| Synaptics  WBDI                                        | 2         | 7.69%   |
| Elan ELAN:Fingerprint                                  | 2         | 7.69%   |
| Elan ELAN:ARM-M4                                       | 2         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor           | 1         | 3.85%   |
| Validity Sensors Fingerprint scanner                   | 1         | 3.85%   |
| Synaptics WBDI                                         | 1         | 3.85%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 1         | 3.85%   |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 1         | 3.85%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 1         | 3.85%   |
| Synaptics Fingerprint scanner                          | 1         | 3.85%   |
| STMicroelectronics Fingerprint Reader                  | 1         | 3.85%   |
| LighTuning Fingerprint Sensor                          | 1         | 3.85%   |
| AuthenTec AES2810                                      | 1         | 3.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 4         | 44.44%  |
| O2 Micro    | 3         | 33.33%  |
| Upek        | 1         | 11.11%  |
| Alcor Micro | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 22.22%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 2         | 22.22%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 11.11%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 11.11%  |
| Broadcom 5880                                                                | 1         | 11.11%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 242       | 71.6%   |
| 1     | 79        | 23.37%  |
| 2     | 15        | 4.44%   |
| 5     | 1         | 0.3%    |
| 3     | 1         | 0.3%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 31        | 26.5%   |
| Fingerprint reader       | 26        | 22.22%  |
| Net/wireless             | 22        | 18.8%   |
| Multimedia controller    | 10        | 8.55%   |
| Chipcard                 | 8         | 6.84%   |
| Communication controller | 4         | 3.42%   |
| Camera                   | 4         | 3.42%   |
| Bluetooth                | 4         | 3.42%   |
| Storage                  | 3         | 2.56%   |
| Sound                    | 3         | 2.56%   |
| Network                  | 1         | 0.85%   |
| Net/ethernet             | 1         | 0.85%   |

