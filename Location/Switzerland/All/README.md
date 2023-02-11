Linux in Switzerland - Tested Hardware & Statistics
---------------------------------------------------

A project to collect tested hardware configurations for Linux in Switzerland.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Switzerland/Desktop/README.md) and [notebooks](/Location/Switzerland/Notebook/README.md).

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

Total: 2861

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | ZBook Studio G3             | Notebook    | [506988f4ba](https://linux-hardware.org/?probe=506988f4ba) | Jan 31, 2023 |
| Medion        | MS-7728                     | Desktop     | [60cf9e4948](https://linux-hardware.org/?probe=60cf9e4948) | Jan 31, 2023 |
| Apple         | MacBookPro14,2              | Notebook    | [ff0dfe765e](https://linux-hardware.org/?probe=ff0dfe765e) | Jan 31, 2023 |
| Acer          | Aspire A715-75G             | Notebook    | [59a0c6f08f](https://linux-hardware.org/?probe=59a0c6f08f) | Jan 30, 2023 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [fddcdb0f47](https://linux-hardware.org/?probe=fddcdb0f47) | Jan 29, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [d6faeebd74](https://linux-hardware.org/?probe=d6faeebd74) | Jan 29, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [11b07d4e11](https://linux-hardware.org/?probe=11b07d4e11) | Jan 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [933e5a5b96](https://linux-hardware.org/?probe=933e5a5b96) | Jan 29, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [a1b5cdf1db](https://linux-hardware.org/?probe=a1b5cdf1db) | Jan 28, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a88e343a83](https://linux-hardware.org/?probe=a88e343a83) | Jan 28, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [096eede9c5](https://linux-hardware.org/?probe=096eede9c5) | Jan 28, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [9d3e931cc1](https://linux-hardware.org/?probe=9d3e931cc1) | Jan 27, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [5e0dfe2630](https://linux-hardware.org/?probe=5e0dfe2630) | Jan 27, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [1d79d6f224](https://linux-hardware.org/?probe=1d79d6f224) | Jan 26, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [e4970ed713](https://linux-hardware.org/?probe=e4970ed713) | Jan 26, 2023 |
| Lenovo        | ThinkPad R61 8918DEG        | Notebook    | [c29f24d0ca](https://linux-hardware.org/?probe=c29f24d0ca) | Jan 26, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [14b3eb9a58](https://linux-hardware.org/?probe=14b3eb9a58) | Jan 25, 2023 |
| HP            | Spectre x360 2-in-1 Lapt... | Convertible | [b83c8fb5a1](https://linux-hardware.org/?probe=b83c8fb5a1) | Jan 25, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [b6afa43240](https://linux-hardware.org/?probe=b6afa43240) | Jan 24, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [141c9ffa73](https://linux-hardware.org/?probe=141c9ffa73) | Jan 24, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [e04cbf47d6](https://linux-hardware.org/?probe=e04cbf47d6) | Jan 24, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [213b4b45e5](https://linux-hardware.org/?probe=213b4b45e5) | Jan 24, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [fabda16ea6](https://linux-hardware.org/?probe=fabda16ea6) | Jan 23, 2023 |
| Dell          | XPS 13 9360                 | Notebook    | [45f94cdedc](https://linux-hardware.org/?probe=45f94cdedc) | Jan 23, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [163afb997a](https://linux-hardware.org/?probe=163afb997a) | Jan 23, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [f45af20da6](https://linux-hardware.org/?probe=f45af20da6) | Jan 23, 2023 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [50d894fc60](https://linux-hardware.org/?probe=50d894fc60) | Jan 22, 2023 |
| ASUSTek       | ROG Strix G733CX_G733CX     | Notebook    | [a02df0f932](https://linux-hardware.org/?probe=a02df0f932) | Jan 21, 2023 |
| AZW           | GTR V02                     | Desktop     | [3616feeeac](https://linux-hardware.org/?probe=3616feeeac) | Jan 21, 2023 |
| Lenovo        | MAHOBAY Win8 Pro DPK TPG    | Desktop     | [0d70d03543](https://linux-hardware.org/?probe=0d70d03543) | Jan 21, 2023 |
| Medion        | MS-7728                     | Desktop     | [93d0aaac10](https://linux-hardware.org/?probe=93d0aaac10) | Jan 21, 2023 |
| Medion        | MS-7728                     | Desktop     | [eb9cef403c](https://linux-hardware.org/?probe=eb9cef403c) | Jan 21, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [0192877edc](https://linux-hardware.org/?probe=0192877edc) | Jan 20, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [69f4adcf81](https://linux-hardware.org/?probe=69f4adcf81) | Jan 20, 2023 |
| Lenovo        | Z710 20250                  | Notebook    | [f59ce535eb](https://linux-hardware.org/?probe=f59ce535eb) | Jan 20, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [873a521bf5](https://linux-hardware.org/?probe=873a521bf5) | Jan 19, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [bf7bab9d7c](https://linux-hardware.org/?probe=bf7bab9d7c) | Jan 19, 2023 |
| ASRock        | Z370 Pro4                   | Desktop     | [e05b7e7729](https://linux-hardware.org/?probe=e05b7e7729) | Jan 19, 2023 |
| Lenovo        | ThinkPad T470s 20HGS36U0... | Notebook    | [37fd07b937](https://linux-hardware.org/?probe=37fd07b937) | Jan 18, 2023 |
| Medion        | MS-7728                     | Desktop     | [b5e3ddf859](https://linux-hardware.org/?probe=b5e3ddf859) | Jan 18, 2023 |
| Acer          | Veriton M2110G              | Desktop     | [7097a3cf90](https://linux-hardware.org/?probe=7097a3cf90) | Jan 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [6dab459ed2](https://linux-hardware.org/?probe=6dab459ed2) | Jan 18, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [430b938694](https://linux-hardware.org/?probe=430b938694) | Jan 18, 2023 |
| HP            | EliteBook 2170p             | Notebook    | [46705d578e](https://linux-hardware.org/?probe=46705d578e) | Jan 18, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [952c81c314](https://linux-hardware.org/?probe=952c81c314) | Jan 18, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [b4e1da9857](https://linux-hardware.org/?probe=b4e1da9857) | Jan 17, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [80f8925010](https://linux-hardware.org/?probe=80f8925010) | Jan 17, 2023 |
| Acer          | Aspire M5910                | Desktop     | [d2d4e86b49](https://linux-hardware.org/?probe=d2d4e86b49) | Jan 17, 2023 |
| Lenovo        | B50-10 80QR                 | Notebook    | [e5903bfd98](https://linux-hardware.org/?probe=e5903bfd98) | Jan 17, 2023 |
| HP            | 212B                        | Desktop     | [00822b2263](https://linux-hardware.org/?probe=00822b2263) | Jan 16, 2023 |
| Medion        | MS-7728                     | Desktop     | [5168c2f916](https://linux-hardware.org/?probe=5168c2f916) | Jan 16, 2023 |
| HP            | ProBook 650 G4              | Notebook    | [340bddf38d](https://linux-hardware.org/?probe=340bddf38d) | Jan 16, 2023 |
| HP            | EliteBook 2560p             | Notebook    | [7d0cedda95](https://linux-hardware.org/?probe=7d0cedda95) | Jan 15, 2023 |
| Lenovo        | ThinkPad X1 Titanium Gen... | Convertible | [ca74e79834](https://linux-hardware.org/?probe=ca74e79834) | Jan 15, 2023 |
| AZW           | GTR V02                     | Desktop     | [074c3ab42f](https://linux-hardware.org/?probe=074c3ab42f) | Jan 14, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [1f30a57359](https://linux-hardware.org/?probe=1f30a57359) | Jan 14, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [ebb69311f7](https://linux-hardware.org/?probe=ebb69311f7) | Jan 14, 2023 |
| Lenovo        | ThinkPad L390 Yoga 20NTC... | Convertible | [03e4d52b2d](https://linux-hardware.org/?probe=03e4d52b2d) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [182eb9ffa1](https://linux-hardware.org/?probe=182eb9ffa1) | Jan 12, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [f84f79fce7](https://linux-hardware.org/?probe=f84f79fce7) | Jan 11, 2023 |
| ELSKY         | QM10u                       | Desktop     | [c9bde314b5](https://linux-hardware.org/?probe=c9bde314b5) | Jan 11, 2023 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [d014e736fc](https://linux-hardware.org/?probe=d014e736fc) | Jan 11, 2023 |
| Dell          | Latitude 9420               | Convertible | [1446885eb7](https://linux-hardware.org/?probe=1446885eb7) | Jan 11, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [9a7b0b9f2e](https://linux-hardware.org/?probe=9a7b0b9f2e) | Jan 10, 2023 |
| Medion        | MS-7728                     | Desktop     | [8310cf0974](https://linux-hardware.org/?probe=8310cf0974) | Jan 10, 2023 |
| HP            | 3048h                       | Desktop     | [e13a2bdf6e](https://linux-hardware.org/?probe=e13a2bdf6e) | Jan 10, 2023 |
| HP            | 158A                        | Desktop     | [c0e1c9b6e6](https://linux-hardware.org/?probe=c0e1c9b6e6) | Jan 09, 2023 |
| Acer          | Aspire E5-511               | Notebook    | [e16bac2828](https://linux-hardware.org/?probe=e16bac2828) | Jan 09, 2023 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [d665a7f0ff](https://linux-hardware.org/?probe=d665a7f0ff) | Jan 09, 2023 |
| AZW           | GTR V02                     | Desktop     | [b7a911ab61](https://linux-hardware.org/?probe=b7a911ab61) | Jan 09, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CR... | Notebook    | [ff783dac11](https://linux-hardware.org/?probe=ff783dac11) | Jan 08, 2023 |
| Acer          | Aspire V3-772G              | Notebook    | [bd0adf87e3](https://linux-hardware.org/?probe=bd0adf87e3) | Jan 08, 2023 |
| ASUSTek       | K53U                        | Notebook    | [63849b1b5a](https://linux-hardware.org/?probe=63849b1b5a) | Jan 08, 2023 |
| Alienware     | 17 R3                       | Notebook    | [f94b2fc95f](https://linux-hardware.org/?probe=f94b2fc95f) | Jan 08, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [97335b8723](https://linux-hardware.org/?probe=97335b8723) | Jan 07, 2023 |
| Lenovo        | 3733 SDK0T76461 WIN 3422... | Desktop     | [ac69fa3d31](https://linux-hardware.org/?probe=ac69fa3d31) | Jan 07, 2023 |
| ASUSTek       | P8H77-M PRO                 | Desktop     | [03524fa074](https://linux-hardware.org/?probe=03524fa074) | Jan 07, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [7281c172f4](https://linux-hardware.org/?probe=7281c172f4) | Jan 06, 2023 |
| MSI           | IONA                        | Desktop     | [8e49c8c0b1](https://linux-hardware.org/?probe=8e49c8c0b1) | Jan 06, 2023 |
| MSI           | IONA                        | Desktop     | [ca8adec17c](https://linux-hardware.org/?probe=ca8adec17c) | Jan 06, 2023 |
| Medion        | MS-7728                     | Desktop     | [4b3e96394b](https://linux-hardware.org/?probe=4b3e96394b) | Jan 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [9b0a8d487e](https://linux-hardware.org/?probe=9b0a8d487e) | Jan 06, 2023 |
| Lenovo        | ThinkPad T470s 20HF0016M... | Notebook    | [b48981da6d](https://linux-hardware.org/?probe=b48981da6d) | Jan 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b329d8f40f](https://linux-hardware.org/?probe=b329d8f40f) | Jan 06, 2023 |
| Acer          | Predator G9-591             | Notebook    | [160b31ea8f](https://linux-hardware.org/?probe=160b31ea8f) | Jan 06, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [0b9972387e](https://linux-hardware.org/?probe=0b9972387e) | Jan 05, 2023 |
| Medion        | MS-7728                     | Desktop     | [0ffef4911e](https://linux-hardware.org/?probe=0ffef4911e) | Jan 05, 2023 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [583ea447a9](https://linux-hardware.org/?probe=583ea447a9) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8f519746c2](https://linux-hardware.org/?probe=8f519746c2) | Jan 04, 2023 |
| Medion        | MS-7728                     | Desktop     | [9c2439adf6](https://linux-hardware.org/?probe=9c2439adf6) | Jan 04, 2023 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [518b2272d4](https://linux-hardware.org/?probe=518b2272d4) | Jan 04, 2023 |
| PC Special... | NH5x_7xRCx,RDx              | Notebook    | [0941a9c7a2](https://linux-hardware.org/?probe=0941a9c7a2) | Jan 04, 2023 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [b341980e6c](https://linux-hardware.org/?probe=b341980e6c) | Jan 04, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d50cf83414](https://linux-hardware.org/?probe=d50cf83414) | Jan 04, 2023 |
| MSI           | Katana GF66 11SC            | Notebook    | [5a078a161f](https://linux-hardware.org/?probe=5a078a161f) | Jan 03, 2023 |
| Lenovo        | ThinkPad T530 24296FG       | Notebook    | [303cb1bd6f](https://linux-hardware.org/?probe=303cb1bd6f) | Jan 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [8c9e803e01](https://linux-hardware.org/?probe=8c9e803e01) | Jan 01, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [cc24dc6f72](https://linux-hardware.org/?probe=cc24dc6f72) | Dec 31, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [bf3922e95d](https://linux-hardware.org/?probe=bf3922e95d) | Dec 31, 2022 |
| Valve         | Jupiter                     | Notebook    | [82b86d954a](https://linux-hardware.org/?probe=82b86d954a) | Dec 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1JN0... | Notebook    | [049bc54496](https://linux-hardware.org/?probe=049bc54496) | Dec 30, 2022 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [29bca2b322](https://linux-hardware.org/?probe=29bca2b322) | Dec 29, 2022 |
| Lenovo        | ThinkPad X240 20AL007AMZ    | Notebook    | [bcb9b7a061](https://linux-hardware.org/?probe=bcb9b7a061) | Dec 29, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [71168d8107](https://linux-hardware.org/?probe=71168d8107) | Dec 29, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [a73fe5e678](https://linux-hardware.org/?probe=a73fe5e678) | Dec 28, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [538bf2bb33](https://linux-hardware.org/?probe=538bf2bb33) | Dec 28, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [b8ad48c33c](https://linux-hardware.org/?probe=b8ad48c33c) | Dec 26, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [77ee14ad98](https://linux-hardware.org/?probe=77ee14ad98) | Dec 26, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [1c022f7ff8](https://linux-hardware.org/?probe=1c022f7ff8) | Dec 26, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [8762b5f41f](https://linux-hardware.org/?probe=8762b5f41f) | Dec 25, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [803a4e58e0](https://linux-hardware.org/?probe=803a4e58e0) | Dec 25, 2022 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [b445490856](https://linux-hardware.org/?probe=b445490856) | Dec 25, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [f47d3ce638](https://linux-hardware.org/?probe=f47d3ce638) | Dec 24, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [2d50f93c7f](https://linux-hardware.org/?probe=2d50f93c7f) | Dec 22, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [dac438be55](https://linux-hardware.org/?probe=dac438be55) | Dec 22, 2022 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [3f3c7b0e92](https://linux-hardware.org/?probe=3f3c7b0e92) | Dec 22, 2022 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [e160bf6ea0](https://linux-hardware.org/?probe=e160bf6ea0) | Dec 22, 2022 |
| Dell          | Inspiron 15 3511            | Notebook    | [e7bf0c0a09](https://linux-hardware.org/?probe=e7bf0c0a09) | Dec 21, 2022 |
| Notebook      | NL5xRU                      | Notebook    | [c32538c73b](https://linux-hardware.org/?probe=c32538c73b) | Dec 21, 2022 |
| CompuLab      | Intense-PC                  | Mini pc     | [907ca44afe](https://linux-hardware.org/?probe=907ca44afe) | Dec 21, 2022 |
| Lenovo        | Yoga Slim 7 Pro 16ACH6 8... | Notebook    | [b6252c3e0e](https://linux-hardware.org/?probe=b6252c3e0e) | Dec 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW11    | Notebook    | [9fca55febc](https://linux-hardware.org/?probe=9fca55febc) | Dec 19, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [47397487a7](https://linux-hardware.org/?probe=47397487a7) | Dec 19, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [e954c9ca37](https://linux-hardware.org/?probe=e954c9ca37) | Dec 19, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW11    | Notebook    | [57605a26eb](https://linux-hardware.org/?probe=57605a26eb) | Dec 19, 2022 |
| ASUSTek       | PN64                        | Mini pc     | [a5fdbdb0c8](https://linux-hardware.org/?probe=a5fdbdb0c8) | Dec 19, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [3a6e0b953f](https://linux-hardware.org/?probe=3a6e0b953f) | Dec 19, 2022 |
| Notebook      | PC5x_7xHP_HR_HS             | Notebook    | [7a528ca531](https://linux-hardware.org/?probe=7a528ca531) | Dec 17, 2022 |
| Acer          | Aspire E5-773               | Notebook    | [d8d1898a3b](https://linux-hardware.org/?probe=d8d1898a3b) | Dec 17, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [86627d739c](https://linux-hardware.org/?probe=86627d739c) | Dec 16, 2022 |
| Lenovo        | ThinkPad E15 20RD0011MZ     | Notebook    | [ee758acf19](https://linux-hardware.org/?probe=ee758acf19) | Dec 16, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [13ee187e45](https://linux-hardware.org/?probe=13ee187e45) | Dec 15, 2022 |
| HP            | Compaq 6830s                | Notebook    | [1883df2312](https://linux-hardware.org/?probe=1883df2312) | Dec 14, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [1129626fee](https://linux-hardware.org/?probe=1129626fee) | Dec 13, 2022 |
| Acer          | Aspire 7750                 | Notebook    | [9f0f4a8510](https://linux-hardware.org/?probe=9f0f4a8510) | Dec 12, 2022 |
| Acer          | Aspire 7750                 | Notebook    | [f7577f248a](https://linux-hardware.org/?probe=f7577f248a) | Dec 12, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [787ba0950d](https://linux-hardware.org/?probe=787ba0950d) | Dec 11, 2022 |
| Gigabyte      | P67A-D3-B3                  | Desktop     | [9ed715edc4](https://linux-hardware.org/?probe=9ed715edc4) | Dec 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3282a529f0](https://linux-hardware.org/?probe=3282a529f0) | Dec 11, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | Desktop     | [6c26c9ff8c](https://linux-hardware.org/?probe=6c26c9ff8c) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [d53608f3e3](https://linux-hardware.org/?probe=d53608f3e3) | Dec 10, 2022 |
| Lenovo        | ThinkPad T480s 20L7CTO1W... | Notebook    | [b524e6fd67](https://linux-hardware.org/?probe=b524e6fd67) | Dec 09, 2022 |
| Acer          | Swift SF314-511             | Notebook    | [c3c6c2f4fc](https://linux-hardware.org/?probe=c3c6c2f4fc) | Dec 09, 2022 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [945412b0cc](https://linux-hardware.org/?probe=945412b0cc) | Dec 09, 2022 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [474cde3412](https://linux-hardware.org/?probe=474cde3412) | Dec 08, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [62986b3426](https://linux-hardware.org/?probe=62986b3426) | Dec 08, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [637056cc12](https://linux-hardware.org/?probe=637056cc12) | Dec 08, 2022 |
| Lenovo        | ThinkPad E490 20N8000UMZ    | Notebook    | [15ca126de2](https://linux-hardware.org/?probe=15ca126de2) | Dec 08, 2022 |
| Lenovo        | ThinkPad E490 20N8000UMZ    | Notebook    | [eef6c9c624](https://linux-hardware.org/?probe=eef6c9c624) | Dec 08, 2022 |
| BESSTAR Te... | B550                        | Desktop     | [5471ce4bdc](https://linux-hardware.org/?probe=5471ce4bdc) | Dec 07, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [31ae5769eb](https://linux-hardware.org/?probe=31ae5769eb) | Dec 07, 2022 |
| CompuLab      | Intense-PC                  | Mini pc     | [439e89b31f](https://linux-hardware.org/?probe=439e89b31f) | Dec 07, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [f2ba8a7d55](https://linux-hardware.org/?probe=f2ba8a7d55) | Dec 06, 2022 |
| Dell          | 0HN7XN A00                  | Desktop     | [927991f54f](https://linux-hardware.org/?probe=927991f54f) | Dec 06, 2022 |
| Gigabyte      | Z690 AORUS PRO              | Desktop     | [ee9c9e919b](https://linux-hardware.org/?probe=ee9c9e919b) | Dec 05, 2022 |
| HP            | ENVY dv7                    | Notebook    | [8e8b9ecfb6](https://linux-hardware.org/?probe=8e8b9ecfb6) | Dec 04, 2022 |
| ASUSTek       | Maximus VII RANGER          | Desktop     | [9a0718a60f](https://linux-hardware.org/?probe=9a0718a60f) | Dec 04, 2022 |
| ASUSTek       | GL702ZC                     | Notebook    | [de8b2bcfab](https://linux-hardware.org/?probe=de8b2bcfab) | Dec 03, 2022 |
| GPD           | P2 MAX                      | Notebook    | [dce4c87de8](https://linux-hardware.org/?probe=dce4c87de8) | Dec 03, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [4568e83912](https://linux-hardware.org/?probe=4568e83912) | Dec 03, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [2047a872cb](https://linux-hardware.org/?probe=2047a872cb) | Dec 03, 2022 |
| Dell          | XPS 15 9520                 | Notebook    | [b6cf92da13](https://linux-hardware.org/?probe=b6cf92da13) | Dec 02, 2022 |
| Acer          | Predator PH317-56           | Notebook    | [ea1d794b18](https://linux-hardware.org/?probe=ea1d794b18) | Dec 02, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [19395b5e21](https://linux-hardware.org/?probe=19395b5e21) | Dec 02, 2022 |
| HP            | ProBook 6560b               | Notebook    | [c62ff16666](https://linux-hardware.org/?probe=c62ff16666) | Dec 02, 2022 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [13b2f864f8](https://linux-hardware.org/?probe=13b2f864f8) | Dec 02, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [8e0ea55ccc](https://linux-hardware.org/?probe=8e0ea55ccc) | Dec 02, 2022 |
| ASUSTek       | X556UAK                     | Notebook    | [7817399ec6](https://linux-hardware.org/?probe=7817399ec6) | Dec 02, 2022 |
| HP            | ENVY dv7                    | Notebook    | [60e3263ce2](https://linux-hardware.org/?probe=60e3263ce2) | Dec 01, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [a37f48c68a](https://linux-hardware.org/?probe=a37f48c68a) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [3ee313dd51](https://linux-hardware.org/?probe=3ee313dd51) | Dec 01, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [fde8194d5c](https://linux-hardware.org/?probe=fde8194d5c) | Dec 01, 2022 |
| HP            | ENVY dv7                    | Notebook    | [1cef09f19a](https://linux-hardware.org/?probe=1cef09f19a) | Dec 01, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [3e67e44d23](https://linux-hardware.org/?probe=3e67e44d23) | Nov 30, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [8d98938198](https://linux-hardware.org/?probe=8d98938198) | Nov 30, 2022 |
| Dell          | 0Y2G81 A01                  | Server      | [7ce42afb90](https://linux-hardware.org/?probe=7ce42afb90) | Nov 30, 2022 |
| HP            | Pavilion dv9000 (RP919EA... | Notebook    | [dcdd31c3d5](https://linux-hardware.org/?probe=dcdd31c3d5) | Nov 30, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [d233ee2114](https://linux-hardware.org/?probe=d233ee2114) | Nov 30, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [8d37e3e327](https://linux-hardware.org/?probe=8d37e3e327) | Nov 29, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [e41751f26a](https://linux-hardware.org/?probe=e41751f26a) | Nov 29, 2022 |
| Notebook      | L140PU                      | Notebook    | [8893420e06](https://linux-hardware.org/?probe=8893420e06) | Nov 28, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [d353a1624b](https://linux-hardware.org/?probe=d353a1624b) | Nov 28, 2022 |
| Pegatron      | VIOLET                      | Desktop     | [f0f25e6854](https://linux-hardware.org/?probe=f0f25e6854) | Nov 28, 2022 |
| Dell          | Latitude E6420              | Notebook    | [15ee6e2e20](https://linux-hardware.org/?probe=15ee6e2e20) | Nov 28, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [4cec4d0e04](https://linux-hardware.org/?probe=4cec4d0e04) | Nov 27, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [8e266a1137](https://linux-hardware.org/?probe=8e266a1137) | Nov 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [3ba26453f1](https://linux-hardware.org/?probe=3ba26453f1) | Nov 24, 2022 |
| Nvidia        | Tegra                       | Soc         | [b565b4082e](https://linux-hardware.org/?probe=b565b4082e) | Nov 24, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [90f931841d](https://linux-hardware.org/?probe=90f931841d) | Nov 23, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [111f6a1fc2](https://linux-hardware.org/?probe=111f6a1fc2) | Nov 23, 2022 |
| Fujitsu       | D3348-B2 S26361-D3348-B2    | Desktop     | [eabfad66da](https://linux-hardware.org/?probe=eabfad66da) | Nov 22, 2022 |
| Lenovo        | ThinkPad T450 20BUS08L00    | Notebook    | [080bbeb75a](https://linux-hardware.org/?probe=080bbeb75a) | Nov 22, 2022 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [b5ed1b189a](https://linux-hardware.org/?probe=b5ed1b189a) | Nov 22, 2022 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [54f10b9d0b](https://linux-hardware.org/?probe=54f10b9d0b) | Nov 21, 2022 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [576ca67a28](https://linux-hardware.org/?probe=576ca67a28) | Nov 21, 2022 |
| Lenovo        | ThinkPad P52 20M90017MX     | Notebook    | [65c874adbd](https://linux-hardware.org/?probe=65c874adbd) | Nov 20, 2022 |
| ASUSTek       | P7H55-M PRO                 | Desktop     | [b25dd25478](https://linux-hardware.org/?probe=b25dd25478) | Nov 20, 2022 |
| Dell          | XPS 9320                    | Notebook    | [e590d602a9](https://linux-hardware.org/?probe=e590d602a9) | Nov 19, 2022 |
| HP            | 212B                        | Desktop     | [574a94ad86](https://linux-hardware.org/?probe=574a94ad86) | Nov 18, 2022 |
| HP            | 212B                        | Desktop     | [3995268826](https://linux-hardware.org/?probe=3995268826) | Nov 18, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX450FD... | Notebook    | [27084d9125](https://linux-hardware.org/?probe=27084d9125) | Nov 17, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [871be7733f](https://linux-hardware.org/?probe=871be7733f) | Nov 17, 2022 |
| MPMAN         | CONVERTER8                  | Notebook    | [0c8f7446f7](https://linux-hardware.org/?probe=0c8f7446f7) | Nov 17, 2022 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [b3e809f3d2](https://linux-hardware.org/?probe=b3e809f3d2) | Nov 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [6f2f504425](https://linux-hardware.org/?probe=6f2f504425) | Nov 16, 2022 |
| Lenovo        | ThinkPad Edge 03192AG       | Notebook    | [48da1b11bc](https://linux-hardware.org/?probe=48da1b11bc) | Nov 16, 2022 |
| HP            | Compaq 15                   | Notebook    | [d437023699](https://linux-hardware.org/?probe=d437023699) | Nov 16, 2022 |
| GPD           | G1619-04                    | Notebook    | [c1e365fd5d](https://linux-hardware.org/?probe=c1e365fd5d) | Nov 16, 2022 |
| Clevo         | W240EU/W250EUQ/W270EUQ      | Notebook    | [71a871168d](https://linux-hardware.org/?probe=71a871168d) | Nov 15, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [aabc2148da](https://linux-hardware.org/?probe=aabc2148da) | Nov 15, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c6c7120833](https://linux-hardware.org/?probe=c6c7120833) | Nov 15, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [5682e576ad](https://linux-hardware.org/?probe=5682e576ad) | Nov 14, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [2053688baa](https://linux-hardware.org/?probe=2053688baa) | Nov 14, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [15f6c6a1aa](https://linux-hardware.org/?probe=15f6c6a1aa) | Nov 14, 2022 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [3726e23d23](https://linux-hardware.org/?probe=3726e23d23) | Nov 14, 2022 |
| Alienware     | 07W25T A00                  | Desktop     | [f320cc2659](https://linux-hardware.org/?probe=f320cc2659) | Nov 11, 2022 |
| Acer          | Spin SP313-51N              | Convertible | [d2e25c9c4e](https://linux-hardware.org/?probe=d2e25c9c4e) | Nov 10, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [d7a20bdac6](https://linux-hardware.org/?probe=d7a20bdac6) | Nov 09, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [33a4a1ea9a](https://linux-hardware.org/?probe=33a4a1ea9a) | Nov 09, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [581ff62688](https://linux-hardware.org/?probe=581ff62688) | Nov 07, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [a0a7ef6e3a](https://linux-hardware.org/?probe=a0a7ef6e3a) | Nov 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [ff7014b9b8](https://linux-hardware.org/?probe=ff7014b9b8) | Nov 06, 2022 |
| Apple         | MacBookPro4,1               | Notebook    | [69c1a004e6](https://linux-hardware.org/?probe=69c1a004e6) | Nov 03, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [9224a599b3](https://linux-hardware.org/?probe=9224a599b3) | Nov 03, 2022 |
| HP            | 8458                        | Mini pc     | [4da864256d](https://linux-hardware.org/?probe=4da864256d) | Nov 03, 2022 |
| ASUSTek       | Z590 WIFI GUNDAM EDITION    | Desktop     | [74f8de9f71](https://linux-hardware.org/?probe=74f8de9f71) | Nov 02, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [fd4d484f61](https://linux-hardware.org/?probe=fd4d484f61) | Nov 02, 2022 |
| Dell          | Precision 5520              | Notebook    | [e1a819ec3e](https://linux-hardware.org/?probe=e1a819ec3e) | Nov 01, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [e101d9d50a](https://linux-hardware.org/?probe=e101d9d50a) | Nov 01, 2022 |
| GPD           | G1619-04                    | Notebook    | [898bbfb591](https://linux-hardware.org/?probe=898bbfb591) | Nov 01, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [a75bc2ff26](https://linux-hardware.org/?probe=a75bc2ff26) | Oct 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [1e1f105579](https://linux-hardware.org/?probe=1e1f105579) | Oct 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [19cddcf899](https://linux-hardware.org/?probe=19cddcf899) | Oct 30, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [a4eebe6485](https://linux-hardware.org/?probe=a4eebe6485) | Oct 30, 2022 |
| Lenovo        | ThinkPad T470s 20HGS2W30... | Notebook    | [8e0c00531b](https://linux-hardware.org/?probe=8e0c00531b) | Oct 29, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [6047d5d94a](https://linux-hardware.org/?probe=6047d5d94a) | Oct 29, 2022 |
| ASUSTek       | K55VJ                       | Notebook    | [6dc11e517b](https://linux-hardware.org/?probe=6dc11e517b) | Oct 29, 2022 |
| Dell          | Latitude E4310              | Notebook    | [fe6c65dd77](https://linux-hardware.org/?probe=fe6c65dd77) | Oct 29, 2022 |
| Dell          | Latitude E4310              | Notebook    | [7a610ca46d](https://linux-hardware.org/?probe=7a610ca46d) | Oct 29, 2022 |
| HP            | ProBook 6570b               | Notebook    | [b5d48f6adb](https://linux-hardware.org/?probe=b5d48f6adb) | Oct 29, 2022 |
| Lenovo        | ThinkPad T420 4236NUG       | Notebook    | [d0e3fa9699](https://linux-hardware.org/?probe=d0e3fa9699) | Oct 28, 2022 |
| HP            | 3396                        | Desktop     | [d42479acb8](https://linux-hardware.org/?probe=d42479acb8) | Oct 28, 2022 |
| ZOTAC         | ZBOX-EN72080V/EN72070V/E... | Mini pc     | [9a540d96f5](https://linux-hardware.org/?probe=9a540d96f5) | Oct 27, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c55b37c393](https://linux-hardware.org/?probe=c55b37c393) | Oct 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [c3bbb31b04](https://linux-hardware.org/?probe=c3bbb31b04) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [85510879a5](https://linux-hardware.org/?probe=85510879a5) | Oct 24, 2022 |
| ASUSTek       | N750JK                      | Notebook    | [849800f3f3](https://linux-hardware.org/?probe=849800f3f3) | Oct 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [c16378c914](https://linux-hardware.org/?probe=c16378c914) | Oct 23, 2022 |
| Acer          | WG43M                       | Desktop     | [e520a7dfca](https://linux-hardware.org/?probe=e520a7dfca) | Oct 22, 2022 |
| Lenovo        | ThinkPad T480 20L50004MZ    | Notebook    | [7fe25296ef](https://linux-hardware.org/?probe=7fe25296ef) | Oct 21, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [b81dd63334](https://linux-hardware.org/?probe=b81dd63334) | Oct 21, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [55a46537f8](https://linux-hardware.org/?probe=55a46537f8) | Oct 21, 2022 |
| Medion        | S15449                      | Notebook    | [c737a8be4a](https://linux-hardware.org/?probe=c737a8be4a) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a83d0f0ade](https://linux-hardware.org/?probe=a83d0f0ade) | Oct 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [f5073cd7a2](https://linux-hardware.org/?probe=f5073cd7a2) | Oct 20, 2022 |
| HP            | 829A                        | Mini pc     | [3470bd9a76](https://linux-hardware.org/?probe=3470bd9a76) | Oct 17, 2022 |
| HP            | 829A                        | Mini pc     | [3ab01040ef](https://linux-hardware.org/?probe=3ab01040ef) | Oct 17, 2022 |
| MSI           | H170I PRO AC                | Desktop     | [ea4ecf6238](https://linux-hardware.org/?probe=ea4ecf6238) | Oct 17, 2022 |
| ASUSTek       | ZenBook 13 UX331FAL_UX33... | Notebook    | [3e8ca06ac6](https://linux-hardware.org/?probe=3e8ca06ac6) | Oct 17, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [8bd50f112b](https://linux-hardware.org/?probe=8bd50f112b) | Oct 15, 2022 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [88497baf29](https://linux-hardware.org/?probe=88497baf29) | Oct 15, 2022 |
| Apple         | Mac-FFE5EF870D7BA81A iMa... | All in one  | [5d60b980ca](https://linux-hardware.org/?probe=5d60b980ca) | Oct 15, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [1993500f68](https://linux-hardware.org/?probe=1993500f68) | Oct 15, 2022 |
| ASUSTek       | PN41                        | Mini pc     | [3498692f6e](https://linux-hardware.org/?probe=3498692f6e) | Oct 15, 2022 |
| Google        | Lars                        | Notebook    | [b607a23c77](https://linux-hardware.org/?probe=b607a23c77) | Oct 14, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | Notebook    | [b02e3ede3f](https://linux-hardware.org/?probe=b02e3ede3f) | Oct 14, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | Notebook    | [33efe8c37a](https://linux-hardware.org/?probe=33efe8c37a) | Oct 14, 2022 |
| HP            | ENVY 15                     | Notebook    | [71c0056a73](https://linux-hardware.org/?probe=71c0056a73) | Oct 13, 2022 |
| Acer          | Aspire 7250G                | Notebook    | [34966259d6](https://linux-hardware.org/?probe=34966259d6) | Oct 13, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [9d2cf83f81](https://linux-hardware.org/?probe=9d2cf83f81) | Oct 12, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [feb997ebfc](https://linux-hardware.org/?probe=feb997ebfc) | Oct 12, 2022 |
| HP            | ENVY Laptop 17-cr0xxx       | Notebook    | [67532c45cb](https://linux-hardware.org/?probe=67532c45cb) | Oct 12, 2022 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [5112d236ce](https://linux-hardware.org/?probe=5112d236ce) | Oct 12, 2022 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [10e153f71e](https://linux-hardware.org/?probe=10e153f71e) | Oct 10, 2022 |
| Chuwi         | RZBOX                       | Desktop     | [76b6d7cd78](https://linux-hardware.org/?probe=76b6d7cd78) | Oct 08, 2022 |
| Samsung       | RC530/RC730                 | Notebook    | [ee62bfc634](https://linux-hardware.org/?probe=ee62bfc634) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [ff847da23a](https://linux-hardware.org/?probe=ff847da23a) | Oct 07, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [fceffec337](https://linux-hardware.org/?probe=fceffec337) | Oct 07, 2022 |
| Notebook      | W65_67SZ                    | Notebook    | [a3a056691b](https://linux-hardware.org/?probe=a3a056691b) | Oct 07, 2022 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [7f03ff4490](https://linux-hardware.org/?probe=7f03ff4490) | Oct 07, 2022 |
| Gigabyte      | RC14UD                      | Notebook    | [e48bdade3d](https://linux-hardware.org/?probe=e48bdade3d) | Oct 06, 2022 |
| Dell          | Latitude E6410              | Notebook    | [f7baa71813](https://linux-hardware.org/?probe=f7baa71813) | Oct 05, 2022 |
| Dell          | 0T656F A01                  | Desktop     | [24da875cf7](https://linux-hardware.org/?probe=24da875cf7) | Oct 04, 2022 |
| HP            | 213D A01                    | Desktop     | [e81fd5fea5](https://linux-hardware.org/?probe=e81fd5fea5) | Oct 04, 2022 |
| HP            | ProBook 640 G2              | Notebook    | [e4cc03e802](https://linux-hardware.org/?probe=e4cc03e802) | Oct 03, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [6a5067b548](https://linux-hardware.org/?probe=6a5067b548) | Oct 02, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [2044c11c98](https://linux-hardware.org/?probe=2044c11c98) | Oct 02, 2022 |
| ASUSTek       | K55VJ                       | Notebook    | [e405dee0bd](https://linux-hardware.org/?probe=e405dee0bd) | Oct 02, 2022 |
| MSI           | 2A9C                        | Desktop     | [a933ad6bca](https://linux-hardware.org/?probe=a933ad6bca) | Oct 01, 2022 |
| Pegatron      | IPMSB-GS                    | Desktop     | [5e38213b3b](https://linux-hardware.org/?probe=5e38213b3b) | Sep 30, 2022 |
| Gigabyte      | RC14UD                      | Notebook    | [744143bdd6](https://linux-hardware.org/?probe=744143bdd6) | Sep 30, 2022 |
| Acer          | Spin SP111-32N              | Convertible | [6c3ab0f793](https://linux-hardware.org/?probe=6c3ab0f793) | Sep 27, 2022 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [9a1514cc61](https://linux-hardware.org/?probe=9a1514cc61) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [41cc3cdcfd](https://linux-hardware.org/?probe=41cc3cdcfd) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [d6924eb78d](https://linux-hardware.org/?probe=d6924eb78d) | Sep 26, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [3c87156766](https://linux-hardware.org/?probe=3c87156766) | Sep 25, 2022 |
| Lenovo        | Yoga S730-13IWL 81J0        | Notebook    | [fee2b2d57e](https://linux-hardware.org/?probe=fee2b2d57e) | Sep 24, 2022 |
| Packard Be... | IMEDIA S1300                | Desktop     | [13b1f0e28e](https://linux-hardware.org/?probe=13b1f0e28e) | Sep 24, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6f492f55c3](https://linux-hardware.org/?probe=6f492f55c3) | Sep 24, 2022 |
| Acer          | Spin SP111-32N              | Convertible | [75ed13ea90](https://linux-hardware.org/?probe=75ed13ea90) | Sep 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Convertible | [f9c071cdd8](https://linux-hardware.org/?probe=f9c071cdd8) | Sep 23, 2022 |
| System76      | Darter Pro                  | Notebook    | [012968a4a3](https://linux-hardware.org/?probe=012968a4a3) | Sep 22, 2022 |
| HP            | 8053                        | Desktop     | [d46ac6d7db](https://linux-hardware.org/?probe=d46ac6d7db) | Sep 22, 2022 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [074a9f8433](https://linux-hardware.org/?probe=074a9f8433) | Sep 22, 2022 |
| System76      | Darter Pro                  | Notebook    | [8d3bdb7585](https://linux-hardware.org/?probe=8d3bdb7585) | Sep 22, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [dc6bf82565](https://linux-hardware.org/?probe=dc6bf82565) | Sep 22, 2022 |
| ASUSTek       | K56CB                       | Notebook    | [7a7717e793](https://linux-hardware.org/?probe=7a7717e793) | Sep 21, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [dddf15cbf5](https://linux-hardware.org/?probe=dddf15cbf5) | Sep 21, 2022 |
| Acer          | Aspire E5-571               | Notebook    | [21404b14d1](https://linux-hardware.org/?probe=21404b14d1) | Sep 21, 2022 |
| Packard Be... | IMEDIA S1300                | Desktop     | [fae2bea6f3](https://linux-hardware.org/?probe=fae2bea6f3) | Sep 19, 2022 |
| HP            | 0AA8h                       | Desktop     | [3c274fc7f3](https://linux-hardware.org/?probe=3c274fc7f3) | Sep 19, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [3aa36dda04](https://linux-hardware.org/?probe=3aa36dda04) | Sep 18, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [43bc9e36cd](https://linux-hardware.org/?probe=43bc9e36cd) | Sep 17, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [ec15390099](https://linux-hardware.org/?probe=ec15390099) | Sep 14, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [81d620ed2f](https://linux-hardware.org/?probe=81d620ed2f) | Sep 14, 2022 |
| HP            | Notebook                    | Notebook    | [963af7e07b](https://linux-hardware.org/?probe=963af7e07b) | Sep 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [c54a63e1a3](https://linux-hardware.org/?probe=c54a63e1a3) | Sep 13, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [4aa1954c0c](https://linux-hardware.org/?probe=4aa1954c0c) | Sep 13, 2022 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [e2d13711aa](https://linux-hardware.org/?probe=e2d13711aa) | Sep 10, 2022 |
| Lenovo        | ThinkPad T430 2350A26       | Notebook    | [7374ee44fa](https://linux-hardware.org/?probe=7374ee44fa) | Sep 10, 2022 |
| HP            | EliteBook 840 G1            | Notebook    | [e72b842ab6](https://linux-hardware.org/?probe=e72b842ab6) | Sep 10, 2022 |
| ASUSTek       | SABERTOOTH X58              | Desktop     | [ce9d09e18a](https://linux-hardware.org/?probe=ce9d09e18a) | Sep 10, 2022 |
| Supermicro    | X9DRD-7LN4F                 | Server      | [6a4fa8ebe7](https://linux-hardware.org/?probe=6a4fa8ebe7) | Sep 09, 2022 |
| Supermicro    | X9DRD-7LN4F                 | Server      | [965f8fe14d](https://linux-hardware.org/?probe=965f8fe14d) | Sep 09, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [c0353e7c9e](https://linux-hardware.org/?probe=c0353e7c9e) | Sep 09, 2022 |
| ASUSTek       | V161GAR                     | All in one  | [668d4ac33b](https://linux-hardware.org/?probe=668d4ac33b) | Sep 09, 2022 |
| MSI           | B250M PRO-VDH               | Desktop     | [6c5483e3f5](https://linux-hardware.org/?probe=6c5483e3f5) | Sep 07, 2022 |
| Acer          | Aspire X3950                | Desktop     | [22d1319220](https://linux-hardware.org/?probe=22d1319220) | Sep 06, 2022 |
| Dell          | 0GN6JF A01                  | Desktop     | [390fbaaca7](https://linux-hardware.org/?probe=390fbaaca7) | Sep 05, 2022 |
| HP            | 8076                        | Desktop     | [e6fa33cc02](https://linux-hardware.org/?probe=e6fa33cc02) | Sep 05, 2022 |
| Acer          | Aspire S5-371               | Notebook    | [ed31a97b57](https://linux-hardware.org/?probe=ed31a97b57) | Sep 05, 2022 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [f16d383b65](https://linux-hardware.org/?probe=f16d383b65) | Sep 05, 2022 |
| ASUSTek       | Z97-PRO                     | Desktop     | [b9f3857d65](https://linux-hardware.org/?probe=b9f3857d65) | Sep 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d7c3304983](https://linux-hardware.org/?probe=d7c3304983) | Sep 04, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [08cfa37b81](https://linux-hardware.org/?probe=08cfa37b81) | Sep 03, 2022 |
| Acer          | Aspire 5942                 | Notebook    | [c2c893f2c2](https://linux-hardware.org/?probe=c2c893f2c2) | Sep 02, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [4808984401](https://linux-hardware.org/?probe=4808984401) | Aug 31, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [39faa4acc5](https://linux-hardware.org/?probe=39faa4acc5) | Aug 31, 2022 |
| Lenovo        | ThinkPad P43s 20RJS0D100    | Notebook    | [afbf0f6021](https://linux-hardware.org/?probe=afbf0f6021) | Aug 31, 2022 |
| Lenovo        | V330 81AX                   | Notebook    | [1457fc2903](https://linux-hardware.org/?probe=1457fc2903) | Aug 30, 2022 |
| Lenovo        | V330 81AX                   | Notebook    | [0699372547](https://linux-hardware.org/?probe=0699372547) | Aug 30, 2022 |
| Lenovo        | ThinkPad P50 20EQS33R0J     | Notebook    | [72f6962ac8](https://linux-hardware.org/?probe=72f6962ac8) | Aug 30, 2022 |
| HP            | 2B36                        | Desktop     | [c6de6225af](https://linux-hardware.org/?probe=c6de6225af) | Aug 29, 2022 |
| Medion        | Cattle24 1M                 | Desktop     | [eb19c533e0](https://linux-hardware.org/?probe=eb19c533e0) | Aug 29, 2022 |
| Lenovo        | 32E4 SDK0J40697 WIN 3305... | Mini pc     | [3825d0ce9c](https://linux-hardware.org/?probe=3825d0ce9c) | Aug 29, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [8f0f345242](https://linux-hardware.org/?probe=8f0f345242) | Aug 28, 2022 |
| Pegatron      | IPMSB-GS                    | Desktop     | [9edb57e041](https://linux-hardware.org/?probe=9edb57e041) | Aug 28, 2022 |
| Acer          | V3-771                      | Notebook    | [3efe8f2f41](https://linux-hardware.org/?probe=3efe8f2f41) | Aug 28, 2022 |
| Shuttle       | DS437                       | Notebook    | [9b866a79d6](https://linux-hardware.org/?probe=9b866a79d6) | Aug 27, 2022 |
| Acer          | Aspire VN7-592G             | Notebook    | [cec4df79eb](https://linux-hardware.org/?probe=cec4df79eb) | Aug 26, 2022 |
| Acer          | Aspire 5942                 | Notebook    | [528e0a954b](https://linux-hardware.org/?probe=528e0a954b) | Aug 26, 2022 |
| Lenovo        | ThinkPad X13 Gen 2a 20XH... | Notebook    | [d0b18cffdb](https://linux-hardware.org/?probe=d0b18cffdb) | Aug 23, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [936ce5ca55](https://linux-hardware.org/?probe=936ce5ca55) | Aug 22, 2022 |
| Unknown       | Unknown                     | All in one  | [da8e3c67be](https://linux-hardware.org/?probe=da8e3c67be) | Aug 22, 2022 |
| Acer          | TravelMate 5730             | Notebook    | [ec6fd6cddb](https://linux-hardware.org/?probe=ec6fd6cddb) | Aug 22, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [959dda5404](https://linux-hardware.org/?probe=959dda5404) | Aug 22, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [3de1fd7f2c](https://linux-hardware.org/?probe=3de1fd7f2c) | Aug 21, 2022 |
| HP            | 2B36                        | Desktop     | [9890b96e0e](https://linux-hardware.org/?probe=9890b96e0e) | Aug 21, 2022 |
| HP            | 212B                        | Desktop     | [ba5bf87e58](https://linux-hardware.org/?probe=ba5bf87e58) | Aug 21, 2022 |
| Acer          | Predator G9-791             | Notebook    | [782f581f0b](https://linux-hardware.org/?probe=782f581f0b) | Aug 21, 2022 |
| ASUSTek       | P7H55-M LX                  | Desktop     | [b545a0cf4f](https://linux-hardware.org/?probe=b545a0cf4f) | Aug 19, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [8a48025d15](https://linux-hardware.org/?probe=8a48025d15) | Aug 18, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [d0c25e4ba8](https://linux-hardware.org/?probe=d0c25e4ba8) | Aug 17, 2022 |
| ASUSTek       | Berkeley                    | Desktop     | [e9998910ee](https://linux-hardware.org/?probe=e9998910ee) | Aug 17, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [a6de4113fa](https://linux-hardware.org/?probe=a6de4113fa) | Aug 17, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [6cf76ee482](https://linux-hardware.org/?probe=6cf76ee482) | Aug 15, 2022 |
| Biostar       | A960D+V3                    | Desktop     | [83f7f840b7](https://linux-hardware.org/?probe=83f7f840b7) | Aug 15, 2022 |
| ASUSTek       | P5B                         | Desktop     | [1c5cafd185](https://linux-hardware.org/?probe=1c5cafd185) | Aug 15, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [98ea1068a3](https://linux-hardware.org/?probe=98ea1068a3) | Aug 15, 2022 |
| Intel         | NUC11TNBv7 K87766-405       | Mini pc     | [fee71ca4bf](https://linux-hardware.org/?probe=fee71ca4bf) | Aug 15, 2022 |
| Acer          | Aspire XC-605               | Desktop     | [125a8c791a](https://linux-hardware.org/?probe=125a8c791a) | Aug 14, 2022 |
| Panasonic     | CF-31JBGNNDM                | Notebook    | [008621e9e0](https://linux-hardware.org/?probe=008621e9e0) | Aug 14, 2022 |
| Lenovo        | Y70-70 Touch 80DU           | Notebook    | [7817924a07](https://linux-hardware.org/?probe=7817924a07) | Aug 14, 2022 |
| HP            | Unknown                     | Notebook    | [7375604d06](https://linux-hardware.org/?probe=7375604d06) | Aug 13, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [3d37c741c8](https://linux-hardware.org/?probe=3d37c741c8) | Aug 12, 2022 |
| Pegatron      | IPMSB-GS                    | Desktop     | [7d2cd4cc35](https://linux-hardware.org/?probe=7d2cd4cc35) | Aug 11, 2022 |
| Pegatron      | IPMSB-GS                    | Desktop     | [7e2bf60517](https://linux-hardware.org/?probe=7e2bf60517) | Aug 11, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [23005caccd](https://linux-hardware.org/?probe=23005caccd) | Aug 11, 2022 |
| ASUSTek       | H81T                        | Desktop     | [4049aa824c](https://linux-hardware.org/?probe=4049aa824c) | Aug 11, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [49098497d4](https://linux-hardware.org/?probe=49098497d4) | Aug 11, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [06422a72b8](https://linux-hardware.org/?probe=06422a72b8) | Aug 08, 2022 |
| ASRock        | 880GM-LE FX                 | Desktop     | [957edc332a](https://linux-hardware.org/?probe=957edc332a) | Aug 06, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [283eb3c040](https://linux-hardware.org/?probe=283eb3c040) | Aug 06, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [3db1e1ee37](https://linux-hardware.org/?probe=3db1e1ee37) | Aug 03, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [42cb82f584](https://linux-hardware.org/?probe=42cb82f584) | Aug 01, 2022 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [b5fded6824](https://linux-hardware.org/?probe=b5fded6824) | Aug 01, 2022 |
| Intel         | NUC11TNBv7 K87766-405       | Mini pc     | [e82d9ce558](https://linux-hardware.org/?probe=e82d9ce558) | Jul 29, 2022 |
| MSI           | GT72S 6QE                   | Notebook    | [9cb4896eba](https://linux-hardware.org/?probe=9cb4896eba) | Jul 28, 2022 |
| Lenovo        | ThinkPad T470s 20HGS36K0... | Notebook    | [caf10d48a0](https://linux-hardware.org/?probe=caf10d48a0) | Jul 28, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [b08a0deeff](https://linux-hardware.org/?probe=b08a0deeff) | Jul 28, 2022 |
| Lenovo        | ThinkPad P51 20HH001RMZ     | Notebook    | [3fee9267ba](https://linux-hardware.org/?probe=3fee9267ba) | Jul 27, 2022 |
| Intel         | NUC11TNBv7 K87766-405       | Mini pc     | [c086eb22b3](https://linux-hardware.org/?probe=c086eb22b3) | Jul 27, 2022 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [44a5e2107e](https://linux-hardware.org/?probe=44a5e2107e) | Jul 27, 2022 |
| Gigabyte      | EP45-DS3                    | Desktop     | [5b5fe46f75](https://linux-hardware.org/?probe=5b5fe46f75) | Jul 26, 2022 |
| Timi          | Mi Laptop Pro 15 2020       | Notebook    | [5455e664e0](https://linux-hardware.org/?probe=5455e664e0) | Jul 26, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [9a3e446c9e](https://linux-hardware.org/?probe=9a3e446c9e) | Jul 26, 2022 |
| Gigabyte      | G31M-S2L                    | Desktop     | [2e1715f154](https://linux-hardware.org/?probe=2e1715f154) | Jul 25, 2022 |
| MSI           | PRO B660M-A WIFI            | Desktop     | [e8da564bb8](https://linux-hardware.org/?probe=e8da564bb8) | Jul 23, 2022 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [7d3501365a](https://linux-hardware.org/?probe=7d3501365a) | Jul 23, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [8b9c2d3dc0](https://linux-hardware.org/?probe=8b9c2d3dc0) | Jul 22, 2022 |
| Apple         | Mac-7BA5B2D9E42DDD94 iMa... | Desktop     | [e80a3e71e2](https://linux-hardware.org/?probe=e80a3e71e2) | Jul 21, 2022 |
| Sony          | SVE1513R1EB                 | Notebook    | [61c51541dd](https://linux-hardware.org/?probe=61c51541dd) | Jul 21, 2022 |
| Alienware     | 17 R5                       | Notebook    | [29b538f1c0](https://linux-hardware.org/?probe=29b538f1c0) | Jul 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [a04d18d87a](https://linux-hardware.org/?probe=a04d18d87a) | Jul 20, 2022 |
| Lenovo        | ThinkPad L480 20LSCTO1WW    | Notebook    | [51dd660f49](https://linux-hardware.org/?probe=51dd660f49) | Jul 20, 2022 |
| HP            | 1998                        | Desktop     | [8aa7e05c70](https://linux-hardware.org/?probe=8aa7e05c70) | Jul 17, 2022 |
| Acer          | V3-771                      | Notebook    | [809bd80b9a](https://linux-hardware.org/?probe=809bd80b9a) | Jul 17, 2022 |
| Lenovo        | ThinkPad T410 25379UG       | Notebook    | [00478c63ba](https://linux-hardware.org/?probe=00478c63ba) | Jul 16, 2022 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [41c6118825](https://linux-hardware.org/?probe=41c6118825) | Jul 15, 2022 |
| HP            | Pavilion dv7                | Notebook    | [4065c23b56](https://linux-hardware.org/?probe=4065c23b56) | Jul 15, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [52a3abee65](https://linux-hardware.org/?probe=52a3abee65) | Jul 15, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [7a661a1449](https://linux-hardware.org/?probe=7a661a1449) | Jul 15, 2022 |
| HP            | Pavilion dv6700             | Notebook    | [c8bf7e091c](https://linux-hardware.org/?probe=c8bf7e091c) | Jul 14, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [c3f5c82808](https://linux-hardware.org/?probe=c3f5c82808) | Jul 14, 2022 |
| MSI           | X99A XPOWER GAMING TITAN... | Desktop     | [e764729eeb](https://linux-hardware.org/?probe=e764729eeb) | Jul 13, 2022 |
| ASUSTek       | X99-A                       | Desktop     | [6db5d85e5c](https://linux-hardware.org/?probe=6db5d85e5c) | Jul 13, 2022 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [f5982952c2](https://linux-hardware.org/?probe=f5982952c2) | Jul 11, 2022 |
| HP            | ProBook 440 G6              | Notebook    | [6a065093ba](https://linux-hardware.org/?probe=6a065093ba) | Jul 10, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [2435f08ee8](https://linux-hardware.org/?probe=2435f08ee8) | Jul 10, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [0e5d573899](https://linux-hardware.org/?probe=0e5d573899) | Jul 09, 2022 |
| Apple         | Mac-F2268DAE                | All in one  | [3dc1d7b18a](https://linux-hardware.org/?probe=3dc1d7b18a) | Jul 09, 2022 |
| ZOTAC         | Unknown                     | Desktop     | [70105d0f43](https://linux-hardware.org/?probe=70105d0f43) | Jul 09, 2022 |
| HP            | EliteBook Folio 1040 G2     | Notebook    | [c58559e78c](https://linux-hardware.org/?probe=c58559e78c) | Jul 09, 2022 |
| Unknown       | Unknown                     | Tablet      | [bf70ad93f5](https://linux-hardware.org/?probe=bf70ad93f5) | Jul 06, 2022 |
| Unknown       | Unknown                     | Tablet      | [6edba7f033](https://linux-hardware.org/?probe=6edba7f033) | Jul 06, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [d58dd09f25](https://linux-hardware.org/?probe=d58dd09f25) | Jul 06, 2022 |
| HP            | Pavilion dv7                | Notebook    | [ee1a040981](https://linux-hardware.org/?probe=ee1a040981) | Jul 06, 2022 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [5819973ca4](https://linux-hardware.org/?probe=5819973ca4) | Jul 05, 2022 |
| MSI           | GE62 2QF                    | Notebook    | [789826020e](https://linux-hardware.org/?probe=789826020e) | Jul 03, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6fa5768750](https://linux-hardware.org/?probe=6fa5768750) | Jul 02, 2022 |
| Dell          | 0HD5W2 A01                  | Desktop     | [924537ba87](https://linux-hardware.org/?probe=924537ba87) | Jul 02, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [564950d244](https://linux-hardware.org/?probe=564950d244) | Jul 02, 2022 |
| Medion        | MS-7667                     | Desktop     | [22ac257e4a](https://linux-hardware.org/?probe=22ac257e4a) | Jul 02, 2022 |
| Lenovo        | ThinkPad E14 20RA001MMZ     | Notebook    | [4bf795762d](https://linux-hardware.org/?probe=4bf795762d) | Jul 02, 2022 |
| Dell          | Latitude 7530               | Notebook    | [0d40af60b2](https://linux-hardware.org/?probe=0d40af60b2) | Jul 01, 2022 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [9b8bb07ff0](https://linux-hardware.org/?probe=9b8bb07ff0) | Jul 01, 2022 |
| Dell          | Latitude 7530               | Notebook    | [a66aca8921](https://linux-hardware.org/?probe=a66aca8921) | Jul 01, 2022 |
| Dell          | 0HD5W2 A01                  | Desktop     | [d5419be6e7](https://linux-hardware.org/?probe=d5419be6e7) | Jun 30, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [21cba60be3](https://linux-hardware.org/?probe=21cba60be3) | Jun 30, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [0dcbb35983](https://linux-hardware.org/?probe=0dcbb35983) | Jun 30, 2022 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [a2729b2e3b](https://linux-hardware.org/?probe=a2729b2e3b) | Jun 30, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [d8190f3da8](https://linux-hardware.org/?probe=d8190f3da8) | Jun 29, 2022 |
| HP            | ENVY dv7                    | Notebook    | [9f64d5f095](https://linux-hardware.org/?probe=9f64d5f095) | Jun 29, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [757741fe0d](https://linux-hardware.org/?probe=757741fe0d) | Jun 29, 2022 |
| Lenovo        | ThinkPad X220 4291WSH       | Notebook    | [7406ba0eb2](https://linux-hardware.org/?probe=7406ba0eb2) | Jun 29, 2022 |
| Dell          | Precision M6800             | Notebook    | [027cb621ef](https://linux-hardware.org/?probe=027cb621ef) | Jun 28, 2022 |
| HP            | ENVY dv7                    | Notebook    | [00ce30e950](https://linux-hardware.org/?probe=00ce30e950) | Jun 28, 2022 |
| MSI           | 2A9C                        | Desktop     | [c4d999a9a5](https://linux-hardware.org/?probe=c4d999a9a5) | Jun 26, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [800f6f5802](https://linux-hardware.org/?probe=800f6f5802) | Jun 26, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [2103486702](https://linux-hardware.org/?probe=2103486702) | Jun 23, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [7d5a943ab0](https://linux-hardware.org/?probe=7d5a943ab0) | Jun 23, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [2ba22aa099](https://linux-hardware.org/?probe=2ba22aa099) | Jun 22, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [eea8da46bd](https://linux-hardware.org/?probe=eea8da46bd) | Jun 22, 2022 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | Desktop     | [62aec95456](https://linux-hardware.org/?probe=62aec95456) | Jun 22, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [c6f721f315](https://linux-hardware.org/?probe=c6f721f315) | Jun 21, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B+     | Soc         | [2911b2782c](https://linux-hardware.org/?probe=2911b2782c) | Jun 21, 2022 |
| Lenovo        | ThinkStation S20 4105J6G    | Desktop     | [3182b17f83](https://linux-hardware.org/?probe=3182b17f83) | Jun 21, 2022 |
| Intel         | NUC11PHBi7 M26151-403       | Mini pc     | [7c3f1cd4c1](https://linux-hardware.org/?probe=7c3f1cd4c1) | Jun 21, 2022 |
| Apple         | MacBookPro15,2              | Notebook    | [c931d0e7bf](https://linux-hardware.org/?probe=c931d0e7bf) | Jun 20, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [9c4b7a7742](https://linux-hardware.org/?probe=9c4b7a7742) | Jun 20, 2022 |
| ASUSTek       | ZenBook UX391FA_UX391FA     | Notebook    | [faa0749731](https://linux-hardware.org/?probe=faa0749731) | Jun 20, 2022 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [a4621aa4ec](https://linux-hardware.org/?probe=a4621aa4ec) | Jun 19, 2022 |
| Lenovo        | IdeaPadFlex 5 16ALC7 82R... | Convertible | [5cde38b27f](https://linux-hardware.org/?probe=5cde38b27f) | Jun 19, 2022 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [6ec8ece12d](https://linux-hardware.org/?probe=6ec8ece12d) | Jun 19, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [21f78f9cf4](https://linux-hardware.org/?probe=21f78f9cf4) | Jun 19, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [0f85d8c023](https://linux-hardware.org/?probe=0f85d8c023) | Jun 19, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [d84600d5b0](https://linux-hardware.org/?probe=d84600d5b0) | Jun 17, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [8845a2219f](https://linux-hardware.org/?probe=8845a2219f) | Jun 17, 2022 |
| Lenovo        | G70-70 80HW                 | Notebook    | [de123e03c3](https://linux-hardware.org/?probe=de123e03c3) | Jun 16, 2022 |
| Lenovo        | G70-70 80HW                 | Notebook    | [31aa19ff98](https://linux-hardware.org/?probe=31aa19ff98) | Jun 16, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [7cebf6f4c1](https://linux-hardware.org/?probe=7cebf6f4c1) | Jun 16, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [a46a8033f8](https://linux-hardware.org/?probe=a46a8033f8) | Jun 15, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [c250d3b2e0](https://linux-hardware.org/?probe=c250d3b2e0) | Jun 14, 2022 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [dd22c99aac](https://linux-hardware.org/?probe=dd22c99aac) | Jun 14, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [dc89caf09f](https://linux-hardware.org/?probe=dc89caf09f) | Jun 13, 2022 |
| Clevo         | W150ER                      | Notebook    | [9121da24a8](https://linux-hardware.org/?probe=9121da24a8) | Jun 13, 2022 |
| Acer          | Aspire X3950                | Desktop     | [81797815d2](https://linux-hardware.org/?probe=81797815d2) | Jun 13, 2022 |
| TrekStor      | Surfbook A13                | Notebook    | [2c8d07851d](https://linux-hardware.org/?probe=2c8d07851d) | Jun 12, 2022 |
| Microsoft     | Surface Book 3              | Tablet      | [26c417012f](https://linux-hardware.org/?probe=26c417012f) | Jun 12, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [b31c452186](https://linux-hardware.org/?probe=b31c452186) | Jun 11, 2022 |
| HP            | 3032h                       | Desktop     | [fee76c58db](https://linux-hardware.org/?probe=fee76c58db) | Jun 09, 2022 |
| HP            | 8710                        | Mini pc     | [a4b6fd8f8a](https://linux-hardware.org/?probe=a4b6fd8f8a) | Jun 07, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [6a14acf011](https://linux-hardware.org/?probe=6a14acf011) | Jun 07, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [0fbc627b7e](https://linux-hardware.org/?probe=0fbc627b7e) | Jun 07, 2022 |
| ASUSTek       | WS X299 PRO                 | Desktop     | [219d19f97e](https://linux-hardware.org/?probe=219d19f97e) | Jun 06, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [13e2575e63](https://linux-hardware.org/?probe=13e2575e63) | Jun 05, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [812b41fe55](https://linux-hardware.org/?probe=812b41fe55) | Jun 04, 2022 |
| Shuttle       | DS10U                       | Desktop     | [f2d2634abd](https://linux-hardware.org/?probe=f2d2634abd) | Jun 04, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [c91b17ed23](https://linux-hardware.org/?probe=c91b17ed23) | Jun 04, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [b57fa63f1a](https://linux-hardware.org/?probe=b57fa63f1a) | Jun 04, 2022 |
| Lenovo        | ThinkPad T450 20BUS0HA0G    | Notebook    | [878cae499d](https://linux-hardware.org/?probe=878cae499d) | Jun 04, 2022 |
| Lenovo        | ThinkPad T450 20BUS0HA0G    | Notebook    | [0c53f7240c](https://linux-hardware.org/?probe=0c53f7240c) | Jun 03, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [a2a510d9dd](https://linux-hardware.org/?probe=a2a510d9dd) | Jun 03, 2022 |
| Toshiba       | Satellite L850-1D5          | Notebook    | [c8a260ef80](https://linux-hardware.org/?probe=c8a260ef80) | Jun 03, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [d8134fd2fe](https://linux-hardware.org/?probe=d8134fd2fe) | Jun 02, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [1fb17fc133](https://linux-hardware.org/?probe=1fb17fc133) | Jun 01, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [70ad46aa8e](https://linux-hardware.org/?probe=70ad46aa8e) | Jun 01, 2022 |
| ASUSTek       | P5B                         | Desktop     | [12554af571](https://linux-hardware.org/?probe=12554af571) | May 31, 2022 |
| Acer          | Swift SF515-51T             | Notebook    | [d4283c0b8b](https://linux-hardware.org/?probe=d4283c0b8b) | May 31, 2022 |
| Acer          | Swift SF515-51T             | Notebook    | [1d0b1a1c50](https://linux-hardware.org/?probe=1d0b1a1c50) | May 31, 2022 |
| HP            | 212B                        | Desktop     | [f651b20f02](https://linux-hardware.org/?probe=f651b20f02) | May 30, 2022 |
| HP            | ENVY Laptop 15-ep1xxx       | Notebook    | [e6145c7453](https://linux-hardware.org/?probe=e6145c7453) | May 30, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e474768a25](https://linux-hardware.org/?probe=e474768a25) | May 30, 2022 |
| Minix         | NEO Z83-4A V1.1             | Desktop     | [e828d9bd38](https://linux-hardware.org/?probe=e828d9bd38) | May 29, 2022 |
| Dell          | 0J3C2F A00                  | Desktop     | [c192680ab5](https://linux-hardware.org/?probe=c192680ab5) | May 29, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [03a4099a33](https://linux-hardware.org/?probe=03a4099a33) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [7ae101b473](https://linux-hardware.org/?probe=7ae101b473) | May 28, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [469ed3f68b](https://linux-hardware.org/?probe=469ed3f68b) | May 28, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [7220b6a007](https://linux-hardware.org/?probe=7220b6a007) | May 28, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [962defa2c3](https://linux-hardware.org/?probe=962defa2c3) | May 28, 2022 |
| HP            | ENVY TS 15                  | Notebook    | [cde5dba599](https://linux-hardware.org/?probe=cde5dba599) | May 27, 2022 |
| HP            | ENVY TS 15                  | Notebook    | [e6ee61fdd8](https://linux-hardware.org/?probe=e6ee61fdd8) | May 27, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [365ff27343](https://linux-hardware.org/?probe=365ff27343) | May 27, 2022 |
| Lenovo        | V320-17IKB 81AH             | Notebook    | [c5d9a03264](https://linux-hardware.org/?probe=c5d9a03264) | May 27, 2022 |
| Dell          | 073MMW A02                  | Desktop     | [6c7cfb5226](https://linux-hardware.org/?probe=6c7cfb5226) | May 27, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8bcdd771fa](https://linux-hardware.org/?probe=8bcdd771fa) | May 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [41529bd0e1](https://linux-hardware.org/?probe=41529bd0e1) | May 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [da6bd78cdb](https://linux-hardware.org/?probe=da6bd78cdb) | May 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [071bc80c0b](https://linux-hardware.org/?probe=071bc80c0b) | May 27, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [586d86827b](https://linux-hardware.org/?probe=586d86827b) | May 27, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [5f505dd767](https://linux-hardware.org/?probe=5f505dd767) | May 26, 2022 |
| ASRock        | FM2A85X Extreme6            | Desktop     | [00d4dc8661](https://linux-hardware.org/?probe=00d4dc8661) | May 24, 2022 |
| HP            | 8703                        | Desktop     | [14af29c571](https://linux-hardware.org/?probe=14af29c571) | May 24, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [1158b31567](https://linux-hardware.org/?probe=1158b31567) | May 24, 2022 |
| Timi          | TM1613                      | Notebook    | [695d8d5ff0](https://linux-hardware.org/?probe=695d8d5ff0) | May 21, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [da6b66b74f](https://linux-hardware.org/?probe=da6b66b74f) | May 21, 2022 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [162c85f06d](https://linux-hardware.org/?probe=162c85f06d) | May 20, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [6e7143bfd4](https://linux-hardware.org/?probe=6e7143bfd4) | May 20, 2022 |
| Acer          | V3-771                      | Notebook    | [8bcab66496](https://linux-hardware.org/?probe=8bcab66496) | May 20, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [0d4945774e](https://linux-hardware.org/?probe=0d4945774e) | May 18, 2022 |
| Razer         | Blade 15 Mid 2019-Base      | Notebook    | [e771dc589b](https://linux-hardware.org/?probe=e771dc589b) | May 18, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [625d790cde](https://linux-hardware.org/?probe=625d790cde) | May 17, 2022 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [d8b886317a](https://linux-hardware.org/?probe=d8b886317a) | May 17, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [61c1716210](https://linux-hardware.org/?probe=61c1716210) | May 16, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [7f7463682a](https://linux-hardware.org/?probe=7f7463682a) | May 16, 2022 |
| HP            | 81B7 1001                   | All in one  | [d99babe70f](https://linux-hardware.org/?probe=d99babe70f) | May 15, 2022 |
| HP            | Notebook                    | Notebook    | [e672632acf](https://linux-hardware.org/?probe=e672632acf) | May 13, 2022 |
| HP            | 805F                        | Desktop     | [c682455b49](https://linux-hardware.org/?probe=c682455b49) | May 13, 2022 |
| HP            | 805F                        | Desktop     | [ef6a65832f](https://linux-hardware.org/?probe=ef6a65832f) | May 13, 2022 |
| Shuttle       | DS10U                       | Desktop     | [2f2acb55e9](https://linux-hardware.org/?probe=2f2acb55e9) | May 13, 2022 |
| TUXEDO        | N2x0WU                      | Notebook    | [b70a08c999](https://linux-hardware.org/?probe=b70a08c999) | May 12, 2022 |
| ASUSTek       | GA35DX                      | Desktop     | [f604073d1f](https://linux-hardware.org/?probe=f604073d1f) | May 11, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [0e12a4aa26](https://linux-hardware.org/?probe=0e12a4aa26) | May 11, 2022 |
| Lenovo        | ThinkPad W530 2463A64       | Notebook    | [f45c19aa6c](https://linux-hardware.org/?probe=f45c19aa6c) | May 11, 2022 |
| Sony          | VPCF23S1E                   | Notebook    | [5eb4b61ffb](https://linux-hardware.org/?probe=5eb4b61ffb) | May 10, 2022 |
| ASRock        | J4105B-ITX                  | Desktop     | [6e507d9a68](https://linux-hardware.org/?probe=6e507d9a68) | May 09, 2022 |
| ASRock        | J4105B-ITX                  | Desktop     | [c4eea9f630](https://linux-hardware.org/?probe=c4eea9f630) | May 09, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9f6a18226f](https://linux-hardware.org/?probe=9f6a18226f) | May 09, 2022 |
| HP            | 870C                        | Desktop     | [adb470192a](https://linux-hardware.org/?probe=adb470192a) | May 08, 2022 |
| Toshiba       | TECRA R840                  | Notebook    | [38ff1a3344](https://linux-hardware.org/?probe=38ff1a3344) | May 07, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [7894bd4591](https://linux-hardware.org/?probe=7894bd4591) | May 07, 2022 |
| Lenovo        | SDK0E50510 WIN 262504835... | Desktop     | [5565a2f131](https://linux-hardware.org/?probe=5565a2f131) | May 07, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [e281a8eee2](https://linux-hardware.org/?probe=e281a8eee2) | May 06, 2022 |
| Dell          | Inspiron 1720               | Notebook    | [e95b0172b4](https://linux-hardware.org/?probe=e95b0172b4) | May 06, 2022 |
| Dell          | Inspiron 1720               | Notebook    | [a888a93774](https://linux-hardware.org/?probe=a888a93774) | May 06, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [1332984f5d](https://linux-hardware.org/?probe=1332984f5d) | May 06, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [94806fd9bf](https://linux-hardware.org/?probe=94806fd9bf) | May 05, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ebc49550d4](https://linux-hardware.org/?probe=ebc49550d4) | May 05, 2022 |
| ASUSTek       | P8H77-M                     | Desktop     | [9264c80f15](https://linux-hardware.org/?probe=9264c80f15) | May 05, 2022 |
| Khadas        | VIM3                        | Soc         | [c17309ec68](https://linux-hardware.org/?probe=c17309ec68) | May 04, 2022 |
| Apple         | MacBookPro11,3              | Notebook    | [21f611f3c7](https://linux-hardware.org/?probe=21f611f3c7) | May 03, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [aa294d2650](https://linux-hardware.org/?probe=aa294d2650) | May 02, 2022 |
| MSI           | PRO B660M-A WIFI            | Desktop     | [878c361636](https://linux-hardware.org/?probe=878c361636) | May 01, 2022 |
| Medion        | Cattle24 1M                 | Desktop     | [920d1b35ab](https://linux-hardware.org/?probe=920d1b35ab) | Apr 30, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [a10b79694f](https://linux-hardware.org/?probe=a10b79694f) | Apr 29, 2022 |
| Acer          | Predator G3620              | Desktop     | [556a67d50d](https://linux-hardware.org/?probe=556a67d50d) | Apr 28, 2022 |
| NF541         | 1.0                         | Desktop     | [c0999696b6](https://linux-hardware.org/?probe=c0999696b6) | Apr 27, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [99b46394bf](https://linux-hardware.org/?probe=99b46394bf) | Apr 27, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [25041b35de](https://linux-hardware.org/?probe=25041b35de) | Apr 27, 2022 |
| HP            | ENVY 17                     | Notebook    | [c33b35becc](https://linux-hardware.org/?probe=c33b35becc) | Apr 26, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [c052066ee4](https://linux-hardware.org/?probe=c052066ee4) | Apr 26, 2022 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [85cc720515](https://linux-hardware.org/?probe=85cc720515) | Apr 24, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [475131a6f4](https://linux-hardware.org/?probe=475131a6f4) | Apr 23, 2022 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [19d81a0ef0](https://linux-hardware.org/?probe=19d81a0ef0) | Apr 22, 2022 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [cd9c2dd8f9](https://linux-hardware.org/?probe=cd9c2dd8f9) | Apr 22, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [597940fbe8](https://linux-hardware.org/?probe=597940fbe8) | Apr 22, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [6495b55188](https://linux-hardware.org/?probe=6495b55188) | Apr 21, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [3d667e4edf](https://linux-hardware.org/?probe=3d667e4edf) | Apr 21, 2022 |
| Lenovo        | ThinkPad P43s 20RH0023UK    | Notebook    | [1cabdda156](https://linux-hardware.org/?probe=1cabdda156) | Apr 21, 2022 |
| Lenovo        | ThinkPad E580 20KS006EMZ    | Notebook    | [4d54c594ff](https://linux-hardware.org/?probe=4d54c594ff) | Apr 20, 2022 |
| HP            | 3048h                       | Desktop     | [b35df4ed74](https://linux-hardware.org/?probe=b35df4ed74) | Apr 20, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [3af8357ab9](https://linux-hardware.org/?probe=3af8357ab9) | Apr 20, 2022 |
| MSI           | X99A SLI PLUS               | Desktop     | [0b935aadb3](https://linux-hardware.org/?probe=0b935aadb3) | Apr 19, 2022 |
| System76      | Galago Pro                  | Notebook    | [32b09fd215](https://linux-hardware.org/?probe=32b09fd215) | Apr 19, 2022 |
| Acer          | Aspire ES1-731              | Notebook    | [451ce5305a](https://linux-hardware.org/?probe=451ce5305a) | Apr 19, 2022 |
| Acer          | Aspire ES1-731              | Notebook    | [fa843a199c](https://linux-hardware.org/?probe=fa843a199c) | Apr 19, 2022 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [1ceaddfc92](https://linux-hardware.org/?probe=1ceaddfc92) | Apr 16, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [46dd37cb4b](https://linux-hardware.org/?probe=46dd37cb4b) | Apr 16, 2022 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [6d63a9c8bc](https://linux-hardware.org/?probe=6d63a9c8bc) | Apr 15, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [e3ab162648](https://linux-hardware.org/?probe=e3ab162648) | Apr 15, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [0d7edf2aa9](https://linux-hardware.org/?probe=0d7edf2aa9) | Apr 15, 2022 |
| Acer          | TMP455-M                    | Notebook    | [451dbf0a20](https://linux-hardware.org/?probe=451dbf0a20) | Apr 15, 2022 |
| Acer          | TMP455-M                    | Notebook    | [b7b9924190](https://linux-hardware.org/?probe=b7b9924190) | Apr 15, 2022 |
| HP            | 8298                        | Desktop     | [a9796ddd8d](https://linux-hardware.org/?probe=a9796ddd8d) | Apr 14, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [cfd276f151](https://linux-hardware.org/?probe=cfd276f151) | Apr 13, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [8e46ef2a00](https://linux-hardware.org/?probe=8e46ef2a00) | Apr 13, 2022 |
| Acer          | Swift SF514-51              | Notebook    | [147a0161aa](https://linux-hardware.org/?probe=147a0161aa) | Apr 13, 2022 |
| Lenovo        | ThinkPad T490s 20NY000JM... | Notebook    | [e93e7d9ad1](https://linux-hardware.org/?probe=e93e7d9ad1) | Apr 13, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [18a9612e64](https://linux-hardware.org/?probe=18a9612e64) | Apr 13, 2022 |
| Dell          | Latitude E7240              | Notebook    | [1a08843719](https://linux-hardware.org/?probe=1a08843719) | Apr 13, 2022 |
| Lenovo        | ThinkPad Helix 36986CG      | Notebook    | [f0aa04a603](https://linux-hardware.org/?probe=f0aa04a603) | Apr 12, 2022 |
| Dell          | Inspiron 7786               | Convertible | [cdf7aa0cb8](https://linux-hardware.org/?probe=cdf7aa0cb8) | Apr 11, 2022 |
| Dell          | Latitude D400               | Notebook    | [46981d939b](https://linux-hardware.org/?probe=46981d939b) | Apr 11, 2022 |
| PC Engines    | apu4                        | Desktop     | [601866ecaa](https://linux-hardware.org/?probe=601866ecaa) | Apr 11, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [36e8e44760](https://linux-hardware.org/?probe=36e8e44760) | Apr 11, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [50d7c349cd](https://linux-hardware.org/?probe=50d7c349cd) | Apr 10, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [b160291e93](https://linux-hardware.org/?probe=b160291e93) | Apr 09, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [b53427c0f4](https://linux-hardware.org/?probe=b53427c0f4) | Apr 07, 2022 |
| HP            | ProBook 4530s               | Notebook    | [1b32584f41](https://linux-hardware.org/?probe=1b32584f41) | Apr 06, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [091190515b](https://linux-hardware.org/?probe=091190515b) | Apr 06, 2022 |
| HP            | ProBook 4530s               | Notebook    | [f4dfc894d9](https://linux-hardware.org/?probe=f4dfc894d9) | Apr 06, 2022 |
| MSI           | 2A9C                        | Desktop     | [d56d880fd1](https://linux-hardware.org/?probe=d56d880fd1) | Apr 05, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [7e44cf1d2c](https://linux-hardware.org/?probe=7e44cf1d2c) | Apr 04, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [3aa8c7cbc6](https://linux-hardware.org/?probe=3aa8c7cbc6) | Apr 04, 2022 |
| Acer          | Swift SF314-57              | Notebook    | [e43f33eef1](https://linux-hardware.org/?probe=e43f33eef1) | Apr 03, 2022 |
| Quanmax       | Platin SE                   | Notebook    | [5090da9cbf](https://linux-hardware.org/?probe=5090da9cbf) | Apr 03, 2022 |
| Apple         | MacBookPro10,1              | Notebook    | [d1c62a1f93](https://linux-hardware.org/?probe=d1c62a1f93) | Apr 03, 2022 |
| Quanmax       | Platin SE                   | Notebook    | [2388fe9587](https://linux-hardware.org/?probe=2388fe9587) | Apr 03, 2022 |
| Lenovo        | ThinkPad X201 Tablet 311... | Notebook    | [7f48dd5612](https://linux-hardware.org/?probe=7f48dd5612) | Apr 02, 2022 |
| Gigabyte      | H410M S2H V3                | Desktop     | [0c9c9dd7e9](https://linux-hardware.org/?probe=0c9c9dd7e9) | Apr 02, 2022 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [e7d599e001](https://linux-hardware.org/?probe=e7d599e001) | Apr 01, 2022 |
| Apple         | Mac-F4228EC8 DVT            | All in one  | [52d7f90956](https://linux-hardware.org/?probe=52d7f90956) | Apr 01, 2022 |
| Acer          | Aspire E5-773G              | Notebook    | [b43b436e59](https://linux-hardware.org/?probe=b43b436e59) | Mar 31, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [521a29d065](https://linux-hardware.org/?probe=521a29d065) | Mar 31, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [6755915c96](https://linux-hardware.org/?probe=6755915c96) | Mar 29, 2022 |
| HP            | Pavilion g7                 | Notebook    | [44a6ea06b0](https://linux-hardware.org/?probe=44a6ea06b0) | Mar 28, 2022 |
| MSI           | Z170A PC MATE               | Desktop     | [546a66dcf1](https://linux-hardware.org/?probe=546a66dcf1) | Mar 27, 2022 |
| HP            | ZBook Studio G7 Mobile W... | Notebook    | [edbd5fd6aa](https://linux-hardware.org/?probe=edbd5fd6aa) | Mar 27, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [85f4e6ff91](https://linux-hardware.org/?probe=85f4e6ff91) | Mar 26, 2022 |
| Lenovo        | ThinkPad T430 2349U4B       | Notebook    | [95526f5b3e](https://linux-hardware.org/?probe=95526f5b3e) | Mar 25, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [ed949b0853](https://linux-hardware.org/?probe=ed949b0853) | Mar 24, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [684a4fd3c3](https://linux-hardware.org/?probe=684a4fd3c3) | Mar 24, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [96244433f0](https://linux-hardware.org/?probe=96244433f0) | Mar 23, 2022 |
| Dell          | Inspiron 7400               | Notebook    | [a17dc3be48](https://linux-hardware.org/?probe=a17dc3be48) | Mar 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [9391fc9592](https://linux-hardware.org/?probe=9391fc9592) | Mar 23, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [a9df37f3f0](https://linux-hardware.org/?probe=a9df37f3f0) | Mar 23, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [dd13dcfd89](https://linux-hardware.org/?probe=dd13dcfd89) | Mar 22, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [b7f10d6ec0](https://linux-hardware.org/?probe=b7f10d6ec0) | Mar 21, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [a1a39d622b](https://linux-hardware.org/?probe=a1a39d622b) | Mar 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [18294dd367](https://linux-hardware.org/?probe=18294dd367) | Mar 21, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f51c0bb134](https://linux-hardware.org/?probe=f51c0bb134) | Mar 21, 2022 |
| ASUSTek       | K73E                        | Notebook    | [75069bd642](https://linux-hardware.org/?probe=75069bd642) | Mar 20, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [d98f42c86b](https://linux-hardware.org/?probe=d98f42c86b) | Mar 20, 2022 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | Notebook    | [161ca16bc2](https://linux-hardware.org/?probe=161ca16bc2) | Mar 19, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [a226a58819](https://linux-hardware.org/?probe=a226a58819) | Mar 19, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [7664c536f4](https://linux-hardware.org/?probe=7664c536f4) | Mar 18, 2022 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [9c78b8d68b](https://linux-hardware.org/?probe=9c78b8d68b) | Mar 17, 2022 |
| ASUSTek       | Zenbook UN5401QA_UN5401Q... | Convertible | [d0253d1ffc](https://linux-hardware.org/?probe=d0253d1ffc) | Mar 16, 2022 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [04e11e3668](https://linux-hardware.org/?probe=04e11e3668) | Mar 16, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [b0d9828f83](https://linux-hardware.org/?probe=b0d9828f83) | Mar 16, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [81ec123b24](https://linux-hardware.org/?probe=81ec123b24) | Mar 15, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [bf629bc1a5](https://linux-hardware.org/?probe=bf629bc1a5) | Mar 14, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [7649fad366](https://linux-hardware.org/?probe=7649fad366) | Mar 14, 2022 |
| ASUSTek       | VC66                        | Mini pc     | [e89b5b2495](https://linux-hardware.org/?probe=e89b5b2495) | Mar 14, 2022 |
| ASUSTek       | VC66                        | Mini pc     | [52c0b45697](https://linux-hardware.org/?probe=52c0b45697) | Mar 14, 2022 |
| Dell          | Latitude 5400               | Notebook    | [e23429d8ea](https://linux-hardware.org/?probe=e23429d8ea) | Mar 13, 2022 |
| Fujitsu       | LIFEBOOK E782               | Notebook    | [77b3a7f272](https://linux-hardware.org/?probe=77b3a7f272) | Mar 13, 2022 |
| Gigabyte      | Z590 VISION G               | Desktop     | [f56d8f0fe4](https://linux-hardware.org/?probe=f56d8f0fe4) | Mar 13, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [fd7e52fdd3](https://linux-hardware.org/?probe=fd7e52fdd3) | Mar 13, 2022 |
| ASUSTek       | Crosshair IV Formula        | Desktop     | [f4f7ab1aaf](https://linux-hardware.org/?probe=f4f7ab1aaf) | Mar 12, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [5f36bc3969](https://linux-hardware.org/?probe=5f36bc3969) | Mar 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f735730566](https://linux-hardware.org/?probe=f735730566) | Mar 11, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e8ffb57db8](https://linux-hardware.org/?probe=e8ffb57db8) | Mar 11, 2022 |
| HP            | 806A                        | Desktop     | [60d334dbf5](https://linux-hardware.org/?probe=60d334dbf5) | Mar 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Convertible | [566eee23f5](https://linux-hardware.org/?probe=566eee23f5) | Mar 10, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Convertible | [0046299935](https://linux-hardware.org/?probe=0046299935) | Mar 10, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [1526117b64](https://linux-hardware.org/?probe=1526117b64) | Mar 10, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [67ead34e9e](https://linux-hardware.org/?probe=67ead34e9e) | Mar 10, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [c98fcbec3c](https://linux-hardware.org/?probe=c98fcbec3c) | Mar 10, 2022 |
| HUAWEI        | WRT-WX9                     | Notebook    | [2bd4f9201a](https://linux-hardware.org/?probe=2bd4f9201a) | Mar 09, 2022 |
| MSI           | MAG B460M MORTAR            | Desktop     | [0e1398474c](https://linux-hardware.org/?probe=0e1398474c) | Mar 09, 2022 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | Notebook    | [1eaa06bf11](https://linux-hardware.org/?probe=1eaa06bf11) | Mar 06, 2022 |
| Dell          | XPS 13 9350                 | Notebook    | [ce5fd5227f](https://linux-hardware.org/?probe=ce5fd5227f) | Mar 05, 2022 |
| ASUSTek       | G551JK                      | Notebook    | [a9f394c585](https://linux-hardware.org/?probe=a9f394c585) | Mar 05, 2022 |
| Dell          | Latitude 7490               | Notebook    | [64f0d004ce](https://linux-hardware.org/?probe=64f0d004ce) | Mar 05, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [af17a2da6b](https://linux-hardware.org/?probe=af17a2da6b) | Mar 05, 2022 |
| Dell          | 0K240Y A02                  | Desktop     | [95d4a7b220](https://linux-hardware.org/?probe=95d4a7b220) | Mar 05, 2022 |
| Apple         | MacBookPro6,2               | Notebook    | [a2f1d82d9c](https://linux-hardware.org/?probe=a2f1d82d9c) | Mar 05, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [fd01513251](https://linux-hardware.org/?probe=fd01513251) | Mar 04, 2022 |
| HP            | EliteBook x360 1030 G3      | Convertible | [7d5295d845](https://linux-hardware.org/?probe=7d5295d845) | Mar 03, 2022 |
| Fujitsu       | D3090-A1 S26361-D3090-A1    | Server      | [ee54bb96c5](https://linux-hardware.org/?probe=ee54bb96c5) | Mar 03, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [5c8b94d514](https://linux-hardware.org/?probe=5c8b94d514) | Mar 03, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [75b63c2d2c](https://linux-hardware.org/?probe=75b63c2d2c) | Mar 02, 2022 |
| HP            | 8592                        | Desktop     | [a34dbdb173](https://linux-hardware.org/?probe=a34dbdb173) | Mar 01, 2022 |
| Medion        | P6624                       | Notebook    | [0a502fd230](https://linux-hardware.org/?probe=0a502fd230) | Feb 28, 2022 |
| MSI           | MAG X570S TOMAHAWK MAX W... | Desktop     | [e0d39731a0](https://linux-hardware.org/?probe=e0d39731a0) | Feb 27, 2022 |
| ASRock        | Z370 Pro4                   | Desktop     | [e996ec20ea](https://linux-hardware.org/?probe=e996ec20ea) | Feb 25, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [4c72ebcb41](https://linux-hardware.org/?probe=4c72ebcb41) | Feb 25, 2022 |
| Notebook      | N13xWU                      | Notebook    | [50acf36954](https://linux-hardware.org/?probe=50acf36954) | Feb 25, 2022 |
| Acer          | TMP455-MG                   | Notebook    | [f1a500ae43](https://linux-hardware.org/?probe=f1a500ae43) | Feb 25, 2022 |
| Dell          | Precision 3551              | Notebook    | [9394fc8844](https://linux-hardware.org/?probe=9394fc8844) | Feb 24, 2022 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [98a6706e6a](https://linux-hardware.org/?probe=98a6706e6a) | Feb 23, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [9d3f01a706](https://linux-hardware.org/?probe=9d3f01a706) | Feb 23, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [923930ee4e](https://linux-hardware.org/?probe=923930ee4e) | Feb 22, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [226452fec0](https://linux-hardware.org/?probe=226452fec0) | Feb 21, 2022 |
| Lenovo        | MIIX 310-10ICR 80SG         | Tablet      | [1b5b236f76](https://linux-hardware.org/?probe=1b5b236f76) | Feb 21, 2022 |
| ASUSTek       | G551JK                      | Notebook    | [93e40c8fbc](https://linux-hardware.org/?probe=93e40c8fbc) | Feb 20, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [b0e0d82d12](https://linux-hardware.org/?probe=b0e0d82d12) | Feb 20, 2022 |
| BESSTAR Te... | ATB15                       | Server      | [0ab1ff409b](https://linux-hardware.org/?probe=0ab1ff409b) | Feb 20, 2022 |
| Lenovo        | 3130 SDK0J40697 WIN 3305... | Mini pc     | [40f1930253](https://linux-hardware.org/?probe=40f1930253) | Feb 19, 2022 |
| Gigabyte      | MSH87TN-00                  | Desktop     | [6baa824f3a](https://linux-hardware.org/?probe=6baa824f3a) | Feb 17, 2022 |
| ASUSTek       | P5B                         | Desktop     | [fa4c095fd7](https://linux-hardware.org/?probe=fa4c095fd7) | Feb 17, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [f2d47f2d8b](https://linux-hardware.org/?probe=f2d47f2d8b) | Feb 17, 2022 |
| Dell          | Latitude 7490               | Notebook    | [2620ebab43](https://linux-hardware.org/?probe=2620ebab43) | Feb 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [1055dc7082](https://linux-hardware.org/?probe=1055dc7082) | Feb 14, 2022 |
| Acer          | Aspire 3820                 | Notebook    | [7364dc5d5e](https://linux-hardware.org/?probe=7364dc5d5e) | Feb 14, 2022 |
| HP            | EliteBook x360 1030 G3      | Convertible | [91dbebb5dd](https://linux-hardware.org/?probe=91dbebb5dd) | Feb 14, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [34bb725d27](https://linux-hardware.org/?probe=34bb725d27) | Feb 14, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [a82c9b223f](https://linux-hardware.org/?probe=a82c9b223f) | Feb 14, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [3dd59d8ebe](https://linux-hardware.org/?probe=3dd59d8ebe) | Feb 13, 2022 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | Desktop     | [4583e687ca](https://linux-hardware.org/?probe=4583e687ca) | Feb 13, 2022 |
| HP            | Compaq 15                   | Notebook    | [fa22db8854](https://linux-hardware.org/?probe=fa22db8854) | Feb 12, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [0f83b2fd97](https://linux-hardware.org/?probe=0f83b2fd97) | Feb 12, 2022 |
| HP            | 8618                        | Desktop     | [6976caf9ed](https://linux-hardware.org/?probe=6976caf9ed) | Feb 12, 2022 |
| HP            | 8618                        | Desktop     | [1038885608](https://linux-hardware.org/?probe=1038885608) | Feb 12, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [6a16b1953c](https://linux-hardware.org/?probe=6a16b1953c) | Feb 11, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [c5b6cfb8bc](https://linux-hardware.org/?probe=c5b6cfb8bc) | Feb 11, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [8b31b460fc](https://linux-hardware.org/?probe=8b31b460fc) | Feb 11, 2022 |
| PC Special... | NH5x_7xRCx,RDx              | Notebook    | [3fad293703](https://linux-hardware.org/?probe=3fad293703) | Feb 10, 2022 |
| MSI           | G31TM-P35                   | Desktop     | [6312e054ab](https://linux-hardware.org/?probe=6312e054ab) | Feb 09, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [cf4fbc7ab1](https://linux-hardware.org/?probe=cf4fbc7ab1) | Feb 09, 2022 |
| Medion        | B460H6-EM                   | Desktop     | [b32b83ff4b](https://linux-hardware.org/?probe=b32b83ff4b) | Feb 09, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [b8a4437ef8](https://linux-hardware.org/?probe=b8a4437ef8) | Feb 09, 2022 |
| Dell          | XPS 15 7590                 | Notebook    | [e06f742b06](https://linux-hardware.org/?probe=e06f742b06) | Feb 09, 2022 |
| whyopencom... | Unknown                     | Notebook    | [ed4f02d91d](https://linux-hardware.org/?probe=ed4f02d91d) | Feb 09, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [da25fcadb3](https://linux-hardware.org/?probe=da25fcadb3) | Feb 09, 2022 |
| HP            | 18E5                        | Desktop     | [85267de714](https://linux-hardware.org/?probe=85267de714) | Feb 09, 2022 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [f252168753](https://linux-hardware.org/?probe=f252168753) | Feb 08, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [73738d3f0c](https://linux-hardware.org/?probe=73738d3f0c) | Feb 08, 2022 |
| Quanta        | TW8/SW8/DW8                 | Notebook    | [a542c42556](https://linux-hardware.org/?probe=a542c42556) | Feb 08, 2022 |
| Dell          | Latitude E5410              | Notebook    | [fd73c50faa](https://linux-hardware.org/?probe=fd73c50faa) | Feb 07, 2022 |
| Acer          | Aspire A515-52G             | Notebook    | [cfc69482e3](https://linux-hardware.org/?probe=cfc69482e3) | Feb 07, 2022 |
| ASUSTek       | P8P67                       | Desktop     | [59a8e93ae4](https://linux-hardware.org/?probe=59a8e93ae4) | Feb 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [99770a5e77](https://linux-hardware.org/?probe=99770a5e77) | Feb 06, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [30bb989cfa](https://linux-hardware.org/?probe=30bb989cfa) | Feb 05, 2022 |
| ZOTAC         | ZBOXNANO-ID67               | Mini pc     | [7eab522138](https://linux-hardware.org/?probe=7eab522138) | Feb 05, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [091a9c467d](https://linux-hardware.org/?probe=091a9c467d) | Feb 04, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [7ff1fc83fc](https://linux-hardware.org/?probe=7ff1fc83fc) | Feb 04, 2022 |
| ASUSTek       | P5B                         | Desktop     | [9b661f64dd](https://linux-hardware.org/?probe=9b661f64dd) | Feb 04, 2022 |
| AAEON         | MF-001 V1.0                 | Desktop     | [01244429c8](https://linux-hardware.org/?probe=01244429c8) | Feb 03, 2022 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [dde47afaff](https://linux-hardware.org/?probe=dde47afaff) | Feb 03, 2022 |
| Packard Be... | EasyNote TV44HC             | Notebook    | [60aaa89bfa](https://linux-hardware.org/?probe=60aaa89bfa) | Feb 03, 2022 |
| Unknown       | 1.0                         | Desktop     | [03f9d9de62](https://linux-hardware.org/?probe=03f9d9de62) | Jan 31, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [08a04a280f](https://linux-hardware.org/?probe=08a04a280f) | Jan 30, 2022 |
| HP            | 3048h                       | Desktop     | [cb51d0cf78](https://linux-hardware.org/?probe=cb51d0cf78) | Jan 30, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [1e4b8a880e](https://linux-hardware.org/?probe=1e4b8a880e) | Jan 29, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [31a1c1d4ab](https://linux-hardware.org/?probe=31a1c1d4ab) | Jan 28, 2022 |
| Clevo         | W76x/M77xCUH                | Notebook    | [48d0efb057](https://linux-hardware.org/?probe=48d0efb057) | Jan 26, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [5f5b79eabf](https://linux-hardware.org/?probe=5f5b79eabf) | Jan 25, 2022 |
| AMI           | Cherry Trail Tablet         | Notebook    | [0560bf99e5](https://linux-hardware.org/?probe=0560bf99e5) | Jan 25, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [055decea61](https://linux-hardware.org/?probe=055decea61) | Jan 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [dbeeb0a6f3](https://linux-hardware.org/?probe=dbeeb0a6f3) | Jan 24, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [db3a3ddae1](https://linux-hardware.org/?probe=db3a3ddae1) | Jan 23, 2022 |
| HP            | ProBook 445 G8 Notebook ... | Notebook    | [8ee01c475e](https://linux-hardware.org/?probe=8ee01c475e) | Jan 23, 2022 |
| Packard Be... | EasyNote TV44HC             | Notebook    | [38fb76e085](https://linux-hardware.org/?probe=38fb76e085) | Jan 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [7a934945d5](https://linux-hardware.org/?probe=7a934945d5) | Jan 23, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [cf8776e11f](https://linux-hardware.org/?probe=cf8776e11f) | Jan 22, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [4a0bd17330](https://linux-hardware.org/?probe=4a0bd17330) | Jan 22, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [c528c04bb7](https://linux-hardware.org/?probe=c528c04bb7) | Jan 22, 2022 |
| Apple         | MacBookPro5,3               | Notebook    | [e0b61bcde4](https://linux-hardware.org/?probe=e0b61bcde4) | Jan 22, 2022 |
| Packard Be... | EasyNote TV44HC             | Notebook    | [d2a1835844](https://linux-hardware.org/?probe=d2a1835844) | Jan 22, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [95b7ce0007](https://linux-hardware.org/?probe=95b7ce0007) | Jan 22, 2022 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [986b65d292](https://linux-hardware.org/?probe=986b65d292) | Jan 21, 2022 |
| Medion        | Cattle24 1M                 | Desktop     | [328e103a74](https://linux-hardware.org/?probe=328e103a74) | Jan 21, 2022 |
| Gigabyte      | H97-D3H-CF                  | Desktop     | [8e39cc0d01](https://linux-hardware.org/?probe=8e39cc0d01) | Jan 21, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [0bb120993f](https://linux-hardware.org/?probe=0bb120993f) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [07b8344de7](https://linux-hardware.org/?probe=07b8344de7) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [3bdae5c5ac](https://linux-hardware.org/?probe=3bdae5c5ac) | Jan 21, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [d70ebfd602](https://linux-hardware.org/?probe=d70ebfd602) | Jan 20, 2022 |
| HP            | Pavilion g7                 | Notebook    | [064474c7e0](https://linux-hardware.org/?probe=064474c7e0) | Jan 20, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [4b8a587819](https://linux-hardware.org/?probe=4b8a587819) | Jan 20, 2022 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [e2161b5856](https://linux-hardware.org/?probe=e2161b5856) | Jan 20, 2022 |
| ASUSTek       | UX330UAK                    | Notebook    | [3749e7dc2e](https://linux-hardware.org/?probe=3749e7dc2e) | Jan 19, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [f1c61e2a1b](https://linux-hardware.org/?probe=f1c61e2a1b) | Jan 19, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [3afcc4b1c0](https://linux-hardware.org/?probe=3afcc4b1c0) | Jan 18, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [d897de368d](https://linux-hardware.org/?probe=d897de368d) | Jan 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [1478a3da5a](https://linux-hardware.org/?probe=1478a3da5a) | Jan 17, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [1c35674fd1](https://linux-hardware.org/?probe=1c35674fd1) | Jan 17, 2022 |
| Acer          | Aspire E5-511               | Notebook    | [c2691bf00b](https://linux-hardware.org/?probe=c2691bf00b) | Jan 16, 2022 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | Notebook    | [80a80d7619](https://linux-hardware.org/?probe=80a80d7619) | Jan 16, 2022 |
| HP            | 3048h                       | Desktop     | [d6f6435471](https://linux-hardware.org/?probe=d6f6435471) | Jan 15, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [ff75719a4e](https://linux-hardware.org/?probe=ff75719a4e) | Jan 15, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [d508a12888](https://linux-hardware.org/?probe=d508a12888) | Jan 15, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [2d14961843](https://linux-hardware.org/?probe=2d14961843) | Jan 14, 2022 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [0c991d9fae](https://linux-hardware.org/?probe=0c991d9fae) | Jan 14, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [c6dc2d8971](https://linux-hardware.org/?probe=c6dc2d8971) | Jan 14, 2022 |
| HP            | 829A                        | Mini pc     | [9526ea61c6](https://linux-hardware.org/?probe=9526ea61c6) | Jan 13, 2022 |
| Gigabyte      | H55M-USB3                   | Desktop     | [88396d099b](https://linux-hardware.org/?probe=88396d099b) | Jan 13, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c450cd4a79](https://linux-hardware.org/?probe=c450cd4a79) | Jan 13, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [642e01d970](https://linux-hardware.org/?probe=642e01d970) | Jan 13, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [0eb5cecbac](https://linux-hardware.org/?probe=0eb5cecbac) | Jan 12, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [bb65153cf2](https://linux-hardware.org/?probe=bb65153cf2) | Jan 12, 2022 |
| HP            | ProBook 635 Aero G8 Note... | Notebook    | [06f3fa0e22](https://linux-hardware.org/?probe=06f3fa0e22) | Jan 12, 2022 |
| HP            | ProBook 635 Aero G8 Note... | Notebook    | [ec88cd8e93](https://linux-hardware.org/?probe=ec88cd8e93) | Jan 12, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [102e1371f8](https://linux-hardware.org/?probe=102e1371f8) | Jan 11, 2022 |
| Acer          | Aspire V3-772G              | Notebook    | [aaf1227ec4](https://linux-hardware.org/?probe=aaf1227ec4) | Jan 11, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [0c0a6589e8](https://linux-hardware.org/?probe=0c0a6589e8) | Jan 11, 2022 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [2cbbce1a0e](https://linux-hardware.org/?probe=2cbbce1a0e) | Jan 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [7ce7a30da1](https://linux-hardware.org/?probe=7ce7a30da1) | Jan 10, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [ac620bc1b6](https://linux-hardware.org/?probe=ac620bc1b6) | Jan 10, 2022 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [eb70946711](https://linux-hardware.org/?probe=eb70946711) | Jan 09, 2022 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [993e94e5fd](https://linux-hardware.org/?probe=993e94e5fd) | Jan 09, 2022 |
| Intel         | NUC8BEB J72688-303          | Mini pc     | [c908574f83](https://linux-hardware.org/?probe=c908574f83) | Jan 09, 2022 |
| Gigabyte      | H55M-USB3                   | Desktop     | [aad9837ee4](https://linux-hardware.org/?probe=aad9837ee4) | Jan 08, 2022 |
| Acer          | Aspire R7-572G              | Notebook    | [dc4a930b99](https://linux-hardware.org/?probe=dc4a930b99) | Jan 08, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [a519d3f9af](https://linux-hardware.org/?probe=a519d3f9af) | Jan 07, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [4d67659f6c](https://linux-hardware.org/?probe=4d67659f6c) | Jan 07, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [b3428338c0](https://linux-hardware.org/?probe=b3428338c0) | Jan 07, 2022 |
| ASUSTek       | K53U                        | Notebook    | [62410e0adc](https://linux-hardware.org/?probe=62410e0adc) | Jan 07, 2022 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [ad5ae136c9](https://linux-hardware.org/?probe=ad5ae136c9) | Jan 05, 2022 |
| Dell          | 096JG8 A01                  | Desktop     | [fecf0d29c7](https://linux-hardware.org/?probe=fecf0d29c7) | Jan 05, 2022 |
| MSI           | 2A9Ch                       | Desktop     | [358b325347](https://linux-hardware.org/?probe=358b325347) | Jan 05, 2022 |
| Apple         | MacBookPro14,3              | Notebook    | [96b76bc44b](https://linux-hardware.org/?probe=96b76bc44b) | Jan 05, 2022 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [843345dfe6](https://linux-hardware.org/?probe=843345dfe6) | Jan 04, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [d0d2edf745](https://linux-hardware.org/?probe=d0d2edf745) | Jan 04, 2022 |
| Medion        | Cattle24 1M                 | Desktop     | [9980b9fb17](https://linux-hardware.org/?probe=9980b9fb17) | Jan 04, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [bb8b56ca21](https://linux-hardware.org/?probe=bb8b56ca21) | Jan 04, 2022 |
| ASUSTek       | ROG STRIX Z370-F GAMING     | Desktop     | [d7f6228561](https://linux-hardware.org/?probe=d7f6228561) | Jan 04, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [5209cf627a](https://linux-hardware.org/?probe=5209cf627a) | Jan 02, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [6a1f7a20cf](https://linux-hardware.org/?probe=6a1f7a20cf) | Jan 02, 2022 |
| Dell          | XPS 13 9365                 | Convertible | [bd7de25478](https://linux-hardware.org/?probe=bd7de25478) | Jan 02, 2022 |
| ASUSTek       | P5K Deluxe                  | Desktop     | [48524c94d1](https://linux-hardware.org/?probe=48524c94d1) | Jan 01, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [0551fb871e](https://linux-hardware.org/?probe=0551fb871e) | Dec 31, 2021 |
| Intel         | DP35DP AAD81073-208         | Desktop     | [469127a5f9](https://linux-hardware.org/?probe=469127a5f9) | Dec 31, 2021 |
| Intel         | NUC6i7KYB H90766-406        | Mini pc     | [c4103c8737](https://linux-hardware.org/?probe=c4103c8737) | Dec 31, 2021 |
| MSI           | 2A9C                        | Desktop     | [2e51628103](https://linux-hardware.org/?probe=2e51628103) | Dec 30, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [40eee8c893](https://linux-hardware.org/?probe=40eee8c893) | Dec 30, 2021 |
| Dell          | Latitude E5420              | Notebook    | [a2d1902586](https://linux-hardware.org/?probe=a2d1902586) | Dec 29, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [ca7f3a7275](https://linux-hardware.org/?probe=ca7f3a7275) | Dec 29, 2021 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [1c36b4c1cd](https://linux-hardware.org/?probe=1c36b4c1cd) | Dec 29, 2021 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [997c8caab6](https://linux-hardware.org/?probe=997c8caab6) | Dec 29, 2021 |
| Acer          | Aspire V3-572               | Notebook    | [57f2afd2a3](https://linux-hardware.org/?probe=57f2afd2a3) | Dec 28, 2021 |
| Gigabyte      | H55M-USB3                   | Desktop     | [6ae95f862e](https://linux-hardware.org/?probe=6ae95f862e) | Dec 28, 2021 |
| Intel         | MONTARA                     | Desktop     | [963db2e79c](https://linux-hardware.org/?probe=963db2e79c) | Dec 28, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [41edb1b55b](https://linux-hardware.org/?probe=41edb1b55b) | Dec 28, 2021 |
| HP            | Pavilion dv7                | Notebook    | [79cc0303f4](https://linux-hardware.org/?probe=79cc0303f4) | Dec 27, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [a940c31cf7](https://linux-hardware.org/?probe=a940c31cf7) | Dec 27, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [1afb1306eb](https://linux-hardware.org/?probe=1afb1306eb) | Dec 27, 2021 |
| HP            | Pavilion dv7                | Notebook    | [3ab4ebdbfd](https://linux-hardware.org/?probe=3ab4ebdbfd) | Dec 27, 2021 |
| HP            | Pavilion dv7                | Notebook    | [d9456116de](https://linux-hardware.org/?probe=d9456116de) | Dec 27, 2021 |
| HP            | 300-250                     | Notebook    | [94f3405ce4](https://linux-hardware.org/?probe=94f3405ce4) | Dec 26, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [f113b07c3e](https://linux-hardware.org/?probe=f113b07c3e) | Dec 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [cb4cb1ea51](https://linux-hardware.org/?probe=cb4cb1ea51) | Dec 26, 2021 |
| Lenovo        | B50-10 80QR                 | Notebook    | [0195687c06](https://linux-hardware.org/?probe=0195687c06) | Dec 26, 2021 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [7ebdb585ab](https://linux-hardware.org/?probe=7ebdb585ab) | Dec 26, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [527037fe8b](https://linux-hardware.org/?probe=527037fe8b) | Dec 26, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0f19f19470](https://linux-hardware.org/?probe=0f19f19470) | Dec 26, 2021 |
| Acer          | Aspire ES1-571              | Notebook    | [4973bd9cc7](https://linux-hardware.org/?probe=4973bd9cc7) | Dec 25, 2021 |
| Sony          | VPCEB1M1E                   | Notebook    | [1e9385a74f](https://linux-hardware.org/?probe=1e9385a74f) | Dec 25, 2021 |
| Shuttle       | FZ87                        | Desktop     | [e26f5a10e8](https://linux-hardware.org/?probe=e26f5a10e8) | Dec 24, 2021 |
| Shuttle       | FZ87                        | Desktop     | [62a0a858a6](https://linux-hardware.org/?probe=62a0a858a6) | Dec 24, 2021 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [d2ce6b29f7](https://linux-hardware.org/?probe=d2ce6b29f7) | Dec 23, 2021 |
| HP            | 3048h                       | Desktop     | [2e47687170](https://linux-hardware.org/?probe=2e47687170) | Dec 23, 2021 |
| HP            | ProBook 4740s               | Notebook    | [149c7edca2](https://linux-hardware.org/?probe=149c7edca2) | Dec 23, 2021 |
| ASRock        | Z77 Pro3                    | Desktop     | [da59408c08](https://linux-hardware.org/?probe=da59408c08) | Dec 22, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [72ba2d0d17](https://linux-hardware.org/?probe=72ba2d0d17) | Dec 22, 2021 |
| Lenovo        | 3176 SDK0J40697 WIN 3305... | Desktop     | [7ffa31df44](https://linux-hardware.org/?probe=7ffa31df44) | Dec 20, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [711a930635](https://linux-hardware.org/?probe=711a930635) | Dec 20, 2021 |
| Acer          | Aspire A315-31              | Notebook    | [a55ed0d992](https://linux-hardware.org/?probe=a55ed0d992) | Dec 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1f86ef0f23](https://linux-hardware.org/?probe=1f86ef0f23) | Dec 19, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [aa65cbb14e](https://linux-hardware.org/?probe=aa65cbb14e) | Dec 19, 2021 |
| HP            | 8056                        | Desktop     | [68992da248](https://linux-hardware.org/?probe=68992da248) | Dec 19, 2021 |
| Dell          | 0KWVT8 A02                  | Desktop     | [60db65ec3a](https://linux-hardware.org/?probe=60db65ec3a) | Dec 19, 2021 |
| HP            | 18E4                        | Desktop     | [b4a1d6b778](https://linux-hardware.org/?probe=b4a1d6b778) | Dec 19, 2021 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [3e25d6dd20](https://linux-hardware.org/?probe=3e25d6dd20) | Dec 18, 2021 |
| HP            | Pavilion dv7                | Notebook    | [e1ac371752](https://linux-hardware.org/?probe=e1ac371752) | Dec 18, 2021 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [6e8ba23594](https://linux-hardware.org/?probe=6e8ba23594) | Dec 16, 2021 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [70a9d341b1](https://linux-hardware.org/?probe=70a9d341b1) | Dec 16, 2021 |
| Dell          | Latitude E5410              | Notebook    | [433ad50dd3](https://linux-hardware.org/?probe=433ad50dd3) | Dec 16, 2021 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [d103baf427](https://linux-hardware.org/?probe=d103baf427) | Dec 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [0fc861a848](https://linux-hardware.org/?probe=0fc861a848) | Dec 16, 2021 |
| ASUSTek       | ZenBook UX481FLY_UX481FL    | Notebook    | [d680085d25](https://linux-hardware.org/?probe=d680085d25) | Dec 15, 2021 |
| Medion        | Cattle24 1M                 | Desktop     | [2d145ac87e](https://linux-hardware.org/?probe=2d145ac87e) | Dec 14, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c821efaed8](https://linux-hardware.org/?probe=c821efaed8) | Dec 14, 2021 |
| Dell          | Inspiron 16 7610            | Notebook    | [e0d697a356](https://linux-hardware.org/?probe=e0d697a356) | Dec 14, 2021 |
| Medion        | Cattle24 1M                 | Desktop     | [4fdfe223e0](https://linux-hardware.org/?probe=4fdfe223e0) | Dec 13, 2021 |
| Apple         | MacBookAir3,1               | Notebook    | [edebb4d39b](https://linux-hardware.org/?probe=edebb4d39b) | Dec 12, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [7abd85fdc5](https://linux-hardware.org/?probe=7abd85fdc5) | Dec 12, 2021 |
| ZOTAC         | ZBOX-EN1070/1060 Rev.00     | Mini pc     | [7348d34142](https://linux-hardware.org/?probe=7348d34142) | Dec 12, 2021 |
| HP            | 871A                        | Mini pc     | [fdbb17d3b2](https://linux-hardware.org/?probe=fdbb17d3b2) | Dec 12, 2021 |
| ASUSTek       | G75VW                       | Notebook    | [4fce5a6b3b](https://linux-hardware.org/?probe=4fce5a6b3b) | Dec 12, 2021 |
| ASUSTek       | N551JW                      | Notebook    | [95f2828cd6](https://linux-hardware.org/?probe=95f2828cd6) | Dec 12, 2021 |
| Intel         | DG965WH AAD41692-304        | Desktop     | [663a79c9de](https://linux-hardware.org/?probe=663a79c9de) | Dec 11, 2021 |
| Intel         | DG965WH AAD41692-304        | Desktop     | [4166d874cc](https://linux-hardware.org/?probe=4166d874cc) | Dec 11, 2021 |
| ASRock        | B560M-HDV                   | Desktop     | [6390e2db9b](https://linux-hardware.org/?probe=6390e2db9b) | Dec 09, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [892d6ba035](https://linux-hardware.org/?probe=892d6ba035) | Dec 09, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [cd20a94e3e](https://linux-hardware.org/?probe=cd20a94e3e) | Dec 08, 2021 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [fa1e8b87a6](https://linux-hardware.org/?probe=fa1e8b87a6) | Dec 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [1dba035790](https://linux-hardware.org/?probe=1dba035790) | Dec 07, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [64c5154edc](https://linux-hardware.org/?probe=64c5154edc) | Dec 07, 2021 |
| Acer          | Aspire E5-511               | Notebook    | [9e8fd519f0](https://linux-hardware.org/?probe=9e8fd519f0) | Dec 07, 2021 |
| Intel         | NUC8i7HNB J68197-600        | Mini pc     | [ca6047ef7c](https://linux-hardware.org/?probe=ca6047ef7c) | Dec 06, 2021 |
| HP            | ENVY dv7                    | Notebook    | [1ab140a424](https://linux-hardware.org/?probe=1ab140a424) | Dec 06, 2021 |
| Intel         | NUC8i7HNB J68197-600        | Mini pc     | [6a2129aabd](https://linux-hardware.org/?probe=6a2129aabd) | Dec 06, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [f454c30e46](https://linux-hardware.org/?probe=f454c30e46) | Dec 05, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [d78c027940](https://linux-hardware.org/?probe=d78c027940) | Dec 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [fc540c3951](https://linux-hardware.org/?probe=fc540c3951) | Dec 05, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [ce3d88a2a2](https://linux-hardware.org/?probe=ce3d88a2a2) | Dec 05, 2021 |
| ASUSTek       | ZenBook Pro Duo UX582LR_... | Notebook    | [26964d4c51](https://linux-hardware.org/?probe=26964d4c51) | Dec 04, 2021 |
| Razer         | Blade Stealth               | Notebook    | [03738c7e11](https://linux-hardware.org/?probe=03738c7e11) | Dec 04, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [585c81c884](https://linux-hardware.org/?probe=585c81c884) | Dec 04, 2021 |
| HP            | ProBook 450 G4              | Notebook    | [0cc317d213](https://linux-hardware.org/?probe=0cc317d213) | Dec 04, 2021 |
| ASUSTek       | STRIX Z270G GAMING          | Desktop     | [0e777fade8](https://linux-hardware.org/?probe=0e777fade8) | Dec 03, 2021 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [e2e7015852](https://linux-hardware.org/?probe=e2e7015852) | Dec 03, 2021 |
| Unknown       | 1.0                         | Desktop     | [412614529f](https://linux-hardware.org/?probe=412614529f) | Dec 02, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [74dcac77ec](https://linux-hardware.org/?probe=74dcac77ec) | Dec 01, 2021 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | Desktop     | [9bbe9ad940](https://linux-hardware.org/?probe=9bbe9ad940) | Nov 27, 2021 |
| Lenovo        | G50-70 20351                | Notebook    | [6de772fed7](https://linux-hardware.org/?probe=6de772fed7) | Nov 27, 2021 |
| Unknown       | Unknown                     | Desktop     | [3b55838cb6](https://linux-hardware.org/?probe=3b55838cb6) | Nov 27, 2021 |
| Gigabyte      | EP45-DS3                    | Desktop     | [b7cb8d0193](https://linux-hardware.org/?probe=b7cb8d0193) | Nov 27, 2021 |
| Lenovo        | Yoga 730-13IKB 81CT         | Convertible | [b1147db572](https://linux-hardware.org/?probe=b1147db572) | Nov 27, 2021 |
| MSI           | MS-17G                      | Notebook    | [0fd0763f15](https://linux-hardware.org/?probe=0fd0763f15) | Nov 26, 2021 |
| MSI           | MS-17G                      | Notebook    | [00c3cd9a83](https://linux-hardware.org/?probe=00c3cd9a83) | Nov 26, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [fbec23b579](https://linux-hardware.org/?probe=fbec23b579) | Nov 26, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [51d432b698](https://linux-hardware.org/?probe=51d432b698) | Nov 26, 2021 |
| Polaroid      | MP1464PR001                 | Notebook    | [6475eec282](https://linux-hardware.org/?probe=6475eec282) | Nov 25, 2021 |
| Polaroid      | MP1464PR001                 | Notebook    | [244042f0d1](https://linux-hardware.org/?probe=244042f0d1) | Nov 25, 2021 |
| MSI           | X99A SLI PLUS               | Desktop     | [6c1248588e](https://linux-hardware.org/?probe=6c1248588e) | Nov 24, 2021 |
| MSI           | X99A SLI PLUS               | Desktop     | [4ae4bcc876](https://linux-hardware.org/?probe=4ae4bcc876) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [2fbb75de6f](https://linux-hardware.org/?probe=2fbb75de6f) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP40... | Convertible | [c70684a5e6](https://linux-hardware.org/?probe=c70684a5e6) | Nov 24, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [ab7e1ab2f6](https://linux-hardware.org/?probe=ab7e1ab2f6) | Nov 23, 2021 |
| ASUSTek       | P8P67 LE                    | Desktop     | [0a637eba53](https://linux-hardware.org/?probe=0a637eba53) | Nov 23, 2021 |
| Lenovo        | ThinkPad P53 20QN000SMZ     | Notebook    | [bf8a290d91](https://linux-hardware.org/?probe=bf8a290d91) | Nov 23, 2021 |
| Lenovo        | ThinkPad P53 20QN000SMZ     | Notebook    | [3b2959cf2d](https://linux-hardware.org/?probe=3b2959cf2d) | Nov 23, 2021 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [91a66a7648](https://linux-hardware.org/?probe=91a66a7648) | Nov 22, 2021 |
| Microsoft     | Surface Pro 7               | Tablet      | [4c05633d40](https://linux-hardware.org/?probe=4c05633d40) | Nov 22, 2021 |
| HP            | Notebook                    | Notebook    | [9e9ce14e95](https://linux-hardware.org/?probe=9e9ce14e95) | Nov 22, 2021 |
| Lenovo        | ThinkPad X250 20CM004UGE    | Notebook    | [26bd0cd883](https://linux-hardware.org/?probe=26bd0cd883) | Nov 22, 2021 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [c0960ee402](https://linux-hardware.org/?probe=c0960ee402) | Nov 21, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ec72611685](https://linux-hardware.org/?probe=ec72611685) | Nov 21, 2021 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [80d0bc77b6](https://linux-hardware.org/?probe=80d0bc77b6) | Nov 20, 2021 |
| Dell          | Latitude E7440              | Notebook    | [a4581f0839](https://linux-hardware.org/?probe=a4581f0839) | Nov 20, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [fa7d35906a](https://linux-hardware.org/?probe=fa7d35906a) | Nov 19, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [69a210799e](https://linux-hardware.org/?probe=69a210799e) | Nov 19, 2021 |
| HP            | ProLiant ML350 Gen9         | Desktop     | [9a5ec34f4b](https://linux-hardware.org/?probe=9a5ec34f4b) | Nov 18, 2021 |
| ASUSTek       | Z87-DELUXE                  | Desktop     | [b858dc4d83](https://linux-hardware.org/?probe=b858dc4d83) | Nov 18, 2021 |
| Google        | Lars                        | Notebook    | [c346746b7e](https://linux-hardware.org/?probe=c346746b7e) | Nov 18, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [701785b28a](https://linux-hardware.org/?probe=701785b28a) | Nov 17, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [2fd9cf16d9](https://linux-hardware.org/?probe=2fd9cf16d9) | Nov 17, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [2984f10b43](https://linux-hardware.org/?probe=2984f10b43) | Nov 16, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [2067df0e1e](https://linux-hardware.org/?probe=2067df0e1e) | Nov 16, 2021 |
| Acer          | Aspire V3-772G              | Notebook    | [1e66881588](https://linux-hardware.org/?probe=1e66881588) | Nov 16, 2021 |
| HP            | ZBook 15 G2                 | Notebook    | [f40c4458aa](https://linux-hardware.org/?probe=f40c4458aa) | Nov 16, 2021 |
| Microsoft     | Surface Pro 7               | Tablet      | [8facfa8bce](https://linux-hardware.org/?probe=8facfa8bce) | Nov 15, 2021 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [d193380f1d](https://linux-hardware.org/?probe=d193380f1d) | Nov 15, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [098387cb9c](https://linux-hardware.org/?probe=098387cb9c) | Nov 15, 2021 |
| Dell          | Latitude E7240              | Notebook    | [aaf6395a70](https://linux-hardware.org/?probe=aaf6395a70) | Nov 14, 2021 |
| MSI           | A320M-A PRO MAX             | Desktop     | [09a1713d46](https://linux-hardware.org/?probe=09a1713d46) | Nov 14, 2021 |
| Dell          | Latitude E7270              | Notebook    | [b462d15a6b](https://linux-hardware.org/?probe=b462d15a6b) | Nov 14, 2021 |
| HP            | EliteBook 735 G5            | Notebook    | [79600db29f](https://linux-hardware.org/?probe=79600db29f) | Nov 14, 2021 |
| Microsoft     | Surface Pro 4               | Tablet      | [30b1c49250](https://linux-hardware.org/?probe=30b1c49250) | Nov 13, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [a283cb744b](https://linux-hardware.org/?probe=a283cb744b) | Nov 13, 2021 |
| HP            | Pavilion 15                 | Notebook    | [366558c9a6](https://linux-hardware.org/?probe=366558c9a6) | Nov 11, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [18391015f7](https://linux-hardware.org/?probe=18391015f7) | Nov 11, 2021 |
| Dell          | 0KC9NP A01                  | Desktop     | [20898da2a5](https://linux-hardware.org/?probe=20898da2a5) | Nov 10, 2021 |
| ASRock        | Z370 Pro4                   | Desktop     | [e0856ca7fa](https://linux-hardware.org/?probe=e0856ca7fa) | Nov 10, 2021 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | Notebook    | [f9f140b132](https://linux-hardware.org/?probe=f9f140b132) | Nov 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [3876a60641](https://linux-hardware.org/?probe=3876a60641) | Nov 10, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [92b50813ac](https://linux-hardware.org/?probe=92b50813ac) | Nov 10, 2021 |
| Lenovo        | ThinkPad T440p 20AWS18U0... | Notebook    | [258574fc87](https://linux-hardware.org/?probe=258574fc87) | Nov 10, 2021 |
| Intel         | DH77DF AAG40293-300         | Desktop     | [64ba244f45](https://linux-hardware.org/?probe=64ba244f45) | Nov 09, 2021 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [e0d50907c2](https://linux-hardware.org/?probe=e0d50907c2) | Nov 07, 2021 |
| ASUSTek       | UX430UNR                    | Notebook    | [292992ce5a](https://linux-hardware.org/?probe=292992ce5a) | Nov 07, 2021 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [e4a203dda2](https://linux-hardware.org/?probe=e4a203dda2) | Nov 07, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [6f9b7bffd1](https://linux-hardware.org/?probe=6f9b7bffd1) | Nov 06, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [6f308039a8](https://linux-hardware.org/?probe=6f308039a8) | Nov 06, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [86f84e606c](https://linux-hardware.org/?probe=86f84e606c) | Nov 05, 2021 |
| Acer          | V3-771                      | Notebook    | [bf99ad481c](https://linux-hardware.org/?probe=bf99ad481c) | Nov 04, 2021 |
| ASUSTek       | A85XM-A                     | Desktop     | [f28dea1e67](https://linux-hardware.org/?probe=f28dea1e67) | Nov 03, 2021 |
| ASUSTek       | U36SD                       | Notebook    | [84e47bb477](https://linux-hardware.org/?probe=84e47bb477) | Nov 03, 2021 |
| ASUSTek       | ROG ZENITH II EXTREME       | Desktop     | [5fabc60d11](https://linux-hardware.org/?probe=5fabc60d11) | Nov 03, 2021 |
| HP            | 1494                        | Desktop     | [ef0237e3cf](https://linux-hardware.org/?probe=ef0237e3cf) | Nov 03, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [bc49b41641](https://linux-hardware.org/?probe=bc49b41641) | Nov 03, 2021 |
| PC Special... | NH5x_7xRCx,RDx              | Notebook    | [8686d92d45](https://linux-hardware.org/?probe=8686d92d45) | Nov 03, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | Notebook    | [7205a2ab55](https://linux-hardware.org/?probe=7205a2ab55) | Nov 03, 2021 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [6c7ecc284b](https://linux-hardware.org/?probe=6c7ecc284b) | Oct 31, 2021 |
| ASUSTek       | P6T DELUXE                  | Desktop     | [f35cfefa93](https://linux-hardware.org/?probe=f35cfefa93) | Oct 31, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [3f7a2585fe](https://linux-hardware.org/?probe=3f7a2585fe) | Oct 31, 2021 |
| ASUSTek       | ROG Zephyrus G15 GA503QS... | Notebook    | [e6958a71d6](https://linux-hardware.org/?probe=e6958a71d6) | Oct 31, 2021 |
| Acer          | TravelMate P459-G2-MG       | Notebook    | [05087f89c1](https://linux-hardware.org/?probe=05087f89c1) | Oct 30, 2021 |
| Lenovo        | ThinkPad T480s 20L70026U... | Notebook    | [eeb181f50b](https://linux-hardware.org/?probe=eeb181f50b) | Oct 30, 2021 |
| Acer          | TravelMate P459-G2-MG       | Notebook    | [4a80b949aa](https://linux-hardware.org/?probe=4a80b949aa) | Oct 30, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [d0307fd66e](https://linux-hardware.org/?probe=d0307fd66e) | Oct 29, 2021 |
| HP            | 1998                        | Desktop     | [f943d839a8](https://linux-hardware.org/?probe=f943d839a8) | Oct 29, 2021 |
| HP            | EliteBook 840 G6            | Notebook    | [a5abf5d5ee](https://linux-hardware.org/?probe=a5abf5d5ee) | Oct 29, 2021 |
| Gigabyte      | X570 AORUS PRO              | Desktop     | [fbd2076eee](https://linux-hardware.org/?probe=fbd2076eee) | Oct 28, 2021 |
| Medion        | S3409 MD60234               | Notebook    | [4bb4415dae](https://linux-hardware.org/?probe=4bb4415dae) | Oct 27, 2021 |
| Acer          | Aspire X3450                | Desktop     | [8f27aff70b](https://linux-hardware.org/?probe=8f27aff70b) | Oct 27, 2021 |
| Supermicro    | X9DR3-F                     | Desktop     | [6908407322](https://linux-hardware.org/?probe=6908407322) | Oct 26, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0B80... | Notebook    | [a567978a3c](https://linux-hardware.org/?probe=a567978a3c) | Oct 26, 2021 |
| Acer          | V3-771                      | Notebook    | [b953b67d06](https://linux-hardware.org/?probe=b953b67d06) | Oct 25, 2021 |
| TUXEDO        | BC1510 1710                 | Notebook    | [90be7d16be](https://linux-hardware.org/?probe=90be7d16be) | Oct 24, 2021 |
| TUXEDO        | BC1510 1710                 | Notebook    | [49b52175c5](https://linux-hardware.org/?probe=49b52175c5) | Oct 24, 2021 |
| Pegatron      | 2AB5                        | Desktop     | [d19235c3d0](https://linux-hardware.org/?probe=d19235c3d0) | Oct 24, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [681b537e82](https://linux-hardware.org/?probe=681b537e82) | Oct 23, 2021 |
| ASUSTek       | SABERTOOTH Z170 MARK 1      | Desktop     | [fca2aa4310](https://linux-hardware.org/?probe=fca2aa4310) | Oct 23, 2021 |
| Packard Be... | EasyNote TV44HC             | Notebook    | [5ebedd4a1c](https://linux-hardware.org/?probe=5ebedd4a1c) | Oct 23, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d53c49a17f](https://linux-hardware.org/?probe=d53c49a17f) | Oct 23, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [117223995c](https://linux-hardware.org/?probe=117223995c) | Oct 23, 2021 |
| Dell          | 0KRC95 A00                  | Desktop     | [e97646cc2e](https://linux-hardware.org/?probe=e97646cc2e) | Oct 23, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Switzerland/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 294       | 14.64%  |
| Ubuntu 18.04                 | 271       | 13.5%   |
| Ubuntu 22.04                 | 76        | 3.78%   |
| Debian 11                    | 75        | 3.74%   |
| Linux Mint 20.3              | 48        | 2.39%   |
| OpenMandriva 4.3             | 41        | 2.04%   |
| Debian 10                    | 40        | 1.99%   |
| Ubuntu 21.10                 | 38        | 1.89%   |
| KDE neon 20.04               | 36        | 1.79%   |
| Linux Mint 20.2              | 35        | 1.74%   |
| Linux Mint 20.1              | 35        | 1.74%   |
| openSUSE Tumbleweed-XXXXXXXX | 30        | 1.49%   |
| OpenMandriva 4.2             | 30        | 1.49%   |
| Arch                         | 28        | 1.39%   |
| Ubuntu 20.10                 | 25        | 1.25%   |
| Fedora 32                    | 24        | 1.2%    |
| Arch Rolling                 | 24        | 1.2%    |
| Ubuntu 21.04                 | 22        | 1.1%    |
| Pop!_OS 22.04                | 22        | 1.1%    |
| Ubuntu 19.10                 | 21        | 1.05%   |
| Pop!_OS 21.04                | 21        | 1.05%   |
| Pop!_OS 20.04                | 21        | 1.05%   |
| Fedora 33                    | 21        | 1.05%   |
| Ubuntu 19.04                 | 20        | 1%      |
| Pop!_OS 20.10                | 20        | 1%      |
| Manjaro                      | 20        | 1%      |
| Fedora 35                    | 20        | 1%      |
| Fedora 34                    | 20        | 1%      |
| ArcoLinux Rolling            | 20        | 1%      |
| Zorin 16                     | 19        | 0.95%   |
| Linux Mint 19.3              | 18        | 0.9%    |
| Fedora 36                    | 16        | 0.8%    |
| Zorin 15                     | 15        | 0.75%   |
| Kubuntu 20.04                | 15        | 0.75%   |
| Fedora 37                    | 15        | 0.75%   |
| Ubuntu 22.10                 | 14        | 0.7%    |
| OpenMandriva 23.01           | 14        | 0.7%    |
| Linux Mint 20                | 14        | 0.7%    |
| Linux Mint 21                | 13        | 0.65%   |
| Fedora 31                    | 13        | 0.65%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 741       | 39.56%  |
| Linux Mint    | 158       | 8.44%   |
| Debian        | 139       | 7.42%   |
| Fedora        | 122       | 6.51%   |
| OpenMandriva  | 97        | 5.18%   |
| Pop!_OS       | 85        | 4.54%   |
| Manjaro       | 59        | 3.15%   |
| Arch          | 51        | 2.72%   |
| Kubuntu       | 42        | 2.24%   |
| openSUSE      | 39        | 2.08%   |
| KDE neon      | 39        | 2.08%   |
| Zorin         | 34        | 1.82%   |
| ROSA          | 25        | 1.33%   |
| ArcoLinux     | 23        | 1.23%   |
| Xubuntu       | 18        | 0.96%   |
| Ubuntu MATE   | 17        | 0.91%   |
| Gentoo        | 16        | 0.85%   |
| Kali          | 14        | 0.75%   |
| Elementary    | 14        | 0.75%   |
| Lubuntu       | 13        | 0.69%   |
| CentOS        | 12        | 0.64%   |
| Ubuntu Budgie | 10        | 0.53%   |
| Feren OS      | 10        | 0.53%   |
| Clear Linux   | 8         | 0.43%   |
| Ubuntu Unity  | 7         | 0.37%   |
| LMDE          | 7         | 0.37%   |
| Endless       | 7         | 0.37%   |
| BlackPanther  | 7         | 0.37%   |
| EndeavourOS   | 6         | 0.32%   |
| RHEL          | 4         | 0.21%   |
| MX            | 4         | 0.21%   |
| Artix         | 4         | 0.21%   |
| Void Linux    | 3         | 0.16%   |
| Virtuozzo     | 3         | 0.16%   |
| Solus         | 3         | 0.16%   |
| NixOS         | 3         | 0.16%   |
| Q4OS          | 2         | 0.11%   |
| PCS           | 2         | 0.11%   |
| Parrot        | 2         | 0.11%   |
| Manjaro-ARM   | 2         | 0.11%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 4.15.0-88-generic        | 44        | 1.95%   |
| 5.16.7-desktop-1omv4003  | 37        | 1.64%   |
| 5.4.0-42-generic         | 32        | 1.42%   |
| 5.10.14-desktop-1omv4002 | 29        | 1.28%   |
| 4.15.0-91-generic        | 27        | 1.2%    |
| 5.15.0-56-generic        | 24        | 1.06%   |
| 5.4.0-52-generic         | 22        | 0.97%   |
| 5.4.0-48-generic         | 22        | 0.97%   |
| 4.15.0-96-generic        | 22        | 0.97%   |
| 5.4.0-58-generic         | 21        | 0.93%   |
| 5.15.0-46-generic        | 17        | 0.75%   |
| 5.10.0-8-arm64           | 17        | 0.75%   |
| 5.8.0-43-generic         | 15        | 0.66%   |
| 5.4.0-91-generic         | 15        | 0.66%   |
| 6.1.1-desktop-1omv2290   | 14        | 0.62%   |
| 5.13.0-35-generic        | 14        | 0.62%   |
| 5.4.0-80-generic         | 13        | 0.58%   |
| 5.4.0-26-generic         | 13        | 0.58%   |
| 5.15.0-52-generic        | 13        | 0.58%   |
| 5.11.0-43-generic        | 13        | 0.58%   |
| 5.11.0-27-generic        | 13        | 0.58%   |
| 5.4.0-81-generic         | 12        | 0.53%   |
| 5.4.0-47-generic         | 12        | 0.53%   |
| 5.15.0-48-generic        | 12        | 0.53%   |
| 5.13.0-39-generic        | 12        | 0.53%   |
| 5.13.0-30-generic        | 12        | 0.53%   |
| 5.10.0-8-amd64           | 12        | 0.53%   |
| 5.0.0-37-generic         | 12        | 0.53%   |
| 5.8.0-55-generic         | 11        | 0.49%   |
| 5.8.0-53-generic         | 11        | 0.49%   |
| 5.8.0-48-generic         | 11        | 0.49%   |
| 5.8.0-44-generic         | 11        | 0.49%   |
| 5.4.0-72-generic         | 11        | 0.49%   |
| 5.4.0-66-generic         | 11        | 0.49%   |
| 5.8.0-59-generic         | 10        | 0.44%   |
| 5.4.0-70-generic         | 10        | 0.44%   |
| 5.4.0-65-generic         | 10        | 0.44%   |
| 5.4.0-37-generic         | 10        | 0.44%   |
| 5.4.0-29-generic         | 10        | 0.44%   |
| 5.3.0-51-generic         | 10        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 364       | 17.35%  |
| 4.15.0  | 205       | 9.77%   |
| 5.15.0  | 143       | 6.82%   |
| 5.8.0   | 127       | 6.05%   |
| 5.11.0  | 117       | 5.58%   |
| 5.13.0  | 104       | 4.96%   |
| 5.10.0  | 78        | 3.72%   |
| 5.3.0   | 72        | 3.43%   |
| 5.0.0   | 50        | 2.38%   |
| 4.18.0  | 41        | 1.95%   |
| 5.16.7  | 38        | 1.81%   |
| 4.19.0  | 37        | 1.76%   |
| 5.10.14 | 30        | 1.43%   |
| 5.19.0  | 22        | 1.05%   |
| 6.1.1   | 18        | 0.86%   |
| 5.14.0  | 15        | 0.71%   |
| 5.17.5  | 13        | 0.62%   |
| 5.6.0   | 11        | 0.52%   |
| 6.0.0   | 9         | 0.43%   |
| 5.7.0   | 9         | 0.43%   |
| 5.18.0  | 9         | 0.43%   |
| 3.10.0  | 8         | 0.38%   |
| 5.16.13 | 7         | 0.33%   |
| 5.10.7  | 7         | 0.33%   |
| 4.9.60  | 7         | 0.33%   |
| 6.0.15  | 6         | 0.29%   |
| 5.6.14  | 6         | 0.29%   |
| 5.16.0  | 6         | 0.29%   |
| 4.18.16 | 6         | 0.29%   |
| 5.9.16  | 5         | 0.24%   |
| 5.9.11  | 5         | 0.24%   |
| 5.7.1   | 5         | 0.24%   |
| 5.6.15  | 5         | 0.24%   |
| 5.3.18  | 5         | 0.24%   |
| 5.15.5  | 5         | 0.24%   |
| 5.14.14 | 5         | 0.24%   |
| 5.11.2  | 5         | 0.24%   |
| 5.11.16 | 5         | 0.24%   |
| 4.9.20  | 5         | 0.24%   |
| 6.1.0   | 4         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 383       | 18.59%  |
| 4.15    | 206       | 10%     |
| 5.15    | 192       | 9.32%   |
| 5.8     | 160       | 7.77%   |
| 5.10    | 148       | 7.18%   |
| 5.11    | 146       | 7.09%   |
| 5.13    | 121       | 5.87%   |
| 5.3     | 84        | 4.08%   |
| 5.16    | 73        | 3.54%   |
| 5.0     | 55        | 2.67%   |
| 4.18    | 49        | 2.38%   |
| 4.19    | 44        | 2.14%   |
| 5.6     | 41        | 1.99%   |
| 6.0     | 40        | 1.94%   |
| 5.14    | 36        | 1.75%   |
| 5.19    | 35        | 1.7%    |
| 5.17    | 35        | 1.7%    |
| 5.9     | 29        | 1.41%   |
| 5.7     | 29        | 1.41%   |
| 5.18    | 28        | 1.36%   |
| 5.12    | 25        | 1.21%   |
| 6.1     | 23        | 1.12%   |
| 4.9     | 23        | 1.12%   |
| 5.5     | 11        | 0.53%   |
| 3.10    | 8         | 0.39%   |
| 4.4     | 5         | 0.24%   |
| 4.14    | 4         | 0.19%   |
| 5.2     | 3         | 0.15%   |
| 4.20    | 3         | 0.15%   |
| 4.13    | 3         | 0.15%   |
| 4.1     | 3         | 0.15%   |
| 2.6     | 3         | 0.15%   |
| 4.10    | 2         | 0.1%    |
| 3.16    | 2         | 0.1%    |
| 5.1     | 1         | 0.05%   |
| 5       | 1         | 0.05%   |
| 4.2     | 1         | 0.05%   |
| 4.16    | 1         | 0.05%   |
| 4.12    | 1         | 0.05%   |
| 3.4     | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1739      | 96.18%  |
| aarch64 | 36        | 1.99%   |
| i686    | 31        | 1.71%   |
| armv8l  | 1         | 0.06%   |
| armv7l  | 1         | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 750       | 39.64%  |
| Unknown         | 294       | 15.54%  |
| KDE5            | 271       | 14.32%  |
| X-Cinnamon      | 127       | 6.71%   |
| GNUstep         | 113       | 5.97%   |
| XFCE            | 86        | 4.55%   |
| MATE            | 46        | 2.43%   |
| KDE             | 43        | 2.27%   |
| Cinnamon        | 32        | 1.69%   |
| LXQt            | 19        | 1%      |
| KDE4            | 16        | 0.85%   |
| Pantheon        | 15        | 0.79%   |
| Budgie          | 15        | 0.79%   |
| LXDE            | 13        | 0.69%   |
| i3              | 12        | 0.63%   |
| GNOME Flashback | 11        | 0.58%   |
| Unity           | 6         | 0.32%   |
| bspwm           | 5         | 0.26%   |
| qtile           | 4         | 0.21%   |
| Trinity         | 2         | 0.11%   |
| sway            | 2         | 0.11%   |
| GNOME Classic   | 2         | 0.11%   |
| DWM             | 2         | 0.11%   |
| xmonad          | 1         | 0.05%   |
| openbox         | 1         | 0.05%   |
| none+awesome    | 1         | 0.05%   |
| ICEWM           | 1         | 0.05%   |
| herbstluftwm    | 1         | 0.05%   |
| fluxbox         | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1347      | 71.31%  |
| Wayland | 300       | 15.88%  |
| Unknown | 164       | 8.68%   |
| Tty     | 75        | 3.97%   |
| Web     | 3         | 0.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 844       | 44.54%  |
| LightDM | 305       | 16.09%  |
| SDDM    | 244       | 12.88%  |
| GDM     | 243       | 12.82%  |
| GDM3    | 156       | 8.23%   |
| TDM     | 80        | 4.22%   |
| KDM     | 15        | 0.79%   |
| XDM     | 4         | 0.21%   |
| SLiM    | 2         | 0.11%   |
| LXDM    | 1         | 0.05%   |
| GREETD  | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| en_US      | 605       | 32.37%  |
| de_CH      | 422       | 22.58%  |
| Unknown    | 348       | 18.62%  |
| fr_CH      | 126       | 6.74%   |
| de_DE      | 115       | 6.15%   |
| en_GB      | 75        | 4.01%   |
| fr_FR      | 39        | 2.09%   |
| C          | 38        | 2.03%   |
| pt_PT      | 17        | 0.91%   |
| it_CH      | 17        | 0.91%   |
| it_IT      | 14        | 0.75%   |
| es_ES      | 7         | 0.37%   |
| ru_RU      | 6         | 0.32%   |
| pl_PL      | 6         | 0.32%   |
| en_CH      | 6         | 0.32%   |
| en_AU      | 4         | 0.21%   |
| POSIX      | 3         | 0.16%   |
| en_IE      | 3         | 0.16%   |
| de_AT      | 3         | 0.16%   |
| en_CA      | 2         | 0.11%   |
| tr_TR      | 1         | 0.05%   |
| sk_SK      | 1         | 0.05%   |
| ru_UA      | 1         | 0.05%   |
| nl_BE      | 1         | 0.05%   |
| hu_HU      | 1         | 0.05%   |
| gsw_CH     | 1         | 0.05%   |
| en_AG      | 1         | 0.05%   |
| de_LI      | 1         | 0.05%   |
| de_IT      | 1         | 0.05%   |
| de_CH.UTF8 | 1         | 0.05%   |
| cs_CZ      | 1         | 0.05%   |
| ca_ES      | 1         | 0.05%   |
| C.UTF8     | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 991       | 53.83%  |
| BIOS | 850       | 46.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1456      | 78.96%  |
| Btrfs   | 137       | 7.43%   |
| Overlay | 122       | 6.62%   |
| Unknown | 64        | 3.47%   |
| Xfs     | 38        | 2.06%   |
| Zfs     | 11        | 0.6%    |
| Ext2    | 6         | 0.33%   |
| F2fs    | 4         | 0.22%   |
| Ext3    | 3         | 0.16%   |
| Jfs     | 1         | 0.05%   |
| ExX4    | 1         | 0.05%   |
| Aufs    | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 868       | 47%     |
| GPT     | 765       | 41.42%  |
| MBR     | 214       | 11.59%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1551      | 84.11%  |
| Yes       | 293       | 15.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1379      | 74.99%  |
| Yes       | 460       | 25.01%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Hewlett-Packard         | 314       | 17.39%  |
| ASUSTek Computer        | 307       | 17%     |
| Lenovo                  | 284       | 15.73%  |
| Dell                    | 146       | 8.08%   |
| Acer                    | 107       | 5.92%   |
| Gigabyte Technology     | 84        | 4.65%   |
| Apple                   | 64        | 3.54%   |
| MSI                     | 63        | 3.49%   |
| Intel                   | 62        | 3.43%   |
| ASRock                  | 55        | 3.05%   |
| Fujitsu                 | 33        | 1.83%   |
| Raspberry Pi Foundation | 31        | 1.72%   |
| Medion                  | 23        | 1.27%   |
| Supermicro              | 19        | 1.05%   |
| Toshiba                 | 17        | 0.94%   |
| Sony                    | 13        | 0.72%   |
| Microsoft               | 13        | 0.72%   |
| TUXEDO                  | 11        | 0.61%   |
| Notebook                | 11        | 0.61%   |
| Unknown                 | 11        | 0.61%   |
| Samsung Electronics     | 10        | 0.55%   |
| Shuttle                 | 9         | 0.5%    |
| HUAWEI                  | 9         | 0.5%    |
| ZOTAC                   | 8         | 0.44%   |
| TrekStor                | 7         | 0.39%   |
| Pegatron                | 7         | 0.39%   |
| PC Engines              | 7         | 0.39%   |
| Razer                   | 6         | 0.33%   |
| DALCO AG Switzerland    | 6         | 0.33%   |
| Alienware               | 5         | 0.28%   |
| Schenker                | 4         | 0.22%   |
| Packard Bell            | 4         | 0.22%   |
| GPD                     | 3         | 0.17%   |
| Clevo                   | 3         | 0.17%   |
| Biostar                 | 3         | 0.17%   |
| whyopencomputing        | 2         | 0.11%   |
| Timi                    | 2         | 0.11%   |
| System76                | 2         | 0.11%   |
| PC Specialist           | 2         | 0.11%   |
| MPMAN                   | 2         | 0.11%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| ASUS All Series                       | 32        | 1.77%   |
| Unknown                               | 18        | 1%      |
| Fujitsu CELSIUS_W550                  | 12        | 0.66%   |
| RPi Raspberry Pi 4 Model B Rev 1.2    | 9         | 0.5%    |
| RPi Raspberry Pi 4 Model B Rev 1.1    | 8         | 0.44%   |
| RPi Raspberry Pi 3 Model B Rev 1.2    | 8         | 0.44%   |
| ASUS ROG STRIX X570-E GAMING          | 8         | 0.44%   |
| HP Pavilion dv7                       | 7         | 0.39%   |
| ASUS STRIX Z270F GAMING               | 7         | 0.39%   |
| ASUS P9X79 WS                         | 7         | 0.39%   |
| ASUS P8Z77-V LX                       | 7         | 0.39%   |
| MSI MS-7C02                           | 6         | 0.33%   |
| Microsoft Surface Pro 4               | 6         | 0.33%   |
| DALCO AG Switzerland +41 44 908 38 38 | 6         | 0.33%   |
| PC Engines APU2                       | 5         | 0.28%   |
| Intel DP67BA AAG10219-303             | 5         | 0.28%   |
| HP Notebook                           | 5         | 0.28%   |
| HP ENVY 15                            | 5         | 0.28%   |
| HP EliteDesk 800 G1 SFF               | 5         | 0.28%   |
| Dell XPS 15 9570                      | 5         | 0.28%   |
| Dell Latitude E7240                   | 5         | 0.28%   |
| Dell Latitude 7490                    | 5         | 0.28%   |
| ASUS ROG STRIX Z370-F GAMING          | 5         | 0.28%   |
| Apple iMac8,1                         | 5         | 0.28%   |
| Apple iMac12,2                        | 5         | 0.28%   |
| Supermicro X8DTN+-F                   | 4         | 0.22%   |
| Lenovo MIIX 310-10ICR 80SG            | 4         | 0.22%   |
| Intel S4600LH                         | 4         | 0.22%   |
| Intel NUC8i7BEH                       | 4         | 0.22%   |
| Intel DP55WB AAE64798-207             | 4         | 0.22%   |
| HP ProBook 440 G8 Notebook PC         | 4         | 0.22%   |
| HP Pavilion g7                        | 4         | 0.22%   |
| HP Pavilion dv6                       | 4         | 0.22%   |
| HP Laptop 15-bs1xx                    | 4         | 0.22%   |
| HP ENVY x360 Convertible 15-ee0xxx    | 4         | 0.22%   |
| HP EliteBook Folio 1040 G1            | 4         | 0.22%   |
| Gigabyte X570 AORUS ELITE             | 4         | 0.22%   |
| Gigabyte H97-HD3                      | 4         | 0.22%   |
| Fujitsu CELSIUS W570                  | 4         | 0.22%   |
| Dell XPS 15 9560                      | 4         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 183       | 10.13%  |
| Acer Aspire        | 64        | 3.54%   |
| HP EliteBook       | 57        | 3.16%   |
| HP Pavilion        | 51        | 2.82%   |
| ASUS ROG           | 51        | 2.82%   |
| Dell XPS           | 43        | 2.38%   |
| Dell Latitude      | 41        | 2.27%   |
| HP ProBook         | 33        | 1.83%   |
| ASUS All           | 32        | 1.77%   |
| RPi Raspberry      | 31        | 1.72%   |
| HP ENVY            | 31        | 1.72%   |
| ASUS PRIME         | 30        | 1.66%   |
| Lenovo Yoga        | 27        | 1.5%    |
| Dell OptiPlex      | 27        | 1.5%    |
| HP Compaq          | 25        | 1.38%   |
| Fujitsu CELSIUS    | 25        | 1.38%   |
| HP EliteDesk       | 23        | 1.27%   |
| Unknown            | 18        | 1%      |
| Lenovo IdeaPad     | 17        | 0.94%   |
| HP Laptop          | 17        | 0.94%   |
| Dell Inspiron      | 14        | 0.78%   |
| ASUS TUF           | 14        | 0.78%   |
| Microsoft Surface  | 13        | 0.72%   |
| Acer Swift         | 13        | 0.72%   |
| ASUS VivoBook      | 12        | 0.66%   |
| Toshiba Satellite  | 11        | 0.61%   |
| HP ZBook           | 11        | 0.61%   |
| Dell Precision     | 11        | 0.61%   |
| ASUS ZenBook       | 11        | 0.61%   |
| Gigabyte X570      | 9         | 0.5%    |
| Lenovo ThinkCentre | 8         | 0.44%   |
| HP Spectre         | 8         | 0.44%   |
| HP ProLiant        | 8         | 0.44%   |
| HP ProDesk         | 8         | 0.44%   |
| ASUS STRIX         | 8         | 0.44%   |
| ASUS P9X79         | 8         | 0.44%   |
| ASUS P8Z77-V       | 8         | 0.44%   |
| Apple iMac12       | 7         | 0.39%   |
| Acer Predator      | 7         | 0.39%   |
| Razer Blade        | 6         | 0.33%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 199       | 11.02%  |
| 2019    | 189       | 10.47%  |
| 2020    | 164       | 9.08%   |
| 2017    | 157       | 8.69%   |
| 2012    | 141       | 7.81%   |
| 2011    | 125       | 6.92%   |
| 2013    | 115       | 6.37%   |
| 2015    | 110       | 6.09%   |
| 2014    | 107       | 5.92%   |
| 2021    | 103       | 5.7%    |
| 2010    | 87        | 4.82%   |
| 2016    | 86        | 4.76%   |
| 2008    | 58        | 3.21%   |
| 2009    | 50        | 2.77%   |
| 2022    | 33        | 1.83%   |
| 2007    | 32        | 1.77%   |
| Unknown | 25        | 1.38%   |
| 2006    | 15        | 0.83%   |
| 2005    | 6         | 0.33%   |
| 2004    | 3         | 0.17%   |
| 2003    | 1         | 0.06%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 832       | 46.07%  |
| Desktop        | 682       | 37.76%  |
| Convertible    | 95        | 5.26%   |
| Mini pc        | 49        | 2.71%   |
| Server         | 44        | 2.44%   |
| System on chip | 35        | 1.94%   |
| All in one     | 35        | 1.94%   |
| Tablet         | 31        | 1.72%   |
| Phone          | 3         | 0.17%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1655      | 90.73%  |
| Enabled  | 169       | 9.27%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1793      | 99.28%  |
| Yes  | 13        | 0.72%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 471       | 25.61%  |
| 4.01-8.0        | 311       | 16.91%  |
| 8.01-16.0       | 296       | 16.1%   |
| 32.01-64.0      | 283       | 15.39%  |
| 3.01-4.0        | 235       | 12.78%  |
| 64.01-256.0     | 98        | 5.33%   |
| 1.01-2.0        | 49        | 2.66%   |
| 24.01-32.0      | 38        | 2.07%   |
| 0.51-1.0        | 22        | 1.2%    |
| More than 256.0 | 21        | 1.14%   |
| 2.01-3.0        | 14        | 0.76%   |
| 0.01-0.5        | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 646       | 31.92%  |
| 2.01-3.0        | 458       | 22.63%  |
| 4.01-8.0        | 329       | 16.25%  |
| 3.01-4.0        | 235       | 11.61%  |
| 0.51-1.0        | 166       | 8.2%    |
| 8.01-16.0       | 106       | 5.24%   |
| 0.01-0.5        | 38        | 1.88%   |
| 16.01-24.0      | 18        | 0.89%   |
| 24.01-32.0      | 8         | 0.4%    |
| 32.01-64.0      | 7         | 0.35%   |
| 64.01-256.0     | 7         | 0.35%   |
| Unknown         | 4         | 0.2%    |
| More than 256.0 | 2         | 0.1%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1119      | 60.03%  |
| 2       | 443       | 23.77%  |
| 3       | 160       | 8.58%   |
| 4       | 50        | 2.68%   |
| 5       | 36        | 1.93%   |
| 0       | 19        | 1.02%   |
| 6       | 17        | 0.91%   |
| 7       | 14        | 0.75%   |
| 14      | 2         | 0.11%   |
| 11      | 1         | 0.05%   |
| 9       | 1         | 0.05%   |
| 8       | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1157      | 63.47%  |
| Yes       | 666       | 36.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1548      | 85.1%   |
| No        | 271       | 14.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1292      | 70.99%  |
| No        | 528       | 29.01%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1064      | 58.21%  |
| No        | 764       | 41.79%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Switzerland | 1806      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                               | Computers | Percent |
|------------------------------------|-----------|---------|
| Zurich                             | 514       | 26.2%   |
| Bern                               | 96        | 4.89%   |
| Geneva                             | 66        | 3.36%   |
| Basel                              | 34        | 1.73%   |
| Wiesendangen / Wiesendangen (Dorf) | 33        | 1.68%   |
| Lausanne                           | 33        | 1.68%   |
| Winterthur                         | 31        | 1.58%   |
| Lucerne                            | 30        | 1.53%   |
| Neuchatel                          | 25        | 1.27%   |
| Thun                               | 23        | 1.17%   |
| Lyss                               | 18        | 0.92%   |
| Lugano                             | 16        | 0.82%   |
| St. Gallen                         | 15        | 0.76%   |
| Dietikon                           | 15        | 0.76%   |
| Wil                                | 14        | 0.71%   |
| Munchenstein                       | 12        | 0.61%   |
| Herrliberg                         | 12        | 0.61%   |
| Wettingen                          | 11        | 0.56%   |
| Sion                               | 10        | 0.51%   |
| Dubendorf                          | 10        | 0.51%   |
| Willisau                           | 9         | 0.46%   |
| Wallisellen                        | 9         | 0.46%   |
| Schaffhausen                       | 9         | 0.46%   |
| Oberwil-Lieli                      | 9         | 0.46%   |
| Aarau                              | 9         | 0.46%   |
| Zollikofen                         | 8         | 0.41%   |
| Wetzikon                           | 8         | 0.41%   |
| Morges                             | 8         | 0.41%   |
| Burgdorf                           | 8         | 0.41%   |
| Bosingen                           | 8         | 0.41%   |
| Uster                              | 7         | 0.36%   |
| Prilly                             | 7         | 0.36%   |
| Onex                               | 7         | 0.36%   |
| Le Mont-sur-Lausanne               | 7         | 0.36%   |
| Kloten                             | 7         | 0.36%   |
| Kilchberg                          | 7         | 0.36%   |
| Grabs                              | 7         | 0.36%   |
| Gossau                             | 7         | 0.36%   |
| Chur                               | 7         | 0.36%   |
| Biel/Bienne                        | 7         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 659       | 1201   | 25.89%  |
| WDC                       | 368       | 586    | 14.46%  |
| Seagate                   | 306       | 430    | 12.02%  |
| SanDisk                   | 131       | 164    | 5.15%   |
| Unknown                   | 127       | 188    | 4.99%   |
| Toshiba                   | 127       | 173    | 4.99%   |
| Intel                     | 117       | 163    | 4.6%    |
| Hitachi                   | 83        | 111    | 3.26%   |
| Crucial                   | 75        | 108    | 2.95%   |
| SK hynix                  | 73        | 88     | 2.87%   |
| Kingston                  | 68        | 103    | 2.67%   |
| Micron Technology         | 40        | 52     | 1.57%   |
| Apple                     | 30        | 33     | 1.18%   |
| HGST                      | 27        | 36     | 1.06%   |
| Corsair                   | 25        | 30     | 0.98%   |
| OCZ                       | 23        | 28     | 0.9%    |
| A-DATA Technology         | 21        | 33     | 0.83%   |
| Phison                    | 18        | 29     | 0.71%   |
| LITEON                    | 18        | 24     | 0.71%   |
| Intenso                   | 16        | 16     | 0.63%   |
| Transcend                 | 13        | 23     | 0.51%   |
| KIOXIA                    | 13        | 16     | 0.51%   |
| LITEONIT                  | 12        | 14     | 0.47%   |
| ASMT                      | 10        | 15     | 0.39%   |
| China                     | 9         | 10     | 0.35%   |
| Phison Electronics        | 7         | 15     | 0.28%   |
| KingSpec                  | 7         | 12     | 0.28%   |
| Hewlett-Packard           | 7         | 9      | 0.28%   |
| Silicon Motion            | 6         | 7      | 0.24%   |
| LaCie                     | 6         | 6      | 0.24%   |
| JMicron Technology        | 6         | 6      | 0.24%   |
| Fujitsu                   | 6         | 9      | 0.24%   |
| Plextor                   | 5         | 5      | 0.2%    |
| HPE                       | 5         | 12     | 0.2%    |
| SPCC                      | 4         | 4      | 0.16%   |
| PNY                       | 4         | 9      | 0.16%   |
| Patriot                   | 4         | 5      | 0.16%   |
| Micron/Crucial Technology | 4         | 6      | 0.16%   |
| Maxtor                    | 4         | 5      | 0.16%   |
| Lenovo                    | 4         | 4      | 0.16%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 500GB                           | 38        | 1.33%   |
| Samsung SSD 850 EVO 250GB                           | 32        | 1.12%   |
| Samsung SSD 860 EVO 1TB                             | 29        | 1.01%   |
| Samsung SSD 860 EVO 500GB                           | 25        | 0.87%   |
| Samsung SSD 860 EVO 250GB                           | 23        | 0.8%    |
| Samsung NVMe SSD Drive 512GB                        | 23        | 0.8%    |
| Samsung NVMe SSD Drive 1TB                          | 22        | 0.77%   |
| Samsung SSD 970 EVO Plus 1TB                        | 21        | 0.73%   |
| Unknown MMC Card  32GB                              | 19        | 0.66%   |
| Seagate ST2000DM006-2DM164 2TB                      | 17        | 0.59%   |
| Samsung NVMe SSD Drive 500GB                        | 17        | 0.59%   |
| Unknown MMC Card  128GB                             | 16        | 0.56%   |
| Seagate ST2000DM008-2FR102 2TB                      | 16        | 0.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 16        | 0.56%   |
| Unknown MMC Card  64GB                              | 15        | 0.52%   |
| Samsung SSD 850 EVO 1TB                             | 15        | 0.52%   |
| Samsung SSD 840 EVO 250GB                           | 15        | 0.52%   |
| SanDisk NVMe SSD Drive 512GB                        | 14        | 0.49%   |
| Samsung NVMe SSD Drive 1024GB                       | 14        | 0.49%   |
| HGST HTS721010A9E630 1TB                            | 14        | 0.49%   |
| Seagate ST2000DM001-1ER164 2TB                      | 13        | 0.45%   |
| Seagate Expansion 240GB                             | 13        | 0.45%   |
| Samsung SSD 970 EVO Plus 500GB                      | 13        | 0.45%   |
| SK hynix NVMe SSD Drive 512GB                       | 12        | 0.42%   |
| Samsung SSD 970 EVO 1TB                             | 12        | 0.42%   |
| Samsung SSD 860 QVO 1TB                             | 12        | 0.42%   |
| Samsung SSD 850 PRO 256GB                           | 12        | 0.42%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB              | 12        | 0.42%   |
| Samsung HD103SJ 1TB                                 | 11        | 0.38%   |
| Crucial CT1000MX500SSD1 1TB                         | 11        | 0.38%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 10        | 0.35%   |
| Unknown SD/MMC/MS PRO 2GB                           | 10        | 0.35%   |
| Samsung SSD 970 EVO Plus 2TB                        | 10        | 0.35%   |
| Samsung SSD 970 EVO 500GB                           | 10        | 0.35%   |
| Samsung SSD 850 PRO 512GB                           | 10        | 0.35%   |
| Samsung NVMe SSD Drive 2TB                          | 10        | 0.35%   |
| Intel SSDPEKNW512G8H 512GB                          | 10        | 0.35%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 9         | 0.31%   |
| Toshiba DT01ACA100 1TB                              | 9         | 0.31%   |
| Seagate ST1000LM048-2E7172 1TB                      | 9         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 296       | 409    | 35.66%  |
| WDC                 | 273       | 441    | 32.89%  |
| Hitachi             | 83        | 111    | 10%     |
| Toshiba             | 65        | 81     | 7.83%   |
| Samsung Electronics | 40        | 56     | 4.82%   |
| HGST                | 27        | 36     | 3.25%   |
| Unknown             | 11        | 12     | 1.33%   |
| Fujitsu             | 6         | 9      | 0.72%   |
| ASMT                | 5         | 7      | 0.6%    |
| Maxtor              | 4         | 5      | 0.48%   |
| Intenso             | 4         | 4      | 0.48%   |
| Apple               | 3         | 3      | 0.36%   |
| ASMedia             | 2         | 2      | 0.24%   |
| USB3.0              | 1         | 2      | 0.12%   |
| Unknown (CF)        | 1         | 1      | 0.12%   |
| SABRENT             | 1         | 1      | 0.12%   |
| MARVELL             | 1         | 1      | 0.12%   |
| IET                 | 1         | 1      | 0.12%   |
| ICY BOX             | 1         | 1      | 0.12%   |
| HPE                 | 1         | 2      | 0.12%   |
| HGST HTS            | 1         | 1      | 0.12%   |
| Hewlett-Packard     | 1         | 2      | 0.12%   |
| ExcelStor           | 1         | 2      | 0.12%   |
| ASMT109x            | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 379       | 662    | 39.77%  |
| SanDisk             | 84        | 106    | 8.81%   |
| Crucial             | 71        | 104    | 7.45%   |
| WDC                 | 57        | 75     | 5.98%   |
| Intel               | 54        | 66     | 5.67%   |
| Kingston            | 50        | 82     | 5.25%   |
| Micron Technology   | 25        | 35     | 2.62%   |
| OCZ                 | 23        | 28     | 2.41%   |
| Toshiba             | 22        | 33     | 2.31%   |
| Apple               | 21        | 22     | 2.2%    |
| SK hynix            | 18        | 22     | 1.89%   |
| LITEON              | 18        | 24     | 1.89%   |
| A-DATA Technology   | 14        | 23     | 1.47%   |
| Corsair             | 13        | 14     | 1.36%   |
| Transcend           | 12        | 22     | 1.26%   |
| LITEONIT            | 12        | 14     | 1.26%   |
| Intenso             | 11        | 11     | 1.15%   |
| China               | 9         | 10     | 0.94%   |
| KingSpec            | 7         | 12     | 0.73%   |
| Plextor             | 5         | 5      | 0.52%   |
| Patriot             | 4         | 5      | 0.42%   |
| JMicron Technology  | 4         | 4      | 0.42%   |
| ASMT                | 4         | 7      | 0.42%   |
| SPCC                | 3         | 3      | 0.31%   |
| Seagate             | 3         | 3      | 0.31%   |
| Hewlett-Packard     | 3         | 4      | 0.31%   |
| PNY                 | 2         | 3      | 0.21%   |
| Mushkin             | 2         | 2      | 0.21%   |
| Initio              | 2         | 2      | 0.21%   |
| HPE                 | 2         | 2      | 0.21%   |
| Unknown             | 1         | 1      | 0.1%    |
| TO Exter            | 1         | 1      | 0.1%    |
| Phison              | 1         | 3      | 0.1%    |
| Palit               | 1         | 1      | 0.1%    |
| ORICO               | 1         | 1      | 0.1%    |
| NVME                | 1         | 2      | 0.1%    |
| Netac               | 1         | 1      | 0.1%    |
| Leven               | 1         | 1      | 0.1%    |
| Kolink              | 1         | 1      | 0.1%    |
| KIOXIA-EXCERIA      | 1         | 1      | 0.1%    |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 839       | 1429   | 35.64%  |
| HDD     | 714       | 1191   | 30.33%  |
| NVMe    | 653       | 1010   | 27.74%  |
| MMC     | 119       | 180    | 5.06%   |
| Unknown | 29        | 47     | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1230      | 2518   | 58.13%  |
| NVMe | 652       | 1009   | 30.81%  |
| MMC  | 119       | 180    | 5.62%   |
| SAS  | 115       | 150    | 5.43%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 861       | 1384   | 52.5%   |
| 0.51-1.0   | 454       | 726    | 27.68%  |
| 1.01-2.0   | 183       | 287    | 11.16%  |
| 3.01-4.0   | 53        | 93     | 3.23%   |
| 2.01-3.0   | 42        | 63     | 2.56%   |
| 4.01-10.0  | 39        | 51     | 2.38%   |
| 10.01-20.0 | 8         | 16     | 0.49%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 441       | 22.87%  |
| 251-500        | 366       | 18.98%  |
| 501-1000       | 301       | 15.61%  |
| 1001-2000      | 192       | 9.96%   |
| 1-20           | 144       | 7.47%   |
| More than 3000 | 126       | 6.54%   |
| 51-100         | 101       | 5.24%   |
| 2001-3000      | 92        | 4.77%   |
| Unknown        | 90        | 4.67%   |
| 21-50          | 75        | 3.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 708       | 35.29%  |
| 21-50          | 262       | 13.06%  |
| 101-250        | 243       | 12.11%  |
| 51-100         | 221       | 11.02%  |
| 251-500        | 178       | 8.87%   |
| 501-1000       | 140       | 6.98%   |
| Unknown        | 90        | 4.49%   |
| 1001-2000      | 89        | 4.44%   |
| More than 3000 | 49        | 2.44%   |
| 2001-3000      | 26        | 1.3%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| WDC WD3000HLHX-01JJPV0 304GB          | 2         | 2      | 1.61%   |
| Seagate ST9320325AS 320GB             | 2         | 2      | 1.61%   |
| Seagate ST3250310AS 250GB             | 2         | 2      | 1.61%   |
| Seagate ST31500341AS 1TB              | 2         | 5      | 1.61%   |
| Samsung Electronics SSD 850 EVO 1TB   | 2         | 2      | 1.61%   |
| Initio 3639S 160GB SSD                | 2         | 2      | 1.61%   |
| Hitachi HUA722020ALA330 2TB           | 2         | 2      | 1.61%   |
| Hitachi HTS545050B9A300 500GB         | 2         | 2      | 1.61%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD      | 1         | 1      | 0.81%   |
| WDC WD5000AAKS-65A7B0 500GB           | 1         | 1      | 0.81%   |
| WDC WD5000AAKS-00TMA0 500GB           | 1         | 1      | 0.81%   |
| WDC WD5000AAKS-00E4A0 500GB           | 1         | 1      | 0.81%   |
| WDC WD40EZRZ-00WN9B0 4TB              | 1         | 1      | 0.81%   |
| WDC WD4003FZEX-00Z4SA0 4TB            | 1         | 2      | 0.81%   |
| WDC WD3200AAKS-00B3A0 320GB           | 1         | 1      | 0.81%   |
| WDC WD3200AAJS-40VWA1 320GB           | 1         | 1      | 0.81%   |
| WDC WD30EZRX-00D8PB0 3TB              | 1         | 1      | 0.81%   |
| WDC WD2502ABYS-01B7A0 256GB           | 1         | 1      | 0.81%   |
| WDC WD20EZRZ-00Z5HB0 2TB              | 1         | 1      | 0.81%   |
| WDC WD20EZRX-00D8PB0 2TB              | 1         | 2      | 0.81%   |
| WDC WD20EFRX-68AX9N0 2TB              | 1         | 1      | 0.81%   |
| WDC WD1600BEKT-60A25T1 160GB          | 1         | 1      | 0.81%   |
| WDC WD10EZEX-08M2NA0 1TB              | 1         | 1      | 0.81%   |
| WDC WD10EARS-00Y5B1 1TB               | 1         | 1      | 0.81%   |
| WDC WD10EADS-22M2B0 1TB               | 1         | 1      | 0.81%   |
| WDC WD10EADS-00L5B1 1TB               | 1         | 1      | 0.81%   |
| WDC WD1001FALS-403AA0 1TB             | 1         | 1      | 0.81%   |
| WDC PC SN730 SDBQNTY-512G-1001 512GB  | 1         | 1      | 0.81%   |
| Toshiba THNSN5256GPUK 256GB           | 1         | 1      | 0.81%   |
| Toshiba MQ01ABF050 500GB              | 1         | 1      | 0.81%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 0.81%   |
| Toshiba MQ01ABD075 752GB              | 1         | 1      | 0.81%   |
| Toshiba MK7575GSX 752GB               | 1         | 3      | 0.81%   |
| Toshiba MK1652GSX 160GB               | 1         | 1      | 0.81%   |
| Toshiba MK1255GSX H 120GB             | 1         | 1      | 0.81%   |
| Toshiba DT01ACA100 1TB                | 1         | 1      | 0.81%   |
| SK hynix SC401 SATA 512GB SSD         | 1         | 2      | 0.81%   |
| SK hynix SC210 mSATA 256GB SSD        | 1         | 1      | 0.81%   |
| SK hynix HFS256GD9TNG-62A0A 256GB     | 1         | 1      | 0.81%   |
| SK hynix HFS256G39TND-N210A 256GB SSD | 1         | 1      | 0.81%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 22        | 24     | 17.89%  |
| Seagate             | 19        | 29     | 15.45%  |
| Samsung Electronics | 16        | 18     | 13.01%  |
| Hitachi             | 11        | 12     | 8.94%   |
| Toshiba             | 8         | 10     | 6.5%    |
| Intel               | 8         | 9      | 6.5%    |
| SK hynix            | 7         | 8      | 5.69%   |
| SanDisk             | 5         | 6      | 4.07%   |
| Kingston            | 5         | 6      | 4.07%   |
| HGST                | 4         | 4      | 3.25%   |
| OCZ                 | 3         | 4      | 2.44%   |
| Micron Technology   | 3         | 3      | 2.44%   |
| A-DATA Technology   | 3         | 5      | 2.44%   |
| Initio              | 2         | 2      | 1.63%   |
| Crucial             | 2         | 2      | 1.63%   |
| Patriot             | 1         | 2      | 0.81%   |
| LITEONIT            | 1         | 1      | 0.81%   |
| Intenso             | 1         | 1      | 0.81%   |
| China               | 1         | 1      | 0.81%   |
| ASMedia             | 1         | 1      | 0.81%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 20        | 22     | 29.85%  |
| Seagate             | 19        | 29     | 28.36%  |
| Hitachi             | 11        | 12     | 16.42%  |
| Toshiba             | 7         | 9      | 10.45%  |
| Samsung Electronics | 5         | 5      | 7.46%   |
| HGST                | 4         | 4      | 5.97%   |
| ASMedia             | 1         | 1      | 1.49%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 61        | 82     | 52.14%  |
| SSD  | 46        | 55     | 39.32%  |
| NVMe | 10        | 11     | 8.55%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3750528AS 752GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 998       | 2058   | 51.26%  |
| Works    | 838       | 1650   | 43.04%  |
| Malfunc  | 110       | 148    | 5.65%   |
| Failed   | 1         | 1      | 0.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 1220      | 52.41%  |
| Samsung Electronics            | 318       | 13.66%  |
| AMD                            | 264       | 11.34%  |
| SanDisk                        | 88        | 3.78%   |
| ASMedia Technology             | 56        | 2.41%   |
| SK hynix                       | 50        | 2.15%   |
| Marvell Technology Group       | 50        | 2.15%   |
| Toshiba America Info Systems   | 45        | 1.93%   |
| Phison Electronics             | 35        | 1.5%    |
| JMicron Technology             | 28        | 1.2%    |
| Nvidia                         | 25        | 1.07%   |
| Kingston Technology Company    | 21        | 0.9%    |
| Micron Technology              | 16        | 0.69%   |
| LSI Logic / Symbios Logic      | 13        | 0.56%   |
| Areca Technology               | 13        | 0.56%   |
| KIOXIA                         | 12        | 0.52%   |
| Silicon Motion                 | 11        | 0.47%   |
| Seagate Technology             | 10        | 0.43%   |
| Hewlett-Packard                | 7         | 0.3%    |
| Broadcom / LSI                 | 7         | 0.3%    |
| ADATA Technology               | 7         | 0.3%    |
| Micron/Crucial Technology      | 6         | 0.26%   |
| Apple                          | 5         | 0.21%   |
| Lenovo                         | 4         | 0.17%   |
| VIA Technologies               | 3         | 0.13%   |
| Solid State Storage Technology | 3         | 0.13%   |
| Realtek Semiconductor          | 3         | 0.13%   |
| Lite-On Technology             | 3         | 0.13%   |
| Adaptec                        | 2         | 0.09%   |
| Transcend                      | 1         | 0.04%   |
| Tekram Technology              | 1         | 0.04%   |
| Biwin Storage Technology       | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 187       | 7.03%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 182       | 6.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 92        | 3.46%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 81        | 3.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 77        | 2.9%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 61        | 2.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 57        | 2.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 52        | 1.96%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 52        | 1.96%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 50        | 1.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 47        | 1.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 47        | 1.77%   |
| Intel Volume Management Device NVMe RAID Controller                            | 44        | 1.65%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 43        | 1.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 39        | 1.47%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 39        | 1.47%   |
| Intel SATA Controller [RAID mode]                                              | 37        | 1.39%   |
| AMD 400 Series Chipset SATA Controller                                         | 36        | 1.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 34        | 1.28%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 31        | 1.17%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 31        | 1.17%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 30        | 1.13%   |
| Intel SSD 660P Series                                                          | 28        | 1.05%   |
| Samsung NVMe SSD Controller 980                                                | 27        | 1.02%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 25        | 0.94%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 25        | 0.94%   |
| Intel Comet Lake SATA AHCI Controller                                          | 24        | 0.9%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 24        | 0.9%    |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 23        | 0.86%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 22        | 0.83%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 21        | 0.79%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 20        | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 20        | 0.75%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                              | 19        | 0.71%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 18        | 0.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 18        | 0.68%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 17        | 0.64%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 17        | 0.64%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]               | 17        | 0.64%   |
| AMD 500 Series Chipset SATA Controller                                         | 17        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1253      | 54.22%  |
| NVMe | 657       | 28.43%  |
| IDE  | 197       | 8.52%   |
| RAID | 182       | 7.88%   |
| SAS  | 21        | 0.91%   |
| SCSI | 1         | 0.04%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 1439      | 79.68%  |
| AMD          | 327       | 18.11%  |
| ARM          | 35        | 1.94%   |
| QUALCOMM     | 2         | 0.11%   |
| CentaurHauls | 2         | 0.11%   |
| Unknown      | 1         | 0.06%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                      | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz          | 45        | 2.49%   |
| Intel Core i7-8550U CPU @ 1.80GHz          | 40        | 2.21%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz    | 35        | 1.94%   |
| ARM Processor                              | 35        | 1.94%   |
| Intel Core i7-6700 CPU @ 3.40GHz           | 21        | 1.16%   |
| Intel Core i7-7500U CPU @ 2.70GHz          | 20        | 1.11%   |
| Intel Core i5-8250U CPU @ 1.60GHz          | 19        | 1.05%   |
| Intel Core i5-7200U CPU @ 2.50GHz          | 19        | 1.05%   |
| Intel Core i7-3770 CPU @ 3.40GHz           | 18        | 1%      |
| Intel Core i7-2600 CPU @ 3.40GHz           | 18        | 1%      |
| Intel Core i7-10510U CPU @ 1.80GHz         | 17        | 0.94%   |
| Intel Core i7-9750H CPU @ 2.60GHz          | 15        | 0.83%   |
| AMD Ryzen 7 3700X 8-Core Processor         | 15        | 0.83%   |
| Intel Core i7-4790 CPU @ 3.60GHz           | 14        | 0.78%   |
| Intel Core i7-4770 CPU @ 3.40GHz           | 14        | 0.78%   |
| Intel Core i7-4600U CPU @ 2.10GHz          | 14        | 0.78%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz         | 14        | 0.78%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz    | 13        | 0.72%   |
| AMD Ryzen 5 3600 6-Core Processor          | 13        | 0.72%   |
| Intel Core i7-8750H CPU @ 2.20GHz          | 12        | 0.66%   |
| Intel Core i7-8700K CPU @ 3.70GHz          | 12        | 0.66%   |
| Intel Core i7-8650U CPU @ 1.90GHz          | 12        | 0.66%   |
| AMD Ryzen 9 3900X 12-Core Processor        | 12        | 0.66%   |
| Intel Core i7-7700K CPU @ 4.20GHz          | 11        | 0.61%   |
| Intel Core i5-8265U CPU @ 1.60GHz          | 11        | 0.61%   |
| Intel Core i5-6200U CPU @ 2.30GHz          | 11        | 0.61%   |
| Intel Core i5-10210U CPU @ 1.60GHz         | 11        | 0.61%   |
| Intel Core i7-4790K CPU @ 4.00GHz          | 10        | 0.55%   |
| Intel Core i7-3630QM CPU @ 2.40GHz         | 10        | 0.55%   |
| Intel Core i5-6300U CPU @ 2.40GHz          | 10        | 0.55%   |
| Intel Core i5-5300U CPU @ 2.30GHz          | 10        | 0.55%   |
| Intel Core i5-2520M CPU @ 2.50GHz          | 10        | 0.55%   |
| Intel Core i5-2400 CPU @ 3.10GHz           | 10        | 0.55%   |
| AMD Ryzen 7 4700U with Radeon Graphics     | 10        | 0.55%   |
| Intel Core i7-6700K CPU @ 4.00GHz          | 9         | 0.5%    |
| Intel Core i7-6700HQ CPU @ 2.60GHz         | 9         | 0.5%    |
| Intel Core i7-3770K CPU @ 3.50GHz          | 9         | 0.5%    |
| Intel Core i5-6500 CPU @ 3.20GHz           | 9         | 0.5%    |
| Intel Atom x5-Z8350 CPU @ 1.44GHz          | 9         | 0.5%    |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics | 9         | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 613       | 33.94%  |
| Intel Core i5           | 360       | 19.93%  |
| Other                   | 133       | 7.36%   |
| AMD Ryzen 7             | 77        | 4.26%   |
| Intel Xeon              | 74        | 4.1%    |
| AMD Ryzen 5             | 73        | 4.04%   |
| Intel Core 2 Duo        | 62        | 3.43%   |
| Intel Core i3           | 49        | 2.71%   |
| Intel Celeron           | 46        | 2.55%   |
| AMD Ryzen 9             | 31        | 1.72%   |
| Intel Atom              | 28        | 1.55%   |
| Intel Pentium           | 26        | 1.44%   |
| Intel Core i9           | 18        | 1%      |
| AMD FX                  | 18        | 1%      |
| Intel Pentium Dual-Core | 14        | 0.78%   |
| Intel Core 2            | 14        | 0.78%   |
| AMD Ryzen 7 PRO         | 14        | 0.78%   |
| Intel Core 2 Quad       | 13        | 0.72%   |
| AMD Ryzen Threadripper  | 12        | 0.66%   |
| AMD Ryzen 3             | 9         | 0.5%    |
| AMD Quad-Core Opteron   | 8         | 0.44%   |
| AMD GX                  | 8         | 0.44%   |
| AMD A8                  | 7         | 0.39%   |
| Intel Xeon Gold         | 6         | 0.33%   |
| AMD E                   | 6         | 0.33%   |
| AMD Opteron             | 5         | 0.28%   |
| AMD EPYC                | 5         | 0.28%   |
| AMD Athlon              | 5         | 0.28%   |
| Intel Pentium 4         | 4         | 0.22%   |
| AMD Phenom II X6        | 4         | 0.22%   |
| AMD Phenom II X4        | 4         | 0.22%   |
| AMD A10                 | 4         | 0.22%   |
| Intel Pentium Silver    | 3         | 0.17%   |
| Intel Pentium M         | 3         | 0.17%   |
| Intel Genuine           | 3         | 0.17%   |
| Intel Core M            | 3         | 0.17%   |
| AMD Ryzen 5 PRO         | 3         | 0.17%   |
| AMD E2                  | 3         | 0.17%   |
| AMD E1                  | 3         | 0.17%   |
| AMD Athlon II X2        | 3         | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 803       | 44.41%  |
| 2       | 518       | 28.65%  |
| 6       | 189       | 10.45%  |
| 8       | 160       | 8.85%   |
| 12      | 42        | 2.32%   |
| 16      | 23        | 1.27%   |
| 1       | 20        | 1.11%   |
| 32      | 9         | 0.5%    |
| 10      | 9         | 0.5%    |
| 24      | 6         | 0.33%   |
| 3       | 6         | 0.33%   |
| Unknown | 6         | 0.33%   |
| 14      | 5         | 0.28%   |
| 40      | 4         | 0.22%   |
| 128     | 3         | 0.17%   |
| 48      | 3         | 0.17%   |
| 20      | 1         | 0.06%   |
| 18      | 1         | 0.06%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1746      | 96.62%  |
| 2       | 46        | 2.55%   |
| 4       | 10        | 0.55%   |
| Unknown | 4         | 0.22%   |
| 3       | 1         | 0.06%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1308      | 72.11%  |
| 1       | 500       | 27.56%  |
| Unknown | 6         | 0.33%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1768      | 97.57%  |
| Unknown        | 31        | 1.71%   |
| 32-bit         | 12        | 0.66%   |
| 64-bit         | 1         | 0.06%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 376       | 20.22%  |
| 0x306a9    | 115       | 6.18%   |
| 0x206a7    | 96        | 5.16%   |
| 0x306c3    | 91        | 4.89%   |
| 0x806ea    | 74        | 3.98%   |
| 0x906ea    | 60        | 3.23%   |
| 0x506e3    | 60        | 3.23%   |
| 0x806ec    | 53        | 2.85%   |
| 0x40651    | 51        | 2.74%   |
| 0x1067a    | 51        | 2.74%   |
| 0x806e9    | 48        | 2.58%   |
| 0x806c1    | 46        | 2.47%   |
| 0x906e9    | 31        | 1.67%   |
| 0x306d4    | 30        | 1.61%   |
| 0x08701021 | 26        | 1.4%    |
| 0x20655    | 25        | 1.34%   |
| 0x406e3    | 24        | 1.29%   |
| 0x30678    | 21        | 1.13%   |
| 0x706e5    | 17        | 0.91%   |
| 0x10676    | 17        | 0.91%   |
| 0x0a50000c | 17        | 0.91%   |
| 0x806eb    | 16        | 0.86%   |
| 0xa0655    | 15        | 0.81%   |
| 0x206d7    | 15        | 0.81%   |
| 0x0800820d | 15        | 0.81%   |
| 0xa0652    | 14        | 0.75%   |
| 0x50654    | 14        | 0.75%   |
| 0x106e5    | 13        | 0.7%    |
| 0x406c4    | 12        | 0.65%   |
| 0x306e4    | 12        | 0.65%   |
| 0x20652    | 12        | 0.65%   |
| 0x08701013 | 12        | 0.65%   |
| 0x706a1    | 11        | 0.59%   |
| 0x6fd      | 11        | 0.59%   |
| 0x306f2    | 11        | 0.59%   |
| 0x206c2    | 11        | 0.59%   |
| 0x906ed    | 10        | 0.54%   |
| 0x08600106 | 10        | 0.54%   |
| 0x08600103 | 10        | 0.54%   |
| 0x906a3    | 9         | 0.48%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 373       | 20.63%  |
| Haswell          | 186       | 10.29%  |
| IvyBridge        | 147       | 8.13%   |
| SandyBridge      | 133       | 7.36%   |
| Skylake          | 122       | 6.75%   |
| Zen 2            | 90        | 4.98%   |
| Penryn           | 77        | 4.26%   |
| Unknown          | 74        | 4.09%   |
| TigerLake        | 59        | 3.26%   |
| Westmere         | 55        | 3.04%   |
| Zen 3            | 48        | 2.65%   |
| Silvermont       | 43        | 2.38%   |
| CometLake        | 43        | 2.38%   |
| Broadwell        | 40        | 2.21%   |
| Zen+             | 36        | 1.99%   |
| Zen              | 33        | 1.83%   |
| Core             | 33        | 1.83%   |
| Nehalem          | 29        | 1.6%    |
| K10              | 27        | 1.49%   |
| IceLake          | 27        | 1.49%   |
| Piledriver       | 20        | 1.11%   |
| Goldmont plus    | 17        | 0.94%   |
| Alderlake Hybrid | 16        | 0.88%   |
| Goldmont         | 12        | 0.66%   |
| Bobcat           | 12        | 0.66%   |
| Puma             | 10        | 0.55%   |
| K8 Hammer        | 8         | 0.44%   |
| Jaguar           | 8         | 0.44%   |
| P6               | 6         | 0.33%   |
| Excavator        | 5         | 0.28%   |
| Bulldozer        | 5         | 0.28%   |
| Bonnell          | 5         | 0.28%   |
| NetBurst         | 4         | 0.22%   |
| K10 Llano        | 3         | 0.17%   |
| Steamroller      | 2         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1011      | 49.1%   |
| Nvidia                                       | 621       | 30.16%  |
| AMD                                          | 373       | 18.12%  |
| Matrox Electronics Systems                   | 30        | 1.46%   |
| ASPEED Technology                            | 13        | 0.63%   |
| XGI Technology (eXtreme Graphics Innovation) | 9         | 0.44%   |
| VIA Technologies                             | 2         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel UHD Graphics 620                                                                   | 79        | 3.78%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 76        | 3.64%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 74        | 3.54%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 61        | 2.92%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 57        | 2.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 57        | 2.73%   |
| Intel HD Graphics 620                                                                    | 50        | 2.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 40        | 1.91%   |
| Intel HD Graphics 530                                                                    | 37        | 1.77%   |
| AMD Renoir                                                                               | 34        | 1.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 33        | 1.58%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 33        | 1.58%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 32        | 1.53%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 30        | 1.44%   |
| Intel HD Graphics 5500                                                                   | 28        | 1.34%   |
| Intel Core Processor Integrated Graphics Controller                                      | 27        | 1.29%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 27        | 1.29%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 24        | 1.15%   |
| Intel HD Graphics 630                                                                    | 22        | 1.05%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 21        | 1%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 21        | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 19        | 0.91%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 17        | 0.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 17        | 0.81%   |
| Nvidia GK107GL [Quadro K420]                                                             | 15        | 0.72%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 14        | 0.67%   |
| Matrox Electronics Systems MGA G200eW WPCM450                                            | 14        | 0.67%   |
| Intel Iris Plus Graphics G7                                                              | 14        | 0.67%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 14        | 0.67%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 14        | 0.67%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 13        | 0.62%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 13        | 0.62%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 12        | 0.57%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 12        | 0.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12        | 0.57%   |
| AMD Lucienne                                                                             | 12        | 0.57%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 11        | 0.53%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 11        | 0.53%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 11        | 0.53%   |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 11        | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 743       | 40.85%  |
| 1 x Nvidia               | 390       | 21.44%  |
| 1 x AMD                  | 314       | 17.26%  |
| Intel + Nvidia           | 208       | 11.43%  |
| Other                    | 48        | 2.64%   |
| Intel + AMD              | 35        | 1.92%   |
| 1 x Matrox               | 27        | 1.48%   |
| AMD + Nvidia             | 13        | 0.71%   |
| 2 x AMD                  | 9         | 0.49%   |
| 1 x XGI                  | 9         | 0.49%   |
| 1 x ASPEED               | 8         | 0.44%   |
| Nvidia + ASPEED          | 4         | 0.22%   |
| 2 x Nvidia               | 3         | 0.16%   |
| 1 x VIA                  | 2         | 0.11%   |
| Nvidia + Matrox          | 2         | 0.11%   |
| 2 x Nvidia + 1 x ASPEED  | 1         | 0.05%   |
| 2 x Intel                | 1         | 0.05%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.05%   |
| AMD + Matrox             | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1353      | 74.22%  |
| Proprietary | 361       | 19.8%   |
| Unknown     | 109       | 5.98%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 989       | 53.4%   |
| 1.01-2.0   | 236       | 12.74%  |
| 0.01-0.5   | 172       | 9.29%   |
| 3.01-4.0   | 138       | 7.45%   |
| 0.51-1.0   | 128       | 6.91%   |
| 7.01-8.0   | 83        | 4.48%   |
| 8.01-16.0  | 59        | 3.19%   |
| 5.01-6.0   | 32        | 1.73%   |
| 2.01-3.0   | 13        | 0.7%    |
| 4.01-5.0   | 1         | 0.05%   |
| 16.01-24.0 | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 256       | 13.06%  |
| AU Optronics            | 224       | 11.43%  |
| LG Display              | 185       | 9.44%   |
| Dell                    | 135       | 6.89%   |
| Chimei Innolux          | 111       | 5.66%   |
| Hewlett-Packard         | 94        | 4.8%    |
| BOE                     | 93        | 4.74%   |
| Acer                    | 93        | 4.74%   |
| Philips                 | 80        | 4.08%   |
| Apple                   | 69        | 3.52%   |
| BenQ                    | 63        | 3.21%   |
| Ancor Communications    | 59        | 3.01%   |
| Sharp                   | 55        | 2.81%   |
| Lenovo                  | 49        | 2.5%    |
| Goldstar                | 46        | 2.35%   |
| AOC                     | 40        | 2.04%   |
| Eizo                    | 36        | 1.84%   |
| Chi Mei Optoelectronics | 22        | 1.12%   |
| Sony                    | 20        | 1.02%   |
| ASUSTek Computer        | 20        | 1.02%   |
| Unknown                 | 19        | 0.97%   |
| InfoVision              | 19        | 0.97%   |
| Iiyama                  | 13        | 0.66%   |
| CSO                     | 13        | 0.66%   |
| NEC Computers           | 11        | 0.56%   |
| Panasonic               | 9         | 0.46%   |
| Toshiba                 | 8         | 0.41%   |
| PANDA                   | 7         | 0.36%   |
| Medion                  | 7         | 0.36%   |
| ViewSonic               | 5         | 0.26%   |
| Vestel Elektronik       | 5         | 0.26%   |
| LG Philips              | 5         | 0.26%   |
| LG Electronics          | 5         | 0.26%   |
| Gigabyte Technology     | 5         | 0.26%   |
| AUS                     | 5         | 0.26%   |
| MSI                     | 4         | 0.2%    |
| JDI                     | 4         | 0.2%    |
| Fujitsu Siemens         | 4         | 0.2%    |
| ___                     | 3         | 0.15%   |
| HannStar                | 3         | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch | 11        | 0.53%   |
| AOC Q3279WG5B AOC3279 2560x1440 730x430mm 33.4-inch                   | 9         | 0.44%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1200                  | 8         | 0.39%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.39%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch      | 7         | 0.34%   |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch        | 7         | 0.34%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 6         | 0.29%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch   | 6         | 0.29%   |
| Philips LCD Monitor PHL 272S4L 2560x1440                              | 6         | 0.29%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 6         | 0.29%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.29%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 6         | 0.29%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch        | 6         | 0.29%   |
| Apple iMac APPA00C 1920x1080 475x267mm 21.5-inch                      | 6         | 0.29%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 5         | 0.24%   |
| Samsung Electronics U32J59x SAM0F34 3840x2160 697x392mm 31.5-inch     | 5         | 0.24%   |
| Samsung Electronics LCD Monitor SDC3853 2736x1824 260x173mm 12.3-inch | 5         | 0.24%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 5         | 0.24%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 5         | 0.24%   |
| Hewlett-Packard LA2405 HWP284B 1920x1200 518x324mm 24.1-inch          | 5         | 0.24%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 5         | 0.24%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 5         | 0.24%   |
| AU Optronics LCD Monitor AUO139E 1600x900 380x210mm 17.1-inch         | 5         | 0.24%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch        | 5         | 0.24%   |
| Ancor Communications ASUS PB278 ACI27A3 1920x1080 597x336mm 27.0-inch | 5         | 0.24%   |
| Sharp LCD Monitor SHP1476 3840x2160 346x194mm 15.6-inch               | 4         | 0.19%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch     | 4         | 0.19%   |
| Samsung Electronics LCD Monitor SyncMaster                            | 4         | 0.19%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 4         | 0.19%   |
| Samsung Electronics C49HG9x SAM0E5D 3840x1080 1196x336mm 48.9-inch    | 4         | 0.19%   |
| Philips PHL 272B8Q PHL0918 2560x1440 597x336mm 27.0-inch              | 4         | 0.19%   |
| Panasonic TV MEIA296 1920x1080 1280x720mm 57.8-inch                   | 4         | 0.19%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 4         | 0.19%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 4         | 0.19%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch          | 4         | 0.19%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch          | 4         | 0.19%   |
| LG Display LCD Monitor LGD040A 1920x1080 309x175mm 14.0-inch          | 4         | 0.19%   |
| Lenovo LEN P27h-10 LEN61AF 2560x1440 600x340mm 27.2-inch              | 4         | 0.19%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 4         | 0.19%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x193mm 15.5-inch               | 4         | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 795       | 41.97%  |
| 3840x2160 (4K)     | 171       | 9.03%   |
| 2560x1440 (QHD)    | 141       | 7.44%   |
| 1366x768 (WXGA)    | 138       | 7.29%   |
| 1920x1200 (WUXGA)  | 93        | 4.91%   |
| 1600x900 (HD+)     | 77        | 4.07%   |
| 1680x1050 (WSXGA+) | 69        | 3.64%   |
| 1280x1024 (SXGA)   | 59        | 3.12%   |
| Unknown            | 51        | 2.69%   |
| 1280x800 (WXGA)    | 34        | 1.8%    |
| 3440x1440          | 30        | 1.58%   |
| 1440x900 (WXGA+)   | 30        | 1.58%   |
| 1600x1200          | 21        | 1.11%   |
| 2560x1600          | 20        | 1.06%   |
| 3840x1080          | 19        | 1%      |
| 2880x1800          | 12        | 0.63%   |
| 3200x1800 (QHD+)   | 11        | 0.58%   |
| 2560x1080          | 10        | 0.53%   |
| 2736x1824          | 9         | 0.48%   |
| 3840x2400          | 8         | 0.42%   |
| 1360x768           | 7         | 0.37%   |
| 1024x768 (XGA)     | 7         | 0.37%   |
| 3840x1200          | 6         | 0.32%   |
| 3000x2000          | 6         | 0.32%   |
| 1920x540           | 6         | 0.32%   |
| 4480x1440          | 5         | 0.26%   |
| 3840x1600          | 5         | 0.26%   |
| 1024x600           | 5         | 0.26%   |
| 2160x1440          | 4         | 0.21%   |
| 3520x1200          | 3         | 0.16%   |
| 3360x1050          | 3         | 0.16%   |
| 2048x1152          | 3         | 0.16%   |
| 7680x2160          | 2         | 0.11%   |
| 6400x1440          | 2         | 0.11%   |
| 5120x1440          | 2         | 0.11%   |
| 3840x1100          | 2         | 0.11%   |
| 3200x1080          | 2         | 0.11%   |
| 2560x1024          | 2         | 0.11%   |
| 2288x1287          | 2         | 0.11%   |
| 800x1280           | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 368       | 18.9%   |
| 27      | 203       | 10.43%  |
| 13      | 175       | 8.99%   |
| 24      | 163       | 8.37%   |
| Unknown | 160       | 8.22%   |
| 14      | 158       | 8.12%   |
| 17      | 122       | 6.27%   |
| 23      | 104       | 5.34%   |
| 21      | 82        | 4.21%   |
| 12      | 54        | 2.77%   |
| 31      | 49        | 2.52%   |
| 19      | 34        | 1.75%   |
| 34      | 33        | 1.69%   |
| 22      | 32        | 1.64%   |
| 20      | 30        | 1.54%   |
| 32      | 18        | 0.92%   |
| 40      | 15        | 0.77%   |
| 84      | 14        | 0.72%   |
| 72      | 13        | 0.67%   |
| 25      | 13        | 0.67%   |
| 33      | 10        | 0.51%   |
| 11      | 10        | 0.51%   |
| 46      | 8         | 0.41%   |
| 16      | 8         | 0.41%   |
| 54      | 7         | 0.36%   |
| 37      | 7         | 0.36%   |
| 18      | 7         | 0.36%   |
| 29      | 6         | 0.31%   |
| 28      | 5         | 0.26%   |
| 26      | 5         | 0.26%   |
| 10      | 5         | 0.26%   |
| 49      | 4         | 0.21%   |
| 48      | 4         | 0.21%   |
| 55      | 3         | 0.15%   |
| 142     | 2         | 0.1%    |
| 65      | 2         | 0.1%    |
| 60      | 2         | 0.1%    |
| 42      | 2         | 0.1%    |
| 74      | 1         | 0.05%   |
| 59      | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 602       | 31.44%  |
| 501-600        | 437       | 22.82%  |
| 201-300        | 181       | 9.45%   |
| Unknown        | 160       | 8.36%   |
| 401-500        | 155       | 8.09%   |
| 351-400        | 147       | 7.68%   |
| 601-700        | 80        | 4.18%   |
| 701-800        | 61        | 3.19%   |
| 1001-1500      | 32        | 1.67%   |
| 1501-2000      | 28        | 1.46%   |
| 801-900        | 25        | 1.31%   |
| 901-1000       | 3         | 0.16%   |
| More than 2000 | 2         | 0.1%    |
| 101-200        | 1         | 0.05%   |
| 1-100          | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1193      | 68.09%  |
| 16/10   | 250       | 14.27%  |
| Unknown | 146       | 8.33%   |
| 5/4     | 51        | 2.91%   |
| 21/9    | 41        | 2.34%   |
| 3/2     | 29        | 1.66%   |
| 4/3     | 24        | 1.37%   |
| 32/9    | 7         | 0.4%    |
| 6/5     | 3         | 0.17%   |
| 1.00    | 3         | 0.17%   |
| 3.40    | 2         | 0.11%   |
| 3.73    | 1         | 0.06%   |
| 2.50    | 1         | 0.06%   |
| 0.67    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 366       | 19.01%  |
| 201-250        | 269       | 13.97%  |
| 81-90          | 232       | 12.05%  |
| 301-350        | 207       | 10.75%  |
| Unknown        | 160       | 8.31%   |
| 351-500        | 120       | 6.23%   |
| 71-80          | 98        | 5.09%   |
| 251-300        | 96        | 4.99%   |
| 121-130        | 94        | 4.88%   |
| 151-200        | 84        | 4.36%   |
| 61-70          | 52        | 2.7%    |
| More than 1000 | 49        | 2.55%   |
| 501-1000       | 37        | 1.92%   |
| 141-150        | 19        | 0.99%   |
| 51-60          | 12        | 0.62%   |
| 131-140        | 12        | 0.62%   |
| 111-120        | 7         | 0.36%   |
| 41-50          | 5         | 0.26%   |
| 91-100         | 4         | 0.21%   |
| 1-40           | 2         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 564       | 30.16%  |
| 121-160       | 499       | 26.68%  |
| 101-120       | 364       | 19.47%  |
| Unknown       | 160       | 8.56%   |
| 161-240       | 144       | 7.7%    |
| More than 240 | 92        | 4.92%   |
| 1-50          | 47        | 2.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1364      | 73.53%  |
| 2     | 309       | 16.66%  |
| 0     | 135       | 7.28%   |
| 3     | 45        | 2.43%   |
| 4     | 2         | 0.11%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1112      | 41.98%  |
| Realtek Semiconductor             | 727       | 27.44%  |
| Qualcomm Atheros                  | 205       | 7.74%   |
| Broadcom                          | 154       | 5.81%   |
| Broadcom Limited                  | 37        | 1.4%    |
| Marvell Technology Group          | 34        | 1.28%   |
| Ralink                            | 31        | 1.17%   |
| MediaTek                          | 25        | 0.94%   |
| Aquantia                          | 25        | 0.94%   |
| Lenovo                            | 22        | 0.83%   |
| Nvidia                            | 19        | 0.72%   |
| ASIX Electronics                  | 19        | 0.72%   |
| Ralink Technology                 | 18        | 0.68%   |
| Sierra Wireless                   | 16        | 0.6%    |
| Hewlett-Packard                   | 14        | 0.53%   |
| Huawei Technologies               | 13        | 0.49%   |
| Edimax Technology                 | 12        | 0.45%   |
| Dell                              | 12        | 0.45%   |
| TP-Link                           | 11        | 0.42%   |
| Samsung Electronics               | 11        | 0.42%   |
| NetGear                           | 11        | 0.42%   |
| Microchip Technology              | 10        | 0.38%   |
| Ericsson Business Mobile Networks | 10        | 0.38%   |
| DisplayLink                       | 10        | 0.38%   |
| D-Link                            | 7         | 0.26%   |
| ASUSTek Computer                  | 7         | 0.26%   |
| Xiaomi                            | 5         | 0.19%   |
| Microsoft                         | 5         | 0.19%   |
| Fibocom                           | 5         | 0.19%   |
| Qualcomm                          | 4         | 0.15%   |
| IMC Networks                      | 4         | 0.15%   |
| ICS Advent                        | 4         | 0.15%   |
| D-Link System                     | 4         | 0.15%   |
| AVM                               | 4         | 0.15%   |
| Wilocity                          | 3         | 0.11%   |
| NetXen Incorporated               | 3         | 0.11%   |
| Mellanox Technologies             | 3         | 0.11%   |
| Linksys                           | 3         | 0.11%   |
| Qualcomm Atheros Communications   | 2         | 0.08%   |
| Micro Star International          | 2         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 517       | 16.31%  |
| Intel Wi-Fi 6 AX200                                               | 113       | 3.56%   |
| Intel Wireless 8265 / 8275                                        | 94        | 2.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 79        | 2.49%   |
| Intel I211 Gigabit Network Connection                             | 72        | 2.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 71        | 2.24%   |
| Intel Ethernet Connection (2) I219-V                              | 51        | 1.61%   |
| Intel Wireless 7260                                               | 47        | 1.48%   |
| Intel Wi-Fi 6 AX201                                               | 46        | 1.45%   |
| Intel Wireless 7265                                               | 42        | 1.32%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 41        | 1.29%   |
| Intel Ethernet Connection I217-LM                                 | 41        | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 38        | 1.2%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 37        | 1.17%   |
| Intel Ethernet Connection (2) I219-LM                             | 36        | 1.14%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 36        | 1.14%   |
| Intel 82579V Gigabit Network Connection                           | 33        | 1.04%   |
| Intel Wireless 8260                                               | 31        | 0.98%   |
| Intel 82574L Gigabit Network Connection                           | 30        | 0.95%   |
| Realtek RTL8125 2.5GbE Controller                                 | 29        | 0.91%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 28        | 0.88%   |
| Intel Ethernet Connection (6) I219-V                              | 26        | 0.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 25        | 0.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 25        | 0.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 24        | 0.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 23        | 0.73%   |
| Intel Wireless 3165                                               | 22        | 0.69%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 21        | 0.66%   |
| Intel Ethernet Connection I218-LM                                 | 21        | 0.66%   |
| Intel Ethernet Connection (4) I219-V                              | 21        | 0.66%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 21        | 0.66%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20        | 0.63%   |
| Intel Ethernet Connection (2) I218-V                              | 20        | 0.63%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 20        | 0.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 19        | 0.6%    |
| Intel Wireless-AC 9260                                            | 19        | 0.6%    |
| Intel I350 Gigabit Network Connection                             | 19        | 0.6%    |
| Intel I210 Gigabit Network Connection                             | 18        | 0.57%   |
| Intel Ethernet Controller I225-V                                  | 18        | 0.57%   |
| Intel Ethernet Connection (4) I219-LM                             | 18        | 0.57%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 762       | 55.78%  |
| Qualcomm Atheros                      | 170       | 12.45%  |
| Realtek Semiconductor                 | 137       | 10.03%  |
| Broadcom                              | 85        | 6.22%   |
| Ralink                                | 31        | 2.27%   |
| MediaTek                              | 22        | 1.61%   |
| Broadcom Limited                      | 22        | 1.61%   |
| Ralink Technology                     | 18        | 1.32%   |
| Sierra Wireless                       | 16        | 1.17%   |
| Edimax Technology                     | 12        | 0.88%   |
| TP-Link                               | 10        | 0.73%   |
| NetGear                               | 10        | 0.73%   |
| Marvell Technology Group              | 9         | 0.66%   |
| Hewlett-Packard                       | 7         | 0.51%   |
| ASUSTek Computer                      | 7         | 0.51%   |
| Dell                                  | 6         | 0.44%   |
| D-Link                                | 6         | 0.44%   |
| Fibocom                               | 5         | 0.37%   |
| IMC Networks                          | 4         | 0.29%   |
| AVM                                   | 4         | 0.29%   |
| Wilocity                              | 3         | 0.22%   |
| Qualcomm                              | 3         | 0.22%   |
| Microsoft                             | 3         | 0.22%   |
| D-Link System                         | 3         | 0.22%   |
| Qualcomm Atheros Communications       | 2         | 0.15%   |
| Micro Star International              | 2         | 0.15%   |
| Philips (or NXP)                      | 1         | 0.07%   |
| Netopia                               | 1         | 0.07%   |
| Linksys                               | 1         | 0.07%   |
| Gemtek                                | 1         | 0.07%   |
| Ericsson Business Mobile Networks     | 1         | 0.07%   |
| CyberTAN Technology                   | 1         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 113       | 8.21%   |
| Intel Wireless 8265 / 8275                                     | 94        | 6.83%   |
| Intel Wireless 7260                                            | 47        | 3.42%   |
| Intel Wi-Fi 6 AX201                                            | 46        | 3.34%   |
| Intel Wireless 7265                                            | 42        | 3.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 38        | 2.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 37        | 2.69%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 36        | 2.62%   |
| Intel Wireless 8260                                            | 31        | 2.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 28        | 2.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 25        | 1.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 25        | 1.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 24        | 1.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 23        | 1.67%   |
| Intel Wireless 3165                                            | 22        | 1.6%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 21        | 1.53%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 21        | 1.53%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 20        | 1.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 19        | 1.38%   |
| Intel Wireless-AC 9260                                         | 19        | 1.38%   |
| Intel Centrino Ultimate-N 6300                                 | 18        | 1.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 17        | 1.24%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 16        | 1.16%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 15        | 1.09%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 15        | 1.09%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 14        | 1.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 13        | 0.94%   |
| Intel Centrino Advanced-N 6235                                 | 13        | 0.94%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 13        | 0.94%   |
| Intel Wireless 3160                                            | 12        | 0.87%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 11        | 0.8%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 11        | 0.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 11        | 0.8%    |
| Intel Centrino Advanced-N 6200                                 | 10        | 0.73%   |
| Sierra Wireless EM7455                                         | 9         | 0.65%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 9         | 0.65%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter               | 9         | 0.65%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 9         | 0.65%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 9         | 0.65%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 8         | 0.58%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Intel                         | 678       | 40.17%  |
| Realtek Semiconductor         | 665       | 39.4%   |
| Broadcom                      | 86        | 5.09%   |
| Qualcomm Atheros              | 60        | 3.55%   |
| Marvell Technology Group      | 25        | 1.48%   |
| Aquantia                      | 25        | 1.48%   |
| Lenovo                        | 22        | 1.3%    |
| Nvidia                        | 19        | 1.13%   |
| ASIX Electronics              | 19        | 1.13%   |
| Broadcom Limited              | 15        | 0.89%   |
| Samsung Electronics           | 11        | 0.65%   |
| DisplayLink                   | 10        | 0.59%   |
| Microchip Technology          | 8         | 0.47%   |
| Huawei Technologies           | 8         | 0.47%   |
| Xiaomi                        | 5         | 0.3%    |
| ICS Advent                    | 4         | 0.24%   |
| NetXen Incorporated           | 3         | 0.18%   |
| MediaTek                      | 3         | 0.18%   |
| Microsoft                     | 2         | 0.12%   |
| Mellanox Technologies         | 2         | 0.12%   |
| Linksys                       | 2         | 0.12%   |
| TP-Link                       | 1         | 0.06%   |
| Standard Microsystems         | 1         | 0.06%   |
| Qualcomm                      | 1         | 0.06%   |
| QNAP System                   | 1         | 0.06%   |
| OnePlus Technology (Shenzhen) | 1         | 0.06%   |
| NetGear                       | 1         | 0.06%   |
| Netchip Technology            | 1         | 0.06%   |
| MosChip Semiconductor         | 1         | 0.06%   |
| JMicron Technology            | 1         | 0.06%   |
| HMD Global                    | 1         | 0.06%   |
| Hewlett-Packard               | 1         | 0.06%   |
| D-Link System                 | 1         | 0.06%   |
| D-Link                        | 1         | 0.06%   |
| Cypress Semiconductor         | 1         | 0.06%   |
| Apple                         | 1         | 0.06%   |
| ADMtek                        | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 517       | 29.56%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 79        | 4.52%   |
| Intel I211 Gigabit Network Connection                             | 72        | 4.12%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 71        | 4.06%   |
| Intel Ethernet Connection (2) I219-V                              | 51        | 2.92%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 41        | 2.34%   |
| Intel Ethernet Connection I217-LM                                 | 41        | 2.34%   |
| Intel Ethernet Connection (2) I219-LM                             | 36        | 2.06%   |
| Intel 82579V Gigabit Network Connection                           | 33        | 1.89%   |
| Intel 82574L Gigabit Network Connection                           | 30        | 1.72%   |
| Realtek RTL8125 2.5GbE Controller                                 | 29        | 1.66%   |
| Intel Ethernet Connection (6) I219-V                              | 26        | 1.49%   |
| Intel Ethernet Connection I218-LM                                 | 21        | 1.2%    |
| Intel Ethernet Connection (4) I219-V                              | 21        | 1.2%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 20        | 1.14%   |
| Intel Ethernet Connection (2) I218-V                              | 20        | 1.14%   |
| Intel I350 Gigabit Network Connection                             | 19        | 1.09%   |
| Intel I210 Gigabit Network Connection                             | 18        | 1.03%   |
| Intel Ethernet Controller I225-V                                  | 18        | 1.03%   |
| Intel Ethernet Connection (4) I219-LM                             | 18        | 1.03%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 18        | 1.03%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 0.91%   |
| Intel Ethernet Connection (7) I219-V                              | 15        | 0.86%   |
| ASIX AX88179 Gigabit Ethernet                                     | 15        | 0.86%   |
| Intel Ethernet Connection (7) I219-LM                             | 14        | 0.8%    |
| Intel Ethernet Connection (3) I218-LM                             | 14        | 0.8%    |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 14        | 0.8%    |
| Intel Ethernet Connection I219-LM                                 | 13        | 0.74%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 11        | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 9         | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 8         | 0.46%   |
| Microchip SMSC9512/9514 Fast Ethernet Adapter                     | 8         | 0.46%   |
| Lenovo ThinkPad Lan                                               | 8         | 0.46%   |
| Intel 82576 Gigabit Network Connection                            | 8         | 0.46%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 8         | 0.46%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 7         | 0.4%    |
| Nvidia MCP55 Ethernet                                             | 7         | 0.4%    |
| Intel Ethernet Connection (13) I219-V                             | 7         | 0.4%    |
| Intel 82567LM Gigabit Network Connection                          | 7         | 0.4%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                 | 7         | 0.4%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1542      | 53.63%  |
| WiFi     | 1290      | 44.87%  |
| Modem    | 40        | 1.39%   |
| Unknown  | 3         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 931       | 51.13%  |
| Ethernet | 890       | 48.87%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 928       | 51.16%  |
| 1     | 709       | 39.08%  |
| 3     | 79        | 4.36%   |
| 0     | 60        | 3.31%   |
| 4     | 23        | 1.27%   |
| 6     | 8         | 0.44%   |
| 5     | 4         | 0.22%   |
| 10    | 1         | 0.06%   |
| 8     | 1         | 0.06%   |
| 7     | 1         | 0.06%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1491      | 80.59%  |
| Yes  | 359       | 19.41%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 608       | 56.56%  |
| Realtek Semiconductor           | 64        | 5.95%   |
| Broadcom                        | 61        | 5.67%   |
| Apple                           | 57        | 5.3%    |
| Qualcomm Atheros Communications | 51        | 4.74%   |
| Cambridge Silicon Radio         | 48        | 4.47%   |
| Foxconn / Hon Hai               | 37        | 3.44%   |
| Lite-On Technology              | 30        | 2.79%   |
| IMC Networks                    | 26        | 2.42%   |
| ASUSTek Computer                | 24        | 2.23%   |
| Hewlett-Packard                 | 13        | 1.21%   |
| Dell                            | 12        | 1.12%   |
| Ralink                          | 9         | 0.84%   |
| Marvell Semiconductor           | 7         | 0.65%   |
| MediaTek                        | 5         | 0.47%   |
| Toshiba                         | 3         | 0.28%   |
| Realtek                         | 3         | 0.28%   |
| Micro Star International        | 3         | 0.28%   |
| Alps Electric                   | 3         | 0.28%   |
| Ralink Technology               | 2         | 0.19%   |
| Chicony Electronics             | 2         | 0.19%   |
| USI                             | 1         | 0.09%   |
| Taiyo Yuden                     | 1         | 0.09%   |
| Logitech                        | 1         | 0.09%   |
| Integrated System Solution      | 1         | 0.09%   |
| Fujitsu                         | 1         | 0.09%   |
| Foxconn International           | 1         | 0.09%   |
| Edimax Technology               | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 242       | 22.47%  |
| Intel Bluetooth Device                              | 116       | 10.77%  |
| Intel AX200 Bluetooth                               | 107       | 9.94%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 73        | 6.78%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 48        | 4.46%   |
| Realtek Bluetooth Radio                             | 40        | 3.71%   |
| Intel Wireless-AC 3168 Bluetooth                    | 21        | 1.95%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 20        | 1.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 20        | 1.86%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 20        | 1.86%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 19        | 1.76%   |
| Realtek  Bluetooth 4.2 Adapter                      | 18        | 1.67%   |
| Apple Bluetooth Host Controller                     | 18        | 1.67%   |
| Lite-On Bluetooth Device                            | 14        | 1.3%    |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 1.3%    |
| IMC Networks Bluetooth Radio                        | 13        | 1.21%   |
| Qualcomm Atheros  Bluetooth Device                  | 12        | 1.11%   |
| Apple Bluetooth USB Host Controller                 | 12        | 1.11%   |
| Intel AX210 Bluetooth                               | 11        | 1.02%   |
| Foxconn / Hon Hai BCM20702A0                        | 11        | 1.02%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 11        | 1.02%   |
| Foxconn / Hon Hai Bluetooth Device                  | 10        | 0.93%   |
| Ralink RT3290 Bluetooth                             | 9         | 0.84%   |
| Lite-On Atheros AR3012 Bluetooth                    | 9         | 0.84%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 0.84%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 8         | 0.74%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 8         | 0.74%   |
| Apple Bluetooth HCI                                 | 8         | 0.74%   |
| HP Broadcom 2070 Bluetooth Combo                    | 6         | 0.56%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 0.56%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 6         | 0.56%   |
| MediaTek Wireless_Device                            | 5         | 0.46%   |
| Marvell Bluetooth and Wireless LAN Composite        | 5         | 0.46%   |
| IMC Networks Wireless_Device                        | 5         | 0.46%   |
| Dell DW375 Bluetooth Module                         | 5         | 0.46%   |
| IMC Networks Bluetooth Device                       | 4         | 0.37%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 4         | 0.37%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 4         | 0.37%   |
| ASUS Qualcomm Bluetooth 4.1                         | 4         | 0.37%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 4         | 0.37%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 1359      | 54.89%  |
| Nvidia                    | 458       | 18.5%   |
| AMD                       | 395       | 15.95%  |
| Logitech                  | 28        | 1.13%   |
| GN Netcom                 | 26        | 1.05%   |
| C-Media Electronics       | 26        | 1.05%   |
| Lenovo                    | 14        | 0.57%   |
| Plantronics               | 10        | 0.4%    |
| Hewlett-Packard           | 10        | 0.4%    |
| ASUSTek Computer          | 9         | 0.36%   |
| SteelSeries ApS           | 8         | 0.32%   |
| RODE Microphones          | 8         | 0.32%   |
| Realtek Semiconductor     | 8         | 0.32%   |
| Kingston Technology       | 8         | 0.32%   |
| Creative Labs             | 8         | 0.32%   |
| BEHRINGER International   | 6         | 0.24%   |
| Apple                     | 6         | 0.24%   |
| Texas Instruments         | 5         | 0.2%    |
| Razer USA                 | 5         | 0.2%    |
| Samson Technologies       | 4         | 0.16%   |
| Generalplus Technology    | 4         | 0.16%   |
| Creative Technology       | 3         | 0.12%   |
| Corsair                   | 3         | 0.12%   |
| Conexant Systems          | 3         | 0.12%   |
| Yamaha                    | 2         | 0.08%   |
| XMOS                      | 2         | 0.08%   |
| VIA Technologies          | 2         | 0.08%   |
| TerraTec Electronic       | 2         | 0.08%   |
| Tenx Technology           | 2         | 0.08%   |
| Sennheiser Communications | 2         | 0.08%   |
| Roland                    | 2         | 0.08%   |
| ROCCAT                    | 2         | 0.08%   |
| Magic Control Technology  | 2         | 0.08%   |
| JMTek                     | 2         | 0.08%   |
| HiFiBerry                 | 2         | 0.08%   |
| GYROCOM C&C               | 2         | 0.08%   |
| Giga-Byte Technology      | 2         | 0.08%   |
| Focusrite-Novation        | 2         | 0.08%   |
| AudioQuest                | 2         | 0.08%   |
| Audinate                  | 2         | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 174       | 6.08%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 138       | 4.82%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 105       | 3.67%   |
| AMD Family 17h/19h HD Audio Controller                                     | 100       | 3.5%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 88        | 3.08%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 77        | 2.69%   |
| AMD Starship/Matisse HD Audio Controller                                   | 71        | 2.48%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 69        | 2.41%   |
| Intel Cannon Lake PCH cAVS                                                 | 67        | 2.34%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 66        | 2.31%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 65        | 2.27%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 59        | 2.06%   |
| Intel Haswell-ULT HD Audio Controller                                      | 58        | 2.03%   |
| Intel 8 Series HD Audio Controller                                         | 58        | 2.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 58        | 2.03%   |
| Intel 200 Series PCH HD Audio                                              | 53        | 1.85%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 43        | 1.5%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 43        | 1.5%    |
| Nvidia GK107 HDMI Audio Controller                                         | 41        | 1.43%   |
| Nvidia GP107GL High Definition Audio Controller                            | 38        | 1.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 37        | 1.29%   |
| Intel Comet Lake PCH-LP cAVS                                               | 36        | 1.26%   |
| Intel Broadwell-U Audio Controller                                         | 36        | 1.26%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 35        | 1.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 32        | 1.12%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 28        | 0.98%   |
| Nvidia GP104 High Definition Audio Controller                              | 26        | 0.91%   |
| Intel Comet Lake PCH cAVS                                                  | 26        | 0.91%   |
| Nvidia GP102 HDMI Audio Controller                                         | 25        | 0.87%   |
| Nvidia GF108 High Definition Audio Controller                              | 25        | 0.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 24        | 0.84%   |
| Nvidia GK104 HDMI Audio Controller                                         | 24        | 0.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 24        | 0.84%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 24        | 0.84%   |
| AMD FCH Azalia Controller                                                  | 24        | 0.84%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 23        | 0.8%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 23        | 0.8%    |
| Nvidia GF119 HDMI Audio Controller                                         | 20        | 0.7%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 20        | 0.7%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 19        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 297       | 24.87%  |
| SK hynix            | 223       | 18.68%  |
| Kingston            | 178       | 14.91%  |
| Micron Technology   | 126       | 10.55%  |
| Corsair             | 121       | 10.13%  |
| Unknown             | 90        | 7.54%   |
| Crucial             | 45        | 3.77%   |
| G.Skill             | 32        | 2.68%   |
| Elpida              | 16        | 1.34%   |
| A-DATA Technology   | 13        | 1.09%   |
| Ramaxel Technology  | 11        | 0.92%   |
| Unknown             | 6         | 0.5%    |
| Patriot             | 5         | 0.42%   |
| Nanya Technology    | 5         | 0.42%   |
| Unknown (ABCD)      | 3         | 0.25%   |
| Hewlett-Packard     | 3         | 0.25%   |
| Avant               | 3         | 0.25%   |
| Unknown (0x9801)    | 2         | 0.17%   |
| Apacer              | 2         | 0.17%   |
| Unknown (08AE)      | 1         | 0.08%   |
| Unifosa             | 1         | 0.08%   |
| Princeton           | 1         | 0.08%   |
| Patriot Memory      | 1         | 0.08%   |
| OnBoard             | 1         | 0.08%   |
| OCZ                 | 1         | 0.08%   |
| KANMEIQi            | 1         | 0.08%   |
| HPE                 | 1         | 0.08%   |
| G-Alantic           | 1         | 0.08%   |
| ASint Technology    | 1         | 0.08%   |
| Advantech           | 1         | 0.08%   |
| A-DA                | 1         | 0.08%   |
| 48spaces            | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 13        | 1.01%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 13        | 1.01%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 12        | 0.93%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 11        | 0.85%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 11        | 0.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.7%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.62%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.54%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.54%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.54%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 7         | 0.54%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 7         | 0.54%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.54%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.46%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.46%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.46%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.46%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 0.46%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.46%   |
| Micron RAM MT52L1G32D4PG-093 8GB Row Of Chips LPDDR3 2133MT/s    | 6         | 0.46%   |
| Corsair RAM CMK32GX4M2B3000C15 16GB DIMM DDR4 3000MT/s           | 6         | 0.46%   |
| Unknown                                                          | 6         | 0.46%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                     | 5         | 0.39%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.39%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 5         | 0.39%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s           | 5         | 0.39%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 5         | 0.39%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 5         | 0.39%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 5         | 0.39%   |
| Samsung RAM K4EBE304EB-EGCG 8GB Row Of Chips LPDDR3 2133MT/s     | 5         | 0.39%   |
| Kingston RAM 99U5471-020.A00LF 4GB DIMM DDR3 1600MT/s            | 5         | 0.39%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 5         | 0.39%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 5         | 0.39%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 4         | 0.31%   |
| SK hynix RAM Module 8192MB Row Of Chips LPDDR3 2133MT/s          | 4         | 0.31%   |
| SK hynix RAM Module 16384MB SODIMM DDR4 2667MT/s                 | 4         | 0.31%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.31%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 4         | 0.31%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8192MB DIMM DDR4 2400MT/s          | 4         | 0.31%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 4         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 529       | 48.98%  |
| DDR3    | 378       | 35%     |
| LPDDR3  | 52        | 4.81%   |
| LPDDR4  | 39        | 3.61%   |
| DDR2    | 35        | 3.24%   |
| Unknown | 19        | 1.76%   |
| SDRAM   | 15        | 1.39%   |
| DDR5    | 5         | 0.46%   |
| DDR     | 5         | 0.46%   |
| LPDDR5  | 3         | 0.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 544       | 50.6%   |
| DIMM         | 430       | 40%     |
| Row Of Chips | 86        | 8%      |
| Chip         | 8         | 0.74%   |
| RIMM         | 3         | 0.28%   |
| Unknown      | 3         | 0.28%   |
| FB-DIMM      | 1         | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 478       | 41.42%  |
| 4096  | 263       | 22.79%  |
| 16384 | 235       | 20.36%  |
| 2048  | 106       | 9.19%   |
| 32768 | 42        | 3.64%   |
| 1024  | 26        | 2.25%   |
| 65536 | 3         | 0.26%   |
| 512   | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 232       | 20.12%  |
| 2667    | 166       | 14.4%   |
| 3200    | 158       | 13.7%   |
| 2133    | 100       | 8.67%   |
| 1333    | 86        | 7.46%   |
| 2400    | 82        | 7.11%   |
| 1334    | 40        | 3.47%   |
| 3600    | 27        | 2.34%   |
| 800     | 25        | 2.17%   |
| 1867    | 20        | 1.73%   |
| 2666    | 19        | 1.65%   |
| 4267    | 18        | 1.56%   |
| 3400    | 17        | 1.47%   |
| 3000    | 17        | 1.47%   |
| 1067    | 15        | 1.3%    |
| 667     | 14        | 1.21%   |
| Unknown | 10        | 0.87%   |
| 1066    | 9         | 0.78%   |
| 3266    | 8         | 0.69%   |
| 4800    | 7         | 0.61%   |
| 3733    | 7         | 0.61%   |
| 3466    | 7         | 0.61%   |
| 8400    | 5         | 0.43%   |
| 2933    | 5         | 0.43%   |
| 2000    | 5         | 0.43%   |
| 4266    | 4         | 0.35%   |
| 3666    | 4         | 0.35%   |
| 2465    | 4         | 0.35%   |
| 2048    | 4         | 0.35%   |
| 1866    | 4         | 0.35%   |
| 6400    | 3         | 0.26%   |
| 4199    | 3         | 0.26%   |
| 3100    | 3         | 0.26%   |
| 333     | 3         | 0.26%   |
| 3800    | 2         | 0.17%   |
| 3500    | 2         | 0.17%   |
| 3334    | 2         | 0.17%   |
| 2800    | 2         | 0.17%   |
| 975     | 2         | 0.17%   |
| 266     | 2         | 0.17%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Hewlett-Packard          | 23        | 46%     |
| Brother Industries       | 12        | 24%     |
| Samsung Electronics      | 4         | 8%      |
| Canon                    | 4         | 8%      |
| Oki Data                 | 2         | 4%      |
| Zhuhai Poskey Technology | 1         | 2%      |
| Seiko Epson              | 1         | 2%      |
| Prolific Technology      | 1         | 2%      |
| Konica Minolta           | 1         | 2%      |
| Dymo-CoStar              | 1         | 2%      |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Samsung M337x 387x 407x Series                             | 2         | 4%      |
| Oki Data USB Device                                        | 2         | 4%      |
| HP OfficeJet Pro 7730 series                               | 2         | 4%      |
| HP OfficeJet 6950                                          | 2         | 4%      |
| HP LaserJet Pro M148f-M149f                                | 2         | 4%      |
| HP ENVY 5540 series                                        | 2         | 4%      |
| HP Deskjet 2540 series                                     | 2         | 4%      |
| Zhuhai Poskey Printer                                      | 1         | 2%      |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 2%      |
| Samsung M332x 382x 402x Series                             | 1         | 2%      |
| Samsung C48x Series                                        | 1         | 2%      |
| Prolific PL2305 Parallel Port                              | 1         | 2%      |
| Konica Minolta Printer                                     | 1         | 2%      |
| HP Smart Tank Plus 550 series                              | 1         | 2%      |
| HP Smart Tank 7000 series                                  | 1         | 2%      |
| HP Officejet 4630 series                                   | 1         | 2%      |
| HP LaserJet P3010 Series                                   | 1         | 2%      |
| HP LaserJet P2055 series                                   | 1         | 2%      |
| HP Laserjet P1505                                          | 1         | 2%      |
| HP LaserJet 3050                                           | 1         | 2%      |
| HP LaserJet 1320                                           | 1         | 2%      |
| HP LaserJet 1020                                           | 1         | 2%      |
| HP Laser 107a                                              | 1         | 2%      |
| HP ENVY Photo 6200 series                                  | 1         | 2%      |
| HP ENVY 4520 series                                        | 1         | 2%      |
| HP DeskJet F2100 Printer series                            | 1         | 2%      |
| Dymo-CoStar LabelWriter 450                                | 1         | 2%      |
| Canon TS3300 series                                        | 1         | 2%      |
| Canon PIXMA TS6250                                         | 1         | 2%      |
| Canon PIXMA MX450 Series                                   | 1         | 2%      |
| Canon iP7200 series                                        | 1         | 2%      |
| Brother Printer                                            | 1         | 2%      |
| Brother MFC-9320CW                                         | 1         | 2%      |
| Brother MFC Composite Device                               | 1         | 2%      |
| Brother HL-L2360D series                                   | 1         | 2%      |
| Brother HL-L2350DW series                                  | 1         | 2%      |
| Brother HL-3140CW series                                   | 1         | 2%      |
| Brother HL-3040CN series                                   | 1         | 2%      |
| Brother HL-2130 series                                     | 1         | 2%      |
| Brother HL-2030 Laser Printer                              | 1         | 2%      |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Canon             | 7         | 53.85%  |
| Seiko Epson       | 3         | 23.08%  |
| Hewlett-Packard   | 2         | 15.38%  |
| Canon Electronics | 1         | 7.69%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 220                                 | 2         | 15.38%  |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]             | 1         | 7.69%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 7.69%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 7.69%   |
| HP ScanJet 4070 PhotoSmart                              | 1         | 7.69%   |
| HP ScanJet 2400c                                        | 1         | 7.69%   |
| Canon P-150 Scanner                                     | 1         | 7.69%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 7.69%   |
| Canon CanoScan N650U/N656U                              | 1         | 7.69%   |
| Canon CanoScan LIDE 25                                  | 1         | 7.69%   |
| Canon CanoScan LiDE 200                                 | 1         | 7.69%   |
| Canon CanoScan LiDE 100                                 | 1         | 7.69%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 286       | 28.34%  |
| IMC Networks                           | 79        | 7.83%   |
| Acer                                   | 73        | 7.23%   |
| Logitech                               | 69        | 6.84%   |
| Microdia                               | 61        | 6.05%   |
| Apple                                  | 58        | 5.75%   |
| Realtek Semiconductor                  | 49        | 4.86%   |
| Quanta                                 | 44        | 4.36%   |
| Sunplus Innovation Technology          | 43        | 4.26%   |
| Cheng Uei Precision Industry (Foxlink) | 40        | 3.96%   |
| Lite-On Technology                     | 33        | 3.27%   |
| Suyin                                  | 29        | 2.87%   |
| Syntek                                 | 17        | 1.68%   |
| Lenovo                                 | 16        | 1.59%   |
| Samsung Electronics                    | 11        | 1.09%   |
| Ricoh                                  | 11        | 1.09%   |
| Luxvisions Innotech Limited            | 11        | 1.09%   |
| Alcor Micro                            | 11        | 1.09%   |
| Microsoft                              | 10        | 0.99%   |
| Silicon Motion                         | 7         | 0.69%   |
| Z-Star Microelectronics                | 5         | 0.5%    |
| Primax Electronics                     | 5         | 0.5%    |
| Generalplus Technology                 | 3         | 0.3%    |
| ALi                                    | 3         | 0.3%    |
| Xiaomi                                 | 2         | 0.2%    |
| Tripath Technology                     | 2         | 0.2%    |
| OmniVision Technologies                | 2         | 0.2%    |
| MacroSilicon                           | 2         | 0.2%    |
| Genesys Logic                          | 2         | 0.2%    |
| DigiTech                               | 2         | 0.2%    |
| Creative Technology                    | 2         | 0.2%    |
| YGTek                                  | 1         | 0.1%    |
| WCM_USB                                | 1         | 0.1%    |
| Tobii Technology AB                    | 1         | 0.1%    |
| Sonix Technology                       | 1         | 0.1%    |
| Pixart Imaging                         | 1         | 0.1%    |
| Novatek Microelectronics               | 1         | 0.1%    |
| Nikon                                  | 1         | 0.1%    |
| Mimaki Engineering                     | 1         | 0.1%    |
| Leap Motion                            | 1         | 0.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 66        | 6.43%   |
| IMC Networks Integrated Camera          | 35        | 3.41%   |
| Microdia Integrated_Webcam_HD           | 33        | 3.22%   |
| Chicony HD WebCam                       | 31        | 3.02%   |
| Chicony HP HD Camera                    | 23        | 2.24%   |
| Acer Integrated Camera                  | 19        | 1.85%   |
| Apple Built-in iSight                   | 18        | 1.75%   |
| Realtek Integrated_Webcam_HD            | 17        | 1.66%   |
| IMC Networks USB2.0 HD UVC WebCam       | 17        | 1.66%   |
| Lite-On Integrated Camera               | 16        | 1.56%   |
| Apple FaceTime HD Camera (Built-in)     | 15        | 1.46%   |
| Quanta HP HD Camera                     | 14        | 1.36%   |
| Logitech HD Pro Webcam C920             | 13        | 1.27%   |
| Chicony USB2.0 Camera                   | 13        | 1.27%   |
| Chicony HP Wide Vision HD Camera        | 13        | 1.27%   |
| Sunplus HD WebCam                       | 11        | 1.07%   |
| Samsung Galaxy A5 (MTP)                 | 11        | 1.07%   |
| Chicony HP Truevision HD                | 11        | 1.07%   |
| Apple iPhone 5/5C/5S/6/SE               | 10        | 0.97%   |
| Acer Lenovo EasyCamera                  | 10        | 0.97%   |
| Sunplus Integrated_Webcam_HD            | 9         | 0.88%   |
| Logitech Webcam C270                    | 9         | 0.88%   |
| Chicony Integrated Camera (1280x720@30) | 9         | 0.88%   |
| Syntek Integrated Camera                | 8         | 0.78%   |
| Microdia Integrated Webcam              | 8         | 0.78%   |
| Lite-On HP HD Camera                    | 8         | 0.78%   |
| Chicony HD User Facing                  | 8         | 0.78%   |
| Suyin HP Truevision HD                  | 7         | 0.68%   |
| Lenovo Integrated Webcam                | 7         | 0.68%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 7         | 0.68%   |
| Chicony VGA WebCam                      | 7         | 0.68%   |
| Apple FaceTime HD Camera                | 7         | 0.68%   |
| Syntek Lenovo EasyCamera                | 6         | 0.58%   |
| Realtek USB2.0 HD UVC WebCam            | 6         | 0.58%   |
| Quanta HD Webcam                        | 6         | 0.58%   |
| Lenovo Integrated Webcam [R5U877]       | 6         | 0.58%   |
| Chicony HP HD Webcam                    | 6         | 0.58%   |
| Chicony CNF9055 Toshiba Webcam          | 6         | 0.58%   |
| Acer SunplusIT Integrated Camera        | 6         | 0.58%   |
| Acer BisonCam,NB Pro                    | 6         | 0.58%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 117       | 37.38%  |
| Synaptics                  | 111       | 35.46%  |
| Shenzhen Goodix Technology | 26        | 8.31%   |
| Upek                       | 17        | 5.43%   |
| Elan Microelectronics      | 16        | 5.11%   |
| AuthenTec                  | 14        | 4.47%   |
| LighTuning Technology      | 10        | 3.19%   |
| STMicroelectronics         | 2         | 0.64%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 38        | 12.14%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 25        | 7.99%   |
| Unknown                                                                    | 25        | 7.99%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 17        | 5.43%   |
| Validity Sensors Synaptics WBDI                                            | 14        | 4.47%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 13        | 4.15%   |
| Synaptics  WBDI                                                            | 12        | 3.83%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 12        | 3.83%   |
| Shenzhen Goodix  Fingerprint Device                                        | 11        | 3.51%   |
| Elan ELAN:ARM-M4                                                           | 11        | 3.51%   |
| Shenzhen Goodix Fingerprint Reader                                         | 10        | 3.19%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 9         | 2.88%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 2.88%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 9         | 2.88%   |
| Validity Sensors VFS491                                                    | 8         | 2.56%   |
| Validity Sensors Fingerprint scanner                                       | 8         | 2.56%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 7         | 2.24%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 7         | 2.24%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 2.24%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 1.92%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 5         | 1.6%    |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 5         | 1.6%    |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.6%    |
| Elan ELAN:Fingerprint                                                      | 5         | 1.6%    |
| AuthenTec AES2810                                                          | 5         | 1.6%    |
| AuthenTec AES2501 Fingerprint Sensor                                       | 5         | 1.6%    |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1.28%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.28%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.96%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 0.64%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.64%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 2         | 0.64%   |
| STMicroelectronics Fingerprint Reader                                      | 2         | 0.64%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 0.64%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.32%   |
| Synaptics WBDI Device                                                      | 1         | 0.32%   |
| LighTuning Fingerprint Sensor                                              | 1         | 0.32%   |
| LighTuning Fingerprint Reader                                              | 1         | 0.32%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Alcor Micro               | 41        | 40.2%   |
| Broadcom                  | 35        | 34.31%  |
| Upek                      | 9         | 8.82%   |
| Yubico.com                | 4         | 3.92%   |
| O2 Micro                  | 3         | 2.94%   |
| Lenovo                    | 3         | 2.94%   |
| Clay Logic                | 2         | 1.96%   |
| OmniKey                   | 1         | 0.98%   |
| Gemalto (was Gemplus)     | 1         | 0.98%   |
| BIT4ID                    | 1         | 0.98%   |
| Aladdin Knowledge Systems | 1         | 0.98%   |
| Advanced Card Systems     | 1         | 0.98%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 41        | 40.2%   |
| Broadcom BCM5880 Secure Applications Processor                               | 12        | 11.76%  |
| Broadcom 5880                                                                | 10        | 9.8%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 8.82%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 6.86%   |
| Broadcom 58200                                                               | 6         | 5.88%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 2.94%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 2.94%   |
| Lenovo Integrated Smart Card Reader                                          | 3         | 2.94%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 0.98%   |
| OmniKey CardMan 4321                                                         | 1         | 0.98%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.98%   |
| Clay Logic Nitrokey Start                                                    | 1         | 0.98%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 0.98%   |
| BIT4ID miniLector-S                                                          | 1         | 0.98%   |
| Aladdin Knowledge Systems Token JC                                           | 1         | 0.98%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.98%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1207      | 64.82%  |
| 1     | 504       | 27.07%  |
| 2     | 116       | 6.23%   |
| 3     | 22        | 1.18%   |
| 4     | 9         | 0.48%   |
| 7     | 2         | 0.11%   |
| 6     | 2         | 0.11%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 308       | 37.52%  |
| Graphics card            | 127       | 15.47%  |
| Net/wireless             | 88        | 10.72%  |
| Chipcard                 | 85        | 10.35%  |
| Communication controller | 43        | 5.24%   |
| Multimedia controller    | 42        | 5.12%   |
| Unassigned class         | 30        | 3.65%   |
| Camera                   | 22        | 2.68%   |
| Bluetooth                | 19        | 2.31%   |
| Sound                    | 12        | 1.46%   |
| Card reader              | 12        | 1.46%   |
| Net/ethernet             | 9         | 1.1%    |
| Storage                  | 6         | 0.73%   |
| Network                  | 5         | 0.61%   |
| Modem                    | 5         | 0.61%   |
| Dvb card                 | 3         | 0.37%   |
| Storage/nvme             | 2         | 0.24%   |
| Wireless                 | 1         | 0.12%   |
| Storage/raid             | 1         | 0.12%   |
| Flash memory             | 1         | 0.12%   |

