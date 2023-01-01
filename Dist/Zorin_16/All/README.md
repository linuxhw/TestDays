Zorin 16 - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for Zorin 16.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Zorin_16/Desktop/README.md) and [notebooks](/Dist/Zorin_16/Notebook/README.md).

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

Total: 3513

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
| Dell          | 0MGK50 A04                  | Desktop     | [931b01be38](https://linux-hardware.org/?probe=931b01be38) | Dec 20, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [5212fb0d93](https://linux-hardware.org/?probe=5212fb0d93) | Dec 20, 2022 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [9f456f73eb](https://linux-hardware.org/?probe=9f456f73eb) | Dec 20, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [03e2c64868](https://linux-hardware.org/?probe=03e2c64868) | Dec 20, 2022 |
| ASRock        | Z170 Pro4                   | Desktop     | [ca027f264a](https://linux-hardware.org/?probe=ca027f264a) | Dec 20, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [83df1364c8](https://linux-hardware.org/?probe=83df1364c8) | Dec 20, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [0e5b8434fe](https://linux-hardware.org/?probe=0e5b8434fe) | Dec 20, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [83a3d8e955](https://linux-hardware.org/?probe=83a3d8e955) | Dec 19, 2022 |
| GPD           | G1619-04                    | Notebook    | [f184c297f2](https://linux-hardware.org/?probe=f184c297f2) | Dec 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X403... | Notebook    | [3ec240466e](https://linux-hardware.org/?probe=3ec240466e) | Dec 19, 2022 |
| Lenovo        | 3106 SDK0J40697 WIN 3305... | Desktop     | [87907abff7](https://linux-hardware.org/?probe=87907abff7) | Dec 19, 2022 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [08f3a88ab3](https://linux-hardware.org/?probe=08f3a88ab3) | Dec 19, 2022 |
| HP            | 8715                        | Mini pc     | [a6f7705fd4](https://linux-hardware.org/?probe=a6f7705fd4) | Dec 19, 2022 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [b1bd890ed0](https://linux-hardware.org/?probe=b1bd890ed0) | Dec 19, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [cf1ccbf76a](https://linux-hardware.org/?probe=cf1ccbf76a) | Dec 19, 2022 |
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
| ASUSTek       | K55VD                       | Notebook    | [d8a78ad824](https://linux-hardware.org/?probe=d8a78ad824) | Nov 07, 2022 |
| MSI           | H81M-P33                    | Desktop     | [2ef23ed4ac](https://linux-hardware.org/?probe=2ef23ed4ac) | Nov 07, 2022 |
| ASUSTek       | U36SD                       | Notebook    | [d6b92cbdaa](https://linux-hardware.org/?probe=d6b92cbdaa) | Nov 07, 2022 |
| HP            | 240 G8                      | Notebook    | [cbeff38360](https://linux-hardware.org/?probe=cbeff38360) | Nov 07, 2022 |
| HP            | 240 G8                      | Notebook    | [0fadcc21ac](https://linux-hardware.org/?probe=0fadcc21ac) | Nov 07, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [e44a807758](https://linux-hardware.org/?probe=e44a807758) | Nov 06, 2022 |
| Acer          | H81H3-M4                    | Desktop     | [40c67913d8](https://linux-hardware.org/?probe=40c67913d8) | Nov 06, 2022 |
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
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [ae6fd2de89](https://linux-hardware.org/?probe=ae6fd2de89) | Oct 29, 2022 |
| MSI           | GL72 6QD                    | Notebook    | [2f7c223f5a](https://linux-hardware.org/?probe=2f7c223f5a) | Oct 29, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [068d4ec2e6](https://linux-hardware.org/?probe=068d4ec2e6) | Oct 29, 2022 |
| Acer          | Extensa 5635ZG              | Notebook    | [8c0a7c0aa1](https://linux-hardware.org/?probe=8c0a7c0aa1) | Oct 29, 2022 |
| Dell          | 0T2HR0 A02                  | Desktop     | [e4b1137777](https://linux-hardware.org/?probe=e4b1137777) | Oct 29, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [2c57f9b6a3](https://linux-hardware.org/?probe=2c57f9b6a3) | Oct 29, 2022 |
| Toshiba       | Satellite C660              | Notebook    | [242fa16882](https://linux-hardware.org/?probe=242fa16882) | Oct 29, 2022 |
| ASUSTek       | STRIX X99 GAMING            | Desktop     | [f111078004](https://linux-hardware.org/?probe=f111078004) | Oct 29, 2022 |
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
| MSI           | GT70 2PE                    | Notebook    | [26d9f8ba04](https://linux-hardware.org/?probe=26d9f8ba04) | Oct 25, 2022 |
| Toshiba       | K201                        | Notebook    | [63a892bae3](https://linux-hardware.org/?probe=63a892bae3) | Oct 25, 2022 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [aa82a1f3c9](https://linux-hardware.org/?probe=aa82a1f3c9) | Oct 24, 2022 |
| MSI           | GE62 7RE                    | Notebook    | [bd5b8943f4](https://linux-hardware.org/?probe=bd5b8943f4) | Oct 24, 2022 |
| Samsung       | 305V4A/305V5A/3415VA        | Notebook    | [d8f70347cf](https://linux-hardware.org/?probe=d8f70347cf) | Oct 24, 2022 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [26e7b206ef](https://linux-hardware.org/?probe=26e7b206ef) | Oct 24, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [e894ec1b8d](https://linux-hardware.org/?probe=e894ec1b8d) | Oct 24, 2022 |
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
| HP            | ZBook 17 G5                 | Notebook    | [19db5a4e7c](https://linux-hardware.org/?probe=19db5a4e7c) | Oct 07, 2022 |
| TERRA         | TERRAPC                     | Notebook    | [ec9068f7ea](https://linux-hardware.org/?probe=ec9068f7ea) | Oct 07, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [005d2d7671](https://linux-hardware.org/?probe=005d2d7671) | Oct 07, 2022 |
| HP            | 822A                        | Desktop     | [c893a1b314](https://linux-hardware.org/?probe=c893a1b314) | Oct 07, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [d5a346bdd1](https://linux-hardware.org/?probe=d5a346bdd1) | Oct 07, 2022 |
| Dell          | 0YP696 A00                  | Desktop     | [588d3a6132](https://linux-hardware.org/?probe=588d3a6132) | Oct 07, 2022 |
| HP            | 8265                        | Desktop     | [ddf5f03d86](https://linux-hardware.org/?probe=ddf5f03d86) | Oct 07, 2022 |
| HP            | 843B                        | Desktop     | [5a744e115f](https://linux-hardware.org/?probe=5a744e115f) | Oct 06, 2022 |
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
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b8d65ced41](https://linux-hardware.org/?probe=b8d65ced41) | Oct 02, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b5b057439d](https://linux-hardware.org/?probe=b5b057439d) | Oct 02, 2022 |
| Lenovo        | V570 1066EDG                | Notebook    | [8e2439c590](https://linux-hardware.org/?probe=8e2439c590) | Oct 01, 2022 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [592adc6c9b](https://linux-hardware.org/?probe=592adc6c9b) | Oct 01, 2022 |
| HP            | 843B                        | Desktop     | [b683039e3b](https://linux-hardware.org/?probe=b683039e3b) | Oct 01, 2022 |
| Lenovo        | ThinkPad Yoga 11e 20DAS0... | Notebook    | [dc7e0ada81](https://linux-hardware.org/?probe=dc7e0ada81) | Oct 01, 2022 |
| Acer          | Aspire 4733Z                | Notebook    | [4be4debbe5](https://linux-hardware.org/?probe=4be4debbe5) | Oct 01, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [f42501fcc3](https://linux-hardware.org/?probe=f42501fcc3) | Oct 01, 2022 |
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
| HP            | 843C                        | Desktop     | [e27595d303](https://linux-hardware.org/?probe=e27595d303) | Sep 29, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [01ebd7e70b](https://linux-hardware.org/?probe=01ebd7e70b) | Sep 29, 2022 |
| Toshiba       | Satellite C55-C             | Notebook    | [d2c06711d7](https://linux-hardware.org/?probe=d2c06711d7) | Sep 29, 2022 |
| HP            | Compaq 6730s                | Notebook    | [62fc1b721e](https://linux-hardware.org/?probe=62fc1b721e) | Sep 29, 2022 |
| Dell          | Inspiron 3582               | Notebook    | [8cd21b783a](https://linux-hardware.org/?probe=8cd21b783a) | Sep 28, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [defae2e862](https://linux-hardware.org/?probe=defae2e862) | Sep 28, 2022 |
| Dell          | Inspiron 5559               | Notebook    | [c23649cdd4](https://linux-hardware.org/?probe=c23649cdd4) | Sep 28, 2022 |
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
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [82b3d89bf9](https://linux-hardware.org/?probe=82b3d89bf9) | Sep 20, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [37dbdb48dd](https://linux-hardware.org/?probe=37dbdb48dd) | Sep 20, 2022 |
| Dell          | G15 5515                    | Notebook    | [f308590417](https://linux-hardware.org/?probe=f308590417) | Sep 20, 2022 |
| Dell          | G15 5515                    | Notebook    | [d6a647ab30](https://linux-hardware.org/?probe=d6a647ab30) | Sep 20, 2022 |
| HP            | Pavilion g7                 | Notebook    | [d51d3d282a](https://linux-hardware.org/?probe=d51d3d282a) | Sep 20, 2022 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [9417681a63](https://linux-hardware.org/?probe=9417681a63) | Sep 19, 2022 |
| Lenovo        | ThinkCentre M71e 3157AE2    | Desktop     | [9022058466](https://linux-hardware.org/?probe=9022058466) | Sep 19, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d3140eaa89](https://linux-hardware.org/?probe=d3140eaa89) | Sep 19, 2022 |
| Alienware     | 18                          | Notebook    | [fda9eabd7e](https://linux-hardware.org/?probe=fda9eabd7e) | Sep 18, 2022 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [bceb6698c2](https://linux-hardware.org/?probe=bceb6698c2) | Sep 18, 2022 |
| Microtech     | CoreBook                    | Notebook    | [6b1a53d2c2](https://linux-hardware.org/?probe=6b1a53d2c2) | Sep 18, 2022 |
| HP            | 0AA8h                       | Desktop     | [c79bdb21ed](https://linux-hardware.org/?probe=c79bdb21ed) | Sep 18, 2022 |
| Ematic        | EWT118                      | Notebook    | [41670ebd30](https://linux-hardware.org/?probe=41670ebd30) | Sep 18, 2022 |
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
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [875435f3f0](https://linux-hardware.org/?probe=875435f3f0) | Sep 15, 2022 |
| Toshiba       | Satellite C855              | Notebook    | [bd34f35e50](https://linux-hardware.org/?probe=bd34f35e50) | Sep 15, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [aeac7cfb74](https://linux-hardware.org/?probe=aeac7cfb74) | Sep 14, 2022 |
| IP3 Tech      | GB3B                        | Mini pc     | [32884ec101](https://linux-hardware.org/?probe=32884ec101) | Sep 14, 2022 |
| Dell          | 0TW904 A01                  | Desktop     | [141188a631](https://linux-hardware.org/?probe=141188a631) | Sep 14, 2022 |
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
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [0701918099](https://linux-hardware.org/?probe=0701918099) | Sep 11, 2022 |
| HP            | 0A54h                       | Desktop     | [2c88c7fd30](https://linux-hardware.org/?probe=2c88c7fd30) | Sep 10, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [e6bf2b7f3f](https://linux-hardware.org/?probe=e6bf2b7f3f) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX Z690-I GAMING ... | Desktop     | [d13cf99728](https://linux-hardware.org/?probe=d13cf99728) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1e43753d7a](https://linux-hardware.org/?probe=1e43753d7a) | Sep 10, 2022 |
| MSI           | 2AE0                        | Desktop     | [a2b046dd4e](https://linux-hardware.org/?probe=a2b046dd4e) | Sep 10, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [c027a7cf99](https://linux-hardware.org/?probe=c027a7cf99) | Sep 10, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [4e96c157b7](https://linux-hardware.org/?probe=4e96c157b7) | Sep 10, 2022 |
| HP            | 3031h                       | Desktop     | [ea434d67b5](https://linux-hardware.org/?probe=ea434d67b5) | Sep 10, 2022 |
| HP            | 3031h                       | Desktop     | [feddf42c9f](https://linux-hardware.org/?probe=feddf42c9f) | Sep 10, 2022 |
| AZW           | Z83-V                       | Notebook    | [70e8dba2ef](https://linux-hardware.org/?probe=70e8dba2ef) | Sep 10, 2022 |
| AZW           | Z83-V                       | Notebook    | [622725ab19](https://linux-hardware.org/?probe=622725ab19) | Sep 10, 2022 |
| Acer          | Aspire 7745G                | Notebook    | [a41158c2cc](https://linux-hardware.org/?probe=a41158c2cc) | Sep 10, 2022 |
| HP            | 0AA8h                       | Desktop     | [4e9a1e883c](https://linux-hardware.org/?probe=4e9a1e883c) | Sep 09, 2022 |
| Toshiba       | Satellite P200              | Notebook    | [c49fec0796](https://linux-hardware.org/?probe=c49fec0796) | Sep 09, 2022 |
| Medion        | Akoya E1318T                | Notebook    | [749a12fd63](https://linux-hardware.org/?probe=749a12fd63) | Sep 09, 2022 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [678759289b](https://linux-hardware.org/?probe=678759289b) | Sep 09, 2022 |
| Acer          | Aspire C22-820              | All in one  | [7b21589632](https://linux-hardware.org/?probe=7b21589632) | Sep 09, 2022 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [e11963681c](https://linux-hardware.org/?probe=e11963681c) | Sep 08, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [db80996c7a](https://linux-hardware.org/?probe=db80996c7a) | Sep 08, 2022 |
| HP            | Laptop 17-bs0xx             | Notebook    | [ebf0bfea05](https://linux-hardware.org/?probe=ebf0bfea05) | Sep 08, 2022 |
| Dell          | Latitude E5420              | Notebook    | [b80d26540d](https://linux-hardware.org/?probe=b80d26540d) | Sep 08, 2022 |
| ASUSTek       | UX331UA                     | Notebook    | [e1e0acfdf3](https://linux-hardware.org/?probe=e1e0acfdf3) | Sep 08, 2022 |
| Dell          | Latitude E4300              | Notebook    | [5d3a9edf5d](https://linux-hardware.org/?probe=5d3a9edf5d) | Sep 07, 2022 |
| Lenovo        | MAHOBAY                     | Desktop     | [2619e261d1](https://linux-hardware.org/?probe=2619e261d1) | Sep 07, 2022 |
| Lenovo        | ThinkPad E570 20H50047US    | Notebook    | [70b198055e](https://linux-hardware.org/?probe=70b198055e) | Sep 07, 2022 |
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
| Lenovo        | G505s 20255                 | Notebook    | [58a439770d](https://linux-hardware.org/?probe=58a439770d) | Aug 15, 2022 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [e80596ea44](https://linux-hardware.org/?probe=e80596ea44) | Aug 15, 2022 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [01beed2be8](https://linux-hardware.org/?probe=01beed2be8) | Aug 15, 2022 |
| HP            | 339A                        | Desktop     | [c3e5458c9a](https://linux-hardware.org/?probe=c3e5458c9a) | Aug 15, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [5171fd1732](https://linux-hardware.org/?probe=5171fd1732) | Aug 15, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [08fa90340d](https://linux-hardware.org/?probe=08fa90340d) | Aug 14, 2022 |
| MAXSUN        | MS-TZZ A520M                | Desktop     | [aa844d0dce](https://linux-hardware.org/?probe=aa844d0dce) | Aug 14, 2022 |
| Lenovo        | IdeaPad Z580                | Notebook    | [f9d6b2f915](https://linux-hardware.org/?probe=f9d6b2f915) | Aug 14, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2257302110](https://linux-hardware.org/?probe=2257302110) | Aug 14, 2022 |
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
| Google        | Kasumi                      | Notebook    | [0d1ce61572](https://linux-hardware.org/?probe=0d1ce61572) | Aug 11, 2022 |
| Google        | Kasumi                      | Notebook    | [47ebd6bcac](https://linux-hardware.org/?probe=47ebd6bcac) | Aug 11, 2022 |
| ASUSTek       | J1800I-C/BR                 | Desktop     | [41cd4b02f1](https://linux-hardware.org/?probe=41cd4b02f1) | Aug 11, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [687375ec7c](https://linux-hardware.org/?probe=687375ec7c) | Aug 11, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [4e54f20c67](https://linux-hardware.org/?probe=4e54f20c67) | Aug 10, 2022 |
| Samsung       | 600B4B/600B5B               | Notebook    | [889eb9531f](https://linux-hardware.org/?probe=889eb9531f) | Aug 10, 2022 |
| MSI           | MS-AE611 100                | All in one  | [94bcb206d3](https://linux-hardware.org/?probe=94bcb206d3) | Aug 10, 2022 |
| Lenovo        | IdeaPad C340-14IWL 81N4     | Convertible | [af03bf80b5](https://linux-hardware.org/?probe=af03bf80b5) | Aug 10, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [48722889b6](https://linux-hardware.org/?probe=48722889b6) | Aug 10, 2022 |
| HP            | Pro x2 612 G1 Tablet        | Notebook    | [a40ad10b4c](https://linux-hardware.org/?probe=a40ad10b4c) | Aug 10, 2022 |
| Lenovo        | IdeaPad 110-14IBR 80UJ      | Notebook    | [2f4a79e056](https://linux-hardware.org/?probe=2f4a79e056) | Aug 10, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [9071c341a9](https://linux-hardware.org/?probe=9071c341a9) | Aug 10, 2022 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [bee60f5725](https://linux-hardware.org/?probe=bee60f5725) | Aug 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [4312639df6](https://linux-hardware.org/?probe=4312639df6) | Aug 09, 2022 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [4c372a442f](https://linux-hardware.org/?probe=4c372a442f) | Aug 09, 2022 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [d1215796fb](https://linux-hardware.org/?probe=d1215796fb) | Aug 08, 2022 |
| HP            | 1589                        | Desktop     | [0519e046d2](https://linux-hardware.org/?probe=0519e046d2) | Aug 08, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [5e3e45b5d5](https://linux-hardware.org/?probe=5e3e45b5d5) | Aug 08, 2022 |
| Lenovo        | IdeaPadFlex 15D 20334       | Notebook    | [69430d4693](https://linux-hardware.org/?probe=69430d4693) | Aug 08, 2022 |
| HP            | 18E7                        | Desktop     | [7dd119f85e](https://linux-hardware.org/?probe=7dd119f85e) | Aug 08, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [404319dfd4](https://linux-hardware.org/?probe=404319dfd4) | Aug 07, 2022 |
| MSI           | Z97 GAMING 5                | Desktop     | [7f1e38b57b](https://linux-hardware.org/?probe=7f1e38b57b) | Aug 07, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | Desktop     | [ab0da3a7ec](https://linux-hardware.org/?probe=ab0da3a7ec) | Aug 07, 2022 |
| ASUSTek       | P9X79 LE                    | Desktop     | [f8a36826db](https://linux-hardware.org/?probe=f8a36826db) | Aug 07, 2022 |
| ASUSTek       | ET2701I-W8                  | Desktop     | [5f9c4b50db](https://linux-hardware.org/?probe=5f9c4b50db) | Aug 07, 2022 |
| ASUSTek       | X550JK                      | Notebook    | [a90c14a429](https://linux-hardware.org/?probe=a90c14a429) | Aug 07, 2022 |
| AMI           | Unknown                     | Notebook    | [d40dbd9414](https://linux-hardware.org/?probe=d40dbd9414) | Aug 07, 2022 |
| MSI           | CR620                       | Notebook    | [517b816cd7](https://linux-hardware.org/?probe=517b816cd7) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d19309cb56](https://linux-hardware.org/?probe=d19309cb56) | Aug 06, 2022 |
| MP            | MS-7848                     | Desktop     | [8d4402905d](https://linux-hardware.org/?probe=8d4402905d) | Aug 06, 2022 |
| Lenovo        | ThinkCentre M57 6087YD2     | Desktop     | [9ad2c07771](https://linux-hardware.org/?probe=9ad2c07771) | Aug 06, 2022 |
| Pegatron      | Benicia                     | Desktop     | [d67d37efce](https://linux-hardware.org/?probe=d67d37efce) | Aug 05, 2022 |
| HP            | 339A                        | Desktop     | [53a3b6e834](https://linux-hardware.org/?probe=53a3b6e834) | Aug 05, 2022 |
| HP            | 339A                        | Desktop     | [8883c2cb6c](https://linux-hardware.org/?probe=8883c2cb6c) | Aug 05, 2022 |
| Ematic        | EWT118                      | Notebook    | [a5362d970a](https://linux-hardware.org/?probe=a5362d970a) | Aug 05, 2022 |
| Medion        | E7419 MD60990               | Notebook    | [e1b74852bd](https://linux-hardware.org/?probe=e1b74852bd) | Aug 04, 2022 |
| ASUSTek       | PN51-E1                     | Mini pc     | [d345f9ab52](https://linux-hardware.org/?probe=d345f9ab52) | Aug 04, 2022 |
| Acer          | Peppy                       | Notebook    | [cc1c91fca6](https://linux-hardware.org/?probe=cc1c91fca6) | Aug 04, 2022 |
| Microsoft     | Surface Pro                 | Tablet      | [db66e72de8](https://linux-hardware.org/?probe=db66e72de8) | Aug 04, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [a6f7e6086b](https://linux-hardware.org/?probe=a6f7e6086b) | Aug 03, 2022 |
| LORD ELECT... | GM965 Series                | Desktop     | [b60dce21e7](https://linux-hardware.org/?probe=b60dce21e7) | Aug 03, 2022 |
| Lenovo        | SDK0J40700 WIN              | Desktop     | [299ac7a8ff](https://linux-hardware.org/?probe=299ac7a8ff) | Aug 03, 2022 |
| HP            | 1589                        | Desktop     | [738de77596](https://linux-hardware.org/?probe=738de77596) | Aug 03, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [d1ca5eafe5](https://linux-hardware.org/?probe=d1ca5eafe5) | Aug 03, 2022 |
| Toshiba       | Satellite Pro L670          | Notebook    | [302749341d](https://linux-hardware.org/?probe=302749341d) | Aug 03, 2022 |
| HP            | Notebook                    | Notebook    | [661237e74a](https://linux-hardware.org/?probe=661237e74a) | Aug 03, 2022 |
| MSI           | Boston                      | Desktop     | [32021cecf7](https://linux-hardware.org/?probe=32021cecf7) | Aug 03, 2022 |
| Acer          | Spin SP513-55N              | Convertible | [295df2a1d7](https://linux-hardware.org/?probe=295df2a1d7) | Aug 03, 2022 |
| Dell          | G15 5510                    | Notebook    | [f3406b36e3](https://linux-hardware.org/?probe=f3406b36e3) | Aug 02, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Zorin_16/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.11.0-38-generic      | 176       | 6.63%   |
| 5.11.0-27-generic      | 154       | 5.8%    |
| 5.15.0-46-generic      | 151       | 5.69%   |
| 5.15.0-56-generic      | 150       | 5.65%   |
| 5.15.0-52-generic      | 142       | 5.35%   |
| 5.11.0-40-generic      | 124       | 4.67%   |
| 5.13.0-30-generic      | 123       | 4.63%   |
| 5.13.0-39-generic      | 120       | 4.52%   |
| 5.11.0-41-generic      | 107       | 4.03%   |
| 5.11.0-37-generic      | 107       | 4.03%   |
| 5.11.0-43-generic      | 101       | 3.8%    |
| 5.15.0-48-generic      | 94        | 3.54%   |
| 5.11.0-34-generic      | 94        | 3.54%   |
| 5.13.0-40-generic      | 89        | 3.35%   |
| 5.15.0-53-generic      | 77        | 2.9%    |
| 5.13.0-44-generic      | 76        | 2.86%   |
| 5.15.0-41-generic      | 74        | 2.79%   |
| 5.13.0-35-generic      | 74        | 2.79%   |
| 5.13.0-28-generic      | 71        | 2.67%   |
| 5.13.0-52-generic      | 59        | 2.22%   |
| 5.13.0-27-generic      | 59        | 2.22%   |
| 5.13.0-41-generic      | 54        | 2.03%   |
| 5.13.0-51-generic      | 41        | 1.54%   |
| 5.15.0-43-generic      | 40        | 1.51%   |
| 5.11.0-36-generic      | 39        | 1.47%   |
| 5.11.0-46-generic      | 35        | 1.32%   |
| 5.11.0-44-generic      | 34        | 1.28%   |
| 5.13.0-37-generic      | 29        | 1.09%   |
| 5.13.0-48-generic      | 22        | 0.83%   |
| 5.15.0-50-generic      | 19        | 0.72%   |
| 5.11.0-25-generic      | 16        | 0.6%    |
| 5.8.0-53-generic       | 13        | 0.49%   |
| 5.8.0-50-generic       | 12        | 0.45%   |
| 5.8.0-59-generic       | 9         | 0.34%   |
| 5.8.0-55-generic       | 9         | 0.34%   |
| 5.8.0-49-generic       | 5         | 0.19%   |
| 5.8.0-63-generic       | 4         | 0.15%   |
| 5.13.0-25-generic      | 3         | 0.11%   |
| 5.19.12-051912-generic | 2         | 0.08%   |
| 5.14.0-1052-oem        | 2         | 0.08%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11.0  | 944       | 37.87%  |
| 5.13.0  | 761       | 30.53%  |
| 5.15.0  | 697       | 27.96%  |
| 5.8.0   | 52        | 2.09%   |
| 5.14.0  | 8         | 0.32%   |
| 5.4.0   | 2         | 0.08%   |
| 5.19.12 | 2         | 0.08%   |
| 5.17.5  | 2         | 0.08%   |
| 5.17.1  | 2         | 0.08%   |
| 5.16.0  | 2         | 0.08%   |
| 5.10.0  | 2         | 0.08%   |
| 6.0.8   | 1         | 0.04%   |
| 6.0.0   | 1         | 0.04%   |
| 5.4.180 | 1         | 0.04%   |
| 5.19.9  | 1         | 0.04%   |
| 5.19.6  | 1         | 0.04%   |
| 5.19.2  | 1         | 0.04%   |
| 5.19.14 | 1         | 0.04%   |
| 5.19.1  | 1         | 0.04%   |
| 5.19.0  | 1         | 0.04%   |
| 5.18.6  | 1         | 0.04%   |
| 5.18.15 | 1         | 0.04%   |
| 5.17.9  | 1         | 0.04%   |
| 5.16.5  | 1         | 0.04%   |
| 5.16.14 | 1         | 0.04%   |
| 5.16.12 | 1         | 0.04%   |
| 5.15.49 | 1         | 0.04%   |
| 5.15.24 | 1         | 0.04%   |
| 5.15.13 | 1         | 0.04%   |
| 5.13.18 | 1         | 0.04%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.11    | 944       | 37.87%  |
| 5.13    | 762       | 30.57%  |
| 5.15    | 700       | 28.08%  |
| 5.8     | 52        | 2.09%   |
| 5.19    | 8         | 0.32%   |
| 5.14    | 8         | 0.32%   |
| 5.17    | 5         | 0.2%    |
| 5.16    | 5         | 0.2%    |
| 5.4     | 3         | 0.12%   |
| 6.0     | 2         | 0.08%   |
| 5.18    | 2         | 0.08%   |
| 5.10    | 2         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 2374      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| GNOME      | 2099      | 87.86%  |
| XFCE       | 261       | 10.93%  |
| Unknown    | 16        | 0.67%   |
| X-Cinnamon | 3         | 0.13%   |
| Cinnamon   | 2         | 0.08%   |
| Budgie     | 2         | 0.08%   |
| Unity      | 1         | 0.04%   |
| MATE       | 1         | 0.04%   |
| LXDE       | 1         | 0.04%   |
| KDE5       | 1         | 0.04%   |
| KDE        | 1         | 0.04%   |
| i3         | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2342      | 98.11%  |
| Wayland | 38        | 1.59%   |
| Unknown | 6         | 0.25%   |
| Tty     | 1         | 0.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1878      | 78.18%  |
| GDM     | 244       | 10.16%  |
| GDM3    | 221       | 9.2%    |
| LightDM | 55        | 2.29%   |
| SDDM    | 2         | 0.08%   |
| TDM     | 1         | 0.04%   |
| LXDM    | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 940       | 39.43%  |
| de_DE | 226       | 9.48%   |
| en_GB | 175       | 7.34%   |
| pt_BR | 144       | 6.04%   |
| fr_FR | 78        | 3.27%   |
| it_IT | 70        | 2.94%   |
| es_ES | 67        | 2.81%   |
| en_IN | 64        | 2.68%   |
| en_CA | 62        | 2.6%    |
| pl_PL | 56        | 2.35%   |
| en_AU | 53        | 2.22%   |
| nl_NL | 43        | 1.8%    |
| ru_RU | 37        | 1.55%   |
| es_MX | 36        | 1.51%   |
| en_ZA | 23        | 0.96%   |
| cs_CZ | 21        | 0.88%   |
| pt_PT | 19        | 0.8%    |
| es_AR | 16        | 0.67%   |
| tr_TR | 14        | 0.59%   |
| sv_SE | 13        | 0.55%   |
| nl_BE | 13        | 0.55%   |
| hu_HU | 13        | 0.55%   |
| fr_BE | 13        | 0.55%   |
| en_NZ | 13        | 0.55%   |
| es_CL | 12        | 0.5%    |
| fr_CA | 9         | 0.38%   |
| nb_NO | 8         | 0.34%   |
| ja_JP | 8         | 0.34%   |
| es_CO | 8         | 0.34%   |
| el_GR | 8         | 0.34%   |
| de_AT | 8         | 0.34%   |
| fi_FI | 6         | 0.25%   |
| en_PH | 6         | 0.25%   |
| de_CH | 6         | 0.25%   |
| sk_SK | 5         | 0.21%   |
| es_VE | 5         | 0.21%   |
| es_CR | 5         | 0.21%   |
| en_IL | 5         | 0.21%   |
| da_DK | 5         | 0.21%   |
| ar_EG | 5         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1340      | 55.86%  |
| BIOS | 1059      | 44.14%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 2254      | 94.67%  |
| Zfs      | 47        | 1.97%   |
| Overlay  | 38        | 1.6%    |
| Btrfs    | 25        | 1.05%   |
| Xfs      | 6         | 0.25%   |
| Ext3     | 5         | 0.21%   |
| Ext2     | 5         | 0.21%   |
| Reiserfs | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2055      | 85.91%  |
| GPT     | 267       | 11.16%  |
| MBR     | 70        | 2.93%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2322      | 97.6%   |
| Yes       | 57        | 2.4%    |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2138      | 89.76%  |
| Yes       | 244       | 10.24%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 391       | 16.47%  |
| ASUSTek Computer    | 373       | 15.71%  |
| Dell                | 321       | 13.52%  |
| Lenovo              | 284       | 11.96%  |
| Gigabyte Technology | 145       | 6.11%   |
| MSI                 | 117       | 4.93%   |
| Acer                | 116       | 4.89%   |
| Apple               | 75        | 3.16%   |
| ASRock              | 69        | 2.91%   |
| Toshiba             | 61        | 2.57%   |
| Intel               | 41        | 1.73%   |
| Samsung Electronics | 29        | 1.22%   |
| Unknown             | 22        | 0.93%   |
| Sony                | 19        | 0.8%    |
| Fujitsu             | 18        | 0.76%   |
| Packard Bell        | 15        | 0.63%   |
| Biostar             | 15        | 0.63%   |
| Microsoft           | 14        | 0.59%   |
| Google              | 14        | 0.59%   |
| HUAWEI              | 12        | 0.51%   |
| Foxconn             | 11        | 0.46%   |
| Positivo            | 9         | 0.38%   |
| Alienware           | 9         | 0.38%   |
| Pegatron            | 8         | 0.34%   |
| Chuwi               | 8         | 0.34%   |
| Notebook            | 7         | 0.29%   |
| Medion              | 7         | 0.29%   |
| Gateway             | 6         | 0.25%   |
| AMI                 | 6         | 0.25%   |
| GPU Company         | 5         | 0.21%   |
| Fujitsu Siemens     | 5         | 0.21%   |
| BESSTAR Tech        | 5         | 0.21%   |
| Razer               | 4         | 0.17%   |
| OEM                 | 4         | 0.17%   |
| LG Electronics      | 4         | 0.17%   |
| Jumper              | 4         | 0.17%   |
| AZW                 | 4         | 0.17%   |
| Thomson             | 3         | 0.13%   |
| RCA                 | 3         | 0.13%   |
| Multilaser          | 3         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 30        | 1.26%   |
| ASUS All Series                  | 22        | 0.93%   |
| HP Notebook                      | 15        | 0.63%   |
| HP Pavilion Notebook             | 12        | 0.51%   |
| Dell OptiPlex 7010               | 8         | 0.34%   |
| HP 15                            | 7         | 0.29%   |
| Dell OptiPlex 790                | 7         | 0.29%   |
| Apple MacBookPro8,1              | 7         | 0.29%   |
| Dell OptiPlex 780                | 6         | 0.25%   |
| Dell Latitude E6540              | 6         | 0.25%   |
| Apple iMac12,2                   | 6         | 0.25%   |
| MSI MS-7C02                      | 5         | 0.21%   |
| MSI MS-7817                      | 5         | 0.21%   |
| HP ProBook 640 G1                | 5         | 0.21%   |
| HP Pavilion dv7                  | 5         | 0.21%   |
| HP Pavilion 15                   | 5         | 0.21%   |
| Dell OptiPlex 990                | 5         | 0.21%   |
| Dell OptiPlex 380                | 5         | 0.21%   |
| Dell OptiPlex 3010               | 5         | 0.21%   |
| ASUS M5A78L-M/USB3               | 5         | 0.21%   |
| Toshiba Satellite C660           | 4         | 0.17%   |
| Toshiba Satellite C55-C          | 4         | 0.17%   |
| Microsoft Surface Pro 4          | 4         | 0.17%   |
| Microsoft Surface Pro            | 4         | 0.17%   |
| HP ProDesk 600 G1 SFF            | 4         | 0.17%   |
| HP Pavilion g6                   | 4         | 0.17%   |
| HP Laptop 15-bw0xx               | 4         | 0.17%   |
| HP Compaq Pro 6300 SFF           | 4         | 0.17%   |
| GPU Company GWTC116-2            | 4         | 0.17%   |
| Gigabyte X570 AORUS ELITE        | 4         | 0.17%   |
| Gigabyte B450 AORUS M            | 4         | 0.17%   |
| Gigabyte A320M-S2H               | 4         | 0.17%   |
| Dell Studio 1558                 | 4         | 0.17%   |
| Dell Precision WorkStation T3500 | 4         | 0.17%   |
| Dell Latitude E7440              | 4         | 0.17%   |
| Dell Latitude E5500              | 4         | 0.17%   |
| Dell Inspiron 3542               | 4         | 0.17%   |
| Dell Inspiron 3521               | 4         | 0.17%   |
| Dell Inspiron 15-3567            | 4         | 0.17%   |
| Chuwi HeroBook Air               | 4         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Dell Inspiron         | 93        | 3.92%   |
| Lenovo ThinkPad       | 84        | 3.54%   |
| Dell Latitude         | 83        | 3.5%    |
| Acer Aspire           | 80        | 3.37%   |
| HP Pavilion           | 79        | 3.33%   |
| Lenovo IdeaPad        | 73        | 3.07%   |
| Dell OptiPlex         | 59        | 2.49%   |
| Toshiba Satellite     | 49        | 2.06%   |
| HP EliteBook          | 38        | 1.6%    |
| HP ProBook            | 34        | 1.43%   |
| HP Compaq             | 34        | 1.43%   |
| ASUS ROG              | 34        | 1.43%   |
| ASUS PRIME            | 33        | 1.39%   |
| Unknown               | 30        | 1.26%   |
| ASUS VivoBook         | 28        | 1.18%   |
| Lenovo ThinkCentre    | 27        | 1.14%   |
| HP Laptop             | 27        | 1.14%   |
| HP ENVY               | 23        | 0.97%   |
| Dell XPS              | 23        | 0.97%   |
| ASUS TUF              | 22        | 0.93%   |
| ASUS All              | 22        | 0.93%   |
| Lenovo Yoga           | 18        | 0.76%   |
| Dell Vostro           | 18        | 0.76%   |
| Dell Precision        | 18        | 0.76%   |
| HP Notebook           | 15        | 0.63%   |
| Microsoft Surface     | 14        | 0.59%   |
| Packard Bell EasyNote | 12        | 0.51%   |
| HP Stream             | 12        | 0.51%   |
| HP OMEN               | 11        | 0.46%   |
| HP EliteDesk          | 11        | 0.46%   |
| Dell Studio           | 11        | 0.46%   |
| Apple iMac12          | 10        | 0.42%   |
| HP ProDesk            | 9         | 0.38%   |
| HP 15                 | 9         | 0.38%   |
| Gigabyte B450         | 9         | 0.38%   |
| Fujitsu ESPRIMO       | 9         | 0.38%   |
| ASUS ZenBook          | 9         | 0.38%   |
| ASUS ASUS             | 9         | 0.38%   |
| Apple MacBookPro8     | 9         | 0.38%   |
| Gigabyte X570         | 8         | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 214       | 9.01%   |
| 2021    | 211       | 8.89%   |
| 2012    | 211       | 8.89%   |
| 2013    | 206       | 8.68%   |
| 2019    | 185       | 7.79%   |
| 2018    | 184       | 7.75%   |
| 2020    | 182       | 7.67%   |
| 2014    | 166       | 6.99%   |
| 2010    | 144       | 6.07%   |
| 2017    | 134       | 5.64%   |
| 2016    | 129       | 5.43%   |
| 2015    | 113       | 4.76%   |
| 2008    | 107       | 4.51%   |
| 2009    | 82        | 3.45%   |
| 2007    | 57        | 2.4%    |
| 2022    | 27        | 1.14%   |
| 2006    | 16        | 0.67%   |
| 2005    | 4         | 0.17%   |
| Unknown | 2         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 1300      | 54.76%  |
| Desktop     | 879       | 37.03%  |
| Convertible | 57        | 2.4%    |
| All in one  | 57        | 2.4%    |
| Mini pc     | 39        | 1.64%   |
| Tablet      | 37        | 1.56%   |
| Server      | 5         | 0.21%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2106      | 87.9%   |
| Enabled  | 290       | 12.1%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2357      | 99.28%  |
| Yes  | 17        | 0.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 628       | 26.32%  |
| 3.01-4.0    | 538       | 22.55%  |
| 8.01-16.0   | 430       | 18.02%  |
| 16.01-24.0  | 397       | 16.64%  |
| 32.01-64.0  | 186       | 7.8%    |
| 1.01-2.0    | 114       | 4.78%   |
| 64.01-256.0 | 41        | 1.72%   |
| 2.01-3.0    | 28        | 1.17%   |
| 24.01-32.0  | 21        | 0.88%   |
| 0.51-1.0    | 3         | 0.13%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1013      | 39.76%  |
| 2.01-3.0   | 826       | 32.42%  |
| 3.01-4.0   | 339       | 13.3%   |
| 4.01-8.0   | 275       | 10.79%  |
| 8.01-16.0  | 43        | 1.69%   |
| 0.51-1.0   | 40        | 1.57%   |
| 16.01-24.0 | 7         | 0.27%   |
| 24.01-32.0 | 3         | 0.12%   |
| 32.01-64.0 | 1         | 0.04%   |
| 0.01-0.5   | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1513      | 62.55%  |
| 2      | 596       | 24.64%  |
| 3      | 148       | 6.12%   |
| 4      | 69        | 2.85%   |
| 5      | 37        | 1.53%   |
| 6      | 24        | 0.99%   |
| 0      | 13        | 0.54%   |
| 8      | 8         | 0.33%   |
| 7      | 8         | 0.33%   |
| 51     | 1         | 0.04%   |
| 30     | 1         | 0.04%   |
| 11     | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1324      | 55.56%  |
| Yes       | 1059      | 44.44%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2002      | 84.15%  |
| No        | 377       | 15.85%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1868      | 78.49%  |
| No        | 512       | 21.51%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1389      | 58.02%  |
| No        | 1005      | 41.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 566       | 23.76%  |
| Germany      | 244       | 10.24%  |
| Brazil       | 158       | 6.63%   |
| UK           | 157       | 6.59%   |
| Canada       | 81        | 3.4%    |
| Spain        | 80        | 3.36%   |
| Italy        | 77        | 3.23%   |
| France       | 71        | 2.98%   |
| India        | 66        | 2.77%   |
| Netherlands  | 64        | 2.69%   |
| Australia    | 54        | 2.27%   |
| Poland       | 53        | 2.23%   |
| Mexico       | 47        | 1.97%   |
| Russia       | 35        | 1.47%   |
| Belgium      | 34        | 1.43%   |
| South Africa | 27        | 1.13%   |
| Sweden       | 25        | 1.05%   |
| Portugal     | 23        | 0.97%   |
| Czechia      | 22        | 0.92%   |
| Austria      | 22        | 0.92%   |
| Greece       | 21        | 0.88%   |
| Argentina    | 21        | 0.88%   |
| Turkey       | 20        | 0.84%   |
| Norway       | 20        | 0.84%   |
| Romania      | 19        | 0.8%    |
| Hungary      | 19        | 0.8%    |
| Switzerland  | 17        | 0.71%   |
| Japan        | 16        | 0.67%   |
| Chile        | 15        | 0.63%   |
| New Zealand  | 14        | 0.59%   |
| Egypt        | 14        | 0.59%   |
| Denmark      | 14        | 0.59%   |
| Indonesia    | 12        | 0.5%    |
| Finland      | 11        | 0.46%   |
| Colombia     | 11        | 0.46%   |
| Slovenia     | 9         | 0.38%   |
| Serbia       | 9         | 0.38%   |
| Malaysia     | 9         | 0.38%   |
| Bulgaria     | 9         | 0.38%   |
| Slovakia     | 8         | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Berlin            | 22        | 0.9%    |
| Munich            | 19        | 0.77%   |
| Athens            | 19        | 0.77%   |
| Madrid            | 15        | 0.61%   |
| Sydney            | 14        | 0.57%   |
| Sao Paulo         | 12        | 0.49%   |
| New York          | 12        | 0.49%   |
| Dallas            | 12        | 0.49%   |
| Vienna            | 11        | 0.45%   |
| Rome              | 11        | 0.45%   |
| Rio de Janeiro    | 11        | 0.45%   |
| Hamburg           | 11        | 0.45%   |
| Montreal          | 10        | 0.41%   |
| Salt Lake City    | 9         | 0.37%   |
| London            | 9         | 0.37%   |
| Phoenix           | 8         | 0.33%   |
| Paris             | 8         | 0.33%   |
| Moscow            | 8         | 0.33%   |
| Milan             | 8         | 0.33%   |
| Mexico City       | 8         | 0.33%   |
| Johannesburg      | 8         | 0.33%   |
| Glasgow           | 8         | 0.33%   |
| Frankfurt am Main | 8         | 0.33%   |
| Brisbane          | 8         | 0.33%   |
| Bengaluru         | 8         | 0.33%   |
| Auckland          | 8         | 0.33%   |
| Amsterdam         | 8         | 0.33%   |
| Valencia          | 7         | 0.29%   |
| Seattle           | 7         | 0.29%   |
| Perth             | 7         | 0.29%   |
| Jakarta           | 7         | 0.29%   |
| Istanbul          | 7         | 0.29%   |
| Cairo             | 7         | 0.29%   |
| Buenos Aires      | 7         | 0.29%   |
| Adelaide          | 7         | 0.29%   |
| Toronto           | 6         | 0.24%   |
| Stuttgart         | 6         | 0.24%   |
| Richmond          | 6         | 0.24%   |
| Prague            | 6         | 0.24%   |
| Portland          | 6         | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 537       | 760    | 15.96%  |
| Samsung Electronics       | 451       | 647    | 13.41%  |
| WDC                       | 443       | 590    | 13.17%  |
| Toshiba                   | 252       | 324    | 7.49%   |
| SanDisk                   | 202       | 230    | 6%      |
| Unknown                   | 186       | 258    | 5.53%   |
| Kingston                  | 186       | 245    | 5.53%   |
| Crucial                   | 126       | 154    | 3.75%   |
| Hitachi                   | 111       | 146    | 3.3%    |
| Intel                     | 68        | 89     | 2.02%   |
| SK hynix                  | 63        | 74     | 1.87%   |
| HGST                      | 52        | 66     | 1.55%   |
| A-DATA Technology         | 51        | 59     | 1.52%   |
| Micron Technology         | 41        | 48     | 1.22%   |
| China                     | 35        | 41     | 1.04%   |
| Phison                    | 29        | 33     | 0.86%   |
| Apple                     | 29        | 32     | 0.86%   |
| Intenso                   | 26        | 28     | 0.77%   |
| Silicon Motion            | 23        | 30     | 0.68%   |
| PNY                       | 22        | 29     | 0.65%   |
| SPCC                      | 19        | 22     | 0.56%   |
| Netac                     | 19        | 21     | 0.56%   |
| Patriot                   | 18        | 22     | 0.54%   |
| KIOXIA                    | 16        | 16     | 0.48%   |
| OCZ                       | 15        | 18     | 0.45%   |
| JMicron Technology        | 14        | 17     | 0.42%   |
| Unknown                   | 14        | 16     | 0.42%   |
| LITEON                    | 13        | 15     | 0.39%   |
| Lexar                     | 13        | 13     | 0.39%   |
| GOODRAM                   | 13        | 14     | 0.39%   |
| Transcend                 | 11        | 28     | 0.33%   |
| Team                      | 10        | 13     | 0.3%    |
| KingSpec                  | 10        | 12     | 0.3%    |
| Hewlett-Packard           | 10        | 14     | 0.3%    |
| SABRENT                   | 9         | 10     | 0.27%   |
| Micron/Crucial Technology | 9         | 9      | 0.27%   |
| LITEONIT                  | 9         | 10     | 0.27%   |
| Gigabyte Technology       | 9         | 11     | 0.27%   |
| Maxtor                    | 8         | 10     | 0.24%   |
| XPG                       | 7         | 8      | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Unknown MMC Card  32GB                              | 60        | 1.61%   |
| Unknown MMC Card  64GB                              | 52        | 1.39%   |
| Kingston SA400S37240G 240GB SSD                     | 43        | 1.15%   |
| Seagate ST500DM002-1BD142 500GB                     | 37        | 0.99%   |
| Seagate ST1000LM035-1RK172 1TB                      | 30        | 0.8%    |
| Crucial CT240BX500SSD1 240GB                        | 29        | 0.78%   |
| Samsung SSD 860 EVO 500GB                           | 28        | 0.75%   |
| Kingston SA400S37480G 480GB SSD                     | 28        | 0.75%   |
| Toshiba MQ01ABD100 1TB                              | 26        | 0.7%    |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 26        | 0.7%    |
| Unknown MMC Card  128GB                             | 25        | 0.67%   |
| Samsung NVMe SSD Drive 512GB                        | 25        | 0.67%   |
| Samsung NVMe SSD Drive 1TB                          | 25        | 0.67%   |
| Toshiba MQ01ABF050 500GB                            | 24        | 0.64%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 24        | 0.64%   |
| Seagate ST1000DM010-2EP102 1TB                      | 23        | 0.62%   |
| Kingston SA400S37120G 120GB SSD                     | 23        | 0.62%   |
| Unknown SD/MMC/MS PRO 64GB                          | 22        | 0.59%   |
| SanDisk NVMe SSD Drive 256GB                        | 21        | 0.56%   |
| Samsung NVMe SSD Drive 500GB                        | 21        | 0.56%   |
| Toshiba MQ04ABF100 1TB                              | 19        | 0.51%   |
| Seagate ST500LT012-1DG142 500GB                     | 19        | 0.51%   |
| Samsung SSD 850 EVO 250GB                           | 19        | 0.51%   |
| Samsung SSD 850 EVO 500GB                           | 18        | 0.48%   |
| Seagate Expansion 4TB                               | 17        | 0.46%   |
| Crucial CT500MX500SSD1 500GB                        | 17        | 0.46%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 16        | 0.43%   |
| SanDisk NVMe SSD Drive 512GB                        | 15        | 0.4%    |
| SanDisk NVMe SSD Drive 1TB                          | 15        | 0.4%    |
| Samsung SSD 870 EVO 1TB                             | 15        | 0.4%    |
| Samsung SSD 840 EVO 250GB                           | 15        | 0.4%    |
| Kingston SV300S37A120G 120GB SSD                    | 15        | 0.4%    |
| Toshiba HDWD110 1TB                                 | 14        | 0.38%   |
| Seagate ST9500325AS 500GB                           | 14        | 0.38%   |
| Seagate ST3500418AS 500GB                           | 14        | 0.38%   |
| Intel NVMe SSD Drive 512GB                          | 14        | 0.38%   |
| Unknown                                             | 14        | 0.38%   |
| Seagate ST2000DM008-2FR102 2TB                      | 13        | 0.35%   |
| Samsung SSD 860 EVO 250GB                           | 13        | 0.35%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 13        | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 532       | 743    | 38%     |
| WDC                 | 386       | 505    | 27.57%  |
| Toshiba             | 197       | 261    | 14.07%  |
| Hitachi             | 111       | 146    | 7.93%   |
| Samsung Electronics | 54        | 69     | 3.86%   |
| HGST                | 52        | 66     | 3.71%   |
| Unknown             | 22        | 26     | 1.57%   |
| Apple               | 15        | 17     | 1.07%   |
| Maxtor              | 8         | 10     | 0.57%   |
| Fujitsu             | 7         | 8      | 0.5%    |
| ASMT                | 4         | 4      | 0.29%   |
| USB3.0              | 3         | 4      | 0.21%   |
| Hewlett-Packard     | 3         | 6      | 0.21%   |
| JMicron Technology  | 2         | 2      | 0.14%   |
| Intenso             | 2         | 2      | 0.14%   |
| SABRENT             | 1         | 1      | 0.07%   |
| KESU                | 1         | 1      | 0.07%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 240       | 329    | 20.44%  |
| Kingston            | 154       | 196    | 13.12%  |
| Crucial             | 121       | 147    | 10.31%  |
| SanDisk             | 120       | 141    | 10.22%  |
| WDC                 | 49        | 61     | 4.17%   |
| A-DATA Technology   | 46        | 54     | 3.92%   |
| China               | 33        | 39     | 2.81%   |
| Toshiba             | 29        | 33     | 2.47%   |
| Intel               | 26        | 31     | 2.21%   |
| PNY                 | 22        | 29     | 1.87%   |
| SK hynix            | 20        | 20     | 1.7%    |
| Micron Technology   | 20        | 23     | 1.7%    |
| Netac               | 19        | 20     | 1.62%   |
| SPCC                | 18        | 21     | 1.53%   |
| Patriot             | 17        | 21     | 1.45%   |
| Intenso             | 16        | 17     | 1.36%   |
| OCZ                 | 14        | 17     | 1.19%   |
| LITEON              | 13        | 15     | 1.11%   |
| Lexar               | 12        | 12     | 1.02%   |
| GOODRAM             | 12        | 13     | 1.02%   |
| Apple               | 12        | 12     | 1.02%   |
| Transcend           | 11        | 28     | 0.94%   |
| Team                | 10        | 13     | 0.85%   |
| LITEONIT            | 9         | 10     | 0.77%   |
| KingSpec            | 9         | 11     | 0.77%   |
| JMicron Technology  | 7         | 9      | 0.6%    |
| Hewlett-Packard     | 7         | 8      | 0.6%    |
| Gigabyte Technology | 7         | 8      | 0.6%    |
| Unknown             | 7         | 9      | 0.6%    |
| Leven               | 6         | 7      | 0.51%   |
| Apacer              | 6         | 7      | 0.51%   |
| Super Talent        | 4         | 5      | 0.34%   |
| FORESEE             | 4         | 4      | 0.34%   |
| Seagate             | 3         | 5      | 0.26%   |
| Plextor             | 3         | 4      | 0.26%   |
| OWC                 | 3         | 3      | 0.26%   |
| Mushkin             | 3         | 3      | 0.26%   |
| KIOXIA-EXCERIA      | 3         | 6      | 0.26%   |
| BHT                 | 3         | 4      | 0.26%   |
| Verbatim            | 2         | 2      | 0.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1198      | 1871   | 39.24%  |
| SSD     | 1050      | 1462   | 34.39%  |
| NVMe    | 564       | 748    | 18.47%  |
| MMC     | 171       | 227    | 5.6%    |
| Unknown | 70        | 92     | 2.29%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1893      | 3226   | 68.39%  |
| NVMe | 560       | 738    | 20.23%  |
| MMC  | 171       | 227    | 6.18%   |
| SAS  | 144       | 209    | 5.2%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1418      | 2025   | 61.25%  |
| 0.51-1.0   | 631       | 862    | 27.26%  |
| 1.01-2.0   | 149       | 212    | 6.44%   |
| 3.01-4.0   | 56        | 120    | 2.42%   |
| 4.01-10.0  | 37        | 57     | 1.6%    |
| 2.01-3.0   | 21        | 42     | 0.91%   |
| 10.01-20.0 | 3         | 15     | 0.13%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 777       | 31.82%  |
| 251-500        | 612       | 25.06%  |
| 501-1000       | 370       | 15.15%  |
| 51-100         | 212       | 8.68%   |
| 1001-2000      | 129       | 5.28%   |
| 21-50          | 124       | 5.08%   |
| More than 3000 | 89        | 3.64%   |
| 1-20           | 51        | 2.09%   |
| 2001-3000      | 46        | 1.88%   |
| Unknown        | 32        | 1.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1004      | 39.51%  |
| 21-50          | 700       | 27.55%  |
| 51-100         | 289       | 11.37%  |
| 101-250        | 228       | 8.97%   |
| 251-500        | 128       | 5.04%   |
| 501-1000       | 73        | 2.87%   |
| More than 3000 | 46        | 1.81%   |
| Unknown        | 32        | 1.26%   |
| 1001-2000      | 30        | 1.18%   |
| 2001-3000      | 11        | 0.43%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Toshiba MQ02ABD100H 1TB              | 2         | 2      | 3.17%   |
| Toshiba MQ01ABD100 1TB               | 2         | 2      | 3.17%   |
| Seagate ST9500420AS 500GB            | 2         | 2      | 3.17%   |
| Kingston SUV400S37240G 240GB SSD     | 2         | 2      | 3.17%   |
| WDC WD6400BEVT-22A0RT0 640GB         | 1         | 1      | 1.59%   |
| WDC WD5000LPVX-75V0TT0 500GB         | 1         | 1      | 1.59%   |
| WDC WD3200AAKS-22B3A0 320GB          | 1         | 1      | 1.59%   |
| WDC WD3200AAJS-00L7A0 320GB          | 1         | 1      | 1.59%   |
| WDC WD30EFRX-68EUZN0 3TB             | 1         | 1      | 1.59%   |
| WDC WD10SPZX-75Z10T2 1TB             | 1         | 1      | 1.59%   |
| WDC WD10JPVX-22JC3T0 1TB             | 1         | 1      | 1.59%   |
| WDC WD10JPVT-55A1YT0 1TB             | 1         | 1      | 1.59%   |
| WDC WD10EZEX-21M2NA0 1TB             | 1         | 2      | 1.59%   |
| WDC WD10EURX-63FH1Y0 1TB             | 1         | 1      | 1.59%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD | 1         | 1      | 1.59%   |
| Toshiba MQ01ABF050 500GB             | 1         | 1      | 1.59%   |
| Toshiba MQ01ABD075 752GB             | 1         | 1      | 1.59%   |
| Toshiba MK8046GSX 80GB               | 1         | 1      | 1.59%   |
| Toshiba MK3265GSX 320GB              | 1         | 1      | 1.59%   |
| Toshiba MG03ACA200 2TB               | 1         | 1      | 1.59%   |
| SK hynix BC711 HFM512GD3JX013N 512GB | 1         | 1      | 1.59%   |
| Silicon Motion Inland NVMe SSD 256GB | 1         | 1      | 1.59%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 1.59%   |
| Seagate ST9250315AS 250GB            | 1         | 1      | 1.59%   |
| Seagate ST9200420ASG 200GB           | 1         | 1      | 1.59%   |
| Seagate ST8000DM004-2CX188 8TB       | 1         | 1      | 1.59%   |
| Seagate ST500LT012-9WS142 500GB      | 1         | 1      | 1.59%   |
| Seagate ST500LT012-1DG142 500GB      | 1         | 1      | 1.59%   |
| Seagate ST500LM000-SSHD-8GB          | 1         | 1      | 1.59%   |
| Seagate ST500DM002-1BD142 500GB      | 1         | 1      | 1.59%   |
| Seagate ST4000DM004-2CV104 4TB       | 1         | 1      | 1.59%   |
| Seagate ST3500514NS 500GB            | 1         | 1      | 1.59%   |
| Seagate ST3500413AS 500GB            | 1         | 1      | 1.59%   |
| Seagate ST3320620AS 320GB            | 1         | 1      | 1.59%   |
| Seagate ST3250318AS 250GB            | 1         | 1      | 1.59%   |
| Seagate ST320LT012-1DG14C 320GB      | 1         | 1      | 1.59%   |
| Seagate ST2000LM003 HN-M201RAD 2TB   | 1         | 1      | 1.59%   |
| Seagate ST2000DM008-2FR102 2TB       | 1         | 1      | 1.59%   |
| Seagate ST2000DM001-9YN164 2TB       | 1         | 1      | 1.59%   |
| Seagate ST2000DL003-9VT166 2TB       | 1         | 1      | 1.59%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 22     | 33.87%  |
| WDC                 | 10        | 11     | 16.13%  |
| Toshiba             | 10        | 10     | 16.13%  |
| Kingston            | 4         | 4      | 6.45%   |
| HGST                | 4         | 4      | 6.45%   |
| Samsung Electronics | 3         | 3      | 4.84%   |
| Hitachi             | 2         | 2      | 3.23%   |
| A-DATA Technology   | 2         | 2      | 3.23%   |
| SK hynix            | 1         | 1      | 1.61%   |
| Silicon Motion      | 1         | 1      | 1.61%   |
| OCZ                 | 1         | 1      | 1.61%   |
| LITEONIT            | 1         | 1      | 1.61%   |
| Intel               | 1         | 1      | 1.61%   |
| Hewlett-Packard     | 1         | 1      | 1.61%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 22     | 44.68%  |
| WDC                 | 10        | 11     | 21.28%  |
| Toshiba             | 9         | 9      | 19.15%  |
| HGST                | 4         | 4      | 8.51%   |
| Hitachi             | 2         | 2      | 4.26%   |
| Samsung Electronics | 1         | 1      | 2.13%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 45        | 49     | 75%     |
| SSD  | 12        | 12     | 20%     |
| NVMe | 3         | 3      | 5%      |

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
| Detected | 2112      | 3872   | 86.45%  |
| Works    | 270       | 462    | 11.05%  |
| Malfunc  | 59        | 64     | 2.42%   |
| Failed   | 2         | 2      | 0.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1638      | 58.33%  |
| AMD                              | 461       | 16.42%  |
| Samsung Electronics              | 200       | 7.12%   |
| SanDisk                          | 90        | 3.21%   |
| SK hynix                         | 40        | 1.42%   |
| Phison Electronics               | 40        | 1.42%   |
| ASMedia Technology               | 39        | 1.39%   |
| Kingston Technology Company      | 38        | 1.35%   |
| Nvidia                           | 36        | 1.28%   |
| Toshiba America Info Systems     | 26        | 0.93%   |
| Silicon Motion                   | 25        | 0.89%   |
| JMicron Technology               | 24        | 0.85%   |
| Micron Technology                | 22        | 0.78%   |
| Marvell Technology Group         | 20        | 0.71%   |
| KIOXIA                           | 18        | 0.64%   |
| Micron/Crucial Technology        | 14        | 0.5%    |
| ADATA Technology                 | 14        | 0.5%    |
| Silicon Image                    | 8         | 0.28%   |
| Realtek Semiconductor            | 8         | 0.28%   |
| VIA Technologies                 | 7         | 0.25%   |
| Lite-On Technology               | 6         | 0.21%   |
| Union Memory (Shenzhen)          | 4         | 0.14%   |
| Seagate Technology               | 4         | 0.14%   |
| Solid State Storage Technology   | 3         | 0.11%   |
| Broadcom / LSI                   | 3         | 0.11%   |
| Yangtze Memory Technologies      | 2         | 0.07%   |
| Silicon Integrated Systems [SiS] | 2         | 0.07%   |
| OCZ Technology Group             | 2         | 0.07%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.07%   |
| LSI Logic / Symbios Logic        | 2         | 0.07%   |
| INNOGRIT                         | 2         | 0.07%   |
| Apple                            | 2         | 0.07%   |
| Netac Technology                 | 1         | 0.04%   |
| Lenovo                           | 1         | 0.04%   |
| Dell                             | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |
| Beijing Starblaze Technology     | 1         | 0.04%   |
| Adaptec                          | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 314       | 9.65%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 130       | 3.99%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 121       | 3.72%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 103       | 3.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 93        | 2.86%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 91        | 2.8%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 89        | 2.73%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 70        | 2.15%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 66        | 2.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 59        | 1.81%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 58        | 1.78%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 56        | 1.72%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 54        | 1.66%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 53        | 1.63%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 50        | 1.54%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 50        | 1.54%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 49        | 1.51%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 45        | 1.38%   |
| Intel SATA Controller [RAID mode]                                                       | 45        | 1.38%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 43        | 1.32%   |
| Samsung NVMe SSD Controller 980                                                         | 42        | 1.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 40        | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 40        | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 40        | 1.23%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 37        | 1.14%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 36        | 1.11%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 36        | 1.11%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 34        | 1.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 33        | 1.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 30        | 0.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 30        | 0.92%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 29        | 0.89%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 25        | 0.77%   |
| AMD 500 Series Chipset SATA Controller                                                  | 25        | 0.77%   |
| SanDisk WD Blue SN550 NVMe SSD                                                          | 23        | 0.71%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 23        | 0.71%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 23        | 0.71%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 22        | 0.68%   |
| Micron Non-Volatile memory controller                                                   | 22        | 0.68%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 22        | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1786      | 61.5%   |
| NVMe | 562       | 19.35%  |
| IDE  | 339       | 11.67%  |
| RAID | 210       | 7.23%   |
| SAS  | 4         | 0.14%   |
| SCSI | 3         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1848      | 77.84%  |
| AMD    | 526       | 22.16%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 35        | 1.47%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 27        | 1.14%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 21        | 0.88%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 20        | 0.84%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 19        | 0.8%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 19        | 0.8%    |
| AMD Ryzen 5 3600 6-Core Processor             | 18        | 0.76%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 18        | 0.76%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 16        | 0.67%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 16        | 0.67%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 15        | 0.63%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 15        | 0.63%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 14        | 0.59%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 14        | 0.59%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 14        | 0.59%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 14        | 0.59%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 13        | 0.55%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 13        | 0.55%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 13        | 0.55%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 12        | 0.51%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 12        | 0.51%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 12        | 0.51%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 12        | 0.51%   |
| Intel Core i5-2430M CPU @ 2.40GHz             | 12        | 0.51%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 12        | 0.51%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 12        | 0.51%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 12        | 0.51%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 11        | 0.46%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 11        | 0.46%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 11        | 0.46%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 11        | 0.46%   |
| Intel Core i3 CPU M 380 @ 2.53GHz             | 11        | 0.46%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 0.42%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 10        | 0.42%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 10        | 0.42%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 10        | 0.42%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 10        | 0.42%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 10        | 0.42%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 10        | 0.42%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 10        | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 551       | 23.19%  |
| Intel Core i7           | 342       | 14.39%  |
| Intel Core i3           | 238       | 10.02%  |
| Intel Celeron           | 149       | 6.27%   |
| Intel Core 2 Duo        | 124       | 5.22%   |
| AMD Ryzen 5             | 118       | 4.97%   |
| Other                   | 110       | 4.63%   |
| Intel Pentium           | 79        | 3.32%   |
| AMD Ryzen 7             | 76        | 3.2%    |
| Intel Atom              | 73        | 3.07%   |
| Intel Xeon              | 51        | 2.15%   |
| AMD FX                  | 42        | 1.77%   |
| AMD A6                  | 35        | 1.47%   |
| AMD Ryzen 9             | 31        | 1.3%    |
| Intel Pentium Dual-Core | 30        | 1.26%   |
| Intel Core 2 Quad       | 25        | 1.05%   |
| AMD A10                 | 25        | 1.05%   |
| AMD Ryzen 3             | 23        | 0.97%   |
| AMD A4                  | 22        | 0.93%   |
| Intel Pentium Dual      | 21        | 0.88%   |
| AMD A8                  | 21        | 0.88%   |
| AMD E1                  | 14        | 0.59%   |
| Intel Core 2            | 13        | 0.55%   |
| Intel Core i9           | 11        | 0.46%   |
| AMD Phenom II X4        | 11        | 0.46%   |
| Intel Pentium Silver    | 9         | 0.38%   |
| AMD Athlon II X2        | 9         | 0.38%   |
| Intel Pentium Gold      | 8         | 0.34%   |
| AMD Phenom II X6        | 7         | 0.29%   |
| AMD E                   | 7         | 0.29%   |
| AMD Athlon II X4        | 7         | 0.29%   |
| AMD Athlon 64 X2        | 7         | 0.29%   |
| AMD Athlon              | 7         | 0.29%   |
| Intel Core M            | 6         | 0.25%   |
| AMD Turion 64 X2 Mobile | 5         | 0.21%   |
| Intel Pentium 4         | 4         | 0.17%   |
| Intel Core m5           | 4         | 0.17%   |
| AMD Ryzen 7 PRO         | 4         | 0.17%   |
| AMD E2                  | 4         | 0.17%   |
| AMD Athlon II X3        | 4         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1118      | 47.05%  |
| 4      | 865       | 36.41%  |
| 6      | 178       | 7.49%   |
| 8      | 122       | 5.13%   |
| 1      | 29        | 1.22%   |
| 12     | 23        | 0.97%   |
| 3      | 18        | 0.76%   |
| 16     | 11        | 0.46%   |
| 10     | 9         | 0.38%   |
| 14     | 2         | 0.08%   |
| 40     | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 2364      | 99.58%  |
| 2      | 10        | 0.42%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 1423      | 59.92%  |
| 1      | 952       | 40.08%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2374      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0x206a7    | 197       | 8.18%   |
| 0x306a9    | 194       | 8.06%   |
| Unknown    | 170       | 7.06%   |
| 0x306c3    | 139       | 5.77%   |
| 0x1067a    | 115       | 4.78%   |
| 0x40651    | 74        | 3.07%   |
| 0x20655    | 63        | 2.62%   |
| 0x806c1    | 61        | 2.53%   |
| 0x806e9    | 55        | 2.29%   |
| 0x406c4    | 52        | 2.16%   |
| 0x30678    | 52        | 2.16%   |
| 0x406e3    | 50        | 2.08%   |
| 0x306d4    | 50        | 2.08%   |
| 0x906ea    | 47        | 1.95%   |
| 0x506e3    | 46        | 1.91%   |
| 0x806ea    | 43        | 1.79%   |
| 0x806ec    | 40        | 1.66%   |
| 0x08701021 | 39        | 1.62%   |
| 0x6fd      | 37        | 1.54%   |
| 0x906e9    | 36        | 1.5%    |
| 0x706a8    | 30        | 1.25%   |
| 0x06000852 | 29        | 1.2%    |
| 0x20652    | 28        | 1.16%   |
| 0x10676    | 28        | 1.16%   |
| 0x706e5    | 26        | 1.08%   |
| 0x6fb      | 26        | 1.08%   |
| 0x08108109 | 26        | 1.08%   |
| 0x506c9    | 22        | 0.91%   |
| 0x406c3    | 21        | 0.87%   |
| 0x07030105 | 21        | 0.87%   |
| 0x06001119 | 20        | 0.83%   |
| 0x0a201016 | 18        | 0.75%   |
| 0x0800820d | 18        | 0.75%   |
| 0x0700010f | 18        | 0.75%   |
| 0x08600106 | 17        | 0.71%   |
| 0x06006705 | 17        | 0.71%   |
| 0x010000c8 | 17        | 0.71%   |
| 0xa0653    | 16        | 0.66%   |
| 0xa0652    | 16        | 0.66%   |
| 0x0a50000c | 16        | 0.66%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 280       | 11.79%  |
| Haswell          | 235       | 9.89%   |
| SandyBridge      | 214       | 9.01%   |
| IvyBridge        | 204       | 8.59%   |
| Penryn           | 147       | 6.19%   |
| Silvermont       | 133       | 5.6%    |
| Skylake          | 102       | 4.29%   |
| Westmere         | 99        | 4.17%   |
| Core             | 85        | 3.58%   |
| Zen 2            | 83        | 3.49%   |
| TigerLake        | 70        | 2.95%   |
| Zen+             | 64        | 2.69%   |
| Zen 3            | 61        | 2.57%   |
| Piledriver       | 54        | 2.27%   |
| Broadwell        | 52        | 2.19%   |
| K10              | 49        | 2.06%   |
| CometLake        | 49        | 2.06%   |
| IceLake          | 47        | 1.98%   |
| Goldmont plus    | 44        | 1.85%   |
| Excavator        | 43        | 1.81%   |
| Zen              | 33        | 1.39%   |
| Puma             | 31        | 1.31%   |
| Unknown          | 29        | 1.22%   |
| Nehalem          | 27        | 1.14%   |
| Goldmont         | 25        | 1.05%   |
| Jaguar           | 21        | 0.88%   |
| K8 Hammer        | 17        | 0.72%   |
| K10 Llano        | 12        | 0.51%   |
| Bobcat           | 12        | 0.51%   |
| Steamroller      | 10        | 0.42%   |
| Bulldozer        | 10        | 0.42%   |
| Alderlake Hybrid | 9         | 0.38%   |
| Bonnell          | 8         | 0.34%   |
| NetBurst         | 7         | 0.29%   |
| Tremont          | 5         | 0.21%   |
| K8 & K10 hybrid  | 4         | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1433      | 52.59%  |
| Nvidia                           | 672       | 24.66%  |
| AMD                              | 612       | 22.46%  |
| VIA Technologies                 | 3         | 0.11%   |
| Silicon Integrated Systems [SiS] | 2         | 0.07%   |
| Matrox Electronics Systems       | 2         | 0.07%   |
| ASPEED Technology                | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 167       | 6%      |
| Intel 3rd Gen Core processor Graphics Controller                                         | 118       | 4.24%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 75        | 2.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 74        | 2.66%   |
| Intel Core Processor Integrated Graphics Controller                                      | 67        | 2.41%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 58        | 2.08%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 54        | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 50        | 1.8%    |
| Intel HD Graphics 620                                                                    | 49        | 1.76%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 44        | 1.58%   |
| Intel UHD Graphics 620                                                                   | 42        | 1.51%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 42        | 1.51%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 41        | 1.47%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 38        | 1.36%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 34        | 1.22%   |
| Intel HD Graphics 5500                                                                   | 34        | 1.22%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 34        | 1.22%   |
| AMD Renoir                                                                               | 32        | 1.15%   |
| Intel HD Graphics 630                                                                    | 31        | 1.11%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 31        | 1.11%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 28        | 1.01%   |
| Intel HD Graphics 530                                                                    | 27        | 0.97%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 27        | 0.97%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 25        | 0.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 25        | 0.9%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 25        | 0.9%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 22        | 0.79%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 22        | 0.79%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 22        | 0.79%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 22        | 0.79%   |
| AMD Lucienne                                                                             | 21        | 0.75%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 21        | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 20        | 0.72%   |
| Intel HD Graphics 500                                                                    | 20        | 0.72%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 20        | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 19        | 0.68%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 18        | 0.65%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 17        | 0.61%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 17        | 0.61%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 15        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1122      | 47.08%  |
| 1 x AMD        | 501       | 21.02%  |
| 1 x Nvidia     | 422       | 17.71%  |
| Intel + Nvidia | 214       | 8.98%   |
| Intel + AMD    | 58        | 2.43%   |
| AMD + Nvidia   | 28        | 1.17%   |
| 2 x AMD        | 25        | 1.05%   |
| 2 x Nvidia     | 3         | 0.13%   |
| 1 x VIA        | 3         | 0.13%   |
| 1 x SiS        | 2         | 0.08%   |
| 1 x Matrox     | 2         | 0.08%   |
| Other          | 1         | 0.04%   |
| 2 x Intel      | 1         | 0.04%   |
| 1 x ASPEED     | 1         | 0.04%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1894      | 79.38%  |
| Proprietary | 418       | 17.52%  |
| Unknown     | 74        | 3.1%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1396      | 57.85%  |
| 0.01-0.5   | 275       | 11.4%   |
| 1.01-2.0   | 244       | 10.11%  |
| 0.51-1.0   | 215       | 8.91%   |
| 3.01-4.0   | 117       | 4.85%   |
| 7.01-8.0   | 78        | 3.23%   |
| 5.01-6.0   | 42        | 1.74%   |
| 8.01-16.0  | 25        | 1.04%   |
| 2.01-3.0   | 17        | 0.7%    |
| 16.01-24.0 | 4         | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 318       | 12.97%  |
| AU Optronics            | 283       | 11.55%  |
| Chimei Innolux          | 220       | 8.98%   |
| LG Display              | 217       | 8.85%   |
| BOE                     | 193       | 7.87%   |
| Dell                    | 132       | 5.39%   |
| Goldstar                | 114       | 4.65%   |
| Hewlett-Packard         | 89        | 3.63%   |
| Acer                    | 69        | 2.82%   |
| Apple                   | 64        | 2.61%   |
| Philips                 | 62        | 2.53%   |
| AOC                     | 55        | 2.24%   |
| Chi Mei Optoelectronics | 46        | 1.88%   |
| Ancor Communications    | 46        | 1.88%   |
| BenQ                    | 42        | 1.71%   |
| Lenovo                  | 37        | 1.51%   |
| Sharp                   | 31        | 1.26%   |
| LG Electronics          | 25        | 1.02%   |
| Unknown                 | 20        | 0.82%   |
| Sony                    | 20        | 0.82%   |
| PANDA                   | 19        | 0.78%   |
| ViewSonic               | 18        | 0.73%   |
| LG Philips              | 18        | 0.73%   |
| Unknown                 | 17        | 0.69%   |
| ASUSTek Computer        | 16        | 0.65%   |
| Vizio                   | 15        | 0.61%   |
| Iiyama                  | 15        | 0.61%   |
| Sceptre Tech            | 11        | 0.45%   |
| InfoVision              | 11        | 0.45%   |
| HPN                     | 10        | 0.41%   |
| NEC Computers           | 9         | 0.37%   |
| Fujitsu Siemens         | 9         | 0.37%   |
| Eizo                    | 9         | 0.37%   |
| HannStar                | 8         | 0.33%   |
| CPT                     | 8         | 0.33%   |
| Toshiba                 | 7         | 0.29%   |
| Panasonic               | 7         | 0.29%   |
| LGD                     | 6         | 0.24%   |
| AUS                     | 6         | 0.24%   |
| MSI                     | 5         | 0.2%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                  | 17        | 0.68%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 15        | 0.6%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 15        | 0.6%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 12        | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 11        | 0.44%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 10        | 0.4%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 10        | 0.4%    |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 9         | 0.36%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 9         | 0.36%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch                 | 9         | 0.36%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 9         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 9         | 0.36%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 9         | 0.36%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 9         | 0.36%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 7         | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.28%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                    | 7         | 0.28%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                     | 7         | 0.28%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch            | 7         | 0.28%   |
| LG Display LCD Monitor LGD0555 1536x1024 263x175mm 12.4-inch             | 6         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15C6 1366x768 344x193mm 15.5-inch          | 6         | 0.24%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 6         | 0.24%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 6         | 0.24%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 6         | 0.24%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.24%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 6         | 0.24%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 309x174mm 14.0-inch     | 5         | 0.2%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch    | 5         | 0.2%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 5         | 0.2%    |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 5         | 0.2%    |
| Chimei Innolux LCD Monitor CMN1728 1600x900 382x215mm 17.3-inch          | 5         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 5         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 5         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch          | 5         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 5         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch          | 5         | 0.2%    |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch            | 5         | 0.2%    |
| AU Optronics LCD Monitor AUO405C 1366x768 256x144mm 11.6-inch            | 5         | 0.2%    |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 5         | 0.2%    |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch           | 5         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 884       | 37.16%  |
| 1366x768 (WXGA)    | 614       | 25.81%  |
| 1600x900 (HD+)     | 131       | 5.51%   |
| 3840x2160 (4K)     | 127       | 5.34%   |
| 1280x800 (WXGA)    | 69        | 2.9%    |
| 2560x1440 (QHD)    | 68        | 2.86%   |
| 1680x1050 (WSXGA+) | 66        | 2.77%   |
| 1440x900 (WXGA+)   | 62        | 2.61%   |
| 1280x1024 (SXGA)   | 61        | 2.56%   |
| Unknown            | 51        | 2.14%   |
| 1920x1200 (WUXGA)  | 34        | 1.43%   |
| 1360x768           | 32        | 1.35%   |
| 3840x1080          | 20        | 0.84%   |
| 3440x1440          | 16        | 0.67%   |
| 2560x1600          | 16        | 0.67%   |
| 2560x1080          | 13        | 0.55%   |
| 2736x1824          | 10        | 0.42%   |
| 1920x540           | 10        | 0.42%   |
| 2256x1504          | 8         | 0.34%   |
| 2160x1440          | 7         | 0.29%   |
| 3200x1800 (QHD+)   | 6         | 0.25%   |
| 1024x768 (XGA)     | 6         | 0.25%   |
| 3840x2400          | 5         | 0.21%   |
| 1600x1200          | 5         | 0.21%   |
| 2880x1800          | 4         | 0.17%   |
| 5760x1080          | 3         | 0.13%   |
| 4480x1440          | 3         | 0.13%   |
| 3840x1600          | 3         | 0.13%   |
| 3600x1080          | 3         | 0.13%   |
| 1280x720 (HD)      | 3         | 0.13%   |
| 1024x600           | 3         | 0.13%   |
| 5760x2160          | 2         | 0.08%   |
| 3360x1080          | 2         | 0.08%   |
| 3200x1200          | 2         | 0.08%   |
| 3120x1050          | 2         | 0.08%   |
| 2944x1080          | 2         | 0.08%   |
| 2880x1920          | 2         | 0.08%   |
| 1920x515           | 2         | 0.08%   |
| 1920x1280          | 2         | 0.08%   |
| 7680x2160          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 640       | 26.42%  |
| Unknown | 215       | 8.88%   |
| 13      | 213       | 8.79%   |
| 14      | 160       | 6.61%   |
| 17      | 148       | 6.11%   |
| 27      | 144       | 5.95%   |
| 24      | 121       | 5%      |
| 23      | 116       | 4.79%   |
| 21      | 112       | 4.62%   |
| 19      | 64        | 2.64%   |
| 11      | 60        | 2.48%   |
| 18      | 53        | 2.19%   |
| 31      | 52        | 2.15%   |
| 20      | 52        | 2.15%   |
| 12      | 46        | 1.9%    |
| 22      | 45        | 1.86%   |
| 34      | 24        | 0.99%   |
| 84      | 15        | 0.62%   |
| 54      | 14        | 0.58%   |
| 40      | 13        | 0.54%   |
| 32      | 13        | 0.54%   |
| 72      | 12        | 0.5%    |
| 16      | 12        | 0.5%    |
| 25      | 10        | 0.41%   |
| 26      | 8         | 0.33%   |
| 10      | 8         | 0.33%   |
| 65      | 4         | 0.17%   |
| 52      | 4         | 0.17%   |
| 49      | 4         | 0.17%   |
| 37      | 4         | 0.17%   |
| 36      | 4         | 0.17%   |
| 48      | 3         | 0.12%   |
| 33      | 3         | 0.12%   |
| 29      | 3         | 0.12%   |
| 74      | 2         | 0.08%   |
| 64      | 2         | 0.08%   |
| 42      | 2         | 0.08%   |
| 41      | 2         | 0.08%   |
| 35      | 2         | 0.08%   |
| 28      | 2         | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 918       | 38.57%  |
| 501-600     | 353       | 14.83%  |
| 401-500     | 292       | 12.27%  |
| 201-300     | 223       | 9.37%   |
| Unknown     | 215       | 9.03%   |
| 351-400     | 169       | 7.1%    |
| 601-700     | 72        | 3.03%   |
| 701-800     | 44        | 1.85%   |
| 1001-1500   | 37        | 1.55%   |
| 1501-2000   | 31        | 1.3%    |
| 801-900     | 20        | 0.84%   |
| 901-1000    | 5         | 0.21%   |
| 101-200     | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1652      | 74.01%  |
| 16/10   | 245       | 10.98%  |
| Unknown | 194       | 8.69%   |
| 5/4     | 54        | 2.42%   |
| 3/2     | 33        | 1.48%   |
| 21/9    | 29        | 1.3%    |
| 4/3     | 14        | 0.63%   |
| 32/9    | 6         | 0.27%   |
| 6/5     | 2         | 0.09%   |
| 3.73    | 2         | 0.09%   |
| 0.62    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 641       | 26.65%  |
| 201-250        | 313       | 13.01%  |
| 81-90          | 293       | 12.18%  |
| Unknown        | 215       | 8.94%   |
| 151-200        | 160       | 6.65%   |
| 301-350        | 146       | 6.07%   |
| 121-130        | 101       | 4.2%    |
| 351-500        | 99        | 4.12%   |
| 71-80          | 84        | 3.49%   |
| 141-150        | 73        | 3.04%   |
| More than 1000 | 64        | 2.66%   |
| 51-60          | 61        | 2.54%   |
| 251-300        | 49        | 2.04%   |
| 61-70          | 39        | 1.62%   |
| 501-1000       | 29        | 1.21%   |
| 131-140        | 16        | 0.67%   |
| 111-120        | 9         | 0.37%   |
| 41-50          | 7         | 0.29%   |
| 91-100         | 5         | 0.21%   |
| 1-40           | 1         | 0.04%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 719       | 30.67%  |
| 51-100        | 703       | 29.99%  |
| 121-160       | 503       | 21.46%  |
| Unknown       | 215       | 9.17%   |
| 161-240       | 100       | 4.27%   |
| 1-50          | 63        | 2.69%   |
| More than 240 | 41        | 1.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2012      | 83.55%  |
| 2     | 296       | 12.29%  |
| 0     | 74        | 3.07%   |
| 3     | 23        | 0.96%   |
| 4     | 2         | 0.08%   |
| 5     | 1         | 0.04%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1298      | 35.73%  |
| Intel                             | 987       | 27.17%  |
| Qualcomm Atheros                  | 474       | 13.05%  |
| Broadcom                          | 263       | 7.24%   |
| Broadcom Limited                  | 76        | 2.09%   |
| Ralink Technology                 | 54        | 1.49%   |
| TP-Link                           | 52        | 1.43%   |
| Ralink                            | 47        | 1.29%   |
| Marvell Technology Group          | 46        | 1.27%   |
| MediaTek                          | 33        | 0.91%   |
| Nvidia                            | 32        | 0.88%   |
| Samsung Electronics               | 24        | 0.66%   |
| ASIX Electronics                  | 20        | 0.55%   |
| Xiaomi                            | 14        | 0.39%   |
| NetGear                           | 14        | 0.39%   |
| DisplayLink                       | 14        | 0.39%   |
| Qualcomm Atheros Communications   | 12        | 0.33%   |
| Dell                              | 12        | 0.33%   |
| Huawei Technologies               | 10        | 0.28%   |
| Microsoft                         | 9         | 0.25%   |
| Edimax Technology                 | 9         | 0.25%   |
| D-Link System                     | 9         | 0.25%   |
| Sierra Wireless                   | 7         | 0.19%   |
| JMicron Technology                | 7         | 0.19%   |
| Hewlett-Packard                   | 7         | 0.19%   |
| D-Link                            | 7         | 0.19%   |
| ASUSTek Computer                  | 7         | 0.19%   |
| Qualcomm                          | 6         | 0.17%   |
| Motorola PCS                      | 5         | 0.14%   |
| Linksys                           | 5         | 0.14%   |
| Ericsson Business Mobile Networks | 5         | 0.14%   |
| T & A Mobile Phones               | 4         | 0.11%   |
| OPPO Electronics                  | 4         | 0.11%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.11%   |
| Aquantia                          | 4         | 0.11%   |
| Google                            | 3         | 0.08%   |
| ZyDAS                             | 2         | 0.06%   |
| VIA Technologies                  | 2         | 0.06%   |
| U-Blox                            | 2         | 0.06%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 824       | 19.53%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 204       | 4.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 118       | 2.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 92        | 2.18%   |
| Intel Wi-Fi 6 AX200                                               | 76        | 1.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 65        | 1.54%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 65        | 1.54%   |
| Intel Wireless 7265                                               | 54        | 1.28%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 53        | 1.26%   |
| Intel Wireless 7260                                               | 53        | 1.26%   |
| Realtek RTL8125 2.5GbE Controller                                 | 49        | 1.16%   |
| Intel Wireless 8265 / 8275                                        | 49        | 1.16%   |
| Intel Wi-Fi 6 AX201                                               | 46        | 1.09%   |
| Intel Ethernet Connection I217-LM                                 | 46        | 1.09%   |
| Broadcom BCM43142 802.11b/g/n                                     | 45        | 1.07%   |
| Intel I211 Gigabit Network Connection                             | 44        | 1.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 43        | 1.02%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 40        | 0.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 40        | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 35        | 0.83%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 34        | 0.81%   |
| Intel Wireless 8260                                               | 34        | 0.81%   |
| Realtek 802.11ac NIC                                              | 33        | 0.78%   |
| Intel Wireless 3165                                               | 33        | 0.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 31        | 0.73%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 29        | 0.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 28        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 26        | 0.62%   |
| Intel Ethernet Connection (2) I219-V                              | 26        | 0.62%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 24        | 0.57%   |
| Ralink MT7601U Wireless Adapter                                   | 24        | 0.57%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 24        | 0.57%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 24        | 0.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 24        | 0.57%   |
| Realtek RTL8188EE Wireless Network Adapter                        | 23        | 0.55%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 23        | 0.55%   |
| Intel Ethernet Controller I225-V                                  | 23        | 0.55%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 23        | 0.55%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 20        | 0.47%   |
| Realtek 802.11n WLAN Adapter                                      | 20        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 736       | 36.65%  |
| Qualcomm Atheros                      | 376       | 18.73%  |
| Realtek Semiconductor                 | 373       | 18.58%  |
| Broadcom                              | 186       | 9.26%   |
| Ralink Technology                     | 54        | 2.69%   |
| Broadcom Limited                      | 49        | 2.44%   |
| Ralink                                | 47        | 2.34%   |
| TP-Link                               | 45        | 2.24%   |
| MediaTek                              | 27        | 1.34%   |
| NetGear                               | 14        | 0.7%    |
| Qualcomm Atheros Communications       | 12        | 0.6%    |
| Marvell Technology Group              | 12        | 0.6%    |
| Edimax Technology                     | 9         | 0.45%   |
| Microsoft                             | 8         | 0.4%    |
| Sierra Wireless                       | 7         | 0.35%   |
| D-Link System                         | 7         | 0.35%   |
| D-Link                                | 7         | 0.35%   |
| Dell                                  | 6         | 0.3%    |
| ASUSTek Computer                      | 6         | 0.3%    |
| Linksys                               | 5         | 0.25%   |
| ZyDAS                                 | 2         | 0.1%    |
| Gemtek                                | 2         | 0.1%    |
| Fibocom                               | 2         | 0.1%    |
| Belkin Components                     | 2         | 0.1%    |
| AVM                                   | 2         | 0.1%    |
| ZyXEL Communications                  | 1         | 0.05%   |
| Xiaomi                                | 1         | 0.05%   |
| TRENDnet                              | 1         | 0.05%   |
| Samsung Electronics                   | 1         | 0.05%   |
| Qualcomm                              | 1         | 0.05%   |
| Panasonic (Matsushita)                | 1         | 0.05%   |
| Ovislink                              | 1         | 0.05%   |
| Mercucys                              | 1         | 0.05%   |
| Hewlett-Packard                       | 1         | 0.05%   |
| Askey Computer                        | 1         | 0.05%   |
| ADMtek                                | 1         | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 92        | 4.54%   |
| Intel Wi-Fi 6 AX200                                            | 76        | 3.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 65        | 3.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 65        | 3.21%   |
| Intel Wireless 7265                                            | 54        | 2.66%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 53        | 2.61%   |
| Intel Wireless 7260                                            | 53        | 2.61%   |
| Intel Wireless 8265 / 8275                                     | 49        | 2.42%   |
| Intel Wi-Fi 6 AX201                                            | 46        | 2.27%   |
| Broadcom BCM43142 802.11b/g/n                                  | 45        | 2.22%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 43        | 2.12%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 40        | 1.97%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 35        | 1.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 34        | 1.68%   |
| Intel Wireless 8260                                            | 34        | 1.68%   |
| Realtek 802.11ac NIC                                           | 33        | 1.63%   |
| Intel Wireless 3165                                            | 33        | 1.63%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 31        | 1.53%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 29        | 1.43%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 28        | 1.38%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 24        | 1.18%   |
| Ralink MT7601U Wireless Adapter                                | 24        | 1.18%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 24        | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 24        | 1.18%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 23        | 1.13%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 23        | 1.13%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 23        | 1.13%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 20        | 0.99%   |
| Realtek 802.11n WLAN Adapter                                   | 20        | 0.99%   |
| Intel WiFi Link 5100                                           | 19        | 0.94%   |
| Intel Centrino Ultimate-N 6300                                 | 19        | 0.94%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 18        | 0.89%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 17        | 0.84%   |
| Intel Wireless-AC 9260                                         | 16        | 0.79%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                      | 16        | 0.79%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 16        | 0.79%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 15        | 0.74%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 14        | 0.69%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 14        | 0.69%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 14        | 0.69%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1136      | 53.61%  |
| Intel                             | 502       | 23.69%  |
| Qualcomm Atheros                  | 137       | 6.47%   |
| Broadcom                          | 111       | 5.24%   |
| Marvell Technology Group          | 34        | 1.6%    |
| Nvidia                            | 32        | 1.51%   |
| Broadcom Limited                  | 29        | 1.37%   |
| Samsung Electronics               | 23        | 1.09%   |
| ASIX Electronics                  | 20        | 0.94%   |
| DisplayLink                       | 14        | 0.66%   |
| Xiaomi                            | 13        | 0.61%   |
| TP-Link                           | 7         | 0.33%   |
| JMicron Technology                | 7         | 0.33%   |
| Huawei Technologies               | 7         | 0.33%   |
| MediaTek                          | 6         | 0.28%   |
| Qualcomm                          | 5         | 0.24%   |
| OPPO Electronics                  | 4         | 0.19%   |
| Aquantia                          | 4         | 0.19%   |
| Motorola PCS                      | 3         | 0.14%   |
| Hewlett-Packard                   | 3         | 0.14%   |
| Google                            | 3         | 0.14%   |
| VIA Technologies                  | 2         | 0.09%   |
| Silicon Integrated Systems [SiS]  | 2         | 0.09%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.09%   |
| HMD Global                        | 2         | 0.09%   |
| D-Link System                     | 2         | 0.09%   |
| Sundance Technology Inc / IC Plus | 1         | 0.05%   |
| Sun Microsystems                  | 1         | 0.05%   |
| Research In Motion                | 1         | 0.05%   |
| Novatel Wireless                  | 1         | 0.05%   |
| Motorola BCS                      | 1         | 0.05%   |
| Lenovo                            | 1         | 0.05%   |
| ICS Advent                        | 1         | 0.05%   |
| GoPro                             | 1         | 0.05%   |
| ASUSTek Computer                  | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 824       | 38.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 204       | 9.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 118       | 5.49%   |
| Realtek RTL8125 2.5GbE Controller                                 | 49        | 2.28%   |
| Intel Ethernet Connection I217-LM                                 | 46        | 2.14%   |
| Intel I211 Gigabit Network Connection                             | 44        | 2.05%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 40        | 1.86%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 26        | 1.21%   |
| Intel Ethernet Connection (2) I219-V                              | 26        | 1.21%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 24        | 1.12%   |
| Intel Ethernet Controller I225-V                                  | 23        | 1.07%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 16        | 0.74%   |
| Intel Ethernet Connection I218-LM                                 | 16        | 0.74%   |
| Intel Ethernet Connection I217-V                                  | 16        | 0.74%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 0.74%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 15        | 0.7%    |
| ASIX AX88179 Gigabit Ethernet                                     | 15        | 0.7%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 14        | 0.65%   |
| Intel Ethernet Connection I219-LM                                 | 14        | 0.65%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 14        | 0.65%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 12        | 0.56%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 12        | 0.56%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 12        | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 12        | 0.56%   |
| Nvidia MCP79 Ethernet                                             | 12        | 0.56%   |
| Intel Ethernet Connection (7) I219-V                              | 12        | 0.56%   |
| Intel 82567LM Gigabit Network Connection                          | 12        | 0.56%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 12        | 0.56%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 11        | 0.51%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 10        | 0.47%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 10        | 0.47%   |
| Intel Ethernet Connection (2) I219-LM                             | 10        | 0.47%   |
| Intel Ethernet Connection (2) I218-V                              | 10        | 0.47%   |
| Intel 82579V Gigabit Network Connection                           | 10        | 0.47%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 9         | 0.42%   |
| Nvidia MCP61 Ethernet                                             | 9         | 0.42%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 9         | 0.42%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 9         | 0.42%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 8         | 0.37%   |
| Intel Ethernet Connection (4) I219-V                              | 8         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1999      | 51.11%  |
| WiFi     | 1870      | 47.81%  |
| Modem    | 31        | 0.79%   |
| Unknown  | 11        | 0.28%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1466      | 59.33%  |
| Ethernet | 1001      | 40.51%  |
| Modem    | 2         | 0.08%   |
| Unknown  | 2         | 0.08%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1293      | 54.28%  |
| 1     | 956       | 40.13%  |
| 0     | 84        | 3.53%   |
| 3     | 44        | 1.85%   |
| 5     | 3         | 0.13%   |
| 7     | 1         | 0.04%   |
| 4     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1651      | 68.53%  |
| Yes  | 758       | 31.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 547       | 38.82%  |
| Realtek Semiconductor           | 173       | 12.28%  |
| Qualcomm Atheros Communications | 144       | 10.22%  |
| Broadcom                        | 85        | 6.03%   |
| Cambridge Silicon Radio         | 83        | 5.89%   |
| IMC Networks                    | 72        | 5.11%   |
| Apple                           | 71        | 5.04%   |
| Lite-On Technology              | 40        | 2.84%   |
| Foxconn / Hon Hai               | 34        | 2.41%   |
| Dell                            | 28        | 1.99%   |
| ASUSTek Computer                | 25        | 1.77%   |
| Hewlett-Packard                 | 20        | 1.42%   |
| Toshiba                         | 19        | 1.35%   |
| Ralink                          | 12        | 0.85%   |
| Marvell Semiconductor           | 11        | 0.78%   |
| MediaTek                        | 8         | 0.57%   |
| Foxconn International           | 5         | 0.35%   |
| TP-Link                         | 4         | 0.28%   |
| Realtek                         | 4         | 0.28%   |
| Integrated System Solution      | 4         | 0.28%   |
| Alps Electric                   | 4         | 0.28%   |
| Dynex                           | 3         | 0.21%   |
| Belkin Components               | 2         | 0.14%   |
| Askey Computer                  | 2         | 0.14%   |
| Sitecom Europe                  | 1         | 0.07%   |
| Qcom                            | 1         | 0.07%   |
| National Semiconductor          | 1         | 0.07%   |
| Micro Star International        | 1         | 0.07%   |
| Edimax Technology               | 1         | 0.07%   |
| D-Link System                   | 1         | 0.07%   |
| Chicony Electronics             | 1         | 0.07%   |
| Actions                         | 1         | 0.07%   |
| Unknown                         | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 225       | 15.96%  |
| Realtek Bluetooth Radio                             | 120       | 8.51%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 83        | 5.89%   |
| Intel AX201 Bluetooth                               | 81        | 5.74%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 69        | 4.89%   |
| Intel AX200 Bluetooth                               | 66        | 4.68%   |
| Qualcomm Atheros  Bluetooth Device                  | 60        | 4.26%   |
| Realtek  Bluetooth 4.2 Adapter                      | 38        | 2.7%    |
| IMC Networks Bluetooth Device                       | 30        | 2.13%   |
| Intel AX210 Bluetooth                               | 29        | 2.06%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 26        | 1.84%   |
| Apple Bluetooth Host Controller                     | 25        | 1.77%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 23        | 1.63%   |
| Intel Wireless-AC 3168 Bluetooth                    | 22        | 1.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 20        | 1.42%   |
| IMC Networks Bluetooth Radio                        | 19        | 1.35%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 19        | 1.35%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 19        | 1.35%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 17        | 1.21%   |
| Apple Bluetooth USB Host Controller                 | 17        | 1.21%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 16        | 1.13%   |
| Lite-On Atheros AR3012 Bluetooth                    | 15        | 1.06%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 13        | 0.92%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 13        | 0.92%   |
| Ralink RT3290 Bluetooth                             | 12        | 0.85%   |
| Marvell Bluetooth and Wireless LAN Composite        | 11        | 0.78%   |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 0.78%   |
| Foxconn / Hon Hai Bluetooth Device                  | 11        | 0.78%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 10        | 0.71%   |
| Dell DW375 Bluetooth Module                         | 10        | 0.71%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 10        | 0.71%   |
| Apple Bluetooth HCI                                 | 10        | 0.71%   |
| IMC Networks Wireless_Device                        | 9         | 0.64%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 9         | 0.64%   |
| Broadcom BCM2045B (BDC-2.1)                         | 9         | 0.64%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 8         | 0.57%   |
| Realtek RTL8723B Bluetooth                          | 7         | 0.5%    |
| MediaTek Wireless_Device                            | 7         | 0.5%    |
| Lite-On Bluetooth Device                            | 7         | 0.5%    |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 7         | 0.5%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1749      | 54.84%  |
| AMD                                  | 667       | 20.92%  |
| Nvidia                               | 532       | 16.68%  |
| C-Media Electronics                  | 38        | 1.19%   |
| Creative Labs                        | 16        | 0.5%    |
| Logitech                             | 13        | 0.41%   |
| Texas Instruments                    | 12        | 0.38%   |
| Kingston Technology                  | 12        | 0.38%   |
| Realtek Semiconductor                | 11        | 0.34%   |
| JMTek                                | 10        | 0.31%   |
| Razer USA                            | 8         | 0.25%   |
| GN Netcom                            | 7         | 0.22%   |
| ASUSTek Computer                     | 7         | 0.22%   |
| VIA Technologies                     | 6         | 0.19%   |
| SteelSeries ApS                      | 6         | 0.19%   |
| Plantronics                          | 6         | 0.19%   |
| KTMicro                              | 5         | 0.16%   |
| Generalplus Technology               | 5         | 0.16%   |
| Creative Technology                  | 4         | 0.13%   |
| Lenovo                               | 3         | 0.09%   |
| Focusrite-Novation                   | 3         | 0.09%   |
| Corsair                              | 3         | 0.09%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.06%   |
| Tenx Technology                      | 2         | 0.06%   |
| Silicon Integrated Systems [SiS]     | 2         | 0.06%   |
| Sennheiser Communications            | 2         | 0.06%   |
| Samsung Electronics                  | 2         | 0.06%   |
| RODE Microphones                     | 2         | 0.06%   |
| Numark                               | 2         | 0.06%   |
| Micro Star International             | 2         | 0.06%   |
| DSEA A/S                             | 2         | 0.06%   |
| BEHRINGER International              | 2         | 0.06%   |
| Audio-Technica                       | 2         | 0.06%   |
| Astro Gaming                         | 2         | 0.06%   |
| XMOS                                 | 1         | 0.03%   |
| Valve Software                       | 1         | 0.03%   |
| Swissonic                            | 1         | 0.03%   |
| Sony                                 | 1         | 0.03%   |
| Silicon Labs                         | 1         | 0.03%   |
| Schiit Audio                         | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 207       | 5.49%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 201       | 5.33%   |
| Intel Sunrise Point-LP HD Audio                                            | 158       | 4.19%   |
| AMD Family 17h/19h HD Audio Controller                                     | 143       | 3.79%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 136       | 3.61%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 110       | 2.92%   |
| AMD FCH Azalia Controller                                                  | 103       | 2.73%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 93        | 2.47%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 89        | 2.36%   |
| AMD Starship/Matisse HD Audio Controller                                   | 84        | 2.23%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 79        | 2.1%    |
| Intel 8 Series HD Audio Controller                                         | 77        | 2.04%   |
| Intel Haswell-ULT HD Audio Controller                                      | 73        | 1.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 70        | 1.86%   |
| Intel Cannon Lake PCH cAVS                                                 | 70        | 1.86%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 69        | 1.83%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 68        | 1.8%    |
| AMD Kabini HDMI/DP Audio                                                   | 62        | 1.64%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 57        | 1.51%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 50        | 1.33%   |
| Intel Broadwell-U Audio Controller                                         | 50        | 1.33%   |
| Nvidia GF108 High Definition Audio Controller                              | 48        | 1.27%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 48        | 1.27%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 47        | 1.25%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 44        | 1.17%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 42        | 1.11%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 42        | 1.11%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 41        | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 36        | 0.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 32        | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 31        | 0.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 31        | 0.82%   |
| Intel 200 Series PCH HD Audio                                              | 30        | 0.8%    |
| Nvidia TU106 High Definition Audio Controller                              | 29        | 0.77%   |
| Nvidia TU116 High Definition Audio Controller                              | 28        | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 28        | 0.74%   |
| AMD High Definition Audio Controller                                       | 28        | 0.74%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 28        | 0.74%   |
| Intel Comet Lake PCH-LP cAVS                                               | 27        | 0.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 27        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 126       | 25.25%  |
| SK hynix            | 89        | 17.84%  |
| Micron Technology   | 53        | 10.62%  |
| Unknown             | 42        | 8.42%   |
| Kingston            | 39        | 7.82%   |
| Crucial             | 28        | 5.61%   |
| Unknown (ABCD)      | 17        | 3.41%   |
| G.Skill             | 16        | 3.21%   |
| Corsair             | 16        | 3.21%   |
| A-DATA Technology   | 13        | 2.61%   |
| Team                | 6         | 1.2%    |
| Ramaxel Technology  | 6         | 1.2%    |
| Nanya Technology    | 6         | 1.2%    |
| Elpida              | 6         | 1.2%    |
| Patriot             | 5         | 1%      |
| Unknown             | 4         | 0.8%    |
| Avant               | 3         | 0.6%    |
| Timetec             | 2         | 0.4%    |
| Teikon              | 2         | 0.4%    |
| Qimonda             | 2         | 0.4%    |
| Wilk                | 1         | 0.2%    |
| Unknown (08B5)      | 1         | 0.2%    |
| Unifosa             | 1         | 0.2%    |
| Transcend           | 1         | 0.2%    |
| Strontium           | 1         | 0.2%    |
| Smart               | 1         | 0.2%    |
| PUSKILL             | 1         | 0.2%    |
| Netlist             | 1         | 0.2%    |
| Kingmax             | 1         | 0.2%    |
| GSkill              | 1         | 0.2%    |
| Goldkey             | 1         | 0.2%    |
| ff                  | 1         | 0.2%    |
| F7852C80            | 1         | 0.2%    |
| Essencore           | 1         | 0.2%    |
| CSX                 | 1         | 0.2%    |
| Axiom               | 1         | 0.2%    |
| AMD                 | 1         | 0.2%    |
| 4ea5                | 1         | 0.2%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 15        | 2.83%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 8         | 1.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 1.13%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 6         | 1.13%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 6         | 1.13%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 1.13%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.13%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.94%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s    | 4         | 0.75%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 0.75%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.75%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 4         | 0.75%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 0.75%   |
| Unknown                                                          | 4         | 0.75%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.57%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.57%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 3         | 0.57%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.57%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.57%   |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 3         | 0.57%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 3         | 0.57%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 3         | 0.57%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.57%   |
| Kingston RAM ACR16D3LS1KFG/4G 4096MB SODIMM DDR3 1600MT/s        | 3         | 0.57%   |
| Elpida RAM EBJ21UE8BDS0-DJ-F 2GB SODIMM DDR3 1334MT/s            | 3         | 0.57%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                      | 2         | 0.38%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 2         | 0.38%   |
| Unknown RAM Module 4096MB SODIMM DDR3                            | 2         | 0.38%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 2         | 0.38%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 2         | 0.38%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 2         | 0.38%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 2         | 0.38%   |
| Team RAM TEAMGROUP-UD4-2666 32GB DIMM DDR4 3000MT/s              | 2         | 0.38%   |
| SK hynix RAM Module 8192MB SODIMM DDR4 2400MT/s                  | 2         | 0.38%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 2         | 0.38%   |
| SK hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 3200MT/s           | 2         | 0.38%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s          | 2         | 0.38%   |
| SK hynix RAM HMT351U6CFR8C-H9 4GB DIMM DDR3 1600MT/s             | 2         | 0.38%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 2         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 181       | 42.39%  |
| DDR3    | 154       | 36.07%  |
| LPDDR4  | 35        | 8.2%    |
| LPDDR3  | 18        | 4.22%   |
| DDR2    | 17        | 3.98%   |
| SDRAM   | 10        | 2.34%   |
| Unknown | 8         | 1.87%   |
| DDR     | 3         | 0.7%    |
| LPDDR5  | 1         | 0.23%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 256       | 59.95%  |
| DIMM         | 119       | 27.87%  |
| Row Of Chips | 47        | 11.01%  |
| Chip         | 2         | 0.47%   |
| Unknown      | 2         | 0.47%   |
| FB-DIMM      | 1         | 0.23%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 183       | 38.85%  |
| 4096  | 157       | 33.33%  |
| 2048  | 62        | 13.16%  |
| 16384 | 45        | 9.55%   |
| 1024  | 13        | 2.76%   |
| 32768 | 11        | 2.34%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 99        | 21.2%   |
| 3200    | 69        | 14.78%  |
| 2667    | 61        | 13.06%  |
| 2400    | 43        | 9.21%   |
| 1333    | 33        | 7.07%   |
| 1334    | 19        | 4.07%   |
| 2133    | 18        | 3.85%   |
| 4267    | 12        | 2.57%   |
| 1867    | 12        | 2.57%   |
| 3600    | 10        | 2.14%   |
| 667     | 10        | 2.14%   |
| 3266    | 8         | 1.71%   |
| 1066    | 8         | 1.71%   |
| 800     | 7         | 1.5%    |
| Unknown | 7         | 1.5%    |
| 3000    | 4         | 0.86%   |
| 1866    | 4         | 0.86%   |
| 1800    | 4         | 0.86%   |
| 8400    | 3         | 0.64%   |
| 2666    | 3         | 0.64%   |
| 2048    | 3         | 0.64%   |
| 4266    | 2         | 0.43%   |
| 4199    | 2         | 0.43%   |
| 3866    | 2         | 0.43%   |
| 3666    | 2         | 0.43%   |
| 3466    | 2         | 0.43%   |
| 3333    | 2         | 0.43%   |
| 2933    | 2         | 0.43%   |
| 1067    | 2         | 0.43%   |
| 975     | 2         | 0.43%   |
| 6400    | 1         | 0.21%   |
| 4800    | 1         | 0.21%   |
| 4000    | 1         | 0.21%   |
| 3800    | 1         | 0.21%   |
| 3733    | 1         | 0.21%   |
| 3400    | 1         | 0.21%   |
| 2800    | 1         | 0.21%   |
| 2200    | 1         | 0.21%   |
| 1400    | 1         | 0.21%   |
| 976     | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 16        | 32%     |
| Canon                 | 10        | 20%     |
| Seiko Epson           | 7         | 14%     |
| Samsung Electronics   | 7         | 14%     |
| Brother Industries    | 7         | 14%     |
| Zebra                 | 1         | 2%      |
| QinHeng Electronics   | 1         | 2%      |
| Lexmark International | 1         | 2%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| Seiko Epson L3110 Series             | 3         | 6%      |
| HP ENVY Photo 6200 series            | 2         | 4%      |
| HP DeskJet 2130 series               | 2         | 4%      |
| Canon TS3100 series                  | 2         | 4%      |
| Zebra ZP 450 Printer                 | 1         | 2%      |
| Seiko Epson XP-7100 Series           | 1         | 2%      |
| Seiko Epson XP-200 Series            | 1         | 2%      |
| Seiko Epson L355 Series              | 1         | 2%      |
| Seiko Epson ET-2820 Series           | 1         | 2%      |
| Samsung SCX-483x 5x3x Series         | 1         | 2%      |
| Samsung SCX-4200 series              | 1         | 2%      |
| Samsung SCX-3400 Series              | 1         | 2%      |
| Samsung ML-2950 Series               | 1         | 2%      |
| Samsung ML-216x Series Laser Printer | 1         | 2%      |
| Samsung M2020 Series                 | 1         | 2%      |
| Samsung C460 Series                  | 1         | 2%      |
| QinHeng CH340S                       | 1         | 2%      |
| Lexmark International 2400 series    | 1         | 2%      |
| HP Smart Tank 510 series             | 1         | 2%      |
| HP PSC 1100 series                   | 1         | 2%      |
| HP OfficeJet Pro 9010 series         | 1         | 2%      |
| HP Officejet 6600                    | 1         | 2%      |
| HP OfficeJet 4650 series             | 1         | 2%      |
| HP LaserJet Professional P1102w      | 1         | 2%      |
| HP LaserJet 1200                     | 1         | 2%      |
| HP LaserJet 1000                     | 1         | 2%      |
| HP ENVY 4520 series                  | 1         | 2%      |
| HP DeskJet 2700 series               | 1         | 2%      |
| HP DeskJet 2300 series               | 1         | 2%      |
| HP DeskJet 1110 series               | 1         | 2%      |
| Canon TR4500 series                  | 1         | 2%      |
| Canon PIXMA MX320 series             | 1         | 2%      |
| Canon PIXMA MG3000 series            | 1         | 2%      |
| Canon PIXMA MG2500 Series            | 1         | 2%      |
| Canon LiDE 400                       | 1         | 2%      |
| Canon iP4200                         | 1         | 2%      |
| Canon G3010 series                   | 1         | 2%      |
| Canon E410 series                    | 1         | 2%      |
| Brother QL-500 label printer         | 1         | 2%      |
| Brother MFC-J1010DW                  | 1         | 2%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 7         | 63.64%  |
| Seiko Epson     | 2         | 18.18%  |
| Hewlett-Packard | 2         | 18.18%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X750 [Perfection 4490 Photo] | 2         | 18.18%  |
| HP ScanJet 2400c                            | 1         | 9.09%   |
| HP PSC 1200                                 | 1         | 9.09%   |
| Canon CanoScan LiDE 90                      | 1         | 9.09%   |
| Canon CanoScan LiDE 60                      | 1         | 9.09%   |
| Canon CanoScan LIDE 25                      | 1         | 9.09%   |
| Canon CanoScan LiDE 110                     | 1         | 9.09%   |
| Canon CanoScan LiDE 100                     | 1         | 9.09%   |
| Canon CanoScan D660U                        | 1         | 9.09%   |
| Canon CanoScan 8800F                        | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 290       | 20.94%  |
| Microdia                               | 130       | 9.39%   |
| Realtek Semiconductor                  | 117       | 8.45%   |
| IMC Networks                           | 110       | 7.94%   |
| Acer                                   | 81        | 5.85%   |
| Sunplus Innovation Technology          | 77        | 5.56%   |
| Apple                                  | 70        | 5.05%   |
| Cheng Uei Precision Industry (Foxlink) | 67        | 4.84%   |
| Suyin                                  | 50        | 3.61%   |
| Quanta                                 | 50        | 3.61%   |
| Logitech                               | 50        | 3.61%   |
| Syntek                                 | 36        | 2.6%    |
| Silicon Motion                         | 23        | 1.66%   |
| Lite-On Technology                     | 21        | 1.52%   |
| Alcor Micro                            | 19        | 1.37%   |
| Ricoh                                  | 17        | 1.23%   |
| Samsung Electronics                    | 15        | 1.08%   |
| Luxvisions Innotech Limited            | 12        | 0.87%   |
| USB Camera                             | 11        | 0.79%   |
| Primax Electronics                     | 11        | 0.79%   |
| Microsoft                              | 11        | 0.79%   |
| Generalplus Technology                 | 10        | 0.72%   |
| ARC International                      | 9         | 0.65%   |
| Sonix Technology                       | 7         | 0.51%   |
| ALi                                    | 7         | 0.51%   |
| Unknown                                | 6         | 0.43%   |
| Lenovo                                 | 6         | 0.43%   |
| SunplusIT                              | 5         | 0.36%   |
| Importek                               | 5         | 0.36%   |
| Sunplus Technology                     | 4         | 0.29%   |
| GEMBIRD                                | 4         | 0.29%   |
| Z-Star Microelectronics                | 3         | 0.22%   |
| Razer USA                              | 3         | 0.22%   |
| Jieli Technology                       | 3         | 0.22%   |
| Huawei Technologies                    | 3         | 0.22%   |
| Genesys Logic                          | 3         | 0.22%   |
| Xiongmai                               | 2         | 0.14%   |
| Pixart Imaging                         | 2         | 0.14%   |
| OmniVision Technologies                | 2         | 0.14%   |
| HD 2MP WEBCAM                          | 2         | 0.14%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 40        | 2.87%   |
| Microdia Integrated_Webcam_HD                    | 31        | 2.23%   |
| Realtek Integrated_Webcam_HD                     | 29        | 2.08%   |
| IMC Networks USB2.0 HD UVC WebCam                | 28        | 2.01%   |
| Acer Integrated Camera                           | 26        | 1.87%   |
| Apple FaceTime HD Camera (Built-in)              | 25        | 1.79%   |
| Microdia Integrated Webcam                       | 24        | 1.72%   |
| Syntek Integrated Camera                         | 22        | 1.58%   |
| Chicony HD WebCam                                | 22        | 1.58%   |
| Chicony HP TrueVision HD                         | 20        | 1.44%   |
| IMC Networks Integrated Camera                   | 18        | 1.29%   |
| Chicony TOSHIBA Web Camera - HD                  | 17        | 1.22%   |
| Apple iPhone5/5C/5S/6                            | 17        | 1.22%   |
| Realtek USB Camera                               | 16        | 1.15%   |
| Samsung Galaxy A5 (MTP)                          | 15        | 1.08%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 15        | 1.08%   |
| Apple Built-in iSight                            | 14        | 1.01%   |
| Acer Lenovo EasyCamera                           | 14        | 1.01%   |
| Sunplus HD WebCam                                | 13        | 0.93%   |
| Logitech Webcam C270                             | 12        | 0.86%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 12        | 0.86%   |
| USB Camera USB Camera                            | 11        | 0.79%   |
| Sunplus Integrated_Webcam_HD                     | 11        | 0.79%   |
| Microdia Webcam Vitade AF                        | 11        | 0.79%   |
| Chicony USB2.0 VGA UVC WebCam                    | 11        | 0.79%   |
| Chicony HP TrueVision HD Camera                  | 11        | 0.79%   |
| Apple FaceTime HD Camera                         | 11        | 0.79%   |
| Microdia USB 2.0 Camera                          | 10        | 0.72%   |
| Chicony HP HD Webcam                             | 10        | 0.72%   |
| Realtek Lenovo EasyCamera                        | 9         | 0.65%   |
| Chicony Lenovo EasyCamera                        | 9         | 0.65%   |
| ARC International Camera                         | 9         | 0.65%   |
| Alcor Micro USB 2.0 Camera                       | 9         | 0.65%   |
| Realtek Integrated Webcam                        | 8         | 0.57%   |
| Quanta HP Wide Vision HD Camera                  | 8         | 0.57%   |
| Quanta HP TrueVision HD Camera                   | 8         | 0.57%   |
| Chicony VGA Webcam                               | 8         | 0.57%   |
| Chicony USB2.0 HD UVC WebCam                     | 8         | 0.57%   |
| Chicony USB 2.0 Camera                           | 8         | 0.57%   |
| Chicony HP Wide Vision HD Camera                 | 8         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 85        | 40.09%  |
| Synaptics                  | 29        | 13.68%  |
| Shenzhen Goodix Technology | 29        | 13.68%  |
| AuthenTec                  | 23        | 10.85%  |
| Upek                       | 19        | 8.96%   |
| Elan Microelectronics      | 11        | 5.19%   |
| LighTuning Technology      | 8         | 3.77%   |
| STMicroelectronics         | 5         | 2.36%   |
| Samsung Electronics        | 2         | 0.94%   |
| Focal-systems.Corp         | 1         | 0.47%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 18        | 8.49%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 18        | 8.49%   |
| Shenzhen Goodix  FingerPrint Device                                        | 16        | 7.55%   |
| Unknown                                                                    | 13        | 6.13%   |
| Shenzhen Goodix Fingerprint Reader                                         | 11        | 5.19%   |
| AuthenTec AES2810                                                          | 10        | 4.72%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 9         | 4.25%   |
| Validity Sensors Fingerprint scanner                                       | 8         | 3.77%   |
| Validity Sensors VFS491                                                    | 7         | 3.3%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 3.3%    |
| Elan ELAN:ARM-M4                                                           | 7         | 3.3%    |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 6         | 2.83%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 2.36%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 2.36%   |
| STMicroelectronics Fingerprint Reader                                      | 5         | 2.36%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 2.36%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 1.89%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 1.89%   |
| Synaptics  WBDI                                                            | 4         | 1.89%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 1.89%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 1.89%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 4         | 1.89%   |
| Elan ELAN:Fingerprint                                                      | 4         | 1.89%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.89%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 1.42%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 1.42%   |
| AuthenTec AES1600                                                          | 3         | 1.42%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.94%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.94%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 0.94%   |
| Shenzhen Goodix FingerPrint                                                | 2         | 0.94%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 0.94%   |
| LighTuning Fingerprint Sensor                                              | 2         | 0.94%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.47%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.47%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.47%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.47%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 0.47%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.47%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.47%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 46        | 51.11%  |
| Alcor Micro                       | 13        | 14.44%  |
| O2 Micro                          | 7         | 7.78%   |
| Lenovo                            | 6         | 6.67%   |
| Upek                              | 5         | 5.56%   |
| Realtek Semiconductor             | 3         | 3.33%   |
| Yubico.com                        | 2         | 2.22%   |
| SCM Microsystems                  | 2         | 2.22%   |
| Advanced Card Systems             | 2         | 2.22%   |
| VASCO Data Security International | 1         | 1.11%   |
| Reiner SCT Kartensysteme          | 1         | 1.11%   |
| OmniKey                           | 1         | 1.11%   |
| Fujitsu Siemens Computers         | 1         | 1.11%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 18        | 20%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 15        | 16.67%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 14.44%  |
| Broadcom 5880                                                                | 9         | 10%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 7         | 7.78%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 6.67%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 5.56%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 3         | 3.33%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 2.22%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 2.22%   |
| Broadcom 58200                                                               | 2         | 2.22%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 1.11%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 1.11%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 1.11%   |
| Reiner SCT Kartensysteme cyberJack e-com/pinpad                              | 1         | 1.11%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 1.11%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 1.11%   |
| Advanced Card Systems ACR39U                                                 | 1         | 1.11%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 1.11%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1768      | 73.3%   |
| 1     | 537       | 22.26%  |
| 2     | 99        | 4.1%    |
| 3     | 8         | 0.33%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 207       | 27.94%  |
| Graphics card            | 151       | 20.38%  |
| Net/wireless             | 130       | 17.54%  |
| Multimedia controller    | 83        | 11.2%   |
| Chipcard                 | 81        | 10.93%  |
| Bluetooth                | 16        | 2.16%   |
| Storage                  | 15        | 2.02%   |
| Communication controller | 13        | 1.75%   |
| Unassigned class         | 6         | 0.81%   |
| Sound                    | 6         | 0.81%   |
| Camera                   | 6         | 0.81%   |
| Modem                    | 4         | 0.54%   |
| Dvb card                 | 4         | 0.54%   |
| Card reader              | 4         | 0.54%   |
| Storage/ide              | 3         | 0.4%    |
| Network                  | 3         | 0.4%    |
| Net/ethernet             | 3         | 0.4%    |
| Storage/nvme             | 2         | 0.27%   |
| Flash memory             | 2         | 0.27%   |
| Unclassified device      | 1         | 0.13%   |
| Storage/raid             | 1         | 0.13%   |

