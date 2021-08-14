Debian 11 - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for Debian 11 (Beta test).

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please submit a probe of your configuration if it's not presented on the page or is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian_11/Desktop/README.md) and [notebooks](/Dist/Debian_11/Notebook/README.md).

Full-feature report is available here: https://linux-hardware.org/?view=trends&rel=debian-11

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
| Dell          | Latitude 7490               | Notebook    | [6ca174eba8](https://linux-hardware.org/?probe=6ca174eba8) | Aug 14, 2021 |
| HP            | 3397                        | Desktop     | [a3425b956c](https://linux-hardware.org/?probe=a3425b956c) | Aug 14, 2021 |
| Dell          | Latitude 7490               | Notebook    | [85cacfa170](https://linux-hardware.org/?probe=85cacfa170) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [cac72ff077](https://linux-hardware.org/?probe=cac72ff077) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [8c489e2c59](https://linux-hardware.org/?probe=8c489e2c59) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [d79905590c](https://linux-hardware.org/?probe=d79905590c) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [7efce8d06b](https://linux-hardware.org/?probe=7efce8d06b) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [c53a0803e7](https://linux-hardware.org/?probe=c53a0803e7) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [410a4b2e26](https://linux-hardware.org/?probe=410a4b2e26) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [cbc9f75923](https://linux-hardware.org/?probe=cbc9f75923) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [4ca322af56](https://linux-hardware.org/?probe=4ca322af56) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [2af4090c36](https://linux-hardware.org/?probe=2af4090c36) | Aug 13, 2021 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [f59179a579](https://linux-hardware.org/?probe=f59179a579) | Aug 13, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [0fb5cb1e91](https://linux-hardware.org/?probe=0fb5cb1e91) | Aug 13, 2021 |
| ASUSTek       | Z170-PRO                    | Desktop     | [7f9b5606a5](https://linux-hardware.org/?probe=7f9b5606a5) | Aug 13, 2021 |
| Google        | Enguarde                    | Notebook    | [43919a91f3](https://linux-hardware.org/?probe=43919a91f3) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [c93dcd9531](https://linux-hardware.org/?probe=c93dcd9531) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [8e7147d832](https://linux-hardware.org/?probe=8e7147d832) | Aug 12, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [65a4eb9f2c](https://linux-hardware.org/?probe=65a4eb9f2c) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [e9f95dc0ed](https://linux-hardware.org/?probe=e9f95dc0ed) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [3b5b9d1698](https://linux-hardware.org/?probe=3b5b9d1698) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [e423d1eee6](https://linux-hardware.org/?probe=e423d1eee6) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [1f00600e9b](https://linux-hardware.org/?probe=1f00600e9b) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [88adc88ccd](https://linux-hardware.org/?probe=88adc88ccd) | Aug 12, 2021 |
| Notebook      | NL4x_NL5xLU                 | Notebook    | [82a8b9c657](https://linux-hardware.org/?probe=82a8b9c657) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [2434eac448](https://linux-hardware.org/?probe=2434eac448) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [d766910df0](https://linux-hardware.org/?probe=d766910df0) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [c0516ce965](https://linux-hardware.org/?probe=c0516ce965) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [728007c621](https://linux-hardware.org/?probe=728007c621) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [b808ac5856](https://linux-hardware.org/?probe=b808ac5856) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [326cc3aae3](https://linux-hardware.org/?probe=326cc3aae3) | Aug 12, 2021 |
| Google        | Enguarde                    | Notebook    | [1fddcb2525](https://linux-hardware.org/?probe=1fddcb2525) | Aug 12, 2021 |
| Lenovo        | ThinkPad T440s 20AR0011M... | Notebook    | [df7a1d9358](https://linux-hardware.org/?probe=df7a1d9358) | Aug 12, 2021 |
| Lenovo        | V14 G2 ITL 82KA             | Notebook    | [2bc14051d8](https://linux-hardware.org/?probe=2bc14051d8) | Aug 12, 2021 |
| Lenovo        | ThinkPad X250 20CM001RMS    | Notebook    | [d0dfc1011e](https://linux-hardware.org/?probe=d0dfc1011e) | Aug 12, 2021 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [c0bae6c52e](https://linux-hardware.org/?probe=c0bae6c52e) | Aug 12, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [cbe8c5170f](https://linux-hardware.org/?probe=cbe8c5170f) | Aug 12, 2021 |
| HP            | ProBook 4530s               | Notebook    | [14a78c65a1](https://linux-hardware.org/?probe=14a78c65a1) | Aug 12, 2021 |
| Lenovo        | ThinkPad X250 20CLS4WV08    | Notebook    | [2c09cdd5bd](https://linux-hardware.org/?probe=2c09cdd5bd) | Aug 12, 2021 |
| HP            | 3048h                       | Desktop     | [894950911f](https://linux-hardware.org/?probe=894950911f) | Aug 11, 2021 |
| Intel         | NUC7i3BNB J22859-303        | Mini pc     | [7e6788485b](https://linux-hardware.org/?probe=7e6788485b) | Aug 11, 2021 |
| Samsung       | 300E5M/300E5L               | Notebook    | [4139a3a855](https://linux-hardware.org/?probe=4139a3a855) | Aug 11, 2021 |
| Notebook      | N13_N140ZU                  | Notebook    | [cbaecf1d3e](https://linux-hardware.org/?probe=cbaecf1d3e) | Aug 11, 2021 |
| Samsung       | 300E5M/300E5L               | Notebook    | [48573ed425](https://linux-hardware.org/?probe=48573ed425) | Aug 11, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [9b62457757](https://linux-hardware.org/?probe=9b62457757) | Aug 11, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [40d1d24c90](https://linux-hardware.org/?probe=40d1d24c90) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [4d023d9be2](https://linux-hardware.org/?probe=4d023d9be2) | Aug 11, 2021 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [927a3673b9](https://linux-hardware.org/?probe=927a3673b9) | Aug 11, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [f174ea79a1](https://linux-hardware.org/?probe=f174ea79a1) | Aug 11, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [a5a2ea2cda](https://linux-hardware.org/?probe=a5a2ea2cda) | Aug 11, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [cabe0ebbc8](https://linux-hardware.org/?probe=cabe0ebbc8) | Aug 10, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [1dcbf85471](https://linux-hardware.org/?probe=1dcbf85471) | Aug 10, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [0c67490330](https://linux-hardware.org/?probe=0c67490330) | Aug 10, 2021 |
| Dell          | Precision 3551              | Notebook    | [da8459ac73](https://linux-hardware.org/?probe=da8459ac73) | Aug 10, 2021 |
| ASUSTek       | STRIX B250H GAMING          | Desktop     | [78223998b6](https://linux-hardware.org/?probe=78223998b6) | Aug 10, 2021 |
| HP            | 250 G4                      | Notebook    | [5640b0689d](https://linux-hardware.org/?probe=5640b0689d) | Aug 10, 2021 |
| MSI           | B250M PRO-VDH               | Desktop     | [d6be998202](https://linux-hardware.org/?probe=d6be998202) | Aug 10, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [d650ff0c3e](https://linux-hardware.org/?probe=d650ff0c3e) | Aug 10, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [4ce98656a4](https://linux-hardware.org/?probe=4ce98656a4) | Aug 10, 2021 |
| Dell          | Inspiron ME051              | Notebook    | [5ca4e6101b](https://linux-hardware.org/?probe=5ca4e6101b) | Aug 10, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [7cc269740d](https://linux-hardware.org/?probe=7cc269740d) | Aug 10, 2021 |
| Lenovo        | B51-35 80LH                 | Notebook    | [5f87168a65](https://linux-hardware.org/?probe=5f87168a65) | Aug 10, 2021 |
| Dell          | 04MFRM A01                  | Desktop     | [c0094def97](https://linux-hardware.org/?probe=c0094def97) | Aug 09, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [6ab68482c0](https://linux-hardware.org/?probe=6ab68482c0) | Aug 09, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [58b4f52cc0](https://linux-hardware.org/?probe=58b4f52cc0) | Aug 09, 2021 |
| Lenovo        | ThinkPad T470s 20HGS3R80... | Notebook    | [fbc29e2063](https://linux-hardware.org/?probe=fbc29e2063) | Aug 09, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [e4ce236efd](https://linux-hardware.org/?probe=e4ce236efd) | Aug 09, 2021 |
| Lenovo        | ThinkPad T450s 20BXCTO1W... | Notebook    | [1c26f935e6](https://linux-hardware.org/?probe=1c26f935e6) | Aug 09, 2021 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [538a15f3cc](https://linux-hardware.org/?probe=538a15f3cc) | Aug 09, 2021 |
| HP            | 2000                        | Notebook    | [73e2b73533](https://linux-hardware.org/?probe=73e2b73533) | Aug 09, 2021 |
| Lenovo        | ThinkPad T580 20L9001AUS    | Notebook    | [65e201224c](https://linux-hardware.org/?probe=65e201224c) | Aug 09, 2021 |
| MSI           | GP60 2PE                    | Notebook    | [516f3cd4e5](https://linux-hardware.org/?probe=516f3cd4e5) | Aug 09, 2021 |
| Gigabyte      | H470M DS3H                  | Desktop     | [29de4693d8](https://linux-hardware.org/?probe=29de4693d8) | Aug 09, 2021 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [1a19648b3b](https://linux-hardware.org/?probe=1a19648b3b) | Aug 09, 2021 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [64784dd9c7](https://linux-hardware.org/?probe=64784dd9c7) | Aug 09, 2021 |
| ASRock        | 970A-G                      | Desktop     | [f1e9959894](https://linux-hardware.org/?probe=f1e9959894) | Aug 09, 2021 |
| Lenovo        | ThinkPad T410 2537E49       | Notebook    | [ea10aead92](https://linux-hardware.org/?probe=ea10aead92) | Aug 08, 2021 |
| Toshiba       | STI 910090 STIJ             | Desktop     | [389ebd7675](https://linux-hardware.org/?probe=389ebd7675) | Aug 08, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [575a84d010](https://linux-hardware.org/?probe=575a84d010) | Aug 08, 2021 |
| Clevo         | W55xEU                      | Notebook    | [ee96e1ca32](https://linux-hardware.org/?probe=ee96e1ca32) | Aug 08, 2021 |
| ASRock        | X370 Killer SLI             | Desktop     | [8a0885afb6](https://linux-hardware.org/?probe=8a0885afb6) | Aug 08, 2021 |
| Lenovo        | ThinkPad W500 406152G       | Notebook    | [b400f1bc46](https://linux-hardware.org/?probe=b400f1bc46) | Aug 08, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [eac37d633f](https://linux-hardware.org/?probe=eac37d633f) | Aug 08, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [43aae04fa6](https://linux-hardware.org/?probe=43aae04fa6) | Aug 08, 2021 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [b1f5babbfb](https://linux-hardware.org/?probe=b1f5babbfb) | Aug 08, 2021 |
| Lenovo        | ThinkPad X230 23252FG       | Notebook    | [1c7914d660](https://linux-hardware.org/?probe=1c7914d660) | Aug 08, 2021 |
| ASRock        | Z97 Pro4                    | Desktop     | [090d12a96f](https://linux-hardware.org/?probe=090d12a96f) | Aug 08, 2021 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [39eb5a1578](https://linux-hardware.org/?probe=39eb5a1578) | Aug 08, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [c5ef006a35](https://linux-hardware.org/?probe=c5ef006a35) | Aug 08, 2021 |
| Toshiba       | STI 005038 G31T-M7          | Desktop     | [faa8f15725](https://linux-hardware.org/?probe=faa8f15725) | Aug 08, 2021 |
| Acer          | Swift SF314-51              | Notebook    | [88fa728376](https://linux-hardware.org/?probe=88fa728376) | Aug 07, 2021 |
| Lenovo        | ThinkBook 14 G2 ARE 20VF    | Notebook    | [e18202a558](https://linux-hardware.org/?probe=e18202a558) | Aug 07, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [a89cdf06f5](https://linux-hardware.org/?probe=a89cdf06f5) | Aug 07, 2021 |
| Samsung       | 900X3C/900X3D/900X3E/900... | Notebook    | [18d1628875](https://linux-hardware.org/?probe=18d1628875) | Aug 07, 2021 |
| Clevo         | P170EM                      | Notebook    | [f101b2b318](https://linux-hardware.org/?probe=f101b2b318) | Aug 07, 2021 |
| Acer          | Aspire E5-575               | Notebook    | [3caca4f238](https://linux-hardware.org/?probe=3caca4f238) | Aug 07, 2021 |
| Acer          | Aspire E5-571P              | Notebook    | [1dbaeef7d2](https://linux-hardware.org/?probe=1dbaeef7d2) | Aug 07, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [9dafe47483](https://linux-hardware.org/?probe=9dafe47483) | Aug 07, 2021 |
| Google        | Parrot                      | Notebook    | [2efb04c61c](https://linux-hardware.org/?probe=2efb04c61c) | Aug 07, 2021 |
| Lenovo        | ThinkPad T61 7661BK7        | Notebook    | [bbabc03a27](https://linux-hardware.org/?probe=bbabc03a27) | Aug 07, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [da833ac33e](https://linux-hardware.org/?probe=da833ac33e) | Aug 07, 2021 |
| ASUSTek       | TUF Z370-PLUS GAMING        | Desktop     | [80c7711147](https://linux-hardware.org/?probe=80c7711147) | Aug 07, 2021 |
| Sony          | VPCF21AFX                   | Notebook    | [40aa5144f7](https://linux-hardware.org/?probe=40aa5144f7) | Aug 07, 2021 |
| Lenovo        | ThinkPad T450 20BUS16700    | Notebook    | [8123256638](https://linux-hardware.org/?probe=8123256638) | Aug 07, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [e82d4c3561](https://linux-hardware.org/?probe=e82d4c3561) | Aug 07, 2021 |
| HP            | Pavilion 15                 | Notebook    | [73f50567a1](https://linux-hardware.org/?probe=73f50567a1) | Aug 07, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [4ff5966d22](https://linux-hardware.org/?probe=4ff5966d22) | Aug 07, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [5839492cd8](https://linux-hardware.org/?probe=5839492cd8) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [412f800d01](https://linux-hardware.org/?probe=412f800d01) | Aug 07, 2021 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [733a3e325c](https://linux-hardware.org/?probe=733a3e325c) | Aug 07, 2021 |
| Dell          | 08WKV3 A01                  | Desktop     | [8ab0ff9442](https://linux-hardware.org/?probe=8ab0ff9442) | Aug 07, 2021 |
| Lenovo        | ThinkPad T550 20CK0002MZ    | Notebook    | [701a99b60f](https://linux-hardware.org/?probe=701a99b60f) | Aug 07, 2021 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [69696c0e3a](https://linux-hardware.org/?probe=69696c0e3a) | Aug 07, 2021 |
| Lenovo        | ThinkPad X200 7458B64       | Notebook    | [110a19b1b7](https://linux-hardware.org/?probe=110a19b1b7) | Aug 07, 2021 |
| MSI           | MEG X399 CREATION           | Desktop     | [7cada9aaed](https://linux-hardware.org/?probe=7cada9aaed) | Aug 07, 2021 |
| Lenovo        | ThinkPad X240 20AMS0BU0T    | Notebook    | [f22b591a0a](https://linux-hardware.org/?probe=f22b591a0a) | Aug 07, 2021 |
| Lenovo        | ThinkPad T440s 20ARA1DJM... | Notebook    | [3d02d8b67f](https://linux-hardware.org/?probe=3d02d8b67f) | Aug 07, 2021 |
| HP            | 630                         | Notebook    | [b2d03b8717](https://linux-hardware.org/?probe=b2d03b8717) | Aug 07, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [368abe4066](https://linux-hardware.org/?probe=368abe4066) | Aug 07, 2021 |
| MSI           | B250M PRO-VDH               | Desktop     | [187e4dd872](https://linux-hardware.org/?probe=187e4dd872) | Aug 07, 2021 |
| HP            | 630                         | Notebook    | [428ee9672e](https://linux-hardware.org/?probe=428ee9672e) | Aug 07, 2021 |
| Lenovo        | ThinkPad P17 Gen 1 20SNZ... | Notebook    | [669874ee19](https://linux-hardware.org/?probe=669874ee19) | Aug 07, 2021 |
| MSI           | GP60 2PE                    | Notebook    | [ad24cf2899](https://linux-hardware.org/?probe=ad24cf2899) | Aug 07, 2021 |
| MSI           | GP60 2PE                    | Notebook    | [9f994fc086](https://linux-hardware.org/?probe=9f994fc086) | Aug 07, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e2b8c558f7](https://linux-hardware.org/?probe=e2b8c558f7) | Aug 06, 2021 |
| HP            | Compaq nx6125 (PZ849UA#A... | Notebook    | [8cc604abc2](https://linux-hardware.org/?probe=8cc604abc2) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c9c4b53460](https://linux-hardware.org/?probe=c9c4b53460) | Aug 06, 2021 |
| HP            | Compaq nx6110 (PZ065UA#A... | Notebook    | [f54c45ab89](https://linux-hardware.org/?probe=f54c45ab89) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [81fef8f548](https://linux-hardware.org/?probe=81fef8f548) | Aug 06, 2021 |
| HP            | Compaq nx6125 (PZ849UA#A... | Notebook    | [4e000b3710](https://linux-hardware.org/?probe=4e000b3710) | Aug 06, 2021 |
| HP            | Compaq nx6110 (PZ065UA#A... | Notebook    | [493e2762bc](https://linux-hardware.org/?probe=493e2762bc) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [2eb3a16b53](https://linux-hardware.org/?probe=2eb3a16b53) | Aug 06, 2021 |
| Dell          | Precision 3540              | Notebook    | [1b8206cd29](https://linux-hardware.org/?probe=1b8206cd29) | Aug 06, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [10811e8109](https://linux-hardware.org/?probe=10811e8109) | Aug 06, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [bba0c0a13c](https://linux-hardware.org/?probe=bba0c0a13c) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [25f1a5ecdf](https://linux-hardware.org/?probe=25f1a5ecdf) | Aug 06, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [a7114078e2](https://linux-hardware.org/?probe=a7114078e2) | Aug 06, 2021 |
| Lenovo        | ThinkPad W520 4284CY1       | Notebook    | [5e1c9e9e30](https://linux-hardware.org/?probe=5e1c9e9e30) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [639bb0ca17](https://linux-hardware.org/?probe=639bb0ca17) | Aug 06, 2021 |
| Dell          | G3 3579                     | Notebook    | [5a268dbc14](https://linux-hardware.org/?probe=5a268dbc14) | Aug 06, 2021 |
| Dell          | G3 3579                     | Notebook    | [6aae1a533f](https://linux-hardware.org/?probe=6aae1a533f) | Aug 06, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [41d352c625](https://linux-hardware.org/?probe=41d352c625) | Aug 06, 2021 |
| Acer          | Aspire 5315                 | Notebook    | [3256d646b0](https://linux-hardware.org/?probe=3256d646b0) | Aug 06, 2021 |
| Lenovo        | ThinkPad E14 Gen 2 20TBS... | Notebook    | [f7718b0dfe](https://linux-hardware.org/?probe=f7718b0dfe) | Aug 06, 2021 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [31d159af99](https://linux-hardware.org/?probe=31d159af99) | Aug 06, 2021 |
| Dell          | Latitude E7240              | Notebook    | [4dd840f3dd](https://linux-hardware.org/?probe=4dd840f3dd) | Aug 06, 2021 |
| Acer          | Aspire 5315                 | Notebook    | [64b6992b74](https://linux-hardware.org/?probe=64b6992b74) | Aug 06, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [f8727e28db](https://linux-hardware.org/?probe=f8727e28db) | Aug 05, 2021 |
| Acer          | Aspire 5315                 | Notebook    | [249a58dd07](https://linux-hardware.org/?probe=249a58dd07) | Aug 05, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [fa1f3da353](https://linux-hardware.org/?probe=fa1f3da353) | Aug 05, 2021 |
| Acer          | Aspire 5315                 | Notebook    | [812e20e37e](https://linux-hardware.org/?probe=812e20e37e) | Aug 05, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [b90c18f9a0](https://linux-hardware.org/?probe=b90c18f9a0) | Aug 05, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [393c8e4faa](https://linux-hardware.org/?probe=393c8e4faa) | Aug 05, 2021 |
| Lenovo        | Board                       | Desktop     | [18138486db](https://linux-hardware.org/?probe=18138486db) | Aug 05, 2021 |
| Intel         | DN2820FYK H24582-201        | Desktop     | [7caf949908](https://linux-hardware.org/?probe=7caf949908) | Aug 05, 2021 |
| Apple         | MacBook2,1                  | Notebook    | [103dba0476](https://linux-hardware.org/?probe=103dba0476) | Aug 05, 2021 |
| HP            | ProBook 6450b               | Notebook    | [ec02a5333b](https://linux-hardware.org/?probe=ec02a5333b) | Aug 05, 2021 |
| HP            | 3085B                       | Notebook    | [6be769f55c](https://linux-hardware.org/?probe=6be769f55c) | Aug 05, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [0a79f49420](https://linux-hardware.org/?probe=0a79f49420) | Aug 05, 2021 |
| HP            | Pavilion dm4                | Notebook    | [7ba854b03e](https://linux-hardware.org/?probe=7ba854b03e) | Aug 05, 2021 |
| Clevo         | W240HU/W250HUQ              | Notebook    | [f71032cd7f](https://linux-hardware.org/?probe=f71032cd7f) | Aug 05, 2021 |
| Unknown       | Intel X79                   | Desktop     | [fc0dedbb3c](https://linux-hardware.org/?probe=fc0dedbb3c) | Aug 05, 2021 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [5ba990c425](https://linux-hardware.org/?probe=5ba990c425) | Aug 04, 2021 |
| HP            | ProLiant DL360 G7           | Server      | [4882999fd5](https://linux-hardware.org/?probe=4882999fd5) | Aug 04, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [a0e7632e28](https://linux-hardware.org/?probe=a0e7632e28) | Aug 04, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [803a6be591](https://linux-hardware.org/?probe=803a6be591) | Aug 04, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [cca5aa2900](https://linux-hardware.org/?probe=cca5aa2900) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [2c8c33becf](https://linux-hardware.org/?probe=2c8c33becf) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [97f8f86784](https://linux-hardware.org/?probe=97f8f86784) | Aug 04, 2021 |
| Notebook      | NJ50_70CU                   | Notebook    | [a9b3790d07](https://linux-hardware.org/?probe=a9b3790d07) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [2d764714a4](https://linux-hardware.org/?probe=2d764714a4) | Aug 04, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [b2a62f65d6](https://linux-hardware.org/?probe=b2a62f65d6) | Aug 04, 2021 |
| AMD           | 970A-D3                     | Desktop     | [91825066e0](https://linux-hardware.org/?probe=91825066e0) | Aug 04, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [09a6257403](https://linux-hardware.org/?probe=09a6257403) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [eafaf5ece3](https://linux-hardware.org/?probe=eafaf5ece3) | Aug 04, 2021 |
| ASUSTek       | N53Ta                       | Notebook    | [896a02b57b](https://linux-hardware.org/?probe=896a02b57b) | Aug 04, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [c0bf2b7b10](https://linux-hardware.org/?probe=c0bf2b7b10) | Aug 03, 2021 |
| HP            | 3047h                       | Desktop     | [6294617672](https://linux-hardware.org/?probe=6294617672) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [3d29b58c58](https://linux-hardware.org/?probe=3d29b58c58) | Aug 03, 2021 |
| Lenovo        | ThinkPad E475 20H40006US    | Notebook    | [8b35a81ed6](https://linux-hardware.org/?probe=8b35a81ed6) | Aug 03, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [87bca8ecbc](https://linux-hardware.org/?probe=87bca8ecbc) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [fbbd748072](https://linux-hardware.org/?probe=fbbd748072) | Aug 03, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [a7bdbd8ebe](https://linux-hardware.org/?probe=a7bdbd8ebe) | Aug 03, 2021 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [55cd593df1](https://linux-hardware.org/?probe=55cd593df1) | Aug 03, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [71738ebf7e](https://linux-hardware.org/?probe=71738ebf7e) | Aug 03, 2021 |
| Apple         | MacBook7,1                  | Notebook    | [06d86172a1](https://linux-hardware.org/?probe=06d86172a1) | Aug 03, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [aa415746d6](https://linux-hardware.org/?probe=aa415746d6) | Aug 03, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [c8674581d0](https://linux-hardware.org/?probe=c8674581d0) | Aug 03, 2021 |
| Dell          | Latitude E4310              | Notebook    | [75a9aa20f2](https://linux-hardware.org/?probe=75a9aa20f2) | Aug 03, 2021 |
| Google        | Enguarde                    | Notebook    | [c758164470](https://linux-hardware.org/?probe=c758164470) | Aug 03, 2021 |
| Lenovo        | ThinkPad R61e 7650DHU       | Notebook    | [82f2f3a1a7](https://linux-hardware.org/?probe=82f2f3a1a7) | Aug 03, 2021 |
| ASUSTek       | 1005HA                      | Notebook    | [1f83d95a2a](https://linux-hardware.org/?probe=1f83d95a2a) | Aug 03, 2021 |
| Lenovo        | ThinkPad T410 2537W2L       | Notebook    | [c14dd630ed](https://linux-hardware.org/?probe=c14dd630ed) | Aug 03, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [3a2fd430f6](https://linux-hardware.org/?probe=3a2fd430f6) | Aug 03, 2021 |
| MSI           | 760GM-P23                   | Desktop     | [93b6f212af](https://linux-hardware.org/?probe=93b6f212af) | Aug 02, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [99ccdd5455](https://linux-hardware.org/?probe=99ccdd5455) | Aug 02, 2021 |
| Supermicro    | X11SSH-F                    | Desktop     | [641e4fd8ce](https://linux-hardware.org/?probe=641e4fd8ce) | Aug 02, 2021 |
| Lenovo        | Reno                        | Server      | [91a367ab6d](https://linux-hardware.org/?probe=91a367ab6d) | Aug 02, 2021 |
| Apple         | MacBook5,2                  | Notebook    | [aa5aaf6fd0](https://linux-hardware.org/?probe=aa5aaf6fd0) | Aug 02, 2021 |
| SimpliVity    | 04N3DF A03                  | Server      | [c5705e6436](https://linux-hardware.org/?probe=c5705e6436) | Aug 02, 2021 |
| Google        | Stout                       | Notebook    | [e4463bb3d4](https://linux-hardware.org/?probe=e4463bb3d4) | Aug 02, 2021 |
| Fujitsu       | LIFEBOOK T5010              | Notebook    | [75a544682e](https://linux-hardware.org/?probe=75a544682e) | Aug 02, 2021 |
| Google        | Enguarde                    | Notebook    | [09406c6908](https://linux-hardware.org/?probe=09406c6908) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [01315f2df2](https://linux-hardware.org/?probe=01315f2df2) | Aug 02, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [e6ca37026c](https://linux-hardware.org/?probe=e6ca37026c) | Aug 02, 2021 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [70647a7f66](https://linux-hardware.org/?probe=70647a7f66) | Aug 02, 2021 |
| ASRock        | H310CM-DVS                  | Desktop     | [f84e5eba5a](https://linux-hardware.org/?probe=f84e5eba5a) | Aug 02, 2021 |
| ASUSTek       | M4A785TD-M EVO              | Desktop     | [e90a873ad0](https://linux-hardware.org/?probe=e90a873ad0) | Aug 02, 2021 |
| ASUSTek       | P5QL-E                      | Desktop     | [2894e88095](https://linux-hardware.org/?probe=2894e88095) | Aug 02, 2021 |
| Dell          | Inspiron 7391               | Notebook    | [c4ac48e264](https://linux-hardware.org/?probe=c4ac48e264) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [ace43d8e9f](https://linux-hardware.org/?probe=ace43d8e9f) | Aug 02, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [384ffe1123](https://linux-hardware.org/?probe=384ffe1123) | Aug 02, 2021 |
| ASUSTek       | A88X-PRO                    | Desktop     | [ed95430eec](https://linux-hardware.org/?probe=ed95430eec) | Aug 02, 2021 |
| HP            | 2187 A01                    | Desktop     | [16bfdd86e3](https://linux-hardware.org/?probe=16bfdd86e3) | Aug 02, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | Notebook    | [101a0ca1b3](https://linux-hardware.org/?probe=101a0ca1b3) | Aug 01, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [61886d812f](https://linux-hardware.org/?probe=61886d812f) | Aug 01, 2021 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [9c7fb8e911](https://linux-hardware.org/?probe=9c7fb8e911) | Aug 01, 2021 |
| Lenovo        | ThinkPad L520 5016NU7       | Notebook    | [08fe25ec71](https://linux-hardware.org/?probe=08fe25ec71) | Aug 01, 2021 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [8f40021fde](https://linux-hardware.org/?probe=8f40021fde) | Aug 01, 2021 |
| ASRock        | J1900D2Y                    | Desktop     | [0dc4afc8c4](https://linux-hardware.org/?probe=0dc4afc8c4) | Aug 01, 2021 |
| Lenovo        | ThinkPad Edge E330 3354D... | Notebook    | [9c317f536b](https://linux-hardware.org/?probe=9c317f536b) | Aug 01, 2021 |
| ASUSTek       | ROG Strix G731GT_G731GT     | Notebook    | [f851abbdf5](https://linux-hardware.org/?probe=f851abbdf5) | Aug 01, 2021 |
| ASRock        | N68C-S UCC                  | Desktop     | [3da0d57fd5](https://linux-hardware.org/?probe=3da0d57fd5) | Aug 01, 2021 |
| Dell          | 0WVYMC A00                  | Desktop     | [4d2aa42e3c](https://linux-hardware.org/?probe=4d2aa42e3c) | Jul 31, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5b89a99ad8](https://linux-hardware.org/?probe=5b89a99ad8) | Jul 31, 2021 |
| Dell          | Vostro 5502                 | Notebook    | [f1e6f11078](https://linux-hardware.org/?probe=f1e6f11078) | Jul 31, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [159ff0ba7f](https://linux-hardware.org/?probe=159ff0ba7f) | Jul 31, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | Notebook    | [60f065b770](https://linux-hardware.org/?probe=60f065b770) | Jul 31, 2021 |
| ASRock        | Z370M-ITX/ac                | Desktop     | [30511d93c4](https://linux-hardware.org/?probe=30511d93c4) | Jul 31, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [b62fb400bf](https://linux-hardware.org/?probe=b62fb400bf) | Jul 31, 2021 |
| Acer          | Aspire 7720                 | Notebook    | [6472272bf7](https://linux-hardware.org/?probe=6472272bf7) | Jul 30, 2021 |
| Lenovo        | ThinkPad E14 20RA001LMC     | Notebook    | [b16533813f](https://linux-hardware.org/?probe=b16533813f) | Jul 30, 2021 |
| ASUSTek       | Pro WS WRX80E-SAGE SE WI... | Desktop     | [3f0c3901f6](https://linux-hardware.org/?probe=3f0c3901f6) | Jul 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0A60... | Notebook    | [8a3c585de4](https://linux-hardware.org/?probe=8a3c585de4) | Jul 30, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | Notebook    | [a46cb950a4](https://linux-hardware.org/?probe=a46cb950a4) | Jul 29, 2021 |
| MSI           | Z490-A PRO                  | Desktop     | [b882a9cf0d](https://linux-hardware.org/?probe=b882a9cf0d) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [370cea169d](https://linux-hardware.org/?probe=370cea169d) | Jul 29, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [a5a9ca4678](https://linux-hardware.org/?probe=a5a9ca4678) | Jul 29, 2021 |
| MSI           | Q45MDO                      | Desktop     | [ab547f0047](https://linux-hardware.org/?probe=ab547f0047) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [55c54d17ad](https://linux-hardware.org/?probe=55c54d17ad) | Jul 29, 2021 |
| MSI           | Q45MDO                      | Desktop     | [6b5aaa6969](https://linux-hardware.org/?probe=6b5aaa6969) | Jul 29, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [1bb07ffc9f](https://linux-hardware.org/?probe=1bb07ffc9f) | Jul 29, 2021 |
| Dell          | 0TY915                      | Desktop     | [9cb5aed659](https://linux-hardware.org/?probe=9cb5aed659) | Jul 29, 2021 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [ed7394c65a](https://linux-hardware.org/?probe=ed7394c65a) | Jul 29, 2021 |
| ASUSTek       | LEONITE                     | Desktop     | [3bf9048839](https://linux-hardware.org/?probe=3bf9048839) | Jul 29, 2021 |
| Foxconn       | 2AA9                        | Desktop     | [920a813aaf](https://linux-hardware.org/?probe=920a813aaf) | Jul 29, 2021 |
| SLIMBOOK      | PROX14-AMD                  | Notebook    | [16aeb37a86](https://linux-hardware.org/?probe=16aeb37a86) | Jul 29, 2021 |
| ASRock        | B85M Pro4                   | Desktop     | [32e615b538](https://linux-hardware.org/?probe=32e615b538) | Jul 29, 2021 |
| Acer          | Nitro AN517-41              | Notebook    | [ccc850c1da](https://linux-hardware.org/?probe=ccc850c1da) | Jul 29, 2021 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [f449b8ce85](https://linux-hardware.org/?probe=f449b8ce85) | Jul 29, 2021 |
| Lenovo        | ThinkPad T420s 4174PEG      | Notebook    | [e448710e41](https://linux-hardware.org/?probe=e448710e41) | Jul 28, 2021 |
| ECS           | H61H2-M12                   | Desktop     | [42050ab984](https://linux-hardware.org/?probe=42050ab984) | Jul 28, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [89d3c0f09d](https://linux-hardware.org/?probe=89d3c0f09d) | Jul 28, 2021 |
| MSI           | B450M PRO-VDH PLUS          | Desktop     | [cccaebb483](https://linux-hardware.org/?probe=cccaebb483) | Jul 28, 2021 |
| HP            | OMEN by HP Laptop 17-cb1... | Notebook    | [bee4fd945a](https://linux-hardware.org/?probe=bee4fd945a) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [4206886abb](https://linux-hardware.org/?probe=4206886abb) | Jul 28, 2021 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [d244dc6763](https://linux-hardware.org/?probe=d244dc6763) | Jul 28, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [f96bcc3ab2](https://linux-hardware.org/?probe=f96bcc3ab2) | Jul 28, 2021 |
| ZOTAC         | ZBOX-EN1070/1060,EN1070K... | Mini pc     | [cc099348c2](https://linux-hardware.org/?probe=cc099348c2) | Jul 28, 2021 |
| Lenovo        | ThinkPad T470 20HES1UD00    | Notebook    | [6034f6a417](https://linux-hardware.org/?probe=6034f6a417) | Jul 28, 2021 |
| Lenovo        | ThinkPad X230 2325BQ3       | Notebook    | [79a19ade20](https://linux-hardware.org/?probe=79a19ade20) | Jul 28, 2021 |
| Dell          | Inspiron 8600               | Notebook    | [2f49d18738](https://linux-hardware.org/?probe=2f49d18738) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [abdeaec5ce](https://linux-hardware.org/?probe=abdeaec5ce) | Jul 28, 2021 |
| Lenovo        | ThinkPad P52 20M9CTO1WW     | Notebook    | [5258847421](https://linux-hardware.org/?probe=5258847421) | Jul 28, 2021 |
| Lenovo        | ThinkPad T490 20RYCTO1WW    | Notebook    | [60c16ed267](https://linux-hardware.org/?probe=60c16ed267) | Jul 28, 2021 |
| Shuttle       | FX79R                       | Desktop     | [6ceba6fc67](https://linux-hardware.org/?probe=6ceba6fc67) | Jul 28, 2021 |
| Acer          | Swift SF313-52G             | Notebook    | [87add43827](https://linux-hardware.org/?probe=87add43827) | Jul 28, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [df0a4b1a0f](https://linux-hardware.org/?probe=df0a4b1a0f) | Jul 27, 2021 |
| Casper        | C17B                        | Notebook    | [6f56921ba5](https://linux-hardware.org/?probe=6f56921ba5) | Jul 27, 2021 |
| ASRockRack    | X570D4U-2L2T                | Desktop     | [7bb34c9dec](https://linux-hardware.org/?probe=7bb34c9dec) | Jul 27, 2021 |
| Lenovo        | ThinkPad X240 20AL008EUK    | Notebook    | [367150f04f](https://linux-hardware.org/?probe=367150f04f) | Jul 27, 2021 |
| HP            | Laptop 17-by0xxx            | Notebook    | [0cb6fde0ef](https://linux-hardware.org/?probe=0cb6fde0ef) | Jul 27, 2021 |
| HP            | ProBook 445 G7              | Notebook    | [bc4f8acaf2](https://linux-hardware.org/?probe=bc4f8acaf2) | Jul 27, 2021 |
| ASUSTek       | A88X-PLUS/USB               | Desktop     | [57b54cc925](https://linux-hardware.org/?probe=57b54cc925) | Jul 27, 2021 |
| ASRock        | N68C-GS FX                  | Desktop     | [660f13d25d](https://linux-hardware.org/?probe=660f13d25d) | Jul 27, 2021 |
| ASUSTek       | PRIME Z490-P                | Desktop     | [2e0f5417fc](https://linux-hardware.org/?probe=2e0f5417fc) | Jul 27, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [7821dfc370](https://linux-hardware.org/?probe=7821dfc370) | Jul 27, 2021 |
| ASUSTek       | M4A785D-M PRO               | Desktop     | [467d107518](https://linux-hardware.org/?probe=467d107518) | Jul 27, 2021 |
| Foxconn       | 915MH Series                | Desktop     | [6a3ae85dfc](https://linux-hardware.org/?probe=6a3ae85dfc) | Jul 27, 2021 |
| HP            | ProBook 635 Aero G7 Note... | Notebook    | [e6ee486690](https://linux-hardware.org/?probe=e6ee486690) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [dc4a709a3b](https://linux-hardware.org/?probe=dc4a709a3b) | Jul 27, 2021 |
| Dell          | 0WMJ54 A01                  | Desktop     | [b24fc8e5f2](https://linux-hardware.org/?probe=b24fc8e5f2) | Jul 27, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [2a645d9cba](https://linux-hardware.org/?probe=2a645d9cba) | Jul 27, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [1e69873301](https://linux-hardware.org/?probe=1e69873301) | Jul 27, 2021 |
| Lenovo        | IdeaPad S540-13ITL 82H1     | Notebook    | [730c33a1b0](https://linux-hardware.org/?probe=730c33a1b0) | Jul 27, 2021 |
| Lenovo        | ThinkPad E14 20RAS13M00     | Notebook    | [b46ca83c19](https://linux-hardware.org/?probe=b46ca83c19) | Jul 27, 2021 |
| Dell          | Latitude 7480               | Notebook    | [0c79ad3dd4](https://linux-hardware.org/?probe=0c79ad3dd4) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [5b2e06697e](https://linux-hardware.org/?probe=5b2e06697e) | Jul 27, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [e94bee6137](https://linux-hardware.org/?probe=e94bee6137) | Jul 27, 2021 |
| Dell          | Inspiron 7420               | Notebook    | [567612e805](https://linux-hardware.org/?probe=567612e805) | Jul 27, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [0172934285](https://linux-hardware.org/?probe=0172934285) | Jul 27, 2021 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [e8ffe8991b](https://linux-hardware.org/?probe=e8ffe8991b) | Jul 27, 2021 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [3c6898fcd8](https://linux-hardware.org/?probe=3c6898fcd8) | Jul 27, 2021 |
| HP            | EliteBook 820 G1            | Notebook    | [f3878ff548](https://linux-hardware.org/?probe=f3878ff548) | Jul 27, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [9d0528280a](https://linux-hardware.org/?probe=9d0528280a) | Jul 26, 2021 |
| Apple         | MacBookPro11,4              | Notebook    | [d58bb90557](https://linux-hardware.org/?probe=d58bb90557) | Jul 26, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [1bbe185e86](https://linux-hardware.org/?probe=1bbe185e86) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA001HRT     | Notebook    | [f7175e6651](https://linux-hardware.org/?probe=f7175e6651) | Jul 26, 2021 |
| Quanta        | TWC                         | Notebook    | [1ecec0372f](https://linux-hardware.org/?probe=1ecec0372f) | Jul 26, 2021 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [2f259b4ae2](https://linux-hardware.org/?probe=2f259b4ae2) | Jul 26, 2021 |
| ASRock        | Z97 Pro3                    | Desktop     | [8cd14c1874](https://linux-hardware.org/?probe=8cd14c1874) | Jul 26, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [73c1da1908](https://linux-hardware.org/?probe=73c1da1908) | Jul 26, 2021 |
| ASUSTek       | ZenBook Q536FD_Q536FD       | Convertible | [52e5d3e16d](https://linux-hardware.org/?probe=52e5d3e16d) | Jul 26, 2021 |
| MSI           | Z370 SLI PLUS               | Desktop     | [04d84e38b8](https://linux-hardware.org/?probe=04d84e38b8) | Jul 26, 2021 |
| Intel         | NUC6i7KYB H90766-402        | Mini pc     | [e7aeecff98](https://linux-hardware.org/?probe=e7aeecff98) | Jul 26, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [eaedf12907](https://linux-hardware.org/?probe=eaedf12907) | Jul 26, 2021 |
| HP            | EliteBook 8470p             | Notebook    | [8bfc663f48](https://linux-hardware.org/?probe=8bfc663f48) | Jul 26, 2021 |
| HP            | ProBook 470 G3              | Notebook    | [cb1b02b979](https://linux-hardware.org/?probe=cb1b02b979) | Jul 26, 2021 |
| ASUSTek       | 701                         | Notebook    | [db72d4004a](https://linux-hardware.org/?probe=db72d4004a) | Jul 26, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [eb6369aac9](https://linux-hardware.org/?probe=eb6369aac9) | Jul 26, 2021 |
| ASRock        | B450 Pro4                   | Desktop     | [0de4a63af4](https://linux-hardware.org/?probe=0de4a63af4) | Jul 26, 2021 |
| HP            | 2B38                        | Desktop     | [be24f3f652](https://linux-hardware.org/?probe=be24f3f652) | Jul 26, 2021 |
| HP            | 2B38                        | Desktop     | [c1198b90f6](https://linux-hardware.org/?probe=c1198b90f6) | Jul 26, 2021 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [9fd8d25e24](https://linux-hardware.org/?probe=9fd8d25e24) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [8b0f398a93](https://linux-hardware.org/?probe=8b0f398a93) | Jul 26, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [cd62d88495](https://linux-hardware.org/?probe=cd62d88495) | Jul 26, 2021 |
| ASUSTek       | 1215B                       | Notebook    | [ce53b40511](https://linux-hardware.org/?probe=ce53b40511) | Jul 26, 2021 |
| Dell          | Latitude E6420              | Notebook    | [01000461fc](https://linux-hardware.org/?probe=01000461fc) | Jul 26, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [b040663b7c](https://linux-hardware.org/?probe=b040663b7c) | Jul 26, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [36caa67715](https://linux-hardware.org/?probe=36caa67715) | Jul 26, 2021 |
| Dell          | Studio 1555                 | Notebook    | [30b17f2421](https://linux-hardware.org/?probe=30b17f2421) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [e9ddc17233](https://linux-hardware.org/?probe=e9ddc17233) | Jul 26, 2021 |
| Lenovo        | ThinkPad E14 20RA0036RT     | Notebook    | [e4f29039a8](https://linux-hardware.org/?probe=e4f29039a8) | Jul 26, 2021 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [6623f96b90](https://linux-hardware.org/?probe=6623f96b90) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [2c05790c36](https://linux-hardware.org/?probe=2c05790c36) | Jul 26, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [c676ac21ee](https://linux-hardware.org/?probe=c676ac21ee) | Jul 26, 2021 |
| ASUSTek       | 701SD                       | Notebook    | [b7c888a9a7](https://linux-hardware.org/?probe=b7c888a9a7) | Jul 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [64b4d84778](https://linux-hardware.org/?probe=64b4d84778) | Jul 26, 2021 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [fffec5c87f](https://linux-hardware.org/?probe=fffec5c87f) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [0b35b55294](https://linux-hardware.org/?probe=0b35b55294) | Jul 26, 2021 |
| Dell          | 0D28YY A02                  | Desktop     | [71b0f194a3](https://linux-hardware.org/?probe=71b0f194a3) | Jul 26, 2021 |
| ASRock        | H470M-ITX/ac                | Desktop     | [8a3b6cb663](https://linux-hardware.org/?probe=8a3b6cb663) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [a145aa9a69](https://linux-hardware.org/?probe=a145aa9a69) | Jul 26, 2021 |
| ASUSTek       | M5A78L-M LX3                | Desktop     | [fcd103f100](https://linux-hardware.org/?probe=fcd103f100) | Jul 26, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [00d53058e7](https://linux-hardware.org/?probe=00d53058e7) | Jul 26, 2021 |
| ASUSTek       | X541NC                      | Notebook    | [500a26f588](https://linux-hardware.org/?probe=500a26f588) | Jul 26, 2021 |
| Toshiba       | Satellite S55-A             | Notebook    | [08eec2f3a7](https://linux-hardware.org/?probe=08eec2f3a7) | Jul 25, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ec1cea0d9d](https://linux-hardware.org/?probe=ec1cea0d9d) | Jul 25, 2021 |
| Dell          | XPS 17 9700                 | Notebook    | [92cd785445](https://linux-hardware.org/?probe=92cd785445) | Jul 25, 2021 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [d09fdc110f](https://linux-hardware.org/?probe=d09fdc110f) | Jul 25, 2021 |
| Lenovo        | ThinkPad T460 20FMS03600    | Notebook    | [84f380e2a2](https://linux-hardware.org/?probe=84f380e2a2) | Jul 25, 2021 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [4454739a42](https://linux-hardware.org/?probe=4454739a42) | Jul 25, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3UX0... | Notebook    | [abced1dd83](https://linux-hardware.org/?probe=abced1dd83) | Jul 25, 2021 |
| Lenovo        | ThinkPad E480 20KN001NGE    | Notebook    | [e3b2914d19](https://linux-hardware.org/?probe=e3b2914d19) | Jul 25, 2021 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1e2b68b7d8](https://linux-hardware.org/?probe=1e2b68b7d8) | Jul 25, 2021 |
| Toshiba       | Satellite C45-A             | Notebook    | [0497ab613d](https://linux-hardware.org/?probe=0497ab613d) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WNU       | Notebook    | [d817abc511](https://linux-hardware.org/?probe=d817abc511) | Jul 25, 2021 |
| Gigabyte      | H110M-S2H-CF                | Desktop     | [11c5d6c6d0](https://linux-hardware.org/?probe=11c5d6c6d0) | Jul 25, 2021 |
| Dell          | 0PTTT9 A00                  | Desktop     | [113235448d](https://linux-hardware.org/?probe=113235448d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [54b46bdd5d](https://linux-hardware.org/?probe=54b46bdd5d) | Jul 25, 2021 |
| HP            | ProBook x360 11 G1 EE       | Notebook    | [90aeea53cc](https://linux-hardware.org/?probe=90aeea53cc) | Jul 25, 2021 |
| ASUSTek       | PRIME H270M-PLUS            | Desktop     | [21b43b8718](https://linux-hardware.org/?probe=21b43b8718) | Jul 25, 2021 |
| Gigabyte      | Z170M-D3H-CF                | Desktop     | [9301420a7b](https://linux-hardware.org/?probe=9301420a7b) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5c61fdfb49](https://linux-hardware.org/?probe=5c61fdfb49) | Jul 25, 2021 |
| ASRock        | P67 Pro3                    | Desktop     | [ce711e5011](https://linux-hardware.org/?probe=ce711e5011) | Jul 25, 2021 |
| Supermicro    | A1SA2-2750FA                | Desktop     | [de408d6408](https://linux-hardware.org/?probe=de408d6408) | Jul 25, 2021 |
| Gigabyte      | H87-HD3                     | Desktop     | [a102014ef0](https://linux-hardware.org/?probe=a102014ef0) | Jul 25, 2021 |
| Dell          | Latitude E5520              | Notebook    | [0d74f57317](https://linux-hardware.org/?probe=0d74f57317) | Jul 25, 2021 |
| Dell          | Latitude E5520              | Notebook    | [5866765bab](https://linux-hardware.org/?probe=5866765bab) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [dcff1a4a95](https://linux-hardware.org/?probe=dcff1a4a95) | Jul 25, 2021 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [8b1c4f962a](https://linux-hardware.org/?probe=8b1c4f962a) | Jul 25, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ab8a90e145](https://linux-hardware.org/?probe=ab8a90e145) | Jul 25, 2021 |
| IBM           | I/O Port                    | Server      | [8538814cd6](https://linux-hardware.org/?probe=8538814cd6) | Jul 25, 2021 |
| Dell          | 0Y1057                      | Desktop     | [ac342b01e2](https://linux-hardware.org/?probe=ac342b01e2) | Jul 25, 2021 |
| HP            | OMEN by HP Laptop 15-dc0... | Notebook    | [b8a2299d30](https://linux-hardware.org/?probe=b8a2299d30) | Jul 25, 2021 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [2bcfda70b5](https://linux-hardware.org/?probe=2bcfda70b5) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [514f64cef0](https://linux-hardware.org/?probe=514f64cef0) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [0d45d49199](https://linux-hardware.org/?probe=0d45d49199) | Jul 25, 2021 |
| PC Special... | NV4XMB,ME,MZ                | Notebook    | [eb789efe18](https://linux-hardware.org/?probe=eb789efe18) | Jul 25, 2021 |
| ASRock        | Z97 Extreme6                | Desktop     | [84730f7819](https://linux-hardware.org/?probe=84730f7819) | Jul 25, 2021 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [a172262124](https://linux-hardware.org/?probe=a172262124) | Jul 25, 2021 |
| Lenovo        | ThinkPad T410 2522WUZ       | Notebook    | [62cddaceb1](https://linux-hardware.org/?probe=62cddaceb1) | Jul 25, 2021 |
| Lenovo        | 3098 0B98401 PRO            | Desktop     | [a5bb2fb53c](https://linux-hardware.org/?probe=a5bb2fb53c) | Jul 25, 2021 |
| HP            | 1495                        | Desktop     | [5d01240605](https://linux-hardware.org/?probe=5d01240605) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L5S1S000    | Notebook    | [1217d711fb](https://linux-hardware.org/?probe=1217d711fb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480 20L50063EU    | Notebook    | [c59c2aa27d](https://linux-hardware.org/?probe=c59c2aa27d) | Jul 25, 2021 |
| Lenovo        | ThinkPad X201 3626ES3       | Notebook    | [c18f4c4102](https://linux-hardware.org/?probe=c18f4c4102) | Jul 25, 2021 |
| HP            | 158A                        | Desktop     | [219b010ebb](https://linux-hardware.org/?probe=219b010ebb) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349BW1       | Notebook    | [75c4d5c7a9](https://linux-hardware.org/?probe=75c4d5c7a9) | Jul 25, 2021 |
| HP            | 158A                        | Desktop     | [da4016cb27](https://linux-hardware.org/?probe=da4016cb27) | Jul 25, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [59533bd2bf](https://linux-hardware.org/?probe=59533bd2bf) | Jul 25, 2021 |
| Acer          | Aspire 5735                 | Notebook    | [60451d6f55](https://linux-hardware.org/?probe=60451d6f55) | Jul 25, 2021 |
| Fujitsu       | LIFEBOOK AH532/G52          | Notebook    | [4e8d8d9253](https://linux-hardware.org/?probe=4e8d8d9253) | Jul 25, 2021 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [a98eb4deab](https://linux-hardware.org/?probe=a98eb4deab) | Jul 25, 2021 |
| HP            | ProBook 470 G5              | Notebook    | [a778d78c98](https://linux-hardware.org/?probe=a778d78c98) | Jul 25, 2021 |
| Gigabyte      | H110N-CF                    | Desktop     | [2a85c9961c](https://linux-hardware.org/?probe=2a85c9961c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236EV9       | Notebook    | [62cc86b330](https://linux-hardware.org/?probe=62cc86b330) | Jul 25, 2021 |
| MSI           | MAG B550M MORTAR            | Desktop     | [b5e7cb3f3d](https://linux-hardware.org/?probe=b5e7cb3f3d) | Jul 25, 2021 |
| Dell          | 0X8DXD A00                  | Desktop     | [dd60e87813](https://linux-hardware.org/?probe=dd60e87813) | Jul 25, 2021 |
| HP            | 2129                        | Desktop     | [8de5bae655](https://linux-hardware.org/?probe=8de5bae655) | Jul 25, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [b3dca0cfaa](https://linux-hardware.org/?probe=b3dca0cfaa) | Jul 25, 2021 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [f8ad21d44a](https://linux-hardware.org/?probe=f8ad21d44a) | Jul 25, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [53d3003d94](https://linux-hardware.org/?probe=53d3003d94) | Jul 25, 2021 |
| ASUSTek       | ZenBook UX333FA_UX333FA     | Notebook    | [043c5815ee](https://linux-hardware.org/?probe=043c5815ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [a30a8b568e](https://linux-hardware.org/?probe=a30a8b568e) | Jul 25, 2021 |
| ASUSTek       | TUF GAMING FX504GD_FX80G... | Notebook    | [686f21af90](https://linux-hardware.org/?probe=686f21af90) | Jul 25, 2021 |
| Dell          | XPS L322X                   | Notebook    | [6b0ab2e22d](https://linux-hardware.org/?probe=6b0ab2e22d) | Jul 25, 2021 |
| Intel         | DP55WG AAE57269-407         | Desktop     | [fa1be73a3f](https://linux-hardware.org/?probe=fa1be73a3f) | Jul 25, 2021 |
| ASRock        | B85 Anniversary             | Desktop     | [b9bdc402ce](https://linux-hardware.org/?probe=b9bdc402ce) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [db0c50510b](https://linux-hardware.org/?probe=db0c50510b) | Jul 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [c873d77069](https://linux-hardware.org/?probe=c873d77069) | Jul 25, 2021 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [722792ec34](https://linux-hardware.org/?probe=722792ec34) | Jul 25, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [6630c7ef27](https://linux-hardware.org/?probe=6630c7ef27) | Jul 25, 2021 |
| Lenovo        | 3110 SDK0J40697 WIN 3305... | All in one  | [84b6274afe](https://linux-hardware.org/?probe=84b6274afe) | Jul 25, 2021 |
| Lenovo        | Yoga 530-14IKB 81EK         | Convertible | [e1db015807](https://linux-hardware.org/?probe=e1db015807) | Jul 25, 2021 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [b0f56654dc](https://linux-hardware.org/?probe=b0f56654dc) | Jul 25, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [be67f17212](https://linux-hardware.org/?probe=be67f17212) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [cd13d1596f](https://linux-hardware.org/?probe=cd13d1596f) | Jul 25, 2021 |
| Dell          | XPS 13 9300                 | Notebook    | [15012d7630](https://linux-hardware.org/?probe=15012d7630) | Jul 25, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [beec8a1c7d](https://linux-hardware.org/?probe=beec8a1c7d) | Jul 25, 2021 |
| Panasonic     | CF-AX2LDCZMF                | Notebook    | [31feab61fe](https://linux-hardware.org/?probe=31feab61fe) | Jul 25, 2021 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [3dae264c17](https://linux-hardware.org/?probe=3dae264c17) | Jul 25, 2021 |
| HP            | Laptop 14-ck0xxx            | Notebook    | [814f91322d](https://linux-hardware.org/?probe=814f91322d) | Jul 25, 2021 |
| Dell          | Inspiron 5423               | Notebook    | [f15c87c33c](https://linux-hardware.org/?probe=f15c87c33c) | Jul 25, 2021 |
| Lenovo        | ThinkPad T480s 20L8S7HF0... | Notebook    | [5417d20b5b](https://linux-hardware.org/?probe=5417d20b5b) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2349GCG       | Notebook    | [7275a5dc90](https://linux-hardware.org/?probe=7275a5dc90) | Jul 25, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [8e2d810033](https://linux-hardware.org/?probe=8e2d810033) | Jul 25, 2021 |
| Lenovo        | ThinkPad T450s 20BX004QG... | Notebook    | [079f1c9006](https://linux-hardware.org/?probe=079f1c9006) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [6f137bd0e5](https://linux-hardware.org/?probe=6f137bd0e5) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [94307be3d8](https://linux-hardware.org/?probe=94307be3d8) | Jul 25, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [9e0045da76](https://linux-hardware.org/?probe=9e0045da76) | Jul 25, 2021 |
| MSI           | Modern 15 A11M              | Notebook    | [acfcaa9077](https://linux-hardware.org/?probe=acfcaa9077) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [fb8dc2feb1](https://linux-hardware.org/?probe=fb8dc2feb1) | Jul 25, 2021 |
| HP            | Stream Notebook             | Notebook    | [078c5d40f8](https://linux-hardware.org/?probe=078c5d40f8) | Jul 25, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [49198ead06](https://linux-hardware.org/?probe=49198ead06) | Jul 25, 2021 |
| Compulab      | fitlet2                     | Mini pc     | [9d1571afa4](https://linux-hardware.org/?probe=9d1571afa4) | Jul 25, 2021 |
| Gigabyte      | H61MS                       | Desktop     | [742ede3c3e](https://linux-hardware.org/?probe=742ede3c3e) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | Notebook    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| Gigabyte      | H81M-S2H GSM                | Desktop     | [f49c35b208](https://linux-hardware.org/?probe=f49c35b208) | Jul 25, 2021 |
| Dell          | 09KPNV A01                  | Desktop     | [fb6ec7188c](https://linux-hardware.org/?probe=fb6ec7188c) | Jul 25, 2021 |
| Dell          | Inspiron 5402               | Notebook    | [f54ac49b39](https://linux-hardware.org/?probe=f54ac49b39) | Jul 25, 2021 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [fca7acc5ee](https://linux-hardware.org/?probe=fca7acc5ee) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [10fb3b6e94](https://linux-hardware.org/?probe=10fb3b6e94) | Jul 25, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [96fd57ba79](https://linux-hardware.org/?probe=96fd57ba79) | Jul 25, 2021 |
| Lenovo        | ThinkPad X260 20F5S46R00    | Notebook    | [c72e326772](https://linux-hardware.org/?probe=c72e326772) | Jul 25, 2021 |
| ASUSTek       | H61M-K                      | Desktop     | [1cf0bdeec4](https://linux-hardware.org/?probe=1cf0bdeec4) | Jul 25, 2021 |
| Dell          | 0NK5PH A00                  | Desktop     | [d6444ebf26](https://linux-hardware.org/?probe=d6444ebf26) | Jul 25, 2021 |
| Gigabyte      | AERO 15 KB                  | Notebook    | [d66f45fc2e](https://linux-hardware.org/?probe=d66f45fc2e) | Jul 25, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [522d784ace](https://linux-hardware.org/?probe=522d784ace) | Jul 25, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [558f739aab](https://linux-hardware.org/?probe=558f739aab) | Jul 25, 2021 |
| Intel         | DP55WB AAE64798-206         | Desktop     | [9c9e82f80f](https://linux-hardware.org/?probe=9c9e82f80f) | Jul 25, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [2c9c978361](https://linux-hardware.org/?probe=2c9c978361) | Jul 25, 2021 |
| Lenovo        | ThinkPad T420 4236WC3       | Notebook    | [2dbdc931e7](https://linux-hardware.org/?probe=2dbdc931e7) | Jul 25, 2021 |
| Lenovo        | ThinkPad E14 20RB000UBR     | Notebook    | [c25d549bd7](https://linux-hardware.org/?probe=c25d549bd7) | Jul 25, 2021 |
| HP            | Laptop 15-ef1xxx            | Notebook    | [9f0fbc1613](https://linux-hardware.org/?probe=9f0fbc1613) | Jul 25, 2021 |
| Protectli     | FW6                         | Desktop     | [0efef10e76](https://linux-hardware.org/?probe=0efef10e76) | Jul 25, 2021 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [dd3347639f](https://linux-hardware.org/?probe=dd3347639f) | Jul 25, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [f7c4474b4d](https://linux-hardware.org/?probe=f7c4474b4d) | Jul 25, 2021 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [df5c29f984](https://linux-hardware.org/?probe=df5c29f984) | Jul 25, 2021 |
| Gigabyte      | 970A-D3P                    | Desktop     | [c564faffdb](https://linux-hardware.org/?probe=c564faffdb) | Jul 25, 2021 |
| Lenovo        | Yoga 710-11ISK 80TX         | Convertible | [c34bcc095c](https://linux-hardware.org/?probe=c34bcc095c) | Jul 25, 2021 |
| Dell          | 0D441T A03                  | Desktop     | [41283af596](https://linux-hardware.org/?probe=41283af596) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [17b5a12640](https://linux-hardware.org/?probe=17b5a12640) | Jul 25, 2021 |
| MSI           | H110I PRO AC                | Desktop     | [08094a9121](https://linux-hardware.org/?probe=08094a9121) | Jul 25, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| MSI           | Z77MA-G45                   | Desktop     | [bbc6d96681](https://linux-hardware.org/?probe=bbc6d96681) | Jul 25, 2021 |
| Lenovo        | ThinkPad T430 2347FF9       | Notebook    | [cdc7a6e9c8](https://linux-hardware.org/?probe=cdc7a6e9c8) | Jul 25, 2021 |
| HP            | 2000                        | Notebook    | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| Acer          | Aspire A515-41G             | Notebook    | [a34056020d](https://linux-hardware.org/?probe=a34056020d) | Jul 25, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [884f8f2850](https://linux-hardware.org/?probe=884f8f2850) | Jul 25, 2021 |
| Dell          | XPS 13 7390                 | Notebook    | [02e6821b40](https://linux-hardware.org/?probe=02e6821b40) | Jul 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [1e8f9a7189](https://linux-hardware.org/?probe=1e8f9a7189) | Jul 24, 2021 |
| Lenovo        | IdeaPad S145-14AST 81ST     | Notebook    | [4cf2681a8c](https://linux-hardware.org/?probe=4cf2681a8c) | Jul 24, 2021 |
| HP            | EliteBook x360 1030 G3      | Convertible | [0c49a20e7c](https://linux-hardware.org/?probe=0c49a20e7c) | Jul 24, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [b0e58bf8de](https://linux-hardware.org/?probe=b0e58bf8de) | Jul 24, 2021 |
| Gigabyte      | B560M D3H                   | Desktop     | [1456f9bf8e](https://linux-hardware.org/?probe=1456f9bf8e) | Jul 23, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [3491bd4228](https://linux-hardware.org/?probe=3491bd4228) | Jul 23, 2021 |
| Lenovo        | ThinkPad E595 20NF0005IX    | Notebook    | [dd220c0bdb](https://linux-hardware.org/?probe=dd220c0bdb) | Jul 23, 2021 |
| Gigabyte      | AERO 17-SA                  | Notebook    | [eaff86e276](https://linux-hardware.org/?probe=eaff86e276) | Jul 23, 2021 |
| Acer          | Aspire A715-72G             | Notebook    | [b436023dda](https://linux-hardware.org/?probe=b436023dda) | Jul 23, 2021 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [ecd10ec3a7](https://linux-hardware.org/?probe=ecd10ec3a7) | Jul 22, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1abb08da83](https://linux-hardware.org/?probe=1abb08da83) | Jul 21, 2021 |
| Supermicro    | X11DDW-L                    | Server      | [6fab4e3135](https://linux-hardware.org/?probe=6fab4e3135) | Jul 20, 2021 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [4ed280d4c8](https://linux-hardware.org/?probe=4ed280d4c8) | Jul 19, 2021 |
| ASUSTek       | ROG STRIX Z370-H GAMING     | Desktop     | [8af9716200](https://linux-hardware.org/?probe=8af9716200) | Jul 19, 2021 |
| ASUSTek       | P8Z68-V                     | Desktop     | [1a60e02aa9](https://linux-hardware.org/?probe=1a60e02aa9) | Jul 19, 2021 |
| Dell          | 0H5J4J A01                  | Server      | [fbdf83f7ff](https://linux-hardware.org/?probe=fbdf83f7ff) | Jul 17, 2021 |
| HP            | ProLiant MicroServer        | Desktop     | [ca7c4b4967](https://linux-hardware.org/?probe=ca7c4b4967) | Jul 16, 2021 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [acca72e9c1](https://linux-hardware.org/?probe=acca72e9c1) | Jul 15, 2021 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [a5daecad1d](https://linux-hardware.org/?probe=a5daecad1d) | Jul 15, 2021 |
| Dell          | Precision 3540              | Notebook    | [383ebf30aa](https://linux-hardware.org/?probe=383ebf30aa) | Jul 14, 2021 |
| Itautec       | Infoway                     | Notebook    | [06dc7b0fd1](https://linux-hardware.org/?probe=06dc7b0fd1) | Jul 14, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [71d234aaef](https://linux-hardware.org/?probe=71d234aaef) | Jul 14, 2021 |
| MSI           | A68HM-E33 V2                | Desktop     | [983bc90bc7](https://linux-hardware.org/?probe=983bc90bc7) | Jul 14, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [6ed4934b61](https://linux-hardware.org/?probe=6ed4934b61) | Jul 13, 2021 |
| Acer          | Aspire 7741                 | Notebook    | [ee5a2b2029](https://linux-hardware.org/?probe=ee5a2b2029) | Jul 13, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [54bfb26e0f](https://linux-hardware.org/?probe=54bfb26e0f) | Jul 12, 2021 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [98271924ba](https://linux-hardware.org/?probe=98271924ba) | Jul 11, 2021 |
| Lenovo        | ThinkPad T430 2349V4B       | Notebook    | [d39fe8e9d4](https://linux-hardware.org/?probe=d39fe8e9d4) | Jul 11, 2021 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [1cb0058b88](https://linux-hardware.org/?probe=1cb0058b88) | Jul 10, 2021 |
| Huanan        | X99-F8 V2.0                 | Desktop     | [776f848ccd](https://linux-hardware.org/?probe=776f848ccd) | Jul 09, 2021 |
| Dell          | 0M863N A00                  | Desktop     | [574671bbb9](https://linux-hardware.org/?probe=574671bbb9) | Jul 09, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [e6aa891005](https://linux-hardware.org/?probe=e6aa891005) | Jul 08, 2021 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [c79b71d033](https://linux-hardware.org/?probe=c79b71d033) | Jul 08, 2021 |
| ASUSTek       | H81M-E                      | Desktop     | [02c3ce63e7](https://linux-hardware.org/?probe=02c3ce63e7) | Jul 08, 2021 |
| HP            | 2215                        | Desktop     | [b0b56138b2](https://linux-hardware.org/?probe=b0b56138b2) | Jul 08, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [b31688ecfa](https://linux-hardware.org/?probe=b31688ecfa) | Jul 08, 2021 |
| HP            | 2215                        | Desktop     | [cdf48de6b2](https://linux-hardware.org/?probe=cdf48de6b2) | Jul 07, 2021 |
| Dell          | Latitude E6330              | Notebook    | [321bec10eb](https://linux-hardware.org/?probe=321bec10eb) | Jul 05, 2021 |
| HP            | Compaq 6830s                | Notebook    | [9c47e76afe](https://linux-hardware.org/?probe=9c47e76afe) | Jul 04, 2021 |
| MSI           | MS-6712                     | Desktop     | [ced0409e55](https://linux-hardware.org/?probe=ced0409e55) | Jul 04, 2021 |
| HP            | Compaq 6830s                | Notebook    | [b524035304](https://linux-hardware.org/?probe=b524035304) | Jul 04, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [b760b0d9cc](https://linux-hardware.org/?probe=b760b0d9cc) | Jul 03, 2021 |
| Acer          | Aspire A515-51              | Notebook    | [f94bb31c5a](https://linux-hardware.org/?probe=f94bb31c5a) | Jul 03, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | Notebook    | [c24fcd1454](https://linux-hardware.org/?probe=c24fcd1454) | Jul 02, 2021 |
| Dell          | Latitude 7410               | Convertible | [457f309f39](https://linux-hardware.org/?probe=457f309f39) | Jul 02, 2021 |
| Dell          | Latitude 7410               | Convertible | [945a4600c4](https://linux-hardware.org/?probe=945a4600c4) | Jul 02, 2021 |
| ASRock        | H77 Pro4-M                  | Desktop     | [8ba58cff9a](https://linux-hardware.org/?probe=8ba58cff9a) | Jul 02, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [cb62272a68](https://linux-hardware.org/?probe=cb62272a68) | Jul 02, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [44b96068f2](https://linux-hardware.org/?probe=44b96068f2) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [5729444e9b](https://linux-hardware.org/?probe=5729444e9b) | Jul 02, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [bd3211a03b](https://linux-hardware.org/?probe=bd3211a03b) | Jun 30, 2021 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [c8cb82f74d](https://linux-hardware.org/?probe=c8cb82f74d) | Jun 30, 2021 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [e325df530d](https://linux-hardware.org/?probe=e325df530d) | Jun 30, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [24a52836b4](https://linux-hardware.org/?probe=24a52836b4) | Jun 30, 2021 |
| HP            | ProBook 640 G3              | Notebook    | [c56b8f3ff1](https://linux-hardware.org/?probe=c56b8f3ff1) | Jun 29, 2021 |
| MSI           | B85M-G43                    | Desktop     | [4598afdf7e](https://linux-hardware.org/?probe=4598afdf7e) | Jun 29, 2021 |
| HP            | ZBook 17 G5                 | Notebook    | [5557a5c23c](https://linux-hardware.org/?probe=5557a5c23c) | Jun 29, 2021 |
| Lenovo        | IdeaPad Z580                | Notebook    | [6a9d31c8ef](https://linux-hardware.org/?probe=6a9d31c8ef) | Jun 29, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [5335641d04](https://linux-hardware.org/?probe=5335641d04) | Jun 28, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [0632a7bf28](https://linux-hardware.org/?probe=0632a7bf28) | Jun 28, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [834b68e61a](https://linux-hardware.org/?probe=834b68e61a) | Jun 28, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [65c54db09e](https://linux-hardware.org/?probe=65c54db09e) | Jun 27, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [fda3d18cf7](https://linux-hardware.org/?probe=fda3d18cf7) | Jun 27, 2021 |
| Huanan        | X99-8M-F V1.1               | Desktop     | [8ecfcffbaf](https://linux-hardware.org/?probe=8ecfcffbaf) | Jun 27, 2021 |
| HP            | ZBook Fury 17 G7 Mobile ... | Notebook    | [c3d5fd07c1](https://linux-hardware.org/?probe=c3d5fd07c1) | Jun 27, 2021 |
| ASRock        | FM2A68M-HD+                 | Desktop     | [f435417b41](https://linux-hardware.org/?probe=f435417b41) | Jun 26, 2021 |
| Acer          | Nitro AN515-51              | Notebook    | [6c4a46b4ec](https://linux-hardware.org/?probe=6c4a46b4ec) | Jun 26, 2021 |
| Pine Micro... | Pine64 PinePhone (1.2) (... | Phone       | [6805b89f3d](https://linux-hardware.org/?probe=6805b89f3d) | Jun 25, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [807a4ba37d](https://linux-hardware.org/?probe=807a4ba37d) | Jun 23, 2021 |
| Gigabyte      | Z370 AORUS Gaming 5-CF      | Desktop     | [bc7246038e](https://linux-hardware.org/?probe=bc7246038e) | Jun 23, 2021 |
| ASRock        | B550 Pro4                   | Desktop     | [ef1b7bfb77](https://linux-hardware.org/?probe=ef1b7bfb77) | Jun 23, 2021 |
| ASRock        | X399 Taichi                 | Desktop     | [a664e4cf99](https://linux-hardware.org/?probe=a664e4cf99) | Jun 23, 2021 |
| HARDKERNEL    | ODROID-H2                   | Desktop     | [c9fed56a36](https://linux-hardware.org/?probe=c9fed56a36) | Jun 23, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [d6f07cb592](https://linux-hardware.org/?probe=d6f07cb592) | Jun 23, 2021 |
| Dell          | 04WYPY A04                  | Server      | [20fa770830](https://linux-hardware.org/?probe=20fa770830) | Jun 22, 2021 |
| MSI           | GF65 Thin 10UE              | Notebook    | [d1e0b6ee58](https://linux-hardware.org/?probe=d1e0b6ee58) | Jun 22, 2021 |
| Lenovo        | ThinkPad T495 20NKS0PG00    | Notebook    | [9e646a384e](https://linux-hardware.org/?probe=9e646a384e) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [b3a5333d2a](https://linux-hardware.org/?probe=b3a5333d2a) | Jun 21, 2021 |
| Dell          | Precision 3560              | Notebook    | [81efcf647c](https://linux-hardware.org/?probe=81efcf647c) | Jun 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [75c4ec9e5a](https://linux-hardware.org/?probe=75c4ec9e5a) | Jun 21, 2021 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [08fc06c75e](https://linux-hardware.org/?probe=08fc06c75e) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [c62a9a5058](https://linux-hardware.org/?probe=c62a9a5058) | Jun 20, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [5a39dabe8a](https://linux-hardware.org/?probe=5a39dabe8a) | Jun 20, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [b37bec27b3](https://linux-hardware.org/?probe=b37bec27b3) | Jun 20, 2021 |
| Dell          | Latitude E7470              | Notebook    | [49cb9ff0b0](https://linux-hardware.org/?probe=49cb9ff0b0) | Jun 20, 2021 |
| Acer          | Aspire 5750G                | Notebook    | [73d6b46b6b](https://linux-hardware.org/?probe=73d6b46b6b) | Jun 19, 2021 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [a894e25838](https://linux-hardware.org/?probe=a894e25838) | Jun 19, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [dde7123487](https://linux-hardware.org/?probe=dde7123487) | Jun 19, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [33ffb80782](https://linux-hardware.org/?probe=33ffb80782) | Jun 19, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [842c53b8e2](https://linux-hardware.org/?probe=842c53b8e2) | Jun 18, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [1a8a3efde5](https://linux-hardware.org/?probe=1a8a3efde5) | Jun 18, 2021 |
| Lenovo        | ThinkPad X230 2325AZ8       | Notebook    | [b5ea5009bf](https://linux-hardware.org/?probe=b5ea5009bf) | Jun 18, 2021 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [259fc86278](https://linux-hardware.org/?probe=259fc86278) | Jun 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [9e3e72ec72](https://linux-hardware.org/?probe=9e3e72ec72) | Jun 17, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [c26c0f6e33](https://linux-hardware.org/?probe=c26c0f6e33) | Jun 15, 2021 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [0ccc446224](https://linux-hardware.org/?probe=0ccc446224) | Jun 14, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [eb77944ea2](https://linux-hardware.org/?probe=eb77944ea2) | Jun 14, 2021 |
| Gigabyte      | MCMLUAB-00                  | Desktop     | [99780e8ba8](https://linux-hardware.org/?probe=99780e8ba8) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | Notebook    | [91f4f7aab6](https://linux-hardware.org/?probe=91f4f7aab6) | Jun 13, 2021 |
| UNOWHY        | Y13G002S4EI                 | Notebook    | [3d25dc9f69](https://linux-hardware.org/?probe=3d25dc9f69) | Jun 13, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [2d1f6364aa](https://linux-hardware.org/?probe=2d1f6364aa) | Jun 13, 2021 |
| Acer          | Aspire V3-331               | Notebook    | [02e288caf9](https://linux-hardware.org/?probe=02e288caf9) | Jun 13, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [1b2cda6c08](https://linux-hardware.org/?probe=1b2cda6c08) | Jun 12, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [f2770a810e](https://linux-hardware.org/?probe=f2770a810e) | Jun 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [f6ba765876](https://linux-hardware.org/?probe=f6ba765876) | Jun 12, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [57684125de](https://linux-hardware.org/?probe=57684125de) | Jun 12, 2021 |
| Unknown       | Helios64                    | Soc         | [33c6248333](https://linux-hardware.org/?probe=33c6248333) | Jun 11, 2021 |
| Dell          | 0Y7WYT A00                  | Desktop     | [8e424773e5](https://linux-hardware.org/?probe=8e424773e5) | Jun 10, 2021 |
| Dell          | Latitude E7470              | Notebook    | [51c1f3f1f5](https://linux-hardware.org/?probe=51c1f3f1f5) | Jun 10, 2021 |
| ASUSTek       | Z97-AR                      | Desktop     | [709a74c713](https://linux-hardware.org/?probe=709a74c713) | Jun 09, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [377f2e9ec6](https://linux-hardware.org/?probe=377f2e9ec6) | Jun 09, 2021 |
| Dell          | Latitude E6330              | Notebook    | [ba88cd6328](https://linux-hardware.org/?probe=ba88cd6328) | Jun 08, 2021 |
| Lenovo        | ThinkPad T430s 2356A89      | Notebook    | [0195b8564e](https://linux-hardware.org/?probe=0195b8564e) | Jun 08, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [ee4dfdfde3](https://linux-hardware.org/?probe=ee4dfdfde3) | Jun 08, 2021 |
| Acer          | Aspire ES1-132              | Notebook    | [2db77f0d01](https://linux-hardware.org/?probe=2db77f0d01) | Jun 07, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [69dd9fbe20](https://linux-hardware.org/?probe=69dd9fbe20) | Jun 07, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [548356ed30](https://linux-hardware.org/?probe=548356ed30) | Jun 06, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [f65812f774](https://linux-hardware.org/?probe=f65812f774) | Jun 06, 2021 |
| ASUSTek       | M3N                         | Notebook    | [ec5f914161](https://linux-hardware.org/?probe=ec5f914161) | Jun 06, 2021 |
| ASUSTek       | M3N                         | Notebook    | [bd89f26d7e](https://linux-hardware.org/?probe=bd89f26d7e) | Jun 05, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [0fd993c4dd](https://linux-hardware.org/?probe=0fd993c4dd) | Jun 05, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [5c16d903d3](https://linux-hardware.org/?probe=5c16d903d3) | Jun 05, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [47e9dfd146](https://linux-hardware.org/?probe=47e9dfd146) | Jun 05, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [90dbe22a68](https://linux-hardware.org/?probe=90dbe22a68) | Jun 05, 2021 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [e20b51102d](https://linux-hardware.org/?probe=e20b51102d) | Jun 03, 2021 |
| Lenovo        | ThinkPad T495 20NJCTO1WW    | Notebook    | [b513f2fc77](https://linux-hardware.org/?probe=b513f2fc77) | Jun 03, 2021 |
| ASUSTek       | M4A88T-M/USB3               | Desktop     | [7483847993](https://linux-hardware.org/?probe=7483847993) | Jun 03, 2021 |
| Monster       | ABRA A5 V15.2               | Notebook    | [012bfa586d](https://linux-hardware.org/?probe=012bfa586d) | Jun 02, 2021 |
| Pegatron      | A15                         | Notebook    | [dec1b6b43a](https://linux-hardware.org/?probe=dec1b6b43a) | Jun 02, 2021 |
| Dell          | 0YXT71 A02                  | Desktop     | [a45729e01a](https://linux-hardware.org/?probe=a45729e01a) | Jun 01, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [ac80feea4f](https://linux-hardware.org/?probe=ac80feea4f) | Jun 01, 2021 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [21574f62a5](https://linux-hardware.org/?probe=21574f62a5) | Jun 01, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [80cf3dc8e7](https://linux-hardware.org/?probe=80cf3dc8e7) | Jun 01, 2021 |
| HP            | Compaq tc4400 (GE179UP#A... | Notebook    | [eeaee9f1ad](https://linux-hardware.org/?probe=eeaee9f1ad) | Jun 01, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f77e2ebb10](https://linux-hardware.org/?probe=f77e2ebb10) | May 31, 2021 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [926229be87](https://linux-hardware.org/?probe=926229be87) | May 31, 2021 |
| Toshiba       | Satellite U800W             | Notebook    | [ac79b35dfd](https://linux-hardware.org/?probe=ac79b35dfd) | May 30, 2021 |
| MSI           | U90/U100                    | Notebook    | [477251f62e](https://linux-hardware.org/?probe=477251f62e) | May 30, 2021 |
| MSI           | U90/U100                    | Notebook    | [1a0476551b](https://linux-hardware.org/?probe=1a0476551b) | May 30, 2021 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [eb3d04e089](https://linux-hardware.org/?probe=eb3d04e089) | May 29, 2021 |
| Intel         | NUC10i7FNB K61360-302       | Mini pc     | [92aa2017b9](https://linux-hardware.org/?probe=92aa2017b9) | May 29, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [c33e7ced42](https://linux-hardware.org/?probe=c33e7ced42) | May 29, 2021 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [24d2e85009](https://linux-hardware.org/?probe=24d2e85009) | May 29, 2021 |
| MSI           | CX700                       | Notebook    | [ef40976753](https://linux-hardware.org/?probe=ef40976753) | May 29, 2021 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [7ca350189c](https://linux-hardware.org/?probe=7ca350189c) | May 29, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [5de2c933c1](https://linux-hardware.org/?probe=5de2c933c1) | May 28, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [88cee1e822](https://linux-hardware.org/?probe=88cee1e822) | May 28, 2021 |
| Samsung       | 370E4K                      | Notebook    | [125fbb3d15](https://linux-hardware.org/?probe=125fbb3d15) | May 28, 2021 |
| MSI           | CX700                       | Notebook    | [535d0016e2](https://linux-hardware.org/?probe=535d0016e2) | May 27, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [fb2eef67f2](https://linux-hardware.org/?probe=fb2eef67f2) | May 26, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [c091670daa](https://linux-hardware.org/?probe=c091670daa) | May 25, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [ad6cd7847f](https://linux-hardware.org/?probe=ad6cd7847f) | May 24, 2021 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [2c698534c6](https://linux-hardware.org/?probe=2c698534c6) | May 23, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [f03341d873](https://linux-hardware.org/?probe=f03341d873) | May 23, 2021 |
| Gigabyte      | AB350M-D3H-CF               | Desktop     | [1ad175fddc](https://linux-hardware.org/?probe=1ad175fddc) | May 23, 2021 |
| Dell          | Latitude 7410               | Convertible | [bc7c58f248](https://linux-hardware.org/?probe=bc7c58f248) | May 21, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [6573923d55](https://linux-hardware.org/?probe=6573923d55) | May 21, 2021 |
| Lenovo        | ThinkPad X1 Tablet 20GGS... | Tablet      | [1c271464f4](https://linux-hardware.org/?probe=1c271464f4) | May 21, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [8b7b153998](https://linux-hardware.org/?probe=8b7b153998) | May 20, 2021 |
| Dell          | Latitude 7410               | Convertible | [cbd8832f44](https://linux-hardware.org/?probe=cbd8832f44) | May 19, 2021 |
| Dell          | Latitude 7480               | Notebook    | [0f2477786d](https://linux-hardware.org/?probe=0f2477786d) | May 19, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4PN0... | Notebook    | [f8b2c84bc1](https://linux-hardware.org/?probe=f8b2c84bc1) | May 19, 2021 |
| sunxi         | Unknown                     | Soc         | [d54c3a2a33](https://linux-hardware.org/?probe=d54c3a2a33) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [b9d0acf0a6](https://linux-hardware.org/?probe=b9d0acf0a6) | May 19, 2021 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [97a658e572](https://linux-hardware.org/?probe=97a658e572) | May 19, 2021 |
| Gigabyte      | Z170X-GamingG1              | Desktop     | [361469c7d5](https://linux-hardware.org/?probe=361469c7d5) | May 18, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [28bb88d60c](https://linux-hardware.org/?probe=28bb88d60c) | May 17, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FEA0... | Convertible | [2a0eca4670](https://linux-hardware.org/?probe=2a0eca4670) | May 17, 2021 |
| HP            | Compaq Presario C700        | Notebook    | [91a939ce16](https://linux-hardware.org/?probe=91a939ce16) | May 16, 2021 |
| Acer          | Aspire A315-23G             | Notebook    | [646b64ccb3](https://linux-hardware.org/?probe=646b64ccb3) | May 15, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [71f4ed3e35](https://linux-hardware.org/?probe=71f4ed3e35) | May 11, 2021 |
| Lenovo        | MAHOBAY                     | Desktop     | [c0b8e99e35](https://linux-hardware.org/?probe=c0b8e99e35) | May 06, 2021 |
| HP            | Split 13 x2 PC              | Notebook    | [5834b6321d](https://linux-hardware.org/?probe=5834b6321d) | May 05, 2021 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [bf3e99374e](https://linux-hardware.org/?probe=bf3e99374e) | Apr 29, 2021 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [a06f2bc29e](https://linux-hardware.org/?probe=a06f2bc29e) | Apr 27, 2021 |
| Biostar       | B450MH                      | Desktop     | [f0a1151d81](https://linux-hardware.org/?probe=f0a1151d81) | Apr 27, 2021 |
| ASUSTek       | ZenBook UX333FN_UX333FN     | Notebook    | [a042fd63c6](https://linux-hardware.org/?probe=a042fd63c6) | Apr 27, 2021 |
| Dell          | Inspiron 3793               | Notebook    | [a4c79ea8c3](https://linux-hardware.org/?probe=a4c79ea8c3) | Apr 26, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [446238dd0c](https://linux-hardware.org/?probe=446238dd0c) | Apr 25, 2021 |
| Chuwi         | Hi10 pro tablet             | Tablet      | [bb76391a12](https://linux-hardware.org/?probe=bb76391a12) | Apr 25, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [bcea790fba](https://linux-hardware.org/?probe=bcea790fba) | Apr 24, 2021 |
| Lenovo        | ThinkPad T430s 23533KJ      | Notebook    | [39aa120e47](https://linux-hardware.org/?probe=39aa120e47) | Apr 21, 2021 |
| Dell          | Inspiron 5468               | Notebook    | [cfc77b26b5](https://linux-hardware.org/?probe=cfc77b26b5) | Apr 17, 2021 |
| Gigabyte      | EG41MF-US2H                 | Desktop     | [a2aa6eaec8](https://linux-hardware.org/?probe=a2aa6eaec8) | Apr 16, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [4967255e37](https://linux-hardware.org/?probe=4967255e37) | Apr 14, 2021 |
| Lenovo        | ThinkPad T530 24296HG       | Notebook    | [e1a5725060](https://linux-hardware.org/?probe=e1a5725060) | Apr 14, 2021 |
| sunxi         | Banana Pi BPI-M2-Ultra      | Soc         | [c0536c5433](https://linux-hardware.org/?probe=c0536c5433) | Apr 13, 2021 |
| sunxi         | Banana Pi BPI-M2-Ultra      | Soc         | [935ccffcd5](https://linux-hardware.org/?probe=935ccffcd5) | Feb 01, 2021 |
| Unknown       | Shenzhen Amediatech Tech... | Soc         | [2fed627592](https://linux-hardware.org/?probe=2fed627592) | Jan 18, 2021 |
| sunxi         | Unknown                     | Soc         | [604dd9d393](https://linux-hardware.org/?probe=604dd9d393) | Feb 25, 2020 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                        | Computers | Percent |
|--------------------------------|-----------|---------|
| 5.10.0-8-amd64                 | 319       | 58.96%  |
| 5.10.0-7-amd64                 | 112       | 20.7%   |
| 5.10.0-6-amd64                 | 37        | 6.84%   |
| 5.10.0-8-686-pae               | 6         | 1.11%   |
| 5.11.22-1-pve                  | 5         | 0.92%   |
| 5.10.0-8-686                   | 4         | 0.74%   |
| 5.12.0-19.3-liquorix-amd64     | 2         | 0.37%   |
| 5.11.22-2-pve                  | 2         | 0.37%   |
| 5.10.42+truenas                | 2         | 0.37%   |
| 5.10.0-8-rt-amd64              | 2         | 0.37%   |
| 5.10-sunxi64                   | 2         | 0.37%   |
| 4.19.0-14-amd64                | 2         | 0.37%   |
| 5.9.0-arm-64                   | 1         | 0.18%   |
| 5.8.0-3-amd64                  | 1         | 0.18%   |
| 5.4.18-sunxi64                 | 1         | 0.18%   |
| 5.4.0-73-generic               | 1         | 0.18%   |
| 5.14.0-rc3-prygun              | 1         | 0.18%   |
| 5.13.8-xanmod1                 | 1         | 0.18%   |
| 5.13.8-gnu                     | 1         | 0.18%   |
| 5.13.8                         | 1         | 0.18%   |
| 5.13.5-xanmod1                 | 1         | 0.18%   |
| 5.13.4-e5520                   | 1         | 0.18%   |
| 5.13.4                         | 1         | 0.18%   |
| 5.13.1a                        | 1         | 0.18%   |
| 5.13.0-rc7-00024-g0418ae8de752 | 1         | 0.18%   |
| 5.12.4                         | 1         | 0.18%   |
| 5.12.10                        | 1         | 0.18%   |
| 5.12.1                         | 1         | 0.18%   |
| 5.12.0-9.2-liquorix-amd64      | 1         | 0.18%   |
| 5.12.0-14.2-liquorix-amd64     | 1         | 0.18%   |
| 5.11.9+                        | 1         | 0.18%   |
| 5.11.22-3-pve                  | 1         | 0.18%   |
| 5.11.15-terranz                | 1         | 0.18%   |
| 5.11.15-051115-generic         | 1         | 0.18%   |
| 5.11.14                        | 1         | 0.18%   |
| 5.11.0-rc6                     | 1         | 0.18%   |
| 5.11.0-21.1-liquorix-amd64     | 1         | 0.18%   |
| 5.11.0-16.1-liquorix-amd64     | 1         | 0.18%   |
| 5.10.52-v8+                    | 1         | 0.18%   |
| 5.10.46custom                  | 1         | 0.18%   |
| 5.10.40-ismynik                | 1         | 0.18%   |
| 5.10.38-falcot                 | 1         | 0.18%   |
| 5.10.35-rockchip64             | 1         | 0.18%   |
| 5.10.21-sunxi                  | 1         | 0.18%   |
| 5.10.12-sunxi                  | 1         | 0.18%   |
| 5.10.10-64                     | 1         | 0.18%   |
| 5.10.0-io7-amd64               | 1         | 0.18%   |
| 5.10.0-8-armmp                 | 1         | 0.18%   |
| 5.10.0-7-686-pae               | 1         | 0.18%   |
| 5.10.0-6-rt-amd64              | 1         | 0.18%   |
| 5.10.0-6-686                   | 1         | 0.18%   |
| 5.10.0-5-amd64                 | 1         | 0.18%   |
| 5.10.0-4-amd64                 | 1         | 0.18%   |
| 5.10.0-3-amd64                 | 1         | 0.18%   |
| 5.10.0-2-amd64                 | 1         | 0.18%   |
| 4.19.181-z580322               | 1         | 0.18%   |
| 4.19.0-16-amd64                | 1         | 0.18%   |
| 4.19.0-16-686-pae              | 1         | 0.18%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.10.0   | 478       | 90.36%  |
| 5.11.22  | 8         | 1.51%   |
| 4.19.0   | 4         | 0.76%   |
| 5.13.8   | 3         | 0.57%   |
| 5.12.0   | 3         | 0.57%   |
| 5.11.0   | 3         | 0.57%   |
| 5.13.4   | 2         | 0.38%   |
| 5.11.15  | 2         | 0.38%   |
| 5.10.42  | 2         | 0.38%   |
| 5.10     | 2         | 0.38%   |
| 5.9.0    | 1         | 0.19%   |
| 5.8.0    | 1         | 0.19%   |
| 5.4.18   | 1         | 0.19%   |
| 5.4.0    | 1         | 0.19%   |
| 5.14.0   | 1         | 0.19%   |
| 5.13.5   | 1         | 0.19%   |
| 5.13.1   | 1         | 0.19%   |
| 5.13.0   | 1         | 0.19%   |
| 5.12.4   | 1         | 0.19%   |
| 5.12.10  | 1         | 0.19%   |
| 5.12.1   | 1         | 0.19%   |
| 5.11.9   | 1         | 0.19%   |
| 5.11.14  | 1         | 0.19%   |
| 5.10.52  | 1         | 0.19%   |
| 5.10.46  | 1         | 0.19%   |
| 5.10.40  | 1         | 0.19%   |
| 5.10.38  | 1         | 0.19%   |
| 5.10.35  | 1         | 0.19%   |
| 5.10.21  | 1         | 0.19%   |
| 5.10.12  | 1         | 0.19%   |
| 5.10.10  | 1         | 0.19%   |
| 4.19.181 | 1         | 0.19%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 487       | 92.23%  |
| 5.11    | 15        | 2.84%   |
| 5.13    | 8         | 1.52%   |
| 5.12    | 6         | 1.14%   |
| 4.19    | 5         | 0.95%   |
| 5.4     | 2         | 0.38%   |
| 5       | 2         | 0.38%   |
| 5.9     | 1         | 0.19%   |
| 5.8     | 1         | 0.19%   |
| 5.14    | 1         | 0.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 507       | 96.02%  |
| i686    | 13        | 2.46%   |
| aarch64 | 6         | 1.14%   |
| armv7l  | 2         | 0.38%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 136       | 25.61%  |
| Unknown          | 107       | 20.15%  |
| KDE5             | 103       | 19.4%   |
| XFCE             | 55        | 10.36%  |
| MATE             | 34        | 6.4%    |
| Cinnamon         | 15        | 2.82%   |
| LXQt             | 13        | 2.45%   |
| i3               | 13        | 2.45%   |
| X-Cinnamon       | 10        | 1.88%   |
| LXDE             | 10        | 1.88%   |
| KDE              | 10        | 1.88%   |
| lightdm-xsession | 6         | 1.13%   |
| Trinity          | 5         | 0.94%   |
| GNOME Flashback  | 4         | 0.75%   |
| sway             | 2         | 0.38%   |
| openbox          | 2         | 0.38%   |
| ICEWM            | 1         | 0.19%   |
| GNUstep          | 1         | 0.19%   |
| Enlightenment    | 1         | 0.19%   |
| default          | 1         | 0.19%   |
| Budgie           | 1         | 0.19%   |
| awesome          | 1         | 0.19%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 306       | 57.63%  |
| Wayland | 106       | 19.96%  |
| Unknown | 76        | 14.31%  |
| Tty     | 43        | 8.1%    |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 142       | 26.79%  |
| TDM     | 140       | 26.42%  |
| GDM     | 127       | 23.96%  |
| SDDM    | 106       | 20%     |
| LightDM | 9         | 1.7%    |
| SLiM    | 3         | 0.57%   |
| XDM     | 2         | 0.38%   |
| KDM     | 1         | 0.19%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 210       | 39.7%   |
| Unknown | 58        | 10.96%  |
| ru_RU   | 39        | 7.37%   |
| en_GB   | 33        | 6.24%   |
| fr_FR   | 26        | 4.91%   |
| de_DE   | 24        | 4.54%   |
| es_ES   | 17        | 3.21%   |
| pt_BR   | 13        | 2.46%   |
| pl_PL   | 10        | 1.89%   |
| en_IN   | 8         | 1.51%   |
| C       | 8         | 1.51%   |
| it_IT   | 6         | 1.13%   |
| en_CA   | 6         | 1.13%   |
| en_AU   | 6         | 1.13%   |
| sv_SE   | 5         | 0.95%   |
| de_CH   | 5         | 0.95%   |
| tr_TR   | 3         | 0.57%   |
| nn_NO   | 3         | 0.57%   |
| nl_BE   | 3         | 0.57%   |
| ja_JP   | 3         | 0.57%   |
| hu_HU   | 3         | 0.57%   |
| cs_CZ   | 3         | 0.57%   |
| uk_UA   | 2         | 0.38%   |
| ru_UA   | 2         | 0.38%   |
| ro_RO   | 2         | 0.38%   |
| pt_PT   | 2         | 0.38%   |
| hr_HR   | 2         | 0.38%   |
| fi_FI   | 2         | 0.38%   |
| es_MX   | 2         | 0.38%   |
| es_CO   | 2         | 0.38%   |
| en_SG   | 2         | 0.38%   |
| en_NZ   | 2         | 0.38%   |
| en_IE   | 2         | 0.38%   |
| en_HK   | 2         | 0.38%   |
| sr_RS   | 1         | 0.19%   |
| sk_SK   | 1         | 0.19%   |
| nl_NL   | 1         | 0.19%   |
| gl_ES   | 1         | 0.19%   |
| es_VE   | 1         | 0.19%   |
| es_UY   | 1         | 0.19%   |
| es_US   | 1         | 0.19%   |
| es_EC   | 1         | 0.19%   |
| es_AR   | 1         | 0.19%   |
| en_SI   | 1         | 0.19%   |
| en_PH   | 1         | 0.19%   |
| de_AT   | 1         | 0.19%   |
| ca_ES   | 1         | 0.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 333       | 62.83%  |
| BIOS | 197       | 37.17%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 379       | 71.78%  |
| Overlay | 90        | 17.05%  |
| Btrfs   | 34        | 6.44%   |
| Zfs     | 10        | 1.89%   |
| Xfs     | 5         | 0.95%   |
| Ext3    | 5         | 0.95%   |
| Unknown | 4         | 0.76%   |
| Rootfs  | 1         | 0.19%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 366       | 69.06%  |
| MBR     | 121       | 22.83%  |
| Unknown | 43        | 8.11%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 439       | 82.99%  |
| Yes       | 90        | 17.01%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 398       | 75.24%  |
| Yes       | 131       | 24.76%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 110       | 20.83%  |
| ASUSTek Computer        | 69        | 13.07%  |
| Hewlett-Packard         | 65        | 12.31%  |
| Dell                    | 62        | 11.74%  |
| Gigabyte Technology     | 38        | 7.2%    |
| MSI                     | 27        | 5.11%   |
| Google                  | 26        | 4.92%   |
| ASRock                  | 26        | 4.92%   |
| Apple                   | 20        | 3.79%   |
| Acer                    | 20        | 3.79%   |
| Intel                   | 7         | 1.33%   |
| Toshiba                 | 3         | 0.57%   |
| Supermicro              | 3         | 0.57%   |
| sunxi                   | 3         | 0.57%   |
| Samsung Electronics     | 3         | 0.57%   |
| Notebook                | 3         | 0.57%   |
| HUAWEI                  | 3         | 0.57%   |
| Fujitsu                 | 3         | 0.57%   |
| Clevo                   | 3         | 0.57%   |
| Unknown                 | 3         | 0.57%   |
| Semp Toshiba            | 2         | 0.38%   |
| Raspberry Pi Foundation | 2         | 0.38%   |
| Huanan                  | 2         | 0.38%   |
| Foxconn                 | 2         | 0.38%   |
| ZOTAC                   | 1         | 0.19%   |
| UNOWHY                  | 1         | 0.19%   |
| TUXEDO                  | 1         | 0.19%   |
| Sony                    | 1         | 0.19%   |
| SLIMBOOK                | 1         | 0.19%   |
| SimpliVity              | 1         | 0.19%   |
| Shuttle                 | 1         | 0.19%   |
| Quanta                  | 1         | 0.19%   |
| Protectli               | 1         | 0.19%   |
| Pine Microsystems       | 1         | 0.19%   |
| Pegatron                | 1         | 0.19%   |
| PC Specialist           | 1         | 0.19%   |
| Panasonic               | 1         | 0.19%   |
| Monster                 | 1         | 0.19%   |
| Itautec                 | 1         | 0.19%   |
| IBM                     | 1         | 0.19%   |
| HARDKERNEL              | 1         | 0.19%   |
| ECS                     | 1         | 0.19%   |
| Compulab                | 1         | 0.19%   |
| Chuwi                   | 1         | 0.19%   |
| Casper                  | 1         | 0.19%   |
| Biostar                 | 1         | 0.19%   |
| ASRockRack              | 1         | 0.19%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                          | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Google Enguarde                               | 24        | 4.55%   |
| ASUS All Series                               | 5         | 0.95%   |
| Apple MacBookAir7,2                           | 5         | 0.95%   |
| Unknown                                       | 5         | 0.95%   |
| Apple MacBookAir7,1                           | 4         | 0.76%   |
| Gigabyte Z77-D3H                              | 3         | 0.57%   |
| Gigabyte B550I AORUS PRO AX                   | 3         | 0.57%   |
| ASRock B450M Pro4                             | 3         | 0.57%   |
| Semp Toshiba STI                              | 2         | 0.38%   |
| MSI MS-7A70                                   | 2         | 0.38%   |
| Lenovo ThinkPad T490 20N2CTO1WW               | 2         | 0.38%   |
| Lenovo ThinkPad E475 20H40006US               | 2         | 0.38%   |
| Lenovo ThinkBook 14 G2 ARE 20VF               | 2         | 0.38%   |
| Lenovo G50-80 80E5                            | 2         | 0.38%   |
| HUAWEI NBLK-WAX9X                             | 2         | 0.38%   |
| HP Z620 Workstation                           | 2         | 0.38%   |
| HP Laptop 15s-fq2xxx                          | 2         | 0.38%   |
| HP EliteBook 8460p                            | 2         | 0.38%   |
| HP Compaq nx6125 (PZ849UA#ABA)                | 2         | 0.38%   |
| HP Compaq nx6110 (PZ065UA#ABA)                | 2         | 0.38%   |
| Gigabyte Z370 AORUS Gaming 5                  | 2         | 0.38%   |
| Gigabyte 970A-DS3P                            | 2         | 0.38%   |
| Dell XPS 13 9370                              | 2         | 0.38%   |
| Dell XPS 13 9310                              | 2         | 0.38%   |
| Dell XPS 13 7390                              | 2         | 0.38%   |
| Dell Precision 3540                           | 2         | 0.38%   |
| Dell OptiPlex 760                             | 2         | 0.38%   |
| Dell Latitude 7480                            | 2         | 0.38%   |
| Dell Inspiron 5570                            | 2         | 0.38%   |
| Dell Inspiron 3793                            | 2         | 0.38%   |
| ASUS VivoBook_ASUS Laptop E210MA_L210MA       | 2         | 0.38%   |
| ASUS PRIME B550-PLUS                          | 2         | 0.38%   |
| ASUS PRIME B450M-A                            | 2         | 0.38%   |
| ASUS PRIME A320M-K                            | 2         | 0.38%   |
| Apple MacBook5,2                              | 2         | 0.38%   |
| Acer Aspire 5315                              | 2         | 0.38%   |
| ZOTAC ZBOX-EN1070/1060,EN1070K/1060K          | 1         | 0.19%   |
| UNOWHY Y13G002S4EI                            | 1         | 0.19%   |
| TUXEDO Pulse 15 Gen1                          | 1         | 0.19%   |
| Toshiba Satellite U800W                       | 1         | 0.19%   |
| Toshiba Satellite S55-A                       | 1         | 0.19%   |
| Toshiba Satellite C45-A                       | 1         | 0.19%   |
| Supermicro SYS-6019P-WT                       | 1         | 0.19%   |
| Supermicro SYS-5038MA-H24TRF                  | 1         | 0.19%   |
| Supermicro SYS-5019S-MR                       | 1         | 0.19%   |
| sunxi Banana Pi BPI-M2-Ultra                  | 1         | 0.19%   |
| Sony VPCF21AFX                                | 1         | 0.19%   |
| SLIMBOOK PROX14-AMD                           | 1         | 0.19%   |
| SimpliVity OmniCube CN-3400-1                 | 1         | 0.19%   |
| Shuttle SX79R                                 | 1         | 0.19%   |
| Samsung 900X3C/900X3D/900X3E/900X4C/900X4D    | 1         | 0.19%   |
| Samsung 370E4K                                | 1         | 0.19%   |
| Samsung 300E5M/300E5L                         | 1         | 0.19%   |
| RPi Raspberry Pi 4 Model B Rev 1.4            | 1         | 0.19%   |
| RPi Raspberry Pi 2 Model B Rev 1.1            | 1         | 0.19%   |
| Quanta TWC                                    | 1         | 0.19%   |
| Protectli FW6                                 | 1         | 0.19%   |
| Pine Microsystems Pine64 PinePhone (1.2) (DT) | 1         | 0.19%   |
| Pegatron A15                                  | 1         | 0.19%   |
| PC Specialist NV4XMB,ME,MZ                    | 1         | 0.19%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Lenovo ThinkPad              | 80        | 15.15%  |
| Google Enguarde              | 24        | 4.55%   |
| ASUS PRIME                   | 18        | 3.41%   |
| Dell Inspiron                | 16        | 3.03%   |
| Acer Aspire                  | 15        | 2.84%   |
| Lenovo IdeaPad               | 14        | 2.65%   |
| HP ProBook                   | 11        | 2.08%   |
| HP Compaq                    | 11        | 2.08%   |
| Dell XPS                     | 11        | 2.08%   |
| Dell OptiPlex                | 11        | 2.08%   |
| Dell Latitude                | 10        | 1.89%   |
| HP EliteBook                 | 9         | 1.7%    |
| ASUS ROG                     | 9         | 1.7%    |
| Apple MacBookAir7            | 9         | 1.7%    |
| Dell Precision               | 8         | 1.52%   |
| HP Laptop                    | 7         | 1.33%   |
| Lenovo Yoga                  | 5         | 0.95%   |
| ASUS ZenBook                 | 5         | 0.95%   |
| ASUS VivoBook                | 5         | 0.95%   |
| ASUS All                     | 5         | 0.95%   |
| Unknown                      | 5         | 0.95%   |
| Lenovo ThinkCentre           | 4         | 0.76%   |
| HP Pavilion                  | 4         | 0.76%   |
| Toshiba Satellite            | 3         | 0.57%   |
| HP ProLiant                  | 3         | 0.57%   |
| HP 250                       | 3         | 0.57%   |
| Gigabyte Z77-D3H             | 3         | 0.57%   |
| Gigabyte B550I               | 3         | 0.57%   |
| Fujitsu LIFEBOOK             | 3         | 0.57%   |
| ASRock Z97                   | 3         | 0.57%   |
| ASRock B450M                 | 3         | 0.57%   |
| Semp Toshiba STI             | 2         | 0.38%   |
| RPi Raspberry                | 2         | 0.38%   |
| MSI MS-7A70                  | 2         | 0.38%   |
| Lenovo ThinkBook             | 2         | 0.38%   |
| Lenovo G50-80                | 2         | 0.38%   |
| HUAWEI NBLK-WAX9X            | 2         | 0.38%   |
| HP ZBook                     | 2         | 0.38%   |
| HP Z620                      | 2         | 0.38%   |
| HP OMEN                      | 2         | 0.38%   |
| HP ENVY                      | 2         | 0.38%   |
| Gigabyte Z370                | 2         | 0.38%   |
| Gigabyte AERO                | 2         | 0.38%   |
| Gigabyte 970A-DS3P           | 2         | 0.38%   |
| Dell Vostro                  | 2         | 0.38%   |
| Dell PowerEdge               | 2         | 0.38%   |
| ASUS TUF                     | 2         | 0.38%   |
| Apple MacBook5               | 2         | 0.38%   |
| Acer Swift                   | 2         | 0.38%   |
| Acer Nitro                   | 2         | 0.38%   |
| ZOTAC ZBOX-EN1070            | 1         | 0.19%   |
| UNOWHY Y13G002S4EI           | 1         | 0.19%   |
| TUXEDO Pulse                 | 1         | 0.19%   |
| Supermicro SYS-6019P-WT      | 1         | 0.19%   |
| Supermicro SYS-5038MA-H24TRF | 1         | 0.19%   |
| Supermicro SYS-5019S-MR      | 1         | 0.19%   |
| sunxi Banana                 | 1         | 0.19%   |
| Sony VPCF21AFX               | 1         | 0.19%   |
| SLIMBOOK PROX14-AMD          | 1         | 0.19%   |
| SimpliVity OmniCube          | 1         | 0.19%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 111       | 21.02%  |
| 2021    | 103       | 19.51%  |
| 2019    | 68        | 12.88%  |
| 2018    | 47        | 8.9%    |
| 2016    | 25        | 4.73%   |
| 2012    | 24        | 4.55%   |
| 2013    | 20        | 3.79%   |
| 2015    | 19        | 3.6%    |
| 2014    | 19        | 3.6%    |
| 2011    | 17        | 3.22%   |
| 2009    | 15        | 2.84%   |
| 2017    | 14        | 2.65%   |
| 2008    | 12        | 2.27%   |
| 2010    | 11        | 2.08%   |
| Unknown | 8         | 1.52%   |
| 2007    | 6         | 1.14%   |
| 2006    | 4         | 0.76%   |
| 2005    | 2         | 0.38%   |
| 2004    | 2         | 0.38%   |
| 2001    | 1         | 0.19%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 312       | 59.09%  |
| Desktop        | 179       | 33.9%   |
| Convertible    | 10        | 1.89%   |
| System on chip | 7         | 1.33%   |
| Mini pc        | 7         | 1.33%   |
| Server         | 7         | 1.33%   |
| All in one     | 3         | 0.57%   |
| Tablet         | 2         | 0.38%   |
| Phone          | 1         | 0.19%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 483       | 91.13%  |
| Enabled  | 47        | 8.87%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 501       | 94.89%  |
| Yes  | 27        | 5.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 134       | 25.38%  |
| 4.01-8.0        | 110       | 20.83%  |
| 8.01-16.0       | 85        | 16.1%   |
| 3.01-4.0        | 75        | 14.2%   |
| 32.01-64.0      | 51        | 9.66%   |
| 64.01-256.0     | 27        | 5.11%   |
| 1.01-2.0        | 21        | 3.98%   |
| 2.01-3.0        | 9         | 1.7%    |
| 0.51-1.0        | 6         | 1.14%   |
| 24.01-32.0      | 4         | 0.76%   |
| 0.01-0.5        | 4         | 0.76%   |
| More than 256.0 | 2         | 0.38%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 147       | 27.53%  |
| 2.01-3.0    | 115       | 21.54%  |
| 4.01-8.0    | 82        | 15.36%  |
| 3.01-4.0    | 63        | 11.8%   |
| 0.51-1.0    | 49        | 9.18%   |
| 8.01-16.0   | 37        | 6.93%   |
| 0.01-0.5    | 27        | 5.06%   |
| 16.01-24.0  | 5         | 0.94%   |
| 24.01-32.0  | 4         | 0.75%   |
| 32.01-64.0  | 3         | 0.56%   |
| 64.01-256.0 | 2         | 0.37%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 294       | 55.68%  |
| 2      | 145       | 27.46%  |
| 3      | 37        | 7.01%   |
| 4      | 22        | 4.17%   |
| 5      | 12        | 2.27%   |
| 8      | 6         | 1.14%   |
| 6      | 4         | 0.76%   |
| 9      | 3         | 0.57%   |
| 10     | 2         | 0.38%   |
| 0      | 2         | 0.38%   |
| 28     | 1         | 0.19%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 366       | 69.32%  |
| Yes       | 162       | 30.68%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 434       | 82.2%   |
| No        | 94        | 17.8%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 379       | 71.78%  |
| No        | 149       | 28.22%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 311       | 58.9%   |
| No        | 217       | 41.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country                | Computers | Percent |
|------------------------|-----------|---------|
| USA                    | 140       | 26.52%  |
| Russia                 | 39        | 7.39%   |
| Germany                | 39        | 7.39%   |
| France                 | 38        | 7.2%    |
| UK                     | 23        | 4.36%   |
| Spain                  | 22        | 4.17%   |
| Ukraine                | 19        | 3.6%    |
| Poland                 | 17        | 3.22%   |
| Brazil                 | 15        | 2.84%   |
| Netherlands            | 11        | 2.08%   |
| Switzerland            | 10        | 1.89%   |
| Canada                 | 10        | 1.89%   |
| Sweden                 | 8         | 1.52%   |
| Italy                  | 8         | 1.52%   |
| India                  | 8         | 1.52%   |
| Norway                 | 7         | 1.33%   |
| Czechia                | 7         | 1.33%   |
| Australia              | 7         | 1.33%   |
| Turkey                 | 6         | 1.14%   |
| Mexico                 | 6         | 1.14%   |
| Greece                 | 6         | 1.14%   |
| Portugal               | 5         | 0.95%   |
| Hungary                | 5         | 0.95%   |
| Belgium                | 5         | 0.95%   |
| Thailand               | 4         | 0.76%   |
| Kazakhstan             | 4         | 0.76%   |
| Finland                | 4         | 0.76%   |
| Bulgaria               | 4         | 0.76%   |
| Belarus                | 4         | 0.76%   |
| Austria                | 4         | 0.76%   |
| Japan                  | 3         | 0.57%   |
| Ecuador                | 3         | 0.57%   |
| Croatia                | 3         | 0.57%   |
| Argentina              | 3         | 0.57%   |
| Venezuela              | 2         | 0.38%   |
| Slovenia               | 2         | 0.38%   |
| Romania                | 2         | 0.38%   |
| New Zealand            | 2         | 0.38%   |
| Indonesia              | 2         | 0.38%   |
| Colombia               | 2         | 0.38%   |
| China                  | 2         | 0.38%   |
| Vietnam                | 1         | 0.19%   |
| Uruguay                | 1         | 0.19%   |
| Syria                  | 1         | 0.19%   |
| South Sudan            | 1         | 0.19%   |
| Singapore              | 1         | 0.19%   |
| Serbia                 | 1         | 0.19%   |
| Philippines            | 1         | 0.19%   |
| New Caledonia          | 1         | 0.19%   |
| Morocco                | 1         | 0.19%   |
| Mongolia               | 1         | 0.19%   |
| Malaysia               | 1         | 0.19%   |
| Madagascar             | 1         | 0.19%   |
| Ireland                | 1         | 0.19%   |
| Hong Kong              | 1         | 0.19%   |
| Denmark                | 1         | 0.19%   |
| Bosnia and Herzegovina | 1         | 0.19%   |
| Bangladesh             | 1         | 0.19%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City           | Computers | Percent |
|----------------|-----------|---------|
| Portland       | 63        | 11.82%  |
| St Petersburg  | 11        | 2.06%   |
| Paris          | 9         | 1.69%   |
| Lyon           | 8         | 1.5%    |
| London         | 7         | 1.31%   |
| Ocala          | 5         | 0.94%   |
| Kalamazoo      | 5         | 0.94%   |
| Athens         | 5         | 0.94%   |
| Warsaw         | 4         | 0.75%   |
| Vienna         | 4         | 0.75%   |
| Sofia          | 4         | 0.75%   |
| Sevastopol     | 4         | 0.75%   |
| Moscow         | 4         | 0.75%   |
| Kyiv           | 4         | 0.75%   |
| Ensenada       | 4         | 0.75%   |
| Berlin         | 4         | 0.75%   |
| Bengaluru      | 4         | 0.75%   |
| Bangkok        | 4         | 0.75%   |
| Amsterdam      | 4         | 0.75%   |
| Zurich         | 3         | 0.56%   |
| Sunnyvale      | 3         | 0.56%   |
| Stockholm      | 3         | 0.56%   |
| S??o Paulo     | 3         | 0.56%   |
| Perm           | 3         | 0.56%   |
| Mesa           | 3         | 0.56%   |
| Madrid         | 3         | 0.56%   |
| Istanbul       | 3         | 0.56%   |
| Gloucester     | 3         | 0.56%   |
| Clitheroe      | 3         | 0.56%   |
| Zagreb         | 2         | 0.38%   |
| Yevpatoriya    | 2         | 0.38%   |
| Waregem        | 2         | 0.38%   |
| Toronto        | 2         | 0.38%   |
| Sydney         | 2         | 0.38%   |
| Springfield    | 2         | 0.38%   |
| Shizuoka       | 2         | 0.38%   |
| Saratov        | 2         | 0.38%   |
| Saint-Denis    | 2         | 0.38%   |
| Rio de Janeiro | 2         | 0.38%   |
| Riegelwood     | 2         | 0.38%   |
| Prague         | 2         | 0.38%   |
| Oleksandrivka  | 2         | 0.38%   |
| Offenburg      | 2         | 0.38%   |
| Noblesville    | 2         | 0.38%   |
| New York       | 2         | 0.38%   |
| Munich         | 2         | 0.38%   |
| Molde          | 2         | 0.38%   |
| Mainz          | 2         | 0.38%   |
| Madison        | 2         | 0.38%   |
| Lublin         | 2         | 0.38%   |
| Las Vegas      | 2         | 0.38%   |
| Kreuzlingen    | 2         | 0.38%   |
| Kharkiv        | 2         | 0.38%   |
| Hanover        | 2         | 0.38%   |
| Hamilton       | 2         | 0.38%   |
| Halifax        | 2         | 0.38%   |
| Hakadal        | 2         | 0.38%   |
| Gorinchem      | 2         | 0.38%   |
| Fryazino       | 2         | 0.38%   |
| Donetsk        | 2         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 142       | 188    | 18.37%  |
| WDC                       | 111       | 187    | 14.36%  |
| Seagate                   | 105       | 153    | 13.58%  |
| Unknown                   | 54        | 65     | 6.99%   |
| Kingston                  | 48        | 55     | 6.21%   |
| Toshiba                   | 46        | 64     | 5.95%   |
| Crucial                   | 37        | 41     | 4.79%   |
| Intel                     | 25        | 32     | 3.23%   |
| SanDisk                   | 22        | 27     | 2.85%   |
| Hitachi                   | 20        | 21     | 2.59%   |
| SABRENT                   | 17        | 17     | 2.2%    |
| SK Hynix                  | 16        | 18     | 2.07%   |
| Apple                     | 12        | 12     | 1.55%   |
| A-DATA Technology         | 12        | 16     | 1.55%   |
| HGST                      | 9         | 12     | 1.16%   |
| Micron Technology         | 8         | 8      | 1.03%   |
| China                     | 7         | 7      | 0.91%   |
| SPCC                      | 6         | 6      | 0.78%   |
| Transcend                 | 5         | 6      | 0.65%   |
| PNY                       | 5         | 5      | 0.65%   |
| KIOXIA                    | 5         | 5      | 0.65%   |
| Fujitsu                   | 5         | 5      | 0.65%   |
| Union Memory              | 4         | 4      | 0.52%   |
| Phison                    | 3         | 6      | 0.39%   |
| Patriot                   | 3         | 3      | 0.39%   |
| LITEONIT                  | 3         | 3      | 0.39%   |
| LITEON                    | 3         | 3      | 0.39%   |
| JMicron                   | 3         | 3      | 0.39%   |
| Intenso                   | 3         | 4      | 0.39%   |
| Gigabyte Technology       | 3         | 3      | 0.39%   |
| ZTC                       | 2         | 2      | 0.26%   |
| Phison Electronics        | 2         | 2      | 0.26%   |
| Lenovo                    | 2         | 2      | 0.26%   |
| Corsair                   | 2         | 2      | 0.26%   |
| XPG                       | 1         | 1      | 0.13%   |
| TrueNAS                   | 1         | 1      | 0.13%   |
| Team                      | 1         | 1      | 0.13%   |
| T-FORCE                   | 1         | 1      | 0.13%   |
| SILICONMOTION             | 1         | 1      | 0.13%   |
| Silicon Motion            | 1         | 2      | 0.13%   |
| OCZ                       | 1         | 1      | 0.13%   |
| NAS                       | 1         | 5      | 0.13%   |
| MyDigitalSSD              | 1         | 1      | 0.13%   |
| Micron/Crucial Technology | 1         | 1      | 0.13%   |
| Maxtor                    | 1         | 2      | 0.13%   |
| Maximus                   | 1         | 1      | 0.13%   |
| MaxDigital                | 1         | 2      | 0.13%   |
| Lexar                     | 1         | 1      | 0.13%   |
| LDLC                      | 1         | 1      | 0.13%   |
| KingDian                  | 1         | 1      | 0.13%   |
| IBM-ESXS                  | 1         | 2      | 0.13%   |
| Hewlett-Packard           | 1         | 1      | 0.13%   |
| GOODRAM                   | 1         | 1      | 0.13%   |
| DOGFISH                   | 1         | 1      | 0.13%   |
| ASUS-PHISON               | 1         | 1      | 0.13%   |
| Apacer                    | 1         | 1      | 0.13%   |
| AMD                       | 1         | 2      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| SABRENT Disk 160GB                 | 17        | 1.94%   |
| Unknown AGND3R  16GB               | 14        | 1.6%    |
| Samsung SSD 860 EVO 1TB            | 12        | 1.37%   |
| Samsung SSD 970 EVO Plus 500GB     | 10        | 1.14%   |
| Samsung SSD 970 EVO Plus 1TB       | 10        | 1.14%   |
| Kingston SA400S37120G 120GB SSD    | 10        | 1.14%   |
| Samsung SSD 850 EVO 500GB          | 9         | 1.03%   |
| Unknown HAG2e  16GB                | 8         | 0.91%   |
| Samsung SSD 850 EVO 250GB          | 8         | 0.91%   |
| Samsung SSD 860 EVO 500GB          | 7         | 0.8%    |
| Kingston SA400S37240G 240GB SSD    | 7         | 0.8%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 6         | 0.69%   |
| Seagate ST1000DM010-2EP102 1TB     | 6         | 0.69%   |
| Crucial CT1000MX500SSD1 1TB        | 6         | 0.69%   |
| Toshiba HDWD110 1TB                | 5         | 0.57%   |
| Seagate ST500DM002-1BD142 500GB    | 5         | 0.57%   |
| Seagate ST4000DM004-2CV104 4TB     | 5         | 0.57%   |
| Seagate ST1000LM035-1RK172 1TB     | 5         | 0.57%   |
| Samsung SSD 860 EVO 250GB          | 5         | 0.57%   |
| Kingston SV300S37A120G 120GB SSD   | 5         | 0.57%   |
| Crucial CT500MX500SSD1 500GB       | 5         | 0.57%   |
| Apple SSD SM0128G 121GB            | 5         | 0.57%   |
| WDC WDS500G3X0C-00SJG0 500GB       | 4         | 0.46%   |
| Toshiba DT01ACA300 3TB             | 4         | 0.46%   |
| Toshiba DT01ACA200 2TB             | 4         | 0.46%   |
| Samsung SSD 970 EVO 500GB          | 4         | 0.46%   |
| Kingston SV300S37A240G 240GB SSD   | 4         | 0.46%   |
| Crucial CT500P1SSD8 500GB          | 4         | 0.46%   |
| Crucial CT1000P1SSD8 1TB           | 4         | 0.46%   |
| Apple SSD AP0128H 121GB            | 4         | 0.46%   |
| WDC WDS500G2B0C-00PXH0 500GB       | 3         | 0.34%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 3         | 0.34%   |
| WDC WDS120G2G0A-00JH30 120GB SSD   | 3         | 0.34%   |
| WDC WD40EFRX-68N32N0 4TB           | 3         | 0.34%   |
| WDC WD10SPZX-21Z10T0 1TB           | 3         | 0.34%   |
| WDC WD10JPVX-22JC3T0 1TB           | 3         | 0.34%   |
| WDC WD10EZEX-08WN4A0 1TB           | 3         | 0.34%   |
| WDC WD10EZEX-00BN5A0 1TB           | 3         | 0.34%   |
| Unknown DA4064  64GB               | 3         | 0.34%   |
| Toshiba MQ04ABF100 1TB             | 3         | 0.34%   |
| Seagate ST3000DM001-1CH166 3TB     | 3         | 0.34%   |
| Seagate ST2000LX001-1RG174 2TB     | 3         | 0.34%   |
| Seagate ST2000DM008-2FR102 2TB     | 3         | 0.34%   |
| Seagate ST2000DM001-1ER164 2TB     | 3         | 0.34%   |
| Seagate Backup+ Hub BK 4TB         | 3         | 0.34%   |
| SanDisk SSD PLUS 240GB             | 3         | 0.34%   |
| SanDisk SD8SBAT128G1122 128GB SSD  | 3         | 0.34%   |
| Samsung SSD 860 EVO M.2 1TB        | 3         | 0.34%   |
| Samsung SSD 850 PRO 1TB            | 3         | 0.34%   |
| Samsung SSD 840 PRO Series 256GB   | 3         | 0.34%   |
| Samsung NVMe SSD Drive 1TB         | 3         | 0.34%   |
| Samsung MZALQ256HAJD-000L1 256GB   | 3         | 0.34%   |
| Kingston SUV400S37120G 120GB SSD   | 3         | 0.34%   |
| Hitachi HUS724040ALE641 4TB        | 3         | 0.34%   |
| Hitachi HTS543216L9A300 160GB      | 3         | 0.34%   |
| HGST HTS721010A9E630 1TB           | 3         | 0.34%   |
| Crucial CT240BX500SSD1 240GB       | 3         | 0.34%   |
| ZTC SM201-512G SSD                 | 2         | 0.23%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 2         | 0.23%   |
| WDC WD5000AADS-00S9B0 500GB        | 2         | 0.23%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 98        | 136    | 38.58%  |
| WDC                 | 79        | 142    | 31.1%   |
| Toshiba             | 30        | 45     | 11.81%  |
| Hitachi             | 20        | 21     | 7.87%   |
| Samsung Electronics | 9         | 10     | 3.54%   |
| HGST                | 9         | 12     | 3.54%   |
| Fujitsu             | 5         | 5      | 1.97%   |
| SILICONMOTION       | 1         | 1      | 0.39%   |
| NAS                 | 1         | 5      | 0.39%   |
| MaxDigital          | 1         | 2      | 0.39%   |
| IBM-ESXS            | 1         | 2      | 0.39%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 80        | 104    | 28.27%  |
| Kingston            | 39        | 46     | 13.78%  |
| Crucial             | 27        | 29     | 9.54%   |
| SanDisk             | 17        | 21     | 6.01%   |
| SABRENT             | 17        | 17     | 6.01%   |
| WDC                 | 12        | 15     | 4.24%   |
| A-DATA Technology   | 8         | 9      | 2.83%   |
| Intel               | 7         | 7      | 2.47%   |
| China               | 7         | 7      | 2.47%   |
| Apple               | 7         | 7      | 2.47%   |
| Transcend           | 5         | 6      | 1.77%   |
| Toshiba             | 5         | 7      | 1.77%   |
| SPCC                | 5         | 5      | 1.77%   |
| SK Hynix            | 4         | 4      | 1.41%   |
| PNY                 | 4         | 4      | 1.41%   |
| Micron Technology   | 4         | 4      | 1.41%   |
| Seagate             | 3         | 3      | 1.06%   |
| Patriot             | 3         | 3      | 1.06%   |
| LITEONIT            | 3         | 3      | 1.06%   |
| ZTC                 | 2         | 2      | 0.71%   |
| LITEON              | 2         | 2      | 0.71%   |
| JMicron             | 2         | 2      | 0.71%   |
| Intenso             | 2         | 2      | 0.71%   |
| Unknown             | 1         | 1      | 0.35%   |
| Union Memory        | 1         | 1      | 0.35%   |
| TrueNAS             | 1         | 1      | 0.35%   |
| Team                | 1         | 1      | 0.35%   |
| T-FORCE             | 1         | 1      | 0.35%   |
| OCZ                 | 1         | 1      | 0.35%   |
| MyDigitalSSD        | 1         | 1      | 0.35%   |
| Maxtor              | 1         | 2      | 0.35%   |
| Maximus             | 1         | 1      | 0.35%   |
| Lexar               | 1         | 1      | 0.35%   |
| LDLC                | 1         | 1      | 0.35%   |
| KingDian            | 1         | 1      | 0.35%   |
| GOODRAM             | 1         | 1      | 0.35%   |
| Gigabyte Technology | 1         | 1      | 0.35%   |
| DOGFISH             | 1         | 1      | 0.35%   |
| ASUS-PHISON         | 1         | 1      | 0.35%   |
| Apacer              | 1         | 1      | 0.35%   |
| AMD                 | 1         | 2      | 0.35%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 258       | 329    | 35.64%  |
| HDD     | 218       | 381    | 30.11%  |
| NVMe    | 186       | 227    | 25.69%  |
| MMC     | 51        | 63     | 7.04%   |
| Unknown | 11        | 19     | 1.52%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 365       | 671    | 56.68%  |
| NVMe | 186       | 227    | 28.88%  |
| MMC  | 51        | 63     | 7.92%   |
| SAS  | 42        | 58     | 6.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 271       | 390    | 55.19%  |
| 0.51-1.0   | 131       | 161    | 26.68%  |
| 1.01-2.0   | 48        | 66     | 9.78%   |
| 3.01-4.0   | 18        | 45     | 3.67%   |
| 2.01-3.0   | 12        | 19     | 2.44%   |
| 4.01-10.0  | 8         | 21     | 1.63%   |
| 10.01-20.0 | 3         | 8      | 0.61%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 125       | 23.58%  |
| 251-500        | 98        | 18.49%  |
| 1-20           | 66        | 12.45%  |
| 501-1000       | 66        | 12.45%  |
| 1001-2000      | 46        | 8.68%   |
| More than 3000 | 41        | 7.74%   |
| 51-100         | 30        | 5.66%   |
| Unknown        | 25        | 4.72%   |
| 21-50          | 18        | 3.4%    |
| 2001-3000      | 15        | 2.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 186       | 34.83%  |
| 101-250        | 69        | 12.92%  |
| 21-50          | 60        | 11.24%  |
| 51-100         | 52        | 9.74%   |
| 251-500        | 49        | 9.18%   |
| 501-1000       | 39        | 7.3%    |
| 1001-2000      | 26        | 4.87%   |
| Unknown        | 25        | 4.68%   |
| More than 3000 | 16        | 3%      |
| 2001-3000      | 8         | 1.5%    |
| 0              | 4         | 0.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB                       | 2         | 2      | 2.44%   |
| WDC WD10JPVX-22JC3T0 1TB                       | 2         | 2      | 2.44%   |
| Seagate ST500DM002-1BD142 500GB                | 2         | 2      | 2.44%   |
| Kingston SV300S37A120G 120GB SSD               | 2         | 2      | 2.44%   |
| WDC WD5003ABYX-18WERA0 500GB                   | 1         | 2      | 1.22%   |
| WDC WD5000AAKX-00U6AA0 500GB                   | 1         | 1      | 1.22%   |
| WDC WD5000AAKX-00ERMA0 500GB                   | 1         | 1      | 1.22%   |
| WDC WD5000AAKS-22V1A0 500GB                    | 1         | 1      | 1.22%   |
| WDC WD5000AAJS-22A8B0 500GB                    | 1         | 1      | 1.22%   |
| WDC WD40EFZX-68AWUN0 4TB                       | 1         | 6      | 1.22%   |
| WDC WD400BB-00DEA0 40GB                        | 1         | 1      | 1.22%   |
| WDC WD30EZRX-00AZ6B0 3TB                       | 1         | 1      | 1.22%   |
| WDC WD20EFRX-68EUZN0 2TB                       | 1         | 2      | 1.22%   |
| WDC WD20EARX-00PASB0 2TB                       | 1         | 1      | 1.22%   |
| WDC WD1600AAJS-00L7A0 160GB                    | 1         | 1      | 1.22%   |
| WDC WD10JPVX-60JC3T0 1TB                       | 1         | 1      | 1.22%   |
| WDC WD10JPVT-75A1YT0 1TB                       | 1         | 1      | 1.22%   |
| WDC WD10EZEX-08WN4A0 1TB                       | 1         | 1      | 1.22%   |
| WDC WD10EZEX-00BN5A0 1TB                       | 1         | 1      | 1.22%   |
| WDC WD1001FALS-75J7B0 1TB                      | 1         | 1      | 1.22%   |
| Toshiba MQ04ABF100 1TB                         | 1         | 1      | 1.22%   |
| Toshiba MQ01ABF050 500GB                       | 1         | 1      | 1.22%   |
| Toshiba MQ01ABD100 1TB                         | 1         | 1      | 1.22%   |
| Toshiba MK2565GSX 250GB                        | 1         | 1      | 1.22%   |
| Toshiba DT01ACA050 500GB                       | 1         | 1      | 1.22%   |
| SK Hynix PC401 NVMe 512GB                      | 1         | 2      | 1.22%   |
| Seagate ST960822A 64GB                         | 1         | 1      | 1.22%   |
| Seagate ST9320325AS 320GB                      | 1         | 1      | 1.22%   |
| Seagate ST9160310AS 160GB                      | 1         | 1      | 1.22%   |
| Seagate ST500LT012-9WS142 500GB                | 1         | 1      | 1.22%   |
| Seagate ST500LM021-1KJ152 500GB                | 1         | 1      | 1.22%   |
| Seagate ST3320620A 320GB                       | 1         | 1      | 1.22%   |
| Seagate ST3200827AS 200GB                      | 1         | 1      | 1.22%   |
| Seagate ST32000542AS 2TB                       | 1         | 1      | 1.22%   |
| Seagate ST3160813AS 160GB                      | 1         | 1      | 1.22%   |
| Seagate ST31500341AS 1TB                       | 1         | 1      | 1.22%   |
| Seagate ST3120827AS 120GB                      | 1         | 1      | 1.22%   |
| Seagate ST31000333AS 1TB                       | 1         | 1      | 1.22%   |
| Seagate ST3000DM001-9YN166 320GB               | 1         | 1      | 1.22%   |
| Seagate ST250DM000-1BD141 250GB                | 1         | 1      | 1.22%   |
| Seagate ST2000LX001-1RG174 2TB                 | 1         | 1      | 1.22%   |
| Seagate ST2000DM001-1ER164 2TB                 | 1         | 1      | 1.22%   |
| Seagate ST1000LX015-1U7172 1TB                 | 1         | 1      | 1.22%   |
| Seagate ST1000LM035-1RK172 1TB                 | 1         | 1      | 1.22%   |
| Seagate ST1000LM024 HN-M101MBB 1TB             | 1         | 1      | 1.22%   |
| Seagate ST1000DM003-9YN162 1TB                 | 1         | 1      | 1.22%   |
| Seagate ST1000DM003-1CH162 1TB                 | 1         | 1      | 1.22%   |
| SanDisk SSD PLUS 120 GB                        | 1         | 1      | 1.22%   |
| SanDisk SD7SB2Q512G1001 512GB SSD              | 1         | 1      | 1.22%   |
| Samsung Electronics SSD 970 EVO 250GB          | 1         | 1      | 1.22%   |
| Samsung Electronics SSD 870 EVO 500GB          | 1         | 1      | 1.22%   |
| Samsung Electronics SSD 850 EVO 1TB            | 1         | 1      | 1.22%   |
| Samsung Electronics SSD 840 PRO Series 256GB   | 1         | 2      | 1.22%   |
| Samsung Electronics SP0842N 80GB               | 1         | 1      | 1.22%   |
| Samsung Electronics HM321HI 320GB              | 1         | 1      | 1.22%   |
| Samsung Electronics HD161GJ 160GB              | 1         | 1      | 1.22%   |
| PNY SSD2SC240G3LC709B121-460P 240GB            | 1         | 1      | 1.22%   |
| Micron Technology 1100_MTFDDAV256TBN 256GB SSD | 1         | 1      | 1.22%   |
| LITEONIT LMT-64M6M-HP 64GB SSD                 | 1         | 1      | 1.22%   |
| Kingston SE100S3100G 100GB SSD                 | 1         | 1      | 1.22%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 23     | 26.25%  |
| WDC                 | 20        | 27     | 25%     |
| Samsung Electronics | 7         | 8      | 8.75%   |
| Hitachi             | 7         | 7      | 8.75%   |
| Toshiba             | 5         | 5      | 6.25%   |
| Intel               | 5         | 6      | 6.25%   |
| Kingston            | 4         | 4      | 5%      |
| A-DATA Technology   | 3         | 4      | 3.75%   |
| SanDisk             | 2         | 2      | 2.5%    |
| SK Hynix            | 1         | 2      | 1.25%   |
| PNY                 | 1         | 1      | 1.25%   |
| Micron Technology   | 1         | 1      | 1.25%   |
| LITEONIT            | 1         | 1      | 1.25%   |
| KingDian            | 1         | 1      | 1.25%   |
| HGST                | 1         | 1      | 1.25%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 23     | 36.84%  |
| WDC                 | 20        | 27     | 35.09%  |
| Hitachi             | 7         | 7      | 12.28%  |
| Toshiba             | 5         | 5      | 8.77%   |
| Samsung Electronics | 3         | 3      | 5.26%   |
| HGST                | 1         | 1      | 1.75%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 56        | 66     | 70.89%  |
| SSD  | 19        | 21     | 24.05%  |
| NVMe | 4         | 6      | 5.06%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                            | Computers | Drives | Percent |
|----------------------------------|-----------|--------|---------|
| Seagate ST500DM005 HD502HJ 500GB | 1         | 1      | 50%     |
| Seagate ST3500830AS 500GB        | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 2      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 416       | 736    | 67.97%  |
| Detected | 118       | 188    | 19.28%  |
| Malfunc  | 76        | 93     | 12.42%  |
| Failed   | 2         | 2      | 0.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 311       | 49.37%  |
| AMD                          | 101       | 16.03%  |
| Samsung Electronics          | 75        | 11.9%   |
| Sandisk                      | 29        | 4.6%    |
| SK Hynix                     | 12        | 1.9%    |
| Micron/Crucial Technology    | 12        | 1.9%    |
| Phison Electronics           | 10        | 1.59%   |
| Kingston Technology Company  | 9         | 1.43%   |
| Toshiba America Info Systems | 8         | 1.27%   |
| ASMedia Technology           | 8         | 1.27%   |
| KIOXIA                       | 7         | 1.11%   |
| Marvell Technology Group     | 6         | 0.95%   |
| Nvidia                       | 5         | 0.79%   |
| ADATA Technology             | 5         | 0.79%   |
| Micron Technology            | 4         | 0.63%   |
| JMicron Technology           | 4         | 0.63%   |
| Broadcom / LSI               | 4         | 0.63%   |
| Apple                        | 4         | 0.63%   |
| Union Memory (Shenzhen)      | 3         | 0.48%   |
| VIA Technologies             | 2         | 0.32%   |
| Silicon Motion               | 2         | 0.32%   |
| Lenovo                       | 2         | 0.32%   |
| Silicon Image                | 1         | 0.16%   |
| Seagate Technology           | 1         | 0.16%   |
| OCZ Technology Group         | 1         | 0.16%   |
| LSI Logic / Symbios Logic    | 1         | 0.16%   |
| Lite-On Technology           | 1         | 0.16%   |
| Hewlett-Packard              | 1         | 0.16%   |
| Adaptec                      | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 70        | 9.56%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 45        | 6.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 29        | 3.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 27        | 3.69%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 19        | 2.6%    |
| AMD 400 Series Chipset SATA Controller                                         | 19        | 2.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 18        | 2.46%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 17        | 2.32%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 16        | 2.19%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 14        | 1.91%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 13        | 1.78%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 12        | 1.64%   |
| Intel Comet Lake SATA AHCI Controller                                          | 12        | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 12        | 1.64%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 11        | 1.5%    |
| Intel Volume Management Device NVMe RAID Controller                            | 10        | 1.37%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD                                     | 9         | 1.23%   |
| Micron/Crucial P1 NVMe PCIe SSD                                                | 9         | 1.23%   |
| AMD Starship/Matisse Chipset SATA Controller [AHCI mode]                       | 9         | 1.23%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 9         | 1.23%   |
| Samsung NVMe Controller                                                        | 8         | 1.09%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 8         | 1.09%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 8         | 1.09%   |
| Sandisk WD Blue SN550 NVMe SSD                                                 | 7         | 0.96%   |
| Phison E12 NVMe Controller                                                     | 7         | 0.96%   |
| KIOXIA Non-Volatile memory controller                                          | 7         | 0.96%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 7         | 0.96%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 7         | 0.96%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 6         | 0.82%   |
| Samsung Electronics SATA controller                                            | 6         | 0.82%   |
| Intel SSD 660P Series                                                          | 6         | 0.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 6         | 0.82%   |
| AMD 300 Series Chipset SATA Controller                                         | 6         | 0.82%   |
| Intel SSD 600P Series                                                          | 5         | 0.68%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 5         | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 5         | 0.68%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 0.68%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                      | 5         | 0.68%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 5         | 0.68%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 5         | 0.68%   |
| SK Hynix NVMe SSD Controller                                                   | 4         | 0.55%   |
| Sandisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 4         | 0.55%   |
| Micron Non-Volatile memory controller                                          | 4         | 0.55%   |
| Intel SATA Controller [RAID mode]                                              | 4         | 0.55%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 4         | 0.55%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 4         | 0.55%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) IDE Controller                       | 4         | 0.55%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 4         | 0.55%   |
| Apple S1X NVMe Controller                                                      | 4         | 0.55%   |
| AMD X399 Series Chipset SATA Controller                                        | 4         | 0.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 4         | 0.55%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 3         | 0.41%   |
| SK Hynix BC511                                                                 | 3         | 0.41%   |
| SK Hynix BC501 NVMe Solid State Drive                                          | 3         | 0.41%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 3         | 0.41%   |
| Sandisk Non-Volatile memory controller                                         | 3         | 0.41%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 3         | 0.41%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 3         | 0.41%   |
| Kingston Company Company Non-Volatile memory controller                        | 3         | 0.41%   |
| Kingston Company A2000 NVMe SSD                                                | 3         | 0.41%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 359       | 55.06%  |
| NVMe | 186       | 28.53%  |
| IDE  | 59        | 9.05%   |
| RAID | 42        | 6.44%   |
| SAS  | 6         | 0.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 401       | 75.95%  |
| AMD    | 119       | 22.54%  |
| ARM    | 8         | 1.52%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Celeron CPU N2840 @ 2.16GHz             | 24        | 4.55%   |
| AMD Ryzen 5 3600 6-Core Processor             | 10        | 1.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 9         | 1.7%    |
| Intel Core i5-5250U CPU @ 1.60GHz             | 9         | 1.7%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 1.7%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 8         | 1.52%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 7         | 1.33%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 7         | 1.33%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 6         | 1.14%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 6         | 1.14%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 6         | 1.14%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 6         | 1.14%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 6         | 1.14%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 5         | 0.95%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 5         | 0.95%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 5         | 0.95%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.95%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 5         | 0.95%   |
| ARM Processor                                 | 5         | 0.95%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 5         | 0.95%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 4         | 0.76%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 4         | 0.76%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 4         | 0.76%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 4         | 0.76%   |
| Intel Core i5-4300U CPU @ 1.90GHz             | 4         | 0.76%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.76%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 4         | 0.76%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 0.76%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 4         | 0.76%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.57%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 3         | 0.57%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 3         | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 0.57%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 3         | 0.57%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 0.57%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 3         | 0.57%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 3         | 0.57%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 3         | 0.57%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 3         | 0.57%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 3         | 0.57%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 3         | 0.57%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 3         | 0.57%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 3         | 0.57%   |
| Intel Xeon CPU E5-2640 v3 @ 2.60GHz           | 2         | 0.38%   |
| Intel Pentium M processor 1.73GHz             | 2         | 0.38%   |
| Intel Pentium Gold G5420 CPU @ 3.80GHz        | 2         | 0.38%   |
| Intel Genuine CPU T1400 @ 1.73GHz             | 2         | 0.38%   |
| Intel Core i7-8700K CPU @ 3.70GHz             | 2         | 0.38%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 2         | 0.38%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 2         | 0.38%   |
| Intel Core i7-8086K CPU @ 4.00GHz             | 2         | 0.38%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 0.38%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 2         | 0.38%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 2         | 0.38%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 2         | 0.38%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 2         | 0.38%   |
| Intel Core i7-4600U CPU @ 2.10GHz             | 2         | 0.38%   |
| Intel Core i7-3630QM CPU @ 2.40GHz            | 2         | 0.38%   |
| Intel Core i7-3612QM CPU @ 2.10GHz            | 2         | 0.38%   |
| Intel Core i7-3537U CPU @ 2.00GHz             | 2         | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 134       | 25.38%  |
| Intel Core i7           | 105       | 19.89%  |
| Intel Celeron           | 45        | 8.52%   |
| AMD Ryzen 5             | 35        | 6.63%   |
| Other                   | 26        | 4.92%   |
| AMD Ryzen 7             | 23        | 4.36%   |
| Intel Core i3           | 21        | 3.98%   |
| Intel Core 2 Duo        | 19        | 3.6%    |
| Intel Xeon              | 17        | 3.22%   |
| Intel Pentium           | 11        | 2.08%   |
| AMD FX                  | 8         | 1.52%   |
| AMD Ryzen 7 PRO         | 7         | 1.33%   |
| AMD Ryzen 9             | 6         | 1.14%   |
| AMD Ryzen 3             | 6         | 1.14%   |
| AMD Ryzen Threadripper  | 5         | 0.95%   |
| Intel Pentium M         | 4         | 0.76%   |
| Intel Core 2            | 4         | 0.76%   |
| Intel Atom              | 4         | 0.76%   |
| AMD Phenom II X4        | 4         | 0.76%   |
| Intel Pentium Gold      | 3         | 0.57%   |
| Intel Core 2 Quad       | 3         | 0.57%   |
| Intel Celeron M         | 3         | 0.57%   |
| AMD A8                  | 3         | 0.57%   |
| Intel Pentium Dual-Core | 2         | 0.38%   |
| Intel Pentium 4         | 2         | 0.38%   |
| Intel Genuine           | 2         | 0.38%   |
| AMD Turion 64 Mobile    | 2         | 0.38%   |
| AMD Athlon X4           | 2         | 0.38%   |
| AMD A10                 | 2         | 0.38%   |
| Intel Xeon Silver       | 1         | 0.19%   |
| Intel Pentium Dual      | 1         | 0.19%   |
| Intel Core m7           | 1         | 0.19%   |
| Intel Core i9           | 1         | 0.19%   |
| ARM BCM                 | 1         | 0.19%   |
| ARM Allwinner           | 1         | 0.19%   |
| ARM AArch64             | 1         | 0.19%   |
| AMD Sempron             | 1         | 0.19%   |
| AMD PRO A8              | 1         | 0.19%   |
| AMD Phenom II X3        | 1         | 0.19%   |
| AMD GX                  | 1         | 0.19%   |
| AMD C-30                | 1         | 0.19%   |
| AMD Athlon XP           | 1         | 0.19%   |
| AMD Athlon II X2        | 1         | 0.19%   |
| AMD Athlon II Neo       | 1         | 0.19%   |
| AMD Athlon Dual Core    | 1         | 0.19%   |
| AMD Athlon 64           | 1         | 0.19%   |
| AMD Athlon              | 1         | 0.19%   |
| AMD A6                  | 1         | 0.19%   |
| AMD A12                 | 1         | 0.19%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 215       | 40.72%  |
| 4      | 178       | 33.71%  |
| 6      | 55        | 10.42%  |
| 8      | 41        | 7.77%   |
| 1      | 22        | 4.17%   |
| 16     | 7         | 1.33%   |
| 12     | 6         | 1.14%   |
| 44     | 1         | 0.19%   |
| 32     | 1         | 0.19%   |
| 28     | 1         | 0.19%   |
| 3      | 1         | 0.19%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 519       | 98.3%   |
| 2      | 9         | 1.7%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 355       | 67.23%  |
| 1      | 173       | 32.77%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 513       | 97.16%  |
| 32-bit         | 11        | 2.08%   |
| 64-bit         | 2         | 0.38%   |
| Unknown        | 2         | 0.38%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 89        | 16.76%  |
| 0x306a9    | 34        | 6.4%    |
| 0x206a7    | 26        | 4.9%    |
| 0x30678    | 25        | 4.71%   |
| 0x306d4    | 23        | 4.33%   |
| 0x306c3    | 18        | 3.39%   |
| 0x806e9    | 16        | 3.01%   |
| 0x806c1    | 16        | 3.01%   |
| 0x08701021 | 15        | 2.82%   |
| 0x906ea    | 14        | 2.64%   |
| 0x806ec    | 14        | 2.64%   |
| 0x806ea    | 14        | 2.64%   |
| 0x1067a    | 13        | 2.45%   |
| 0x906e9    | 11        | 2.07%   |
| 0x406e3    | 10        | 1.88%   |
| 0x706e5    | 9         | 1.69%   |
| 0x40651    | 9         | 1.69%   |
| 0xa0652    | 8         | 1.51%   |
| 0x08600106 | 8         | 1.51%   |
| 0x506e3    | 7         | 1.32%   |
| 0x206d7    | 7         | 1.32%   |
| 0x08108109 | 7         | 1.32%   |
| 0x806eb    | 6         | 1.13%   |
| 0x0800820d | 6         | 1.13%   |
| 0x06003106 | 6         | 1.13%   |
| 0x6fd      | 5         | 0.94%   |
| 0x6d8      | 5         | 0.94%   |
| 0x506c9    | 5         | 0.94%   |
| 0x20655    | 5         | 0.94%   |
| 0x306f2    | 4         | 0.75%   |
| 0x0a201009 | 4         | 0.75%   |
| 0x06000852 | 4         | 0.75%   |
| 0xa0655    | 3         | 0.56%   |
| 0x6f6      | 3         | 0.56%   |
| 0x08600104 | 3         | 0.56%   |
| 0x08001138 | 3         | 0.56%   |
| 0x0600611a | 3         | 0.56%   |
| 0x010000c8 | 3         | 0.56%   |
| 0x010000b6 | 3         | 0.56%   |
| 0xa0660    | 2         | 0.38%   |
| 0xa0653    | 2         | 0.38%   |
| 0x706a8    | 2         | 0.38%   |
| 0x6fb      | 2         | 0.38%   |
| 0x6fa      | 2         | 0.38%   |
| 0x695      | 2         | 0.38%   |
| 0x406c4    | 2         | 0.38%   |
| 0x406c3    | 2         | 0.38%   |
| 0x106e5    | 2         | 0.38%   |
| 0x106c2    | 2         | 0.38%   |
| 0x0a50000b | 2         | 0.38%   |
| 0x0a201016 | 2         | 0.38%   |
| 0x08701013 | 2         | 0.38%   |
| 0x08600103 | 2         | 0.38%   |
| 0x08108102 | 2         | 0.38%   |
| 0x08001137 | 2         | 0.38%   |
| 0xf49      | 1         | 0.19%   |
| 0xf41      | 1         | 0.19%   |
| 0xf29      | 1         | 0.19%   |
| 0xa0671    | 1         | 0.19%   |
| 0x906ed    | 1         | 0.19%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 95        | 17.99%  |
| Haswell       | 42        | 7.95%   |
| IvyBridge     | 41        | 7.77%   |
| Zen 2         | 39        | 7.39%   |
| SandyBridge   | 33        | 6.25%   |
| Silvermont    | 31        | 5.87%   |
| Skylake       | 25        | 4.73%   |
| Broadwell     | 24        | 4.55%   |
| Zen+          | 23        | 4.36%   |
| TigerLake     | 18        | 3.41%   |
| Penryn        | 16        | 3.03%   |
| Core          | 16        | 3.03%   |
| CometLake     | 16        | 3.03%   |
| Westmere      | 11        | 2.08%   |
| Zen 3         | 10        | 1.89%   |
| Zen           | 10        | 1.89%   |
| Unknown       | 10        | 1.89%   |
| IceLake       | 9         | 1.7%    |
| K10           | 8         | 1.52%   |
| Steamroller   | 7         | 1.33%   |
| P6            | 7         | 1.33%   |
| Piledriver    | 6         | 1.14%   |
| Goldmont      | 5         | 0.95%   |
| K8 Hammer     | 4         | 0.76%   |
| Excavator     | 4         | 0.76%   |
| NetBurst      | 3         | 0.57%   |
| Nehalem       | 3         | 0.57%   |
| Goldmont plus | 3         | 0.57%   |
| Bulldozer     | 2         | 0.38%   |
| Bonnell       | 2         | 0.38%   |
| Puma          | 1         | 0.19%   |
| K6            | 1         | 0.19%   |
| K10 Llano     | 1         | 0.19%   |
| Jaguar        | 1         | 0.19%   |
| Bobcat        | 1         | 0.19%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 324       | 54.64%  |
| Nvidia                     | 135       | 22.77%  |
| AMD                        | 122       | 20.57%  |
| ASPEED Technology          | 7         | 1.18%   |
| Matrox Electronics Systems | 4         | 0.67%   |
| VIA Technologies           | 1         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 28        | 4.6%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 26        | 4.27%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 22        | 3.61%   |
| Intel UHD Graphics 620                                                                   | 19        | 3.12%   |
| AMD Renoir                                                                               | 16        | 2.63%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 16        | 2.63%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 15        | 2.46%   |
| Intel HD Graphics 620                                                                    | 15        | 2.46%   |
| Intel HD Graphics 5500                                                                   | 14        | 2.3%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 13        | 2.13%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 13        | 2.13%   |
| AMD Picasso                                                                              | 12        | 1.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 1.81%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 11        | 1.81%   |
| Intel HD Graphics 6000                                                                   | 9         | 1.48%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 8         | 1.31%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 8         | 1.31%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 8         | 1.31%   |
| Intel Core Processor Integrated Graphics Controller                                      | 8         | 1.31%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 8         | 1.31%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 7         | 1.15%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 7         | 1.15%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 7         | 1.15%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 1.15%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 7         | 1.15%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 7         | 1.15%   |
| Intel HD Graphics 630                                                                    | 6         | 0.99%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 6         | 0.99%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 6         | 0.99%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.82%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 5         | 0.82%   |
| Intel Mobile 915GM/GMS/910GML Express Graphics Controller                                | 5         | 0.82%   |
| Intel Iris Plus Graphics G7                                                              | 5         | 0.82%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 5         | 0.82%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 4         | 0.66%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 4         | 0.66%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 4         | 0.66%   |
| Nvidia GK107M [GeForce GT 640M]                                                          | 4         | 0.66%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 4         | 0.66%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 4         | 0.66%   |
| Intel HD Graphics 530                                                                    | 4         | 0.66%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 0.66%   |
| AMD Kaveri [Radeon R7 Graphics]                                                          | 4         | 0.66%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 0.49%   |
| Nvidia GM108M [GeForce 840M]                                                             | 3         | 0.49%   |
| Matrox Electronics Systems G200eR2                                                       | 3         | 0.49%   |
| Intel Tiger Lake UHD Graphics                                                            | 3         | 0.49%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 3         | 0.49%   |
| Intel Kaby Lake-U GT1 Integrated Graphics Controller                                     | 3         | 0.49%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 3         | 0.49%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 3         | 0.49%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 3         | 0.49%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 3         | 0.49%   |
| AMD RS480M [Mobility Radeon Xpress 200]                                                  | 3         | 0.49%   |
| AMD Cezanne                                                                              | 3         | 0.49%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 3         | 0.49%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 2         | 0.33%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 2         | 0.33%   |
| Nvidia GT218 [GeForce 210]                                                               | 2         | 0.33%   |
| Nvidia GP108M [GeForce MX250]                                                            | 2         | 0.33%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 258       | 48.68%  |
| 1 x AMD         | 100       | 18.87%  |
| 1 x Nvidia      | 79        | 14.91%  |
| Intel + Nvidia  | 51        | 9.62%   |
| Intel + AMD     | 12        | 2.26%   |
| Other           | 9         | 1.7%    |
| 1 x ASPEED      | 6         | 1.13%   |
| AMD + Nvidia    | 5         | 0.94%   |
| 2 x AMD         | 4         | 0.75%   |
| 1 x Matrox      | 3         | 0.57%   |
| 1 x VIA         | 1         | 0.19%   |
| Nvidia + Matrox | 1         | 0.19%   |
| AMD + ASPEED    | 1         | 0.19%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 440       | 83.18%  |
| Proprietary | 71        | 13.42%  |
| Unknown     | 18        | 3.4%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 353       | 66.35%  |
| 0.01-0.5   | 44        | 8.27%   |
| 1.01-2.0   | 37        | 6.95%   |
| 0.51-1.0   | 30        | 5.64%   |
| 3.01-4.0   | 28        | 5.26%   |
| 7.01-8.0   | 26        | 4.89%   |
| 5.01-6.0   | 7         | 1.32%   |
| 8.01-16.0  | 3         | 0.56%   |
| 2.01-3.0   | 2         | 0.38%   |
| 24.01-32.0 | 1         | 0.19%   |
| 16.01-24.0 | 1         | 0.19%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 70        | 12.09%  |
| BOE                     | 62        | 10.71%  |
| Samsung Electronics     | 55        | 9.5%    |
| Chimei Innolux          | 52        | 8.98%   |
| LG Display              | 45        | 7.77%   |
| Dell                    | 34        | 5.87%   |
| Goldstar                | 28        | 4.84%   |
| Ancor Communications    | 22        | 3.8%    |
| Apple                   | 20        | 3.45%   |
| Acer                    | 20        | 3.45%   |
| Lenovo                  | 17        | 2.94%   |
| Hewlett-Packard         | 17        | 2.94%   |
| BenQ                    | 15        | 2.59%   |
| Sharp                   | 14        | 2.42%   |
| Philips                 | 12        | 2.07%   |
| AOC                     | 11        | 1.9%    |
| ViewSonic               | 9         | 1.55%   |
| NEC Computers           | 7         | 1.21%   |
| InfoVision              | 6         | 1.04%   |
| Eizo                    | 5         | 0.86%   |
| ASUSTek Computer        | 5         | 0.86%   |
| Unknown                 | 4         | 0.69%   |
| Chi Mei Optoelectronics | 4         | 0.69%   |
| PANDA                   | 3         | 0.52%   |
| LG Philips              | 3         | 0.52%   |
| Iiyama                  | 3         | 0.52%   |
| Vestel Elektronik       | 2         | 0.35%   |
| Sony                    | 2         | 0.35%   |
| MSI                     | 2         | 0.35%   |
| LG Electronics          | 2         | 0.35%   |
| HannStar                | 2         | 0.35%   |
| CPT                     | 2         | 0.35%   |
| ___                     | 1         | 0.17%   |
| VMO                     | 1         | 0.17%   |
| Vizio                   | 1         | 0.17%   |
| TEO                     | 1         | 0.17%   |
| Prestigio               | 1         | 0.17%   |
| ODH                     | 1         | 0.17%   |
| NCS                     | 1         | 0.17%   |
| MIT                     | 1         | 0.17%   |
| Mi                      | 1         | 0.17%   |
| Medion                  | 1         | 0.17%   |
| LPL                     | 1         | 0.17%   |
| JXG                     | 1         | 0.17%   |
| JVC                     | 1         | 0.17%   |
| JRY                     | 1         | 0.17%   |
| IOD                     | 1         | 0.17%   |
| INFOTRONIC              | 1         | 0.17%   |
| Idek Iiyama             | 1         | 0.17%   |
| HKC                     | 1         | 0.17%   |
| Hitachi                 | 1         | 0.17%   |
| HannStar Display        | 1         | 0.17%   |
| CSO                     | 1         | 0.17%   |
| COBY                    | 1         | 0.17%   |
| CMN                     | 1         | 0.17%   |
| Belinea                 | 1         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                      | 16        | 2.68%   |
| AU Optronics LCD Monitor AUO235C 1366x768 260x140mm 11.6-inch             | 7         | 1.17%   |
| Chimei Innolux LCD Monitor CMN1132 1366x768 260x140mm 11.6-inch           | 5         | 0.84%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch            | 5         | 0.84%   |
| Dell E176FP DELA014 1280x1024 340x270mm 17.1-inch                         | 4         | 0.67%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch          | 4         | 0.67%   |
| AU Optronics LCD Monitor AUO213E 1600x900 309x174mm 14.0-inch             | 4         | 0.67%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                    | 3         | 0.5%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch                 | 3         | 0.5%    |
| Samsung Electronics LCD Monitor SEC4351 1366x768 344x194mm 15.5-inch      | 3         | 0.5%    |
| NEC Computers LCD1550V NEC65C6 1024x768 304x228mm 15.0-inch               | 3         | 0.5%    |
| LG Display LCD Monitor LGD0362 1600x900 309x174mm 14.0-inch               | 3         | 0.5%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                         | 3         | 0.5%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch          | 3         | 0.5%    |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                      | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 340x190mm 15.3-inch            | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch            | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch            | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch            | 3         | 0.5%    |
| ASUSTek Computer MZ279 AUS27CA 1920x1080 598x336mm 27.0-inch              | 3         | 0.5%    |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                      | 3         | 0.5%    |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                      | 3         | 0.5%    |
| Ancor Communications ASUS VH236H ACI23F2 1920x1080 520x290mm 23.4-inch    | 3         | 0.5%    |
| ViewSonic VX3211-2K VSCF634 2560x1440 698x392mm 31.5-inch                 | 2         | 0.34%   |
| Vestel Elektronik 50UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch    | 2         | 0.34%   |
| Sharp LCD Monitor SHP14F9 1920x1200 288x180mm 13.4-inch                   | 2         | 0.34%   |
| Sharp LCD Monitor SHP14AD 3840x2160 294x165mm 13.3-inch                   | 2         | 0.34%   |
| Sharp LCD Monitor SHP1484 1920x1080 294x165mm 13.3-inch                   | 2         | 0.34%   |
| Samsung Electronics SyncMaster SAM0656 1920x1080 510x287mm 23.0-inch      | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch      | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 1050x590mm 47.4-inch    | 2         | 0.34%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                   | 2         | 0.34%   |
| LG Philips LCD Monitor LPL1151 1024x768 304x228mm 15.0-inch               | 2         | 0.34%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch              | 2         | 0.34%   |
| LG Display LCD Monitor LGD05FA 1920x1080 309x174mm 14.0-inch              | 2         | 0.34%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch              | 2         | 0.34%   |
| LG Display LCD Monitor LGD03A3 1366x768 277x156mm 12.5-inch               | 2         | 0.34%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch                  | 2         | 0.34%   |
| Lenovo LCD Monitor LEN4036 1440x900 304x190mm 14.1-inch                   | 2         | 0.34%   |
| Lenovo L2251x Wide LEN0A12 1680x1050 474x296mm 22.0-inch                  | 2         | 0.34%   |
| Hewlett-Packard ZR30w HWP286C 2560x1600 641x400mm 29.7-inch               | 2         | 0.34%   |
| Hewlett-Packard Z23i HWP308F 1920x1080 509x286mm 23.0-inch                | 2         | 0.34%   |
| Hewlett-Packard LA2405 HWP284C 1920x1200 518x324mm 24.1-inch              | 2         | 0.34%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                   | 2         | 0.34%   |
| Goldstar LG ULTRAWIDE GSM59F1 1920x1080 580x240mm 24.7-inch               | 2         | 0.34%   |
| Goldstar HDR 4K GSM7706 3840x2160 600x340mm 27.2-inch                     | 2         | 0.34%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                    | 2         | 0.34%   |
| Goldstar 27GL850 GSM5B7F 2560x1440 597x336mm 27.0-inch                    | 2         | 0.34%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                         | 2         | 0.34%   |
| Dell LCD Monitor U2312HM 1920x1080                                        | 2         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch          | 2         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch          | 2         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch           | 2         | 0.34%   |
| Chimei Innolux LCD Monitor CMN1515 1920x1080 344x193mm 15.5-inch          | 2         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14F2 1920x1080 309x173mm 13.9-inch          | 2         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14E5 1920x1080 309x173mm 13.9-inch          | 2         | 0.34%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch          | 2         | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO1720 1920x1080 382x215mm 17.3-inch | 2         | 0.34%   |
| BOE LCD Monitor BOE097D 1920x1080 344x194mm 15.5-inch                     | 2         | 0.34%   |
| BOE LCD Monitor BOE0903 1920x1080 344x194mm 15.5-inch                     | 2         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 236       | 41.92%  |
| 1366x768 (WXGA)    | 106       | 18.83%  |
| 3840x2160 (4K)     | 33        | 5.86%   |
| 2560x1440 (QHD)    | 32        | 5.68%   |
| 1920x1200 (WUXGA)  | 22        | 3.91%   |
| 1600x900 (HD+)     | 22        | 3.91%   |
| 1280x1024 (SXGA)   | 20        | 3.55%   |
| 1280x800 (WXGA)    | 18        | 3.2%    |
| 1680x1050 (WSXGA+) | 13        | 2.31%   |
| 1440x900 (WXGA+)   | 13        | 2.31%   |
| 1024x768 (XGA)     | 10        | 1.78%   |
| Unknown            | 6         | 1.07%   |
| 2560x1600          | 4         | 0.71%   |
| 2560x1080          | 4         | 0.71%   |
| 3440x1440          | 3         | 0.53%   |
| 2288x1287          | 3         | 0.53%   |
| 1600x1200          | 3         | 0.53%   |
| 3840x1080          | 2         | 0.36%   |
| 1024x600           | 2         | 0.36%   |
| 7680x4320          | 1         | 0.18%   |
| 5760x1080          | 1         | 0.18%   |
| 4480x1440          | 1         | 0.18%   |
| 3840x2400          | 1         | 0.18%   |
| 3360x1080          | 1         | 0.18%   |
| 3200x1800 (QHD+)   | 1         | 0.18%   |
| 2880x1800          | 1         | 0.18%   |
| 2256x1504          | 1         | 0.18%   |
| 2160x1440          | 1         | 0.18%   |
| 1920x540           | 1         | 0.18%   |
| 1792x768           | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 111       | 19.3%   |
| 13      | 75        | 13.04%  |
| 14      | 51        | 8.87%   |
| 24      | 49        | 8.52%   |
| 27      | 38        | 6.61%   |
| 23      | 37        | 6.43%   |
| 11      | 37        | 6.43%   |
| 17      | 31        | 5.39%   |
| 21      | 25        | 4.35%   |
| 12      | 21        | 3.65%   |
| Unknown | 16        | 2.78%   |
| 31      | 12        | 2.09%   |
| 19      | 9         | 1.57%   |
| 18      | 8         | 1.39%   |
| 22      | 7         | 1.22%   |
| 34      | 6         | 1.04%   |
| 20      | 6         | 1.04%   |
| 25      | 5         | 0.87%   |
| 84      | 4         | 0.7%    |
| 142     | 3         | 0.52%   |
| 28      | 3         | 0.52%   |
| 72      | 2         | 0.35%   |
| 47      | 2         | 0.35%   |
| 40      | 2         | 0.35%   |
| 32      | 2         | 0.35%   |
| 29      | 2         | 0.35%   |
| 16      | 2         | 0.35%   |
| 10      | 2         | 0.35%   |
| 74      | 1         | 0.17%   |
| 55      | 1         | 0.17%   |
| 48      | 1         | 0.17%   |
| 46      | 1         | 0.17%   |
| 38      | 1         | 0.17%   |
| 33      | 1         | 0.17%   |
| 26      | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 210       | 36.91%  |
| 501-600        | 115       | 20.21%  |
| 201-300        | 98        | 17.22%  |
| 401-500        | 53        | 9.31%   |
| 351-400        | 27        | 4.75%   |
| 601-700        | 23        | 4.04%   |
| Unknown        | 16        | 2.81%   |
| 701-800        | 9         | 1.58%   |
| 1501-2000      | 7         | 1.23%   |
| 1001-1500      | 5         | 0.88%   |
| More than 2000 | 3         | 0.53%   |
| 801-900        | 3         | 0.53%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 396       | 74.16%  |
| 16/10   | 68        | 12.73%  |
| 5/4     | 18        | 3.37%   |
| 4/3     | 16        | 3%      |
| Unknown | 15        | 2.81%   |
| 21/9    | 8         | 1.5%    |
| 3/2     | 7         | 1.31%   |
| 1.00    | 4         | 0.75%   |
| 6/5     | 1         | 0.19%   |
| 1.96    | 1         | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 112       | 19.58%  |
| 81-90          | 97        | 16.96%  |
| 201-250        | 87        | 15.21%  |
| 301-350        | 38        | 6.64%   |
| 51-60          | 37        | 6.47%   |
| 71-80          | 30        | 5.24%   |
| 351-500        | 26        | 4.55%   |
| 251-300        | 26        | 4.55%   |
| 151-200        | 24        | 4.2%    |
| 61-70          | 20        | 3.5%    |
| 141-150        | 19        | 3.32%   |
| 121-130        | 17        | 2.97%   |
| Unknown        | 16        | 2.8%    |
| More than 1000 | 11        | 1.92%   |
| 501-1000       | 7         | 1.22%   |
| 131-140        | 3         | 0.52%   |
| 41-50          | 2         | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 211       | 37.95%  |
| 51-100        | 173       | 31.12%  |
| 101-120       | 101       | 18.17%  |
| 161-240       | 34        | 6.12%   |
| Unknown       | 16        | 2.88%   |
| 1-50          | 12        | 2.16%   |
| More than 240 | 9         | 1.62%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 408       | 76.98%  |
| 2     | 84        | 15.85%  |
| 0     | 27        | 5.09%   |
| 3     | 10        | 1.89%   |
| 4     | 1         | 0.19%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 306       | 41.98%  |
| Realtek Semiconductor             | 227       | 31.14%  |
| Qualcomm Atheros                  | 71        | 9.74%   |
| Broadcom                          | 43        | 5.9%    |
| Broadcom Limited                  | 17        | 2.33%   |
| Marvell Technology Group          | 6         | 0.82%   |
| Sierra Wireless                   | 5         | 0.69%   |
| Nvidia                            | 5         | 0.69%   |
| Ericsson Business Mobile Networks | 4         | 0.55%   |
| Ralink Technology                 | 3         | 0.41%   |
| Ralink                            | 3         | 0.41%   |
| Dell                              | 3         | 0.41%   |
| AMD                               | 3         | 0.41%   |
| Xiaomi                            | 2         | 0.27%   |
| TP-Link                           | 2         | 0.27%   |
| Qualcomm Atheros Communications   | 2         | 0.27%   |
| Microsoft                         | 2         | 0.27%   |
| Microchip Technology              | 2         | 0.27%   |
| Mellanox Technologies             | 2         | 0.27%   |
| Edimax Technology                 | 2         | 0.27%   |
| DisplayLink                       | 2         | 0.27%   |
| D-Link                            | 2         | 0.27%   |
| Cypress Semiconductor             | 2         | 0.27%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.14%   |
| VIA Technologies                  | 1         | 0.14%   |
| Qualcomm                          | 1         | 0.14%   |
| MEDIATEK                          | 1         | 0.14%   |
| Lenovo                            | 1         | 0.14%   |
| JMicron Technology                | 1         | 0.14%   |
| IBM                               | 1         | 0.14%   |
| Huawei Technologies               | 1         | 0.14%   |
| Hewlett-Packard                   | 1         | 0.14%   |
| Fibocom                           | 1         | 0.14%   |
| Attansic Technology               | 1         | 0.14%   |
| Aquantia                          | 1         | 0.14%   |
| American Megatrends               | 1         | 0.14%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 164       | 18.68%  |
| Intel Wireless 7260                                               | 35        | 3.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 30        | 3.42%   |
| Intel Wi-Fi 6 AX200                                               | 28        | 3.19%   |
| Intel Wireless 8265 / 8275                                        | 19        | 2.16%   |
| Intel I211 Gigabit Network Connection                             | 17        | 1.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 16        | 1.82%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 1.71%   |
| Intel Wireless 8260                                               | 14        | 1.59%   |
| Intel Ethernet Connection (2) I219-V                              | 13        | 1.48%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 13        | 1.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 12        | 1.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 11        | 1.25%   |
| Intel Wireless 7265                                               | 11        | 1.25%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 1.14%   |
| Intel Wi-Fi 6 AX201                                               | 10        | 1.14%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 1.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 9         | 1.03%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 9         | 1.03%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 8         | 0.91%   |
| Intel Ethernet Connection (4) I219-V                              | 8         | 0.91%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 0.91%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 8         | 0.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 8         | 0.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 7         | 0.8%    |
| Intel Wireless 3165                                               | 7         | 0.8%    |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7         | 0.8%    |
| Intel Cannon Lake PCH CNVi WiFi                                   | 7         | 0.8%    |
| Intel I210 Gigabit Network Connection                             | 6         | 0.68%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.68%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 0.68%   |
| Intel Centrino Ultimate-N 6300                                    | 6         | 0.68%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 0.57%   |
| Intel Wireless 3160                                               | 5         | 0.57%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 5         | 0.57%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 0.57%   |
| Intel Ethernet Connection (2) I218-V                              | 5         | 0.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 0.57%   |
| Intel Centrino Wireless-N 2230                                    | 5         | 0.57%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 4         | 0.46%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.46%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.46%   |
| Intel Wireless-AC 9260                                            | 4         | 0.46%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 4         | 0.46%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 0.46%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4         | 0.46%   |
| Sierra Wireless EM7345 4G LTE                                     | 3         | 0.34%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 3         | 0.34%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 3         | 0.34%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.34%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 3         | 0.34%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 3         | 0.34%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection     | 3         | 0.34%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.34%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.34%   |
| Intel Centrino Advanced-N 6200                                    | 3         | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 235       | 60.41%  |
| Qualcomm Atheros                  | 55        | 14.14%  |
| Realtek Semiconductor             | 43        | 11.05%  |
| Broadcom                          | 20        | 5.14%   |
| Broadcom Limited                  | 14        | 3.6%    |
| Ralink Technology                 | 3         | 0.77%   |
| Ralink                            | 3         | 0.77%   |
| TP-Link                           | 2         | 0.51%   |
| Sierra Wireless                   | 2         | 0.51%   |
| Qualcomm Atheros Communications   | 2         | 0.51%   |
| Microsoft                         | 2         | 0.51%   |
| Edimax Technology                 | 2         | 0.51%   |
| Qualcomm                          | 1         | 0.26%   |
| MEDIATEK                          | 1         | 0.26%   |
| Fibocom                           | 1         | 0.26%   |
| Ericsson Business Mobile Networks | 1         | 0.26%   |
| Dell                              | 1         | 0.26%   |
| D-Link                            | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 7260                                                         | 35        | 8.97%   |
| Intel Wi-Fi 6 AX200                                                         | 28        | 7.18%   |
| Intel Wireless 8265 / 8275                                                  | 19        | 4.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                  | 16        | 4.1%    |
| Intel Wireless 8260                                                         | 14        | 3.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                | 13        | 3.33%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                           | 12        | 3.08%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                    | 11        | 2.82%   |
| Intel Wireless 7265                                                         | 11        | 2.82%   |
| Intel Wi-Fi 6 AX201                                                         | 10        | 2.56%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                    | 9         | 2.31%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                  | 9         | 2.31%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                  | 9         | 2.31%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)              | 8         | 2.05%   |
| Intel Comet Lake PCH CNVi WiFi                                              | 8         | 2.05%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                    | 8         | 2.05%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                  | 7         | 1.79%   |
| Intel Wireless 3165                                                         | 7         | 1.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                            | 7         | 1.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                             | 7         | 1.79%   |
| Intel Centrino Ultimate-N 6300                                              | 6         | 1.54%   |
| Intel Wireless 3160                                                         | 5         | 1.28%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                             | 5         | 1.28%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                             | 5         | 1.28%   |
| Intel Centrino Wireless-N 2230                                              | 5         | 1.28%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                             | 4         | 1.03%   |
| Intel Wireless-AC 9260                                                      | 4         | 1.03%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                       | 4         | 1.03%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                             | 3         | 0.77%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                     | 3         | 0.77%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                            | 3         | 0.77%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                            | 3         | 0.77%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection               | 3         | 0.77%   |
| Intel Centrino Advanced-N 6200                                              | 3         | 0.77%   |
| Broadcom BCM4331 802.11a/b/g/n                                              | 3         | 0.77%   |
| Broadcom BCM43142 802.11b/g/n                                               | 3         | 0.77%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                         | 2         | 0.51%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                             | 2         | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                         | 2         | 0.51%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                  | 2         | 0.51%   |
| Qualcomm Atheros AR9271 802.11n                                             | 2         | 0.51%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)              | 2         | 0.51%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)              | 2         | 0.51%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)     | 2         | 0.51%   |
| Microsoft Xbox 360 Wireless Adapter                                         | 2         | 0.51%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                      | 2         | 0.51%   |
| Intel Ultimate N WiFi Link 5300                                             | 2         | 0.51%   |
| Intel PRO/Wireless 2915ABG [Calexico2] Network Connection                   | 2         | 0.51%   |
| Intel Centrino Advanced-N 6235                                              | 2         | 0.51%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]              | 2         | 0.51%   |
| Broadcom Limited BCM4318 [AirForce 54g] 802.11a/b/g PCI Express Transceiver | 2         | 0.51%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                          | 2         | 0.51%   |
| Broadcom BCM43224 802.11a/b/g/n                                             | 2         | 0.51%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                      | 2         | 0.51%   |
| Broadcom BCM4318 [AirForce One 54g] 802.11g Wireless LAN Controller         | 2         | 0.51%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                         | 1         | 0.26%   |
| TP-Link Archer T4U ver.3                                                    | 1         | 0.26%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                          | 1         | 0.26%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                    | 1         | 0.26%   |
| Realtek RTL8723DE Wireless Network Adapter                                  | 1         | 0.26%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 206       | 44.78%  |
| Intel                    | 166       | 36.09%  |
| Broadcom                 | 28        | 6.09%   |
| Qualcomm Atheros         | 23        | 5%      |
| Marvell Technology Group | 6         | 1.3%    |
| Nvidia                   | 5         | 1.09%   |
| Broadcom Limited         | 4         | 0.87%   |
| Sierra Wireless          | 3         | 0.65%   |
| Xiaomi                   | 2         | 0.43%   |
| Microchip Technology     | 2         | 0.43%   |
| Mellanox Technologies    | 2         | 0.43%   |
| DisplayLink              | 2         | 0.43%   |
| Cypress Semiconductor    | 2         | 0.43%   |
| VIA Technologies         | 1         | 0.22%   |
| Lenovo                   | 1         | 0.22%   |
| JMicron Technology       | 1         | 0.22%   |
| IBM                      | 1         | 0.22%   |
| Huawei Technologies      | 1         | 0.22%   |
| D-Link                   | 1         | 0.22%   |
| Attansic Technology      | 1         | 0.22%   |
| Aquantia                 | 1         | 0.22%   |
| American Megatrends      | 1         | 0.22%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 164       | 34.6%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 30        | 6.33%   |
| Intel I211 Gigabit Network Connection                             | 17        | 3.59%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 15        | 3.16%   |
| Intel Ethernet Connection (2) I219-V                              | 13        | 2.74%   |
| Realtek RTL8125 2.5GbE Controller                                 | 10        | 2.11%   |
| Intel Ethernet Connection (4) I219-V                              | 8         | 1.69%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 1.69%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 1.48%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 1.48%   |
| Intel I210 Gigabit Network Connection                             | 6         | 1.27%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 1.27%   |
| Intel Ethernet Connection (3) I218-LM                             | 6         | 1.27%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 1.05%   |
| Intel Ethernet Connection I219-LM                                 | 5         | 1.05%   |
| Intel Ethernet Connection (2) I218-V                              | 5         | 1.05%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 1.05%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 4         | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 4         | 0.84%   |
| Intel 82574L Gigabit Network Connection                           | 4         | 0.84%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4         | 0.84%   |
| Sierra Wireless EM7345 4G LTE                                     | 3         | 0.63%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.63%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.63%   |
| Intel Ethernet Connection I219-V                                  | 3         | 0.63%   |
| Intel Ethernet Connection I217-V                                  | 3         | 0.63%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 3         | 0.63%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 3         | 0.63%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.42%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 2         | 0.42%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                        | 2         | 0.42%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.42%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.42%   |
| Nvidia MCP79 Ethernet                                             | 2         | 0.42%   |
| Nvidia MCP61 Ethernet                                             | 2         | 0.42%   |
| Mellanox MT27500 Family [ConnectX-3]                              | 2         | 0.42%   |
| Intel I350 Gigabit Network Connection                             | 2         | 0.42%   |
| Intel Ethernet Controller 10G X550T                               | 2         | 0.42%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.42%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.42%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.42%   |
| Intel Ethernet Connection (5) I219-LM                             | 2         | 0.42%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.42%   |
| Intel Ethernet Connection (13) I219-V                             | 2         | 0.42%   |
| Intel Ethernet Connection (11) I219-V                             | 2         | 0.42%   |
| Intel Ethernet Connection (11) I219-LM                            | 2         | 0.42%   |
| Intel Ethernet Connection (10) I219-V                             | 2         | 0.42%   |
| Intel 82567LM Gigabit Network Connection                          | 2         | 0.42%   |
| Cypress K38231_03                                                 | 2         | 0.42%   |
| Broadcom NetXtreme BCM5788 Gigabit Ethernet                       | 2         | 0.42%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 2         | 0.42%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 2         | 0.42%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2         | 0.42%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express               | 2         | 0.42%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 2         | 0.42%   |
| Broadcom BCM4401-B0 100Base-TX                                    | 2         | 0.42%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 1         | 0.21%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.21%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.21%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.21%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 434       | 52.54%  |
| WiFi     | 378       | 45.76%  |
| Modem    | 14        | 1.69%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 342       | 49.93%  |
| Ethernet | 341       | 49.78%  |
| Modem    | 2         | 0.29%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 277       | 52.46%  |
| 1     | 218       | 41.29%  |
| 3     | 15        | 2.84%   |
| 0     | 10        | 1.89%   |
| 4     | 5         | 0.95%   |
| 13    | 1         | 0.19%   |
| 6     | 1         | 0.19%   |
| 5     | 1         | 0.19%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 427       | 80.72%  |
| Yes  | 102       | 19.28%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 177       | 56.55%  |
| Qualcomm Atheros Communications | 23        | 7.35%   |
| Realtek Semiconductor           | 22        | 7.03%   |
| Broadcom                        | 21        | 6.71%   |
| Apple                           | 18        | 5.75%   |
| Cambridge Silicon Radio         | 13        | 4.15%   |
| Lite-On Technology              | 11        | 3.51%   |
| IMC Networks                    | 5         | 1.6%    |
| Foxconn / Hon Hai               | 5         | 1.6%    |
| ASUSTek Computer                | 5         | 1.6%    |
| Hewlett-Packard                 | 4         | 1.28%   |
| Realtek                         | 3         | 0.96%   |
| Toshiba                         | 2         | 0.64%   |
| Dell                            | 2         | 0.64%   |
| Taiyo Yuden                     | 1         | 0.32%   |
| Ralink                          | 1         | 0.32%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                    | 82        | 26.2%   |
| Intel AX200 Bluetooth                                 | 29        | 9.27%   |
| Intel Bluetooth Device                                | 28        | 8.95%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 20        | 6.39%   |
| Realtek Bluetooth Radio                               | 18        | 5.75%   |
| Qualcomm Atheros  Bluetooth Device                    | 14        | 4.47%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 13        | 4.15%   |
| Apple Bluetooth USB Host Controller                   | 10        | 3.19%   |
| Lite-On Bluetooth Device                              | 7         | 2.24%   |
| Intel Wireless-AC 3168 Bluetooth                      | 6         | 1.92%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]            | 6         | 1.92%   |
| Broadcom BCM2045B (BDC-2.1)                           | 6         | 1.92%   |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 5         | 1.6%    |
| Intel Centrino Bluetooth Wireless Transceiver         | 5         | 1.6%    |
| Qualcomm Atheros AR3011 Bluetooth                     | 4         | 1.28%   |
| Foxconn / Hon Hai Bluetooth Device                    | 4         | 1.28%   |
| Realtek Bluetooth Radio                               | 3         | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                 | 3         | 0.96%   |
| IMC Networks Bluetooth Radio                          | 3         | 0.96%   |
| HP Broadcom 2070 Bluetooth Combo                      | 3         | 0.96%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                  | 3         | 0.96%   |
| Apple Bluetooth Host Controller                       | 3         | 0.96%   |
| Toshiba Bluetooth Device                              | 2         | 0.64%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                | 2         | 0.64%   |
| Lite-On Atheros AR3012 Bluetooth                      | 2         | 0.64%   |
| Broadcom BCM43142A0 Bluetooth 4.0                     | 2         | 0.64%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2         | 0.64%   |
| Apple Bluetooth HCI MacBookPro (HID mode)             | 2         | 0.64%   |
| Taiyo Yuden Bluetooth Device                          | 1         | 0.32%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter               | 1         | 0.32%   |
| Realtek RTL8723B Bluetooth                            | 1         | 0.32%   |
| Realtek  Bluetooth 4.2 Adapter                        | 1         | 0.32%   |
| Realtek CSR BS8510                                    | 1         | 0.32%   |
| Ralink RT3290 Bluetooth                               | 1         | 0.32%   |
| Lite-On Wireless_Device                               | 1         | 0.32%   |
| Lite-On BCM43142A0                                    | 1         | 0.32%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter      | 1         | 0.32%   |
| Intel AX210 Bluetooth                                 | 1         | 0.32%   |
| IMC Networks Bluetooth Device                         | 1         | 0.32%   |
| IMC Networks Bluetooth                                | 1         | 0.32%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 1         | 0.32%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth         | 1         | 0.32%   |
| Dell DW375 Bluetooth Module                           | 1         | 0.32%   |
| Dell BCM20702A0 Bluetooth Module                      | 1         | 0.32%   |
| Broadcom HP Portable SoftSailing                      | 1         | 0.32%   |
| Broadcom Bluetooth 3.0 Device                         | 1         | 0.32%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 1         | 0.32%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]    | 1         | 0.32%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]      | 1         | 0.32%   |
| Broadcom BCM2045 Bluetooth                            | 1         | 0.32%   |
| Broadcom BCM2035 Bluetooth dongle                     | 1         | 0.32%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 1         | 0.32%   |
| ASUS Bluetooth Radio                                  | 1         | 0.32%   |
| ASUS Bluetooth Adapter                                | 1         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 381       | 54.74%  |
| AMD                        | 133       | 19.11%  |
| Nvidia                     | 102       | 14.66%  |
| C-Media Electronics        | 15        | 2.16%   |
| Logitech                   | 8         | 1.15%   |
| Generalplus Technology     | 7         | 1.01%   |
| GN Netcom                  | 5         | 0.72%   |
| GYROCOM C&C                | 4         | 0.57%   |
| Creative Labs              | 4         | 0.57%   |
| VIA Technologies           | 3         | 0.43%   |
| Texas Instruments          | 3         | 0.43%   |
| Plantronics                | 3         | 0.43%   |
| XMOS                       | 2         | 0.29%   |
| Samson Technologies        | 2         | 0.29%   |
| Lenovo                     | 2         | 0.29%   |
| BEHRINGER International    | 2         | 0.29%   |
| Unknown                    | 1         | 0.14%   |
| TEAC                       | 1         | 0.14%   |
| SteelSeries ApS            | 1         | 0.14%   |
| RODE Microphones           | 1         | 0.14%   |
| ROCCAT                     | 1         | 0.14%   |
| Razer USA                  | 1         | 0.14%   |
| PreSonus Audio Electronics | 1         | 0.14%   |
| JMTek                      | 1         | 0.14%   |
| Hewlett-Packard            | 1         | 0.14%   |
| Hangzhou Worlde            | 1         | 0.14%   |
| Focusrite-Novation         | 1         | 0.14%   |
| Dell                       | 1         | 0.14%   |
| Creative Technology        | 1         | 0.14%   |
| Blue Microphones           | 1         | 0.14%   |
| AXELVOX                    | 1         | 0.14%   |
| AVID Technology            | 1         | 0.14%   |
| Audioengine                | 1         | 0.14%   |
| ASUSTek Computer           | 1         | 0.14%   |
| Apple                      | 1         | 0.14%   |
| Alesis                     | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 49        | 5.95%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 40        | 4.85%   |
| AMD Family 17h (Models 10h-1fh) HD Audio Controller                                               | 36        | 4.37%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 28        | 3.4%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 26        | 3.16%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 25        | 3.03%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 23        | 2.79%   |
| Intel Broadwell-U Audio Controller                                                                | 23        | 2.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 19        | 2.31%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 18        | 2.18%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 17        | 2.06%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 17        | 2.06%   |
| Intel 200 Series PCH HD Audio                                                                     | 17        | 2.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 16        | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 1.82%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 15        | 1.82%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 15        | 1.82%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 15        | 1.82%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 14        | 1.7%    |
| Intel 8 Series HD Audio Controller                                                                | 14        | 1.7%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 14        | 1.7%    |
| Intel Comet Lake PCH cAVS                                                                         | 13        | 1.58%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 12        | 1.46%   |
| Intel Cannon Lake PCH cAVS                                                                        | 12        | 1.46%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 12        | 1.46%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 1.33%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 11        | 1.33%   |
| AMD FCH Azalia Controller                                                                         | 10        | 1.21%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 9         | 1.09%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 9         | 1.09%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 8         | 0.97%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 8         | 0.97%   |
| AMD Navi 10 HDMI Audio                                                                            | 8         | 0.97%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 7         | 0.85%   |
| Generalplus Technology USB Audio Device                                                           | 7         | 0.85%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 6         | 0.73%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 0.73%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 6         | 0.73%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 5         | 0.61%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 5         | 0.61%   |
| Intel C600/X79 series chipset High Definition Audio Controller                                    | 5         | 0.61%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 5         | 0.61%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 5         | 0.61%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 0.61%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 0.49%   |
| Nvidia GP108 High Definition Audio Controller                                                     | 4         | 0.49%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 4         | 0.49%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 4         | 0.49%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 4         | 0.49%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 3         | 0.36%   |
| Nvidia TU104 HD Audio Controller                                                                  | 3         | 0.36%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 3         | 0.36%   |
| Nvidia GK104 HDMI Audio Controller                                                                | 3         | 0.36%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 3         | 0.36%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 3         | 0.36%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 3         | 0.36%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) High Definition Audio Controller                        | 3         | 0.36%   |
| Intel 82801FB/FBM/FR/FW/FRW (ICH6 Family) AC'97 Audio Controller                                  | 3         | 0.36%   |
| GYROCOM C&C Fiio E10                                                                              | 3         | 0.36%   |
| C-Media Electronics CMI8788 [Oxygen HD Audio]                                                     | 3         | 0.36%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 128       | 22.78%  |
| SK Hynix            | 103       | 18.33%  |
| Kingston            | 73        | 12.99%  |
| Unknown             | 51        | 9.07%   |
| Micron Technology   | 45        | 8.01%   |
| Crucial             | 41        | 7.3%    |
| Corsair             | 40        | 7.12%   |
| G.Skill             | 17        | 3.02%   |
| A-DATA Technology   | 12        | 2.14%   |
| Ramaxel Technology  | 9         | 1.6%    |
| Nanya Technology    | 7         | 1.25%   |
| Elpida              | 7         | 1.25%   |
| Team                | 5         | 0.89%   |
| Patriot             | 4         | 0.71%   |
| Kllisre             | 3         | 0.53%   |
| Unknown (ABCD)      | 2         | 0.36%   |
| Smart               | 2         | 0.36%   |
| GOODRAM             | 2         | 0.36%   |
| V-Color             | 1         | 0.18%   |
| Unifosa             | 1         | 0.18%   |
| SMART Brazil        | 1         | 0.18%   |
| Silicon Power       | 1         | 0.18%   |
| Sesame              | 1         | 0.18%   |
| PNY                 | 1         | 0.18%   |
| Kingmax             | 1         | 0.18%   |
| KETECH              | 1         | 0.18%   |
| Infineon            | 1         | 0.18%   |
| GeIL                | 1         | 0.18%   |
| AMD                 | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 18        | 2.94%   |
| Samsung RAM M471B5273DH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 6         | 0.98%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 5         | 0.82%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 5         | 0.82%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 5         | 0.82%   |
| Micron RAM 4KTF25664HZ-1G6E 2GB SODIMM DDR3 1333MT/s             | 5         | 0.82%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3466MT/s            | 5         | 0.82%   |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 4         | 0.65%   |
| SK Hynix RAM HMT351S6EFR8C-PB 4096MB SODIMM DDR3 1600MT/s        | 4         | 0.65%   |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s         | 4         | 0.65%   |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s         | 4         | 0.65%   |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s         | 4         | 0.65%   |
| Samsung RAM M471B1G73DB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 4         | 0.65%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 2667MT/s            | 4         | 0.65%   |
| Kingston RAM KHX3200C16D4/32GX 32GB DIMM DDR4 3200MT/s           | 4         | 0.65%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.49%   |
| SK Hynix RAM HMA82GS6CJR8N-VK 16384MB SODIMM DDR4 2667MT/s       | 3         | 0.49%   |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.49%   |
| SK Hynix RAM H9CCNNNCLGALAR-NVD 8GB Row Of Chips LPDDR3 2133MT/s | 3         | 0.49%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 3         | 0.49%   |
| Samsung RAM Module 1GB SODIMM DDR2 533MT/s                       | 3         | 0.49%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.49%   |
| Samsung RAM M471A5244CB0-CRC 4096MB SODIMM DDR4 2667MT/s         | 3         | 0.49%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 3         | 0.49%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.49%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.49%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8192MB SODIMM DDR4 3200MT/s          | 3         | 0.49%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 2933MT/s                | 3         | 0.49%   |
| Kingston RAM 99U5469-046.A00LF 4GB SODIMM DDR3 1333MT/s          | 3         | 0.49%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 3         | 0.49%   |
| Crucial RAM CT102464BF160B.M16 8192MB SODIMM DDR3 1600MT/s       | 3         | 0.49%   |
| Corsair RAM CMZ16GX3M2A1600C10 8GB DIMM DDR3 1600MT/s            | 3         | 0.49%   |
| Corsair RAM CMK16GX4M2B3200C16 8192MB DIMM DDR4 3600MT/s         | 3         | 0.49%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 2         | 0.33%   |
| Unknown RAM Module 512MB SODIMM DDR2 400MT/s                     | 2         | 0.33%   |
| Unknown RAM Module 4GB SODIMM DDR4 2400MT/s                      | 2         | 0.33%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 2         | 0.33%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 2         | 0.33%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 2         | 0.33%   |
| Unknown RAM Module 1GB SODIMM SDRAM                              | 2         | 0.33%   |
| Unknown RAM Module 1GB DIMM DDR2 800MT/s                         | 2         | 0.33%   |
| Unknown RAM Module 16GB DIMM DDR4 2667MT/s                       | 2         | 0.33%   |
| Unknown RAM 99[2/7/4]164(F/R) 4GB DIMM DDR3 1600MT/s             | 2         | 0.33%   |
| SK Hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 2         | 0.33%   |
| SK Hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 2         | 0.33%   |
| SK Hynix RAM HMT425S6AFR6A-PB 2GB SODIMM DDR3 1600MT/s           | 2         | 0.33%   |
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 2         | 0.33%   |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 0.33%   |
| SK Hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s        | 2         | 0.33%   |
| SK Hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 0.33%   |
| SK Hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 2         | 0.33%   |
| SK Hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 0.33%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2133MT/s        | 2         | 0.33%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 2         | 0.33%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 0.33%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.33%   |
| Samsung RAM M471A2K43DB1-CWE 16384MB SODIMM DDR4 3200MT/s        | 2         | 0.33%   |
| Samsung RAM M471A2K43CB1-CRC 16384MB SODIMM DDR4 2667MT/s        | 2         | 0.33%   |
| Samsung RAM M471A1K43DB1-CTD 8192MB SODIMM DDR4 2667MT/s         | 2         | 0.33%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 220       | 45.08%  |
| DDR3    | 194       | 39.75%  |
| DDR2    | 24        | 4.92%   |
| LPDDR3  | 15        | 3.07%   |
| SDRAM   | 10        | 2.05%   |
| Unknown | 10        | 2.05%   |
| LPDDR4  | 8         | 1.64%   |
| DDR     | 6         | 1.23%   |
| DRAM    | 1         | 0.2%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 291       | 59.39%  |
| DIMM         | 167       | 34.08%  |
| Row Of Chips | 25        | 5.1%    |
| Chip         | 5         | 1.02%   |
| RIMM         | 1         | 0.2%    |
| Unknown      | 1         | 0.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 186       | 35.16%  |
| 4096  | 142       | 26.84%  |
| 16384 | 73        | 13.8%   |
| 2048  | 67        | 12.67%  |
| 1024  | 27        | 5.1%    |
| 32768 | 20        | 3.78%   |
| 512   | 9         | 1.7%    |
| 256   | 4         | 0.76%   |
| 65536 | 1         | 0.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 137       | 25.66%  |
| 2667    | 79        | 14.79%  |
| 3200    | 67        | 12.55%  |
| 1333    | 45        | 8.43%   |
| 2400    | 38        | 7.12%   |
| 2133    | 26        | 4.87%   |
| 1334    | 19        | 3.56%   |
| 1867    | 13        | 2.43%   |
| 3600    | 12        | 2.25%   |
| 667     | 11        | 2.06%   |
| Unknown | 9         | 1.69%   |
| 800     | 8         | 1.5%    |
| 2933    | 7         | 1.31%   |
| 1866    | 7         | 1.31%   |
| 400     | 6         | 1.12%   |
| 3466    | 5         | 0.94%   |
| 533     | 5         | 0.94%   |
| 3000    | 4         | 0.75%   |
| 2666    | 4         | 0.75%   |
| 1067    | 4         | 0.75%   |
| 333     | 4         | 0.75%   |
| 4267    | 3         | 0.56%   |
| 3500    | 2         | 0.37%   |
| 3400    | 2         | 0.37%   |
| 3100    | 2         | 0.37%   |
| 2000    | 2         | 0.37%   |
| 1066    | 2         | 0.37%   |
| 4266    | 1         | 0.19%   |
| 4199    | 1         | 0.19%   |
| 3533    | 1         | 0.19%   |
| 3066    | 1         | 0.19%   |
| 2866    | 1         | 0.19%   |
| 2465    | 1         | 0.19%   |
| 2267    | 1         | 0.19%   |
| 1800    | 1         | 0.19%   |
| 1400    | 1         | 0.19%   |
| 1367    | 1         | 0.19%   |
| 975     | 1         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 4         | 44.44%  |
| Samsung Electronics | 2         | 22.22%  |
| Canon               | 2         | 22.22%  |
| Konica Minolta      | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Samsung ML-2010P Mono Laser Printer | 1         | 11.11%  |
| Samsung ML-1660 Series              | 1         | 11.11%  |
| Konica Minolta bizhub 4402P         | 1         | 11.11%  |
| HP LaserJet P1006                   | 1         | 11.11%  |
| HP LaserJet M101-M106               | 1         | 11.11%  |
| HP LaserJet 1200                    | 1         | 11.11%  |
| HP ENVY 4520 series                 | 1         | 11.11%  |
| Canon LiDE 400                      | 1         | 11.11%  |
| Canon iP2700 series                 | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Seiko Epson | 2         | 50%     |
| Canon       | 2         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20            | 2         | 50%     |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO] | 1         | 25%     |
| Seiko Epson GT-7700U [Perfection 1240U]       | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 62        | 19.87%  |
| IMC Networks                           | 38        | 12.18%  |
| Acer                                   | 32        | 10.26%  |
| Quanta                                 | 30        | 9.62%   |
| Microdia                               | 26        | 8.33%   |
| Realtek Semiconductor                  | 22        | 7.05%   |
| Logitech                               | 19        | 6.09%   |
| Lite-On Technology                     | 11        | 3.53%   |
| Sunplus Innovation Technology          | 10        | 3.21%   |
| Apple                                  | 8         | 2.56%   |
| Suyin                                  | 7         | 2.24%   |
| Cheng Uei Precision Industry (Foxlink) | 6         | 1.92%   |
| Syntek                                 | 5         | 1.6%    |
| Lenovo                                 | 5         | 1.6%    |
| Luxvisions Innotech Limited            | 4         | 1.28%   |
| Samsung Electronics                    | 3         | 0.96%   |
| Z-Star Microelectronics                | 2         | 0.64%   |
| Silicon Motion                         | 2         | 0.64%   |
| Genesys Logic                          | 2         | 0.64%   |
| Generalplus Technology                 | 2         | 0.64%   |
| eMPIA Technology                       | 2         | 0.64%   |
| Xiongmai                               | 1         | 0.32%   |
| SiGma Micro                            | 1         | 0.32%   |
| Ricoh                                  | 1         | 0.32%   |
| Razer USA                              | 1         | 0.32%   |
| Primax Electronics                     | 1         | 0.32%   |
| Pixart Imaging                         | 1         | 0.32%   |
| Huawei Technologies                    | 1         | 0.32%   |
| Hewlett-Packard                        | 1         | 0.32%   |
| AVerMedia Technologies                 | 1         | 0.32%   |
| ARC International                      | 1         | 0.32%   |
| ALi                                    | 1         | 0.32%   |
| Alcor Micro                            | 1         | 0.32%   |
| A4Tech                                 | 1         | 0.32%   |
| 8SSC20F27114V1SR11K1SE2                | 1         | 0.32%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                                  | 22        | 7.03%   |
| Quanta Chromebook HD Camera                                                | 19        | 6.07%   |
| IMC Networks Integrated Camera                                             | 14        | 4.47%   |
| Acer Integrated Camera                                                     | 13        | 4.15%   |
| Microdia Integrated_Webcam_HD                                              | 11        | 3.51%   |
| Realtek Integrated_Webcam_HD                                               | 10        | 3.19%   |
| Chicony HD WebCam                                                          | 9         | 2.88%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 8         | 2.56%   |
| Logitech Webcam C270                                                       | 5         | 1.6%    |
| Chicony HP HD Camera                                                       | 5         | 1.6%    |
| Chicony Chromebook HD Camera                                               | 5         | 1.6%    |
| Acer SunplusIT Integrated Camera                                           | 5         | 1.6%    |
| Lite-On Integrated Camera                                                  | 4         | 1.28%   |
| Samsung Galaxy A5 (MTP)                                                    | 3         | 0.96%   |
| Realtek Integrated Webcam                                                  | 3         | 0.96%   |
| Quanta HD WebCam                                                           | 3         | 0.96%   |
| Microdia Webcam Vitade AF                                                  | 3         | 0.96%   |
| Microdia Integrated Webcam HD                                              | 3         | 0.96%   |
| Logitech HD Pro Webcam C920                                                | 3         | 0.96%   |
| Lenovo Integrated Webcam                                                   | 3         | 0.96%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 3         | 0.96%   |
| IMC Networks USB2.0 HD IR UVC WebCam                                       | 3         | 0.96%   |
| Chicony USB2.0 Camera                                                      | 3         | 0.96%   |
| Chicony Integrated Camera (1280x720@30)                                    | 3         | 0.96%   |
| Acer ThinkPad Integrated Camera                                            | 3         | 0.96%   |
| Syntek Integrated Camera                                                   | 2         | 0.64%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                   | 2         | 0.64%   |
| Sunplus Integrated_Webcam_HD                                               | 2         | 0.64%   |
| Sunplus HP Universal Camera                                                | 2         | 0.64%   |
| Realtek EasyCamera                                                         | 2         | 0.64%   |
| Quanta HP TrueVision HD Camera                                             | 2         | 0.64%   |
| Microdia USB Live camera                                                   | 2         | 0.64%   |
| Luxvisions Innotech Limited HP HD Camera                                   | 2         | 0.64%   |
| Logitech HD Webcam C910                                                    | 2         | 0.64%   |
| Logitech HD Webcam C615                                                    | 2         | 0.64%   |
| Logitech C505 HD Webcam                                                    | 2         | 0.64%   |
| Lite-On HP Webcam                                                          | 2         | 0.64%   |
| Lite-On HP HD Camera                                                       | 2         | 0.64%   |
| IMC Networks ov9734_azurewave_camera                                       | 2         | 0.64%   |
| IMC Networks Lenovo EasyCamera                                             | 2         | 0.64%   |
| IMC Networks HP TrueVision HD Camera                                       | 2         | 0.64%   |
| Chicony ThinkPad T490 Webcam                                               | 2         | 0.64%   |
| Chicony Lenovo EasyCamera                                                  | 2         | 0.64%   |
| Chicony HP HD Webcam                                                       | 2         | 0.64%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD Integrated Webcam | 2         | 0.64%   |
| Apple FaceTime HD Camera                                                   | 2         | 0.64%   |
| Apple Built-in iSight                                                      | 2         | 0.64%   |
| Acer Lenovo Integrated Webcam                                              | 2         | 0.64%   |
| Acer Lenovo EasyCamera                                                     | 2         | 0.64%   |
| Acer EasyCamera                                                            | 2         | 0.64%   |
| Acer BisonCam, NB Pro                                                      | 2         | 0.64%   |
| Z-Star Venus USB2.0 Camera                                                 | 1         | 0.32%   |
| Z-Star Sirius USB2.0 Camera                                                | 1         | 0.32%   |
| Xiongmai web camera                                                        | 1         | 0.32%   |
| Syntek USB 2.0 UVC PC Camera                                               | 1         | 0.32%   |
| Syntek Lenovo EasyCamera                                                   | 1         | 0.32%   |
| Syntek Integrated RGB Camera                                               | 1         | 0.32%   |
| Suyin Laptop_Integrated_Webcam_HD                                          | 1         | 0.32%   |
| Suyin HP TrueVision HD Integrated Webcam                                   | 1         | 0.32%   |
| Suyin HP TrueVision Full HD                                                | 1         | 0.32%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 21        | 31.82%  |
| Validity Sensors           | 19        | 28.79%  |
| Shenzhen Goodix Technology | 10        | 15.15%  |
| Upek                       | 7         | 10.61%  |
| AuthenTec                  | 4         | 6.06%   |
| Elan Microelectronics      | 3         | 4.55%   |
| LighTuning Technology      | 2         | 3.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 13.64%  |
| Validity Sensors VFS 5011 fingerprint sensor                               | 8         | 12.12%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 7         | 10.61%  |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 9.09%   |
| Shenzhen Goodix  Fingerprint Device                                        | 5         | 7.58%   |
| Shenzhen Goodix FingerPrint                                                | 4         | 6.06%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 4.55%   |
| Validity Sensors Synaptics WBDI                                            | 3         | 4.55%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 3         | 4.55%   |
| Elan ELAN:Fingerprint                                                      | 3         | 4.55%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 4.55%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 3.03%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 3.03%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 1.52%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 1.52%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 1.52%   |
| Synaptics  WBDI                                                            | 1         | 1.52%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 1.52%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 1.52%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 1.52%   |
| Unknown                                                                    | 1         | 1.52%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 13        | 38.24%  |
| Broadcom              | 8         | 23.53%  |
| Lenovo                | 5         | 14.71%  |
| Upek                  | 4         | 11.76%  |
| Yubico.com            | 1         | 2.94%   |
| OmniKey               | 1         | 2.94%   |
| O2 Micro              | 1         | 2.94%   |
| Gemalto (was Gemplus) | 1         | 2.94%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 13        | 38.24%  |
| Lenovo Integrated Smart Card Reader                                          | 5         | 14.71%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 11.76%  |
| Broadcom 58200                                                               | 3         | 8.82%   |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 5.88%   |
| Broadcom 5880                                                                | 2         | 5.88%   |
| Yubico.com Yubikey 4 CCID                                                    | 1         | 2.94%   |
| OmniKey CardMan 4321                                                         | 1         | 2.94%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.94%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 2.94%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.94%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 394       | 74.2%   |
| 1     | 100       | 18.83%  |
| 2     | 32        | 6.03%   |
| 5     | 2         | 0.38%   |
| 3     | 2         | 0.38%   |
| 4     | 1         | 0.19%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 66        | 38.37%  |
| Chipcard                 | 28        | 16.28%  |
| Graphics card            | 26        | 15.12%  |
| Multimedia controller    | 16        | 9.3%    |
| Communication controller | 10        | 5.81%   |
| Net/wireless             | 8         | 4.65%   |
| Unassigned class         | 6         | 3.49%   |
| Storage                  | 3         | 1.74%   |
| Network                  | 3         | 1.74%   |
| Card reader              | 2         | 1.16%   |
| Sound                    | 1         | 0.58%   |
| Modem                    | 1         | 0.58%   |
| Firewire controller      | 1         | 0.58%   |
| Bluetooth                | 1         | 0.58%   |

