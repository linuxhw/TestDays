Zorin - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for Zorin.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin/Desktop/README.md) and [notebooks](/Dist/Zorin/Notebook/README.md).

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

Total: 6199

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | Latitude E5500              | Notebook    | [f04cd8f466](https://linux-hardware.org/?probe=f04cd8f466) | Dec 31, 2022 |
| Dell          | Latitude E5500              | Notebook    | [24a0ca1b65](https://linux-hardware.org/?probe=24a0ca1b65) | Dec 31, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [39c9c8aaea](https://linux-hardware.org/?probe=39c9c8aaea) | Dec 31, 2022 |
| Dell          | 0T10XW A00                  | Desktop     | [21638e1dfe](https://linux-hardware.org/?probe=21638e1dfe) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9220da7abb](https://linux-hardware.org/?probe=9220da7abb) | Dec 31, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [39f08657f8](https://linux-hardware.org/?probe=39f08657f8) | Dec 31, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [43f808e1e4](https://linux-hardware.org/?probe=43f808e1e4) | Dec 30, 2022 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [c8da48f03c](https://linux-hardware.org/?probe=c8da48f03c) | Dec 30, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [b8eccb0fbe](https://linux-hardware.org/?probe=b8eccb0fbe) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | Notebook    | [a2f6a6831a](https://linux-hardware.org/?probe=a2f6a6831a) | Dec 30, 2022 |
| Lenovo        | ThinkPad W541 20EF0011IX    | Notebook    | [3f5a2c6ea1](https://linux-hardware.org/?probe=3f5a2c6ea1) | Dec 30, 2022 |
| HOUTER        | IPMIP-GS                    | Desktop     | [6fddf7d035](https://linux-hardware.org/?probe=6fddf7d035) | Dec 30, 2022 |
| HP            | Pavilion dv6                | Notebook    | [12a8186204](https://linux-hardware.org/?probe=12a8186204) | Dec 30, 2022 |
| Biostar       | TA970                       | Desktop     | [6a55825894](https://linux-hardware.org/?probe=6a55825894) | Dec 30, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e0e5f33e60](https://linux-hardware.org/?probe=e0e5f33e60) | Dec 30, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [c841093094](https://linux-hardware.org/?probe=c841093094) | Dec 30, 2022 |
| MSI           | X99A RAIDER                 | Desktop     | [59f6170d5b](https://linux-hardware.org/?probe=59f6170d5b) | Dec 29, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [e4e5afd812](https://linux-hardware.org/?probe=e4e5afd812) | Dec 29, 2022 |
| ASUSTek       | X540YA                      | Notebook    | [d128cfee28](https://linux-hardware.org/?probe=d128cfee28) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [0d8d6061d7](https://linux-hardware.org/?probe=0d8d6061d7) | Dec 29, 2022 |
| ASUSTek       | P6T DELUXE V2               | Desktop     | [4bda137e99](https://linux-hardware.org/?probe=4bda137e99) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [7ce6d4b3e3](https://linux-hardware.org/?probe=7ce6d4b3e3) | Dec 29, 2022 |
| Dell          | 0KWVT8 A03                  | Desktop     | [f828f74e07](https://linux-hardware.org/?probe=f828f74e07) | Dec 29, 2022 |
| PCWare        | IPMH61R1                    | Desktop     | [a221946f02](https://linux-hardware.org/?probe=a221946f02) | Dec 29, 2022 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [cc1dd99957](https://linux-hardware.org/?probe=cc1dd99957) | Dec 28, 2022 |
| Dell          | 03KWTV A02                  | Desktop     | [82612358ac](https://linux-hardware.org/?probe=82612358ac) | Dec 28, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0c49efe5e1](https://linux-hardware.org/?probe=0c49efe5e1) | Dec 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [27e072cb3e](https://linux-hardware.org/?probe=27e072cb3e) | Dec 28, 2022 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [75fe6d9325](https://linux-hardware.org/?probe=75fe6d9325) | Dec 28, 2022 |
| HP            | 2AF7                        | Desktop     | [9663a281c1](https://linux-hardware.org/?probe=9663a281c1) | Dec 28, 2022 |
| Lenovo        | ThinkPad X131e 33672K5      | Notebook    | [70d10e91fb](https://linux-hardware.org/?probe=70d10e91fb) | Dec 28, 2022 |
| Toshiba       | Satellite C50-B             | Notebook    | [31241c1f30](https://linux-hardware.org/?probe=31241c1f30) | Dec 28, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [b65d5ce654](https://linux-hardware.org/?probe=b65d5ce654) | Dec 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [6aa557fb75](https://linux-hardware.org/?probe=6aa557fb75) | Dec 27, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [71c1ee486e](https://linux-hardware.org/?probe=71c1ee486e) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [2c6e8a0c9f](https://linux-hardware.org/?probe=2c6e8a0c9f) | Dec 27, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [b3db56361b](https://linux-hardware.org/?probe=b3db56361b) | Dec 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0763603d12](https://linux-hardware.org/?probe=0763603d12) | Dec 27, 2022 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Convertible | [2fe0a7fe8b](https://linux-hardware.org/?probe=2fe0a7fe8b) | Dec 27, 2022 |
| Acer          | Aspire XC-780               | Desktop     | [0d90d1884c](https://linux-hardware.org/?probe=0d90d1884c) | Dec 27, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [5ce1ea886f](https://linux-hardware.org/?probe=5ce1ea886f) | Dec 26, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | Notebook    | [052cdcd8bb](https://linux-hardware.org/?probe=052cdcd8bb) | Dec 26, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | Notebook    | [940218d084](https://linux-hardware.org/?probe=940218d084) | Dec 26, 2022 |
| Lenovo        | ThinkPad E590 20NB001AMX    | Notebook    | [047944fa9f](https://linux-hardware.org/?probe=047944fa9f) | Dec 26, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [f56ea263a2](https://linux-hardware.org/?probe=f56ea263a2) | Dec 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [da3f79863a](https://linux-hardware.org/?probe=da3f79863a) | Dec 26, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [047823ffbc](https://linux-hardware.org/?probe=047823ffbc) | Dec 26, 2022 |
| ASUSTek       | T100TAS                     | Notebook    | [25894bb300](https://linux-hardware.org/?probe=25894bb300) | Dec 26, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [1ba51900a6](https://linux-hardware.org/?probe=1ba51900a6) | Dec 25, 2022 |
| Acer          | Aspire M3-581G              | Notebook    | [67071376c6](https://linux-hardware.org/?probe=67071376c6) | Dec 25, 2022 |
| HP            | 2AF7                        | Desktop     | [287696b4fc](https://linux-hardware.org/?probe=287696b4fc) | Dec 25, 2022 |
| Gigabyte      | GA-770T-USB3                | Desktop     | [08d1b04754](https://linux-hardware.org/?probe=08d1b04754) | Dec 25, 2022 |
| Sony          | VGN-NR32M_S                 | Notebook    | [6ad0da2e88](https://linux-hardware.org/?probe=6ad0da2e88) | Dec 25, 2022 |
| ASRock        | 970 Extreme4                | Desktop     | [2655b3c6b6](https://linux-hardware.org/?probe=2655b3c6b6) | Dec 24, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [1c2f8d9457](https://linux-hardware.org/?probe=1c2f8d9457) | Dec 24, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [e968a4fe6d](https://linux-hardware.org/?probe=e968a4fe6d) | Dec 24, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [2415ad5980](https://linux-hardware.org/?probe=2415ad5980) | Dec 24, 2022 |
| HP            | Compaq 6730b (NB034ET#UU... | Notebook    | [304e2ca750](https://linux-hardware.org/?probe=304e2ca750) | Dec 24, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [9bcea5d857](https://linux-hardware.org/?probe=9bcea5d857) | Dec 24, 2022 |
| HP            | Pavilion dv7                | Notebook    | [a099e9b6ac](https://linux-hardware.org/?probe=a099e9b6ac) | Dec 24, 2022 |
| Intel         | H61                         | Desktop     | [8d5eb236e1](https://linux-hardware.org/?probe=8d5eb236e1) | Dec 24, 2022 |
| HP            | Pavilion g7                 | Notebook    | [ef4cc6fa1a](https://linux-hardware.org/?probe=ef4cc6fa1a) | Dec 24, 2022 |
| HP            | 2AF7                        | Desktop     | [7b79dd8352](https://linux-hardware.org/?probe=7b79dd8352) | Dec 23, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [3e8fb581f0](https://linux-hardware.org/?probe=3e8fb581f0) | Dec 23, 2022 |
| HP            | 2AF7                        | Desktop     | [5ef9ce3357](https://linux-hardware.org/?probe=5ef9ce3357) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | Desktop     | [08a8cc75ac](https://linux-hardware.org/?probe=08a8cc75ac) | Dec 23, 2022 |
| Dell          | 0C2KJT A00                  | Desktop     | [bd8a5003e8](https://linux-hardware.org/?probe=bd8a5003e8) | Dec 23, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [bb9724d53f](https://linux-hardware.org/?probe=bb9724d53f) | Dec 23, 2022 |
| Dell          | Latitude E4310              | Notebook    | [6386845196](https://linux-hardware.org/?probe=6386845196) | Dec 23, 2022 |
| ASRock        | G31M-S                      | Desktop     | [476c5ec563](https://linux-hardware.org/?probe=476c5ec563) | Dec 22, 2022 |
| Lenovo        | ThinkPad P52 20MAS25B1X     | Notebook    | [f82f15da88](https://linux-hardware.org/?probe=f82f15da88) | Dec 22, 2022 |
| MSI           | H61MU-E35                   | Desktop     | [cb9ec3d5ad](https://linux-hardware.org/?probe=cb9ec3d5ad) | Dec 22, 2022 |
| MSI           | H61MU-E35                   | Desktop     | [bfdc9d1e12](https://linux-hardware.org/?probe=bfdc9d1e12) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [f497db99b3](https://linux-hardware.org/?probe=f497db99b3) | Dec 22, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [79aabf81c4](https://linux-hardware.org/?probe=79aabf81c4) | Dec 22, 2022 |
| ECS           | H110M4-C2H                  | Desktop     | [f349ed8914](https://linux-hardware.org/?probe=f349ed8914) | Dec 22, 2022 |
| MSI           | B450M MORTAR                | Desktop     | [2279954594](https://linux-hardware.org/?probe=2279954594) | Dec 22, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [c0f831d7a4](https://linux-hardware.org/?probe=c0f831d7a4) | Dec 22, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [279e1eacf6](https://linux-hardware.org/?probe=279e1eacf6) | Dec 22, 2022 |
| ASRock        | G31M-S                      | Desktop     | [88d93da5a7](https://linux-hardware.org/?probe=88d93da5a7) | Dec 22, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [3caae1ba3b](https://linux-hardware.org/?probe=3caae1ba3b) | Dec 21, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [8d8716cdca](https://linux-hardware.org/?probe=8d8716cdca) | Dec 21, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [2e63730e46](https://linux-hardware.org/?probe=2e63730e46) | Dec 21, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [64cd4afc6d](https://linux-hardware.org/?probe=64cd4afc6d) | Dec 21, 2022 |
| PCWare        | IPMH310 PRO 1.0             | Desktop     | [c4dea5edbb](https://linux-hardware.org/?probe=c4dea5edbb) | Dec 21, 2022 |
| Sony          | VJZ13A                      | Notebook    | [748f77bace](https://linux-hardware.org/?probe=748f77bace) | Dec 21, 2022 |
| Dell          | Latitude E4310              | Notebook    | [7b184a032b](https://linux-hardware.org/?probe=7b184a032b) | Dec 21, 2022 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [06c3b647be](https://linux-hardware.org/?probe=06c3b647be) | Dec 21, 2022 |
| MSI           | GS73VR 7RF                  | Notebook    | [7f37920146](https://linux-hardware.org/?probe=7f37920146) | Dec 20, 2022 |
| HP            | 09CCh                       | Desktop     | [60d8cc87c7](https://linux-hardware.org/?probe=60d8cc87c7) | Dec 20, 2022 |
| Dell          | 0MGK50 A04                  | Desktop     | [931b01be38](https://linux-hardware.org/?probe=931b01be38) | Dec 20, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [5212fb0d93](https://linux-hardware.org/?probe=5212fb0d93) | Dec 20, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [9f456f73eb](https://linux-hardware.org/?probe=9f456f73eb) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [03e2c64868](https://linux-hardware.org/?probe=03e2c64868) | Dec 20, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [ca027f264a](https://linux-hardware.org/?probe=ca027f264a) | Dec 20, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [83df1364c8](https://linux-hardware.org/?probe=83df1364c8) | Dec 20, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [0e5b8434fe](https://linux-hardware.org/?probe=0e5b8434fe) | Dec 20, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [83a3d8e955](https://linux-hardware.org/?probe=83a3d8e955) | Dec 19, 2022 |
| MSI           | MS-1035                     | Notebook    | [6a8a6b7de4](https://linux-hardware.org/?probe=6a8a6b7de4) | Dec 19, 2022 |
| GPD           | G1619-04                    | Notebook    | [f184c297f2](https://linux-hardware.org/?probe=f184c297f2) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [3ec240466e](https://linux-hardware.org/?probe=3ec240466e) | Dec 19, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [87907abff7](https://linux-hardware.org/?probe=87907abff7) | Dec 19, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [08f3a88ab3](https://linux-hardware.org/?probe=08f3a88ab3) | Dec 19, 2022 |
| HP            | 8715                        | Mini pc     | [a6f7705fd4](https://linux-hardware.org/?probe=a6f7705fd4) | Dec 19, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [b1bd890ed0](https://linux-hardware.org/?probe=b1bd890ed0) | Dec 19, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [cf1ccbf76a](https://linux-hardware.org/?probe=cf1ccbf76a) | Dec 19, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | Desktop     | [0d5c4254b7](https://linux-hardware.org/?probe=0d5c4254b7) | Dec 19, 2022 |
| Dell          | Studio XPS 1645             | Notebook    | [e1c0f5a53b](https://linux-hardware.org/?probe=e1c0f5a53b) | Dec 18, 2022 |
| Dell          | Studio XPS 1645             | Notebook    | [2c26ce45b7](https://linux-hardware.org/?probe=2c26ce45b7) | Dec 18, 2022 |
| ASRock        | N3150-NUC                   | Desktop     | [5e77ec1117](https://linux-hardware.org/?probe=5e77ec1117) | Dec 18, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [20b69069fa](https://linux-hardware.org/?probe=20b69069fa) | Dec 18, 2022 |
| Dell          | Inspiron 7537               | Notebook    | [7064963568](https://linux-hardware.org/?probe=7064963568) | Dec 18, 2022 |
| ASUSTek       | S500CA                      | Notebook    | [55cf134a8b](https://linux-hardware.org/?probe=55cf134a8b) | Dec 18, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [d12b0d42fc](https://linux-hardware.org/?probe=d12b0d42fc) | Dec 17, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [1a23b502b9](https://linux-hardware.org/?probe=1a23b502b9) | Dec 17, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [e64e0ee27a](https://linux-hardware.org/?probe=e64e0ee27a) | Dec 17, 2022 |
| Fusion5       | C60Bv2-128GB                | Notebook    | [7cc701c4de](https://linux-hardware.org/?probe=7cc701c4de) | Dec 17, 2022 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [be98ae95c3](https://linux-hardware.org/?probe=be98ae95c3) | Dec 17, 2022 |
| ASRock        | N3150-NUC                   | Desktop     | [e497bf2ce3](https://linux-hardware.org/?probe=e497bf2ce3) | Dec 17, 2022 |
| HP            | Compaq 6910p (RM231UT#AB... | Notebook    | [4653b4877b](https://linux-hardware.org/?probe=4653b4877b) | Dec 17, 2022 |
| HP            | 250 G1                      | Notebook    | [07f20cc1ec](https://linux-hardware.org/?probe=07f20cc1ec) | Dec 17, 2022 |
| Jumper        | EZbook                      | Notebook    | [010f6841e5](https://linux-hardware.org/?probe=010f6841e5) | Dec 17, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [18d7dcfb19](https://linux-hardware.org/?probe=18d7dcfb19) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [2505ff8962](https://linux-hardware.org/?probe=2505ff8962) | Dec 17, 2022 |
| Sony          | VPCEB2M1E                   | Notebook    | [72bcddb15e](https://linux-hardware.org/?probe=72bcddb15e) | Dec 17, 2022 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [53ae51748b](https://linux-hardware.org/?probe=53ae51748b) | Dec 17, 2022 |
| Jumper        | EZbook                      | Notebook    | [bbae74f641](https://linux-hardware.org/?probe=bbae74f641) | Dec 17, 2022 |
| Apple         | Mac-F2268DC8                | All in one  | [396db83818](https://linux-hardware.org/?probe=396db83818) | Dec 17, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [dec0d049f7](https://linux-hardware.org/?probe=dec0d049f7) | Dec 17, 2022 |
| WYSE          | XM CLASS                    | Notebook    | [8aac2f31cb](https://linux-hardware.org/?probe=8aac2f31cb) | Dec 17, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [255499abee](https://linux-hardware.org/?probe=255499abee) | Dec 17, 2022 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [1a8c883ac5](https://linux-hardware.org/?probe=1a8c883ac5) | Dec 16, 2022 |
| Toshiba       | Satellite P500              | Notebook    | [58163fa1d7](https://linux-hardware.org/?probe=58163fa1d7) | Dec 16, 2022 |
| Fujitsu       | D2901-A1 S26361-D2901-A1    | Desktop     | [d9ee8a9854](https://linux-hardware.org/?probe=d9ee8a9854) | Dec 16, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [ced1979abf](https://linux-hardware.org/?probe=ced1979abf) | Dec 16, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [a0a0296ca4](https://linux-hardware.org/?probe=a0a0296ca4) | Dec 16, 2022 |
| Google        | Blorb                       | Notebook    | [4134deb94e](https://linux-hardware.org/?probe=4134deb94e) | Dec 16, 2022 |
| HP            | 8750                        | Desktop     | [a4911352d1](https://linux-hardware.org/?probe=a4911352d1) | Dec 16, 2022 |
| MSI           | GP75 Leopard 10SEK          | Notebook    | [9eda9896f3](https://linux-hardware.org/?probe=9eda9896f3) | Dec 15, 2022 |
| Machcreato... | 14                          | Notebook    | [8b69842953](https://linux-hardware.org/?probe=8b69842953) | Dec 15, 2022 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | Desktop     | [827fabbd5f](https://linux-hardware.org/?probe=827fabbd5f) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [eeb913fa7c](https://linux-hardware.org/?probe=eeb913fa7c) | Dec 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [7a72cfa484](https://linux-hardware.org/?probe=7a72cfa484) | Dec 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [06bbbb04a9](https://linux-hardware.org/?probe=06bbbb04a9) | Dec 15, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [34611b96d0](https://linux-hardware.org/?probe=34611b96d0) | Dec 15, 2022 |
| ASUSTek       | P5PL2-E                     | Desktop     | [d304b202fc](https://linux-hardware.org/?probe=d304b202fc) | Dec 14, 2022 |
| Lenovo        | ThinkPad T460 20FMS2AN00    | Notebook    | [7db77c4fcd](https://linux-hardware.org/?probe=7db77c4fcd) | Dec 14, 2022 |
| Lenovo        | ThinkPad Helix 2nd 20CG0... | Tablet      | [e32ae95f08](https://linux-hardware.org/?probe=e32ae95f08) | Dec 14, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [3339909881](https://linux-hardware.org/?probe=3339909881) | Dec 14, 2022 |
| MSI           | MS-B9071                    | Desktop     | [fc31fe11a2](https://linux-hardware.org/?probe=fc31fe11a2) | Dec 14, 2022 |
| HP            | Pavilion dv7                | Notebook    | [7067714e91](https://linux-hardware.org/?probe=7067714e91) | Dec 14, 2022 |
| Intel         | NUC10i5FNB M38063-307       | Mini pc     | [1e8031daad](https://linux-hardware.org/?probe=1e8031daad) | Dec 13, 2022 |
| Intel         | NUC10i5FNB M38063-307       | Mini pc     | [c8c56f3e93](https://linux-hardware.org/?probe=c8c56f3e93) | Dec 13, 2022 |
| HP            | 1905                        | Desktop     | [21f639657c](https://linux-hardware.org/?probe=21f639657c) | Dec 13, 2022 |
| AZW           | GTR V01                     | Mini pc     | [7cae9d407c](https://linux-hardware.org/?probe=7cae9d407c) | Dec 13, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [d4812cfdb6](https://linux-hardware.org/?probe=d4812cfdb6) | Dec 13, 2022 |
| Gigabyte      | H57M-USB3                   | Desktop     | [c48aaf8b29](https://linux-hardware.org/?probe=c48aaf8b29) | Dec 12, 2022 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [9704c6b7c4](https://linux-hardware.org/?probe=9704c6b7c4) | Dec 12, 2022 |
| Biostar       | A520MH                      | Desktop     | [e1eff55b96](https://linux-hardware.org/?probe=e1eff55b96) | Dec 12, 2022 |
| Foxconn       | H55MXV-LE                   | Desktop     | [931837aeec](https://linux-hardware.org/?probe=931837aeec) | Dec 12, 2022 |
| AZW           | GTR V01                     | Mini pc     | [9f1097843c](https://linux-hardware.org/?probe=9f1097843c) | Dec 12, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [d83f209b7f](https://linux-hardware.org/?probe=d83f209b7f) | Dec 12, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [09b233d518](https://linux-hardware.org/?probe=09b233d518) | Dec 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [4a5f657daf](https://linux-hardware.org/?probe=4a5f657daf) | Dec 12, 2022 |
| Apple         | MacBook4,1                  | Notebook    | [45ad14cbc2](https://linux-hardware.org/?probe=45ad14cbc2) | Dec 12, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [bc16110ca8](https://linux-hardware.org/?probe=bc16110ca8) | Dec 12, 2022 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [477bcdd546](https://linux-hardware.org/?probe=477bcdd546) | Dec 12, 2022 |
| Alienware     | 18                          | Notebook    | [707124d216](https://linux-hardware.org/?probe=707124d216) | Dec 11, 2022 |
| Biostar       | A520MH                      | Desktop     | [2c6278e478](https://linux-hardware.org/?probe=2c6278e478) | Dec 11, 2022 |
| Lenovo        | 30D2 SDK0J40705 WIN 3425... | Desktop     | [80281a1e7b](https://linux-hardware.org/?probe=80281a1e7b) | Dec 11, 2022 |
| Acer          | Aspire M3-581G              | Notebook    | [25b27d5b17](https://linux-hardware.org/?probe=25b27d5b17) | Dec 11, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [c2cb5ad16b](https://linux-hardware.org/?probe=c2cb5ad16b) | Dec 11, 2022 |
| ASUSTek       | X751SA                      | Notebook    | [2da53106a0](https://linux-hardware.org/?probe=2da53106a0) | Dec 11, 2022 |
| Sony          | VGN-NR32M_S                 | Notebook    | [f37234d095](https://linux-hardware.org/?probe=f37234d095) | Dec 10, 2022 |
| ASUSTek       | X751SA                      | Notebook    | [36b3666998](https://linux-hardware.org/?probe=36b3666998) | Dec 10, 2022 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [e2a043a361](https://linux-hardware.org/?probe=e2a043a361) | Dec 10, 2022 |
| Lenovo        | ThinkPad T470 20HES0PF00    | Notebook    | [097b783ae5](https://linux-hardware.org/?probe=097b783ae5) | Dec 10, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [9d7365bdd6](https://linux-hardware.org/?probe=9d7365bdd6) | Dec 10, 2022 |
| ASUSTek       | P5Q                         | Desktop     | [fbc5b65636](https://linux-hardware.org/?probe=fbc5b65636) | Dec 10, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [0f4312c32e](https://linux-hardware.org/?probe=0f4312c32e) | Dec 10, 2022 |
| Dell          | Latitude E7240              | Notebook    | [722c8c8b32](https://linux-hardware.org/?probe=722c8c8b32) | Dec 10, 2022 |
| ASUSTek       | M3N78-VM                    | Desktop     | [fa99389a1a](https://linux-hardware.org/?probe=fa99389a1a) | Dec 10, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [3e0d5dc490](https://linux-hardware.org/?probe=3e0d5dc490) | Dec 09, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [2dffa88142](https://linux-hardware.org/?probe=2dffa88142) | Dec 09, 2022 |
| ASUSTek       | P5Q                         | Desktop     | [415b325dd0](https://linux-hardware.org/?probe=415b325dd0) | Dec 09, 2022 |
| Hampoo        | P02BD6_HI-122LP             | Tablet      | [fbbd6a06c8](https://linux-hardware.org/?probe=fbbd6a06c8) | Dec 09, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [69e83bcd80](https://linux-hardware.org/?probe=69e83bcd80) | Dec 09, 2022 |
| MSI           | GS73VR 7RF                  | Notebook    | [31aa44b519](https://linux-hardware.org/?probe=31aa44b519) | Dec 09, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [3f3a7f6841](https://linux-hardware.org/?probe=3f3a7f6841) | Dec 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [41ff90c88a](https://linux-hardware.org/?probe=41ff90c88a) | Dec 09, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [30bbadcb93](https://linux-hardware.org/?probe=30bbadcb93) | Dec 09, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [3a1ec09d8a](https://linux-hardware.org/?probe=3a1ec09d8a) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [ead8cc9c0a](https://linux-hardware.org/?probe=ead8cc9c0a) | Dec 08, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [3258bb06ef](https://linux-hardware.org/?probe=3258bb06ef) | Dec 08, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [0db55b0eea](https://linux-hardware.org/?probe=0db55b0eea) | Dec 08, 2022 |
| HP            | 82FE 11                     | Desktop     | [6bf35b7005](https://linux-hardware.org/?probe=6bf35b7005) | Dec 08, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [54eaa6d2f3](https://linux-hardware.org/?probe=54eaa6d2f3) | Dec 07, 2022 |
| Dell          | Latitude 7490               | Notebook    | [6021de66f0](https://linux-hardware.org/?probe=6021de66f0) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [8c8e80423c](https://linux-hardware.org/?probe=8c8e80423c) | Dec 07, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [37283186c3](https://linux-hardware.org/?probe=37283186c3) | Dec 07, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [1c99985945](https://linux-hardware.org/?probe=1c99985945) | Dec 07, 2022 |
| Dell          | Studio 1558                 | Notebook    | [ce0c8ffe20](https://linux-hardware.org/?probe=ce0c8ffe20) | Dec 06, 2022 |
| MSI           | K9A2 Platinum               | Desktop     | [3ce727deb7](https://linux-hardware.org/?probe=3ce727deb7) | Dec 06, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [8442e3381c](https://linux-hardware.org/?probe=8442e3381c) | Dec 06, 2022 |
| Dell          | Latitude 7490               | Notebook    | [2b29482df2](https://linux-hardware.org/?probe=2b29482df2) | Dec 06, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [f8e7b50548](https://linux-hardware.org/?probe=f8e7b50548) | Dec 06, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [a4029fd324](https://linux-hardware.org/?probe=a4029fd324) | Dec 06, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [a28616ab1b](https://linux-hardware.org/?probe=a28616ab1b) | Dec 06, 2022 |
| Packard Be... | EasyNote TE11BZ             | Notebook    | [b243114de5](https://linux-hardware.org/?probe=b243114de5) | Dec 06, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [5132e1aba1](https://linux-hardware.org/?probe=5132e1aba1) | Dec 05, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [b500d948bf](https://linux-hardware.org/?probe=b500d948bf) | Dec 05, 2022 |
| Dell          | 0T10XW A00                  | Desktop     | [d6f876fa52](https://linux-hardware.org/?probe=d6f876fa52) | Dec 05, 2022 |
| HP            | 8350                        | Desktop     | [f7768016d5](https://linux-hardware.org/?probe=f7768016d5) | Dec 05, 2022 |
| IP3 Tech      | GB3                         | Mini pc     | [586b9fe0a6](https://linux-hardware.org/?probe=586b9fe0a6) | Dec 05, 2022 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [9775fe7147](https://linux-hardware.org/?probe=9775fe7147) | Dec 05, 2022 |
| HP            | Pavilion dv7                | Notebook    | [901e0c59ce](https://linux-hardware.org/?probe=901e0c59ce) | Dec 05, 2022 |
| HP            | Pavilion dv7                | Notebook    | [d02f343be8](https://linux-hardware.org/?probe=d02f343be8) | Dec 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [2ee93ad61d](https://linux-hardware.org/?probe=2ee93ad61d) | Dec 05, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [d5ba349e44](https://linux-hardware.org/?probe=d5ba349e44) | Dec 04, 2022 |
| Dell          | Latitude E6540              | Notebook    | [9a547affad](https://linux-hardware.org/?probe=9a547affad) | Dec 04, 2022 |
| Toshiba       | Satellite C870-1C2          | Notebook    | [0e270ccc80](https://linux-hardware.org/?probe=0e270ccc80) | Dec 04, 2022 |
| ASUSTek       | K53SD                       | Notebook    | [dbaf532969](https://linux-hardware.org/?probe=dbaf532969) | Dec 04, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [101ea9ca8e](https://linux-hardware.org/?probe=101ea9ca8e) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [8de52c0ea7](https://linux-hardware.org/?probe=8de52c0ea7) | Dec 04, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [888ec24e9d](https://linux-hardware.org/?probe=888ec24e9d) | Dec 04, 2022 |
| MACHINIST     | E5-MR9A PRO V1.0            | Desktop     | [67fa9fb5aa](https://linux-hardware.org/?probe=67fa9fb5aa) | Dec 03, 2022 |
| MSI           | K9A2 Platinum               | Desktop     | [79c823558a](https://linux-hardware.org/?probe=79c823558a) | Dec 03, 2022 |
| HP            | 2AE2                        | Desktop     | [549eacfc3d](https://linux-hardware.org/?probe=549eacfc3d) | Dec 03, 2022 |
| MSI           | B75A-G41                    | Desktop     | [cbf02bbd94](https://linux-hardware.org/?probe=cbf02bbd94) | Dec 03, 2022 |
| HP            | Pavilion dv7                | Notebook    | [c398cf4372](https://linux-hardware.org/?probe=c398cf4372) | Dec 03, 2022 |
| HP            | Pavilion dv7                | Notebook    | [e34ad54f3b](https://linux-hardware.org/?probe=e34ad54f3b) | Dec 03, 2022 |
| Dell          | Latitude 5490               | Notebook    | [e74106a982](https://linux-hardware.org/?probe=e74106a982) | Dec 03, 2022 |
| Dell          | Latitude 5490               | Notebook    | [26e6a987d0](https://linux-hardware.org/?probe=26e6a987d0) | Dec 03, 2022 |
| ASUSTek       | ET2400IN-1G                 | All in one  | [dba5f63d66](https://linux-hardware.org/?probe=dba5f63d66) | Dec 03, 2022 |
| HP            | Pavilion g4                 | Notebook    | [c6a564dce1](https://linux-hardware.org/?probe=c6a564dce1) | Dec 02, 2022 |
| Biostar       | TPower X58                  | Desktop     | [320769fceb](https://linux-hardware.org/?probe=320769fceb) | Dec 02, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [d42891d37b](https://linux-hardware.org/?probe=d42891d37b) | Dec 02, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [686afd3c20](https://linux-hardware.org/?probe=686afd3c20) | Dec 02, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [71b49e89e9](https://linux-hardware.org/?probe=71b49e89e9) | Dec 02, 2022 |
| AZW           | U59                         | Desktop     | [6a7c9cb905](https://linux-hardware.org/?probe=6a7c9cb905) | Dec 02, 2022 |
| Lenovo        | ThinkPad T420 4236GY3       | Notebook    | [63dd78fcec](https://linux-hardware.org/?probe=63dd78fcec) | Dec 02, 2022 |
| NZXT          | N7 Z590                     | Desktop     | [cc56e65209](https://linux-hardware.org/?probe=cc56e65209) | Dec 02, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [dfd11598ed](https://linux-hardware.org/?probe=dfd11598ed) | Dec 02, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [50c8de6edf](https://linux-hardware.org/?probe=50c8de6edf) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [c469225241](https://linux-hardware.org/?probe=c469225241) | Dec 01, 2022 |
| Acer          | Aspire V5-121               | Notebook    | [473cfb46f7](https://linux-hardware.org/?probe=473cfb46f7) | Dec 01, 2022 |
| MSI           | G41M-S03                    | Desktop     | [763decb5d5](https://linux-hardware.org/?probe=763decb5d5) | Dec 01, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [7f91a09589](https://linux-hardware.org/?probe=7f91a09589) | Dec 01, 2022 |
| Sony          | VPCEB1M1E                   | Notebook    | [988c78f70d](https://linux-hardware.org/?probe=988c78f70d) | Dec 01, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [f9020b8dc6](https://linux-hardware.org/?probe=f9020b8dc6) | Dec 01, 2022 |
| HP            | 8433 11                     | Desktop     | [01f9a28da3](https://linux-hardware.org/?probe=01f9a28da3) | Dec 01, 2022 |
| Acer          | Aspire C24-963              | All in one  | [ab421fd2d4](https://linux-hardware.org/?probe=ab421fd2d4) | Dec 01, 2022 |
| Acer          | Aspire C24-963              | All in one  | [4f517e816d](https://linux-hardware.org/?probe=4f517e816d) | Dec 01, 2022 |
| Dell          | Latitude E5520              | Notebook    | [92a4c9b5ef](https://linux-hardware.org/?probe=92a4c9b5ef) | Nov 30, 2022 |
| Dell          | Studio 1558                 | Notebook    | [cf40788ef8](https://linux-hardware.org/?probe=cf40788ef8) | Nov 30, 2022 |
| OEM           | H110 Ver:2.21               | Desktop     | [ad7fffd9e3](https://linux-hardware.org/?probe=ad7fffd9e3) | Nov 30, 2022 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [e214cb1bb9](https://linux-hardware.org/?probe=e214cb1bb9) | Nov 30, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [9d6aeff37c](https://linux-hardware.org/?probe=9d6aeff37c) | Nov 30, 2022 |
| MSI           | GE75 Raider 10SE            | Notebook    | [88245a0df3](https://linux-hardware.org/?probe=88245a0df3) | Nov 30, 2022 |
| OEM           | H110 Ver:2.21               | Desktop     | [2e7e420f42](https://linux-hardware.org/?probe=2e7e420f42) | Nov 29, 2022 |
| Dell          | Latitude E6540              | Notebook    | [48c805974c](https://linux-hardware.org/?probe=48c805974c) | Nov 29, 2022 |
| Gateway       | SX2851                      | Desktop     | [b408695def](https://linux-hardware.org/?probe=b408695def) | Nov 28, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [f4b2035429](https://linux-hardware.org/?probe=f4b2035429) | Nov 28, 2022 |
| HOUTER        | IPMIP-GS                    | Desktop     | [cbc472e6df](https://linux-hardware.org/?probe=cbc472e6df) | Nov 28, 2022 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [ab9b95babe](https://linux-hardware.org/?probe=ab9b95babe) | Nov 28, 2022 |
| Microsoft     | Surface Book 2              | Tablet      | [c4bbe90221](https://linux-hardware.org/?probe=c4bbe90221) | Nov 28, 2022 |
| Dell          | System XPS L502X            | Notebook    | [bd45da46bc](https://linux-hardware.org/?probe=bd45da46bc) | Nov 27, 2022 |
| Notebook      | NP5x_NP6x_NP7xPNP           | Notebook    | [3dd83d6d9d](https://linux-hardware.org/?probe=3dd83d6d9d) | Nov 27, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [47782768eb](https://linux-hardware.org/?probe=47782768eb) | Nov 27, 2022 |
| Dell          | Studio 1558                 | Notebook    | [bc76adb105](https://linux-hardware.org/?probe=bc76adb105) | Nov 27, 2022 |
| HP            | Pavilion g6                 | Notebook    | [17d324d115](https://linux-hardware.org/?probe=17d324d115) | Nov 27, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [eda49557ae](https://linux-hardware.org/?probe=eda49557ae) | Nov 27, 2022 |
| Lenovo        | B50-30 80ES                 | Notebook    | [ced4c1f563](https://linux-hardware.org/?probe=ced4c1f563) | Nov 27, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [6867d8eeaf](https://linux-hardware.org/?probe=6867d8eeaf) | Nov 27, 2022 |
| Dell          | Studio 1558                 | Notebook    | [43438ab851](https://linux-hardware.org/?probe=43438ab851) | Nov 27, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [07df50a08c](https://linux-hardware.org/?probe=07df50a08c) | Nov 27, 2022 |
| Panasonic     | CF-19AHN3BFF                | Notebook    | [a5989143a8](https://linux-hardware.org/?probe=a5989143a8) | Nov 26, 2022 |
| Megaware      | MW-NM70HD-MI 01/13/2013 ... | Desktop     | [95b48709fd](https://linux-hardware.org/?probe=95b48709fd) | Nov 26, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [c26e52327e](https://linux-hardware.org/?probe=c26e52327e) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [88db74df98](https://linux-hardware.org/?probe=88db74df98) | Nov 26, 2022 |
| Dell          | Latitude E6540              | Notebook    | [543ca1307c](https://linux-hardware.org/?probe=543ca1307c) | Nov 26, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [5b531b7b41](https://linux-hardware.org/?probe=5b531b7b41) | Nov 26, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [def104dd7d](https://linux-hardware.org/?probe=def104dd7d) | Nov 26, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [5e51349002](https://linux-hardware.org/?probe=5e51349002) | Nov 26, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [f70a6fa6ae](https://linux-hardware.org/?probe=f70a6fa6ae) | Nov 26, 2022 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [3ca25803b5](https://linux-hardware.org/?probe=3ca25803b5) | Nov 25, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [2eb5cc0a12](https://linux-hardware.org/?probe=2eb5cc0a12) | Nov 25, 2022 |
| Lenovo        | MIIX 2 11 20327             | Tablet      | [c0102f2633](https://linux-hardware.org/?probe=c0102f2633) | Nov 25, 2022 |
| ASUSTek       | X202E                       | Notebook    | [24a8811d77](https://linux-hardware.org/?probe=24a8811d77) | Nov 25, 2022 |
| ASUSTek       | X202E                       | Notebook    | [69a3fa54c1](https://linux-hardware.org/?probe=69a3fa54c1) | Nov 25, 2022 |
| Toshiba       | Satellite C50D-B            | Notebook    | [92d54fef2b](https://linux-hardware.org/?probe=92d54fef2b) | Nov 25, 2022 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | Notebook    | [1ed724b75e](https://linux-hardware.org/?probe=1ed724b75e) | Nov 25, 2022 |
| HP            | ENVY m6                     | Notebook    | [cb48bbdcc1](https://linux-hardware.org/?probe=cb48bbdcc1) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [dc9d24ac01](https://linux-hardware.org/?probe=dc9d24ac01) | Nov 25, 2022 |
| Pegatron      | 2ACF                        | Desktop     | [037b47ab43](https://linux-hardware.org/?probe=037b47ab43) | Nov 25, 2022 |
| HP            | 18E7                        | Desktop     | [048d4bd3ae](https://linux-hardware.org/?probe=048d4bd3ae) | Nov 25, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [2c7485441f](https://linux-hardware.org/?probe=2c7485441f) | Nov 25, 2022 |
| Panasonic     | CF-19AHN3BFF                | Notebook    | [bfd184ea5c](https://linux-hardware.org/?probe=bfd184ea5c) | Nov 25, 2022 |
| Dell          | 0T10XW A02                  | Desktop     | [83daa0cf15](https://linux-hardware.org/?probe=83daa0cf15) | Nov 25, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [c43b60c09b](https://linux-hardware.org/?probe=c43b60c09b) | Nov 25, 2022 |
| ASUSTek       | M5401WUA                    | All in one  | [e49d5c5f9d](https://linux-hardware.org/?probe=e49d5c5f9d) | Nov 24, 2022 |
| Gigabyte      | B560 DS3H AC-Y1             | Desktop     | [6bcefa911d](https://linux-hardware.org/?probe=6bcefa911d) | Nov 24, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [6cbdda4e27](https://linux-hardware.org/?probe=6cbdda4e27) | Nov 24, 2022 |
| Thomson       | GEN17V3C8WH256              | Notebook    | [7b1a510e2e](https://linux-hardware.org/?probe=7b1a510e2e) | Nov 24, 2022 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [07ac3ace2c](https://linux-hardware.org/?probe=07ac3ace2c) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [a1fad8227f](https://linux-hardware.org/?probe=a1fad8227f) | Nov 24, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [4a3e80efe5](https://linux-hardware.org/?probe=4a3e80efe5) | Nov 24, 2022 |
| ASRock        | FP6D4-P1                    | Desktop     | [5e52f1b520](https://linux-hardware.org/?probe=5e52f1b520) | Nov 24, 2022 |
| MSI           | Z490-A PRO                  | Desktop     | [9154fdbc9e](https://linux-hardware.org/?probe=9154fdbc9e) | Nov 24, 2022 |
| Toshiba       | Satellite S55t-B            | Notebook    | [4b01021314](https://linux-hardware.org/?probe=4b01021314) | Nov 24, 2022 |
| Lenovo        | ThinkCentre M91p 4524WAP    | Desktop     | [51f3e71650](https://linux-hardware.org/?probe=51f3e71650) | Nov 24, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [ac6ad8d54d](https://linux-hardware.org/?probe=ac6ad8d54d) | Nov 24, 2022 |
| HP            | Notebook                    | Notebook    | [d65b0a06fe](https://linux-hardware.org/?probe=d65b0a06fe) | Nov 24, 2022 |
| HP            | Notebook                    | Notebook    | [54b351457e](https://linux-hardware.org/?probe=54b351457e) | Nov 24, 2022 |
| Dell          | Inspiron 7586               | Convertible | [a41bb9177a](https://linux-hardware.org/?probe=a41bb9177a) | Nov 23, 2022 |
| HP            | 15                          | Notebook    | [6ce90bccf9](https://linux-hardware.org/?probe=6ce90bccf9) | Nov 23, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [5357d43f13](https://linux-hardware.org/?probe=5357d43f13) | Nov 23, 2022 |
| HP            | Laptop 14-bw0xx             | Notebook    | [5d4e847eef](https://linux-hardware.org/?probe=5d4e847eef) | Nov 23, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [9dbd34c7bd](https://linux-hardware.org/?probe=9dbd34c7bd) | Nov 23, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [5786af4776](https://linux-hardware.org/?probe=5786af4776) | Nov 23, 2022 |
| Intel         | D946GZAB AAD66610-302       | Desktop     | [5433ee5bc1](https://linux-hardware.org/?probe=5433ee5bc1) | Nov 22, 2022 |
| ASUSTek       | M5401WUA                    | All in one  | [7a2c8b647d](https://linux-hardware.org/?probe=7a2c8b647d) | Nov 22, 2022 |
| Lenovo        | IdeaPad U400 09932JU        | Notebook    | [cb5d9871d0](https://linux-hardware.org/?probe=cb5d9871d0) | Nov 22, 2022 |
| HP            | 8184 X4                     | Desktop     | [f38ad9d963](https://linux-hardware.org/?probe=f38ad9d963) | Nov 21, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [722165a975](https://linux-hardware.org/?probe=722165a975) | Nov 21, 2022 |
| HP            | 822A                        | Desktop     | [b464dc4cf0](https://linux-hardware.org/?probe=b464dc4cf0) | Nov 21, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [dfb9f9524e](https://linux-hardware.org/?probe=dfb9f9524e) | Nov 20, 2022 |
| Acer          | Veriton N4640G              | Desktop     | [a7984c4a95](https://linux-hardware.org/?probe=a7984c4a95) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [cd0f904ca4](https://linux-hardware.org/?probe=cd0f904ca4) | Nov 20, 2022 |
| Gigabyte      | Z68X-UD3H-B3                | Desktop     | [c4bd142690](https://linux-hardware.org/?probe=c4bd142690) | Nov 20, 2022 |
| Gigabyte      | GA-890GPA-UD3H              | Desktop     | [41cca3d850](https://linux-hardware.org/?probe=41cca3d850) | Nov 20, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [87f2179621](https://linux-hardware.org/?probe=87f2179621) | Nov 20, 2022 |
| Framework     | Laptop                      | Notebook    | [6cc495c0d9](https://linux-hardware.org/?probe=6cc495c0d9) | Nov 20, 2022 |
| Acer          | Aspire ES1-521              | Notebook    | [6af4249f1a](https://linux-hardware.org/?probe=6af4249f1a) | Nov 20, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [77dcd3bef6](https://linux-hardware.org/?probe=77dcd3bef6) | Nov 19, 2022 |
| MSI           | Z77A-G43                    | Desktop     | [2033b97419](https://linux-hardware.org/?probe=2033b97419) | Nov 19, 2022 |
| Acer          | FX58M                       | Desktop     | [837da7d885](https://linux-hardware.org/?probe=837da7d885) | Nov 19, 2022 |
| Apple         | Mac-F4218EC8 DVT            | All in one  | [c92c0834ef](https://linux-hardware.org/?probe=c92c0834ef) | Nov 19, 2022 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [a7c034bd91](https://linux-hardware.org/?probe=a7c034bd91) | Nov 19, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [b40e651ff2](https://linux-hardware.org/?probe=b40e651ff2) | Nov 18, 2022 |
| Dell          | Latitude E6540              | Notebook    | [4148292f4d](https://linux-hardware.org/?probe=4148292f4d) | Nov 18, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [0185c349b9](https://linux-hardware.org/?probe=0185c349b9) | Nov 18, 2022 |
| HP            | 14                          | Notebook    | [958eb656f2](https://linux-hardware.org/?probe=958eb656f2) | Nov 18, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [6992e11b21](https://linux-hardware.org/?probe=6992e11b21) | Nov 18, 2022 |
| Dell          | Latitude E6540              | Notebook    | [31752fdaa8](https://linux-hardware.org/?probe=31752fdaa8) | Nov 18, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [3e217adbf8](https://linux-hardware.org/?probe=3e217adbf8) | Nov 18, 2022 |
| HP            | 14                          | Notebook    | [8e4d001eb6](https://linux-hardware.org/?probe=8e4d001eb6) | Nov 18, 2022 |
| Unknown       | Unknown                     | Notebook    | [ef7af01d47](https://linux-hardware.org/?probe=ef7af01d47) | Nov 18, 2022 |
| Unknown       | Unknown                     | Notebook    | [ceca708c95](https://linux-hardware.org/?probe=ceca708c95) | Nov 18, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [0c4442c160](https://linux-hardware.org/?probe=0c4442c160) | Nov 18, 2022 |
| Dell          | 0C27VV A02                  | Desktop     | [5f4b4b8571](https://linux-hardware.org/?probe=5f4b4b8571) | Nov 18, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [f324f5bc16](https://linux-hardware.org/?probe=f324f5bc16) | Nov 18, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [1c76975e0e](https://linux-hardware.org/?probe=1c76975e0e) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | Notebook    | [fc1628983b](https://linux-hardware.org/?probe=fc1628983b) | Nov 17, 2022 |
| ALLDOCUBE     | i1405S                      | Notebook    | [0b61421847](https://linux-hardware.org/?probe=0b61421847) | Nov 17, 2022 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [522c9222c5](https://linux-hardware.org/?probe=522c9222c5) | Nov 17, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [b81771eed0](https://linux-hardware.org/?probe=b81771eed0) | Nov 17, 2022 |
| Acer          | Aspire 7741                 | Notebook    | [4197d5fccf](https://linux-hardware.org/?probe=4197d5fccf) | Nov 17, 2022 |
| MSI           | H81M-P33                    | Desktop     | [a535339292](https://linux-hardware.org/?probe=a535339292) | Nov 17, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [23f8c23e8b](https://linux-hardware.org/?probe=23f8c23e8b) | Nov 17, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [545eb5e46c](https://linux-hardware.org/?probe=545eb5e46c) | Nov 16, 2022 |
| MSI           | 2AE0                        | Desktop     | [c0d9e23faa](https://linux-hardware.org/?probe=c0d9e23faa) | Nov 16, 2022 |
| MSI           | H81M-P33                    | Desktop     | [246d594268](https://linux-hardware.org/?probe=246d594268) | Nov 16, 2022 |
| Gateway       | NV59C                       | Notebook    | [b3be978b72](https://linux-hardware.org/?probe=b3be978b72) | Nov 16, 2022 |
| Dell          | Inspiron 3543               | Notebook    | [15cc03ec87](https://linux-hardware.org/?probe=15cc03ec87) | Nov 16, 2022 |
| Lenovo        | ThinkPad X201 36809T1       | Notebook    | [aad9f7cbaf](https://linux-hardware.org/?probe=aad9f7cbaf) | Nov 16, 2022 |
| HP            | 0AA4h                       | Desktop     | [328259669b](https://linux-hardware.org/?probe=328259669b) | Nov 16, 2022 |
| Lenovo        | ThinkPad P15v Gen 3 21D9... | Notebook    | [30c7b06e6f](https://linux-hardware.org/?probe=30c7b06e6f) | Nov 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [733e52cbdb](https://linux-hardware.org/?probe=733e52cbdb) | Nov 15, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [9a93c5f349](https://linux-hardware.org/?probe=9a93c5f349) | Nov 15, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [d1e60135e1](https://linux-hardware.org/?probe=d1e60135e1) | Nov 15, 2022 |
| HP            | 18E7                        | Desktop     | [7ecd6a2f37](https://linux-hardware.org/?probe=7ecd6a2f37) | Nov 15, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [b240ae5338](https://linux-hardware.org/?probe=b240ae5338) | Nov 15, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [d1049db1fb](https://linux-hardware.org/?probe=d1049db1fb) | Nov 15, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [73bc7e7428](https://linux-hardware.org/?probe=73bc7e7428) | Nov 14, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [9d798077df](https://linux-hardware.org/?probe=9d798077df) | Nov 14, 2022 |
| ALURIN        | PR1-M146                    | Notebook    | [124eefce98](https://linux-hardware.org/?probe=124eefce98) | Nov 14, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [5d1cf4ca11](https://linux-hardware.org/?probe=5d1cf4ca11) | Nov 14, 2022 |
| Microtech     | ebookLite                   | Notebook    | [471a1a6ac7](https://linux-hardware.org/?probe=471a1a6ac7) | Nov 14, 2022 |
| Acer          | Extensa 2530                | Notebook    | [ac83b4e3e9](https://linux-hardware.org/?probe=ac83b4e3e9) | Nov 14, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [4ce82dba3d](https://linux-hardware.org/?probe=4ce82dba3d) | Nov 14, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [97b0a5f239](https://linux-hardware.org/?probe=97b0a5f239) | Nov 14, 2022 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [9e70e7fc3a](https://linux-hardware.org/?probe=9e70e7fc3a) | Nov 13, 2022 |
| HP            | 1850                        | Desktop     | [0b5e36c27b](https://linux-hardware.org/?probe=0b5e36c27b) | Nov 13, 2022 |
| Hampoo        | Cherry Trail CR             | Notebook    | [ae8d0b2d8e](https://linux-hardware.org/?probe=ae8d0b2d8e) | Nov 13, 2022 |
| Mediacom      | M-AO241/64                  | Desktop     | [8c577b3d8f](https://linux-hardware.org/?probe=8c577b3d8f) | Nov 13, 2022 |
| ALURIN        | PR1-M146                    | Notebook    | [8d9345b655](https://linux-hardware.org/?probe=8d9345b655) | Nov 12, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [1c7b3f934d](https://linux-hardware.org/?probe=1c7b3f934d) | Nov 12, 2022 |
| Fujitsu Si... | MS-7304VP-A13               | Desktop     | [69b1471202](https://linux-hardware.org/?probe=69b1471202) | Nov 12, 2022 |
| HP            | 250 G4                      | Notebook    | [58f7b77f39](https://linux-hardware.org/?probe=58f7b77f39) | Nov 12, 2022 |
| HP            | 250 G4                      | Notebook    | [f700001da4](https://linux-hardware.org/?probe=f700001da4) | Nov 12, 2022 |
| JGINYUE       | X79M-PLUS V2.3              | Desktop     | [8dac2a9292](https://linux-hardware.org/?probe=8dac2a9292) | Nov 12, 2022 |
| Microtech     | ebookLite                   | Notebook    | [9c3039fa75](https://linux-hardware.org/?probe=9c3039fa75) | Nov 12, 2022 |
| Fujitsu       | STYLISTIC Q572              | Notebook    | [afd0e0efc4](https://linux-hardware.org/?probe=afd0e0efc4) | Nov 12, 2022 |
| Unknown       | 775i65G                     | Desktop     | [b872a779af](https://linux-hardware.org/?probe=b872a779af) | Nov 12, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [16247a3667](https://linux-hardware.org/?probe=16247a3667) | Nov 12, 2022 |
| Dell          | 018D1Y A00                  | Desktop     | [bc5562e288](https://linux-hardware.org/?probe=bc5562e288) | Nov 12, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [2865464ccd](https://linux-hardware.org/?probe=2865464ccd) | Nov 11, 2022 |
| Biostar       | TPower X58                  | Desktop     | [8662697d27](https://linux-hardware.org/?probe=8662697d27) | Nov 11, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [1d6ae45d45](https://linux-hardware.org/?probe=1d6ae45d45) | Nov 11, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [2e79d44f43](https://linux-hardware.org/?probe=2e79d44f43) | Nov 11, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [1f9e0a7e16](https://linux-hardware.org/?probe=1f9e0a7e16) | Nov 11, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [d3a6ca47df](https://linux-hardware.org/?probe=d3a6ca47df) | Nov 11, 2022 |
| HP            | 2000                        | Notebook    | [5045f21cc3](https://linux-hardware.org/?probe=5045f21cc3) | Nov 10, 2022 |
| Microtech     | ebookLite                   | Notebook    | [63f80f900a](https://linux-hardware.org/?probe=63f80f900a) | Nov 10, 2022 |
| ASUSTek       | G50VT                       | Notebook    | [57f7e69b18](https://linux-hardware.org/?probe=57f7e69b18) | Nov 10, 2022 |
| Mediacom      | M-AO241/64                  | Desktop     | [d0cac7ee7b](https://linux-hardware.org/?probe=d0cac7ee7b) | Nov 10, 2022 |
| Mediacom      | M-AO241/64                  | Desktop     | [cf0ed7acab](https://linux-hardware.org/?probe=cf0ed7acab) | Nov 10, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [bb4dff706b](https://linux-hardware.org/?probe=bb4dff706b) | Nov 10, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [b7619dbd72](https://linux-hardware.org/?probe=b7619dbd72) | Nov 10, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [fb2770f137](https://linux-hardware.org/?probe=fb2770f137) | Nov 10, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [150409691d](https://linux-hardware.org/?probe=150409691d) | Nov 09, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [ef9d0cf774](https://linux-hardware.org/?probe=ef9d0cf774) | Nov 09, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [c3aaf6eed2](https://linux-hardware.org/?probe=c3aaf6eed2) | Nov 09, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a7de751ce8](https://linux-hardware.org/?probe=a7de751ce8) | Nov 09, 2022 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [cf64038190](https://linux-hardware.org/?probe=cf64038190) | Nov 08, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [c17772f8e7](https://linux-hardware.org/?probe=c17772f8e7) | Nov 08, 2022 |
| H-BUSTER      | HBNB1403                    | Notebook    | [9d439a53b2](https://linux-hardware.org/?probe=9d439a53b2) | Nov 08, 2022 |
| HP            | ProBook 430 G4              | Notebook    | [5d6f34affd](https://linux-hardware.org/?probe=5d6f34affd) | Nov 08, 2022 |
| Gateway       | ML6732                      | Notebook    | [7889349228](https://linux-hardware.org/?probe=7889349228) | Nov 08, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [5030ff83c2](https://linux-hardware.org/?probe=5030ff83c2) | Nov 08, 2022 |
| Dell          | Latitude E5420              | Notebook    | [c6264f1223](https://linux-hardware.org/?probe=c6264f1223) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [5285abf94f](https://linux-hardware.org/?probe=5285abf94f) | Nov 08, 2022 |
| A-DATA Tec... | XENIAXe15TI7G11GXELX        | Notebook    | [5cfd9a145a](https://linux-hardware.org/?probe=5cfd9a145a) | Nov 08, 2022 |
| Linx          | LINX1010B                   | Notebook    | [fa6d1ebd57](https://linux-hardware.org/?probe=fa6d1ebd57) | Nov 07, 2022 |
| HP            | Pavilion dv5000 (EU087EA... | Notebook    | [185c483599](https://linux-hardware.org/?probe=185c483599) | Nov 07, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [d8a78ad824](https://linux-hardware.org/?probe=d8a78ad824) | Nov 07, 2022 |
| MSI           | H81M-P33                    | Desktop     | [2ef23ed4ac](https://linux-hardware.org/?probe=2ef23ed4ac) | Nov 07, 2022 |
| ASUSTek       | U36SD                       | Notebook    | [d6b92cbdaa](https://linux-hardware.org/?probe=d6b92cbdaa) | Nov 07, 2022 |
| ASUSTek       | F5V                         | Notebook    | [877e968b61](https://linux-hardware.org/?probe=877e968b61) | Nov 07, 2022 |
| HP            | 240 G8                      | Notebook    | [cbeff38360](https://linux-hardware.org/?probe=cbeff38360) | Nov 07, 2022 |
| HP            | 240 G8                      | Notebook    | [0fadcc21ac](https://linux-hardware.org/?probe=0fadcc21ac) | Nov 07, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [e44a807758](https://linux-hardware.org/?probe=e44a807758) | Nov 06, 2022 |
| Acer          | H81H3-M4                    | Desktop     | [40c67913d8](https://linux-hardware.org/?probe=40c67913d8) | Nov 06, 2022 |
| HP            | Pavilion dv5000 (EU087EA... | Notebook    | [d763771ba6](https://linux-hardware.org/?probe=d763771ba6) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | Desktop     | [708d98bf92](https://linux-hardware.org/?probe=708d98bf92) | Nov 06, 2022 |
| ASRock        | B660M Steel Legend          | Desktop     | [2fce0b247c](https://linux-hardware.org/?probe=2fce0b247c) | Nov 06, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [8a62c61d38](https://linux-hardware.org/?probe=8a62c61d38) | Nov 06, 2022 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [a06275a0f2](https://linux-hardware.org/?probe=a06275a0f2) | Nov 05, 2022 |
| Quanta        | TW8/SW8/DW8                 | Notebook    | [31caaec976](https://linux-hardware.org/?probe=31caaec976) | Nov 05, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [e14cb334c4](https://linux-hardware.org/?probe=e14cb334c4) | Nov 05, 2022 |
| HP            | 1790                        | Desktop     | [8916928344](https://linux-hardware.org/?probe=8916928344) | Nov 05, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [ee11f3942f](https://linux-hardware.org/?probe=ee11f3942f) | Nov 05, 2022 |
| HP            | 1790                        | Desktop     | [1de8a8af0d](https://linux-hardware.org/?probe=1de8a8af0d) | Nov 05, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [2313029c70](https://linux-hardware.org/?probe=2313029c70) | Nov 04, 2022 |
| Lenovo        | ThinkPad P16 Gen 1 21D7S... | Notebook    | [fc4b865872](https://linux-hardware.org/?probe=fc4b865872) | Nov 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [507697b22f](https://linux-hardware.org/?probe=507697b22f) | Nov 04, 2022 |
| Dell          | 0C27VV A02                  | Desktop     | [fb4c1f85a2](https://linux-hardware.org/?probe=fb4c1f85a2) | Nov 04, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a8f3260004](https://linux-hardware.org/?probe=a8f3260004) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [60d8b24187](https://linux-hardware.org/?probe=60d8b24187) | Nov 04, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [81c0293410](https://linux-hardware.org/?probe=81c0293410) | Nov 04, 2022 |
| BANGHO        | W240HU/W250HUQ              | Notebook    | [82bafb1ca4](https://linux-hardware.org/?probe=82bafb1ca4) | Nov 04, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [c796c2f9ee](https://linux-hardware.org/?probe=c796c2f9ee) | Nov 03, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [baf6b79b85](https://linux-hardware.org/?probe=baf6b79b85) | Nov 03, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [30cd9b0d29](https://linux-hardware.org/?probe=30cd9b0d29) | Nov 03, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [fea56b5428](https://linux-hardware.org/?probe=fea56b5428) | Nov 03, 2022 |
| Microtech     | CoreBook                    | Notebook    | [1276c24890](https://linux-hardware.org/?probe=1276c24890) | Nov 03, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [920c4567d3](https://linux-hardware.org/?probe=920c4567d3) | Nov 03, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [e24f2a2f57](https://linux-hardware.org/?probe=e24f2a2f57) | Nov 03, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [df00a6281b](https://linux-hardware.org/?probe=df00a6281b) | Nov 03, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [2ec155a4b6](https://linux-hardware.org/?probe=2ec155a4b6) | Nov 03, 2022 |
| Dell          | Latitude E6540              | Notebook    | [fe0f06d2d3](https://linux-hardware.org/?probe=fe0f06d2d3) | Nov 02, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [383066ca1c](https://linux-hardware.org/?probe=383066ca1c) | Nov 02, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [56767f430b](https://linux-hardware.org/?probe=56767f430b) | Nov 02, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [b1ffa94d76](https://linux-hardware.org/?probe=b1ffa94d76) | Nov 02, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [66acf8991e](https://linux-hardware.org/?probe=66acf8991e) | Nov 02, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [ebe8179d26](https://linux-hardware.org/?probe=ebe8179d26) | Nov 02, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [9fef9a6a8a](https://linux-hardware.org/?probe=9fef9a6a8a) | Nov 02, 2022 |
| Dell          | 0GDG8Y A00                  | Desktop     | [609ccd3204](https://linux-hardware.org/?probe=609ccd3204) | Nov 02, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [4968129a1a](https://linux-hardware.org/?probe=4968129a1a) | Nov 02, 2022 |
| Lenovo        | IdeaPad 100S-11IBY 80R2     | Notebook    | [7c6ddf22b5](https://linux-hardware.org/?probe=7c6ddf22b5) | Nov 02, 2022 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [a7fb2c2163](https://linux-hardware.org/?probe=a7fb2c2163) | Nov 02, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [005b25ef06](https://linux-hardware.org/?probe=005b25ef06) | Nov 02, 2022 |
| Gigabyte      | P55-UD6                     | Desktop     | [2898ec20b3](https://linux-hardware.org/?probe=2898ec20b3) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cd0e637d88](https://linux-hardware.org/?probe=cd0e637d88) | Nov 01, 2022 |
| Lenovo        | ThinkCentre M55E 898578G    | Desktop     | [d025c115d8](https://linux-hardware.org/?probe=d025c115d8) | Nov 01, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [9dea1bfedb](https://linux-hardware.org/?probe=9dea1bfedb) | Nov 01, 2022 |
| HP            | Pavilion 15                 | Notebook    | [8552c17b28](https://linux-hardware.org/?probe=8552c17b28) | Nov 01, 2022 |
| HP            | ProBook 650 G1              | Notebook    | [85f1aa7b6d](https://linux-hardware.org/?probe=85f1aa7b6d) | Nov 01, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [6e2ff87fad](https://linux-hardware.org/?probe=6e2ff87fad) | Nov 01, 2022 |
| Lenovo        | ThinkPad Edge E530c 3366... | Notebook    | [9864cd6db6](https://linux-hardware.org/?probe=9864cd6db6) | Nov 01, 2022 |
| HP            | 2B3B                        | All in one  | [a42ac6f6c7](https://linux-hardware.org/?probe=a42ac6f6c7) | Nov 01, 2022 |
| GPU Compan... | GWTN156-2BK                 | Notebook    | [99ab599fbc](https://linux-hardware.org/?probe=99ab599fbc) | Nov 01, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [21213fdeec](https://linux-hardware.org/?probe=21213fdeec) | Oct 31, 2022 |
| Dell          | Latitude E6500              | Notebook    | [b7be8c3204](https://linux-hardware.org/?probe=b7be8c3204) | Oct 31, 2022 |
| Dell          | Latitude E6500              | Notebook    | [cb3b467ba8](https://linux-hardware.org/?probe=cb3b467ba8) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [dc7fa9ac1e](https://linux-hardware.org/?probe=dc7fa9ac1e) | Oct 31, 2022 |
| HP            | 1790                        | Desktop     | [6dc2cef5ea](https://linux-hardware.org/?probe=6dc2cef5ea) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | Notebook    | [ba67d47c9c](https://linux-hardware.org/?probe=ba67d47c9c) | Oct 31, 2022 |
| Seco          | C40 C                       | Desktop     | [08509c30b6](https://linux-hardware.org/?probe=08509c30b6) | Oct 31, 2022 |
| HP            | 2000                        | Notebook    | [ea6e4e2cca](https://linux-hardware.org/?probe=ea6e4e2cca) | Oct 31, 2022 |
| Lenovo        | ThinkPad T420 4180DW1       | Notebook    | [b1e229b9a0](https://linux-hardware.org/?probe=b1e229b9a0) | Oct 31, 2022 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [34727cd696](https://linux-hardware.org/?probe=34727cd696) | Oct 31, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [6bf9e760ca](https://linux-hardware.org/?probe=6bf9e760ca) | Oct 30, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [b83d2dd685](https://linux-hardware.org/?probe=b83d2dd685) | Oct 30, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [f7dd154c47](https://linux-hardware.org/?probe=f7dd154c47) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [1ca9fe180c](https://linux-hardware.org/?probe=1ca9fe180c) | Oct 30, 2022 |
| Lenovo        | ThinkPad T480 20L6S82F0C    | Notebook    | [c06d6a27f5](https://linux-hardware.org/?probe=c06d6a27f5) | Oct 30, 2022 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [50170811fd](https://linux-hardware.org/?probe=50170811fd) | Oct 30, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [d8f6faad10](https://linux-hardware.org/?probe=d8f6faad10) | Oct 30, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [75dcd27c77](https://linux-hardware.org/?probe=75dcd27c77) | Oct 30, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [6c3a410233](https://linux-hardware.org/?probe=6c3a410233) | Oct 30, 2022 |
| Dell          | Inspiron 5537               | Notebook    | [4cd1e12a5d](https://linux-hardware.org/?probe=4cd1e12a5d) | Oct 30, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [f844544154](https://linux-hardware.org/?probe=f844544154) | Oct 30, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [97d7d8c2d9](https://linux-hardware.org/?probe=97d7d8c2d9) | Oct 29, 2022 |
| Lenovo        | ThinkPad T460 20FMS7DA00    | Notebook    | [861aaf5a99](https://linux-hardware.org/?probe=861aaf5a99) | Oct 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [ae6fd2de89](https://linux-hardware.org/?probe=ae6fd2de89) | Oct 29, 2022 |
| MSI           | GL72 6QD                    | Notebook    | [2f7c223f5a](https://linux-hardware.org/?probe=2f7c223f5a) | Oct 29, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [068d4ec2e6](https://linux-hardware.org/?probe=068d4ec2e6) | Oct 29, 2022 |
| Acer          | Extensa 5635ZG              | Notebook    | [8c0a7c0aa1](https://linux-hardware.org/?probe=8c0a7c0aa1) | Oct 29, 2022 |
| Dell          | 0T2HR0 A02                  | Desktop     | [e4b1137777](https://linux-hardware.org/?probe=e4b1137777) | Oct 29, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [2c57f9b6a3](https://linux-hardware.org/?probe=2c57f9b6a3) | Oct 29, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [242fa16882](https://linux-hardware.org/?probe=242fa16882) | Oct 29, 2022 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [f111078004](https://linux-hardware.org/?probe=f111078004) | Oct 29, 2022 |
| Phoenix/Si... | M7x0S                       | Notebook    | [8b27fc5eb3](https://linux-hardware.org/?probe=8b27fc5eb3) | Oct 29, 2022 |
| MSI           | B560M PRO                   | Desktop     | [a84dc6f9cb](https://linux-hardware.org/?probe=a84dc6f9cb) | Oct 29, 2022 |
| Dell          | Latitude E6530              | Notebook    | [cdd3b5ce40](https://linux-hardware.org/?probe=cdd3b5ce40) | Oct 28, 2022 |
| HP            | Presario V6000 (RV053UA#... | Notebook    | [ca121e3727](https://linux-hardware.org/?probe=ca121e3727) | Oct 28, 2022 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [b683357ec4](https://linux-hardware.org/?probe=b683357ec4) | Oct 28, 2022 |
| HP            | OMEN Notebook PC 15         | Notebook    | [fea0167027](https://linux-hardware.org/?probe=fea0167027) | Oct 28, 2022 |
| Packard Be... | EasyNote MH45               | Notebook    | [b9aa4cc6d5](https://linux-hardware.org/?probe=b9aa4cc6d5) | Oct 27, 2022 |
| Gateway       | SX2851                      | Desktop     | [500b4bb8ec](https://linux-hardware.org/?probe=500b4bb8ec) | Oct 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9986b4ff02](https://linux-hardware.org/?probe=9986b4ff02) | Oct 27, 2022 |
| ASUSTek       | P8H61/USB3                  | Desktop     | [c20c97e43e](https://linux-hardware.org/?probe=c20c97e43e) | Oct 27, 2022 |
| HP            | 829B                        | All in one  | [1f8f75d1c0](https://linux-hardware.org/?probe=1f8f75d1c0) | Oct 27, 2022 |
| MSI           | MS-AE611 100                | All in one  | [7527f4a200](https://linux-hardware.org/?probe=7527f4a200) | Oct 27, 2022 |
| Acer          | Aspire 5720Z                | Notebook    | [fc0b8944bc](https://linux-hardware.org/?probe=fc0b8944bc) | Oct 26, 2022 |
| MSI           | Creator Z16 A11UET          | Notebook    | [58e18764cb](https://linux-hardware.org/?probe=58e18764cb) | Oct 26, 2022 |
| MSI           | Creator Z16 A11UET          | Notebook    | [06274bdff6](https://linux-hardware.org/?probe=06274bdff6) | Oct 26, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [7a0f5285f2](https://linux-hardware.org/?probe=7a0f5285f2) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [80c2aeb241](https://linux-hardware.org/?probe=80c2aeb241) | Oct 26, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [54f6493d11](https://linux-hardware.org/?probe=54f6493d11) | Oct 26, 2022 |
| ASUSTek       | PRIME Z690-P D4             | Desktop     | [5bc9d4bdc8](https://linux-hardware.org/?probe=5bc9d4bdc8) | Oct 26, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [6b0380ea4c](https://linux-hardware.org/?probe=6b0380ea4c) | Oct 26, 2022 |
| Dell          | Latitude E6510              | Notebook    | [1949f78888](https://linux-hardware.org/?probe=1949f78888) | Oct 26, 2022 |
| ALURIN        | PR1-M146                    | Notebook    | [af492a458f](https://linux-hardware.org/?probe=af492a458f) | Oct 25, 2022 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [bb655d6ea7](https://linux-hardware.org/?probe=bb655d6ea7) | Oct 25, 2022 |
| MSI           | MS-AE611 100                | All in one  | [1f6fc12b09](https://linux-hardware.org/?probe=1f6fc12b09) | Oct 25, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [91437ee9a7](https://linux-hardware.org/?probe=91437ee9a7) | Oct 25, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [742bf13a9f](https://linux-hardware.org/?probe=742bf13a9f) | Oct 25, 2022 |
| MSI           | GT70 2PE                    | Notebook    | [26d9f8ba04](https://linux-hardware.org/?probe=26d9f8ba04) | Oct 25, 2022 |
| Toshiba       | K201                        | Notebook    | [63a892bae3](https://linux-hardware.org/?probe=63a892bae3) | Oct 25, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [aa82a1f3c9](https://linux-hardware.org/?probe=aa82a1f3c9) | Oct 24, 2022 |
| MSI           | GE62 7RE                    | Notebook    | [bd5b8943f4](https://linux-hardware.org/?probe=bd5b8943f4) | Oct 24, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [d8f70347cf](https://linux-hardware.org/?probe=d8f70347cf) | Oct 24, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [26e7b206ef](https://linux-hardware.org/?probe=26e7b206ef) | Oct 24, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [e894ec1b8d](https://linux-hardware.org/?probe=e894ec1b8d) | Oct 24, 2022 |
| Lenovo        | ThinkPad T520 4243PN7       | Notebook    | [fdca71510b](https://linux-hardware.org/?probe=fdca71510b) | Oct 24, 2022 |
| Lenovo        | G50-45 80MQ                 | Notebook    | [2628815c23](https://linux-hardware.org/?probe=2628815c23) | Oct 24, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [200f2ac48e](https://linux-hardware.org/?probe=200f2ac48e) | Oct 24, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [646b07cc4c](https://linux-hardware.org/?probe=646b07cc4c) | Oct 24, 2022 |
| Alienware     | 18                          | Notebook    | [11e8831b9d](https://linux-hardware.org/?probe=11e8831b9d) | Oct 24, 2022 |
| Alienware     | 18                          | Notebook    | [86eb347494](https://linux-hardware.org/?probe=86eb347494) | Oct 24, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [17adb9ee1e](https://linux-hardware.org/?probe=17adb9ee1e) | Oct 23, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [055a6c2be8](https://linux-hardware.org/?probe=055a6c2be8) | Oct 23, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [cb299f8f1b](https://linux-hardware.org/?probe=cb299f8f1b) | Oct 23, 2022 |
| Gigabyte      | GA-78LMT-S2                 | Desktop     | [dad9e03a82](https://linux-hardware.org/?probe=dad9e03a82) | Oct 23, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [1f3d807ceb](https://linux-hardware.org/?probe=1f3d807ceb) | Oct 23, 2022 |
| Dell          | 0JP3NX A01                  | Desktop     | [86365f2c05](https://linux-hardware.org/?probe=86365f2c05) | Oct 23, 2022 |
| Gigabyte      | B150N Phoenix-WIFI-CF       | Desktop     | [6a42097b41](https://linux-hardware.org/?probe=6a42097b41) | Oct 23, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [42280c6145](https://linux-hardware.org/?probe=42280c6145) | Oct 23, 2022 |
| AMI           | Unknown                     | Notebook    | [337d94fb96](https://linux-hardware.org/?probe=337d94fb96) | Oct 23, 2022 |
| ASUSTek       | X510UQ                      | Notebook    | [6d976f6f96](https://linux-hardware.org/?probe=6d976f6f96) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [9035fff7ea](https://linux-hardware.org/?probe=9035fff7ea) | Oct 23, 2022 |
| Dell          | 0200DY A02                  | Desktop     | [8fd4b48b80](https://linux-hardware.org/?probe=8fd4b48b80) | Oct 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3d2171b17e](https://linux-hardware.org/?probe=3d2171b17e) | Oct 23, 2022 |
| Dell          | 0HN7XN A01                  | Desktop     | [4e75c878a3](https://linux-hardware.org/?probe=4e75c878a3) | Oct 22, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [a8a9cdfabc](https://linux-hardware.org/?probe=a8a9cdfabc) | Oct 22, 2022 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [d82378ea41](https://linux-hardware.org/?probe=d82378ea41) | Oct 22, 2022 |
| Acer          | Aspire E5-411               | Notebook    | [f4fa3fce70](https://linux-hardware.org/?probe=f4fa3fce70) | Oct 22, 2022 |
| HP            | EliteBook 755 G5            | Notebook    | [b1550ee8e1](https://linux-hardware.org/?probe=b1550ee8e1) | Oct 22, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [f43a04f63f](https://linux-hardware.org/?probe=f43a04f63f) | Oct 21, 2022 |
| Dell          | Studio 1558                 | Notebook    | [ac449d0411](https://linux-hardware.org/?probe=ac449d0411) | Oct 21, 2022 |
| HP            | Stream Notebook             | Notebook    | [685271f268](https://linux-hardware.org/?probe=685271f268) | Oct 21, 2022 |
| Acer          | Predator PH517-61           | Notebook    | [e30217884a](https://linux-hardware.org/?probe=e30217884a) | Oct 21, 2022 |
| Dell          | Vostro V13                  | Notebook    | [c7cd7a2ddf](https://linux-hardware.org/?probe=c7cd7a2ddf) | Oct 21, 2022 |
| Dell          | Vostro V13                  | Notebook    | [43eb559763](https://linux-hardware.org/?probe=43eb559763) | Oct 21, 2022 |
| Gigabyte      | GA-78LMT-S2 sex             | Desktop     | [95ddb7c758](https://linux-hardware.org/?probe=95ddb7c758) | Oct 21, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [31d7e67080](https://linux-hardware.org/?probe=31d7e67080) | Oct 21, 2022 |
| Acer          | Aspire A315-33              | Notebook    | [1358385d49](https://linux-hardware.org/?probe=1358385d49) | Oct 20, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [0aad9d8ecd](https://linux-hardware.org/?probe=0aad9d8ecd) | Oct 20, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [354afbd4d8](https://linux-hardware.org/?probe=354afbd4d8) | Oct 20, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [f31749db41](https://linux-hardware.org/?probe=f31749db41) | Oct 20, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [8ae5de2c7d](https://linux-hardware.org/?probe=8ae5de2c7d) | Oct 20, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [2991e146ce](https://linux-hardware.org/?probe=2991e146ce) | Oct 19, 2022 |
| HP            | G62                         | Notebook    | [721c09b331](https://linux-hardware.org/?probe=721c09b331) | Oct 19, 2022 |
| Microtech     | CoreBook                    | Notebook    | [0592b30e41](https://linux-hardware.org/?probe=0592b30e41) | Oct 19, 2022 |
| Microtech     | CoreBook                    | Notebook    | [536451ed8a](https://linux-hardware.org/?probe=536451ed8a) | Oct 19, 2022 |
| ASRock        | 970 Extreme3                | Desktop     | [23f7ae20e3](https://linux-hardware.org/?probe=23f7ae20e3) | Oct 19, 2022 |
| Dell          | Studio 1458                 | Notebook    | [57b5c85b2a](https://linux-hardware.org/?probe=57b5c85b2a) | Oct 19, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [5d1bb5d8aa](https://linux-hardware.org/?probe=5d1bb5d8aa) | Oct 19, 2022 |
| ASUSTek       | T200TAC                     | Notebook    | [c33c750766](https://linux-hardware.org/?probe=c33c750766) | Oct 18, 2022 |
| Dell          | 0GTK4K A02                  | Desktop     | [f92314f74b](https://linux-hardware.org/?probe=f92314f74b) | Oct 18, 2022 |
| HP            | Notebook                    | Notebook    | [01692e8f30](https://linux-hardware.org/?probe=01692e8f30) | Oct 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ff6d42a3ef](https://linux-hardware.org/?probe=ff6d42a3ef) | Oct 17, 2022 |
| Acer          | Aspire E5-411               | Notebook    | [01979e17ce](https://linux-hardware.org/?probe=01979e17ce) | Oct 17, 2022 |
| HP            | Laptop 15-db0xxx            | Notebook    | [4b0c3a6022](https://linux-hardware.org/?probe=4b0c3a6022) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [f188526e04](https://linux-hardware.org/?probe=f188526e04) | Oct 17, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [50c44df4fb](https://linux-hardware.org/?probe=50c44df4fb) | Oct 17, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [bc6696e1d5](https://linux-hardware.org/?probe=bc6696e1d5) | Oct 17, 2022 |
| Toshiba       | Satellite C55-A             | Notebook    | [f93fb31ad5](https://linux-hardware.org/?probe=f93fb31ad5) | Oct 16, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [0c025c3b68](https://linux-hardware.org/?probe=0c025c3b68) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c4a0f6af56](https://linux-hardware.org/?probe=c4a0f6af56) | Oct 16, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [cde8c87a3a](https://linux-hardware.org/?probe=cde8c87a3a) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | Notebook    | [9c955c6521](https://linux-hardware.org/?probe=9c955c6521) | Oct 16, 2022 |
| Dell          | Inspiron 14 5401            | Notebook    | [5fbc33b9bf](https://linux-hardware.org/?probe=5fbc33b9bf) | Oct 16, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [732c7afd4c](https://linux-hardware.org/?probe=732c7afd4c) | Oct 16, 2022 |
| HP            | 1790                        | Desktop     | [5b9b2357c5](https://linux-hardware.org/?probe=5b9b2357c5) | Oct 16, 2022 |
| Dell          | 0XGMD0 A00                  | All in one  | [e38169d409](https://linux-hardware.org/?probe=e38169d409) | Oct 16, 2022 |
| Intel         | H55                         | Desktop     | [ab27a6c8d9](https://linux-hardware.org/?probe=ab27a6c8d9) | Oct 15, 2022 |
| Google        | Lars                        | Notebook    | [b607a23c77](https://linux-hardware.org/?probe=b607a23c77) | Oct 14, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [bb7d61198e](https://linux-hardware.org/?probe=bb7d61198e) | Oct 14, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [772645390a](https://linux-hardware.org/?probe=772645390a) | Oct 14, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [7e770fd62b](https://linux-hardware.org/?probe=7e770fd62b) | Oct 14, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [e4c404552a](https://linux-hardware.org/?probe=e4c404552a) | Oct 13, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [4fe76d84fd](https://linux-hardware.org/?probe=4fe76d84fd) | Oct 13, 2022 |
| HP            | 18E7                        | Desktop     | [98b59ebfce](https://linux-hardware.org/?probe=98b59ebfce) | Oct 13, 2022 |
| HP            | 0AA0h                       | Desktop     | [f4a69ac6f5](https://linux-hardware.org/?probe=f4a69ac6f5) | Oct 13, 2022 |
| Dell          | Vostro 3558                 | Notebook    | [855e0d050c](https://linux-hardware.org/?probe=855e0d050c) | Oct 13, 2022 |
| Dell          | Latitude E6330              | Notebook    | [815d48ffba](https://linux-hardware.org/?probe=815d48ffba) | Oct 12, 2022 |
| HP            | 2AF3                        | Desktop     | [f59df65c18](https://linux-hardware.org/?probe=f59df65c18) | Oct 12, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [e8dd0752ac](https://linux-hardware.org/?probe=e8dd0752ac) | Oct 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [bfd4bad69d](https://linux-hardware.org/?probe=bfd4bad69d) | Oct 11, 2022 |
| Dell          | Latitude E6410              | Notebook    | [9ed4124073](https://linux-hardware.org/?probe=9ed4124073) | Oct 11, 2022 |
| HP            | 304Ah                       | Desktop     | [69f11e2008](https://linux-hardware.org/?probe=69f11e2008) | Oct 11, 2022 |
| TERRA         | TERRAPC                     | Notebook    | [048f3ad5ef](https://linux-hardware.org/?probe=048f3ad5ef) | Oct 11, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [da36ee9925](https://linux-hardware.org/?probe=da36ee9925) | Oct 11, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [5c2dd967f9](https://linux-hardware.org/?probe=5c2dd967f9) | Oct 11, 2022 |
| Standard      | X50-V2                      | Desktop     | [fbcfd56903](https://linux-hardware.org/?probe=fbcfd56903) | Oct 11, 2022 |
| Alienware     | 0NWN7M A00                  | Desktop     | [a7c3e67810](https://linux-hardware.org/?probe=a7c3e67810) | Oct 10, 2022 |
| Acer          | Aspire A315-33              | Notebook    | [8606cbf7cc](https://linux-hardware.org/?probe=8606cbf7cc) | Oct 10, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [f6e7e1585c](https://linux-hardware.org/?probe=f6e7e1585c) | Oct 10, 2022 |
| Dell          | 0X9M3X A01                  | Desktop     | [b729cadad8](https://linux-hardware.org/?probe=b729cadad8) | Oct 10, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [897321f579](https://linux-hardware.org/?probe=897321f579) | Oct 09, 2022 |
| ASUSTek       | H81M-P                      | Desktop     | [907b7761d0](https://linux-hardware.org/?probe=907b7761d0) | Oct 09, 2022 |
| ASUSTek       | H81M-P                      | Desktop     | [f2d9df375d](https://linux-hardware.org/?probe=f2d9df375d) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | Notebook    | [439e2c8122](https://linux-hardware.org/?probe=439e2c8122) | Oct 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [fef2c17618](https://linux-hardware.org/?probe=fef2c17618) | Oct 09, 2022 |
| Panasonic     | CF-19-8                     | Notebook    | [bc5820629b](https://linux-hardware.org/?probe=bc5820629b) | Oct 09, 2022 |
| Packard Be... | EasyNote TM82               | Notebook    | [8e3ecfd03d](https://linux-hardware.org/?probe=8e3ecfd03d) | Oct 08, 2022 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [d1c01a07a2](https://linux-hardware.org/?probe=d1c01a07a2) | Oct 08, 2022 |
| Acer          | EM61SM/EM61PM               | Desktop     | [58d2cda88f](https://linux-hardware.org/?probe=58d2cda88f) | Oct 08, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [0b225367b8](https://linux-hardware.org/?probe=0b225367b8) | Oct 08, 2022 |
| Dell          | Latitude E6410              | Notebook    | [0b617be9dd](https://linux-hardware.org/?probe=0b617be9dd) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [46b44504df](https://linux-hardware.org/?probe=46b44504df) | Oct 08, 2022 |
| AXDIA Inte... | WINBOOK 13                  | Notebook    | [35638411ee](https://linux-hardware.org/?probe=35638411ee) | Oct 08, 2022 |
| Fujitsu       | LIFEBOOK LH531              | Notebook    | [21a68d8c0e](https://linux-hardware.org/?probe=21a68d8c0e) | Oct 08, 2022 |
| ASUSTek       | CM1630                      | Desktop     | [dc63e03d48](https://linux-hardware.org/?probe=dc63e03d48) | Oct 08, 2022 |
| Gateway       | SX2851                      | Desktop     | [2cc7e399b2](https://linux-hardware.org/?probe=2cc7e399b2) | Oct 08, 2022 |
| Dell          | Inspiron 1200               | Notebook    | [45c46e1b91](https://linux-hardware.org/?probe=45c46e1b91) | Oct 08, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [19db5a4e7c](https://linux-hardware.org/?probe=19db5a4e7c) | Oct 07, 2022 |
| TERRA         | TERRAPC                     | Notebook    | [ec9068f7ea](https://linux-hardware.org/?probe=ec9068f7ea) | Oct 07, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [005d2d7671](https://linux-hardware.org/?probe=005d2d7671) | Oct 07, 2022 |
| HP            | 822A                        | Desktop     | [c893a1b314](https://linux-hardware.org/?probe=c893a1b314) | Oct 07, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [d5a346bdd1](https://linux-hardware.org/?probe=d5a346bdd1) | Oct 07, 2022 |
| Dell          | 0YP696 A00                  | Desktop     | [588d3a6132](https://linux-hardware.org/?probe=588d3a6132) | Oct 07, 2022 |
| HP            | 8265                        | Desktop     | [ddf5f03d86](https://linux-hardware.org/?probe=ddf5f03d86) | Oct 07, 2022 |
| HP            | 843B                        | Desktop     | [5a744e115f](https://linux-hardware.org/?probe=5a744e115f) | Oct 06, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [5c00e1dddc](https://linux-hardware.org/?probe=5c00e1dddc) | Oct 06, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [29c7a43356](https://linux-hardware.org/?probe=29c7a43356) | Oct 06, 2022 |
| Dell          | Vostro 2520                 | Notebook    | [da789d3a06](https://linux-hardware.org/?probe=da789d3a06) | Oct 06, 2022 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [2e57f97484](https://linux-hardware.org/?probe=2e57f97484) | Oct 06, 2022 |
| Dell          | Latitude E6500              | Notebook    | [84fa5b35ed](https://linux-hardware.org/?probe=84fa5b35ed) | Oct 06, 2022 |
| Acer          | Aspire E1-522               | Notebook    | [769baa3828](https://linux-hardware.org/?probe=769baa3828) | Oct 05, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [397e5be75c](https://linux-hardware.org/?probe=397e5be75c) | Oct 05, 2022 |
| HP            | 2B60 MVB                    | Desktop     | [092e063471](https://linux-hardware.org/?probe=092e063471) | Oct 05, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [5bb972fab4](https://linux-hardware.org/?probe=5bb972fab4) | Oct 05, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | Notebook    | [9b8dc565f9](https://linux-hardware.org/?probe=9b8dc565f9) | Oct 04, 2022 |
| Gigabyte      | AORUS 7 SB                  | Notebook    | [444224d1e0](https://linux-hardware.org/?probe=444224d1e0) | Oct 04, 2022 |
| HP            | ENVY m6                     | Notebook    | [5c828496a7](https://linux-hardware.org/?probe=5c828496a7) | Oct 04, 2022 |
| Google        | Careena                     | Notebook    | [7ac4802a10](https://linux-hardware.org/?probe=7ac4802a10) | Oct 04, 2022 |
| Acer          | Extensa 2530                | Notebook    | [684b31b41d](https://linux-hardware.org/?probe=684b31b41d) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | Notebook    | [acae78b85a](https://linux-hardware.org/?probe=acae78b85a) | Oct 03, 2022 |
| HP            | 3397                        | Desktop     | [eb6f8b5a56](https://linux-hardware.org/?probe=eb6f8b5a56) | Oct 03, 2022 |
| HP            | ProBook 455 G6              | Notebook    | [3697a412bd](https://linux-hardware.org/?probe=3697a412bd) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [e17cbbf886](https://linux-hardware.org/?probe=e17cbbf886) | Oct 03, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [5767aaf6db](https://linux-hardware.org/?probe=5767aaf6db) | Oct 03, 2022 |
| ASUSTek       | P7H55-USB3                  | Desktop     | [9f15eece8f](https://linux-hardware.org/?probe=9f15eece8f) | Oct 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d3bcd51be1](https://linux-hardware.org/?probe=d3bcd51be1) | Oct 03, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [0c58d8b873](https://linux-hardware.org/?probe=0c58d8b873) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | Notebook    | [fb6e1d3652](https://linux-hardware.org/?probe=fb6e1d3652) | Oct 03, 2022 |
| ASUSTek       | R11CX                       | Notebook    | [f0bc5f49a4](https://linux-hardware.org/?probe=f0bc5f49a4) | Oct 03, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b8d65ced41](https://linux-hardware.org/?probe=b8d65ced41) | Oct 02, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b5b057439d](https://linux-hardware.org/?probe=b5b057439d) | Oct 02, 2022 |
| Lenovo        | V570 1066EDG                | Notebook    | [8e2439c590](https://linux-hardware.org/?probe=8e2439c590) | Oct 01, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [592adc6c9b](https://linux-hardware.org/?probe=592adc6c9b) | Oct 01, 2022 |
| HP            | 843B                        | Desktop     | [b683039e3b](https://linux-hardware.org/?probe=b683039e3b) | Oct 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [dc7e0ada81](https://linux-hardware.org/?probe=dc7e0ada81) | Oct 01, 2022 |
| Acer          | Aspire 4733Z                | Notebook    | [4be4debbe5](https://linux-hardware.org/?probe=4be4debbe5) | Oct 01, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f42501fcc3](https://linux-hardware.org/?probe=f42501fcc3) | Oct 01, 2022 |
| HP            | 1632                        | Desktop     | [0f9387690b](https://linux-hardware.org/?probe=0f9387690b) | Oct 01, 2022 |
| Hampoo        | C3W6_AP108_4GB Reserved     | Notebook    | [93d3e41339](https://linux-hardware.org/?probe=93d3e41339) | Oct 01, 2022 |
| Biostar       | B350ET2                     | Desktop     | [d7c5b1ad40](https://linux-hardware.org/?probe=d7c5b1ad40) | Oct 01, 2022 |
| Biostar       | B350ET2                     | Desktop     | [2b7bea0eda](https://linux-hardware.org/?probe=2b7bea0eda) | Sep 30, 2022 |
| Notebook      | NJ50GU                      | Notebook    | [430d3b2873](https://linux-hardware.org/?probe=430d3b2873) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [1f142c7087](https://linux-hardware.org/?probe=1f142c7087) | Sep 30, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [263313ef38](https://linux-hardware.org/?probe=263313ef38) | Sep 30, 2022 |
| MSI           | Z97 MPOWER                  | Desktop     | [f16a15a5b7](https://linux-hardware.org/?probe=f16a15a5b7) | Sep 30, 2022 |
| Apple         | Mac-F4218EC8 DVT            | All in one  | [1a331f2583](https://linux-hardware.org/?probe=1a331f2583) | Sep 30, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8c116d30f9](https://linux-hardware.org/?probe=8c116d30f9) | Sep 30, 2022 |
| HP            | Pavilion Laptop 17-ar0xx    | Notebook    | [733654d30d](https://linux-hardware.org/?probe=733654d30d) | Sep 30, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [cc4740fa37](https://linux-hardware.org/?probe=cc4740fa37) | Sep 30, 2022 |
| Notebook      | NJ50_70CU                   | Notebook    | [4914d3ffe1](https://linux-hardware.org/?probe=4914d3ffe1) | Sep 29, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [7bffcb84c2](https://linux-hardware.org/?probe=7bffcb84c2) | Sep 29, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [e3e6ad5c35](https://linux-hardware.org/?probe=e3e6ad5c35) | Sep 29, 2022 |
| Irbis         | NB61 WS001                  | Notebook    | [3fda78e356](https://linux-hardware.org/?probe=3fda78e356) | Sep 29, 2022 |
| HP            | 8055                        | Desktop     | [aa3bd09485](https://linux-hardware.org/?probe=aa3bd09485) | Sep 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [565b94d7f4](https://linux-hardware.org/?probe=565b94d7f4) | Sep 29, 2022 |
| Dell          | Inspiron 1200               | Notebook    | [32dd972d77](https://linux-hardware.org/?probe=32dd972d77) | Sep 29, 2022 |
| HP            | 843C                        | Desktop     | [e27595d303](https://linux-hardware.org/?probe=e27595d303) | Sep 29, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [01ebd7e70b](https://linux-hardware.org/?probe=01ebd7e70b) | Sep 29, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [d2c06711d7](https://linux-hardware.org/?probe=d2c06711d7) | Sep 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [62fc1b721e](https://linux-hardware.org/?probe=62fc1b721e) | Sep 29, 2022 |
| Dell          | Inspiron 3582               | Notebook    | [8cd21b783a](https://linux-hardware.org/?probe=8cd21b783a) | Sep 28, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [defae2e862](https://linux-hardware.org/?probe=defae2e862) | Sep 28, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [c23649cdd4](https://linux-hardware.org/?probe=c23649cdd4) | Sep 28, 2022 |
| Apple         | Mac-F4208EC8 PVT            | Mini pc     | [62d808a3e5](https://linux-hardware.org/?probe=62d808a3e5) | Sep 28, 2022 |
| Dell          | Latitude E6520              | Notebook    | [e228fa6546](https://linux-hardware.org/?probe=e228fa6546) | Sep 28, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [3052bded51](https://linux-hardware.org/?probe=3052bded51) | Sep 28, 2022 |
| ASUSTek       | P5K                         | Desktop     | [2d278ddcdf](https://linux-hardware.org/?probe=2d278ddcdf) | Sep 28, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [19e5b180eb](https://linux-hardware.org/?probe=19e5b180eb) | Sep 28, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f501591d1b](https://linux-hardware.org/?probe=f501591d1b) | Sep 27, 2022 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [5116d1cae9](https://linux-hardware.org/?probe=5116d1cae9) | Sep 27, 2022 |
| Dell          | XPS 8700                    | Desktop     | [19fff8b508](https://linux-hardware.org/?probe=19fff8b508) | Sep 27, 2022 |
| Dell          | 0WN7Y6 A01                  | Desktop     | [356dc77824](https://linux-hardware.org/?probe=356dc77824) | Sep 27, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [016d5e3146](https://linux-hardware.org/?probe=016d5e3146) | Sep 27, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [34287ac52a](https://linux-hardware.org/?probe=34287ac52a) | Sep 27, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [75d51e6237](https://linux-hardware.org/?probe=75d51e6237) | Sep 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [e777d38fbd](https://linux-hardware.org/?probe=e777d38fbd) | Sep 26, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [c45069d56d](https://linux-hardware.org/?probe=c45069d56d) | Sep 26, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [3441e0cac3](https://linux-hardware.org/?probe=3441e0cac3) | Sep 26, 2022 |
| ASUSTek       | X201EP                      | Notebook    | [4e6c202d5d](https://linux-hardware.org/?probe=4e6c202d5d) | Sep 26, 2022 |
| Unknown       | NB-7000                     | Notebook    | [1713526cff](https://linux-hardware.org/?probe=1713526cff) | Sep 25, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [28e086b848](https://linux-hardware.org/?probe=28e086b848) | Sep 25, 2022 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [6a8d9c1d7a](https://linux-hardware.org/?probe=6a8d9c1d7a) | Sep 25, 2022 |
| Gateway       | FMCP7AM                     | Desktop     | [0cb51f3e6f](https://linux-hardware.org/?probe=0cb51f3e6f) | Sep 25, 2022 |
| ASUSTek       | PRO A320M-R WI-FI           | Desktop     | [e760f06cef](https://linux-hardware.org/?probe=e760f06cef) | Sep 25, 2022 |
| Dell          | Inspiron 14-3452            | Notebook    | [bb90844ff6](https://linux-hardware.org/?probe=bb90844ff6) | Sep 25, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [33a0b663ea](https://linux-hardware.org/?probe=33a0b663ea) | Sep 25, 2022 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [d8a451b3e6](https://linux-hardware.org/?probe=d8a451b3e6) | Sep 25, 2022 |
| Dell          | Inspiron 3185               | Notebook    | [561c02f958](https://linux-hardware.org/?probe=561c02f958) | Sep 25, 2022 |
| Acer          | Aspire SW5-012              | Notebook    | [ed8f3f7403](https://linux-hardware.org/?probe=ed8f3f7403) | Sep 25, 2022 |
| ASRock        | QC5000M-ITX/PH              | Desktop     | [571b95c201](https://linux-hardware.org/?probe=571b95c201) | Sep 25, 2022 |
| Acer          | Extensa 5635ZG              | Notebook    | [ade183eadc](https://linux-hardware.org/?probe=ade183eadc) | Sep 24, 2022 |
| HP            | 18E7                        | Desktop     | [71a12280de](https://linux-hardware.org/?probe=71a12280de) | Sep 24, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [fab0eac5a6](https://linux-hardware.org/?probe=fab0eac5a6) | Sep 24, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [dc3a97d467](https://linux-hardware.org/?probe=dc3a97d467) | Sep 23, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [77b578f861](https://linux-hardware.org/?probe=77b578f861) | Sep 23, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [9ccc1b86a7](https://linux-hardware.org/?probe=9ccc1b86a7) | Sep 23, 2022 |
| ASRock        | B85M Pro4                   | Desktop     | [cd75d968d7](https://linux-hardware.org/?probe=cd75d968d7) | Sep 23, 2022 |
| Lenovo        | ThinkPad Edge E530 3259C... | Notebook    | [cdaec9c224](https://linux-hardware.org/?probe=cdaec9c224) | Sep 22, 2022 |
| ASUSTek       | P5K                         | Desktop     | [0ddf0a48dd](https://linux-hardware.org/?probe=0ddf0a48dd) | Sep 22, 2022 |
| Pegatron      | 2ACD                        | Desktop     | [d6270f88cc](https://linux-hardware.org/?probe=d6270f88cc) | Sep 22, 2022 |
| HP            | ENVY Notebook               | Notebook    | [1eef25f6d8](https://linux-hardware.org/?probe=1eef25f6d8) | Sep 22, 2022 |
| HP            | ENVY Notebook               | Notebook    | [b95a98e133](https://linux-hardware.org/?probe=b95a98e133) | Sep 22, 2022 |
| HP            | 8055                        | Desktop     | [c72e0ed04b](https://linux-hardware.org/?probe=c72e0ed04b) | Sep 22, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [00e679e86c](https://linux-hardware.org/?probe=00e679e86c) | Sep 22, 2022 |
| Acer          | Aspire ES1-512              | Notebook    | [318436c7ab](https://linux-hardware.org/?probe=318436c7ab) | Sep 22, 2022 |
| ASUSTek       | 1201PN                      | Notebook    | [3dd4546344](https://linux-hardware.org/?probe=3dd4546344) | Sep 21, 2022 |
| ASUSTek       | 1201PN                      | Notebook    | [080d9c8964](https://linux-hardware.org/?probe=080d9c8964) | Sep 21, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [22bf75699c](https://linux-hardware.org/?probe=22bf75699c) | Sep 21, 2022 |
| ASRock        | A75M-HVS                    | Desktop     | [0f81852612](https://linux-hardware.org/?probe=0f81852612) | Sep 21, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [4421e54d32](https://linux-hardware.org/?probe=4421e54d32) | Sep 21, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [6d0a2986ad](https://linux-hardware.org/?probe=6d0a2986ad) | Sep 21, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [f49e8d08ef](https://linux-hardware.org/?probe=f49e8d08ef) | Sep 20, 2022 |
| Alienware     | 18                          | Notebook    | [91d0153265](https://linux-hardware.org/?probe=91d0153265) | Sep 20, 2022 |
| Dell          | 0D441T A01                  | Desktop     | [c315329853](https://linux-hardware.org/?probe=c315329853) | Sep 20, 2022 |
| MSI           | MS-7260                     | Desktop     | [52d2fa8c71](https://linux-hardware.org/?probe=52d2fa8c71) | Sep 20, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [82b3d89bf9](https://linux-hardware.org/?probe=82b3d89bf9) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [37dbdb48dd](https://linux-hardware.org/?probe=37dbdb48dd) | Sep 20, 2022 |
| Dell          | G15 5515                    | Notebook    | [f308590417](https://linux-hardware.org/?probe=f308590417) | Sep 20, 2022 |
| Dell          | G15 5515                    | Notebook    | [d6a647ab30](https://linux-hardware.org/?probe=d6a647ab30) | Sep 20, 2022 |
| HP            | Pavilion g7                 | Notebook    | [d51d3d282a](https://linux-hardware.org/?probe=d51d3d282a) | Sep 20, 2022 |
| Dell          | Latitude D610               | Notebook    | [47e0f0fa27](https://linux-hardware.org/?probe=47e0f0fa27) | Sep 19, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [9417681a63](https://linux-hardware.org/?probe=9417681a63) | Sep 19, 2022 |
| Lenovo        | ThinkPad 11e 20DAS09U00     | Notebook    | [81bd748796](https://linux-hardware.org/?probe=81bd748796) | Sep 19, 2022 |
| Lenovo        | ThinkCentre M71e 3157AE2    | Desktop     | [9022058466](https://linux-hardware.org/?probe=9022058466) | Sep 19, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d3140eaa89](https://linux-hardware.org/?probe=d3140eaa89) | Sep 19, 2022 |
| Alienware     | 18                          | Notebook    | [fda9eabd7e](https://linux-hardware.org/?probe=fda9eabd7e) | Sep 18, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [bceb6698c2](https://linux-hardware.org/?probe=bceb6698c2) | Sep 18, 2022 |
| Microtech     | CoreBook                    | Notebook    | [6b1a53d2c2](https://linux-hardware.org/?probe=6b1a53d2c2) | Sep 18, 2022 |
| HP            | 0AA8h                       | Desktop     | [c79bdb21ed](https://linux-hardware.org/?probe=c79bdb21ed) | Sep 18, 2022 |
| Ematic        | EWT118                      | Notebook    | [41670ebd30](https://linux-hardware.org/?probe=41670ebd30) | Sep 18, 2022 |
| Dell          | Latitude D610               | Notebook    | [df13ed7396](https://linux-hardware.org/?probe=df13ed7396) | Sep 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a5d838868a](https://linux-hardware.org/?probe=a5d838868a) | Sep 18, 2022 |
| Lenovo        | ThinkCentre M58e 7298A76    | Desktop     | [4775ccd67f](https://linux-hardware.org/?probe=4775ccd67f) | Sep 18, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [24534d00db](https://linux-hardware.org/?probe=24534d00db) | Sep 17, 2022 |
| Dell          | Latitude E6510              | Notebook    | [ee09885560](https://linux-hardware.org/?probe=ee09885560) | Sep 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [e7bb3017fb](https://linux-hardware.org/?probe=e7bb3017fb) | Sep 16, 2022 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [c81727b775](https://linux-hardware.org/?probe=c81727b775) | Sep 16, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [5620510083](https://linux-hardware.org/?probe=5620510083) | Sep 16, 2022 |
| Dell          | Latitude E4300              | Notebook    | [b3c04d8a81](https://linux-hardware.org/?probe=b3c04d8a81) | Sep 16, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [eeb58ef0f2](https://linux-hardware.org/?probe=eeb58ef0f2) | Sep 15, 2022 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [258c624b3b](https://linux-hardware.org/?probe=258c624b3b) | Sep 15, 2022 |
| Dell          | Latitude D630               | Notebook    | [b898e91e58](https://linux-hardware.org/?probe=b898e91e58) | Sep 15, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [875435f3f0](https://linux-hardware.org/?probe=875435f3f0) | Sep 15, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [bd34f35e50](https://linux-hardware.org/?probe=bd34f35e50) | Sep 15, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [aeac7cfb74](https://linux-hardware.org/?probe=aeac7cfb74) | Sep 14, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [32884ec101](https://linux-hardware.org/?probe=32884ec101) | Sep 14, 2022 |
| Dell          | 0TW904 A01                  | Desktop     | [141188a631](https://linux-hardware.org/?probe=141188a631) | Sep 14, 2022 |
| HP            | EliteBook 820 G2            | Notebook    | [199f191441](https://linux-hardware.org/?probe=199f191441) | Sep 14, 2022 |
| Lenovo        | IdeaPad 3 15ADA6 82KR       | Notebook    | [676dbc76db](https://linux-hardware.org/?probe=676dbc76db) | Sep 13, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [b1b929517d](https://linux-hardware.org/?probe=b1b929517d) | Sep 13, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [3c13816886](https://linux-hardware.org/?probe=3c13816886) | Sep 13, 2022 |
| Samsung       | 800G5M/800G5W               | Notebook    | [ad3cd5381f](https://linux-hardware.org/?probe=ad3cd5381f) | Sep 13, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [b404f51fbe](https://linux-hardware.org/?probe=b404f51fbe) | Sep 12, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [ca9a099cf6](https://linux-hardware.org/?probe=ca9a099cf6) | Sep 12, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [25c2b764a6](https://linux-hardware.org/?probe=25c2b764a6) | Sep 12, 2022 |
| Zinox Tech... | x64-Based PC                | Tablet      | [4618d27b09](https://linux-hardware.org/?probe=4618d27b09) | Sep 11, 2022 |
| Dell          | Latitude E7240              | Notebook    | [72a8c650c5](https://linux-hardware.org/?probe=72a8c650c5) | Sep 11, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [b8f3a58a03](https://linux-hardware.org/?probe=b8f3a58a03) | Sep 11, 2022 |
| Gigabyte      | G1.Sniper Z97               | Desktop     | [445e54016b](https://linux-hardware.org/?probe=445e54016b) | Sep 11, 2022 |
| Gigabyte      | P64V7                       | Notebook    | [b9d2c998be](https://linux-hardware.org/?probe=b9d2c998be) | Sep 11, 2022 |
| UMAX          | VisionBook N14G Plus        | Notebook    | [6d05deca49](https://linux-hardware.org/?probe=6d05deca49) | Sep 11, 2022 |
| HP            | Pavilion dv6000 (RP986EA... | Notebook    | [f20de20683](https://linux-hardware.org/?probe=f20de20683) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [0701918099](https://linux-hardware.org/?probe=0701918099) | Sep 11, 2022 |
| ECS           | Iris8                       | Desktop     | [dcfb9e172d](https://linux-hardware.org/?probe=dcfb9e172d) | Sep 11, 2022 |
| HP            | 0A54h                       | Desktop     | [2c88c7fd30](https://linux-hardware.org/?probe=2c88c7fd30) | Sep 10, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [e6bf2b7f3f](https://linux-hardware.org/?probe=e6bf2b7f3f) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [d13cf99728](https://linux-hardware.org/?probe=d13cf99728) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1e43753d7a](https://linux-hardware.org/?probe=1e43753d7a) | Sep 10, 2022 |
| MSI           | 2AE0                        | Desktop     | [a2b046dd4e](https://linux-hardware.org/?probe=a2b046dd4e) | Sep 10, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [c027a7cf99](https://linux-hardware.org/?probe=c027a7cf99) | Sep 10, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [4e96c157b7](https://linux-hardware.org/?probe=4e96c157b7) | Sep 10, 2022 |
| HP            | 3031h                       | Desktop     | [ea434d67b5](https://linux-hardware.org/?probe=ea434d67b5) | Sep 10, 2022 |
| HP            | 3031h                       | Desktop     | [feddf42c9f](https://linux-hardware.org/?probe=feddf42c9f) | Sep 10, 2022 |
| ECS           | Iris8                       | Desktop     | [29bc0560b4](https://linux-hardware.org/?probe=29bc0560b4) | Sep 10, 2022 |
| AZW           | Z83-V                       | Notebook    | [70e8dba2ef](https://linux-hardware.org/?probe=70e8dba2ef) | Sep 10, 2022 |
| AZW           | Z83-V                       | Notebook    | [622725ab19](https://linux-hardware.org/?probe=622725ab19) | Sep 10, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [a41158c2cc](https://linux-hardware.org/?probe=a41158c2cc) | Sep 10, 2022 |
| HP            | 0AA8h                       | Desktop     | [4e9a1e883c](https://linux-hardware.org/?probe=4e9a1e883c) | Sep 09, 2022 |
| Toshiba       | Satellite P200              | Notebook    | [c49fec0796](https://linux-hardware.org/?probe=c49fec0796) | Sep 09, 2022 |
| Medion        | Akoya E1318T                | Notebook    | [749a12fd63](https://linux-hardware.org/?probe=749a12fd63) | Sep 09, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [678759289b](https://linux-hardware.org/?probe=678759289b) | Sep 09, 2022 |
| Acer          | Aspire C22-820              | All in one  | [7b21589632](https://linux-hardware.org/?probe=7b21589632) | Sep 09, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [7c3cdfba24](https://linux-hardware.org/?probe=7c3cdfba24) | Sep 08, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [e11963681c](https://linux-hardware.org/?probe=e11963681c) | Sep 08, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [db80996c7a](https://linux-hardware.org/?probe=db80996c7a) | Sep 08, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [ebf0bfea05](https://linux-hardware.org/?probe=ebf0bfea05) | Sep 08, 2022 |
| Dell          | Latitude E5420              | Notebook    | [b80d26540d](https://linux-hardware.org/?probe=b80d26540d) | Sep 08, 2022 |
| ASUSTek       | UX331UA                     | Notebook    | [e1e0acfdf3](https://linux-hardware.org/?probe=e1e0acfdf3) | Sep 08, 2022 |
| Dell          | Latitude E4300              | Notebook    | [5d3a9edf5d](https://linux-hardware.org/?probe=5d3a9edf5d) | Sep 07, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [2619e261d1](https://linux-hardware.org/?probe=2619e261d1) | Sep 07, 2022 |
| Lenovo        | ThinkPad E570 20H50047US    | Notebook    | [70b198055e](https://linux-hardware.org/?probe=70b198055e) | Sep 07, 2022 |
| Intel         | SKYBAY                      | Desktop     | [b667cf66e8](https://linux-hardware.org/?probe=b667cf66e8) | Sep 07, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [dd20f0351c](https://linux-hardware.org/?probe=dd20f0351c) | Sep 06, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [3aca46f88b](https://linux-hardware.org/?probe=3aca46f88b) | Sep 06, 2022 |
| HP            | 15                          | Notebook    | [c02361a2ff](https://linux-hardware.org/?probe=c02361a2ff) | Sep 06, 2022 |
| ASUSTek       | A88X-GAMER                  | Desktop     | [15fe45edd7](https://linux-hardware.org/?probe=15fe45edd7) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [44c27d1083](https://linux-hardware.org/?probe=44c27d1083) | Sep 06, 2022 |
| Lenovo        | G400s VILG1                 | Notebook    | [ec3283d49b](https://linux-hardware.org/?probe=ec3283d49b) | Sep 06, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [92ff48d462](https://linux-hardware.org/?probe=92ff48d462) | Sep 06, 2022 |
| HP            | 2AF7                        | Desktop     | [9b7ccd5aa0](https://linux-hardware.org/?probe=9b7ccd5aa0) | Sep 06, 2022 |
| HP            | Pavilion g7                 | Notebook    | [5ed29a7629](https://linux-hardware.org/?probe=5ed29a7629) | Sep 05, 2022 |
| Dell          | 0HY9JP A02                  | Desktop     | [7cbf141461](https://linux-hardware.org/?probe=7cbf141461) | Sep 05, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [88c4e0664a](https://linux-hardware.org/?probe=88c4e0664a) | Sep 05, 2022 |
| HP            | G62                         | Notebook    | [a3f84f3bf8](https://linux-hardware.org/?probe=a3f84f3bf8) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [d0ec4eb9cc](https://linux-hardware.org/?probe=d0ec4eb9cc) | Sep 05, 2022 |
| Acer          | Aspire 5750G                | Notebook    | [e7061e11ff](https://linux-hardware.org/?probe=e7061e11ff) | Sep 04, 2022 |
| Lenovo        | G560 20042                  | Notebook    | [c661e65b46](https://linux-hardware.org/?probe=c661e65b46) | Sep 04, 2022 |
| Lenovo        | G560 20042                  | Notebook    | [ad86775475](https://linux-hardware.org/?probe=ad86775475) | Sep 04, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [eec792ef79](https://linux-hardware.org/?probe=eec792ef79) | Sep 04, 2022 |
| HP            | Pavilion dv6500             | Notebook    | [0751d35153](https://linux-hardware.org/?probe=0751d35153) | Sep 04, 2022 |
| ASRock        | B550M/ac                    | Desktop     | [b8ccaa27ef](https://linux-hardware.org/?probe=b8ccaa27ef) | Sep 04, 2022 |
| HP            | 821D                        | Desktop     | [459bdd177e](https://linux-hardware.org/?probe=459bdd177e) | Sep 03, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [079d33f9b2](https://linux-hardware.org/?probe=079d33f9b2) | Sep 03, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [2ae6d7c950](https://linux-hardware.org/?probe=2ae6d7c950) | Sep 03, 2022 |
| HP            | 620                         | Notebook    | [096486e01d](https://linux-hardware.org/?probe=096486e01d) | Sep 03, 2022 |
| Itautec       | Infoway                     | Notebook    | [d207af3252](https://linux-hardware.org/?probe=d207af3252) | Sep 03, 2022 |
| Itautec       | Infoway                     | Notebook    | [737122a0d1](https://linux-hardware.org/?probe=737122a0d1) | Sep 03, 2022 |
| HP            | 87D6 SMVB                   | Desktop     | [e597d54472](https://linux-hardware.org/?probe=e597d54472) | Sep 03, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [c74752a0d2](https://linux-hardware.org/?probe=c74752a0d2) | Sep 02, 2022 |
| MSI           | H97 GAMING 3                | Desktop     | [a5fb8d7651](https://linux-hardware.org/?probe=a5fb8d7651) | Sep 02, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [63e2adf3a9](https://linux-hardware.org/?probe=63e2adf3a9) | Sep 02, 2022 |
| MSI           | MS-B9201                    | Desktop     | [7bbae05d63](https://linux-hardware.org/?probe=7bbae05d63) | Sep 01, 2022 |
| MSI           | MS-B9201                    | Desktop     | [0d04798699](https://linux-hardware.org/?probe=0d04798699) | Sep 01, 2022 |
| Positivo      | C14CR01                     | Notebook    | [ff4d1d45b7](https://linux-hardware.org/?probe=ff4d1d45b7) | Sep 01, 2022 |
| Positivo      | C14CR01                     | Notebook    | [d1fc217886](https://linux-hardware.org/?probe=d1fc217886) | Sep 01, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [2eb780855d](https://linux-hardware.org/?probe=2eb780855d) | Sep 01, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [f4d5b9fc69](https://linux-hardware.org/?probe=f4d5b9fc69) | Aug 31, 2022 |
| Intel         | powered classmate PC        | Notebook    | [ed36baccf9](https://linux-hardware.org/?probe=ed36baccf9) | Aug 31, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [82cda7dfe9](https://linux-hardware.org/?probe=82cda7dfe9) | Aug 31, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [194290f42c](https://linux-hardware.org/?probe=194290f42c) | Aug 31, 2022 |
| MSI           | H410M PRO                   | Desktop     | [e1184c4522](https://linux-hardware.org/?probe=e1184c4522) | Aug 31, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [13454a57f9](https://linux-hardware.org/?probe=13454a57f9) | Aug 31, 2022 |
| Dell          | Inspiron 15-3552            | Notebook    | [8e2cd928f3](https://linux-hardware.org/?probe=8e2cd928f3) | Aug 31, 2022 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [836644c18b](https://linux-hardware.org/?probe=836644c18b) | Aug 31, 2022 |
| Dell          | 0GXM1W A00                  | Desktop     | [b358b1d32b](https://linux-hardware.org/?probe=b358b1d32b) | Aug 31, 2022 |
| HP            | 2B38                        | Desktop     | [9170225d70](https://linux-hardware.org/?probe=9170225d70) | Aug 30, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | Desktop     | [8712171422](https://linux-hardware.org/?probe=8712171422) | Aug 30, 2022 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [eb74fdbbbc](https://linux-hardware.org/?probe=eb74fdbbbc) | Aug 30, 2022 |
| Dell          | 0R092H                      | Desktop     | [85871600b3](https://linux-hardware.org/?probe=85871600b3) | Aug 30, 2022 |
| HP            | ProBook 6470b               | Notebook    | [2cbe458c94](https://linux-hardware.org/?probe=2cbe458c94) | Aug 30, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [a96a893eac](https://linux-hardware.org/?probe=a96a893eac) | Aug 30, 2022 |
| JGINYUE       | B85M VH PLUS V1.0           | Desktop     | [f065870080](https://linux-hardware.org/?probe=f065870080) | Aug 30, 2022 |
| Acer          | Aspire SW5-271              | Notebook    | [3446f93f1d](https://linux-hardware.org/?probe=3446f93f1d) | Aug 29, 2022 |
| Samsung       | 300E5M/300E5L               | Notebook    | [6f920f9002](https://linux-hardware.org/?probe=6f920f9002) | Aug 29, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [be30fd63a0](https://linux-hardware.org/?probe=be30fd63a0) | Aug 29, 2022 |
| Microsoft     | Surface Pro 6               | Tablet      | [135f83007e](https://linux-hardware.org/?probe=135f83007e) | Aug 29, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [45bba02b35](https://linux-hardware.org/?probe=45bba02b35) | Aug 29, 2022 |
| MSI           | B250M PRO-VD                | Desktop     | [d462e3b9d0](https://linux-hardware.org/?probe=d462e3b9d0) | Aug 29, 2022 |
| Dell          | Latitude E5440              | Notebook    | [b0d92d186f](https://linux-hardware.org/?probe=b0d92d186f) | Aug 29, 2022 |
| HP            | EW7-I7D22875GR1             | Notebook    | [307b75624e](https://linux-hardware.org/?probe=307b75624e) | Aug 29, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [eaa574481f](https://linux-hardware.org/?probe=eaa574481f) | Aug 29, 2022 |
| Lenovo        | ThinkPad L440 20ASA1V8BP    | Notebook    | [64f71278c7](https://linux-hardware.org/?probe=64f71278c7) | Aug 28, 2022 |
| HP            | 339A                        | Desktop     | [7338bebb05](https://linux-hardware.org/?probe=7338bebb05) | Aug 28, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [023204fa1f](https://linux-hardware.org/?probe=023204fa1f) | Aug 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [be59676867](https://linux-hardware.org/?probe=be59676867) | Aug 28, 2022 |
| WIPRO         | G31T-M                      | Desktop     | [51cea718eb](https://linux-hardware.org/?probe=51cea718eb) | Aug 28, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [04aec7a28a](https://linux-hardware.org/?probe=04aec7a28a) | Aug 28, 2022 |
| Google        | Butterfly                   | Notebook    | [df8fafaf3b](https://linux-hardware.org/?probe=df8fafaf3b) | Aug 28, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [134adccc85](https://linux-hardware.org/?probe=134adccc85) | Aug 27, 2022 |
| GHIA          | 2 en 1                      | Tablet      | [5ed07e6854](https://linux-hardware.org/?probe=5ed07e6854) | Aug 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [9a05044c38](https://linux-hardware.org/?probe=9a05044c38) | Aug 27, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [c8eb396b68](https://linux-hardware.org/?probe=c8eb396b68) | Aug 26, 2022 |
| ASUSTek       | ZenBook UX425UG_Q408UG      | Notebook    | [5b80fb349f](https://linux-hardware.org/?probe=5b80fb349f) | Aug 26, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [7c9f388153](https://linux-hardware.org/?probe=7c9f388153) | Aug 26, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [d1bb410d06](https://linux-hardware.org/?probe=d1bb410d06) | Aug 26, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [c6fc39489e](https://linux-hardware.org/?probe=c6fc39489e) | Aug 26, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [b56c1d75a6](https://linux-hardware.org/?probe=b56c1d75a6) | Aug 25, 2022 |
| Framework     | Laptop                      | Notebook    | [87e09551b3](https://linux-hardware.org/?probe=87e09551b3) | Aug 25, 2022 |
| ASUSTek       | SABERTOOTH Z87              | Desktop     | [02072aee33](https://linux-hardware.org/?probe=02072aee33) | Aug 25, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [dad1ede2be](https://linux-hardware.org/?probe=dad1ede2be) | Aug 25, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [5d03f69f35](https://linux-hardware.org/?probe=5d03f69f35) | Aug 25, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [8f13ff6ebd](https://linux-hardware.org/?probe=8f13ff6ebd) | Aug 24, 2022 |
| Dell          | Latitude E7240              | Notebook    | [0e15063cb3](https://linux-hardware.org/?probe=0e15063cb3) | Aug 24, 2022 |
| Dell          | Inspiron M5030              | Notebook    | [59eec9a80d](https://linux-hardware.org/?probe=59eec9a80d) | Aug 24, 2022 |
| Framework     | Laptop                      | Notebook    | [3c4bab3769](https://linux-hardware.org/?probe=3c4bab3769) | Aug 24, 2022 |
| Gigabyte      | 970-GAMING                  | Desktop     | [faa79b7d62](https://linux-hardware.org/?probe=faa79b7d62) | Aug 24, 2022 |
| HP            | 2AFB                        | Desktop     | [ea3ce3f8dd](https://linux-hardware.org/?probe=ea3ce3f8dd) | Aug 24, 2022 |
| Toshiba       | Satellite L855              | Notebook    | [73de62c6c7](https://linux-hardware.org/?probe=73de62c6c7) | Aug 24, 2022 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [b9ac5d4051](https://linux-hardware.org/?probe=b9ac5d4051) | Aug 23, 2022 |
| Gigabyte      | H61M-D2H-USB3               | Desktop     | [eae2c82e26](https://linux-hardware.org/?probe=eae2c82e26) | Aug 23, 2022 |
| Dell          | Inspiron M5030              | Notebook    | [a43c618dbb](https://linux-hardware.org/?probe=a43c618dbb) | Aug 23, 2022 |
| HP            | Laptop 14-dq4xxx            | Notebook    | [8171eb84c2](https://linux-hardware.org/?probe=8171eb84c2) | Aug 23, 2022 |
| Alienware     | 15 R4                       | Notebook    | [f53260e0c2](https://linux-hardware.org/?probe=f53260e0c2) | Aug 23, 2022 |
| Dell          | Inspiron 5770               | Notebook    | [49314a1dfe](https://linux-hardware.org/?probe=49314a1dfe) | Aug 23, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [fc9bb1e6fa](https://linux-hardware.org/?probe=fc9bb1e6fa) | Aug 23, 2022 |
| HP            | 2AF7                        | Desktop     | [fbc1710ad8](https://linux-hardware.org/?probe=fbc1710ad8) | Aug 22, 2022 |
| MSI           | X99S GAMING 7               | Desktop     | [f729654c4a](https://linux-hardware.org/?probe=f729654c4a) | Aug 22, 2022 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [f2f76737ad](https://linux-hardware.org/?probe=f2f76737ad) | Aug 22, 2022 |
| Samsung       | Galaxy Book 12 LTE          | Tablet      | [e7f6559a38](https://linux-hardware.org/?probe=e7f6559a38) | Aug 21, 2022 |
| Dell          | 0C27VV A03                  | Desktop     | [4e894e1897](https://linux-hardware.org/?probe=4e894e1897) | Aug 21, 2022 |
| ZOTAC         | ZBOX-CI323NANO              | Mini pc     | [a8bf4ad2a0](https://linux-hardware.org/?probe=a8bf4ad2a0) | Aug 21, 2022 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [01416789ab](https://linux-hardware.org/?probe=01416789ab) | Aug 21, 2022 |
| Alienware     | 15 R3                       | Notebook    | [109d7cb528](https://linux-hardware.org/?probe=109d7cb528) | Aug 21, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ced2388c29](https://linux-hardware.org/?probe=ced2388c29) | Aug 21, 2022 |
| Positivo      | C14CU51                     | Notebook    | [288c810d97](https://linux-hardware.org/?probe=288c810d97) | Aug 21, 2022 |
| ASUSTek       | X542BA                      | Notebook    | [7e86736ebc](https://linux-hardware.org/?probe=7e86736ebc) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2055A38       | Notebook    | [f37fce9f01](https://linux-hardware.org/?probe=f37fce9f01) | Aug 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4dc3a452d9](https://linux-hardware.org/?probe=4dc3a452d9) | Aug 19, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [f429863c5f](https://linux-hardware.org/?probe=f429863c5f) | Aug 19, 2022 |
| ASUSTek       | ProArt B660-CREATOR D4      | Desktop     | [0b9e6d6ad9](https://linux-hardware.org/?probe=0b9e6d6ad9) | Aug 19, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [ec1b67985f](https://linux-hardware.org/?probe=ec1b67985f) | Aug 19, 2022 |
| GPU Compan... | GWTN156-11                  | Notebook    | [c22aa4377d](https://linux-hardware.org/?probe=c22aa4377d) | Aug 19, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [6865f5ed0b](https://linux-hardware.org/?probe=6865f5ed0b) | Aug 19, 2022 |
| BESSTAR Te... | UM350                       | Desktop     | [c7bb6b56fb](https://linux-hardware.org/?probe=c7bb6b56fb) | Aug 18, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [e03daeba5f](https://linux-hardware.org/?probe=e03daeba5f) | Aug 18, 2022 |
| MSI           | MS-AE611 100                | All in one  | [336e0dfd12](https://linux-hardware.org/?probe=336e0dfd12) | Aug 18, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [a54395e915](https://linux-hardware.org/?probe=a54395e915) | Aug 18, 2022 |
| MSI           | Creator Z16 Hiroshi F A1... | Notebook    | [e056c24d1d](https://linux-hardware.org/?probe=e056c24d1d) | Aug 18, 2022 |
| HP            | 14                          | Notebook    | [0f2cde73bb](https://linux-hardware.org/?probe=0f2cde73bb) | Aug 17, 2022 |
| ASUSTek       | X756UQ                      | Notebook    | [9b30268acb](https://linux-hardware.org/?probe=9b30268acb) | Aug 17, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [8ea659cd8c](https://linux-hardware.org/?probe=8ea659cd8c) | Aug 17, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [ab3425dd99](https://linux-hardware.org/?probe=ab3425dd99) | Aug 17, 2022 |
| Dell          | Latitude E6420              | Notebook    | [3e7ce84c59](https://linux-hardware.org/?probe=3e7ce84c59) | Aug 17, 2022 |
| ASUSTek       | K54C                        | Notebook    | [e10b52270f](https://linux-hardware.org/?probe=e10b52270f) | Aug 17, 2022 |
| ASUSTek       | PRIME H370-A                | Desktop     | [da477254e7](https://linux-hardware.org/?probe=da477254e7) | Aug 16, 2022 |
| Gigabyte      | M4HM87P-00                  | Desktop     | [5bb7e42eae](https://linux-hardware.org/?probe=5bb7e42eae) | Aug 16, 2022 |
| HP            | Pavilion dv9700             | Notebook    | [7c3e324e4f](https://linux-hardware.org/?probe=7c3e324e4f) | Aug 16, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [58a439770d](https://linux-hardware.org/?probe=58a439770d) | Aug 15, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [e80596ea44](https://linux-hardware.org/?probe=e80596ea44) | Aug 15, 2022 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [01beed2be8](https://linux-hardware.org/?probe=01beed2be8) | Aug 15, 2022 |
| HP            | 339A                        | Desktop     | [c3e5458c9a](https://linux-hardware.org/?probe=c3e5458c9a) | Aug 15, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [5171fd1732](https://linux-hardware.org/?probe=5171fd1732) | Aug 15, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [08fa90340d](https://linux-hardware.org/?probe=08fa90340d) | Aug 14, 2022 |
| MAXSUN        | MS-TZZ A520M                | Desktop     | [aa844d0dce](https://linux-hardware.org/?probe=aa844d0dce) | Aug 14, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [f9d6b2f915](https://linux-hardware.org/?probe=f9d6b2f915) | Aug 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2257302110](https://linux-hardware.org/?probe=2257302110) | Aug 14, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [47632d043c](https://linux-hardware.org/?probe=47632d043c) | Aug 14, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [58d97fbc16](https://linux-hardware.org/?probe=58d97fbc16) | Aug 14, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [0006dc34cf](https://linux-hardware.org/?probe=0006dc34cf) | Aug 14, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [0c80c167e4](https://linux-hardware.org/?probe=0c80c167e4) | Aug 13, 2022 |
| HP            | EliteBook 6930p             | Notebook    | [7267931d03](https://linux-hardware.org/?probe=7267931d03) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fb405688fe](https://linux-hardware.org/?probe=fb405688fe) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [62a1acd85d](https://linux-hardware.org/?probe=62a1acd85d) | Aug 13, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [9321e2df1a](https://linux-hardware.org/?probe=9321e2df1a) | Aug 13, 2022 |
| Lenovo        | IdeaPad S145-14IIL 81W6     | Notebook    | [d08cbbc3d8](https://linux-hardware.org/?probe=d08cbbc3d8) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [3dcb75072e](https://linux-hardware.org/?probe=3dcb75072e) | Aug 12, 2022 |
| ASUSTek       | A88X-PRO                    | Desktop     | [399f7ec1da](https://linux-hardware.org/?probe=399f7ec1da) | Aug 12, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [b3e408ce95](https://linux-hardware.org/?probe=b3e408ce95) | Aug 12, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [1fe351cfab](https://linux-hardware.org/?probe=1fe351cfab) | Aug 12, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [3d37c741c8](https://linux-hardware.org/?probe=3d37c741c8) | Aug 12, 2022 |
| Notebook      | NJ50GU                      | Notebook    | [59d1efda98](https://linux-hardware.org/?probe=59d1efda98) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | Notebook    | [4549b417bf](https://linux-hardware.org/?probe=4549b417bf) | Aug 12, 2022 |
| MSI           | Vector GP76 12UH            | Notebook    | [8bbf4dd310](https://linux-hardware.org/?probe=8bbf4dd310) | Aug 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [ddeddb54bf](https://linux-hardware.org/?probe=ddeddb54bf) | Aug 12, 2022 |
| Unknown       | Unknown                     | Notebook    | [b19949df5a](https://linux-hardware.org/?probe=b19949df5a) | Aug 12, 2022 |
| ASUSTek       | P5GC-MX                     | Desktop     | [346a48750b](https://linux-hardware.org/?probe=346a48750b) | Aug 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [dbbd0524d8](https://linux-hardware.org/?probe=dbbd0524d8) | Aug 12, 2022 |
| HP            | Pavilion 15                 | Notebook    | [462769d45e](https://linux-hardware.org/?probe=462769d45e) | Aug 11, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| Zorin 16 | 2374      | 57.05%  |
| Zorin 15 | 1591      | 38.24%  |
| Zorin 12 | 196       | 4.71%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name  | Computers | Percent |
|-------|-----------|---------|
| Zorin | 4148      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.11.0-38-generic | 176       | 3.77%   |
| 5.11.0-27-generic | 154       | 3.3%    |
| 5.15.0-46-generic | 151       | 3.23%   |
| 5.15.0-56-generic | 150       | 3.21%   |
| 5.15.0-52-generic | 142       | 3.04%   |
| 5.11.0-40-generic | 124       | 2.65%   |
| 5.13.0-30-generic | 123       | 2.63%   |
| 5.13.0-39-generic | 120       | 2.57%   |
| 5.3.0-40-generic  | 110       | 2.35%   |
| 5.11.0-41-generic | 107       | 2.29%   |
| 5.11.0-37-generic | 107       | 2.29%   |
| 5.11.0-43-generic | 101       | 2.16%   |
| 5.4.0-42-generic  | 99        | 2.12%   |
| 5.15.0-48-generic | 94        | 2.01%   |
| 5.11.0-34-generic | 94        | 2.01%   |
| 5.13.0-40-generic | 89        | 1.91%   |
| 5.0.0-37-generic  | 79        | 1.69%   |
| 5.15.0-53-generic | 77        | 1.65%   |
| 5.13.0-44-generic | 76        | 1.63%   |
| 5.15.0-41-generic | 74        | 1.58%   |
| 5.13.0-35-generic | 74        | 1.58%   |
| 5.3.0-46-generic  | 73        | 1.56%   |
| 5.13.0-28-generic | 71        | 1.52%   |
| 5.3.0-51-generic  | 65        | 1.39%   |
| 5.4.0-47-generic  | 60        | 1.28%   |
| 5.13.0-52-generic | 59        | 1.26%   |
| 5.13.0-27-generic | 59        | 1.26%   |
| 5.3.0-53-generic  | 54        | 1.16%   |
| 5.13.0-41-generic | 54        | 1.16%   |
| 5.4.0-58-generic  | 53        | 1.13%   |
| 5.3.0-42-generic  | 52        | 1.11%   |
| 5.4.0-48-generic  | 48        | 1.03%   |
| 5.4.0-65-generic  | 46        | 0.98%   |
| 5.4.0-72-generic  | 45        | 0.96%   |
| 5.4.0-45-generic  | 45        | 0.96%   |
| 5.4.0-80-generic  | 41        | 0.88%   |
| 5.13.0-51-generic | 41        | 0.88%   |
| 5.15.0-43-generic | 40        | 0.86%   |
| 5.11.0-36-generic | 39        | 0.83%   |
| 5.3.0-62-generic  | 38        | 0.81%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 944       | 21.79%  |
| 5.4.0   | 913       | 21.08%  |
| 5.13.0  | 761       | 17.57%  |
| 5.15.0  | 698       | 16.11%  |
| 5.3.0   | 487       | 11.24%  |
| 4.15.0  | 189       | 4.36%   |
| 5.0.0   | 153       | 3.53%   |
| 4.18.0  | 75        | 1.73%   |
| 5.8.0   | 53        | 1.22%   |
| 5.14.0  | 8         | 0.18%   |
| 4.4.0   | 6         | 0.14%   |
| 5.7.1   | 3         | 0.07%   |
| 5.7.0   | 2         | 0.05%   |
| 5.6.0   | 2         | 0.05%   |
| 5.19.12 | 2         | 0.05%   |
| 5.17.5  | 2         | 0.05%   |
| 5.17.1  | 2         | 0.05%   |
| 5.16.0  | 2         | 0.05%   |
| 5.10.0  | 2         | 0.05%   |
| 4.13.0  | 2         | 0.05%   |
| 6.0.8   | 1         | 0.02%   |
| 6.0.0   | 1         | 0.02%   |
| 5.9.12  | 1         | 0.02%   |
| 5.9.0   | 1         | 0.02%   |
| 5.8.5   | 1         | 0.02%   |
| 5.7.17  | 1         | 0.02%   |
| 5.4.180 | 1         | 0.02%   |
| 5.4.1   | 1         | 0.02%   |
| 5.19.9  | 1         | 0.02%   |
| 5.19.6  | 1         | 0.02%   |
| 5.19.2  | 1         | 0.02%   |
| 5.19.14 | 1         | 0.02%   |
| 5.19.1  | 1         | 0.02%   |
| 5.19.0  | 1         | 0.02%   |
| 5.18.6  | 1         | 0.02%   |
| 5.18.15 | 1         | 0.02%   |
| 5.17.9  | 1         | 0.02%   |
| 5.16.5  | 1         | 0.02%   |
| 5.16.14 | 1         | 0.02%   |
| 5.16.12 | 1         | 0.02%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 944       | 21.79%  |
| 5.4     | 915       | 21.12%  |
| 5.13    | 762       | 17.59%  |
| 5.15    | 701       | 16.18%  |
| 5.3     | 487       | 11.24%  |
| 4.15    | 189       | 4.36%   |
| 5.0     | 153       | 3.53%   |
| 4.18    | 75        | 1.73%   |
| 5.8     | 54        | 1.25%   |
| 5.19    | 8         | 0.18%   |
| 5.14    | 8         | 0.18%   |
| 5.7     | 6         | 0.14%   |
| 4.4     | 6         | 0.14%   |
| 5.17    | 5         | 0.12%   |
| 5.16    | 5         | 0.12%   |
| 5.10    | 4         | 0.09%   |
| 6.0     | 2         | 0.05%   |
| 5.9     | 2         | 0.05%   |
| 5.6     | 2         | 0.05%   |
| 5.18    | 2         | 0.05%   |
| 4.13    | 2         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 3783      | 91.13%  |
| i686   | 368       | 8.87%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 3019      | 71.86%  |
| XFCE       | 864       | 20.57%  |
| Unknown    | 295       | 7.02%   |
| X-Cinnamon | 7         | 0.17%   |
| KDE        | 4         | 0.1%    |
| Unity      | 3         | 0.07%   |
| KDE5       | 2         | 0.05%   |
| Cinnamon   | 2         | 0.05%   |
| Budgie     | 2         | 0.05%   |
| MATE       | 1         | 0.02%   |
| LXDE       | 1         | 0.02%   |
| i3         | 1         | 0.02%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 3940      | 94.21%  |
| Unknown | 182       | 4.35%   |
| Wayland | 59        | 1.41%   |
| Tty     | 1         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3459      | 82.08%  |
| GDM3    | 296       | 7.02%   |
| GDM     | 264       | 6.26%   |
| LightDM | 180       | 4.27%   |
| TDM     | 11        | 0.26%   |
| SDDM    | 3         | 0.07%   |
| LXDM    | 1         | 0.02%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1499      | 35.85%  |
| de_DE   | 322       | 7.7%    |
| pt_BR   | 279       | 6.67%   |
| en_GB   | 260       | 6.22%   |
| Unknown | 230       | 5.5%    |
| it_IT   | 141       | 3.37%   |
| en_CA   | 117       | 2.8%    |
| fr_FR   | 113       | 2.7%    |
| en_IN   | 113       | 2.7%    |
| es_ES   | 108       | 2.58%   |
| pl_PL   | 91        | 2.18%   |
| en_AU   | 77        | 1.84%   |
| nl_NL   | 65        | 1.55%   |
| es_MX   | 59        | 1.41%   |
| ru_RU   | 58        | 1.39%   |
| es_AR   | 47        | 1.12%   |
| pt_PT   | 45        | 1.08%   |
| en_ZA   | 38        | 0.91%   |
| cs_CZ   | 38        | 0.91%   |
| tr_TR   | 27        | 0.65%   |
| C       | 27        | 0.65%   |
| sv_SE   | 25        | 0.6%    |
| hu_HU   | 25        | 0.6%    |
| es_CL   | 25        | 0.6%    |
| fr_CA   | 21        | 0.5%    |
| es_CO   | 20        | 0.48%   |
| en_NZ   | 20        | 0.48%   |
| ja_JP   | 17        | 0.41%   |
| nl_BE   | 16        | 0.38%   |
| de_AT   | 16        | 0.38%   |
| el_GR   | 15        | 0.36%   |
| fr_BE   | 13        | 0.31%   |
| da_DK   | 13        | 0.31%   |
| es_PE   | 12        | 0.29%   |
| en_PH   | 12        | 0.29%   |
| nb_NO   | 11        | 0.26%   |
| de_CH   | 10        | 0.24%   |
| ru_UA   | 9         | 0.22%   |
| fi_FI   | 9         | 0.22%   |
| bg_BG   | 9         | 0.22%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2334      | 55.65%  |
| EFI  | 1860      | 44.35%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 3916      | 94.09%  |
| Overlay  | 89        | 2.14%   |
| Zfs      | 47        | 1.13%   |
| Btrfs    | 35        | 0.84%   |
| Ext2     | 32        | 0.77%   |
| Unknown  | 27        | 0.65%   |
| Ext3     | 9         | 0.22%   |
| Xfs      | 6         | 0.14%   |
| Reiserfs | 1         | 0.02%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3793      | 90.94%  |
| GPT     | 286       | 6.86%   |
| MBR     | 92        | 2.21%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3921      | 93.94%  |
| Yes       | 253       | 6.06%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 3367      | 80.51%  |
| Yes       | 815       | 19.49%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 724       | 17.45%  |
| ASUSTek Computer    | 595       | 14.34%  |
| Dell                | 553       | 13.33%  |
| Lenovo              | 459       | 11.07%  |
| Gigabyte Technology | 234       | 5.64%   |
| Acer                | 228       | 5.5%    |
| MSI                 | 168       | 4.05%   |
| Toshiba             | 141       | 3.4%    |
| ASRock              | 121       | 2.92%   |
| Apple               | 111       | 2.68%   |
| Intel               | 67        | 1.62%   |
| Samsung Electronics | 57        | 1.37%   |
| Unknown             | 49        | 1.18%   |
| Sony                | 42        | 1.01%   |
| Fujitsu             | 36        | 0.87%   |
| Packard Bell        | 29        | 0.7%    |
| Pegatron            | 27        | 0.65%   |
| Positivo            | 23        | 0.55%   |
| Biostar             | 22        | 0.53%   |
| Foxconn             | 21        | 0.51%   |
| Medion              | 19        | 0.46%   |
| Fujitsu Siemens     | 18        | 0.43%   |
| ECS                 | 18        | 0.43%   |
| Microsoft           | 17        | 0.41%   |
| HUAWEI              | 17        | 0.41%   |
| Google              | 17        | 0.41%   |
| Alienware           | 14        | 0.34%   |
| Gateway             | 13        | 0.31%   |
| AMI                 | 13        | 0.31%   |
| Notebook            | 11        | 0.27%   |
| Panasonic           | 9         | 0.22%   |
| eMachines           | 9         | 0.22%   |
| Chuwi               | 8         | 0.19%   |
| NEC Computers       | 7         | 0.17%   |
| Shuttle             | 6         | 0.14%   |
| Semp Toshiba        | 6         | 0.14%   |
| Quanta              | 6         | 0.14%   |
| Insyde              | 6         | 0.14%   |
| IBM                 | 6         | 0.14%   |
| Multilaser          | 5         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Unknown                | 78        | 1.88%   |
| ASUS All Series        | 32        | 0.77%   |
| HP Notebook            | 24        | 0.58%   |
| HP Pavilion Notebook   | 15        | 0.36%   |
| HP Pavilion dv6        | 11        | 0.27%   |
| HP 15                  | 11        | 0.27%   |
| Dell OptiPlex 7010     | 11        | 0.27%   |
| Toshiba Satellite C660 | 10        | 0.24%   |
| HP Pavilion dv7        | 10        | 0.24%   |
| Dell OptiPlex 780      | 10        | 0.24%   |
| HP Pavilion 15         | 9         | 0.22%   |
| Dell OptiPlex 790      | 9         | 0.22%   |
| Dell Inspiron 1545     | 9         | 0.22%   |
| HP Pavilion g6         | 8         | 0.19%   |
| HP Laptop 15-bw0xx     | 8         | 0.19%   |
| Gigabyte A320M-S2H     | 8         | 0.19%   |
| Dell Latitude E6540    | 8         | 0.19%   |
| Dell Latitude D630     | 8         | 0.19%   |
| Apple MacBookPro8,1    | 8         | 0.19%   |
| Apple iMac12,2         | 8         | 0.19%   |
| MSI MS-7C02            | 7         | 0.17%   |
| Gigabyte 970A-DS3P     | 7         | 0.17%   |
| Dell OptiPlex 990      | 7         | 0.17%   |
| Dell OptiPlex 755      | 7         | 0.17%   |
| Dell OptiPlex 380      | 7         | 0.17%   |
| Dell Latitude E6410    | 7         | 0.17%   |
| Dell Latitude E6400    | 7         | 0.17%   |
| Dell Inspiron 3521     | 7         | 0.17%   |
| Dell Inspiron 15-3567  | 7         | 0.17%   |
| ASUS M5A78L-M/USB3     | 7         | 0.17%   |
| MSI MS-7817            | 6         | 0.14%   |
| HP ProDesk 600 G1 SFF  | 6         | 0.14%   |
| HP ProBook 640 G1      | 6         | 0.14%   |
| HP Pavilion g7         | 6         | 0.14%   |
| HP Pavilion dv6700     | 6         | 0.14%   |
| HP Pavilion 17         | 6         | 0.14%   |
| HP EliteBook 840 G1    | 6         | 0.14%   |
| Gigabyte B450 AORUS M  | 6         | 0.14%   |
| Dell OptiPlex 3010     | 6         | 0.14%   |
| Dell Inspiron 7520     | 6         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 172       | 4.15%   |
| HP Pavilion           | 160       | 3.86%   |
| Acer Aspire           | 151       | 3.64%   |
| Lenovo ThinkPad       | 144       | 3.47%   |
| Dell Latitude         | 139       | 3.35%   |
| Toshiba Satellite     | 120       | 2.89%   |
| Lenovo IdeaPad        | 113       | 2.72%   |
| Dell OptiPlex         | 97        | 2.34%   |
| HP Compaq             | 94        | 2.27%   |
| Unknown               | 78        | 1.88%   |
| HP EliteBook          | 69        | 1.66%   |
| HP ProBook            | 61        | 1.47%   |
| HP Laptop             | 48        | 1.16%   |
| Lenovo ThinkCentre    | 45        | 1.08%   |
| ASUS ROG              | 40        | 0.96%   |
| ASUS PRIME            | 39        | 0.94%   |
| Dell Vostro           | 35        | 0.84%   |
| ASUS VivoBook         | 33        | 0.8%    |
| ASUS All              | 32        | 0.77%   |
| HP ENVY               | 31        | 0.75%   |
| Dell XPS              | 30        | 0.72%   |
| ASUS TUF              | 29        | 0.7%    |
| Dell Precision        | 28        | 0.68%   |
| Lenovo Yoga           | 25        | 0.6%    |
| Packard Bell EasyNote | 24        | 0.58%   |
| HP Notebook           | 24        | 0.58%   |
| Microsoft Surface     | 17        | 0.41%   |
| HP Stream             | 17        | 0.41%   |
| Fujitsu ESPRIMO       | 16        | 0.39%   |
| Dell Studio           | 16        | 0.39%   |
| HP EliteDesk          | 14        | 0.34%   |
| HP Presario           | 13        | 0.31%   |
| HP 255                | 13        | 0.31%   |
| HP 15                 | 13        | 0.31%   |
| ASUS ZenBook          | 13        | 0.31%   |
| HP ProDesk            | 12        | 0.29%   |
| HP OMEN               | 12        | 0.29%   |
| Gigabyte B450         | 12        | 0.29%   |
| ASUS M5A78L-M         | 12        | 0.29%   |
| Apple iMac12          | 12        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 382       | 9.21%   |
| 2012    | 342       | 8.24%   |
| 2013    | 334       | 8.05%   |
| 2010    | 310       | 7.47%   |
| 2018    | 294       | 7.09%   |
| 2008    | 272       | 6.56%   |
| 2014    | 264       | 6.36%   |
| 2019    | 251       | 6.05%   |
| 2009    | 234       | 5.64%   |
| 2017    | 227       | 5.47%   |
| 2021    | 218       | 5.26%   |
| 2020    | 214       | 5.16%   |
| 2007    | 206       | 4.97%   |
| 2016    | 197       | 4.75%   |
| 2015    | 194       | 4.68%   |
| 2006    | 95        | 2.29%   |
| 2005    | 59        | 1.42%   |
| 2022    | 27        | 0.65%   |
| 2004    | 11        | 0.27%   |
| 2003    | 8         | 0.19%   |
| Unknown | 8         | 0.19%   |
| 2002    | 1         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 2390      | 57.62%  |
| Desktop     | 1486      | 35.82%  |
| Convertible | 80        | 1.93%   |
| All in one  | 80        | 1.93%   |
| Mini pc     | 52        | 1.25%   |
| Tablet      | 51        | 1.23%   |
| Server      | 9         | 0.22%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 3784      | 90.68%  |
| Enabled  | 389       | 9.32%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 4127      | 99.49%  |
| Yes  | 21        | 0.51%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 1087      | 25.96%  |
| 4.01-8.0    | 957       | 22.86%  |
| 8.01-16.0   | 655       | 15.64%  |
| 16.01-24.0  | 539       | 12.87%  |
| 1.01-2.0    | 413       | 9.86%   |
| 32.01-64.0  | 226       | 5.4%    |
| 2.01-3.0    | 142       | 3.39%   |
| 0.51-1.0    | 89        | 2.13%   |
| 64.01-256.0 | 50        | 1.19%   |
| 24.01-32.0  | 29        | 0.69%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1929      | 43.28%  |
| 2.01-3.0   | 1193      | 26.77%  |
| 3.01-4.0   | 486       | 10.9%   |
| 0.51-1.0   | 371       | 8.32%   |
| 4.01-8.0   | 368       | 8.26%   |
| 8.01-16.0  | 57        | 1.28%   |
| 0.01-0.5   | 41        | 0.92%   |
| 16.01-24.0 | 8         | 0.18%   |
| 24.01-32.0 | 3         | 0.07%   |
| 32.01-64.0 | 1         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2779      | 65.68%  |
| 2       | 994       | 23.49%  |
| 3       | 239       | 5.65%   |
| 4       | 97        | 2.29%   |
| 5       | 49        | 1.16%   |
| 6       | 27        | 0.64%   |
| 0       | 22        | 0.52%   |
| 7       | 10        | 0.24%   |
| 8       | 9         | 0.21%   |
| 51      | 1         | 0.02%   |
| 30      | 1         | 0.02%   |
| 11      | 1         | 0.02%   |
| 10      | 1         | 0.02%   |
| Unknown | 1         | 0.02%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2111      | 50.66%  |
| No        | 2056      | 49.34%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3630      | 87.36%  |
| No        | 525       | 12.64%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 3272      | 78.58%  |
| No        | 892       | 21.42%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2151      | 51.39%  |
| No        | 2035      | 48.61%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 949       | 22.79%  |
| Germany      | 374       | 8.98%   |
| Brazil       | 316       | 7.59%   |
| UK           | 258       | 6.19%   |
| Canada       | 159       | 3.82%   |
| Italy        | 156       | 3.75%   |
| Spain        | 124       | 2.98%   |
| India        | 121       | 2.91%   |
| France       | 115       | 2.76%   |
| Netherlands  | 110       | 2.64%   |
| Poland       | 92        | 2.21%   |
| Australia    | 87        | 2.09%   |
| Mexico       | 80        | 1.92%   |
| Argentina    | 59        | 1.42%   |
| Portugal     | 53        | 1.27%   |
| Russia       | 52        | 1.25%   |
| Sweden       | 46        | 1.1%    |
| South Africa | 46        | 1.1%    |
| Czechia      | 45        | 1.08%   |
| Belgium      | 45        | 1.08%   |
| Romania      | 41        | 0.98%   |
| Greece       | 40        | 0.96%   |
| Indonesia    | 39        | 0.94%   |
| Turkey       | 33        | 0.79%   |
| Austria      | 33        | 0.79%   |
| Switzerland  | 32        | 0.77%   |
| Hungary      | 31        | 0.74%   |
| Colombia     | 30        | 0.72%   |
| Chile        | 30        | 0.72%   |
| Norway       | 29        | 0.7%    |
| Japan        | 27        | 0.65%   |
| Denmark      | 27        | 0.65%   |
| New Zealand  | 26        | 0.62%   |
| Serbia       | 25        | 0.6%    |
| Egypt        | 22        | 0.53%   |
| Bulgaria     | 21        | 0.5%    |
| Ukraine      | 19        | 0.46%   |
| Philippines  | 18        | 0.43%   |
| Slovakia     | 15        | 0.36%   |
| Finland      | 15        | 0.36%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Sao Paulo      | 35        | 0.81%   |
| Berlin         | 35        | 0.81%   |
| Athens         | 29        | 0.67%   |
| Munich         | 26        | 0.6%    |
| Sydney         | 25        | 0.58%   |
| Rio de Janeiro | 22        | 0.51%   |
| Madrid         | 22        | 0.51%   |
| Vienna         | 20        | 0.46%   |
| Milan          | 20        | 0.46%   |
| Rome           | 19        | 0.44%   |
| Montreal       | 17        | 0.39%   |
| Dallas         | 17        | 0.39%   |
| Toronto        | 16        | 0.37%   |
| Perth          | 16        | 0.37%   |
| Johannesburg   | 16        | 0.37%   |
| Auckland       | 16        | 0.37%   |
| New York       | 15        | 0.35%   |
| Buenos Aires   | 15        | 0.35%   |
| Bengaluru      | 15        | 0.35%   |
| Mexico City    | 14        | 0.32%   |
| London         | 14        | 0.32%   |
| Istanbul       | 14        | 0.32%   |
| Hamburg        | 14        | 0.32%   |
| Cairo          | 14        | 0.32%   |
| Bogotá        | 14        | 0.32%   |
| Belgrade       | 14        | 0.32%   |
| Warsaw         | 13        | 0.3%    |
| Paris          | 13        | 0.3%    |
| Moscow         | 13        | 0.3%    |
| Jakarta        | 13        | 0.3%    |
| Zurich         | 12        | 0.28%   |
| Prague         | 12        | 0.28%   |
| Denver         | 12        | 0.28%   |
| Bucharest      | 12        | 0.28%   |
| Brisbane       | 12        | 0.28%   |
| Seattle        | 11        | 0.25%   |
| Portland       | 11        | 0.25%   |
| Phoenix        | 11        | 0.25%   |
| Nairobi        | 11        | 0.25%   |
| Houston        | 11        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 950       | 1292   | 16.98%  |
| WDC                       | 848       | 1105   | 15.16%  |
| Samsung Electronics       | 675       | 958    | 12.07%  |
| Toshiba                   | 457       | 570    | 8.17%   |
| Unknown                   | 312       | 443    | 5.58%   |
| Kingston                  | 292       | 372    | 5.22%   |
| SanDisk                   | 286       | 335    | 5.11%   |
| Hitachi                   | 277       | 338    | 4.95%   |
| Crucial                   | 178       | 215    | 3.18%   |
| Intel                     | 103       | 132    | 1.84%   |
| HGST                      | 98        | 121    | 1.75%   |
| SK hynix                  | 77        | 92     | 1.38%   |
| A-DATA Technology         | 68        | 76     | 1.22%   |
| China                     | 56        | 63     | 1%      |
| Micron Technology         | 53        | 62     | 0.95%   |
| Phison                    | 46        | 58     | 0.82%   |
| Apple                     | 43        | 46     | 0.77%   |
| Maxtor                    | 41        | 57     | 0.73%   |
| PNY                       | 40        | 51     | 0.72%   |
| Fujitsu                   | 39        | 41     | 0.7%    |
| Intenso                   | 38        | 42     | 0.68%   |
| SPCC                      | 28        | 32     | 0.5%    |
| Silicon Motion            | 26        | 34     | 0.46%   |
| Patriot                   | 26        | 36     | 0.46%   |
| OCZ                       | 26        | 30     | 0.46%   |
| Transcend                 | 21        | 42     | 0.38%   |
| LITEON                    | 21        | 26     | 0.38%   |
| JMicron Technology        | 21        | 27     | 0.38%   |
| Netac                     | 19        | 21     | 0.34%   |
| KIOXIA                    | 18        | 18     | 0.32%   |
| Micron/Crucial Technology | 17        | 18     | 0.3%    |
| SABRENT                   | 16        | 17     | 0.29%   |
| GOODRAM                   | 16        | 17     | 0.29%   |
| LITEONIT                  | 15        | 17     | 0.27%   |
| Team                      | 14        | 17     | 0.25%   |
| Hewlett-Packard           | 14        | 18     | 0.25%   |
| Unknown                   | 14        | 16     | 0.25%   |
| Lexar                     | 13        | 13     | 0.23%   |
| KingSpec                  | 11        | 13     | 0.2%    |
| Gigabyte Technology       | 11        | 19     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                 | 108       | 1.77%   |
| Unknown MMC Card  64GB                 | 82        | 1.35%   |
| Kingston SA400S37240G 240GB SSD        | 72        | 1.18%   |
| Seagate ST500DM002-1BD142 500GB        | 51        | 0.84%   |
| Toshiba MQ01ABF050 500GB               | 48        | 0.79%   |
| Kingston SA400S37480G 480GB SSD        | 45        | 0.74%   |
| Seagate ST1000LM035-1RK172 1TB         | 44        | 0.72%   |
| Crucial CT240BX500SSD1 240GB           | 41        | 0.67%   |
| Samsung SSD 860 EVO 500GB              | 38        | 0.62%   |
| Kingston SA400S37120G 120GB SSD        | 38        | 0.62%   |
| Unknown MMC Card  128GB                | 36        | 0.59%   |
| Toshiba MQ01ABD100 1TB                 | 36        | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 36        | 0.59%   |
| Seagate ST1000DM010-2EP102 1TB         | 36        | 0.59%   |
| Seagate ST500LT012-1DG142 500GB        | 35        | 0.58%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 34        | 0.56%   |
| Samsung NVMe SSD Drive 512GB           | 33        | 0.54%   |
| Toshiba MQ04ABF100 1TB                 | 30        | 0.49%   |
| Samsung NVMe SSD Drive 500GB           | 30        | 0.49%   |
| Unknown SD/MMC/MS PRO 64GB             | 29        | 0.48%   |
| Samsung SSD 850 EVO 500GB              | 29        | 0.48%   |
| Samsung SSD 850 EVO 250GB              | 29        | 0.48%   |
| Samsung NVMe SSD Drive 1TB             | 29        | 0.48%   |
| Kingston SV300S37A120G 120GB SSD       | 28        | 0.46%   |
| Seagate ST9500325AS 500GB              | 27        | 0.44%   |
| Seagate ST3500418AS 500GB              | 27        | 0.44%   |
| Crucial CT500MX500SSD1 500GB           | 25        | 0.41%   |
| Toshiba DT01ACA100 1TB                 | 24        | 0.39%   |
| Seagate Expansion 4TB                  | 24        | 0.39%   |
| WDC WD10EZEX-08WN4A0 1TB               | 22        | 0.36%   |
| SanDisk NVMe SSD Drive 256GB           | 22        | 0.36%   |
| Samsung SSD 860 EVO 250GB              | 22        | 0.36%   |
| Unknown MMC Card  16GB                 | 21        | 0.35%   |
| Samsung SSD 840 EVO 250GB              | 21        | 0.35%   |
| Seagate ST500LM012 HN-M500MBB 500GB    | 20        | 0.33%   |
| Intel NVMe SSD Drive 512GB             | 20        | 0.33%   |
| Seagate ST1000DM003-1ER162 1TB         | 19        | 0.31%   |
| Seagate ST1000DM003-1CH162 1TB         | 19        | 0.31%   |
| SanDisk NVMe SSD Drive 512GB           | 19        | 0.31%   |
| Hitachi HTS545032B9A300 320GB          | 19        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 939       | 1264   | 34.01%  |
| WDC                 | 768       | 985    | 27.82%  |
| Toshiba             | 386       | 489    | 13.98%  |
| Hitachi             | 277       | 338    | 10.03%  |
| Samsung Electronics | 135       | 171    | 4.89%   |
| HGST                | 98        | 121    | 3.55%   |
| Maxtor              | 39        | 55     | 1.41%   |
| Fujitsu             | 39        | 41     | 1.41%   |
| Unknown             | 29        | 37     | 1.05%   |
| Apple               | 22        | 24     | 0.8%    |
| ASMT                | 7         | 7      | 0.25%   |
| USB3.0              | 4         | 5      | 0.14%   |
| IBM/Hitachi         | 4         | 5      | 0.14%   |
| Hewlett-Packard     | 3         | 6      | 0.11%   |
| SABRENT             | 2         | 2      | 0.07%   |
| JMicron Technology  | 2         | 2      | 0.07%   |
| Intenso             | 2         | 2      | 0.07%   |
| Quantum             | 1         | 1      | 0.04%   |
| Pioneer             | 1         | 1      | 0.04%   |
| KESU                | 1         | 1      | 0.04%   |
| ExcelStor           | 1         | 1      | 0.04%   |
| ASMT109x            | 1         | 2      | 0.04%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 352       | 485    | 19.83%  |
| Kingston            | 253       | 315    | 14.25%  |
| SanDisk             | 181       | 216    | 10.2%   |
| Crucial             | 173       | 208    | 9.75%   |
| WDC                 | 78        | 96     | 4.39%   |
| A-DATA Technology   | 63        | 71     | 3.55%   |
| China               | 53        | 60     | 2.99%   |
| Intel               | 52        | 61     | 2.93%   |
| PNY                 | 40        | 51     | 2.25%   |
| Toshiba             | 39        | 44     | 2.2%    |
| SK hynix            | 30        | 34     | 1.69%   |
| Micron Technology   | 30        | 35     | 1.69%   |
| SPCC                | 26        | 30     | 1.46%   |
| Intenso             | 26        | 29     | 1.46%   |
| Patriot             | 25        | 35     | 1.41%   |
| OCZ                 | 24        | 28     | 1.35%   |
| Transcend           | 21        | 42     | 1.18%   |
| LITEON              | 21        | 26     | 1.18%   |
| Netac               | 19        | 20     | 1.07%   |
| Apple               | 18        | 18     | 1.01%   |
| LITEONIT            | 15        | 17     | 0.85%   |
| GOODRAM             | 15        | 16     | 0.85%   |
| Team                | 14        | 17     | 0.79%   |
| Lexar               | 12        | 12     | 0.68%   |
| JMicron Technology  | 12        | 17     | 0.68%   |
| KingSpec            | 10        | 12     | 0.56%   |
| Hewlett-Packard     | 10        | 11     | 0.56%   |
| Leven               | 9         | 10     | 0.51%   |
| Gigabyte Technology | 9         | 16     | 0.51%   |
| Apacer              | 9         | 10     | 0.51%   |
| Corsair             | 7         | 8      | 0.39%   |
| Unknown             | 7         | 9      | 0.39%   |
| Plextor             | 6         | 7      | 0.34%   |
| OWC                 | 6         | 7      | 0.34%   |
| Verbatim            | 4         | 4      | 0.23%   |
| TCSUNBOW            | 4         | 4      | 0.23%   |
| Super Talent        | 4         | 5      | 0.23%   |
| Seagate             | 4         | 6      | 0.23%   |
| Mushkin             | 4         | 4      | 0.23%   |
| FORESEE             | 4         | 4      | 0.23%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 2416      | 3560   | 47.39%  |
| SSD     | 1599      | 2203   | 31.37%  |
| NVMe    | 685       | 910    | 13.44%  |
| MMC     | 288       | 399    | 5.65%   |
| Unknown | 110       | 140    | 2.16%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 3508      | 5618   | 74.94%  |
| NVMe | 675       | 893    | 14.42%  |
| MMC  | 288       | 399    | 6.15%   |
| SAS  | 210       | 302    | 4.49%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 2762      | 3826   | 67.15%  |
| 0.51-1.0   | 984       | 1334   | 23.92%  |
| 1.01-2.0   | 205       | 295    | 4.98%   |
| 3.01-4.0   | 77        | 162    | 1.87%   |
| 4.01-10.0  | 51        | 73     | 1.24%   |
| 2.01-3.0   | 30        | 57     | 0.73%   |
| 10.01-20.0 | 4         | 16     | 0.1%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1403      | 32.8%   |
| 251-500        | 1047      | 24.48%  |
| 501-1000       | 560       | 13.09%  |
| 51-100         | 445       | 10.4%   |
| 21-50          | 260       | 6.08%   |
| 1001-2000      | 201       | 4.7%    |
| 1-20           | 129       | 3.02%   |
| More than 3000 | 125       | 2.92%   |
| 2001-3000      | 69        | 1.61%   |
| Unknown        | 38        | 0.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2158      | 48.69%  |
| 21-50          | 989       | 22.31%  |
| 51-100         | 444       | 10.02%  |
| 101-250        | 357       | 8.06%   |
| 251-500        | 203       | 4.58%   |
| 501-1000       | 108       | 2.44%   |
| 1001-2000      | 61        | 1.38%   |
| More than 3000 | 57        | 1.29%   |
| Unknown        | 38        | 0.86%   |
| 2001-3000      | 17        | 0.38%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB            | 3         | 3      | 3.9%    |
| Toshiba MQ02ABD100H 1TB              | 2         | 2      | 2.6%    |
| Toshiba MQ01ABD100 1TB               | 2         | 2      | 2.6%    |
| Seagate ST9500420AS 500GB            | 2         | 2      | 2.6%    |
| Seagate ST500LT012-9WS142 500GB      | 2         | 2      | 2.6%    |
| Kingston SUV400S37240G 240GB SSD     | 2         | 2      | 2.6%    |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 1      | 1.3%    |
| WDC WD5000LPVX-75V0TT0 500GB         | 1         | 1      | 1.3%    |
| WDC WD5000AAKS-00V1A0 500GB          | 1         | 1      | 1.3%    |
| WDC WD3200BPVT-55ZEST0 320GB         | 1         | 1      | 1.3%    |
| WDC WD3200AAKS-22B3A0 320GB          | 1         | 1      | 1.3%    |
| WDC WD3200AAJS-00L7A0 320GB          | 1         | 1      | 1.3%    |
| WDC WD30EFRX-68EUZN0 3TB             | 1         | 1      | 1.3%    |
| WDC WD10SPZX-75Z10T2 1TB             | 1         | 1      | 1.3%    |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 1      | 1.3%    |
| WDC WD10JPVT-55A1YT0 1TB             | 1         | 1      | 1.3%    |
| WDC WD10EZEX-21M2NA0 1TB             | 1         | 2      | 1.3%    |
| WDC WD10EURX-63FH1Y0 1TB             | 1         | 1      | 1.3%    |
| Toshiba THNSNK256GCS8 SATA 256GB SSD | 1         | 1      | 1.3%    |
| Toshiba MQ01ABF050 500GB             | 1         | 1      | 1.3%    |
| Toshiba MQ01ABD075 752GB             | 1         | 1      | 1.3%    |
| Toshiba MK8046GSX 80GB               | 1         | 1      | 1.3%    |
| Toshiba MK5061GSY 500GB              | 1         | 1      | 1.3%    |
| Toshiba MK3265GSX 320GB              | 1         | 1      | 1.3%    |
| Toshiba MK2046GSX 200GB              | 1         | 1      | 1.3%    |
| Toshiba MG03ACA200 2TB               | 1         | 1      | 1.3%    |
| SK hynix BC711 HFM512GD3JX013N 512GB | 1         | 1      | 1.3%    |
| Silicon Motion Inland NVMe SSD 256GB | 1         | 1      | 1.3%    |
| Seagate ST9320325AS 320GB            | 1         | 1      | 1.3%    |
| Seagate ST9250315AS 250GB            | 1         | 1      | 1.3%    |
| Seagate ST9200420ASG 200GB           | 1         | 1      | 1.3%    |
| Seagate ST9160314AS 160GB            | 1         | 1      | 1.3%    |
| Seagate ST9120822AS 120GB            | 1         | 1      | 1.3%    |
| Seagate ST8000DM004-2CX188 8TB       | 1         | 1      | 1.3%    |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 1.3%    |
| Seagate ST500LM000-SSHD-8GB          | 1         | 1      | 1.3%    |
| Seagate ST500DM002-1BD142 500GB      | 1         | 1      | 1.3%    |
| Seagate ST4000DM004-2CV104 4TB       | 1         | 1      | 1.3%    |
| Seagate ST3500514NS 500GB            | 1         | 1      | 1.3%    |
| Seagate ST3500413AS 500GB            | 1         | 1      | 1.3%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 29     | 36.84%  |
| WDC                 | 12        | 13     | 15.79%  |
| Toshiba             | 12        | 12     | 15.79%  |
| Kingston            | 4         | 4      | 5.26%   |
| HGST                | 4         | 4      | 5.26%   |
| Samsung Electronics | 3         | 3      | 3.95%   |
| Hitachi             | 3         | 3      | 3.95%   |
| A-DATA Technology   | 2         | 2      | 2.63%   |
| SK hynix            | 1         | 1      | 1.32%   |
| Silicon Motion      | 1         | 1      | 1.32%   |
| OCZ                 | 1         | 1      | 1.32%   |
| Micron Technology   | 1         | 1      | 1.32%   |
| LITEONIT            | 1         | 1      | 1.32%   |
| LITEON              | 1         | 1      | 1.32%   |
| Intel               | 1         | 1      | 1.32%   |
| Hewlett-Packard     | 1         | 1      | 1.32%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 28        | 29     | 47.46%  |
| WDC                 | 12        | 13     | 20.34%  |
| Toshiba             | 11        | 11     | 18.64%  |
| HGST                | 4         | 4      | 6.78%   |
| Hitachi             | 3         | 3      | 5.08%   |
| Samsung Electronics | 1         | 1      | 1.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 57        | 61     | 77.03%  |
| SSD  | 14        | 14     | 18.92%  |
| NVMe | 3         | 3      | 4.05%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                          | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate ST2000LX001-1RG174 2TB | 1         | 1      | 50%     |
| SanDisk SSD i100 24GB          | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 50%     |
| SanDisk | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 3836      | 6624   | 91.01%  |
| Works    | 304       | 508    | 7.21%   |
| Malfunc  | 73        | 78     | 1.73%   |
| Failed   | 2         | 2      | 0.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2887      | 61.36%  |
| AMD                              | 763       | 16.22%  |
| Samsung Electronics              | 242       | 5.14%   |
| Nvidia                           | 125       | 2.66%   |
| SanDisk                          | 108       | 2.3%    |
| Phison Electronics               | 56        | 1.19%   |
| ASMedia Technology               | 56        | 1.19%   |
| JMicron Technology               | 55        | 1.17%   |
| Kingston Technology Company      | 46        | 0.98%   |
| SK hynix                         | 43        | 0.91%   |
| Marvell Technology Group         | 39        | 0.83%   |
| VIA Technologies                 | 35        | 0.74%   |
| Toshiba America Info Systems     | 33        | 0.7%    |
| Silicon Integrated Systems [SiS] | 33        | 0.7%    |
| Silicon Motion                   | 28        | 0.6%    |
| Micron Technology                | 24        | 0.51%   |
| Micron/Crucial Technology        | 22        | 0.47%   |
| KIOXIA                           | 20        | 0.43%   |
| ADATA Technology                 | 15        | 0.32%   |
| Silicon Image                    | 14        | 0.3%    |
| Realtek Semiconductor            | 9         | 0.19%   |
| Union Memory (Shenzhen)          | 6         | 0.13%   |
| Lite-On Technology               | 6         | 0.13%   |
| Broadcom / LSI                   | 6         | 0.13%   |
| Seagate Technology               | 4         | 0.09%   |
| LSI Logic / Symbios Logic        | 4         | 0.09%   |
| Solid State Storage Technology   | 3         | 0.06%   |
| OCZ Technology Group             | 3         | 0.06%   |
| Apple                            | 3         | 0.06%   |
| Yangtze Memory Technologies      | 2         | 0.04%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.04%   |
| INNOGRIT                         | 2         | 0.04%   |
| Adaptec                          | 2         | 0.04%   |
| Promise Technology               | 1         | 0.02%   |
| Netac Technology                 | 1         | 0.02%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.02%   |
| Lenovo                           | 1         | 0.02%   |
| Integrated Technology Express    | 1         | 0.02%   |
| Hewlett-Packard                  | 1         | 0.02%   |
| Dell                             | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 473       | 8.29%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 206       | 3.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 186       | 3.26%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 177       | 3.1%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 172       | 3.02%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 155       | 2.72%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 148       | 2.6%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 140       | 2.45%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 133       | 2.33%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 115       | 2.02%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 112       | 1.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 109       | 1.91%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 108       | 1.89%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 107       | 1.88%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 103       | 1.81%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 94        | 1.65%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 87        | 1.53%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 86        | 1.51%   |
| AMD 400 Series Chipset SATA Controller                                                  | 75        | 1.32%   |
| Intel SATA Controller [RAID mode]                                                       | 71        | 1.24%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 65        | 1.14%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 60        | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 58        | 1.02%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 57        | 1%      |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 54        | 0.95%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 53        | 0.93%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 51        | 0.89%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 48        | 0.84%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 45        | 0.79%   |
| Samsung NVMe SSD Controller 980                                                         | 44        | 0.77%   |
| Nvidia MCP61 SATA Controller                                                            | 41        | 0.72%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 41        | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 41        | 0.72%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 39        | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 38        | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 38        | 0.67%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 37        | 0.65%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                          | 34        | 0.6%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 34        | 0.6%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                                    | 32        | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2939      | 59.47%  |
| IDE  | 993       | 20.09%  |
| NVMe | 679       | 13.74%  |
| RAID | 318       | 6.43%   |
| SAS  | 7         | 0.14%   |
| SCSI | 6         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 3240      | 78.11%  |
| AMD          | 907       | 21.87%  |
| CentaurHauls | 1         | 0.02%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 59        | 1.42%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 34        | 0.82%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 34        | 0.82%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 30        | 0.72%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 28        | 0.67%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 27        | 0.65%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 26        | 0.63%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 26        | 0.63%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 24        | 0.58%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 22        | 0.53%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 22        | 0.53%   |
| AMD Ryzen 5 3600 6-Core Processor             | 22        | 0.53%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 21        | 0.51%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 20        | 0.48%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 20        | 0.48%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 19        | 0.46%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 19        | 0.46%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 19        | 0.46%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 19        | 0.46%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 19        | 0.46%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 19        | 0.46%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 18        | 0.43%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 18        | 0.43%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 18        | 0.43%   |
| Intel Atom CPU N450 @ 1.66GHz                 | 18        | 0.43%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 17        | 0.41%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 17        | 0.41%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 17        | 0.41%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 16        | 0.38%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 16        | 0.38%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 16        | 0.38%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 16        | 0.38%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 16        | 0.38%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 16        | 0.38%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz          | 16        | 0.38%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 16        | 0.38%   |
| Intel Pentium 4 CPU 3.00GHz                   | 15        | 0.36%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 15        | 0.36%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 15        | 0.36%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 15        | 0.36%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 819       | 19.71%  |
| Intel Core i7           | 522       | 12.56%  |
| Intel Core i3           | 386       | 9.29%   |
| Intel Core 2 Duo        | 303       | 7.29%   |
| Intel Celeron           | 267       | 6.43%   |
| Intel Atom              | 185       | 4.45%   |
| AMD Ryzen 5             | 145       | 3.49%   |
| Intel Pentium           | 133       | 3.2%    |
| Other                   | 118       | 2.84%   |
| AMD Ryzen 7             | 99        | 2.38%   |
| Intel Xeon              | 77        | 1.85%   |
| Intel Pentium Dual-Core | 77        | 1.85%   |
| AMD FX                  | 68        | 1.64%   |
| Intel Pentium Dual      | 66        | 1.59%   |
| AMD A6                  | 63        | 1.52%   |
| Intel Core 2 Quad       | 58        | 1.4%    |
| AMD A4                  | 49        | 1.18%   |
| Intel Genuine           | 44        | 1.06%   |
| AMD Ryzen 3             | 43        | 1.03%   |
| Intel Core 2            | 41        | 0.99%   |
| Intel Pentium 4         | 38        | 0.91%   |
| AMD A8                  | 38        | 0.91%   |
| AMD Athlon 64 X2        | 37        | 0.89%   |
| AMD A10                 | 36        | 0.87%   |
| AMD Ryzen 9             | 34        | 0.82%   |
| AMD Athlon II X2        | 26        | 0.63%   |
| AMD E1                  | 24        | 0.58%   |
| Intel Pentium M         | 23        | 0.55%   |
| Intel Celeron M         | 23        | 0.55%   |
| AMD Phenom II X4        | 21        | 0.51%   |
| AMD E                   | 20        | 0.48%   |
| AMD Athlon              | 18        | 0.43%   |
| AMD Sempron             | 17        | 0.41%   |
| AMD Turion 64 X2 Mobile | 14        | 0.34%   |
| Intel Core i9           | 13        | 0.31%   |
| AMD Athlon II X4        | 12        | 0.29%   |
| Intel Pentium Silver    | 11        | 0.26%   |
| Intel Pentium Gold      | 9         | 0.22%   |
| Intel Pentium D         | 9         | 0.22%   |
| AMD Turion 64 Mobile    | 9         | 0.22%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2160      | 51.97%  |
| 4      | 1278      | 30.75%  |
| 1      | 260       | 6.26%   |
| 6      | 217       | 5.22%   |
| 8      | 155       | 3.73%   |
| 3      | 33        | 0.79%   |
| 12     | 24        | 0.58%   |
| 16     | 13        | 0.31%   |
| 10     | 11        | 0.26%   |
| 20     | 2         | 0.05%   |
| 14     | 2         | 0.05%   |
| 40     | 1         | 0.02%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 4131      | 99.59%  |
| 2      | 17        | 0.41%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 2192      | 52.83%  |
| 1      | 1957      | 47.17%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 4006      | 96.55%  |
| 32-bit         | 140       | 3.37%   |
| Unknown        | 3         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 386       | 9.16%   |
| 0x206a7    | 355       | 8.42%   |
| 0x306a9    | 277       | 6.57%   |
| 0x1067a    | 265       | 6.29%   |
| 0x306c3    | 218       | 5.17%   |
| 0x6fd      | 126       | 2.99%   |
| 0x40651    | 119       | 2.82%   |
| 0x20655    | 107       | 2.54%   |
| 0x806e9    | 82        | 1.95%   |
| 0x406e3    | 81        | 1.92%   |
| 0x406c4    | 81        | 1.92%   |
| 0x30678    | 77        | 1.83%   |
| 0x306d4    | 75        | 1.78%   |
| 0x806ea    | 66        | 1.57%   |
| 0x506e3    | 64        | 1.52%   |
| 0x10676    | 62        | 1.47%   |
| 0x906ea    | 61        | 1.45%   |
| 0x806c1    | 61        | 1.45%   |
| 0x906e9    | 54        | 1.28%   |
| 0x806ec    | 54        | 1.28%   |
| 0x6fb      | 54        | 1.28%   |
| 0x06000852 | 49        | 1.16%   |
| 0x06001119 | 47        | 1.12%   |
| 0x20652    | 45        | 1.07%   |
| 0x010000c8 | 45        | 1.07%   |
| 0x08701021 | 42        | 1%      |
| 0x406c3    | 40        | 0.95%   |
| 0x506c9    | 38        | 0.9%    |
| 0x106ca    | 36        | 0.85%   |
| 0x08108109 | 36        | 0.85%   |
| 0x6f6      | 33        | 0.78%   |
| 0x06006705 | 33        | 0.78%   |
| 0x706a8    | 32        | 0.76%   |
| 0x0700010f | 32        | 0.76%   |
| 0x706e5    | 30        | 0.71%   |
| 0x6e8      | 30        | 0.71%   |
| 0x6d8      | 29        | 0.69%   |
| 0x0800820d | 26        | 0.62%   |
| 0x07030105 | 26        | 0.62%   |
| 0x05000119 | 26        | 0.62%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 397       | 9.56%   |
| SandyBridge      | 377       | 9.08%   |
| Haswell          | 369       | 8.89%   |
| Penryn           | 347       | 8.36%   |
| IvyBridge        | 296       | 7.13%   |
| Core             | 271       | 6.53%   |
| Silvermont       | 233       | 5.61%   |
| Westmere         | 171       | 4.12%   |
| Skylake          | 156       | 3.76%   |
| K10              | 107       | 2.58%   |
| Piledriver       | 103       | 2.48%   |
| Zen 2            | 99        | 2.38%   |
| Zen+             | 98        | 2.36%   |
| K8 Hammer        | 92        | 2.22%   |
| P6               | 81        | 1.95%   |
| Broadwell        | 78        | 1.88%   |
| Bonnell          | 73        | 1.76%   |
| TigerLake        | 70        | 1.69%   |
| Excavator        | 65        | 1.57%   |
| Zen 3            | 63        | 1.52%   |
| Zen              | 57        | 1.37%   |
| Goldmont plus    | 56        | 1.35%   |
| CometLake        | 56        | 1.35%   |
| NetBurst         | 55        | 1.32%   |
| IceLake          | 51        | 1.23%   |
| Puma             | 42        | 1.01%   |
| Nehalem          | 41        | 0.99%   |
| Goldmont         | 41        | 0.99%   |
| Bobcat           | 40        | 0.96%   |
| Jaguar           | 38        | 0.92%   |
| Unknown          | 35        | 0.84%   |
| K10 Llano        | 26        | 0.63%   |
| Steamroller      | 19        | 0.46%   |
| Bulldozer        | 16        | 0.39%   |
| K8 & K10 hybrid  | 15        | 0.36%   |
| Alderlake Hybrid | 9         | 0.22%   |
| Tremont          | 5         | 0.12%   |
| K6               | 3         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 2447      | 52.29%  |
| Nvidia                           | 1111      | 23.74%  |
| AMD                              | 1070      | 22.86%  |
| Silicon Integrated Systems [SiS] | 26        | 0.56%   |
| VIA Technologies                 | 17        | 0.36%   |
| Matrox Electronics Systems       | 5         | 0.11%   |
| ASPEED Technology                | 2         | 0.04%   |
| Trident Microsystems             | 1         | 0.02%   |
| Silicon Motion                   | 1         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 291       | 5.94%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 182       | 3.71%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 132       | 2.69%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 122       | 2.49%   |
| Intel Core Processor Integrated Graphics Controller                                      | 118       | 2.41%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 117       | 2.39%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 100       | 2.04%   |
| Intel HD Graphics 620                                                                    | 80        | 1.63%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 75        | 1.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 72        | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 72        | 1.47%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 72        | 1.47%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 72        | 1.47%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 69        | 1.41%   |
| Intel UHD Graphics 620                                                                   | 62        | 1.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 60        | 1.22%   |
| Intel HD Graphics 5500                                                                   | 55        | 1.12%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 54        | 1.1%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 53        | 1.08%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 51        | 1.04%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 50        | 1.02%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 48        | 0.98%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 48        | 0.98%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 47        | 0.96%   |
| Intel HD Graphics 630                                                                    | 43        | 0.88%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 42        | 0.86%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 40        | 0.82%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 39        | 0.8%    |
| AMD Renoir                                                                               | 39        | 0.8%    |
| Intel HD Graphics 530                                                                    | 37        | 0.75%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 37        | 0.75%   |
| Intel HD Graphics 500                                                                    | 33        | 0.67%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 33        | 0.67%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 28        | 0.57%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 27        | 0.55%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 26        | 0.53%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 25        | 0.51%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 25        | 0.51%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 25        | 0.51%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 25        | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1967      | 47.25%  |
| 1 x AMD                  | 862       | 20.71%  |
| 1 x Nvidia               | 745       | 17.9%   |
| Intel + Nvidia           | 319       | 7.66%   |
| Intel + AMD              | 111       | 2.67%   |
| 2 x AMD                  | 62        | 1.49%   |
| AMD + Nvidia             | 33        | 0.79%   |
| 1 x SiS                  | 26        | 0.62%   |
| 1 x VIA                  | 17        | 0.41%   |
| 2 x Nvidia               | 7         | 0.17%   |
| 1 x Matrox               | 5         | 0.12%   |
| Other                    | 4         | 0.1%    |
| 2 x Intel                | 1         | 0.02%   |
| 1 x Trident Microsystems | 1         | 0.02%   |
| Nvidia + Silicon Motion  | 1         | 0.02%   |
| Nvidia + ASPEED          | 1         | 0.02%   |
| 1 x ASPEED               | 1         | 0.02%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 3360      | 80.44%  |
| Proprietary | 611       | 14.63%  |
| Unknown     | 206       | 4.93%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2372      | 56.21%  |
| 0.01-0.5   | 657       | 15.57%  |
| 1.01-2.0   | 442       | 10.47%  |
| 0.51-1.0   | 370       | 8.77%   |
| 3.01-4.0   | 175       | 4.15%   |
| 7.01-8.0   | 102       | 2.42%   |
| 5.01-6.0   | 51        | 1.21%   |
| 8.01-16.0  | 26        | 0.62%   |
| 2.01-3.0   | 20        | 0.47%   |
| 16.01-24.0 | 4         | 0.09%   |
| 4.01-5.0   | 1         | 0.02%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 588       | 14.29%  |
| AU Optronics            | 495       | 12.03%  |
| LG Display              | 373       | 9.06%   |
| Chimei Innolux          | 316       | 7.68%   |
| BOE                     | 280       | 6.8%    |
| Dell                    | 206       | 5.01%   |
| Goldstar                | 185       | 4.5%    |
| Hewlett-Packard         | 154       | 3.74%   |
| Acer                    | 118       | 2.87%   |
| Chi Mei Optoelectronics | 101       | 2.45%   |
| Apple                   | 96        | 2.33%   |
| AOC                     | 87        | 2.11%   |
| Philips                 | 85        | 2.07%   |
| Ancor Communications    | 74        | 1.8%    |
| LG Philips              | 66        | 1.6%    |
| BenQ                    | 64        | 1.56%   |
| Lenovo                  | 59        | 1.43%   |
| Sharp                   | 43        | 1.04%   |
| LG Electronics          | 40        | 0.97%   |
| InfoVision              | 36        | 0.87%   |
| ViewSonic               | 35        | 0.85%   |
| Unknown                 | 35        | 0.85%   |
| Sony                    | 30        | 0.73%   |
| Toshiba                 | 25        | 0.61%   |
| PANDA                   | 25        | 0.61%   |
| HannStar                | 25        | 0.61%   |
| Vizio                   | 23        | 0.56%   |
| Iiyama                  | 21        | 0.51%   |
| ASUSTek Computer        | 19        | 0.46%   |
| CPT                     | 18        | 0.44%   |
| Unknown                 | 17        | 0.41%   |
| Eizo                    | 16        | 0.39%   |
| Sceptre Tech            | 14        | 0.34%   |
| NEC Computers           | 13        | 0.32%   |
| Fujitsu Siemens         | 12        | 0.29%   |
| Quanta Display          | 11        | 0.27%   |
| Panasonic               | 11        | 0.27%   |
| LGD                     | 10        | 0.24%   |
| HPN                     | 10        | 0.24%   |
| Gateway                 | 10        | 0.24%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 30        | 0.71%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 21        | 0.5%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 18        | 0.43%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 18        | 0.43%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 18        | 0.43%   |
| Unknown                                                                  | 17        | 0.4%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 16        | 0.38%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 15        | 0.36%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 14        | 0.33%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 13        | 0.31%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 13        | 0.31%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 12        | 0.28%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 12        | 0.28%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 11        | 0.26%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 11        | 0.26%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 11        | 0.26%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 11        | 0.26%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 11        | 0.26%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch                  | 10        | 0.24%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 10        | 0.24%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 10        | 0.24%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 10        | 0.24%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 10        | 0.24%   |
| HannStar HSD101PFW2 HSD03E9 1024x600 222x125mm 10.0-inch                 | 9         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 9         | 0.21%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 9         | 0.21%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 9         | 0.21%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 9         | 0.21%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 9         | 0.21%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch     | 8         | 0.19%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 8         | 0.19%   |
| LG Display LCD Monitor LGD02E9 1366x768 310x170mm 13.9-inch              | 8         | 0.19%   |
| InfoVision LCD Monitor IVO03F4 1024x600 223x125mm 10.1-inch              | 8         | 0.19%   |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 8         | 0.19%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 8         | 0.19%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 8         | 0.19%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 8         | 0.19%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 8         | 0.19%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 8         | 0.19%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch    | 7         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1324      | 32.85%  |
| 1366x768 (WXGA)    | 1113      | 27.61%  |
| 1600x900 (HD+)     | 234       | 5.81%   |
| 1280x800 (WXGA)    | 200       | 4.96%   |
| 3840x2160 (4K)     | 167       | 4.14%   |
| 1280x1024 (SXGA)   | 136       | 3.37%   |
| 1440x900 (WXGA+)   | 134       | 3.32%   |
| 1680x1050 (WSXGA+) | 117       | 2.9%    |
| 2560x1440 (QHD)    | 86        | 2.13%   |
| Unknown            | 70        | 1.74%   |
| 1920x1200 (WUXGA)  | 65        | 1.61%   |
| 1360x768           | 61        | 1.51%   |
| 1024x600           | 46        | 1.14%   |
| 3840x1080          | 26        | 0.65%   |
| 1024x768 (XGA)     | 24        | 0.6%    |
| 3440x1440          | 22        | 0.55%   |
| 2560x1600          | 21        | 0.52%   |
| 2560x1080          | 19        | 0.47%   |
| 1920x540           | 17        | 0.42%   |
| 2736x1824          | 11        | 0.27%   |
| 2256x1504          | 8         | 0.2%    |
| 2160x1440          | 8         | 0.2%    |
| 5760x1080          | 7         | 0.17%   |
| 3200x1800 (QHD+)   | 7         | 0.17%   |
| 1600x1200          | 7         | 0.17%   |
| 1280x768           | 7         | 0.17%   |
| 3840x2400          | 5         | 0.12%   |
| 3600x1080          | 5         | 0.12%   |
| 2880x1800          | 5         | 0.12%   |
| 1280x720 (HD)      | 5         | 0.12%   |
| 5760x2160          | 4         | 0.1%    |
| 4480x1440          | 4         | 0.1%    |
| 1680x945           | 4         | 0.1%    |
| 3840x1600          | 3         | 0.07%   |
| 2048x1152          | 3         | 0.07%   |
| 1400x1050          | 3         | 0.07%   |
| 1024x576           | 3         | 0.07%   |
| 6400x1440          | 2         | 0.05%   |
| 5440x1080          | 2         | 0.05%   |
| 3840x1200          | 2         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1142      | 27.98%  |
| Unknown | 360       | 8.82%   |
| 13      | 333       | 8.16%   |
| 14      | 285       | 6.98%   |
| 17      | 276       | 6.76%   |
| 27      | 192       | 4.7%    |
| 24      | 178       | 4.36%   |
| 23      | 178       | 4.36%   |
| 21      | 177       | 4.34%   |
| 19      | 122       | 2.99%   |
| 18      | 111       | 2.72%   |
| 11      | 96        | 2.35%   |
| 20      | 90        | 2.2%    |
| 12      | 72        | 1.76%   |
| 22      | 71        | 1.74%   |
| 31      | 70        | 1.71%   |
| 10      | 56        | 1.37%   |
| 34      | 36        | 0.88%   |
| 72      | 23        | 0.56%   |
| 84      | 22        | 0.54%   |
| 54      | 21        | 0.51%   |
| 40      | 21        | 0.51%   |
| 32      | 17        | 0.42%   |
| 16      | 16        | 0.39%   |
| 26      | 15        | 0.37%   |
| 25      | 10        | 0.24%   |
| 52      | 8         | 0.2%    |
| 65      | 6         | 0.15%   |
| 49      | 6         | 0.15%   |
| 42      | 6         | 0.15%   |
| 74      | 5         | 0.12%   |
| 37      | 5         | 0.12%   |
| 36      | 5         | 0.12%   |
| 33      | 5         | 0.12%   |
| 29      | 5         | 0.12%   |
| 8       | 4         | 0.1%    |
| 48      | 3         | 0.07%   |
| 46      | 3         | 0.07%   |
| 41      | 3         | 0.07%   |
| 39      | 3         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1629      | 40.44%  |
| 501-600     | 517       | 12.84%  |
| 401-500     | 504       | 12.51%  |
| 201-300     | 381       | 9.46%   |
| Unknown     | 360       | 8.94%   |
| 351-400     | 319       | 7.92%   |
| 601-700     | 95        | 2.36%   |
| 701-800     | 63        | 1.56%   |
| 1001-1500   | 60        | 1.49%   |
| 1501-2000   | 52        | 1.29%   |
| 801-900     | 31        | 0.77%   |
| 901-1000    | 13        | 0.32%   |
| 101-200     | 4         | 0.1%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2701      | 71.06%  |
| 16/10   | 522       | 13.73%  |
| Unknown | 319       | 8.39%   |
| 5/4     | 121       | 3.18%   |
| 4/3     | 41        | 1.08%   |
| 21/9    | 40        | 1.05%   |
| 3/2     | 38        | 1%      |
| 32/9    | 11        | 0.29%   |
| 6/5     | 5         | 0.13%   |
| 3.73    | 2         | 0.05%   |
| 0.62    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1140      | 28.12%  |
| 81-90          | 497       | 12.26%  |
| 201-250        | 471       | 11.62%  |
| Unknown        | 360       | 8.88%   |
| 151-200        | 290       | 7.15%   |
| 301-350        | 195       | 4.81%   |
| 141-150        | 155       | 3.82%   |
| 121-130        | 153       | 3.77%   |
| 351-500        | 137       | 3.38%   |
| 71-80          | 118       | 2.91%   |
| More than 1000 | 101       | 2.49%   |
| 51-60          | 97        | 2.39%   |
| 251-300        | 78        | 1.92%   |
| 61-70          | 64        | 1.58%   |
| 131-140        | 59        | 1.46%   |
| 501-1000       | 56        | 1.38%   |
| 41-50          | 55        | 1.36%   |
| 111-120        | 12        | 0.3%    |
| 91-100         | 12        | 0.3%    |
| 1-40           | 4         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 1310      | 33.13%  |
| 51-100        | 1268      | 32.07%  |
| 121-160       | 735       | 18.59%  |
| Unknown       | 360       | 9.1%    |
| 161-240       | 130       | 3.29%   |
| 1-50          | 105       | 2.66%   |
| More than 240 | 46        | 1.16%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 3523      | 83.56%  |
| 2     | 440       | 10.44%  |
| 0     | 210       | 4.98%   |
| 3     | 39        | 0.93%   |
| 4     | 3         | 0.07%   |
| 5     | 1         | 0.02%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 2218      | 34.11%  |
| Intel                             | 1602      | 24.64%  |
| Qualcomm Atheros                  | 880       | 13.53%  |
| Broadcom                          | 530       | 8.15%   |
| Broadcom Limited                  | 169       | 2.6%    |
| Marvell Technology Group          | 120       | 1.85%   |
| Ralink Technology                 | 111       | 1.71%   |
| Nvidia                            | 108       | 1.66%   |
| Ralink                            | 90        | 1.38%   |
| TP-Link                           | 74        | 1.14%   |
| Samsung Electronics               | 41        | 0.63%   |
| MediaTek                          | 41        | 0.63%   |
| Silicon Integrated Systems [SiS]  | 30        | 0.46%   |
| VIA Technologies                  | 28        | 0.43%   |
| ASIX Electronics                  | 28        | 0.43%   |
| Xiaomi                            | 27        | 0.42%   |
| NetGear                           | 25        | 0.38%   |
| D-Link                            | 24        | 0.37%   |
| JMicron Technology                | 23        | 0.35%   |
| Qualcomm Atheros Communications   | 22        | 0.34%   |
| D-Link System                     | 22        | 0.34%   |
| Huawei Technologies               | 18        | 0.28%   |
| DisplayLink                       | 18        | 0.28%   |
| Edimax Technology                 | 17        | 0.26%   |
| Dell                              | 17        | 0.26%   |
| ASUSTek Computer                  | 16        | 0.25%   |
| Sierra Wireless                   | 13        | 0.2%    |
| Microsoft                         | 11        | 0.17%   |
| Hewlett-Packard                   | 11        | 0.17%   |
| Motorola PCS                      | 10        | 0.15%   |
| Qualcomm                          | 9         | 0.14%   |
| OPPO Electronics                  | 9         | 0.14%   |
| Ericsson Business Mobile Networks | 9         | 0.14%   |
| Linksys                           | 8         | 0.12%   |
| Belkin Components                 | 8         | 0.12%   |
| AMD                               | 8         | 0.12%   |
| Aquantia                          | 7         | 0.11%   |
| Attansic Technology               | 6         | 0.09%   |
| T & A Mobile Phones               | 5         | 0.08%   |
| Sitecom Europe                    | 4         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 1331      | 17.61%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 424       | 5.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 180       | 2.38%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 141       | 1.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 124       | 1.64%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 116       | 1.53%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 104       | 1.38%   |
| Intel Wireless 7260                                                     | 95        | 1.26%   |
| Intel Wi-Fi 6 AX200                                                     | 93        | 1.23%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 78        | 1.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 73        | 0.97%   |
| Intel Wireless 7265                                                     | 72        | 0.95%   |
| Intel Ethernet Connection I217-LM                                       | 72        | 0.95%   |
| Intel Wireless 8265 / 8275                                              | 70        | 0.93%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 63        | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 62        | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 62        | 0.82%   |
| Broadcom BCM43142 802.11b/g/n                                           | 62        | 0.82%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 60        | 0.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 60        | 0.79%   |
| Intel Wireless 3165                                                     | 59        | 0.78%   |
| Intel I211 Gigabit Network Connection                                   | 56        | 0.74%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 54        | 0.71%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 54        | 0.71%   |
| Realtek RTL8125 2.5GbE Controller                                       | 53        | 0.7%    |
| Ralink MT7601U Wireless Adapter                                         | 52        | 0.69%   |
| Intel Wireless 8260                                                     | 49        | 0.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 46        | 0.61%   |
| Realtek 802.11ac NIC                                                    | 46        | 0.61%   |
| Intel Wi-Fi 6 AX201                                                     | 46        | 0.61%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 46        | 0.61%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 42        | 0.56%   |
| Intel WiFi Link 5100                                                    | 42        | 0.56%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 39        | 0.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 39        | 0.52%   |
| Nvidia MCP61 Ethernet                                                   | 39        | 0.52%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 34        | 0.45%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 34        | 0.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 33        | 0.44%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 33        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1166      | 32.98%  |
| Qualcomm Atheros                      | 702       | 19.85%  |
| Realtek Semiconductor                 | 668       | 18.89%  |
| Broadcom                              | 367       | 10.38%  |
| Ralink Technology                     | 111       | 3.14%   |
| Broadcom Limited                      | 109       | 3.08%   |
| Ralink                                | 90        | 2.55%   |
| TP-Link                               | 66        | 1.87%   |
| MediaTek                              | 30        | 0.85%   |
| NetGear                               | 24        | 0.68%   |
| D-Link                                | 23        | 0.65%   |
| Qualcomm Atheros Communications       | 22        | 0.62%   |
| D-Link System                         | 18        | 0.51%   |
| Edimax Technology                     | 17        | 0.48%   |
| Marvell Technology Group              | 16        | 0.45%   |
| ASUSTek Computer                      | 14        | 0.4%    |
| Sierra Wireless                       | 13        | 0.37%   |
| Microsoft                             | 10        | 0.28%   |
| Linksys                               | 8         | 0.23%   |
| Dell                                  | 8         | 0.23%   |
| Belkin Components                     | 8         | 0.23%   |
| Sitecom Europe                        | 4         | 0.11%   |
| Micro Star International              | 4         | 0.11%   |
| Gemtek                                | 4         | 0.11%   |
| ZyDAS                                 | 3         | 0.08%   |
| Hewlett-Packard                       | 3         | 0.08%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.08%   |
| ZyXEL Communications                  | 2         | 0.06%   |
| Xiaomi                                | 2         | 0.06%   |
| TRENDnet                              | 2         | 0.06%   |
| Senao                                 | 2         | 0.06%   |
| IMC Networks                          | 2         | 0.06%   |
| Fibocom                               | 2         | 0.06%   |
| AVM                                   | 2         | 0.06%   |
| Samsung Electronics                   | 1         | 0.03%   |
| Qualcomm                              | 1         | 0.03%   |
| Qcom                                  | 1         | 0.03%   |
| Philips (or NXP)                      | 1         | 0.03%   |
| Panasonic (Matsushita)                | 1         | 0.03%   |
| Ovislink                              | 1         | 0.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 141       | 3.95%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 124       | 3.48%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 116       | 3.25%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 104       | 2.91%   |
| Intel Wireless 7260                                                     | 95        | 2.66%   |
| Intel Wi-Fi 6 AX200                                                     | 93        | 2.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 78        | 2.19%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 73        | 2.05%   |
| Intel Wireless 7265                                                     | 72        | 2.02%   |
| Intel Wireless 8265 / 8275                                              | 70        | 1.96%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 63        | 1.77%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 62        | 1.74%   |
| Broadcom BCM43142 802.11b/g/n                                           | 62        | 1.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 60        | 1.68%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 60        | 1.68%   |
| Intel Wireless 3165                                                     | 59        | 1.65%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 54        | 1.51%   |
| Ralink MT7601U Wireless Adapter                                         | 52        | 1.46%   |
| Intel Wireless 8260                                                     | 49        | 1.37%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 46        | 1.29%   |
| Realtek 802.11ac NIC                                                    | 46        | 1.29%   |
| Intel Wi-Fi 6 AX201                                                     | 46        | 1.29%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 46        | 1.29%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 42        | 1.18%   |
| Intel WiFi Link 5100                                                    | 42        | 1.18%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 39        | 1.09%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 34        | 0.95%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 34        | 0.95%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 33        | 0.92%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 33        | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 33        | 0.92%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 33        | 0.92%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 31        | 0.87%   |
| Intel Centrino Ultimate-N 6300                                          | 30        | 0.84%   |
| Intel Wireless 3160                                                     | 28        | 0.78%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 28        | 0.78%   |
| Realtek 802.11n WLAN Adapter                                            | 27        | 0.76%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 26        | 0.73%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 26        | 0.73%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 25        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1942      | 50.59%  |
| Intel                                  | 836       | 21.78%  |
| Qualcomm Atheros                       | 258       | 6.72%   |
| Broadcom                               | 227       | 5.91%   |
| Nvidia                                 | 108       | 2.81%   |
| Marvell Technology Group               | 104       | 2.71%   |
| Broadcom Limited                       | 66        | 1.72%   |
| Samsung Electronics                    | 40        | 1.04%   |
| Silicon Integrated Systems [SiS]       | 29        | 0.76%   |
| VIA Technologies                       | 28        | 0.73%   |
| ASIX Electronics                       | 28        | 0.73%   |
| Xiaomi                                 | 25        | 0.65%   |
| JMicron Technology                     | 23        | 0.6%    |
| DisplayLink                            | 18        | 0.47%   |
| Huawei Technologies                    | 14        | 0.36%   |
| MediaTek                               | 11        | 0.29%   |
| OPPO Electronics                       | 9         | 0.23%   |
| TP-Link                                | 8         | 0.21%   |
| Qualcomm                               | 8         | 0.21%   |
| Motorola PCS                           | 7         | 0.18%   |
| Aquantia                               | 7         | 0.18%   |
| Attansic Technology                    | 6         | 0.16%   |
| D-Link System                          | 4         | 0.1%    |
| Hewlett-Packard                        | 3         | 0.08%   |
| Google                                 | 3         | 0.08%   |
| Davicom Semiconductor                  | 3         | 0.08%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.05%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.05%   |
| HMD Global                             | 2         | 0.05%   |
| ASUSTek Computer                       | 2         | 0.05%   |
| Apple                                  | 2         | 0.05%   |
| ZTE WCDMA Technologies MSM             | 1         | 0.03%   |
| T & A Mobile Phones                    | 1         | 0.03%   |
| Sun Microsystems                       | 1         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| Research In Motion                     | 1         | 0.03%   |
| Novatel Wireless                       | 1         | 0.03%   |
| NetGear                                | 1         | 0.03%   |
| Motorola BCS                           | 1         | 0.03%   |
| Lenovo                                 | 1         | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1331      | 34.24%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 424       | 10.91%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 180       | 4.63%   |
| Intel Ethernet Connection I217-LM                                 | 72        | 1.85%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 62        | 1.6%    |
| Intel I211 Gigabit Network Connection                             | 56        | 1.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 54        | 1.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 53        | 1.36%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 39        | 1%      |
| Nvidia MCP61 Ethernet                                             | 39        | 1%      |
| Intel Ethernet Connection (2) I219-V                              | 33        | 0.85%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 29        | 0.75%   |
| Intel Ethernet Connection I218-LM                                 | 28        | 0.72%   |
| Intel 82577LM Gigabit Network Connection                          | 28        | 0.72%   |
| Intel 82567LM Gigabit Network Connection                          | 28        | 0.72%   |
| Intel 82579V Gigabit Network Connection                           | 26        | 0.67%   |
| Intel Ethernet Controller I225-V                                  | 25        | 0.64%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 24        | 0.62%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 23        | 0.59%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 23        | 0.59%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 23        | 0.59%   |
| Intel Ethernet Connection I217-V                                  | 23        | 0.59%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 22        | 0.57%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 22        | 0.57%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 21        | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 21        | 0.54%   |
| Intel Ethernet Connection I219-LM                                 | 21        | 0.54%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 21        | 0.54%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 21        | 0.54%   |
| Nvidia MCP79 Ethernet                                             | 20        | 0.51%   |
| Intel 82566MM Gigabit Network Connection                          | 20        | 0.51%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 19        | 0.49%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 18        | 0.46%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 18        | 0.46%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 18        | 0.46%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 18        | 0.46%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 18        | 0.46%   |
| Intel Ethernet Connection (2) I218-V                              | 18        | 0.46%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 18        | 0.46%   |
| ASIX AX88179 Gigabit Ethernet                                     | 18        | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 3626      | 51.78%  |
| WiFi     | 3273      | 46.74%  |
| Modem    | 91        | 1.3%    |
| Unknown  | 13        | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2568      | 59.64%  |
| Ethernet | 1734      | 40.27%  |
| Modem    | 2         | 0.05%   |
| Unknown  | 2         | 0.05%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 2394      | 57.53%  |
| 1     | 1570      | 37.73%  |
| 0     | 129       | 3.1%    |
| 3     | 62        | 1.49%   |
| 5     | 4         | 0.1%    |
| 7     | 1         | 0.02%   |
| 4     | 1         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 3311      | 78.8%   |
| Yes  | 891       | 21.2%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 762       | 35%     |
| Realtek Semiconductor           | 251       | 11.53%  |
| Qualcomm Atheros Communications | 235       | 10.79%  |
| Broadcom                        | 163       | 7.49%   |
| Cambridge Silicon Radio         | 127       | 5.83%   |
| Apple                           | 107       | 4.92%   |
| IMC Networks                    | 97        | 4.46%   |
| Lite-On Technology              | 68        | 3.12%   |
| Dell                            | 61        | 2.8%    |
| Hewlett-Packard                 | 54        | 2.48%   |
| Foxconn / Hon Hai               | 54        | 2.48%   |
| ASUSTek Computer                | 35        | 1.61%   |
| Toshiba                         | 33        | 1.52%   |
| Ralink                          | 21        | 0.96%   |
| Marvell Semiconductor           | 13        | 0.6%    |
| Alps Electric                   | 12        | 0.55%   |
| Realtek                         | 11        | 0.51%   |
| Foxconn International           | 10        | 0.46%   |
| MediaTek                        | 9         | 0.41%   |
| Dynex                           | 8         | 0.37%   |
| Integrated System Solution      | 6         | 0.28%   |
| Askey Computer                  | 6         | 0.28%   |
| TP-Link                         | 5         | 0.23%   |
| Taiyo Yuden                     | 4         | 0.18%   |
| Ralink Technology               | 4         | 0.18%   |
| Micro Star International        | 4         | 0.18%   |
| Belkin Components               | 4         | 0.18%   |
| Chicony Electronics             | 3         | 0.14%   |
| Qcom                            | 2         | 0.09%   |
| Sitecom Europe                  | 1         | 0.05%   |
| National Semiconductor          | 1         | 0.05%   |
| Logitech                        | 1         | 0.05%   |
| Fujitsu                         | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| D-Link System                   | 1         | 0.05%   |
| Actions                         | 1         | 0.05%   |
| Unknown                         | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 353       | 16.2%   |
| Realtek Bluetooth Radio                             | 162       | 7.43%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 127       | 5.83%   |
| Qualcomm Atheros  Bluetooth Device                  | 98        | 4.5%    |
| Intel AX201 Bluetooth                               | 90        | 4.13%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 89        | 4.08%   |
| Intel AX200 Bluetooth                               | 82        | 3.76%   |
| Realtek  Bluetooth 4.2 Adapter                      | 70        | 3.21%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 44        | 2.02%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 40        | 1.84%   |
| IMC Networks Bluetooth Device                       | 39        | 1.79%   |
| Apple Bluetooth Host Controller                     | 36        | 1.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 33        | 1.51%   |
| Intel Wireless-AC 3168 Bluetooth                    | 31        | 1.42%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 30        | 1.38%   |
| Intel AX210 Bluetooth                               | 29        | 1.33%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 27        | 1.24%   |
| IMC Networks Bluetooth Radio                        | 27        | 1.24%   |
| Apple Bluetooth USB Host Controller                 | 27        | 1.24%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 26        | 1.19%   |
| Lite-On Atheros AR3012 Bluetooth                    | 25        | 1.15%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 23        | 1.06%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 23        | 1.06%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 23        | 1.06%   |
| Ralink RT3290 Bluetooth                             | 21        | 0.96%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 0.87%   |
| HP Broadcom 2070 Bluetooth Combo                    | 19        | 0.87%   |
| Apple Bluetooth HCI                                 | 18        | 0.83%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 16        | 0.73%   |
| Dell DW375 Bluetooth Module                         | 16        | 0.73%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                | 16        | 0.73%   |
| Broadcom BCM2045B (BDC-2.1)                         | 16        | 0.73%   |
| Foxconn / Hon Hai Bluetooth Device                  | 14        | 0.64%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 14        | 0.64%   |
| Lite-On Bluetooth Device                            | 13        | 0.6%    |
| Marvell Bluetooth and Wireless LAN Composite        | 12        | 0.55%   |
| Dell Wireless 365 Bluetooth                         | 12        | 0.55%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 0.55%   |
| Broadcom BCM2045 Bluetooth                          | 12        | 0.55%   |
| Realtek Bluetooth Radio                             | 11        | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 3015      | 56.68%  |
| AMD                                  | 1073      | 20.17%  |
| Nvidia                               | 828       | 15.57%  |
| C-Media Electronics                  | 70        | 1.32%   |
| Silicon Integrated Systems [SiS]     | 33        | 0.62%   |
| VIA Technologies                     | 31        | 0.58%   |
| Creative Labs                        | 30        | 0.56%   |
| Logitech                             | 22        | 0.41%   |
| Texas Instruments                    | 15        | 0.28%   |
| JMTek                                | 14        | 0.26%   |
| Kingston Technology                  | 12        | 0.23%   |
| GN Netcom                            | 12        | 0.23%   |
| Realtek Semiconductor                | 11        | 0.21%   |
| Generalplus Technology               | 11        | 0.21%   |
| Razer USA                            | 9         | 0.17%   |
| Plantronics                          | 8         | 0.15%   |
| Creative Technology                  | 8         | 0.15%   |
| Tenx Technology                      | 7         | 0.13%   |
| ASUSTek Computer                     | 7         | 0.13%   |
| SteelSeries ApS                      | 6         | 0.11%   |
| KTMicro                              | 5         | 0.09%   |
| Corsair                              | 4         | 0.08%   |
| Thesycon Systemsoftware & Consulting | 3         | 0.06%   |
| Samsung Electronics                  | 3         | 0.06%   |
| Lenovo                               | 3         | 0.06%   |
| Focusrite-Novation                   | 3         | 0.06%   |
| Astro Gaming                         | 3         | 0.06%   |
| Yamaha                               | 2         | 0.04%   |
| Turtle Beach                         | 2         | 0.04%   |
| Sennheiser Communications            | 2         | 0.04%   |
| RODE Microphones                     | 2         | 0.04%   |
| Numark                               | 2         | 0.04%   |
| Micronas                             | 2         | 0.04%   |
| Micro Star International             | 2         | 0.04%   |
| Klipsch Audio                        | 2         | 0.04%   |
| Ensoniq                              | 2         | 0.04%   |
| DSEA A/S                             | 2         | 0.04%   |
| DigiTech                             | 2         | 0.04%   |
| BEHRINGER International              | 2         | 0.04%   |
| Audio-Technica                       | 2         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 348       | 5.55%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 309       | 4.93%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 270       | 4.31%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 247       | 3.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 208       | 3.32%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 203       | 3.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 202       | 3.22%   |
| AMD FCH Azalia Controller                                                                         | 187       | 2.98%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 186       | 2.97%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 184       | 2.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 150       | 2.39%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 127       | 2.03%   |
| Intel 8 Series HD Audio Controller                                                                | 125       | 2%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 121       | 1.93%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 95        | 1.52%   |
| AMD Kabini HDMI/DP Audio                                                                          | 92        | 1.47%   |
| Intel Cannon Lake PCH cAVS                                                                        | 90        | 1.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 87        | 1.39%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 86        | 1.37%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 78        | 1.25%   |
| Intel Broadwell-U Audio Controller                                                                | 75        | 1.2%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 74        | 1.18%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 73        | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 71        | 1.13%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 70        | 1.12%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 69        | 1.1%    |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 63        | 1.01%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 56        | 0.89%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 55        | 0.88%   |
| Nvidia High Definition Audio Controller                                                           | 53        | 0.85%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 52        | 0.83%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 51        | 0.81%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 50        | 0.8%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 50        | 0.8%    |
| AMD High Definition Audio Controller                                                              | 47        | 0.75%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 45        | 0.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 41        | 0.65%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 41        | 0.65%   |
| Nvidia MCP61 High Definition Audio                                                                | 40        | 0.64%   |
| AMD Trinity HDMI Audio Controller                                                                 | 39        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 187       | 21.97%  |
| SK hynix            | 163       | 19.15%  |
| Unknown             | 115       | 13.51%  |
| Micron Technology   | 81        | 9.52%   |
| Kingston            | 73        | 8.58%   |
| Crucial             | 38        | 4.47%   |
| Corsair             | 27        | 3.17%   |
| G.Skill             | 22        | 2.59%   |
| Unknown (ABCD)      | 19        | 2.23%   |
| Nanya Technology    | 17        | 2%      |
| Elpida              | 16        | 1.88%   |
| A-DATA Technology   | 15        | 1.76%   |
| Ramaxel Technology  | 13        | 1.53%   |
| Team                | 7         | 0.82%   |
| Qimonda             | 6         | 0.71%   |
| Patriot             | 6         | 0.71%   |
| Smart               | 4         | 0.47%   |
| Unknown             | 4         | 0.47%   |
| Avant               | 3         | 0.35%   |
| Transcend           | 2         | 0.24%   |
| Timetec             | 2         | 0.24%   |
| Teikon              | 2         | 0.24%   |
| High Bridge         | 2         | 0.24%   |
| CSX                 | 2         | 0.24%   |
| Wilk                | 1         | 0.12%   |
| Walton Chaintech    | 1         | 0.12%   |
| Unknown (08B5)      | 1         | 0.12%   |
| Unifosa             | 1         | 0.12%   |
| Toshiba             | 1         | 0.12%   |
| Strontium           | 1         | 0.12%   |
| Smart Brazil        | 1         | 0.12%   |
| SHARETRONIC         | 1         | 0.12%   |
| Ramos Technology    | 1         | 0.12%   |
| PUSKILL             | 1         | 0.12%   |
| PNY                 | 1         | 0.12%   |
| Netlist             | 1         | 0.12%   |
| Nayna               | 1         | 0.12%   |
| Kingmax             | 1         | 0.12%   |
| HBS                 | 1         | 0.12%   |
| GSkill              | 1         | 0.12%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 17        | 1.87%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 12        | 1.32%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 9         | 0.99%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 8         | 0.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 8         | 0.88%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.77%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.77%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 800MT/s            | 6         | 0.66%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 6         | 0.66%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.66%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.66%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.55%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.55%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.55%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.55%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 5         | 0.55%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.55%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 4         | 0.44%   |
| SK hynix RAM HYMP112S64CP6-S6 1GB SODIMM DDR2 975MT/s            | 4         | 0.44%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.44%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.44%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s    | 4         | 0.44%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 4         | 0.44%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.44%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 4         | 0.44%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.44%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.44%   |
| Unknown                                                          | 4         | 0.44%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 3         | 0.33%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 3         | 0.33%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                    | 3         | 0.33%   |
| SK hynix RAM Module 2048MB SODIMM DDR3 1066MT/s                  | 3         | 0.33%   |
| SK hynix RAM HYMP125S64CP8-Y5 2GB SODIMM DDR2 667MT/s            | 3         | 0.33%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.33%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.33%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.33%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 3         | 0.33%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.33%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 3         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 279       | 38.01%  |
| DDR4    | 240       | 32.7%   |
| DDR2    | 79        | 10.76%  |
| LPDDR4  | 38        | 5.18%   |
| SDRAM   | 35        | 4.77%   |
| Unknown | 27        | 3.68%   |
| LPDDR3  | 20        | 2.72%   |
| DDR     | 9         | 1.23%   |
| DRAM    | 6         | 0.82%   |
| LPDDR5  | 1         | 0.14%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 450       | 62.33%  |
| DIMM         | 213       | 29.5%   |
| Row Of Chips | 53        | 7.34%   |
| Chip         | 3         | 0.42%   |
| Unknown      | 2         | 0.28%   |
| FB-DIMM      | 1         | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 260       | 31.82%  |
| 8192  | 249       | 30.48%  |
| 2048  | 162       | 19.83%  |
| 1024  | 67        | 8.2%    |
| 16384 | 54        | 6.61%   |
| 512   | 12        | 1.47%   |
| 32768 | 11        | 1.35%   |
| 256   | 2         | 0.24%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 178       | 22.31%  |
| 2667    | 85        | 10.65%  |
| 3200    | 75        | 9.4%    |
| 1333    | 62        | 7.77%   |
| 2400    | 51        | 6.39%   |
| 667     | 41        | 5.14%   |
| Unknown | 36        | 4.51%   |
| 1334    | 34        | 4.26%   |
| 2133    | 31        | 3.88%   |
| 800     | 24        | 3.01%   |
| 1066    | 20        | 2.51%   |
| 3600    | 15        | 1.88%   |
| 1867    | 13        | 1.63%   |
| 4267    | 12        | 1.5%    |
| 3266    | 12        | 1.5%    |
| 533     | 11        | 1.38%   |
| 4199    | 9         | 1.13%   |
| 975     | 9         | 1.13%   |
| 2048    | 8         | 1%      |
| 3000    | 6         | 0.75%   |
| 1866    | 6         | 0.75%   |
| 400     | 6         | 0.75%   |
| 2666    | 4         | 0.5%    |
| 1800    | 4         | 0.5%    |
| 1067    | 4         | 0.5%    |
| 333     | 4         | 0.5%    |
| 8400    | 3         | 0.38%   |
| 3866    | 3         | 0.38%   |
| 3466    | 3         | 0.38%   |
| 2933    | 3         | 0.38%   |
| 2800    | 3         | 0.38%   |
| 4266    | 2         | 0.25%   |
| 3733    | 2         | 0.25%   |
| 3666    | 2         | 0.25%   |
| 3400    | 2         | 0.25%   |
| 3333    | 2         | 0.25%   |
| 1639    | 2         | 0.25%   |
| 49926   | 1         | 0.13%   |
| 6400    | 1         | 0.13%   |
| 4800    | 1         | 0.13%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 36        | 32.14%  |
| Canon                 | 25        | 22.32%  |
| Brother Industries    | 17        | 15.18%  |
| Seiko Epson           | 13        | 11.61%  |
| Samsung Electronics   | 13        | 11.61%  |
| STMicroelectronics    | 2         | 1.79%   |
| Zebra                 | 1         | 0.89%   |
| Toshiba TEC           | 1         | 0.89%   |
| Ricoh                 | 1         | 0.89%   |
| QinHeng Electronics   | 1         | 0.89%   |
| Pantum                | 1         | 0.89%   |
| Lexmark International | 1         | 0.89%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Canon TS3100 series                                       | 4         | 3.57%   |
| Seiko Epson L3110 Series                                  | 3         | 2.68%   |
| Canon PIXMA MG2500 Series                                 | 3         | 2.68%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 2         | 1.79%   |
| Samsung SCX-3400 Series                                   | 2         | 1.79%   |
| Samsung ML-216x Series Laser Printer                      | 2         | 1.79%   |
| Samsung CLX-3300 Series                                   | 2         | 1.79%   |
| HP LaserJet Professional P 1102w                          | 2         | 1.79%   |
| HP ENVY Photo 6200 series                                 | 2         | 1.79%   |
| HP ENVY 5000 series                                       | 2         | 1.79%   |
| HP ENVY 4520 series                                       | 2         | 1.79%   |
| HP DeskJet 2700 series                                    | 2         | 1.79%   |
| HP DeskJet 2130 series                                    | 2         | 1.79%   |
| HP DeskJet 1110 series                                    | 2         | 1.79%   |
| Canon PIXMA MX340                                         | 2         | 1.79%   |
| Canon MF4010 series                                       | 2         | 1.79%   |
| Brother HL-2130 series                                    | 2         | 1.79%   |
| Zebra ZP 450 Printer                                      | 1         | 0.89%   |
| Toshiba TEC e-STD120 USB                                  | 1         | 0.89%   |
| Seiko Epson XP-7100 Series                                | 1         | 0.89%   |
| Seiko Epson XP-200 Series                                 | 1         | 0.89%   |
| Seiko Epson WF-2010 Series                                | 1         | 0.89%   |
| Seiko Epson Printer                                       | 1         | 0.89%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 0.89%   |
| Seiko Epson L365 Series                                   | 1         | 0.89%   |
| Seiko Epson L355 Series                                   | 1         | 0.89%   |
| Seiko Epson L220 Series                                   | 1         | 0.89%   |
| Seiko Epson L120 Series                                   | 1         | 0.89%   |
| Seiko Epson ET-2820 Series                                | 1         | 0.89%   |
| Samsung SCX-483x 5x3x Series                              | 1         | 0.89%   |
| Samsung SCX-4200 series                                   | 1         | 0.89%   |
| Samsung ML-2950 Series                                    | 1         | 0.89%   |
| Samsung ML-2010P Mono Laser Printer                       | 1         | 0.89%   |
| Samsung M2070 Series                                      | 1         | 0.89%   |
| Samsung M2020 Series                                      | 1         | 0.89%   |
| Samsung C460 Series                                       | 1         | 0.89%   |
| Ricoh SP C250SF                                           | 1         | 0.89%   |
| QinHeng CH340S                                            | 1         | 0.89%   |
| Pantum P2500W series                                      | 1         | 0.89%   |
| Lexmark International 2400 series                         | 1         | 0.89%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 11        | 73.33%  |
| Seiko Epson     | 2         | 13.33%  |
| Hewlett-Packard | 2         | 13.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 13.33%  |
| Canon CanoScan LIDE 25                      | 2         | 13.33%  |
| Canon CanoScan LiDE 100                     | 2         | 13.33%  |
| HP ScanJet 2400c                            | 1         | 6.67%   |
| HP PSC 1200                                 | 1         | 6.67%   |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 6.67%   |
| Canon CanoScan LiDE 90                      | 1         | 6.67%   |
| Canon CanoScan LiDE 60                      | 1         | 6.67%   |
| Canon CanoScan LiDE 200                     | 1         | 6.67%   |
| Canon CanoScan LiDE 110                     | 1         | 6.67%   |
| Canon CanoScan D660U                        | 1         | 6.67%   |
| Canon CanoScan 8800F                        | 1         | 6.67%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 530       | 23.16%  |
| Microdia                               | 212       | 9.27%   |
| Realtek Semiconductor                  | 172       | 7.52%   |
| IMC Networks                           | 163       | 7.12%   |
| Acer                                   | 141       | 6.16%   |
| Sunplus Innovation Technology          | 118       | 5.16%   |
| Suyin                                  | 111       | 4.85%   |
| Apple                                  | 106       | 4.63%   |
| Cheng Uei Precision Industry (Foxlink) | 103       | 4.5%    |
| Quanta                                 | 76        | 3.32%   |
| Logitech                               | 69        | 3.02%   |
| Syntek                                 | 51        | 2.23%   |
| Silicon Motion                         | 48        | 2.1%    |
| Lite-On Technology                     | 39        | 1.7%    |
| Alcor Micro                            | 38        | 1.66%   |
| Ricoh                                  | 31        | 1.35%   |
| Samsung Electronics                    | 25        | 1.09%   |
| Microsoft                              | 20        | 0.87%   |
| Importek                               | 17        | 0.74%   |
| ALi                                    | 16        | 0.7%    |
| Primax Electronics                     | 14        | 0.61%   |
| Luxvisions Innotech Limited            | 14        | 0.61%   |
| Z-Star Microelectronics                | 13        | 0.57%   |
| Generalplus Technology                 | 12        | 0.52%   |
| USB Camera                             | 11        | 0.48%   |
| GEMBIRD                                | 10        | 0.44%   |
| Lenovo                                 | 9         | 0.39%   |
| ARC International                      | 9         | 0.39%   |
| Sonix Technology                       | 8         | 0.35%   |
| OmniVision Technologies                | 8         | 0.35%   |
| Genesys Logic                          | 7         | 0.31%   |
| Unknown                                | 6         | 0.26%   |
| SunplusIT                              | 5         | 0.22%   |
| Sunplus Technology                     | 5         | 0.22%   |
| Cubeternet                             | 5         | 0.22%   |
| Pixart Imaging                         | 4         | 0.17%   |
| Jieli Technology                       | 4         | 0.17%   |
| Huawei Technologies                    | 4         | 0.17%   |
| Razer USA                              | 3         | 0.13%   |
| LG Electronics                         | 3         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 58        | 2.52%   |
| Realtek Integrated_Webcam_HD                            | 40        | 1.74%   |
| Microdia Integrated_Webcam_HD                           | 38        | 1.65%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 37        | 1.61%   |
| Acer Integrated Camera                                  | 35        | 1.52%   |
| Microdia Integrated Webcam                              | 34        | 1.48%   |
| Apple FaceTime HD Camera (Built-in)                     | 32        | 1.39%   |
| Chicony HP TrueVision HD                                | 30        | 1.3%    |
| Chicony HD WebCam                                       | 30        | 1.3%    |
| Apple iPhone5/5C/5S/6                                   | 30        | 1.3%    |
| Chicony USB 2.0 Camera                                  | 27        | 1.17%   |
| Acer Lenovo EasyCamera                                  | 27        | 1.17%   |
| Samsung Galaxy A5 (MTP)                                 | 25        | 1.09%   |
| Syntek Integrated Camera                                | 24        | 1.04%   |
| Chicony TOSHIBA Web Camera - HD                         | 24        | 1.04%   |
| Realtek USB Camera                                      | 22        | 0.96%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 22        | 0.96%   |
| IMC Networks Integrated Camera                          | 22        | 0.96%   |
| Chicony HP TrueVision HD Camera                         | 22        | 0.96%   |
| Apple Built-in iSight                                   | 21        | 0.91%   |
| Sunplus Integrated_Webcam_HD                            | 20        | 0.87%   |
| Microdia USB 2.0 Camera                                 | 19        | 0.83%   |
| Chicony EasyCamera                                      | 19        | 0.83%   |
| Sunplus HD WebCam                                       | 18        | 0.78%   |
| Logitech Webcam C270                                    | 18        | 0.78%   |
| Chicony HP HD Webcam                                    | 18        | 0.78%   |
| Chicony Lenovo EasyCamera                               | 17        | 0.74%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 17        | 0.74%   |
| Suyin HP Truevision HD                                  | 16        | 0.7%    |
| Realtek Integrated Webcam                               | 16        | 0.7%    |
| Chicony VGA Webcam                                      | 16        | 0.7%    |
| Chicony USB2.0 VGA UVC WebCam                           | 16        | 0.7%    |
| Alcor Micro USB 2.0 Camera                              | 16        | 0.7%    |
| Chicony CNF9055 Toshiba Webcam                          | 15        | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 15        | 0.65%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 14        | 0.61%   |
| Quanta HP Webcam                                        | 14        | 0.61%   |
| Quanta HP TrueVision HD Camera                          | 14        | 0.61%   |
| Microdia Sonix USB 2.0 Camera                           | 14        | 0.61%   |
| Microdia Laptop_Integrated_Webcam_HD                    | 14        | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 159       | 43.68%  |
| AuthenTec                  | 55        | 15.11%  |
| Synaptics                  | 37        | 10.16%  |
| Shenzhen Goodix Technology | 36        | 9.89%   |
| Upek                       | 29        | 7.97%   |
| Elan Microelectronics      | 18        | 4.95%   |
| STMicroelectronics         | 17        | 4.67%   |
| LighTuning Technology      | 10        | 2.75%   |
| Samsung Electronics        | 2         | 0.55%   |
| Focal-systems.Corp         | 1         | 0.27%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 35        | 9.62%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 28        | 7.69%   |
| Shenzhen Goodix  FingerPrint Device                                        | 20        | 5.49%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 19        | 5.22%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 18        | 4.95%   |
| STMicroelectronics Fingerprint Reader                                      | 17        | 4.67%   |
| AuthenTec AES2810                                                          | 17        | 4.67%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 16        | 4.4%    |
| Validity Sensors VFS5011 Fingerprint Reader                                | 15        | 4.12%   |
| Validity Sensors Fingerprint scanner                                       | 15        | 4.12%   |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 3.57%   |
| Unknown                                                                    | 13        | 3.57%   |
| Validity Sensors VFS491                                                    | 12        | 3.3%    |
| Elan ELAN:Fingerprint                                                      | 10        | 2.75%   |
| AuthenTec AES1600                                                          | 9         | 2.47%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.2%    |
| Synaptics  WBDI                                                            | 8         | 2.2%    |
| Elan ELAN:ARM-M4                                                           | 8         | 2.2%    |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 7         | 1.92%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 6         | 1.65%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 1.65%   |
| AuthenTec Fingerprint Sensor                                               | 6         | 1.65%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 1.37%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1.1%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 4         | 1.1%    |
| Validity Sensors VFS101 Fingerprint Reader                                 | 4         | 1.1%    |
| Validity Sensors Synaptics WBDI                                            | 4         | 1.1%    |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 1.1%    |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.1%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 1.1%    |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.82%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.82%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.55%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.55%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 0.55%   |
| LighTuning Fingerprint Sensor                                              | 2         | 0.55%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.55%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.55%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.27%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 1         | 0.27%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 75        | 49.02%  |
| Alcor Micro                       | 25        | 16.34%  |
| O2 Micro                          | 21        | 13.73%  |
| Lenovo                            | 9         | 5.88%   |
| Upek                              | 7         | 4.58%   |
| Realtek Semiconductor             | 4         | 2.61%   |
| SCM Microsystems                  | 3         | 1.96%   |
| Yubico.com                        | 2         | 1.31%   |
| Advanced Card Systems             | 2         | 1.31%   |
| VASCO Data Security International | 1         | 0.65%   |
| Reiner SCT Kartensysteme          | 1         | 0.65%   |
| OmniKey                           | 1         | 0.65%   |
| Kobil Systems                     | 1         | 0.65%   |
| Fujitsu Siemens Computers         | 1         | 0.65%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 37        | 24.18%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 24        | 15.69%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 13.07%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 17        | 11.11%  |
| Broadcom 5880                                                                | 14        | 9.15%   |
| Lenovo Integrated Smart Card Reader                                          | 9         | 5.88%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 7         | 4.58%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 4         | 2.61%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 2.61%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.31%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.31%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.31%   |
| Broadcom 58200                                                               | 2         | 1.31%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.65%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.65%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 1         | 0.65%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.65%   |
| Kobil Systems KOBIL Class 3 Reader                                           | 1         | 0.65%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.65%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.65%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.65%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.65%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2994      | 71.05%  |
| 1     | 1003      | 23.8%   |
| 2     | 198       | 4.7%    |
| 3     | 15        | 0.36%   |
| 4     | 3         | 0.07%   |
| 7     | 1         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 358       | 25.37%  |
| Graphics card            | 334       | 23.67%  |
| Net/wireless             | 249       | 17.65%  |
| Chipcard                 | 142       | 10.06%  |
| Multimedia controller    | 106       | 7.51%   |
| Modem                    | 38        | 2.69%   |
| Communication controller | 38        | 2.69%   |
| Storage                  | 36        | 2.55%   |
| Bluetooth                | 28        | 1.98%   |
| Sound                    | 16        | 1.13%   |
| Camera                   | 13        | 0.92%   |
| Unassigned class         | 12        | 0.85%   |
| Flash memory             | 11        | 0.78%   |
| Net/ethernet             | 6         | 0.43%   |
| Card reader              | 6         | 0.43%   |
| Network                  | 4         | 0.28%   |
| Dvb card                 | 4         | 0.28%   |
| Storage/nvme             | 3         | 0.21%   |
| Storage/ide              | 3         | 0.21%   |
| Storage/raid             | 2         | 0.14%   |
| Unclassified device      | 1         | 0.07%   |
| Storage/ata              | 1         | 0.07%   |

