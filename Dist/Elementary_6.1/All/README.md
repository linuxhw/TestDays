Elementary 6.1 - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Elementary 6.1.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Elementary_6.1/Desktop/README.md) and [notebooks](/Dist/Elementary_6.1/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends

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

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ProBook 450 G7              | Notebook    | [a73f7ae919](https://linux-hardware.org/?probe=a73f7ae919) | Feb 28, 2022 |
| ASUSTek       | M4N72-E                     | Desktop     | [c3fe570b4d](https://linux-hardware.org/?probe=c3fe570b4d) | Feb 28, 2022 |
| ASUSTek       | H81-PLUS                    | Desktop     | [e8956dc4ec](https://linux-hardware.org/?probe=e8956dc4ec) | Feb 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [d7b815d3d6](https://linux-hardware.org/?probe=d7b815d3d6) | Feb 27, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [d04715f0dc](https://linux-hardware.org/?probe=d04715f0dc) | Feb 26, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [a6d5cc0368](https://linux-hardware.org/?probe=a6d5cc0368) | Feb 26, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [745fa98d2e](https://linux-hardware.org/?probe=745fa98d2e) | Feb 26, 2022 |
| Acer          | Aspire A315-42G             | Notebook    | [75830af7ff](https://linux-hardware.org/?probe=75830af7ff) | Feb 25, 2022 |
| ASUSTek       | K50IJ                       | Notebook    | [97284dc322](https://linux-hardware.org/?probe=97284dc322) | Feb 25, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [a8b2cacac9](https://linux-hardware.org/?probe=a8b2cacac9) | Feb 25, 2022 |
| HP            | Pavilion Laptop 15-cd0xx    | Notebook    | [eeaed94df7](https://linux-hardware.org/?probe=eeaed94df7) | Feb 23, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [7ea66813f3](https://linux-hardware.org/?probe=7ea66813f3) | Feb 23, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [88c13620a2](https://linux-hardware.org/?probe=88c13620a2) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [7a8aaaa5a6](https://linux-hardware.org/?probe=7a8aaaa5a6) | Feb 23, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [849ceb3653](https://linux-hardware.org/?probe=849ceb3653) | Feb 23, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [1f32b0aa84](https://linux-hardware.org/?probe=1f32b0aa84) | Feb 23, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [ef94f0dd4d](https://linux-hardware.org/?probe=ef94f0dd4d) | Feb 23, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [1527f67c84](https://linux-hardware.org/?probe=1527f67c84) | Feb 23, 2022 |
| Samsung       | 500R4K/500R5H/5400RK/501... | Notebook    | [1391579931](https://linux-hardware.org/?probe=1391579931) | Feb 21, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [73b31ddab0](https://linux-hardware.org/?probe=73b31ddab0) | Feb 20, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [25f1ab36fc](https://linux-hardware.org/?probe=25f1ab36fc) | Feb 20, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [48dcaa8622](https://linux-hardware.org/?probe=48dcaa8622) | Feb 20, 2022 |
| MSI           | B85I                        | Desktop     | [24674e9e3a](https://linux-hardware.org/?probe=24674e9e3a) | Feb 20, 2022 |
| ASUSTek       | E402SA                      | Notebook    | [b9796e46de](https://linux-hardware.org/?probe=b9796e46de) | Feb 20, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [3503d61993](https://linux-hardware.org/?probe=3503d61993) | Feb 19, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [44210b95fe](https://linux-hardware.org/?probe=44210b95fe) | Feb 19, 2022 |
| Intel         | DH61BE AAG14062-210         | Desktop     | [00566bb73f](https://linux-hardware.org/?probe=00566bb73f) | Feb 19, 2022 |
| MSI           | B85I                        | Desktop     | [633f6bf495](https://linux-hardware.org/?probe=633f6bf495) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [da54df3fd4](https://linux-hardware.org/?probe=da54df3fd4) | Feb 19, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [05cb921db2](https://linux-hardware.org/?probe=05cb921db2) | Feb 19, 2022 |
| ASUSTek       | M11AD                       | Desktop     | [035887c4ab](https://linux-hardware.org/?probe=035887c4ab) | Feb 18, 2022 |
| MSI           | Modern 14 B10MW             | Notebook    | [beb5ff195a](https://linux-hardware.org/?probe=beb5ff195a) | Feb 18, 2022 |
| ASUSTek       | P5B                         | Desktop     | [fa4c095fd7](https://linux-hardware.org/?probe=fa4c095fd7) | Feb 17, 2022 |
| Intel         | H61                         | Desktop     | [a70c59ad0e](https://linux-hardware.org/?probe=a70c59ad0e) | Feb 17, 2022 |
| Packard Be... | EasyNote LS11HR             | Notebook    | [d8b9f8edb0](https://linux-hardware.org/?probe=d8b9f8edb0) | Feb 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [03dfc41744](https://linux-hardware.org/?probe=03dfc41744) | Feb 16, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [6beda6e2da](https://linux-hardware.org/?probe=6beda6e2da) | Feb 16, 2022 |
| Biostar       | A68MD PRO                   | Desktop     | [da42cc4da7](https://linux-hardware.org/?probe=da42cc4da7) | Feb 16, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [f97643f94c](https://linux-hardware.org/?probe=f97643f94c) | Feb 16, 2022 |
| Acer          | Aspire A315-35              | Notebook    | [9986615814](https://linux-hardware.org/?probe=9986615814) | Feb 15, 2022 |
| Acer          | Swift SF314-56              | Notebook    | [a6c7102b14](https://linux-hardware.org/?probe=a6c7102b14) | Feb 14, 2022 |
| MSI           | B85I                        | Desktop     | [28c1f1b8ae](https://linux-hardware.org/?probe=28c1f1b8ae) | Feb 13, 2022 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [825734953d](https://linux-hardware.org/?probe=825734953d) | Feb 13, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [eba09c169c](https://linux-hardware.org/?probe=eba09c169c) | Feb 13, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [45c9189643](https://linux-hardware.org/?probe=45c9189643) | Feb 13, 2022 |
| ASUSTek       | E402NA                      | Notebook    | [ec217b7bd1](https://linux-hardware.org/?probe=ec217b7bd1) | Feb 13, 2022 |
| MSI           | B85I                        | Desktop     | [898dced271](https://linux-hardware.org/?probe=898dced271) | Feb 13, 2022 |
| Dell          | Precision 7720              | Notebook    | [e5c37c787f](https://linux-hardware.org/?probe=e5c37c787f) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [a2a41e039c](https://linux-hardware.org/?probe=a2a41e039c) | Feb 13, 2022 |
| Google        | Lulu                        | Notebook    | [5b81b703ea](https://linux-hardware.org/?probe=5b81b703ea) | Feb 13, 2022 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [2f3941c9cb](https://linux-hardware.org/?probe=2f3941c9cb) | Feb 12, 2022 |
| Sony          | SVE15115EN                  | Notebook    | [facd08033e](https://linux-hardware.org/?probe=facd08033e) | Feb 12, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [5f4de1e2b0](https://linux-hardware.org/?probe=5f4de1e2b0) | Feb 12, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [4fc3af48e2](https://linux-hardware.org/?probe=4fc3af48e2) | Feb 12, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [1aeb3957c5](https://linux-hardware.org/?probe=1aeb3957c5) | Feb 12, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [aac284c4db](https://linux-hardware.org/?probe=aac284c4db) | Feb 12, 2022 |
| Dell          | Inspiron 1764               | Notebook    | [3b22e2edbb](https://linux-hardware.org/?probe=3b22e2edbb) | Feb 11, 2022 |
| LG Electro... | A410-G.BC51P1               | Notebook    | [0caedcc26b](https://linux-hardware.org/?probe=0caedcc26b) | Feb 11, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [39d4765770](https://linux-hardware.org/?probe=39d4765770) | Feb 11, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [113add3cba](https://linux-hardware.org/?probe=113add3cba) | Feb 10, 2022 |
| BANGHO        | Suma 1025                   | Tablet      | [585ea8c657](https://linux-hardware.org/?probe=585ea8c657) | Feb 10, 2022 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [698e174402](https://linux-hardware.org/?probe=698e174402) | Feb 09, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [accb1d4232](https://linux-hardware.org/?probe=accb1d4232) | Feb 09, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [82f3d6edf9](https://linux-hardware.org/?probe=82f3d6edf9) | Feb 09, 2022 |
| Timi          | TM1613                      | Notebook    | [737c2fcb2f](https://linux-hardware.org/?probe=737c2fcb2f) | Feb 09, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [a2af859752](https://linux-hardware.org/?probe=a2af859752) | Feb 09, 2022 |
| Dell          | Inspiron 5481               | Convertible | [1f266a5183](https://linux-hardware.org/?probe=1f266a5183) | Feb 08, 2022 |
| ECS           | H55H-M                      | Desktop     | [856a42d74b](https://linux-hardware.org/?probe=856a42d74b) | Feb 07, 2022 |
| Lenovo        | ThinkPad T440p 20AN006NU... | Notebook    | [d4fccf53c8](https://linux-hardware.org/?probe=d4fccf53c8) | Feb 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [87954474ed](https://linux-hardware.org/?probe=87954474ed) | Feb 07, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [baa251b3db](https://linux-hardware.org/?probe=baa251b3db) | Feb 07, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [92d9fdcc97](https://linux-hardware.org/?probe=92d9fdcc97) | Feb 07, 2022 |
| Lenovo        | ThinkPad E550 20DF0040US    | Notebook    | [ca4c420e00](https://linux-hardware.org/?probe=ca4c420e00) | Feb 07, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [4bb7cedbd8](https://linux-hardware.org/?probe=4bb7cedbd8) | Feb 06, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [b298d77ce8](https://linux-hardware.org/?probe=b298d77ce8) | Feb 06, 2022 |
| Timi          | TM1613                      | Notebook    | [8d16a0555c](https://linux-hardware.org/?probe=8d16a0555c) | Feb 06, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [f7500c309c](https://linux-hardware.org/?probe=f7500c309c) | Feb 06, 2022 |
| Acer          | Aspire V5-573PG             | Notebook    | [0edb115ff8](https://linux-hardware.org/?probe=0edb115ff8) | Feb 05, 2022 |
| Acer          | Aspire V5-573PG             | Notebook    | [68595aad84](https://linux-hardware.org/?probe=68595aad84) | Feb 05, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [e23451d062](https://linux-hardware.org/?probe=e23451d062) | Feb 05, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [a933b9c8f4](https://linux-hardware.org/?probe=a933b9c8f4) | Feb 05, 2022 |
| HP            | 802E                        | Desktop     | [31e2fe159c](https://linux-hardware.org/?probe=31e2fe159c) | Feb 05, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [7b1b45a8ed](https://linux-hardware.org/?probe=7b1b45a8ed) | Feb 05, 2022 |
| HP            | 240 G4                      | Notebook    | [9e7ffa0cf2](https://linux-hardware.org/?probe=9e7ffa0cf2) | Feb 04, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [6ba127c715](https://linux-hardware.org/?probe=6ba127c715) | Feb 04, 2022 |
| ASUSTek       | P5B                         | Desktop     | [9b661f64dd](https://linux-hardware.org/?probe=9b661f64dd) | Feb 04, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | Desktop     | [c7d50db62b](https://linux-hardware.org/?probe=c7d50db62b) | Feb 03, 2022 |
| Foxconn       | NETBOX nT-435/535 Ver       | Desktop     | [2ee2be7ccf](https://linux-hardware.org/?probe=2ee2be7ccf) | Feb 03, 2022 |
| HP            | 82A5                        | Mini pc     | [c47d9b3ae0](https://linux-hardware.org/?probe=c47d9b3ae0) | Feb 03, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [7e21d67fa5](https://linux-hardware.org/?probe=7e21d67fa5) | Feb 03, 2022 |
| HP            | ProLiant ML110 G7           | Desktop     | [2e1dcafe6c](https://linux-hardware.org/?probe=2e1dcafe6c) | Feb 03, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [1837325ca2](https://linux-hardware.org/?probe=1837325ca2) | Feb 03, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [4d2233f824](https://linux-hardware.org/?probe=4d2233f824) | Feb 03, 2022 |
| HP            | 339A                        | Desktop     | [cf9dca84ff](https://linux-hardware.org/?probe=cf9dca84ff) | Feb 02, 2022 |
| ASUSTek       | K95VJ                       | Notebook    | [ebff9950e3](https://linux-hardware.org/?probe=ebff9950e3) | Feb 02, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [7b7a2f85e0](https://linux-hardware.org/?probe=7b7a2f85e0) | Feb 02, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [87788239d2](https://linux-hardware.org/?probe=87788239d2) | Feb 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [2a4563231b](https://linux-hardware.org/?probe=2a4563231b) | Feb 02, 2022 |
| Toshiba       | Satellite L850D-BJS         | Notebook    | [d3897cf605](https://linux-hardware.org/?probe=d3897cf605) | Feb 02, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [d2bcb368c1](https://linux-hardware.org/?probe=d2bcb368c1) | Feb 02, 2022 |
| PIPO          | Cherry Trail CR             | Notebook    | [eb92e7ef7f](https://linux-hardware.org/?probe=eb92e7ef7f) | Feb 01, 2022 |
| Unknown       | Unknown                     | Desktop     | [629972c689](https://linux-hardware.org/?probe=629972c689) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [1a0b7da0df](https://linux-hardware.org/?probe=1a0b7da0df) | Feb 01, 2022 |
| HP            | 805D                        | Desktop     | [19295e5827](https://linux-hardware.org/?probe=19295e5827) | Feb 01, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [ce9e5f5d44](https://linux-hardware.org/?probe=ce9e5f5d44) | Feb 01, 2022 |
| ASUSTek       | H110I-PLUS                  | Desktop     | [ebeaf681e3](https://linux-hardware.org/?probe=ebeaf681e3) | Feb 01, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [18717f0712](https://linux-hardware.org/?probe=18717f0712) | Feb 01, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b86eb71aa1](https://linux-hardware.org/?probe=b86eb71aa1) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [1f2faf4487](https://linux-hardware.org/?probe=1f2faf4487) | Jan 31, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [03cb9013e4](https://linux-hardware.org/?probe=03cb9013e4) | Jan 31, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [34a7deb292](https://linux-hardware.org/?probe=34a7deb292) | Jan 30, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [add488b5fe](https://linux-hardware.org/?probe=add488b5fe) | Jan 30, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [13b478195a](https://linux-hardware.org/?probe=13b478195a) | Jan 30, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [479381fba6](https://linux-hardware.org/?probe=479381fba6) | Jan 29, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [697f73bc7c](https://linux-hardware.org/?probe=697f73bc7c) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [7ab82cc23a](https://linux-hardware.org/?probe=7ab82cc23a) | Jan 29, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [a015de4156](https://linux-hardware.org/?probe=a015de4156) | Jan 29, 2022 |
| Teclast       | X6 plus                     | Tablet      | [a84fba541b](https://linux-hardware.org/?probe=a84fba541b) | Jan 29, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [857a74feaa](https://linux-hardware.org/?probe=857a74feaa) | Jan 28, 2022 |
| ASUSTek       | X550CA                      | Notebook    | [81cfc7fba7](https://linux-hardware.org/?probe=81cfc7fba7) | Jan 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [61d5b0014e](https://linux-hardware.org/?probe=61d5b0014e) | Jan 28, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [a29ec0cc55](https://linux-hardware.org/?probe=a29ec0cc55) | Jan 28, 2022 |
| MSI           | Z270 KRAIT GAMING           | Desktop     | [17ccbf9c76](https://linux-hardware.org/?probe=17ccbf9c76) | Jan 28, 2022 |
| Razer         | Blade Stealth               | Notebook    | [6a4fbb1374](https://linux-hardware.org/?probe=6a4fbb1374) | Jan 27, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [e800b95c58](https://linux-hardware.org/?probe=e800b95c58) | Jan 26, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [124dcb4c34](https://linux-hardware.org/?probe=124dcb4c34) | Jan 26, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [804f9dbb94](https://linux-hardware.org/?probe=804f9dbb94) | Jan 26, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [8c1e438e47](https://linux-hardware.org/?probe=8c1e438e47) | Jan 26, 2022 |
| Apple         | MacBookAir1,1               | Notebook    | [dfbdc8f20b](https://linux-hardware.org/?probe=dfbdc8f20b) | Jan 25, 2022 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [8394958e0e](https://linux-hardware.org/?probe=8394958e0e) | Jan 25, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [8fdf1980ee](https://linux-hardware.org/?probe=8fdf1980ee) | Jan 25, 2022 |
| ASRock        | H61M-HVS                    | Desktop     | [5d19dff1e4](https://linux-hardware.org/?probe=5d19dff1e4) | Jan 25, 2022 |
| Acer          | ConceptD CM100-51A V:1.1    | Desktop     | [663bbd709d](https://linux-hardware.org/?probe=663bbd709d) | Jan 24, 2022 |
| Lenovo        | G550 20023                  | Notebook    | [9432cdb859](https://linux-hardware.org/?probe=9432cdb859) | Jan 24, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [79cf3b66a3](https://linux-hardware.org/?probe=79cf3b66a3) | Jan 24, 2022 |
| Lenovo        | G550 2958                   | Notebook    | [fd2872d2d8](https://linux-hardware.org/?probe=fd2872d2d8) | Jan 24, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [d1e0923b7a](https://linux-hardware.org/?probe=d1e0923b7a) | Jan 24, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [4e3ef7a5a7](https://linux-hardware.org/?probe=4e3ef7a5a7) | Jan 23, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [37e7b98af1](https://linux-hardware.org/?probe=37e7b98af1) | Jan 23, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a5a4652304](https://linux-hardware.org/?probe=a5a4652304) | Jan 23, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | Notebook    | [92991c028e](https://linux-hardware.org/?probe=92991c028e) | Jan 22, 2022 |
| Apple         | MacBookPro8,3               | Notebook    | [fb5a640b14](https://linux-hardware.org/?probe=fb5a640b14) | Jan 22, 2022 |
| FIRICH        | J1900                       | Desktop     | [937e24af64](https://linux-hardware.org/?probe=937e24af64) | Jan 22, 2022 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [5007cce576](https://linux-hardware.org/?probe=5007cce576) | Jan 21, 2022 |
| ASUSTek       | ROG STRIX B360-H GAMING     | Desktop     | [d1505fe489](https://linux-hardware.org/?probe=d1505fe489) | Jan 21, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [db0cc3978c](https://linux-hardware.org/?probe=db0cc3978c) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7fd85b85b8](https://linux-hardware.org/?probe=7fd85b85b8) | Jan 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [2c01bf53cb](https://linux-hardware.org/?probe=2c01bf53cb) | Jan 21, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [3bf6b408ee](https://linux-hardware.org/?probe=3bf6b408ee) | Jan 21, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| Apple         | MacBookPro11,5              | Notebook    | [0a8fb964eb](https://linux-hardware.org/?probe=0a8fb964eb) | Jan 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [75d67cd8a4](https://linux-hardware.org/?probe=75d67cd8a4) | Jan 20, 2022 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [7a14d864d4](https://linux-hardware.org/?probe=7a14d864d4) | Jan 20, 2022 |
| HP            | ProBook 4540s               | Notebook    | [16794fee23](https://linux-hardware.org/?probe=16794fee23) | Jan 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [3dd4035494](https://linux-hardware.org/?probe=3dd4035494) | Jan 19, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [df4c38dba6](https://linux-hardware.org/?probe=df4c38dba6) | Jan 19, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [3088724103](https://linux-hardware.org/?probe=3088724103) | Jan 19, 2022 |
| ASUSTek       | TUF B365M-PLUS GAMING       | Desktop     | [ec51f5ca3e](https://linux-hardware.org/?probe=ec51f5ca3e) | Jan 19, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [488d339e77](https://linux-hardware.org/?probe=488d339e77) | Jan 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [377afa98c8](https://linux-hardware.org/?probe=377afa98c8) | Jan 19, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [a0fdaf761c](https://linux-hardware.org/?probe=a0fdaf761c) | Jan 17, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [f7c8c966dc](https://linux-hardware.org/?probe=f7c8c966dc) | Jan 17, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [744cfeb340](https://linux-hardware.org/?probe=744cfeb340) | Jan 17, 2022 |
| ASUSTek       | X555LN                      | Notebook    | [6fba3bb5aa](https://linux-hardware.org/?probe=6fba3bb5aa) | Jan 17, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [e7225dad8e](https://linux-hardware.org/?probe=e7225dad8e) | Jan 17, 2022 |
| Dell          | Latitude E5400              | Notebook    | [1303d72d3b](https://linux-hardware.org/?probe=1303d72d3b) | Jan 17, 2022 |
| Acer          | Swift SF315-52              | Notebook    | [1a6e0815fc](https://linux-hardware.org/?probe=1a6e0815fc) | Jan 16, 2022 |
| Lenovo        | ThinkPad T430 2347JC2       | Notebook    | [cac66153bc](https://linux-hardware.org/?probe=cac66153bc) | Jan 16, 2022 |
| ASUSTek       | X541NA                      | Notebook    | [89459685e9](https://linux-hardware.org/?probe=89459685e9) | Jan 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [5248d37c26](https://linux-hardware.org/?probe=5248d37c26) | Jan 15, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [ff75719a4e](https://linux-hardware.org/?probe=ff75719a4e) | Jan 15, 2022 |
| HP            | ProBook 4430s               | Notebook    | [e2103ef2d8](https://linux-hardware.org/?probe=e2103ef2d8) | Jan 14, 2022 |
| ASUSTek       | H61M-CS                     | Desktop     | [8855875fbd](https://linux-hardware.org/?probe=8855875fbd) | Jan 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [fae944592d](https://linux-hardware.org/?probe=fae944592d) | Jan 14, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [ebdb392f57](https://linux-hardware.org/?probe=ebdb392f57) | Jan 14, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [33392a90ce](https://linux-hardware.org/?probe=33392a90ce) | Jan 13, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [00a00c3cac](https://linux-hardware.org/?probe=00a00c3cac) | Jan 13, 2022 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [39f3687349](https://linux-hardware.org/?probe=39f3687349) | Jan 12, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [d8c919f740](https://linux-hardware.org/?probe=d8c919f740) | Jan 12, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [07faf9a309](https://linux-hardware.org/?probe=07faf9a309) | Jan 12, 2022 |
| Apple         | MacBook3,1                  | Notebook    | [c670d007f3](https://linux-hardware.org/?probe=c670d007f3) | Jan 11, 2022 |
| Foxconn       | 2AB1                        | Desktop     | [de61623232](https://linux-hardware.org/?probe=de61623232) | Jan 11, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [66d12682ac](https://linux-hardware.org/?probe=66d12682ac) | Jan 10, 2022 |
| ASUSTek       | H110M-C                     | Desktop     | [be4291793d](https://linux-hardware.org/?probe=be4291793d) | Jan 10, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [6a8c354065](https://linux-hardware.org/?probe=6a8c354065) | Jan 10, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [7ce29e0c54](https://linux-hardware.org/?probe=7ce29e0c54) | Jan 09, 2022 |
| Lenovo        | ThinkPad E14 20RAS0EQ00     | Notebook    | [ea22270511](https://linux-hardware.org/?probe=ea22270511) | Jan 09, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [9d29b20f2d](https://linux-hardware.org/?probe=9d29b20f2d) | Jan 08, 2022 |
| HP            | 8597                        | Desktop     | [09ed815dd0](https://linux-hardware.org/?probe=09ed815dd0) | Jan 08, 2022 |
| HUAWEI        | MACHD-WXX9                  | Notebook    | [72b280602e](https://linux-hardware.org/?probe=72b280602e) | Jan 07, 2022 |
| Sony          | VPCEA3S1E                   | Notebook    | [670b7a5d31](https://linux-hardware.org/?probe=670b7a5d31) | Jan 07, 2022 |
| Gigabyte      | GA-970A-D3                  | Desktop     | [b1c9832ce6](https://linux-hardware.org/?probe=b1c9832ce6) | Jan 07, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [51cba69624](https://linux-hardware.org/?probe=51cba69624) | Jan 06, 2022 |
| Star Labs     | StarBook                    | Notebook    | [bd2b8ba939](https://linux-hardware.org/?probe=bd2b8ba939) | Jan 06, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [864ecfe029](https://linux-hardware.org/?probe=864ecfe029) | Jan 06, 2022 |
| Notebook      | W65_67SJ                    | Notebook    | [606e2587dd](https://linux-hardware.org/?probe=606e2587dd) | Jan 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [590907f437](https://linux-hardware.org/?probe=590907f437) | Jan 06, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [20dfc25b62](https://linux-hardware.org/?probe=20dfc25b62) | Jan 05, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [27756cb751](https://linux-hardware.org/?probe=27756cb751) | Jan 05, 2022 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [21f2a5e1b9](https://linux-hardware.org/?probe=21f2a5e1b9) | Jan 05, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [a03baba93d](https://linux-hardware.org/?probe=a03baba93d) | Jan 05, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [fbb0e6d1d5](https://linux-hardware.org/?probe=fbb0e6d1d5) | Jan 05, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [6eab59bbbf](https://linux-hardware.org/?probe=6eab59bbbf) | Jan 05, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [5496b24a51](https://linux-hardware.org/?probe=5496b24a51) | Jan 05, 2022 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [520ced18c4](https://linux-hardware.org/?probe=520ced18c4) | Jan 05, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [ae2f1bc63c](https://linux-hardware.org/?probe=ae2f1bc63c) | Jan 05, 2022 |
| HUAWEI        | MACHC-WAX9                  | Notebook    | [b0df1464a1](https://linux-hardware.org/?probe=b0df1464a1) | Jan 05, 2022 |
| Sony          | SVE14A390X                  | Notebook    | [3b11d123cf](https://linux-hardware.org/?probe=3b11d123cf) | Jan 04, 2022 |
| HP            | ProBook 4430s               | Notebook    | [aafb807fc2](https://linux-hardware.org/?probe=aafb807fc2) | Jan 04, 2022 |
| HP            | ProBook 4430s               | Notebook    | [f534b0dd91](https://linux-hardware.org/?probe=f534b0dd91) | Jan 04, 2022 |
| Lenovo        | ThinkPad W541 20EGS1VV00    | Notebook    | [5d88eb323c](https://linux-hardware.org/?probe=5d88eb323c) | Jan 04, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [a1c3f24aab](https://linux-hardware.org/?probe=a1c3f24aab) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [71e992725f](https://linux-hardware.org/?probe=71e992725f) | Jan 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [8087320623](https://linux-hardware.org/?probe=8087320623) | Jan 04, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [b18501f890](https://linux-hardware.org/?probe=b18501f890) | Jan 04, 2022 |
| Star Labs     | LabTop                      | Notebook    | [043cd26c60](https://linux-hardware.org/?probe=043cd26c60) | Jan 04, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [1172390e59](https://linux-hardware.org/?probe=1172390e59) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [9d633f7bdb](https://linux-hardware.org/?probe=9d633f7bdb) | Jan 04, 2022 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [c91feb11a8](https://linux-hardware.org/?probe=c91feb11a8) | Jan 04, 2022 |
| Lenovo        | ThinkPad E495 20NE001RTX    | Notebook    | [79e95e3cb6](https://linux-hardware.org/?probe=79e95e3cb6) | Jan 04, 2022 |
| Dell          | Precision 5530              | Notebook    | [b385c0a16e](https://linux-hardware.org/?probe=b385c0a16e) | Jan 04, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [023df04f60](https://linux-hardware.org/?probe=023df04f60) | Jan 04, 2022 |
| Monster       | ABRA A5 V13.2               | Notebook    | [6d8d622050](https://linux-hardware.org/?probe=6d8d622050) | Jan 04, 2022 |
| MSI           | PS63 Modern 8RD             | Notebook    | [1cd435c54f](https://linux-hardware.org/?probe=1cd435c54f) | Jan 04, 2022 |
| Lenovo        | Legion Y530-15ICH 81GT      | Notebook    | [c694c358f9](https://linux-hardware.org/?probe=c694c358f9) | Jan 04, 2022 |
| Lenovo        | 371C No DPK                 | All in one  | [6c4714d241](https://linux-hardware.org/?probe=6c4714d241) | Jan 04, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [c61ed9ea15](https://linux-hardware.org/?probe=c61ed9ea15) | Jan 04, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [1015862a37](https://linux-hardware.org/?probe=1015862a37) | Jan 04, 2022 |
| Acidanther... | Mac-42FD25EABCABB274 iMa... | All in one  | [545dd570a9](https://linux-hardware.org/?probe=545dd570a9) | Jan 04, 2022 |
| Timi          | TM1613                      | Notebook    | [6761bd1e12](https://linux-hardware.org/?probe=6761bd1e12) | Jan 04, 2022 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [cd6abb9f49](https://linux-hardware.org/?probe=cd6abb9f49) | Jan 03, 2022 |
| ASUSTek       | E202SA                      | Notebook    | [d721e131f4](https://linux-hardware.org/?probe=d721e131f4) | Jan 02, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [440d6a1b59](https://linux-hardware.org/?probe=440d6a1b59) | Jan 02, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [6c7a3affdb](https://linux-hardware.org/?probe=6c7a3affdb) | Jan 02, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [45b6bf0410](https://linux-hardware.org/?probe=45b6bf0410) | Jan 01, 2022 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [fb332a2529](https://linux-hardware.org/?probe=fb332a2529) | Jan 01, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [d44b06ec61](https://linux-hardware.org/?probe=d44b06ec61) | Jan 01, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [f215102713](https://linux-hardware.org/?probe=f215102713) | Dec 31, 2021 |
| MSI           | 2A9C                        | Desktop     | [8d08f7f383](https://linux-hardware.org/?probe=8d08f7f383) | Dec 31, 2021 |
| Notebook      | P65xHP                      | Notebook    | [37db5af302](https://linux-hardware.org/?probe=37db5af302) | Dec 31, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [e060f00ff8](https://linux-hardware.org/?probe=e060f00ff8) | Dec 31, 2021 |
| Notebook      | P65xHP                      | Notebook    | [fc81fedcf3](https://linux-hardware.org/?probe=fc81fedcf3) | Dec 31, 2021 |
| Teclast       | F7                          | Notebook    | [44bba02dee](https://linux-hardware.org/?probe=44bba02dee) | Dec 31, 2021 |
| HP            | 3397                        | Desktop     | [323dc8992b](https://linux-hardware.org/?probe=323dc8992b) | Dec 31, 2021 |
| ASUSTek       | X79-DELUXE                  | Desktop     | [00b9dd3788](https://linux-hardware.org/?probe=00b9dd3788) | Dec 30, 2021 |
| Wortmann      | 1220729_1470271             | Notebook    | [018071ac3e](https://linux-hardware.org/?probe=018071ac3e) | Dec 30, 2021 |
| HP            | 1589                        | Desktop     | [d123a8de64](https://linux-hardware.org/?probe=d123a8de64) | Dec 30, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [bcd6fc46cc](https://linux-hardware.org/?probe=bcd6fc46cc) | Dec 30, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [3a24dba335](https://linux-hardware.org/?probe=3a24dba335) | Dec 28, 2021 |
| Acer          | Aspire 7750G                | Notebook    | [516cb4e250](https://linux-hardware.org/?probe=516cb4e250) | Dec 28, 2021 |
| ASUSTek       | X555UB                      | Notebook    | [e0844450ac](https://linux-hardware.org/?probe=e0844450ac) | Dec 28, 2021 |
| ASUSTek       | TUF GAMING B550M-PLUS       | Desktop     | [5f67c759fe](https://linux-hardware.org/?probe=5f67c759fe) | Dec 28, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [829dc5243a](https://linux-hardware.org/?probe=829dc5243a) | Dec 28, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [352c62bd8f](https://linux-hardware.org/?probe=352c62bd8f) | Dec 28, 2021 |
| Dell          | Latitude 3580               | Notebook    | [f243f4c09e](https://linux-hardware.org/?probe=f243f4c09e) | Dec 27, 2021 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [5d91acd13d](https://linux-hardware.org/?probe=5d91acd13d) | Dec 27, 2021 |
| Lenovo        | ThinkPad T430 23501M2       | Notebook    | [2645817d64](https://linux-hardware.org/?probe=2645817d64) | Dec 26, 2021 |
| Gigabyte      | Z390 UD                     | Desktop     | [2399fa64ba](https://linux-hardware.org/?probe=2399fa64ba) | Dec 26, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [a71c970cbf](https://linux-hardware.org/?probe=a71c970cbf) | Dec 25, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [99bea5df6c](https://linux-hardware.org/?probe=99bea5df6c) | Dec 25, 2021 |
| Lenovo        | IdeaPad 320-14AST 80XU      | Notebook    | [80c8feb8bf](https://linux-hardware.org/?probe=80c8feb8bf) | Dec 25, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [211b723554](https://linux-hardware.org/?probe=211b723554) | Dec 24, 2021 |
| LG Electro... | A410-G.BC51P1               | Notebook    | [b231405a63](https://linux-hardware.org/?probe=b231405a63) | Dec 24, 2021 |
| Microsoft     | Surface Book 2              | Tablet      | [730558c6bd](https://linux-hardware.org/?probe=730558c6bd) | Dec 24, 2021 |
| Acer          | TravelMate 5760             | Notebook    | [71526c7767](https://linux-hardware.org/?probe=71526c7767) | Dec 23, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [783618fe4b](https://linux-hardware.org/?probe=783618fe4b) | Dec 23, 2021 |
| Lenovo        | Flex 2-14D 20376            | Notebook    | [d950a63316](https://linux-hardware.org/?probe=d950a63316) | Dec 23, 2021 |
| Dell          | Inspiron 3542               | Notebook    | [277f97ef07](https://linux-hardware.org/?probe=277f97ef07) | Dec 23, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [dfbdb618f1](https://linux-hardware.org/?probe=dfbdb618f1) | Dec 23, 2021 |
| ASUSTek       | H97-PLUS                    | Desktop     | [cba91c2ad2](https://linux-hardware.org/?probe=cba91c2ad2) | Dec 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f74c2da103](https://linux-hardware.org/?probe=f74c2da103) | Dec 22, 2021 |
| Dell          | Precision M3800             | Notebook    | [ed44d9ac8c](https://linux-hardware.org/?probe=ed44d9ac8c) | Dec 21, 2021 |
| Dell          | Inspiron 7405 2n1           | Convertible | [64d2a0328e](https://linux-hardware.org/?probe=64d2a0328e) | Dec 21, 2021 |
| Apple         | MacBookAir6,1               | Notebook    | [b2e3490378](https://linux-hardware.org/?probe=b2e3490378) | Dec 21, 2021 |
| Dell          | Precision M6500             | Notebook    | [931f365c60](https://linux-hardware.org/?probe=931f365c60) | Dec 20, 2021 |
| MSI           | B450-A PRO MAX              | Desktop     | [f14eef1ae6](https://linux-hardware.org/?probe=f14eef1ae6) | Dec 20, 2021 |
| Gigabyte      | H310M S2P                   | Desktop     | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| Dell          | Inspiron 5555               | Notebook    | [09d45f017d](https://linux-hardware.org/?probe=09d45f017d) | Dec 18, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [d9077a5d94](https://linux-hardware.org/?probe=d9077a5d94) | Dec 18, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [b789981cc4](https://linux-hardware.org/?probe=b789981cc4) | Dec 17, 2021 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [a45f76da28](https://linux-hardware.org/?probe=a45f76da28) | Dec 17, 2021 |
| ASUSTek       | UX410UAK                    | Notebook    | [39dcbe0f57](https://linux-hardware.org/?probe=39dcbe0f57) | Dec 17, 2021 |
| Monster       | MARKUT M7 V1.x              | Notebook    | [2d2ed2143e](https://linux-hardware.org/?probe=2d2ed2143e) | Dec 17, 2021 |
| Gigabyte      | Z590 AORUS ELITE AX         | Desktop     | [c068e358e8](https://linux-hardware.org/?probe=c068e358e8) | Dec 16, 2021 |
| Intel         | NUC10i3FNB K61362-305       | Mini pc     | [3371572aa9](https://linux-hardware.org/?probe=3371572aa9) | Dec 16, 2021 |
| Monster       | MARKUT M7 V1.x              | Notebook    | [2390550c49](https://linux-hardware.org/?probe=2390550c49) | Dec 15, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [720cc7a45f](https://linux-hardware.org/?probe=720cc7a45f) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [661e7dae0c](https://linux-hardware.org/?probe=661e7dae0c) | Dec 15, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [b682cee818](https://linux-hardware.org/?probe=b682cee818) | Dec 15, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [5dcbdab7ca](https://linux-hardware.org/?probe=5dcbdab7ca) | Dec 15, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.11.0-43-generic      | 76        | 31.93%  |
| 5.13.0-28-generic      | 52        | 21.85%  |
| 5.13.0-27-generic      | 33        | 13.87%  |
| 5.13.0-30-generic      | 19        | 7.98%   |
| 5.11.0-44-generic      | 17        | 7.14%   |
| 5.11.0-46-generic      | 12        | 5.04%   |
| 5.11.0-41-generic      | 10        | 4.2%    |
| 5.13.0-25-generic      | 3         | 1.26%   |
| 5.11.0-40-generic      | 2         | 0.84%   |
| 5.8.0-50-generic       | 1         | 0.42%   |
| 5.16.10-051610-generic | 1         | 0.42%   |
| 5.15.6-surface         | 1         | 0.42%   |
| 5.15.3-xanmod1         | 1         | 0.42%   |
| 5.15.13-xanmod1        | 1         | 0.42%   |
| 5.15.12-xanmod1-tt     | 1         | 0.42%   |
| 5.15.11-t2-big-sur     | 1         | 0.42%   |
| 5.15.10-xanmod1        | 1         | 0.42%   |
| 5.14.10-051410-generic | 1         | 0.42%   |
| 5.14.0-1011-oem        | 1         | 0.42%   |
| 5.13.0-28-lowlatency   | 1         | 0.42%   |
| 5.13.0-22-generic      | 1         | 0.42%   |
| 5.11.0-43-lowlatency   | 1         | 0.42%   |
| 5.11.0-37-generic      | 1         | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 117       | 50.21%  |
| 5.13.0  | 106       | 45.49%  |
| 5.8.0   | 1         | 0.43%   |
| 5.16.10 | 1         | 0.43%   |
| 5.15.6  | 1         | 0.43%   |
| 5.15.3  | 1         | 0.43%   |
| 5.15.13 | 1         | 0.43%   |
| 5.15.12 | 1         | 0.43%   |
| 5.15.11 | 1         | 0.43%   |
| 5.15.10 | 1         | 0.43%   |
| 5.14.10 | 1         | 0.43%   |
| 5.14.0  | 1         | 0.43%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 117       | 50.21%  |
| 5.13    | 106       | 45.49%  |
| 5.15    | 6         | 2.58%   |
| 5.14    | 2         | 0.86%   |
| 5.8     | 1         | 0.43%   |
| 5.16    | 1         | 0.43%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 231       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Pantheon | 231       | 100%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 231       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 181       | 78.02%  |
| LightDM | 50        | 21.55%  |
| GDM     | 1         | 0.43%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 102       | 44.16%  |
| de_DE | 39        | 16.88%  |
| en_GB | 16        | 6.93%   |
| es_ES | 14        | 6.06%   |
| fr_FR | 10        | 4.33%   |
| ru_RU | 9         | 3.9%    |
| pt_BR | 9         | 3.9%    |
| pl_PL | 7         | 3.03%   |
| it_IT | 6         | 2.6%    |
| pt_PT | 4         | 1.73%   |
| tr_TR | 2         | 0.87%   |
| nl_NL | 2         | 0.87%   |
| en_CA | 2         | 0.87%   |
| en_AU | 2         | 0.87%   |
| sv_SE | 1         | 0.43%   |
| sr_RS | 1         | 0.43%   |
| ja_JP | 1         | 0.43%   |
| hu_HU | 1         | 0.43%   |
| hr_HR | 1         | 0.43%   |
| fr_CA | 1         | 0.43%   |
| bg_BG | 1         | 0.43%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 159       | 68.83%  |
| BIOS | 72        | 31.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 222       | 96.1%   |
| Btrfs   | 7         | 3.03%   |
| Xfs     | 1         | 0.43%   |
| Overlay | 1         | 0.43%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 189       | 81.47%  |
| GPT     | 37        | 15.95%  |
| MBR     | 6         | 2.59%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 223       | 96.54%  |
| Yes       | 8         | 3.46%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 215       | 93.07%  |
| Yes       | 16        | 6.93%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 39        | 16.88%  |
| Lenovo              | 34        | 14.72%  |
| Hewlett-Packard     | 29        | 12.55%  |
| Apple               | 28        | 12.12%  |
| Dell                | 17        | 7.36%   |
| Acer                | 13        | 5.63%   |
| MSI                 | 12        | 5.19%   |
| Gigabyte Technology | 11        | 4.76%   |
| HUAWEI              | 6         | 2.6%    |
| Sony                | 3         | 1.3%    |
| Samsung Electronics | 3         | 1.3%    |
| Microsoft           | 3         | 1.3%    |
| Intel               | 3         | 1.3%    |
| ASRock              | 3         | 1.3%    |
| Timi                | 2         | 0.87%   |
| Teclast             | 2         | 0.87%   |
| Star Labs           | 2         | 0.87%   |
| Notebook            | 2         | 0.87%   |
| Monster             | 2         | 0.87%   |
| Foxconn             | 2         | 0.87%   |
| Unknown             | 2         | 0.87%   |
| Wortmann AG         | 1         | 0.43%   |
| Toshiba             | 1         | 0.43%   |
| Razer               | 1         | 0.43%   |
| PIPO                | 1         | 0.43%   |
| Packard Bell        | 1         | 0.43%   |
| LG Electronics      | 1         | 0.43%   |
| Google              | 1         | 0.43%   |
| Fujitsu             | 1         | 0.43%   |
| FIRICH              | 1         | 0.43%   |
| ECS                 | 1         | 0.43%   |
| Biostar             | 1         | 0.43%   |
| BANGHO              | 1         | 0.43%   |
| Acidanthera         | 1         | 0.43%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Apple MacBook5,1                                  | 4         | 1.73%   |
| HUAWEI MACHD-WXX9                                 | 3         | 1.3%    |
| Timi TM1613                                       | 2         | 0.87%   |
| HP EliteBook 8460p                                | 2         | 0.87%   |
| Gigabyte Z390 UD                                  | 2         | 0.87%   |
| Dell Inspiron N5050                               | 2         | 0.87%   |
| ASUS X550CA                                       | 2         | 0.87%   |
| ASUS TUF GAMING B550M-PLUS                        | 2         | 0.87%   |
| ASUS All Series                                   | 2         | 0.87%   |
| Apple MacBookPro8,2                               | 2         | 0.87%   |
| Apple MacBookPro5,5                               | 2         | 0.87%   |
| Unknown                                           | 2         | 0.87%   |
| Wortmann AG 1220729_1470271                       | 1         | 0.43%   |
| Toshiba Satellite L850D-BJS                       | 1         | 0.43%   |
| Teclast X6 plus                                   | 1         | 0.43%   |
| Teclast F7                                        | 1         | 0.43%   |
| Star Labs StarBook                                | 1         | 0.43%   |
| Star Labs LabTop                                  | 1         | 0.43%   |
| Sony VPCEA3S1E                                    | 1         | 0.43%   |
| Sony SVE15115EN                                   | 1         | 0.43%   |
| Sony SVE14A390X                                   | 1         | 0.43%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D        | 1         | 0.43%   |
| Samsung 870Z5E/880Z5E/680Z5E                      | 1         | 0.43%   |
| Samsung 500R4K/500R5H/5400RK/501R5H/5500RH/500R5S | 1         | 0.43%   |
| Razer Blade Stealth                               | 1         | 0.43%   |
| PIPO W9                                           | 1         | 0.43%   |
| Packard Bell EasyNote LS11HR                      | 1         | 0.43%   |
| Notebook W65_67SJ                                 | 1         | 0.43%   |
| Notebook P65xHP                                   | 1         | 0.43%   |
| MSI PS63 Modern 8RD                               | 1         | 0.43%   |
| MSI PPPPP-CCC#MMMMMMMM                            | 1         | 0.43%   |
| MSI MS-7C52                                       | 1         | 0.43%   |
| MSI MS-7C02                                       | 1         | 0.43%   |
| MSI MS-7B86                                       | 1         | 0.43%   |
| MSI MS-7B79                                       | 1         | 0.43%   |
| MSI MS-7A59                                       | 1         | 0.43%   |
| MSI MS-7A40                                       | 1         | 0.43%   |
| MSI MS-7851                                       | 1         | 0.43%   |
| MSI Modern 14 B4MW                                | 1         | 0.43%   |
| MSI Modern 14 B10MW                               | 1         | 0.43%   |
| MSI GF63 Thin 9SCSR                               | 1         | 0.43%   |
| Monster MARKUT M7 V1.x                            | 1         | 0.43%   |
| Monster ABRA A5 V13.2                             | 1         | 0.43%   |
| Microsoft Surface with Windows 8 Pro              | 1         | 0.43%   |
| Microsoft Surface Go                              | 1         | 0.43%   |
| Microsoft Surface Book 2                          | 1         | 0.43%   |
| LG A410-G.BC51P1                                  | 1         | 0.43%   |
| Lenovo Yoga 300-11IBR 80M1                        | 1         | 0.43%   |
| Lenovo ThinkPad X270 W10DG 20K5S2VL00             | 1         | 0.43%   |
| Lenovo ThinkPad X13 Gen 1 20UFS00G00              | 1         | 0.43%   |
| Lenovo ThinkPad X1 Carbon Gen 9 20XWCTO1WW        | 1         | 0.43%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHS1L200          | 1         | 0.43%   |
| Lenovo ThinkPad X1 Carbon 6th 20KHS0L800          | 1         | 0.43%   |
| Lenovo ThinkPad W541 20EGS1VV00                   | 1         | 0.43%   |
| Lenovo ThinkPad T470 W10DG 20JNS08H00             | 1         | 0.43%   |
| Lenovo ThinkPad T470 20JNS08H00                   | 1         | 0.43%   |
| Lenovo ThinkPad T440p 20AN006NUS                  | 1         | 0.43%   |
| Lenovo ThinkPad T430 23501M2                      | 1         | 0.43%   |
| Lenovo ThinkPad T430 2347JC2                      | 1         | 0.43%   |
| Lenovo ThinkPad P14s Gen 1 20Y1S00E00             | 1         | 0.43%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 17        | 7.36%   |
| Lenovo IdeaPad         | 8         | 3.46%   |
| Dell Inspiron          | 8         | 3.46%   |
| Acer Aspire            | 7         | 3.03%   |
| HP Pavilion            | 5         | 2.16%   |
| HP EliteBook           | 5         | 2.16%   |
| ASUS VivoBook          | 5         | 2.16%   |
| Apple MacBook5         | 5         | 2.16%   |
| HP ProBook             | 4         | 1.73%   |
| Dell Precision         | 4         | 1.73%   |
| Acer Swift             | 4         | 1.73%   |
| Microsoft Surface      | 3         | 1.3%    |
| HUAWEI MACHD-WXX9      | 3         | 1.3%    |
| HP ProDesk             | 3         | 1.3%    |
| HP Laptop              | 3         | 1.3%    |
| ASUS ZenBook           | 3         | 1.3%    |
| ASUS TUF               | 3         | 1.3%    |
| ASUS PRIME             | 3         | 1.3%    |
| Apple MacBookPro8      | 3         | 1.3%    |
| Apple MacBookPro5      | 3         | 1.3%    |
| Timi TM1613            | 2         | 0.87%   |
| MSI Modern             | 2         | 0.87%   |
| Lenovo Legion          | 2         | 0.87%   |
| Lenovo G550            | 2         | 0.87%   |
| HP ProLiant            | 2         | 0.87%   |
| HP Compaq              | 2         | 0.87%   |
| Gigabyte Z390          | 2         | 0.87%   |
| Dell Vostro            | 2         | 0.87%   |
| Dell Latitude          | 2         | 0.87%   |
| ASUS X550CA            | 2         | 0.87%   |
| ASUS ROG               | 2         | 0.87%   |
| ASUS All               | 2         | 0.87%   |
| Apple MacBookPro9      | 2         | 0.87%   |
| Apple MacBookAir7      | 2         | 0.87%   |
| Apple MacBookAir6      | 2         | 0.87%   |
| Unknown                | 2         | 0.87%   |
| Wortmann AG 1220729    | 1         | 0.43%   |
| Toshiba Satellite      | 1         | 0.43%   |
| Teclast X6             | 1         | 0.43%   |
| Teclast F7             | 1         | 0.43%   |
| Star Labs StarBook     | 1         | 0.43%   |
| Star Labs LabTop       | 1         | 0.43%   |
| Sony VPCEA3S1E         | 1         | 0.43%   |
| Sony SVE15115EN        | 1         | 0.43%   |
| Sony SVE14A390X        | 1         | 0.43%   |
| Samsung 900X3C         | 1         | 0.43%   |
| Samsung 870Z5E         | 1         | 0.43%   |
| Samsung 500R4K         | 1         | 0.43%   |
| Razer Blade            | 1         | 0.43%   |
| PIPO W9                | 1         | 0.43%   |
| Packard Bell EasyNote  | 1         | 0.43%   |
| Notebook W65           | 1         | 0.43%   |
| Notebook P65xHP        | 1         | 0.43%   |
| MSI PS63               | 1         | 0.43%   |
| MSI PPPPP-CCC#MMMMMMMM | 1         | 0.43%   |
| MSI MS-7C52            | 1         | 0.43%   |
| MSI MS-7C02            | 1         | 0.43%   |
| MSI MS-7B86            | 1         | 0.43%   |
| MSI MS-7B79            | 1         | 0.43%   |
| MSI MS-7A59            | 1         | 0.43%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 29        | 12.55%  |
| 2018 | 27        | 11.69%  |
| 2012 | 20        | 8.66%   |
| 2021 | 19        | 8.23%   |
| 2015 | 19        | 8.23%   |
| 2019 | 18        | 7.79%   |
| 2011 | 16        | 6.93%   |
| 2016 | 15        | 6.49%   |
| 2014 | 15        | 6.49%   |
| 2017 | 13        | 5.63%   |
| 2013 | 13        | 5.63%   |
| 2009 | 12        | 5.19%   |
| 2010 | 9         | 3.9%    |
| 2008 | 4         | 1.73%   |
| 2007 | 1         | 0.43%   |
| 2006 | 1         | 0.43%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 156       | 67.53%  |
| Desktop     | 59        | 25.54%  |
| Tablet      | 5         | 2.16%   |
| All in one  | 5         | 2.16%   |
| Convertible | 3         | 1.3%    |
| Mini pc     | 2         | 0.87%   |
| Server      | 1         | 0.43%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 203       | 87.88%  |
| Enabled  | 28        | 12.12%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 228       | 98.7%   |
| Yes  | 3         | 1.3%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 77        | 33.33%  |
| 16.01-24.0  | 44        | 19.05%  |
| 3.01-4.0    | 41        | 17.75%  |
| 8.01-16.0   | 37        | 16.02%  |
| 32.01-64.0  | 19        | 8.23%   |
| 1.01-2.0    | 7         | 3.03%   |
| 24.01-32.0  | 3         | 1.3%    |
| 64.01-256.0 | 2         | 0.87%   |
| 2.01-3.0    | 1         | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 84        | 35.44%  |
| 2.01-3.0   | 72        | 30.38%  |
| 3.01-4.0   | 35        | 14.77%  |
| 4.01-8.0   | 26        | 10.97%  |
| 0.51-1.0   | 10        | 4.22%   |
| 8.01-16.0  | 9         | 3.8%    |
| 16.01-24.0 | 1         | 0.42%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 139       | 59.91%  |
| 2      | 67        | 28.88%  |
| 3      | 15        | 6.47%   |
| 4      | 5         | 2.16%   |
| 5      | 3         | 1.29%   |
| 7      | 2         | 0.86%   |
| 6      | 1         | 0.43%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 151       | 65.09%  |
| Yes       | 81        | 34.91%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 178       | 77.06%  |
| No        | 53        | 22.94%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 194       | 83.98%  |
| No        | 37        | 16.02%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 176       | 76.19%  |
| No        | 55        | 23.81%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 36        | 15.58%  |
| USA          | 30        | 12.99%  |
| India        | 14        | 6.06%   |
| Brazil       | 13        | 5.63%   |
| UK           | 12        | 5.19%   |
| Russia       | 10        | 4.33%   |
| Poland       | 9         | 3.9%    |
| Italy        | 8         | 3.46%   |
| France       | 8         | 3.46%   |
| Turkey       | 7         | 3.03%   |
| Spain        | 7         | 3.03%   |
| Indonesia    | 6         | 2.6%    |
| Canada       | 6         | 2.6%    |
| Austria      | 5         | 2.16%   |
| Australia    | 4         | 1.73%   |
| Argentina    | 4         | 1.73%   |
| Sweden       | 3         | 1.3%    |
| Mexico       | 3         | 1.3%    |
| Belgium      | 3         | 1.3%    |
| Switzerland  | 2         | 0.87%   |
| South Africa | 2         | 0.87%   |
| Romania      | 2         | 0.87%   |
| Portugal     | 2         | 0.87%   |
| New Zealand  | 2         | 0.87%   |
| Netherlands  | 2         | 0.87%   |
| Japan        | 2         | 0.87%   |
| Iran         | 2         | 0.87%   |
| Czechia      | 2         | 0.87%   |
| Colombia     | 2         | 0.87%   |
| Chile        | 2         | 0.87%   |
| Belarus      | 2         | 0.87%   |
| Ukraine      | 1         | 0.43%   |
| Thailand     | 1         | 0.43%   |
| Taiwan       | 1         | 0.43%   |
| Sri Lanka    | 1         | 0.43%   |
| Serbia       | 1         | 0.43%   |
| Peru         | 1         | 0.43%   |
| Pakistan     | 1         | 0.43%   |
| Mozambique   | 1         | 0.43%   |
| Malaysia     | 1         | 0.43%   |
| Lithuania    | 1         | 0.43%   |
| Latvia       | 1         | 0.43%   |
| Kenya        | 1         | 0.43%   |
| Ireland      | 1         | 0.43%   |
| Hungary      | 1         | 0.43%   |
| Hong Kong    | 1         | 0.43%   |
| Guyana       | 1         | 0.43%   |
| Greece       | 1         | 0.43%   |
| Croatia      | 1         | 0.43%   |
| Bulgaria     | 1         | 0.43%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                     | Computers | Percent |
|--------------------------|-----------|---------|
| Warsaw                   | 4         | 1.69%   |
| Munich                   | 4         | 1.69%   |
| Ankara                   | 4         | 1.69%   |
| Vienna                   | 3         | 1.27%   |
| Sydney                   | 3         | 1.27%   |
| St Petersburg            | 3         | 1.27%   |
| Wolgast                  | 2         | 0.85%   |
| Tucson                   | 2         | 0.85%   |
| SÃ£o Paulo             | 2         | 0.85%   |
| Paris                    | 2         | 0.85%   |
| Moscow                   | 2         | 0.85%   |
| Minsk                    | 2         | 0.85%   |
| Madrid                   | 2         | 0.85%   |
| Hamburg                  | 2         | 0.85%   |
| Dresden                  | 2         | 0.85%   |
| Berlin                   | 2         | 0.85%   |
| Antalya                  | 2         | 0.85%   |
| Znojmo                   | 1         | 0.42%   |
| Wroclaw                  | 1         | 0.42%   |
| Wriedel                  | 1         | 0.42%   |
| Woolloongabba            | 1         | 0.42%   |
| Witbank                  | 1         | 0.42%   |
| West Bromwich            | 1         | 0.42%   |
| Wellington               | 1         | 0.42%   |
| Wattala                  | 1         | 0.42%   |
| VitÃ³ria da Conquista  | 1         | 0.42%   |
| Vinnytsia                | 1         | 0.42%   |
| Vilanova i la GeltrÃº  | 1         | 0.42%   |
| Vila Nova de Gaia        | 1         | 0.42%   |
| Vigodarzere              | 1         | 0.42%   |
| Uppsala                  | 1         | 0.42%   |
| Trieste                  | 1         | 0.42%   |
| Tongeren                 | 1         | 0.42%   |
| Thrissur                 | 1         | 0.42%   |
| The Hague                | 1         | 0.42%   |
| Tehran                   | 1         | 0.42%   |
| Tecuci                   | 1         | 0.42%   |
| Tangerang                | 1         | 0.42%   |
| Surrey                   | 1         | 0.42%   |
| Suresnes                 | 1         | 0.42%   |
| Surabaya                 | 1         | 0.42%   |
| Stronsdorf               | 1         | 0.42%   |
| Stockholm                | 1         | 0.42%   |
| Steinbach                | 1         | 0.42%   |
| Southampton              | 1         | 0.42%   |
| Sornay                   | 1         | 0.42%   |
| Soliera                  | 1         | 0.42%   |
| Solapur                  | 1         | 0.42%   |
| Siersburg                | 1         | 0.42%   |
| Shetland Islands         | 1         | 0.42%   |
| Semarang                 | 1         | 0.42%   |
| Scottsdale               | 1         | 0.42%   |
| SÃ£o Bernardo do Campo | 1         | 0.42%   |
| Sazava                   | 1         | 0.42%   |
| Sassnitz                 | 1         | 0.42%   |
| Santo AndrÃ©           | 1         | 0.42%   |
| Santa Clara              | 1         | 0.42%   |
| San Antonio              | 1         | 0.42%   |
| Samobor                  | 1         | 0.42%   |
| Saltsjoe-Boo             | 1         | 0.42%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 55        | 67     | 16.47%  |
| WDC                       | 41        | 54     | 12.28%  |
| Seagate                   | 36        | 39     | 10.78%  |
| Kingston                  | 24        | 26     | 7.19%   |
| Sandisk                   | 22        | 24     | 6.59%   |
| Crucial                   | 20        | 21     | 5.99%   |
| Toshiba                   | 16        | 18     | 4.79%   |
| Unknown                   | 13        | 18     | 3.89%   |
| Intel                     | 8         | 9      | 2.4%    |
| HGST                      | 8         | 8      | 2.4%    |
| Apple                     | 8         | 8      | 2.4%    |
| SK Hynix                  | 7         | 7      | 2.1%    |
| Hitachi                   | 7         | 7      | 2.1%    |
| A-DATA Technology         | 6         | 6      | 1.8%    |
| PNY                       | 5         | 5      | 1.5%    |
| Unknown                   | 5         | 6      | 1.5%    |
| Phison                    | 4         | 4      | 1.2%    |
| Transcend                 | 3         | 3      | 0.9%    |
| Micron Technology         | 3         | 3      | 0.9%    |
| KIOXIA                    | 3         | 3      | 0.9%    |
| ASMT                      | 3         | 3      | 0.9%    |
| Teclast                   | 2         | 2      | 0.6%    |
| LITEON                    | 2         | 2      | 0.6%    |
| KingDian                  | 2         | 2      | 0.6%    |
| JMicron                   | 2         | 2      | 0.6%    |
| China                     | 2         | 2      | 0.6%    |
| TO Exter                  | 1         | 1      | 0.3%    |
| Team                      | 1         | 1      | 0.3%    |
| Star Drive                | 1         | 1      | 0.3%    |
| Star                      | 1         | 1      | 0.3%    |
| SSK                       | 1         | 1      | 0.3%    |
| SSDPR-CX                  | 1         | 1      | 0.3%    |
| SPCC                      | 1         | 1      | 0.3%    |
| Silicon Motion            | 1         | 1      | 0.3%    |
| SABRENT                   | 1         | 1      | 0.3%    |
| Realtek Semiconductor     | 1         | 1      | 0.3%    |
| OCZ                       | 1         | 1      | 0.3%    |
| Netac                     | 1         | 1      | 0.3%    |
| Micron/Crucial Technology | 1         | 1      | 0.3%    |
| MENGMI                    | 1         | 1      | 0.3%    |
| MAXTOR                    | 1         | 1      | 0.3%    |
| Leven                     | 1         | 1      | 0.3%    |
| KingSpec                  | 1         | 1      | 0.3%    |
| Intenso                   | 1         | 1      | 0.3%    |
| Hewlett-Packard           | 1         | 1      | 0.3%    |
| GOODRAM                   | 1         | 1      | 0.3%    |
| Gigabyte Technology       | 1         | 1      | 0.3%    |
| Fujitsu                   | 1         | 1      | 0.3%    |
| Ext Hard                  | 1         | 1      | 0.3%    |
| Corsair                   | 1         | 1      | 0.3%    |
| Colorful                  | 1         | 1      | 0.3%    |
| asmedia                   | 1         | 1      | 0.3%    |
| Apacer                    | 1         | 1      | 0.3%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 6         | 1.69%   |
| Samsung NVMe SSD Drive 512GB           | 6         | 1.69%   |
| Seagate ST1000LM035-1RK172 1TB         | 5         | 1.4%    |
| Kingston SA400S37240G 240GB SSD        | 5         | 1.4%    |
| Unknown                                | 5         | 1.4%    |
| Samsung SSD 850 EVO 250GB              | 4         | 1.12%   |
| Samsung NVMe SSD Drive 500GB           | 4         | 1.12%   |
| Kingston SA400S37120G 120GB SSD        | 4         | 1.12%   |
| Intel NVMe SSD Drive 512GB             | 4         | 1.12%   |
| Crucial CT240BX500SSD1 240GB           | 4         | 1.12%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 3         | 0.84%   |
| Toshiba MQ04ABF100 1TB                 | 3         | 0.84%   |
| Toshiba KBG30ZMS128G 128GB NVMe SSD    | 3         | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 3         | 0.84%   |
| Sandisk NVMe SSD Drive 512GB           | 3         | 0.84%   |
| PNY CS900 480GB SSD                    | 3         | 0.84%   |
| Kingston NVMe SSD Drive 500GB          | 3         | 0.84%   |
| Crucial CT1000MX500SSD1 1TB            | 3         | 0.84%   |
| WDC WD5000LPVX-75V0TT0 500GB           | 2         | 0.56%   |
| WDC WD5000AAKX-00ERMA0 500GB           | 2         | 0.56%   |
| Unknown SD/MMC 16GB                    | 2         | 0.56%   |
| Unknown MMC Card  32GB                 | 2         | 0.56%   |
| Unknown MMC Card  128GB                | 2         | 0.56%   |
| Unknown M.S./M.S.Pro/HG 16GB           | 2         | 0.56%   |
| Toshiba MQ01ABF050 500GB               | 2         | 0.56%   |
| Toshiba HDWD110 1TB                    | 2         | 0.56%   |
| Toshiba DT01ACA050 500GB               | 2         | 0.56%   |
| SK Hynix NVMe SSD Drive 512GB          | 2         | 0.56%   |
| SK Hynix NVMe SSD Drive 256GB          | 2         | 0.56%   |
| Seagate ST9500325AS 500GB              | 2         | 0.56%   |
| Seagate ST500LT012-1DG142 500GB        | 2         | 0.56%   |
| Seagate ST1000DM003-1ER162 1TB         | 2         | 0.56%   |
| Seagate OneTouch HDD 4TB               | 2         | 0.56%   |
| Seagate Expansion Desk 8TB             | 2         | 0.56%   |
| SanDisk SD9SN8W-128G-1006 128GB SSD    | 2         | 0.56%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD    | 2         | 0.56%   |
| Samsung SSD 860 EVO 1TB                | 2         | 0.56%   |
| Samsung SSD 850 EVO 120GB              | 2         | 0.56%   |
| Samsung SSD 840 EVO 120GB              | 2         | 0.56%   |
| Samsung NVMe SSD Drive 1TB             | 2         | 0.56%   |
| Samsung NVMe SSD Drive 1024GB          | 2         | 0.56%   |
| Samsung MZNLN128HAHQ-000H1 128GB SSD   | 2         | 0.56%   |
| Samsung HD322HJ 320GB                  | 2         | 0.56%   |
| PNY CS900 120GB SSD                    | 2         | 0.56%   |
| Phison NVMe SSD Drive 1TB              | 2         | 0.56%   |
| Kingston NVMe SSD Drive 1TB            | 2         | 0.56%   |
| JMicron Tech 250GB                     | 2         | 0.56%   |
| Hitachi HTS547575A9E384 752GB          | 2         | 0.56%   |
| HGST HTS545050A7E380 500GB             | 2         | 0.56%   |
| HGST HTS541010B7E610 1TB               | 2         | 0.56%   |
| Crucial CT480BX500SSD1 480GB           | 2         | 0.56%   |
| Crucial CT250MX500SSD1 250GB           | 2         | 0.56%   |
| Crucial CT120BX500SSD1 120GB           | 2         | 0.56%   |
| WDC WDS500G2B0A-00SM50 500GB SSD       | 1         | 0.28%   |
| WDC WDS480G2G0A-00JH30 480GB SSD       | 1         | 0.28%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD       | 1         | 0.28%   |
| WDC WDS200T2B0A-00SM50 2TB SSD         | 1         | 0.28%   |
| WDC WDS120G2G0A-00JH30 120GB SSD       | 1         | 0.28%   |
| WDC WD7500BPVT-22A1YT0 752GB           | 1         | 0.28%   |
| WDC WD6401AALS-00L3B2 640GB            | 1         | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 35        | 38     | 34.31%  |
| WDC                 | 31        | 38     | 30.39%  |
| Toshiba             | 11        | 12     | 10.78%  |
| HGST                | 8         | 8      | 7.84%   |
| Hitachi             | 7         | 7      | 6.86%   |
| Samsung Electronics | 2         | 3      | 1.96%   |
| ASMT                | 2         | 2      | 1.96%   |
| Unknown             | 1         | 1      | 0.98%   |
| SABRENT             | 1         | 1      | 0.98%   |
| Hewlett-Packard     | 1         | 1      | 0.98%   |
| Fujitsu             | 1         | 1      | 0.98%   |
| Ext Hard            | 1         | 1      | 0.98%   |
| Apple               | 1         | 1      | 0.98%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 32        | 37     | 23.36%  |
| Crucial             | 20        | 21     | 14.6%   |
| SanDisk             | 15        | 17     | 10.95%  |
| Kingston            | 14        | 15     | 10.22%  |
| WDC                 | 8         | 12     | 5.84%   |
| Apple               | 6         | 6      | 4.38%   |
| PNY                 | 5         | 5      | 3.65%   |
| A-DATA Technology   | 5         | 5      | 3.65%   |
| Transcend           | 3         | 3      | 2.19%   |
| Micron Technology   | 3         | 3      | 2.19%   |
| Teclast             | 2         | 2      | 1.46%   |
| LITEON              | 2         | 2      | 1.46%   |
| Intel               | 2         | 2      | 1.46%   |
| China               | 2         | 2      | 1.46%   |
| Toshiba             | 1         | 1      | 0.73%   |
| TO Exter            | 1         | 1      | 0.73%   |
| Team                | 1         | 1      | 0.73%   |
| Star                | 1         | 1      | 0.73%   |
| SPCC                | 1         | 1      | 0.73%   |
| OCZ                 | 1         | 1      | 0.73%   |
| MENGMI              | 1         | 1      | 0.73%   |
| MAXTOR              | 1         | 1      | 0.73%   |
| Leven               | 1         | 1      | 0.73%   |
| KingSpec            | 1         | 1      | 0.73%   |
| KingDian            | 1         | 1      | 0.73%   |
| Intenso             | 1         | 1      | 0.73%   |
| GOODRAM             | 1         | 1      | 0.73%   |
| Gigabyte Technology | 1         | 1      | 0.73%   |
| Corsair             | 1         | 1      | 0.73%   |
| Colorful            | 1         | 1      | 0.73%   |
| Apacer              | 1         | 1      | 0.73%   |
| Unknown             | 1         | 1      | 0.73%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 125       | 150    | 39.68%  |
| HDD     | 92        | 114    | 29.21%  |
| NVMe    | 73        | 81     | 23.17%  |
| Unknown | 13        | 17     | 4.13%   |
| MMC     | 12        | 14     | 3.81%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 178       | 256    | 62.9%   |
| NVMe | 73        | 81     | 25.8%   |
| SAS  | 20        | 25     | 7.07%   |
| MMC  | 12        | 14     | 4.24%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 136       | 178    | 66.02%  |
| 0.51-1.0   | 45        | 56     | 21.84%  |
| 1.01-2.0   | 13        | 17     | 6.31%   |
| 3.01-4.0   | 6         | 6      | 2.91%   |
| 4.01-10.0  | 4         | 4      | 1.94%   |
| 2.01-3.0   | 2         | 3      | 0.97%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 92        | 39.66%  |
| 251-500        | 66        | 28.45%  |
| 501-1000       | 27        | 11.64%  |
| 51-100         | 19        | 8.19%   |
| 1001-2000      | 13        | 5.6%    |
| 21-50          | 8         | 3.45%   |
| More than 3000 | 6         | 2.59%   |
| 2001-3000      | 1         | 0.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 107       | 45.53%  |
| 21-50          | 56        | 23.83%  |
| 51-100         | 25        | 10.64%  |
| 101-250        | 24        | 10.21%  |
| 251-500        | 10        | 4.26%   |
| 501-1000       | 6         | 2.55%   |
| 1001-2000      | 4         | 1.7%    |
| 2001-3000      | 2         | 0.85%   |
| More than 3000 | 1         | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                           | Computers | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB          | 1         | 1      | 20%     |
| Toshiba KBG30ZPZ128G 128GB      | 1         | 1      | 20%     |
| Seagate ST500LM030-2E717D 500GB | 1         | 1      | 20%     |
| Seagate ST3500312CS 500GB       | 1         | 1      | 20%     |
| Crucial CT512M550SSD3 512GB     | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 40%     |
| WDC     | 1         | 1      | 20%     |
| Toshiba | 1         | 1      | 20%     |
| Crucial | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 66.67%  |
| WDC     | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 60%     |
| NVMe | 1         | 1      | 20%     |
| SSD  | 1         | 1      | 20%     |

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
| Detected | 202       | 313    | 82.11%  |
| Works    | 39        | 58     | 15.85%  |
| Malfunc  | 5         | 5      | 2.03%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 155       | 55.36%  |
| AMD                          | 35        | 12.5%   |
| Samsung Electronics          | 27        | 9.64%   |
| Nvidia                       | 11        | 3.93%   |
| Kingston Technology Company  | 11        | 3.93%   |
| Sandisk                      | 10        | 3.57%   |
| SK Hynix                     | 7         | 2.5%    |
| Phison Electronics           | 5         | 1.79%   |
| Toshiba America Info Systems | 4         | 1.43%   |
| Marvell Technology Group     | 3         | 1.07%   |
| Realtek Semiconductor        | 2         | 0.71%   |
| KIOXIA                       | 2         | 0.71%   |
| ASMedia Technology           | 2         | 0.71%   |
| Silicon Motion               | 1         | 0.36%   |
| Seagate Technology           | 1         | 0.36%   |
| Micron/Crucial Technology    | 1         | 0.36%   |
| JMicron Technology           | 1         | 0.36%   |
| Hewlett-Packard              | 1         | 0.36%   |
| Apple                        | 1         | 0.36%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 25        | 8.17%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 15        | 4.9%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 14        | 4.58%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 12        | 3.92%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 11        | 3.59%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 10        | 3.27%   |
| Samsung NVMe SSD Controller 980                                                         | 8         | 2.61%   |
| Nvidia MCP79 AHCI Controller                                                            | 8         | 2.61%   |
| AMD 400 Series Chipset SATA Controller                                                  | 8         | 2.61%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 7         | 2.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 6         | 1.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6         | 1.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 1.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 6         | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 6         | 1.96%   |
| Intel SSD 660P Series                                                                   | 5         | 1.63%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 5         | 1.63%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 5         | 1.63%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 5         | 1.63%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 1.63%   |
| Kingston Company A2000 NVMe SSD                                                         | 4         | 1.31%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.31%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4         | 1.31%   |
| Toshiba America Info Systems BG3 NVMe SSD Controller                                    | 3         | 0.98%   |
| SK Hynix BC511                                                                          | 3         | 0.98%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 3         | 0.98%   |
| Samsung NVMe SSD Controller SM951/PM951                                                 | 3         | 0.98%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3         | 0.98%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 3         | 0.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 3         | 0.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 3         | 0.98%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 3         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 3         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 3         | 0.98%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 2         | 0.65%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                              | 2         | 0.65%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                         | 2         | 0.65%   |
| Samsung Electronics SATA controller                                                     | 2         | 0.65%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 2         | 0.65%   |
| Phison E12 NVMe Controller                                                              | 2         | 0.65%   |
| KIOXIA Non-Volatile memory controller                                                   | 2         | 0.65%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                                   | 2         | 0.65%   |
| Kingston Company OM3PDP3 NVMe SSD                                                       | 2         | 0.65%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.65%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 0.65%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 2         | 0.65%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 0.65%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                                | 2         | 0.65%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 2         | 0.65%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 2         | 0.65%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 2         | 0.65%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 1         | 0.33%   |
| SK Hynix PC401 NVMe Solid State Drive 256GB                                             | 1         | 0.33%   |
| SK Hynix Non-Volatile memory controller                                                 | 1         | 0.33%   |
| SK Hynix Gold P31 SSD                                                                   | 1         | 0.33%   |
| SK Hynix BC501 NVMe Solid State Drive                                                   | 1         | 0.33%   |
| Silicon Motion Non-Volatile memory controller                                           | 1         | 0.33%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 184       | 64.34%  |
| NVMe | 72        | 25.17%  |
| IDE  | 18        | 6.29%   |
| RAID | 11        | 3.85%   |
| SAS  | 1         | 0.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 185       | 80.09%  |
| AMD    | 46        | 19.91%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz         | 6         | 2.6%    |
| Intel Core i7-8565U CPU @ 1.80GHz               | 4         | 1.73%   |
| Intel Core i7-8550U CPU @ 1.80GHz               | 4         | 1.73%   |
| Intel Core i5-6200U CPU @ 2.30GHz               | 4         | 1.73%   |
| Intel Core i7-5500U CPU @ 2.40GHz               | 3         | 1.3%    |
| Intel Core i5-2520M CPU @ 2.50GHz               | 3         | 1.3%    |
| Intel Core i5-10210U CPU @ 1.60GHz              | 3         | 1.3%    |
| Intel Core i3-10110U CPU @ 2.10GHz              | 3         | 1.3%    |
| Intel Core 2 Duo CPU P7350 @ 2.00GHz            | 3         | 1.3%    |
| Intel Celeron CPU N3050 @ 1.60GHz               | 3         | 1.3%    |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics      | 3         | 1.3%    |
| AMD Ryzen 7 4700U with Radeon Graphics          | 3         | 1.3%    |
| AMD Ryzen 5 5500U with Radeon Graphics          | 3         | 1.3%    |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx   | 3         | 1.3%    |
| Intel Core i7-9700 CPU @ 3.00GHz                | 2         | 0.87%   |
| Intel Core i7-8750H CPU @ 2.20GHz               | 2         | 0.87%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz              | 2         | 0.87%   |
| Intel Core i7-2670QM CPU @ 2.20GHz              | 2         | 0.87%   |
| Intel Core i5-8400 CPU @ 2.80GHz                | 2         | 0.87%   |
| Intel Core i5-7200U CPU @ 2.50GHz               | 2         | 0.87%   |
| Intel Core i5-6300U CPU @ 2.40GHz               | 2         | 0.87%   |
| Intel Core i5-5300U CPU @ 2.30GHz               | 2         | 0.87%   |
| Intel Core i5-4260U CPU @ 1.40GHz               | 2         | 0.87%   |
| Intel Core i5-3470 CPU @ 3.20GHz                | 2         | 0.87%   |
| Intel Core i5-3317U CPU @ 1.70GHz               | 2         | 0.87%   |
| Intel Core i5 CPU M 520 @ 2.40GHz               | 2         | 0.87%   |
| Intel Core i3-8145U CPU @ 2.10GHz               | 2         | 0.87%   |
| Intel Core i3 CPU M 350 @ 2.27GHz               | 2         | 0.87%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz            | 2         | 0.87%   |
| Intel 11th Gen Core i7-11700K @ 3.60GHz         | 2         | 0.87%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz         | 2         | 0.87%   |
| AMD Ryzen 9 3900X 12-Core Processor             | 2         | 0.87%   |
| AMD Ryzen 7 3700X 8-Core Processor              | 2         | 0.87%   |
| AMD Ryzen 5 4500U with Radeon Graphics          | 2         | 0.87%   |
| AMD Ryzen 5 2600 Six-Core Processor             | 2         | 0.87%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx   | 2         | 0.87%   |
| AMD A12-9720P RADEON R7, 12 COMPUTE CORES 4C+8G | 2         | 0.87%   |
| Intel Xeon CPU E5462 @ 2.80GHz                  | 1         | 0.43%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz              | 1         | 0.43%   |
| Intel Xeon CPU E5-2670 0 @ 2.60GHz              | 1         | 0.43%   |
| Intel Xeon CPU E31240 @ 3.30GHz                 | 1         | 0.43%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz        | 1         | 0.43%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz     | 1         | 0.43%   |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz     | 1         | 0.43%   |
| Intel Pentium CPU N4200 @ 1.10GHz               | 1         | 0.43%   |
| Intel Pentium CPU N3700 @ 1.60GHz               | 1         | 0.43%   |
| Intel Pentium CPU G630 @ 2.70GHz                | 1         | 0.43%   |
| Intel Pentium CPU 4415Y @ 1.60GHz               | 1         | 0.43%   |
| Intel Core m5-6Y57 CPU @ 1.10GHz                | 1         | 0.43%   |
| Intel Core i7-9750H CPU @ 2.60GHz               | 1         | 0.43%   |
| Intel Core i7-9700K CPU @ 3.60GHz               | 1         | 0.43%   |
| Intel Core i7-8850H CPU @ 2.60GHz               | 1         | 0.43%   |
| Intel Core i7-8650U CPU @ 1.90GHz               | 1         | 0.43%   |
| Intel Core i7-7700K CPU @ 4.20GHz               | 1         | 0.43%   |
| Intel Core i7-7500U CPU @ 2.70GHz               | 1         | 0.43%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz              | 1         | 0.43%   |
| Intel Core i7-6700K CPU @ 4.00GHz               | 1         | 0.43%   |
| Intel Core i7-6700 CPU @ 3.40GHz                | 1         | 0.43%   |
| Intel Core i7-6500U CPU @ 2.50GHz               | 1         | 0.43%   |
| Intel Core i7-5650U CPU @ 2.20GHz               | 1         | 0.43%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 51        | 22.08%  |
| Intel Core i5           | 50        | 21.65%  |
| Intel Core i3           | 27        | 11.69%  |
| Intel Celeron           | 16        | 6.93%   |
| AMD Ryzen 5             | 15        | 6.49%   |
| Intel Core 2 Duo        | 14        | 6.06%   |
| Other                   | 12        | 5.19%   |
| AMD Ryzen 7             | 9         | 3.9%    |
| Intel Xeon              | 4         | 1.73%   |
| Intel Pentium           | 4         | 1.73%   |
| Intel Atom              | 3         | 1.3%    |
| AMD Ryzen 7 PRO         | 3         | 1.3%    |
| AMD Ryzen 3             | 3         | 1.3%    |
| AMD Phenom II X4        | 3         | 1.3%    |
| Intel Pentium Dual-Core | 2         | 0.87%   |
| AMD Ryzen 9             | 2         | 0.87%   |
| AMD A8                  | 2         | 0.87%   |
| AMD A12                 | 2         | 0.87%   |
| AMD A10                 | 2         | 0.87%   |
| Intel Pentium Silver    | 1         | 0.43%   |
| Intel Core m5           | 1         | 0.43%   |
| Intel Core 2 Quad       | 1         | 0.43%   |
| Intel Celeron Dual-Core | 1         | 0.43%   |
| AMD FX                  | 1         | 0.43%   |
| AMD Athlon              | 1         | 0.43%   |
| AMD A6                  | 1         | 0.43%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 105       | 45.45%  |
| 4      | 83        | 35.93%  |
| 6      | 20        | 8.66%   |
| 8      | 19        | 8.23%   |
| 12     | 2         | 0.87%   |
| 16     | 1         | 0.43%   |
| 1      | 1         | 0.43%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 229       | 99.13%  |
| 2      | 2         | 0.87%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 158       | 68.4%   |
| 1      | 73        | 31.6%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 231       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 22        | 9.44%   |
| Unknown    | 18        | 7.73%   |
| 0x306a9    | 14        | 6.01%   |
| 0x306c3    | 10        | 4.29%   |
| 0x306d4    | 9         | 3.86%   |
| 0x1067a    | 9         | 3.86%   |
| 0x806c1    | 8         | 3.43%   |
| 0x406e3    | 8         | 3.43%   |
| 0x40651    | 8         | 3.43%   |
| 0x806ec    | 7         | 3%      |
| 0x10676    | 7         | 3%      |
| 0x906ea    | 6         | 2.58%   |
| 0x406c3    | 6         | 2.58%   |
| 0x08600106 | 6         | 2.58%   |
| 0x906e9    | 5         | 2.15%   |
| 0x806eb    | 5         | 2.15%   |
| 0x806ea    | 5         | 2.15%   |
| 0x506e3    | 5         | 2.15%   |
| 0x20655    | 5         | 2.15%   |
| 0x806e9    | 4         | 1.72%   |
| 0x08701021 | 4         | 1.72%   |
| 0x08108109 | 4         | 1.72%   |
| 0x906ed    | 3         | 1.29%   |
| 0x706a8    | 3         | 1.29%   |
| 0x506c9    | 3         | 1.29%   |
| 0x20652    | 3         | 1.29%   |
| 0x08608103 | 3         | 1.29%   |
| 0xa0671    | 2         | 0.86%   |
| 0x906eb    | 2         | 0.86%   |
| 0x30678    | 2         | 0.86%   |
| 0x206d7    | 2         | 0.86%   |
| 0x08108102 | 2         | 0.86%   |
| 0x08101007 | 2         | 0.86%   |
| 0x0800820d | 2         | 0.86%   |
| 0x06003106 | 2         | 0.86%   |
| 0x010000c8 | 2         | 0.86%   |
| 0xa0660    | 1         | 0.43%   |
| 0xa0652    | 1         | 0.43%   |
| 0x906ec    | 1         | 0.43%   |
| 0x906c0    | 1         | 0.43%   |
| 0x706a1    | 1         | 0.43%   |
| 0x6fd      | 1         | 0.43%   |
| 0x6fb      | 1         | 0.43%   |
| 0x6fa      | 1         | 0.43%   |
| 0x406c4    | 1         | 0.43%   |
| 0x40661    | 1         | 0.43%   |
| 0x306e4    | 1         | 0.43%   |
| 0x106e5    | 1         | 0.43%   |
| 0x106ca    | 1         | 0.43%   |
| 0x0a201009 | 1         | 0.43%   |
| 0x08701013 | 1         | 0.43%   |
| 0x08600104 | 1         | 0.43%   |
| 0x08101016 | 1         | 0.43%   |
| 0x07030105 | 1         | 0.43%   |
| 0x07030104 | 1         | 0.43%   |
| 0x06006705 | 1         | 0.43%   |
| 0x06006704 | 1         | 0.43%   |
| 0x0600611a | 1         | 0.43%   |
| 0x06001119 | 1         | 0.43%   |
| 0x0600063e | 1         | 0.43%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 44        | 19.05%  |
| SandyBridge   | 25        | 10.82%  |
| Haswell       | 20        | 8.66%   |
| Zen 2         | 16        | 6.93%   |
| Penryn        | 16        | 6.93%   |
| IvyBridge     | 15        | 6.49%   |
| Skylake       | 14        | 6.06%   |
| Zen+          | 9         | 3.9%    |
| Silvermont    | 9         | 3.9%    |
| Broadwell     | 9         | 3.9%    |
| Westmere      | 8         | 3.46%   |
| TigerLake     | 8         | 3.46%   |
| Goldmont plus | 4         | 1.73%   |
| Excavator     | 4         | 1.73%   |
| Unknown       | 4         | 1.73%   |
| Zen           | 3         | 1.3%    |
| K10           | 3         | 1.3%    |
| Goldmont      | 3         | 1.3%    |
| Core          | 3         | 1.3%    |
| Steamroller   | 2         | 0.87%   |
| Puma          | 2         | 0.87%   |
| Icelake       | 2         | 0.87%   |
| CometLake     | 2         | 0.87%   |
| Zen 3         | 1         | 0.43%   |
| Tremont       | 1         | 0.43%   |
| Piledriver    | 1         | 0.43%   |
| Nehalem       | 1         | 0.43%   |
| Bulldozer     | 1         | 0.43%   |
| Bonnell       | 1         | 0.43%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 144       | 52.36%  |
| Nvidia                     | 68        | 24.73%  |
| AMD                        | 62        | 22.55%  |
| Matrox Electronics Systems | 1         | 0.36%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 20        | 7.07%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 11        | 3.89%   |
| AMD Renoir                                                                               | 10        | 3.53%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 2.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 8         | 2.83%   |
| Nvidia C79 [GeForce 9400M]                                                               | 7         | 2.47%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 7         | 2.47%   |
| Intel UHD Graphics 620                                                                   | 7         | 2.47%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 7         | 2.47%   |
| Intel HD Graphics 5500                                                                   | 7         | 2.47%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 2.47%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 6         | 2.12%   |
| Intel Core Processor Integrated Graphics Controller                                      | 5         | 1.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 5         | 1.77%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 1.77%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 1.77%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 4         | 1.41%   |
| Intel HD Graphics 630                                                                    | 4         | 1.41%   |
| AMD Lucienne                                                                             | 4         | 1.41%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 3         | 1.06%   |
| Intel HD Graphics 620                                                                    | 3         | 1.06%   |
| Intel HD Graphics 530                                                                    | 3         | 1.06%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 1.06%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 3         | 1.06%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 3         | 1.06%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 2         | 0.71%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.71%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.71%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 2         | 0.71%   |
| Nvidia GM108M [GeForce 940M]                                                             | 2         | 0.71%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 2         | 0.71%   |
| Nvidia GM108M [GeForce 840M]                                                             | 2         | 0.71%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 2         | 0.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 2         | 0.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 2         | 0.71%   |
| Intel HD Graphics 6000                                                                   | 2         | 0.71%   |
| Intel HD Graphics 500                                                                    | 2         | 0.71%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.71%   |
| AMD Whistler [Radeon HD 6630M/6650M/6750M/7670M/7690M]                                   | 2         | 0.71%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 2         | 0.71%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 2         | 0.71%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 2         | 0.71%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 2         | 0.71%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.71%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 2         | 0.71%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 2         | 0.71%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 2         | 0.71%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 0.71%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                           | 2         | 0.71%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 2         | 0.71%   |
| Nvidia TU117M [GeForce MX450]                                                            | 1         | 0.35%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 1         | 0.35%   |
| Nvidia TU117M                                                                            | 1         | 0.35%   |
| Nvidia TU116 [GeForce GTX 1660]                                                          | 1         | 0.35%   |
| Nvidia TU104 [GeForce RTX 2080]                                                          | 1         | 0.35%   |
| Nvidia TU104 [GeForce RTX 2080 SUPER]                                                    | 1         | 0.35%   |
| Nvidia TU104 [GeForce RTX 2060]                                                          | 1         | 0.35%   |
| Nvidia MCP89 [GeForce 320M]                                                              | 1         | 0.35%   |
| Nvidia GT216M [GeForce GT 330M]                                                          | 1         | 0.35%   |
| Nvidia GP108M [GeForce MX250]                                                            | 1         | 0.35%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 101       | 43.72%  |
| 1 x AMD        | 47        | 20.35%  |
| 1 x Nvidia     | 35        | 15.15%  |
| Intel + Nvidia | 31        | 13.42%  |
| Intel + AMD    | 10        | 4.33%   |
| 2 x AMD        | 4         | 1.73%   |
| 2 x Nvidia     | 1         | 0.43%   |
| 1 x Matrox     | 1         | 0.43%   |
| AMD + Nvidia   | 1         | 0.43%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 196       | 84.48%  |
| Proprietary | 36        | 15.52%  |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 117       | 50.43%  |
| 0.01-0.5   | 31        | 13.36%  |
| 1.01-2.0   | 30        | 12.93%  |
| 3.01-4.0   | 21        | 9.05%   |
| 0.51-1.0   | 21        | 9.05%   |
| 7.01-8.0   | 5         | 2.16%   |
| 5.01-6.0   | 4         | 1.72%   |
| 8.01-16.0  | 2         | 0.86%   |
| 2.01-3.0   | 1         | 0.43%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 37        | 14.12%  |
| LG Display              | 28        | 10.69%  |
| Apple                   | 27        | 10.31%  |
| Chimei Innolux          | 26        | 9.92%   |
| Samsung Electronics     | 24        | 9.16%   |
| BOE                     | 15        | 5.73%   |
| Acer                    | 12        | 4.58%   |
| Goldstar                | 11        | 4.2%    |
| Hewlett-Packard         | 9         | 3.44%   |
| Dell                    | 8         | 3.05%   |
| Sharp                   | 7         | 2.67%   |
| Lenovo                  | 6         | 2.29%   |
| BenQ                    | 6         | 2.29%   |
| Philips                 | 5         | 1.91%   |
| PANDA                   | 4         | 1.53%   |
| CSO                     | 4         | 1.53%   |
| Chi Mei Optoelectronics | 3         | 1.15%   |
| AOC                     | 3         | 1.15%   |
| Ancor Communications    | 3         | 1.15%   |
| ViewSonic               | 2         | 0.76%   |
| InfoVision              | 2         | 0.76%   |
| AUS                     | 2         | 0.76%   |
| Vestel                  | 1         | 0.38%   |
| Toshiba                 | 1         | 0.38%   |
| Sony                    | 1         | 0.38%   |
| Panasonic               | 1         | 0.38%   |
| MSI                     | 1         | 0.38%   |
| Mi                      | 1         | 0.38%   |
| Marantz                 | 1         | 0.38%   |
| LG Electronics          | 1         | 0.38%   |
| JDI                     | 1         | 0.38%   |
| IOD                     | 1         | 0.38%   |
| Iiyama                  | 1         | 0.38%   |
| HUAWEI                  | 1         | 0.38%   |
| HPN                     | 1         | 0.38%   |
| Element                 | 1         | 0.38%   |
| Eizo                    | 1         | 0.38%   |
| CHR                     | 1         | 0.38%   |
| CHD                     | 1         | 0.38%   |
| Unknown                 | 1         | 0.38%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 4         | 1.48%   |
| CSO LCD Monitor CSO1309 3000x2000 293x195mm 13.9-inch                  | 3         | 1.11%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 3         | 1.11%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 3         | 1.11%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 3         | 1.11%   |
| Apple LCD Monitor APP9C89 1280x800 286x179mm 13.3-inch                 | 3         | 1.11%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 2         | 0.74%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 2         | 0.74%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch           | 2         | 0.74%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch           | 2         | 0.74%   |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch            | 2         | 0.74%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch                | 2         | 0.74%   |
| Goldstar 22EN33 GSM597C 1920x1080 480x270mm 21.7-inch                  | 2         | 0.74%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch        | 2         | 0.74%   |
| BOE LCD Monitor BOE06DF 1920x1080 309x173mm 13.9-inch                  | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch         | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch          | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch          | 2         | 0.74%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch         | 2         | 0.74%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                   | 2         | 0.74%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                   | 2         | 0.74%   |
| Apple Color LCD APP9CA4 1440x900 331x207mm 15.4-inch                   | 2         | 0.74%   |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch              | 1         | 0.37%   |
| ViewSonic LCD Monitor VX2260WM 3840x1080                               | 1         | 0.37%   |
| ViewSonic LCD Monitor VX2260WM                                         | 1         | 0.37%   |
| Vestel LCD Monitor 49FHD_LCD_TV 1920x1080                              | 1         | 0.37%   |
| Toshiba TV TSB2019 3840x2160                                           | 1         | 0.37%   |
| Sony LCD Monitor SNY05FA 1366x768 340x190mm 15.3-inch                  | 1         | 0.37%   |
| Sharp PN-K321 SHP21DD 3840x2160                                        | 1         | 0.37%   |
| Sharp LQ100P1JX51 SHP14A6 1800x1200 211x141mm 10.0-inch                | 1         | 0.37%   |
| Sharp LCD Monitor SHP14B8 1920x1080 294x165mm 13.3-inch                | 1         | 0.37%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch                | 1         | 0.37%   |
| Sharp LCD Monitor SHP1447 1920x1080 294x165mm 13.3-inch                | 1         | 0.37%   |
| Sharp LCD Monitor SHP1431 3840x2160 350x190mm 15.7-inch                | 1         | 0.37%   |
| Sharp LCD Monitor SHP1421 3200x1800 294x165mm 13.3-inch                | 1         | 0.37%   |
| Samsung Electronics U32R59x SAM0F94 3840x2160 700x390mm 31.5-inch      | 1         | 0.37%   |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch      | 1         | 0.37%   |
| Samsung Electronics T24D391 SAM0B72 1920x1080 521x293mm 23.5-inch      | 1         | 0.37%   |
| Samsung Electronics SA300/SA350 SAM078C 1600x900 443x249mm 20.0-inch   | 1         | 0.37%   |
| Samsung Electronics SA300/SA350 SAM078B 1600x900 443x249mm 20.0-inch   | 1         | 0.37%   |
| Samsung Electronics S22B300 SAM08AC 1920x1080 477x268mm 21.5-inch      | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC5A42 1366x768 309x174mm 14.0-inch   | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3541 1366x768 344x194mm 15.5-inch   | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SEC3242 1024x600 223x125mm 10.1-inch   | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SDC834D 1920x1080 293x165mm 13.2-inch  | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4259 1920x1080 293x165mm 13.2-inch  | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch  | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4158 1920x1080 294x165mm 13.3-inch  | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SDC280F 1366x768 344x193mm 15.5-inch   | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch  | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SAM0B54 1366x768 609x347mm 27.6-inch   | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SAM0900 1366x768 410x230mm 18.5-inch   | 1         | 0.37%   |
| Samsung Electronics LCD Monitor SAM0530 1360x768                       | 1         | 0.37%   |
| Samsung Electronics LCD Monitor S22D300                                | 1         | 0.37%   |
| Samsung Electronics LC32G5xT SAM7088 2560x1440 700x400mm 31.7-inch     | 1         | 0.37%   |
| Philips PHL 275E1 PHLC20C 2560x1440 597x336mm 27.0-inch                | 1         | 0.37%   |
| Philips PHL 203V5 PHLC0CE 1600x900 434x236mm 19.4-inch                 | 1         | 0.37%   |
| Philips LCD Monitor PHL 276E8V 7680x2160                               | 1         | 0.37%   |
| Philips LCD Monitor PHL 276E8V                                         | 1         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 102       | 40.16%  |
| 1366x768 (WXGA)    | 59        | 23.23%  |
| 2560x1440 (QHD)    | 17        | 6.69%   |
| 3840x2160 (4K)     | 13        | 5.12%   |
| 1600x900 (HD+)     | 12        | 4.72%   |
| 1280x800 (WXGA)    | 10        | 3.94%   |
| 1440x900 (WXGA+)   | 8         | 3.15%   |
| 1680x1050 (WSXGA+) | 6         | 2.36%   |
| 3000x2000          | 4         | 1.57%   |
| 1920x1200 (WUXGA)  | 3         | 1.18%   |
| Unknown            | 3         | 1.18%   |
| 3840x1080          | 2         | 0.79%   |
| 2560x1080          | 2         | 0.79%   |
| 1360x768           | 2         | 0.79%   |
| 7680x2160          | 1         | 0.39%   |
| 3840x2400          | 1         | 0.39%   |
| 3440x1440          | 1         | 0.39%   |
| 3200x1800 (QHD+)   | 1         | 0.39%   |
| 3072x1920          | 1         | 0.39%   |
| 2880x1920          | 1         | 0.39%   |
| 2880x1800          | 1         | 0.39%   |
| 1920x540           | 1         | 0.39%   |
| 1920x1280          | 1         | 0.39%   |
| 1800x1200          | 1         | 0.39%   |
| 1280x1024 (SXGA)   | 1         | 0.39%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 71        | 27.31%  |
| 13      | 44        | 16.92%  |
| 14      | 27        | 10.38%  |
| 24      | 15        | 5.77%   |
| Unknown | 14        | 5.38%   |
| 27      | 12        | 4.62%   |
| 23      | 12        | 4.62%   |
| 21      | 10        | 3.85%   |
| 17      | 9         | 3.46%   |
| 31      | 6         | 2.31%   |
| 11      | 5         | 1.92%   |
| 22      | 4         | 1.54%   |
| 20      | 4         | 1.54%   |
| 34      | 3         | 1.15%   |
| 32      | 3         | 1.15%   |
| 26      | 3         | 1.15%   |
| 12      | 3         | 1.15%   |
| 10      | 3         | 1.15%   |
| 25      | 2         | 0.77%   |
| 19      | 2         | 0.77%   |
| 18      | 2         | 0.77%   |
| 72      | 1         | 0.38%   |
| 65      | 1         | 0.38%   |
| 55      | 1         | 0.38%   |
| 48      | 1         | 0.38%   |
| 47      | 1         | 0.38%   |
| 16      | 1         | 0.38%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 112       | 43.75%  |
| 201-300     | 40        | 15.63%  |
| 501-600     | 38        | 14.84%  |
| 401-500     | 21        | 8.2%    |
| Unknown     | 14        | 5.47%   |
| 351-400     | 11        | 4.3%    |
| 601-700     | 9         | 3.52%   |
| 701-800     | 6         | 2.34%   |
| 1001-1500   | 4         | 1.56%   |
| 1501-2000   | 1         | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 179       | 76.17%  |
| 16/10   | 33        | 14.04%  |
| Unknown | 12        | 5.11%   |
| 3/2     | 8         | 3.4%    |
| 21/9    | 3         | 1.28%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 68        | 26.46%  |
| 81-90          | 53        | 20.62%  |
| 201-250        | 30        | 11.67%  |
| 71-80          | 19        | 7.39%   |
| Unknown        | 14        | 5.45%   |
| 301-350        | 13        | 5.06%   |
| 351-500        | 12        | 4.67%   |
| 251-300        | 10        | 3.89%   |
| 151-200        | 8         | 3.11%   |
| 121-130        | 8         | 3.11%   |
| 51-60          | 5         | 1.95%   |
| More than 1000 | 4         | 1.56%   |
| 41-50          | 3         | 1.17%   |
| 61-70          | 2         | 0.78%   |
| 141-150        | 2         | 0.78%   |
| 111-120        | 2         | 0.78%   |
| 91-100         | 2         | 0.78%   |
| 131-140        | 1         | 0.39%   |
| 501-1000       | 1         | 0.39%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 79        | 30.98%  |
| 101-120       | 77        | 30.2%   |
| 51-100        | 56        | 21.96%  |
| 161-240       | 14        | 5.49%   |
| Unknown       | 14        | 5.49%   |
| More than 240 | 10        | 3.92%   |
| 1-50          | 5         | 1.96%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 196       | 84.85%  |
| 2     | 30        | 12.99%  |
| 3     | 5         | 2.16%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 116       | 34.22%  |
| Intel                    | 104       | 30.68%  |
| Broadcom                 | 36        | 10.62%  |
| Qualcomm Atheros         | 32        | 9.44%   |
| Nvidia                   | 9         | 2.65%   |
| Broadcom Limited         | 6         | 1.77%   |
| Marvell Technology Group | 5         | 1.47%   |
| TP-Link                  | 4         | 1.18%   |
| Ralink Technology        | 4         | 1.18%   |
| Samsung Electronics      | 3         | 0.88%   |
| Ralink                   | 3         | 0.88%   |
| Xiaomi                   | 2         | 0.59%   |
| Google                   | 2         | 0.59%   |
| Sitecom Europe           | 1         | 0.29%   |
| Sierra Wireless          | 1         | 0.29%   |
| OPPO Electronics         | 1         | 0.29%   |
| Motorola PCS             | 1         | 0.29%   |
| Microsoft                | 1         | 0.29%   |
| MEDIATEK                 | 1         | 0.29%   |
| Linksys                  | 1         | 0.29%   |
| LG Electronics           | 1         | 0.29%   |
| Hewlett-Packard          | 1         | 0.29%   |
| D-Link System            | 1         | 0.29%   |
| AVM                      | 1         | 0.29%   |
| ASIX Electronics         | 1         | 0.29%   |
| Apple                    | 1         | 0.29%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 81        | 20.51%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 17        | 4.3%    |
| Intel Wi-Fi 6 AX200                                               | 11        | 2.78%   |
| Nvidia MCP79 Ethernet                                             | 9         | 2.28%   |
| Intel Wireless 8260                                               | 9         | 2.28%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 2.03%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 8         | 2.03%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 7         | 1.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 7         | 1.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 1.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 1.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 6         | 1.52%   |
| Intel Wireless 8265 / 8275                                        | 6         | 1.52%   |
| Intel Wireless 7265                                               | 6         | 1.52%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 1.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 1.52%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 6         | 1.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 5         | 1.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5         | 1.27%   |
| Intel Wireless 7260                                               | 5         | 1.27%   |
| Broadcom BCM43224 802.11a/b/g/n                                   | 5         | 1.27%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.01%   |
| Realtek RTL8125 2.5GbE Controller                                 | 4         | 1.01%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 1.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 4         | 1.01%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 4         | 1.01%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 0.76%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.76%   |
| Intel Wireless-AC 9260                                            | 3         | 0.76%   |
| Intel Wireless 3165                                               | 3         | 0.76%   |
| Intel I211 Gigabit Network Connection                             | 3         | 0.76%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.76%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 3         | 0.76%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 3         | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 3         | 0.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 3         | 0.76%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                       | 3         | 0.76%   |
| Broadcom BCM4321 802.11a/b/g/n                                    | 3         | 0.76%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.51%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.51%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.51%   |
| Realtek 802.11ac NIC                                              | 2         | 0.51%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.51%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 2         | 0.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 2         | 0.51%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 2         | 0.51%   |
| Intel Wireless 3160                                               | 2         | 0.51%   |
| Intel Gemini Lake PCH CNVi WiFi                                   | 2         | 0.51%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.51%   |
| Intel Ethernet Connection I219-LM                                 | 2         | 0.51%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.51%   |
| Intel Ethernet Connection (4) I219-V                              | 2         | 0.51%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.51%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.51%   |
| Intel Centrino Advanced-N 6235                                    | 2         | 0.51%   |
| Intel 82579V Gigabit Network Connection                           | 2         | 0.51%   |
| Google Nexus/Pixel Device (tether)                                | 2         | 0.51%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.51%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 2         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 85        | 41.67%  |
| Broadcom                 | 34        | 16.67%  |
| Realtek Semiconductor    | 31        | 15.2%   |
| Qualcomm Atheros         | 27        | 13.24%  |
| Broadcom Limited         | 6         | 2.94%   |
| TP-Link                  | 4         | 1.96%   |
| Ralink Technology        | 4         | 1.96%   |
| Ralink                   | 3         | 1.47%   |
| Marvell Technology Group | 2         | 0.98%   |
| Sitecom Europe           | 1         | 0.49%   |
| Sierra Wireless          | 1         | 0.49%   |
| Microsoft                | 1         | 0.49%   |
| MEDIATEK                 | 1         | 0.49%   |
| Linksys                  | 1         | 0.49%   |
| LG Electronics           | 1         | 0.49%   |
| D-Link System            | 1         | 0.49%   |
| AVM                      | 1         | 0.49%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 11        | 5.37%   |
| Intel Wireless 8260                                            | 9         | 4.39%   |
| Intel Wi-Fi 6 AX201                                            | 8         | 3.9%    |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 8         | 3.9%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 7         | 3.41%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 7         | 3.41%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 6         | 2.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 6         | 2.93%   |
| Intel Wireless 8265 / 8275                                     | 6         | 2.93%   |
| Intel Wireless 7265                                            | 6         | 2.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 2.93%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 6         | 2.93%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 5         | 2.44%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 5         | 2.44%   |
| Intel Wireless 7260                                            | 5         | 2.44%   |
| Broadcom BCM43224 802.11a/b/g/n                                | 5         | 2.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.95%   |
| Ralink MT7601U Wireless Adapter                                | 4         | 1.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 4         | 1.95%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 4         | 1.95%   |
| Intel Wireless-AC 9260                                         | 3         | 1.46%   |
| Intel Wireless 3165                                            | 3         | 1.46%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 3         | 1.46%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 3         | 1.46%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 1.46%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 3         | 1.46%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 3         | 1.46%   |
| Broadcom BCM4321 802.11a/b/g/n                                 | 3         | 1.46%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.98%   |
| Realtek 802.11ac NIC                                           | 2         | 0.98%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 2         | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 2         | 0.98%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 2         | 0.98%   |
| Intel Wireless 3160                                            | 2         | 0.98%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 2         | 0.98%   |
| Intel Centrino Advanced-N 6235                                 | 2         | 0.98%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 2         | 0.98%   |
| Broadcom BCM43227 802.11b/g/n                                  | 2         | 0.98%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 0.98%   |
| TP-Link Archer T4U ver.3                                       | 1         | 0.49%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.49%   |
| TP-Link 802.11n NIC                                            | 1         | 0.49%   |
| TP-Link 802.11ac NIC                                           | 1         | 0.49%   |
| Sitecom Europe WL-329 Wireless Dualband USB adapter 300N       | 1         | 0.49%   |
| Sierra Wireless EM7455 QualcommÂ Snapdragonâ¢ X7 LTE-A    | 1         | 0.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 0.49%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 1         | 0.49%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 1         | 0.49%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.49%   |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 1         | 0.49%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 1         | 0.49%   |
| Realtek RTL8191SEvA Wireless LAN Controller                    | 1         | 0.49%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 1         | 0.49%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 0.49%   |
| Realtek RTL8187 Wireless Adapter                               | 1         | 0.49%   |
| Realtek Realtek Network controller                             | 1         | 0.49%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 0.49%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 1         | 0.49%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 1         | 0.49%   |
| Microsoft Xbox 360 Wireless Adapter                            | 1         | 0.49%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 106       | 56.08%  |
| Intel                    | 40        | 21.16%  |
| Broadcom                 | 11        | 5.82%   |
| Nvidia                   | 9         | 4.76%   |
| Qualcomm Atheros         | 7         | 3.7%    |
| Samsung Electronics      | 3         | 1.59%   |
| Marvell Technology Group | 3         | 1.59%   |
| Xiaomi                   | 2         | 1.06%   |
| Google                   | 2         | 1.06%   |
| OPPO Electronics         | 1         | 0.53%   |
| Motorola PCS             | 1         | 0.53%   |
| Hewlett-Packard          | 1         | 0.53%   |
| Broadcom Limited         | 1         | 0.53%   |
| ASIX Electronics         | 1         | 0.53%   |
| Apple                    | 1         | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 81        | 42.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 17        | 8.95%   |
| Nvidia MCP79 Ethernet                                                          | 9         | 4.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7         | 3.68%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 6         | 3.16%   |
| Realtek RTL8125 2.5GbE Controller                                              | 4         | 2.11%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 3         | 1.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 1.58%   |
| Intel I211 Gigabit Network Connection                                          | 3         | 1.58%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 1.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 2         | 1.05%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2         | 1.05%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 2         | 1.05%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller                        | 2         | 1.05%   |
| Intel Ethernet Controller I225-V                                               | 2         | 1.05%   |
| Intel Ethernet Connection I219-LM                                              | 2         | 1.05%   |
| Intel Ethernet Connection I217-LM                                              | 2         | 1.05%   |
| Intel Ethernet Connection (4) I219-V                                           | 2         | 1.05%   |
| Intel Ethernet Connection (3) I218-LM                                          | 2         | 1.05%   |
| Intel Ethernet Connection (2) I219-LM                                          | 2         | 1.05%   |
| Intel 82579V Gigabit Network Connection                                        | 2         | 1.05%   |
| Google Nexus/Pixel Device (tether)                                             | 2         | 1.05%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                            | 2         | 1.05%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1         | 0.53%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 1         | 0.53%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 1         | 0.53%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.53%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.53%   |
| OPPO SM6115-QRD _SN:D6BC0450                                                   | 1         | 0.53%   |
| Motorola PCS motorola edge                                                     | 1         | 0.53%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.53%   |
| Intel I210 Gigabit Network Connection                                          | 1         | 0.53%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.53%   |
| Intel Ethernet Connection I218-LM                                              | 1         | 0.53%   |
| Intel Ethernet Connection I217-V                                               | 1         | 0.53%   |
| Intel Ethernet Connection (7) I219-V                                           | 1         | 0.53%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.53%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.53%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1         | 0.53%   |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.53%   |
| Intel Ethernet Connection (10) I219-V                                          | 1         | 0.53%   |
| Intel 82577LM Gigabit Network Connection                                       | 1         | 0.53%   |
| Intel 82574L Gigabit Network Connection                                        | 1         | 0.53%   |
| Intel 80003ES2LAN Gigabit Ethernet Controller (Copper)                         | 1         | 0.53%   |
| HP HP lt4120 Snapdragon X5 LTE                                                 | 1         | 0.53%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                              | 1         | 0.53%   |
| Broadcom NetXtreme BCM5761e Gigabit Ethernet PCIe                              | 1         | 0.53%   |
| Broadcom NetXtreme BCM5719 Gigabit Ethernet PCIe                               | 1         | 0.53%   |
| Broadcom Limited NetXtreme BCM5761e Gigabit Ethernet PCIe                      | 1         | 0.53%   |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.53%   |
| Apple T2 Controller                                                            | 1         | 0.53%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 196       | 52.55%  |
| Ethernet | 177       | 47.45%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 186       | 52.25%  |
| Ethernet | 170       | 47.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 122       | 52.81%  |
| 1     | 100       | 43.29%  |
| 3     | 5         | 2.16%   |
| 0     | 3         | 1.3%    |
| 4     | 1         | 0.43%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 158       | 67.81%  |
| Yes  | 75        | 32.19%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 80        | 44.69%  |
| Apple                           | 29        | 16.2%   |
| Realtek Semiconductor           | 20        | 11.17%  |
| Cambridge Silicon Radio         | 10        | 5.59%   |
| Qualcomm Atheros Communications | 9         | 5.03%   |
| IMC Networks                    | 7         | 3.91%   |
| Lite-On Technology              | 6         | 3.35%   |
| Foxconn / Hon Hai               | 5         | 2.79%   |
| Broadcom                        | 4         | 2.23%   |
| Marvell Semiconductor           | 2         | 1.12%   |
| Hewlett-Packard                 | 2         | 1.12%   |
| Toshiba                         | 1         | 0.56%   |
| Realtek                         | 1         | 0.56%   |
| Ralink                          | 1         | 0.56%   |
| Qualcomm Atheros                | 1         | 0.56%   |
| ASUSTek Computer                | 1         | 0.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth Device                                                              | 31        | 17.32%  |
| Intel Bluetooth wireless interface                                                  | 19        | 10.61%  |
| Realtek Bluetooth Radio                                                             | 14        | 7.82%   |
| Apple Bluetooth Host Controller                                                     | 13        | 7.26%   |
| Intel AX201 Bluetooth                                                               | 12        | 6.7%    |
| Intel AX200 Bluetooth                                                               | 10        | 5.59%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 10        | 5.59%   |
| Apple Bluetooth USB Host Controller                                                 | 8         | 4.47%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 5         | 2.79%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 4         | 2.23%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 4         | 2.23%   |
| Apple Bluetooth HCI                                                                 | 4         | 2.23%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 1.68%   |
| Lite-On Bluetooth Device                                                            | 3         | 1.68%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 1.68%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 1.68%   |
| IMC Networks Bluetooth Device                                                       | 3         | 1.68%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 2         | 1.12%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.12%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 2         | 1.12%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 2         | 1.12%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.56%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.56%   |
| Realtek RTL8723B Bluetooth                                                          | 1         | 0.56%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.56%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.56%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 1         | 0.56%   |
| Marvell Bluetooth and Wireless LAN Composite Device                                 | 1         | 0.56%   |
| Marvell Bluetooth and Wireless LAN Composite                                        | 1         | 0.56%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 1         | 0.56%   |
| Lite-On Atheros Bluetooth                                                           | 1         | 0.56%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.56%   |
| IMC Networks Wireless_Device                                                        | 1         | 0.56%   |
| IMC Networks Bluetooth Radio                                                        | 1         | 0.56%   |
| IMC Networks BCM20702A0                                                             | 1         | 0.56%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 0.56%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.56%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.56%   |
| Foxconn / Hon Hai Acer Module                                                       | 1         | 0.56%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 1         | 0.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 1         | 0.56%   |
| ASUS BCM20702A0                                                                     | 1         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Intel                   | 168       | 56.38%  |
| AMD                     | 62        | 20.81%  |
| Nvidia                  | 45        | 15.1%   |
| C-Media Electronics     | 6         | 2.01%   |
| Creative Labs           | 4         | 1.34%   |
| Logitech                | 3         | 1.01%   |
| Texas Instruments       | 1         | 0.34%   |
| Realtek Semiconductor   | 1         | 0.34%   |
| Razer USA               | 1         | 0.34%   |
| No brand                | 1         | 0.34%   |
| GN Netcom               | 1         | 0.34%   |
| Focusrite-Novation      | 1         | 0.34%   |
| ESS Technology          | 1         | 0.34%   |
| Corsair                 | 1         | 0.34%   |
| BEHRINGER International | 1         | 0.34%   |
| Apple                   | 1         | 0.34%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                                            | 23        | 6.37%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 20        | 5.54%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 19        | 5.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 17        | 4.71%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 3.88%   |
| Intel Cannon Lake PCH cAVS                                                                        | 11        | 3.05%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 10        | 2.77%   |
| Nvidia MCP79 High Definition Audio                                                                | 9         | 2.49%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 9         | 2.49%   |
| Intel Broadwell-U Audio Controller                                                                | 9         | 2.49%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 9         | 2.49%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 8         | 2.22%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 8         | 2.22%   |
| Intel 8 Series HD Audio Controller                                                                | 8         | 2.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 8         | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 7         | 1.94%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 7         | 1.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 7         | 1.94%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 6         | 1.66%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.39%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 1.39%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.39%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                                                 | 5         | 1.39%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 5         | 1.39%   |
| AMD FCH Azalia Controller                                                                         | 5         | 1.39%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 4         | 1.11%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 4         | 1.11%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.11%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 4         | 1.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 4         | 1.11%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 1.11%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 4         | 1.11%   |
| AMD Kabini HDMI/DP Audio                                                                          | 4         | 1.11%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 1.11%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 3         | 0.83%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 0.83%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 3         | 0.83%   |
| Intel CM238 HD Audio Controller                                                                   | 3         | 0.83%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.83%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 3         | 0.83%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 0.83%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 3         | 0.83%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 3         | 0.83%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 0.55%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 2         | 0.55%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.55%   |
| AMD Navi 10 HDMI Audio                                                                            | 2         | 0.55%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 2         | 0.55%   |
| AMD High Definition Audio Controller                                                              | 2         | 0.55%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 0.55%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 0.55%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.28%   |
| Realtek Semiconductor USB Audio                                                                   | 1         | 0.28%   |
| Razer USA RC30-026902, Gaming Headset [Nari Essential, Wireless, Receiver]                        | 1         | 0.28%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 1         | 0.28%   |
| Nvidia MCP89 High Definition Audio                                                                | 1         | 0.28%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 1         | 0.28%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.28%   |
| Nvidia GP102 HDMI Audio Controller                                                                | 1         | 0.28%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 1         | 0.28%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 16        | 32.65%  |
| SK Hynix            | 7         | 14.29%  |
| Micron Technology   | 7         | 14.29%  |
| Unknown             | 4         | 8.16%   |
| Kingston            | 2         | 4.08%   |
| G.Skill             | 2         | 4.08%   |
| Corsair             | 2         | 4.08%   |
| Unknown (ABCD)      | 1         | 2.04%   |
| SHARETRONIC         | 1         | 2.04%   |
| Ramaxel Technology  | 1         | 2.04%   |
| PNY                 | 1         | 2.04%   |
| Patriot             | 1         | 2.04%   |
| Hewlett-Packard     | 1         | 2.04%   |
| GSkill              | 1         | 2.04%   |
| Crucial             | 1         | 2.04%   |
| A-DATA Technology   | 1         | 2.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 3.77%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 3.77%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 3.77%   |
| Unknown RAM Module 8192MB SODIMM DDR3                            | 1         | 1.89%   |
| Unknown RAM Module 8192MB DIMM DDR3 1066MT/s                     | 1         | 1.89%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 1.89%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1333MT/s                   | 1         | 1.89%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.89%   |
| SK Hynix RAM Module 8192MB SODIMM DDR3 1600MT/s                  | 1         | 1.89%   |
| SK Hynix RAM Module 4096MB SODIMM LPDDR3 1867MT/s                | 1         | 1.89%   |
| SK Hynix RAM Module 4096MB SODIMM DDR3 1600MT/s                  | 1         | 1.89%   |
| SK Hynix RAM HMT851S6AMR6R-PB 4GB Chip DDR3 1600MT/s             | 1         | 1.89%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 1.89%   |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.89%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.89%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 1.89%   |
| SHARETRONIC RAM Module 8192MB SODIMM DDR3 1600MT/s               | 1         | 1.89%   |
| Samsung RAM Module 8192MB DIMM DDR4 2666MT/s                     | 1         | 1.89%   |
| Samsung RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 1.89%   |
| Samsung RAM M471B5673FH0-CH9 2048MB SODIMM DDR3 1334MT/s         | 1         | 1.89%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.89%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.89%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s         | 1         | 1.89%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.89%   |
| Samsung RAM M471A1K43CB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 1         | 1.89%   |
| Samsung RAM M471A1K43BB0-CPB 8192MB SODIMM DDR4 2133MT/s         | 1         | 1.89%   |
| Samsung RAM K4EBE304ED-EGCG 8192MB Row Of Chips LPDDR3 2133MT/s  | 1         | 1.89%   |
| Samsung RAM K3QF4F40BM-AGCF 4096MB Row Of Chips LPDDR3 1867MT/s  | 1         | 1.89%   |
| Ramaxel RAM RMUA5090KB78HAF2133 8192MB DIMM DDR4 2133MT/s        | 1         | 1.89%   |
| PNY RAM 8GBF1X08QFHH38-135-K 8192MB DIMM DDR4 3200MT/s           | 1         | 1.89%   |
| Patriot RAM 3200 C16 Series 8GB DIMM DDR4 3200MT/s               | 1         | 1.89%   |
| Micron RAM MT40A1G16KD-062E:E 8192MB SODIMM DDR4 2667MT/s        | 1         | 1.89%   |
| Micron RAM Module 2048MB SODIMM DDR3 1600MT/s                    | 1         | 1.89%   |
| Micron RAM 8KTF51264HZ-1G6N1 4GB SODIMM DDR3 1600MT/s            | 1         | 1.89%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 1         | 1.89%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 1.89%   |
| Micron RAM 53E2G32D4NQ-046 4GB Row Of Chips LPDDR4 4267MT/s      | 1         | 1.89%   |
| Micron RAM 53E1G32D4NQ 2048MB Row Of Chips LPDDR4 4267MT/s       | 1         | 1.89%   |
| Micron RAM 4ATF51264HZ-2G3AZ 4096MB SODIMM DDR4 2133MT/s         | 1         | 1.89%   |
| Kingston RAM 9905625-030.A00G 8192MB DIMM DDR4 2133MT/s          | 1         | 1.89%   |
| Kingston RAM 9905471-015.A00LF 4096MB DIMM DDR3 1333MT/s         | 1         | 1.89%   |
| HP RAM 647650-071 8192MB DIMM DDR3 1333MT/s                      | 1         | 1.89%   |
| GSkill RAM F4-3200C22-8GRS 8192MB SODIMM DDR4 3200MT/s           | 1         | 1.89%   |
| G.Skill RAM F4-2666C18-16GRS 16GB SODIMM DDR4 2667MT/s           | 1         | 1.89%   |
| G.Skill RAM F3-1600C11-8GSQ 8192MB SODIMM DDR3 1600MT/s          | 1         | 1.89%   |
| G.Skill RAM F3-1600C11-8GSL 8192MB SODIMM DDR3 1600MT/s          | 1         | 1.89%   |
| Crucial RAM CB8GS2400.C8D 8192MB SODIMM DDR4 2400MT/s            | 1         | 1.89%   |
| Corsair RAM CMX8GX3M1A1600C11 8192MB DIMM DDR3 1600MT/s          | 1         | 1.89%   |
| Corsair RAM CMK8GX4M1A2400C16 8GB DIMM DDR4 2800MT/s             | 1         | 1.89%   |
| A-DATA RAM AM1U16BC4P2-B19N 4096MB SODIMM DDR3 1600MT/s          | 1         | 1.89%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Computers | Percent |
|--------|-----------|---------|
| DDR4   | 22        | 47.83%  |
| DDR3   | 18        | 39.13%  |
| LPDDR4 | 3         | 6.52%   |
| LPDDR3 | 3         | 6.52%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 32        | 69.57%  |
| DIMM         | 9         | 19.57%  |
| Row Of Chips | 4         | 8.7%    |
| Chip         | 1         | 2.17%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 24        | 48.98%  |
| 4096  | 16        | 32.65%  |
| 16384 | 4         | 8.16%   |
| 2048  | 4         | 8.16%   |
| 32768 | 1         | 2.04%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 12        | 25.53%  |
| 3200    | 8         | 17.02%  |
| 2667    | 8         | 17.02%  |
| 2133    | 4         | 8.51%   |
| 1333    | 3         | 6.38%   |
| 4267    | 2         | 4.26%   |
| 2400    | 2         | 4.26%   |
| 1867    | 2         | 4.26%   |
| 3266    | 1         | 2.13%   |
| 2800    | 1         | 2.13%   |
| 2666    | 1         | 2.13%   |
| 1334    | 1         | 2.13%   |
| 1066    | 1         | 2.13%   |
| Unknown | 1         | 2.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 2         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                     | Computers | Percent |
|---------------------------|-----------|---------|
| Canon PIXMA MG3600 Series | 1         | 50%     |
| Canon PIXMA MG2500 Series | 1         | 50%     |

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
| Chicony Electronics                    | 31        | 18.67%  |
| Apple                                  | 24        | 14.46%  |
| IMC Networks                           | 23        | 13.86%  |
| Realtek Semiconductor                  | 13        | 7.83%   |
| Acer                                   | 13        | 7.83%   |
| Microdia                               | 11        | 6.63%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 5.42%   |
| Quanta                                 | 7         | 4.22%   |
| Suyin                                  | 6         | 3.61%   |
| Alcor Micro                            | 4         | 2.41%   |
| Sunplus Innovation Technology          | 3         | 1.81%   |
| Silicon Motion                         | 3         | 1.81%   |
| Microsoft                              | 3         | 1.81%   |
| Logitech                               | 3         | 1.81%   |
| Syntek                                 | 2         | 1.2%    |
| Luxvisions Innotech Limited            | 2         | 1.2%    |
| Y Media                                | 1         | 0.6%    |
| Sony                                   | 1         | 0.6%    |
| Ricoh                                  | 1         | 0.6%    |
| Lite-On Technology                     | 1         | 0.6%    |
| kingcome                               | 1         | 0.6%    |
| Google                                 | 1         | 0.6%    |
| Generalplus Technology                 | 1         | 0.6%    |
| Foxconn / Hon Hai                      | 1         | 0.6%    |
| ANYKA                                  | 1         | 0.6%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Apple Built-in iSight                                                    | 11        | 6.47%   |
| IMC Networks Integrated Camera                                           | 8         | 4.71%   |
| IMC Networks USB2.0 HD UVC WebCam                                        | 6         | 3.53%   |
| Chicony Integrated Camera                                                | 6         | 3.53%   |
| Chicony HD WebCam                                                        | 6         | 3.53%   |
| Microdia Integrated_Webcam_HD                                            | 5         | 2.94%   |
| Apple FaceTime HD Camera                                                 | 5         | 2.94%   |
| Realtek Integrated_Webcam_HD                                             | 4         | 2.35%   |
| Apple iPhone 5/5C/5S/6/SE                                                | 4         | 2.35%   |
| Acer Lenovo EasyCamera                                                   | 4         | 2.35%   |
| Realtek USB2.0 VGA UVC WebCam                                            | 3         | 1.76%   |
| IMC Networks USB2.0 VGA UVC WebCam                                       | 3         | 1.76%   |
| Chicony USB 2.0 Camera                                                   | 3         | 1.76%   |
| Syntek Integrated Camera                                                 | 2         | 1.18%   |
| Realtek USB2.0 HD UVC WebCam                                             | 2         | 1.18%   |
| Realtek USB Camera                                                       | 2         | 1.18%   |
| Quanta VGA WebCam                                                        | 2         | 1.18%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 2         | 1.18%   |
| IMC Networks USB2.0 UVC HD Webcam                                        | 2         | 1.18%   |
| IMC Networks EasyCamera                                                  | 2         | 1.18%   |
| Chicony USB2.0 VGA UVC WebCam                                            | 2         | 1.18%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 2         | 1.18%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera                         | 2         | 1.18%   |
| Apple FaceTime HD Camera (Built-in)                                      | 2         | 1.18%   |
| Apple FaceTime Camera                                                    | 2         | 1.18%   |
| Alcor Micro Acer Integrated Webcam                                       | 2         | 1.18%   |
| Acer Integrated Camera                                                   | 2         | 1.18%   |
| Acer HD Webcam                                                           | 2         | 1.18%   |
| Acer EasyCamera                                                          | 2         | 1.18%   |
| Y Media USB Camera                                                       | 1         | 0.59%   |
| Suyin UVC HD Webcam                                                      | 1         | 0.59%   |
| Suyin USB 2.0 Camera                                                     | 1         | 0.59%   |
| Suyin Integrated_Webcam_HD                                               | 1         | 0.59%   |
| Suyin HP Integrated Webcam                                               | 1         | 0.59%   |
| Suyin HD WebCam                                                          | 1         | 0.59%   |
| Suyin 1.3M HD WebCam                                                     | 1         | 0.59%   |
| Sunplus Integrated_Webcam_HD                                             | 1         | 0.59%   |
| Sunplus HP Universal Camera                                              | 1         | 0.59%   |
| Sunplus HP HD Webcam [Fixed]                                             | 1         | 0.59%   |
| Sony CEVCECM                                                             | 1         | 0.59%   |
| Silicon Motion Webcam SC-13HDL11624N [Namuga Co., Ltd.]                  | 1         | 0.59%   |
| Silicon Motion WebCam SC-10HDP12631N                                     | 1         | 0.59%   |
| Silicon Motion ATIV VGA Camera                                           | 1         | 0.59%   |
| Ricoh Dell Laptop Integrated Webcam                                      | 1         | 0.59%   |
| Realtek Integrated Webcam                                                | 1         | 0.59%   |
| Realtek HP Wide Vision HD Camera                                         | 1         | 0.59%   |
| Quanta USB2.0 HD UVC WebCam                                              | 1         | 0.59%   |
| Quanta HP Webcam                                                         | 1         | 0.59%   |
| Quanta HP TrueVision HD Camera                                           | 1         | 0.59%   |
| Quanta hm1091_techfront                                                  | 1         | 0.59%   |
| Quanta HD User Facing                                                    | 1         | 0.59%   |
| Microsoft Rear LifeCam                                                   | 1         | 0.59%   |
| Microsoft LifeCam VX-800                                                 | 1         | 0.59%   |
| Microsoft LifeCam HD-3000                                                | 1         | 0.59%   |
| Microsoft Front LifeCam                                                  | 1         | 0.59%   |
| Microdia Webcam Vitade AF                                                | 1         | 0.59%   |
| Microdia USB 2.0 Camera                                                  | 1         | 0.59%   |
| Microdia Sonix USB 2.0 Camera                                            | 1         | 0.59%   |
| Microdia Sonix 1.3 MP Laptop Integrated Webcam                           | 1         | 0.59%   |
| Microdia OV5648                                                          | 1         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 8         | 34.78%  |
| Validity Sensors           | 7         | 30.43%  |
| LighTuning Technology      | 5         | 21.74%  |
| Shenzhen Goodix Technology | 2         | 8.7%    |
| Elan Microelectronics      | 1         | 4.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader         | 3         | 13.04%  |
| LighTuning EgisTec Touch Fingerprint Sensor               | 3         | 13.04%  |
| Validity Sensors VFS495 Fingerprint Reader                | 2         | 8.7%    |
| Validity Sensors VFS 5011 fingerprint sensor              | 2         | 8.7%    |
| Synaptics Metallica MIS Touch Fingerprint Reader          | 2         | 8.7%    |
| Shenzhen Goodix  Fingerprint Device                       | 2         | 8.7%    |
| LighTuning ES603 Swipe Fingerprint Sensor                 | 2         | 8.7%    |
| Validity Sensors VFS5011 Fingerprint Reader               | 1         | 4.35%   |
| Validity Sensors VFS491                                   | 1         | 4.35%   |
| Validity Sensors VFS471 Fingerprint Reader                | 1         | 4.35%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint | 1         | 4.35%   |
| Synaptics Metallica MOH Touch Fingerprint Reader          | 1         | 4.35%   |
| Elan ELAN:Fingerprint                                     | 1         | 4.35%   |
| Unknown                                                   | 1         | 4.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Broadcom            | 2         | 33.33%  |
| Alcor Micro         | 2         | 33.33%  |
| Lenovo              | 1         | 16.67%  |
| Chicony Electronics | 1         | 16.67%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                  | 2         | 33.33%  |
| Lenovo Integrated Smart Card Reader                  | 1         | 16.67%  |
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 1         | 16.67%  |
| Broadcom BCM5880 Secure Applications Processor       | 1         | 16.67%  |
| Broadcom 5880                                        | 1         | 16.67%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 182       | 78.45%  |
| 1     | 46        | 19.83%  |
| 2     | 4         | 1.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 23        | 41.82%  |
| Net/wireless          | 10        | 18.18%  |
| Multimedia controller | 10        | 18.18%  |
| Chipcard              | 5         | 9.09%   |
| Graphics card         | 3         | 5.45%   |
| Camera                | 3         | 5.45%   |
| Bluetooth             | 1         | 1.82%   |

