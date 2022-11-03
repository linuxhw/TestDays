Kubuntu 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Kubuntu 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Kubuntu_22.04/Desktop/README.md) and [notebooks](/Dist/Kubuntu_22.04/Notebook/README.md).

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

Total: 531

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad T440p 20AW000GU... | Notebook    | [b4ff1758e9](https://linux-hardware.org/?probe=b4ff1758e9) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | Notebook    | [623af75bb3](https://linux-hardware.org/?probe=623af75bb3) | Nov 02, 2022 |
| Panasonic     | CF-31WBLEHLM                | Notebook    | [52e7c62bae](https://linux-hardware.org/?probe=52e7c62bae) | Nov 02, 2022 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [50bd7a7436](https://linux-hardware.org/?probe=50bd7a7436) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [fefe8e5d04](https://linux-hardware.org/?probe=fefe8e5d04) | Nov 01, 2022 |
| Lenovo        | IdeaPad 720S-13ARR 81BR     | Notebook    | [df949b6e10](https://linux-hardware.org/?probe=df949b6e10) | Nov 01, 2022 |
| Shuttle       | FH61R                       | Desktop     | [26f86947ef](https://linux-hardware.org/?probe=26f86947ef) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U8S... | Notebook    | [4b778e52ee](https://linux-hardware.org/?probe=4b778e52ee) | Oct 30, 2022 |
| ASUSTek       | Zephyrus S GX502GW_GX502... | Notebook    | [c3f344809a](https://linux-hardware.org/?probe=c3f344809a) | Oct 30, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [418b143f46](https://linux-hardware.org/?probe=418b143f46) | Oct 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [293877c614](https://linux-hardware.org/?probe=293877c614) | Oct 29, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [aea626acae](https://linux-hardware.org/?probe=aea626acae) | Oct 29, 2022 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [5bd4292187](https://linux-hardware.org/?probe=5bd4292187) | Oct 29, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [91f0c87afa](https://linux-hardware.org/?probe=91f0c87afa) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d7491bf8e7](https://linux-hardware.org/?probe=d7491bf8e7) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [6bdf703faf](https://linux-hardware.org/?probe=6bdf703faf) | Oct 29, 2022 |
| ASRock        | H61M-VS                     | Desktop     | [9a48b2a679](https://linux-hardware.org/?probe=9a48b2a679) | Oct 28, 2022 |
| Dell          | Latitude 5521               | Notebook    | [460057b367](https://linux-hardware.org/?probe=460057b367) | Oct 28, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [a2d71fd3ca](https://linux-hardware.org/?probe=a2d71fd3ca) | Oct 28, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [ac3b0eaf36](https://linux-hardware.org/?probe=ac3b0eaf36) | Oct 28, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ba5aec702a](https://linux-hardware.org/?probe=ba5aec702a) | Oct 27, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [c0cebe4cfe](https://linux-hardware.org/?probe=c0cebe4cfe) | Oct 27, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [a5c5f0ec1e](https://linux-hardware.org/?probe=a5c5f0ec1e) | Oct 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ed392a140d](https://linux-hardware.org/?probe=ed392a140d) | Oct 27, 2022 |
| HP            | G62                         | Notebook    | [c9ba156401](https://linux-hardware.org/?probe=c9ba156401) | Oct 27, 2022 |
| HP            | 844C                        | Desktop     | [7e994c50c9](https://linux-hardware.org/?probe=7e994c50c9) | Oct 27, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [a308f68bce](https://linux-hardware.org/?probe=a308f68bce) | Oct 27, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [0763832411](https://linux-hardware.org/?probe=0763832411) | Oct 27, 2022 |
| ASUSTek       | M5A78L-M LE                 | Desktop     | [6954f669c5](https://linux-hardware.org/?probe=6954f669c5) | Oct 27, 2022 |
| Notebook      | PD5x_7xPNP_PNR_PNN_PNT      | Notebook    | [93229f0fab](https://linux-hardware.org/?probe=93229f0fab) | Oct 26, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [7910e04e13](https://linux-hardware.org/?probe=7910e04e13) | Oct 25, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [2920658e38](https://linux-hardware.org/?probe=2920658e38) | Oct 25, 2022 |
| Samsung       | 767XCL                      | Notebook    | [17bd1b4506](https://linux-hardware.org/?probe=17bd1b4506) | Oct 25, 2022 |
| HP            | Pavilion g6                 | Notebook    | [448d52b32f](https://linux-hardware.org/?probe=448d52b32f) | Oct 25, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [bd3a8063b3](https://linux-hardware.org/?probe=bd3a8063b3) | Oct 25, 2022 |
| Sony          | VAIO                        | All in one  | [27e76b1c76](https://linux-hardware.org/?probe=27e76b1c76) | Oct 25, 2022 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [285e8cd1a5](https://linux-hardware.org/?probe=285e8cd1a5) | Oct 25, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [cfb2e32cea](https://linux-hardware.org/?probe=cfb2e32cea) | Oct 25, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [fe222419ec](https://linux-hardware.org/?probe=fe222419ec) | Oct 25, 2022 |
| Acer          | Nitro AN517-51              | Notebook    | [7fed0ea2a9](https://linux-hardware.org/?probe=7fed0ea2a9) | Oct 24, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [37fc32cacd](https://linux-hardware.org/?probe=37fc32cacd) | Oct 24, 2022 |
| Gigabyte      | B365M D2V                   | Desktop     | [c852b8f3f7](https://linux-hardware.org/?probe=c852b8f3f7) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [638c72b105](https://linux-hardware.org/?probe=638c72b105) | Oct 24, 2022 |
| Lenovo        | ThinkPad P73 20QRS00100     | Notebook    | [532b112928](https://linux-hardware.org/?probe=532b112928) | Oct 24, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [918b0ef1ab](https://linux-hardware.org/?probe=918b0ef1ab) | Oct 24, 2022 |
| HP            | Laptop 17-by0xxx            | Notebook    | [faedd5a008](https://linux-hardware.org/?probe=faedd5a008) | Oct 24, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [13c917aa38](https://linux-hardware.org/?probe=13c917aa38) | Oct 23, 2022 |
| ASUSTek       | STRIX Z270E GAMING          | Desktop     | [ca0e86eb6b](https://linux-hardware.org/?probe=ca0e86eb6b) | Oct 22, 2022 |
| Dell          | Latitude 7390               | Notebook    | [71f8a9e59b](https://linux-hardware.org/?probe=71f8a9e59b) | Oct 22, 2022 |
| Acer          | Predator PT516-52s          | Notebook    | [ec8dac6fd3](https://linux-hardware.org/?probe=ec8dac6fd3) | Oct 22, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [b438a2ba8f](https://linux-hardware.org/?probe=b438a2ba8f) | Oct 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [a8c892608e](https://linux-hardware.org/?probe=a8c892608e) | Oct 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [20f991643f](https://linux-hardware.org/?probe=20f991643f) | Oct 21, 2022 |
| HP            | Laptop 17-by4xxx            | Notebook    | [6090ec7241](https://linux-hardware.org/?probe=6090ec7241) | Oct 21, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [0cf70c348b](https://linux-hardware.org/?probe=0cf70c348b) | Oct 21, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [c8e47b28fe](https://linux-hardware.org/?probe=c8e47b28fe) | Oct 20, 2022 |
| MSI           | A320M PRO-M2 V2             | Desktop     | [7524f39579](https://linux-hardware.org/?probe=7524f39579) | Oct 19, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [46cb50f2f6](https://linux-hardware.org/?probe=46cb50f2f6) | Oct 19, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [6d01f5c57b](https://linux-hardware.org/?probe=6d01f5c57b) | Oct 19, 2022 |
| Dell          | XPS 9320                    | Notebook    | [8dd41b53b6](https://linux-hardware.org/?probe=8dd41b53b6) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [a2db8aeade](https://linux-hardware.org/?probe=a2db8aeade) | Oct 19, 2022 |
| Samsung       | R430/P430/R480              | Notebook    | [92957e0afc](https://linux-hardware.org/?probe=92957e0afc) | Oct 19, 2022 |
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
| ASUSTek       | PN41                        | Mini pc     | [3498692f6e](https://linux-hardware.org/?probe=3498692f6e) | Oct 15, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [dad786ca06](https://linux-hardware.org/?probe=dad786ca06) | Oct 15, 2022 |
| Lenovo        | ThinkPad T430 2342A19       | Notebook    | [7c6c3783e6](https://linux-hardware.org/?probe=7c6c3783e6) | Oct 14, 2022 |
| Dell          | Precision M6700             | Notebook    | [e198a003b6](https://linux-hardware.org/?probe=e198a003b6) | Oct 13, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [b36220c65b](https://linux-hardware.org/?probe=b36220c65b) | Oct 13, 2022 |
| Lenovo        | ThinkBook 14 G4 ABA 21DK    | Notebook    | [1258429041](https://linux-hardware.org/?probe=1258429041) | Oct 13, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [20eebb7b05](https://linux-hardware.org/?probe=20eebb7b05) | Oct 12, 2022 |
| GPU Compan... | GWTC116-2                   | Notebook    | [93ee54a067](https://linux-hardware.org/?probe=93ee54a067) | Oct 11, 2022 |
| Gigabyte      | P55-US3L                    | Desktop     | [59843156e8](https://linux-hardware.org/?probe=59843156e8) | Oct 11, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [125ad4881a](https://linux-hardware.org/?probe=125ad4881a) | Oct 11, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [77d21da9a2](https://linux-hardware.org/?probe=77d21da9a2) | Oct 11, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [d67f89127f](https://linux-hardware.org/?probe=d67f89127f) | Oct 11, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [b88e8a8b49](https://linux-hardware.org/?probe=b88e8a8b49) | Oct 11, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [71c916389e](https://linux-hardware.org/?probe=71c916389e) | Oct 09, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [5268977f64](https://linux-hardware.org/?probe=5268977f64) | Oct 09, 2022 |
| Acer          | Aspire G7750                | Desktop     | [bd21d9c12b](https://linux-hardware.org/?probe=bd21d9c12b) | Oct 09, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [aad99b4421](https://linux-hardware.org/?probe=aad99b4421) | Oct 09, 2022 |
| ASUSTek       | TUF X470-PLUS GAMING        | Desktop     | [691aa10e89](https://linux-hardware.org/?probe=691aa10e89) | Oct 09, 2022 |
| ASUSTek       | X555UA                      | Notebook    | [9cf559ac01](https://linux-hardware.org/?probe=9cf559ac01) | Oct 08, 2022 |
| Gigabyte      | AERO 15-X9                  | Notebook    | [1f634e5071](https://linux-hardware.org/?probe=1f634e5071) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [1b90e3cfa5](https://linux-hardware.org/?probe=1b90e3cfa5) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [fddd82ba56](https://linux-hardware.org/?probe=fddd82ba56) | Oct 08, 2022 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [9a16ca15b3](https://linux-hardware.org/?probe=9a16ca15b3) | Oct 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [9bb8f8e33b](https://linux-hardware.org/?probe=9bb8f8e33b) | Oct 07, 2022 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [c621294169](https://linux-hardware.org/?probe=c621294169) | Oct 07, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [e59c8f50b4](https://linux-hardware.org/?probe=e59c8f50b4) | Oct 07, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [51442982cd](https://linux-hardware.org/?probe=51442982cd) | Oct 07, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [865d1f0e6f](https://linux-hardware.org/?probe=865d1f0e6f) | Oct 07, 2022 |
| Lenovo        | ZHAOYANG E53-80 81CM        | Notebook    | [985ca1961c](https://linux-hardware.org/?probe=985ca1961c) | Oct 06, 2022 |
| Toshiba       | Satellite NB10t-A-102       | Notebook    | [0bf17a1e92](https://linux-hardware.org/?probe=0bf17a1e92) | Oct 06, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [3b023a0363](https://linux-hardware.org/?probe=3b023a0363) | Oct 06, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [1bf20fe68c](https://linux-hardware.org/?probe=1bf20fe68c) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [99ed468a82](https://linux-hardware.org/?probe=99ed468a82) | Oct 05, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e8b8141f03](https://linux-hardware.org/?probe=e8b8141f03) | Oct 05, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [e4df51e64f](https://linux-hardware.org/?probe=e4df51e64f) | Oct 05, 2022 |
| HUAWEI        | NBD-WXX9                    | Notebook    | [2513dfd51e](https://linux-hardware.org/?probe=2513dfd51e) | Oct 05, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [1ba8422c66](https://linux-hardware.org/?probe=1ba8422c66) | Oct 04, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [082814c248](https://linux-hardware.org/?probe=082814c248) | Oct 04, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [3bc5547f39](https://linux-hardware.org/?probe=3bc5547f39) | Oct 04, 2022 |
| HP            | ProLiant DL360 Gen9         | Server      | [eb5e8725ae](https://linux-hardware.org/?probe=eb5e8725ae) | Oct 04, 2022 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [e857a28ed2](https://linux-hardware.org/?probe=e857a28ed2) | Oct 04, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [bc03e42377](https://linux-hardware.org/?probe=bc03e42377) | Oct 03, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [2dc13504cf](https://linux-hardware.org/?probe=2dc13504cf) | Oct 03, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [61d1e2102b](https://linux-hardware.org/?probe=61d1e2102b) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [2969d635b3](https://linux-hardware.org/?probe=2969d635b3) | Oct 03, 2022 |
| Acer          | Aspire A315-58              | Notebook    | [28b873114a](https://linux-hardware.org/?probe=28b873114a) | Oct 03, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [330f866cf3](https://linux-hardware.org/?probe=330f866cf3) | Oct 03, 2022 |
| ASUSTek       | ZenBook UX562FD_UX562FD     | Convertible | [b9f2861719](https://linux-hardware.org/?probe=b9f2861719) | Oct 02, 2022 |
| Lenovo        | IdeaPad 1 14IGL05 81VU      | Notebook    | [c555fbbf75](https://linux-hardware.org/?probe=c555fbbf75) | Oct 01, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [ec44263cbd](https://linux-hardware.org/?probe=ec44263cbd) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [f05b832b90](https://linux-hardware.org/?probe=f05b832b90) | Oct 01, 2022 |
| Lenovo        | ThinkCentre M90p 5498A2U    | Desktop     | [d638b38369](https://linux-hardware.org/?probe=d638b38369) | Sep 30, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [24a248630f](https://linux-hardware.org/?probe=24a248630f) | Sep 30, 2022 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [dad71b5547](https://linux-hardware.org/?probe=dad71b5547) | Sep 28, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [19fe9ebfb6](https://linux-hardware.org/?probe=19fe9ebfb6) | Sep 27, 2022 |
| ASRock        | 990FX Extreme9              | Desktop     | [c7522b70ba](https://linux-hardware.org/?probe=c7522b70ba) | Sep 27, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [3e14df6c26](https://linux-hardware.org/?probe=3e14df6c26) | Sep 27, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [476623a6a1](https://linux-hardware.org/?probe=476623a6a1) | Sep 26, 2022 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [762ad6e460](https://linux-hardware.org/?probe=762ad6e460) | Sep 26, 2022 |
| MSI           | Z590-A PRO                  | Desktop     | [72bd6750e5](https://linux-hardware.org/?probe=72bd6750e5) | Sep 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [923985941d](https://linux-hardware.org/?probe=923985941d) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | Notebook    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| Lenovo        | ThinkPad X230 23256N6       | Notebook    | [f061f902ff](https://linux-hardware.org/?probe=f061f902ff) | Sep 25, 2022 |
| Lenovo        | ThinkPad T430 2349NZ8       | Notebook    | [8f61a903c5](https://linux-hardware.org/?probe=8f61a903c5) | Sep 25, 2022 |
| Acer          | Aspire R3-131T              | Notebook    | [0d44032bc0](https://linux-hardware.org/?probe=0d44032bc0) | Sep 25, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [60635ca9bc](https://linux-hardware.org/?probe=60635ca9bc) | Sep 24, 2022 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [2a7c09d404](https://linux-hardware.org/?probe=2a7c09d404) | Sep 24, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [07f9a5063e](https://linux-hardware.org/?probe=07f9a5063e) | Sep 23, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [18a4d2bb72](https://linux-hardware.org/?probe=18a4d2bb72) | Sep 23, 2022 |
| Biostar       | TA75MH2                     | Desktop     | [e76fb13311](https://linux-hardware.org/?probe=e76fb13311) | Sep 23, 2022 |
| Lenovo        | ThinkPad L14 Gen 2 20X1S... | Notebook    | [6e943a4d35](https://linux-hardware.org/?probe=6e943a4d35) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [384ab44e0a](https://linux-hardware.org/?probe=384ab44e0a) | Sep 23, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [24c7d626c8](https://linux-hardware.org/?probe=24c7d626c8) | Sep 23, 2022 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [f6e7ad269e](https://linux-hardware.org/?probe=f6e7ad269e) | Sep 22, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [20691b389b](https://linux-hardware.org/?probe=20691b389b) | Sep 21, 2022 |
| AZW           | SER                         | Mini pc     | [9e9ee5be74](https://linux-hardware.org/?probe=9e9ee5be74) | Sep 21, 2022 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [6352f6fb82](https://linux-hardware.org/?probe=6352f6fb82) | Sep 21, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [2a27e3cb58](https://linux-hardware.org/?probe=2a27e3cb58) | Sep 21, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [256ff04106](https://linux-hardware.org/?probe=256ff04106) | Sep 20, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [9b0dd73d61](https://linux-hardware.org/?probe=9b0dd73d61) | Sep 20, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [b7dcf8a06c](https://linux-hardware.org/?probe=b7dcf8a06c) | Sep 20, 2022 |
| Dell          | OptiPlex 9020 AIO           | All in one  | [f52114ac39](https://linux-hardware.org/?probe=f52114ac39) | Sep 19, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [41b1b790fd](https://linux-hardware.org/?probe=41b1b790fd) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Acer          | Aspire G7750                | Desktop     | [c54e28dc84](https://linux-hardware.org/?probe=c54e28dc84) | Sep 18, 2022 |
| Google        | Blooglet                    | Notebook    | [971a174a56](https://linux-hardware.org/?probe=971a174a56) | Sep 18, 2022 |
| Gigabyte      | B560M D3H                   | Desktop     | [515d75e6b7](https://linux-hardware.org/?probe=515d75e6b7) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [5aadfd37c5](https://linux-hardware.org/?probe=5aadfd37c5) | Sep 17, 2022 |
| Acer          | Aspire S3-391               | Notebook    | [82a1f45915](https://linux-hardware.org/?probe=82a1f45915) | Sep 17, 2022 |
| MSI           | Delta 15 A5EFK              | Notebook    | [382e0f70a3](https://linux-hardware.org/?probe=382e0f70a3) | Sep 17, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [4a903b438f](https://linux-hardware.org/?probe=4a903b438f) | Sep 17, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [4ee2b37edf](https://linux-hardware.org/?probe=4ee2b37edf) | Sep 16, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [3f362093da](https://linux-hardware.org/?probe=3f362093da) | Sep 16, 2022 |
| ASUSTek       | G501VW                      | Notebook    | [cf04ceb420](https://linux-hardware.org/?probe=cf04ceb420) | Sep 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ea2264656c](https://linux-hardware.org/?probe=ea2264656c) | Sep 15, 2022 |
| Google        | Treeya                      | Notebook    | [a2723e9afa](https://linux-hardware.org/?probe=a2723e9afa) | Sep 15, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [3af5d11f3f](https://linux-hardware.org/?probe=3af5d11f3f) | Sep 14, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [356956ad10](https://linux-hardware.org/?probe=356956ad10) | Sep 14, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [22e62266a2](https://linux-hardware.org/?probe=22e62266a2) | Sep 13, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [d4fb6aa0ae](https://linux-hardware.org/?probe=d4fb6aa0ae) | Sep 13, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [8aac6d779b](https://linux-hardware.org/?probe=8aac6d779b) | Sep 13, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [703c55185d](https://linux-hardware.org/?probe=703c55185d) | Sep 12, 2022 |
| Sony          | SVE1512J6EW                 | Notebook    | [69e2400606](https://linux-hardware.org/?probe=69e2400606) | Sep 11, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [52f6655891](https://linux-hardware.org/?probe=52f6655891) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [d79d03b7ef](https://linux-hardware.org/?probe=d79d03b7ef) | Sep 11, 2022 |
| Dell          | G15 5511                    | Notebook    | [b971c27fae](https://linux-hardware.org/?probe=b971c27fae) | Sep 10, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [50f39d7738](https://linux-hardware.org/?probe=50f39d7738) | Sep 09, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [17e4855f90](https://linux-hardware.org/?probe=17e4855f90) | Sep 09, 2022 |
| Dell          | Latitude 7430               | Notebook    | [b1cdbef6b2](https://linux-hardware.org/?probe=b1cdbef6b2) | Sep 09, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [b50a1bc29b](https://linux-hardware.org/?probe=b50a1bc29b) | Sep 09, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [d3f42d0c24](https://linux-hardware.org/?probe=d3f42d0c24) | Sep 08, 2022 |
| Acer          | Predator G3-571             | Notebook    | [553cf2f33f](https://linux-hardware.org/?probe=553cf2f33f) | Sep 08, 2022 |
| Dell          | Vostro 3700                 | Notebook    | [40e150eb3b](https://linux-hardware.org/?probe=40e150eb3b) | Sep 08, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [557860ffbd](https://linux-hardware.org/?probe=557860ffbd) | Sep 07, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [1f4f30c013](https://linux-hardware.org/?probe=1f4f30c013) | Sep 06, 2022 |
| HP            | 2B3E                        | All in one  | [4ccdce6df9](https://linux-hardware.org/?probe=4ccdce6df9) | Sep 06, 2022 |
| Samsung       | 270E5G/270E5U               | Notebook    | [0300dd1a2d](https://linux-hardware.org/?probe=0300dd1a2d) | Sep 05, 2022 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [85798fb011](https://linux-hardware.org/?probe=85798fb011) | Sep 05, 2022 |
| ASUSTek       | UX51VZA                     | Notebook    | [46aa1dbafa](https://linux-hardware.org/?probe=46aa1dbafa) | Sep 04, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [0c89daf254](https://linux-hardware.org/?probe=0c89daf254) | Sep 03, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8eec266b41](https://linux-hardware.org/?probe=8eec266b41) | Sep 03, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [5c11f5477e](https://linux-hardware.org/?probe=5c11f5477e) | Sep 03, 2022 |
| ASRock        | A320M-HDV                   | Desktop     | [5a9342d8e9](https://linux-hardware.org/?probe=5a9342d8e9) | Sep 03, 2022 |
| Dell          | 02YYK5 A00                  | Desktop     | [742579c33d](https://linux-hardware.org/?probe=742579c33d) | Sep 03, 2022 |
| HP            | Notebook                    | Notebook    | [a3b180cbb5](https://linux-hardware.org/?probe=a3b180cbb5) | Sep 03, 2022 |
| OEM           | G41 775 ICH7 8712           | Desktop     | [4c9041cf15](https://linux-hardware.org/?probe=4c9041cf15) | Sep 03, 2022 |
| Lenovo        | G780 20138                  | Notebook    | [4a452f0874](https://linux-hardware.org/?probe=4a452f0874) | Sep 03, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [a4290c0678](https://linux-hardware.org/?probe=a4290c0678) | Sep 03, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [296c04b276](https://linux-hardware.org/?probe=296c04b276) | Sep 02, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [33784347f5](https://linux-hardware.org/?probe=33784347f5) | Sep 02, 2022 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [a1b5555512](https://linux-hardware.org/?probe=a1b5555512) | Sep 02, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL 20VD    | Notebook    | [a15c233224](https://linux-hardware.org/?probe=a15c233224) | Sep 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [d34c9cb705](https://linux-hardware.org/?probe=d34c9cb705) | Sep 01, 2022 |
| Lenovo        | ThinkPad T460 20FMS08U00    | Notebook    | [d7457fd32a](https://linux-hardware.org/?probe=d7457fd32a) | Sep 01, 2022 |
| HP            | Pavilion Gaming Laptop      | Notebook    | [8382b4123e](https://linux-hardware.org/?probe=8382b4123e) | Aug 31, 2022 |
| Samsung       | 870Z5E/880Z5E/680Z5E        | Notebook    | [0166c06969](https://linux-hardware.org/?probe=0166c06969) | Aug 30, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [505eb9a97c](https://linux-hardware.org/?probe=505eb9a97c) | Aug 29, 2022 |
| Lenovo        | 32E4 SDK0J40697 WIN 3305... | Mini pc     | [3825d0ce9c](https://linux-hardware.org/?probe=3825d0ce9c) | Aug 29, 2022 |
| Gigabyte      | B85M-HD3                    | Desktop     | [dcb5e7a20c](https://linux-hardware.org/?probe=dcb5e7a20c) | Aug 29, 2022 |
| Dell          | Latitude 9420               | Notebook    | [0b8d883170](https://linux-hardware.org/?probe=0b8d883170) | Aug 29, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [3f4c6a4d48](https://linux-hardware.org/?probe=3f4c6a4d48) | Aug 29, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [fe1480794c](https://linux-hardware.org/?probe=fe1480794c) | Aug 29, 2022 |
| Google        | Eldrid                      | Notebook    | [ae53120bac](https://linux-hardware.org/?probe=ae53120bac) | Aug 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [20bea980d2](https://linux-hardware.org/?probe=20bea980d2) | Aug 28, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [93af020634](https://linux-hardware.org/?probe=93af020634) | Aug 27, 2022 |
| AMI           | Aptio CRB                   | Mini pc     | [11cd220cfd](https://linux-hardware.org/?probe=11cd220cfd) | Aug 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [208be390fa](https://linux-hardware.org/?probe=208be390fa) | Aug 26, 2022 |
| ASRock        | B450M/ac R2.0               | Desktop     | [ede2f61f08](https://linux-hardware.org/?probe=ede2f61f08) | Aug 26, 2022 |
| Sony          | VGN-NR11Z_T                 | Notebook    | [54c1e7c198](https://linux-hardware.org/?probe=54c1e7c198) | Aug 26, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [36f10ad555](https://linux-hardware.org/?probe=36f10ad555) | Aug 24, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [5097845796](https://linux-hardware.org/?probe=5097845796) | Aug 24, 2022 |
| ASUSTek       | B85-PLUS                    | Desktop     | [1eba4b558d](https://linux-hardware.org/?probe=1eba4b558d) | Aug 23, 2022 |
| Gigabyte      | BOLD E3032                  | Desktop     | [4b70fe47a2](https://linux-hardware.org/?probe=4b70fe47a2) | Aug 23, 2022 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [cb43b7a4cf](https://linux-hardware.org/?probe=cb43b7a4cf) | Aug 22, 2022 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [c084ff3123](https://linux-hardware.org/?probe=c084ff3123) | Aug 22, 2022 |
| HP            | ENVY Laptop 17-ce1xxx       | Notebook    | [4c201d43d0](https://linux-hardware.org/?probe=4c201d43d0) | Aug 22, 2022 |
| Supermicro    | SKAGIT09                    | Desktop     | [1ae2767db3](https://linux-hardware.org/?probe=1ae2767db3) | Aug 22, 2022 |
| Toshiba       | Satellite P70-B             | Notebook    | [4e04d56e06](https://linux-hardware.org/?probe=4e04d56e06) | Aug 21, 2022 |
| Toshiba       | Satellite P70-B             | Notebook    | [402017a7ea](https://linux-hardware.org/?probe=402017a7ea) | Aug 21, 2022 |
| Dell          | G3 3500                     | Notebook    | [1e8edd3350](https://linux-hardware.org/?probe=1e8edd3350) | Aug 21, 2022 |
| Dell          | Inspiron 15-5578            | Notebook    | [a0ff8934e5](https://linux-hardware.org/?probe=a0ff8934e5) | Aug 21, 2022 |
| HP            | Pavilion g6                 | Notebook    | [8d5375bd39](https://linux-hardware.org/?probe=8d5375bd39) | Aug 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [45bac2f9d1](https://linux-hardware.org/?probe=45bac2f9d1) | Aug 20, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [e058dec94d](https://linux-hardware.org/?probe=e058dec94d) | Aug 19, 2022 |
| MSI           | GF75 Thin 10SCXR            | Notebook    | [b75c38c8a5](https://linux-hardware.org/?probe=b75c38c8a5) | Aug 19, 2022 |
| Dell          | Latitude 7280               | Notebook    | [63e00d0c9d](https://linux-hardware.org/?probe=63e00d0c9d) | Aug 18, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [73649d898c](https://linux-hardware.org/?probe=73649d898c) | Aug 18, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1AY0... | Notebook    | [fcda79b03d](https://linux-hardware.org/?probe=fcda79b03d) | Aug 17, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [dd98185972](https://linux-hardware.org/?probe=dd98185972) | Aug 16, 2022 |
| ASUSTek       | H170M-PLUS/BR               | Desktop     | [feb4e50ec5](https://linux-hardware.org/?probe=feb4e50ec5) | Aug 16, 2022 |
| Lenovo        | Bantry CRB SDK0J40700 WI... | Desktop     | [792eb4143f](https://linux-hardware.org/?probe=792eb4143f) | Aug 16, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [4d6f6d6a23](https://linux-hardware.org/?probe=4d6f6d6a23) | Aug 15, 2022 |
| ZOTAC         | ZBOXNANO-CI520NANO/CI540... | Mini pc     | [96b090be6a](https://linux-hardware.org/?probe=96b090be6a) | Aug 15, 2022 |
| Dell          | Precision 3571              | Notebook    | [48c3133a7f](https://linux-hardware.org/?probe=48c3133a7f) | Aug 15, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [646d091037](https://linux-hardware.org/?probe=646d091037) | Aug 15, 2022 |
| HP            | 805D                        | Desktop     | [54f4e0fdb0](https://linux-hardware.org/?probe=54f4e0fdb0) | Aug 14, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [ca96da9d08](https://linux-hardware.org/?probe=ca96da9d08) | Aug 12, 2022 |
| Dell          | 0C2XKD A01                  | Desktop     | [cfad241ca0](https://linux-hardware.org/?probe=cfad241ca0) | Aug 12, 2022 |
| Positivo      | POS-PARS760GCD POSITIVO     | Desktop     | [dc6e65929f](https://linux-hardware.org/?probe=dc6e65929f) | Aug 12, 2022 |
| Panasonic     | CF-53JSWZGFF                | Notebook    | [88c83a7e28](https://linux-hardware.org/?probe=88c83a7e28) | Aug 11, 2022 |
| HP            | 8459                        | Desktop     | [677ca01f4f](https://linux-hardware.org/?probe=677ca01f4f) | Aug 11, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [d2f7a86fd8](https://linux-hardware.org/?probe=d2f7a86fd8) | Aug 11, 2022 |
| Dell          | Latitude 5590               | Notebook    | [a00272df56](https://linux-hardware.org/?probe=a00272df56) | Aug 11, 2022 |
| Lenovo        | Yoga Slim 7 15ITL05 82AC    | Notebook    | [477ce53969](https://linux-hardware.org/?probe=477ce53969) | Aug 10, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [14aebc0034](https://linux-hardware.org/?probe=14aebc0034) | Aug 09, 2022 |
| HP            | G62                         | Notebook    | [430fe133db](https://linux-hardware.org/?probe=430fe133db) | Aug 09, 2022 |
| Lenovo        | ThinkPad T430 2347AT2       | Notebook    | [4b74670050](https://linux-hardware.org/?probe=4b74670050) | Aug 08, 2022 |
| Dell          | Latitude 5420               | Notebook    | [824404ee24](https://linux-hardware.org/?probe=824404ee24) | Aug 08, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [7311161548](https://linux-hardware.org/?probe=7311161548) | Aug 07, 2022 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [6eac3041ec](https://linux-hardware.org/?probe=6eac3041ec) | Aug 07, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [fb01882d07](https://linux-hardware.org/?probe=fb01882d07) | Aug 06, 2022 |
| MSI           | Z97 GAMING 7                | Desktop     | [01cf6a0897](https://linux-hardware.org/?probe=01cf6a0897) | Aug 06, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [1340311493](https://linux-hardware.org/?probe=1340311493) | Aug 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [9c77d1a0d5](https://linux-hardware.org/?probe=9c77d1a0d5) | Aug 06, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [ea189dab70](https://linux-hardware.org/?probe=ea189dab70) | Aug 06, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [9893d12c54](https://linux-hardware.org/?probe=9893d12c54) | Aug 06, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [6fa2b142e4](https://linux-hardware.org/?probe=6fa2b142e4) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [22e9ee373f](https://linux-hardware.org/?probe=22e9ee373f) | Aug 06, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [df685682b3](https://linux-hardware.org/?probe=df685682b3) | Aug 05, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [e5e72c1264](https://linux-hardware.org/?probe=e5e72c1264) | Aug 05, 2022 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [d725206bff](https://linux-hardware.org/?probe=d725206bff) | Aug 04, 2022 |
| Dell          | Latitude 5590               | Notebook    | [52f059849a](https://linux-hardware.org/?probe=52f059849a) | Aug 04, 2022 |
| Dell          | Latitude 5590               | Notebook    | [47292ecf57](https://linux-hardware.org/?probe=47292ecf57) | Aug 04, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [42469385bc](https://linux-hardware.org/?probe=42469385bc) | Aug 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [f79a1d3402](https://linux-hardware.org/?probe=f79a1d3402) | Aug 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [b2e4380743](https://linux-hardware.org/?probe=b2e4380743) | Aug 03, 2022 |
| Hardkernel    | ODROID-C4                   | Soc         | [85ed0f33f0](https://linux-hardware.org/?probe=85ed0f33f0) | Aug 02, 2022 |
| Intel         | Unknown                     | Notebook    | [9fce3597b9](https://linux-hardware.org/?probe=9fce3597b9) | Aug 01, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [09c15c1ed8](https://linux-hardware.org/?probe=09c15c1ed8) | Jul 31, 2022 |
| ASUSTek       | P8H67                       | Desktop     | [b1b842e547](https://linux-hardware.org/?probe=b1b842e547) | Jul 29, 2022 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [73b9d340d2](https://linux-hardware.org/?probe=73b9d340d2) | Jul 28, 2022 |
| Dell          | Latitude 5590               | Notebook    | [7fa93449bd](https://linux-hardware.org/?probe=7fa93449bd) | Jul 28, 2022 |
| Dell          | Inspiron 7791 2n1           | Convertible | [8b027b07d9](https://linux-hardware.org/?probe=8b027b07d9) | Jul 27, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [9c0b784d1d](https://linux-hardware.org/?probe=9c0b784d1d) | Jul 27, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [5ed19c54a9](https://linux-hardware.org/?probe=5ed19c54a9) | Jul 27, 2022 |
| Dell          | G5 5590                     | Notebook    | [20f75f2334](https://linux-hardware.org/?probe=20f75f2334) | Jul 27, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [ee8688ecdb](https://linux-hardware.org/?probe=ee8688ecdb) | Jul 26, 2022 |
| Unknown       | Unknown                     | Notebook    | [03fa847263](https://linux-hardware.org/?probe=03fa847263) | Jul 26, 2022 |
| Lenovo        | G570 20079                  | Notebook    | [50bab54f21](https://linux-hardware.org/?probe=50bab54f21) | Jul 26, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6967eac391](https://linux-hardware.org/?probe=6967eac391) | Jul 26, 2022 |
| ASRock        | Z270 Gaming K4              | Desktop     | [63612e20b4](https://linux-hardware.org/?probe=63612e20b4) | Jul 26, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [2c515ee09a](https://linux-hardware.org/?probe=2c515ee09a) | Jul 24, 2022 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [e24e72037a](https://linux-hardware.org/?probe=e24e72037a) | Jul 24, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [d404840b57](https://linux-hardware.org/?probe=d404840b57) | Jul 24, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [5658129aa4](https://linux-hardware.org/?probe=5658129aa4) | Jul 24, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [ec23b6375e](https://linux-hardware.org/?probe=ec23b6375e) | Jul 24, 2022 |
| Fujitsu       | D3500-A1 S26361-D3500-A1    | Desktop     | [ba1841221c](https://linux-hardware.org/?probe=ba1841221c) | Jul 24, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [021e469888](https://linux-hardware.org/?probe=021e469888) | Jul 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [ea90d78c53](https://linux-hardware.org/?probe=ea90d78c53) | Jul 23, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [6e6e65c711](https://linux-hardware.org/?probe=6e6e65c711) | Jul 23, 2022 |
| Gigabyte      | P35-DS3L                    | Desktop     | [4ae76fafc9](https://linux-hardware.org/?probe=4ae76fafc9) | Jul 22, 2022 |
| Shuttle       | NC01U V1.0                  | Desktop     | [827d6c81ae](https://linux-hardware.org/?probe=827d6c81ae) | Jul 22, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e71169659f](https://linux-hardware.org/?probe=e71169659f) | Jul 22, 2022 |
| HP            | G62                         | Notebook    | [418c1c572e](https://linux-hardware.org/?probe=418c1c572e) | Jul 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| Shuttle       | NC01U V1.0                  | Desktop     | [fecfaf6008](https://linux-hardware.org/?probe=fecfaf6008) | Jul 21, 2022 |
| HP            | 18E9                        | Desktop     | [f15b2671b0](https://linux-hardware.org/?probe=f15b2671b0) | Jul 21, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [226924706f](https://linux-hardware.org/?probe=226924706f) | Jul 20, 2022 |
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
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [01d595926f](https://linux-hardware.org/?probe=01d595926f) | Jul 15, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [789f614370](https://linux-hardware.org/?probe=789f614370) | Jul 14, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [57ef4db755](https://linux-hardware.org/?probe=57ef4db755) | Jul 14, 2022 |
| Schenker      | XMG APEX (Mid 2021)         | Notebook    | [41136553b2](https://linux-hardware.org/?probe=41136553b2) | Jul 13, 2022 |
| MSI           | X99A XPOWER GAMING TITAN... | Desktop     | [e764729eeb](https://linux-hardware.org/?probe=e764729eeb) | Jul 13, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [7ecf3ad1b7](https://linux-hardware.org/?probe=7ecf3ad1b7) | Jul 13, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [6106db3d9a](https://linux-hardware.org/?probe=6106db3d9a) | Jul 12, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [fafb6deae6](https://linux-hardware.org/?probe=fafb6deae6) | Jul 12, 2022 |
| TUXEDO        | Stellaris AMD Gen3 (CZN)    | Notebook    | [33bea96de9](https://linux-hardware.org/?probe=33bea96de9) | Jul 12, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [21ef2a8d9a](https://linux-hardware.org/?probe=21ef2a8d9a) | Jul 12, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [1bbf224b5c](https://linux-hardware.org/?probe=1bbf224b5c) | Jul 11, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [d6531258d0](https://linux-hardware.org/?probe=d6531258d0) | Jul 11, 2022 |
| System76      | Lemur Ultra                 | Notebook    | [10e8deaf3b](https://linux-hardware.org/?probe=10e8deaf3b) | Jul 11, 2022 |
| ASRock        | B550 Taichi                 | Desktop     | [61fe809791](https://linux-hardware.org/?probe=61fe809791) | Jul 10, 2022 |
| Gigabyte      | Z77-D3H                     | Desktop     | [f9e15346d3](https://linux-hardware.org/?probe=f9e15346d3) | Jul 10, 2022 |
| Toshiba       | TECRA S11                   | Notebook    | [c33fa181ba](https://linux-hardware.org/?probe=c33fa181ba) | Jul 08, 2022 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [d7e1136386](https://linux-hardware.org/?probe=d7e1136386) | Jul 07, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [6b007e333a](https://linux-hardware.org/?probe=6b007e333a) | Jul 06, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [f09a1deecc](https://linux-hardware.org/?probe=f09a1deecc) | Jul 06, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [e7e175955d](https://linux-hardware.org/?probe=e7e175955d) | Jul 05, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [a23d0fe53d](https://linux-hardware.org/?probe=a23d0fe53d) | Jul 04, 2022 |
| Chuwi         | CoreBook X                  | Notebook    | [a8d8dfc814](https://linux-hardware.org/?probe=a8d8dfc814) | Jul 03, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [7d5d5c1a7e](https://linux-hardware.org/?probe=7d5d5c1a7e) | Jul 02, 2022 |
| Dell          | Latitude 7530               | Notebook    | [a66aca8921](https://linux-hardware.org/?probe=a66aca8921) | Jul 01, 2022 |
| HP            | 8459                        | Desktop     | [f43fdff127](https://linux-hardware.org/?probe=f43fdff127) | Jul 01, 2022 |
| ASUSTek       | ET2400A                     | Desktop     | [8801791f80](https://linux-hardware.org/?probe=8801791f80) | Jul 01, 2022 |
| HONOR         | BOHK-WAX9X                  | Notebook    | [1647402099](https://linux-hardware.org/?probe=1647402099) | Jun 30, 2022 |
| Jumper        | EZpad                       | Notebook    | [5d5f3980e1](https://linux-hardware.org/?probe=5d5f3980e1) | Jun 30, 2022 |
| Dell          | Latitude 3420               | Notebook    | [5fef19c107](https://linux-hardware.org/?probe=5fef19c107) | Jun 29, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [6dc02ab574](https://linux-hardware.org/?probe=6dc02ab574) | Jun 29, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [33c8a42a4d](https://linux-hardware.org/?probe=33c8a42a4d) | Jun 29, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [757741fe0d](https://linux-hardware.org/?probe=757741fe0d) | Jun 29, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [d2f3d5aefd](https://linux-hardware.org/?probe=d2f3d5aefd) | Jun 28, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [0c1cbe6fd7](https://linux-hardware.org/?probe=0c1cbe6fd7) | Jun 28, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [efb8cff806](https://linux-hardware.org/?probe=efb8cff806) | Jun 28, 2022 |
| Haier         | A1420EM                     | Notebook    | [3690a94424](https://linux-hardware.org/?probe=3690a94424) | Jun 28, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [f39c4bd8a0](https://linux-hardware.org/?probe=f39c4bd8a0) | Jun 27, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [a6555d107c](https://linux-hardware.org/?probe=a6555d107c) | Jun 27, 2022 |
| HP            | 15                          | Notebook    | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| ASUSTek       | K46CB                       | Notebook    | [3af9df185f](https://linux-hardware.org/?probe=3af9df185f) | Jun 26, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [e1918d8aab](https://linux-hardware.org/?probe=e1918d8aab) | Jun 25, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [6afa74e5b6](https://linux-hardware.org/?probe=6afa74e5b6) | Jun 25, 2022 |
| Huanan        | X99-F8 GAMING V5.0          | Desktop     | [2688876fc9](https://linux-hardware.org/?probe=2688876fc9) | Jun 25, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [f4f2e68e79](https://linux-hardware.org/?probe=f4f2e68e79) | Jun 24, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [0647ff3774](https://linux-hardware.org/?probe=0647ff3774) | Jun 24, 2022 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [04e6f0ee4a](https://linux-hardware.org/?probe=04e6f0ee4a) | Jun 24, 2022 |
| ABIT          | IP35 Pro                    | Desktop     | [a5f262c233](https://linux-hardware.org/?probe=a5f262c233) | Jun 23, 2022 |
| Dell          | Latitude 5590               | Notebook    | [aa45d97e0b](https://linux-hardware.org/?probe=aa45d97e0b) | Jun 23, 2022 |
| Dell          | Latitude 5590               | Notebook    | [3745dfcae3](https://linux-hardware.org/?probe=3745dfcae3) | Jun 23, 2022 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [62f47da7d2](https://linux-hardware.org/?probe=62f47da7d2) | Jun 22, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [c931d0e7bf](https://linux-hardware.org/?probe=c931d0e7bf) | Jun 20, 2022 |
| Dell          | XPS 17 9720                 | Notebook    | [2a36b8d90d](https://linux-hardware.org/?probe=2a36b8d90d) | Jun 20, 2022 |
| ASUSTek       | P8P67 LE                    | Desktop     | [8e1bc37281](https://linux-hardware.org/?probe=8e1bc37281) | Jun 19, 2022 |
| Toshiba       | Satellite L655              | Notebook    | [2e67542246](https://linux-hardware.org/?probe=2e67542246) | Jun 19, 2022 |
| ASUSTek       | X550JF                      | Notebook    | [be77e811e2](https://linux-hardware.org/?probe=be77e811e2) | Jun 18, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [1dbf6320bc](https://linux-hardware.org/?probe=1dbf6320bc) | Jun 18, 2022 |
| SLIMBOOK      | PROX15-AMD                  | Notebook    | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [bbb784f2df](https://linux-hardware.org/?probe=bbb784f2df) | Jun 18, 2022 |
| Dell          | 0YNVJG A01                  | Desktop     | [b75bebfda2](https://linux-hardware.org/?probe=b75bebfda2) | Jun 18, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [aace637cfc](https://linux-hardware.org/?probe=aace637cfc) | Jun 17, 2022 |
| MSI           | Raider GE66 12UGS           | Notebook    | [d69dc59622](https://linux-hardware.org/?probe=d69dc59622) | Jun 16, 2022 |
| ASUSTek       | X99-A/USB                   | Desktop     | [3ad17f6d78](https://linux-hardware.org/?probe=3ad17f6d78) | Jun 16, 2022 |
| ASUSTek       | P5QC                        | Desktop     | [b9a53514e1](https://linux-hardware.org/?probe=b9a53514e1) | Jun 16, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [06bef31587](https://linux-hardware.org/?probe=06bef31587) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [d5f742022e](https://linux-hardware.org/?probe=d5f742022e) | Jun 16, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [6c352cf792](https://linux-hardware.org/?probe=6c352cf792) | Jun 16, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7adac78ac0](https://linux-hardware.org/?probe=7adac78ac0) | Jun 15, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [91316a0904](https://linux-hardware.org/?probe=91316a0904) | Jun 15, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [2b307211cd](https://linux-hardware.org/?probe=2b307211cd) | Jun 14, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [8faa0f9e6a](https://linux-hardware.org/?probe=8faa0f9e6a) | Jun 14, 2022 |
| ASUSTek       | UX51VZ                      | Notebook    | [d58122ba72](https://linux-hardware.org/?probe=d58122ba72) | Jun 13, 2022 |
| Jumper        | EZpad                       | Notebook    | [3a5e6bc998](https://linux-hardware.org/?probe=3a5e6bc998) | Jun 13, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [013de61252](https://linux-hardware.org/?probe=013de61252) | Jun 12, 2022 |
| Dell          | 0KC9NP A01                  | Desktop     | [c573376df6](https://linux-hardware.org/?probe=c573376df6) | Jun 11, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [317ae1383a](https://linux-hardware.org/?probe=317ae1383a) | Jun 10, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [4f6d06171b](https://linux-hardware.org/?probe=4f6d06171b) | Jun 10, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [2c789d1a84](https://linux-hardware.org/?probe=2c789d1a84) | Jun 10, 2022 |
| HP            | Pavilion dv6                | Notebook    | [88a92966a3](https://linux-hardware.org/?probe=88a92966a3) | Jun 09, 2022 |
| Dell          | Latitude 5590               | Notebook    | [befc14c3db](https://linux-hardware.org/?probe=befc14c3db) | Jun 09, 2022 |
| Dell          | Latitude 5590               | Notebook    | [0c8e1f9f23](https://linux-hardware.org/?probe=0c8e1f9f23) | Jun 09, 2022 |
| MSI           | GP76 Leopard 11UH           | Notebook    | [8a3c021b8a](https://linux-hardware.org/?probe=8a3c021b8a) | Jun 08, 2022 |
| AZW           | Gemini J45                  | Desktop     | [f4d7238f95](https://linux-hardware.org/?probe=f4d7238f95) | Jun 08, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [15f48b1e64](https://linux-hardware.org/?probe=15f48b1e64) | Jun 08, 2022 |
| System76      | Kudu Professional           | Notebook    | [4ffc6fc358](https://linux-hardware.org/?probe=4ffc6fc358) | Jun 08, 2022 |
| System76      | Kudu Professional           | Notebook    | [0c0e2ed5b2](https://linux-hardware.org/?probe=0c0e2ed5b2) | Jun 08, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [3a58a9889b](https://linux-hardware.org/?probe=3a58a9889b) | Jun 08, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MG... | Notebook    | [f4c82e1fb6](https://linux-hardware.org/?probe=f4c82e1fb6) | Jun 07, 2022 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [1dea88e6b2](https://linux-hardware.org/?probe=1dea88e6b2) | Jun 07, 2022 |
| Dell          | Inspiron 7391 2n1           | Convertible | [acf0372bdc](https://linux-hardware.org/?probe=acf0372bdc) | Jun 06, 2022 |
| Lenovo        | ThinkPad X61 Tablet 7762... | Notebook    | [9ccaec00d8](https://linux-hardware.org/?probe=9ccaec00d8) | Jun 06, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9bc79127f3](https://linux-hardware.org/?probe=9bc79127f3) | Jun 06, 2022 |
| Dell          | 0Y2MRG A00                  | Desktop     | [11bba01e79](https://linux-hardware.org/?probe=11bba01e79) | Jun 06, 2022 |
| Dell          | Latitude 5590               | Notebook    | [be30c04869](https://linux-hardware.org/?probe=be30c04869) | Jun 05, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [065dee2160](https://linux-hardware.org/?probe=065dee2160) | Jun 04, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [de4976b9dd](https://linux-hardware.org/?probe=de4976b9dd) | Jun 04, 2022 |
| Dell          | Latitude 5590               | Notebook    | [cc94c06259](https://linux-hardware.org/?probe=cc94c06259) | Jun 04, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [5e57fb2871](https://linux-hardware.org/?probe=5e57fb2871) | Jun 04, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [70f49afd95](https://linux-hardware.org/?probe=70f49afd95) | Jun 04, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [11ec221a7e](https://linux-hardware.org/?probe=11ec221a7e) | Jun 04, 2022 |
| ASUSTek       | M5A78L-M LE/USB3            | Desktop     | [95173b9d90](https://linux-hardware.org/?probe=95173b9d90) | Jun 04, 2022 |
| MSI           | CX61 2PC                    | Notebook    | [d3decdad4c](https://linux-hardware.org/?probe=d3decdad4c) | Jun 03, 2022 |
| Dell          | OptiPlex 9020 AIO           | All in one  | [c8e2700624](https://linux-hardware.org/?probe=c8e2700624) | Jun 02, 2022 |
| Dell          | Latitude 7420               | Notebook    | [b2ba370a59](https://linux-hardware.org/?probe=b2ba370a59) | Jun 02, 2022 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [66e01e7706](https://linux-hardware.org/?probe=66e01e7706) | Jun 02, 2022 |
| SK hynix      | Onnyx III                   | Notebook    | [a04d3f7fd9](https://linux-hardware.org/?probe=a04d3f7fd9) | Jun 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [6378f52a92](https://linux-hardware.org/?probe=6378f52a92) | May 31, 2022 |
| Acer          | Aspire AV15-51              | Notebook    | [a9183103ee](https://linux-hardware.org/?probe=a9183103ee) | May 31, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [8eda28a8d4](https://linux-hardware.org/?probe=8eda28a8d4) | May 30, 2022 |
| ASUSTek       | P7H55-M LE                  | Desktop     | [4f55b87c44](https://linux-hardware.org/?probe=4f55b87c44) | May 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [177e92d46b](https://linux-hardware.org/?probe=177e92d46b) | May 28, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8bcdd771fa](https://linux-hardware.org/?probe=8bcdd771fa) | May 27, 2022 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [f592de92c2](https://linux-hardware.org/?probe=f592de92c2) | May 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [5718bd4854](https://linux-hardware.org/?probe=5718bd4854) | May 27, 2022 |
| Gigabyte      | AORUS 15 XE4                | Notebook    | [f56ba4f49d](https://linux-hardware.org/?probe=f56ba4f49d) | May 27, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [5410acf8ab](https://linux-hardware.org/?probe=5410acf8ab) | May 25, 2022 |
| Dell          | Vostro 5625                 | Notebook    | [2ae97190b6](https://linux-hardware.org/?probe=2ae97190b6) | May 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [540416deba](https://linux-hardware.org/?probe=540416deba) | May 24, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [887985e68a](https://linux-hardware.org/?probe=887985e68a) | May 24, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [63a10ce1e0](https://linux-hardware.org/?probe=63a10ce1e0) | May 23, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [da40fdda29](https://linux-hardware.org/?probe=da40fdda29) | May 22, 2022 |
| Gigabyte      | B85M-D2V                    | Desktop     | [2bc6293c6a](https://linux-hardware.org/?probe=2bc6293c6a) | May 19, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [93b08c2d75](https://linux-hardware.org/?probe=93b08c2d75) | May 19, 2022 |
| Dell          | Inspiron 7572               | Notebook    | [b7747e3ea4](https://linux-hardware.org/?probe=b7747e3ea4) | May 19, 2022 |
| ASRock        | B560M Pro4                  | Desktop     | [ba3b29db98](https://linux-hardware.org/?probe=ba3b29db98) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [0d4945774e](https://linux-hardware.org/?probe=0d4945774e) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [e771dc589b](https://linux-hardware.org/?probe=e771dc589b) | May 18, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0571b7cb83](https://linux-hardware.org/?probe=0571b7cb83) | May 18, 2022 |
| Gigabyte      | B85M-D2V                    | Desktop     | [da9da96cda](https://linux-hardware.org/?probe=da9da96cda) | May 17, 2022 |
| HP            | ProBook 6470b               | Notebook    | [0581bb1005](https://linux-hardware.org/?probe=0581bb1005) | May 17, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [697a89162e](https://linux-hardware.org/?probe=697a89162e) | May 16, 2022 |
| HP            | Unknown                     | Notebook    | [796c00a0cd](https://linux-hardware.org/?probe=796c00a0cd) | May 15, 2022 |
| Dell          | 0KJCC5 A00                  | Desktop     | [bb68e24835](https://linux-hardware.org/?probe=bb68e24835) | May 15, 2022 |
| HP            | ProBook 6570b               | Notebook    | [e8c38d4e97](https://linux-hardware.org/?probe=e8c38d4e97) | May 15, 2022 |
| Apple         | MacBookPro13,2              | Notebook    | [68e687c794](https://linux-hardware.org/?probe=68e687c794) | May 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [0ec606b729](https://linux-hardware.org/?probe=0ec606b729) | May 14, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [6fdf1cd28c](https://linux-hardware.org/?probe=6fdf1cd28c) | May 14, 2022 |
| MSI           | B450M PRO-M2                | Desktop     | [0bb720a248](https://linux-hardware.org/?probe=0bb720a248) | May 14, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [fb2a9c9ddf](https://linux-hardware.org/?probe=fb2a9c9ddf) | May 13, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [b03899e10b](https://linux-hardware.org/?probe=b03899e10b) | May 13, 2022 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [beaf18770e](https://linux-hardware.org/?probe=beaf18770e) | May 12, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [7923c29010](https://linux-hardware.org/?probe=7923c29010) | May 11, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [dba988f81d](https://linux-hardware.org/?probe=dba988f81d) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [76cc09b228](https://linux-hardware.org/?probe=76cc09b228) | May 10, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [6500cb78c3](https://linux-hardware.org/?probe=6500cb78c3) | May 10, 2022 |
| HP            | 1998                        | Desktop     | [7f82a04d73](https://linux-hardware.org/?probe=7f82a04d73) | May 10, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [f90e5f669e](https://linux-hardware.org/?probe=f90e5f669e) | May 09, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [8aefcd7551](https://linux-hardware.org/?probe=8aefcd7551) | May 08, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [5f90cb38d2](https://linux-hardware.org/?probe=5f90cb38d2) | May 07, 2022 |
| HP            | ProBook 6470b               | Notebook    | [7849fd57dc](https://linux-hardware.org/?probe=7849fd57dc) | May 06, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [8eb673ec29](https://linux-hardware.org/?probe=8eb673ec29) | May 06, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [0af35aa835](https://linux-hardware.org/?probe=0af35aa835) | May 06, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [b420f9214c](https://linux-hardware.org/?probe=b420f9214c) | May 06, 2022 |
| HP            | 2000                        | Notebook    | [1616d82d8e](https://linux-hardware.org/?probe=1616d82d8e) | May 05, 2022 |
| HP            | 2000                        | Notebook    | [f6f20fd25e](https://linux-hardware.org/?probe=f6f20fd25e) | May 05, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [0b27354c9c](https://linux-hardware.org/?probe=0b27354c9c) | May 05, 2022 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [8a561e2442](https://linux-hardware.org/?probe=8a561e2442) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [df622f284f](https://linux-hardware.org/?probe=df622f284f) | May 05, 2022 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [d861de9453](https://linux-hardware.org/?probe=d861de9453) | May 04, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [53a75b2d5c](https://linux-hardware.org/?probe=53a75b2d5c) | May 04, 2022 |
| Toshiba       | Satellite C650D             | Notebook    | [ce16326df2](https://linux-hardware.org/?probe=ce16326df2) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [62f9f79f7c](https://linux-hardware.org/?probe=62f9f79f7c) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [afce1937fe](https://linux-hardware.org/?probe=afce1937fe) | May 03, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [dadde1bbc0](https://linux-hardware.org/?probe=dadde1bbc0) | May 02, 2022 |
| Supermicro    | X8ST3                       | Desktop     | [a94462f4b5](https://linux-hardware.org/?probe=a94462f4b5) | May 02, 2022 |
| Lenovo        | IdeaPad 500-15ISK 80NT      | Notebook    | [d5b6bc1a67](https://linux-hardware.org/?probe=d5b6bc1a67) | May 01, 2022 |
| HP            | Pavilion Laptop 13-bb0xx... | Notebook    | [ae7d5dbb0c](https://linux-hardware.org/?probe=ae7d5dbb0c) | May 01, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [92c09fc927](https://linux-hardware.org/?probe=92c09fc927) | Apr 30, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [7a90a198f5](https://linux-hardware.org/?probe=7a90a198f5) | Apr 30, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [9328531b5a](https://linux-hardware.org/?probe=9328531b5a) | Apr 30, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | Notebook    | [73ee1262a6](https://linux-hardware.org/?probe=73ee1262a6) | Apr 30, 2022 |
| Lenovo        | 36C5 SDK0J40700 WIN 3258... | Desktop     | [d9ac32b17d](https://linux-hardware.org/?probe=d9ac32b17d) | Apr 30, 2022 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [f301c52b41](https://linux-hardware.org/?probe=f301c52b41) | Apr 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [57271a5f8b](https://linux-hardware.org/?probe=57271a5f8b) | Apr 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M340... | Notebook    | [382d77c2b0](https://linux-hardware.org/?probe=382d77c2b0) | Apr 28, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [db9760ae3a](https://linux-hardware.org/?probe=db9760ae3a) | Apr 27, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [87d629883f](https://linux-hardware.org/?probe=87d629883f) | Apr 27, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | Notebook    | [9fffc0babc](https://linux-hardware.org/?probe=9fffc0babc) | Apr 26, 2022 |
| Lenovo        | ThinkPad T530 2394CTO       | Notebook    | [b5f175a650](https://linux-hardware.org/?probe=b5f175a650) | Apr 26, 2022 |
| ASUSTek       | G750JS                      | Notebook    | [24dab87910](https://linux-hardware.org/?probe=24dab87910) | Apr 26, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | Notebook    | [8e7b2c79a0](https://linux-hardware.org/?probe=8e7b2c79a0) | Apr 25, 2022 |
| HP            | 0AACh                       | Desktop     | [f9e511945d](https://linux-hardware.org/?probe=f9e511945d) | Apr 25, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [4b41ff5fb9](https://linux-hardware.org/?probe=4b41ff5fb9) | Apr 24, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [ef1e814871](https://linux-hardware.org/?probe=ef1e814871) | Apr 24, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [3ea846ae2a](https://linux-hardware.org/?probe=3ea846ae2a) | Apr 24, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ITL6 82L... | Notebook    | [a260bf9ce6](https://linux-hardware.org/?probe=a260bf9ce6) | Apr 24, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [9ba9e35d88](https://linux-hardware.org/?probe=9ba9e35d88) | Apr 23, 2022 |
| ASUSTek       | G550JK                      | Notebook    | [566770a325](https://linux-hardware.org/?probe=566770a325) | Apr 21, 2022 |
| Shanghai Z... | ZXE CRB                     | Notebook    | [fe284f4173](https://linux-hardware.org/?probe=fe284f4173) | Apr 17, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [de2cf28654](https://linux-hardware.org/?probe=de2cf28654) | Apr 13, 2022 |
| Lenovo        | ThinkPad X260 20F5S0W22B    | Notebook    | [765eaec64d](https://linux-hardware.org/?probe=765eaec64d) | Apr 04, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e087a37f5f](https://linux-hardware.org/?probe=e087a37f5f) | Apr 02, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [3d513e3c6c](https://linux-hardware.org/?probe=3d513e3c6c) | Mar 24, 2022 |
| Dell          | 0K240Y A02                  | Desktop     | [b5783c7fa0](https://linux-hardware.org/?probe=b5783c7fa0) | Mar 03, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [e5da146c8e](https://linux-hardware.org/?probe=e5da146c8e) | Feb 27, 2022 |
| Timi          | Mi Laptop Air 12.5          | Notebook    | [7aa852e941](https://linux-hardware.org/?probe=7aa852e941) | Feb 25, 2022 |
| Timi          | Mi Laptop Air 12.5          | Notebook    | [67297aad2c](https://linux-hardware.org/?probe=67297aad2c) | Feb 25, 2022 |
| Dell          | Latitude E6320              | Notebook    | [ae7b660be1](https://linux-hardware.org/?probe=ae7b660be1) | Feb 16, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [b99a5f9b59](https://linux-hardware.org/?probe=b99a5f9b59) | Feb 14, 2022 |
| Lenovo        | IdeaPad S145-15API 81UT     | Notebook    | [aba110f180](https://linux-hardware.org/?probe=aba110f180) | Feb 10, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | Notebook    | [30ddfbc611](https://linux-hardware.org/?probe=30ddfbc611) | Feb 03, 2022 |
| LG Electro... | 16Z90P-G.AA78C              | Notebook    | [992ee00a94](https://linux-hardware.org/?probe=992ee00a94) | Feb 02, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [21a8a676d1](https://linux-hardware.org/?probe=21a8a676d1) | Dec 28, 2021 |
| Gigabyte      | B550M DS3H                  | Desktop     | [61561f50ba](https://linux-hardware.org/?probe=61561f50ba) | Dec 28, 2021 |
| Gigabyte      | P35-DS3L                    | Desktop     | [e13fea24e4](https://linux-hardware.org/?probe=e13fea24e4) | Dec 27, 2021 |
| Unknown       | Unknown                     | Notebook    | [d88cb8b5ae](https://linux-hardware.org/?probe=d88cb8b5ae) | Dec 27, 2021 |
| Dell          | 0MX4YF A01                  | Server      | [2015948e6d](https://linux-hardware.org/?probe=2015948e6d) | Dec 15, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1c12810a81](https://linux-hardware.org/?probe=1c12810a81) | Dec 06, 2021 |
| Dell          | 0MX4YF A01                  | Server      | [2c7c189ffa](https://linux-hardware.org/?probe=2c7c189ffa) | Dec 04, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [acadafa3aa](https://linux-hardware.org/?probe=acadafa3aa) | Nov 30, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [5bb4e443f9](https://linux-hardware.org/?probe=5bb4e443f9) | Oct 26, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Kubuntu_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                 | Computers | Percent |
|-------------------------|-----------|---------|
| 5.15.0-48-generic       | 40        | 9.28%   |
| 5.15.0-47-generic       | 35        | 8.12%   |
| 5.15.0-46-generic       | 32        | 7.42%   |
| 5.15.0-41-generic       | 29        | 6.73%   |
| 5.15.0-52-generic       | 28        | 6.5%    |
| 5.15.0-40-generic       | 26        | 6.03%   |
| 5.15.0-43-generic       | 25        | 5.8%    |
| 5.15.0-27-generic       | 24        | 5.57%   |
| 5.15.0-50-generic       | 22        | 5.1%    |
| 5.15.0-25-generic       | 21        | 4.87%   |
| 5.15.0-33-generic       | 18        | 4.18%   |
| 5.15.0-37-generic       | 10        | 2.32%   |
| 5.15.0-30-generic       | 10        | 2.32%   |
| 5.15.0-39-generic       | 8         | 1.86%   |
| 5.15.0-48-lowlatency    | 7         | 1.62%   |
| 5.15.0-35-generic       | 6         | 1.39%   |
| 5.15.0-43-lowlatency    | 5         | 1.16%   |
| 5.15.0-18-generic       | 5         | 1.16%   |
| 5.15.0-46-lowlatency    | 4         | 0.93%   |
| 5.17.0-1017-oem         | 3         | 0.7%    |
| 5.15.0-52-lowlatency    | 3         | 0.7%    |
| 5.15.0-47-lowlatency    | 3         | 0.7%    |
| 5.15.0-30-lowlatency    | 3         | 0.7%    |
| 5.15.0-27-lowlatency    | 3         | 0.7%    |
| 5.13.0-19-generic       | 3         | 0.7%    |
| 6.0.1-060001-generic    | 2         | 0.46%   |
| 5.19.5-051905-generic   | 2         | 0.46%   |
| 5.18.10-051810-generic  | 2         | 0.46%   |
| 5.15.0-53-generic       | 2         | 0.46%   |
| 5.15.0-32-generic       | 2         | 0.46%   |
| 5.15.0-23-generic       | 2         | 0.46%   |
| 5.15.0-10033-tuxedo     | 2         | 0.46%   |
| 6.0.0-t2                | 1         | 0.23%   |
| 6.0.0-060000rc3-generic | 1         | 0.23%   |
| 6.0.0-060000-generic    | 1         | 0.23%   |
| 5.4.0-122-generic       | 1         | 0.23%   |
| 5.19.2-051902-generic   | 1         | 0.23%   |
| 5.19.12-xanmod1         | 1         | 0.23%   |
| 5.19.11-051911-generic  | 1         | 0.23%   |
| 5.18.6-051806-generic   | 1         | 0.23%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.0   | 368       | 89.54%  |
| 5.17.0   | 8         | 1.95%   |
| 5.13.0   | 4         | 0.97%   |
| 6.0.0    | 3         | 0.73%   |
| 6.0.1    | 2         | 0.49%   |
| 5.19.5   | 2         | 0.49%   |
| 5.18.4   | 2         | 0.49%   |
| 5.18.10  | 2         | 0.49%   |
| 5.4.0    | 1         | 0.24%   |
| 5.19.2   | 1         | 0.24%   |
| 5.19.12  | 1         | 0.24%   |
| 5.19.11  | 1         | 0.24%   |
| 5.18.6   | 1         | 0.24%   |
| 5.18.15  | 1         | 0.24%   |
| 5.18.12  | 1         | 0.24%   |
| 5.17.6   | 1         | 0.24%   |
| 5.17.5   | 1         | 0.24%   |
| 5.17.4   | 1         | 0.24%   |
| 5.17.2   | 1         | 0.24%   |
| 5.17.14  | 1         | 0.24%   |
| 5.16.2   | 1         | 0.24%   |
| 5.16.11  | 1         | 0.24%   |
| 5.16.0   | 1         | 0.24%   |
| 5.15.65  | 1         | 0.24%   |
| 5.15.34  | 1         | 0.24%   |
| 5.15.13  | 1         | 0.24%   |
| 5.11.0   | 1         | 0.24%   |
| 5.10.123 | 1         | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 370       | 90.24%  |
| 5.17    | 13        | 3.17%   |
| 5.18    | 7         | 1.71%   |
| 6.0     | 5         | 1.22%   |
| 5.19    | 5         | 1.22%   |
| 5.13    | 4         | 0.98%   |
| 5.16    | 3         | 0.73%   |
| 5.4     | 1         | 0.24%   |
| 5.11    | 1         | 0.24%   |
| 5.10    | 1         | 0.24%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 404       | 99.75%  |
| aarch64 | 1         | 0.25%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| KDE5       | 400       | 98.52%  |
| GNOME      | 2         | 0.49%   |
| X-Cinnamon | 1         | 0.25%   |
| MATE       | 1         | 0.25%   |
| i3         | 1         | 0.25%   |
| GNUstep    | 1         | 0.25%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 383       | 94.33%  |
| Wayland | 18        | 4.43%   |
| Tty     | 5         | 1.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 300       | 73.71%  |
| Unknown | 76        | 18.67%  |
| GDM3    | 21        | 5.16%   |
| LightDM | 8         | 1.97%   |
| SLiM    | 1         | 0.25%   |
| LXDM    | 1         | 0.25%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 203       | 50%     |
| it_IT   | 27        | 6.65%   |
| de_DE   | 23        | 5.67%   |
| ru_RU   | 19        | 4.68%   |
| fr_FR   | 18        | 4.43%   |
| en_GB   | 17        | 4.19%   |
| en_AU   | 12        | 2.96%   |
| pl_PL   | 9         | 2.22%   |
| pt_BR   | 8         | 1.97%   |
| es_ES   | 8         | 1.97%   |
| en_IN   | 7         | 1.72%   |
| en_CA   | 7         | 1.72%   |
| en_PH   | 5         | 1.23%   |
| en_ZA   | 4         | 0.99%   |
| en_NZ   | 4         | 0.99%   |
| hu_HU   | 3         | 0.74%   |
| es_AR   | 3         | 0.74%   |
| en_SG   | 3         | 0.74%   |
| sl_SI   | 2         | 0.49%   |
| nl_NL   | 2         | 0.49%   |
| es_CL   | 2         | 0.49%   |
| Default | 2         | 0.49%   |
| tr_TR   | 1         | 0.25%   |
| ru_UA   | 1         | 0.25%   |
| nl_BE   | 1         | 0.25%   |
| ko_KR   | 1         | 0.25%   |
| fr_BE   | 1         | 0.25%   |
| et_EE   | 1         | 0.25%   |
| es_MX   | 1         | 0.25%   |
| es_EC   | 1         | 0.25%   |
| es_CR   | 1         | 0.25%   |
| es_CO   | 1         | 0.25%   |
| en_IL   | 1         | 0.25%   |
| en_AG   | 1         | 0.25%   |
| el_GR   | 1         | 0.25%   |
| de_LU   | 1         | 0.25%   |
| de_CH   | 1         | 0.25%   |
| de_AT   | 1         | 0.25%   |
| cs_CZ   | 1         | 0.25%   |
| C       | 1         | 0.25%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 211       | 51.59%  |
| BIOS | 198       | 48.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 364       | 89.66%  |
| Overlay | 19        | 4.68%   |
| Btrfs   | 17        | 4.19%   |
| Xfs     | 3         | 0.74%   |
| Zfs     | 1         | 0.25%   |
| Ext3    | 1         | 0.25%   |
| Ext2    | 1         | 0.25%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 244       | 59.37%  |
| Unknown | 149       | 36.25%  |
| MBR     | 18        | 4.38%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 371       | 90.93%  |
| Yes       | 37        | 9.07%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 244       | 60.1%   |
| Yes       | 162       | 39.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 70        | 17.28%  |
| ASUSTek Computer               | 68        | 16.79%  |
| Hewlett-Packard                | 56        | 13.83%  |
| Dell                           | 45        | 11.11%  |
| Gigabyte Technology            | 29        | 7.16%   |
| MSI                            | 27        | 6.67%   |
| Acer                           | 17        | 4.2%    |
| ASRock                         | 13        | 3.21%   |
| Apple                          | 10        | 2.47%   |
| Toshiba                        | 6         | 1.48%   |
| Samsung Electronics            | 5         | 1.23%   |
| HUAWEI                         | 5         | 1.23%   |
| TUXEDO                         | 3         | 0.74%   |
| Supermicro                     | 3         | 0.74%   |
| Sony                           | 3         | 0.74%   |
| Google                         | 3         | 0.74%   |
| AZW                            | 3         | 0.74%   |
| System76                       | 2         | 0.49%   |
| Shuttle                        | 2         | 0.49%   |
| Panasonic                      | 2         | 0.49%   |
| HONOR                          | 2         | 0.49%   |
| Fujitsu                        | 2         | 0.49%   |
| Biostar                        | 2         | 0.49%   |
| Unknown                        | 2         | 0.49%   |
| ZOTAC                          | 1         | 0.25%   |
| Timi                           | 1         | 0.25%   |
| Tactus                         | 1         | 0.25%   |
| Standard                       | 1         | 0.25%   |
| SLIMBOOK                       | 1         | 0.25%   |
| SK hynix                       | 1         | 0.25%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.25%   |
| Schenker                       | 1         | 0.25%   |
| Razer                          | 1         | 0.25%   |
| Positivo                       | 1         | 0.25%   |
| Pegatron                       | 1         | 0.25%   |
| OEM                            | 1         | 0.25%   |
| Notebook                       | 1         | 0.25%   |
| Microsoft                      | 1         | 0.25%   |
| LG Electronics                 | 1         | 0.25%   |
| JWIPC                          | 1         | 0.25%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 5         | 1.23%   |
| Unknown                            | 5         | 1.23%   |
| Gigabyte B450M DS3H                | 3         | 0.74%   |
| ASUS ROG STRIX B550-F GAMING       | 3         | 0.74%   |
| Supermicro SKAGIT09                | 2         | 0.49%   |
| MSI MS-7C56                        | 2         | 0.49%   |
| MSI MS-7B86                        | 2         | 0.49%   |
| MSI MS-7B84                        | 2         | 0.49%   |
| MSI MS-7B79                        | 2         | 0.49%   |
| Lenovo IdeaPad 5 15ARE05 81YQ      | 2         | 0.49%   |
| HUAWEI CREM-WXX9                   | 2         | 0.49%   |
| HP ProBook 6470b                   | 2         | 0.49%   |
| HP ProBook 440 G8 Notebook PC      | 2         | 0.49%   |
| HP Pavilion Laptop 15-eh1xxx       | 2         | 0.49%   |
| HP Pavilion g6                     | 2         | 0.49%   |
| HP Pavilion dv6                    | 2         | 0.49%   |
| HP OMEN Laptop 15-en0xxx           | 2         | 0.49%   |
| HP EliteBook 845 G7 Notebook PC    | 2         | 0.49%   |
| HP 255 G8 Notebook PC              | 2         | 0.49%   |
| Gigabyte X570 GAMING X             | 2         | 0.49%   |
| Gigabyte B450 I AORUS PRO WIFI     | 2         | 0.49%   |
| Dell XPS 15 9560                   | 2         | 0.49%   |
| AZW SER                            | 2         | 0.49%   |
| ASUS ROG ZENITH EXTREME            | 2         | 0.49%   |
| ASUS ROG STRIX B550-I GAMING       | 2         | 0.49%   |
| Acer Aspire E5-575G                | 2         | 0.49%   |
| ZOTAC ZBOXNANO-CI520NANO/CI540NANO | 1         | 0.25%   |
| TUXEDO Stellaris AMD Gen3 (CZN)    | 1         | 0.25%   |
| TUXEDO Polaris 15 AMD Gen1         | 1         | 0.25%   |
| TUXEDO InfinityBook S 15 Gen6      | 1         | 0.25%   |
| Toshiba TECRA S11                  | 1         | 0.25%   |
| Toshiba Satellite P70-B            | 1         | 0.25%   |
| Toshiba Satellite NB10t-A-102      | 1         | 0.25%   |
| Toshiba Satellite L850             | 1         | 0.25%   |
| Toshiba Satellite L655             | 1         | 0.25%   |
| Toshiba Satellite C650D            | 1         | 0.25%   |
| Timi Mi Laptop Air 12.5            | 1         | 0.25%   |
| Tactus GeoBook 140                 | 1         | 0.25%   |
| System76 Lemur Ultra               | 1         | 0.25%   |
| System76 Kudu Professional         | 1         | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 23        | 5.68%   |
| Lenovo IdeaPad      | 17        | 4.2%    |
| ASUS ROG            | 16        | 3.95%   |
| Dell Latitude       | 13        | 3.21%   |
| HP Pavilion         | 12        | 2.96%   |
| HP ProBook          | 9         | 2.22%   |
| Acer Aspire         | 9         | 2.22%   |
| Dell Inspiron       | 8         | 1.98%   |
| Dell XPS            | 7         | 1.73%   |
| Lenovo ThinkCentre  | 6         | 1.48%   |
| Lenovo ThinkBook    | 6         | 1.48%   |
| HP EliteBook        | 6         | 1.48%   |
| Dell OptiPlex       | 6         | 1.48%   |
| ASUS VivoBook       | 6         | 1.48%   |
| ASUS TUF            | 6         | 1.48%   |
| ASUS PRIME          | 6         | 1.48%   |
| Toshiba Satellite   | 5         | 1.23%   |
| HP Laptop           | 5         | 1.23%   |
| ASUS All            | 5         | 1.23%   |
| Unknown             | 5         | 1.23%   |
| Lenovo Yoga         | 4         | 0.99%   |
| Lenovo Legion       | 4         | 0.99%   |
| Dell Precision      | 4         | 0.99%   |
| HP OMEN             | 3         | 0.74%   |
| HP ENVY             | 3         | 0.74%   |
| Gigabyte X570       | 3         | 0.74%   |
| Gigabyte B450M      | 3         | 0.74%   |
| Dell Vostro         | 3         | 0.74%   |
| ASUS ZenBook        | 3         | 0.74%   |
| ASUS M5A78L-M       | 3         | 0.74%   |
| Acer Predator       | 3         | 0.74%   |
| Supermicro SKAGIT09 | 2         | 0.49%   |
| MSI MS-7C56         | 2         | 0.49%   |
| MSI MS-7B86         | 2         | 0.49%   |
| MSI MS-7B84         | 2         | 0.49%   |
| MSI MS-7B79         | 2         | 0.49%   |
| HUAWEI CREM-WXX9    | 2         | 0.49%   |
| HP ProDesk          | 2         | 0.49%   |
| HP 255              | 2         | 0.49%   |
| Gigabyte H410M      | 2         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 72        | 17.78%  |
| 2021    | 66        | 16.3%   |
| 2019    | 40        | 9.88%   |
| 2018    | 33        | 8.15%   |
| 2012    | 30        | 7.41%   |
| 2022    | 25        | 6.17%   |
| 2016    | 21        | 5.19%   |
| 2014    | 20        | 4.94%   |
| 2017    | 19        | 4.69%   |
| 2013    | 19        | 4.69%   |
| 2011    | 18        | 4.44%   |
| 2015    | 16        | 3.95%   |
| 2010    | 12        | 2.96%   |
| 2008    | 5         | 1.23%   |
| 2009    | 4         | 0.99%   |
| 2007    | 4         | 0.99%   |
| Unknown | 1         | 0.25%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 232       | 57.28%  |
| Desktop        | 145       | 35.8%   |
| Convertible    | 13        | 3.21%   |
| Mini pc        | 6         | 1.48%   |
| All in one     | 3         | 0.74%   |
| Server         | 3         | 0.74%   |
| Tablet         | 2         | 0.49%   |
| System on chip | 1         | 0.25%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 366       | 90.15%  |
| Enabled  | 40        | 9.85%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 402       | 99.26%  |
| Yes  | 3         | 0.74%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 120       | 29.41%  |
| 8.01-16.0   | 87        | 21.32%  |
| 4.01-8.0    | 78        | 19.12%  |
| 32.01-64.0  | 58        | 14.22%  |
| 3.01-4.0    | 36        | 8.82%   |
| 64.01-256.0 | 17        | 4.17%   |
| 24.01-32.0  | 8         | 1.96%   |
| 2.01-3.0    | 3         | 0.74%   |
| 1.01-2.0    | 1         | 0.25%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 121       | 28.4%   |
| 4.01-8.0   | 97        | 22.77%  |
| 3.01-4.0   | 90        | 21.13%  |
| 1.01-2.0   | 84        | 19.72%  |
| 8.01-16.0  | 29        | 6.81%   |
| 0.51-1.0   | 4         | 0.94%   |
| 32.01-64.0 | 1         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 213       | 51.95%  |
| 2      | 123       | 30%     |
| 3      | 37        | 9.02%   |
| 4      | 17        | 4.15%   |
| 5      | 11        | 2.68%   |
| 6      | 5         | 1.22%   |
| 7      | 2         | 0.49%   |
| 11     | 1         | 0.24%   |
| 9      | 1         | 0.24%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 298       | 73.4%   |
| Yes       | 108       | 26.6%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 332       | 81.98%  |
| No        | 73        | 18.02%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 336       | 82.76%  |
| No        | 70        | 17.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 291       | 71.5%   |
| No        | 116       | 28.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 76        | 18.77%  |
| Italy        | 36        | 8.89%   |
| Germany      | 32        | 7.9%    |
| Russia       | 28        | 6.91%   |
| France       | 25        | 6.17%   |
| UK           | 15        | 3.7%    |
| Poland       | 15        | 3.7%    |
| Brazil       | 15        | 3.7%    |
| Spain        | 11        | 2.72%   |
| Australia    | 10        | 2.47%   |
| Switzerland  | 8         | 1.98%   |
| India        | 8         | 1.98%   |
| Netherlands  | 7         | 1.73%   |
| Canada       | 7         | 1.73%   |
| Philippines  | 6         | 1.48%   |
| Slovenia     | 5         | 1.23%   |
| New Zealand  | 5         | 1.23%   |
| Indonesia    | 5         | 1.23%   |
| Hungary      | 5         | 1.23%   |
| Argentina    | 5         | 1.23%   |
| South Africa | 4         | 0.99%   |
| Mexico       | 4         | 0.99%   |
| Estonia      | 4         | 0.99%   |
| Bulgaria     | 4         | 0.99%   |
| Turkey       | 3         | 0.74%   |
| Sweden       | 3         | 0.74%   |
| Singapore    | 3         | 0.74%   |
| Greece       | 3         | 0.74%   |
| Ecuador      | 3         | 0.74%   |
| Czechia      | 3         | 0.74%   |
| Chile        | 3         | 0.74%   |
| Belgium      | 3         | 0.74%   |
| Ukraine      | 2         | 0.49%   |
| Thailand     | 2         | 0.49%   |
| Serbia       | 2         | 0.49%   |
| Portugal     | 2         | 0.49%   |
| Malaysia     | 2         | 0.49%   |
| Ireland      | 2         | 0.49%   |
| Denmark      | 2         | 0.49%   |
| China        | 2         | 0.49%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                    | Computers | Percent |
|-------------------------|-----------|---------|
| Moscow                  | 9         | 2.18%   |
| Milan                   | 9         | 2.18%   |
| Wroclaw                 | 5         | 1.21%   |
| St Petersburg           | 5         | 1.21%   |
| Berlin                  | 5         | 1.21%   |
| Rio de Janeiro          | 4         | 0.97%   |
| Dallas                  | 4         | 0.97%   |
| Washington              | 3         | 0.73%   |
| Vladivostok             | 3         | 0.73%   |
| Turin                   | 3         | 0.73%   |
| Tallinn                 | 3         | 0.73%   |
| Singapore               | 3         | 0.73%   |
| Sao Paulo               | 3         | 0.73%   |
| Paris                   | 3         | 0.73%   |
| Johannesburg            | 3         | 0.73%   |
| Jacksonville            | 3         | 0.73%   |
| Budapest                | 3         | 0.73%   |
| Bougival                | 3         | 0.73%   |
| Bengaluru               | 3         | 0.73%   |
| Auckland                | 3         | 0.73%   |
| Zurich                  | 2         | 0.48%   |
| Vienna                  | 2         | 0.48%   |
| Varna                   | 2         | 0.48%   |
| Sydney                  | 2         | 0.48%   |
| Sofia                   | 2         | 0.48%   |
| Quito                   | 2         | 0.48%   |
| Prague                  | 2         | 0.48%   |
| Parma                   | 2         | 0.48%   |
| Ocala                   | 2         | 0.48%   |
| Nîmes                  | 2         | 0.48%   |
| Murska Sobota           | 2         | 0.48%   |
| Munich                  | 2         | 0.48%   |
| Marseille               | 2         | 0.48%   |
| Madrid                  | 2         | 0.48%   |
| Katowice                | 2         | 0.48%   |
| Katerini                | 2         | 0.48%   |
| Jakarta                 | 2         | 0.48%   |
| Granozzo con Monticello | 2         | 0.48%   |
| Fucecchio               | 2         | 0.48%   |
| Dublin                  | 2         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 102       | 135    | 16.19%  |
| WDC                         | 78        | 107    | 12.38%  |
| Seagate                     | 67        | 116    | 10.63%  |
| Kingston                    | 47        | 53     | 7.46%   |
| Toshiba                     | 42        | 51     | 6.67%   |
| SanDisk                     | 34        | 37     | 5.4%    |
| SK hynix                    | 23        | 25     | 3.65%   |
| Crucial                     | 23        | 28     | 3.65%   |
| Unknown                     | 19        | 24     | 3.02%   |
| Intel                       | 19        | 23     | 3.02%   |
| Hitachi                     | 19        | 19     | 3.02%   |
| Micron Technology           | 13        | 13     | 2.06%   |
| HGST                        | 10        | 11     | 1.59%   |
| KIOXIA                      | 9         | 9      | 1.43%   |
| Patriot                     | 8         | 10     | 1.27%   |
| A-DATA Technology           | 8         | 9      | 1.27%   |
| China                       | 7         | 8      | 1.11%   |
| Apple                       | 7         | 8      | 1.11%   |
| PNY                         | 6         | 7      | 0.95%   |
| Phison                      | 5         | 5      | 0.79%   |
| Lexar                       | 4         | 4      | 0.63%   |
| Emtec                       | 4         | 4      | 0.63%   |
| Verbatim                    | 3         | 3      | 0.48%   |
| Transcend                   | 3         | 4      | 0.48%   |
| SSSTC                       | 3         | 3      | 0.48%   |
| Phison Electronics          | 3         | 3      | 0.48%   |
| Micron/Crucial Technology   | 3         | 4      | 0.48%   |
| LITEON                      | 3         | 3      | 0.48%   |
| Unknown                     | 3         | 3      | 0.48%   |
| USB3.0                      | 2         | 2      | 0.32%   |
| Smart                       | 2         | 2      | 0.32%   |
| Silicon Motion              | 2         | 2      | 0.32%   |
| Realtek Semiconductor       | 2         | 2      | 0.32%   |
| Plextor                     | 2         | 2      | 0.32%   |
| Netac                       | 2         | 2      | 0.32%   |
| LITEONIT                    | 2         | 2      | 0.32%   |
| KODAK                       | 2         | 2      | 0.32%   |
| Kingston Technology Company | 2         | 2      | 0.32%   |
| JMicron Technology          | 2         | 2      | 0.32%   |
| Intenso                     | 2         | 2      | 0.32%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 10        | 1.43%   |
| Samsung SSD 860 EVO 500GB          | 7         | 1%      |
| Seagate ST4000DM004-2CV104 4TB     | 6         | 0.86%   |
| Crucial CT500MX500SSD1 500GB       | 6         | 0.86%   |
| Kingston SA2000M81000G 1TB         | 5         | 0.71%   |
| WDC WDS240G2G0A-00JH30 240GB SSD   | 4         | 0.57%   |
| Toshiba MQ01ABD100 1TB             | 4         | 0.57%   |
| Toshiba DT01ACA100 1TB             | 4         | 0.57%   |
| SanDisk NVMe SSD Drive 500GB       | 4         | 0.57%   |
| Samsung SSD 980 PRO 1TB            | 4         | 0.57%   |
| Samsung SSD 970 EVO Plus 500GB     | 4         | 0.57%   |
| Samsung SSD 860 QVO 1TB            | 4         | 0.57%   |
| Samsung SSD 850 EVO 500GB          | 4         | 0.57%   |
| Samsung NVMe SSD Drive 500GB       | 4         | 0.57%   |
| Hitachi HTS547550A9E384 500GB      | 4         | 0.57%   |
| Crucial CT500P2SSD8 500GB          | 4         | 0.57%   |
| Crucial CT240BX500SSD1 240GB       | 4         | 0.57%   |
| WDC WD10EZEX-22MFCA0 1TB           | 3         | 0.43%   |
| Toshiba MQ04ABF100 1TB             | 3         | 0.43%   |
| SK hynix NVMe SSD Drive 512GB      | 3         | 0.43%   |
| Seagate ST2000LM007-1R8174 2TB     | 3         | 0.43%   |
| Seagate ST1000LM035-1RK172 1TB     | 3         | 0.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 3         | 0.43%   |
| Seagate Expansion 2TB              | 3         | 0.43%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB | 3         | 0.43%   |
| Samsung SSD 980 500GB              | 3         | 0.43%   |
| Samsung SSD 980 1TB                | 3         | 0.43%   |
| Samsung SSD 970 EVO Plus 250GB     | 3         | 0.43%   |
| Samsung SSD 870 EVO 1TB            | 3         | 0.43%   |
| Samsung SSD 860 EVO 1TB            | 3         | 0.43%   |
| Samsung SSD 850 EVO 250GB          | 3         | 0.43%   |
| Samsung NVMe SSD Drive 512GB       | 3         | 0.43%   |
| Samsung HD103SI 1TB                | 3         | 0.43%   |
| Patriot Burst 240GB SSD            | 3         | 0.43%   |
| Kingston SV300S37A120G 120GB SSD   | 3         | 0.43%   |
| Kingston SA400S37480G 480GB SSD    | 3         | 0.43%   |
| Kingston SA400S37120G 120GB SSD    | 3         | 0.43%   |
| Crucial CT1000BX500SSD1 1TB        | 3         | 0.43%   |
| Unknown                            | 3         | 0.43%   |
| WDC WD5000AADS-00S9B0 500GB        | 2         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 64        | 108    | 33.68%  |
| WDC                 | 53        | 67     | 27.89%  |
| Toshiba             | 26        | 30     | 13.68%  |
| Hitachi             | 19        | 19     | 10%     |
| HGST                | 10        | 11     | 5.26%   |
| Samsung Electronics | 8         | 9      | 4.21%   |
| USB3.0              | 2         | 2      | 1.05%   |
| Unknown             | 1         | 1      | 0.53%   |
| SAGE                | 1         | 1      | 0.53%   |
| SABRENT             | 1         | 3      | 0.53%   |
| KESU                | 1         | 1      | 0.53%   |
| JMicron Technology  | 1         | 1      | 0.53%   |
| IET                 | 1         | 1      | 0.53%   |
| HPE                 | 1         | 6      | 0.53%   |
| HGST HTS            | 1         | 1      | 0.53%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 54        | 67     | 24.66%  |
| Kingston            | 31        | 33     | 14.16%  |
| SanDisk             | 18        | 19     | 8.22%   |
| Crucial             | 18        | 21     | 8.22%   |
| WDC                 | 12        | 17     | 5.48%   |
| Patriot             | 8         | 10     | 3.65%   |
| Intel               | 6         | 6      | 2.74%   |
| China               | 6         | 7      | 2.74%   |
| A-DATA Technology   | 5         | 6      | 2.28%   |
| Toshiba             | 4         | 6      | 1.83%   |
| PNY                 | 4         | 5      | 1.83%   |
| Micron Technology   | 4         | 4      | 1.83%   |
| Apple               | 4         | 4      | 1.83%   |
| Verbatim            | 3         | 3      | 1.37%   |
| LITEON              | 3         | 3      | 1.37%   |
| Lexar               | 3         | 3      | 1.37%   |
| Transcend           | 2         | 2      | 0.91%   |
| Smart               | 2         | 2      | 0.91%   |
| SK hynix            | 2         | 2      | 0.91%   |
| Plextor             | 2         | 2      | 0.91%   |
| Netac               | 2         | 2      | 0.91%   |
| LITEONIT            | 2         | 2      | 0.91%   |
| KODAK               | 2         | 2      | 0.91%   |
| Emtec               | 2         | 2      | 0.91%   |
| tecmiyo             | 1         | 2      | 0.46%   |
| Team                | 1         | 1      | 0.46%   |
| Smartbuy            | 1         | 1      | 0.46%   |
| OCZ                 | 1         | 1      | 0.46%   |
| Maxtor              | 1         | 1      | 0.46%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.46%   |
| KingSpec            | 1         | 1      | 0.46%   |
| KingFast            | 1         | 1      | 0.46%   |
| Intenso             | 1         | 1      | 0.46%   |
| INNOVATION IT       | 1         | 1      | 0.46%   |
| INDMEM              | 1         | 1      | 0.46%   |
| Hewlett-Packard     | 1         | 1      | 0.46%   |
| GOODRAM             | 1         | 1      | 0.46%   |
| Drevo               | 1         | 1      | 0.46%   |
| Dogfish             | 1         | 1      | 0.46%   |
| Corsair             | 1         | 1      | 0.46%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 188       | 251    | 33.63%  |
| NVMe    | 187       | 250    | 33.45%  |
| HDD     | 156       | 261    | 27.91%  |
| MMC     | 21        | 25     | 3.76%   |
| Unknown | 7         | 7      | 1.25%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 257       | 477    | 52.24%  |
| NVMe | 186       | 248    | 37.8%   |
| SAS  | 28        | 44     | 5.69%   |
| MMC  | 21        | 25     | 4.27%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 189       | 269    | 51.5%   |
| 0.51-1.0   | 101       | 131    | 27.52%  |
| 1.01-2.0   | 35        | 45     | 9.54%   |
| 3.01-4.0   | 21        | 41     | 5.72%   |
| 4.01-10.0  | 10        | 13     | 2.72%   |
| 2.01-3.0   | 9         | 11     | 2.45%   |
| 10.01-20.0 | 2         | 2      | 0.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 90        | 21.74%  |
| 251-500        | 88        | 21.26%  |
| 501-1000       | 76        | 18.36%  |
| 1001-2000      | 54        | 13.04%  |
| More than 3000 | 30        | 7.25%   |
| 2001-3000      | 27        | 6.52%   |
| 51-100         | 23        | 5.56%   |
| 1-20           | 17        | 4.11%   |
| 21-50          | 8         | 1.93%   |
| Unknown        | 1         | 0.24%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 103       | 24.88%  |
| 101-250        | 70        | 16.91%  |
| 21-50          | 62        | 14.98%  |
| 251-500        | 52        | 12.56%  |
| 51-100         | 43        | 10.39%  |
| 501-1000       | 41        | 9.9%    |
| 1001-2000      | 19        | 4.59%   |
| More than 3000 | 15        | 3.62%   |
| 2001-3000      | 8         | 1.93%   |
| Unknown        | 1         | 0.24%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                               | Computers | Drives | Percent |
|-----------------------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB                            | 2         | 2      | 5.41%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD                    | 1         | 1      | 2.7%    |
| WDC WD5000AVVS-63M8B0 500GB                         | 1         | 1      | 2.7%    |
| WDC WD10EZEX-22MFCA0 1TB                            | 1         | 1      | 2.7%    |
| WDC WD10EZEX-08M2NA0 1TB                            | 1         | 1      | 2.7%    |
| Toshiba MQ04ABF100 1TB                              | 1         | 1      | 2.7%    |
| Toshiba MQ01ABD075 752GB                            | 1         | 1      | 2.7%    |
| tecmiyo SATA SSD 128GB                              | 1         | 2      | 2.7%    |
| SK hynix BC711 HFM512GD3JX013N 512GB                | 1         | 1      | 2.7%    |
| SK hynix BC711 HFM256GD3JX013N 256GB                | 1         | 1      | 2.7%    |
| Seagate ST9750420AS 752GB                           | 1         | 1      | 2.7%    |
| Seagate ST500LT012-9WS142 500GB                     | 1         | 1      | 2.7%    |
| Seagate ST500LM012 HN-M500MBB 500GB                 | 1         | 1      | 2.7%    |
| Seagate ST500DM002-1BD142 500GB                     | 1         | 1      | 2.7%    |
| Seagate ST320LT020-9YG142 320GB                     | 1         | 1      | 2.7%    |
| Seagate ST3160827AS 160GB                           | 1         | 1      | 2.7%    |
| Seagate ST31500341AS 1TB                            | 1         | 2      | 2.7%    |
| Seagate ST31000524AS 1TB                            | 1         | 2      | 2.7%    |
| Seagate ST2000LM007-1R8174 2TB                      | 1         | 1      | 2.7%    |
| Seagate ST1000DM003-1SB102 1TB                      | 1         | 1      | 2.7%    |
| Seagate ST1000DM003-1CH162 1TB                      | 1         | 1      | 2.7%    |
| SanDisk SSD PLUS 240GB                              | 1         | 1      | 2.7%    |
| Samsung Electronics SSD 870 EVO 1TB                 | 1         | 1      | 2.7%    |
| Samsung Electronics SSD 840 Series 250GB            | 1         | 1      | 2.7%    |
| Samsung Electronics HM321HI 320GB                   | 1         | 1      | 2.7%    |
| Samsung Electronics HD103SI 1TB                     | 1         | 1      | 2.7%    |
| Micron Technology MTFDDAV256TDL-1AW1ZABHA 256GB SSD | 1         | 1      | 2.7%    |
| Hitachi HTS723232A7A364 320GB                       | 1         | 1      | 2.7%    |
| Hitachi HTS547550A9E384 500GB                       | 1         | 1      | 2.7%    |
| Hitachi HTS545050B9A300 500GB                       | 1         | 1      | 2.7%    |
| Hitachi HDP725050GLA360 500GB                       | 1         | 1      | 2.7%    |
| Hitachi HCT721010SLA360 1TB                         | 1         | 1      | 2.7%    |
| HGST HTS545050A7E680 500GB                          | 1         | 1      | 2.7%    |
| Crucial CT128M550SSD1 128GB                         | 1         | 1      | 2.7%    |
| BAITITON BT58SSD09S 240GB                           | 1         | 1      | 2.7%    |
| A-DATA Technology XM11 256GB-V2 SSD                 | 1         | 1      | 2.7%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 13     | 27.78%  |
| Hitachi             | 5         | 5      | 13.89%  |
| WDC                 | 4         | 4      | 11.11%  |
| Samsung Electronics | 4         | 4      | 11.11%  |
| HGST                | 3         | 3      | 8.33%   |
| Toshiba             | 2         | 2      | 5.56%   |
| SK hynix            | 2         | 2      | 5.56%   |
| tecmiyo             | 1         | 2      | 2.78%   |
| SanDisk             | 1         | 1      | 2.78%   |
| Micron Technology   | 1         | 1      | 2.78%   |
| Crucial             | 1         | 1      | 2.78%   |
| BAITITON            | 1         | 1      | 2.78%   |
| A-DATA Technology   | 1         | 1      | 2.78%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 13     | 40%     |
| Hitachi             | 5         | 5      | 20%     |
| WDC                 | 3         | 3      | 12%     |
| HGST                | 3         | 3      | 12%     |
| Toshiba             | 2         | 2      | 8%      |
| Samsung Electronics | 2         | 2      | 8%      |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 24        | 28     | 70.59%  |
| SSD  | 8         | 10     | 23.53%  |
| NVMe | 2         | 2      | 5.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Samsung Electronics HD502IJ 500GB | 1         | 1      | 50%     |
| Hitachi HTS547550A9E384 500GB     | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1         | 1      | 50%     |
| Hitachi             | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 221       | 376    | 49.33%  |
| Detected | 192       | 376    | 42.86%  |
| Malfunc  | 34        | 40     | 7.59%   |
| Failed   | 1         | 2      | 0.22%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 230       | 41.07%  |
| AMD                            | 104       | 18.57%  |
| Samsung Electronics            | 50        | 8.93%   |
| SanDisk                        | 36        | 6.43%   |
| SK hynix                       | 21        | 3.75%   |
| Kingston Technology Company    | 20        | 3.57%   |
| Toshiba America Info Systems   | 14        | 2.5%    |
| Phison Electronics             | 12        | 2.14%   |
| ASMedia Technology             | 10        | 1.79%   |
| Micron/Crucial Technology      | 9         | 1.61%   |
| Micron Technology              | 9         | 1.61%   |
| KIOXIA                         | 8         | 1.43%   |
| JMicron Technology             | 5         | 0.89%   |
| Solid State Storage Technology | 4         | 0.71%   |
| ADATA Technology               | 4         | 0.71%   |
| Silicon Motion                 | 3         | 0.54%   |
| Seagate Technology             | 3         | 0.54%   |
| Marvell Technology Group       | 3         | 0.54%   |
| Apple                          | 3         | 0.54%   |
| Realtek Semiconductor          | 2         | 0.36%   |
| LSI Logic / Symbios Logic      | 2         | 0.36%   |
| Zhaoxin                        | 1         | 0.18%   |
| VIA Technologies               | 1         | 0.18%   |
| Unknown                        | 1         | 0.18%   |
| Union Memory (Shenzhen)        | 1         | 0.18%   |
| Silicon Image                  | 1         | 0.18%   |
| Shenzhen Longsys Electronics   | 1         | 0.18%   |
| Nvidia                         | 1         | 0.18%   |
| Hewlett-Packard                | 1         | 0.18%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 73        | 11.44%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 23        | 3.61%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 23        | 3.61%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 22        | 3.45%   |
| Intel Volume Management Device NVMe RAID Controller                            | 21        | 3.29%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 19        | 2.98%   |
| AMD 400 Series Chipset SATA Controller                                         | 19        | 2.98%   |
| AMD 500 Series Chipset SATA Controller                                         | 14        | 2.19%   |
| Samsung NVMe SSD Controller 980                                                | 13        | 2.04%   |
| SK hynix Gold P31 SSD                                                          | 12        | 1.88%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 12        | 1.88%   |
| SanDisk Non-Volatile memory controller                                         | 11        | 1.72%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 11        | 1.72%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 10        | 1.57%   |
| Micron Non-Volatile memory controller                                          | 9         | 1.41%   |
| Intel Tiger Lake-LP SATA Controller                                            | 9         | 1.41%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 9         | 1.41%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 9         | 1.41%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 9         | 1.41%   |
| Kingston Company Company Non-Volatile memory controller                        | 8         | 1.25%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 8         | 1.25%   |
| Phison E12 NVMe Controller                                                     | 7         | 1.1%    |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 7         | 1.1%    |
| Intel SSD 660P Series                                                          | 7         | 1.1%    |
| Intel Comet Lake SATA AHCI Controller                                          | 7         | 1.1%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 7         | 1.1%    |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 7         | 1.1%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 6         | 0.94%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 6         | 0.94%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 6         | 0.94%   |
| Kingston Company A2000 NVMe SSD                                                | 6         | 0.94%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 6         | 0.94%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 6         | 0.94%   |
| SK hynix Non-Volatile memory controller                                        | 5         | 0.78%   |
| Kingston Company OM3PDP3 NVMe SSD                                              | 5         | 0.78%   |
| Intel SATA Controller [RAID mode]                                              | 5         | 0.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 5         | 0.78%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 5         | 0.78%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 5         | 0.78%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 293       | 53.18%  |
| NVMe | 186       | 33.76%  |
| RAID | 43        | 7.8%    |
| IDE  | 29        | 5.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 274       | 67.65%  |
| AMD          | 129       | 31.85%  |
| CentaurHauls | 1         | 0.25%   |
| ARM          | 1         | 0.25%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 10        | 2.47%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 9         | 2.22%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 9         | 2.22%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 8         | 1.98%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 7         | 1.73%   |
| Intel 12th Gen Core i7-12700H           | 7         | 1.73%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 6         | 1.48%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 6         | 1.48%   |
| AMD Ryzen 5 5600X 6-Core Processor      | 6         | 1.48%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 5         | 1.23%   |
| Intel Celeron N4020 CPU @ 1.10GHz       | 5         | 1.23%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 4         | 0.99%   |
| Intel Core i7-10510U CPU @ 1.80GHz      | 4         | 0.99%   |
| AMD Ryzen 9 5900HX with Radeon Graphics | 4         | 0.99%   |
| AMD Ryzen 5 5500U with Radeon Graphics  | 4         | 0.99%   |
| Intel Core i7-4790K CPU @ 4.00GHz       | 3         | 0.74%   |
| Intel Core i7-4790 CPU @ 3.60GHz        | 3         | 0.74%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz      | 3         | 0.74%   |
| Intel Core i7-3632QM CPU @ 2.20GHz      | 3         | 0.74%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 3         | 0.74%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 3         | 0.74%   |
| Intel Core i5-10400F CPU @ 2.90GHz      | 3         | 0.74%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 3         | 0.74%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 3         | 0.74%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 3         | 0.74%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 3         | 0.74%   |
| AMD Ryzen 9 5950X 16-Core Processor     | 3         | 0.74%   |
| AMD Ryzen 9 5900X 12-Core Processor     | 3         | 0.74%   |
| AMD Ryzen 7 5700G with Radeon Graphics  | 3         | 0.74%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 3         | 0.74%   |
| AMD Ryzen 7 3700X 8-Core Processor      | 3         | 0.74%   |
| AMD Ryzen 5 4600H with Radeon Graphics  | 3         | 0.74%   |
| AMD Ryzen 5 3600 6-Core Processor       | 3         | 0.74%   |
| AMD Ryzen 5 2600X Six-Core Processor    | 3         | 0.74%   |
| Intel Pentium CPU G2020 @ 2.90GHz       | 2         | 0.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 2         | 0.49%   |
| Intel Core i7-7700K CPU @ 4.20GHz       | 2         | 0.49%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 2         | 0.49%   |
| Intel Core i7-6700 CPU @ 3.40GHz        | 2         | 0.49%   |
| Intel Core i7-6600U CPU @ 2.60GHz       | 2         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 89        | 21.98%  |
| Intel Core i5           | 64        | 15.8%   |
| Other                   | 54        | 13.33%  |
| AMD Ryzen 7             | 39        | 9.63%   |
| AMD Ryzen 5             | 38        | 9.38%   |
| Intel Celeron           | 16        | 3.95%   |
| AMD Ryzen 9             | 15        | 3.7%    |
| Intel Core i3           | 13        | 3.21%   |
| Intel Xeon              | 10        | 2.47%   |
| Intel Pentium           | 9         | 2.22%   |
| Intel Core 2 Duo        | 9         | 2.22%   |
| AMD Ryzen 3             | 8         | 1.98%   |
| AMD Ryzen 7 PRO         | 5         | 1.23%   |
| AMD FX                  | 4         | 0.99%   |
| Intel Core i9           | 3         | 0.74%   |
| AMD Ryzen Threadripper  | 3         | 0.74%   |
| Intel Pentium Silver    | 2         | 0.49%   |
| Intel Core 2 Quad       | 2         | 0.49%   |
| AMD Phenom II X2        | 2         | 0.49%   |
| AMD Opteron             | 2         | 0.49%   |
| AMD E                   | 2         | 0.49%   |
| AMD A6                  | 2         | 0.49%   |
| AMD A4                  | 2         | 0.49%   |
| Intel Pentium Gold      | 1         | 0.25%   |
| Intel Core m3           | 1         | 0.25%   |
| Intel Core 2            | 1         | 0.25%   |
| Intel Celeron Dual-Core | 1         | 0.25%   |
| Intel Atom              | 1         | 0.25%   |
| AMD Ryzen 5 PRO         | 1         | 0.25%   |
| AMD Phenom II X6        | 1         | 0.25%   |
| AMD Phenom II X4        | 1         | 0.25%   |
| AMD E1                  | 1         | 0.25%   |
| AMD Athlon II X2        | 1         | 0.25%   |
| AMD A8                  | 1         | 0.25%   |
| AMD A10                 | 1         | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 153       | 37.78%  |
| 2       | 100       | 24.69%  |
| 8       | 60        | 14.81%  |
| 6       | 60        | 14.81%  |
| 12      | 10        | 2.47%   |
| 14      | 8         | 1.98%   |
| 16      | 7         | 1.73%   |
| 10      | 4         | 0.99%   |
| 5       | 1         | 0.25%   |
| 1       | 1         | 0.25%   |
| Unknown | 1         | 0.25%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 403       | 99.51%  |
| 2       | 1         | 0.25%   |
| Unknown | 1         | 0.25%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 324       | 79.8%   |
| 1       | 81        | 19.95%  |
| Unknown | 1         | 0.25%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 405       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 172       | 41.85%  |
| 0x806c1    | 17        | 4.14%   |
| 0x306a9    | 17        | 4.14%   |
| 0x0a50000c | 17        | 4.14%   |
| 0x306c3    | 12        | 2.92%   |
| 0x08600106 | 11        | 2.68%   |
| 0x906ea    | 9         | 2.19%   |
| 0x906a3    | 8         | 1.95%   |
| 0x08701021 | 8         | 1.95%   |
| 0x08608103 | 8         | 1.95%   |
| 0x806ec    | 7         | 1.7%    |
| 0x806ea    | 7         | 1.7%    |
| 0x806e9    | 6         | 1.46%   |
| 0x906e9    | 5         | 1.22%   |
| 0x406e3    | 5         | 1.22%   |
| 0x206a7    | 5         | 1.22%   |
| 0x08608102 | 4         | 0.97%   |
| 0x0800820d | 4         | 0.97%   |
| 0x010000c8 | 4         | 0.97%   |
| 0xa0653    | 3         | 0.73%   |
| 0xa0652    | 3         | 0.73%   |
| 0x906ed    | 3         | 0.73%   |
| 0x806d1    | 3         | 0.73%   |
| 0x406f1    | 3         | 0.73%   |
| 0x40651    | 3         | 0.73%   |
| 0x1067a    | 3         | 0.73%   |
| 0x0a201205 | 3         | 0.73%   |
| 0x0a201016 | 3         | 0.73%   |
| 0x08600103 | 3         | 0.73%   |
| 0x08108109 | 3         | 0.73%   |
| 0xa0655    | 2         | 0.49%   |
| 0x906a4    | 2         | 0.49%   |
| 0x90672    | 2         | 0.49%   |
| 0x806c2    | 2         | 0.49%   |
| 0x706a8    | 2         | 0.49%   |
| 0x6fb      | 2         | 0.49%   |
| 0x506e3    | 2         | 0.49%   |
| 0x506c9    | 2         | 0.49%   |
| 0x40661    | 2         | 0.49%   |
| 0x20652    | 2         | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 59        | 14.53%  |
| Zen 3            | 42        | 10.34%  |
| Haswell          | 37        | 9.11%   |
| IvyBridge        | 34        | 8.37%   |
| TigerLake        | 30        | 7.39%   |
| Zen 2            | 28        | 6.9%    |
| Unknown          | 25        | 6.16%   |
| Zen+             | 18        | 4.43%   |
| Skylake          | 17        | 4.19%   |
| SandyBridge      | 13        | 3.2%    |
| Alderlake Hybrid | 12        | 2.96%   |
| CometLake        | 11        | 2.71%   |
| Goldmont plus    | 10        | 2.46%   |
| Zen              | 8         | 1.97%   |
| Penryn           | 8         | 1.97%   |
| Piledriver       | 7         | 1.72%   |
| Westmere         | 6         | 1.48%   |
| K10              | 6         | 1.48%   |
| Nehalem          | 5         | 1.23%   |
| Icelake          | 5         | 1.23%   |
| Core             | 5         | 1.23%   |
| Broadwell        | 5         | 1.23%   |
| Silvermont       | 4         | 0.99%   |
| Goldmont         | 4         | 0.99%   |
| Excavator        | 2         | 0.49%   |
| Bobcat           | 2         | 0.49%   |
| Steamroller      | 1         | 0.25%   |
| Puma             | 1         | 0.25%   |
| K10 Llano        | 1         | 0.25%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 202       | 40.81%  |
| Nvidia                     | 161       | 32.53%  |
| AMD                        | 127       | 25.66%  |
| Matrox Electronics Systems | 3         | 0.61%   |
| Zhaoxin                    | 1         | 0.2%    |
| ASPEED Technology          | 1         | 0.2%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 26        | 5.18%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 22        | 4.38%   |
| AMD Cezanne                                                                           | 19        | 3.78%   |
| AMD Renoir                                                                            | 16        | 3.19%   |
| AMD Lucienne                                                                          | 12        | 2.39%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                    | 11        | 2.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 11        | 2.19%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 10        | 1.99%   |
| Intel UHD Graphics 620                                                                | 9         | 1.79%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 9         | 1.79%   |
| Intel HD Graphics 620                                                                 | 9         | 1.79%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 9         | 1.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 9         | 1.79%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 8         | 1.59%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 8         | 1.59%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 8         | 1.59%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                       | 7         | 1.39%   |
| Intel HD Graphics 630                                                                 | 7         | 1.39%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 7         | 1.39%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 7         | 1.39%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                               | 5         | 1%      |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 5         | 1%      |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                                 | 4         | 0.8%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                   | 4         | 0.8%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                               | 4         | 0.8%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                                  | 4         | 0.8%    |
| Intel HD Graphics 530                                                                 | 4         | 0.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 4         | 0.8%    |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 4         | 0.8%    |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                            | 3         | 0.6%    |
| Nvidia GT218 [GeForce 210]                                                            | 3         | 0.6%    |
| Nvidia GP108 [GeForce GT 1030]                                                        | 3         | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 3         | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 3 GB Max-Q]                                           | 3         | 0.6%    |
| Nvidia GP104 [GeForce GTX 1070]                                                       | 3         | 0.6%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                            | 3         | 0.6%    |
| Nvidia GA104 [Geforce RTX 3070 Ti Laptop GPU]                                         | 3         | 0.6%    |
| Intel Tiger Lake UHD Graphics                                                         | 3         | 0.6%    |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                | 3         | 0.6%    |
| Intel HD Graphics 500                                                                 | 3         | 0.6%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 130       | 32.1%   |
| 1 x Nvidia               | 91        | 22.47%  |
| 1 x AMD                  | 90        | 22.22%  |
| Intel + Nvidia           | 50        | 12.35%  |
| Intel + AMD              | 15        | 3.7%    |
| AMD + Nvidia             | 15        | 3.7%    |
| 2 x AMD                  | 4         | 0.99%   |
| Other                    | 2         | 0.49%   |
| 2 x Nvidia               | 2         | 0.49%   |
| 1 x Zhaoxin              | 1         | 0.25%   |
| Nvidia + Matrox          | 1         | 0.25%   |
| Nvidia + ASPEED          | 1         | 0.25%   |
| 1 x Matrox               | 1         | 0.25%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.25%   |
| AMD + Matrox             | 1         | 0.25%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 274       | 67.65%  |
| Proprietary | 119       | 29.38%  |
| Unknown     | 12        | 2.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 247       | 60.24%  |
| 0.01-0.5   | 38        | 9.27%   |
| 1.01-2.0   | 35        | 8.54%   |
| 3.01-4.0   | 24        | 5.85%   |
| 7.01-8.0   | 21        | 5.12%   |
| 0.51-1.0   | 18        | 4.39%   |
| 5.01-6.0   | 16        | 3.9%    |
| 8.01-16.0  | 7         | 1.71%   |
| 16.01-24.0 | 2         | 0.49%   |
| 4.01-5.0   | 1         | 0.24%   |
| 2.01-3.0   | 1         | 0.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 63        | 13.29%  |
| AU Optronics            | 50        | 10.55%  |
| Chimei Innolux          | 46        | 9.7%    |
| BOE                     | 46        | 9.7%    |
| LG Display              | 36        | 7.59%   |
| Dell                    | 27        | 5.7%    |
| Goldstar                | 26        | 5.49%   |
| Hewlett-Packard         | 23        | 4.85%   |
| Acer                    | 17        | 3.59%   |
| BenQ                    | 14        | 2.95%   |
| Philips                 | 13        | 2.74%   |
| AOC                     | 13        | 2.74%   |
| Sharp                   | 11        | 2.32%   |
| Apple                   | 8         | 1.69%   |
| Iiyama                  | 6         | 1.27%   |
| Sony                    | 5         | 1.05%   |
| Lenovo                  | 5         | 1.05%   |
| InfoVision              | 5         | 1.05%   |
| CSO                     | 5         | 1.05%   |
| Chi Mei Optoelectronics | 5         | 1.05%   |
| Ancor Communications    | 5         | 1.05%   |
| ASUSTek Computer        | 4         | 0.84%   |
| NEC Computers           | 3         | 0.63%   |
| Vizio                   | 2         | 0.42%   |
| PANDA                   | 2         | 0.42%   |
| Panasonic               | 2         | 0.42%   |
| MSI                     | 2         | 0.42%   |
| LG Electronics          | 2         | 0.42%   |
| Idek Iiyama             | 2         | 0.42%   |
| HKC                     | 2         | 0.42%   |
| Gigabyte Technology     | 2         | 0.42%   |
| Eizo                    | 2         | 0.42%   |
| Denver                  | 2         | 0.42%   |
| Xiaomi                  | 1         | 0.21%   |
| Vita                    | 1         | 0.21%   |
| Unknown                 | 1         | 0.21%   |
| Sunplus                 | 1         | 0.21%   |
| STD                     | 1         | 0.21%   |
| SLD                     | 1         | 0.21%   |
| Sceptre Tech            | 1         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 5         | 1.02%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 1.02%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 3         | 0.61%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch    | 3         | 0.61%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 3         | 0.61%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch        | 3         | 0.61%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 3         | 0.61%   |
| Chimei Innolux LCD Monitor CMN176C 1920x1080 381x214mm 17.2-inch         | 3         | 0.61%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 3         | 0.61%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 3         | 0.61%   |
| AOC 27G2G3 AOC2702 1920x1080 598x336mm 27.0-inch                         | 3         | 0.61%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 2         | 0.41%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch      | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 2         | 0.41%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch    | 2         | 0.41%   |
| Philips FTV PHL01EA 1920x1080 640x360mm 28.9-inch                        | 2         | 0.41%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 2         | 0.41%   |
| LG Display LCD Monitor LGD069A 1920x1080 344x194mm 15.5-inch             | 2         | 0.41%   |
| LG Display LCD Monitor LGD068D 1920x1080 309x174mm 14.0-inch             | 2         | 0.41%   |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 2         | 0.41%   |
| LG Display LCD Monitor LGD0323 1920x1080 345x194mm 15.6-inch             | 2         | 0.41%   |
| LG Display LCD Monitor LGD02F2 1366x768 344x194mm 15.5-inch              | 2         | 0.41%   |
| Hewlett-Packard 24w HPN3431 1920x1080 527x296mm 23.8-inch                | 2         | 0.41%   |
| Goldstar 22EA53 GSM59A5 1920x1080 477x268mm 21.5-inch                    | 2         | 0.41%   |
| Dell P2719H DEL4184 1920x1080 598x336mm 27.0-inch                        | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch         | 2         | 0.41%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch         | 2         | 0.41%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A3 1366x768 344x193mm 15.5-inch | 2         | 0.41%   |
| BOE LCD Monitor BOE092F 2520x1680 338x226mm 16.0-inch                    | 2         | 0.41%   |
| BOE LCD Monitor BOE08B9 1920x1080 344x194mm 15.5-inch                    | 2         | 0.41%   |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 2         | 0.41%   |
| BOE LCD Monitor BOE069B 1600x900 382x215mm 17.3-inch                     | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO82ED 1920x1080 344x194mm 15.5-inch           | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch            | 2         | 0.41%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch           | 2         | 0.41%   |
| AOC U3277WB AOC3277 3840x2160 698x393mm 31.5-inch                        | 2         | 0.41%   |
| Acer VG240Y ACR06BF 1920x1080 527x296mm 23.8-inch                        | 2         | 0.41%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 228       | 51.58%  |
| 1366x768 (WXGA)    | 55        | 12.44%  |
| 3840x2160 (4K)     | 34        | 7.69%   |
| 2560x1440 (QHD)    | 25        | 5.66%   |
| 1920x1200 (WUXGA)  | 16        | 3.62%   |
| 1600x900 (HD+)     | 13        | 2.94%   |
| 2560x1600          | 10        | 2.26%   |
| 1680x1050 (WSXGA+) | 9         | 2.04%   |
| 2880x1800          | 8         | 1.81%   |
| 1280x1024 (SXGA)   | 8         | 1.81%   |
| 2560x1080          | 6         | 1.36%   |
| 3440x1440          | 4         | 0.9%    |
| 1440x900 (WXGA+)   | 4         | 0.9%    |
| 1280x800 (WXGA)    | 3         | 0.68%   |
| 2520x1680          | 2         | 0.45%   |
| 2240x1400          | 2         | 0.45%   |
| 1280x720 (HD)      | 2         | 0.45%   |
| 1024x768 (XGA)     | 2         | 0.45%   |
| 3840x1200          | 1         | 0.23%   |
| 3840x1080          | 1         | 0.23%   |
| 3600x1200          | 1         | 0.23%   |
| 3072x1920          | 1         | 0.23%   |
| 2736x1824          | 1         | 0.23%   |
| 2288x1287          | 1         | 0.23%   |
| 2160x1440          | 1         | 0.23%   |
| 2160x1350          | 1         | 0.23%   |
| 1920x540           | 1         | 0.23%   |
| 1360x768           | 1         | 0.23%   |
| Unknown            | 1         | 0.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 117       | 24.79%  |
| 24      | 49        | 10.38%  |
| 27      | 44        | 9.32%   |
| 14      | 38        | 8.05%   |
| 13      | 37        | 7.84%   |
| 23      | 28        | 5.93%   |
| 21      | 27        | 5.72%   |
| 17      | 20        | 4.24%   |
| 31      | 15        | 3.18%   |
| 16      | 13        | 2.75%   |
| 19      | 11        | 2.33%   |
| 34      | 9         | 1.91%   |
| 22      | 8         | 1.69%   |
| 12      | 6         | 1.27%   |
| 11      | 6         | 1.27%   |
| Unknown | 6         | 1.27%   |
| 18      | 5         | 1.06%   |
| 32      | 4         | 0.85%   |
| 46      | 3         | 0.64%   |
| 20      | 3         | 0.64%   |
| 72      | 2         | 0.42%   |
| 65      | 2         | 0.42%   |
| 60      | 2         | 0.42%   |
| 54      | 2         | 0.42%   |
| 40      | 2         | 0.42%   |
| 36      | 2         | 0.42%   |
| 142     | 1         | 0.21%   |
| 84      | 1         | 0.21%   |
| 78      | 1         | 0.21%   |
| 55      | 1         | 0.21%   |
| 48      | 1         | 0.21%   |
| 43      | 1         | 0.21%   |
| 42      | 1         | 0.21%   |
| 28      | 1         | 0.21%   |
| 26      | 1         | 0.21%   |
| 25      | 1         | 0.21%   |
| 10      | 1         | 0.21%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 179       | 39.25%  |
| 501-600        | 102       | 22.37%  |
| 401-500        | 47        | 10.31%  |
| 201-300        | 34        | 7.46%   |
| 351-400        | 30        | 6.58%   |
| 601-700        | 23        | 5.04%   |
| 701-800        | 15        | 3.29%   |
| 1001-1500      | 11        | 2.41%   |
| Unknown        | 6         | 1.32%   |
| 1501-2000      | 4         | 0.88%   |
| 801-900        | 2         | 0.44%   |
| 901-1000       | 2         | 0.44%   |
| More than 2000 | 1         | 0.22%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 324       | 78.45%  |
| 16/10   | 57        | 13.8%   |
| 21/9    | 10        | 2.42%   |
| 5/4     | 8         | 1.94%   |
| Unknown | 5         | 1.21%   |
| 3/2     | 4         | 0.97%   |
| 4/3     | 2         | 0.48%   |
| 32/9    | 1         | 0.24%   |
| 1.98    | 1         | 0.24%   |
| 1.00    | 1         | 0.24%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 119       | 25.76%  |
| 201-250        | 81        | 17.53%  |
| 81-90          | 57        | 12.34%  |
| 301-350        | 44        | 9.52%   |
| 351-500        | 28        | 6.06%   |
| 151-200        | 23        | 4.98%   |
| 71-80          | 19        | 4.11%   |
| 121-130        | 18        | 3.9%    |
| 251-300        | 16        | 3.46%   |
| More than 1000 | 12        | 2.6%    |
| 111-120        | 10        | 2.16%   |
| 501-1000       | 10        | 2.16%   |
| 51-60          | 6         | 1.3%    |
| 141-150        | 6         | 1.3%    |
| Unknown        | 6         | 1.3%    |
| 61-70          | 5         | 1.08%   |
| 41-50          | 1         | 0.22%   |
| 91-100         | 1         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 143       | 32.13%  |
| 51-100        | 136       | 30.56%  |
| 101-120       | 87        | 19.55%  |
| 161-240       | 44        | 9.89%   |
| 1-50          | 16        | 3.6%    |
| More than 240 | 13        | 2.92%   |
| Unknown       | 6         | 1.35%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 298       | 72.68%  |
| 2     | 91        | 22.2%   |
| 0     | 11        | 2.68%   |
| 3     | 8         | 1.95%   |
| 4     | 2         | 0.49%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 242       | 38.35%  |
| Intel                             | 208       | 32.96%  |
| Qualcomm Atheros                  | 51        | 8.08%   |
| Broadcom                          | 29        | 4.6%    |
| MediaTek                          | 21        | 3.33%   |
| Ralink Technology                 | 11        | 1.74%   |
| Samsung Electronics               | 7         | 1.11%   |
| TP-Link                           | 6         | 0.95%   |
| ASIX Electronics                  | 6         | 0.95%   |
| Aquantia                          | 5         | 0.79%   |
| Ralink                            | 3         | 0.48%   |
| Marvell Technology Group          | 3         | 0.48%   |
| Lenovo                            | 3         | 0.48%   |
| Huawei Technologies               | 3         | 0.48%   |
| Broadcom Limited                  | 3         | 0.48%   |
| Xiaomi                            | 2         | 0.32%   |
| Sierra Wireless                   | 2         | 0.32%   |
| D-Link System                     | 2         | 0.32%   |
| ASUSTek Computer                  | 2         | 0.32%   |
| Apple                             | 2         | 0.32%   |
| ZyXEL Communications              | 1         | 0.16%   |
| Wilocity                          | 1         | 0.16%   |
| VIA Technologies                  | 1         | 0.16%   |
| Qualcomm Atheros Communications   | 1         | 0.16%   |
| Qualcomm                          | 1         | 0.16%   |
| Nvidia                            | 1         | 0.16%   |
| NetGear                           | 1         | 0.16%   |
| Motorola PCS                      | 1         | 0.16%   |
| Microsoft                         | 1         | 0.16%   |
| Mercucys                          | 1         | 0.16%   |
| Linksys                           | 1         | 0.16%   |
| ICS Advent                        | 1         | 0.16%   |
| Google                            | 1         | 0.16%   |
| Ericsson Business Mobile Networks | 1         | 0.16%   |
| Edimax Technology                 | 1         | 0.16%   |
| DisplayLink                       | 1         | 0.16%   |
| Dell                              | 1         | 0.16%   |
| D-Link                            | 1         | 0.16%   |
| Bose                              | 1         | 0.16%   |
| Belkin Components                 | 1         | 0.16%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 161       | 22.12%  |
| Intel Wi-Fi 6 AX200                                               | 27        | 3.71%   |
| Intel Wi-Fi 6 AX201                                               | 21        | 2.88%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 19        | 2.61%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 17        | 2.34%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 17        | 2.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 1.79%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 12        | 1.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 1.65%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 11        | 1.51%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 1.51%   |
| Intel Wireless 7260                                               | 11        | 1.51%   |
| Intel Ethernet Connection I217-LM                                 | 11        | 1.51%   |
| Intel Ethernet Controller I225-V                                  | 10        | 1.37%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 9         | 1.24%   |
| Intel I211 Gigabit Network Connection                             | 9         | 1.24%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 9         | 1.24%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 8         | 1.1%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 8         | 1.1%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 7         | 0.96%   |
| Intel Ethernet Connection (7) I219-V                              | 7         | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 7         | 0.96%   |
| Realtek 802.11ac NIC                                              | 6         | 0.82%   |
| Intel Wireless 8265 / 8275                                        | 6         | 0.82%   |
| Intel Wireless 8260                                               | 6         | 0.82%   |
| Intel Wireless 7265                                               | 6         | 0.82%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 6         | 0.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 0.82%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 0.82%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 0.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 5         | 0.69%   |
| Intel Wireless 3165                                               | 5         | 0.69%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 0.69%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 0.69%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 5         | 0.69%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4         | 0.55%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.55%   |
| Realtek 802.11n WLAN Adapter                                      | 4         | 0.55%   |
| Ralink MT7601U Wireless Adapter                                   | 4         | 0.55%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 157       | 44.86%  |
| Realtek Semiconductor           | 69        | 19.71%  |
| Qualcomm Atheros                | 37        | 10.57%  |
| Broadcom                        | 26        | 7.43%   |
| MediaTek                        | 20        | 5.71%   |
| Ralink Technology               | 11        | 3.14%   |
| TP-Link                         | 5         | 1.43%   |
| Ralink                          | 3         | 0.86%   |
| Broadcom Limited                | 3         | 0.86%   |
| Sierra Wireless                 | 2         | 0.57%   |
| D-Link System                   | 2         | 0.57%   |
| ASUSTek Computer                | 2         | 0.57%   |
| ZyXEL Communications            | 1         | 0.29%   |
| Wilocity                        | 1         | 0.29%   |
| Qualcomm Atheros Communications | 1         | 0.29%   |
| Qualcomm                        | 1         | 0.29%   |
| NetGear                         | 1         | 0.29%   |
| Microsoft                       | 1         | 0.29%   |
| Mercucys                        | 1         | 0.29%   |
| Marvell Technology Group        | 1         | 0.29%   |
| Linksys                         | 1         | 0.29%   |
| Edimax Technology               | 1         | 0.29%   |
| Dell                            | 1         | 0.29%   |
| D-Link                          | 1         | 0.29%   |
| Belkin Components               | 1         | 0.29%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 27        | 7.65%   |
| Intel Wi-Fi 6 AX201                                            | 21        | 5.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 19        | 5.38%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 17        | 4.82%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 12        | 3.4%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 11        | 3.12%   |
| Intel Wireless 7260                                            | 11        | 3.12%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 9         | 2.55%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 9         | 2.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 8         | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 8         | 2.27%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 7         | 1.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 7         | 1.98%   |
| Realtek 802.11ac NIC                                           | 6         | 1.7%    |
| Intel Wireless 8265 / 8275                                     | 6         | 1.7%    |
| Intel Wireless 8260                                            | 6         | 1.7%    |
| Intel Wireless 7265                                            | 6         | 1.7%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 6         | 1.7%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 6         | 1.7%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 5         | 1.42%   |
| Intel Wireless 3165                                            | 5         | 1.42%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 5         | 1.42%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 4         | 1.13%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 4         | 1.13%   |
| Realtek 802.11n WLAN Adapter                                   | 4         | 1.13%   |
| Ralink MT7601U Wireless Adapter                                | 4         | 1.13%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 4         | 1.13%   |
| Intel Wireless-AC 9260                                         | 4         | 1.13%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 4         | 1.13%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 4         | 1.13%   |
| Intel Centrino Advanced-N 6235                                 | 4         | 1.13%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 3         | 0.85%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 3         | 0.85%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 0.85%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 0.85%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 3         | 0.85%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 3         | 0.85%   |
| Broadcom BCM43142 802.11b/g/n                                  | 3         | 0.85%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 2         | 0.57%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 2         | 0.57%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 204       | 56.35%  |
| Intel                    | 99        | 27.35%  |
| Qualcomm Atheros         | 15        | 4.14%   |
| Samsung Electronics      | 7         | 1.93%   |
| Broadcom                 | 7         | 1.93%   |
| ASIX Electronics         | 6         | 1.66%   |
| Aquantia                 | 5         | 1.38%   |
| Lenovo                   | 3         | 0.83%   |
| Huawei Technologies      | 3         | 0.83%   |
| Xiaomi                   | 2         | 0.55%   |
| Marvell Technology Group | 2         | 0.55%   |
| Apple                    | 2         | 0.55%   |
| VIA Technologies         | 1         | 0.28%   |
| TP-Link                  | 1         | 0.28%   |
| Nvidia                   | 1         | 0.28%   |
| MediaTek                 | 1         | 0.28%   |
| ICS Advent               | 1         | 0.28%   |
| Google                   | 1         | 0.28%   |
| DisplayLink              | 1         | 0.28%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 161       | 43.28%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 17        | 4.57%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 13        | 3.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 12        | 3.23%   |
| Realtek RTL8125 2.5GbE Controller                                 | 11        | 2.96%   |
| Intel Ethernet Connection I217-LM                                 | 11        | 2.96%   |
| Intel Ethernet Controller I225-V                                  | 10        | 2.69%   |
| Intel I211 Gigabit Network Connection                             | 9         | 2.42%   |
| Intel Ethernet Connection (7) I219-V                              | 7         | 1.88%   |
| ASIX AX88179 Gigabit Ethernet                                     | 6         | 1.61%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 5         | 1.34%   |
| Intel Ethernet Connection (2) I219-V                              | 5         | 1.34%   |
| Intel 82579V Gigabit Network Connection                           | 5         | 1.34%   |
| Intel Ethernet Connection (13) I219-V                             | 4         | 1.08%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 1.08%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 4         | 1.08%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.81%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.81%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.81%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.81%   |
| Huawei LYA-L09                                                    | 3         | 0.81%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.54%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 2         | 0.54%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 2         | 0.54%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.54%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 2         | 0.54%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.54%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.54%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2         | 0.54%   |
| Intel I210 Gigabit Network Connection                             | 2         | 0.54%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.54%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.54%   |
| Intel Ethernet Connection (14) I219-V                             | 2         | 0.54%   |
| Intel Ethernet Connection (11) I219-V                             | 2         | 0.54%   |
| Broadcom NetXtreme BCM57762 Gigabit Ethernet PCIe                 | 2         | 0.54%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 1         | 0.27%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.27%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 336       | 50.15%  |
| Ethernet | 331       | 49.4%   |
| Modem    | 2         | 0.3%    |
| Unknown  | 1         | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 260       | 61.32%  |
| Ethernet | 164       | 38.68%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 215       | 53.09%  |
| 1     | 173       | 42.72%  |
| 3     | 7         | 1.73%   |
| 0     | 7         | 1.73%   |
| 4     | 2         | 0.49%   |
| 6     | 1         | 0.25%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 296       | 72.55%  |
| Yes  | 112       | 27.45%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 133       | 44.63%  |
| Realtek Semiconductor           | 40        | 13.42%  |
| Cambridge Silicon Radio         | 25        | 8.39%   |
| Qualcomm Atheros Communications | 16        | 5.37%   |
| IMC Networks                    | 15        | 5.03%   |
| Foxconn / Hon Hai               | 13        | 4.36%   |
| Broadcom                        | 13        | 4.36%   |
| Lite-On Technology              | 11        | 3.69%   |
| ASUSTek Computer                | 7         | 2.35%   |
| Apple                           | 6         | 2.01%   |
| Toshiba                         | 4         | 1.34%   |
| Realtek                         | 3         | 1.01%   |
| Edimax Technology               | 3         | 1.01%   |
| TP-Link                         | 2         | 0.67%   |
| Dell                            | 2         | 0.67%   |
| MediaTek                        | 1         | 0.34%   |
| Marvell Semiconductor           | 1         | 0.34%   |
| Hewlett-Packard                 | 1         | 0.34%   |
| Foxconn International           | 1         | 0.34%   |
| Alps Electric                   | 1         | 0.34%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                             | 33        | 11.07%  |
| Intel Bluetooth wireless interface                  | 32        | 10.74%  |
| Intel AX201 Bluetooth                               | 30        | 10.07%  |
| Intel AX200 Bluetooth                               | 26        | 8.72%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 25        | 8.39%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 18        | 6.04%   |
| Intel Bluetooth Device                              | 12        | 4.03%   |
| Foxconn / Hon Hai Wireless_Device                   | 8         | 2.68%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 2.01%   |
| Qualcomm Atheros  Bluetooth Device                  | 6         | 2.01%   |
| IMC Networks Wireless_Device                        | 6         | 2.01%   |
| Lite-On Wireless_Device                             | 5         | 1.68%   |
| Intel AX210 Bluetooth                               | 5         | 1.68%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 4         | 1.34%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 4         | 1.34%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 4         | 1.34%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 4         | 1.34%   |
| IMC Networks Bluetooth Radio                        | 4         | 1.34%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 4         | 1.34%   |
| Apple Bluetooth Host Controller                     | 4         | 1.34%   |
| Realtek Bluetooth Radio                             | 3         | 1.01%   |
| Foxconn / Hon Hai Bluetooth Device                  | 3         | 1.01%   |
| Broadcom HP Portable SoftSailing                    | 3         | 1.01%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 3         | 1.01%   |
| ASUS ASUS USB-BT500                                 | 3         | 1.01%   |
| TP-Link TPuLink UB500 Adapter                       | 2         | 0.67%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 2         | 0.67%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2         | 0.67%   |
| IMC Networks Bluetooth Device                       | 2         | 0.67%   |
| Apple Bluetooth USB Host Controller                 | 2         | 0.67%   |
| Toshiba Integrated Bluetooth HCI                    | 1         | 0.34%   |
| Toshiba Bluetooth USB Host Controller               | 1         | 0.34%   |
| Toshiba Bluetooth Device                            | 1         | 0.34%   |
| Toshiba Askey Bluetooth Module                      | 1         | 0.34%   |
| Realtek RTL8723B Bluetooth                          | 1         | 0.34%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 1         | 0.34%   |
| Qualcomm Atheros Bluetooth                          | 1         | 0.34%   |
| MediaTek Wireless_Device                            | 1         | 0.34%   |
| Marvell Bluetooth and Wireless LAN Composite        | 1         | 0.34%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 1         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 264       | 41.84%  |
| AMD                      | 153       | 24.25%  |
| Nvidia                   | 131       | 20.76%  |
| C-Media Electronics      | 10        | 1.58%   |
| GN Netcom                | 6         | 0.95%   |
| JMTek                    | 5         | 0.79%   |
| Creative Labs            | 4         | 0.63%   |
| Razer USA                | 3         | 0.48%   |
| Lenovo                   | 3         | 0.48%   |
| ZOOM                     | 2         | 0.32%   |
| VIA Technologies         | 2         | 0.32%   |
| Texas Instruments        | 2         | 0.32%   |
| TerraTec Electronic      | 2         | 0.32%   |
| Logitech                 | 2         | 0.32%   |
| KORG                     | 2         | 0.32%   |
| Kingston Technology      | 2         | 0.32%   |
| Generalplus Technology   | 2         | 0.32%   |
| Corsair                  | 2         | 0.32%   |
| BY EDIFIER               | 2         | 0.32%   |
| Blue Microphones         | 2         | 0.32%   |
| ASUSTek Computer         | 2         | 0.32%   |
| Arturia                  | 2         | 0.32%   |
| Apple                    | 2         | 0.32%   |
| Zhaoxin                  | 1         | 0.16%   |
| Yamaha                   | 1         | 0.16%   |
| Unknown                  | 1         | 0.16%   |
| Tenx Technology          | 1         | 0.16%   |
| SteelSeries ApS          | 1         | 0.16%   |
| Sony                     | 1         | 0.16%   |
| Samson Technologies      | 1         | 0.16%   |
| QinHeng Electronics      | 1         | 0.16%   |
| Philips (or NXP)         | 1         | 0.16%   |
| Nordic Semiconductor ASA | 1         | 0.16%   |
| Microdia                 | 1         | 0.16%   |
| Micro Star International | 1         | 0.16%   |
| M-Audio                  | 1         | 0.16%   |
| Hewlett-Packard          | 1         | 0.16%   |
| Hangzhou Worlde          | 1         | 0.16%   |
| Focusrite-Novation       | 1         | 0.16%   |
| DisplayLink              | 1         | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 66        | 8.93%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 45        | 6.09%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 30        | 4.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 30        | 4.06%   |
| Intel Sunrise Point-LP HD Audio                                            | 29        | 3.92%   |
| AMD Starship/Matisse HD Audio Controller                                   | 26        | 3.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 25        | 3.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 18        | 2.44%   |
| Nvidia GP107GL High Definition Audio Controller                            | 17        | 2.3%    |
| Intel Cannon Lake PCH cAVS                                                 | 17        | 2.3%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 14        | 1.89%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 13        | 1.76%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 13        | 1.76%   |
| Nvidia TU116 High Definition Audio Controller                              | 11        | 1.49%   |
| Nvidia GA104 High Definition Audio Controller                              | 11        | 1.49%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 10        | 1.35%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 10        | 1.35%   |
| Nvidia TU106 High Definition Audio Controller                              | 9         | 1.22%   |
| Intel Comet Lake PCH cAVS                                                  | 9         | 1.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9         | 1.22%   |
| Nvidia GA106 High Definition Audio Controller                              | 8         | 1.08%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 8         | 1.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 1.08%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 7         | 0.95%   |
| Nvidia High Definition Audio Controller                                    | 7         | 0.95%   |
| Nvidia GP106 High Definition Audio Controller                              | 7         | 0.95%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 7         | 0.95%   |
| Intel Comet Lake PCH-LP cAVS                                               | 7         | 0.95%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 0.95%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 7         | 0.95%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 6         | 0.81%   |
| Nvidia GK107 HDMI Audio Controller                                         | 6         | 0.81%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6         | 0.81%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 6         | 0.81%   |
| AMD FCH Azalia Controller                                                  | 6         | 0.81%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 6         | 0.81%   |
| Nvidia TU104 HD Audio Controller                                           | 5         | 0.68%   |
| Nvidia GP104 High Definition Audio Controller                              | 5         | 0.68%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 5         | 0.68%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 84        | 27.81%  |
| SK hynix            | 47        | 15.56%  |
| Kingston            | 34        | 11.26%  |
| Micron Technology   | 30        | 9.93%   |
| Crucial             | 22        | 7.28%   |
| Corsair             | 19        | 6.29%   |
| G.Skill             | 14        | 4.64%   |
| Unknown             | 10        | 3.31%   |
| A-DATA Technology   | 5         | 1.66%   |
| Unknown             | 5         | 1.66%   |
| Unknown (ABCD)      | 4         | 1.32%   |
| Patriot             | 3         | 0.99%   |
| Elpida              | 3         | 0.99%   |
| Team                | 2         | 0.66%   |
| Ramaxel Technology  | 2         | 0.66%   |
| Nanya Technology    | 2         | 0.66%   |
| Atermiter           | 2         | 0.66%   |
| AMD                 | 2         | 0.66%   |
| Wilk                | 1         | 0.33%   |
| Unknown (8A02)      | 1         | 0.33%   |
| Teikon              | 1         | 0.33%   |
| Silicon Power       | 1         | 0.33%   |
| Shenzhen Zhongteng  | 1         | 0.33%   |
| Shenzhen WODPOSIT   | 1         | 0.33%   |
| Qimonda             | 1         | 0.33%   |
| PNY                 | 1         | 0.33%   |
| Lexar               | 1         | 0.33%   |
| Kingmax             | 1         | 0.33%   |
| Hewlett-Packard     | 1         | 0.33%   |
| GOODRAM             | 1         | 0.33%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown                                                          | 5         | 1.54%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.23%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.23%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 1.23%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 1.23%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 1.23%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 4         | 1.23%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 4         | 1.23%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.93%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.93%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 3         | 0.93%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.93%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.93%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.93%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 2         | 0.62%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.62%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.62%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8192MB SODIMM DDR4 3200MT/s        | 2         | 0.62%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 0.62%   |
| Samsung RAM UBE3D4AA-MGCR 8GB Row Of Chips LPDDR4 4267MT/s       | 2         | 0.62%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 2         | 0.62%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 0.62%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.62%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.62%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 2         | 0.62%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 2         | 0.62%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 0.62%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.62%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 2         | 0.62%   |
| Samsung RAM M471A1K43BB0-CPB 8GB SODIMM DDR4 2133MT/s            | 2         | 0.62%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.62%   |
| Micron RAM 8ATF1G64AZ-2G6E1 8192MB DIMM DDR4 2667MT/s            | 2         | 0.62%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 0.62%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 2         | 0.62%   |
| Micron RAM 16KTF1G64HZ-1G6E1 8GB SODIMM DDR3 1600MT/s            | 2         | 0.62%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3200MT/s            | 2         | 0.62%   |
| Elpida RAM EBJ40UG8BBU0-GN-F 4GB SODIMM DDR3 1600MT/s            | 2         | 0.62%   |
| Crucial RAM CT102464BA160B.C16 8GB DIMM DDR3 1600MT/s            | 2         | 0.62%   |
| Corsair RAM CMK32GX4M2Z3600C18 16GB DIMM DDR4 3800MT/s           | 2         | 0.62%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s            | 2         | 0.62%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 160       | 61.3%   |
| DDR3    | 61        | 23.37%  |
| LPDDR4  | 15        | 5.75%   |
| DDR5    | 5         | 1.92%   |
| DDR2    | 5         | 1.92%   |
| SDRAM   | 4         | 1.53%   |
| LPDDR5  | 4         | 1.53%   |
| Unknown | 4         | 1.53%   |
| LPDDR3  | 3         | 1.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 149       | 56.02%  |
| DIMM         | 83        | 31.2%   |
| Row Of Chips | 32        | 12.03%  |
| RIMM         | 1         | 0.38%   |
| Chip         | 1         | 0.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 130       | 46.1%   |
| 4096  | 65        | 23.05%  |
| 16384 | 51        | 18.09%  |
| 2048  | 19        | 6.74%   |
| 32768 | 13        | 4.61%   |
| 1024  | 4         | 1.42%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 78        | 28.26%  |
| 1600    | 45        | 16.3%   |
| 2667    | 36        | 13.04%  |
| 2400    | 20        | 7.25%   |
| 1333    | 14        | 5.07%   |
| 2133    | 12        | 4.35%   |
| 3600    | 8         | 2.9%    |
| 4267    | 7         | 2.54%   |
| 4800    | 5         | 1.81%   |
| 1334    | 5         | 1.81%   |
| 6400    | 4         | 1.45%   |
| 3000    | 4         | 1.45%   |
| 2666    | 4         | 1.45%   |
| 1867    | 4         | 1.45%   |
| 3066    | 3         | 1.09%   |
| 4266    | 2         | 0.72%   |
| 3800    | 2         | 0.72%   |
| 3266    | 2         | 0.72%   |
| 667     | 2         | 0.72%   |
| Unknown | 2         | 0.72%   |
| 8400    | 1         | 0.36%   |
| 6000    | 1         | 0.36%   |
| 5800    | 1         | 0.36%   |
| 4000    | 1         | 0.36%   |
| 3866    | 1         | 0.36%   |
| 3666    | 1         | 0.36%   |
| 3467    | 1         | 0.36%   |
| 3400    | 1         | 0.36%   |
| 3334    | 1         | 0.36%   |
| 3333    | 1         | 0.36%   |
| 2800    | 1         | 0.36%   |
| 2448    | 1         | 0.36%   |
| 2048    | 1         | 0.36%   |
| 1866    | 1         | 0.36%   |
| 1067    | 1         | 0.36%   |
| 1066    | 1         | 0.36%   |
| 800     | 1         | 0.36%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 5         | 31.25%  |
| Seiko Epson         | 3         | 18.75%  |
| Canon               | 3         | 18.75%  |
| Brother Industries  | 2         | 12.5%   |
| Xerox               | 1         | 6.25%   |
| Samsung Electronics | 1         | 6.25%   |
| Datamax-O'Neil      | 1         | 6.25%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Seiko Epson L3110 Series         | 2         | 12.5%   |
| Xerox Phaser 3140 and 3155       | 1         | 6.25%   |
| Seiko Epson L222 Series          | 1         | 6.25%   |
| Samsung M2070 Series             | 1         | 6.25%   |
| HP OfficeJet 5500 series         | 1         | 6.25%   |
| HP LaserJet 1022                 | 1         | 6.25%   |
| HP ENVY 4500 series              | 1         | 6.25%   |
| HP DeskJet D2300                 | 1         | 6.25%   |
| HP DeskJet 3700 series           | 1         | 6.25%   |
| Datamax-O'Neil Datamax E-4304    | 1         | 6.25%   |
| Canon PIXMA MX470 Series         | 1         | 6.25%   |
| Canon LaserShot LBP-1120 Printer | 1         | 6.25%   |
| Canon iP2600 series              | 1         | 6.25%   |
| Brother MFC-J460DW               | 1         | 6.25%   |
| Brother HL-2230 series           | 1         | 6.25%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 4         | 66.67%  |
| Seiko Epson    | 1         | 16.67%  |
| Mustek Systems | 1         | 16.67%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Seiko Epson GT-X820 [Perfection V600 Photo] | 1         | 16.67%  |
| Mustek Systems ScanExpress A3 USB 1200 PRO  | 1         | 16.67%  |
| Canon CanoScan N670U/N676U/LiDE 20          | 1         | 16.67%  |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40      | 1         | 16.67%  |
| Canon CanoScan LiDE 220                     | 1         | 16.67%  |
| Canon CanoScan LiDE 210                     | 1         | 16.67%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 54        | 19.85%  |
| Microdia                               | 29        | 10.66%  |
| IMC Networks                           | 26        | 9.56%   |
| Acer                                   | 24        | 8.82%   |
| Logitech                               | 23        | 8.46%   |
| Realtek Semiconductor                  | 17        | 6.25%   |
| Quanta                                 | 16        | 5.88%   |
| Luxvisions Innotech Limited            | 11        | 4.04%   |
| Cheng Uei Precision Industry (Foxlink) | 9         | 3.31%   |
| Sunplus Innovation Technology          | 8         | 2.94%   |
| Lite-On Technology                     | 6         | 2.21%   |
| Apple                                  | 6         | 2.21%   |
| Silicon Motion                         | 5         | 1.84%   |
| Syntek                                 | 4         | 1.47%   |
| Microsoft                              | 3         | 1.1%    |
| Alcor Micro                            | 3         | 1.1%    |
| Z-Star Microelectronics                | 2         | 0.74%   |
| Y Media                                | 2         | 0.74%   |
| SunplusIT                              | 2         | 0.74%   |
| KYE Systems (Mouse Systems)            | 2         | 0.74%   |
| Jieli Technology                       | 2         | 0.74%   |
| Generalplus Technology                 | 2         | 0.74%   |
| Xiaomi                                 | 1         | 0.37%   |
| Unknown                                | 1         | 0.37%   |
| Suyin                                  | 1         | 0.37%   |
| ShineTech                              | 1         | 0.37%   |
| Samsung Electronics                    | 1         | 0.37%   |
| Ricoh                                  | 1         | 0.37%   |
| Novatek Microelectronics               | 1         | 0.37%   |
| Importek                               | 1         | 0.37%   |
| icSpring                               | 1         | 0.37%   |
| Hewlett-Packard                        | 1         | 0.37%   |
| Goodong Industry                       | 1         | 0.37%   |
| Goodong                                | 1         | 0.37%   |
| eMPIA Technology                       | 1         | 0.37%   |
| Cubeternet                             | 1         | 0.37%   |
| Asuscom Network                        | 1         | 0.37%   |
| ARC International                      | 1         | 0.37%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                       | 14        | 5.11%   |
| Acer Integrated Camera                                          | 13        | 4.74%   |
| Microdia Integrated_Webcam_HD                                   | 10        | 3.65%   |
| IMC Networks USB2.0 HD UVC WebCam                               | 8         | 2.92%   |
| IMC Networks Integrated Camera                                  | 8         | 2.92%   |
| Chicony HD WebCam                                               | 7         | 2.55%   |
| Realtek Integrated_Webcam_HD                                    | 4         | 1.46%   |
| Quanta HP TrueVision HD Camera                                  | 4         | 1.46%   |
| Microdia Webcam Vitade AF                                       | 4         | 1.46%   |
| Microdia Integrated_Webcam_FHD                                  | 4         | 1.46%   |
| Logitech Webcam C270                                            | 4         | 1.46%   |
| Chicony HP HD Camera                                            | 4         | 1.46%   |
| Chicony HD User Facing                                          | 4         | 1.46%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Camera | 4         | 1.46%   |
| Syntek Integrated Camera                                        | 3         | 1.09%   |
| Sunplus Integrated_Webcam_HD                                    | 3         | 1.09%   |
| Quanta HP Wide Vision HD Camera                                 | 3         | 1.09%   |
| Quanta HD User Facing                                           | 3         | 1.09%   |
| Luxvisions Innotech Limited Integrated Camera                   | 3         | 1.09%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera             | 3         | 1.09%   |
| Logitech Webcam C310                                            | 3         | 1.09%   |
| Logitech HD Pro Webcam C920                                     | 3         | 1.09%   |
| Chicony USB2.0 Camera                                           | 3         | 1.09%   |
| Y Media USB Camera                                              | 2         | 0.73%   |
| Silicon Motion 300k Pixel Camera                                | 2         | 0.73%   |
| Realtek USB Camera                                              | 2         | 0.73%   |
| Realtek Integrated Webcam HD                                    | 2         | 0.73%   |
| Microdia USB Live camera                                        | 2         | 0.73%   |
| Microdia Integrated Webcam                                      | 2         | 0.73%   |
| Microdia Integrated Camera                                      | 2         | 0.73%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera            | 2         | 0.73%   |
| Luxvisions Innotech Limited HP HD Camera                        | 2         | 0.73%   |
| Logitech StreamCam                                              | 2         | 0.73%   |
| Logitech C922 Pro Stream Webcam                                 | 2         | 0.73%   |
| Logitech C920 PRO HD Webcam                                     | 2         | 0.73%   |
| Lite-On Integrated Camera                                       | 2         | 0.73%   |
| Jieli USB PHY 2.0                                               | 2         | 0.73%   |
| IMC Networks USB2.0 UVC HD Webcam                               | 2         | 0.73%   |
| IMC Networks USB Camera                                         | 2         | 0.73%   |
| IMC Networks HD Camera                                          | 2         | 0.73%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 19        | 33.93%  |
| Synaptics                  | 16        | 28.57%  |
| Validity Sensors           | 12        | 21.43%  |
| Elan Microelectronics      | 5         | 8.93%   |
| AuthenTec                  | 3         | 5.36%   |
| STMicroelectronics         | 1         | 1.79%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                         | 17        | 30.36%  |
| Elan ELAN:ARM-M4                                            | 5         | 8.93%   |
| Unknown                                                     | 4         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader                  | 3         | 5.36%   |
| Validity Sensors VFS 5011 fingerprint sensor                | 3         | 5.36%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader           | 3         | 5.36%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                | 2         | 3.57%   |
| Synaptics  WBDI                                             | 2         | 3.57%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint   | 2         | 3.57%   |
| Synaptics Metallica MIS Touch Fingerprint Reader            | 2         | 3.57%   |
| Shenzhen Goodix Fingerprint Reader                          | 2         | 3.57%   |
| AuthenTec Fingerprint Sensor                                | 2         | 3.57%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor           | 1         | 1.79%   |
| Validity Sensors VFS491                                     | 1         | 1.79%   |
| Validity Sensors VFS471 Fingerprint Reader                  | 1         | 1.79%   |
| Validity Sensors VFS300 Fingerprint Reader                  | 1         | 1.79%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1         | 1.79%   |
| Validity Sensors Fingerprint scanner                        | 1         | 1.79%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint  | 1         | 1.79%   |
| STMicroelectronics Fingerprint Reader                       | 1         | 1.79%   |
| AuthenTec AES2501 Fingerprint Sensor                        | 1         | 1.79%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 8         | 44.44%  |
| Alcor Micro           | 5         | 27.78%  |
| BIT4ID                | 2         | 11.11%  |
| Upek                  | 1         | 5.56%   |
| O2 Micro              | 1         | 5.56%   |
| Gemalto (was Gemplus) | 1         | 5.56%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 27.78%  |
| Broadcom 5880                                                                | 3         | 16.67%  |
| Broadcom 58200                                                               | 3         | 16.67%  |
| BIT4ID miniLector EVO                                                        | 2         | 11.11%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 5.56%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.56%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 5.56%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 5.56%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 279       | 68.38%  |
| 1     | 102       | 25%     |
| 2     | 23        | 5.64%   |
| 3     | 2         | 0.49%   |
| 9     | 1         | 0.25%   |
| 4     | 1         | 0.25%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 56        | 36.13%  |
| Graphics card            | 20        | 12.9%   |
| Chipcard                 | 17        | 10.97%  |
| Net/wireless             | 15        | 9.68%   |
| Multimedia controller    | 11        | 7.1%    |
| Camera                   | 10        | 6.45%   |
| Unassigned class         | 7         | 4.52%   |
| Sound                    | 5         | 3.23%   |
| Communication controller | 5         | 3.23%   |
| Bluetooth                | 5         | 3.23%   |
| Network                  | 2         | 1.29%   |
| Net/ethernet             | 1         | 0.65%   |
| Card reader              | 1         | 0.65%   |

