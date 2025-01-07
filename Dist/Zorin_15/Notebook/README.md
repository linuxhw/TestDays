Zorin 15 - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------

A project to collect tested hardware configurations for Zorin 15.

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

Total: 1560

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Toshiba       | Satellite A110              | [1d2307c817](https://linux-hardware.org/?probe=1d2307c817) | Dec 16, 2024 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [b0508a61eb](https://linux-hardware.org/?probe=b0508a61eb) | Dec 05, 2024 |
| HP            | Pavilion g6                 | [5b93f09faa](https://linux-hardware.org/?probe=5b93f09faa) | Nov 15, 2024 |
| HP            | Compaq 6710s (GC014ET#AB... | [f37a3d2488](https://linux-hardware.org/?probe=f37a3d2488) | Nov 11, 2024 |
| HP            | Compaq 6710s (GC014ET#AB... | [59cdfa97ac](https://linux-hardware.org/?probe=59cdfa97ac) | Nov 10, 2024 |
| Acer          | Aspire 5738                 | [d550044553](https://linux-hardware.org/?probe=d550044553) | Oct 19, 2024 |
| HP            | Stream Notebook PC 14       | [bf5f7ae790](https://linux-hardware.org/?probe=bf5f7ae790) | Sep 28, 2024 |
| Acer          | Aspire one                  | [61a3d9531f](https://linux-hardware.org/?probe=61a3d9531f) | Sep 22, 2024 |
| HP            | Pavilion 15                 | [eac3707cd6](https://linux-hardware.org/?probe=eac3707cd6) | Sep 08, 2024 |
| Technopc      | TI15N33W                    | [4845d584a3](https://linux-hardware.org/?probe=4845d584a3) | Aug 23, 2024 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [c478363aa1](https://linux-hardware.org/?probe=c478363aa1) | Aug 17, 2024 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [b4deb0d4f1](https://linux-hardware.org/?probe=b4deb0d4f1) | Aug 15, 2024 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [ba3fa007b2](https://linux-hardware.org/?probe=ba3fa007b2) | Aug 13, 2024 |
| Toshiba       | Satellite L40               | [dac6bed959](https://linux-hardware.org/?probe=dac6bed959) | Jul 23, 2024 |
| Toshiba       | Satellite L40               | [be27198d96](https://linux-hardware.org/?probe=be27198d96) | Jul 23, 2024 |
| IBM           | ThinkPad T40p 2373CG6       | [f9c1ee57fa](https://linux-hardware.org/?probe=f9c1ee57fa) | Jul 06, 2024 |
| IBM           | ThinkPad T40p 2373CG6       | [535ae7d8ae](https://linux-hardware.org/?probe=535ae7d8ae) | Jul 06, 2024 |
| Gateway       | NV57H                       | [5889815ec9](https://linux-hardware.org/?probe=5889815ec9) | May 30, 2024 |
| Acer          | TravelMate 4060             | [5bbfc69ef7](https://linux-hardware.org/?probe=5bbfc69ef7) | May 01, 2024 |
| Toshiba       | NB520                       | [d347b22da0](https://linux-hardware.org/?probe=d347b22da0) | Apr 03, 2024 |
| HP            | 2133                        | [262c68f9a7](https://linux-hardware.org/?probe=262c68f9a7) | Mar 08, 2024 |
| Acer          | Aspire 5310                 | [5a8aa1f2f8](https://linux-hardware.org/?probe=5a8aa1f2f8) | Mar 03, 2024 |
| Dell          | Vostro 1500                 | [a1e50e7852](https://linux-hardware.org/?probe=a1e50e7852) | Feb 28, 2024 |
| Dell          | Vostro 1500                 | [c6a22855f4](https://linux-hardware.org/?probe=c6a22855f4) | Feb 16, 2024 |
| Dell          | Vostro 1500                 | [4941fdca15](https://linux-hardware.org/?probe=4941fdca15) | Feb 07, 2024 |
| Acer          | Aspire 5738                 | [7137d60986](https://linux-hardware.org/?probe=7137d60986) | Feb 02, 2024 |
| HP            | 15 Notebook PC              | [b60abe5c3d](https://linux-hardware.org/?probe=b60abe5c3d) | Feb 01, 2024 |
| HP            | 15 Notebook PC              | [b2f9ce6a03](https://linux-hardware.org/?probe=b2f9ce6a03) | Feb 01, 2024 |
| Lenovo        | Y50-70 20378                | [d146d31a02](https://linux-hardware.org/?probe=d146d31a02) | Jan 20, 2024 |
| HP            | 530 Notebook PC(GU324AA#... | [785d324acb](https://linux-hardware.org/?probe=785d324acb) | Jan 18, 2024 |
| Toshiba       | Satellite P200              | [bda7517862](https://linux-hardware.org/?probe=bda7517862) | Jan 08, 2024 |
| Packard Be... | EasyNote TN36               | [2b83138160](https://linux-hardware.org/?probe=2b83138160) | Dec 28, 2023 |
| Gateway       | MX3235m                     | [074b414446](https://linux-hardware.org/?probe=074b414446) | Dec 28, 2023 |
| Gateway       | MX3235m                     | [283075fa43](https://linux-hardware.org/?probe=283075fa43) | Dec 28, 2023 |
| Lenovo        | Y50-70 20378                | [07c7da687a](https://linux-hardware.org/?probe=07c7da687a) | Dec 17, 2023 |
| Lenovo        | Y50-70 20378                | [e6ad27a4dd](https://linux-hardware.org/?probe=e6ad27a4dd) | Dec 17, 2023 |
| Dell          | Latitude E5470              | [cea78b64d4](https://linux-hardware.org/?probe=cea78b64d4) | Dec 08, 2023 |
| HP            | Pavilion dv5                | [de192ce8b7](https://linux-hardware.org/?probe=de192ce8b7) | Nov 26, 2023 |
| HP            | Pavilion dv5                | [51fc2d77fc](https://linux-hardware.org/?probe=51fc2d77fc) | Nov 26, 2023 |
| Dell          | Latitude E5470              | [b1efa66e79](https://linux-hardware.org/?probe=b1efa66e79) | Aug 27, 2023 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [7726b35ef6](https://linux-hardware.org/?probe=7726b35ef6) | Aug 25, 2023 |
| Dell          | Latitude E5470              | [ca95c6f5bc](https://linux-hardware.org/?probe=ca95c6f5bc) | Aug 19, 2023 |
| HP            | 530                         | [3d05ea6c86](https://linux-hardware.org/?probe=3d05ea6c86) | Jul 30, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [0a1ef2aa5b](https://linux-hardware.org/?probe=0a1ef2aa5b) | Jul 27, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | [d4914d5e5d](https://linux-hardware.org/?probe=d4914d5e5d) | Jul 27, 2023 |
| Dell          | Vostro 1500                 | [c57ac4da0a](https://linux-hardware.org/?probe=c57ac4da0a) | Jul 25, 2023 |
| OEM           | Unknown                     | [a45e07b803](https://linux-hardware.org/?probe=a45e07b803) | Jul 23, 2023 |
| HP            | Compaq Presario CQ50        | [1316c533a8](https://linux-hardware.org/?probe=1316c533a8) | Jul 21, 2023 |
| Dell          | Vostro 1500                 | [0c4f8fe4d2](https://linux-hardware.org/?probe=0c4f8fe4d2) | Jul 20, 2023 |
| Positivo      | Mobile                      | [1a6243fc5d](https://linux-hardware.org/?probe=1a6243fc5d) | Jul 18, 2023 |
| Positivo      | Mobile                      | [0c194a9d1d](https://linux-hardware.org/?probe=0c194a9d1d) | Jul 18, 2023 |
| Apple         | MacBookPro9,2               | [9cab0f6446](https://linux-hardware.org/?probe=9cab0f6446) | Jul 13, 2023 |
| Apple         | MacBookPro9,2               | [c1a6aea2fc](https://linux-hardware.org/?probe=c1a6aea2fc) | Jul 13, 2023 |
| Dell          | Precision M4700             | [3680e0f79f](https://linux-hardware.org/?probe=3680e0f79f) | Jul 04, 2023 |
| HP            | Compaq 6910p (GR670ET#UU... | [1ca7da939f](https://linux-hardware.org/?probe=1ca7da939f) | Jul 02, 2023 |
| ASUSTek       | K50IJ                       | [8262209249](https://linux-hardware.org/?probe=8262209249) | Jun 30, 2023 |
| eMachines     | eMD728                      | [85dd880b0d](https://linux-hardware.org/?probe=85dd880b0d) | Jun 15, 2023 |
| ASUSTek       | K52N                        | [eb2ec7cb3d](https://linux-hardware.org/?probe=eb2ec7cb3d) | Jun 15, 2023 |
| HP            | Pavilion g7                 | [c599527484](https://linux-hardware.org/?probe=c599527484) | Jun 11, 2023 |
| Fujitsu Si... | AMILO A1645                 | [d825262368](https://linux-hardware.org/?probe=d825262368) | May 16, 2023 |
| Fujitsu Si... | AMILO A1645                 | [18ca79ef29](https://linux-hardware.org/?probe=18ca79ef29) | May 16, 2023 |
| eMachines     | E620                        | [827a81facc](https://linux-hardware.org/?probe=827a81facc) | May 11, 2023 |
| Toshiba       | Satellite M60               | [91437556e8](https://linux-hardware.org/?probe=91437556e8) | May 09, 2023 |
| Toshiba       | Satellite M60               | [39b2bcd3a5](https://linux-hardware.org/?probe=39b2bcd3a5) | May 09, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | [953d03df07](https://linux-hardware.org/?probe=953d03df07) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | [ee52ca7ce5](https://linux-hardware.org/?probe=ee52ca7ce5) | May 08, 2023 |
| Acer          | Aspire 5732Z                | [f9868f3430](https://linux-hardware.org/?probe=f9868f3430) | May 04, 2023 |
| Acer          | AOHAPPY                     | [6f32fad8f0](https://linux-hardware.org/?probe=6f32fad8f0) | Apr 24, 2023 |
| Acer          | AOHAPPY                     | [57a7ebf03f](https://linux-hardware.org/?probe=57a7ebf03f) | Apr 21, 2023 |
| Lenovo        | G500 20236                  | [22d22e0742](https://linux-hardware.org/?probe=22d22e0742) | Apr 01, 2023 |
| Lenovo        | G500 20236                  | [2994622700](https://linux-hardware.org/?probe=2994622700) | Apr 01, 2023 |
| HP            | 255 G5                      | [99e2d83974](https://linux-hardware.org/?probe=99e2d83974) | Mar 24, 2023 |
| Acer          | TravelMate 2490             | [5a21a61bef](https://linux-hardware.org/?probe=5a21a61bef) | Mar 19, 2023 |
| Google        | Kip                         | [84b79bf446](https://linux-hardware.org/?probe=84b79bf446) | Mar 19, 2023 |
| Google        | Kip                         | [4e63ea7ac8](https://linux-hardware.org/?probe=4e63ea7ac8) | Mar 19, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | [2b864d8f97](https://linux-hardware.org/?probe=2b864d8f97) | Mar 12, 2023 |
| Dell          | Latitude E5470              | [86adaddcae](https://linux-hardware.org/?probe=86adaddcae) | Mar 12, 2023 |
| Dell          | Latitude E5470              | [e7e23885b7](https://linux-hardware.org/?probe=e7e23885b7) | Mar 11, 2023 |
| HP            | Compaq nc6120 (PY505EA#A... | [c8d3cf3a4b](https://linux-hardware.org/?probe=c8d3cf3a4b) | Mar 11, 2023 |
| ASUSTek       | K50IJ                       | [6b906bab7d](https://linux-hardware.org/?probe=6b906bab7d) | Mar 09, 2023 |
| ASUSTek       | K50IJ                       | [cc455dcfac](https://linux-hardware.org/?probe=cc455dcfac) | Mar 08, 2023 |
| Dell          | Inspiron N5010              | [480ff87a20](https://linux-hardware.org/?probe=480ff87a20) | Feb 28, 2023 |
| HP            | ENVY 17                     | [61d1252ef3](https://linux-hardware.org/?probe=61d1252ef3) | Feb 28, 2023 |
| Lenovo        | ThinkPad R400 7439W2F       | [2673ce6bd9](https://linux-hardware.org/?probe=2673ce6bd9) | Feb 27, 2023 |
| HP            | ENVY 17                     | [ea0b2e63ef](https://linux-hardware.org/?probe=ea0b2e63ef) | Feb 21, 2023 |
| Toshiba       | Satellite L50D-B            | [689c37d3b7](https://linux-hardware.org/?probe=689c37d3b7) | Feb 19, 2023 |
| HP            | ENVY 17                     | [de8af1b249](https://linux-hardware.org/?probe=de8af1b249) | Feb 18, 2023 |
| ASUSTek       | K50IJ                       | [9b35a3205f](https://linux-hardware.org/?probe=9b35a3205f) | Feb 17, 2023 |
| ASUSTek       | K50IJ                       | [a37ac85ec2](https://linux-hardware.org/?probe=a37ac85ec2) | Feb 16, 2023 |
| IBM           | ThinkPad T40p 2373CG6       | [a7aa67f64e](https://linux-hardware.org/?probe=a7aa67f64e) | Feb 14, 2023 |
| IBM           | ThinkPad T40p 2373CG6       | [eda645cefe](https://linux-hardware.org/?probe=eda645cefe) | Feb 14, 2023 |
| TWC           | Unknown                     | [4ea2803396](https://linux-hardware.org/?probe=4ea2803396) | Feb 06, 2023 |
| ASUSTek       | K50IJ                       | [c01f530c1c](https://linux-hardware.org/?probe=c01f530c1c) | Jan 31, 2023 |
| ASUSTek       | K50IJ                       | [51c65b48bc](https://linux-hardware.org/?probe=51c65b48bc) | Jan 31, 2023 |
| AXDIA Inte... | WINPAD V10                  | [dc93e9d9f0](https://linux-hardware.org/?probe=dc93e9d9f0) | Jan 24, 2023 |
| ASUSTek       | A6U                         | [58c040d67c](https://linux-hardware.org/?probe=58c040d67c) | Jan 19, 2023 |
| ASUSTek       | A6U                         | [9156e1c9cd](https://linux-hardware.org/?probe=9156e1c9cd) | Jan 19, 2023 |
| HP            | Pavilion 17                 | [09b186fbf7](https://linux-hardware.org/?probe=09b186fbf7) | Jan 16, 2023 |
| Sony          | VGN-SR16GN_B                | [94475e6d4e](https://linux-hardware.org/?probe=94475e6d4e) | Jan 14, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [cc8d4f6e6d](https://linux-hardware.org/?probe=cc8d4f6e6d) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [393397e25c](https://linux-hardware.org/?probe=393397e25c) | Jan 06, 2023 |
| Lenovo        | IdeaPad 130-15AST 81H5      | [76f452827f](https://linux-hardware.org/?probe=76f452827f) | Jan 06, 2023 |
| HP            | Pavilion dv6000 (GA131UA... | [115a479990](https://linux-hardware.org/?probe=115a479990) | Jan 05, 2023 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [a2f6a6831a](https://linux-hardware.org/?probe=a2f6a6831a) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | [3f5a2c6ea1](https://linux-hardware.org/?probe=3f5a2c6ea1) | Dec 30, 2022 |
| HP            | Pavilion dv6                | [12a8186204](https://linux-hardware.org/?probe=12a8186204) | Dec 30, 2022 |
| Toshiba       | Satellite L500              | [3258bb06ef](https://linux-hardware.org/?probe=3258bb06ef) | Dec 08, 2022 |
| HP            | Laptop 15s-eq2xxx           | [686afd3c20](https://linux-hardware.org/?probe=686afd3c20) | Dec 02, 2022 |
| HP            | Pavilion dv5000 (EU087EA... | [185c483599](https://linux-hardware.org/?probe=185c483599) | Nov 07, 2022 |
| ASUSTek       | F5V                         | [877e968b61](https://linux-hardware.org/?probe=877e968b61) | Nov 07, 2022 |
| HP            | Pavilion dv5000 (EU087EA... | [d763771ba6](https://linux-hardware.org/?probe=d763771ba6) | Nov 06, 2022 |
| HP            | Pavilion 15                 | [8552c17b28](https://linux-hardware.org/?probe=8552c17b28) | Nov 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [861aaf5a99](https://linux-hardware.org/?probe=861aaf5a99) | Oct 29, 2022 |
| Phoenix/Si... | M7x0S                       | [8b27fc5eb3](https://linux-hardware.org/?probe=8b27fc5eb3) | Oct 29, 2022 |
| Dell          | Inspiron 1525               | [742bf13a9f](https://linux-hardware.org/?probe=742bf13a9f) | Oct 25, 2022 |
| Lenovo        | ThinkPad T520 4243PN7       | [fdca71510b](https://linux-hardware.org/?probe=fdca71510b) | Oct 24, 2022 |
| Dell          | Vostro V13                  | [c7cd7a2ddf](https://linux-hardware.org/?probe=c7cd7a2ddf) | Oct 21, 2022 |
| Dell          | Vostro V13                  | [43eb559763](https://linux-hardware.org/?probe=43eb559763) | Oct 21, 2022 |
| Dell          | Inspiron 1200               | [45c46e1b91](https://linux-hardware.org/?probe=45c46e1b91) | Oct 08, 2022 |
| Toshiba       | Satellite L500              | [29c7a43356](https://linux-hardware.org/?probe=29c7a43356) | Oct 06, 2022 |
| ASUSTek       | R11CX                       | [fb6e1d3652](https://linux-hardware.org/?probe=fb6e1d3652) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | [f0bc5f49a4](https://linux-hardware.org/?probe=f0bc5f49a4) | Oct 03, 2022 |
| Dell          | Inspiron 1200               | [32dd972d77](https://linux-hardware.org/?probe=32dd972d77) | Sep 29, 2022 |
| Acer          | Aspire SW5-012              | [ed8f3f7403](https://linux-hardware.org/?probe=ed8f3f7403) | Sep 25, 2022 |
| Dell          | Latitude D610               | [47e0f0fa27](https://linux-hardware.org/?probe=47e0f0fa27) | Sep 19, 2022 |
| Lenovo        | ThinkPad 11e 20DAS09U00     | [81bd748796](https://linux-hardware.org/?probe=81bd748796) | Sep 19, 2022 |
| Dell          | Latitude D610               | [df13ed7396](https://linux-hardware.org/?probe=df13ed7396) | Sep 18, 2022 |
| Dell          | Latitude D630               | [b898e91e58](https://linux-hardware.org/?probe=b898e91e58) | Sep 15, 2022 |
| HP            | EliteBook 820 G2            | [199f191441](https://linux-hardware.org/?probe=199f191441) | Sep 14, 2022 |
| HP            | Pavilion dv6000 (RP986EA... | [f20de20683](https://linux-hardware.org/?probe=f20de20683) | Sep 11, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [7c3cdfba24](https://linux-hardware.org/?probe=7c3cdfba24) | Sep 08, 2022 |
| Intel         | powered classmate PC        | [ed36baccf9](https://linux-hardware.org/?probe=ed36baccf9) | Aug 31, 2022 |
| HP            | ProBook 6470b               | [2cbe458c94](https://linux-hardware.org/?probe=2cbe458c94) | Aug 30, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [01416789ab](https://linux-hardware.org/?probe=01416789ab) | Aug 21, 2022 |
| HP            | Pavilion dv9700             | [7c3e324e4f](https://linux-hardware.org/?probe=7c3e324e4f) | Aug 16, 2022 |
| HP            | Pavilion 15                 | [462769d45e](https://linux-hardware.org/?probe=462769d45e) | Aug 11, 2022 |
| Dell          | Latitude D630               | [3650f52bba](https://linux-hardware.org/?probe=3650f52bba) | Aug 11, 2022 |
| Acer          | Aspire 9410                 | [0d433f48f4](https://linux-hardware.org/?probe=0d433f48f4) | Aug 05, 2022 |
| Fujitsu Si... | AMILO Li1705                | [af83e534ff](https://linux-hardware.org/?probe=af83e534ff) | Aug 04, 2022 |
| Toshiba       | Satellite P205              | [8ed745a2dc](https://linux-hardware.org/?probe=8ed745a2dc) | Aug 03, 2022 |
| HP            | Compaq 6730s                | [5d805b2f5e](https://linux-hardware.org/?probe=5d805b2f5e) | Jul 31, 2022 |
| Dell          | Inspiron 1525               | [6c43e1dfd6](https://linux-hardware.org/?probe=6c43e1dfd6) | Jul 22, 2022 |
| Dell          | MXG061                      | [9301162b93](https://linux-hardware.org/?probe=9301162b93) | Jul 18, 2022 |
| HP            | ENVY 17                     | [bc1e8b41a5](https://linux-hardware.org/?probe=bc1e8b41a5) | Jul 17, 2022 |
| HP            | Compaq nx6310 (EY589ES#A... | [613395d2cf](https://linux-hardware.org/?probe=613395d2cf) | Jul 13, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | [9e604c2dcc](https://linux-hardware.org/?probe=9e604c2dcc) | Jul 12, 2022 |
| Fujitsu Si... | AMILO L Series              | [410cd1aeec](https://linux-hardware.org/?probe=410cd1aeec) | Jul 08, 2022 |
| Lenovo        | ThinkPad E570 20H50047US    | [f11f4826ba](https://linux-hardware.org/?probe=f11f4826ba) | Jul 08, 2022 |
| Lenovo        | ThinkPad E570 20H50047US    | [50e02d8554](https://linux-hardware.org/?probe=50e02d8554) | Jul 08, 2022 |
| ASUSTek       | K70IC                       | [baa2ddeb5a](https://linux-hardware.org/?probe=baa2ddeb5a) | Jul 08, 2022 |
| ASUSTek       | ZenBook UX392FN_UX392FN     | [b4699ba106](https://linux-hardware.org/?probe=b4699ba106) | Jun 30, 2022 |
| Dell          | Latitude E6400              | [df93b48c3c](https://linux-hardware.org/?probe=df93b48c3c) | Jun 28, 2022 |
| Acer          | Aspire A315-42              | [57d9c7c28a](https://linux-hardware.org/?probe=57d9c7c28a) | Jun 24, 2022 |
| Dell          | Latitude E6400              | [6198dd2784](https://linux-hardware.org/?probe=6198dd2784) | Jun 22, 2022 |
| HP            | Pavilion Notebook           | [551da1dbb6](https://linux-hardware.org/?probe=551da1dbb6) | Jun 20, 2022 |
| Acer          | TravelMate 5320             | [4d7e13024d](https://linux-hardware.org/?probe=4d7e13024d) | May 19, 2022 |
| HP            | Pavilion 17                 | [a3f1fe480c](https://linux-hardware.org/?probe=a3f1fe480c) | May 14, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [5d02fb20c7](https://linux-hardware.org/?probe=5d02fb20c7) | Apr 29, 2022 |
| Lenovo        | ThinkPad L412 440332U       | [6616ce20ee](https://linux-hardware.org/?probe=6616ce20ee) | Apr 28, 2022 |
| HP            | Notebook                    | [b746d96b41](https://linux-hardware.org/?probe=b746d96b41) | Apr 19, 2022 |
| Dell          | Latitude E6410              | [391866815a](https://linux-hardware.org/?probe=391866815a) | Apr 17, 2022 |
| Packard Be... | EasyNote TN36               | [23936e29bb](https://linux-hardware.org/?probe=23936e29bb) | Apr 15, 2022 |
| Packard Be... | EasyNote TN36               | [ae514187f2](https://linux-hardware.org/?probe=ae514187f2) | Apr 15, 2022 |
| HP            | Laptop 14-cm0xxx            | [d6463e4014](https://linux-hardware.org/?probe=d6463e4014) | Apr 14, 2022 |
| HP            | Presario C500 (GF852EA#A... | [b14e9c5694](https://linux-hardware.org/?probe=b14e9c5694) | Apr 08, 2022 |
| Lenovo        | ThinkPad R61 8933W4F        | [4864fcdfa0](https://linux-hardware.org/?probe=4864fcdfa0) | Apr 07, 2022 |
| Panasonic     | CF-31ACJAXPM                | [c90a918208](https://linux-hardware.org/?probe=c90a918208) | Mar 28, 2022 |
| ASUSTek       | K70IC                       | [977e15d60c](https://linux-hardware.org/?probe=977e15d60c) | Mar 28, 2022 |
| Acer          | Aspire 3690                 | [76139c48e8](https://linux-hardware.org/?probe=76139c48e8) | Mar 25, 2022 |
| BGH e-Nova    | Unknown                     | [408be10e82](https://linux-hardware.org/?probe=408be10e82) | Mar 22, 2022 |
| Acer          | Unknown                     | [3c80f8700c](https://linux-hardware.org/?probe=3c80f8700c) | Mar 19, 2022 |
| Toshiba       | Satellite M505              | [924c539075](https://linux-hardware.org/?probe=924c539075) | Mar 12, 2022 |
| Dell          | Inspiron MM061              | [ad5413d163](https://linux-hardware.org/?probe=ad5413d163) | Mar 06, 2022 |
| HP            | ProBook 445 G7              | [b0b810cf14](https://linux-hardware.org/?probe=b0b810cf14) | Mar 04, 2022 |
| HP            | 255 G5                      | [050e7b02e7](https://linux-hardware.org/?probe=050e7b02e7) | Feb 28, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [d5c0be1b13](https://linux-hardware.org/?probe=d5c0be1b13) | Feb 27, 2022 |
| ASUSTek       | S500CA                      | [db6a143f17](https://linux-hardware.org/?probe=db6a143f17) | Feb 27, 2022 |
| Fujitsu       | FARQ0200GZ                  | [a309120953](https://linux-hardware.org/?probe=a309120953) | Feb 26, 2022 |
| ASUSTek       | S500CA                      | [d8941a4a85](https://linux-hardware.org/?probe=d8941a4a85) | Feb 25, 2022 |
| HP            | 2140                        | [ad18e8d0b3](https://linux-hardware.org/?probe=ad18e8d0b3) | Feb 22, 2022 |
| HP            | 2140                        | [e0757f087f](https://linux-hardware.org/?probe=e0757f087f) | Feb 22, 2022 |
| Sony          | VPCEH3L1E                   | [4fa6aebb55](https://linux-hardware.org/?probe=4fa6aebb55) | Feb 21, 2022 |
| HP            | Notebook                    | [aee3f5ce0b](https://linux-hardware.org/?probe=aee3f5ce0b) | Feb 18, 2022 |
| ATI           | BONEFISH                    | [caa7c41c75](https://linux-hardware.org/?probe=caa7c41c75) | Feb 17, 2022 |
| Lenovo        | ThinkPad T61 6458CTO        | [9081d7a51d](https://linux-hardware.org/?probe=9081d7a51d) | Feb 17, 2022 |
| Lenovo        | ThinkPad T61 6458CTO        | [4f0437053f](https://linux-hardware.org/?probe=4f0437053f) | Feb 17, 2022 |
| HP            | Compaq 6910p (GR670ET#UU... | [f21dcf572e](https://linux-hardware.org/?probe=f21dcf572e) | Feb 13, 2022 |
| HP            | Compaq 6910p (GR670ET#UU... | [7f07e2a9da](https://linux-hardware.org/?probe=7f07e2a9da) | Feb 13, 2022 |
| Dell          | Inspiron 1525               | [3db88da0ec](https://linux-hardware.org/?probe=3db88da0ec) | Feb 13, 2022 |
| Dell          | Inspiron 1545               | [feafacf00d](https://linux-hardware.org/?probe=feafacf00d) | Feb 13, 2022 |
| HP            | 255 G5                      | [a030b8f406](https://linux-hardware.org/?probe=a030b8f406) | Feb 13, 2022 |
| HP            | Compaq 6530b (NA755ES#AB... | [5bc4fdcfb0](https://linux-hardware.org/?probe=5bc4fdcfb0) | Feb 13, 2022 |
| Dell          | Inspiron 1545               | [00d31012f1](https://linux-hardware.org/?probe=00d31012f1) | Feb 12, 2022 |
| Acer          | Aspire 5600                 | [35dd7239e3](https://linux-hardware.org/?probe=35dd7239e3) | Feb 06, 2022 |
| Acer          | Aspire 5600                 | [4d2723a19e](https://linux-hardware.org/?probe=4d2723a19e) | Feb 06, 2022 |
| BenQ          | Joybook Lite U121           | [28f254dd8d](https://linux-hardware.org/?probe=28f254dd8d) | Feb 02, 2022 |
| Toshiba       | Satellite Pro C660          | [8be575e86a](https://linux-hardware.org/?probe=8be575e86a) | Feb 01, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [7db720ba39](https://linux-hardware.org/?probe=7db720ba39) | Feb 01, 2022 |
| Dell          | Inspiron 5567               | [0e47f03d64](https://linux-hardware.org/?probe=0e47f03d64) | Jan 24, 2022 |
| Toshiba       | Satellite Pro C660          | [49c83041f3](https://linux-hardware.org/?probe=49c83041f3) | Jan 24, 2022 |
| Toshiba       | Satellite M505              | [9356dfa5a9](https://linux-hardware.org/?probe=9356dfa5a9) | Jan 20, 2022 |
| WinSome       | A14C .B005                  | [d685b78944](https://linux-hardware.org/?probe=d685b78944) | Jan 19, 2022 |
| TWC           | Unknown                     | [85a8fd2cf1](https://linux-hardware.org/?probe=85a8fd2cf1) | Jan 18, 2022 |
| Dell          | Inspiron 5567               | [4b51693e30](https://linux-hardware.org/?probe=4b51693e30) | Jan 17, 2022 |
| TWC           | Unknown                     | [d4cc69cea7](https://linux-hardware.org/?probe=d4cc69cea7) | Jan 16, 2022 |
| Dell          | Inspiron 1545               | [a6c2013bf1](https://linux-hardware.org/?probe=a6c2013bf1) | Jan 15, 2022 |
| eMachines     | G625                        | [1c60347748](https://linux-hardware.org/?probe=1c60347748) | Jan 07, 2022 |
| Packard Be... | EasyNote MZ35               | [63281c8766](https://linux-hardware.org/?probe=63281c8766) | Jan 06, 2022 |
| Packard Be... | EasyNote MZ35               | [205f3bc0b9](https://linux-hardware.org/?probe=205f3bc0b9) | Jan 06, 2022 |
| Toshiba       | Satellite Pro C660          | [4d080d5d7a](https://linux-hardware.org/?probe=4d080d5d7a) | Jan 03, 2022 |
| eMachines     | G625                        | [03810742ed](https://linux-hardware.org/?probe=03810742ed) | Jan 03, 2022 |
| Lenovo        | ThinkPad T540p 20BFS5630... | [e1e090d622](https://linux-hardware.org/?probe=e1e090d622) | Jan 02, 2022 |
| eMachines     | G625                        | [e3f96637bb](https://linux-hardware.org/?probe=e3f96637bb) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 1294BL5         | [2cd6f5fbb0](https://linux-hardware.org/?probe=2cd6f5fbb0) | Jan 01, 2022 |
| HP            | Unknown                     | [acd2b01673](https://linux-hardware.org/?probe=acd2b01673) | Dec 31, 2021 |
| HP            | Unknown                     | [8f2ecbe94d](https://linux-hardware.org/?probe=8f2ecbe94d) | Dec 31, 2021 |
| Dell          | Latitude D420               | [3caac63d5f](https://linux-hardware.org/?probe=3caac63d5f) | Dec 31, 2021 |
| HP            | ZBook 15u G3                | [e220b55c78](https://linux-hardware.org/?probe=e220b55c78) | Dec 30, 2021 |
| HP            | Pavilion dv6700             | [ce62bcd9b0](https://linux-hardware.org/?probe=ce62bcd9b0) | Dec 28, 2021 |
| HP            | 255 G5                      | [0bf7bc5435](https://linux-hardware.org/?probe=0bf7bc5435) | Dec 28, 2021 |
| HP            | Laptop 14-dk1xxx            | [31fbadcc88](https://linux-hardware.org/?probe=31fbadcc88) | Dec 28, 2021 |
| HP            | ZBook 15u G3                | [f770dacb13](https://linux-hardware.org/?probe=f770dacb13) | Dec 25, 2021 |
| Acer          | Aspire 5250                 | [bef8e4334a](https://linux-hardware.org/?probe=bef8e4334a) | Dec 23, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [8f7a53f316](https://linux-hardware.org/?probe=8f7a53f316) | Dec 20, 2021 |
| Quanta        | MW1/HW1                     | [06bcb3603d](https://linux-hardware.org/?probe=06bcb3603d) | Dec 17, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | [b9908b0aa8](https://linux-hardware.org/?probe=b9908b0aa8) | Dec 12, 2021 |
| HP            | Notebook                    | [97e434f4aa](https://linux-hardware.org/?probe=97e434f4aa) | Dec 11, 2021 |
| Packard Be... | EasyNote MH35               | [c5dd11f2bd](https://linux-hardware.org/?probe=c5dd11f2bd) | Dec 08, 2021 |
| Packard Be... | EasyNote MH35               | [87a83af447](https://linux-hardware.org/?probe=87a83af447) | Dec 08, 2021 |
| Lenovo        | S10-3                       | [19cd43f2f7](https://linux-hardware.org/?probe=19cd43f2f7) | Nov 29, 2021 |
| Dell          | Inspiron 14-3452            | [b0fb64bf16](https://linux-hardware.org/?probe=b0fb64bf16) | Nov 27, 2021 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [c23b71e54e](https://linux-hardware.org/?probe=c23b71e54e) | Nov 27, 2021 |
| HP            | Pavilion g7                 | [e8dcea99ad](https://linux-hardware.org/?probe=e8dcea99ad) | Nov 26, 2021 |
| Toshiba       | Satellite L750              | [836cf1ca10](https://linux-hardware.org/?probe=836cf1ca10) | Nov 25, 2021 |
| Toshiba       | Satellite L750              | [827e07a075](https://linux-hardware.org/?probe=827e07a075) | Nov 24, 2021 |
| Fujitsu Si... | AMILO Li1705                | [397611b48d](https://linux-hardware.org/?probe=397611b48d) | Nov 20, 2021 |
| Lenovo        | ThinkPad X1 1294BL5         | [d543e2cd80](https://linux-hardware.org/?probe=d543e2cd80) | Nov 19, 2021 |
| HP            | Pavilion dv7                | [33202c35ad](https://linux-hardware.org/?probe=33202c35ad) | Nov 19, 2021 |
| HP            | Pavilion dv7                | [66ec298a1c](https://linux-hardware.org/?probe=66ec298a1c) | Nov 18, 2021 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [641218d2e6](https://linux-hardware.org/?probe=641218d2e6) | Nov 16, 2021 |
| HP            | Pavilion dv9500             | [bef50ae82a](https://linux-hardware.org/?probe=bef50ae82a) | Nov 15, 2021 |
| HP            | Compaq nx8220 (PG801ET#A... | [60c7204131](https://linux-hardware.org/?probe=60c7204131) | Nov 14, 2021 |
| Samsung       | 370E4K                      | [f076dae1f9](https://linux-hardware.org/?probe=f076dae1f9) | Nov 12, 2021 |
| Medion        | P8610                       | [122043c04d](https://linux-hardware.org/?probe=122043c04d) | Nov 08, 2021 |
| Medion        | P8610                       | [4d519680a1](https://linux-hardware.org/?probe=4d519680a1) | Nov 07, 2021 |
| ASUSTek       | K42F                        | [a0fc0b335f](https://linux-hardware.org/?probe=a0fc0b335f) | Nov 07, 2021 |
| MAXDATA       | ECO4000IW                   | [5a5fb011c7](https://linux-hardware.org/?probe=5a5fb011c7) | Nov 06, 2021 |
| Apple         | MacBookAir4,1               | [01eb7627e2](https://linux-hardware.org/?probe=01eb7627e2) | Nov 06, 2021 |
| Dell          | XPS M1330                   | [3fcb1bf591](https://linux-hardware.org/?probe=3fcb1bf591) | Nov 06, 2021 |
| Intel         | HURONRIVER                  | [5ded89b4a5](https://linux-hardware.org/?probe=5ded89b4a5) | Nov 02, 2021 |
| Lenovo        | ThinkPad X1 1294BL5         | [e18dd8b896](https://linux-hardware.org/?probe=e18dd8b896) | Nov 01, 2021 |
| Toshiba       | Satellite U400              | [abcf2eee75](https://linux-hardware.org/?probe=abcf2eee75) | Oct 27, 2021 |
| Acer          | Acadia V1.42                | [01122f69f4](https://linux-hardware.org/?probe=01122f69f4) | Oct 23, 2021 |
| Acer          | Acadia V1.42                | [11b24034fc](https://linux-hardware.org/?probe=11b24034fc) | Oct 23, 2021 |
| HP            | 255 G5                      | [02e4b753ca](https://linux-hardware.org/?probe=02e4b753ca) | Oct 22, 2021 |
| HP            | EliteBook 8460p             | [24535d9a4b](https://linux-hardware.org/?probe=24535d9a4b) | Oct 20, 2021 |
| HP            | EliteBook 8460p             | [cf78694aa7](https://linux-hardware.org/?probe=cf78694aa7) | Oct 20, 2021 |
| Dell          | System XPS 15Z              | [751ffeefa0](https://linux-hardware.org/?probe=751ffeefa0) | Oct 20, 2021 |
| HP            | Presario CQ42               | [d82c04d026](https://linux-hardware.org/?probe=d82c04d026) | Oct 19, 2021 |
| Acer          | Aspire ES1-531              | [a7058244ce](https://linux-hardware.org/?probe=a7058244ce) | Oct 16, 2021 |
| Dell          | Inspiron N5010              | [eca5c4cbf7](https://linux-hardware.org/?probe=eca5c4cbf7) | Oct 15, 2021 |
| HP            | Laptop 15-da0xxx            | [3054954ea5](https://linux-hardware.org/?probe=3054954ea5) | Oct 14, 2021 |
| Dell          | Inspiron N5010              | [2495309045](https://linux-hardware.org/?probe=2495309045) | Oct 14, 2021 |
| HP            | Laptop 15-da0xxx            | [dd3b21ba26](https://linux-hardware.org/?probe=dd3b21ba26) | Oct 14, 2021 |
| Dell          | Inspiron N5050              | [1dd1c022a2](https://linux-hardware.org/?probe=1dd1c022a2) | Oct 13, 2021 |
| Dell          | Inspiron N5050              | [8866975539](https://linux-hardware.org/?probe=8866975539) | Oct 13, 2021 |
| American M... | 255/259 Series              | [e8761321aa](https://linux-hardware.org/?probe=e8761321aa) | Oct 13, 2021 |
| Acer          | Aspire E1-572               | [dc154fe7c0](https://linux-hardware.org/?probe=dc154fe7c0) | Oct 13, 2021 |
| ASUSTek       | N61Jv                       | [0e300bafe8](https://linux-hardware.org/?probe=0e300bafe8) | Oct 12, 2021 |
| Toshiba       | Satellite Pro C660          | [14a96b5cec](https://linux-hardware.org/?probe=14a96b5cec) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | [34d9be1b4a](https://linux-hardware.org/?probe=34d9be1b4a) | Oct 10, 2021 |
| Acer          | TravelMate 2400             | [4895b20211](https://linux-hardware.org/?probe=4895b20211) | Oct 09, 2021 |
| HP            | Laptop 15-db0xxx            | [a49c0e5d41](https://linux-hardware.org/?probe=a49c0e5d41) | Oct 08, 2021 |
| Sony          | VPCEA20FB                   | [de4d94232e](https://linux-hardware.org/?probe=de4d94232e) | Oct 07, 2021 |
| Sony          | VPCEA20FB                   | [52e6abba3c](https://linux-hardware.org/?probe=52e6abba3c) | Oct 07, 2021 |
| Matsushita... | CF-19CHB23BE                | [7024487bcd](https://linux-hardware.org/?probe=7024487bcd) | Oct 07, 2021 |
| Acer          | AOD255                      | [79fa37e2d3](https://linux-hardware.org/?probe=79fa37e2d3) | Sep 30, 2021 |
| Lenovo        | ThinkPad Edge E531 68852... | [4cd46a616f](https://linux-hardware.org/?probe=4cd46a616f) | Sep 29, 2021 |
| Digibras      | NH4CU53                     | [f0615abf72](https://linux-hardware.org/?probe=f0615abf72) | Sep 27, 2021 |
| Toshiba       | Satellite C50-B             | [0914aeed54](https://linux-hardware.org/?probe=0914aeed54) | Sep 25, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1070... | [c77dd4d1b4](https://linux-hardware.org/?probe=c77dd4d1b4) | Sep 23, 2021 |
| Philco        | 14F                         | [093b9632e8](https://linux-hardware.org/?probe=093b9632e8) | Sep 23, 2021 |
| Dell          | Inspiron 6000               | [f48bad44cd](https://linux-hardware.org/?probe=f48bad44cd) | Sep 22, 2021 |
| ASUSTek       | UX430UAR                    | [57d695a843](https://linux-hardware.org/?probe=57d695a843) | Sep 21, 2021 |
| HP            | ProBook 4540s               | [ccac6a82ca](https://linux-hardware.org/?probe=ccac6a82ca) | Sep 20, 2021 |
| Fujitsu Si... | AMILO M7440D                | [e23f21b9b4](https://linux-hardware.org/?probe=e23f21b9b4) | Sep 19, 2021 |
| Fujitsu Si... | AMILO M7440D                | [bce3e66350](https://linux-hardware.org/?probe=bce3e66350) | Sep 19, 2021 |
| Positivo      | Mobile                      | [6f701d72fd](https://linux-hardware.org/?probe=6f701d72fd) | Sep 17, 2021 |
| ASUSTek       | F5SL                        | [e6e93168a6](https://linux-hardware.org/?probe=e6e93168a6) | Sep 15, 2021 |
| Toshiba       | Satellite Pro C850-1H8      | [ea23c035b2](https://linux-hardware.org/?probe=ea23c035b2) | Sep 15, 2021 |
| HP            | EliteBook 6930p             | [8f38de340d](https://linux-hardware.org/?probe=8f38de340d) | Sep 15, 2021 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [445f079c6d](https://linux-hardware.org/?probe=445f079c6d) | Sep 15, 2021 |
| Lenovo        | ThinkPad T61 765818U        | [7bae831cdf](https://linux-hardware.org/?probe=7bae831cdf) | Sep 12, 2021 |
| Acer          | Lugano M                    | [5c114a6e41](https://linux-hardware.org/?probe=5c114a6e41) | Sep 11, 2021 |
| Acer          | Aspire 5020                 | [54ddef7aa7](https://linux-hardware.org/?probe=54ddef7aa7) | Sep 11, 2021 |
| Acer          | Aspire 5020                 | [8c00427976](https://linux-hardware.org/?probe=8c00427976) | Sep 11, 2021 |
| Acer          | Aspire 3610                 | [fc6953a3f9](https://linux-hardware.org/?probe=fc6953a3f9) | Sep 10, 2021 |
| HP            | ProBook 6460b               | [b0f0eaf216](https://linux-hardware.org/?probe=b0f0eaf216) | Sep 09, 2021 |
| Pendo Indu... | PNDFWXUFD11BLK6             | [06d0750e6e](https://linux-hardware.org/?probe=06d0750e6e) | Sep 08, 2021 |
| Acer          | Aspire 3610                 | [3ab0387498](https://linux-hardware.org/?probe=3ab0387498) | Sep 08, 2021 |
| Dell          | Inspiron 1010               | [ee05ebef50](https://linux-hardware.org/?probe=ee05ebef50) | Sep 07, 2021 |
| Dell          | Inspiron 1010               | [8805be4e5c](https://linux-hardware.org/?probe=8805be4e5c) | Sep 07, 2021 |
| Lenovo        | ThinkPad T61 765818U        | [df384e1ab4](https://linux-hardware.org/?probe=df384e1ab4) | Sep 06, 2021 |
| GPD           | MicroPC                     | [d0ffed23be](https://linux-hardware.org/?probe=d0ffed23be) | Sep 05, 2021 |
| Unknown       | T3 MRD                      | [0687d6609d](https://linux-hardware.org/?probe=0687d6609d) | Sep 03, 2021 |
| Dell          | Latitude D630               | [6b4af154d5](https://linux-hardware.org/?probe=6b4af154d5) | Sep 03, 2021 |
| Acer          | Aspire 9410                 | [d6632fcd8b](https://linux-hardware.org/?probe=d6632fcd8b) | Sep 02, 2021 |
| HP            | 530                         | [cc7cc97ae3](https://linux-hardware.org/?probe=cc7cc97ae3) | Aug 31, 2021 |
| HP            | 530                         | [20bf2422fc](https://linux-hardware.org/?probe=20bf2422fc) | Aug 31, 2021 |
| ASUSTek       | X55U                        | [b37f7fdf24](https://linux-hardware.org/?probe=b37f7fdf24) | Aug 30, 2021 |
| Acer          | Aspire 8920                 | [8a006e9280](https://linux-hardware.org/?probe=8a006e9280) | Aug 28, 2021 |
| ASUSTek       | 1001PX                      | [1b8954cf9f](https://linux-hardware.org/?probe=1b8954cf9f) | Aug 27, 2021 |
| Lenovo        | ThinkPad R61e 7650ELU       | [7c29fad093](https://linux-hardware.org/?probe=7c29fad093) | Aug 26, 2021 |
| Lenovo        | ThinkPad SL510 28752NG      | [285a023dd8](https://linux-hardware.org/?probe=285a023dd8) | Aug 26, 2021 |
| ASUSTek       | UX430UAR                    | [88f301b39f](https://linux-hardware.org/?probe=88f301b39f) | Aug 26, 2021 |
| HP            | Mini 110-3100               | [2bca9a30ab](https://linux-hardware.org/?probe=2bca9a30ab) | Aug 25, 2021 |
| Dell          | Inspiron 6000               | [f4ae3e605a](https://linux-hardware.org/?probe=f4ae3e605a) | Aug 24, 2021 |
| Samsung       | 340XAA/350XAA/550XAA        | [ab8a4f01d9](https://linux-hardware.org/?probe=ab8a4f01d9) | Aug 22, 2021 |
| Panasonic     | CF-31JEGAX1M                | [c5acecef3a](https://linux-hardware.org/?probe=c5acecef3a) | Aug 22, 2021 |
| HP            | Compaq Presario CQ61        | [c7c1d06954](https://linux-hardware.org/?probe=c7c1d06954) | Aug 21, 2021 |
| Positivo      | Mobile                      | [e4a47e39b6](https://linux-hardware.org/?probe=e4a47e39b6) | Aug 21, 2021 |
| Samsung       | RV419                       | [ba6f454b7d](https://linux-hardware.org/?probe=ba6f454b7d) | Aug 20, 2021 |
| Samsung       | N150                        | [86914b23ac](https://linux-hardware.org/?probe=86914b23ac) | Aug 19, 2021 |
| Positivo      | Q232A                       | [f76d2dc489](https://linux-hardware.org/?probe=f76d2dc489) | Aug 19, 2021 |
| HP            | ProBook 4430s               | [0235e3c344](https://linux-hardware.org/?probe=0235e3c344) | Aug 18, 2021 |
| Lenovo        | IdeaPad S540-14API 81NH     | [5ab0429d85](https://linux-hardware.org/?probe=5ab0429d85) | Aug 17, 2021 |
| HP            | ENVY 17                     | [7c9143912d](https://linux-hardware.org/?probe=7c9143912d) | Aug 17, 2021 |
| ASUSTek       | X441SA                      | [f23d4d50be](https://linux-hardware.org/?probe=f23d4d50be) | Aug 16, 2021 |
| Itautec       | Infoway                     | [f66edac6bd](https://linux-hardware.org/?probe=f66edac6bd) | Aug 16, 2021 |
| Itautec       | Infoway                     | [94c198d530](https://linux-hardware.org/?probe=94c198d530) | Aug 16, 2021 |
| HP            | Pavilion 17                 | [b628f70687](https://linux-hardware.org/?probe=b628f70687) | Aug 15, 2021 |
| SiS           | M672 Board SI94B-20+SI96... | [8268c73ee9](https://linux-hardware.org/?probe=8268c73ee9) | Aug 14, 2021 |
| HP            | Pavilion g7                 | [cf766b8d76](https://linux-hardware.org/?probe=cf766b8d76) | Aug 13, 2021 |
| Quanta        | QL5 TBD                     | [be465dec60](https://linux-hardware.org/?probe=be465dec60) | Aug 13, 2021 |
| Toshiba       | Satellite L505D             | [b7b43a605d](https://linux-hardware.org/?probe=b7b43a605d) | Aug 12, 2021 |
| Toshiba       | Satellite L505D             | [8560337601](https://linux-hardware.org/?probe=8560337601) | Aug 12, 2021 |
| Acer          | Aspire 8920                 | [9ac1d0a471](https://linux-hardware.org/?probe=9ac1d0a471) | Aug 12, 2021 |
| Lenovo        | Z50-70 20354                | [1eba114602](https://linux-hardware.org/?probe=1eba114602) | Aug 11, 2021 |
| Lenovo        | Z50-70 20354                | [a31c1f0fda](https://linux-hardware.org/?probe=a31c1f0fda) | Aug 11, 2021 |
| HP            | Pavilion dv6700             | [ebf6b956cb](https://linux-hardware.org/?probe=ebf6b956cb) | Aug 10, 2021 |
| Apple         | MacBookPro7,1               | [da4107ffc3](https://linux-hardware.org/?probe=da4107ffc3) | Aug 10, 2021 |
| Samsung       | RV419                       | [66823b7d4d](https://linux-hardware.org/?probe=66823b7d4d) | Aug 10, 2021 |
| ASUSTek       | X51R                        | [1d1aad3900](https://linux-hardware.org/?probe=1d1aad3900) | Aug 08, 2021 |
| Dell          | Inspiron 3521               | [d0814fcb72](https://linux-hardware.org/?probe=d0814fcb72) | Aug 08, 2021 |
| Acer          | Extensa 5220                | [c2e39c0d39](https://linux-hardware.org/?probe=c2e39c0d39) | Aug 07, 2021 |
| HP            | Compaq 2510p                | [ea3c7d2fe2](https://linux-hardware.org/?probe=ea3c7d2fe2) | Aug 07, 2021 |
| HP            | Compaq 2510p                | [31449a4b42](https://linux-hardware.org/?probe=31449a4b42) | Aug 07, 2021 |
| Dell          | Inspiron 3421               | [dc8767625f](https://linux-hardware.org/?probe=dc8767625f) | Aug 07, 2021 |
| Acer          | Extensa 5220                | [b0da636247](https://linux-hardware.org/?probe=b0da636247) | Aug 07, 2021 |
| Dell          | Inspiron 3421               | [52f396865d](https://linux-hardware.org/?probe=52f396865d) | Aug 07, 2021 |
| Positivo      | CHT14B                      | [c8d89d2cde](https://linux-hardware.org/?probe=c8d89d2cde) | Aug 06, 2021 |
| Acer          | Aspire E5-575               | [9d4f584337](https://linux-hardware.org/?probe=9d4f584337) | Aug 06, 2021 |
| Lenovo        | ThinkPad T61 6468AE2        | [58f1efa783](https://linux-hardware.org/?probe=58f1efa783) | Aug 06, 2021 |
| Dell          | Latitude E5500              | [0688139a45](https://linux-hardware.org/?probe=0688139a45) | Aug 04, 2021 |
| Lenovo        | ThinkPad T61 6465CTO        | [d93258840e](https://linux-hardware.org/?probe=d93258840e) | Aug 04, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [1b40831803](https://linux-hardware.org/?probe=1b40831803) | Aug 04, 2021 |
| Acer          | Extensa 5220                | [e8b82c756d](https://linux-hardware.org/?probe=e8b82c756d) | Jul 26, 2021 |
| Acer          | Extensa 5220                | [82ae089b21](https://linux-hardware.org/?probe=82ae089b21) | Jul 26, 2021 |
| Medion        | Unknown                     | [021ba4d5b5](https://linux-hardware.org/?probe=021ba4d5b5) | Jul 25, 2021 |
| Medion        | Unknown                     | [e9c5e99e0b](https://linux-hardware.org/?probe=e9c5e99e0b) | Jul 25, 2021 |
| HP            | Compaq CQ58                 | [96df68c59e](https://linux-hardware.org/?probe=96df68c59e) | Jul 25, 2021 |
| Dell          | Latitude 5480               | [1b32299688](https://linux-hardware.org/?probe=1b32299688) | Jul 24, 2021 |
| HP            | Notebook                    | [71959b30db](https://linux-hardware.org/?probe=71959b30db) | Jul 23, 2021 |
| Samsung       | 355V4C/355V4X/355V5C/355... | [8d72c96d15](https://linux-hardware.org/?probe=8d72c96d15) | Jul 23, 2021 |
| Dell          | Inspiron N5010              | [4a76f84bf5](https://linux-hardware.org/?probe=4a76f84bf5) | Jul 22, 2021 |
| Lenovo        | Y70-70 Touch 80DU           | [36fb0f3df5](https://linux-hardware.org/?probe=36fb0f3df5) | Jul 16, 2021 |
| Sony          | SVE14A2V1EW                 | [2b1ce53eca](https://linux-hardware.org/?probe=2b1ce53eca) | Jul 16, 2021 |
| HP            | 250 G7 Notebook PC          | [846febb191](https://linux-hardware.org/?probe=846febb191) | Jul 14, 2021 |
| HP            | EliteBook 820 G2            | [8c035c3e82](https://linux-hardware.org/?probe=8c035c3e82) | Jul 14, 2021 |
| ASUSTek       | G50V                        | [ec1ddd4644](https://linux-hardware.org/?probe=ec1ddd4644) | Jul 11, 2021 |
| Samsung       | N145P/N250P/N260P           | [e60ff3401a](https://linux-hardware.org/?probe=e60ff3401a) | Jul 11, 2021 |
| Sony          | VPCEH16EA                   | [189be303f7](https://linux-hardware.org/?probe=189be303f7) | Jul 09, 2021 |
| Sony          | VPCEH16EA                   | [c93e5aee87](https://linux-hardware.org/?probe=c93e5aee87) | Jul 08, 2021 |
| HP            | 255 G7 Notebook PC          | [b543fedfd0](https://linux-hardware.org/?probe=b543fedfd0) | Jul 08, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [508ac5b4d5](https://linux-hardware.org/?probe=508ac5b4d5) | Jul 07, 2021 |
| Sony          | VPCSB25FB                   | [6de928a758](https://linux-hardware.org/?probe=6de928a758) | Jul 07, 2021 |
| Gateway       | MX8711                      | [185e86b37e](https://linux-hardware.org/?probe=185e86b37e) | Jul 06, 2021 |
| Acer          | Aspire A515-45              | [42249c6e47](https://linux-hardware.org/?probe=42249c6e47) | Jul 02, 2021 |
| HP            | Pavilion dv6700             | [93c6a703a7](https://linux-hardware.org/?probe=93c6a703a7) | Jun 27, 2021 |
| HP            | Pavilion dv6700             | [f7e407b14c](https://linux-hardware.org/?probe=f7e407b14c) | Jun 27, 2021 |
| ASUSTek       | K54HR                       | [8fcbeb49c1](https://linux-hardware.org/?probe=8fcbeb49c1) | Jun 26, 2021 |
| Sony          | VPCSB16FG                   | [ead356e548](https://linux-hardware.org/?probe=ead356e548) | Jun 24, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f3430744d8](https://linux-hardware.org/?probe=f3430744d8) | Jun 24, 2021 |
| HP            | Laptop 15-da0xxx            | [77fba11f44](https://linux-hardware.org/?probe=77fba11f44) | Jun 21, 2021 |
| Lenovo        | G40-30 80FY                 | [114ba38c36](https://linux-hardware.org/?probe=114ba38c36) | Jun 20, 2021 |
| Lenovo        | G40-30 80FY                 | [0cb7e73af9](https://linux-hardware.org/?probe=0cb7e73af9) | Jun 19, 2021 |
| Dell          | Precision 7520              | [9b19302ca7](https://linux-hardware.org/?probe=9b19302ca7) | Jun 18, 2021 |
| Dell          | Inspiron N4010              | [d385bb7617](https://linux-hardware.org/?probe=d385bb7617) | Jun 15, 2021 |
| Dell          | Inspiron N4010              | [be79fbc95c](https://linux-hardware.org/?probe=be79fbc95c) | Jun 15, 2021 |
| Samsung       | N150/N210/N220              | [8e03d52f53](https://linux-hardware.org/?probe=8e03d52f53) | Jun 12, 2021 |
| Lenovo        | Unknown                     | [108d3cba46](https://linux-hardware.org/?probe=108d3cba46) | Jun 10, 2021 |
| HP            | Stream Notebook             | [806c24449c](https://linux-hardware.org/?probe=806c24449c) | Jun 09, 2021 |
| HCL Infosy... | HCL ME Laptop               | [0aaf1b69bc](https://linux-hardware.org/?probe=0aaf1b69bc) | Jun 08, 2021 |
| Dell          | Latitude E6520              | [04a7f10801](https://linux-hardware.org/?probe=04a7f10801) | Jun 08, 2021 |
| Lenovo        | G40-30 80FY                 | [b2fe748178](https://linux-hardware.org/?probe=b2fe748178) | Jun 08, 2021 |
| Sony          | VGN-BX51VN                  | [debf4b3290](https://linux-hardware.org/?probe=debf4b3290) | Jun 06, 2021 |
| ASUSTek       | Q524UQ                      | [442c1c8b06](https://linux-hardware.org/?probe=442c1c8b06) | Jun 05, 2021 |
| HP            | Pavilion dv5                | [94cfdbc88f](https://linux-hardware.org/?probe=94cfdbc88f) | Jun 03, 2021 |
| Unknown       | Unknown                     | [3ce5819b57](https://linux-hardware.org/?probe=3ce5819b57) | Jun 02, 2021 |
| Apple         | MacBookPro12,1              | [f7f5736b13](https://linux-hardware.org/?probe=f7f5736b13) | Jun 01, 2021 |
| Sony          | VGN-BX51VN                  | [055903703c](https://linux-hardware.org/?probe=055903703c) | Jun 01, 2021 |
| Toshiba       | Satellite M70               | [67580c50df](https://linux-hardware.org/?probe=67580c50df) | Jun 01, 2021 |
| Acer          | Aspire 3100                 | [d38f5b09d2](https://linux-hardware.org/?probe=d38f5b09d2) | Jun 01, 2021 |
| Acer          | Aspire 3100                 | [fbcd23ac31](https://linux-hardware.org/?probe=fbcd23ac31) | May 31, 2021 |
| Toshiba       | Satellite P300              | [feb13460e8](https://linux-hardware.org/?probe=feb13460e8) | May 30, 2021 |
| Toshiba       | Satellite P300              | [8b5034adc9](https://linux-hardware.org/?probe=8b5034adc9) | May 30, 2021 |
| Lenovo        | G40-30 80FY                 | [eb9aaa55ea](https://linux-hardware.org/?probe=eb9aaa55ea) | May 30, 2021 |
| Dell          | Inspiron 3521               | [9fc71241e6](https://linux-hardware.org/?probe=9fc71241e6) | May 26, 2021 |
| Lenovo        | G40-30 80FY                 | [0c3e0e8293](https://linux-hardware.org/?probe=0c3e0e8293) | May 26, 2021 |
| ARIMA         | W351UI                      | [6cbffa9177](https://linux-hardware.org/?probe=6cbffa9177) | May 25, 2021 |
| Dell          | Latitude D520               | [7a817a0426](https://linux-hardware.org/?probe=7a817a0426) | May 25, 2021 |
| HP            | Pavilion dv6700             | [b30d13bbba](https://linux-hardware.org/?probe=b30d13bbba) | May 25, 2021 |
| ASUSTek       | UX31A                       | [edeed3b99b](https://linux-hardware.org/?probe=edeed3b99b) | May 23, 2021 |
| ASUSTek       | UX31A                       | [7f750ead39](https://linux-hardware.org/?probe=7f750ead39) | May 23, 2021 |
| Google        | Candy                       | [f6b5b1fd81](https://linux-hardware.org/?probe=f6b5b1fd81) | May 23, 2021 |
| ASUSTek       | X540YA                      | [369ebd51b8](https://linux-hardware.org/?probe=369ebd51b8) | May 23, 2021 |
| ASUSTek       | F5N                         | [414786c3d5](https://linux-hardware.org/?probe=414786c3d5) | May 22, 2021 |
| Dell          | Inspiron 3521               | [ef65e1a0f7](https://linux-hardware.org/?probe=ef65e1a0f7) | May 21, 2021 |
| Dell          | Latitude E7240              | [9e790ba3f0](https://linux-hardware.org/?probe=9e790ba3f0) | May 21, 2021 |
| HP            | 255 G5                      | [cbd6a96f91](https://linux-hardware.org/?probe=cbd6a96f91) | May 20, 2021 |
| ASUSTek       | T100TA                      | [bca3c06314](https://linux-hardware.org/?probe=bca3c06314) | May 20, 2021 |
| ASUSTek       | T100TA                      | [f232d2395d](https://linux-hardware.org/?probe=f232d2395d) | May 19, 2021 |
| Dell          | G5 5587                     | [39be80ad79](https://linux-hardware.org/?probe=39be80ad79) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [d9592ead1e](https://linux-hardware.org/?probe=d9592ead1e) | May 18, 2021 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [bc6920fa56](https://linux-hardware.org/?probe=bc6920fa56) | May 16, 2021 |
| HP            | 435                         | [65bbde1e13](https://linux-hardware.org/?probe=65bbde1e13) | May 16, 2021 |
| HP            | 435                         | [fe5a82cf02](https://linux-hardware.org/?probe=fe5a82cf02) | May 16, 2021 |
| ASUSTek       | K54C                        | [af86f8b1ed](https://linux-hardware.org/?probe=af86f8b1ed) | May 14, 2021 |
| Dell          | Inspiron 14-3467            | [511f638394](https://linux-hardware.org/?probe=511f638394) | May 14, 2021 |
| Acer          | V5-131                      | [d78c3cc207](https://linux-hardware.org/?probe=d78c3cc207) | May 14, 2021 |
| Dell          | Inspiron 1525               | [22f4b67d9b](https://linux-hardware.org/?probe=22f4b67d9b) | May 12, 2021 |
| Dell          | Inspiron 7520               | [fdf52a6676](https://linux-hardware.org/?probe=fdf52a6676) | May 11, 2021 |
| Samsung       | RF712                       | [a3624b29fa](https://linux-hardware.org/?probe=a3624b29fa) | May 11, 2021 |
| Samsung       | RF712                       | [652fb28adb](https://linux-hardware.org/?probe=652fb28adb) | May 11, 2021 |
| HP            | ProBook 4510s               | [dbdd169cb4](https://linux-hardware.org/?probe=dbdd169cb4) | May 10, 2021 |
| Dell          | Inspiron 14-3467            | [2fd207a33d](https://linux-hardware.org/?probe=2fd207a33d) | May 10, 2021 |
| Fujitsu       | FMVNF40UK                   | [8648b42278](https://linux-hardware.org/?probe=8648b42278) | May 09, 2021 |
| Dell          | Inspiron 14-3467            | [173baf5fdb](https://linux-hardware.org/?probe=173baf5fdb) | May 09, 2021 |
| Toshiba       | Satellite P200              | [5fff6be5f0](https://linux-hardware.org/?probe=5fff6be5f0) | May 05, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | [0c612ea2a3](https://linux-hardware.org/?probe=0c612ea2a3) | May 04, 2021 |
| Lenovo        | 406822U                     | [68080373ce](https://linux-hardware.org/?probe=68080373ce) | May 03, 2021 |
| Lenovo        | 406822U                     | [5d498a42cc](https://linux-hardware.org/?probe=5d498a42cc) | May 03, 2021 |
| ASUSTek       | X540SA                      | [0f79fb429b](https://linux-hardware.org/?probe=0f79fb429b) | May 02, 2021 |
| Acer          | Aspire 5538                 | [b01066567a](https://linux-hardware.org/?probe=b01066567a) | May 02, 2021 |
| Acer          | Aspire 5538                 | [39c929202c](https://linux-hardware.org/?probe=39c929202c) | May 02, 2021 |
| Acer          | AOD255E                     | [202573d3f1](https://linux-hardware.org/?probe=202573d3f1) | May 02, 2021 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [21666fb8b5](https://linux-hardware.org/?probe=21666fb8b5) | May 01, 2021 |
| TrekStor      | Notebook Slim S130          | [3ee0251799](https://linux-hardware.org/?probe=3ee0251799) | May 01, 2021 |
| HP            | ENVY Notebook               | [00123e7e27](https://linux-hardware.org/?probe=00123e7e27) | May 01, 2021 |
| Positivo      | S14CT01                     | [d6ad6f67a7](https://linux-hardware.org/?probe=d6ad6f67a7) | Apr 30, 2021 |
| Dell          | Latitude D630               | [ce166d946d](https://linux-hardware.org/?probe=ce166d946d) | Apr 30, 2021 |
| NEC Comput... | PC-VY25AACZ9                | [dc22e810b4](https://linux-hardware.org/?probe=dc22e810b4) | Apr 29, 2021 |
| Itautec       | Infoway                     | [01e1f5151c](https://linux-hardware.org/?probe=01e1f5151c) | Apr 28, 2021 |
| Fujitsu       | LIFEBOOK U772               | [e2c74983d8](https://linux-hardware.org/?probe=e2c74983d8) | Apr 28, 2021 |
| Lenovo        | ThinkPad X131e 3372A14      | [3c79681783](https://linux-hardware.org/?probe=3c79681783) | Apr 26, 2021 |
| Acer          | Aspire E5-523               | [7acc074ffd](https://linux-hardware.org/?probe=7acc074ffd) | Apr 26, 2021 |
| Acer          | Aspire E5-523               | [349b8662d9](https://linux-hardware.org/?probe=349b8662d9) | Apr 26, 2021 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | [4cffaa3991](https://linux-hardware.org/?probe=4cffaa3991) | Apr 23, 2021 |
| Acer          | Unknown                     | [cd6b0eabe2](https://linux-hardware.org/?probe=cd6b0eabe2) | Apr 23, 2021 |
| Acer          | Aspire 5333                 | [c6227d5004](https://linux-hardware.org/?probe=c6227d5004) | Apr 23, 2021 |
| Toshiba       | IS 1422                     | [f52456fce9](https://linux-hardware.org/?probe=f52456fce9) | Apr 22, 2021 |
| Toshiba       | IS 1422                     | [9443f68502](https://linux-hardware.org/?probe=9443f68502) | Apr 22, 2021 |
| Samsung       | 550XCJ/550XCR               | [2a2a56b6d4](https://linux-hardware.org/?probe=2a2a56b6d4) | Apr 22, 2021 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | [d8340c053a](https://linux-hardware.org/?probe=d8340c053a) | Apr 22, 2021 |
| Packard Be... | EasyNote_BU45               | [7d3e06e670](https://linux-hardware.org/?probe=7d3e06e670) | Apr 21, 2021 |
| Packard Be... | EasyNote_BU45               | [c97faabab8](https://linux-hardware.org/?probe=c97faabab8) | Apr 21, 2021 |
| Dell          | Latitude D620               | [116568909e](https://linux-hardware.org/?probe=116568909e) | Apr 19, 2021 |
| Dell          | Latitude D520               | [4e8b58ab28](https://linux-hardware.org/?probe=4e8b58ab28) | Apr 16, 2021 |
| Acer          | Aspire 5333                 | [2171d74173](https://linux-hardware.org/?probe=2171d74173) | Apr 15, 2021 |
| Acer          | Aspire 5333                 | [dd4fee2ece](https://linux-hardware.org/?probe=dd4fee2ece) | Apr 15, 2021 |
| Toshiba       | Satellite C55-A             | [6670c58f24](https://linux-hardware.org/?probe=6670c58f24) | Apr 15, 2021 |
| Dell          | Inspiron 5759               | [7fcec2352e](https://linux-hardware.org/?probe=7fcec2352e) | Apr 15, 2021 |
| HP            | Pavilion dv5                | [901dd6f4bc](https://linux-hardware.org/?probe=901dd6f4bc) | Apr 14, 2021 |
| Toshiba       | Satellite C55-A             | [7862f9a6e6](https://linux-hardware.org/?probe=7862f9a6e6) | Apr 14, 2021 |
| Toshiba       | Satellite P200              | [f6b3c134f2](https://linux-hardware.org/?probe=f6b3c134f2) | Apr 11, 2021 |
| HP            | EliteBook 850 G5            | [8351e652e0](https://linux-hardware.org/?probe=8351e652e0) | Apr 11, 2021 |
| Dell          | Latitude D620               | [f0eb74cd27](https://linux-hardware.org/?probe=f0eb74cd27) | Apr 11, 2021 |
| Dell          | Latitude D620               | [599e543d6b](https://linux-hardware.org/?probe=599e543d6b) | Apr 11, 2021 |
| NEC Comput... | PC-VY25AACZ9                | [24f7a90612](https://linux-hardware.org/?probe=24f7a90612) | Apr 10, 2021 |
| Lenovo        | ThinkPad W540 20BHS1MX00    | [762a1d15ab](https://linux-hardware.org/?probe=762a1d15ab) | Apr 09, 2021 |
| Toshiba       | dynabook R731/E             | [108510a130](https://linux-hardware.org/?probe=108510a130) | Apr 08, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [cdf6743f68](https://linux-hardware.org/?probe=cdf6743f68) | Apr 08, 2021 |
| Positivo      | Mobile                      | [340616710c](https://linux-hardware.org/?probe=340616710c) | Apr 07, 2021 |
| Toshiba       | QOSMIO X300                 | [7f3b22129c](https://linux-hardware.org/?probe=7f3b22129c) | Apr 07, 2021 |
| Toshiba       | QOSMIO X300                 | [c1e66d512d](https://linux-hardware.org/?probe=c1e66d512d) | Apr 07, 2021 |
| HP            | 15                          | [69d2aa2538](https://linux-hardware.org/?probe=69d2aa2538) | Apr 05, 2021 |
| HP            | EliteBook Folio 9480m       | [c878c10e7b](https://linux-hardware.org/?probe=c878c10e7b) | Apr 03, 2021 |
| Gigabyte      | AERO 15-SA                  | [b162082414](https://linux-hardware.org/?probe=b162082414) | Apr 03, 2021 |
| Compaq        | Presario CQ-17              | [d1ae1543d9](https://linux-hardware.org/?probe=d1ae1543d9) | Apr 02, 2021 |
| HP            | Stream Notebook PC 11       | [a2a25ee9ac](https://linux-hardware.org/?probe=a2a25ee9ac) | Apr 02, 2021 |
| HP            | Stream Notebook PC 11       | [bb9c9dc740](https://linux-hardware.org/?probe=bb9c9dc740) | Apr 01, 2021 |
| HP            | Laptop 15-dw1xxx            | [276153c011](https://linux-hardware.org/?probe=276153c011) | Mar 31, 2021 |
| HP            | Laptop 15-dw1xxx            | [7dc5cad98d](https://linux-hardware.org/?probe=7dc5cad98d) | Mar 31, 2021 |
| Gigabyte      | AERO 15-SA                  | [26957c118d](https://linux-hardware.org/?probe=26957c118d) | Mar 30, 2021 |
| Toshiba       | QOSMIO F50                  | [d9d565847f](https://linux-hardware.org/?probe=d9d565847f) | Mar 29, 2021 |
| HP            | ProBook 4540s               | [94b1064fc6](https://linux-hardware.org/?probe=94b1064fc6) | Mar 28, 2021 |
| HP            | ProBook 4540s               | [c6e6b05536](https://linux-hardware.org/?probe=c6e6b05536) | Mar 28, 2021 |
| ASUSTek       | X200CA                      | [fd66b80491](https://linux-hardware.org/?probe=fd66b80491) | Mar 28, 2021 |
| Gigabyte      | AERO 15-SA                  | [536dfb993f](https://linux-hardware.org/?probe=536dfb993f) | Mar 28, 2021 |
| Lenovo        | ThinkPad T430s 2356DH2      | [86d756fb89](https://linux-hardware.org/?probe=86d756fb89) | Mar 27, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20T8S... | [327b8352df](https://linux-hardware.org/?probe=327b8352df) | Mar 27, 2021 |
| HP            | Mini 110-1100               | [05039f09e2](https://linux-hardware.org/?probe=05039f09e2) | Mar 26, 2021 |
| HP            | Mini 110-1100               | [5192a10f03](https://linux-hardware.org/?probe=5192a10f03) | Mar 26, 2021 |
| ASUSTek       | 1011PX                      | [3d23090e46](https://linux-hardware.org/?probe=3d23090e46) | Mar 26, 2021 |
| HP            | Compaq Presario CQ61        | [58db0eef1f](https://linux-hardware.org/?probe=58db0eef1f) | Mar 25, 2021 |
| Lenovo        | ThinkPad L470 20J4000LGE    | [125911ba8d](https://linux-hardware.org/?probe=125911ba8d) | Mar 21, 2021 |
| Apple         | MacBookPro5,4               | [e1ff6cd3c6](https://linux-hardware.org/?probe=e1ff6cd3c6) | Mar 20, 2021 |
| ASUSTek       | X555LD                      | [cf0c496200](https://linux-hardware.org/?probe=cf0c496200) | Mar 20, 2021 |
| HP            | ProBook 470 G1              | [7358a0ab88](https://linux-hardware.org/?probe=7358a0ab88) | Mar 20, 2021 |
| HP            | ProBook 470 G1              | [9a754ec32f](https://linux-hardware.org/?probe=9a754ec32f) | Mar 20, 2021 |
| Lenovo        | ThinkPad T420 41786UU       | [3965832137](https://linux-hardware.org/?probe=3965832137) | Mar 20, 2021 |
| Dell          | Latitude D610               | [faaf3b4f3d](https://linux-hardware.org/?probe=faaf3b4f3d) | Mar 18, 2021 |
| Panasonic     | CF-31JEGAX1M                | [4636e611d8](https://linux-hardware.org/?probe=4636e611d8) | Mar 14, 2021 |
| Lenovo        | ThinkPad Edge E531 68852... | [9707772e02](https://linux-hardware.org/?probe=9707772e02) | Mar 13, 2021 |
| Acer          | Aspire 5610Z                | [ba43bff53e](https://linux-hardware.org/?probe=ba43bff53e) | Mar 13, 2021 |
| ASUSTek       | E402SA                      | [eec3171b5f](https://linux-hardware.org/?probe=eec3171b5f) | Mar 13, 2021 |
| ASUSTek       | TUF Gaming FX505DU_FX505... | [85703241b5](https://linux-hardware.org/?probe=85703241b5) | Mar 13, 2021 |
| MSI           | GX60 1AC                    | [774db4f685](https://linux-hardware.org/?probe=774db4f685) | Mar 12, 2021 |
| Hometech      | ELITE TAB 10                | [8bfad5d181](https://linux-hardware.org/?probe=8bfad5d181) | Mar 09, 2021 |
| Fujitsu       | LIFEBOOK AH531/GFO          | [8a0395042b](https://linux-hardware.org/?probe=8a0395042b) | Mar 08, 2021 |
| Toshiba       | Satellite P300-17Q          | [72b5282501](https://linux-hardware.org/?probe=72b5282501) | Mar 08, 2021 |
| Gateway       | NV55C                       | [3f5377a2de](https://linux-hardware.org/?probe=3f5377a2de) | Mar 08, 2021 |
| Acer          | Aspire 5735                 | [cde827bd2e](https://linux-hardware.org/?probe=cde827bd2e) | Mar 07, 2021 |
| Acer          | Aspire 5735                 | [9730b9273d](https://linux-hardware.org/?probe=9730b9273d) | Mar 07, 2021 |
| HP            | 255 G7 Notebook PC          | [f5600011bb](https://linux-hardware.org/?probe=f5600011bb) | Mar 05, 2021 |
| HP            | 255 G7 Notebook PC          | [19e8d1a155](https://linux-hardware.org/?probe=19e8d1a155) | Mar 05, 2021 |
| Toshiba       | Satellite U920t             | [26b9e489aa](https://linux-hardware.org/?probe=26b9e489aa) | Mar 04, 2021 |
| Toshiba       | Satellite NB10t-A           | [c1c084e42c](https://linux-hardware.org/?probe=c1c084e42c) | Feb 28, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | [dfc0744775](https://linux-hardware.org/?probe=dfc0744775) | Feb 28, 2021 |
| Multilaser    | PC024                       | [abaddb333b](https://linux-hardware.org/?probe=abaddb333b) | Feb 27, 2021 |
| Multilaser    | PC024                       | [54e46489ac](https://linux-hardware.org/?probe=54e46489ac) | Feb 27, 2021 |
| HP            | Compaq 6510b (GR690ET#AB... | [b9b8fa550a](https://linux-hardware.org/?probe=b9b8fa550a) | Feb 26, 2021 |
| HP            | Compaq 6510b (GR690ET#AB... | [4529dc90b2](https://linux-hardware.org/?probe=4529dc90b2) | Feb 26, 2021 |
| ASUSTek       | X555LD                      | [665cf4701a](https://linux-hardware.org/?probe=665cf4701a) | Feb 25, 2021 |
| Dell          | Inspiron 3543               | [cfc4c1a529](https://linux-hardware.org/?probe=cfc4c1a529) | Feb 24, 2021 |
| ASUSTek       | X751SJ                      | [81295695f3](https://linux-hardware.org/?probe=81295695f3) | Feb 24, 2021 |
| Dell          | Inspiron 3543               | [6b53f592ed](https://linux-hardware.org/?probe=6b53f592ed) | Feb 22, 2021 |
| HP            | ZBook 17 G2                 | [7213996a6e](https://linux-hardware.org/?probe=7213996a6e) | Feb 22, 2021 |
| Samsung       | 370E4K                      | [9d25cf824e](https://linux-hardware.org/?probe=9d25cf824e) | Feb 20, 2021 |
| Dell          | Inspiron 7737               | [ffaf611204](https://linux-hardware.org/?probe=ffaf611204) | Feb 20, 2021 |
| ASUSTek       | K52N                        | [0139461f57](https://linux-hardware.org/?probe=0139461f57) | Feb 19, 2021 |
| ASUSTek       | U36SD                       | [981c7e8da7](https://linux-hardware.org/?probe=981c7e8da7) | Feb 19, 2021 |
| ASUSTek       | X550ZA                      | [503250e6f1](https://linux-hardware.org/?probe=503250e6f1) | Feb 19, 2021 |
| HP            | 255 G5                      | [2ffdcec174](https://linux-hardware.org/?probe=2ffdcec174) | Feb 19, 2021 |
| Dell          | XPS 13 9333                 | [0166a2e7b9](https://linux-hardware.org/?probe=0166a2e7b9) | Feb 17, 2021 |
| Dell          | XPS 13 9333                 | [4e08aeb5c5](https://linux-hardware.org/?probe=4e08aeb5c5) | Feb 17, 2021 |
| HP            | Compaq Presario CQ61        | [e72ebb6663](https://linux-hardware.org/?probe=e72ebb6663) | Feb 14, 2021 |
| Toshiba       | Satellite L855              | [941b946e5e](https://linux-hardware.org/?probe=941b946e5e) | Feb 14, 2021 |
| Toshiba       | Satellite L855              | [4cfe29288e](https://linux-hardware.org/?probe=4cfe29288e) | Feb 14, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [622900874e](https://linux-hardware.org/?probe=622900874e) | Feb 14, 2021 |
| HP            | Pavilion dv6000 (RR398EA... | [2b5732689b](https://linux-hardware.org/?probe=2b5732689b) | Feb 13, 2021 |
| HP            | Pavilion dv6000 (RR398EA... | [0005b66219](https://linux-hardware.org/?probe=0005b66219) | Feb 13, 2021 |
| HP            | ENVY 15                     | [ab6ef5e4cf](https://linux-hardware.org/?probe=ab6ef5e4cf) | Feb 12, 2021 |
| HP            | Compaq Presario CQ61        | [bcf179fa51](https://linux-hardware.org/?probe=bcf179fa51) | Feb 12, 2021 |
| ASUSTek       | X510UAR                     | [e194fe9742](https://linux-hardware.org/?probe=e194fe9742) | Feb 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [c7c4c6fe88](https://linux-hardware.org/?probe=c7c4c6fe88) | Feb 11, 2021 |
| Lenovo        | ThinkPad T440s 20ARS1070... | [b14a3d0adb](https://linux-hardware.org/?probe=b14a3d0adb) | Feb 09, 2021 |
| NEC Comput... | PC-VY12FBHEW                | [c65bc992c6](https://linux-hardware.org/?probe=c65bc992c6) | Feb 08, 2021 |
| Dell          | Inspiron 1012               | [e5ec198a6d](https://linux-hardware.org/?probe=e5ec198a6d) | Feb 07, 2021 |
| HP            | Stream Laptop 11-y0XX       | [1a6227c6cf](https://linux-hardware.org/?probe=1a6227c6cf) | Feb 07, 2021 |
| Toshiba       | Satellite Pro L550          | [b6870f2fea](https://linux-hardware.org/?probe=b6870f2fea) | Feb 07, 2021 |
| Lenovo        | ThinkPad R61 8943DKG        | [fd7beeb674](https://linux-hardware.org/?probe=fd7beeb674) | Feb 06, 2021 |
| Lenovo        | ThinkPad R61 8943DKG        | [6a3c7e3263](https://linux-hardware.org/?probe=6a3c7e3263) | Feb 06, 2021 |
| Acer          | TravelMate 6592             | [9b2c049705](https://linux-hardware.org/?probe=9b2c049705) | Feb 06, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | [067995d50f](https://linux-hardware.org/?probe=067995d50f) | Feb 05, 2021 |
| Unknown       | ARCELIK ANB 573 D SR        | [7ef8639d95](https://linux-hardware.org/?probe=7ef8639d95) | Feb 04, 2021 |
| Unknown       | ARCELIK ANB 573 D SR        | [70b60f77cc](https://linux-hardware.org/?probe=70b60f77cc) | Feb 04, 2021 |
| Lenovo        | G560 0679                   | [ebf2298ba0](https://linux-hardware.org/?probe=ebf2298ba0) | Feb 04, 2021 |
| Dell          | Latitude E6400              | [99e1f46388](https://linux-hardware.org/?probe=99e1f46388) | Feb 03, 2021 |
| HP            | EliteBook 2560p             | [f741035d0d](https://linux-hardware.org/?probe=f741035d0d) | Feb 02, 2021 |
| Dell          | Latitude D520               | [038841ada5](https://linux-hardware.org/?probe=038841ada5) | Feb 02, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [2dd10bb86f](https://linux-hardware.org/?probe=2dd10bb86f) | Feb 01, 2021 |
| HP            | G42                         | [532d273aec](https://linux-hardware.org/?probe=532d273aec) | Feb 01, 2021 |
| Lenovo        | ThinkPad Edge E531 68852... | [18ceaaebaf](https://linux-hardware.org/?probe=18ceaaebaf) | Feb 01, 2021 |
| Lenovo        | ThinkPad Edge E531 68852... | [90149b2d99](https://linux-hardware.org/?probe=90149b2d99) | Feb 01, 2021 |
| ASUSTek       | X555LD                      | [eb3be3f63f](https://linux-hardware.org/?probe=eb3be3f63f) | Jan 31, 2021 |
| Sony          | VGN-AR630E                  | [2e155fc628](https://linux-hardware.org/?probe=2e155fc628) | Jan 31, 2021 |
| Panasonic     | CF-30K3PAZN2                | [9a9c09f250](https://linux-hardware.org/?probe=9a9c09f250) | Jan 30, 2021 |
| Panasonic     | CF-30K3PAZN2                | [a1b4116c85](https://linux-hardware.org/?probe=a1b4116c85) | Jan 30, 2021 |
| ASUSTek       | U36SD                       | [5267c17fbb](https://linux-hardware.org/?probe=5267c17fbb) | Jan 30, 2021 |
| HP            | Pavilion zd8000 (PW934EA... | [640a4d1741](https://linux-hardware.org/?probe=640a4d1741) | Jan 29, 2021 |
| Olidata       | U40SI1                      | [60dd97276a](https://linux-hardware.org/?probe=60dd97276a) | Jan 28, 2021 |
| Olidata       | U40SI1                      | [cca9468e85](https://linux-hardware.org/?probe=cca9468e85) | Jan 28, 2021 |
| ASUSTek       | U36SD                       | [15288996d1](https://linux-hardware.org/?probe=15288996d1) | Jan 28, 2021 |
| Lenovo        | ThinkPad X240 20AM006KMN    | [7c40d08353](https://linux-hardware.org/?probe=7c40d08353) | Jan 28, 2021 |
| Acer          | Aspire E1-570G              | [19e6d6afd7](https://linux-hardware.org/?probe=19e6d6afd7) | Jan 28, 2021 |
| Toshiba       | Satellite L500              | [f9341665f3](https://linux-hardware.org/?probe=f9341665f3) | Jan 27, 2021 |
| Dell          | Latitude E5470              | [72db68119a](https://linux-hardware.org/?probe=72db68119a) | Jan 27, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [00f0257410](https://linux-hardware.org/?probe=00f0257410) | Jan 27, 2021 |
| HP            | ZBook 17 G6                 | [63c3d95bd5](https://linux-hardware.org/?probe=63c3d95bd5) | Jan 27, 2021 |
| Dell          | Latitude D630               | [efc4256a09](https://linux-hardware.org/?probe=efc4256a09) | Jan 26, 2021 |
| Dell          | Latitude E6400              | [91be1b1bd7](https://linux-hardware.org/?probe=91be1b1bd7) | Jan 26, 2021 |
| Acer          | Aspire E1-570G              | [f8f4880823](https://linux-hardware.org/?probe=f8f4880823) | Jan 26, 2021 |
| Toshiba       | Satellite L635              | [ca6d27fd9c](https://linux-hardware.org/?probe=ca6d27fd9c) | Jan 24, 2021 |
| ASUSTek       | ZenBook UX433FN_UX433FN     | [158b3578e3](https://linux-hardware.org/?probe=158b3578e3) | Jan 23, 2021 |
| Unknown       | Unknown                     | [0c6628ea31](https://linux-hardware.org/?probe=0c6628ea31) | Jan 23, 2021 |
| Dell          | Latitude E6400              | [fc052ebe8f](https://linux-hardware.org/?probe=fc052ebe8f) | Jan 23, 2021 |
| Apple         | MacBookPro11,1              | [b27a2d92e2](https://linux-hardware.org/?probe=b27a2d92e2) | Jan 22, 2021 |
| Sony          | SVE14A2V1EW                 | [baaf829145](https://linux-hardware.org/?probe=baaf829145) | Jan 20, 2021 |
| Dell          | Latitude E5430 non-vPro     | [db6d4d3deb](https://linux-hardware.org/?probe=db6d4d3deb) | Jan 20, 2021 |
| HP            | ProBook 6560b               | [4771c30f72](https://linux-hardware.org/?probe=4771c30f72) | Jan 18, 2021 |
| Lenovo        | ThinkPad X220 4290NC9       | [f90fbc6c88](https://linux-hardware.org/?probe=f90fbc6c88) | Jan 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | [1dfeaa1b83](https://linux-hardware.org/?probe=1dfeaa1b83) | Jan 17, 2021 |
| Toshiba       | Satellite L850-1HP          | [1e0aa7f353](https://linux-hardware.org/?probe=1e0aa7f353) | Jan 17, 2021 |
| Toshiba       | Satellite U920t             | [566f573caf](https://linux-hardware.org/?probe=566f573caf) | Jan 17, 2021 |
| Itautec       | Infoway a7420               | [d32d9bf816](https://linux-hardware.org/?probe=d32d9bf816) | Jan 16, 2021 |
| Quanta        | MW1/HW1                     | [ebab0a47f8](https://linux-hardware.org/?probe=ebab0a47f8) | Jan 16, 2021 |
| Unknown       | Unknown                     | [1fddcd5f95](https://linux-hardware.org/?probe=1fddcd5f95) | Jan 15, 2021 |
| Lenovo        | V145-15AST 81MT             | [ecaaa0fccb](https://linux-hardware.org/?probe=ecaaa0fccb) | Jan 14, 2021 |
| Lenovo        | ThinkPad Edge E530 3259A... | [e7ef3a9e86](https://linux-hardware.org/?probe=e7ef3a9e86) | Jan 14, 2021 |
| HP            | Presario V6000 (GF814EA#... | [1cb2345540](https://linux-hardware.org/?probe=1cb2345540) | Jan 12, 2021 |
| HP            | Compaq 6730s                | [71a2587c96](https://linux-hardware.org/?probe=71a2587c96) | Jan 12, 2021 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [b30b783683](https://linux-hardware.org/?probe=b30b783683) | Jan 12, 2021 |
| Dell          | Inspiron 3521               | [2e84869a9a](https://linux-hardware.org/?probe=2e84869a9a) | Jan 11, 2021 |
| Samsung       | 305E4A/305E5A/305E7A        | [a8a6e06472](https://linux-hardware.org/?probe=a8a6e06472) | Jan 10, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [9088e2aaad](https://linux-hardware.org/?probe=9088e2aaad) | Jan 09, 2021 |
| HP            | Pavilion (EH735UA#ABA)      | [f01f51c47c](https://linux-hardware.org/?probe=f01f51c47c) | Jan 09, 2021 |
| HP            | Pavilion (EH735UA#ABA)      | [d3c610e2b0](https://linux-hardware.org/?probe=d3c610e2b0) | Jan 08, 2021 |
| Acer          | Aspire V5-571               | [1d56503d52](https://linux-hardware.org/?probe=1d56503d52) | Jan 06, 2021 |
| Packard Be... | EasyNote TS11HR             | [ab603b2fe8](https://linux-hardware.org/?probe=ab603b2fe8) | Jan 06, 2021 |
| Dell          | Inspiron M5040              | [1cac82f558](https://linux-hardware.org/?probe=1cac82f558) | Jan 06, 2021 |
| Acer          | Aspire 5100                 | [a009c7e619](https://linux-hardware.org/?probe=a009c7e619) | Jan 05, 2021 |
| ASUSTek       | G74Sx                       | [17e1f90630](https://linux-hardware.org/?probe=17e1f90630) | Jan 04, 2021 |
| HP            | Compaq 6730s                | [00acad5ef5](https://linux-hardware.org/?probe=00acad5ef5) | Jan 03, 2021 |
| HP            | 250 G5 Notebook PC          | [a79116f681](https://linux-hardware.org/?probe=a79116f681) | Jan 03, 2021 |
| Dell          | XPS 13 9300                 | [0d6592676a](https://linux-hardware.org/?probe=0d6592676a) | Jan 02, 2021 |
| Packard Be... | EasyNote TS11HR             | [343249d2da](https://linux-hardware.org/?probe=343249d2da) | Jan 02, 2021 |
| HP            | 250 G5 Notebook PC          | [393c8ee706](https://linux-hardware.org/?probe=393c8ee706) | Jan 01, 2021 |
| Dell          | Inspiron 3541               | [e194f83f11](https://linux-hardware.org/?probe=e194f83f11) | Jan 01, 2021 |
| Dell          | Inspiron 3541               | [6d747c6598](https://linux-hardware.org/?probe=6d747c6598) | Jan 01, 2021 |
| Panasonic     | CF-31JEGAX1M                | [c0745f5a94](https://linux-hardware.org/?probe=c0745f5a94) | Dec 31, 2020 |
| HP            | ProBook 6560b               | [d6d7748e86](https://linux-hardware.org/?probe=d6d7748e86) | Dec 30, 2020 |
| Dell          | Inspiron 7737               | [494c51dbea](https://linux-hardware.org/?probe=494c51dbea) | Dec 30, 2020 |
| HP            | Compaq Presario CQ61        | [82c51cc214](https://linux-hardware.org/?probe=82c51cc214) | Dec 29, 2020 |
| HP            | Compaq Presario CQ61        | [a28099fd90](https://linux-hardware.org/?probe=a28099fd90) | Dec 29, 2020 |
| BGH           | C46G                        | [e61ae53564](https://linux-hardware.org/?probe=e61ae53564) | Dec 29, 2020 |
| HP            | Pavilion g7                 | [df2771c104](https://linux-hardware.org/?probe=df2771c104) | Dec 28, 2020 |
| Dell          | Inspiron 6000               | [7158c9692c](https://linux-hardware.org/?probe=7158c9692c) | Dec 27, 2020 |
| Insyde        | CherryTrail                 | [3d9eb0babd](https://linux-hardware.org/?probe=3d9eb0babd) | Dec 26, 2020 |
| BGH           | C46G                        | [515be17b75](https://linux-hardware.org/?probe=515be17b75) | Dec 26, 2020 |
| HP            | Mini 110-3100               | [f716ec84db](https://linux-hardware.org/?probe=f716ec84db) | Dec 26, 2020 |
| Dell          | Inspiron 5490               | [25dadb6466](https://linux-hardware.org/?probe=25dadb6466) | Dec 26, 2020 |
| Dell          | Inspiron 5490               | [72bfd374e3](https://linux-hardware.org/?probe=72bfd374e3) | Dec 26, 2020 |
| HP            | 255 G5                      | [0dc71b4d28](https://linux-hardware.org/?probe=0dc71b4d28) | Dec 24, 2020 |
| Acer          | Aspire 5715Z                | [8e6e0fd1c6](https://linux-hardware.org/?probe=8e6e0fd1c6) | Dec 24, 2020 |
| Ematic        | EWT127                      | [c48f491ddd](https://linux-hardware.org/?probe=c48f491ddd) | Dec 24, 2020 |
| HP            | Pavilion Laptop 14-ce3xx... | [d3a90166ed](https://linux-hardware.org/?probe=d3a90166ed) | Dec 23, 2020 |
| Acer          | Aspire 5738                 | [27df1aad94](https://linux-hardware.org/?probe=27df1aad94) | Dec 22, 2020 |
| Lenovo        | G700 20251                  | [2bf9eaa028](https://linux-hardware.org/?probe=2bf9eaa028) | Dec 22, 2020 |
| HP            | Stream Notebook PC 14       | [515632d3df](https://linux-hardware.org/?probe=515632d3df) | Dec 22, 2020 |
| Dell          | Inspiron M5040              | [aa3db87a20](https://linux-hardware.org/?probe=aa3db87a20) | Dec 22, 2020 |
| Dell          | Latitude E6540              | [a210e1c5b0](https://linux-hardware.org/?probe=a210e1c5b0) | Dec 21, 2020 |
| Lenovo        | G700 20251                  | [33926859e5](https://linux-hardware.org/?probe=33926859e5) | Dec 20, 2020 |
| Dell          | Inspiron 6000               | [2cb0530e89](https://linux-hardware.org/?probe=2cb0530e89) | Dec 20, 2020 |
| Acer          | Aspire E1-570G              | [54c4be3905](https://linux-hardware.org/?probe=54c4be3905) | Dec 19, 2020 |
| Phoenix/Si... | M720SR                      | [019e901528](https://linux-hardware.org/?probe=019e901528) | Dec 19, 2020 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [7148c9a870](https://linux-hardware.org/?probe=7148c9a870) | Dec 19, 2020 |
| HP            | 550                         | [43d983a998](https://linux-hardware.org/?probe=43d983a998) | Dec 16, 2020 |
| Dell          | Precision 3520              | [688878db51](https://linux-hardware.org/?probe=688878db51) | Dec 16, 2020 |
| Toshiba       | Satellite L40               | [1ec0f32bdf](https://linux-hardware.org/?probe=1ec0f32bdf) | Dec 14, 2020 |
| HP            | Stream Laptop 11-y0XX       | [ed04aa76f7](https://linux-hardware.org/?probe=ed04aa76f7) | Dec 13, 2020 |
| HP            | Stream Laptop 11-y0XX       | [a45597a09a](https://linux-hardware.org/?probe=a45597a09a) | Dec 13, 2020 |
| ASUSTek       | G74Sx                       | [79afc26e90](https://linux-hardware.org/?probe=79afc26e90) | Dec 13, 2020 |
| Acer          | Aspire ES1-111              | [89f4d8b69a](https://linux-hardware.org/?probe=89f4d8b69a) | Dec 13, 2020 |
| Acer          | Aspire ES1-111              | [d0f8154669](https://linux-hardware.org/?probe=d0f8154669) | Dec 13, 2020 |
| Lenovo        | ThinkPad T440p 20AWS37D0... | [c35140641b](https://linux-hardware.org/?probe=c35140641b) | Dec 13, 2020 |
| NEC Comput... | PC-VY16AWZE4                | [c395763d53](https://linux-hardware.org/?probe=c395763d53) | Dec 12, 2020 |
| Dell          | Inspiron 3737               | [db241e053d](https://linux-hardware.org/?probe=db241e053d) | Dec 11, 2020 |
| HP            | ZBook 17 G5                 | [ca21d7e31d](https://linux-hardware.org/?probe=ca21d7e31d) | Dec 11, 2020 |
| NEC Comput... | PC-VY16AWZE4                | [eb1884e7bd](https://linux-hardware.org/?probe=eb1884e7bd) | Dec 10, 2020 |
| Insyde        | CAVION BASE 8 MS            | [b2a146e87c](https://linux-hardware.org/?probe=b2a146e87c) | Dec 09, 2020 |
| Insyde        | CAVION BASE 8 MS            | [9a210b4ebc](https://linux-hardware.org/?probe=9a210b4ebc) | Dec 09, 2020 |
| HP            | Laptop 15-bw0xx             | [577608cf6f](https://linux-hardware.org/?probe=577608cf6f) | Dec 08, 2020 |
| HP            | Laptop 15-bw0xx             | [f20b348140](https://linux-hardware.org/?probe=f20b348140) | Dec 08, 2020 |
| HP            | ProBook 450 G3              | [68d5e14ae0](https://linux-hardware.org/?probe=68d5e14ae0) | Dec 08, 2020 |
| HP            | Mini 110-1000               | [b0b1659e5a](https://linux-hardware.org/?probe=b0b1659e5a) | Dec 07, 2020 |
| Toshiba       | NB500                       | [fa6b10012f](https://linux-hardware.org/?probe=fa6b10012f) | Dec 06, 2020 |
| HP            | Pavilion dv9700             | [c2e755bbd2](https://linux-hardware.org/?probe=c2e755bbd2) | Dec 06, 2020 |
| HP            | ProBook 450 G3              | [a2e08c9405](https://linux-hardware.org/?probe=a2e08c9405) | Dec 06, 2020 |
| HP            | Laptop 15s-eq0xxx           | [31f7a22aab](https://linux-hardware.org/?probe=31f7a22aab) | Dec 04, 2020 |
| HP            | Laptop 15s-eq0xxx           | [411cb199ce](https://linux-hardware.org/?probe=411cb199ce) | Dec 04, 2020 |
| Acer          | V5-131                      | [bfdf441399](https://linux-hardware.org/?probe=bfdf441399) | Dec 03, 2020 |
| HP            | EliteBook 2560p             | [704777ce16](https://linux-hardware.org/?probe=704777ce16) | Dec 03, 2020 |
| Fujitsu       | CELSIUS H710                | [03fea3325c](https://linux-hardware.org/?probe=03fea3325c) | Dec 01, 2020 |
| Fujitsu       | CELSIUS H710                | [1214e804ff](https://linux-hardware.org/?probe=1214e804ff) | Dec 01, 2020 |
| Dell          | Latitude E6410              | [073ae61394](https://linux-hardware.org/?probe=073ae61394) | Nov 30, 2020 |
| HP            | G7000                       | [9596f449f8](https://linux-hardware.org/?probe=9596f449f8) | Nov 30, 2020 |
| HP            | G7000                       | [ae575e12ab](https://linux-hardware.org/?probe=ae575e12ab) | Nov 30, 2020 |
| Notebook      | RIM2020                     | [2b494bfd6c](https://linux-hardware.org/?probe=2b494bfd6c) | Nov 28, 2020 |
| Dell          | Inspiron 15-3552            | [762c5e70ba](https://linux-hardware.org/?probe=762c5e70ba) | Nov 28, 2020 |
| Dell          | Inspiron 15-3552            | [fc13827e05](https://linux-hardware.org/?probe=fc13827e05) | Nov 28, 2020 |
| Dell          | Latitude E6410              | [c17a248879](https://linux-hardware.org/?probe=c17a248879) | Nov 28, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [b6570c8388](https://linux-hardware.org/?probe=b6570c8388) | Nov 28, 2020 |
| HP            | 530                         | [8f3bc43ec5](https://linux-hardware.org/?probe=8f3bc43ec5) | Nov 27, 2020 |
| Notebook      | RIM2020                     | [a8a163c8b0](https://linux-hardware.org/?probe=a8a163c8b0) | Nov 27, 2020 |
| Dell          | Vostro A860                 | [beffd605b7](https://linux-hardware.org/?probe=beffd605b7) | Nov 27, 2020 |
| HP            | 530                         | [4d719de8d0](https://linux-hardware.org/?probe=4d719de8d0) | Nov 26, 2020 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | [4be164a8cb](https://linux-hardware.org/?probe=4be164a8cb) | Nov 26, 2020 |
| HP            | 2000                        | [031b9cf2af](https://linux-hardware.org/?probe=031b9cf2af) | Nov 25, 2020 |
| HP            | Pavilion dv6                | [678f6ed857](https://linux-hardware.org/?probe=678f6ed857) | Nov 24, 2020 |
| eMachines     | eM350                       | [2bafdd62aa](https://linux-hardware.org/?probe=2bafdd62aa) | Nov 23, 2020 |
| eMachines     | eM350                       | [03b9a0de29](https://linux-hardware.org/?probe=03b9a0de29) | Nov 23, 2020 |
| HP            | Presario V6500              | [6950f2532b](https://linux-hardware.org/?probe=6950f2532b) | Nov 23, 2020 |
| HP            | Pavilion Notebook           | [a021bfc757](https://linux-hardware.org/?probe=a021bfc757) | Nov 23, 2020 |
| Lenovo        | IdeaPad 330-14IKB 81G2      | [4accc1011e](https://linux-hardware.org/?probe=4accc1011e) | Nov 23, 2020 |
| HP            | 2000                        | [2090a455f6](https://linux-hardware.org/?probe=2090a455f6) | Nov 23, 2020 |
| HP            | 2000                        | [39c1685ce9](https://linux-hardware.org/?probe=39c1685ce9) | Nov 23, 2020 |
| HP            | Presario V6500              | [f4f30c83df](https://linux-hardware.org/?probe=f4f30c83df) | Nov 23, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [7fe15caabf](https://linux-hardware.org/?probe=7fe15caabf) | Nov 23, 2020 |
| eMachines     | E525 V1.03                  | [a5c37bf711](https://linux-hardware.org/?probe=a5c37bf711) | Nov 22, 2020 |
| Dell          | Inspiron 3737               | [7dced8b5ca](https://linux-hardware.org/?probe=7dced8b5ca) | Nov 22, 2020 |
| Dell          | Vostro1710                  | [a359187c45](https://linux-hardware.org/?probe=a359187c45) | Nov 22, 2020 |
| Dell          | Vostro1710                  | [748c9cec43](https://linux-hardware.org/?probe=748c9cec43) | Nov 22, 2020 |
| ARIMA         | W622-DCX                    | [07cc1e0952](https://linux-hardware.org/?probe=07cc1e0952) | Nov 22, 2020 |
| ARIMA         | W622-DCX                    | [7388498d54](https://linux-hardware.org/?probe=7388498d54) | Nov 22, 2020 |
| Dell          | Latitude D430               | [77ef794b1d](https://linux-hardware.org/?probe=77ef794b1d) | Nov 21, 2020 |
| Dell          | Latitude D430               | [c028c146b6](https://linux-hardware.org/?probe=c028c146b6) | Nov 21, 2020 |
| Dell          | Inspiron 3737               | [80df1af89c](https://linux-hardware.org/?probe=80df1af89c) | Nov 20, 2020 |
| Dell          | Latitude E6410              | [4879940968](https://linux-hardware.org/?probe=4879940968) | Nov 19, 2020 |
| HP            | Pavilion x2 Detachable      | [742f34e12f](https://linux-hardware.org/?probe=742f34e12f) | Nov 19, 2020 |
| Acer          | Aspire 5253                 | [5700a5a6f1](https://linux-hardware.org/?probe=5700a5a6f1) | Nov 19, 2020 |
| Dell          | Latitude E5420              | [816b9060e4](https://linux-hardware.org/?probe=816b9060e4) | Nov 19, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | [6e9cf39149](https://linux-hardware.org/?probe=6e9cf39149) | Nov 18, 2020 |
| HP            | Compaq Mini 110c-1100       | [36bc2c3cdf](https://linux-hardware.org/?probe=36bc2c3cdf) | Nov 18, 2020 |
| Acer          | Aspire one V1.03            | [455b9d5ac3](https://linux-hardware.org/?probe=455b9d5ac3) | Nov 17, 2020 |
| Acer          | Aspire E1-570G              | [3ac799a86e](https://linux-hardware.org/?probe=3ac799a86e) | Nov 17, 2020 |
| HP            | Pavilion x2 Detachable      | [14c5b0631b](https://linux-hardware.org/?probe=14c5b0631b) | Nov 17, 2020 |
| Toshiba       | Satellite Pro L550          | [0bd37ae304](https://linux-hardware.org/?probe=0bd37ae304) | Nov 16, 2020 |
| HP            | Pavilion dv6                | [b9e6c75b90](https://linux-hardware.org/?probe=b9e6c75b90) | Nov 15, 2020 |
| Dell          | Latitude E5440              | [b010db49f4](https://linux-hardware.org/?probe=b010db49f4) | Nov 15, 2020 |
| Acer          | Aspire 5630                 | [7479658951](https://linux-hardware.org/?probe=7479658951) | Nov 15, 2020 |
| Dell          | Latitude E6410              | [415cdc7c74](https://linux-hardware.org/?probe=415cdc7c74) | Nov 15, 2020 |
| HP            | EliteBook 840 G3            | [ec506b9770](https://linux-hardware.org/?probe=ec506b9770) | Nov 14, 2020 |
| Lenovo        | G550 20023                  | [9d67fb8d8b](https://linux-hardware.org/?probe=9d67fb8d8b) | Nov 13, 2020 |
| Fujitsu Si... | LIFEBOOK E8410              | [d79b3878a5](https://linux-hardware.org/?probe=d79b3878a5) | Nov 13, 2020 |
| Dell          | Latitude E6410              | [11be79ed72](https://linux-hardware.org/?probe=11be79ed72) | Nov 13, 2020 |
| Dell          | Inspiron 1545               | [3a0512d317](https://linux-hardware.org/?probe=3a0512d317) | Nov 13, 2020 |
| Dell          | Inspiron 1545               | [0c78c7bd9e](https://linux-hardware.org/?probe=0c78c7bd9e) | Nov 13, 2020 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [0470427c68](https://linux-hardware.org/?probe=0470427c68) | Nov 12, 2020 |
| HP            | Pavilion dv5000 (EP413UA... | [d8592798be](https://linux-hardware.org/?probe=d8592798be) | Nov 12, 2020 |
| ASUSTek       | M50Vm                       | [152f954015](https://linux-hardware.org/?probe=152f954015) | Nov 11, 2020 |
| ASUSTek       | M50Vm                       | [46b6e6863b](https://linux-hardware.org/?probe=46b6e6863b) | Nov 11, 2020 |
| HP            | Pavilion dv5                | [8be4ce3c5a](https://linux-hardware.org/?probe=8be4ce3c5a) | Nov 11, 2020 |
| Toshiba       | Satellite C660              | [a5ce6d0206](https://linux-hardware.org/?probe=a5ce6d0206) | Nov 11, 2020 |
| Notebook      | RIM2520                     | [771a897694](https://linux-hardware.org/?probe=771a897694) | Nov 11, 2020 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | [2c5e88fe3a](https://linux-hardware.org/?probe=2c5e88fe3a) | Nov 10, 2020 |
| ASUSTek       | X550CC                      | [cb23a45745](https://linux-hardware.org/?probe=cb23a45745) | Nov 10, 2020 |
| ASUSTek       | X550CC                      | [ccdf1d9de6](https://linux-hardware.org/?probe=ccdf1d9de6) | Nov 10, 2020 |
| HP            | EliteBook 820 G2            | [d57310a957](https://linux-hardware.org/?probe=d57310a957) | Nov 10, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [4c0fec3ac5](https://linux-hardware.org/?probe=4c0fec3ac5) | Nov 09, 2020 |
| Lenovo        | S20-30 Touch 20434          | [bbac27d1f0](https://linux-hardware.org/?probe=bbac27d1f0) | Nov 08, 2020 |
| Lenovo        | ThinkPad T530 23595JU       | [2cce5c789a](https://linux-hardware.org/?probe=2cce5c789a) | Nov 08, 2020 |
| HP            | ENVY 15                     | [1fc6315caf](https://linux-hardware.org/?probe=1fc6315caf) | Nov 08, 2020 |
| HP            | ENVY 15                     | [996ca9b894](https://linux-hardware.org/?probe=996ca9b894) | Nov 08, 2020 |
| Dell          | Latitude D520               | [48ca9c477c](https://linux-hardware.org/?probe=48ca9c477c) | Nov 08, 2020 |
| Lenovo        | S20-30 Touch 20434          | [344bc8046a](https://linux-hardware.org/?probe=344bc8046a) | Nov 08, 2020 |
| HP            | Pavilion g6                 | [a1e12ac11a](https://linux-hardware.org/?probe=a1e12ac11a) | Nov 07, 2020 |
| HP            | 15                          | [a322932224](https://linux-hardware.org/?probe=a322932224) | Nov 07, 2020 |
| HP            | Pavilion g6                 | [c9fef7b025](https://linux-hardware.org/?probe=c9fef7b025) | Nov 07, 2020 |
| Toshiba       | Satellite C660              | [d5f99c156c](https://linux-hardware.org/?probe=d5f99c156c) | Nov 07, 2020 |
| Toshiba       | Satellite C660              | [45404bd97a](https://linux-hardware.org/?probe=45404bd97a) | Nov 07, 2020 |
| ASUSTek       | 1001PXD                     | [d50b2e1307](https://linux-hardware.org/?probe=d50b2e1307) | Nov 05, 2020 |
| Dell          | Inspiron 3421               | [e08c38affc](https://linux-hardware.org/?probe=e08c38affc) | Nov 04, 2020 |
| Dell          | System Inspiron N7110       | [df14fcf89e](https://linux-hardware.org/?probe=df14fcf89e) | Nov 04, 2020 |
| HP            | Compaq Presario CQ60        | [dd9a86b9e4](https://linux-hardware.org/?probe=dd9a86b9e4) | Nov 04, 2020 |
| HP            | Compaq Presario CQ60        | [04db08c84c](https://linux-hardware.org/?probe=04db08c84c) | Nov 04, 2020 |
| Acer          | Aspire 5742G                | [9bc7704a4f](https://linux-hardware.org/?probe=9bc7704a4f) | Nov 02, 2020 |
| Packard Be... | EasyNote TJ65               | [f4459e22c9](https://linux-hardware.org/?probe=f4459e22c9) | Nov 02, 2020 |
| Acer          | Aspire V5-531               | [8eb2cc2336](https://linux-hardware.org/?probe=8eb2cc2336) | Nov 01, 2020 |
| Acer          | Aspire 5742G                | [214289d932](https://linux-hardware.org/?probe=214289d932) | Oct 29, 2020 |
| HP            | 255 G5                      | [e0fe2872e1](https://linux-hardware.org/?probe=e0fe2872e1) | Oct 29, 2020 |
| HUAWEI        | NBLK-WAX9X                  | [5e797005c4](https://linux-hardware.org/?probe=5e797005c4) | Oct 27, 2020 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | [3e49c517bb](https://linux-hardware.org/?probe=3e49c517bb) | Oct 25, 2020 |
| Acer          | Extensa 5635Z               | [c0b6900751](https://linux-hardware.org/?probe=c0b6900751) | Oct 24, 2020 |
| Toshiba       | Satellite P100              | [60e53b8e68](https://linux-hardware.org/?probe=60e53b8e68) | Oct 22, 2020 |
| Toshiba       | Satellite M70               | [b99abfd9d6](https://linux-hardware.org/?probe=b99abfd9d6) | Oct 21, 2020 |
| Sony          | SVE15115ENB                 | [fb5da6e89d](https://linux-hardware.org/?probe=fb5da6e89d) | Oct 20, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6A... | [9565cc6937](https://linux-hardware.org/?probe=9565cc6937) | Oct 20, 2020 |
| HP            | Notebook                    | [8057d8104a](https://linux-hardware.org/?probe=8057d8104a) | Oct 19, 2020 |
| HP            | Compaq Presario CQ60        | [3b01f6d9e5](https://linux-hardware.org/?probe=3b01f6d9e5) | Oct 19, 2020 |
| HP            | Pavilion dv6                | [6fd2a79436](https://linux-hardware.org/?probe=6fd2a79436) | Oct 18, 2020 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | [4408c079e4](https://linux-hardware.org/?probe=4408c079e4) | Oct 17, 2020 |
| ASUSTek       | K53BR                       | [11d1b669d5](https://linux-hardware.org/?probe=11d1b669d5) | Oct 17, 2020 |
| Unknown       | Unknown                     | [4b9298725d](https://linux-hardware.org/?probe=4b9298725d) | Oct 17, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [3a3de52609](https://linux-hardware.org/?probe=3a3de52609) | Oct 16, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [7e7adfbb13](https://linux-hardware.org/?probe=7e7adfbb13) | Oct 16, 2020 |
| Dell          | Vostro 3578                 | [aca3bf63fc](https://linux-hardware.org/?probe=aca3bf63fc) | Oct 16, 2020 |
| Lenovo        | ThinkPad T400 64752C3       | [1729f0708e](https://linux-hardware.org/?probe=1729f0708e) | Oct 15, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X530... | [b572236a74](https://linux-hardware.org/?probe=b572236a74) | Oct 14, 2020 |
| Dell          | Inspiron 15-3567            | [42a82239c5](https://linux-hardware.org/?probe=42a82239c5) | Oct 13, 2020 |
| HP            | Mini 5103                   | [d51f4ebf17](https://linux-hardware.org/?probe=d51f4ebf17) | Oct 13, 2020 |
| HP            | Pavilion Laptop 15-cs0xx... | [6c015911fb](https://linux-hardware.org/?probe=6c015911fb) | Oct 12, 2020 |
| HP            | 2000                        | [36cb1ae33f](https://linux-hardware.org/?probe=36cb1ae33f) | Oct 12, 2020 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [7f2d533ddf](https://linux-hardware.org/?probe=7f2d533ddf) | Oct 12, 2020 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [00f264d5ce](https://linux-hardware.org/?probe=00f264d5ce) | Oct 12, 2020 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [78f452a46b](https://linux-hardware.org/?probe=78f452a46b) | Oct 12, 2020 |
| HP            | Pavilion dv6                | [5b878286a6](https://linux-hardware.org/?probe=5b878286a6) | Oct 10, 2020 |
| Lenovo        | Kona                        | [7490728355](https://linux-hardware.org/?probe=7490728355) | Oct 09, 2020 |
| HP            | Notebook                    | [60b847baba](https://linux-hardware.org/?probe=60b847baba) | Oct 08, 2020 |
| HP            | Pavilion Notebook           | [8e441f98e8](https://linux-hardware.org/?probe=8e441f98e8) | Oct 08, 2020 |
| ASUSTek       | G60VX                       | [737170838e](https://linux-hardware.org/?probe=737170838e) | Oct 07, 2020 |
| Panasonic     | CF-31JQH7MDM                | [bd9af285fe](https://linux-hardware.org/?probe=bd9af285fe) | Oct 07, 2020 |
| Dell          | Latitude E5470              | [a1ae53e261](https://linux-hardware.org/?probe=a1ae53e261) | Oct 06, 2020 |
| Dell          | Vostro 1510                 | [b2e8cb8306](https://linux-hardware.org/?probe=b2e8cb8306) | Oct 06, 2020 |
| Toshiba       | NB100                       | [0136048af7](https://linux-hardware.org/?probe=0136048af7) | Oct 06, 2020 |
| ASUSTek       | 1015PX                      | [4c53e6b790](https://linux-hardware.org/?probe=4c53e6b790) | Oct 05, 2020 |
| Acer          | AOD260                      | [df3f6056c4](https://linux-hardware.org/?probe=df3f6056c4) | Oct 05, 2020 |
| HP            | Presario C700 (GY219LA#A... | [4154ef951b](https://linux-hardware.org/?probe=4154ef951b) | Oct 03, 2020 |
| HP            | Presario C700 (GY219LA#A... | [322081e0c8](https://linux-hardware.org/?probe=322081e0c8) | Oct 03, 2020 |
| Fujitsu       | LIFEBOOK T730               | [79e7520c34](https://linux-hardware.org/?probe=79e7520c34) | Oct 02, 2020 |
| Fujitsu       | LIFEBOOK T730               | [df7fc1fcdd](https://linux-hardware.org/?probe=df7fc1fcdd) | Oct 02, 2020 |
| ASUSTek       | K54C                        | [b82b607833](https://linux-hardware.org/?probe=b82b607833) | Oct 02, 2020 |
| Toshiba       | Satellite A100              | [05371b4921](https://linux-hardware.org/?probe=05371b4921) | Oct 02, 2020 |
| HUAWEI        | HN-WX9X                     | [2b80873c58](https://linux-hardware.org/?probe=2b80873c58) | Oct 02, 2020 |
| Acer          | Makalu                      | [e68197eded](https://linux-hardware.org/?probe=e68197eded) | Sep 30, 2020 |
| Apple         | MacBook5,2                  | [47c45ae46f](https://linux-hardware.org/?probe=47c45ae46f) | Sep 30, 2020 |
| Acer          | AOD270                      | [4d7f40e97b](https://linux-hardware.org/?probe=4d7f40e97b) | Sep 30, 2020 |
| Apple         | MacBookPro8,1               | [7b095a0a58](https://linux-hardware.org/?probe=7b095a0a58) | Sep 30, 2020 |
| ASUSTek       | K54C                        | [a15a6332bf](https://linux-hardware.org/?probe=a15a6332bf) | Sep 30, 2020 |
| Lenovo        | 3000 N200 0769B6G           | [7e9967fb0e](https://linux-hardware.org/?probe=7e9967fb0e) | Sep 30, 2020 |
| HP            | 530                         | [c330f06c15](https://linux-hardware.org/?probe=c330f06c15) | Sep 30, 2020 |
| HP            | ZBook 17 G2                 | [0d0b182c79](https://linux-hardware.org/?probe=0d0b182c79) | Sep 27, 2020 |
| Dell          | Latitude D630               | [fa947637f9](https://linux-hardware.org/?probe=fa947637f9) | Sep 25, 2020 |
| Samsung       | RV420/RV520/RV720/E3530/... | [fffe9391c2](https://linux-hardware.org/?probe=fffe9391c2) | Sep 25, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | [31e0cd8ca1](https://linux-hardware.org/?probe=31e0cd8ca1) | Sep 24, 2020 |
| Acer          | Extensa 5620                | [2cd43c8065](https://linux-hardware.org/?probe=2cd43c8065) | Sep 24, 2020 |
| HP            | Laptop 15-bw0xx             | [9067f67190](https://linux-hardware.org/?probe=9067f67190) | Sep 24, 2020 |
| Acer          | Swift SF314-42              | [03a2ad0203](https://linux-hardware.org/?probe=03a2ad0203) | Sep 23, 2020 |
| Sony          | VGN-SZ4VWN_X                | [b5f136ce13](https://linux-hardware.org/?probe=b5f136ce13) | Sep 23, 2020 |
| Fujitsu Si... | AMILO Li3710                | [4e11c10492](https://linux-hardware.org/?probe=4e11c10492) | Sep 23, 2020 |
| Fujitsu Si... | AMILO Li3710                | [a5d32c72d2](https://linux-hardware.org/?probe=a5d32c72d2) | Sep 23, 2020 |
| Sony          | VGN-CR120E                  | [8569f91c17](https://linux-hardware.org/?probe=8569f91c17) | Sep 23, 2020 |
| HP            | EliteBook 840 G4            | [adec24022c](https://linux-hardware.org/?probe=adec24022c) | Sep 22, 2020 |
| ASUSTek       | W7J                         | [70078e77fa](https://linux-hardware.org/?probe=70078e77fa) | Sep 22, 2020 |
| Acer          | Swift SF314-42              | [a243f6284c](https://linux-hardware.org/?probe=a243f6284c) | Sep 21, 2020 |
| Dell          | Inspiron 1110               | [01517be2d7](https://linux-hardware.org/?probe=01517be2d7) | Sep 20, 2020 |
| ASUSTek       | G74Sx                       | [76f3c2d574](https://linux-hardware.org/?probe=76f3c2d574) | Sep 20, 2020 |
| AMI           | Cherry Trail CR             | [a1343de48d](https://linux-hardware.org/?probe=a1343de48d) | Sep 20, 2020 |
| Toshiba       | Satellite C660              | [ba30a12748](https://linux-hardware.org/?probe=ba30a12748) | Sep 19, 2020 |
| HP            | ENVY Notebook               | [fab3ee0d2e](https://linux-hardware.org/?probe=fab3ee0d2e) | Sep 19, 2020 |
| Lenovo        | IdeaPad 320S-13IKB 81AK     | [fe11f72b06](https://linux-hardware.org/?probe=fe11f72b06) | Sep 19, 2020 |
| HP            | ProBook 4540s               | [9ca21222f5](https://linux-hardware.org/?probe=9ca21222f5) | Sep 19, 2020 |
| HP            | Compaq Presario C700        | [4e8ba77ee3](https://linux-hardware.org/?probe=4e8ba77ee3) | Sep 18, 2020 |
| HP            | Compaq Presario C700        | [b9b510693c](https://linux-hardware.org/?probe=b9b510693c) | Sep 18, 2020 |
| Acer          | AO722                       | [d4c9b21741](https://linux-hardware.org/?probe=d4c9b21741) | Sep 18, 2020 |
| Toshiba       | NA 1402                     | [e1d38cee7f](https://linux-hardware.org/?probe=e1d38cee7f) | Sep 17, 2020 |
| HP            | Mini 210-1100               | [3b76e02a8f](https://linux-hardware.org/?probe=3b76e02a8f) | Sep 17, 2020 |
| Packard Be... | EasyNote ENTF71BM           | [b6c8ba71e9](https://linux-hardware.org/?probe=b6c8ba71e9) | Sep 17, 2020 |
| Packard Be... | EasyNote ENTF71BM           | [e09802de6b](https://linux-hardware.org/?probe=e09802de6b) | Sep 17, 2020 |
| Dell          | Inspiron 5577               | [17862346f8](https://linux-hardware.org/?probe=17862346f8) | Sep 15, 2020 |
| Acer          | Aspire 7520                 | [d8ae16fc0b](https://linux-hardware.org/?probe=d8ae16fc0b) | Sep 14, 2020 |
| Unknown       | Unknown                     | [2c52151f77](https://linux-hardware.org/?probe=2c52151f77) | Sep 13, 2020 |
| Acer          | AO722                       | [39f920ae53](https://linux-hardware.org/?probe=39f920ae53) | Sep 13, 2020 |
| ASUSTek       | N750JK                      | [e140f6e3e4](https://linux-hardware.org/?probe=e140f6e3e4) | Sep 12, 2020 |
| Unknown       | Unknown                     | [922d1c2533](https://linux-hardware.org/?probe=922d1c2533) | Sep 11, 2020 |
| Unknown       | Unknown                     | [f56d6dcffd](https://linux-hardware.org/?probe=f56d6dcffd) | Sep 11, 2020 |
| HP            | 530                         | [e0ea19e1dc](https://linux-hardware.org/?probe=e0ea19e1dc) | Sep 10, 2020 |
| HP            | Pavilion dv5                | [f5a369d166](https://linux-hardware.org/?probe=f5a369d166) | Sep 10, 2020 |
| HP            | Pavilion dv5                | [f9f9a9ca5f](https://linux-hardware.org/?probe=f9f9a9ca5f) | Sep 09, 2020 |
| Acer          | Aspire A315-21              | [07fb4fed45](https://linux-hardware.org/?probe=07fb4fed45) | Sep 08, 2020 |
| HP            | 530                         | [8d751d7d91](https://linux-hardware.org/?probe=8d751d7d91) | Sep 07, 2020 |
| Lenovo        | ThinkPad T520 4239CTO       | [fa8846ee61](https://linux-hardware.org/?probe=fa8846ee61) | Sep 07, 2020 |
| Dell          | Inspiron 5577               | [da6490c410](https://linux-hardware.org/?probe=da6490c410) | Sep 06, 2020 |
| Toshiba       | Satellite L855D             | [a14d72d23c](https://linux-hardware.org/?probe=a14d72d23c) | Sep 06, 2020 |
| ASUSTek       | W7J                         | [c505a80ea5](https://linux-hardware.org/?probe=c505a80ea5) | Sep 06, 2020 |
| Dell          | Vostro 3700                 | [c9b764a48b](https://linux-hardware.org/?probe=c9b764a48b) | Sep 05, 2020 |
| Dell          | Inspiron 5537               | [4ddf924081](https://linux-hardware.org/?probe=4ddf924081) | Sep 05, 2020 |
| Dell          | Inspiron 5537               | [23a0e05047](https://linux-hardware.org/?probe=23a0e05047) | Sep 05, 2020 |
| HP            | EliteBook 840 G6            | [4a5bac87d8](https://linux-hardware.org/?probe=4a5bac87d8) | Sep 04, 2020 |
| Dell          | Inspiron N4010              | [59357480b7](https://linux-hardware.org/?probe=59357480b7) | Sep 04, 2020 |
| Toshiba       | Satellite C650D             | [c661cb7e35](https://linux-hardware.org/?probe=c661cb7e35) | Sep 03, 2020 |
| HP            | Laptop 15-bw0xx             | [02c0bf156d](https://linux-hardware.org/?probe=02c0bf156d) | Sep 03, 2020 |
| HP            | Presario CQ57               | [2dcab385bd](https://linux-hardware.org/?probe=2dcab385bd) | Sep 03, 2020 |
| Dell          | Inspiron 3542               | [9661146a6a](https://linux-hardware.org/?probe=9661146a6a) | Sep 02, 2020 |
| Acer          | Aspire one V1.13            | [37b4d70de4](https://linux-hardware.org/?probe=37b4d70de4) | Sep 01, 2020 |
| Toshiba       | Satellite C55-A-16D         | [ffb7e1e547](https://linux-hardware.org/?probe=ffb7e1e547) | Aug 31, 2020 |
| Dell          | Inspiron 15-3567            | [f9903ce5d2](https://linux-hardware.org/?probe=f9903ce5d2) | Aug 31, 2020 |
| Toshiba       | Satellite Pro L550          | [02e28c5706](https://linux-hardware.org/?probe=02e28c5706) | Aug 30, 2020 |
| Apple         | MacBookAir3,1               | [a3168c57ea](https://linux-hardware.org/?probe=a3168c57ea) | Aug 30, 2020 |
| Dell          | Inspiron 1520               | [6d520f3f75](https://linux-hardware.org/?probe=6d520f3f75) | Aug 29, 2020 |
| HP            | Laptop 14-dk1xxx            | [f72e36a4c1](https://linux-hardware.org/?probe=f72e36a4c1) | Aug 28, 2020 |
| Dell          | Inspiron N4010              | [f80559862a](https://linux-hardware.org/?probe=f80559862a) | Aug 27, 2020 |
| Lenovo        | IdeaPad 310-14ISK 80UG      | [a2b597141c](https://linux-hardware.org/?probe=a2b597141c) | Aug 27, 2020 |
| HP            | Pavilion g4                 | [55dec82070](https://linux-hardware.org/?probe=55dec82070) | Aug 26, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [de3f00fc50](https://linux-hardware.org/?probe=de3f00fc50) | Aug 26, 2020 |
| Lenovo        | G475 20080                  | [c97ad59308](https://linux-hardware.org/?probe=c97ad59308) | Aug 26, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [6b7781d4f0](https://linux-hardware.org/?probe=6b7781d4f0) | Aug 25, 2020 |
| Acer          | Aspire A515-52G             | [86a890eb18](https://linux-hardware.org/?probe=86a890eb18) | Aug 23, 2020 |
| Acer          | Aspire A515-52G             | [5034bf6bc3](https://linux-hardware.org/?probe=5034bf6bc3) | Aug 23, 2020 |
| Dell          | Inspiron MM061              | [a34d3a0236](https://linux-hardware.org/?probe=a34d3a0236) | Aug 22, 2020 |
| Unknown       | Unknown                     | [858431dd69](https://linux-hardware.org/?probe=858431dd69) | Aug 22, 2020 |
| HP            | EliteBook 725 G2            | [f9f5c68624](https://linux-hardware.org/?probe=f9f5c68624) | Aug 22, 2020 |
| Dell          | Inspiron 1545               | [0502d22a6e](https://linux-hardware.org/?probe=0502d22a6e) | Aug 22, 2020 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | [955166808e](https://linux-hardware.org/?probe=955166808e) | Aug 22, 2020 |
| Lenovo        | 4068RZ7                     | [a019743ebe](https://linux-hardware.org/?probe=a019743ebe) | Aug 20, 2020 |
| Lenovo        | 4068RZ7                     | [8b55712014](https://linux-hardware.org/?probe=8b55712014) | Aug 20, 2020 |
| Dell          | Inspiron 1545               | [20a0eaa36a](https://linux-hardware.org/?probe=20a0eaa36a) | Aug 20, 2020 |
| Toshiba       | Satellite L670D             | [746e1de754](https://linux-hardware.org/?probe=746e1de754) | Aug 19, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [47f5ea43b8](https://linux-hardware.org/?probe=47f5ea43b8) | Aug 18, 2020 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [712e524505](https://linux-hardware.org/?probe=712e524505) | Aug 18, 2020 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | [188c3f31c6](https://linux-hardware.org/?probe=188c3f31c6) | Aug 18, 2020 |
| HP            | 530 Notebook PC(GU327AA#... | [55d79e4d6a](https://linux-hardware.org/?probe=55d79e4d6a) | Aug 17, 2020 |
| HP            | 530 Notebook PC(GU327AA#... | [19b6cecfad](https://linux-hardware.org/?probe=19b6cecfad) | Aug 17, 2020 |
| HP            | Stream Laptop 14-ax0XX      | [5faf279c4f](https://linux-hardware.org/?probe=5faf279c4f) | Aug 17, 2020 |
| HP            | Laptop 15-bs0xx             | [45004f5195](https://linux-hardware.org/?probe=45004f5195) | Aug 17, 2020 |
| Medion        | ERAZER X7853 MD60604        | [1216fcc86c](https://linux-hardware.org/?probe=1216fcc86c) | Aug 16, 2020 |
| Medion        | ERAZER X7853 MD60604        | [6be345d7bd](https://linux-hardware.org/?probe=6be345d7bd) | Aug 16, 2020 |
| Samsung       | 400B4B/400B5B/200B4B/200... | [299e17392c](https://linux-hardware.org/?probe=299e17392c) | Aug 15, 2020 |
| Acer          | Aspire one V1.13            | [c2802686dc](https://linux-hardware.org/?probe=c2802686dc) | Aug 15, 2020 |
| Dell          | G5 5505                     | [9d7d4c771b](https://linux-hardware.org/?probe=9d7d4c771b) | Aug 14, 2020 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | [72b1361358](https://linux-hardware.org/?probe=72b1361358) | Aug 13, 2020 |
| Toshiba       | STI NA 1402                 | [d75672b88f](https://linux-hardware.org/?probe=d75672b88f) | Aug 13, 2020 |
| Alienware     | 15                          | [4b1d9f9153](https://linux-hardware.org/?probe=4b1d9f9153) | Aug 13, 2020 |
| Alienware     | 15                          | [dfde91faf2](https://linux-hardware.org/?probe=dfde91faf2) | Aug 13, 2020 |
| Toshiba       | Satellite C650              | [0b2880b414](https://linux-hardware.org/?probe=0b2880b414) | Aug 12, 2020 |
| Dell          | G5 5505                     | [c4a555abaa](https://linux-hardware.org/?probe=c4a555abaa) | Aug 12, 2020 |
| MSI           | GT72 2PC                    | [464657ada9](https://linux-hardware.org/?probe=464657ada9) | Aug 11, 2020 |
| Acer          | Aspire 5532                 | [6d1ed17c3a](https://linux-hardware.org/?probe=6d1ed17c3a) | Aug 10, 2020 |
| HP            | 255 G3                      | [4d659eb265](https://linux-hardware.org/?probe=4d659eb265) | Aug 10, 2020 |
| Bluechip C... | Crestline & ICH8M Chipse... | [9b8c4353cc](https://linux-hardware.org/?probe=9b8c4353cc) | Aug 09, 2020 |
| HP            | G62                         | [79f5cf8c86](https://linux-hardware.org/?probe=79f5cf8c86) | Aug 08, 2020 |
| HP            | 14                          | [b7289075c1](https://linux-hardware.org/?probe=b7289075c1) | Aug 08, 2020 |
| Dell          | Vostro 15-3568              | [3b1e04b2da](https://linux-hardware.org/?probe=3b1e04b2da) | Aug 07, 2020 |
| Lenovo        | ThinkPad X230 23252EG       | [df9004d133](https://linux-hardware.org/?probe=df9004d133) | Aug 07, 2020 |
| HP            | ProBook 650 G1              | [3790f3b233](https://linux-hardware.org/?probe=3790f3b233) | Aug 07, 2020 |
| Toshiba       | Satellite C55-A             | [8fb6762361](https://linux-hardware.org/?probe=8fb6762361) | Aug 06, 2020 |
| MSI           | GE620/GE620DX/FX620DX/FX... | [b9fddd15e8](https://linux-hardware.org/?probe=b9fddd15e8) | Aug 05, 2020 |
| Toshiba       | Satellite L670D             | [d28122373c](https://linux-hardware.org/?probe=d28122373c) | Aug 05, 2020 |
| HP            | EliteBook 8460p             | [452088e655](https://linux-hardware.org/?probe=452088e655) | Aug 03, 2020 |
| Dell          | Inspiron MP061              | [7355e190ca](https://linux-hardware.org/?probe=7355e190ca) | Aug 03, 2020 |
| HP            | Pavilion g4                 | [4fc16d6e09](https://linux-hardware.org/?probe=4fc16d6e09) | Aug 02, 2020 |
| HP            | Pavilion g4                 | [0b9fc56cd1](https://linux-hardware.org/?probe=0b9fc56cd1) | Aug 02, 2020 |
| Unknown       | Unknown                     | [59c9ce7401](https://linux-hardware.org/?probe=59c9ce7401) | Aug 02, 2020 |
| Dell          | Latitude E5450              | [884ee42c35](https://linux-hardware.org/?probe=884ee42c35) | Aug 01, 2020 |
| ASUSTek       | GX501VIK                    | [de4780e6e4](https://linux-hardware.org/?probe=de4780e6e4) | Aug 01, 2020 |
| Lenovo        | IdeaPad S145-14IWL 81MU     | [18b9136e87](https://linux-hardware.org/?probe=18b9136e87) | Aug 01, 2020 |
| Dell          | Inspiron N5050              | [cb18c38bd3](https://linux-hardware.org/?probe=cb18c38bd3) | Jul 30, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [dc8ed0c837](https://linux-hardware.org/?probe=dc8ed0c837) | Jul 30, 2020 |
| HP            | EliteBook 2760p             | [ef84151f18](https://linux-hardware.org/?probe=ef84151f18) | Jul 29, 2020 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [3db826b463](https://linux-hardware.org/?probe=3db826b463) | Jul 29, 2020 |
| Lenovo        | ThinkPad T530 2394BK7       | [3fd417f684](https://linux-hardware.org/?probe=3fd417f684) | Jul 29, 2020 |
| HP            | ProBook 6470b               | [fe3206ee5f](https://linux-hardware.org/?probe=fe3206ee5f) | Jul 28, 2020 |
| Toshiba       | Satellite L670D             | [91a4aad7d7](https://linux-hardware.org/?probe=91a4aad7d7) | Jul 28, 2020 |
| Toshiba       | Satellite L670D             | [10658a729f](https://linux-hardware.org/?probe=10658a729f) | Jul 28, 2020 |
| HP            | 1000                        | [d0cdc87248](https://linux-hardware.org/?probe=d0cdc87248) | Jul 27, 2020 |
| Lenovo        | G560 20042                  | [fb76f0edee](https://linux-hardware.org/?probe=fb76f0edee) | Jul 27, 2020 |
| Acer          | Aspire 5741                 | [6fa0f96d6b](https://linux-hardware.org/?probe=6fa0f96d6b) | Jul 27, 2020 |
| HP            | 1000                        | [36db752887](https://linux-hardware.org/?probe=36db752887) | Jul 26, 2020 |
| Sony          | VPCYB35AB                   | [6cc28f56ff](https://linux-hardware.org/?probe=6cc28f56ff) | Jul 26, 2020 |
| Sony          | VPCYB35AB                   | [4b5b2115c1](https://linux-hardware.org/?probe=4b5b2115c1) | Jul 26, 2020 |
| ASUSTek       | G750JM                      | [9b3a5ac253](https://linux-hardware.org/?probe=9b3a5ac253) | Jul 25, 2020 |
| Dell          | Inspiron 1545               | [57675258c0](https://linux-hardware.org/?probe=57675258c0) | Jul 25, 2020 |
| Compal        | HGL31I                      | [8f7aac30a8](https://linux-hardware.org/?probe=8f7aac30a8) | Jul 25, 2020 |
| Dell          | Latitude E6420              | [0de23594ba](https://linux-hardware.org/?probe=0de23594ba) | Jul 24, 2020 |
| Acer          | Aspire 5750                 | [fbb8795c20](https://linux-hardware.org/?probe=fbb8795c20) | Jul 24, 2020 |
| Lenovo        | IdeaPad 100S-14IBR 80R9     | [8dd238e5a1](https://linux-hardware.org/?probe=8dd238e5a1) | Jul 24, 2020 |
| Lenovo        | IdeaPad S145-15API 81V7     | [d65a2f5a5a](https://linux-hardware.org/?probe=d65a2f5a5a) | Jul 24, 2020 |
| HP            | 14                          | [143464e093](https://linux-hardware.org/?probe=143464e093) | Jul 24, 2020 |
| Dell          | Vostro 3460                 | [ecdbc21896](https://linux-hardware.org/?probe=ecdbc21896) | Jul 24, 2020 |
| Clevo         | M540SR VT6363A              | [b5b4e22b05](https://linux-hardware.org/?probe=b5b4e22b05) | Jul 21, 2020 |
| Dell          | Vostro 15-3568              | [7ef51b8ffe](https://linux-hardware.org/?probe=7ef51b8ffe) | Jul 20, 2020 |
| Dell          | Vostro 15-3568              | [7ba1b7b850](https://linux-hardware.org/?probe=7ba1b7b850) | Jul 19, 2020 |
| Digibras      | NH4CU03                     | [3bad8b713e](https://linux-hardware.org/?probe=3bad8b713e) | Jul 19, 2020 |
| HP            | ElitePad 1000 G2            | [a8871cdcff](https://linux-hardware.org/?probe=a8871cdcff) | Jul 19, 2020 |
| HP            | Notebook                    | [875e3886d1](https://linux-hardware.org/?probe=875e3886d1) | Jul 18, 2020 |
| Dell          | Studio 1737                 | [b08787e998](https://linux-hardware.org/?probe=b08787e998) | Jul 17, 2020 |
| Acer          | Aspire 5715Z                | [929559cae0](https://linux-hardware.org/?probe=929559cae0) | Jul 17, 2020 |
| HP            | Laptop 14-dq1xxx            | [1e49fe5909](https://linux-hardware.org/?probe=1e49fe5909) | Jul 16, 2020 |
| Google        | Chell                       | [fb663766c0](https://linux-hardware.org/?probe=fb663766c0) | Jul 16, 2020 |
| Google        | Chell                       | [af33f4bc7b](https://linux-hardware.org/?probe=af33f4bc7b) | Jul 15, 2020 |
| HP            | EliteBook 840 G2            | [a2a8e9d267](https://linux-hardware.org/?probe=a2a8e9d267) | Jul 13, 2020 |
| Sony          | VGN-P11Z_G                  | [7615c6d02b](https://linux-hardware.org/?probe=7615c6d02b) | Jul 11, 2020 |
| Lenovo        | IdeaPad S145-15API 81UT     | [8164d6222a](https://linux-hardware.org/?probe=8164d6222a) | Jul 11, 2020 |
| Lenovo        | IdeaPad S145-15API 81UT     | [478d2b6718](https://linux-hardware.org/?probe=478d2b6718) | Jul 11, 2020 |
| Lenovo        | BP PV CLASSMATE+            | [0e381612fb](https://linux-hardware.org/?probe=0e381612fb) | Jul 11, 2020 |
| Toshiba       | Satellite C660              | [b15da8cdfc](https://linux-hardware.org/?probe=b15da8cdfc) | Jul 11, 2020 |
| HP            | ElitePad 1000 G2            | [b2c793bfb4](https://linux-hardware.org/?probe=b2c793bfb4) | Jul 09, 2020 |
| HP            | ElitePad 1000 G2            | [152f8e9ebd](https://linux-hardware.org/?probe=152f8e9ebd) | Jul 09, 2020 |
| HP            | ElitePad 1000 G2            | [5054174795](https://linux-hardware.org/?probe=5054174795) | Jul 08, 2020 |
| ASUSTek       | GX501VIK                    | [0dc513d440](https://linux-hardware.org/?probe=0dc513d440) | Jul 07, 2020 |
| UMAX          | VisionBook 14Wg Pro         | [5d2b6ed775](https://linux-hardware.org/?probe=5d2b6ed775) | Jul 06, 2020 |
| Dell          | Latitude E6520              | [c11c08470c](https://linux-hardware.org/?probe=c11c08470c) | Jul 06, 2020 |
| ECS           | G410                        | [38bad5d8cb](https://linux-hardware.org/?probe=38bad5d8cb) | Jul 05, 2020 |
| Samsung       | N150                        | [76e856e9e9](https://linux-hardware.org/?probe=76e856e9e9) | Jul 04, 2020 |
| Samsung       | N150                        | [cf90fb442b](https://linux-hardware.org/?probe=cf90fb442b) | Jul 04, 2020 |
| Lenovo        | ThinkPad X140e 20BMS00E0... | [ee2280ecd4](https://linux-hardware.org/?probe=ee2280ecd4) | Jul 04, 2020 |
| Toshiba       | Satellite C40-A             | [672cca96fd](https://linux-hardware.org/?probe=672cca96fd) | Jul 04, 2020 |
| Acer          | Lugano M                    | [c3722a65f4](https://linux-hardware.org/?probe=c3722a65f4) | Jul 04, 2020 |
| WIPRO         | WIVNB7B1623-0002            | [4669989193](https://linux-hardware.org/?probe=4669989193) | Jul 03, 2020 |
| Acer          | Lugano M                    | [d91f2c3af1](https://linux-hardware.org/?probe=d91f2c3af1) | Jul 03, 2020 |
| Dell          | Latitude E6440              | [521818b099](https://linux-hardware.org/?probe=521818b099) | Jul 02, 2020 |
| HP            | ProBook 450 G3              | [cf66568c1a](https://linux-hardware.org/?probe=cf66568c1a) | Jul 01, 2020 |
| HP            | Notebook                    | [1b077e7d7e](https://linux-hardware.org/?probe=1b077e7d7e) | Jun 30, 2020 |
| HP            | G60                         | [2c11d20a74](https://linux-hardware.org/?probe=2c11d20a74) | Jun 29, 2020 |
| Toshiba       | Satellite C645              | [962d89d16d](https://linux-hardware.org/?probe=962d89d16d) | Jun 29, 2020 |
| Toshiba       | Satellite C645              | [bec8895749](https://linux-hardware.org/?probe=bec8895749) | Jun 29, 2020 |
| Toshiba       | Satellite S50-B             | [2e8165ca6a](https://linux-hardware.org/?probe=2e8165ca6a) | Jun 28, 2020 |
| Dell          | Inspiron 1525               | [754b2de717](https://linux-hardware.org/?probe=754b2de717) | Jun 27, 2020 |
| Dell          | System Vostro 3450          | [6ecdf91891](https://linux-hardware.org/?probe=6ecdf91891) | Jun 27, 2020 |
| Alienware     | M17x                        | [4a26920858](https://linux-hardware.org/?probe=4a26920858) | Jun 26, 2020 |
| Toshiba       | Satellite L655              | [d03c7bb948](https://linux-hardware.org/?probe=d03c7bb948) | Jun 26, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_15/Notebook/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Notebooks | Percent |
|-------------------|-----------|---------|
| 5.3.0-40-generic  | 67        | 5.79%   |
| 5.4.0-42-generic  | 61        | 5.27%   |
| 5.3.0-46-generic  | 53        | 4.58%   |
| 5.3.0-51-generic  | 47        | 4.06%   |
| 5.0.0-37-generic  | 47        | 4.06%   |
| 5.4.0-47-generic  | 39        | 3.37%   |
| 5.4.0-45-generic  | 37        | 3.2%    |
| 5.3.0-53-generic  | 37        | 3.2%    |
| 5.3.0-42-generic  | 36        | 3.11%   |
| 5.4.0-58-generic  | 32        | 2.76%   |
| 5.4.0-48-generic  | 31        | 2.68%   |
| 5.4.0-150-generic | 29        | 2.5%    |
| 5.4.0-65-generic  | 28        | 2.42%   |
| 5.4.0-80-generic  | 25        | 2.16%   |
| 5.4.0-72-generic  | 24        | 2.07%   |
| 5.4.0-52-generic  | 23        | 1.99%   |
| 5.4.0-81-generic  | 20        | 1.73%   |
| 5.4.0-73-generic  | 20        | 1.73%   |
| 5.3.0-62-generic  | 20        | 1.73%   |
| 5.4.0-70-generic  | 19        | 1.64%   |
| 5.3.0-45-generic  | 18        | 1.55%   |
| 5.4.0-54-generic  | 17        | 1.47%   |
| 5.3.0-59-generic  | 17        | 1.47%   |
| 5.3.0-28-generic  | 17        | 1.47%   |
| 5.4.0-87-generic  | 16        | 1.38%   |
| 4.18.0-25-generic | 16        | 1.38%   |
| 5.4.0-91-generic  | 15        | 1.3%    |
| 5.4.0-66-generic  | 15        | 1.3%    |
| 4.18.0-21-generic | 15        | 1.3%    |
| 5.4.0-77-generic  | 13        | 1.12%   |
| 5.4.0-64-generic  | 13        | 1.12%   |
| 5.0.0-36-generic  | 13        | 1.12%   |
| 5.4.0-89-generic  | 12        | 1.04%   |
| 4.18.0-22-generic | 12        | 1.04%   |
| 5.4.0-74-generic  | 11        | 0.95%   |
| 5.4.0-90-generic  | 10        | 0.86%   |
| 5.4.0-56-generic  | 10        | 0.86%   |
| 5.4.0-53-generic  | 10        | 0.86%   |
| 5.3.0-61-generic  | 10        | 0.86%   |
| 5.4.0-62-generic  | 9         | 0.78%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 611       | 57.37%  |
| 5.3.0   | 312       | 29.3%   |
| 5.0.0   | 89        | 8.36%   |
| 4.18.0  | 45        | 4.23%   |
| 5.6.0   | 2         | 0.19%   |
| 5.9.12  | 1         | 0.09%   |
| 5.9.0   | 1         | 0.09%   |
| 5.7.1   | 1         | 0.09%   |
| 5.4.1   | 1         | 0.09%   |
| 5.10.35 | 1         | 0.09%   |
| 5.10.16 | 1         | 0.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 612       | 57.46%  |
| 5.3     | 312       | 29.3%   |
| 5.0     | 89        | 8.36%   |
| 4.18    | 45        | 4.23%   |
| 5.9     | 2         | 0.19%   |
| 5.6     | 2         | 0.19%   |
| 5.10    | 2         | 0.19%   |
| 5.7     | 1         | 0.09%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 792       | 76.52%  |
| i686   | 243       | 23.48%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| GNOME      | 524       | 50.14%  |
| XFCE       | 421       | 40.29%  |
| Unknown    | 96        | 9.19%   |
| KDE        | 2         | 0.19%   |
| X-Cinnamon | 1         | 0.1%    |
| Unity      | 1         | 0.1%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 966       | 92.35%  |
| Unknown | 64        | 6.12%   |
| Wayland | 16        | 1.53%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 859       | 81.73%  |
| LightDM | 127       | 12.08%  |
| GDM3    | 50        | 4.76%   |
| GDM     | 9         | 0.86%   |
| TDM     | 6         | 0.57%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 330       | 31.67%  |
| pt_BR   | 81        | 7.77%   |
| Unknown | 61        | 5.85%   |
| de_DE   | 51        | 4.89%   |
| it_IT   | 50        | 4.8%    |
| en_GB   | 50        | 4.8%    |
| en_IN   | 35        | 3.36%   |
| en_CA   | 33        | 3.17%   |
| es_ES   | 29        | 2.78%   |
| pl_PL   | 25        | 2.4%    |
| fr_FR   | 23        | 2.21%   |
| pt_PT   | 22        | 2.11%   |
| C       | 19        | 1.82%   |
| es_AR   | 18        | 1.73%   |
| cs_CZ   | 18        | 1.73%   |
| ru_RU   | 13        | 1.25%   |
| es_MX   | 13        | 1.25%   |
| en_AU   | 13        | 1.25%   |
| tr_TR   | 11        | 1.06%   |
| nl_NL   | 11        | 1.06%   |
| es_CL   | 9         | 0.86%   |
| en_ZA   | 9         | 0.86%   |
| ja_JP   | 8         | 0.77%   |
| fr_CA   | 8         | 0.77%   |
| sv_SE   | 7         | 0.67%   |
| en_NZ   | 7         | 0.67%   |
| el_GR   | 7         | 0.67%   |
| de_AT   | 7         | 0.67%   |
| hu_HU   | 6         | 0.58%   |
| da_DK   | 6         | 0.58%   |
| ro_RO   | 5         | 0.48%   |
| es_PE   | 5         | 0.48%   |
| ru_UA   | 4         | 0.38%   |
| nl_BE   | 4         | 0.38%   |
| es_CO   | 4         | 0.38%   |
| en_PH   | 4         | 0.38%   |
| sl_SI   | 3         | 0.29%   |
| sk_SK   | 3         | 0.29%   |
| hr_HR   | 2         | 0.19%   |
| fi_FI   | 2         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 725       | 69.31%  |
| EFI  | 321       | 30.69%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 948       | 90.72%  |
| Tmpfs   | 39        | 3.73%   |
| Overlay | 32        | 3.06%   |
| Unknown | 14        | 1.34%   |
| Btrfs   | 6         | 0.57%   |
| Ext2    | 5         | 0.48%   |
| Ext3    | 1         | 0.1%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 988       | 94.82%  |
| MBR     | 31        | 2.98%   |
| GPT     | 23        | 2.21%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 950       | 91.08%  |
| Yes       | 93        | 8.92%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 769       | 73.87%  |
| Yes       | 272       | 26.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 257       | 24.85%  |
| Dell                | 150       | 14.51%  |
| Lenovo              | 131       | 12.67%  |
| Acer                | 95        | 9.19%   |
| ASUSTek Computer    | 90        | 8.7%    |
| Toshiba             | 72        | 6.96%   |
| Samsung Electronics | 27        | 2.61%   |
| Sony                | 21        | 2.03%   |
| Apple               | 16        | 1.55%   |
| Fujitsu Siemens     | 14        | 1.35%   |
| Unknown             | 12        | 1.16%   |
| Packard Bell        | 11        | 1.06%   |
| Positivo            | 9         | 0.87%   |
| MSI                 | 8         | 0.77%   |
| Fujitsu             | 7         | 0.68%   |
| eMachines           | 7         | 0.68%   |
| Panasonic           | 6         | 0.58%   |
| Gateway             | 6         | 0.58%   |
| Medion              | 5         | 0.48%   |
| HUAWEI              | 5         | 0.48%   |
| Notebook            | 4         | 0.39%   |
| NEC Computers       | 4         | 0.39%   |
| Google              | 4         | 0.39%   |
| AMI                 | 4         | 0.39%   |
| Semp Toshiba        | 3         | 0.29%   |
| Quanta              | 3         | 0.29%   |
| Itautec             | 3         | 0.29%   |
| Intel               | 3         | 0.29%   |
| Insyde              | 3         | 0.29%   |
| IBM                 | 3         | 0.29%   |
| Ematic              | 3         | 0.29%   |
| Clevo               | 3         | 0.29%   |
| Alienware           | 3         | 0.29%   |
| TrekStor            | 2         | 0.19%   |
| Phoenix/SiS         | 2         | 0.19%   |
| Durabook            | 2         | 0.19%   |
| Digibras            | 2         | 0.19%   |
| ARIMA               | 2         | 0.19%   |
| WIPRO               | 1         | 0.1%    |
| WinSome             | 1         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 26        | 2.51%   |
| HP Notebook                  | 9         | 0.87%   |
| HP Pavilion dv6              | 7         | 0.68%   |
| Dell Latitude D630           | 6         | 0.58%   |
| Positivo Mobile              | 5         | 0.48%   |
| HP Pavilion dv7              | 5         | 0.48%   |
| HP Pavilion dv6700           | 5         | 0.48%   |
| HP Pavilion 15               | 5         | 0.48%   |
| HP 530                       | 5         | 0.48%   |
| Dell Latitude E6410          | 5         | 0.48%   |
| Dell Latitude E6400          | 5         | 0.48%   |
| Dell Inspiron 1545           | 5         | 0.48%   |
| Toshiba Satellite C660       | 4         | 0.39%   |
| HP Pavilion g7               | 4         | 0.39%   |
| HP Laptop 15-bw0xx           | 4         | 0.39%   |
| HP Compaq Presario CQ61      | 4         | 0.39%   |
| HP 15                        | 4         | 0.39%   |
| Dell Inspiron 1525           | 4         | 0.39%   |
| Acer Aspire one              | 4         | 0.39%   |
| Toshiba Satellite L500       | 3         | 0.29%   |
| Toshiba Satellite C55-A      | 3         | 0.29%   |
| Samsung 340XAA/350XAA/550XAA | 3         | 0.29%   |
| Packard Bell EasyNote TJ65   | 3         | 0.29%   |
| HUAWEI BOHK-WAX9X            | 3         | 0.29%   |
| HP ProBook 4540s             | 3         | 0.29%   |
| HP Pavilion Notebook         | 3         | 0.29%   |
| HP Pavilion g6               | 3         | 0.29%   |
| HP Pavilion dv5              | 3         | 0.29%   |
| HP Pavilion 17               | 3         | 0.29%   |
| HP EliteBook 8460p           | 3         | 0.29%   |
| HP EliteBook 840 G1          | 3         | 0.29%   |
| HP EliteBook 6930p           | 3         | 0.29%   |
| HP Compaq Presario CQ60      | 3         | 0.29%   |
| Dell Latitude E5470          | 3         | 0.29%   |
| Dell Latitude D520           | 3         | 0.29%   |
| Dell Inspiron N4010          | 3         | 0.29%   |
| Dell Inspiron 7520           | 3         | 0.29%   |
| Dell Inspiron 6000           | 3         | 0.29%   |
| Dell Inspiron 3521           | 3         | 0.29%   |
| Dell Inspiron 1520           | 3         | 0.29%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| HP Pavilion              | 69        | 6.67%   |
| Dell Inspiron            | 69        | 6.67%   |
| Acer Aspire              | 67        | 6.48%   |
| Toshiba Satellite        | 64        | 6.19%   |
| Lenovo ThinkPad          | 56        | 5.42%   |
| Dell Latitude            | 51        | 4.93%   |
| Lenovo IdeaPad           | 39        | 3.77%   |
| HP Compaq                | 28        | 2.71%   |
| HP EliteBook             | 27        | 2.61%   |
| Unknown                  | 26        | 2.51%   |
| HP ProBook               | 25        | 2.42%   |
| HP Laptop                | 18        | 1.74%   |
| Packard Bell EasyNote    | 11        | 1.06%   |
| HP Presario              | 10        | 0.97%   |
| Dell Vostro              | 10        | 0.97%   |
| HP Notebook              | 9         | 0.87%   |
| Fujitsu Siemens AMILO    | 8         | 0.77%   |
| HP Mini                  | 7         | 0.68%   |
| HP ENVY                  | 7         | 0.68%   |
| HP 530                   | 7         | 0.68%   |
| HP Stream                | 6         | 0.58%   |
| HP 255                   | 6         | 0.58%   |
| Positivo Mobile          | 5         | 0.48%   |
| HP ZBook                 | 5         | 0.48%   |
| HP 15                    | 5         | 0.48%   |
| Dell XPS                 | 5         | 0.48%   |
| ASUS VivoBook            | 5         | 0.48%   |
| Acer TravelMate          | 5         | 0.48%   |
| Fujitsu LIFEBOOK         | 4         | 0.39%   |
| Dell System              | 4         | 0.39%   |
| Dell Precision           | 4         | 0.39%   |
| ASUS ZenBook             | 4         | 0.39%   |
| ASUS ROG                 | 4         | 0.39%   |
| Acer Extensa             | 4         | 0.39%   |
| Samsung 340XAA           | 3         | 0.29%   |
| Itautec Infoway          | 3         | 0.29%   |
| IBM ThinkPad             | 3         | 0.29%   |
| HUAWEI BOHK-WAX9X        | 3         | 0.29%   |
| Fujitsu Siemens LIFEBOOK | 3         | 0.29%   |
| Fujitsu Siemens ESPRIMO  | 3         | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 101       | 9.77%   |
| 2008    | 97        | 9.38%   |
| 2007    | 97        | 9.38%   |
| 2010    | 94        | 9.09%   |
| 2013    | 82        | 7.93%   |
| 2009    | 79        | 7.64%   |
| 2012    | 75        | 7.25%   |
| 2014    | 63        | 6.09%   |
| 2018    | 61        | 5.9%    |
| 2017    | 53        | 5.13%   |
| 2016    | 48        | 4.64%   |
| 2015    | 46        | 4.45%   |
| 2019    | 45        | 4.35%   |
| 2006    | 39        | 3.77%   |
| 2005    | 35        | 3.38%   |
| 2020    | 12        | 1.16%   |
| Unknown | 3         | 0.29%   |
| 2021    | 2         | 0.19%   |
| 2023    | 1         | 0.1%    |
| 2022    | 1         | 0.1%    |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1034      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 968       | 93.44%  |
| Enabled  | 68        | 6.56%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1029      | 99.52%  |
| Yes  | 5         | 0.48%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 334       | 32.02%  |
| 4.01-8.0    | 211       | 20.23%  |
| 1.01-2.0    | 193       | 18.5%   |
| 8.01-16.0   | 108       | 10.35%  |
| 2.01-3.0    | 70        | 6.71%   |
| 0.51-1.0    | 59        | 5.66%   |
| 16.01-24.0  | 53        | 5.08%   |
| 32.01-64.0  | 12        | 1.15%   |
| 24.01-32.0  | 2         | 0.19%   |
| 64.01-256.0 | 1         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 528       | 47.74%  |
| 2.01-3.0  | 225       | 20.34%  |
| 0.51-1.0  | 205       | 18.54%  |
| 3.01-4.0  | 80        | 7.23%   |
| 4.01-8.0  | 54        | 4.88%   |
| 0.01-0.5  | 11        | 0.99%   |
| 8.01-16.0 | 3         | 0.27%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 812       | 77.41%  |
| 2      | 205       | 19.54%  |
| 3      | 22        | 2.1%    |
| 0      | 5         | 0.48%   |
| 5      | 2         | 0.19%   |
| 4      | 2         | 0.19%   |
| 6      | 1         | 0.1%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 607       | 58.42%  |
| No        | 432       | 41.58%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 923       | 89.09%  |
| No        | 113       | 10.91%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1007      | 97.2%   |
| No        | 29        | 2.8%    |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 566       | 54.21%  |
| No        | 478       | 45.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 190       | 18.3%   |
| Brazil       | 94        | 9.06%   |
| Germany      | 65        | 6.26%   |
| UK           | 55        | 5.3%    |
| Italy        | 52        | 5.01%   |
| Canada       | 43        | 4.14%   |
| India        | 39        | 3.76%   |
| France       | 29        | 2.79%   |
| Spain        | 28        | 2.7%    |
| Poland       | 27        | 2.6%    |
| Portugal     | 24        | 2.31%   |
| Czechia      | 21        | 2.02%   |
| Argentina    | 21        | 2.02%   |
| Netherlands  | 20        | 1.93%   |
| Mexico       | 20        | 1.93%   |
| Sweden       | 16        | 1.54%   |
| Australia    | 16        | 1.54%   |
| Romania      | 15        | 1.45%   |
| Indonesia    | 13        | 1.25%   |
| Greece       | 12        | 1.16%   |
| Turkey       | 11        | 1.06%   |
| South Africa | 11        | 1.06%   |
| Russia       | 10        | 0.96%   |
| New Zealand  | 10        | 0.96%   |
| Serbia       | 9         | 0.87%   |
| Austria      | 9         | 0.87%   |
| Switzerland  | 8         | 0.77%   |
| Japan        | 8         | 0.77%   |
| Chile        | 8         | 0.77%   |
| Belgium      | 8         | 0.77%   |
| Egypt        | 7         | 0.67%   |
| Denmark      | 7         | 0.67%   |
| Colombia     | 7         | 0.67%   |
| Ukraine      | 6         | 0.58%   |
| Philippines  | 6         | 0.58%   |
| Peru         | 6         | 0.58%   |
| Hungary      | 6         | 0.58%   |
| Bulgaria     | 6         | 0.58%   |
| Israel       | 5         | 0.48%   |
| Slovenia     | 4         | 0.39%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 12        | 1.1%    |
| Milan          | 8         | 0.74%   |
| Vienna         | 7         | 0.64%   |
| Prague         | 7         | 0.64%   |
| Johannesburg   | 7         | 0.64%   |
| Istanbul       | 7         | 0.64%   |
| Auckland       | 7         | 0.64%   |
| Sydney         | 6         | 0.55%   |
| Rome           | 6         | 0.55%   |
| Cairo          | 6         | 0.55%   |
| Warsaw         | 5         | 0.46%   |
| Rio de Janeiro | 5         | 0.46%   |
| Munich         | 5         | 0.46%   |
| Montreal       | 5         | 0.46%   |
| Mexico City    | 5         | 0.46%   |
| Madrid         | 5         | 0.46%   |
| Buenos Aires   | 5         | 0.46%   |
| Bucharest      | 5         | 0.46%   |
| Berlin         | 5         | 0.46%   |
| Zurich         | 4         | 0.37%   |
| Winnipeg       | 4         | 0.37%   |
| Tel Aviv       | 4         | 0.37%   |
| Stuttgart      | 4         | 0.37%   |
| Stockholm      | 4         | 0.37%   |
| Sofia          | 4         | 0.37%   |
| Seattle        | 4         | 0.37%   |
| Perth          | 4         | 0.37%   |
| Panama City    | 4         | 0.37%   |
| Nairobi        | 4         | 0.37%   |
| Lisbon         | 4         | 0.37%   |
| Lima           | 4         | 0.37%   |
| Brooklyn       | 4         | 0.37%   |
| Bengaluru      | 4         | 0.37%   |
| Belgrade       | 4         | 0.37%   |
| Amman          | 4         | 0.37%   |
| Toronto        | 3         | 0.28%   |
| The Hague      | 3         | 0.28%   |
| Surabaya       | 3         | 0.28%   |
| Salvador       | 3         | 0.28%   |
| Pune           | 3         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 184       | 219    | 15.75%  |
| Seagate             | 175       | 206    | 14.98%  |
| Toshiba             | 143       | 161    | 12.24%  |
| Samsung Electronics | 112       | 148    | 9.59%   |
| Hitachi             | 100       | 114    | 8.56%   |
| Unknown             | 97        | 134    | 8.3%    |
| Kingston            | 49        | 54     | 4.2%    |
| SanDisk             | 44        | 55     | 3.77%   |
| HGST                | 38        | 47     | 3.25%   |
| Crucial             | 32        | 37     | 2.74%   |
| Fujitsu             | 29        | 30     | 2.48%   |
| Intel               | 20        | 23     | 1.71%   |
| SK hynix            | 11        | 15     | 0.94%   |
| China               | 9         | 9      | 0.77%   |
| A-DATA Technology   | 9         | 9      | 0.77%   |
| Transcend           | 7         | 11     | 0.6%    |
| Micron Technology   | 7         | 8      | 0.6%    |
| Intenso             | 7         | 7      | 0.6%    |
| Apple               | 6         | 6      | 0.51%   |
| PNY                 | 5         | 7      | 0.43%   |
| Phison              | 5         | 8      | 0.43%   |
| Patriot             | 5         | 7      | 0.43%   |
| LITEON              | 5         | 7      | 0.43%   |
| Team                | 4         | 4      | 0.34%   |
| SPCC                | 3         | 4      | 0.26%   |
| SABRENT             | 3         | 3      | 0.26%   |
| OCZ                 | 3         | 3      | 0.26%   |
| LITEONIT            | 3         | 3      | 0.26%   |
| JMicron Technology  | 3         | 3      | 0.26%   |
| GOODRAM             | 3         | 3      | 0.26%   |
| Zheino              | 2         | 2      | 0.17%   |
| TCSUNBOW            | 2         | 2      | 0.17%   |
| Plextor             | 2         | 2      | 0.17%   |
| KIOXIA              | 2         | 2      | 0.17%   |
| KingDian            | 2         | 2      | 0.17%   |
| IBM/Hitachi         | 2         | 3      | 0.17%   |
| Hewlett-Packard     | 2         | 2      | 0.17%   |
| BHT                 | 2         | 2      | 0.17%   |
| ASMT                | 2         | 2      | 0.17%   |
| Verbatim            | 1         | 1      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Unknown MMC Card  32GB              | 43        | 3.6%    |
| Toshiba MQ01ABF050 500GB            | 22        | 1.84%   |
| Unknown MMC Card  64GB              | 17        | 1.42%   |
| Seagate ST500LT012-1DG142 500GB     | 15        | 1.25%   |
| Kingston SA400S37240G 240GB SSD     | 13        | 1.09%   |
| Seagate ST1000LM035-1RK172 1TB      | 12        | 1%      |
| Unknown MMC Card  16GB              | 10        | 0.84%   |
| Seagate ST9500325AS 500GB           | 10        | 0.84%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 10        | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 10        | 0.84%   |
| HGST HTS725050A7E630 500GB          | 10        | 0.84%   |
| Toshiba MQ04ABF100 1TB              | 9         | 0.75%   |
| Toshiba MQ01ABD100 1TB              | 9         | 0.75%   |
| Samsung HM160HI 160GB               | 9         | 0.75%   |
| Hitachi HTS545032B9A300 320GB       | 9         | 0.75%   |
| Unknown MMC Card  128GB             | 8         | 0.67%   |
| Kingston SA400S37480G 480GB SSD     | 8         | 0.67%   |
| Hitachi HTS543232A7A384 320GB       | 8         | 0.67%   |
| Crucial CT240BX500SSD1 240GB        | 8         | 0.67%   |
| Seagate ST9250315AS 250GB           | 7         | 0.59%   |
| Samsung NVMe SSD Drive 512GB        | 7         | 0.59%   |
| Samsung NVMe SSD Drive 256GB        | 7         | 0.59%   |
| Seagate ST9320325AS 320GB           | 6         | 0.5%    |
| Seagate ST9160314AS 160GB           | 6         | 0.5%    |
| Samsung HM321HI 320GB               | 6         | 0.5%    |
| Kingston SA400S37120G 120GB SSD     | 6         | 0.5%    |
| HGST HTS541010A9E680 1TB            | 6         | 0.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 5         | 0.42%   |
| WDC WD3200BEVT-22ZCT0 320GB         | 5         | 0.42%   |
| WDC WD10JPVX-60JC3T0 1TB            | 5         | 0.42%   |
| Toshiba MQ01ABD032 320GB            | 5         | 0.42%   |
| Seagate ST500LT012-9WS142 500GB     | 5         | 0.42%   |
| Samsung SSD 860 EVO 250GB           | 5         | 0.42%   |
| Samsung SSD 850 EVO 500GB           | 5         | 0.42%   |
| Intel NVMe SSD Drive 512GB          | 5         | 0.42%   |
| Hitachi HTS547575A9E384 752GB       | 5         | 0.42%   |
| Hitachi HTS541616J9SA00 160GB       | 5         | 0.42%   |
| HGST HTS721010A9E630 1TB            | 5         | 0.42%   |
| HGST HTS545050A7E680 500GB          | 5         | 0.42%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 4         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 173       | 201    | 25.29%  |
| WDC                 | 171       | 198    | 25%     |
| Toshiba             | 132       | 148    | 19.3%   |
| Hitachi             | 100       | 114    | 14.62%  |
| HGST                | 38        | 47     | 5.56%   |
| Fujitsu             | 29        | 30     | 4.24%   |
| Samsung Electronics | 28        | 33     | 4.09%   |
| SABRENT             | 3         | 3      | 0.44%   |
| Unknown             | 2         | 6      | 0.29%   |
| JMicron Technology  | 2         | 2      | 0.29%   |
| IBM/Hitachi         | 2         | 3      | 0.29%   |
| ASMT                | 2         | 2      | 0.29%   |
| TO Exter            | 1         | 2      | 0.15%   |
| Apple               | 1         | 1      | 0.15%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 64        | 86     | 20%     |
| Kingston            | 43        | 47     | 13.44%  |
| SanDisk             | 33        | 41     | 10.31%  |
| Crucial             | 32        | 37     | 10%     |
| WDC                 | 16        | 21     | 5%      |
| Intel               | 14        | 15     | 4.38%   |
| SK hynix            | 9         | 13     | 2.81%   |
| China               | 9         | 9      | 2.81%   |
| A-DATA Technology   | 9         | 9      | 2.81%   |
| Transcend           | 7         | 11     | 2.19%   |
| Toshiba             | 7         | 8      | 2.19%   |
| Micron Technology   | 6         | 7      | 1.88%   |
| PNY                 | 5         | 7      | 1.56%   |
| Patriot             | 5         | 7      | 1.56%   |
| LITEON              | 5         | 7      | 1.56%   |
| Intenso             | 5         | 5      | 1.56%   |
| Apple               | 5         | 5      | 1.56%   |
| Team                | 4         | 4      | 1.25%   |
| SPCC                | 3         | 4      | 0.94%   |
| OCZ                 | 3         | 3      | 0.94%   |
| LITEONIT            | 3         | 3      | 0.94%   |
| GOODRAM             | 3         | 3      | 0.94%   |
| TCSUNBOW            | 2         | 2      | 0.63%   |
| Plextor             | 2         | 2      | 0.63%   |
| KingDian            | 2         | 2      | 0.63%   |
| BHT                 | 2         | 2      | 0.63%   |
| Zheino              | 1         | 1      | 0.31%   |
| Verbatim            | 1         | 1      | 0.31%   |
| USB30               | 1         | 1      | 0.31%   |
| Unknown             | 1         | 1      | 0.31%   |
| TrekStor            | 1         | 1      | 0.31%   |
| Seagate             | 1         | 1      | 0.31%   |
| PNY USB             | 1         | 1      | 0.31%   |
| Pioneer             | 1         | 1      | 0.31%   |
| Phison              | 1         | 3      | 0.31%   |
| Pacific Sun         | 1         | 1      | 0.31%   |
| OWC                 | 1         | 1      | 0.31%   |
| Maxtor              | 1         | 1      | 0.31%   |
| Lexar               | 1         | 1      | 0.31%   |
| Leven               | 1         | 1      | 0.31%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 666       | 790    | 58.47%  |
| SSD     | 305       | 384    | 26.78%  |
| MMC     | 94        | 131    | 8.25%   |
| NVMe    | 55        | 69     | 4.83%   |
| Unknown | 19        | 21     | 1.67%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 929       | 1149   | 84.07%  |
| MMC  | 94        | 131    | 8.51%   |
| NVMe | 55        | 69     | 4.98%   |
| SAS  | 27        | 46     | 2.44%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 776       | 933    | 80.17%  |
| 0.51-1.0   | 177       | 223    | 18.29%  |
| 1.01-2.0   | 12        | 15     | 1.24%   |
| 4.01-10.0  | 2         | 2      | 0.21%   |
| 3.01-4.0   | 1         | 1      | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 379       | 35.86%  |
| 251-500        | 270       | 25.54%  |
| 51-100         | 137       | 12.96%  |
| 501-1000       | 100       | 9.46%   |
| 21-50          | 79        | 7.47%   |
| 1-20           | 46        | 4.35%   |
| 1001-2000      | 33        | 3.12%   |
| More than 3000 | 6         | 0.57%   |
| Unknown        | 4         | 0.38%   |
| 2001-3000      | 3         | 0.28%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 685       | 62.73%  |
| 21-50          | 182       | 16.67%  |
| 51-100         | 88        | 8.06%   |
| 101-250        | 72        | 6.59%   |
| 251-500        | 38        | 3.48%   |
| 501-1000       | 12        | 1.1%    |
| 1001-2000      | 6         | 0.55%   |
| More than 3000 | 4         | 0.37%   |
| Unknown        | 4         | 0.37%   |
| 2001-3000      | 1         | 0.09%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                               | Notebooks | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                           | 2         | 2      | 16.67%  |
| WDC WD3200BPVT-55ZEST0 320GB                        | 1         | 1      | 8.33%   |
| Toshiba MK5061GSY 500GB                             | 1         | 1      | 8.33%   |
| Seagate ST9320325AS 320GB                           | 1         | 1      | 8.33%   |
| Seagate ST9160314AS 160GB                           | 1         | 1      | 8.33%   |
| Seagate ST9120822AS 120GB                           | 1         | 1      | 8.33%   |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 8.33%   |
| Micron Technology MTFDDAV256TBN-1AR15ABHA 256GB SSD | 1         | 1      | 8.33%   |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 8.33%   |
| Hitachi HTS543280L9SA00 80GB                        | 1         | 1      | 8.33%   |
| Hitachi HTS541616J9SA00 160GB                       | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 6         | 6      | 50%     |
| Hitachi           | 3         | 3      | 25%     |
| WDC               | 1         | 1      | 8.33%   |
| Toshiba           | 1         | 1      | 8.33%   |
| Micron Technology | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 6         | 6      | 54.55%  |
| Hitachi | 3         | 3      | 27.27%  |
| WDC     | 1         | 1      | 9.09%   |
| Toshiba | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 11     | 91.67%  |
| SSD  | 1         | 1      | 8.33%   |

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
| Detected | 1006      | 1362   | 97.1%   |
| Works    | 18        | 21     | 1.74%   |
| Malfunc  | 12        | 12     | 1.16%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 773       | 74.4%   |
| AMD                              | 141       | 13.57%  |
| Silicon Integrated Systems [SiS] | 28        | 2.69%   |
| Nvidia                           | 26        | 2.5%    |
| Samsung Electronics              | 25        | 2.41%   |
| VIA Technologies                 | 10        | 0.96%   |
| SanDisk                          | 8         | 0.77%   |
| Kingston Technology Company      | 6         | 0.58%   |
| Toshiba America Info Systems     | 5         | 0.48%   |
| JMicron Technology               | 5         | 0.48%   |
| Phison Electronics               | 3         | 0.29%   |
| KIOXIA                           | 2         | 0.19%   |
| Union Memory (Shenzhen)          | 1         | 0.1%    |
| SK hynix                         | 1         | 0.1%    |
| Silicon Image                    | 1         | 0.1%    |
| Realtek Semiconductor            | 1         | 0.1%    |
| Micron/Crucial Technology        | 1         | 0.1%    |
| Micron Technology                | 1         | 0.1%    |
| Marvell Technology Group         | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                    | 85        | 6.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 78        | 6.34%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 73        | 5.93%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 72        | 5.85%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 68        | 5.52%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 63        | 5.12%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 50        | 4.06%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 48        | 3.9%    |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 39        | 3.17%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 38        | 3.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 38        | 3.09%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 30        | 2.44%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 29        | 2.36%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 29        | 2.36%   |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                   | 28        | 2.27%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 27        | 2.19%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 26        | 2.11%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                            | 22        | 1.79%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 21        | 1.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 18        | 1.46%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 16        | 1.3%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 15        | 1.22%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                               | 15        | 1.22%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 14        | 1.14%   |
| Intel 82801FBM (ICH6M) SATA Controller                                                 | 13        | 1.06%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 13        | 1.06%   |
| AMD IXP SB4x0 IDE Controller                                                           | 12        | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 10        | 0.81%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 10        | 0.81%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 9         | 0.73%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 9         | 0.73%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                            | 8         | 0.65%   |
| Nvidia MCP67 AHCI Controller                                                           | 8         | 0.65%   |
| AMD FCH IDE Controller                                                                 | 8         | 0.65%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 7         | 0.57%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 7         | 0.57%   |
| Nvidia MCP79 AHCI Controller                                                           | 6         | 0.49%   |
| Nvidia MCP67 IDE Controller                                                            | 6         | 0.49%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 4-5) | 6         | 0.49%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 6         | 0.49%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 739       | 65.05%  |
| IDE  | 290       | 25.53%  |
| NVMe | 56        | 4.93%   |
| RAID | 51        | 4.49%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 867       | 83.85%  |
| AMD          | 165       | 15.96%  |
| CentaurHauls | 2         | 0.19%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz                 | 15        | 1.45%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 14        | 1.35%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 13        | 1.26%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 13        | 1.26%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 12        | 1.16%   |
| Intel Atom CPU N455 @ 1.66GHz                 | 12        | 1.16%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 1.06%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 11        | 1.06%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz          | 11        | 1.06%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 11        | 1.06%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 9         | 0.87%   |
| Intel Core 2 Duo CPU T7250 @ 2.00GHz          | 9         | 0.87%   |
| Intel Core 2 Duo CPU T6600 @ 2.20GHz          | 9         | 0.87%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 9         | 0.87%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz   | 8         | 0.77%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 8         | 0.77%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 8         | 0.77%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 8         | 0.77%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 8         | 0.77%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 8         | 0.77%   |
| Intel Pentium Dual CPU T3400 @ 2.16GHz        | 7         | 0.68%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 0.68%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 7         | 0.68%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 7         | 0.68%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 7         | 0.68%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 7         | 0.68%   |
| Intel Celeron CPU N3050 @ 1.60GHz             | 7         | 0.68%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 7         | 0.68%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 0.68%   |
| AMD E-450 APU with Radeon HD Graphics         | 7         | 0.68%   |
| Intel Pentium M processor 1.73GHz             | 6         | 0.58%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 6         | 0.58%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 6         | 0.58%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz   | 6         | 0.58%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 6         | 0.58%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 6         | 0.58%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 0.58%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 6         | 0.58%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 6         | 0.58%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 6         | 0.58%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 162       | 15.67%  |
| Intel Core i7           | 132       | 12.77%  |
| Intel Core 2 Duo        | 117       | 11.32%  |
| Intel Core i3           | 98        | 9.48%   |
| Intel Celeron           | 88        | 8.51%   |
| Intel Atom              | 84        | 8.12%   |
| Intel Genuine           | 34        | 3.29%   |
| Intel Pentium           | 29        | 2.8%    |
| Intel Pentium Dual-Core | 26        | 2.51%   |
| Intel Pentium M         | 23        | 2.22%   |
| Intel Celeron M         | 23        | 2.22%   |
| Intel Pentium Dual      | 18        | 1.74%   |
| AMD A6                  | 18        | 1.74%   |
| Intel Core 2            | 15        | 1.45%   |
| AMD A4                  | 15        | 1.45%   |
| AMD Ryzen 5             | 11        | 1.06%   |
| AMD Ryzen 3             | 11        | 1.06%   |
| AMD E                   | 11        | 1.06%   |
| AMD Turion 64 X2 Mobile | 9         | 0.87%   |
| AMD E1                  | 9         | 0.87%   |
| AMD Turion 64 Mobile    | 8         | 0.77%   |
| AMD Ryzen 7             | 7         | 0.68%   |
| AMD A8                  | 7         | 0.68%   |
| AMD Mobile Sempron      | 6         | 0.58%   |
| AMD C-50                | 6         | 0.58%   |
| AMD A10                 | 6         | 0.58%   |
| Intel Core Duo          | 5         | 0.48%   |
| Intel Celeron Dual-Core | 5         | 0.48%   |
| AMD Athlon 64 X2        | 5         | 0.48%   |
| Other                   | 4         | 0.39%   |
| AMD Sempron             | 4         | 0.39%   |
| AMD E2                  | 4         | 0.39%   |
| AMD C-60                | 4         | 0.39%   |
| AMD Athlon X2           | 4         | 0.39%   |
| Intel Core M            | 2         | 0.19%   |
| CentaurHauls VIA C7     | 2         | 0.19%   |
| AMD Turion Dual-Core    | 2         | 0.19%   |
| AMD Ryzen 9             | 2         | 0.19%   |
| AMD Phenom II           | 2         | 0.19%   |
| AMD Athlon II           | 2         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 697       | 67.41%  |
| 4      | 168       | 16.25%  |
| 1      | 149       | 14.41%  |
| 6      | 13        | 1.26%   |
| 8      | 6         | 0.58%   |
| 3      | 1         | 0.1%    |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1034      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 543       | 52.51%  |
| 2      | 491       | 47.49%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 933       | 90.14%  |
| 32-bit         | 101       | 9.76%   |
| Unknown        | 1         | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 111       | 10.6%   |
| 0x206a7    | 96        | 9.17%   |
| 0x1067a    | 78        | 7.45%   |
| 0x306a9    | 62        | 5.92%   |
| 0x6fd      | 55        | 5.25%   |
| 0x40651    | 41        | 3.92%   |
| 0x20655    | 32        | 3.06%   |
| 0x406e3    | 29        | 2.77%   |
| 0x306c3    | 29        | 2.77%   |
| 0x106ca    | 28        | 2.67%   |
| 0x6d8      | 27        | 2.58%   |
| 0x6e8      | 26        | 2.48%   |
| 0x306d4    | 24        | 2.29%   |
| 0x806e9    | 22        | 2.1%    |
| 0x30678    | 21        | 2.01%   |
| 0x10676    | 21        | 2.01%   |
| 0x106c2    | 20        | 1.91%   |
| 0x406c4    | 19        | 1.81%   |
| 0x806ea    | 18        | 1.72%   |
| 0x10661    | 17        | 1.62%   |
| 0x6ec      | 15        | 1.43%   |
| 0x406c3    | 15        | 1.43%   |
| 0x06006705 | 15        | 1.43%   |
| 0x6f6      | 14        | 1.34%   |
| 0x05000119 | 14        | 1.34%   |
| 0x20652    | 12        | 1.15%   |
| 0x906ea    | 11        | 1.05%   |
| 0x906e9    | 10        | 0.96%   |
| 0x6fb      | 10        | 0.96%   |
| 0x506c9    | 9         | 0.86%   |
| 0x06001119 | 9         | 0.86%   |
| 0x05000029 | 9         | 0.86%   |
| 0x08108102 | 8         | 0.76%   |
| 0x0700010f | 8         | 0.76%   |
| 0x806ec    | 7         | 0.67%   |
| 0x08108109 | 7         | 0.67%   |
| 0x03000027 | 7         | 0.67%   |
| 0x806eb    | 6         | 0.57%   |
| 0x706a1    | 6         | 0.57%   |
| 0x0810100b | 6         | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Penryn          | 109       | 10.54%  |
| Core            | 108       | 10.44%  |
| SandyBridge     | 96        | 9.28%   |
| KabyLake        | 82        | 7.93%   |
| Haswell         | 77        | 7.45%   |
| P6              | 73        | 7.06%   |
| Silvermont      | 72        | 6.96%   |
| IvyBridge       | 67        | 6.48%   |
| Bonnell         | 53        | 5.13%   |
| Westmere        | 48        | 4.64%   |
| Skylake         | 34        | 3.29%   |
| K8 Hammer       | 32        | 3.09%   |
| Broadwell       | 24        | 2.32%   |
| Bobcat          | 24        | 2.32%   |
| Excavator       | 19        | 1.84%   |
| Zen+            | 15        | 1.45%   |
| Puma            | 12        | 1.16%   |
| Jaguar          | 11        | 1.06%   |
| Piledriver      | 10        | 0.97%   |
| Goldmont        | 10        | 0.97%   |
| K8 & K10 hybrid | 9         | 0.87%   |
| K10             | 8         | 0.77%   |
| Zen 2           | 7         | 0.68%   |
| Zen             | 7         | 0.68%   |
| K10 Llano       | 7         | 0.68%   |
| Goldmont plus   | 7         | 0.68%   |
| Unknown         | 4         | 0.39%   |
| IceLake         | 3         | 0.29%   |
| Steamroller     | 2         | 0.19%   |
| CometLake       | 2         | 0.19%   |
| NetBurst        | 1         | 0.1%    |
| Nehalem         | 1         | 0.1%    |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 717       | 60.76%  |
| AMD                              | 233       | 19.75%  |
| Nvidia                           | 195       | 16.53%  |
| Silicon Integrated Systems [SiS] | 25        | 2.12%   |
| VIA Technologies                 | 10        | 0.85%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 85        | 6.51%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 65        | 4.98%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 63        | 4.83%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 58        | 4.44%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 47        | 3.6%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 47        | 3.6%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 43        | 3.3%    |
| Intel Core Processor Integrated Graphics Controller                                      | 39        | 2.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 39        | 2.99%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 37        | 2.84%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 33        | 2.53%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 33        | 2.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 30        | 2.3%    |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 29        | 2.22%   |
| Intel HD Graphics 620                                                                    | 28        | 2.15%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 21        | 1.61%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 21        | 1.61%   |
| Intel HD Graphics 5500                                                                   | 20        | 1.53%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 18        | 1.38%   |
| Intel UHD Graphics 620                                                                   | 16        | 1.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 15        | 1.15%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 12        | 0.92%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 12        | 0.92%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 12        | 0.92%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 10        | 0.77%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 10        | 0.77%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 9         | 0.69%   |
| Intel HD Graphics 500                                                                    | 9         | 0.69%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 9         | 0.69%   |
| Intel HD Graphics 630                                                                    | 8         | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 7         | 0.54%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 7         | 0.54%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 0.54%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 7         | 0.54%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 7         | 0.54%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 0.54%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 6         | 0.46%   |
| Nvidia C67 [GeForce 7150M / nForce 630M]                                                 | 6         | 0.46%   |
| AMD Wrestler [Radeon HD 6250]                                                            | 6         | 0.46%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 6         | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 575       | 55.5%   |
| 1 x AMD        | 168       | 16.22%  |
| Intel + Nvidia | 97        | 9.36%   |
| 1 x Nvidia     | 91        | 8.78%   |
| Intel + AMD    | 44        | 4.25%   |
| 1 x SiS        | 25        | 2.41%   |
| 2 x AMD        | 16        | 1.54%   |
| 1 x VIA        | 10        | 0.97%   |
| AMD + Nvidia   | 5         | 0.48%   |
| 2 x Nvidia     | 3         | 0.29%   |
| Other          | 2         | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 887       | 85.45%  |
| Proprietary | 82        | 7.9%    |
| Unknown     | 69        | 6.65%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 699       | 67.02%  |
| 0.01-0.5   | 192       | 18.41%  |
| 1.01-2.0   | 65        | 6.23%   |
| 0.51-1.0   | 58        | 5.56%   |
| 3.01-4.0   | 23        | 2.21%   |
| 7.01-8.0   | 3         | 0.29%   |
| 5.01-6.0   | 2         | 0.19%   |
| 2.01-3.0   | 1         | 0.1%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 197       | 20.16%  |
| Samsung Electronics     | 161       | 16.48%  |
| LG Display              | 153       | 15.66%  |
| Chimei Innolux          | 91        | 9.31%   |
| BOE                     | 78        | 7.98%   |
| Chi Mei Optoelectronics | 55        | 5.63%   |
| LG Philips              | 43        | 4.4%    |
| Apple                   | 18        | 1.84%   |
| Lenovo                  | 16        | 1.64%   |
| InfoVision              | 16        | 1.64%   |
| Toshiba                 | 12        | 1.23%   |
| HannStar                | 10        | 1.02%   |
| Goldstar                | 10        | 1.02%   |
| CPT                     | 10        | 1.02%   |
| Sharp                   | 9         | 0.92%   |
| Dell                    | 9         | 0.92%   |
| Seiko/Epson             | 8         | 0.82%   |
| Quanta Display          | 8         | 0.82%   |
| Sony                    | 6         | 0.61%   |
| PANDA                   | 5         | 0.51%   |
| LGD                     | 5         | 0.51%   |
| InnoLux Display         | 5         | 0.51%   |
| Panasonic               | 4         | 0.41%   |
| Hewlett-Packard         | 4         | 0.41%   |
| Eizo                    | 4         | 0.41%   |
| AOC                     | 4         | 0.41%   |
| Acer                    | 4         | 0.41%   |
| Unknown                 | 3         | 0.31%   |
| Nvidia                  | 3         | 0.31%   |
| ___                     | 2         | 0.2%    |
| ViewSonic               | 2         | 0.2%    |
| Philips                 | 2         | 0.2%    |
| Iiyama                  | 2         | 0.2%    |
| IBM                     | 2         | 0.2%    |
| BenQ                    | 2         | 0.2%    |
| Vizio                   | 1         | 0.1%    |
| Vestel Elektronik       | 1         | 0.1%    |
| Vestel                  | 1         | 0.1%    |
| Unknown (AAA)           | 1         | 0.1%    |
| TM@                     | 1         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 15        | 1.52%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 286x179mm 13.3-inch     | 13        | 1.32%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 9         | 0.91%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 9         | 0.91%   |
| LG Display LCD Monitor LGD033A 1366x768 340x190mm 15.3-inch              | 7         | 0.71%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 7         | 0.71%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 7         | 0.71%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 6         | 0.61%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 6         | 0.61%   |
| Samsung Electronics LCD Monitor SEC3633 1280x800 331x207mm 15.4-inch     | 5         | 0.51%   |
| LG Philips LCD Monitor LPLDB00 1280x800 331x207mm 15.4-inch              | 5         | 0.51%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 5         | 0.51%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch              | 5         | 0.51%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 5         | 0.51%   |
| InfoVision LCD Monitor IVO0489 1366x768 256x144mm 11.6-inch              | 5         | 0.51%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 5         | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 5         | 0.51%   |
| Chi Mei Optoelectronics LCD Monitor CMO1007 1024x600 222x125mm 10.0-inch | 5         | 0.51%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 5         | 0.51%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 5         | 0.51%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 5         | 0.51%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 5         | 0.51%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 5         | 0.51%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 5         | 0.51%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x215mm 17.3-inch     | 4         | 0.41%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch     | 4         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3358 1280x800 331x207mm 15.4-inch     | 4         | 0.41%   |
| Samsung Electronics LCD Monitor SEC3345 1280x800 331x207mm 15.4-inch     | 4         | 0.41%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch     | 4         | 0.41%   |
| LG Philips LCD Monitor LPLBC00 1280x800 331x207mm 15.4-inch              | 4         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 4         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15C3 1920x1080 344x193mm 15.5-inch         | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO61D2 1024x600 222x125mm 10.0-inch            | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO2174 1280x800 331x207mm 15.4-inch            | 4         | 0.41%   |
| AU Optronics LCD Monitor AUO193C 1366x768 309x173mm 13.9-inch            | 4         | 0.41%   |
| Seiko/Epson LCD Monitor 1280x800                                         | 3         | 0.3%    |
| Samsung Electronics LCD Monitor SEC5442 1440x900 331x207mm 15.4-inch     | 3         | 0.3%    |
| Samsung Electronics LCD Monitor SEC4C42 1280x800 303x190mm 14.1-inch     | 3         | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 429       | 44.46%  |
| 1920x1080 (FHD)    | 185       | 19.17%  |
| 1280x800 (WXGA)    | 126       | 13.06%  |
| 1600x900 (HD+)     | 67        | 6.94%   |
| 1024x600           | 36        | 3.73%   |
| 1440x900 (WXGA+)   | 34        | 3.52%   |
| 3840x2160 (4K)     | 14        | 1.45%   |
| 1920x1200 (WUXGA)  | 14        | 1.45%   |
| 1680x1050 (WSXGA+) | 11        | 1.14%   |
| 1024x768 (XGA)     | 8         | 0.83%   |
| 1280x768           | 7         | 0.73%   |
| 2560x1600          | 4         | 0.41%   |
| 1360x768           | 4         | 0.41%   |
| 1280x1024 (SXGA)   | 4         | 0.41%   |
| 2560x1440 (QHD)    | 3         | 0.31%   |
| 1400x1050          | 3         | 0.31%   |
| 1024x576           | 3         | 0.31%   |
| 3200x1800 (QHD+)   | 2         | 0.21%   |
| 1680x945           | 2         | 0.21%   |
| 5760x2160          | 1         | 0.1%    |
| 3840x1080          | 1         | 0.1%    |
| 2880x1800          | 1         | 0.1%    |
| 2560x1080          | 1         | 0.1%    |
| 2288x1287          | 1         | 0.1%    |
| 2160x1440          | 1         | 0.1%    |
| 2048x1152          | 1         | 0.1%    |
| 1920x540           | 1         | 0.1%    |
| Unknown            | 1         | 0.1%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 454       | 46.42%  |
| 14      | 113       | 11.55%  |
| 13      | 111       | 11.35%  |
| 17      | 83        | 8.49%   |
| 10      | 40        | 4.09%   |
| 11      | 32        | 3.27%   |
| Unknown | 32        | 3.27%   |
| 12      | 23        | 2.35%   |
| 24      | 13        | 1.33%   |
| 21      | 12        | 1.23%   |
| 27      | 8         | 0.82%   |
| 23      | 7         | 0.72%   |
| 72      | 6         | 0.61%   |
| 31      | 5         | 0.51%   |
| 18      | 5         | 0.51%   |
| 22      | 4         | 0.41%   |
| 20      | 4         | 0.41%   |
| 8       | 3         | 0.31%   |
| 84      | 2         | 0.2%    |
| 54      | 2         | 0.2%    |
| 40      | 2         | 0.2%    |
| 34      | 2         | 0.2%    |
| 19      | 2         | 0.2%    |
| 74      | 1         | 0.1%    |
| 59      | 1         | 0.1%    |
| 58      | 1         | 0.1%    |
| 55      | 1         | 0.1%    |
| 49      | 1         | 0.1%    |
| 46      | 1         | 0.1%    |
| 44      | 1         | 0.1%    |
| 41      | 1         | 0.1%    |
| 36      | 1         | 0.1%    |
| 33      | 1         | 0.1%    |
| 32      | 1         | 0.1%    |
| 29      | 1         | 0.1%    |
| 16      | 1         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 619       | 63.49%  |
| 201-300     | 136       | 13.95%  |
| 351-400     | 99        | 10.15%  |
| Unknown     | 32        | 3.28%   |
| 501-600     | 28        | 2.87%   |
| 401-500     | 27        | 2.77%   |
| 1501-2000   | 9         | 0.92%   |
| 1001-1500   | 7         | 0.72%   |
| 601-700     | 6         | 0.62%   |
| 701-800     | 5         | 0.51%   |
| 101-200     | 3         | 0.31%   |
| 801-900     | 2         | 0.21%   |
| 901-1000    | 2         | 0.21%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 694       | 75.27%  |
| 16/10   | 182       | 19.74%  |
| Unknown | 27        | 2.93%   |
| 4/3     | 12        | 1.3%    |
| 5/4     | 4         | 0.43%   |
| 32/9    | 1         | 0.11%   |
| 3/2     | 1         | 0.11%   |
| 21/9    | 1         | 0.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 454       | 46.61%  |
| 81-90          | 189       | 19.4%   |
| 121-130        | 46        | 4.72%   |
| 41-50          | 40        | 4.11%   |
| 131-140        | 33        | 3.39%   |
| 51-60          | 32        | 3.29%   |
| Unknown        | 32        | 3.29%   |
| 71-80          | 29        | 2.98%   |
| 201-250        | 25        | 2.57%   |
| 61-70          | 23        | 2.36%   |
| More than 1000 | 14        | 1.44%   |
| 151-200        | 10        | 1.03%   |
| 351-500        | 9         | 0.92%   |
| 141-150        | 9         | 0.92%   |
| 301-350        | 8         | 0.82%   |
| 501-1000       | 8         | 0.82%   |
| 251-300        | 5         | 0.51%   |
| 91-100         | 5         | 0.51%   |
| 1-40           | 3         | 0.31%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 472       | 49.12%  |
| 51-100        | 213       | 22.16%  |
| 121-160       | 205       | 21.33%  |
| Unknown       | 32        | 3.33%   |
| 161-240       | 21        | 2.19%   |
| 1-50          | 13        | 1.35%   |
| More than 240 | 5         | 0.52%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 886       | 84.06%  |
| 2     | 90        | 8.54%   |
| 0     | 73        | 6.93%   |
| 3     | 5         | 0.47%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 519       | 29.41%  |
| Intel                                  | 386       | 21.87%  |
| Qualcomm Atheros                       | 318       | 18.02%  |
| Broadcom                               | 210       | 11.9%   |
| Broadcom Limited                       | 68        | 3.85%   |
| Marvell Technology Group               | 44        | 2.49%   |
| Silicon Integrated Systems [SiS]       | 27        | 1.53%   |
| Ralink                                 | 23        | 1.3%    |
| Nvidia                                 | 22        | 1.25%   |
| Ralink Technology                      | 13        | 0.74%   |
| TP-Link                                | 12        | 0.68%   |
| JMicron Technology                     | 12        | 0.68%   |
| VIA Technologies                       | 8         | 0.45%   |
| Xiaomi                                 | 7         | 0.4%    |
| Sierra Wireless                        | 7         | 0.4%    |
| Samsung Electronics                    | 7         | 0.4%    |
| AMD                                    | 7         | 0.4%    |
| Qualcomm Atheros Communications        | 6         | 0.34%   |
| ASUSTek Computer                       | 6         | 0.34%   |
| ASIX Electronics                       | 6         | 0.34%   |
| Dell                                   | 5         | 0.28%   |
| Motorola PCS                           | 4         | 0.23%   |
| MediaTek                               | 4         | 0.23%   |
| Huawei Technologies                    | 4         | 0.23%   |
| Hewlett-Packard                        | 4         | 0.23%   |
| Edimax Technology                      | 4         | 0.23%   |
| Attansic Technology                    | 4         | 0.23%   |
| OPPO Electronics                       | 3         | 0.17%   |
| NetGear                                | 3         | 0.17%   |
| D-Link                                 | 3         | 0.17%   |
| Micro Star International               | 2         | 0.11%   |
| DisplayLink                            | 2         | 0.11%   |
| Davicom Semiconductor                  | 2         | 0.11%   |
| ZyDAS                                  | 1         | 0.06%   |
| Toshiba                                | 1         | 0.06%   |
| T & A Mobile Phones                    | 1         | 0.06%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.06%   |
| Sitecom Europe                         | 1         | 0.06%   |
| Qcom                                   | 1         | 0.06%   |
| Lite-On Technology                     | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 228       | 10.8%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 176       | 8.34%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 67        | 3.17%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 49        | 2.32%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 43        | 2.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 41        | 1.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 40        | 1.89%   |
| Intel Wireless 7260                                                     | 38        | 1.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 37        | 1.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 36        | 1.71%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 34        | 1.61%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 33        | 1.56%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 29        | 1.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 27        | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 24        | 1.14%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 22        | 1.04%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 22        | 1.04%   |
| Intel WiFi Link 5100                                                    | 21        | 0.99%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 21        | 0.99%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 21        | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                           | 20        | 0.95%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 19        | 0.9%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 19        | 0.9%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 18        | 0.85%   |
| Intel Wireless 3165                                                     | 17        | 0.81%   |
| Intel Wireless 8265 / 8275                                              | 16        | 0.76%   |
| Intel Wireless 7265                                                     | 15        | 0.71%   |
| Intel Wireless 3160                                                     | 14        | 0.66%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 14        | 0.66%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 14        | 0.66%   |
| Broadcom BCM4401-B0 100Base-TX                                          | 14        | 0.66%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 13        | 0.62%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 13        | 0.62%   |
| Intel Ethernet Connection I218-LM                                       | 13        | 0.62%   |
| Intel Ethernet Connection I217-LM                                       | 13        | 0.62%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller     | 13        | 0.62%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 12        | 0.57%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 12        | 0.57%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                              | 12        | 0.57%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 12        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 343       | 31.15%  |
| Qualcomm Atheros                | 272       | 24.7%   |
| Realtek Semiconductor           | 191       | 17.35%  |
| Broadcom                        | 154       | 13.99%  |
| Broadcom Limited                | 48        | 4.36%   |
| Ralink                          | 23        | 2.09%   |
| Ralink Technology               | 13        | 1.18%   |
| TP-Link                         | 11        | 1%      |
| Sierra Wireless                 | 7         | 0.64%   |
| Qualcomm Atheros Communications | 6         | 0.54%   |
| ASUSTek Computer                | 6         | 0.54%   |
| Edimax Technology               | 4         | 0.36%   |
| NetGear                         | 3         | 0.27%   |
| D-Link                          | 3         | 0.27%   |
| Micro Star International        | 2         | 0.18%   |
| MediaTek                        | 2         | 0.18%   |
| Hewlett-Packard                 | 2         | 0.18%   |
| Dell                            | 2         | 0.18%   |
| ZyDAS                           | 1         | 0.09%   |
| Xiaomi                          | 1         | 0.09%   |
| Sitecom Europe                  | 1         | 0.09%   |
| Qcom                            | 1         | 0.09%   |
| Lite-On Technology              | 1         | 0.09%   |
| Linksys                         | 1         | 0.09%   |
| IMC Networks                    | 1         | 0.09%   |
| D-Link System                   | 1         | 0.09%   |
| Belkin Components               | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 67        | 6.04%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 49        | 4.41%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 43        | 3.87%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 41        | 3.69%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 40        | 3.6%    |
| Intel Wireless 7260                                                     | 38        | 3.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 37        | 3.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 34        | 3.06%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 33        | 2.97%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 27        | 2.43%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 24        | 2.16%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 22        | 1.98%   |
| Intel WiFi Link 5100                                                    | 21        | 1.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 21        | 1.89%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 21        | 1.89%   |
| Broadcom BCM43142 802.11b/g/n                                           | 20        | 1.8%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 18        | 1.62%   |
| Intel Wireless 3165                                                     | 17        | 1.53%   |
| Intel Wireless 8265 / 8275                                              | 16        | 1.44%   |
| Intel Wireless 7265                                                     | 15        | 1.35%   |
| Intel Wireless 3160                                                     | 14        | 1.26%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                            | 14        | 1.26%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 14        | 1.26%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 13        | 1.17%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller     | 13        | 1.17%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 12        | 1.08%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 12        | 1.08%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 12        | 1.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 11        | 0.99%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 11        | 0.99%   |
| Ralink MT7601U Wireless Adapter                                         | 11        | 0.99%   |
| Intel Centrino Ultimate-N 6300                                          | 11        | 0.99%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 10        | 0.9%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 10        | 0.9%    |
| Intel Wireless 8260                                                     | 10        | 0.9%    |
| Intel Centrino Wireless-N 2230                                          | 10        | 0.9%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 9         | 0.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 9         | 0.81%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 9         | 0.81%   |
| Intel Wi-Fi 6 AX200                                                     | 9         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 447       | 47.15%  |
| Intel                                  | 163       | 17.19%  |
| Qualcomm Atheros                       | 87        | 9.18%   |
| Broadcom                               | 80        | 8.44%   |
| Marvell Technology Group               | 44        | 4.64%   |
| Silicon Integrated Systems [SiS]       | 25        | 2.64%   |
| Broadcom Limited                       | 23        | 2.43%   |
| Nvidia                                 | 22        | 2.32%   |
| JMicron Technology                     | 12        | 1.27%   |
| VIA Technologies                       | 8         | 0.84%   |
| Xiaomi                                 | 6         | 0.63%   |
| ASIX Electronics                       | 6         | 0.63%   |
| Motorola PCS                           | 4         | 0.42%   |
| Attansic Technology                    | 4         | 0.42%   |
| OPPO Electronics                       | 3         | 0.32%   |
| Huawei Technologies                    | 3         | 0.32%   |
| Samsung Electronics                    | 2         | 0.21%   |
| MediaTek                               | 2         | 0.21%   |
| DisplayLink                            | 2         | 0.21%   |
| Davicom Semiconductor                  | 2         | 0.21%   |
| TP-Link                                | 1         | 0.11%   |
| T & A Mobile Phones                    | 1         | 0.11%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.11%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 228       | 24%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 176       | 18.53%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 36        | 3.79%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 29        | 3.05%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 22        | 2.32%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 19        | 2%      |
| Broadcom BCM4401-B0 100Base-TX                                         | 14        | 1.47%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 13        | 1.37%   |
| Intel Ethernet Connection I218-LM                                      | 13        | 1.37%   |
| Intel Ethernet Connection I217-LM                                      | 13        | 1.37%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 12        | 1.26%   |
| Intel 82567LM Gigabit Network Connection                               | 11        | 1.16%   |
| Intel 82577LM Gigabit Network Connection                               | 10        | 1.05%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 10        | 1.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 9         | 0.95%   |
| Intel 82566MM Gigabit Network Connection                               | 9         | 0.95%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 9         | 0.95%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 9         | 0.95%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 8         | 0.84%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 8         | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 8         | 0.84%   |
| Nvidia MCP67 Ethernet                                                  | 8         | 0.84%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 8         | 0.84%   |
| Intel Ethernet Connection I219-LM                                      | 8         | 0.84%   |
| Intel 82579V Gigabit Network Connection                                | 8         | 0.84%   |
| Intel 82562ET/EZ/GT/GZ - PRO/100 VE (LOM) Ethernet Controller Mobile   | 8         | 0.84%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 7         | 0.74%   |
| Intel PRO/100 VE Network Connection                                    | 7         | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                                  | 7         | 0.74%   |
| Broadcom Limited BCM4401-B0 100Base-TX                                 | 7         | 0.74%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 6         | 0.63%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 6         | 0.63%   |
| Nvidia MCP79 Ethernet                                                  | 6         | 0.63%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 6         | 0.63%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 6         | 0.63%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 6         | 0.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 5         | 0.53%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 5         | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 5         | 0.53%   |
| Nvidia MCP77 Ethernet                                                  | 5         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1006      | 50.83%  |
| Ethernet | 922       | 46.59%  |
| Modem    | 51        | 2.58%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 829       | 77.19%  |
| Ethernet | 245       | 22.81%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 862       | 83.29%  |
| 1     | 136       | 13.14%  |
| 0     | 33        | 3.19%   |
| 3     | 4         | 0.39%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 944       | 90.33%  |
| Yes  | 101       | 9.67%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 153       | 26.84%  |
| Qualcomm Atheros Communications | 77        | 13.51%  |
| Realtek Semiconductor           | 63        | 11.05%  |
| Broadcom                        | 62        | 10.88%  |
| Hewlett-Packard                 | 32        | 5.61%   |
| Dell                            | 32        | 5.61%   |
| Lite-On Technology              | 25        | 4.39%   |
| Foxconn / Hon Hai               | 20        | 3.51%   |
| IMC Networks                    | 16        | 2.81%   |
| Apple                           | 15        | 2.63%   |
| Toshiba                         | 12        | 2.11%   |
| Ralink                          | 9         | 1.58%   |
| Cambridge Silicon Radio         | 9         | 1.58%   |
| Alps Electric                   | 9         | 1.58%   |
| Realtek                         | 7         | 1.23%   |
| ASUSTek Computer                | 7         | 1.23%   |
| Foxconn International           | 6         | 1.05%   |
| Taiyo Yuden                     | 3         | 0.53%   |
| Ralink Technology               | 3         | 0.53%   |
| Dynex                           | 3         | 0.53%   |
| Askey Computer                  | 2         | 0.35%   |
| TP-Link                         | 1         | 0.18%   |
| Qcom                            | 1         | 0.18%   |
| MediaTek                        | 1         | 0.18%   |
| Chicony Electronics             | 1         | 0.18%   |
| Actiontec Electronics           | 1         | 0.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 102       | 17.86%  |
| Realtek Bluetooth Radio                                                             | 37        | 6.48%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 33        | 5.78%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 23        | 4.03%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 19        | 3.33%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 15        | 2.63%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 14        | 2.45%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 13        | 2.28%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 11        | 1.93%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 10        | 1.75%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 10        | 1.75%   |
| Ralink RT3290 Bluetooth                                                             | 9         | 1.58%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 9         | 1.58%   |
| Intel AX200 Bluetooth                                                               | 9         | 1.58%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 9         | 1.58%   |
| Broadcom BCM2045 Bluetooth                                                          | 9         | 1.58%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 8         | 1.4%    |
| HP Broadcom 2070 Bluetooth Combo                                                    | 8         | 1.4%    |
| Realtek Bluetooth Radio                                                             | 7         | 1.23%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 7         | 1.23%   |
| Dell Wireless 365 Bluetooth                                                         | 7         | 1.23%   |
| Apple Bluetooth Host Controller                                                     | 7         | 1.23%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 6         | 1.05%   |
| Dell DW375 Bluetooth Module                                                         | 6         | 1.05%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 0.88%   |
| IMC Networks Bluetooth Device                                                       | 5         | 0.88%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 5         | 0.88%   |
| Dell Wireless 350 Bluetooth                                                         | 5         | 0.88%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 5         | 0.88%   |
| Broadcom BCM20702A0                                                                 | 5         | 0.88%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 5         | 0.88%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 5         | 0.88%   |
| Toshiba Bluetooth Device                                                            | 4         | 0.7%    |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 4         | 0.7%    |
| Lite-On Bluetooth Device                                                            | 4         | 0.7%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 4         | 0.7%    |
| HP Bluetooth 1.2 Interface [Broadcom BCM2035]                                       | 4         | 0.7%    |
| Dell Wireless 370 Bluetooth Mini-card                                               | 4         | 0.7%    |
| Dell Wireless 360 Bluetooth                                                         | 4         | 0.7%    |
| Dell BCM20702A0 Bluetooth Module                                                    | 4         | 0.7%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 792       | 70.97%  |
| AMD                              | 171       | 15.32%  |
| Nvidia                           | 91        | 8.15%   |
| Silicon Integrated Systems [SiS] | 28        | 2.51%   |
| VIA Technologies                 | 10        | 0.9%    |
| C-Media Electronics              | 5         | 0.45%   |
| Tenx Technology                  | 4         | 0.36%   |
| Creative Technology              | 3         | 0.27%   |
| Yamaha                           | 2         | 0.18%   |
| Texas Instruments                | 2         | 0.18%   |
| Generalplus Technology           | 2         | 0.18%   |
| ZOOM                             | 1         | 0.09%   |
| Syntek                           | 1         | 0.09%   |
| OPPO Electronics                 | 1         | 0.09%   |
| Logitech                         | 1         | 0.09%   |
| Hewlett-Packard                  | 1         | 0.09%   |
| AKAI Professional M.I.           | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 106       | 7.93%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 93        | 6.96%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 82        | 6.13%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 80        | 5.98%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 78        | 5.83%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 69        | 5.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 49        | 3.66%   |
| AMD FCH Azalia Controller                                                                         | 46        | 3.44%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 44        | 3.29%   |
| Intel 8 Series HD Audio Controller                                                                | 44        | 3.29%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 40        | 2.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 33        | 2.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 32        | 2.39%   |
| AMD Family 17h/19h/1ah HD Audio Controller                                                        | 31        | 2.32%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 24        | 1.8%    |
| Intel Broadwell-U Audio Controller                                                                | 24        | 1.8%    |
| AMD Kabini HDMI/DP Audio                                                                          | 24        | 1.8%    |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 23        | 1.72%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 23        | 1.72%   |
| AMD Wrestler HDMI Audio                                                                           | 20        | 1.5%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 20        | 1.5%    |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 19        | 1.42%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 19        | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 18        | 1.35%   |
| AMD High Definition Audio Controller                                                              | 18        | 1.35%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 13        | 0.97%   |
| Intel Cannon Lake PCH cAVS                                                                        | 13        | 0.97%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 0.82%   |
| Intel CM238 HD Audio Controller                                                                   | 10        | 0.75%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 10        | 0.75%   |
| AMD Trinity HDMI Audio Controller                                                                 | 10        | 0.75%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 0.67%   |
| Nvidia MCP67 High Definition Audio                                                                | 8         | 0.6%    |
| Nvidia MCP79 High Definition Audio                                                                | 7         | 0.52%   |
| Nvidia High Definition Audio Controller                                                           | 7         | 0.52%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 0.52%   |
| AMD IXP SB400 AC'97 Audio Controller                                                              | 7         | 0.52%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 7         | 0.52%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 6         | 0.45%   |
| Silicon Integrated Systems [SiS] SiS7012 AC'97 Sound Controller                                   | 5         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| SK hynix            | 58        | 26.24%  |
| Samsung Electronics | 44        | 19.91%  |
| Unknown             | 37        | 16.74%  |
| Kingston            | 20        | 9.05%   |
| Micron Technology   | 17        | 7.69%   |
| Nanya Technology    | 9         | 4.07%   |
| Ramaxel Technology  | 6         | 2.71%   |
| Elpida              | 5         | 2.26%   |
| Smart               | 3         | 1.36%   |
| Qimonda             | 3         | 1.36%   |
| Unknown (ABCD)      | 2         | 0.9%    |
| High Bridge         | 2         | 0.9%    |
| Crucial             | 2         | 0.9%    |
| A-DATA Technology   | 2         | 0.9%    |
| Walton Chaintech    | 1         | 0.45%   |
| Transcend           | 1         | 0.45%   |
| Toshiba             | 1         | 0.45%   |
| Team                | 1         | 0.45%   |
| Smart Brazil        | 1         | 0.45%   |
| SHARETRONIC         | 1         | 0.45%   |
| Nayna               | 1         | 0.45%   |
| HBS                 | 1         | 0.45%   |
| COS Memory          | 1         | 0.45%   |
| Corsair             | 1         | 0.45%   |
| Avant               | 1         | 0.45%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 2.48%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR2 975MT/s         | 5         | 2.07%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 1.65%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 3         | 1.24%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR 667MT/s             | 3         | 1.24%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR 975MT/s             | 3         | 1.24%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 3         | 1.24%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.24%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 1.24%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.24%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 2         | 0.83%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 2         | 0.83%   |
| Unknown RAM Module 2GB SODIMM DDR2 533MT/s                       | 2         | 0.83%   |
| Unknown RAM Module 2GB SODIMM DDR                                | 2         | 0.83%   |
| Unknown RAM Module 2048MB SODIMM SDRAM                           | 2         | 0.83%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s                    | 2         | 0.83%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 2         | 0.83%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR3 2400MT/s | 2         | 0.83%   |
| SK hynix RAM Module 4096MB DIMM DDR3 1066MT/s                    | 2         | 0.83%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.83%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.83%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.83%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.83%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 2         | 0.83%   |
| SK hynix RAM HMA451S6AFR8N-TF 4GB SODIMM DDR4 2133MT/s           | 2         | 0.83%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 2         | 0.83%   |
| SK hynix RAM H5TC4G63AFR_PBA 2GB SODIMM DDR3 1600MT/s            | 2         | 0.83%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 0.83%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 0.83%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s          | 2         | 0.83%   |
| Qimonda RAM 64T128021EDL3SB2 1024MB SODIMM DDR2 667MT/s          | 2         | 0.83%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 2         | 0.83%   |
| Micron RAM 8JSF25664HZ-1G4D1 2GB SODIMM DDR3 1334MT/s            | 2         | 0.83%   |
| Kingston RAM 99U5428-018.A00LF 8GB SODIMM DDR3 1600MT/s          | 2         | 0.83%   |
| A-DATA RAM AM1U16BC4P2-B19H 4GB SODIMM DDR3 1600MT/s             | 2         | 0.83%   |
| Walton Chaintech RAM AS2G833-13GH905 2048MB SODIMM DDR2          | 1         | 0.41%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 1         | 0.41%   |
| Unknown RAM Module 8192MB SODIMM DDR4 2400MT/s                   | 1         | 0.41%   |
| Unknown RAM Module 512MB SODIMM DRAM                             | 1         | 0.41%   |
| Unknown RAM Module 512MB SODIMM DDR2 667MT/s                     | 1         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 83        | 43.01%  |
| DDR2    | 47        | 24.35%  |
| DDR4    | 33        | 17.1%   |
| SDRAM   | 13        | 6.74%   |
| DDR     | 6         | 3.11%   |
| DRAM    | 5         | 2.59%   |
| LPDDR4  | 3         | 1.55%   |
| LPDDR3  | 2         | 1.04%   |
| Unknown | 1         | 0.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 174       | 94.57%  |
| Row Of Chips | 5         | 2.72%   |
| DIMM         | 4         | 2.17%   |
| Chip         | 1         | 0.54%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 2048  | 68        | 30.91%  |
| 4096  | 62        | 28.18%  |
| 8192  | 42        | 19.09%  |
| 1024  | 31        | 14.09%  |
| 512   | 10        | 4.55%   |
| 16384 | 5         | 2.27%   |
| 256   | 2         | 0.91%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 53        | 25.36%  |
| 2667    | 23        | 11%     |
| 667     | 23        | 11%     |
| Unknown | 18        | 8.61%   |
| 1334    | 15        | 7.18%   |
| 1333    | 10        | 4.78%   |
| 2133    | 9         | 4.31%   |
| 1066    | 8         | 3.83%   |
| 533     | 8         | 3.83%   |
| 4199    | 7         | 3.35%   |
| 2400    | 7         | 3.35%   |
| 975     | 7         | 3.35%   |
| 800     | 6         | 2.87%   |
| 2048    | 3         | 1.44%   |
| 1067    | 3         | 1.44%   |
| 400     | 3         | 1.44%   |
| 3266    | 2         | 0.96%   |
| 3200    | 2         | 0.96%   |
| 3733    | 1         | 0.48%   |
| 1639    | 1         | 0.48%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 5         | 35.71%  |
| Canon              | 4         | 28.57%  |
| Seiko Epson        | 2         | 14.29%  |
| Brother Industries | 2         | 14.29%  |
| STMicroelectronics | 1         | 7.14%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 7.14%   |
| Seiko Epson WF-2010 Series                                | 1         | 7.14%   |
| Seiko Epson Printer                                       | 1         | 7.14%   |
| HP Laserjet P1505                                         | 1         | 7.14%   |
| HP LaserJet 1020                                          | 1         | 7.14%   |
| HP DeskJet 2700 series                                    | 1         | 7.14%   |
| HP Deskjet 1510                                           | 1         | 7.14%   |
| HP DeskJet 1110 series                                    | 1         | 7.14%   |
| Canon PIXMA MX490 Series                                  | 1         | 7.14%   |
| Canon PIXMA MX340                                         | 1         | 7.14%   |
| Canon PIXMA MG3600 Series                                 | 1         | 7.14%   |
| Canon MG2100 series                                       | 1         | 7.14%   |
| Brother MFC-L2730DW series                                | 1         | 7.14%   |
| Brother DCP-T300                                          | 1         | 7.14%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 200 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 214       | 28.08%  |
| Microdia                               | 74        | 9.71%   |
| Suyin                                  | 59        | 7.74%   |
| Realtek Semiconductor                  | 54        | 7.09%   |
| IMC Networks                           | 46        | 6.04%   |
| Bison Electronics                      | 40        | 5.25%   |
| Sunplus Innovation Technology          | 37        | 4.86%   |
| Cheng Uei Precision Industry (Foxlink) | 28        | 3.67%   |
| Silicon Motion                         | 24        | 3.15%   |
| Quanta                                 | 20        | 2.62%   |
| Syntek                                 | 17        | 2.23%   |
| Apple                                  | 17        | 2.23%   |
| Alcor Micro                            | 16        | 2.1%    |
| Lite-On Technology                     | 15        | 1.97%   |
| Ricoh                                  | 14        | 1.84%   |
| Acer                                   | 13        | 1.71%   |
| Importek                               | 11        | 1.44%   |
| ALi                                    | 11        | 1.44%   |
| Z-Star Microelectronics                | 7         | 0.92%   |
| OmniVision Technologies                | 6         | 0.79%   |
| Samsung Electronics                    | 5         | 0.66%   |
| Logitech                               | 5         | 0.66%   |
| GEMBIRD                                | 4         | 0.52%   |
| Lenovo                                 | 3         | 0.39%   |
| Primax Electronics                     | 2         | 0.26%   |
| Luxvisions Innotech Limited            | 2         | 0.26%   |
| Genesys Logic                          | 2         | 0.26%   |
| YGTek                                  | 1         | 0.13%   |
| Trust                                  | 1         | 0.13%   |
| Sunplus Technology                     | 1         | 0.13%   |
| OPPO Electronics                       | 1         | 0.13%   |
| Nebraska Furniture Mart                | 1         | 0.13%   |
| Microsoft                              | 1         | 0.13%   |
| LG Electronics                         | 1         | 0.13%   |
| Intel                                  | 1         | 0.13%   |
| Huawei Technologies                    | 1         | 0.13%   |
| HD USB Camera                          | 1         | 0.13%   |
| Generalplus Technology                 | 1         | 0.13%   |
| Foxconn / Hon Hai                      | 1         | 0.13%   |
| eMPIA Technology                       | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 18        | 2.36%   |
| Chicony USB 2.0 Camera                   | 15        | 1.97%   |
| Realtek Integrated_Webcam_HD             | 12        | 1.57%   |
| Microdia Sonix USB 2.0 Camera            | 11        | 1.44%   |
| Suyin HP Truevision HD                   | 10        | 1.31%   |
| Microdia Integrated Webcam               | 10        | 1.31%   |
| IMC Networks USB2.0 HD UVC WebCam        | 10        | 1.31%   |
| Chicony HP Truevision HD camera          | 10        | 1.31%   |
| Chicony EasyCamera                       | 10        | 1.31%   |
| Suyin Acer/HP Integrated Webcam [CN0314] | 9         | 1.18%   |
| Chicony HP Truevision HD                 | 9         | 1.18%   |
| ALi Gateway Webcam                       | 9         | 1.18%   |
| Sunplus Integrated_Webcam_HD             | 8         | 1.05%   |
| Realtek Integrated Webcam                | 8         | 1.05%   |
| Chicony TOSHIBA Web Camera - HD          | 8         | 1.05%   |
| Chicony Lenovo EasyCamera                | 8         | 1.05%   |
| Chicony HP HD Webcam                     | 8         | 1.05%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 7         | 0.92%   |
| Chicony VGA WebCam                       | 7         | 0.92%   |
| Chicony HP Webcam                        | 7         | 0.92%   |
| Chicony CNF9055 Toshiba Webcam           | 7         | 0.92%   |
| Bison Lenovo EasyCamera                  | 7         | 0.92%   |
| Suyin USB 2.0 Camera                     | 6         | 0.79%   |
| Quanta HP Webcam                         | 6         | 0.79%   |
| Microdia Laptop_Integrated_Webcam_HD     | 6         | 0.79%   |
| Microdia Integrated_Webcam_HD            | 6         | 0.79%   |
| Lite-On Integrated Camera                | 6         | 0.79%   |
| Chicony HD WebCam                        | 6         | 0.79%   |
| Chicony Acer CrystalEye Webcam           | 6         | 0.79%   |
| Bison Integrated Camera                  | 6         | 0.79%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR       | 6         | 0.79%   |
| Alcor Micro USB 2.0 Camera               | 6         | 0.79%   |
| Acer Lenovo EasyCamera                   | 6         | 0.79%   |
| Syntek EasyCamera                        | 5         | 0.66%   |
| Suyin Acer CrystalEye Webcam             | 5         | 0.66%   |
| Sunplus HP HD Webcam [Fixed]             | 5         | 0.66%   |
| Sunplus HD WebCam                        | 5         | 0.66%   |
| Silicon Motion Web Camera                | 5         | 0.66%   |
| Samsung Galaxy series, misc. (MTP mode)  | 5         | 0.66%   |
| Quanta HP TrueVision HD Camera           | 5         | 0.66%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 70        | 53.44%  |
| AuthenTec                  | 26        | 19.85%  |
| Upek                       | 10        | 7.63%   |
| STMicroelectronics         | 10        | 7.63%   |
| Shenzhen Goodix Technology | 6         | 4.58%   |
| Elan Microelectronics      | 5         | 3.82%   |
| Synaptics                  | 3         | 2.29%   |
| LighTuning Technology      | 1         | 0.76%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 16        | 12.21%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 8.4%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 10        | 7.63%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 10        | 7.63%   |
| STMicroelectronics Fingerprint Reader                                      | 10        | 7.63%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 10        | 7.63%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 6.87%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 4.58%   |
| Validity Sensors VFS491                                                    | 5         | 3.82%   |
| AuthenTec AES2810                                                          | 5         | 3.82%   |
| AuthenTec AES1600                                                          | 5         | 3.82%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 3.05%   |
| Shenzhen Goodix  Fingerprint Device                                        | 4         | 3.05%   |
| Elan ELAN:Fingerprint                                                      | 4         | 3.05%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 2.29%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 3         | 2.29%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.53%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 1.53%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.53%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.76%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.76%   |
| Synaptics  WBDI                                                            | 1         | 0.76%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.76%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.76%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.76%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.76%   |
| Elan ELAN:ARM-M4                                                           | 1         | 0.76%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.76%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 26        | 45.61%  |
| O2 Micro              | 14        | 24.56%  |
| Alcor Micro           | 10        | 17.54%  |
| Lenovo                | 3         | 5.26%   |
| Upek                  | 2         | 3.51%   |
| SCM Microsystems      | 1         | 1.75%   |
| Realtek Semiconductor | 1         | 1.75%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 15        | 26.32%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 10        | 17.54%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 17.54%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 10.53%  |
| Broadcom 5880                                                                | 5         | 8.77%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 7.02%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 5.26%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.51%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 1.75%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 1.75%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 611       | 58.25%  |
| 1     | 337       | 32.13%  |
| 2     | 86        | 8.2%    |
| 3     | 13        | 1.24%   |
| 7     | 1         | 0.1%    |
| 4     | 1         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 175       | 32.83%  |
| Fingerprint reader       | 130       | 24.39%  |
| Net/wireless             | 68        | 12.76%  |
| Chipcard                 | 56        | 10.51%  |
| Modem                    | 27        | 5.07%   |
| Storage                  | 16        | 3%      |
| Flash memory             | 13        | 2.44%   |
| Bluetooth                | 12        | 2.25%   |
| Sound                    | 8         | 1.5%    |
| Multimedia controller    | 7         | 1.31%   |
| Communication controller | 7         | 1.31%   |
| Camera                   | 7         | 1.31%   |
| Net/ethernet             | 3         | 0.56%   |
| Card reader              | 2         | 0.38%   |
| Storage/ata              | 1         | 0.19%   |
| Network                  | 1         | 0.19%   |

