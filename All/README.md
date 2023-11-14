Linux - Tested Hardware & Statistics
------------------------------------

A project to collect tested hardware configurations for Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Desktop/README.md) and [notebooks](/Notebook/README.md).

Distribution-specific reports: [AlmaLinux](/Dist/AlmaLinux), [Alpine](/Dist/Alpine), [ALT_Linux](/Dist/ALT_Linux), [antiX](/Dist/antiX), [Artix](/Dist/Artix), [Chrome_OS](/Dist/Chrome_OS), [Clear_Linux](/Dist/Clear_Linux), [Deepin](/Dist/Deepin), [Devuan](/Dist/Devuan), [EndeavourOS](/Dist/EndeavourOS), [Garuda_Linux](/Dist/Garuda_Linux), [GNOME_OS](/Dist/GNOME_OS), [Kaisen](/Dist/Kaisen), [Mageia](/Dist/Mageia), [Makulu](/Dist/Makulu), [NixOS](/Dist/NixOS), [Nobara](/Dist/Nobara), [Oracle_Linux](/Dist/Oracle_Linux), [Pardus](/Dist/Pardus), [PureOS](/Dist/PureOS), [Q4OS](/Dist/Q4OS), [Reborn_OS](/Dist/Reborn_OS), [Rocky_Linux](/Dist/Rocky_Linux), [Sparky](/Dist/Sparky), [Void_Linux](/Dist/Void_Linux), [Xero](/Dist/Xero).

