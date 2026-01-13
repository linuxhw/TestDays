Parrot - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Parrot.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Parrot/Desktop/README.md) and [notebooks](/Dist/Parrot/Notebook/README.md).

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

Total: 1074

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| AZW           | SER V1.0                    | Mini pc     | [73c4d1d693](https://linux-hardware.org/?probe=73c4d1d693) | Jan 01, 2026 |
| AZW           | SER V1.0                    | Mini pc     | [594df42dc8](https://linux-hardware.org/?probe=594df42dc8) | Dec 31, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [744913d110](https://linux-hardware.org/?probe=744913d110) | Dec 30, 2025 |
| Dell          | 0YXT71 A00                  | Desktop     | [656340a869](https://linux-hardware.org/?probe=656340a869) | Dec 29, 2025 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [d979493a4f](https://linux-hardware.org/?probe=d979493a4f) | Dec 29, 2025 |
| Acer          | Aspire A715-51G             | Notebook    | [505005da4e](https://linux-hardware.org/?probe=505005da4e) | Dec 26, 2025 |
| Acer          | Aspire A715-75G             | Notebook    | [e2184f09c9](https://linux-hardware.org/?probe=e2184f09c9) | Dec 21, 2025 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [70b7496265](https://linux-hardware.org/?probe=70b7496265) | Dec 20, 2025 |
| Gigabyte      | EP43T-S3L                   | Desktop     | [fa303b42ef](https://linux-hardware.org/?probe=fa303b42ef) | Dec 18, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [ee94d47e48](https://linux-hardware.org/?probe=ee94d47e48) | Dec 09, 2025 |
| HP            | 250 G2                      | Notebook    | [bcdae6c7a8](https://linux-hardware.org/?probe=bcdae6c7a8) | Nov 16, 2025 |
| Lenovo        | ThinkPad T14s Gen 4 21F8... | Notebook    | [7b6b56eeaa](https://linux-hardware.org/?probe=7b6b56eeaa) | Oct 22, 2025 |
| Lenovo        | ThinkPad X13 Gen 1 20T3S... | Notebook    | [466fbf7b8e](https://linux-hardware.org/?probe=466fbf7b8e) | Oct 18, 2025 |
| Dell          | Latitude 5480               | Notebook    | [2cd49ec30a](https://linux-hardware.org/?probe=2cd49ec30a) | Oct 16, 2025 |
| MSI           | A320M-A PRO                 | Desktop     | [5b2ecf58f7](https://linux-hardware.org/?probe=5b2ecf58f7) | Oct 16, 2025 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [8daea7ed7f](https://linux-hardware.org/?probe=8daea7ed7f) | Oct 10, 2025 |
| HP            | 18E5                        | Desktop     | [442c80266a](https://linux-hardware.org/?probe=442c80266a) | Oct 03, 2025 |
| Apple         | MacBookPro11,2              | Notebook    | [ff5905b503](https://linux-hardware.org/?probe=ff5905b503) | Oct 02, 2025 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [91160b6a31](https://linux-hardware.org/?probe=91160b6a31) | Oct 01, 2025 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [7bddf7d521](https://linux-hardware.org/?probe=7bddf7d521) | Sep 19, 2025 |
| Apple         | MacBookPro11,2              | Notebook    | [4cf21a84b4](https://linux-hardware.org/?probe=4cf21a84b4) | Sep 19, 2025 |
| HP            | Pavilion g7                 | Notebook    | [02e6f41fef](https://linux-hardware.org/?probe=02e6f41fef) | Sep 18, 2025 |
| MSI           | GF63 Thin 11SC              | Notebook    | [873715915b](https://linux-hardware.org/?probe=873715915b) | Sep 16, 2025 |
| Acer          | Aspire A715-51G             | Notebook    | [5f352f5ec2](https://linux-hardware.org/?probe=5f352f5ec2) | Sep 15, 2025 |
| Acer          | Aspire A715-51G             | Notebook    | [c327e2d1f7](https://linux-hardware.org/?probe=c327e2d1f7) | Sep 15, 2025 |
| AZW           | SER V1.0                    | Mini pc     | [d5d4087691](https://linux-hardware.org/?probe=d5d4087691) | Sep 15, 2025 |
| Google        | Cyan                        | Notebook    | [4a76020090](https://linux-hardware.org/?probe=4a76020090) | Sep 14, 2025 |
| Lenovo        | ThinkPad X230 2325SR3       | Notebook    | [7b07ede8af](https://linux-hardware.org/?probe=7b07ede8af) | Sep 13, 2025 |
| Acer          | Nitro AN515-55              | Notebook    | [7d73867673](https://linux-hardware.org/?probe=7d73867673) | Sep 13, 2025 |
| Google        | Cyan                        | Notebook    | [91676d204f](https://linux-hardware.org/?probe=91676d204f) | Sep 12, 2025 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [70c7076ab2](https://linux-hardware.org/?probe=70c7076ab2) | Sep 10, 2025 |
| Acer          | Nitro AN515-55              | Notebook    | [e0551ee901](https://linux-hardware.org/?probe=e0551ee901) | Sep 09, 2025 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [23f1fd286a](https://linux-hardware.org/?probe=23f1fd286a) | Sep 04, 2025 |
| Shenzhen D... | MP100                       | Desktop     | [cb6bbf5749](https://linux-hardware.org/?probe=cb6bbf5749) | Aug 27, 2025 |
| IBM           | 8215ER9                     | Desktop     | [21f34b2740](https://linux-hardware.org/?probe=21f34b2740) | Aug 23, 2025 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3f6f5a491f](https://linux-hardware.org/?probe=3f6f5a491f) | Aug 21, 2025 |
| Gigabyte      | B650M GAMING PLUS WIFI      | Desktop     | [0fa7b89df6](https://linux-hardware.org/?probe=0fa7b89df6) | Aug 19, 2025 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [416be7ec92](https://linux-hardware.org/?probe=416be7ec92) | Aug 17, 2025 |
| Dell          | Latitude E6420              | Notebook    | [eaf14256e5](https://linux-hardware.org/?probe=eaf14256e5) | Aug 14, 2025 |
| Gigabyte      | A520I AC                    | Desktop     | [fc6c4b2405](https://linux-hardware.org/?probe=fc6c4b2405) | Aug 12, 2025 |
| Dell          | 0WMJ54 A01                  | Desktop     | [ce9e10db3b](https://linux-hardware.org/?probe=ce9e10db3b) | Aug 12, 2025 |
| Gigabyte      | A520I AC                    | Desktop     | [7d8f2be178](https://linux-hardware.org/?probe=7d8f2be178) | Aug 09, 2025 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [f4510613ed](https://linux-hardware.org/?probe=f4510613ed) | Aug 06, 2025 |
| MSI           | PRO Z690-A WIFI DDR4        | Desktop     | [610c55fb14](https://linux-hardware.org/?probe=610c55fb14) | Aug 06, 2025 |
| Alienware     | m15 R4                      | Notebook    | [8de61d6444](https://linux-hardware.org/?probe=8de61d6444) | Aug 04, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d6976bf82a](https://linux-hardware.org/?probe=d6976bf82a) | Aug 04, 2025 |
| Apple         | MacBookPro11,2              | Notebook    | [fd1d2331a9](https://linux-hardware.org/?probe=fd1d2331a9) | Aug 03, 2025 |
| Dell          | 0WMJ54 A01                  | Desktop     | [45bb8820bd](https://linux-hardware.org/?probe=45bb8820bd) | Jul 31, 2025 |
| Mancer        | B450M-DA V1.1               | Desktop     | [7563ca2b25](https://linux-hardware.org/?probe=7563ca2b25) | Jul 30, 2025 |
| HP            | 1589                        | Desktop     | [5a9ff5753b](https://linux-hardware.org/?probe=5a9ff5753b) | Jul 30, 2025 |
| ASUSTek       | ROG Zephyrus M16 GU603ZM... | Notebook    | [8305a624c8](https://linux-hardware.org/?probe=8305a624c8) | Jul 29, 2025 |
| Dell          | Latitude 5289               | Notebook    | [cee903145e](https://linux-hardware.org/?probe=cee903145e) | Jul 13, 2025 |
| Dell          | 07WP95 A02                  | Desktop     | [11eacb862e](https://linux-hardware.org/?probe=11eacb862e) | Jul 12, 2025 |
| Dell          | Latitude 5540               | Notebook    | [c7fb8843f0](https://linux-hardware.org/?probe=c7fb8843f0) | Jul 11, 2025 |
| Lenovo        | VersaPro Type VB 20F5000... | Notebook    | [0a05f8b17f](https://linux-hardware.org/?probe=0a05f8b17f) | Jul 06, 2025 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [6ef3913344](https://linux-hardware.org/?probe=6ef3913344) | Jun 23, 2025 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [f93213d03b](https://linux-hardware.org/?probe=f93213d03b) | Jun 23, 2025 |
| Lenovo        | 3102 SDK0J40697 WIN 3305... | Desktop     | [ed1051cbc6](https://linux-hardware.org/?probe=ed1051cbc6) | Jun 16, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [f84a315a87](https://linux-hardware.org/?probe=f84a315a87) | Jun 09, 2025 |
| Dell          | Latitude E5250              | Notebook    | [d6946cbb78](https://linux-hardware.org/?probe=d6946cbb78) | May 29, 2025 |
| Dell          | Latitude 5310               | Notebook    | [6220db7cc7](https://linux-hardware.org/?probe=6220db7cc7) | May 29, 2025 |
| Lenovo        | Y50-70 20378                | Notebook    | [5b76e0b9e8](https://linux-hardware.org/?probe=5b76e0b9e8) | May 28, 2025 |
| ASUSTek       | GL553VD                     | Notebook    | [4a044c2e72](https://linux-hardware.org/?probe=4a044c2e72) | May 25, 2025 |
| MSI           | Summit E13 AI Evo A1MTG     | Notebook    | [bf2eb29374](https://linux-hardware.org/?probe=bf2eb29374) | May 23, 2025 |
| Dell          | Latitude 5320               | Notebook    | [7a34b99885](https://linux-hardware.org/?probe=7a34b99885) | May 16, 2025 |
| MSI           | Thin 15 B12UCX              | Notebook    | [0149065484](https://linux-hardware.org/?probe=0149065484) | May 15, 2025 |
| Acer          | Nitro AN515-55              | Notebook    | [ef6312509f](https://linux-hardware.org/?probe=ef6312509f) | May 13, 2025 |
| Foxconn       | 2A92                        | Desktop     | [dd7a3713c5](https://linux-hardware.org/?probe=dd7a3713c5) | May 10, 2025 |
| HP            | EliteBook 830 G6            | Notebook    | [593a3dd9eb](https://linux-hardware.org/?probe=593a3dd9eb) | May 06, 2025 |
| Acer          | Nitro AN515-55              | Notebook    | [fb5899c78a](https://linux-hardware.org/?probe=fb5899c78a) | May 05, 2025 |
| Wortmann      | 1220571_1470066             | Notebook    | [4b08fc4ff4](https://linux-hardware.org/?probe=4b08fc4ff4) | May 04, 2025 |
| Toshiba       | Satellite L750              | Notebook    | [16e2788551](https://linux-hardware.org/?probe=16e2788551) | May 04, 2025 |
| HP            | 0AACh                       | Desktop     | [c91d397030](https://linux-hardware.org/?probe=c91d397030) | May 03, 2025 |
| Intel         | H81                         | Desktop     | [b026bbb2f2](https://linux-hardware.org/?probe=b026bbb2f2) | May 02, 2025 |
| Microsoft     | Surface Pro 7               | Tablet      | [9d83ace38a](https://linux-hardware.org/?probe=9d83ace38a) | May 01, 2025 |
| Dell          | Latitude 5320               | Notebook    | [ae25a92124](https://linux-hardware.org/?probe=ae25a92124) | Apr 30, 2025 |
| Lenovo        | ThinkPad L580 20LXS4K01T    | Notebook    | [92fe8ad34f](https://linux-hardware.org/?probe=92fe8ad34f) | Apr 26, 2025 |
| HP            | EliteBook 830 G6            | Notebook    | [a217cf929b](https://linux-hardware.org/?probe=a217cf929b) | Apr 26, 2025 |
| ASUSTek       | G75VW                       | Notebook    | [48fb9c18bd](https://linux-hardware.org/?probe=48fb9c18bd) | Apr 25, 2025 |
| ASUSTek       | G75VW                       | Notebook    | [dfd21655e2](https://linux-hardware.org/?probe=dfd21655e2) | Apr 24, 2025 |
| Dell          | Latitude 5540               | Notebook    | [98cd6b73bd](https://linux-hardware.org/?probe=98cd6b73bd) | Apr 24, 2025 |
| Fujitsu       | LIFEBOOK U7311              | Notebook    | [c67ef08569](https://linux-hardware.org/?probe=c67ef08569) | Apr 23, 2025 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6377d14004](https://linux-hardware.org/?probe=6377d14004) | Apr 16, 2025 |
| ASUSTek       | ROG STRIX X870E-E GAMING... | Desktop     | [e05942bf7b](https://linux-hardware.org/?probe=e05942bf7b) | Apr 11, 2025 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [f9d5eeacd5](https://linux-hardware.org/?probe=f9d5eeacd5) | Apr 10, 2025 |
| HP            | EliteBook 830 G6            | Notebook    | [1653ef90a2](https://linux-hardware.org/?probe=1653ef90a2) | Apr 09, 2025 |
| HP            | EliteBook 820 G3            | Notebook    | [f980f38a0c](https://linux-hardware.org/?probe=f980f38a0c) | Apr 09, 2025 |
| Toshiba       | Satellite L750              | Notebook    | [56d38de9fa](https://linux-hardware.org/?probe=56d38de9fa) | Apr 07, 2025 |
| Samsung       | 750XGK                      | Notebook    | [ce93e99625](https://linux-hardware.org/?probe=ce93e99625) | Apr 03, 2025 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [85fa36c903](https://linux-hardware.org/?probe=85fa36c903) | Apr 02, 2025 |
| Lenovo        | ThinkPad X390 20Q1S2SA00    | Notebook    | [654cf2f499](https://linux-hardware.org/?probe=654cf2f499) | Mar 30, 2025 |
| Acer          | Nitro ANV15-51              | Notebook    | [ed3711c5a9](https://linux-hardware.org/?probe=ed3711c5a9) | Mar 26, 2025 |
| Lenovo        | ThinkPad X250 20CLA15GCD    | Notebook    | [a3eef98464](https://linux-hardware.org/?probe=a3eef98464) | Mar 25, 2025 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [606b10b6dd](https://linux-hardware.org/?probe=606b10b6dd) | Mar 24, 2025 |
| Dell          | Inspiron 5570               | Notebook    | [0826cacd1c](https://linux-hardware.org/?probe=0826cacd1c) | Mar 24, 2025 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [031d5da69c](https://linux-hardware.org/?probe=031d5da69c) | Mar 23, 2025 |
| MSI           | GF65 Thin 10UE              | Notebook    | [4c79bba223](https://linux-hardware.org/?probe=4c79bba223) | Mar 23, 2025 |
| Acer          | Nitro AN17-41               | Notebook    | [45ba9bff84](https://linux-hardware.org/?probe=45ba9bff84) | Mar 19, 2025 |
| Lenovo        | Yoga Slim 6 14IAP8 83C7     | Notebook    | [347246bfd8](https://linux-hardware.org/?probe=347246bfd8) | Mar 19, 2025 |
| Lenovo        | Yoga Slim 6 14IAP8 83C7     | Notebook    | [b459d6f900](https://linux-hardware.org/?probe=b459d6f900) | Mar 19, 2025 |
| Dell          | Inspiron 5570               | Notebook    | [5db1ab546e](https://linux-hardware.org/?probe=5db1ab546e) | Mar 19, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [9b71f53122](https://linux-hardware.org/?probe=9b71f53122) | Mar 14, 2025 |
| Toshiba       | Satellite L750              | Notebook    | [d5c8babf81](https://linux-hardware.org/?probe=d5c8babf81) | Mar 10, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [c168f6e2f3](https://linux-hardware.org/?probe=c168f6e2f3) | Feb 28, 2025 |
| Supermicro    | X9DRD-7LN4F                 | Desktop     | [f246d95df8](https://linux-hardware.org/?probe=f246d95df8) | Feb 27, 2025 |
| Toshiba       | Satellite L750              | Notebook    | [e122ba0efb](https://linux-hardware.org/?probe=e122ba0efb) | Feb 27, 2025 |
| Maibenben     | MaiBook X series            | Notebook    | [eb682062bf](https://linux-hardware.org/?probe=eb682062bf) | Feb 24, 2025 |
| Gigabyte      | A520M K V2                  | Desktop     | [89861d455b](https://linux-hardware.org/?probe=89861d455b) | Feb 24, 2025 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [fac6745cb7](https://linux-hardware.org/?probe=fac6745cb7) | Feb 24, 2025 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [f4e74128aa](https://linux-hardware.org/?probe=f4e74128aa) | Feb 21, 2025 |
| Acer          | Aspire A315-24PT            | Notebook    | [4f36954228](https://linux-hardware.org/?probe=4f36954228) | Feb 18, 2025 |
| ASUSTek       | Vivobook Go E1504FA_E150... | Notebook    | [525b50d759](https://linux-hardware.org/?probe=525b50d759) | Feb 14, 2025 |
| Acer          | Aspire A515-41G             | Notebook    | [73bc9f01ba](https://linux-hardware.org/?probe=73bc9f01ba) | Feb 09, 2025 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [8d734380d1](https://linux-hardware.org/?probe=8d734380d1) | Feb 04, 2025 |
| HP            | ZBook 17 G6                 | Notebook    | [d18a524ac7](https://linux-hardware.org/?probe=d18a524ac7) | Feb 01, 2025 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [25accf5d71](https://linux-hardware.org/?probe=25accf5d71) | Jan 29, 2025 |
| Acer          | Nitro AN517-52              | Notebook    | [5c97d8274c](https://linux-hardware.org/?probe=5c97d8274c) | Jan 26, 2025 |
| ASUSTek       | Zenbook UM3402YA_UM3402Y... | Notebook    | [f8b4df4a1a](https://linux-hardware.org/?probe=f8b4df4a1a) | Jan 20, 2025 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [2b8502327a](https://linux-hardware.org/?probe=2b8502327a) | Jan 17, 2025 |
| Dell          | XPS 13 9305                 | Notebook    | [5b06a32fea](https://linux-hardware.org/?probe=5b06a32fea) | Jan 06, 2025 |
| Acer          | Nitro AN515-55              | Notebook    | [87f960a021](https://linux-hardware.org/?probe=87f960a021) | Jan 05, 2025 |
| ASRock        | B550M-HDV                   | Desktop     | [6ce988b582](https://linux-hardware.org/?probe=6ce988b582) | Jan 04, 2025 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [63b427416a](https://linux-hardware.org/?probe=63b427416a) | Jan 02, 2025 |
| Acer          | Aspire A315-510P            | Notebook    | [f3fd803275](https://linux-hardware.org/?probe=f3fd803275) | Jan 01, 2025 |
| Acer          | Aspire A315-510P            | Notebook    | [b079131625](https://linux-hardware.org/?probe=b079131625) | Dec 30, 2024 |
| Acer          | Aspire A315-510P            | Notebook    | [ede893e1e1](https://linux-hardware.org/?probe=ede893e1e1) | Dec 30, 2024 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [f1382538df](https://linux-hardware.org/?probe=f1382538df) | Dec 28, 2024 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [247cc9f886](https://linux-hardware.org/?probe=247cc9f886) | Dec 24, 2024 |
| HP            | ProBook 440 G7              | Notebook    | [205f2940e7](https://linux-hardware.org/?probe=205f2940e7) | Dec 24, 2024 |
| HP            | 0AA8h                       | Desktop     | [5f76cb932b](https://linux-hardware.org/?probe=5f76cb932b) | Dec 23, 2024 |
| HP            | 0AA8h                       | Desktop     | [8a22af001d](https://linux-hardware.org/?probe=8a22af001d) | Dec 23, 2024 |
| ASUSTek       | S400CA                      | Notebook    | [a076c3dca9](https://linux-hardware.org/?probe=a076c3dca9) | Dec 20, 2024 |
| HP            | EliteBook Folio 9480m       | Notebook    | [7d0e5bbe48](https://linux-hardware.org/?probe=7d0e5bbe48) | Dec 14, 2024 |
| HP            | 1587h                       | Desktop     | [0c955e88ce](https://linux-hardware.org/?probe=0c955e88ce) | Dec 13, 2024 |
| HP            | 1587h                       | Desktop     | [85205e402a](https://linux-hardware.org/?probe=85205e402a) | Dec 12, 2024 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [e96ccf6429](https://linux-hardware.org/?probe=e96ccf6429) | Dec 10, 2024 |
| MSI           | Katana GF66 11UE            | Notebook    | [b74e19bf4f](https://linux-hardware.org/?probe=b74e19bf4f) | Dec 10, 2024 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [cb5e7488d1](https://linux-hardware.org/?probe=cb5e7488d1) | Dec 07, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [bd90895fef](https://linux-hardware.org/?probe=bd90895fef) | Dec 07, 2024 |
| ASUSTek       | S400CA                      | Notebook    | [6b626eb981](https://linux-hardware.org/?probe=6b626eb981) | Dec 01, 2024 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | Notebook    | [8a363e4242](https://linux-hardware.org/?probe=8a363e4242) | Nov 29, 2024 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [e55906c344](https://linux-hardware.org/?probe=e55906c344) | Nov 28, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2ca4532a01](https://linux-hardware.org/?probe=2ca4532a01) | Nov 27, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [fd5c871a74](https://linux-hardware.org/?probe=fd5c871a74) | Nov 27, 2024 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [2397b52715](https://linux-hardware.org/?probe=2397b52715) | Nov 27, 2024 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [4da22094eb](https://linux-hardware.org/?probe=4da22094eb) | Nov 25, 2024 |
| MSI           | PRO B760-VC WIFI 7 BULK     | Desktop     | [e51990975e](https://linux-hardware.org/?probe=e51990975e) | Nov 25, 2024 |
| Google        | Caroline                    | Notebook    | [3783098457](https://linux-hardware.org/?probe=3783098457) | Nov 23, 2024 |
| Dell          | Latitude 7490               | Notebook    | [47d677a13e](https://linux-hardware.org/?probe=47d677a13e) | Nov 22, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [d8aeb9e84d](https://linux-hardware.org/?probe=d8aeb9e84d) | Nov 13, 2024 |
| ASUSTek       | ProArt X670E-CREATOR WIF... | Desktop     | [aceb94369e](https://linux-hardware.org/?probe=aceb94369e) | Nov 13, 2024 |
| HP            | EliteBook 2560p             | Notebook    | [84d5a17ce2](https://linux-hardware.org/?probe=84d5a17ce2) | Nov 12, 2024 |
| Panasonic     | FZ55-2                      | Notebook    | [72e6f447fd](https://linux-hardware.org/?probe=72e6f447fd) | Nov 09, 2024 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [b31e3a00d3](https://linux-hardware.org/?probe=b31e3a00d3) | Nov 02, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [a3e0d131dc](https://linux-hardware.org/?probe=a3e0d131dc) | Nov 01, 2024 |
| ASUSTek       | H81M-C                      | Desktop     | [f7228f91c2](https://linux-hardware.org/?probe=f7228f91c2) | Nov 01, 2024 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [ee7b5089e2](https://linux-hardware.org/?probe=ee7b5089e2) | Oct 24, 2024 |
| Unknown       | Unknown                     | Desktop     | [3a8dff97c1](https://linux-hardware.org/?probe=3a8dff97c1) | Oct 23, 2024 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [b1209b5d81](https://linux-hardware.org/?probe=b1209b5d81) | Oct 18, 2024 |
| Lenovo        | ThinkPad X260 20F5A13P00    | Notebook    | [4ac4d50f73](https://linux-hardware.org/?probe=4ac4d50f73) | Oct 17, 2024 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | Notebook    | [5a97215ee3](https://linux-hardware.org/?probe=5a97215ee3) | Oct 15, 2024 |
| Dell          | Inspiron 14 7430 2-in-1     | Convertible | [7666cd37c7](https://linux-hardware.org/?probe=7666cd37c7) | Oct 15, 2024 |
| Dell          | Inspiron 14 7430 2-in-1     | Convertible | [4c0992c685](https://linux-hardware.org/?probe=4c0992c685) | Oct 15, 2024 |
| Foxconn       | 2ABF                        | Desktop     | [a154274724](https://linux-hardware.org/?probe=a154274724) | Oct 15, 2024 |
| HP            | Pavilion Laptop 15-cc5xx    | Notebook    | [7cdb58b80e](https://linux-hardware.org/?probe=7cdb58b80e) | Oct 10, 2024 |
| Acer          | Aspire A515-51G             | Notebook    | [020774040e](https://linux-hardware.org/?probe=020774040e) | Oct 10, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [38d2b1b15c](https://linux-hardware.org/?probe=38d2b1b15c) | Oct 05, 2024 |
| Lenovo        | ThinkPad E14 Gen 6 21M70... | Notebook    | [d52e4fc3c0](https://linux-hardware.org/?probe=d52e4fc3c0) | Oct 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [cb3a3420ad](https://linux-hardware.org/?probe=cb3a3420ad) | Oct 01, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X140... | Notebook    | [a0adceb41d](https://linux-hardware.org/?probe=a0adceb41d) | Sep 26, 2024 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [ba1ef8f0ae](https://linux-hardware.org/?probe=ba1ef8f0ae) | Sep 25, 2024 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [da7400591d](https://linux-hardware.org/?probe=da7400591d) | Sep 25, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [22961f031e](https://linux-hardware.org/?probe=22961f031e) | Sep 24, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b73138fbf5](https://linux-hardware.org/?probe=b73138fbf5) | Sep 23, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [ba2f866270](https://linux-hardware.org/?probe=ba2f866270) | Sep 07, 2024 |
| HP            | Laptop 15-dw2xxx            | Notebook    | [08230cbafb](https://linux-hardware.org/?probe=08230cbafb) | Sep 03, 2024 |
| Gigabyte      | B660M AORUS PRO DDR4        | Desktop     | [293134b0b9](https://linux-hardware.org/?probe=293134b0b9) | Sep 03, 2024 |
| Lenovo        | ThinkPad T450s 20BX001EU... | Notebook    | [fd7ece1b23](https://linux-hardware.org/?probe=fd7ece1b23) | Sep 01, 2024 |
| Panasonic     | CF-31-5                     | Notebook    | [3dc2b9bef7](https://linux-hardware.org/?probe=3dc2b9bef7) | Aug 30, 2024 |
| Panasonic     | CF-31-5                     | Notebook    | [15b61b0ba5](https://linux-hardware.org/?probe=15b61b0ba5) | Aug 30, 2024 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [faf752e7d5](https://linux-hardware.org/?probe=faf752e7d5) | Aug 27, 2024 |
| HP            | ProBook 650 G8 Notebook ... | Notebook    | [4870c26466](https://linux-hardware.org/?probe=4870c26466) | Aug 27, 2024 |
| HP            | EliteBook 830 G6            | Notebook    | [453f8f7b00](https://linux-hardware.org/?probe=453f8f7b00) | Aug 25, 2024 |
| HP            | EliteBook 830 G6            | Notebook    | [082baba5be](https://linux-hardware.org/?probe=082baba5be) | Aug 25, 2024 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [a10bc8baff](https://linux-hardware.org/?probe=a10bc8baff) | Aug 23, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [df3aacdfdd](https://linux-hardware.org/?probe=df3aacdfdd) | Aug 22, 2024 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [80db9ffa06](https://linux-hardware.org/?probe=80db9ffa06) | Aug 22, 2024 |
| Dell          | Inspiron 7559               | Notebook    | [1b8c70c653](https://linux-hardware.org/?probe=1b8c70c653) | Aug 18, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [752156b44a](https://linux-hardware.org/?probe=752156b44a) | Aug 16, 2024 |
| Dell          | 0WMJ54 A01                  | Desktop     | [d877099204](https://linux-hardware.org/?probe=d877099204) | Aug 14, 2024 |
| Acer          | Aspire ES1-431              | Notebook    | [7dd0a748d7](https://linux-hardware.org/?probe=7dd0a748d7) | Aug 14, 2024 |
| Gigabyte      | X99-SLI-CF                  | Desktop     | [2b28fed015](https://linux-hardware.org/?probe=2b28fed015) | Aug 06, 2024 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [f01ca35d63](https://linux-hardware.org/?probe=f01ca35d63) | Aug 05, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [22c0d405de](https://linux-hardware.org/?probe=22c0d405de) | Aug 01, 2024 |
| Acer          | Predator PT314-51s          | Notebook    | [8eda2b6d8a](https://linux-hardware.org/?probe=8eda2b6d8a) | Jul 28, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [154385f06a](https://linux-hardware.org/?probe=154385f06a) | Jul 23, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [224fdf8c28](https://linux-hardware.org/?probe=224fdf8c28) | Jul 23, 2024 |
| HP            | EliteBook 850 G3            | Notebook    | [5a3d8f3ce0](https://linux-hardware.org/?probe=5a3d8f3ce0) | Jul 23, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [34fa837cb3](https://linux-hardware.org/?probe=34fa837cb3) | Jul 18, 2024 |
| Foxconn       | 2AB1 DVT                    | Desktop     | [610048cdd2](https://linux-hardware.org/?probe=610048cdd2) | Jul 16, 2024 |
| Foxconn       | 2AB1 DVT                    | Desktop     | [855e1bd72f](https://linux-hardware.org/?probe=855e1bd72f) | Jul 16, 2024 |
| Lenovo        | IdeaPadFlex 5 15IIL05 81... | Convertible | [5269132576](https://linux-hardware.org/?probe=5269132576) | Jul 15, 2024 |
| Lenovo        | IdeaPadFlex 5 15IIL05 81... | Convertible | [529eaa1393](https://linux-hardware.org/?probe=529eaa1393) | Jul 15, 2024 |
| Dell          | Latitude 5511               | Notebook    | [6094708e32](https://linux-hardware.org/?probe=6094708e32) | Jul 14, 2024 |
| MSI           | Prestige 13 AI Evo A1MG     | Notebook    | [f201feeb20](https://linux-hardware.org/?probe=f201feeb20) | Jul 14, 2024 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6ad8913d16](https://linux-hardware.org/?probe=6ad8913d16) | Jul 09, 2024 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [4d4543ae64](https://linux-hardware.org/?probe=4d4543ae64) | Jul 09, 2024 |
| HP            | 250 G7 Notebook PC          | Notebook    | [38b439c526](https://linux-hardware.org/?probe=38b439c526) | Jul 06, 2024 |
| Lenovo        | E50-80 80J2                 | Notebook    | [6ef0c878e3](https://linux-hardware.org/?probe=6ef0c878e3) | Jul 06, 2024 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [290e8e87d1](https://linux-hardware.org/?probe=290e8e87d1) | Jun 28, 2024 |
| HC Technol... | HCAR5000-MI                 | Desktop     | [ee1ab4ebe8](https://linux-hardware.org/?probe=ee1ab4ebe8) | Jun 27, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [7da90462ec](https://linux-hardware.org/?probe=7da90462ec) | Jun 22, 2024 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [c22d1433bf](https://linux-hardware.org/?probe=c22d1433bf) | Jun 15, 2024 |
| Orange Pi     | 5                           | Soc         | [b7c66c1d54](https://linux-hardware.org/?probe=b7c66c1d54) | Jun 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [e570948d49](https://linux-hardware.org/?probe=e570948d49) | Jun 10, 2024 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [d5de03918b](https://linux-hardware.org/?probe=d5de03918b) | Jun 05, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [f41596eb9b](https://linux-hardware.org/?probe=f41596eb9b) | Jun 03, 2024 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [88ea74eb50](https://linux-hardware.org/?probe=88ea74eb50) | Jun 03, 2024 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [93ed456d67](https://linux-hardware.org/?probe=93ed456d67) | Jun 02, 2024 |
| HP            | 18E7                        | Desktop     | [42046a0b95](https://linux-hardware.org/?probe=42046a0b95) | May 27, 2024 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [3779586782](https://linux-hardware.org/?probe=3779586782) | May 25, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [7642e68170](https://linux-hardware.org/?probe=7642e68170) | May 16, 2024 |
| Lenovo        | ThinkPad T410 2537VXX       | Notebook    | [a5aa605397](https://linux-hardware.org/?probe=a5aa605397) | May 10, 2024 |
| Toshiba       | Satellite E55-A             | Notebook    | [b77667e33a](https://linux-hardware.org/?probe=b77667e33a) | May 08, 2024 |
| HP            | 2000                        | Notebook    | [71d3942f81](https://linux-hardware.org/?probe=71d3942f81) | May 06, 2024 |
| Acer          | Aspire E1-522               | Notebook    | [b1c41ef5a0](https://linux-hardware.org/?probe=b1c41ef5a0) | May 04, 2024 |
| Dell          | Latitude E6430              | Notebook    | [3ea51c9416](https://linux-hardware.org/?probe=3ea51c9416) | May 04, 2024 |
| Dell          | Latitude E6430              | Notebook    | [0e3b2e7c55](https://linux-hardware.org/?probe=0e3b2e7c55) | May 04, 2024 |
| Toshiba       | Satellite E55-A             | Notebook    | [66fc7bf95a](https://linux-hardware.org/?probe=66fc7bf95a) | Apr 30, 2024 |
| Acidanther... | MacBookAir9,1               | Notebook    | [ba60edeb99](https://linux-hardware.org/?probe=ba60edeb99) | Apr 25, 2024 |
| Apple         | Mac-F226BEC8 PVT            | All in one  | [8cb1d1d18b](https://linux-hardware.org/?probe=8cb1d1d18b) | Apr 24, 2024 |
| Lenovo        | ThinkPad X1 Tablet Gen 3... | Tablet      | [ae663e3731](https://linux-hardware.org/?probe=ae663e3731) | Apr 24, 2024 |
| MSI           | GL75 9SEK                   | Notebook    | [3d679e4ec2](https://linux-hardware.org/?probe=3d679e4ec2) | Apr 17, 2024 |
| MSI           | GL75 9SEK                   | Notebook    | [b2d528d9b4](https://linux-hardware.org/?probe=b2d528d9b4) | Apr 16, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [6291093e82](https://linux-hardware.org/?probe=6291093e82) | Apr 16, 2024 |
| Lenovo        | E41-25 81FS                 | Notebook    | [ee47604b55](https://linux-hardware.org/?probe=ee47604b55) | Apr 13, 2024 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [bc17e5113b](https://linux-hardware.org/?probe=bc17e5113b) | Apr 13, 2024 |
| HP            | Laptop 14-cf2xxx            | Notebook    | [bef6cb8975](https://linux-hardware.org/?probe=bef6cb8975) | Apr 13, 2024 |
| ASUSTek       | H110M-R                     | Desktop     | [473b7a412c](https://linux-hardware.org/?probe=473b7a412c) | Apr 10, 2024 |
| Lenovo        | Z50-70 20354                | Notebook    | [4469cb6e76](https://linux-hardware.org/?probe=4469cb6e76) | Apr 10, 2024 |
| ASUSTek       | H110M-R                     | Desktop     | [d8c6b0c73f](https://linux-hardware.org/?probe=d8c6b0c73f) | Apr 10, 2024 |
| ASUSTek       | ROG Strix G513QR_G513QR     | Notebook    | [2c23a28e81](https://linux-hardware.org/?probe=2c23a28e81) | Apr 08, 2024 |
| Biostar       | H410MH                      | Desktop     | [b8034503cb](https://linux-hardware.org/?probe=b8034503cb) | Apr 04, 2024 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [c737a816f3](https://linux-hardware.org/?probe=c737a816f3) | Apr 04, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [d0eac00952](https://linux-hardware.org/?probe=d0eac00952) | Apr 02, 2024 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [c498cd96d4](https://linux-hardware.org/?probe=c498cd96d4) | Mar 31, 2024 |
| Razer         | Blade 15 - RZ09-0485        | Notebook    | [24980909b2](https://linux-hardware.org/?probe=24980909b2) | Mar 26, 2024 |
| ASUSTek       | PRIME X570-P                | Desktop     | [8928a51f78](https://linux-hardware.org/?probe=8928a51f78) | Mar 22, 2024 |
| HP            | EliteBook 830 G6            | Notebook    | [955e65cc0f](https://linux-hardware.org/?probe=955e65cc0f) | Mar 22, 2024 |
| HP            | EliteBook 830 G6            | Notebook    | [c5ada253ab](https://linux-hardware.org/?probe=c5ada253ab) | Mar 22, 2024 |
| HP            | EliteBook 830 G6            | Notebook    | [2ab6329c32](https://linux-hardware.org/?probe=2ab6329c32) | Mar 22, 2024 |
| Acer          | Extensa 5230                | Notebook    | [790672cb92](https://linux-hardware.org/?probe=790672cb92) | Mar 22, 2024 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [700d8c6016](https://linux-hardware.org/?probe=700d8c6016) | Mar 18, 2024 |
| Lenovo        | ThinkPad T480 20L6S69X08    | Notebook    | [63c84de71e](https://linux-hardware.org/?probe=63c84de71e) | Mar 15, 2024 |
| Gigabyte      | H81M-DS2                    | Desktop     | [db79be4310](https://linux-hardware.org/?probe=db79be4310) | Mar 09, 2024 |
| Dell          | Latitude 5420 Rugged        | Notebook    | [f9c7c915c9](https://linux-hardware.org/?probe=f9c7c915c9) | Mar 08, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [58e64cec89](https://linux-hardware.org/?probe=58e64cec89) | Mar 06, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [74faba00a3](https://linux-hardware.org/?probe=74faba00a3) | Mar 05, 2024 |
| Lenovo        | ThinkPad T480 20L6S69X08    | Notebook    | [16326b521f](https://linux-hardware.org/?probe=16326b521f) | Mar 01, 2024 |
| MSI           | Z97 GAMING 7                | Desktop     | [be7cf8b3fc](https://linux-hardware.org/?probe=be7cf8b3fc) | Mar 01, 2024 |
| Dell          | XPS 13 9370                 | Notebook    | [086a1782c7](https://linux-hardware.org/?probe=086a1782c7) | Feb 22, 2024 |
| Lenovo        | IdeaPad S145-14API 81UV     | Notebook    | [da65aaff1d](https://linux-hardware.org/?probe=da65aaff1d) | Feb 20, 2024 |
| Samsung       | 750XDA                      | Notebook    | [0aed547d08](https://linux-hardware.org/?probe=0aed547d08) | Feb 18, 2024 |
| HP            | Pavilion dv4                | Notebook    | [20e9de9ad8](https://linux-hardware.org/?probe=20e9de9ad8) | Feb 08, 2024 |
| ASUSTek       | UX430UAR                    | Notebook    | [cc89a20253](https://linux-hardware.org/?probe=cc89a20253) | Feb 04, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [fcabd4a1f4](https://linux-hardware.org/?probe=fcabd4a1f4) | Feb 01, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [b31d7d9323](https://linux-hardware.org/?probe=b31d7d9323) | Feb 01, 2024 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [7acd38748f](https://linux-hardware.org/?probe=7acd38748f) | Jan 30, 2024 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [0a1087fdad](https://linux-hardware.org/?probe=0a1087fdad) | Jan 29, 2024 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [b7fff52e41](https://linux-hardware.org/?probe=b7fff52e41) | Jan 29, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [7c4514376b](https://linux-hardware.org/?probe=7c4514376b) | Jan 27, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [f1117537a5](https://linux-hardware.org/?probe=f1117537a5) | Jan 27, 2024 |
| Acer          | Aspire A715-51G             | Notebook    | [fad23c2b03](https://linux-hardware.org/?probe=fad23c2b03) | Jan 27, 2024 |
| Dell          | XPS 13 9350                 | Notebook    | [fb1c7c4cab](https://linux-hardware.org/?probe=fb1c7c4cab) | Jan 26, 2024 |
| Lenovo        | ThinkPad T460s 20FAS2JW0... | Notebook    | [59d637113b](https://linux-hardware.org/?probe=59d637113b) | Jan 26, 2024 |
| Acer          | Aspire E1-522               | Notebook    | [a43c97b66c](https://linux-hardware.org/?probe=a43c97b66c) | Jan 26, 2024 |
| HP            | ProBook 455 G4              | Notebook    | [6490d02d72](https://linux-hardware.org/?probe=6490d02d72) | Jan 22, 2024 |
| ASRock        | Z77M                        | Desktop     | [f3bd1cdf2c](https://linux-hardware.org/?probe=f3bd1cdf2c) | Jan 19, 2024 |
| Lenovo        | IdeaPad 1 15IAU7 82QD       | Notebook    | [bb5610a4f5](https://linux-hardware.org/?probe=bb5610a4f5) | Jan 17, 2024 |
| Acer          | Aspire E1-522               | Notebook    | [538c5ee96f](https://linux-hardware.org/?probe=538c5ee96f) | Jan 16, 2024 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [ca8734dc63](https://linux-hardware.org/?probe=ca8734dc63) | Jan 11, 2024 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [feaf3edd58](https://linux-hardware.org/?probe=feaf3edd58) | Jan 10, 2024 |
| Acer          | Aspire A715-51G             | Notebook    | [2a3ea77b7a](https://linux-hardware.org/?probe=2a3ea77b7a) | Jan 10, 2024 |
| Lenovo        | ThinkPad T490 20N20023US    | Notebook    | [ce82358c06](https://linux-hardware.org/?probe=ce82358c06) | Jan 04, 2024 |
| Lenovo        | ThinkPad T490 20N20023US    | Notebook    | [ffe96991b4](https://linux-hardware.org/?probe=ffe96991b4) | Jan 04, 2024 |
| HP            | ProBook 450 G5              | Notebook    | [b80a7c9287](https://linux-hardware.org/?probe=b80a7c9287) | Jan 02, 2024 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [1f44330bcf](https://linux-hardware.org/?probe=1f44330bcf) | Dec 31, 2023 |
| Lenovo        | ThinkPad T490 20N3S4PX02    | Notebook    | [0afd47e9fc](https://linux-hardware.org/?probe=0afd47e9fc) | Dec 31, 2023 |
| Google        | Blorb                       | Notebook    | [4e0c068a82](https://linux-hardware.org/?probe=4e0c068a82) | Dec 30, 2023 |
| MSI           | B550 GAMING GEN3            | Desktop     | [02163b04b7](https://linux-hardware.org/?probe=02163b04b7) | Dec 30, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [404320e4d7](https://linux-hardware.org/?probe=404320e4d7) | Dec 28, 2023 |
| HP            | Pavilion g6                 | Notebook    | [62a002d063](https://linux-hardware.org/?probe=62a002d063) | Dec 26, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [5c7029f981](https://linux-hardware.org/?probe=5c7029f981) | Dec 23, 2023 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | Notebook    | [980280224f](https://linux-hardware.org/?probe=980280224f) | Dec 18, 2023 |
| Lenovo        | IdeaPad 1 11ADA05 82GV      | Notebook    | [41f03f0699](https://linux-hardware.org/?probe=41f03f0699) | Dec 18, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [72facc22f6](https://linux-hardware.org/?probe=72facc22f6) | Dec 14, 2023 |
| Toshiba       | PORTEGE R930                | Notebook    | [e341599417](https://linux-hardware.org/?probe=e341599417) | Dec 14, 2023 |
| MSI           | MPG Z490 GAMING EDGE WIF... | Desktop     | [d90c13f9c6](https://linux-hardware.org/?probe=d90c13f9c6) | Dec 12, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [baf21dcbce](https://linux-hardware.org/?probe=baf21dcbce) | Dec 06, 2023 |
| ASUSTek       | X540SAA                     | Notebook    | [86295630b8](https://linux-hardware.org/?probe=86295630b8) | Dec 06, 2023 |
| Alienware     | 17 R5                       | Notebook    | [e0fdc679e3](https://linux-hardware.org/?probe=e0fdc679e3) | Dec 04, 2023 |
| Alienware     | 17 R5                       | Notebook    | [1e44992982](https://linux-hardware.org/?probe=1e44992982) | Dec 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [30c19ab13f](https://linux-hardware.org/?probe=30c19ab13f) | Dec 04, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80Q7      | Notebook    | [d416d62cf1](https://linux-hardware.org/?probe=d416d62cf1) | Nov 29, 2023 |
| Acer          | Nitro AN517-55              | Notebook    | [91df918363](https://linux-hardware.org/?probe=91df918363) | Nov 28, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [a54c387b5f](https://linux-hardware.org/?probe=a54c387b5f) | Nov 27, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [e22c72e9d4](https://linux-hardware.org/?probe=e22c72e9d4) | Nov 26, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3242361790](https://linux-hardware.org/?probe=3242361790) | Nov 25, 2023 |
| Apple         | MacBookAir6,1               | Notebook    | [dfa296fd96](https://linux-hardware.org/?probe=dfa296fd96) | Nov 25, 2023 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [8ad2369936](https://linux-hardware.org/?probe=8ad2369936) | Nov 21, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [a8e951e3b6](https://linux-hardware.org/?probe=a8e951e3b6) | Nov 20, 2023 |
| Lenovo        | ThinkPad L13 Gen 3 21B30... | Notebook    | [5685f17122](https://linux-hardware.org/?probe=5685f17122) | Nov 19, 2023 |
| Acer          | TravelMate 5760             | Notebook    | [f90be838c9](https://linux-hardware.org/?probe=f90be838c9) | Nov 18, 2023 |
| Acer          | TravelMate 5760             | Notebook    | [db234d226d](https://linux-hardware.org/?probe=db234d226d) | Nov 18, 2023 |
| Dell          | Latitude E6530              | Notebook    | [f43bd72db4](https://linux-hardware.org/?probe=f43bd72db4) | Nov 16, 2023 |
| Lenovo        | Legion Pro 5 16IRX8 82WK    | Notebook    | [20394838bd](https://linux-hardware.org/?probe=20394838bd) | Nov 11, 2023 |
| Gateway       | TBGM01                      | Desktop     | [3ca4695541](https://linux-hardware.org/?probe=3ca4695541) | Nov 07, 2023 |
| Toshiba       | Satellite L50-A-1DL         | Notebook    | [e7b5bfa0b4](https://linux-hardware.org/?probe=e7b5bfa0b4) | Nov 06, 2023 |
| Unknown       | Unknown                     | Notebook    | [2c2d291f54](https://linux-hardware.org/?probe=2c2d291f54) | Nov 05, 2023 |
| Dell          | 0V8WGR A00                  | Desktop     | [9b13411bc8](https://linux-hardware.org/?probe=9b13411bc8) | Nov 05, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [4ce8997d5a](https://linux-hardware.org/?probe=4ce8997d5a) | Nov 05, 2023 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [98e32e98bf](https://linux-hardware.org/?probe=98e32e98bf) | Oct 31, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [be57c0ce22](https://linux-hardware.org/?probe=be57c0ce22) | Oct 29, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [3c959b9af8](https://linux-hardware.org/?probe=3c959b9af8) | Oct 25, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [e3540cf969](https://linux-hardware.org/?probe=e3540cf969) | Oct 23, 2023 |
| Google        | Reef                        | Notebook    | [819e00dd76](https://linux-hardware.org/?probe=819e00dd76) | Oct 22, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [4e2a3f7606](https://linux-hardware.org/?probe=4e2a3f7606) | Oct 15, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [94d47a3e29](https://linux-hardware.org/?probe=94d47a3e29) | Oct 15, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [fb0b3ea9e7](https://linux-hardware.org/?probe=fb0b3ea9e7) | Oct 12, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [0755ce07a3](https://linux-hardware.org/?probe=0755ce07a3) | Oct 08, 2023 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [35081bd0e8](https://linux-hardware.org/?probe=35081bd0e8) | Oct 08, 2023 |
| Lenovo        | Legion 5 15IAH7H 82RB       | Notebook    | [30b0879baa](https://linux-hardware.org/?probe=30b0879baa) | Oct 07, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [ee251b10d4](https://linux-hardware.org/?probe=ee251b10d4) | Oct 07, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [442ef4b7be](https://linux-hardware.org/?probe=442ef4b7be) | Oct 04, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [3185dde146](https://linux-hardware.org/?probe=3185dde146) | Oct 04, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [a13621c5d3](https://linux-hardware.org/?probe=a13621c5d3) | Oct 04, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [144cbc70d0](https://linux-hardware.org/?probe=144cbc70d0) | Oct 03, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [5ef983c393](https://linux-hardware.org/?probe=5ef983c393) | Oct 01, 2023 |
| HP            | 8619                        | Desktop     | [d631850d2f](https://linux-hardware.org/?probe=d631850d2f) | Sep 28, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [34e34036d7](https://linux-hardware.org/?probe=34e34036d7) | Sep 27, 2023 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [167d2e893e](https://linux-hardware.org/?probe=167d2e893e) | Sep 27, 2023 |
| HP            | 8714                        | Desktop     | [235d6bd11b](https://linux-hardware.org/?probe=235d6bd11b) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [37ecdee3d3](https://linux-hardware.org/?probe=37ecdee3d3) | Sep 24, 2023 |
| Lenovo        | IdeaPad 3 15IAU7 82RK       | Notebook    | [ecc0e92fb0](https://linux-hardware.org/?probe=ecc0e92fb0) | Sep 24, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [e10f21c5c5](https://linux-hardware.org/?probe=e10f21c5c5) | Sep 22, 2023 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [648ac87a81](https://linux-hardware.org/?probe=648ac87a81) | Sep 21, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [10d32d6284](https://linux-hardware.org/?probe=10d32d6284) | Sep 17, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [faf0bfe427](https://linux-hardware.org/?probe=faf0bfe427) | Sep 17, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [faa9a71ce1](https://linux-hardware.org/?probe=faa9a71ce1) | Sep 17, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [2f99528572](https://linux-hardware.org/?probe=2f99528572) | Sep 16, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [6495df6735](https://linux-hardware.org/?probe=6495df6735) | Sep 15, 2023 |
| Acer          | Aspire C20-820              | All in one  | [1b2bdeafca](https://linux-hardware.org/?probe=1b2bdeafca) | Sep 11, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [e59c5b4fda](https://linux-hardware.org/?probe=e59c5b4fda) | Sep 10, 2023 |
| ASUSTek       | S550CB                      | Notebook    | [dbf2770e09](https://linux-hardware.org/?probe=dbf2770e09) | Sep 10, 2023 |
| Toshiba       | Satellite L775D             | Notebook    | [681dab0969](https://linux-hardware.org/?probe=681dab0969) | Sep 09, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [694ffed41f](https://linux-hardware.org/?probe=694ffed41f) | Sep 06, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [039aa353eb](https://linux-hardware.org/?probe=039aa353eb) | Sep 06, 2023 |
| Dell          | Latitude 7280               | Notebook    | [3cf6ec76b5](https://linux-hardware.org/?probe=3cf6ec76b5) | Sep 05, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [ec33c11aa1](https://linux-hardware.org/?probe=ec33c11aa1) | Aug 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [101a39c37a](https://linux-hardware.org/?probe=101a39c37a) | Aug 28, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [da3ab01b3a](https://linux-hardware.org/?probe=da3ab01b3a) | Aug 25, 2023 |
| IP3 Tech      | PCBA-IP3_ACB20015           | Mini pc     | [57f24399d5](https://linux-hardware.org/?probe=57f24399d5) | Aug 22, 2023 |
| IP3 Tech      | PCBA-IP3_ACB20015           | Mini pc     | [a7c7baada2](https://linux-hardware.org/?probe=a7c7baada2) | Aug 22, 2023 |
| IP3 Tech      | PCBA-IP3_ACB20015           | Mini pc     | [8b42955659](https://linux-hardware.org/?probe=8b42955659) | Aug 21, 2023 |
| MSI           | Katana 15 B13VGK            | Notebook    | [e92e058288](https://linux-hardware.org/?probe=e92e058288) | Aug 20, 2023 |
| Pegatron      | 2A94h                       | Desktop     | [e9816ab65b](https://linux-hardware.org/?probe=e9816ab65b) | Aug 19, 2023 |
| MSI           | 3666h                       | Desktop     | [d3f51a2bf0](https://linux-hardware.org/?probe=d3f51a2bf0) | Aug 15, 2023 |
| Dell          | 0100P6 A01                  | Desktop     | [2cf993001c](https://linux-hardware.org/?probe=2cf993001c) | Aug 13, 2023 |
| Lenovo        | IdeaPad Slim 1-11AST-05 ... | Notebook    | [30c7051967](https://linux-hardware.org/?probe=30c7051967) | Aug 11, 2023 |
| MSI           | Summit E14Evo A12M          | Notebook    | [b83d821361](https://linux-hardware.org/?probe=b83d821361) | Aug 11, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3e66a1f712](https://linux-hardware.org/?probe=3e66a1f712) | Aug 10, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [b76b1bf00a](https://linux-hardware.org/?probe=b76b1bf00a) | Aug 08, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [63665fca24](https://linux-hardware.org/?probe=63665fca24) | Aug 08, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [324819c88d](https://linux-hardware.org/?probe=324819c88d) | Aug 08, 2023 |
| Acer          | Aspire 4810T                | Notebook    | [aaf9cdefc0](https://linux-hardware.org/?probe=aaf9cdefc0) | Aug 07, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [d3999a626a](https://linux-hardware.org/?probe=d3999a626a) | Aug 07, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [1b3c788790](https://linux-hardware.org/?probe=1b3c788790) | Aug 06, 2023 |
| Dell          | Precision 7730              | Notebook    | [1ed1a60e50](https://linux-hardware.org/?probe=1ed1a60e50) | Aug 06, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [48ec623298](https://linux-hardware.org/?probe=48ec623298) | Aug 06, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [7979e7ce95](https://linux-hardware.org/?probe=7979e7ce95) | Aug 05, 2023 |
| Microsoft     | Surface Laptop 4            | Tablet      | [70c6936cfc](https://linux-hardware.org/?probe=70c6936cfc) | Aug 04, 2023 |
| Dell          | 0RY007                      | Desktop     | [8317045335](https://linux-hardware.org/?probe=8317045335) | Aug 01, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [ad4e7cf4ad](https://linux-hardware.org/?probe=ad4e7cf4ad) | Aug 01, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [36d9df3244](https://linux-hardware.org/?probe=36d9df3244) | Jul 31, 2023 |
| MSI           | Katana 17 B13VFK            | Notebook    | [8bc597da6e](https://linux-hardware.org/?probe=8bc597da6e) | Jul 29, 2023 |
| MSI           | Katana GF66 11UE            | Notebook    | [78e12df29a](https://linux-hardware.org/?probe=78e12df29a) | Jul 28, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [cea811cc5f](https://linux-hardware.org/?probe=cea811cc5f) | Jul 25, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [d047b35269](https://linux-hardware.org/?probe=d047b35269) | Jul 25, 2023 |
| HP            | ProBook 650 G2              | Notebook    | [affdd0a6f9](https://linux-hardware.org/?probe=affdd0a6f9) | Jul 25, 2023 |
| Lenovo        | ThinkPad T480s 20L70028U... | Notebook    | [af539103c5](https://linux-hardware.org/?probe=af539103c5) | Jul 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [58882ecdfe](https://linux-hardware.org/?probe=58882ecdfe) | Jul 20, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8abec746f7](https://linux-hardware.org/?probe=8abec746f7) | Jul 19, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [3e6412c30b](https://linux-hardware.org/?probe=3e6412c30b) | Jul 19, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8e533f69a9](https://linux-hardware.org/?probe=8e533f69a9) | Jul 19, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [c4b019ee7f](https://linux-hardware.org/?probe=c4b019ee7f) | Jul 18, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [d7c21e7889](https://linux-hardware.org/?probe=d7c21e7889) | Jul 13, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [10d3da2824](https://linux-hardware.org/?probe=10d3da2824) | Jul 12, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [37bc760339](https://linux-hardware.org/?probe=37bc760339) | Jul 11, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [b5a021ae8a](https://linux-hardware.org/?probe=b5a021ae8a) | Jul 10, 2023 |
| Samsung       | 750XED                      | Notebook    | [412a36c3f1](https://linux-hardware.org/?probe=412a36c3f1) | Jul 08, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [70a6354074](https://linux-hardware.org/?probe=70a6354074) | Jul 05, 2023 |
| Dell          | Latitude 3410               | Notebook    | [da609df435](https://linux-hardware.org/?probe=da609df435) | Jul 03, 2023 |
| HP            | EliteBook 860 16 inch G9... | Notebook    | [4a4b49a909](https://linux-hardware.org/?probe=4a4b49a909) | Jul 03, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [b4d959d91f](https://linux-hardware.org/?probe=b4d959d91f) | Jul 02, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [12871de62d](https://linux-hardware.org/?probe=12871de62d) | Jun 30, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [ea4a5ccb1a](https://linux-hardware.org/?probe=ea4a5ccb1a) | Jun 29, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [a4b38b88cc](https://linux-hardware.org/?probe=a4b38b88cc) | Jun 27, 2023 |
| Lenovo        | ThinkPad P53 20QNS00X00     | Notebook    | [e28a0d43ed](https://linux-hardware.org/?probe=e28a0d43ed) | Jun 27, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [ee31bf4efe](https://linux-hardware.org/?probe=ee31bf4efe) | Jun 26, 2023 |
| Unknown       | Unknown                     | Notebook    | [9c8513ff31](https://linux-hardware.org/?probe=9c8513ff31) | Jun 25, 2023 |
| HONOR         | BMH-WCX9                    | Notebook    | [f40cb826de](https://linux-hardware.org/?probe=f40cb826de) | Jun 25, 2023 |
| Samsung       | 530XBB                      | Notebook    | [51007aebd3](https://linux-hardware.org/?probe=51007aebd3) | Jun 24, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [190d408bc2](https://linux-hardware.org/?probe=190d408bc2) | Jun 23, 2023 |
| ASUSTek       | Maximus V FORMULA           | Desktop     | [fa49028492](https://linux-hardware.org/?probe=fa49028492) | Jun 23, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [3055046330](https://linux-hardware.org/?probe=3055046330) | Jun 20, 2023 |
| Lenovo        | ThinkPad L490 20Q5001YMX    | Notebook    | [c04ebf8de3](https://linux-hardware.org/?probe=c04ebf8de3) | Jun 20, 2023 |
| HP            | EliteBook 850 G3            | Notebook    | [2102fc8523](https://linux-hardware.org/?probe=2102fc8523) | Jun 19, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [464db6c1df](https://linux-hardware.org/?probe=464db6c1df) | Jun 18, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [11161fa30c](https://linux-hardware.org/?probe=11161fa30c) | Jun 18, 2023 |
| Lenovo        | ThinkPad L520 78595GJ       | Notebook    | [52faa96ad0](https://linux-hardware.org/?probe=52faa96ad0) | Jun 17, 2023 |
| Dell          | Latitude 7430               | Notebook    | [e25ec87b40](https://linux-hardware.org/?probe=e25ec87b40) | Jun 17, 2023 |
| Dell          | Latitude 7430               | Notebook    | [35c6e2b80e](https://linux-hardware.org/?probe=35c6e2b80e) | Jun 17, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [20a66afa75](https://linux-hardware.org/?probe=20a66afa75) | Jun 14, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [3d8862fe69](https://linux-hardware.org/?probe=3d8862fe69) | Jun 13, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [dbf4a1d57c](https://linux-hardware.org/?probe=dbf4a1d57c) | Jun 12, 2023 |
| HP            | 339A                        | Desktop     | [d1fa07d03f](https://linux-hardware.org/?probe=d1fa07d03f) | Jun 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [3de2e4c6f9](https://linux-hardware.org/?probe=3de2e4c6f9) | Jun 10, 2023 |
| Onda TLC      | ONDA Oliver                 | Notebook    | [80a06d821b](https://linux-hardware.org/?probe=80a06d821b) | Jun 09, 2023 |
| HP            | ENVY m6 Notebook            | Notebook    | [f72410be27](https://linux-hardware.org/?probe=f72410be27) | Jun 08, 2023 |
| HP            | 339A                        | Desktop     | [f2147ed11b](https://linux-hardware.org/?probe=f2147ed11b) | Jun 05, 2023 |
| HP            | 1495                        | Desktop     | [32cfd162b8](https://linux-hardware.org/?probe=32cfd162b8) | Jun 05, 2023 |
| HP            | 1495                        | Desktop     | [f6c9f689ec](https://linux-hardware.org/?probe=f6c9f689ec) | Jun 05, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [f0e52437a7](https://linux-hardware.org/?probe=f0e52437a7) | Jun 04, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [c359b173f6](https://linux-hardware.org/?probe=c359b173f6) | Jun 04, 2023 |
| Dell          | XPS 13 9370                 | Notebook    | [a0efed7ee2](https://linux-hardware.org/?probe=a0efed7ee2) | Jun 04, 2023 |
| ASUSTek       | P8Z68-V                     | Desktop     | [59e64db8de](https://linux-hardware.org/?probe=59e64db8de) | Jun 02, 2023 |
| Acer          | Nitro AN515-42              | Notebook    | [0acaadb3d1](https://linux-hardware.org/?probe=0acaadb3d1) | Jun 01, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [743741a477](https://linux-hardware.org/?probe=743741a477) | May 31, 2023 |
| HP            | Laptop 15s-fq1xxx           | Notebook    | [4c7348e8b3](https://linux-hardware.org/?probe=4c7348e8b3) | May 31, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [15b23b6779](https://linux-hardware.org/?probe=15b23b6779) | May 30, 2023 |
| Lenovo        | ThinkPad X230 2325UYW       | Notebook    | [c2165f9183](https://linux-hardware.org/?probe=c2165f9183) | May 29, 2023 |
| Gigabyte      | H61M-HD2                    | Desktop     | [7c57f43d4a](https://linux-hardware.org/?probe=7c57f43d4a) | May 29, 2023 |
| ASUSTek       | ROG Strix G513QR_G513QR     | Notebook    | [76a373f9dd](https://linux-hardware.org/?probe=76a373f9dd) | May 26, 2023 |
| Dell          | Latitude 7370               | Notebook    | [4c3bfe7a9d](https://linux-hardware.org/?probe=4c3bfe7a9d) | May 26, 2023 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [922428b203](https://linux-hardware.org/?probe=922428b203) | May 25, 2023 |
| Dell          | Latitude 7280               | Notebook    | [c9a41b2795](https://linux-hardware.org/?probe=c9a41b2795) | May 24, 2023 |
| Dell          | Latitude 7280               | Notebook    | [215bef2144](https://linux-hardware.org/?probe=215bef2144) | May 23, 2023 |
| Gigabyte      | B85M-DS3H-A                 | Desktop     | [d2ddb8221f](https://linux-hardware.org/?probe=d2ddb8221f) | May 23, 2023 |
| Gigabyte      | Z97X-UD3H-CF                | Desktop     | [719fbbd5a5](https://linux-hardware.org/?probe=719fbbd5a5) | May 23, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [7a302f637c](https://linux-hardware.org/?probe=7a302f637c) | May 22, 2023 |
| ASUSTek       | X551MA                      | Notebook    | [d0466f101a](https://linux-hardware.org/?probe=d0466f101a) | May 22, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [64b9ba417c](https://linux-hardware.org/?probe=64b9ba417c) | May 19, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [5c07806ab1](https://linux-hardware.org/?probe=5c07806ab1) | May 19, 2023 |
| HP            | ProBook 4540s               | Notebook    | [1ea4f5cce0](https://linux-hardware.org/?probe=1ea4f5cce0) | May 18, 2023 |
| HP            | EliteBook 8760w             | Notebook    | [4b60a3d942](https://linux-hardware.org/?probe=4b60a3d942) | May 15, 2023 |
| Lenovo        | ThinkPad E14 20RA0059VA     | Notebook    | [72280fb1c5](https://linux-hardware.org/?probe=72280fb1c5) | May 14, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [689db5f7b4](https://linux-hardware.org/?probe=689db5f7b4) | May 14, 2023 |
| Dell          | Latitude 7370               | Notebook    | [78654593c7](https://linux-hardware.org/?probe=78654593c7) | May 10, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [c2392e1f40](https://linux-hardware.org/?probe=c2392e1f40) | May 10, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [4dc1934f7b](https://linux-hardware.org/?probe=4dc1934f7b) | May 09, 2023 |
| Dell          | Latitude 7370               | Notebook    | [4ea44288b5](https://linux-hardware.org/?probe=4ea44288b5) | May 08, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [4ad69aea88](https://linux-hardware.org/?probe=4ad69aea88) | May 05, 2023 |
| Dell          | Precision 7720              | Notebook    | [b6c3392263](https://linux-hardware.org/?probe=b6c3392263) | May 05, 2023 |
| HP            | Notebook                    | Notebook    | [a34031954a](https://linux-hardware.org/?probe=a34031954a) | May 05, 2023 |
| ASUSTek       | K42Jc                       | Notebook    | [ba4b9c97f9](https://linux-hardware.org/?probe=ba4b9c97f9) | May 05, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [e9c446ce66](https://linux-hardware.org/?probe=e9c446ce66) | May 03, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [4fbbf7e453](https://linux-hardware.org/?probe=4fbbf7e453) | May 02, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | Notebook    | [cfe1d4ffab](https://linux-hardware.org/?probe=cfe1d4ffab) | May 02, 2023 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [f3b5a181df](https://linux-hardware.org/?probe=f3b5a181df) | May 02, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [85df1ec917](https://linux-hardware.org/?probe=85df1ec917) | Apr 29, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [9d6905e35d](https://linux-hardware.org/?probe=9d6905e35d) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [7ba933a829](https://linux-hardware.org/?probe=7ba933a829) | Apr 28, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [d2ed10f8b1](https://linux-hardware.org/?probe=d2ed10f8b1) | Apr 27, 2023 |
| Dell          | Vostro 1550                 | Notebook    | [d7951530f0](https://linux-hardware.org/?probe=d7951530f0) | Apr 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [ac831756d0](https://linux-hardware.org/?probe=ac831756d0) | Apr 26, 2023 |
| Dell          | Inspiron 14 5410            | Notebook    | [89017780fa](https://linux-hardware.org/?probe=89017780fa) | Apr 25, 2023 |
| HP            | ProBook 4540s               | Notebook    | [db866a1036](https://linux-hardware.org/?probe=db866a1036) | Apr 24, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [b4861cf35c](https://linux-hardware.org/?probe=b4861cf35c) | Apr 23, 2023 |
| Lenovo        | ThinkPad L15 Gen 3 21C3C... | Notebook    | [b37a4411c5](https://linux-hardware.org/?probe=b37a4411c5) | Apr 22, 2023 |
| Apple         | Mac-63001698E7A34814 iMa... | All in one  | [0f3f45f8e9](https://linux-hardware.org/?probe=0f3f45f8e9) | Apr 13, 2023 |
| Lenovo        | ThinkPad E460 20ETA05KAU    | Notebook    | [a8090f51bc](https://linux-hardware.org/?probe=a8090f51bc) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [fc68164465](https://linux-hardware.org/?probe=fc68164465) | Apr 08, 2023 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [1dcab8aee7](https://linux-hardware.org/?probe=1dcab8aee7) | Apr 08, 2023 |
| Gigabyte      | AORUS 15P KD                | Notebook    | [0b53411753](https://linux-hardware.org/?probe=0b53411753) | Apr 07, 2023 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [04c16989b3](https://linux-hardware.org/?probe=04c16989b3) | Apr 06, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [b307524661](https://linux-hardware.org/?probe=b307524661) | Apr 06, 2023 |
| Acer          | Extensa 215-54              | Notebook    | [60a8537172](https://linux-hardware.org/?probe=60a8537172) | Apr 05, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [2f61bfa5a5](https://linux-hardware.org/?probe=2f61bfa5a5) | Apr 04, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [1e81e330e1](https://linux-hardware.org/?probe=1e81e330e1) | Apr 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7a61d16701](https://linux-hardware.org/?probe=7a61d16701) | Apr 04, 2023 |
| MSI           | 760GM-P33                   | Desktop     | [4145a32920](https://linux-hardware.org/?probe=4145a32920) | Apr 03, 2023 |
| Google        | Lillipup                    | Notebook    | [09292890c9](https://linux-hardware.org/?probe=09292890c9) | Mar 30, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [9edda5f374](https://linux-hardware.org/?probe=9edda5f374) | Mar 28, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [c25f99afed](https://linux-hardware.org/?probe=c25f99afed) | Mar 28, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [0180776452](https://linux-hardware.org/?probe=0180776452) | Mar 26, 2023 |
| ASUSTek       | X510UAR                     | Notebook    | [728805785d](https://linux-hardware.org/?probe=728805785d) | Mar 25, 2023 |
| HP            | ZBook Firefly 14 inch G9... | Notebook    | [35030027f5](https://linux-hardware.org/?probe=35030027f5) | Mar 21, 2023 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | Notebook    | [0927eb4ba9](https://linux-hardware.org/?probe=0927eb4ba9) | Mar 17, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [8307fbf791](https://linux-hardware.org/?probe=8307fbf791) | Mar 14, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [6752797fe9](https://linux-hardware.org/?probe=6752797fe9) | Mar 14, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [2e0019e450](https://linux-hardware.org/?probe=2e0019e450) | Mar 14, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [b5d8bdc57d](https://linux-hardware.org/?probe=b5d8bdc57d) | Mar 12, 2023 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [4525fa2931](https://linux-hardware.org/?probe=4525fa2931) | Mar 12, 2023 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [47f7858a60](https://linux-hardware.org/?probe=47f7858a60) | Mar 07, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [143b06f2d6](https://linux-hardware.org/?probe=143b06f2d6) | Mar 06, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [fe287f85c8](https://linux-hardware.org/?probe=fe287f85c8) | Mar 05, 2023 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [d3bb7ff642](https://linux-hardware.org/?probe=d3bb7ff642) | Mar 05, 2023 |
| HP            | Pavilion 15                 | Notebook    | [3a06e7e211](https://linux-hardware.org/?probe=3a06e7e211) | Mar 05, 2023 |
| ASRock        | B560M-C                     | Desktop     | [a93d64aa2c](https://linux-hardware.org/?probe=a93d64aa2c) | Feb 28, 2023 |
| ASRock        | B560M-C                     | Desktop     | [cbbd0a63d4](https://linux-hardware.org/?probe=cbbd0a63d4) | Feb 28, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [418b5dd7ff](https://linux-hardware.org/?probe=418b5dd7ff) | Feb 27, 2023 |
| Pegatron      | 2ACB                        | Desktop     | [13355a7d07](https://linux-hardware.org/?probe=13355a7d07) | Feb 26, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21ED0... | Notebook    | [85bc55a850](https://linux-hardware.org/?probe=85bc55a850) | Feb 26, 2023 |
| Lenovo        | ThinkPad X230 23253Z5       | Notebook    | [1237b75ae4](https://linux-hardware.org/?probe=1237b75ae4) | Feb 24, 2023 |
| Dell          | 0C1R19 A02                  | Desktop     | [42ff2c0844](https://linux-hardware.org/?probe=42ff2c0844) | Feb 22, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [fd899aea79](https://linux-hardware.org/?probe=fd899aea79) | Feb 22, 2023 |
| Alienware     | 17 R5                       | Notebook    | [1d234f85b4](https://linux-hardware.org/?probe=1d234f85b4) | Feb 22, 2023 |
| Alienware     | 17 R5                       | Notebook    | [5b6b8eee92](https://linux-hardware.org/?probe=5b6b8eee92) | Feb 22, 2023 |
| ASRock        | B560M-C                     | Desktop     | [0641c704e9](https://linux-hardware.org/?probe=0641c704e9) | Feb 20, 2023 |
| Biostar       | B450MH                      | Desktop     | [963e90387d](https://linux-hardware.org/?probe=963e90387d) | Feb 17, 2023 |
| Google        | Robo360                     | Notebook    | [e7c85b2410](https://linux-hardware.org/?probe=e7c85b2410) | Feb 09, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [bfb29a2d13](https://linux-hardware.org/?probe=bfb29a2d13) | Feb 04, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [725e7248ee](https://linux-hardware.org/?probe=725e7248ee) | Feb 04, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [9f67df0760](https://linux-hardware.org/?probe=9f67df0760) | Feb 03, 2023 |
| ASRock        | Z87M Extreme4               | Desktop     | [8821f128c8](https://linux-hardware.org/?probe=8821f128c8) | Feb 03, 2023 |
| Lenovo        | ThinkPad T460 20FMS2J300    | Notebook    | [741b347456](https://linux-hardware.org/?probe=741b347456) | Feb 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [d800b8a4b9](https://linux-hardware.org/?probe=d800b8a4b9) | Jan 30, 2023 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [15644c39de](https://linux-hardware.org/?probe=15644c39de) | Jan 25, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [91e33f05ed](https://linux-hardware.org/?probe=91e33f05ed) | Jan 24, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [eb10e25652](https://linux-hardware.org/?probe=eb10e25652) | Jan 23, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [6552c7b8b3](https://linux-hardware.org/?probe=6552c7b8b3) | Jan 22, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [543136f475](https://linux-hardware.org/?probe=543136f475) | Jan 20, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [64164ef7df](https://linux-hardware.org/?probe=64164ef7df) | Jan 20, 2023 |
| Gigabyte      | GA-880GMA-USB3              | Desktop     | [46befb7112](https://linux-hardware.org/?probe=46befb7112) | Jan 20, 2023 |
| HP            | Laptop 15-dy1xxx            | Notebook    | [4b76c154f3](https://linux-hardware.org/?probe=4b76c154f3) | Jan 20, 2023 |
| Quanta        | TW9/SW9                     | Notebook    | [4a196739f5](https://linux-hardware.org/?probe=4a196739f5) | Jan 18, 2023 |
| Lenovo        | ThinkPad E590 20NB0003AD    | Notebook    | [fe3de007e1](https://linux-hardware.org/?probe=fe3de007e1) | Jan 16, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [493f0e9608](https://linux-hardware.org/?probe=493f0e9608) | Jan 13, 2023 |
| Intel Clie... | LAPBC510                    | Notebook    | [ac0b81bf2e](https://linux-hardware.org/?probe=ac0b81bf2e) | Jan 13, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [d8ab62070c](https://linux-hardware.org/?probe=d8ab62070c) | Jan 11, 2023 |
| Dell          | Latitude E6520              | Notebook    | [96679022de](https://linux-hardware.org/?probe=96679022de) | Jan 06, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [9496d56fab](https://linux-hardware.org/?probe=9496d56fab) | Jan 04, 2023 |
| Acer          | Aspire A315-58              | Notebook    | [3629e42dc4](https://linux-hardware.org/?probe=3629e42dc4) | Jan 04, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [0df48a29e1](https://linux-hardware.org/?probe=0df48a29e1) | Jan 03, 2023 |
| Unknown       | Unknown                     | Notebook    | [1e55cad727](https://linux-hardware.org/?probe=1e55cad727) | Dec 25, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [aaac67afbe](https://linux-hardware.org/?probe=aaac67afbe) | Dec 23, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [5bbf457036](https://linux-hardware.org/?probe=5bbf457036) | Dec 22, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [be01b942ed](https://linux-hardware.org/?probe=be01b942ed) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [4fc06d2c89](https://linux-hardware.org/?probe=4fc06d2c89) | Dec 22, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [3c22afd21b](https://linux-hardware.org/?probe=3c22afd21b) | Dec 22, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [d45689035c](https://linux-hardware.org/?probe=d45689035c) | Dec 19, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [7895ac3dc1](https://linux-hardware.org/?probe=7895ac3dc1) | Dec 17, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [30f6db8749](https://linux-hardware.org/?probe=30f6db8749) | Dec 17, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [a17338c77a](https://linux-hardware.org/?probe=a17338c77a) | Dec 17, 2022 |
| HP            | 3397                        | Desktop     | [33ba62be32](https://linux-hardware.org/?probe=33ba62be32) | Dec 10, 2022 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [0e7586e771](https://linux-hardware.org/?probe=0e7586e771) | Dec 06, 2022 |
| Dell          | G3 3500                     | Notebook    | [5b23644904](https://linux-hardware.org/?probe=5b23644904) | Dec 05, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [90db11aeba](https://linux-hardware.org/?probe=90db11aeba) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [6c74973e99](https://linux-hardware.org/?probe=6c74973e99) | Dec 04, 2022 |
| Intel Clie... | LAPBC510                    | Notebook    | [e903f5edea](https://linux-hardware.org/?probe=e903f5edea) | Dec 02, 2022 |
| MSI           | GT60                        | Notebook    | [07557bed1b](https://linux-hardware.org/?probe=07557bed1b) | Nov 29, 2022 |
| Quanta        | TW9/SW9                     | Notebook    | [5bfeb648aa](https://linux-hardware.org/?probe=5bfeb648aa) | Nov 28, 2022 |
| Quanta        | TW9/SW9                     | Notebook    | [ba75780c3e](https://linux-hardware.org/?probe=ba75780c3e) | Nov 28, 2022 |
| Intel Clie... | LAPBC510                    | Notebook    | [f58ff7b6fa](https://linux-hardware.org/?probe=f58ff7b6fa) | Nov 27, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [d57a12d93c](https://linux-hardware.org/?probe=d57a12d93c) | Nov 20, 2022 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [7928d11567](https://linux-hardware.org/?probe=7928d11567) | Nov 19, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [3050d57edc](https://linux-hardware.org/?probe=3050d57edc) | Nov 17, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [b152ccfb56](https://linux-hardware.org/?probe=b152ccfb56) | Nov 14, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [104fb805bd](https://linux-hardware.org/?probe=104fb805bd) | Nov 09, 2022 |
| Dell          | 0C1R19 A02                  | Desktop     | [514ae17aa9](https://linux-hardware.org/?probe=514ae17aa9) | Nov 06, 2022 |
| HP            | 89B5 A                      | Desktop     | [1b04604c98](https://linux-hardware.org/?probe=1b04604c98) | Nov 03, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [a65efa454e](https://linux-hardware.org/?probe=a65efa454e) | Nov 01, 2022 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [3380dfae20](https://linux-hardware.org/?probe=3380dfae20) | Nov 01, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [f141a6cddf](https://linux-hardware.org/?probe=f141a6cddf) | Oct 31, 2022 |
| HP            | Victus by Laptop 16-d1xx... | Notebook    | [b9890126af](https://linux-hardware.org/?probe=b9890126af) | Oct 31, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [9eec3492e9](https://linux-hardware.org/?probe=9eec3492e9) | Oct 30, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [c6a7aeb8ad](https://linux-hardware.org/?probe=c6a7aeb8ad) | Oct 30, 2022 |
| Dell          | Latitude 3350               | Notebook    | [e545da88bf](https://linux-hardware.org/?probe=e545da88bf) | Oct 28, 2022 |
| Apple         | Mac-F2218EA9                | All in one  | [5b16264bea](https://linux-hardware.org/?probe=5b16264bea) | Oct 28, 2022 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [afd2f21c66](https://linux-hardware.org/?probe=afd2f21c66) | Oct 26, 2022 |
| Acer          | Aspire ES1-111M             | Notebook    | [ebff9e2fa5](https://linux-hardware.org/?probe=ebff9e2fa5) | Oct 25, 2022 |
| Dell          | Latitude E5500              | Notebook    | [10cb5545fd](https://linux-hardware.org/?probe=10cb5545fd) | Oct 24, 2022 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [dd5c78f136](https://linux-hardware.org/?probe=dd5c78f136) | Oct 24, 2022 |
| Gigabyte      | Z97N-WIFI                   | Desktop     | [10d8d16b6c](https://linux-hardware.org/?probe=10d8d16b6c) | Oct 24, 2022 |
| Dell          | Inspiron 13-7378            | Notebook    | [fbd3c71f34](https://linux-hardware.org/?probe=fbd3c71f34) | Oct 23, 2022 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [7c046d1ba8](https://linux-hardware.org/?probe=7c046d1ba8) | Oct 23, 2022 |
| Gigabyte      | M61SME-S2                   | Desktop     | [6595a0b531](https://linux-hardware.org/?probe=6595a0b531) | Oct 19, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | Notebook    | [6a85eb0ff4](https://linux-hardware.org/?probe=6a85eb0ff4) | Oct 14, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [d84fc5ce81](https://linux-hardware.org/?probe=d84fc5ce81) | Oct 13, 2022 |
| ASUSTek       | P6X58D-E                    | Desktop     | [2a896ec4f6](https://linux-hardware.org/?probe=2a896ec4f6) | Oct 13, 2022 |
| Clevo         | W25xHPx                     | Notebook    | [04196b2306](https://linux-hardware.org/?probe=04196b2306) | Oct 13, 2022 |
| Irbis         | NB121                       | Notebook    | [04f312f46b](https://linux-hardware.org/?probe=04f312f46b) | Oct 13, 2022 |
| Irbis         | NB121                       | Notebook    | [ff99468633](https://linux-hardware.org/?probe=ff99468633) | Oct 13, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [7ba818df9e](https://linux-hardware.org/?probe=7ba818df9e) | Oct 11, 2022 |
| Alienware     | m15 R7                      | Notebook    | [79aa2b2dd4](https://linux-hardware.org/?probe=79aa2b2dd4) | Oct 10, 2022 |
| Lenovo        | LEGIONC7 82EH               | Notebook    | [880c4773fd](https://linux-hardware.org/?probe=880c4773fd) | Oct 06, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [f02e3f9e3b](https://linux-hardware.org/?probe=f02e3f9e3b) | Oct 04, 2022 |
| Lenovo        | ThinkPad E570 20H5009MUS    | Notebook    | [5b3df02ed5](https://linux-hardware.org/?probe=5b3df02ed5) | Oct 03, 2022 |
| HP            | Unknown                     | Notebook    | [0a6433c4fe](https://linux-hardware.org/?probe=0a6433c4fe) | Oct 03, 2022 |
| Lenovo        | ThinkPad E570 20H5009MUS    | Notebook    | [70451644fc](https://linux-hardware.org/?probe=70451644fc) | Oct 03, 2022 |
| BANGHO        | GAMER GM-X 15s              | Notebook    | [d3e2d5452a](https://linux-hardware.org/?probe=d3e2d5452a) | Oct 03, 2022 |
| Gigabyte      | H110M-H DDR3-CF             | Desktop     | [8169fe8dbd](https://linux-hardware.org/?probe=8169fe8dbd) | Oct 01, 2022 |
| HP            | Presario CQ58               | Notebook    | [4bb50cd19d](https://linux-hardware.org/?probe=4bb50cd19d) | Sep 28, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [7ad1831ce9](https://linux-hardware.org/?probe=7ad1831ce9) | Sep 27, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [9616464154](https://linux-hardware.org/?probe=9616464154) | Sep 26, 2022 |
| Dell          | Latitude 3350               | Notebook    | [62c380dcd0](https://linux-hardware.org/?probe=62c380dcd0) | Sep 22, 2022 |
| MSI           | Katana GF66 12UD            | Notebook    | [c0c6c57498](https://linux-hardware.org/?probe=c0c6c57498) | Sep 17, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [5dc824a596](https://linux-hardware.org/?probe=5dc824a596) | Sep 16, 2022 |
| Toshiba       | Satellite C855D             | Notebook    | [bae94a45be](https://linux-hardware.org/?probe=bae94a45be) | Sep 13, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [f8de7730b6](https://linux-hardware.org/?probe=f8de7730b6) | Sep 11, 2022 |
| Dell          | Inspiron 14 5410            | Notebook    | [315af016c7](https://linux-hardware.org/?probe=315af016c7) | Sep 09, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d4e798ff22](https://linux-hardware.org/?probe=d4e798ff22) | Sep 07, 2022 |
| Dell          | Latitude E6400              | Notebook    | [1de889aa64](https://linux-hardware.org/?probe=1de889aa64) | Sep 05, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [b50b1adb0f](https://linux-hardware.org/?probe=b50b1adb0f) | Sep 01, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1d04855f84](https://linux-hardware.org/?probe=1d04855f84) | Aug 29, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [5739f0b1a0](https://linux-hardware.org/?probe=5739f0b1a0) | Aug 28, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [7439a7400d](https://linux-hardware.org/?probe=7439a7400d) | Aug 27, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [fa26302bd8](https://linux-hardware.org/?probe=fa26302bd8) | Aug 27, 2022 |
| Gigabyte      | H61M-S2PT                   | Desktop     | [b7e6228017](https://linux-hardware.org/?probe=b7e6228017) | Aug 22, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [b61f6861a6](https://linux-hardware.org/?probe=b61f6861a6) | Aug 21, 2022 |
| Standard      | Unknown                     | Notebook    | [782f229d6c](https://linux-hardware.org/?probe=782f229d6c) | Aug 17, 2022 |
| Panasonic     | CF-31JBGNNDM                | Notebook    | [008621e9e0](https://linux-hardware.org/?probe=008621e9e0) | Aug 14, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | Notebook    | [437387fdc3](https://linux-hardware.org/?probe=437387fdc3) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [47608d95ea](https://linux-hardware.org/?probe=47608d95ea) | Aug 10, 2022 |
| Lenovo        | ThinkPad X230 Tablet 343... | Notebook    | [0bd14e553d](https://linux-hardware.org/?probe=0bd14e553d) | Aug 10, 2022 |
| Lenovo        | ThinkPad T420 4180MNU       | Notebook    | [dae7cc7b69](https://linux-hardware.org/?probe=dae7cc7b69) | Aug 08, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [1a13c37dce](https://linux-hardware.org/?probe=1a13c37dce) | Aug 08, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [a7e9a050ea](https://linux-hardware.org/?probe=a7e9a050ea) | Aug 02, 2022 |
| HP            | EliteBook 850 G6            | Notebook    | [1dca756b58](https://linux-hardware.org/?probe=1dca756b58) | Jul 31, 2022 |
| Dell          | Latitude E6420              | Notebook    | [a6b2ee6088](https://linux-hardware.org/?probe=a6b2ee6088) | Jul 30, 2022 |
| Gateway       | SX2855                      | Desktop     | [a896e3b0f7](https://linux-hardware.org/?probe=a896e3b0f7) | Jul 30, 2022 |
| HP            | 250 G2                      | Notebook    | [5650fd3dd6](https://linux-hardware.org/?probe=5650fd3dd6) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [99fd83f85d](https://linux-hardware.org/?probe=99fd83f85d) | Jul 28, 2022 |
| Fujitsu       | LIFEBOOK AH532/G21          | Notebook    | [e64903db3d](https://linux-hardware.org/?probe=e64903db3d) | Jul 28, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [26be63e8a0](https://linux-hardware.org/?probe=26be63e8a0) | Jul 25, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [0bacf44374](https://linux-hardware.org/?probe=0bacf44374) | Jul 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [007eeacf86](https://linux-hardware.org/?probe=007eeacf86) | Jul 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8ce974e537](https://linux-hardware.org/?probe=8ce974e537) | Jul 23, 2022 |
| Sony          | VPCSB1C5E                   | Notebook    | [184e5b179e](https://linux-hardware.org/?probe=184e5b179e) | Jul 23, 2022 |
| Acer          | Nitro AN515-57              | Notebook    | [4d3cf557ba](https://linux-hardware.org/?probe=4d3cf557ba) | Jul 23, 2022 |
| Lenovo        | Z40-70 80E6                 | Notebook    | [e77b84e593](https://linux-hardware.org/?probe=e77b84e593) | Jul 22, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [8337c958e2](https://linux-hardware.org/?probe=8337c958e2) | Jul 22, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [90cf247d2d](https://linux-hardware.org/?probe=90cf247d2d) | Jul 20, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [2d31c995c8](https://linux-hardware.org/?probe=2d31c995c8) | Jul 19, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [9e9ca5b39a](https://linux-hardware.org/?probe=9e9ca5b39a) | Jul 19, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [0539efedb2](https://linux-hardware.org/?probe=0539efedb2) | Jul 18, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [2c55e11e85](https://linux-hardware.org/?probe=2c55e11e85) | Jul 18, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [0e0a7a2fbc](https://linux-hardware.org/?probe=0e0a7a2fbc) | Jul 16, 2022 |
| Unknown       | Unknown                     | Notebook    | [a7de2e1421](https://linux-hardware.org/?probe=a7de2e1421) | Jul 14, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [623281f994](https://linux-hardware.org/?probe=623281f994) | Jul 14, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [713bd9f4b0](https://linux-hardware.org/?probe=713bd9f4b0) | Jul 14, 2022 |
| Dell          | Inspiron MM061              | Notebook    | [49e71e9dc1](https://linux-hardware.org/?probe=49e71e9dc1) | Jul 13, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f6c3c6f86e](https://linux-hardware.org/?probe=f6c3c6f86e) | Jul 12, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [2ffa772ac9](https://linux-hardware.org/?probe=2ffa772ac9) | Jul 10, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c680f5f212](https://linux-hardware.org/?probe=c680f5f212) | Jul 10, 2022 |
| Apple         | MacBookPro5,1               | Notebook    | [fd79c5481a](https://linux-hardware.org/?probe=fd79c5481a) | Jul 09, 2022 |
| Lenovo        | ThinkPad L430 2465C32       | Notebook    | [f088c4ae11](https://linux-hardware.org/?probe=f088c4ae11) | Jul 09, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [48aa7eac9f](https://linux-hardware.org/?probe=48aa7eac9f) | Jul 09, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [8a96de43eb](https://linux-hardware.org/?probe=8a96de43eb) | Jul 08, 2022 |
| Acer          | Predator PT516-51s          | Notebook    | [9309da8b72](https://linux-hardware.org/?probe=9309da8b72) | Jul 05, 2022 |
| HP            | Laptop 15-bs2xx             | Notebook    | [fc35a0726c](https://linux-hardware.org/?probe=fc35a0726c) | Jul 03, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3ba50e78b9](https://linux-hardware.org/?probe=3ba50e78b9) | Jun 29, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [f33854651b](https://linux-hardware.org/?probe=f33854651b) | Jun 29, 2022 |
| Samsung       | 930QDB                      | Convertible | [e022aed2bc](https://linux-hardware.org/?probe=e022aed2bc) | Jun 28, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8b55dcfd2d](https://linux-hardware.org/?probe=8b55dcfd2d) | Jun 28, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [d1b8d3ff84](https://linux-hardware.org/?probe=d1b8d3ff84) | Jun 27, 2022 |
| HP            | Pavilion dv6                | Notebook    | [ff3ebff8ff](https://linux-hardware.org/?probe=ff3ebff8ff) | Jun 27, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6f3036d638](https://linux-hardware.org/?probe=6f3036d638) | Jun 26, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [6348a01f19](https://linux-hardware.org/?probe=6348a01f19) | Jun 23, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [86c0fc94e6](https://linux-hardware.org/?probe=86c0fc94e6) | Jun 23, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [656a452bc6](https://linux-hardware.org/?probe=656a452bc6) | Jun 21, 2022 |
| HP            | ProBook 440 G5              | Notebook    | [2969400046](https://linux-hardware.org/?probe=2969400046) | Jun 20, 2022 |
| Gigabyte      | H61M-USB3H                  | Desktop     | [6b9dcbd952](https://linux-hardware.org/?probe=6b9dcbd952) | Jun 20, 2022 |
| Toshiba       | Satellite-L845              | Notebook    | [d617282ee0](https://linux-hardware.org/?probe=d617282ee0) | Jun 18, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [4cafd85b65](https://linux-hardware.org/?probe=4cafd85b65) | Jun 15, 2022 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [2a3c65eda7](https://linux-hardware.org/?probe=2a3c65eda7) | Jun 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [e2efffbd81](https://linux-hardware.org/?probe=e2efffbd81) | Jun 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [c509b12c63](https://linux-hardware.org/?probe=c509b12c63) | Jun 07, 2022 |
| Unknown       | TB-4000                     | Desktop     | [c268e7111b](https://linux-hardware.org/?probe=c268e7111b) | Jun 07, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [fd246079ad](https://linux-hardware.org/?probe=fd246079ad) | Jun 04, 2022 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [7e3fc5fe06](https://linux-hardware.org/?probe=7e3fc5fe06) | Jun 02, 2022 |
| HP            | ENVY x360 m6 Convertible    | Convertible | [02ace99875](https://linux-hardware.org/?probe=02ace99875) | Jun 02, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [449fc46111](https://linux-hardware.org/?probe=449fc46111) | Jun 01, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [c4468417e9](https://linux-hardware.org/?probe=c4468417e9) | Jun 01, 2022 |
| Lenovo        | ThinkPad X230 2325N66       | Notebook    | [2061351dbc](https://linux-hardware.org/?probe=2061351dbc) | May 28, 2022 |
| Dell          | Latitude E6540              | Notebook    | [9171fd4d35](https://linux-hardware.org/?probe=9171fd4d35) | May 26, 2022 |
| Dell          | Latitude E6540              | Notebook    | [e7a078f1a1](https://linux-hardware.org/?probe=e7a078f1a1) | May 26, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [dbf37b46f6](https://linux-hardware.org/?probe=dbf37b46f6) | May 25, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [9fcb918138](https://linux-hardware.org/?probe=9fcb918138) | May 25, 2022 |
| Dell          | Latitude 5400               | Notebook    | [fdfa7356be](https://linux-hardware.org/?probe=fdfa7356be) | May 23, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 80X4     | Notebook    | [aa6aefb86a](https://linux-hardware.org/?probe=aa6aefb86a) | May 21, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [cb4959b996](https://linux-hardware.org/?probe=cb4959b996) | May 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fb7cb376e9](https://linux-hardware.org/?probe=fb7cb376e9) | May 21, 2022 |
| Dell          | Latitude E6410              | Notebook    | [b098a84988](https://linux-hardware.org/?probe=b098a84988) | May 20, 2022 |
| MSI           | G31M3-L V2                  | Desktop     | [29d45c64bb](https://linux-hardware.org/?probe=29d45c64bb) | May 11, 2022 |
| MSI           | GE62 6QE                    | Notebook    | [6a3161d4ee](https://linux-hardware.org/?probe=6a3161d4ee) | May 09, 2022 |
| Timi          | TM1613                      | Notebook    | [114752ffeb](https://linux-hardware.org/?probe=114752ffeb) | May 08, 2022 |
| Timi          | TM1613                      | Notebook    | [b714f7dbd8](https://linux-hardware.org/?probe=b714f7dbd8) | May 08, 2022 |
| HP            | 1495                        | Desktop     | [c845f7b657](https://linux-hardware.org/?probe=c845f7b657) | May 05, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [60a636868c](https://linux-hardware.org/?probe=60a636868c) | Apr 30, 2022 |
| Unknown       | TB-4000                     | Desktop     | [99911022e9](https://linux-hardware.org/?probe=99911022e9) | Apr 26, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [032acaf88c](https://linux-hardware.org/?probe=032acaf88c) | Apr 25, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [56d949b3bb](https://linux-hardware.org/?probe=56d949b3bb) | Apr 23, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [0ee15f97fd](https://linux-hardware.org/?probe=0ee15f97fd) | Apr 23, 2022 |
| Dell          | Inspiron 15 5510            | Notebook    | [73a8933099](https://linux-hardware.org/?probe=73a8933099) | Apr 22, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [4d911b0d94](https://linux-hardware.org/?probe=4d911b0d94) | Apr 22, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | Desktop     | [9c06485301](https://linux-hardware.org/?probe=9c06485301) | Apr 21, 2022 |
| HP            | 18E7                        | Desktop     | [1b6db66cc1](https://linux-hardware.org/?probe=1b6db66cc1) | Apr 19, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b68f986aaf](https://linux-hardware.org/?probe=b68f986aaf) | Apr 17, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [93306ff9ee](https://linux-hardware.org/?probe=93306ff9ee) | Apr 17, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [7e03ed9f70](https://linux-hardware.org/?probe=7e03ed9f70) | Apr 13, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [b9187e8521](https://linux-hardware.org/?probe=b9187e8521) | Apr 13, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [bdccad7bf9](https://linux-hardware.org/?probe=bdccad7bf9) | Apr 12, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [0832404b40](https://linux-hardware.org/?probe=0832404b40) | Apr 11, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [b1a322fa38](https://linux-hardware.org/?probe=b1a322fa38) | Apr 11, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [b3afe4ff08](https://linux-hardware.org/?probe=b3afe4ff08) | Apr 11, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [b670324e44](https://linux-hardware.org/?probe=b670324e44) | Apr 10, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [8cb4405c5f](https://linux-hardware.org/?probe=8cb4405c5f) | Apr 09, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [320ae25dbf](https://linux-hardware.org/?probe=320ae25dbf) | Apr 09, 2022 |
| Toshiba       | Satellite Click 2 L35W-B    | Notebook    | [f992f9305a](https://linux-hardware.org/?probe=f992f9305a) | Apr 07, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [e422a0e166](https://linux-hardware.org/?probe=e422a0e166) | Apr 05, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [b96e97fa2b](https://linux-hardware.org/?probe=b96e97fa2b) | Apr 04, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [401792c28e](https://linux-hardware.org/?probe=401792c28e) | Apr 01, 2022 |
| Alienware     | M14xR1                      | Notebook    | [f3ea3f497c](https://linux-hardware.org/?probe=f3ea3f497c) | Apr 01, 2022 |
| HP            | Notebook                    | Notebook    | [313ca81d16](https://linux-hardware.org/?probe=313ca81d16) | Mar 27, 2022 |
| ECS           | Nettle2                     | Desktop     | [4939d60e6d](https://linux-hardware.org/?probe=4939d60e6d) | Mar 27, 2022 |
| HP            | 18E7                        | Desktop     | [d8d1c3d468](https://linux-hardware.org/?probe=d8d1c3d468) | Mar 26, 2022 |
| ASUSTek       | X540SAA                     | Notebook    | [988b4570ed](https://linux-hardware.org/?probe=988b4570ed) | Mar 24, 2022 |
| Lenovo        | ThinkPad E15 20RD0086UE     | Notebook    | [f26a636b1b](https://linux-hardware.org/?probe=f26a636b1b) | Mar 24, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [72245fe662](https://linux-hardware.org/?probe=72245fe662) | Mar 22, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [85260f6ed1](https://linux-hardware.org/?probe=85260f6ed1) | Mar 20, 2022 |
| Lenovo        | SHARKBAY 31900058 STD       | Desktop     | [e849ec3916](https://linux-hardware.org/?probe=e849ec3916) | Mar 20, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [b0769dffdd](https://linux-hardware.org/?probe=b0769dffdd) | Mar 19, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2c1ca9145b](https://linux-hardware.org/?probe=2c1ca9145b) | Mar 18, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [167928d6e9](https://linux-hardware.org/?probe=167928d6e9) | Mar 17, 2022 |
| Wistron       | JIG31B3                     | Desktop     | [a360eaf501](https://linux-hardware.org/?probe=a360eaf501) | Mar 15, 2022 |
| ASUSTek       | H170M-E D3                  | Desktop     | [937c0097ca](https://linux-hardware.org/?probe=937c0097ca) | Mar 14, 2022 |
| Toshiba       | Satellite L775D             | Notebook    | [3d09dbe623](https://linux-hardware.org/?probe=3d09dbe623) | Mar 14, 2022 |
| Positivo      | Q232A                       | Notebook    | [87c79b8f05](https://linux-hardware.org/?probe=87c79b8f05) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [36d17e4fdb](https://linux-hardware.org/?probe=36d17e4fdb) | Mar 13, 2022 |
| ASUSTek       | F2A85-M                     | Desktop     | [453d0816b3](https://linux-hardware.org/?probe=453d0816b3) | Mar 13, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [dba57ee1b3](https://linux-hardware.org/?probe=dba57ee1b3) | Mar 12, 2022 |
| ASUSTek       | X75VC                       | Notebook    | [3973070120](https://linux-hardware.org/?probe=3973070120) | Mar 12, 2022 |
| Jumper        | EZbook                      | Notebook    | [c374bd5058](https://linux-hardware.org/?probe=c374bd5058) | Mar 11, 2022 |
| Apple         | MacBookAir3,1               | Notebook    | [320f9e6841](https://linux-hardware.org/?probe=320f9e6841) | Mar 11, 2022 |
| Metabox       | Edge-Pro NS50MU             | Notebook    | [1371afa6ac](https://linux-hardware.org/?probe=1371afa6ac) | Mar 11, 2022 |
| MSI           | G31M3-L V2                  | Desktop     | [4c15ba6fb9](https://linux-hardware.org/?probe=4c15ba6fb9) | Mar 10, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [b27d8c8724](https://linux-hardware.org/?probe=b27d8c8724) | Mar 10, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [e77116d171](https://linux-hardware.org/?probe=e77116d171) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [161eda858b](https://linux-hardware.org/?probe=161eda858b) | Mar 10, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [36bada67c8](https://linux-hardware.org/?probe=36bada67c8) | Mar 08, 2022 |
| Dell          | Latitude XT2                | Notebook    | [ff6a48346f](https://linux-hardware.org/?probe=ff6a48346f) | Mar 07, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [f9c159a911](https://linux-hardware.org/?probe=f9c159a911) | Mar 06, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [ec13383aff](https://linux-hardware.org/?probe=ec13383aff) | Mar 06, 2022 |
| Jumper        | EZbook                      | Notebook    | [09544efb61](https://linux-hardware.org/?probe=09544efb61) | Mar 05, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [fb03915a3e](https://linux-hardware.org/?probe=fb03915a3e) | Mar 03, 2022 |
| Unknown       | TB-4000                     | Desktop     | [d92c05a18a](https://linux-hardware.org/?probe=d92c05a18a) | Mar 03, 2022 |
| Daewoo Luc... | Solo Top                    | Desktop     | [7f7b20688f](https://linux-hardware.org/?probe=7f7b20688f) | Mar 03, 2022 |
| Jumper        | EZbook                      | Notebook    | [de9a14c4ec](https://linux-hardware.org/?probe=de9a14c4ec) | Mar 02, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [bb9f45273a](https://linux-hardware.org/?probe=bb9f45273a) | Mar 01, 2022 |
| Unknown       | TB-4000                     | Desktop     | [dc43686a5a](https://linux-hardware.org/?probe=dc43686a5a) | Feb 27, 2022 |
| Samsung       | 550P5C/550P7C               | Notebook    | [f14f73025f](https://linux-hardware.org/?probe=f14f73025f) | Feb 27, 2022 |
| Dell          | 0GXM1W A02                  | Desktop     | [044a00e086](https://linux-hardware.org/?probe=044a00e086) | Feb 25, 2022 |
| Toshiba       | Satellite C75D-B            | Notebook    | [952057ee2b](https://linux-hardware.org/?probe=952057ee2b) | Feb 24, 2022 |
| Acer          | Nitro AN517-41              | Notebook    | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| Chuwi         | GemiBook                    | Notebook    | [25f5f358cb](https://linux-hardware.org/?probe=25f5f358cb) | Feb 17, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [f83ccc9cce](https://linux-hardware.org/?probe=f83ccc9cce) | Feb 15, 2022 |
| Sony          | SVP1321L1EBI                | Notebook    | [b35a3fbfec](https://linux-hardware.org/?probe=b35a3fbfec) | Feb 13, 2022 |
| HP            | ProBook 4535s               | Notebook    | [0d0cd13f8b](https://linux-hardware.org/?probe=0d0cd13f8b) | Feb 12, 2022 |
| ASUSTek       | Benicia                     | Desktop     | [aceee2d932](https://linux-hardware.org/?probe=aceee2d932) | Feb 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0df06bcae3](https://linux-hardware.org/?probe=0df06bcae3) | Feb 11, 2022 |
| HP            | Notebook                    | Notebook    | [1f47143486](https://linux-hardware.org/?probe=1f47143486) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [9f4f77f51d](https://linux-hardware.org/?probe=9f4f77f51d) | Feb 06, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [b6d5344f4e](https://linux-hardware.org/?probe=b6d5344f4e) | Feb 04, 2022 |
| Unknown       | TB-4000                     | Desktop     | [225e399fc1](https://linux-hardware.org/?probe=225e399fc1) | Feb 03, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [5aa1140ad5](https://linux-hardware.org/?probe=5aa1140ad5) | Feb 02, 2022 |
| Lenovo        | ThinkPad T480 20L6SCYP00    | Notebook    | [d69eb6fc3e](https://linux-hardware.org/?probe=d69eb6fc3e) | Jan 30, 2022 |
| GPU Compan... | GWTN141-10                  | Notebook    | [89835cd678](https://linux-hardware.org/?probe=89835cd678) | Jan 30, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [880cca4c8f](https://linux-hardware.org/?probe=880cca4c8f) | Jan 24, 2022 |
| Microsoft     | Surface Book                | Tablet      | [327a2ec07f](https://linux-hardware.org/?probe=327a2ec07f) | Jan 22, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [1e5331da8c](https://linux-hardware.org/?probe=1e5331da8c) | Jan 21, 2022 |
| Dell          | Latitude 7480               | Notebook    | [e184163da5](https://linux-hardware.org/?probe=e184163da5) | Jan 19, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [9901f0a14a](https://linux-hardware.org/?probe=9901f0a14a) | Jan 18, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [3837c06ca1](https://linux-hardware.org/?probe=3837c06ca1) | Jan 18, 2022 |
| Dell          | Inspiron 5580               | Notebook    | [a8e7059c51](https://linux-hardware.org/?probe=a8e7059c51) | Jan 17, 2022 |
| Lenovo        | ThinkPad E14 20RA0016GE     | Notebook    | [46eeb2d4b8](https://linux-hardware.org/?probe=46eeb2d4b8) | Jan 14, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [4e45161acc](https://linux-hardware.org/?probe=4e45161acc) | Jan 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [4c04661023](https://linux-hardware.org/?probe=4c04661023) | Jan 12, 2022 |
| Unknown       | Unknown                     | Desktop     | [bccc675fea](https://linux-hardware.org/?probe=bccc675fea) | Jan 08, 2022 |
| Microsoft     | Surface Pro 3               | Tablet      | [8f4b5410ad](https://linux-hardware.org/?probe=8f4b5410ad) | Jan 06, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [f75ebfbbc8](https://linux-hardware.org/?probe=f75ebfbbc8) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [680408ec06](https://linux-hardware.org/?probe=680408ec06) | Jan 01, 2022 |
| Dell          | 04YP6J A01                  | Desktop     | [623d384766](https://linux-hardware.org/?probe=623d384766) | Jan 01, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [4ec2105ead](https://linux-hardware.org/?probe=4ec2105ead) | Jan 01, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d0c5b453db](https://linux-hardware.org/?probe=d0c5b453db) | Dec 31, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [cbb37b3b6a](https://linux-hardware.org/?probe=cbb37b3b6a) | Dec 20, 2021 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [5c55046f50](https://linux-hardware.org/?probe=5c55046f50) | Dec 13, 2021 |
| Lenovo        | IdeaPad Y580                | Notebook    | [48d92517e3](https://linux-hardware.org/?probe=48d92517e3) | Dec 11, 2021 |
| Dell          | Precision M4600             | Notebook    | [f386251b14](https://linux-hardware.org/?probe=f386251b14) | Nov 30, 2021 |
| Alienware     | m15 R6                      | Notebook    | [487678d2e5](https://linux-hardware.org/?probe=487678d2e5) | Nov 27, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [550ad36300](https://linux-hardware.org/?probe=550ad36300) | Nov 26, 2021 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [db67630cee](https://linux-hardware.org/?probe=db67630cee) | Nov 26, 2021 |
| Toxic         | GM7MQ8P                     | Notebook    | [deb5cbd490](https://linux-hardware.org/?probe=deb5cbd490) | Nov 24, 2021 |
| MSI           | Creator Z16 Hiroshi F A1... | Notebook    | [40f615079d](https://linux-hardware.org/?probe=40f615079d) | Nov 23, 2021 |
| HP            | ZBook Firefly 14 G7 Mobi... | Notebook    | [0dc4672364](https://linux-hardware.org/?probe=0dc4672364) | Nov 21, 2021 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [aeacaefd26](https://linux-hardware.org/?probe=aeacaefd26) | Nov 14, 2021 |
| ASRock        | Z87 Killer                  | Desktop     | [0aafc0d981](https://linux-hardware.org/?probe=0aafc0d981) | Nov 13, 2021 |
| Toshiba       | Satellite L655              | Notebook    | [e41f3dd777](https://linux-hardware.org/?probe=e41f3dd777) | Nov 12, 2021 |
| Dell          | Latitude E6410              | Notebook    | [2f9b89dbb4](https://linux-hardware.org/?probe=2f9b89dbb4) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [6ef3dbe032](https://linux-hardware.org/?probe=6ef3dbe032) | Nov 09, 2021 |
| Dell          | Latitude E6410              | Notebook    | [099708f286](https://linux-hardware.org/?probe=099708f286) | Nov 07, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| HP            | Pavilion g7                 | Notebook    | [c1b5449516](https://linux-hardware.org/?probe=c1b5449516) | Nov 05, 2021 |
| Acer          | Aspire TC-780               | Desktop     | [f6de1ed637](https://linux-hardware.org/?probe=f6de1ed637) | Nov 04, 2021 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [833500916c](https://linux-hardware.org/?probe=833500916c) | Nov 03, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [37a983c1e7](https://linux-hardware.org/?probe=37a983c1e7) | Oct 26, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [ca3a74943a](https://linux-hardware.org/?probe=ca3a74943a) | Oct 25, 2021 |
| Dell          | Latitude E7450              | Notebook    | [2d94d751ff](https://linux-hardware.org/?probe=2d94d751ff) | Oct 22, 2021 |
| Dell          | Latitude E7450              | Notebook    | [a2b09ead76](https://linux-hardware.org/?probe=a2b09ead76) | Oct 22, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [56c85806e2](https://linux-hardware.org/?probe=56c85806e2) | Oct 20, 2021 |
| HP            | Laptop 15q-dy0xxx           | Notebook    | [aa4c6c2a25](https://linux-hardware.org/?probe=aa4c6c2a25) | Oct 18, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [5b16f69a60](https://linux-hardware.org/?probe=5b16f69a60) | Oct 17, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [caa2855c26](https://linux-hardware.org/?probe=caa2855c26) | Oct 17, 2021 |
| HP            | Pavilion g7                 | Notebook    | [7e80ec4599](https://linux-hardware.org/?probe=7e80ec4599) | Oct 11, 2021 |
| HP            | Pavilion g7                 | Notebook    | [cd8ce3be30](https://linux-hardware.org/?probe=cd8ce3be30) | Oct 10, 2021 |
| HP            | Pavilion g7                 | Notebook    | [dd3f8159e0](https://linux-hardware.org/?probe=dd3f8159e0) | Oct 10, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [79e12d69ec](https://linux-hardware.org/?probe=79e12d69ec) | Oct 08, 2021 |
| Dell          | 0T2HR0 A00                  | Desktop     | [dc55f173fe](https://linux-hardware.org/?probe=dc55f173fe) | Oct 05, 2021 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [7dcd6067ac](https://linux-hardware.org/?probe=7dcd6067ac) | Oct 04, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [d0cd1577c7](https://linux-hardware.org/?probe=d0cd1577c7) | Oct 04, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [fb11994deb](https://linux-hardware.org/?probe=fb11994deb) | Oct 04, 2021 |
| Dell          | Inspiron 7501               | Notebook    | [1d532e72c0](https://linux-hardware.org/?probe=1d532e72c0) | Oct 02, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [b33c31b0cf](https://linux-hardware.org/?probe=b33c31b0cf) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [eafc16e86f](https://linux-hardware.org/?probe=eafc16e86f) | Sep 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [3eac62e012](https://linux-hardware.org/?probe=3eac62e012) | Sep 24, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [b733e7fac1](https://linux-hardware.org/?probe=b733e7fac1) | Sep 23, 2021 |
| Radxa         | ROCK 5B                     | Soc         | [c57bcaa35d](https://linux-hardware.org/?probe=c57bcaa35d) | Sep 19, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [493f8d65cb](https://linux-hardware.org/?probe=493f8d65cb) | Sep 18, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [09b7566e74](https://linux-hardware.org/?probe=09b7566e74) | Sep 14, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [b08ac328d1](https://linux-hardware.org/?probe=b08ac328d1) | Sep 14, 2021 |
| Eluktronic... | MAG-15u                     | Notebook    | [f931222022](https://linux-hardware.org/?probe=f931222022) | Sep 13, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [31bc470f08](https://linux-hardware.org/?probe=31bc470f08) | Sep 11, 2021 |
| Lenovo        | ThinkPad X250 20CL001GZA    | Notebook    | [e732588a09](https://linux-hardware.org/?probe=e732588a09) | Sep 05, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [ede284a3a3](https://linux-hardware.org/?probe=ede284a3a3) | Aug 30, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X412... | Notebook    | [03676f1856](https://linux-hardware.org/?probe=03676f1856) | Aug 28, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [41663f4fb2](https://linux-hardware.org/?probe=41663f4fb2) | Aug 26, 2021 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0460f1a29b](https://linux-hardware.org/?probe=0460f1a29b) | Aug 24, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [2ef0cf3a18](https://linux-hardware.org/?probe=2ef0cf3a18) | Aug 16, 2021 |
| Dell          | Inspiron 5593               | Notebook    | [340be8f7fb](https://linux-hardware.org/?probe=340be8f7fb) | Aug 15, 2021 |
| Lenovo        | B50-80 80EW                 | Notebook    | [bd70ed892a](https://linux-hardware.org/?probe=bd70ed892a) | Aug 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b741d2ab2b](https://linux-hardware.org/?probe=b741d2ab2b) | Aug 12, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [3ba02ffef3](https://linux-hardware.org/?probe=3ba02ffef3) | Aug 10, 2021 |
| HP            | Pavilion dv6700             | Notebook    | [8714c1e6ab](https://linux-hardware.org/?probe=8714c1e6ab) | Aug 10, 2021 |
| MSI           | GT60 2OC/2OD                | Notebook    | [5ff69797f3](https://linux-hardware.org/?probe=5ff69797f3) | Aug 09, 2021 |
| ASUSTek       | X75VB                       | Notebook    | [bc26a9b439](https://linux-hardware.org/?probe=bc26a9b439) | Aug 07, 2021 |
| HP            | Pavilion 15                 | Notebook    | [f0f33cb33a](https://linux-hardware.org/?probe=f0f33cb33a) | Aug 06, 2021 |
| Dell          | Latitude E6420              | Notebook    | [9e72687dd4](https://linux-hardware.org/?probe=9e72687dd4) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [57037eb714](https://linux-hardware.org/?probe=57037eb714) | Aug 05, 2021 |
| Microsoft     | Surface Pro 3               | Tablet      | [89852ab731](https://linux-hardware.org/?probe=89852ab731) | Aug 05, 2021 |
| HP            | Pavilion dv7                | Notebook    | [5d8cfc9c95](https://linux-hardware.org/?probe=5d8cfc9c95) | Aug 04, 2021 |
| HP            | Pavilion dv7                | Notebook    | [1d2d7a30f9](https://linux-hardware.org/?probe=1d2d7a30f9) | Aug 04, 2021 |
| ZOTAC         | Unknown                     | Desktop     | [0324aff0a3](https://linux-hardware.org/?probe=0324aff0a3) | Aug 03, 2021 |
| ZOTAC         | Unknown                     | Desktop     | [c1a9e01bd7](https://linux-hardware.org/?probe=c1a9e01bd7) | Aug 03, 2021 |
| ASUSTek       | G74Sx                       | Notebook    | [fb80932ddd](https://linux-hardware.org/?probe=fb80932ddd) | Jul 23, 2021 |
| HP            | 1850                        | Desktop     | [687c780f5c](https://linux-hardware.org/?probe=687c780f5c) | Jul 19, 2021 |
| Dell          | Latitude E7440              | Notebook    | [3a22179f3b](https://linux-hardware.org/?probe=3a22179f3b) | Jul 18, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [57a4116288](https://linux-hardware.org/?probe=57a4116288) | Jul 17, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [91a0ff32e1](https://linux-hardware.org/?probe=91a0ff32e1) | Jul 06, 2021 |
| ASUSTek       | X450EA                      | Notebook    | [e4dc18ebf9](https://linux-hardware.org/?probe=e4dc18ebf9) | Jul 06, 2021 |
| Dell          | Precision M6400             | Notebook    | [7f2245c976](https://linux-hardware.org/?probe=7f2245c976) | Jun 24, 2021 |
| ASUSTek       | Q524UQ                      | Notebook    | [33d61b2077](https://linux-hardware.org/?probe=33d61b2077) | Jun 17, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [2a633bc008](https://linux-hardware.org/?probe=2a633bc008) | Jun 14, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [e3bb48a049](https://linux-hardware.org/?probe=e3bb48a049) | Jun 14, 2021 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [fa4061e79f](https://linux-hardware.org/?probe=fa4061e79f) | Jun 09, 2021 |
| Gateway       | MP8708                      | Notebook    | [ba382202c2](https://linux-hardware.org/?probe=ba382202c2) | Jun 04, 2021 |
| HP            | ZBook 15 G5                 | Notebook    | [462531aabd](https://linux-hardware.org/?probe=462531aabd) | Jun 03, 2021 |
| ASUSTek       | Q524UQ                      | Notebook    | [b510297404](https://linux-hardware.org/?probe=b510297404) | Jun 03, 2021 |
| Dell          | Inspiron 5558               | Notebook    | [91fdca7228](https://linux-hardware.org/?probe=91fdca7228) | May 31, 2021 |
| HP            | 1850                        | Desktop     | [3bde7e8e11](https://linux-hardware.org/?probe=3bde7e8e11) | May 27, 2021 |
| MSI           | GE73 Raider RGB 8RE         | Notebook    | [5aedb75ad8](https://linux-hardware.org/?probe=5aedb75ad8) | May 21, 2021 |
| Fujitsu       | LIFEBOOK T731               | Notebook    | [1cb3267b57](https://linux-hardware.org/?probe=1cb3267b57) | May 21, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [dc6bc48c4d](https://linux-hardware.org/?probe=dc6bc48c4d) | May 18, 2021 |
| Lenovo        | ThinkPad X260 20F5S5QT00    | Notebook    | [a84514b117](https://linux-hardware.org/?probe=a84514b117) | May 14, 2021 |
| Intel         | NUC8i7HVB J68196-601        | Mini pc     | [d186af4ee3](https://linux-hardware.org/?probe=d186af4ee3) | May 14, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [aa4c3ffed1](https://linux-hardware.org/?probe=aa4c3ffed1) | May 13, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [605367d5d4](https://linux-hardware.org/?probe=605367d5d4) | May 13, 2021 |
| HP            | Pavilion dv4                | Notebook    | [250773011b](https://linux-hardware.org/?probe=250773011b) | May 07, 2021 |
| Dell          | 0C1R19 A02                  | Desktop     | [ff5bb2ee2a](https://linux-hardware.org/?probe=ff5bb2ee2a) | May 03, 2021 |
| HP            | HDX PREMIUM SERIES          | Notebook    | [47374d1b5f](https://linux-hardware.org/?probe=47374d1b5f) | Apr 27, 2021 |
| HP            | HDX PREMIUM SERIES          | Notebook    | [58b0d9473e](https://linux-hardware.org/?probe=58b0d9473e) | Apr 27, 2021 |
| HP            | 8430 1000                   | All in one  | [5c5adcc248](https://linux-hardware.org/?probe=5c5adcc248) | Apr 24, 2021 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4dd4f28ca7](https://linux-hardware.org/?probe=4dd4f28ca7) | Apr 11, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [ee1ba6ee04](https://linux-hardware.org/?probe=ee1ba6ee04) | Apr 01, 2021 |
| PC Special... | N150CU                      | Notebook    | [39136d47f7](https://linux-hardware.org/?probe=39136d47f7) | Apr 01, 2021 |
| MSI           | GE75 Raider 10SF            | Notebook    | [d15c48b6a1](https://linux-hardware.org/?probe=d15c48b6a1) | Mar 29, 2021 |
| Acer          | Predator PO3-600 V:1.1      | Desktop     | [6ea75bdbb5](https://linux-hardware.org/?probe=6ea75bdbb5) | Mar 26, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [78663f1468](https://linux-hardware.org/?probe=78663f1468) | Mar 25, 2021 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [de917105cd](https://linux-hardware.org/?probe=de917105cd) | Mar 22, 2021 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [01ab712b94](https://linux-hardware.org/?probe=01ab712b94) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [67ed2b4e7f](https://linux-hardware.org/?probe=67ed2b4e7f) | Mar 22, 2021 |
| HP            | Pavilion Notebook           | Notebook    | [acda849408](https://linux-hardware.org/?probe=acda849408) | Mar 22, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [76f7963d8a](https://linux-hardware.org/?probe=76f7963d8a) | Mar 21, 2021 |
| Wortmann      | TERRA_MOBILE_1542           | Notebook    | [12fb4cc711](https://linux-hardware.org/?probe=12fb4cc711) | Mar 21, 2021 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [6b26a69326](https://linux-hardware.org/?probe=6b26a69326) | Mar 21, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [a4bf4bb64c](https://linux-hardware.org/?probe=a4bf4bb64c) | Mar 17, 2021 |
| HP            | Pavilion dv6                | Notebook    | [06b3024017](https://linux-hardware.org/?probe=06b3024017) | Mar 14, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [11a466e06d](https://linux-hardware.org/?probe=11a466e06d) | Mar 05, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [89174dda21](https://linux-hardware.org/?probe=89174dda21) | Feb 27, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [489ed0f996](https://linux-hardware.org/?probe=489ed0f996) | Feb 26, 2021 |
| Dell          | Inspiron 5420               | Notebook    | [a357eb71e0](https://linux-hardware.org/?probe=a357eb71e0) | Feb 22, 2021 |
| HP            | 339A                        | Desktop     | [b105e94284](https://linux-hardware.org/?probe=b105e94284) | Feb 20, 2021 |
| HP            | 339A                        | Desktop     | [3dfdd6aa5e](https://linux-hardware.org/?probe=3dfdd6aa5e) | Feb 20, 2021 |
| Lenovo        | IdeaPad 110-14ISK 80UC      | Notebook    | [2cf1bfd6c6](https://linux-hardware.org/?probe=2cf1bfd6c6) | Feb 16, 2021 |
| HP            | Laptop 15-db0xxx            | Notebook    | [c337c59497](https://linux-hardware.org/?probe=c337c59497) | Feb 13, 2021 |
| HP            | ProBook 450 G1              | Notebook    | [284fd25f3e](https://linux-hardware.org/?probe=284fd25f3e) | Feb 11, 2021 |
| MSI           | B250M MORTAR                | Desktop     | [be8a65f362](https://linux-hardware.org/?probe=be8a65f362) | Feb 02, 2021 |
| Dell          | 0CU409                      | Desktop     | [64c8a84081](https://linux-hardware.org/?probe=64c8a84081) | Jan 29, 2021 |
| HP            | ENVY 15                     | Notebook    | [c39474b63f](https://linux-hardware.org/?probe=c39474b63f) | Jan 23, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | Notebook    | [ea1a80dc34](https://linux-hardware.org/?probe=ea1a80dc34) | Jan 21, 2021 |
| Positivo B... | VJFE51F11X-B0111H           | Notebook    | [80dc10f323](https://linux-hardware.org/?probe=80dc10f323) | Jan 21, 2021 |
| Acer          | Aspire X3990                | Desktop     | [a3e9301c7f](https://linux-hardware.org/?probe=a3e9301c7f) | Jan 16, 2021 |
| Acer          | Aspire X3990                | Desktop     | [1660d13b44](https://linux-hardware.org/?probe=1660d13b44) | Jan 12, 2021 |
| HP            | 3047h                       | Desktop     | [8b50e12296](https://linux-hardware.org/?probe=8b50e12296) | Jan 07, 2021 |
| Dell          | Latitude 7390               | Notebook    | [0ef9ffc535](https://linux-hardware.org/?probe=0ef9ffc535) | Dec 27, 2020 |
| Medion        | MS-7621                     | Desktop     | [74c49730d1](https://linux-hardware.org/?probe=74c49730d1) | Dec 27, 2020 |
| Positivo      | POS-PIG43BC                 | Desktop     | [146c7d86bb](https://linux-hardware.org/?probe=146c7d86bb) | Dec 27, 2020 |
| ASUSTek       | X555LAB                     | Notebook    | [ab17ca4eef](https://linux-hardware.org/?probe=ab17ca4eef) | Dec 25, 2020 |
| Lenovo        | ThinkPad T490 20N2S04000    | Notebook    | [4f02aacb6d](https://linux-hardware.org/?probe=4f02aacb6d) | Dec 21, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [33960a08de](https://linux-hardware.org/?probe=33960a08de) | Dec 20, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [748a6b0b09](https://linux-hardware.org/?probe=748a6b0b09) | Dec 16, 2020 |
| Dell          | Latitude E5440              | Notebook    | [7befb8e28b](https://linux-hardware.org/?probe=7befb8e28b) | Nov 29, 2020 |
| Dell          | Latitude E5440              | Notebook    | [3064211887](https://linux-hardware.org/?probe=3064211887) | Nov 28, 2020 |
| Lenovo        | ThinkPad X220 42912XG       | Notebook    | [ce89f09531](https://linux-hardware.org/?probe=ce89f09531) | Nov 26, 2020 |
| HP            | 3047h                       | Desktop     | [b65caab721](https://linux-hardware.org/?probe=b65caab721) | Nov 24, 2020 |
| Acer          | Aspire 5250                 | Notebook    | [11f670b6b1](https://linux-hardware.org/?probe=11f670b6b1) | Nov 23, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [82be91a50a](https://linux-hardware.org/?probe=82be91a50a) | Nov 20, 2020 |
| HP            | Compaq Presario C700        | Notebook    | [f86087eece](https://linux-hardware.org/?probe=f86087eece) | Nov 20, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [458ab52080](https://linux-hardware.org/?probe=458ab52080) | Nov 17, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [6608936515](https://linux-hardware.org/?probe=6608936515) | Nov 10, 2020 |
| Foxconn       | 45CMX/45GMX/45CMX-K         | Desktop     | [7918687a8b](https://linux-hardware.org/?probe=7918687a8b) | Nov 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [c110de3643](https://linux-hardware.org/?probe=c110de3643) | Oct 31, 2020 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [f95c24897c](https://linux-hardware.org/?probe=f95c24897c) | Oct 30, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [f7a2b660d8](https://linux-hardware.org/?probe=f7a2b660d8) | Oct 29, 2020 |
| ASUSTek       | M5A99X EVO                  | Desktop     | [c687805b04](https://linux-hardware.org/?probe=c687805b04) | Oct 29, 2020 |
| ASUSTek       | X540YA                      | Notebook    | [501ca10eeb](https://linux-hardware.org/?probe=501ca10eeb) | Oct 25, 2020 |
| ECS           | A740GM-M                    | Desktop     | [423f49affd](https://linux-hardware.org/?probe=423f49affd) | Oct 25, 2020 |
| Dell          | Vostro 3558                 | Notebook    | [8f4f321359](https://linux-hardware.org/?probe=8f4f321359) | Oct 18, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | Notebook    | [8ce3caa35a](https://linux-hardware.org/?probe=8ce3caa35a) | Oct 15, 2020 |
| ASUSTek       | TUF Gaming FX705GD          | Notebook    | [b2d5b6eb69](https://linux-hardware.org/?probe=b2d5b6eb69) | Oct 15, 2020 |
| Lenovo        | ThinkPad T420s 4174W2P      | Notebook    | [c8eacff838](https://linux-hardware.org/?probe=c8eacff838) | Oct 10, 2020 |
| HP            | Pavilion 17                 | Notebook    | [2a0d11caf1](https://linux-hardware.org/?probe=2a0d11caf1) | Oct 09, 2020 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [f06ac6483c](https://linux-hardware.org/?probe=f06ac6483c) | Oct 06, 2020 |
| Razer         | Blade Stealth               | Notebook    | [564265e066](https://linux-hardware.org/?probe=564265e066) | Oct 01, 2020 |
| Acer          | Predator PH317-53           | Notebook    | [16cddb4fce](https://linux-hardware.org/?probe=16cddb4fce) | Sep 29, 2020 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [2bc8fbe372](https://linux-hardware.org/?probe=2bc8fbe372) | Sep 27, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [74a0ca3614](https://linux-hardware.org/?probe=74a0ca3614) | Sep 25, 2020 |
| HP            | EliteBook Folio 9480m       | Notebook    | [bb1615dd63](https://linux-hardware.org/?probe=bb1615dd63) | Sep 24, 2020 |
| System76      | Gazelle                     | Notebook    | [d96d5e60ae](https://linux-hardware.org/?probe=d96d5e60ae) | Sep 20, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [4ad16b3038](https://linux-hardware.org/?probe=4ad16b3038) | Sep 20, 2020 |
| Alienware     | 17 R4                       | Notebook    | [d58b082d72](https://linux-hardware.org/?probe=d58b082d72) | Sep 19, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d77bb0aa31](https://linux-hardware.org/?probe=d77bb0aa31) | Sep 18, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [951e2d1aa6](https://linux-hardware.org/?probe=951e2d1aa6) | Sep 18, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [f88025bc71](https://linux-hardware.org/?probe=f88025bc71) | Sep 16, 2020 |
| Dell          | Latitude 3400               | Notebook    | [f7d1872e51](https://linux-hardware.org/?probe=f7d1872e51) | Sep 13, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [090d50eec1](https://linux-hardware.org/?probe=090d50eec1) | Sep 12, 2020 |
| Lenovo        | E41-25 81FS                 | Notebook    | [1e512df642](https://linux-hardware.org/?probe=1e512df642) | Sep 12, 2020 |
| Toshiba       | Satellite L750              | Notebook    | [091facc59a](https://linux-hardware.org/?probe=091facc59a) | Sep 12, 2020 |
| Dell          | Latitude 3400               | Notebook    | [825d226ad5](https://linux-hardware.org/?probe=825d226ad5) | Sep 10, 2020 |
| Apple         | MacBookPro8,1               | Notebook    | [fc23c05e20](https://linux-hardware.org/?probe=fc23c05e20) | Sep 04, 2020 |
| Lenovo        | ThinkPad X240 20AMS4MH00    | Notebook    | [3e6177e73c](https://linux-hardware.org/?probe=3e6177e73c) | Sep 01, 2020 |
| Gigabyte      | H370M DS3H-CF               | Desktop     | [affb4f7587](https://linux-hardware.org/?probe=affb4f7587) | Aug 29, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [c87fcab7c7](https://linux-hardware.org/?probe=c87fcab7c7) | Aug 26, 2020 |
| Lenovo        | IdeaPadFlex 4-1470 80SA     | Convertible | [608ad8477d](https://linux-hardware.org/?probe=608ad8477d) | Aug 22, 2020 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [dbf4ca0908](https://linux-hardware.org/?probe=dbf4ca0908) | Aug 10, 2020 |
| Sony          | VPCCB15FG                   | Notebook    | [4d93dfd9c0](https://linux-hardware.org/?probe=4d93dfd9c0) | Aug 09, 2020 |
| Dell          | System Inspiron N7110       | Notebook    | [c4ba9dc0dc](https://linux-hardware.org/?probe=c4ba9dc0dc) | Aug 05, 2020 |
| HP            | Notebook                    | Notebook    | [989b6b7d5d](https://linux-hardware.org/?probe=989b6b7d5d) | Aug 04, 2020 |
| Acer          | Aspire ES1-111M             | Notebook    | [359a7266e5](https://linux-hardware.org/?probe=359a7266e5) | Aug 03, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [bfffb28472](https://linux-hardware.org/?probe=bfffb28472) | Jul 27, 2020 |
| Lenovo        | G480 20149                  | Notebook    | [53b70e68df](https://linux-hardware.org/?probe=53b70e68df) | Jul 27, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [f032f63f3a](https://linux-hardware.org/?probe=f032f63f3a) | Jul 26, 2020 |
| HP            | Notebook                    | Notebook    | [ee51b68070](https://linux-hardware.org/?probe=ee51b68070) | Jul 23, 2020 |
| HP            | Notebook                    | Notebook    | [87cfa4c37e](https://linux-hardware.org/?probe=87cfa4c37e) | Jul 23, 2020 |
| Dell          | System Inspiron N7110       | Notebook    | [3177a50194](https://linux-hardware.org/?probe=3177a50194) | Jul 22, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [f77f8a2639](https://linux-hardware.org/?probe=f77f8a2639) | Jul 15, 2020 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [4afe4f5961](https://linux-hardware.org/?probe=4afe4f5961) | Jul 15, 2020 |
| Acer          | Aspire V5-122P              | Notebook    | [a362dee702](https://linux-hardware.org/?probe=a362dee702) | Jul 10, 2020 |
| Dell          | Latitude 7480               | Notebook    | [aab5a5b50a](https://linux-hardware.org/?probe=aab5a5b50a) | Jul 07, 2020 |
| eMachines     | eME728                      | Notebook    | [3f409bf927](https://linux-hardware.org/?probe=3f409bf927) | Jul 05, 2020 |
| Lenovo        | IdeaPad 110-15IBR 80T7      | Notebook    | [3c48dbb383](https://linux-hardware.org/?probe=3c48dbb383) | Jul 05, 2020 |
| Apple         | Mac-F221BEC8                | Desktop     | [1d8d1db67e](https://linux-hardware.org/?probe=1d8d1db67e) | Jul 04, 2020 |
| Dell          | 0D6H9T A00                  | Desktop     | [06e9599063](https://linux-hardware.org/?probe=06e9599063) | Jul 04, 2020 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [dda8536e62](https://linux-hardware.org/?probe=dda8536e62) | Jun 11, 2020 |
| Dell          | G7 7790                     | Notebook    | [506d29b806](https://linux-hardware.org/?probe=506d29b806) | Jun 02, 2020 |
| Dell          | G7 7790                     | Notebook    | [0551762cbb](https://linux-hardware.org/?probe=0551762cbb) | Jun 02, 2020 |
| Biostar       | H77MU3                      | Desktop     | [048ffba01b](https://linux-hardware.org/?probe=048ffba01b) | May 24, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [7c05b67968](https://linux-hardware.org/?probe=7c05b67968) | May 22, 2020 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [fc8bf8a5a6](https://linux-hardware.org/?probe=fc8bf8a5a6) | May 22, 2020 |
| Google        | Celes                       | Notebook    | [d417dd63dd](https://linux-hardware.org/?probe=d417dd63dd) | May 22, 2020 |
| Google        | Celes                       | Notebook    | [88d722fa1b](https://linux-hardware.org/?probe=88d722fa1b) | May 22, 2020 |
| ASUSTek       | X75VB                       | Notebook    | [f41d9b003f](https://linux-hardware.org/?probe=f41d9b003f) | May 22, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Parrot/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Parrot 5.3   | 120       | 15.04%  |
| Parrot 5.0   | 119       | 14.91%  |
| Parrot 4.11  | 101       | 12.66%  |
| Parrot 5.1   | 74        | 9.27%   |
| Parrot 4.10  | 60        | 7.52%   |
| Parrot 6.2   | 55        | 6.89%   |
| Parrot 6.0   | 50        | 6.27%   |
| Parrot 6.3   | 46        | 5.76%   |
| Parrot 6.4   | 40        | 5.01%   |
| Parrot 5.2   | 36        | 4.51%   |
| Parrot 6.1   | 30        | 3.76%   |
| Parrot 4.9   | 23        | 2.88%   |
| Parrot 4.8   | 23        | 2.88%   |
| Parrot 4.7   | 13        | 1.63%   |
| Parrot 7.0   | 2         | 0.25%   |
| Parrot 4.6   | 2         | 0.25%   |
| Parrot 4.5   | 1         | 0.13%   |
| Parrot 4.4   | 1         | 0.13%   |
| Parrot 4.2.2 | 1         | 0.13%   |
| Parrot 3.10  | 1         | 0.13%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Parrot | 757       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 6.1.0-1parrot1-amd64     | 119       | 14.73%  |
| 6.5.0-13parrot1-amd64    | 64        | 7.92%   |
| 5.16.0-12parrot1-amd64   | 56        | 6.93%   |
| 5.14.0-9parrot1-amd64    | 54        | 6.68%   |
| 6.0.0-12parrot1-amd64    | 48        | 5.94%   |
| 6.12.32-amd64            | 37        | 4.58%   |
| 5.18.0-14parrot1-amd64   | 35        | 4.33%   |
| 5.10.0-6parrot1-amd64    | 35        | 4.33%   |
| 6.10.11-amd64            | 33        | 4.08%   |
| 6.0.0-2parrot1-amd64     | 33        | 4.08%   |
| 5.7.0-2parrot2-amd64     | 33        | 4.08%   |
| 6.12.12-amd64            | 29        | 3.59%   |
| 5.5.0-1parrot1-amd64     | 25        | 3.09%   |
| 6.9.7-amd64              | 22        | 2.72%   |
| 6.11+parrot-amd64        | 22        | 2.72%   |
| 5.10.0-8parrot1-amd64    | 18        | 2.23%   |
| 5.18.0-1parrot1-amd64    | 17        | 2.1%    |
| 5.4.0-4parrot1-amd64     | 16        | 1.98%   |
| 5.15.0-15parrot1-amd64   | 11        | 1.36%   |
| 5.14.0-2parrot1-amd64    | 11        | 1.36%   |
| 5.6.0-2parrot1-amd64     | 10        | 1.24%   |
| 5.9.0-2parrot1-amd64     | 9         | 1.11%   |
| 5.8.0-2parrot1-amd64     | 6         | 0.74%   |
| 6.5.0-3parrot1-amd64     | 5         | 0.62%   |
| 5.4.0-2parrot1-amd64     | 5         | 0.62%   |
| 5.10.0-3parrot1-amd64    | 5         | 0.62%   |
| 5.8.0-1parrot1-amd64     | 4         | 0.5%    |
| 5.10.0-5parrot1-amd64    | 4         | 0.5%    |
| 5.4.0-3parrot1-amd64     | 3         | 0.37%   |
| 5.3.0-3parrot3-amd64     | 3         | 0.37%   |
| 5.2.0-2parrot1-amd64     | 3         | 0.37%   |
| 4.19.0-parrot4-28t-amd64 | 3         | 0.37%   |
| 6.12.57+deb13-amd64      | 2         | 0.25%   |
| 6.0.5-x64v1-xanmod1      | 2         | 0.25%   |
| 5.10.92-v8+              | 2         | 0.25%   |
| 4.18.0-parrot10-amd64    | 2         | 0.25%   |
| 6.6.13+bpo-amd64         | 1         | 0.12%   |
| 6.5.0-kali3-amd64        | 1         | 0.12%   |
| 6.5.0-13parrot1-arm64    | 1         | 0.12%   |
| 6.14.1-x64v3-xanmod1     | 1         | 0.12%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.0   | 121       | 15.07%  |
| 6.0.0   | 80        | 9.96%   |
| 6.5.0   | 70        | 8.72%   |
| 5.10.0  | 64        | 7.97%   |
| 5.14.0  | 63        | 7.85%   |
| 5.16.0  | 57        | 7.1%    |
| 5.18.0  | 51        | 6.35%   |
| 6.12.32 | 37        | 4.61%   |
| 5.7.0   | 34        | 4.23%   |
| 6.10.11 | 33        | 4.11%   |
| 6.12.12 | 29        | 3.61%   |
| 5.4.0   | 26        | 3.24%   |
| 5.5.0   | 25        | 3.11%   |
| 6.9.7   | 22        | 2.74%   |
| 6.11    | 22        | 2.74%   |
| 5.15.0  | 12        | 1.49%   |
| 5.8.0   | 10        | 1.25%   |
| 5.6.0   | 10        | 1.25%   |
| 5.9.0   | 9         | 1.12%   |
| 5.3.0   | 5         | 0.62%   |
| 4.19.0  | 4         | 0.5%    |
| 5.2.0   | 3         | 0.37%   |
| 6.12.57 | 2         | 0.25%   |
| 6.0.5   | 2         | 0.25%   |
| 5.10.92 | 2         | 0.25%   |
| 4.18.0  | 2         | 0.25%   |
| 6.6.13  | 1         | 0.12%   |
| 6.14.1  | 1         | 0.12%   |
| 6.12.15 | 1         | 0.12%   |
| 6.11.5  | 1         | 0.12%   |
| 6.1.27  | 1         | 0.12%   |
| 5.1.0   | 1         | 0.12%   |
| 4.14.0  | 1         | 0.12%   |
| Unknown | 1         | 0.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1     | 122       | 15.27%  |
| 6.0     | 82        | 10.26%  |
| 6.5     | 70        | 8.76%   |
| 5.10    | 66        | 8.26%   |
| 6.12    | 65        | 8.14%   |
| 5.14    | 63        | 7.88%   |
| 5.16    | 57        | 7.13%   |
| 5.18    | 51        | 6.38%   |
| 5.7     | 34        | 4.26%   |
| 6.10    | 33        | 4.13%   |
| 5.4     | 26        | 3.25%   |
| 5.5     | 25        | 3.13%   |
| 6.9     | 22        | 2.75%   |
| 6       | 22        | 2.75%   |
| 5.15    | 12        | 1.5%    |
| 5.8     | 10        | 1.25%   |
| 5.6     | 10        | 1.25%   |
| 5.9     | 9         | 1.13%   |
| 5.3     | 5         | 0.63%   |
| 4.19    | 4         | 0.5%    |
| 5.2     | 3         | 0.38%   |
| 4.18    | 2         | 0.25%   |
| 6.6     | 1         | 0.13%   |
| 6.14    | 1         | 0.13%   |
| 6.11    | 1         | 0.13%   |
| 5.1     | 1         | 0.13%   |
| 4.14    | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 752       | 99.34%  |
| aarch64 | 3         | 0.4%    |
| i686    | 2         | 0.26%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| MATE            | 593       | 76.52%  |
| KDE5            | 102       | 13.16%  |
| Unknown         | 23        | 2.97%   |
| KDE             | 21        | 2.71%   |
| XFCE            | 15        | 1.94%   |
| GNOME           | 11        | 1.42%   |
| X-Cinnamon      | 3         | 0.39%   |
| LXDE            | 1         | 0.13%   |
| KDE6            | 1         | 0.13%   |
| GNOME Flashback | 1         | 0.13%   |
| GNOME Classic   | 1         | 0.13%   |
| Cinnamon        | 1         | 0.13%   |
| Budgie          | 1         | 0.13%   |
| bspwm           | 1         | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 733       | 96.83%  |
| Wayland | 18        | 2.38%   |
| Tty     | 4         | 0.53%   |
| Unknown | 2         | 0.26%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 430       | 55.7%   |
| Unknown | 238       | 30.83%  |
| TDM     | 71        | 9.2%    |
| SDDM    | 21        | 2.72%   |
| GDM     | 10        | 1.3%    |
| GDM3    | 2         | 0.26%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 428       | 56.24%  |
| en_GB   | 44        | 5.78%   |
| fr_FR   | 31        | 4.07%   |
| de_DE   | 22        | 2.89%   |
| ru_RU   | 21        | 2.76%   |
| es_ES   | 21        | 2.76%   |
| pt_BR   | 19        | 2.5%    |
| it_IT   | 19        | 2.5%    |
| en_IN   | 18        | 2.37%   |
| en_AU   | 16        | 2.1%    |
| Unknown | 15        | 1.97%   |
| pl_PL   | 13        | 1.71%   |
| es_MX   | 13        | 1.71%   |
| en_CA   | 11        | 1.45%   |
| cs_CZ   | 7         | 0.92%   |
| es_CO   | 4         | 0.53%   |
| en_ZA   | 4         | 0.53%   |
| tr_TR   | 3         | 0.39%   |
| es_PE   | 3         | 0.39%   |
| es_CL   | 3         | 0.39%   |
| es_AR   | 3         | 0.39%   |
| en_IE   | 3         | 0.39%   |
| C       | 3         | 0.39%   |
| ja_JP   | 2         | 0.26%   |
| id_ID   | 2         | 0.26%   |
| fr_CA   | 2         | 0.26%   |
| es_US   | 2         | 0.26%   |
| en_NZ   | 2         | 0.26%   |
| en_NG   | 2         | 0.26%   |
| en_HK   | 2         | 0.26%   |
| en_DK   | 2         | 0.26%   |
| de_CH   | 2         | 0.26%   |
| sk_SK   | 1         | 0.13%   |
| ru_UA   | 1         | 0.13%   |
| pt_PT   | 1         | 0.13%   |
| nl_NL   | 1         | 0.13%   |
| nl_BE   | 1         | 0.13%   |
| nb_NO   | 1         | 0.13%   |
| mk_MK   | 1         | 0.13%   |
| lt_LT   | 1         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 424       | 55.14%  |
| EFI  | 345       | 44.86%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 575       | 75.07%  |
| Ext4    | 93        | 12.14%  |
| Tmpfs   | 44        | 5.74%   |
| Overlay | 33        | 4.31%   |
| Xfs     | 14        | 1.83%   |
| Unknown | 7         | 0.91%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 384       | 49.81%  |
| Unknown | 270       | 35.02%  |
| MBR     | 117       | 15.18%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 657       | 85.88%  |
| Yes       | 108       | 14.12%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 497       | 64.97%  |
| Yes       | 268       | 35.03%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 133       | 17.57%  |
| Hewlett-Packard                      | 128       | 16.91%  |
| ASUSTek Computer                     | 110       | 14.53%  |
| Dell                                 | 97        | 12.81%  |
| Acer                                 | 49        | 6.47%   |
| MSI                                  | 48        | 6.34%   |
| Gigabyte Technology                  | 29        | 3.83%   |
| Apple                                | 23        | 3.04%   |
| Toshiba                              | 13        | 1.72%   |
| Samsung Electronics                  | 12        | 1.59%   |
| ASRock                               | 7         | 0.92%   |
| Unknown                              | 7         | 0.92%   |
| HUAWEI                               | 6         | 0.79%   |
| Google                               | 6         | 0.79%   |
| Foxconn                              | 6         | 0.79%   |
| Alienware                            | 6         | 0.79%   |
| Microsoft                            | 5         | 0.66%   |
| Fujitsu                              | 5         | 0.66%   |
| Gateway                              | 4         | 0.53%   |
| Sony                                 | 3         | 0.4%    |
| Razer                                | 3         | 0.4%    |
| Panasonic                            | 3         | 0.4%    |
| Intel                                | 3         | 0.4%    |
| Biostar                              | 3         | 0.4%    |
| Wortmann AG                          | 2         | 0.26%   |
| Raspberry Pi Foundation              | 2         | 0.26%   |
| Quanta                               | 2         | 0.26%   |
| Positivo                             | 2         | 0.26%   |
| Pegatron                             | 2         | 0.26%   |
| Notebook                             | 2         | 0.26%   |
| HC Technology.                       | 2         | 0.26%   |
| ECS                                  | 2         | 0.26%   |
| ZOTAC                                | 1         | 0.13%   |
| Wistron                              | 1         | 0.13%   |
| Toxic                                | 1         | 0.13%   |
| Timi                                 | 1         | 0.13%   |
| System76                             | 1         | 0.13%   |
| Supermicro                           | 1         | 0.13%   |
| Standard                             | 1         | 0.13%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Unknown                              | 10        | 1.32%   |
| HP Laptop 15-dy2xxx                  | 6         | 0.79%   |
| HP Notebook                          | 4         | 0.53%   |
| Dell OptiPlex 3020                   | 4         | 0.53%   |
| Dell Latitude E6420                  | 4         | 0.53%   |
| MSI Modern 15 A5M                    | 3         | 0.4%    |
| Lenovo IdeaPad 3 15IIL05 81WE        | 3         | 0.4%    |
| HP ProDesk 600 G1 SFF                | 3         | 0.4%    |
| HP Pavilion 15                       | 3         | 0.4%    |
| HP ENVY x360 Convertible 13-bd0xxx   | 3         | 0.4%    |
| HP EliteBook 8470p                   | 3         | 0.4%    |
| HP EliteBook 830 G6                  | 3         | 0.4%    |
| HP 250 G7 Notebook PC                | 3         | 0.4%    |
| Dell OptiPlex 7010                   | 3         | 0.4%    |
| Dell Inspiron MM061                  | 3         | 0.4%    |
| ASUS M5A78L-M/USB3                   | 3         | 0.4%    |
| Apple MacBookAir7,2                  | 3         | 0.4%    |
| Toshiba Satellite L775D              | 2         | 0.26%   |
| Toshiba Satellite L750               | 2         | 0.26%   |
| Samsung 300E4C/300E5C/300E7C         | 2         | 0.26%   |
| RPi Raspberry Pi 4 Model B Rev 1.5   | 2         | 0.26%   |
| Quanta TW9/SW9                       | 2         | 0.26%   |
| MSI MS-7D25                          | 2         | 0.26%   |
| MSI Katana GF66 12UC                 | 2         | 0.26%   |
| MSI Katana GF66 11UE                 | 2         | 0.26%   |
| Microsoft Surface Pro 3              | 2         | 0.26%   |
| Lenovo ThinkPad E15 Gen 3 20YG0041MX | 2         | 0.26%   |
| Lenovo Legion Pro 5 16IRX8 82WK      | 2         | 0.26%   |
| Lenovo E41-25 81FS                   | 2         | 0.26%   |
| HUAWEI HVY-WXX9                      | 2         | 0.26%   |
| HP ProBook 650 G1                    | 2         | 0.26%   |
| HP Pavilion g7                       | 2         | 0.26%   |
| HP Pavilion g6                       | 2         | 0.26%   |
| HP Pavilion dv6                      | 2         | 0.26%   |
| HP Pavilion dv4                      | 2         | 0.26%   |
| HP Laptop 17-cn0xxx                  | 2         | 0.26%   |
| HP ENVY x360 2-in-1 Laptop 15-ew0xxx | 2         | 0.26%   |
| HP EliteBook Folio 9480m             | 2         | 0.26%   |
| HP Compaq 8200 Elite SFF PC          | 2         | 0.26%   |
| HP 250 G2                            | 2         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 68        | 8.98%   |
| Dell Latitude      | 37        | 4.89%   |
| Lenovo IdeaPad     | 27        | 3.57%   |
| Dell Inspiron      | 27        | 3.57%   |
| Acer Aspire        | 25        | 3.3%    |
| HP Pavilion        | 22        | 2.91%   |
| HP Laptop          | 20        | 2.64%   |
| HP EliteBook       | 20        | 2.64%   |
| ASUS VivoBook      | 16        | 2.11%   |
| Dell OptiPlex      | 13        | 1.72%   |
| HP ENVY            | 12        | 1.59%   |
| ASUS ROG           | 12        | 1.59%   |
| Acer Nitro         | 12        | 1.59%   |
| Toshiba Satellite  | 11        | 1.45%   |
| HP ProBook         | 11        | 1.45%   |
| HP Compaq          | 10        | 1.32%   |
| ASUS PRIME         | 10        | 1.32%   |
| Unknown            | 10        | 1.32%   |
| Dell XPS           | 8         | 1.06%   |
| ASUS ASUS          | 8         | 1.06%   |
| MSI Katana         | 7         | 0.92%   |
| Lenovo Legion      | 6         | 0.79%   |
| Microsoft Surface  | 5         | 0.66%   |
| Lenovo Yoga        | 5         | 0.66%   |
| HP ZBook           | 5         | 0.66%   |
| HP Victus          | 5         | 0.66%   |
| HP 250             | 5         | 0.66%   |
| ASUS Zenbook       | 5         | 0.66%   |
| Lenovo ThinkCentre | 4         | 0.53%   |
| HP ProDesk         | 4         | 0.53%   |
| HP Notebook        | 4         | 0.53%   |
| Fujitsu LIFEBOOK   | 4         | 0.53%   |
| Dell Vostro        | 4         | 0.53%   |
| Dell Precision     | 4         | 0.53%   |
| ASUS TUF           | 4         | 0.53%   |
| Apple MacBookPro11 | 4         | 0.53%   |
| Acer Predator      | 4         | 0.53%   |
| Razer Blade        | 3         | 0.4%    |
| MSI Modern         | 3         | 0.4%    |
| Lenovo IdeaPadFlex | 3         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2021    | 84        | 11.1%   |
| 2019    | 73        | 9.64%   |
| 2020    | 66        | 8.72%   |
| 2011    | 59        | 7.79%   |
| 2022    | 56        | 7.4%    |
| 2012    | 56        | 7.4%    |
| 2018    | 52        | 6.87%   |
| 2017    | 50        | 6.61%   |
| 2013    | 48        | 6.34%   |
| 2016    | 39        | 5.15%   |
| 2014    | 35        | 4.62%   |
| 2015    | 30        | 3.96%   |
| 2023    | 25        | 3.3%    |
| 2010    | 23        | 3.04%   |
| 2008    | 16        | 2.11%   |
| 2009    | 12        | 1.59%   |
| 2024    | 11        | 1.45%   |
| 2007    | 11        | 1.45%   |
| 2006    | 8         | 1.06%   |
| Unknown | 2         | 0.26%   |
| 2025    | 1         | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 527       | 69.62%  |
| Desktop        | 182       | 24.04%  |
| Convertible    | 24        | 3.17%   |
| Tablet         | 7         | 0.92%   |
| Mini pc        | 7         | 0.92%   |
| All in one     | 6         | 0.79%   |
| System on chip | 4         | 0.53%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 757       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 751       | 99.21%  |
| Yes  | 6         | 0.79%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 198       | 25.85%  |
| 16.01-24.0  | 177       | 23.11%  |
| 8.01-16.0   | 154       | 20.1%   |
| 3.01-4.0    | 98        | 12.79%  |
| 32.01-64.0  | 79        | 10.31%  |
| 64.01-256.0 | 22        | 2.87%   |
| 24.01-32.0  | 20        | 2.61%   |
| 1.01-2.0    | 14        | 1.83%   |
| 2.01-3.0    | 4         | 0.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 271       | 33.54%  |
| 1.01-2.0   | 228       | 28.22%  |
| 4.01-8.0   | 133       | 16.46%  |
| 3.01-4.0   | 121       | 14.98%  |
| 0.51-1.0   | 25        | 3.09%   |
| 8.01-16.0  | 21        | 2.6%    |
| 16.01-24.0 | 4         | 0.5%    |
| 0.01-0.5   | 3         | 0.37%   |
| 32.01-64.0 | 1         | 0.12%   |
| 24.01-32.0 | 1         | 0.12%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 482       | 62.19%  |
| 2      | 214       | 27.61%  |
| 3      | 47        | 6.06%   |
| 4      | 17        | 2.19%   |
| 5      | 7         | 0.9%    |
| 6      | 4         | 0.52%   |
| 0      | 4         | 0.52%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 571       | 74.93%  |
| Yes       | 191       | 25.07%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 628       | 82.52%  |
| No        | 133       | 17.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 667       | 87.76%  |
| No        | 93        | 12.24%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 550       | 71.9%   |
| No        | 215       | 28.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 239       | 31.2%   |
| Germany      | 47        | 6.14%   |
| France       | 29        | 3.79%   |
| Brazil       | 28        | 3.66%   |
| Italy        | 26        | 3.39%   |
| UK           | 25        | 3.26%   |
| Spain        | 25        | 3.26%   |
| Russia       | 24        | 3.13%   |
| India        | 23        | 3%      |
| Netherlands  | 21        | 2.74%   |
| Mexico       | 20        | 2.61%   |
| Canada       | 19        | 2.48%   |
| Australia    | 16        | 2.09%   |
| Poland       | 11        | 1.44%   |
| Sweden       | 9         | 1.17%   |
| Kenya        | 9         | 1.17%   |
| Czechia      | 9         | 1.17%   |
| Indonesia    | 8         | 1.04%   |
| Switzerland  | 7         | 0.91%   |
| Algeria      | 7         | 0.91%   |
| South Africa | 6         | 0.78%   |
| Peru         | 6         | 0.78%   |
| Egypt        | 6         | 0.78%   |
| Colombia     | 6         | 0.78%   |
| Turkey       | 5         | 0.65%   |
| Portugal     | 5         | 0.65%   |
| Greece       | 5         | 0.65%   |
| Finland      | 5         | 0.65%   |
| Denmark      | 5         | 0.65%   |
| Belgium      | 5         | 0.65%   |
| Bangladesh   | 5         | 0.65%   |
| Japan        | 4         | 0.52%   |
| Chile        | 4         | 0.52%   |
| Bulgaria     | 4         | 0.52%   |
| Austria      | 4         | 0.52%   |
| Argentina    | 4         | 0.52%   |
| UAE          | 3         | 0.39%   |
| Romania      | 3         | 0.39%   |
| Pakistan     | 3         | 0.39%   |
| Norway       | 3         | 0.39%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City         | Computers | Percent |
|--------------|-----------|---------|
| Amsterdam    | 11        | 1.38%   |
| Seattle      | 9         | 1.13%   |
| Rome         | 8         | 1%      |
| Nairobi      | 8         | 1%      |
| Los Angeles  | 8         | 1%      |
| Berlin       | 8         | 1%      |
| Moscow       | 7         | 0.88%   |
| Sydney       | 6         | 0.75%   |
| Melbourne    | 6         | 0.75%   |
| Houston      | 6         | 0.75%   |
| Dallas       | 6         | 0.75%   |
| Barcelona    | 6         | 0.75%   |
| Atlanta      | 6         | 0.75%   |
| San Antonio  | 5         | 0.63%   |
| Saint Paul   | 5         | 0.63%   |
| Phoenix      | 5         | 0.63%   |
| Paris        | 5         | 0.63%   |
| Minneapolis  | 5         | 0.63%   |
| Lima         | 5         | 0.63%   |
| Indianapolis | 5         | 0.63%   |
| Dublin       | 5         | 0.63%   |
| Alexandria   | 5         | 0.63%   |
| Prague       | 4         | 0.5%    |
| New York     | 4         | 0.5%    |
| Milan        | 4         | 0.5%    |
| Madrid       | 4         | 0.5%    |
| Lyon         | 4         | 0.5%    |
| London       | 4         | 0.5%    |
| Helsinki     | 4         | 0.5%    |
| Dhaka        | 4         | 0.5%    |
| Chicago      | 4         | 0.5%    |
| Athens       | 4         | 0.5%    |
| Zurich       | 3         | 0.38%   |
| Warsaw       | 3         | 0.38%   |
| Vienna       | 3         | 0.38%   |
| Ulan Bator   | 3         | 0.38%   |
| Toronto      | 3         | 0.38%   |
| Stockholm    | 3         | 0.38%   |
| Sao Paulo    | 3         | 0.38%   |
| San José    | 3         | 0.38%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 160       | 210    | 15.15%  |
| WDC                         | 137       | 176    | 12.97%  |
| Seagate                     | 115       | 149    | 10.89%  |
| Toshiba                     | 95        | 106    | 9%      |
| Sandisk                     | 59        | 73     | 5.59%   |
| Unknown                     | 55        | 59     | 5.21%   |
| Kingston                    | 55        | 59     | 5.21%   |
| SK hynix                    | 43        | 54     | 4.07%   |
| Hitachi                     | 32        | 39     | 3.03%   |
| Micron Technology           | 31        | 32     | 2.94%   |
| Crucial                     | 30        | 38     | 2.84%   |
| Intel                       | 24        | 44     | 2.27%   |
| HGST                        | 19        | 22     | 1.8%    |
| A-DATA Technology           | 16        | 16     | 1.52%   |
| China                       | 15        | 18     | 1.42%   |
| KIOXIA                      | 13        | 15     | 1.23%   |
| Apple                       | 13        | 15     | 1.23%   |
| Team                        | 10        | 12     | 0.95%   |
| JMicron Technology          | 7         | 7      | 0.66%   |
| Silicon Motion              | 6         | 6      | 0.57%   |
| PNY                         | 6         | 6      | 0.57%   |
| Kingston Technology Company | 6         | 8      | 0.57%   |
| SPCC                        | 5         | 5      | 0.47%   |
| Phison                      | 5         | 5      | 0.47%   |
| LITEON                      | 5         | 5      | 0.47%   |
| Intenso                     | 4         | 9      | 0.38%   |
| Unknown                     | 4         | 4      | 0.38%   |
| YMTC                        | 3         | 3      | 0.28%   |
| LITEONIT                    | 3         | 3      | 0.28%   |
| KingFast                    | 3         | 4      | 0.28%   |
| GOODRAM                     | 3         | 3      | 0.28%   |
| Fujitsu                     | 3         | 3      | 0.28%   |
| Corsair                     | 3         | 4      | 0.28%   |
| Teclast                     | 2         | 2      | 0.19%   |
| Patriot                     | 2         | 2      | 0.19%   |
| Netac                       | 2         | 2      | 0.19%   |
| Micron/Crucial Technology   | 2         | 3      | 0.19%   |
| Lexar                       | 2         | 2      | 0.19%   |
| KingSpec                    | 2         | 3      | 0.19%   |
| HUAWEI                      | 2         | 2      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Toshiba MQ04ABF100 1TB                            | 14        | 1.21%   |
| Samsung SSD 860 EVO 500GB                         | 11        | 0.95%   |
| Toshiba MQ01ABF050 500GB                          | 9         | 0.78%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 8         | 0.69%   |
| Kingston SA400S37240G 240GB SSD                   | 8         | 0.69%   |
| Unknown SD/MMC/MS PRO 2GB                         | 7         | 0.61%   |
| Unknown MMC Card  64GB                            | 7         | 0.61%   |
| Toshiba MQ01ABD100 1TB                            | 7         | 0.61%   |
| Kingston SA400S37480G 480GB SSD                   | 7         | 0.61%   |
| Toshiba DT01ACA200 2TB                            | 6         | 0.52%   |
| Toshiba DT01ACA100 1TB                            | 6         | 0.52%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                | 6         | 0.52%   |
| Seagate ST1000LM035-1RK172 1TB                    | 6         | 0.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                | 6         | 0.52%   |
| Seagate ST1000DM010-2EP102 1TB                    | 6         | 0.52%   |
| SanDisk NVMe SSD Drive 1TB                        | 6         | 0.52%   |
| Intel SSDPEKNU512GZ 512GB                         | 6         | 0.52%   |
| Intel HBRPEKNX0202AH 512GB                        | 6         | 0.52%   |
| Crucial CT1000MX500SSD1 1TB                       | 6         | 0.52%   |
| Unknown MMC Card  32GB                            | 5         | 0.43%   |
| Toshiba MQ01ABD075 752GB                          | 5         | 0.43%   |
| Seagate ST500LM012 HN-M500MBB 500GB               | 5         | 0.43%   |
| Seagate ST31000528AS 1TB                          | 5         | 0.43%   |
| Seagate Expansion 2TB                             | 5         | 0.43%   |
| SanDisk NVMe SSD Drive 512GB                      | 5         | 0.43%   |
| Samsung SSD 980 1TB                               | 5         | 0.43%   |
| Samsung SSD 970 EVO Plus 1TB                      | 5         | 0.43%   |
| Samsung SSD 850 EVO 250GB                         | 5         | 0.43%   |
| Micron 2400_MTFDKBA512QFM 512GB                   | 5         | 0.43%   |
| Kingston NVMe SSD Drive 512GB                     | 5         | 0.43%   |
| JMicron Generic 320GB                             | 5         | 0.43%   |
| Intel HBRPEKNX0202AHO 32GB                        | 5         | 0.43%   |
| HGST HTS721010A9E630 1TB                          | 5         | 0.43%   |
| HGST HTS541010A9E680 1TB                          | 5         | 0.43%   |
| Toshiba DT01ACA050 500GB                          | 4         | 0.35%   |
| Seagate ST320LT007-9ZV142 320GB                   | 4         | 0.35%   |
| Seagate ST2000DM008-2FR102 2TB                    | 4         | 0.35%   |
| SanDisk SSD PLUS 1000GB                           | 4         | 0.35%   |
| SanDisk NVMe SSD Drive 256GB                      | 4         | 0.35%   |
| Samsung SSD 980 PRO 1TB                           | 4         | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 112       | 146    | 30.35%  |
| WDC                 | 95        | 124    | 25.75%  |
| Toshiba             | 77        | 86     | 20.87%  |
| Hitachi             | 32        | 39     | 8.67%   |
| HGST                | 19        | 22     | 5.15%   |
| Samsung Electronics | 13        | 15     | 3.52%   |
| Unknown             | 7         | 8      | 1.9%    |
| JMicron Technology  | 5         | 5      | 1.36%   |
| Apple               | 2         | 2      | 0.54%   |
| TO Exter            | 1         | 1      | 0.27%   |
| SSK                 | 1         | 2      | 0.27%   |
| Maxtor              | 1         | 1      | 0.27%   |
| Intenso             | 1         | 5      | 0.27%   |
| Fujitsu             | 1         | 1      | 0.27%   |
| CLOVER              | 1         | 1      | 0.27%   |
| ASMedia             | 1         | 1      | 0.27%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 56        | 80     | 19.31%  |
| Kingston            | 33        | 36     | 11.38%  |
| SanDisk             | 26        | 29     | 8.97%   |
| Crucial             | 23        | 28     | 7.93%   |
| WDC                 | 21        | 23     | 7.24%   |
| China               | 14        | 17     | 4.83%   |
| Apple               | 9         | 11     | 3.1%    |
| A-DATA Technology   | 7         | 7      | 2.41%   |
| Team                | 6         | 8      | 2.07%   |
| PNY                 | 6         | 6      | 2.07%   |
| Micron Technology   | 6         | 6      | 2.07%   |
| Toshiba             | 5         | 6      | 1.72%   |
| SK hynix            | 5         | 5      | 1.72%   |
| LITEON              | 5         | 5      | 1.72%   |
| SPCC                | 3         | 3      | 1.03%   |
| Seagate             | 3         | 3      | 1.03%   |
| LITEONIT            | 3         | 3      | 1.03%   |
| KingFast            | 3         | 3      | 1.03%   |
| Intenso             | 3         | 4      | 1.03%   |
| Intel               | 3         | 3      | 1.03%   |
| GOODRAM             | 3         | 3      | 1.03%   |
| Unknown             | 2         | 2      | 0.69%   |
| Teclast             | 2         | 2      | 0.69%   |
| Patriot             | 2         | 2      | 0.69%   |
| KingSpec            | 2         | 3      | 0.69%   |
| Fujitsu             | 2         | 2      | 0.69%   |
| Fanxiang            | 2         | 2      | 0.69%   |
| Corsair             | 2         | 3      | 0.69%   |
| BR                  | 2         | 2      | 0.69%   |
| Apacer              | 2         | 3      | 0.69%   |
| Unknown             | 2         | 2      | 0.69%   |
| Zheino              | 1         | 1      | 0.34%   |
| XUM                 | 1         | 1      | 0.34%   |
| Wdxsky              | 1         | 1      | 0.34%   |
| WALRAM              | 1         | 1      | 0.34%   |
| W800SH              | 1         | 1      | 0.34%   |
| TSA 256G            | 1         | 1      | 0.34%   |
| Transcend           | 1         | 1      | 0.34%   |
| SCY                 | 1         | 1      | 0.34%   |
| S3+                 | 1         | 1      | 0.34%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 323       | 426    | 33.82%  |
| HDD     | 314       | 459    | 32.88%  |
| SSD     | 262       | 339    | 27.43%  |
| MMC     | 44        | 50     | 4.61%   |
| Unknown | 12        | 12     | 1.26%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 475       | 748    | 53.01%  |
| NVMe | 323       | 425    | 36.05%  |
| SAS  | 54        | 63     | 6.03%   |
| MMC  | 44        | 50     | 4.91%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 336       | 473    | 56.28%  |
| 0.51-1.0   | 192       | 237    | 32.16%  |
| 1.01-2.0   | 51        | 65     | 8.54%   |
| 3.01-4.0   | 10        | 12     | 1.68%   |
| 2.01-3.0   | 5         | 7      | 0.84%   |
| 4.01-10.0  | 2         | 2      | 0.34%   |
| 10.01-20.0 | 1         | 2      | 0.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 181       | 23.12%  |
| 501-1000       | 147       | 18.77%  |
| 101-250        | 146       | 18.65%  |
| 1001-2000      | 94        | 12.01%  |
| Unknown        | 71        | 9.07%   |
| 51-100         | 43        | 5.49%   |
| 1-20           | 33        | 4.21%   |
| More than 3000 | 29        | 3.7%    |
| 21-50          | 25        | 3.19%   |
| 2001-3000      | 14        | 1.79%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 238       | 29.75%  |
| 51-100         | 144       | 18%     |
| 1-20           | 115       | 14.38%  |
| 101-250        | 114       | 14.25%  |
| Unknown        | 71        | 8.88%   |
| 251-500        | 66        | 8.25%   |
| 501-1000       | 26        | 3.25%   |
| 1001-2000      | 17        | 2.13%   |
| More than 3000 | 4         | 0.5%    |
| 0              | 4         | 0.5%    |
| 2001-3000      | 1         | 0.13%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                | Computers | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| Samsung Electronics HM500JI 500GB    | 3         | 3      | 3.3%    |
| Toshiba MQ01ABD100 1TB               | 2         | 2      | 2.2%    |
| Seagate ST1000DM010-2EP102 1TB       | 2         | 2      | 2.2%    |
| SanDisk SD6SF1M128G1022I 128GB SSD   | 2         | 3      | 2.2%    |
| LITEON CV8-8E128-HP 128GB SSD        | 2         | 2      | 2.2%    |
| XUM HX256GSSDM2 256GB                | 1         | 1      | 1.1%    |
| WDC WD5000AAKS-75V0A0 500GB          | 1         | 1      | 1.1%    |
| WDC WD5000AADS-00S9B0 500GB          | 1         | 1      | 1.1%    |
| WDC WD3200BPVT-00JJ5T0 320GB         | 1         | 1      | 1.1%    |
| WDC WD3200BEKT-75PVMT1 320GB         | 1         | 1      | 1.1%    |
| WDC WD3200AVJS-63B6A0 320GB          | 1         | 1      | 1.1%    |
| WDC WD2500BEVT-22A23T0 250GB         | 1         | 1      | 1.1%    |
| WDC WD2003FZEX-00Z4SA0 2TB           | 1         | 1      | 1.1%    |
| WDC WD10JUCX-63WPNY0 1TB             | 1         | 1      | 1.1%    |
| WDC WD10EZRX-00L4HB0 1TB             | 1         | 1      | 1.1%    |
| WDC WD10EADS-22M2B0 1TB              | 1         | 1      | 1.1%    |
| Toshiba MQ01ABD075 752GB             | 1         | 1      | 1.1%    |
| Toshiba MK6475GSX 640GB              | 1         | 1      | 1.1%    |
| Toshiba MK5059GSXP 500GB             | 1         | 1      | 1.1%    |
| Toshiba MK3265GSXF 320GB             | 1         | 1      | 1.1%    |
| Toshiba MK3261GSYN 320GB             | 1         | 1      | 1.1%    |
| Toshiba HDWD110 1TB                  | 1         | 1      | 1.1%    |
| Toshiba DT01ACA050 500GB             | 1         | 1      | 1.1%    |
| SPCC M.2 PCIe SSD 256GB              | 1         | 1      | 1.1%    |
| SK hynix PC711 HFS256GDE9X073N 256GB | 1         | 1      | 1.1%    |
| SK hynix BC711 HFM512GD3JX013N 512GB | 1         | 1      | 1.1%    |
| Seagate ST9500325AS 500GB            | 1         | 1      | 1.1%    |
| Seagate ST940210AS 40GB              | 1         | 1      | 1.1%    |
| Seagate ST9250410AS 250GB            | 1         | 1      | 1.1%    |
| Seagate ST500NM0011 500GB            | 1         | 1      | 1.1%    |
| Seagate ST500LM012 HN-M500MBB 500GB  | 1         | 1      | 1.1%    |
| Seagate ST380215AS 80GB              | 1         | 1      | 1.1%    |
| Seagate ST3802110A 80GB              | 1         | 1      | 1.1%    |
| Seagate ST3500413AS 500GB            | 1         | 1      | 1.1%    |
| Seagate ST3320418AS 320GB            | 1         | 1      | 1.1%    |
| Seagate ST3250824AS 250GB            | 1         | 1      | 1.1%    |
| Seagate ST320LT007-9ZV142 320GB      | 1         | 1      | 1.1%    |
| Seagate ST320LM001 HN-M320MBB 320GB  | 1         | 1      | 1.1%    |
| Seagate ST3160215AS 160GB            | 1         | 1      | 1.1%    |
| Seagate ST31000528AS 1TB             | 1         | 1      | 1.1%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 21     | 19.32%  |
| WDC                 | 10        | 10     | 11.36%  |
| Toshiba             | 9         | 9      | 10.23%  |
| Samsung Electronics | 9         | 10     | 10.23%  |
| Hitachi             | 9         | 10     | 10.23%  |
| SanDisk             | 8         | 9      | 9.09%   |
| HGST                | 4         | 4      | 4.55%   |
| A-DATA Technology   | 3         | 3      | 3.41%   |
| SK hynix            | 2         | 2      | 2.27%   |
| LITEON              | 2         | 2      | 2.27%   |
| Kingston            | 2         | 3      | 2.27%   |
| Intel               | 2         | 2      | 2.27%   |
| XUM                 | 1         | 1      | 1.14%   |
| SPCC                | 1         | 1      | 1.14%   |
| Plextor             | 1         | 1      | 1.14%   |
| Micron Technology   | 1         | 1      | 1.14%   |
| Intenso             | 1         | 1      | 1.14%   |
| Hewlett-Packard     | 1         | 1      | 1.14%   |
| Fujitsu             | 1         | 1      | 1.14%   |
| Crucial             | 1         | 1      | 1.14%   |
| CLOVER              | 1         | 1      | 1.14%   |
| China               | 1         | 1      | 1.14%   |
| Unknown             | 1         | 1      | 1.14%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 17        | 21     | 29.31%  |
| WDC                 | 10        | 10     | 17.24%  |
| Toshiba             | 9         | 9      | 15.52%  |
| Hitachi             | 9         | 10     | 15.52%  |
| Samsung Electronics | 7         | 7      | 12.07%  |
| HGST                | 4         | 4      | 6.9%    |
| Fujitsu             | 1         | 1      | 1.72%   |
| CLOVER              | 1         | 1      | 1.72%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 52        | 63     | 63.41%  |
| SSD  | 24        | 27     | 29.27%  |
| NVMe | 6         | 6      | 7.32%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                       | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC WD5000AADS-00S9B0 500GB | 1         | 1      | 33.33%  |
| Toshiba MK2565GSXN 250GB    | 1         | 1      | 33.33%  |
| Intenso SSD SATAIII 512GB   | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Toshiba | 1         | 1      | 33.33%  |
| Intenso | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 394       | 546    | 45.92%  |
| Detected | 384       | 641    | 44.76%  |
| Malfunc  | 77        | 96     | 8.97%   |
| Failed   | 3         | 3      | 0.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 484       | 50.42%  |
| AMD                            | 117       | 12.19%  |
| Samsung Electronics            | 103       | 10.73%  |
| SanDisk                        | 57        | 5.94%   |
| SK hynix                       | 39        | 4.06%   |
| Kingston Technology Company    | 28        | 2.92%   |
| Micron Technology              | 25        | 2.6%    |
| KIOXIA                         | 15        | 1.56%   |
| Toshiba America Info Systems   | 11        | 1.15%   |
| Silicon Motion                 | 10        | 1.04%   |
| Micron/Crucial Technology      | 9         | 0.94%   |
| ADATA Technology               | 9         | 0.94%   |
| Phison Electronics             | 8         | 0.83%   |
| Nvidia                         | 8         | 0.83%   |
| ASMedia Technology             | 8         | 0.83%   |
| Realtek Semiconductor          | 5         | 0.52%   |
| JMicron Technology             | 5         | 0.52%   |
| Yangtze Memory Technologies    | 3         | 0.31%   |
| Union Memory (Shenzhen)        | 2         | 0.21%   |
| Solidigm                       | 2         | 0.21%   |
| Marvell Technology Group       | 2         | 0.21%   |
| VIA Technologies               | 1         | 0.1%    |
| TenaFe                         | 1         | 0.1%    |
| Solid State Storage Technology | 1         | 0.1%    |
| Shenzhen Longsys Electronics   | 1         | 0.1%    |
| Netac Technology               | 1         | 0.1%    |
| MAXIO Technology (Hangzhou)    | 1         | 0.1%    |
| Hosin Global Electronics       | 1         | 0.1%    |
| Broadcom / LSI                 | 1         | 0.1%    |
| Biwin Storage Technology       | 1         | 0.1%    |
| Apple                          | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 79        | 7.31%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 54        | 5%      |
| Intel Volume Management Device NVMe RAID Controller                            | 51        | 4.72%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 35        | 3.24%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 34        | 3.15%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 34        | 3.15%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 25        | 2.31%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 24        | 2.22%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 22        | 2.04%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 19        | 1.76%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 18        | 1.67%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 18        | 1.67%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 16        | 1.48%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 15        | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 15        | 1.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 14        | 1.3%    |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 14        | 1.3%    |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 11        | 1.02%   |
| Intel Comet Lake SATA AHCI Controller                                          | 11        | 1.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 11        | 1.02%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 11        | 1.02%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 11        | 1.02%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 10        | 0.93%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 9         | 0.83%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 9         | 0.83%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 9         | 0.83%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 8         | 0.74%   |
| Intel Tiger Lake-LP SATA Controller                                            | 8         | 0.74%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 8         | 0.74%   |
| Intel Optane NVME SSD H10 with Solid State Storage [Teton Glacier]             | 8         | 0.74%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 8         | 0.74%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 8         | 0.74%   |
| AMD 500 Series Chipset SATA Controller                                         | 8         | 0.74%   |
| AMD 400 Series Chipset SATA Controller                                         | 8         | 0.74%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 7         | 0.65%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 7         | 0.65%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 7         | 0.65%   |
| Intel Tiger Lake SATA AHCI Controller                                          | 7         | 0.65%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 7         | 0.65%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 7         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 479       | 49.18%  |
| NVMe | 322       | 33.06%  |
| RAID | 100       | 10.27%  |
| IDE  | 71        | 7.29%   |
| SAS  | 2         | 0.21%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 597       | 78.86%  |
| AMD    | 157       | 20.74%  |
| ARM    | 3         | 0.4%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz | 15        | 1.98%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz | 15        | 1.98%   |
| Intel Core i5-2520M CPU @ 2.50GHz       | 11        | 1.45%   |
| Intel Core i5-8265U CPU @ 1.60GHz       | 9         | 1.19%   |
| Intel Core i5-8250U CPU @ 1.60GHz       | 9         | 1.19%   |
| Intel Core i5-3210M CPU @ 2.50GHz       | 9         | 1.19%   |
| Intel Core i7-8565U CPU @ 1.80GHz       | 8         | 1.06%   |
| Intel Core i5-6200U CPU @ 2.30GHz       | 8         | 1.06%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz | 8         | 1.06%   |
| Intel Core i7-9750H CPU @ 2.60GHz       | 7         | 0.92%   |
| Intel Core i7-8550U CPU @ 1.80GHz       | 7         | 0.92%   |
| Intel Core i7-10750H CPU @ 2.60GHz      | 7         | 0.92%   |
| Intel Core i5-10300H CPU @ 2.50GHz      | 7         | 0.92%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz | 7         | 0.92%   |
| AMD Ryzen 7 5700U with Radeon Graphics  | 7         | 0.92%   |
| Intel Core i5-8365U CPU @ 1.60GHz       | 6         | 0.79%   |
| Intel Core i5-3320M CPU @ 2.60GHz       | 6         | 0.79%   |
| Intel Core i5-10210U CPU @ 1.60GHz      | 6         | 0.79%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz      | 6         | 0.79%   |
| Intel 12th Gen Core i7-12700H           | 6         | 0.79%   |
| Intel Core i7-6500U CPU @ 2.50GHz       | 5         | 0.66%   |
| Intel Core i7-2600 CPU @ 3.40GHz        | 5         | 0.66%   |
| Intel Core i5-8350U CPU @ 1.70GHz       | 5         | 0.66%   |
| Intel Core i5-7400 CPU @ 3.00GHz        | 5         | 0.66%   |
| Intel Core i5-2450M CPU @ 2.50GHz       | 5         | 0.66%   |
| Intel Core i3-5005U CPU @ 2.00GHz       | 5         | 0.66%   |
| Intel 12th Gen Core i7-1260P            | 5         | 0.66%   |
| Intel 12th Gen Core i7-1255U            | 5         | 0.66%   |
| Intel 12th Gen Core i5-12500H           | 5         | 0.66%   |
| Intel 12th Gen Core i5-1235U            | 5         | 0.66%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz | 5         | 0.66%   |
| AMD Ryzen 7 5800H with Radeon Graphics  | 5         | 0.66%   |
| AMD Ryzen 7 4800H with Radeon Graphics  | 5         | 0.66%   |
| AMD FX-6300 Six-Core Processor          | 5         | 0.66%   |
| Intel Core i7-8750H CPU @ 2.20GHz       | 4         | 0.53%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz      | 4         | 0.53%   |
| Intel Core i7-7500U CPU @ 2.70GHz       | 4         | 0.53%   |
| Intel Core i5-7200U CPU @ 2.50GHz       | 4         | 0.53%   |
| Intel Core i5-6300U CPU @ 2.40GHz       | 4         | 0.53%   |
| Intel Core i5-5300U CPU @ 2.30GHz       | 4         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 177       | 23.38%  |
| Intel Core i7           | 140       | 18.49%  |
| Other                   | 129       | 17.04%  |
| Intel Core i3           | 60        | 7.93%   |
| AMD Ryzen 7             | 41        | 5.42%   |
| AMD Ryzen 5             | 37        | 4.89%   |
| Intel Celeron           | 26        | 3.43%   |
| Intel Core 2 Duo        | 20        | 2.64%   |
| AMD FX                  | 12        | 1.59%   |
| AMD A6                  | 11        | 1.45%   |
| Intel Pentium           | 10        | 1.32%   |
| AMD Ryzen 3             | 10        | 1.32%   |
| Intel Xeon              | 7         | 0.92%   |
| Intel Pentium Dual-Core | 6         | 0.79%   |
| AMD Ryzen 9             | 6         | 0.79%   |
| AMD A4                  | 6         | 0.79%   |
| Intel Core              | 5         | 0.66%   |
| Intel Core i9           | 4         | 0.53%   |
| Intel Core 2            | 4         | 0.53%   |
| Intel Pentium Silver    | 3         | 0.4%    |
| Intel Core 2 Quad       | 3         | 0.4%    |
| Intel Atom              | 3         | 0.4%    |
| AMD Phenom II X4        | 3         | 0.4%    |
| AMD E1                  | 3         | 0.4%    |
| AMD Ryzen Threadripper  | 2         | 0.26%   |
| AMD Ryzen 7 PRO         | 2         | 0.26%   |
| AMD Ryzen 5 PRO         | 2         | 0.26%   |
| AMD E                   | 2         | 0.26%   |
| AMD Athlon II X2        | 2         | 0.26%   |
| AMD A8                  | 2         | 0.26%   |
| AMD A10                 | 2         | 0.26%   |
| Intel Pentium Dual      | 1         | 0.13%   |
| Intel Pentium D         | 1         | 0.13%   |
| Intel Genuine           | 1         | 0.13%   |
| Intel Core m5           | 1         | 0.13%   |
| Intel Core m3           | 1         | 0.13%   |
| Intel Core M            | 1         | 0.13%   |
| Intel Core 2 Extreme    | 1         | 0.13%   |
| AMD Sempron             | 1         | 0.13%   |
| AMD Phenom              | 1         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 285       | 37.65%  |
| 4      | 259       | 34.21%  |
| 6      | 72        | 9.51%   |
| 8      | 56        | 7.4%    |
| 12     | 25        | 3.3%    |
| 10     | 25        | 3.3%    |
| 14     | 13        | 1.72%   |
| 16     | 8         | 1.06%   |
| 1      | 8         | 1.06%   |
| 3      | 4         | 0.53%   |
| 24     | 2         | 0.26%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 754       | 99.6%   |
| 2      | 3         | 0.4%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 543       | 71.64%  |
| 1      | 214       | 28.23%  |
| 8      | 1         | 0.13%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 752       | 99.34%  |
| Unknown        | 5         | 0.66%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 440       | 56.85%  |
| 0x206a7    | 29        | 3.75%   |
| 0x806c1    | 22        | 2.84%   |
| 0x306a9    | 21        | 2.71%   |
| 0x906a3    | 19        | 2.45%   |
| 0x806ec    | 17        | 2.2%    |
| 0x406e3    | 15        | 1.94%   |
| 0xa0652    | 11        | 1.42%   |
| 0x906ea    | 10        | 1.29%   |
| 0x906a4    | 10        | 1.29%   |
| 0x806e9    | 10        | 1.29%   |
| 0x806ea    | 9         | 1.16%   |
| 0x306c3    | 9         | 1.16%   |
| 0x906e9    | 8         | 1.03%   |
| 0x706a8    | 7         | 0.9%    |
| 0x40651    | 7         | 0.9%    |
| 0x1067a    | 7         | 0.9%    |
| 0x0a50000c | 7         | 0.9%    |
| 0x08108109 | 7         | 0.9%    |
| 0x806d1    | 6         | 0.78%   |
| 0x706e5    | 5         | 0.65%   |
| 0x08608103 | 5         | 0.65%   |
| 0x08600106 | 5         | 0.65%   |
| 0x06006705 | 5         | 0.65%   |
| 0x06000852 | 5         | 0.65%   |
| 0x6f6      | 4         | 0.52%   |
| 0x406c4    | 4         | 0.52%   |
| 0x306d4    | 4         | 0.52%   |
| 0x90672    | 3         | 0.39%   |
| 0x07030105 | 3         | 0.39%   |
| 0x03000027 | 3         | 0.39%   |
| 0x010000c8 | 3         | 0.39%   |
| 0xb06a2    | 2         | 0.26%   |
| 0xb0671    | 2         | 0.26%   |
| 0x906ed    | 2         | 0.26%   |
| 0x806eb    | 2         | 0.26%   |
| 0x806c2    | 2         | 0.26%   |
| 0x706a1    | 2         | 0.26%   |
| 0x6fd      | 2         | 0.26%   |
| 0x506c9    | 2         | 0.26%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KabyLake          | 125       | 16.51%  |
| SandyBridge       | 57        | 7.53%   |
| Haswell           | 57        | 7.53%   |
| Alderlake Hybrid  | 50        | 6.61%   |
| Unknown           | 49        | 6.47%   |
| IvyBridge         | 47        | 6.21%   |
| TigerLake         | 46        | 6.08%   |
| Skylake           | 38        | 5.02%   |
| Zen 3             | 27        | 3.57%   |
| Penryn            | 26        | 3.43%   |
| CometLake         | 26        | 3.43%   |
| Zen+              | 22        | 2.91%   |
| IceLake           | 22        | 2.91%   |
| Broadwell         | 21        | 2.77%   |
| Zen 2             | 17        | 2.25%   |
| Piledriver        | 16        | 2.11%   |
| Silvermont        | 15        | 1.98%   |
| Goldmont plus     | 13        | 1.72%   |
| Core              | 13        | 1.72%   |
| Excavator         | 12        | 1.59%   |
| Zen               | 10        | 1.32%   |
| K10               | 9         | 1.19%   |
| Westmere          | 8         | 1.06%   |
| K10 Llano         | 5         | 0.66%   |
| Nehalem           | 4         | 0.53%   |
| Meteorlake Hybrid | 4         | 0.53%   |
| Jaguar            | 4         | 0.53%   |
| Puma              | 3         | 0.4%    |
| Goldmont          | 3         | 0.4%    |
| Bobcat            | 3         | 0.4%    |
| K8 Hammer         | 2         | 0.26%   |
| Steamroller       | 1         | 0.13%   |
| NetBurst          | 1         | 0.13%   |
| K8 & K10 hybrid   | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Intel            | 524       | 54.75%  |
| Nvidia           | 247       | 25.81%  |
| AMD              | 185       | 19.33%  |
| ATI Technologies | 1         | 0.1%    |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 45        | 4.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 38        | 3.93%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 33        | 3.41%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 26        | 2.69%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 25        | 2.58%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 24        | 2.48%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 24        | 2.48%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 22        | 2.27%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 22        | 2.27%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 18        | 1.86%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 17        | 1.76%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 16        | 1.65%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 16        | 1.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 15        | 1.55%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 14        | 1.45%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 14        | 1.45%   |
| AMD Lucienne                                                                             | 13        | 1.34%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 12        | 1.24%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 12        | 1.24%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 11        | 1.14%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 11        | 1.14%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 10        | 1.03%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 1.03%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 10        | 1.03%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 10        | 1.03%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 9         | 0.93%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 8         | 0.83%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 8         | 0.83%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 8         | 0.83%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 7         | 0.72%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 7         | 0.72%   |
| Intel Core Processor Integrated Graphics Controller                                      | 7         | 0.72%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 0.72%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 7         | 0.72%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 6         | 0.62%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 6         | 0.62%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                               | 6         | 0.62%   |
| Intel Kaby Lake-S GT2 [HD Graphics 630]                                                  | 6         | 0.62%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 6         | 0.62%   |
| AMD Barcelo                                                                              | 6         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 338       | 44.42%  |
| Intel + Nvidia | 144       | 18.92%  |
| 1 x AMD        | 138       | 18.13%  |
| 1 x Nvidia     | 85        | 11.17%  |
| Intel + AMD    | 22        | 2.89%   |
| AMD + Nvidia   | 20        | 2.63%   |
| 2 x AMD        | 6         | 0.79%   |
| Other          | 4         | 0.53%   |
| 2 x Intel      | 3         | 0.39%   |
| 2 x Nvidia     | 1         | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 670       | 88.16%  |
| Proprietary | 67        | 8.82%   |
| Unknown     | 23        | 3.03%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 570       | 74.61%  |
| 1.01-2.0   | 43        | 5.63%   |
| 0.01-0.5   | 41        | 5.37%   |
| 3.01-4.0   | 37        | 4.84%   |
| 0.51-1.0   | 29        | 3.8%    |
| 7.01-8.0   | 19        | 2.49%   |
| 5.01-6.0   | 16        | 2.09%   |
| 2.01-3.0   | 4         | 0.52%   |
| 8.01-16.0  | 4         | 0.52%   |
| 16.01-24.0 | 1         | 0.13%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 125       | 15.02%  |
| BOE                     | 106       | 12.74%  |
| LG Display              | 97        | 11.66%  |
| Chimei Innolux          | 92        | 11.06%  |
| Samsung Electronics     | 86        | 10.34%  |
| Dell                    | 37        | 4.45%   |
| Goldstar                | 25        | 3%      |
| Apple                   | 21        | 2.52%   |
| Sharp                   | 20        | 2.4%    |
| Hewlett-Packard         | 20        | 2.4%    |
| Acer                    | 20        | 2.4%    |
| BenQ                    | 13        | 1.56%   |
| InfoVision              | 12        | 1.44%   |
| Chi Mei Optoelectronics | 12        | 1.44%   |
| AOC                     | 12        | 1.44%   |
| Philips                 | 10        | 1.2%    |
| PANDA                   | 10        | 1.2%    |
| Ancor Communications    | 10        | 1.2%    |
| Unknown                 | 7         | 0.84%   |
| ViewSonic               | 6         | 0.72%   |
| Lenovo                  | 6         | 0.72%   |
| Iiyama                  | 6         | 0.72%   |
| Sony                    | 5         | 0.6%    |
| CSO                     | 5         | 0.6%    |
| Vizio                   | 4         | 0.48%   |
| Sceptre Tech            | 4         | 0.48%   |
| Panasonic               | 4         | 0.48%   |
| Toshiba                 | 3         | 0.36%   |
| NEC Computers           | 3         | 0.36%   |
| Eizo                    | 3         | 0.36%   |
| AUS                     | 3         | 0.36%   |
| ___                     | 2         | 0.24%   |
| STD                     | 2         | 0.24%   |
| STA                     | 2         | 0.24%   |
| Pixio                   | 2         | 0.24%   |
| Insignia                | 2         | 0.24%   |
| ASUSTek Computer        | 2         | 0.24%   |
| Unknown                 | 2         | 0.24%   |
| VOR                     | 1         | 0.12%   |
| VIZ                     | 1         | 0.12%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 8         | 0.94%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 7         | 0.82%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                 | 6         | 0.71%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch        | 5         | 0.59%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch          | 5         | 0.59%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch           | 5         | 0.59%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch            | 4         | 0.47%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch             | 4         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch         | 4         | 0.47%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch         | 4         | 0.47%   |
| BOE LCD Monitor BOE08A8 1920x1080 344x194mm 15.5-inch                   | 4         | 0.47%   |
| BOE LCD Monitor BOE0897 1366x768 344x194mm 15.5-inch                    | 4         | 0.47%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch          | 4         | 0.47%   |
| Sony TV SNYF301 1920x1080                                               | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 382x214mm 17.2-inch    | 3         | 0.35%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch   | 3         | 0.35%   |
| InfoVision LCD Monitor IVO8584 1920x1080 294x165mm 13.3-inch            | 3         | 0.35%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 3         | 0.35%   |
| BOE LCD Monitor BOE07C9 1920x1080 309x173mm 13.9-inch                   | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch          | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch          | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch           | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch           | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch           | 3         | 0.35%   |
| AU Optronics LCD Monitor AUO133D 1920x1080 309x173mm 13.9-inch          | 3         | 0.35%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                    | 3         | 0.35%   |
| Apple Color LCD APP9CC7 1280x800 286x179mm 13.3-inch                    | 3         | 0.35%   |
| ___ LCD TV ___9000 1360x768                                             | 2         | 0.24%   |
| Vizio E220VA VIZ0070 1920x1080 476x268mm 21.5-inch                      | 2         | 0.24%   |
| Unknown LCD Monitor XMD Mi TV 1360x768                                  | 2         | 0.24%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                        | 2         | 0.24%   |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch                 | 2         | 0.24%   |
| Samsung Electronics LF27T35 SAM707F 1920x1080 598x337mm 27.0-inch       | 2         | 0.24%   |
| Samsung Electronics LF24T35 SAM707D 1920x1080 528x297mm 23.9-inch       | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SEC4D45 1280x800 331x207mm 15.4-inch    | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SEC4D42 1280x800 303x190mm 14.1-inch    | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SEC3542 2160x1440 254x169mm 12.0-inch   | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SEC3150 1366x768 344x193mm 15.5-inch    | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SDC4951 1366x768 344x194mm 15.5-inch    | 2         | 0.24%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 2         | 0.24%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 384       | 48.24%  |
| 1366x768 (WXGA)    | 172       | 21.61%  |
| 3840x2160 (4K)     | 35        | 4.4%    |
| 1600x900 (HD+)     | 29        | 3.64%   |
| 1920x1200 (WUXGA)  | 25        | 3.14%   |
| 2560x1440 (QHD)    | 19        | 2.39%   |
| 1680x1050 (WSXGA+) | 19        | 2.39%   |
| 1280x1024 (SXGA)   | 17        | 2.14%   |
| 1280x800 (WXGA)    | 16        | 2.01%   |
| 1440x900 (WXGA+)   | 13        | 1.63%   |
| 2560x1600          | 8         | 1.01%   |
| 2560x1080          | 7         | 0.88%   |
| 1360x768           | 7         | 0.88%   |
| 2880x1800          | 6         | 0.75%   |
| 3440x1440          | 4         | 0.5%    |
| 2160x1440          | 4         | 0.5%    |
| 1920x540           | 4         | 0.5%    |
| Unknown            | 4         | 0.5%    |
| 3840x2400          | 3         | 0.38%   |
| 3840x1080          | 2         | 0.25%   |
| 3200x1080          | 2         | 0.25%   |
| 2240x1400          | 2         | 0.25%   |
| 1280x720 (HD)      | 2         | 0.25%   |
| 1024x768 (XGA)     | 2         | 0.25%   |
| 5200x1080          | 1         | 0.13%   |
| 3200x1800 (QHD+)   | 1         | 0.13%   |
| 3000x2000          | 1         | 0.13%   |
| 2944x1080          | 1         | 0.13%   |
| 2880x1920          | 1         | 0.13%   |
| 2880x1620          | 1         | 0.13%   |
| 2496x1664          | 1         | 0.13%   |
| 2400x1600          | 1         | 0.13%   |
| 1920x515           | 1         | 0.13%   |
| 1600x1200          | 1         | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 261       | 31.33%  |
| 14      | 90        | 10.8%   |
| 13      | 89        | 10.68%  |
| 17      | 53        | 6.36%   |
| 24      | 48        | 5.76%   |
| 27      | 34        | 4.08%   |
| Unknown | 28        | 3.36%   |
| 21      | 27        | 3.24%   |
| 23      | 26        | 3.12%   |
| 12      | 24        | 2.88%   |
| 31      | 23        | 2.76%   |
| 22      | 16        | 1.92%   |
| 16      | 15        | 1.8%    |
| 19      | 14        | 1.68%   |
| 11      | 13        | 1.56%   |
| 18      | 8         | 0.96%   |
| 84      | 7         | 0.84%   |
| 72      | 6         | 0.72%   |
| 34      | 6         | 0.72%   |
| 20      | 6         | 0.72%   |
| 40      | 5         | 0.6%    |
| 32      | 5         | 0.6%    |
| 54      | 3         | 0.36%   |
| 46      | 3         | 0.36%   |
| 42      | 3         | 0.36%   |
| 29      | 3         | 0.36%   |
| 26      | 3         | 0.36%   |
| 48      | 2         | 0.24%   |
| 47      | 2         | 0.24%   |
| 36      | 2         | 0.24%   |
| 74      | 1         | 0.12%   |
| 65      | 1         | 0.12%   |
| 63      | 1         | 0.12%   |
| 58      | 1         | 0.12%   |
| 52      | 1         | 0.12%   |
| 43      | 1         | 0.12%   |
| 41      | 1         | 0.12%   |
| 25      | 1         | 0.12%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 410       | 50%     |
| 501-600     | 101       | 12.32%  |
| 201-300     | 83        | 10.12%  |
| 401-500     | 61        | 7.44%   |
| 351-400     | 58        | 7.07%   |
| 601-700     | 28        | 3.41%   |
| Unknown     | 28        | 3.41%   |
| 1501-2000   | 14        | 1.71%   |
| 1001-1500   | 14        | 1.71%   |
| 701-800     | 13        | 1.59%   |
| 801-900     | 5         | 0.61%   |
| 901-1000    | 5         | 0.61%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 607       | 80.08%  |
| 16/10   | 89        | 11.74%  |
| Unknown | 19        | 2.51%   |
| 5/4     | 14        | 1.85%   |
| 3/2     | 8         | 1.06%   |
| 21/9    | 8         | 1.06%   |
| 4/3     | 7         | 0.92%   |
| 32/9    | 4         | 0.53%   |
| 6/5     | 1         | 0.13%   |
| 3.73    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 265       | 31.97%  |
| 81-90          | 140       | 16.89%  |
| 201-250        | 93        | 11.22%  |
| 71-80          | 40        | 4.83%   |
| 121-130        | 40        | 4.83%   |
| 301-350        | 37        | 4.46%   |
| 351-500        | 35        | 4.22%   |
| 151-200        | 30        | 3.62%   |
| Unknown        | 28        | 3.38%   |
| 61-70          | 23        | 2.77%   |
| More than 1000 | 22        | 2.65%   |
| 141-150        | 17        | 2.05%   |
| 501-1000       | 17        | 2.05%   |
| 251-300        | 15        | 1.81%   |
| 51-60          | 13        | 1.57%   |
| 111-120        | 11        | 1.33%   |
| 131-140        | 3         | 0.36%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 285       | 35.19%  |
| 51-100        | 196       | 24.2%   |
| 101-120       | 193       | 23.83%  |
| 161-240       | 66        | 8.15%   |
| Unknown       | 28        | 3.46%   |
| 1-50          | 25        | 3.09%   |
| More than 240 | 17        | 2.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 625       | 80.96%  |
| 2     | 117       | 15.16%  |
| 0     | 17        | 2.2%    |
| 3     | 13        | 1.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 418       | 33.44%  |
| Intel                                  | 413       | 33.04%  |
| Qualcomm Atheros                       | 112       | 8.96%   |
| Broadcom                               | 50        | 4%      |
| MediaTek                               | 38        | 3.04%   |
| Ralink Technology                      | 28        | 2.24%   |
| TP-Link                                | 25        | 2%      |
| Samsung Electronics                    | 17        | 1.36%   |
| Broadcom Limited                       | 16        | 1.28%   |
| Ralink                                 | 11        | 0.88%   |
| Qualcomm Atheros Communications        | 10        | 0.8%    |
| Xiaomi                                 | 9         | 0.72%   |
| NetGear                                | 8         | 0.64%   |
| ASIX Electronics                       | 8         | 0.64%   |
| Nvidia                                 | 7         | 0.56%   |
| Huawei Technologies                    | 6         | 0.48%   |
| Qualcomm                               | 5         | 0.4%    |
| Marvell Technology Group               | 5         | 0.4%    |
| ASUSTek Computer                       | 5         | 0.4%    |
| OPPO Electronics                       | 4         | 0.32%   |
| Microsoft                              | 4         | 0.32%   |
| Lenovo                                 | 4         | 0.32%   |
| Shenzhen Goodix Technology             | 3         | 0.24%   |
| Mercucys                               | 3         | 0.24%   |
| Linksys                                | 3         | 0.24%   |
| D-Link System                          | 3         | 0.24%   |
| vivo                                   | 2         | 0.16%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.16%   |
| Sierra Wireless                        | 2         | 0.16%   |
| OnePlus Technology (Shenzhen)          | 2         | 0.16%   |
| JMicron Technology                     | 2         | 0.16%   |
| ICS Advent                             | 2         | 0.16%   |
| Google                                 | 2         | 0.16%   |
| Ericsson Business Mobile Networks      | 2         | 0.16%   |
| D-Link                                 | 2         | 0.16%   |
| Aquantia                               | 2         | 0.16%   |
| Apple                                  | 2         | 0.16%   |
| ZyXEL Communications                   | 1         | 0.08%   |
| U-Blox                                 | 1         | 0.08%   |
| STMicroelectronics                     | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 250       | 16.64%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 48        | 3.2%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 37        | 2.46%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 36        | 2.4%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 36        | 2.4%    |
| Intel Wi-Fi 6 AX201                                                    | 32        | 2.13%   |
| Intel Wi-Fi 6 AX200                                                    | 26        | 1.73%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 25        | 1.66%   |
| Intel Wireless 8265 / 8275                                             | 25        | 1.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 21        | 1.4%    |
| Intel Wireless 7265                                                    | 21        | 1.4%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 21        | 1.4%    |
| Intel Comet Lake PCH CNVi WiFi                                         | 20        | 1.33%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 18        | 1.2%    |
| Realtek RTL8125 2.5GbE Controller                                      | 14        | 0.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 14        | 0.93%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 14        | 0.93%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 13        | 0.87%   |
| Intel Wireless 7260                                                    | 13        | 0.87%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 13        | 0.87%   |
| Realtek 802.11ac NIC                                                   | 12        | 0.8%    |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 12        | 0.8%    |
| Intel Wireless 8260                                                    | 12        | 0.8%    |
| Intel Ethernet Connection (4) I219-LM                                  | 12        | 0.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 11        | 0.73%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 11        | 0.73%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 11        | 0.73%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                     | 10        | 0.67%   |
| Qualcomm Atheros AR9271 802.11n                                        | 10        | 0.67%   |
| Intel Ethernet Controller I225-V                                       | 10        | 0.67%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 9         | 0.6%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 9         | 0.6%    |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 9         | 0.6%    |
| Realtek Killer E2600 GbE Controller                                    | 9         | 0.6%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 9         | 0.6%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 9         | 0.6%    |
| Intel Wireless 3165                                                    | 9         | 0.6%    |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]              | 9         | 0.6%    |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 8         | 0.53%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 8         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 337       | 43.71%  |
| Realtek Semiconductor           | 144       | 18.68%  |
| Qualcomm Atheros                | 89        | 11.54%  |
| Broadcom                        | 42        | 5.45%   |
| MediaTek                        | 33        | 4.28%   |
| Ralink Technology               | 28        | 3.63%   |
| TP-Link                         | 25        | 3.24%   |
| Broadcom Limited                | 13        | 1.69%   |
| Ralink                          | 11        | 1.43%   |
| Qualcomm Atheros Communications | 10        | 1.3%    |
| NetGear                         | 8         | 1.04%   |
| ASUSTek Computer                | 5         | 0.65%   |
| Microsoft                       | 4         | 0.52%   |
| Mercucys                        | 3         | 0.39%   |
| Marvell Technology Group        | 3         | 0.39%   |
| Linksys                         | 3         | 0.39%   |
| Sierra Wireless                 | 2         | 0.26%   |
| Qualcomm                        | 2         | 0.26%   |
| D-Link                          | 2         | 0.26%   |
| ZyXEL Communications            | 1         | 0.13%   |
| Sagem                           | 1         | 0.13%   |
| Gemtek                          | 1         | 0.13%   |
| Fibocom                         | 1         | 0.13%   |
| Dell                            | 1         | 0.13%   |
| D-Link System                   | 1         | 0.13%   |
| Belkin Components               | 1         | 0.13%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX201                                                  | 32        | 4.11%   |
| Intel Wi-Fi 6 AX200                                                  | 26        | 3.34%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter           | 25        | 3.21%   |
| Intel Wireless 8265 / 8275                                           | 25        | 3.21%   |
| Intel Alder Lake-P PCH CNVi WiFi                                     | 22        | 2.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter             | 21        | 2.7%    |
| Intel Wireless 7265                                                  | 21        | 2.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                         | 21        | 2.7%    |
| Intel Comet Lake PCH CNVi WiFi                                       | 20        | 2.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter           | 18        | 2.31%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                     | 14        | 1.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                    | 14        | 1.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter             | 13        | 1.67%   |
| Intel Wireless 7260                                                  | 13        | 1.67%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                             | 13        | 1.67%   |
| Realtek 802.11ac NIC                                                 | 12        | 1.54%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330] | 12        | 1.54%   |
| Intel Wireless 8260                                                  | 12        | 1.54%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter             | 11        | 1.41%   |
| Ralink RT2870/RT3070 Wireless Adapter                                | 11        | 1.41%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)       | 11        | 1.41%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                   | 10        | 1.28%   |
| Qualcomm Atheros AR9271 802.11n                                      | 10        | 1.28%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                         | 9         | 1.16%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                | 9         | 1.16%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter           | 9         | 1.16%   |
| Intel Wireless 3165                                                  | 9         | 1.16%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]            | 9         | 1.16%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                  | 8         | 1.03%   |
| Intel Tiger Lake PCH CNVi WiFi                                       | 8         | 1.03%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                      | 8         | 1.03%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter              | 7         | 0.9%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                      | 7         | 0.9%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter        | 7         | 0.9%    |
| Intel Raptor Lake PCH CNVi WiFi                                      | 7         | 0.9%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                     | 7         | 0.9%    |
| Intel Cannon Lake PCH CNVi WiFi                                      | 7         | 0.9%    |
| Broadcom Limited BCM4360 802.11ac Dual Band Wireless Network Adapter | 7         | 0.9%    |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                  | 6         | 0.77%   |
| Ralink MT7601U Wireless Adapter                                      | 6         | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 362       | 52.69%  |
| Intel                                  | 188       | 27.37%  |
| Qualcomm Atheros                       | 39        | 5.68%   |
| Samsung Electronics                    | 17        | 2.47%   |
| Broadcom                               | 15        | 2.18%   |
| Xiaomi                                 | 9         | 1.31%   |
| ASIX Electronics                       | 8         | 1.16%   |
| Nvidia                                 | 7         | 1.02%   |
| MediaTek                               | 5         | 0.73%   |
| OPPO Electronics                       | 4         | 0.58%   |
| Lenovo                                 | 4         | 0.58%   |
| Qualcomm                               | 3         | 0.44%   |
| Broadcom Limited                       | 3         | 0.44%   |
| vivo                                   | 2         | 0.29%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.29%   |
| Marvell Technology Group               | 2         | 0.29%   |
| JMicron Technology                     | 2         | 0.29%   |
| ICS Advent                             | 2         | 0.29%   |
| Huawei Technologies                    | 2         | 0.29%   |
| Google                                 | 2         | 0.29%   |
| D-Link System                          | 2         | 0.29%   |
| Aquantia                               | 2         | 0.29%   |
| Apple                                  | 2         | 0.29%   |
| Hewlett-Packard                        | 1         | 0.15%   |
| DisplayLink                            | 1         | 0.15%   |
| Davicom Semiconductor                  | 1         | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 250       | 35.31%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 48        | 6.78%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 37        | 5.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 36        | 5.08%   |
| Realtek RTL8125 2.5GbE Controller                                      | 14        | 1.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 14        | 1.98%   |
| Intel Ethernet Connection (4) I219-LM                                  | 12        | 1.69%   |
| Intel Ethernet Controller I225-V                                       | 10        | 1.41%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 9         | 1.27%   |
| Realtek Killer E2600 GbE Controller                                    | 9         | 1.27%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 8         | 1.13%   |
| Intel I211 Gigabit Network Connection                                  | 8         | 1.13%   |
| Intel Ethernet Connection I218-LM                                      | 8         | 1.13%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 7         | 0.99%   |
| Intel Ethernet Connection I219-LM                                      | 7         | 0.99%   |
| Intel Ethernet Connection (2) I219-V                                   | 7         | 0.99%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 6         | 0.85%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 6         | 0.85%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 6         | 0.85%   |
| Intel Ethernet Connection I217-LM                                      | 6         | 0.85%   |
| Intel Ethernet Connection (6) I219-V                                   | 6         | 0.85%   |
| Intel Ethernet Connection (6) I219-LM                                  | 6         | 0.85%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 5         | 0.71%   |
| Intel Ethernet Connection I217-V                                       | 5         | 0.71%   |
| Intel 82579V Gigabit Network Connection                                | 5         | 0.71%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 0.71%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 4         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 4         | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 0.56%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 4         | 0.56%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                                   | 3         | 0.42%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 3         | 0.42%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 3         | 0.42%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 3         | 0.42%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 3         | 0.42%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 3         | 0.42%   |
| Nvidia MCP79 Ethernet                                                  | 3         | 0.42%   |
| Nvidia MCP61 Ethernet                                                  | 3         | 0.42%   |
| Intel Ethernet Controller I226-V                                       | 3         | 0.42%   |
| Intel Ethernet Connection I219-V                                       | 3         | 0.42%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 668       | 51.11%  |
| Ethernet | 624       | 47.74%  |
| Modem    | 12        | 0.92%   |
| Unknown  | 3         | 0.23%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 518       | 66.07%  |
| Ethernet | 265       | 33.8%   |
| Unknown  | 1         | 0.13%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 436       | 57.37%  |
| 1     | 294       | 38.68%  |
| 3     | 14        | 1.84%   |
| 0     | 13        | 1.71%   |
| 4     | 2         | 0.26%   |
| 5     | 1         | 0.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 578       | 75.06%  |
| Yes     | 191       | 24.81%  |
| Unknown | 1         | 0.13%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 284       | 51.17%  |
| Realtek Semiconductor           | 59        | 10.63%  |
| Qualcomm Atheros Communications | 46        | 8.29%   |
| IMC Networks                    | 28        | 5.05%   |
| Broadcom                        | 22        | 3.96%   |
| Foxconn / Hon Hai               | 20        | 3.6%    |
| Apple                           | 20        | 3.6%    |
| Lite-On Technology              | 18        | 3.24%   |
| Cambridge Silicon Radio         | 18        | 3.24%   |
| MediaTek                        | 7         | 1.26%   |
| ASUSTek Computer                | 6         | 1.08%   |
| Dell                            | 5         | 0.9%    |
| Toshiba                         | 3         | 0.54%   |
| Realtek                         | 3         | 0.54%   |
| Marvell Semiconductor           | 3         | 0.54%   |
| TP-Link                         | 2         | 0.36%   |
| Ralink                          | 2         | 0.36%   |
| Hewlett-Packard                 | 2         | 0.36%   |
| Dynex                           | 2         | 0.36%   |
| USI                             | 1         | 0.18%   |
| Logitech                        | 1         | 0.18%   |
| Alps Electric                   | 1         | 0.18%   |
| Actions                         | 1         | 0.18%   |
| Unknown                         | 1         | 0.18%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel AX201 Bluetooth                               | 85        | 15.29%  |
| Intel Bluetooth wireless interface                  | 84        | 15.11%  |
| Realtek Bluetooth Radio                             | 39        | 7.01%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 36        | 6.47%   |
| Intel Bluetooth Device                              | 28        | 5.04%   |
| Qualcomm Atheros  Bluetooth Device                  | 25        | 4.5%    |
| Intel AX200 Bluetooth                               | 24        | 4.32%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 18        | 3.24%   |
| Realtek  Bluetooth 4.2 Adapter                      | 15        | 2.7%    |
| IMC Networks Wireless_Device                        | 13        | 2.34%   |
| Intel AX210 Bluetooth                               | 9         | 1.62%   |
| Apple Bluetooth Host Controller                     | 8         | 1.44%   |
| MediaTek Wireless_Device                            | 7         | 1.26%   |
| Intel Wireless-AC 3168 Bluetooth                    | 7         | 1.26%   |
| IMC Networks Bluetooth Device                       | 7         | 1.26%   |
| Foxconn / Hon Hai Wireless_Device                   | 7         | 1.26%   |
| Foxconn / Hon Hai Bluetooth Device                  | 7         | 1.26%   |
| Apple Bluetooth USB Host Controller                 | 7         | 1.26%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 1.08%   |
| IMC Networks Bluetooth Radio                        | 6         | 1.08%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 5         | 0.9%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 0.9%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 0.9%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 0.72%   |
| Lite-On Wireless_Device                             | 4         | 0.72%   |
| Dell DW375 Bluetooth Module                         | 4         | 0.72%   |
| Broadcom HP Portable SoftSailing                    | 4         | 0.72%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 4         | 0.72%   |
| Realtek RTL8821A Bluetooth                          | 3         | 0.54%   |
| Realtek Bluetooth Radio                             | 3         | 0.54%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.54%   |
| Qualcomm Atheros Bluetooth USB Host Controller      | 3         | 0.54%   |
| Qualcomm Atheros Bluetooth                          | 3         | 0.54%   |
| Broadcom BCM43142A0 Bluetooth Device                | 3         | 0.54%   |
| Broadcom BCM2045B (BDC-2.1)                         | 3         | 0.54%   |
| TP-Link TP-T@- UB500 Adapter                        | 2         | 0.36%   |
| Ralink RT3290 Bluetooth                             | 2         | 0.36%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.36%   |
| Marvell Bluetooth and Wireless LAN Composite Device | 2         | 0.36%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device        | 2         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 585       | 58.15%  |
| AMD                      | 181       | 17.99%  |
| Nvidia                   | 178       | 17.69%  |
| C-Media Electronics      | 12        | 1.19%   |
| Razer USA                | 4         | 0.4%    |
| JMTek                    | 4         | 0.4%    |
| Logitech                 | 3         | 0.3%    |
| GN Netcom                | 3         | 0.3%    |
| Creative Labs            | 3         | 0.3%    |
| Tenx Technology          | 2         | 0.2%    |
| Realtek Semiconductor    | 2         | 0.2%    |
| Micro Star International | 2         | 0.2%    |
| Generalplus Technology   | 2         | 0.2%    |
| Corsair                  | 2         | 0.2%    |
| Yamaha                   | 1         | 0.1%    |
| USB MICROPHONE           | 1         | 0.1%    |
| Texas Instruments        | 1         | 0.1%    |
| SteelSeries ApS          | 1         | 0.1%    |
| Samson Technologies      | 1         | 0.1%    |
| Plantronics              | 1         | 0.1%    |
| Microdia                 | 1         | 0.1%    |
| Medeli Electronics       | 1         | 0.1%    |
| Mackie Designs           | 1         | 0.1%    |
| Lenovo                   | 1         | 0.1%    |
| Kingston Technology      | 1         | 0.1%    |
| GYROCOM C&C              | 1         | 0.1%    |
| Guillemot                | 1         | 0.1%    |
| Focusrite-Novation       | 1         | 0.1%    |
| fifine Microphones       | 1         | 0.1%    |
| FDUCE PRO AUDIO MADE     | 1         | 0.1%    |
| Conexant Systems         | 1         | 0.1%    |
| Cambridge Silicon Radio  | 1         | 0.1%    |
| BY EDIFIER 0819          | 1         | 0.1%    |
| ATI Technologies         | 1         | 0.1%    |
| ASUSTek Computer         | 1         | 0.1%    |
| Apple                    | 1         | 0.1%    |
| Anker                    | 1         | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 76        | 6.31%   |
| Intel Sunrise Point-LP HD Audio                                            | 72        | 5.98%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 51        | 4.23%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 51        | 4.23%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 46        | 3.82%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 42        | 3.49%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 41        | 3.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 27        | 2.24%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 26        | 2.16%   |
| Intel Haswell-ULT HD Audio Controller                                      | 24        | 1.99%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 24        | 1.99%   |
| Intel 8 Series HD Audio Controller                                         | 24        | 1.99%   |
| Intel Comet Lake PCH cAVS                                                  | 23        | 1.91%   |
| Intel Cannon Lake PCH cAVS                                                 | 23        | 1.91%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 22        | 1.83%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 20        | 1.66%   |
| Intel Broadwell-U Audio Controller                                         | 20        | 1.66%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 20        | 1.66%   |
| AMD FCH Azalia Controller                                                  | 19        | 1.58%   |
| Nvidia GA106 High Definition Audio Controller                              | 18        | 1.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 16        | 1.33%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 15        | 1.24%   |
| Intel Comet Lake PCH-LP cAVS                                               | 15        | 1.24%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 15        | 1.24%   |
| Nvidia GA104 High Definition Audio Controller                              | 14        | 1.16%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 14        | 1.16%   |
| Nvidia GA107 High Definition Audio Controller                              | 13        | 1.08%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 13        | 1.08%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 12        | 1%      |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 12        | 1%      |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 12        | 1%      |
| Nvidia TU106 High Definition Audio Controller                              | 11        | 0.91%   |
| AMD Starship/Matisse HD Audio Controller                                   | 11        | 0.91%   |
| AMD Radeon High Definition Audio Controller                                | 11        | 0.91%   |
| Nvidia TU116 High Definition Audio Controller                              | 10        | 0.83%   |
| Nvidia GP107GL High Definition Audio Controller                            | 10        | 0.83%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 10        | 0.83%   |
| AMD Kabini HDMI/DP Audio                                                   | 10        | 0.83%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 10        | 0.83%   |
| Intel Alder Lake-S HD Audio Controller                                     | 9         | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 151       | 26.87%  |
| SK hynix            | 94        | 16.73%  |
| Micron Technology   | 80        | 14.23%  |
| Kingston            | 45        | 8.01%   |
| Crucial             | 39        | 6.94%   |
| Unknown             | 30        | 5.34%   |
| Corsair             | 21        | 3.74%   |
| Elpida              | 13        | 2.31%   |
| A-DATA Technology   | 13        | 2.31%   |
| Ramaxel Technology  | 11        | 1.96%   |
| Team                | 8         | 1.42%   |
| G.Skill             | 8         | 1.42%   |
| Unknown (ABCD)      | 7         | 1.25%   |
| Unknown             | 7         | 1.25%   |
| Nanya Technology    | 6         | 1.07%   |
| PNY                 | 5         | 0.89%   |
| Smart               | 3         | 0.53%   |
| Transcend           | 2         | 0.36%   |
| Avant               | 2         | 0.36%   |
| Unknown (0x0080)    | 1         | 0.18%   |
| Unifosa             | 1         | 0.18%   |
| Timetec             | 1         | 0.18%   |
| Teikon              | 1         | 0.18%   |
| TeamGroup           | 1         | 0.18%   |
| TBD                 | 1         | 0.18%   |
| Silicon Power       | 1         | 0.18%   |
| Saikano             | 1         | 0.18%   |
| S                   | 1         | 0.18%   |
| Ramos Technology    | 1         | 0.18%   |
| Patriot             | 1         | 0.18%   |
| Lexar Co Limited    | 1         | 0.18%   |
| Lexar               | 1         | 0.18%   |
| fef5                | 1         | 0.18%   |
| ChangXin Memory     | 1         | 0.18%   |
| Asgard              | 1         | 0.18%   |
| AMD                 | 1         | 0.18%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 12        | 2.04%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 1.7%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 1.36%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 7         | 1.19%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 7         | 1.19%   |
| Unknown                                                          | 7         | 1.19%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 3200MT/s            | 6         | 1.02%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 5         | 0.85%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.85%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 5         | 0.85%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.68%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 4         | 0.68%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 4         | 0.68%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 4         | 0.68%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 4         | 0.68%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 3         | 0.51%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 0.51%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 3         | 0.51%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 3         | 0.51%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.51%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.51%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 3         | 0.51%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 3         | 0.51%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 3         | 0.51%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 3         | 0.51%   |
| Samsung RAM M471A1K43BB1-CTD 8GB SODIMM DDR4 2667MT/s            | 3         | 0.51%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.51%   |
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 3         | 0.51%   |
| Samsung RAM M425R1GB4BB0-CWMOD 8GB SODIMM DDR5 5600MT/s          | 3         | 0.51%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.51%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 0.51%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 3         | 0.51%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 3         | 0.51%   |
| Micron RAM 16ATF2G64HZ-2G6E1 16GB SODIMM DDR4 2667MT/s           | 3         | 0.51%   |
| Crucial RAM CT8G4SFRA32A.M4FE 8GB SODIMM DDR4 3200MT/s           | 3         | 0.51%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 3         | 0.51%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 2         | 0.34%   |
| Unknown RAM Module 4GB DIMM DDR3 1600MT/s                        | 2         | 0.34%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 2         | 0.34%   |
| Transcend RAM JM1333KSN-4G 4GB SODIMM DDR3 1334MT/s              | 2         | 0.34%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 236       | 48.96%  |
| DDR3    | 138       | 28.63%  |
| LPDDR4  | 31        | 6.43%   |
| DDR5    | 19        | 3.94%   |
| LPDDR3  | 15        | 3.11%   |
| Unknown | 14        | 2.9%    |
| LPDDR5  | 11        | 2.28%   |
| DDR2    | 9         | 1.87%   |
| SDRAM   | 7         | 1.45%   |
| DDR     | 2         | 0.41%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 333       | 69.67%  |
| DIMM         | 90        | 18.83%  |
| Row Of Chips | 49        | 10.25%  |
| Unknown      | 4         | 0.84%   |
| Chip         | 2         | 0.42%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 214       | 40.61%  |
| 4096  | 131       | 24.86%  |
| 16384 | 90        | 17.08%  |
| 2048  | 43        | 8.16%   |
| 32768 | 32        | 6.07%   |
| 1024  | 16        | 3.04%   |
| 65536 | 1         | 0.19%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 123       | 23.43%  |
| 1600    | 99        | 18.86%  |
| 2667    | 79        | 15.05%  |
| 2400    | 33        | 6.29%   |
| 2133    | 23        | 4.38%   |
| 1333    | 18        | 3.43%   |
| 1334    | 15        | 2.86%   |
| 4800    | 13        | 2.48%   |
| 4267    | 12        | 2.29%   |
| 3600    | 12        | 2.29%   |
| 6400    | 11        | 2.1%    |
| 1867    | 11        | 2.1%    |
| 5600    | 7         | 1.33%   |
| 1067    | 6         | 1.14%   |
| Unknown | 6         | 1.14%   |
| 1066    | 5         | 0.95%   |
| 8400    | 4         | 0.76%   |
| 3800    | 4         | 0.76%   |
| 1800    | 4         | 0.76%   |
| 800     | 4         | 0.76%   |
| 667     | 4         | 0.76%   |
| 3733    | 3         | 0.57%   |
| 3266    | 3         | 0.57%   |
| 1866    | 3         | 0.57%   |
| 4266    | 2         | 0.38%   |
| 3466    | 2         | 0.38%   |
| 533     | 2         | 0.38%   |
| 12800   | 1         | 0.19%   |
| 7500    | 1         | 0.19%   |
| 6800    | 1         | 0.19%   |
| 6000    | 1         | 0.19%   |
| 4000    | 1         | 0.19%   |
| 3866    | 1         | 0.19%   |
| 3666    | 1         | 0.19%   |
| 3100    | 1         | 0.19%   |
| 3000    | 1         | 0.19%   |
| 2933    | 1         | 0.19%   |
| 2666    | 1         | 0.19%   |
| 2200    | 1         | 0.19%   |
| 2048    | 1         | 0.19%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 33.33%  |
| Brother Industries  | 3         | 33.33%  |
| Seiko Epson         | 1         | 11.11%  |
| Samsung Electronics | 1         | 11.11%  |
| Dymo-CoStar         | 1         | 11.11%  |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                        | Computers | Percent |
|------------------------------|-----------|---------|
| Seiko Epson L120 Series      | 1         | 11.11%  |
| Samsung ML-2850 Series       | 1         | 11.11%  |
| HP OfficeJet Pro 7720 series | 1         | 11.11%  |
| HP Deskjet 4640 series       | 1         | 11.11%  |
| HP Deskjet 2050 J510         | 1         | 11.11%  |
| Dymo-CoStar LabelWriter 450  | 1         | 11.11%  |
| Brother HL-5380DN series     | 1         | 11.11%  |
| Brother HL-1210W series      | 1         | 11.11%  |
| Brother DCP-T300             | 1         | 11.11%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Canon CanoScan N1240U/LiDE 30 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 121       | 22.16%  |
| IMC Networks                           | 57        | 10.44%  |
| Bison Electronics                      | 50        | 9.16%   |
| Microdia                               | 43        | 7.88%   |
| Quanta                                 | 35        | 6.41%   |
| Realtek Semiconductor                  | 32        | 5.86%   |
| Sunplus Innovation Technology          | 25        | 4.58%   |
| Apple                                  | 23        | 4.21%   |
| Luxvisions Innotech Limited            | 18        | 3.3%    |
| Syntek                                 | 17        | 3.11%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 2.56%   |
| Logitech                               | 13        | 2.38%   |
| Lite-On Technology                     | 12        | 2.2%    |
| Suyin                                  | 8         | 1.47%   |
| Silicon Motion                         | 8         | 1.47%   |
| Samsung Electronics                    | 8         | 1.47%   |
| Sonix Technology                       | 7         | 1.28%   |
| Ricoh                                  | 6         | 1.1%    |
| ShineTech                              | 4         | 0.73%   |
| icSpring                               | 4         | 0.73%   |
| Alcor Micro                            | 4         | 0.73%   |
| SunplusIT                              | 3         | 0.55%   |
| Microsoft                              | 3         | 0.55%   |
| Generalplus Technology                 | 3         | 0.55%   |
| Primax Electronics                     | 2         | 0.37%   |
| Motorola PCS                           | 2         | 0.37%   |
| LG Electronics                         | 2         | 0.37%   |
| Importek                               | 2         | 0.37%   |
| GEMBIRD                                | 2         | 0.37%   |
| Creative Technology                    | 2         | 0.37%   |
| ARC International                      | 2         | 0.37%   |
| Acer                                   | 2         | 0.37%   |
| USB Camera CS                          | 1         | 0.18%   |
| Tobii Technology AB                    | 1         | 0.18%   |
| Teslong Camera                         | 1         | 0.18%   |
| Razer USA                              | 1         | 0.18%   |
| Lenovo                                 | 1         | 0.18%   |
| Jieli Technology                       | 1         | 0.18%   |
| Jiangxi Shinetech Optical              | 1         | 0.18%   |
| Goertek Electronics                    | 1         | 0.18%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 23        | 4.19%   |
| IMC Networks USB2.0 HD UVC WebCam                    | 19        | 3.46%   |
| IMC Networks Integrated Camera                       | 16        | 2.91%   |
| Realtek Integrated_Webcam_HD                         | 15        | 2.73%   |
| Microdia Integrated_Webcam_HD                        | 12        | 2.19%   |
| Bison HD Webcam                                      | 12        | 2.19%   |
| Syntek Integrated Camera                             | 11        | 2%      |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                      | 11        | 2%      |
| Bison Integrated Camera                              | 10        | 1.82%   |
| Quanta HD User Facing                                | 9         | 1.64%   |
| Samsung Galaxy series, misc. (MTP mode)              | 8         | 1.46%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 8         | 1.46%   |
| Chicony HD WebCam                                    | 8         | 1.46%   |
| Chicony HD User Facing                               | 8         | 1.46%   |
| Chicony HP HD Camera                                 | 7         | 1.28%   |
| Sunplus Integrated_Webcam_HD                         | 6         | 1.09%   |
| Quanta HD Webcam                                     | 6         | 1.09%   |
| Chicony HP Truevision HD                             | 6         | 1.09%   |
| Bison SunplusIT Integrated Camera                    | 6         | 1.09%   |
| Realtek Integrated Webcam HD                         | 5         | 0.91%   |
| Quanta HP TrueVision HD Camera                       | 5         | 0.91%   |
| Microdia Integrated_Webcam_FHD                       | 5         | 0.91%   |
| Lite-On Integrated Camera                            | 5         | 0.91%   |
| Apple Built-in iSight                                | 5         | 0.91%   |
| Syntek Lenovo EasyCamera                             | 4         | 0.73%   |
| Sonix USB2.0 HD UVC WebCam                           | 4         | 0.73%   |
| ShineTech USB2.0 HD UVC WebCam                       | 4         | 0.73%   |
| Quanta HP HD Camera                                  | 4         | 0.73%   |
| Microdia Webcam Vitade AF                            | 4         | 0.73%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 4         | 0.73%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 4         | 0.73%   |
| icSpring camera                                      | 4         | 0.73%   |
| Chicony USB2.0 HD UVC WebCam                         | 4         | 0.73%   |
| Chicony Integrated Camera (1280x720@30)              | 4         | 0.73%   |
| Chicony EasyCamera                                   | 4         | 0.73%   |
| Chicony Chicony USB2.0 Camera                        | 4         | 0.73%   |
| Bison EasyCamera                                     | 4         | 0.73%   |
| Apple FaceTime HD Camera                             | 4         | 0.73%   |
| Sunplus ASUS Webcam                                  | 3         | 0.55%   |
| Sonix USB2.0 FHD UVC WebCam                          | 3         | 0.55%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 44        | 42.72%  |
| Validity Sensors           | 30        | 29.13%  |
| Shenzhen Goodix Technology | 11        | 10.68%  |
| Elan Microelectronics      | 7         | 6.8%    |
| Upek                       | 4         | 3.88%   |
| AuthenTec                  | 3         | 2.91%   |
| LighTuning Technology      | 2         | 1.94%   |
| Samsung Electronics        | 1         | 0.97%   |
| HOLTEK                     | 1         | 0.97%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 12        | 11.65%  |
| Shenzhen Goodix  Fingerprint Device                                        | 8         | 7.77%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 6         | 5.83%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 5         | 4.85%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 4.85%   |
| Synaptics Fingerprint reader [HP G6]                                       | 5         | 4.85%   |
| Elan ELAN:Fingerprint                                                      | 5         | 4.85%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 3.88%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 3.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 3.88%   |
| Synaptics WBDI                                                             | 4         | 3.88%   |
| Synaptics UWP WBDI Device                                                  | 4         | 3.88%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.91%   |
| Validity Sensors VFS491                                                    | 3         | 2.91%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 2.91%   |
| Synaptics UWP WBDI                                                         | 3         | 2.91%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 3         | 2.91%   |
| Synaptics  WBDI                                                            | 2         | 1.94%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 1.94%   |
| Shenzhen Goodix Fingerprint Reader                                         | 2         | 1.94%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.94%   |
| AuthenTec Fingerprint Sensor                                               | 2         | 1.94%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.97%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.97%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.97%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.97%   |
| Synaptics Prometheus Fingerprint Reader                                    | 1         | 0.97%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.97%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.97%   |
| Samsung Fingerprint Device                                                 | 1         | 0.97%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.97%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 0.97%   |
| HOLTEK FocalTech Fingerprint Device                                        | 1         | 0.97%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.97%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 23        | 60.53%  |
| Alcor Micro      | 10        | 26.32%  |
| SCM Microsystems | 2         | 5.26%   |
| Upek             | 1         | 2.63%   |
| OmniKey          | 1         | 2.63%   |
| O2 Micro         | 1         | 2.63%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 10        | 26.32%  |
| Broadcom BCM5880 Secure Applications Processor                               | 8         | 21.05%  |
| Broadcom 5880                                                                | 8         | 21.05%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 4         | 10.53%  |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 2         | 5.26%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 2.63%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 2.63%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 1         | 2.63%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 2.63%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.63%   |
| Broadcom 58200                                                               | 1         | 2.63%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 488       | 63.13%  |
| 1     | 233       | 30.14%  |
| 2     | 49        | 6.34%   |
| 3     | 2         | 0.26%   |
| 4     | 1         | 0.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 103       | 31.4%   |
| Graphics card            | 59        | 17.99%  |
| Net/wireless             | 46        | 14.02%  |
| Chipcard                 | 32        | 9.76%   |
| Multimedia controller    | 27        | 8.23%   |
| Net/ethernet             | 16        | 4.88%   |
| Camera                   | 15        | 4.57%   |
| Storage                  | 7         | 2.13%   |
| Communication controller | 5         | 1.52%   |
| Bluetooth                | 5         | 1.52%   |
| Network                  | 4         | 1.22%   |
| Sound                    | 3         | 0.91%   |
| Dvb card                 | 2         | 0.61%   |
| Unassigned class         | 1         | 0.3%    |
| Storage/raid             | 1         | 0.3%    |
| Modem                    | 1         | 0.3%    |
| Card reader              | 1         | 0.3%    |

