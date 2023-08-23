Fedora - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Fedora.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Fedora/Desktop/README.md) and [notebooks](/Dist/Fedora/Notebook/README.md).

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

Total: 19299

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | G15 5510                    | Notebook    | [3cfac2d234](https://linux-hardware.org/?probe=3cfac2d234) | Aug 12, 2023 |
| Lenovo        | ThinkPad T460p 20FXS1C30... | Notebook    | [08542d994e](https://linux-hardware.org/?probe=08542d994e) | Aug 12, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [05024005e4](https://linux-hardware.org/?probe=05024005e4) | Aug 12, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | Notebook    | [411b9f412c](https://linux-hardware.org/?probe=411b9f412c) | Aug 12, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [d25ab08211](https://linux-hardware.org/?probe=d25ab08211) | Aug 12, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [90816726b0](https://linux-hardware.org/?probe=90816726b0) | Aug 12, 2023 |
| Toshiba       | Satellite C55-A             | Notebook    | [d1bf5ba3c3](https://linux-hardware.org/?probe=d1bf5ba3c3) | Aug 12, 2023 |
| Mini PC       | Rev JSL5 DDR4               | Mini pc     | [783651bb7d](https://linux-hardware.org/?probe=783651bb7d) | Aug 12, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [5b9aef438f](https://linux-hardware.org/?probe=5b9aef438f) | Aug 12, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [1f3f8a869b](https://linux-hardware.org/?probe=1f3f8a869b) | Aug 12, 2023 |
| Dell          | Latitude E7270              | Notebook    | [63fd1b0d6b](https://linux-hardware.org/?probe=63fd1b0d6b) | Aug 12, 2023 |
| Gigabyte      | Z170-HD3P-CF                | Desktop     | [7ef87af541](https://linux-hardware.org/?probe=7ef87af541) | Aug 12, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [92f4e14369](https://linux-hardware.org/?probe=92f4e14369) | Aug 11, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [377a0e25aa](https://linux-hardware.org/?probe=377a0e25aa) | Aug 11, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [7574e6b53a](https://linux-hardware.org/?probe=7574e6b53a) | Aug 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [d4b93affe2](https://linux-hardware.org/?probe=d4b93affe2) | Aug 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [7a8e32eb89](https://linux-hardware.org/?probe=7a8e32eb89) | Aug 11, 2023 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [c336f9aa8c](https://linux-hardware.org/?probe=c336f9aa8c) | Aug 11, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | Notebook    | [83879b8247](https://linux-hardware.org/?probe=83879b8247) | Aug 11, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [c352abad93](https://linux-hardware.org/?probe=c352abad93) | Aug 11, 2023 |
| Unknown       | Unknown                     | Desktop     | [4b174f07d2](https://linux-hardware.org/?probe=4b174f07d2) | Aug 11, 2023 |
| Acer          | Aspire E5-721               | Notebook    | [f4abfc94d4](https://linux-hardware.org/?probe=f4abfc94d4) | Aug 11, 2023 |
| Dell          | 0CRWCR A01                  | All in one  | [74283f31aa](https://linux-hardware.org/?probe=74283f31aa) | Aug 11, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [8c449cd820](https://linux-hardware.org/?probe=8c449cd820) | Aug 11, 2023 |
| ASUSTek       | ZenBook UX535LI_UX535LI     | Notebook    | [29065a56ee](https://linux-hardware.org/?probe=29065a56ee) | Aug 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [22fc28c382](https://linux-hardware.org/?probe=22fc28c382) | Aug 11, 2023 |
| Lenovo        | IdeaCentre B320             | Desktop     | [175fb6f041](https://linux-hardware.org/?probe=175fb6f041) | Aug 11, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [471e3c5077](https://linux-hardware.org/?probe=471e3c5077) | Aug 11, 2023 |
| Gigabyte      | Z170N-WIFI-CF               | Desktop     | [2ee88f0ec0](https://linux-hardware.org/?probe=2ee88f0ec0) | Aug 11, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [ee1a7cb0aa](https://linux-hardware.org/?probe=ee1a7cb0aa) | Aug 11, 2023 |
| ASUSTek       | P8Z68-V LE                  | Desktop     | [a88d7e81e5](https://linux-hardware.org/?probe=a88d7e81e5) | Aug 11, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [df9e6a8d98](https://linux-hardware.org/?probe=df9e6a8d98) | Aug 10, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [7da6954bc5](https://linux-hardware.org/?probe=7da6954bc5) | Aug 10, 2023 |
| Dell          | Latitude 5300               | Notebook    | [661051063f](https://linux-hardware.org/?probe=661051063f) | Aug 10, 2023 |
| Lenovo        | ThinkPad X220 4291SEN       | Notebook    | [b62026890a](https://linux-hardware.org/?probe=b62026890a) | Aug 10, 2023 |
| HP            | 250 G3                      | Notebook    | [512fd5d81f](https://linux-hardware.org/?probe=512fd5d81f) | Aug 10, 2023 |
| HP            | ProBook 430 G2              | Notebook    | [426901227d](https://linux-hardware.org/?probe=426901227d) | Aug 10, 2023 |
| Acer          | Aspire E5-721               | Notebook    | [6743c7ca9d](https://linux-hardware.org/?probe=6743c7ca9d) | Aug 10, 2023 |
| Gigabyte      | AERO 15-WA                  | Notebook    | [bd9f5d0f39](https://linux-hardware.org/?probe=bd9f5d0f39) | Aug 10, 2023 |
| Apple         | MacBookPro5,1               | Notebook    | [23fc9401d3](https://linux-hardware.org/?probe=23fc9401d3) | Aug 10, 2023 |
| Dell          | 0MGK50 A01                  | Desktop     | [ac0ed4109e](https://linux-hardware.org/?probe=ac0ed4109e) | Aug 10, 2023 |
| Lenovo        | IdeaPad U430 Touch 20270    | Notebook    | [4446f503d5](https://linux-hardware.org/?probe=4446f503d5) | Aug 10, 2023 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [13edff3291](https://linux-hardware.org/?probe=13edff3291) | Aug 10, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [c5491b8e9f](https://linux-hardware.org/?probe=c5491b8e9f) | Aug 10, 2023 |
| HP            | 14                          | Notebook    | [8692626574](https://linux-hardware.org/?probe=8692626574) | Aug 09, 2023 |
| HP            | Laptop 14s-dq2xxx           | Notebook    | [bb40aa6fd9](https://linux-hardware.org/?probe=bb40aa6fd9) | Aug 09, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [0f34656484](https://linux-hardware.org/?probe=0f34656484) | Aug 09, 2023 |
| Unknown       | Unknown                     | Desktop     | [09037ac346](https://linux-hardware.org/?probe=09037ac346) | Aug 09, 2023 |
| Dell          | 0PXXHP A03                  | Server      | [6fc4589ff0](https://linux-hardware.org/?probe=6fc4589ff0) | Aug 09, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [466419add0](https://linux-hardware.org/?probe=466419add0) | Aug 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [afa02e4c02](https://linux-hardware.org/?probe=afa02e4c02) | Aug 09, 2023 |
| Huanan        | X99-TF-Q GAMING V1.2        | Desktop     | [da612198cc](https://linux-hardware.org/?probe=da612198cc) | Aug 09, 2023 |
| Fujitsu       | UH-X                        | Notebook    | [e26b430aef](https://linux-hardware.org/?probe=e26b430aef) | Aug 09, 2023 |
| Unknown       | HX90                        | Desktop     | [7a14bb927e](https://linux-hardware.org/?probe=7a14bb927e) | Aug 09, 2023 |
| Supermicro    | X10SRi-FB                   | Server      | [253c6295e0](https://linux-hardware.org/?probe=253c6295e0) | Aug 09, 2023 |
| Dell          | 0CRWCR A01                  | All in one  | [8f3bc0a06a](https://linux-hardware.org/?probe=8f3bc0a06a) | Aug 09, 2023 |
| Lenovo        | ThinkPad S1 Yoga 20C0A0C... | Notebook    | [6de592988e](https://linux-hardware.org/?probe=6de592988e) | Aug 09, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [1aa926149a](https://linux-hardware.org/?probe=1aa926149a) | Aug 09, 2023 |
| Dell          | 06CJMN A00                  | Desktop     | [cead9bd601](https://linux-hardware.org/?probe=cead9bd601) | Aug 09, 2023 |
| Acer          | Aspire A317-33              | Notebook    | [6dd8126a05](https://linux-hardware.org/?probe=6dd8126a05) | Aug 09, 2023 |
| HP            | Notebook                    | Notebook    | [bac7155006](https://linux-hardware.org/?probe=bac7155006) | Aug 09, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [be4ad618b4](https://linux-hardware.org/?probe=be4ad618b4) | Aug 09, 2023 |
| HP            | 240 G5 Notebook PC          | Notebook    | [c801f4bbd0](https://linux-hardware.org/?probe=c801f4bbd0) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | Notebook    | [a8fc44190a](https://linux-hardware.org/?probe=a8fc44190a) | Aug 09, 2023 |
| ASUSTek       | ROG Strix G614JV_G614JV     | Notebook    | [766e35e920](https://linux-hardware.org/?probe=766e35e920) | Aug 09, 2023 |
| Apple         | MacBookPro15,2              | Notebook    | [68e26bb5d3](https://linux-hardware.org/?probe=68e26bb5d3) | Aug 09, 2023 |
| Dell          | Latitude 7320               | Notebook    | [6db1867722](https://linux-hardware.org/?probe=6db1867722) | Aug 09, 2023 |
| Acer          | Aspire E5-721               | Notebook    | [82a8a2346a](https://linux-hardware.org/?probe=82a8a2346a) | Aug 08, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [7ce5fc846b](https://linux-hardware.org/?probe=7ce5fc846b) | Aug 08, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [ee7bcf8fe1](https://linux-hardware.org/?probe=ee7bcf8fe1) | Aug 08, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S0C... | Notebook    | [2e4e848552](https://linux-hardware.org/?probe=2e4e848552) | Aug 08, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [1105c8c2ea](https://linux-hardware.org/?probe=1105c8c2ea) | Aug 08, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [c8553cabce](https://linux-hardware.org/?probe=c8553cabce) | Aug 08, 2023 |
| Gigabyte      | H510M S2H                   | Desktop     | [72eb04ca17](https://linux-hardware.org/?probe=72eb04ca17) | Aug 08, 2023 |
| Dell          | Latitude 5511               | Notebook    | [e9ea435e85](https://linux-hardware.org/?probe=e9ea435e85) | Aug 08, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | Notebook    | [914ff5745c](https://linux-hardware.org/?probe=914ff5745c) | Aug 08, 2023 |
| MSI           | Z170A GAMING M9 ACK         | Desktop     | [8839aa58c4](https://linux-hardware.org/?probe=8839aa58c4) | Aug 08, 2023 |
| HP            | 3397                        | Desktop     | [d7edc80c00](https://linux-hardware.org/?probe=d7edc80c00) | Aug 08, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [7a088aea04](https://linux-hardware.org/?probe=7a088aea04) | Aug 08, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [1a3b5297dd](https://linux-hardware.org/?probe=1a3b5297dd) | Aug 08, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [18208500ee](https://linux-hardware.org/?probe=18208500ee) | Aug 08, 2023 |
| Acer          | Aspire 4752                 | Notebook    | [1c68b4d24a](https://linux-hardware.org/?probe=1c68b4d24a) | Aug 08, 2023 |
| ASUSTek       | PHOENIX                     | Desktop     | [388bcf4158](https://linux-hardware.org/?probe=388bcf4158) | Aug 08, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5dfaa2b1c0](https://linux-hardware.org/?probe=5dfaa2b1c0) | Aug 08, 2023 |
| HP            | Elite x2 1012 G1            | Notebook    | [0ee8428f91](https://linux-hardware.org/?probe=0ee8428f91) | Aug 07, 2023 |
| Dell          | Inspiron 3505               | Notebook    | [e07624ae41](https://linux-hardware.org/?probe=e07624ae41) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [36b0caba9e](https://linux-hardware.org/?probe=36b0caba9e) | Aug 07, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [d989868a6b](https://linux-hardware.org/?probe=d989868a6b) | Aug 07, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [ee8f18e185](https://linux-hardware.org/?probe=ee8f18e185) | Aug 07, 2023 |
| Microsoft     | Surface Pro 6               | Tablet      | [d9513873ac](https://linux-hardware.org/?probe=d9513873ac) | Aug 07, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [8b5e74e190](https://linux-hardware.org/?probe=8b5e74e190) | Aug 07, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [0a1b8d0627](https://linux-hardware.org/?probe=0a1b8d0627) | Aug 07, 2023 |
| Timi          | A7S                         | Notebook    | [34a354df5a](https://linux-hardware.org/?probe=34a354df5a) | Aug 07, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [04e63e59bd](https://linux-hardware.org/?probe=04e63e59bd) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [b4b049b997](https://linux-hardware.org/?probe=b4b049b997) | Aug 07, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [8633bc5aa5](https://linux-hardware.org/?probe=8633bc5aa5) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [2980681052](https://linux-hardware.org/?probe=2980681052) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [aabc0a8aee](https://linux-hardware.org/?probe=aabc0a8aee) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [08b395f8d6](https://linux-hardware.org/?probe=08b395f8d6) | Aug 07, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [3d4073bb1d](https://linux-hardware.org/?probe=3d4073bb1d) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [4dec7b692a](https://linux-hardware.org/?probe=4dec7b692a) | Aug 07, 2023 |
| HUAWEI        | WRTD-WXX9                   | Notebook    | [dc02eefe63](https://linux-hardware.org/?probe=dc02eefe63) | Aug 06, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [1134279f41](https://linux-hardware.org/?probe=1134279f41) | Aug 06, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [c19229d536](https://linux-hardware.org/?probe=c19229d536) | Aug 06, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [eed6ad702b](https://linux-hardware.org/?probe=eed6ad702b) | Aug 06, 2023 |
| Dell          | Inspiron 3520               | Notebook    | [8a3ba73fae](https://linux-hardware.org/?probe=8a3ba73fae) | Aug 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [c3df1aaae9](https://linux-hardware.org/?probe=c3df1aaae9) | Aug 06, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [8218626de4](https://linux-hardware.org/?probe=8218626de4) | Aug 06, 2023 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [572f537532](https://linux-hardware.org/?probe=572f537532) | Aug 06, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [c003e20331](https://linux-hardware.org/?probe=c003e20331) | Aug 06, 2023 |
| Lenovo        | ThinkPad T460 20FN002JUS    | Notebook    | [e71ac5ca78](https://linux-hardware.org/?probe=e71ac5ca78) | Aug 06, 2023 |
| Lenovo        | ThinkPad T560 20FJS18V00    | Notebook    | [27d1d39b58](https://linux-hardware.org/?probe=27d1d39b58) | Aug 06, 2023 |
| ASRock        | X470 Taichi                 | Desktop     | [f9d29dca0d](https://linux-hardware.org/?probe=f9d29dca0d) | Aug 06, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [9fe9cf4748](https://linux-hardware.org/?probe=9fe9cf4748) | Aug 06, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [3dd038d891](https://linux-hardware.org/?probe=3dd038d891) | Aug 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [2771828543](https://linux-hardware.org/?probe=2771828543) | Aug 06, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IAH7 8... | Notebook    | [f77c465da0](https://linux-hardware.org/?probe=f77c465da0) | Aug 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [56c7715a6d](https://linux-hardware.org/?probe=56c7715a6d) | Aug 06, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [6a9e7cc3e2](https://linux-hardware.org/?probe=6a9e7cc3e2) | Aug 06, 2023 |
| RCA           | 038-WT9S10WM02              | Notebook    | [61c1a104d2](https://linux-hardware.org/?probe=61c1a104d2) | Aug 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [932391bfea](https://linux-hardware.org/?probe=932391bfea) | Aug 06, 2023 |
| RCA           | 038-WT9S10WM02              | Notebook    | [fe15934abe](https://linux-hardware.org/?probe=fe15934abe) | Aug 06, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [2e8d48f9bc](https://linux-hardware.org/?probe=2e8d48f9bc) | Aug 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [1b9794e2e3](https://linux-hardware.org/?probe=1b9794e2e3) | Aug 06, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [b47eca38dc](https://linux-hardware.org/?probe=b47eca38dc) | Aug 06, 2023 |
| COMPUMAX C... | MOBIL                       | Notebook    | [60293c1ac3](https://linux-hardware.org/?probe=60293c1ac3) | Aug 06, 2023 |
| Mini PC       | Rev JSL5 DDR4               | Mini pc     | [fed729f0aa](https://linux-hardware.org/?probe=fed729f0aa) | Aug 05, 2023 |
| Acer          | Aspire A715-72G             | Notebook    | [4afe306798](https://linux-hardware.org/?probe=4afe306798) | Aug 05, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8add0a69cc](https://linux-hardware.org/?probe=8add0a69cc) | Aug 05, 2023 |
| Dell          | Venue 8 Pro 5855            | Notebook    | [146fa40942](https://linux-hardware.org/?probe=146fa40942) | Aug 05, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [6af70944d8](https://linux-hardware.org/?probe=6af70944d8) | Aug 05, 2023 |
| Gateway       | SX2185                      | Desktop     | [a6df16b355](https://linux-hardware.org/?probe=a6df16b355) | Aug 05, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [1790fa9d72](https://linux-hardware.org/?probe=1790fa9d72) | Aug 05, 2023 |
| ASUSTek       | ROG Strix G731GU_GL731GU    | Notebook    | [b3c77ee42f](https://linux-hardware.org/?probe=b3c77ee42f) | Aug 05, 2023 |
| Dell          | Latitude E6230              | Notebook    | [cc78868322](https://linux-hardware.org/?probe=cc78868322) | Aug 05, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [4c1ef04fe9](https://linux-hardware.org/?probe=4c1ef04fe9) | Aug 05, 2023 |
| Multilaser    | PC13X                       | Notebook    | [2f79cffddd](https://linux-hardware.org/?probe=2f79cffddd) | Aug 05, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [ea70e92c9a](https://linux-hardware.org/?probe=ea70e92c9a) | Aug 05, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [40bc2f506a](https://linux-hardware.org/?probe=40bc2f506a) | Aug 05, 2023 |
| Dell          | Latitude E6220              | Notebook    | [636392b4bf](https://linux-hardware.org/?probe=636392b4bf) | Aug 05, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [abb19010d2](https://linux-hardware.org/?probe=abb19010d2) | Aug 05, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [87fc943eb1](https://linux-hardware.org/?probe=87fc943eb1) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [d2d45c853b](https://linux-hardware.org/?probe=d2d45c853b) | Aug 05, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f18b2ff744](https://linux-hardware.org/?probe=f18b2ff744) | Aug 05, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [364b15d850](https://linux-hardware.org/?probe=364b15d850) | Aug 05, 2023 |
| System76      | Darter Pro                  | Notebook    | [55a328cd9a](https://linux-hardware.org/?probe=55a328cd9a) | Aug 05, 2023 |
| Intel         | B75                         | Desktop     | [9411dd987c](https://linux-hardware.org/?probe=9411dd987c) | Aug 05, 2023 |
| ASUSTek       | PHOENIX                     | Desktop     | [193262b7ea](https://linux-hardware.org/?probe=193262b7ea) | Aug 05, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [5dc4c594ea](https://linux-hardware.org/?probe=5dc4c594ea) | Aug 05, 2023 |
| Corsair       | Voyager a1600               | Notebook    | [6dea5f2c0c](https://linux-hardware.org/?probe=6dea5f2c0c) | Aug 04, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [ccbf514dc7](https://linux-hardware.org/?probe=ccbf514dc7) | Aug 04, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [e6e6cc7b2e](https://linux-hardware.org/?probe=e6e6cc7b2e) | Aug 04, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [9a4f9f590c](https://linux-hardware.org/?probe=9a4f9f590c) | Aug 04, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [7bc7a7e01c](https://linux-hardware.org/?probe=7bc7a7e01c) | Aug 04, 2023 |
| MSI           | PRO H610M-G WIFI DDR4       | Desktop     | [d8b172537e](https://linux-hardware.org/?probe=d8b172537e) | Aug 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [fcc05278d6](https://linux-hardware.org/?probe=fcc05278d6) | Aug 04, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [b8fa3962ed](https://linux-hardware.org/?probe=b8fa3962ed) | Aug 04, 2023 |
| Acer          | Swift SF114-34              | Notebook    | [2af2b0aecb](https://linux-hardware.org/?probe=2af2b0aecb) | Aug 04, 2023 |
| Dell          | Latitude 7400               | Notebook    | [48e2858e56](https://linux-hardware.org/?probe=48e2858e56) | Aug 04, 2023 |
| Lenovo        | 32DD SDK0J40697 WIN 3305... | Mini pc     | [a894ae9bfc](https://linux-hardware.org/?probe=a894ae9bfc) | Aug 04, 2023 |
| Dell          | Latitude 3420               | Notebook    | [cdecb64c4a](https://linux-hardware.org/?probe=cdecb64c4a) | Aug 04, 2023 |
| AZW           | GTR V02                     | Desktop     | [b2afc2c53e](https://linux-hardware.org/?probe=b2afc2c53e) | Aug 04, 2023 |
| Dell          | 0CRWCR A01                  | All in one  | [16511212ba](https://linux-hardware.org/?probe=16511212ba) | Aug 04, 2023 |
| Gigabyte      | GA-MA785G-UD3H              | Desktop     | [a02f0405a3](https://linux-hardware.org/?probe=a02f0405a3) | Aug 04, 2023 |
| Dell          | Latitude 7440               | Notebook    | [195716ccf3](https://linux-hardware.org/?probe=195716ccf3) | Aug 04, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [de1c7d119e](https://linux-hardware.org/?probe=de1c7d119e) | Aug 04, 2023 |
| Dell          | Latitude 5480               | Notebook    | [b682f988e8](https://linux-hardware.org/?probe=b682f988e8) | Aug 04, 2023 |
| Dell          | Latitude 7440               | Notebook    | [5a9a057759](https://linux-hardware.org/?probe=5a9a057759) | Aug 04, 2023 |
| Dell          | Latitude 7440               | Notebook    | [367f14eae6](https://linux-hardware.org/?probe=367f14eae6) | Aug 04, 2023 |
| HP            | ENVY Notebook               | Notebook    | [90325282da](https://linux-hardware.org/?probe=90325282da) | Aug 04, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [082f92da07](https://linux-hardware.org/?probe=082f92da07) | Aug 04, 2023 |
| HP            | ENVY Laptop 16-h0xxx        | Notebook    | [1078db460a](https://linux-hardware.org/?probe=1078db460a) | Aug 04, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [4077d11575](https://linux-hardware.org/?probe=4077d11575) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [a260479012](https://linux-hardware.org/?probe=a260479012) | Aug 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3c3d90d709](https://linux-hardware.org/?probe=3c3d90d709) | Aug 04, 2023 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [8f3b8dea26](https://linux-hardware.org/?probe=8f3b8dea26) | Aug 04, 2023 |
| ASUSTek       | UX490UAR                    | Notebook    | [6a305978e3](https://linux-hardware.org/?probe=6a305978e3) | Aug 03, 2023 |
| Dell          | Latitude E6510              | Notebook    | [b32213c71d](https://linux-hardware.org/?probe=b32213c71d) | Aug 03, 2023 |
| HP            | ENVY Laptop 16-h1xxx        | Notebook    | [ca0d3636a5](https://linux-hardware.org/?probe=ca0d3636a5) | Aug 03, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [c0a4bb6c7e](https://linux-hardware.org/?probe=c0a4bb6c7e) | Aug 03, 2023 |
| HP            | ENVY Laptop 16-h1xxx        | Notebook    | [3552dd7642](https://linux-hardware.org/?probe=3552dd7642) | Aug 03, 2023 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [aa6b646b24](https://linux-hardware.org/?probe=aa6b646b24) | Aug 03, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [620397fdc9](https://linux-hardware.org/?probe=620397fdc9) | Aug 03, 2023 |
| HP            | 1791                        | Desktop     | [61285d3724](https://linux-hardware.org/?probe=61285d3724) | Aug 03, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Notebook    | [882d963e19](https://linux-hardware.org/?probe=882d963e19) | Aug 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E3S... | Notebook    | [0cf8e99478](https://linux-hardware.org/?probe=0cf8e99478) | Aug 03, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [2d10ecdff1](https://linux-hardware.org/?probe=2d10ecdff1) | Aug 03, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [80498caa0d](https://linux-hardware.org/?probe=80498caa0d) | Aug 03, 2023 |
| Microsoft     | Surface Pro 7+              | Tablet      | [1a39b68c7f](https://linux-hardware.org/?probe=1a39b68c7f) | Aug 03, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Notebook    | [38d0bcf5d1](https://linux-hardware.org/?probe=38d0bcf5d1) | Aug 03, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [e066712070](https://linux-hardware.org/?probe=e066712070) | Aug 03, 2023 |
| Lenovo        | ThinkPad T450 20BU000QLM    | Notebook    | [610fdfd850](https://linux-hardware.org/?probe=610fdfd850) | Aug 03, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [7d96f87e00](https://linux-hardware.org/?probe=7d96f87e00) | Aug 03, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [a956adcb38](https://linux-hardware.org/?probe=a956adcb38) | Aug 03, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [219278bb56](https://linux-hardware.org/?probe=219278bb56) | Aug 03, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [c741db51a0](https://linux-hardware.org/?probe=c741db51a0) | Aug 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [7df997ee08](https://linux-hardware.org/?probe=7df997ee08) | Aug 03, 2023 |
| Lenovo        | ThinkPad X240 20AMS1RR0D    | Notebook    | [dcf2bedb58](https://linux-hardware.org/?probe=dcf2bedb58) | Aug 03, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [6478fd4e76](https://linux-hardware.org/?probe=6478fd4e76) | Aug 03, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [a449d60316](https://linux-hardware.org/?probe=a449d60316) | Aug 03, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [25dcc9a7c5](https://linux-hardware.org/?probe=25dcc9a7c5) | Aug 03, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [3f5df1b569](https://linux-hardware.org/?probe=3f5df1b569) | Aug 03, 2023 |
| Dell          | Latitude E7470              | Notebook    | [7c8c07214a](https://linux-hardware.org/?probe=7c8c07214a) | Aug 03, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [877d855f27](https://linux-hardware.org/?probe=877d855f27) | Aug 02, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [fa53c99b17](https://linux-hardware.org/?probe=fa53c99b17) | Aug 02, 2023 |
| Dell          | Latitude E7470              | Notebook    | [b672c65f9b](https://linux-hardware.org/?probe=b672c65f9b) | Aug 02, 2023 |
| Acer          | Aspire A715-72G             | Notebook    | [d0bad7993f](https://linux-hardware.org/?probe=d0bad7993f) | Aug 02, 2023 |
| ASRock        | Z170 Gaming K4              | Desktop     | [2c10cb0378](https://linux-hardware.org/?probe=2c10cb0378) | Aug 02, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c66b1ed22c](https://linux-hardware.org/?probe=c66b1ed22c) | Aug 02, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [0e3cacbea1](https://linux-hardware.org/?probe=0e3cacbea1) | Aug 02, 2023 |
| MSI           | B560M PRO-E                 | Desktop     | [b10154befd](https://linux-hardware.org/?probe=b10154befd) | Aug 02, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [883a115efd](https://linux-hardware.org/?probe=883a115efd) | Aug 02, 2023 |
| Dell          | System XPS L322X            | Notebook    | [dbe168d1a1](https://linux-hardware.org/?probe=dbe168d1a1) | Aug 02, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [2d1e78ec7e](https://linux-hardware.org/?probe=2d1e78ec7e) | Aug 02, 2023 |
| ASUSTek       | X750JN                      | Notebook    | [6f7dc2198b](https://linux-hardware.org/?probe=6f7dc2198b) | Aug 02, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14IHU5 O... | Notebook    | [491aec1ea1](https://linux-hardware.org/?probe=491aec1ea1) | Aug 02, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [517b498a25](https://linux-hardware.org/?probe=517b498a25) | Aug 02, 2023 |
| HUAWEI        | WRTD-WXX9                   | Notebook    | [18396303b8](https://linux-hardware.org/?probe=18396303b8) | Aug 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [5bbfe225b6](https://linux-hardware.org/?probe=5bbfe225b6) | Aug 02, 2023 |
| ASUSTek       | ROG Maximus XII APEX        | Desktop     | [b8a5aee838](https://linux-hardware.org/?probe=b8a5aee838) | Aug 02, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [2ff30156cf](https://linux-hardware.org/?probe=2ff30156cf) | Aug 02, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [8c9bca1e79](https://linux-hardware.org/?probe=8c9bca1e79) | Aug 02, 2023 |
| Dell          | XPS 9320                    | Notebook    | [3abc4aaf82](https://linux-hardware.org/?probe=3abc4aaf82) | Aug 02, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [f37f2f707b](https://linux-hardware.org/?probe=f37f2f707b) | Aug 02, 2023 |
| HP            | Dragonfly Pro               | Notebook    | [630670f052](https://linux-hardware.org/?probe=630670f052) | Aug 01, 2023 |
| Dell          | Precision 7550              | Notebook    | [ab0d21bb4e](https://linux-hardware.org/?probe=ab0d21bb4e) | Aug 01, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [2d7cbca56b](https://linux-hardware.org/?probe=2d7cbca56b) | Aug 01, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [8353d48977](https://linux-hardware.org/?probe=8353d48977) | Aug 01, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [abe7173905](https://linux-hardware.org/?probe=abe7173905) | Aug 01, 2023 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [13d25503d7](https://linux-hardware.org/?probe=13d25503d7) | Aug 01, 2023 |
| Dell          | Inspiron 15-3573            | Notebook    | [e29b3656ee](https://linux-hardware.org/?probe=e29b3656ee) | Aug 01, 2023 |
| HP            | ProBook 6475b               | Notebook    | [c3cfc235fe](https://linux-hardware.org/?probe=c3cfc235fe) | Aug 01, 2023 |
| ASRock        | H61M/U3S3                   | Desktop     | [33c887e577](https://linux-hardware.org/?probe=33c887e577) | Aug 01, 2023 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [752821ae1a](https://linux-hardware.org/?probe=752821ae1a) | Aug 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [7a5ef06c39](https://linux-hardware.org/?probe=7a5ef06c39) | Aug 01, 2023 |
| Lenovo        | Yoga 720-13IKB 81C3         | Convertible | [287ea63732](https://linux-hardware.org/?probe=287ea63732) | Aug 01, 2023 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [b847ac4535](https://linux-hardware.org/?probe=b847ac4535) | Aug 01, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [41cc0d3bfc](https://linux-hardware.org/?probe=41cc0d3bfc) | Aug 01, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [70b94de26b](https://linux-hardware.org/?probe=70b94de26b) | Jul 31, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [afbf5d75c1](https://linux-hardware.org/?probe=afbf5d75c1) | Jul 31, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [1dfc12fc6c](https://linux-hardware.org/?probe=1dfc12fc6c) | Jul 31, 2023 |
| ASRock        | H110M-HG4                   | Desktop     | [7584e2db20](https://linux-hardware.org/?probe=7584e2db20) | Jul 31, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [df2a633f24](https://linux-hardware.org/?probe=df2a633f24) | Jul 31, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [a7cf8e8ef1](https://linux-hardware.org/?probe=a7cf8e8ef1) | Jul 31, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [9b9830aedf](https://linux-hardware.org/?probe=9b9830aedf) | Jul 31, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [b42946849e](https://linux-hardware.org/?probe=b42946849e) | Jul 31, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [49a431c092](https://linux-hardware.org/?probe=49a431c092) | Jul 31, 2023 |
| MSI           | GE75 Raider 10SE            | Notebook    | [995b9ae73e](https://linux-hardware.org/?probe=995b9ae73e) | Jul 31, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [a3bbf1ecd0](https://linux-hardware.org/?probe=a3bbf1ecd0) | Jul 31, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [08e20bb994](https://linux-hardware.org/?probe=08e20bb994) | Jul 31, 2023 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [bb88f3afdc](https://linux-hardware.org/?probe=bb88f3afdc) | Jul 31, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [7890c76098](https://linux-hardware.org/?probe=7890c76098) | Jul 31, 2023 |
| Lenovo        | ThinkPad P50 20EQS20D00     | Notebook    | [4ef8aa09c6](https://linux-hardware.org/?probe=4ef8aa09c6) | Jul 31, 2023 |
| HP            | ProBook 440 G3              | Notebook    | [beea8be008](https://linux-hardware.org/?probe=beea8be008) | Jul 30, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [9a3416654f](https://linux-hardware.org/?probe=9a3416654f) | Jul 30, 2023 |
| HP            | 8056                        | Desktop     | [3a98a11778](https://linux-hardware.org/?probe=3a98a11778) | Jul 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [5bf8462b77](https://linux-hardware.org/?probe=5bf8462b77) | Jul 30, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [5ce91f2c11](https://linux-hardware.org/?probe=5ce91f2c11) | Jul 30, 2023 |
| HP            | 0AECh D                     | Desktop     | [50c84d005e](https://linux-hardware.org/?probe=50c84d005e) | Jul 30, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [6bf2e91f31](https://linux-hardware.org/?probe=6bf2e91f31) | Jul 30, 2023 |
| HP            | Pavilion 15                 | Notebook    | [7dcc58cdf2](https://linux-hardware.org/?probe=7dcc58cdf2) | Jul 30, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [0f9accc3e8](https://linux-hardware.org/?probe=0f9accc3e8) | Jul 30, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [f641b9c622](https://linux-hardware.org/?probe=f641b9c622) | Jul 30, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [63b8471789](https://linux-hardware.org/?probe=63b8471789) | Jul 30, 2023 |
| Lenovo        | WEI6 15 ITL 82F2            | Notebook    | [d30f44ebbb](https://linux-hardware.org/?probe=d30f44ebbb) | Jul 30, 2023 |
| ASUSTek       | P552LA                      | Notebook    | [d84e6d9683](https://linux-hardware.org/?probe=d84e6d9683) | Jul 30, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [d9d3f5bce4](https://linux-hardware.org/?probe=d9d3f5bce4) | Jul 30, 2023 |
| Sony          | SVE14A2V2RS                 | Notebook    | [adc151e590](https://linux-hardware.org/?probe=adc151e590) | Jul 30, 2023 |
| Intel         | NUC13ANBi5 M89647-202       | Mini pc     | [8e59554b8d](https://linux-hardware.org/?probe=8e59554b8d) | Jul 30, 2023 |
| Dell          | Inspiron M5010              | Notebook    | [8608f29a0f](https://linux-hardware.org/?probe=8608f29a0f) | Jul 30, 2023 |
| HP            | 8617                        | Desktop     | [0c3ee28cd8](https://linux-hardware.org/?probe=0c3ee28cd8) | Jul 30, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [6c5528a787](https://linux-hardware.org/?probe=6c5528a787) | Jul 30, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [4fb6a46f65](https://linux-hardware.org/?probe=4fb6a46f65) | Jul 30, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [529bf65ac4](https://linux-hardware.org/?probe=529bf65ac4) | Jul 30, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [df34eb4472](https://linux-hardware.org/?probe=df34eb4472) | Jul 30, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [f5cc7a2d00](https://linux-hardware.org/?probe=f5cc7a2d00) | Jul 30, 2023 |
| ASRock        | X570 Phantom Gaming X       | Desktop     | [0449350f3d](https://linux-hardware.org/?probe=0449350f3d) | Jul 30, 2023 |
| HP            | ENVY Laptop 17-cg1xxx       | Notebook    | [16545b3964](https://linux-hardware.org/?probe=16545b3964) | Jul 30, 2023 |
| Lenovo        | ThinkPad T490 20N3S5XF01    | Notebook    | [942cb3149b](https://linux-hardware.org/?probe=942cb3149b) | Jul 29, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [9469c1037c](https://linux-hardware.org/?probe=9469c1037c) | Jul 29, 2023 |
| ASUSTek       | M4A89TD PRO USB3            | Desktop     | [bcfe09b617](https://linux-hardware.org/?probe=bcfe09b617) | Jul 29, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [cd073a7899](https://linux-hardware.org/?probe=cd073a7899) | Jul 29, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [10b634ac99](https://linux-hardware.org/?probe=10b634ac99) | Jul 29, 2023 |
| HP            | Beats 15                    | Notebook    | [933bd63249](https://linux-hardware.org/?probe=933bd63249) | Jul 29, 2023 |
| HP            | Beats 15                    | Notebook    | [acea7d6786](https://linux-hardware.org/?probe=acea7d6786) | Jul 29, 2023 |
| HP            | 3397                        | Desktop     | [98e4e362d9](https://linux-hardware.org/?probe=98e4e362d9) | Jul 29, 2023 |
| Lenovo        | ThinkPad T490 20N20031US    | Notebook    | [64e178e433](https://linux-hardware.org/?probe=64e178e433) | Jul 29, 2023 |
| HP            | 470 17 inch G9 Notebook ... | Notebook    | [dbcda8f4d0](https://linux-hardware.org/?probe=dbcda8f4d0) | Jul 29, 2023 |
| Lenovo        | Unknown                     | Notebook    | [a1dac68b95](https://linux-hardware.org/?probe=a1dac68b95) | Jul 29, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [32ad81bc5d](https://linux-hardware.org/?probe=32ad81bc5d) | Jul 29, 2023 |
| Lenovo        | Yoga 7 14ARP8 82YM          | Convertible | [4baa3fe63b](https://linux-hardware.org/?probe=4baa3fe63b) | Jul 29, 2023 |
| Lenovo        | Yoga 7 14ARP8 82YM          | Convertible | [254354d9aa](https://linux-hardware.org/?probe=254354d9aa) | Jul 29, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [95e189ee7a](https://linux-hardware.org/?probe=95e189ee7a) | Jul 29, 2023 |
| ECS           | H61H2-M17                   | Desktop     | [360623689a](https://linux-hardware.org/?probe=360623689a) | Jul 29, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [9669adfa57](https://linux-hardware.org/?probe=9669adfa57) | Jul 29, 2023 |
| ECS           | H61H2-M17                   | Desktop     | [aa0f0813e4](https://linux-hardware.org/?probe=aa0f0813e4) | Jul 29, 2023 |
| HP            | ProBook 4530s               | Notebook    | [884d64edd7](https://linux-hardware.org/?probe=884d64edd7) | Jul 29, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [580c4fb755](https://linux-hardware.org/?probe=580c4fb755) | Jul 29, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [733695ae93](https://linux-hardware.org/?probe=733695ae93) | Jul 29, 2023 |
| Samsung       | 550XDA                      | Notebook    | [c140c9176e](https://linux-hardware.org/?probe=c140c9176e) | Jul 29, 2023 |
| MSI           | A320M PRO-VH                | Desktop     | [0728a96775](https://linux-hardware.org/?probe=0728a96775) | Jul 29, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [dd2b310ecf](https://linux-hardware.org/?probe=dd2b310ecf) | Jul 29, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [b8e059a47d](https://linux-hardware.org/?probe=b8e059a47d) | Jul 29, 2023 |
| GPD           | G1621-02                    | Notebook    | [1710e0f480](https://linux-hardware.org/?probe=1710e0f480) | Jul 29, 2023 |
| Dell          | XPS 9320                    | Notebook    | [4000df5584](https://linux-hardware.org/?probe=4000df5584) | Jul 29, 2023 |
| Dell          | Latitude 5400               | Notebook    | [9416ce803c](https://linux-hardware.org/?probe=9416ce803c) | Jul 28, 2023 |
| Microsoft     | Surface Pro 8               | Tablet      | [21aa433472](https://linux-hardware.org/?probe=21aa433472) | Jul 28, 2023 |
| Gigabyte      | B460M DS3H AC V2-Y1         | Notebook    | [75e93aaa88](https://linux-hardware.org/?probe=75e93aaa88) | Jul 28, 2023 |
| ASRock        | H110M-HG4                   | Desktop     | [205f3a047f](https://linux-hardware.org/?probe=205f3a047f) | Jul 28, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [dcd24dfdc7](https://linux-hardware.org/?probe=dcd24dfdc7) | Jul 28, 2023 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [ea4fee91b6](https://linux-hardware.org/?probe=ea4fee91b6) | Jul 28, 2023 |
| Gigabyte      | B460M DS3H AC V2-Y1         | Notebook    | [730caebd96](https://linux-hardware.org/?probe=730caebd96) | Jul 28, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fa1452d305](https://linux-hardware.org/?probe=fa1452d305) | Jul 28, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [1c3edafdf4](https://linux-hardware.org/?probe=1c3edafdf4) | Jul 28, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [ba7c69f7e0](https://linux-hardware.org/?probe=ba7c69f7e0) | Jul 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [2e6ab71954](https://linux-hardware.org/?probe=2e6ab71954) | Jul 28, 2023 |
| ASUSTek       | WS C246 PRO                 | Desktop     | [cfffc2ba92](https://linux-hardware.org/?probe=cfffc2ba92) | Jul 28, 2023 |
| Lenovo        | ThinkPad Z16 Gen 1 21D4C... | Notebook    | [4439f26a90](https://linux-hardware.org/?probe=4439f26a90) | Jul 28, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [2e0e88694a](https://linux-hardware.org/?probe=2e0e88694a) | Jul 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [f5497a92cf](https://linux-hardware.org/?probe=f5497a92cf) | Jul 28, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [7864dbf54c](https://linux-hardware.org/?probe=7864dbf54c) | Jul 28, 2023 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [f7c6565b62](https://linux-hardware.org/?probe=f7c6565b62) | Jul 28, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [49daa98623](https://linux-hardware.org/?probe=49daa98623) | Jul 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [058f75de84](https://linux-hardware.org/?probe=058f75de84) | Jul 28, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [c26daef72c](https://linux-hardware.org/?probe=c26daef72c) | Jul 28, 2023 |
| MSI           | Z270 GAMING PLUS            | Desktop     | [cc489fad92](https://linux-hardware.org/?probe=cc489fad92) | Jul 28, 2023 |
| ASUSTek       | P9D-I Series                | Server      | [b8af713f2c](https://linux-hardware.org/?probe=b8af713f2c) | Jul 28, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [b784cbe3ab](https://linux-hardware.org/?probe=b784cbe3ab) | Jul 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [4bd819d37b](https://linux-hardware.org/?probe=4bd819d37b) | Jul 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e46fa3639e](https://linux-hardware.org/?probe=e46fa3639e) | Jul 27, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [6287e66ff2](https://linux-hardware.org/?probe=6287e66ff2) | Jul 27, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [da2904da80](https://linux-hardware.org/?probe=da2904da80) | Jul 27, 2023 |
| Lenovo        | ThinkPad E490 20N80029RT    | Notebook    | [69cf27eaae](https://linux-hardware.org/?probe=69cf27eaae) | Jul 27, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [abf0e5979c](https://linux-hardware.org/?probe=abf0e5979c) | Jul 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [1b3e699a2a](https://linux-hardware.org/?probe=1b3e699a2a) | Jul 27, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [2c2dfaa670](https://linux-hardware.org/?probe=2c2dfaa670) | Jul 27, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [865315bd06](https://linux-hardware.org/?probe=865315bd06) | Jul 27, 2023 |
| Dell          | Latitude 5530               | Notebook    | [165d2cd3b1](https://linux-hardware.org/?probe=165d2cd3b1) | Jul 27, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [56489a32b2](https://linux-hardware.org/?probe=56489a32b2) | Jul 27, 2023 |
| ASUSTek       | PHOENIX                     | Desktop     | [aad7b03818](https://linux-hardware.org/?probe=aad7b03818) | Jul 27, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [02cf19407b](https://linux-hardware.org/?probe=02cf19407b) | Jul 26, 2023 |
| HP            | 829A                        | Mini pc     | [c78cd4ea03](https://linux-hardware.org/?probe=c78cd4ea03) | Jul 26, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [32b57e4adb](https://linux-hardware.org/?probe=32b57e4adb) | Jul 26, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [87d69792fb](https://linux-hardware.org/?probe=87d69792fb) | Jul 26, 2023 |
| Dell          | Latitude E6400              | Notebook    | [a9333607eb](https://linux-hardware.org/?probe=a9333607eb) | Jul 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [b8b95820c1](https://linux-hardware.org/?probe=b8b95820c1) | Jul 26, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [aed4f431ec](https://linux-hardware.org/?probe=aed4f431ec) | Jul 26, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [8daa291377](https://linux-hardware.org/?probe=8daa291377) | Jul 26, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [83097985a2](https://linux-hardware.org/?probe=83097985a2) | Jul 26, 2023 |
| Dell          | Vostro 15 5510              | Notebook    | [2e810b1c93](https://linux-hardware.org/?probe=2e810b1c93) | Jul 26, 2023 |
| Dell          | Vostro 15 5510              | Notebook    | [4171fc8925](https://linux-hardware.org/?probe=4171fc8925) | Jul 26, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [f375185ce4](https://linux-hardware.org/?probe=f375185ce4) | Jul 26, 2023 |
| Dell          | Latitude E7440              | Notebook    | [9b8234d640](https://linux-hardware.org/?probe=9b8234d640) | Jul 26, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [9b1ae569c1](https://linux-hardware.org/?probe=9b1ae569c1) | Jul 26, 2023 |
| Dell          | Inspiron 13 5310            | Notebook    | [5f44d0b1d8](https://linux-hardware.org/?probe=5f44d0b1d8) | Jul 26, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [30cb22d368](https://linux-hardware.org/?probe=30cb22d368) | Jul 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [f321614376](https://linux-hardware.org/?probe=f321614376) | Jul 25, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [b731684f10](https://linux-hardware.org/?probe=b731684f10) | Jul 25, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [b28bc4ba91](https://linux-hardware.org/?probe=b28bc4ba91) | Jul 25, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [067a1b82b7](https://linux-hardware.org/?probe=067a1b82b7) | Jul 25, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [62bcc903fd](https://linux-hardware.org/?probe=62bcc903fd) | Jul 25, 2023 |
| Intel         | NUC5i5MYBE H47797-206       | Mini pc     | [393855b913](https://linux-hardware.org/?probe=393855b913) | Jul 25, 2023 |
| HP            | 871C                        | All in one  | [4ebf5aee4d](https://linux-hardware.org/?probe=4ebf5aee4d) | Jul 25, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [0059745bdf](https://linux-hardware.org/?probe=0059745bdf) | Jul 25, 2023 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | Notebook    | [90beff8e65](https://linux-hardware.org/?probe=90beff8e65) | Jul 25, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [bd31324aeb](https://linux-hardware.org/?probe=bd31324aeb) | Jul 25, 2023 |
| Gigabyte      | B365M H                     | Desktop     | [12902831a7](https://linux-hardware.org/?probe=12902831a7) | Jul 25, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [31b7924358](https://linux-hardware.org/?probe=31b7924358) | Jul 25, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [da046587dc](https://linux-hardware.org/?probe=da046587dc) | Jul 25, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [8cf3728f9b](https://linux-hardware.org/?probe=8cf3728f9b) | Jul 25, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [a4e9cddcdb](https://linux-hardware.org/?probe=a4e9cddcdb) | Jul 25, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [0ecaae8a05](https://linux-hardware.org/?probe=0ecaae8a05) | Jul 25, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [7ee6422d01](https://linux-hardware.org/?probe=7ee6422d01) | Jul 25, 2023 |
| Unknown       | Unknown                     | Desktop     | [a7d120e20a](https://linux-hardware.org/?probe=a7d120e20a) | Jul 24, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [c49c2e7a5a](https://linux-hardware.org/?probe=c49c2e7a5a) | Jul 24, 2023 |
| ASUSTek       | PHOENIX                     | Desktop     | [66ab03991c](https://linux-hardware.org/?probe=66ab03991c) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [53de15710b](https://linux-hardware.org/?probe=53de15710b) | Jul 24, 2023 |
| Fujitsu       | CELSIUS H700                | Notebook    | [8a23e1d76a](https://linux-hardware.org/?probe=8a23e1d76a) | Jul 24, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [61646d77f1](https://linux-hardware.org/?probe=61646d77f1) | Jul 24, 2023 |
| MSI           | Summit E16Flip A12UCT       | Notebook    | [daf09efe6e](https://linux-hardware.org/?probe=daf09efe6e) | Jul 24, 2023 |
| ASUSTek       | ROG Flow X16 GV601RM_GV6... | Convertible | [3086b1ce57](https://linux-hardware.org/?probe=3086b1ce57) | Jul 24, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [fbfa8af465](https://linux-hardware.org/?probe=fbfa8af465) | Jul 24, 2023 |
| Acer          | Aspire A315-59              | Notebook    | [8ecb2eb1fc](https://linux-hardware.org/?probe=8ecb2eb1fc) | Jul 24, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [84c7ea08c6](https://linux-hardware.org/?probe=84c7ea08c6) | Jul 24, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [60b9e2fbc9](https://linux-hardware.org/?probe=60b9e2fbc9) | Jul 24, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [b892c011a8](https://linux-hardware.org/?probe=b892c011a8) | Jul 24, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [4f06d87bd5](https://linux-hardware.org/?probe=4f06d87bd5) | Jul 24, 2023 |
| ASRock        | Z690 Pro RS                 | Desktop     | [2afa2c2afe](https://linux-hardware.org/?probe=2afa2c2afe) | Jul 23, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [95290b34e3](https://linux-hardware.org/?probe=95290b34e3) | Jul 23, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [e1f3c75353](https://linux-hardware.org/?probe=e1f3c75353) | Jul 23, 2023 |
| Dell          | 0YGR09 A00                  | All in one  | [256d182fcd](https://linux-hardware.org/?probe=256d182fcd) | Jul 23, 2023 |
| MSI           | Z170A SLI PLUS              | Desktop     | [a3ccd7aece](https://linux-hardware.org/?probe=a3ccd7aece) | Jul 23, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [04982390e0](https://linux-hardware.org/?probe=04982390e0) | Jul 23, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [b13bb2310f](https://linux-hardware.org/?probe=b13bb2310f) | Jul 23, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [82a4cfcd9f](https://linux-hardware.org/?probe=82a4cfcd9f) | Jul 23, 2023 |
| ASUSTek       | H170M-PLUS                  | Notebook    | [f17fd3bbe1](https://linux-hardware.org/?probe=f17fd3bbe1) | Jul 23, 2023 |
| HP            | 250 G1                      | Notebook    | [deab96c404](https://linux-hardware.org/?probe=deab96c404) | Jul 23, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | Notebook    | [ff5e295a5d](https://linux-hardware.org/?probe=ff5e295a5d) | Jul 23, 2023 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [09b55ea163](https://linux-hardware.org/?probe=09b55ea163) | Jul 23, 2023 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [95b700531a](https://linux-hardware.org/?probe=95b700531a) | Jul 23, 2023 |
| Gigabyte      | H61MS                       | Desktop     | [545d840e2f](https://linux-hardware.org/?probe=545d840e2f) | Jul 23, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [9a2136d9ef](https://linux-hardware.org/?probe=9a2136d9ef) | Jul 23, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [6c0c0671df](https://linux-hardware.org/?probe=6c0c0671df) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [28340d4ad4](https://linux-hardware.org/?probe=28340d4ad4) | Jul 23, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [6323d6b43c](https://linux-hardware.org/?probe=6323d6b43c) | Jul 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [49cc99fa7e](https://linux-hardware.org/?probe=49cc99fa7e) | Jul 23, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [994ae7ffec](https://linux-hardware.org/?probe=994ae7ffec) | Jul 23, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [9c92b34677](https://linux-hardware.org/?probe=9c92b34677) | Jul 23, 2023 |
| Gigabyte      | B360M D2V                   | Desktop     | [eef08e2598](https://linux-hardware.org/?probe=eef08e2598) | Jul 22, 2023 |
| Lenovo        | Legion 5 15IMH6 82NL        | Notebook    | [f12c3b23e5](https://linux-hardware.org/?probe=f12c3b23e5) | Jul 22, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [3ed87bb81b](https://linux-hardware.org/?probe=3ed87bb81b) | Jul 22, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [b957598d8e](https://linux-hardware.org/?probe=b957598d8e) | Jul 22, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [ea078c7fb9](https://linux-hardware.org/?probe=ea078c7fb9) | Jul 22, 2023 |
| ZOTAC         | ZBOX-ID88/ID89/ID90         | Mini pc     | [8c75932124](https://linux-hardware.org/?probe=8c75932124) | Jul 22, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [51ca7593a6](https://linux-hardware.org/?probe=51ca7593a6) | Jul 22, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20HE... | Notebook    | [e6320dd4ae](https://linux-hardware.org/?probe=e6320dd4ae) | Jul 22, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [931df813b1](https://linux-hardware.org/?probe=931df813b1) | Jul 22, 2023 |
| Dell          | Precision M4700             | Notebook    | [0a5346a25d](https://linux-hardware.org/?probe=0a5346a25d) | Jul 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [ba42ca5ace](https://linux-hardware.org/?probe=ba42ca5ace) | Jul 22, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [ec2be7713c](https://linux-hardware.org/?probe=ec2be7713c) | Jul 22, 2023 |
| HP            | Notebook                    | Notebook    | [fde29b5a32](https://linux-hardware.org/?probe=fde29b5a32) | Jul 22, 2023 |
| Notebook      | PE60RNE_RND_RNC             | Notebook    | [5f2993b629](https://linux-hardware.org/?probe=5f2993b629) | Jul 22, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [c1e386e9cc](https://linux-hardware.org/?probe=c1e386e9cc) | Jul 22, 2023 |
| Kllisre       | X99-B5 V1.1                 | Desktop     | [b132b3f39c](https://linux-hardware.org/?probe=b132b3f39c) | Jul 21, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [8c79a454ff](https://linux-hardware.org/?probe=8c79a454ff) | Jul 21, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21J6... | Notebook    | [27b5dabe8d](https://linux-hardware.org/?probe=27b5dabe8d) | Jul 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [d16a211675](https://linux-hardware.org/?probe=d16a211675) | Jul 21, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [e222d263f6](https://linux-hardware.org/?probe=e222d263f6) | Jul 21, 2023 |
| MACHINIST     | E5-D8-MAX V1.1              | Desktop     | [ea68d9762b](https://linux-hardware.org/?probe=ea68d9762b) | Jul 21, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B      | Soc         | [fbd6b6197b](https://linux-hardware.org/?probe=fbd6b6197b) | Jul 21, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [355ac636c1](https://linux-hardware.org/?probe=355ac636c1) | Jul 21, 2023 |
| Intel         | NUC8BEB J72688-308          | Mini pc     | [0026c9edf0](https://linux-hardware.org/?probe=0026c9edf0) | Jul 21, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [32ec9929c9](https://linux-hardware.org/?probe=32ec9929c9) | Jul 21, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [e8249dc6d6](https://linux-hardware.org/?probe=e8249dc6d6) | Jul 21, 2023 |
| Fujitsu       | D3430-U1 S26361-D3430-U1    | Desktop     | [37132be6bd](https://linux-hardware.org/?probe=37132be6bd) | Jul 21, 2023 |
| Toshiba       | TECRA A50-A                 | Notebook    | [e96ff00334](https://linux-hardware.org/?probe=e96ff00334) | Jul 21, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [fa4def4ece](https://linux-hardware.org/?probe=fa4def4ece) | Jul 21, 2023 |
| Avell High... | B.ON                        | Notebook    | [8269a683ef](https://linux-hardware.org/?probe=8269a683ef) | Jul 21, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [689b191bae](https://linux-hardware.org/?probe=689b191bae) | Jul 21, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [d163198c13](https://linux-hardware.org/?probe=d163198c13) | Jul 21, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [b541d17031](https://linux-hardware.org/?probe=b541d17031) | Jul 21, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [cf2d22469b](https://linux-hardware.org/?probe=cf2d22469b) | Jul 20, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [5224cc55eb](https://linux-hardware.org/?probe=5224cc55eb) | Jul 20, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [df2bfbf3e1](https://linux-hardware.org/?probe=df2bfbf3e1) | Jul 20, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [de8a458cb8](https://linux-hardware.org/?probe=de8a458cb8) | Jul 20, 2023 |
| MSI           | PRO B550-VC                 | Desktop     | [5439295c30](https://linux-hardware.org/?probe=5439295c30) | Jul 20, 2023 |
| Dell          | 00010C A00                  | Desktop     | [71eca6ee4c](https://linux-hardware.org/?probe=71eca6ee4c) | Jul 20, 2023 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | Notebook    | [6bc352838a](https://linux-hardware.org/?probe=6bc352838a) | Jul 20, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [dd441dfa0d](https://linux-hardware.org/?probe=dd441dfa0d) | Jul 20, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [e9c650988e](https://linux-hardware.org/?probe=e9c650988e) | Jul 20, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [a1f316c8c9](https://linux-hardware.org/?probe=a1f316c8c9) | Jul 20, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [18a6e9f055](https://linux-hardware.org/?probe=18a6e9f055) | Jul 20, 2023 |
| ASUSTek       | Zenbook UN5401RA UN5401R... | Convertible | [cfbad825dc](https://linux-hardware.org/?probe=cfbad825dc) | Jul 20, 2023 |
| Lenovo        | Legion 5 15ACH6 82QJ        | Notebook    | [c7e1f17f9e](https://linux-hardware.org/?probe=c7e1f17f9e) | Jul 20, 2023 |
| Apple         | MacBookPro5,5               | Notebook    | [af457a5412](https://linux-hardware.org/?probe=af457a5412) | Jul 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [e99bf7a4be](https://linux-hardware.org/?probe=e99bf7a4be) | Jul 20, 2023 |
| Dell          | Latitude 5420               | Notebook    | [ea97d72c47](https://linux-hardware.org/?probe=ea97d72c47) | Jul 20, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [f92f9065bc](https://linux-hardware.org/?probe=f92f9065bc) | Jul 19, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [fc26baabc9](https://linux-hardware.org/?probe=fc26baabc9) | Jul 19, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [b3a1dbc5d0](https://linux-hardware.org/?probe=b3a1dbc5d0) | Jul 19, 2023 |
| MSI           | Sword 17 A11UD              | Notebook    | [fd2864f7e1](https://linux-hardware.org/?probe=fd2864f7e1) | Jul 19, 2023 |
| Chuwi         | Hi10 X                      | Tablet      | [a2f35813e6](https://linux-hardware.org/?probe=a2f35813e6) | Jul 19, 2023 |
| Lenovo        | ThinkPad 11e 20DAS0C800     | Notebook    | [b894a6d96b](https://linux-hardware.org/?probe=b894a6d96b) | Jul 19, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [38c5f4d547](https://linux-hardware.org/?probe=38c5f4d547) | Jul 19, 2023 |
| Lenovo        | IdeaPad 3 17ALC6 82KV       | Notebook    | [e2cf7ed35f](https://linux-hardware.org/?probe=e2cf7ed35f) | Jul 19, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [22bbaa5937](https://linux-hardware.org/?probe=22bbaa5937) | Jul 19, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [173929b667](https://linux-hardware.org/?probe=173929b667) | Jul 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [360ee7202f](https://linux-hardware.org/?probe=360ee7202f) | Jul 18, 2023 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [ba24f3bb61](https://linux-hardware.org/?probe=ba24f3bb61) | Jul 18, 2023 |
| Dell          | 0MN1TX A01                  | Desktop     | [696072cf7c](https://linux-hardware.org/?probe=696072cf7c) | Jul 18, 2023 |
| HP            | Notebook                    | Notebook    | [4498c757a7](https://linux-hardware.org/?probe=4498c757a7) | Jul 18, 2023 |
| Lenovo        | IdeaPad 130-14IKB 81H6      | Notebook    | [3649d91857](https://linux-hardware.org/?probe=3649d91857) | Jul 18, 2023 |
| LattePanda    | 3 Delta LP-BS-7-S70JR120... | Desktop     | [0296e5fd5c](https://linux-hardware.org/?probe=0296e5fd5c) | Jul 18, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [5d3e13fc77](https://linux-hardware.org/?probe=5d3e13fc77) | Jul 18, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [96585144ab](https://linux-hardware.org/?probe=96585144ab) | Jul 18, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [ea47e53a45](https://linux-hardware.org/?probe=ea47e53a45) | Jul 18, 2023 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [14478a9226](https://linux-hardware.org/?probe=14478a9226) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [3618885533](https://linux-hardware.org/?probe=3618885533) | Jul 18, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [d0fff20fb0](https://linux-hardware.org/?probe=d0fff20fb0) | Jul 18, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [d2c6c9bcba](https://linux-hardware.org/?probe=d2c6c9bcba) | Jul 18, 2023 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [c4ab55ea69](https://linux-hardware.org/?probe=c4ab55ea69) | Jul 18, 2023 |
| ASUSTek       | M11AD                       | Desktop     | [4019d4eb57](https://linux-hardware.org/?probe=4019d4eb57) | Jul 18, 2023 |
| MSI           | IONA                        | Desktop     | [7b8b6c38e1](https://linux-hardware.org/?probe=7b8b6c38e1) | Jul 18, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [bb84df2364](https://linux-hardware.org/?probe=bb84df2364) | Jul 18, 2023 |
| ASRock        | X570M Pro4                  | Desktop     | [b8caf7c9a3](https://linux-hardware.org/?probe=b8caf7c9a3) | Jul 18, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [fe1ab04658](https://linux-hardware.org/?probe=fe1ab04658) | Jul 18, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [e0303e4012](https://linux-hardware.org/?probe=e0303e4012) | Jul 17, 2023 |
| MSI           | Creator 17 A10SE            | Notebook    | [775c65db16](https://linux-hardware.org/?probe=775c65db16) | Jul 17, 2023 |
| HP            | 3048h                       | Desktop     | [ad7b0d8c8d](https://linux-hardware.org/?probe=ad7b0d8c8d) | Jul 17, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [44ac31ab5e](https://linux-hardware.org/?probe=44ac31ab5e) | Jul 17, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [60d7a077dc](https://linux-hardware.org/?probe=60d7a077dc) | Jul 17, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [14defb538e](https://linux-hardware.org/?probe=14defb538e) | Jul 17, 2023 |
| Samsung       | 950XCJ/951XCJ/950XCR        | Notebook    | [3a7fbf07fa](https://linux-hardware.org/?probe=3a7fbf07fa) | Jul 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [2bda9f913a](https://linux-hardware.org/?probe=2bda9f913a) | Jul 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [3de307450d](https://linux-hardware.org/?probe=3de307450d) | Jul 17, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [9d835f25a7](https://linux-hardware.org/?probe=9d835f25a7) | Jul 17, 2023 |
| Lenovo        | ThinkPad T480s 20L8S1R50... | Notebook    | [5633b6ed54](https://linux-hardware.org/?probe=5633b6ed54) | Jul 17, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [62238aaf82](https://linux-hardware.org/?probe=62238aaf82) | Jul 17, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [7284e87529](https://linux-hardware.org/?probe=7284e87529) | Jul 17, 2023 |
| ASRock        | H510M-HDV/M.2               | Desktop     | [4c07b0b74c](https://linux-hardware.org/?probe=4c07b0b74c) | Jul 17, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [49e298a314](https://linux-hardware.org/?probe=49e298a314) | Jul 17, 2023 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [d8595efd58](https://linux-hardware.org/?probe=d8595efd58) | Jul 17, 2023 |
| ASRock        | B450M Pro4 R2.0             | Desktop     | [6039e0f3c4](https://linux-hardware.org/?probe=6039e0f3c4) | Jul 17, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [04dce054f4](https://linux-hardware.org/?probe=04dce054f4) | Jul 17, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [a097322114](https://linux-hardware.org/?probe=a097322114) | Jul 17, 2023 |
| Lenovo        | ThinkPad T430 23426QU       | Notebook    | [9c1cb1fd39](https://linux-hardware.org/?probe=9c1cb1fd39) | Jul 16, 2023 |
| Gigabyte      | AORUS 17 YE5                | Notebook    | [9c17ae5e55](https://linux-hardware.org/?probe=9c17ae5e55) | Jul 16, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [07161141b4](https://linux-hardware.org/?probe=07161141b4) | Jul 16, 2023 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [ec4db25eb9](https://linux-hardware.org/?probe=ec4db25eb9) | Jul 16, 2023 |
| Lenovo        | ThinkPad L380 20M50013UK    | Notebook    | [99b59160a1](https://linux-hardware.org/?probe=99b59160a1) | Jul 16, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [999de9eeb2](https://linux-hardware.org/?probe=999de9eeb2) | Jul 16, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [65afe9f74b](https://linux-hardware.org/?probe=65afe9f74b) | Jul 16, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [46a3598028](https://linux-hardware.org/?probe=46a3598028) | Jul 16, 2023 |
| Lenovo        | ThinkPad X13s Gen 1 21BY... | Notebook    | [1a0f8c842b](https://linux-hardware.org/?probe=1a0f8c842b) | Jul 16, 2023 |
| Fujitsu Si... | LIFEBOOK E8310              | Notebook    | [0093aba5fd](https://linux-hardware.org/?probe=0093aba5fd) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [6b4e2c6a3e](https://linux-hardware.org/?probe=6b4e2c6a3e) | Jul 16, 2023 |
| MSI           | 2A9C                        | Desktop     | [eaaf1d2a5a](https://linux-hardware.org/?probe=eaaf1d2a5a) | Jul 16, 2023 |
| Compaq        | 420                         | Notebook    | [e5b8695df7](https://linux-hardware.org/?probe=e5b8695df7) | Jul 16, 2023 |
| HP            | ProLiant ML110 G7           | Desktop     | [2278b34727](https://linux-hardware.org/?probe=2278b34727) | Jul 16, 2023 |
| MSI           | GE72MVR 7RG                 | Notebook    | [c1834b63c2](https://linux-hardware.org/?probe=c1834b63c2) | Jul 16, 2023 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [5bf40815d5](https://linux-hardware.org/?probe=5bf40815d5) | Jul 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8c3486fa69](https://linux-hardware.org/?probe=8c3486fa69) | Jul 16, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [b7992c5de7](https://linux-hardware.org/?probe=b7992c5de7) | Jul 16, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [069bfd995c](https://linux-hardware.org/?probe=069bfd995c) | Jul 15, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [f4bcea4686](https://linux-hardware.org/?probe=f4bcea4686) | Jul 15, 2023 |
| HP            | ZBook Power 15.6 inch G1... | Notebook    | [c2042a2e0e](https://linux-hardware.org/?probe=c2042a2e0e) | Jul 15, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [ba3be987e8](https://linux-hardware.org/?probe=ba3be987e8) | Jul 15, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [d2b32f5512](https://linux-hardware.org/?probe=d2b32f5512) | Jul 15, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [3577bb1c8f](https://linux-hardware.org/?probe=3577bb1c8f) | Jul 15, 2023 |
| ASRock        | Z690 Pro RS                 | Desktop     | [3becbb23af](https://linux-hardware.org/?probe=3becbb23af) | Jul 15, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [d7512ceea8](https://linux-hardware.org/?probe=d7512ceea8) | Jul 15, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [14bae4d3e7](https://linux-hardware.org/?probe=14bae4d3e7) | Jul 15, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [7872b8a730](https://linux-hardware.org/?probe=7872b8a730) | Jul 15, 2023 |
| Gateway       | SX2185                      | Desktop     | [1fe932f485](https://linux-hardware.org/?probe=1fe932f485) | Jul 15, 2023 |
| Gateway       | SX2185                      | Desktop     | [00e7bb0f9f](https://linux-hardware.org/?probe=00e7bb0f9f) | Jul 15, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [fab0c2fb26](https://linux-hardware.org/?probe=fab0c2fb26) | Jul 15, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [94f963ff8c](https://linux-hardware.org/?probe=94f963ff8c) | Jul 15, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [f25464fb37](https://linux-hardware.org/?probe=f25464fb37) | Jul 15, 2023 |
| Dell          | G5 5505                     | Notebook    | [ba144013b3](https://linux-hardware.org/?probe=ba144013b3) | Jul 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [c9cc25539e](https://linux-hardware.org/?probe=c9cc25539e) | Jul 15, 2023 |
| Acer          | Aspire V5-571G              | Notebook    | [e49b457f5b](https://linux-hardware.org/?probe=e49b457f5b) | Jul 15, 2023 |
| HP            | Pavilion Laptop 15-cc6xx    | Notebook    | [d39c88d40a](https://linux-hardware.org/?probe=d39c88d40a) | Jul 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [5fe3ea6d25](https://linux-hardware.org/?probe=5fe3ea6d25) | Jul 15, 2023 |
| Toshiba       | Satellite C70-B             | Notebook    | [9727ab2451](https://linux-hardware.org/?probe=9727ab2451) | Jul 14, 2023 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [62a4efa95d](https://linux-hardware.org/?probe=62a4efa95d) | Jul 14, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [c58d69659f](https://linux-hardware.org/?probe=c58d69659f) | Jul 14, 2023 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [4e78c933e4](https://linux-hardware.org/?probe=4e78c933e4) | Jul 14, 2023 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [14b5fe64fa](https://linux-hardware.org/?probe=14b5fe64fa) | Jul 14, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [e34b3f4c71](https://linux-hardware.org/?probe=e34b3f4c71) | Jul 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [d3c3cdb439](https://linux-hardware.org/?probe=d3c3cdb439) | Jul 14, 2023 |
| Acer          | Aspire V5-571G              | Notebook    | [e606ef8f63](https://linux-hardware.org/?probe=e606ef8f63) | Jul 14, 2023 |
| Dell          | Precision 7540              | Notebook    | [c862752535](https://linux-hardware.org/?probe=c862752535) | Jul 14, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [163766c886](https://linux-hardware.org/?probe=163766c886) | Jul 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [1e2b959156](https://linux-hardware.org/?probe=1e2b959156) | Jul 14, 2023 |
| Lenovo        | Legion R9000K2021H 82N6     | Notebook    | [4c8fc2482e](https://linux-hardware.org/?probe=4c8fc2482e) | Jul 14, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [62099e9da7](https://linux-hardware.org/?probe=62099e9da7) | Jul 14, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [065aed3358](https://linux-hardware.org/?probe=065aed3358) | Jul 14, 2023 |
| ASUSTek       | PRIME B550M-A AC            | Desktop     | [ed49c9c5e0](https://linux-hardware.org/?probe=ed49c9c5e0) | Jul 14, 2023 |
| Dell          | Latitude 7490               | Notebook    | [3ea6ad0e30](https://linux-hardware.org/?probe=3ea6ad0e30) | Jul 14, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [d132761a85](https://linux-hardware.org/?probe=d132761a85) | Jul 14, 2023 |
| ASUSTek       | X99-DELUXE II               | Desktop     | [70345fff08](https://linux-hardware.org/?probe=70345fff08) | Jul 14, 2023 |
| MSI           | MPG Z690 EDGE WIFI DDR4     | Desktop     | [96921926b1](https://linux-hardware.org/?probe=96921926b1) | Jul 14, 2023 |
| Gigabyte      | H77N-WIFI                   | Desktop     | [8ee665fb8f](https://linux-hardware.org/?probe=8ee665fb8f) | Jul 14, 2023 |
| Samsung       | 950QED                      | Convertible | [f2faf62d79](https://linux-hardware.org/?probe=f2faf62d79) | Jul 14, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [133cc41dd0](https://linux-hardware.org/?probe=133cc41dd0) | Jul 14, 2023 |
| GALAX         | A320M G10g                  | Desktop     | [730e46d4f0](https://linux-hardware.org/?probe=730e46d4f0) | Jul 14, 2023 |
| Google        | Droid                       | Notebook    | [9b77a9ba04](https://linux-hardware.org/?probe=9b77a9ba04) | Jul 14, 2023 |
| Dell          | 0HFG24 A01                  | Server      | [e7898eacb6](https://linux-hardware.org/?probe=e7898eacb6) | Jul 13, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [d2d9d84e27](https://linux-hardware.org/?probe=d2d9d84e27) | Jul 13, 2023 |
| Alienware     | x15 R1                      | Notebook    | [a72051a57e](https://linux-hardware.org/?probe=a72051a57e) | Jul 13, 2023 |
| Aava Mobil... | INARI10-WLAN-1              | Notebook    | [46d98ecf9a](https://linux-hardware.org/?probe=46d98ecf9a) | Jul 13, 2023 |
| Gigabyte      | P75-D3P                     | Desktop     | [0a7c65caae](https://linux-hardware.org/?probe=0a7c65caae) | Jul 13, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [cf9bdab1ee](https://linux-hardware.org/?probe=cf9bdab1ee) | Jul 13, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [ab0a96405e](https://linux-hardware.org/?probe=ab0a96405e) | Jul 13, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [965ca81d78](https://linux-hardware.org/?probe=965ca81d78) | Jul 13, 2023 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [fadd5eeba6](https://linux-hardware.org/?probe=fadd5eeba6) | Jul 13, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [adad96c487](https://linux-hardware.org/?probe=adad96c487) | Jul 13, 2023 |
| Aava Mobil... | INARI10-WLAN-1              | Notebook    | [d605371dc3](https://linux-hardware.org/?probe=d605371dc3) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460 20FMS50T0Q    | Notebook    | [0d5f86f700](https://linux-hardware.org/?probe=0d5f86f700) | Jul 13, 2023 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [144711a0e0](https://linux-hardware.org/?probe=144711a0e0) | Jul 13, 2023 |
| Lenovo        | ThinkPad T61 6465CTO        | Notebook    | [fcf6ce5b9e](https://linux-hardware.org/?probe=fcf6ce5b9e) | Jul 13, 2023 |
| MSI           | Katana GF66 11UC            | Notebook    | [d22ab22240](https://linux-hardware.org/?probe=d22ab22240) | Jul 13, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [cd3de89b97](https://linux-hardware.org/?probe=cd3de89b97) | Jul 12, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [4271ad9e9b](https://linux-hardware.org/?probe=4271ad9e9b) | Jul 12, 2023 |
| MSI           | 970A-G46                    | Desktop     | [09496b3221](https://linux-hardware.org/?probe=09496b3221) | Jul 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2a 21AB... | Notebook    | [63f31c01af](https://linux-hardware.org/?probe=63f31c01af) | Jul 12, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [e99992afd5](https://linux-hardware.org/?probe=e99992afd5) | Jul 12, 2023 |
| Lenovo        | ThinkPad X240 20AMS1FW00    | Notebook    | [15067533b3](https://linux-hardware.org/?probe=15067533b3) | Jul 12, 2023 |
| Lenovo        | ThinkPad L13 Gen 2a 21AB... | Notebook    | [e84be6ee7e](https://linux-hardware.org/?probe=e84be6ee7e) | Jul 12, 2023 |
| HP            | Laptop 15t-dy200            | Notebook    | [ef2fb33b01](https://linux-hardware.org/?probe=ef2fb33b01) | Jul 12, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [ad18a95d12](https://linux-hardware.org/?probe=ad18a95d12) | Jul 12, 2023 |
| MSI           | Alpha 15 A4DEK              | Notebook    | [cbae5fed49](https://linux-hardware.org/?probe=cbae5fed49) | Jul 12, 2023 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [779f922cbb](https://linux-hardware.org/?probe=779f922cbb) | Jul 12, 2023 |
| Dell          | Inspiron 5590               | Notebook    | [f3c9995017](https://linux-hardware.org/?probe=f3c9995017) | Jul 12, 2023 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [835e924f6d](https://linux-hardware.org/?probe=835e924f6d) | Jul 12, 2023 |
| MSI           | GF63 Thin 9SCSR             | Notebook    | [7bf81133fc](https://linux-hardware.org/?probe=7bf81133fc) | Jul 12, 2023 |
| MSI           | GF65 Thin 10UE              | Notebook    | [414c5bc2c0](https://linux-hardware.org/?probe=414c5bc2c0) | Jul 12, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [18a8fc202c](https://linux-hardware.org/?probe=18a8fc202c) | Jul 12, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [27df8fc0e5](https://linux-hardware.org/?probe=27df8fc0e5) | Jul 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [eccd385af4](https://linux-hardware.org/?probe=eccd385af4) | Jul 11, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [8267a42a4f](https://linux-hardware.org/?probe=8267a42a4f) | Jul 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [30d6b8bfde](https://linux-hardware.org/?probe=30d6b8bfde) | Jul 11, 2023 |
| raspberryp... | Raspberry Pi 4 Model B R... | Soc         | [a00ed74767](https://linux-hardware.org/?probe=a00ed74767) | Jul 11, 2023 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [161a78ce7d](https://linux-hardware.org/?probe=161a78ce7d) | Jul 11, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [069cf3a06d](https://linux-hardware.org/?probe=069cf3a06d) | Jul 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [aea754f076](https://linux-hardware.org/?probe=aea754f076) | Jul 11, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [5c12592f23](https://linux-hardware.org/?probe=5c12592f23) | Jul 11, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [aac3e629d3](https://linux-hardware.org/?probe=aac3e629d3) | Jul 11, 2023 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [2b544082c2](https://linux-hardware.org/?probe=2b544082c2) | Jul 11, 2023 |
| Dell          | Precision 5680              | Notebook    | [e1363522ee](https://linux-hardware.org/?probe=e1363522ee) | Jul 11, 2023 |
| Gigabyte      | J1900M-D2P                  | Desktop     | [a9e19d3887](https://linux-hardware.org/?probe=a9e19d3887) | Jul 11, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [76d89b3b3b](https://linux-hardware.org/?probe=76d89b3b3b) | Jul 11, 2023 |
| HP            | Tablet 11m-be0xxx           | Tablet      | [f825e83db2](https://linux-hardware.org/?probe=f825e83db2) | Jul 11, 2023 |
| Dell          | Latitude E5540              | Notebook    | [cdad6cb751](https://linux-hardware.org/?probe=cdad6cb751) | Jul 11, 2023 |
| Pegatron      | IPMH61P1                    | Desktop     | [9aa934f232](https://linux-hardware.org/?probe=9aa934f232) | Jul 11, 2023 |
| HP            | Tablet 11m-be0xxx           | Tablet      | [f0833b1df6](https://linux-hardware.org/?probe=f0833b1df6) | Jul 11, 2023 |
| ASUSTek       | PRIME B250M-D               | Desktop     | [304630d909](https://linux-hardware.org/?probe=304630d909) | Jul 11, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [2749c7cf78](https://linux-hardware.org/?probe=2749c7cf78) | Jul 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [9cc59dffca](https://linux-hardware.org/?probe=9cc59dffca) | Jul 11, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [464293fd0e](https://linux-hardware.org/?probe=464293fd0e) | Jul 11, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [04c6c9ba2b](https://linux-hardware.org/?probe=04c6c9ba2b) | Jul 10, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [35f03cf89f](https://linux-hardware.org/?probe=35f03cf89f) | Jul 10, 2023 |
| Lenovo        | ThinkPad Edge 0578P6G       | Notebook    | [e79fbdad2d](https://linux-hardware.org/?probe=e79fbdad2d) | Jul 10, 2023 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [6d191bde49](https://linux-hardware.org/?probe=6d191bde49) | Jul 10, 2023 |
| MSI           | GE66 Raider 10SFS           | Notebook    | [de2112a82f](https://linux-hardware.org/?probe=de2112a82f) | Jul 10, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [eca6eabcb2](https://linux-hardware.org/?probe=eca6eabcb2) | Jul 10, 2023 |
| ASUSTek       | N61Vn                       | Notebook    | [6bbb5b2105](https://linux-hardware.org/?probe=6bbb5b2105) | Jul 10, 2023 |
| ASUSTek       | N61Vn                       | Notebook    | [dd1a0f1acf](https://linux-hardware.org/?probe=dd1a0f1acf) | Jul 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [4e02ec47c0](https://linux-hardware.org/?probe=4e02ec47c0) | Jul 10, 2023 |
| MSI           | GF65 Thin 10UE              | Notebook    | [d73ac20739](https://linux-hardware.org/?probe=d73ac20739) | Jul 10, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [480ee8d732](https://linux-hardware.org/?probe=480ee8d732) | Jul 10, 2023 |
| MSI           | GF65 Thin 10UE              | Notebook    | [beef3128c2](https://linux-hardware.org/?probe=beef3128c2) | Jul 10, 2023 |
| Gigabyte      | Z77MX-D3H                   | Desktop     | [ac8df9628d](https://linux-hardware.org/?probe=ac8df9628d) | Jul 10, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [52fafabf05](https://linux-hardware.org/?probe=52fafabf05) | Jul 10, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [b904121800](https://linux-hardware.org/?probe=b904121800) | Jul 10, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [dcf418007d](https://linux-hardware.org/?probe=dcf418007d) | Jul 10, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [b515a2980e](https://linux-hardware.org/?probe=b515a2980e) | Jul 10, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [a2f3950062](https://linux-hardware.org/?probe=a2f3950062) | Jul 10, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [cf25605b3a](https://linux-hardware.org/?probe=cf25605b3a) | Jul 10, 2023 |
| Acer          | Aspire V3-571               | Notebook    | [3c3c2ac038](https://linux-hardware.org/?probe=3c3c2ac038) | Jul 10, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [55896d87cf](https://linux-hardware.org/?probe=55896d87cf) | Jul 10, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [0060a91b79](https://linux-hardware.org/?probe=0060a91b79) | Jul 10, 2023 |
| GALAX         | A320M G10g                  | Desktop     | [8ab8387585](https://linux-hardware.org/?probe=8ab8387585) | Jul 10, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [ceccedafbd](https://linux-hardware.org/?probe=ceccedafbd) | Jul 10, 2023 |
| ASUSTek       | PHOENIX                     | Desktop     | [88c02f40e7](https://linux-hardware.org/?probe=88c02f40e7) | Jul 09, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [c09e539c94](https://linux-hardware.org/?probe=c09e539c94) | Jul 09, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [9a2170442d](https://linux-hardware.org/?probe=9a2170442d) | Jul 09, 2023 |
| Dell          | Precision M4800             | Notebook    | [ef29f43a6f](https://linux-hardware.org/?probe=ef29f43a6f) | Jul 09, 2023 |
| Gigabyte      | B365M DS3H WIFI             | Desktop     | [150b2a2675](https://linux-hardware.org/?probe=150b2a2675) | Jul 09, 2023 |
| Gigabyte      | B365M DS3H WIFI             | Desktop     | [a887a01dd7](https://linux-hardware.org/?probe=a887a01dd7) | Jul 09, 2023 |
| Samsung       | 950XDB/951XDB/950XDY        | Notebook    | [5e41313f45](https://linux-hardware.org/?probe=5e41313f45) | Jul 09, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [e7c0c87a14](https://linux-hardware.org/?probe=e7c0c87a14) | Jul 09, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [fbeae7b57e](https://linux-hardware.org/?probe=fbeae7b57e) | Jul 09, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d9880a123f](https://linux-hardware.org/?probe=d9880a123f) | Jul 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [3a1baa8f6c](https://linux-hardware.org/?probe=3a1baa8f6c) | Jul 09, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [f79821f2eb](https://linux-hardware.org/?probe=f79821f2eb) | Jul 09, 2023 |
| Dell          | Latitude E6230              | Notebook    | [dd453671f3](https://linux-hardware.org/?probe=dd453671f3) | Jul 09, 2023 |
| Dell          | Latitude 5400               | Notebook    | [e8b701bf4e](https://linux-hardware.org/?probe=e8b701bf4e) | Jul 09, 2023 |
| Dell          | Latitude 5320               | Notebook    | [55d5b4447a](https://linux-hardware.org/?probe=55d5b4447a) | Jul 09, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [7d98a62bcc](https://linux-hardware.org/?probe=7d98a62bcc) | Jul 09, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [f9c2ea463a](https://linux-hardware.org/?probe=f9c2ea463a) | Jul 09, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [2dc2abef17](https://linux-hardware.org/?probe=2dc2abef17) | Jul 09, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [5593c83f71](https://linux-hardware.org/?probe=5593c83f71) | Jul 09, 2023 |
| Dell          | 00F82W A00                  | Desktop     | [603d370b5c](https://linux-hardware.org/?probe=603d370b5c) | Jul 09, 2023 |
| MSI           | Z97 GUARD-PRO               | Desktop     | [298da90a40](https://linux-hardware.org/?probe=298da90a40) | Jul 09, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [b05e0bc4e2](https://linux-hardware.org/?probe=b05e0bc4e2) | Jul 09, 2023 |
| MSI           | Stealth 16Studio A13VG      | Notebook    | [e16527e244](https://linux-hardware.org/?probe=e16527e244) | Jul 09, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [30658f7ab7](https://linux-hardware.org/?probe=30658f7ab7) | Jul 09, 2023 |
| Dell          | Latitude 7490               | Notebook    | [2a7f6b974b](https://linux-hardware.org/?probe=2a7f6b974b) | Jul 09, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21EBC... | Notebook    | [50f23f3476](https://linux-hardware.org/?probe=50f23f3476) | Jul 09, 2023 |
| HP            | G42                         | Notebook    | [e215b464bf](https://linux-hardware.org/?probe=e215b464bf) | Jul 09, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [f8aa10b5cb](https://linux-hardware.org/?probe=f8aa10b5cb) | Jul 08, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [1027217195](https://linux-hardware.org/?probe=1027217195) | Jul 08, 2023 |
| ECS           | P43T-AD3                    | Desktop     | [bdbd07c719](https://linux-hardware.org/?probe=bdbd07c719) | Jul 08, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [215fbed3ff](https://linux-hardware.org/?probe=215fbed3ff) | Jul 08, 2023 |
| GALAX         | A320M G10g                  | Desktop     | [21dab37c75](https://linux-hardware.org/?probe=21dab37c75) | Jul 08, 2023 |
| Dell          | Latitude 3500               | Notebook    | [38a0d6b099](https://linux-hardware.org/?probe=38a0d6b099) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [9b8e16f852](https://linux-hardware.org/?probe=9b8e16f852) | Jul 08, 2023 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [b4d926a4bc](https://linux-hardware.org/?probe=b4d926a4bc) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [06b52888f8](https://linux-hardware.org/?probe=06b52888f8) | Jul 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [0048149cd5](https://linux-hardware.org/?probe=0048149cd5) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [ffde5244e6](https://linux-hardware.org/?probe=ffde5244e6) | Jul 08, 2023 |
| Dell          | Inspiron 5493               | Notebook    | [3b68a8661e](https://linux-hardware.org/?probe=3b68a8661e) | Jul 08, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [2349cf550c](https://linux-hardware.org/?probe=2349cf550c) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [2e2541c7a6](https://linux-hardware.org/?probe=2e2541c7a6) | Jul 08, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [a5267b5818](https://linux-hardware.org/?probe=a5267b5818) | Jul 08, 2023 |
| HP            | 0AECh D                     | Desktop     | [c3d2867e48](https://linux-hardware.org/?probe=c3d2867e48) | Jul 08, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [d41838c540](https://linux-hardware.org/?probe=d41838c540) | Jul 08, 2023 |
| MSI           | GF65 Thin 10UE              | Notebook    | [8dd1516457](https://linux-hardware.org/?probe=8dd1516457) | Jul 08, 2023 |
| Gigabyte      | GA-A55M-S2V                 | Desktop     | [6cac69cac1](https://linux-hardware.org/?probe=6cac69cac1) | Jul 08, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [f86f946540](https://linux-hardware.org/?probe=f86f946540) | Jul 08, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [4bcab5adb1](https://linux-hardware.org/?probe=4bcab5adb1) | Jul 08, 2023 |
| MSI           | MPG B650I EDGE WIFI         | Desktop     | [bdaa09e52c](https://linux-hardware.org/?probe=bdaa09e52c) | Jul 08, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [052c072bc4](https://linux-hardware.org/?probe=052c072bc4) | Jul 08, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [09c80a40ac](https://linux-hardware.org/?probe=09c80a40ac) | Jul 07, 2023 |
| ASUSTek       | PHOENIX                     | Desktop     | [f12b531ae3](https://linux-hardware.org/?probe=f12b531ae3) | Jul 07, 2023 |
| Acer          | Aspire E1-570G              | Notebook    | [f1d3e3070e](https://linux-hardware.org/?probe=f1d3e3070e) | Jul 07, 2023 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [f2203ae88e](https://linux-hardware.org/?probe=f2203ae88e) | Jul 07, 2023 |
| AZW           | SER                         | Mini pc     | [1a93a70c6b](https://linux-hardware.org/?probe=1a93a70c6b) | Jul 07, 2023 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [e2adf09ecf](https://linux-hardware.org/?probe=e2adf09ecf) | Jul 07, 2023 |
| ASUSTek       | PHOENIX                     | Desktop     | [cc54a5a0bf](https://linux-hardware.org/?probe=cc54a5a0bf) | Jul 07, 2023 |
| HP            | 3397                        | Desktop     | [45bc734b0b](https://linux-hardware.org/?probe=45bc734b0b) | Jul 07, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [e4bb31a52c](https://linux-hardware.org/?probe=e4bb31a52c) | Jul 07, 2023 |
| Fujitsu       | D2628-C1 S26361-D2628-C1    | Desktop     | [bdf5ce2163](https://linux-hardware.org/?probe=bdf5ce2163) | Jul 07, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [2ed128676f](https://linux-hardware.org/?probe=2ed128676f) | Jul 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [aa8cfd7d60](https://linux-hardware.org/?probe=aa8cfd7d60) | Jul 07, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [0b4200c1e4](https://linux-hardware.org/?probe=0b4200c1e4) | Jul 07, 2023 |
| Schenker      | VIA 15 Pro                  | Notebook    | [bec6fac79a](https://linux-hardware.org/?probe=bec6fac79a) | Jul 07, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [629f165835](https://linux-hardware.org/?probe=629f165835) | Jul 07, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | Notebook    | [2ddfbf8bb9](https://linux-hardware.org/?probe=2ddfbf8bb9) | Jul 07, 2023 |
| Lenovo        | ThinkPad P52 20MAS17228     | Notebook    | [cb869cfeab](https://linux-hardware.org/?probe=cb869cfeab) | Jul 07, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [b7459d1653](https://linux-hardware.org/?probe=b7459d1653) | Jul 07, 2023 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | Notebook    | [dcf48c7be4](https://linux-hardware.org/?probe=dcf48c7be4) | Jul 07, 2023 |
| ASRock        | Z370 Professional Gaming... | Desktop     | [9101223f5e](https://linux-hardware.org/?probe=9101223f5e) | Jul 07, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1a318303e0](https://linux-hardware.org/?probe=1a318303e0) | Jul 07, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [2eb6b1bb05](https://linux-hardware.org/?probe=2eb6b1bb05) | Jul 07, 2023 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [4068c56cd3](https://linux-hardware.org/?probe=4068c56cd3) | Jul 07, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [5d0d505ca1](https://linux-hardware.org/?probe=5d0d505ca1) | Jul 07, 2023 |
| Lenovo        | XiaoXinPro 14ITL 2021 82... | Notebook    | [c060069870](https://linux-hardware.org/?probe=c060069870) | Jul 07, 2023 |
| Acer          | Aspire E1-570G              | Notebook    | [276cdeb14d](https://linux-hardware.org/?probe=276cdeb14d) | Jul 07, 2023 |
| Dell          | Inspiron 7506 2n1           | Convertible | [62b52c6053](https://linux-hardware.org/?probe=62b52c6053) | Jul 07, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [f687a3ac28](https://linux-hardware.org/?probe=f687a3ac28) | Jul 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [d09af80a65](https://linux-hardware.org/?probe=d09af80a65) | Jul 07, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [8da6cc6879](https://linux-hardware.org/?probe=8da6cc6879) | Jul 07, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [e134f78b10](https://linux-hardware.org/?probe=e134f78b10) | Jul 07, 2023 |
| HP            | 84EF 01100                  | All in one  | [d31e0669fa](https://linux-hardware.org/?probe=d31e0669fa) | Jul 06, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [2802b7951e](https://linux-hardware.org/?probe=2802b7951e) | Jul 06, 2023 |
| Lenovo        | ThinkPad T530 2392ASU       | Notebook    | [60c3515504](https://linux-hardware.org/?probe=60c3515504) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [097260a10f](https://linux-hardware.org/?probe=097260a10f) | Jul 06, 2023 |
| AZW           | SER V2.0                    | Mini pc     | [e9d599ea2a](https://linux-hardware.org/?probe=e9d599ea2a) | Jul 06, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [0c13e384e9](https://linux-hardware.org/?probe=0c13e384e9) | Jul 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [03f454349c](https://linux-hardware.org/?probe=03f454349c) | Jul 06, 2023 |
| HP            | Laptop 15-bs0xx             | Notebook    | [0a18dd76c6](https://linux-hardware.org/?probe=0a18dd76c6) | Jul 06, 2023 |
| MSI           | MS-7142                     | Desktop     | [3247a2f71c](https://linux-hardware.org/?probe=3247a2f71c) | Jul 06, 2023 |
| MSI           | H510M PRO-E                 | Desktop     | [598f789eb0](https://linux-hardware.org/?probe=598f789eb0) | Jul 06, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [4122f6e73c](https://linux-hardware.org/?probe=4122f6e73c) | Jul 06, 2023 |
| HP            | 82FE 11                     | Desktop     | [fcac934bde](https://linux-hardware.org/?probe=fcac934bde) | Jul 06, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU604VI... | Notebook    | [0311778091](https://linux-hardware.org/?probe=0311778091) | Jul 06, 2023 |
| AZW           | U59                         | Desktop     | [0b59408438](https://linux-hardware.org/?probe=0b59408438) | Jul 06, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [c93db722a7](https://linux-hardware.org/?probe=c93db722a7) | Jul 06, 2023 |
| MSI           | B150 GAMING M3              | Desktop     | [a8018be55a](https://linux-hardware.org/?probe=a8018be55a) | Jul 06, 2023 |
| Dell          | 06D7TR A00                  | Desktop     | [27f1fe9389](https://linux-hardware.org/?probe=27f1fe9389) | Jul 06, 2023 |
| Intel         | NUC6i7KYB H90766-408        | Mini pc     | [3ad05bcf55](https://linux-hardware.org/?probe=3ad05bcf55) | Jul 06, 2023 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [b50c5ad983](https://linux-hardware.org/?probe=b50c5ad983) | Jul 06, 2023 |
| ASUSTek       | A8R32-MVP Deluxe            | Desktop     | [3af1e33a01](https://linux-hardware.org/?probe=3af1e33a01) | Jul 06, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [ed520a330d](https://linux-hardware.org/?probe=ed520a330d) | Jul 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [a98b1d131d](https://linux-hardware.org/?probe=a98b1d131d) | Jul 06, 2023 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [eb913300f2](https://linux-hardware.org/?probe=eb913300f2) | Jul 06, 2023 |
| Microsoft     | Surface Pro 9               | Tablet      | [0572bb1441](https://linux-hardware.org/?probe=0572bb1441) | Jul 06, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [d0258b4ca5](https://linux-hardware.org/?probe=d0258b4ca5) | Jul 06, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [602c50a904](https://linux-hardware.org/?probe=602c50a904) | Jul 06, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [382fff8a04](https://linux-hardware.org/?probe=382fff8a04) | Jul 06, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [26145eba2e](https://linux-hardware.org/?probe=26145eba2e) | Jul 05, 2023 |
| HP            | Notebook                    | Notebook    | [19d38aa402](https://linux-hardware.org/?probe=19d38aa402) | Jul 05, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [dd020d65e5](https://linux-hardware.org/?probe=dd020d65e5) | Jul 05, 2023 |
| HP            | 304Ah                       | Desktop     | [029412ce85](https://linux-hardware.org/?probe=029412ce85) | Jul 05, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [c997aced4e](https://linux-hardware.org/?probe=c997aced4e) | Jul 05, 2023 |
| HP            | Notebook                    | Notebook    | [ac7ccc907b](https://linux-hardware.org/?probe=ac7ccc907b) | Jul 05, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [2fa3986e67](https://linux-hardware.org/?probe=2fa3986e67) | Jul 05, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [3e5dc0c313](https://linux-hardware.org/?probe=3e5dc0c313) | Jul 05, 2023 |
| Lenovo        | ThinkPad P73 20QRCTO1WW     | Notebook    | [60dad73833](https://linux-hardware.org/?probe=60dad73833) | Jul 05, 2023 |
| raspberryp... | Raspberry Pi 4 Model B R... | Soc         | [08387a7b77](https://linux-hardware.org/?probe=08387a7b77) | Jul 05, 2023 |
| raspberryp... | Raspberry Pi 4 Model B R... | Soc         | [48bd923b17](https://linux-hardware.org/?probe=48bd923b17) | Jul 05, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [a3a67ab04c](https://linux-hardware.org/?probe=a3a67ab04c) | Jul 05, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [06b0f38502](https://linux-hardware.org/?probe=06b0f38502) | Jul 05, 2023 |
| Samsung       | R580                        | Notebook    | [5205794d78](https://linux-hardware.org/?probe=5205794d78) | Jul 05, 2023 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [65cc87f2f0](https://linux-hardware.org/?probe=65cc87f2f0) | Jul 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [5e18a2d43c](https://linux-hardware.org/?probe=5e18a2d43c) | Jul 05, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [355ccda3d5](https://linux-hardware.org/?probe=355ccda3d5) | Jul 05, 2023 |
| ASUSTek       | ROG Strix G533ZM_G533ZM     | Notebook    | [e141746297](https://linux-hardware.org/?probe=e141746297) | Jul 05, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [bb708e03aa](https://linux-hardware.org/?probe=bb708e03aa) | Jul 05, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [b8f9aa3c52](https://linux-hardware.org/?probe=b8f9aa3c52) | Jul 05, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [50edacf233](https://linux-hardware.org/?probe=50edacf233) | Jul 05, 2023 |
| MSI           | Modern 14 B4MW              | Notebook    | [210a7aea7f](https://linux-hardware.org/?probe=210a7aea7f) | Jul 05, 2023 |
| ASUSTek       | CROSSBLADE RANGER           | Desktop     | [d816bd723e](https://linux-hardware.org/?probe=d816bd723e) | Jul 05, 2023 |
| Dell          | Inspiron 5593               | Notebook    | [a40b38a093](https://linux-hardware.org/?probe=a40b38a093) | Jul 05, 2023 |
| Lenovo        | 30D0 SDK0J40700 WIN 3258... | Desktop     | [2bb5ca7ea2](https://linux-hardware.org/?probe=2bb5ca7ea2) | Jul 05, 2023 |
| HP            | 245 14 inch G9 Notebook ... | Notebook    | [53bd77d836](https://linux-hardware.org/?probe=53bd77d836) | Jul 05, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [1a32b23618](https://linux-hardware.org/?probe=1a32b23618) | Jul 04, 2023 |
| MSI           | Summit E13FlipEvo A13MT     | Notebook    | [ec1d2fbdad](https://linux-hardware.org/?probe=ec1d2fbdad) | Jul 04, 2023 |
| HP            | Pavilion dv5                | Notebook    | [8064b5c083](https://linux-hardware.org/?probe=8064b5c083) | Jul 04, 2023 |
| Lenovo        | Legion R9000K2021H 82N6     | Notebook    | [a968f4b15c](https://linux-hardware.org/?probe=a968f4b15c) | Jul 04, 2023 |
| HP            | EliteBook 820 G1            | Notebook    | [5b1b409a2f](https://linux-hardware.org/?probe=5b1b409a2f) | Jul 04, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [6b4a40a1db](https://linux-hardware.org/?probe=6b4a40a1db) | Jul 04, 2023 |
| Apple         | MacBook8,1                  | Notebook    | [06ac15dcca](https://linux-hardware.org/?probe=06ac15dcca) | Jul 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [c3098317a7](https://linux-hardware.org/?probe=c3098317a7) | Jul 04, 2023 |
| AYANEO        | 2                           | Tablet      | [faff3af875](https://linux-hardware.org/?probe=faff3af875) | Jul 04, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [fea629b2e8](https://linux-hardware.org/?probe=fea629b2e8) | Jul 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [8553179448](https://linux-hardware.org/?probe=8553179448) | Jul 04, 2023 |
| HP            | 212B                        | Desktop     | [5c022be621](https://linux-hardware.org/?probe=5c022be621) | Jul 04, 2023 |
| Lenovo        | ThinkPad P50 20EQS48H00     | Notebook    | [7f64164b64](https://linux-hardware.org/?probe=7f64164b64) | Jul 04, 2023 |
| Timi          | Redmi G 2022                | Notebook    | [a6c12e95a6](https://linux-hardware.org/?probe=a6c12e95a6) | Jul 04, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [7acafd9528](https://linux-hardware.org/?probe=7acafd9528) | Jul 04, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [dfd88b9f78](https://linux-hardware.org/?probe=dfd88b9f78) | Jul 04, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [f5aa631644](https://linux-hardware.org/?probe=f5aa631644) | Jul 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [ca25e859c3](https://linux-hardware.org/?probe=ca25e859c3) | Jul 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [5d2bd9c3ce](https://linux-hardware.org/?probe=5d2bd9c3ce) | Jul 04, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [da0ca66579](https://linux-hardware.org/?probe=da0ca66579) | Jul 04, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [1714400cb9](https://linux-hardware.org/?probe=1714400cb9) | Jul 04, 2023 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [234c36d2ba](https://linux-hardware.org/?probe=234c36d2ba) | Jul 04, 2023 |
| Notebook      | P377SM-A                    | Notebook    | [acc35485db](https://linux-hardware.org/?probe=acc35485db) | Jul 04, 2023 |
| Notebook      | P377SM-A                    | Notebook    | [f37ed7f8db](https://linux-hardware.org/?probe=f37ed7f8db) | Jul 04, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [3fb951a266](https://linux-hardware.org/?probe=3fb951a266) | Jul 03, 2023 |
| Dell          | Precision 3581              | Notebook    | [1d4db3cec3](https://linux-hardware.org/?probe=1d4db3cec3) | Jul 03, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [d36574de10](https://linux-hardware.org/?probe=d36574de10) | Jul 03, 2023 |
| Kupi deshe... | X99Z-V102 Date 27052020     | Desktop     | [0cdbbfe5b3](https://linux-hardware.org/?probe=0cdbbfe5b3) | Jul 03, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [293008463e](https://linux-hardware.org/?probe=293008463e) | Jul 03, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [67c131f536](https://linux-hardware.org/?probe=67c131f536) | Jul 03, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [1af3478d1a](https://linux-hardware.org/?probe=1af3478d1a) | Jul 03, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [2585d66bd1](https://linux-hardware.org/?probe=2585d66bd1) | Jul 03, 2023 |
| MSI           | Z170A KRAIT GAMING          | Desktop     | [4bede9ff31](https://linux-hardware.org/?probe=4bede9ff31) | Jul 03, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [de620c05a9](https://linux-hardware.org/?probe=de620c05a9) | Jul 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | Notebook    | [6ca874df22](https://linux-hardware.org/?probe=6ca874df22) | Jul 03, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [b241427d10](https://linux-hardware.org/?probe=b241427d10) | Jul 03, 2023 |
| Lenovo        | Yoga 7 14ARB7 82QF          | Convertible | [205dfa0056](https://linux-hardware.org/?probe=205dfa0056) | Jul 03, 2023 |
| MSI           | Raider GE77HX 12UHS         | Notebook    | [87cc790852](https://linux-hardware.org/?probe=87cc790852) | Jul 03, 2023 |
| Lenovo        | ThinkPad P53 20QN0011IV     | Notebook    | [7aed7e46ad](https://linux-hardware.org/?probe=7aed7e46ad) | Jul 03, 2023 |
| HP            | 861A                        | Desktop     | [0531675f82](https://linux-hardware.org/?probe=0531675f82) | Jul 03, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [5f2c613312](https://linux-hardware.org/?probe=5f2c613312) | Jul 03, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [dc77810d67](https://linux-hardware.org/?probe=dc77810d67) | Jul 03, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [f957ad317f](https://linux-hardware.org/?probe=f957ad317f) | Jul 03, 2023 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [a7c8848746](https://linux-hardware.org/?probe=a7c8848746) | Jul 03, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [40ca2e97cc](https://linux-hardware.org/?probe=40ca2e97cc) | Jul 03, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [bdbf0fa0c3](https://linux-hardware.org/?probe=bdbf0fa0c3) | Jul 03, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [590efa4873](https://linux-hardware.org/?probe=590efa4873) | Jul 02, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [a6ceaae01b](https://linux-hardware.org/?probe=a6ceaae01b) | Jul 02, 2023 |
| ASRock        | Z87 Extreme6                | Desktop     | [d69ea1a2cb](https://linux-hardware.org/?probe=d69ea1a2cb) | Jul 02, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [69c34bf001](https://linux-hardware.org/?probe=69c34bf001) | Jul 02, 2023 |
| ASUSTek       | X99-M WS                    | Desktop     | [4f9ad96681](https://linux-hardware.org/?probe=4f9ad96681) | Jul 02, 2023 |
| AZW           | MINI S                      | Desktop     | [fb96f8d7bf](https://linux-hardware.org/?probe=fb96f8d7bf) | Jul 02, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [740a0dad30](https://linux-hardware.org/?probe=740a0dad30) | Jul 02, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [9c8f32ac20](https://linux-hardware.org/?probe=9c8f32ac20) | Jul 02, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [6c32038385](https://linux-hardware.org/?probe=6c32038385) | Jul 02, 2023 |
| Samsung       | 700Z3A/700Z4A/700Z5A/700... | Notebook    | [4586b855ca](https://linux-hardware.org/?probe=4586b855ca) | Jul 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [835f3a390f](https://linux-hardware.org/?probe=835f3a390f) | Jul 02, 2023 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [0a9e5c0979](https://linux-hardware.org/?probe=0a9e5c0979) | Jul 02, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [c2b529a2ee](https://linux-hardware.org/?probe=c2b529a2ee) | Jul 02, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [638d99b4f8](https://linux-hardware.org/?probe=638d99b4f8) | Jul 02, 2023 |
| HP            | Compaq 6910p                | Notebook    | [d72eacd7ea](https://linux-hardware.org/?probe=d72eacd7ea) | Jul 02, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d0ab54293f](https://linux-hardware.org/?probe=d0ab54293f) | Jul 02, 2023 |
| Samsung       | Galaxy TabPro S LTE         | Tablet      | [a53eeb72a6](https://linux-hardware.org/?probe=a53eeb72a6) | Jul 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [05394ee8a5](https://linux-hardware.org/?probe=05394ee8a5) | Jul 02, 2023 |
| Dell          | Latitude E6420              | Notebook    | [aae88e9000](https://linux-hardware.org/?probe=aae88e9000) | Jul 01, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [3bafd84f65](https://linux-hardware.org/?probe=3bafd84f65) | Jul 01, 2023 |
| Dell          | Latitude 7280               | Notebook    | [8ffe276705](https://linux-hardware.org/?probe=8ffe276705) | Jul 01, 2023 |
| ASRock        | B560M-ITX/ac                | Desktop     | [4c5f8f3d95](https://linux-hardware.org/?probe=4c5f8f3d95) | Jul 01, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [d2cbd5208d](https://linux-hardware.org/?probe=d2cbd5208d) | Jul 01, 2023 |
| Dell          | 09T7VV A02                  | Server      | [a63b9c6851](https://linux-hardware.org/?probe=a63b9c6851) | Jul 01, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [354dd05c7f](https://linux-hardware.org/?probe=354dd05c7f) | Jul 01, 2023 |
| ASRock        | A620M Pro RS WiFi           | Desktop     | [f771aedc9c](https://linux-hardware.org/?probe=f771aedc9c) | Jul 01, 2023 |
| HP            | 8061                        | Desktop     | [429534fab2](https://linux-hardware.org/?probe=429534fab2) | Jul 01, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [18b69ee7ff](https://linux-hardware.org/?probe=18b69ee7ff) | Jul 01, 2023 |
| Lenovo        | Yoga S740-15IRH 81NX        | Notebook    | [46508a63f2](https://linux-hardware.org/?probe=46508a63f2) | Jul 01, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [be62cc78df](https://linux-hardware.org/?probe=be62cc78df) | Jul 01, 2023 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [0c4c59cf86](https://linux-hardware.org/?probe=0c4c59cf86) | Jul 01, 2023 |
| HP            | 8054                        | Desktop     | [30c45def21](https://linux-hardware.org/?probe=30c45def21) | Jul 01, 2023 |
| HP            | 8054                        | Desktop     | [edf94b1f66](https://linux-hardware.org/?probe=edf94b1f66) | Jul 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 PRO     | Desktop     | [6c1829f43d](https://linux-hardware.org/?probe=6c1829f43d) | Jul 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [246d688f1c](https://linux-hardware.org/?probe=246d688f1c) | Jul 01, 2023 |
| Acer          | Aspire A515-56G             | Notebook    | [4c212e25ee](https://linux-hardware.org/?probe=4c212e25ee) | Jul 01, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [cfdff3114c](https://linux-hardware.org/?probe=cfdff3114c) | Jul 01, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [02a31c9704](https://linux-hardware.org/?probe=02a31c9704) | Jul 01, 2023 |
| Lenovo        | B40-70 20392                | Notebook    | [45739a208c](https://linux-hardware.org/?probe=45739a208c) | Jul 01, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [d7efa66a54](https://linux-hardware.org/?probe=d7efa66a54) | Jul 01, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [8ea4c888cf](https://linux-hardware.org/?probe=8ea4c888cf) | Jul 01, 2023 |
| Google        | Eldrid                      | Notebook    | [407bde63f9](https://linux-hardware.org/?probe=407bde63f9) | Jul 01, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [8f38634e0e](https://linux-hardware.org/?probe=8f38634e0e) | Jul 01, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a1739aa401](https://linux-hardware.org/?probe=a1739aa401) | Jul 01, 2023 |
| Fujitsu       | LIFEBOOK E780               | Notebook    | [12c5cd0309](https://linux-hardware.org/?probe=12c5cd0309) | Jul 01, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [d772da19a0](https://linux-hardware.org/?probe=d772da19a0) | Jun 30, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [e539937c27](https://linux-hardware.org/?probe=e539937c27) | Jun 30, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [b465607eea](https://linux-hardware.org/?probe=b465607eea) | Jun 30, 2023 |
| Acer          | Predator PO5-640            | Desktop     | [416b01c954](https://linux-hardware.org/?probe=416b01c954) | Jun 30, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [434ba90999](https://linux-hardware.org/?probe=434ba90999) | Jun 30, 2023 |
| HP            | ENVY m6                     | Notebook    | [b4f8d19895](https://linux-hardware.org/?probe=b4f8d19895) | Jun 30, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [3749bda51b](https://linux-hardware.org/?probe=3749bda51b) | Jun 30, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [3c3556dd33](https://linux-hardware.org/?probe=3c3556dd33) | Jun 30, 2023 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [6ee8476c0e](https://linux-hardware.org/?probe=6ee8476c0e) | Jun 30, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [eab5331f66](https://linux-hardware.org/?probe=eab5331f66) | Jun 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M560... | Notebook    | [5dd37cbc97](https://linux-hardware.org/?probe=5dd37cbc97) | Jun 30, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [0668932749](https://linux-hardware.org/?probe=0668932749) | Jun 30, 2023 |
| Google        | Eldrid                      | Notebook    | [4e08107dd6](https://linux-hardware.org/?probe=4e08107dd6) | Jun 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [77e6b09eb9](https://linux-hardware.org/?probe=77e6b09eb9) | Jun 30, 2023 |
| Dell          | Vostro 2520                 | Notebook    | [48d04d8282](https://linux-hardware.org/?probe=48d04d8282) | Jun 30, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [bb8a8eac46](https://linux-hardware.org/?probe=bb8a8eac46) | Jun 30, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [997b1fe1f8](https://linux-hardware.org/?probe=997b1fe1f8) | Jun 30, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [394788bdc8](https://linux-hardware.org/?probe=394788bdc8) | Jun 30, 2023 |
| AZW           | MINI S 10                   | Desktop     | [84eec8c276](https://linux-hardware.org/?probe=84eec8c276) | Jun 29, 2023 |
| AZW           | MINI S 10                   | Desktop     | [d1795fbf64](https://linux-hardware.org/?probe=d1795fbf64) | Jun 29, 2023 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [a64b48a5a2](https://linux-hardware.org/?probe=a64b48a5a2) | Jun 29, 2023 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [e21f5d35bb](https://linux-hardware.org/?probe=e21f5d35bb) | Jun 29, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [cfbc8c8a97](https://linux-hardware.org/?probe=cfbc8c8a97) | Jun 29, 2023 |
| MSI           | PS63 Modern 8SC             | Notebook    | [dcbb8108cf](https://linux-hardware.org/?probe=dcbb8108cf) | Jun 29, 2023 |
| Gigabyte      | H310M H                     | Desktop     | [0ad496c06d](https://linux-hardware.org/?probe=0ad496c06d) | Jun 29, 2023 |
| Dell          | Latitude 5521               | Notebook    | [3a8f3794aa](https://linux-hardware.org/?probe=3a8f3794aa) | Jun 29, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [5496b9130e](https://linux-hardware.org/?probe=5496b9130e) | Jun 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [df0ca94515](https://linux-hardware.org/?probe=df0ca94515) | Jun 29, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [95fb20193a](https://linux-hardware.org/?probe=95fb20193a) | Jun 29, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5bb4af3f8b](https://linux-hardware.org/?probe=5bb4af3f8b) | Jun 29, 2023 |
| Lenovo        | ThinkBook 14p Gen 3 21EJ    | Notebook    | [0086cae258](https://linux-hardware.org/?probe=0086cae258) | Jun 29, 2023 |
| Google        | Nami                        | Notebook    | [6ffc403580](https://linux-hardware.org/?probe=6ffc403580) | Jun 29, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [2a5ae27f54](https://linux-hardware.org/?probe=2a5ae27f54) | Jun 29, 2023 |
| Acer          | Aspire 5745G                | Notebook    | [c3394b9eb0](https://linux-hardware.org/?probe=c3394b9eb0) | Jun 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [92a71d25d7](https://linux-hardware.org/?probe=92a71d25d7) | Jun 28, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [6e6779c5d6](https://linux-hardware.org/?probe=6e6779c5d6) | Jun 28, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [08708e8e9d](https://linux-hardware.org/?probe=08708e8e9d) | Jun 28, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | Notebook    | [76e11b36e9](https://linux-hardware.org/?probe=76e11b36e9) | Jun 28, 2023 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [3f9d0da410](https://linux-hardware.org/?probe=3f9d0da410) | Jun 28, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [36f9eb51e6](https://linux-hardware.org/?probe=36f9eb51e6) | Jun 28, 2023 |
| Gigabyte      | B560M DS3H V2               | Desktop     | [aa24aa071b](https://linux-hardware.org/?probe=aa24aa071b) | Jun 28, 2023 |
| Dell          | Precision M6500             | Notebook    | [1db851fd5d](https://linux-hardware.org/?probe=1db851fd5d) | Jun 28, 2023 |
| MSI           | 880GM-E41                   | Desktop     | [91a2474332](https://linux-hardware.org/?probe=91a2474332) | Jun 28, 2023 |
| Fill By OE... | Q7700                       | Desktop     | [93c7c01ecb](https://linux-hardware.org/?probe=93c7c01ecb) | Jun 28, 2023 |
| ASRock        | H510M-HVS                   | Desktop     | [b90f532588](https://linux-hardware.org/?probe=b90f532588) | Jun 28, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [0294ef5e1f](https://linux-hardware.org/?probe=0294ef5e1f) | Jun 28, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [1aa332e26f](https://linux-hardware.org/?probe=1aa332e26f) | Jun 27, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [3d2a2196ae](https://linux-hardware.org/?probe=3d2a2196ae) | Jun 27, 2023 |
| HP            | 802F                        | Desktop     | [585f9bf338](https://linux-hardware.org/?probe=585f9bf338) | Jun 27, 2023 |
| HP            | 802F                        | Desktop     | [efceba0028](https://linux-hardware.org/?probe=efceba0028) | Jun 27, 2023 |
| HP            | Pavilion g6                 | Notebook    | [ec6a70b7d4](https://linux-hardware.org/?probe=ec6a70b7d4) | Jun 27, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [8c2e9b8870](https://linux-hardware.org/?probe=8c2e9b8870) | Jun 27, 2023 |
| Dell          | Inspiron 3543               | Notebook    | [4baea798b1](https://linux-hardware.org/?probe=4baea798b1) | Jun 27, 2023 |
| Intel Clie... | LAPRC710                    | Notebook    | [5aabe7850a](https://linux-hardware.org/?probe=5aabe7850a) | Jun 27, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [c05a780b64](https://linux-hardware.org/?probe=c05a780b64) | Jun 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [24d66c058b](https://linux-hardware.org/?probe=24d66c058b) | Jun 27, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [c3ae8b2d38](https://linux-hardware.org/?probe=c3ae8b2d38) | Jun 27, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [39ec9cf6c4](https://linux-hardware.org/?probe=39ec9cf6c4) | Jun 27, 2023 |
| Lenovo        | Yoga Slim 7 Carbon 13ITL... | Notebook    | [78b698279a](https://linux-hardware.org/?probe=78b698279a) | Jun 27, 2023 |
| Intel         | LADPNVMO AAE76523-300       | Desktop     | [76cc7bbb86](https://linux-hardware.org/?probe=76cc7bbb86) | Jun 27, 2023 |
| Fill By OE... | Q7700                       | Desktop     | [32ac9cb839](https://linux-hardware.org/?probe=32ac9cb839) | Jun 27, 2023 |
| HP            | ENVY Laptop 17-ch2xxx       | Notebook    | [41e22753cc](https://linux-hardware.org/?probe=41e22753cc) | Jun 27, 2023 |
| Dell          | 0R6PCT A01                  | Desktop     | [2fd7aa28db](https://linux-hardware.org/?probe=2fd7aa28db) | Jun 27, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D20... | Notebook    | [7487f61ff1](https://linux-hardware.org/?probe=7487f61ff1) | Jun 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b21d5b2e0a](https://linux-hardware.org/?probe=b21d5b2e0a) | Jun 26, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [e16689358e](https://linux-hardware.org/?probe=e16689358e) | Jun 26, 2023 |
| ASUSTek       | T102HA                      | Tablet      | [09acdc7c4a](https://linux-hardware.org/?probe=09acdc7c4a) | Jun 26, 2023 |
| Gigabyte      | MZBAYAB-00                  | Desktop     | [a44397603c](https://linux-hardware.org/?probe=a44397603c) | Jun 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [253fb546a2](https://linux-hardware.org/?probe=253fb546a2) | Jun 26, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [e5b49b2807](https://linux-hardware.org/?probe=e5b49b2807) | Jun 26, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [49c7e22c1e](https://linux-hardware.org/?probe=49c7e22c1e) | Jun 26, 2023 |
| Dell          | PowerEdge R720xd            | Server      | [4570023480](https://linux-hardware.org/?probe=4570023480) | Jun 26, 2023 |
| Toshiba       | TECRA R950                  | Notebook    | [f02bb9a43a](https://linux-hardware.org/?probe=f02bb9a43a) | Jun 26, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [22372b435f](https://linux-hardware.org/?probe=22372b435f) | Jun 26, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [a974c1b82e](https://linux-hardware.org/?probe=a974c1b82e) | Jun 26, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [31fc00f1ac](https://linux-hardware.org/?probe=31fc00f1ac) | Jun 26, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [ee5172b420](https://linux-hardware.org/?probe=ee5172b420) | Jun 26, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [03153f31b2](https://linux-hardware.org/?probe=03153f31b2) | Jun 26, 2023 |
| Lenovo        | ThinkPad T430 2349UA9       | Notebook    | [68117675ab](https://linux-hardware.org/?probe=68117675ab) | Jun 25, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [3486e43434](https://linux-hardware.org/?probe=3486e43434) | Jun 25, 2023 |
| HP            | Pavilion Laptop 14-bk0xx    | Notebook    | [e6184368a0](https://linux-hardware.org/?probe=e6184368a0) | Jun 25, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [bfa03ecd27](https://linux-hardware.org/?probe=bfa03ecd27) | Jun 25, 2023 |
| Lenovo        | ThinkPad X230 2324H58       | Notebook    | [bcf8a71bb4](https://linux-hardware.org/?probe=bcf8a71bb4) | Jun 25, 2023 |
| Lenovo        | Yoga Slim 7 13ACN5 82CY     | Notebook    | [58d1b3da16](https://linux-hardware.org/?probe=58d1b3da16) | Jun 25, 2023 |
| HP            | 255 G5 Notebook PC          | Notebook    | [cad891675f](https://linux-hardware.org/?probe=cad891675f) | Jun 25, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [6a01ca36af](https://linux-hardware.org/?probe=6a01ca36af) | Jun 25, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [b5996a0d85](https://linux-hardware.org/?probe=b5996a0d85) | Jun 25, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [29203c5ffe](https://linux-hardware.org/?probe=29203c5ffe) | Jun 25, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [3fbef5ec38](https://linux-hardware.org/?probe=3fbef5ec38) | Jun 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K650... | Notebook    | [8a833d8c52](https://linux-hardware.org/?probe=8a833d8c52) | Jun 25, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [2153f80362](https://linux-hardware.org/?probe=2153f80362) | Jun 25, 2023 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [1c648f1f3e](https://linux-hardware.org/?probe=1c648f1f3e) | Jun 25, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [684000f2c5](https://linux-hardware.org/?probe=684000f2c5) | Jun 25, 2023 |
| Lenovo        | V14 G2 ALC 82KC             | Notebook    | [40cbc38a69](https://linux-hardware.org/?probe=40cbc38a69) | Jun 25, 2023 |
| Google        | Nami                        | Notebook    | [f9f785f70d](https://linux-hardware.org/?probe=f9f785f70d) | Jun 25, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [7baa53c127](https://linux-hardware.org/?probe=7baa53c127) | Jun 25, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [75f62d2200](https://linux-hardware.org/?probe=75f62d2200) | Jun 24, 2023 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [3d1eeda7fa](https://linux-hardware.org/?probe=3d1eeda7fa) | Jun 24, 2023 |
| Dell          | 088DT1 A01                  | Desktop     | [755d1f8c03](https://linux-hardware.org/?probe=755d1f8c03) | Jun 24, 2023 |
| Dell          | Precision 5510              | Notebook    | [38d61a4475](https://linux-hardware.org/?probe=38d61a4475) | Jun 24, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [e80fd49ba9](https://linux-hardware.org/?probe=e80fd49ba9) | Jun 24, 2023 |
| Dell          | Vostro 2520                 | Notebook    | [9279842ec3](https://linux-hardware.org/?probe=9279842ec3) | Jun 24, 2023 |
| MSI           | Modern 14 A10M              | Notebook    | [fcc6786de6](https://linux-hardware.org/?probe=fcc6786de6) | Jun 24, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [4ad837baa7](https://linux-hardware.org/?probe=4ad837baa7) | Jun 24, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [77473ea84c](https://linux-hardware.org/?probe=77473ea84c) | Jun 24, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [1c0d2d86f3](https://linux-hardware.org/?probe=1c0d2d86f3) | Jun 24, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [99efa1a1c5](https://linux-hardware.org/?probe=99efa1a1c5) | Jun 24, 2023 |
| Lenovo        | Yoga Pro 7 14IRH8 82Y7      | Notebook    | [a74b5c2880](https://linux-hardware.org/?probe=a74b5c2880) | Jun 24, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [27c389d734](https://linux-hardware.org/?probe=27c389d734) | Jun 24, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b4c9b0d1f7](https://linux-hardware.org/?probe=b4c9b0d1f7) | Jun 24, 2023 |
| Xplore        | iX104C6                     | Notebook    | [23bb4c656b](https://linux-hardware.org/?probe=23bb4c656b) | Jun 24, 2023 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [bcfc1fe2de](https://linux-hardware.org/?probe=bcfc1fe2de) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [f51aeb6252](https://linux-hardware.org/?probe=f51aeb6252) | Jun 23, 2023 |
| Lenovo        | ThinkPad P15 Gen 1 20ST0... | Notebook    | [e44e80fc33](https://linux-hardware.org/?probe=e44e80fc33) | Jun 23, 2023 |
| Lenovo        | 00YJ434 SVT                 | Server      | [ba92d2c25b](https://linux-hardware.org/?probe=ba92d2c25b) | Jun 23, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [4c4335bcff](https://linux-hardware.org/?probe=4c4335bcff) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [7b187eac86](https://linux-hardware.org/?probe=7b187eac86) | Jun 23, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [ae40c874ae](https://linux-hardware.org/?probe=ae40c874ae) | Jun 23, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [505b340648](https://linux-hardware.org/?probe=505b340648) | Jun 23, 2023 |
| Oracle        | ASM,MOTHERBOARD,1U          | Server      | [cb71d1574c](https://linux-hardware.org/?probe=cb71d1574c) | Jun 23, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0NF0... | Notebook    | [f2e368a70d](https://linux-hardware.org/?probe=f2e368a70d) | Jun 23, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [a5f281a10e](https://linux-hardware.org/?probe=a5f281a10e) | Jun 23, 2023 |
| ASUSTek       | M4A77                       | Desktop     | [67e6b51c63](https://linux-hardware.org/?probe=67e6b51c63) | Jun 23, 2023 |
| AZW           | SER                         | Mini pc     | [4375fcb36a](https://linux-hardware.org/?probe=4375fcb36a) | Jun 23, 2023 |
| MSI           | B450M PRO-M2 V2             | Desktop     | [af46eedb6f](https://linux-hardware.org/?probe=af46eedb6f) | Jun 23, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [efb0264470](https://linux-hardware.org/?probe=efb0264470) | Jun 23, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [06977283b8](https://linux-hardware.org/?probe=06977283b8) | Jun 22, 2023 |
| HP            | Compaq 6710b (GF940AT#AB... | Notebook    | [75199aaf80](https://linux-hardware.org/?probe=75199aaf80) | Jun 22, 2023 |
| HONOR         | NBR-WAX9                    | Notebook    | [dfeaf221e6](https://linux-hardware.org/?probe=dfeaf221e6) | Jun 22, 2023 |
| ASUSTek       | PN64                        | Mini pc     | [c63cf5f434](https://linux-hardware.org/?probe=c63cf5f434) | Jun 22, 2023 |
| Positivo B... | VJFE43F11X-XXXXXX           | Notebook    | [e03310c8e8](https://linux-hardware.org/?probe=e03310c8e8) | Jun 22, 2023 |
| ASUSTek       | Maximus VIII RANGER Modi... | Desktop     | [d24120bc4e](https://linux-hardware.org/?probe=d24120bc4e) | Jun 22, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Fedora/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Fedora 36 | 2132      | 15.76%  |
| Fedora 37 | 2000      | 14.78%  |
| Fedora 38 | 1707      | 12.62%  |
| Fedora 35 | 1660      | 12.27%  |
| Fedora 34 | 1595      | 11.79%  |
| Fedora 33 | 1567      | 11.58%  |
| Fedora 32 | 1371      | 10.13%  |
| Fedora 31 | 910       | 6.73%   |
| Fedora 30 | 314       | 2.32%   |
| Fedora 29 | 173       | 1.28%   |
| Fedora 28 | 43        | 0.32%   |
| Fedora 27 | 19        | 0.14%   |
| Fedora 39 | 18        | 0.13%   |
| Fedora 24 | 6         | 0.04%   |
| Fedora 21 | 6         | 0.04%   |
| Fedora 25 | 4         | 0.03%   |
| Fedora 4  | 1         | 0.01%   |
| Fedora 17 | 1         | 0.01%   |
| Fedora 14 | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Fedora | 11960     | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 6.2.15-300.fc38.x86_64  | 227       | 1.49%   |
| 6.3.8-200.fc38.x86_64   | 208       | 1.37%   |
| 6.2.9-300.fc38.x86_64   | 187       | 1.23%   |
| 5.17.5-300.fc36.x86_64  | 182       | 1.2%    |
| 5.16.18-200.fc35.x86_64 | 162       | 1.06%   |
| 5.9.16-200.fc33.x86_64  | 159       | 1.05%   |
| 6.2.14-300.fc38.x86_64  | 151       | 0.99%   |
| 6.0.7-301.fc37.x86_64   | 145       | 0.95%   |
| 6.2.11-300.fc38.x86_64  | 133       | 0.87%   |
| 6.0.15-300.fc37.x86_64  | 131       | 0.86%   |
| 5.14.10-300.fc35.x86_64 | 130       | 0.85%   |
| 5.11.12-300.fc34.x86_64 | 123       | 0.81%   |
| 6.0.5-200.fc36.x86_64   | 116       | 0.76%   |
| 6.3.12-200.fc38.x86_64  | 114       | 0.75%   |
| 5.18.13-200.fc36.x86_64 | 112       | 0.74%   |
| 6.0.12-300.fc37.x86_64  | 107       | 0.7%    |
| 5.8.4-200.fc32.x86_64   | 101       | 0.66%   |
| 5.8.15-301.fc33.x86_64  | 100       | 0.66%   |
| 6.1.14-200.fc37.x86_64  | 97        | 0.64%   |
| 5.8.16-300.fc33.x86_64  | 97        | 0.64%   |
| 5.19.16-200.fc36.x86_64 | 96        | 0.63%   |
| 5.13.12-200.fc34.x86_64 | 96        | 0.63%   |
| 5.18.11-200.fc36.x86_64 | 90        | 0.59%   |
| 6.1.18-200.fc37.x86_64  | 89        | 0.58%   |
| 6.3.11-200.fc38.x86_64  | 87        | 0.57%   |
| 6.0.9-300.fc37.x86_64   | 87        | 0.57%   |
| 5.19.9-200.fc36.x86_64  | 87        | 0.57%   |
| 6.0.8-300.fc37.x86_64   | 86        | 0.57%   |
| 5.18.16-200.fc36.x86_64 | 85        | 0.56%   |
| 6.4.6-200.fc38.x86_64   | 84        | 0.55%   |
| 5.8.18-300.fc33.x86_64  | 81        | 0.53%   |
| 6.1.7-200.fc37.x86_64   | 79        | 0.52%   |
| 5.15.6-200.fc35.x86_64  | 78        | 0.51%   |
| 5.12.13-300.fc34.x86_64 | 78        | 0.51%   |
| 5.9.8-200.fc33.x86_64   | 77        | 0.51%   |
| 6.4.7-200.fc38.x86_64   | 76        | 0.5%    |
| 5.18.5-200.fc36.x86_64  | 75        | 0.49%   |
| 5.16.16-200.fc35.x86_64 | 75        | 0.49%   |
| 6.3.5-200.fc38.x86_64   | 74        | 0.49%   |
| 5.17.6-300.fc36.x86_64  | 74        | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.15  | 274       | 1.8%    |
| 6.2.9   | 251       | 1.65%   |
| 5.17.5  | 236       | 1.55%   |
| 6.3.8   | 226       | 1.49%   |
| 6.2.14  | 177       | 1.16%   |
| 5.9.16  | 176       | 1.16%   |
| 5.16.18 | 174       | 1.15%   |
| 6.0.7   | 173       | 1.14%   |
| 6.2.11  | 152       | 1%      |
| 5.8.15  | 151       | 0.99%   |
| 6.0.15  | 149       | 0.98%   |
| 5.19.16 | 146       | 0.96%   |
| 5.14.10 | 141       | 0.93%   |
| 5.11.12 | 133       | 0.88%   |
| 6.0.12  | 132       | 0.87%   |
| 5.8.16  | 131       | 0.86%   |
| 6.0.5   | 127       | 0.84%   |
| 5.8.18  | 121       | 0.8%    |
| 5.11.11 | 119       | 0.78%   |
| 6.3.12  | 117       | 0.77%   |
| 5.18.13 | 117       | 0.77%   |
| 6.0.9   | 113       | 0.74%   |
| 6.0.8   | 113       | 0.74%   |
| 6.1.14  | 104       | 0.68%   |
| 5.19.9  | 103       | 0.68%   |
| 5.13.12 | 102       | 0.67%   |
| 5.8.4   | 101       | 0.66%   |
| 5.14.18 | 96        | 0.63%   |
| 5.18.11 | 94        | 0.62%   |
| 6.1.18  | 93        | 0.61%   |
| 5.18.16 | 91        | 0.6%    |
| 6.2.8   | 89        | 0.59%   |
| 6.3.11  | 88        | 0.58%   |
| 5.15.6  | 88        | 0.58%   |
| 6.4.6   | 87        | 0.57%   |
| 5.19.8  | 87        | 0.57%   |
| 5.9.8   | 86        | 0.57%   |
| 5.18.5  | 86        | 0.57%   |
| 5.17.6  | 86        | 0.57%   |
| 6.1.7   | 85        | 0.56%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2     | 1198      | 8.27%   |
| 6.0     | 1115      | 7.69%   |
| 5.17    | 845       | 5.83%   |
| 5.8     | 843       | 5.82%   |
| 6.1     | 792       | 5.46%   |
| 5.11    | 792       | 5.46%   |
| 5.19    | 785       | 5.42%   |
| 5.18    | 738       | 5.09%   |
| 6.3     | 692       | 4.77%   |
| 5.16    | 664       | 4.58%   |
| 5.14    | 658       | 4.54%   |
| 5.9     | 563       | 3.88%   |
| 5.10    | 549       | 3.79%   |
| 5.13    | 543       | 3.75%   |
| 5.15    | 531       | 3.66%   |
| 5.6     | 522       | 3.6%    |
| 5.12    | 506       | 3.49%   |
| 5.7     | 423       | 2.92%   |
| 5.3     | 332       | 2.29%   |
| 5.4     | 323       | 2.23%   |
| 5.5     | 319       | 2.2%    |
| 6.4     | 259       | 1.79%   |
| 5.0     | 120       | 0.83%   |
| 5.2     | 110       | 0.76%   |
| 5.1     | 75        | 0.52%   |
| 4.19    | 56        | 0.39%   |
| 4.18    | 49        | 0.34%   |
| 4.20    | 39        | 0.27%   |
| 4.16    | 9         | 0.06%   |
| 6.5     | 6         | 0.04%   |
| 4.15    | 6         | 0.04%   |
| 4.17    | 5         | 0.03%   |
| 4.14    | 5         | 0.03%   |
| 4.11    | 5         | 0.03%   |
| 4.1     | 4         | 0.03%   |
| 3.17    | 3         | 0.02%   |
| 4.8     | 2         | 0.01%   |
| 4.13    | 2         | 0.01%   |
| Unknown | 2         | 0.01%   |
| 4.5     | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 11915     | 99.61%  |
| aarch64 | 30        | 0.25%   |
| i686    | 9         | 0.08%   |
| armv7l  | 5         | 0.04%   |
| Unknown | 2         | 0.02%   |
| ppc64le | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| GNOME                        | 8840      | 71.91%  |
| KDE5                         | 1455      | 11.84%  |
| Unknown                      | 681       | 5.54%   |
| KDE                          | 271       | 2.2%    |
| XFCE                         | 258       | 2.1%    |
| X-Cinnamon                   | 181       | 1.47%   |
| MATE                         | 156       | 1.27%   |
| Cinnamon                     | 149       | 1.21%   |
| GNOME Classic                | 58        | 0.47%   |
| i3                           | 48        | 0.39%   |
| LXQt                         | 39        | 0.32%   |
| LXDE                         | 30        | 0.24%   |
| Deepin                       | 27        | 0.22%   |
| sway                         | 25        | 0.2%    |
| KDE4                         | 11        | 0.09%   |
| Budgie                       | 10        | 0.08%   |
| awesome                      | 7         | 0.06%   |
| Pantheon                     | 6         | 0.05%   |
| openbox                      | 5         | 0.04%   |
| Hyprland                     | 5         | 0.04%   |
| DWM                          | 5         | 0.04%   |
| GNOME Flashback              | 4         | 0.03%   |
| fluxbox                      | 4         | 0.03%   |
| bspwm                        | 4         | 0.03%   |
| qtile                        | 3         | 0.02%   |
| xinit-compat                 | 2         | 0.02%   |
| GNOME-Classic                | 2         | 0.02%   |
| xmonad                       | 1         | 0.01%   |
| Phosh:GNOME                  | 1         | 0.01%   |
| NsCDE                        | 1         | 0.01%   |
| KDE:old                      | 1         | 0.01%   |
| GNUstep                      | 1         | 0.01%   |
| custom                       | 1         | 0.01%   |
| ${XDG_CURRENT_DESKTOP:-sway} | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 7781      | 62.45%  |
| X11     | 4031      | 32.35%  |
| Unknown | 390       | 3.13%   |
| Tty     | 250       | 2.01%   |
| Web     | 6         | 0.05%   |
| Xcb     | 1         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 6538      | 53.11%  |
| GDM     | 4159      | 33.79%  |
| SDDM    | 895       | 7.27%   |
| LightDM | 499       | 4.05%   |
| TDM     | 169       | 1.37%   |
| XDM     | 18        | 0.15%   |
| KDM     | 15        | 0.12%   |
| LXDM    | 12        | 0.1%    |
| SLiM    | 3         | 0.02%   |
| Ly      | 1         | 0.01%   |
| GREETD  | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 6102      | 50.08%  |
| en_GB   | 848       | 6.96%   |
| Unknown | 672       | 5.51%   |
| pt_BR   | 553       | 4.54%   |
| ru_RU   | 544       | 4.46%   |
| de_DE   | 495       | 4.06%   |
| fr_FR   | 359       | 2.95%   |
| it_IT   | 293       | 2.4%    |
| en_CA   | 256       | 2.1%    |
| en_AU   | 229       | 1.88%   |
| es_ES   | 184       | 1.51%   |
| pl_PL   | 183       | 1.5%    |
| en_IN   | 121       | 0.99%   |
| es_MX   | 105       | 0.86%   |
| cs_CZ   | 76        | 0.62%   |
| es_CL   | 60        | 0.49%   |
| es_AR   | 56        | 0.46%   |
| zh_CN   | 51        | 0.42%   |
| tr_TR   | 51        | 0.42%   |
| en_NZ   | 51        | 0.42%   |
| nl_NL   | 48        | 0.39%   |
| hu_HU   | 42        | 0.34%   |
| es_CO   | 42        | 0.34%   |
| sv_SE   | 41        | 0.34%   |
| C       | 40        | 0.33%   |
| en_DK   | 38        | 0.31%   |
| de_AT   | 38        | 0.31%   |
| en_IE   | 35        | 0.29%   |
| pt_PT   | 34        | 0.28%   |
| fi_FI   | 28        | 0.23%   |
| fr_CA   | 25        | 0.21%   |
| ru_UA   | 24        | 0.2%    |
| ja_JP   | 22        | 0.18%   |
| de_CH   | 22        | 0.18%   |
| nl_BE   | 20        | 0.16%   |
| fr_BE   | 20        | 0.16%   |
| uk_UA   | 19        | 0.16%   |
| sk_SK   | 19        | 0.16%   |
| en_ZA   | 19        | 0.16%   |
| da_DK   | 18        | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 9211      | 75.94%  |
| BIOS | 2918      | 24.06%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Btrfs               | 7332      | 59.87%  |
| Ext4                | 4106      | 33.53%  |
| Xfs                 | 411       | 3.36%   |
| Unknown             | 351       | 2.87%   |
| Overlay             | 21        | 0.17%   |
| Zfs                 | 8         | 0.07%   |
| Ext3                | 7         | 0.06%   |
| F2fs                | 6         | 0.05%   |
| Fuse.fuse-overlayfs | 4         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 6410      | 52.22%  |
| GPT     | 5043      | 41.08%  |
| MBR     | 823       | 6.7%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 10802     | 88.86%  |
| Yes       | 1354      | 11.14%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 9815      | 80.89%  |
| Yes       | 2319      | 19.11%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 2452      | 20.5%   |
| ASUSTek Computer        | 1907      | 15.94%  |
| Dell                    | 1612      | 13.48%  |
| Hewlett-Packard         | 1471      | 12.3%   |
| Gigabyte Technology     | 780       | 6.52%   |
| MSI                     | 765       | 6.4%    |
| Acer                    | 513       | 4.29%   |
| ASRock                  | 400       | 3.34%   |
| Apple                   | 285       | 2.38%   |
| HUAWEI                  | 152       | 1.27%   |
| Intel                   | 148       | 1.24%   |
| Samsung Electronics     | 114       | 0.95%   |
| Toshiba                 | 96        | 0.8%    |
| Unknown                 | 89        | 0.74%   |
| Microsoft               | 73        | 0.61%   |
| Sony                    | 56        | 0.47%   |
| Notebook                | 55        | 0.46%   |
| Timi                    | 49        | 0.41%   |
| Fujitsu                 | 46        | 0.38%   |
| Google                  | 40        | 0.33%   |
| Alienware               | 36        | 0.3%    |
| Positivo                | 34        | 0.28%   |
| Framework               | 33        | 0.28%   |
| Supermicro              | 32        | 0.27%   |
| Pegatron                | 26        | 0.22%   |
| System76                | 24        | 0.2%    |
| AZW                     | 22        | 0.18%   |
| BESSTAR Tech            | 20        | 0.17%   |
| TUXEDO                  | 19        | 0.16%   |
| LG Electronics          | 19        | 0.16%   |
| Razer                   | 18        | 0.15%   |
| Huanan                  | 18        | 0.15%   |
| Chuwi                   | 18        | 0.15%   |
| Biostar                 | 18        | 0.15%   |
| ECS                     | 17        | 0.14%   |
| Raspberry Pi Foundation | 15        | 0.13%   |
| Medion                  | 15        | 0.13%   |
| AMI                     | 14        | 0.12%   |
| HONOR                   | 13        | 0.11%   |
| Itautec                 | 12        | 0.1%    |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Unknown                            | 116       | 0.97%   |
| ASUS All Series                    | 113       | 0.94%   |
| MSI MS-7C37                        | 43        | 0.36%   |
| HP Notebook                        | 34        | 0.28%   |
| ASUS TUF Gaming X570-PLUS          | 31        | 0.26%   |
| MSI MS-7A38                        | 25        | 0.21%   |
| Framework Laptop                   | 25        | 0.21%   |
| Dell XPS 15 9570                   | 25        | 0.21%   |
| Dell XPS 13 9370                   | 25        | 0.21%   |
| MSI MS-7C02                        | 24        | 0.2%    |
| Gigabyte B450M DS3H                | 24        | 0.2%    |
| Dell OptiPlex 7010                 | 24        | 0.2%    |
| Dell Latitude 7490                 | 24        | 0.2%    |
| Dell XPS 15 7590                   | 23        | 0.19%   |
| Lenovo IdeaPadFlex 5 14ARE05 81X2  | 22        | 0.18%   |
| Dell XPS 15 9560                   | 22        | 0.18%   |
| Dell XPS 13 9310                   | 21        | 0.18%   |
| MSI MS-7B86                        | 19        | 0.16%   |
| HP EliteBook 840 G6                | 19        | 0.16%   |
| Dell XPS 13 9360                   | 19        | 0.16%   |
| Dell XPS 13 7390                   | 19        | 0.16%   |
| Apple MacBookPro9,2                | 19        | 0.16%   |
| Dell XPS 15 9500                   | 18        | 0.15%   |
| Dell Latitude E7450                | 18        | 0.15%   |
| MSI MS-7C91                        | 17        | 0.14%   |
| MSI MS-7C56                        | 17        | 0.14%   |
| MSI MS-7B79                        | 17        | 0.14%   |
| HP Pavilion dv6                    | 17        | 0.14%   |
| HP ENVY x360 Convertible 13-ay0xxx | 17        | 0.14%   |
| Dell XPS 15 9550                   | 17        | 0.14%   |
| Dell OptiPlex 9020                 | 17        | 0.14%   |
| ASUS ROG STRIX B550-F GAMING       | 17        | 0.14%   |
| HP Pavilion 15                     | 16        | 0.13%   |
| Apple MacBookPro12,1               | 16        | 0.13%   |
| MSI MS-7B89                        | 15        | 0.13%   |
| Lenovo ThinkBook 15 G2 ITL 20VE    | 15        | 0.13%   |
| HP Laptop 15-da0xxx                | 15        | 0.13%   |
| Gigabyte B450 AORUS ELITE          | 15        | 0.13%   |
| ASUS ROG STRIX X570-F GAMING       | 15        | 0.13%   |
| ASUS ROG STRIX B550-I GAMING       | 15        | 0.13%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 1316      | 11%     |
| Lenovo IdeaPad     | 428       | 3.58%   |
| Dell Inspiron      | 419       | 3.5%    |
| Dell Latitude      | 395       | 3.3%    |
| ASUS ROG           | 362       | 3.03%   |
| Dell XPS           | 325       | 2.72%   |
| Acer Aspire        | 319       | 2.67%   |
| HP Pavilion        | 267       | 2.23%   |
| ASUS PRIME         | 237       | 1.98%   |
| HP EliteBook       | 213       | 1.78%   |
| ASUS TUF           | 166       | 1.39%   |
| HP ProBook         | 163       | 1.36%   |
| ASUS VivoBook      | 158       | 1.32%   |
| Lenovo Yoga        | 155       | 1.3%    |
| Dell OptiPlex      | 153       | 1.28%   |
| HP Laptop          | 152       | 1.27%   |
| Dell Precision     | 151       | 1.26%   |
| HP ENVY            | 130       | 1.09%   |
| Unknown            | 116       | 0.97%   |
| ASUS All           | 113       | 0.94%   |
| Lenovo Legion      | 94        | 0.79%   |
| Lenovo ThinkCentre | 83        | 0.69%   |
| Lenovo ThinkBook   | 82        | 0.69%   |
| Toshiba Satellite  | 78        | 0.65%   |
| Microsoft Surface  | 73        | 0.61%   |
| ASUS ZenBook       | 68        | 0.57%   |
| Dell Vostro        | 67        | 0.56%   |
| Gigabyte X570      | 66        | 0.55%   |
| ASUS ASUS          | 65        | 0.54%   |
| Acer Nitro         | 65        | 0.54%   |
| HP Compaq          | 59        | 0.49%   |
| HP ZBook           | 55        | 0.46%   |
| Lenovo IdeaPadFlex | 51        | 0.43%   |
| Gigabyte B450      | 48        | 0.4%    |
| MSI MS-7C37        | 43        | 0.36%   |
| HP EliteDesk       | 43        | 0.36%   |
| Acer Swift         | 41        | 0.34%   |
| Gigabyte B450M     | 40        | 0.33%   |
| HP Spectre         | 39        | 0.33%   |
| HP OMEN            | 38        | 0.32%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 1546      | 12.93%  |
| 2019    | 1515      | 12.67%  |
| 2018    | 1403      | 11.73%  |
| 2021    | 1226      | 10.25%  |
| 2017    | 968       | 8.09%   |
| 2012    | 715       | 5.98%   |
| 2013    | 669       | 5.59%   |
| 2015    | 667       | 5.58%   |
| 2016    | 634       | 5.3%    |
| 2014    | 619       | 5.18%   |
| 2022    | 614       | 5.13%   |
| 2011    | 512       | 4.28%   |
| 2010    | 295       | 2.47%   |
| 2009    | 200       | 1.67%   |
| 2008    | 186       | 1.56%   |
| 2023    | 74        | 0.62%   |
| 2007    | 68        | 0.57%   |
| 2006    | 26        | 0.22%   |
| Unknown | 17        | 0.14%   |
| 2005    | 5         | 0.04%   |
| 2003    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 6965      | 58.24%  |
| Desktop        | 3905      | 32.65%  |
| Convertible    | 527       | 4.41%   |
| Tablet         | 175       | 1.46%   |
| Mini pc        | 172       | 1.44%   |
| All in one     | 126       | 1.05%   |
| Server         | 60        | 0.5%    |
| System on chip | 30        | 0.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 10035     | 82.59%  |
| Enabled  | 2115      | 17.41%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 11898     | 99.48%  |
| Yes  | 62        | 0.52%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 3166      | 26.01%  |
| 4.01-8.0        | 2812      | 23.1%   |
| 8.01-16.0       | 2300      | 18.89%  |
| 32.01-64.0      | 1804      | 14.82%  |
| 3.01-4.0        | 1042      | 8.56%   |
| 64.01-256.0     | 476       | 3.91%   |
| 24.01-32.0      | 298       | 2.45%   |
| 1.01-2.0        | 195       | 1.6%    |
| 2.01-3.0        | 46        | 0.38%   |
| 0.51-1.0        | 20        | 0.16%   |
| More than 256.0 | 9         | 0.07%   |
| Unknown         | 6         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 3782      | 27.82%  |
| 2.01-3.0    | 3627      | 26.68%  |
| 3.01-4.0    | 2893      | 21.28%  |
| 1.01-2.0    | 1776      | 13.06%  |
| 8.01-16.0   | 1077      | 7.92%   |
| 0.51-1.0    | 184       | 1.35%   |
| 16.01-24.0  | 148       | 1.09%   |
| 24.01-32.0  | 46        | 0.34%   |
| 32.01-64.0  | 26        | 0.19%   |
| 0.01-0.5    | 25        | 0.18%   |
| Unknown     | 8         | 0.06%   |
| 64.01-256.0 | 3         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7084      | 57.34%  |
| 2       | 3187      | 25.8%   |
| 3       | 1051      | 8.51%   |
| 4       | 486       | 3.93%   |
| 5       | 235       | 1.9%    |
| 6       | 117       | 0.95%   |
| 0       | 64        | 0.52%   |
| 7       | 58        | 0.47%   |
| 8       | 29        | 0.23%   |
| 9       | 13        | 0.11%   |
| 10      | 10        | 0.08%   |
| 11      | 5         | 0.04%   |
| 12      | 4         | 0.03%   |
| 36      | 2         | 0.02%   |
| 15      | 2         | 0.02%   |
| 14      | 2         | 0.02%   |
| 27      | 1         | 0.01%   |
| 24      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |
| 17      | 1         | 0.01%   |
| 13      | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 9107      | 75.6%   |
| Yes       | 2939      | 24.4%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 9578      | 79.68%  |
| No        | 2443      | 20.32%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 9682      | 80.5%   |
| No        | 2345      | 19.5%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 8445      | 69.62%  |
| No        | 3685      | 30.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 2387      | 19.77%  |
| Germany     | 901       | 7.46%   |
| Brazil      | 832       | 6.89%   |
| Russia      | 749       | 6.2%    |
| Italy       | 512       | 4.24%   |
| France      | 460       | 3.81%   |
| UK          | 438       | 3.63%   |
| Canada      | 409       | 3.39%   |
| India       | 356       | 2.95%   |
| Poland      | 339       | 2.81%   |
| Netherlands | 325       | 2.69%   |
| Spain       | 287       | 2.38%   |
| Australia   | 273       | 2.26%   |
| Mexico      | 191       | 1.58%   |
| Czechia     | 184       | 1.52%   |
| Sweden      | 173       | 1.43%   |
| Turkey      | 152       | 1.26%   |
| Switzerland | 148       | 1.23%   |
| Austria     | 145       | 1.2%    |
| Belgium     | 125       | 1.04%   |
| Argentina   | 107       | 0.89%   |
| Ukraine     | 104       | 0.86%   |
| Finland     | 102       | 0.84%   |
| Romania     | 99        | 0.82%   |
| Portugal    | 98        | 0.81%   |
| Norway      | 98        | 0.81%   |
| Hungary     | 94        | 0.78%   |
| Chile       | 90        | 0.75%   |
| Indonesia   | 84        | 0.7%    |
| Denmark     | 79        | 0.65%   |
| Colombia    | 75        | 0.62%   |
| China       | 66        | 0.55%   |
| New Zealand | 62        | 0.51%   |
| Greece      | 61        | 0.51%   |
| Japan       | 59        | 0.49%   |
| Israel      | 54        | 0.45%   |
| Belarus     | 54        | 0.45%   |
| Bulgaria    | 51        | 0.42%   |
| Slovakia    | 50        | 0.41%   |
| Iran        | 47        | 0.39%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 224       | 1.74%   |
| Sao Paulo         | 105       | 0.81%   |
| St Petersburg     | 104       | 0.81%   |
| Berlin            | 101       | 0.78%   |
| Vienna            | 94        | 0.73%   |
| Sydney            | 92        | 0.71%   |
| Warsaw            | 80        | 0.62%   |
| Paris             | 80        | 0.62%   |
| Prague            | 70        | 0.54%   |
| Milan             | 70        | 0.54%   |
| Amsterdam         | 69        | 0.53%   |
| Melbourne         | 65        | 0.5%    |
| Madrid            | 62        | 0.48%   |
| Istanbul          | 62        | 0.48%   |
| Helsinki          | 57        | 0.44%   |
| Rio de Janeiro    | 50        | 0.39%   |
| Munich            | 50        | 0.39%   |
| Bengaluru         | 49        | 0.38%   |
| Hamburg           | 48        | 0.37%   |
| Brisbane          | 48        | 0.37%   |
| Mexico City       | 47        | 0.36%   |
| Montreal          | 46        | 0.36%   |
| Delft             | 45        | 0.35%   |
| Budapest          | 45        | 0.35%   |
| Zurich            | 44        | 0.34%   |
| Oslo              | 43        | 0.33%   |
| Rome              | 42        | 0.33%   |
| Frankfurt am Main | 42        | 0.33%   |
| Toronto           | 41        | 0.32%   |
| Santiago          | 40        | 0.31%   |
| Seattle           | 38        | 0.29%   |
| Portland          | 38        | 0.29%   |
| Los Angeles       | 37        | 0.29%   |
| Bucharest         | 37        | 0.29%   |
| Athens            | 36        | 0.28%   |
| New York          | 35        | 0.27%   |
| London            | 35        | 0.27%   |
| Minsk             | 34        | 0.26%   |
| Lisbon            | 34        | 0.26%   |
| Buenos Aires      | 34        | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 3632      | 5992   | 20.02%  |
| WDC                         | 2350      | 3936   | 12.95%  |
| Seagate                     | 1999      | 3299   | 11.02%  |
| SanDisk                     | 1169      | 1564   | 6.44%   |
| Toshiba                     | 1072      | 1472   | 5.91%   |
| Kingston                    | 1018      | 1395   | 5.61%   |
| Crucial                     | 706       | 1036   | 3.89%   |
| Unknown                     | 675       | 935    | 3.72%   |
| SK hynix                    | 673       | 831    | 3.71%   |
| Intel                       | 627       | 955    | 3.46%   |
| Micron Technology           | 369       | 486    | 2.03%   |
| Hitachi                     | 290       | 437    | 1.6%    |
| A-DATA Technology           | 278       | 354    | 1.53%   |
| HGST                        | 260       | 411    | 1.43%   |
| KIOXIA                      | 184       | 272    | 1.01%   |
| Phison                      | 173       | 224    | 0.95%   |
| Apple                       | 150       | 200    | 0.83%   |
| China                       | 123       | 157    | 0.68%   |
| Silicon Motion              | 116       | 151    | 0.64%   |
| Micron/Crucial Technology   | 111       | 136    | 0.61%   |
| Phison Electronics          | 103       | 142    | 0.57%   |
| LITEON                      | 99        | 109    | 0.55%   |
| SPCC                        | 96        | 138    | 0.53%   |
| PNY                         | 84        | 114    | 0.46%   |
| Corsair                     | 81        | 115    | 0.45%   |
| Transcend                   | 68        | 99     | 0.37%   |
| Patriot                     | 64        | 94     | 0.35%   |
| OCZ                         | 57        | 73     | 0.31%   |
| ADATA Technology            | 53        | 57     | 0.29%   |
| XPG                         | 48        | 68     | 0.26%   |
| JMicron Technology          | 48        | 67     | 0.26%   |
| Intenso                     | 47        | 58     | 0.26%   |
| Unknown                     | 46        | 53     | 0.25%   |
| Realtek Semiconductor       | 42        | 55     | 0.23%   |
| Kingston Technology Company | 42        | 49     | 0.23%   |
| LITEONIT                    | 41        | 49     | 0.23%   |
| Team                        | 40        | 53     | 0.22%   |
| Hewlett-Packard             | 40        | 63     | 0.22%   |
| Gigabyte Technology         | 37        | 59     | 0.2%    |
| Netac                       | 36        | 43     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 257       | 1.26%   |
| Kingston SA400S37240G 240GB SSD                     | 203       | 1%      |
| Samsung SSD 850 EVO 250GB                           | 179       | 0.88%   |
| Samsung SSD 860 EVO 500GB                           | 171       | 0.84%   |
| Seagate ST1000LM035-1RK172 1TB                      | 157       | 0.77%   |
| Samsung NVMe SSD Drive 512GB                        | 148       | 0.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 139       | 0.68%   |
| Samsung SSD 850 EVO 500GB                           | 137       | 0.67%   |
| Samsung NVMe SSD Drive 500GB                        | 132       | 0.65%   |
| Kingston SA400S37480G 480GB SSD                     | 130       | 0.64%   |
| Samsung SSD 860 EVO 1TB                             | 129       | 0.63%   |
| Samsung NVMe SSD Drive 1TB                          | 119       | 0.58%   |
| Samsung NVMe SSD Drive 256GB                        | 115       | 0.56%   |
| Seagate ST1000DM010-2EP102 1TB                      | 106       | 0.52%   |
| Unknown MMC Card  32GB                              | 105       | 0.52%   |
| Kingston SA400S37120G 120GB SSD                     | 103       | 0.51%   |
| Crucial CT500MX500SSD1 500GB                        | 100       | 0.49%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 98        | 0.48%   |
| Unknown MMC Card  64GB                              | 97        | 0.48%   |
| Seagate ST2000DM008-2FR102 2TB                      | 97        | 0.48%   |
| SanDisk NVMe SSD Drive 512GB                        | 97        | 0.48%   |
| HGST HTS721010A9E630 1TB                            | 93        | 0.46%   |
| Crucial CT1000MX500SSD1 1TB                         | 92        | 0.45%   |
| Seagate ST500DM002-1BD142 500GB                     | 86        | 0.42%   |
| Samsung SSD 860 EVO 250GB                           | 86        | 0.42%   |
| Toshiba MQ01ABD100 1TB                              | 83        | 0.41%   |
| Toshiba MQ04ABF100 1TB                              | 81        | 0.4%    |
| Samsung SSD 970 EVO Plus 500GB                      | 76        | 0.37%   |
| Crucial CT240BX500SSD1 240GB                        | 75        | 0.37%   |
| Toshiba DT01ACA100 1TB                              | 74        | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 72        | 0.35%   |
| Unknown MMC Card  128GB                             | 72        | 0.35%   |
| Samsung SSD 970 EVO Plus 1TB                        | 71        | 0.35%   |
| SanDisk NVMe SSD Drive 1TB                          | 70        | 0.34%   |
| Samsung NVMe SSD Drive 1024GB                       | 70        | 0.34%   |
| Intel NVMe SSD Drive 512GB                          | 69        | 0.34%   |
| SanDisk NVMe SSD Drive 500GB                        | 65        | 0.32%   |
| Kingston SV300S37A120G 120GB SSD                    | 62        | 0.3%    |
| SK hynix NVMe SSD Drive 512GB                       | 61        | 0.3%    |
| Seagate Expansion 1TB                               | 58        | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1933      | 3184   | 36.81%  |
| WDC                 | 1682      | 2926   | 32.03%  |
| Toshiba             | 657       | 897    | 12.51%  |
| Hitachi             | 290       | 437    | 5.52%   |
| HGST                | 259       | 410    | 4.93%   |
| Samsung Electronics | 166       | 255    | 3.16%   |
| Unknown             | 51        | 69     | 0.97%   |
| Apple               | 41        | 45     | 0.78%   |
| JMicron Technology  | 31        | 48     | 0.59%   |
| Maxtor              | 26        | 30     | 0.5%    |
| Fujitsu             | 21        | 23     | 0.4%    |
| ASMT                | 20        | 23     | 0.38%   |
| Hewlett-Packard     | 7         | 27     | 0.13%   |
| External            | 7         | 10     | 0.13%   |
| USB3.0              | 6         | 6      | 0.11%   |
| Intenso             | 5         | 8      | 0.1%    |
| Inateck             | 5         | 13     | 0.1%    |
| SSK                 | 4         | 4      | 0.08%   |
| LIO-ORG             | 4         | 21     | 0.08%   |
| LaCie               | 4         | 7      | 0.08%   |
| USB                 | 3         | 3      | 0.06%   |
| QNAP                | 3         | 6      | 0.06%   |
| MaxDigital          | 3         | 3      | 0.06%   |
| ASMedia             | 3         | 3      | 0.06%   |
| Synology            | 2         | 3      | 0.04%   |
| HGST HTS            | 2         | 2      | 0.04%   |
| H/W                 | 2         | 4      | 0.04%   |
| ASMT109x            | 2         | 2      | 0.04%   |
| USB 3.0             | 1         | 3      | 0.02%   |
| RSH-339             | 1         | 1      | 0.02%   |
| Phison              | 1         | 2      | 0.02%   |
| PHD 3.0             | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 1      | 0.02%   |
| Magnetic Data       | 1         | 1      | 0.02%   |
| KESU                | 1         | 1      | 0.02%   |
| IET                 | 1         | 1      | 0.02%   |
| IB-AC703            | 1         | 1      | 0.02%   |
| IB                  | 1         | 2      | 0.02%   |
| ExcelStor           | 1         | 1      | 0.02%   |
| ASMT106x            | 1         | 2      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1589      | 2585   | 26.47%  |
| Kingston            | 779       | 1071   | 12.98%  |
| Crucial             | 636       | 946    | 10.59%  |
| SanDisk             | 531       | 708    | 8.85%   |
| WDC                 | 361       | 507    | 6.01%   |
| A-DATA Technology   | 210       | 273    | 3.5%    |
| Intel               | 193       | 327    | 3.22%   |
| Micron Technology   | 126       | 160    | 2.1%    |
| China               | 122       | 156    | 2.03%   |
| SK hynix            | 99        | 117    | 1.65%   |
| Toshiba             | 97        | 133    | 1.62%   |
| Apple               | 86        | 100    | 1.43%   |
| LITEON              | 84        | 94     | 1.4%    |
| PNY                 | 82        | 110    | 1.37%   |
| SPCC                | 78        | 111    | 1.3%    |
| Transcend           | 60        | 85     | 1%      |
| Patriot             | 59        | 87     | 0.98%   |
| OCZ                 | 56        | 72     | 0.93%   |
| Corsair             | 46        | 64     | 0.77%   |
| LITEONIT            | 41        | 49     | 0.68%   |
| Intenso             | 34        | 41     | 0.57%   |
| Team                | 31        | 44     | 0.52%   |
| KingSpec            | 31        | 43     | 0.52%   |
| GOODRAM             | 31        | 50     | 0.52%   |
| Gigabyte Technology | 27        | 42     | 0.45%   |
| Plextor             | 26        | 36     | 0.43%   |
| Seagate             | 25        | 28     | 0.42%   |
| Netac               | 25        | 30     | 0.42%   |
| Apacer              | 25        | 40     | 0.42%   |
| Hewlett-Packard     | 20        | 22     | 0.33%   |
| Lexar               | 19        | 32     | 0.32%   |
| Unknown             | 18        | 18     | 0.3%    |
| KingDian            | 16        | 17     | 0.27%   |
| Mushkin             | 14        | 31     | 0.23%   |
| Leven               | 11        | 12     | 0.18%   |
| Verbatim            | 10        | 13     | 0.17%   |
| Unknown             | 10        | 13     | 0.17%   |
| AMD                 | 9         | 12     | 0.15%   |
| TO Exter            | 8         | 8      | 0.13%   |
| Dogfish             | 8         | 12     | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 5901      | 8842   | 36.26%  |
| SSD     | 5175      | 8644   | 31.8%   |
| HDD     | 4360      | 8487   | 26.79%  |
| MMC     | 598       | 834    | 3.67%   |
| Unknown | 242       | 326    | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 7399      | 16475  | 50.81%  |
| NVMe | 5881      | 8792   | 40.39%  |
| SAS  | 684       | 1032   | 4.7%    |
| MMC  | 598       | 834    | 4.11%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 5300      | 9091   | 52.28%  |
| 0.51-1.0   | 3241      | 5116   | 31.97%  |
| 1.01-2.0   | 875       | 1416   | 8.63%   |
| 3.01-4.0   | 297       | 556    | 2.93%   |
| 4.01-10.0  | 212       | 495    | 2.09%   |
| 2.01-3.0   | 180       | 375    | 1.78%   |
| 10.01-20.0 | 32        | 80     | 0.32%   |
| 0          | 1         | 2      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 501-1000       | 2522      | 19.92%  |
| 251-500        | 2491      | 19.67%  |
| 101-250        | 2044      | 16.14%  |
| 1001-2000      | 1697      | 13.4%   |
| 1-20           | 1104      | 8.72%   |
| More than 3000 | 829       | 6.55%   |
| Unknown        | 776       | 6.13%   |
| 2001-3000      | 504       | 3.98%   |
| 51-100         | 450       | 3.55%   |
| 21-50          | 245       | 1.93%   |
| 0              | 1         | 0.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3504      | 26.37%  |
| 21-50          | 2135      | 16.07%  |
| 101-250        | 1950      | 14.67%  |
| 51-100         | 1632      | 12.28%  |
| 251-500        | 1346      | 10.13%  |
| 501-1000       | 998       | 7.51%   |
| Unknown        | 776       | 5.84%   |
| 1001-2000      | 535       | 4.03%   |
| More than 3000 | 236       | 1.78%   |
| 2001-3000      | 173       | 1.3%    |
| 0              | 3         | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                | 18        | 43     | 2%      |
| Seagate ST500LT012-1DG142 500GB                | 14        | 14     | 1.56%   |
| HGST HTS721010A9E630 1TB                       | 11        | 14     | 1.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 10        | 20     | 1.11%   |
| Toshiba MQ01ABD100 1TB                         | 9         | 9      | 1%      |
| Seagate ST3500418AS 500GB                      | 8         | 16     | 0.89%   |
| Seagate ST31000524AS 1TB                       | 8         | 8      | 0.89%   |
| HGST HTS545050A7E680 500GB                     | 8         | 8      | 0.89%   |
| WDC WD10EZEX-00BN5A0 1TB                       | 7         | 7      | 0.78%   |
| Seagate ST9500325AS 500GB                      | 7         | 9      | 0.78%   |
| Seagate ST31000528AS 1TB                       | 7         | 9      | 0.78%   |
| Seagate ST1000LM035-1RK172 1TB                 | 7         | 7      | 0.78%   |
| Samsung Electronics SSD 870 EVO 1TB            | 7         | 9      | 0.78%   |
| HGST HTS541010A9E680 1TB                       | 7         | 7      | 0.78%   |
| Toshiba MQ01ABD050 500GB                       | 6         | 7      | 0.67%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 6         | 6      | 0.67%   |
| Toshiba MQ01ABD075 752GB                       | 5         | 5      | 0.56%   |
| Seagate ST500LM021-1KJ152 500GB                | 5         | 7      | 0.56%   |
| Seagate ST31500341AS 1TB                       | 5         | 5      | 0.56%   |
| Seagate ST1000DM010-2EP102 1TB                 | 5         | 5      | 0.56%   |
| Samsung Electronics SSD 870 EVO 500GB          | 5         | 9      | 0.56%   |
| Samsung Electronics HD322HJ 320GB              | 5         | 7      | 0.56%   |
| Kingston SV300S37A120G 120GB SSD               | 5         | 5      | 0.56%   |
| Intel SSDSC2CT120A3 120GB                      | 5         | 30     | 0.56%   |
| Hitachi HTS547575A9E384 752GB                  | 5         | 7      | 0.56%   |
| HGST HTS725050A7E630 500GB                     | 5         | 7      | 0.56%   |
| Crucial CT128MX100SSD1 128GB                   | 5         | 7      | 0.56%   |
| WDC WD10EZEX-08WN4A0 1TB                       | 4         | 5      | 0.44%   |
| WDC WD1002FAEX-00Z3A0 1TB                      | 4         | 4      | 0.44%   |
| Toshiba MQ01ABF050 500GB                       | 4         | 4      | 0.44%   |
| Seagate ST500LM012 HN-M500MBB 500GB            | 4         | 4      | 0.44%   |
| Seagate ST2000DM001-1CH164 2TB                 | 4         | 4      | 0.44%   |
| SanDisk SSD PLUS 480GB                         | 4         | 4      | 0.44%   |
| SanDisk SSD PLUS 240GB                         | 4         | 4      | 0.44%   |
| Samsung Electronics HD501LJ 500GB              | 4         | 31     | 0.44%   |
| LITEON CV8-8E128-HP 128GB SSD                  | 4         | 4      | 0.44%   |
| Hitachi HTS545050B9A300 500GB                  | 4         | 4      | 0.44%   |
| Crucial CT275MX300SSD1 275GB                   | 4         | 5      | 0.44%   |
| Crucial CT240M500SSD1 240GB                    | 4         | 4      | 0.44%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD               | 3         | 3      | 0.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 205       | 316    | 23.67%  |
| WDC                         | 167       | 240    | 19.28%  |
| Samsung Electronics         | 77        | 122    | 8.89%   |
| Toshiba                     | 68        | 74     | 7.85%   |
| Hitachi                     | 58        | 75     | 6.7%    |
| Intel                       | 37        | 76     | 4.27%   |
| HGST                        | 36        | 43     | 4.16%   |
| Crucial                     | 34        | 49     | 3.93%   |
| SanDisk                     | 30        | 32     | 3.46%   |
| Kingston                    | 23        | 26     | 2.66%   |
| SK hynix                    | 20        | 21     | 2.31%   |
| Micron Technology           | 17        | 20     | 1.96%   |
| A-DATA Technology           | 16        | 16     | 1.85%   |
| LITEON                      | 9         | 9      | 1.04%   |
| Maxtor                      | 7         | 7      | 0.81%   |
| Corsair                     | 6         | 9      | 0.69%   |
| SPCC                        | 5         | 6      | 0.58%   |
| Fujitsu                     | 5         | 5      | 0.58%   |
| OCZ                         | 4         | 5      | 0.46%   |
| OCZ-VERTEX3                 | 3         | 3      | 0.35%   |
| LITEONIT                    | 3         | 4      | 0.35%   |
| Intenso                     | 3         | 3      | 0.35%   |
| Apple                       | 3         | 3      | 0.35%   |
| Unknown                     | 2         | 2      | 0.23%   |
| PNY                         | 2         | 2      | 0.23%   |
| China                       | 2         | 2      | 0.23%   |
| YS                          | 1         | 1      | 0.12%   |
| walram                      | 1         | 1      | 0.12%   |
| Verbatim                    | 1         | 1      | 0.12%   |
| Union Memory                | 1         | 1      | 0.12%   |
| Teclast                     | 1         | 1      | 0.12%   |
| Team                        | 1         | 4      | 0.12%   |
| SSSTC                       | 1         | 1      | 0.12%   |
| SSD                         | 1         | 1      | 0.12%   |
| Plextor                     | 1         | 1      | 0.12%   |
| Origin                      | 1         | 1      | 0.12%   |
| ORICO                       | 1         | 1      | 0.12%   |
| MAXIO Technology (Hangzhou) | 1         | 1      | 0.12%   |
| Lenovo                      | 1         | 2      | 0.12%   |
| KingSpec                    | 1         | 1      | 0.12%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 205       | 316    | 35.71%  |
| WDC                 | 160       | 232    | 27.87%  |
| Toshiba             | 66        | 72     | 11.5%   |
| Hitachi             | 58        | 75     | 10.1%   |
| HGST                | 36        | 43     | 6.27%   |
| Samsung Electronics | 32        | 66     | 5.57%   |
| Maxtor              | 7         | 7      | 1.22%   |
| Fujitsu             | 5         | 5      | 0.87%   |
| HGST HTS            | 1         | 1      | 0.17%   |
| Hewlett-Packard     | 1         | 1      | 0.17%   |
| ASMT                | 1         | 1      | 0.17%   |
| ASMedia             | 1         | 1      | 0.17%   |
| Apple               | 1         | 1      | 0.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 539       | 821    | 65.18%  |
| SSD  | 245       | 331    | 29.63%  |
| NVMe | 43        | 47     | 5.2%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 980 500GB                | 2         | 3      | 13.33%  |
| WDC WD5000BEVT-00ZAT0 500GB                      | 1         | 2      | 6.67%   |
| WDC PC SN520 SDAPMUW-512G-1001 512GB             | 1         | 1      | 6.67%   |
| Toshiba THNSN5512GPUK NVMe 512GB                 | 1         | 1      | 6.67%   |
| Toshiba HDWD130 3TB                              | 1         | 1      | 6.67%   |
| SPCC M.2 PCIe SSD 2TB                            | 1         | 1      | 6.67%   |
| Seagate ST3320613AS 320GB                        | 1         | 1      | 6.67%   |
| Seagate ST31000528AS 1TB                         | 1         | 2      | 6.67%   |
| Seagate ST1000LM035-1RK172 1TB                   | 1         | 1      | 6.67%   |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 6.67%   |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 6.67%   |
| Samsung Electronics HD321HJ 320GB                | 1         | 2      | 6.67%   |
| Hitachi HDS721010DLE630 1TB                      | 1         | 6      | 6.67%   |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 6.67%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 5         | 7      | 33.33%  |
| Seagate             | 3         | 4      | 20%     |
| WDC                 | 2         | 3      | 13.33%  |
| Toshiba             | 2         | 2      | 13.33%  |
| SPCC                | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 6      | 6.67%   |
| HGST                | 1         | 1      | 6.67%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 7040      | 15475  | 53.4%   |
| Works    | 5332      | 10435  | 40.44%  |
| Malfunc  | 798       | 1199   | 6.05%   |
| Failed   | 14        | 24     | 0.11%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 6941      | 43.05%  |
| AMD                            | 2497      | 15.49%  |
| Samsung Electronics            | 2229      | 13.82%  |
| SanDisk                        | 993       | 6.16%   |
| SK hynix                       | 557       | 3.45%   |
| Toshiba America Info Systems   | 326       | 2.02%   |
| Phison Electronics             | 316       | 1.96%   |
| Kingston Technology Company    | 298       | 1.85%   |
| ASMedia Technology             | 263       | 1.63%   |
| Micron Technology              | 247       | 1.53%   |
| KIOXIA                         | 194       | 1.2%    |
| Micron/Crucial Technology      | 178       | 1.1%    |
| Silicon Motion                 | 147       | 0.91%   |
| ADATA Technology               | 147       | 0.91%   |
| Marvell Technology Group       | 140       | 0.87%   |
| JMicron Technology             | 95        | 0.59%   |
| Nvidia                         | 90        | 0.56%   |
| Realtek Semiconductor          | 58        | 0.36%   |
| Union Memory (Shenzhen)        | 51        | 0.32%   |
| Lite-On Technology             | 38        | 0.24%   |
| Solid State Storage Technology | 35        | 0.22%   |
| LSI Logic / Symbios Logic      | 35        | 0.22%   |
| Seagate Technology             | 31        | 0.19%   |
| MAXIO Technology (Hangzhou)    | 27        | 0.17%   |
| Broadcom / LSI                 | 27        | 0.17%   |
| Lenovo                         | 26        | 0.16%   |
| Apple                          | 22        | 0.14%   |
| Silicon Image                  | 13        | 0.08%   |
| Shenzhen Longsys Electronics   | 13        | 0.08%   |
| VIA Technologies               | 11        | 0.07%   |
| Yangtze Memory Technologies    | 10        | 0.06%   |
| Adaptec                        | 10        | 0.06%   |
| Netac Technology               | 9         | 0.06%   |
| Hewlett-Packard                | 8         | 0.05%   |
| Biwin Storage Technology       | 5         | 0.03%   |
| Solidigm                       | 4         | 0.02%   |
| Integrated Technology Express  | 4         | 0.02%   |
| INNOGRIT                       | 4         | 0.02%   |
| ULi Electronics                | 3         | 0.02%   |
| Lite-On IT Corp. / Plextor     | 3         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 1866      | 10.41%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 1155      | 6.44%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 768       | 4.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 461       | 2.57%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 442       | 2.47%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 424       | 2.36%   |
| AMD 400 Series Chipset SATA Controller                                         | 413       | 2.3%    |
| Samsung NVMe SSD Controller 980                                                | 401       | 2.24%   |
| Intel Volume Management Device NVMe RAID Controller                            | 400       | 2.23%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 322       | 1.8%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 314       | 1.75%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 264       | 1.47%   |
| AMD 500 Series Chipset SATA Controller                                         | 264       | 1.47%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 255       | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 251       | 1.4%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 251       | 1.4%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 244       | 1.36%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 243       | 1.36%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 228       | 1.27%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 210       | 1.17%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 210       | 1.17%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 200       | 1.12%   |
| Intel SATA Controller [RAID mode]                                              | 182       | 1.02%   |
| Intel Comet Lake SATA AHCI Controller                                          | 180       | 1%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 177       | 0.99%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 174       | 0.97%   |
| Intel SSD 660P Series                                                          | 173       | 0.96%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 173       | 0.96%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 167       | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 159       | 0.89%   |
| Phison E12 NVMe Controller                                                     | 157       | 0.88%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 154       | 0.86%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 154       | 0.86%   |
| Intel Tiger Lake-LP SATA Controller                                            | 135       | 0.75%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 134       | 0.75%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 123       | 0.69%   |
| AMD 300 Series Chipset SATA Controller                                         | 114       | 0.64%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 107       | 0.6%    |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 106       | 0.59%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 100       | 0.56%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 8137      | 51.06%  |
| NVMe | 5882      | 36.91%  |
| RAID | 1140      | 7.15%   |
| IDE  | 710       | 4.46%   |
| SAS  | 47        | 0.29%   |
| SCSI | 19        | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 8653      | 72.35%  |
| AMD                      | 3269      | 27.33%  |
| ARM                      | 32        | 0.27%   |
| Unknown                  | 3         | 0.03%   |
| QUALCOMM                 | 1         | 0.01%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.01%   |
| CentaurHauls             | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 204       | 1.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 201       | 1.68%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 181       | 1.51%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 176       | 1.47%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 144       | 1.2%    |
| AMD Ryzen 5 3600 6-Core Processor             | 134       | 1.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 131       | 1.09%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 125       | 1.04%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 124       | 1.03%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 120       | 1%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 119       | 0.99%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 118       | 0.98%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 111       | 0.93%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 100       | 0.83%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 98        | 0.82%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 96        | 0.8%    |
| Intel Core i5-6200U CPU @ 2.30GHz             | 95        | 0.79%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 94        | 0.78%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 83        | 0.69%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 78        | 0.65%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 78        | 0.65%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 76        | 0.63%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 75        | 0.63%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 74        | 0.62%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 73        | 0.61%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 71        | 0.59%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 71        | 0.59%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 69        | 0.58%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 67        | 0.56%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 67        | 0.56%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 66        | 0.55%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 66        | 0.55%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 65        | 0.54%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 65        | 0.54%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 64        | 0.53%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 63        | 0.53%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 61        | 0.51%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 56        | 0.47%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 55        | 0.46%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 55        | 0.46%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 2849      | 23.79%  |
| Intel Core i5           | 2662      | 22.23%  |
| Other                   | 1128      | 9.42%   |
| AMD Ryzen 5             | 1065      | 8.89%   |
| AMD Ryzen 7             | 870       | 7.26%   |
| Intel Core i3           | 663       | 5.54%   |
| AMD Ryzen 9             | 354       | 2.96%   |
| Intel Xeon              | 267       | 2.23%   |
| Intel Celeron           | 250       | 2.09%   |
| Intel Core 2 Duo        | 199       | 1.66%   |
| Intel Atom              | 187       | 1.56%   |
| Intel Pentium           | 151       | 1.26%   |
| AMD FX                  | 145       | 1.21%   |
| AMD Ryzen 3             | 129       | 1.08%   |
| Intel Core i9           | 117       | 0.98%   |
| AMD Ryzen 7 PRO         | 105       | 0.88%   |
| AMD Ryzen 5 PRO         | 67        | 0.56%   |
| AMD A10                 | 66        | 0.55%   |
| AMD A6                  | 62        | 0.52%   |
| AMD A8                  | 57        | 0.48%   |
| Intel Core 2 Quad       | 54        | 0.45%   |
| AMD Ryzen Threadripper  | 46        | 0.38%   |
| Intel Pentium Silver    | 39        | 0.33%   |
| Intel Pentium Dual-Core | 39        | 0.33%   |
| AMD Phenom II X4        | 39        | 0.33%   |
| AMD A4                  | 32        | 0.27%   |
| AMD Athlon              | 29        | 0.24%   |
| Intel Core 2            | 19        | 0.16%   |
| AMD Athlon II X2        | 19        | 0.16%   |
| AMD Phenom II X6        | 17        | 0.14%   |
| Intel Pentium Dual      | 15        | 0.13%   |
| Intel Core m3           | 15        | 0.13%   |
| AMD A12                 | 14        | 0.12%   |
| AMD Phenom              | 12        | 0.1%    |
| AMD Athlon 64 X2        | 12        | 0.1%    |
| Intel Genuine           | 11        | 0.09%   |
| Intel Core m5           | 11        | 0.09%   |
| AMD E1                  | 11        | 0.09%   |
| AMD E                   | 11        | 0.09%   |
| AMD Opteron             | 8         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 4841      | 40.41%  |
| 2       | 3318      | 27.7%   |
| 6       | 1623      | 13.55%  |
| 8       | 1342      | 11.2%   |
| 12      | 329       | 2.75%   |
| 16      | 148       | 1.24%   |
| 10      | 116       | 0.97%   |
| 14      | 96        | 0.8%    |
| 3       | 56        | 0.47%   |
| 1       | 55        | 0.46%   |
| 24      | 21        | 0.18%   |
| 32      | 12        | 0.1%    |
| Unknown | 9         | 0.08%   |
| 36      | 4         | 0.03%   |
| 20      | 4         | 0.03%   |
| 96      | 1         | 0.01%   |
| 72      | 1         | 0.01%   |
| 40      | 1         | 0.01%   |
| 28      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |
| 5       | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 11863     | 99.17%  |
| 2       | 87        | 0.73%   |
| Unknown | 9         | 0.08%   |
| 4       | 2         | 0.02%   |
| 3       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 9594      | 80.08%  |
| 1       | 2377      | 19.84%  |
| Unknown | 9         | 0.08%   |
| 4       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 11707     | 97.52%  |
| Unknown        | 283       | 2.36%   |
| 64-bit         | 11        | 0.09%   |
| 32-bit         | 4         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2078      | 16.82%  |
| 0x306a9    | 559       | 4.52%   |
| 0x306c3    | 503       | 4.07%   |
| 0x806ea    | 465       | 3.76%   |
| 0x806ec    | 460       | 3.72%   |
| 0x206a7    | 439       | 3.55%   |
| 0x806c1    | 420       | 3.4%    |
| 0x906ea    | 416       | 3.37%   |
| 0x806e9    | 349       | 2.82%   |
| 0x506e3    | 304       | 2.46%   |
| 0x406e3    | 301       | 2.44%   |
| 0x08701021 | 287       | 2.32%   |
| 0x0a50000c | 275       | 2.23%   |
| 0x906e9    | 266       | 2.15%   |
| 0x40651    | 232       | 1.88%   |
| 0x306d4    | 224       | 1.81%   |
| 0x08108109 | 191       | 1.55%   |
| 0x08600106 | 183       | 1.48%   |
| 0xa0652    | 167       | 1.35%   |
| 0x1067a    | 166       | 1.34%   |
| 0x0800820d | 162       | 1.31%   |
| 0x706e5    | 140       | 1.13%   |
| 0x08108102 | 134       | 1.08%   |
| 0x08701013 | 123       | 1%      |
| 0x08608103 | 123       | 1%      |
| 0x906ed    | 115       | 0.93%   |
| 0x20655    | 114       | 0.92%   |
| 0x906a3    | 103       | 0.83%   |
| 0x30678    | 100       | 0.81%   |
| 0x806eb    | 99        | 0.8%    |
| 0x08600104 | 97        | 0.79%   |
| 0x0a50000d | 86        | 0.7%    |
| 0x0a201016 | 86        | 0.7%    |
| 0x06000852 | 75        | 0.61%   |
| 0x406c4    | 74        | 0.6%    |
| 0x0810100b | 72        | 0.58%   |
| 0x0a404102 | 67        | 0.54%   |
| 0x0a201009 | 67        | 0.54%   |
| 0x08001138 | 63        | 0.51%   |
| 0x806d1    | 61        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 2663      | 22.22%  |
| Haswell          | 954       | 7.96%   |
| Zen 2            | 834       | 6.96%   |
| Skylake          | 745       | 6.22%   |
| IvyBridge        | 705       | 5.88%   |
| Zen 3            | 654       | 5.46%   |
| TigerLake        | 581       | 4.85%   |
| SandyBridge      | 561       | 4.68%   |
| Zen+             | 545       | 4.55%   |
| Unknown          | 413       | 3.45%   |
| Alderlake Hybrid | 355       | 2.96%   |
| CometLake        | 350       | 2.92%   |
| Zen              | 302       | 2.52%   |
| IceLake          | 293       | 2.45%   |
| Broadwell        | 281       | 2.34%   |
| Silvermont       | 278       | 2.32%   |
| Penryn           | 260       | 2.17%   |
| Westmere         | 211       | 1.76%   |
| Piledriver       | 186       | 1.55%   |
| K10              | 118       | 0.98%   |
| Goldmont plus    | 105       | 0.88%   |
| Core             | 102       | 0.85%   |
| Excavator        | 100       | 0.83%   |
| Nehalem          | 87        | 0.73%   |
| Goldmont         | 51        | 0.43%   |
| Puma             | 39        | 0.33%   |
| Steamroller      | 38        | 0.32%   |
| Bulldozer        | 27        | 0.23%   |
| Jaguar           | 26        | 0.22%   |
| K8 Hammer        | 25        | 0.21%   |
| Tremont          | 23        | 0.19%   |
| Bobcat           | 21        | 0.18%   |
| K10 Llano        | 17        | 0.14%   |
| Bonnell          | 15        | 0.13%   |
| NetBurst         | 8         | 0.07%   |
| K8 & K10 hybrid  | 5         | 0.04%   |
| P6               | 3         | 0.03%   |
| Gracemont        | 2         | 0.02%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 6999      | 47.97%  |
| Nvidia                           | 3986      | 27.32%  |
| AMD                              | 3541      | 24.27%  |
| Matrox Electronics Systems       | 31        | 0.21%   |
| ASPEED Technology                | 26        | 0.18%   |
| ATI Technologies                 | 3         | 0.02%   |
| Zhaoxin                          | 1         | 0.01%   |
| VIA Technologies                 | 1         | 0.01%   |
| Silicon Integrated Systems [SiS] | 1         | 0.01%   |
| S3 Graphics                      | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 532       | 3.57%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 528       | 3.54%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 407       | 2.73%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 395       | 2.65%   |
| AMD Renoir                                                                               | 387       | 2.59%   |
| Intel HD Graphics 620                                                                    | 370       | 2.48%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 359       | 2.41%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 339       | 2.27%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 333       | 2.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 329       | 2.2%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 313       | 2.1%    |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 306       | 2.05%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 291       | 1.95%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 272       | 1.82%   |
| Intel HD Graphics 630                                                                    | 225       | 1.51%   |
| Intel HD Graphics 530                                                                    | 225       | 1.51%   |
| Intel HD Graphics 5500                                                                   | 218       | 1.46%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 193       | 1.29%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 188       | 1.26%   |
| AMD Lucienne                                                                             | 169       | 1.13%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 168       | 1.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 166       | 1.11%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 144       | 0.97%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 143       | 0.96%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 135       | 0.9%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 133       | 0.89%   |
| Intel Core Processor Integrated Graphics Controller                                      | 123       | 0.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 120       | 0.8%    |
| AMD Rembrandt [Radeon 680M]                                                              | 116       | 0.78%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 115       | 0.77%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 114       | 0.76%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 107       | 0.72%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 104       | 0.7%    |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 99        | 0.66%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 97        | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 94        | 0.63%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                               | 89        | 0.6%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 88        | 0.59%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]                            | 79        | 0.53%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 78        | 0.52%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 4707      | 39.05%  |
| 1 x AMD                  | 2743      | 22.76%  |
| 1 x Nvidia               | 1826      | 15.15%  |
| Intel + Nvidia           | 1823      | 15.12%  |
| Intel + AMD              | 307       | 2.55%   |
| AMD + Nvidia             | 303       | 2.51%   |
| 2 x AMD                  | 188       | 1.56%   |
| Other                    | 41        | 0.34%   |
| 2 x Nvidia               | 27        | 0.22%   |
| 1 x Matrox               | 24        | 0.2%    |
| 2 x Intel                | 19        | 0.16%   |
| 1 x ASPEED               | 19        | 0.16%   |
| Nvidia + Matrox          | 5         | 0.04%   |
| Nvidia + ASPEED          | 3         | 0.02%   |
| Intel + 2 x Nvidia       | 3         | 0.02%   |
| AMD + ASPEED             | 3         | 0.02%   |
| Intel + AMD + 1 x Nvidia | 2         | 0.02%   |
| AMD + Matrox             | 2         | 0.02%   |
| 3 x AMD                  | 1         | 0.01%   |
| 2 x Nvidia + 1 x ASPEED  | 1         | 0.01%   |
| 1 x Zhaoxin              | 1         | 0.01%   |
| 1 x VIA                  | 1         | 0.01%   |
| 1 x SiS                  | 1         | 0.01%   |
| 1 x S3 Graphics          | 1         | 0.01%   |
| Intel + 2 x AMD          | 1         | 0.01%   |
| AMD + 2 x Nvidia         | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 9906      | 81.67%  |
| Proprietary | 1940      | 15.99%  |
| Unknown     | 284       | 2.34%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 6497      | 52.89%  |
| 1.01-2.0   | 1493      | 12.15%  |
| 0.01-0.5   | 1172      | 9.54%   |
| 3.01-4.0   | 955       | 7.77%   |
| 0.51-1.0   | 790       | 6.43%   |
| 7.01-8.0   | 741       | 6.03%   |
| 5.01-6.0   | 293       | 2.39%   |
| 8.01-16.0  | 240       | 1.95%   |
| 2.01-3.0   | 83        | 0.68%   |
| 16.01-24.0 | 20        | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 1598      | 11.22%  |
| Samsung Electronics     | 1461      | 10.26%  |
| BOE                     | 1423      | 9.99%   |
| Chimei Innolux          | 1261      | 8.86%   |
| LG Display              | 1204      | 8.46%   |
| Dell                    | 1095      | 7.69%   |
| Goldstar                | 869       | 6.1%    |
| Hewlett-Packard         | 449       | 3.15%   |
| Acer                    | 431       | 3.03%   |
| Sharp                   | 413       | 2.9%    |
| AOC                     | 374       | 2.63%   |
| BenQ                    | 356       | 2.5%    |
| Ancor Communications    | 300       | 2.11%   |
| Lenovo                  | 298       | 2.09%   |
| Philips                 | 290       | 2.04%   |
| Apple                   | 253       | 1.78%   |
| PANDA                   | 165       | 1.16%   |
| ViewSonic               | 160       | 1.12%   |
| Iiyama                  | 146       | 1.03%   |
| ASUSTek Computer        | 141       | 0.99%   |
| InfoVision              | 116       | 0.81%   |
| CSO                     | 107       | 0.75%   |
| Chi Mei Optoelectronics | 91        | 0.64%   |
| Sony                    | 69        | 0.48%   |
| MSI                     | 61        | 0.43%   |
| Sceptre Tech            | 55        | 0.39%   |
| Eizo                    | 51        | 0.36%   |
| Gigabyte Technology     | 50        | 0.35%   |
| Panasonic               | 44        | 0.31%   |
| Unknown                 | 42        | 0.29%   |
| HannStar                | 39        | 0.27%   |
| TMX                     | 37        | 0.26%   |
| NEC Computers           | 37        | 0.26%   |
| Vizio                   | 31        | 0.22%   |
| Toshiba                 | 29        | 0.2%    |
| Mi                      | 27        | 0.19%   |
| Fujitsu Siemens         | 26        | 0.18%   |
| Insignia                | 20        | 0.14%   |
| JDI                     | 19        | 0.13%   |
| RTK                     | 18        | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 84        | 0.57%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 65        | 0.44%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 62        | 0.42%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch       | 58        | 0.39%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 55        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 52        | 0.35%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 51        | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 50        | 0.34%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 45        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 45        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 41        | 0.28%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 39        | 0.26%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 38        | 0.26%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 310x170mm 13.9-inch       | 38        | 0.26%   |
| AU Optronics LCD Monitor AUO106C 1366x768 277x156mm 12.5-inch        | 38        | 0.26%   |
| AOC Q27G2SG4 AOC2702 2560x1440 597x336mm 27.0-inch                   | 38        | 0.26%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 37        | 0.25%   |
| BOE LCD Monitor BOE095F 2256x1504 285x190mm 13.5-inch                | 36        | 0.24%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch     | 35        | 0.24%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch             | 33        | 0.22%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                    | 33        | 0.22%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 31        | 0.21%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 31        | 0.21%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch    | 30        | 0.2%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 30        | 0.2%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 29        | 0.2%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 28        | 0.19%   |
| Panasonic LCD Monitor MEI96A2 2560x1440 309x173mm 13.9-inch          | 27        | 0.18%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 27        | 0.18%   |
| Goldstar LG HDR WFHD GSM7714 2560x1080 800x340mm 34.2-inch           | 27        | 0.18%   |
| BOE LCD Monitor BOE08D7 1920x1080 309x174mm 14.0-inch                | 27        | 0.18%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 25        | 0.17%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch             | 25        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch     | 25        | 0.17%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                | 25        | 0.17%   |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x194mm 15.5-inch       | 25        | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch    | 24        | 0.16%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 24        | 0.16%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 24        | 0.16%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 24        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 6472      | 48.73%  |
| 1366x768 (WXGA)    | 1667      | 12.55%  |
| 3840x2160 (4K)     | 1114      | 8.39%   |
| 2560x1440 (QHD)    | 977       | 7.36%   |
| 1920x1200 (WUXGA)  | 429       | 3.23%   |
| 1600x900 (HD+)     | 371       | 2.79%   |
| 1680x1050 (WSXGA+) | 234       | 1.76%   |
| 3440x1440          | 233       | 1.75%   |
| 1280x1024 (SXGA)   | 228       | 1.72%   |
| 2560x1080          | 191       | 1.44%   |
| 1440x900 (WXGA+)   | 186       | 1.4%    |
| 2560x1600          | 185       | 1.39%   |
| 1280x800 (WXGA)    | 130       | 0.98%   |
| 2880x1800          | 110       | 0.83%   |
| 1360x768           | 75        | 0.56%   |
| 3840x2400          | 66        | 0.5%    |
| 2160x1440          | 59        | 0.44%   |
| 3840x1080          | 46        | 0.35%   |
| 2256x1504          | 43        | 0.32%   |
| Unknown            | 42        | 0.32%   |
| 3200x1800 (QHD+)   | 37        | 0.28%   |
| 2736x1824          | 35        | 0.26%   |
| 1600x1200          | 28        | 0.21%   |
| 3000x2000          | 24        | 0.18%   |
| 1920x540           | 24        | 0.18%   |
| 1920x1280          | 24        | 0.18%   |
| 1024x768 (XGA)     | 24        | 0.18%   |
| 2288x1287          | 22        | 0.17%   |
| 3840x1600          | 14        | 0.11%   |
| 3200x2000          | 14        | 0.11%   |
| 2520x1680          | 13        | 0.1%    |
| 2240x1400          | 12        | 0.09%   |
| 3456x2160          | 11        | 0.08%   |
| 3072x1920          | 11        | 0.08%   |
| 1280x720 (HD)      | 11        | 0.08%   |
| 2160x1350          | 10        | 0.08%   |
| 2048x1152          | 10        | 0.08%   |
| 1280x960           | 7         | 0.05%   |
| 2880x1620          | 6         | 0.05%   |
| 2880x1920          | 5         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 3347      | 23.42%  |
| 13      | 1645      | 11.51%  |
| 27      | 1363      | 9.54%   |
| 14      | 1333      | 9.33%   |
| 24      | 1260      | 8.82%   |
| 23      | 881       | 6.17%   |
| 21      | 797       | 5.58%   |
| 17      | 498       | 3.48%   |
| 34      | 366       | 2.56%   |
| 31      | 362       | 2.53%   |
| 12      | 284       | 1.99%   |
| 19      | 260       | 1.82%   |
| 18      | 225       | 1.57%   |
| 22      | 186       | 1.3%    |
| 20      | 177       | 1.24%   |
| 16      | 173       | 1.21%   |
| Unknown | 165       | 1.15%   |
| 11      | 91        | 0.64%   |
| 84      | 84        | 0.59%   |
| 32      | 84        | 0.59%   |
| 25      | 76        | 0.53%   |
| 72      | 69        | 0.48%   |
| 40      | 64        | 0.45%   |
| 26      | 53        | 0.37%   |
| 54      | 47        | 0.33%   |
| 48      | 37        | 0.26%   |
| 28      | 36        | 0.25%   |
| 10      | 34        | 0.24%   |
| 42      | 30        | 0.21%   |
| 29      | 29        | 0.2%    |
| 35      | 28        | 0.2%    |
| 142     | 19        | 0.13%   |
| 37      | 18        | 0.13%   |
| 52      | 17        | 0.12%   |
| 49      | 14        | 0.1%    |
| 39      | 14        | 0.1%    |
| 36      | 14        | 0.1%    |
| 46      | 13        | 0.09%   |
| 65      | 12        | 0.08%   |
| 43      | 10        | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 5610      | 40.23%  |
| 501-600        | 3208      | 23.01%  |
| 401-500        | 1448      | 10.38%  |
| 201-300        | 1257      | 9.01%   |
| 351-400        | 679       | 4.87%   |
| 601-700        | 569       | 4.08%   |
| 701-800        | 472       | 3.38%   |
| 1501-2000      | 170       | 1.22%   |
| 1001-1500      | 165       | 1.18%   |
| Unknown        | 165       | 1.18%   |
| 801-900        | 127       | 0.91%   |
| 901-1000       | 50        | 0.36%   |
| More than 2000 | 21        | 0.15%   |
| 1-100          | 2         | 0.01%   |
| 101-200        | 1         | 0.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 9654      | 78.45%  |
| 16/10   | 1482      | 12.04%  |
| 21/9    | 426       | 3.46%   |
| 3/2     | 235       | 1.91%   |
| 5/4     | 222       | 1.8%    |
| Unknown | 99        | 0.8%    |
| 4/3     | 86        | 0.7%    |
| 32/9    | 42        | 0.34%   |
| 1.00    | 20        | 0.16%   |
| 6/5     | 16        | 0.13%   |
| 1.96    | 5         | 0.04%   |
| 3.40    | 4         | 0.03%   |
| 0.62    | 3         | 0.02%   |
| 0.89    | 2         | 0.02%   |
| 0.67    | 2         | 0.02%   |
| 3.88    | 1         | 0.01%   |
| 3.73    | 1         | 0.01%   |
| 3.33    | 1         | 0.01%   |
| 3.20    | 1         | 0.01%   |
| 2.12    | 1         | 0.01%   |
| 0.80    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |
| 0.45    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 3341      | 23.68%  |
| 201-250        | 2377      | 16.85%  |
| 81-90          | 2281      | 16.17%  |
| 301-350        | 1410      | 10%     |
| 351-500        | 878       | 6.22%   |
| 71-80          | 703       | 4.98%   |
| 151-200        | 682       | 4.83%   |
| 251-300        | 488       | 3.46%   |
| 121-130        | 391       | 2.77%   |
| More than 1000 | 297       | 2.11%   |
| 141-150        | 252       | 1.79%   |
| 61-70          | 248       | 1.76%   |
| 501-1000       | 217       | 1.54%   |
| Unknown        | 165       | 1.17%   |
| 111-120        | 164       | 1.16%   |
| 51-60          | 102       | 0.72%   |
| 131-140        | 47        | 0.33%   |
| 91-100         | 33        | 0.23%   |
| 41-50          | 27        | 0.19%   |
| 1-40           | 4         | 0.03%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 4320      | 31.65%  |
| 51-100        | 4031      | 29.54%  |
| 101-120       | 3050      | 22.35%  |
| 161-240       | 1282      | 9.39%   |
| More than 240 | 552       | 4.04%   |
| 1-50          | 248       | 1.82%   |
| Unknown       | 165       | 1.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 8927      | 72.13%  |
| 2     | 2657      | 21.47%  |
| 0     | 409       | 3.3%    |
| 3     | 342       | 2.76%   |
| 4     | 35        | 0.28%   |
| 5     | 7         | 0.06%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 6811      | 38.68%  |
| Realtek Semiconductor             | 6063      | 34.43%  |
| Qualcomm Atheros                  | 1551      | 8.81%   |
| Broadcom                          | 723       | 4.11%   |
| MediaTek                          | 374       | 2.12%   |
| TP-Link                           | 199       | 1.13%   |
| Ralink Technology                 | 146       | 0.83%   |
| Broadcom Limited                  | 133       | 0.76%   |
| Lenovo                            | 112       | 0.64%   |
| ASIX Electronics                  | 103       | 0.58%   |
| Ralink                            | 101       | 0.57%   |
| Marvell Technology Group          | 100       | 0.57%   |
| Sierra Wireless                   | 74        | 0.42%   |
| Nvidia                            | 71        | 0.4%    |
| Microsoft                         | 68        | 0.39%   |
| DisplayLink                       | 62        | 0.35%   |
| Samsung Electronics               | 60        | 0.34%   |
| Qualcomm                          | 59        | 0.34%   |
| Aquantia                          | 59        | 0.34%   |
| Xiaomi                            | 51        | 0.29%   |
| Dell                              | 51        | 0.29%   |
| ASUSTek Computer                  | 48        | 0.27%   |
| Qualcomm Atheros Communications   | 43        | 0.24%   |
| D-Link                            | 36        | 0.2%    |
| Huawei Technologies               | 34        | 0.19%   |
| Hewlett-Packard                   | 33        | 0.19%   |
| Ericsson Business Mobile Networks | 33        | 0.19%   |
| NetGear                           | 32        | 0.18%   |
| Google                            | 25        | 0.14%   |
| Apple                             | 24        | 0.14%   |
| Edimax Technology                 | 23        | 0.13%   |
| Linksys                           | 18        | 0.1%    |
| Mellanox Technologies             | 17        | 0.1%    |
| OPPO Electronics                  | 15        | 0.09%   |
| Motorola PCS                      | 15        | 0.09%   |
| D-Link System                     | 15        | 0.09%   |
| Fibocom                           | 14        | 0.08%   |
| JMicron Technology                | 11        | 0.06%   |
| ICS Advent                        | 11        | 0.06%   |
| OnePlus Technology (Shenzhen)     | 10        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4075      | 19.35%  |
| Intel Wi-Fi 6 AX200                                               | 913       | 4.33%   |
| Intel Wireless 8265 / 8275                                        | 573       | 2.72%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 512       | 2.43%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 485       | 2.3%    |
| Intel Wi-Fi 6 AX201                                               | 464       | 2.2%    |
| Intel I211 Gigabit Network Connection                             | 400       | 1.9%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 393       | 1.87%   |
| Realtek RTL8125 2.5GbE Controller                                 | 317       | 1.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 311       | 1.48%   |
| Intel Wireless 8260                                               | 308       | 1.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 296       | 1.41%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 281       | 1.33%   |
| Intel Wireless 7260                                               | 271       | 1.29%   |
| Intel Wireless 7265                                               | 268       | 1.27%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 250       | 1.19%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 242       | 1.15%   |
| Intel Ethernet Connection (2) I219-V                              | 231       | 1.1%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 222       | 1.05%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 219       | 1.04%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 201       | 0.95%   |
| Intel Ethernet Controller I225-V                                  | 197       | 0.94%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 196       | 0.93%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 196       | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 194       | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 191       | 0.91%   |
| Intel Wireless-AC 9260                                            | 183       | 0.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 179       | 0.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 176       | 0.84%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 173       | 0.82%   |
| Intel Wireless 3165                                               | 162       | 0.77%   |
| Intel Ethernet Connection I217-LM                                 | 153       | 0.73%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 151       | 0.72%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 140       | 0.66%   |
| Intel Ethernet Connection (7) I219-V                              | 125       | 0.59%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 123       | 0.58%   |
| Intel Ethernet Connection I219-LM                                 | 118       | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 114       | 0.54%   |
| Intel Ethernet Connection (4) I219-V                              | 112       | 0.53%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 103       | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 5585      | 54.66%  |
| Realtek Semiconductor                 | 1435      | 14.04%  |
| Qualcomm Atheros                      | 1264      | 12.37%  |
| Broadcom                              | 517       | 5.06%   |
| MediaTek                              | 366       | 3.58%   |
| TP-Link                               | 175       | 1.71%   |
| Ralink Technology                     | 146       | 1.43%   |
| Broadcom Limited                      | 102       | 1%      |
| Ralink                                | 101       | 0.99%   |
| Sierra Wireless                       | 74        | 0.72%   |
| Microsoft                             | 62        | 0.61%   |
| ASUSTek Computer                      | 45        | 0.44%   |
| Qualcomm Atheros Communications       | 43        | 0.42%   |
| Qualcomm                              | 40        | 0.39%   |
| Dell                                  | 37        | 0.36%   |
| Marvell Technology Group              | 34        | 0.33%   |
| NetGear                               | 30        | 0.29%   |
| D-Link                                | 27        | 0.26%   |
| Edimax Technology                     | 23        | 0.23%   |
| Linksys                               | 16        | 0.16%   |
| Fibocom                               | 14        | 0.14%   |
| D-Link System                         | 12        | 0.12%   |
| Ericsson Business Mobile Networks     | 11        | 0.11%   |
| Hewlett-Packard                       | 9         | 0.09%   |
| Belkin Components                     | 9         | 0.09%   |
| AVM                                   | 7         | 0.07%   |
| Wilocity                              | 6         | 0.06%   |
| IMC Networks                          | 4         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.03%   |
| ZyDAS                                 | 2         | 0.02%   |
| Xiaomi                                | 2         | 0.02%   |
| Sitecom Europe                        | 2         | 0.02%   |
| Quectel Wireless Solutions            | 2         | 0.02%   |
| BUFFALO                               | 2         | 0.02%   |
| AboCom Systems                        | 2         | 0.02%   |
| ZyXEL Communications                  | 1         | 0.01%   |
| ZTE WCDMA Technologies MSM            | 1         | 0.01%   |
| TRENDnet                              | 1         | 0.01%   |
| Toshiba                               | 1         | 0.01%   |
| Samsung Electronics                   | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 913       | 8.88%   |
| Intel Wireless 8265 / 8275                                     | 573       | 5.57%   |
| Intel Wi-Fi 6 AX201                                            | 464       | 4.51%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 311       | 3.02%   |
| Intel Wireless 8260                                            | 308       | 3%      |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 296       | 2.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 281       | 2.73%   |
| Intel Wireless 7260                                            | 271       | 2.64%   |
| Intel Wireless 7265                                            | 268       | 2.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 250       | 2.43%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 242       | 2.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 222       | 2.16%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 219       | 2.13%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 201       | 1.95%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 196       | 1.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 196       | 1.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 194       | 1.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 191       | 1.86%   |
| Intel Wireless-AC 9260                                         | 183       | 1.78%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 179       | 1.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 173       | 1.68%   |
| Intel Wireless 3165                                            | 162       | 1.58%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 151       | 1.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 140       | 1.36%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 123       | 1.2%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 103       | 1%      |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 96        | 0.93%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 92        | 0.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 92        | 0.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 86        | 0.84%   |
| Intel Wireless 3160                                            | 84        | 0.82%   |
| Broadcom BCM43142 802.11b/g/n                                  | 78        | 0.76%   |
| Intel Centrino Ultimate-N 6300                                 | 75        | 0.73%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 71        | 0.69%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 68        | 0.66%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 68        | 0.66%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 58        | 0.56%   |
| Ralink MT7601U Wireless Adapter                                | 55        | 0.53%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                    | 52        | 0.51%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 52        | 0.51%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 5416      | 52.49%  |
| Intel                                  | 3293      | 31.91%  |
| Qualcomm Atheros                       | 403       | 3.91%   |
| Broadcom                               | 316       | 3.06%   |
| Lenovo                                 | 110       | 1.07%   |
| ASIX Electronics                       | 103       | 1%      |
| Nvidia                                 | 71        | 0.69%   |
| Marvell Technology Group               | 66        | 0.64%   |
| DisplayLink                            | 62        | 0.6%    |
| Aquantia                               | 59        | 0.57%   |
| Xiaomi                                 | 49        | 0.47%   |
| Samsung Electronics                    | 48        | 0.47%   |
| Broadcom Limited                       | 31        | 0.3%    |
| TP-Link                                | 26        | 0.25%   |
| Google                                 | 25        | 0.24%   |
| Apple                                  | 24        | 0.23%   |
| Huawei Technologies                    | 21        | 0.2%    |
| Qualcomm                               | 19        | 0.18%   |
| OPPO Electronics                       | 15        | 0.15%   |
| Mellanox Technologies                  | 15        | 0.15%   |
| JMicron Technology                     | 11        | 0.11%   |
| ICS Advent                             | 11        | 0.11%   |
| Motorola PCS                           | 10        | 0.1%    |
| OnePlus Technology (Shenzhen)          | 9         | 0.09%   |
| Hewlett-Packard                        | 9         | 0.09%   |
| D-Link                                 | 9         | 0.09%   |
| MediaTek                               | 8         | 0.08%   |
| HMD Global                             | 6         | 0.06%   |
| Cypress Semiconductor                  | 6         | 0.06%   |
| Microsoft                              | 5         | 0.05%   |
| ZTE WCDMA Technologies MSM             | 4         | 0.04%   |
| VIA Technologies                       | 3         | 0.03%   |
| T & A Mobile Phones                    | 3         | 0.03%   |
| Sony Ericsson Mobile Communications AB | 3         | 0.03%   |
| MosChip Semiconductor                  | 3         | 0.03%   |
| D-Link System                          | 3         | 0.03%   |
| ASUSTek Computer                       | 3         | 0.03%   |
| ADMtek                                 | 3         | 0.03%   |
| 3Com                                   | 3         | 0.03%   |
| vivo                                   | 2         | 0.02%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 4075      | 38.37%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 512       | 4.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 485       | 4.57%   |
| Intel I211 Gigabit Network Connection                             | 400       | 3.77%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 393       | 3.7%    |
| Realtek RTL8125 2.5GbE Controller                                 | 317       | 2.98%   |
| Intel Ethernet Connection (2) I219-V                              | 231       | 2.17%   |
| Intel Ethernet Controller I225-V                                  | 197       | 1.85%   |
| Intel Ethernet Connection (4) I219-LM                             | 176       | 1.66%   |
| Intel Ethernet Connection I217-LM                                 | 153       | 1.44%   |
| Intel Ethernet Connection (7) I219-V                              | 125       | 1.18%   |
| Intel Ethernet Connection I219-LM                                 | 118       | 1.11%   |
| Intel Ethernet Connection (2) I219-LM                             | 114       | 1.07%   |
| Intel Ethernet Connection (4) I219-V                              | 112       | 1.05%   |
| Intel Ethernet Connection (6) I219-V                              | 99        | 0.93%   |
| ASIX AX88179 Gigabit Ethernet                                     | 92        | 0.87%   |
| Intel Ethernet Connection (7) I219-LM                             | 88        | 0.83%   |
| Intel Ethernet Connection I218-LM                                 | 82        | 0.77%   |
| Intel Ethernet Connection (10) I219-V                             | 81        | 0.76%   |
| Intel Ethernet Connection (3) I218-LM                             | 71        | 0.67%   |
| Intel Ethernet Connection (2) I218-V                              | 70        | 0.66%   |
| Intel 82579V Gigabit Network Connection                           | 66        | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 61        | 0.57%   |
| Intel Ethernet Connection I217-V                                  | 61        | 0.57%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 60        | 0.56%   |
| Intel Ethernet Connection (6) I219-LM                             | 59        | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 58        | 0.55%   |
| Intel 82574L Gigabit Network Connection                           | 57        | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 50        | 0.47%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 48        | 0.45%   |
| Intel I210 Gigabit Network Connection                             | 48        | 0.45%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 47        | 0.44%   |
| Intel 82577LM Gigabit Network Connection                          | 47        | 0.44%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 46        | 0.43%   |
| Intel Ethernet Connection I219-V                                  | 46        | 0.43%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 46        | 0.43%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 44        | 0.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 43        | 0.4%    |
| Lenovo ThinkPad TBT 3 Dock                                        | 42        | 0.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 38        | 0.36%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 9684      | 49.91%  |
| Ethernet | 9559      | 49.27%  |
| Modem    | 137       | 0.71%   |
| Unknown  | 22        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 7734      | 61.22%  |
| Ethernet | 4896      | 38.76%  |
| Modem    | 3         | 0.02%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 6327      | 52.61%  |
| 1     | 5026      | 41.79%  |
| 3     | 349       | 2.9%    |
| 0     | 243       | 2.02%   |
| 4     | 50        | 0.42%   |
| 5     | 17        | 0.14%   |
| 6     | 8         | 0.07%   |
| 8     | 4         | 0.03%   |
| 9     | 2         | 0.02%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 9828      | 80.33%  |
| Yes     | 2401      | 19.62%  |
| Unknown | 6         | 0.05%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 4811      | 56.2%   |
| Realtek Semiconductor           | 802       | 9.37%   |
| Qualcomm Atheros Communications | 581       | 6.79%   |
| Cambridge Silicon Radio         | 409       | 4.78%   |
| Broadcom                        | 328       | 3.83%   |
| IMC Networks                    | 299       | 3.49%   |
| Foxconn / Hon Hai               | 273       | 3.19%   |
| Apple                           | 259       | 3.03%   |
| Lite-On Technology              | 226       | 2.64%   |
| ASUSTek Computer                | 138       | 1.61%   |
| Realtek                         | 70        | 0.82%   |
| MediaTek                        | 66        | 0.77%   |
| Dell                            | 48        | 0.56%   |
| Marvell Semiconductor           | 35        | 0.41%   |
| Hewlett-Packard                 | 35        | 0.41%   |
| Ralink                          | 30        | 0.35%   |
| TP-Link                         | 28        | 0.33%   |
| Toshiba                         | 27        | 0.32%   |
| Foxconn International           | 13        | 0.15%   |
| USI                             | 12        | 0.14%   |
| Opticis                         | 9         | 0.11%   |
| Belkin Components               | 8         | 0.09%   |
| Edimax Technology               | 7         | 0.08%   |
| HTC (High Tech Computer)        | 6         | 0.07%   |
| Integrated System Solution      | 5         | 0.06%   |
| Smart Modular Technologies      | 4         | 0.05%   |
| Ralink Technology               | 4         | 0.05%   |
| Dynex                           | 4         | 0.05%   |
| Chicony Electronics             | 3         | 0.04%   |
| Alps Electric                   | 3         | 0.04%   |
| Taiyo Yuden                     | 2         | 0.02%   |
| SINO WEALTH                     | 2         | 0.02%   |
| Qcom                            | 2         | 0.02%   |
| Askey Computer                  | 2         | 0.02%   |
| Unknown                         | 2         | 0.02%   |
| Micro Star International        | 1         | 0.01%   |
| Kensington                      | 1         | 0.01%   |
| Fujitsu                         | 1         | 0.01%   |
| D-Link System                   | 1         | 0.01%   |
| D-Link                          | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 1539      | 17.95%  |
| Intel AX201 Bluetooth                               | 949       | 11.07%  |
| Intel AX200 Bluetooth                               | 879       | 10.25%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 649       | 7.57%   |
| Realtek Bluetooth Radio                             | 519       | 6.05%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 409       | 4.77%   |
| Qualcomm Atheros  Bluetooth Device                  | 328       | 3.83%   |
| Intel AX210 Bluetooth                               | 189       | 2.2%    |
| Realtek  Bluetooth 4.2 Adapter                      | 178       | 2.08%   |
| Intel Bluetooth Device                              | 176       | 2.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 167       | 1.95%   |
| Intel Wireless-AC 3168 Bluetooth                    | 167       | 1.95%   |
| Apple Bluetooth Host Controller                     | 122       | 1.42%   |
| IMC Networks Wireless_Device                        | 115       | 1.34%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 102       | 1.19%   |
| IMC Networks Bluetooth Radio                        | 92        | 1.07%   |
| Apple Bluetooth USB Host Controller                 | 86        | 1%      |
| Intel Centrino Bluetooth Wireless Transceiver       | 82        | 0.96%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 81        | 0.94%   |
| Foxconn / Hon Hai Bluetooth Device                  | 78        | 0.91%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 71        | 0.83%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 68        | 0.79%   |
| MediaTek Wireless_Device                            | 66        | 0.77%   |
| Realtek 802.11ac WLAN Adapter                       | 65        | 0.76%   |
| Foxconn / Hon Hai Wireless_Device                   | 58        | 0.68%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 56        | 0.65%   |
| Lite-On Bluetooth Device                            | 56        | 0.65%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 52        | 0.61%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 50        | 0.58%   |
| IMC Networks Bluetooth Device                       | 48        | 0.56%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 46        | 0.54%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 46        | 0.54%   |
| Broadcom BCM2045B (BDC-2.1)                         | 39        | 0.45%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 36        | 0.42%   |
| Ralink RT3290 Bluetooth                             | 30        | 0.35%   |
| TP-Link UB500 Adapter                               | 28        | 0.33%   |
| Lite-On Atheros AR3012 Bluetooth                    | 28        | 0.33%   |
| Marvell Bluetooth and Wireless LAN Composite        | 27        | 0.31%   |
| Lite-On Wireless_Device                             | 25        | 0.29%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 25        | 0.29%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 8303      | 47.38%  |
| AMD                         | 3835      | 21.88%  |
| Nvidia                      | 2885      | 16.46%  |
| C-Media Electronics         | 350       | 2%      |
| Logitech                    | 197       | 1.12%   |
| Lenovo                      | 133       | 0.76%   |
| Realtek Semiconductor       | 126       | 0.72%   |
| GN Netcom                   | 100       | 0.57%   |
| JMTek                       | 86        | 0.49%   |
| Creative Labs               | 86        | 0.49%   |
| Kingston Technology         | 74        | 0.42%   |
| SteelSeries ApS             | 70        | 0.4%    |
| Texas Instruments           | 68        | 0.39%   |
| Plantronics                 | 65        | 0.37%   |
| Creative Technology         | 64        | 0.37%   |
| Corsair                     | 64        | 0.37%   |
| Razer USA                   | 61        | 0.35%   |
| ASUSTek Computer            | 50        | 0.29%   |
| Generalplus Technology      | 48        | 0.27%   |
| Focusrite-Novation          | 47        | 0.27%   |
| Hewlett-Packard             | 37        | 0.21%   |
| Blue Microphones            | 35        | 0.2%    |
| Sony                        | 34        | 0.19%   |
| Samson Technologies         | 29        | 0.17%   |
| Dell                        | 26        | 0.15%   |
| GYROCOM C&C                 | 25        | 0.14%   |
| RODE Microphones            | 24        | 0.14%   |
| Micro Star International    | 22        | 0.13%   |
| XMOS                        | 20        | 0.11%   |
| Apple                       | 18        | 0.1%    |
| Cambridge Silicon Radio     | 17        | 0.1%    |
| Tenx Technology             | 16        | 0.09%   |
| Sennheiser Communications   | 15        | 0.09%   |
| Scarlett                    | 14        | 0.08%   |
| DSEA A/S                    | 14        | 0.08%   |
| Yamaha                      | 13        | 0.07%   |
| SAVITECH                    | 13        | 0.07%   |
| FiiO Electronics Technology | 13        | 0.07%   |
| Conexant Systems            | 13        | 0.07%   |
| VIA Technologies            | 12        | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 1571      | 7.45%   |
| Intel Sunrise Point-LP HD Audio                                            | 1314      | 6.23%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 862       | 4.09%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 679       | 3.22%   |
| AMD Starship/Matisse HD Audio Controller                                   | 668       | 3.17%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 580       | 2.75%   |
| Intel Cannon Lake PCH cAVS                                                 | 564       | 2.67%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 517       | 2.45%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 515       | 2.44%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 441       | 2.09%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 388       | 1.84%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 388       | 1.84%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 367       | 1.74%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 352       | 1.67%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 341       | 1.62%   |
| Intel Comet Lake PCH-LP cAVS                                               | 319       | 1.51%   |
| Nvidia GP107GL High Definition Audio Controller                            | 315       | 1.49%   |
| Intel Haswell-ULT HD Audio Controller                                      | 277       | 1.31%   |
| Intel 8 Series HD Audio Controller                                         | 277       | 1.31%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 268       | 1.27%   |
| Intel Comet Lake PCH cAVS                                                  | 261       | 1.24%   |
| Intel Broadwell-U Audio Controller                                         | 260       | 1.23%   |
| Intel 200 Series PCH HD Audio                                              | 255       | 1.21%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 251       | 1.19%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 243       | 1.15%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 237       | 1.12%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 227       | 1.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 227       | 1.08%   |
| AMD FCH Azalia Controller                                                  | 200       | 0.95%   |
| Nvidia GP106 High Definition Audio Controller                              | 194       | 0.92%   |
| AMD Navi 10 HDMI Audio                                                     | 184       | 0.87%   |
| Nvidia TU116 High Definition Audio Controller                              | 176       | 0.83%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 174       | 0.82%   |
| Nvidia TU106 High Definition Audio Controller                              | 169       | 0.8%    |
| Intel CM238 HD Audio Controller                                            | 165       | 0.78%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 156       | 0.74%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 155       | 0.73%   |
| Nvidia GP104 High Definition Audio Controller                              | 146       | 0.69%   |
| Nvidia GA104 High Definition Audio Controller                              | 144       | 0.68%   |
| Nvidia GA106 High Definition Audio Controller                              | 141       | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1637      | 23.24%  |
| SK hynix            | 1257      | 17.85%  |
| Micron Technology   | 825       | 11.71%  |
| Kingston            | 795       | 11.29%  |
| Unknown             | 470       | 6.67%   |
| Crucial             | 439       | 6.23%   |
| Corsair             | 421       | 5.98%   |
| G.Skill             | 294       | 4.17%   |
| A-DATA Technology   | 158       | 2.24%   |
| Ramaxel Technology  | 128       | 1.82%   |
| Team                | 64        | 0.91%   |
| Patriot             | 54        | 0.77%   |
| Elpida              | 54        | 0.77%   |
| Smart               | 43        | 0.61%   |
| Unknown             | 42        | 0.6%    |
| Unknown (ABCD)      | 41        | 0.58%   |
| Nanya Technology    | 36        | 0.51%   |
| GOODRAM             | 21        | 0.3%    |
| Transcend           | 18        | 0.26%   |
| Teikon              | 17        | 0.24%   |
| Avant               | 13        | 0.18%   |
| Smart Brazil        | 12        | 0.17%   |
| Silicon Power       | 11        | 0.16%   |
| PNY                 | 10        | 0.14%   |
| AMD                 | 10        | 0.14%   |
| GeIL                | 9         | 0.13%   |
| Apacer              | 9         | 0.13%   |
| Timetec             | 7         | 0.1%    |
| Goldkey             | 7         | 0.1%    |
| CSX                 | 7         | 0.1%    |
| Qumo                | 6         | 0.09%   |
| Qimonda             | 6         | 0.09%   |
| PUSKILL             | 5         | 0.07%   |
| V-GeN               | 4         | 0.06%   |
| Sesame              | 4         | 0.06%   |
| Kllisre             | 4         | 0.06%   |
| Gold Key            | 4         | 0.06%   |
| Unifosa             | 3         | 0.04%   |
| OnBoard             | 3         | 0.04%   |
| Mushkin             | 3         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 83        | 1.11%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 81        | 1.08%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 67        | 0.9%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 65        | 0.87%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 47        | 0.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 47        | 0.63%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 43        | 0.58%   |
| Unknown                                                          | 42        | 0.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 41        | 0.55%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 40        | 0.54%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 40        | 0.54%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 40        | 0.54%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 38        | 0.51%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 36        | 0.48%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 33        | 0.44%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 33        | 0.44%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 33        | 0.44%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 32        | 0.43%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 32        | 0.43%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 31        | 0.41%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 30        | 0.4%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 30        | 0.4%    |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 30        | 0.4%    |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 29        | 0.39%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 29        | 0.39%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 29        | 0.39%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 29        | 0.39%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 28        | 0.37%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 28        | 0.37%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 27        | 0.36%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 27        | 0.36%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 27        | 0.36%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 26        | 0.35%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 26        | 0.35%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 26        | 0.35%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 25        | 0.33%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 25        | 0.33%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 25        | 0.33%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 24        | 0.32%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 24        | 0.32%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind            | Computers | Percent |
|-----------------|-----------|---------|
| DDR4            | 3475      | 57.48%  |
| DDR3            | 1533      | 25.36%  |
| LPDDR4          | 278       | 4.6%    |
| LPDDR3          | 261       | 4.32%   |
| DDR2            | 116       | 1.92%   |
| DDR5            | 113       | 1.87%   |
| Unknown         | 104       | 1.72%   |
| LPDDR5          | 85        | 1.41%   |
| SDRAM           | 65        | 1.08%   |
| DDR             | 13        | 0.22%   |
| Logical non-vol | 2         | 0.03%   |
| DRAM            | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 3497      | 57.4%   |
| DIMM         | 1809      | 29.69%  |
| Row Of Chips | 689       | 11.31%  |
| Chip         | 60        | 0.98%   |
| Unknown      | 23        | 0.38%   |
| RIMM         | 9         | 0.15%   |
| FB-DIMM      | 4         | 0.07%   |
| DIP          | 1         | 0.02%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size   | Computers | Percent |
|--------|-----------|---------|
| 8192   | 2828      | 43.2%   |
| 4096   | 1548      | 23.64%  |
| 16384  | 1253      | 19.14%  |
| 2048   | 530       | 8.1%    |
| 32768  | 279       | 4.26%   |
| 1024   | 96        | 1.47%   |
| 512    | 5         | 0.08%   |
| 129408 | 2         | 0.03%   |
| 3072   | 2         | 0.03%   |
| 32767  | 1         | 0.02%   |
| 12288  | 1         | 0.02%   |
| 256    | 1         | 0.02%   |
| 64     | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 1311      | 20.11%  |
| 2667    | 1130      | 17.33%  |
| 1600    | 1007      | 15.45%  |
| 2400    | 479       | 7.35%   |
| 2133    | 417       | 6.4%    |
| 1333    | 309       | 4.74%   |
| 3600    | 209       | 3.21%   |
| 1867    | 160       | 2.45%   |
| 4267    | 148       | 2.27%   |
| 1334    | 116       | 1.78%   |
| 4800    | 91        | 1.4%    |
| 6400    | 88        | 1.35%   |
| 3266    | 81        | 1.24%   |
| 667     | 76        | 1.17%   |
| 800     | 74        | 1.14%   |
| Unknown | 63        | 0.97%   |
| 1067    | 56        | 0.86%   |
| 3400    | 53        | 0.81%   |
| 3000    | 53        | 0.81%   |
| 1066    | 49        | 0.75%   |
| 3733    | 46        | 0.71%   |
| 2666    | 35        | 0.54%   |
| 3800    | 33        | 0.51%   |
| 1866    | 30        | 0.46%   |
| 8400    | 29        | 0.44%   |
| 4266    | 29        | 0.44%   |
| 3866    | 26        | 0.4%    |
| 3533    | 26        | 0.4%    |
| 2933    | 26        | 0.4%    |
| 1800    | 26        | 0.4%    |
| 2800    | 25        | 0.38%   |
| 3466    | 22        | 0.34%   |
| 3666    | 16        | 0.25%   |
| 4199    | 15        | 0.23%   |
| 5200    | 10        | 0.15%   |
| 3333    | 8         | 0.12%   |
| 3100    | 8         | 0.12%   |
| 533     | 8         | 0.12%   |
| 5600    | 7         | 0.11%   |
| 3534    | 7         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 82        | 36.44%  |
| Brother Industries    | 50        | 22.22%  |
| Canon                 | 28        | 12.44%  |
| Samsung Electronics   | 20        | 8.89%   |
| Seiko Epson           | 18        | 8%      |
| Prolific Technology   | 7         | 3.11%   |
| Lexmark International | 4         | 1.78%   |
| Xerox                 | 2         | 0.89%   |
| Kyocera               | 2         | 0.89%   |
| Dymo-CoStar           | 2         | 0.89%   |
| STMicroelectronics    | 1         | 0.44%   |
| Star Micronics        | 1         | 0.44%   |
| Ricoh                 | 1         | 0.44%   |
| QinHeng Electronics   | 1         | 0.44%   |
| Pantum                | 1         | 0.44%   |
| NXP Semiconductors    | 1         | 0.44%   |
| MiiiW                 | 1         | 0.44%   |
| Graphtec America      | 1         | 0.44%   |
| Dell                  | 1         | 0.44%   |
| Boca Systems          | 1         | 0.44%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                                         | 7         | 3.1%    |
| Samsung M2070 Series                                                  | 6         | 2.65%   |
| HP LaserJet Professional P 1102w                                      | 4         | 1.77%   |
| HP ENVY 5000 series                                                   | 4         | 1.77%   |
| Brother Printer                                                       | 4         | 1.77%   |
| Brother HL-L2340D series                                              | 4         | 1.77%   |
| Seiko Epson Printer                                                   | 3         | 1.33%   |
| Samsung ML-216x Series Laser Printer                                  | 3         | 1.33%   |
| HP ENVY 4520 series                                                   | 3         | 1.33%   |
| HP DeskJet F300 series                                                | 3         | 1.33%   |
| HP DeskJet 3700 series                                                | 3         | 1.33%   |
| HP DeskJet 3630 series                                                | 3         | 1.33%   |
| HP DeskJet 2130 series                                                | 3         | 1.33%   |
| Brother HL-2030 Laser Printer                                         | 3         | 1.33%   |
| Brother HL-1110 series                                                | 3         | 1.33%   |
| Seiko Epson WF-2860 Series                                            | 2         | 0.88%   |
| HP OfficeJet 6950                                                     | 2         | 0.88%   |
| HP LaserJet Professional P1102w                                       | 2         | 0.88%   |
| HP LaserJet 1020                                                      | 2         | 0.88%   |
| HP LaserJet 1010                                                      | 2         | 0.88%   |
| HP Deskjet 3510 series                                                | 2         | 0.88%   |
| HP DeskJet 2620 All-in-One Printer                                    | 2         | 0.88%   |
| Canon TS3300 series                                                   | 2         | 0.88%   |
| Canon TR4500 series                                                   | 2         | 0.88%   |
| Canon CanoScan LiDE 300                                               | 2         | 0.88%   |
| Brother MFC-9330CDW                                                   | 2         | 0.88%   |
| Brother HL-5250DN Printer                                             | 2         | 0.88%   |
| Brother HL-2230 series                                                | 2         | 0.88%   |
| Brother HL-1440 Laser Printer                                         | 2         | 0.88%   |
| Xerox Phaser 6500DN                                                   | 1         | 0.44%   |
| Xerox Phaser 3010                                                     | 1         | 0.44%   |
| STMicroelectronics USB Printing Support                               | 1         | 0.44%   |
| Star Micronics TUP592 (STR_T-001)                                     | 1         | 0.44%   |
| Seiko Epson XP-100 Series                                             | 1         | 0.44%   |
| Seiko Epson WP-4020 Series                                            | 1         | 0.44%   |
| Seiko Epson WF-2830 Series                                            | 1         | 0.44%   |
| Seiko Epson WF-2510 Series                                            | 1         | 0.44%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 0.44%   |
| Seiko Epson ME 320/330 Series [Stylus SX125]                          | 1         | 0.44%   |
| Seiko Epson L360 Series                                               | 1         | 0.44%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 31        | 55.36%  |
| Seiko Epson     | 18        | 32.14%  |
| Hewlett-Packard | 5         | 8.93%   |
| UMAX            | 1         | 1.79%   |
| Mustek Systems  | 1         | 1.79%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X770 [Perfection V500]                    | 6         | 10.71%  |
| Canon CanoScan LiDE 210                                  | 6         | 10.71%  |
| Canon CanoScan LiDE 220                                  | 5         | 8.93%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 4         | 7.14%   |
| Canon CanoScan LIDE 25                                   | 3         | 5.36%   |
| Canon CanoScan LiDE 110                                  | 3         | 5.36%   |
| Canon CanoScan LiDE 100                                  | 3         | 5.36%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]              | 2         | 3.57%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]              | 2         | 3.57%   |
| Seiko Epson GT-6600U [Perfection 610]                    | 2         | 3.57%   |
| Canon CanoScan 4400F                                     | 2         | 3.57%   |
| UMAX Astra 2200/2200SU                                   | 1         | 1.79%   |
| Seiko Epson GT-X900 [Perfection V700/V750 Photo]         | 1         | 1.79%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]  | 1         | 1.79%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]              | 1         | 1.79%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 1         | 1.79%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]            | 1         | 1.79%   |
| Seiko Epson ES-D400 [GT-S80]                             | 1         | 1.79%   |
| Mustek Systems BearPaw 2448 TA Plus                      | 1         | 1.79%   |
| HP ScanJet G4050                                         | 1         | 1.79%   |
| HP ScanJet 5590                                          | 1         | 1.79%   |
| HP ScanJet 3400cse                                       | 1         | 1.79%   |
| HP Scanjet 300                                           | 1         | 1.79%   |
| HP ScanJet 2400c                                         | 1         | 1.79%   |
| Canon CanoScan N650U/N656U                               | 1         | 1.79%   |
| Canon CanoScan N1240U/LiDE 30                            | 1         | 1.79%   |
| Canon CanoScan LiDE 70                                   | 1         | 1.79%   |
| Canon CanoScan LiDE 200                                  | 1         | 1.79%   |
| Canon CanoScan LiDE 120                                  | 1         | 1.79%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1716      | 20.81%  |
| IMC Networks                           | 871       | 10.56%  |
| Microdia                               | 684       | 8.3%    |
| Logitech                               | 653       | 7.92%   |
| Realtek Semiconductor                  | 614       | 7.45%   |
| Quanta                                 | 444       | 5.39%   |
| Bison Electronics                      | 410       | 4.97%   |
| Sunplus Innovation Technology          | 390       | 4.73%   |
| Cheng Uei Precision Industry (Foxlink) | 292       | 3.54%   |
| Acer                                   | 284       | 3.44%   |
| Apple                                  | 255       | 3.09%   |
| Syntek                                 | 218       | 2.64%   |
| Lite-On Technology                     | 201       | 2.44%   |
| Luxvisions Innotech Limited            | 146       | 1.77%   |
| Microsoft                              | 114       | 1.38%   |
| Suyin                                  | 106       | 1.29%   |
| Silicon Motion                         | 78        | 0.95%   |
| Samsung Electronics                    | 78        | 0.95%   |
| Alcor Micro                            | 55        | 0.67%   |
| Sonix Technology                       | 53        | 0.64%   |
| Ricoh                                  | 39        | 0.47%   |
| Lenovo                                 | 30        | 0.36%   |
| KYE Systems (Mouse Systems)            | 28        | 0.34%   |
| SunplusIT                              | 27        | 0.33%   |
| Z-Star Microelectronics                | 24        | 0.29%   |
| Generalplus Technology                 | 24        | 0.29%   |
| Primax Electronics                     | 22        | 0.27%   |
| ARC International                      | 21        | 0.25%   |
| Creative Technology                    | 18        | 0.22%   |
| Importek                               | 17        | 0.21%   |
| Razer USA                              | 16        | 0.19%   |
| MacroSilicon                           | 16        | 0.19%   |
| Cubeternet                             | 13        | 0.16%   |
| Shenzhen Kingcome Optoelectronic       | 12        | 0.15%   |
| Jieli Technology                       | 12        | 0.15%   |
| AVerMedia Technologies                 | 12        | 0.15%   |
| 2M UVC CAMERA                          | 12        | 0.15%   |
| Intel                                  | 11        | 0.13%   |
| Hewlett-Packard                        | 11        | 0.13%   |
| icSpring                               | 9         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 582       | 6.97%   |
| Microdia Integrated_Webcam_HD                       | 360       | 4.31%   |
| IMC Networks Integrated Camera                      | 355       | 4.25%   |
| Realtek Integrated_Webcam_HD                        | 274       | 3.28%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 232       | 2.78%   |
| Syntek Integrated Camera                            | 155       | 1.86%   |
| Chicony HD WebCam                                   | 152       | 1.82%   |
| Sunplus Integrated_Webcam_HD                        | 151       | 1.81%   |
| Logitech HD Pro Webcam C920                         | 144       | 1.72%   |
| Logitech Webcam C270                                | 134       | 1.6%    |
| Acer Integrated Camera                              | 124       | 1.48%   |
| Bison Integrated Camera                             | 113       | 1.35%   |
| Chicony Integrated Camera (1280x720@30)             | 93        | 1.11%   |
| Quanta HD User Facing                               | 88        | 1.05%   |
| Lite-On Integrated Camera                           | 88        | 1.05%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 83        | 0.99%   |
| Samsung Galaxy series, misc. (MTP mode)             | 77        | 0.92%   |
| Chicony HP HD Camera                                | 75        | 0.9%    |
| Bison SunplusIT Integrated Camera                   | 70        | 0.84%   |
| Apple FaceTime HD Camera (Built-in)                 | 67        | 0.8%    |
| Chicony HP Wide Vision HD Camera                    | 63        | 0.75%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 62        | 0.74%   |
| Quanta HP TrueVision HD Camera                      | 55        | 0.66%   |
| Apple Built-in iSight                               | 55        | 0.66%   |
| IMC Networks HD Camera                              | 53        | 0.63%   |
| Realtek USB Camera                                  | 51        | 0.61%   |
| Quanta HP HD Camera                                 | 50        | 0.6%    |
| Chicony USB2.0 Camera                               | 48        | 0.57%   |
| Logitech C922 Pro Stream Webcam                     | 46        | 0.55%   |
| Quanta HD Webcam                                    | 45        | 0.54%   |
| Chicony HP TrueVision HD Camera                     | 45        | 0.54%   |
| Microdia Integrated Webcam                          | 44        | 0.53%   |
| Quanta HP Wide Vision HD Camera                     | 43        | 0.51%   |
| Chicony Integrated IR Camera                        | 43        | 0.51%   |
| Lite-On HP HD Camera                                | 41        | 0.49%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 41        | 0.49%   |
| Apple FaceTime HD Camera                            | 40        | 0.48%   |
| Microdia Webcam Vitade AF                           | 39        | 0.47%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 39        | 0.47%   |
| Chicony EasyCamera                                  | 39        | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 762       | 38.54%  |
| Validity Sensors                   | 542       | 27.42%  |
| Shenzhen Goodix Technology         | 346       | 17.5%   |
| Elan Microelectronics              | 123       | 6.22%   |
| Upek                               | 63        | 3.19%   |
| LighTuning Technology              | 61        | 3.09%   |
| AuthenTec                          | 39        | 1.97%   |
| Samsung Electronics                | 14        | 0.71%   |
| Realtek USB2.0 Finger Print Bridge | 12        | 0.61%   |
| STMicroelectronics                 | 5         | 0.25%   |
| Focal-systems.Corp                 | 4         | 0.2%    |
| DigitalPersona                     | 3         | 0.15%   |
| Dell                               | 2         | 0.1%    |
| Microsoft                          | 1         | 0.05%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 295       | 14.91%  |
| Shenzhen Goodix  Fingerprint Device                                        | 190       | 9.61%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 112       | 5.66%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 106       | 5.36%   |
| Shenzhen Goodix Fingerprint Reader                                         | 97        | 4.9%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 94        | 4.75%   |
| Validity Sensors Synaptics WBDI                                            | 73        | 3.69%   |
| Elan ELAN:Fingerprint                                                      | 67        | 3.39%   |
| Synaptics  WBDI                                                            | 61        | 3.08%   |
| Shenzhen Goodix FingerPrint                                                | 59        | 2.98%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 58        | 2.93%   |
| Synaptics WBDI                                                             | 55        | 2.78%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 54        | 2.73%   |
| Elan ELAN:ARM-M4                                                           | 51        | 2.58%   |
| Synaptics UWP WBDI                                                         | 46        | 2.33%   |
| Synaptics Fingerprint reader [HP G6]                                       | 44        | 2.22%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 42        | 2.12%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 33        | 1.67%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 31        | 1.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 29        | 1.47%   |
| Validity Sensors VFS491                                                    | 28        | 1.42%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 25        | 1.26%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 25        | 1.26%   |
| Synaptics UWP WBDI Device                                                  | 24        | 1.21%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 22        | 1.11%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 22        | 1.11%   |
| Validity Sensors Fingerprint scanner                                       | 18        | 0.91%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 16        | 0.81%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 15        | 0.76%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 15        | 0.76%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 14        | 0.71%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 12        | 0.61%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 12        | 0.61%   |
| AuthenTec Fingerprint Sensor                                               | 9         | 0.46%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 8         | 0.4%    |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 8         | 0.4%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 8         | 0.4%    |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 0.35%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 7         | 0.35%   |
| Samsung Fingerprint Device                                                 | 7         | 0.35%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 271       | 39.33%  |
| Alcor Micro                       | 269       | 39.04%  |
| Upek                              | 39        | 5.66%   |
| Lenovo                            | 33        | 4.79%   |
| O2 Micro                          | 14        | 2.03%   |
| Gemalto (was Gemplus)             | 10        | 1.45%   |
| Yubico.com                        | 9         | 1.31%   |
| Realtek Semiconductor             | 8         | 1.16%   |
| SCM Microsystems                  | 7         | 1.02%   |
| OmniKey                           | 7         | 1.02%   |
| VASCO Data Security International | 3         | 0.44%   |
| Aladdin Knowledge Systems         | 3         | 0.44%   |
| Reiner SCT Kartensysteme          | 2         | 0.29%   |
| Chicony Electronics               | 2         | 0.29%   |
| Aktiv                             | 2         | 0.29%   |
| Advanced Card Systems             | 2         | 0.29%   |
| Purism, SPC                       | 1         | 0.15%   |
| Hewlett-Packard                   | 1         | 0.15%   |
| Fujitsu Siemens Computers         | 1         | 0.15%   |
| Feitian Technologies              | 1         | 0.15%   |
| Clay Logic                        | 1         | 0.15%   |
| Cherry                            | 1         | 0.15%   |
| BIT4ID                            | 1         | 0.15%   |
| Athena Smartcard Solutions        | 1         | 0.15%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 266       | 38.61%  |
| Broadcom 5880                                                                | 84        | 12.19%  |
| Broadcom 58200                                                               | 83        | 12.05%  |
| Broadcom BCM5880 Secure Applications Processor                               | 58        | 8.42%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 44        | 6.39%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 39        | 5.66%   |
| Lenovo Integrated Smart Card Reader                                          | 32        | 4.64%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 11        | 1.6%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 8         | 1.16%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 7         | 1.02%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 6         | 0.87%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 4         | 0.58%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 4         | 0.58%   |
| OmniKey CardMan 1021                                                         | 3         | 0.44%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.44%   |
| Aladdin Knowledge Systems Token JC                                           | 3         | 0.44%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 2         | 0.29%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.29%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.29%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.29%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 0.29%   |
| Aktiv Rutoken lite                                                           | 2         | 0.29%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 0.15%   |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.15%   |
| VASCO Data Security International DIGIPASS 870                               | 1         | 0.15%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.15%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.15%   |
| SCM Microsystems CLOUD 2900 R Smart Card Reader                              | 1         | 0.15%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.15%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.15%   |
| Purism, SPC Librem Key                                                       | 1         | 0.15%   |
| OmniKey CardMan 4321                                                         | 1         | 0.15%   |
| OmniKey CardMan 3121 (HID Technologies)                                      | 1         | 0.15%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.15%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.15%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.15%   |
| Feitian Technologies FT SCR310                                               | 1         | 0.15%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.15%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 1         | 0.15%   |
| BIT4ID miniLector EVO                                                        | 1         | 0.15%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 8202      | 66.72%  |
| 1     | 3350      | 27.25%  |
| 2     | 608       | 4.95%   |
| 3     | 83        | 0.68%   |
| 4     | 20        | 0.16%   |
| 5     | 13        | 0.11%   |
| 6     | 8         | 0.07%   |
| 7     | 6         | 0.05%   |
| 8     | 3         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 1953      | 40.69%  |
| Graphics card            | 934       | 19.46%  |
| Multimedia controller    | 489       | 10.19%  |
| Net/wireless             | 484       | 10.08%  |
| Chipcard                 | 216       | 4.5%    |
| Camera                   | 174       | 3.63%   |
| Communication controller | 91        | 1.9%    |
| Bluetooth                | 91        | 1.9%    |
| Unassigned class         | 85        | 1.77%   |
| Sound                    | 69        | 1.44%   |
| Card reader              | 59        | 1.23%   |
| Storage                  | 53        | 1.1%    |
| Network                  | 34        | 0.71%   |
| Net/ethernet             | 26        | 0.54%   |
| Modem                    | 16        | 0.33%   |
| Storage/raid             | 12        | 0.25%   |
| Firewire controller      | 3         | 0.06%   |
| Dvb card                 | 3         | 0.06%   |
| Storage/ata              | 2         | 0.04%   |
| Flash memory             | 2         | 0.04%   |
| Wireless                 | 1         | 0.02%   |
| Video                    | 1         | 0.02%   |
| Tv card                  | 1         | 0.02%   |
| Storage/nvme             | 1         | 0.02%   |