This report is for real hardware. Report for virtual hardware: [TestDays_VE](https://github.com/linuxhw/TestDays_VE)

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

Total: 346086

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [ef03031eaa](https://linux-hardware.org/?probe=ef03031eaa) | Nov 06, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [26332591d7](https://linux-hardware.org/?probe=26332591d7) | Nov 06, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [cc6b66c576](https://linux-hardware.org/?probe=cc6b66c576) | Nov 06, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [725ce23e28](https://linux-hardware.org/?probe=725ce23e28) | Nov 06, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | Notebook    | [88cc97d0be](https://linux-hardware.org/?probe=88cc97d0be) | Nov 06, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [a22610f17c](https://linux-hardware.org/?probe=a22610f17c) | Nov 06, 2023 |
| Pegatron      | 2AF0                        | Desktop     | [d918aae63e](https://linux-hardware.org/?probe=d918aae63e) | Nov 06, 2023 |
| GMKtec        | NucBox K2                   | Desktop     | [a88d491579](https://linux-hardware.org/?probe=a88d491579) | Nov 06, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [df52b675c8](https://linux-hardware.org/?probe=df52b675c8) | Nov 06, 2023 |
| Medion        | MS-7708                     | Desktop     | [9170f4dd42](https://linux-hardware.org/?probe=9170f4dd42) | Nov 06, 2023 |
| Lenovo        | 1038 NO DPK                 | Server      | [fe01dc6819](https://linux-hardware.org/?probe=fe01dc6819) | Nov 06, 2023 |
| Unknown       | HX90                        | Desktop     | [bc832d475f](https://linux-hardware.org/?probe=bc832d475f) | Nov 06, 2023 |
| Apple         | MacBookPro11,3              | Notebook    | [0009d8a468](https://linux-hardware.org/?probe=0009d8a468) | Nov 06, 2023 |
| Lenovo        | Yoga 7 14ITL5 82BH          | Convertible | [27b2ce4d8c](https://linux-hardware.org/?probe=27b2ce4d8c) | Nov 06, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f459ffa824](https://linux-hardware.org/?probe=f459ffa824) | Nov 06, 2023 |
| Aquarius      | NS585                       | Notebook    | [ddc8256647](https://linux-hardware.org/?probe=ddc8256647) | Nov 06, 2023 |
| Acer          | TMP645-M                    | Notebook    | [a062c55357](https://linux-hardware.org/?probe=a062c55357) | Nov 06, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [77a31d50ce](https://linux-hardware.org/?probe=77a31d50ce) | Nov 06, 2023 |
| Lenovo        | ThinkPad T480s 20L7002HU... | Notebook    | [f09ace6b9d](https://linux-hardware.org/?probe=f09ace6b9d) | Nov 06, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [ccc7d658ea](https://linux-hardware.org/?probe=ccc7d658ea) | Nov 06, 2023 |
| Unknown       | HX90                        | Desktop     | [91269ec2b8](https://linux-hardware.org/?probe=91269ec2b8) | Nov 06, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [27381bdf35](https://linux-hardware.org/?probe=27381bdf35) | Nov 06, 2023 |
| ASRock        | H110M-ITX                   | Desktop     | [c384352141](https://linux-hardware.org/?probe=c384352141) | Nov 06, 2023 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [d57d789e77](https://linux-hardware.org/?probe=d57d789e77) | Nov 06, 2023 |
| HP            | G61                         | Notebook    | [65f7664fe3](https://linux-hardware.org/?probe=65f7664fe3) | Nov 06, 2023 |
| HP            | 89E9 0100                   | All in one  | [5e98ad51b6](https://linux-hardware.org/?probe=5e98ad51b6) | Nov 06, 2023 |
| MSI           | A520M PRO                   | Desktop     | [b83b272494](https://linux-hardware.org/?probe=b83b272494) | Nov 06, 2023 |
| Dell          | Latitude E6420              | Notebook    | [9fd076e986](https://linux-hardware.org/?probe=9fd076e986) | Nov 06, 2023 |
| Lenovo        | 3734 SDK0R32862 WIN 3258... | All in one  | [b153378dab](https://linux-hardware.org/?probe=b153378dab) | Nov 06, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [f01a35c9a7](https://linux-hardware.org/?probe=f01a35c9a7) | Nov 06, 2023 |
| Lenovo        | ThinkPad E14 20RA002UHV     | Notebook    | [79a037e80b](https://linux-hardware.org/?probe=79a037e80b) | Nov 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [aef9c84cf7](https://linux-hardware.org/?probe=aef9c84cf7) | Nov 06, 2023 |
| Aquarius      | NS585                       | Notebook    | [2f4e49837d](https://linux-hardware.org/?probe=2f4e49837d) | Nov 06, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [ea2142174c](https://linux-hardware.org/?probe=ea2142174c) | Nov 06, 2023 |
| Lenovo        | IdeaPad 530S-14IKB 81EU     | Notebook    | [985ed440bf](https://linux-hardware.org/?probe=985ed440bf) | Nov 06, 2023 |
| HP            | 2B34                        | Desktop     | [52737869e2](https://linux-hardware.org/?probe=52737869e2) | Nov 06, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [279ac4ed92](https://linux-hardware.org/?probe=279ac4ed92) | Nov 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b63a038c08](https://linux-hardware.org/?probe=b63a038c08) | Nov 06, 2023 |
| HP            | 8594                        | Desktop     | [d51c507511](https://linux-hardware.org/?probe=d51c507511) | Nov 06, 2023 |
| Valve         | Jupiter                     | Notebook    | [d8ac880948](https://linux-hardware.org/?probe=d8ac880948) | Nov 06, 2023 |
| ASUSTek       | X751MA                      | Notebook    | [d5e1758d4e](https://linux-hardware.org/?probe=d5e1758d4e) | Nov 06, 2023 |
| HP            | 82A2                        | Desktop     | [1d34952ece](https://linux-hardware.org/?probe=1d34952ece) | Nov 06, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [9b0f4eeb46](https://linux-hardware.org/?probe=9b0f4eeb46) | Nov 06, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [cee650aa5a](https://linux-hardware.org/?probe=cee650aa5a) | Nov 06, 2023 |
| ASUSTek       | PRIME X299-A                | Desktop     | [8d9bbb07dd](https://linux-hardware.org/?probe=8d9bbb07dd) | Nov 06, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [b58de33b7d](https://linux-hardware.org/?probe=b58de33b7d) | Nov 06, 2023 |
| Aquarius      | NS585                       | Notebook    | [4fea63336a](https://linux-hardware.org/?probe=4fea63336a) | Nov 06, 2023 |
| Lenovo        | Yoga 14cACN 2021 82N7       | Convertible | [4f7bb0e30b](https://linux-hardware.org/?probe=4f7bb0e30b) | Nov 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [231b5b8ef8](https://linux-hardware.org/?probe=231b5b8ef8) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [5d63a1487d](https://linux-hardware.org/?probe=5d63a1487d) | Nov 06, 2023 |
| HP            | Pavilion dv8000 (ET839UA... | Notebook    | [ad7dc81954](https://linux-hardware.org/?probe=ad7dc81954) | Nov 06, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [9e50325ddd](https://linux-hardware.org/?probe=9e50325ddd) | Nov 06, 2023 |
| Lenovo        | IdeaPad 1 15ADA7 82R1       | Notebook    | [b88b3757af](https://linux-hardware.org/?probe=b88b3757af) | Nov 06, 2023 |
| Toshiba       | Satellite C855-10N          | Notebook    | [7afd607141](https://linux-hardware.org/?probe=7afd607141) | Nov 06, 2023 |
| Lenovo        | 1036 NO DPK                 | Desktop     | [6e0b8b9df9](https://linux-hardware.org/?probe=6e0b8b9df9) | Nov 06, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [37aa104ebf](https://linux-hardware.org/?probe=37aa104ebf) | Nov 06, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [5b992d974a](https://linux-hardware.org/?probe=5b992d974a) | Nov 06, 2023 |
| HP            | Spectre Pro x360 G2         | Convertible | [de099b29d0](https://linux-hardware.org/?probe=de099b29d0) | Nov 06, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [b5e4afb8e9](https://linux-hardware.org/?probe=b5e4afb8e9) | Nov 06, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [216faa6f5d](https://linux-hardware.org/?probe=216faa6f5d) | Nov 06, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [3734293144](https://linux-hardware.org/?probe=3734293144) | Nov 06, 2023 |
| MSI           | GL65 9SD                    | Notebook    | [d831c2e78e](https://linux-hardware.org/?probe=d831c2e78e) | Nov 06, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [bd3e108e8a](https://linux-hardware.org/?probe=bd3e108e8a) | Nov 06, 2023 |
| MSI           | B75MA-P45                   | Desktop     | [bfe1423965](https://linux-hardware.org/?probe=bfe1423965) | Nov 06, 2023 |
| Supermicro    | H12SSL-i                    | Server      | [0bcc882e05](https://linux-hardware.org/?probe=0bcc882e05) | Nov 06, 2023 |
| HP            | ENVY 15                     | Notebook    | [5f301610ee](https://linux-hardware.org/?probe=5f301610ee) | Nov 06, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [5fafb134cf](https://linux-hardware.org/?probe=5fafb134cf) | Nov 06, 2023 |
| HP            | ENVY 15                     | Notebook    | [150ca6a1a0](https://linux-hardware.org/?probe=150ca6a1a0) | Nov 06, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [37d32a1fd5](https://linux-hardware.org/?probe=37d32a1fd5) | Nov 06, 2023 |
| Dell          | OptiPlex 5050               | Desktop     | [6c4a08354b](https://linux-hardware.org/?probe=6c4a08354b) | Nov 06, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [ef019ff242](https://linux-hardware.org/?probe=ef019ff242) | Nov 06, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [f87e3a97c4](https://linux-hardware.org/?probe=f87e3a97c4) | Nov 06, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [b42102e397](https://linux-hardware.org/?probe=b42102e397) | Nov 06, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [7974075b64](https://linux-hardware.org/?probe=7974075b64) | Nov 06, 2023 |
| ASRockRack    | B650D4U-2L2T/BCM            | Server      | [963acb5f2b](https://linux-hardware.org/?probe=963acb5f2b) | Nov 06, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [bb021ca517](https://linux-hardware.org/?probe=bb021ca517) | Nov 06, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [b3e37dd334](https://linux-hardware.org/?probe=b3e37dd334) | Nov 06, 2023 |
| Dell          | Precision M4800             | Notebook    | [e67352eb0f](https://linux-hardware.org/?probe=e67352eb0f) | Nov 06, 2023 |
| MSI           | X99A RAIDER                 | Desktop     | [3a2a72df26](https://linux-hardware.org/?probe=3a2a72df26) | Nov 06, 2023 |
| Apple         | MacBookPro11,1              | Notebook    | [2d84377719](https://linux-hardware.org/?probe=2d84377719) | Nov 06, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [f5a032555f](https://linux-hardware.org/?probe=f5a032555f) | Nov 06, 2023 |
| Samsung       | DT1234567890 SEC_SW_REVI... | Desktop     | [4ef314d383](https://linux-hardware.org/?probe=4ef314d383) | Nov 06, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [3daa9909b3](https://linux-hardware.org/?probe=3daa9909b3) | Nov 06, 2023 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [4d3a7373ae](https://linux-hardware.org/?probe=4d3a7373ae) | Nov 06, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [5cfef4c0b7](https://linux-hardware.org/?probe=5cfef4c0b7) | Nov 06, 2023 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [f1d9fe0bb7](https://linux-hardware.org/?probe=f1d9fe0bb7) | Nov 06, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [6aaef57f51](https://linux-hardware.org/?probe=6aaef57f51) | Nov 06, 2023 |
| MSI           | MPG B650 CARBON WIFI        | Desktop     | [fcd42a2056](https://linux-hardware.org/?probe=fcd42a2056) | Nov 06, 2023 |
| HP            | ProBook 650 G1              | Notebook    | [e56fc59b28](https://linux-hardware.org/?probe=e56fc59b28) | Nov 06, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop E41... | Notebook    | [62b6928793](https://linux-hardware.org/?probe=62b6928793) | Nov 06, 2023 |
| Positivo      | C41TF                       | Notebook    | [4bb5f6150c](https://linux-hardware.org/?probe=4bb5f6150c) | Nov 06, 2023 |
| Lenovo        | ThinkPad Edge E431 62771... | Notebook    | [8d789a3937](https://linux-hardware.org/?probe=8d789a3937) | Nov 06, 2023 |
| TUXEDO        | Pulse 15 Gen2               | Notebook    | [10f2785958](https://linux-hardware.org/?probe=10f2785958) | Nov 06, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [24a052bf0c](https://linux-hardware.org/?probe=24a052bf0c) | Nov 06, 2023 |
| HP            | 245 G8                      | Notebook    | [e9c1cc78b8](https://linux-hardware.org/?probe=e9c1cc78b8) | Nov 06, 2023 |
| Lenovo        | ThinkPad T440s 20ARS0HB0... | Notebook    | [95376bfed1](https://linux-hardware.org/?probe=95376bfed1) | Nov 06, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [c8c8d15e25](https://linux-hardware.org/?probe=c8c8d15e25) | Nov 06, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [d643312744](https://linux-hardware.org/?probe=d643312744) | Nov 06, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [f575f3121e](https://linux-hardware.org/?probe=f575f3121e) | Nov 06, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [3333de3c07](https://linux-hardware.org/?probe=3333de3c07) | Nov 06, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [1da691596b](https://linux-hardware.org/?probe=1da691596b) | Nov 06, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [ac8533d263](https://linux-hardware.org/?probe=ac8533d263) | Nov 06, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [d385d4714c](https://linux-hardware.org/?probe=d385d4714c) | Nov 06, 2023 |
| GPU Compan... | GWNR71517                   | Notebook    | [7676ff267d](https://linux-hardware.org/?probe=7676ff267d) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [8447756322](https://linux-hardware.org/?probe=8447756322) | Nov 06, 2023 |
| Lenovo        | Y720-15IKB 80VR             | Notebook    | [7cc876dcfa](https://linux-hardware.org/?probe=7cc876dcfa) | Nov 06, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [290be8911e](https://linux-hardware.org/?probe=290be8911e) | Nov 06, 2023 |
| MSI           | B560M PRO-E                 | Desktop     | [89a24ae9fa](https://linux-hardware.org/?probe=89a24ae9fa) | Nov 06, 2023 |
| Lenovo        | 3743 SDK0T76463 WIN 3422... | Desktop     | [ce42858c1f](https://linux-hardware.org/?probe=ce42858c1f) | Nov 06, 2023 |
| Gigabyte      | AB350-Gaming-CF             | Desktop     | [ff44a3299b](https://linux-hardware.org/?probe=ff44a3299b) | Nov 06, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [af12dd22ba](https://linux-hardware.org/?probe=af12dd22ba) | Nov 06, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [c3e5415128](https://linux-hardware.org/?probe=c3e5415128) | Nov 06, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [18053575fc](https://linux-hardware.org/?probe=18053575fc) | Nov 06, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [72bedff7a6](https://linux-hardware.org/?probe=72bedff7a6) | Nov 06, 2023 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [c46040087a](https://linux-hardware.org/?probe=c46040087a) | Nov 06, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [ff199303a2](https://linux-hardware.org/?probe=ff199303a2) | Nov 06, 2023 |
| Shuttle       | XS35V3                      | Desktop     | [0c51d541de](https://linux-hardware.org/?probe=0c51d541de) | Nov 06, 2023 |
| Gigabyte      | B560M AORUS PRO AX          | Desktop     | [04327aa85c](https://linux-hardware.org/?probe=04327aa85c) | Nov 06, 2023 |
| ASUSTek       | X555LN                      | Notebook    | [7971055e99](https://linux-hardware.org/?probe=7971055e99) | Nov 06, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [17dda27251](https://linux-hardware.org/?probe=17dda27251) | Nov 06, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [c4d9d2cd13](https://linux-hardware.org/?probe=c4d9d2cd13) | Nov 06, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [52781b1111](https://linux-hardware.org/?probe=52781b1111) | Nov 06, 2023 |
| Lenovo        | ThinkPad T420 4180FB5       | Notebook    | [5abc3caec3](https://linux-hardware.org/?probe=5abc3caec3) | Nov 06, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [c8e2ba1336](https://linux-hardware.org/?probe=c8e2ba1336) | Nov 06, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [e005a7da3a](https://linux-hardware.org/?probe=e005a7da3a) | Nov 06, 2023 |
| Dell          | Latitude E6440              | Notebook    | [ad28c1e239](https://linux-hardware.org/?probe=ad28c1e239) | Nov 06, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a2ad36d26c](https://linux-hardware.org/?probe=a2ad36d26c) | Nov 06, 2023 |
| MSI           | Bravo 17 C7VF               | Notebook    | [5982277b4b](https://linux-hardware.org/?probe=5982277b4b) | Nov 06, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [9655bf2db1](https://linux-hardware.org/?probe=9655bf2db1) | Nov 06, 2023 |
| Lenovo        | ThinkPad P50 20EQS42M00     | Notebook    | [f4761a87e1](https://linux-hardware.org/?probe=f4761a87e1) | Nov 06, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [8cd8d5ade1](https://linux-hardware.org/?probe=8cd8d5ade1) | Nov 06, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [ce6a053669](https://linux-hardware.org/?probe=ce6a053669) | Nov 06, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [d61e270082](https://linux-hardware.org/?probe=d61e270082) | Nov 06, 2023 |
| Dell          | Latitude E6410              | Notebook    | [b6ac4a50b7](https://linux-hardware.org/?probe=b6ac4a50b7) | Nov 06, 2023 |
| ASUSTek       | P8Z77-M                     | Desktop     | [fef5a2e8ae](https://linux-hardware.org/?probe=fef5a2e8ae) | Nov 05, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [07ef51bd31](https://linux-hardware.org/?probe=07ef51bd31) | Nov 05, 2023 |
| Lenovo        | ThinkPad T480 20L6S5VP3U    | Notebook    | [ea70f0e597](https://linux-hardware.org/?probe=ea70f0e597) | Nov 05, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [b40c43c829](https://linux-hardware.org/?probe=b40c43c829) | Nov 05, 2023 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [6c8bb1840e](https://linux-hardware.org/?probe=6c8bb1840e) | Nov 05, 2023 |
| HP            | 83D0                        | Mini pc     | [4f947ffed7](https://linux-hardware.org/?probe=4f947ffed7) | Nov 05, 2023 |
| Dell          | Latitude E6410              | Notebook    | [ebdd852a85](https://linux-hardware.org/?probe=ebdd852a85) | Nov 05, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2430... | Notebook    | [658d6f150e](https://linux-hardware.org/?probe=658d6f150e) | Nov 05, 2023 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [d40cc6e0a4](https://linux-hardware.org/?probe=d40cc6e0a4) | Nov 05, 2023 |
| Dell          | Latitude 5590               | Notebook    | [913308d97b](https://linux-hardware.org/?probe=913308d97b) | Nov 05, 2023 |
| Dell          | Latitude D520               | Notebook    | [99c85f2153](https://linux-hardware.org/?probe=99c85f2153) | Nov 05, 2023 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [1cf99ffe12](https://linux-hardware.org/?probe=1cf99ffe12) | Nov 05, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [60ec029256](https://linux-hardware.org/?probe=60ec029256) | Nov 05, 2023 |
| Huanan        | X99-QD4 V1.0                | Desktop     | [3cedc8f704](https://linux-hardware.org/?probe=3cedc8f704) | Nov 05, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [67a1ec0ae8](https://linux-hardware.org/?probe=67a1ec0ae8) | Nov 05, 2023 |
| Dell          | 08WKV3 A00                  | Desktop     | [e16dbbaf8b](https://linux-hardware.org/?probe=e16dbbaf8b) | Nov 05, 2023 |
| Unknown       | H96 Max X3                  | Soc         | [362598f755](https://linux-hardware.org/?probe=362598f755) | Nov 05, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [35b7407efb](https://linux-hardware.org/?probe=35b7407efb) | Nov 05, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [415cb187a2](https://linux-hardware.org/?probe=415cb187a2) | Nov 05, 2023 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [105d51f329](https://linux-hardware.org/?probe=105d51f329) | Nov 05, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [0facd311dc](https://linux-hardware.org/?probe=0facd311dc) | Nov 05, 2023 |
| HP            | 198E                        | Desktop     | [f1d1b6839f](https://linux-hardware.org/?probe=f1d1b6839f) | Nov 05, 2023 |
| Dell          | Latitude D520               | Notebook    | [d56819f452](https://linux-hardware.org/?probe=d56819f452) | Nov 05, 2023 |
| Dell          | Inspiron 5459               | Notebook    | [fc242f51bf](https://linux-hardware.org/?probe=fc242f51bf) | Nov 05, 2023 |
| Lenovo        | 1038 NO DPK                 | Server      | [a8c249eafd](https://linux-hardware.org/?probe=a8c249eafd) | Nov 05, 2023 |
| ASUSTek       | P30AD                       | Desktop     | [63322c386f](https://linux-hardware.org/?probe=63322c386f) | Nov 05, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [a782c6c087](https://linux-hardware.org/?probe=a782c6c087) | Nov 05, 2023 |
| Dell          | 042P49 A02                  | Desktop     | [b8808915ed](https://linux-hardware.org/?probe=b8808915ed) | Nov 05, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [45dfbee68a](https://linux-hardware.org/?probe=45dfbee68a) | Nov 05, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [99a6c38b5d](https://linux-hardware.org/?probe=99a6c38b5d) | Nov 05, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [1cc495d15b](https://linux-hardware.org/?probe=1cc495d15b) | Nov 05, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [eef004b620](https://linux-hardware.org/?probe=eef004b620) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8ee603dbfc](https://linux-hardware.org/?probe=8ee603dbfc) | Nov 05, 2023 |
| HP            | Spectre Pro G1              | Notebook    | [78bce56071](https://linux-hardware.org/?probe=78bce56071) | Nov 05, 2023 |
| Lenovo        | ThinkPad T520 4243RU3       | Notebook    | [5095529d19](https://linux-hardware.org/?probe=5095529d19) | Nov 05, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [4bfe797838](https://linux-hardware.org/?probe=4bfe797838) | Nov 05, 2023 |
| Dell          | Latitude 7280               | Notebook    | [3f1419b0ea](https://linux-hardware.org/?probe=3f1419b0ea) | Nov 05, 2023 |
| Toshiba       | PORTEGE Z10t-A              | Notebook    | [600445b726](https://linux-hardware.org/?probe=600445b726) | Nov 05, 2023 |
| HP            | 2B05                        | Desktop     | [eb343bd373](https://linux-hardware.org/?probe=eb343bd373) | Nov 05, 2023 |
| HP            | ProBook 450 G5              | Notebook    | [6407166dd5](https://linux-hardware.org/?probe=6407166dd5) | Nov 05, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [67a67e246c](https://linux-hardware.org/?probe=67a67e246c) | Nov 05, 2023 |
| Pegatron      | 2AF0                        | Desktop     | [de892702f8](https://linux-hardware.org/?probe=de892702f8) | Nov 05, 2023 |
| Toshiba       | TECRA R950                  | Notebook    | [864877692e](https://linux-hardware.org/?probe=864877692e) | Nov 05, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [3a69031984](https://linux-hardware.org/?probe=3a69031984) | Nov 05, 2023 |
| MSI           | A55M-E33                    | Desktop     | [d1def05873](https://linux-hardware.org/?probe=d1def05873) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [254a87d641](https://linux-hardware.org/?probe=254a87d641) | Nov 05, 2023 |
| ASRock        | H81M-VG4 R2.0               | Desktop     | [2de5f4ef98](https://linux-hardware.org/?probe=2de5f4ef98) | Nov 05, 2023 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [cf8911c5e0](https://linux-hardware.org/?probe=cf8911c5e0) | Nov 05, 2023 |
| Lenovo        | IdeaPad 1 11IGL05 81VT      | Notebook    | [27923cd021](https://linux-hardware.org/?probe=27923cd021) | Nov 05, 2023 |
| MSI           | Z77 MPower                  | Desktop     | [9a199b462a](https://linux-hardware.org/?probe=9a199b462a) | Nov 05, 2023 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | Notebook    | [e25bb48957](https://linux-hardware.org/?probe=e25bb48957) | Nov 05, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [4a5e89566c](https://linux-hardware.org/?probe=4a5e89566c) | Nov 05, 2023 |
| ASRock        | X670E Taichi                | Desktop     | [6f05d717db](https://linux-hardware.org/?probe=6f05d717db) | Nov 05, 2023 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [25b39b698c](https://linux-hardware.org/?probe=25b39b698c) | Nov 05, 2023 |
| Dell          | XPS 17 9720                 | Notebook    | [39e8a692ae](https://linux-hardware.org/?probe=39e8a692ae) | Nov 05, 2023 |
| ASRock        | X670E Taichi                | Desktop     | [a366b27921](https://linux-hardware.org/?probe=a366b27921) | Nov 05, 2023 |
| ASUSTek       | X550WA                      | Notebook    | [8c15da796b](https://linux-hardware.org/?probe=8c15da796b) | Nov 05, 2023 |
| Dell          | 0JCTF8 A00                  | Desktop     | [b3669f73a8](https://linux-hardware.org/?probe=b3669f73a8) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [8e3e7668cf](https://linux-hardware.org/?probe=8e3e7668cf) | Nov 05, 2023 |
| MECHREVO      | Code 01 Series PF5NU1G      | Notebook    | [767c3ff7fa](https://linux-hardware.org/?probe=767c3ff7fa) | Nov 05, 2023 |
| Lenovo        | ThinkPad T480s 20L7002HU... | Notebook    | [92ef56cc92](https://linux-hardware.org/?probe=92ef56cc92) | Nov 05, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [c64e4d8a0b](https://linux-hardware.org/?probe=c64e4d8a0b) | Nov 05, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [00f864bd9e](https://linux-hardware.org/?probe=00f864bd9e) | Nov 05, 2023 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [62a888f71c](https://linux-hardware.org/?probe=62a888f71c) | Nov 05, 2023 |
| Inter Sale... | NID-11125DE                 | Notebook    | [aca3d534de](https://linux-hardware.org/?probe=aca3d534de) | Nov 05, 2023 |
| Sony          | VGN-N21S_W                  | Notebook    | [6ff4658440](https://linux-hardware.org/?probe=6ff4658440) | Nov 05, 2023 |
| Acer          | Swift SF113-31              | Notebook    | [a6fbe4af41](https://linux-hardware.org/?probe=a6fbe4af41) | Nov 05, 2023 |
| Sony          | VGN-N21S_W                  | Notebook    | [266bedfdc3](https://linux-hardware.org/?probe=266bedfdc3) | Nov 05, 2023 |
| Acer          | Predator PT516-52s          | Notebook    | [30b7a47643](https://linux-hardware.org/?probe=30b7a47643) | Nov 05, 2023 |
| Lenovo        | IdeaPad S410p 20296         | Notebook    | [61828bc39f](https://linux-hardware.org/?probe=61828bc39f) | Nov 05, 2023 |
| sunxi         | Banana Pi BPI-M2-Zero       | Soc         | [fc24faaa0c](https://linux-hardware.org/?probe=fc24faaa0c) | Nov 05, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [cff5d02cde](https://linux-hardware.org/?probe=cff5d02cde) | Nov 05, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [27740d5118](https://linux-hardware.org/?probe=27740d5118) | Nov 05, 2023 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [1c86a5a6de](https://linux-hardware.org/?probe=1c86a5a6de) | Nov 05, 2023 |
| Dell          | 0J1C3P A01                  | Desktop     | [8aefbb37f5](https://linux-hardware.org/?probe=8aefbb37f5) | Nov 05, 2023 |
| MSI           | MAG X670E TOMAHAWK WIFI     | Desktop     | [d95f04dd2c](https://linux-hardware.org/?probe=d95f04dd2c) | Nov 05, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [38b95c0462](https://linux-hardware.org/?probe=38b95c0462) | Nov 05, 2023 |
| ASRock        | Z68 Pro3                    | Desktop     | [e6c695d4a7](https://linux-hardware.org/?probe=e6c695d4a7) | Nov 05, 2023 |
| HP            | 1495                        | Desktop     | [fe18b89530](https://linux-hardware.org/?probe=fe18b89530) | Nov 05, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [42cbdffa93](https://linux-hardware.org/?probe=42cbdffa93) | Nov 05, 2023 |
| ASUSTek       | K401UB                      | Notebook    | [3bc894aa34](https://linux-hardware.org/?probe=3bc894aa34) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [4f690a4297](https://linux-hardware.org/?probe=4f690a4297) | Nov 05, 2023 |
| Lenovo        | XiaoXinPro 14 IRH8 83AL     | Notebook    | [de5461c78b](https://linux-hardware.org/?probe=de5461c78b) | Nov 05, 2023 |
| HP            | Unknown                     | Notebook    | [c8cff9e339](https://linux-hardware.org/?probe=c8cff9e339) | Nov 05, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [692601dd3b](https://linux-hardware.org/?probe=692601dd3b) | Nov 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [5c4543cc31](https://linux-hardware.org/?probe=5c4543cc31) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [f48ca40214](https://linux-hardware.org/?probe=f48ca40214) | Nov 05, 2023 |
| Dell          | Latitude E7450              | Notebook    | [71fe592aa3](https://linux-hardware.org/?probe=71fe592aa3) | Nov 05, 2023 |
| Medion        | TJ4125                      | Desktop     | [65a059325e](https://linux-hardware.org/?probe=65a059325e) | Nov 05, 2023 |
| ASUSTek       | PRIME J4005I-C              | Desktop     | [76b89da142](https://linux-hardware.org/?probe=76b89da142) | Nov 05, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [9d79aa9486](https://linux-hardware.org/?probe=9d79aa9486) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [4bf4b470a0](https://linux-hardware.org/?probe=4bf4b470a0) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [8e8cfaa103](https://linux-hardware.org/?probe=8e8cfaa103) | Nov 05, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [a0450fee29](https://linux-hardware.org/?probe=a0450fee29) | Nov 05, 2023 |
| ASUSTek       | X541NA                      | Notebook    | [f0399efc08](https://linux-hardware.org/?probe=f0399efc08) | Nov 05, 2023 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [8e5ae08c12](https://linux-hardware.org/?probe=8e5ae08c12) | Nov 05, 2023 |
| Acidanther... | Mac-CFF7D910A743CAAF iMa... | All in one  | [4601ae11d9](https://linux-hardware.org/?probe=4601ae11d9) | Nov 05, 2023 |
| Chuwi         | LarkBox X                   | Mini pc     | [21d2f3c41d](https://linux-hardware.org/?probe=21d2f3c41d) | Nov 05, 2023 |
| MSI           | MEG Z590 UNIFY              | Desktop     | [1f84fe45f8](https://linux-hardware.org/?probe=1f84fe45f8) | Nov 05, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [a00f71e5d3](https://linux-hardware.org/?probe=a00f71e5d3) | Nov 05, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [5cff6ffdfc](https://linux-hardware.org/?probe=5cff6ffdfc) | Nov 05, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [82bf4f530a](https://linux-hardware.org/?probe=82bf4f530a) | Nov 05, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [436a3dc68e](https://linux-hardware.org/?probe=436a3dc68e) | Nov 05, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [5f192519d4](https://linux-hardware.org/?probe=5f192519d4) | Nov 05, 2023 |
| HP            | 1497                        | Desktop     | [734abf0595](https://linux-hardware.org/?probe=734abf0595) | Nov 05, 2023 |
| HP            | ProBook 6470b               | Notebook    | [50c1d43281](https://linux-hardware.org/?probe=50c1d43281) | Nov 05, 2023 |
| HP            | ProBook 440 G7              | Notebook    | [1d1311204e](https://linux-hardware.org/?probe=1d1311204e) | Nov 05, 2023 |
| Dell          | 0J8H4R A00                  | Desktop     | [d743b33cc7](https://linux-hardware.org/?probe=d743b33cc7) | Nov 05, 2023 |
| HP            | Pavilion 17                 | Notebook    | [50a9cf65b3](https://linux-hardware.org/?probe=50a9cf65b3) | Nov 05, 2023 |
| Lenovo        | ThinkPad T580 20LAS62M07    | Notebook    | [56d9dc4a36](https://linux-hardware.org/?probe=56d9dc4a36) | Nov 05, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [038e8719ec](https://linux-hardware.org/?probe=038e8719ec) | Nov 05, 2023 |
| Unknown       | Unknown                     | Notebook    | [2c2d291f54](https://linux-hardware.org/?probe=2c2d291f54) | Nov 05, 2023 |
| ASUSTek       | P5K PRO                     | Desktop     | [7dd5e78310](https://linux-hardware.org/?probe=7dd5e78310) | Nov 05, 2023 |
| HP            | Compaq 6710b                | Notebook    | [7a0b2fd29b](https://linux-hardware.org/?probe=7a0b2fd29b) | Nov 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [2e74968a1e](https://linux-hardware.org/?probe=2e74968a1e) | Nov 05, 2023 |
| MSI           | Cyborg 15 A12VF             | Notebook    | [be39067306](https://linux-hardware.org/?probe=be39067306) | Nov 05, 2023 |
| Dell          | 048DY8 A01                  | Desktop     | [2ef39546ef](https://linux-hardware.org/?probe=2ef39546ef) | Nov 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [edb0760b00](https://linux-hardware.org/?probe=edb0760b00) | Nov 05, 2023 |
| Dell          | Latitude E6400              | Notebook    | [c5f0762ae5](https://linux-hardware.org/?probe=c5f0762ae5) | Nov 05, 2023 |
| Shuttle       | FH87                        | Desktop     | [1488ef29c3](https://linux-hardware.org/?probe=1488ef29c3) | Nov 05, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [451abee058](https://linux-hardware.org/?probe=451abee058) | Nov 05, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [72b02cceec](https://linux-hardware.org/?probe=72b02cceec) | Nov 05, 2023 |
| HP            | HPPavilionLaptop15-eh0xx... | Notebook    | [436064bfba](https://linux-hardware.org/?probe=436064bfba) | Nov 05, 2023 |
| HP            | 650                         | Notebook    | [5b72d0e471](https://linux-hardware.org/?probe=5b72d0e471) | Nov 05, 2023 |
| HP            | 8959                        | All in one  | [68870f0170](https://linux-hardware.org/?probe=68870f0170) | Nov 05, 2023 |
| MSI           | Bravo 15 B5DD               | Notebook    | [8a35411be4](https://linux-hardware.org/?probe=8a35411be4) | Nov 05, 2023 |
| ASUSTek       | ROG Strix G713PI_G713PI     | Notebook    | [8b3f431a00](https://linux-hardware.org/?probe=8b3f431a00) | Nov 05, 2023 |
| MSI           | NIGHTBLADE Z97              | Desktop     | [3da62b47b3](https://linux-hardware.org/?probe=3da62b47b3) | Nov 05, 2023 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [53f5c381aa](https://linux-hardware.org/?probe=53f5c381aa) | Nov 05, 2023 |
| Gigabyte      | B450M GAMING-CF             | Desktop     | [247cc16161](https://linux-hardware.org/?probe=247cc16161) | Nov 05, 2023 |
| HP            | ProBook 4740s               | Notebook    | [2efc1092dd](https://linux-hardware.org/?probe=2efc1092dd) | Nov 05, 2023 |
| HP            | ProBook 4740s               | Notebook    | [0351f35099](https://linux-hardware.org/?probe=0351f35099) | Nov 05, 2023 |
| HP            | ProBook 6545b               | Notebook    | [a81427fffa](https://linux-hardware.org/?probe=a81427fffa) | Nov 05, 2023 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [01e74da42d](https://linux-hardware.org/?probe=01e74da42d) | Nov 05, 2023 |
| ASUSTek       | P5G41T-M LX2/GB             | Desktop     | [5196f9303d](https://linux-hardware.org/?probe=5196f9303d) | Nov 05, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [9213826ac6](https://linux-hardware.org/?probe=9213826ac6) | Nov 05, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [1801a9c841](https://linux-hardware.org/?probe=1801a9c841) | Nov 05, 2023 |
| HP            | 8184 X4                     | Desktop     | [fb7f295b44](https://linux-hardware.org/?probe=fb7f295b44) | Nov 05, 2023 |
| HP            | Laptop 17t-by000            | Notebook    | [b23b606118](https://linux-hardware.org/?probe=b23b606118) | Nov 05, 2023 |
| HP            | 802F                        | Desktop     | [8fe557cc85](https://linux-hardware.org/?probe=8fe557cc85) | Nov 05, 2023 |
| HP            | Pavilion dm4                | Notebook    | [ed4309477f](https://linux-hardware.org/?probe=ed4309477f) | Nov 05, 2023 |
| Lenovo        | Legion 5 17ITH6H 82JM       | Notebook    | [7bde99341f](https://linux-hardware.org/?probe=7bde99341f) | Nov 05, 2023 |
| Gigabyte      | MZBSWAP-K4                  | Desktop     | [ef6c15830d](https://linux-hardware.org/?probe=ef6c15830d) | Nov 05, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [2ac9878b30](https://linux-hardware.org/?probe=2ac9878b30) | Nov 05, 2023 |
| Lenovo        | ThinkPad T490 20N2000LSP    | Notebook    | [55e3cdf0cc](https://linux-hardware.org/?probe=55e3cdf0cc) | Nov 05, 2023 |
| Lenovo        | SDK0E50510 WIN              | Desktop     | [1e59a67f24](https://linux-hardware.org/?probe=1e59a67f24) | Nov 05, 2023 |
| ASUSTek       | G53SX                       | Notebook    | [7834b537a1](https://linux-hardware.org/?probe=7834b537a1) | Nov 05, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [a1500e2e9c](https://linux-hardware.org/?probe=a1500e2e9c) | Nov 05, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [7152c7ed2c](https://linux-hardware.org/?probe=7152c7ed2c) | Nov 05, 2023 |
| HP            | 530                         | Notebook    | [710ba89827](https://linux-hardware.org/?probe=710ba89827) | Nov 05, 2023 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [be33944c69](https://linux-hardware.org/?probe=be33944c69) | Nov 05, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [615e914ddd](https://linux-hardware.org/?probe=615e914ddd) | Nov 05, 2023 |
| Acer          | Aspire ES1-311              | Notebook    | [d06185f74c](https://linux-hardware.org/?probe=d06185f74c) | Nov 05, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [7ba5de3dfd](https://linux-hardware.org/?probe=7ba5de3dfd) | Nov 05, 2023 |
| Unknown       | Unknown                     | Soc         | [d9a46b8149](https://linux-hardware.org/?probe=d9a46b8149) | Nov 05, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [7b281cb925](https://linux-hardware.org/?probe=7b281cb925) | Nov 05, 2023 |
| ASUSTek       | G75VW                       | Notebook    | [94bc809d57](https://linux-hardware.org/?probe=94bc809d57) | Nov 05, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [22b09dfb91](https://linux-hardware.org/?probe=22b09dfb91) | Nov 05, 2023 |
| Dell          | Inspiron 7559               | Notebook    | [da97d12548](https://linux-hardware.org/?probe=da97d12548) | Nov 05, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [05a8c22a35](https://linux-hardware.org/?probe=05a8c22a35) | Nov 05, 2023 |
| Medion        | E7220                       | Notebook    | [a8643a8082](https://linux-hardware.org/?probe=a8643a8082) | Nov 05, 2023 |
| HP            | Pavilion dv6                | Notebook    | [60ff7a74af](https://linux-hardware.org/?probe=60ff7a74af) | Nov 05, 2023 |
| Google        | Phaser360                   | Notebook    | [dbd0db9b7e](https://linux-hardware.org/?probe=dbd0db9b7e) | Nov 05, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [b1c2db4297](https://linux-hardware.org/?probe=b1c2db4297) | Nov 05, 2023 |
| Acer          | Aspire 5349                 | Notebook    | [b1ca6f597c](https://linux-hardware.org/?probe=b1ca6f597c) | Nov 05, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [034b113ac8](https://linux-hardware.org/?probe=034b113ac8) | Nov 05, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [3d09b709c4](https://linux-hardware.org/?probe=3d09b709c4) | Nov 05, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [2710dfedf4](https://linux-hardware.org/?probe=2710dfedf4) | Nov 05, 2023 |
| Dell          | 062TCH A00                  | Desktop     | [b82fbd03d5](https://linux-hardware.org/?probe=b82fbd03d5) | Nov 05, 2023 |
| AMI           | Unknown                     | Notebook    | [2512404fd7](https://linux-hardware.org/?probe=2512404fd7) | Nov 05, 2023 |
| ASRock        | A320M Pro4-F                | Desktop     | [7dab52cd8c](https://linux-hardware.org/?probe=7dab52cd8c) | Nov 05, 2023 |
| Dell          | 0V8WGR A00                  | Desktop     | [9b13411bc8](https://linux-hardware.org/?probe=9b13411bc8) | Nov 05, 2023 |
| Medion        | E7220                       | Notebook    | [f093abab73](https://linux-hardware.org/?probe=f093abab73) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [f1d00fbb93](https://linux-hardware.org/?probe=f1d00fbb93) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [e1d50d8743](https://linux-hardware.org/?probe=e1d50d8743) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [92ed6d25c3](https://linux-hardware.org/?probe=92ed6d25c3) | Nov 05, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [f0b35f0acb](https://linux-hardware.org/?probe=f0b35f0acb) | Nov 05, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [f782cf5541](https://linux-hardware.org/?probe=f782cf5541) | Nov 05, 2023 |
| MSI           | PRO B760M-P DDR4            | Desktop     | [5b5425c6d8](https://linux-hardware.org/?probe=5b5425c6d8) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [ae9fcece31](https://linux-hardware.org/?probe=ae9fcece31) | Nov 05, 2023 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [e079b95148](https://linux-hardware.org/?probe=e079b95148) | Nov 05, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [7060a82ed0](https://linux-hardware.org/?probe=7060a82ed0) | Nov 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ea37beb412](https://linux-hardware.org/?probe=ea37beb412) | Nov 05, 2023 |
| Gigabyte      | B650M DS3H                  | Desktop     | [a424739d4f](https://linux-hardware.org/?probe=a424739d4f) | Nov 05, 2023 |
| HP            | Notebook                    | Notebook    | [8eea1901f7](https://linux-hardware.org/?probe=8eea1901f7) | Nov 05, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [287ceab4df](https://linux-hardware.org/?probe=287ceab4df) | Nov 05, 2023 |
| HP            | Pavilion dv5                | Notebook    | [6a122b29a9](https://linux-hardware.org/?probe=6a122b29a9) | Nov 05, 2023 |
| ASUSTek       | K55VJ                       | Notebook    | [47851a05e9](https://linux-hardware.org/?probe=47851a05e9) | Nov 05, 2023 |
| Alienware     | 0N43JM A01                  | Desktop     | [7bd0e03c1b](https://linux-hardware.org/?probe=7bd0e03c1b) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | Notebook    | [fd9594de89](https://linux-hardware.org/?probe=fd9594de89) | Nov 05, 2023 |
| Google        | Pyro                        | Notebook    | [2fd8f11a53](https://linux-hardware.org/?probe=2fd8f11a53) | Nov 05, 2023 |
| Gigabyte      | X570 UD                     | Desktop     | [1c9b1632b8](https://linux-hardware.org/?probe=1c9b1632b8) | Nov 05, 2023 |
| Unknown       | Unknown                     | Notebook    | [f90d872043](https://linux-hardware.org/?probe=f90d872043) | Nov 05, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [a42da62572](https://linux-hardware.org/?probe=a42da62572) | Nov 05, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [c17ad7033c](https://linux-hardware.org/?probe=c17ad7033c) | Nov 05, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | Desktop     | [24e4446a67](https://linux-hardware.org/?probe=24e4446a67) | Nov 05, 2023 |
| ASUSTek       | X756UVK                     | Notebook    | [3ba2cc1e0c](https://linux-hardware.org/?probe=3ba2cc1e0c) | Nov 05, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [23e52fc4f5](https://linux-hardware.org/?probe=23e52fc4f5) | Nov 05, 2023 |
| Dell          | 03X6X0 A06                  | Server      | [90b61e75ba](https://linux-hardware.org/?probe=90b61e75ba) | Nov 05, 2023 |
| Lenovo        | ThinkPad X250 20CM001UUK    | Notebook    | [b0fd9fa3c0](https://linux-hardware.org/?probe=b0fd9fa3c0) | Nov 05, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [4b29646104](https://linux-hardware.org/?probe=4b29646104) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [a3a6205085](https://linux-hardware.org/?probe=a3a6205085) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [1d56b84bdd](https://linux-hardware.org/?probe=1d56b84bdd) | Nov 05, 2023 |
| Lenovo        | ThinkPad E580 20KS003QUS    | Notebook    | [6bccd355f7](https://linux-hardware.org/?probe=6bccd355f7) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [263a417420](https://linux-hardware.org/?probe=263a417420) | Nov 05, 2023 |
| Medion        | E6417 MD99252               | Notebook    | [8660ae1c16](https://linux-hardware.org/?probe=8660ae1c16) | Nov 05, 2023 |
| Raspberry ... | Raspberry Pi Zero W Rev ... | Soc         | [b5b47ea33a](https://linux-hardware.org/?probe=b5b47ea33a) | Nov 05, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [f4cbcd5ba1](https://linux-hardware.org/?probe=f4cbcd5ba1) | Nov 05, 2023 |
| Dell          | 0VNP2H A00                  | Desktop     | [98439489ad](https://linux-hardware.org/?probe=98439489ad) | Nov 05, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [63e30986f6](https://linux-hardware.org/?probe=63e30986f6) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [60f590c96c](https://linux-hardware.org/?probe=60f590c96c) | Nov 05, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [34a347877f](https://linux-hardware.org/?probe=34a347877f) | Nov 05, 2023 |
| Samsung       | 305E4A/305E5A/305E7A        | Notebook    | [257e40f6bd](https://linux-hardware.org/?probe=257e40f6bd) | Nov 05, 2023 |
| ASUSTek       | G11CD                       | Desktop     | [8fcbd49e37](https://linux-hardware.org/?probe=8fcbd49e37) | Nov 05, 2023 |
| HP            | Mini 210-3000               | Notebook    | [8b55a876a9](https://linux-hardware.org/?probe=8b55a876a9) | Nov 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [555d9146a4](https://linux-hardware.org/?probe=555d9146a4) | Nov 05, 2023 |
| HP            | 1589                        | Desktop     | [61922d4b43](https://linux-hardware.org/?probe=61922d4b43) | Nov 05, 2023 |
| Acer          | Aspire E1-571G              | Notebook    | [fac63c4d5c](https://linux-hardware.org/?probe=fac63c4d5c) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | Notebook    | [a5a8cf5c09](https://linux-hardware.org/?probe=a5a8cf5c09) | Nov 05, 2023 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [2cc662a279](https://linux-hardware.org/?probe=2cc662a279) | Nov 05, 2023 |
| Google        | Nami                        | Notebook    | [19c94b9484](https://linux-hardware.org/?probe=19c94b9484) | Nov 05, 2023 |
| HP            | ProBook 4330s               | Notebook    | [b22a07c92b](https://linux-hardware.org/?probe=b22a07c92b) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b2cfb39c04](https://linux-hardware.org/?probe=b2cfb39c04) | Nov 05, 2023 |
| Dell          | 09T7VV A05                  | Server      | [ed330c4205](https://linux-hardware.org/?probe=ed330c4205) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | Notebook    | [74099b3a6e](https://linux-hardware.org/?probe=74099b3a6e) | Nov 05, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [2cbd472a6e](https://linux-hardware.org/?probe=2cbd472a6e) | Nov 05, 2023 |
| MSI           | Alpha 17 C7VG               | Notebook    | [bdad71bf99](https://linux-hardware.org/?probe=bdad71bf99) | Nov 05, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [f154c5979f](https://linux-hardware.org/?probe=f154c5979f) | Nov 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [1db5fee13c](https://linux-hardware.org/?probe=1db5fee13c) | Nov 05, 2023 |
| Dell          | Latitude 5520               | Notebook    | [46be4f4eec](https://linux-hardware.org/?probe=46be4f4eec) | Nov 05, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [a2fbd58a8c](https://linux-hardware.org/?probe=a2fbd58a8c) | Nov 05, 2023 |
| HP            | 1494                        | Desktop     | [93e0e0302f](https://linux-hardware.org/?probe=93e0e0302f) | Nov 05, 2023 |
| Trigkey       | S5 V2.0                     | Mini pc     | [dc066ab76b](https://linux-hardware.org/?probe=dc066ab76b) | Nov 05, 2023 |
| Apple         | Mac-F2218EA9                | All in one  | [5c50c142b3](https://linux-hardware.org/?probe=5c50c142b3) | Nov 05, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [4ce8997d5a](https://linux-hardware.org/?probe=4ce8997d5a) | Nov 05, 2023 |
| Toshiba       | Satellite L515              | Notebook    | [70a66852db](https://linux-hardware.org/?probe=70a66852db) | Nov 05, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [c520e5a3b2](https://linux-hardware.org/?probe=c520e5a3b2) | Nov 05, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d74f909776](https://linux-hardware.org/?probe=d74f909776) | Nov 05, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [d6cd277a79](https://linux-hardware.org/?probe=d6cd277a79) | Nov 05, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [50306c96e2](https://linux-hardware.org/?probe=50306c96e2) | Nov 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [4ece1b1597](https://linux-hardware.org/?probe=4ece1b1597) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [486d28dfeb](https://linux-hardware.org/?probe=486d28dfeb) | Nov 05, 2023 |
| Toshiba       | Satellite L845              | Notebook    | [4dc7e8931e](https://linux-hardware.org/?probe=4dc7e8931e) | Nov 05, 2023 |
| Google        | Taeko                       | Notebook    | [d148b001d9](https://linux-hardware.org/?probe=d148b001d9) | Nov 05, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [21b415bccc](https://linux-hardware.org/?probe=21b415bccc) | Nov 05, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [95f3002643](https://linux-hardware.org/?probe=95f3002643) | Nov 05, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [3f295082ce](https://linux-hardware.org/?probe=3f295082ce) | Nov 05, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [9d8a12d929](https://linux-hardware.org/?probe=9d8a12d929) | Nov 05, 2023 |
| GEEKOM        | A5                          | Desktop     | [d3dd0e1aca](https://linux-hardware.org/?probe=d3dd0e1aca) | Nov 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [28e2c2aa38](https://linux-hardware.org/?probe=28e2c2aa38) | Nov 05, 2023 |
| Fujitsu       | LIFEBOOK E736               | Notebook    | [a2b93486a9](https://linux-hardware.org/?probe=a2b93486a9) | Nov 05, 2023 |
| MSI           | B560M PRO-E                 | Desktop     | [1488a8a70f](https://linux-hardware.org/?probe=1488a8a70f) | Nov 05, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [c3b2667bbf](https://linux-hardware.org/?probe=c3b2667bbf) | Nov 05, 2023 |
| HP            | 1998                        | Desktop     | [d454314b77](https://linux-hardware.org/?probe=d454314b77) | Nov 05, 2023 |
| ASRockRack    | EPC602D8A                   | Desktop     | [c1b6c06dc5](https://linux-hardware.org/?probe=c1b6c06dc5) | Nov 05, 2023 |
| HP            | 829A                        | Mini pc     | [34b672080f](https://linux-hardware.org/?probe=34b672080f) | Nov 05, 2023 |
| Notebook      | NL5xRU                      | Notebook    | [6dd04cca75](https://linux-hardware.org/?probe=6dd04cca75) | Nov 05, 2023 |
| HP            | 829A                        | Mini pc     | [03af1f506e](https://linux-hardware.org/?probe=03af1f506e) | Nov 05, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [4998a82a6b](https://linux-hardware.org/?probe=4998a82a6b) | Nov 05, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [bdd24f60d2](https://linux-hardware.org/?probe=bdd24f60d2) | Nov 05, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [f5cd797cc8](https://linux-hardware.org/?probe=f5cd797cc8) | Nov 05, 2023 |
| ASUSTek       | UX370UAR                    | Convertible | [754b927267](https://linux-hardware.org/?probe=754b927267) | Nov 05, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [539d8551fc](https://linux-hardware.org/?probe=539d8551fc) | Nov 05, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5541e01522](https://linux-hardware.org/?probe=5541e01522) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [85733c0ec0](https://linux-hardware.org/?probe=85733c0ec0) | Nov 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [f45893cbf7](https://linux-hardware.org/?probe=f45893cbf7) | Nov 05, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [17acb71f9d](https://linux-hardware.org/?probe=17acb71f9d) | Nov 05, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [f070e73453](https://linux-hardware.org/?probe=f070e73453) | Nov 05, 2023 |
| Toshiba       | QOSMIO X505                 | Notebook    | [e5e5eb9254](https://linux-hardware.org/?probe=e5e5eb9254) | Nov 05, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [532db79d07](https://linux-hardware.org/?probe=532db79d07) | Nov 05, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [c235d90592](https://linux-hardware.org/?probe=c235d90592) | Nov 05, 2023 |
| ASUSTek       | PRIME A520M-K               | Desktop     | [907a7f6dd8](https://linux-hardware.org/?probe=907a7f6dd8) | Nov 05, 2023 |
| Digibras      | NH4CU53                     | Notebook    | [2c274cbad8](https://linux-hardware.org/?probe=2c274cbad8) | Nov 05, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [8a4147b40a](https://linux-hardware.org/?probe=8a4147b40a) | Nov 05, 2023 |
| Gigabyte      | M5NM1AI-GB                  | Desktop     | [99e2275a93](https://linux-hardware.org/?probe=99e2275a93) | Nov 05, 2023 |
| ASUSTek       | ROG Maximus Z790 HERO       | Desktop     | [a9ad2b542a](https://linux-hardware.org/?probe=a9ad2b542a) | Nov 05, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [7a8597dd50](https://linux-hardware.org/?probe=7a8597dd50) | Nov 05, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [482f1a0fe7](https://linux-hardware.org/?probe=482f1a0fe7) | Nov 05, 2023 |
| MSI           | H110I PRO                   | Desktop     | [c335c71c4b](https://linux-hardware.org/?probe=c335c71c4b) | Nov 05, 2023 |
| Dell          | 0T7D40 A00                  | Desktop     | [2053de6443](https://linux-hardware.org/?probe=2053de6443) | Nov 05, 2023 |
| Dell          | Inspiron 14 5401            | Notebook    | [124c666940](https://linux-hardware.org/?probe=124c666940) | Nov 05, 2023 |
| Lenovo        | SKYBAY NOK                  | Desktop     | [534fcded19](https://linux-hardware.org/?probe=534fcded19) | Nov 05, 2023 |
| Google        | Akemi                       | Notebook    | [350f53d84a](https://linux-hardware.org/?probe=350f53d84a) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [dbd2e07499](https://linux-hardware.org/?probe=dbd2e07499) | Nov 05, 2023 |
| Dell          | Latitude E7440              | Notebook    | [5a151e929f](https://linux-hardware.org/?probe=5a151e929f) | Nov 05, 2023 |
| HP            | 8054                        | Desktop     | [cbf4895785](https://linux-hardware.org/?probe=cbf4895785) | Nov 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [e98e6bb977](https://linux-hardware.org/?probe=e98e6bb977) | Nov 05, 2023 |
| Dell          | Inspiron 14 5401            | Notebook    | [9eeeda059e](https://linux-hardware.org/?probe=9eeeda059e) | Nov 05, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [fc01ceb47b](https://linux-hardware.org/?probe=fc01ceb47b) | Nov 05, 2023 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [2b9b1f909c](https://linux-hardware.org/?probe=2b9b1f909c) | Nov 05, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [279f1b8b4f](https://linux-hardware.org/?probe=279f1b8b4f) | Nov 05, 2023 |
| Dell          | Inspiron 7501               | Notebook    | [0926c7cdad](https://linux-hardware.org/?probe=0926c7cdad) | Nov 05, 2023 |
| ASRock        | P67 Pro3 SE                 | Desktop     | [10b1460f7a](https://linux-hardware.org/?probe=10b1460f7a) | Nov 05, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [7d9395e4a7](https://linux-hardware.org/?probe=7d9395e4a7) | Nov 05, 2023 |
| Tactus        | GeoFlex 140                 | Convertible | [a386eceffe](https://linux-hardware.org/?probe=a386eceffe) | Nov 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ee2a20b30a](https://linux-hardware.org/?probe=ee2a20b30a) | Nov 05, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fefb7e12d2](https://linux-hardware.org/?probe=fefb7e12d2) | Nov 05, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [d20af6bf95](https://linux-hardware.org/?probe=d20af6bf95) | Nov 05, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [f8860a91a3](https://linux-hardware.org/?probe=f8860a91a3) | Nov 05, 2023 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [45e65903ff](https://linux-hardware.org/?probe=45e65903ff) | Nov 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS0QG1Z    | Notebook    | [ae8881b2b2](https://linux-hardware.org/?probe=ae8881b2b2) | Nov 04, 2023 |
| Tactus        | GeoFlex 140                 | Convertible | [1e6407d9d5](https://linux-hardware.org/?probe=1e6407d9d5) | Nov 04, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [52a36f5268](https://linux-hardware.org/?probe=52a36f5268) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [6f11758faa](https://linux-hardware.org/?probe=6f11758faa) | Nov 04, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [1bb894cf19](https://linux-hardware.org/?probe=1bb894cf19) | Nov 04, 2023 |
| Gigabyte      | H410M S2H V2                | Desktop     | [8bbce8a378](https://linux-hardware.org/?probe=8bbce8a378) | Nov 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [5832913981](https://linux-hardware.org/?probe=5832913981) | Nov 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS0QG1Z    | Notebook    | [a3d91609e9](https://linux-hardware.org/?probe=a3d91609e9) | Nov 04, 2023 |
| System76      | Lemur Pro                   | Notebook    | [dacc229f22](https://linux-hardware.org/?probe=dacc229f22) | Nov 04, 2023 |
| Lenovo        | IdeaPadFlex 5 16ABR8 82X... | Convertible | [9f19a2ba3a](https://linux-hardware.org/?probe=9f19a2ba3a) | Nov 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [4f6d5932fa](https://linux-hardware.org/?probe=4f6d5932fa) | Nov 04, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [a513bb8188](https://linux-hardware.org/?probe=a513bb8188) | Nov 04, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [4e3cd50b3f](https://linux-hardware.org/?probe=4e3cd50b3f) | Nov 04, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [62798aa8cf](https://linux-hardware.org/?probe=62798aa8cf) | Nov 04, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [b77c593ace](https://linux-hardware.org/?probe=b77c593ace) | Nov 04, 2023 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [1c80cbda1c](https://linux-hardware.org/?probe=1c80cbda1c) | Nov 04, 2023 |
| Lenovo        | ThinkPad T470 20HD0000BM    | Notebook    | [3e379ff6e8](https://linux-hardware.org/?probe=3e379ff6e8) | Nov 04, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [29fc753f1e](https://linux-hardware.org/?probe=29fc753f1e) | Nov 04, 2023 |
| Acer          | Aspire A517-51G             | Notebook    | [11f85eb258](https://linux-hardware.org/?probe=11f85eb258) | Nov 04, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [a9f0b015d5](https://linux-hardware.org/?probe=a9f0b015d5) | Nov 04, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [ddf88ff37c](https://linux-hardware.org/?probe=ddf88ff37c) | Nov 04, 2023 |
| MSI           | B560M PRO-VDH               | Desktop     | [04e96e2742](https://linux-hardware.org/?probe=04e96e2742) | Nov 04, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [08d79042a7](https://linux-hardware.org/?probe=08d79042a7) | Nov 04, 2023 |
| Lenovo        | IdeaPadFlex 5 16ABR8 82X... | Convertible | [d3a8398c99](https://linux-hardware.org/?probe=d3a8398c99) | Nov 04, 2023 |
| Medion        | H110H4-EM                   | Desktop     | [9fe03aa296](https://linux-hardware.org/?probe=9fe03aa296) | Nov 04, 2023 |
| Supermicro    | X10SRA                      | Server      | [87045c1939](https://linux-hardware.org/?probe=87045c1939) | Nov 04, 2023 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [f8a30d78d3](https://linux-hardware.org/?probe=f8a30d78d3) | Nov 04, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [8efb96e5d7](https://linux-hardware.org/?probe=8efb96e5d7) | Nov 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [dd81ed04ea](https://linux-hardware.org/?probe=dd81ed04ea) | Nov 04, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [cfdf343144](https://linux-hardware.org/?probe=cfdf343144) | Nov 04, 2023 |
| Acer          | Aspire 5100                 | Notebook    | [62b63704e9](https://linux-hardware.org/?probe=62b63704e9) | Nov 04, 2023 |
| Lenovo        | S145-15IWL 81MV             | Notebook    | [d38fdaf0eb](https://linux-hardware.org/?probe=d38fdaf0eb) | Nov 04, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [237bd5cfb2](https://linux-hardware.org/?probe=237bd5cfb2) | Nov 04, 2023 |
| Lenovo        | ThinkPad W550s 20E2000PM... | Notebook    | [1294d54c1a](https://linux-hardware.org/?probe=1294d54c1a) | Nov 04, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [8841ab599e](https://linux-hardware.org/?probe=8841ab599e) | Nov 04, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [d423a5c34a](https://linux-hardware.org/?probe=d423a5c34a) | Nov 04, 2023 |
| Pegatron      | IPMIP-H55-GEN               | Desktop     | [f87bf6e0dd](https://linux-hardware.org/?probe=f87bf6e0dd) | Nov 04, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [e6459bb42f](https://linux-hardware.org/?probe=e6459bb42f) | Nov 04, 2023 |
| Dell          | XPS 13 9315 2-in-1          | Tablet      | [79016d8b5e](https://linux-hardware.org/?probe=79016d8b5e) | Nov 04, 2023 |
| Acer          | Aspire 5100                 | Notebook    | [c4d628cb50](https://linux-hardware.org/?probe=c4d628cb50) | Nov 04, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [459eb3cd2a](https://linux-hardware.org/?probe=459eb3cd2a) | Nov 04, 2023 |
| Toshiba       | STI 001359                  | Desktop     | [ebf464dbb3](https://linux-hardware.org/?probe=ebf464dbb3) | Nov 04, 2023 |
| Acer          | Aspire M1920                | Desktop     | [f6ffcb0c41](https://linux-hardware.org/?probe=f6ffcb0c41) | Nov 04, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [399dda92eb](https://linux-hardware.org/?probe=399dda92eb) | Nov 04, 2023 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [dade20f823](https://linux-hardware.org/?probe=dade20f823) | Nov 04, 2023 |
| Apple         | Mac-F2268DC8                | All in one  | [1173519349](https://linux-hardware.org/?probe=1173519349) | Nov 04, 2023 |
| Intel         | DG33BU AAD79951-407         | Desktop     | [734dafca4e](https://linux-hardware.org/?probe=734dafca4e) | Nov 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [f1e059fa93](https://linux-hardware.org/?probe=f1e059fa93) | Nov 04, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [d11250217c](https://linux-hardware.org/?probe=d11250217c) | Nov 04, 2023 |
| HP            | 650                         | Notebook    | [c472e54502](https://linux-hardware.org/?probe=c472e54502) | Nov 04, 2023 |
| Apple         | Mac-B809C3757DA9BB8D iMa... | All in one  | [64b26f1390](https://linux-hardware.org/?probe=64b26f1390) | Nov 04, 2023 |
| HP            | ProBook 430 G1              | Notebook    | [14dc35a1b9](https://linux-hardware.org/?probe=14dc35a1b9) | Nov 04, 2023 |
| Lenovo        | ThinkPad E15 20RD0011UK     | Notebook    | [dc13d6012b](https://linux-hardware.org/?probe=dc13d6012b) | Nov 04, 2023 |
| Lenovo        | ThinkPad T460 20FMS3YT01    | Notebook    | [89b8df73c1](https://linux-hardware.org/?probe=89b8df73c1) | Nov 04, 2023 |
| MSI           | Modern 15 B7M               | Notebook    | [b4a588e60e](https://linux-hardware.org/?probe=b4a588e60e) | Nov 04, 2023 |
| System76      | Lemur Pro                   | Notebook    | [80b1ef75d6](https://linux-hardware.org/?probe=80b1ef75d6) | Nov 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [20ffbbc165](https://linux-hardware.org/?probe=20ffbbc165) | Nov 04, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6a44cc2c3c](https://linux-hardware.org/?probe=6a44cc2c3c) | Nov 04, 2023 |
| ASUSTek       | ROG Strix G733QR_G733QR     | Notebook    | [5b7dc65a39](https://linux-hardware.org/?probe=5b7dc65a39) | Nov 04, 2023 |
| Acer          | TravelMate B118-M           | Notebook    | [051346666e](https://linux-hardware.org/?probe=051346666e) | Nov 04, 2023 |
| System76      | Oryx Pro                    | Notebook    | [ea89273272](https://linux-hardware.org/?probe=ea89273272) | Nov 04, 2023 |
| ASUSTek       | K53U                        | Notebook    | [eb44961984](https://linux-hardware.org/?probe=eb44961984) | Nov 04, 2023 |
| Dell          | Latitude E6430              | Notebook    | [6a724d5aa8](https://linux-hardware.org/?probe=6a724d5aa8) | Nov 04, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [6ea9e5b141](https://linux-hardware.org/?probe=6ea9e5b141) | Nov 04, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [2084300c18](https://linux-hardware.org/?probe=2084300c18) | Nov 04, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [013a7815c3](https://linux-hardware.org/?probe=013a7815c3) | Nov 04, 2023 |
| MSI           | H110M PRO-D                 | Desktop     | [9a7337554c](https://linux-hardware.org/?probe=9a7337554c) | Nov 04, 2023 |
| HP            | EliteBook 850 G2            | Notebook    | [36646aca12](https://linux-hardware.org/?probe=36646aca12) | Nov 04, 2023 |
| HP            | 655                         | Notebook    | [8cf9aa61c7](https://linux-hardware.org/?probe=8cf9aa61c7) | Nov 04, 2023 |
| Medion        | E6214                       | Notebook    | [776be82bf6](https://linux-hardware.org/?probe=776be82bf6) | Nov 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [e95c10c89d](https://linux-hardware.org/?probe=e95c10c89d) | Nov 04, 2023 |
| HP            | 21D0                        | Desktop     | [160964fbab](https://linux-hardware.org/?probe=160964fbab) | Nov 04, 2023 |
| Intel         | NUC8BEB J72692-303          | Mini pc     | [77f3748e01](https://linux-hardware.org/?probe=77f3748e01) | Nov 04, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c1523fb6a1](https://linux-hardware.org/?probe=c1523fb6a1) | Nov 04, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [3ba4126936](https://linux-hardware.org/?probe=3ba4126936) | Nov 04, 2023 |
| HP            | ProBook 430 G8 Notebook ... | Notebook    | [5d8cae0407](https://linux-hardware.org/?probe=5d8cae0407) | Nov 04, 2023 |
| HP            | 8767 A                      | Desktop     | [307b4eb17b](https://linux-hardware.org/?probe=307b4eb17b) | Nov 04, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [30a0e0602f](https://linux-hardware.org/?probe=30a0e0602f) | Nov 04, 2023 |
| Gigabyte      | GA-870A-USB3L               | Desktop     | [d2412dfd7c](https://linux-hardware.org/?probe=d2412dfd7c) | Nov 04, 2023 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [2b5c984cd8](https://linux-hardware.org/?probe=2b5c984cd8) | Nov 04, 2023 |
| HP            | 8265                        | Desktop     | [f6b38e869b](https://linux-hardware.org/?probe=f6b38e869b) | Nov 04, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [b390f8cd05](https://linux-hardware.org/?probe=b390f8cd05) | Nov 04, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [c74051abb7](https://linux-hardware.org/?probe=c74051abb7) | Nov 04, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [e6f4957064](https://linux-hardware.org/?probe=e6f4957064) | Nov 04, 2023 |
| ASUSTek       | PRIME Z370-P II             | Desktop     | [701314a2ff](https://linux-hardware.org/?probe=701314a2ff) | Nov 04, 2023 |
| Acer          | TravelMate P215-54          | Notebook    | [5688b7940d](https://linux-hardware.org/?probe=5688b7940d) | Nov 04, 2023 |
| ASUSTek       | H97M-PLUS                   | Desktop     | [69cb1e7068](https://linux-hardware.org/?probe=69cb1e7068) | Nov 04, 2023 |
| MSI           | B560M PRO                   | Desktop     | [903907b7c0](https://linux-hardware.org/?probe=903907b7c0) | Nov 04, 2023 |
| ASRock        | B250M-HDV                   | Desktop     | [c8521456ad](https://linux-hardware.org/?probe=c8521456ad) | Nov 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [38df9f5382](https://linux-hardware.org/?probe=38df9f5382) | Nov 04, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [4c97723997](https://linux-hardware.org/?probe=4c97723997) | Nov 04, 2023 |
| ASRock        | H470M-STX                   | Desktop     | [5a50d371b8](https://linux-hardware.org/?probe=5a50d371b8) | Nov 04, 2023 |
| Notebook      | N141CU                      | Notebook    | [8f817eeabf](https://linux-hardware.org/?probe=8f817eeabf) | Nov 04, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [6fcd2a768b](https://linux-hardware.org/?probe=6fcd2a768b) | Nov 04, 2023 |
| HP            | Notebook                    | Notebook    | [f8cf975d3c](https://linux-hardware.org/?probe=f8cf975d3c) | Nov 04, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [f8507f333d](https://linux-hardware.org/?probe=f8507f333d) | Nov 04, 2023 |
| Lenovo        | ThinkPad T550 20CJS07P01    | Notebook    | [52157a4ee8](https://linux-hardware.org/?probe=52157a4ee8) | Nov 04, 2023 |
| MSI           | Bravo 15 C7VE               | Notebook    | [5db0e7314a](https://linux-hardware.org/?probe=5db0e7314a) | Nov 04, 2023 |
| Acer          | AO532h                      | Notebook    | [0b3d66b04a](https://linux-hardware.org/?probe=0b3d66b04a) | Nov 04, 2023 |
| ASUSTek       | X550LC                      | Notebook    | [bd59b07dbf](https://linux-hardware.org/?probe=bd59b07dbf) | Nov 04, 2023 |
| Samsung       | 750XEE                      | Notebook    | [fd74ae52f8](https://linux-hardware.org/?probe=fd74ae52f8) | Nov 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [b0487db7bf](https://linux-hardware.org/?probe=b0487db7bf) | Nov 04, 2023 |
| Acer          | TravelMate P215-54          | Notebook    | [f051dc617c](https://linux-hardware.org/?probe=f051dc617c) | Nov 04, 2023 |
| ASUSTek       | X550LC                      | Notebook    | [b7fa2bbb0b](https://linux-hardware.org/?probe=b7fa2bbb0b) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX X370-F GAMING     | Desktop     | [03f8b26adb](https://linux-hardware.org/?probe=03f8b26adb) | Nov 04, 2023 |
| Gigabyte      | B550M S2H                   | Desktop     | [7fb9150b16](https://linux-hardware.org/?probe=7fb9150b16) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [49c91b6782](https://linux-hardware.org/?probe=49c91b6782) | Nov 04, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [1d8dad6600](https://linux-hardware.org/?probe=1d8dad6600) | Nov 04, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [157f4d1006](https://linux-hardware.org/?probe=157f4d1006) | Nov 04, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1NF0... | Notebook    | [8528f9946b](https://linux-hardware.org/?probe=8528f9946b) | Nov 04, 2023 |
| HP            | Presario C500 (GF849EA#A... | Notebook    | [a4965dff09](https://linux-hardware.org/?probe=a4965dff09) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [80d949b057](https://linux-hardware.org/?probe=80d949b057) | Nov 04, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [812ceefef6](https://linux-hardware.org/?probe=812ceefef6) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [5e5e97717a](https://linux-hardware.org/?probe=5e5e97717a) | Nov 04, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2N80... | Notebook    | [87abd90a63](https://linux-hardware.org/?probe=87abd90a63) | Nov 04, 2023 |
| HP            | 8265                        | Desktop     | [49cb61db2e](https://linux-hardware.org/?probe=49cb61db2e) | Nov 04, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [0a0e80ef0f](https://linux-hardware.org/?probe=0a0e80ef0f) | Nov 04, 2023 |
| HP            | EliteBook 850 G5            | Notebook    | [a7f0f43604](https://linux-hardware.org/?probe=a7f0f43604) | Nov 04, 2023 |
| Lenovo        | IdeaPad 3 14ABA7 82RM       | Notebook    | [a8bb556bfe](https://linux-hardware.org/?probe=a8bb556bfe) | Nov 04, 2023 |
| Sony          | VPCEH3J1E                   | Notebook    | [e0ae745034](https://linux-hardware.org/?probe=e0ae745034) | Nov 04, 2023 |
| Lenovo        | 103D SDK0Q40112 WIN 3305... | Desktop     | [76acaae6cc](https://linux-hardware.org/?probe=76acaae6cc) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [c39cd7480d](https://linux-hardware.org/?probe=c39cd7480d) | Nov 04, 2023 |
| Apple         | Mac-F221BEC8                | Desktop     | [03f4055831](https://linux-hardware.org/?probe=03f4055831) | Nov 04, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [5ff7f9b284](https://linux-hardware.org/?probe=5ff7f9b284) | Nov 04, 2023 |
| Toshiba       | Satellite L70-A             | Notebook    | [bf7be11ced](https://linux-hardware.org/?probe=bf7be11ced) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [34e4bd156f](https://linux-hardware.org/?probe=34e4bd156f) | Nov 04, 2023 |
| Lenovo        | IdeaPad 3 17ABA7 82RQ       | Notebook    | [12b6cd2d09](https://linux-hardware.org/?probe=12b6cd2d09) | Nov 04, 2023 |
| TrekStor      | Surfbook W2                 | Notebook    | [cfee0c0363](https://linux-hardware.org/?probe=cfee0c0363) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [aba7da7a37](https://linux-hardware.org/?probe=aba7da7a37) | Nov 04, 2023 |
| Lenovo        | Yoga 9 14IAP7 82LU          | Convertible | [e1c8a14f2a](https://linux-hardware.org/?probe=e1c8a14f2a) | Nov 04, 2023 |
| Packard Be... | EasyNote TE69KB             | Notebook    | [440d52f445](https://linux-hardware.org/?probe=440d52f445) | Nov 04, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [7a24e5115a](https://linux-hardware.org/?probe=7a24e5115a) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [972ef88623](https://linux-hardware.org/?probe=972ef88623) | Nov 04, 2023 |
| HP            | 15                          | Notebook    | [5d5fb36764](https://linux-hardware.org/?probe=5d5fb36764) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [927b50091e](https://linux-hardware.org/?probe=927b50091e) | Nov 04, 2023 |
| HP            | 89B5 A                      | Desktop     | [e31ecc3904](https://linux-hardware.org/?probe=e31ecc3904) | Nov 04, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [30416c0355](https://linux-hardware.org/?probe=30416c0355) | Nov 04, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | Desktop     | [1da3521ff2](https://linux-hardware.org/?probe=1da3521ff2) | Nov 04, 2023 |
| Gigabyte      | 945GM-S2                    | Desktop     | [f71f764594](https://linux-hardware.org/?probe=f71f764594) | Nov 04, 2023 |
| Dell          | Inspiron 16 5620            | Notebook    | [04d425d450](https://linux-hardware.org/?probe=04d425d450) | Nov 04, 2023 |
| Lenovo        | 80SY                        | Notebook    | [7c7a6ba82f](https://linux-hardware.org/?probe=7c7a6ba82f) | Nov 04, 2023 |
| Lenovo        | 317E NOK                    | Desktop     | [1d038af880](https://linux-hardware.org/?probe=1d038af880) | Nov 04, 2023 |
| Timi          | TM1612                      | Notebook    | [f4284a928a](https://linux-hardware.org/?probe=f4284a928a) | Nov 04, 2023 |
| Lenovo        | ThinkPad P16v Gen 1 21FE... | Notebook    | [d0d84fed9a](https://linux-hardware.org/?probe=d0d84fed9a) | Nov 04, 2023 |
| FriendlyEl... | NanoPC-T6                   | Soc         | [7a75d5ed73](https://linux-hardware.org/?probe=7a75d5ed73) | Nov 04, 2023 |
| Medion        | E6214                       | Notebook    | [65976063e7](https://linux-hardware.org/?probe=65976063e7) | Nov 04, 2023 |
| HP            | 83E1                        | Desktop     | [c82d34ebac](https://linux-hardware.org/?probe=c82d34ebac) | Nov 04, 2023 |
| Gigabyte      | GA-MA78LMT-S2               | Desktop     | [1636a231b2](https://linux-hardware.org/?probe=1636a231b2) | Nov 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | Notebook    | [60187ba0be](https://linux-hardware.org/?probe=60187ba0be) | Nov 04, 2023 |
| Acer          | Aspire R5-571TG             | Convertible | [f0e8c6a66f](https://linux-hardware.org/?probe=f0e8c6a66f) | Nov 04, 2023 |
| Gigabyte      | H470M K                     | Desktop     | [d69493b7d2](https://linux-hardware.org/?probe=d69493b7d2) | Nov 04, 2023 |
| HP            | Compaq Presario CQ40        | Notebook    | [ede0c05f18](https://linux-hardware.org/?probe=ede0c05f18) | Nov 04, 2023 |
| Dell          | Latitude E6420              | Notebook    | [6bd73f2b0e](https://linux-hardware.org/?probe=6bd73f2b0e) | Nov 04, 2023 |
| Pegatron      | E60                         | Desktop     | [42e0c4ad61](https://linux-hardware.org/?probe=42e0c4ad61) | Nov 04, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [7d38ea5f87](https://linux-hardware.org/?probe=7d38ea5f87) | Nov 04, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [d4b22ac16a](https://linux-hardware.org/?probe=d4b22ac16a) | Nov 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [3922b02290](https://linux-hardware.org/?probe=3922b02290) | Nov 04, 2023 |
| ASUSTek       | M4N68T-M                    | Desktop     | [582304a8c5](https://linux-hardware.org/?probe=582304a8c5) | Nov 04, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [cda17ca99b](https://linux-hardware.org/?probe=cda17ca99b) | Nov 04, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [669430e32e](https://linux-hardware.org/?probe=669430e32e) | Nov 04, 2023 |
| ASRock        | B550M Pro4                  | Desktop     | [f0354d2416](https://linux-hardware.org/?probe=f0354d2416) | Nov 04, 2023 |
| HP            | Pavilion 17                 | Notebook    | [54cf91ddc7](https://linux-hardware.org/?probe=54cf91ddc7) | Nov 04, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [1fcf1ef0b5](https://linux-hardware.org/?probe=1fcf1ef0b5) | Nov 04, 2023 |
| Gigabyte      | H470M K                     | Desktop     | [80085c7047](https://linux-hardware.org/?probe=80085c7047) | Nov 04, 2023 |
| MSI           | B650 GAMING PLUS WIFI       | Desktop     | [8edaffcccb](https://linux-hardware.org/?probe=8edaffcccb) | Nov 04, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [2d1116cd1b](https://linux-hardware.org/?probe=2d1116cd1b) | Nov 04, 2023 |
| Dell          | 0W0CHX A00                  | Desktop     | [3ed37b3d70](https://linux-hardware.org/?probe=3ed37b3d70) | Nov 04, 2023 |
| Unknown       | Unknown                     | Desktop     | [50949c6e51](https://linux-hardware.org/?probe=50949c6e51) | Nov 04, 2023 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | Desktop     | [6a8536f5df](https://linux-hardware.org/?probe=6a8536f5df) | Nov 04, 2023 |
| Acer          | Aspire A514-55              | Notebook    | [b9ad0e270f](https://linux-hardware.org/?probe=b9ad0e270f) | Nov 04, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [85e528f1bf](https://linux-hardware.org/?probe=85e528f1bf) | Nov 04, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [ebf86ce161](https://linux-hardware.org/?probe=ebf86ce161) | Nov 04, 2023 |
| Google        | Bluebird                    | Notebook    | [55dbc11653](https://linux-hardware.org/?probe=55dbc11653) | Nov 04, 2023 |
| Sony          | SVE15137CGW                 | Notebook    | [5d2a4746af](https://linux-hardware.org/?probe=5d2a4746af) | Nov 04, 2023 |
| Lenovo        | ThinkPad L570 W10DG 20JR... | Notebook    | [5eada91f48](https://linux-hardware.org/?probe=5eada91f48) | Nov 04, 2023 |
| Acidanther... | MacBookPro15,2              | Notebook    | [ae60650070](https://linux-hardware.org/?probe=ae60650070) | Nov 04, 2023 |
| MSI           | MS-1759                     | Notebook    | [2dd46c2a71](https://linux-hardware.org/?probe=2dd46c2a71) | Nov 04, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [07e66cf3c5](https://linux-hardware.org/?probe=07e66cf3c5) | Nov 04, 2023 |
| MSI           | MAG B660M MORTAR WIFI DD... | Desktop     | [3521a1f918](https://linux-hardware.org/?probe=3521a1f918) | Nov 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [9999b9fa3d](https://linux-hardware.org/?probe=9999b9fa3d) | Nov 04, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [18bafa67dc](https://linux-hardware.org/?probe=18bafa67dc) | Nov 04, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [9f47c70860](https://linux-hardware.org/?probe=9f47c70860) | Nov 04, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [5abff2e87a](https://linux-hardware.org/?probe=5abff2e87a) | Nov 04, 2023 |
| Unknown       | Unknown                     | Notebook    | [662c88776a](https://linux-hardware.org/?probe=662c88776a) | Nov 04, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [d95fab9dc1](https://linux-hardware.org/?probe=d95fab9dc1) | Nov 04, 2023 |
| Lenovo        | Legion Y545 81Q6            | Notebook    | [c2fa613f00](https://linux-hardware.org/?probe=c2fa613f00) | Nov 04, 2023 |
| Google        | Bluebird                    | Notebook    | [9e12130a28](https://linux-hardware.org/?probe=9e12130a28) | Nov 04, 2023 |
| HP            | Laptop 14-bw0xx             | Notebook    | [aea5699bb8](https://linux-hardware.org/?probe=aea5699bb8) | Nov 04, 2023 |
| AVITA         | NS14A2                      | Notebook    | [738e0008ce](https://linux-hardware.org/?probe=738e0008ce) | Nov 04, 2023 |
| Lenovo        | ThinkPad T61 6460D6G        | Notebook    | [1d51aba71e](https://linux-hardware.org/?probe=1d51aba71e) | Nov 04, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [4a6383e886](https://linux-hardware.org/?probe=4a6383e886) | Nov 04, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [3d8056e30e](https://linux-hardware.org/?probe=3d8056e30e) | Nov 04, 2023 |
| HP            | ZBook Studio G3             | Notebook    | [eb90a23afa](https://linux-hardware.org/?probe=eb90a23afa) | Nov 04, 2023 |
| Lenovo        | ThinkPad T61 6460D6G        | Notebook    | [585906fa27](https://linux-hardware.org/?probe=585906fa27) | Nov 04, 2023 |
| HP            | 0A9Ch                       | Desktop     | [95415dec13](https://linux-hardware.org/?probe=95415dec13) | Nov 04, 2023 |
| Dell          | Inspiron 15 3511            | Notebook    | [8c23fbf7d1](https://linux-hardware.org/?probe=8c23fbf7d1) | Nov 04, 2023 |
| American M... | A6                          | Notebook    | [4ff43d7d31](https://linux-hardware.org/?probe=4ff43d7d31) | Nov 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [798cba826c](https://linux-hardware.org/?probe=798cba826c) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [119816ea7d](https://linux-hardware.org/?probe=119816ea7d) | Nov 04, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [2b389d48e1](https://linux-hardware.org/?probe=2b389d48e1) | Nov 04, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [d0f3cf43b7](https://linux-hardware.org/?probe=d0f3cf43b7) | Nov 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [905d699d4d](https://linux-hardware.org/?probe=905d699d4d) | Nov 04, 2023 |
| Lenovo        | ThinkPad P43s 20RH0021MX    | Notebook    | [082adbf921](https://linux-hardware.org/?probe=082adbf921) | Nov 04, 2023 |
| HP            | 8767 A                      | Desktop     | [a9d65549d2](https://linux-hardware.org/?probe=a9d65549d2) | Nov 04, 2023 |
| Dell          | Latitude E7450              | Notebook    | [e7effc42ed](https://linux-hardware.org/?probe=e7effc42ed) | Nov 04, 2023 |
| Xiaomi        | POCO X3 NFC                 | Soc         | [009c4485f7](https://linux-hardware.org/?probe=009c4485f7) | Nov 04, 2023 |
| HP            | OMEN by Laptop 17-ck1xxx    | Notebook    | [bea6a6babf](https://linux-hardware.org/?probe=bea6a6babf) | Nov 04, 2023 |
| Xiaomi        | POCO X3 NFC                 | Soc         | [3c682a6ee3](https://linux-hardware.org/?probe=3c682a6ee3) | Nov 04, 2023 |
| Lenovo        | ThinkPad T530 2429F27       | Notebook    | [0767db36fe](https://linux-hardware.org/?probe=0767db36fe) | Nov 04, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [546178d07d](https://linux-hardware.org/?probe=546178d07d) | Nov 04, 2023 |
| Acer          | Aspire A314-23P             | Notebook    | [1e3cdf0bf2](https://linux-hardware.org/?probe=1e3cdf0bf2) | Nov 04, 2023 |
| POV           | I102A                       | Notebook    | [955f97d47e](https://linux-hardware.org/?probe=955f97d47e) | Nov 04, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2c601304f7](https://linux-hardware.org/?probe=2c601304f7) | Nov 04, 2023 |
| Dell          | 062TCH A00                  | Desktop     | [b964b2c6be](https://linux-hardware.org/?probe=b964b2c6be) | Nov 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [af20418f73](https://linux-hardware.org/?probe=af20418f73) | Nov 04, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | Desktop     | [f27bded4c1](https://linux-hardware.org/?probe=f27bded4c1) | Nov 04, 2023 |
| Supermicro    | X11SCA-F                    | Server      | [e63931ed4f](https://linux-hardware.org/?probe=e63931ed4f) | Nov 04, 2023 |
| Dell          | Latitude E5450              | Notebook    | [1f23c5fd7c](https://linux-hardware.org/?probe=1f23c5fd7c) | Nov 04, 2023 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [97e043115e](https://linux-hardware.org/?probe=97e043115e) | Nov 04, 2023 |
| ASUSTek       | H110M-D                     | Desktop     | [03303fa6ed](https://linux-hardware.org/?probe=03303fa6ed) | Nov 04, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [26aff1917e](https://linux-hardware.org/?probe=26aff1917e) | Nov 04, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [afbfce6e52](https://linux-hardware.org/?probe=afbfce6e52) | Nov 04, 2023 |
| Dell          | 0VWT90 A10                  | Server      | [2a20b2817d](https://linux-hardware.org/?probe=2a20b2817d) | Nov 04, 2023 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [cd2b005e61](https://linux-hardware.org/?probe=cd2b005e61) | Nov 04, 2023 |
| MSI           | GV62 7RE                    | Notebook    | [a6ce21c9de](https://linux-hardware.org/?probe=a6ce21c9de) | Nov 04, 2023 |
| ASUSTek       | UX32VD                      | Notebook    | [7c4eefbe35](https://linux-hardware.org/?probe=7c4eefbe35) | Nov 04, 2023 |
| Dell          | 01NP3N A00                  | Desktop     | [2332805279](https://linux-hardware.org/?probe=2332805279) | Nov 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [28f8f3e3cd](https://linux-hardware.org/?probe=28f8f3e3cd) | Nov 04, 2023 |
| ASRock        | B450 Steel Legend           | Desktop     | [2ab63a2fb6](https://linux-hardware.org/?probe=2ab63a2fb6) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [bc3444ed2f](https://linux-hardware.org/?probe=bc3444ed2f) | Nov 04, 2023 |
| Dell          | Inspiron M5110              | Notebook    | [20e338fb21](https://linux-hardware.org/?probe=20e338fb21) | Nov 04, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [f36f4e888c](https://linux-hardware.org/?probe=f36f4e888c) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [3c1e4ea8bf](https://linux-hardware.org/?probe=3c1e4ea8bf) | Nov 04, 2023 |
| ASUSTek       | VivoBook 14_ASUS Laptop ... | Notebook    | [0ce0a4d87a](https://linux-hardware.org/?probe=0ce0a4d87a) | Nov 04, 2023 |
| Toshiba       | TECRA W50-A                 | Notebook    | [ad6c61de24](https://linux-hardware.org/?probe=ad6c61de24) | Nov 04, 2023 |
| Lenovo        | G450 2949                   | Notebook    | [3f631dfb6e](https://linux-hardware.org/?probe=3f631dfb6e) | Nov 04, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [d2a9171090](https://linux-hardware.org/?probe=d2a9171090) | Nov 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [bb7622a7ba](https://linux-hardware.org/?probe=bb7622a7ba) | Nov 04, 2023 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [a3eb4c9d76](https://linux-hardware.org/?probe=a3eb4c9d76) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [c07d28d9bc](https://linux-hardware.org/?probe=c07d28d9bc) | Nov 04, 2023 |
| Lenovo        | IdeaPad 710S Plus-13ISK ... | Notebook    | [f143d09ba7](https://linux-hardware.org/?probe=f143d09ba7) | Nov 04, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [00cab2c4d1](https://linux-hardware.org/?probe=00cab2c4d1) | Nov 04, 2023 |
| Dell          | 018D1Y A00                  | Desktop     | [2135015e09](https://linux-hardware.org/?probe=2135015e09) | Nov 04, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [8685e384af](https://linux-hardware.org/?probe=8685e384af) | Nov 04, 2023 |
| Dell          | Precision 7560              | Notebook    | [54a8deb305](https://linux-hardware.org/?probe=54a8deb305) | Nov 04, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [ea9a865ed2](https://linux-hardware.org/?probe=ea9a865ed2) | Nov 03, 2023 |
| Microsoft     | Surface Book 3              | Tablet      | [ba8e987366](https://linux-hardware.org/?probe=ba8e987366) | Nov 03, 2023 |
| Raspberry ... | Raspberry Pi 5 Model B R... | Soc         | [6d47b63d51](https://linux-hardware.org/?probe=6d47b63d51) | Nov 03, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [cfb51ce306](https://linux-hardware.org/?probe=cfb51ce306) | Nov 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [d17e6059bb](https://linux-hardware.org/?probe=d17e6059bb) | Nov 03, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [86d2394935](https://linux-hardware.org/?probe=86d2394935) | Nov 03, 2023 |
| HP            | 246 G6 Notebook PC          | Notebook    | [cd997e5a97](https://linux-hardware.org/?probe=cd997e5a97) | Nov 03, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [f029848e7d](https://linux-hardware.org/?probe=f029848e7d) | Nov 03, 2023 |
| Dell          | Inspiron N4010              | Notebook    | [f8aed4abab](https://linux-hardware.org/?probe=f8aed4abab) | Nov 03, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [abe3da8a30](https://linux-hardware.org/?probe=abe3da8a30) | Nov 03, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [de4c3bfe46](https://linux-hardware.org/?probe=de4c3bfe46) | Nov 03, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [7d06f443c7](https://linux-hardware.org/?probe=7d06f443c7) | Nov 03, 2023 |
| Apple         | Mac-F60DEB81FF30ACF6 Mac... | Desktop     | [b213aefe09](https://linux-hardware.org/?probe=b213aefe09) | Nov 03, 2023 |
| Lenovo        | ThinkPad X220 4293A25       | Notebook    | [95a5125a73](https://linux-hardware.org/?probe=95a5125a73) | Nov 03, 2023 |
| HP            | OMEN by Laptop 17-ck2xxx    | Notebook    | [e34a0ab109](https://linux-hardware.org/?probe=e34a0ab109) | Nov 03, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [300c72bf93](https://linux-hardware.org/?probe=300c72bf93) | Nov 03, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [c864159547](https://linux-hardware.org/?probe=c864159547) | Nov 03, 2023 |
| HP            | Elite x2 1012 G2 Tablet     | Tablet      | [8e563a8223](https://linux-hardware.org/?probe=8e563a8223) | Nov 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [1f2c5ea57b](https://linux-hardware.org/?probe=1f2c5ea57b) | Nov 03, 2023 |
| Intel         | NUC7i5BNB J31144-314        | Mini pc     | [5949f1fc04](https://linux-hardware.org/?probe=5949f1fc04) | Nov 03, 2023 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [e7ccaf83d7](https://linux-hardware.org/?probe=e7ccaf83d7) | Nov 03, 2023 |
| Irbis         | NB211                       | Notebook    | [694ca0f127](https://linux-hardware.org/?probe=694ca0f127) | Nov 03, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [85a38e7906](https://linux-hardware.org/?probe=85a38e7906) | Nov 03, 2023 |
| System76      | Oryx Pro                    | Notebook    | [1704acc89b](https://linux-hardware.org/?probe=1704acc89b) | Nov 03, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [dff06d88c5](https://linux-hardware.org/?probe=dff06d88c5) | Nov 03, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [61342b31ea](https://linux-hardware.org/?probe=61342b31ea) | Nov 03, 2023 |
| Supermicro    | X9DRW                       | Desktop     | [d9bb198389](https://linux-hardware.org/?probe=d9bb198389) | Nov 03, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [f8e737dbde](https://linux-hardware.org/?probe=f8e737dbde) | Nov 03, 2023 |
| Lenovo        | ThinkPad T460p 20FXS0960... | Notebook    | [10407542ab](https://linux-hardware.org/?probe=10407542ab) | Nov 03, 2023 |
| Thomson       | N14C4WH64                   | Notebook    | [51c94bc00f](https://linux-hardware.org/?probe=51c94bc00f) | Nov 03, 2023 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [4a350b6fdb](https://linux-hardware.org/?probe=4a350b6fdb) | Nov 03, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [e7d16a3fc2](https://linux-hardware.org/?probe=e7d16a3fc2) | Nov 03, 2023 |
| Dell          | Latitude 3420               | Notebook    | [9211e0f588](https://linux-hardware.org/?probe=9211e0f588) | Nov 03, 2023 |
| Lenovo        | G580 2189                   | Notebook    | [29a529e02c](https://linux-hardware.org/?probe=29a529e02c) | Nov 03, 2023 |
| Gigabyte      | H81M-DS2                    | Desktop     | [5ac9818b1f](https://linux-hardware.org/?probe=5ac9818b1f) | Nov 03, 2023 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [62a859fb72](https://linux-hardware.org/?probe=62a859fb72) | Nov 03, 2023 |
| ECS           | A890GXM-A2                  | Desktop     | [3e5d819c23](https://linux-hardware.org/?probe=3e5d819c23) | Nov 03, 2023 |
| ASUSTek       | X551CA                      | Notebook    | [20bee22e0a](https://linux-hardware.org/?probe=20bee22e0a) | Nov 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [7b64212148](https://linux-hardware.org/?probe=7b64212148) | Nov 03, 2023 |
| BANGHO        | Suma 1025                   | Tablet      | [a0ed1238ea](https://linux-hardware.org/?probe=a0ed1238ea) | Nov 03, 2023 |
| ECS           | A890GXM-A2                  | Desktop     | [9fb5c6d4d3](https://linux-hardware.org/?probe=9fb5c6d4d3) | Nov 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [d27cd12013](https://linux-hardware.org/?probe=d27cd12013) | Nov 03, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21EDC... | Notebook    | [b4d28df125](https://linux-hardware.org/?probe=b4d28df125) | Nov 03, 2023 |
| Packard Be... | EasyNote TK87               | Notebook    | [3ff2e66179](https://linux-hardware.org/?probe=3ff2e66179) | Nov 03, 2023 |
| Gigabyte      | H510M S2H V2                | Desktop     | [2d4845b6b9](https://linux-hardware.org/?probe=2d4845b6b9) | Nov 03, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [f4bae2d5b5](https://linux-hardware.org/?probe=f4bae2d5b5) | Nov 03, 2023 |
| ASRock        | H61M-HVS                    | Desktop     | [fbbb34a0cb](https://linux-hardware.org/?probe=fbbb34a0cb) | Nov 03, 2023 |
| HP            | 255 G6 Notebook PC          | Notebook    | [b73e7cf536](https://linux-hardware.org/?probe=b73e7cf536) | Nov 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [db71fb65bf](https://linux-hardware.org/?probe=db71fb65bf) | Nov 03, 2023 |
| ASRock        | TRX40 Creator               | Desktop     | [05304710e4](https://linux-hardware.org/?probe=05304710e4) | Nov 03, 2023 |
| Acer          | Aspire 5920                 | Notebook    | [02fa7cf5bb](https://linux-hardware.org/?probe=02fa7cf5bb) | Nov 03, 2023 |
| Lenovo        | B560 433028U                | Notebook    | [37a6693c3d](https://linux-hardware.org/?probe=37a6693c3d) | Nov 03, 2023 |
| DEXP          | Aquilon C14                 | Notebook    | [b91d7803a2](https://linux-hardware.org/?probe=b91d7803a2) | Nov 03, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [a816b34b9e](https://linux-hardware.org/?probe=a816b34b9e) | Nov 03, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [6c0dc28b9f](https://linux-hardware.org/?probe=6c0dc28b9f) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [c9e7b12e63](https://linux-hardware.org/?probe=c9e7b12e63) | Nov 03, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [9501d6d6cf](https://linux-hardware.org/?probe=9501d6d6cf) | Nov 03, 2023 |
| VALE          | Notebook Classic C140       | Notebook    | [fd52185cf0](https://linux-hardware.org/?probe=fd52185cf0) | Nov 03, 2023 |
| Google        | Phaser360                   | Notebook    | [9915a1a3be](https://linux-hardware.org/?probe=9915a1a3be) | Nov 03, 2023 |
| HP            | 859C                        | Desktop     | [7928158950](https://linux-hardware.org/?probe=7928158950) | Nov 03, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [ded1d73643](https://linux-hardware.org/?probe=ded1d73643) | Nov 03, 2023 |
| ASRock        | A770DE+                     | Desktop     | [330e203c8a](https://linux-hardware.org/?probe=330e203c8a) | Nov 03, 2023 |
| Timi          | A35S                        | Notebook    | [d62fbb6f83](https://linux-hardware.org/?probe=d62fbb6f83) | Nov 03, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [ae66cf41f9](https://linux-hardware.org/?probe=ae66cf41f9) | Nov 03, 2023 |
| Intel         | H610-MIX v1.0               | Desktop     | [eeaea55301](https://linux-hardware.org/?probe=eeaea55301) | Nov 03, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [0e71b912ec](https://linux-hardware.org/?probe=0e71b912ec) | Nov 03, 2023 |
| ASRock        | TRX40 Creator               | Desktop     | [62f85af4b5](https://linux-hardware.org/?probe=62f85af4b5) | Nov 03, 2023 |
| HUAWEI        | MRGFG-XX                    | Notebook    | [5117a849b3](https://linux-hardware.org/?probe=5117a849b3) | Nov 03, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [792c22d04f](https://linux-hardware.org/?probe=792c22d04f) | Nov 03, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [92b484d86d](https://linux-hardware.org/?probe=92b484d86d) | Nov 03, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [7a6f17c843](https://linux-hardware.org/?probe=7a6f17c843) | Nov 03, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [ff0d013246](https://linux-hardware.org/?probe=ff0d013246) | Nov 03, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [993a2b9f3e](https://linux-hardware.org/?probe=993a2b9f3e) | Nov 03, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [4236902f3d](https://linux-hardware.org/?probe=4236902f3d) | Nov 03, 2023 |
| Dell          | Latitude E6420              | Notebook    | [43ccf36bf0](https://linux-hardware.org/?probe=43ccf36bf0) | Nov 03, 2023 |
| Intel         | X79 V1.0                    | Desktop     | [9483a097a1](https://linux-hardware.org/?probe=9483a097a1) | Nov 03, 2023 |
| HONOR         | NMH-WDX9                    | Notebook    | [11e32e2482](https://linux-hardware.org/?probe=11e32e2482) | Nov 03, 2023 |
| Google        | Enguarde                    | Notebook    | [bc6a541eb9](https://linux-hardware.org/?probe=bc6a541eb9) | Nov 03, 2023 |
| Gigabyte      | 970A-D3                     | Desktop     | [80fb26e63a](https://linux-hardware.org/?probe=80fb26e63a) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [d35fc5aa78](https://linux-hardware.org/?probe=d35fc5aa78) | Nov 03, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [547a248361](https://linux-hardware.org/?probe=547a248361) | Nov 03, 2023 |
| Timi          | A35                         | Notebook    | [1baa5932cc](https://linux-hardware.org/?probe=1baa5932cc) | Nov 03, 2023 |
| HP            | Pavilion dv6                | Notebook    | [bf6361ff84](https://linux-hardware.org/?probe=bf6361ff84) | Nov 03, 2023 |
| Multilaser    | PC13X                       | Notebook    | [1c6a314055](https://linux-hardware.org/?probe=1c6a314055) | Nov 03, 2023 |
| Supermicro    | X8DTU                       | Server      | [17ea09c2b2](https://linux-hardware.org/?probe=17ea09c2b2) | Nov 03, 2023 |
| Dell          | Latitude 7280               | Notebook    | [b795f0157b](https://linux-hardware.org/?probe=b795f0157b) | Nov 03, 2023 |
| Supermicro    | X10DRL-i                    | Desktop     | [cada5224ab](https://linux-hardware.org/?probe=cada5224ab) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [a0c7507d6d](https://linux-hardware.org/?probe=a0c7507d6d) | Nov 03, 2023 |
| Dell          | 0VHWTR A02                  | Desktop     | [7663b608dd](https://linux-hardware.org/?probe=7663b608dd) | Nov 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [594257aca2](https://linux-hardware.org/?probe=594257aca2) | Nov 03, 2023 |
| HP            | 0B54h D                     | Desktop     | [574e5fd946](https://linux-hardware.org/?probe=574e5fd946) | Nov 03, 2023 |
| MSI           | GF75 Thin 9SC               | Notebook    | [2aceaf7016](https://linux-hardware.org/?probe=2aceaf7016) | Nov 03, 2023 |
| Dell          | Precision 5550              | Notebook    | [033e294199](https://linux-hardware.org/?probe=033e294199) | Nov 03, 2023 |
| HP            | Compaq 6730s                | Notebook    | [073756d958](https://linux-hardware.org/?probe=073756d958) | Nov 03, 2023 |
| Dell          | 09WH54 A01                  | Desktop     | [4eae8e67db](https://linux-hardware.org/?probe=4eae8e67db) | Nov 03, 2023 |
| Toshiba       | Satellite C660D             | Notebook    | [de50c92d6c](https://linux-hardware.org/?probe=de50c92d6c) | Nov 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [0b00fd801c](https://linux-hardware.org/?probe=0b00fd801c) | Nov 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JR0... | Notebook    | [d1d65399a0](https://linux-hardware.org/?probe=d1d65399a0) | Nov 03, 2023 |
| Medion        | ERAZER X7855 MD60892        | Notebook    | [b34c69b29d](https://linux-hardware.org/?probe=b34c69b29d) | Nov 03, 2023 |
| ZOTAC         | ZBOXNANO-AD10               | Mini pc     | [2b0fbc5661](https://linux-hardware.org/?probe=2b0fbc5661) | Nov 03, 2023 |
| HP            | Spectre Folio Convertibl... | Convertible | [aa5a6d3348](https://linux-hardware.org/?probe=aa5a6d3348) | Nov 03, 2023 |
| Lenovo        | ThinkPad X1 Fold Gen 1 2... | Tablet      | [a06677f6ea](https://linux-hardware.org/?probe=a06677f6ea) | Nov 03, 2023 |
| Lenovo        | ThinkPad X1 Fold Gen 1 2... | Tablet      | [d8c90f446f](https://linux-hardware.org/?probe=d8c90f446f) | Nov 03, 2023 |
| Lenovo        | ThinkPad T420s 417032U      | Notebook    | [76247c39f4](https://linux-hardware.org/?probe=76247c39f4) | Nov 03, 2023 |
| Lenovo        | 310C SDK0J40697 WIN 3305... | Mini pc     | [f69b9b159a](https://linux-hardware.org/?probe=f69b9b159a) | Nov 03, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [49ec48adb9](https://linux-hardware.org/?probe=49ec48adb9) | Nov 03, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [4342649c26](https://linux-hardware.org/?probe=4342649c26) | Nov 03, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [baf30122ca](https://linux-hardware.org/?probe=baf30122ca) | Nov 03, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [44890192a1](https://linux-hardware.org/?probe=44890192a1) | Nov 03, 2023 |
| Dell          | 0T7D40 A00                  | Desktop     | [a81d5bbd02](https://linux-hardware.org/?probe=a81d5bbd02) | Nov 03, 2023 |
| ASUSTek       | X550VQ                      | Notebook    | [b6d6ff10aa](https://linux-hardware.org/?probe=b6d6ff10aa) | Nov 03, 2023 |
| ETegro Tec... | ETRS125G4 31S2MMB0040       | Server      | [5085991741](https://linux-hardware.org/?probe=5085991741) | Nov 03, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [ee12470303](https://linux-hardware.org/?probe=ee12470303) | Nov 03, 2023 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [2ac0d5a547](https://linux-hardware.org/?probe=2ac0d5a547) | Nov 03, 2023 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [4ccd2ef567](https://linux-hardware.org/?probe=4ccd2ef567) | Nov 03, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [ce98faee85](https://linux-hardware.org/?probe=ce98faee85) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [2aa4f1a7f7](https://linux-hardware.org/?probe=2aa4f1a7f7) | Nov 03, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3c4533c5a9](https://linux-hardware.org/?probe=3c4533c5a9) | Nov 03, 2023 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [8b855ce4f4](https://linux-hardware.org/?probe=8b855ce4f4) | Nov 03, 2023 |
| ASRock        | H170M Pro4                  | Desktop     | [b87ccd7768](https://linux-hardware.org/?probe=b87ccd7768) | Nov 03, 2023 |
| Rockchip      | Orange Pi 5 Plus            | Soc         | [9c30c8c8b4](https://linux-hardware.org/?probe=9c30c8c8b4) | Nov 03, 2023 |
| Supermicro    | X8DTU                       | Server      | [1e45f05458](https://linux-hardware.org/?probe=1e45f05458) | Nov 03, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [76374cbbfe](https://linux-hardware.org/?probe=76374cbbfe) | Nov 03, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [429b14ee32](https://linux-hardware.org/?probe=429b14ee32) | Nov 03, 2023 |
| Lenovo        | IdeaPad 3 15IML05 81WB      | Notebook    | [f9bdbf6371](https://linux-hardware.org/?probe=f9bdbf6371) | Nov 03, 2023 |
| Supermicro    | X8DTU                       | Server      | [330f475535](https://linux-hardware.org/?probe=330f475535) | Nov 03, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [bc3b3daf33](https://linux-hardware.org/?probe=bc3b3daf33) | Nov 03, 2023 |
| Insyde        | Purley                      | Server      | [cb46a7ce21](https://linux-hardware.org/?probe=cb46a7ce21) | Nov 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [b526accbcd](https://linux-hardware.org/?probe=b526accbcd) | Nov 03, 2023 |
| Colorful T... | CVN X570M GAMING PRO V14    | Desktop     | [65b9bad459](https://linux-hardware.org/?probe=65b9bad459) | Nov 03, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [ac631c05bc](https://linux-hardware.org/?probe=ac631c05bc) | Nov 03, 2023 |
| Dell          | Latitude E5570              | Notebook    | [a4617a2ea3](https://linux-hardware.org/?probe=a4617a2ea3) | Nov 03, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [d8ceb3854c](https://linux-hardware.org/?probe=d8ceb3854c) | Nov 03, 2023 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [5339cc53ed](https://linux-hardware.org/?probe=5339cc53ed) | Nov 03, 2023 |
| ASUSTek       | PRIME X299-A                | Desktop     | [387194bdf6](https://linux-hardware.org/?probe=387194bdf6) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [b592d36d74](https://linux-hardware.org/?probe=b592d36d74) | Nov 03, 2023 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [e95902544f](https://linux-hardware.org/?probe=e95902544f) | Nov 03, 2023 |
| Dell          | Precision 5750              | Notebook    | [00e8468779](https://linux-hardware.org/?probe=00e8468779) | Nov 03, 2023 |
| Dell          | Latitude E5570              | Notebook    | [82d66aaaf1](https://linux-hardware.org/?probe=82d66aaaf1) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [da695062ba](https://linux-hardware.org/?probe=da695062ba) | Nov 03, 2023 |
| Intel         | X99                         | Desktop     | [cb3515efba](https://linux-hardware.org/?probe=cb3515efba) | Nov 03, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [157f3bd86a](https://linux-hardware.org/?probe=157f3bd86a) | Nov 03, 2023 |
| Lenovo        | ThinkPad 11e 5th Gen 20L... | Notebook    | [fca8401d97](https://linux-hardware.org/?probe=fca8401d97) | Nov 03, 2023 |
| HP            | 843B                        | Desktop     | [8fdaf74414](https://linux-hardware.org/?probe=8fdaf74414) | Nov 03, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [bcea72b22f](https://linux-hardware.org/?probe=bcea72b22f) | Nov 03, 2023 |
| HP            | 843B                        | Desktop     | [ba22079238](https://linux-hardware.org/?probe=ba22079238) | Nov 03, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [5ff77430fa](https://linux-hardware.org/?probe=5ff77430fa) | Nov 03, 2023 |
| Dell          | Latitude E7470              | Notebook    | [343fdc858a](https://linux-hardware.org/?probe=343fdc858a) | Nov 03, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | Notebook    | [0845a0ec43](https://linux-hardware.org/?probe=0845a0ec43) | Nov 03, 2023 |
| ASUSTek       | X510URR                     | Notebook    | [645fbe9fc3](https://linux-hardware.org/?probe=645fbe9fc3) | Nov 03, 2023 |
| Dell          | 0TDG4V A01                  | Desktop     | [9d9b09db51](https://linux-hardware.org/?probe=9d9b09db51) | Nov 03, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [4933bbb7ac](https://linux-hardware.org/?probe=4933bbb7ac) | Nov 03, 2023 |
| Lenovo        | ThinkPad T470s 20HF0047U... | Notebook    | [00a8b74f46](https://linux-hardware.org/?probe=00a8b74f46) | Nov 03, 2023 |
| MSI           | 760GM-P21                   | Desktop     | [f3b16a05ae](https://linux-hardware.org/?probe=f3b16a05ae) | Nov 03, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [9c089ed10c](https://linux-hardware.org/?probe=9c089ed10c) | Nov 03, 2023 |
| Supermicro    | X10DRU-i+B                  | Desktop     | [305ce5bbcc](https://linux-hardware.org/?probe=305ce5bbcc) | Nov 03, 2023 |
| Supermicro    | X10DDW-i                    | Desktop     | [8a0ff875f1](https://linux-hardware.org/?probe=8a0ff875f1) | Nov 03, 2023 |
| Supermicro    | X10DDW-i                    | Desktop     | [3138fbde8e](https://linux-hardware.org/?probe=3138fbde8e) | Nov 03, 2023 |
| Supermicro    | X10DDW-i                    | Desktop     | [f3023a2a6f](https://linux-hardware.org/?probe=f3023a2a6f) | Nov 03, 2023 |
| Supermicro    | X10DDW-i                    | Desktop     | [d9dcb6003e](https://linux-hardware.org/?probe=d9dcb6003e) | Nov 03, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [d6f5634b02](https://linux-hardware.org/?probe=d6f5634b02) | Nov 03, 2023 |
| Lenovo        | G500s 20245                 | Notebook    | [c4aa915297](https://linux-hardware.org/?probe=c4aa915297) | Nov 03, 2023 |
| Lenovo        | ThinkPad Z13 Gen 1 21D3S... | Notebook    | [6a2591b5e9](https://linux-hardware.org/?probe=6a2591b5e9) | Nov 03, 2023 |
| Dell          | Latitude 9330               | Convertible | [d4597194bb](https://linux-hardware.org/?probe=d4597194bb) | Nov 03, 2023 |
| Gigabyte      | G41MT-D3                    | Desktop     | [3a4be91563](https://linux-hardware.org/?probe=3a4be91563) | Nov 03, 2023 |
| Toshiba       | Satellite C650              | Notebook    | [6844fc4fcf](https://linux-hardware.org/?probe=6844fc4fcf) | Nov 03, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [48103e7e91](https://linux-hardware.org/?probe=48103e7e91) | Nov 03, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [400a0e689f](https://linux-hardware.org/?probe=400a0e689f) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1bdfa38b3e](https://linux-hardware.org/?probe=1bdfa38b3e) | Nov 03, 2023 |
| Lenovo        | ThinkBook Plus G3 IAP 21... | Notebook    | [a6fabd1a6d](https://linux-hardware.org/?probe=a6fabd1a6d) | Nov 03, 2023 |
| MSI           | MEG X570 UNIFY              | Desktop     | [89e8c02e17](https://linux-hardware.org/?probe=89e8c02e17) | Nov 03, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [f16aeca403](https://linux-hardware.org/?probe=f16aeca403) | Nov 03, 2023 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [f96f6e6127](https://linux-hardware.org/?probe=f96f6e6127) | Nov 03, 2023 |
| Gigabyte      | GA-790XTA-UD4               | Desktop     | [71fd69724b](https://linux-hardware.org/?probe=71fd69724b) | Nov 03, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [2e6585ecc4](https://linux-hardware.org/?probe=2e6585ecc4) | Nov 03, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [3a8d337535](https://linux-hardware.org/?probe=3a8d337535) | Nov 03, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [6d39c4f814](https://linux-hardware.org/?probe=6d39c4f814) | Nov 03, 2023 |
| HP            | ProBook 4330s               | Notebook    | [046f30b044](https://linux-hardware.org/?probe=046f30b044) | Nov 03, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [28990f206a](https://linux-hardware.org/?probe=28990f206a) | Nov 03, 2023 |
| Dell          | Inspiron 15-7568            | Notebook    | [70b564a0db](https://linux-hardware.org/?probe=70b564a0db) | Nov 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [a08b1cfa29](https://linux-hardware.org/?probe=a08b1cfa29) | Nov 03, 2023 |
| Dell          | 05KX61 A02                  | Server      | [e74ef17929](https://linux-hardware.org/?probe=e74ef17929) | Nov 03, 2023 |
| HP            | 21D0                        | Desktop     | [c634d51a77](https://linux-hardware.org/?probe=c634d51a77) | Nov 03, 2023 |
| Gigabyte      | P35-DS3L                    | Desktop     | [c2df6f267b](https://linux-hardware.org/?probe=c2df6f267b) | Nov 03, 2023 |
| Dell          | 05KX61 A02                  | Server      | [3ccea24165](https://linux-hardware.org/?probe=3ccea24165) | Nov 03, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [0be20c3fe3](https://linux-hardware.org/?probe=0be20c3fe3) | Nov 03, 2023 |
| ASUSTek       | PRIME H370M-PLUS            | Desktop     | [328a40f6fe](https://linux-hardware.org/?probe=328a40f6fe) | Nov 03, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [f9942dbf89](https://linux-hardware.org/?probe=f9942dbf89) | Nov 03, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [e928da88d7](https://linux-hardware.org/?probe=e928da88d7) | Nov 03, 2023 |
| ASUSTek       | X205TA                      | Notebook    | [b29e9ebfbe](https://linux-hardware.org/?probe=b29e9ebfbe) | Nov 03, 2023 |
| ASUSTek       | M3A78-CM                    | Desktop     | [0e493c7b85](https://linux-hardware.org/?probe=0e493c7b85) | Nov 03, 2023 |
| NEC Comput... | MS-7770MH                   | Desktop     | [9d2ab645d4](https://linux-hardware.org/?probe=9d2ab645d4) | Nov 03, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [684c7d7bf7](https://linux-hardware.org/?probe=684c7d7bf7) | Nov 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [6987861086](https://linux-hardware.org/?probe=6987861086) | Nov 03, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [3618f2a4b5](https://linux-hardware.org/?probe=3618f2a4b5) | Nov 03, 2023 |
| Acer          | Aspire V5-571P              | Notebook    | [36d10f86c0](https://linux-hardware.org/?probe=36d10f86c0) | Nov 03, 2023 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [9495d53da4](https://linux-hardware.org/?probe=9495d53da4) | Nov 03, 2023 |
| HP            | 0AECh D                     | Desktop     | [2ddad2bbf2](https://linux-hardware.org/?probe=2ddad2bbf2) | Nov 03, 2023 |
| HP            | ZBook Power G7 Mobile Wo... | Notebook    | [044aa1f9b5](https://linux-hardware.org/?probe=044aa1f9b5) | Nov 03, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [e26ed8b740](https://linux-hardware.org/?probe=e26ed8b740) | Nov 03, 2023 |
| Dell          | 09T7VV A05                  | Server      | [8d5ae6e4de](https://linux-hardware.org/?probe=8d5ae6e4de) | Nov 03, 2023 |
| Irbis         | NB211                       | Notebook    | [3ebca4338a](https://linux-hardware.org/?probe=3ebca4338a) | Nov 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [367bde5a11](https://linux-hardware.org/?probe=367bde5a11) | Nov 03, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [f23e44229f](https://linux-hardware.org/?probe=f23e44229f) | Nov 03, 2023 |
| Alienware     | 0GWM1Y A00                  | Desktop     | [01d536cc44](https://linux-hardware.org/?probe=01d536cc44) | Nov 03, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [239e99c725](https://linux-hardware.org/?probe=239e99c725) | Nov 03, 2023 |
| Schenker      | XMG CORE (REN/E21)          | Notebook    | [9edac2c8ee](https://linux-hardware.org/?probe=9edac2c8ee) | Nov 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N740... | Notebook    | [7fd71a723a](https://linux-hardware.org/?probe=7fd71a723a) | Nov 03, 2023 |
| HP            | Stream Laptop 11-ah1XX      | Notebook    | [94cdd979b2](https://linux-hardware.org/?probe=94cdd979b2) | Nov 03, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [e073d8c90a](https://linux-hardware.org/?probe=e073d8c90a) | Nov 03, 2023 |
| Dell          | 0MGK50 A02                  | Desktop     | [ca062f44be](https://linux-hardware.org/?probe=ca062f44be) | Nov 03, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [18f018a8ae](https://linux-hardware.org/?probe=18f018a8ae) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK S937               | Notebook    | [e4e8acb8db](https://linux-hardware.org/?probe=e4e8acb8db) | Nov 03, 2023 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [36fb8d63bb](https://linux-hardware.org/?probe=36fb8d63bb) | Nov 03, 2023 |
| Dell          | 0CN7X8 A05                  | Server      | [afe0c7dfbe](https://linux-hardware.org/?probe=afe0c7dfbe) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK A3510              | Notebook    | [0929326be0](https://linux-hardware.org/?probe=0929326be0) | Nov 03, 2023 |
| Medion        | MS-7848                     | Desktop     | [ced5528ea5](https://linux-hardware.org/?probe=ced5528ea5) | Nov 03, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [2314e30b70](https://linux-hardware.org/?probe=2314e30b70) | Nov 03, 2023 |
| HP            | Stream Laptop 11-ah1XX      | Notebook    | [5149df3a58](https://linux-hardware.org/?probe=5149df3a58) | Nov 03, 2023 |
| HP            | 2215                        | Desktop     | [6acbe1a873](https://linux-hardware.org/?probe=6acbe1a873) | Nov 03, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [491aa458cc](https://linux-hardware.org/?probe=491aa458cc) | Nov 03, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | Notebook    | [de293a4621](https://linux-hardware.org/?probe=de293a4621) | Nov 03, 2023 |
| Fujitsu       | LIFEBOOK S710               | Notebook    | [b0ee1e5f32](https://linux-hardware.org/?probe=b0ee1e5f32) | Nov 03, 2023 |
| MSI           | MEG B550 UNIFY-X            | Desktop     | [88f58a978f](https://linux-hardware.org/?probe=88f58a978f) | Nov 03, 2023 |
| Acer          | Swift SF114-32              | Notebook    | [ad12644dff](https://linux-hardware.org/?probe=ad12644dff) | Nov 03, 2023 |
| HP            | 250 G7 Notebook PC          | Notebook    | [1889111d8a](https://linux-hardware.org/?probe=1889111d8a) | Nov 03, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | Notebook    | [5d06dbbe5f](https://linux-hardware.org/?probe=5d06dbbe5f) | Nov 03, 2023 |
| Fujitsu Si... | G31T-M2 V3.02               | Desktop     | [d069c6012d](https://linux-hardware.org/?probe=d069c6012d) | Nov 03, 2023 |
| Dell          | Latitude 5511               | Notebook    | [66a8176344](https://linux-hardware.org/?probe=66a8176344) | Nov 03, 2023 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [9ea1c674f9](https://linux-hardware.org/?probe=9ea1c674f9) | Nov 03, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [e1edc2410b](https://linux-hardware.org/?probe=e1edc2410b) | Nov 03, 2023 |
| Acer          | Aspire VN7-591G             | Notebook    | [f446da83f1](https://linux-hardware.org/?probe=f446da83f1) | Nov 03, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [e14eb66450](https://linux-hardware.org/?probe=e14eb66450) | Nov 03, 2023 |
| Acer          | Aspire V3-771               | Notebook    | [3a0023b4ba](https://linux-hardware.org/?probe=3a0023b4ba) | Nov 03, 2023 |
| MACHINIST     | H81M-PRO S1 V2.0            | Desktop     | [98b382243b](https://linux-hardware.org/?probe=98b382243b) | Nov 03, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | Notebook    | [cf0c02a17a](https://linux-hardware.org/?probe=cf0c02a17a) | Nov 03, 2023 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [1b43feda1f](https://linux-hardware.org/?probe=1b43feda1f) | Nov 03, 2023 |
| Dell          | 0X8DXD A00                  | Desktop     | [e972336105](https://linux-hardware.org/?probe=e972336105) | Nov 03, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [3ddccb994b](https://linux-hardware.org/?probe=3ddccb994b) | Nov 03, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [7aa3982cb4](https://linux-hardware.org/?probe=7aa3982cb4) | Nov 03, 2023 |
| Apple         | MacBookAir7,1               | Notebook    | [50cb167f37](https://linux-hardware.org/?probe=50cb167f37) | Nov 03, 2023 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [b0d77e36b1](https://linux-hardware.org/?probe=b0d77e36b1) | Nov 03, 2023 |
| Dell          | 0R6PCT A01                  | Desktop     | [c561f87237](https://linux-hardware.org/?probe=c561f87237) | Nov 02, 2023 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [212105774f](https://linux-hardware.org/?probe=212105774f) | Nov 02, 2023 |
| Hampoo        | I2W6_AP135 Reserved         | Notebook    | [fdb464fed7](https://linux-hardware.org/?probe=fdb464fed7) | Nov 02, 2023 |
| Star Labs     | StarBook                    | Notebook    | [288fdf6f55](https://linux-hardware.org/?probe=288fdf6f55) | Nov 02, 2023 |
| ASRock        | B450M Steel Legend          | Desktop     | [dafce26ef5](https://linux-hardware.org/?probe=dafce26ef5) | Nov 02, 2023 |
| HP            | 18E7                        | Desktop     | [212d6dba47](https://linux-hardware.org/?probe=212d6dba47) | Nov 02, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [62579a601d](https://linux-hardware.org/?probe=62579a601d) | Nov 02, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [9cabd6fd2c](https://linux-hardware.org/?probe=9cabd6fd2c) | Nov 02, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [26bc5f025c](https://linux-hardware.org/?probe=26bc5f025c) | Nov 02, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [3414d178f2](https://linux-hardware.org/?probe=3414d178f2) | Nov 02, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [b58b97e74a](https://linux-hardware.org/?probe=b58b97e74a) | Nov 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [14de2c4b3a](https://linux-hardware.org/?probe=14de2c4b3a) | Nov 02, 2023 |
| HP            | 18E7                        | Desktop     | [7064df5d87](https://linux-hardware.org/?probe=7064df5d87) | Nov 02, 2023 |
| Lenovo        | ThinkPad L560 20F2S0DA00    | Notebook    | [3030ad2bc8](https://linux-hardware.org/?probe=3030ad2bc8) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [4b04b9ef25](https://linux-hardware.org/?probe=4b04b9ef25) | Nov 02, 2023 |
| Unknown       | X99-GT                      | Desktop     | [751ea1add9](https://linux-hardware.org/?probe=751ea1add9) | Nov 02, 2023 |
| Lenovo        | ThinkPad T480s 20L8S35G0... | Notebook    | [14074a05b9](https://linux-hardware.org/?probe=14074a05b9) | Nov 02, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | Notebook    | [9552d5f729](https://linux-hardware.org/?probe=9552d5f729) | Nov 02, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [5bb358c66e](https://linux-hardware.org/?probe=5bb358c66e) | Nov 02, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [7d589af687](https://linux-hardware.org/?probe=7d589af687) | Nov 02, 2023 |
| Biostar       | B250MHC                     | Desktop     | [528c04a30a](https://linux-hardware.org/?probe=528c04a30a) | Nov 02, 2023 |
| ASUSTek       | PRIME H770-PLUS D4          | Desktop     | [62645c6b56](https://linux-hardware.org/?probe=62645c6b56) | Nov 02, 2023 |
| Shenzhen M... | F7BFD                       | Desktop     | [f2b8e311c3](https://linux-hardware.org/?probe=f2b8e311c3) | Nov 02, 2023 |
| Dell          | Vostro 5590                 | Notebook    | [aa355fcc89](https://linux-hardware.org/?probe=aa355fcc89) | Nov 02, 2023 |
| Toshiba       | Satellite Pro L770-12Q      | Notebook    | [bd3567b828](https://linux-hardware.org/?probe=bd3567b828) | Nov 02, 2023 |
| HP            | ProBook 6450b               | Notebook    | [75ad2cf5f8](https://linux-hardware.org/?probe=75ad2cf5f8) | Nov 02, 2023 |
| Dell          | Latitude E6520              | Notebook    | [a0e05f5040](https://linux-hardware.org/?probe=a0e05f5040) | Nov 02, 2023 |
| Dell          | 0VHWTR A01                  | Desktop     | [b5c8e35523](https://linux-hardware.org/?probe=b5c8e35523) | Nov 02, 2023 |
| Lenovo        | 314D SDK0J40697 WIN 3305... | Mini pc     | [e74d5a77e4](https://linux-hardware.org/?probe=e74d5a77e4) | Nov 02, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [9a5c45e54b](https://linux-hardware.org/?probe=9a5c45e54b) | Nov 02, 2023 |
| Acer          | Predator PH717-71           | Notebook    | [a72ab29450](https://linux-hardware.org/?probe=a72ab29450) | Nov 02, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fc6336fedd](https://linux-hardware.org/?probe=fc6336fedd) | Nov 02, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [43a85c50bf](https://linux-hardware.org/?probe=43a85c50bf) | Nov 02, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [9493bec7e6](https://linux-hardware.org/?probe=9493bec7e6) | Nov 02, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [741bcd1343](https://linux-hardware.org/?probe=741bcd1343) | Nov 02, 2023 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [ea92d94742](https://linux-hardware.org/?probe=ea92d94742) | Nov 02, 2023 |
| Acer          | AO722                       | Notebook    | [3464dc7b3c](https://linux-hardware.org/?probe=3464dc7b3c) | Nov 02, 2023 |
| HP            | ProBook 4330s               | Notebook    | [0d3ba579b4](https://linux-hardware.org/?probe=0d3ba579b4) | Nov 02, 2023 |
| HUAWEI        | KPL-W0X                     | Notebook    | [9cdd815382](https://linux-hardware.org/?probe=9cdd815382) | Nov 02, 2023 |
| Lenovo        | ThinkPad T400 2768BB1       | Notebook    | [56bbf7c0bb](https://linux-hardware.org/?probe=56bbf7c0bb) | Nov 02, 2023 |
| Framework     | Laptop (12th Gen Intel C... | Notebook    | [7c06ac2664](https://linux-hardware.org/?probe=7c06ac2664) | Nov 02, 2023 |
| Lenovo        | Unknown                     | Notebook    | [3b5aa652dc](https://linux-hardware.org/?probe=3b5aa652dc) | Nov 02, 2023 |
| ASUSTek       | A88XM-E                     | Desktop     | [b828019cc1](https://linux-hardware.org/?probe=b828019cc1) | Nov 02, 2023 |
| Lenovo        | Unknown                     | Notebook    | [da6aff8db2](https://linux-hardware.org/?probe=da6aff8db2) | Nov 02, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS        | Desktop     | [99b1ce4372](https://linux-hardware.org/?probe=99b1ce4372) | Nov 02, 2023 |
| Lenovo        | G580                        | Notebook    | [d137c3bc30](https://linux-hardware.org/?probe=d137c3bc30) | Nov 02, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [3b14b40bc9](https://linux-hardware.org/?probe=3b14b40bc9) | Nov 02, 2023 |
| Dell          | Vostro 14-3468              | Notebook    | [33a984f9f8](https://linux-hardware.org/?probe=33a984f9f8) | Nov 02, 2023 |
| Lenovo        | 31A7 SDK0K17763 WIN 1801... | Mini pc     | [4291eb9ffb](https://linux-hardware.org/?probe=4291eb9ffb) | Nov 02, 2023 |
| Lenovo        | 31A7 SDK0K17763 WIN 1801... | Mini pc     | [b616f22a15](https://linux-hardware.org/?probe=b616f22a15) | Nov 02, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [b724ede64d](https://linux-hardware.org/?probe=b724ede64d) | Nov 02, 2023 |
| Dell          | Precision 7740              | Notebook    | [71b262696a](https://linux-hardware.org/?probe=71b262696a) | Nov 02, 2023 |
| HP            | 0B54h D                     | Desktop     | [4ec7776a76](https://linux-hardware.org/?probe=4ec7776a76) | Nov 02, 2023 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [1a0272a4ca](https://linux-hardware.org/?probe=1a0272a4ca) | Nov 02, 2023 |
| Lenovo        | ThinkPad L540 20AUS0YU00    | Notebook    | [16b302d74a](https://linux-hardware.org/?probe=16b302d74a) | Nov 02, 2023 |
| MSI           | Prestige 14Evo A11M         | Notebook    | [12414485a5](https://linux-hardware.org/?probe=12414485a5) | Nov 02, 2023 |
| ASUSTek       | T100TAF                     | Notebook    | [ea9f809740](https://linux-hardware.org/?probe=ea9f809740) | Nov 02, 2023 |
| Dell          | 0200DY A02                  | Desktop     | [f07206a75c](https://linux-hardware.org/?probe=f07206a75c) | Nov 02, 2023 |
| HP            | ProBook 6450b               | Notebook    | [a63f28d2be](https://linux-hardware.org/?probe=a63f28d2be) | Nov 02, 2023 |
| Gigabyte      | Z370 HD3P-CF                | Desktop     | [8ce1afee32](https://linux-hardware.org/?probe=8ce1afee32) | Nov 02, 2023 |
| HP            | EliteBook 830 G5            | Notebook    | [8ab22982cc](https://linux-hardware.org/?probe=8ab22982cc) | Nov 02, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [8ee912a147](https://linux-hardware.org/?probe=8ee912a147) | Nov 02, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [d48f7514df](https://linux-hardware.org/?probe=d48f7514df) | Nov 02, 2023 |
| MSI           | X370 SLI PLUS               | Desktop     | [98208c406a](https://linux-hardware.org/?probe=98208c406a) | Nov 02, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [c5e282cbad](https://linux-hardware.org/?probe=c5e282cbad) | Nov 02, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [b2c5bb3ed9](https://linux-hardware.org/?probe=b2c5bb3ed9) | Nov 02, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [54a7f5d1fa](https://linux-hardware.org/?probe=54a7f5d1fa) | Nov 02, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [175020104d](https://linux-hardware.org/?probe=175020104d) | Nov 02, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [97348209dd](https://linux-hardware.org/?probe=97348209dd) | Nov 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [26b7407b02](https://linux-hardware.org/?probe=26b7407b02) | Nov 02, 2023 |
| ASUSTek       | ROG STRIX B365-G GAMING     | Desktop     | [89a9c53f3a](https://linux-hardware.org/?probe=89a9c53f3a) | Nov 02, 2023 |
| Dell          | Inspiron 1750               | Notebook    | [0250d0fe82](https://linux-hardware.org/?probe=0250d0fe82) | Nov 02, 2023 |
| 3Logic Gro... | Graviton N15i               | Notebook    | [555d634638](https://linux-hardware.org/?probe=555d634638) | Nov 02, 2023 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [68dd4f08d9](https://linux-hardware.org/?probe=68dd4f08d9) | Nov 02, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [b84c515650](https://linux-hardware.org/?probe=b84c515650) | Nov 02, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [7d93bb6f25](https://linux-hardware.org/?probe=7d93bb6f25) | Nov 02, 2023 |
| Dell          | Inspiron 1750               | Notebook    | [39bb893e18](https://linux-hardware.org/?probe=39bb893e18) | Nov 02, 2023 |
| Dell          | Latitude E6530              | Notebook    | [878bc8ec66](https://linux-hardware.org/?probe=878bc8ec66) | Nov 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [b0c996ac38](https://linux-hardware.org/?probe=b0c996ac38) | Nov 02, 2023 |
| Google        | Akemi                       | Notebook    | [20ec65943c](https://linux-hardware.org/?probe=20ec65943c) | Nov 02, 2023 |

...


System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 25493     | 10.43%  |
| Ubuntu 18.04       | 13161     | 5.38%   |
| Ubuntu 22.04       | 12544     | 5.13%   |
| Debian 11          | 6726      | 2.75%   |
| OpenMandriva 4.2   | 4679      | 1.91%   |
| OpenMandriva 4.3   | 4616      | 1.89%   |
| ROSA R10           | 4390      | 1.8%    |
| Arch Rolling       | 4325      | 1.77%   |
| ROSA R11           | 4120      | 1.69%   |
| Zorin 16           | 3642      | 1.49%   |
| ROSA R8            | 3637      | 1.49%   |
| Pop!_OS 22.04      | 3588      | 1.47%   |
| ROSA R6            | 3496      | 1.43%   |
| ROSA R7            | 3301      | 1.35%   |
| Linux Mint 20.3    | 3169      | 1.3%    |
| Manjaro            | 3071      | 1.26%   |
| Arch               | 2982      | 1.22%   |
| BlackPanther 18.1  | 2931      | 1.2%    |
| KDE neon 20.04     | 2866      | 1.17%   |
| ROSA R8.1          | 2853      | 1.17%   |
| Fedora 38          | 2826      | 1.16%   |
| Linux Mint 21.1    | 2690      | 1.1%    |
| ROSA R9            | 2549      | 1.04%   |
| Linux Mint 20.2    | 2427      | 0.99%   |
| ROSA R11.1         | 2330      | 0.95%   |
| Linux Mint 20.1    | 2262      | 0.93%   |
| Ubuntu 20.10       | 2227      | 0.91%   |
| Linux Mint 19.3    | 2199      | 0.9%    |
| Fedora 36          | 2142      | 0.88%   |
| Pop!_OS 20.04      | 2129      | 0.87%   |
| ArcoLinux Rolling  | 2112      | 0.86%   |
| Ubuntu 21.10       | 2091      | 0.86%   |
| Ubuntu 19.10       | 2056      | 0.84%   |
| Fedora 37          | 2035      | 0.83%   |
| Linux Mint 20      | 2026      | 0.83%   |
| ROSA 12.2          | 2009      | 0.82%   |
| Xubuntu 20.04      | 1993      | 0.82%   |
| OpenMandriva 23.01 | 1989      | 0.81%   |
| Debian 12          | 1928      | 0.79%   |
| OpenMandriva 23.03 | 1911      | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 63153     | 27.87%  |
| ROSA          | 26647     | 11.76%  |
| Linux Mint    | 18416     | 8.13%   |
| OpenMandriva  | 15184     | 6.7%    |
| Fedora        | 13096     | 5.78%   |
| Debian        | 11466     | 5.06%   |
| Pop!_OS       | 9827      | 4.34%   |
| Arch          | 7139      | 3.15%   |
| Manjaro       | 7115      | 3.14%   |
| Zorin         | 5462      | 2.41%   |
| Kubuntu       | 4263      | 1.88%   |
| Xubuntu       | 4256      | 1.88%   |
| KDE neon      | 4107      | 1.81%   |
| Endless       | 3484      | 1.54%   |
| BlackPanther  | 3167      | 1.4%    |
| openSUSE      | 2424      | 1.07%   |
| ArcoLinux     | 2285      | 1.01%   |
| Kali          | 1757      | 0.78%   |
| Elementary    | 1685      | 0.74%   |
| Gentoo        | 1593      | 0.7%    |
| Ubuntu MATE   | 1455      | 0.64%   |
| Lubuntu       | 1363      | 0.6%    |
| SteamOS       | 1186      | 0.52%   |
| EndeavourOS   | 1184      | 0.52%   |
| Ubuntu Unity  | 1167      | 0.51%   |
| LMDE          | 901       | 0.4%    |
| Clear Linux   | 870       | 0.38%   |
| CentOS        | 732       | 0.32%   |
| MX            | 686       | 0.3%    |
| Ubuntu Budgie | 665       | 0.29%   |
| Nobara        | 651       | 0.29%   |
| ALT Linux     | 618       | 0.27%   |
| Garuda Linux  | 538       | 0.24%   |
| Parrot        | 526       | 0.23%   |
| Xero          | 352       | 0.16%   |
| Red OS        | 324       | 0.14%   |
| Peppermint    | 303       | 0.13%   |
| Raspbian      | 300       | 0.13%   |
| RHEL          | 292       | 0.13%   |
| NixOS         | 236       | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002           | 4509      | 1.67%   |
| 5.16.7-desktop-1omv4003            | 4319      | 1.6%    |
| 5.4.0-42-generic                   | 3815      | 1.42%   |
| 4.18.16-desktop-1bP                | 2179      | 0.81%   |
| 5.15.0-56-generic                  | 2168      | 0.8%    |
| 4.9.60-nrj-desktop-1rosa-x86_64    | 2054      | 0.76%   |
| 3.14.44-nrj-desktop-2rosa-x86_64   | 1868      | 0.69%   |
| 6.2.6-desktop-1omv2390             | 1847      | 0.69%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 1840      | 0.68%   |
| 6.1.1-desktop-1omv2290             | 1822      | 0.68%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 1803      | 0.67%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 1784      | 0.66%   |
| 5.4.0-58-generic                   | 1738      | 0.64%   |
| 4.1.25-nrj-desktop-1rosa-x86_64    | 1602      | 0.59%   |
| 5.4.0-48-generic                   | 1532      | 0.57%   |
| 5.4.0-52-generic                   | 1522      | 0.56%   |
| 5.15.0-58-generic                  | 1512      | 0.56%   |
| 5.15.0-52-generic                  | 1465      | 0.54%   |
| 4.1.15-nrj-desktop-1rosa-x86_64    | 1381      | 0.51%   |
| 5.4.0-26-generic                   | 1341      | 0.5%    |
| 5.15.0-46-generic                  | 1222      | 0.45%   |
| 5.3.0-28-generic                   | 1137      | 0.42%   |
| 5.4.0-29-generic                   | 1125      | 0.42%   |
| 5.4.0-40-generic                   | 1101      | 0.41%   |
| 5.3.0-40-generic                   | 1090      | 0.4%    |
| 5.11.0-27-generic                  | 1075      | 0.4%    |
| 5.15.0-48-generic                  | 1070      | 0.4%    |
| 5.10.0-8-amd64                     | 1010      | 0.37%   |
| 5.3.0-46-generic                   | 998       | 0.37%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 972       | 0.36%   |
| 5.19.0-35-generic                  | 951       | 0.35%   |
| 5.4.0-54-generic                   | 950       | 0.35%   |
| 5.4.0-91-generic                   | 947       | 0.35%   |
| 5.8.0-43-generic                   | 940       | 0.35%   |
| 5.11.0-38-generic                  | 928       | 0.34%   |
| 5.11.0-37-generic                  | 927       | 0.34%   |
| 5.4.0-37-generic                   | 923       | 0.34%   |
| 6.2.0-26-generic                   | 916       | 0.34%   |
| 5.4.0-65-generic                   | 914       | 0.34%   |
| 5.6.14-desktop-2bP                 | 896       | 0.33%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 33344     | 13.1%   |
| 5.15.0  | 19332     | 7.6%    |
| 4.15.0  | 14446     | 5.68%   |
| 5.8.0   | 10673     | 4.19%   |
| 5.11.0  | 10320     | 4.05%   |
| 5.13.0  | 9346      | 3.67%   |
| 5.3.0   | 7859      | 3.09%   |
| 5.10.0  | 7460      | 2.93%   |
| 5.19.0  | 7094      | 2.79%   |
| 5.0.0   | 5262      | 2.07%   |
| 6.2.0   | 4766      | 1.87%   |
| 5.10.14 | 4561      | 1.79%   |
| 5.16.7  | 4386      | 1.72%   |
| 4.18.0  | 3995      | 1.57%   |
| 6.2.6   | 2831      | 1.11%   |
| 6.1.0   | 2700      | 1.06%   |
| 3.14.44 | 2697      | 1.06%   |
| 4.9.60  | 2596      | 1.02%   |
| 4.9.20  | 2584      | 1.02%   |
| 4.18.16 | 2235      | 0.88%   |
| 4.1.25  | 2174      | 0.85%   |
| 6.1.1   | 2088      | 0.82%   |
| 4.19.0  | 1987      | 0.78%   |
| 5.10.74 | 1848      | 0.73%   |
| 4.1.15  | 1836      | 0.72%   |
| 4.1.34  | 1350      | 0.53%   |
| 4.1.38  | 1111      | 0.44%   |
| 6.4.11  | 1096      | 0.43%   |
| 4.9.9   | 1003      | 0.39%   |
| 5.6.14  | 1000      | 0.39%   |
| 4.9.124 | 995       | 0.39%   |
| 5.14.0  | 925       | 0.36%   |
| 5.17.5  | 860       | 0.34%   |
| 6.0.12  | 789       | 0.31%   |
| 6.0.0   | 777       | 0.31%   |
| 4.9.155 | 691       | 0.27%   |
| 4.9.76  | 648       | 0.25%   |
| 4.1.16  | 633       | 0.25%   |
| 4.9.41  | 627       | 0.25%   |
| 6.1.20  | 620       | 0.24%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 36802     | 14.85%  |
| 5.15    | 25685     | 10.36%  |
| 5.10    | 17988     | 7.26%   |
| 4.15    | 14519     | 5.86%   |
| 5.8     | 12961     | 5.23%   |
| 5.11    | 12254     | 4.94%   |
| 5.13    | 10995     | 4.44%   |
| 6.2     | 10249     | 4.14%   |
| 6.1     | 9292      | 3.75%   |
| 4.9     | 9285      | 3.75%   |
| 5.19    | 9245      | 3.73%   |
| 5.3     | 8873      | 3.58%   |
| 4.1     | 7578      | 3.06%   |
| 5.16    | 7373      | 2.98%   |
| 4.18    | 6333      | 2.56%   |
| 5.0     | 5581      | 2.25%   |
| 6.0     | 4284      | 1.73%   |
| 6.4     | 4008      | 1.62%   |
| 3.14    | 3554      | 1.43%   |
| 5.17    | 2933      | 1.18%   |
| 5.18    | 2917      | 1.18%   |
| 5.14    | 2867      | 1.16%   |
| 6.5     | 2864      | 1.16%   |
| 5.6     | 2777      | 1.12%   |
| 6.3     | 2651      | 1.07%   |
| 4.19    | 2602      | 1.05%   |
| 5.9     | 2355      | 0.95%   |
| 5.12    | 1893      | 0.76%   |
| 5.7     | 1639      | 0.66%   |
| 5.5     | 985       | 0.4%    |
| 4.4     | 859       | 0.35%   |
| 3.10    | 620       | 0.25%   |
| 4.13    | 406       | 0.16%   |
| 5.2     | 400       | 0.16%   |
| 5.1     | 390       | 0.16%   |
| 4.14    | 233       | 0.09%   |
| 4.12    | 188       | 0.08%   |
| 4.16    | 173       | 0.07%   |
| 4.10    | 159       | 0.06%   |
| 4.8     | 140       | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| x86_64      | 206367    | 94.36%  |
| i686        | 10265     | 4.69%   |
| aarch64     | 1479      | 0.68%   |
| armv7l      | 423       | 0.19%   |
| armv8l      | 40        | 0.02%   |
| armv6l      | 40        | 0.02%   |
| riscv64     | 24        | 0.01%   |
| ppc64       | 10        | 0.005%  |
| ppc         | 9         | 0.004%  |
| Unknown     | 7         | 0.003%  |
| i586        | 6         | 0.003%  |
| ppc64le     | 5         | 0.002%  |
| loongarch64 | 5         | 0.002%  |
| e2k         | 5         | 0.002%  |
| mips64      | 4         | 0.002%  |
| mips        | 2         | 0.001%  |
| armv5tel    | 2         | 0.001%  |
| unknow      | 1         | 0.0005% |
| sparc64     | 1         | 0.0005% |
| sh4a        | 1         | 0.0005% |
| s390x       | 1         | 0.0005% |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 88062     | 38.38%  |
| KDE5             | 44027     | 19.19%  |
| Unknown          | 24737     | 10.78%  |
| KDE4             | 18349     | 8%      |
| XFCE             | 14609     | 6.37%   |
| X-Cinnamon       | 13898     | 6.06%   |
| MATE             | 5860      | 2.55%   |
| KDE              | 4566      | 1.99%   |
| LXQt             | 2790      | 1.22%   |
| Cinnamon         | 2688      | 1.17%   |
| Pantheon         | 1609      | 0.7%    |
| Unity            | 1194      | 0.52%   |
| LXDE             | 1181      | 0.51%   |
| i3               | 1105      | 0.48%   |
| Budgie           | 1064      | 0.46%   |
| GNOME Flashback  | 549       | 0.24%   |
| Deepin           | 527       | 0.23%   |
| GNOME Classic    | 270       | 0.12%   |
| sway             | 248       | 0.11%   |
| awesome          | 231       | 0.1%    |
| Openbox          | 222       | 0.1%    |
| Hyprland         | 202       | 0.09%   |
| GNUstep          | 169       | 0.07%   |
| bspwm            | 153       | 0.07%   |
| lightdm-xsession | 123       | 0.05%   |
| DWM              | 118       | 0.05%   |
| qtile            | 115       | 0.05%   |
| Trinity          | 79        | 0.03%   |
| xmonad           | 78        | 0.03%   |
| Enlightenment    | 77        | 0.03%   |
| icewm            | 70        | 0.03%   |
| LeftWM           | 45        | 0.02%   |
| i3-with-shmlog   | 27        | 0.01%   |
| BunsenLabs       | 26        | 0.01%   |
| UKUI             | 23        | 0.01%   |
| fluxbox          | 22        | 0.01%   |
| chadwm           | 22        | 0.01%   |
| herbstluftwm     | 18        | 0.01%   |
| fly              | 18        | 0.01%   |
| Cutefish         | 13        | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 170709    | 75.87%  |
| Wayland     | 36255     | 16.11%  |
| Unknown     | 13483     | 5.99%   |
| Tty         | 4508      | 2%      |
| Web         | 30        | 0.01%   |
| Unspecified | 11        | 0.005%  |
| Xcb         | 1         | 0.0004% |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 98306     | 43.05%  |
| SDDM    | 39568     | 17.33%  |
| GDM     | 23502     | 10.29%  |
| GDM3    | 22290     | 9.76%   |
| LightDM | 19040     | 8.34%   |
| KDM     | 18480     | 8.09%   |
| TDM     | 6023      | 2.64%   |
| XDM     | 372       | 0.16%   |
| SLiM    | 239       | 0.1%    |
| LXDM    | 182       | 0.08%   |
| Ly      | 101       | 0.04%   |
| MDM     | 88        | 0.04%   |
| GREETD  | 59        | 0.03%   |
| NODM    | 35        | 0.02%   |
| FLY-DM  | 17        | 0.01%   |
| LY-DM   | 16        | 0.01%   |
| SLIMSKI | 12        | 0.01%   |
| EMPTTY  | 6         | 0.003%  |
| WDM     | 5         | 0.002%  |
| LDM     | 3         | 0.001%  |
| SU      | 2         | 0.001%  |
| XINIT   | 1         | 0.0004% |
| LYNDE   | 1         | 0.0004% |
| LEMURS  | 1         | 0.0004% |
| CDM     | 1         | 0.0004% |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 77074     | 34.37%  |
| Unknown | 42825     | 19.1%   |
| de_DE   | 14521     | 6.48%   |
| ru_RU   | 13877     | 6.19%   |
| en_GB   | 9498      | 4.24%   |
| pt_BR   | 9148      | 4.08%   |
| fr_FR   | 8063      | 3.6%    |
| it_IT   | 5294      | 2.36%   |
| es_ES   | 4220      | 1.88%   |
| C       | 3681      | 1.64%   |
| en_CA   | 3493      | 1.56%   |
| pl_PL   | 3141      | 1.4%    |
| en_IN   | 2960      | 1.32%   |
| en_AU   | 2659      | 1.19%   |
| es_MX   | 1480      | 0.66%   |
| nl_NL   | 1356      | 0.6%    |
| cs_CZ   | 1196      | 0.53%   |
| es_AR   | 1126      | 0.5%    |
| hu_HU   | 1050      | 0.47%   |
| zh_CN   | 876       | 0.39%   |
| pt_PT   | 808       | 0.36%   |
| de_AT   | 797       | 0.36%   |
| en_ZA   | 765       | 0.34%   |
| tr_TR   | 751       | 0.33%   |
| sv_SE   | 642       | 0.29%   |
| ja_JP   | 578       | 0.26%   |
| de_CH   | 575       | 0.26%   |
| ru_UA   | 531       | 0.24%   |
| es_CL   | 525       | 0.23%   |
| es_CO   | 521       | 0.23%   |
| fi_FI   | 495       | 0.22%   |
| en_NZ   | 491       | 0.22%   |
| en_IE   | 448       | 0.2%    |
| fr_CA   | 439       | 0.2%    |
| fr_BE   | 375       | 0.17%   |
| el_GR   | 371       | 0.17%   |
| ro_RO   | 363       | 0.16%   |
| nl_BE   | 330       | 0.15%   |
| da_DK   | 313       | 0.14%   |
| en_PH   | 297       | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 119954    | 53.67%  |
| EFI  | 103539    | 46.33%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type                | Computers | Percent |
|---------------------|-----------|---------|
| Ext4                | 155290    | 68.71%  |
| Unknown             | 21448     | 9.49%   |
| Btrfs               | 19481     | 8.62%   |
| Overlay             | 19263     | 8.52%   |
| Tmpfs               | 4532      | 2.01%   |
| Xfs                 | 2962      | 1.31%   |
| Zfs                 | 1496      | 0.66%   |
| Ext2                | 510       | 0.23%   |
| Ext3                | 417       | 0.18%   |
| F2fs                | 315       | 0.14%   |
| Aufs                | 81        | 0.04%   |
| Reiserfs            | 52        | 0.02%   |
| Jfs                 | 42        | 0.02%   |
| Rootfs              | 27        | 0.01%   |
| XXXXXXX             | 25        | 0.01%   |
| XXXXX               | 8         | 0.004%  |
| XXX4                | 7         | 0.003%  |
| SAMSUNG             | 6         | 0.003%  |
| Fuse.fuse-overlayfs | 5         | 0.002%  |
| XXXX                | 4         | 0.002%  |
| ExX4                | 3         | 0.001%  |
| XXXfs               | 2         | 0.001%  |
| XXX                 | 2         | 0.001%  |
| Ubifs               | 2         | 0.001%  |
| Ntfs                | 2         | 0.001%  |
| Xtrfs               | 1         | 0.0004% |
| Ufs                 | 1         | 0.0004% |
| SquXshfs            | 1         | 0.0004% |
| SquasXfs            | 1         | 0.0004% |
| OveXlay             | 1         | 0.0004% |
| Nilfs2              | 1         | 0.0004% |
| Nfs                 | 1         | 0.0004% |
| Lvm                 | 1         | 0.0004% |
| Fuse.sshfs          | 1         | 0.0004% |
| Fuse.snapfuse       | 1         | 0.0004% |
| Exfat               | 1         | 0.0004% |
| Bcachefs            | 1         | 0.0004% |
| 2G                  | 1         | 0.0004% |
| 20G                 | 1         | 0.0004% |
| 12G                 | 1         | 0.0004% |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 104419    | 46.29%  |
| GPT     | 81849     | 36.28%  |
| MBR     | 39332     | 17.43%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 190062    | 85.1%   |
| Yes       | 33277     | 14.9%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 158729    | 71.1%   |
| Yes       | 64530     | 28.9%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 38029     | 17.45%  |
| Lenovo                  | 28581     | 13.12%  |
| Hewlett-Packard         | 27992     | 12.85%  |
| Dell                    | 25494     | 11.7%   |
| Gigabyte Technology     | 15607     | 7.16%   |
| Acer                    | 13058     | 5.99%   |
| MSI                     | 12396     | 5.69%   |
| ASRock                  | 8059      | 3.7%    |
| Apple                   | 5095      | 2.34%   |
| Intel                   | 3839      | 1.76%   |
| Toshiba                 | 3439      | 1.58%   |
| Samsung Electronics     | 3110      | 1.43%   |
| Unknown                 | 2169      | 1%      |
| Sony                    | 1811      | 0.83%   |
| Fujitsu                 | 1603      | 0.74%   |
| HUAWEI                  | 1268      | 0.58%   |
| Raspberry Pi Foundation | 1209      | 0.55%   |
| Valve                   | 992       | 0.46%   |
| Medion                  | 987       | 0.45%   |
| Pegatron                | 955       | 0.44%   |
| Google                  | 924       | 0.42%   |
| Packard Bell            | 884       | 0.41%   |
| Foxconn                 | 856       | 0.39%   |
| Biostar                 | 849       | 0.39%   |
| ECS                     | 839       | 0.39%   |
| Supermicro              | 837       | 0.38%   |
| Positivo                | 784       | 0.36%   |
| Notebook                | 742       | 0.34%   |
| Microsoft               | 683       | 0.31%   |
| Fujitsu Siemens         | 615       | 0.28%   |
| Alienware               | 556       | 0.26%   |
| eMachines               | 465       | 0.21%   |
| Timi                    | 442       | 0.2%    |
| System76                | 416       | 0.19%   |
| TUXEDO                  | 377       | 0.17%   |
| AZW                     | 375       | 0.17%   |
| AMI                     | 368       | 0.17%   |
| LG Electronics          | 332       | 0.15%   |
| Clevo                   | 329       | 0.15%   |
| Gateway                 | 327       | 0.15%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Unknown                      | 2903      | 1.33%   |
| ASUS All Series              | 2116      | 0.97%   |
| Valve Jupiter                | 992       | 0.46%   |
| HP Notebook                  | 791       | 0.36%   |
| HP Pavilion g6               | 544       | 0.25%   |
| HP Pavilion dv6              | 523       | 0.24%   |
| Dell OptiPlex 7010           | 430       | 0.2%    |
| Apple MacBook5,2             | 384       | 0.18%   |
| ASUS TUF Gaming X570-PLUS    | 381       | 0.17%   |
| MSI MS-7C37                  | 378       | 0.17%   |
| RPi Raspberry Pi             | 371       | 0.17%   |
| MSI MS-7C02                  | 335       | 0.15%   |
| Gigabyte B450M DS3H          | 335       | 0.15%   |
| HP Pavilion 15               | 332       | 0.15%   |
| HP Pavilion dv7              | 331       | 0.15%   |
| ASUS PRIME A320M-K           | 314       | 0.14%   |
| HP Pavilion Notebook         | 310       | 0.14%   |
| Dell OptiPlex 9020           | 307       | 0.14%   |
| MSI MS-7817                  | 303       | 0.14%   |
| Gigabyte 970A-DS3P           | 274       | 0.13%   |
| MSI MS-7B86                  | 267       | 0.12%   |
| Dell Latitude E6420          | 265       | 0.12%   |
| Apple MacBookPro9,2          | 262       | 0.12%   |
| Dell OptiPlex 780            | 248       | 0.11%   |
| HP 15                        | 244       | 0.11%   |
| Dell OptiPlex 790            | 241       | 0.11%   |
| Apple MacBookAir7,2          | 240       | 0.11%   |
| ASUS M5A78L-M/USB3           | 237       | 0.11%   |
| Dell Latitude E6430          | 235       | 0.11%   |
| Apple MacBookPro8,1          | 233       | 0.11%   |
| MSI MS-7721                  | 231       | 0.11%   |
| Dell Latitude E6410          | 230       | 0.11%   |
| ASUS M5A97 R2.0              | 228       | 0.1%    |
| MSI MS-7693                  | 226       | 0.1%    |
| MSI MS-7C91                  | 218       | 0.1%    |
| MSI MS-7A38                  | 218       | 0.1%    |
| Dell OptiPlex 3020           | 214       | 0.1%    |
| Acer Nitro AN515-54          | 214       | 0.1%    |
| MSI MS-7B79                  | 210       | 0.1%    |
| ASUS ROG STRIX B550-F GAMING | 210       | 0.1%    |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Lenovo ThinkPad       | 12010     | 5.51%   |
| Acer Aspire           | 8692      | 3.99%   |
| Dell Inspiron         | 6779      | 3.11%   |
| Dell Latitude         | 6325      | 2.9%    |
| Lenovo IdeaPad        | 5735      | 2.63%   |
| HP Pavilion           | 5242      | 2.41%   |
| Dell OptiPlex         | 3744      | 1.72%   |
| ASUS PRIME            | 3704      | 1.7%    |
| HP EliteBook          | 3314      | 1.52%   |
| ASUS ROG              | 3273      | 1.5%    |
| HP Compaq             | 2931      | 1.35%   |
| Unknown               | 2903      | 1.33%   |
| Toshiba Satellite     | 2879      | 1.32%   |
| Dell XPS              | 2757      | 1.27%   |
| ASUS VivoBook         | 2683      | 1.23%   |
| HP ProBook            | 2651      | 1.22%   |
| HP Laptop             | 2645      | 1.21%   |
| Dell Precision        | 2272      | 1.04%   |
| ASUS All              | 2116      | 0.97%   |
| ASUS TUF              | 1945      | 0.89%   |
| Lenovo ThinkCentre    | 1732      | 0.79%   |
| Dell Vostro           | 1516      | 0.7%    |
| HP ENVY               | 1313      | 0.6%    |
| RPi Raspberry         | 1207      | 0.55%   |
| Lenovo Yoga           | 1145      | 0.53%   |
| Acer Nitro            | 1014      | 0.47%   |
| Valve Jupiter         | 992       | 0.46%   |
| Lenovo Legion         | 976       | 0.45%   |
| HP Notebook           | 794       | 0.36%   |
| ASUS ZenBook          | 794       | 0.36%   |
| ASUS M5A78L-M         | 748       | 0.34%   |
| Acer Swift            | 732       | 0.34%   |
| HP EliteDesk          | 695       | 0.32%   |
| Fujitsu LIFEBOOK      | 694       | 0.32%   |
| Microsoft Surface     | 683       | 0.31%   |
| Gigabyte X570         | 659       | 0.3%    |
| HP ZBook              | 637       | 0.29%   |
| Packard Bell EasyNote | 619       | 0.28%   |
| ASUS ASUS             | 613       | 0.28%   |
| Gigabyte B450M        | 610       | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 18836     | 8.64%   |
| 2012    | 18723     | 8.59%   |
| 2019    | 17872     | 8.2%    |
| 2020    | 17039     | 7.82%   |
| 2011    | 16798     | 7.71%   |
| 2013    | 15356     | 7.05%   |
| 2017    | 13484     | 6.19%   |
| 2021    | 12899     | 5.92%   |
| 2014    | 12359     | 5.67%   |
| 2010    | 12201     | 5.6%    |
| 2015    | 10733     | 4.93%   |
| 2016    | 10368     | 4.76%   |
| 2009    | 10061     | 4.62%   |
| 2008    | 9195      | 4.22%   |
| 2022    | 7444      | 3.42%   |
| 2007    | 6388      | 2.93%   |
| 2006    | 2958      | 1.36%   |
| Unknown | 1866      | 0.86%   |
| 2023    | 1665      | 0.76%   |
| 2005    | 1081      | 0.5%    |
| 2004    | 323       | 0.15%   |
| 2003    | 172       | 0.08%   |
| 2002    | 44        | 0.02%   |
| 2001    | 20        | 0.01%   |
| 2000    | 10        | 0.005%  |
| 1999    | 3         | 0.001%  |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 117099    | 53.74%  |
| Desktop        | 84858     | 38.94%  |
| Convertible    | 4716      | 2.16%   |
| Mini pc        | 2940      | 1.35%   |
| All in one     | 2743      | 1.26%   |
| Server         | 1932      | 0.89%   |
| Tablet         | 1739      | 0.8%    |
| System on chip | 1710      | 0.78%   |
| Phone          | 133       | 0.06%   |
| Stick pc       | 16        | 0.01%   |
| Other          | 7         | 0.003%  |
| Firewall       | 5         | 0.002%  |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 204461    | 93.16%  |
| Enabled  | 15018     | 6.84%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 216589    | 99.4%   |
| Yes  | 1317      | 0.6%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 49185     | 22.04%  |
| 3.01-4.0        | 45800     | 20.52%  |
| 16.01-24.0      | 39943     | 17.9%   |
| 8.01-16.0       | 39462     | 17.68%  |
| 32.01-64.0      | 18962     | 8.5%    |
| 1.01-2.0        | 11841     | 5.31%   |
| 64.01-256.0     | 5820      | 2.61%   |
| 2.01-3.0        | 5509      | 2.47%   |
| 24.01-32.0      | 3499      | 1.57%   |
| 0.51-1.0        | 2075      | 0.93%   |
| Unknown         | 436       | 0.2%    |
| More than 256.0 | 411       | 0.18%   |
| 0.01-0.5        | 220       | 0.1%    |
| 0               | 1         | 0.0004% |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 85944     | 35.02%  |
| 2.01-3.0        | 55550     | 22.64%  |
| 4.01-8.0        | 31456     | 12.82%  |
| 3.01-4.0        | 28097     | 11.45%  |
| 0.51-1.0        | 27955     | 11.39%  |
| 8.01-16.0       | 8852      | 3.61%   |
| 0.01-0.5        | 4494      | 1.83%   |
| 16.01-24.0      | 1348      | 0.55%   |
| Unknown         | 639       | 0.26%   |
| 24.01-32.0      | 493       | 0.2%    |
| 32.01-64.0      | 391       | 0.16%   |
| 64.01-256.0     | 145       | 0.06%   |
| More than 256.0 | 19        | 0.01%   |
| 0               | 10        | 0.004%  |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 136342    | 60.21%  |
| 2       | 55644     | 24.57%  |
| 3       | 17193     | 7.59%   |
| 4       | 7713      | 3.41%   |
| 5       | 3626      | 1.6%    |
| 0       | 2126      | 0.94%   |
| 6       | 1681      | 0.74%   |
| 7       | 817       | 0.36%   |
| 8       | 404       | 0.18%   |
| 9       | 241       | 0.11%   |
| 10      | 137       | 0.06%   |
| Unknown | 119       | 0.05%   |
| 11      | 108       | 0.05%   |
| 13      | 51        | 0.02%   |
| 12      | 50        | 0.02%   |
| 14      | 30        | 0.01%   |
| 17      | 18        | 0.01%   |
| 16      | 13        | 0.01%   |
| 18      | 12        | 0.01%   |
| 19      | 11        | 0.005%  |
| 15      | 10        | 0.004%  |
| 20      | 8         | 0.004%  |
| 27      | 7         | 0.003%  |
| 25      | 7         | 0.003%  |
| 21      | 7         | 0.003%  |
| 36      | 6         | 0.003%  |
| 28      | 6         | 0.003%  |
| 26      | 5         | 0.002%  |
| 24      | 5         | 0.002%  |
| 23      | 4         | 0.002%  |
| 22      | 4         | 0.002%  |
| 32      | 3         | 0.001%  |
| 97      | 2         | 0.001%  |
| 93      | 2         | 0.001%  |
| 29      | 2         | 0.001%  |
| 410     | 1         | 0.0004% |
| 209     | 1         | 0.0004% |
| 87      | 1         | 0.0004% |
| 79      | 1         | 0.0004% |
| 71      | 1         | 0.0004% |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 129783    | 58.89%  |
| Yes       | 90589     | 41.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 190018    | 86.95%  |
| No        | 28513     | 13.05%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 160970    | 73.28%  |
| No        | 58695     | 26.72%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 122863    | 55.58%  |
| No        | 98177     | 44.42%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 35326     | 16.01%  |
| Russia       | 26677     | 12.09%  |
| Germany      | 20688     | 9.38%   |
| Brazil       | 13328     | 6.04%   |
| France       | 9958      | 4.51%   |
| Unknown      | 8148      | 3.69%   |
| UK           | 7951      | 3.6%    |
| Italy        | 7927      | 3.59%   |
| Canada       | 5973      | 2.71%   |
| Spain        | 5675      | 2.57%   |
| Poland       | 5139      | 2.33%   |
| India        | 4647      | 2.11%   |
| Netherlands  | 4207      | 1.91%   |
| Hungary      | 3961      | 1.8%    |
| Australia    | 3454      | 1.57%   |
| Ukraine      | 3244      | 1.47%   |
| Mexico       | 2536      | 1.15%   |
| Switzerland  | 2266      | 1.03%   |
| Sweden       | 2175      | 0.99%   |
| Czechia      | 2160      | 0.98%   |
| Austria      | 1956      | 0.89%   |
| Argentina    | 1940      | 0.88%   |
| Belgium      | 1879      | 0.85%   |
| Turkey       | 1878      | 0.85%   |
| Romania      | 1838      | 0.83%   |
| Portugal     | 1616      | 0.73%   |
| Finland      | 1520      | 0.69%   |
| China        | 1479      | 0.67%   |
| Greece       | 1328      | 0.6%    |
| Indonesia    | 1325      | 0.6%    |
| Japan        | 1291      | 0.59%   |
| South Africa | 1116      | 0.51%   |
| Norway       | 1089      | 0.49%   |
| Colombia     | 1044      | 0.47%   |
| Bulgaria     | 1026      | 0.47%   |
| Belarus      | 1010      | 0.46%   |
| Denmark      | 986       | 0.45%   |
| Chile        | 960       | 0.44%   |
| Slovakia     | 803       | 0.36%   |
| Serbia       | 770       | 0.35%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 8198      | 3.46%   |
| Moscow            | 5663      | 2.39%   |
| St Petersburg     | 2307      | 0.97%   |
| Berlin            | 1887      | 0.8%    |
| Sao Paulo         | 1692      | 0.71%   |
| Budapest          | 1564      | 0.66%   |
| Paris             | 1537      | 0.65%   |
| Voronezh          | 1259      | 0.53%   |
| Warsaw            | 1192      | 0.5%    |
| Vienna            | 1144      | 0.48%   |
| Milan             | 1109      | 0.47%   |
| Sydney            | 973       | 0.41%   |
| Madrid            | 945       | 0.4%    |
| Munich            | 940       | 0.4%    |
| Rome              | 925       | 0.39%   |
| Hamburg           | 875       | 0.37%   |
| Prague            | 845       | 0.36%   |
| Bangor            | 842       | 0.36%   |
| Novosibirsk       | 840       | 0.35%   |
| Rio de Janeiro    | 826       | 0.35%   |
| Amsterdam         | 801       | 0.34%   |
| Melbourne         | 780       | 0.33%   |
| Kyiv              | 776       | 0.33%   |
| Pecherskoye       | 765       | 0.32%   |
| Krasnodar         | 732       | 0.31%   |
| Yekaterinburg     | 725       | 0.31%   |
| Athens            | 707       | 0.3%    |
| Istanbul          | 706       | 0.3%    |
| Helsinki          | 704       | 0.3%    |
| Frankfurt am Main | 696       | 0.29%   |
| Zurich            | 646       | 0.27%   |
| Barcelona         | 644       | 0.27%   |
| Toronto           | 619       | 0.26%   |
| Montreal          | 609       | 0.26%   |
| Bengaluru         | 593       | 0.25%   |
| London            | 587       | 0.25%   |
| Bucharest         | 587       | 0.25%   |
| Nizhniy Novgorod  | 540       | 0.23%   |
| Sofia             | 533       | 0.23%   |
| Mexico City       | 532       | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 50545     | 80372  | 15.93%  |
| Seagate                     | 49478     | 78162  | 15.59%  |
| Samsung Electronics         | 45861     | 71871  | 14.45%  |
| Toshiba                     | 21362     | 29257  | 6.73%   |
| Kingston                    | 17021     | 23172  | 5.36%   |
| SanDisk                     | 15390     | 20775  | 4.85%   |
| Unknown                     | 12746     | 17415  | 4.02%   |
| Hitachi                     | 11704     | 15941  | 3.69%   |
| Crucial                     | 10289     | 14520  | 3.24%   |
| Intel                       | 7457      | 10765  | 2.35%   |
| SK hynix                    | 6943      | 8820   | 2.19%   |
| HGST                        | 6057      | 8869   | 1.91%   |
| A-DATA Technology           | 4518      | 6035   | 1.42%   |
| Micron Technology           | 4223      | 5413   | 1.33%   |
| China                       | 2918      | 3809   | 0.92%   |
| Apple                       | 2282      | 2986   | 0.72%   |
| Phison                      | 2136      | 2917   | 0.67%   |
| SPCC                        | 1908      | 2569   | 0.6%    |
| KIOXIA                      | 1873      | 2378   | 0.59%   |
| Fujitsu                     | 1728      | 2194   | 0.54%   |
| PNY                         | 1649      | 2213   | 0.52%   |
| Maxtor                      | 1606      | 2134   | 0.51%   |
| OCZ                         | 1485      | 1954   | 0.47%   |
| Silicon Motion              | 1480      | 1968   | 0.47%   |
| Intenso                     | 1312      | 1782   | 0.41%   |
| Transcend                   | 1295      | 1669   | 0.41%   |
| Phison Electronics          | 1287      | 1699   | 0.41%   |
| Micron/Crucial Technology   | 1253      | 1685   | 0.39%   |
| Patriot                     | 1214      | 1622   | 0.38%   |
| LITEON                      | 1132      | 1382   | 0.36%   |
| Unknown                     | 1132      | 1313   | 0.36%   |
| Corsair                     | 1026      | 1390   | 0.32%   |
| JMicron Technology          | 930       | 1123   | 0.29%   |
| Kingston Technology Company | 916       | 1109   | 0.29%   |
| GOODRAM                     | 906       | 1301   | 0.29%   |
| Apacer                      | 810       | 1047   | 0.26%   |
| Hewlett-Packard             | 719       | 1208   | 0.23%   |
| Plextor                     | 685       | 974    | 0.22%   |
| Team                        | 681       | 892    | 0.21%   |
| KingSpec                    | 665       | 849    | 0.21%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 3478      | 0.99%   |
| Seagate ST1000LM035-1RK172 1TB                     | 2595      | 0.74%   |
| Seagate ST500DM002-1BD142 500GB                    | 2531      | 0.72%   |
| Samsung SSD 860 EVO 500GB                          | 2310      | 0.66%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 2238      | 0.64%   |
| Samsung SSD 850 EVO 250GB                          | 2139      | 0.61%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 2133      | 0.61%   |
| Unknown MMC Card  32GB                             | 2050      | 0.58%   |
| Kingston SA400S37120G 120GB SSD                    | 2045      | 0.58%   |
| Toshiba MQ01ABD100 1TB                             | 1948      | 0.56%   |
| Seagate ST1000DM010-2EP102 1TB                     | 1869      | 0.53%   |
| Kingston SA400S37480G 480GB SSD                    | 1808      | 0.52%   |
| Unknown MMC Card  64GB                             | 1727      | 0.49%   |
| Toshiba MQ01ABF050 500GB                           | 1691      | 0.48%   |
| Samsung SSD 850 EVO 500GB                          | 1683      | 0.48%   |
| Seagate ST500LT012-1DG142 500GB                    | 1602      | 0.46%   |
| Toshiba DT01ACA100 1TB                             | 1566      | 0.45%   |
| Kingston SV300S37A120G 120GB SSD                   | 1556      | 0.44%   |
| Seagate ST2000DM008-2FR102 2TB                     | 1410      | 0.4%    |
| Crucial CT500MX500SSD1 500GB                       | 1402      | 0.4%    |
| Samsung SSD 860 EVO 1TB                            | 1387      | 0.4%    |
| Toshiba MQ04ABF100 1TB                             | 1386      | 0.4%    |
| WDC WD10EZEX-08WN4A0 1TB                           | 1352      | 0.39%   |
| HGST HTS721010A9E630 1TB                           | 1347      | 0.38%   |
| Seagate ST9500325AS 500GB                          | 1291      | 0.37%   |
| Samsung SSD 860 EVO 250GB                          | 1280      | 0.36%   |
| Crucial CT240BX500SSD1 240GB                       | 1253      | 0.36%   |
| Samsung NVMe SSD Drive 512GB                       | 1250      | 0.36%   |
| Seagate ST3500418AS 500GB                          | 1220      | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB                     | 1190      | 0.34%   |
| Crucial CT1000MX500SSD1 1TB                        | 1182      | 0.34%   |
| Samsung NVMe SSD Drive 500GB                       | 1157      | 0.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 1151      | 0.33%   |
| Unknown                                            | 1132      | 0.32%   |
| Unknown SD/MMC/MS PRO 16GB                         | 1077      | 0.31%   |
| Seagate ST1000DM003-1ER162 1TB                     | 1040      | 0.3%    |
| Toshiba DT01ACA050 500GB                           | 1021      | 0.29%   |
| Unknown MMC Card  128GB                            | 1015      | 0.29%   |
| Samsung NVMe SSD Drive 1TB                         | 1005      | 0.29%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 999       | 0.28%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 48631     | 76449  | 34.79%  |
| WDC                 | 42245     | 67211  | 30.22%  |
| Toshiba             | 17148     | 23443  | 12.27%  |
| Hitachi             | 11699     | 15934  | 8.37%   |
| Samsung Electronics | 7005      | 10020  | 5.01%   |
| HGST                | 6046      | 8711   | 4.33%   |
| Fujitsu             | 1710      | 2162   | 1.22%   |
| Maxtor              | 1546      | 2035   | 1.11%   |
| Unknown             | 1177      | 1634   | 0.84%   |
| Apple               | 682       | 802    | 0.49%   |
| Hewlett-Packard     | 187       | 418    | 0.13%   |
| External            | 152       | 199    | 0.11%   |
| Intenso             | 145       | 204    | 0.1%    |
| ASMT                | 138       | 271    | 0.1%    |
| USB3.0              | 115       | 136    | 0.08%   |
| IBM/Hitachi         | 89        | 104    | 0.06%   |
| JMicron Technology  | 79        | 156    | 0.06%   |
| ExcelStor           | 64        | 76     | 0.05%   |
| SSK                 | 61        | 68     | 0.04%   |
| HGST HTS            | 58        | 70     | 0.04%   |
| LaCie               | 52        | 79     | 0.04%   |
| WD MediaMax         | 51        | 79     | 0.04%   |
| USB                 | 51        | 61     | 0.04%   |
| HPE                 | 35        | 69     | 0.03%   |
| ASMedia             | 30        | 40     | 0.02%   |
| SABRENT             | 27        | 40     | 0.02%   |
| Unknown             | 27        | 33     | 0.02%   |
| Quantum             | 24        | 26     | 0.02%   |
| KESU                | 24        | 34     | 0.02%   |
| SAGE                | 23        | 30     | 0.02%   |
| Maxone              | 21        | 27     | 0.02%   |
| ASMT109x            | 21        | 31     | 0.02%   |
| MARVELL             | 20        | 27     | 0.01%   |
| StoreJet            | 17        | 18     | 0.01%   |
| Magnetic Data       | 17        | 19     | 0.01%   |
| Initio              | 16        | 16     | 0.01%   |
| IBM                 | 16        | 22     | 0.01%   |
| Pioneer             | 15        | 25     | 0.01%   |
| DELLBOSS            | 13        | 14     | 0.01%   |
| Apricorn            | 13        | 16     | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 21682     | 32408  | 21.69%  |
| Kingston            | 14098     | 19131  | 14.1%   |
| Crucial             | 9315      | 13182  | 9.32%   |
| SanDisk             | 9061      | 12261  | 9.06%   |
| WDC                 | 5825      | 7853   | 5.83%   |
| A-DATA Technology   | 3647      | 4871   | 3.65%   |
| China               | 2887      | 3768   | 2.89%   |
| Intel               | 2815      | 3991   | 2.82%   |
| Micron Technology   | 1801      | 2414   | 1.8%    |
| SPCC                | 1707      | 2307   | 1.71%   |
| SK hynix            | 1589      | 2079   | 1.59%   |
| Toshiba             | 1575      | 2138   | 1.58%   |
| PNY                 | 1534      | 2065   | 1.53%   |
| OCZ                 | 1470      | 1913   | 1.47%   |
| Transcend           | 1191      | 1526   | 1.19%   |
| Apple               | 1158      | 1346   | 1.16%   |
| Patriot             | 1138      | 1533   | 1.14%   |
| LITEON              | 1027      | 1265   | 1.03%   |
| Intenso             | 987       | 1317   | 0.99%   |
| GOODRAM             | 873       | 1251   | 0.87%   |
| Apacer              | 717       | 931    | 0.72%   |
| Corsair             | 697       | 935    | 0.7%    |
| LITEONIT            | 648       | 827    | 0.65%   |
| KingSpec            | 644       | 825    | 0.64%   |
| Plextor             | 633       | 895    | 0.63%   |
| Team                | 610       | 795    | 0.61%   |
| Netac               | 528       | 739    | 0.53%   |
| Gigabyte Technology | 394       | 553    | 0.39%   |
| Hewlett-Packard     | 386       | 548    | 0.39%   |
| SABRENT             | 385       | 460    | 0.39%   |
| Lexar               | 375       | 447    | 0.38%   |
| ASMT                | 346       | 420    | 0.35%   |
| Unknown             | 344       | 393    | 0.34%   |
| Seagate             | 323       | 455    | 0.32%   |
| KingDian            | 304       | 417    | 0.3%    |
| Smartbuy            | 260       | 338    | 0.26%   |
| AMD                 | 231       | 299    | 0.23%   |
| Mushkin             | 218       | 320    | 0.22%   |
| TO Exter            | 200       | 252    | 0.2%    |
| Unknown             | 192       | 230    | 0.19%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 118209    | 211410 | 41.9%   |
| SSD     | 87072     | 137994 | 30.86%  |
| NVMe    | 60852     | 90504  | 21.57%  |
| MMC     | 11384     | 15319  | 4.03%   |
| Unknown | 4638      | 6723   | 1.64%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 168291    | 337674 | 66.72%  |
| NVMe | 60412     | 89536  | 23.95%  |
| SAS  | 12164     | 19421  | 4.82%   |
| MMC  | 11384     | 15319  | 4.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 128644    | 209895 | 60.11%  |
| 0.51-1.0        | 59015     | 90785  | 27.57%  |
| 1.01-2.0        | 14717     | 24544  | 6.88%   |
| 3.01-4.0        | 4468      | 8843   | 2.09%   |
| 2.01-3.0        | 3640      | 6555   | 1.7%    |
| 4.01-10.0       | 2889      | 6895   | 1.35%   |
| 10.01-20.0      | 610       | 1840   | 0.29%   |
| More than 100.0 | 16        | 18     | 0.01%   |
| 20.01-50.0      | 10        | 15     | 0.005%  |
| 0               | 10        | 10     | 0.005%  |
| 50.01-100.0     | 1         | 4      | 0.0005% |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 59715     | 25.31%  |
| 251-500        | 50935     | 21.59%  |
| 501-1000       | 33860     | 14.35%  |
| 1-20           | 19768     | 8.38%   |
| 1001-2000      | 17385     | 7.37%   |
| 51-100         | 16600     | 7.04%   |
| 21-50          | 10829     | 4.59%   |
| More than 3000 | 10590     | 4.49%   |
| Unknown        | 9876      | 4.19%   |
| 2001-3000      | 6336      | 2.69%   |
| 0              | 2         | 0.001%  |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 99593     | 40.9%   |
| 21-50          | 39065     | 16.04%  |
| 101-250        | 27796     | 11.41%  |
| 51-100         | 25280     | 10.38%  |
| 251-500        | 17034     | 7%      |
| 501-1000       | 12005     | 4.93%   |
| Unknown        | 9876      | 4.06%   |
| 1001-2000      | 6716      | 2.76%   |
| More than 3000 | 3681      | 1.51%   |
| 2001-3000      | 2408      | 0.99%   |
| 0              | 52        | 0.02%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 552       | 707    | 1.74%   |
| Seagate ST9500325AS 500GB           | 482       | 614    | 1.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 351       | 437    | 1.11%   |
| Seagate ST500LT012-9WS142 500GB     | 338       | 423    | 1.07%   |
| Seagate ST3500418AS 500GB           | 326       | 435    | 1.03%   |
| Seagate ST500LT012-1DG142 500GB     | 270       | 322    | 0.85%   |
| HGST HTS545050A7E680 500GB          | 269       | 357    | 0.85%   |
| Seagate ST9320325AS 320GB           | 243       | 304    | 0.77%   |
| Toshiba MQ01ABD100 1TB              | 216       | 259    | 0.68%   |
| Seagate ST1000LM035-1RK172 1TB      | 204       | 224    | 0.64%   |
| Kingston SV300S37A120G 120GB SSD    | 192       | 219    | 0.61%   |
| Seagate ST9250315AS 250GB           | 184       | 224    | 0.58%   |
| HGST HTS541010A9E680 1TB            | 179       | 223    | 0.56%   |
| Seagate ST31000528AS 1TB            | 177       | 223    | 0.56%   |
| WDC WD5000AAKX-001CA0 500GB         | 167       | 212    | 0.53%   |
| HGST HTS721010A9E630 1TB            | 165       | 197    | 0.52%   |
| Toshiba MQ01ABF050 500GB            | 159       | 206    | 0.5%    |
| Seagate ST3250410AS 250GB           | 155       | 198    | 0.49%   |
| HGST HTS545050A7E380 500GB          | 149       | 206    | 0.47%   |
| Seagate ST3250310AS 250GB           | 147       | 213    | 0.46%   |
| HGST HTS725050A7E630 500GB          | 142       | 178    | 0.45%   |
| Hitachi HTS543232A7A384 320GB       | 140       | 167    | 0.44%   |
| Seagate ST1000DM003-1CH162 1TB      | 139       | 188    | 0.44%   |
| Seagate ST31000524AS 1TB            | 134       | 168    | 0.42%   |
| SanDisk SSD U100 256GB              | 128       | 129    | 0.4%    |
| Seagate ST1000DM003-9YN162 1TB      | 127       | 148    | 0.4%    |
| Toshiba MQ01ABD050 500GB            | 125       | 146    | 0.39%   |
| Seagate ST9500420AS 500GB           | 122       | 152    | 0.38%   |
| Seagate ST320LT020-9YG142 320GB     | 120       | 169    | 0.38%   |
| Hitachi HTS547575A9E384 752GB       | 118       | 149    | 0.37%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 117       | 137    | 0.37%   |
| Hitachi HTS545050A7E380 500GB       | 117       | 142    | 0.37%   |
| WDC WD10EARS-00Y5B1 1TB             | 115       | 164    | 0.36%   |
| Seagate ST3320613AS 320GB           | 112       | 149    | 0.35%   |
| Hitachi HTS545050B9A300 500GB       | 112       | 145    | 0.35%   |
| Toshiba DT01ACA100 1TB              | 109       | 148    | 0.34%   |
| Hitachi HTS547550A9E384 500GB       | 106       | 144    | 0.33%   |
| Hitachi HDS721010CLA332 1TB         | 106       | 129    | 0.33%   |
| Seagate ST3500413AS 500GB           | 105       | 122    | 0.33%   |
| Seagate ST3160815AS 160GB           | 105       | 123    | 0.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9008      | 12042  | 29.5%   |
| WDC                 | 6785      | 9159   | 22.22%  |
| Hitachi             | 3180      | 4039   | 10.41%  |
| Samsung Electronics | 2406      | 3202   | 7.88%   |
| Toshiba             | 2389      | 2947   | 7.82%   |
| HGST                | 1128      | 1450   | 3.69%   |
| Kingston            | 720       | 872    | 2.36%   |
| SanDisk             | 593       | 668    | 1.94%   |
| Maxtor              | 524       | 650    | 1.72%   |
| Intel               | 488       | 663    | 1.6%    |
| Crucial             | 394       | 506    | 1.29%   |
| SK hynix            | 334       | 398    | 1.09%   |
| Fujitsu             | 299       | 359    | 0.98%   |
| A-DATA Technology   | 297       | 371    | 0.97%   |
| Micron Technology   | 188       | 244    | 0.62%   |
| OCZ                 | 167       | 215    | 0.55%   |
| China               | 136       | 158    | 0.45%   |
| SPCC                | 116       | 137    | 0.38%   |
| Corsair             | 100       | 141    | 0.33%   |
| Apple               | 79        | 88     | 0.26%   |
| LITEON              | 77        | 87     | 0.25%   |
| KingSpec            | 54        | 68     | 0.18%   |
| LITEONIT            | 53        | 67     | 0.17%   |
| Hewlett-Packard     | 51        | 57     | 0.17%   |
| IBM/Hitachi         | 43        | 50     | 0.14%   |
| Netac               | 40        | 43     | 0.13%   |
| Plextor             | 39        | 56     | 0.13%   |
| Kingmax             | 39        | 67     | 0.13%   |
| Intenso             | 38        | 46     | 0.12%   |
| Unknown             | 35        | 39     | 0.11%   |
| Transcend           | 34        | 49     | 0.11%   |
| ASMT                | 33        | 48     | 0.11%   |
| Patriot             | 26        | 29     | 0.09%   |
| Apacer              | 26        | 34     | 0.09%   |
| AMD                 | 23        | 28     | 0.08%   |
| PNY                 | 19        | 32     | 0.06%   |
| Unknown             | 18        | 23     | 0.06%   |
| Mushkin             | 18        | 18     | 0.06%   |
| ExcelStor           | 18        | 20     | 0.06%   |
| SSSTC               | 17        | 20     | 0.06%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 9006      | 12038  | 35.97%  |
| WDC                 | 6548      | 8864   | 26.15%  |
| Hitachi             | 3180      | 4039   | 12.7%   |
| Toshiba             | 2315      | 2857   | 9.25%   |
| Samsung Electronics | 1774      | 2372   | 7.08%   |
| HGST                | 1128      | 1450   | 4.5%    |
| Maxtor              | 524       | 650    | 2.09%   |
| Fujitsu             | 299       | 359    | 1.19%   |
| Apple               | 54        | 59     | 0.22%   |
| IBM/Hitachi         | 43        | 50     | 0.17%   |
| Hewlett-Packard     | 29        | 35     | 0.12%   |
| ExcelStor           | 18        | 20     | 0.07%   |
| ASMT                | 15        | 23     | 0.06%   |
| WD MediaMax         | 13        | 18     | 0.05%   |
| IBM                 | 12        | 14     | 0.05%   |
| Unknown             | 10        | 15     | 0.04%   |
| HGST HTS            | 7         | 9      | 0.03%   |
| MARSHAL             | 6         | 7      | 0.02%   |
| ASMedia             | 6         | 10     | 0.02%   |
| USB3.0              | 5         | 6      | 0.02%   |
| Quantum             | 5         | 5      | 0.02%   |
| Unknown             | 5         | 6      | 0.02%   |
| Initio              | 4         | 5      | 0.02%   |
| HPE                 | 4         | 6      | 0.02%   |
| MDT                 | 3         | 3      | 0.01%   |
| Magnetic Data       | 3         | 3      | 0.01%   |
| JMicron Technology  | 3         | 4      | 0.01%   |
| SAGE                | 2         | 2      | 0.01%   |
| LaCie               | 2         | 2      | 0.01%   |
| Intenso             | 2         | 2      | 0.01%   |
| USB                 | 1         | 1      | 0.004%  |
| TPH00100500GB       | 1         | 1      | 0.004%  |
| RSH-339             | 1         | 1      | 0.004%  |
| RSH-319             | 1         | 1      | 0.004%  |
| MaxDigital          | 1         | 1      | 0.004%  |
| ICY BOX             | 1         | 2      | 0.004%  |
| IB                  | 1         | 1      | 0.004%  |
| FEASSO              | 1         | 2      | 0.004%  |
| External            | 1         | 1      | 0.004%  |
| DAS                 | 1         | 3      | 0.004%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 23102     | 32952  | 80.95%  |
| SSD     | 4765      | 6023   | 16.7%   |
| NVMe    | 668       | 844    | 2.34%   |
| Unknown | 5         | 6      | 0.02%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB          | 20        | 24     | 2.43%   |
| Seagate ST31000528AS 1TB           | 18        | 22     | 2.19%   |
| Samsung Electronics HD502HJ 500GB  | 12        | 17     | 1.46%   |
| Samsung Electronics SSD 980 1TB    | 10        | 11     | 1.22%   |
| Hitachi HDS721010DLE630 1TB        | 10        | 19     | 1.22%   |
| Seagate ST500DM002-1BD142 500GB    | 9         | 10     | 1.09%   |
| Samsung Electronics HM321HI 320GB  | 9         | 11     | 1.09%   |
| Seagate ST9500325AS 500GB          | 8         | 10     | 0.97%   |
| Seagate ST9320325AS 320GB          | 8         | 9      | 0.97%   |
| Seagate ST500LT012-1DG142 500GB    | 8         | 8      | 0.97%   |
| Seagate ST31000524AS 1TB           | 8         | 10     | 0.97%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 8         | 8      | 0.97%   |
| HGST HTS545050A7E680 500GB         | 8         | 8      | 0.97%   |
| Seagate ST3250318AS 250GB          | 7         | 11     | 0.85%   |
| Samsung Electronics SSD 980 500GB  | 7         | 8      | 0.85%   |
| Samsung Electronics HD103SJ 1TB    | 7         | 9      | 0.85%   |
| Hitachi HTS545050A7E380 500GB      | 7         | 8      | 0.85%   |
| HGST HTS721010A9E630 1TB           | 7         | 8      | 0.85%   |
| Apple HDD HTS541010A9E662 1TB      | 7         | 7      | 0.85%   |
| WDC WD3200BEVT-22ZCT0 320GB        | 6         | 7      | 0.73%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 6         | 7      | 0.73%   |
| Seagate ST3500412AS 500GB          | 6         | 8      | 0.73%   |
| Samsung Electronics HD502IJ 500GB  | 6         | 6      | 0.73%   |
| Samsung Electronics HD252HJ 250GB  | 6         | 10     | 0.73%   |
| Hitachi HTS547550A9E384 500GB      | 6         | 7      | 0.73%   |
| HGST HTS545050A7E380 500GB         | 6         | 6      | 0.73%   |
| Toshiba MQ01ABD100 1TB             | 5         | 5      | 0.61%   |
| Toshiba MQ01ABD050 500GB           | 5         | 5      | 0.61%   |
| Toshiba MK6465GSX 640GB            | 5         | 7      | 0.61%   |
| Toshiba MK3265GSX 320GB            | 5         | 5      | 0.61%   |
| Toshiba DT01ACA100 1TB             | 5         | 6      | 0.61%   |
| Seagate ST3500410AS 500GB          | 5         | 7      | 0.61%   |
| Seagate ST3320613AS 320GB          | 5         | 6      | 0.61%   |
| Samsung Electronics HD322GJ 320GB  | 5         | 6      | 0.61%   |
| HGST HTS541010A9E680 1TB           | 5         | 6      | 0.61%   |
| WDC WD5000BEVT-22A0RT0 500GB       | 4         | 10     | 0.49%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 4         | 4      | 0.49%   |
| Toshiba MK5065GSX 500GB            | 4         | 4      | 0.49%   |
| Toshiba DT01ACA050 500GB           | 4         | 4      | 0.49%   |
| Seagate ST9250315AS 250GB          | 4         | 4      | 0.49%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| Seagate                 | 206       | 250    | 25.12%  |
| WDC                     | 193       | 228    | 23.54%  |
| Samsung Electronics     | 152       | 184    | 18.54%  |
| Toshiba                 | 88        | 100    | 10.73%  |
| Hitachi                 | 68        | 81     | 8.29%   |
| HGST                    | 35        | 39     | 4.27%   |
| Maxtor                  | 12        | 12     | 1.46%   |
| Apple                   | 10        | 11     | 1.22%   |
| Intel                   | 8         | 11     | 0.98%   |
| Crucial                 | 6         | 6      | 0.73%   |
| SK hynix                | 5         | 5      | 0.61%   |
| Kingston                | 4         | 4      | 0.49%   |
| Hewlett-Packard         | 4         | 8      | 0.49%   |
| Mushkin                 | 2         | 2      | 0.24%   |
| Intenso                 | 2         | 2      | 0.24%   |
| Fujitsu                 | 2         | 2      | 0.24%   |
| A-DATA Technology       | 2         | 2      | 0.24%   |
| Zheino                  | 1         | 1      | 0.12%   |
| Unknown                 | 1         | 1      | 0.12%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.12%   |
| Transcend               | 1         | 1      | 0.12%   |
| TPH00800640GB           | 1         | 1      | 0.12%   |
| SPCC                    | 1         | 1      | 0.12%   |
| SanDisk                 | 1         | 1      | 0.12%   |
| Phison                  | 1         | 1      | 0.12%   |
| Patriot                 | 1         | 2      | 0.12%   |
| OCZ-AGIL                | 1         | 1      | 0.12%   |
| OCZ                     | 1         | 1      | 0.12%   |
| Micron Technology       | 1         | 1      | 0.12%   |
| LITEON                  | 1         | 2      | 0.12%   |
| KingDian                | 1         | 4      | 0.12%   |
| JMicron Technology      | 1         | 1      | 0.12%   |
| Inland                  | 1         | 1      | 0.12%   |
| IBM-ESXS                | 1         | 2      | 0.12%   |
| GOODRAM                 | 1         | 1      | 0.12%   |
| External                | 1         | 1      | 0.12%   |
| Corsair                 | 1         | 1      | 0.12%   |
| Acer                    | 1         | 1      | 0.12%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 118180    | 241304 | 49.14%  |
| Works    | 93708     | 179833 | 38.97%  |
| Malfunc  | 27764     | 39825  | 11.55%  |
| Failed   | 813       | 974    | 0.34%   |
| Limited  | 9         | 9      | 0.004%  |
| Fixed    | 5         | 5      | 0.002%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 144079    | 53.48%  |
| AMD                              | 42793     | 15.88%  |
| Samsung Electronics              | 21426     | 7.95%   |
| Sandisk                          | 9671      | 3.59%   |
| SK hynix                         | 5188      | 1.93%   |
| Nvidia                           | 5169      | 1.92%   |
| ASMedia Technology               | 4131      | 1.53%   |
| Phison Electronics               | 4123      | 1.53%   |
| Kingston Technology Company      | 3943      | 1.46%   |
| JMicron Technology               | 3558      | 1.32%   |
| Marvell Technology Group         | 3249      | 1.21%   |
| Toshiba America Info Systems     | 2849      | 1.06%   |
| Micron Technology                | 2483      | 0.92%   |
| Micron/Crucial Technology        | 2216      | 0.82%   |
| Silicon Motion                   | 2015      | 0.75%   |
| KIOXIA                           | 1966      | 0.73%   |
| ADATA Technology                 | 1628      | 0.6%    |
| VIA Technologies                 | 1028      | 0.38%   |
| LSI Logic / Symbios Logic        | 816       | 0.3%    |
| Realtek Semiconductor            | 814       | 0.3%    |
| Broadcom / LSI                   | 672       | 0.25%   |
| Silicon Integrated Systems [SiS] | 592       | 0.22%   |
| Union Memory (Shenzhen)          | 537       | 0.2%    |
| Solid State Storage Technology   | 479       | 0.18%   |
| Apple                            | 448       | 0.17%   |
| MAXIO Technology (Hangzhou)      | 380       | 0.14%   |
| Silicon Image                    | 375       | 0.14%   |
| Lite-On Technology               | 334       | 0.12%   |
| Seagate Technology               | 302       | 0.11%   |
| Hewlett-Packard                  | 256       | 0.1%    |
| Adaptec                          | 252       | 0.09%   |
| Shenzhen Longsys Electronics     | 239       | 0.09%   |
| Lenovo                           | 183       | 0.07%   |
| O2 Micro                         | 150       | 0.06%   |
| INNOGRIT                         | 135       | 0.05%   |
| Integrated Technology Express    | 122       | 0.05%   |
| Yangtze Memory Technologies      | 121       | 0.04%   |
| Biwin Storage Technology         | 79        | 0.03%   |
| Netac Technology                 | 72        | 0.03%   |
| OCZ Technology Group             | 44        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 27238     | 8.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 10645     | 3.34%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 10233     | 3.22%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 10028     | 3.15%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 9198      | 2.89%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 7155      | 2.25%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 7096      | 2.23%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5802      | 1.82%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5624      | 1.77%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 5621      | 1.77%   |
| AMD 400 Series Chipset SATA Controller                                                  | 5345      | 1.68%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 5040      | 1.58%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4824      | 1.52%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 4807      | 1.51%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4648      | 1.46%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 4405      | 1.38%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 4119      | 1.29%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4013      | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 3807      | 1.2%    |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3806      | 1.2%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 3730      | 1.17%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3541      | 1.11%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3418      | 1.07%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 3287      | 1.03%   |
| Intel SATA Controller [RAID mode]                                                       | 3065      | 0.96%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 3000      | 0.94%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 2970      | 0.93%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2930      | 0.92%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2868      | 0.9%    |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2711      | 0.85%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2683      | 0.84%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 2624      | 0.82%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2569      | 0.81%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2494      | 0.78%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2487      | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2425      | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 2404      | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2195      | 0.69%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 2191      | 0.69%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 2134      | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 155815    | 56.98%  |
| NVMe | 60815     | 22.24%  |
| IDE  | 38329     | 14.02%  |
| RAID | 17030     | 6.23%   |
| SAS  | 1004      | 0.37%   |
| SCSI | 464       | 0.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 162332    | 74.49%  |
| AMD                      | 53459     | 24.53%  |
| ARM                      | 1822      | 0.84%   |
| QUALCOMM                 | 72        | 0.03%   |
| CentaurHauls             | 70        | 0.03%   |
| Unknown                  | 70        | 0.03%   |
| Phytium                  | 23        | 0.01%   |
| sifive,u74-mc            | 13        | 0.01%   |
| HiSilicon                | 6         | 0.003%  |
| Marvell Semiconductor    | 5         | 0.002%  |
| CHRP IBM,8233-E8B        | 5         | 0.002%  |
| Loongson                 | 4         | 0.002%  |
| thead,c906               | 3         | 0.001%  |
| sifive,bullet0           | 3         | 0.001%  |
| PowerNV C1P9S01 REV 1.01 | 3         | 0.001%  |
| PowerBook5,6             | 2         | 0.001%  |
| MIPS                     | 2         | 0.001%  |
| CHRP IBM,9131-52A        | 2         | 0.001%  |
| PowerNV FP5466G2         | 1         | 0.0005% |
| PowerNV C829UAG3         | 1         | 0.0005% |
| PowerMac8,1              | 1         | 0.0005% |
| PowerMac7,2              | 1         | 0.0005% |
| PowerMac3,6              | 1         | 0.0005% |
| PowerMac11,2             | 1         | 0.0005% |
| PowerMac10,2             | 1         | 0.0005% |
| PowerBook6,7             | 1         | 0.0005% |
| PowerBook5,5             | 1         | 0.0005% |
| PowerBook5,4             | 1         | 0.0005% |
| PowerBook3,4             | 1         | 0.0005% |
| MBE8C-PC                 | 1         | 0.0005% |
| IBM/S390                 | 1         | 0.0005% |
| GenuineTMx86             | 1         | 0.0005% |
| FSP-1                    | 1         | 0.0005% |
| Elbrus-MCST              | 1         | 0.0005% |
| E8C/EATX                 | 1         | 0.0005% |
| E8C-SWTX                 | 1         | 0.0005% |
| E8C-mITX                 | 1         | 0.0005% |
| AppliedMicro             | 1         | 0.0005% |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 2112      | 0.97%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1829      | 0.84%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1823      | 0.83%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 1782      | 0.81%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1779      | 0.81%   |
| AMD Ryzen 5 3600 6-Core Processor             | 1534      | 0.7%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1435      | 0.66%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 1416      | 0.65%   |
| ARM Processor                                 | 1297      | 0.59%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1283      | 0.59%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1278      | 0.58%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 1248      | 0.57%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 1233      | 0.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 1225      | 0.56%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 1187      | 0.54%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1174      | 0.54%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 1131      | 0.52%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1129      | 0.52%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 1110      | 0.51%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 1032      | 0.47%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 1029      | 0.47%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1022      | 0.47%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 1019      | 0.47%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 1011      | 0.46%   |
| AMD Custom APU 0405                           | 992       | 0.45%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 971       | 0.44%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 943       | 0.43%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 927       | 0.42%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 917       | 0.42%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 848       | 0.39%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 843       | 0.39%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 837       | 0.38%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 836       | 0.38%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 835       | 0.38%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 811       | 0.37%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 804       | 0.37%   |
| AMD FX-8350 Eight-Core Processor              | 783       | 0.36%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 762       | 0.35%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 762       | 0.35%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 750       | 0.34%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 44592     | 20.41%  |
| Intel Core i7           | 35981     | 16.47%  |
| Intel Core i3           | 17490     | 8%      |
| Other                   | 14332     | 6.56%   |
| AMD Ryzen 5             | 11622     | 5.32%   |
| Intel Celeron           | 11386     | 5.21%   |
| Intel Core 2 Duo        | 10438     | 4.78%   |
| AMD Ryzen 7             | 8870      | 4.06%   |
| Intel Pentium           | 6556      | 3%      |
| Intel Xeon              | 5500      | 2.52%   |
| Intel Atom              | 4600      | 2.11%   |
| AMD FX                  | 3688      | 1.69%   |
| Intel Pentium Dual-Core | 3185      | 1.46%   |
| AMD Ryzen 9             | 3035      | 1.39%   |
| AMD Ryzen 3             | 2305      | 1.05%   |
| Intel Core 2 Quad       | 2194      | 1%      |
| AMD A6                  | 1900      | 0.87%   |
| AMD A8                  | 1828      | 0.84%   |
| Intel Core 2            | 1574      | 0.72%   |
| AMD A10                 | 1552      | 0.71%   |
| AMD Athlon 64 X2        | 1536      | 0.7%    |
| AMD A4                  | 1518      | 0.69%   |
| Intel Pentium Dual      | 1479      | 0.68%   |
| AMD Athlon II X2        | 1367      | 0.63%   |
| AMD Phenom II X4        | 1272      | 0.58%   |
| Intel Core i9           | 1213      | 0.56%   |
| Intel Pentium 4         | 1025      | 0.47%   |
| AMD E                   | 940       | 0.43%   |
| Intel Genuine           | 867       | 0.4%    |
| AMD Ryzen 7 PRO         | 806       | 0.37%   |
| AMD E1                  | 782       | 0.36%   |
| AMD Athlon              | 778       | 0.36%   |
| Intel Pentium Silver    | 776       | 0.36%   |
| AMD Athlon II X4        | 629       | 0.29%   |
| AMD E2                  | 602       | 0.28%   |
| AMD Ryzen 5 PRO         | 503       | 0.23%   |
| AMD Phenom II X6        | 491       | 0.22%   |
| AMD Ryzen Threadripper  | 486       | 0.22%   |
| Intel Pentium D         | 473       | 0.22%   |
| AMD Sempron             | 401       | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 91898     | 41.94%  |
| 4       | 74405     | 33.96%  |
| 6       | 19332     | 8.82%   |
| 8       | 14238     | 6.5%    |
| 1       | 6867      | 3.13%   |
| 12      | 3324      | 1.52%   |
| Unknown | 2142      | 0.98%   |
| 3       | 1680      | 0.77%   |
| 16      | 1662      | 0.76%   |
| 10      | 1375      | 0.63%   |
| 14      | 1031      | 0.47%   |
| 24      | 414       | 0.19%   |
| 32      | 184       | 0.08%   |
| 20      | 178       | 0.08%   |
| 28      | 77        | 0.04%   |
| 18      | 52        | 0.02%   |
| 64      | 49        | 0.02%   |
| 40      | 48        | 0.02%   |
| 36      | 31        | 0.01%   |
| 5       | 30        | 0.01%   |
| 48      | 28        | 0.01%   |
| 44      | 17        | 0.01%   |
| 128     | 15        | 0.01%   |
| 96      | 9         | 0.004%  |
| 22      | 8         | 0.004%  |
| 56      | 7         | 0.003%  |
| 80      | 4         | 0.002%  |
| 52      | 4         | 0.002%  |
| 192     | 3         | 0.001%  |
| 26      | 3         | 0.001%  |
| 104     | 2         | 0.001%  |
| 7       | 2         | 0.001%  |
| 384     | 1         | 0.0005% |
| 120     | 1         | 0.0005% |
| 72      | 1         | 0.0005% |
| 68      | 1         | 0.0005% |
| 15      | 1         | 0.0005% |
| 9       | 1         | 0.0005% |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 215205    | 98.71%  |
| 2       | 2303      | 1.06%   |
| Unknown | 405       | 0.19%   |
| 4       | 70        | 0.03%   |
| 3       | 34        | 0.02%   |
| 8       | 4         | 0.002%  |
| 0       | 3         | 0.001%  |
| 16      | 2         | 0.001%  |
| 14      | 1         | 0.0005% |
| 6       | 1         | 0.0005% |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 136269    | 62.22%  |
| 1       | 80526     | 36.76%  |
| Unknown | 2142      | 0.98%   |
| 4       | 53        | 0.02%   |
| 8       | 28        | 0.01%   |
| 12      | 6         | 0.003%  |
| 16      | 2         | 0.001%  |
| 6       | 2         | 0.001%  |
| 112     | 1         | 0.0005% |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 211004    | 96.48%  |
| Unknown        | 4870      | 2.23%   |
| 32-bit         | 2464      | 1.13%   |
| 64-bit         | 375       | 0.17%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 56635     | 24.94%  |
| 0x206a7    | 13179     | 5.8%    |
| 0x306a9    | 12392     | 5.46%   |
| 0x1067a    | 9039      | 3.98%   |
| 0x306c3    | 9001      | 3.96%   |
| 0x906ea    | 4949      | 2.18%   |
| 0x806ea    | 4293      | 1.89%   |
| 0x806ec    | 4064      | 1.79%   |
| 0x40651    | 4051      | 1.78%   |
| 0x506e3    | 3858      | 1.7%    |
| 0x20655    | 3758      | 1.65%   |
| 0x806e9    | 3697      | 1.63%   |
| 0x806c1    | 3690      | 1.62%   |
| 0x406e3    | 3584      | 1.58%   |
| 0x906e9    | 3353      | 1.48%   |
| 0x6fd      | 3205      | 1.41%   |
| 0x306d4    | 3203      | 1.41%   |
| 0x010000c8 | 2540      | 1.12%   |
| 0x08701021 | 2434      | 1.07%   |
| 0x10676    | 2301      | 1.01%   |
| 0x30678    | 2277      | 1%      |
| 0x08108109 | 2253      | 0.99%   |
| 0x406c4    | 1961      | 0.86%   |
| 0x0a50000c | 1887      | 0.83%   |
| 0x06001119 | 1855      | 0.82%   |
| 0x0800820d | 1724      | 0.76%   |
| 0x06000852 | 1673      | 0.74%   |
| 0x6fb      | 1597      | 0.7%    |
| 0x20652    | 1575      | 0.69%   |
| 0x706e5    | 1408      | 0.62%   |
| 0x08600106 | 1404      | 0.62%   |
| 0xa0652    | 1320      | 0.58%   |
| 0x706a1    | 1264      | 0.56%   |
| 0x08108102 | 1256      | 0.55%   |
| 0x506c9    | 1191      | 0.52%   |
| 0x106ca    | 1182      | 0.52%   |
| 0x106e5    | 1170      | 0.52%   |
| 0x906ed    | 1154      | 0.51%   |
| 0x08701013 | 1112      | 0.49%   |
| 0x806eb    | 1109      | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 30915     | 14.14%  |
| Haswell          | 17930     | 8.2%    |
| SandyBridge      | 16773     | 7.67%   |
| IvyBridge        | 16078     | 7.36%   |
| Penryn           | 13395     | 6.13%   |
| Skylake          | 10682     | 4.89%   |
| Unknown          | 8791      | 4.02%   |
| Zen 2            | 8402      | 3.84%   |
| Core             | 8104      | 3.71%   |
| Westmere         | 7157      | 3.27%   |
| Zen+             | 6814      | 3.12%   |
| Silvermont       | 6725      | 3.08%   |
| Zen 3            | 6088      | 2.79%   |
| K10              | 5852      | 2.68%   |
| TigerLake        | 5379      | 2.46%   |
| Piledriver       | 5210      | 2.38%   |
| Broadwell        | 4701      | 2.15%   |
| CometLake        | 4231      | 1.94%   |
| Zen              | 4002      | 1.83%   |
| Icelake          | 3065      | 1.4%    |
| Goldmont plus    | 2971      | 1.36%   |
| K8 Hammer        | 2859      | 1.31%   |
| Alderlake Hybrid | 2749      | 1.26%   |
| Excavator        | 2604      | 1.19%   |
| Bonnell          | 2373      | 1.09%   |
| Nehalem          | 2221      | 1.02%   |
| NetBurst         | 1838      | 0.84%   |
| Bobcat           | 1827      | 0.84%   |
| Goldmont         | 1606      | 0.73%   |
| Puma             | 1413      | 0.65%   |
| P6               | 1103      | 0.5%    |
| K10 Llano        | 1016      | 0.46%   |
| Jaguar           | 1008      | 0.46%   |
| Steamroller      | 979       | 0.45%   |
| Bulldozer        | 758       | 0.35%   |
| Tremont          | 457       | 0.21%   |
| K8 & K10 hybrid  | 400       | 0.18%   |
| K6               | 65        | 0.03%   |
| Gracemont        | 42        | 0.02%   |
| Sapphire Rapids  | 4         | 0.002%  |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 121036    | 47.53%  |
| Nvidia                                       | 71618     | 28.13%  |
| AMD                                          | 59179     | 23.24%  |
| Matrox Electronics Systems                   | 1136      | 0.45%   |
| ASPEED Technology                            | 826       | 0.32%   |
| Silicon Integrated Systems [SiS]             | 370       | 0.15%   |
| VIA Technologies                             | 262       | 0.1%    |
| ATI Technologies                             | 79        | 0.03%   |
| XGI Technology (eXtreme Graphics Innovation) | 35        | 0.01%   |
| S3 Graphics                                  | 25        | 0.01%   |
| Zhaoxin                                      | 17        | 0.01%   |
| Silicon Motion                               | 14        | 0.01%   |
| Huawei Technologies                          | 11        | 0.004%  |
| Loongson Technology                          | 7         | 0.003%  |
| Neomagic                                     | 5         | 0.002%  |
| Red Hat                                      | 3         | 0.001%  |
| Phytium Technology                           | 3         | 0.001%  |
| Trident Microsystems                         | 2         | 0.001%  |
| NVidia / SGS Thomson (Joint Venture)         | 2         | 0.001%  |
| Conexant Systems                             | 2         | 0.001%  |
| Nanjing Ruixinview Technology                | 1         | 0.0004% |
| Moore Threads Technology                     | 1         | 0.0004% |
| Jingjia Microelectronics                     | 1         | 0.0004% |
| Dome Imaging Systems                         | 1         | 0.0004% |
| Cirrus Logic                                 | 1         | 0.0004% |
| Alliance Semiconductor                       | 1         | 0.0004% |
| 3DLabs                                       | 1         | 0.0004% |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 12130     | 4.59%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 8936      | 3.38%   |
| Intel UHD Graphics 620                                                                   | 5134      | 1.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5117      | 1.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4712      | 1.78%   |
| Intel HD Graphics 620                                                                    | 4356      | 1.65%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4203      | 1.59%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4182      | 1.58%   |
| Intel Core Processor Integrated Graphics Controller                                      | 4160      | 1.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 3979      | 1.51%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 3936      | 1.49%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3663      | 1.39%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 3621      | 1.37%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3606      | 1.37%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 3574      | 1.35%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 3360      | 1.27%   |
| Intel HD Graphics 5500                                                                   | 3310      | 1.25%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 3116      | 1.18%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 3077      | 1.17%   |
| Intel HD Graphics 530                                                                    | 2959      | 1.12%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2893      | 1.1%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 2752      | 1.04%   |
| Intel HD Graphics 630                                                                    | 2746      | 1.04%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2383      | 0.9%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 2337      | 0.89%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2065      | 0.78%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 2004      | 0.76%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 1982      | 0.75%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 1957      | 0.74%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1888      | 0.72%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1837      | 0.7%    |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1837      | 0.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 1767      | 0.67%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 1718      | 0.65%   |
| AMD Lucienne                                                                             | 1649      | 0.62%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 1523      | 0.58%   |
| Nvidia GT218 [GeForce 210]                                                               | 1484      | 0.56%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1427      | 0.54%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1359      | 0.51%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 1352      | 0.51%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 87204     | 39.63%  |
| 1 x AMD                  | 46201     | 21%     |
| 1 x Nvidia               | 41952     | 19.07%  |
| Intel + Nvidia           | 25548     | 11.61%  |
| Intel + AMD              | 5705      | 2.59%   |
| 2 x AMD                  | 4022      | 1.83%   |
| AMD + Nvidia             | 3277      | 1.49%   |
| Other                    | 2196      | 1%      |
| 1 x Matrox               | 975       | 0.44%   |
| 1 x ASPEED               | 608       | 0.28%   |
| 2 x Nvidia               | 556       | 0.25%   |
| 2 x Intel                | 465       | 0.21%   |
| 1 x SiS                  | 369       | 0.17%   |
| 1 x VIA                  | 259       | 0.12%   |
| Nvidia + ASPEED          | 154       | 0.07%   |
| Nvidia + Matrox          | 113       | 0.05%   |
| AMD + ASPEED             | 48        | 0.02%   |
| AMD + Matrox             | 46        | 0.02%   |
| Intel + 2 x Nvidia       | 45        | 0.02%   |
| 1 x XGI                  | 26        | 0.01%   |
| Intel + AMD + 1 x Nvidia | 25        | 0.01%   |
| 1 x S3 Graphics          | 22        | 0.01%   |
| 3 x AMD                  | 20        | 0.01%   |
| Intel + 2 x AMD          | 18        | 0.01%   |
| 1 x Zhaoxin              | 16        | 0.01%   |
| 3 x Nvidia               | 13        | 0.01%   |
| 2 x AMD + 1 x Nvidia     | 12        | 0.01%   |
| AMD + 2 x Nvidia         | 12        | 0.01%   |
| 2 x Nvidia + 1 x ASPEED  | 11        | 0.005%  |
| 1 x Silicon Motion       | 11        | 0.005%  |
| 1 x Huawei Technologies  | 10        | 0.005%  |
| 2 x Nvidia + 1 x Matrox  | 6         | 0.003%  |
| Nvidia + XGI             | 5         | 0.002%  |
| 1 x Neomagic             | 5         | 0.002%  |
| 1 x Intel + 3 x Nvidia   | 4         | 0.002%  |
| Intel + ASPEED           | 4         | 0.002%  |
| AMD + XGI                | 4         | 0.002%  |
| 4 x Nvidia               | 3         | 0.001%  |
| 1 x Red Hat              | 3         | 0.001%  |
| 1 x Phytium Technology   | 3         | 0.001%  |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 175325    | 78.75%  |
| Proprietary | 36079     | 16.2%   |
| Unknown     | 11239     | 5.05%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 119118    | 52.67%  |
| 1.01-2.0       | 30776     | 13.61%  |
| 0.01-0.5       | 28917     | 12.79%  |
| 0.51-1.0       | 17889     | 7.91%   |
| 3.01-4.0       | 13438     | 5.94%   |
| 7.01-8.0       | 7694      | 3.4%    |
| 5.01-6.0       | 4137      | 1.83%   |
| 8.01-16.0      | 2333      | 1.03%   |
| 2.01-3.0       | 1390      | 0.61%   |
| 16.01-24.0     | 353       | 0.16%   |
| 4.01-5.0       | 69        | 0.03%   |
| 32.01-64.0     | 12        | 0.01%   |
| 24.01-32.0     | 10        | 0.004%  |
| 0              | 3         | 0.001%  |
| More than 64.0 | 1         | 0.0004% |
| 6.01-7.0       | 1         | 0.0004% |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 31338     | 13.5%   |
| AU Optronics            | 26133     | 11.26%  |
| LG Display              | 19876     | 8.56%   |
| BOE                     | 17598     | 7.58%   |
| Chimei Innolux          | 17380     | 7.49%   |
| Goldstar                | 13199     | 5.69%   |
| Dell                    | 12742     | 5.49%   |
| Acer                    | 8521      | 3.67%   |
| Hewlett-Packard         | 7673      | 3.31%   |
| BenQ                    | 5701      | 2.46%   |
| AOC                     | 5580      | 2.4%    |
| Philips                 | 5296      | 2.28%   |
| Ancor Communications    | 4915      | 2.12%   |
| Apple                   | 4490      | 1.93%   |
| Lenovo                  | 4146      | 1.79%   |
| Chi Mei Optoelectronics | 4011      | 1.73%   |
| Sharp                   | 3661      | 1.58%   |
| ViewSonic               | 2772      | 1.19%   |
| Iiyama                  | 2119      | 0.91%   |
| PANDA                   | 1932      | 0.83%   |
| ASUSTek Computer        | 1759      | 0.76%   |
| Sony                    | 1744      | 0.75%   |
| InfoVision              | 1552      | 0.67%   |
| LG Philips              | 1457      | 0.63%   |
| Unknown                 | 1353      | 0.58%   |
| LG Electronics          | 1231      | 0.53%   |
| HannStar                | 1120      | 0.48%   |
| NEC Computers           | 1047      | 0.45%   |
| Eizo                    | 868       | 0.37%   |
| Fujitsu Siemens         | 766       | 0.33%   |
| Panasonic               | 734       | 0.32%   |
| Valve                   | 704       | 0.3%    |
| CPT                     | 694       | 0.3%    |
| Toshiba                 | 686       | 0.3%    |
| CSO                     | 656       | 0.28%   |
| MSI                     | 655       | 0.28%   |
| Vizio                   | 642       | 0.28%   |
| Sceptre Tech            | 530       | 0.23%   |
| Medion                  | 402       | 0.17%   |
| Gigabyte Technology     | 355       | 0.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 1053      | 0.44%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 994       | 0.41%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 964       | 0.4%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 940       | 0.39%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 877       | 0.37%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 868       | 0.36%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 851       | 0.35%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 778       | 0.32%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 663       | 0.28%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 661       | 0.28%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 652       | 0.27%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 652       | 0.27%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch              | 638       | 0.27%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 524       | 0.22%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 495       | 0.21%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 477       | 0.2%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 467       | 0.19%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 455       | 0.19%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 448       | 0.19%   |
| Goldstar LG IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 430       | 0.18%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 413       | 0.17%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 407       | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 404       | 0.17%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 390       | 0.16%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 379       | 0.16%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 372       | 0.15%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 363       | 0.15%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 352       | 0.15%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 349       | 0.15%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 348       | 0.14%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x193mm 15.5-inch            | 345       | 0.14%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 340       | 0.14%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 336       | 0.14%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 336       | 0.14%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 336       | 0.14%   |
| Vestel Elektronik 42 FHD_LCD-TV VES3700 1920x540                         | 335       | 0.14%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 334       | 0.14%   |
| Unknown                                                                  | 332       | 0.14%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 324       | 0.13%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch         | 322       | 0.13%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 90795     | 40.62%  |
| 1366x768 (WXGA)    | 45187     | 20.21%  |
| 3840x2160 (4K)     | 12193     | 5.45%   |
| 1600x900 (HD+)     | 9945      | 4.45%   |
| 1280x1024 (SXGA)   | 9721      | 4.35%   |
| 2560x1440 (QHD)    | 8813      | 3.94%   |
| 1680x1050 (WSXGA+) | 6429      | 2.88%   |
| 1280x800 (WXGA)    | 6322      | 2.83%   |
| 1440x900 (WXGA+)   | 6022      | 2.69%   |
| 1920x1200 (WUXGA)  | 5065      | 2.27%   |
| Unknown            | 2391      | 1.07%   |
| 1360x768           | 2014      | 0.9%    |
| 2560x1080          | 1968      | 0.88%   |
| 3440x1440          | 1938      | 0.87%   |
| 2560x1600          | 1555      | 0.7%    |
| 1024x600           | 1318      | 0.59%   |
| 1024x768 (XGA)     | 1163      | 0.52%   |
| 3840x1080          | 1055      | 0.47%   |
| 2880x1800          | 866       | 0.39%   |
| 800x1280           | 820       | 0.37%   |
| 1920x540           | 753       | 0.34%   |
| 1600x1200          | 629       | 0.28%   |
| 3840x2400          | 564       | 0.25%   |
| 2160x1440          | 537       | 0.24%   |
| 1280x720 (HD)      | 376       | 0.17%   |
| 3200x1800 (QHD+)   | 352       | 0.16%   |
| 2736x1824          | 320       | 0.14%   |
| 2288x1287          | 281       | 0.13%   |
| 2256x1504          | 219       | 0.1%    |
| 3840x1600          | 181       | 0.08%   |
| 1920x1280          | 178       | 0.08%   |
| 1400x1050          | 170       | 0.08%   |
| 3000x2000          | 167       | 0.07%   |
| 3840x1200          | 129       | 0.06%   |
| 2048x1152          | 125       | 0.06%   |
| 3072x1920          | 119       | 0.05%   |
| 4480x1440          | 118       | 0.05%   |
| 3200x2000          | 110       | 0.05%   |
| 1680x945           | 104       | 0.05%   |
| 1280x960           | 104       | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 59117     | 25.5%   |
| 13      | 19558     | 8.44%   |
| 14      | 16433     | 7.09%   |
| 24      | 15319     | 6.61%   |
| 27      | 14804     | 6.39%   |
| 23      | 14525     | 6.27%   |
| 17      | 14353     | 6.19%   |
| 21      | 13491     | 5.82%   |
| Unknown | 10228     | 4.41%   |
| 19      | 8301      | 3.58%   |
| 18      | 5213      | 2.25%   |
| 31      | 4475      | 1.93%   |
| 20      | 4143      | 1.79%   |
| 22      | 4029      | 1.74%   |
| 12      | 3798      | 1.64%   |
| 34      | 3211      | 1.39%   |
| 11      | 3020      | 1.3%    |
| 16      | 1848      | 0.8%    |
| 10      | 1664      | 0.72%   |
| 84      | 1565      | 0.68%   |
| 72      | 1293      | 0.56%   |
| 40      | 1246      | 0.54%   |
| 32      | 1207      | 0.52%   |
| 54      | 1093      | 0.47%   |
| 25      | 820       | 0.35%   |
| 7       | 684       | 0.3%    |
| 26      | 670       | 0.29%   |
| 28      | 442       | 0.19%   |
| 52      | 418       | 0.18%   |
| 48      | 417       | 0.18%   |
| 46      | 351       | 0.15%   |
| 65      | 305       | 0.13%   |
| 37      | 304       | 0.13%   |
| 29      | 297       | 0.13%   |
| 42      | 279       | 0.12%   |
| 49      | 226       | 0.1%    |
| 33      | 215       | 0.09%   |
| 142     | 196       | 0.08%   |
| 39      | 192       | 0.08%   |
| 3       | 177       | 0.08%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 88831     | 38.96%  |
| 501-600        | 41611     | 18.25%  |
| 401-500        | 29886     | 13.11%  |
| 201-300        | 18633     | 8.17%   |
| 351-400        | 16847     | 7.39%   |
| Unknown        | 10228     | 4.49%   |
| 601-700        | 6857      | 3.01%   |
| 701-800        | 4810      | 2.11%   |
| 1001-1500      | 3441      | 1.51%   |
| 1501-2000      | 3094      | 1.36%   |
| 801-900        | 1967      | 0.86%   |
| 1-100          | 823       | 0.36%   |
| 901-1000       | 580       | 0.25%   |
| More than 2000 | 210       | 0.09%   |
| 101-200        | 175       | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 155601    | 73.59%  |
| 16/10   | 26897     | 12.72%  |
| 5/4     | 9088      | 4.3%    |
| Unknown | 8563      | 4.05%   |
| 21/9    | 3799      | 1.8%    |
| 4/3     | 2791      | 1.32%   |
| 3/2     | 2397      | 1.13%   |
| 0.67    | 661       | 0.31%   |
| 6/5     | 521       | 0.25%   |
| 32/9    | 514       | 0.24%   |
| 1.00    | 217       | 0.1%    |
| 0.56    | 99        | 0.05%   |
| 1.96    | 70        | 0.03%   |
| 0.62    | 38        | 0.02%   |
| 3.40    | 32        | 0.02%   |
| 0.45    | 30        | 0.01%   |
| 3.20    | 24        | 0.01%   |
| 3.73    | 16        | 0.01%   |
| 2.00    | 15        | 0.01%   |
| 2.65    | 14        | 0.01%   |
| 0.89    | 7         | 0.003%  |
| 0.58    | 7         | 0.003%  |
| 2.12    | 6         | 0.003%  |
| 0.80    | 5         | 0.002%  |
| 11/10   | 4         | 0.002%  |
| 0.75    | 4         | 0.002%  |
| 0.63    | 4         | 0.002%  |
| 3.33    | 2         | 0.001%  |
| 2.01    | 2         | 0.001%  |
| 1.03    | 2         | 0.001%  |
| 0.65    | 2         | 0.001%  |
| 0.25    | 2         | 0.001%  |
| 3.88    | 1         | 0.0005% |
| 3.76    | 1         | 0.0005% |
| 2.50    | 1         | 0.0005% |
| 2.21    | 1         | 0.0005% |
| 0.57    | 1         | 0.0005% |
| 0.31    | 1         | 0.0005% |
| 0.00    | 1         | 0.0005% |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 58577     | 25.5%   |
| 201-250        | 38079     | 16.58%  |
| 81-90          | 28121     | 12.24%  |
| 151-200        | 16434     | 7.15%   |
| 301-350        | 15290     | 6.66%   |
| Unknown        | 10229     | 4.45%   |
| 351-500        | 9600      | 4.18%   |
| 141-150        | 8689      | 3.78%   |
| 121-130        | 8333      | 3.63%   |
| 71-80          | 7912      | 3.44%   |
| More than 1000 | 5914      | 2.57%   |
| 251-300        | 5822      | 2.53%   |
| 501-1000       | 3385      | 1.47%   |
| 61-70          | 3308      | 1.44%   |
| 51-60          | 3095      | 1.35%   |
| 111-120        | 1827      | 0.8%    |
| 131-140        | 1786      | 0.78%   |
| 41-50          | 1631      | 0.71%   |
| 1-40           | 992       | 0.43%   |
| 91-100         | 687       | 0.3%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 77104     | 34.51%  |
| 101-120       | 62256     | 27.87%  |
| 121-160       | 51964     | 23.26%  |
| 161-240       | 11845     | 5.3%    |
| Unknown       | 10229     | 4.58%   |
| 1-50          | 5490      | 2.46%   |
| More than 240 | 4515      | 2.02%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 178766    | 79.96%  |
| 2     | 30216     | 13.52%  |
| 0     | 10989     | 4.92%   |
| 3     | 3271      | 1.46%   |
| 4     | 288       | 0.13%   |
| 5     | 21        | 0.01%   |
| 6     | 9         | 0.004%  |
| 7     | 1         | 0.0004% |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 119828    | 36.48%  |
| Intel                             | 94222     | 28.68%  |
| Qualcomm Atheros                  | 40522     | 12.34%  |
| Broadcom                          | 19477     | 5.93%   |
| Broadcom Limited                  | 4732      | 1.44%   |
| Marvell Technology Group          | 4455      | 1.36%   |
| Ralink Technology                 | 4350      | 1.32%   |
| Nvidia                            | 4253      | 1.29%   |
| MediaTek                          | 3811      | 1.16%   |
| Ralink                            | 3672      | 1.12%   |
| TP-Link                           | 3278      | 1%      |
| ASIX Electronics                  | 1615      | 0.49%   |
| Samsung Electronics               | 1599      | 0.49%   |
| Huawei Technologies               | 1459      | 0.44%   |
| Qualcomm Atheros Communications   | 1263      | 0.38%   |
| Xiaomi                            | 958       | 0.29%   |
| D-Link                            | 892       | 0.27%   |
| NetGear                           | 885       | 0.27%   |
| Dell                              | 817       | 0.25%   |
| ASUSTek Computer                  | 790       | 0.24%   |
| D-Link System                     | 772       | 0.24%   |
| Microsoft                         | 752       | 0.23%   |
| JMicron Technology                | 733       | 0.22%   |
| Sierra Wireless                   | 728       | 0.22%   |
| VIA Technologies                  | 715       | 0.22%   |
| DisplayLink                       | 657       | 0.2%    |
| Lenovo                            | 643       | 0.2%    |
| Ericsson Business Mobile Networks | 611       | 0.19%   |
| Qualcomm                          | 584       | 0.18%   |
| Aquantia                          | 583       | 0.18%   |
| Hewlett-Packard                   | 482       | 0.15%   |
| Silicon Integrated Systems [SiS]  | 474       | 0.14%   |
| Edimax Technology                 | 407       | 0.12%   |
| Linksys                           | 332       | 0.1%    |
| Motorola PCS                      | 306       | 0.09%   |
| Belkin Components                 | 304       | 0.09%   |
| Microchip Technology              | 278       | 0.08%   |
| Attansic Technology               | 274       | 0.08%   |
| ZTE WCDMA Technologies MSM        | 261       | 0.08%   |
| Google                            | 259       | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 80768     | 21.12%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15574     | 4.07%   |
| Intel Wi-Fi 6 AX200                                               | 8043      | 2.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7237      | 1.89%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 5621      | 1.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 5468      | 1.43%   |
| Intel Wireless 8265 / 8275                                        | 5392      | 1.41%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5325      | 1.39%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 4932      | 1.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4850      | 1.27%   |
| Intel I211 Gigabit Network Connection                             | 4376      | 1.14%   |
| Intel Wireless 7265                                               | 4167      | 1.09%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 4154      | 1.09%   |
| Intel Wi-Fi 6 AX201                                               | 4063      | 1.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3946      | 1.03%   |
| Intel Wireless 7260                                               | 3898      | 1.02%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3891      | 1.02%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 3141      | 0.82%   |
| Intel Wireless 8260                                               | 3119      | 0.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 2926      | 0.77%   |
| Intel Ethernet Connection (2) I219-V                              | 2923      | 0.76%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 2837      | 0.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2789      | 0.73%   |
| Intel Ethernet Connection I217-LM                                 | 2742      | 0.72%   |
| Intel Wireless 3165                                               | 2716      | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 2519      | 0.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2488      | 0.65%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 2346      | 0.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2340      | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2190      | 0.57%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2005      | 0.52%   |
| Broadcom BCM43142 802.11b/g/n                                     | 1999      | 0.52%   |
| Intel Ethernet Controller I225-V                                  | 1977      | 0.52%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 1911      | 0.5%    |
| Intel 82579V Gigabit Network Connection                           | 1889      | 0.49%   |
| Intel Wireless-AC 9260                                            | 1861      | 0.49%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 1823      | 0.48%   |
| Ralink MT7601U Wireless Adapter                                   | 1820      | 0.48%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 1741      | 0.46%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 1702      | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 69679     | 40.96%  |
| Qualcomm Atheros                      | 31785     | 18.68%  |
| Realtek Semiconductor                 | 28835     | 16.95%  |
| Broadcom                              | 12927     | 7.6%    |
| Ralink Technology                     | 4350      | 2.56%   |
| Ralink                                | 3670      | 2.16%   |
| MediaTek                              | 3461      | 2.03%   |
| TP-Link                               | 2962      | 1.74%   |
| Broadcom Limited                      | 2838      | 1.67%   |
| Qualcomm Atheros Communications       | 1263      | 0.74%   |
| NetGear                               | 859       | 0.5%    |
| D-Link                                | 833       | 0.49%   |
| ASUSTek Computer                      | 746       | 0.44%   |
| Sierra Wireless                       | 728       | 0.43%   |
| Microsoft                             | 656       | 0.39%   |
| D-Link System                         | 484       | 0.28%   |
| Dell                                  | 479       | 0.28%   |
| Marvell Technology Group              | 467       | 0.27%   |
| Edimax Technology                     | 407       | 0.24%   |
| Linksys                               | 304       | 0.18%   |
| Qualcomm                              | 302       | 0.18%   |
| Belkin Components                     | 295       | 0.17%   |
| Fibocom                               | 175       | 0.1%    |
| IMC Networks                          | 169       | 0.1%    |
| AVM                                   | 155       | 0.09%   |
| Ericsson Business Mobile Networks     | 130       | 0.08%   |
| Hewlett-Packard                       | 109       | 0.06%   |
| Sitecom Europe                        | 83        | 0.05%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 81        | 0.05%   |
| ZyDAS                                 | 71        | 0.04%   |
| ZyXEL Communications                  | 68        | 0.04%   |
| Gemtek                                | 67        | 0.04%   |
| Mercucys                              | 63        | 0.04%   |
| Micro Star International              | 56        | 0.03%   |
| BUFFALO                               | 52        | 0.03%   |
| Wilocity                              | 40        | 0.02%   |
| Tenda                                 | 37        | 0.02%   |
| Wacom                                 | 32        | 0.02%   |
| TRENDnet                              | 31        | 0.02%   |
| Xiaomi                                | 28        | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 8043      | 4.69%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 5621      | 3.28%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 5468      | 3.19%   |
| Intel Wireless 8265 / 8275                                              | 5392      | 3.14%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5325      | 3.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 4932      | 2.88%   |
| Intel Wireless 7265                                                     | 4167      | 2.43%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 4154      | 2.42%   |
| Intel Wi-Fi 6 AX201                                                     | 4063      | 2.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 3946      | 2.3%    |
| Intel Wireless 7260                                                     | 3898      | 2.27%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 3141      | 1.83%   |
| Intel Wireless 8260                                                     | 3119      | 1.82%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 2926      | 1.71%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 2837      | 1.65%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 2789      | 1.63%   |
| Intel Wireless 3165                                                     | 2716      | 1.58%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 2519      | 1.47%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 2488      | 1.45%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2346      | 1.37%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2340      | 1.36%   |
| Broadcom BCM43142 802.11b/g/n                                           | 1999      | 1.17%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 1911      | 1.11%   |
| Intel Wireless-AC 9260                                                  | 1861      | 1.09%   |
| Ralink MT7601U Wireless Adapter                                         | 1820      | 1.06%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 1797      | 1.05%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 1741      | 1.02%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1702      | 0.99%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 1651      | 0.96%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 1595      | 0.93%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 1591      | 0.93%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 1590      | 0.93%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 1588      | 0.93%   |
| Intel Wireless 3160                                                     | 1512      | 0.88%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1470      | 0.86%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 1251      | 0.73%   |
| Realtek 802.11ac NIC                                                    | 1246      | 0.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 1172      | 0.68%   |
| Intel WiFi Link 5100                                                    | 1164      | 0.68%   |
| Intel Centrino Ultimate-N 6300                                          | 1153      | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 107817    | 53.25%  |
| Intel                             | 48660     | 24.03%  |
| Qualcomm Atheros                  | 12916     | 6.38%   |
| Broadcom                          | 9007      | 4.45%   |
| Nvidia                            | 4243      | 2.1%    |
| Marvell Technology Group          | 3991      | 1.97%   |
| Broadcom Limited                  | 1973      | 0.97%   |
| ASIX Electronics                  | 1615      | 0.8%    |
| Samsung Electronics               | 1568      | 0.77%   |
| Xiaomi                            | 929       | 0.46%   |
| JMicron Technology                | 733       | 0.36%   |
| Huawei Technologies               | 731       | 0.36%   |
| VIA Technologies                  | 694       | 0.34%   |
| DisplayLink                       | 657       | 0.32%   |
| Lenovo                            | 626       | 0.31%   |
| Aquantia                          | 583       | 0.29%   |
| Silicon Integrated Systems [SiS]  | 461       | 0.23%   |
| MediaTek                          | 330       | 0.16%   |
| TP-Link                           | 322       | 0.16%   |
| D-Link System                     | 289       | 0.14%   |
| Attansic Technology               | 274       | 0.14%   |
| Qualcomm                          | 270       | 0.13%   |
| OPPO Electronics                  | 255       | 0.13%   |
| Google                            | 249       | 0.12%   |
| ZTE WCDMA Technologies MSM        | 234       | 0.12%   |
| Motorola PCS                      | 214       | 0.11%   |
| Apple                             | 204       | 0.1%    |
| Microchip Technology              | 201       | 0.1%    |
| Mellanox Technologies             | 180       | 0.09%   |
| ICS Advent                        | 175       | 0.09%   |
| 3Com                              | 139       | 0.07%   |
| Hewlett-Packard                   | 134       | 0.07%   |
| Sundance Technology Inc / IC Plus | 112       | 0.06%   |
| OnePlus Technology (Shenzhen)     | 94        | 0.05%   |
| IBM                               | 89        | 0.04%   |
| HTC (High Tech Computer)          | 89        | 0.04%   |
| Microsoft                         | 87        | 0.04%   |
| American Megatrends               | 77        | 0.04%   |
| T & A Mobile Phones               | 76        | 0.04%   |
| LG Electronics                    | 61        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 80768     | 39.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15574     | 7.53%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7237      | 3.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4850      | 2.34%   |
| Intel I211 Gigabit Network Connection                             | 4376      | 2.11%   |
| Realtek RTL8125 2.5GbE Controller                                 | 3891      | 1.88%   |
| Intel Ethernet Connection (2) I219-V                              | 2923      | 1.41%   |
| Intel Ethernet Connection I217-LM                                 | 2742      | 1.32%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 2190      | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2005      | 0.97%   |
| Intel Ethernet Controller I225-V                                  | 1977      | 0.96%   |
| Intel 82579V Gigabit Network Connection                           | 1889      | 0.91%   |
| Nvidia MCP61 Ethernet                                             | 1618      | 0.78%   |
| Intel Ethernet Connection (7) I219-V                              | 1527      | 0.74%   |
| Intel Ethernet Connection (4) I219-LM                             | 1457      | 0.7%    |
| Intel 82577LM Gigabit Network Connection                          | 1323      | 0.64%   |
| Intel Ethernet Connection (2) I219-LM                             | 1307      | 0.63%   |
| Intel Ethernet Connection I219-LM                                 | 1306      | 0.63%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1286      | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1212      | 0.59%   |
| Intel Ethernet Connection I218-LM                                 | 1151      | 0.56%   |
| Intel Ethernet Connection I217-V                                  | 1147      | 0.55%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 1118      | 0.54%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1117      | 0.54%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 1029      | 0.5%    |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 1020      | 0.49%   |
| Intel I210 Gigabit Network Connection                             | 1020      | 0.49%   |
| Nvidia MCP79 Ethernet                                             | 1010      | 0.49%   |
| Intel Ethernet Connection (3) I218-LM                             | 985       | 0.48%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 984       | 0.48%   |
| Intel Ethernet Connection (4) I219-V                              | 976       | 0.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 967       | 0.47%   |
| Intel 82574L Gigabit Network Connection                           | 963       | 0.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 940       | 0.45%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 926       | 0.45%   |
| Intel 82567LM Gigabit Network Connection                          | 926       | 0.45%   |
| Intel Ethernet Connection (2) I218-V                              | 904       | 0.44%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 868       | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                             | 865       | 0.42%   |
| Intel Ethernet Connection (6) I219-V                              | 865       | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 189700    | 53.52%  |
| WiFi     | 160785    | 45.36%  |
| Modem    | 3446      | 0.97%   |
| Unknown  | 539       | 0.15%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 123933    | 55.03%  |
| Ethernet | 101208    | 44.94%  |
| Unknown  | 63        | 0.03%   |
| Modem    | 20        | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 117854    | 53.8%   |
| 1     | 90405     | 41.27%  |
| 0     | 4972      | 2.27%   |
| 3     | 4149      | 1.89%   |
| 4     | 1033      | 0.47%   |
| 6     | 227       | 0.1%    |
| 5     | 215       | 0.1%    |
| 8     | 77        | 0.04%   |
| 7     | 38        | 0.02%   |
| 10    | 22        | 0.01%   |
| 12    | 11        | 0.01%   |
| 9     | 10        | 0.005%  |
| 13    | 4         | 0.002%  |
| 20    | 3         | 0.001%  |
| 18    | 3         | 0.001%  |
| 11    | 3         | 0.001%  |
| 132   | 2         | 0.001%  |
| 33    | 2         | 0.001%  |
| 17    | 2         | 0.001%  |
| 16    | 2         | 0.001%  |
| 14    | 2         | 0.001%  |
| 66    | 1         | 0.0005% |
| 42    | 1         | 0.0005% |
| 32    | 1         | 0.0005% |
| 22    | 1         | 0.0005% |
| 21    | 1         | 0.0005% |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 176962    | 79.13%  |
| Yes     | 38603     | 17.26%  |
| Unknown | 8071      | 3.61%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 54850     | 44.07%  |
| Realtek Semiconductor           | 12093     | 9.72%   |
| Qualcomm Atheros Communications | 10689     | 8.59%   |
| Cambridge Silicon Radio         | 7505      | 6.03%   |
| Broadcom                        | 6802      | 5.46%   |
| IMC Networks                    | 6346      | 5.1%    |
| Apple                           | 4733      | 3.8%    |
| Lite-On Technology              | 4728      | 3.8%    |
| Foxconn / Hon Hai               | 3966      | 3.19%   |
| ASUSTek Computer                | 2325      | 1.87%   |
| Dell                            | 1772      | 1.42%   |
| Hewlett-Packard                 | 1442      | 1.16%   |
| Ralink                          | 1092      | 0.88%   |
| Toshiba                         | 1082      | 0.87%   |
| MediaTek                        | 820       | 0.66%   |
| Realtek                         | 736       | 0.59%   |
| Foxconn International           | 480       | 0.39%   |
| Marvell Semiconductor           | 425       | 0.34%   |
| Alps Electric                   | 363       | 0.29%   |
| TP-Link                         | 291       | 0.23%   |
| Ralink Technology               | 251       | 0.2%    |
| Integrated System Solution      | 200       | 0.16%   |
| Belkin Components               | 124       | 0.1%    |
| Dynex                           | 117       | 0.09%   |
| Askey Computer                  | 113       | 0.09%   |
| USI                             | 108       | 0.09%   |
| Edimax Technology               | 108       | 0.09%   |
| Chicony Electronics             | 94        | 0.08%   |
| Micro Star International        | 93        | 0.07%   |
| Taiyo Yuden                     | 80        | 0.06%   |
| Opticis                         | 67        | 0.05%   |
| Qcom                            | 64        | 0.05%   |
| HTC (High Tech Computer)        | 60        | 0.05%   |
| Smart Modular Technologies      | 49        | 0.04%   |
| Logitech                        | 47        | 0.04%   |
| Conwise Technology              | 39        | 0.03%   |
| Unknown                         | 36        | 0.03%   |
| Fujitsu                         | 35        | 0.03%   |
| Actions                         | 34        | 0.03%   |
| ISSC                            | 30        | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 20238     | 16.24%  |
| Intel AX201 Bluetooth                               | 9112      | 7.31%   |
| Intel AX200 Bluetooth                               | 7670      | 6.16%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 7645      | 6.14%   |
| Realtek Bluetooth Radio                             | 7555      | 6.06%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 7504      | 6.02%   |
| Qualcomm Atheros  Bluetooth Device                  | 4746      | 3.81%   |
| Realtek  Bluetooth 4.2 Adapter                      | 2981      | 2.39%   |
| Intel Bluetooth Device                              | 2798      | 2.25%   |
| IMC Networks Bluetooth Radio                        | 2753      | 2.21%   |
| Intel Wireless-AC 3168 Bluetooth                    | 2274      | 1.82%   |
| Apple Bluetooth Host Controller                     | 1873      | 1.5%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 1840      | 1.48%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 1768      | 1.42%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 1733      | 1.39%   |
| Intel AX210 Bluetooth                               | 1632      | 1.31%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 1605      | 1.29%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 1595      | 1.28%   |
| IMC Networks Bluetooth Device                       | 1405      | 1.13%   |
| Foxconn / Hon Hai Bluetooth Device                  | 1270      | 1.02%   |
| Apple Bluetooth USB Host Controller                 | 1240      | 1%      |
| Lite-On Bluetooth Device                            | 1204      | 0.97%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 1127      | 0.9%    |
| Ralink RT3290 Bluetooth                             | 1092      | 0.88%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 1048      | 0.84%   |
| IMC Networks Wireless_Device                        | 979       | 0.79%   |
| Foxconn / Hon Hai Wireless_Device                   | 917       | 0.74%   |
| Lite-On Atheros AR3012 Bluetooth                    | 884       | 0.71%   |
| Broadcom BCM2045B (BDC-2.1)                         | 877       | 0.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 862       | 0.69%   |
| MediaTek Wireless_Device                            | 762       | 0.61%   |
| HP Broadcom 2070 Bluetooth Combo                    | 757       | 0.61%   |
| Realtek Bluetooth Radio                             | 736       | 0.59%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 670       | 0.54%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 640       | 0.51%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 618       | 0.5%    |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 612       | 0.49%   |
| Dell DW375 Bluetooth Module                         | 595       | 0.48%   |
| Realtek RTL8723B Bluetooth                          | 565       | 0.45%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 533       | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 153819    | 51.87%  |
| AMD                              | 62539     | 21.09%  |
| Nvidia                           | 51031     | 17.21%  |
| C-Media Electronics              | 4815      | 1.62%   |
| Logitech                         | 2126      | 0.72%   |
| Creative Labs                    | 2021      | 0.68%   |
| Texas Instruments                | 1035      | 0.35%   |
| JMTek                            | 948       | 0.32%   |
| Realtek Semiconductor            | 894       | 0.3%    |
| GN Netcom                        | 861       | 0.29%   |
| Generalplus Technology           | 766       | 0.26%   |
| VIA Technologies                 | 759       | 0.26%   |
| Kingston Technology              | 758       | 0.26%   |
| Creative Technology              | 720       | 0.24%   |
| ASUSTek Computer                 | 676       | 0.23%   |
| Lenovo                           | 660       | 0.22%   |
| Plantronics                      | 607       | 0.2%    |
| Focusrite-Novation               | 590       | 0.2%    |
| Silicon Integrated Systems [SiS] | 582       | 0.2%    |
| Razer USA                        | 576       | 0.19%   |
| SteelSeries ApS                  | 536       | 0.18%   |
| Corsair                          | 517       | 0.17%   |
| Hewlett-Packard                  | 307       | 0.1%    |
| Blue Microphones                 | 307       | 0.1%    |
| Apple                            | 303       | 0.1%    |
| Micro Star International         | 277       | 0.09%   |
| Sony                             | 239       | 0.08%   |
| Tenx Technology                  | 226       | 0.08%   |
| BEHRINGER International          | 210       | 0.07%   |
| Samson Technologies              | 209       | 0.07%   |
| Dell                             | 205       | 0.07%   |
| Sennheiser Communications        | 185       | 0.06%   |
| M-Audio                          | 177       | 0.06%   |
| Yamaha                           | 170       | 0.06%   |
| GYROCOM C&C                      | 165       | 0.06%   |
| Microsoft                        | 156       | 0.05%   |
| RODE Microphones                 | 149       | 0.05%   |
| XMOS                             | 143       | 0.05%   |
| DSEA A/S                         | 135       | 0.05%   |
| SAVITECH                         | 123       | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 16084     | 4.58%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 15897     | 4.53%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 15139     | 4.31%   |
| Intel Sunrise Point-LP HD Audio                                            | 15070     | 4.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10186     | 2.9%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 9975      | 2.84%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 8673      | 2.47%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 7647      | 2.18%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 7608      | 2.17%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7375      | 2.1%    |
| AMD FCH Azalia Controller                                                  | 7355      | 2.1%    |
| Intel Cannon Lake PCH cAVS                                                 | 7154      | 2.04%   |
| AMD Starship/Matisse HD Audio Controller                                   | 7048      | 2.01%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 7011      | 2%      |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5695      | 1.62%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5688      | 1.62%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5371      | 1.53%   |
| Intel 8 Series HD Audio Controller                                         | 5202      | 1.48%   |
| Intel Haswell-ULT HD Audio Controller                                      | 5174      | 1.47%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 4293      | 1.22%   |
| Intel Broadwell-U Audio Controller                                         | 4226      | 1.2%    |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4109      | 1.17%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4097      | 1.17%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4011      | 1.14%   |
| Intel 200 Series PCH HD Audio                                              | 3844      | 1.1%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3784      | 1.08%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3783      | 1.08%   |
| Nvidia GF108 High Definition Audio Controller                              | 3576      | 1.02%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3463      | 0.99%   |
| AMD Kabini HDMI/DP Audio                                                   | 3251      | 0.93%   |
| Intel Comet Lake PCH-LP cAVS                                               | 3232      | 0.92%   |
| Nvidia High Definition Audio Controller                                    | 3062      | 0.87%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2957      | 0.84%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 2794      | 0.8%    |
| Intel Comet Lake PCH cAVS                                                  | 2627      | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2617      | 0.75%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 2551      | 0.73%   |
| Nvidia GP106 High Definition Audio Controller                              | 2525      | 0.72%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2510      | 0.72%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 2484      | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 29770     | 20.2%   |
| SK hynix            | 23910     | 16.22%  |
| Unknown             | 20335     | 13.8%   |
| Kingston            | 17805     | 12.08%  |
| Micron Technology   | 12580     | 8.54%   |
| Crucial             | 8142      | 5.52%   |
| Corsair             | 6884      | 4.67%   |
| G.Skill             | 4305      | 2.92%   |
| A-DATA Technology   | 2901      | 1.97%   |
| Elpida              | 2606      | 1.77%   |
| Ramaxel Technology  | 2488      | 1.69%   |
| Nanya Technology    | 2103      | 1.43%   |
| Unknown (ABCD)      | 1131      | 0.77%   |
| Patriot             | 1116      | 0.76%   |
| Team                | 971       | 0.66%   |
| Unknown             | 885       | 0.6%    |
| Smart               | 814       | 0.55%   |
| Transcend           | 653       | 0.44%   |
| AMD                 | 582       | 0.39%   |
| GOODRAM             | 567       | 0.38%   |
| Apacer              | 396       | 0.27%   |
| ASint Technology    | 342       | 0.23%   |
| Goldkey             | 287       | 0.19%   |
| Silicon Power       | 266       | 0.18%   |
| Kingmax             | 257       | 0.17%   |
| Teikon              | 214       | 0.15%   |
| Qimonda             | 211       | 0.14%   |
| 48spaces            | 195       | 0.13%   |
| PNY                 | 191       | 0.13%   |
| Avant               | 181       | 0.12%   |
| Unifosa             | 166       | 0.11%   |
| GeIL                | 163       | 0.11%   |
| SHARETRONIC         | 128       | 0.09%   |
| Smart Brazil        | 126       | 0.09%   |
| Foxline             | 121       | 0.08%   |
| Kllisre             | 119       | 0.08%   |
| Hewlett-Packard     | 119       | 0.08%   |
| Qumo                | 115       | 0.08%   |
| CSX                 | 115       | 0.08%   |
| Timetec             | 110       | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1067      | 0.66%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1051      | 0.65%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1010      | 0.63%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 932       | 0.58%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 930       | 0.58%   |
| Unknown                                                          | 885       | 0.55%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 883       | 0.55%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 879       | 0.55%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 869       | 0.54%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 813       | 0.51%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 717       | 0.45%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 715       | 0.45%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 701       | 0.44%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 643       | 0.4%    |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 641       | 0.4%    |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 619       | 0.39%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 615       | 0.38%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 596       | 0.37%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 582       | 0.36%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 575       | 0.36%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 537       | 0.33%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 536       | 0.33%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 527       | 0.33%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 526       | 0.33%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 521       | 0.32%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 515       | 0.32%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 508       | 0.32%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM 4199MT/s                 | 506       | 0.32%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 498       | 0.31%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 498       | 0.31%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 496       | 0.31%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 495       | 0.31%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 493       | 0.31%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 478       | 0.3%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 478       | 0.3%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 476       | 0.3%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 456       | 0.28%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 454       | 0.28%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 447       | 0.28%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 427       | 0.27%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind            | Computers | Percent |
|-----------------|-----------|---------|
| DDR4            | 49885     | 39.08%  |
| DDR3            | 46320     | 36.29%  |
| DDR2            | 9229      | 7.23%   |
| Unknown         | 6046      | 4.74%   |
| SDRAM           | 5304      | 4.16%   |
| LPDDR4          | 4012      | 3.14%   |
| LPDDR3          | 2511      | 1.97%   |
| DDR5            | 1560      | 1.22%   |
| DDR             | 1477      | 1.16%   |
| LPDDR5          | 830       | 0.65%   |
| DRAM            | 439       | 0.34%   |
| RAM             | 7         | 0.01%   |
| EEPROM          | 7         | 0.01%   |
| DDR2 FB-DIMM    | 4         | 0.003%  |
| Logical non-vol | 3         | 0.002%  |
| SRAM            | 1         | 0.001%  |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| SODIMM          | 69028     | 54.63%  |
| DIMM            | 49185     | 38.92%  |
| Row Of Chips    | 6967      | 5.51%   |
| Chip            | 521       | 0.41%   |
| Unknown         | 429       | 0.34%   |
| FB-DIMM         | 122       | 0.1%    |
| RIMM            | 101       | 0.08%   |
| Proprietary Car | 5         | 0.004%  |
| DIP             | 1         | 0.001%  |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 8192    | 45518     | 32.17%  |
| 4096    | 40407     | 28.56%  |
| 2048    | 24370     | 17.23%  |
| 16384   | 16438     | 11.62%  |
| 1024    | 8593      | 6.07%   |
| 32768   | 4153      | 2.94%   |
| 512     | 1473      | 1.04%   |
| 256     | 277       | 0.2%    |
| 65536   | 107       | 0.08%   |
| 1536    | 22        | 0.02%   |
| 128     | 18        | 0.01%   |
| Unknown | 18        | 0.01%   |
| 49152   | 11        | 0.01%   |
| 3072    | 8         | 0.01%   |
| 64      | 8         | 0.01%   |
| 12288   | 7         | 0.005%  |
| 32      | 7         | 0.005%  |
| 16      | 7         | 0.005%  |
| 1       | 7         | 0.005%  |
| 6144    | 5         | 0.004%  |
| 129408  | 4         | 0.003%  |
| 131072  | 3         | 0.002%  |
| 258496  | 1         | 0.001%  |
| 32767   | 1         | 0.001%  |
| 24576   | 1         | 0.001%  |
| 16315   | 1         | 0.001%  |
| 15616   | 1         | 0.001%  |
| 12333   | 1         | 0.001%  |
| 8072    | 1         | 0.001%  |
| 384     | 1         | 0.001%  |
| 232     | 1         | 0.001%  |
| 13      | 1         | 0.001%  |
| 8       | 1         | 0.001%  |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 28698     | 20.61%  |
| 3200    | 16611     | 11.93%  |
| 2667    | 16416     | 11.79%  |
| 1333    | 11607     | 8.34%   |
| 2400    | 8752      | 6.29%   |
| 2133    | 5953      | 4.28%   |
| 1334    | 5428      | 3.9%    |
| 800     | 5208      | 3.74%   |
| 667     | 4986      | 3.58%   |
| Unknown | 4744      | 3.41%   |
| 3600    | 2809      | 2.02%   |
| 1867    | 2436      | 1.75%   |
| 1067    | 1914      | 1.37%   |
| 4267    | 1497      | 1.08%   |
| 1066    | 1444      | 1.04%   |
| 3266    | 1348      | 0.97%   |
| 4800    | 1125      | 0.81%   |
| 4199    | 1090      | 0.78%   |
| 1866    | 1059      | 0.76%   |
| 533     | 1007      | 0.72%   |
| 3733    | 926       | 0.67%   |
| 2666    | 868       | 0.62%   |
| 6400    | 857       | 0.62%   |
| 3000    | 855       | 0.61%   |
| 400     | 853       | 0.61%   |
| 2933    | 817       | 0.59%   |
| 3400    | 799       | 0.57%   |
| 1800    | 791       | 0.57%   |
| 2048    | 755       | 0.54%   |
| 333     | 493       | 0.35%   |
| 975     | 442       | 0.32%   |
| 3800    | 431       | 0.31%   |
| 3533    | 378       | 0.27%   |
| 2800    | 375       | 0.27%   |
| 3466    | 363       | 0.26%   |
| 3866    | 353       | 0.25%   |
| 8400    | 350       | 0.25%   |
| 4266    | 340       | 0.24%   |
| 3666    | 210       | 0.15%   |
| 1639    | 204       | 0.15%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Hewlett-Packard                 | 2402      | 34.36%  |
| Canon                           | 1218      | 17.42%  |
| Brother Industries              | 1049      | 15.01%  |
| Samsung Electronics             | 820       | 11.73%  |
| Seiko Epson                     | 639       | 9.14%   |
| Xerox                           | 111       | 1.59%   |
| Prolific Technology             | 88        | 1.26%   |
| Lexmark International           | 72        | 1.03%   |
| Dymo-CoStar                     | 72        | 1.03%   |
| Pantum                          | 70        | 1%      |
| Kyocera                         | 70        | 1%      |
| QinHeng Electronics             | 59        | 0.84%   |
| Ricoh                           | 50        | 0.72%   |
| Panasonic (Matsushita)          | 48        | 0.69%   |
| STMicroelectronics              | 27        | 0.39%   |
| Zebra                           | 26        | 0.37%   |
| Oki Data                        | 20        | 0.29%   |
| Dell                            | 19        | 0.27%   |
| Fuji Xerox                      | 13        | 0.19%   |
| Apple                           | 10        | 0.14%   |
| Konica Minolta                  | 8         | 0.11%   |
| TSC Auto ID Technology          | 6         | 0.09%   |
| MiiiW                           | 6         | 0.09%   |
| Xiaomi                          | 5         | 0.07%   |
| Star Micronics                  | 5         | 0.07%   |
| Citizen                         | 5         | 0.07%   |
| NXP Semiconductors              | 4         | 0.06%   |
| Datamax-O'Neil                  | 4         | 0.06%   |
| Custom Engineering SPA          | 4         | 0.06%   |
| WinChipHead                     | 3         | 0.04%   |
| Sharp                           | 3         | 0.04%   |
| Samsung Info. Systems America   | 3         | 0.04%   |
| Magic Control Technology        | 3         | 0.04%   |
| ICS Advent                      | 3         | 0.04%   |
| cab Produkttechnik GmbH & Co KG | 3         | 0.04%   |
| BIXOLON                         | 3         | 0.04%   |
| BESTEASY                        | 3         | 0.04%   |
| ATEN International              | 3         | 0.04%   |
| Zhuhai Poskey Technology        | 2         | 0.03%   |
| Toshiba TEC                     | 2         | 0.03%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                | Computers | Percent |
|--------------------------------------|-----------|---------|
| HP LaserJet 1020                     | 128       | 1.81%   |
| HP LaserJet 1018                     | 96        | 1.35%   |
| Prolific PL2305 Parallel Port        | 88        | 1.24%   |
| Samsung M2020 Series                 | 83        | 1.17%   |
| HP DeskJet 2600 series               | 82        | 1.16%   |
| HP LaserJet P1102                    | 79        | 1.11%   |
| Samsung M2070 Series                 | 69        | 0.97%   |
| HP DeskJet 2130 series               | 68        | 0.96%   |
| Canon PIXMA MG2500 Series            | 68        | 0.96%   |
| Brother Printer                      | 67        | 0.95%   |
| Samsung SCX-4200 series              | 64        | 0.9%    |
| Seiko Epson Printer                  | 62        | 0.87%   |
| QinHeng CH340S                       | 59        | 0.83%   |
| Samsung SCX-3400 Series              | 58        | 0.82%   |
| HP LaserJet P1005                    | 56        | 0.79%   |
| Canon LBP2900                        | 55        | 0.78%   |
| HP ENVY 4520 series                  | 53        | 0.75%   |
| HP DeskJet 2700 series               | 51        | 0.72%   |
| HP DeskJet 3630 series               | 46        | 0.65%   |
| HP Deskjet 2050 J510                 | 46        | 0.65%   |
| Brother HL-2030 Laser Printer        | 46        | 0.65%   |
| HP LaserJet 1010                     | 45        | 0.64%   |
| Samsung ML-1640 Series Laser Printer | 44        | 0.62%   |
| Canon PIXMA MG3600 Series            | 41        | 0.58%   |
| Samsung SCX-3200 Series              | 40        | 0.56%   |
| Canon PIXMA MX920 Series             | 40        | 0.56%   |
| Brother HL-1110 series               | 39        | 0.55%   |
| Seiko Epson ET-2710 Series           | 37        | 0.52%   |
| Samsung ML-216x Series Laser Printer | 36        | 0.51%   |
| Canon LiDE 400                       | 36        | 0.51%   |
| Canon LiDE 300                       | 36        | 0.51%   |
| HP Deskjet 2540 series               | 35        | 0.49%   |
| HP LaserJet 1200                     | 34        | 0.48%   |
| HP Deskjet 1050 J410                 | 34        | 0.48%   |
| Canon MF4410                         | 34        | 0.48%   |
| Canon iP7200 series                  | 34        | 0.48%   |
| HP LaserJet Professional P1102w      | 33        | 0.47%   |
| Canon MF3010                         | 33        | 0.47%   |
| Panasonic (Matsushita) KX-MB1500RU   | 32        | 0.45%   |
| HP ENVY 5000 series                  | 32        | 0.45%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor                                         | Computers | Percent |
|------------------------------------------------|-----------|---------|
| Canon                                          | 803       | 51.81%  |
| Seiko Epson                                    | 339       | 21.87%  |
| Hewlett-Packard                                | 204       | 13.16%  |
| Mustek Systems                                 | 89        | 5.74%   |
| Ultima Electronics                             | 29        | 1.87%   |
| Acer Peripherals (now BenQ)                    | 25        | 1.61%   |
| AGFA-Gevaert NV                                | 17        | 1.1%    |
| Plustek                                        | 11        | 0.71%   |
| KYE Systems (Mouse Systems)                    | 10        | 0.65%   |
| Microtek International                         | 4         | 0.26%   |
| Fujitsu                                        | 4         | 0.26%   |
| Visioneer                                      | 2         | 0.13%   |
| UMAX                                           | 2         | 0.13%   |
| Siemens Information and Communication Products | 2         | 0.13%   |
| Canon Electronics                              | 2         | 0.13%   |
| Avision                                        | 2         | 0.13%   |
| Syscan                                         | 1         | 0.06%   |
| Salix Technology                               | 1         | 0.06%   |
| Papillon Systems                               | 1         | 0.06%   |
| Nikon                                          | 1         | 0.06%   |
| Minolta                                        | 1         | 0.06%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 122       | 7.85%   |
| Canon CanoScan LIDE 25                                                                | 94        | 6.05%   |
| Canon CanoScan LiDE 210                                                               | 88        | 5.66%   |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 83        | 5.34%   |
| Canon CanoScan LiDE 220                                                               | 73        | 4.69%   |
| Canon CanoScan LiDE 120                                                               | 58        | 3.73%   |
| Canon CanoScan LiDE 100                                                               | 46        | 2.96%   |
| HP ScanJet 2400c                                                                      | 39        | 2.51%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 38        | 2.44%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 29        | 1.86%   |
| Canon CanoScan LiDE 60                                                                | 28        | 1.8%    |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 27        | 1.74%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 26        | 1.67%   |
| Seiko Epson GT-X770 [Perfection V500]                                                 | 26        | 1.67%   |
| Canon CanoScan LiDE 200                                                               | 26        | 1.67%   |
| Seiko Epson GT-X820 [Perfection V600 Photo]                                           | 24        | 1.54%   |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 23        | 1.48%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 21        | 1.35%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 21        | 1.35%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 21        | 1.35%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 15        | 0.96%   |
| Mustek Systems SNAPSCAN e22                                                           | 15        | 0.96%   |
| Canon CanoScan LiDE 90                                                                | 14        | 0.9%    |
| Canon CanoScan LiDE 700F                                                              | 14        | 0.9%    |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 13        | 0.84%   |
| Seiko Epson GT-7400U [Perfection 1270]                                                | 13        | 0.84%   |
| Canon CanoScan N650U/N656U                                                            | 13        | 0.84%   |
| Canon CanoScan 4400F                                                                  | 13        | 0.84%   |
| Seiko Epson Scanner                                                                   | 12        | 0.77%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo]                               | 12        | 0.77%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 11        | 0.71%   |
| Mustek Systems ScanExpress 1200 UB                                                    | 11        | 0.71%   |
| Seiko Epson GT-F670 [Perfection V200 Photo]                                           | 9         | 0.58%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 9         | 0.58%   |
| Mustek Systems BearPaw 2400 CU Plus                                                   | 9         | 0.58%   |
| HP ScanJet 3800c                                                                      | 9         | 0.58%   |
| HP Scanjet 200                                                                        | 9         | 0.58%   |
| Canon CanoScan LiDE 70                                                                | 9         | 0.58%   |
| Canon CanoScan 9000F Mark II                                                          | 9         | 0.58%   |
| Seiko Epson GT-F700 [Perfection V350]                                                 | 8         | 0.51%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 27145     | 21.35%  |
| IMC Networks                           | 11406     | 8.97%   |
| Microdia                               | 10535     | 8.29%   |
| Realtek Semiconductor                  | 9332      | 7.34%   |
| Logitech                               | 7522      | 5.92%   |
| Bison Electronics                      | 6851      | 5.39%   |
| Sunplus Innovation Technology          | 6540      | 5.14%   |
| Quanta                                 | 5716      | 4.5%    |
| Cheng Uei Precision Industry (Foxlink) | 4471      | 3.52%   |
| Suyin                                  | 4427      | 3.48%   |
| Apple                                  | 3808      | 3%      |
| Syntek                                 | 3001      | 2.36%   |
| Acer                                   | 2492      | 1.96%   |
| Lite-On Technology                     | 2362      | 1.86%   |
| Silicon Motion                         | 2257      | 1.78%   |
| Alcor Micro                            | 1817      | 1.43%   |
| Z-Star Microelectronics                | 1560      | 1.23%   |
| Luxvisions Innotech Limited            | 1447      | 1.14%   |
| Microsoft                              | 1385      | 1.09%   |
| Samsung Electronics                    | 1231      | 0.97%   |
| Ricoh                                  | 1131      | 0.89%   |
| Lenovo                                 | 693       | 0.55%   |
| Sonix Technology                       | 605       | 0.48%   |
| ALi                                    | 520       | 0.41%   |
| Importek                               | 470       | 0.37%   |
| Generalplus Technology                 | 464       | 0.36%   |
| Primax Electronics                     | 409       | 0.32%   |
| KYE Systems (Mouse Systems)            | 370       | 0.29%   |
| GEMBIRD                                | 364       | 0.29%   |
| SunplusIT                              | 324       | 0.25%   |
| Cubeternet                             | 310       | 0.24%   |
| Creative Technology                    | 310       | 0.24%   |
| DigiTech                               | 279       | 0.22%   |
| ARC International                      | 264       | 0.21%   |
| OmniVision Technologies                | 238       | 0.19%   |
| Aveo Technology                        | 221       | 0.17%   |
| Pixart Imaging                         | 202       | 0.16%   |
| MacroSilicon                           | 202       | 0.16%   |
| Arkmicro Technologies                  | 200       | 0.16%   |
| Jieli Technology                       | 187       | 0.15%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Chicony Integrated Camera               | 4780      | 3.73%   |
| Microdia Integrated_Webcam_HD           | 3908      | 3.05%   |
| Realtek Integrated_Webcam_HD            | 2951      | 2.3%    |
| IMC Networks USB2.0 HD UVC WebCam       | 2696      | 2.11%   |
| IMC Networks Integrated Camera          | 2686      | 2.1%    |
| Chicony HD Webcam                       | 2414      | 1.88%   |
| Logitech Webcam C270                    | 1757      | 1.37%   |
| Sunplus Integrated_Webcam_HD            | 1752      | 1.37%   |
| IMC Networks USB2.0 VGA UVC WebCam      | 1700      | 1.33%   |
| Syntek Integrated Camera                | 1510      | 1.18%   |
| Bison Integrated Camera                 | 1397      | 1.09%   |
| Samsung Galaxy series, misc. (MTP mode) | 1207      | 0.94%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X         | 1114      | 0.87%   |
| Logitech HD Pro Webcam C920             | 1110      | 0.87%   |
| Sunplus HD WebCam                       | 1011      | 0.79%   |
| Acer Integrated Camera                  | 998       | 0.78%   |
| Apple Built-in iSight                   | 994       | 0.78%   |
| Quanta HD User Facing                   | 991       | 0.77%   |
| Chicony HP HD Camera                    | 954       | 0.74%   |
| Microdia Integrated Webcam              | 885       | 0.69%   |
| Bison Lenovo EasyCamera                 | 858       | 0.67%   |
| Chicony HP TrueVision HD                | 857       | 0.67%   |
| Chicony USB2.0 HD UVC WebCam            | 846       | 0.66%   |
| Chicony Lenovo EasyCamera               | 834       | 0.65%   |
| Apple FaceTime HD Camera (Built-in)     | 834       | 0.65%   |
| Lite-On Integrated Camera               | 832       | 0.65%   |
| Realtek USB Camera                      | 801       | 0.63%   |
| Chicony USB 2.0 Camera                  | 801       | 0.63%   |
| Chicony HD User Facing                  | 778       | 0.61%   |
| Chicony USB2.0 VGA UVC WebCam           | 776       | 0.61%   |
| Bison HD Webcam                         | 756       | 0.59%   |
| Chicony HP TrueVision HD Camera         | 755       | 0.59%   |
| Chicony EasyCamera                      | 718       | 0.56%   |
| Chicony USB2.0 Camera                   | 713       | 0.56%   |
| Quanta VGA WebCam                       | 703       | 0.55%   |
| Bison Lenovo Integrated Webcam          | 697       | 0.54%   |
| Quanta HP TrueVision HD Camera          | 694       | 0.54%   |
| Chicony TOSHIBA Web Camera - HD         | 678       | 0.53%   |
| Chicony VGA WebCam                      | 651       | 0.51%   |
| Alcor Micro USB 2.0 Camera              | 647       | 0.51%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 7298      | 33.82%  |
| Synaptics                          | 5716      | 26.49%  |
| Shenzhen Goodix Technology         | 3023      | 14.01%  |
| AuthenTec                          | 1477      | 6.84%   |
| Elan Microelectronics              | 1248      | 5.78%   |
| Upek                               | 1213      | 5.62%   |
| LighTuning Technology              | 880       | 4.08%   |
| STMicroelectronics                 | 371       | 1.72%   |
| Realtek USB2.0 Finger Print Bridge | 97        | 0.45%   |
| Samsung Electronics                | 88        | 0.41%   |
| Focal-systems.Corp                 | 88        | 0.41%   |
| DigitalPersona                     | 24        | 0.11%   |
| HOLTEK                             | 20        | 0.09%   |
| Microsoft                          | 13        | 0.06%   |
| Dell                               | 9         | 0.04%   |
| Futronic Technology                | 4         | 0.02%   |
| Next Biometrics                    | 3         | 0.01%   |
| Gingytech                          | 3         | 0.01%   |
| GDMicroelectronics                 | 3         | 0.01%   |
| Suprema                            | 2         | 0.01%   |
| FocalTech                          | 2         | 0.01%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 1721      | 7.97%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1631      | 7.56%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1544      | 7.15%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 1120      | 5.19%   |
| Shenzhen Goodix Fingerprint Reader                                         | 907       | 4.2%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 835       | 3.87%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 771       | 3.57%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 763       | 3.54%   |
| Elan ELAN:Fingerprint                                                      | 697       | 3.23%   |
| Validity Sensors Synaptics WBDI                                            | 596       | 2.76%   |
| Elan ELAN:ARM-M4                                                           | 499       | 2.31%   |
| Validity Sensors VFS491                                                    | 498       | 2.31%   |
| Validity Sensors Fingerprint scanner                                       | 493       | 2.28%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 485       | 2.25%   |
| Shenzhen Goodix FingerPrint                                                | 485       | 2.25%   |
| Synaptics  WBDI                                                            | 460       | 2.13%   |
| AuthenTec AES2810                                                          | 460       | 2.13%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 434       | 2.01%   |
| Synaptics WBDI                                                             | 406       | 1.88%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 382       | 1.77%   |
| STMicroelectronics Fingerprint Reader                                      | 369       | 1.71%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 362       | 1.68%   |
| Synaptics UWP WBDI                                                         | 357       | 1.65%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 352       | 1.63%   |
| Synaptics Fingerprint reader [HP G6]                                       | 343       | 1.59%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 339       | 1.57%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 303       | 1.4%    |
| Validity Sensors Swipe Fingerprint Sensor                                  | 293       | 1.36%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 290       | 1.34%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 262       | 1.21%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 251       | 1.16%   |
| AuthenTec AES1600                                                          | 238       | 1.1%    |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 211       | 0.98%   |
| AuthenTec Fingerprint Sensor                                               | 210       | 0.97%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 184       | 0.85%   |
| Synaptics UWP WBDI Device                                                  | 167       | 0.77%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 149       | 0.69%   |
| LighTuning Fingerprint Reader                                              | 141       | 0.65%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 127       | 0.59%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 119       | 0.55%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 4040      | 45.06%  |
| Alcor Micro                       | 2385      | 26.6%   |
| O2 Micro                          | 654       | 7.3%    |
| Upek                              | 509       | 5.68%   |
| Lenovo                            | 455       | 5.08%   |
| Gemalto (was Gemplus)             | 137       | 1.53%   |
| SCM Microsystems                  | 116       | 1.29%   |
| Advanced Card Systems             | 93        | 1.04%   |
| OmniKey                           | 81        | 0.9%    |
| Realtek Semiconductor             | 62        | 0.69%   |
| Yubico.com                        | 59        | 0.66%   |
| Aladdin Knowledge Systems         | 50        | 0.56%   |
| Reiner SCT Kartensysteme          | 32        | 0.36%   |
| Clay Logic                        | 32        | 0.36%   |
| Cherry                            | 30        | 0.33%   |
| VASCO Data Security International | 27        | 0.3%    |
| Chicony Electronics               | 27        | 0.3%    |
| Aktiv                             | 24        | 0.27%   |
| Bit4id                            | 23        | 0.26%   |
| Hewlett-Packard                   | 19        | 0.21%   |
| Giesecke & Devrient               | 14        | 0.16%   |
| Fujitsu Siemens Computers         | 14        | 0.16%   |
| Aladdin R.D.                      | 14        | 0.16%   |
| Athena Smartcard Solutions        | 10        | 0.11%   |
| Watchdata                         | 7         | 0.08%   |
| C3PO                              | 6         | 0.07%   |
| Purism, SPC                       | 5         | 0.06%   |
| NXP Semiconductors                | 5         | 0.06%   |
| In Focus Systems                  | 5         | 0.06%   |
| Kobil Systems                     | 4         | 0.04%   |
| Feitian Technologies              | 4         | 0.04%   |
| Castles Technology                | 4         | 0.04%   |
| Microchip Technology              | 3         | 0.03%   |
| Jing-Mold Enterprise              | 2         | 0.02%   |
| Avtor                             | 2         | 0.02%   |
| ST-Ericsson                       | 1         | 0.01%   |
| SpringCard                        | 1         | 0.01%   |
| Precise Biometrics                | 1         | 0.01%   |
| Mako Technologies                 | 1         | 0.01%   |
| MagTek                            | 1         | 0.01%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 2335      | 26.03%  |
| Broadcom BCM5880 Secure Applications Processor                               | 1484      | 16.54%  |
| Broadcom 5880                                                                | 951       | 10.6%   |
| Broadcom 58200                                                               | 825       | 9.2%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 747       | 8.33%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 561       | 6.25%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 509       | 5.67%   |
| Lenovo Integrated Smart Card Reader                                          | 450       | 5.02%   |
| O2 Micro Oz776 SmartCard Reader                                              | 93        | 1.04%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 80        | 0.89%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 62        | 0.69%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 54        | 0.6%    |
| Aladdin Knowledge Systems Token JC                                           | 50        | 0.56%   |
| Alcor Micro Watchdata W 1981                                                 | 47        | 0.52%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 47        | 0.52%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 43        | 0.48%   |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 42        | 0.47%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 37        | 0.41%   |
| OmniKey CardMan 3021 / 3121                                                  | 27        | 0.3%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 27        | 0.3%    |
| Clay Logic Nitrokey Pro                                                      | 23        | 0.26%   |
| Aktiv Rutoken lite                                                           | 23        | 0.26%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 21        | 0.23%   |
| Advanced Card Systems ACR122U                                                | 21        | 0.23%   |
| OmniKey CardMan 1021                                                         | 20        | 0.22%   |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 20        | 0.22%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 19        | 0.21%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 19        | 0.21%   |
| Bit4id miniLector EVO                                                        | 19        | 0.21%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 16        | 0.18%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 12        | 0.13%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 12        | 0.13%   |
| Aladdin R.D. JaCarta                                                         | 12        | 0.13%   |
| OmniKey CardMan 4321                                                         | 11        | 0.12%   |
| Advanced Card Systems ACR39U                                                 | 11        | 0.12%   |
| VASCO Data Security International DIGIPASS 870                               | 10        | 0.11%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 10        | 0.11%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 9         | 0.1%    |
| SCM Microsystems SCR331 SmartCard Reader                                     | 9         | 0.1%    |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 9         | 0.1%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 157764    | 70.31%  |
| 1     | 53268     | 23.74%  |
| 2     | 10543     | 4.7%    |
| 3     | 1843      | 0.82%   |
| 4     | 580       | 0.26%   |
| 5     | 205       | 0.09%   |
| 6     | 99        | 0.04%   |
| 7     | 52        | 0.02%   |
| 8     | 27        | 0.01%   |
| 9     | 9         | 0.004%  |
| 10    | 5         | 0.002%  |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 21316     | 26.79%  |
| Graphics card            | 20273     | 25.48%  |
| Net/wireless             | 9675      | 12.16%  |
| Chipcard                 | 7815      | 9.82%   |
| Multimedia controller    | 4742      | 5.96%   |
| Communication controller | 3558      | 4.47%   |
| Bluetooth                | 2261      | 2.84%   |
| Camera                   | 2172      | 2.73%   |
| Unassigned class         | 1767      | 2.22%   |
| Sound                    | 1296      | 1.63%   |
| Storage                  | 1184      | 1.49%   |
| Net/ethernet             | 785       | 0.99%   |
| Card reader              | 729       | 0.92%   |
| Network                  | 456       | 0.57%   |
| Modem                    | 426       | 0.54%   |
| Flash memory             | 266       | 0.33%   |
| Storage/raid             | 212       | 0.27%   |
| Dvb card                 | 162       | 0.2%    |
| Storage/ide              | 137       | 0.17%   |
| Firewire controller      | 123       | 0.15%   |
| Storage/nvme             | 53        | 0.07%   |
| Storage/ata              | 53        | 0.07%   |
| Tv card                  | 42        | 0.05%   |
| Wireless                 | 26        | 0.03%   |
| Video                    | 18        | 0.02%   |
| Unclassified device      | 17        | 0.02%   |

