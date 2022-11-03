Kubuntu - Tested Hardware & Statistics
--------------------------------------

A project to collect tested hardware configurations for Kubuntu.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kubuntu/Desktop/README.md) and [notebooks](/Dist/Kubuntu/Notebook/README.md).

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

Total: 4210

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Dell          | 0GY6Y8 A02                  | Desktop     | [760c526784](https://linux-hardware.org/?probe=760c526784) | Nov 02, 2022 |
| Dell          | 040DDP A00                  | Desktop     | [fba864b37c](https://linux-hardware.org/?probe=fba864b37c) | Nov 02, 2022 |
| Lenovo        | ThinkPad T440p 20AW000GU... | Notebook    | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e4dfd41fa4](https://linux-hardware.org/?probe=e4dfd41fa4) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | Notebook    | [623af75bb3](https://linux-hardware.org/?probe=623af75bb3) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | Notebook    | [52e7c62bae](https://linux-hardware.org/?probe=52e7c62bae) | Nov 02, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [4f1e0d9702](https://linux-hardware.org/?probe=4f1e0d9702) | Nov 02, 2022 |
| MSI           | MAG Z390 TOMAHAWK           | Desktop     | [842320d7b3](https://linux-hardware.org/?probe=842320d7b3) | Nov 02, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [8b8ec08876](https://linux-hardware.org/?probe=8b8ec08876) | Nov 02, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [7b42bc51be](https://linux-hardware.org/?probe=7b42bc51be) | Nov 02, 2022 |
| Notebook      | P65_P67SE                   | Notebook    | [9b99df1e15](https://linux-hardware.org/?probe=9b99df1e15) | Nov 02, 2022 |
| Gigabyte      | H81M-DS2V                   | Desktop     | [caffb9ebd7](https://linux-hardware.org/?probe=caffb9ebd7) | Nov 01, 2022 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [50bd7a7436](https://linux-hardware.org/?probe=50bd7a7436) | Nov 01, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [50d2f412f0](https://linux-hardware.org/?probe=50d2f412f0) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [6d6a8caf61](https://linux-hardware.org/?probe=6d6a8caf61) | Nov 01, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [722ae37952](https://linux-hardware.org/?probe=722ae37952) | Nov 01, 2022 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [77ccdee0fe](https://linux-hardware.org/?probe=77ccdee0fe) | Nov 01, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [ea7591794a](https://linux-hardware.org/?probe=ea7591794a) | Nov 01, 2022 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [27b07caa39](https://linux-hardware.org/?probe=27b07caa39) | Oct 31, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [865aef7529](https://linux-hardware.org/?probe=865aef7529) | Oct 31, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [80f6da5216](https://linux-hardware.org/?probe=80f6da5216) | Oct 31, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [1e0daee604](https://linux-hardware.org/?probe=1e0daee604) | Oct 30, 2022 |
| Acer          | Aspire 5732Z                | Notebook    | [df73e0ca67](https://linux-hardware.org/?probe=df73e0ca67) | Oct 30, 2022 |
| Shuttle       | FH61R                       | Desktop     | [26f86947ef](https://linux-hardware.org/?probe=26f86947ef) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [4b778e52ee](https://linux-hardware.org/?probe=4b778e52ee) | Oct 30, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | Notebook    | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| EVGA          | 122-CK-NF68 2               | Desktop     | [91b3144c5c](https://linux-hardware.org/?probe=91b3144c5c) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [418b143f46](https://linux-hardware.org/?probe=418b143f46) | Oct 30, 2022 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [7047610fd9](https://linux-hardware.org/?probe=7047610fd9) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [293877c614](https://linux-hardware.org/?probe=293877c614) | Oct 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [aea626acae](https://linux-hardware.org/?probe=aea626acae) | Oct 29, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [5bd4292187](https://linux-hardware.org/?probe=5bd4292187) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d7491bf8e7](https://linux-hardware.org/?probe=d7491bf8e7) | Oct 29, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [883100c74f](https://linux-hardware.org/?probe=883100c74f) | Oct 29, 2022 |
| Google        | Kench                       | Desktop     | [faf24fddcd](https://linux-hardware.org/?probe=faf24fddcd) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6bdf703faf](https://linux-hardware.org/?probe=6bdf703faf) | Oct 29, 2022 |
| Dell          | 0478VN A00                  | Desktop     | [629858e96c](https://linux-hardware.org/?probe=629858e96c) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [cfa027a9e2](https://linux-hardware.org/?probe=cfa027a9e2) | Oct 28, 2022 |
| ASRock        | H61M-VS                     | Desktop     | [9a48b2a679](https://linux-hardware.org/?probe=9a48b2a679) | Oct 28, 2022 |
| Dell          | Latitude 5521               | Notebook    | [460057b367](https://linux-hardware.org/?probe=460057b367) | Oct 28, 2022 |
| Dell          | 0KRC95 A02                  | Desktop     | [8afc3da46d](https://linux-hardware.org/?probe=8afc3da46d) | Oct 28, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [071938b19a](https://linux-hardware.org/?probe=071938b19a) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [ac3b0eaf36](https://linux-hardware.org/?probe=ac3b0eaf36) | Oct 28, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ba5aec702a](https://linux-hardware.org/?probe=ba5aec702a) | Oct 27, 2022 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [c33d6de923](https://linux-hardware.org/?probe=c33d6de923) | Oct 27, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [a5c5f0ec1e](https://linux-hardware.org/?probe=a5c5f0ec1e) | Oct 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ed392a140d](https://linux-hardware.org/?probe=ed392a140d) | Oct 27, 2022 |
| HP            | G62                         | Notebook    | [c9ba156401](https://linux-hardware.org/?probe=c9ba156401) | Oct 27, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [74ad4c8c59](https://linux-hardware.org/?probe=74ad4c8c59) | Oct 27, 2022 |
| HP            | 844C                        | Desktop     | [7e994c50c9](https://linux-hardware.org/?probe=7e994c50c9) | Oct 27, 2022 |
| Gigabyte      | AX370M-Gaming 3-CF          | Desktop     | [abe170cf19](https://linux-hardware.org/?probe=abe170cf19) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a308f68bce](https://linux-hardware.org/?probe=a308f68bce) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [6954f669c5](https://linux-hardware.org/?probe=6954f669c5) | Oct 27, 2022 |
| ASUSTek       | ROG STRIX Z690-F GAMING ... | Desktop     | [3acf0ca326](https://linux-hardware.org/?probe=3acf0ca326) | Oct 26, 2022 |
| Notebook      | PD5x_7xPNP_PNR_PNN_PNT      | Notebook    | [93229f0fab](https://linux-hardware.org/?probe=93229f0fab) | Oct 26, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7910e04e13](https://linux-hardware.org/?probe=7910e04e13) | Oct 25, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [2920658e38](https://linux-hardware.org/?probe=2920658e38) | Oct 25, 2022 |
| Samsung       | 767XCL                      | Notebook    | [17bd1b4506](https://linux-hardware.org/?probe=17bd1b4506) | Oct 25, 2022 |
| HP            | Pavilion g6                 | Notebook    | [448d52b32f](https://linux-hardware.org/?probe=448d52b32f) | Oct 25, 2022 |
| ASUSTek       | N751JK                      | Notebook    | [f6f0ff5048](https://linux-hardware.org/?probe=f6f0ff5048) | Oct 25, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [94fa6196b8](https://linux-hardware.org/?probe=94fa6196b8) | Oct 25, 2022 |
| Acer          | Aspire 5750                 | Notebook    | [20df7ad008](https://linux-hardware.org/?probe=20df7ad008) | Oct 25, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [bd3a8063b3](https://linux-hardware.org/?probe=bd3a8063b3) | Oct 25, 2022 |
| Sony          | VAIO                        | All in one  | [27e76b1c76](https://linux-hardware.org/?probe=27e76b1c76) | Oct 25, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [6a9d81591f](https://linux-hardware.org/?probe=6a9d81591f) | Oct 25, 2022 |
| Dell          | Vostro 15 5501              | Notebook    | [3338297022](https://linux-hardware.org/?probe=3338297022) | Oct 25, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [285e8cd1a5](https://linux-hardware.org/?probe=285e8cd1a5) | Oct 25, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [cfb2e32cea](https://linux-hardware.org/?probe=cfb2e32cea) | Oct 25, 2022 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [daa76e4b78](https://linux-hardware.org/?probe=daa76e4b78) | Oct 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [fe222419ec](https://linux-hardware.org/?probe=fe222419ec) | Oct 25, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [65c39a9702](https://linux-hardware.org/?probe=65c39a9702) | Oct 24, 2022 |
| HP            | 470 G8 Notebook PC          | Notebook    | [1cae6fb5ac](https://linux-hardware.org/?probe=1cae6fb5ac) | Oct 24, 2022 |
| HP            | 470 G8 Notebook PC          | Notebook    | [4c3e8196af](https://linux-hardware.org/?probe=4c3e8196af) | Oct 24, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [7fed0ea2a9](https://linux-hardware.org/?probe=7fed0ea2a9) | Oct 24, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [37fc32cacd](https://linux-hardware.org/?probe=37fc32cacd) | Oct 24, 2022 |
| Gigabyte      | B365M D2V                   | Desktop     | [c852b8f3f7](https://linux-hardware.org/?probe=c852b8f3f7) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [f42213926f](https://linux-hardware.org/?probe=f42213926f) | Oct 24, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [aaf3b72437](https://linux-hardware.org/?probe=aaf3b72437) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [638c72b105](https://linux-hardware.org/?probe=638c72b105) | Oct 24, 2022 |
| Dell          | 0RW199                      | Desktop     | [dc99b64e62](https://linux-hardware.org/?probe=dc99b64e62) | Oct 24, 2022 |
| Lenovo        | ThinkPad P73 20QRS00100     | Notebook    | [532b112928](https://linux-hardware.org/?probe=532b112928) | Oct 24, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [918b0ef1ab](https://linux-hardware.org/?probe=918b0ef1ab) | Oct 24, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [faedd5a008](https://linux-hardware.org/?probe=faedd5a008) | Oct 24, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [21db3e8ee8](https://linux-hardware.org/?probe=21db3e8ee8) | Oct 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [13c917aa38](https://linux-hardware.org/?probe=13c917aa38) | Oct 23, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [ca0e86eb6b](https://linux-hardware.org/?probe=ca0e86eb6b) | Oct 22, 2022 |
| Dell          | Latitude 7390               | Notebook    | [71f8a9e59b](https://linux-hardware.org/?probe=71f8a9e59b) | Oct 22, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [ddc08ffe48](https://linux-hardware.org/?probe=ddc08ffe48) | Oct 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [a8c892608e](https://linux-hardware.org/?probe=a8c892608e) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [20f991643f](https://linux-hardware.org/?probe=20f991643f) | Oct 21, 2022 |
| HP            | Laptop 17-by4xxx            | Notebook    | [6090ec7241](https://linux-hardware.org/?probe=6090ec7241) | Oct 21, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [0cf70c348b](https://linux-hardware.org/?probe=0cf70c348b) | Oct 21, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [a9de489f26](https://linux-hardware.org/?probe=a9de489f26) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [c8e47b28fe](https://linux-hardware.org/?probe=c8e47b28fe) | Oct 20, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [7524f39579](https://linux-hardware.org/?probe=7524f39579) | Oct 19, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [46cb50f2f6](https://linux-hardware.org/?probe=46cb50f2f6) | Oct 19, 2022 |
| Haier         | A1420EM                     | Notebook    | [62ce3535b2](https://linux-hardware.org/?probe=62ce3535b2) | Oct 19, 2022 |
| Haier         | A1420EM                     | Notebook    | [a50bc27e31](https://linux-hardware.org/?probe=a50bc27e31) | Oct 19, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [6d01f5c57b](https://linux-hardware.org/?probe=6d01f5c57b) | Oct 19, 2022 |
| Dell          | XPS 9320                    | Notebook    | [8dd41b53b6](https://linux-hardware.org/?probe=8dd41b53b6) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [a2db8aeade](https://linux-hardware.org/?probe=a2db8aeade) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [92957e0afc](https://linux-hardware.org/?probe=92957e0afc) | Oct 19, 2022 |
| Lenovo        | MIIX 510-12IKB 80XE         | Tablet      | [1066d54fec](https://linux-hardware.org/?probe=1066d54fec) | Oct 18, 2022 |
| Gigabyte      | MX33-BS0-00 00010001        | Server      | [abfee9c5f7](https://linux-hardware.org/?probe=abfee9c5f7) | Oct 18, 2022 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [431a84fc31](https://linux-hardware.org/?probe=431a84fc31) | Oct 18, 2022 |
| AZW           | SER V01                     | Mini pc     | [b106ebaef6](https://linux-hardware.org/?probe=b106ebaef6) | Oct 18, 2022 |
| MSI           | H110M PRO-D                 | Desktop     | [d0580b46f2](https://linux-hardware.org/?probe=d0580b46f2) | Oct 18, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | Desktop     | [1b0e52eddb](https://linux-hardware.org/?probe=1b0e52eddb) | Oct 18, 2022 |
| Dell          | Precision 3570              | Notebook    | [90711415f5](https://linux-hardware.org/?probe=90711415f5) | Oct 18, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [159150cc56](https://linux-hardware.org/?probe=159150cc56) | Oct 17, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [a7ebb4b3c4](https://linux-hardware.org/?probe=a7ebb4b3c4) | Oct 16, 2022 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [f779ba08c9](https://linux-hardware.org/?probe=f779ba08c9) | Oct 16, 2022 |
| JWIPC         | A320I S1                    | Desktop     | [44689a88d8](https://linux-hardware.org/?probe=44689a88d8) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | Notebook    | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c22c1df016](https://linux-hardware.org/?probe=c22c1df016) | Oct 15, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [3498692f6e](https://linux-hardware.org/?probe=3498692f6e) | Oct 15, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| ASUSTek       | X455LD                      | Notebook    | [ae520872e3](https://linux-hardware.org/?probe=ae520872e3) | Oct 14, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Dell          | Latitude E6420              | Notebook    | [f39e0305c5](https://linux-hardware.org/?probe=f39e0305c5) | Oct 13, 2022 |
| Dell          | Precision M6700             | Notebook    | [e198a003b6](https://linux-hardware.org/?probe=e198a003b6) | Oct 13, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [b36220c65b](https://linux-hardware.org/?probe=b36220c65b) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [1258429041](https://linux-hardware.org/?probe=1258429041) | Oct 13, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [2813d441b5](https://linux-hardware.org/?probe=2813d441b5) | Oct 13, 2022 |
| HP            | Laptop 15-da2xxx            | Notebook    | [4039ed6d6f](https://linux-hardware.org/?probe=4039ed6d6f) | Oct 13, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [20eebb7b05](https://linux-hardware.org/?probe=20eebb7b05) | Oct 12, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [93ee54a067](https://linux-hardware.org/?probe=93ee54a067) | Oct 11, 2022 |
| Gigabyte      | P55-US3L                    | Desktop     | [59843156e8](https://linux-hardware.org/?probe=59843156e8) | Oct 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [125ad4881a](https://linux-hardware.org/?probe=125ad4881a) | Oct 11, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [77d21da9a2](https://linux-hardware.org/?probe=77d21da9a2) | Oct 11, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [7c58857f43](https://linux-hardware.org/?probe=7c58857f43) | Oct 11, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | Notebook    | [7a11da121e](https://linux-hardware.org/?probe=7a11da121e) | Oct 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [b88e8a8b49](https://linux-hardware.org/?probe=b88e8a8b49) | Oct 11, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [71c916389e](https://linux-hardware.org/?probe=71c916389e) | Oct 09, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [5268977f64](https://linux-hardware.org/?probe=5268977f64) | Oct 09, 2022 |
| Acer          | Aspire G7750                | Desktop     | [bd21d9c12b](https://linux-hardware.org/?probe=bd21d9c12b) | Oct 09, 2022 |
| Medion        | H110H4-EM2                  | Desktop     | [7bd38709d3](https://linux-hardware.org/?probe=7bd38709d3) | Oct 09, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [aad99b4421](https://linux-hardware.org/?probe=aad99b4421) | Oct 09, 2022 |
| LG Electro... | 16T90P-K.ADB9U1             | Convertible | [7242c5df58](https://linux-hardware.org/?probe=7242c5df58) | Oct 09, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [691aa10e89](https://linux-hardware.org/?probe=691aa10e89) | Oct 09, 2022 |
| ASUSTek       | X555UA                      | Notebook    | [9cf559ac01](https://linux-hardware.org/?probe=9cf559ac01) | Oct 08, 2022 |
| ASRock        | A75M                        | Desktop     | [b3df324d02](https://linux-hardware.org/?probe=b3df324d02) | Oct 08, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [1f634e5071](https://linux-hardware.org/?probe=1f634e5071) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [1b90e3cfa5](https://linux-hardware.org/?probe=1b90e3cfa5) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [fddd82ba56](https://linux-hardware.org/?probe=fddd82ba56) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [9a16ca15b3](https://linux-hardware.org/?probe=9a16ca15b3) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [9bb8f8e33b](https://linux-hardware.org/?probe=9bb8f8e33b) | Oct 07, 2022 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [c621294169](https://linux-hardware.org/?probe=c621294169) | Oct 07, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [e59c8f50b4](https://linux-hardware.org/?probe=e59c8f50b4) | Oct 07, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [51442982cd](https://linux-hardware.org/?probe=51442982cd) | Oct 07, 2022 |
| MSI           | B150 PC MATE                | Desktop     | [d4a4eaeb7d](https://linux-hardware.org/?probe=d4a4eaeb7d) | Oct 07, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [865d1f0e6f](https://linux-hardware.org/?probe=865d1f0e6f) | Oct 07, 2022 |
| Lenovo        | ZHAOYANG E53-80 81CM        | Notebook    | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [8a89e7f4da](https://linux-hardware.org/?probe=8a89e7f4da) | Oct 06, 2022 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [0bf17a1e92](https://linux-hardware.org/?probe=0bf17a1e92) | Oct 06, 2022 |
| Dell          | 0C27VV A00                  | Desktop     | [0866f99d43](https://linux-hardware.org/?probe=0866f99d43) | Oct 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [236a43a0ce](https://linux-hardware.org/?probe=236a43a0ce) | Oct 06, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [1bf20fe68c](https://linux-hardware.org/?probe=1bf20fe68c) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [99ed468a82](https://linux-hardware.org/?probe=99ed468a82) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e8b8141f03](https://linux-hardware.org/?probe=e8b8141f03) | Oct 05, 2022 |
| Dell          | Inspiron 5406 2n1           | Convertible | [84ba2e1db1](https://linux-hardware.org/?probe=84ba2e1db1) | Oct 05, 2022 |
| HP            | Compaq 15                   | Notebook    | [bba22531ad](https://linux-hardware.org/?probe=bba22531ad) | Oct 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [e4df51e64f](https://linux-hardware.org/?probe=e4df51e64f) | Oct 05, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [2513dfd51e](https://linux-hardware.org/?probe=2513dfd51e) | Oct 05, 2022 |
| HP            | Compaq 15                   | Notebook    | [0f48335990](https://linux-hardware.org/?probe=0f48335990) | Oct 05, 2022 |
| Intel         | W7645                       | Notebook    | [4f76b8b5ad](https://linux-hardware.org/?probe=4f76b8b5ad) | Oct 04, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [bc05c332e6](https://linux-hardware.org/?probe=bc05c332e6) | Oct 04, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [1ba8422c66](https://linux-hardware.org/?probe=1ba8422c66) | Oct 04, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [082814c248](https://linux-hardware.org/?probe=082814c248) | Oct 04, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [3bc5547f39](https://linux-hardware.org/?probe=3bc5547f39) | Oct 04, 2022 |
| LG Electro... | 16T90P-K.ADB9U1             | Convertible | [d5bbcb7c9b](https://linux-hardware.org/?probe=d5bbcb7c9b) | Oct 04, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | Notebook    | [76709f5d09](https://linux-hardware.org/?probe=76709f5d09) | Oct 04, 2022 |
| HP            | ProLiant DL360 Gen9         | Server      | [eb5e8725ae](https://linux-hardware.org/?probe=eb5e8725ae) | Oct 04, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [e857a28ed2](https://linux-hardware.org/?probe=e857a28ed2) | Oct 04, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [bc03e42377](https://linux-hardware.org/?probe=bc03e42377) | Oct 03, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [2dc13504cf](https://linux-hardware.org/?probe=2dc13504cf) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [61d1e2102b](https://linux-hardware.org/?probe=61d1e2102b) | Oct 03, 2022 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [6e0ea7e989](https://linux-hardware.org/?probe=6e0ea7e989) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [28b873114a](https://linux-hardware.org/?probe=28b873114a) | Oct 03, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [330f866cf3](https://linux-hardware.org/?probe=330f866cf3) | Oct 03, 2022 |
| Gateway       | DX4850                      | Desktop     | [419e3338fb](https://linux-hardware.org/?probe=419e3338fb) | Oct 02, 2022 |
| ASUSTek       | ZenBook UX562FD_UX562FD     | Convertible | [b9f2861719](https://linux-hardware.org/?probe=b9f2861719) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [7221bbf8e7](https://linux-hardware.org/?probe=7221bbf8e7) | Oct 01, 2022 |
| Apple         | MacBookPro9,1               | Notebook    | [08db9e8d75](https://linux-hardware.org/?probe=08db9e8d75) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [f05b832b90](https://linux-hardware.org/?probe=f05b832b90) | Oct 01, 2022 |
| Shuttle       | FS35V4                      | Desktop     | [e38fd71e40](https://linux-hardware.org/?probe=e38fd71e40) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [d638b38369](https://linux-hardware.org/?probe=d638b38369) | Sep 30, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [2b78a7c7f1](https://linux-hardware.org/?probe=2b78a7c7f1) | Sep 29, 2022 |
| Lenovo        | ThinkPad E590 20NB005MUS    | Notebook    | [4b198e87aa](https://linux-hardware.org/?probe=4b198e87aa) | Sep 28, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [dad71b5547](https://linux-hardware.org/?probe=dad71b5547) | Sep 28, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [ec59847e5b](https://linux-hardware.org/?probe=ec59847e5b) | Sep 27, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [19fe9ebfb6](https://linux-hardware.org/?probe=19fe9ebfb6) | Sep 27, 2022 |
| ASRock        | 990FX Extreme9              | Desktop     | [c7522b70ba](https://linux-hardware.org/?probe=c7522b70ba) | Sep 27, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [3e14df6c26](https://linux-hardware.org/?probe=3e14df6c26) | Sep 27, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| ASUSTek       | K93SV                       | Notebook    | [541a21ceb8](https://linux-hardware.org/?probe=541a21ceb8) | Sep 26, 2022 |
| Gigabyte      | AORUS 7 SB                  | Notebook    | [3e8222ad7c](https://linux-hardware.org/?probe=3e8222ad7c) | Sep 26, 2022 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [762ad6e460](https://linux-hardware.org/?probe=762ad6e460) | Sep 26, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [72bd6750e5](https://linux-hardware.org/?probe=72bd6750e5) | Sep 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | Notebook    | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [0d44032bc0](https://linux-hardware.org/?probe=0d44032bc0) | Sep 25, 2022 |
| Dell          | Latitude E5400              | Notebook    | [09be905a45](https://linux-hardware.org/?probe=09be905a45) | Sep 24, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [60635ca9bc](https://linux-hardware.org/?probe=60635ca9bc) | Sep 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [2a7c09d404](https://linux-hardware.org/?probe=2a7c09d404) | Sep 24, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [07f9a5063e](https://linux-hardware.org/?probe=07f9a5063e) | Sep 23, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [18a4d2bb72](https://linux-hardware.org/?probe=18a4d2bb72) | Sep 23, 2022 |
| Biostar       | TA75MH2                     | Desktop     | [e76fb13311](https://linux-hardware.org/?probe=e76fb13311) | Sep 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | Notebook    | [6e943a4d35](https://linux-hardware.org/?probe=6e943a4d35) | Sep 23, 2022 |
| HP            | Pavilion 14                 | Notebook    | [277d97cc71](https://linux-hardware.org/?probe=277d97cc71) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [384ab44e0a](https://linux-hardware.org/?probe=384ab44e0a) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [24c7d626c8](https://linux-hardware.org/?probe=24c7d626c8) | Sep 23, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [3b1de255e3](https://linux-hardware.org/?probe=3b1de255e3) | Sep 22, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [f6e7ad269e](https://linux-hardware.org/?probe=f6e7ad269e) | Sep 22, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [20691b389b](https://linux-hardware.org/?probe=20691b389b) | Sep 21, 2022 |
| AZW           | SER                         | Mini pc     | [9e9ee5be74](https://linux-hardware.org/?probe=9e9ee5be74) | Sep 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [6352f6fb82](https://linux-hardware.org/?probe=6352f6fb82) | Sep 21, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [2a27e3cb58](https://linux-hardware.org/?probe=2a27e3cb58) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [256ff04106](https://linux-hardware.org/?probe=256ff04106) | Sep 20, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [9b0dd73d61](https://linux-hardware.org/?probe=9b0dd73d61) | Sep 20, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [b7dcf8a06c](https://linux-hardware.org/?probe=b7dcf8a06c) | Sep 20, 2022 |
| Dell          | OptiPlex 9020 AIO           | All in one  | [f52114ac39](https://linux-hardware.org/?probe=f52114ac39) | Sep 19, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [4abbaf3df9](https://linux-hardware.org/?probe=4abbaf3df9) | Sep 19, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [41b1b790fd](https://linux-hardware.org/?probe=41b1b790fd) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Acer          | Aspire G7750                | Desktop     | [c54e28dc84](https://linux-hardware.org/?probe=c54e28dc84) | Sep 18, 2022 |
| Google        | Blooglet                    | Notebook    | [971a174a56](https://linux-hardware.org/?probe=971a174a56) | Sep 18, 2022 |
| Gigabyte      | B560M D3H                   | Desktop     | [515d75e6b7](https://linux-hardware.org/?probe=515d75e6b7) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [5aadfd37c5](https://linux-hardware.org/?probe=5aadfd37c5) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [82a1f45915](https://linux-hardware.org/?probe=82a1f45915) | Sep 17, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [382e0f70a3](https://linux-hardware.org/?probe=382e0f70a3) | Sep 17, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [4a903b438f](https://linux-hardware.org/?probe=4a903b438f) | Sep 17, 2022 |
| Intel         | NUC7i3BNB J22859-313        | Mini pc     | [97b748d5d3](https://linux-hardware.org/?probe=97b748d5d3) | Sep 16, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [4ee2b37edf](https://linux-hardware.org/?probe=4ee2b37edf) | Sep 16, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [3f362093da](https://linux-hardware.org/?probe=3f362093da) | Sep 16, 2022 |
| ASUSTek       | G501VW                      | Notebook    | [cf04ceb420](https://linux-hardware.org/?probe=cf04ceb420) | Sep 15, 2022 |
| Dell          | Latitude 7430               | Notebook    | [4fdf1a303c](https://linux-hardware.org/?probe=4fdf1a303c) | Sep 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ea2264656c](https://linux-hardware.org/?probe=ea2264656c) | Sep 15, 2022 |
| Google        | Treeya                      | Notebook    | [a2723e9afa](https://linux-hardware.org/?probe=a2723e9afa) | Sep 15, 2022 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [eb49db3a8c](https://linux-hardware.org/?probe=eb49db3a8c) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [3af5d11f3f](https://linux-hardware.org/?probe=3af5d11f3f) | Sep 14, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [356956ad10](https://linux-hardware.org/?probe=356956ad10) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Lenovo        | B40-70 80F30005BR           | Notebook    | [b899f1b7da](https://linux-hardware.org/?probe=b899f1b7da) | Sep 13, 2022 |
| Lenovo        | B40-70 80F30005BR           | Notebook    | [99be4451df](https://linux-hardware.org/?probe=99be4451df) | Sep 13, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [8aac6d779b](https://linux-hardware.org/?probe=8aac6d779b) | Sep 13, 2022 |
| Unknown       | Unknown                     | Other       | [1e94b50834](https://linux-hardware.org/?probe=1e94b50834) | Sep 12, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [703c55185d](https://linux-hardware.org/?probe=703c55185d) | Sep 12, 2022 |
| Sony          | SVE1512J6EW                 | Notebook    | [69e2400606](https://linux-hardware.org/?probe=69e2400606) | Sep 11, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [52f6655891](https://linux-hardware.org/?probe=52f6655891) | Sep 11, 2022 |
| Gigabyte      | Z77X-UP7                    | Desktop     | [1634db2e78](https://linux-hardware.org/?probe=1634db2e78) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [d79d03b7ef](https://linux-hardware.org/?probe=d79d03b7ef) | Sep 11, 2022 |
| Dell          | G15 5511                    | Notebook    | [b971c27fae](https://linux-hardware.org/?probe=b971c27fae) | Sep 10, 2022 |
| ASUSTek       | H81M-P PLUS                 | Desktop     | [1ede09cb8a](https://linux-hardware.org/?probe=1ede09cb8a) | Sep 10, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [50f39d7738](https://linux-hardware.org/?probe=50f39d7738) | Sep 09, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [17e4855f90](https://linux-hardware.org/?probe=17e4855f90) | Sep 09, 2022 |
| Dell          | Latitude 7430               | Notebook    | [b1cdbef6b2](https://linux-hardware.org/?probe=b1cdbef6b2) | Sep 09, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [b50a1bc29b](https://linux-hardware.org/?probe=b50a1bc29b) | Sep 09, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [d3f42d0c24](https://linux-hardware.org/?probe=d3f42d0c24) | Sep 08, 2022 |
| Acer          | Predator G3-571             | Notebook    | [553cf2f33f](https://linux-hardware.org/?probe=553cf2f33f) | Sep 08, 2022 |
| Dell          | Vostro 3700                 | Notebook    | [40e150eb3b](https://linux-hardware.org/?probe=40e150eb3b) | Sep 08, 2022 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [0efc3cb183](https://linux-hardware.org/?probe=0efc3cb183) | Sep 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [280ca4dce2](https://linux-hardware.org/?probe=280ca4dce2) | Sep 07, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [557860ffbd](https://linux-hardware.org/?probe=557860ffbd) | Sep 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [9d494c5486](https://linux-hardware.org/?probe=9d494c5486) | Sep 07, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [1f4f30c013](https://linux-hardware.org/?probe=1f4f30c013) | Sep 06, 2022 |
| MSI           | Z97-G43                     | Desktop     | [eeea153bb2](https://linux-hardware.org/?probe=eeea153bb2) | Sep 06, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [8a1c5532d6](https://linux-hardware.org/?probe=8a1c5532d6) | Sep 06, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [5c53e30fe6](https://linux-hardware.org/?probe=5c53e30fe6) | Sep 06, 2022 |
| HP            | 2B3E                        | All in one  | [4ccdce6df9](https://linux-hardware.org/?probe=4ccdce6df9) | Sep 06, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [0300dd1a2d](https://linux-hardware.org/?probe=0300dd1a2d) | Sep 05, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JM... | Notebook    | [d496e01f0e](https://linux-hardware.org/?probe=d496e01f0e) | Sep 05, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [85798fb011](https://linux-hardware.org/?probe=85798fb011) | Sep 05, 2022 |
| ASUSTek       | UX51VZA                     | Notebook    | [46aa1dbafa](https://linux-hardware.org/?probe=46aa1dbafa) | Sep 04, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [0c89daf254](https://linux-hardware.org/?probe=0c89daf254) | Sep 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8eec266b41](https://linux-hardware.org/?probe=8eec266b41) | Sep 03, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5c11f5477e](https://linux-hardware.org/?probe=5c11f5477e) | Sep 03, 2022 |
| ASRock        | A320M-HDV                   | Desktop     | [5a9342d8e9](https://linux-hardware.org/?probe=5a9342d8e9) | Sep 03, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [742579c33d](https://linux-hardware.org/?probe=742579c33d) | Sep 03, 2022 |
| HP            | Notebook                    | Notebook    | [a3b180cbb5](https://linux-hardware.org/?probe=a3b180cbb5) | Sep 03, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [71ff7749aa](https://linux-hardware.org/?probe=71ff7749aa) | Sep 03, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [4c9041cf15](https://linux-hardware.org/?probe=4c9041cf15) | Sep 03, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [4a452f0874](https://linux-hardware.org/?probe=4a452f0874) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [a4290c0678](https://linux-hardware.org/?probe=a4290c0678) | Sep 03, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [296c04b276](https://linux-hardware.org/?probe=296c04b276) | Sep 02, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0789b27bdb](https://linux-hardware.org/?probe=0789b27bdb) | Sep 02, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [33784347f5](https://linux-hardware.org/?probe=33784347f5) | Sep 02, 2022 |
| ASUSTek       | UX51VZA                     | Notebook    | [e93c1732ec](https://linux-hardware.org/?probe=e93c1732ec) | Sep 02, 2022 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [f77ecfe3bc](https://linux-hardware.org/?probe=f77ecfe3bc) | Sep 02, 2022 |
| Gigabyte      | GA-870A-UD3                 | Desktop     | [27840cf8d2](https://linux-hardware.org/?probe=27840cf8d2) | Sep 02, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [a1b5555512](https://linux-hardware.org/?probe=a1b5555512) | Sep 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [a15c233224](https://linux-hardware.org/?probe=a15c233224) | Sep 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [e8b9bc90f3](https://linux-hardware.org/?probe=e8b9bc90f3) | Sep 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [d34c9cb705](https://linux-hardware.org/?probe=d34c9cb705) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | Notebook    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| Lenovo        | IdeaPadFlex 3 11ADA05 82... | Convertible | [b99f4a264b](https://linux-hardware.org/?probe=b99f4a264b) | Sep 01, 2022 |
| ASUSTek       | P5K/EPU                     | Desktop     | [196d56922a](https://linux-hardware.org/?probe=196d56922a) | Aug 31, 2022 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [0166c06969](https://linux-hardware.org/?probe=0166c06969) | Aug 30, 2022 |
| Gigabyte      | H81M-DS2                    | Desktop     | [373a11a297](https://linux-hardware.org/?probe=373a11a297) | Aug 29, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [505eb9a97c](https://linux-hardware.org/?probe=505eb9a97c) | Aug 29, 2022 |
| Lenovo        | 32E4 SDK0J40697 WIN 3305... | Mini pc     | [3825d0ce9c](https://linux-hardware.org/?probe=3825d0ce9c) | Aug 29, 2022 |
| Gigabyte      | B85M-HD3                    | Desktop     | [dcb5e7a20c](https://linux-hardware.org/?probe=dcb5e7a20c) | Aug 29, 2022 |
| Dell          | Latitude 9420               | Notebook    | [0b8d883170](https://linux-hardware.org/?probe=0b8d883170) | Aug 29, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [3f4c6a4d48](https://linux-hardware.org/?probe=3f4c6a4d48) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| Google        | Eldrid                      | Notebook    | [ae53120bac](https://linux-hardware.org/?probe=ae53120bac) | Aug 28, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [8fae050683](https://linux-hardware.org/?probe=8fae050683) | Aug 28, 2022 |
| Gigabyte      | GA-MA770T-UD3               | Desktop     | [f6c6b627f7](https://linux-hardware.org/?probe=f6c6b627f7) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [20bea980d2](https://linux-hardware.org/?probe=20bea980d2) | Aug 28, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [93af020634](https://linux-hardware.org/?probe=93af020634) | Aug 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [11cd220cfd](https://linux-hardware.org/?probe=11cd220cfd) | Aug 27, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [1912258e10](https://linux-hardware.org/?probe=1912258e10) | Aug 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| ASRock        | B450M/ac R2.0               | Desktop     | [ede2f61f08](https://linux-hardware.org/?probe=ede2f61f08) | Aug 26, 2022 |
| Dell          | Latitude E6400              | Notebook    | [8517e82248](https://linux-hardware.org/?probe=8517e82248) | Aug 26, 2022 |
| Sony          | VGN-NR11Z_T                 | Notebook    | [54c1e7c198](https://linux-hardware.org/?probe=54c1e7c198) | Aug 26, 2022 |
| MSI           | A320M PRO-VD/S              | Desktop     | [676e223d96](https://linux-hardware.org/?probe=676e223d96) | Aug 25, 2022 |
| HP            | ProBook 4540s               | Notebook    | [f082a7566a](https://linux-hardware.org/?probe=f082a7566a) | Aug 24, 2022 |
| HP            | ProBook 4540s               | Notebook    | [de08e9b296](https://linux-hardware.org/?probe=de08e9b296) | Aug 24, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [36f10ad555](https://linux-hardware.org/?probe=36f10ad555) | Aug 24, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| ASUSTek       | B85-PLUS                    | Desktop     | [1eba4b558d](https://linux-hardware.org/?probe=1eba4b558d) | Aug 23, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [348dc86c64](https://linux-hardware.org/?probe=348dc86c64) | Aug 23, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [83e175bed9](https://linux-hardware.org/?probe=83e175bed9) | Aug 23, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [4b70fe47a2](https://linux-hardware.org/?probe=4b70fe47a2) | Aug 23, 2022 |
| ASRock        | FM2A88M-HD+ R3.0            | Desktop     | [10973eca34](https://linux-hardware.org/?probe=10973eca34) | Aug 22, 2022 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [cb43b7a4cf](https://linux-hardware.org/?probe=cb43b7a4cf) | Aug 22, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [c084ff3123](https://linux-hardware.org/?probe=c084ff3123) | Aug 22, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [4c201d43d0](https://linux-hardware.org/?probe=4c201d43d0) | Aug 22, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [1ae2767db3](https://linux-hardware.org/?probe=1ae2767db3) | Aug 22, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | Notebook    | [29d7ac6ea6](https://linux-hardware.org/?probe=29d7ac6ea6) | Aug 21, 2022 |
| Lenovo        | ThinkPad T500 2082BRG       | Notebook    | [c8f76780a1](https://linux-hardware.org/?probe=c8f76780a1) | Aug 21, 2022 |
| Toshiba       | Satellite P70-B             | Notebook    | [4e04d56e06](https://linux-hardware.org/?probe=4e04d56e06) | Aug 21, 2022 |
| Toshiba       | Satellite P70-B             | Notebook    | [402017a7ea](https://linux-hardware.org/?probe=402017a7ea) | Aug 21, 2022 |
| Dell          | G3 3500                     | Notebook    | [1e8edd3350](https://linux-hardware.org/?probe=1e8edd3350) | Aug 21, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [bdc4179004](https://linux-hardware.org/?probe=bdc4179004) | Aug 21, 2022 |
| HP            | ProBook 6570b               | Notebook    | [eba0cd02ec](https://linux-hardware.org/?probe=eba0cd02ec) | Aug 21, 2022 |
| Dell          | Inspiron 15-5578            | Notebook    | [a0ff8934e5](https://linux-hardware.org/?probe=a0ff8934e5) | Aug 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [8d5375bd39](https://linux-hardware.org/?probe=8d5375bd39) | Aug 20, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [b12d6e7967](https://linux-hardware.org/?probe=b12d6e7967) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [45bac2f9d1](https://linux-hardware.org/?probe=45bac2f9d1) | Aug 20, 2022 |
| Dell          | G3 3779                     | Notebook    | [a2b721ca15](https://linux-hardware.org/?probe=a2b721ca15) | Aug 19, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [e058dec94d](https://linux-hardware.org/?probe=e058dec94d) | Aug 19, 2022 |
| MSI           | GF75 Thin 10SCXR            | Notebook    | [b75c38c8a5](https://linux-hardware.org/?probe=b75c38c8a5) | Aug 19, 2022 |
| Dell          | Latitude 7280               | Notebook    | [63e00d0c9d](https://linux-hardware.org/?probe=63e00d0c9d) | Aug 18, 2022 |
| Samsung       | 950QDB                      | Convertible | [d4fc73ce00](https://linux-hardware.org/?probe=d4fc73ce00) | Aug 18, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [73649d898c](https://linux-hardware.org/?probe=73649d898c) | Aug 18, 2022 |
| ASUSTek       | Z10PC-D8 Series             | Desktop     | [1cb7c569c1](https://linux-hardware.org/?probe=1cb7c569c1) | Aug 17, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | Notebook    | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [dd98185972](https://linux-hardware.org/?probe=dd98185972) | Aug 16, 2022 |
| ASUSTek       | H170M-PLUS/BR               | Desktop     | [feb4e50ec5](https://linux-hardware.org/?probe=feb4e50ec5) | Aug 16, 2022 |
| Lenovo        | Bantry CRB SDK0J40700 WI... | Desktop     | [792eb4143f](https://linux-hardware.org/?probe=792eb4143f) | Aug 16, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| ZOTAC         | ZBOXNANO-CI520NANO/CI540... | Mini pc     | [96b090be6a](https://linux-hardware.org/?probe=96b090be6a) | Aug 15, 2022 |
| HP            | ProBook 6570b               | Notebook    | [b490a791c0](https://linux-hardware.org/?probe=b490a791c0) | Aug 15, 2022 |
| Dell          | Precision 3571              | Notebook    | [48c3133a7f](https://linux-hardware.org/?probe=48c3133a7f) | Aug 15, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [646d091037](https://linux-hardware.org/?probe=646d091037) | Aug 15, 2022 |
| HP            | 805D                        | Desktop     | [54f4e0fdb0](https://linux-hardware.org/?probe=54f4e0fdb0) | Aug 14, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [30820abfa2](https://linux-hardware.org/?probe=30820abfa2) | Aug 14, 2022 |
| ASUSTek       | NAGAMI                      | Desktop     | [c6c8918483](https://linux-hardware.org/?probe=c6c8918483) | Aug 12, 2022 |
| HP            | ZBook 15 G4                 | Notebook    | [92cacb2a11](https://linux-hardware.org/?probe=92cacb2a11) | Aug 12, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [ca96da9d08](https://linux-hardware.org/?probe=ca96da9d08) | Aug 12, 2022 |
| Dell          | 0C2XKD A01                  | Desktop     | [cfad241ca0](https://linux-hardware.org/?probe=cfad241ca0) | Aug 12, 2022 |
| Positivo      | POS-PARS760GCD POSITIVO     | Desktop     | [dc6e65929f](https://linux-hardware.org/?probe=dc6e65929f) | Aug 12, 2022 |
| Gigabyte      | H61M-S1                     | Desktop     | [18f3dd56e8](https://linux-hardware.org/?probe=18f3dd56e8) | Aug 11, 2022 |
| Panasonic     | CF-53JSWZGFF                | Notebook    | [88c83a7e28](https://linux-hardware.org/?probe=88c83a7e28) | Aug 11, 2022 |
| HP            | 8459                        | Desktop     | [677ca01f4f](https://linux-hardware.org/?probe=677ca01f4f) | Aug 11, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [d2f7a86fd8](https://linux-hardware.org/?probe=d2f7a86fd8) | Aug 11, 2022 |
| Dell          | Latitude 5590               | Notebook    | [a00272df56](https://linux-hardware.org/?probe=a00272df56) | Aug 11, 2022 |
| Timi          | TM1709                      | Notebook    | [26b592f734](https://linux-hardware.org/?probe=26b592f734) | Aug 11, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [ca185c2301](https://linux-hardware.org/?probe=ca185c2301) | Aug 10, 2022 |
| Unknown       | Unknown                     | Other       | [23e67d3f72](https://linux-hardware.org/?probe=23e67d3f72) | Aug 10, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | Notebook    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| HP            | ProBook 6570b               | Notebook    | [0acbdaf806](https://linux-hardware.org/?probe=0acbdaf806) | Aug 10, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [9ac3c0b157](https://linux-hardware.org/?probe=9ac3c0b157) | Aug 09, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [14aebc0034](https://linux-hardware.org/?probe=14aebc0034) | Aug 09, 2022 |
| HP            | G62                         | Notebook    | [430fe133db](https://linux-hardware.org/?probe=430fe133db) | Aug 09, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [4b74670050](https://linux-hardware.org/?probe=4b74670050) | Aug 08, 2022 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [5b7d298ca6](https://linux-hardware.org/?probe=5b7d298ca6) | Aug 08, 2022 |
| Dell          | Latitude 5420               | Notebook    | [824404ee24](https://linux-hardware.org/?probe=824404ee24) | Aug 08, 2022 |
| HP            | 212A                        | Desktop     | [3b1662cede](https://linux-hardware.org/?probe=3b1662cede) | Aug 08, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [b2e805c687](https://linux-hardware.org/?probe=b2e805c687) | Aug 07, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [7311161548](https://linux-hardware.org/?probe=7311161548) | Aug 07, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [6eac3041ec](https://linux-hardware.org/?probe=6eac3041ec) | Aug 07, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [fb01882d07](https://linux-hardware.org/?probe=fb01882d07) | Aug 06, 2022 |
| MSI           | Z97 GAMING 7                | Desktop     | [01cf6a0897](https://linux-hardware.org/?probe=01cf6a0897) | Aug 06, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [1340311493](https://linux-hardware.org/?probe=1340311493) | Aug 06, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [23905636a4](https://linux-hardware.org/?probe=23905636a4) | Aug 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [9c77d1a0d5](https://linux-hardware.org/?probe=9c77d1a0d5) | Aug 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [ea189dab70](https://linux-hardware.org/?probe=ea189dab70) | Aug 06, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [9893d12c54](https://linux-hardware.org/?probe=9893d12c54) | Aug 06, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [6fa2b142e4](https://linux-hardware.org/?probe=6fa2b142e4) | Aug 06, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [49390f2f0e](https://linux-hardware.org/?probe=49390f2f0e) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [22e9ee373f](https://linux-hardware.org/?probe=22e9ee373f) | Aug 06, 2022 |
| Dell          | Precision 7530              | Notebook    | [40854a027f](https://linux-hardware.org/?probe=40854a027f) | Aug 05, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [df685682b3](https://linux-hardware.org/?probe=df685682b3) | Aug 05, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [e5e72c1264](https://linux-hardware.org/?probe=e5e72c1264) | Aug 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [d725206bff](https://linux-hardware.org/?probe=d725206bff) | Aug 04, 2022 |
| Dell          | Latitude 5590               | Notebook    | [52f059849a](https://linux-hardware.org/?probe=52f059849a) | Aug 04, 2022 |
| Dell          | Latitude 5590               | Notebook    | [47292ecf57](https://linux-hardware.org/?probe=47292ecf57) | Aug 04, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [42469385bc](https://linux-hardware.org/?probe=42469385bc) | Aug 04, 2022 |
| VIT           | P2402                       | Notebook    | [895454e84f](https://linux-hardware.org/?probe=895454e84f) | Aug 03, 2022 |
| Fujitsu       | LIFEBOOK U758               | Notebook    | [3a73f1ffdd](https://linux-hardware.org/?probe=3a73f1ffdd) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f79a1d3402](https://linux-hardware.org/?probe=f79a1d3402) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [b2e4380743](https://linux-hardware.org/?probe=b2e4380743) | Aug 03, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [9814fa3bca](https://linux-hardware.org/?probe=9814fa3bca) | Aug 03, 2022 |
| Hardkernel    | ODROID-C4                   | Soc         | [85ed0f33f0](https://linux-hardware.org/?probe=85ed0f33f0) | Aug 02, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [6adb003f2e](https://linux-hardware.org/?probe=6adb003f2e) | Aug 01, 2022 |
| ASUSTek       | X540SA                      | Notebook    | [4dbed1e983](https://linux-hardware.org/?probe=4dbed1e983) | Aug 01, 2022 |
| VIT           | P2402                       | Notebook    | [fd1ab8ad90](https://linux-hardware.org/?probe=fd1ab8ad90) | Aug 01, 2022 |
| Gigabyte      | G1.SNIPER B7-CF             | Desktop     | [83e4b444ae](https://linux-hardware.org/?probe=83e4b444ae) | Aug 01, 2022 |
| Gigabyte      | G1.SNIPER B7-CF             | Desktop     | [4e335cb7ce](https://linux-hardware.org/?probe=4e335cb7ce) | Aug 01, 2022 |
| Intel         | Unknown                     | Notebook    | [9fce3597b9](https://linux-hardware.org/?probe=9fce3597b9) | Aug 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [b99b5ef83f](https://linux-hardware.org/?probe=b99b5ef83f) | Aug 01, 2022 |
| HP            | ProBook 6570b               | Notebook    | [3898ce2b5f](https://linux-hardware.org/?probe=3898ce2b5f) | Aug 01, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [09c15c1ed8](https://linux-hardware.org/?probe=09c15c1ed8) | Jul 31, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [1a2713a2b0](https://linux-hardware.org/?probe=1a2713a2b0) | Jul 31, 2022 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [5dcf2bfdbd](https://linux-hardware.org/?probe=5dcf2bfdbd) | Jul 30, 2022 |
| Lenovo        | 1051L 60073                 | Tablet      | [4ae44495ba](https://linux-hardware.org/?probe=4ae44495ba) | Jul 30, 2022 |
| Dell          | 0F8098                      | Desktop     | [4e6058685a](https://linux-hardware.org/?probe=4e6058685a) | Jul 30, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [b1b842e547](https://linux-hardware.org/?probe=b1b842e547) | Jul 29, 2022 |
| HP            | 158A                        | Desktop     | [788844c3df](https://linux-hardware.org/?probe=788844c3df) | Jul 29, 2022 |
| ASUSTek       | Z87M-PLUS                   | Desktop     | [1b47c32e5d](https://linux-hardware.org/?probe=1b47c32e5d) | Jul 29, 2022 |
| HP            | 8754                        | Mini pc     | [1b0ae59d1f](https://linux-hardware.org/?probe=1b0ae59d1f) | Jul 28, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [2d3706b78b](https://linux-hardware.org/?probe=2d3706b78b) | Jul 28, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [73b9d340d2](https://linux-hardware.org/?probe=73b9d340d2) | Jul 28, 2022 |
| Dell          | Latitude 5590               | Notebook    | [7fa93449bd](https://linux-hardware.org/?probe=7fa93449bd) | Jul 28, 2022 |
| Dell          | Inspiron 7791 2n1           | Convertible | [8b027b07d9](https://linux-hardware.org/?probe=8b027b07d9) | Jul 27, 2022 |
| Lenovo        | 1051L 60073                 | Tablet      | [2b505d28f7](https://linux-hardware.org/?probe=2b505d28f7) | Jul 27, 2022 |
| Lenovo        | 1051L 60073                 | Tablet      | [51bf4e60d3](https://linux-hardware.org/?probe=51bf4e60d3) | Jul 27, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [9c0b784d1d](https://linux-hardware.org/?probe=9c0b784d1d) | Jul 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| HP            | 86E9 A                      | Desktop     | [6634eaee32](https://linux-hardware.org/?probe=6634eaee32) | Jul 27, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [3e40b1abe6](https://linux-hardware.org/?probe=3e40b1abe6) | Jul 27, 2022 |
| Dell          | G5 5590                     | Notebook    | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [ee8688ecdb](https://linux-hardware.org/?probe=ee8688ecdb) | Jul 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [03fa847263](https://linux-hardware.org/?probe=03fa847263) | Jul 26, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [50bab54f21](https://linux-hardware.org/?probe=50bab54f21) | Jul 26, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6967eac391](https://linux-hardware.org/?probe=6967eac391) | Jul 26, 2022 |
| ASRock        | Z270 Gaming K4              | Desktop     | [63612e20b4](https://linux-hardware.org/?probe=63612e20b4) | Jul 26, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [df38a7a1ff](https://linux-hardware.org/?probe=df38a7a1ff) | Jul 25, 2022 |
| ASRock        | 990FX Extreme3              | Desktop     | [158c8d142b](https://linux-hardware.org/?probe=158c8d142b) | Jul 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [2c515ee09a](https://linux-hardware.org/?probe=2c515ee09a) | Jul 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [e24e72037a](https://linux-hardware.org/?probe=e24e72037a) | Jul 24, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [d404840b57](https://linux-hardware.org/?probe=d404840b57) | Jul 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [5658129aa4](https://linux-hardware.org/?probe=5658129aa4) | Jul 24, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [ec23b6375e](https://linux-hardware.org/?probe=ec23b6375e) | Jul 24, 2022 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [ba1841221c](https://linux-hardware.org/?probe=ba1841221c) | Jul 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [021e469888](https://linux-hardware.org/?probe=021e469888) | Jul 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ea90d78c53](https://linux-hardware.org/?probe=ea90d78c53) | Jul 23, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6e6e65c711](https://linux-hardware.org/?probe=6e6e65c711) | Jul 23, 2022 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [88530d3d60](https://linux-hardware.org/?probe=88530d3d60) | Jul 23, 2022 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [24bc799d14](https://linux-hardware.org/?probe=24bc799d14) | Jul 23, 2022 |
| Gigabyte      | P35-DS3L                    | Desktop     | [4ae76fafc9](https://linux-hardware.org/?probe=4ae76fafc9) | Jul 22, 2022 |
| Shuttle       | NC01U V1.0                  | Desktop     | [827d6c81ae](https://linux-hardware.org/?probe=827d6c81ae) | Jul 22, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| HP            | G62                         | Notebook    | [418c1c572e](https://linux-hardware.org/?probe=418c1c572e) | Jul 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| Shuttle       | NC01U V1.0                  | Desktop     | [fecfaf6008](https://linux-hardware.org/?probe=fecfaf6008) | Jul 21, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [379da1a196](https://linux-hardware.org/?probe=379da1a196) | Jul 21, 2022 |
| HP            | 8054                        | Desktop     | [466d7f5591](https://linux-hardware.org/?probe=466d7f5591) | Jul 21, 2022 |
| HP            | 18E9                        | Desktop     | [f15b2671b0](https://linux-hardware.org/?probe=f15b2671b0) | Jul 21, 2022 |
| Lenovo        | ThinkPad E570 20H5006TFR    | Notebook    | [1a1220dc79](https://linux-hardware.org/?probe=1a1220dc79) | Jul 21, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [226924706f](https://linux-hardware.org/?probe=226924706f) | Jul 20, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS        | Desktop     | [468283ab86](https://linux-hardware.org/?probe=468283ab86) | Jul 20, 2022 |
| Gigabyte      | P35-DS3L                    | Desktop     | [cabd591648](https://linux-hardware.org/?probe=cabd591648) | Jul 20, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [0e3950303c](https://linux-hardware.org/?probe=0e3950303c) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [23f16d1cac](https://linux-hardware.org/?probe=23f16d1cac) | Jul 18, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [4f4b63a026](https://linux-hardware.org/?probe=4f4b63a026) | Jul 18, 2022 |
| Acer          | Predator PO3-620            | Desktop     | [f3e22c0e6d](https://linux-hardware.org/?probe=f3e22c0e6d) | Jul 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [d83a4d5121](https://linux-hardware.org/?probe=d83a4d5121) | Jul 18, 2022 |
| HONOR         | HYM-WXX                     | Notebook    | [654a2a5950](https://linux-hardware.org/?probe=654a2a5950) | Jul 17, 2022 |
| ASUSTek       | K53U                        | Notebook    | [20120e258a](https://linux-hardware.org/?probe=20120e258a) | Jul 16, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [f6670624ed](https://linux-hardware.org/?probe=f6670624ed) | Jul 16, 2022 |
| Standard      | Unknown                     | Notebook    | [3b4805163d](https://linux-hardware.org/?probe=3b4805163d) | Jul 15, 2022 |
| HP            | 1790                        | Desktop     | [ff91b0d921](https://linux-hardware.org/?probe=ff91b0d921) | Jul 15, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [01d595926f](https://linux-hardware.org/?probe=01d595926f) | Jul 15, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [789f614370](https://linux-hardware.org/?probe=789f614370) | Jul 14, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [57ef4db755](https://linux-hardware.org/?probe=57ef4db755) | Jul 14, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [02a5205d57](https://linux-hardware.org/?probe=02a5205d57) | Jul 14, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | Notebook    | [41136553b2](https://linux-hardware.org/?probe=41136553b2) | Jul 13, 2022 |
| MSI           | X99A XPOWER GAMING TITAN... | Desktop     | [e764729eeb](https://linux-hardware.org/?probe=e764729eeb) | Jul 13, 2022 |
| Lenovo        | YB1-X91L                    | Convertible | [3ea67a64cb](https://linux-hardware.org/?probe=3ea67a64cb) | Jul 13, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [7ecf3ad1b7](https://linux-hardware.org/?probe=7ecf3ad1b7) | Jul 13, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [6106db3d9a](https://linux-hardware.org/?probe=6106db3d9a) | Jul 12, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [fafb6deae6](https://linux-hardware.org/?probe=fafb6deae6) | Jul 12, 2022 |
| ASRock        | J4105M                      | Desktop     | [509b122b9b](https://linux-hardware.org/?probe=509b122b9b) | Jul 12, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [21ef2a8d9a](https://linux-hardware.org/?probe=21ef2a8d9a) | Jul 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [1bbf224b5c](https://linux-hardware.org/?probe=1bbf224b5c) | Jul 11, 2022 |
| Dell          | Latitude E5520              | Notebook    | [e04cdad7b7](https://linux-hardware.org/?probe=e04cdad7b7) | Jul 11, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [d6531258d0](https://linux-hardware.org/?probe=d6531258d0) | Jul 11, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [0967e17760](https://linux-hardware.org/?probe=0967e17760) | Jul 11, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [392310b916](https://linux-hardware.org/?probe=392310b916) | Jul 11, 2022 |
| System76      | Lemur Ultra                 | Notebook    | [10e8deaf3b](https://linux-hardware.org/?probe=10e8deaf3b) | Jul 11, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [61fe809791](https://linux-hardware.org/?probe=61fe809791) | Jul 10, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [f9e15346d3](https://linux-hardware.org/?probe=f9e15346d3) | Jul 10, 2022 |
| Lenovo        | IdeaPad Y430 2781           | Notebook    | [b8960364cb](https://linux-hardware.org/?probe=b8960364cb) | Jul 10, 2022 |
| Toshiba       | TECRA S11                   | Notebook    | [c33fa181ba](https://linux-hardware.org/?probe=c33fa181ba) | Jul 08, 2022 |
| Lenovo        | ThinkPad X200 7458FDG       | Notebook    | [435e7998bd](https://linux-hardware.org/?probe=435e7998bd) | Jul 08, 2022 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [d7e1136386](https://linux-hardware.org/?probe=d7e1136386) | Jul 07, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [6b007e333a](https://linux-hardware.org/?probe=6b007e333a) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [f09a1deecc](https://linux-hardware.org/?probe=f09a1deecc) | Jul 06, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [445bedc2c9](https://linux-hardware.org/?probe=445bedc2c9) | Jul 06, 2022 |
| HP            | G42                         | Notebook    | [4a57fd54c6](https://linux-hardware.org/?probe=4a57fd54c6) | Jul 06, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [e7e175955d](https://linux-hardware.org/?probe=e7e175955d) | Jul 05, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [a23d0fe53d](https://linux-hardware.org/?probe=a23d0fe53d) | Jul 04, 2022 |
| Sony          | VPCSA3M9E                   | Notebook    | [b36435a1fd](https://linux-hardware.org/?probe=b36435a1fd) | Jul 03, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [a8d8dfc814](https://linux-hardware.org/?probe=a8d8dfc814) | Jul 03, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [0dfbfe1182](https://linux-hardware.org/?probe=0dfbfe1182) | Jul 03, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [7d5d5c1a7e](https://linux-hardware.org/?probe=7d5d5c1a7e) | Jul 02, 2022 |
| HP            | 620                         | Notebook    | [cc970fdd77](https://linux-hardware.org/?probe=cc970fdd77) | Jul 02, 2022 |
| Lenovo        | ThinkPad T420 4180M8P       | Notebook    | [8a94c5bc15](https://linux-hardware.org/?probe=8a94c5bc15) | Jul 02, 2022 |
| Dell          | Latitude 7530               | Notebook    | [a66aca8921](https://linux-hardware.org/?probe=a66aca8921) | Jul 01, 2022 |
| HP            | 8459                        | Desktop     | [f43fdff127](https://linux-hardware.org/?probe=f43fdff127) | Jul 01, 2022 |
| Dell          | 06NWYK A01                  | Desktop     | [91408af847](https://linux-hardware.org/?probe=91408af847) | Jul 01, 2022 |
| ASUSTek       | ET2400A                     | Desktop     | [8801791f80](https://linux-hardware.org/?probe=8801791f80) | Jul 01, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [b691598870](https://linux-hardware.org/?probe=b691598870) | Jul 01, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [1647402099](https://linux-hardware.org/?probe=1647402099) | Jun 30, 2022 |
| Lenovo        | ThinkPad P15 Gen 1 20SUS... | Notebook    | [4b04ded505](https://linux-hardware.org/?probe=4b04ded505) | Jun 30, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [32e2995911](https://linux-hardware.org/?probe=32e2995911) | Jun 30, 2022 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [530c44caa8](https://linux-hardware.org/?probe=530c44caa8) | Jun 30, 2022 |
| Jumper        | EZpad                       | Notebook    | [5d5f3980e1](https://linux-hardware.org/?probe=5d5f3980e1) | Jun 30, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5fef19c107](https://linux-hardware.org/?probe=5fef19c107) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6dc02ab574](https://linux-hardware.org/?probe=6dc02ab574) | Jun 29, 2022 |
| HP            | EliteBook 840 G6            | Notebook    | [faaa7b9c81](https://linux-hardware.org/?probe=faaa7b9c81) | Jun 29, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [86a93d8ea0](https://linux-hardware.org/?probe=86a93d8ea0) | Jun 29, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [33c8a42a4d](https://linux-hardware.org/?probe=33c8a42a4d) | Jun 29, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [757741fe0d](https://linux-hardware.org/?probe=757741fe0d) | Jun 29, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [d2f3d5aefd](https://linux-hardware.org/?probe=d2f3d5aefd) | Jun 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [efb8cff806](https://linux-hardware.org/?probe=efb8cff806) | Jun 28, 2022 |
| Haier         | A1420EM                     | Notebook    | [3690a94424](https://linux-hardware.org/?probe=3690a94424) | Jun 28, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [183f3e59fb](https://linux-hardware.org/?probe=183f3e59fb) | Jun 28, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [f39c4bd8a0](https://linux-hardware.org/?probe=f39c4bd8a0) | Jun 27, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [a6555d107c](https://linux-hardware.org/?probe=a6555d107c) | Jun 27, 2022 |
| Intel         | X99                         | Desktop     | [4322217bc5](https://linux-hardware.org/?probe=4322217bc5) | Jun 26, 2022 |
| HP            | 15                          | Notebook    | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [e1918d8aab](https://linux-hardware.org/?probe=e1918d8aab) | Jun 25, 2022 |
| Medion        | E3216 MD60900               | Convertible | [2890f2581b](https://linux-hardware.org/?probe=2890f2581b) | Jun 25, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [6afa74e5b6](https://linux-hardware.org/?probe=6afa74e5b6) | Jun 25, 2022 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [2688876fc9](https://linux-hardware.org/?probe=2688876fc9) | Jun 25, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [554ba1726f](https://linux-hardware.org/?probe=554ba1726f) | Jun 24, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [3dffa312da](https://linux-hardware.org/?probe=3dffa312da) | Jun 24, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [10d0c2a6ea](https://linux-hardware.org/?probe=10d0c2a6ea) | Jun 24, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [f4f2e68e79](https://linux-hardware.org/?probe=f4f2e68e79) | Jun 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ece1eb60ef](https://linux-hardware.org/?probe=ece1eb60ef) | Jun 24, 2022 |
| Dell          | Latitude XT3                | Notebook    | [87377f03e2](https://linux-hardware.org/?probe=87377f03e2) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [04e6f0ee4a](https://linux-hardware.org/?probe=04e6f0ee4a) | Jun 24, 2022 |
| HP            | EliteBook 820 G1            | Notebook    | [ff4b7698ed](https://linux-hardware.org/?probe=ff4b7698ed) | Jun 23, 2022 |
| ABIT          | IP35 Pro                    | Desktop     | [a5f262c233](https://linux-hardware.org/?probe=a5f262c233) | Jun 23, 2022 |
| Dell          | Latitude 5590               | Notebook    | [aa45d97e0b](https://linux-hardware.org/?probe=aa45d97e0b) | Jun 23, 2022 |
| Dell          | Latitude 5590               | Notebook    | [3745dfcae3](https://linux-hardware.org/?probe=3745dfcae3) | Jun 23, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [ba64ef130a](https://linux-hardware.org/?probe=ba64ef130a) | Jun 23, 2022 |
| Clevo         | Modified by dsanke          | Notebook    | [b88e7a22fe](https://linux-hardware.org/?probe=b88e7a22fe) | Jun 22, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [62f47da7d2](https://linux-hardware.org/?probe=62f47da7d2) | Jun 22, 2022 |
| Dell          | Precision 5540              | Notebook    | [d4a5611433](https://linux-hardware.org/?probe=d4a5611433) | Jun 22, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [2727a44bcd](https://linux-hardware.org/?probe=2727a44bcd) | Jun 22, 2022 |
| ASUSTek       | GR8                         | Notebook    | [90afe7bdd7](https://linux-hardware.org/?probe=90afe7bdd7) | Jun 20, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [c931d0e7bf](https://linux-hardware.org/?probe=c931d0e7bf) | Jun 20, 2022 |
| Medion        | AXIR                        | All in one  | [c3acbcaea0](https://linux-hardware.org/?probe=c3acbcaea0) | Jun 20, 2022 |
| Dell          | XPS 17 9720                 | Notebook    | [2a36b8d90d](https://linux-hardware.org/?probe=2a36b8d90d) | Jun 20, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [8e1bc37281](https://linux-hardware.org/?probe=8e1bc37281) | Jun 19, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [2e67542246](https://linux-hardware.org/?probe=2e67542246) | Jun 19, 2022 |
| Packard Be... | H17HV                       | Notebook    | [daa945363e](https://linux-hardware.org/?probe=daa945363e) | Jun 19, 2022 |
| ASUSTek       | X550JF                      | Notebook    | [be77e811e2](https://linux-hardware.org/?probe=be77e811e2) | Jun 18, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [1dbf6320bc](https://linux-hardware.org/?probe=1dbf6320bc) | Jun 18, 2022 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [bbb784f2df](https://linux-hardware.org/?probe=bbb784f2df) | Jun 18, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [b75bebfda2](https://linux-hardware.org/?probe=b75bebfda2) | Jun 18, 2022 |
| HP            | 0A60h                       | Desktop     | [cb42238223](https://linux-hardware.org/?probe=cb42238223) | Jun 17, 2022 |
| ASRock        | B85M DASH/OL R2.0           | Desktop     | [c5763f8865](https://linux-hardware.org/?probe=c5763f8865) | Jun 17, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [aace637cfc](https://linux-hardware.org/?probe=aace637cfc) | Jun 17, 2022 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [bf18000c3c](https://linux-hardware.org/?probe=bf18000c3c) | Jun 17, 2022 |
| MSI           | Raider GE66 12UGS           | Notebook    | [d69dc59622](https://linux-hardware.org/?probe=d69dc59622) | Jun 16, 2022 |
| ASUSTek       | X99-A/USB                   | Desktop     | [3ad17f6d78](https://linux-hardware.org/?probe=3ad17f6d78) | Jun 16, 2022 |
| ASUSTek       | P5QC                        | Desktop     | [b9a53514e1](https://linux-hardware.org/?probe=b9a53514e1) | Jun 16, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [06bef31587](https://linux-hardware.org/?probe=06bef31587) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [d5f742022e](https://linux-hardware.org/?probe=d5f742022e) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [6c352cf792](https://linux-hardware.org/?probe=6c352cf792) | Jun 16, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7adac78ac0](https://linux-hardware.org/?probe=7adac78ac0) | Jun 15, 2022 |
| Acer          | Aspire E1-570G              | Notebook    | [060b0319ff](https://linux-hardware.org/?probe=060b0319ff) | Jun 15, 2022 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [b4a87914f3](https://linux-hardware.org/?probe=b4a87914f3) | Jun 15, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [91316a0904](https://linux-hardware.org/?probe=91316a0904) | Jun 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2b307211cd](https://linux-hardware.org/?probe=2b307211cd) | Jun 14, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [8faa0f9e6a](https://linux-hardware.org/?probe=8faa0f9e6a) | Jun 14, 2022 |
| ASUSTek       | UX51VZ                      | Notebook    | [d58122ba72](https://linux-hardware.org/?probe=d58122ba72) | Jun 13, 2022 |
| HP            | 620                         | Notebook    | [fe1a420f17](https://linux-hardware.org/?probe=fe1a420f17) | Jun 13, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [8b6f8e8952](https://linux-hardware.org/?probe=8b6f8e8952) | Jun 13, 2022 |
| Jumper        | EZpad                       | Notebook    | [3a5e6bc998](https://linux-hardware.org/?probe=3a5e6bc998) | Jun 13, 2022 |
| Dell          | Inspiron 1428               | Notebook    | [e47c98983f](https://linux-hardware.org/?probe=e47c98983f) | Jun 13, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [e65bd18434](https://linux-hardware.org/?probe=e65bd18434) | Jun 12, 2022 |
| Dell          | Inspiron 3521               | Notebook    | [13a04a66d8](https://linux-hardware.org/?probe=13a04a66d8) | Jun 12, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [013de61252](https://linux-hardware.org/?probe=013de61252) | Jun 12, 2022 |
| Dell          | 0KC9NP A01                  | Desktop     | [c573376df6](https://linux-hardware.org/?probe=c573376df6) | Jun 11, 2022 |
| HP            | Pavilion dv7                | Notebook    | [7f7678265b](https://linux-hardware.org/?probe=7f7678265b) | Jun 11, 2022 |
| HP            | Pavilion dv7                | Notebook    | [c8d1e1be32](https://linux-hardware.org/?probe=c8d1e1be32) | Jun 10, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [317ae1383a](https://linux-hardware.org/?probe=317ae1383a) | Jun 10, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [4f6d06171b](https://linux-hardware.org/?probe=4f6d06171b) | Jun 10, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [2c789d1a84](https://linux-hardware.org/?probe=2c789d1a84) | Jun 10, 2022 |
| HP            | 0A98h                       | Desktop     | [d3c54ab2d6](https://linux-hardware.org/?probe=d3c54ab2d6) | Jun 10, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [011acdab42](https://linux-hardware.org/?probe=011acdab42) | Jun 09, 2022 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [c751dcffff](https://linux-hardware.org/?probe=c751dcffff) | Jun 09, 2022 |
| HP            | Pavilion dv6                | Notebook    | [88a92966a3](https://linux-hardware.org/?probe=88a92966a3) | Jun 09, 2022 |
| Dell          | Latitude 5590               | Notebook    | [befc14c3db](https://linux-hardware.org/?probe=befc14c3db) | Jun 09, 2022 |
| Dell          | Latitude 5590               | Notebook    | [0c8e1f9f23](https://linux-hardware.org/?probe=0c8e1f9f23) | Jun 09, 2022 |
| MSI           | GP76 Leopard 11UH           | Notebook    | [8a3c021b8a](https://linux-hardware.org/?probe=8a3c021b8a) | Jun 08, 2022 |
| AZW           | Gemini J45                  | Desktop     | [f4d7238f95](https://linux-hardware.org/?probe=f4d7238f95) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [15f48b1e64](https://linux-hardware.org/?probe=15f48b1e64) | Jun 08, 2022 |
| System76      | Kudu Professional           | Notebook    | [4ffc6fc358](https://linux-hardware.org/?probe=4ffc6fc358) | Jun 08, 2022 |
| System76      | Kudu Professional           | Notebook    | [0c0e2ed5b2](https://linux-hardware.org/?probe=0c0e2ed5b2) | Jun 08, 2022 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | Notebook    | [54a2c4fa94](https://linux-hardware.org/?probe=54a2c4fa94) | Jun 08, 2022 |
| ASRock        | 960GM-VGS3 FX               | Desktop     | [82aa782cce](https://linux-hardware.org/?probe=82aa782cce) | Jun 08, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [3a58a9889b](https://linux-hardware.org/?probe=3a58a9889b) | Jun 08, 2022 |
| HP            | 620                         | Notebook    | [1adcb99573](https://linux-hardware.org/?probe=1adcb99573) | Jun 07, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | Notebook    | [f4c82e1fb6](https://linux-hardware.org/?probe=f4c82e1fb6) | Jun 07, 2022 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [1dea88e6b2](https://linux-hardware.org/?probe=1dea88e6b2) | Jun 07, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | Notebook    | [42aaad44bc](https://linux-hardware.org/?probe=42aaad44bc) | Jun 06, 2022 |
| Dell          | Inspiron 7391 2n1           | Convertible | [acf0372bdc](https://linux-hardware.org/?probe=acf0372bdc) | Jun 06, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | Notebook    | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| ASUSTek       | WS X299 PRO                 | Desktop     | [219d19f97e](https://linux-hardware.org/?probe=219d19f97e) | Jun 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9bc79127f3](https://linux-hardware.org/?probe=9bc79127f3) | Jun 06, 2022 |
| Toshiba       | Satellite C75D-A            | Notebook    | [a5aee20b56](https://linux-hardware.org/?probe=a5aee20b56) | Jun 06, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [11bba01e79](https://linux-hardware.org/?probe=11bba01e79) | Jun 06, 2022 |
| Positivo      | Q464C                       | Notebook    | [e00b91e529](https://linux-hardware.org/?probe=e00b91e529) | Jun 06, 2022 |
| Dell          | Latitude 5590               | Notebook    | [be30c04869](https://linux-hardware.org/?probe=be30c04869) | Jun 05, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [eb62d09265](https://linux-hardware.org/?probe=eb62d09265) | Jun 05, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [065dee2160](https://linux-hardware.org/?probe=065dee2160) | Jun 04, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [de4976b9dd](https://linux-hardware.org/?probe=de4976b9dd) | Jun 04, 2022 |
| Dell          | Latitude 5590               | Notebook    | [cc94c06259](https://linux-hardware.org/?probe=cc94c06259) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [5e57fb2871](https://linux-hardware.org/?probe=5e57fb2871) | Jun 04, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [70f49afd95](https://linux-hardware.org/?probe=70f49afd95) | Jun 04, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [96f8c08754](https://linux-hardware.org/?probe=96f8c08754) | Jun 04, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [11ec221a7e](https://linux-hardware.org/?probe=11ec221a7e) | Jun 04, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [95173b9d90](https://linux-hardware.org/?probe=95173b9d90) | Jun 04, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [a580e923a7](https://linux-hardware.org/?probe=a580e923a7) | Jun 03, 2022 |
| Dell          | Latitude E5470              | Notebook    | [e858488f6f](https://linux-hardware.org/?probe=e858488f6f) | Jun 03, 2022 |
| MSI           | CX61 2PC                    | Notebook    | [d3decdad4c](https://linux-hardware.org/?probe=d3decdad4c) | Jun 03, 2022 |
| HP            | ProBook 650 G2              | Notebook    | [27063b3b3a](https://linux-hardware.org/?probe=27063b3b3a) | Jun 03, 2022 |
| Dell          | OptiPlex 9020 AIO           | All in one  | [c8e2700624](https://linux-hardware.org/?probe=c8e2700624) | Jun 02, 2022 |
| Dell          | Latitude 7420               | Notebook    | [b2ba370a59](https://linux-hardware.org/?probe=b2ba370a59) | Jun 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [66e01e7706](https://linux-hardware.org/?probe=66e01e7706) | Jun 02, 2022 |
| SK hynix      | Onnyx III                   | Notebook    | [a04d3f7fd9](https://linux-hardware.org/?probe=a04d3f7fd9) | Jun 01, 2022 |
| ASUSTek       | TX201LA                     | Notebook    | [ba677dadab](https://linux-hardware.org/?probe=ba677dadab) | Jun 01, 2022 |
| Toshiba       | Satellite L50-A-1D6         | Notebook    | [0436371728](https://linux-hardware.org/?probe=0436371728) | Jun 01, 2022 |
| Toshiba       | Satellite L50-A-1D6         | Notebook    | [20d1a7e37b](https://linux-hardware.org/?probe=20d1a7e37b) | Jun 01, 2022 |
| Dell          | Inspiron 7537               | Notebook    | [2861999420](https://linux-hardware.org/?probe=2861999420) | Jun 01, 2022 |
| Dell          | Inspiron 7537               | Notebook    | [103bb197fa](https://linux-hardware.org/?probe=103bb197fa) | Jun 01, 2022 |
| Dell          | G7 7588                     | Notebook    | [3e41b876c2](https://linux-hardware.org/?probe=3e41b876c2) | May 31, 2022 |
| Dell          | Vostro 5481                 | Notebook    | [5fd6fe3593](https://linux-hardware.org/?probe=5fd6fe3593) | May 31, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [6378f52a92](https://linux-hardware.org/?probe=6378f52a92) | May 31, 2022 |
| Acer          | Aspire AV15-51              | Notebook    | [a9183103ee](https://linux-hardware.org/?probe=a9183103ee) | May 31, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [b450673fc0](https://linux-hardware.org/?probe=b450673fc0) | May 31, 2022 |
| Google        | Coral                       | Notebook    | [c517ad03c1](https://linux-hardware.org/?probe=c517ad03c1) | May 30, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [8eda28a8d4](https://linux-hardware.org/?probe=8eda28a8d4) | May 30, 2022 |
| Dell          | Precision 7710              | Notebook    | [f24e29d104](https://linux-hardware.org/?probe=f24e29d104) | May 30, 2022 |
| Dell          | Precision 7710              | Notebook    | [1bae5a0bf0](https://linux-hardware.org/?probe=1bae5a0bf0) | May 30, 2022 |
| ASUSTek       | X540LA                      | Notebook    | [57e0b15d17](https://linux-hardware.org/?probe=57e0b15d17) | May 30, 2022 |
| HP            | Pavilion g4                 | Notebook    | [39cdebfff4](https://linux-hardware.org/?probe=39cdebfff4) | May 29, 2022 |
| Medion        | S6445 MD61489               | Notebook    | [a933286b06](https://linux-hardware.org/?probe=a933286b06) | May 29, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [4f55b87c44](https://linux-hardware.org/?probe=4f55b87c44) | May 28, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [326c7a11e6](https://linux-hardware.org/?probe=326c7a11e6) | May 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [177e92d46b](https://linux-hardware.org/?probe=177e92d46b) | May 28, 2022 |
| HP            | 304Bh                       | Desktop     | [eaf30cead9](https://linux-hardware.org/?probe=eaf30cead9) | May 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8bcdd771fa](https://linux-hardware.org/?probe=8bcdd771fa) | May 27, 2022 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [f592de92c2](https://linux-hardware.org/?probe=f592de92c2) | May 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Gigabyte      | AORUS 15 XE4                | Notebook    | [f56ba4f49d](https://linux-hardware.org/?probe=f56ba4f49d) | May 27, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [1eddee7bcd](https://linux-hardware.org/?probe=1eddee7bcd) | May 26, 2022 |
| Lenovo        | ThinkCentre M90p 5864AL2    | Desktop     | [679cfd5a27](https://linux-hardware.org/?probe=679cfd5a27) | May 26, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [d153ce4509](https://linux-hardware.org/?probe=d153ce4509) | May 26, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [5410acf8ab](https://linux-hardware.org/?probe=5410acf8ab) | May 25, 2022 |
| Dell          | Vostro 5625                 | Notebook    | [2ae97190b6](https://linux-hardware.org/?probe=2ae97190b6) | May 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [540416deba](https://linux-hardware.org/?probe=540416deba) | May 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [887985e68a](https://linux-hardware.org/?probe=887985e68a) | May 24, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [63a10ce1e0](https://linux-hardware.org/?probe=63a10ce1e0) | May 23, 2022 |
| Acer          | Aspire M5-581TG             | Notebook    | [c6ffc6271c](https://linux-hardware.org/?probe=c6ffc6271c) | May 23, 2022 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [765d22e752](https://linux-hardware.org/?probe=765d22e752) | May 23, 2022 |
| HP            | 15                          | Notebook    | [a61f6dd1eb](https://linux-hardware.org/?probe=a61f6dd1eb) | May 23, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [52dce4d0c3](https://linux-hardware.org/?probe=52dce4d0c3) | May 23, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| ASRock        | B460 Phantom Gaming 4       | Desktop     | [2a6ba92f67](https://linux-hardware.org/?probe=2a6ba92f67) | May 22, 2022 |
| Lenovo        | ThinkPad T400 6474AL9       | Notebook    | [06ec4e94a2](https://linux-hardware.org/?probe=06ec4e94a2) | May 22, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [3d856e6f83](https://linux-hardware.org/?probe=3d856e6f83) | May 22, 2022 |
| Acer          | Aspire E5-573               | Notebook    | [dce8b618f8](https://linux-hardware.org/?probe=dce8b618f8) | May 22, 2022 |
| ASUSTek       | P7P55D-E PRO                | Desktop     | [dfa1010543](https://linux-hardware.org/?probe=dfa1010543) | May 21, 2022 |
| MSI           | 2AE0                        | Desktop     | [d99294cadc](https://linux-hardware.org/?probe=d99294cadc) | May 21, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [49df794b0b](https://linux-hardware.org/?probe=49df794b0b) | May 20, 2022 |
| Gigabyte      | B85M-D2V                    | Desktop     | [2bc6293c6a](https://linux-hardware.org/?probe=2bc6293c6a) | May 19, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [93b08c2d75](https://linux-hardware.org/?probe=93b08c2d75) | May 19, 2022 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [8266843e53](https://linux-hardware.org/?probe=8266843e53) | May 19, 2022 |
| Dell          | Inspiron 7572               | Notebook    | [b7747e3ea4](https://linux-hardware.org/?probe=b7747e3ea4) | May 19, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [b098eb44db](https://linux-hardware.org/?probe=b098eb44db) | May 18, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [cf5954d738](https://linux-hardware.org/?probe=cf5954d738) | May 18, 2022 |
| Dell          | Inspiron 5593               | Notebook    | [e08308603a](https://linux-hardware.org/?probe=e08308603a) | May 18, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [ba3b29db98](https://linux-hardware.org/?probe=ba3b29db98) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [0d4945774e](https://linux-hardware.org/?probe=0d4945774e) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [e771dc589b](https://linux-hardware.org/?probe=e771dc589b) | May 18, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [c01f14c77f](https://linux-hardware.org/?probe=c01f14c77f) | May 18, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0571b7cb83](https://linux-hardware.org/?probe=0571b7cb83) | May 18, 2022 |
| Acer          | Predator PH315-53           | Notebook    | [eb5d08e402](https://linux-hardware.org/?probe=eb5d08e402) | May 18, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [ee6e90c751](https://linux-hardware.org/?probe=ee6e90c751) | May 17, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [4bc8f93383](https://linux-hardware.org/?probe=4bc8f93383) | May 17, 2022 |
| Gigabyte      | B85M-D2V                    | Desktop     | [da9da96cda](https://linux-hardware.org/?probe=da9da96cda) | May 17, 2022 |
| HP            | ProBook 6470b               | Notebook    | [0581bb1005](https://linux-hardware.org/?probe=0581bb1005) | May 17, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [78fe695a2f](https://linux-hardware.org/?probe=78fe695a2f) | May 16, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [89b16a89c5](https://linux-hardware.org/?probe=89b16a89c5) | May 16, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [697a89162e](https://linux-hardware.org/?probe=697a89162e) | May 16, 2022 |
| HP            | Unknown                     | Notebook    | [796c00a0cd](https://linux-hardware.org/?probe=796c00a0cd) | May 15, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [bb68e24835](https://linux-hardware.org/?probe=bb68e24835) | May 15, 2022 |
| HP            | ProBook 6570b               | Notebook    | [e8c38d4e97](https://linux-hardware.org/?probe=e8c38d4e97) | May 15, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [2ee65efb9e](https://linux-hardware.org/?probe=2ee65efb9e) | May 15, 2022 |
| Apple         | MacBookPro13,2              | Notebook    | [68e687c794](https://linux-hardware.org/?probe=68e687c794) | May 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0ec606b729](https://linux-hardware.org/?probe=0ec606b729) | May 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [6fdf1cd28c](https://linux-hardware.org/?probe=6fdf1cd28c) | May 14, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [cd20eb0809](https://linux-hardware.org/?probe=cd20eb0809) | May 14, 2022 |
| MSI           | B450M PRO-M2                | Desktop     | [0bb720a248](https://linux-hardware.org/?probe=0bb720a248) | May 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [2d1e8a0642](https://linux-hardware.org/?probe=2d1e8a0642) | May 14, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [fb2a9c9ddf](https://linux-hardware.org/?probe=fb2a9c9ddf) | May 13, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [2152787c64](https://linux-hardware.org/?probe=2152787c64) | May 13, 2022 |
| ASUSTek       | F1A75-M LE                  | Desktop     | [823a7381c9](https://linux-hardware.org/?probe=823a7381c9) | May 13, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b03899e10b](https://linux-hardware.org/?probe=b03899e10b) | May 13, 2022 |
| ASUSTek       | F1A75-M LE                  | Desktop     | [d7733a6d5e](https://linux-hardware.org/?probe=d7733a6d5e) | May 13, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a0a6e09b95](https://linux-hardware.org/?probe=a0a6e09b95) | May 13, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [beaf18770e](https://linux-hardware.org/?probe=beaf18770e) | May 12, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [7923c29010](https://linux-hardware.org/?probe=7923c29010) | May 11, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [dba988f81d](https://linux-hardware.org/?probe=dba988f81d) | May 10, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [2ba7ecdb55](https://linux-hardware.org/?probe=2ba7ecdb55) | May 10, 2022 |
| Dell          | Latitude E6540              | Notebook    | [a5bb9f2b58](https://linux-hardware.org/?probe=a5bb9f2b58) | May 10, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [cb4ef48c3d](https://linux-hardware.org/?probe=cb4ef48c3d) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [76cc09b228](https://linux-hardware.org/?probe=76cc09b228) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [6500cb78c3](https://linux-hardware.org/?probe=6500cb78c3) | May 10, 2022 |
| HP            | 1998                        | Desktop     | [7f82a04d73](https://linux-hardware.org/?probe=7f82a04d73) | May 10, 2022 |
| Positivo      | POS-PIQ57BQA                | Desktop     | [f3abe22dd6](https://linux-hardware.org/?probe=f3abe22dd6) | May 09, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [f90e5f669e](https://linux-hardware.org/?probe=f90e5f669e) | May 09, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [dc9b228486](https://linux-hardware.org/?probe=dc9b228486) | May 08, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [8aefcd7551](https://linux-hardware.org/?probe=8aefcd7551) | May 08, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [4c4a006287](https://linux-hardware.org/?probe=4c4a006287) | May 07, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [5f90cb38d2](https://linux-hardware.org/?probe=5f90cb38d2) | May 07, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [a20a5df1ad](https://linux-hardware.org/?probe=a20a5df1ad) | May 06, 2022 |
| HP            | ProBook 6470b               | Notebook    | [7849fd57dc](https://linux-hardware.org/?probe=7849fd57dc) | May 06, 2022 |
| ASUSTek       | EB1501P                     | Desktop     | [f1d427d32b](https://linux-hardware.org/?probe=f1d427d32b) | May 06, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [8eb673ec29](https://linux-hardware.org/?probe=8eb673ec29) | May 06, 2022 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [ef836a5eca](https://linux-hardware.org/?probe=ef836a5eca) | May 06, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [aefe7a52e0](https://linux-hardware.org/?probe=aefe7a52e0) | May 06, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [0af35aa835](https://linux-hardware.org/?probe=0af35aa835) | May 06, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [b420f9214c](https://linux-hardware.org/?probe=b420f9214c) | May 06, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [71c0c4f257](https://linux-hardware.org/?probe=71c0c4f257) | May 05, 2022 |
| HP            | 2000                        | Notebook    | [1616d82d8e](https://linux-hardware.org/?probe=1616d82d8e) | May 05, 2022 |
| HP            | 2000                        | Notebook    | [f6f20fd25e](https://linux-hardware.org/?probe=f6f20fd25e) | May 05, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [0b27354c9c](https://linux-hardware.org/?probe=0b27354c9c) | May 05, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [8a561e2442](https://linux-hardware.org/?probe=8a561e2442) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [df622f284f](https://linux-hardware.org/?probe=df622f284f) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [d861de9453](https://linux-hardware.org/?probe=d861de9453) | May 04, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [53a75b2d5c](https://linux-hardware.org/?probe=53a75b2d5c) | May 04, 2022 |
| HP            | ProBook 6450b               | Notebook    | [0c23a5cbc2](https://linux-hardware.org/?probe=0c23a5cbc2) | May 04, 2022 |
| HP            | Pavilion dv7                | Notebook    | [978f98cef3](https://linux-hardware.org/?probe=978f98cef3) | May 04, 2022 |
| Alienware     | 17                          | Notebook    | [1a4cd056f8](https://linux-hardware.org/?probe=1a4cd056f8) | May 04, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [ce16326df2](https://linux-hardware.org/?probe=ce16326df2) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [62f9f79f7c](https://linux-hardware.org/?probe=62f9f79f7c) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [afce1937fe](https://linux-hardware.org/?probe=afce1937fe) | May 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [e126640b3b](https://linux-hardware.org/?probe=e126640b3b) | May 03, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [dadde1bbc0](https://linux-hardware.org/?probe=dadde1bbc0) | May 02, 2022 |
| Supermicro    | X8ST3                       | Desktop     | [a94462f4b5](https://linux-hardware.org/?probe=a94462f4b5) | May 02, 2022 |
| Lenovo        | ThinkPad T400 6474AL9       | Notebook    | [b303038c87](https://linux-hardware.org/?probe=b303038c87) | May 01, 2022 |
| Lenovo        | ThinkPad X201 3680AC2       | Notebook    | [5c4515d51e](https://linux-hardware.org/?probe=5c4515d51e) | May 01, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [d5b6bc1a67](https://linux-hardware.org/?probe=d5b6bc1a67) | May 01, 2022 |
| HP            | Pavilion Laptop 13-bb0xx... | Notebook    | [ae7d5dbb0c](https://linux-hardware.org/?probe=ae7d5dbb0c) | May 01, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [92c09fc927](https://linux-hardware.org/?probe=92c09fc927) | Apr 30, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [7a90a198f5](https://linux-hardware.org/?probe=7a90a198f5) | Apr 30, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [9328531b5a](https://linux-hardware.org/?probe=9328531b5a) | Apr 30, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | Notebook    | [73ee1262a6](https://linux-hardware.org/?probe=73ee1262a6) | Apr 30, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [75362e2061](https://linux-hardware.org/?probe=75362e2061) | Apr 30, 2022 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | Desktop     | [d9ac32b17d](https://linux-hardware.org/?probe=d9ac32b17d) | Apr 30, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [52609c3695](https://linux-hardware.org/?probe=52609c3695) | Apr 29, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [f301c52b41](https://linux-hardware.org/?probe=f301c52b41) | Apr 29, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [9f7923bcd2](https://linux-hardware.org/?probe=9f7923bcd2) | Apr 29, 2022 |
| HP            | 3396                        | Desktop     | [bd2e5eb69c](https://linux-hardware.org/?probe=bd2e5eb69c) | Apr 29, 2022 |
| HP            | 3396                        | Desktop     | [705baf56a1](https://linux-hardware.org/?probe=705baf56a1) | Apr 29, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [12a0105da3](https://linux-hardware.org/?probe=12a0105da3) | Apr 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [57271a5f8b](https://linux-hardware.org/?probe=57271a5f8b) | Apr 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [382d77c2b0](https://linux-hardware.org/?probe=382d77c2b0) | Apr 28, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [3206e0f075](https://linux-hardware.org/?probe=3206e0f075) | Apr 27, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [a7061bdb08](https://linux-hardware.org/?probe=a7061bdb08) | Apr 27, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [db9760ae3a](https://linux-hardware.org/?probe=db9760ae3a) | Apr 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [e77a313003](https://linux-hardware.org/?probe=e77a313003) | Apr 27, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [87d629883f](https://linux-hardware.org/?probe=87d629883f) | Apr 27, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [e4ecdec958](https://linux-hardware.org/?probe=e4ecdec958) | Apr 27, 2022 |
| Acer          | Aspire A515-55              | Notebook    | [fa33f58948](https://linux-hardware.org/?probe=fa33f58948) | Apr 27, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | Notebook    | [9fffc0babc](https://linux-hardware.org/?probe=9fffc0babc) | Apr 26, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | Notebook    | [b5f175a650](https://linux-hardware.org/?probe=b5f175a650) | Apr 26, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [fcd8a2962e](https://linux-hardware.org/?probe=fcd8a2962e) | Apr 26, 2022 |
| HP            | ENVY 17                     | Notebook    | [c33b35becc](https://linux-hardware.org/?probe=c33b35becc) | Apr 26, 2022 |
| ASUSTek       | G750JS                      | Notebook    | [24dab87910](https://linux-hardware.org/?probe=24dab87910) | Apr 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [e466d79804](https://linux-hardware.org/?probe=e466d79804) | Apr 26, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [89debf3e0e](https://linux-hardware.org/?probe=89debf3e0e) | Apr 25, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | Notebook    | [8e7b2c79a0](https://linux-hardware.org/?probe=8e7b2c79a0) | Apr 25, 2022 |
| ASUSTek       | P7P55 LX                    | Desktop     | [82c13f2b01](https://linux-hardware.org/?probe=82c13f2b01) | Apr 25, 2022 |
| HP            | 0AACh                       | Desktop     | [f9e511945d](https://linux-hardware.org/?probe=f9e511945d) | Apr 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [4b41ff5fb9](https://linux-hardware.org/?probe=4b41ff5fb9) | Apr 24, 2022 |
| Dell          | Studio 1558                 | Notebook    | [b31435ef0c](https://linux-hardware.org/?probe=b31435ef0c) | Apr 24, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [ef1e814871](https://linux-hardware.org/?probe=ef1e814871) | Apr 24, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [3ea846ae2a](https://linux-hardware.org/?probe=3ea846ae2a) | Apr 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [a260bf9ce6](https://linux-hardware.org/?probe=a260bf9ce6) | Apr 24, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [9877ddeaf6](https://linux-hardware.org/?probe=9877ddeaf6) | Apr 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [99e25e855e](https://linux-hardware.org/?probe=99e25e855e) | Apr 23, 2022 |
| Intel         | NUC6CAYB J23203-402         | Mini pc     | [86964dccfd](https://linux-hardware.org/?probe=86964dccfd) | Apr 23, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [9ba9e35d88](https://linux-hardware.org/?probe=9ba9e35d88) | Apr 23, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [848b9d8f5c](https://linux-hardware.org/?probe=848b9d8f5c) | Apr 22, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [da630d58cf](https://linux-hardware.org/?probe=da630d58cf) | Apr 22, 2022 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [8ee6cabf43](https://linux-hardware.org/?probe=8ee6cabf43) | Apr 22, 2022 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [28690580aa](https://linux-hardware.org/?probe=28690580aa) | Apr 22, 2022 |
| HP            | 2B4B                        | Desktop     | [c3dd8ed52a](https://linux-hardware.org/?probe=c3dd8ed52a) | Apr 22, 2022 |
| ASRock        | Z87 Pro4                    | Desktop     | [0c4cc8712f](https://linux-hardware.org/?probe=0c4cc8712f) | Apr 22, 2022 |
| ASUSTek       | P5P43TD                     | Desktop     | [8c7c0bd289](https://linux-hardware.org/?probe=8c7c0bd289) | Apr 21, 2022 |
| Dynabook      | PORTEGE X30L-J              | Notebook    | [5894fd3a34](https://linux-hardware.org/?probe=5894fd3a34) | Apr 21, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [566770a325](https://linux-hardware.org/?probe=566770a325) | Apr 21, 2022 |
| Positivo      | W940TU                      | Notebook    | [4d03effd28](https://linux-hardware.org/?probe=4d03effd28) | Apr 20, 2022 |
| Positivo      | W940TU                      | Notebook    | [971493b883](https://linux-hardware.org/?probe=971493b883) | Apr 20, 2022 |
| Dell          | Latitude XT3                | Notebook    | [6db9585e20](https://linux-hardware.org/?probe=6db9585e20) | Apr 20, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [b925b403ca](https://linux-hardware.org/?probe=b925b403ca) | Apr 20, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [53199db8c8](https://linux-hardware.org/?probe=53199db8c8) | Apr 20, 2022 |
| Lenovo        | ThinkPad T560 20FJS0NT04    | Notebook    | [19ebdf705a](https://linux-hardware.org/?probe=19ebdf705a) | Apr 20, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [ee7354dd8d](https://linux-hardware.org/?probe=ee7354dd8d) | Apr 19, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [f8e7d70919](https://linux-hardware.org/?probe=f8e7d70919) | Apr 18, 2022 |
| Shuttle       | FH61V                       | Desktop     | [2fae1ee493](https://linux-hardware.org/?probe=2fae1ee493) | Apr 18, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | Notebook    | [4ed718df3e](https://linux-hardware.org/?probe=4ed718df3e) | Apr 18, 2022 |
| Lenovo        | ThinkPad T420 4180DV2       | Notebook    | [402c31b107](https://linux-hardware.org/?probe=402c31b107) | Apr 18, 2022 |
| ASUSTek       | S551LB                      | Notebook    | [bb1d6d3623](https://linux-hardware.org/?probe=bb1d6d3623) | Apr 17, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [fe284f4173](https://linux-hardware.org/?probe=fe284f4173) | Apr 17, 2022 |
| MSI           | H81M-E33                    | Desktop     | [ff9197cd63](https://linux-hardware.org/?probe=ff9197cd63) | Apr 17, 2022 |
| Dell          | Latitude XT3                | Notebook    | [c4d7d751b7](https://linux-hardware.org/?probe=c4d7d751b7) | Apr 17, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [a767ef8b4e](https://linux-hardware.org/?probe=a767ef8b4e) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [5ce6ef2934](https://linux-hardware.org/?probe=5ce6ef2934) | Apr 16, 2022 |
| Dell          | 0HY9JP A00                  | Desktop     | [fed643b7ec](https://linux-hardware.org/?probe=fed643b7ec) | Apr 16, 2022 |
| Dell          | Latitude 7410               | Notebook    | [da82f8bba8](https://linux-hardware.org/?probe=da82f8bba8) | Apr 15, 2022 |
| Lenovo        | G40-45 80E1                 | Notebook    | [840ffde0c4](https://linux-hardware.org/?probe=840ffde0c4) | Apr 15, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [c00611352d](https://linux-hardware.org/?probe=c00611352d) | Apr 15, 2022 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [78a785e4a9](https://linux-hardware.org/?probe=78a785e4a9) | Apr 15, 2022 |
| Dell          | Latitude XT3                | Notebook    | [ce6c2e43a0](https://linux-hardware.org/?probe=ce6c2e43a0) | Apr 15, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [f52ef2faf2](https://linux-hardware.org/?probe=f52ef2faf2) | Apr 15, 2022 |
| Dell          | Latitude E6540              | Notebook    | [2ee68b5f38](https://linux-hardware.org/?probe=2ee68b5f38) | Apr 14, 2022 |
| Framework     | Laptop                      | Notebook    | [6846ee88e0](https://linux-hardware.org/?probe=6846ee88e0) | Apr 14, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [e172be90b8](https://linux-hardware.org/?probe=e172be90b8) | Apr 14, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [45b8eba74c](https://linux-hardware.org/?probe=45b8eba74c) | Apr 14, 2022 |
| HP            | Pavilion Laptop 15-cs3xx... | Notebook    | [3e09de906e](https://linux-hardware.org/?probe=3e09de906e) | Apr 14, 2022 |
| Lenovo        | ThinkPad T420 41786UU       | Notebook    | [2211278055](https://linux-hardware.org/?probe=2211278055) | Apr 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [4434290159](https://linux-hardware.org/?probe=4434290159) | Apr 14, 2022 |
| Lenovo        | ThinkPad P51 20HH000AUS     | Notebook    | [b7365a4abd](https://linux-hardware.org/?probe=b7365a4abd) | Apr 14, 2022 |
| Samsung       | R425D/R525D                 | Notebook    | [bd5a2f5943](https://linux-hardware.org/?probe=bd5a2f5943) | Apr 14, 2022 |
| Dell          | XPS 13 9300                 | Notebook    | [a21bd26d1e](https://linux-hardware.org/?probe=a21bd26d1e) | Apr 14, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [8888d86504](https://linux-hardware.org/?probe=8888d86504) | Apr 13, 2022 |
| Lenovo        | IdeaPad 710S Plus Touch-... | Notebook    | [f4578ea652](https://linux-hardware.org/?probe=f4578ea652) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [744144c472](https://linux-hardware.org/?probe=744144c472) | Apr 13, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [479b8d48fc](https://linux-hardware.org/?probe=479b8d48fc) | Apr 13, 2022 |
| MSI           | Z270 SLI PLUS               | Desktop     | [fa00f6ccd6](https://linux-hardware.org/?probe=fa00f6ccd6) | Apr 13, 2022 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [74191e7ffb](https://linux-hardware.org/?probe=74191e7ffb) | Apr 13, 2022 |
| ASUSTek       | PN50                        | Mini pc     | [2d44f4a10b](https://linux-hardware.org/?probe=2d44f4a10b) | Apr 13, 2022 |
| Toshiba       | Satellite P70-B             | Notebook    | [6c01bb2cc3](https://linux-hardware.org/?probe=6c01bb2cc3) | Apr 13, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [de2cf28654](https://linux-hardware.org/?probe=de2cf28654) | Apr 13, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [f74831788b](https://linux-hardware.org/?probe=f74831788b) | Apr 13, 2022 |
| Dell          | Latitude 5591               | Notebook    | [3f3f097a1a](https://linux-hardware.org/?probe=3f3f097a1a) | Apr 13, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [5923be4543](https://linux-hardware.org/?probe=5923be4543) | Apr 13, 2022 |
| Dell          | Latitude 7400               | Notebook    | [2c32d69a57](https://linux-hardware.org/?probe=2c32d69a57) | Apr 13, 2022 |
| HP            | Pavilion g6                 | Notebook    | [44035cfa83](https://linux-hardware.org/?probe=44035cfa83) | Apr 13, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [db6bf8f1b9](https://linux-hardware.org/?probe=db6bf8f1b9) | Apr 13, 2022 |
| Dell          | Precision 5520              | Notebook    | [eb5bfc87ed](https://linux-hardware.org/?probe=eb5bfc87ed) | Apr 12, 2022 |
| Lenovo        | ThinkPad T430 2349T2A       | Notebook    | [344710cc3a](https://linux-hardware.org/?probe=344710cc3a) | Apr 12, 2022 |
| HONOR         | NBD-WXX9                    | Notebook    | [090560f0c5](https://linux-hardware.org/?probe=090560f0c5) | Apr 12, 2022 |
| Dell          | Inspiron 7786               | Convertible | [cdf7aa0cb8](https://linux-hardware.org/?probe=cdf7aa0cb8) | Apr 11, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [c3d5951840](https://linux-hardware.org/?probe=c3d5951840) | Apr 10, 2022 |
| Lenovo        | IdeaPad Z585                | Notebook    | [5f84c70657](https://linux-hardware.org/?probe=5f84c70657) | Apr 10, 2022 |
| Notebook      | NS50_70MU                   | Notebook    | [cf76bb9e39](https://linux-hardware.org/?probe=cf76bb9e39) | Apr 10, 2022 |
| ASRock        | H110M-ITX                   | Desktop     | [13dff6f000](https://linux-hardware.org/?probe=13dff6f000) | Apr 10, 2022 |
| Dell          | G7 7790                     | Notebook    | [6cdb296d8e](https://linux-hardware.org/?probe=6cdb296d8e) | Apr 10, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [848a486145](https://linux-hardware.org/?probe=848a486145) | Apr 10, 2022 |
| eMachines     | G525                        | Notebook    | [6ba45c519c](https://linux-hardware.org/?probe=6ba45c519c) | Apr 09, 2022 |
| HP            | Laptop 14s-fq0xxx           | Notebook    | [18045cb759](https://linux-hardware.org/?probe=18045cb759) | Apr 09, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [272c9f107a](https://linux-hardware.org/?probe=272c9f107a) | Apr 09, 2022 |
| Intel         | MAHOBAY                     | Desktop     | [47119856f6](https://linux-hardware.org/?probe=47119856f6) | Apr 09, 2022 |
| Positivo      | N1250                       | Notebook    | [c64a47d6fc](https://linux-hardware.org/?probe=c64a47d6fc) | Apr 09, 2022 |
| Sony          | VPCF236FM                   | Notebook    | [ea109b146b](https://linux-hardware.org/?probe=ea109b146b) | Apr 08, 2022 |
| Sony          | SVE1511W1ESI                | Notebook    | [403773664b](https://linux-hardware.org/?probe=403773664b) | Apr 08, 2022 |
| Dell          | Latitude 5480               | Notebook    | [6891954221](https://linux-hardware.org/?probe=6891954221) | Apr 08, 2022 |
| HP            | ENVY 15                     | Notebook    | [cdd8aea3c3](https://linux-hardware.org/?probe=cdd8aea3c3) | Apr 07, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [dea231bf61](https://linux-hardware.org/?probe=dea231bf61) | Apr 07, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [b02ac7d8ce](https://linux-hardware.org/?probe=b02ac7d8ce) | Apr 07, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [64c2c15492](https://linux-hardware.org/?probe=64c2c15492) | Apr 05, 2022 |
| HP            | 3047h                       | Desktop     | [6766d428ef](https://linux-hardware.org/?probe=6766d428ef) | Apr 05, 2022 |
| Wortmann      | TERRA_MOBILE_1749           | Notebook    | [ee8ada5124](https://linux-hardware.org/?probe=ee8ada5124) | Apr 05, 2022 |
| MSI           | Z590 PRO WIFI               | Desktop     | [e7576083a0](https://linux-hardware.org/?probe=e7576083a0) | Apr 05, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [f98a0cf73b](https://linux-hardware.org/?probe=f98a0cf73b) | Apr 05, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [f72149904c](https://linux-hardware.org/?probe=f72149904c) | Apr 05, 2022 |
| Lenovo        | ThinkPad X260 20F5S0W22B    | Notebook    | [765eaec64d](https://linux-hardware.org/?probe=765eaec64d) | Apr 04, 2022 |
| Dell          | Latitude E6530              | Notebook    | [a63f363043](https://linux-hardware.org/?probe=a63f363043) | Apr 04, 2022 |
| Lenovo        | IdeaPadFlex 14 20308        | Notebook    | [9ecbc31fc2](https://linux-hardware.org/?probe=9ecbc31fc2) | Apr 04, 2022 |
| HP            | 805D                        | Desktop     | [198cff1b8e](https://linux-hardware.org/?probe=198cff1b8e) | Apr 04, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [73ecbc62b1](https://linux-hardware.org/?probe=73ecbc62b1) | Apr 04, 2022 |
| ASUSTek       | WS Z390 PRO                 | Desktop     | [9aea13fa1b](https://linux-hardware.org/?probe=9aea13fa1b) | Apr 04, 2022 |
| HP            | 1790                        | Desktop     | [5fd16b3e1e](https://linux-hardware.org/?probe=5fd16b3e1e) | Apr 03, 2022 |
| ASUSTek       | WS Z390 PRO                 | Desktop     | [ec2fb21c00](https://linux-hardware.org/?probe=ec2fb21c00) | Apr 03, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [5a4174b74d](https://linux-hardware.org/?probe=5a4174b74d) | Apr 02, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e087a37f5f](https://linux-hardware.org/?probe=e087a37f5f) | Apr 02, 2022 |
| MSI           | H81M-E35 V2                 | Desktop     | [a3aea1cbf5](https://linux-hardware.org/?probe=a3aea1cbf5) | Apr 02, 2022 |
| HP            | 805D                        | Desktop     | [709488e1da](https://linux-hardware.org/?probe=709488e1da) | Mar 31, 2022 |
| Lenovo        | ThinkPad T540p 20BEA00FR... | Notebook    | [c9323a9c40](https://linux-hardware.org/?probe=c9323a9c40) | Mar 31, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [946628cb20](https://linux-hardware.org/?probe=946628cb20) | Mar 30, 2022 |
| Dell          | 0PC5F7 A03                  | Desktop     | [3d76ab6a14](https://linux-hardware.org/?probe=3d76ab6a14) | Mar 30, 2022 |
| Dell          | Vostro 15 3515              | Notebook    | [b61b3e31e7](https://linux-hardware.org/?probe=b61b3e31e7) | Mar 30, 2022 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [f47336bbed](https://linux-hardware.org/?probe=f47336bbed) | Mar 30, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [f398041b40](https://linux-hardware.org/?probe=f398041b40) | Mar 29, 2022 |
| Intel         | DP965LT AAD41694-206        | Desktop     | [b6f8d31fa5](https://linux-hardware.org/?probe=b6f8d31fa5) | Mar 28, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [5dae1dd2a5](https://linux-hardware.org/?probe=5dae1dd2a5) | Mar 28, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [323ca65327](https://linux-hardware.org/?probe=323ca65327) | Mar 28, 2022 |
| HP            | Pavilion 14                 | Notebook    | [1b15a2e740](https://linux-hardware.org/?probe=1b15a2e740) | Mar 28, 2022 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [f457ad3a65](https://linux-hardware.org/?probe=f457ad3a65) | Mar 27, 2022 |
| HP            | Stream Notebook PC 14       | Notebook    | [9fc309dcaf](https://linux-hardware.org/?probe=9fc309dcaf) | Mar 27, 2022 |
| Lenovo        | NO DPK                      | Desktop     | [7cff95afcb](https://linux-hardware.org/?probe=7cff95afcb) | Mar 27, 2022 |
| Positivo      | Q232A                       | Notebook    | [fe29ba6b10](https://linux-hardware.org/?probe=fe29ba6b10) | Mar 27, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [d5f059e17d](https://linux-hardware.org/?probe=d5f059e17d) | Mar 26, 2022 |
| Lenovo        | IdeaPad S530-13IWL 81J7     | Notebook    | [a9a4291601](https://linux-hardware.org/?probe=a9a4291601) | Mar 26, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [dc2a2c1054](https://linux-hardware.org/?probe=dc2a2c1054) | Mar 25, 2022 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [f0a08eb35b](https://linux-hardware.org/?probe=f0a08eb35b) | Mar 25, 2022 |
| Dell          | Inspiron 5379               | Notebook    | [85c7a99f91](https://linux-hardware.org/?probe=85c7a99f91) | Mar 25, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [eef252e4f2](https://linux-hardware.org/?probe=eef252e4f2) | Mar 25, 2022 |
| Avell High... | B.ON                        | Notebook    | [19b689aa12](https://linux-hardware.org/?probe=19b689aa12) | Mar 25, 2022 |
| TrekStor      | Primetab T13B               | Tablet      | [c3cd38fd2d](https://linux-hardware.org/?probe=c3cd38fd2d) | Mar 25, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [a2db3c2cab](https://linux-hardware.org/?probe=a2db3c2cab) | Mar 24, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [3d513e3c6c](https://linux-hardware.org/?probe=3d513e3c6c) | Mar 24, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [cb089466a3](https://linux-hardware.org/?probe=cb089466a3) | Mar 24, 2022 |
| TrekStor      | Primetab T13B               | Tablet      | [43e7eab371](https://linux-hardware.org/?probe=43e7eab371) | Mar 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [c136393c4b](https://linux-hardware.org/?probe=c136393c4b) | Mar 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X760... | Notebook    | [713ff9dcb8](https://linux-hardware.org/?probe=713ff9dcb8) | Mar 23, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [96244433f0](https://linux-hardware.org/?probe=96244433f0) | Mar 23, 2022 |
| Gigabyte      | B75M-HD3                    | Desktop     | [b886cf0849](https://linux-hardware.org/?probe=b886cf0849) | Mar 23, 2022 |
| Acer          | Swift SF314-54G             | Notebook    | [615009b8ee](https://linux-hardware.org/?probe=615009b8ee) | Mar 23, 2022 |
| ASUSTek       | N550LF                      | Notebook    | [5e5462ce64](https://linux-hardware.org/?probe=5e5462ce64) | Mar 23, 2022 |
| Dell          | 0NK70N A03                  | Desktop     | [e5fe628a7b](https://linux-hardware.org/?probe=e5fe628a7b) | Mar 23, 2022 |
| Lenovo        | ThinkPad X230 23202DG       | Notebook    | [5b74db2557](https://linux-hardware.org/?probe=5b74db2557) | Mar 22, 2022 |
| MSI           | GP76 Leopard 11UH           | Notebook    | [d398e3284e](https://linux-hardware.org/?probe=d398e3284e) | Mar 22, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [c90c0f1819](https://linux-hardware.org/?probe=c90c0f1819) | Mar 22, 2022 |
| ASUSTek       | X555LNB                     | Notebook    | [ae49172b0f](https://linux-hardware.org/?probe=ae49172b0f) | Mar 21, 2022 |
| ASRock        | FM2A75 Pro4+                | Desktop     | [0d7edce12d](https://linux-hardware.org/?probe=0d7edce12d) | Mar 21, 2022 |
| ASUSTek       | X555LNB                     | Notebook    | [33e081f100](https://linux-hardware.org/?probe=33e081f100) | Mar 21, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [d3b1757cf5](https://linux-hardware.org/?probe=d3b1757cf5) | Mar 21, 2022 |
| ASUSTek       | K73E                        | Notebook    | [75069bd642](https://linux-hardware.org/?probe=75069bd642) | Mar 20, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [0e4992c717](https://linux-hardware.org/?probe=0e4992c717) | Mar 20, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [789a97d437](https://linux-hardware.org/?probe=789a97d437) | Mar 20, 2022 |
| HP            | 212B                        | Desktop     | [fd6a569226](https://linux-hardware.org/?probe=fd6a569226) | Mar 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [3607969e9d](https://linux-hardware.org/?probe=3607969e9d) | Mar 20, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [b1a437de4c](https://linux-hardware.org/?probe=b1a437de4c) | Mar 19, 2022 |
| HP            | 212B                        | Desktop     | [a85896bd48](https://linux-hardware.org/?probe=a85896bd48) | Mar 19, 2022 |
| HP            | 1589                        | Desktop     | [998f465bfc](https://linux-hardware.org/?probe=998f465bfc) | Mar 19, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 6 2... | Convertible | [05780b53fa](https://linux-hardware.org/?probe=05780b53fa) | Mar 19, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [d1f5b906e4](https://linux-hardware.org/?probe=d1f5b906e4) | Mar 19, 2022 |
| Panasonic     | FZ-M1CC-51BE                | Notebook    | [94e014ee40](https://linux-hardware.org/?probe=94e014ee40) | Mar 18, 2022 |
| Dell          | 0RY206                      | Desktop     | [df958219ab](https://linux-hardware.org/?probe=df958219ab) | Mar 18, 2022 |
| Dell          | 0RY206                      | Desktop     | [d46b854bd5](https://linux-hardware.org/?probe=d46b854bd5) | Mar 18, 2022 |
| ASUSTek       | K52Jr                       | Notebook    | [b05ec1dbda](https://linux-hardware.org/?probe=b05ec1dbda) | Mar 18, 2022 |
| Foxconn       | G41MXE/G41MXE-K             | Desktop     | [cd5c0f974e](https://linux-hardware.org/?probe=cd5c0f974e) | Mar 18, 2022 |
| Dell          | Precision M6300             | Notebook    | [aac71b9e66](https://linux-hardware.org/?probe=aac71b9e66) | Mar 17, 2022 |
| ASUSTek       | K52Jr                       | Notebook    | [77c6485b0f](https://linux-hardware.org/?probe=77c6485b0f) | Mar 17, 2022 |
| Packard Be... | IMEDIA S2885                | Desktop     | [1cf614db1e](https://linux-hardware.org/?probe=1cf614db1e) | Mar 17, 2022 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [c0db7c9966](https://linux-hardware.org/?probe=c0db7c9966) | Mar 17, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [6d8c8748e2](https://linux-hardware.org/?probe=6d8c8748e2) | Mar 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [8713806c38](https://linux-hardware.org/?probe=8713806c38) | Mar 17, 2022 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [42b5f424ce](https://linux-hardware.org/?probe=42b5f424ce) | Mar 17, 2022 |
| ASUSTek       | Zenbook UN5401QA_UN5401Q... | Convertible | [d0253d1ffc](https://linux-hardware.org/?probe=d0253d1ffc) | Mar 16, 2022 |
| GEO           | GeoFlex 110                 | Convertible | [763a31bbc5](https://linux-hardware.org/?probe=763a31bbc5) | Mar 16, 2022 |
| HP            | ProBook 430 G2              | Notebook    | [e2ad81141c](https://linux-hardware.org/?probe=e2ad81141c) | Mar 16, 2022 |
| ASRock        | 990FX Killer                | Desktop     | [acdee8aa65](https://linux-hardware.org/?probe=acdee8aa65) | Mar 15, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [8e9c955b47](https://linux-hardware.org/?probe=8e9c955b47) | Mar 15, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [bf80f02a40](https://linux-hardware.org/?probe=bf80f02a40) | Mar 15, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | Desktop     | [c8809e0561](https://linux-hardware.org/?probe=c8809e0561) | Mar 15, 2022 |
| ASRock        | B85M DASH/OL R2.0           | Desktop     | [162abf1031](https://linux-hardware.org/?probe=162abf1031) | Mar 15, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [95c6b15672](https://linux-hardware.org/?probe=95c6b15672) | Mar 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [96b413780f](https://linux-hardware.org/?probe=96b413780f) | Mar 13, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [8ab5133b14](https://linux-hardware.org/?probe=8ab5133b14) | Mar 13, 2022 |
| Lenovo        | B580 20144                  | Notebook    | [9918c132f0](https://linux-hardware.org/?probe=9918c132f0) | Mar 13, 2022 |
| Lenovo        | B580 20144                  | Notebook    | [fd9ec44205](https://linux-hardware.org/?probe=fd9ec44205) | Mar 13, 2022 |
| Dell          | Latitude E6430              | Notebook    | [bc21cb0e8b](https://linux-hardware.org/?probe=bc21cb0e8b) | Mar 13, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| Kubuntu 20.04   | 1362      | 44.85%  |
| Kubuntu 22.04   | 405       | 13.34%  |
| Kubuntu 20.10   | 254       | 8.36%   |
| Kubuntu 21.10   | 240       | 7.9%    |
| Kubuntu 21.04   | 213       | 7.01%   |
| Kubuntu 18.04   | 196       | 6.45%   |
| Kubuntu 19.10   | 178       | 5.86%   |
| Kubuntu 11      | 73        | 2.4%    |
| Kubuntu 22.10   | 27        | 0.89%   |
| Kubuntu 11.1    | 25        | 0.82%   |
| Kubuntu 19.04   | 22        | 0.72%   |
| Kubuntu 16.04   | 12        | 0.4%    |
| Kubuntu         | 8         | 0.26%   |
| Kubuntu 18.10   | 7         | 0.23%   |
| Kubuntu 2.0     | 6         | 0.2%    |
| Kubuntu 17.10   | 3         | 0.1%    |
| Kubuntu 17.04   | 2         | 0.07%   |
| Kubuntu 14.04   | 2         | 0.07%   |
| Kubuntu 20.08.3 | 1         | 0.03%   |
| Kubuntu 12.04   | 1         | 0.03%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Kubuntu | 2903      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.4.0-42-generic  | 103       | 3.09%   |
| 5.4.0-52-generic  | 68        | 2.04%   |
| 5.4.0-58-generic  | 59        | 1.77%   |
| 5.4.0-48-generic  | 59        | 1.77%   |
| 5.15.0-48-generic | 57        | 1.71%   |
| 5.15.0-46-generic | 52        | 1.56%   |
| 5.13.0-39-generic | 52        | 1.56%   |
| 5.4.0-40-generic  | 47        | 1.41%   |
| 5.13.0-28-generic | 44        | 1.32%   |
| 5.15.0-41-generic | 39        | 1.17%   |
| 5.11.0-37-generic | 38        | 1.14%   |
| 5.11.0-25-generic | 38        | 1.14%   |
| 5.13.0-30-generic | 37        | 1.11%   |
| 5.4.0-47-generic  | 36        | 1.08%   |
| 5.15.0-47-generic | 36        | 1.08%   |
| 5.4.0-65-generic  | 35        | 1.05%   |
| 5.15.0-52-generic | 35        | 1.05%   |
| 5.8.0-48-generic  | 34        | 1.02%   |
| 5.3.0-40-generic  | 34        | 1.02%   |
| 5.4.0-37-generic  | 33        | 0.99%   |
| 5.4.0-29-generic  | 33        | 0.99%   |
| 5.13.0-22-generic | 31        | 0.93%   |
| 5.4.0-45-generic  | 30        | 0.9%    |
| 5.15.0-43-generic | 30        | 0.9%    |
| 5.8.0-50-generic  | 29        | 0.87%   |
| 5.13.0-35-generic | 29        | 0.87%   |
| 5.8.0-63-generic  | 28        | 0.84%   |
| 5.4.0-54-generic  | 28        | 0.84%   |
| 5.3.0-26-generic  | 28        | 0.84%   |
| 5.13.0-40-generic | 28        | 0.84%   |
| 5.8.0-44-generic  | 27        | 0.81%   |
| 5.8.0-43-generic  | 27        | 0.81%   |
| 5.15.0-50-generic | 26        | 0.78%   |
| 5.15.0-40-generic | 26        | 0.78%   |
| 5.11.0-22-generic | 26        | 0.78%   |
| 5.4.0-26-generic  | 25        | 0.75%   |
| 5.15.0-27-generic | 25        | 0.75%   |
| 5.13.0-27-generic | 24        | 0.72%   |
| 5.4.0-56-generic  | 23        | 0.69%   |
| 5.3.0-42-generic  | 23        | 0.69%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 921       | 29.84%  |
| 5.15.0  | 434       | 14.06%  |
| 5.13.0  | 405       | 13.12%  |
| 5.8.0   | 404       | 13.09%  |
| 5.11.0  | 324       | 10.5%   |
| 5.3.0   | 224       | 7.26%   |
| 4.15.0  | 69        | 2.24%   |
| 5.0.0   | 36        | 1.17%   |
| 5.19.0  | 19        | 0.62%   |
| 5.10.0  | 17        | 0.55%   |
| 5.6.0   | 15        | 0.49%   |
| 5.17.0  | 13        | 0.42%   |
| 4.4.0   | 9         | 0.29%   |
| 4.18.0  | 8         | 0.26%   |
| 5.14.0  | 7         | 0.23%   |
| 5.9.0   | 5         | 0.16%   |
| 5.7.0   | 4         | 0.13%   |
| 6.0.0   | 3         | 0.1%    |
| 5.8.18  | 3         | 0.1%    |
| 5.18.4  | 3         | 0.1%    |
| 5.16.0  | 3         | 0.1%    |
| 5.12.8  | 3         | 0.1%    |
| 5.12.0  | 3         | 0.1%    |
| 4.13.0  | 3         | 0.1%    |
| 4.10.0  | 3         | 0.1%    |
| 6.0.1   | 2         | 0.06%   |
| 5.9.16  | 2         | 0.06%   |
| 5.9.10  | 2         | 0.06%   |
| 5.8.5   | 2         | 0.06%   |
| 5.8.2   | 2         | 0.06%   |
| 5.8.12  | 2         | 0.06%   |
| 5.8.1   | 2         | 0.06%   |
| 5.7.10  | 2         | 0.06%   |
| 5.7.1   | 2         | 0.06%   |
| 5.5.13  | 2         | 0.06%   |
| 5.19.5  | 2         | 0.06%   |
| 5.18.10 | 2         | 0.06%   |
| 5.17.5  | 2         | 0.06%   |
| 5.16.2  | 2         | 0.06%   |
| 5.16.10 | 2         | 0.06%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 928       | 30.11%  |
| 5.15    | 447       | 14.5%   |
| 5.8     | 420       | 13.63%  |
| 5.13    | 415       | 13.47%  |
| 5.11    | 330       | 10.71%  |
| 5.3     | 227       | 7.37%   |
| 4.15    | 70        | 2.27%   |
| 5.0     | 37        | 1.2%    |
| 5.10    | 28        | 0.91%   |
| 5.19    | 25        | 0.81%   |
| 5.6     | 20        | 0.65%   |
| 5.17    | 20        | 0.65%   |
| 5.14    | 16        | 0.52%   |
| 5.9     | 13        | 0.42%   |
| 5.12    | 13        | 0.42%   |
| 5.7     | 11        | 0.36%   |
| 5.18    | 10        | 0.32%   |
| 5.16    | 10        | 0.32%   |
| 4.18    | 10        | 0.32%   |
| 4.4     | 9         | 0.29%   |
| 6.0     | 7         | 0.23%   |
| 5.5     | 5         | 0.16%   |
| 4.13    | 3         | 0.1%    |
| 4.10    | 3         | 0.1%    |
| 5.1     | 2         | 0.06%   |
| 4.17    | 1         | 0.03%   |
| 4.12    | 1         | 0.03%   |
| 3.13    | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2887      | 99.45%  |
| i686    | 12        | 0.41%   |
| aarch64 | 3         | 0.1%    |
| riscv64 | 1         | 0.03%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 2021      | 68.32%  |
| KDE        | 892       | 30.16%  |
| GNOME      | 12        | 0.41%   |
| Cinnamon   | 9         | 0.3%    |
| Budgie     | 7         | 0.24%   |
| MATE       | 5         | 0.17%   |
| KDE4       | 3         | 0.1%    |
| XFCE       | 2         | 0.07%   |
| LXQt       | 2         | 0.07%   |
| X-Cinnamon | 1         | 0.03%   |
| Unity      | 1         | 0.03%   |
| i3         | 1         | 0.03%   |
| GNUstep    | 1         | 0.03%   |
| Unknown    | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2810      | 96.17%  |
| Wayland | 84        | 2.87%   |
| Tty     | 28        | 0.96%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 1645      | 55.57%  |
| Unknown | 1109      | 37.47%  |
| GDM     | 105       | 3.55%   |
| LightDM | 40        | 1.35%   |
| GDM3    | 37        | 1.25%   |
| TDM     | 21        | 0.71%   |
| SLiM    | 2         | 0.07%   |
| LXDM    | 1         | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1191      | 40.58%  |
| de_DE   | 235       | 8.01%   |
| ru_RU   | 158       | 5.38%   |
| pt_BR   | 144       | 4.91%   |
| en_GB   | 138       | 4.7%    |
| fr_FR   | 133       | 4.53%   |
| it_IT   | 119       | 4.05%   |
| Unknown | 77        | 2.62%   |
| en_CA   | 66        | 2.25%   |
| es_ES   | 60        | 2.04%   |
| en_AU   | 57        | 1.94%   |
| pl_PL   | 56        | 1.91%   |
| en_IN   | 50        | 1.7%    |
| C       | 31        | 1.06%   |
| hu_HU   | 24        | 0.82%   |
| ru_UA   | 23        | 0.78%   |
| es_MX   | 23        | 0.78%   |
| en_ZA   | 20        | 0.68%   |
| es_AR   | 18        | 0.61%   |
| cs_CZ   | 18        | 0.61%   |
| nl_NL   | 15        | 0.51%   |
| de_AT   | 15        | 0.51%   |
| en_NZ   | 14        | 0.48%   |
| de_CH   | 12        | 0.41%   |
| sv_SE   | 9         | 0.31%   |
| pt_PT   | 9         | 0.31%   |
| es_CO   | 9         | 0.31%   |
| en_IL   | 9         | 0.31%   |
| el_GR   | 9         | 0.31%   |
| uk_UA   | 8         | 0.27%   |
| tr_TR   | 8         | 0.27%   |
| es_CL   | 8         | 0.27%   |
| en_PH   | 8         | 0.27%   |
| en_IE   | 8         | 0.27%   |
| nl_BE   | 7         | 0.24%   |
| es_VE   | 7         | 0.24%   |
| zh_CN   | 6         | 0.2%    |
| sl_SI   | 6         | 0.2%    |
| sk_SK   | 6         | 0.2%    |
| ja_JP   | 6         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 1638      | 55.49%  |
| BIOS | 1314      | 44.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 2664      | 91.14%  |
| Btrfs    | 115       | 3.93%   |
| Overlay  | 71        | 2.43%   |
| Xfs      | 33        | 1.13%   |
| Zfs      | 17        | 0.58%   |
| Unknown  | 12        | 0.41%   |
| Ext3     | 4         | 0.14%   |
| Ext2     | 3         | 0.1%    |
| XXXX     | 1         | 0.03%   |
| Reiserfs | 1         | 0.03%   |
| Jfs      | 1         | 0.03%   |
| ExX4     | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1350      | 45.81%  |
| GPT     | 1313      | 44.55%  |
| MBR     | 284       | 9.64%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2534      | 86.31%  |
| Yes       | 402       | 13.69%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1778      | 60.48%  |
| Yes       | 1162      | 39.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 472       | 16.26%  |
| Lenovo              | 436       | 15.02%  |
| Dell                | 412       | 14.19%  |
| Hewlett-Packard     | 397       | 13.68%  |
| Gigabyte Technology | 235       | 8.1%    |
| MSI                 | 197       | 6.79%   |
| Acer                | 128       | 4.41%   |
| ASRock              | 111       | 3.82%   |
| Samsung Electronics | 38        | 1.31%   |
| Apple               | 37        | 1.27%   |
| Intel               | 32        | 1.1%    |
| HUAWEI              | 26        | 0.9%    |
| Unknown             | 24        | 0.83%   |
| Toshiba             | 23        | 0.79%   |
| TUXEDO              | 18        | 0.62%   |
| Sony                | 18        | 0.62%   |
| Notebook            | 17        | 0.59%   |
| Fujitsu             | 16        | 0.55%   |
| Google              | 15        | 0.52%   |
| Positivo            | 12        | 0.41%   |
| Pegatron            | 12        | 0.41%   |
| Timi                | 10        | 0.34%   |
| Medion              | 10        | 0.34%   |
| Biostar             | 10        | 0.34%   |
| Alienware           | 9         | 0.31%   |
| ZOTAC               | 8         | 0.28%   |
| Packard Bell        | 8         | 0.28%   |
| Foxconn             | 8         | 0.28%   |
| Microsoft           | 7         | 0.24%   |
| ECS                 | 7         | 0.24%   |
| System76            | 6         | 0.21%   |
| Supermicro          | 6         | 0.21%   |
| LG Electronics      | 6         | 0.21%   |
| Chuwi               | 6         | 0.21%   |
| Shuttle             | 5         | 0.17%   |
| PC Specialist       | 5         | 0.17%   |
| Panasonic           | 5         | 0.17%   |
| Huanan              | 5         | 0.17%   |
| Gateway             | 5         | 0.17%   |
| Fujitsu Siemens     | 5         | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 38        | 1.31%   |
| Unknown                            | 35        | 1.21%   |
| Gigabyte B450M DS3H                | 11        | 0.38%   |
| MSI MS-7C37                        | 9         | 0.31%   |
| HP Pavilion dv6                    | 9         | 0.31%   |
| ASUS ROG STRIX B550-F GAMING       | 9         | 0.31%   |
| HP Pavilion g6                     | 8         | 0.28%   |
| HP Notebook                        | 8         | 0.28%   |
| Dell OptiPlex 9020                 | 8         | 0.28%   |
| MSI MS-7B79                        | 7         | 0.24%   |
| HUAWEI NBLK-WAX9X                  | 7         | 0.24%   |
| Gigabyte 970A-DS3P                 | 7         | 0.24%   |
| Dell XPS 15 9560                   | 7         | 0.24%   |
| ASUS ROG STRIX X570-E GAMING       | 7         | 0.24%   |
| ASUS PRIME B450M-A                 | 7         | 0.24%   |
| ASUS PRIME B350-PLUS               | 7         | 0.24%   |
| MSI MS-7A34                        | 6         | 0.21%   |
| MSI MS-7817                        | 6         | 0.21%   |
| HP Pavilion dv7                    | 6         | 0.21%   |
| HP EliteBook 840 G5                | 6         | 0.21%   |
| HP EliteBook 840 G3                | 6         | 0.21%   |
| Gigabyte A320M-S2H                 | 6         | 0.21%   |
| Dell OptiPlex 7010                 | 6         | 0.21%   |
| MSI MS-7C02                        | 5         | 0.17%   |
| HP Pavilion 15                     | 5         | 0.17%   |
| HP EliteBook 840 G6                | 5         | 0.17%   |
| Gigabyte X570 AORUS MASTER         | 5         | 0.17%   |
| Dell XPS 15 9570                   | 5         | 0.17%   |
| Dell XPS 15 7590                   | 5         | 0.17%   |
| Dell XPS 13 9310                   | 5         | 0.17%   |
| Dell Latitude E6540                | 5         | 0.17%   |
| Dell Latitude 5480                 | 5         | 0.17%   |
| ASUS PRIME X570-P                  | 5         | 0.17%   |
| ASRock AB350 Pro4                  | 5         | 0.17%   |
| MSI MS-7996                        | 4         | 0.14%   |
| MSI MS-7693                        | 4         | 0.14%   |
| Lenovo Legion Y530-15ICH 81FV      | 4         | 0.14%   |
| Lenovo IdeaPad 330-15IKB 81DE      | 4         | 0.14%   |
| HP Laptop 15s-eq0xxx               | 4         | 0.14%   |
| HP ENVY x360 Convertible 13-ay0xxx | 4         | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 202       | 6.96%   |
| Dell Latitude      | 112       | 3.86%   |
| Dell Inspiron      | 103       | 3.55%   |
| HP Pavilion        | 85        | 2.93%   |
| Acer Aspire        | 85        | 2.93%   |
| Lenovo IdeaPad     | 80        | 2.76%   |
| ASUS ROG           | 62        | 2.14%   |
| ASUS PRIME         | 62        | 2.14%   |
| Dell XPS           | 60        | 2.07%   |
| HP ProBook         | 51        | 1.76%   |
| HP EliteBook       | 48        | 1.65%   |
| HP Laptop          | 42        | 1.45%   |
| Dell Precision     | 40        | 1.38%   |
| Dell OptiPlex      | 40        | 1.38%   |
| ASUS All           | 38        | 1.31%   |
| Unknown            | 35        | 1.21%   |
| ASUS VivoBook      | 34        | 1.17%   |
| ASUS TUF           | 30        | 1.03%   |
| Lenovo ThinkCentre | 25        | 0.86%   |
| HP Compaq          | 25        | 0.86%   |
| Dell Vostro        | 25        | 0.86%   |
| HP ENVY            | 23        | 0.79%   |
| Lenovo Yoga        | 22        | 0.76%   |
| Toshiba Satellite  | 19        | 0.65%   |
| Lenovo ThinkBook   | 18        | 0.62%   |
| Lenovo Legion      | 17        | 0.59%   |
| Gigabyte B450M     | 17        | 0.59%   |
| ASUS ZenBook       | 15        | 0.52%   |
| Acer Nitro         | 15        | 0.52%   |
| Gigabyte X570      | 14        | 0.48%   |
| ASUS ASUS          | 12        | 0.41%   |
| Acer Swift         | 11        | 0.38%   |
| Gigabyte A320M-S2H | 10        | 0.34%   |
| MSI MS-7C37        | 9         | 0.31%   |
| HP ZBook           | 9         | 0.31%   |
| ASUS M5A78L-M      | 9         | 0.31%   |
| HP Notebook        | 8         | 0.28%   |
| HP EliteDesk       | 8         | 0.28%   |
| Gigabyte B550      | 8         | 0.28%   |
| Gigabyte B450      | 8         | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 374       | 12.88%  |
| 2020    | 357       | 12.3%   |
| 2018    | 341       | 11.75%  |
| 2017    | 226       | 7.79%   |
| 2013    | 214       | 7.37%   |
| 2012    | 209       | 7.2%    |
| 2021    | 189       | 6.51%   |
| 2011    | 183       | 6.3%    |
| 2014    | 179       | 6.17%   |
| 2016    | 145       | 4.99%   |
| 2015    | 138       | 4.75%   |
| 2010    | 111       | 3.82%   |
| 2008    | 84        | 2.89%   |
| 2009    | 72        | 2.48%   |
| 2022    | 32        | 1.1%    |
| 2007    | 31        | 1.07%   |
| 2006    | 9         | 0.31%   |
| Unknown | 5         | 0.17%   |
| 2005    | 3         | 0.1%    |
| 2004    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1606      | 55.32%  |
| Desktop        | 1110      | 38.24%  |
| Convertible    | 87        | 3%      |
| Mini pc        | 38        | 1.31%   |
| All in one     | 27        | 0.93%   |
| Tablet         | 20        | 0.69%   |
| Server         | 11        | 0.38%   |
| System on chip | 3         | 0.1%    |
| Other          | 1         | 0.03%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2677      | 91.65%  |
| Enabled  | 244       | 8.35%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2883      | 99.31%  |
| Yes  | 20        | 0.69%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 762       | 26.03%  |
| 4.01-8.0    | 643       | 21.97%  |
| 8.01-16.0   | 548       | 18.72%  |
| 3.01-4.0    | 375       | 12.81%  |
| 32.01-64.0  | 374       | 12.78%  |
| 64.01-256.0 | 83        | 2.84%   |
| 24.01-32.0  | 74        | 2.53%   |
| 1.01-2.0    | 48        | 1.64%   |
| 2.01-3.0    | 20        | 0.68%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 822       | 26.11%  |
| 1.01-2.0   | 752       | 23.89%  |
| 4.01-8.0   | 704       | 22.36%  |
| 3.01-4.0   | 503       | 15.98%  |
| 8.01-16.0  | 236       | 7.5%    |
| 0.51-1.0   | 79        | 2.51%   |
| 16.01-24.0 | 30        | 0.95%   |
| 24.01-32.0 | 11        | 0.35%   |
| 32.01-64.0 | 6         | 0.19%   |
| 0.01-0.5   | 4         | 0.13%   |
| Unknown    | 1         | 0.03%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1581      | 53%     |
| 2      | 817       | 27.39%  |
| 3      | 270       | 9.05%   |
| 4      | 154       | 5.16%   |
| 5      | 80        | 2.68%   |
| 6      | 36        | 1.21%   |
| 7      | 17        | 0.57%   |
| 0      | 11        | 0.37%   |
| 8      | 5         | 0.17%   |
| 9      | 4         | 0.13%   |
| 10     | 3         | 0.1%    |
| 12     | 2         | 0.07%   |
| 11     | 2         | 0.07%   |
| 13     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1927      | 65.84%  |
| Yes       | 1000      | 34.16%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2491      | 85.69%  |
| No        | 416       | 14.31%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2226      | 76.34%  |
| No        | 690       | 23.66%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1900      | 64.87%  |
| No        | 1029      | 35.13%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 520       | 17.88%  |
| Germany      | 314       | 10.8%   |
| Russia       | 223       | 7.67%   |
| Brazil       | 189       | 6.5%    |
| France       | 167       | 5.74%   |
| Italy        | 153       | 5.26%   |
| UK           | 127       | 4.37%   |
| Spain        | 88        | 3.03%   |
| Poland       | 74        | 2.54%   |
| Canada       | 74        | 2.54%   |
| Netherlands  | 69        | 2.37%   |
| Ukraine      | 62        | 2.13%   |
| Australia    | 55        | 1.89%   |
| India        | 52        | 1.79%   |
| Mexico       | 41        | 1.41%   |
| Hungary      | 39        | 1.34%   |
| Switzerland  | 36        | 1.24%   |
| Czechia      | 33        | 1.13%   |
| Belgium      | 28        | 0.96%   |
| Argentina    | 27        | 0.93%   |
| Austria      | 26        | 0.89%   |
| Greece       | 23        | 0.79%   |
| South Africa | 22        | 0.76%   |
| Indonesia    | 21        | 0.72%   |
| Sweden       | 19        | 0.65%   |
| Bulgaria     | 19        | 0.65%   |
| Turkey       | 18        | 0.62%   |
| Slovenia     | 16        | 0.55%   |
| Romania      | 16        | 0.55%   |
| Finland      | 16        | 0.55%   |
| Denmark      | 15        | 0.52%   |
| New Zealand  | 14        | 0.48%   |
| Colombia     | 14        | 0.48%   |
| Belarus      | 14        | 0.48%   |
| Portugal     | 13        | 0.45%   |
| China        | 13        | 0.45%   |
| Serbia       | 12        | 0.41%   |
| Ireland      | 12        | 0.41%   |
| Israel       | 11        | 0.38%   |
| Norway       | 10        | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Moscow            | 61        | 2.01%   |
| Berlin            | 30        | 0.99%   |
| St Petersburg     | 26        | 0.86%   |
| Paris             | 26        | 0.86%   |
| Milan             | 23        | 0.76%   |
| Hamburg           | 22        | 0.73%   |
| Warsaw            | 21        | 0.69%   |
| Sao Paulo         | 21        | 0.69%   |
| Rome              | 21        | 0.69%   |
| Budapest          | 21        | 0.69%   |
| Kyiv              | 18        | 0.59%   |
| Rio de Janeiro    | 17        | 0.56%   |
| Sydney            | 16        | 0.53%   |
| Madrid            | 16        | 0.53%   |
| Cologne           | 15        | 0.5%    |
| Amsterdam         | 15        | 0.5%    |
| Zurich            | 14        | 0.46%   |
| Vienna            | 13        | 0.43%   |
| Munich            | 13        | 0.43%   |
| Novosibirsk       | 12        | 0.4%    |
| Minsk             | 12        | 0.4%    |
| Frankfurt am Main | 12        | 0.4%    |
| Sofia             | 11        | 0.36%   |
| Prague            | 11        | 0.36%   |
| Dallas            | 11        | 0.36%   |
| Athens            | 11        | 0.36%   |
| Melbourne         | 10        | 0.33%   |
| London            | 10        | 0.33%   |
| Jakarta           | 10        | 0.33%   |
| Belgrade          | 10        | 0.33%   |
| Wroclaw           | 9         | 0.3%    |
| Seattle           | 9         | 0.3%    |
| Los Angeles       | 9         | 0.3%    |
| Phoenix           | 8         | 0.26%   |
| Marseille         | 8         | 0.26%   |
| Dublin            | 8         | 0.26%   |
| Brasília         | 8         | 0.26%   |
| Auckland          | 8         | 0.26%   |
| Sindelfingen      | 7         | 0.23%   |
| Montreal          | 7         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 832       | 1247   | 18.11%  |
| WDC                       | 694       | 1125   | 15.11%  |
| Seagate                   | 630       | 940    | 13.71%  |
| Toshiba                   | 285       | 376    | 6.2%    |
| Kingston                  | 271       | 325    | 5.9%    |
| SanDisk                   | 227       | 266    | 4.94%   |
| Crucial                   | 188       | 233    | 4.09%   |
| Unknown                   | 157       | 195    | 3.42%   |
| Intel                     | 135       | 183    | 2.94%   |
| Hitachi                   | 125       | 150    | 2.72%   |
| SK hynix                  | 117       | 138    | 2.55%   |
| HGST                      | 90        | 114    | 1.96%   |
| A-DATA Technology         | 69        | 75     | 1.5%    |
| Micron Technology         | 66        | 73     | 1.44%   |
| Phison                    | 38        | 52     | 0.83%   |
| KIOXIA                    | 36        | 39     | 0.78%   |
| China                     | 30        | 40     | 0.65%   |
| Transcend                 | 28        | 30     | 0.61%   |
| Silicon Motion            | 27        | 31     | 0.59%   |
| Apple                     | 26        | 29     | 0.57%   |
| PNY                       | 25        | 29     | 0.54%   |
| Intenso                   | 24        | 27     | 0.52%   |
| Patriot                   | 23        | 31     | 0.5%    |
| OCZ                       | 21        | 28     | 0.46%   |
| LITEON                    | 21        | 23     | 0.46%   |
| SPCC                      | 20        | 25     | 0.44%   |
| Corsair                   | 18        | 27     | 0.39%   |
| Maxtor                    | 17        | 18     | 0.37%   |
| JMicron Technology        | 15        | 17     | 0.33%   |
| GOODRAM                   | 15        | 30     | 0.33%   |
| XPG                       | 14        | 15     | 0.3%    |
| KingSpec                  | 13        | 15     | 0.28%   |
| LITEONIT                  | 11        | 13     | 0.24%   |
| Fujitsu                   | 11        | 14     | 0.24%   |
| Unknown                   | 11        | 11     | 0.24%   |
| Team                      | 10        | 11     | 0.22%   |
| Gigabyte Technology       | 10        | 11     | 0.22%   |
| SABRENT                   | 9         | 12     | 0.2%    |
| Micron/Crucial Technology | 9         | 11     | 0.2%    |
| Apacer                    | 9         | 14     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB          | 52        | 1.01%   |
| Kingston SA400S37240G 240GB SSD    | 45        | 0.87%   |
| Samsung SSD 850 EVO 500GB          | 44        | 0.85%   |
| Samsung SSD 850 EVO 250GB          | 43        | 0.83%   |
| Samsung SSD 860 EVO 1TB            | 35        | 0.68%   |
| Samsung NVMe SSD Drive 500GB       | 33        | 0.64%   |
| Seagate ST1000LM035-1RK172 1TB     | 32        | 0.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 31        | 0.6%    |
| Samsung NVMe SSD Drive 1TB         | 30        | 0.58%   |
| Kingston SA400S37480G 480GB SSD    | 29        | 0.56%   |
| Toshiba MQ01ABD100 1TB             | 28        | 0.54%   |
| Samsung NVMe SSD Drive 512GB       | 28        | 0.54%   |
| Crucial CT1000MX500SSD1 1TB        | 27        | 0.52%   |
| Unknown MMC Card  32GB             | 26        | 0.5%    |
| Toshiba MQ04ABF100 1TB             | 26        | 0.5%    |
| Unknown MMC Card  64GB             | 24        | 0.47%   |
| HGST HTS721010A9E630 1TB           | 24        | 0.47%   |
| Seagate ST1000DM010-2EP102 1TB     | 23        | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB           | 22        | 0.43%   |
| Samsung SSD 970 EVO Plus 1TB       | 22        | 0.43%   |
| Samsung SSD 970 EVO Plus 500GB     | 21        | 0.41%   |
| Crucial CT500MX500SSD1 500GB       | 20        | 0.39%   |
| Toshiba DT01ACA100 1TB             | 18        | 0.35%   |
| Seagate ST500LT012-1DG142 500GB    | 18        | 0.35%   |
| Seagate ST500DM002-1BD142 500GB    | 18        | 0.35%   |
| Seagate ST4000DM004-2CV104 4TB     | 18        | 0.35%   |
| Seagate ST2000DM001-1ER164 2TB     | 18        | 0.35%   |
| Seagate ST1000DM003-1ER162 1TB     | 18        | 0.35%   |
| SanDisk SSD PLUS 240GB             | 18        | 0.35%   |
| Samsung SSD 860 EVO 250GB          | 18        | 0.35%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 17        | 0.33%   |
| Toshiba HDWD110 1TB                | 17        | 0.33%   |
| Seagate ST1000DM003-1CH162 1TB     | 17        | 0.33%   |
| Kingston SA400S37120G 120GB SSD    | 17        | 0.33%   |
| Seagate ST2000DM008-2FR102 2TB     | 16        | 0.31%   |
| Seagate Expansion 2TB              | 16        | 0.31%   |
| Kingston SV300S37A120G 120GB SSD   | 16        | 0.31%   |
| Seagate ST2000DM006-2DM164 2TB     | 15        | 0.29%   |
| SanDisk NVMe SSD Drive 512GB       | 15        | 0.29%   |
| Samsung SSD 860 EVO M.2 500GB      | 15        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 616       | 911    | 35.38%  |
| WDC                 | 533       | 894    | 30.61%  |
| Toshiba             | 202       | 267    | 11.6%   |
| Hitachi             | 125       | 150    | 7.18%   |
| Samsung Electronics | 92        | 141    | 5.28%   |
| HGST                | 89        | 113    | 5.11%   |
| Unknown             | 19        | 22     | 1.09%   |
| Maxtor              | 16        | 17     | 0.92%   |
| Fujitsu             | 10        | 13     | 0.57%   |
| SABRENT             | 9         | 12     | 0.52%   |
| Apple               | 9         | 9      | 0.52%   |
| Hewlett-Packard     | 3         | 5      | 0.17%   |
| USB3.0              | 2         | 2      | 0.11%   |
| SAGE                | 2         | 2      | 0.11%   |
| JMicron Technology  | 2         | 2      | 0.11%   |
| WD MediaMax         | 1         | 1      | 0.06%   |
| USB                 | 1         | 1      | 0.06%   |
| Magnetic Data       | 1         | 2      | 0.06%   |
| LIO-ORG             | 1         | 1      | 0.06%   |
| LaCie               | 1         | 1      | 0.06%   |
| KESU                | 1         | 1      | 0.06%   |
| ipTIME              | 1         | 1      | 0.06%   |
| IET                 | 1         | 1      | 0.06%   |
| HPE                 | 1         | 6      | 0.06%   |
| HGST HTS            | 1         | 1      | 0.06%   |
| ASMT                | 1         | 1      | 0.06%   |
| ASMedia             | 1         | 1      | 0.06%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 444       | 607    | 27.72%  |
| Kingston            | 205       | 245    | 12.8%   |
| Crucial             | 161       | 203    | 10.05%  |
| SanDisk             | 156       | 182    | 9.74%   |
| WDC                 | 82        | 105    | 5.12%   |
| A-DATA Technology   | 47        | 52     | 2.93%   |
| Intel               | 44        | 53     | 2.75%   |
| Toshiba             | 29        | 41     | 1.81%   |
| Micron Technology   | 29        | 32     | 1.81%   |
| China               | 29        | 39     | 1.81%   |
| SK hynix            | 23        | 25     | 1.44%   |
| Patriot             | 23        | 31     | 1.44%   |
| Transcend           | 22        | 22     | 1.37%   |
| PNY                 | 21        | 25     | 1.31%   |
| OCZ                 | 21        | 28     | 1.31%   |
| Intenso             | 20        | 23     | 1.25%   |
| SPCC                | 18        | 22     | 1.12%   |
| LITEON              | 16        | 17     | 1%      |
| GOODRAM             | 15        | 30     | 0.94%   |
| KingSpec            | 13        | 15     | 0.81%   |
| LITEONIT            | 11        | 13     | 0.69%   |
| Corsair             | 11        | 18     | 0.69%   |
| Apple               | 11        | 11     | 0.69%   |
| Team                | 9         | 9      | 0.56%   |
| Apacer              | 9         | 14     | 0.56%   |
| Mushkin             | 7         | 7      | 0.44%   |
| Verbatim            | 6         | 6      | 0.37%   |
| Plextor             | 6         | 7      | 0.37%   |
| Emtec               | 6         | 6      | 0.37%   |
| Lexar               | 5         | 6      | 0.31%   |
| ASMT                | 5         | 6      | 0.31%   |
| Unknown             | 4         | 4      | 0.25%   |
| Seagate             | 4         | 9      | 0.25%   |
| Netac               | 4         | 5      | 0.25%   |
| KingDian            | 4         | 5      | 0.25%   |
| Gigabyte Technology | 4         | 4      | 0.25%   |
| Dogfish             | 4         | 4      | 0.25%   |
| Unknown             | 4         | 4      | 0.25%   |
| Zheino              | 3         | 5      | 0.19%   |
| TO Exter            | 3         | 3      | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1395      | 2578   | 34.5%   |
| SSD     | 1373      | 2021   | 33.95%  |
| NVMe    | 1080      | 1459   | 26.71%  |
| MMC     | 137       | 170    | 3.39%   |
| Unknown | 59        | 80     | 1.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 2139      | 4446   | 60.78%  |
| NVMe | 1073      | 1444   | 30.49%  |
| SAS  | 170       | 248    | 4.83%   |
| MMC  | 137       | 170    | 3.89%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1516      | 2346   | 50.86%  |
| 0.51-1.0   | 924       | 1387   | 31%     |
| 1.01-2.0   | 308       | 475    | 10.33%  |
| 3.01-4.0   | 103       | 194    | 3.46%   |
| 2.01-3.0   | 73        | 105    | 2.45%   |
| 4.01-10.0  | 50        | 80     | 1.68%   |
| 10.01-20.0 | 7         | 12     | 0.23%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 753       | 25.04%  |
| 251-500        | 716       | 23.81%  |
| 501-1000       | 550       | 18.29%  |
| 1001-2000      | 295       | 9.81%   |
| More than 3000 | 224       | 7.45%   |
| 51-100         | 164       | 5.45%   |
| 2001-3000      | 133       | 4.42%   |
| 1-20           | 81        | 2.69%   |
| 21-50          | 78        | 2.59%   |
| Unknown        | 13        | 0.43%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 734       | 23.68%  |
| 101-250        | 518       | 16.71%  |
| 21-50          | 487       | 15.71%  |
| 51-100         | 405       | 13.06%  |
| 251-500        | 359       | 11.58%  |
| 501-1000       | 271       | 8.74%   |
| 1001-2000      | 150       | 4.84%   |
| More than 3000 | 109       | 3.52%   |
| 2001-3000      | 54        | 1.74%   |
| Unknown        | 13        | 0.42%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB              | 6         | 7      | 1.79%   |
| Seagate ST500LT012-9WS142 500GB       | 4         | 4      | 1.19%   |
| Seagate ST500DM002-1BD142 500GB       | 4         | 4      | 1.19%   |
| Seagate ST31000524AS 1TB              | 4         | 5      | 1.19%   |
| Seagate ST1000LM035-1RK172 1TB        | 4         | 4      | 1.19%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 4         | 10     | 1.19%   |
| Seagate ST1000DM003-1CH162 1TB        | 4         | 9      | 1.19%   |
| Toshiba MQ04ABF100 1TB                | 3         | 3      | 0.9%    |
| Toshiba MQ01ABD100 1TB                | 3         | 5      | 0.9%    |
| Seagate ST500LM012 HN-M500MBB 500GB   | 3         | 3      | 0.9%    |
| Seagate ST31000528AS 1TB              | 3         | 3      | 0.9%    |
| Seagate ST1000LM048-2E7172 1TB        | 3         | 3      | 0.9%    |
| Kingston SV300S37A120G 120GB SSD      | 3         | 3      | 0.9%    |
| Hitachi HTS547564A9E384 640GB         | 3         | 3      | 0.9%    |
| HGST HTS545050A7E680 500GB            | 3         | 3      | 0.9%    |
| Crucial CT1050MX300SSD1 1050GB        | 3         | 3      | 0.9%    |
| WDC WD5000AAKS-00V1A0 500GB           | 2         | 3      | 0.6%    |
| WDC WD5000AAKS-00A7B0 500GB           | 2         | 2      | 0.6%    |
| WDC WD3200JD-22KLB0 320GB             | 2         | 2      | 0.6%    |
| WDC WD20EFRX-68EUZN0 2TB              | 2         | 4      | 0.6%    |
| WDC WD15EARS-00Z5B1 1TB               | 2         | 2      | 0.6%    |
| WDC WD10EZEX-08WN4A0 1TB              | 2         | 2      | 0.6%    |
| WDC WD1001FALS-40U9B0 1TB             | 2         | 2      | 0.6%    |
| Toshiba MK1652GSX 160GB               | 2         | 2      | 0.6%    |
| Toshiba HDWD110 1TB                   | 2         | 2      | 0.6%    |
| SK hynix SC401 SATA 512GB SSD         | 2         | 2      | 0.6%    |
| Seagate ST9500325AS 500GB             | 2         | 2      | 0.6%    |
| Seagate ST9250315AS 250GB             | 2         | 3      | 0.6%    |
| Seagate ST500LT012-1DG142 500GB       | 2         | 2      | 0.6%    |
| Seagate ST500LM000-1EJ162 500GB       | 2         | 2      | 0.6%    |
| Seagate ST3500418AS 500GB             | 2         | 2      | 0.6%    |
| Seagate ST32000542AS 2TB              | 2         | 2      | 0.6%    |
| Seagate ST1000DM003-1SB102 1TB        | 2         | 2      | 0.6%    |
| SanDisk SSD PLUS 240GB                | 2         | 2      | 0.6%    |
| SanDisk SSD PLUS 240 GB               | 2         | 2      | 0.6%    |
| SanDisk SD9SN8W-128G-1006 128GB SSD   | 2         | 2      | 0.6%    |
| Samsung Electronics SSD 840 EVO 500GB | 2         | 3      | 0.6%    |
| Samsung Electronics HD502HJ 500GB     | 2         | 2      | 0.6%    |
| Intel SSDSA2M080G2GC 80GB             | 2         | 2      | 0.6%    |
| Hitachi HTS547575A9E384 752GB         | 2         | 2      | 0.6%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 75        | 97     | 23.22%  |
| WDC                 | 72        | 89     | 22.29%  |
| Samsung Electronics | 32        | 38     | 9.91%   |
| Toshiba             | 30        | 35     | 9.29%   |
| Hitachi             | 21        | 21     | 6.5%    |
| Crucial             | 14        | 17     | 4.33%   |
| HGST                | 13        | 14     | 4.02%   |
| SanDisk             | 11        | 11     | 3.41%   |
| Intel               | 10        | 10     | 3.1%    |
| SK hynix            | 8         | 8      | 2.48%   |
| Kingston            | 6         | 6      | 1.86%   |
| A-DATA Technology   | 5         | 5      | 1.55%   |
| Micron Technology   | 4         | 4      | 1.24%   |
| OCZ                 | 3         | 3      | 0.93%   |
| Maxtor              | 3         | 4      | 0.93%   |
| Apple               | 3         | 3      | 0.93%   |
| Fujitsu             | 2         | 2      | 0.62%   |
| Zheino              | 1         | 2      | 0.31%   |
| XPG                 | 1         | 1      | 0.31%   |
| VENO                | 1         | 1      | 0.31%   |
| tecmiyo             | 1         | 2      | 0.31%   |
| SPCC                | 1         | 1      | 0.31%   |
| Mushkin             | 1         | 1      | 0.31%   |
| LITEONIT            | 1         | 1      | 0.31%   |
| Drevo               | 1         | 1      | 0.31%   |
| BAITITON            | 1         | 1      | 0.31%   |
| ASMT                | 1         | 1      | 0.31%   |
| ASENNO              | 1         | 1      | 0.31%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 75        | 97     | 32.47%  |
| WDC                 | 70        | 87     | 30.3%   |
| Toshiba             | 26        | 31     | 11.26%  |
| Hitachi             | 21        | 21     | 9.09%   |
| Samsung Electronics | 17        | 22     | 7.36%   |
| HGST                | 13        | 14     | 5.63%   |
| Maxtor              | 3         | 4      | 1.3%    |
| Apple               | 3         | 3      | 1.3%    |
| Fujitsu             | 2         | 2      | 0.87%   |
| ASMT                | 1         | 1      | 0.43%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 212       | 282    | 70.2%   |
| SSD  | 74        | 82     | 24.5%   |
| NVMe | 16        | 16     | 5.3%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB         | 1         | 1      | 20%     |
| Samsung Electronics HD502IJ 500GB | 1         | 1      | 20%     |
| OCZ VERTEX460A 480GB SSD          | 1         | 1      | 20%     |
| Intel SSDSC2KB960G8 960GB         | 1         | 1      | 20%     |
| Hitachi HTS547550A9E384 500GB     | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 20%     |
| Samsung Electronics | 1         | 1      | 20%     |
| OCZ                 | 1         | 1      | 20%     |
| Intel               | 1         | 1      | 20%     |
| Hitachi             | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1482      | 3328   | 45.47%  |
| Works    | 1476      | 2595   | 45.29%  |
| Malfunc  | 297       | 380    | 9.11%   |
| Failed   | 4         | 5      | 0.12%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1872      | 48.88%  |
| AMD                              | 671       | 17.52%  |
| Samsung Electronics              | 367       | 9.58%   |
| SanDisk                          | 177       | 4.62%   |
| SK hynix                         | 93        | 2.43%   |
| Kingston Technology Company      | 71        | 1.85%   |
| ASMedia Technology               | 70        | 1.83%   |
| Toshiba America Info Systems     | 65        | 1.7%    |
| Phison Electronics               | 59        | 1.54%   |
| JMicron Technology               | 42        | 1.1%    |
| Silicon Motion                   | 39        | 1.02%   |
| Micron Technology                | 38        | 0.99%   |
| Micron/Crucial Technology        | 36        | 0.94%   |
| Marvell Technology Group         | 36        | 0.94%   |
| Nvidia                           | 33        | 0.86%   |
| KIOXIA                           | 32        | 0.84%   |
| ADATA Technology                 | 32        | 0.84%   |
| Realtek Semiconductor            | 15        | 0.39%   |
| Solid State Storage Technology   | 10        | 0.26%   |
| Lite-On Technology               | 10        | 0.26%   |
| Broadcom / LSI                   | 10        | 0.26%   |
| VIA Technologies                 | 7         | 0.18%   |
| Silicon Image                    | 7         | 0.18%   |
| Union Memory (Shenzhen)          | 6         | 0.16%   |
| LSI Logic / Symbios Logic        | 6         | 0.16%   |
| Apple                            | 5         | 0.13%   |
| Lenovo                           | 4         | 0.1%    |
| Seagate Technology               | 3         | 0.08%   |
| Unknown                          | 2         | 0.05%   |
| Silicon Integrated Systems [SiS] | 2         | 0.05%   |
| Integrated Technology Express    | 2         | 0.05%   |
| Adaptec                          | 2         | 0.05%   |
| Zhaoxin                          | 1         | 0.03%   |
| Yangtze Memory Technologies      | 1         | 0.03%   |
| Shenzhen Longsys Electronics     | 1         | 0.03%   |
| Promise Technology               | 1         | 0.03%   |
| Hewlett-Packard                  | 1         | 0.03%   |
| 3ware                            | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 477       | 10.89%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 230       | 5.25%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 165       | 3.77%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 150       | 3.42%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 133       | 3.04%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 118       | 2.69%   |
| AMD 400 Series Chipset SATA Controller                                         | 101       | 2.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 84        | 1.92%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 78        | 1.78%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 77        | 1.76%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 73        | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 71        | 1.62%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 68        | 1.55%   |
| Intel Volume Management Device NVMe RAID Controller                            | 67        | 1.53%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 64        | 1.46%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 57        | 1.3%    |
| Samsung NVMe SSD Controller 980                                                | 57        | 1.3%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 57        | 1.3%    |
| AMD 500 Series Chipset SATA Controller                                         | 53        | 1.21%   |
| Intel SSD 660P Series                                                          | 52        | 1.19%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 52        | 1.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 45        | 1.03%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 45        | 1.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 45        | 1.03%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 44        | 1%      |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 43        | 0.98%   |
| Intel Comet Lake SATA AHCI Controller                                          | 43        | 0.98%   |
| Intel SATA Controller [RAID mode]                                              | 42        | 0.96%   |
| Micron Non-Volatile memory controller                                          | 38        | 0.87%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 38        | 0.87%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 38        | 0.87%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 37        | 0.84%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 36        | 0.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 36        | 0.82%   |
| AMD 300 Series Chipset SATA Controller                                         | 36        | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 33        | 0.75%   |
| AMD FCH SATA Controller D                                                      | 33        | 0.75%   |
| Phison E12 NVMe Controller                                                     | 31        | 0.71%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 29        | 0.66%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 28        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2176      | 56.78%  |
| NVMe | 1072      | 27.97%  |
| IDE  | 292       | 7.62%   |
| RAID | 276       | 7.2%    |
| SAS  | 10        | 0.26%   |
| SCSI | 6         | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor        | Computers | Percent |
|---------------|-----------|---------|
| Intel         | 2100      | 72.34%  |
| AMD           | 798       | 27.49%  |
| ARM           | 2         | 0.07%   |
| sifive,u74-mc | 1         | 0.03%   |
| QUALCOMM      | 1         | 0.03%   |
| CentaurHauls  | 1         | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 45        | 1.55%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 39        | 1.34%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 38        | 1.31%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 35        | 1.2%    |
| AMD Ryzen 5 3600 6-Core Processor             | 34        | 1.17%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 33        | 1.13%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 33        | 1.13%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 33        | 1.13%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 32        | 1.1%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 32        | 1.1%    |
| Intel Core i5-7200U CPU @ 2.50GHz             | 32        | 1.1%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 31        | 1.07%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 27        | 0.93%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 27        | 0.93%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 26        | 0.89%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 24        | 0.83%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 24        | 0.83%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 22        | 0.76%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 22        | 0.76%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 21        | 0.72%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 19        | 0.65%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 19        | 0.65%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 18        | 0.62%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 16        | 0.55%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 16        | 0.55%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 16        | 0.55%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 16        | 0.55%   |
| AMD FX-8350 Eight-Core Processor              | 16        | 0.55%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 15        | 0.52%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 15        | 0.52%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 15        | 0.52%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 15        | 0.52%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 15        | 0.52%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 14        | 0.48%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 14        | 0.48%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 14        | 0.48%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 14        | 0.48%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 14        | 0.48%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 13        | 0.45%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 13        | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 705       | 24.24%  |
| Intel Core i5           | 646       | 22.21%  |
| AMD Ryzen 5             | 228       | 7.84%   |
| AMD Ryzen 7             | 170       | 5.85%   |
| Other                   | 168       | 5.78%   |
| Intel Core i3           | 156       | 5.36%   |
| Intel Celeron           | 98        | 3.37%   |
| Intel Core 2 Duo        | 75        | 2.58%   |
| Intel Xeon              | 68        | 2.34%   |
| AMD Ryzen 9             | 58        | 1.99%   |
| Intel Pentium           | 56        | 1.93%   |
| AMD FX                  | 56        | 1.93%   |
| AMD Ryzen 3             | 36        | 1.24%   |
| AMD A10                 | 28        | 0.96%   |
| Intel Core i9           | 27        | 0.93%   |
| Intel Atom              | 25        | 0.86%   |
| AMD A6                  | 23        | 0.79%   |
| Intel Pentium Dual-Core | 21        | 0.72%   |
| AMD A8                  | 21        | 0.72%   |
| AMD Ryzen 7 PRO         | 20        | 0.69%   |
| Intel Core 2 Quad       | 19        | 0.65%   |
| AMD Phenom II X4        | 19        | 0.65%   |
| AMD Athlon II X4        | 14        | 0.48%   |
| AMD A4                  | 13        | 0.45%   |
| Intel Pentium Silver    | 11        | 0.38%   |
| AMD Ryzen 5 PRO         | 9         | 0.31%   |
| AMD Athlon              | 9         | 0.31%   |
| Intel Genuine           | 8         | 0.28%   |
| AMD Ryzen Threadripper  | 8         | 0.28%   |
| AMD E1                  | 8         | 0.28%   |
| Intel Pentium Dual      | 7         | 0.24%   |
| AMD E                   | 7         | 0.24%   |
| AMD Athlon II X2        | 7         | 0.24%   |
| AMD E2                  | 6         | 0.21%   |
| AMD Athlon 64 X2        | 6         | 0.21%   |
| Intel Core m3           | 5         | 0.17%   |
| Intel Core 2            | 5         | 0.17%   |
| Intel Celeron Dual-Core | 5         | 0.17%   |
| AMD Phenom II X6        | 5         | 0.17%   |
| AMD Phenom II X2        | 5         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 1203      | 41.38%  |
| 2       | 949       | 32.65%  |
| 6       | 364       | 12.52%  |
| 8       | 251       | 8.63%   |
| 12      | 49        | 1.69%   |
| 1       | 32        | 1.1%    |
| 16      | 26        | 0.89%   |
| 14      | 8         | 0.28%   |
| 10      | 8         | 0.28%   |
| 3       | 5         | 0.17%   |
| 20      | 3         | 0.1%    |
| 32      | 2         | 0.07%   |
| 24      | 2         | 0.07%   |
| 18      | 2         | 0.07%   |
| Unknown | 2         | 0.07%   |
| 5       | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2880      | 99.21%  |
| 2       | 20        | 0.69%   |
| Unknown | 2         | 0.07%   |
| 4       | 1         | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2158      | 74.16%  |
| 1       | 750       | 25.77%  |
| Unknown | 2         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2899      | 99.86%  |
| 32-bit         | 2         | 0.07%   |
| Unknown        | 2         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 663       | 22.19%  |
| 0x306a9    | 156       | 5.22%   |
| 0x306c3    | 142       | 4.75%   |
| 0x206a7    | 141       | 4.72%   |
| 0x906ea    | 107       | 3.58%   |
| 0x806ec    | 92        | 3.08%   |
| 0x806c1    | 77        | 2.58%   |
| 0x40651    | 76        | 2.54%   |
| 0x806ea    | 75        | 2.51%   |
| 0x1067a    | 71        | 2.38%   |
| 0x08701021 | 67        | 2.24%   |
| 0x806e9    | 65        | 2.18%   |
| 0x906e9    | 64        | 2.14%   |
| 0x506e3    | 57        | 1.91%   |
| 0x406e3    | 51        | 1.71%   |
| 0x08108109 | 43        | 1.44%   |
| 0x0800820d | 42        | 1.41%   |
| 0x306d4    | 40        | 1.34%   |
| 0x08701013 | 38        | 1.27%   |
| 0x08600106 | 37        | 1.24%   |
| 0x06000852 | 37        | 1.24%   |
| 0x08108102 | 34        | 1.14%   |
| 0x0a50000c | 32        | 1.07%   |
| 0xa0652    | 31        | 1.04%   |
| 0x806eb    | 31        | 1.04%   |
| 0x706e5    | 30        | 1%      |
| 0x010000c8 | 26        | 0.87%   |
| 0x906ed    | 25        | 0.84%   |
| 0x20655    | 23        | 0.77%   |
| 0x406c4    | 21        | 0.7%    |
| 0x706a1    | 20        | 0.67%   |
| 0x30678    | 18        | 0.6%    |
| 0x06001119 | 18        | 0.6%    |
| 0x10676    | 17        | 0.57%   |
| 0x08600104 | 17        | 0.57%   |
| 0x6fb      | 16        | 0.54%   |
| 0x706a8    | 15        | 0.5%    |
| 0x306f2    | 15        | 0.5%    |
| 0xa0653    | 14        | 0.47%   |
| 0x806d1    | 14        | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 573       | 19.69%  |
| Haswell          | 298       | 10.24%  |
| Zen 2            | 209       | 7.18%   |
| IvyBridge        | 203       | 6.98%   |
| SandyBridge      | 180       | 6.19%   |
| Zen+             | 150       | 5.15%   |
| Skylake          | 148       | 5.09%   |
| TigerLake        | 107       | 3.68%   |
| Penryn           | 106       | 3.64%   |
| Zen 3            | 83        | 2.85%   |
| Zen              | 76        | 2.61%   |
| CometLake        | 73        | 2.51%   |
| Piledriver       | 72        | 2.47%   |
| K10              | 60        | 2.06%   |
| Westmere         | 58        | 1.99%   |
| IceLake          | 57        | 1.96%   |
| Broadwell        | 53        | 1.82%   |
| Silvermont       | 51        | 1.75%   |
| Goldmont plus    | 51        | 1.75%   |
| Core             | 47        | 1.62%   |
| Unknown          | 47        | 1.62%   |
| Nehalem          | 34        | 1.17%   |
| Excavator        | 34        | 1.17%   |
| Goldmont         | 18        | 0.62%   |
| Steamroller      | 16        | 0.55%   |
| Puma             | 15        | 0.52%   |
| K10 Llano        | 15        | 0.52%   |
| Alderlake Hybrid | 15        | 0.52%   |
| K8 Hammer        | 13        | 0.45%   |
| Jaguar           | 13        | 0.45%   |
| Bobcat           | 13        | 0.45%   |
| NetBurst         | 7         | 0.24%   |
| Bulldozer        | 7         | 0.24%   |
| Bonnell          | 5         | 0.17%   |
| Tremont          | 1         | 0.03%   |
| K8 & K10 hybrid  | 1         | 0.03%   |
| K6               | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1606      | 45.86%  |
| Nvidia                           | 1075      | 30.7%   |
| AMD                              | 807       | 23.04%  |
| ASPEED Technology                | 6         | 0.17%   |
| Matrox Electronics Systems       | 5         | 0.14%   |
| Zhaoxin                          | 1         | 0.03%   |
| Silicon Integrated Systems [SiS] | 1         | 0.03%   |
| ATI Technologies                 | 1         | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 122       | 3.4%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 113       | 3.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 102       | 2.85%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 99        | 2.76%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 94        | 2.62%   |
| AMD Renoir                                                                               | 87        | 2.43%   |
| Intel UHD Graphics 620                                                                   | 86        | 2.4%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 82        | 2.29%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 81        | 2.26%   |
| Intel HD Graphics 620                                                                    | 70        | 1.95%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 67        | 1.87%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 64        | 1.79%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 60        | 1.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 59        | 1.65%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 59        | 1.65%   |
| Intel HD Graphics 630                                                                    | 49        | 1.37%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 44        | 1.23%   |
| Intel HD Graphics 5500                                                                   | 44        | 1.23%   |
| Intel HD Graphics 530                                                                    | 44        | 1.23%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 41        | 1.14%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 40        | 1.12%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 39        | 1.09%   |
| AMD Cezanne                                                                              | 38        | 1.06%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 34        | 0.95%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 30        | 0.84%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 30        | 0.84%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 28        | 0.78%   |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 0.75%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 26        | 0.73%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 26        | 0.73%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 25        | 0.7%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 21        | 0.59%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 21        | 0.59%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 20        | 0.56%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 20        | 0.56%   |
| AMD Lucienne                                                                             | 20        | 0.56%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 19        | 0.53%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 19        | 0.53%   |
| Intel Iris Plus Graphics G7                                                              | 19        | 0.53%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 19        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 1061      | 36.41%  |
| 1 x AMD                  | 636       | 21.83%  |
| 1 x Nvidia               | 572       | 19.63%  |
| Intel + Nvidia           | 439       | 15.07%  |
| Intel + AMD              | 80        | 2.75%   |
| 2 x AMD                  | 47        | 1.61%   |
| AMD + Nvidia             | 44        | 1.51%   |
| 2 x Nvidia               | 14        | 0.48%   |
| Other                    | 5         | 0.17%   |
| Nvidia + ASPEED          | 3         | 0.1%    |
| 1 x ASPEED               | 3         | 0.1%    |
| Nvidia + Matrox          | 2         | 0.07%   |
| 1 x Matrox               | 2         | 0.07%   |
| 3 x Nvidia               | 1         | 0.03%   |
| 2 x Intel                | 1         | 0.03%   |
| 1 x Zhaoxin              | 1         | 0.03%   |
| 1 x SiS                  | 1         | 0.03%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.03%   |
| AMD + Matrox             | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 2106      | 71.71%  |
| Proprietary | 771       | 26.25%  |
| Unknown     | 60        | 2.04%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1528      | 51.38%  |
| 1.01-2.0   | 380       | 12.78%  |
| 0.01-0.5   | 258       | 8.68%   |
| 3.01-4.0   | 247       | 8.31%   |
| 0.51-1.0   | 240       | 8.07%   |
| 7.01-8.0   | 159       | 5.35%   |
| 5.01-6.0   | 92        | 3.09%   |
| 2.01-3.0   | 31        | 1.04%   |
| 8.01-16.0  | 31        | 1.04%   |
| 16.01-24.0 | 4         | 0.13%   |
| 4.01-5.0   | 3         | 0.1%    |
| 32.01-64.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 440       | 12.84%  |
| AU Optronics            | 377       | 11%     |
| LG Display              | 302       | 8.81%   |
| Chimei Innolux          | 279       | 8.14%   |
| BOE                     | 271       | 7.91%   |
| Dell                    | 230       | 6.71%   |
| Goldstar                | 186       | 5.43%   |
| Acer                    | 132       | 3.85%   |
| Hewlett-Packard         | 118       | 3.44%   |
| BenQ                    | 96        | 2.8%    |
| AOC                     | 88        | 2.57%   |
| Ancor Communications    | 86        | 2.51%   |
| Sharp                   | 84        | 2.45%   |
| Philips                 | 79        | 2.31%   |
| Lenovo                  | 49        | 1.43%   |
| ViewSonic               | 45        | 1.31%   |
| PANDA                   | 39        | 1.14%   |
| Iiyama                  | 39        | 1.14%   |
| Chi Mei Optoelectronics | 37        | 1.08%   |
| ASUSTek Computer        | 32        | 0.93%   |
| Apple                   | 30        | 0.88%   |
| LG Electronics          | 29        | 0.85%   |
| Unknown                 | 22        | 0.64%   |
| InfoVision              | 22        | 0.64%   |
| Sony                    | 20        | 0.58%   |
| Panasonic               | 17        | 0.5%    |
| NEC Computers           | 16        | 0.47%   |
| HannStar                | 11        | 0.32%   |
| Eizo                    | 11        | 0.32%   |
| MSI                     | 9         | 0.26%   |
| Medion                  | 9         | 0.26%   |
| CSO                     | 8         | 0.23%   |
| Vizio                   | 7         | 0.2%    |
| Toshiba                 | 7         | 0.2%    |
| Idek Iiyama             | 7         | 0.2%    |
| Vestel Elektronik       | 6         | 0.18%   |
| Sceptre Tech            | 6         | 0.18%   |
| LG Philips              | 5         | 0.15%   |
| Seiko/Epson             | 4         | 0.12%   |
| Gigabyte Technology     | 4         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 20        | 0.56%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 17        | 0.47%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 16        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 16        | 0.45%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch       | 15        | 0.42%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch               | 14        | 0.39%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch            | 13        | 0.36%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 11        | 0.31%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 11        | 0.31%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 11        | 0.31%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch          | 11        | 0.31%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                  | 9         | 0.25%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 8         | 0.22%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 8         | 0.22%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch      | 8         | 0.22%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch        | 8         | 0.22%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch         | 8         | 0.22%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch         | 8         | 0.22%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                | 7         | 0.2%    |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch           | 7         | 0.2%    |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch               | 7         | 0.2%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 7         | 0.2%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 7         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch       | 7         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch        | 7         | 0.2%    |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch       | 7         | 0.2%    |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch         | 7         | 0.2%    |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch         | 7         | 0.2%    |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 6         | 0.17%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 6         | 0.17%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch  | 6         | 0.17%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch  | 6         | 0.17%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 6         | 0.17%   |
| Panasonic VVX14P048M00 MEI96A2 3000x2000 285x190mm 13.5-inch           | 6         | 0.17%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch           | 6         | 0.17%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch            | 6         | 0.17%   |
| InfoVision LCD Monitor IVO057F 1920x1080 309x174mm 14.0-inch           | 6         | 0.17%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                  | 6         | 0.17%   |
| Dell U3415W DELA0A6 3440x1440 798x335mm 34.1-inch                      | 6         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch       | 6         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1557      | 48%     |
| 1366x768 (WXGA)    | 485       | 14.95%  |
| 3840x2160 (4K)     | 224       | 6.91%   |
| 2560x1440 (QHD)    | 161       | 4.96%   |
| 1600x900 (HD+)     | 119       | 3.67%   |
| 1920x1200 (WUXGA)  | 98        | 3.02%   |
| 1680x1050 (WSXGA+) | 79        | 2.44%   |
| 1280x1024 (SXGA)   | 73        | 2.25%   |
| Unknown            | 69        | 2.13%   |
| 1440x900 (WXGA+)   | 44        | 1.36%   |
| 2560x1080          | 36        | 1.11%   |
| 1280x800 (WXGA)    | 34        | 1.05%   |
| 3440x1440          | 32        | 0.99%   |
| 3840x1080          | 27        | 0.83%   |
| 1360x768           | 25        | 0.77%   |
| 2560x1600          | 20        | 0.62%   |
| 2880x1800          | 14        | 0.43%   |
| 2160x1440          | 14        | 0.43%   |
| 3840x2400          | 12        | 0.37%   |
| 1024x768 (XGA)     | 11        | 0.34%   |
| 3840x1200          | 9         | 0.28%   |
| 1920x540           | 9         | 0.28%   |
| 1600x1200          | 9         | 0.28%   |
| 3200x1800 (QHD+)   | 7         | 0.22%   |
| 4480x1440          | 6         | 0.18%   |
| 3840x1600          | 4         | 0.12%   |
| 1920x1280          | 4         | 0.12%   |
| 5760x1080          | 3         | 0.09%   |
| 3600x1080          | 3         | 0.09%   |
| 3456x2160          | 3         | 0.09%   |
| 3200x1080          | 3         | 0.09%   |
| 2736x1824          | 3         | 0.09%   |
| 2288x1287          | 3         | 0.09%   |
| 2240x1400          | 3         | 0.09%   |
| 1280x720 (HD)      | 3         | 0.09%   |
| 7680x2160          | 2         | 0.06%   |
| 5760x2160          | 2         | 0.06%   |
| 4480x1080          | 2         | 0.06%   |
| 3600x1200          | 2         | 0.06%   |
| 3072x1920          | 2         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 845       | 24.77%  |
| 27      | 289       | 8.47%   |
| 13      | 286       | 8.38%   |
| 24      | 284       | 8.32%   |
| 14      | 249       | 7.3%    |
| 23      | 241       | 7.06%   |
| Unknown | 212       | 6.21%   |
| 17      | 189       | 5.54%   |
| 21      | 187       | 5.48%   |
| 31      | 80        | 2.34%   |
| 19      | 69        | 2.02%   |
| 34      | 60        | 1.76%   |
| 22      | 52        | 1.52%   |
| 20      | 49        | 1.44%   |
| 12      | 44        | 1.29%   |
| 18      | 40        | 1.17%   |
| 11      | 36        | 1.06%   |
| 16      | 22        | 0.64%   |
| 84      | 21        | 0.62%   |
| 32      | 19        | 0.56%   |
| 25      | 16        | 0.47%   |
| 54      | 15        | 0.44%   |
| 72      | 14        | 0.41%   |
| 40      | 10        | 0.29%   |
| 26      | 7         | 0.21%   |
| 47      | 6         | 0.18%   |
| 46      | 6         | 0.18%   |
| 42      | 6         | 0.18%   |
| 48      | 5         | 0.15%   |
| 37      | 5         | 0.15%   |
| 28      | 5         | 0.15%   |
| 60      | 4         | 0.12%   |
| 52      | 4         | 0.12%   |
| 39      | 4         | 0.12%   |
| 10      | 4         | 0.12%   |
| 43      | 3         | 0.09%   |
| 36      | 3         | 0.09%   |
| 29      | 3         | 0.09%   |
| 142     | 2         | 0.06%   |
| 65      | 2         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1260      | 37.97%  |
| 501-600        | 731       | 22.03%  |
| 401-500        | 348       | 10.49%  |
| 351-400        | 223       | 6.72%   |
| 201-300        | 223       | 6.72%   |
| Unknown        | 212       | 6.39%   |
| 601-700        | 120       | 3.62%   |
| 701-800        | 83        | 2.5%    |
| 1001-1500      | 47        | 1.42%   |
| 1501-2000      | 37        | 1.12%   |
| 801-900        | 20        | 0.6%    |
| 901-1000       | 9         | 0.27%   |
| More than 2000 | 2         | 0.06%   |
| 1-100          | 2         | 0.06%   |
| 101-200        | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2280      | 76.28%  |
| 16/10   | 312       | 10.44%  |
| Unknown | 187       | 6.26%   |
| 5/4     | 71        | 2.38%   |
| 21/9    | 67        | 2.24%   |
| 3/2     | 30        | 1%      |
| 4/3     | 25        | 0.84%   |
| 32/9    | 8         | 0.27%   |
| 6/5     | 2         | 0.07%   |
| 1.96    | 2         | 0.07%   |
| 1.00    | 2         | 0.07%   |
| 1.98    | 1         | 0.03%   |
| 0.62    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 843       | 25.16%  |
| 201-250        | 571       | 17.04%  |
| 81-90          | 410       | 12.24%  |
| 301-350        | 294       | 8.78%   |
| Unknown        | 212       | 6.33%   |
| 151-200        | 171       | 5.1%    |
| 351-500        | 165       | 4.93%   |
| 121-130        | 136       | 4.06%   |
| 71-80          | 133       | 3.97%   |
| 251-300        | 112       | 3.34%   |
| More than 1000 | 68        | 2.03%   |
| 141-150        | 66        | 1.97%   |
| 501-1000       | 48        | 1.43%   |
| 61-70          | 36        | 1.07%   |
| 51-60          | 36        | 1.07%   |
| 131-140        | 18        | 0.54%   |
| 111-120        | 17        | 0.51%   |
| 91-100         | 7         | 0.21%   |
| 41-50          | 4         | 0.12%   |
| 1-40           | 3         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 1030      | 31.61%  |
| 121-160       | 932       | 28.61%  |
| 101-120       | 728       | 22.34%  |
| Unknown       | 212       | 6.51%   |
| 161-240       | 185       | 5.68%   |
| More than 240 | 98        | 3.01%   |
| 1-50          | 73        | 2.24%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2195      | 74.08%  |
| 2     | 621       | 20.96%  |
| 3     | 77        | 2.6%    |
| 0     | 63        | 2.13%   |
| 4     | 7         | 0.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1680      | 38.36%  |
| Intel                             | 1480      | 33.79%  |
| Qualcomm Atheros                  | 461       | 10.53%  |
| Broadcom                          | 185       | 4.22%   |
| Ralink Technology                 | 55        | 1.26%   |
| TP-Link                           | 50        | 1.14%   |
| Ralink                            | 40        | 0.91%   |
| MediaTek                          | 39        | 0.89%   |
| Broadcom Limited                  | 34        | 0.78%   |
| Nvidia                            | 27        | 0.62%   |
| Marvell Technology Group          | 25        | 0.57%   |
| Samsung Electronics               | 19        | 0.43%   |
| Qualcomm Atheros Communications   | 16        | 0.37%   |
| Microsoft                         | 16        | 0.37%   |
| Aquantia                          | 16        | 0.37%   |
| NetGear                           | 15        | 0.34%   |
| ASIX Electronics                  | 14        | 0.32%   |
| Xiaomi                            | 13        | 0.3%    |
| DisplayLink                       | 13        | 0.3%    |
| Qualcomm                          | 12        | 0.27%   |
| Huawei Technologies               | 12        | 0.27%   |
| Lenovo                            | 11        | 0.25%   |
| D-Link                            | 11        | 0.25%   |
| Dell                              | 10        | 0.23%   |
| Sierra Wireless                   | 9         | 0.21%   |
| Ericsson Business Mobile Networks | 9         | 0.21%   |
| Edimax Technology                 | 8         | 0.18%   |
| ASUSTek Computer                  | 7         | 0.16%   |
| Linksys                           | 6         | 0.14%   |
| JMicron Technology                | 6         | 0.14%   |
| D-Link System                     | 6         | 0.14%   |
| Apple                             | 6         | 0.14%   |
| FIBOCOM                           | 4         | 0.09%   |
| Belkin Components                 | 4         | 0.09%   |
| VIA Technologies                  | 3         | 0.07%   |
| T & A Mobile Phones               | 3         | 0.07%   |
| Google                            | 3         | 0.07%   |
| AVM                               | 3         | 0.07%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.05%   |
| Wacom                             | 2         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1196      | 23.36%  |
| Intel Wi-Fi 6 AX200                                               | 178       | 3.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 157       | 3.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 104       | 2.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 101       | 1.97%   |
| Intel Wireless 8265 / 8275                                        | 94        | 1.84%   |
| Intel I211 Gigabit Network Connection                             | 94        | 1.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 76        | 1.48%   |
| Intel Wi-Fi 6 AX201                                               | 76        | 1.48%   |
| Intel Wireless 7260                                               | 75        | 1.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 71        | 1.39%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 71        | 1.39%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 65        | 1.27%   |
| Realtek RTL8125 2.5GbE Controller                                 | 63        | 1.23%   |
| Intel Wireless 7265                                               | 61        | 1.19%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 59        | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 59        | 1.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 58        | 1.13%   |
| Intel Ethernet Connection (2) I219-V                              | 51        | 1%      |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 51        | 1%      |
| Intel Wireless 3165                                               | 48        | 0.94%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 47        | 0.92%   |
| Intel Wireless-AC 9260                                            | 45        | 0.88%   |
| Intel Ethernet Connection I217-LM                                 | 45        | 0.88%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 45        | 0.88%   |
| Intel Wireless 8260                                               | 39        | 0.76%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 38        | 0.74%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 33        | 0.64%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 32        | 0.63%   |
| Intel Ethernet Connection (7) I219-V                              | 32        | 0.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 30        | 0.59%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 29        | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 29        | 0.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 28        | 0.55%   |
| Intel Ethernet Connection (7) I219-LM                             | 27        | 0.53%   |
| Ralink MT7601U Wireless Adapter                                   | 26        | 0.51%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 25        | 0.49%   |
| Intel Ethernet Controller I225-V                                  | 25        | 0.49%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 23        | 0.45%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 23        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1138      | 48.67%  |
| Realtek Semiconductor                 | 375       | 16.04%  |
| Qualcomm Atheros                      | 360       | 15.4%   |
| Broadcom                              | 126       | 5.39%   |
| Ralink Technology                     | 55        | 2.35%   |
| TP-Link                               | 45        | 1.92%   |
| Ralink                                | 40        | 1.71%   |
| MediaTek                              | 35        | 1.5%    |
| Broadcom Limited                      | 28        | 1.2%    |
| Qualcomm Atheros Communications       | 16        | 0.68%   |
| NetGear                               | 15        | 0.64%   |
| Microsoft                             | 15        | 0.64%   |
| D-Link                                | 11        | 0.47%   |
| Sierra Wireless                       | 9         | 0.38%   |
| Edimax Technology                     | 8         | 0.34%   |
| Qualcomm                              | 7         | 0.3%    |
| ASUSTek Computer                      | 7         | 0.3%    |
| Linksys                               | 6         | 0.26%   |
| Marvell Technology Group              | 5         | 0.21%   |
| Dell                                  | 5         | 0.21%   |
| FIBOCOM                               | 4         | 0.17%   |
| D-Link System                         | 4         | 0.17%   |
| Belkin Components                     | 4         | 0.17%   |
| AVM                                   | 3         | 0.13%   |
| Wacom                                 | 2         | 0.09%   |
| Mercucys                              | 2         | 0.09%   |
| ZyXEL Communications                  | 1         | 0.04%   |
| ZyDAS                                 | 1         | 0.04%   |
| Wilocity                              | 1         | 0.04%   |
| Tenda                                 | 1         | 0.04%   |
| Sitecom Europe                        | 1         | 0.04%   |
| Philips (or NXP)                      | 1         | 0.04%   |
| Micro Star International              | 1         | 0.04%   |
| IMC Networks                          | 1         | 0.04%   |
| Guillemot                             | 1         | 0.04%   |
| Gemtek                                | 1         | 0.04%   |
| AirTies Wireless Networks             | 1         | 0.04%   |
| Accton Technology                     | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 178       | 7.56%   |
| Intel Wireless 8265 / 8275                                     | 94        | 3.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 76        | 3.23%   |
| Intel Wi-Fi 6 AX201                                            | 76        | 3.23%   |
| Intel Wireless 7260                                            | 75        | 3.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 71        | 3.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 71        | 3.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 65        | 2.76%   |
| Intel Wireless 7265                                            | 61        | 2.59%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 59        | 2.5%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 59        | 2.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 58        | 2.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 51        | 2.16%   |
| Intel Wireless 3165                                            | 48        | 2.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 47        | 1.99%   |
| Intel Wireless-AC 9260                                         | 45        | 1.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 45        | 1.91%   |
| Intel Wireless 8260                                            | 39        | 1.66%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 38        | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 33        | 1.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 32        | 1.36%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 30        | 1.27%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 29        | 1.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 29        | 1.23%   |
| Ralink MT7601U Wireless Adapter                                | 26        | 1.1%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 25        | 1.06%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 23        | 0.98%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 23        | 0.98%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 22        | 0.93%   |
| Intel Wireless 3160                                            | 22        | 0.93%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 21        | 0.89%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 19        | 0.81%   |
| Broadcom BCM43142 802.11b/g/n                                  | 19        | 0.81%   |
| Realtek 802.11ac NIC                                           | 18        | 0.76%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 17        | 0.72%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 17        | 0.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 16        | 0.68%   |
| Intel Centrino Advanced-N 6235                                 | 16        | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 15        | 0.64%   |
| Qualcomm Atheros AR9271 802.11n                                | 15        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 1523      | 57.36%  |
| Intel                            | 723       | 27.23%  |
| Qualcomm Atheros                 | 133       | 5.01%   |
| Broadcom                         | 73        | 2.75%   |
| Nvidia                           | 27        | 1.02%   |
| Marvell Technology Group         | 20        | 0.75%   |
| Samsung Electronics              | 19        | 0.72%   |
| Aquantia                         | 16        | 0.6%    |
| ASIX Electronics                 | 14        | 0.53%   |
| Xiaomi                           | 13        | 0.49%   |
| DisplayLink                      | 13        | 0.49%   |
| Lenovo                           | 11        | 0.41%   |
| Huawei Technologies              | 9         | 0.34%   |
| Broadcom Limited                 | 7         | 0.26%   |
| JMicron Technology               | 6         | 0.23%   |
| Apple                            | 6         | 0.23%   |
| TP-Link                          | 5         | 0.19%   |
| Qualcomm                         | 5         | 0.19%   |
| MediaTek                         | 4         | 0.15%   |
| VIA Technologies                 | 3         | 0.11%   |
| T & A Mobile Phones              | 3         | 0.11%   |
| Google                           | 3         | 0.11%   |
| ZTE WCDMA Technologies MSM       | 2         | 0.08%   |
| Silicon Integrated Systems [SiS] | 2         | 0.08%   |
| D-Link System                    | 2         | 0.08%   |
| 3Com                             | 2         | 0.08%   |
| QNAP System                      | 1         | 0.04%   |
| OnePlus                          | 1         | 0.04%   |
| Motorola PCS                     | 1         | 0.04%   |
| Motorola BCS                     | 1         | 0.04%   |
| Microsoft                        | 1         | 0.04%   |
| Mellanox Technologies            | 1         | 0.04%   |
| ICS Advent                       | 1         | 0.04%   |
| HMD Global                       | 1         | 0.04%   |
| Hewlett-Packard                  | 1         | 0.04%   |
| Elecom                           | 1         | 0.04%   |
| Davicom Semiconductor            | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1196      | 43.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 157       | 5.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 104       | 3.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 101       | 3.7%    |
| Intel I211 Gigabit Network Connection                             | 94        | 3.44%   |
| Realtek RTL8125 2.5GbE Controller                                 | 63        | 2.31%   |
| Intel Ethernet Connection (2) I219-V                              | 51        | 1.87%   |
| Intel Ethernet Connection I217-LM                                 | 45        | 1.65%   |
| Intel Ethernet Connection (7) I219-V                              | 32        | 1.17%   |
| Intel Ethernet Connection (4) I219-LM                             | 28        | 1.03%   |
| Intel Ethernet Connection (7) I219-LM                             | 27        | 0.99%   |
| Intel Ethernet Controller I225-V                                  | 25        | 0.92%   |
| Intel Ethernet Connection I218-LM                                 | 21        | 0.77%   |
| Intel 82579V Gigabit Network Connection                           | 21        | 0.77%   |
| Intel Ethernet Connection (2) I218-V                              | 20        | 0.73%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 19        | 0.7%    |
| Intel I210 Gigabit Network Connection                             | 18        | 0.66%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 17        | 0.62%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 17        | 0.62%   |
| Intel Ethernet Connection (6) I219-V                              | 17        | 0.62%   |
| Intel Ethernet Connection I219-LM                                 | 16        | 0.59%   |
| Intel 82574L Gigabit Network Connection                           | 16        | 0.59%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 15        | 0.55%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 15        | 0.55%   |
| Intel Ethernet Connection I217-V                                  | 15        | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                             | 15        | 0.55%   |
| Intel Ethernet Connection (2) I219-LM                             | 14        | 0.51%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 14        | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 13        | 0.48%   |
| ASIX AX88179 Gigabit Ethernet                                     | 13        | 0.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 12        | 0.44%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 12        | 0.44%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 0.44%   |
| Intel 82577LM Gigabit Network Connection                          | 12        | 0.44%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 12        | 0.44%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 11        | 0.4%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 10        | 0.37%   |
| Intel Ethernet Connection I219-V                                  | 10        | 0.37%   |
| Intel Ethernet Connection (13) I219-V                             | 10        | 0.37%   |
| Intel Ethernet Connection (10) I219-V                             | 10        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2486      | 52.38%  |
| WiFi     | 2227      | 46.92%  |
| Modem    | 31        | 0.65%   |
| Unknown  | 2         | 0.04%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1741      | 56.67%  |
| Ethernet | 1330      | 43.29%  |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1569      | 53.99%  |
| 1     | 1220      | 41.98%  |
| 3     | 61        | 2.1%    |
| 0     | 44        | 1.51%   |
| 4     | 9         | 0.31%   |
| 6     | 3         | 0.1%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 2474      | 84.06%  |
| Yes     | 468       | 15.9%   |
| Unknown | 1         | 0.03%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 963       | 49.95%  |
| Realtek Semiconductor           | 194       | 10.06%  |
| Qualcomm Atheros Communications | 159       | 8.25%   |
| Cambridge Silicon Radio         | 147       | 7.62%   |
| Broadcom                        | 103       | 5.34%   |
| IMC Networks                    | 68        | 3.53%   |
| Lite-On Technology              | 64        | 3.32%   |
| Foxconn / Hon Hai               | 45        | 2.33%   |
| ASUSTek Computer                | 31        | 1.61%   |
| Apple                           | 31        | 1.61%   |
| Dell                            | 28        | 1.45%   |
| Realtek                         | 19        | 0.99%   |
| Hewlett-Packard                 | 11        | 0.57%   |
| Toshiba                         | 10        | 0.52%   |
| Ralink                          | 10        | 0.52%   |
| Marvell Semiconductor           | 6         | 0.31%   |
| Foxconn International           | 6         | 0.31%   |
| Ralink Technology               | 5         | 0.26%   |
| Dynex                           | 4         | 0.21%   |
| TP-Link                         | 3         | 0.16%   |
| Edimax Technology               | 3         | 0.16%   |
| Alps Electric                   | 3         | 0.16%   |
| Unknown                         | 2         | 0.1%    |
| Taiyo Yuden                     | 2         | 0.1%    |
| Integrated System Solution      | 2         | 0.1%    |
| Belkin Components               | 2         | 0.1%    |
| Micro Star International        | 1         | 0.05%   |
| MediaTek                        | 1         | 0.05%   |
| Kensington                      | 1         | 0.05%   |
| D-Link                          | 1         | 0.05%   |
| Creative Technology             | 1         | 0.05%   |
| Corsair                         | 1         | 0.05%   |
| AboCom Systems                  | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 327       | 16.93%  |
| Intel AX201 Bluetooth                               | 176       | 9.11%   |
| Intel AX200 Bluetooth                               | 173       | 8.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 147       | 7.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 147       | 7.61%   |
| Realtek Bluetooth Radio                             | 110       | 5.7%    |
| Qualcomm Atheros  Bluetooth Device                  | 83        | 4.3%    |
| Realtek  Bluetooth 4.2 Adapter                      | 62        | 3.21%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 42        | 2.18%   |
| Intel Wireless-AC 3168 Bluetooth                    | 31        | 1.61%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 26        | 1.35%   |
| Lite-On Bluetooth Device                            | 25        | 1.29%   |
| IMC Networks Bluetooth Radio                        | 24        | 1.24%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 24        | 1.24%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 22        | 1.14%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 22        | 1.14%   |
| Realtek Bluetooth Radio                             | 19        | 0.98%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 17        | 0.88%   |
| IMC Networks Bluetooth Device                       | 17        | 0.88%   |
| Intel AX210 Bluetooth                               | 16        | 0.83%   |
| Foxconn / Hon Hai Bluetooth Device                  | 16        | 0.83%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 16        | 0.83%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 14        | 0.73%   |
| Intel Bluetooth Device                              | 13        | 0.67%   |
| Foxconn / Hon Hai Wireless_Device                   | 13        | 0.67%   |
| Broadcom BCM2045B (BDC-2.1)                         | 13        | 0.67%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 12        | 0.62%   |
| Apple Bluetooth USB Host Controller                 | 12        | 0.62%   |
| Apple Bluetooth Host Controller                     | 12        | 0.62%   |
| Realtek RTL8723B Bluetooth                          | 11        | 0.57%   |
| Dell BCM20702A0 Bluetooth Module                    | 11        | 0.57%   |
| Ralink RT3290 Bluetooth                             | 10        | 0.52%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 10        | 0.52%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 0.47%   |
| IMC Networks Wireless_Device                        | 9         | 0.47%   |
| Lite-On Atheros AR3012 Bluetooth                    | 8         | 0.41%   |
| Broadcom HP Portable SoftSailing                    | 8         | 0.41%   |
| ASUS ASUS USB-BT500                                 | 8         | 0.41%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 7         | 0.36%   |
| IMC Networks Bluetooth USB Host Controller          | 7         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 2040      | 47.76%  |
| AMD                        | 942       | 22.06%  |
| Nvidia                     | 777       | 18.19%  |
| C-Media Electronics        | 79        | 1.85%   |
| Logitech                   | 34        | 0.8%    |
| Creative Labs              | 33        | 0.77%   |
| GN Netcom                  | 30        | 0.7%    |
| Realtek Semiconductor      | 23        | 0.54%   |
| JMTek                      | 23        | 0.54%   |
| Texas Instruments          | 17        | 0.4%    |
| Creative Technology        | 14        | 0.33%   |
| Corsair                    | 14        | 0.33%   |
| Plantronics                | 13        | 0.3%    |
| Generalplus Technology     | 13        | 0.3%    |
| ASUSTek Computer           | 13        | 0.3%    |
| Razer USA                  | 12        | 0.28%   |
| Lenovo                     | 9         | 0.21%   |
| Kingston Technology        | 8         | 0.19%   |
| Focusrite-Novation         | 8         | 0.19%   |
| SteelSeries ApS            | 7         | 0.16%   |
| Hewlett-Packard            | 7         | 0.16%   |
| VIA Technologies           | 6         | 0.14%   |
| Tenx Technology            | 6         | 0.14%   |
| Sony                       | 6         | 0.14%   |
| Blue Microphones           | 6         | 0.14%   |
| Dell                       | 5         | 0.12%   |
| Yamaha                     | 4         | 0.09%   |
| Sennheiser Communications  | 4         | 0.09%   |
| SAVITECH                   | 4         | 0.09%   |
| ZOOM                       | 3         | 0.07%   |
| TerraTec Electronic        | 3         | 0.07%   |
| RODE Microphones           | 3         | 0.07%   |
| QinHeng Electronics        | 3         | 0.07%   |
| PreSonus Audio Electronics | 3         | 0.07%   |
| GYROCOM C&C                | 3         | 0.07%   |
| CMX Systems                | 3         | 0.07%   |
| Best Buy                   | 3         | 0.07%   |
| BEHRINGER International    | 3         | 0.07%   |
| XMOS                       | 2         | 0.05%   |
| Unknown                    | 2         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 282       | 5.54%   |
| Intel Sunrise Point-LP HD Audio                                            | 232       | 4.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 186       | 3.66%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 170       | 3.34%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 165       | 3.24%   |
| AMD Starship/Matisse HD Audio Controller                                   | 152       | 2.99%   |
| Intel Cannon Lake PCH cAVS                                                 | 151       | 2.97%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 132       | 2.59%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 130       | 2.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 116       | 2.28%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 107       | 2.1%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 107       | 2.1%    |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 94        | 1.85%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 94        | 1.85%   |
| Nvidia GP107GL High Definition Audio Controller                            | 93        | 1.83%   |
| AMD FCH Azalia Controller                                                  | 87        | 1.71%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 85        | 1.67%   |
| Intel Haswell-ULT HD Audio Controller                                      | 84        | 1.65%   |
| Intel 8 Series HD Audio Controller                                         | 83        | 1.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 69        | 1.36%   |
| Intel Comet Lake PCH-LP cAVS                                               | 66        | 1.3%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 66        | 1.3%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 62        | 1.22%   |
| Nvidia TU116 High Definition Audio Controller                              | 56        | 1.1%    |
| Intel 200 Series PCH HD Audio                                              | 55        | 1.08%   |
| Intel Comet Lake PCH cAVS                                                  | 54        | 1.06%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 51        | 1%      |
| Nvidia GP106 High Definition Audio Controller                              | 51        | 1%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 51        | 1%      |
| Nvidia TU106 High Definition Audio Controller                              | 48        | 0.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 48        | 0.94%   |
| Intel Broadwell-U Audio Controller                                         | 48        | 0.94%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 47        | 0.92%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 46        | 0.9%    |
| Nvidia GP104 High Definition Audio Controller                              | 41        | 0.81%   |
| Nvidia GF108 High Definition Audio Controller                              | 40        | 0.79%   |
| AMD Kabini HDMI/DP Audio                                                   | 40        | 0.79%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 37        | 0.73%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 35        | 0.69%   |
| Intel CM238 HD Audio Controller                                            | 35        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 469       | 21.82%  |
| SK hynix            | 347       | 16.15%  |
| Kingston            | 286       | 13.31%  |
| Micron Technology   | 203       | 9.45%   |
| Unknown             | 161       | 7.49%   |
| Crucial             | 150       | 6.98%   |
| Corsair             | 139       | 6.47%   |
| G.Skill             | 101       | 4.7%    |
| A-DATA Technology   | 40        | 1.86%   |
| Ramaxel Technology  | 31        | 1.44%   |
| Elpida              | 28        | 1.3%    |
| Nanya Technology    | 25        | 1.16%   |
| Unknown (ABCD)      | 21        | 0.98%   |
| Team                | 17        | 0.79%   |
| Patriot             | 15        | 0.7%    |
| Transcend           | 12        | 0.56%   |
| Smart               | 12        | 0.56%   |
| Unknown             | 10        | 0.47%   |
| GOODRAM             | 7         | 0.33%   |
| AMD                 | 6         | 0.28%   |
| Smart Brazil        | 5         | 0.23%   |
| Silicon Power       | 5         | 0.23%   |
| Apacer              | 5         | 0.23%   |
| Teikon              | 4         | 0.19%   |
| Wilk                | 3         | 0.14%   |
| ASint Technology    | 3         | 0.14%   |
| SHARETRONIC         | 2         | 0.09%   |
| Reboto              | 2         | 0.09%   |
| Kllisre             | 2         | 0.09%   |
| Kingmax             | 2         | 0.09%   |
| Hewlett-Packard     | 2         | 0.09%   |
| GLOWAY              | 2         | 0.09%   |
| GeIL                | 2         | 0.09%   |
| CSX                 | 2         | 0.09%   |
| Avant               | 2         | 0.09%   |
| Atermiter           | 2         | 0.09%   |
| V-GeN               | 1         | 0.05%   |
| V-Color             | 1         | 0.05%   |
| Unknown (8A02)      | 1         | 0.05%   |
| Unknown (82B5)      | 1         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 24        | 1.03%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 22        | 0.95%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 21        | 0.9%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 18        | 0.77%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 18        | 0.77%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 16        | 0.69%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 0.65%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 15        | 0.65%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 15        | 0.65%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 14        | 0.6%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 14        | 0.6%    |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 13        | 0.56%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 13        | 0.56%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 13        | 0.56%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 12        | 0.52%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 12        | 0.52%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 12        | 0.52%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 11        | 0.47%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 11        | 0.47%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 11        | 0.47%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 11        | 0.47%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 10        | 0.43%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 10        | 0.43%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 10        | 0.43%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.43%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 10        | 0.43%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 10        | 0.43%   |
| Unknown                                                          | 10        | 0.43%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 9         | 0.39%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 9         | 0.39%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 9         | 0.39%   |
| Kingston RAM KHX2666C15S4/16G 16GB SODIMM DDR4 2667MT/s          | 9         | 0.39%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 8         | 0.34%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s        | 8         | 0.34%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.34%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.34%   |
| Samsung RAM M471A2G44AM0-CWE 16384MB SODIMM DDR4 3200MT/s        | 8         | 0.34%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.3%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.3%    |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 7         | 0.3%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1047      | 56.59%  |
| DDR3    | 551       | 29.78%  |
| LPDDR4  | 67        | 3.62%   |
| Unknown | 51        | 2.76%   |
| DDR2    | 45        | 2.43%   |
| LPDDR3  | 44        | 2.38%   |
| SDRAM   | 28        | 1.51%   |
| DDR5    | 6         | 0.32%   |
| DDR     | 6         | 0.32%   |
| LPDDR5  | 4         | 0.22%   |
| DRAM    | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 1057      | 57.04%  |
| DIMM         | 654       | 35.29%  |
| Row Of Chips | 121       | 6.53%   |
| Chip         | 11        | 0.59%   |
| Unknown      | 5         | 0.27%   |
| FB-DIMM      | 3         | 0.16%   |
| RIMM         | 2         | 0.11%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 844       | 41.84%  |
| 4096  | 550       | 27.27%  |
| 16384 | 358       | 17.75%  |
| 2048  | 184       | 9.12%   |
| 32768 | 51        | 2.53%   |
| 1024  | 27        | 1.34%   |
| 512   | 1         | 0.05%   |
| 256   | 1         | 0.05%   |
| 128   | 1         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 379       | 18.9%   |
| 1600    | 379       | 18.9%   |
| 3200    | 306       | 15.26%  |
| 2400    | 174       | 8.68%   |
| 1333    | 126       | 6.28%   |
| 2133    | 109       | 5.44%   |
| 3600    | 72        | 3.59%   |
| 1334    | 51        | 2.54%   |
| 800     | 32        | 1.6%    |
| 4267    | 30        | 1.5%    |
| 1867    | 27        | 1.35%   |
| 667     | 25        | 1.25%   |
| 2666    | 22        | 1.1%    |
| 3000    | 21        | 1.05%   |
| Unknown | 19        | 0.95%   |
| 3400    | 18        | 0.9%    |
| 3266    | 18        | 0.9%    |
| 1067    | 14        | 0.7%    |
| 3733    | 13        | 0.65%   |
| 8400    | 12        | 0.6%    |
| 1066    | 12        | 0.6%    |
| 3800    | 10        | 0.5%    |
| 3466    | 10        | 0.5%    |
| 2933    | 10        | 0.5%    |
| 3866    | 9         | 0.45%   |
| 1866    | 9         | 0.45%   |
| 4199    | 7         | 0.35%   |
| 2800    | 7         | 0.35%   |
| 4800    | 6         | 0.3%    |
| 400     | 6         | 0.3%    |
| 4266    | 5         | 0.25%   |
| 3333    | 5         | 0.25%   |
| 3066    | 5         | 0.25%   |
| 2048    | 5         | 0.25%   |
| 1800    | 5         | 0.25%   |
| 6400    | 4         | 0.2%    |
| 3151    | 4         | 0.2%    |
| 2000    | 4         | 0.2%    |
| 975     | 3         | 0.15%   |
| 533     | 3         | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 41        | 42.27%  |
| Brother Industries     | 21        | 21.65%  |
| Samsung Electronics    | 9         | 9.28%   |
| Seiko Epson            | 8         | 8.25%   |
| Canon                  | 8         | 8.25%   |
| Xerox                  | 2         | 2.06%   |
| Zebra                  | 1         | 1.03%   |
| SAT                    | 1         | 1.03%   |
| Prolific Technology    | 1         | 1.03%   |
| Pantum                 | 1         | 1.03%   |
| Panasonic (Matsushita) | 1         | 1.03%   |
| ICS Advent             | 1         | 1.03%   |
| Datamax-O'Neil         | 1         | 1.03%   |
| Apple                  | 1         | 1.03%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| HP OfficeJet Pro 8020 series                           | 3         | 3.03%   |
| Seiko Epson L3110 Series                               | 2         | 2.02%   |
| HP OfficeJet Pro 7740 series                           | 2         | 2.02%   |
| HP LaserJet 1018                                       | 2         | 2.02%   |
| HP ENVY 4500 series                                    | 2         | 2.02%   |
| HP DeskJet 2620 All-in-One Printer                     | 2         | 2.02%   |
| Brother HL-2230 series                                 | 2         | 2.02%   |
| Zebra ZTC LP2844-Z-200dpi                              | 1         | 1.01%   |
| Xerox Phaser 6500DN                                    | 1         | 1.01%   |
| Xerox Phaser 3140 and 3155                             | 1         | 1.01%   |
| Seiko Epson WF-2530 Series                             | 1         | 1.01%   |
| Seiko Epson Printer                                    | 1         | 1.01%   |
| Seiko Epson ME Office 600F/Stylus Office BX300F/TX300F | 1         | 1.01%   |
| Seiko Epson L222 Series                                | 1         | 1.01%   |
| Seiko Epson L120 Series                                | 1         | 1.01%   |
| Seiko Epson ET-2710 Series                             | 1         | 1.01%   |
| SAT SAT38TUSE                                          | 1         | 1.01%   |
| Samsung Xerox Phaser 3117 Laser Printer                | 1         | 1.01%   |
| Samsung SCX-3200 Series                                | 1         | 1.01%   |
| Samsung ML-2250 Series                                 | 1         | 1.01%   |
| Samsung ML-216x Series Laser Printer                   | 1         | 1.01%   |
| Samsung M262x/M282x Xpress Series Laser Printer        | 1         | 1.01%   |
| Samsung M2070 Series                                   | 1         | 1.01%   |
| Samsung CLX-3180 Series                                | 1         | 1.01%   |
| Samsung CLX-3170 Series                                | 1         | 1.01%   |
| Samsung CLP-360 Series                                 | 1         | 1.01%   |
| Prolific PL2305 Parallel Port                          | 1         | 1.01%   |
| Pantum P2200 series                                    | 1         | 1.01%   |
| Panasonic (Matsushita) KX-MB1520G                      | 1         | 1.01%   |
| ICS Advent Parallel Adapter                            | 1         | 1.01%   |
| HP OfficeJet Pro 9010 series                           | 1         | 1.01%   |
| HP OfficeJet 9010 series                               | 1         | 1.01%   |
| HP OfficeJet 5500 series                               | 1         | 1.01%   |
| HP OfficeJet 4650 series                               | 1         | 1.01%   |
| HP Officejet 4630 series                               | 1         | 1.01%   |
| HP OfficeJet 3830 series                               | 1         | 1.01%   |
| HP LaserJet Pro M202dw                                 | 1         | 1.01%   |
| HP LaserJet P2055 series                               | 1         | 1.01%   |
| HP LaserJet P2035                                      | 1         | 1.01%   |
| HP LaserJet P2015 series                               | 1         | 1.01%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 10        | 47.62%  |
| Seiko Epson     | 5         | 23.81%  |
| Mustek Systems  | 3         | 14.29%  |
| Hewlett-Packard | 3         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 2         | 9.52%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 2         | 9.52%   |
| Canon CanoScan LiDE 220                                 | 2         | 9.52%   |
| Canon CanoScan LiDE 110                                 | 2         | 9.52%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]             | 1         | 4.76%   |
| Seiko Epson GT-X770 [Perfection V500]                   | 1         | 4.76%   |
| Seiko Epson ES-D200 [GT-S50]                            | 1         | 4.76%   |
| Mustek Systems SNAPSCAN e22                             | 1         | 4.76%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO              | 1         | 4.76%   |
| Mustek Systems BearPaw 1200 CU Plus                     | 1         | 4.76%   |
| HP ScanJet G4010                                        | 1         | 4.76%   |
| HP ScanJet 82x0C                                        | 1         | 4.76%   |
| HP ScanJet 3770                                         | 1         | 4.76%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                  | 1         | 4.76%   |
| Canon CanoScan LIDE 25                                  | 1         | 4.76%   |
| Canon CanoScan LiDE 210                                 | 1         | 4.76%   |
| Canon CanoScan LiDE 120                                 | 1         | 4.76%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 377       | 19.44%  |
| IMC Networks                           | 185       | 9.54%   |
| Microdia                               | 180       | 9.28%   |
| Acer                                   | 158       | 8.15%   |
| Logitech                               | 156       | 8.05%   |
| Realtek Semiconductor                  | 151       | 7.79%   |
| Sunplus Innovation Technology          | 96        | 4.95%   |
| Quanta                                 | 87        | 4.49%   |
| Cheng Uei Precision Industry (Foxlink) | 77        | 3.97%   |
| Suyin                                  | 39        | 2.01%   |
| Silicon Motion                         | 39        | 2.01%   |
| Syntek                                 | 36        | 1.86%   |
| Lite-On Technology                     | 34        | 1.75%   |
| Apple                                  | 31        | 1.6%    |
| Luxvisions Innotech Limited            | 30        | 1.55%   |
| Microsoft                              | 29        | 1.5%    |
| Alcor Micro                            | 25        | 1.29%   |
| Samsung Electronics                    | 20        | 1.03%   |
| Ricoh                                  | 15        | 0.77%   |
| Z-Star Microelectronics                | 12        | 0.62%   |
| Generalplus Technology                 | 12        | 0.62%   |
| Lenovo                                 | 11        | 0.57%   |
| KYE Systems (Mouse Systems)            | 8         | 0.41%   |
| Genesys Logic                          | 8         | 0.41%   |
| SunplusIT                              | 6         | 0.31%   |
| Sunplus Technology                     | 6         | 0.31%   |
| MacroSilicon                           | 6         | 0.31%   |
| Huawei Technologies                    | 6         | 0.31%   |
| Cubeternet                             | 6         | 0.31%   |
| ARC International                      | 6         | 0.31%   |
| Importek                               | 5         | 0.26%   |
| Y Media                                | 4         | 0.21%   |
| Unknown                                | 4         | 0.21%   |
| Sonix Technology                       | 4         | 0.21%   |
| Intel                                  | 4         | 0.21%   |
| Creative Technology                    | 4         | 0.21%   |
| Razer USA                              | 3         | 0.15%   |
| Novatek Microelectronics               | 3         | 0.15%   |
| LG Electronics                         | 3         | 0.15%   |
| Jieli Technology                       | 3         | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 79        | 4.03%   |
| Microdia Integrated_Webcam_HD                                   | 74        | 3.77%   |
| Realtek Integrated_Webcam_HD                                    | 67        | 3.42%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 56        | 2.86%   |
| IMC Networks Integrated Camera                                  | 54        | 2.75%   |
| Acer Integrated Camera                                          | 53        | 2.7%    |
| Sunplus Integrated_Webcam_HD                                    | 41        | 2.09%   |
| Chicony HD WebCam                                               | 40        | 2.04%   |
| Logitech HD Pro Webcam C920                                     | 33        | 1.68%   |
| Logitech Webcam C270                                            | 32        | 1.63%   |
| Chicony USB2.0 Camera                                           | 27        | 1.38%   |
| Chicony HP HD Camera                                            | 26        | 1.33%   |
| Syntek Integrated Camera                                        | 25        | 1.27%   |
| Acer Lenovo EasyCamera                                          | 22        | 1.12%   |
| Microdia Integrated Webcam                                      | 21        | 1.07%   |
| Samsung Galaxy series, misc. (MTP mode)                         | 19        | 0.97%   |
| Chicony HD User Facing                                          | 18        | 0.92%   |
| Quanta HD User Facing                                           | 17        | 0.87%   |
| Microdia Webcam Vitade AF                                       | 17        | 0.87%   |
| Acer HD Webcam                                                  | 16        | 0.82%   |
| Lite-On Integrated Camera                                       | 15        | 0.76%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 14        | 0.71%   |
| Acer BisonCam, NB Pro                                           | 14        | 0.71%   |
| Quanta HP HD Camera                                             | 13        | 0.66%   |
| IMC Networks USB2.0 VGA UVC WebCam                              | 13        | 0.66%   |
| Chicony Integrated Camera (1280x720@30)                         | 13        | 0.66%   |
| Chicony HP Wide Vision HD Camera                                | 13        | 0.66%   |
| Chicony HP TrueVision HD                                        | 13        | 0.66%   |
| Apple iPhone 5/5C/5S/6/SE                                       | 13        | 0.66%   |
| Quanta HP TrueVision HD Camera                                  | 12        | 0.61%   |
| Chicony USB 2.0 Camera                                          | 12        | 0.61%   |
| Realtek Integrated Webcam HD                                    | 11        | 0.56%   |
| Microsoft LifeCam HD-3000                                       | 11        | 0.56%   |
| Quanta HD Webcam                                                | 10        | 0.51%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 10        | 0.51%   |
| Luxvisions Innotech Limited HP HD Camera                        | 10        | 0.51%   |
| IMC Networks HD Camera                                          | 10        | 0.51%   |
| Chicony HP TrueVision HD Camera                                 | 10        | 0.51%   |
| Realtek Integrated Webcam                                       | 9         | 0.46%   |
| Quanta HP Webcam                                                | 9         | 0.46%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 130       | 32.58%  |
| Validity Sensors           | 104       | 26.07%  |
| Shenzhen Goodix Technology | 77        | 19.3%   |
| Elan Microelectronics      | 29        | 7.27%   |
| AuthenTec                  | 20        | 5.01%   |
| Upek                       | 16        | 4.01%   |
| LighTuning Technology      | 15        | 3.76%   |
| STMicroelectronics         | 6         | 1.5%    |
| Focal-systems.Corp         | 1         | 0.25%   |
| DigitalPersona             | 1         | 0.25%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 46        | 11.53%  |
| Shenzhen Goodix  FingerPrint Device                                        | 40        | 10.03%  |
| Unknown                                                                    | 34        | 8.52%   |
| Shenzhen Goodix Fingerprint Reader                                         | 22        | 5.51%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 17        | 4.26%   |
| Elan ELAN:Fingerprint                                                      | 17        | 4.26%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 16        | 4.01%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 16        | 4.01%   |
| Shenzhen Goodix FingerPrint                                                | 15        | 3.76%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 13        | 3.26%   |
| Synaptics  WBDI                                                            | 11        | 2.76%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 10        | 2.51%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 10        | 2.51%   |
| Elan ELAN:ARM-M4                                                           | 10        | 2.51%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 2.26%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 2.26%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 9         | 2.26%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 8         | 2.01%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 8         | 2.01%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 7         | 1.75%   |
| AuthenTec AES2810                                                          | 7         | 1.75%   |
| Validity Sensors Fingerprint scanner                                       | 6         | 1.5%    |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.5%    |
| LighTuning EgisTec_ES603                                                   | 5         | 1.25%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.25%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 4         | 1%      |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 4         | 1%      |
| Validity Sensors VFS491                                                    | 4         | 1%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 4         | 1%      |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1%      |
| AuthenTec Fingerprint Sensor                                               | 4         | 1%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.75%   |
| Synaptics WBDI Device                                                      | 2         | 0.5%    |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 2         | 0.5%    |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.5%    |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.5%    |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.25%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.25%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.25%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.25%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 72        | 41.38%  |
| Alcor Micro               | 47        | 27.01%  |
| Upek                      | 11        | 6.32%   |
| O2 Micro                  | 8         | 4.6%    |
| Lenovo                    | 6         | 3.45%   |
| Advanced Card Systems     | 4         | 2.3%    |
| SCM Microsystems          | 3         | 1.72%   |
| Gemalto (was Gemplus)     | 3         | 1.72%   |
| Yubico.com                | 2         | 1.15%   |
| Reiner SCT Kartensysteme  | 2         | 1.15%   |
| Realtek Semiconductor     | 2         | 1.15%   |
| OmniKey                   | 2         | 1.15%   |
| Fujitsu Siemens Computers | 2         | 1.15%   |
| BIT4ID                    | 2         | 1.15%   |
| Watchdata                 | 1         | 0.57%   |
| In Focus Systems          | 1         | 0.57%   |
| Giesecke & Devrient       | 1         | 0.57%   |
| Clay Logic                | 1         | 0.57%   |
| Chicony Electronics       | 1         | 0.57%   |
| Aladdin R.D.              | 1         | 0.57%   |
| Aladdin Knowledge Systems | 1         | 0.57%   |
| Aktiv                     | 1         | 0.57%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 45        | 25.86%  |
| Broadcom 5880                                                                | 21        | 12.07%  |
| Broadcom BCM5880 Secure Applications Processor                               | 19        | 10.92%  |
| Broadcom 58200                                                               | 18        | 10.34%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 12        | 6.9%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 11        | 6.32%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 8         | 4.6%    |
| Lenovo Integrated Smart Card Reader                                          | 6         | 3.45%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 4         | 2.3%    |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 3         | 1.72%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 2         | 1.15%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.15%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 1.15%   |
| BIT4ID miniLector EVO                                                        | 2         | 1.15%   |
| Alcor Micro Watchdata W 1981                                                 | 2         | 1.15%   |
| Watchdata USB Key                                                            | 1         | 0.57%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.57%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.57%   |
| SCM Microsystems SCR331 SmartCard Reader                                     | 1         | 0.57%   |
| Reiner SCT Kartensysteme tanJack USB                                         | 1         | 0.57%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 1         | 0.57%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.57%   |
| OmniKey CardMan 1021                                                         | 1         | 0.57%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.57%   |
| Giesecke & Devrient StarSign CUT                                             | 1         | 0.57%   |
| Fujitsu Siemens Computers Smartcard Reader D323                              | 1         | 0.57%   |
| Fujitsu Siemens Computers Keyboard KB SCR                                    | 1         | 0.57%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.57%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.57%   |
| Aladdin R.D. JaCarta                                                         | 1         | 0.57%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.57%   |
| Aktiv Rutoken lite                                                           | 1         | 0.57%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2033      | 68.82%  |
| 1     | 741       | 25.08%  |
| 2     | 146       | 4.94%   |
| 3     | 15        | 0.51%   |
| 4     | 8         | 0.27%   |
| 6     | 4         | 0.14%   |
| 7     | 3         | 0.1%    |
| 5     | 3         | 0.1%    |
| 9     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 393       | 35.22%  |
| Graphics card            | 181       | 16.22%  |
| Chipcard                 | 149       | 13.35%  |
| Net/wireless             | 129       | 11.56%  |
| Multimedia controller    | 44        | 3.94%   |
| Camera                   | 41        | 3.67%   |
| Sound                    | 36        | 3.23%   |
| Bluetooth                | 32        | 2.87%   |
| Communication controller | 31        | 2.78%   |
| Unassigned class         | 27        | 2.42%   |
| Card reader              | 16        | 1.43%   |
| Storage                  | 13        | 1.16%   |
| Network                  | 6         | 0.54%   |
| Net/ethernet             | 6         | 0.54%   |
| Storage/ide              | 4         | 0.36%   |
| Modem                    | 3         | 0.27%   |
| Firewire controller      | 3         | 0.27%   |
| Dvb card                 | 2         | 0.18%   |

