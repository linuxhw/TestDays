Pop!_OS 22.04 - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Pop!_OS 22.04.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Pop!_OS_22.04/Desktop/README.md) and [notebooks](/Dist/Pop!_OS_22.04/Notebook/README.md).

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

Total: 4135

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Acer          | Spin SP314-54N              | Convertible | [446ce08df0](https://linux-hardware.org/?probe=446ce08df0) | Jun 30, 2023 |
| Gigabyte      | B550 UD AC                  | Desktop     | [7d7d37522c](https://linux-hardware.org/?probe=7d7d37522c) | Jun 30, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [b95a7c049a](https://linux-hardware.org/?probe=b95a7c049a) | Jun 30, 2023 |
| Teclast       | F7 Plus                     | Notebook    | [cebd3b027c](https://linux-hardware.org/?probe=cebd3b027c) | Jun 30, 2023 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [59d1be1c5d](https://linux-hardware.org/?probe=59d1be1c5d) | Jun 30, 2023 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | Desktop     | [878e617ba4](https://linux-hardware.org/?probe=878e617ba4) | Jun 30, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [ec4bf131f5](https://linux-hardware.org/?probe=ec4bf131f5) | Jun 30, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [cdb77bf9b6](https://linux-hardware.org/?probe=cdb77bf9b6) | Jun 30, 2023 |
| Dell          | 0M6C7G A00                  | Desktop     | [d7dfcc4a38](https://linux-hardware.org/?probe=d7dfcc4a38) | Jun 30, 2023 |
| Positivo      | Mobile                      | Notebook    | [fdaaf6915b](https://linux-hardware.org/?probe=fdaaf6915b) | Jun 30, 2023 |
| MSI           | GS65 Stealth 9SD            | Notebook    | [568380fd59](https://linux-hardware.org/?probe=568380fd59) | Jun 30, 2023 |
| MSI           | GS65 Stealth 9SD            | Notebook    | [54013b2dfd](https://linux-hardware.org/?probe=54013b2dfd) | Jun 30, 2023 |
| Positivo      | H14CU02                     | Notebook    | [d50e6fbbdc](https://linux-hardware.org/?probe=d50e6fbbdc) | Jun 29, 2023 |
| ASRock        | Z77 Performance             | Notebook    | [a678dc9605](https://linux-hardware.org/?probe=a678dc9605) | Jun 29, 2023 |
| MSI           | Vector GP76 12UH            | Notebook    | [b7035d78a6](https://linux-hardware.org/?probe=b7035d78a6) | Jun 29, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [323464eebb](https://linux-hardware.org/?probe=323464eebb) | Jun 28, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [b1b4052442](https://linux-hardware.org/?probe=b1b4052442) | Jun 28, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [4054ebeac8](https://linux-hardware.org/?probe=4054ebeac8) | Jun 28, 2023 |
| MSI           | GE70 2PL                    | Notebook    | [e5354b6cb4](https://linux-hardware.org/?probe=e5354b6cb4) | Jun 28, 2023 |
| Dell          | 0F6X5P A00                  | Desktop     | [cad43414b4](https://linux-hardware.org/?probe=cad43414b4) | Jun 27, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [4bf524cd80](https://linux-hardware.org/?probe=4bf524cd80) | Jun 27, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [894f8583ea](https://linux-hardware.org/?probe=894f8583ea) | Jun 27, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [adb3a3de68](https://linux-hardware.org/?probe=adb3a3de68) | Jun 27, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [0dda4e26da](https://linux-hardware.org/?probe=0dda4e26da) | Jun 27, 2023 |
| Dell          | Precision M6800             | Notebook    | [b0fe737883](https://linux-hardware.org/?probe=b0fe737883) | Jun 27, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [882bd512a2](https://linux-hardware.org/?probe=882bd512a2) | Jun 27, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [975e5164c6](https://linux-hardware.org/?probe=975e5164c6) | Jun 27, 2023 |
| ASUSTek       | X550JX                      | Notebook    | [80770014b8](https://linux-hardware.org/?probe=80770014b8) | Jun 27, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [e1e76b3d77](https://linux-hardware.org/?probe=e1e76b3d77) | Jun 27, 2023 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [5454a08ba6](https://linux-hardware.org/?probe=5454a08ba6) | Jun 26, 2023 |
| Lenovo        | ThinkPad P53 20QQS34C04     | Notebook    | [3019d7a733](https://linux-hardware.org/?probe=3019d7a733) | Jun 26, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [6b44c8513d](https://linux-hardware.org/?probe=6b44c8513d) | Jun 26, 2023 |
| Dell          | Precision M6800             | Notebook    | [4e6c5423b1](https://linux-hardware.org/?probe=4e6c5423b1) | Jun 25, 2023 |
| Dell          | Precision M6800             | Notebook    | [feb0adfd99](https://linux-hardware.org/?probe=feb0adfd99) | Jun 25, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [1bd3b2b912](https://linux-hardware.org/?probe=1bd3b2b912) | Jun 25, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d436c6bcdf](https://linux-hardware.org/?probe=d436c6bcdf) | Jun 25, 2023 |
| HP            | Notebook                    | Notebook    | [ea00ce6c5b](https://linux-hardware.org/?probe=ea00ce6c5b) | Jun 25, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [3907252056](https://linux-hardware.org/?probe=3907252056) | Jun 25, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [9888e54285](https://linux-hardware.org/?probe=9888e54285) | Jun 25, 2023 |
| Biostar       | H81MHV3 5.0                 | Desktop     | [0f95f72b43](https://linux-hardware.org/?probe=0f95f72b43) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | Notebook    | [b9a835920f](https://linux-hardware.org/?probe=b9a835920f) | Jun 25, 2023 |
| Sony          | VPCEA23FB                   | Notebook    | [c462c4c75e](https://linux-hardware.org/?probe=c462c4c75e) | Jun 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [b4ab698b09](https://linux-hardware.org/?probe=b4ab698b09) | Jun 25, 2023 |
| HP            | ENVY NOTEBOOK PC            | Notebook    | [8bd62ffdf1](https://linux-hardware.org/?probe=8bd62ffdf1) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [210d09c5dd](https://linux-hardware.org/?probe=210d09c5dd) | Jun 24, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [12f361cd8c](https://linux-hardware.org/?probe=12f361cd8c) | Jun 24, 2023 |
| System76      | Oryx Pro                    | Notebook    | [eaa4d8e105](https://linux-hardware.org/?probe=eaa4d8e105) | Jun 24, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [737204f453](https://linux-hardware.org/?probe=737204f453) | Jun 24, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [7f13c620bf](https://linux-hardware.org/?probe=7f13c620bf) | Jun 23, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [703e12843e](https://linux-hardware.org/?probe=703e12843e) | Jun 23, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [700914c136](https://linux-hardware.org/?probe=700914c136) | Jun 23, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [70954bb61e](https://linux-hardware.org/?probe=70954bb61e) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [7f41e23d3a](https://linux-hardware.org/?probe=7f41e23d3a) | Jun 23, 2023 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [79ec1a7b3f](https://linux-hardware.org/?probe=79ec1a7b3f) | Jun 23, 2023 |
| MSI           | H77MA-G43                   | Desktop     | [510d2844bd](https://linux-hardware.org/?probe=510d2844bd) | Jun 23, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [36dc72c683](https://linux-hardware.org/?probe=36dc72c683) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [c7be73b6ca](https://linux-hardware.org/?probe=c7be73b6ca) | Jun 23, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [346bbb0b47](https://linux-hardware.org/?probe=346bbb0b47) | Jun 23, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [410b20161b](https://linux-hardware.org/?probe=410b20161b) | Jun 23, 2023 |
| Dell          | Inspiron 3501               | Notebook    | [e8db86e014](https://linux-hardware.org/?probe=e8db86e014) | Jun 22, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [6e68a59ffb](https://linux-hardware.org/?probe=6e68a59ffb) | Jun 22, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [41a5a93ebb](https://linux-hardware.org/?probe=41a5a93ebb) | Jun 22, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [082d9a4988](https://linux-hardware.org/?probe=082d9a4988) | Jun 22, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [5b2b7d4a7f](https://linux-hardware.org/?probe=5b2b7d4a7f) | Jun 22, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [170d1f4f0b](https://linux-hardware.org/?probe=170d1f4f0b) | Jun 22, 2023 |
| HP            | Notebook                    | Notebook    | [35b8a2a187](https://linux-hardware.org/?probe=35b8a2a187) | Jun 22, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [3c27e4a91d](https://linux-hardware.org/?probe=3c27e4a91d) | Jun 22, 2023 |
| Acidanther... | Mac-77EB7D7DAF985301 iMa... | All in one  | [1b2f8eb529](https://linux-hardware.org/?probe=1b2f8eb529) | Jun 22, 2023 |
| Lenovo        | B5400 80B6QB0               | Notebook    | [6885fc56aa](https://linux-hardware.org/?probe=6885fc56aa) | Jun 22, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [f7c2ec659b](https://linux-hardware.org/?probe=f7c2ec659b) | Jun 22, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [8634954b1c](https://linux-hardware.org/?probe=8634954b1c) | Jun 22, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [43ee82258d](https://linux-hardware.org/?probe=43ee82258d) | Jun 21, 2023 |
| Intel         | H55                         | Desktop     | [545c7e42b3](https://linux-hardware.org/?probe=545c7e42b3) | Jun 21, 2023 |
| HP            | 89B5 A                      | Desktop     | [01e8a85a35](https://linux-hardware.org/?probe=01e8a85a35) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | Notebook    | [ebaceedccf](https://linux-hardware.org/?probe=ebaceedccf) | Jun 21, 2023 |
| Lenovo        | ThinkPad T480 20L6S3H102    | Notebook    | [4a8bd602ff](https://linux-hardware.org/?probe=4a8bd602ff) | Jun 21, 2023 |
| Dell          | System Inspiron N4110       | Notebook    | [a168f45822](https://linux-hardware.org/?probe=a168f45822) | Jun 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [b255195205](https://linux-hardware.org/?probe=b255195205) | Jun 21, 2023 |
| Acer          | Aspire A515-52              | Notebook    | [b2d464d2bc](https://linux-hardware.org/?probe=b2d464d2bc) | Jun 21, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [14296e98e7](https://linux-hardware.org/?probe=14296e98e7) | Jun 21, 2023 |
| Dell          | Latitude E7240              | Notebook    | [f8b3fce80b](https://linux-hardware.org/?probe=f8b3fce80b) | Jun 21, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | Notebook    | [383aed9129](https://linux-hardware.org/?probe=383aed9129) | Jun 20, 2023 |
| HP            | Pavilion Laptop 15t-eg00... | Notebook    | [3996492e80](https://linux-hardware.org/?probe=3996492e80) | Jun 20, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [1c9456fd1d](https://linux-hardware.org/?probe=1c9456fd1d) | Jun 20, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [ec5318fcd1](https://linux-hardware.org/?probe=ec5318fcd1) | Jun 20, 2023 |
| Lenovo        | ThinkCentre M90p 5498R97    | Desktop     | [4a18635ad7](https://linux-hardware.org/?probe=4a18635ad7) | Jun 20, 2023 |
| Dell          | 0X9M3X A01                  | Desktop     | [1d14950f1e](https://linux-hardware.org/?probe=1d14950f1e) | Jun 20, 2023 |
| Dell          | 0X9M3X A01                  | Desktop     | [46baecef13](https://linux-hardware.org/?probe=46baecef13) | Jun 20, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [796769b68a](https://linux-hardware.org/?probe=796769b68a) | Jun 20, 2023 |
| Lenovo        | ThinkCentre M90p 5498R97    | Desktop     | [d2550efee5](https://linux-hardware.org/?probe=d2550efee5) | Jun 19, 2023 |
| System76      | Lemur Pro                   | Notebook    | [5074769fee](https://linux-hardware.org/?probe=5074769fee) | Jun 19, 2023 |
| Dell          | Latitude 7430               | Notebook    | [84f66041f9](https://linux-hardware.org/?probe=84f66041f9) | Jun 19, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [5a89024be5](https://linux-hardware.org/?probe=5a89024be5) | Jun 19, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [347c5ce944](https://linux-hardware.org/?probe=347c5ce944) | Jun 19, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [0699537327](https://linux-hardware.org/?probe=0699537327) | Jun 19, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [26d77cd5be](https://linux-hardware.org/?probe=26d77cd5be) | Jun 19, 2023 |
| HP            | 829A                        | Mini pc     | [0ca8c646bb](https://linux-hardware.org/?probe=0ca8c646bb) | Jun 19, 2023 |
| MSI           | Raider GE66 12UGS           | Notebook    | [73b20b76a3](https://linux-hardware.org/?probe=73b20b76a3) | Jun 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [f93c91b6d9](https://linux-hardware.org/?probe=f93c91b6d9) | Jun 18, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [4f35e25c20](https://linux-hardware.org/?probe=4f35e25c20) | Jun 18, 2023 |
| ASUSTek       | Maximus VI HERO             | Desktop     | [fcbe9b509b](https://linux-hardware.org/?probe=fcbe9b509b) | Jun 18, 2023 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [ae0a1a134a](https://linux-hardware.org/?probe=ae0a1a134a) | Jun 18, 2023 |
| HP            | 8949 11                     | Desktop     | [bd6b95fc23](https://linux-hardware.org/?probe=bd6b95fc23) | Jun 18, 2023 |
| Biostar       | A320MH                      | Desktop     | [0c38427f58](https://linux-hardware.org/?probe=0c38427f58) | Jun 18, 2023 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [6e40a39112](https://linux-hardware.org/?probe=6e40a39112) | Jun 18, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [e9dd574827](https://linux-hardware.org/?probe=e9dd574827) | Jun 18, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [c45aea7474](https://linux-hardware.org/?probe=c45aea7474) | Jun 18, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [6c2811bbf5](https://linux-hardware.org/?probe=6c2811bbf5) | Jun 18, 2023 |
| HONOR         | BRN-FXX                     | Notebook    | [d3671dca6a](https://linux-hardware.org/?probe=d3671dca6a) | Jun 18, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c2f10ad55c](https://linux-hardware.org/?probe=c2f10ad55c) | Jun 17, 2023 |
| Avell High... | A70 HYB                     | Notebook    | [10eb079da8](https://linux-hardware.org/?probe=10eb079da8) | Jun 17, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | Notebook    | [cf08c655b9](https://linux-hardware.org/?probe=cf08c655b9) | Jun 17, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [2b3a058830](https://linux-hardware.org/?probe=2b3a058830) | Jun 17, 2023 |
| Acer          | Aspire 4752                 | Notebook    | [441eb3fe51](https://linux-hardware.org/?probe=441eb3fe51) | Jun 17, 2023 |
| MSI           | H67MA-E35                   | Desktop     | [8b37f91738](https://linux-hardware.org/?probe=8b37f91738) | Jun 16, 2023 |
| ASUSTek       | ASUSPRO P5440UF             | Notebook    | [272d8de237](https://linux-hardware.org/?probe=272d8de237) | Jun 16, 2023 |
| Dell          | Inspiron 5481               | Convertible | [4e24ca3b12](https://linux-hardware.org/?probe=4e24ca3b12) | Jun 16, 2023 |
| Dell          | 00V62H A00                  | Desktop     | [da12f0d8e3](https://linux-hardware.org/?probe=da12f0d8e3) | Jun 16, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [989287c8b1](https://linux-hardware.org/?probe=989287c8b1) | Jun 16, 2023 |
| HP            | Laptop 14-bp0xx             | Notebook    | [fd6b492010](https://linux-hardware.org/?probe=fd6b492010) | Jun 16, 2023 |
| HP            | Pavilion dv6                | Notebook    | [55c83ec890](https://linux-hardware.org/?probe=55c83ec890) | Jun 15, 2023 |
| Dell          | Vostro 3420                 | Notebook    | [c1b8b07db0](https://linux-hardware.org/?probe=c1b8b07db0) | Jun 15, 2023 |
| System76      | Gazelle                     | Notebook    | [79c4236cdd](https://linux-hardware.org/?probe=79c4236cdd) | Jun 15, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [1bcfd50d08](https://linux-hardware.org/?probe=1bcfd50d08) | Jun 15, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [04b5148080](https://linux-hardware.org/?probe=04b5148080) | Jun 15, 2023 |
| HP            | Laptop 14-dk0xxx            | Notebook    | [1e6fdd560b](https://linux-hardware.org/?probe=1e6fdd560b) | Jun 14, 2023 |
| ZOTAC         | ZBOX-AD04                   | Mini pc     | [c7c537bd79](https://linux-hardware.org/?probe=c7c537bd79) | Jun 14, 2023 |
| ZOTAC         | ZBOX-AD04                   | Mini pc     | [42e6a44062](https://linux-hardware.org/?probe=42e6a44062) | Jun 14, 2023 |
| Lenovo        | ThinkPad P53s 20N6001UUS    | Notebook    | [667f0a20c1](https://linux-hardware.org/?probe=667f0a20c1) | Jun 14, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [17c4d68066](https://linux-hardware.org/?probe=17c4d68066) | Jun 14, 2023 |
| System76      | Gazelle                     | Notebook    | [117f199b15](https://linux-hardware.org/?probe=117f199b15) | Jun 14, 2023 |
| ATOPNUC       | MA90                        | Mini pc     | [384ee8b42e](https://linux-hardware.org/?probe=384ee8b42e) | Jun 13, 2023 |
| ASUSTek       | Zenbook UN5401RA UN5401R... | Convertible | [ad75eab286](https://linux-hardware.org/?probe=ad75eab286) | Jun 13, 2023 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [d7c90a9c25](https://linux-hardware.org/?probe=d7c90a9c25) | Jun 13, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [c17f7d87b3](https://linux-hardware.org/?probe=c17f7d87b3) | Jun 13, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b3303b8ed6](https://linux-hardware.org/?probe=b3303b8ed6) | Jun 13, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [b5294ee338](https://linux-hardware.org/?probe=b5294ee338) | Jun 13, 2023 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [5281ad2271](https://linux-hardware.org/?probe=5281ad2271) | Jun 13, 2023 |
| ASUSTek       | ROG Zephyrus Duo 15 SE G... | Notebook    | [fff5e11f1c](https://linux-hardware.org/?probe=fff5e11f1c) | Jun 13, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [d730799661](https://linux-hardware.org/?probe=d730799661) | Jun 12, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | Desktop     | [0190531869](https://linux-hardware.org/?probe=0190531869) | Jun 12, 2023 |
| ASRock        | Z690 Steel Legend WiFi 6... | Desktop     | [648161a6ff](https://linux-hardware.org/?probe=648161a6ff) | Jun 12, 2023 |
| ASUSTek       | Zenbook UP6502ZD_Q539ZD     | Convertible | [e2cd0602f8](https://linux-hardware.org/?probe=e2cd0602f8) | Jun 12, 2023 |
| Pegatron      | NARRA5                      | Desktop     | [3e7cbbb991](https://linux-hardware.org/?probe=3e7cbbb991) | Jun 12, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [fd51db661f](https://linux-hardware.org/?probe=fd51db661f) | Jun 12, 2023 |
| Dell          | Latitude E7470              | Notebook    | [1253de4554](https://linux-hardware.org/?probe=1253de4554) | Jun 12, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [1f4d0ebdc1](https://linux-hardware.org/?probe=1f4d0ebdc1) | Jun 12, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81G3      | Notebook    | [c09c4a0f69](https://linux-hardware.org/?probe=c09c4a0f69) | Jun 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [a9bb4cfb62](https://linux-hardware.org/?probe=a9bb4cfb62) | Jun 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [9c0f9bf219](https://linux-hardware.org/?probe=9c0f9bf219) | Jun 12, 2023 |
| Toshiba       | Satellite P55t-B            | Notebook    | [efc0f87778](https://linux-hardware.org/?probe=efc0f87778) | Jun 11, 2023 |
| BESSTAR Te... | B550                        | Desktop     | [b74cc9dfff](https://linux-hardware.org/?probe=b74cc9dfff) | Jun 11, 2023 |
| Pegatron      | NARRA5                      | Desktop     | [609c2921d3](https://linux-hardware.org/?probe=609c2921d3) | Jun 11, 2023 |
| HP            | Stream Laptop 11-ah0XX      | Notebook    | [a3e566ad38](https://linux-hardware.org/?probe=a3e566ad38) | Jun 11, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [86c52dcc7a](https://linux-hardware.org/?probe=86c52dcc7a) | Jun 11, 2023 |
| HP            | 89B5 A                      | Desktop     | [7bf638dc35](https://linux-hardware.org/?probe=7bf638dc35) | Jun 10, 2023 |
| MSI           | X99A GODLIKE GAMING         | Desktop     | [19511501c7](https://linux-hardware.org/?probe=19511501c7) | Jun 10, 2023 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [fd388e00c3](https://linux-hardware.org/?probe=fd388e00c3) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [6c8e1de1cf](https://linux-hardware.org/?probe=6c8e1de1cf) | Jun 10, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [d8dac01c79](https://linux-hardware.org/?probe=d8dac01c79) | Jun 10, 2023 |
| HP            | 8949 11                     | Desktop     | [f5e1f4b6c9](https://linux-hardware.org/?probe=f5e1f4b6c9) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [cac24c37e5](https://linux-hardware.org/?probe=cac24c37e5) | Jun 10, 2023 |
| Lenovo        | ThinkPad T540p 20BFS4P80... | Notebook    | [4160d59c4f](https://linux-hardware.org/?probe=4160d59c4f) | Jun 10, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [280baa2765](https://linux-hardware.org/?probe=280baa2765) | Jun 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0f42ca8c95](https://linux-hardware.org/?probe=0f42ca8c95) | Jun 09, 2023 |
| ASUSTek       | PRIME A520M-A II            | Desktop     | [176b4ca0bb](https://linux-hardware.org/?probe=176b4ca0bb) | Jun 09, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [50b022f065](https://linux-hardware.org/?probe=50b022f065) | Jun 09, 2023 |
| Acer          | Aspire 7750                 | Notebook    | [b0daafa057](https://linux-hardware.org/?probe=b0daafa057) | Jun 09, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [1189f6696f](https://linux-hardware.org/?probe=1189f6696f) | Jun 09, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [1256480fca](https://linux-hardware.org/?probe=1256480fca) | Jun 09, 2023 |
| ASUSTek       | M4A785G-HTPC                | Desktop     | [76304dfb4a](https://linux-hardware.org/?probe=76304dfb4a) | Jun 09, 2023 |
| AZW           | SEi                         | Desktop     | [2b085e7ed2](https://linux-hardware.org/?probe=2b085e7ed2) | Jun 09, 2023 |
| Dell          | Latitude E7240              | Notebook    | [e21cc2151b](https://linux-hardware.org/?probe=e21cc2151b) | Jun 08, 2023 |
| Dell          | Latitude E6420              | Notebook    | [d408418ddd](https://linux-hardware.org/?probe=d408418ddd) | Jun 08, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [975246674d](https://linux-hardware.org/?probe=975246674d) | Jun 08, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [348173e172](https://linux-hardware.org/?probe=348173e172) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [e355aa21b5](https://linux-hardware.org/?probe=e355aa21b5) | Jun 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M160... | Notebook    | [c5a1a47343](https://linux-hardware.org/?probe=c5a1a47343) | Jun 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [35c7fcb130](https://linux-hardware.org/?probe=35c7fcb130) | Jun 08, 2023 |
| HP            | Pavilion dv7                | Notebook    | [896e71aaaf](https://linux-hardware.org/?probe=896e71aaaf) | Jun 08, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [e127b4c2f4](https://linux-hardware.org/?probe=e127b4c2f4) | Jun 08, 2023 |
| Gigabyte      | M68M-S2P                    | Desktop     | [ee2b6b0279](https://linux-hardware.org/?probe=ee2b6b0279) | Jun 08, 2023 |
| MSI           | PRO B550M-VC WIFI           | Desktop     | [70c409a2b8](https://linux-hardware.org/?probe=70c409a2b8) | Jun 08, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [540fc1c58d](https://linux-hardware.org/?probe=540fc1c58d) | Jun 07, 2023 |
| Machcreato... | 14                          | Notebook    | [d889b02b13](https://linux-hardware.org/?probe=d889b02b13) | Jun 07, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [276844abe2](https://linux-hardware.org/?probe=276844abe2) | Jun 07, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [cc023db7a9](https://linux-hardware.org/?probe=cc023db7a9) | Jun 07, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [ee9c6252ae](https://linux-hardware.org/?probe=ee9c6252ae) | Jun 07, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | Notebook    | [7381bd00f3](https://linux-hardware.org/?probe=7381bd00f3) | Jun 07, 2023 |
| System76      | Thelio Mira thelio-mira-... | Desktop     | [d7d155d89d](https://linux-hardware.org/?probe=d7d155d89d) | Jun 07, 2023 |
| Dell          | Latitude E6420              | Notebook    | [620ca905d2](https://linux-hardware.org/?probe=620ca905d2) | Jun 07, 2023 |
| Dell          | Latitude 7200 2-in-1        | Tablet      | [4d60f57084](https://linux-hardware.org/?probe=4d60f57084) | Jun 07, 2023 |
| Machcreato... | 14                          | Notebook    | [f0a27a9f97](https://linux-hardware.org/?probe=f0a27a9f97) | Jun 06, 2023 |
| Lenovo        | ThinkPad T480s 20L8S3JE0... | Notebook    | [2834fee64f](https://linux-hardware.org/?probe=2834fee64f) | Jun 06, 2023 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [e6bf4ead0a](https://linux-hardware.org/?probe=e6bf4ead0a) | Jun 06, 2023 |
| Lenovo        | ThinkPad W520 427637U       | Notebook    | [1bec07891b](https://linux-hardware.org/?probe=1bec07891b) | Jun 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [841eeea3f9](https://linux-hardware.org/?probe=841eeea3f9) | Jun 05, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [afc9f50009](https://linux-hardware.org/?probe=afc9f50009) | Jun 05, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [804abce033](https://linux-hardware.org/?probe=804abce033) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [f53388e7df](https://linux-hardware.org/?probe=f53388e7df) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [6c151a9750](https://linux-hardware.org/?probe=6c151a9750) | Jun 05, 2023 |
| HP            | 15 Notebook PC              | Notebook    | [7c76016c9d](https://linux-hardware.org/?probe=7c76016c9d) | Jun 05, 2023 |
| Lenovo        | ThinkPad T540p 20BFS4P80... | Notebook    | [5dd18339de](https://linux-hardware.org/?probe=5dd18339de) | Jun 05, 2023 |
| ASUSTek       | ROG Flow X16 GV601RM_GV6... | Convertible | [5a2d788a64](https://linux-hardware.org/?probe=5a2d788a64) | Jun 05, 2023 |
| HP            | 8949 11                     | Desktop     | [06bca18276](https://linux-hardware.org/?probe=06bca18276) | Jun 04, 2023 |
| ASUSTek       | M4N72-E                     | Desktop     | [51d39945ec](https://linux-hardware.org/?probe=51d39945ec) | Jun 04, 2023 |
| MSI           | A55M-E33                    | Desktop     | [336b7f877d](https://linux-hardware.org/?probe=336b7f877d) | Jun 04, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [aafda7cf63](https://linux-hardware.org/?probe=aafda7cf63) | Jun 04, 2023 |
| Dell          | Inspiron 5437               | Notebook    | [d805b4ec1f](https://linux-hardware.org/?probe=d805b4ec1f) | Jun 03, 2023 |
| Foxconn       | A74ML-K                     | Desktop     | [7a4f7e239b](https://linux-hardware.org/?probe=7a4f7e239b) | Jun 03, 2023 |
| HP            | 8949 11                     | Desktop     | [f06749002f](https://linux-hardware.org/?probe=f06749002f) | Jun 03, 2023 |
| ASUSTek       | PRIME B365M-A               | Desktop     | [5c280bbd6c](https://linux-hardware.org/?probe=5c280bbd6c) | Jun 03, 2023 |
| MSI           | B150M MORTAR                | Desktop     | [3fc6303165](https://linux-hardware.org/?probe=3fc6303165) | Jun 03, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [e0008bd879](https://linux-hardware.org/?probe=e0008bd879) | Jun 03, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [979df15914](https://linux-hardware.org/?probe=979df15914) | Jun 03, 2023 |
| Dell          | Inspiron 7472               | Notebook    | [53b9d0dfa6](https://linux-hardware.org/?probe=53b9d0dfa6) | Jun 03, 2023 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9966a3f6d1](https://linux-hardware.org/?probe=9966a3f6d1) | Jun 03, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [71c4a65aae](https://linux-hardware.org/?probe=71c4a65aae) | Jun 03, 2023 |
| System76      | Oryx Pro                    | Notebook    | [b3b398ba61](https://linux-hardware.org/?probe=b3b398ba61) | Jun 03, 2023 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [2354c37832](https://linux-hardware.org/?probe=2354c37832) | Jun 02, 2023 |
| MSI           | Prestige 16 A12UD           | Notebook    | [b13e4f0242](https://linux-hardware.org/?probe=b13e4f0242) | Jun 02, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [b86be4f1de](https://linux-hardware.org/?probe=b86be4f1de) | Jun 02, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [a8f8239e40](https://linux-hardware.org/?probe=a8f8239e40) | Jun 02, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [7f2c514dff](https://linux-hardware.org/?probe=7f2c514dff) | Jun 02, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [ded9a8f554](https://linux-hardware.org/?probe=ded9a8f554) | Jun 02, 2023 |
| Acer          | Predator PH517-51           | Notebook    | [1de529b11c](https://linux-hardware.org/?probe=1de529b11c) | Jun 01, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [df7287f2c8](https://linux-hardware.org/?probe=df7287f2c8) | Jun 01, 2023 |
| HP            | 212A                        | Desktop     | [a0e56b03e2](https://linux-hardware.org/?probe=a0e56b03e2) | Jun 01, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [c33f531350](https://linux-hardware.org/?probe=c33f531350) | Jun 01, 2023 |
| System76      | Adder WS                    | Notebook    | [5cfa553a01](https://linux-hardware.org/?probe=5cfa553a01) | May 31, 2023 |
| MSI           | B350M BAZOOKA               | Desktop     | [a494d94087](https://linux-hardware.org/?probe=a494d94087) | May 31, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [16f1d67220](https://linux-hardware.org/?probe=16f1d67220) | May 31, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [d950f8b732](https://linux-hardware.org/?probe=d950f8b732) | May 31, 2023 |
| Acer          | Predator PH517-51           | Notebook    | [cc24e32ab1](https://linux-hardware.org/?probe=cc24e32ab1) | May 30, 2023 |
| MSI           | B350M PRO-VD PLUS           | Desktop     | [ca4e5a8f82](https://linux-hardware.org/?probe=ca4e5a8f82) | May 30, 2023 |
| BESSTAR Te... | HM90                        | Desktop     | [cb78f83d80](https://linux-hardware.org/?probe=cb78f83d80) | May 30, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [2334995ee9](https://linux-hardware.org/?probe=2334995ee9) | May 30, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [4f41d4f16f](https://linux-hardware.org/?probe=4f41d4f16f) | May 30, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [907448944d](https://linux-hardware.org/?probe=907448944d) | May 30, 2023 |
| AZW           | GTR V01                     | Mini pc     | [9144d0218a](https://linux-hardware.org/?probe=9144d0218a) | May 30, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [1793fc9d72](https://linux-hardware.org/?probe=1793fc9d72) | May 30, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | Notebook    | [83f869ee2a](https://linux-hardware.org/?probe=83f869ee2a) | May 30, 2023 |
| Lenovo        | ThinkPad T440p 20ANCTO1W... | Notebook    | [23af21bb34](https://linux-hardware.org/?probe=23af21bb34) | May 30, 2023 |
| ASUSTek       | F2A85-M                     | Desktop     | [94fda2dea0](https://linux-hardware.org/?probe=94fda2dea0) | May 30, 2023 |
| Toshiba       | Satellite P755              | Notebook    | [5dc8f46db5](https://linux-hardware.org/?probe=5dc8f46db5) | May 29, 2023 |
| ASUSTek       | M5A97                       | Desktop     | [650fb21fd0](https://linux-hardware.org/?probe=650fb21fd0) | May 29, 2023 |
| Avell High... | A70 MOB                     | Notebook    | [70e4c12911](https://linux-hardware.org/?probe=70e4c12911) | May 29, 2023 |
| Dell          | 0NM64V A01                  | Desktop     | [a109a924f0](https://linux-hardware.org/?probe=a109a924f0) | May 29, 2023 |
| ASUSTek       | TUF Gaming H770-PRO WIFI    | Desktop     | [6729d5ffa7](https://linux-hardware.org/?probe=6729d5ffa7) | May 29, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [bcad978a06](https://linux-hardware.org/?probe=bcad978a06) | May 29, 2023 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [505b123692](https://linux-hardware.org/?probe=505b123692) | May 29, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [331bbabc0e](https://linux-hardware.org/?probe=331bbabc0e) | May 29, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [8b1445b47c](https://linux-hardware.org/?probe=8b1445b47c) | May 29, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [06318d2354](https://linux-hardware.org/?probe=06318d2354) | May 29, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [c24eb2f7dd](https://linux-hardware.org/?probe=c24eb2f7dd) | May 29, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [4fc496bcc4](https://linux-hardware.org/?probe=4fc496bcc4) | May 29, 2023 |
| Lenovo        | ThinkPad T500 2056Y4R       | Notebook    | [dbd22d38bd](https://linux-hardware.org/?probe=dbd22d38bd) | May 28, 2023 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [2f1017a58e](https://linux-hardware.org/?probe=2f1017a58e) | May 28, 2023 |
| System76      | Adder WS                    | Notebook    | [d6de84e0c6](https://linux-hardware.org/?probe=d6de84e0c6) | May 28, 2023 |
| System76      | Adder WS                    | Notebook    | [5624c5b0e8](https://linux-hardware.org/?probe=5624c5b0e8) | May 28, 2023 |
| System76      | Adder WS                    | Notebook    | [2522fb534f](https://linux-hardware.org/?probe=2522fb534f) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1fde8a9c8c](https://linux-hardware.org/?probe=1fde8a9c8c) | May 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [439a2f1c9e](https://linux-hardware.org/?probe=439a2f1c9e) | May 28, 2023 |
| Lenovo        | ThinkPad T440p 20AWS1420... | Notebook    | [7faaacfcaf](https://linux-hardware.org/?probe=7faaacfcaf) | May 28, 2023 |
| AZW           | EQ                          | Desktop     | [8e6c18ebbb](https://linux-hardware.org/?probe=8e6c18ebbb) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M540... | Notebook    | [6b71e36a41](https://linux-hardware.org/?probe=6b71e36a41) | May 28, 2023 |
| AZW           | EQ                          | Desktop     | [98e5ea581c](https://linux-hardware.org/?probe=98e5ea581c) | May 28, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [46460561e1](https://linux-hardware.org/?probe=46460561e1) | May 27, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [b2672eb1db](https://linux-hardware.org/?probe=b2672eb1db) | May 27, 2023 |
| Lenovo        | Yoga 700-11ISK 80QE         | Notebook    | [149dfccfe7](https://linux-hardware.org/?probe=149dfccfe7) | May 27, 2023 |
| Google        | Kohaku                      | Notebook    | [2b46417afd](https://linux-hardware.org/?probe=2b46417afd) | May 27, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [07b70ac9e5](https://linux-hardware.org/?probe=07b70ac9e5) | May 27, 2023 |
| System76      | Galago Pro                  | Notebook    | [51cc594a01](https://linux-hardware.org/?probe=51cc594a01) | May 27, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [8d5c73bd4d](https://linux-hardware.org/?probe=8d5c73bd4d) | May 27, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [ea5ba11b48](https://linux-hardware.org/?probe=ea5ba11b48) | May 27, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [e74ee1390f](https://linux-hardware.org/?probe=e74ee1390f) | May 26, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [ce5179659e](https://linux-hardware.org/?probe=ce5179659e) | May 26, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [8f16767017](https://linux-hardware.org/?probe=8f16767017) | May 26, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ac75726738](https://linux-hardware.org/?probe=ac75726738) | May 26, 2023 |
| HP            | ZBook 17 G6                 | Notebook    | [177d184559](https://linux-hardware.org/?probe=177d184559) | May 26, 2023 |
| HP            | ZBook 17 G6                 | Notebook    | [56a8a0e368](https://linux-hardware.org/?probe=56a8a0e368) | May 26, 2023 |
| ASRock        | X300M-STX                   | Desktop     | [c3af0f3242](https://linux-hardware.org/?probe=c3af0f3242) | May 26, 2023 |
| ASUSTek       | TUF X299 MARK 1             | Desktop     | [9b2b467879](https://linux-hardware.org/?probe=9b2b467879) | May 26, 2023 |
| HP            | 0AA4h                       | Desktop     | [41ec821e77](https://linux-hardware.org/?probe=41ec821e77) | May 26, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [8c61dd5381](https://linux-hardware.org/?probe=8c61dd5381) | May 26, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [92223e639f](https://linux-hardware.org/?probe=92223e639f) | May 26, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [9a58438669](https://linux-hardware.org/?probe=9a58438669) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [a12e26f683](https://linux-hardware.org/?probe=a12e26f683) | May 26, 2023 |
| Dell          | Inspiron 7520               | Notebook    | [6d237fdf95](https://linux-hardware.org/?probe=6d237fdf95) | May 26, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [248bd35ba0](https://linux-hardware.org/?probe=248bd35ba0) | May 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [72f5c85f7f](https://linux-hardware.org/?probe=72f5c85f7f) | May 26, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [925f0e5016](https://linux-hardware.org/?probe=925f0e5016) | May 26, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [486d6ac497](https://linux-hardware.org/?probe=486d6ac497) | May 25, 2023 |
| ASUSTek       | X502CA                      | Notebook    | [7b19816353](https://linux-hardware.org/?probe=7b19816353) | May 25, 2023 |
| MSI           | Alpha 15 A3DDK              | Notebook    | [722e709153](https://linux-hardware.org/?probe=722e709153) | May 25, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [fcecd714d6](https://linux-hardware.org/?probe=fcecd714d6) | May 25, 2023 |
| Apple         | MacBookPro6,1               | Notebook    | [c8eb2c32b3](https://linux-hardware.org/?probe=c8eb2c32b3) | May 25, 2023 |
| Lenovo        | ThinkPad W540 20BHS0BD02    | Notebook    | [b6318da458](https://linux-hardware.org/?probe=b6318da458) | May 25, 2023 |
| Lenovo        | IdeaPad Y560                | Notebook    | [a8b595f03c](https://linux-hardware.org/?probe=a8b595f03c) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | Notebook    | [b3f6af4f8c](https://linux-hardware.org/?probe=b3f6af4f8c) | May 24, 2023 |
| Dell          | Precision 5470              | Notebook    | [e0a145106b](https://linux-hardware.org/?probe=e0a145106b) | May 24, 2023 |
| HP            | Laptop PC 15-e3000          | Notebook    | [29c9a90dc9](https://linux-hardware.org/?probe=29c9a90dc9) | May 24, 2023 |
| ASUSTek       | P8H67-M                     | Desktop     | [41755306e6](https://linux-hardware.org/?probe=41755306e6) | May 24, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [a38171543f](https://linux-hardware.org/?probe=a38171543f) | May 24, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [8e5402cb16](https://linux-hardware.org/?probe=8e5402cb16) | May 24, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [31ea0c4ab8](https://linux-hardware.org/?probe=31ea0c4ab8) | May 24, 2023 |
| Dell          | G15 5511                    | Notebook    | [3876065a3e](https://linux-hardware.org/?probe=3876065a3e) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [b7d26b3293](https://linux-hardware.org/?probe=b7d26b3293) | May 24, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [e3a554c09d](https://linux-hardware.org/?probe=e3a554c09d) | May 24, 2023 |
| Apple         | MacBookPro6,1               | Notebook    | [a8da820b95](https://linux-hardware.org/?probe=a8da820b95) | May 24, 2023 |
| Lenovo        | Yoga 920-13IKB 80Y7         | Convertible | [f339d13a59](https://linux-hardware.org/?probe=f339d13a59) | May 24, 2023 |
| HP            | 212A                        | Desktop     | [87b3c9809f](https://linux-hardware.org/?probe=87b3c9809f) | May 23, 2023 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [8604115d8b](https://linux-hardware.org/?probe=8604115d8b) | May 23, 2023 |
| HP            | Spectre Pro x360 G1         | Notebook    | [90df3b7bfa](https://linux-hardware.org/?probe=90df3b7bfa) | May 23, 2023 |
| HP            | Spectre Pro x360 G1         | Notebook    | [0f0ad128aa](https://linux-hardware.org/?probe=0f0ad128aa) | May 23, 2023 |
| Lenovo        | ThinkPad E595 20NFS0TH00    | Notebook    | [c843de4a39](https://linux-hardware.org/?probe=c843de4a39) | May 23, 2023 |
| MSI           | B150M MORTAR                | Desktop     | [c2b6ba6654](https://linux-hardware.org/?probe=c2b6ba6654) | May 23, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [da701ce37f](https://linux-hardware.org/?probe=da701ce37f) | May 23, 2023 |
| Acidanther... | Mac-77EB7D7DAF985301 iMa... | All in one  | [b021476220](https://linux-hardware.org/?probe=b021476220) | May 23, 2023 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [77ccb1431b](https://linux-hardware.org/?probe=77ccb1431b) | May 23, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [e781194fb3](https://linux-hardware.org/?probe=e781194fb3) | May 23, 2023 |
| Lenovo        | Unknown                     | Notebook    | [144302ab2c](https://linux-hardware.org/?probe=144302ab2c) | May 23, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [b0fac119c2](https://linux-hardware.org/?probe=b0fac119c2) | May 22, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [8226c82b49](https://linux-hardware.org/?probe=8226c82b49) | May 21, 2023 |
| ASUSTek       | X550CC                      | Notebook    | [6a8e6201be](https://linux-hardware.org/?probe=6a8e6201be) | May 21, 2023 |
| Lenovo        | Unknown                     | Notebook    | [1288108e10](https://linux-hardware.org/?probe=1288108e10) | May 21, 2023 |
| Unknown       | V00                         | Mini pc     | [7b8747aad5](https://linux-hardware.org/?probe=7b8747aad5) | May 21, 2023 |
| Lenovo        | ThinkPad T440p              | Notebook    | [b6c59c331b](https://linux-hardware.org/?probe=b6c59c331b) | May 21, 2023 |
| Apple         | MacBookPro5,3               | Notebook    | [0df526f042](https://linux-hardware.org/?probe=0df526f042) | May 21, 2023 |
| Dell          | G15 5511                    | Notebook    | [ad4c2a0521](https://linux-hardware.org/?probe=ad4c2a0521) | May 21, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [399ea93745](https://linux-hardware.org/?probe=399ea93745) | May 21, 2023 |
| Toshiba       | Satellite L855D             | Notebook    | [5be0280c53](https://linux-hardware.org/?probe=5be0280c53) | May 21, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [23fb35880e](https://linux-hardware.org/?probe=23fb35880e) | May 21, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [d52da23326](https://linux-hardware.org/?probe=d52da23326) | May 21, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [fb1832d859](https://linux-hardware.org/?probe=fb1832d859) | May 20, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [4c5dce3a01](https://linux-hardware.org/?probe=4c5dce3a01) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [51f87ac309](https://linux-hardware.org/?probe=51f87ac309) | May 20, 2023 |
| Gigabyte      | B660M AORUS PRO DDR4        | Desktop     | [6a3afbb593](https://linux-hardware.org/?probe=6a3afbb593) | May 20, 2023 |
| HP            | Pavilion dv6                | Notebook    | [51e808c93a](https://linux-hardware.org/?probe=51e808c93a) | May 20, 2023 |
| Dell          | 0VTJVC A00                  | Desktop     | [1acd938f30](https://linux-hardware.org/?probe=1acd938f30) | May 20, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [7384b29d21](https://linux-hardware.org/?probe=7384b29d21) | May 20, 2023 |
| Samsung       | DeskTop System              | Desktop     | [0f49fcc9e8](https://linux-hardware.org/?probe=0f49fcc9e8) | May 20, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [e16a632eca](https://linux-hardware.org/?probe=e16a632eca) | May 20, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [42e009b3c5](https://linux-hardware.org/?probe=42e009b3c5) | May 19, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [a5fdda0f63](https://linux-hardware.org/?probe=a5fdda0f63) | May 19, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [2cde0cc93d](https://linux-hardware.org/?probe=2cde0cc93d) | May 19, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [a100e90e0b](https://linux-hardware.org/?probe=a100e90e0b) | May 19, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [4a9869b7a6](https://linux-hardware.org/?probe=4a9869b7a6) | May 19, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [337509e694](https://linux-hardware.org/?probe=337509e694) | May 19, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [d51c5680e8](https://linux-hardware.org/?probe=d51c5680e8) | May 19, 2023 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [986792e4f0](https://linux-hardware.org/?probe=986792e4f0) | May 19, 2023 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [75d3691dae](https://linux-hardware.org/?probe=75d3691dae) | May 18, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [08df098150](https://linux-hardware.org/?probe=08df098150) | May 18, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [994adfd229](https://linux-hardware.org/?probe=994adfd229) | May 18, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [a74f787d52](https://linux-hardware.org/?probe=a74f787d52) | May 18, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [e28f96322d](https://linux-hardware.org/?probe=e28f96322d) | May 18, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [644878287e](https://linux-hardware.org/?probe=644878287e) | May 18, 2023 |
| Gigabyte      | H410M S2 V2                 | Desktop     | [9d2439e8d7](https://linux-hardware.org/?probe=9d2439e8d7) | May 18, 2023 |
| Reliance C... | R141TL5                     | Notebook    | [a21525c003](https://linux-hardware.org/?probe=a21525c003) | May 18, 2023 |
| ASUSTek       | SABERTOOTH Z77              | Desktop     | [06003cbcc2](https://linux-hardware.org/?probe=06003cbcc2) | May 18, 2023 |
| PS            | X570 Pro4                   | Desktop     | [cde38918e6](https://linux-hardware.org/?probe=cde38918e6) | May 18, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [a1cb84300e](https://linux-hardware.org/?probe=a1cb84300e) | May 18, 2023 |
| Dell          | Inspiron 5559               | Notebook    | [620177b4fa](https://linux-hardware.org/?probe=620177b4fa) | May 17, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | Notebook    | [a35e6c0b2d](https://linux-hardware.org/?probe=a35e6c0b2d) | May 17, 2023 |
| Dell          | Inspiron 14 5408            | Notebook    | [c1853f7df2](https://linux-hardware.org/?probe=c1853f7df2) | May 17, 2023 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [dd1e6376c2](https://linux-hardware.org/?probe=dd1e6376c2) | May 17, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [63c991635f](https://linux-hardware.org/?probe=63c991635f) | May 17, 2023 |
| Google        | Blorb                       | Notebook    | [7537bc5890](https://linux-hardware.org/?probe=7537bc5890) | May 17, 2023 |
| Dell          | 048DY8 A01                  | Desktop     | [aaf390dad1](https://linux-hardware.org/?probe=aaf390dad1) | May 17, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [add6bcd4f7](https://linux-hardware.org/?probe=add6bcd4f7) | May 16, 2023 |
| EVGA          | 151-HE-E999                 | Desktop     | [aa87f447d5](https://linux-hardware.org/?probe=aa87f447d5) | May 16, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [2616bd6b98](https://linux-hardware.org/?probe=2616bd6b98) | May 16, 2023 |
| Fujitsu       | D2924-A1 S26361-D2924-A1    | Desktop     | [af5b595698](https://linux-hardware.org/?probe=af5b595698) | May 16, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [9a08def3ae](https://linux-hardware.org/?probe=9a08def3ae) | May 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [d35caae2b6](https://linux-hardware.org/?probe=d35caae2b6) | May 15, 2023 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [9f4a8a37c0](https://linux-hardware.org/?probe=9f4a8a37c0) | May 15, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fd5291d10e](https://linux-hardware.org/?probe=fd5291d10e) | May 15, 2023 |
| HP            | OMEN by Laptop 17-cb0xxx    | Notebook    | [2192ceeebd](https://linux-hardware.org/?probe=2192ceeebd) | May 15, 2023 |
| ASRock        | B550 Phantom Gaming-ITX/... | Desktop     | [829665d7bf](https://linux-hardware.org/?probe=829665d7bf) | May 15, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [a7c2953571](https://linux-hardware.org/?probe=a7c2953571) | May 15, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | Notebook    | [681e1f8c61](https://linux-hardware.org/?probe=681e1f8c61) | May 15, 2023 |
| HP            | 3398                        | Desktop     | [7339f433ef](https://linux-hardware.org/?probe=7339f433ef) | May 15, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e21cdf9e37](https://linux-hardware.org/?probe=e21cdf9e37) | May 15, 2023 |
| MSI           | H61M-P23                    | Desktop     | [e6b643867b](https://linux-hardware.org/?probe=e6b643867b) | May 15, 2023 |
| ASUSTek       | X541UJ                      | Notebook    | [9be042ca8a](https://linux-hardware.org/?probe=9be042ca8a) | May 14, 2023 |
| Dell          | 02GDWG A00                  | Desktop     | [38a459c2e0](https://linux-hardware.org/?probe=38a459c2e0) | May 14, 2023 |
| EVGA          | 151-HE-E999                 | Desktop     | [a431f34e2b](https://linux-hardware.org/?probe=a431f34e2b) | May 14, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [3d3bfc28a6](https://linux-hardware.org/?probe=3d3bfc28a6) | May 14, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [c74505560b](https://linux-hardware.org/?probe=c74505560b) | May 14, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [f67b1d428b](https://linux-hardware.org/?probe=f67b1d428b) | May 14, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [e48ff4432d](https://linux-hardware.org/?probe=e48ff4432d) | May 14, 2023 |
| MSI           | H110I PRO                   | Desktop     | [1224d45c07](https://linux-hardware.org/?probe=1224d45c07) | May 14, 2023 |
| ASUSTek       | Q87M-E                      | Desktop     | [88a88bec15](https://linux-hardware.org/?probe=88a88bec15) | May 14, 2023 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [effc7c876e](https://linux-hardware.org/?probe=effc7c876e) | May 14, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [d26275a2de](https://linux-hardware.org/?probe=d26275a2de) | May 14, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [676c25e644](https://linux-hardware.org/?probe=676c25e644) | May 13, 2023 |
| HP            | Pavilion dv6                | Notebook    | [e20ba378ac](https://linux-hardware.org/?probe=e20ba378ac) | May 13, 2023 |
| Dell          | G7 7700                     | Notebook    | [6568ba5b4d](https://linux-hardware.org/?probe=6568ba5b4d) | May 13, 2023 |
| Gigabyte      | P34V7                       | Notebook    | [90e6e5d5d9](https://linux-hardware.org/?probe=90e6e5d5d9) | May 13, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1d4c35daa6](https://linux-hardware.org/?probe=1d4c35daa6) | May 13, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [275f194797](https://linux-hardware.org/?probe=275f194797) | May 13, 2023 |
| System76      | Galago Pro                  | Notebook    | [a30efb5622](https://linux-hardware.org/?probe=a30efb5622) | May 13, 2023 |
| Lenovo        | ThinkPad X230 23301E0       | Notebook    | [9a5e07f865](https://linux-hardware.org/?probe=9a5e07f865) | May 13, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ed810bd154](https://linux-hardware.org/?probe=ed810bd154) | May 13, 2023 |
| Dell          | Precision 3571              | Notebook    | [9a20dccb42](https://linux-hardware.org/?probe=9a20dccb42) | May 13, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [69a20b9c03](https://linux-hardware.org/?probe=69a20b9c03) | May 13, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [415306aabf](https://linux-hardware.org/?probe=415306aabf) | May 12, 2023 |
| System76      | Gazelle                     | Notebook    | [bd4e912b20](https://linux-hardware.org/?probe=bd4e912b20) | May 12, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [7dd8e30770](https://linux-hardware.org/?probe=7dd8e30770) | May 12, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [d6598957ff](https://linux-hardware.org/?probe=d6598957ff) | May 12, 2023 |
| Lenovo        | ThinkPad T590 20N4002WGE    | Notebook    | [6caedd8a7b](https://linux-hardware.org/?probe=6caedd8a7b) | May 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [cf7c801d5c](https://linux-hardware.org/?probe=cf7c801d5c) | May 12, 2023 |
| ASUSTek       | ZenBook UX431FN             | Notebook    | [ee40bf2168](https://linux-hardware.org/?probe=ee40bf2168) | May 12, 2023 |
| System76      | Gazelle                     | Notebook    | [83ef9e6d2d](https://linux-hardware.org/?probe=83ef9e6d2d) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [729a4181de](https://linux-hardware.org/?probe=729a4181de) | May 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3010c8760e](https://linux-hardware.org/?probe=3010c8760e) | May 12, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [ffffd119fb](https://linux-hardware.org/?probe=ffffd119fb) | May 12, 2023 |
| MSI           | 970A-G46                    | Desktop     | [6ad3215735](https://linux-hardware.org/?probe=6ad3215735) | May 12, 2023 |
| ASUSTek       | ROG STRIX X470-I GAMING     | Desktop     | [39f854e5de](https://linux-hardware.org/?probe=39f854e5de) | May 11, 2023 |
| ASUSTek       | ROG Zephyrus M16 GU603HM... | Notebook    | [f54531cd16](https://linux-hardware.org/?probe=f54531cd16) | May 11, 2023 |
| MSI           | Stealth 16Studio A13VG      | Notebook    | [7c232216fd](https://linux-hardware.org/?probe=7c232216fd) | May 11, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [eefa55009a](https://linux-hardware.org/?probe=eefa55009a) | May 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [a7155be531](https://linux-hardware.org/?probe=a7155be531) | May 11, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [f46fe8b9ee](https://linux-hardware.org/?probe=f46fe8b9ee) | May 11, 2023 |
| HP            | 158A                        | Desktop     | [a085c7a516](https://linux-hardware.org/?probe=a085c7a516) | May 11, 2023 |
| Dell          | 0T2HR0 A01                  | Desktop     | [96c6b065e8](https://linux-hardware.org/?probe=96c6b065e8) | May 11, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [5d50ca41ef](https://linux-hardware.org/?probe=5d50ca41ef) | May 11, 2023 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [0e8fab037b](https://linux-hardware.org/?probe=0e8fab037b) | May 11, 2023 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [96310a4cfe](https://linux-hardware.org/?probe=96310a4cfe) | May 11, 2023 |
| Apple         | Mac-FA842E06C61E91C5 iMa... | All in one  | [ed6a0c4e82](https://linux-hardware.org/?probe=ed6a0c4e82) | May 11, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [4276c0fd28](https://linux-hardware.org/?probe=4276c0fd28) | May 11, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [30036be67b](https://linux-hardware.org/?probe=30036be67b) | May 10, 2023 |
| Dell          | 07JJ74 A01                  | Server      | [8ba2d54929](https://linux-hardware.org/?probe=8ba2d54929) | May 10, 2023 |
| Gigabyte      | H97N-WIFI                   | Desktop     | [ceebdc263a](https://linux-hardware.org/?probe=ceebdc263a) | May 10, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | Desktop     | [5f3555ab64](https://linux-hardware.org/?probe=5f3555ab64) | May 10, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [e1e22ae448](https://linux-hardware.org/?probe=e1e22ae448) | May 10, 2023 |
| Dell          | 07JJ74 A01                  | Server      | [6d6dffc4fe](https://linux-hardware.org/?probe=6d6dffc4fe) | May 10, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [1fe1a8fcd2](https://linux-hardware.org/?probe=1fe1a8fcd2) | May 09, 2023 |
| ASUSTek       | Z170-K                      | Desktop     | [695a40ecc7](https://linux-hardware.org/?probe=695a40ecc7) | May 09, 2023 |
| MSI           | GL65 Leopard 10SCSR         | Notebook    | [4d9a7df494](https://linux-hardware.org/?probe=4d9a7df494) | May 09, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [28e1a5c2e9](https://linux-hardware.org/?probe=28e1a5c2e9) | May 09, 2023 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [fed7278850](https://linux-hardware.org/?probe=fed7278850) | May 09, 2023 |
| Lenovo        | ThinkPad T410 2522AA6       | Notebook    | [82755e3688](https://linux-hardware.org/?probe=82755e3688) | May 08, 2023 |
| ASUSTek       | P8Z77-I DELUXE              | Desktop     | [c40e865226](https://linux-hardware.org/?probe=c40e865226) | May 08, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [95dbf74d72](https://linux-hardware.org/?probe=95dbf74d72) | May 08, 2023 |
| ASUSTek       | M3N WS                      | Desktop     | [fb7920c5f9](https://linux-hardware.org/?probe=fb7920c5f9) | May 08, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [51eba04846](https://linux-hardware.org/?probe=51eba04846) | May 08, 2023 |
| Acer          | Aspire A715-72G             | Notebook    | [da1c6920b6](https://linux-hardware.org/?probe=da1c6920b6) | May 08, 2023 |
| Alienware     | Area-51m R2 A00             | Notebook    | [3cc417c9d9](https://linux-hardware.org/?probe=3cc417c9d9) | May 08, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [6bc581f37c](https://linux-hardware.org/?probe=6bc581f37c) | May 08, 2023 |
| ASUSTek       | P8P67-M                     | Desktop     | [386d7c9de4](https://linux-hardware.org/?probe=386d7c9de4) | May 07, 2023 |
| HP            | Pavilion dv6                | Notebook    | [978d2165ac](https://linux-hardware.org/?probe=978d2165ac) | May 07, 2023 |
| Dell          | 0T0MHW A03                  | Desktop     | [1945ccd76d](https://linux-hardware.org/?probe=1945ccd76d) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | Notebook    | [e81eb02947](https://linux-hardware.org/?probe=e81eb02947) | May 07, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [894029cc14](https://linux-hardware.org/?probe=894029cc14) | May 07, 2023 |
| Notebook      | N141CU                      | Notebook    | [535b4ca746](https://linux-hardware.org/?probe=535b4ca746) | May 07, 2023 |
| Dell          | 0T0MHW A03                  | Desktop     | [a5c758152f](https://linux-hardware.org/?probe=a5c758152f) | May 07, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [8c5b603452](https://linux-hardware.org/?probe=8c5b603452) | May 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [619dc53d25](https://linux-hardware.org/?probe=619dc53d25) | May 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [078d3ae45f](https://linux-hardware.org/?probe=078d3ae45f) | May 06, 2023 |
| Notebook      | P15SM                       | Notebook    | [dcea4ec037](https://linux-hardware.org/?probe=dcea4ec037) | May 06, 2023 |
| Packard Be... | EasyNote LM85               | Notebook    | [d37b9e6687](https://linux-hardware.org/?probe=d37b9e6687) | May 06, 2023 |
| Lenovo        | ThinkPad T580 20L9001HUS    | Notebook    | [4bad3ee37e](https://linux-hardware.org/?probe=4bad3ee37e) | May 06, 2023 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [ecb5894e85](https://linux-hardware.org/?probe=ecb5894e85) | May 06, 2023 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [7c3b61fab9](https://linux-hardware.org/?probe=7c3b61fab9) | May 05, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [fbe46d0c6e](https://linux-hardware.org/?probe=fbe46d0c6e) | May 05, 2023 |
| Gigabyte      | H310M H x.x                 | Desktop     | [fec056072d](https://linux-hardware.org/?probe=fec056072d) | May 05, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [f28f7150ba](https://linux-hardware.org/?probe=f28f7150ba) | May 05, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [fbd91068d3](https://linux-hardware.org/?probe=fbd91068d3) | May 05, 2023 |
| Positivo      | N4350                       | Notebook    | [ec0df546f9](https://linux-hardware.org/?probe=ec0df546f9) | May 05, 2023 |
| ASUSTek       | ZenBook UX431FN             | Notebook    | [3194ab7fa2](https://linux-hardware.org/?probe=3194ab7fa2) | May 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [eaf28f6af4](https://linux-hardware.org/?probe=eaf28f6af4) | May 05, 2023 |
| Toshiba       | TECRA R850                  | Notebook    | [bb41171733](https://linux-hardware.org/?probe=bb41171733) | May 05, 2023 |
| Dell          | 02GDWG A00                  | Desktop     | [7b9a0196b1](https://linux-hardware.org/?probe=7b9a0196b1) | May 05, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [7fd9fd4619](https://linux-hardware.org/?probe=7fd9fd4619) | May 04, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [040ab09ebe](https://linux-hardware.org/?probe=040ab09ebe) | May 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [139c809251](https://linux-hardware.org/?probe=139c809251) | May 04, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [5022c3993a](https://linux-hardware.org/?probe=5022c3993a) | May 04, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [95f75e1344](https://linux-hardware.org/?probe=95f75e1344) | May 04, 2023 |
| Dell          | Latitude 7370               | Notebook    | [6beab237df](https://linux-hardware.org/?probe=6beab237df) | May 04, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [2ab4f57ff6](https://linux-hardware.org/?probe=2ab4f57ff6) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [0767486bb6](https://linux-hardware.org/?probe=0767486bb6) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [3c6e20e260](https://linux-hardware.org/?probe=3c6e20e260) | May 04, 2023 |
| HP            | Unknown                     | Notebook    | [311e275897](https://linux-hardware.org/?probe=311e275897) | May 04, 2023 |
| MSI           | GV62 7RE                    | Notebook    | [1b048994c9](https://linux-hardware.org/?probe=1b048994c9) | May 04, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [3e13b2bc4a](https://linux-hardware.org/?probe=3e13b2bc4a) | May 04, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [b3ed654fde](https://linux-hardware.org/?probe=b3ed654fde) | May 04, 2023 |
| System76      | Oryx Pro                    | Notebook    | [cae9fadc38](https://linux-hardware.org/?probe=cae9fadc38) | May 04, 2023 |
| Dell          | 02GDWG A00                  | Desktop     | [46abb3e5c7](https://linux-hardware.org/?probe=46abb3e5c7) | May 03, 2023 |
| Lenovo        | Yoga 300-11IBY 80M0         | Notebook    | [a4a894bb7a](https://linux-hardware.org/?probe=a4a894bb7a) | May 03, 2023 |
| MSI           | B450M MORTAR                | Desktop     | [691239a442](https://linux-hardware.org/?probe=691239a442) | May 03, 2023 |
| HP            | Unknown                     | Notebook    | [122c1783c0](https://linux-hardware.org/?probe=122c1783c0) | May 03, 2023 |
| American M... | XA133PR110                  | Notebook    | [4c02a6f8da](https://linux-hardware.org/?probe=4c02a6f8da) | May 03, 2023 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [6cb7429ec6](https://linux-hardware.org/?probe=6cb7429ec6) | May 02, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [eae11b1ac4](https://linux-hardware.org/?probe=eae11b1ac4) | May 02, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | Notebook    | [9322206a7d](https://linux-hardware.org/?probe=9322206a7d) | May 02, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [ee33a17baa](https://linux-hardware.org/?probe=ee33a17baa) | May 02, 2023 |
| Toshiba       | PORTEGE Z30-A               | Notebook    | [ccc620956f](https://linux-hardware.org/?probe=ccc620956f) | May 02, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [d817c9a53f](https://linux-hardware.org/?probe=d817c9a53f) | May 02, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [a14544f923](https://linux-hardware.org/?probe=a14544f923) | May 02, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [3ba3358e4d](https://linux-hardware.org/?probe=3ba3358e4d) | May 02, 2023 |
| System76      | Oryx Pro                    | Notebook    | [8bd4f39eaa](https://linux-hardware.org/?probe=8bd4f39eaa) | May 02, 2023 |
| Lenovo        | ThinkPad W541 20EGS0B010    | Notebook    | [3f87bce0eb](https://linux-hardware.org/?probe=3f87bce0eb) | May 01, 2023 |
| System76      | Gazelle                     | Notebook    | [8a8de3e027](https://linux-hardware.org/?probe=8a8de3e027) | May 01, 2023 |
| EVGA          | 151-HE-E999                 | Desktop     | [b293ade39d](https://linux-hardware.org/?probe=b293ade39d) | May 01, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [37ba71ddb4](https://linux-hardware.org/?probe=37ba71ddb4) | May 01, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [1979bde291](https://linux-hardware.org/?probe=1979bde291) | May 01, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [b61c6e5277](https://linux-hardware.org/?probe=b61c6e5277) | May 01, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [3c82fea068](https://linux-hardware.org/?probe=3c82fea068) | May 01, 2023 |
| Dell          | Precision 5530              | Notebook    | [c8878b0f0f](https://linux-hardware.org/?probe=c8878b0f0f) | May 01, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [dc16d81ba0](https://linux-hardware.org/?probe=dc16d81ba0) | May 01, 2023 |
| Fujitsu       | D3223-A1 S26361-D3223-A1    | Desktop     | [9b6f7cea89](https://linux-hardware.org/?probe=9b6f7cea89) | May 01, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [80671ff25c](https://linux-hardware.org/?probe=80671ff25c) | May 01, 2023 |
| Lenovo        | ThinkPad P52s 20LCS1H100    | Notebook    | [34b877bcb5](https://linux-hardware.org/?probe=34b877bcb5) | May 01, 2023 |
| ASUSTek       | X455LJ                      | Notebook    | [4e252eab9f](https://linux-hardware.org/?probe=4e252eab9f) | May 01, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [0d5e9310d3](https://linux-hardware.org/?probe=0d5e9310d3) | Apr 30, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [9df1b688c0](https://linux-hardware.org/?probe=9df1b688c0) | Apr 30, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [875ae124a1](https://linux-hardware.org/?probe=875ae124a1) | Apr 30, 2023 |
| Dell          | Latitude E6430              | Notebook    | [4c20239367](https://linux-hardware.org/?probe=4c20239367) | Apr 30, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [04a7cea7cb](https://linux-hardware.org/?probe=04a7cea7cb) | Apr 29, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [4ac7cbf111](https://linux-hardware.org/?probe=4ac7cbf111) | Apr 29, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [3feeeb3341](https://linux-hardware.org/?probe=3feeeb3341) | Apr 29, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [8e0692ebe3](https://linux-hardware.org/?probe=8e0692ebe3) | Apr 29, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | Desktop     | [c203c197b7](https://linux-hardware.org/?probe=c203c197b7) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [af0c1ea83c](https://linux-hardware.org/?probe=af0c1ea83c) | Apr 29, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [7c8c5a4668](https://linux-hardware.org/?probe=7c8c5a4668) | Apr 29, 2023 |
| Intel         | DB75EN AAG39650-303         | Desktop     | [713c422641](https://linux-hardware.org/?probe=713c422641) | Apr 29, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [998427cdcf](https://linux-hardware.org/?probe=998427cdcf) | Apr 29, 2023 |
| HP            | 8054                        | Desktop     | [81a57b4a2f](https://linux-hardware.org/?probe=81a57b4a2f) | Apr 29, 2023 |
| Dell          | Inspiron 7706 2n1           | Convertible | [9a9fdf0dd3](https://linux-hardware.org/?probe=9a9fdf0dd3) | Apr 29, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [9b560392f5](https://linux-hardware.org/?probe=9b560392f5) | Apr 29, 2023 |
| Gigabyte      | H410M H                     | Desktop     | [3ea3271f4a](https://linux-hardware.org/?probe=3ea3271f4a) | Apr 29, 2023 |
| Dell          | 0P4T42 A01                  | All in one  | [323e28fded](https://linux-hardware.org/?probe=323e28fded) | Apr 29, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ARH7 8... | Notebook    | [39644ab1d4](https://linux-hardware.org/?probe=39644ab1d4) | Apr 28, 2023 |
| Lenovo        | ThinkPad T450 20BUS0B000    | Notebook    | [a2cbf65767](https://linux-hardware.org/?probe=a2cbf65767) | Apr 28, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [261c116001](https://linux-hardware.org/?probe=261c116001) | Apr 28, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [266688994a](https://linux-hardware.org/?probe=266688994a) | Apr 28, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [af0663fd52](https://linux-hardware.org/?probe=af0663fd52) | Apr 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [f1679a62d0](https://linux-hardware.org/?probe=f1679a62d0) | Apr 28, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [26c158df39](https://linux-hardware.org/?probe=26c158df39) | Apr 28, 2023 |
| HP            | ENVY 15                     | Notebook    | [d870c486c7](https://linux-hardware.org/?probe=d870c486c7) | Apr 27, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [f96c9382bd](https://linux-hardware.org/?probe=f96c9382bd) | Apr 27, 2023 |
| Dell          | Latitude D520               | Notebook    | [a643e2e424](https://linux-hardware.org/?probe=a643e2e424) | Apr 27, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [4363ca582a](https://linux-hardware.org/?probe=4363ca582a) | Apr 26, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [f5de49d5b3](https://linux-hardware.org/?probe=f5de49d5b3) | Apr 26, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | Desktop     | [83453e6960](https://linux-hardware.org/?probe=83453e6960) | Apr 26, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [208a0fc365](https://linux-hardware.org/?probe=208a0fc365) | Apr 26, 2023 |
| Intel         | B75                         | Desktop     | [72a3677ac2](https://linux-hardware.org/?probe=72a3677ac2) | Apr 26, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [d040f4ff16](https://linux-hardware.org/?probe=d040f4ff16) | Apr 26, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [a24f74af8e](https://linux-hardware.org/?probe=a24f74af8e) | Apr 26, 2023 |
| Lenovo        | ThinkPad L570 20J80021MD    | Notebook    | [26e9a466cd](https://linux-hardware.org/?probe=26e9a466cd) | Apr 26, 2023 |
| Intel         | X99H                        | Desktop     | [d0f8c22128](https://linux-hardware.org/?probe=d0f8c22128) | Apr 26, 2023 |
| System76      | Gazelle                     | Notebook    | [ca2e23db8d](https://linux-hardware.org/?probe=ca2e23db8d) | Apr 25, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [f797b7112c](https://linux-hardware.org/?probe=f797b7112c) | Apr 25, 2023 |
| HP            | ENVY 15                     | Notebook    | [3539894e49](https://linux-hardware.org/?probe=3539894e49) | Apr 25, 2023 |
| Dell          | Latitude 7400 2-in-1        | Convertible | [da35752b66](https://linux-hardware.org/?probe=da35752b66) | Apr 25, 2023 |
| ASRock        | Z370 Extreme4               | Desktop     | [0e46ae0751](https://linux-hardware.org/?probe=0e46ae0751) | Apr 25, 2023 |
| Lenovo        | 103D SDK0J40697 WIN 3305... | Desktop     | [f82b3152d0](https://linux-hardware.org/?probe=f82b3152d0) | Apr 25, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [517a694a82](https://linux-hardware.org/?probe=517a694a82) | Apr 25, 2023 |
| Acer          | E5-551G-871W                | Notebook    | [2730a30d89](https://linux-hardware.org/?probe=2730a30d89) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [42a0a6d5e4](https://linux-hardware.org/?probe=42a0a6d5e4) | Apr 25, 2023 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [7ab59d4ba9](https://linux-hardware.org/?probe=7ab59d4ba9) | Apr 25, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [05d2b26ee6](https://linux-hardware.org/?probe=05d2b26ee6) | Apr 25, 2023 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [0ef0676073](https://linux-hardware.org/?probe=0ef0676073) | Apr 25, 2023 |
| HP            | ENVY 15                     | Notebook    | [39d32b035a](https://linux-hardware.org/?probe=39d32b035a) | Apr 25, 2023 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [a06d7e1f82](https://linux-hardware.org/?probe=a06d7e1f82) | Apr 25, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [db176db0db](https://linux-hardware.org/?probe=db176db0db) | Apr 25, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [2f1eb3e6ee](https://linux-hardware.org/?probe=2f1eb3e6ee) | Apr 24, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [0d6740c2a8](https://linux-hardware.org/?probe=0d6740c2a8) | Apr 24, 2023 |
| Alienware     | 13 R2                       | Notebook    | [ee7a023f6d](https://linux-hardware.org/?probe=ee7a023f6d) | Apr 24, 2023 |
| G7-2011       | X79                         | Desktop     | [5070a0a7a7](https://linux-hardware.org/?probe=5070a0a7a7) | Apr 24, 2023 |
| ASRock        | A320M Pro4                  | Desktop     | [bfe26862f0](https://linux-hardware.org/?probe=bfe26862f0) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480 20L50003GE    | Notebook    | [1259bb0006](https://linux-hardware.org/?probe=1259bb0006) | Apr 24, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [074135d4f4](https://linux-hardware.org/?probe=074135d4f4) | Apr 24, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [f3c853b789](https://linux-hardware.org/?probe=f3c853b789) | Apr 23, 2023 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [0b29ee62f9](https://linux-hardware.org/?probe=0b29ee62f9) | Apr 23, 2023 |
| Alienware     | 13 R3                       | Notebook    | [f04b34f41d](https://linux-hardware.org/?probe=f04b34f41d) | Apr 23, 2023 |
| Packard Be... | IPOWER G3610                | Desktop     | [05de2306b0](https://linux-hardware.org/?probe=05de2306b0) | Apr 23, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [44ca7e29c0](https://linux-hardware.org/?probe=44ca7e29c0) | Apr 23, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [cd11cc0e25](https://linux-hardware.org/?probe=cd11cc0e25) | Apr 23, 2023 |
| Dell          | Inspiron 7737               | Notebook    | [50b75a71d3](https://linux-hardware.org/?probe=50b75a71d3) | Apr 23, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [1b475eaa99](https://linux-hardware.org/?probe=1b475eaa99) | Apr 23, 2023 |
| HP            | ZBook 15                    | Notebook    | [c7ae51efcd](https://linux-hardware.org/?probe=c7ae51efcd) | Apr 22, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [f639b8e21a](https://linux-hardware.org/?probe=f639b8e21a) | Apr 22, 2023 |
| Dell          | 0FDY5C A00                  | Desktop     | [c35628b7c7](https://linux-hardware.org/?probe=c35628b7c7) | Apr 22, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [1c76d0f5a4](https://linux-hardware.org/?probe=1c76d0f5a4) | Apr 22, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [332fdb5298](https://linux-hardware.org/?probe=332fdb5298) | Apr 22, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [1ed1930799](https://linux-hardware.org/?probe=1ed1930799) | Apr 21, 2023 |
| GPU Compan... | GWTC116-2                   | Notebook    | [8f7df56d73](https://linux-hardware.org/?probe=8f7df56d73) | Apr 21, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [7215ce49dd](https://linux-hardware.org/?probe=7215ce49dd) | Apr 21, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [b5022d8a2f](https://linux-hardware.org/?probe=b5022d8a2f) | Apr 21, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [68d07ba405](https://linux-hardware.org/?probe=68d07ba405) | Apr 20, 2023 |
| Dell          | Precision M6600             | Notebook    | [e71bf9e7bb](https://linux-hardware.org/?probe=e71bf9e7bb) | Apr 20, 2023 |
| Lenovo        | ThinkPad X220 4291WF5       | Notebook    | [4c78af0e05](https://linux-hardware.org/?probe=4c78af0e05) | Apr 20, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [573d482e45](https://linux-hardware.org/?probe=573d482e45) | Apr 20, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | Notebook    | [f9415c65e9](https://linux-hardware.org/?probe=f9415c65e9) | Apr 20, 2023 |
| Dell          | Inspiron 17 7000 Series ... | Notebook    | [6222d9b2b0](https://linux-hardware.org/?probe=6222d9b2b0) | Apr 19, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [cc76c44731](https://linux-hardware.org/?probe=cc76c44731) | Apr 19, 2023 |
| HP            | Compaq 6510b (KE131ET#AK... | Notebook    | [fc27cf4b3e](https://linux-hardware.org/?probe=fc27cf4b3e) | Apr 19, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0187ac7a0c](https://linux-hardware.org/?probe=0187ac7a0c) | Apr 19, 2023 |
| Lenovo        | ThinkPad T480s 20L8S6S30... | Notebook    | [9241adf5fb](https://linux-hardware.org/?probe=9241adf5fb) | Apr 19, 2023 |
| ASUSTek       | M5A78L-M LX V2              | Desktop     | [1e8a2bbf1d](https://linux-hardware.org/?probe=1e8a2bbf1d) | Apr 19, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [eedaf9f548](https://linux-hardware.org/?probe=eedaf9f548) | Apr 19, 2023 |
| American M... | XA133PR110                  | Notebook    | [5c634b7029](https://linux-hardware.org/?probe=5c634b7029) | Apr 19, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [0f058078c9](https://linux-hardware.org/?probe=0f058078c9) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [33b92210c7](https://linux-hardware.org/?probe=33b92210c7) | Apr 19, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [fe26aeffdd](https://linux-hardware.org/?probe=fe26aeffdd) | Apr 19, 2023 |
| ASUSTek       | X541UJ                      | Notebook    | [1aa63436a5](https://linux-hardware.org/?probe=1aa63436a5) | Apr 19, 2023 |
| Acer          | Aspire AV15-52              | Notebook    | [e1044f40e2](https://linux-hardware.org/?probe=e1044f40e2) | Apr 18, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [4abccb30eb](https://linux-hardware.org/?probe=4abccb30eb) | Apr 18, 2023 |
| Samsung       | DT1234567890 SAMSUNG_SW_... | Desktop     | [e84a6f3538](https://linux-hardware.org/?probe=e84a6f3538) | Apr 18, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [58b159ef8f](https://linux-hardware.org/?probe=58b159ef8f) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [c35c104c5e](https://linux-hardware.org/?probe=c35c104c5e) | Apr 18, 2023 |
| Lenovo        | ThinkPad A275 20KDS01T00    | Notebook    | [14df620b0a](https://linux-hardware.org/?probe=14df620b0a) | Apr 18, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [af6c719754](https://linux-hardware.org/?probe=af6c719754) | Apr 18, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [9c66c608f3](https://linux-hardware.org/?probe=9c66c608f3) | Apr 18, 2023 |
| Lenovo        | ThinkPad T480 20L50003GE    | Notebook    | [e779a9606f](https://linux-hardware.org/?probe=e779a9606f) | Apr 18, 2023 |
| Dell          | 08WKV3 A00                  | Desktop     | [091f305ccb](https://linux-hardware.org/?probe=091f305ccb) | Apr 18, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [f045e3f800](https://linux-hardware.org/?probe=f045e3f800) | Apr 18, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [f1baab4be4](https://linux-hardware.org/?probe=f1baab4be4) | Apr 17, 2023 |
| MSI           | PS42 Modern 8RC             | Notebook    | [459a84f65e](https://linux-hardware.org/?probe=459a84f65e) | Apr 17, 2023 |
| American M... | XA133PR110                  | Notebook    | [08b47e43a7](https://linux-hardware.org/?probe=08b47e43a7) | Apr 17, 2023 |
| Toshiba       | Satellite E45-B             | Notebook    | [ec0bb6bfc6](https://linux-hardware.org/?probe=ec0bb6bfc6) | Apr 17, 2023 |
| ASUSTek       | PRIME H670-PLUS D4          | Desktop     | [59f6a81039](https://linux-hardware.org/?probe=59f6a81039) | Apr 17, 2023 |
| Lenovo        | Legion 7 16IAX7 82TD        | Notebook    | [8f0188b2a1](https://linux-hardware.org/?probe=8f0188b2a1) | Apr 17, 2023 |
| Dell          | Inspiron 3541               | Notebook    | [dd409790ad](https://linux-hardware.org/?probe=dd409790ad) | Apr 17, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [55325c372c](https://linux-hardware.org/?probe=55325c372c) | Apr 17, 2023 |
| HP            | ENVY 17                     | Notebook    | [ba2c1aae76](https://linux-hardware.org/?probe=ba2c1aae76) | Apr 17, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [5e3f0907fa](https://linux-hardware.org/?probe=5e3f0907fa) | Apr 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [beac478abb](https://linux-hardware.org/?probe=beac478abb) | Apr 16, 2023 |
| Chuwi         | LarkBox Pro                 | Mini pc     | [9feb6e0d59](https://linux-hardware.org/?probe=9feb6e0d59) | Apr 16, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [cfc2be8311](https://linux-hardware.org/?probe=cfc2be8311) | Apr 16, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [be0c962cda](https://linux-hardware.org/?probe=be0c962cda) | Apr 16, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [8888f53504](https://linux-hardware.org/?probe=8888f53504) | Apr 16, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [3a7d52ef90](https://linux-hardware.org/?probe=3a7d52ef90) | Apr 16, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [6b126883e9](https://linux-hardware.org/?probe=6b126883e9) | Apr 16, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [9ac7ca1a63](https://linux-hardware.org/?probe=9ac7ca1a63) | Apr 16, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [762ad80f82](https://linux-hardware.org/?probe=762ad80f82) | Apr 16, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [3b20856ccc](https://linux-hardware.org/?probe=3b20856ccc) | Apr 16, 2023 |
| Acer          | Swift SFX14-41G             | Notebook    | [a0f08c4442](https://linux-hardware.org/?probe=a0f08c4442) | Apr 16, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [da31814636](https://linux-hardware.org/?probe=da31814636) | Apr 15, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [f7ce1b2ab5](https://linux-hardware.org/?probe=f7ce1b2ab5) | Apr 15, 2023 |
| Medion        | E15415                      | Notebook    | [fb905ef988](https://linux-hardware.org/?probe=fb905ef988) | Apr 15, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [1d253a4901](https://linux-hardware.org/?probe=1d253a4901) | Apr 15, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [e405d73576](https://linux-hardware.org/?probe=e405d73576) | Apr 15, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [f45051411c](https://linux-hardware.org/?probe=f45051411c) | Apr 15, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [aedbc43074](https://linux-hardware.org/?probe=aedbc43074) | Apr 15, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [a9d18f5eaa](https://linux-hardware.org/?probe=a9d18f5eaa) | Apr 15, 2023 |
| HP            | Pavilion g6                 | Notebook    | [a918284993](https://linux-hardware.org/?probe=a918284993) | Apr 15, 2023 |
| Dell          | 0HY9JP A02                  | Desktop     | [25a1ee5a25](https://linux-hardware.org/?probe=25a1ee5a25) | Apr 15, 2023 |
| Biostar       | A960D+V2                    | Desktop     | [da262e3956](https://linux-hardware.org/?probe=da262e3956) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [c30c14f9b0](https://linux-hardware.org/?probe=c30c14f9b0) | Apr 14, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [5ab7cc057f](https://linux-hardware.org/?probe=5ab7cc057f) | Apr 14, 2023 |
| Dell          | Precision 5550              | Notebook    | [1546772c9f](https://linux-hardware.org/?probe=1546772c9f) | Apr 14, 2023 |
| Dell          | Latitude E5440              | Notebook    | [a827218c2e](https://linux-hardware.org/?probe=a827218c2e) | Apr 14, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [871fd53afd](https://linux-hardware.org/?probe=871fd53afd) | Apr 14, 2023 |
| HP            | Laptop 15z-fc000            | Notebook    | [df47336192](https://linux-hardware.org/?probe=df47336192) | Apr 14, 2023 |
| HP            | Notebook                    | Notebook    | [79541411b2](https://linux-hardware.org/?probe=79541411b2) | Apr 14, 2023 |
| Gigabyte      | B650M AORUS ELITE AX        | Desktop     | [87b5989939](https://linux-hardware.org/?probe=87b5989939) | Apr 13, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [78ddf23352](https://linux-hardware.org/?probe=78ddf23352) | Apr 13, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [f57cf8ddf4](https://linux-hardware.org/?probe=f57cf8ddf4) | Apr 13, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [106963edf7](https://linux-hardware.org/?probe=106963edf7) | Apr 13, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5a86b52121](https://linux-hardware.org/?probe=5a86b52121) | Apr 13, 2023 |
| HP            | 8433 11                     | Desktop     | [911f2844c9](https://linux-hardware.org/?probe=911f2844c9) | Apr 13, 2023 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [df59296148](https://linux-hardware.org/?probe=df59296148) | Apr 13, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [eb84ecafb4](https://linux-hardware.org/?probe=eb84ecafb4) | Apr 13, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [df185fb277](https://linux-hardware.org/?probe=df185fb277) | Apr 12, 2023 |
| System76      | Pangolin                    | Notebook    | [1750f20c8d](https://linux-hardware.org/?probe=1750f20c8d) | Apr 12, 2023 |
| System76      | Thelio thelio-r3            | Desktop     | [3acd31b3be](https://linux-hardware.org/?probe=3acd31b3be) | Apr 12, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [1f12146974](https://linux-hardware.org/?probe=1f12146974) | Apr 12, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [0d8eb6aa86](https://linux-hardware.org/?probe=0d8eb6aa86) | Apr 12, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [9aadb88a2d](https://linux-hardware.org/?probe=9aadb88a2d) | Apr 12, 2023 |
| System76      | Thelio thelio-r3            | Desktop     | [7a1d69f216](https://linux-hardware.org/?probe=7a1d69f216) | Apr 12, 2023 |
| Gigabyte      | G1.Sniper M3-CF             | Desktop     | [d3ecd3c066](https://linux-hardware.org/?probe=d3ecd3c066) | Apr 12, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [94372e3520](https://linux-hardware.org/?probe=94372e3520) | Apr 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [0120f0db62](https://linux-hardware.org/?probe=0120f0db62) | Apr 12, 2023 |
| ASRock        | X370 Gaming-ITX/ac          | Desktop     | [29ed28536e](https://linux-hardware.org/?probe=29ed28536e) | Apr 12, 2023 |
| Dell          | G3 3579                     | Notebook    | [24d10a8497](https://linux-hardware.org/?probe=24d10a8497) | Apr 12, 2023 |
| Timi          | TM1707                      | Notebook    | [0e015e68ec](https://linux-hardware.org/?probe=0e015e68ec) | Apr 12, 2023 |
| Timi          | TM1707                      | Notebook    | [b611ba24ed](https://linux-hardware.org/?probe=b611ba24ed) | Apr 12, 2023 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [4c217a8a03](https://linux-hardware.org/?probe=4c217a8a03) | Apr 11, 2023 |
| BESSTAR Te... | GB1B                        | Mini pc     | [dc66113388](https://linux-hardware.org/?probe=dc66113388) | Apr 11, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [87059322b0](https://linux-hardware.org/?probe=87059322b0) | Apr 11, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [63574c5adf](https://linux-hardware.org/?probe=63574c5adf) | Apr 11, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [73233d1c4c](https://linux-hardware.org/?probe=73233d1c4c) | Apr 11, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [02d670e0db](https://linux-hardware.org/?probe=02d670e0db) | Apr 11, 2023 |
| MSI           | B350 GAMING PLUS            | Desktop     | [df2f924a6e](https://linux-hardware.org/?probe=df2f924a6e) | Apr 11, 2023 |
| Samsung       | 760XDA                      | Notebook    | [bdc1648c05](https://linux-hardware.org/?probe=bdc1648c05) | Apr 11, 2023 |
| Dell          | Latitude 5590               | Notebook    | [f8f0f0125f](https://linux-hardware.org/?probe=f8f0f0125f) | Apr 11, 2023 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [c48286f8a2](https://linux-hardware.org/?probe=c48286f8a2) | Apr 10, 2023 |
| MSI           | H81M-P33                    | Desktop     | [129abe0b90](https://linux-hardware.org/?probe=129abe0b90) | Apr 10, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [85a39124f3](https://linux-hardware.org/?probe=85a39124f3) | Apr 09, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [beeb850c3b](https://linux-hardware.org/?probe=beeb850c3b) | Apr 09, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [0844c71fd0](https://linux-hardware.org/?probe=0844c71fd0) | Apr 07, 2023 |
| System76      | Oryx Pro                    | Notebook    | [a221f4f9d4](https://linux-hardware.org/?probe=a221f4f9d4) | Apr 06, 2023 |
| ASRock        | B650M PG Riptide WiFi       | Desktop     | [8302310eaf](https://linux-hardware.org/?probe=8302310eaf) | Apr 06, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [645fe56eb3](https://linux-hardware.org/?probe=645fe56eb3) | Apr 06, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [c963121074](https://linux-hardware.org/?probe=c963121074) | Apr 06, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [06d1f0e63f](https://linux-hardware.org/?probe=06d1f0e63f) | Apr 06, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [769d886cc9](https://linux-hardware.org/?probe=769d886cc9) | Apr 05, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [de7d3ba0c0](https://linux-hardware.org/?probe=de7d3ba0c0) | Apr 05, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [d1f4197f52](https://linux-hardware.org/?probe=d1f4197f52) | Apr 05, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [eb35e0beff](https://linux-hardware.org/?probe=eb35e0beff) | Apr 05, 2023 |
| MSI           | B75MA-E33                   | Desktop     | [d89431372f](https://linux-hardware.org/?probe=d89431372f) | Apr 05, 2023 |
| MSI           | 970 GAMING                  | Desktop     | [87b536f504](https://linux-hardware.org/?probe=87b536f504) | Apr 05, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [add0dfc4ca](https://linux-hardware.org/?probe=add0dfc4ca) | Apr 05, 2023 |
| PS            | X570 Pro4                   | Desktop     | [f67323ef28](https://linux-hardware.org/?probe=f67323ef28) | Apr 05, 2023 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [6f3f9cf977](https://linux-hardware.org/?probe=6f3f9cf977) | Apr 05, 2023 |
| Razer         | Blade                       | Notebook    | [351fe907cb](https://linux-hardware.org/?probe=351fe907cb) | Apr 05, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [fb0dc3cc20](https://linux-hardware.org/?probe=fb0dc3cc20) | Apr 05, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [c77ef60bcc](https://linux-hardware.org/?probe=c77ef60bcc) | Apr 05, 2023 |
| Unknown       | X99-GT                      | Desktop     | [d4b6b3ebe8](https://linux-hardware.org/?probe=d4b6b3ebe8) | Apr 05, 2023 |
| HP            | Laptop 14-dq0xxx            | Notebook    | [ba87782532](https://linux-hardware.org/?probe=ba87782532) | Apr 05, 2023 |
| Lenovo        | Edge 15 80K9                | Notebook    | [911d261c1b](https://linux-hardware.org/?probe=911d261c1b) | Apr 05, 2023 |
| ASUSTek       | N76VZ                       | Notebook    | [d87006e429](https://linux-hardware.org/?probe=d87006e429) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [3f886e678f](https://linux-hardware.org/?probe=3f886e678f) | Apr 05, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [43e4869357](https://linux-hardware.org/?probe=43e4869357) | Apr 05, 2023 |
| Lenovo        | ThinkBook 15-IML 20RW       | Notebook    | [58f5904dec](https://linux-hardware.org/?probe=58f5904dec) | Apr 04, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [29dc58335f](https://linux-hardware.org/?probe=29dc58335f) | Apr 04, 2023 |
| HP            | 8522 A01                    | Mini pc     | [28b79ea28b](https://linux-hardware.org/?probe=28b79ea28b) | Apr 04, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [7a5ee5da76](https://linux-hardware.org/?probe=7a5ee5da76) | Apr 04, 2023 |
| Dell          | 0DF42J A00                  | Desktop     | [056818267b](https://linux-hardware.org/?probe=056818267b) | Apr 04, 2023 |
| Dell          | Inspiron 7375               | Notebook    | [0d8465f75c](https://linux-hardware.org/?probe=0d8465f75c) | Apr 04, 2023 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [d56565f374](https://linux-hardware.org/?probe=d56565f374) | Apr 04, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [84f877fde3](https://linux-hardware.org/?probe=84f877fde3) | Apr 04, 2023 |
| ASUSTek       | E201NA                      | Notebook    | [098fb721f8](https://linux-hardware.org/?probe=098fb721f8) | Apr 04, 2023 |
| MSI           | H310M PRO-VH PLUS           | Desktop     | [606eb36d59](https://linux-hardware.org/?probe=606eb36d59) | Apr 04, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [a964b0aa55](https://linux-hardware.org/?probe=a964b0aa55) | Apr 04, 2023 |
| Razer         | Blade Stealth               | Notebook    | [2cf4a53eb5](https://linux-hardware.org/?probe=2cf4a53eb5) | Apr 04, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [98a0bf82e1](https://linux-hardware.org/?probe=98a0bf82e1) | Apr 04, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [c621d48717](https://linux-hardware.org/?probe=c621d48717) | Apr 04, 2023 |
| Dell          | Latitude E7240              | Notebook    | [fce3da8380](https://linux-hardware.org/?probe=fce3da8380) | Apr 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [190b5364e1](https://linux-hardware.org/?probe=190b5364e1) | Apr 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [a6a766a40a](https://linux-hardware.org/?probe=a6a766a40a) | Apr 03, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [b65273209b](https://linux-hardware.org/?probe=b65273209b) | Apr 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [9880810adc](https://linux-hardware.org/?probe=9880810adc) | Apr 03, 2023 |
| MSI           | GV62 7RE                    | Notebook    | [5d441311f4](https://linux-hardware.org/?probe=5d441311f4) | Apr 03, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [777f7d0fc4](https://linux-hardware.org/?probe=777f7d0fc4) | Apr 03, 2023 |
| MSI           | GL63 8RC                    | Notebook    | [8c90ec7da1](https://linux-hardware.org/?probe=8c90ec7da1) | Apr 03, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [f013c5ca48](https://linux-hardware.org/?probe=f013c5ca48) | Apr 03, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [1e66b2ab37](https://linux-hardware.org/?probe=1e66b2ab37) | Apr 03, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [edb2f4188e](https://linux-hardware.org/?probe=edb2f4188e) | Apr 03, 2023 |
| HP            | 650                         | Notebook    | [bcb4e8d60a](https://linux-hardware.org/?probe=bcb4e8d60a) | Apr 03, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [daa2099403](https://linux-hardware.org/?probe=daa2099403) | Apr 03, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [0385e01f4d](https://linux-hardware.org/?probe=0385e01f4d) | Apr 02, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [20b1ee364f](https://linux-hardware.org/?probe=20b1ee364f) | Apr 02, 2023 |
| Lenovo        | ThinkPad T470 20HES0FA03    | Notebook    | [7274c8222b](https://linux-hardware.org/?probe=7274c8222b) | Apr 02, 2023 |
| Lenovo        | ThinkPad T460p 20FXS08N0... | Notebook    | [ffcf174547](https://linux-hardware.org/?probe=ffcf174547) | Apr 02, 2023 |
| Apple         | MacBook3,1                  | Notebook    | [44f31f3094](https://linux-hardware.org/?probe=44f31f3094) | Apr 02, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [a700fbd33d](https://linux-hardware.org/?probe=a700fbd33d) | Apr 02, 2023 |
| MSI           | B350 GAMING PRO CARBON      | Desktop     | [0ffb7303f2](https://linux-hardware.org/?probe=0ffb7303f2) | Apr 02, 2023 |
| HP            | 0AA4h                       | Desktop     | [9b84d8c935](https://linux-hardware.org/?probe=9b84d8c935) | Apr 02, 2023 |
| Lenovo        | IdeaPadFlex 5 15IIL05 81... | Convertible | [70fb19c0db](https://linux-hardware.org/?probe=70fb19c0db) | Apr 02, 2023 |
| System76      | Kudu                        | Notebook    | [2baafe374c](https://linux-hardware.org/?probe=2baafe374c) | Apr 02, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [cf9da855fc](https://linux-hardware.org/?probe=cf9da855fc) | Apr 02, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [76a94d8c87](https://linux-hardware.org/?probe=76a94d8c87) | Apr 02, 2023 |
| Sony          | VPCSC1AFM                   | Notebook    | [854b8bfa02](https://linux-hardware.org/?probe=854b8bfa02) | Apr 01, 2023 |
| Lenovo        | ThinkPad T570 W10DG 20JX... | Notebook    | [51c7ed9156](https://linux-hardware.org/?probe=51c7ed9156) | Apr 01, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [ab9916feea](https://linux-hardware.org/?probe=ab9916feea) | Apr 01, 2023 |
| BESSTAR Te... | HM80                        | Desktop     | [4242425ada](https://linux-hardware.org/?probe=4242425ada) | Apr 01, 2023 |
| BESSTAR Te... | HM80                        | Desktop     | [702890870e](https://linux-hardware.org/?probe=702890870e) | Apr 01, 2023 |
| Lenovo        | Slim 7 16ARH7 82UX          | Notebook    | [cca7093e15](https://linux-hardware.org/?probe=cca7093e15) | Apr 01, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [5dddcdcb25](https://linux-hardware.org/?probe=5dddcdcb25) | Apr 01, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [277d3c7f43](https://linux-hardware.org/?probe=277d3c7f43) | Apr 01, 2023 |
| Dell          | Latitude 7275               | Tablet      | [c118ca04bc](https://linux-hardware.org/?probe=c118ca04bc) | Apr 01, 2023 |
| Lenovo        | IdeaPad U310                | Notebook    | [6add75e18c](https://linux-hardware.org/?probe=6add75e18c) | Apr 01, 2023 |
| Lenovo        | 4030                        | Desktop     | [7a23fd4fb4](https://linux-hardware.org/?probe=7a23fd4fb4) | Apr 01, 2023 |
| Toshiba       | Satellite L45-B             | Notebook    | [6d4878cdbf](https://linux-hardware.org/?probe=6d4878cdbf) | Apr 01, 2023 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [f7c90851ac](https://linux-hardware.org/?probe=f7c90851ac) | Apr 01, 2023 |
| HP            | 240 G6 Notebook PC          | Notebook    | [44e093df31](https://linux-hardware.org/?probe=44e093df31) | Apr 01, 2023 |
| System76      | Lemur Pro                   | Notebook    | [5d57a3397e](https://linux-hardware.org/?probe=5d57a3397e) | Mar 31, 2023 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [fc44ad8c07](https://linux-hardware.org/?probe=fc44ad8c07) | Mar 31, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [6f4a645737](https://linux-hardware.org/?probe=6f4a645737) | Mar 31, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [61e2653466](https://linux-hardware.org/?probe=61e2653466) | Mar 31, 2023 |
| ASUSTek       | P8H67-M LE                  | Desktop     | [11b3a7cdb1](https://linux-hardware.org/?probe=11b3a7cdb1) | Mar 31, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [2ef82331de](https://linux-hardware.org/?probe=2ef82331de) | Mar 31, 2023 |
| Supermicro    | X10SLV                      | Server      | [b61612a8a8](https://linux-hardware.org/?probe=b61612a8a8) | Mar 31, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [c346cf16d3](https://linux-hardware.org/?probe=c346cf16d3) | Mar 30, 2023 |
| Acer          | Aspire A515-56              | Notebook    | [bf846cebb9](https://linux-hardware.org/?probe=bf846cebb9) | Mar 30, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [27befad01f](https://linux-hardware.org/?probe=27befad01f) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [21515b7373](https://linux-hardware.org/?probe=21515b7373) | Mar 30, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [080e22fdb2](https://linux-hardware.org/?probe=080e22fdb2) | Mar 30, 2023 |
| HP            | 0AA4h                       | Desktop     | [97457bb10c](https://linux-hardware.org/?probe=97457bb10c) | Mar 30, 2023 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [af4901f141](https://linux-hardware.org/?probe=af4901f141) | Mar 30, 2023 |
| Apple         | Mac-F2268CC8                | All in one  | [cec51b833f](https://linux-hardware.org/?probe=cec51b833f) | Mar 30, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [13f35137bd](https://linux-hardware.org/?probe=13f35137bd) | Mar 30, 2023 |
| Foxconn       | 2AB1 DVT                    | Desktop     | [a9e8e4d4b0](https://linux-hardware.org/?probe=a9e8e4d4b0) | Mar 30, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [81dda92e58](https://linux-hardware.org/?probe=81dda92e58) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [7ee1845d96](https://linux-hardware.org/?probe=7ee1845d96) | Mar 30, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [bb80f561a2](https://linux-hardware.org/?probe=bb80f561a2) | Mar 30, 2023 |
| HP            | 8433 11                     | Desktop     | [55f7473ba8](https://linux-hardware.org/?probe=55f7473ba8) | Mar 29, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [854490056d](https://linux-hardware.org/?probe=854490056d) | Mar 29, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [059358e49b](https://linux-hardware.org/?probe=059358e49b) | Mar 29, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [78046d9b99](https://linux-hardware.org/?probe=78046d9b99) | Mar 29, 2023 |
| HP            | 0AA4h                       | Desktop     | [801f843749](https://linux-hardware.org/?probe=801f843749) | Mar 29, 2023 |
| Win elemen... | M600                        | Desktop     | [7cf2343b6f](https://linux-hardware.org/?probe=7cf2343b6f) | Mar 29, 2023 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [c994f20b64](https://linux-hardware.org/?probe=c994f20b64) | Mar 29, 2023 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [af48722867](https://linux-hardware.org/?probe=af48722867) | Mar 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0667374075](https://linux-hardware.org/?probe=0667374075) | Mar 28, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [0aabfe954d](https://linux-hardware.org/?probe=0aabfe954d) | Mar 28, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [7939320fa4](https://linux-hardware.org/?probe=7939320fa4) | Mar 28, 2023 |
| Positivo      | Mobile                      | Notebook    | [60fd382fbf](https://linux-hardware.org/?probe=60fd382fbf) | Mar 28, 2023 |
| Positivo      | Mobile                      | Notebook    | [b08c430903](https://linux-hardware.org/?probe=b08c430903) | Mar 28, 2023 |
| HP            | 09F0h                       | Desktop     | [540ec71101](https://linux-hardware.org/?probe=540ec71101) | Mar 28, 2023 |
| Razer         | Blade                       | Notebook    | [ffa791eb4a](https://linux-hardware.org/?probe=ffa791eb4a) | Mar 28, 2023 |
| ASUSTek       | X751LD                      | Notebook    | [61382d0bd8](https://linux-hardware.org/?probe=61382d0bd8) | Mar 28, 2023 |
| ASRock        | H510M-HVS                   | Desktop     | [97744fad07](https://linux-hardware.org/?probe=97744fad07) | Mar 28, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [d2b4780094](https://linux-hardware.org/?probe=d2b4780094) | Mar 28, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [635309aff4](https://linux-hardware.org/?probe=635309aff4) | Mar 28, 2023 |
| ASRock        | B650M PG Riptide WiFi       | Desktop     | [f17c95f91b](https://linux-hardware.org/?probe=f17c95f91b) | Mar 28, 2023 |
| ASRock        | B650M PG Riptide WiFi       | Desktop     | [1b67e2c4fd](https://linux-hardware.org/?probe=1b67e2c4fd) | Mar 28, 2023 |
| MSI           | MPG X670E CARBON WIFI       | Desktop     | [cde470cb39](https://linux-hardware.org/?probe=cde470cb39) | Mar 28, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [c4bba42d7b](https://linux-hardware.org/?probe=c4bba42d7b) | Mar 28, 2023 |
| Lenovo        | ThinkPad P50 20EQS0T400     | Notebook    | [5b4466c085](https://linux-hardware.org/?probe=5b4466c085) | Mar 28, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | Notebook    | [8ddee342c9](https://linux-hardware.org/?probe=8ddee342c9) | Mar 28, 2023 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [adee3bbdde](https://linux-hardware.org/?probe=adee3bbdde) | Mar 28, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [f6236c5962](https://linux-hardware.org/?probe=f6236c5962) | Mar 27, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [5be538736f](https://linux-hardware.org/?probe=5be538736f) | Mar 27, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [d7ec0eb4b1](https://linux-hardware.org/?probe=d7ec0eb4b1) | Mar 27, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [878fa94b87](https://linux-hardware.org/?probe=878fa94b87) | Mar 26, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [a5c200217f](https://linux-hardware.org/?probe=a5c200217f) | Mar 26, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [8ffc3ea292](https://linux-hardware.org/?probe=8ffc3ea292) | Mar 26, 2023 |
| MSI           | Z490 PLUS                   | Desktop     | [06032b5e04](https://linux-hardware.org/?probe=06032b5e04) | Mar 26, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | Desktop     | [479aff4877](https://linux-hardware.org/?probe=479aff4877) | Mar 26, 2023 |
| MSI           | GL63 8RC                    | Notebook    | [935b78c3da](https://linux-hardware.org/?probe=935b78c3da) | Mar 26, 2023 |
| Lenovo        | CRESCENTBAY SDK0J40677 W... | Desktop     | [67ddc813cf](https://linux-hardware.org/?probe=67ddc813cf) | Mar 26, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [537fc6af0e](https://linux-hardware.org/?probe=537fc6af0e) | Mar 26, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [55c29cec29](https://linux-hardware.org/?probe=55c29cec29) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [fc01cd79a4](https://linux-hardware.org/?probe=fc01cd79a4) | Mar 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c08caf1dee](https://linux-hardware.org/?probe=c08caf1dee) | Mar 26, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [905078c7b9](https://linux-hardware.org/?probe=905078c7b9) | Mar 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [f6f4996c63](https://linux-hardware.org/?probe=f6f4996c63) | Mar 26, 2023 |
| Dell          | Latitude E7240              | Notebook    | [3d91b46fda](https://linux-hardware.org/?probe=3d91b46fda) | Mar 26, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [3f3967267f](https://linux-hardware.org/?probe=3f3967267f) | Mar 26, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [61897b32de](https://linux-hardware.org/?probe=61897b32de) | Mar 25, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [0f7d28bd43](https://linux-hardware.org/?probe=0f7d28bd43) | Mar 25, 2023 |
| HP            | Spectre Laptop 13-af0xx     | Notebook    | [6fdc683220](https://linux-hardware.org/?probe=6fdc683220) | Mar 25, 2023 |
| MSI           | Katana GF66 12UG            | Notebook    | [9e03ac14c0](https://linux-hardware.org/?probe=9e03ac14c0) | Mar 25, 2023 |
| Intel         | NUC10i3FNB K61362-305       | Mini pc     | [26c0bb67b6](https://linux-hardware.org/?probe=26c0bb67b6) | Mar 25, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [811be842de](https://linux-hardware.org/?probe=811be842de) | Mar 25, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [21c3ce9508](https://linux-hardware.org/?probe=21c3ce9508) | Mar 24, 2023 |
| Dell          | 0PC5F7 A01                  | Desktop     | [61550296b7](https://linux-hardware.org/?probe=61550296b7) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ac415822b8](https://linux-hardware.org/?probe=ac415822b8) | Mar 24, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [ad0e5c0483](https://linux-hardware.org/?probe=ad0e5c0483) | Mar 24, 2023 |
| Dell          | Latitude 5420               | Notebook    | [e6afbbee47](https://linux-hardware.org/?probe=e6afbbee47) | Mar 24, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [f78f58795c](https://linux-hardware.org/?probe=f78f58795c) | Mar 24, 2023 |
| HP            | 212B                        | Desktop     | [266912cedd](https://linux-hardware.org/?probe=266912cedd) | Mar 24, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f5cbf68e6d](https://linux-hardware.org/?probe=f5cbf68e6d) | Mar 24, 2023 |
| Alienware     | 17 R4                       | Notebook    | [3c456dc309](https://linux-hardware.org/?probe=3c456dc309) | Mar 24, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [9007c1d23f](https://linux-hardware.org/?probe=9007c1d23f) | Mar 24, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Notebook    | [f8f47e3220](https://linux-hardware.org/?probe=f8f47e3220) | Mar 23, 2023 |
| Dell          | Precision 7710              | Notebook    | [25a4797475](https://linux-hardware.org/?probe=25a4797475) | Mar 23, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [09fec047e4](https://linux-hardware.org/?probe=09fec047e4) | Mar 23, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [3a75d7fb8d](https://linux-hardware.org/?probe=3a75d7fb8d) | Mar 23, 2023 |
| MSI           | MPG Z590 GAMING FORCE       | Desktop     | [7a3319972e](https://linux-hardware.org/?probe=7a3319972e) | Mar 23, 2023 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [c06eaca849](https://linux-hardware.org/?probe=c06eaca849) | Mar 23, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [aba9609828](https://linux-hardware.org/?probe=aba9609828) | Mar 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [f6580b20d3](https://linux-hardware.org/?probe=f6580b20d3) | Mar 22, 2023 |
| Lenovo        | Yoga 6 13ALC7 82UD          | Convertible | [dab7a6edbc](https://linux-hardware.org/?probe=dab7a6edbc) | Mar 22, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [bc6e3fa274](https://linux-hardware.org/?probe=bc6e3fa274) | Mar 22, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [d458338d97](https://linux-hardware.org/?probe=d458338d97) | Mar 22, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [627590f38c](https://linux-hardware.org/?probe=627590f38c) | Mar 22, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | Notebook    | [a49ece0e6c](https://linux-hardware.org/?probe=a49ece0e6c) | Mar 22, 2023 |
| Lenovo        | ThinkPad Twist 33472HU      | Notebook    | [315f2256c6](https://linux-hardware.org/?probe=315f2256c6) | Mar 22, 2023 |
| Dell          | 0RK936                      | Desktop     | [af3e7f60cb](https://linux-hardware.org/?probe=af3e7f60cb) | Mar 22, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b616377b13](https://linux-hardware.org/?probe=b616377b13) | Mar 22, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [aff8d829e0](https://linux-hardware.org/?probe=aff8d829e0) | Mar 22, 2023 |
| Samsung       | 350V5C/350V5X/350V4C/350... | Notebook    | [99fe9f96c6](https://linux-hardware.org/?probe=99fe9f96c6) | Mar 22, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [af60ed4cde](https://linux-hardware.org/?probe=af60ed4cde) | Mar 22, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [3b3376e72c](https://linux-hardware.org/?probe=3b3376e72c) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [b4c65fead7](https://linux-hardware.org/?probe=b4c65fead7) | Mar 21, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [afc1ff125b](https://linux-hardware.org/?probe=afc1ff125b) | Mar 21, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | Notebook    | [3c100c55be](https://linux-hardware.org/?probe=3c100c55be) | Mar 21, 2023 |
| Lenovo        | ThinkPad T420 4180AP3       | Notebook    | [039724e2c2](https://linux-hardware.org/?probe=039724e2c2) | Mar 21, 2023 |
| Dell          | G15 5511                    | Notebook    | [6d71997e08](https://linux-hardware.org/?probe=6d71997e08) | Mar 21, 2023 |
| Dell          | XPS L421X                   | Notebook    | [fd54af9534](https://linux-hardware.org/?probe=fd54af9534) | Mar 21, 2023 |
| Dell          | 0RK936                      | Desktop     | [6c2680e4e9](https://linux-hardware.org/?probe=6c2680e4e9) | Mar 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [afe8ca841c](https://linux-hardware.org/?probe=afe8ca841c) | Mar 21, 2023 |
| Acer          | Aspire 5349                 | Notebook    | [c0f5810e5c](https://linux-hardware.org/?probe=c0f5810e5c) | Mar 21, 2023 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [cac8d6b991](https://linux-hardware.org/?probe=cac8d6b991) | Mar 21, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [d6ff521952](https://linux-hardware.org/?probe=d6ff521952) | Mar 21, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [16253cadcf](https://linux-hardware.org/?probe=16253cadcf) | Mar 21, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [d6393f5710](https://linux-hardware.org/?probe=d6393f5710) | Mar 21, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [404c84b0ea](https://linux-hardware.org/?probe=404c84b0ea) | Mar 21, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [d4e033725b](https://linux-hardware.org/?probe=d4e033725b) | Mar 21, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [edf722e245](https://linux-hardware.org/?probe=edf722e245) | Mar 21, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [5ea7504472](https://linux-hardware.org/?probe=5ea7504472) | Mar 21, 2023 |
| Gigabyte      | A320M-S2H-CF                | Notebook    | [2ff2eab844](https://linux-hardware.org/?probe=2ff2eab844) | Mar 21, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [d2b90b7d2f](https://linux-hardware.org/?probe=d2b90b7d2f) | Mar 21, 2023 |
| HP            | ZBook Power 15.6 inch G9... | Notebook    | [2ef051fd19](https://linux-hardware.org/?probe=2ef051fd19) | Mar 20, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [48de9eb9e3](https://linux-hardware.org/?probe=48de9eb9e3) | Mar 20, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [b133c68356](https://linux-hardware.org/?probe=b133c68356) | Mar 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [afcac034a9](https://linux-hardware.org/?probe=afcac034a9) | Mar 20, 2023 |
| HP            | Pavilion Laptop 15-cw1xx... | Notebook    | [d08f174747](https://linux-hardware.org/?probe=d08f174747) | Mar 20, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Notebook    | [c9b4e3cf00](https://linux-hardware.org/?probe=c9b4e3cf00) | Mar 20, 2023 |
| MSI           | MAG B550M BAZOOKA           | Desktop     | [3fe3c818f7](https://linux-hardware.org/?probe=3fe3c818f7) | Mar 20, 2023 |
| Dell          | Latitude 5590               | Notebook    | [49922a3223](https://linux-hardware.org/?probe=49922a3223) | Mar 19, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [55dc5e3ef4](https://linux-hardware.org/?probe=55dc5e3ef4) | Mar 19, 2023 |
| Intel         | NUC11PHBi7 M26151-404       | Mini pc     | [22290c7abf](https://linux-hardware.org/?probe=22290c7abf) | Mar 19, 2023 |
| Gigabyte      | Z97X-Gaming 7               | Desktop     | [6681949ccc](https://linux-hardware.org/?probe=6681949ccc) | Mar 19, 2023 |
| MSI           | PS42 8M                     | Notebook    | [aad18852f4](https://linux-hardware.org/?probe=aad18852f4) | Mar 19, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [d0079fa594](https://linux-hardware.org/?probe=d0079fa594) | Mar 19, 2023 |
| ASUSTek       | G74Sx                       | Notebook    | [f7f92408dc](https://linux-hardware.org/?probe=f7f92408dc) | Mar 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [6b6ceb1a1a](https://linux-hardware.org/?probe=6b6ceb1a1a) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [e3410282c5](https://linux-hardware.org/?probe=e3410282c5) | Mar 19, 2023 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c462ccc41a](https://linux-hardware.org/?probe=c462ccc41a) | Mar 19, 2023 |
| Gigabyte      | X79-UD3                     | Desktop     | [0139691951](https://linux-hardware.org/?probe=0139691951) | Mar 19, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [22e0286a24](https://linux-hardware.org/?probe=22e0286a24) | Mar 19, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [0018c1237d](https://linux-hardware.org/?probe=0018c1237d) | Mar 19, 2023 |
| Dell          | 0WMJ54 A00                  | Desktop     | [bcb1a34cf2](https://linux-hardware.org/?probe=bcb1a34cf2) | Mar 19, 2023 |
| ASUSTek       | S551LB                      | Notebook    | [7d4485326f](https://linux-hardware.org/?probe=7d4485326f) | Mar 18, 2023 |
| GPU Compan... | GWTN141-10                  | Notebook    | [ff8db61ccf](https://linux-hardware.org/?probe=ff8db61ccf) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [4eab8887fa](https://linux-hardware.org/?probe=4eab8887fa) | Mar 18, 2023 |
| ASUSTek       | X540LJ                      | Notebook    | [b3bf824f3a](https://linux-hardware.org/?probe=b3bf824f3a) | Mar 18, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Notebook    | [dd296a8801](https://linux-hardware.org/?probe=dd296a8801) | Mar 18, 2023 |
| Lenovo        | ThinkPad T480 20L6S11N00    | Notebook    | [60d80937ea](https://linux-hardware.org/?probe=60d80937ea) | Mar 18, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [dc411c9ce3](https://linux-hardware.org/?probe=dc411c9ce3) | Mar 18, 2023 |
| ASUSTek       | ZenBook UX325UA_UM325UA     | Notebook    | [91ae5652cc](https://linux-hardware.org/?probe=91ae5652cc) | Mar 18, 2023 |
| Lenovo        | IdeaPad L340-17IRH Gamin... | Notebook    | [274f959cfc](https://linux-hardware.org/?probe=274f959cfc) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [c4bebd7028](https://linux-hardware.org/?probe=c4bebd7028) | Mar 17, 2023 |
| Unknown       | Unknown                     | Desktop     | [2389fcea33](https://linux-hardware.org/?probe=2389fcea33) | Mar 17, 2023 |
| Dell          | Latitude E7240              | Notebook    | [cbcae7df75](https://linux-hardware.org/?probe=cbcae7df75) | Mar 17, 2023 |
| Intel         | X99 V1.x                    | Desktop     | [9b471dcdcf](https://linux-hardware.org/?probe=9b471dcdcf) | Mar 17, 2023 |
| Positivo      | N1250                       | Notebook    | [e5ee22876a](https://linux-hardware.org/?probe=e5ee22876a) | Mar 17, 2023 |
| Gigabyte      | X399 DESIGNARE EX-CF        | Desktop     | [557a99333f](https://linux-hardware.org/?probe=557a99333f) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [27356d58d5](https://linux-hardware.org/?probe=27356d58d5) | Mar 17, 2023 |
| HP            | 843F                        | Desktop     | [e444e0d76a](https://linux-hardware.org/?probe=e444e0d76a) | Mar 17, 2023 |
| HP            | ProBook 4530s               | Notebook    | [f0abd32fe4](https://linux-hardware.org/?probe=f0abd32fe4) | Mar 17, 2023 |
| Lenovo        | G40-80 80JE                 | Notebook    | [a7a6cc1ab5](https://linux-hardware.org/?probe=a7a6cc1ab5) | Mar 17, 2023 |
| Lenovo        | G40-80 80JE                 | Notebook    | [204994be7f](https://linux-hardware.org/?probe=204994be7f) | Mar 17, 2023 |
| TUXEDO        | Pulse 14 Gen1               | Notebook    | [525b267c31](https://linux-hardware.org/?probe=525b267c31) | Mar 17, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [b20fcd6878](https://linux-hardware.org/?probe=b20fcd6878) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | Notebook    | [a1adc8641d](https://linux-hardware.org/?probe=a1adc8641d) | Mar 17, 2023 |
| Toshiba       | Satellite Pro C50-A-1E2     | Notebook    | [a0eea87e02](https://linux-hardware.org/?probe=a0eea87e02) | Mar 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [3eb0bf05b4](https://linux-hardware.org/?probe=3eb0bf05b4) | Mar 17, 2023 |
| Lenovo        | ThinkPad T460s 20FAS0RP0... | Notebook    | [f901058202](https://linux-hardware.org/?probe=f901058202) | Mar 16, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [d6f5cd9505](https://linux-hardware.org/?probe=d6f5cd9505) | Mar 16, 2023 |
| Dell          | 02GDWG A00                  | Desktop     | [c81ac4434e](https://linux-hardware.org/?probe=c81ac4434e) | Mar 16, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | Notebook    | [5f48c46d68](https://linux-hardware.org/?probe=5f48c46d68) | Mar 16, 2023 |
| Microsoft     | Surface Book                | Tablet      | [d5cd9be69a](https://linux-hardware.org/?probe=d5cd9be69a) | Mar 16, 2023 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [67d6333f85](https://linux-hardware.org/?probe=67d6333f85) | Mar 15, 2023 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [59a304e790](https://linux-hardware.org/?probe=59a304e790) | Mar 15, 2023 |
| Acer          | Aspire A715-42G             | Notebook    | [8bdae79f7a](https://linux-hardware.org/?probe=8bdae79f7a) | Mar 15, 2023 |
| Lenovo        | ThinkPad T440p 20AWS19P0... | Notebook    | [6a2d338526](https://linux-hardware.org/?probe=6a2d338526) | Mar 15, 2023 |
| ASUSTek       | Z87-K                       | Desktop     | [fe2d844bfb](https://linux-hardware.org/?probe=fe2d844bfb) | Mar 15, 2023 |
| Razer         | Blade Stealth 13 (Early ... | Notebook    | [eb1d71edb4](https://linux-hardware.org/?probe=eb1d71edb4) | Mar 15, 2023 |
| HCL Infosy... | HCL ME LAPTOP               | Notebook    | [af254fca4d](https://linux-hardware.org/?probe=af254fca4d) | Mar 15, 2023 |
| SAGER         | X8100                       | Notebook    | [90aaefeb9e](https://linux-hardware.org/?probe=90aaefeb9e) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [88c4c221af](https://linux-hardware.org/?probe=88c4c221af) | Mar 15, 2023 |
| Huanan        | X99-AD3 GAMING V2.0         | Desktop     | [0586633e29](https://linux-hardware.org/?probe=0586633e29) | Mar 15, 2023 |
| ASUSTek       | PRIME Z790-P WIFI D4        | Desktop     | [e8bbe7a962](https://linux-hardware.org/?probe=e8bbe7a962) | Mar 15, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [0c74f7b048](https://linux-hardware.org/?probe=0c74f7b048) | Mar 15, 2023 |
| System76      | Pangolin                    | Notebook    | [4f39796131](https://linux-hardware.org/?probe=4f39796131) | Mar 15, 2023 |
| Dell          | Latitude E7240              | Notebook    | [d4ed345a47](https://linux-hardware.org/?probe=d4ed345a47) | Mar 14, 2023 |
| ASRock        | B550 Extreme4               | Desktop     | [9a139b5bad](https://linux-hardware.org/?probe=9a139b5bad) | Mar 14, 2023 |
| Lenovo        | ThinkPad T450s 20BWS14G0... | Notebook    | [1161c07721](https://linux-hardware.org/?probe=1161c07721) | Mar 14, 2023 |
| Sony          | VPCZ12V9R                   | Notebook    | [28be5f7f2b](https://linux-hardware.org/?probe=28be5f7f2b) | Mar 14, 2023 |
| Dell          | Latitude E7240              | Notebook    | [4a7d442938](https://linux-hardware.org/?probe=4a7d442938) | Mar 14, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [44d9ce8acb](https://linux-hardware.org/?probe=44d9ce8acb) | Mar 14, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [986fe8c418](https://linux-hardware.org/?probe=986fe8c418) | Mar 14, 2023 |
| Gigabyte      | X58A-UD7                    | Desktop     | [95248fc9a0](https://linux-hardware.org/?probe=95248fc9a0) | Mar 14, 2023 |
| Dell          | 0RK936                      | Desktop     | [59cbc1f071](https://linux-hardware.org/?probe=59cbc1f071) | Mar 14, 2023 |
| Fujitsu       | LIFEBOOK E5512A             | Notebook    | [ae9f2da5a4](https://linux-hardware.org/?probe=ae9f2da5a4) | Mar 14, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [874706952d](https://linux-hardware.org/?probe=874706952d) | Mar 14, 2023 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [de22b8a7e6](https://linux-hardware.org/?probe=de22b8a7e6) | Mar 14, 2023 |
| Dell          | Inspiron 7348               | Notebook    | [7459d24035](https://linux-hardware.org/?probe=7459d24035) | Mar 13, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f5215489c7](https://linux-hardware.org/?probe=f5215489c7) | Mar 13, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [b03c056ee1](https://linux-hardware.org/?probe=b03c056ee1) | Mar 13, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [b93a4bdcbb](https://linux-hardware.org/?probe=b93a4bdcbb) | Mar 13, 2023 |
| Acer          | Aspire 4530                 | Notebook    | [84f4733a96](https://linux-hardware.org/?probe=84f4733a96) | Mar 13, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [7f2ecd927d](https://linux-hardware.org/?probe=7f2ecd927d) | Mar 13, 2023 |
| Gateway       | WG43M                       | Desktop     | [c1ab165971](https://linux-hardware.org/?probe=c1ab165971) | Mar 13, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [663f73a08e](https://linux-hardware.org/?probe=663f73a08e) | Mar 13, 2023 |
| Apple         | MacBookPro15,1              | Notebook    | [5d1a30091e](https://linux-hardware.org/?probe=5d1a30091e) | Mar 13, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [a826b1cd32](https://linux-hardware.org/?probe=a826b1cd32) | Mar 13, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [0e2618e3ea](https://linux-hardware.org/?probe=0e2618e3ea) | Mar 12, 2023 |
| Dell          | 0DFRFW A01                  | Desktop     | [1b8b00dbc5](https://linux-hardware.org/?probe=1b8b00dbc5) | Mar 12, 2023 |
| Lenovo        | ThinkPad T480s 20L8S7AS0... | Notebook    | [87ef2f6efb](https://linux-hardware.org/?probe=87ef2f6efb) | Mar 12, 2023 |
| HP            | ProLiant DL380 G7           | Server      | [9911027e53](https://linux-hardware.org/?probe=9911027e53) | Mar 12, 2023 |
| HUAWEI        | NBM-WXX9                    | Notebook    | [27b710cd68](https://linux-hardware.org/?probe=27b710cd68) | Mar 12, 2023 |
| Google        | Kefka                       | Notebook    | [4a54e34e44](https://linux-hardware.org/?probe=4a54e34e44) | Mar 12, 2023 |
| ASUSTek       | ZenBook UX434IQ_Q407IQ      | Notebook    | [7090114437](https://linux-hardware.org/?probe=7090114437) | Mar 12, 2023 |
| Dell          | Inspiron 5452               | Notebook    | [2c8ca0e296](https://linux-hardware.org/?probe=2c8ca0e296) | Mar 12, 2023 |
| Gigabyte      | Z590I AORUS ULTRA           | Desktop     | [47ea9647d3](https://linux-hardware.org/?probe=47ea9647d3) | Mar 12, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [75fc2c0a15](https://linux-hardware.org/?probe=75fc2c0a15) | Mar 12, 2023 |
| Positivo B... | VJFE41F11X-XXXXXX           | Notebook    | [99f410d801](https://linux-hardware.org/?probe=99f410d801) | Mar 11, 2023 |
| ASUSTek       | VivoBook S14 X411UF         | Notebook    | [e101a1c94c](https://linux-hardware.org/?probe=e101a1c94c) | Mar 11, 2023 |
| Acer          | Aspire X1935                | Desktop     | [6846ecd490](https://linux-hardware.org/?probe=6846ecd490) | Mar 11, 2023 |
| HONOR         | NMH-WCX9                    | Notebook    | [d8cf10f11d](https://linux-hardware.org/?probe=d8cf10f11d) | Mar 11, 2023 |
| HP            | ZBook 17                    | Notebook    | [a775bc33c5](https://linux-hardware.org/?probe=a775bc33c5) | Mar 11, 2023 |
| Maibenben     | P748                        | Notebook    | [a44d1bb8e4](https://linux-hardware.org/?probe=a44d1bb8e4) | Mar 11, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [39cc207ce7](https://linux-hardware.org/?probe=39cc207ce7) | Mar 11, 2023 |
| Lenovo        | ThinkPad L440 20ASS0ET00    | Notebook    | [2ac6dfff4f](https://linux-hardware.org/?probe=2ac6dfff4f) | Mar 11, 2023 |
| GPD           | G1619-04                    | Notebook    | [302ff30130](https://linux-hardware.org/?probe=302ff30130) | Mar 11, 2023 |
| GPD           | G1619-04                    | Notebook    | [d8f5b9eec9](https://linux-hardware.org/?probe=d8f5b9eec9) | Mar 11, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [8736fd04a8](https://linux-hardware.org/?probe=8736fd04a8) | Mar 11, 2023 |
| Dell          | 0KC9NP A00                  | Desktop     | [873a2bf50c](https://linux-hardware.org/?probe=873a2bf50c) | Mar 11, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [9535f3676b](https://linux-hardware.org/?probe=9535f3676b) | Mar 10, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [fca941c098](https://linux-hardware.org/?probe=fca941c098) | Mar 10, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | Notebook    | [96f4bd0a52](https://linux-hardware.org/?probe=96f4bd0a52) | Mar 10, 2023 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [ccba86bda3](https://linux-hardware.org/?probe=ccba86bda3) | Mar 10, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Pop!_OS_22.04/All/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 6.2.6-76060206-generic   | 573       | 17.9%   |
| 6.0.12-76060006-generic  | 472       | 14.75%  |
| 5.19.0-76051900-generic  | 445       | 13.9%   |
| 5.17.5-76051705-generic  | 416       | 13%     |
| 6.0.6-76060006-generic   | 300       | 9.37%   |
| 5.18.10-76051810-generic | 207       | 6.47%   |
| 5.17.15-76051715-generic | 185       | 5.78%   |
| 6.2.0-76060200-generic   | 120       | 3.75%   |
| 5.16.19-76051619-generic | 120       | 3.75%   |
| 6.0.2-76060002-generic   | 91        | 2.84%   |
| 6.1.11-76060111-generic  | 90        | 2.81%   |
| 5.19.16-76051916-generic | 43        | 1.34%   |
| 6.0.3-76060003-generic   | 39        | 1.22%   |
| 6.3.4-060304-generic     | 3         | 0.09%   |
| 6.1.0-1006-oem           | 3         | 0.09%   |
| 5.16.15-76051615-generic | 3         | 0.09%   |
| 6.3.7-060307-generic     | 2         | 0.06%   |
| 6.2.11-060211-generic    | 2         | 0.06%   |
| 6.1.8-060108-generic     | 2         | 0.06%   |
| 6.1.0-x64v1-xanmod1      | 2         | 0.06%   |
| 6.0.9-060009-generic     | 2         | 0.06%   |
| 6.0.2-x64v1-xanmod1      | 2         | 0.06%   |
| 5.19.12-xanmod1          | 2         | 0.06%   |
| 5.17.7-051707-generic    | 2         | 0.06%   |
| 5.17.5-051705-generic    | 2         | 0.06%   |
| 6.3.9-x64v3-xanmod1      | 1         | 0.03%   |
| 6.3.8-1-liquorix-amd64   | 1         | 0.03%   |
| 6.3.5-x64v1-xanmod1      | 1         | 0.03%   |
| 6.3.4-x64v1-xanmod1      | 1         | 0.03%   |
| 6.3.2-060302-generic     | 1         | 0.03%   |
| 6.3.1-x64v1-xanmod1      | 1         | 0.03%   |
| 6.3.1-060301-generic     | 1         | 0.03%   |
| 6.3.0-060300-generic     | 1         | 0.03%   |
| 6.2.9-1-liquorix-amd64   | 1         | 0.03%   |
| 6.2.9-060209-generic     | 1         | 0.03%   |
| 6.2.8-060208-generic     | 1         | 0.03%   |
| 6.2.6-060206-generic     | 1         | 0.03%   |
| 6.2.2-x64v3-xanmod1      | 1         | 0.03%   |
| 6.2.2-surface            | 1         | 0.03%   |
| 6.2.16-060216-generic    | 1         | 0.03%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.2.6   | 574       | 17.94%  |
| 6.0.12  | 473       | 14.78%  |
| 5.19.0  | 449       | 14.03%  |
| 5.17.5  | 419       | 13.09%  |
| 6.0.6   | 301       | 9.41%   |
| 5.18.10 | 207       | 6.47%   |
| 5.17.15 | 185       | 5.78%   |
| 6.2.0   | 120       | 3.75%   |
| 5.16.19 | 120       | 3.75%   |
| 6.0.2   | 94        | 2.94%   |
| 6.1.11  | 91        | 2.84%   |
| 5.19.16 | 43        | 1.34%   |
| 6.0.3   | 39        | 1.22%   |
| 6.1.0   | 6         | 0.19%   |
| 5.15.0  | 6         | 0.19%   |
| 6.3.4   | 4         | 0.13%   |
| 6.1.8   | 3         | 0.09%   |
| 6.0.9   | 3         | 0.09%   |
| 5.16.15 | 3         | 0.09%   |
| 6.3.7   | 2         | 0.06%   |
| 6.3.1   | 2         | 0.06%   |
| 6.2.9   | 2         | 0.06%   |
| 6.2.2   | 2         | 0.06%   |
| 6.2.11  | 2         | 0.06%   |
| 6.1.9   | 2         | 0.06%   |
| 6.1.12  | 2         | 0.06%   |
| 6.0.0   | 2         | 0.06%   |
| 5.19.12 | 2         | 0.06%   |
| 5.18.0  | 2         | 0.06%   |
| 5.17.7  | 2         | 0.06%   |
| 5.17.0  | 2         | 0.06%   |
| 6.3.9   | 1         | 0.03%   |
| 6.3.8   | 1         | 0.03%   |
| 6.3.5   | 1         | 0.03%   |
| 6.3.2   | 1         | 0.03%   |
| 6.3.0   | 1         | 0.03%   |
| 6.2.8   | 1         | 0.03%   |
| 6.2.16  | 1         | 0.03%   |
| 6.2.14  | 1         | 0.03%   |
| 6.2.10  | 1         | 0.03%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0     | 886       | 28.16%  |
| 6.2     | 698       | 22.19%  |
| 5.17    | 600       | 19.07%  |
| 5.19    | 494       | 15.7%   |
| 5.18    | 213       | 6.77%   |
| 5.16    | 124       | 3.94%   |
| 6.1     | 108       | 3.43%   |
| 6.3     | 13        | 0.41%   |
| 5.15    | 9         | 0.29%   |
| 5.4     | 1         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2899      | 99.86%  |
| aarch64 | 4         | 0.14%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 2832      | 97.25%  |
| KDE5            | 39        | 1.34%   |
| Unknown         | 15        | 0.52%   |
| X-Cinnamon      | 9         | 0.31%   |
| GNOME Flashback | 4         | 0.14%   |
| Unity           | 3         | 0.1%    |
| LXQt            | 3         | 0.1%    |
| XFCE            | 2         | 0.07%   |
| MATE            | 2         | 0.07%   |
| Cinnamon        | 2         | 0.07%   |
| i3              | 1         | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 2785      | 95.34%  |
| Wayland | 122       | 4.18%   |
| Unknown | 11        | 0.38%   |
| Tty     | 3         | 0.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2189      | 74.91%  |
| GDM3    | 715       | 24.47%  |
| SDDM    | 9         | 0.31%   |
| GDM     | 7         | 0.24%   |
| LightDM | 2         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 1765      | 60.34%  |
| en_GB   | 191       | 6.53%   |
| pt_BR   | 156       | 5.33%   |
| de_DE   | 125       | 4.27%   |
| C       | 92        | 3.15%   |
| en_AU   | 65        | 2.22%   |
| it_IT   | 60        | 2.05%   |
| en_CA   | 55        | 1.88%   |
| fr_FR   | 48        | 1.64%   |
| es_ES   | 35        | 1.2%    |
| ru_RU   | 33        | 1.13%   |
| pl_PL   | 28        | 0.96%   |
| nb_NO   | 19        | 0.65%   |
| sv_SE   | 17        | 0.58%   |
| Unknown | 16        | 0.55%   |
| fi_FI   | 15        | 0.51%   |
| nl_NL   | 14        | 0.48%   |
| pt_PT   | 13        | 0.44%   |
| es_CL   | 12        | 0.41%   |
| en_IN   | 12        | 0.41%   |
| en_IE   | 12        | 0.41%   |
| en_NZ   | 10        | 0.34%   |
| es_MX   | 9         | 0.31%   |
| es_AR   | 9         | 0.31%   |
| de_CH   | 9         | 0.31%   |
| de_AT   | 9         | 0.31%   |
| fr_CA   | 8         | 0.27%   |
| da_DK   | 8         | 0.27%   |
| tr_TR   | 7         | 0.24%   |
| ja_JP   | 7         | 0.24%   |
| en_ZA   | 7         | 0.24%   |
| en_DK   | 7         | 0.24%   |
| cs_CZ   | 6         | 0.21%   |
| fr_CH   | 4         | 0.14%   |
| fr_BE   | 4         | 0.14%   |
| es_CO   | 4         | 0.14%   |
| ro_RO   | 3         | 0.1%    |
| zh_TW   | 2         | 0.07%   |
| nl_BE   | 2         | 0.07%   |
| hu_HU   | 2         | 0.07%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 2232      | 76.41%  |
| EFI  | 689       | 23.59%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 2749      | 94.4%   |
| Btrfs   | 91        | 3.13%   |
| Overlay | 59        | 2.03%   |
| Xfs     | 9         | 0.31%   |
| Zfs     | 3         | 0.1%    |
| Unknown | 1         | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 2174      | 74.4%   |
| GPT     | 702       | 24.02%  |
| MBR     | 46        | 1.57%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2819      | 96.77%  |
| Yes       | 94        | 3.23%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2621      | 90.01%  |
| Yes       | 291       | 9.99%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 522       | 17.98%  |
| Lenovo                  | 426       | 14.67%  |
| Dell                    | 365       | 12.57%  |
| Hewlett-Packard         | 320       | 11.02%  |
| MSI                     | 216       | 7.44%   |
| Gigabyte Technology     | 191       | 6.58%   |
| Apple                   | 142       | 4.89%   |
| Acer                    | 133       | 4.58%   |
| ASRock                  | 93        | 3.2%    |
| System76                | 65        | 2.24%   |
| Intel                   | 37        | 1.27%   |
| Toshiba                 | 33        | 1.14%   |
| Samsung Electronics     | 33        | 1.14%   |
| HUAWEI                  | 26        | 0.9%    |
| Alienware               | 20        | 0.69%   |
| Microsoft               | 17        | 0.59%   |
| Fujitsu                 | 16        | 0.55%   |
| Google                  | 14        | 0.48%   |
| Unknown                 | 13        | 0.45%   |
| AZW                     | 11        | 0.38%   |
| Sony                    | 10        | 0.34%   |
| BESSTAR Tech            | 10        | 0.34%   |
| Razer                   | 9         | 0.31%   |
| Positivo                | 9         | 0.31%   |
| Notebook                | 9         | 0.31%   |
| GPU Company             | 9         | 0.31%   |
| Timi                    | 7         | 0.24%   |
| HONOR                   | 6         | 0.21%   |
| Framework               | 6         | 0.21%   |
| Avell High Performance  | 6         | 0.21%   |
| Supermicro              | 5         | 0.17%   |
| Pegatron                | 5         | 0.17%   |
| MACHINIST               | 5         | 0.17%   |
| Foxconn                 | 5         | 0.17%   |
| TUXEDO                  | 4         | 0.14%   |
| Raspberry Pi Foundation | 4         | 0.14%   |
| Medion                  | 4         | 0.14%   |
| Biostar                 | 4         | 0.14%   |
| ZOTAC                   | 3         | 0.1%    |
| PC Specialist           | 3         | 0.1%    |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 20        | 0.69%   |
| ASUS All Series                  | 18        | 0.62%   |
| System76 Oryx Pro                | 16        | 0.55%   |
| System76 Lemur Pro               | 13        | 0.45%   |
| ASUS ROG STRIX B550-F GAMING     | 12        | 0.41%   |
| Apple MacBookPro12,1             | 11        | 0.38%   |
| Apple MacBookAir7,2              | 11        | 0.38%   |
| System76 Gazelle                 | 10        | 0.34%   |
| ASUS ROG STRIX B550-I GAMING     | 10        | 0.34%   |
| ASUS ROG STRIX B450-F GAMING     | 10        | 0.34%   |
| Gigabyte X570 AORUS ELITE        | 9         | 0.31%   |
| HP Dev One Notebook PC           | 8         | 0.28%   |
| ASUS TUF Gaming X570-PLUS        | 8         | 0.28%   |
| ASUS TUF Gaming B550-PLUS        | 8         | 0.28%   |
| Apple MacBookPro9,2              | 8         | 0.28%   |
| MSI MS-7B86                      | 7         | 0.24%   |
| Gigabyte B450 AORUS M            | 7         | 0.24%   |
| Apple MacBookAir6,2              | 7         | 0.24%   |
| System76 Thelio                  | 6         | 0.21%   |
| System76 Galago Pro              | 6         | 0.21%   |
| MSI MS-7C91                      | 6         | 0.21%   |
| MSI MS-7A38                      | 6         | 0.21%   |
| Lenovo IdeaPad S145-15API 81V7   | 6         | 0.21%   |
| HP Notebook                      | 6         | 0.21%   |
| Gigabyte B550M DS3H              | 6         | 0.21%   |
| Dell XPS 15 9520                 | 6         | 0.21%   |
| ASUS TUF Gaming B550M-PLUS       | 6         | 0.21%   |
| ASUS PRIME B550M-A               | 6         | 0.21%   |
| Apple MacBookPro11,3             | 6         | 0.21%   |
| Acer Aspire A515-45              | 6         | 0.21%   |
| MSI MS-7D54                      | 5         | 0.17%   |
| MSI MS-7D32                      | 5         | 0.17%   |
| MSI MS-7C37                      | 5         | 0.17%   |
| MSI MS-7C02                      | 5         | 0.17%   |
| MSI MS-7A34                      | 5         | 0.17%   |
| MSI MS-7693                      | 5         | 0.17%   |
| Lenovo Legion 5 15ACH6H 82JU     | 5         | 0.17%   |
| Lenovo IdeaPad 5 Pro 16ARH7 82SN | 5         | 0.17%   |
| Lenovo IdeaPad 3 15ALC6 82MF     | 5         | 0.17%   |
| HP Pavilion 15                   | 5         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 170       | 5.86%   |
| ASUS ROG           | 139       | 4.79%   |
| Dell Inspiron      | 95        | 3.27%   |
| Lenovo IdeaPad     | 93        | 3.2%    |
| Acer Aspire        | 82        | 2.82%   |
| Dell Latitude      | 70        | 2.41%   |
| Dell XPS           | 66        | 2.27%   |
| HP Pavilion        | 55        | 1.89%   |
| ASUS PRIME         | 54        | 1.86%   |
| ASUS TUF           | 51        | 1.76%   |
| Dell Precision     | 47        | 1.62%   |
| ASUS VivoBook      | 42        | 1.45%   |
| HP EliteBook       | 40        | 1.38%   |
| Lenovo Legion      | 39        | 1.34%   |
| HP Laptop          | 37        | 1.27%   |
| Dell OptiPlex      | 34        | 1.17%   |
| HP ENVY            | 29        | 1%      |
| Toshiba Satellite  | 28        | 0.96%   |
| Lenovo Yoga        | 27        | 0.93%   |
| HP ProBook         | 25        | 0.86%   |
| ASUS ASUS          | 24        | 0.83%   |
| Lenovo ThinkCentre | 23        | 0.79%   |
| ASUS ZenBook       | 23        | 0.79%   |
| Gigabyte X570      | 21        | 0.72%   |
| Acer Swift         | 20        | 0.69%   |
| Unknown            | 20        | 0.69%   |
| HP ZBook           | 18        | 0.62%   |
| HP Compaq          | 18        | 0.62%   |
| Dell Vostro        | 18        | 0.62%   |
| ASUS All           | 18        | 0.62%   |
| Microsoft Surface  | 17        | 0.59%   |
| Gigabyte B450      | 17        | 0.59%   |
| System76 Oryx      | 16        | 0.55%   |
| Acer Nitro         | 16        | 0.55%   |
| HP OMEN            | 15        | 0.52%   |
| Apple MacBookPro11 | 15        | 0.52%   |
| System76 Lemur     | 13        | 0.45%   |
| Lenovo ThinkBook   | 13        | 0.45%   |
| HP EliteDesk       | 12        | 0.41%   |
| HP Spectre         | 11        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 405       | 13.95%  |
| 2020    | 381       | 13.12%  |
| 2022    | 313       | 10.78%  |
| 2018    | 284       | 9.78%   |
| 2019    | 283       | 9.75%   |
| 2013    | 167       | 5.75%   |
| 2012    | 156       | 5.37%   |
| 2017    | 152       | 5.24%   |
| 2015    | 145       | 4.99%   |
| 2016    | 132       | 4.55%   |
| 2014    | 129       | 4.44%   |
| 2011    | 127       | 4.37%   |
| 2010    | 84        | 2.89%   |
| 2009    | 69        | 2.38%   |
| 2008    | 33        | 1.14%   |
| 2023    | 21        | 0.72%   |
| 2007    | 13        | 0.45%   |
| Unknown | 6         | 0.21%   |
| 2006    | 2         | 0.07%   |
| 2005    | 1         | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1660      | 57.18%  |
| Desktop        | 1013      | 34.89%  |
| Convertible    | 105       | 3.62%   |
| Mini pc        | 51        | 1.76%   |
| All in one     | 33        | 1.14%   |
| Tablet         | 27        | 0.93%   |
| Server         | 9         | 0.31%   |
| System on chip | 5         | 0.17%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2902      | 99.93%  |
| Enabled  | 2         | 0.07%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2845      | 98%     |
| Yes  | 58        | 2%      |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 790       | 26.97%  |
| 4.01-8.0        | 638       | 21.78%  |
| 8.01-16.0       | 529       | 18.06%  |
| 32.01-64.0      | 483       | 16.49%  |
| 3.01-4.0        | 253       | 8.64%   |
| 64.01-256.0     | 148       | 5.05%   |
| 24.01-32.0      | 68        | 2.32%   |
| 1.01-2.0        | 9         | 0.31%   |
| 2.01-3.0        | 8         | 0.27%   |
| More than 256.0 | 3         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 984       | 31.3%   |
| 2.01-3.0    | 848       | 26.97%  |
| 3.01-4.0    | 701       | 22.3%   |
| 1.01-2.0    | 280       | 8.91%   |
| 8.01-16.0   | 272       | 8.65%   |
| 16.01-24.0  | 37        | 1.18%   |
| 24.01-32.0  | 11        | 0.35%   |
| 32.01-64.0  | 7         | 0.22%   |
| 64.01-256.0 | 2         | 0.06%   |
| 0.51-1.0    | 2         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1695      | 57.57%  |
| 2      | 761       | 25.85%  |
| 3      | 259       | 8.8%    |
| 4      | 109       | 3.7%    |
| 5      | 60        | 2.04%   |
| 6      | 26        | 0.88%   |
| 7      | 12        | 0.41%   |
| 0      | 11        | 0.37%   |
| 9      | 3         | 0.1%    |
| 8      | 3         | 0.1%    |
| 10     | 2         | 0.07%   |
| 26     | 1         | 0.03%   |
| 19     | 1         | 0.03%   |
| 11     | 1         | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 2241      | 77.04%  |
| Yes       | 668       | 22.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2372      | 81.32%  |
| No        | 545       | 18.68%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2429      | 83.47%  |
| No        | 481       | 16.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2089      | 71.57%  |
| No        | 830       | 28.43%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 936       | 32.08%  |
| Brazil       | 216       | 7.4%    |
| Germany      | 192       | 6.58%   |
| UK           | 136       | 4.66%   |
| Canada       | 129       | 4.42%   |
| Italy        | 109       | 3.74%   |
| Australia    | 90        | 3.08%   |
| India        | 78        | 2.67%   |
| France       | 74        | 2.54%   |
| Russia       | 53        | 1.82%   |
| Netherlands  | 53        | 1.82%   |
| Poland       | 46        | 1.58%   |
| Spain        | 42        | 1.44%   |
| Norway       | 42        | 1.44%   |
| Sweden       | 41        | 1.41%   |
| Mexico       | 37        | 1.27%   |
| Finland      | 34        | 1.17%   |
| Portugal     | 30        | 1.03%   |
| Switzerland  | 27        | 0.93%   |
| Greece       | 26        | 0.89%   |
| Austria      | 26        | 0.89%   |
| Chile        | 22        | 0.75%   |
| Turkey       | 21        | 0.72%   |
| Argentina    | 21        | 0.72%   |
| Romania      | 20        | 0.69%   |
| Philippines  | 20        | 0.69%   |
| New Zealand  | 20        | 0.69%   |
| Indonesia    | 20        | 0.69%   |
| Denmark      | 20        | 0.69%   |
| Belgium      | 20        | 0.69%   |
| Japan        | 18        | 0.62%   |
| Hungary      | 17        | 0.58%   |
| Czechia      | 17        | 0.58%   |
| South Africa | 16        | 0.55%   |
| Ireland      | 16        | 0.55%   |
| Thailand     | 14        | 0.48%   |
| Serbia       | 12        | 0.41%   |
| Malaysia     | 11        | 0.38%   |
| Bulgaria     | 11        | 0.38%   |
| Hong Kong    | 10        | 0.34%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Milan          | 22        | 0.73%   |
| Melbourne      | 22        | 0.73%   |
| Helsinki       | 21        | 0.69%   |
| Brisbane       | 21        | 0.69%   |
| Berlin         | 20        | 0.66%   |
| Sydney         | 18        | 0.6%    |
| Seattle        | 18        | 0.6%    |
| Sao Paulo      | 18        | 0.6%    |
| Oslo           | 18        | 0.6%    |
| Vienna         | 17        | 0.56%   |
| Rio de Janeiro | 17        | 0.56%   |
| Istanbul       | 15        | 0.5%    |
| Moscow         | 14        | 0.46%   |
| Chicago        | 14        | 0.46%   |
| Zurich         | 12        | 0.4%    |
| Rome           | 12        | 0.4%    |
| New York       | 12        | 0.4%    |
| Toronto        | 11        | 0.36%   |
| Munich         | 11        | 0.36%   |
| Madrid         | 11        | 0.36%   |
| London         | 11        | 0.36%   |
| Edmonton       | 11        | 0.36%   |
| Dallas         | 11        | 0.36%   |
| Bengaluru      | 11        | 0.36%   |
| San Antonio    | 10        | 0.33%   |
| Lisbon         | 10        | 0.33%   |
| Hamburg        | 10        | 0.33%   |
| Belgrade       | 10        | 0.33%   |
| Portland       | 9         | 0.3%    |
| Paris          | 9         | 0.3%    |
| Dublin         | 9         | 0.3%    |
| Denver         | 9         | 0.3%    |
| Cleveland      | 9         | 0.3%    |
| Auckland       | 9         | 0.3%    |
| Amsterdam      | 9         | 0.3%    |
| Warsaw         | 8         | 0.26%   |
| St Petersburg  | 8         | 0.26%   |
| Santiago       | 8         | 0.26%   |
| San Jose       | 8         | 0.26%   |
| Minneapolis    | 8         | 0.26%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 862       | 1225   | 19.38%  |
| WDC                         | 495       | 663    | 11.13%  |
| Seagate                     | 475       | 657    | 10.68%  |
| SanDisk                     | 335       | 427    | 7.53%   |
| Kingston                    | 223       | 260    | 5.01%   |
| Toshiba                     | 202       | 237    | 4.54%   |
| Crucial                     | 196       | 265    | 4.41%   |
| SK hynix                    | 160       | 191    | 3.6%    |
| Intel                       | 123       | 155    | 2.76%   |
| Unknown                     | 120       | 157    | 2.7%    |
| Micron Technology           | 100       | 120    | 2.25%   |
| Apple                       | 79        | 89     | 1.78%   |
| Hitachi                     | 70        | 108    | 1.57%   |
| HGST                        | 65        | 74     | 1.46%   |
| A-DATA Technology           | 63        | 70     | 1.42%   |
| Phison Electronics          | 60        | 81     | 1.35%   |
| Micron/Crucial Technology   | 58        | 75     | 1.3%    |
| Phison                      | 51        | 62     | 1.15%   |
| PNY                         | 46        | 59     | 1.03%   |
| KIOXIA                      | 42        | 47     | 0.94%   |
| China                       | 42        | 55     | 0.94%   |
| Silicon Motion              | 39        | 50     | 0.88%   |
| Kingston Technology Company | 30        | 34     | 0.67%   |
| SPCC                        | 25        | 34     | 0.56%   |
| Netac                       | 21        | 21     | 0.47%   |
| Intenso                     | 19        | 27     | 0.43%   |
| Unknown                     | 19        | 23     | 0.43%   |
| Realtek Semiconductor       | 16        | 16     | 0.36%   |
| ADATA Technology            | 16        | 16     | 0.36%   |
| Team                        | 15        | 20     | 0.34%   |
| Patriot                     | 15        | 18     | 0.34%   |
| LITEON                      | 15        | 18     | 0.34%   |
| OCZ                         | 13        | 18     | 0.29%   |
| LITEONIT                    | 13        | 21     | 0.29%   |
| KingSpec                    | 13        | 14     | 0.29%   |
| XPG                         | 11        | 13     | 0.25%   |
| Lexar                       | 11        | 14     | 0.25%   |
| JMicron Technology          | 11        | 20     | 0.25%   |
| Transcend                   | 10        | 13     | 0.22%   |
| Union Memory (Shenzhen)     | 9         | 11     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 105       | 2.14%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 58        | 1.18%   |
| Kingston SA400S37240G 240GB SSD                     | 58        | 1.18%   |
| SanDisk NVMe SSD Drive 1TB                          | 39        | 0.79%   |
| Samsung NVMe SSD Drive 1TB                          | 36        | 0.73%   |
| Samsung SSD 860 EVO 1TB                             | 34        | 0.69%   |
| Samsung SSD 850 EVO 250GB                           | 34        | 0.69%   |
| Seagate ST1000LM035-1RK172 1TB                      | 33        | 0.67%   |
| Samsung SSD 850 EVO 500GB                           | 32        | 0.65%   |
| Seagate ST2000DM008-2FR102 2TB                      | 31        | 0.63%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 30        | 0.61%   |
| Samsung SSD 860 EVO 500GB                           | 29        | 0.59%   |
| Samsung NVMe SSD Drive 500GB                        | 29        | 0.59%   |
| Kingston SA400S37480G 480GB SSD                     | 29        | 0.59%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                  | 28        | 0.57%   |
| Seagate ST1000DM010-2EP102 1TB                      | 27        | 0.55%   |
| Micron/Crucial P2 NVMe PCIe SSD 4TB                 | 27        | 0.55%   |
| Crucial CT1000MX500SSD1 1TB                         | 27        | 0.55%   |
| Crucial CT240BX500SSD1 240GB                        | 26        | 0.53%   |
| Kingston SA400S37120G 120GB SSD                     | 25        | 0.51%   |
| Phison E12 NVMe Controller 1TB                      | 23        | 0.47%   |
| Samsung NVMe SSD Drive 512GB                        | 22        | 0.45%   |
| Crucial CT500MX500SSD1 500GB                        | 22        | 0.45%   |
| Samsung SSD 980 1TB                                 | 21        | 0.43%   |
| Unknown MMC Card  64GB                              | 20        | 0.41%   |
| Samsung NVMe SSD Drive 2TB                          | 20        | 0.41%   |
| Toshiba MQ01ABD100 1TB                              | 19        | 0.39%   |
| Seagate ST4000DM004-2CV104 4TB                      | 19        | 0.39%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 19        | 0.39%   |
| Seagate Expansion 1TB                               | 19        | 0.39%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB    | 19        | 0.39%   |
| Unknown                                             | 19        | 0.39%   |
| Seagate ST500DM002-1BD142 500GB                     | 18        | 0.37%   |
| Intel SSD 660P Series 512GB                         | 18        | 0.37%   |
| HGST HTS721010A9E630 1TB                            | 18        | 0.37%   |
| SanDisk NVMe SSD Drive 512GB                        | 17        | 0.35%   |
| Samsung SSD 980 PRO 1TB                             | 17        | 0.35%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 16        | 0.33%   |
| Unknown SD/MMC/MS PRO 250GB                         | 16        | 0.33%   |
| Unknown MMC Card  128GB                             | 16        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 457       | 626    | 38.79%  |
| WDC                 | 355       | 483    | 30.14%  |
| Toshiba             | 138       | 162    | 11.71%  |
| Hitachi             | 70        | 108    | 5.94%   |
| HGST                | 65        | 74     | 5.52%   |
| Samsung Electronics | 33        | 41     | 2.8%    |
| Apple               | 19        | 22     | 1.61%   |
| Unknown             | 17        | 21     | 1.44%   |
| Fujitsu             | 5         | 8      | 0.42%   |
| Maxtor              | 3         | 3      | 0.25%   |
| SABRENT             | 2         | 3      | 0.17%   |
| JMicron Technology  | 2         | 9      | 0.17%   |
| Intenso             | 2         | 5      | 0.17%   |
| ASMT                | 2         | 2      | 0.17%   |
| ASMedia             | 2         | 2      | 0.17%   |
| USB3.0              | 1         | 1      | 0.08%   |
| RSH-339             | 1         | 1      | 0.08%   |
| PHD 3.0             | 1         | 1      | 0.08%   |
| LaCie               | 1         | 1      | 0.08%   |
| HGST HDN            | 1         | 1      | 0.08%   |
| Asm                 | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 342       | 473    | 23.73%  |
| Kingston            | 173       | 198    | 12.01%  |
| Crucial             | 172       | 231    | 11.94%  |
| SanDisk             | 125       | 152    | 8.67%   |
| WDC                 | 84        | 99     | 5.83%   |
| Apple               | 51        | 54     | 3.54%   |
| PNY                 | 45        | 58     | 3.12%   |
| A-DATA Technology   | 42        | 46     | 2.91%   |
| China               | 41        | 54     | 2.85%   |
| Intel               | 31        | 37     | 2.15%   |
| SK hynix            | 26        | 31     | 1.8%    |
| Micron Technology   | 21        | 23     | 1.46%   |
| SPCC                | 20        | 24     | 1.39%   |
| Toshiba             | 19        | 19     | 1.32%   |
| Netac               | 18        | 18     | 1.25%   |
| Patriot             | 14        | 17     | 0.97%   |
| OCZ                 | 13        | 18     | 0.9%    |
| LITEONIT            | 13        | 21     | 0.9%    |
| LITEON              | 13        | 16     | 0.9%    |
| KingSpec            | 13        | 14     | 0.9%    |
| Intenso             | 12        | 16     | 0.83%   |
| Transcend           | 9         | 12     | 0.62%   |
| Team                | 9         | 13     | 0.62%   |
| Apacer              | 8         | 12     | 0.56%   |
| Lexar               | 7         | 9      | 0.49%   |
| Hewlett-Packard     | 7         | 10     | 0.49%   |
| Seagate             | 5         | 6      | 0.35%   |
| GOODRAM             | 5         | 5      | 0.35%   |
| Mushkin             | 4         | 6      | 0.28%   |
| KingDian            | 4         | 9      | 0.28%   |
| Dogfish             | 4         | 4      | 0.28%   |
| Corsair             | 4         | 5      | 0.28%   |
| Unknown             | 4         | 4      | 0.28%   |
| TO Exter            | 3         | 3      | 0.21%   |
| OWC                 | 3         | 3      | 0.21%   |
| MyDigitalSSD        | 3         | 3      | 0.21%   |
| Gigabyte Technology | 3         | 3      | 0.21%   |
| Fanxiang            | 3         | 3      | 0.21%   |
| TrekStor            | 2         | 2      | 0.14%   |
| Teclast             | 2         | 2      | 0.14%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 1510      | 2169   | 38.4%   |
| SSD     | 1246      | 1809   | 31.69%  |
| HDD     | 995       | 1575   | 25.31%  |
| MMC     | 97        | 113    | 2.47%   |
| Unknown | 84        | 139    | 2.14%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1804      | 3219   | 50.06%  |
| NVMe | 1504      | 2147   | 41.73%  |
| SAS  | 199       | 326    | 5.52%   |
| MMC  | 97        | 113    | 2.69%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1230      | 1768   | 51.51%  |
| 0.51-1.0   | 758       | 1018   | 31.74%  |
| 1.01-2.0   | 233       | 323    | 9.76%   |
| 3.01-4.0   | 67        | 98     | 2.81%   |
| 4.01-10.0  | 63        | 114    | 2.64%   |
| 2.01-3.0   | 32        | 51     | 1.34%   |
| 10.01-20.0 | 5         | 12     | 0.21%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 802       | 26.85%  |
| 251-500        | 752       | 25.18%  |
| 501-1000       | 649       | 21.73%  |
| 1001-2000      | 278       | 9.31%   |
| More than 3000 | 173       | 5.79%   |
| 2001-3000      | 107       | 3.58%   |
| 51-100         | 89        | 2.98%   |
| 1-20           | 73        | 2.44%   |
| 21-50          | 46        | 1.54%   |
| Unknown        | 18        | 0.6%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 887       | 28.59%  |
| 21-50          | 689       | 22.2%   |
| 101-250        | 455       | 14.66%  |
| 51-100         | 395       | 12.73%  |
| 251-500        | 296       | 9.54%   |
| 501-1000       | 174       | 5.61%   |
| 1001-2000      | 92        | 2.96%   |
| More than 3000 | 61        | 1.97%   |
| 2001-3000      | 36        | 1.16%   |
| Unknown        | 18        | 0.58%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                       | Computers | Drives | Percent |
|---------------------------------------------|-----------|--------|---------|
| SK hynix PC711 HFS001TDE9X073N 1TB          | 3         | 3      | 3.45%   |
| HGST HTS725050A7E630 500GB                  | 3         | 4      | 3.45%   |
| WDC WD10JPVX-60JC3T0 1TB                    | 2         | 2      | 2.3%    |
| Seagate ST1000LX015-1U7172 1TB              | 2         | 2      | 2.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB          | 2         | 2      | 2.3%    |
| Samsung Electronics SSD 850 EVO 250GB       | 2         | 2      | 2.3%    |
| WDC WDS240G2G0A-00JH30 240GB SSD            | 1         | 1      | 1.15%   |
| WDC WD60EFRX-68L0BN1 6TB                    | 1         | 1      | 1.15%   |
| WDC WD5001AALS-00J7B1 500GB                 | 1         | 1      | 1.15%   |
| WDC WD5000AADS-00S9B0 500GB                 | 1         | 1      | 1.15%   |
| WDC WD3200BEKT-60PVMT0 320GB                | 1         | 1      | 1.15%   |
| WDC WD20EFRX-68AX9N0 2TB                    | 1         | 5      | 1.15%   |
| WDC WD15EADS-00P8B0 1TB                     | 1         | 1      | 1.15%   |
| WDC WD10SPZX-22Z10T0 1TB                    | 1         | 1      | 1.15%   |
| WDC WD10JPVX-60JC3T1 1TB                    | 1         | 1      | 1.15%   |
| WDC WD10EZEX-60WN4A0 1TB                    | 1         | 1      | 1.15%   |
| WDC WD1002FAEX-00Z3A0 1TB                   | 1         | 1      | 1.15%   |
| WDC WD1001FALS-00E8B0 1TB                   | 1         | 1      | 1.15%   |
| WDC PC SN520 SDAPMUW-128G-1001 128GB        | 1         | 1      | 1.15%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD    | 1         | 1      | 1.15%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD    | 1         | 1      | 1.15%   |
| Toshiba MQ04ABF100 1TB                      | 1         | 1      | 1.15%   |
| Toshiba MQ01ACF050 500GB                    | 1         | 1      | 1.15%   |
| Toshiba MK3252GSX 320GB                     | 1         | 1      | 1.15%   |
| Toshiba MK1655GSX 160GB                     | 1         | 1      | 1.15%   |
| Team TM8FP4004T 4TB                         | 1         | 1      | 1.15%   |
| Team T253X1120G 120GB SSD                   | 1         | 1      | 1.15%   |
| SK hynix PC711 HFS512GDE9X073N 512GB        | 1         | 1      | 1.15%   |
| SK hynix HFS512G39TND-N210A 512GB SSD       | 1         | 1      | 1.15%   |
| SK hynix BC501 NVMe Solid State Drive 512GB | 1         | 1      | 1.15%   |
| Seagate STM3500418AS 500GB                  | 1         | 1      | 1.15%   |
| Seagate ST9320325AS 320GB                   | 1         | 1      | 1.15%   |
| Seagate ST6000AS0002-1N917X 6TB             | 1         | 1      | 1.15%   |
| Seagate ST500LT012-9WS142 500GB             | 1         | 1      | 1.15%   |
| Seagate ST500LM030-2E717D 500GB             | 1         | 1      | 1.15%   |
| Seagate ST5000LM000-2AN170 5TB              | 1         | 1      | 1.15%   |
| Seagate ST3250310AS 250GB                   | 1         | 1      | 1.15%   |
| Seagate ST320LM001 HN-M320MBB 320GB         | 1         | 1      | 1.15%   |
| Seagate ST2000DM008-2FR102 2TB              | 1         | 1      | 1.15%   |
| Seagate ST2000DM006-2DM164 2TB              | 1         | 1      | 1.15%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 19     | 20.24%  |
| WDC                 | 15        | 19     | 17.86%  |
| Samsung Electronics | 10        | 11     | 11.9%   |
| HGST                | 7         | 8      | 8.33%   |
| Toshiba             | 6         | 6      | 7.14%   |
| SK hynix            | 6         | 6      | 7.14%   |
| Kingston            | 3         | 4      | 3.57%   |
| Hitachi             | 3         | 5      | 3.57%   |
| Team                | 2         | 2      | 2.38%   |
| Micron Technology   | 2         | 4      | 2.38%   |
| Intel               | 2         | 2      | 2.38%   |
| Crucial             | 2         | 2      | 2.38%   |
| A-DATA Technology   | 2         | 2      | 2.38%   |
| SanDisk             | 1         | 1      | 1.19%   |
| SABRENT             | 1         | 1      | 1.19%   |
| Plextor             | 1         | 1      | 1.19%   |
| Lexar               | 1         | 1      | 1.19%   |
| Leven               | 1         | 1      | 1.19%   |
| China               | 1         | 1      | 1.19%   |
| BAITITON            | 1         | 1      | 1.19%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 19     | 36.96%  |
| WDC                 | 13        | 17     | 28.26%  |
| HGST                | 7         | 8      | 15.22%  |
| Toshiba             | 4         | 4      | 8.7%    |
| Hitachi             | 3         | 5      | 6.52%   |
| Samsung Electronics | 2         | 2      | 4.35%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 45        | 55     | 54.22%  |
| SSD  | 24        | 26     | 28.92%  |
| NVMe | 14        | 16     | 16.87%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 1         | 1      | 33.33%  |
| Samsung Electronics HM321HI 320GB | 1         | 1      | 33.33%  |
| KingDian S400 120GB               | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| KingDian            | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 2261      | 4523   | 73.41%  |
| Works    | 736       | 1181   | 23.9%   |
| Malfunc  | 80        | 97     | 2.6%    |
| Failed   | 3         | 4      | 0.1%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1612      | 38.68%  |
| AMD                            | 738       | 17.71%  |
| Samsung Electronics            | 595       | 14.28%  |
| SanDisk                        | 274       | 6.58%   |
| SK hynix                       | 135       | 3.24%   |
| Phison Electronics             | 118       | 2.83%   |
| Micron/Crucial Technology      | 82        | 1.97%   |
| Micron Technology              | 79        | 1.9%    |
| Kingston Technology Company    | 78        | 1.87%   |
| ASMedia Technology             | 59        | 1.42%   |
| Toshiba America Info Systems   | 50        | 1.2%    |
| Silicon Motion                 | 47        | 1.13%   |
| KIOXIA                         | 41        | 0.98%   |
| Nvidia                         | 40        | 0.96%   |
| ADATA Technology               | 39        | 0.94%   |
| Marvell Technology Group       | 31        | 0.74%   |
| Realtek Semiconductor          | 24        | 0.58%   |
| Solid State Storage Technology | 22        | 0.53%   |
| JMicron Technology             | 16        | 0.38%   |
| Union Memory (Shenzhen)        | 14        | 0.34%   |
| Apple                          | 11        | 0.26%   |
| Seagate Technology             | 9         | 0.22%   |
| Broadcom / LSI                 | 8         | 0.19%   |
| Shenzhen Longsys Electronics   | 7         | 0.17%   |
| LSI Logic / Symbios Logic      | 6         | 0.14%   |
| MAXIO Technology (Hangzhou)    | 5         | 0.12%   |
| Lite-On Technology             | 5         | 0.12%   |
| INNOGRIT                       | 5         | 0.12%   |
| VIA Technologies               | 3         | 0.07%   |
| Hewlett-Packard                | 3         | 0.07%   |
| Solidigm                       | 2         | 0.05%   |
| Silicon Image                  | 2         | 0.05%   |
| Netac Technology               | 2         | 0.05%   |
| Yangtze Memory Technologies    | 1         | 0.02%   |
| Transcend                      | 1         | 0.02%   |
| O2 Micro                       | 1         | 0.02%   |
| Biwin Storage Technology       | 1         | 0.02%   |
| Adaptec                        | 1         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 529       | 11.47%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 263       | 5.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 127       | 2.75%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 126       | 2.73%   |
| AMD 500 Series Chipset SATA Controller                                         | 122       | 2.65%   |
| Intel Volume Management Device NVMe RAID Controller                            | 121       | 2.62%   |
| Samsung NVMe SSD Controller 980                                                | 117       | 2.54%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 116       | 2.52%   |
| AMD 400 Series Chipset SATA Controller                                         | 112       | 2.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 94        | 2.04%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 83        | 1.8%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 75        | 1.63%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 73        | 1.58%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 66        | 1.43%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 57        | 1.24%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 57        | 1.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 57        | 1.24%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 55        | 1.19%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 52        | 1.13%   |
| Phison E12 NVMe Controller                                                     | 52        | 1.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 50        | 1.08%   |
| Intel Comet Lake SATA AHCI Controller                                          | 46        | 1%      |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 45        | 0.98%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 45        | 0.98%   |
| Intel SSD 660P Series                                                          | 44        | 0.95%   |
| Micron NVMe Storage Controller                                                 | 43        | 0.93%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 42        | 0.91%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 41        | 0.89%   |
| Intel SATA Controller [RAID mode]                                              | 40        | 0.87%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 37        | 0.8%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 36        | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 35        | 0.76%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 32        | 0.69%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 32        | 0.69%   |
| SanDisk Non-Volatile memory controller                                         | 31        | 0.67%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 30        | 0.65%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 29        | 0.63%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 29        | 0.63%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 29        | 0.63%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 28        | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 2062      | 51.08%  |
| NVMe | 1498      | 37.11%  |
| RAID | 290       | 7.18%   |
| IDE  | 172       | 4.26%   |
| SAS  | 14        | 0.35%   |
| SCSI | 1         | 0.02%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 1950      | 67.17%  |
| AMD    | 949       | 32.69%  |
| ARM    | 4         | 0.14%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 44        | 1.51%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 41        | 1.41%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 36        | 1.24%   |
| AMD Ryzen 5 3600 6-Core Processor             | 36        | 1.24%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 34        | 1.17%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 34        | 1.17%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 32        | 1.1%    |
| Intel 12th Gen Core i7-12700H                 | 30        | 1.03%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 28        | 0.96%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 28        | 0.96%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 27        | 0.93%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 26        | 0.89%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 26        | 0.89%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 26        | 0.89%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 26        | 0.89%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 25        | 0.86%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 24        | 0.83%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 23        | 0.79%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 23        | 0.79%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 23        | 0.79%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 22        | 0.76%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 22        | 0.76%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 22        | 0.76%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 21        | 0.72%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 20        | 0.69%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 19        | 0.65%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 19        | 0.65%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 16        | 0.55%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 16        | 0.55%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 16        | 0.55%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 16        | 0.55%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 15        | 0.52%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 15        | 0.52%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 15        | 0.52%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 15        | 0.52%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 15        | 0.52%   |
| AMD Ryzen 7 PRO 5850U with Radeon Graphics    | 15        | 0.52%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 15        | 0.52%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 14        | 0.48%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 14        | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 615       | 21.16%  |
| Intel Core i5           | 555       | 19.1%   |
| Other                   | 357       | 12.28%  |
| AMD Ryzen 5             | 304       | 10.46%  |
| AMD Ryzen 7             | 292       | 10.05%  |
| Intel Core i3           | 140       | 4.82%   |
| AMD Ryzen 9             | 119       | 4.09%   |
| Intel Celeron           | 71        | 2.44%   |
| Intel Core 2 Duo        | 66        | 2.27%   |
| Intel Xeon              | 60        | 2.06%   |
| AMD FX                  | 36        | 1.24%   |
| AMD Ryzen 3             | 30        | 1.03%   |
| Intel Pentium           | 25        | 0.86%   |
| Intel Core i9           | 23        | 0.79%   |
| AMD Ryzen 7 PRO         | 23        | 0.79%   |
| AMD A8                  | 18        | 0.62%   |
| AMD A10                 | 17        | 0.58%   |
| AMD A6                  | 14        | 0.48%   |
| AMD Ryzen 5 PRO         | 10        | 0.34%   |
| Intel Pentium Dual-Core | 9         | 0.31%   |
| Intel Core 2 Quad       | 9         | 0.31%   |
| AMD Ryzen Threadripper  | 9         | 0.31%   |
| Intel Pentium Silver    | 8         | 0.28%   |
| AMD Athlon              | 8         | 0.28%   |
| AMD A4                  | 7         | 0.24%   |
| Intel Pentium Gold      | 6         | 0.21%   |
| AMD Athlon II X4        | 6         | 0.21%   |
| AMD Athlon II X2        | 6         | 0.21%   |
| AMD Phenom II X4        | 5         | 0.17%   |
| Intel Core m5           | 4         | 0.14%   |
| Intel Core 2            | 4         | 0.14%   |
| Intel Atom              | 4         | 0.14%   |
| AMD Ryzen 3 PRO         | 4         | 0.14%   |
| AMD Phenom II X6        | 4         | 0.14%   |
| Intel Pentium D         | 3         | 0.1%    |
| AMD Phenom              | 3         | 0.1%    |
| AMD E                   | 3         | 0.1%    |
| AMD Athlon X4           | 3         | 0.1%    |
| Intel Pentium Dual      | 2         | 0.07%   |
| Intel Genuine           | 2         | 0.07%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 990       | 34.07%  |
| 2       | 741       | 25.5%   |
| 8       | 442       | 15.21%  |
| 6       | 439       | 15.11%  |
| 12      | 87        | 2.99%   |
| 16      | 64        | 2.2%    |
| 14      | 54        | 1.86%   |
| 10      | 44        | 1.51%   |
| 3       | 15        | 0.52%   |
| 1       | 13        | 0.45%   |
| 24      | 7         | 0.24%   |
| Unknown | 4         | 0.14%   |
| 32      | 2         | 0.07%   |
| 64      | 1         | 0.03%   |
| 40      | 1         | 0.03%   |
| 36      | 1         | 0.03%   |
| 18      | 1         | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2883      | 99.31%  |
| 2       | 16        | 0.55%   |
| Unknown | 4         | 0.14%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 2388      | 82.17%  |
| 1       | 514       | 17.69%  |
| Unknown | 4         | 0.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2900      | 99.9%   |
| 64-bit         | 3         | 0.1%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2284      | 77.53%  |
| 0x806c1    | 49        | 1.66%   |
| 0x0a50000c | 40        | 1.36%   |
| 0x806ec    | 26        | 0.88%   |
| 0x806ea    | 24        | 0.81%   |
| 0x806d1    | 24        | 0.81%   |
| 0x08701021 | 24        | 0.81%   |
| 0x906a3    | 23        | 0.78%   |
| 0x306a9    | 22        | 0.75%   |
| 0x08600106 | 22        | 0.75%   |
| 0x906ea    | 21        | 0.71%   |
| 0xa0652    | 20        | 0.68%   |
| 0x08608103 | 19        | 0.64%   |
| 0x0a404101 | 15        | 0.51%   |
| 0x08108109 | 15        | 0.51%   |
| 0x506e3    | 14        | 0.48%   |
| 0x406e3    | 14        | 0.48%   |
| 0x206a7    | 14        | 0.48%   |
| 0x0a201016 | 14        | 0.48%   |
| 0x806e9    | 13        | 0.44%   |
| 0x306c3    | 13        | 0.44%   |
| 0x0a50000d | 13        | 0.44%   |
| 0x0800820d | 13        | 0.44%   |
| 0x906a4    | 12        | 0.41%   |
| 0x40651    | 12        | 0.41%   |
| 0x0a404102 | 12        | 0.41%   |
| 0x906e9    | 11        | 0.37%   |
| 0x0a601203 | 11        | 0.37%   |
| 0x306d4    | 9         | 0.31%   |
| 0x08600104 | 9         | 0.31%   |
| 0x706e5    | 8         | 0.27%   |
| 0x1067a    | 8         | 0.27%   |
| 0x706a8    | 7         | 0.24%   |
| 0x906ec    | 5         | 0.17%   |
| 0x90672    | 5         | 0.17%   |
| 0x806eb    | 5         | 0.17%   |
| 0x0a20120a | 5         | 0.17%   |
| 0x08701013 | 5         | 0.17%   |
| 0x08600103 | 5         | 0.17%   |
| 0x08108102 | 5         | 0.17%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 455       | 15.64%  |
| Zen 3            | 283       | 9.73%   |
| Unknown          | 281       | 9.66%   |
| Haswell          | 257       | 8.83%   |
| Zen 2            | 189       | 6.5%    |
| SandyBridge      | 149       | 5.12%   |
| Skylake          | 145       | 4.98%   |
| IvyBridge        | 142       | 4.88%   |
| TigerLake        | 129       | 4.43%   |
| Zen+             | 126       | 4.33%   |
| CometLake        | 89        | 3.06%   |
| Broadwell        | 85        | 2.92%   |
| Penryn           | 77        | 2.65%   |
| Alderlake Hybrid | 62        | 2.13%   |
| Zen              | 61        | 2.1%    |
| IceLake          | 60        | 2.06%   |
| Westmere         | 52        | 1.79%   |
| Piledriver       | 51        | 1.75%   |
| Goldmont plus    | 37        | 1.27%   |
| K10              | 29        | 1%      |
| Silvermont       | 27        | 0.93%   |
| Nehalem          | 27        | 0.93%   |
| Excavator        | 21        | 0.72%   |
| Core             | 17        | 0.58%   |
| Puma             | 15        | 0.52%   |
| Steamroller      | 12        | 0.41%   |
| K10 Llano        | 6         | 0.21%   |
| Goldmont         | 5         | 0.17%   |
| Jaguar           | 4         | 0.14%   |
| Tremont          | 3         | 0.1%    |
| NetBurst         | 3         | 0.1%    |
| K8 Hammer        | 3         | 0.1%    |
| Bulldozer        | 3         | 0.1%    |
| Bobcat           | 3         | 0.1%    |
| K8 & K10 hybrid  | 1         | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 1499      | 42.07%  |
| Nvidia                     | 1147      | 32.19%  |
| AMD                        | 913       | 25.62%  |
| Matrox Electronics Systems | 4         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 117       | 3.2%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 116       | 3.18%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 105       | 2.87%   |
| Intel UHD Graphics 620                                                      | 86        | 2.35%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 80        | 2.19%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 78        | 2.14%   |
| AMD Renoir                                                                  | 76        | 2.08%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 73        | 2%      |
| Intel Alder Lake-P Integrated Graphics Controller                           | 73        | 2%      |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 69        | 1.89%   |
| AMD Lucienne                                                                | 62        | 1.7%    |
| Intel Skylake GT2 [HD Graphics 520]                                         | 58        | 1.59%   |
| Intel HD Graphics 620                                                       | 56        | 1.53%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 53        | 1.45%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 52        | 1.42%   |
| Intel HD Graphics 5500                                                      | 50        | 1.37%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 48        | 1.31%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 47        | 1.29%   |
| AMD Rembrandt [Radeon 680M]                                                 | 47        | 1.29%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 46        | 1.26%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 44        | 1.2%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 44        | 1.2%    |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 39        | 1.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 39        | 1.07%   |
| Intel HD Graphics 530                                                       | 37        | 1.01%   |
| Intel HD Graphics 630                                                       | 34        | 0.93%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 33        | 0.9%    |
| Intel Core Processor Integrated Graphics Controller                         | 33        | 0.9%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 32        | 0.88%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 32        | 0.88%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 30        | 0.82%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 28        | 0.77%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 28        | 0.77%   |
| AMD Raphael                                                                 | 25        | 0.68%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 25        | 0.68%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 25        | 0.68%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 23        | 0.63%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 22        | 0.6%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 21        | 0.57%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 21        | 0.57%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| 1 x Intel            | 987       | 33.81%  |
| 1 x AMD              | 660       | 22.61%  |
| 1 x Nvidia           | 581       | 19.9%   |
| Intel + Nvidia       | 411       | 14.08%  |
| AMD + Nvidia         | 135       | 4.62%   |
| Intel + AMD          | 60        | 2.06%   |
| 2 x AMD              | 56        | 1.92%   |
| 2 x Nvidia           | 13        | 0.45%   |
| Other                | 7         | 0.24%   |
| 1 x Matrox           | 4         | 0.14%   |
| Intel + 2 x Nvidia   | 3         | 0.1%    |
| 2 x AMD + 1 x Nvidia | 1         | 0.03%   |
| AMD + 2 x Nvidia     | 1         | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1925      | 65.74%  |
| Proprietary | 932       | 31.83%  |
| Unknown     | 71        | 2.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 2358      | 80.07%  |
| 7.01-8.0   | 114       | 3.87%   |
| 1.01-2.0   | 103       | 3.5%    |
| 0.01-0.5   | 101       | 3.43%   |
| 3.01-4.0   | 89        | 3.02%   |
| 5.01-6.0   | 70        | 2.38%   |
| 8.01-16.0  | 62        | 2.11%   |
| 0.51-1.0   | 27        | 0.92%   |
| 2.01-3.0   | 14        | 0.48%   |
| 16.01-24.0 | 6         | 0.2%    |
| 32.01-64.0 | 1         | 0.03%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 393       | 11.74%  |
| Samsung Electronics     | 363       | 10.85%  |
| BOE                     | 323       | 9.65%   |
| Chimei Innolux          | 295       | 8.81%   |
| LG Display              | 262       | 7.83%   |
| Goldstar                | 223       | 6.66%   |
| Dell                    | 209       | 6.24%   |
| Acer                    | 116       | 3.47%   |
| Apple                   | 109       | 3.26%   |
| Hewlett-Packard         | 95        | 2.84%   |
| AOC                     | 85        | 2.54%   |
| Sharp                   | 79        | 2.36%   |
| ASUSTek Computer        | 73        | 2.18%   |
| Ancor Communications    | 66        | 1.97%   |
| BenQ                    | 58        | 1.73%   |
| Lenovo                  | 53        | 1.58%   |
| PANDA                   | 51        | 1.52%   |
| Philips                 | 46        | 1.37%   |
| InfoVision              | 30        | 0.9%    |
| MSI                     | 25        | 0.75%   |
| Iiyama                  | 25        | 0.75%   |
| CSO                     | 21        | 0.63%   |
| ViewSonic               | 19        | 0.57%   |
| Chi Mei Optoelectronics | 19        | 0.57%   |
| Sceptre Tech            | 18        | 0.54%   |
| Sony                    | 16        | 0.48%   |
| NEC Computers           | 15        | 0.45%   |
| Gigabyte Technology     | 14        | 0.42%   |
| Panasonic               | 13        | 0.39%   |
| Vizio                   | 12        | 0.36%   |
| TMX                     | 9         | 0.27%   |
| Unknown                 | 8         | 0.24%   |
| Toshiba                 | 8         | 0.24%   |
| Vestel Elektronik       | 7         | 0.21%   |
| Insignia                | 6         | 0.18%   |
| Eizo                    | 6         | 0.18%   |
| Pioneer                 | 5         | 0.15%   |
| LG Electronics          | 5         | 0.15%   |
| HKC                     | 5         | 0.15%   |
| Hitachi                 | 5         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch     | 20        | 0.58%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 20        | 0.58%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch       | 18        | 0.52%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 17        | 0.49%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 17        | 0.49%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch     | 17        | 0.49%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 13        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 13        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 13        | 0.38%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 11        | 0.32%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch        | 10        | 0.29%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch    | 9         | 0.26%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch         | 9         | 0.26%   |
| LG Display LCD Monitor LGD046F 1920x1080 350x190mm 15.7-inch         | 9         | 0.26%   |
| Chimei Innolux LCD Monitor CMN1408 1920x1080 309x173mm 13.9-inch     | 9         | 0.26%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 9         | 0.26%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                 | 9         | 0.26%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 8         | 0.23%   |
| InfoVision LCD Monitor IVO8C78 1920x1080 309x174mm 14.0-inch         | 8         | 0.23%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                    | 8         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 8         | 0.23%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch        | 8         | 0.23%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                     | 8         | 0.23%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch | 7         | 0.2%    |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 7         | 0.2%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 7         | 0.2%    |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 7         | 0.2%    |
| Dell P2419H DELD0DA 1920x1080 530x300mm 24.0-inch                    | 7         | 0.2%    |
| Dell P2317H DEL40F4 1920x1080 509x286mm 23.0-inch                    | 7         | 0.2%    |
| BOE LCD Monitor BOE08DF 1920x1080 344x194mm 15.5-inch                | 7         | 0.2%    |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                | 7         | 0.2%    |
| AU Optronics LCD Monitor AUO80ED 1920x1080 344x193mm 15.5-inch       | 7         | 0.2%    |
| Apple Color LCD APPA01B 1440x900 286x179mm 13.3-inch                 | 7         | 0.2%    |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch     | 7         | 0.2%    |
| Samsung Electronics LC49G95T SAM7053 2560x1440 1193x336mm 48.8-inch  | 6         | 0.17%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch         | 6         | 0.17%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                | 6         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 6         | 0.17%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 6         | 0.17%   |
| Chimei Innolux LCD Monitor CMN14D6 1366x768 309x173mm 13.9-inch      | 6         | 0.17%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1500      | 47.29%  |
| 1366x768 (WXGA)    | 425       | 13.4%   |
| 3840x2160 (4K)     | 282       | 8.89%   |
| 2560x1440 (QHD)    | 220       | 6.94%   |
| 1920x1200 (WUXGA)  | 92        | 2.9%    |
| 1600x900 (HD+)     | 85        | 2.68%   |
| 3440x1440          | 74        | 2.33%   |
| 2560x1080          | 60        | 1.89%   |
| 2560x1600          | 58        | 1.83%   |
| 1440x900 (WXGA+)   | 50        | 1.58%   |
| 2880x1800          | 40        | 1.26%   |
| 1280x1024 (SXGA)   | 40        | 1.26%   |
| 1680x1050 (WSXGA+) | 39        | 1.23%   |
| 1280x800 (WXGA)    | 35        | 1.1%    |
| 3840x1080          | 20        | 0.63%   |
| 1360x768           | 18        | 0.57%   |
| 3840x2400          | 13        | 0.41%   |
| 1920x540           | 13        | 0.41%   |
| 2160x1440          | 10        | 0.32%   |
| 3840x1600          | 8         | 0.25%   |
| 2256x1504          | 8         | 0.25%   |
| Unknown            | 8         | 0.25%   |
| 3200x1800 (QHD+)   | 7         | 0.22%   |
| 2736x1824          | 6         | 0.19%   |
| 1920x1280          | 6         | 0.19%   |
| 1024x768 (XGA)     | 6         | 0.19%   |
| 1600x1200          | 5         | 0.16%   |
| 3456x2160          | 4         | 0.13%   |
| 3200x2000          | 4         | 0.13%   |
| 3072x1920          | 4         | 0.13%   |
| 1280x720 (HD)      | 4         | 0.13%   |
| 3840x1100          | 3         | 0.09%   |
| 3000x2000          | 3         | 0.09%   |
| 800x1280           | 2         | 0.06%   |
| 4480x1440          | 2         | 0.06%   |
| 2880x1620          | 2         | 0.06%   |
| 2304x1440          | 2         | 0.06%   |
| 2240x1400          | 2         | 0.06%   |
| 3840x1200          | 1         | 0.03%   |
| 3280x1080          | 1         | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 825       | 24.58%  |
| 13      | 370       | 11.03%  |
| 27      | 312       | 9.3%    |
| 14      | 262       | 7.81%   |
| 24      | 257       | 7.66%   |
| 23      | 196       | 5.84%   |
| 17      | 157       | 4.68%   |
| 21      | 139       | 4.14%   |
| 31      | 131       | 3.9%    |
| 34      | 120       | 3.58%   |
| 16      | 54        | 1.61%   |
| 12      | 54        | 1.61%   |
| 19      | 50        | 1.49%   |
| Unknown | 48        | 1.43%   |
| 32      | 39        | 1.16%   |
| 84      | 34        | 1.01%   |
| 18      | 31        | 0.92%   |
| 22      | 30        | 0.89%   |
| 20      | 26        | 0.77%   |
| 72      | 25        | 0.74%   |
| 11      | 23        | 0.69%   |
| 48      | 20        | 0.6%    |
| 40      | 16        | 0.48%   |
| 28      | 15        | 0.45%   |
| 37      | 11        | 0.33%   |
| 54      | 10        | 0.3%    |
| 25      | 10        | 0.3%    |
| 35      | 8         | 0.24%   |
| 29      | 8         | 0.24%   |
| 26      | 8         | 0.24%   |
| 65      | 7         | 0.21%   |
| 33      | 7         | 0.21%   |
| 52      | 6         | 0.18%   |
| 49      | 6         | 0.18%   |
| 47      | 5         | 0.15%   |
| 46      | 4         | 0.12%   |
| 36      | 4         | 0.12%   |
| 74      | 3         | 0.09%   |
| 57      | 3         | 0.09%   |
| 44      | 3         | 0.09%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 1310      | 40.04%  |
| 501-600     | 685       | 20.94%  |
| 201-300     | 279       | 8.53%   |
| 401-500     | 248       | 7.58%   |
| 601-700     | 185       | 5.65%   |
| 351-400     | 172       | 5.26%   |
| 701-800     | 165       | 5.04%   |
| 1501-2000   | 67        | 2.05%   |
| 1001-1500   | 65        | 1.99%   |
| Unknown     | 48        | 1.47%   |
| 801-900     | 40        | 1.22%   |
| 901-1000    | 5         | 0.15%   |
| 1-100       | 2         | 0.06%   |
| 101-200     | 1         | 0.03%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 2310      | 77.83%  |
| 16/10   | 364       | 12.26%  |
| 21/9    | 144       | 4.85%   |
| 5/4     | 42        | 1.42%   |
| 3/2     | 34        | 1.15%   |
| 32/9    | 24        | 0.81%   |
| Unknown | 22        | 0.74%   |
| 4/3     | 18        | 0.61%   |
| 3.40    | 3         | 0.1%    |
| 6/5     | 2         | 0.07%   |
| 3.73    | 1         | 0.03%   |
| 3.20    | 1         | 0.03%   |
| 0.67    | 1         | 0.03%   |
| 0.63    | 1         | 0.03%   |
| 0.56    | 1         | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 822       | 24.77%  |
| 201-250        | 484       | 14.59%  |
| 81-90          | 480       | 14.47%  |
| 301-350        | 322       | 9.7%    |
| 351-500        | 309       | 9.31%   |
| 71-80          | 154       | 4.64%   |
| 121-130        | 123       | 3.71%   |
| 151-200        | 110       | 3.32%   |
| More than 1000 | 100       | 3.01%   |
| 251-300        | 98        | 2.95%   |
| 501-1000       | 69        | 2.08%   |
| 111-120        | 54        | 1.63%   |
| 141-150        | 53        | 1.6%    |
| Unknown        | 48        | 1.45%   |
| 61-70          | 43        | 1.3%    |
| 51-60          | 26        | 0.78%   |
| 131-140        | 12        | 0.36%   |
| 91-100         | 8         | 0.24%   |
| 1-40           | 3         | 0.09%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 1003      | 31.36%  |
| 51-100        | 953       | 29.8%   |
| 101-120       | 726       | 22.7%   |
| 161-240       | 278       | 8.69%   |
| More than 240 | 112       | 3.5%    |
| 1-50          | 78        | 2.44%   |
| Unknown       | 48        | 1.5%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 2234      | 75.65%  |
| 2     | 537       | 18.18%  |
| 0     | 93        | 3.15%   |
| 3     | 81        | 2.74%   |
| 4     | 7         | 0.24%   |
| 6     | 1         | 0.03%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 1573      | 35.69%  |
| Intel                             | 1530      | 34.72%  |
| Qualcomm Atheros                  | 401       | 9.1%    |
| Broadcom                          | 221       | 5.01%   |
| MediaTek                          | 141       | 3.2%    |
| Broadcom Limited                  | 71        | 1.61%   |
| TP-Link                           | 46        | 1.04%   |
| ASIX Electronics                  | 37        | 0.84%   |
| Marvell Technology Group          | 35        | 0.79%   |
| Nvidia                            | 29        | 0.66%   |
| Ralink Technology                 | 28        | 0.64%   |
| Samsung Electronics               | 24        | 0.54%   |
| Ralink                            | 23        | 0.52%   |
| NetGear                           | 21        | 0.48%   |
| Xiaomi                            | 17        | 0.39%   |
| DisplayLink                       | 17        | 0.39%   |
| Microsoft                         | 12        | 0.27%   |
| Aquantia                          | 12        | 0.27%   |
| Qualcomm                          | 11        | 0.25%   |
| Dell                              | 11        | 0.25%   |
| Sierra Wireless                   | 10        | 0.23%   |
| Lenovo                            | 10        | 0.23%   |
| InterBiometrics                   | 10        | 0.23%   |
| Google                            | 10        | 0.23%   |
| D-Link                            | 9         | 0.2%    |
| ASUSTek Computer                  | 8         | 0.18%   |
| D-Link System                     | 7         | 0.16%   |
| Qualcomm Atheros Communications   | 6         | 0.14%   |
| OPPO Electronics                  | 6         | 0.14%   |
| OnePlus Technology (Shenzhen)     | 6         | 0.14%   |
| JMicron Technology                | 6         | 0.14%   |
| Linksys                           | 5         | 0.11%   |
| Huawei Technologies               | 5         | 0.11%   |
| Hewlett-Packard                   | 5         | 0.11%   |
| Ericsson Business Mobile Networks | 4         | 0.09%   |
| Mellanox Technologies             | 3         | 0.07%   |
| Fibocom                           | 3         | 0.07%   |
| Edimax Technology                 | 3         | 0.07%   |
| Apple                             | 3         | 0.07%   |
| U-Blox                            | 2         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1005      | 19.27%  |
| Intel Wi-Fi 6 AX200                                               | 240       | 4.6%    |
| Realtek RTL8125 2.5GbE Controller                                 | 148       | 2.84%   |
| Intel I211 Gigabit Network Connection                             | 121       | 2.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 115       | 2.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 106       | 2.03%   |
| Intel Wi-Fi 6 AX201                                               | 101       | 1.94%   |
| Intel Wireless 8265 / 8275                                        | 98        | 1.88%   |
| Intel Ethernet Controller I225-V                                  | 97        | 1.86%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 86        | 1.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 75        | 1.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 73        | 1.4%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 69        | 1.32%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 64        | 1.23%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 62        | 1.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 58        | 1.11%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 56        | 1.07%   |
| Intel Wireless 7265                                               | 56        | 1.07%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 55        | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 54        | 1.04%   |
| Intel Ethernet Connection I217-LM                                 | 52        | 1%      |
| Intel Wireless 7260                                               | 50        | 0.96%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 48        | 0.92%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 48        | 0.92%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 48        | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 44        | 0.84%   |
| Intel Wireless 8260                                               | 44        | 0.84%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 44        | 0.84%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 43        | 0.82%   |
| Intel Wireless-AC 9260                                            | 36        | 0.69%   |
| Intel Ethernet Connection (2) I219-V                              | 36        | 0.69%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 35        | 0.67%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 35        | 0.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 33        | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 31        | 0.59%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 30        | 0.58%   |
| Realtek 802.11ac NIC                                              | 30        | 0.58%   |
| ASIX AX88179 Gigabit Ethernet                                     | 30        | 0.58%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 28        | 0.54%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 27        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 1244      | 48.54%  |
| Realtek Semiconductor                 | 406       | 15.84%  |
| Qualcomm Atheros                      | 321       | 12.52%  |
| Broadcom                              | 175       | 6.83%   |
| MediaTek                              | 140       | 5.46%   |
| Broadcom Limited                      | 59        | 2.3%    |
| TP-Link                               | 39        | 1.52%   |
| Ralink Technology                     | 28        | 1.09%   |
| Ralink                                | 23        | 0.9%    |
| NetGear                               | 21        | 0.82%   |
| Microsoft                             | 12        | 0.47%   |
| Marvell Technology Group              | 11        | 0.43%   |
| Sierra Wireless                       | 10        | 0.39%   |
| Qualcomm                              | 10        | 0.39%   |
| Dell                                  | 10        | 0.39%   |
| D-Link                                | 8         | 0.31%   |
| ASUSTek Computer                      | 7         | 0.27%   |
| Qualcomm Atheros Communications       | 6         | 0.23%   |
| D-Link System                         | 6         | 0.23%   |
| Linksys                               | 5         | 0.2%    |
| Hewlett-Packard                       | 3         | 0.12%   |
| Fibocom                               | 3         | 0.12%   |
| Edimax Technology                     | 3         | 0.12%   |
| Belkin Components                     | 2         | 0.08%   |
| Accton Technology                     | 2         | 0.08%   |
| ZyDAS                                 | 1         | 0.04%   |
| Wacom                                 | 1         | 0.04%   |
| Sitecom Europe                        | 1         | 0.04%   |
| Micro Star International              | 1         | 0.04%   |
| IMC Networks                          | 1         | 0.04%   |
| Gemtek                                | 1         | 0.04%   |
| AVM                                   | 1         | 0.04%   |
| Arduino SA                            | 1         | 0.04%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 240       | 9.3%    |
| Intel Wi-Fi 6 AX201                                            | 101       | 3.91%   |
| Intel Wireless 8265 / 8275                                     | 98        | 3.8%    |
| Intel Alder Lake-P PCH CNVi WiFi                               | 86        | 3.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 73        | 2.83%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 69        | 2.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 64        | 2.48%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 62        | 2.4%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 58        | 2.25%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 56        | 2.17%   |
| Intel Wireless 7265                                            | 56        | 2.17%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 55        | 2.13%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 54        | 2.09%   |
| Intel Wireless 7260                                            | 50        | 1.94%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 48        | 1.86%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 48        | 1.86%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 48        | 1.86%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 44        | 1.7%    |
| Intel Wireless 8260                                            | 44        | 1.7%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 44        | 1.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                 | 43        | 1.67%   |
| Intel Wireless-AC 9260                                         | 36        | 1.39%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 35        | 1.36%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 35        | 1.36%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 33        | 1.28%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 30        | 1.16%   |
| Realtek 802.11ac NIC                                           | 30        | 1.16%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 28        | 1.08%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 27        | 1.05%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 27        | 1.05%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller         | 25        | 0.97%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 23        | 0.89%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 21        | 0.81%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 21        | 0.81%   |
| Broadcom BCM43142 802.11b/g/n                                  | 21        | 0.81%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 20        | 0.77%   |
| Intel Wireless 3165                                            | 20        | 0.77%   |
| Intel Alder Lake-S PCH CNVi WiFi                               | 19        | 0.74%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 19        | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 18        | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 1385      | 54.7%   |
| Intel                         | 718       | 28.36%  |
| Qualcomm Atheros              | 114       | 4.5%    |
| Broadcom                      | 89        | 3.52%   |
| ASIX Electronics              | 37        | 1.46%   |
| Nvidia                        | 29        | 1.15%   |
| Marvell Technology Group      | 24        | 0.95%   |
| Xiaomi                        | 17        | 0.67%   |
| DisplayLink                   | 17        | 0.67%   |
| Samsung Electronics           | 15        | 0.59%   |
| Broadcom Limited              | 12        | 0.47%   |
| Aquantia                      | 12        | 0.47%   |
| Lenovo                        | 10        | 0.39%   |
| Google                        | 10        | 0.39%   |
| TP-Link                       | 7         | 0.28%   |
| OPPO Electronics              | 6         | 0.24%   |
| JMicron Technology            | 6         | 0.24%   |
| OnePlus Technology (Shenzhen) | 5         | 0.2%    |
| Huawei Technologies           | 4         | 0.16%   |
| Mellanox Technologies         | 3         | 0.12%   |
| Motorola PCS                  | 2         | 0.08%   |
| Apple                         | 2         | 0.08%   |
| VIA Technologies              | 1         | 0.04%   |
| T & A Mobile Phones           | 1         | 0.04%   |
| Qualcomm                      | 1         | 0.04%   |
| Hewlett-Packard               | 1         | 0.04%   |
| D-Link System                 | 1         | 0.04%   |
| D-Link                        | 1         | 0.04%   |
| ASUSTek Computer              | 1         | 0.04%   |
| American Megatrends           | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1005      | 38.79%  |
| Realtek RTL8125 2.5GbE Controller                                 | 148       | 5.71%   |
| Intel I211 Gigabit Network Connection                             | 121       | 4.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 115       | 4.44%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 106       | 4.09%   |
| Intel Ethernet Controller I225-V                                  | 97        | 3.74%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 75        | 2.89%   |
| Intel Ethernet Connection I217-LM                                 | 52        | 2.01%   |
| Intel Ethernet Connection (2) I219-V                              | 36        | 1.39%   |
| Intel Ethernet Connection (4) I219-LM                             | 31        | 1.2%    |
| ASIX AX88179 Gigabit Ethernet                                     | 30        | 1.16%   |
| Intel Ethernet Connection (7) I219-V                              | 25        | 0.96%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 20        | 0.77%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 20        | 0.77%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 19        | 0.73%   |
| Nvidia MCP79 Ethernet                                             | 19        | 0.73%   |
| Intel Ethernet Connection (2) I219-LM                             | 19        | 0.73%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 17        | 0.66%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 17        | 0.66%   |
| Intel Ethernet Connection (3) I218-LM                             | 17        | 0.66%   |
| Intel Ethernet Connection I219-LM                                 | 16        | 0.62%   |
| Intel Ethernet Connection I217-V                                  | 16        | 0.62%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 15        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 14        | 0.54%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 14        | 0.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 13        | 0.5%    |
| Intel Ethernet Connection (4) I219-V                              | 13        | 0.5%    |
| Intel Ethernet Connection (2) I218-V                              | 13        | 0.5%    |
| Intel I210 Gigabit Network Connection                             | 12        | 0.46%   |
| Intel Ethernet Connection I218-LM                                 | 12        | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                             | 11        | 0.42%   |
| Intel Ethernet Connection (13) I219-V                             | 10        | 0.39%   |
| Intel 82579V Gigabit Network Connection                           | 10        | 0.39%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 10        | 0.39%   |
| Realtek Killer E3000 2.5GbE Controller                            | 9         | 0.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 9         | 0.35%   |
| Intel Ethernet Connection (6) I219-V                              | 9         | 0.35%   |
| Intel Ethernet Connection (16) I219-V                             | 9         | 0.35%   |
| Marvell Group 88E8058 PCI-E Gigabit Ethernet Controller           | 8         | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 2431      | 50.24%  |
| Ethernet | 2365      | 48.87%  |
| Modem    | 33        | 0.68%   |
| Unknown  | 10        | 0.21%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1894      | 61.71%  |
| Ethernet | 1174      | 38.25%  |
| Modem    | 1         | 0.03%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1603      | 55.14%  |
| 1     | 1177      | 40.49%  |
| 3     | 86        | 2.96%   |
| 0     | 34        | 1.17%   |
| 4     | 6         | 0.21%   |
| 5     | 1         | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2042      | 69.53%  |
| Yes  | 895       | 30.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1111      | 52.68%  |
| Realtek Semiconductor           | 203       | 9.63%   |
| Qualcomm Atheros Communications | 147       | 6.97%   |
| Apple                           | 129       | 6.12%   |
| IMC Networks                    | 93        | 4.41%   |
| Cambridge Silicon Radio         | 87        | 4.13%   |
| Foxconn / Hon Hai               | 75        | 3.56%   |
| Lite-On Technology              | 57        | 2.7%    |
| Broadcom                        | 48        | 2.28%   |
| MediaTek                        | 32        | 1.52%   |
| ASUSTek Computer                | 26        | 1.23%   |
| Realtek                         | 13        | 0.62%   |
| Dell                            | 13        | 0.62%   |
| Marvell Semiconductor           | 11        | 0.52%   |
| Toshiba                         | 10        | 0.47%   |
| TP-Link                         | 9         | 0.43%   |
| Hewlett-Packard                 | 7         | 0.33%   |
| Dynex                           | 6         | 0.28%   |
| Actions                         | 4         | 0.19%   |
| Ralink                          | 3         | 0.14%   |
| Opticis                         | 3         | 0.14%   |
| Micro Star International        | 3         | 0.14%   |
| Foxconn International           | 3         | 0.14%   |
| Taiyo Yuden                     | 2         | 0.09%   |
| Smart Modular Technologies      | 2         | 0.09%   |
| Ralink Technology               | 2         | 0.09%   |
| Integrated System Solution      | 2         | 0.09%   |
| Fujitsu                         | 2         | 0.09%   |
| USI                             | 1         | 0.05%   |
| SINO WEALTH                     | 1         | 0.05%   |
| Logitech                        | 1         | 0.05%   |
| HTC (High Tech Computer)        | 1         | 0.05%   |
| Edimax Technology               | 1         | 0.05%   |
| Belkin Components               | 1         | 0.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 268       | 12.7%   |
| Intel AX201 Bluetooth                               | 250       | 11.84%  |
| Intel AX200 Bluetooth                               | 227       | 10.75%  |
| Realtek Bluetooth Radio                             | 147       | 6.96%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 130       | 6.16%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 87        | 4.12%   |
| Qualcomm Atheros  Bluetooth Device                  | 83        | 3.93%   |
| Intel Bluetooth Device                              | 74        | 3.51%   |
| Apple Bluetooth USB Host Controller                 | 52        | 2.46%   |
| Apple Bluetooth Host Controller                     | 52        | 2.46%   |
| Intel AX210 Bluetooth                               | 49        | 2.32%   |
| Intel Wireless-AC 3168 Bluetooth                    | 46        | 2.18%   |
| Realtek  Bluetooth 4.2 Adapter                      | 42        | 1.99%   |
| IMC Networks Wireless_Device                        | 39        | 1.85%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 34        | 1.61%   |
| MediaTek Wireless_Device                            | 32        | 1.52%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 22        | 1.04%   |
| IMC Networks Bluetooth Radio                        | 22        | 1.04%   |
| Foxconn / Hon Hai Bluetooth Device                  | 22        | 1.04%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 20        | 0.95%   |
| Foxconn / Hon Hai Wireless_Device                   | 20        | 0.95%   |
| IMC Networks Bluetooth Device                       | 18        | 0.85%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 16        | 0.76%   |
| Lite-On Wireless_Device                             | 15        | 0.71%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 15        | 0.71%   |
| Realtek Bluetooth Radio                             | 13        | 0.62%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 12        | 0.57%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 12        | 0.57%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 12        | 0.57%   |
| Lite-On Bluetooth Device                            | 10        | 0.47%   |
| Apple Bluetooth HCI                                 | 10        | 0.47%   |
| TP-Link UB500 Adapter                               | 9         | 0.43%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 9         | 0.43%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 9         | 0.43%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 0.38%   |
| Marvell Bluetooth and Wireless LAN Composite        | 8         | 0.38%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 8         | 0.38%   |
| Lite-On Bluetooth Radio                             | 8         | 0.38%   |
| ASUS ASUS USB-BT500                                 | 8         | 0.38%   |
| Lite-On Atheros AR3012 Bluetooth                    | 7         | 0.33%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1893      | 41.95%  |
| AMD                                  | 1079      | 23.91%  |
| Nvidia                               | 910       | 20.16%  |
| C-Media Electronics                  | 77        | 1.71%   |
| Logitech                             | 50        | 1.11%   |
| Kingston Technology                  | 29        | 0.64%   |
| Razer USA                            | 25        | 0.55%   |
| JMTek                                | 24        | 0.53%   |
| ASUSTek Computer                     | 24        | 0.53%   |
| Generalplus Technology               | 22        | 0.49%   |
| Focusrite-Novation                   | 20        | 0.44%   |
| Creative Labs                        | 20        | 0.44%   |
| Micro Star International             | 19        | 0.42%   |
| SteelSeries ApS                      | 18        | 0.4%    |
| GN Netcom                            | 17        | 0.38%   |
| Lenovo                               | 16        | 0.35%   |
| Corsair                              | 14        | 0.31%   |
| Texas Instruments                    | 13        | 0.29%   |
| Realtek Semiconductor                | 13        | 0.29%   |
| Sony                                 | 12        | 0.27%   |
| Creative Technology                  | 11        | 0.24%   |
| Blue Microphones                     | 10        | 0.22%   |
| Hewlett-Packard                      | 9         | 0.2%    |
| Apple                                | 9         | 0.2%    |
| Scarlett                             | 8         | 0.18%   |
| Plantronics                          | 6         | 0.13%   |
| DSEA A/S                             | 6         | 0.13%   |
| FiiO Electronics Technology          | 5         | 0.11%   |
| Astro Gaming                         | 5         | 0.11%   |
| Thesycon Systemsoftware & Consulting | 4         | 0.09%   |
| Tenx Technology                      | 4         | 0.09%   |
| Sennheiser Communications            | 4         | 0.09%   |
| Medeli Electronics                   | 4         | 0.09%   |
| Mackie Designs                       | 4         | 0.09%   |
| M-Audio                              | 4         | 0.09%   |
| Jieli Technology                     | 4         | 0.09%   |
| Giga-Byte Technology                 | 4         | 0.09%   |
| DCMT Technology                      | 4         | 0.09%   |
| BEHRINGER International              | 4         | 0.09%   |
| Antlion Audio                        | 4         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 460       | 8.41%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 256       | 4.68%   |
| AMD Starship/Matisse HD Audio Controller                                   | 231       | 4.22%   |
| Intel Sunrise Point-LP HD Audio                                            | 212       | 3.87%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 149       | 2.72%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 143       | 2.61%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 131       | 2.39%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 129       | 2.36%   |
| Intel Cannon Lake PCH cAVS                                                 | 119       | 2.18%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 106       | 1.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 102       | 1.86%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 95        | 1.74%   |
| Nvidia GA104 High Definition Audio Controller                              | 94        | 1.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 91        | 1.66%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 79        | 1.44%   |
| Intel Broadwell-U Audio Controller                                         | 78        | 1.43%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 76        | 1.39%   |
| Intel Haswell-ULT HD Audio Controller                                      | 74        | 1.35%   |
| Intel 8 Series HD Audio Controller                                         | 73        | 1.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 72        | 1.32%   |
| Nvidia GA106 High Definition Audio Controller                              | 69        | 1.26%   |
| Nvidia TU116 High Definition Audio Controller                              | 68        | 1.24%   |
| Intel Comet Lake PCH cAVS                                                  | 68        | 1.24%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 65        | 1.19%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 64        | 1.17%   |
| Nvidia GP107GL High Definition Audio Controller                            | 62        | 1.13%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 60        | 1.1%    |
| Nvidia TU106 High Definition Audio Controller                              | 59        | 1.08%   |
| Nvidia GP104 High Definition Audio Controller                              | 58        | 1.06%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 57        | 1.04%   |
| Intel Comet Lake PCH-LP cAVS                                               | 56        | 1.02%   |
| AMD FCH Azalia Controller                                                  | 56        | 1.02%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 55        | 1.01%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 55        | 1.01%   |
| Nvidia GP106 High Definition Audio Controller                              | 54        | 0.99%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 54        | 0.99%   |
| Nvidia Audio device                                                        | 50        | 0.91%   |
| Intel 200 Series PCH HD Audio                                              | 50        | 0.91%   |
| Nvidia TU104 HD Audio Controller                                           | 44        | 0.8%    |
| Nvidia GA102 High Definition Audio Controller                              | 39        | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 237       | 25.62%  |
| SK hynix                     | 179       | 19.35%  |
| Micron Technology            | 121       | 13.08%  |
| Kingston                     | 74        | 8%      |
| Corsair                      | 63        | 6.81%   |
| Crucial                      | 55        | 5.95%   |
| G.Skill                      | 41        | 4.43%   |
| Unknown                      | 25        | 2.7%    |
| Team                         | 22        | 2.38%   |
| A-DATA Technology            | 19        | 2.05%   |
| Smart                        | 12        | 1.3%    |
| Unknown                      | 10        | 1.08%   |
| Neo Forza                    | 9         | 0.97%   |
| Unknown (ABCD)               | 8         | 0.86%   |
| Goldkey                      | 7         | 0.76%   |
| Elpida                       | 5         | 0.54%   |
| Ramaxel Technology           | 4         | 0.43%   |
| PNY                          | 4         | 0.43%   |
| Nanya Technology             | 3         | 0.32%   |
| GSkill                       | 3         | 0.32%   |
| Avant                        | 3         | 0.32%   |
| Transcend                    | 2         | 0.22%   |
| Teikon                       | 2         | 0.22%   |
| Smart Brazil                 | 2         | 0.22%   |
| Gold Key                     | 2         | 0.22%   |
| Apacer                       | 2         | 0.22%   |
| Unknown (8A02)               | 1         | 0.11%   |
| Unknown (09B6)               | 1         | 0.11%   |
| Unknown (09A4)               | 1         | 0.11%   |
| Timetec                      | 1         | 0.11%   |
| Patriot Memory (PDP Systems) | 1         | 0.11%   |
| Patriot Memory               | 1         | 0.11%   |
| Patriot                      | 1         | 0.11%   |
| Kllisre                      | 1         | 0.11%   |
| GeIL                         | 1         | 0.11%   |
| CSX                          | 1         | 0.11%   |
| ChangXin Memory              | 1         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 18        | 1.86%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 14        | 1.45%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 14        | 1.45%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 12        | 1.24%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 11        | 1.14%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 10        | 1.03%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 10        | 1.03%   |
| Unknown                                                          | 10        | 1.03%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 8         | 0.83%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s          | 8         | 0.83%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 8         | 0.83%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 7         | 0.72%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 7         | 0.72%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 7         | 0.72%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.72%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.72%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 7         | 0.72%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 7         | 0.72%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.72%   |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 6         | 0.62%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.62%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 0.62%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 6         | 0.62%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 6         | 0.62%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.62%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.62%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.62%   |
| Team RAM TEAMGROUP-SD4-3200 32GB SODIMM DDR4 3200MT/s            | 5         | 0.52%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.52%   |
| SK hynix RAM HMA81GS6CJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.52%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.52%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.52%   |
| Micron RAM MT62F1G32D4DR-031 WT 4GB Row Of Chips LPDDR5 6400MT/s | 5         | 0.52%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 5         | 0.52%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 5         | 0.52%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.52%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s           | 5         | 0.52%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 4         | 0.41%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 4         | 0.41%   |
| SK hynix RAM Module 16GB SODIMM DDR4 3200MT/s                    | 4         | 0.41%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 535       | 66.05%  |
| DDR3    | 122       | 15.06%  |
| LPDDR4  | 50        | 6.17%   |
| DDR5    | 42        | 5.19%   |
| LPDDR5  | 27        | 3.33%   |
| LPDDR3  | 22        | 2.72%   |
| DDR2    | 6         | 0.74%   |
| SDRAM   | 3         | 0.37%   |
| Unknown | 3         | 0.37%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 512       | 62.06%  |
| DIMM         | 193       | 23.39%  |
| Row Of Chips | 114       | 13.82%  |
| Chip         | 4         | 0.48%   |
| Unknown      | 2         | 0.24%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 391       | 44.99%  |
| 16384 | 198       | 22.78%  |
| 4096  | 178       | 20.48%  |
| 32768 | 61        | 7.02%   |
| 2048  | 37        | 4.26%   |
| 1024  | 4         | 0.46%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 253       | 29.28%  |
| 2667  | 139       | 16.09%  |
| 1600  | 91        | 10.53%  |
| 2400  | 53        | 6.13%   |
| 3600  | 37        | 4.28%   |
| 2133  | 35        | 4.05%   |
| 4800  | 31        | 3.59%   |
| 4267  | 29        | 3.36%   |
| 6400  | 28        | 3.24%   |
| 1333  | 14        | 1.62%   |
| 3733  | 13        | 1.5%    |
| 1867  | 12        | 1.39%   |
| 3800  | 11        | 1.27%   |
| 1334  | 9         | 1.04%   |
| 3533  | 8         | 0.93%   |
| 3266  | 8         | 0.93%   |
| 8400  | 7         | 0.81%   |
| 3000  | 7         | 0.81%   |
| 4266  | 6         | 0.69%   |
| 2933  | 6         | 0.69%   |
| 1067  | 6         | 0.69%   |
| 800   | 6         | 0.69%   |
| 6000  | 5         | 0.58%   |
| 3534  | 5         | 0.58%   |
| 3400  | 5         | 0.58%   |
| 5600  | 3         | 0.35%   |
| 3866  | 3         | 0.35%   |
| 2800  | 3         | 0.35%   |
| 5200  | 2         | 0.23%   |
| 4000  | 2         | 0.23%   |
| 3666  | 2         | 0.23%   |
| 3466  | 2         | 0.23%   |
| 3333  | 2         | 0.23%   |
| 3100  | 2         | 0.23%   |
| 2666  | 2         | 0.23%   |
| 2048  | 2         | 0.23%   |
| 1866  | 2         | 0.23%   |
| 4400  | 1         | 0.12%   |
| 4199  | 1         | 0.12%   |
| 3500  | 1         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 15        | 30.61%  |
| Brother Industries  | 9         | 18.37%  |
| Canon               | 8         | 16.33%  |
| Samsung Electronics | 6         | 12.24%  |
| Seiko Epson         | 4         | 8.16%   |
| Xerox               | 1         | 2.04%   |
| STMicroelectronics  | 1         | 2.04%   |
| QinHeng Electronics | 1         | 2.04%   |
| Prolific Technology | 1         | 2.04%   |
| ICS Advent          | 1         | 2.04%   |
| Dymo-CoStar         | 1         | 2.04%   |
| Dell                | 1         | 2.04%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Computers | Percent |
|-----------------------------------------------------------|-----------|---------|
| Brother HL-2130 series                                    | 3         | 6%      |
| Seiko Epson WF-4830 Series                                | 2         | 4%      |
| HP ENVY Pro 6400 series                                   | 2         | 4%      |
| Xerox B215                                                | 1         | 2%      |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1         | 2%      |
| Seiko Epson ME 320/330 Series [Stylus SX125]              | 1         | 2%      |
| Seiko Epson ET-2800 Series                                | 1         | 2%      |
| Samsung SCX-4500 Laser Printer                            | 1         | 2%      |
| Samsung SCX-3400 Series                                   | 1         | 2%      |
| Samsung ML-216x Series Laser Printer                      | 1         | 2%      |
| Samsung ML-191x/ML-252x Laser Printer                     | 1         | 2%      |
| Samsung M2070 Series                                      | 1         | 2%      |
| Samsung M2020 Series                                      | 1         | 2%      |
| QinHeng CH340S                                            | 1         | 2%      |
| Prolific PL2305 Parallel Port                             | 1         | 2%      |
| ICS Advent Parallel Adapter                               | 1         | 2%      |
| HP PSC-1315/PSC-1317                                      | 1         | 2%      |
| HP OfficeJet Pro 9010 series                              | 1         | 2%      |
| HP OfficeJet 3830 series                                  | 1         | 2%      |
| HP LaserJet Professional P1102w                           | 1         | 2%      |
| HP LaserJet Professional P 1102w                          | 1         | 2%      |
| HP LaserJet P2035                                         | 1         | 2%      |
| HP LaserJet 3050                                          | 1         | 2%      |
| HP LaserJet 1010                                          | 1         | 2%      |
| HP Ink Tank Wireless 410 series                           | 1         | 2%      |
| HP Ink Tank 110 series                                    | 1         | 2%      |
| HP ENVY 5000 series                                       | 1         | 2%      |
| HP DeskJet 2620 All-in-One Printer                        | 1         | 2%      |
| HP Color LaserJet CP2025dn                                | 1         | 2%      |
| Dymo-CoStar DYMO LabelWriter 4XL                          | 1         | 2%      |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                    | 1         | 2%      |
| Dell Laser Printer 1720                                   | 1         | 2%      |
| Canon TS9100 series                                       | 1         | 2%      |
| Canon TR8500 series                                       | 1         | 2%      |
| Canon TR4700 series                                       | 1         | 2%      |
| Canon Pro9000II series                                    | 1         | 2%      |
| Canon PIXMA MX920 Series                                  | 1         | 2%      |
| Canon PIXMA MP240                                         | 1         | 2%      |
| Canon PIXMA MG2500 Series                                 | 1         | 2%      |
| Canon E400 series                                         | 1         | 2%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 4         | 57.14%  |
| Seiko Epson    | 2         | 28.57%  |
| Mustek Systems | 1         | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]             | 1         | 14.29%  |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 14.29%  |
| Mustek Systems ScanExpress 1200 UB                      | 1         | 14.29%  |
| Canon CanoScan N650U/N656U                              | 1         | 14.29%  |
| Canon CanoScan LiDE 60                                  | 1         | 14.29%  |
| Canon CanoScan LiDE 200                                 | 1         | 14.29%  |
| Canon CanoScan 9000F Mark II                            | 1         | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 355       | 18.64%  |
| IMC Networks                           | 187       | 9.82%   |
| Microdia                               | 176       | 9.24%   |
| Realtek Semiconductor                  | 137       | 7.19%   |
| Logitech                               | 122       | 6.4%    |
| Bison Electronics                      | 110       | 5.77%   |
| Quanta                                 | 106       | 5.56%   |
| Apple                                  | 100       | 5.25%   |
| Sunplus Innovation Technology          | 92        | 4.83%   |
| Acer                                   | 78        | 4.09%   |
| Cheng Uei Precision Industry (Foxlink) | 49        | 2.57%   |
| Luxvisions Innotech Limited            | 48        | 2.52%   |
| Syntek                                 | 43        | 2.26%   |
| Lite-On Technology                     | 32        | 1.68%   |
| Suyin                                  | 26        | 1.36%   |
| Microsoft                              | 25        | 1.31%   |
| Sonix Technology                       | 18        | 0.94%   |
| Silicon Motion                         | 17        | 0.89%   |
| Samsung Electronics                    | 17        | 0.89%   |
| SunplusIT                              | 13        | 0.68%   |
| Razer USA                              | 10        | 0.52%   |
| Z-Star Microelectronics                | 9         | 0.47%   |
| Generalplus Technology                 | 9         | 0.47%   |
| Creative Technology                    | 7         | 0.37%   |
| Alcor Micro                            | 7         | 0.37%   |
| Ricoh                                  | 6         | 0.31%   |
| Jieli Technology                       | 6         | 0.31%   |
| MacroSilicon                           | 5         | 0.26%   |
| Lenovo                                 | 5         | 0.26%   |
| ARC International                      | 5         | 0.26%   |
| USB Camera                             | 4         | 0.21%   |
| Sunplus IT                             | 4         | 0.21%   |
| Primax Electronics                     | 4         | 0.21%   |
| LG Electronics                         | 4         | 0.21%   |
| AVerMedia Technologies                 | 4         | 0.21%   |
| Trust                                  | 3         | 0.16%   |
| Tobii Technology AB                    | 3         | 0.16%   |
| Cubeternet                             | 3         | 0.16%   |
| ALi                                    | 3         | 0.16%   |
| YGTek                                  | 2         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 81        | 4.2%    |
| Microdia Integrated_Webcam_HD                       | 78        | 4.05%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 71        | 3.68%   |
| Realtek Integrated_Webcam_HD                        | 57        | 2.96%   |
| IMC Networks Integrated Camera                      | 47        | 2.44%   |
| Syntek Integrated Camera                            | 33        | 1.71%   |
| Chicony HD Webcam                                   | 33        | 1.71%   |
| Logitech Webcam C270                                | 31        | 1.61%   |
| Bison BisonCam,NB Pro                               | 31        | 1.61%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 30        | 1.56%   |
| Apple Built-in iSight                               | 30        | 1.56%   |
| Chicony USB2.0 Camera                               | 27        | 1.4%    |
| Acer HD Webcam                                      | 25        | 1.3%    |
| Sunplus Integrated_Webcam_HD                        | 24        | 1.25%   |
| Quanta HD User Facing                               | 21        | 1.09%   |
| Apple FaceTime HD Camera (Built-in)                 | 21        | 1.09%   |
| Acer Integrated Camera                              | 21        | 1.09%   |
| Logitech HD Pro Webcam C920                         | 20        | 1.04%   |
| Quanta HP HD Camera                                 | 18        | 0.93%   |
| Chicony HD User Facing                              | 18        | 0.93%   |
| Bison Integrated Camera                             | 18        | 0.93%   |
| Samsung Galaxy A5 (MTP)                             | 17        | 0.88%   |
| Chicony HP HD Camera                                | 17        | 0.88%   |
| Apple FaceTime HD Camera                            | 17        | 0.88%   |
| Bison SunplusIT Integrated Camera                   | 15        | 0.78%   |
| Microdia Webcam Vitade AF                           | 14        | 0.73%   |
| Chicony USB2.0 VGA UVC WebCam                       | 14        | 0.73%   |
| Sonix USB2.0 HD UVC WebCam                          | 13        | 0.67%   |
| Microdia Integrated Webcam                          | 13        | 0.67%   |
| Lite-On Integrated Camera                           | 13        | 0.67%   |
| Realtek Integrated Webcam                           | 12        | 0.62%   |
| Quanta HP TrueVision HD Camera                      | 12        | 0.62%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 12        | 0.62%   |
| Logitech C922 Pro Stream Webcam                     | 12        | 0.62%   |
| Quanta HP Wide Vision HD Camera                     | 11        | 0.57%   |
| Luxvisions Innotech Limited HP HD Camera            | 11        | 0.57%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 11        | 0.57%   |
| Chicony Integrated Camera (1280x720@30)             | 11        | 0.57%   |
| Chicony HP Wide Vision HD Camera                    | 11        | 0.57%   |
| Chicony HP TrueVision HD Camera                     | 11        | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 124       | 35.23%  |
| Validity Sensors                   | 89        | 25.28%  |
| Shenzhen Goodix Technology         | 69        | 19.6%   |
| Elan Microelectronics              | 22        | 6.25%   |
| LighTuning Technology              | 14        | 3.98%   |
| Upek                               | 13        | 3.69%   |
| AuthenTec                          | 8         | 2.27%   |
| Realtek USB2.0 Finger Print Bridge | 4         | 1.14%   |
| Focal-systems.Corp                 | 4         | 1.14%   |
| HOLTEK                             | 3         | 0.85%   |
| Samsung Electronics                | 1         | 0.28%   |
| DigitalPersona                     | 1         | 0.28%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device                                        | 33        | 9.38%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 32        | 9.09%   |
| Shenzhen Goodix Fingerprint Reader                                         | 22        | 6.25%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 19        | 5.4%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 18        | 5.11%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 15        | 4.26%   |
| Shenzhen Goodix FingerPrint                                                | 14        | 3.98%   |
| Synaptics UWP WBDI                                                         | 13        | 3.69%   |
| Elan ELAN:ARM-M4                                                           | 13        | 3.69%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 11        | 3.13%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 9         | 2.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 8         | 2.27%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 8         | 2.27%   |
| Elan ELAN:Fingerprint                                                      | 8         | 2.27%   |
| Validity Sensors Synaptics WBDI                                            | 7         | 1.99%   |
| Validity Sensors Fingerprint scanner                                       | 7         | 1.99%   |
| Synaptics  WBDI                                                            | 7         | 1.99%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 7         | 1.99%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 6         | 1.7%    |
| Synaptics WBDI Device                                                      | 6         | 1.7%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.7%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.42%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 5         | 1.42%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.42%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.42%   |
| Synaptics WBDI                                                             | 5         | 1.42%   |
| Synaptics UWP WBDI Device                                                  | 5         | 1.42%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 5         | 1.42%   |
| Unknown                                                                    | 5         | 1.42%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 4         | 1.14%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 4         | 1.14%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 4         | 1.14%   |
| Validity Sensors VFS Fingerprint sensor                                    | 3         | 0.85%   |
| LighTuning Fingerprint Sensor                                              | 3         | 0.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 0.85%   |
| HOLTEK FocalTech Fingerprint Device                                        | 3         | 0.85%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 0.85%   |
| Validity Sensors VFS491                                                    | 2         | 0.57%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.57%   |
| Upek TCS5B Fingerprint sensor                                              | 2         | 0.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 55        | 48.25%  |
| Alcor Micro           | 38        | 33.33%  |
| O2 Micro              | 6         | 5.26%   |
| Lenovo                | 5         | 4.39%   |
| Upek                  | 4         | 3.51%   |
| OmniKey               | 2         | 1.75%   |
| SCM Microsystems      | 1         | 0.88%   |
| Gemalto (was Gemplus) | 1         | 0.88%   |
| Clay Logic            | 1         | 0.88%   |
| Advanced Card Systems | 1         | 0.88%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 37        | 32.46%  |
| Broadcom 58200                                                               | 17        | 14.91%  |
| Broadcom 5880                                                                | 15        | 13.16%  |
| Broadcom BCM5880 Secure Applications Processor                               | 14        | 12.28%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 7.89%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 4.39%   |
| Lenovo Integrated Smart Card Reader                                          | 5         | 4.39%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 3.51%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 0.88%   |
| OmniKey CardMan 4321                                                         | 1         | 0.88%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.88%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.88%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.88%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.88%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.88%   |
| Advanced Card Systems ACR1252 Dual Reader                                    | 1         | 0.88%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 2001      | 67.85%  |
| 1     | 768       | 26.04%  |
| 2     | 152       | 5.15%   |
| 3     | 24        | 0.81%   |
| 4     | 3         | 0.1%    |
| 6     | 1         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 340       | 30.33%  |
| Net/wireless             | 163       | 14.54%  |
| Multimedia controller    | 162       | 14.45%  |
| Graphics card            | 150       | 13.38%  |
| Chipcard                 | 107       | 9.55%   |
| Bluetooth                | 46        | 4.1%    |
| Camera                   | 39        | 3.48%   |
| Sound                    | 22        | 1.96%   |
| Unassigned class         | 18        | 1.61%   |
| Communication controller | 16        | 1.43%   |
| Net/ethernet             | 13        | 1.16%   |
| Network                  | 12        | 1.07%   |
| Storage                  | 8         | 0.71%   |
| Card reader              | 8         | 0.71%   |
| Modem                    | 5         | 0.45%   |
| Storage/ide              | 4         | 0.36%   |
| Storage/raid             | 3         | 0.27%   |
| Storage/nvme             | 3         | 0.27%   |
| Wireless                 | 1         | 0.09%   |
| Firewire controller      | 1         | 0.09%   |

