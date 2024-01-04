Peppermint - Tested Hardware & Statistics
-----------------------------------------

A project to collect tested hardware configurations for Peppermint.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Peppermint/Desktop/README.md) and [notebooks](/Dist/Peppermint/Notebook/README.md).

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

Total: 468

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 0T1D10 A01                  | Desktop     | [5fa41b15bb](https://linux-hardware.org/?probe=5fa41b15bb) | Dec 05, 2023 |
| Dell          | 0T1D10 A01                  | Desktop     | [65d5ddf61f](https://linux-hardware.org/?probe=65d5ddf61f) | Dec 05, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [aca11b8b22](https://linux-hardware.org/?probe=aca11b8b22) | Dec 04, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [bd6506d274](https://linux-hardware.org/?probe=bd6506d274) | Nov 30, 2023 |
| Acer          | Aspire E5-576G              | Notebook    | [cbce88f621](https://linux-hardware.org/?probe=cbce88f621) | Nov 26, 2023 |
| Acer          | Aspire E5-576G              | Notebook    | [3ce4659fcd](https://linux-hardware.org/?probe=3ce4659fcd) | Nov 25, 2023 |
| ASUSTek       | P5Q3 DELUXE                 | Desktop     | [7dbdce995b](https://linux-hardware.org/?probe=7dbdce995b) | Oct 07, 2023 |
| Toshiba       | Satellite C50-A-1DV         | Notebook    | [190ce47896](https://linux-hardware.org/?probe=190ce47896) | Oct 03, 2023 |
| Toshiba       | Satellite C50-A-1DV         | Notebook    | [791e483369](https://linux-hardware.org/?probe=791e483369) | Oct 03, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [c25a72c95a](https://linux-hardware.org/?probe=c25a72c95a) | Sep 27, 2023 |
| SiS           | M672 Board SI94B-20+SI96... | Notebook    | [4b309ad43c](https://linux-hardware.org/?probe=4b309ad43c) | Sep 02, 2023 |
| Packard Be... | EasyNote MZ36               | Notebook    | [d628db6497](https://linux-hardware.org/?probe=d628db6497) | Aug 21, 2023 |
| Dell          | Inspiron 15-3552            | Notebook    | [91d473eb35](https://linux-hardware.org/?probe=91d473eb35) | Aug 17, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [aa12dbe8bf](https://linux-hardware.org/?probe=aa12dbe8bf) | Jul 28, 2023 |
| Dell          | Latitude E6330              | Notebook    | [32dbf41885](https://linux-hardware.org/?probe=32dbf41885) | Jul 24, 2023 |
| HP            | 3032h                       | Desktop     | [f6a4202b21](https://linux-hardware.org/?probe=f6a4202b21) | Jul 21, 2023 |
| Lenovo        | ThinkPad Edge E430 3254T... | Notebook    | [2294cf035b](https://linux-hardware.org/?probe=2294cf035b) | Jul 16, 2023 |
| Lenovo        | ThinkPad Edge E430 3254T... | Notebook    | [b26a172e92](https://linux-hardware.org/?probe=b26a172e92) | Jul 16, 2023 |
| Dell          | Latitude E6400              | Notebook    | [a5af3e134e](https://linux-hardware.org/?probe=a5af3e134e) | Jun 30, 2023 |
| Medion        | BTDD-TI                     | All in one  | [64b84cf34d](https://linux-hardware.org/?probe=64b84cf34d) | Jun 29, 2023 |
| Foxconn       | Napa HP P/N                 | Desktop     | [df7eb832b4](https://linux-hardware.org/?probe=df7eb832b4) | Jun 20, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [0c5693c658](https://linux-hardware.org/?probe=0c5693c658) | Jun 18, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [a13bd80e8a](https://linux-hardware.org/?probe=a13bd80e8a) | Jun 01, 2023 |
| Foxconn       | Napa HP P/N                 | Desktop     | [a74b7b2a85](https://linux-hardware.org/?probe=a74b7b2a85) | May 28, 2023 |
| Acer          | E1-510                      | Notebook    | [709c32e016](https://linux-hardware.org/?probe=709c32e016) | May 21, 2023 |
| Acer          | E1-510                      | Notebook    | [c18f4ac56b](https://linux-hardware.org/?probe=c18f4ac56b) | May 21, 2023 |
| Google        | Banon                       | Notebook    | [c693655850](https://linux-hardware.org/?probe=c693655850) | Apr 04, 2023 |
| Google        | Kefka                       | Notebook    | [4817109a3d](https://linux-hardware.org/?probe=4817109a3d) | Mar 12, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [7996de313e](https://linux-hardware.org/?probe=7996de313e) | Jan 25, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [3f4e15d14a](https://linux-hardware.org/?probe=3f4e15d14a) | Jan 25, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [6b3bda5efe](https://linux-hardware.org/?probe=6b3bda5efe) | Jan 24, 2023 |
| Microsoft     | Surface Go 2                | Tablet      | [ae7da39556](https://linux-hardware.org/?probe=ae7da39556) | Jan 23, 2023 |
| Lenovo        | ThinkPad R500 2716W2K       | Notebook    | [ffe1ffc80e](https://linux-hardware.org/?probe=ffe1ffc80e) | Jan 23, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [2c8424ac3d](https://linux-hardware.org/?probe=2c8424ac3d) | Jan 22, 2023 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [9408c33828](https://linux-hardware.org/?probe=9408c33828) | Jan 14, 2023 |
| Lenovo        | ThinkPad X131e 33723FU      | Notebook    | [d2ee3f78a9](https://linux-hardware.org/?probe=d2ee3f78a9) | Jan 06, 2023 |
| Lenovo        | ThinkPad X131e 33723FU      | Notebook    | [9c9801b860](https://linux-hardware.org/?probe=9c9801b860) | Jan 06, 2023 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [6eed1ad6e5](https://linux-hardware.org/?probe=6eed1ad6e5) | Dec 29, 2022 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [ea64c817e2](https://linux-hardware.org/?probe=ea64c817e2) | Dec 28, 2022 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [b1c95f1d21](https://linux-hardware.org/?probe=b1c95f1d21) | Dec 28, 2022 |
| ASUSTek       | P5K SE/EPU                  | Desktop     | [6e816fc83e](https://linux-hardware.org/?probe=6e816fc83e) | Dec 24, 2022 |
| Acer          | AOA110                      | Notebook    | [560aa745c1](https://linux-hardware.org/?probe=560aa745c1) | Dec 14, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [87ecb2b41d](https://linux-hardware.org/?probe=87ecb2b41d) | Dec 07, 2022 |
| Lenovo        | 40684WG                     | Notebook    | [27e2eeccbf](https://linux-hardware.org/?probe=27e2eeccbf) | Nov 25, 2022 |
| Samsung       | SR70S/SR71S                 | Notebook    | [2e1f6c73da](https://linux-hardware.org/?probe=2e1f6c73da) | Nov 22, 2022 |
| HP            | Laptop 15-bs2xx             | Notebook    | [7c94d16c1c](https://linux-hardware.org/?probe=7c94d16c1c) | Oct 31, 2022 |
| ASUSTek       | LEUCITE3                    | Desktop     | [f51161d005](https://linux-hardware.org/?probe=f51161d005) | Oct 29, 2022 |
| ASUSTek       | LEUCITE3                    | Desktop     | [4c4e1b6871](https://linux-hardware.org/?probe=4c4e1b6871) | Oct 29, 2022 |
| Acer          | MCP7A                       | Desktop     | [c14a31f6ab](https://linux-hardware.org/?probe=c14a31f6ab) | Oct 28, 2022 |
| Dell          | 0RD203                      | Desktop     | [b427b55c0b](https://linux-hardware.org/?probe=b427b55c0b) | Oct 28, 2022 |
| Lenovo        | ThinkPad X230 232465G       | Notebook    | [4cfe90552b](https://linux-hardware.org/?probe=4cfe90552b) | Oct 24, 2022 |
| Google        | Swanky                      | Notebook    | [375d986028](https://linux-hardware.org/?probe=375d986028) | Oct 24, 2022 |
| Lenovo        | ThinkPad T60 1952CTO        | Notebook    | [f84f14587b](https://linux-hardware.org/?probe=f84f14587b) | Oct 17, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [a037b1ec8f](https://linux-hardware.org/?probe=a037b1ec8f) | Sep 24, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [0290975708](https://linux-hardware.org/?probe=0290975708) | Sep 24, 2022 |
| HP            | Compaq Presario CQ60        | Notebook    | [f6981692e0](https://linux-hardware.org/?probe=f6981692e0) | Sep 08, 2022 |
| Google        | Banon                       | Notebook    | [a54fd2e29b](https://linux-hardware.org/?probe=a54fd2e29b) | Sep 04, 2022 |
| Acer          | Aspire M5-581TG             | Notebook    | [03ec19b37d](https://linux-hardware.org/?probe=03ec19b37d) | Aug 23, 2022 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [92525ee03c](https://linux-hardware.org/?probe=92525ee03c) | Aug 17, 2022 |
| ASRock        | J4125B-ITX                  | Desktop     | [6e4ca6823f](https://linux-hardware.org/?probe=6e4ca6823f) | Aug 14, 2022 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [4ff9f1893d](https://linux-hardware.org/?probe=4ff9f1893d) | Aug 11, 2022 |
| Intel         | NUC6CAYB J23203-403         | Mini pc     | [91438d7bdd](https://linux-hardware.org/?probe=91438d7bdd) | Aug 06, 2022 |
| HP            | Compaq 2510p                | Notebook    | [b61ccedd14](https://linux-hardware.org/?probe=b61ccedd14) | Jul 31, 2022 |
| Dell          | Latitude E6430              | Notebook    | [c6f235793c](https://linux-hardware.org/?probe=c6f235793c) | Jul 25, 2022 |
| Dell          | Inspiron 1545               | Notebook    | [893377b9f7](https://linux-hardware.org/?probe=893377b9f7) | Jul 23, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [e67924ef34](https://linux-hardware.org/?probe=e67924ef34) | Jul 19, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [33266494dc](https://linux-hardware.org/?probe=33266494dc) | Jul 19, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [7177bb644a](https://linux-hardware.org/?probe=7177bb644a) | Jul 15, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [36851c847b](https://linux-hardware.org/?probe=36851c847b) | Jul 08, 2022 |
| Sony          | VPCEA36FM                   | Notebook    | [3e993cbd4b](https://linux-hardware.org/?probe=3e993cbd4b) | Jul 06, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [2791443b0d](https://linux-hardware.org/?probe=2791443b0d) | Jun 22, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [fe963bacc6](https://linux-hardware.org/?probe=fe963bacc6) | Jun 14, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [3de14e06c5](https://linux-hardware.org/?probe=3de14e06c5) | Jun 08, 2022 |
| HP            | Laptop 17-by4xxx            | Notebook    | [4b63d98b33](https://linux-hardware.org/?probe=4b63d98b33) | May 16, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [244ed30771](https://linux-hardware.org/?probe=244ed30771) | May 04, 2022 |
| Dell          | Inspiron 3421               | Notebook    | [15a2c261da](https://linux-hardware.org/?probe=15a2c261da) | Apr 29, 2022 |
| Lenovo        | G575 4383                   | Notebook    | [2f6fdef961](https://linux-hardware.org/?probe=2f6fdef961) | Apr 27, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [ca95a8324a](https://linux-hardware.org/?probe=ca95a8324a) | Apr 02, 2022 |
| HP            | EliteBook 830 G5            | Notebook    | [271af2d869](https://linux-hardware.org/?probe=271af2d869) | Mar 30, 2022 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [d08bb2f15b](https://linux-hardware.org/?probe=d08bb2f15b) | Mar 25, 2022 |
| Packard Be... | EasyNote_MX45               | Notebook    | [b7444c471c](https://linux-hardware.org/?probe=b7444c471c) | Mar 21, 2022 |
| Packard Be... | EasyNote_MX45               | Notebook    | [1fbe976538](https://linux-hardware.org/?probe=1fbe976538) | Mar 21, 2022 |
| Packard Be... | EasyNote_MX45               | Notebook    | [b664a23750](https://linux-hardware.org/?probe=b664a23750) | Mar 21, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [f3e67de15e](https://linux-hardware.org/?probe=f3e67de15e) | Mar 20, 2022 |
| ASRock        | N68-S3 FX                   | Desktop     | [78676e017b](https://linux-hardware.org/?probe=78676e017b) | Mar 19, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [b8783a8415](https://linux-hardware.org/?probe=b8783a8415) | Mar 12, 2022 |
| Dell          | Inspiron 1525               | Notebook    | [b0d58c6895](https://linux-hardware.org/?probe=b0d58c6895) | Mar 12, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [bedf7835b0](https://linux-hardware.org/?probe=bedf7835b0) | Feb 08, 2022 |
| Dell          | Latitude D630               | Notebook    | [66fe60e209](https://linux-hardware.org/?probe=66fe60e209) | Feb 04, 2022 |
| Dell          | Latitude D630               | Notebook    | [c4b7202805](https://linux-hardware.org/?probe=c4b7202805) | Feb 01, 2022 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [a7209bb34a](https://linux-hardware.org/?probe=a7209bb34a) | Jan 22, 2022 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [5f7c38d0d5](https://linux-hardware.org/?probe=5f7c38d0d5) | Jan 22, 2022 |
| Medion        | WIM2160                     | Notebook    | [5e529f33bc](https://linux-hardware.org/?probe=5e529f33bc) | Jan 15, 2022 |
| Medion        | WIM2160                     | Notebook    | [758e2a7717](https://linux-hardware.org/?probe=758e2a7717) | Jan 15, 2022 |
| ASUSTek       | 1000HE                      | Notebook    | [3cdc62c355](https://linux-hardware.org/?probe=3cdc62c355) | Jan 05, 2022 |
| Acer          | AOA110                      | Notebook    | [1670ad4a71](https://linux-hardware.org/?probe=1670ad4a71) | Dec 29, 2021 |
| ASUSTek       | 1000H                       | Notebook    | [7b25815657](https://linux-hardware.org/?probe=7b25815657) | Dec 29, 2021 |
| Lenovo        | G575 4383                   | Notebook    | [ef4143d3b6](https://linux-hardware.org/?probe=ef4143d3b6) | Dec 22, 2021 |
| Fujitsu Si... | AMILO PRO V8010             | Notebook    | [710a87fb41](https://linux-hardware.org/?probe=710a87fb41) | Dec 18, 2021 |
| Toshiba       | Satellite L300              | Notebook    | [1a2930b22b](https://linux-hardware.org/?probe=1a2930b22b) | Dec 02, 2021 |
| Intel         | D865GSA AAD52278-203        | Desktop     | [9b874becf9](https://linux-hardware.org/?probe=9b874becf9) | Dec 01, 2021 |
| Intel         | D865GSA AAD52278-203        | Desktop     | [ae2963be56](https://linux-hardware.org/?probe=ae2963be56) | Dec 01, 2021 |
| Acer          | Aspire 4810T                | Notebook    | [2f0aa07be8](https://linux-hardware.org/?probe=2f0aa07be8) | Nov 26, 2021 |
| ECS           | 945GCT-M3                   | Desktop     | [a81a27ac47](https://linux-hardware.org/?probe=a81a27ac47) | Nov 25, 2021 |
| Positivo      | Mobile                      | Notebook    | [f67e7cf244](https://linux-hardware.org/?probe=f67e7cf244) | Nov 25, 2021 |
| Positivo      | Mobile                      | Notebook    | [aa89357d9f](https://linux-hardware.org/?probe=aa89357d9f) | Nov 25, 2021 |
| ECS           | Nettle3                     | Desktop     | [844a70698a](https://linux-hardware.org/?probe=844a70698a) | Nov 21, 2021 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [def67fa4e7](https://linux-hardware.org/?probe=def67fa4e7) | Nov 16, 2021 |
| Dell          | Inspiron 1750               | Notebook    | [58d4a2dd00](https://linux-hardware.org/?probe=58d4a2dd00) | Nov 10, 2021 |
| HP            | Compaq nc6320 (RH377ET#A... | Notebook    | [15f9885d1f](https://linux-hardware.org/?probe=15f9885d1f) | Nov 02, 2021 |
| ASUSTek       | N73SV                       | Notebook    | [997a879973](https://linux-hardware.org/?probe=997a879973) | Oct 29, 2021 |
| Intel         | H61                         | Desktop     | [f1d3a975c0](https://linux-hardware.org/?probe=f1d3a975c0) | Oct 26, 2021 |
| Toshiba       | Satellite L750D             | Notebook    | [e24684255d](https://linux-hardware.org/?probe=e24684255d) | Oct 26, 2021 |
| HP            | Pavilion dv2000 (RD261LA... | Notebook    | [9f722a52d9](https://linux-hardware.org/?probe=9f722a52d9) | Oct 15, 2021 |
| ECS           | MCP61PM-GM                  | Desktop     | [1d13b80285](https://linux-hardware.org/?probe=1d13b80285) | Oct 13, 2021 |
| ASRock        | P4VM8                       | Desktop     | [5797c27ef8](https://linux-hardware.org/?probe=5797c27ef8) | Oct 10, 2021 |
| ASRock        | P4VM8                       | Desktop     | [84c50aca4b](https://linux-hardware.org/?probe=84c50aca4b) | Oct 10, 2021 |
| Dell          | Inspiron 1018               | Notebook    | [7f51bdb2d1](https://linux-hardware.org/?probe=7f51bdb2d1) | Oct 08, 2021 |
| HP            | 2000                        | Notebook    | [00f01e8929](https://linux-hardware.org/?probe=00f01e8929) | Oct 08, 2021 |
| Dell          | Inspiron 1750               | Notebook    | [be79dd5979](https://linux-hardware.org/?probe=be79dd5979) | Oct 06, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [c5492b6d2f](https://linux-hardware.org/?probe=c5492b6d2f) | Oct 06, 2021 |
| AAEON         | MF-001 V1.0                 | Desktop     | [522a137a4e](https://linux-hardware.org/?probe=522a137a4e) | Oct 05, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [7716dd2a46](https://linux-hardware.org/?probe=7716dd2a46) | Sep 30, 2021 |
| HP            | 15                          | Notebook    | [a976f1d357](https://linux-hardware.org/?probe=a976f1d357) | Sep 28, 2021 |
| MSI           | MS-7211                     | Desktop     | [bb7e83b8cb](https://linux-hardware.org/?probe=bb7e83b8cb) | Sep 25, 2021 |
| Unknown       | Unknown                     | Notebook    | [b54d6779c8](https://linux-hardware.org/?probe=b54d6779c8) | Sep 19, 2021 |
| ASUSTek       | A88XM-A                     | Desktop     | [b1f8d57cae](https://linux-hardware.org/?probe=b1f8d57cae) | Sep 09, 2021 |
| Packard Be... | EasyNote TK85               | Notebook    | [3e9c16c5a0](https://linux-hardware.org/?probe=3e9c16c5a0) | Sep 07, 2021 |
| Toshiba       | dynabook Satellite B552/... | Notebook    | [9532ae1c30](https://linux-hardware.org/?probe=9532ae1c30) | Sep 05, 2021 |
| ASUSTek       | K52F                        | Notebook    | [743e5c8059](https://linux-hardware.org/?probe=743e5c8059) | Sep 01, 2021 |
| ASUSTek       | K52F                        | Notebook    | [54d5076bc6](https://linux-hardware.org/?probe=54d5076bc6) | Sep 01, 2021 |
| Sony          | VGN-S55B_S                  | Notebook    | [f8237269e1](https://linux-hardware.org/?probe=f8237269e1) | Aug 22, 2021 |
| Packard Be... | EasyNote TK85               | Notebook    | [4faeb04124](https://linux-hardware.org/?probe=4faeb04124) | Aug 17, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [830eaafeac](https://linux-hardware.org/?probe=830eaafeac) | Aug 08, 2021 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [0a9b2f9147](https://linux-hardware.org/?probe=0a9b2f9147) | Aug 08, 2021 |
| HP            | 2AE3                        | Desktop     | [6780c45f7c](https://linux-hardware.org/?probe=6780c45f7c) | Aug 02, 2021 |
| Olivetti      | CL133A                      | Notebook    | [59d8296ec4](https://linux-hardware.org/?probe=59d8296ec4) | Jul 31, 2021 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | Notebook    | [113c8ab052](https://linux-hardware.org/?probe=113c8ab052) | Jul 27, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [827993d9c3](https://linux-hardware.org/?probe=827993d9c3) | Jul 17, 2021 |
| Olivetti      | CL133A                      | Notebook    | [a73133e4f3](https://linux-hardware.org/?probe=a73133e4f3) | Jul 15, 2021 |
| Dell          | Precision M4600             | Notebook    | [0242a479d2](https://linux-hardware.org/?probe=0242a479d2) | Jul 13, 2021 |
| Olivetti      | CL133A                      | Notebook    | [ba8eb5f003](https://linux-hardware.org/?probe=ba8eb5f003) | Jul 10, 2021 |
| Olivetti      | CL133A                      | Notebook    | [117e8fa0b4](https://linux-hardware.org/?probe=117e8fa0b4) | Jul 06, 2021 |
| Pegatron      | 2ACC                        | Desktop     | [271f50a6ed](https://linux-hardware.org/?probe=271f50a6ed) | Jun 29, 2021 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [9ba35acb61](https://linux-hardware.org/?probe=9ba35acb61) | Jun 24, 2021 |
| HP            | Compaq Mini 110c-1100       | Notebook    | [399e422d5b](https://linux-hardware.org/?probe=399e422d5b) | Jun 24, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [09171395a9](https://linux-hardware.org/?probe=09171395a9) | Jun 22, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [cdbc4c8c02](https://linux-hardware.org/?probe=cdbc4c8c02) | Jun 22, 2021 |
| Toshiba       | NB500                       | Notebook    | [e5095d1545](https://linux-hardware.org/?probe=e5095d1545) | Jun 21, 2021 |
| Lenovo        | ThinkPad Edge E431 62775... | Notebook    | [6d6430f8ff](https://linux-hardware.org/?probe=6d6430f8ff) | Jun 18, 2021 |
| Acer          | AOA150                      | Notebook    | [7cbadcfcce](https://linux-hardware.org/?probe=7cbadcfcce) | Jun 13, 2021 |
| Toshiba       | NB500                       | Notebook    | [0a57436b83](https://linux-hardware.org/?probe=0a57436b83) | Jun 13, 2021 |
| Toshiba       | NB500                       | Notebook    | [be659779e6](https://linux-hardware.org/?probe=be659779e6) | Jun 13, 2021 |
| HP            | Mini 110-1100               | Notebook    | [dcaac9d2ce](https://linux-hardware.org/?probe=dcaac9d2ce) | Jun 04, 2021 |
| HP            | Mini 110-1100               | Notebook    | [d919b139c6](https://linux-hardware.org/?probe=d919b139c6) | Jun 04, 2021 |
| LincPlus      | P1                          | Notebook    | [4b49a81a7c](https://linux-hardware.org/?probe=4b49a81a7c) | May 30, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [9c2c0af05f](https://linux-hardware.org/?probe=9c2c0af05f) | May 27, 2021 |
| ASRock        | 970M Pro3                   | Desktop     | [0a5e45a21e](https://linux-hardware.org/?probe=0a5e45a21e) | May 27, 2021 |
| HP            | Presario C500 (RZ343UA#A... | Notebook    | [d37099a83d](https://linux-hardware.org/?probe=d37099a83d) | May 25, 2021 |
| HP            | Presario C500 (RZ343UA#A... | Notebook    | [4aef9f472c](https://linux-hardware.org/?probe=4aef9f472c) | May 17, 2021 |
| LincPlus      | P1                          | Notebook    | [bac5471f0f](https://linux-hardware.org/?probe=bac5471f0f) | May 15, 2021 |
| JPSaCouto     | Intel powered classmate ... | Notebook    | [f82c8e8839](https://linux-hardware.org/?probe=f82c8e8839) | Apr 25, 2021 |
| JPSaCouto     | Intel powered classmate ... | Notebook    | [bcca68ee1a](https://linux-hardware.org/?probe=bcca68ee1a) | Apr 25, 2021 |
| Acer          | Extensa 5510                | Notebook    | [8e9e536486](https://linux-hardware.org/?probe=8e9e536486) | Apr 24, 2021 |
| Gateway       | Blade-K8F                   | Notebook    | [12b76c8bca](https://linux-hardware.org/?probe=12b76c8bca) | Apr 24, 2021 |
| HP            | EliteBook 2530p             | Notebook    | [d54424038e](https://linux-hardware.org/?probe=d54424038e) | Apr 18, 2021 |
| HP            | EliteBook 2530p             | Notebook    | [562d38cca5](https://linux-hardware.org/?probe=562d38cca5) | Apr 18, 2021 |
| HP            | Compaq nc6320 (RH377ET#A... | Notebook    | [87befc0401](https://linux-hardware.org/?probe=87befc0401) | Apr 16, 2021 |
| Pegatron      | Benicia                     | Desktop     | [7b1f7c7edf](https://linux-hardware.org/?probe=7b1f7c7edf) | Apr 15, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [a23936a0de](https://linux-hardware.org/?probe=a23936a0de) | Apr 10, 2021 |
| Fujitsu Si... | AMILO Li1705                | Notebook    | [56c5cc70d1](https://linux-hardware.org/?probe=56c5cc70d1) | Apr 07, 2021 |
| Fujitsu Si... | AMILO Li1705                | Notebook    | [71e906faa3](https://linux-hardware.org/?probe=71e906faa3) | Apr 07, 2021 |
| Dell          | Latitude 7410               | Notebook    | [a72bb094fd](https://linux-hardware.org/?probe=a72bb094fd) | Mar 26, 2021 |
| Dell          | 05DN3X A00                  | Desktop     | [14c65221b8](https://linux-hardware.org/?probe=14c65221b8) | Mar 20, 2021 |
| ASUSTek       | P4VP-MX                     | Desktop     | [ce116189a9](https://linux-hardware.org/?probe=ce116189a9) | Mar 19, 2021 |
| ASUSTek       | P4VP-MX                     | Desktop     | [1f7de7a842](https://linux-hardware.org/?probe=1f7de7a842) | Mar 19, 2021 |
| ASUSTek       | Acacia                      | Desktop     | [51a2e8c7b7](https://linux-hardware.org/?probe=51a2e8c7b7) | Mar 17, 2021 |
| Dell          | Vostro 3550                 | Notebook    | [ebd077e7f4](https://linux-hardware.org/?probe=ebd077e7f4) | Mar 16, 2021 |
| HP            | Pavilion g6                 | Notebook    | [6079cacf9b](https://linux-hardware.org/?probe=6079cacf9b) | Mar 14, 2021 |
| Samsung       | R530/R730/R540              | Notebook    | [a9fd173c51](https://linux-hardware.org/?probe=a9fd173c51) | Mar 13, 2021 |
| Gateway       | MCP61SM2MA FAB1.0           | Desktop     | [efab4d96e9](https://linux-hardware.org/?probe=efab4d96e9) | Mar 10, 2021 |
| Gateway       | MCP61SM2MA FAB1.0           | Desktop     | [514d4c99a1](https://linux-hardware.org/?probe=514d4c99a1) | Mar 10, 2021 |
| Dell          | 05DN3X A00                  | Desktop     | [2407fc2f7a](https://linux-hardware.org/?probe=2407fc2f7a) | Mar 09, 2021 |
| Dell          | Dimension E521              | Desktop     | [c82996b3dc](https://linux-hardware.org/?probe=c82996b3dc) | Mar 07, 2021 |
| Dell          | 0C522T A01                  | Desktop     | [4871abab72](https://linux-hardware.org/?probe=4871abab72) | Mar 06, 2021 |
| Dell          | Inspiron 1012               | Notebook    | [4c4bb4bd4a](https://linux-hardware.org/?probe=4c4bb4bd4a) | Mar 04, 2021 |
| HP            | 3032h                       | Desktop     | [50914ba2f5](https://linux-hardware.org/?probe=50914ba2f5) | Mar 04, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [b0cdfde6d1](https://linux-hardware.org/?probe=b0cdfde6d1) | Mar 02, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [492714801f](https://linux-hardware.org/?probe=492714801f) | Mar 02, 2021 |
| ASUSTek       | P5N-E SLI                   | Desktop     | [236a4d5753](https://linux-hardware.org/?probe=236a4d5753) | Feb 23, 2021 |
| ASUSTek       | P5N-E SLI                   | Desktop     | [27f148966a](https://linux-hardware.org/?probe=27f148966a) | Feb 23, 2021 |
| ASUSTek       | K50C                        | Notebook    | [e6cc5c82bf](https://linux-hardware.org/?probe=e6cc5c82bf) | Feb 21, 2021 |
| HP            | 8458                        | Mini pc     | [87e6e38b4a](https://linux-hardware.org/?probe=87e6e38b4a) | Feb 20, 2021 |
| HP            | 8458                        | Mini pc     | [51c854280c](https://linux-hardware.org/?probe=51c854280c) | Feb 20, 2021 |
| Lenovo        | ThinkPad R60 94566FG        | Notebook    | [f0eb3f1d77](https://linux-hardware.org/?probe=f0eb3f1d77) | Feb 19, 2021 |
| Medion        | Akoya E4214 MD99570         | Notebook    | [3ae1e824ed](https://linux-hardware.org/?probe=3ae1e824ed) | Feb 13, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [003b1f0799](https://linux-hardware.org/?probe=003b1f0799) | Feb 12, 2021 |
| Toshiba       | Satellite L500              | Notebook    | [a642972ffa](https://linux-hardware.org/?probe=a642972ffa) | Feb 12, 2021 |
| Dell          | Dimension E521              | Desktop     | [e1e96701d6](https://linux-hardware.org/?probe=e1e96701d6) | Feb 12, 2021 |
| Dell          | Dimension E521              | Desktop     | [8fa6c876ed](https://linux-hardware.org/?probe=8fa6c876ed) | Feb 12, 2021 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [f7fc4d663b](https://linux-hardware.org/?probe=f7fc4d663b) | Feb 08, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [e4d417012f](https://linux-hardware.org/?probe=e4d417012f) | Feb 08, 2021 |
| ASUSTek       | X541NA                      | Notebook    | [e8ed6f17a3](https://linux-hardware.org/?probe=e8ed6f17a3) | Feb 07, 2021 |
| Unknown       | Unknown                     | Notebook    | [cf6b92a979](https://linux-hardware.org/?probe=cf6b92a979) | Feb 07, 2021 |
| Acer          | Aspire 7730G                | Notebook    | [6fadc9e655](https://linux-hardware.org/?probe=6fadc9e655) | Jan 31, 2021 |
| Toshiba       | Satellite L300              | Notebook    | [9b7beecf8b](https://linux-hardware.org/?probe=9b7beecf8b) | Jan 29, 2021 |
| Dell          | 0TP406                      | Desktop     | [0980bfcfe9](https://linux-hardware.org/?probe=0980bfcfe9) | Jan 28, 2021 |
| Dell          | 0K216C                      | Desktop     | [c1cf70d814](https://linux-hardware.org/?probe=c1cf70d814) | Jan 19, 2021 |
| Sony          | VPCZ21V9E                   | Notebook    | [f0e8428fc2](https://linux-hardware.org/?probe=f0e8428fc2) | Jan 17, 2021 |
| Fujitsu       | LIFEBOOK T902               | Notebook    | [b0aa1bff61](https://linux-hardware.org/?probe=b0aa1bff61) | Jan 12, 2021 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [b0f061dfba](https://linux-hardware.org/?probe=b0f061dfba) | Jan 08, 2021 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [da98de1775](https://linux-hardware.org/?probe=da98de1775) | Jan 08, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [5494aa2859](https://linux-hardware.org/?probe=5494aa2859) | Jan 04, 2021 |
| Acer          | AOD255                      | Notebook    | [534f59ebc3](https://linux-hardware.org/?probe=534f59ebc3) | Jan 02, 2021 |
| Lenovo        | ThinkPad T450 20BUS3CF00    | Notebook    | [4dde602ff6](https://linux-hardware.org/?probe=4dde602ff6) | Jan 01, 2021 |
| Acer          | Extensa 5630                | Notebook    | [eed68dd316](https://linux-hardware.org/?probe=eed68dd316) | Dec 30, 2020 |
| Sony          | VPCZ21V9E                   | Notebook    | [b34a53e0e2](https://linux-hardware.org/?probe=b34a53e0e2) | Dec 29, 2020 |
| Acer          | Extensa 5510                | Notebook    | [efd4fce381](https://linux-hardware.org/?probe=efd4fce381) | Dec 29, 2020 |
| HP            | 3032h                       | Desktop     | [c71be55264](https://linux-hardware.org/?probe=c71be55264) | Dec 24, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [56f8292d5b](https://linux-hardware.org/?probe=56f8292d5b) | Dec 23, 2020 |
| Lenovo        | ThinkPad T60 1951CJ4        | Notebook    | [15c45c1a66](https://linux-hardware.org/?probe=15c45c1a66) | Dec 20, 2020 |
| Lenovo        | ThinkPad T60 1951CJ4        | Notebook    | [0f67c598b9](https://linux-hardware.org/?probe=0f67c598b9) | Dec 20, 2020 |
| MSI           | MS-7211                     | Desktop     | [d5848092f3](https://linux-hardware.org/?probe=d5848092f3) | Dec 14, 2020 |
| Acer          | Extensa 5220                | Notebook    | [3dfca3a90f](https://linux-hardware.org/?probe=3dfca3a90f) | Dec 12, 2020 |
| Acer          | Extensa 5220                | Notebook    | [9b67134373](https://linux-hardware.org/?probe=9b67134373) | Dec 12, 2020 |
| Dell          | Precision M4700             | Notebook    | [58d2d0e8d4](https://linux-hardware.org/?probe=58d2d0e8d4) | Dec 11, 2020 |
| Dell          | Precision M4700             | Notebook    | [379e1a461c](https://linux-hardware.org/?probe=379e1a461c) | Dec 09, 2020 |
| Dell          | Inspiron N5050              | Notebook    | [ac934f7ac7](https://linux-hardware.org/?probe=ac934f7ac7) | Dec 07, 2020 |
| Dell          | Inspiron N5050              | Notebook    | [8f2d17e846](https://linux-hardware.org/?probe=8f2d17e846) | Dec 07, 2020 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [7499600f8c](https://linux-hardware.org/?probe=7499600f8c) | Dec 02, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [c176e7e603](https://linux-hardware.org/?probe=c176e7e603) | Nov 29, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [e4e600f1ed](https://linux-hardware.org/?probe=e4e600f1ed) | Nov 29, 2020 |
| Dell          | 0T656F A02                  | Desktop     | [668f859641](https://linux-hardware.org/?probe=668f859641) | Nov 28, 2020 |
| Nvidia        | MCP7A 2                     | Desktop     | [c18fd136a9](https://linux-hardware.org/?probe=c18fd136a9) | Nov 24, 2020 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [ff9f1e3bc5](https://linux-hardware.org/?probe=ff9f1e3bc5) | Nov 22, 2020 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [41517af8ad](https://linux-hardware.org/?probe=41517af8ad) | Nov 22, 2020 |
| ASUSTek       | 1015PN                      | Notebook    | [c0c9898136](https://linux-hardware.org/?probe=c0c9898136) | Nov 19, 2020 |
| ASUSTek       | 1015PN                      | Notebook    | [f19c7014be](https://linux-hardware.org/?probe=f19c7014be) | Nov 19, 2020 |
| Dell          | Latitude E7440              | Notebook    | [222b0a563a](https://linux-hardware.org/?probe=222b0a563a) | Nov 15, 2020 |
| Gigabyte      | J1800M-D3P                  | Desktop     | [9ab6ea275f](https://linux-hardware.org/?probe=9ab6ea275f) | Nov 11, 2020 |
| Gigabyte      | B450M S2H                   | Desktop     | [b77ab61c1d](https://linux-hardware.org/?probe=b77ab61c1d) | Nov 10, 2020 |
| Gigabyte      | J1800M-D3P                  | Desktop     | [ae71ad880b](https://linux-hardware.org/?probe=ae71ad880b) | Nov 10, 2020 |
| HP            | Pavilion dv8000 (EZ590UA... | Notebook    | [1e64c078af](https://linux-hardware.org/?probe=1e64c078af) | Nov 04, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [c02b06f51f](https://linux-hardware.org/?probe=c02b06f51f) | Oct 31, 2020 |
| Samsung       | N150P/N210P/N220P           | Notebook    | [808224d57c](https://linux-hardware.org/?probe=808224d57c) | Oct 30, 2020 |
| ASUSTek       | X205TA                      | Notebook    | [f7fc9c9932](https://linux-hardware.org/?probe=f7fc9c9932) | Oct 20, 2020 |
| Google        | Gnawty                      | Notebook    | [6bb50a022d](https://linux-hardware.org/?probe=6bb50a022d) | Oct 10, 2020 |
| Toshiba       | QOSMIO F755                 | Notebook    | [defa9c775a](https://linux-hardware.org/?probe=defa9c775a) | Oct 01, 2020 |
| Dell          | 0C2KJT A00                  | Desktop     | [37cf119697](https://linux-hardware.org/?probe=37cf119697) | Sep 30, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [d822785861](https://linux-hardware.org/?probe=d822785861) | Sep 30, 2020 |
| ASUSTek       | A88XM-A                     | Desktop     | [b0a785eecd](https://linux-hardware.org/?probe=b0a785eecd) | Sep 30, 2020 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [64da7044cf](https://linux-hardware.org/?probe=64da7044cf) | Sep 26, 2020 |
| Intel         | 945GCT-M                    | Desktop     | [c00c60e193](https://linux-hardware.org/?probe=c00c60e193) | Sep 26, 2020 |
| Intel         | 945GCT-M                    | Desktop     | [f714eaf1b2](https://linux-hardware.org/?probe=f714eaf1b2) | Sep 26, 2020 |
| HP            | 1494                        | Desktop     | [3d33e5eb9e](https://linux-hardware.org/?probe=3d33e5eb9e) | Sep 20, 2020 |
| Medion        | Akoya E4214 MD99570         | Notebook    | [e45ead8de9](https://linux-hardware.org/?probe=e45ead8de9) | Sep 20, 2020 |
| Samsung       | R610                        | Notebook    | [db61c853a2](https://linux-hardware.org/?probe=db61c853a2) | Sep 17, 2020 |
| ASUSTek       | T101HA                      | Notebook    | [036f4f2304](https://linux-hardware.org/?probe=036f4f2304) | Sep 15, 2020 |
| Dell          | 09KPNV A00                  | Desktop     | [7a9366d7a0](https://linux-hardware.org/?probe=7a9366d7a0) | Sep 04, 2020 |
| ASUSTek       | P53E                        | Notebook    | [75d3fa4178](https://linux-hardware.org/?probe=75d3fa4178) | Sep 04, 2020 |
| Lenovo        | IdeaPad Z460 20059          | Notebook    | [9568d009c0](https://linux-hardware.org/?probe=9568d009c0) | Sep 01, 2020 |
| HP            | Stream Laptop 11-y0XX       | Notebook    | [06dd4aecb5](https://linux-hardware.org/?probe=06dd4aecb5) | Sep 01, 2020 |
| Acer          | TravelMate B115-M           | Notebook    | [d3395dca0c](https://linux-hardware.org/?probe=d3395dca0c) | Aug 30, 2020 |
| Itautec       | W7655                       | Notebook    | [511d121c7f](https://linux-hardware.org/?probe=511d121c7f) | Aug 29, 2020 |
| HP            | 8265                        | Desktop     | [b9ebd37c9f](https://linux-hardware.org/?probe=b9ebd37c9f) | Aug 24, 2020 |
| ASUSTek       | CROSSHAIR II FORMULA        | Desktop     | [fc54031f7e](https://linux-hardware.org/?probe=fc54031f7e) | Aug 12, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [90db4cc4d1](https://linux-hardware.org/?probe=90db4cc4d1) | Aug 07, 2020 |
| Samsung       | N150P                       | Notebook    | [17e2e411da](https://linux-hardware.org/?probe=17e2e411da) | Aug 07, 2020 |
| Toshiba       | Satellite L310              | Notebook    | [bf2bd8711e](https://linux-hardware.org/?probe=bf2bd8711e) | Aug 03, 2020 |
| HP            | 0A54h                       | Desktop     | [097eabe722](https://linux-hardware.org/?probe=097eabe722) | Aug 02, 2020 |
| Samsung       | N150/N210/N220              | Notebook    | [304d7ac49d](https://linux-hardware.org/?probe=304d7ac49d) | Aug 02, 2020 |
| ASRock        | N68-S3 FX                   | Desktop     | [cbf919cfd5](https://linux-hardware.org/?probe=cbf919cfd5) | Jul 30, 2020 |
| HP            | 18E7                        | Desktop     | [4b13141bdb](https://linux-hardware.org/?probe=4b13141bdb) | Jul 30, 2020 |
| HP            | EliteBook 2740p             | Notebook    | [b87f4916b6](https://linux-hardware.org/?probe=b87f4916b6) | Jul 27, 2020 |
| HP            | Compaq Presario CQ40        | Notebook    | [aaf338c454](https://linux-hardware.org/?probe=aaf338c454) | Jul 24, 2020 |
| Dell          | Latitude E6420              | Notebook    | [1db19a0158](https://linux-hardware.org/?probe=1db19a0158) | Jul 24, 2020 |
| Sony          | VGN-S55B_S                  | Notebook    | [2643feee17](https://linux-hardware.org/?probe=2643feee17) | Jul 24, 2020 |
| HP            | EliteBook 8570w             | Notebook    | [bd697a03f8](https://linux-hardware.org/?probe=bd697a03f8) | Jul 19, 2020 |
| Itautec       | W7655                       | Notebook    | [bf4635403e](https://linux-hardware.org/?probe=bf4635403e) | Jul 17, 2020 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [dc82f8cf6b](https://linux-hardware.org/?probe=dc82f8cf6b) | Jul 15, 2020 |
| Positivo      | N1103                       | Notebook    | [3cdb7fc95e](https://linux-hardware.org/?probe=3cdb7fc95e) | Jul 13, 2020 |
| Toshiba       | PORTEGE R500                | Notebook    | [e7c5c010bd](https://linux-hardware.org/?probe=e7c5c010bd) | Jul 12, 2020 |
| Toshiba       | PORTEGE R500                | Notebook    | [fd50b5e2a7](https://linux-hardware.org/?probe=fd50b5e2a7) | Jul 12, 2020 |
| Dell          | Latitude E6420              | Notebook    | [52d11b26d3](https://linux-hardware.org/?probe=52d11b26d3) | Jul 09, 2020 |
| Acer          | Aspire R3-131T              | Notebook    | [dbecc119b2](https://linux-hardware.org/?probe=dbecc119b2) | Jul 08, 2020 |
| Sony          | VGN-S55B_S                  | Notebook    | [1943134c38](https://linux-hardware.org/?probe=1943134c38) | Jun 21, 2020 |
| HP            | Notebook                    | Notebook    | [841b43ba94](https://linux-hardware.org/?probe=841b43ba94) | Jun 14, 2020 |
| MSI           | MS-7211                     | Desktop     | [76c18a99c5](https://linux-hardware.org/?probe=76c18a99c5) | Jun 14, 2020 |
| MSI           | MS-7211                     | Desktop     | [3bad7f0625](https://linux-hardware.org/?probe=3bad7f0625) | Jun 14, 2020 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [d8882da61a](https://linux-hardware.org/?probe=d8882da61a) | Jun 13, 2020 |
| HP            | 1494                        | Desktop     | [69ad46d94d](https://linux-hardware.org/?probe=69ad46d94d) | Jun 11, 2020 |
| ASUSTek       | K8N4-E Deluxe               | Desktop     | [0908450cf0](https://linux-hardware.org/?probe=0908450cf0) | Jun 08, 2020 |
| Fujitsu       | D3171-A1 S26361-D3171-A1    | Desktop     | [a514be4e22](https://linux-hardware.org/?probe=a514be4e22) | Jun 06, 2020 |
| Lenovo        | B490 37722SP                | Notebook    | [9bf0160ca7](https://linux-hardware.org/?probe=9bf0160ca7) | May 28, 2020 |
| MSI           | MS-7267                     | Desktop     | [7003aba6ad](https://linux-hardware.org/?probe=7003aba6ad) | May 27, 2020 |
| Toshiba       | Satellite L500              | Notebook    | [df76123000](https://linux-hardware.org/?probe=df76123000) | May 22, 2020 |
| HP            | Compaq nc6400 (RB516UT#A... | Notebook    | [f950094ff1](https://linux-hardware.org/?probe=f950094ff1) | May 21, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [32ab884c0f](https://linux-hardware.org/?probe=32ab884c0f) | May 21, 2020 |
| HP            | Mini 110-1000               | Notebook    | [1f0854cd2e](https://linux-hardware.org/?probe=1f0854cd2e) | May 19, 2020 |
| HP            | Mini 110-1000               | Notebook    | [bce45cbc8a](https://linux-hardware.org/?probe=bce45cbc8a) | May 19, 2020 |
| Unknown       | Unknown                     | Notebook    | [aabfc32771](https://linux-hardware.org/?probe=aabfc32771) | May 19, 2020 |
| Lenovo        | ThinkPad E490 20N90019BR    | Notebook    | [94839129c9](https://linux-hardware.org/?probe=94839129c9) | May 19, 2020 |
| Lenovo        | ThinkPad E490 20N90019BR    | Notebook    | [adf1cefbf5](https://linux-hardware.org/?probe=adf1cefbf5) | May 19, 2020 |
| Unknown       | Unknown                     | Notebook    | [3bcd40acc0](https://linux-hardware.org/?probe=3bcd40acc0) | May 19, 2020 |
| Toshiba       | Satellite L500              | Notebook    | [6782b31a2e](https://linux-hardware.org/?probe=6782b31a2e) | May 17, 2020 |
| Dell          | 02YRK5 A02                  | Desktop     | [27e6fd0506](https://linux-hardware.org/?probe=27e6fd0506) | May 16, 2020 |
| Clevo         | W55xEU                      | Notebook    | [f1ad04bd23](https://linux-hardware.org/?probe=f1ad04bd23) | May 16, 2020 |
| Dell          | 02YRK5 A02                  | Desktop     | [4fa188ca3e](https://linux-hardware.org/?probe=4fa188ca3e) | May 15, 2020 |
| ECS           | Alhena5                     | Desktop     | [be2ff7b4dc](https://linux-hardware.org/?probe=be2ff7b4dc) | May 15, 2020 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [a0112b2478](https://linux-hardware.org/?probe=a0112b2478) | May 14, 2020 |
| Toshiba       | Satellite M70               | Notebook    | [c9e02a940d](https://linux-hardware.org/?probe=c9e02a940d) | May 13, 2020 |
| ASUSTek       | Q400A                       | Notebook    | [075d494ee2](https://linux-hardware.org/?probe=075d494ee2) | May 10, 2020 |
| Lenovo        | B575 1450A7U                | Notebook    | [b781397fa7](https://linux-hardware.org/?probe=b781397fa7) | May 05, 2020 |
| Gigabyte      | Z87X-UD5H-CF                | Desktop     | [39798ff3d6](https://linux-hardware.org/?probe=39798ff3d6) | May 05, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [3d10f5b306](https://linux-hardware.org/?probe=3d10f5b306) | May 03, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [0e91d35b8e](https://linux-hardware.org/?probe=0e91d35b8e) | May 03, 2020 |
| Sony          | VGN-FW140E                  | Notebook    | [8aad1d7bfc](https://linux-hardware.org/?probe=8aad1d7bfc) | May 02, 2020 |
| Toshiba       | Satellite C660              | Notebook    | [354e994c53](https://linux-hardware.org/?probe=354e994c53) | May 01, 2020 |
| Sony          | VGN-FW140E                  | Notebook    | [cee09f3d1e](https://linux-hardware.org/?probe=cee09f3d1e) | Apr 30, 2020 |
| Dell          | 05DN3X A00                  | Desktop     | [9957230890](https://linux-hardware.org/?probe=9957230890) | Apr 30, 2020 |
| ASUSTek       | Amberine M                  | Desktop     | [c948d7fd76](https://linux-hardware.org/?probe=c948d7fd76) | Apr 29, 2020 |
| ASUSTek       | Amberine M                  | Desktop     | [595c810650](https://linux-hardware.org/?probe=595c810650) | Apr 29, 2020 |
| ASUSTek       | Amberine M                  | Desktop     | [f1fc9b4580](https://linux-hardware.org/?probe=f1fc9b4580) | Apr 29, 2020 |
| Gigabyte      | EQ45M-S2                    | Desktop     | [1faa92e0c1](https://linux-hardware.org/?probe=1faa92e0c1) | Apr 27, 2020 |
| Gigabyte      | EQ45M-S2                    | Desktop     | [e8adc47158](https://linux-hardware.org/?probe=e8adc47158) | Apr 27, 2020 |
| Dell          | 0Y958C A00                  | Desktop     | [131e2c31a9](https://linux-hardware.org/?probe=131e2c31a9) | Apr 26, 2020 |
| ASUSTek       | M3A78-EM                    | Desktop     | [f9944d9361](https://linux-hardware.org/?probe=f9944d9361) | Apr 25, 2020 |
| Toshiba       | Satellite Pro C850          | Notebook    | [1744740eb4](https://linux-hardware.org/?probe=1744740eb4) | Apr 24, 2020 |
| Dell          | 0WF810                      | Desktop     | [1b9697ff31](https://linux-hardware.org/?probe=1b9697ff31) | Apr 23, 2020 |
| Lenovo        | IdeaPad 2in1 14 81CW        | Convertible | [79e6fc40f4](https://linux-hardware.org/?probe=79e6fc40f4) | Apr 23, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [5ddee791c7](https://linux-hardware.org/?probe=5ddee791c7) | Apr 20, 2020 |
| Lenovo        | IdeaPad 2in1 14 81CW        | Convertible | [15b2fb3807](https://linux-hardware.org/?probe=15b2fb3807) | Apr 20, 2020 |
| ASUSTek       | X45U                        | Notebook    | [0ce069357c](https://linux-hardware.org/?probe=0ce069357c) | Apr 18, 2020 |
| Lenovo        | IdeaPad 2in1 14 81CW        | Convertible | [e6b8191910](https://linux-hardware.org/?probe=e6b8191910) | Apr 16, 2020 |
| ECS           | P4S5A/DX+                   | Desktop     | [e4cfc413e7](https://linux-hardware.org/?probe=e4cfc413e7) | Apr 08, 2020 |
| Acer          | Aspire ES1-521              | Notebook    | [20e7fea349](https://linux-hardware.org/?probe=20e7fea349) | Apr 08, 2020 |
| Lenovo        | 433328G                     | Notebook    | [3c5b9e3703](https://linux-hardware.org/?probe=3c5b9e3703) | Apr 07, 2020 |
| Acer          | Aspire ES1-521              | Notebook    | [0c74c17c24](https://linux-hardware.org/?probe=0c74c17c24) | Apr 07, 2020 |
| Gigabyte      | VM900M                      | Desktop     | [8554ccddc2](https://linux-hardware.org/?probe=8554ccddc2) | Apr 03, 2020 |
| HP            | 2133 (FU346EA)              | Notebook    | [499f685a66](https://linux-hardware.org/?probe=499f685a66) | Mar 31, 2020 |
| HP            | 2133 (FU346EA)              | Notebook    | [2c6f9bf922](https://linux-hardware.org/?probe=2c6f9bf922) | Mar 31, 2020 |
| HP            | Stream Laptop 14-ds0xxx     | Notebook    | [8fae01eff8](https://linux-hardware.org/?probe=8fae01eff8) | Mar 31, 2020 |
| HP            | 1494                        | Desktop     | [b34629c804](https://linux-hardware.org/?probe=b34629c804) | Mar 28, 2020 |
| HP            | 0A5Ch                       | Desktop     | [5f4bf573ad](https://linux-hardware.org/?probe=5f4bf573ad) | Mar 28, 2020 |
| HP            | 0A5Ch                       | Desktop     | [7411b1a819](https://linux-hardware.org/?probe=7411b1a819) | Mar 28, 2020 |
| HP            | 255 G2                      | Notebook    | [7cfb9e5a0e](https://linux-hardware.org/?probe=7cfb9e5a0e) | Mar 25, 2020 |
| ECS           | P4S5A/DX+                   | Desktop     | [a16a39037a](https://linux-hardware.org/?probe=a16a39037a) | Mar 24, 2020 |
| ECS           | P4S5A/DX+                   | Desktop     | [f5dcbfaa11](https://linux-hardware.org/?probe=f5dcbfaa11) | Mar 24, 2020 |
| Clevo         | W55xEU                      | Notebook    | [09d70e49b4](https://linux-hardware.org/?probe=09d70e49b4) | Mar 23, 2020 |
| Unknown       | G41 Series                  | Desktop     | [597b5edb76](https://linux-hardware.org/?probe=597b5edb76) | Mar 20, 2020 |
| ASUSTek       | F3E                         | Notebook    | [e01cca6624](https://linux-hardware.org/?probe=e01cca6624) | Mar 18, 2020 |
| ASUSTek       | F3E                         | Notebook    | [d7a53d4fb8](https://linux-hardware.org/?probe=d7a53d4fb8) | Mar 17, 2020 |
| HP            | 0AA8h                       | Desktop     | [881008d596](https://linux-hardware.org/?probe=881008d596) | Mar 11, 2020 |
| Acer          | MCP73PV NVIDIA MCP73        | Desktop     | [97b8e03710](https://linux-hardware.org/?probe=97b8e03710) | Mar 04, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [8b516d50ef](https://linux-hardware.org/?probe=8b516d50ef) | Mar 03, 2020 |
| HP            | Pavilion dv6500             | Notebook    | [1345f0d7df](https://linux-hardware.org/?probe=1345f0d7df) | Mar 02, 2020 |
| ASUSTek       | P8Z68-V PRO GEN3            | Desktop     | [c67fe8542c](https://linux-hardware.org/?probe=c67fe8542c) | Mar 01, 2020 |
| Lenovo        | 3000 N500 423374G           | Notebook    | [b0d0a28cc2](https://linux-hardware.org/?probe=b0d0a28cc2) | Feb 29, 2020 |
| Lenovo        | 3000 N500 423374G           | Notebook    | [c67851f402](https://linux-hardware.org/?probe=c67851f402) | Feb 29, 2020 |
| ECS           | Alhena5                     | Desktop     | [89c17f438e](https://linux-hardware.org/?probe=89c17f438e) | Feb 28, 2020 |
| eMachines     | E520 V1.06                  | Notebook    | [33cabcad9d](https://linux-hardware.org/?probe=33cabcad9d) | Feb 24, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | Desktop     | [6a48bc1e53](https://linux-hardware.org/?probe=6a48bc1e53) | Feb 21, 2020 |
| HP            | Pavilion dv4                | Notebook    | [6f6de0e938](https://linux-hardware.org/?probe=6f6de0e938) | Feb 18, 2020 |
| Acer          | Aspire 7730G                | Notebook    | [f00cf2c184](https://linux-hardware.org/?probe=f00cf2c184) | Feb 13, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | Desktop     | [1ad8d628c8](https://linux-hardware.org/?probe=1ad8d628c8) | Feb 12, 2020 |
| Fujitsu Si... | D1931 S26361-D1931          | Desktop     | [a1abc42f9e](https://linux-hardware.org/?probe=a1abc42f9e) | Feb 12, 2020 |
| Toshiba       | Satellite C850-F117         | Notebook    | [648aab8d5d](https://linux-hardware.org/?probe=648aab8d5d) | Feb 12, 2020 |
| Sony          | VGN-CR21S_P                 | Notebook    | [2ceca1462f](https://linux-hardware.org/?probe=2ceca1462f) | Feb 08, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [eca3e46eed](https://linux-hardware.org/?probe=eca3e46eed) | Feb 07, 2020 |
| HP            | 0AA8h                       | Desktop     | [c5721d223f](https://linux-hardware.org/?probe=c5721d223f) | Feb 05, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [1693ad6fcd](https://linux-hardware.org/?probe=1693ad6fcd) | Feb 04, 2020 |
| Dell          | 0F0TGN A00                  | Desktop     | [1f4a60f810](https://linux-hardware.org/?probe=1f4a60f810) | Feb 03, 2020 |
| Toshiba       | NB520                       | Notebook    | [a6b76ee94c](https://linux-hardware.org/?probe=a6b76ee94c) | Feb 02, 2020 |
| Toshiba       | NB520                       | Notebook    | [7fcee73990](https://linux-hardware.org/?probe=7fcee73990) | Feb 02, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [0244fb9c97](https://linux-hardware.org/?probe=0244fb9c97) | Feb 01, 2020 |
| ASUSTek       | S500CA                      | Notebook    | [4f82008cac](https://linux-hardware.org/?probe=4f82008cac) | Jan 29, 2020 |
| HP            | Compaq nx6310 (EY512ES#A... | Notebook    | [7131bc7839](https://linux-hardware.org/?probe=7131bc7839) | Jan 29, 2020 |
| Lenovo        | 31900058 STD                | Desktop     | [4d8db6ee1f](https://linux-hardware.org/?probe=4d8db6ee1f) | Jan 22, 2020 |
| Lenovo        | 31900058 STD                | Desktop     | [6320c5f50f](https://linux-hardware.org/?probe=6320c5f50f) | Jan 22, 2020 |
| Sony          | VPCCW21FX                   | Notebook    | [78ac20109b](https://linux-hardware.org/?probe=78ac20109b) | Jan 21, 2020 |
| ASUSTek       | P8H61-MX                    | Desktop     | [c7c5cc3339](https://linux-hardware.org/?probe=c7c5cc3339) | Jan 17, 2020 |
| ASUSTek       | P8H61-MX                    | Desktop     | [4e6cff6c0e](https://linux-hardware.org/?probe=4e6cff6c0e) | Jan 17, 2020 |
| HP            | Compaq nx6310 (EY512ES#A... | Notebook    | [5aa6704ff1](https://linux-hardware.org/?probe=5aa6704ff1) | Jan 16, 2020 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [75648daef1](https://linux-hardware.org/?probe=75648daef1) | Jan 15, 2020 |
| Intel         | DP55WG AAE57269-408         | Desktop     | [b1606ddfdf](https://linux-hardware.org/?probe=b1606ddfdf) | Jan 14, 2020 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [d87b9779d7](https://linux-hardware.org/?probe=d87b9779d7) | Jan 14, 2020 |
| ASUSTek       | VivoBook 12_ASUS Laptop ... | Notebook    | [c6595736b8](https://linux-hardware.org/?probe=c6595736b8) | Jan 14, 2020 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [db8eaef3e7](https://linux-hardware.org/?probe=db8eaef3e7) | Jan 09, 2020 |
| HP            | Laptop 15-db0xxx            | Notebook    | [f3d6402b19](https://linux-hardware.org/?probe=f3d6402b19) | Dec 24, 2019 |
| Gigabyte      | P35-DS3R                    | Desktop     | [847cb4544c](https://linux-hardware.org/?probe=847cb4544c) | Dec 23, 2019 |
| Gigabyte      | P35-DS3R                    | Desktop     | [cf7e7bc433](https://linux-hardware.org/?probe=cf7e7bc433) | Dec 23, 2019 |
| Gigabyte      | P35-DS3R                    | Desktop     | [d7442beee0](https://linux-hardware.org/?probe=d7442beee0) | Dec 23, 2019 |
| HP            | 0A54h                       | Desktop     | [3a37dfd543](https://linux-hardware.org/?probe=3a37dfd543) | Dec 05, 2019 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [f30cd368d8](https://linux-hardware.org/?probe=f30cd368d8) | Dec 02, 2019 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [86b1a4acd7](https://linux-hardware.org/?probe=86b1a4acd7) | Dec 02, 2019 |
| Intel         | D945GCLF2 AAE46416-106      | Desktop     | [f2817e5306](https://linux-hardware.org/?probe=f2817e5306) | Nov 29, 2019 |
| Biostar       | A68N-5600E                  | Desktop     | [d91042148c](https://linux-hardware.org/?probe=d91042148c) | Nov 27, 2019 |
| Toshiba       | Satellite C850-F117         | Notebook    | [5b8f68dbc9](https://linux-hardware.org/?probe=5b8f68dbc9) | Nov 26, 2019 |
| Toshiba       | Satellite C55D-B            | Notebook    | [0d1bbd1e60](https://linux-hardware.org/?probe=0d1bbd1e60) | Nov 25, 2019 |
| Toshiba       | Satellite C55D-B            | Notebook    | [98653dbce0](https://linux-hardware.org/?probe=98653dbce0) | Nov 25, 2019 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [05c2549698](https://linux-hardware.org/?probe=05c2549698) | Nov 24, 2019 |
| eMachines     | E945GCU                     | Desktop     | [0a595972e2](https://linux-hardware.org/?probe=0a595972e2) | Nov 23, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [c27bae21b0](https://linux-hardware.org/?probe=c27bae21b0) | Nov 16, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [afb3948882](https://linux-hardware.org/?probe=afb3948882) | Nov 15, 2019 |
| Acer          | Aspire F5-573G              | Notebook    | [db302aa54d](https://linux-hardware.org/?probe=db302aa54d) | Nov 14, 2019 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [00c8d1e4e7](https://linux-hardware.org/?probe=00c8d1e4e7) | Nov 11, 2019 |
| Dell          | 042P49 A01                  | Desktop     | [b7c0226ab5](https://linux-hardware.org/?probe=b7c0226ab5) | Nov 10, 2019 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [cc352f0876](https://linux-hardware.org/?probe=cc352f0876) | Nov 10, 2019 |
| ASUSTek       | X99-A/USB                   | Desktop     | [40ea4505b9](https://linux-hardware.org/?probe=40ea4505b9) | Nov 09, 2019 |
| eMachines     | EL1850                      | Desktop     | [c2b6c642fb](https://linux-hardware.org/?probe=c2b6c642fb) | Nov 09, 2019 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [a4bd90bb25](https://linux-hardware.org/?probe=a4bd90bb25) | Nov 09, 2019 |
| HP            | Laptop 15-bs0xx             | Notebook    | [2ac11dfe68](https://linux-hardware.org/?probe=2ac11dfe68) | Nov 02, 2019 |
| ASUSTek       | 1005PXD                     | Notebook    | [d0afcbe081](https://linux-hardware.org/?probe=d0afcbe081) | Oct 26, 2019 |
| ASUSTek       | 1005PXD                     | Notebook    | [1e57ee0116](https://linux-hardware.org/?probe=1e57ee0116) | Oct 26, 2019 |
| Lenovo        | 31900058 STD                | Desktop     | [ee0395fcb1](https://linux-hardware.org/?probe=ee0395fcb1) | Oct 25, 2019 |
| HP            | Pavilion Notebook           | Notebook    | [14784cf228](https://linux-hardware.org/?probe=14784cf228) | Oct 19, 2019 |
| HP            | 255 G5 Notebook PC          | Notebook    | [f14f865a3d](https://linux-hardware.org/?probe=f14f865a3d) | Oct 08, 2019 |
| HP            | 255 G5 Notebook PC          | Notebook    | [aa23436bf3](https://linux-hardware.org/?probe=aa23436bf3) | Oct 08, 2019 |
| HP            | 255 G5 Notebook PC          | Notebook    | [b9c04a5acf](https://linux-hardware.org/?probe=b9c04a5acf) | Oct 07, 2019 |
| Gigabyte      | H61M-S1                     | Desktop     | [dc52bfa103](https://linux-hardware.org/?probe=dc52bfa103) | Oct 04, 2019 |
| Acer          | GRS400M                     | Desktop     | [1d3dc49b0a](https://linux-hardware.org/?probe=1d3dc49b0a) | Sep 29, 2019 |
| Acer          | GRS400M                     | Desktop     | [e510d98ae4](https://linux-hardware.org/?probe=e510d98ae4) | Sep 22, 2019 |
| Acer          | GRS400M                     | Desktop     | [213156ffb7](https://linux-hardware.org/?probe=213156ffb7) | Sep 22, 2019 |
| Fujitsu Si... | AMILO Pi 1505               | Notebook    | [6e3970fc39](https://linux-hardware.org/?probe=6e3970fc39) | Sep 17, 2019 |
| Fujitsu Si... | AMILO Pi 1505               | Notebook    | [20f7841be1](https://linux-hardware.org/?probe=20f7841be1) | Sep 17, 2019 |
| HP            | Pavilion Notebook           | Notebook    | [f29f057c97](https://linux-hardware.org/?probe=f29f057c97) | Sep 16, 2019 |
| Dell          | Inspiron 1501               | Notebook    | [a638607db3](https://linux-hardware.org/?probe=a638607db3) | Sep 11, 2019 |
| ASUSTek       | K8N4-E Deluxe               | Desktop     | [dee3d2bdaa](https://linux-hardware.org/?probe=dee3d2bdaa) | Sep 04, 2019 |
| ASUSTek       | K8N4-E Deluxe               | Desktop     | [cfaaae942a](https://linux-hardware.org/?probe=cfaaae942a) | Aug 27, 2019 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [85ac9b2b53](https://linux-hardware.org/?probe=85ac9b2b53) | Aug 20, 2019 |
| Foxconn       | 2AB7                        | Desktop     | [f1f1f7133a](https://linux-hardware.org/?probe=f1f1f7133a) | Aug 18, 2019 |
| ASUSTek       | P5K-VM                      | Desktop     | [e2d3942d30](https://linux-hardware.org/?probe=e2d3942d30) | Jul 25, 2019 |
| Unknown       | Unknown                     | Notebook    | [0a9618f99e](https://linux-hardware.org/?probe=0a9618f99e) | Jul 10, 2019 |
| Intel         | DX58SO AAE29331-702         | Desktop     | [d1b680dc39](https://linux-hardware.org/?probe=d1b680dc39) | Jul 05, 2019 |
| Dell          | 0C2KJT A00                  | Desktop     | [986146d6eb](https://linux-hardware.org/?probe=986146d6eb) | Jul 01, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [4faa6112c3](https://linux-hardware.org/?probe=4faa6112c3) | Jun 28, 2019 |
| Dell          | 0C2KJT A00                  | Desktop     | [ee64cbe6b5](https://linux-hardware.org/?probe=ee64cbe6b5) | Jun 28, 2019 |
| HP            | Pavilion dv7                | Notebook    | [24128291a4](https://linux-hardware.org/?probe=24128291a4) | Jun 25, 2019 |
| Unknown       | Unknown                     | Notebook    | [583ec484b5](https://linux-hardware.org/?probe=583ec484b5) | Jun 24, 2019 |
| Unknown       | Unknown                     | Notebook    | [c0eb7dc5f0](https://linux-hardware.org/?probe=c0eb7dc5f0) | Jun 24, 2019 |
| ASUSTek       | Q501LA                      | Notebook    | [ad06395996](https://linux-hardware.org/?probe=ad06395996) | Jun 23, 2019 |
| Toshiba       | Satellite M70               | Notebook    | [c31329a508](https://linux-hardware.org/?probe=c31329a508) | Jun 19, 2019 |
| IBM           | ThinkPad X41 Tablet 1869... | Notebook    | [cca643879f](https://linux-hardware.org/?probe=cca643879f) | Jun 13, 2019 |
| Toshiba       | Satellite C850-F117         | Notebook    | [7e007db586](https://linux-hardware.org/?probe=7e007db586) | Jun 12, 2019 |
| IBM           | ThinkPad T43 2669GY4        | Notebook    | [4916e9ec9c](https://linux-hardware.org/?probe=4916e9ec9c) | Jun 09, 2019 |
| Acer          | Extensa 5630                | Notebook    | [a68ff6fdd1](https://linux-hardware.org/?probe=a68ff6fdd1) | Jun 05, 2019 |
| Gateway       | MX6940M                     | Notebook    | [668db92873](https://linux-hardware.org/?probe=668db92873) | May 09, 2019 |
| Pegatron      | NARRA5                      | Desktop     | [123cff15b7](https://linux-hardware.org/?probe=123cff15b7) | May 04, 2019 |
| Dell          | Latitude D630               | Notebook    | [6ad005d6b7](https://linux-hardware.org/?probe=6ad005d6b7) | May 02, 2019 |
| WinBook       | GL Series                   | Notebook    | [89dac45ef6](https://linux-hardware.org/?probe=89dac45ef6) | Apr 28, 2019 |
| Dell          | Latitude D630               | Notebook    | [d8bf959191](https://linux-hardware.org/?probe=d8bf959191) | Apr 16, 2019 |
| IBM           | ThinkPad X41 Tablet 1869... | Notebook    | [c662baa8f5](https://linux-hardware.org/?probe=c662baa8f5) | Apr 10, 2019 |
| Intel         | D945GNT AAC96324-402        | Desktop     | [23bac57788](https://linux-hardware.org/?probe=23bac57788) | Apr 07, 2019 |
| eMachines     | E620                        | Notebook    | [de3cfd34b1](https://linux-hardware.org/?probe=de3cfd34b1) | Apr 05, 2019 |
| Dell          | 05DN3X A00                  | Desktop     | [81ec6c8fb1](https://linux-hardware.org/?probe=81ec6c8fb1) | Apr 04, 2019 |
| Dell          | Latitude D430               | Notebook    | [269e1c2948](https://linux-hardware.org/?probe=269e1c2948) | Apr 04, 2019 |
| Dell          | Latitude D430               | Notebook    | [d1c49bd4e8](https://linux-hardware.org/?probe=d1c49bd4e8) | Apr 04, 2019 |
| Positivo      | UW3                         | Notebook    | [dda25a3dc9](https://linux-hardware.org/?probe=dda25a3dc9) | Apr 03, 2019 |
| Positivo      | UW3                         | Notebook    | [aebfedfabb](https://linux-hardware.org/?probe=aebfedfabb) | Apr 03, 2019 |
| HP            | Pavilion dv1000 (PS600EA... | Notebook    | [6802b34fdd](https://linux-hardware.org/?probe=6802b34fdd) | Mar 31, 2019 |
| HP            | 17E2                        | Mini pc     | [982f591b41](https://linux-hardware.org/?probe=982f591b41) | Feb 23, 2019 |
| eMachines     | eM350                       | Notebook    | [e42feb9612](https://linux-hardware.org/?probe=e42feb9612) | Feb 06, 2019 |
| eMachines     | eM350                       | Notebook    | [f19d2e4452](https://linux-hardware.org/?probe=f19d2e4452) | Feb 06, 2019 |
| Acer          | Aspire 7730G                | Notebook    | [09bd4355b9](https://linux-hardware.org/?probe=09bd4355b9) | Jan 30, 2019 |
| Lenovo        | Annapurna CRB 0B98401 PR... | Desktop     | [11425d1746](https://linux-hardware.org/?probe=11425d1746) | Jan 27, 2019 |
| Clevo         | M660SR VT6363A              | Notebook    | [647fd58075](https://linux-hardware.org/?probe=647fd58075) | Jan 15, 2019 |
| Clevo         | M660SR VT6363A              | Notebook    | [ad84ff197d](https://linux-hardware.org/?probe=ad84ff197d) | Jan 15, 2019 |
| Lenovo        | ThinkPad W510 4391B49       | Notebook    | [227847df62](https://linux-hardware.org/?probe=227847df62) | Feb 21, 2018 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Peppermint 10   | 235       | 76.8%   |
| Peppermint 9    | 28        | 9.15%   |
| Peppermint      | 19        | 6.21%   |
| Peppermint 11.4 | 7         | 2.29%   |
| Peppermint 11.1 | 5         | 1.63%   |
| Peppermint 11.3 | 4         | 1.31%   |
| Peppermint 11.5 | 3         | 0.98%   |
| Peppermint 11.2 | 2         | 0.65%   |
| Peppermint 8    | 1         | 0.33%   |
| Peppermint 12   | 1         | 0.33%   |
| Peppermint 11.7 | 1         | 0.33%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Peppermint | 306       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.0.0-37-generic  | 39        | 11.4%   |
| 4.18.0-18-generic | 11        | 3.22%   |
| 5.4.0-42-generic  | 10        | 2.92%   |
| 5.3.0-51-generic  | 10        | 2.92%   |
| 5.3.0-62-generic  | 8         | 2.34%   |
| 5.10.0-16-amd64   | 8         | 2.34%   |
| 4.15.0-43-generic | 8         | 2.34%   |
| 5.4.0-65-generic  | 7         | 2.05%   |
| 5.3.0-46-generic  | 7         | 2.05%   |
| 5.0.0-36-generic  | 7         | 2.05%   |
| 5.0.0-32-generic  | 7         | 2.05%   |
| 5.4.0-87-generic  | 6         | 1.75%   |
| 5.4.0-66-generic  | 6         | 1.75%   |
| 5.4.0-58-generic  | 6         | 1.75%   |
| 5.10.0-14-amd64   | 6         | 1.75%   |
| 5.4.0-91-generic  | 5         | 1.46%   |
| 5.4.0-52-generic  | 5         | 1.46%   |
| 5.4.0-150-generic | 5         | 1.46%   |
| 5.3.0-40-generic  | 5         | 1.46%   |
| 5.3.0-28-generic  | 5         | 1.46%   |
| 6.1.0-10-amd64    | 4         | 1.17%   |
| 5.4.0-90-generic  | 4         | 1.17%   |
| 5.4.0-80-generic  | 4         | 1.17%   |
| 5.4.0-72-generic  | 4         | 1.17%   |
| 5.4.0-67-generic  | 4         | 1.17%   |
| 5.4.0-54-generic  | 4         | 1.17%   |
| 5.4.0-48-generic  | 4         | 1.17%   |
| 5.4.0-45-generic  | 4         | 1.17%   |
| 5.3.0-59-generic  | 4         | 1.17%   |
| 5.10.0-19-amd64   | 4         | 1.17%   |
| 4.18.0-25-generic | 4         | 1.17%   |
| 4.15.0-47-generic | 4         | 1.17%   |
| 5.4.0-81-generic  | 3         | 0.88%   |
| 5.4.0-77-generic  | 3         | 0.88%   |
| 5.4.0-70-generic  | 3         | 0.88%   |
| 5.4.0-56-generic  | 3         | 0.88%   |
| 5.4.0-47-generic  | 3         | 0.88%   |
| 5.3.0-47-generic  | 3         | 0.88%   |
| 5.3.0-42-generic  | 3         | 0.88%   |
| 5.10.0-23-amd64   | 3         | 0.88%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 118       | 36.99%  |
| 5.0.0   | 57        | 17.87%  |
| 5.3.0   | 47        | 14.73%  |
| 5.10.0  | 30        | 9.4%    |
| 4.15.0  | 27        | 8.46%   |
| 4.18.0  | 20        | 6.27%   |
| 6.1.0   | 10        | 3.13%   |
| 5.3.6   | 2         | 0.63%   |
| 5.18.0  | 2         | 0.63%   |
| 5.7.1   | 1         | 0.31%   |
| 5.6.7   | 1         | 0.31%   |
| 5.4.95  | 1         | 0.31%   |
| 5.3.9   | 1         | 0.31%   |
| 5.1.11  | 1         | 0.31%   |
| 4.8.0   | 1         | 0.31%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 119       | 37.3%   |
| 5.0     | 57        | 17.87%  |
| 5.3     | 50        | 15.67%  |
| 5.10    | 30        | 9.4%    |
| 4.15    | 27        | 8.46%   |
| 4.18    | 20        | 6.27%   |
| 6.1     | 10        | 3.13%   |
| 5.18    | 2         | 0.63%   |
| 5.7     | 1         | 0.31%   |
| 5.6     | 1         | 0.31%   |
| 5.1     | 1         | 0.31%   |
| 4.8     | 1         | 0.31%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 214       | 69.71%  |
| i686   | 93        | 30.29%  |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| LXDE       | 206       | 65.81%  |
| Unknown    | 52        | 16.61%  |
| XFCE       | 40        | 12.78%  |
| GNOME      | 10        | 3.19%   |
| Peppermint | 2         | 0.64%   |
| X-Cinnamon | 1         | 0.32%   |
| Cinnamon   | 1         | 0.32%   |
| Budgie     | 1         | 0.32%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name | Computers | Percent |
|------|-----------|---------|
| X11  | 306       | 100%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 245       | 79.29%  |
| LightDM | 51        | 16.5%   |
| TDM     | 11        | 3.56%   |
| SDDM    | 1         | 0.32%   |
| GDM3    | 1         | 0.32%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 108       | 34.5%   |
| Unknown | 44        | 14.06%  |
| en_GB   | 19        | 6.07%   |
| de_DE   | 18        | 5.75%   |
| it_IT   | 17        | 5.43%   |
| pt_BR   | 16        | 5.11%   |
| pl_PL   | 11        | 3.51%   |
| C       | 7         | 2.24%   |
| fr_FR   | 6         | 1.92%   |
| en_IN   | 6         | 1.92%   |
| ru_RU   | 5         | 1.6%    |
| nl_NL   | 5         | 1.6%    |
| es_MX   | 5         | 1.6%    |
| es_AR   | 5         | 1.6%    |
| en_CA   | 5         | 1.6%    |
| fi_FI   | 4         | 1.28%   |
| en_NZ   | 4         | 1.28%   |
| ro_RO   | 3         | 0.96%   |
| en_AU   | 3         | 0.96%   |
| ja_JP   | 2         | 0.64%   |
| es_PE   | 2         | 0.64%   |
| es_ES   | 2         | 0.64%   |
| en_ZA   | 2         | 0.64%   |
| en_PH   | 2         | 0.64%   |
| tr_TR   | 1         | 0.32%   |
| sv_SE   | 1         | 0.32%   |
| pt_PT   | 1         | 0.32%   |
| nl_BE   | 1         | 0.32%   |
| lv_LV   | 1         | 0.32%   |
| es_PA   | 1         | 0.32%   |
| es_EC   | 1         | 0.32%   |
| es_CR   | 1         | 0.32%   |
| es_BO   | 1         | 0.32%   |
| en_IE   | 1         | 0.32%   |
| el_GR   | 1         | 0.32%   |
| cs_CZ   | 1         | 0.32%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 238       | 77.52%  |
| EFI  | 69        | 22.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 255       | 81.99%  |
| Unknown  | 25        | 8.04%   |
| Overlay  | 13        | 4.18%   |
| Tmpfs    | 4         | 1.29%   |
| Btrfs    | 4         | 1.29%   |
| Ext3     | 3         | 0.96%   |
| Ext2     | 3         | 0.96%   |
| Xfs      | 1         | 0.32%   |
| Reiserfs | 1         | 0.32%   |
| F2fs     | 1         | 0.32%   |
| Aufs     | 1         | 0.32%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 256       | 83.39%  |
| GPT     | 26        | 8.47%   |
| MBR     | 25        | 8.14%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 286       | 92.26%  |
| Yes       | 24        | 7.74%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 267       | 86.41%  |
| Yes       | 42        | 13.59%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 52        | 16.99%  |
| Dell                | 42        | 13.73%  |
| ASUSTek Computer    | 40        | 13.07%  |
| Lenovo              | 33        | 10.78%  |
| Acer                | 20        | 6.54%   |
| Toshiba             | 17        | 5.56%   |
| Gigabyte Technology | 11        | 3.59%   |
| Samsung Electronics | 8         | 2.61%   |
| Intel               | 8         | 2.61%   |
| Fujitsu Siemens     | 7         | 2.29%   |
| Sony                | 6         | 1.96%   |
| Google              | 5         | 1.63%   |
| eMachines           | 5         | 1.63%   |
| ECS                 | 5         | 1.63%   |
| ASRock              | 5         | 1.63%   |
| Positivo            | 3         | 0.98%   |
| Pegatron            | 3         | 0.98%   |
| Packard Bell        | 3         | 0.98%   |
| MSI                 | 3         | 0.98%   |
| Medion              | 3         | 0.98%   |
| Gateway             | 3         | 0.98%   |
| Apple               | 3         | 0.98%   |
| Unknown             | 3         | 0.98%   |
| IBM                 | 2         | 0.65%   |
| Fujitsu             | 2         | 0.65%   |
| Foxconn             | 2         | 0.65%   |
| Clevo               | 2         | 0.65%   |
| WinBook             | 1         | 0.33%   |
| SiS                 | 1         | 0.33%   |
| Olivetti            | 1         | 0.33%   |
| Nvidia              | 1         | 0.33%   |
| LincPlus            | 1         | 0.33%   |
| JPSaCouto           | 1         | 0.33%   |
| Itautec             | 1         | 0.33%   |
| GPU Company         | 1         | 0.33%   |
| Biostar             | 1         | 0.33%   |
| AAEON               | 1         | 0.33%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Lenovo IdeaPad 2in1 14 81CW                 | 3         | 0.98%   |
| Lenovo G500 20236                           | 3         | 0.98%   |
| HP Compaq dc7900 Convertible Minitower      | 3         | 0.98%   |
| Unknown                                     | 3         | 0.98%   |
| Toshiba Satellite M70                       | 2         | 0.65%   |
| Toshiba Satellite L500                      | 2         | 0.65%   |
| Samsung N150P/N210P/N220P                   | 2         | 0.65%   |
| Positivo Mobile                             | 2         | 0.65%   |
| Lenovo MIIX 310-10ICR 80SG                  | 2         | 0.65%   |
| HP Compaq 8200 Elite CMT PC                 | 2         | 0.65%   |
| Google Banon                                | 2         | 0.65%   |
| Fujitsu Siemens ESPRIMO Mobile V5535        | 2         | 0.65%   |
| Fujitsu Siemens D1931                       | 2         | 0.65%   |
| Dell Latitude D630                          | 2         | 0.65%   |
| Dell Inspiron N5050                         | 2         | 0.65%   |
| Dell Inspiron 1545                          | 2         | 0.65%   |
| ASRock N68-S3 FX                            | 2         | 0.65%   |
| Acer Extensa 5630                           | 2         | 0.65%   |
| WinBook GL Series                           | 1         | 0.33%   |
| Toshiba Satellite Pro C850                  | 1         | 0.33%   |
| Toshiba Satellite L750D                     | 1         | 0.33%   |
| Toshiba Satellite L310                      | 1         | 0.33%   |
| Toshiba Satellite L300                      | 1         | 0.33%   |
| Toshiba Satellite C850-F117                 | 1         | 0.33%   |
| Toshiba Satellite C660                      | 1         | 0.33%   |
| Toshiba Satellite C55D-B                    | 1         | 0.33%   |
| Toshiba Satellite C50-A-1DV                 | 1         | 0.33%   |
| Toshiba QOSMIO F755                         | 1         | 0.33%   |
| Toshiba PORTEGE R500                        | 1         | 0.33%   |
| Toshiba NB520                               | 1         | 0.33%   |
| Toshiba NB500                               | 1         | 0.33%   |
| Toshiba dynabook Satellite B552/H           | 1         | 0.33%   |
| Sony VPCZ21V9E                              | 1         | 0.33%   |
| Sony VPCEA36FM                              | 1         | 0.33%   |
| Sony VPCCW21FX                              | 1         | 0.33%   |
| Sony VGN-S55B_S                             | 1         | 0.33%   |
| Sony VGN-FW140E                             | 1         | 0.33%   |
| Sony VGN-CR21S_P                            | 1         | 0.33%   |
| SiS M672+968                                | 1         | 0.33%   |
| Samsung RV411/RV511/E3511/S3511/RV711/E3411 | 1         | 0.33%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| HP Compaq               | 17        | 5.56%   |
| Dell Inspiron           | 17        | 5.56%   |
| Toshiba Satellite       | 12        | 3.92%   |
| Lenovo ThinkPad         | 12        | 3.92%   |
| Acer Aspire             | 11        | 3.59%   |
| HP Pavilion             | 9         | 2.94%   |
| Dell Latitude           | 9         | 2.94%   |
| Lenovo IdeaPad          | 7         | 2.29%   |
| HP EliteBook            | 6         | 1.96%   |
| Dell OptiPlex           | 6         | 1.96%   |
| HP Laptop               | 4         | 1.31%   |
| Acer Extensa            | 4         | 1.31%   |
| Samsung N150P           | 3         | 0.98%   |
| Packard Bell EasyNote   | 3         | 0.98%   |
| Lenovo G500             | 3         | 0.98%   |
| Fujitsu Siemens AMILO   | 3         | 0.98%   |
| Dell Vostro             | 3         | 0.98%   |
| Dell Precision          | 3         | 0.98%   |
| Unknown                 | 3         | 0.98%   |
| Positivo Mobile         | 2         | 0.65%   |
| Lenovo MIIX             | 2         | 0.65%   |
| IBM ThinkPad            | 2         | 0.65%   |
| HP Stream               | 2         | 0.65%   |
| HP Mini                 | 2         | 0.65%   |
| HP 255                  | 2         | 0.65%   |
| Google Banon            | 2         | 0.65%   |
| Fujitsu Siemens ESPRIMO | 2         | 0.65%   |
| Fujitsu Siemens D1931   | 2         | 0.65%   |
| ASUS SABERTOOTH         | 2         | 0.65%   |
| ASUS ROG                | 2         | 0.65%   |
| ASRock N68-S3           | 2         | 0.65%   |
| WinBook GL              | 1         | 0.33%   |
| Toshiba QOSMIO          | 1         | 0.33%   |
| Toshiba PORTEGE         | 1         | 0.33%   |
| Toshiba NB520           | 1         | 0.33%   |
| Toshiba NB500           | 1         | 0.33%   |
| Toshiba dynabook        | 1         | 0.33%   |
| Sony VPCZ21V9E          | 1         | 0.33%   |
| Sony VPCEA36FM          | 1         | 0.33%   |
| Sony VPCCW21FX          | 1         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2008    | 42        | 13.73%  |
| 2007    | 32        | 10.46%  |
| 2011    | 30        | 9.8%    |
| 2010    | 27        | 8.82%   |
| 2009    | 25        | 8.17%   |
| 2012    | 24        | 7.84%   |
| 2013    | 23        | 7.52%   |
| 2006    | 23        | 7.52%   |
| 2017    | 12        | 3.92%   |
| 2015    | 11        | 3.59%   |
| 2005    | 11        | 3.59%   |
| 2018    | 10        | 3.27%   |
| 2016    | 8         | 2.61%   |
| 2014    | 8         | 2.61%   |
| 2019    | 6         | 1.96%   |
| 2020    | 5         | 1.63%   |
| 2023    | 2         | 0.65%   |
| 2022    | 2         | 0.65%   |
| 2004    | 2         | 0.65%   |
| 2021    | 1         | 0.33%   |
| 2001    | 1         | 0.33%   |
| Unknown | 1         | 0.33%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 196       | 64.05%  |
| Desktop     | 100       | 32.68%  |
| Convertible | 3         | 0.98%   |
| Mini pc     | 3         | 0.98%   |
| Tablet      | 2         | 0.65%   |
| All in one  | 2         | 0.65%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 297       | 97.06%  |
| Enabled  | 9         | 2.94%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 300       | 98.04%  |
| Yes  | 6         | 1.96%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 93        | 29.81%  |
| 1.01-2.0   | 79        | 25.32%  |
| 4.01-8.0   | 44        | 14.1%   |
| 8.01-16.0  | 29        | 9.29%   |
| 2.01-3.0   | 22        | 7.05%   |
| 0.51-1.0   | 22        | 7.05%   |
| 16.01-24.0 | 13        | 4.17%   |
| 32.01-64.0 | 7         | 2.24%   |
| 24.01-32.0 | 2         | 0.64%   |
| 0.01-0.5   | 1         | 0.32%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 124       | 36.9%   |
| 0.51-1.0  | 123       | 36.61%  |
| 2.01-3.0  | 40        | 11.9%   |
| 0.01-0.5  | 23        | 6.85%   |
| 3.01-4.0  | 15        | 4.46%   |
| 4.01-8.0  | 9         | 2.68%   |
| 8.01-16.0 | 2         | 0.6%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 227       | 72.52%  |
| 2      | 62        | 19.81%  |
| 3      | 13        | 4.15%   |
| 0      | 4         | 1.28%   |
| 4      | 3         | 0.96%   |
| 6      | 2         | 0.64%   |
| 7      | 1         | 0.32%   |
| 5      | 1         | 0.32%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 185       | 60.06%  |
| No        | 123       | 39.94%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 280       | 91.5%   |
| No        | 26        | 8.5%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 255       | 83.33%  |
| No        | 51        | 16.67%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 179       | 58.31%  |
| Yes       | 128       | 41.69%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 90        | 29.32%  |
| Germany      | 26        | 8.47%   |
| Italy        | 21        | 6.84%   |
| UK           | 18        | 5.86%   |
| Brazil       | 16        | 5.21%   |
| Poland       | 11        | 3.58%   |
| Canada       | 11        | 3.58%   |
| Netherlands  | 10        | 3.26%   |
| Argentina    | 8         | 2.61%   |
| Romania      | 7         | 2.28%   |
| India        | 7         | 2.28%   |
| Sweden       | 6         | 1.95%   |
| Russia       | 6         | 1.95%   |
| France       | 6         | 1.95%   |
| Spain        | 5         | 1.63%   |
| Mexico       | 5         | 1.63%   |
| Finland      | 5         | 1.63%   |
| New Zealand  | 4         | 1.3%    |
| Greece       | 4         | 1.3%    |
| Portugal     | 3         | 0.98%   |
| Philippines  | 3         | 0.98%   |
| Japan        | 3         | 0.98%   |
| South Africa | 2         | 0.65%   |
| Peru         | 2         | 0.65%   |
| Ireland      | 2         | 0.65%   |
| Bolivia      | 2         | 0.65%   |
| Belgium      | 2         | 0.65%   |
| Australia    | 2         | 0.65%   |
| Algeria      | 2         | 0.65%   |
| Ukraine      | 1         | 0.33%   |
| Turkey       | 1         | 0.33%   |
| Switzerland  | 1         | 0.33%   |
| Serbia       | 1         | 0.33%   |
| Puerto Rico  | 1         | 0.33%   |
| Panama       | 1         | 0.33%   |
| Norway       | 1         | 0.33%   |
| Namibia      | 1         | 0.33%   |
| Malaysia     | 1         | 0.33%   |
| Lithuania    | 1         | 0.33%   |
| Latvia       | 1         | 0.33%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                   | Computers | Percent |
|------------------------|-----------|---------|
| Toronto                | 4         | 1.25%   |
| Charlotte              | 4         | 1.25%   |
| Bucharest              | 4         | 1.25%   |
| Villingen-Schwenningen | 3         | 0.94%   |
| Turin                  | 3         | 0.94%   |
| New York               | 3         | 0.94%   |
| Auckland               | 3         | 0.94%   |
| Warsaw                 | 2         | 0.63%   |
| Topeka                 | 2         | 0.63%   |
| Tokyo                  | 2         | 0.63%   |
| Tahlequah              | 2         | 0.63%   |
| Spokane                | 2         | 0.63%   |
| Siemianowice Śląskie | 2         | 0.63%   |
| Seattle                | 2         | 0.63%   |
| Poznan                 | 2         | 0.63%   |
| Perth                  | 2         | 0.63%   |
| Osasco                 | 2         | 0.63%   |
| Naples                 | 2         | 0.63%   |
| Moscow                 | 2         | 0.63%   |
| Lima                   | 2         | 0.63%   |
| Helsinki               | 2         | 0.63%   |
| Hamburg                | 2         | 0.63%   |
| Friesoythe             | 2         | 0.63%   |
| Fayetteville           | 2         | 0.63%   |
| Dublin                 | 2         | 0.63%   |
| Cavallino              | 2         | 0.63%   |
| Buenos Aires           | 2         | 0.63%   |
| Brunswick              | 2         | 0.63%   |
| Berlin                 | 2         | 0.63%   |
| Bengaluru              | 2         | 0.63%   |
| Atlanta                | 2         | 0.63%   |
| Airdrie                | 2         | 0.63%   |
| Zgierz                 | 1         | 0.31%   |
| York                   | 1         | 0.31%   |
| Yokohama               | 1         | 0.31%   |
| Wysokie Mazowieckie    | 1         | 0.31%   |
| Wroclaw                | 1         | 0.31%   |
| Worthing               | 1         | 0.31%   |
| Windhoek               | 1         | 0.31%   |
| West New York          | 1         | 0.31%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 74        | 82     | 20.11%  |
| WDC                         | 73        | 98     | 19.84%  |
| Samsung Electronics         | 36        | 51     | 9.78%   |
| Hitachi                     | 30        | 40     | 8.15%   |
| Unknown                     | 27        | 33     | 7.34%   |
| Toshiba                     | 25        | 26     | 6.79%   |
| Kingston                    | 16        | 20     | 4.35%   |
| Maxtor                      | 11        | 13     | 2.99%   |
| SanDisk                     | 9         | 10     | 2.45%   |
| HGST                        | 7         | 8      | 1.9%    |
| Fujitsu                     | 6         | 7      | 1.63%   |
| PNY                         | 4         | 5      | 1.09%   |
| GOODRAM                     | 4         | 5      | 1.09%   |
| Crucial                     | 4         | 6      | 1.09%   |
| China                       | 4         | 4      | 1.09%   |
| Intenso                     | 3         | 3      | 0.82%   |
| Intel                       | 3         | 4      | 0.82%   |
| Micron Technology           | 2         | 2      | 0.54%   |
| Integral                    | 2         | 2      | 0.54%   |
| ASMT                        | 2         | 3      | 0.54%   |
| Zheino                      | 1         | 1      | 0.27%   |
| WD MediaMax                 | 1         | 1      | 0.27%   |
| USB3.0                      | 1         | 1      | 0.27%   |
| TrekStor                    | 1         | 1      | 0.27%   |
| TCSUNBOW                    | 1         | 1      | 0.27%   |
| SK hynix                    | 1         | 1      | 0.27%   |
| SABRENT                     | 1         | 1      | 0.27%   |
| Realtek Semiconductor       | 1         | 1      | 0.27%   |
| Phison Electronics          | 1         | 2      | 0.27%   |
| Phison                      | 1         | 2      | 0.27%   |
| Patriot                     | 1         | 1      | 0.27%   |
| OCZ                         | 1         | 1      | 0.27%   |
| LITEONIT                    | 1         | 1      | 0.27%   |
| Lexar                       | 1         | 1      | 0.27%   |
| Kingston Technology Company | 1         | 1      | 0.27%   |
| KingSpec                    | 1         | 1      | 0.27%   |
| HS-SSD-C100                 | 1         | 1      | 0.27%   |
| GAMER                       | 1         | 1      | 0.27%   |
| FATTYDOVE                   | 1         | 1      | 0.27%   |
| Drevo                       | 1         | 1      | 0.27%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST500LM012 HN-M500MBB 500GB | 7         | 1.83%   |
| Unknown MMC Card  32GB              | 6         | 1.57%   |
| Kingston SA400S37120G 120GB SSD     | 6         | 1.57%   |
| Seagate ST9500325AS 500GB           | 4         | 1.04%   |
| Seagate ST9320325AS 320GB           | 4         | 1.04%   |
| Seagate ST9250315AS 250GB           | 4         | 1.04%   |
| Seagate ST500LT012-1DG142 500GB     | 4         | 1.04%   |
| Kingston SA400S37240G 240GB SSD     | 4         | 1.04%   |
| Unknown MMC Card  64GB              | 3         | 0.78%   |
| Unknown MMC Card  16GB              | 3         | 0.78%   |
| Toshiba MQ01ABF050 500GB            | 3         | 0.78%   |
| Seagate ST3500418AS 500GB           | 3         | 0.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 3         | 0.78%   |
| SanDisk SDSSDA120G 120GB            | 3         | 0.78%   |
| Samsung SSD 850 EVO 250GB           | 3         | 0.78%   |
| Hitachi HTS545025B9A300 250GB       | 3         | 0.78%   |
| Hitachi HDT721016SLA380 160GB       | 3         | 0.78%   |
| GOODRAM SSDPR-CL100-120-G2 120GB    | 3         | 0.78%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 2         | 0.52%   |
| WDC WD3200BPVT-24JJ5T0 320GB        | 2         | 0.52%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 2         | 0.52%   |
| WDC WD2500BEVT-22A23T0 250GB        | 2         | 0.52%   |
| WDC WD1200BEVS-22UST0 120GB         | 2         | 0.52%   |
| WDC WD10EZEX-08WN4A0 1TB            | 2         | 0.52%   |
| Unknown SD/MMC/MS PRO 512GB         | 2         | 0.52%   |
| Unknown MMC Card  2GB               | 2         | 0.52%   |
| Toshiba MQ01ABD100 1TB              | 2         | 0.52%   |
| Toshiba MK5055GSX 500GB             | 2         | 0.52%   |
| Seagate ST9160314AS 40GB            | 2         | 0.52%   |
| Seagate ST9120822AS 120GB           | 2         | 0.52%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 2         | 0.52%   |
| Seagate ST3250310AS 250GB           | 2         | 0.52%   |
| Seagate ST3160813AS 160GB           | 2         | 0.52%   |
| Seagate ST1000LM035-1RK172 1TB      | 2         | 0.52%   |
| Seagate ST1000DM003-9YN162 1TB      | 2         | 0.52%   |
| SanDisk DF4032  32GB                | 2         | 0.52%   |
| Samsung SSD 860 EVO 1TB             | 2         | 0.52%   |
| Samsung SSD 850 EVO 500GB           | 2         | 0.52%   |
| Samsung HM160HI 160GB               | 2         | 0.52%   |
| PNY CS900 120GB SSD                 | 2         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 73        | 81     | 30.04%  |
| WDC                 | 69        | 94     | 28.4%   |
| Hitachi             | 30        | 40     | 12.35%  |
| Toshiba             | 24        | 25     | 9.88%   |
| Samsung Electronics | 18        | 21     | 7.41%   |
| Maxtor              | 11        | 13     | 4.53%   |
| HGST                | 7         | 8      | 2.88%   |
| Fujitsu             | 6         | 7      | 2.47%   |
| Unknown             | 2         | 2      | 0.82%   |
| WD MediaMax         | 1         | 1      | 0.41%   |
| USB3.0              | 1         | 1      | 0.41%   |
| ASMT                | 1         | 2      | 0.41%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 16        | 20     | 19.28%  |
| Samsung Electronics | 15        | 26     | 18.07%  |
| SanDisk             | 7         | 8      | 8.43%   |
| WDC                 | 4         | 4      | 4.82%   |
| PNY                 | 4         | 5      | 4.82%   |
| GOODRAM             | 4         | 5      | 4.82%   |
| Crucial             | 4         | 6      | 4.82%   |
| China               | 4         | 4      | 4.82%   |
| Intel               | 3         | 4      | 3.61%   |
| Intenso             | 2         | 2      | 2.41%   |
| Integral            | 2         | 2      | 2.41%   |
| Zheino              | 1         | 1      | 1.2%    |
| TrekStor            | 1         | 1      | 1.2%    |
| Toshiba             | 1         | 1      | 1.2%    |
| TCSUNBOW            | 1         | 1      | 1.2%    |
| Patriot             | 1         | 1      | 1.2%    |
| OCZ                 | 1         | 1      | 1.2%    |
| Micron Technology   | 1         | 1      | 1.2%    |
| LITEONIT            | 1         | 1      | 1.2%    |
| Lexar               | 1         | 1      | 1.2%    |
| KingSpec            | 1         | 1      | 1.2%    |
| GAMER               | 1         | 1      | 1.2%    |
| FATTYDOVE           | 1         | 1      | 1.2%    |
| Drevo               | 1         | 1      | 1.2%    |
| Dogfish             | 1         | 1      | 1.2%    |
| BHT                 | 1         | 2      | 1.2%    |
| ASMT                | 1         | 1      | 1.2%    |
| Apple               | 1         | 1      | 1.2%    |
| Apacer              | 1         | 3      | 1.2%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 221       | 295    | 64.43%  |
| SSD     | 82        | 107    | 23.91%  |
| MMC     | 26        | 32     | 7.58%   |
| NVMe    | 8         | 12     | 2.33%   |
| Unknown | 6         | 7      | 1.75%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 278       | 396    | 86.07%  |
| MMC  | 26        | 32     | 8.05%   |
| SAS  | 11        | 13     | 3.41%   |
| NVMe | 8         | 12     | 2.48%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 247       | 327    | 80.19%  |
| 0.51-1.0   | 48        | 55     | 15.58%  |
| 1.01-2.0   | 11        | 15     | 3.57%   |
| 2.01-3.0   | 1         | 4      | 0.32%   |
| 4.01-10.0  | 1         | 1      | 0.32%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 113       | 35.99%  |
| 251-500        | 56        | 17.83%  |
| 51-100         | 46        | 14.65%  |
| 21-50          | 29        | 9.24%   |
| 501-1000       | 29        | 9.24%   |
| 1-20           | 21        | 6.69%   |
| 1001-2000      | 10        | 3.18%   |
| Unknown        | 4         | 1.27%   |
| More than 3000 | 3         | 0.96%   |
| 2001-3000      | 3         | 0.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 197       | 61.18%  |
| 21-50          | 59        | 18.32%  |
| 51-100         | 26        | 8.07%   |
| 101-250        | 22        | 6.83%   |
| 501-1000       | 7         | 2.17%   |
| 1001-2000      | 4         | 1.24%   |
| Unknown        | 4         | 1.24%   |
| 251-500        | 2         | 0.62%   |
| More than 3000 | 1         | 0.31%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD5000LPVX-22V0TT0 500GB        | 1         | 1      | 7.69%   |
| WDC WD1001FALS-00J7B0 1TB           | 1         | 1      | 7.69%   |
| Toshiba MQ01ABD100 1TB              | 1         | 1      | 7.69%   |
| Seagate ST9500420AS 500GB           | 1         | 1      | 7.69%   |
| Seagate ST9250315AS 250GB           | 1         | 1      | 7.69%   |
| Seagate ST9120822AS 120GB           | 1         | 1      | 7.69%   |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 7.69%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1         | 1      | 7.69%   |
| Seagate ST31500341AS 1TB            | 1         | 1      | 7.69%   |
| Seagate ST2000DM008-2FR102 2TB      | 1         | 1      | 7.69%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 1         | 1      | 7.69%   |
| Hitachi HTS545016B9SA00 160GB       | 1         | 1      | 7.69%   |
| HGST HTS725050A7E630 500GB          | 1         | 1      | 7.69%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 8      | 61.54%  |
| WDC     | 2         | 2      | 15.38%  |
| Toshiba | 1         | 1      | 7.69%   |
| Hitachi | 1         | 1      | 7.69%   |
| HGST    | 1         | 1      | 7.69%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 8         | 8      | 61.54%  |
| WDC     | 2         | 2      | 15.38%  |
| Toshiba | 1         | 1      | 7.69%   |
| Hitachi | 1         | 1      | 7.69%   |
| HGST    | 1         | 1      | 7.69%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 13        | 13     | 100%    |

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
| Detected | 268       | 407    | 86.45%  |
| Works    | 29        | 33     | 9.35%   |
| Malfunc  | 13        | 13     | 4.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 213       | 68.93%  |
| AMD                              | 39        | 12.62%  |
| Nvidia                           | 18        | 5.83%   |
| VIA Technologies                 | 7         | 2.27%   |
| Silicon Integrated Systems [SiS] | 7         | 2.27%   |
| JMicron Technology               | 6         | 1.94%   |
| Samsung Electronics              | 5         | 1.62%   |
| Marvell Technology Group         | 5         | 1.62%   |
| ULi Electronics                  | 1         | 0.32%   |
| Silicon Image                    | 1         | 0.32%   |
| Realtek Semiconductor            | 1         | 0.32%   |
| Phison Electronics               | 1         | 0.32%   |
| Micron Technology                | 1         | 0.32%   |
| LSI Logic / Symbios Logic        | 1         | 0.32%   |
| Kingston Technology Company      | 1         | 0.32%   |
| ASMedia Technology               | 1         | 0.32%   |
| ADATA Technology                 | 1         | 0.32%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel 82801G (ICH7 Family) IDE Controller                                      | 27        | 6.6%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 23        | 5.62%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 20        | 4.89%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 17        | 4.16%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 15        | 3.67%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 13        | 3.18%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 13        | 3.18%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 11        | 2.69%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 2.44%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 9         | 2.2%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 9         | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 9         | 2.2%    |
| Silicon Integrated Systems [SiS] 5513 IDE Controller                           | 7         | 1.71%   |
| Nvidia MCP61 SATA Controller                                                   | 7         | 1.71%   |
| VIA VT82C586A/B/VT82C686/A/B/VT823x/A/C PIPC Bus Master IDE                    | 6         | 1.47%   |
| Silicon Integrated Systems [SiS] SATA Controller / IDE mode                    | 6         | 1.47%   |
| Nvidia MCP61 IDE                                                               | 6         | 1.47%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 6         | 1.47%   |
| Intel 82801FBM (ICH6M) SATA Controller                                         | 6         | 1.47%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 6         | 1.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6         | 1.47%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 6         | 1.47%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 5         | 1.22%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 5         | 1.22%   |
| Intel 4 Series Chipset PT IDER Controller                                      | 5         | 1.22%   |
| Intel SATA Controller [RAID mode]                                              | 4         | 0.98%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 4         | 0.98%   |
| Intel 82801JD/DO (ICH10 Family) 4-port SATA IDE Controller                     | 4         | 0.98%   |
| Intel 82801JD/DO (ICH10 Family) 2-port SATA IDE Controller                     | 4         | 0.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                   | 4         | 0.98%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                   | 4         | 0.98%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 4         | 0.98%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                  | 4         | 0.98%   |
| AMD IXP SB4x0 IDE Controller                                                   | 4         | 0.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 3         | 0.73%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 3         | 0.73%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]           | 3         | 0.73%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                   | 3         | 0.73%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 3         | 0.73%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 3         | 0.73%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 177       | 53.96%  |
| IDE  | 126       | 38.41%  |
| RAID | 16        | 4.88%   |
| NVMe | 8         | 2.44%   |
| SAS  | 1         | 0.3%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 255       | 83.33%  |
| AMD          | 50        | 16.34%  |
| CentaurHauls | 1         | 0.33%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Atom CPU N270 @ 1.60GHz               | 9         | 2.93%   |
| Intel Pentium M processor 1.73GHz           | 6         | 1.95%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 6         | 1.95%   |
| Intel Atom CPU N450 @ 1.66GHz               | 6         | 1.95%   |
| Intel Core 2 Quad CPU Q9400 @ 2.66GHz       | 4         | 1.3%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 4         | 1.3%    |
| Intel Atom CPU N455 @ 1.66GHz               | 4         | 1.3%    |
| Intel Pentium Dual-Core CPU T4200 @ 2.00GHz | 3         | 0.98%   |
| Intel Pentium CPU 4415U @ 2.30GHz           | 3         | 0.98%   |
| Intel Pentium CPU 2020M @ 2.40GHz           | 3         | 0.98%   |
| Intel Pentium 4 CPU 3.00GHz                 | 3         | 0.98%   |
| Intel Genuine CPU T2050 @ 1.60GHz           | 3         | 0.98%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 3         | 0.98%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 3         | 0.98%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 3         | 0.98%   |
| Intel Core 2 CPU T5600 @ 1.83GHz            | 3         | 0.98%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 2         | 0.65%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 2         | 0.65%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 2         | 0.65%   |
| Intel Pentium D CPU 2.80GHz                 | 2         | 0.65%   |
| Intel Pentium CPU N3540 @ 2.16GHz           | 2         | 0.65%   |
| Intel Pentium 4 CPU 3.40GHz                 | 2         | 0.65%   |
| Intel Genuine CPU U4100 @ 1.30GHz           | 2         | 0.65%   |
| Intel Genuine CPU T2130 @ 1.86GHz           | 2         | 0.65%   |
| Intel Genuine CPU 575 @ 2.00GHz             | 2         | 0.65%   |
| Intel Core i7-3632QM CPU @ 2.20GHz          | 2         | 0.65%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 2         | 0.65%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 2         | 0.65%   |
| Intel Core i5-4300U CPU @ 1.90GHz           | 2         | 0.65%   |
| Intel Core i5-3337U CPU @ 1.80GHz           | 2         | 0.65%   |
| Intel Core i3-3120M CPU @ 2.50GHz           | 2         | 0.65%   |
| Intel Core i3-3110M CPU @ 2.40GHz           | 2         | 0.65%   |
| Intel Core i3-2330M CPU @ 2.20GHz           | 2         | 0.65%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 2         | 0.65%   |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 2         | 0.65%   |
| Intel Core 2 Duo CPU T5800 @ 2.00GHz        | 2         | 0.65%   |
| Intel Core 2 Duo CPU T5550 @ 1.83GHz        | 2         | 0.65%   |
| Intel Core 2 Duo CPU L9400 @ 1.86GHz        | 2         | 0.65%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 2         | 0.65%   |
| Intel Core 2 CPU U7600 @ 1.20GHz            | 2         | 0.65%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Celeron           | 36        | 11.76%  |
| Intel Atom              | 32        | 10.46%  |
| Intel Core i5           | 28        | 9.15%   |
| Intel Core i7           | 24        | 7.84%   |
| Intel Core 2 Duo        | 23        | 7.52%   |
| Intel Pentium           | 16        | 5.23%   |
| Intel Core i3           | 16        | 5.23%   |
| Intel Pentium Dual-Core | 13        | 4.25%   |
| Intel Genuine           | 12        | 3.92%   |
| Intel Core 2            | 11        | 3.59%   |
| Intel Core 2 Quad       | 10        | 3.27%   |
| Intel Pentium 4         | 8         | 2.61%   |
| Intel Pentium M         | 7         | 2.29%   |
| Intel Pentium Dual      | 7         | 2.29%   |
| AMD Athlon 64 X2        | 7         | 2.29%   |
| Other                   | 4         | 1.31%   |
| Intel Xeon              | 4         | 1.31%   |
| AMD A8                  | 4         | 1.31%   |
| Intel Pentium D         | 3         | 0.98%   |
| AMD Phenom II X4        | 3         | 0.98%   |
| AMD E1                  | 3         | 0.98%   |
| AMD E                   | 3         | 0.98%   |
| AMD Turion 64 X2 Mobile | 2         | 0.65%   |
| AMD Sempron             | 2         | 0.65%   |
| AMD FX                  | 2         | 0.65%   |
| AMD E2                  | 2         | 0.65%   |
| AMD Athlon II X2        | 2         | 0.65%   |
| AMD Athlon              | 2         | 0.65%   |
| AMD A6                  | 2         | 0.65%   |
| AMD A4                  | 2         | 0.65%   |
| Intel Pentium Silver    | 1         | 0.33%   |
| Intel Core Duo          | 1         | 0.33%   |
| Intel Celeron M         | 1         | 0.33%   |
| Intel Celeron Dual-Core | 1         | 0.33%   |
| CentaurHauls VIA C7     | 1         | 0.33%   |
| AMD Turion 64 Mobile    | 1         | 0.33%   |
| AMD Ryzen 7             | 1         | 0.33%   |
| AMD Ryzen 5             | 1         | 0.33%   |
| AMD Ryzen 3             | 1         | 0.33%   |
| AMD Phenom II           | 1         | 0.33%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 167       | 54.58%  |
| 4      | 66        | 21.57%  |
| 1      | 66        | 21.57%  |
| 6      | 5         | 1.63%   |
| 8      | 1         | 0.33%   |
| 3      | 1         | 0.33%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 306       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 194       | 63.4%   |
| 2      | 112       | 36.6%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 255       | 82.79%  |
| 32-bit         | 33        | 10.71%  |
| Unknown        | 20        | 6.49%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 37        | 11.9%   |
| 0x1067a    | 32        | 10.29%  |
| 0x306a9    | 23        | 7.4%    |
| 0x206a7    | 19        | 6.11%   |
| 0x6fd      | 18        | 5.79%   |
| 0x106ca    | 13        | 4.18%   |
| 0x106c2    | 13        | 4.18%   |
| 0x406c4    | 10        | 3.22%   |
| 0x10661    | 8         | 2.57%   |
| 0x6d8      | 7         | 2.25%   |
| 0x30678    | 7         | 2.25%   |
| 0x20655    | 7         | 2.25%   |
| 0x806e9    | 6         | 1.93%   |
| 0x6f6      | 6         | 1.93%   |
| 0x6e8      | 6         | 1.93%   |
| 0x05000119 | 6         | 1.93%   |
| 0x010000c8 | 5         | 1.61%   |
| 0xf41      | 4         | 1.29%   |
| 0x6fb      | 4         | 1.29%   |
| 0x6f2      | 4         | 1.29%   |
| 0x6ec      | 4         | 1.29%   |
| 0x10676    | 4         | 1.29%   |
| 0x806ec    | 3         | 0.96%   |
| 0x806ea    | 3         | 0.96%   |
| 0x706a8    | 3         | 0.96%   |
| 0x40651    | 3         | 0.96%   |
| 0x07030105 | 3         | 0.96%   |
| 0x06006705 | 3         | 0.96%   |
| 0x06001119 | 3         | 0.96%   |
| 0xf65      | 2         | 0.64%   |
| 0xf47      | 2         | 0.64%   |
| 0x906ea    | 2         | 0.64%   |
| 0x706a1    | 2         | 0.64%   |
| 0x306d4    | 2         | 0.64%   |
| 0x306c3    | 2         | 0.64%   |
| 0x30673    | 2         | 0.64%   |
| 0x206c2    | 2         | 0.64%   |
| 0x20652    | 2         | 0.64%   |
| 0x106a5    | 2         | 0.64%   |
| 0x07030106 | 2         | 0.64%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Core            | 42        | 13.68%  |
| Penryn          | 39        | 12.7%   |
| Bonnell         | 27        | 8.79%   |
| IvyBridge       | 26        | 8.47%   |
| Silvermont      | 20        | 6.51%   |
| SandyBridge     | 19        | 6.19%   |
| P6              | 17        | 5.54%   |
| KabyLake        | 15        | 4.89%   |
| Westmere        | 14        | 4.56%   |
| NetBurst        | 13        | 4.23%   |
| K8 Hammer       | 12        | 3.91%   |
| K10             | 9         | 2.93%   |
| Haswell         | 8         | 2.61%   |
| Bobcat          | 7         | 2.28%   |
| Piledriver      | 6         | 1.95%   |
| Puma            | 5         | 1.63%   |
| Goldmont plus   | 5         | 1.63%   |
| Excavator       | 5         | 1.63%   |
| Nehalem         | 3         | 0.98%   |
| Broadwell       | 3         | 0.98%   |
| Zen 3           | 2         | 0.65%   |
| Goldmont        | 2         | 0.65%   |
| Zen+            | 1         | 0.33%   |
| Zen 2           | 1         | 0.33%   |
| Zen             | 1         | 0.33%   |
| TigerLake       | 1         | 0.33%   |
| Skylake         | 1         | 0.33%   |
| K8 & K10 hybrid | 1         | 0.33%   |
| Jaguar          | 1         | 0.33%   |
| Unknown         | 1         | 0.33%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 194       | 60.82%  |
| Nvidia                           | 61        | 19.12%  |
| AMD                              | 54        | 16.93%  |
| VIA Technologies                 | 5         | 1.57%   |
| Silicon Integrated Systems [SiS] | 5         | 1.57%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 24        | 6.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 20        | 5.56%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 19        | 5.28%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 4.17%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 14        | 3.89%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 12        | 3.33%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 11        | 3.06%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 11        | 3.06%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 11        | 3.06%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 10        | 2.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 9         | 2.5%    |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 2.22%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 8         | 2.22%   |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 6         | 1.67%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 5         | 1.39%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 5         | 1.39%   |
| VIA Technologies CN896/VN896/P4M900 [Chrome 9 HC]                                        | 4         | 1.11%   |
| Intel UHD Graphics 620                                                                   | 4         | 1.11%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.11%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3         | 0.83%   |
| Intel HD Graphics 620                                                                    | 3         | 0.83%   |
| Intel HD Graphics 610                                                                    | 3         | 0.83%   |
| Intel HD Graphics 5500                                                                   | 3         | 0.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 3         | 0.83%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 3         | 0.83%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3         | 0.83%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 3         | 0.83%   |
| AMD RV620 LE [Radeon HD 3450]                                                            | 3         | 0.83%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 3         | 0.83%   |
| Nvidia GT218M [GeForce 310M]                                                             | 2         | 0.56%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 2         | 0.56%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 2         | 0.56%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 2         | 0.56%   |
| Nvidia GK107GLM [Quadro K2000M]                                                          | 2         | 0.56%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 2         | 0.56%   |
| Nvidia G98M [GeForce 9200M GS]                                                           | 2         | 0.56%   |
| Nvidia G94 [GeForce 9600 GS]                                                             | 2         | 0.56%   |
| Nvidia G72 [GeForce 7200 GS / 7300 SE]                                                   | 2         | 0.56%   |
| Nvidia C73 [GeForce 7100 / nForce 630i]                                                  | 2         | 0.56%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 2         | 0.56%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 181       | 59.15%  |
| 1 x Nvidia     | 50        | 16.34%  |
| 1 x AMD        | 49        | 16.01%  |
| Intel + Nvidia | 10        | 3.27%   |
| 1 x VIA        | 5         | 1.63%   |
| 1 x SiS        | 5         | 1.63%   |
| 2 x AMD        | 4         | 1.31%   |
| Other          | 1         | 0.33%   |
| Intel + AMD    | 1         | 0.33%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 273       | 88.35%  |
| Proprietary | 19        | 6.15%   |
| Unknown     | 17        | 5.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 197       | 63.75%  |
| 0.01-0.5   | 69        | 22.33%  |
| 0.51-1.0   | 21        | 6.8%    |
| 1.01-2.0   | 14        | 4.53%   |
| 3.01-4.0   | 6         | 1.94%   |
| 7.01-8.0   | 1         | 0.32%   |
| 8.01-16.0  | 1         | 0.32%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 43        | 14.48%  |
| AU Optronics            | 43        | 14.48%  |
| LG Display              | 24        | 8.08%   |
| Dell                    | 16        | 5.39%   |
| LG Philips              | 14        | 4.71%   |
| Acer                    | 14        | 4.71%   |
| BOE                     | 11        | 3.7%    |
| Chi Mei Optoelectronics | 10        | 3.37%   |
| Hewlett-Packard         | 9         | 3.03%   |
| HannStar                | 9         | 3.03%   |
| Goldstar                | 9         | 3.03%   |
| Chimei Innolux          | 9         | 3.03%   |
| Lenovo                  | 8         | 2.69%   |
| BenQ                    | 7         | 2.36%   |
| Sony                    | 6         | 2.02%   |
| CPT                     | 5         | 1.68%   |
| InfoVision              | 4         | 1.35%   |
| AOC                     | 4         | 1.35%   |
| Ancor Communications    | 4         | 1.35%   |
| ViewSonic               | 3         | 1.01%   |
| LG Electronics          | 3         | 1.01%   |
| Hitachi                 | 3         | 1.01%   |
| Apple                   | 3         | 1.01%   |
| ___                     | 2         | 0.67%   |
| Unknown                 | 2         | 0.67%   |
| Toshiba                 | 2         | 0.67%   |
| Sharp                   | 2         | 0.67%   |
| Philips                 | 2         | 0.67%   |
| PANDA                   | 2         | 0.67%   |
| Optoma                  | 2         | 0.67%   |
| OEM                     | 2         | 0.67%   |
| Vizio                   | 1         | 0.34%   |
| VIZ                     | 1         | 0.34%   |
| Vestel Elektronik       | 1         | 0.34%   |
| Seiko/Epson             | 1         | 0.34%   |
| Sceptre Tech            | 1         | 0.34%   |
| Quanta Display          | 1         | 0.34%   |
| Panasonic               | 1         | 0.34%   |
| MPI                     | 1         | 0.34%   |
| LPL                     | 1         | 0.34%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 6         | 1.97%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 3         | 0.99%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.99%   |
| BOE LCD Monitor BOE0705 1366x768 309x173mm 13.9-inch                     | 3         | 0.99%   |
| ___ LCD TV ___0101 1920x1080                                             | 2         | 0.66%   |
| Unknown LCDTV16 0101 1920x1080 1600x900mm 72.3-inch                      | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SEC3445 1280x800 330x210mm 15.4-inch     | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SEC3052 1366x768 256x144mm 11.6-inch     | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.66%   |
| Samsung Electronics LCD Monitor SAM0DF3 3840x2160 1872x1053mm 84.6-inch  | 2         | 0.66%   |
| OEM 26W_LCD_TV OEM3700 1920x540                                          | 2         | 0.66%   |
| LG Philips LCD Monitor LPLE300 1280x800 331x207mm 15.4-inch              | 2         | 0.66%   |
| LG Philips LCD Monitor LPL3B01 1280x800 331x207mm 15.4-inch              | 2         | 0.66%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 2         | 0.66%   |
| LG Display LCD Monitor LGD02E3 1366x768 344x194mm 15.5-inch              | 2         | 0.66%   |
| InfoVision LCD Monitor IVO03F4 1920x1080 309x173mm 13.9-inch             | 2         | 0.66%   |
| Dell 1905FP DEL400C 1280x1024 376x301mm 19.0-inch                        | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 2         | 0.66%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch          | 2         | 0.66%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A2 1366x768 344x193mm 15.5-inch | 2         | 0.66%   |
| BenQ FP731 BNQ7659 1280x1024 304x228mm 15.0-inch                         | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO30D2 1024x600 223x125mm 10.1-inch            | 2         | 0.66%   |
| AU Optronics LCD Monitor AUO11C2 1024x600 195x113mm 8.9-inch             | 2         | 0.66%   |
| AOC 2590G4 AOC2590 1920x1080 544x303mm 24.5-inch                         | 2         | 0.66%   |
| Acer G276HL ACR0300 1920x1080 600x340mm 27.2-inch                        | 2         | 0.66%   |
| Vizio E321ME VIZ0067 1920x1080 698x392mm 31.5-inch                       | 1         | 0.33%   |
| VIZ LCD Monitor D50-D1 1920x1080                                         | 1         | 0.33%   |
| ViewSonic VG710s VSCA218 1280x1024 338x270mm 17.0-inch                   | 1         | 0.33%   |
| ViewSonic VG2230wm-EU VSCA21E 1680x1050 474x296mm 22.0-inch              | 1         | 0.33%   |
| ViewSonic VA2226w-11 VSC2051 1680x1050 495x291mm 22.6-inch               | 1         | 0.33%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch   | 1         | 0.33%   |
| Toshiba TV TSB0206 1920x1080 890x500mm 40.2-inch                         | 1         | 0.33%   |
| Toshiba LCD Monitor LCD58EF 1280x800 261x163mm 12.1-inch                 | 1         | 0.33%   |
| Sony TV SNYB800 1280x768 690x390mm 31.2-inch                             | 1         | 0.33%   |
| Sony TV SNY9500 720x480 560x420mm 27.6-inch                              | 1         | 0.33%   |
| Sony SDM-HX75 SNY5100 1280x1024 338x270mm 17.0-inch                      | 1         | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 89        | 29.97%  |
| 1920x1080 (FHD)    | 65        | 21.89%  |
| 1280x800 (WXGA)    | 33        | 11.11%  |
| 1280x1024 (SXGA)   | 17        | 5.72%   |
| 1024x600           | 14        | 4.71%   |
| 1600x900 (HD+)     | 11        | 3.7%    |
| 1024x768 (XGA)     | 10        | 3.37%   |
| 1440x900 (WXGA+)   | 9         | 3.03%   |
| 2560x1440 (QHD)    | 6         | 2.02%   |
| 1360x768           | 6         | 2.02%   |
| 3840x2160 (4K)     | 5         | 1.68%   |
| 1920x1200 (WUXGA)  | 5         | 1.68%   |
| 1680x1050 (WSXGA+) | 5         | 1.68%   |
| 1920x540           | 4         | 1.35%   |
| 1280x768           | 3         | 1.01%   |
| Unknown            | 3         | 1.01%   |
| 2560x1080          | 2         | 0.67%   |
| 1024x576           | 2         | 0.67%   |
| 3840x1200          | 1         | 0.34%   |
| 3840x1080          | 1         | 0.34%   |
| 2624x1200          | 1         | 0.34%   |
| 2048x1152          | 1         | 0.34%   |
| 1600x1200          | 1         | 0.34%   |
| 1400x1050          | 1         | 0.34%   |
| 1280x960           | 1         | 0.34%   |
| 1280x720 (HD)      | 1         | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 99        | 33.33%  |
| 14      | 21        | 7.07%   |
| 13      | 19        | 6.4%    |
| Unknown | 19        | 6.4%    |
| 17      | 18        | 6.06%   |
| 10      | 14        | 4.71%   |
| 19      | 12        | 4.04%   |
| 24      | 11        | 3.7%    |
| 21      | 10        | 3.37%   |
| 11      | 10        | 3.37%   |
| 27      | 9         | 3.03%   |
| 31      | 7         | 2.36%   |
| 23      | 7         | 2.36%   |
| 18      | 7         | 2.36%   |
| 84      | 5         | 1.68%   |
| 22      | 5         | 1.68%   |
| 12      | 5         | 1.68%   |
| 20      | 3         | 1.01%   |
| 72      | 2         | 0.67%   |
| 40      | 2         | 0.67%   |
| 34      | 2         | 0.67%   |
| 16      | 2         | 0.67%   |
| 8       | 2         | 0.67%   |
| 74      | 1         | 0.34%   |
| 52      | 1         | 0.34%   |
| 41      | 1         | 0.34%   |
| 39      | 1         | 0.34%   |
| 32      | 1         | 0.34%   |
| 26      | 1         | 0.34%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 133       | 44.93%  |
| 201-300     | 41        | 13.85%  |
| 401-500     | 29        | 9.8%    |
| 501-600     | 27        | 9.12%   |
| 351-400     | 21        | 7.09%   |
| Unknown     | 19        | 6.42%   |
| 601-700     | 8         | 2.7%    |
| 1501-2000   | 8         | 2.7%    |
| 801-900     | 3         | 1.01%   |
| 701-800     | 3         | 1.01%   |
| 101-200     | 2         | 0.68%   |
| 1001-1500   | 1         | 0.34%   |
| 901-1000    | 1         | 0.34%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 183       | 65.83%  |
| 16/10   | 47        | 16.91%  |
| Unknown | 15        | 5.4%    |
| 5/4     | 14        | 5.04%   |
| 4/3     | 12        | 4.32%   |
| 6/5     | 4         | 1.44%   |
| 21/9    | 2         | 0.72%   |
| 1.00    | 1         | 0.36%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 99        | 33.45%  |
| 81-90          | 29        | 9.8%    |
| 201-250        | 24        | 8.11%   |
| 151-200        | 21        | 7.09%   |
| Unknown        | 19        | 6.42%   |
| 141-150        | 16        | 5.41%   |
| 41-50          | 14        | 4.73%   |
| 351-500        | 11        | 3.72%   |
| 51-60          | 10        | 3.38%   |
| More than 1000 | 9         | 3.04%   |
| 301-350        | 8         | 2.7%    |
| 71-80          | 7         | 2.36%   |
| 121-130        | 7         | 2.36%   |
| 61-70          | 5         | 1.69%   |
| 251-300        | 5         | 1.69%   |
| 501-1000       | 4         | 1.35%   |
| 91-100         | 3         | 1.01%   |
| 1-40           | 2         | 0.68%   |
| 131-140        | 2         | 0.68%   |
| 111-120        | 1         | 0.34%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 113       | 39.51%  |
| 101-120 | 105       | 36.71%  |
| 121-160 | 37        | 12.94%  |
| Unknown | 19        | 6.64%   |
| 1-50    | 9         | 3.15%   |
| 161-240 | 3         | 1.05%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 260       | 83.87%  |
| 2     | 34        | 10.97%  |
| 0     | 13        | 4.19%   |
| 3     | 3         | 0.97%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 143       | 27.45%  |
| Intel                             | 105       | 20.15%  |
| Qualcomm Atheros                  | 77        | 14.78%  |
| Broadcom                          | 63        | 12.09%  |
| Marvell Technology Group          | 21        | 4.03%   |
| Nvidia                            | 16        | 3.07%   |
| Broadcom Limited                  | 15        | 2.88%   |
| Ralink Technology                 | 11        | 2.11%   |
| Ralink                            | 8         | 1.54%   |
| VIA Technologies                  | 5         | 0.96%   |
| TP-Link                           | 4         | 0.77%   |
| Silicon Integrated Systems [SiS]  | 4         | 0.77%   |
| Samsung Electronics               | 4         | 0.77%   |
| ASUSTek Computer                  | 4         | 0.77%   |
| Qualcomm Atheros Communications   | 3         | 0.58%   |
| Gemtek                            | 3         | 0.58%   |
| D-Link                            | 3         | 0.58%   |
| NetGear                           | 2         | 0.38%   |
| Motorola PCS                      | 2         | 0.38%   |
| Linksys                           | 2         | 0.38%   |
| JMicron Technology                | 2         | 0.38%   |
| Huawei Technologies               | 2         | 0.38%   |
| DisplayLink                       | 2         | 0.38%   |
| Belkin Components                 | 2         | 0.38%   |
| ASIX Electronics                  | 2         | 0.38%   |
| 3Com                              | 2         | 0.38%   |
| Xiaomi                            | 1         | 0.19%   |
| Spreadtrum Communications         | 1         | 0.19%   |
| Micro Star International          | 1         | 0.19%   |
| MediaTek                          | 1         | 0.19%   |
| LG Electronics                    | 1         | 0.19%   |
| Ericsson Business Mobile Networks | 1         | 0.19%   |
| Dell                              | 1         | 0.19%   |
| D-Link System                     | 1         | 0.19%   |
| Compal Electronics                | 1         | 0.19%   |
| BUFFALO                           | 1         | 0.19%   |
| Attansic Technology               | 1         | 0.19%   |
| Apple                             | 1         | 0.19%   |
| AMD                               | 1         | 0.19%   |
| ADMtek                            | 1         | 0.19%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 64        | 10.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 35        | 5.98%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 17        | 2.91%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 2.56%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 2.56%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 1.71%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 1.71%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 9         | 1.54%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 9         | 1.54%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 9         | 1.54%   |
| Nvidia MCP61 Ethernet                                                   | 7         | 1.2%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 7         | 1.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 1.03%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 6         | 1.03%   |
| Intel Wireless 7265                                                     | 6         | 1.03%   |
| Intel Wireless 7260                                                     | 6         | 1.03%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 6         | 1.03%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 0.85%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 5         | 0.85%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 0.85%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 0.85%   |
| Intel 82567LM-3 Gigabit Network Connection                              | 5         | 0.85%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 5         | 0.85%   |
| VIA VT6102/VT6103 [Rhine-II]                                            | 4         | 0.68%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter           | 4         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 0.68%   |
| Realtek 802.11ac NIC                                                    | 4         | 0.68%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 4         | 0.68%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 0.68%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 0.68%   |
| Intel Wireless 3165                                                     | 4         | 0.68%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 0.68%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 0.68%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Modem Controller        | 4         | 0.68%   |
| Broadcom BCM4401-B0 100Base-TX                                          | 4         | 0.68%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 3         | 0.51%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.51%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 3         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 75        | 27.68%  |
| Qualcomm Atheros                | 59        | 21.77%  |
| Realtek Semiconductor           | 42        | 15.5%   |
| Broadcom                        | 38        | 14.02%  |
| Ralink Technology               | 11        | 4.06%   |
| Broadcom Limited                | 9         | 3.32%   |
| Ralink                          | 8         | 2.95%   |
| TP-Link                         | 4         | 1.48%   |
| ASUSTek Computer                | 4         | 1.48%   |
| Qualcomm Atheros Communications | 3         | 1.11%   |
| Gemtek                          | 3         | 1.11%   |
| D-Link                          | 3         | 1.11%   |
| NetGear                         | 2         | 0.74%   |
| Belkin Components               | 2         | 0.74%   |
| VIA Technologies                | 1         | 0.37%   |
| Samsung Electronics             | 1         | 0.37%   |
| Micro Star International        | 1         | 0.37%   |
| Marvell Technology Group        | 1         | 0.37%   |
| Linksys                         | 1         | 0.37%   |
| Dell                            | 1         | 0.37%   |
| D-Link System                   | 1         | 0.37%   |
| BUFFALO                         | 1         | 0.37%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 15        | 5.51%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 15        | 5.51%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 10        | 3.68%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 10        | 3.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 9         | 3.31%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 9         | 3.31%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 6         | 2.21%   |
| Intel Wireless 7265                                                     | 6         | 2.21%   |
| Intel Wireless 7260                                                     | 6         | 2.21%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 6         | 2.21%   |
| Broadcom BCM43142 802.11b/g/n                                           | 6         | 2.21%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 5         | 1.84%   |
| Ralink MT7601U Wireless Adapter                                         | 5         | 1.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 5         | 1.84%   |
| Broadcom BCM4311 802.11b/g WLAN                                         | 5         | 1.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 1.47%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 4         | 1.47%   |
| Realtek 802.11ac NIC                                                    | 4         | 1.47%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 4         | 1.47%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 4         | 1.47%   |
| Intel Wireless 3165                                                     | 4         | 1.47%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 4         | 1.47%   |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                | 4         | 1.47%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                   | 3         | 1.1%    |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.1%    |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter                | 3         | 1.1%    |
| Realtek RTL-8185 IEEE 802.11a/b/g Wireless LAN Controller               | 3         | 1.1%    |
| Ralink RT5370 Wireless Adapter                                          | 3         | 1.1%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 3         | 1.1%    |
| Intel Centrino Ultimate-N 6300                                          | 3         | 1.1%    |
| Gemtek WUBR-177G [Ralink RT2571W]                                       | 3         | 1.1%    |
| Broadcom BCM43224 802.11a/b/g/n                                         | 3         | 1.1%    |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 2         | 0.74%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                              | 2         | 0.74%   |
| Realtek RTL8187B Wireless Adapter                                       | 2         | 0.74%   |
| Ralink RT2870/RT3070 Wireless Adapter                                   | 2         | 0.74%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 2         | 0.74%   |
| Ralink RT2561/RT61 rev B 802.11g                                        | 2         | 0.74%   |
| Qualcomm Atheros AR9271 802.11n                                         | 2         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 124       | 41.75%  |
| Intel                            | 49        | 16.5%   |
| Broadcom                         | 30        | 10.1%   |
| Qualcomm Atheros                 | 25        | 8.42%   |
| Marvell Technology Group         | 20        | 6.73%   |
| Nvidia                           | 16        | 5.39%   |
| Broadcom Limited                 | 7         | 2.36%   |
| VIA Technologies                 | 4         | 1.35%   |
| Silicon Integrated Systems [SiS] | 4         | 1.35%   |
| JMicron Technology               | 2         | 0.67%   |
| DisplayLink                      | 2         | 0.67%   |
| ASIX Electronics                 | 2         | 0.67%   |
| 3Com                             | 2         | 0.67%   |
| Xiaomi                           | 1         | 0.34%   |
| Spreadtrum Communications        | 1         | 0.34%   |
| Samsung Electronics              | 1         | 0.34%   |
| Motorola PCS                     | 1         | 0.34%   |
| MediaTek                         | 1         | 0.34%   |
| Linksys                          | 1         | 0.34%   |
| LG Electronics                   | 1         | 0.34%   |
| Attansic Technology              | 1         | 0.34%   |
| Apple                            | 1         | 0.34%   |
| ADMtek                           | 1         | 0.34%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 64        | 21.33%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 35        | 11.67%  |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 17        | 5.67%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 9         | 3%      |
| Nvidia MCP61 Ethernet                                             | 7         | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7         | 2.33%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 6         | 2%      |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 1.67%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 5         | 1.67%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 4         | 1.33%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 4         | 1.33%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 4         | 1.33%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 4         | 1.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3         | 1%      |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 1%      |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 3         | 1%      |
| Intel NM10/ICH7 Family LAN Controller                             | 3         | 1%      |
| Intel 82579V Gigabit Network Connection                           | 3         | 1%      |
| Intel 82573L Gigabit Ethernet Controller                          | 3         | 1%      |
| Intel 82566DM Gigabit Network Connection                          | 3         | 1%      |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 3         | 1%      |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 3         | 1%      |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 0.67%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.67%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 2         | 0.67%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.67%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.67%   |
| Nvidia MCP77 Ethernet                                             | 2         | 0.67%   |
| Nvidia MCP73 Ethernet                                             | 2         | 0.67%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 2         | 0.67%   |
| Marvell Group 88E8038 PCI-E Fast Ethernet Controller              | 2         | 0.67%   |
| Intel Ethernet Connection I218-LM                                 | 2         | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                             | 2         | 0.67%   |
| Intel 82577LM Gigabit Network Connection                          | 2         | 0.67%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.67%   |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 2         | 0.67%   |
| Broadcom NetXtreme BCM5755M Gigabit Ethernet PCI Express          | 2         | 0.67%   |
| Broadcom NetXtreme BCM5751M Gigabit Ethernet PCI Express          | 2         | 0.67%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 0.67%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 2         | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 279       | 51.1%   |
| WiFi     | 255       | 46.7%   |
| Modem    | 10        | 1.83%   |
| Unknown  | 2         | 0.37%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 197       | 61.37%  |
| Ethernet | 122       | 38.01%  |
| Modem    | 1         | 0.31%   |
| Unknown  | 1         | 0.31%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 191       | 62.42%  |
| 1     | 104       | 33.99%  |
| 0     | 8         | 2.61%   |
| 3     | 3         | 0.98%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 278       | 90.26%  |
| Yes  | 30        | 9.74%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 33        | 25.58%  |
| Qualcomm Atheros Communications | 16        | 12.4%   |
| Broadcom                        | 15        | 11.63%  |
| Cambridge Silicon Radio         | 12        | 9.3%    |
| Hewlett-Packard                 | 7         | 5.43%   |
| Realtek Semiconductor           | 6         | 4.65%   |
| Toshiba                         | 5         | 3.88%   |
| Lite-On Technology              | 5         | 3.88%   |
| Foxconn / Hon Hai               | 5         | 3.88%   |
| Dell                            | 5         | 3.88%   |
| Foxconn International           | 4         | 3.1%    |
| IMC Networks                    | 3         | 2.33%   |
| ASUSTek Computer                | 3         | 2.33%   |
| Apple                           | 3         | 2.33%   |
| Ralink                          | 2         | 1.55%   |
| Alps Electric                   | 2         | 1.55%   |
| Primax Electronics              | 1         | 0.78%   |
| Kensington                      | 1         | 0.78%   |
| Fujitsu Siemens Computers       | 1         | 0.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 19        | 14.73%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 12        | 9.3%    |
| Qualcomm Atheros  Bluetooth Device                  | 7         | 5.43%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 7         | 5.43%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 5         | 3.88%   |
| Foxconn International BCM43142A0 Bluetooth module   | 4         | 3.1%    |
| Realtek Bluetooth Radio                             | 3         | 2.33%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 3         | 2.33%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 3         | 2.33%   |
| Broadcom Broadcom BCM2070 Bluetooth Device          | 3         | 2.33%   |
| Toshiba Bluetooth Device                            | 2         | 1.55%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2         | 1.55%   |
| Ralink RT3290 Bluetooth                             | 2         | 1.55%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 1.55%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 1.55%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 1.55%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 2         | 1.55%   |
| Intel Bluetooth Device                              | 2         | 1.55%   |
| Intel AX200 Bluetooth                               | 2         | 1.55%   |
| Dell DW375 Bluetooth Module                         | 2         | 1.55%   |
| Dell BCM20702A0 Bluetooth Module                    | 2         | 1.55%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 1.55%   |
| Broadcom BCM20702A0                                 | 2         | 1.55%   |
| ASUS Bluetooth Radio                                | 2         | 1.55%   |
| Apple Bluetooth USB Host Controller                 | 2         | 1.55%   |
| Toshiba RT Bluetooth Radio                          | 1         | 0.78%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.78%   |
| Toshiba Atheros AR3012 Bluetooth                    | 1         | 0.78%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.78%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1         | 0.78%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.78%   |
| Primax Rocketfish RF-FLBTAD Bluetooth Adapter       | 1         | 0.78%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1         | 0.78%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.78%   |
| Lite-On Bluetooth Device                            | 1         | 0.78%   |
| Kensington Bluetooth EDR Dongle                     | 1         | 0.78%   |
| IMC Networks Bluetooth USB Host Controller          | 1         | 0.78%   |
| IMC Networks Bluetooth module                       | 1         | 0.78%   |
| IMC Networks Bluetooth Device                       | 1         | 0.78%   |
| Fujitsu Siemens Computers Bluetooth Device          | 1         | 0.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 228       | 62.81%  |
| AMD                                             | 51        | 14.05%  |
| Nvidia                                          | 46        | 12.67%  |
| C-Media Electronics                             | 8         | 2.2%    |
| VIA Technologies                                | 7         | 1.93%   |
| Silicon Integrated Systems [SiS]                | 6         | 1.65%   |
| Creative Labs                                   | 6         | 1.65%   |
| Logitech                                        | 2         | 0.55%   |
| ULi Electronics                                 | 1         | 0.28%   |
| Licensed by Sony Computer Entertainment America | 1         | 0.28%   |
| Lenovo                                          | 1         | 0.28%   |
| JMTek                                           | 1         | 0.28%   |
| Hewlett-Packard                                 | 1         | 0.28%   |
| Generalplus Technology                          | 1         | 0.28%   |
| Elite Silicon                                   | 1         | 0.28%   |
| Creative Technology                             | 1         | 0.28%   |
| Corsair                                         | 1         | 0.28%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 54        | 13.4%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 30        | 7.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 27        | 6.7%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 18        | 4.47%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 15        | 3.72%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 14        | 3.47%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 13        | 3.23%   |
| AMD FCH Azalia Controller                                                                         | 12        | 2.98%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 11        | 2.73%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 8         | 1.99%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 7         | 1.74%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 7         | 1.74%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 1.74%   |
| Nvidia MCP61 High Definition Audio                                                                | 6         | 1.49%   |
| Nvidia High Definition Audio Controller                                                           | 6         | 1.49%   |
| Silicon Integrated Systems [SiS] Azalia Audio Controller                                          | 5         | 1.24%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 5         | 1.24%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.24%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 5         | 1.24%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 5         | 1.24%   |
| AMD Wrestler HDMI Audio                                                                           | 5         | 1.24%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 5         | 1.24%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 5         | 1.24%   |
| VIA Technologies VX900/VT8xxx High Definition Audio Controller                                    | 4         | 0.99%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 4         | 0.99%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 4         | 0.99%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 4         | 0.99%   |
| VIA Technologies VT8233/A/8235/8237 AC97 Audio Controller                                         | 3         | 0.74%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.74%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 0.74%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 0.74%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 0.74%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 0.74%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 3         | 0.74%   |
| AMD High Definition Audio Controller                                                              | 3         | 0.74%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 3         | 0.74%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 3         | 0.74%   |
| Nvidia MCP79 High Definition Audio                                                                | 2         | 0.5%    |
| Nvidia MCP73 High Definition Audio                                                                | 2         | 0.5%    |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 2         | 0.5%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 24        | 26.37%  |
| Samsung Electronics | 18        | 19.78%  |
| SK hynix            | 13        | 14.29%  |
| Micron Technology   | 8         | 8.79%   |
| Kingston            | 6         | 6.59%   |
| Nanya Technology    | 3         | 3.3%    |
| Crucial             | 3         | 3.3%    |
| Ramaxel Technology  | 2         | 2.2%    |
| Corsair             | 2         | 2.2%    |
| Unknown             | 2         | 2.2%    |
| Unknown (ABCD)      | 1         | 1.1%    |
| Toshiba             | 1         | 1.1%    |
| Smart               | 1         | 1.1%    |
| PNY                 | 1         | 1.1%    |
| Infineon            | 1         | 1.1%    |
| Goldkey             | 1         | 1.1%    |
| G.Skill             | 1         | 1.1%    |
| Elpida              | 1         | 1.1%    |
| A-DATA Technology   | 1         | 1.1%    |
| 48spaces            | 1         | 1.1%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 3.06%   |
| SK hynix RAM HMT451S6DFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.04%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 2.04%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s              | 2         | 2.04%   |
| Micron RAM MT52L256M32D1PF107 2GB LPDDR3 1600MT/s                | 2         | 2.04%   |
| Micron RAM Module 2048MB DIMM DDR3 1333MT/s                      | 2         | 2.04%   |
| Unknown                                                          | 2         | 2.04%   |
| Unknown RAM Module SODIMM DDR                                    | 1         | 1.02%   |
| Unknown RAM Module 512MB SODIMM DDR2 533MT/s                     | 1         | 1.02%   |
| Unknown RAM Module 512MB SODIMM DDR                              | 1         | 1.02%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.02%   |
| Unknown RAM Module 4GB DIMM DDR 1333MT/s                         | 1         | 1.02%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                             | 1         | 1.02%   |
| Unknown RAM Module 2GB SODIMM SDRAM                              | 1         | 1.02%   |
| Unknown RAM Module 2GB SODIMM DRAM                               | 1         | 1.02%   |
| Unknown RAM Module 2GB SODIMM DDR3 1600MT/s                      | 1         | 1.02%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 1.02%   |
| Unknown RAM Module 2GB SODIMM DDR2                               | 1         | 1.02%   |
| Unknown RAM Module 2GB DIMM DRAM                                 | 1         | 1.02%   |
| Unknown RAM Module 2GB DIMM DDR2                                 | 1         | 1.02%   |
| Unknown RAM Module 2048MB SODIMM DRAM                            | 1         | 1.02%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1600MT/s                   | 1         | 1.02%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1333MT/s                   | 1         | 1.02%   |
| Unknown RAM Module 2048MB SODIMM DDR3 1066MT/s                   | 1         | 1.02%   |
| Unknown RAM Module 2048MB SODIMM DDR3                            | 1         | 1.02%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 1         | 1.02%   |
| Unknown RAM Module 1GB DIMM DDR2 533MT/s                         | 1         | 1.02%   |
| Unknown RAM Module 1GB DIMM DDR2                                 | 1         | 1.02%   |
| Unknown RAM Module 1024MB SODIMM DDR2                            | 1         | 1.02%   |
| Unknown RAM Module 1024MB SODIMM DDR 100MT/s                     | 1         | 1.02%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                           | 1         | 1.02%   |
| Unknown RAM Module 1024MB DIMM 41632MT/s                         | 1         | 1.02%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.02%   |
| Toshiba RAM 8HTF12864HDY-800G1 1GB SODIMM 1066MT/s               | 1         | 1.02%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 1.02%   |
| Smart RAM SG564568FG8NWKF-Z1 2GB SODIMM DDR2 800MT/s             | 1         | 1.02%   |
| SK hynix RAM Module 8GB SODIMM DDR4 2400MT/s                     | 1         | 1.02%   |
| SK hynix RAM Module 512MB DIMM DDR2 533MT/s                      | 1         | 1.02%   |
| SK hynix RAM Module 2GB DIMM DDR3 1600MT/s                       | 1         | 1.02%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 1         | 1.02%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 44        | 51.16%  |
| DDR2    | 13        | 15.12%  |
| DDR4    | 7         | 8.14%   |
| SDRAM   | 6         | 6.98%   |
| DDR     | 5         | 5.81%   |
| DRAM    | 4         | 4.65%   |
| LPDDR3  | 3         | 3.49%   |
| Unknown | 3         | 3.49%   |
| LPDDR4  | 1         | 1.16%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 58        | 69.05%  |
| DIMM         | 21        | 25%     |
| Unknown      | 3         | 3.57%   |
| Row Of Chips | 1         | 1.19%   |
| Chip         | 1         | 1.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 31        | 33.7%   |
| 2048    | 31        | 33.7%   |
| 8192    | 12        | 13.04%  |
| 1024    | 12        | 13.04%  |
| 512     | 3         | 3.26%   |
| 16384   | 1         | 1.09%   |
| 256     | 1         | 1.09%   |
| Unknown | 1         | 1.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 29        | 32.22%  |
| Unknown | 13        | 14.44%  |
| 1333    | 10        | 11.11%  |
| 2400    | 6         | 6.67%   |
| 800     | 4         | 4.44%   |
| 667     | 4         | 4.44%   |
| 1334    | 3         | 3.33%   |
| 1066    | 3         | 3.33%   |
| 533     | 3         | 3.33%   |
| 3200    | 2         | 2.22%   |
| 2048    | 2         | 2.22%   |
| 1867    | 2         | 2.22%   |
| 41632   | 1         | 1.11%   |
| 3266    | 1         | 1.11%   |
| 2866    | 1         | 1.11%   |
| 2667    | 1         | 1.11%   |
| 1866    | 1         | 1.11%   |
| 1067    | 1         | 1.11%   |
| 975     | 1         | 1.11%   |
| 320     | 1         | 1.11%   |
| 100     | 1         | 1.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 3         | 33.33%  |
| Hewlett-Packard     | 2         | 22.22%  |
| Seiko Epson         | 1         | 11.11%  |
| Samsung Electronics | 1         | 11.11%  |
| Dymo-CoStar         | 1         | 11.11%  |
| Canon               | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seiko Epson XP-240 Series              | 1         | 11.11%  |
| Samsung ML-216x Series Laser Printer   | 1         | 11.11%  |
| HP OfficeJet 5200 series               | 1         | 11.11%  |
| HP DeskJet 1220C                       | 1         | 11.11%  |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1         | 11.11%  |
| Canon TS3300 series                    | 1         | 11.11%  |
| Brother HL-L2360D series               | 1         | 11.11%  |
| Brother HL-L2350DW series              | 1         | 11.11%  |
| Brother HL-L2340D series               | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 40        | 24.39%  |
| Suyin                                  | 12        | 7.32%   |
| Realtek Semiconductor                  | 12        | 7.32%   |
| Microdia                               | 12        | 7.32%   |
| IMC Networks                           | 11        | 6.71%   |
| Bison Electronics                      | 10        | 6.1%    |
| Cheng Uei Precision Industry (Foxlink) | 8         | 4.88%   |
| Ricoh                                  | 7         | 4.27%   |
| Acer                                   | 7         | 4.27%   |
| Z-Star Microelectronics                | 6         | 3.66%   |
| Sunplus Innovation Technology          | 6         | 3.66%   |
| Silicon Motion                         | 4         | 2.44%   |
| Syntek                                 | 3         | 1.83%   |
| Logitech                               | 3         | 1.83%   |
| Importek                               | 3         | 1.83%   |
| ALi                                    | 3         | 1.83%   |
| Samsung Electronics                    | 2         | 1.22%   |
| Cubeternet                             | 2         | 1.22%   |
| Apple                                  | 2         | 1.22%   |
| Trust                                  | 1         | 0.61%   |
| Quanta                                 | 1         | 0.61%   |
| OPPO Electronics                       | 1         | 0.61%   |
| OmniVision Technologies                | 1         | 0.61%   |
| Lite-On Technology                     | 1         | 0.61%   |
| LG Electronics                         | 1         | 0.61%   |
| Lenovo                                 | 1         | 0.61%   |
| GEO Semi                               | 1         | 0.61%   |
| DigiTech                               | 1         | 0.61%   |
| Aveo Technology                        | 1         | 0.61%   |
| Alcor Micro                            | 1         | 0.61%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Z-Star Webcam                                           | 4         | 2.44%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 4         | 2.44%   |
| Chicony TOSHIBA Web Camera - HD                         | 4         | 2.44%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 4         | 2.44%   |
| Microdia Sonix USB 2.0 Camera                           | 3         | 1.83%   |
| IMC Networks UVC VGA Webcam                             | 3         | 1.83%   |
| Chicony USB 2.0 Camera                                  | 3         | 1.83%   |
| Chicony CNF9055 Toshiba Webcam                          | 3         | 1.83%   |
| Bison Integrated Camera                                 | 3         | 1.83%   |
| Bison EasyCamera                                        | 3         | 1.83%   |
| Acer Lenovo EasyCamera                                  | 3         | 1.83%   |
| Silicon Motion WebCam SC-0311139N                       | 2         | 1.22%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 2         | 1.22%   |
| Ricoh Sony Vaio Integrated Webcam                       | 2         | 1.22%   |
| Ricoh Laptop_Integrated_Webcam_FHD                      | 2         | 1.22%   |
| Realtek USB camera                                      | 2         | 1.22%   |
| Realtek Lenovo EasyCamera                               | 2         | 1.22%   |
| Realtek Integrated_Webcam_HD                            | 2         | 1.22%   |
| Realtek Integrated Webcam                               | 2         | 1.22%   |
| Realtek HD WebCam                                       | 2         | 1.22%   |
| Microdia Integrated Webcam                              | 2         | 1.22%   |
| Importek HP Webcam-50                                   | 2         | 1.22%   |
| IMC Networks USB2.0 UVC HD Webcam                       | 2         | 1.22%   |
| IMC Networks Integrated Webcam                          | 2         | 1.22%   |
| Chicony VGA Webcam                                      | 2         | 1.22%   |
| Chicony Lenovo EasyCamera                               | 2         | 1.22%   |
| Chicony HP HD Camera                                    | 2         | 1.22%   |
| Chicony HD WebCam                                       | 2         | 1.22%   |
| Chicony 2.0M UVC Webcam / CNF7129                       | 2         | 1.22%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam        | 2         | 1.22%   |
| Bison Lenovo Integrated Webcam                          | 2         | 1.22%   |
| Acer BisonCam, NB Pro                                   | 2         | 1.22%   |
| Z-Star Vega USB 2.0 Camera                              | 1         | 0.61%   |
| Z-Star Sirius USB2.0 Camera                             | 1         | 0.61%   |
| Trust WB-6250X Webcam                                   | 1         | 0.61%   |
| Syntek USB Camera Device                                | 1         | 0.61%   |
| Syntek Lenovo EasyCamera                                | 1         | 0.61%   |
| Syntek Integrated Webcam                                | 1         | 0.61%   |
| Suyin USB 2.0 Camera                                    | 1         | 0.61%   |
| Suyin HP Webcam 101                                     | 1         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Validity Sensors      | 6         | 31.58%  |
| AuthenTec             | 5         | 26.32%  |
| STMicroelectronics    | 4         | 21.05%  |
| Upek                  | 2         | 10.53%  |
| Synaptics             | 1         | 5.26%   |
| LighTuning Technology | 1         | 5.26%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| STMicroelectronics Fingerprint Reader                                      | 4         | 21.05%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 10.53%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 10.53%  |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 5.26%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 5.26%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 5.26%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 5.26%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 5.26%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 5.26%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 5.26%   |
| AuthenTec AES2810                                                          | 1         | 5.26%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 5.26%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 5.26%   |
| AuthenTec AES1600                                                          | 1         | 5.26%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| O2 Micro         | 4         | 33.33%  |
| Broadcom         | 4         | 33.33%  |
| Upek             | 1         | 8.33%   |
| SCM Microsystems | 1         | 8.33%   |
| Lenovo           | 1         | 8.33%   |
| Alcor Micro      | 1         | 8.33%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 25%     |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 25%     |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 8.33%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 8.33%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 8.33%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 8.33%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 8.33%   |
| Alcor Micro AU9540 Smartcard Reader                                          | 1         | 8.33%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 204       | 65.59%  |
| 1     | 82        | 26.37%  |
| 2     | 23        | 7.4%    |
| 4     | 1         | 0.32%   |
| 3     | 1         | 0.32%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 41        | 30.83%  |
| Net/wireless             | 21        | 15.79%  |
| Fingerprint reader       | 18        | 13.53%  |
| Chipcard                 | 12        | 9.02%   |
| Communication controller | 11        | 8.27%   |
| Storage                  | 6         | 4.51%   |
| Modem                    | 5         | 3.76%   |
| Camera                   | 5         | 3.76%   |
| Multimedia controller    | 3         | 2.26%   |
| Bluetooth                | 3         | 2.26%   |
| Sound                    | 2         | 1.5%    |
| Flash memory             | 2         | 1.5%    |
| Unassigned class         | 1         | 0.75%   |
| Storage/raid             | 1         | 0.75%   |
| Storage/ide              | 1         | 0.75%   |
| Net/ethernet             | 1         | 0.75%   |

