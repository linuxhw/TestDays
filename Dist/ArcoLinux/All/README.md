ArcoLinux - Tested Hardware & Statistics
----------------------------------------

A project to collect tested hardware configurations for ArcoLinux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/ArcoLinux/Desktop/README.md) and [notebooks](/Dist/ArcoLinux/Notebook/README.md).

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

Total: 1848

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HUAWEI        | HLYL-WXX9                   | Notebook    | [318010d949](https://linux-hardware.org/?probe=318010d949) | Oct 01, 2022 |
| Casper        | C15B                        | Desktop     | [be4c7469a6](https://linux-hardware.org/?probe=be4c7469a6) | Oct 01, 2022 |
| ASRock        | H87M Pro4                   | Desktop     | [bf8e635afa](https://linux-hardware.org/?probe=bf8e635afa) | Oct 01, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [5983281c3f](https://linux-hardware.org/?probe=5983281c3f) | Oct 01, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [f6e2c51367](https://linux-hardware.org/?probe=f6e2c51367) | Sep 30, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [e7ef06706d](https://linux-hardware.org/?probe=e7ef06706d) | Sep 30, 2022 |
| ASRock        | H87M Pro4                   | Desktop     | [f8bb8b6de8](https://linux-hardware.org/?probe=f8bb8b6de8) | Sep 30, 2022 |
| Lenovo        | ThinkPad X260 20F5S6P801    | Notebook    | [e948792d3d](https://linux-hardware.org/?probe=e948792d3d) | Sep 30, 2022 |
| TUXEDO        | Aura 15 Gen2                | Notebook    | [e8ebe97f13](https://linux-hardware.org/?probe=e8ebe97f13) | Sep 30, 2022 |
| Gigabyte      | P55-USB3                    | Desktop     | [adf7389f06](https://linux-hardware.org/?probe=adf7389f06) | Sep 30, 2022 |
| Gigabyte      | Z390 UD                     | Desktop     | [afe1282d38](https://linux-hardware.org/?probe=afe1282d38) | Sep 29, 2022 |
| Positivo B... | VJFE42F11X-XXXXXX           | Notebook    | [fdcdf06f55](https://linux-hardware.org/?probe=fdcdf06f55) | Sep 29, 2022 |
| Dell          | Latitude 3410               | Notebook    | [0f7ad40255](https://linux-hardware.org/?probe=0f7ad40255) | Sep 29, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [dc21fe6a18](https://linux-hardware.org/?probe=dc21fe6a18) | Sep 29, 2022 |
| ASRock        | B250M-HDV                   | Desktop     | [b248539946](https://linux-hardware.org/?probe=b248539946) | Sep 29, 2022 |
| HP            | 2B2C                        | Desktop     | [df8a8ec9bc](https://linux-hardware.org/?probe=df8a8ec9bc) | Sep 29, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [37a7291916](https://linux-hardware.org/?probe=37a7291916) | Sep 29, 2022 |
| ASUSTek       | ROG Strix G531GW_G531GW     | Notebook    | [113f7431d5](https://linux-hardware.org/?probe=113f7431d5) | Sep 28, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [cf8fefa8b5](https://linux-hardware.org/?probe=cf8fefa8b5) | Sep 28, 2022 |
| ASUSTek       | ROG Strix G531GW_G531GW     | Notebook    | [d0f2ed977a](https://linux-hardware.org/?probe=d0f2ed977a) | Sep 28, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [ecdbe4f54f](https://linux-hardware.org/?probe=ecdbe4f54f) | Sep 28, 2022 |
| Acer          | Aspire A715-75G             | Notebook    | [9489561c26](https://linux-hardware.org/?probe=9489561c26) | Sep 28, 2022 |
| Gigabyte      | AORUS 15P YD                | Notebook    | [61e297be71](https://linux-hardware.org/?probe=61e297be71) | Sep 28, 2022 |
| ASUSTek       | P8H61-M LE/CSM              | Desktop     | [45031620df](https://linux-hardware.org/?probe=45031620df) | Sep 27, 2022 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [4a86d53530](https://linux-hardware.org/?probe=4a86d53530) | Sep 25, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [59d0400171](https://linux-hardware.org/?probe=59d0400171) | Sep 24, 2022 |
| Gigabyte      | A320M-S2H V2-CF             | Desktop     | [71766e04c0](https://linux-hardware.org/?probe=71766e04c0) | Sep 23, 2022 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [3666836ba0](https://linux-hardware.org/?probe=3666836ba0) | Sep 23, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [6cb872fe4a](https://linux-hardware.org/?probe=6cb872fe4a) | Sep 22, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [832a8d1947](https://linux-hardware.org/?probe=832a8d1947) | Sep 22, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [03428c1a17](https://linux-hardware.org/?probe=03428c1a17) | Sep 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a06139b33d](https://linux-hardware.org/?probe=a06139b33d) | Sep 17, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [82ec942b27](https://linux-hardware.org/?probe=82ec942b27) | Sep 17, 2022 |
| Packard Be... | IMEDIA S3850                | Desktop     | [1fd4536a73](https://linux-hardware.org/?probe=1fd4536a73) | Sep 16, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [37681cbc64](https://linux-hardware.org/?probe=37681cbc64) | Sep 11, 2022 |
| ASUSTek       | E402BA                      | Notebook    | [e672656164](https://linux-hardware.org/?probe=e672656164) | Sep 10, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [6bb6224efd](https://linux-hardware.org/?probe=6bb6224efd) | Sep 10, 2022 |
| Gigabyte      | AERO 15-SA                  | Notebook    | [5ec761c633](https://linux-hardware.org/?probe=5ec761c633) | Sep 09, 2022 |
| ASUSTek       | ZenBook UX331FA_UX331FA     | Notebook    | [a877bbf17d](https://linux-hardware.org/?probe=a877bbf17d) | Sep 09, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [80a2ececa9](https://linux-hardware.org/?probe=80a2ececa9) | Sep 07, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [2850ddb81f](https://linux-hardware.org/?probe=2850ddb81f) | Sep 06, 2022 |
| System76      | Oryx Pro                    | Notebook    | [66f701b53f](https://linux-hardware.org/?probe=66f701b53f) | Sep 06, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a677e67805](https://linux-hardware.org/?probe=a677e67805) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [c1cc348ec8](https://linux-hardware.org/?probe=c1cc348ec8) | Sep 06, 2022 |
| System76      | Oryx Pro                    | Notebook    | [78adcc218f](https://linux-hardware.org/?probe=78adcc218f) | Sep 04, 2022 |
| System76      | Oryx Pro                    | Notebook    | [0113a2a928](https://linux-hardware.org/?probe=0113a2a928) | Sep 04, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [73b50385f0](https://linux-hardware.org/?probe=73b50385f0) | Sep 01, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [43835631c2](https://linux-hardware.org/?probe=43835631c2) | Sep 01, 2022 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [748558225a](https://linux-hardware.org/?probe=748558225a) | Aug 30, 2022 |
| Acer          | Predator G3-710             | Desktop     | [b14bf667d5](https://linux-hardware.org/?probe=b14bf667d5) | Aug 30, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IV... | Notebook    | [777f18537c](https://linux-hardware.org/?probe=777f18537c) | Aug 30, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [b85d2b0ec5](https://linux-hardware.org/?probe=b85d2b0ec5) | Aug 30, 2022 |
| Shuttle       | DS437                       | Notebook    | [9b866a79d6](https://linux-hardware.org/?probe=9b866a79d6) | Aug 27, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [a8b586b903](https://linux-hardware.org/?probe=a8b586b903) | Aug 27, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [da48ed6b65](https://linux-hardware.org/?probe=da48ed6b65) | Aug 27, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [86a305b6e7](https://linux-hardware.org/?probe=86a305b6e7) | Aug 26, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [21157a31fe](https://linux-hardware.org/?probe=21157a31fe) | Aug 26, 2022 |
| Samsung       | 550XDA                      | Notebook    | [505f5100d0](https://linux-hardware.org/?probe=505f5100d0) | Aug 25, 2022 |
| Gigabyte      | B365 M AORUS ELITE-CF       | Desktop     | [05a337504b](https://linux-hardware.org/?probe=05a337504b) | Aug 25, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [a6d3642195](https://linux-hardware.org/?probe=a6d3642195) | Aug 24, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [986bb07198](https://linux-hardware.org/?probe=986bb07198) | Aug 24, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [c7a1d435fb](https://linux-hardware.org/?probe=c7a1d435fb) | Aug 24, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [03ed2d6805](https://linux-hardware.org/?probe=03ed2d6805) | Aug 22, 2022 |
| HP            | 212B                        | Desktop     | [ba5bf87e58](https://linux-hardware.org/?probe=ba5bf87e58) | Aug 21, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [ba3fb2513f](https://linux-hardware.org/?probe=ba3fb2513f) | Aug 21, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [7ee8720a43](https://linux-hardware.org/?probe=7ee8720a43) | Aug 21, 2022 |
| HP            | 83EF                        | Desktop     | [6f964c19c3](https://linux-hardware.org/?probe=6f964c19c3) | Aug 21, 2022 |
| Unknown       | Unknown                     | Notebook    | [472eb48ecc](https://linux-hardware.org/?probe=472eb48ecc) | Aug 21, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [2a32a11841](https://linux-hardware.org/?probe=2a32a11841) | Aug 20, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [3b7d550ab9](https://linux-hardware.org/?probe=3b7d550ab9) | Aug 19, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [9b438d4bbf](https://linux-hardware.org/?probe=9b438d4bbf) | Aug 19, 2022 |
| Toshiba       | Satellite P55t-C            | Notebook    | [deac60d261](https://linux-hardware.org/?probe=deac60d261) | Aug 18, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [a6de4113fa](https://linux-hardware.org/?probe=a6de4113fa) | Aug 17, 2022 |
| Dell          | G7 7588                     | Notebook    | [246c96a8ae](https://linux-hardware.org/?probe=246c96a8ae) | Aug 16, 2022 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [ea53a9b42b](https://linux-hardware.org/?probe=ea53a9b42b) | Aug 16, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [d193a200da](https://linux-hardware.org/?probe=d193a200da) | Aug 16, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [d6e920456d](https://linux-hardware.org/?probe=d6e920456d) | Aug 16, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [a16dfdfe7b](https://linux-hardware.org/?probe=a16dfdfe7b) | Aug 15, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [abf9c78bdd](https://linux-hardware.org/?probe=abf9c78bdd) | Aug 15, 2022 |
| HP            | EliteBook 8540p             | Notebook    | [e2799ec7f9](https://linux-hardware.org/?probe=e2799ec7f9) | Aug 15, 2022 |
| Chuwi         | HeroBook Air                | Notebook    | [dcf4a63c1e](https://linux-hardware.org/?probe=dcf4a63c1e) | Aug 12, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [9e77f6044a](https://linux-hardware.org/?probe=9e77f6044a) | Aug 12, 2022 |
| Lenovo        | ThinkPad X240 20AL00BNRT    | Notebook    | [72139648d3](https://linux-hardware.org/?probe=72139648d3) | Aug 10, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [5ebbabea13](https://linux-hardware.org/?probe=5ebbabea13) | Aug 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cba8c9f4ac](https://linux-hardware.org/?probe=cba8c9f4ac) | Aug 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [55430614f9](https://linux-hardware.org/?probe=55430614f9) | Aug 10, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [93bd067b5d](https://linux-hardware.org/?probe=93bd067b5d) | Aug 09, 2022 |
| Lenovo        | ThinkPad T550 20CJS1MW00    | Notebook    | [490109686e](https://linux-hardware.org/?probe=490109686e) | Aug 07, 2022 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [cd51b4a39c](https://linux-hardware.org/?probe=cd51b4a39c) | Aug 06, 2022 |
| Xplore        | iX104C5                     | Notebook    | [6ef6194939](https://linux-hardware.org/?probe=6ef6194939) | Aug 06, 2022 |
| Lenovo        | Legion 5 15IMH05H 82CF      | Notebook    | [2f96d2d61a](https://linux-hardware.org/?probe=2f96d2d61a) | Aug 06, 2022 |
| Dell          | 0M9KCM A00                  | Desktop     | [b303a37caf](https://linux-hardware.org/?probe=b303a37caf) | Aug 05, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [afc72e5375](https://linux-hardware.org/?probe=afc72e5375) | Aug 04, 2022 |
| Gigabyte      | Z690 UD DDR4                | Desktop     | [3225b48633](https://linux-hardware.org/?probe=3225b48633) | Aug 03, 2022 |
| MSI           | A320M-HDV R4.0              | Desktop     | [76a5116e6f](https://linux-hardware.org/?probe=76a5116e6f) | Aug 03, 2022 |
| MSI           | A320M-HDV R4.0              | Desktop     | [d5d6bd6478](https://linux-hardware.org/?probe=d5d6bd6478) | Aug 03, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [5ab9ae3992](https://linux-hardware.org/?probe=5ab9ae3992) | Aug 03, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | Notebook    | [d3163f70f3](https://linux-hardware.org/?probe=d3163f70f3) | Aug 02, 2022 |
| Sony          | VPCF120FL                   | Notebook    | [75bd2bb218](https://linux-hardware.org/?probe=75bd2bb218) | Aug 02, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [5f41623898](https://linux-hardware.org/?probe=5f41623898) | Aug 01, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6A... | Notebook    | [76d752f0ad](https://linux-hardware.org/?probe=76d752f0ad) | Aug 01, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [2dee8f9fb1](https://linux-hardware.org/?probe=2dee8f9fb1) | Jul 31, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [458c2e644f](https://linux-hardware.org/?probe=458c2e644f) | Jul 31, 2022 |
| Dell          | Inspiron 5558               | Notebook    | [06b58ca667](https://linux-hardware.org/?probe=06b58ca667) | Jul 31, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [5a31407c67](https://linux-hardware.org/?probe=5a31407c67) | Jul 31, 2022 |
| Biostar       | J3060NH                     | Desktop     | [64ac6dadf2](https://linux-hardware.org/?probe=64ac6dadf2) | Jul 30, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [c2bcea4cf1](https://linux-hardware.org/?probe=c2bcea4cf1) | Jul 28, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [bfed86a5c4](https://linux-hardware.org/?probe=bfed86a5c4) | Jul 28, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [7c72a6289c](https://linux-hardware.org/?probe=7c72a6289c) | Jul 27, 2022 |
| System76      | Oryx Pro                    | Notebook    | [b55d1a9fe5](https://linux-hardware.org/?probe=b55d1a9fe5) | Jul 25, 2022 |
| System76      | Oryx Pro                    | Notebook    | [3b91037c6f](https://linux-hardware.org/?probe=3b91037c6f) | Jul 25, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [437ba53b68](https://linux-hardware.org/?probe=437ba53b68) | Jul 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [987aa33ced](https://linux-hardware.org/?probe=987aa33ced) | Jul 25, 2022 |
| Biostar       | J3060NH                     | Desktop     | [37eb1606ef](https://linux-hardware.org/?probe=37eb1606ef) | Jul 25, 2022 |
| Dell          | Inspiron 14 5401            | Notebook    | [eaf315be72](https://linux-hardware.org/?probe=eaf315be72) | Jul 24, 2022 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [d2379587b9](https://linux-hardware.org/?probe=d2379587b9) | Jul 21, 2022 |
| HP            | 3397                        | Desktop     | [017afa048c](https://linux-hardware.org/?probe=017afa048c) | Jul 20, 2022 |
| Biostar       | J3060NH                     | Desktop     | [ba16aba804](https://linux-hardware.org/?probe=ba16aba804) | Jul 20, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f5aba6ba0f](https://linux-hardware.org/?probe=f5aba6ba0f) | Jul 19, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d8852d71bf](https://linux-hardware.org/?probe=d8852d71bf) | Jul 18, 2022 |
| ASRock        | FM2A58M-VG3+ R2.0           | Desktop     | [04affeedf7](https://linux-hardware.org/?probe=04affeedf7) | Jul 18, 2022 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | Desktop     | [bafb527de8](https://linux-hardware.org/?probe=bafb527de8) | Jul 17, 2022 |
| HP            | Unknown                     | Notebook    | [01622a24ef](https://linux-hardware.org/?probe=01622a24ef) | Jul 17, 2022 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [3cc4a578df](https://linux-hardware.org/?probe=3cc4a578df) | Jul 17, 2022 |
| ASUSTek       | EX-B150M-V3                 | Desktop     | [f8585ad958](https://linux-hardware.org/?probe=f8585ad958) | Jul 17, 2022 |
| ASUSTek       | EX-B150M-V3                 | Desktop     | [f2372286e0](https://linux-hardware.org/?probe=f2372286e0) | Jul 17, 2022 |
| HP            | Notebook                    | Notebook    | [e5a1df8ba8](https://linux-hardware.org/?probe=e5a1df8ba8) | Jul 17, 2022 |
| System76      | Oryx Pro                    | Notebook    | [5cac9c78e6](https://linux-hardware.org/?probe=5cac9c78e6) | Jul 16, 2022 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [27741b20dd](https://linux-hardware.org/?probe=27741b20dd) | Jul 16, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [383c62eca2](https://linux-hardware.org/?probe=383c62eca2) | Jul 14, 2022 |
| System76      | Oryx Pro                    | Notebook    | [7cb7b3fd6a](https://linux-hardware.org/?probe=7cb7b3fd6a) | Jul 14, 2022 |
| Lenovo        | ThinkPad Yoga 260 20FES1... | Convertible | [a6c59d3803](https://linux-hardware.org/?probe=a6c59d3803) | Jul 14, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [2438f42e95](https://linux-hardware.org/?probe=2438f42e95) | Jul 13, 2022 |
| ASRock        | Z170 Gaming K4              | Desktop     | [a1bf65c2d7](https://linux-hardware.org/?probe=a1bf65c2d7) | Jul 12, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [b44d77c9a0](https://linux-hardware.org/?probe=b44d77c9a0) | Jul 12, 2022 |
| Dell          | Inspiron N5050              | Notebook    | [8002a8ec0f](https://linux-hardware.org/?probe=8002a8ec0f) | Jul 10, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [f3a1f552c8](https://linux-hardware.org/?probe=f3a1f552c8) | Jul 09, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [fb5a2ac873](https://linux-hardware.org/?probe=fb5a2ac873) | Jul 09, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [ec18f88382](https://linux-hardware.org/?probe=ec18f88382) | Jul 07, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [019c2b1194](https://linux-hardware.org/?probe=019c2b1194) | Jul 07, 2022 |
| HP            | 3397                        | Desktop     | [5f251b624d](https://linux-hardware.org/?probe=5f251b624d) | Jul 07, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [532bbca1f1](https://linux-hardware.org/?probe=532bbca1f1) | Jul 06, 2022 |
| ASUSTek       | S551LN                      | Notebook    | [1f47ada680](https://linux-hardware.org/?probe=1f47ada680) | Jul 06, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [06b9f15824](https://linux-hardware.org/?probe=06b9f15824) | Jul 06, 2022 |
| Acer          | Aspire V5-571G              | Notebook    | [8476e2e1c3](https://linux-hardware.org/?probe=8476e2e1c3) | Jul 06, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ab630b447f](https://linux-hardware.org/?probe=ab630b447f) | Jul 06, 2022 |
| Acer          | Aspire V5-571G              | Notebook    | [add34d1f6a](https://linux-hardware.org/?probe=add34d1f6a) | Jul 05, 2022 |
| ASUSTek       | Zephyrus M GU502GU_GU502... | Notebook    | [1773a0941f](https://linux-hardware.org/?probe=1773a0941f) | Jul 05, 2022 |
| Acer          | Aspire E5-576G              | Notebook    | [74f6e010da](https://linux-hardware.org/?probe=74f6e010da) | Jul 04, 2022 |
| Biostar       | J3060NH                     | Desktop     | [313e87f523](https://linux-hardware.org/?probe=313e87f523) | Jul 02, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [63da8fa3b9](https://linux-hardware.org/?probe=63da8fa3b9) | Jul 02, 2022 |
| Supermicro    | A2SAN-E-WOHSA               | Desktop     | [f8d0b19c1e](https://linux-hardware.org/?probe=f8d0b19c1e) | Jul 01, 2022 |
| MSI           | GL65 Leopard 10SEK          | Notebook    | [5043bf1cd4](https://linux-hardware.org/?probe=5043bf1cd4) | Jun 29, 2022 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [1b5babe2aa](https://linux-hardware.org/?probe=1b5babe2aa) | Jun 29, 2022 |
| System76      | Oryx Pro                    | Notebook    | [7fa7a1ca82](https://linux-hardware.org/?probe=7fa7a1ca82) | Jun 29, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [5ebcb2f152](https://linux-hardware.org/?probe=5ebcb2f152) | Jun 29, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [0fbd5ca967](https://linux-hardware.org/?probe=0fbd5ca967) | Jun 29, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [cf7b4fb7e1](https://linux-hardware.org/?probe=cf7b4fb7e1) | Jun 29, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [66a8fd4642](https://linux-hardware.org/?probe=66a8fd4642) | Jun 28, 2022 |
| Medion        | E7214                       | Notebook    | [439509e70a](https://linux-hardware.org/?probe=439509e70a) | Jun 28, 2022 |
| Biostar       | J3060NH                     | Desktop     | [6cefe763b7](https://linux-hardware.org/?probe=6cefe763b7) | Jun 28, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [af267c59cd](https://linux-hardware.org/?probe=af267c59cd) | Jun 28, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [23b355d820](https://linux-hardware.org/?probe=23b355d820) | Jun 27, 2022 |
| Toshiba       | Satellite Pro S300          | Notebook    | [09f9ef25cd](https://linux-hardware.org/?probe=09f9ef25cd) | Jun 27, 2022 |
| MSI           | B250 GAMING M3              | Desktop     | [b294a7b0b1](https://linux-hardware.org/?probe=b294a7b0b1) | Jun 26, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [0d16a3f2ce](https://linux-hardware.org/?probe=0d16a3f2ce) | Jun 26, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [11d7e1ecc7](https://linux-hardware.org/?probe=11d7e1ecc7) | Jun 26, 2022 |
| Intel Clie... | LAPKC71F                    | Notebook    | [6452ae1060](https://linux-hardware.org/?probe=6452ae1060) | Jun 26, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [e3fcc67ecc](https://linux-hardware.org/?probe=e3fcc67ecc) | Jun 26, 2022 |
| ASUSTek       | All Series                  | Notebook    | [19dde83002](https://linux-hardware.org/?probe=19dde83002) | Jun 26, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [c2fceb2c81](https://linux-hardware.org/?probe=c2fceb2c81) | Jun 24, 2022 |
| Dell          | Inspiron 5459               | Notebook    | [d3a3e2cf32](https://linux-hardware.org/?probe=d3a3e2cf32) | Jun 22, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [d8f9374e6c](https://linux-hardware.org/?probe=d8f9374e6c) | Jun 22, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [00495646c1](https://linux-hardware.org/?probe=00495646c1) | Jun 22, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [518331cc83](https://linux-hardware.org/?probe=518331cc83) | Jun 21, 2022 |
| Acer          | Aspire ES1-571              | Notebook    | [cfbc040f69](https://linux-hardware.org/?probe=cfbc040f69) | Jun 21, 2022 |
| Lenovo        | ThinkPad T420 4236EF4       | Notebook    | [1894bb8853](https://linux-hardware.org/?probe=1894bb8853) | Jun 21, 2022 |
| ASRock        | X299 Taichi CLX             | Desktop     | [ee5ad45d8b](https://linux-hardware.org/?probe=ee5ad45d8b) | Jun 21, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1D00... | Notebook    | [eacaed715b](https://linux-hardware.org/?probe=eacaed715b) | Jun 21, 2022 |
| Dell          | 0F896N A02                  | Desktop     | [223cbe95f4](https://linux-hardware.org/?probe=223cbe95f4) | Jun 20, 2022 |
| System76      | Oryx Pro                    | Notebook    | [c623d50d29](https://linux-hardware.org/?probe=c623d50d29) | Jun 20, 2022 |
| ASRock        | Z370 Extreme4               | Desktop     | [c971857c53](https://linux-hardware.org/?probe=c971857c53) | Jun 20, 2022 |
| MSI           | A320M PRO-M2                | Desktop     | [8ffdebb12e](https://linux-hardware.org/?probe=8ffdebb12e) | Jun 20, 2022 |
| Lenovo        | ThinkPad T420 4180DY4       | Notebook    | [bf292ae80a](https://linux-hardware.org/?probe=bf292ae80a) | Jun 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [1cf9eae6e5](https://linux-hardware.org/?probe=1cf9eae6e5) | Jun 20, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | Notebook    | [07821abe14](https://linux-hardware.org/?probe=07821abe14) | Jun 20, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [f9eddff413](https://linux-hardware.org/?probe=f9eddff413) | Jun 19, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [3ac49a6b54](https://linux-hardware.org/?probe=3ac49a6b54) | Jun 19, 2022 |
| PLEXHD        | X79 Turbo                   | Desktop     | [b93749f5e0](https://linux-hardware.org/?probe=b93749f5e0) | Jun 19, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [17e0b3e4c0](https://linux-hardware.org/?probe=17e0b3e4c0) | Jun 19, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [208e447fe1](https://linux-hardware.org/?probe=208e447fe1) | Jun 17, 2022 |
| Schenker      | VISION 15 (SVS15E21)        | Notebook    | [8845a2219f](https://linux-hardware.org/?probe=8845a2219f) | Jun 17, 2022 |
| Notebook      | PA70ES                      | Notebook    | [7024a9dc03](https://linux-hardware.org/?probe=7024a9dc03) | Jun 16, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [b018aaf572](https://linux-hardware.org/?probe=b018aaf572) | Jun 15, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [3074e50dff](https://linux-hardware.org/?probe=3074e50dff) | Jun 15, 2022 |
| ASRock        | X299 Taichi CLX             | Desktop     | [d349f8b0f5](https://linux-hardware.org/?probe=d349f8b0f5) | Jun 15, 2022 |
| HP            | ZBook Studio G3             | Notebook    | [0dda22b68b](https://linux-hardware.org/?probe=0dda22b68b) | Jun 12, 2022 |
| System76      | Oryx Pro                    | Notebook    | [8488dcacf9](https://linux-hardware.org/?probe=8488dcacf9) | Jun 11, 2022 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | Notebook    | [5d49ce7763](https://linux-hardware.org/?probe=5d49ce7763) | Jun 10, 2022 |
| Razer         | Blade                       | Notebook    | [2d8524dc81](https://linux-hardware.org/?probe=2d8524dc81) | Jun 10, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [f895a113f9](https://linux-hardware.org/?probe=f895a113f9) | Jun 09, 2022 |
| HP            | Laptop 14-dk1xxx            | Notebook    | [e29eb57530](https://linux-hardware.org/?probe=e29eb57530) | Jun 09, 2022 |
| Dell          | Latitude 5421               | Notebook    | [24665e8e4b](https://linux-hardware.org/?probe=24665e8e4b) | Jun 08, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [ee0fb46764](https://linux-hardware.org/?probe=ee0fb46764) | Jun 08, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [0b67cbecfc](https://linux-hardware.org/?probe=0b67cbecfc) | Jun 07, 2022 |
| HP            | Laptop 15-da1xxx            | Notebook    | [02f5bd70bb](https://linux-hardware.org/?probe=02f5bd70bb) | Jun 07, 2022 |
| Gigabyte      | Z370XP SLI-CF               | Desktop     | [23191e0c1d](https://linux-hardware.org/?probe=23191e0c1d) | Jun 07, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [8f5dae3cd7](https://linux-hardware.org/?probe=8f5dae3cd7) | Jun 06, 2022 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [b3a7546aa9](https://linux-hardware.org/?probe=b3a7546aa9) | Jun 06, 2022 |
| MSI           | H81M-P33                    | Desktop     | [b48f5d554f](https://linux-hardware.org/?probe=b48f5d554f) | Jun 05, 2022 |
| Dell          | 05XGC8 A01                  | Desktop     | [2a1316250b](https://linux-hardware.org/?probe=2a1316250b) | Jun 05, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [dc7a83708a](https://linux-hardware.org/?probe=dc7a83708a) | Jun 04, 2022 |
| ASUSTek       | GL703VD                     | Notebook    | [3a9d836e5e](https://linux-hardware.org/?probe=3a9d836e5e) | Jun 03, 2022 |
| ASUSTek       | GL703VD                     | Notebook    | [531d7297d9](https://linux-hardware.org/?probe=531d7297d9) | Jun 03, 2022 |
| ASUSTek       | ROG Strix G733ZX_G733ZX     | Notebook    | [dca80e1df5](https://linux-hardware.org/?probe=dca80e1df5) | Jun 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [4b11a98b62](https://linux-hardware.org/?probe=4b11a98b62) | May 31, 2022 |
| Biostar       | J3060NH                     | Desktop     | [e2d33f6c66](https://linux-hardware.org/?probe=e2d33f6c66) | May 31, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [606c1d3f8e](https://linux-hardware.org/?probe=606c1d3f8e) | May 31, 2022 |
| Gigabyte      | H110N-CF                    | Desktop     | [3a0b00c45d](https://linux-hardware.org/?probe=3a0b00c45d) | May 30, 2022 |
| System76      | Oryx Pro                    | Notebook    | [5f84134f5d](https://linux-hardware.org/?probe=5f84134f5d) | May 29, 2022 |
| Toshiba       | Satellite C675              | Notebook    | [72daf96a34](https://linux-hardware.org/?probe=72daf96a34) | May 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [7ca69b6206](https://linux-hardware.org/?probe=7ca69b6206) | May 28, 2022 |
| Biostar       | J3060NH                     | Desktop     | [2c67e6fc81](https://linux-hardware.org/?probe=2c67e6fc81) | May 28, 2022 |
| HP            | 2B36                        | Desktop     | [7a6bff3398](https://linux-hardware.org/?probe=7a6bff3398) | May 28, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [c025e27a90](https://linux-hardware.org/?probe=c025e27a90) | May 27, 2022 |
| Lenovo        | Yoga 7 16IAP7 82QG          | Convertible | [509fc21647](https://linux-hardware.org/?probe=509fc21647) | May 27, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | Desktop     | [a434348da9](https://linux-hardware.org/?probe=a434348da9) | May 26, 2022 |
| Dell          | 0RY007                      | Desktop     | [2d0a227175](https://linux-hardware.org/?probe=2d0a227175) | May 26, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [caaf2a56b6](https://linux-hardware.org/?probe=caaf2a56b6) | May 26, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [4976553dfc](https://linux-hardware.org/?probe=4976553dfc) | May 25, 2022 |
| System76      | Oryx Pro                    | Notebook    | [2652ac64a4](https://linux-hardware.org/?probe=2652ac64a4) | May 25, 2022 |
| Dell          | 0YJPT1 A00                  | Desktop     | [f4afc8ed1d](https://linux-hardware.org/?probe=f4afc8ed1d) | May 25, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [6e5dd6f76f](https://linux-hardware.org/?probe=6e5dd6f76f) | May 25, 2022 |
| Lenovo        | ThinkPad L540 20AV0031GE    | Notebook    | [13f326fc7d](https://linux-hardware.org/?probe=13f326fc7d) | May 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [7a1059d5cc](https://linux-hardware.org/?probe=7a1059d5cc) | May 25, 2022 |
| HP            | 86EE                        | All in one  | [0870a9cf1a](https://linux-hardware.org/?probe=0870a9cf1a) | May 24, 2022 |
| Toshiba       | PORTEGE R30-A               | Notebook    | [94cf17bcb6](https://linux-hardware.org/?probe=94cf17bcb6) | May 24, 2022 |
| MSI           | GF75 Thin 9SC               | Notebook    | [49b7f895e9](https://linux-hardware.org/?probe=49b7f895e9) | May 24, 2022 |
| Lenovo        | Yoga 7 16IAP7 82QG          | Convertible | [0c5e493177](https://linux-hardware.org/?probe=0c5e493177) | May 24, 2022 |
| LG Electro... | C500                        | Notebook    | [e59da09f71](https://linux-hardware.org/?probe=e59da09f71) | May 24, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [5c9c033d2f](https://linux-hardware.org/?probe=5c9c033d2f) | May 24, 2022 |
| Alienware     | m15 Ryzen Ed. R5            | Notebook    | [f451e1b307](https://linux-hardware.org/?probe=f451e1b307) | May 22, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [d1ca28a2fb](https://linux-hardware.org/?probe=d1ca28a2fb) | May 21, 2022 |
| Gigabyte      | A520 AORUS ELITE            | Desktop     | [2fdd079ebc](https://linux-hardware.org/?probe=2fdd079ebc) | May 21, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [f729776db3](https://linux-hardware.org/?probe=f729776db3) | May 21, 2022 |
| Supermicro    | X12SPO-F                    | Server      | [1cdd61e1cc](https://linux-hardware.org/?probe=1cdd61e1cc) | May 20, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [1609781085](https://linux-hardware.org/?probe=1609781085) | May 20, 2022 |
| Supermicro    | X12SPO-F                    | Server      | [5b5ab34565](https://linux-hardware.org/?probe=5b5ab34565) | May 20, 2022 |
| Sony          | SVE1712C1EW                 | Notebook    | [9410df7433](https://linux-hardware.org/?probe=9410df7433) | May 20, 2022 |
| MSI           | B460M-A PRO                 | Desktop     | [2f1ec161d1](https://linux-hardware.org/?probe=2f1ec161d1) | May 20, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [efd1b236a1](https://linux-hardware.org/?probe=efd1b236a1) | May 20, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [371eb0d1b7](https://linux-hardware.org/?probe=371eb0d1b7) | May 19, 2022 |
| ASUSTek       | P8Z68-V                     | Desktop     | [c3438d922b](https://linux-hardware.org/?probe=c3438d922b) | May 19, 2022 |
| Supermicro    | X12SCZ-TLN4FA               | Desktop     | [d29a88fa1f](https://linux-hardware.org/?probe=d29a88fa1f) | May 18, 2022 |
| Supermicro    | X12SCZ-TLN4FA               | Desktop     | [d87dcc4dff](https://linux-hardware.org/?probe=d87dcc4dff) | May 18, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [75ec4a948b](https://linux-hardware.org/?probe=75ec4a948b) | May 18, 2022 |
| HP            | 2B36                        | Desktop     | [390784f8e5](https://linux-hardware.org/?probe=390784f8e5) | May 15, 2022 |
| Lenovo        | ThinkPad T400 276521G       | Notebook    | [9a2f5118c5](https://linux-hardware.org/?probe=9a2f5118c5) | May 15, 2022 |
| MSI           | B350M MORTAR                | Desktop     | [459e7e3586](https://linux-hardware.org/?probe=459e7e3586) | May 15, 2022 |
| HP            | Folio 13                    | Notebook    | [9c9cd2aa91](https://linux-hardware.org/?probe=9c9cd2aa91) | May 15, 2022 |
| Biostar       | J3060NH                     | Desktop     | [09900d1cf6](https://linux-hardware.org/?probe=09900d1cf6) | May 14, 2022 |
| System76      | Oryx Pro                    | Notebook    | [d740686b5e](https://linux-hardware.org/?probe=d740686b5e) | May 14, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [2342a9d519](https://linux-hardware.org/?probe=2342a9d519) | May 12, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [2484d9989f](https://linux-hardware.org/?probe=2484d9989f) | May 12, 2022 |
| Lenovo        | ThinkPad X200 7458WAY       | Notebook    | [1d845e69bd](https://linux-hardware.org/?probe=1d845e69bd) | May 11, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [d3088d7665](https://linux-hardware.org/?probe=d3088d7665) | May 11, 2022 |
| Acer          | Predator G3-605             | Desktop     | [fb7a7e74d1](https://linux-hardware.org/?probe=fb7a7e74d1) | May 11, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [6a69aab6ee](https://linux-hardware.org/?probe=6a69aab6ee) | May 11, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [08deba5f5f](https://linux-hardware.org/?probe=08deba5f5f) | May 11, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [e45fa22892](https://linux-hardware.org/?probe=e45fa22892) | May 11, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [3780dc0fe5](https://linux-hardware.org/?probe=3780dc0fe5) | May 10, 2022 |
| Lenovo        | IdeaPad S510p 20298         | Notebook    | [09d0c5a57c](https://linux-hardware.org/?probe=09d0c5a57c) | May 10, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [34a59f46c4](https://linux-hardware.org/?probe=34a59f46c4) | May 10, 2022 |
| Samsung       | 550XDA                      | Notebook    | [d3d7a64817](https://linux-hardware.org/?probe=d3d7a64817) | May 08, 2022 |
| MSI           | B460M-A PRO                 | Desktop     | [29c0818bcd](https://linux-hardware.org/?probe=29c0818bcd) | May 08, 2022 |
| Acer          | WMCP78M                     | Desktop     | [bb0d37a6b8](https://linux-hardware.org/?probe=bb0d37a6b8) | May 08, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [ac1853274e](https://linux-hardware.org/?probe=ac1853274e) | May 08, 2022 |
| MSI           | A320M-HDV R4.0              | Desktop     | [837a74d32f](https://linux-hardware.org/?probe=837a74d32f) | May 08, 2022 |
| HP            | 250 G5 Notebook PC          | Notebook    | [a21e01fec5](https://linux-hardware.org/?probe=a21e01fec5) | May 07, 2022 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [eab46c9089](https://linux-hardware.org/?probe=eab46c9089) | May 07, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0BR0... | Notebook    | [ac2c2a5969](https://linux-hardware.org/?probe=ac2c2a5969) | May 06, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [feaa2cb9fb](https://linux-hardware.org/?probe=feaa2cb9fb) | May 06, 2022 |
| MSI           | A320M-HDV R4.0              | Desktop     | [43b827546c](https://linux-hardware.org/?probe=43b827546c) | May 06, 2022 |
| Lenovo        | ThinkPad X220 4290LD4       | Notebook    | [0a28279824](https://linux-hardware.org/?probe=0a28279824) | May 05, 2022 |
| ASUSTek       | PRIME B250M-PLUS            | Desktop     | [6f9cfe324a](https://linux-hardware.org/?probe=6f9cfe324a) | May 05, 2022 |
| Gigabyte      | GA-M55PLUS-S3G              | Desktop     | [ff948aad6c](https://linux-hardware.org/?probe=ff948aad6c) | May 05, 2022 |
| ASRock        | FM2A78M Pro4+               | Desktop     | [7a00557ba5](https://linux-hardware.org/?probe=7a00557ba5) | May 05, 2022 |
| ASUSTek       | G752VT                      | Notebook    | [b007cf4ed2](https://linux-hardware.org/?probe=b007cf4ed2) | May 04, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [404c22feca](https://linux-hardware.org/?probe=404c22feca) | May 04, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [744b50ab3b](https://linux-hardware.org/?probe=744b50ab3b) | May 03, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFC... | Notebook    | [3835b6bdb8](https://linux-hardware.org/?probe=3835b6bdb8) | May 03, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [1f33fda19d](https://linux-hardware.org/?probe=1f33fda19d) | May 03, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [90aa5187ab](https://linux-hardware.org/?probe=90aa5187ab) | May 02, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5c628f1d84](https://linux-hardware.org/?probe=5c628f1d84) | May 01, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [95ec2ff7d2](https://linux-hardware.org/?probe=95ec2ff7d2) | Apr 30, 2022 |
| ASUSTek       | TUF Gaming FX705GM_FX705... | Notebook    | [3589ada8b3](https://linux-hardware.org/?probe=3589ada8b3) | Apr 30, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [297dca51b9](https://linux-hardware.org/?probe=297dca51b9) | Apr 30, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [3a7104d6b4](https://linux-hardware.org/?probe=3a7104d6b4) | Apr 29, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [6755ed2aa6](https://linux-hardware.org/?probe=6755ed2aa6) | Apr 29, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [2514409f18](https://linux-hardware.org/?probe=2514409f18) | Apr 28, 2022 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [3b25bc9d0d](https://linux-hardware.org/?probe=3b25bc9d0d) | Apr 27, 2022 |
| Lenovo        | IdeaPad 310-14ISK 80SL      | Notebook    | [a57363e60a](https://linux-hardware.org/?probe=a57363e60a) | Apr 27, 2022 |
| Dell          | 0J3C2F A02                  | Desktop     | [833d1610d5](https://linux-hardware.org/?probe=833d1610d5) | Apr 25, 2022 |
| HP            | 2B47                        | Desktop     | [3805de3dc4](https://linux-hardware.org/?probe=3805de3dc4) | Apr 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [7fc8d31b49](https://linux-hardware.org/?probe=7fc8d31b49) | Apr 24, 2022 |
| Dell          | Latitude 3380               | Notebook    | [2aa3eacaee](https://linux-hardware.org/?probe=2aa3eacaee) | Apr 24, 2022 |
| ASUSTek       | Z87-PLUS                    | Desktop     | [cdc3ddaa2d](https://linux-hardware.org/?probe=cdc3ddaa2d) | Apr 22, 2022 |
| ASUSTek       | H87-PRO                     | Desktop     | [aa1df63f27](https://linux-hardware.org/?probe=aa1df63f27) | Apr 20, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [32cc2a24ac](https://linux-hardware.org/?probe=32cc2a24ac) | Apr 20, 2022 |
| HP            | 2B2C                        | Desktop     | [195e5473e9](https://linux-hardware.org/?probe=195e5473e9) | Apr 20, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [4a4df2dc70](https://linux-hardware.org/?probe=4a4df2dc70) | Apr 20, 2022 |
| HP            | Pavilion g7                 | Notebook    | [6bfdb0c3c9](https://linux-hardware.org/?probe=6bfdb0c3c9) | Apr 19, 2022 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [0579e465d1](https://linux-hardware.org/?probe=0579e465d1) | Apr 19, 2022 |
| HP            | Pavilion g7                 | Notebook    | [97e00013eb](https://linux-hardware.org/?probe=97e00013eb) | Apr 19, 2022 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [e44ad7d84e](https://linux-hardware.org/?probe=e44ad7d84e) | Apr 19, 2022 |
| ASUSTek       | G752VSK                     | Notebook    | [4b6d535621](https://linux-hardware.org/?probe=4b6d535621) | Apr 18, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [771e8a4439](https://linux-hardware.org/?probe=771e8a4439) | Apr 18, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [b4ea114ce4](https://linux-hardware.org/?probe=b4ea114ce4) | Apr 17, 2022 |
| ASUSTek       | G752VSK                     | Notebook    | [dfbc0779e8](https://linux-hardware.org/?probe=dfbc0779e8) | Apr 17, 2022 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [9ba73648b1](https://linux-hardware.org/?probe=9ba73648b1) | Apr 16, 2022 |
| HP            | 2B2C                        | Desktop     | [f88798fff2](https://linux-hardware.org/?probe=f88798fff2) | Apr 15, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [a587867d2e](https://linux-hardware.org/?probe=a587867d2e) | Apr 15, 2022 |
| Dell          | Latitude E7250              | Notebook    | [532fb04297](https://linux-hardware.org/?probe=532fb04297) | Apr 15, 2022 |
| Dell          | 00V62H A00                  | Desktop     | [499a00bcf8](https://linux-hardware.org/?probe=499a00bcf8) | Apr 15, 2022 |
| HP            | ProBook 4430s               | Notebook    | [79e30d321b](https://linux-hardware.org/?probe=79e30d321b) | Apr 15, 2022 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [afe37cb756](https://linux-hardware.org/?probe=afe37cb756) | Apr 14, 2022 |
| Dell          | Latitude E7250              | Notebook    | [a1e63550ab](https://linux-hardware.org/?probe=a1e63550ab) | Apr 14, 2022 |
| Lenovo        | ThinkPad X220 4291IU6       | Notebook    | [a4c2a2bff9](https://linux-hardware.org/?probe=a4c2a2bff9) | Apr 14, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [b5375b9ffb](https://linux-hardware.org/?probe=b5375b9ffb) | Apr 13, 2022 |
| ASRock        | TRX40 Taichi                | Desktop     | [7ce5e071a2](https://linux-hardware.org/?probe=7ce5e071a2) | Apr 13, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [85062520f7](https://linux-hardware.org/?probe=85062520f7) | Apr 13, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [4c52c99ee9](https://linux-hardware.org/?probe=4c52c99ee9) | Apr 12, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [162850d6b3](https://linux-hardware.org/?probe=162850d6b3) | Apr 12, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [542c9c6703](https://linux-hardware.org/?probe=542c9c6703) | Apr 11, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [5738641fc9](https://linux-hardware.org/?probe=5738641fc9) | Apr 11, 2022 |
| Unknown       | Unknown                     | Desktop     | [c6577346b8](https://linux-hardware.org/?probe=c6577346b8) | Apr 11, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [36e02535fb](https://linux-hardware.org/?probe=36e02535fb) | Apr 11, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [c32c875fc6](https://linux-hardware.org/?probe=c32c875fc6) | Apr 10, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [36b98241e2](https://linux-hardware.org/?probe=36b98241e2) | Apr 10, 2022 |
| Dell          | Latitude E6230              | Notebook    | [67750bdf0f](https://linux-hardware.org/?probe=67750bdf0f) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [d03632cea9](https://linux-hardware.org/?probe=d03632cea9) | Apr 10, 2022 |
| Dell          | Latitude E6230              | Notebook    | [db52ca23d3](https://linux-hardware.org/?probe=db52ca23d3) | Apr 09, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [a6aee71c13](https://linux-hardware.org/?probe=a6aee71c13) | Apr 09, 2022 |
| HP            | ProBook 470 G2              | Notebook    | [1d1cdbd95c](https://linux-hardware.org/?probe=1d1cdbd95c) | Apr 09, 2022 |
| Unknown       | Unknown                     | Desktop     | [73abf1d6fd](https://linux-hardware.org/?probe=73abf1d6fd) | Apr 08, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [7d87907153](https://linux-hardware.org/?probe=7d87907153) | Apr 07, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [41fc926d28](https://linux-hardware.org/?probe=41fc926d28) | Apr 07, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [586edef1b9](https://linux-hardware.org/?probe=586edef1b9) | Apr 07, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [bb881ed0ee](https://linux-hardware.org/?probe=bb881ed0ee) | Apr 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5370b9e906](https://linux-hardware.org/?probe=5370b9e906) | Apr 07, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [ca558e6708](https://linux-hardware.org/?probe=ca558e6708) | Apr 07, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [4e232c446f](https://linux-hardware.org/?probe=4e232c446f) | Apr 06, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [30591629c3](https://linux-hardware.org/?probe=30591629c3) | Apr 05, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [8181b0cd19](https://linux-hardware.org/?probe=8181b0cd19) | Apr 05, 2022 |
| Dell          | Latitude E6430              | Notebook    | [c974a805b2](https://linux-hardware.org/?probe=c974a805b2) | Apr 05, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [dd1fef9175](https://linux-hardware.org/?probe=dd1fef9175) | Apr 05, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [f41079b495](https://linux-hardware.org/?probe=f41079b495) | Apr 05, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [091e8b72d9](https://linux-hardware.org/?probe=091e8b72d9) | Apr 05, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [fe7fdad91b](https://linux-hardware.org/?probe=fe7fdad91b) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [a26b03795a](https://linux-hardware.org/?probe=a26b03795a) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [d467a8e89f](https://linux-hardware.org/?probe=d467a8e89f) | Apr 04, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [5cfb35fb9e](https://linux-hardware.org/?probe=5cfb35fb9e) | Apr 04, 2022 |
| Notebook      | P65_P67RGRERA               | Notebook    | [654f1700c4](https://linux-hardware.org/?probe=654f1700c4) | Apr 04, 2022 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [b22a799f67](https://linux-hardware.org/?probe=b22a799f67) | Apr 04, 2022 |
| Sony          | SVE1712C1EW                 | Notebook    | [989843d8cf](https://linux-hardware.org/?probe=989843d8cf) | Apr 04, 2022 |
| Lenovo        | SHARKBAY SDK0J40705 WIN     | Desktop     | [374819f582](https://linux-hardware.org/?probe=374819f582) | Apr 04, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [2c39a577ac](https://linux-hardware.org/?probe=2c39a577ac) | Apr 04, 2022 |
| Dell          | Latitude 5421               | Notebook    | [78ac6f00cd](https://linux-hardware.org/?probe=78ac6f00cd) | Apr 04, 2022 |
| Lenovo        | ThinkPad T480s 20L7001SG... | Notebook    | [440bfc13d9](https://linux-hardware.org/?probe=440bfc13d9) | Apr 03, 2022 |
| Sony          | SVE1712C1EW                 | Notebook    | [5e530d1a32](https://linux-hardware.org/?probe=5e530d1a32) | Apr 03, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [492c2c7bf4](https://linux-hardware.org/?probe=492c2c7bf4) | Apr 03, 2022 |
| Gigabyte      | Z270-Gaming K3              | Desktop     | [97969b1325](https://linux-hardware.org/?probe=97969b1325) | Apr 03, 2022 |
| Acer          | WMCP78M                     | Desktop     | [7c9d2a802f](https://linux-hardware.org/?probe=7c9d2a802f) | Apr 03, 2022 |
| Unknown       | Unknown                     | Desktop     | [14a3433a91](https://linux-hardware.org/?probe=14a3433a91) | Apr 03, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [35057588b4](https://linux-hardware.org/?probe=35057588b4) | Apr 03, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [9050980874](https://linux-hardware.org/?probe=9050980874) | Apr 02, 2022 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [a4228141cb](https://linux-hardware.org/?probe=a4228141cb) | Apr 02, 2022 |
| Unknown       | Unknown                     | Desktop     | [9ea14bf201](https://linux-hardware.org/?probe=9ea14bf201) | Apr 02, 2022 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [6b00b2928a](https://linux-hardware.org/?probe=6b00b2928a) | Apr 01, 2022 |
| HPE           | ProLiant DL380 Gen10        | Server      | [5cdc7436c0](https://linux-hardware.org/?probe=5cdc7436c0) | Mar 31, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [097d78d0b6](https://linux-hardware.org/?probe=097d78d0b6) | Mar 31, 2022 |
| Supermicro    | A2SAN-E-WOHSA               | Desktop     | [f74de3797f](https://linux-hardware.org/?probe=f74de3797f) | Mar 31, 2022 |
| Supermicro    | A2SDi-8C-HLN4F              | Desktop     | [44eafd5b02](https://linux-hardware.org/?probe=44eafd5b02) | Mar 31, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [8e7fc0aef9](https://linux-hardware.org/?probe=8e7fc0aef9) | Mar 31, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [9a18c2ac1c](https://linux-hardware.org/?probe=9a18c2ac1c) | Mar 31, 2022 |
| Intel         | Unknown                     | Desktop     | [4689fbf7e1](https://linux-hardware.org/?probe=4689fbf7e1) | Mar 31, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ceae86aef1](https://linux-hardware.org/?probe=ceae86aef1) | Mar 30, 2022 |
| Acer          | Predator G3-710             | Desktop     | [d8d0331e9e](https://linux-hardware.org/?probe=d8d0331e9e) | Mar 30, 2022 |
| Lenovo        | B550 20053                  | Notebook    | [e3c65a5e44](https://linux-hardware.org/?probe=e3c65a5e44) | Mar 30, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | Notebook    | [339d70da8c](https://linux-hardware.org/?probe=339d70da8c) | Mar 30, 2022 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [99de1a9e9d](https://linux-hardware.org/?probe=99de1a9e9d) | Mar 30, 2022 |
| Kanji         | Tamura MAX DUO              | Convertible | [1434c90e55](https://linux-hardware.org/?probe=1434c90e55) | Mar 30, 2022 |
| MSI           | B450-A PRO                  | Desktop     | [e33537863b](https://linux-hardware.org/?probe=e33537863b) | Mar 28, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [d72468b304](https://linux-hardware.org/?probe=d72468b304) | Mar 27, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [1f36f7eada](https://linux-hardware.org/?probe=1f36f7eada) | Mar 27, 2022 |
| Samsung       | 3570R/370R/470R/450R/510... | Notebook    | [799c1dfce8](https://linux-hardware.org/?probe=799c1dfce8) | Mar 26, 2022 |
| MSI           | H170 GAMING M3              | Desktop     | [6467169a74](https://linux-hardware.org/?probe=6467169a74) | Mar 26, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [a2bd44d0a4](https://linux-hardware.org/?probe=a2bd44d0a4) | Mar 25, 2022 |
| MSI           | H170 GAMING M3              | Desktop     | [e1aeadc089](https://linux-hardware.org/?probe=e1aeadc089) | Mar 25, 2022 |
| HP            | 8643 SMVB                   | Desktop     | [170657280c](https://linux-hardware.org/?probe=170657280c) | Mar 25, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [98b597334b](https://linux-hardware.org/?probe=98b597334b) | Mar 25, 2022 |
| System76      | Oryx Pro                    | Notebook    | [b128755fa4](https://linux-hardware.org/?probe=b128755fa4) | Mar 22, 2022 |
| Lenovo        | ThinkPad X260 20F60086MD    | Notebook    | [828cc46772](https://linux-hardware.org/?probe=828cc46772) | Mar 22, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [40f5402f5a](https://linux-hardware.org/?probe=40f5402f5a) | Mar 21, 2022 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [672496577e](https://linux-hardware.org/?probe=672496577e) | Mar 21, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [92c8ac9161](https://linux-hardware.org/?probe=92c8ac9161) | Mar 21, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [dac9dfc52d](https://linux-hardware.org/?probe=dac9dfc52d) | Mar 20, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [3617d07720](https://linux-hardware.org/?probe=3617d07720) | Mar 20, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [555255cb84](https://linux-hardware.org/?probe=555255cb84) | Mar 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [c0faa2a27b](https://linux-hardware.org/?probe=c0faa2a27b) | Mar 19, 2022 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [2692e4dfd1](https://linux-hardware.org/?probe=2692e4dfd1) | Mar 18, 2022 |
| Unknown       | Intel X79                   | Desktop     | [1b92468c15](https://linux-hardware.org/?probe=1b92468c15) | Mar 17, 2022 |
| Lenovo        | ThinkPad T460s 20F9S02U0... | Notebook    | [f255ab814c](https://linux-hardware.org/?probe=f255ab814c) | Mar 17, 2022 |
| MSI           | GS66 Stealth 10SE           | Notebook    | [fb8d2216a5](https://linux-hardware.org/?probe=fb8d2216a5) | Mar 17, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [d0a87aedef](https://linux-hardware.org/?probe=d0a87aedef) | Mar 16, 2022 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [908e3fe366](https://linux-hardware.org/?probe=908e3fe366) | Mar 16, 2022 |
| ASRock        | Z87 Professional            | Desktop     | [e75eb7a802](https://linux-hardware.org/?probe=e75eb7a802) | Mar 15, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [51409532cc](https://linux-hardware.org/?probe=51409532cc) | Mar 15, 2022 |
| Acer          | Aspire A515-52G             | Notebook    | [13775d028d](https://linux-hardware.org/?probe=13775d028d) | Mar 15, 2022 |
| Dell          | Precision 7540              | Notebook    | [9d4662756c](https://linux-hardware.org/?probe=9d4662756c) | Mar 15, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [cb2918a35e](https://linux-hardware.org/?probe=cb2918a35e) | Mar 12, 2022 |
| Dell          | Latitude E7240              | Notebook    | [fed08a1d40](https://linux-hardware.org/?probe=fed08a1d40) | Mar 12, 2022 |
| ASRock        | B550 Phantom Gaming 4/ac    | Desktop     | [d7c05bb862](https://linux-hardware.org/?probe=d7c05bb862) | Mar 11, 2022 |
| Lenovo        | ThinkPad X1 Nano Gen 1 2... | Notebook    | [1f4fadbe2e](https://linux-hardware.org/?probe=1f4fadbe2e) | Mar 11, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e141c99bf2](https://linux-hardware.org/?probe=e141c99bf2) | Mar 09, 2022 |
| Lenovo        | ThinkPad T420 4180MBM       | Notebook    | [a83a1ffe1a](https://linux-hardware.org/?probe=a83a1ffe1a) | Mar 09, 2022 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [ed3d7239af](https://linux-hardware.org/?probe=ed3d7239af) | Mar 09, 2022 |
| System76      | Oryx Pro                    | Notebook    | [d36e30fa5b](https://linux-hardware.org/?probe=d36e30fa5b) | Mar 08, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [dbf296e963](https://linux-hardware.org/?probe=dbf296e963) | Mar 08, 2022 |
| Dell          | 02YYK5 A01                  | Desktop     | [7b670726c4](https://linux-hardware.org/?probe=7b670726c4) | Mar 08, 2022 |
| Sony          | VPCEH25FM                   | Notebook    | [5a60a14cf4](https://linux-hardware.org/?probe=5a60a14cf4) | Mar 07, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [d772cac60d](https://linux-hardware.org/?probe=d772cac60d) | Mar 07, 2022 |
| Dell          | Precision M4800             | Notebook    | [6bca1ea21f](https://linux-hardware.org/?probe=6bca1ea21f) | Mar 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [8dda7f6478](https://linux-hardware.org/?probe=8dda7f6478) | Mar 06, 2022 |
| Dell          | 055H3G A01                  | Desktop     | [7e00973942](https://linux-hardware.org/?probe=7e00973942) | Mar 06, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [6ba21bc191](https://linux-hardware.org/?probe=6ba21bc191) | Mar 05, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [531e740b37](https://linux-hardware.org/?probe=531e740b37) | Mar 05, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [d5ab693301](https://linux-hardware.org/?probe=d5ab693301) | Mar 05, 2022 |
| MSI           | B350 GAMING PLUS            | Desktop     | [2383184762](https://linux-hardware.org/?probe=2383184762) | Mar 05, 2022 |
| ASRock        | X399 Taichi                 | Desktop     | [2efd176b6f](https://linux-hardware.org/?probe=2efd176b6f) | Mar 03, 2022 |
| Gigabyte      | A520M H                     | Desktop     | [1b45a09429](https://linux-hardware.org/?probe=1b45a09429) | Mar 03, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [ee905a56c9](https://linux-hardware.org/?probe=ee905a56c9) | Mar 02, 2022 |
| ASUSTek       | CM6870                      | Desktop     | [45c8e5fea2](https://linux-hardware.org/?probe=45c8e5fea2) | Mar 01, 2022 |
| Apple         | MacBookPro11,2              | Notebook    | [eb57cef46a](https://linux-hardware.org/?probe=eb57cef46a) | Feb 28, 2022 |
| Dell          | Latitude E5400              | Notebook    | [ab5ce36275](https://linux-hardware.org/?probe=ab5ce36275) | Feb 27, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [b531665e82](https://linux-hardware.org/?probe=b531665e82) | Feb 27, 2022 |
| Unknown       | Intel X79                   | Desktop     | [6a9245acd2](https://linux-hardware.org/?probe=6a9245acd2) | Feb 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d606848435](https://linux-hardware.org/?probe=d606848435) | Feb 27, 2022 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [759958a4b0](https://linux-hardware.org/?probe=759958a4b0) | Feb 26, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [36e7b3c4aa](https://linux-hardware.org/?probe=36e7b3c4aa) | Feb 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [a9bcae50d2](https://linux-hardware.org/?probe=a9bcae50d2) | Feb 26, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E21... | Notebook    | [270aaf59b6](https://linux-hardware.org/?probe=270aaf59b6) | Feb 25, 2022 |
| Lenovo        | ThinkPad S430 68852BU       | Notebook    | [7d7bb498fe](https://linux-hardware.org/?probe=7d7bb498fe) | Feb 25, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | Notebook    | [6423622186](https://linux-hardware.org/?probe=6423622186) | Feb 23, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [52bbb8515e](https://linux-hardware.org/?probe=52bbb8515e) | Feb 23, 2022 |
| Casper        | C600 NOTEBOOK DISCRETE      | Notebook    | [9a32d51389](https://linux-hardware.org/?probe=9a32d51389) | Feb 22, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [eacd6c646c](https://linux-hardware.org/?probe=eacd6c646c) | Feb 22, 2022 |
| Medion        | MS-7707                     | Desktop     | [2e4723aea4](https://linux-hardware.org/?probe=2e4723aea4) | Feb 22, 2022 |
| Dell          | Latitude E7240              | Notebook    | [91cc26a6ac](https://linux-hardware.org/?probe=91cc26a6ac) | Feb 22, 2022 |
| Lenovo        | IdeaPad Flex-14API 81SS     | Notebook    | [e24c41d802](https://linux-hardware.org/?probe=e24c41d802) | Feb 21, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [1947127ef5](https://linux-hardware.org/?probe=1947127ef5) | Feb 21, 2022 |
| Dell          | Inspiron 5567               | Notebook    | [1ba170be6a](https://linux-hardware.org/?probe=1ba170be6a) | Feb 20, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDC... | Notebook    | [fb981fe5b0](https://linux-hardware.org/?probe=fb981fe5b0) | Feb 20, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [0fd79af602](https://linux-hardware.org/?probe=0fd79af602) | Feb 19, 2022 |
| ASUSTek       | K54L                        | Notebook    | [5850a8dd22](https://linux-hardware.org/?probe=5850a8dd22) | Feb 19, 2022 |
| Razer         | Blade 15 Base Model (Ear... | Notebook    | [3beffcfd3e](https://linux-hardware.org/?probe=3beffcfd3e) | Feb 19, 2022 |
| Lenovo        | ThinkPad T420 4180DY4       | Notebook    | [88c3891424](https://linux-hardware.org/?probe=88c3891424) | Feb 19, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [732c7ad77e](https://linux-hardware.org/?probe=732c7ad77e) | Feb 18, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1982ff9621](https://linux-hardware.org/?probe=1982ff9621) | Feb 18, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [35ac77d812](https://linux-hardware.org/?probe=35ac77d812) | Feb 17, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [fec0662c03](https://linux-hardware.org/?probe=fec0662c03) | Feb 16, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [1e8c363a67](https://linux-hardware.org/?probe=1e8c363a67) | Feb 16, 2022 |
| ASUSTek       | K53E                        | Notebook    | [929e5d8462](https://linux-hardware.org/?probe=929e5d8462) | Feb 15, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [046f5cdbd7](https://linux-hardware.org/?probe=046f5cdbd7) | Feb 14, 2022 |
| ASUSTek       | ROG Maximus XI FORMULA      | Desktop     | [0ee015dd8e](https://linux-hardware.org/?probe=0ee015dd8e) | Feb 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [34bd2af067](https://linux-hardware.org/?probe=34bd2af067) | Feb 14, 2022 |
| Lenovo        | ThinkPad R61/R61i 8934A7... | Notebook    | [e60d5e52f2](https://linux-hardware.org/?probe=e60d5e52f2) | Feb 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [ed2717ae86](https://linux-hardware.org/?probe=ed2717ae86) | Feb 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b12c01311a](https://linux-hardware.org/?probe=b12c01311a) | Feb 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1df0e30fbc](https://linux-hardware.org/?probe=1df0e30fbc) | Feb 13, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [0f83b2fd97](https://linux-hardware.org/?probe=0f83b2fd97) | Feb 12, 2022 |
| Gigabyte      | F2A78M-D3H                  | Desktop     | [ca5c3f80ae](https://linux-hardware.org/?probe=ca5c3f80ae) | Feb 11, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [cb0abbfe2d](https://linux-hardware.org/?probe=cb0abbfe2d) | Feb 10, 2022 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [c50b098929](https://linux-hardware.org/?probe=c50b098929) | Feb 10, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [dbfb51d331](https://linux-hardware.org/?probe=dbfb51d331) | Feb 10, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [aa66dba98f](https://linux-hardware.org/?probe=aa66dba98f) | Feb 09, 2022 |
| Lenovo        | ThinkPad W510 4389BB4       | Notebook    | [ecaa14289f](https://linux-hardware.org/?probe=ecaa14289f) | Feb 09, 2022 |
| Compal        | PBL21                       | Notebook    | [7a0b26892e](https://linux-hardware.org/?probe=7a0b26892e) | Feb 09, 2022 |
| Lenovo        | IdeaPad Slim 7 Pro 14IHU... | Notebook    | [e6bc24c5b9](https://linux-hardware.org/?probe=e6bc24c5b9) | Feb 08, 2022 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [de476d2b5a](https://linux-hardware.org/?probe=de476d2b5a) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [8023f7f6d2](https://linux-hardware.org/?probe=8023f7f6d2) | Feb 08, 2022 |
| Acer          | Nitro AN515-54              | Notebook    | [66c6eadf8b](https://linux-hardware.org/?probe=66c6eadf8b) | Feb 08, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [8a7cf7aca4](https://linux-hardware.org/?probe=8a7cf7aca4) | Feb 07, 2022 |
| Biostar       | J3060NH                     | Desktop     | [b34126597c](https://linux-hardware.org/?probe=b34126597c) | Feb 07, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [587efdf773](https://linux-hardware.org/?probe=587efdf773) | Feb 06, 2022 |
| Acer          | Aspire A515-41G             | Notebook    | [0785fcc2af](https://linux-hardware.org/?probe=0785fcc2af) | Feb 06, 2022 |
| Supermicro    | X11SAE-M                    | Server      | [ecb9ec0d34](https://linux-hardware.org/?probe=ecb9ec0d34) | Feb 06, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6c3ac00f6a](https://linux-hardware.org/?probe=6c3ac00f6a) | Feb 06, 2022 |
| Dell          | 084J0R A00                  | Desktop     | [70c2ff9419](https://linux-hardware.org/?probe=70c2ff9419) | Feb 06, 2022 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [92c26ed8dc](https://linux-hardware.org/?probe=92c26ed8dc) | Feb 06, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [30bb989cfa](https://linux-hardware.org/?probe=30bb989cfa) | Feb 05, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [b8aa657ab7](https://linux-hardware.org/?probe=b8aa657ab7) | Feb 05, 2022 |
| Dell          | Precision 5550              | Notebook    | [2853896d4c](https://linux-hardware.org/?probe=2853896d4c) | Feb 04, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [4a36d79506](https://linux-hardware.org/?probe=4a36d79506) | Feb 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [8aafebe07c](https://linux-hardware.org/?probe=8aafebe07c) | Feb 03, 2022 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [f4a6341837](https://linux-hardware.org/?probe=f4a6341837) | Feb 03, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [655eea9ee5](https://linux-hardware.org/?probe=655eea9ee5) | Feb 02, 2022 |
| Notebook      | PA70ES                      | Notebook    | [794ffc9a83](https://linux-hardware.org/?probe=794ffc9a83) | Feb 02, 2022 |
| ASUSTek       | X750LN                      | Notebook    | [94a70cdd5d](https://linux-hardware.org/?probe=94a70cdd5d) | Feb 02, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [1c3c43b4ce](https://linux-hardware.org/?probe=1c3c43b4ce) | Feb 02, 2022 |
| Acer          | Aspire V3-771               | Notebook    | [f755eb7a78](https://linux-hardware.org/?probe=f755eb7a78) | Feb 01, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | Notebook    | [88085159bf](https://linux-hardware.org/?probe=88085159bf) | Jan 31, 2022 |
| Casper        | EXCALIBUR G860              | Notebook    | [e6f107eb25](https://linux-hardware.org/?probe=e6f107eb25) | Jan 30, 2022 |
| Gigabyte      | A520M S2H                   | Desktop     | [ccbf2ec4f5](https://linux-hardware.org/?probe=ccbf2ec4f5) | Jan 29, 2022 |
| Gigabyte      | H110M-A-CF                  | Desktop     | [e6a3a69257](https://linux-hardware.org/?probe=e6a3a69257) | Jan 29, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [d2ebf4698b](https://linux-hardware.org/?probe=d2ebf4698b) | Jan 29, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T0... | Notebook    | [9a1fb4d53e](https://linux-hardware.org/?probe=9a1fb4d53e) | Jan 29, 2022 |
| Lenovo        | ThinkPad T540p 20BE0086M... | Notebook    | [707a381138](https://linux-hardware.org/?probe=707a381138) | Jan 28, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [1db87d66c6](https://linux-hardware.org/?probe=1db87d66c6) | Jan 28, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Mini pc     | [1f9df11a59](https://linux-hardware.org/?probe=1f9df11a59) | Jan 28, 2022 |
| Dell          | Latitude E6510              | Notebook    | [efc619cc61](https://linux-hardware.org/?probe=efc619cc61) | Jan 28, 2022 |
| HP            | 1998                        | Desktop     | [4ee1e4fcee](https://linux-hardware.org/?probe=4ee1e4fcee) | Jan 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [75082acc94](https://linux-hardware.org/?probe=75082acc94) | Jan 27, 2022 |
| Lenovo        | ThinkPad L460 20FVS0QQ00    | Notebook    | [470cd66ae6](https://linux-hardware.org/?probe=470cd66ae6) | Jan 27, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [efe16c5921](https://linux-hardware.org/?probe=efe16c5921) | Jan 27, 2022 |
| Lenovo        | ThinkPad Yoga 11e 3rd Ge... | Convertible | [599ea5acd6](https://linux-hardware.org/?probe=599ea5acd6) | Jan 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [0b57afd8bf](https://linux-hardware.org/?probe=0b57afd8bf) | Jan 26, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [d8e76e70e8](https://linux-hardware.org/?probe=d8e76e70e8) | Jan 26, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [a4172550fa](https://linux-hardware.org/?probe=a4172550fa) | Jan 26, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [dfe4dda46b](https://linux-hardware.org/?probe=dfe4dda46b) | Jan 26, 2022 |
| Casper        | EXCALIBUR G860              | Notebook    | [76a2a4e935](https://linux-hardware.org/?probe=76a2a4e935) | Jan 24, 2022 |
| ASRock        | P75 Pro3                    | Desktop     | [76bb99305c](https://linux-hardware.org/?probe=76bb99305c) | Jan 24, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [269d1509c2](https://linux-hardware.org/?probe=269d1509c2) | Jan 24, 2022 |
| Gigabyte      | AB350N-Gaming WIFI-CF       | Desktop     | [2dbb65e1bc](https://linux-hardware.org/?probe=2dbb65e1bc) | Jan 24, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [a2ed61ffcd](https://linux-hardware.org/?probe=a2ed61ffcd) | Jan 24, 2022 |
| HP            | ProBook 450 G1              | Notebook    | [269396626c](https://linux-hardware.org/?probe=269396626c) | Jan 23, 2022 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [22757e0dd9](https://linux-hardware.org/?probe=22757e0dd9) | Jan 23, 2022 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [2ce129a03e](https://linux-hardware.org/?probe=2ce129a03e) | Jan 23, 2022 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [0d9f79bb17](https://linux-hardware.org/?probe=0d9f79bb17) | Jan 23, 2022 |
| Unknown       | Intel X79                   | Desktop     | [7d1ab99839](https://linux-hardware.org/?probe=7d1ab99839) | Jan 23, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [299f1c8cca](https://linux-hardware.org/?probe=299f1c8cca) | Jan 23, 2022 |
| Toshiba       | Satellite L640              | Notebook    | [280b5d9630](https://linux-hardware.org/?probe=280b5d9630) | Jan 22, 2022 |
| Standard      | MB50II                      | Notebook    | [aa719e1665](https://linux-hardware.org/?probe=aa719e1665) | Jan 22, 2022 |
| ASRock        | A300M-STX                   | Desktop     | [13de9d767d](https://linux-hardware.org/?probe=13de9d767d) | Jan 21, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [ae399035f5](https://linux-hardware.org/?probe=ae399035f5) | Jan 21, 2022 |
| Lenovo        | ThinkPad P51 20HJS2JJ01     | Notebook    | [3a0225272f](https://linux-hardware.org/?probe=3a0225272f) | Jan 21, 2022 |
| MSI           | A320M-HDV R4.0              | Desktop     | [09347426df](https://linux-hardware.org/?probe=09347426df) | Jan 20, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [4d77516c19](https://linux-hardware.org/?probe=4d77516c19) | Jan 19, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [3bc52b8340](https://linux-hardware.org/?probe=3bc52b8340) | Jan 19, 2022 |
| Lenovo        | IdeaPad Y580                | Notebook    | [2a4100e03c](https://linux-hardware.org/?probe=2a4100e03c) | Jan 18, 2022 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [0287de904c](https://linux-hardware.org/?probe=0287de904c) | Jan 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0fddd05eae](https://linux-hardware.org/?probe=0fddd05eae) | Jan 18, 2022 |
| Lenovo        | ThinkPad P15v Gen 1 20TQ... | Notebook    | [6f87d7372b](https://linux-hardware.org/?probe=6f87d7372b) | Jan 18, 2022 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [03aa6d19c1](https://linux-hardware.org/?probe=03aa6d19c1) | Jan 18, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [30edae47a1](https://linux-hardware.org/?probe=30edae47a1) | Jan 17, 2022 |
| Dell          | Latitude 7480               | Notebook    | [526c09a456](https://linux-hardware.org/?probe=526c09a456) | Jan 17, 2022 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [b123404920](https://linux-hardware.org/?probe=b123404920) | Jan 17, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [5343777492](https://linux-hardware.org/?probe=5343777492) | Jan 16, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6da1d84e76](https://linux-hardware.org/?probe=6da1d84e76) | Jan 16, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [9324cf10f9](https://linux-hardware.org/?probe=9324cf10f9) | Jan 15, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [f87a30cc1b](https://linux-hardware.org/?probe=f87a30cc1b) | Jan 15, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [a7e3aee849](https://linux-hardware.org/?probe=a7e3aee849) | Jan 15, 2022 |
| ASUSTek       | P5L8L-SE                    | Desktop     | [459b062c3e](https://linux-hardware.org/?probe=459b062c3e) | Jan 14, 2022 |
| Gigabyte      | P55-USB3                    | Desktop     | [07d50b5a0a](https://linux-hardware.org/?probe=07d50b5a0a) | Jan 14, 2022 |
| HP            | 83E0                        | Desktop     | [4a54d6921c](https://linux-hardware.org/?probe=4a54d6921c) | Jan 13, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [7ace73b9e5](https://linux-hardware.org/?probe=7ace73b9e5) | Jan 12, 2022 |
| Lenovo        | ThinkPad T420 4180DY4       | Notebook    | [968c8c3b82](https://linux-hardware.org/?probe=968c8c3b82) | Jan 11, 2022 |
| HP            | EliteBook x360 1030 G4      | Convertible | [3ac159be99](https://linux-hardware.org/?probe=3ac159be99) | Jan 10, 2022 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [148b934acf](https://linux-hardware.org/?probe=148b934acf) | Jan 09, 2022 |
| Lenovo        | ThinkPad T560 20FH001TUS    | Notebook    | [f8400f7913](https://linux-hardware.org/?probe=f8400f7913) | Jan 09, 2022 |
| Dell          | 05CNYF A01                  | Desktop     | [c197ba435d](https://linux-hardware.org/?probe=c197ba435d) | Jan 09, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [2f505d02d9](https://linux-hardware.org/?probe=2f505d02d9) | Jan 09, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [37d39e8efe](https://linux-hardware.org/?probe=37d39e8efe) | Jan 09, 2022 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [ad8e8b92cb](https://linux-hardware.org/?probe=ad8e8b92cb) | Jan 08, 2022 |
| Dell          | XPS 13 7390                 | Notebook    | [4026f1e18c](https://linux-hardware.org/?probe=4026f1e18c) | Jan 08, 2022 |
| MSI           | MEG X570 GODLIKE            | Desktop     | [2e21ca6670](https://linux-hardware.org/?probe=2e21ca6670) | Jan 08, 2022 |
| Acer          | Extensa 5620                | Notebook    | [a10369e225](https://linux-hardware.org/?probe=a10369e225) | Jan 08, 2022 |
| Sony          | VPCEB2B4E                   | Notebook    | [4d3b6ede0c](https://linux-hardware.org/?probe=4d3b6ede0c) | Jan 08, 2022 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [c56817a778](https://linux-hardware.org/?probe=c56817a778) | Jan 08, 2022 |
| HP            | 843B                        | Desktop     | [24e5dae02e](https://linux-hardware.org/?probe=24e5dae02e) | Jan 07, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5cec5778a0](https://linux-hardware.org/?probe=5cec5778a0) | Jan 06, 2022 |
| Lenovo        | ThinkPad T420 4180AJ3       | Notebook    | [d744cfb251](https://linux-hardware.org/?probe=d744cfb251) | Jan 06, 2022 |
| HP            | 82F2 A01                    | Desktop     | [416ee28a87](https://linux-hardware.org/?probe=416ee28a87) | Jan 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [e2753ebd08](https://linux-hardware.org/?probe=e2753ebd08) | Jan 04, 2022 |
| HP            | x2 Detachable 10-p0XX       | Tablet      | [e913dca33e](https://linux-hardware.org/?probe=e913dca33e) | Jan 04, 2022 |
| Dell          | 0KWVT8 A02                  | Desktop     | [fe5ca696c8](https://linux-hardware.org/?probe=fe5ca696c8) | Jan 04, 2022 |
| Monster       | ABRA A5 V11.1               | Notebook    | [0cc6ec8af7](https://linux-hardware.org/?probe=0cc6ec8af7) | Jan 03, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3383929020](https://linux-hardware.org/?probe=3383929020) | Jan 03, 2022 |
| VS Company    | MCP61M                      | Desktop     | [8009a6fbdf](https://linux-hardware.org/?probe=8009a6fbdf) | Jan 02, 2022 |
| Lenovo        | ThinkPad E580 20KS005ASC    | Notebook    | [0a37cdb124](https://linux-hardware.org/?probe=0a37cdb124) | Jan 02, 2022 |
| Lenovo        | ThinkPad X1 Extreme 20MF... | Notebook    | [14ca887c8f](https://linux-hardware.org/?probe=14ca887c8f) | Jan 02, 2022 |
| Lenovo        | ThinkStation S10 6483CTO    | Desktop     | [0d867912a7](https://linux-hardware.org/?probe=0d867912a7) | Jan 01, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [23110f625c](https://linux-hardware.org/?probe=23110f625c) | Dec 31, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [98ed791fc8](https://linux-hardware.org/?probe=98ed791fc8) | Dec 31, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3e3a3df7ce](https://linux-hardware.org/?probe=3e3a3df7ce) | Dec 31, 2021 |
| Gigabyte      | B150-HD3P-CF                | Desktop     | [46c8424272](https://linux-hardware.org/?probe=46c8424272) | Dec 31, 2021 |
| Lenovo        | ThinkPad T410 2522AC1       | Notebook    | [0cf80c2ee3](https://linux-hardware.org/?probe=0cf80c2ee3) | Dec 31, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [f6d8856ace](https://linux-hardware.org/?probe=f6d8856ace) | Dec 30, 2021 |
| Dell          | XPS 13 9370                 | Notebook    | [17548c6fc7](https://linux-hardware.org/?probe=17548c6fc7) | Dec 30, 2021 |
| Gigabyte      | Z77X-D3H                    | Desktop     | [44cbef1c02](https://linux-hardware.org/?probe=44cbef1c02) | Dec 30, 2021 |
| Dell          | 0YXT71 A01                  | Desktop     | [1bd919981a](https://linux-hardware.org/?probe=1bd919981a) | Dec 30, 2021 |
| Lenovo        | ThinkPad T460 20FMS80M0C    | Notebook    | [dfdcb1f759](https://linux-hardware.org/?probe=dfdcb1f759) | Dec 29, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [7376dd6793](https://linux-hardware.org/?probe=7376dd6793) | Dec 29, 2021 |
| Acer          | Nitro AN715-51              | Notebook    | [c3caffed3c](https://linux-hardware.org/?probe=c3caffed3c) | Dec 29, 2021 |
| ASUSTek       | Zephyrus G GU502DU_GA502... | Notebook    | [4a1c70f95f](https://linux-hardware.org/?probe=4a1c70f95f) | Dec 28, 2021 |
| Dell          | Latitude E4310              | Notebook    | [8b6976bdd2](https://linux-hardware.org/?probe=8b6976bdd2) | Dec 28, 2021 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [3ac88f1f0b](https://linux-hardware.org/?probe=3ac88f1f0b) | Dec 28, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [34c9874e50](https://linux-hardware.org/?probe=34c9874e50) | Dec 27, 2021 |
| Dell          | Inspiron 5458               | Notebook    | [58bbd792ef](https://linux-hardware.org/?probe=58bbd792ef) | Dec 27, 2021 |
| Acer          | Aspire 4736                 | Notebook    | [128ea022f0](https://linux-hardware.org/?probe=128ea022f0) | Dec 26, 2021 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [54774d551c](https://linux-hardware.org/?probe=54774d551c) | Dec 26, 2021 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [a3f574b521](https://linux-hardware.org/?probe=a3f574b521) | Dec 26, 2021 |
| MSI           | B450I GAMING PLUS MAX WI... | Desktop     | [9cb5033472](https://linux-hardware.org/?probe=9cb5033472) | Dec 26, 2021 |
| Lenovo        | ThinkPad X200 2024AY7       | Notebook    | [d3c8923c22](https://linux-hardware.org/?probe=d3c8923c22) | Dec 26, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [21f95ee091](https://linux-hardware.org/?probe=21f95ee091) | Dec 25, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [65a1aa570a](https://linux-hardware.org/?probe=65a1aa570a) | Dec 25, 2021 |
| Lenovo        | G40-45 80E1                 | Notebook    | [391b2705c1](https://linux-hardware.org/?probe=391b2705c1) | Dec 25, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | Notebook    | [8910de29bc](https://linux-hardware.org/?probe=8910de29bc) | Dec 25, 2021 |
| Lenovo        | Yoga 7 15ITL5 82BJ          | Convertible | [685afb1399](https://linux-hardware.org/?probe=685afb1399) | Dec 24, 2021 |
| ASUSTek       | ROG STRIX B460-I GAMING     | Desktop     | [258369e6dc](https://linux-hardware.org/?probe=258369e6dc) | Dec 24, 2021 |
| Monster       | ABRA A5 V11.1               | Notebook    | [00b9630631](https://linux-hardware.org/?probe=00b9630631) | Dec 24, 2021 |
| MSI           | MS-AA1511                   | All in one  | [ef477f6784](https://linux-hardware.org/?probe=ef477f6784) | Dec 24, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [d971e22ea1](https://linux-hardware.org/?probe=d971e22ea1) | Dec 24, 2021 |
| Lenovo        | ThinkPad X201 3323LWA       | Notebook    | [7768babe1d](https://linux-hardware.org/?probe=7768babe1d) | Dec 24, 2021 |
| Dell          | Latitude E4310              | Notebook    | [e5b46c1542](https://linux-hardware.org/?probe=e5b46c1542) | Dec 24, 2021 |
| Lenovo        | CRESCENTBAY No DPK          | All in one  | [b5cd12bc15](https://linux-hardware.org/?probe=b5cd12bc15) | Dec 24, 2021 |
| ASRock        | 880GM-LE FX                 | Desktop     | [ed79d730cd](https://linux-hardware.org/?probe=ed79d730cd) | Dec 24, 2021 |
| ASUSTek       | X450LD                      | Notebook    | [b5e36a24f9](https://linux-hardware.org/?probe=b5e36a24f9) | Dec 24, 2021 |
| Lenovo        | IdeaPad Yoga 13 20175       | Notebook    | [0c879745b1](https://linux-hardware.org/?probe=0c879745b1) | Dec 24, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [82a81d9287](https://linux-hardware.org/?probe=82a81d9287) | Dec 24, 2021 |
| ASRock        | H310CM-HDV                  | Desktop     | [3b01d877ce](https://linux-hardware.org/?probe=3b01d877ce) | Dec 24, 2021 |
| MSI           | B250M BAZOOKA               | Desktop     | [af10afb79b](https://linux-hardware.org/?probe=af10afb79b) | Dec 23, 2021 |
| Timi          | TM1701                      | Notebook    | [ce3374e321](https://linux-hardware.org/?probe=ce3374e321) | Dec 23, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [9bd5592765](https://linux-hardware.org/?probe=9bd5592765) | Dec 23, 2021 |
| Medion        | E4213 MD99329               | Notebook    | [8801cfdb2a](https://linux-hardware.org/?probe=8801cfdb2a) | Dec 23, 2021 |
| Teclast       | F15S                        | Notebook    | [8be33fb7e2](https://linux-hardware.org/?probe=8be33fb7e2) | Dec 23, 2021 |
| MSI           | GE72 6QC                    | Notebook    | [8f778b6205](https://linux-hardware.org/?probe=8f778b6205) | Dec 23, 2021 |
| Lenovo        | ThinkPad X220 42912WA       | Notebook    | [c4e472298a](https://linux-hardware.org/?probe=c4e472298a) | Dec 23, 2021 |
| Gigabyte      | Z170N-WIFI-CF               | Desktop     | [9bcfc1e034](https://linux-hardware.org/?probe=9bcfc1e034) | Dec 23, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [8e773bb4e5](https://linux-hardware.org/?probe=8e773bb4e5) | Dec 23, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [a54f9967ef](https://linux-hardware.org/?probe=a54f9967ef) | Dec 23, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [2ca39a2067](https://linux-hardware.org/?probe=2ca39a2067) | Dec 23, 2021 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b73f1f9cb1](https://linux-hardware.org/?probe=b73f1f9cb1) | Dec 23, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [870a0913ee](https://linux-hardware.org/?probe=870a0913ee) | Dec 23, 2021 |
| Dell          | Latitude 3410               | Notebook    | [a0b79031ae](https://linux-hardware.org/?probe=a0b79031ae) | Dec 23, 2021 |
| HP            | 1998                        | Desktop     | [f8e644ed15](https://linux-hardware.org/?probe=f8e644ed15) | Dec 23, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d00c0b2ded](https://linux-hardware.org/?probe=d00c0b2ded) | Dec 23, 2021 |
| ASUSTek       | E502NA                      | Notebook    | [66ade120a5](https://linux-hardware.org/?probe=66ade120a5) | Dec 23, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [d4fcc94659](https://linux-hardware.org/?probe=d4fcc94659) | Dec 22, 2021 |
| SYWZ          | S210H Series                | Desktop     | [df3edf9f7b](https://linux-hardware.org/?probe=df3edf9f7b) | Dec 21, 2021 |
| Lenovo        | XiaoXin-15ARE 2020 81YR     | Notebook    | [fabd656de1](https://linux-hardware.org/?probe=fabd656de1) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [7b2a363709](https://linux-hardware.org/?probe=7b2a363709) | Dec 21, 2021 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [8b33da2ce4](https://linux-hardware.org/?probe=8b33da2ce4) | Dec 21, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [c349552561](https://linux-hardware.org/?probe=c349552561) | Dec 20, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X531... | Notebook    | [d347eea0b2](https://linux-hardware.org/?probe=d347eea0b2) | Dec 19, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [82a9ed12b5](https://linux-hardware.org/?probe=82a9ed12b5) | Dec 19, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [9f084a2062](https://linux-hardware.org/?probe=9f084a2062) | Dec 19, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [342ba009be](https://linux-hardware.org/?probe=342ba009be) | Dec 19, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [9da235adb3](https://linux-hardware.org/?probe=9da235adb3) | Dec 19, 2021 |
| Toshiba       | Satellite C50-B             | Notebook    | [037f47a340](https://linux-hardware.org/?probe=037f47a340) | Dec 19, 2021 |
| Unknown       | Unknown                     | Desktop     | [de9ccde374](https://linux-hardware.org/?probe=de9ccde374) | Dec 18, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [55e4486324](https://linux-hardware.org/?probe=55e4486324) | Dec 18, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [bee0b80356](https://linux-hardware.org/?probe=bee0b80356) | Dec 18, 2021 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [bc4e465833](https://linux-hardware.org/?probe=bc4e465833) | Dec 18, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [b8967e6235](https://linux-hardware.org/?probe=b8967e6235) | Dec 18, 2021 |
| Lenovo        | ThinkPad T430 2349DG5       | Notebook    | [9bd0a6e07d](https://linux-hardware.org/?probe=9bd0a6e07d) | Dec 18, 2021 |
| MSI           | GE72 6QC                    | Notebook    | [1d77c47b4c](https://linux-hardware.org/?probe=1d77c47b4c) | Dec 18, 2021 |
| Acer          | Aspire 5741G                | Notebook    | [702be0b615](https://linux-hardware.org/?probe=702be0b615) | Dec 17, 2021 |
| Acer          | Aspire 5741G                | Notebook    | [60d68b4c13](https://linux-hardware.org/?probe=60d68b4c13) | Dec 17, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [14ffa86838](https://linux-hardware.org/?probe=14ffa86838) | Dec 17, 2021 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [082bd4283a](https://linux-hardware.org/?probe=082bd4283a) | Dec 16, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8b9e71b388](https://linux-hardware.org/?probe=8b9e71b388) | Dec 16, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [f9f891f9b2](https://linux-hardware.org/?probe=f9f891f9b2) | Dec 16, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [e2633be8cd](https://linux-hardware.org/?probe=e2633be8cd) | Dec 16, 2021 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [8218845f08](https://linux-hardware.org/?probe=8218845f08) | Dec 15, 2021 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [4c02cd3e26](https://linux-hardware.org/?probe=4c02cd3e26) | Dec 15, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [9cb226408e](https://linux-hardware.org/?probe=9cb226408e) | Dec 15, 2021 |
| Lenovo        | ThinkPad X250 20CLS2XA00    | Notebook    | [276d570689](https://linux-hardware.org/?probe=276d570689) | Dec 15, 2021 |
| Lenovo        | ThinkPad T540p 20BFS31F0... | Notebook    | [b7b09dcc5e](https://linux-hardware.org/?probe=b7b09dcc5e) | Dec 15, 2021 |
| Lenovo        | ThinkPad W540 20BG0011US    | Notebook    | [ead3a18508](https://linux-hardware.org/?probe=ead3a18508) | Dec 15, 2021 |
| Dell          | Precision M4800             | Notebook    | [90109636fe](https://linux-hardware.org/?probe=90109636fe) | Dec 15, 2021 |
| Dell          | Precision M4800             | Notebook    | [0d1cfc9a0e](https://linux-hardware.org/?probe=0d1cfc9a0e) | Dec 15, 2021 |
| Notebook      | NH5xAx                      | Notebook    | [62f88112f1](https://linux-hardware.org/?probe=62f88112f1) | Dec 14, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [9f5ee59afb](https://linux-hardware.org/?probe=9f5ee59afb) | Dec 14, 2021 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [62f4289baa](https://linux-hardware.org/?probe=62f4289baa) | Dec 14, 2021 |
| ASUSTek       | CM6870                      | Desktop     | [05624c26d2](https://linux-hardware.org/?probe=05624c26d2) | Dec 14, 2021 |
| Foxconn       | 2AB1                        | Desktop     | [d5328cbc95](https://linux-hardware.org/?probe=d5328cbc95) | Dec 14, 2021 |
| Lenovo        | MAHOBAY NO DPK              | Desktop     | [12da1dc78f](https://linux-hardware.org/?probe=12da1dc78f) | Dec 14, 2021 |
| Alienware     | 15 R3                       | Notebook    | [6394aa965a](https://linux-hardware.org/?probe=6394aa965a) | Dec 14, 2021 |
| Acer          | Aspire E5-532G              | Notebook    | [8cbbaee4ad](https://linux-hardware.org/?probe=8cbbaee4ad) | Dec 14, 2021 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [05db94d8a5](https://linux-hardware.org/?probe=05db94d8a5) | Dec 14, 2021 |
| EVGA          | 141-HW-E877                 | Desktop     | [a9d6f7c590](https://linux-hardware.org/?probe=a9d6f7c590) | Dec 14, 2021 |
| ASUSTek       | P8P67 LE                    | Desktop     | [36ce439bef](https://linux-hardware.org/?probe=36ce439bef) | Dec 14, 2021 |
| Lenovo        | ThinkPad T410 2522E38       | Notebook    | [5faef7686a](https://linux-hardware.org/?probe=5faef7686a) | Dec 14, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [ba92d0772e](https://linux-hardware.org/?probe=ba92d0772e) | Dec 14, 2021 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [dc12c3cae7](https://linux-hardware.org/?probe=dc12c3cae7) | Dec 14, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2b3ad3643a](https://linux-hardware.org/?probe=2b3ad3643a) | Dec 14, 2021 |
| HP            | 1587h                       | Desktop     | [b9f599ed03](https://linux-hardware.org/?probe=b9f599ed03) | Dec 13, 2021 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [afbed7279a](https://linux-hardware.org/?probe=afbed7279a) | Dec 13, 2021 |
| ECS           | H61H2-MV                    | Desktop     | [b55aea9c38](https://linux-hardware.org/?probe=b55aea9c38) | Dec 13, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [ebf80cd948](https://linux-hardware.org/?probe=ebf80cd948) | Dec 13, 2021 |
| Acer          | Extensa 5635ZG              | Notebook    | [d232d67b9e](https://linux-hardware.org/?probe=d232d67b9e) | Dec 13, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [5cf5b44fc8](https://linux-hardware.org/?probe=5cf5b44fc8) | Dec 13, 2021 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [fd1da12c59](https://linux-hardware.org/?probe=fd1da12c59) | Dec 13, 2021 |
| Lenovo        | IdeaPad S340-15IWL 81N8     | Notebook    | [91eeb42bcb](https://linux-hardware.org/?probe=91eeb42bcb) | Dec 13, 2021 |
| Acer          | EM61SM/EM61PM               | Desktop     | [2e90062d9a](https://linux-hardware.org/?probe=2e90062d9a) | Dec 12, 2021 |
| Packard Be... | IMEDIA S2185                | Desktop     | [26f91db3d6](https://linux-hardware.org/?probe=26f91db3d6) | Dec 12, 2021 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [b14b8a40ec](https://linux-hardware.org/?probe=b14b8a40ec) | Dec 12, 2021 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [ece425bcfc](https://linux-hardware.org/?probe=ece425bcfc) | Dec 12, 2021 |
| Gigabyte      | G41M-Combo                  | Desktop     | [666796bd7e](https://linux-hardware.org/?probe=666796bd7e) | Dec 12, 2021 |
| HP            | 1495                        | Desktop     | [489e740957](https://linux-hardware.org/?probe=489e740957) | Dec 12, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [981dc4e673](https://linux-hardware.org/?probe=981dc4e673) | Dec 12, 2021 |
| Dell          | Precision 5550              | Notebook    | [9e88f6034f](https://linux-hardware.org/?probe=9e88f6034f) | Dec 12, 2021 |
| System76      | Galago Pro                  | Notebook    | [9fe1e9175f](https://linux-hardware.org/?probe=9fe1e9175f) | Dec 12, 2021 |
| Lenovo        | IdeaPad 510S-14ISK 80TK     | Notebook    | [6343dc8a43](https://linux-hardware.org/?probe=6343dc8a43) | Dec 12, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [5cd58ae5d9](https://linux-hardware.org/?probe=5cd58ae5d9) | Dec 12, 2021 |
| Apple         | MacBookPro11,5              | Notebook    | [e59e1a3c29](https://linux-hardware.org/?probe=e59e1a3c29) | Dec 12, 2021 |
| Lenovo        | ThinkPad X201 3680KC5       | Notebook    | [64958365b3](https://linux-hardware.org/?probe=64958365b3) | Dec 12, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [1812d44a36](https://linux-hardware.org/?probe=1812d44a36) | Dec 12, 2021 |
| Gigabyte      | H81M-S                      | Desktop     | [c11f61f55f](https://linux-hardware.org/?probe=c11f61f55f) | Dec 12, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [da7c19f0b4](https://linux-hardware.org/?probe=da7c19f0b4) | Dec 12, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [85770fb8f5](https://linux-hardware.org/?probe=85770fb8f5) | Dec 12, 2021 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [48325242e3](https://linux-hardware.org/?probe=48325242e3) | Dec 12, 2021 |
| System76      | Darter Pro                  | Notebook    | [2e84db8ffb](https://linux-hardware.org/?probe=2e84db8ffb) | Dec 12, 2021 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [69ecf03c84](https://linux-hardware.org/?probe=69ecf03c84) | Dec 12, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [1bed203660](https://linux-hardware.org/?probe=1bed203660) | Dec 12, 2021 |
| Gigabyte      | Z77-D3H                     | Desktop     | [f73c5829df](https://linux-hardware.org/?probe=f73c5829df) | Dec 12, 2021 |
| ASUSTek       | G75VW                       | Notebook    | [4fce5a6b3b](https://linux-hardware.org/?probe=4fce5a6b3b) | Dec 12, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [a2bfa3a5d3](https://linux-hardware.org/?probe=a2bfa3a5d3) | Dec 12, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [00b5d9eba5](https://linux-hardware.org/?probe=00b5d9eba5) | Dec 12, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [dfa992fc24](https://linux-hardware.org/?probe=dfa992fc24) | Dec 12, 2021 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [15e97e023d](https://linux-hardware.org/?probe=15e97e023d) | Dec 12, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [b9eda20029](https://linux-hardware.org/?probe=b9eda20029) | Dec 12, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [ed5c21cccd](https://linux-hardware.org/?probe=ed5c21cccd) | Dec 11, 2021 |
| ASUSTek       | X99-S                       | Desktop     | [df25f864d4](https://linux-hardware.org/?probe=df25f864d4) | Dec 11, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [330425b3b7](https://linux-hardware.org/?probe=330425b3b7) | Dec 11, 2021 |
| HP            | 86EE                        | All in one  | [1865c9ea80](https://linux-hardware.org/?probe=1865c9ea80) | Dec 11, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c5f999eb1e](https://linux-hardware.org/?probe=c5f999eb1e) | Dec 11, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [882e308c93](https://linux-hardware.org/?probe=882e308c93) | Dec 11, 2021 |
| Dell          | 084J0R A00                  | Desktop     | [dff25b4704](https://linux-hardware.org/?probe=dff25b4704) | Dec 11, 2021 |
| HP            | 8768 A                      | Desktop     | [dddb82f6a8](https://linux-hardware.org/?probe=dddb82f6a8) | Dec 11, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [34dacc4911](https://linux-hardware.org/?probe=34dacc4911) | Dec 11, 2021 |
| ASRock        | H310M-STX                   | Desktop     | [96a7160cee](https://linux-hardware.org/?probe=96a7160cee) | Dec 11, 2021 |
| Acer          | Swift SF314-41              | Notebook    | [4e9e6b5c99](https://linux-hardware.org/?probe=4e9e6b5c99) | Dec 11, 2021 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [1b3b98bfd7](https://linux-hardware.org/?probe=1b3b98bfd7) | Dec 11, 2021 |
| Gigabyte      | Z97X-Gaming GT              | Desktop     | [efb6380716](https://linux-hardware.org/?probe=efb6380716) | Dec 11, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [684572bd8a](https://linux-hardware.org/?probe=684572bd8a) | Dec 11, 2021 |
| ASRock        | H310M-STX                   | Desktop     | [f40860a3ed](https://linux-hardware.org/?probe=f40860a3ed) | Dec 11, 2021 |
| Dell          | 0WR7PY A03                  | Desktop     | [1676bf41af](https://linux-hardware.org/?probe=1676bf41af) | Dec 11, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [debd9b86e1](https://linux-hardware.org/?probe=debd9b86e1) | Dec 11, 2021 |
| Dell          | 00F82W A01                  | Desktop     | [ecdd032df4](https://linux-hardware.org/?probe=ecdd032df4) | Dec 10, 2021 |
| Intel         | NUC5i7RYB H73774-102        | Mini pc     | [9115bc7a4e](https://linux-hardware.org/?probe=9115bc7a4e) | Dec 09, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [e7b92397a3](https://linux-hardware.org/?probe=e7b92397a3) | Dec 09, 2021 |
| Gigabyte      | Z370M AORUS Gaming-CF       | Desktop     | [1a64f6d9ca](https://linux-hardware.org/?probe=1a64f6d9ca) | Dec 09, 2021 |
| ASUSTek       | VivoBook S13 X330FA_S330... | Notebook    | [9a01f01187](https://linux-hardware.org/?probe=9a01f01187) | Dec 09, 2021 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [8fe2d382de](https://linux-hardware.org/?probe=8fe2d382de) | Dec 08, 2021 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [a9cb8442ac](https://linux-hardware.org/?probe=a9cb8442ac) | Dec 08, 2021 |
| Dell          | Inspiron 5468               | Notebook    | [ff0b877d5a](https://linux-hardware.org/?probe=ff0b877d5a) | Dec 08, 2021 |
| Lenovo        | ThinkPad T550 20CJS0S800    | Notebook    | [cf8576527d](https://linux-hardware.org/?probe=cf8576527d) | Dec 07, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [ee8b533768](https://linux-hardware.org/?probe=ee8b533768) | Dec 07, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [b9ebbe30d3](https://linux-hardware.org/?probe=b9ebbe30d3) | Dec 05, 2021 |
| HP            | ENVY Notebook               | Notebook    | [179bd0eae8](https://linux-hardware.org/?probe=179bd0eae8) | Dec 05, 2021 |
| HP            | ENVY Notebook               | Notebook    | [58488b0351](https://linux-hardware.org/?probe=58488b0351) | Dec 05, 2021 |
| Gigabyte      | B550 AORUS MASTER           | Desktop     | [b25e4ae64c](https://linux-hardware.org/?probe=b25e4ae64c) | Dec 05, 2021 |
| Medion        | B360H4-EM V1.0              | Desktop     | [5f5964c9a4](https://linux-hardware.org/?probe=5f5964c9a4) | Dec 05, 2021 |
| Intel         | DH67BL AAG10189-208         | Desktop     | [8647345ee8](https://linux-hardware.org/?probe=8647345ee8) | Dec 05, 2021 |
| MSI           | Summit E13FlipEvo A11MT     | Convertible | [ed656c15ad](https://linux-hardware.org/?probe=ed656c15ad) | Dec 05, 2021 |
| Razer         | Blade Stealth               | Notebook    | [03738c7e11](https://linux-hardware.org/?probe=03738c7e11) | Dec 04, 2021 |
| Dell          | 07C0H8 A00                  | Desktop     | [8b0b4e0427](https://linux-hardware.org/?probe=8b0b4e0427) | Dec 04, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [322f9afcb0](https://linux-hardware.org/?probe=322f9afcb0) | Dec 04, 2021 |
| ASUSTek       | K501UX                      | Notebook    | [3f9b547c57](https://linux-hardware.org/?probe=3f9b547c57) | Dec 04, 2021 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [5efc3e5fc4](https://linux-hardware.org/?probe=5efc3e5fc4) | Dec 03, 2021 |
| HP            | Notebook                    | Notebook    | [9f7082bedb](https://linux-hardware.org/?probe=9f7082bedb) | Dec 03, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [df01b853dd](https://linux-hardware.org/?probe=df01b853dd) | Dec 03, 2021 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [7fd0e9e7cd](https://linux-hardware.org/?probe=7fd0e9e7cd) | Dec 03, 2021 |
| ASUSTek       | TUF Z370-PRO GAMING         | Desktop     | [f35a1d4b6f](https://linux-hardware.org/?probe=f35a1d4b6f) | Dec 02, 2021 |
| Gigabyte      | Z270XP-SLI-CF               | Desktop     | [2f4124145a](https://linux-hardware.org/?probe=2f4124145a) | Dec 01, 2021 |
| Lenovo        | CRESCENTBAY No DPK          | All in one  | [473e7afa6d](https://linux-hardware.org/?probe=473e7afa6d) | Dec 01, 2021 |
| MSI           | B460M-A PRO                 | Desktop     | [53de3c938f](https://linux-hardware.org/?probe=53de3c938f) | Nov 30, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [518ee0b884](https://linux-hardware.org/?probe=518ee0b884) | Nov 30, 2021 |
| Dell          | Inspiron 15-3552            | Notebook    | [7fbb6be9e3](https://linux-hardware.org/?probe=7fbb6be9e3) | Nov 30, 2021 |
| ASUSTek       | K72Jr                       | Notebook    | [405b87f8bf](https://linux-hardware.org/?probe=405b87f8bf) | Nov 29, 2021 |
| ASUSTek       | Rampage III GENE            | Desktop     | [8967a333fa](https://linux-hardware.org/?probe=8967a333fa) | Nov 29, 2021 |
| HP            | Pavilion g7                 | Notebook    | [da6e298046](https://linux-hardware.org/?probe=da6e298046) | Nov 29, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [c5c0c4aca3](https://linux-hardware.org/?probe=c5c0c4aca3) | Nov 29, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [5e6aa10813](https://linux-hardware.org/?probe=5e6aa10813) | Nov 29, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f5a807ee34](https://linux-hardware.org/?probe=f5a807ee34) | Nov 29, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [43ec4aeaa5](https://linux-hardware.org/?probe=43ec4aeaa5) | Nov 28, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [681845a2e3](https://linux-hardware.org/?probe=681845a2e3) | Nov 28, 2021 |
| Apple         | MacBookPro11,2              | Notebook    | [b022b376ee](https://linux-hardware.org/?probe=b022b376ee) | Nov 28, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [73dbadb8f1](https://linux-hardware.org/?probe=73dbadb8f1) | Nov 28, 2021 |
| Dell          | Inspiron 3505               | Notebook    | [d3cfe93dc6](https://linux-hardware.org/?probe=d3cfe93dc6) | Nov 28, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [77a39f82ff](https://linux-hardware.org/?probe=77a39f82ff) | Nov 28, 2021 |
| MSI           | H110M PRO-VD PLUS           | Desktop     | [e6fd06720f](https://linux-hardware.org/?probe=e6fd06720f) | Nov 28, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [be44e9c10b](https://linux-hardware.org/?probe=be44e9c10b) | Nov 28, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | Notebook    | [816aaebc79](https://linux-hardware.org/?probe=816aaebc79) | Nov 27, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6591fce926](https://linux-hardware.org/?probe=6591fce926) | Nov 27, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [3d1d036e1e](https://linux-hardware.org/?probe=3d1d036e1e) | Nov 27, 2021 |
| Lenovo        | ThinkPad T440p 20AWS3DD1... | Notebook    | [162c76040f](https://linux-hardware.org/?probe=162c76040f) | Nov 27, 2021 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [2f2ac97b5b](https://linux-hardware.org/?probe=2f2ac97b5b) | Nov 26, 2021 |
| Lenovo        | V14-ADA 82C6                | Notebook    | [a0f72af8d9](https://linux-hardware.org/?probe=a0f72af8d9) | Nov 26, 2021 |
| ASUSTek       | X556UQK                     | Notebook    | [38ca30691b](https://linux-hardware.org/?probe=38ca30691b) | Nov 26, 2021 |
| Gigabyte      | H81M-S                      | Desktop     | [3df1e42b0e](https://linux-hardware.org/?probe=3df1e42b0e) | Nov 26, 2021 |
| Dell          | 0H4VK7 A01                  | Desktop     | [83171d6677](https://linux-hardware.org/?probe=83171d6677) | Nov 26, 2021 |
| ASRock        | B450 Gaming K4              | Desktop     | [ba4141a214](https://linux-hardware.org/?probe=ba4141a214) | Nov 26, 2021 |
| ASUSTek       | P8Z68 DELUXE                | Desktop     | [5cdb53e7ae](https://linux-hardware.org/?probe=5cdb53e7ae) | Nov 25, 2021 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [9bc92b5ef9](https://linux-hardware.org/?probe=9bc92b5ef9) | Nov 25, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [5575758e0a](https://linux-hardware.org/?probe=5575758e0a) | Nov 25, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [071447b964](https://linux-hardware.org/?probe=071447b964) | Nov 24, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [c30cc4860b](https://linux-hardware.org/?probe=c30cc4860b) | Nov 24, 2021 |
| Apple         | MacBookPro10,1              | Notebook    | [27d5b7dc47](https://linux-hardware.org/?probe=27d5b7dc47) | Nov 24, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [6043e86d2a](https://linux-hardware.org/?probe=6043e86d2a) | Nov 24, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7d4b6453e9](https://linux-hardware.org/?probe=7d4b6453e9) | Nov 24, 2021 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [ce783dccca](https://linux-hardware.org/?probe=ce783dccca) | Nov 24, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [e9b4b7ecba](https://linux-hardware.org/?probe=e9b4b7ecba) | Nov 24, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [485f0b0858](https://linux-hardware.org/?probe=485f0b0858) | Nov 24, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0110ddef8c](https://linux-hardware.org/?probe=0110ddef8c) | Nov 24, 2021 |
| ASRock        | FM2A78M Pro4+               | Desktop     | [1670e83f4d](https://linux-hardware.org/?probe=1670e83f4d) | Nov 24, 2021 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [e215995139](https://linux-hardware.org/?probe=e215995139) | Nov 24, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [93e8bc8935](https://linux-hardware.org/?probe=93e8bc8935) | Nov 24, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1d82d0b32b](https://linux-hardware.org/?probe=1d82d0b32b) | Nov 24, 2021 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b9e2d78f66](https://linux-hardware.org/?probe=b9e2d78f66) | Nov 23, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [6fb3466f59](https://linux-hardware.org/?probe=6fb3466f59) | Nov 23, 2021 |
| HP            | Laptop 14q-cs0xxx           | Notebook    | [c8edde8f8d](https://linux-hardware.org/?probe=c8edde8f8d) | Nov 23, 2021 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [81d28ee0b3](https://linux-hardware.org/?probe=81d28ee0b3) | Nov 23, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [35063b25d7](https://linux-hardware.org/?probe=35063b25d7) | Nov 23, 2021 |
| Dell          | Latitude E5450              | Notebook    | [a1c9396c75](https://linux-hardware.org/?probe=a1c9396c75) | Nov 23, 2021 |
| Lenovo        | IdeaPadFlex 5-1570 81CA     | Convertible | [09ee3255d5](https://linux-hardware.org/?probe=09ee3255d5) | Nov 23, 2021 |
| ASUSTek       | P8Z77-V LE                  | Desktop     | [6994e8dbb3](https://linux-hardware.org/?probe=6994e8dbb3) | Nov 23, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [dba80843bc](https://linux-hardware.org/?probe=dba80843bc) | Nov 23, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [fbc257563e](https://linux-hardware.org/?probe=fbc257563e) | Nov 22, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [8338e70267](https://linux-hardware.org/?probe=8338e70267) | Nov 22, 2021 |
| ASUSTek       | PRIME H310M-K R2.0          | Desktop     | [47fe68608a](https://linux-hardware.org/?probe=47fe68608a) | Nov 22, 2021 |
| Notebook      | NV4XMB,ME,MZ                | Notebook    | [edaff183a5](https://linux-hardware.org/?probe=edaff183a5) | Nov 21, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [a95e047ec3](https://linux-hardware.org/?probe=a95e047ec3) | Nov 20, 2021 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | Notebook    | [dcc60be203](https://linux-hardware.org/?probe=dcc60be203) | Nov 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d0581432da](https://linux-hardware.org/?probe=d0581432da) | Nov 20, 2021 |
| HP            | 158B                        | Desktop     | [28d106042e](https://linux-hardware.org/?probe=28d106042e) | Nov 20, 2021 |
| ASUSTek       | M5401WUA                    | All in one  | [c1f6b30a92](https://linux-hardware.org/?probe=c1f6b30a92) | Nov 18, 2021 |
| ASUSTek       | Z87-A                       | Desktop     | [906510b2cd](https://linux-hardware.org/?probe=906510b2cd) | Nov 18, 2021 |
| HUAWEI        | WRT-WX9                     | Notebook    | [b94e6da627](https://linux-hardware.org/?probe=b94e6da627) | Nov 18, 2021 |
| Dell          | Precision 5550              | Notebook    | [f7853ec2b6](https://linux-hardware.org/?probe=f7853ec2b6) | Nov 18, 2021 |
| Dell          | Inspiron 3558               | Notebook    | [b0f06cc210](https://linux-hardware.org/?probe=b0f06cc210) | Nov 18, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c5c112ae1d](https://linux-hardware.org/?probe=c5c112ae1d) | Nov 18, 2021 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [223642cd17](https://linux-hardware.org/?probe=223642cd17) | Nov 16, 2021 |
| Dell          | Inspiron 3581               | Notebook    | [7025bc6055](https://linux-hardware.org/?probe=7025bc6055) | Nov 16, 2021 |
| ASUSTek       | P8Z77-V                     | Desktop     | [5fc521fe4b](https://linux-hardware.org/?probe=5fc521fe4b) | Nov 15, 2021 |
| Dell          | Inspiron 5579               | Notebook    | [0f7bccdef0](https://linux-hardware.org/?probe=0f7bccdef0) | Nov 15, 2021 |
| Acer          | Predator G3-605             | Desktop     | [5cb8f7dfa7](https://linux-hardware.org/?probe=5cb8f7dfa7) | Nov 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [ab746b7399](https://linux-hardware.org/?probe=ab746b7399) | Nov 12, 2021 |
| Apple         | MacBook5,1                  | Notebook    | [6ddb5fdd76](https://linux-hardware.org/?probe=6ddb5fdd76) | Nov 12, 2021 |
| Gigabyte      | B365M GAMING HD             | Desktop     | [cf60dd841c](https://linux-hardware.org/?probe=cf60dd841c) | Nov 10, 2021 |
| ASRock        | A55M-VS                     | Desktop     | [3e40db1efb](https://linux-hardware.org/?probe=3e40db1efb) | Nov 09, 2021 |
| HP            | 8055                        | Desktop     | [5d16a78abe](https://linux-hardware.org/?probe=5d16a78abe) | Nov 09, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [b64db5197a](https://linux-hardware.org/?probe=b64db5197a) | Nov 09, 2021 |
| Gigabyte      | F2A68HM-H                   | Desktop     | [77b62d6178](https://linux-hardware.org/?probe=77b62d6178) | Nov 09, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [bffba05735](https://linux-hardware.org/?probe=bffba05735) | Nov 08, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [258e2f1594](https://linux-hardware.org/?probe=258e2f1594) | Nov 08, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [4a189c2903](https://linux-hardware.org/?probe=4a189c2903) | Nov 07, 2021 |
| Gigabyte      | B560M DS3H                  | Desktop     | [05314e56c8](https://linux-hardware.org/?probe=05314e56c8) | Nov 07, 2021 |
| Acer          | Swift SF314-41              | Notebook    | [ef268f8220](https://linux-hardware.org/?probe=ef268f8220) | Nov 07, 2021 |
| Dell          | Inspiron 5721               | Notebook    | [d9146c3909](https://linux-hardware.org/?probe=d9146c3909) | Nov 07, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [42e799bba3](https://linux-hardware.org/?probe=42e799bba3) | Nov 06, 2021 |
| Dell          | Latitude E6440              | Notebook    | [38e3c1e18a](https://linux-hardware.org/?probe=38e3c1e18a) | Nov 06, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [88d5f57ea9](https://linux-hardware.org/?probe=88d5f57ea9) | Nov 06, 2021 |
| ASRock        | H81M-DG4                    | Desktop     | [33d4154b93](https://linux-hardware.org/?probe=33d4154b93) | Nov 06, 2021 |
| Dell          | Precision 7510              | Notebook    | [49f177c1c2](https://linux-hardware.org/?probe=49f177c1c2) | Nov 05, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [7e09d7d036](https://linux-hardware.org/?probe=7e09d7d036) | Nov 04, 2021 |
| MSI           | H510M-A PRO                 | Desktop     | [745d661721](https://linux-hardware.org/?probe=745d661721) | Nov 03, 2021 |
| HP            | 630                         | Notebook    | [f01c95d959](https://linux-hardware.org/?probe=f01c95d959) | Nov 03, 2021 |
| Lenovo        | ThinkPad T550 20CJS0S800    | Notebook    | [000c804ed5](https://linux-hardware.org/?probe=000c804ed5) | Nov 03, 2021 |
| Lenovo        | ThinkPad T470 20HES01100    | Notebook    | [d3c8a48b29](https://linux-hardware.org/?probe=d3c8a48b29) | Nov 03, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [54e81a5d8d](https://linux-hardware.org/?probe=54e81a5d8d) | Nov 02, 2021 |
| Acer          | Aspire ES1-311              | Notebook    | [594175a2ac](https://linux-hardware.org/?probe=594175a2ac) | Nov 01, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [f581cf8319](https://linux-hardware.org/?probe=f581cf8319) | Nov 01, 2021 |
| Apple         | MacBookPro8,1               | Notebook    | [6e17fb6ea4](https://linux-hardware.org/?probe=6e17fb6ea4) | Oct 31, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [1069b24865](https://linux-hardware.org/?probe=1069b24865) | Oct 31, 2021 |
| HP            | ProBook 450 G3              | Notebook    | [9e32a01dc0](https://linux-hardware.org/?probe=9e32a01dc0) | Oct 31, 2021 |
| Dell          | XPS 13 9343                 | Notebook    | [0d89b6423c](https://linux-hardware.org/?probe=0d89b6423c) | Oct 31, 2021 |
| MSI           | Z170-A PRO                  | Desktop     | [77006702f8](https://linux-hardware.org/?probe=77006702f8) | Oct 31, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [381023907e](https://linux-hardware.org/?probe=381023907e) | Oct 31, 2021 |
| Intel         | NUC11PHBi7 M26151-403       | Mini pc     | [7f8e6d2da9](https://linux-hardware.org/?probe=7f8e6d2da9) | Oct 31, 2021 |
| Gigabyte      | 945GCM-S2L                  | Desktop     | [35d876d2dc](https://linux-hardware.org/?probe=35d876d2dc) | Oct 30, 2021 |
| ASUSTek       | X99-DELUXE                  | Desktop     | [d3a4772e4e](https://linux-hardware.org/?probe=d3a4772e4e) | Oct 29, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [bd63d5e0cb](https://linux-hardware.org/?probe=bd63d5e0cb) | Oct 28, 2021 |
| Razer         | Blade                       | Notebook    | [744799a3c4](https://linux-hardware.org/?probe=744799a3c4) | Oct 28, 2021 |
| ASRock        | B360M Performance           | Desktop     | [2ff008a28d](https://linux-hardware.org/?probe=2ff008a28d) | Oct 26, 2021 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [c7a0fe2f88](https://linux-hardware.org/?probe=c7a0fe2f88) | Oct 26, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d0cb96f5b2](https://linux-hardware.org/?probe=d0cb96f5b2) | Oct 26, 2021 |
| Dell          | Latitude E6540              | Notebook    | [298ab39418](https://linux-hardware.org/?probe=298ab39418) | Oct 26, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [eaf56ad62b](https://linux-hardware.org/?probe=eaf56ad62b) | Oct 25, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [2eac1bfc4f](https://linux-hardware.org/?probe=2eac1bfc4f) | Oct 24, 2021 |
| MSI           | B450M MORTAR                | Desktop     | [46651b942b](https://linux-hardware.org/?probe=46651b942b) | Oct 23, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d53c49a17f](https://linux-hardware.org/?probe=d53c49a17f) | Oct 23, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [4e11b29d08](https://linux-hardware.org/?probe=4e11b29d08) | Oct 23, 2021 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [be5c338f64](https://linux-hardware.org/?probe=be5c338f64) | Oct 22, 2021 |
| MSI           | Z77A-GD65                   | Desktop     | [5273767a7e](https://linux-hardware.org/?probe=5273767a7e) | Oct 22, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [fe7a37dce1](https://linux-hardware.org/?probe=fe7a37dce1) | Oct 22, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [456b686d28](https://linux-hardware.org/?probe=456b686d28) | Oct 20, 2021 |
| ASUSTek       | X580VD                      | Notebook    | [aff8edafa4](https://linux-hardware.org/?probe=aff8edafa4) | Oct 20, 2021 |
| ASUSTek       | X555LD                      | Notebook    | [eef17ea12f](https://linux-hardware.org/?probe=eef17ea12f) | Oct 20, 2021 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [94848f2347](https://linux-hardware.org/?probe=94848f2347) | Oct 19, 2021 |
| Gigabyte      | F2A88XM-D3HP                | Desktop     | [08715cfcc4](https://linux-hardware.org/?probe=08715cfcc4) | Oct 18, 2021 |
| MSI           | B150 PC MATE                | Desktop     | [f2e71b602e](https://linux-hardware.org/?probe=f2e71b602e) | Oct 18, 2021 |
| Pegatron      | 2AD4                        | Desktop     | [9e231f71ed](https://linux-hardware.org/?probe=9e231f71ed) | Oct 18, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [fb8d7a6a25](https://linux-hardware.org/?probe=fb8d7a6a25) | Oct 18, 2021 |
| Dell          | Latitude E7440              | Notebook    | [98c988645f](https://linux-hardware.org/?probe=98c988645f) | Oct 18, 2021 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [d5bcf80b27](https://linux-hardware.org/?probe=d5bcf80b27) | Oct 17, 2021 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3061eaa067](https://linux-hardware.org/?probe=3061eaa067) | Oct 17, 2021 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [274cba3955](https://linux-hardware.org/?probe=274cba3955) | Oct 17, 2021 |
| Acer          | Aspire SW5-173              | Notebook    | [38872d1422](https://linux-hardware.org/?probe=38872d1422) | Oct 17, 2021 |
| HUAWEI        | WRT-WX9                     | Notebook    | [d9cd722532](https://linux-hardware.org/?probe=d9cd722532) | Oct 17, 2021 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [0c063b9772](https://linux-hardware.org/?probe=0c063b9772) | Oct 17, 2021 |
| ASUSTek       | N53Jq                       | Notebook    | [3cd3bb5eae](https://linux-hardware.org/?probe=3cd3bb5eae) | Oct 16, 2021 |
| Dell          | Inspiron 3520               | Notebook    | [56fe4ab8a1](https://linux-hardware.org/?probe=56fe4ab8a1) | Oct 16, 2021 |
| Acer          | Nitro AN515-55              | Notebook    | [9bf062da25](https://linux-hardware.org/?probe=9bf062da25) | Oct 16, 2021 |
| Dell          | Precision M4800             | Notebook    | [87034ed159](https://linux-hardware.org/?probe=87034ed159) | Oct 16, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8fbafb0d7e](https://linux-hardware.org/?probe=8fbafb0d7e) | Oct 16, 2021 |
| System76      | Pangolin                    | Notebook    | [e4fb2b6b8a](https://linux-hardware.org/?probe=e4fb2b6b8a) | Oct 16, 2021 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [2a03ec745f](https://linux-hardware.org/?probe=2a03ec745f) | Oct 16, 2021 |
| HP            | 8768 A                      | Desktop     | [bd722ad5d5](https://linux-hardware.org/?probe=bd722ad5d5) | Oct 15, 2021 |
| UNITCOM       | W55xEU                      | Notebook    | [ced300109d](https://linux-hardware.org/?probe=ced300109d) | Oct 15, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [e16a7eaba9](https://linux-hardware.org/?probe=e16a7eaba9) | Oct 15, 2021 |
| ASUSTek       | VivoBook_ASUS Laptop X51... | Notebook    | [eed2a8b965](https://linux-hardware.org/?probe=eed2a8b965) | Oct 15, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e025ccbf40](https://linux-hardware.org/?probe=e025ccbf40) | Oct 15, 2021 |
| Dell          | 0RM5DR A00                  | Desktop     | [c35c2fd772](https://linux-hardware.org/?probe=c35c2fd772) | Oct 14, 2021 |
| ASRock        | 4X4-4000 Series             | Desktop     | [fd95402aa1](https://linux-hardware.org/?probe=fd95402aa1) | Oct 14, 2021 |
| ASRock        | 4X4-4000 Series             | Desktop     | [538c0f7723](https://linux-hardware.org/?probe=538c0f7723) | Oct 14, 2021 |
| Lenovo        | G50-30 80G0                 | Notebook    | [3d5411b3f0](https://linux-hardware.org/?probe=3d5411b3f0) | Oct 13, 2021 |
| Dell          | Precision 7510              | Notebook    | [800ca77fe7](https://linux-hardware.org/?probe=800ca77fe7) | Oct 13, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [6bd6fd9002](https://linux-hardware.org/?probe=6bd6fd9002) | Oct 12, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [eb4a97ceef](https://linux-hardware.org/?probe=eb4a97ceef) | Oct 12, 2021 |
| ASUSTek       | B85M-E                      | Desktop     | [d98b27a03c](https://linux-hardware.org/?probe=d98b27a03c) | Oct 11, 2021 |
| HP            | EliteBook 840 G3            | Notebook    | [b3f6912fdd](https://linux-hardware.org/?probe=b3f6912fdd) | Oct 11, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [a94b3893c1](https://linux-hardware.org/?probe=a94b3893c1) | Oct 11, 2021 |
| ASUSTek       | ROG Maximus X HERO          | Desktop     | [70d8ac443f](https://linux-hardware.org/?probe=70d8ac443f) | Oct 11, 2021 |
| Lenovo        | ThinkPad E15 20RD0011AU     | Notebook    | [85c8487ca5](https://linux-hardware.org/?probe=85c8487ca5) | Oct 11, 2021 |
| Samsung       | 550P5C/550P7C               | Notebook    | [3c7018cbdf](https://linux-hardware.org/?probe=3c7018cbdf) | Oct 10, 2021 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [fea72dd4e7](https://linux-hardware.org/?probe=fea72dd4e7) | Oct 10, 2021 |
| Razer         | Blade Stealth               | Notebook    | [82e8aefe39](https://linux-hardware.org/?probe=82e8aefe39) | Oct 09, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [e309ba4276](https://linux-hardware.org/?probe=e309ba4276) | Oct 09, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [e4e8fba89b](https://linux-hardware.org/?probe=e4e8fba89b) | Oct 09, 2021 |
| TUXEDO        | Unknown                     | Notebook    | [59193a23d9](https://linux-hardware.org/?probe=59193a23d9) | Oct 08, 2021 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [168f21cc93](https://linux-hardware.org/?probe=168f21cc93) | Oct 08, 2021 |
| Gigabyte      | Z170-Gaming K3-CF           | Desktop     | [d8a64024f9](https://linux-hardware.org/?probe=d8a64024f9) | Oct 07, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [f50b61b450](https://linux-hardware.org/?probe=f50b61b450) | Oct 06, 2021 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [bd9fe373d2](https://linux-hardware.org/?probe=bd9fe373d2) | Oct 06, 2021 |
| MSI           | GS66 Stealth 10SFS          | Notebook    | [2ff9b97589](https://linux-hardware.org/?probe=2ff9b97589) | Oct 06, 2021 |
| ASUSTek       | STRIX B250F GAMING          | Desktop     | [ceefec9a7f](https://linux-hardware.org/?probe=ceefec9a7f) | Oct 06, 2021 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [d9637236c2](https://linux-hardware.org/?probe=d9637236c2) | Oct 04, 2021 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [e5d1cb1742](https://linux-hardware.org/?probe=e5d1cb1742) | Oct 03, 2021 |
| ASUSTek       | ROG STRIX B460-H GAMING     | Desktop     | [9bec53673d](https://linux-hardware.org/?probe=9bec53673d) | Oct 03, 2021 |
| ASUSTek       | TUF Z390M-PRO GAMING        | Desktop     | [1129266f95](https://linux-hardware.org/?probe=1129266f95) | Oct 03, 2021 |
| ASUSTek       | X99-A                       | Desktop     | [8645db4302](https://linux-hardware.org/?probe=8645db4302) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [3c24d27d51](https://linux-hardware.org/?probe=3c24d27d51) | Oct 02, 2021 |
| Alienware     | 17                          | Notebook    | [1a6f72a2fd](https://linux-hardware.org/?probe=1a6f72a2fd) | Oct 02, 2021 |
| Alienware     | 17                          | Notebook    | [fac8c2f153](https://linux-hardware.org/?probe=fac8c2f153) | Oct 02, 2021 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [1585f476de](https://linux-hardware.org/?probe=1585f476de) | Oct 02, 2021 |
| Dell          | Latitude 5410               | Notebook    | [6928f4237f](https://linux-hardware.org/?probe=6928f4237f) | Oct 01, 2021 |
| Apple         | Mac-BE088AF8C5EB4FA2 iMa... | All in one  | [2642c47cca](https://linux-hardware.org/?probe=2642c47cca) | Sep 30, 2021 |
| HP            | Pavilion dv6                | Notebook    | [ee806bc406](https://linux-hardware.org/?probe=ee806bc406) | Sep 30, 2021 |
| HP            | Pavilion dv6                | Notebook    | [252520800c](https://linux-hardware.org/?probe=252520800c) | Sep 30, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [4ee2cf61ef](https://linux-hardware.org/?probe=4ee2cf61ef) | Sep 29, 2021 |
| Monster       | ABRA A5 V11.1               | Notebook    | [34b6bc562c](https://linux-hardware.org/?probe=34b6bc562c) | Sep 29, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [45605570fe](https://linux-hardware.org/?probe=45605570fe) | Sep 29, 2021 |
| ASRock        | FM2A75M Pro4+               | Desktop     | [d0f4eaa9f8](https://linux-hardware.org/?probe=d0f4eaa9f8) | Sep 29, 2021 |
| Apple         | MacBookAir7,1               | Notebook    | [4642e930ca](https://linux-hardware.org/?probe=4642e930ca) | Sep 28, 2021 |
| Lenovo        | IdeaPadFlex 5-1570 81CA     | Convertible | [b0981c3629](https://linux-hardware.org/?probe=b0981c3629) | Sep 28, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1121eb673b](https://linux-hardware.org/?probe=1121eb673b) | Sep 27, 2021 |
| Monster       | ABRA A5 V11.1               | Notebook    | [b70d12e2f5](https://linux-hardware.org/?probe=b70d12e2f5) | Sep 27, 2021 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [9cd2ba74a0](https://linux-hardware.org/?probe=9cd2ba74a0) | Sep 27, 2021 |
| Timi          | TM1607                      | Notebook    | [aa8b5d346a](https://linux-hardware.org/?probe=aa8b5d346a) | Sep 26, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [e47c168067](https://linux-hardware.org/?probe=e47c168067) | Sep 25, 2021 |
| Apple         | Mac-77EB7D7DAF985301 iMa... | All in one  | [c8d45803a2](https://linux-hardware.org/?probe=c8d45803a2) | Sep 25, 2021 |
| Supermicro    | X8DTH                       | Server      | [d3dc168a2a](https://linux-hardware.org/?probe=d3dc168a2a) | Sep 25, 2021 |
| Lenovo        | ThinkPad T450s 20BWS07N0... | Notebook    | [cb83c57f1c](https://linux-hardware.org/?probe=cb83c57f1c) | Sep 24, 2021 |
| Lenovo        | ThinkPad T480s 20L8S0230... | Notebook    | [04b5e431fe](https://linux-hardware.org/?probe=04b5e431fe) | Sep 24, 2021 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [434da8cb2d](https://linux-hardware.org/?probe=434da8cb2d) | Sep 24, 2021 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | Notebook    | [de3b970f84](https://linux-hardware.org/?probe=de3b970f84) | Sep 23, 2021 |
| Lenovo        | ThinkPad P50 20ENCTO1WW     | Notebook    | [7d9277109c](https://linux-hardware.org/?probe=7d9277109c) | Sep 23, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [d8d6573dea](https://linux-hardware.org/?probe=d8d6573dea) | Sep 23, 2021 |
| Lenovo        | Yoga C740 81TC              | Convertible | [0263be5c11](https://linux-hardware.org/?probe=0263be5c11) | Sep 23, 2021 |
| Toshiba       | IS 1442                     | Notebook    | [26b3724f40](https://linux-hardware.org/?probe=26b3724f40) | Sep 22, 2021 |
| Gigabyte      | H61M-DS2 DVI                | Desktop     | [92e151e105](https://linux-hardware.org/?probe=92e151e105) | Sep 22, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [72b58edccd](https://linux-hardware.org/?probe=72b58edccd) | Sep 21, 2021 |
| Samsung       | QX311/QX411/QX412/QX511     | Notebook    | [9c968d26f7](https://linux-hardware.org/?probe=9c968d26f7) | Sep 21, 2021 |
| Seeed Stud... | ODYSSEY-X86J41X5 SD-BS-C... | Desktop     | [855a10f536](https://linux-hardware.org/?probe=855a10f536) | Sep 21, 2021 |
| ASUSTek       | UX550VE                     | Notebook    | [72925fef5d](https://linux-hardware.org/?probe=72925fef5d) | Sep 21, 2021 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [2aab2f6ffb](https://linux-hardware.org/?probe=2aab2f6ffb) | Sep 21, 2021 |
| Lenovo        | 36C5 SDK0J40709 WIN 3259... | Desktop     | [49e564cb99](https://linux-hardware.org/?probe=49e564cb99) | Sep 21, 2021 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [75c3385947](https://linux-hardware.org/?probe=75c3385947) | Sep 20, 2021 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [bd2cfcf1ee](https://linux-hardware.org/?probe=bd2cfcf1ee) | Sep 20, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [17c3ec978f](https://linux-hardware.org/?probe=17c3ec978f) | Sep 20, 2021 |
| ASUSTek       | X441SA                      | Notebook    | [f107358f2a](https://linux-hardware.org/?probe=f107358f2a) | Sep 20, 2021 |
| Supermicro    | X8DTH                       | Server      | [d6a6b87b9c](https://linux-hardware.org/?probe=d6a6b87b9c) | Sep 20, 2021 |
| Maibenben     | PC34 V1.0                   | Desktop     | [10d3e02dfb](https://linux-hardware.org/?probe=10d3e02dfb) | Sep 19, 2021 |
| HP            | 250 G6 Notebook PC          | Notebook    | [3caff8f18f](https://linux-hardware.org/?probe=3caff8f18f) | Sep 19, 2021 |
| MSI           | GF63 Thin 10SCSR            | Notebook    | [b4b1c2d06c](https://linux-hardware.org/?probe=b4b1c2d06c) | Sep 19, 2021 |
| MSI           | H510M-A PRO                 | Desktop     | [edb11a70a9](https://linux-hardware.org/?probe=edb11a70a9) | Sep 19, 2021 |
| Dell          | Inspiron 1545               | Notebook    | [45b03d16ce](https://linux-hardware.org/?probe=45b03d16ce) | Sep 18, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [a73053ecf3](https://linux-hardware.org/?probe=a73053ecf3) | Sep 18, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/ArcoLinux/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| ArcoLinux Rolling     | 1175      | 88.75%  |
| ArcoLinux             | 101       | 7.63%   |
| ArcoLinux 20.6.5      | 11        | 0.83%   |
| ArcoLinux 20.7.5      | 8         | 0.6%    |
| ArcoLinux 20.3.4      | 4         | 0.3%    |
| ArcoLinux 20.3.3      | 3         | 0.23%   |
| ArcoLinux 20.2.12     | 3         | 0.23%   |
| ArcoLinux 19.12.15    | 3         | 0.23%   |
| ArcoLinux 19.07.11    | 3         | 0.23%   |
| ArcoLinux 20.1.4      | 2         | 0.15%   |
| ArcoLinux 19.02.4     | 2         | 0.15%   |
| ArcoLinux I3-v19.02.4 | 1         | 0.08%   |
| ArcoLinux 6.9.2       | 1         | 0.08%   |
| ArcoLinux 6.9.1       | 1         | 0.08%   |
| ArcoLinux 20.5.7      | 1         | 0.08%   |
| ArcoLinux 20.5.2      | 1         | 0.08%   |
| ArcoLinux 20.4.11     | 1         | 0.08%   |
| ArcoLinux 20.2.9      | 1         | 0.08%   |
| ArcoLinux 19.11.3     | 1         | 0.08%   |
| ArcoLinux 19.03.3     | 1         | 0.08%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| ArcoLinux | 1316      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version           | Computers | Percent |
|-------------------|-----------|---------|
| 5.15.7-arch1-1    | 48        | 3.11%   |
| 5.15.10-arch1-1   | 39        | 2.52%   |
| 5.13.13-arch1-1   | 38        | 2.46%   |
| 5.14.14-arch1-1   | 26        | 1.68%   |
| 5.16.11-arch1-1   | 25        | 1.62%   |
| 5.13.12-arch1-1   | 22        | 1.42%   |
| 5.14.12-arch1-1   | 21        | 1.36%   |
| 5.17.1-arch1-1    | 18        | 1.17%   |
| 5.8.14-arch1-1    | 16        | 1.04%   |
| 5.12.13-arch1-2   | 16        | 1.04%   |
| 5.9.14-arch1-1    | 15        | 0.97%   |
| 5.16.2-arch1-1    | 15        | 0.97%   |
| 5.12.15-arch1-1   | 15        | 0.97%   |
| 5.15.5-arch1-1    | 14        | 0.91%   |
| 5.9.8-arch1-1     | 13        | 0.84%   |
| 5.15.4-arch1-1    | 13        | 0.84%   |
| 5.15.11-arch2-1   | 13        | 0.84%   |
| 5.12.12-arch1-1   | 13        | 0.84%   |
| 5.9.1-arch1-1     | 12        | 0.78%   |
| 5.17.9-arch1-1    | 12        | 0.78%   |
| 5.17.5-arch1-1    | 12        | 0.78%   |
| 5.15.2-arch1-1    | 12        | 0.78%   |
| 5.12.10-arch1-1   | 12        | 0.78%   |
| 5.10.84-1-lts     | 12        | 0.78%   |
| 5.9.6-arch1-1     | 11        | 0.71%   |
| 5.18.3-arch1-1    | 11        | 0.71%   |
| 5.17.4-arch1-1    | 11        | 0.71%   |
| 5.16.10-arch1-1   | 11        | 0.71%   |
| 5.12.14-arch1-1   | 11        | 0.71%   |
| 5.9.10-arch1-1    | 10        | 0.65%   |
| 5.18.16-arch1-1   | 10        | 0.65%   |
| 5.16.16-arch1-1   | 10        | 0.65%   |
| 5.15.7-zen1-1-zen | 10        | 0.65%   |
| 5.15.6-arch2-1    | 10        | 0.65%   |
| 5.15.12-arch1-1   | 10        | 0.65%   |
| 5.14.6-arch1-1    | 10        | 0.65%   |
| 5.13.8-arch1-1    | 10        | 0.65%   |
| 5.18.1-arch1-1    | 9         | 0.58%   |
| 5.15.13-arch1-1   | 9         | 0.58%   |
| 5.11.6-arch1-1    | 9         | 0.58%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15.7  | 59        | 3.82%   |
| 5.15.10 | 41        | 2.65%   |
| 5.13.13 | 38        | 2.46%   |
| 5.16.11 | 28        | 1.81%   |
| 5.14.14 | 26        | 1.68%   |
| 5.17.1  | 25        | 1.62%   |
| 5.14.12 | 24        | 1.55%   |
| 5.13.12 | 24        | 1.55%   |
| 5.9.14  | 19        | 1.23%   |
| 5.16.2  | 19        | 1.23%   |
| 5.9.8   | 18        | 1.17%   |
| 5.17.5  | 18        | 1.17%   |
| 5.15.4  | 18        | 1.17%   |
| 5.12.15 | 18        | 1.17%   |
| 5.12.13 | 18        | 1.17%   |
| 5.8.14  | 17        | 1.1%    |
| 5.9.6   | 16        | 1.04%   |
| 5.15.5  | 16        | 1.04%   |
| 5.9.1   | 15        | 0.97%   |
| 5.15.2  | 14        | 0.91%   |
| 5.15.11 | 14        | 0.91%   |
| 5.12.12 | 14        | 0.91%   |
| 5.17.9  | 13        | 0.84%   |
| 5.15.6  | 13        | 0.84%   |
| 5.14.9  | 13        | 0.84%   |
| 5.9.10  | 12        | 0.78%   |
| 5.18.3  | 12        | 0.78%   |
| 5.16.16 | 12        | 0.78%   |
| 5.16.10 | 12        | 0.78%   |
| 5.15.12 | 12        | 0.78%   |
| 5.12.10 | 12        | 0.78%   |
| 5.10.84 | 12        | 0.78%   |
| 5.10.16 | 12        | 0.78%   |
| 5.18.16 | 11        | 0.71%   |
| 5.17.4  | 11        | 0.71%   |
| 5.15.13 | 11        | 0.71%   |
| 5.14.6  | 11        | 0.71%   |
| 5.12.14 | 11        | 0.71%   |
| 5.9.11  | 10        | 0.65%   |
| 5.18.5  | 10        | 0.65%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 264       | 17.69%  |
| 5.10    | 213       | 14.28%  |
| 5.16    | 130       | 8.71%   |
| 5.14    | 130       | 8.71%   |
| 5.9     | 109       | 7.31%   |
| 5.13    | 109       | 7.31%   |
| 5.12    | 107       | 7.17%   |
| 5.17    | 91        | 6.1%    |
| 5.18    | 86        | 5.76%   |
| 5.11    | 77        | 5.16%   |
| 5.4     | 60        | 4.02%   |
| 5.19    | 52        | 3.49%   |
| 5.8     | 34        | 2.28%   |
| 5.6     | 7         | 0.47%   |
| 5.7     | 6         | 0.4%    |
| 5.5     | 5         | 0.34%   |
| 5.3     | 3         | 0.2%    |
| 5.0     | 3         | 0.2%    |
| 4.19    | 2         | 0.13%   |
| 5.2     | 1         | 0.07%   |
| 4.20    | 1         | 0.07%   |
| 4.18    | 1         | 0.07%   |
| 4.17    | 1         | 0.07%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 1316      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| XFCE           | 461       | 33.31%  |
| KDE5           | 245       | 17.7%   |
| i3             | 95        | 6.86%   |
| GNOME          | 85        | 6.14%   |
| awesome        | 84        | 6.07%   |
| qtile          | 62        | 4.48%   |
| X-Cinnamon     | 50        | 3.61%   |
| bspwm          | 46        | 3.32%   |
| xmonad         | 44        | 3.18%   |
| DWM            | 39        | 2.82%   |
| KDE            | 25        | 1.81%   |
| Unknown        | 25        | 1.81%   |
| LeftWM         | 19        | 1.37%   |
| Deepin         | 18        | 1.3%    |
| Cinnamon       | 14        | 1.01%   |
| LXQt           | 12        | 0.87%   |
| Budgie         | 11        | 0.79%   |
| MATE           | 10        | 0.72%   |
| herbstluftwm   | 10        | 0.72%   |
| i3-with-shmlog | 8         | 0.58%   |
| Cutefish       | 4         | 0.29%   |
| Unity          | 3         | 0.22%   |
| spectrwm       | 3         | 0.22%   |
| openbox        | 2         | 0.14%   |
| ICEWM          | 2         | 0.14%   |
| dusk           | 2         | 0.14%   |
| cwm            | 2         | 0.14%   |
| sway           | 1         | 0.07%   |
| jwm            | 1         | 0.07%   |
| dwm-sc         | 1         | 0.07%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1214      | 91.62%  |
| Tty     | 77        | 5.81%   |
| Wayland | 24        | 1.81%   |
| Unknown | 10        | 0.75%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 699       | 50.18%  |
| TDM     | 295       | 21.18%  |
| LightDM | 232       | 16.65%  |
| Unknown | 140       | 10.05%  |
| GDM     | 19        | 1.36%   |
| Ly      | 5         | 0.36%   |
| XDM     | 1         | 0.07%   |
| SLiM    | 1         | 0.07%   |
| LXDM    | 1         | 0.07%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 778       | 58.41%  |
| en_GB   | 113       | 8.48%   |
| de_DE   | 63        | 4.73%   |
| en_CA   | 46        | 3.45%   |
| en_IN   | 33        | 2.48%   |
| fr_FR   | 29        | 2.18%   |
| en_AU   | 29        | 2.18%   |
| ru_RU   | 18        | 1.35%   |
| es_ES   | 18        | 1.35%   |
| pt_BR   | 17        | 1.28%   |
| Unknown | 14        | 1.05%   |
| pl_PL   | 13        | 0.98%   |
| hu_HU   | 10        | 0.75%   |
| es_AR   | 10        | 0.75%   |
| sv_SE   | 9         | 0.68%   |
| en_ZA   | 9         | 0.68%   |
| it_IT   | 8         | 0.6%    |
| tr_TR   | 7         | 0.53%   |
| nl_NL   | 6         | 0.45%   |
| fi_FI   | 6         | 0.45%   |
| en_IE   | 6         | 0.45%   |
| ru_UA   | 5         | 0.38%   |
| nl_BE   | 5         | 0.38%   |
| fr_CA   | 5         | 0.38%   |
| en_SG   | 5         | 0.38%   |
| en_IL   | 5         | 0.38%   |
| en_DK   | 5         | 0.38%   |
| pt_PT   | 4         | 0.3%    |
| de_CH   | 4         | 0.3%    |
| zh_CN   | 3         | 0.23%   |
| ja_JP   | 3         | 0.23%   |
| es_MX   | 3         | 0.23%   |
| es_CL   | 3         | 0.23%   |
| el_GR   | 3         | 0.23%   |
| de_AT   | 3         | 0.23%   |
| da_DK   | 3         | 0.23%   |
| ro_RO   | 2         | 0.15%   |
| fr_BE   | 2         | 0.15%   |
| es_CO   | 2         | 0.15%   |
| en_PH   | 2         | 0.15%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 938       | 70.69%  |
| BIOS | 389       | 29.31%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1014      | 75.5%   |
| Btrfs   | 228       | 16.98%  |
| Overlay | 64        | 4.77%   |
| Xfs     | 17        | 1.27%   |
| F2fs    | 10        | 0.74%   |
| Unknown | 8         | 0.6%    |
| Jfs     | 2         | 0.15%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 992       | 74.47%  |
| MBR     | 209       | 15.69%  |
| Unknown | 131       | 9.83%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1009      | 74.8%   |
| Yes       | 340       | 25.2%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 802       | 60.39%  |
| Yes       | 526       | 39.61%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 252       | 19.15%  |
| Lenovo              | 240       | 18.24%  |
| Dell                | 144       | 10.94%  |
| Hewlett-Packard     | 132       | 10.03%  |
| Gigabyte Technology | 107       | 8.13%   |
| MSI                 | 97        | 7.37%   |
| Acer                | 57        | 4.33%   |
| ASRock              | 56        | 4.26%   |
| Apple               | 39        | 2.96%   |
| Supermicro          | 18        | 1.37%   |
| Toshiba             | 15        | 1.14%   |
| Intel               | 12        | 0.91%   |
| Unknown             | 12        | 0.91%   |
| Samsung Electronics | 9         | 0.68%   |
| Medion              | 9         | 0.68%   |
| System76            | 8         | 0.61%   |
| Sony                | 8         | 0.61%   |
| Razer               | 7         | 0.53%   |
| HUAWEI              | 7         | 0.53%   |
| Fujitsu             | 7         | 0.53%   |
| Notebook            | 6         | 0.46%   |
| Alienware           | 6         | 0.46%   |
| TUXEDO              | 5         | 0.38%   |
| Timi                | 5         | 0.38%   |
| Pegatron            | 4         | 0.3%    |
| Foxconn             | 3         | 0.23%   |
| Chuwi               | 3         | 0.23%   |
| Casper              | 3         | 0.23%   |
| ZOTAC               | 2         | 0.15%   |
| Teclast             | 2         | 0.15%   |
| Shuttle             | 2         | 0.15%   |
| Schenker            | 2         | 0.15%   |
| Packard Bell        | 2         | 0.15%   |
| LG Electronics      | 2         | 0.15%   |
| Biostar             | 2         | 0.15%   |
| AZW                 | 2         | 0.15%   |
| Xplore              | 1         | 0.08%   |
| VS Company          | 1         | 0.08%   |
| UNITCOM             | 1         | 0.08%   |
| SYWZ                | 1         | 0.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                             | Computers | Percent |
|----------------------------------|-----------|---------|
| Unknown                          | 16        | 1.22%   |
| ASUS TUF Gaming X570-PLUS        | 13        | 0.99%   |
| ASUS All Series                  | 11        | 0.84%   |
| Supermicro SYS-5019A-FTN4        | 10        | 0.76%   |
| ASUS ROG STRIX B550-F GAMING     | 10        | 0.76%   |
| MSI MS-7C37                      | 7         | 0.53%   |
| MSI MS-7C91                      | 6         | 0.46%   |
| HP Pavilion Notebook             | 6         | 0.46%   |
| ASUS PRIME X570-P                | 6         | 0.46%   |
| ASUS PRIME X470-PRO              | 6         | 0.46%   |
| MSI MS-7B79                      | 5         | 0.38%   |
| HP Notebook                      | 5         | 0.38%   |
| Razer Blade                      | 4         | 0.3%    |
| MSI MS-7B89                      | 4         | 0.3%    |
| MSI MS-7971                      | 4         | 0.3%    |
| Lenovo Legion 5 Pro 16ACH6H 82JQ | 4         | 0.3%    |
| HP EliteBook 840 G3              | 4         | 0.3%    |
| Gigabyte X570 AORUS MASTER       | 4         | 0.3%    |
| Dell OptiPlex 7010               | 4         | 0.3%    |
| ASUS Z170 PRO GAMING             | 4         | 0.3%    |
| ASUS STRIX Z270H GAMING          | 4         | 0.3%    |
| ASUS PRIME B450M-A               | 4         | 0.3%    |
| ASUS PRIME A320M-K               | 4         | 0.3%    |
| ASRock B450M Pro4                | 4         | 0.3%    |
| Timi TM1607                      | 3         | 0.23%   |
| MSI MS-7C95                      | 3         | 0.23%   |
| MSI MS-7B98                      | 3         | 0.23%   |
| MSI MS-7B86                      | 3         | 0.23%   |
| MSI MS-7A38                      | 3         | 0.23%   |
| MSI MS-7817                      | 3         | 0.23%   |
| Lenovo Legion Y540-15IRH 81SX    | 3         | 0.23%   |
| Lenovo Legion 5 15ARH05 82B5     | 3         | 0.23%   |
| Lenovo IdeaPad 5 14ARE05 81YM    | 3         | 0.23%   |
| HP Laptop 15s-eq2xxx             | 3         | 0.23%   |
| HP EliteDesk 800 G1 SFF          | 3         | 0.23%   |
| HP EliteBook 8460p               | 3         | 0.23%   |
| HP 255 G7 Notebook PC            | 3         | 0.23%   |
| Gigabyte X570 GAMING X           | 3         | 0.23%   |
| Gigabyte X570 AORUS PRO WIFI     | 3         | 0.23%   |
| Gigabyte B450 AORUS M            | 3         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                      | Computers | Percent |
|---------------------------|-----------|---------|
| Lenovo ThinkPad           | 116       | 8.81%   |
| Lenovo IdeaPad            | 45        | 3.42%   |
| Dell Inspiron             | 43        | 3.27%   |
| ASUS ROG                  | 41        | 3.12%   |
| ASUS PRIME                | 41        | 3.12%   |
| Dell Latitude             | 36        | 2.74%   |
| Acer Aspire               | 36        | 2.74%   |
| ASUS TUF                  | 33        | 2.51%   |
| Dell XPS                  | 25        | 1.9%    |
| HP Pavilion               | 20        | 1.52%   |
| Lenovo Legion             | 19        | 1.44%   |
| HP Laptop                 | 19        | 1.44%   |
| ASUS VivoBook             | 19        | 1.44%   |
| Dell OptiPlex             | 18        | 1.37%   |
| HP EliteBook              | 17        | 1.29%   |
| Unknown                   | 16        | 1.22%   |
| Lenovo Yoga               | 14        | 1.06%   |
| Gigabyte X570             | 13        | 0.99%   |
| Toshiba Satellite         | 12        | 0.91%   |
| HP ENVY                   | 12        | 0.91%   |
| ASUS All                  | 11        | 0.84%   |
| Supermicro SYS-5019A-FTN4 | 10        | 0.76%   |
| Lenovo ThinkCentre        | 10        | 0.76%   |
| Gigabyte B450             | 9         | 0.68%   |
| Dell Vostro               | 9         | 0.68%   |
| Dell Precision            | 9         | 0.68%   |
| Apple MacBookPro11        | 8         | 0.61%   |
| Acer Nitro                | 8         | 0.61%   |
| Razer Blade               | 7         | 0.53%   |
| MSI MS-7C37               | 7         | 0.53%   |
| HP ProBook                | 7         | 0.53%   |
| HP EliteDesk              | 7         | 0.53%   |
| ASUS STRIX                | 7         | 0.53%   |
| MSI MS-7C91               | 6         | 0.46%   |
| HP Compaq                 | 6         | 0.46%   |
| Gigabyte B450M            | 6         | 0.46%   |
| Fujitsu LIFEBOOK          | 6         | 0.46%   |
| ASUS P8Z77-V              | 6         | 0.46%   |
| ASRock B450M              | 6         | 0.46%   |
| MSI MS-7B79               | 5         | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2019    | 188       | 14.29%  |
| 2020    | 174       | 13.22%  |
| 2018    | 174       | 13.22%  |
| 2017    | 124       | 9.42%   |
| 2016    | 84        | 6.38%   |
| 2011    | 83        | 6.31%   |
| 2013    | 82        | 6.23%   |
| 2021    | 80        | 6.08%   |
| 2015    | 79        | 6%      |
| 2012    | 73        | 5.55%   |
| 2014    | 60        | 4.56%   |
| 2010    | 56        | 4.26%   |
| 2009    | 25        | 1.9%    |
| 2008    | 16        | 1.22%   |
| 2007    | 6         | 0.46%   |
| 2022    | 5         | 0.38%   |
| 2006    | 5         | 0.38%   |
| 2005    | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 688       | 52.28%  |
| Desktop     | 562       | 42.71%  |
| Convertible | 31        | 2.36%   |
| All in one  | 15        | 1.14%   |
| Mini pc     | 11        | 0.84%   |
| Server      | 5         | 0.38%   |
| Tablet      | 3         | 0.23%   |
| Stick pc    | 1         | 0.08%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1316      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1311      | 99.62%  |
| Yes  | 5         | 0.38%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 363       | 27.23%  |
| 4.01-8.0    | 309       | 23.18%  |
| 8.01-16.0   | 232       | 17.4%   |
| 32.01-64.0  | 202       | 15.15%  |
| 3.01-4.0    | 133       | 9.98%   |
| 64.01-256.0 | 41        | 3.08%   |
| 24.01-32.0  | 29        | 2.18%   |
| 1.01-2.0    | 16        | 1.2%    |
| 2.01-3.0    | 7         | 0.53%   |
| Unknown     | 1         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 451       | 30.93%  |
| 2.01-3.0   | 368       | 25.24%  |
| 4.01-8.0   | 217       | 14.88%  |
| 3.01-4.0   | 190       | 13.03%  |
| 0.51-1.0   | 139       | 9.53%   |
| 8.01-16.0  | 60        | 4.12%   |
| 0.01-0.5   | 27        | 1.85%   |
| 16.01-24.0 | 4         | 0.27%   |
| 24.01-32.0 | 1         | 0.07%   |
| Unknown    | 1         | 0.07%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 635       | 46.83%  |
| 2      | 387       | 28.54%  |
| 3      | 152       | 11.21%  |
| 4      | 97        | 7.15%   |
| 5      | 45        | 3.32%   |
| 6      | 16        | 1.18%   |
| 7      | 9         | 0.66%   |
| 0      | 6         | 0.44%   |
| 9      | 4         | 0.29%   |
| 8      | 3         | 0.22%   |
| 11     | 1         | 0.07%   |
| 10     | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 937       | 70.77%  |
| Yes       | 387       | 29.23%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1167      | 88.48%  |
| No        | 152       | 11.52%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 991       | 75.19%  |
| No        | 327       | 24.81%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 882       | 66.02%  |
| No        | 454       | 33.98%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 293       | 22.18%  |
| Germany      | 102       | 7.72%   |
| UK           | 80        | 6.06%   |
| Canada       | 62        | 4.69%   |
| India        | 52        | 3.94%   |
| France       | 38        | 2.88%   |
| Brazil       | 38        | 2.88%   |
| Belgium      | 34        | 2.57%   |
| Netherlands  | 32        | 2.42%   |
| Australia    | 31        | 2.35%   |
| Russia       | 28        | 2.12%   |
| Spain        | 25        | 1.89%   |
| Poland       | 24        | 1.82%   |
| Italy        | 24        | 1.82%   |
| Sweden       | 22        | 1.67%   |
| Switzerland  | 21        | 1.59%   |
| Turkey       | 20        | 1.51%   |
| Argentina    | 18        | 1.36%   |
| Hungary      | 17        | 1.29%   |
| Ukraine      | 16        | 1.21%   |
| Romania      | 16        | 1.21%   |
| Norway       | 15        | 1.14%   |
| Finland      | 14        | 1.06%   |
| Indonesia    | 13        | 0.98%   |
| Greece       | 13        | 0.98%   |
| Bulgaria     | 13        | 0.98%   |
| Portugal     | 11        | 0.83%   |
| South Africa | 10        | 0.76%   |
| Mexico       | 9         | 0.68%   |
| Ireland      | 9         | 0.68%   |
| Bangladesh   | 9         | 0.68%   |
| Austria      | 9         | 0.68%   |
| Denmark      | 8         | 0.61%   |
| Czechia      | 8         | 0.61%   |
| Colombia     | 8         | 0.61%   |
| Japan        | 7         | 0.53%   |
| Egypt        | 7         | 0.53%   |
| China        | 7         | 0.53%   |
| Slovakia     | 6         | 0.45%   |
| Serbia       | 6         | 0.45%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Sydney            | 17        | 1.24%   |
| Durham            | 17        | 1.24%   |
| Berlin            | 15        | 1.09%   |
| Lier              | 10        | 0.73%   |
| Madrid            | 9         | 0.66%   |
| Warsaw            | 8         | 0.58%   |
| Pune              | 8         | 0.58%   |
| Paris             | 8         | 0.58%   |
| Houston           | 8         | 0.58%   |
| Sofia             | 7         | 0.51%   |
| Sao Paulo         | 7         | 0.51%   |
| Moscow            | 7         | 0.51%   |
| London            | 7         | 0.51%   |
| Helsinki          | 7         | 0.51%   |
| Athens            | 7         | 0.51%   |
| Amsterdam         | 7         | 0.51%   |
| Zurich            | 6         | 0.44%   |
| Wilrijk           | 6         | 0.44%   |
| Vienna            | 6         | 0.44%   |
| Toronto           | 6         | 0.44%   |
| Frankfurt am Main | 6         | 0.44%   |
| Central           | 6         | 0.44%   |
| Budapest          | 6         | 0.44%   |
| Brooklyn          | 6         | 0.44%   |
| Bengaluru         | 6         | 0.44%   |
| Tallinn           | 5         | 0.36%   |
| Stockholm         | 5         | 0.36%   |
| Rio de Janeiro    | 5         | 0.36%   |
| Portland          | 5         | 0.36%   |
| Oslo              | 5         | 0.36%   |
| Melbourne         | 5         | 0.36%   |
| Kyiv              | 5         | 0.36%   |
| Istanbul          | 5         | 0.36%   |
| Dublin            | 5         | 0.36%   |
| Dallas            | 5         | 0.36%   |
| Chicago           | 5         | 0.36%   |
| Bucharest         | 5         | 0.36%   |
| Belgrade          | 5         | 0.36%   |
| Tehran            | 4         | 0.29%   |
| Shetland Islands  | 4         | 0.29%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 420       | 690    | 18.84%  |
| WDC                       | 373       | 581    | 16.73%  |
| Seagate                   | 306       | 455    | 13.73%  |
| Toshiba                   | 146       | 186    | 6.55%   |
| Kingston                  | 117       | 144    | 5.25%   |
| SanDisk                   | 100       | 116    | 4.49%   |
| Crucial                   | 95        | 138    | 4.26%   |
| Intel                     | 60        | 82     | 2.69%   |
| SK hynix                  | 56        | 67     | 2.51%   |
| Hitachi                   | 45        | 52     | 2.02%   |
| A-DATA Technology         | 39        | 48     | 1.75%   |
| Unknown                   | 36        | 51     | 1.62%   |
| HGST                      | 34        | 44     | 1.53%   |
| Phison                    | 27        | 44     | 1.21%   |
| Apple                     | 25        | 35     | 1.12%   |
| Micron Technology         | 24        | 25     | 1.08%   |
| PNY                       | 20        | 31     | 0.9%    |
| SPCC                      | 17        | 21     | 0.76%   |
| Corsair                   | 17        | 25     | 0.76%   |
| JMicron Technology        | 15        | 18     | 0.67%   |
| KIOXIA                    | 14        | 17     | 0.63%   |
| China                     | 14        | 29     | 0.63%   |
| LITEON                    | 12        | 13     | 0.54%   |
| XPG                       | 10        | 13     | 0.45%   |
| Transcend                 | 10        | 14     | 0.45%   |
| Patriot                   | 10        | 17     | 0.45%   |
| Gigabyte Technology       | 10        | 13     | 0.45%   |
| Silicon Motion            | 9         | 10     | 0.4%    |
| Phison Electronics        | 8         | 8      | 0.36%   |
| LITEONIT                  | 8         | 8      | 0.36%   |
| OCZ                       | 7         | 8      | 0.31%   |
| Plextor                   | 6         | 6      | 0.27%   |
| Mushkin                   | 6         | 9      | 0.27%   |
| Micron/Crucial Technology | 6         | 6      | 0.27%   |
| Intenso                   | 6         | 7      | 0.27%   |
| Hewlett-Packard           | 6         | 7      | 0.27%   |
| ASMT                      | 6         | 6      | 0.27%   |
| SABRENT                   | 5         | 6      | 0.22%   |
| KingSpec                  | 5         | 5      | 0.22%   |
| Team                      | 4         | 4      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 43        | 1.68%   |
| Seagate ST1000LM035-1RK172 1TB                      | 31        | 1.21%   |
| Kingston SA400S37240G 240GB SSD                     | 29        | 1.13%   |
| Samsung SSD 970 EVO Plus 500GB                      | 23        | 0.9%    |
| Samsung SSD 970 EVO Plus 1TB                        | 23        | 0.9%    |
| Samsung SSD 850 EVO 500GB                           | 23        | 0.9%    |
| Samsung SSD 850 EVO 250GB                           | 23        | 0.9%    |
| Seagate ST1000DM010-2EP102 1TB                      | 20        | 0.78%   |
| Samsung SSD 860 EVO 1TB                             | 20        | 0.78%   |
| Samsung SSD 860 EVO 250GB                           | 18        | 0.7%    |
| WDC WD10EZEX-08WN4A0 1TB                            | 17        | 0.66%   |
| Toshiba MQ01ABD100 1TB                              | 17        | 0.66%   |
| Seagate ST2000DM008-2FR102 2TB                      | 17        | 0.66%   |
| Crucial CT1000MX500SSD1 1TB                         | 17        | 0.66%   |
| Kingston SA400S37120G 120GB SSD                     | 16        | 0.62%   |
| Toshiba MQ04ABF100 1TB                              | 15        | 0.59%   |
| Samsung SSD 970 EVO 1TB                             | 15        | 0.59%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 14        | 0.55%   |
| Crucial CT500MX500SSD1 500GB                        | 14        | 0.55%   |
| Seagate ST2000DM001-1ER164 2TB                      | 13        | 0.51%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 12        | 0.47%   |
| Unknown SD/MMC/MS PRO 2GB                           | 11        | 0.43%   |
| Seagate Expansion 1TB                               | 11        | 0.43%   |
| Samsung SSD 840 EVO 250GB                           | 11        | 0.43%   |
| Kingston SA400S37480G 480GB SSD                     | 11        | 0.43%   |
| Crucial CT1000P1SSD8 1TB                            | 11        | 0.43%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 10        | 0.39%   |
| Toshiba KXG60ZNV1T02 1TB                            | 10        | 0.39%   |
| Toshiba HDWD110 1TB                                 | 10        | 0.39%   |
| JMicron Generic 120GB                               | 10        | 0.39%   |
| Seagate ST1000LM048-2E7172 1TB                      | 9         | 0.35%   |
| Seagate ST1000DM003-1ER162 1TB                      | 9         | 0.35%   |
| HGST HTS721010A9E630 1TB                            | 9         | 0.35%   |
| Toshiba DT01ACA100 1TB                              | 8         | 0.31%   |
| Seagate ST4000DM004-2CV104 4TB                      | 8         | 0.31%   |
| Seagate ST1000LM049-2GH172 1TB                      | 8         | 0.31%   |
| Samsung SSD 980 PRO 1TB                             | 8         | 0.31%   |
| Samsung SSD 870 EVO 1TB                             | 8         | 0.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 8         | 0.31%   |
| Intel SSDPEKNW010T8 1TB                             | 8         | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 295       | 433    | 36.69%  |
| WDC                 | 248       | 397    | 30.85%  |
| Toshiba             | 107       | 136    | 13.31%  |
| Hitachi             | 45        | 52     | 5.6%    |
| HGST                | 34        | 44     | 4.23%   |
| Samsung Electronics | 31        | 39     | 3.86%   |
| Unknown             | 12        | 15     | 1.49%   |
| Apple               | 8         | 10     | 1%      |
| ASMT                | 4         | 4      | 0.5%    |
| Maxtor              | 3         | 5      | 0.37%   |
| Hewlett-Packard     | 2         | 3      | 0.25%   |
| Fantom              | 2         | 4      | 0.25%   |
| WD MediaMax         | 1         | 1      | 0.12%   |
| USB3.0              | 1         | 1      | 0.12%   |
| RSH-319             | 1         | 1      | 0.12%   |
| KESU                | 1         | 1      | 0.12%   |
| JMicron Technology  | 1         | 3      | 0.12%   |
| Intenso             | 1         | 1      | 0.12%   |
| Inateck             | 1         | 1      | 0.12%   |
| HPE                 | 1         | 1      | 0.12%   |
| HGST HUS            | 1         | 1      | 0.12%   |
| HGST HTS            | 1         | 1      | 0.12%   |
| Fujitsu             | 1         | 1      | 0.12%   |
| ExcelStor           | 1         | 2      | 0.12%   |
| Unknown             | 1         | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 249       | 378    | 29.19%  |
| Kingston            | 93        | 110    | 10.9%   |
| SanDisk             | 82        | 93     | 9.61%   |
| Crucial             | 78        | 107    | 9.14%   |
| WDC                 | 72        | 90     | 8.44%   |
| A-DATA Technology   | 22        | 29     | 2.58%   |
| PNY                 | 19        | 27     | 2.23%   |
| SK hynix            | 17        | 23     | 1.99%   |
| Intel               | 17        | 21     | 1.99%   |
| Apple               | 15        | 17     | 1.76%   |
| Micron Technology   | 14        | 15     | 1.64%   |
| China               | 14        | 29     | 1.64%   |
| Toshiba             | 13        | 20     | 1.52%   |
| SPCC                | 13        | 15     | 1.52%   |
| Patriot             | 10        | 17     | 1.17%   |
| Transcend           | 9         | 13     | 1.06%   |
| LITEON              | 9         | 10     | 1.06%   |
| LITEONIT            | 8         | 8      | 0.94%   |
| OCZ                 | 7         | 8      | 0.82%   |
| Corsair             | 6         | 6      | 0.7%    |
| KingSpec            | 5         | 5      | 0.59%   |
| Intenso             | 5         | 6      | 0.59%   |
| Team                | 4         | 4      | 0.47%   |
| Plextor             | 4         | 4      | 0.47%   |
| Mushkin             | 4         | 7      | 0.47%   |
| GOODRAM             | 4         | 6      | 0.47%   |
| Gigabyte Technology | 4         | 4      | 0.47%   |
| Unknown             | 3         | 3      | 0.35%   |
| TO Exter            | 3         | 3      | 0.35%   |
| Seagate             | 3         | 5      | 0.35%   |
| Lexar               | 3         | 3      | 0.35%   |
| Vaseky              | 2         | 4      | 0.23%   |
| Leven               | 2         | 2      | 0.23%   |
| KingFast            | 2         | 2      | 0.23%   |
| HS-SSD-C100         | 2         | 3      | 0.23%   |
| Hewlett-Packard     | 2         | 2      | 0.23%   |
| Drevo               | 2         | 2      | 0.23%   |
| ASMT                | 2         | 2      | 0.23%   |
| AMD                 | 2         | 3      | 0.23%   |
| XrayDisk            | 1         | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 702       | 1137   | 35.73%  |
| HDD     | 673       | 1158   | 34.25%  |
| NVMe    | 549       | 821    | 27.94%  |
| MMC     | 23        | 34     | 1.17%   |
| Unknown | 18        | 26     | 0.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1029      | 2159   | 60%     |
| NVMe | 541       | 799    | 31.55%  |
| SAS  | 122       | 184    | 7.11%   |
| MMC  | 23        | 34     | 1.34%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 734       | 1201   | 49.49%  |
| 0.51-1.0   | 500       | 690    | 33.72%  |
| 1.01-2.0   | 151       | 242    | 10.18%  |
| 3.01-4.0   | 44        | 68     | 2.97%   |
| 2.01-3.0   | 28        | 47     | 1.89%   |
| 4.01-10.0  | 23        | 40     | 1.55%   |
| 10.01-20.0 | 3         | 7      | 0.2%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 317       | 22.79%  |
| 251-500        | 282       | 20.27%  |
| 501-1000       | 223       | 16.03%  |
| 1001-2000      | 174       | 12.51%  |
| More than 3000 | 134       | 9.63%   |
| Unknown        | 66        | 4.74%   |
| 1-20           | 63        | 4.53%   |
| 2001-3000      | 59        | 4.24%   |
| 51-100         | 53        | 3.81%   |
| 21-50          | 20        | 1.44%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 376       | 26.04%  |
| 21-50          | 280       | 19.39%  |
| 101-250        | 209       | 14.47%  |
| 51-100         | 158       | 10.94%  |
| 251-500        | 124       | 8.59%   |
| 501-1000       | 106       | 7.34%   |
| Unknown        | 66        | 4.57%   |
| 1001-2000      | 61        | 4.22%   |
| More than 3000 | 36        | 2.49%   |
| 2001-3000      | 27        | 1.87%   |
| 0              | 1         | 0.07%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST1000LM024 HN-M101MBB 1TB  | 7         | 7      | 2.56%   |
| Toshiba MQ01ABD100 1TB              | 5         | 5      | 1.83%   |
| Seagate ST31000528AS 1TB            | 5         | 5      | 1.83%   |
| Seagate ST1000LM035-1RK172 1TB      | 5         | 5      | 1.83%   |
| Seagate ST9320325AS 320GB           | 4         | 5      | 1.47%   |
| Seagate ST500LM021-1KJ152 500GB     | 3         | 3      | 1.1%    |
| Seagate ST2000DM001-1ER164 2TB      | 3         | 4      | 1.1%    |
| Seagate ST1000LM014-1EJ164 1TB      | 3         | 3      | 1.1%    |
| Seagate ST1000DM003-9YN162 1TB      | 3         | 3      | 1.1%    |
| WDC WDS500G1X0E-00AFY0 500GB        | 2         | 2      | 0.73%   |
| WDC WD5000AAKX-603CA0 500GB         | 2         | 6      | 0.73%   |
| WDC WD5000AAKX-00ERMA0 500GB        | 2         | 2      | 0.73%   |
| WDC WD5000AAKX-001CA0 500GB         | 2         | 3      | 0.73%   |
| WDC WD40EFRX-68N32N0 4TB            | 2         | 6      | 0.73%   |
| WDC WD3200AAJS-00L7A0 320GB         | 2         | 2      | 0.73%   |
| WDC WD20EFRX-68EUZN0 2TB            | 2         | 2      | 0.73%   |
| WDC WD20EARX-00PASB0 2TB            | 2         | 2      | 0.73%   |
| WDC WD10EARS-00Y5B1 1TB             | 2         | 3      | 0.73%   |
| WDC WD1003FZEX-00K3CA0 1TB          | 2         | 2      | 0.73%   |
| Toshiba MQ01ABF050 500GB            | 2         | 2      | 0.73%   |
| Seagate ST9500325AS 500GB           | 2         | 2      | 0.73%   |
| Seagate ST9320423AS 320GB           | 2         | 2      | 0.73%   |
| Seagate ST9250315AS 250GB           | 2         | 2      | 0.73%   |
| Seagate ST500LT012-1DG142 500GB     | 2         | 2      | 0.73%   |
| Seagate ST3500413AS 500GB           | 2         | 2      | 0.73%   |
| Seagate ST3500312CS 500GB           | 2         | 4      | 0.73%   |
| Seagate ST31000524AS 1TB            | 2         | 2      | 0.73%   |
| Seagate ST3000DM001-1ER166 3TB      | 2         | 3      | 0.73%   |
| Seagate ST1000LX015-1U7172 1TB      | 2         | 2      | 0.73%   |
| Seagate ST1000LM049-2GH172 1TB      | 2         | 2      | 0.73%   |
| Seagate ST1000DM010-2EP102 1TB      | 2         | 2      | 0.73%   |
| SanDisk SSD PLUS 1000GB             | 2         | 2      | 0.73%   |
| Samsung Electronics SSD 870 EVO 1TB | 2         | 2      | 0.73%   |
| Maxtor STM3250310AS 250GB           | 2         | 3      | 0.73%   |
| Hitachi HTS547575A9E384 752GB       | 2         | 2      | 0.73%   |
| Hitachi HDS723020BLA642 2TB         | 2         | 2      | 0.73%   |
| Hitachi HDS721010CLA332 1TB         | 2         | 3      | 0.73%   |
| HGST HTS725050A7E630 500GB          | 2         | 2      | 0.73%   |
| HGST HTS545050A7E680 500GB          | 2         | 2      | 0.73%   |
| HGST HTS545050A7E380 500GB          | 2         | 3      | 0.73%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 73        | 87     | 28.19%  |
| WDC                 | 67        | 101    | 25.87%  |
| Toshiba             | 19        | 21     | 7.34%   |
| Samsung Electronics | 18        | 19     | 6.95%   |
| HGST                | 12        | 14     | 4.63%   |
| Hitachi             | 11        | 13     | 4.25%   |
| Intel               | 7         | 8      | 2.7%    |
| Kingston            | 6         | 8      | 2.32%   |
| SanDisk             | 5         | 5      | 1.93%   |
| SK hynix            | 4         | 4      | 1.54%   |
| Corsair             | 4         | 4      | 1.54%   |
| Transcend           | 3         | 3      | 1.16%   |
| Micron Technology   | 3         | 3      | 1.16%   |
| Maxtor              | 3         | 5      | 1.16%   |
| LITEONIT            | 2         | 2      | 0.77%   |
| Drevo               | 2         | 2      | 0.77%   |
| Crucial             | 2         | 2      | 0.77%   |
| Apple               | 2         | 2      | 0.77%   |
| A-DATA Technology   | 2         | 2      | 0.77%   |
| XPG                 | 1         | 1      | 0.39%   |
| USB3.0              | 1         | 1      | 0.39%   |
| SSSTC               | 1         | 1      | 0.39%   |
| SPCC                | 1         | 1      | 0.39%   |
| Plextor             | 1         | 1      | 0.39%   |
| Patriot             | 1         | 1      | 0.39%   |
| Mushkin             | 1         | 1      | 0.39%   |
| Lenovo              | 1         | 1      | 0.39%   |
| Inateck             | 1         | 1      | 0.39%   |
| HGST HTS            | 1         | 1      | 0.39%   |
| Hewlett-Packard     | 1         | 1      | 0.39%   |
| China               | 1         | 2      | 0.39%   |
| ASMedia             | 1         | 2      | 0.39%   |
| Unknown             | 1         | 1      | 0.39%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 73        | 87     | 37.44%  |
| WDC                 | 67        | 99     | 34.36%  |
| Toshiba             | 18        | 20     | 9.23%   |
| HGST                | 12        | 14     | 6.15%   |
| Hitachi             | 11        | 13     | 5.64%   |
| Samsung Electronics | 5         | 5      | 2.56%   |
| Maxtor              | 3         | 5      | 1.54%   |
| Apple               | 2         | 2      | 1.03%   |
| USB3.0              | 1         | 1      | 0.51%   |
| Inateck             | 1         | 1      | 0.51%   |
| HGST HTS            | 1         | 1      | 0.51%   |
| Unknown             | 1         | 1      | 0.51%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 182       | 249    | 73.98%  |
| SSD  | 52        | 59     | 21.14%  |
| NVMe | 12        | 13     | 4.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-21Z10T0 1TB                         | 1         | 1      | 14.29%  |
| Seagate ST9320325AS 320GB                        | 1         | 1      | 14.29%  |
| Seagate ST32000641AS 2TB                         | 1         | 2      | 14.29%  |
| Seagate ST2000DL001-9VT156 2TB                   | 1         | 1      | 14.29%  |
| Samsung Electronics MZ7TY128HDHP-000L1 128GB SSD | 1         | 1      | 14.29%  |
| HGST HTS721010A9E630 1TB                         | 1         | 1      | 14.29%  |
| HGST HTS545050A7E680 500GB                       | 1         | 1      | 14.29%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3         | 4      | 42.86%  |
| HGST                | 2         | 2      | 28.57%  |
| WDC                 | 1         | 1      | 14.29%  |
| Samsung Electronics | 1         | 1      | 14.29%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1061      | 2353   | 67.11%  |
| Detected | 273       | 494    | 17.27%  |
| Malfunc  | 240       | 321    | 15.18%  |
| Failed   | 7         | 8      | 0.44%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 845       | 45.8%   |
| AMD                            | 337       | 18.27%  |
| Samsung Electronics            | 213       | 11.54%  |
| SanDisk                        | 89        | 4.82%   |
| Phison Electronics             | 56        | 3.04%   |
| SK hynix                       | 40        | 2.17%   |
| ASMedia Technology             | 36        | 1.95%   |
| Kingston Technology Company    | 28        | 1.52%   |
| Micron/Crucial Technology      | 25        | 1.36%   |
| Toshiba America Info Systems   | 23        | 1.25%   |
| Marvell Technology Group       | 23        | 1.25%   |
| ADATA Technology               | 20        | 1.08%   |
| KIOXIA                         | 19        | 1.03%   |
| Silicon Motion                 | 16        | 0.87%   |
| Nvidia                         | 14        | 0.76%   |
| Micron Technology              | 11        | 0.6%    |
| Realtek Semiconductor          | 10        | 0.54%   |
| Seagate Technology             | 7         | 0.38%   |
| JMicron Technology             | 6         | 0.33%   |
| Lite-On Technology             | 5         | 0.27%   |
| Union Memory (Shenzhen)        | 3         | 0.16%   |
| Lenovo                         | 3         | 0.16%   |
| Apple                          | 3         | 0.16%   |
| VIA Technologies               | 2         | 0.11%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.11%   |
| LSI Logic / Symbios Logic      | 2         | 0.11%   |
| Broadcom / LSI                 | 2         | 0.11%   |
| Unknown                        | 1         | 0.05%   |
| Solid State Storage Technology | 1         | 0.05%   |
| Silicon Image                  | 1         | 0.05%   |
| Shenzhen Longsys Electronics   | 1         | 0.05%   |
| Adaptec                        | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 248       | 12.03%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 126       | 6.11%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 88        | 4.27%   |
| AMD 400 Series Chipset SATA Controller                                         | 76        | 3.69%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 63        | 3.06%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 56        | 2.72%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 51        | 2.47%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 44        | 2.13%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 44        | 2.13%   |
| AMD 500 Series Chipset SATA Controller                                         | 44        | 2.13%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 40        | 1.94%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 38        | 1.84%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 35        | 1.7%    |
| Phison E12 NVMe Controller                                                     | 33        | 1.6%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 32        | 1.55%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 31        | 1.5%    |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 30        | 1.45%   |
| Samsung NVMe SSD Controller 980                                                | 26        | 1.26%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 25        | 1.21%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 25        | 1.21%   |
| Intel SSD 660P Series                                                          | 24        | 1.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 23        | 1.12%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 22        | 1.07%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 21        | 1.02%   |
| Phison E16 PCIe4 NVMe Controller                                               | 20        | 0.97%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 20        | 0.97%   |
| Intel SATA Controller [RAID mode]                                              | 20        | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 20        | 0.97%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 19        | 0.92%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 18        | 0.87%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 18        | 0.87%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 17        | 0.82%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 17        | 0.82%   |
| SK hynix Gold P31 SSD                                                          | 16        | 0.78%   |
| Intel Comet Lake SATA AHCI Controller                                          | 15        | 0.73%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 14        | 0.68%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 13        | 0.63%   |
| Kingston Company A2000 NVMe SSD                                                | 13        | 0.63%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 12        | 0.58%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 12        | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1055      | 59.47%  |
| NVMe | 542       | 30.55%  |
| RAID | 87        | 4.9%    |
| IDE  | 86        | 4.85%   |
| SAS  | 2         | 0.11%   |
| SCSI | 2         | 0.11%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 927       | 70.44%  |
| AMD     | 388       | 29.48%  |
| Unknown | 1         | 0.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 25        | 1.9%    |
| Intel Core i5-8250U CPU @ 1.60GHz             | 23        | 1.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 19        | 1.44%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 19        | 1.44%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 18        | 1.37%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 18        | 1.37%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 17        | 1.29%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 16        | 1.21%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 15        | 1.14%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 14        | 1.06%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 14        | 1.06%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 13        | 0.99%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 12        | 0.91%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 12        | 0.91%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 11        | 0.83%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 11        | 0.83%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 11        | 0.83%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 11        | 0.83%   |
| Intel Core i7-7700K CPU @ 4.20GHz             | 10        | 0.76%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 10        | 0.76%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 10        | 0.76%   |
| Intel Atom CPU C3758 @ 2.20GHz                | 10        | 0.76%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 10        | 0.76%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 10        | 0.76%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 10        | 0.76%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 10        | 0.76%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 9         | 0.68%   |
| Intel Core i5-8400 CPU @ 2.80GHz              | 9         | 0.68%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 9         | 0.68%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 0.68%   |
| Intel Core i7-7700 CPU @ 3.60GHz              | 8         | 0.61%   |
| Intel Core i7-6700K CPU @ 4.00GHz             | 8         | 0.61%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 8         | 0.61%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 8         | 0.61%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 8         | 0.61%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 8         | 0.61%   |
| AMD Ryzen 5 3600X 6-Core Processor            | 8         | 0.61%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 0.61%   |
| AMD Ryzen 5 2500U with Radeon Vega Mobile Gfx | 8         | 0.61%   |
| Intel Core i7-8700 CPU @ 3.20GHz              | 7         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 329       | 24.96%  |
| Intel Core i7           | 323       | 24.51%  |
| AMD Ryzen 5             | 122       | 9.26%   |
| AMD Ryzen 7             | 106       | 8.04%   |
| Intel Core i3           | 65        | 4.93%   |
| AMD Ryzen 9             | 42        | 3.19%   |
| Other                   | 40        | 3.03%   |
| Intel Pentium           | 33        | 2.5%    |
| Intel Xeon              | 31        | 2.35%   |
| Intel Celeron           | 29        | 2.2%    |
| AMD Ryzen 3             | 29        | 2.2%    |
| Intel Core 2 Duo        | 24        | 1.82%   |
| Intel Atom              | 19        | 1.44%   |
| AMD FX                  | 13        | 0.99%   |
| Intel Core i9           | 11        | 0.83%   |
| AMD A6                  | 11        | 0.83%   |
| AMD A10                 | 10        | 0.76%   |
| AMD Ryzen 7 PRO         | 8         | 0.61%   |
| Intel Pentium Dual-Core | 7         | 0.53%   |
| AMD A8                  | 7         | 0.53%   |
| AMD A4                  | 7         | 0.53%   |
| AMD Ryzen Threadripper  | 5         | 0.38%   |
| AMD Phenom II X4        | 5         | 0.38%   |
| AMD A12                 | 5         | 0.38%   |
| Intel Xeon Silver       | 3         | 0.23%   |
| Intel Pentium Silver    | 3         | 0.23%   |
| Intel Pentium Dual      | 3         | 0.23%   |
| Intel Core m3           | 3         | 0.23%   |
| AMD Athlon 64 X2        | 3         | 0.23%   |
| Intel Core 2 Quad       | 2         | 0.15%   |
| Intel Core 2            | 2         | 0.15%   |
| AMD Ryzen 5 PRO         | 2         | 0.15%   |
| AMD Phenom II X6        | 2         | 0.15%   |
| AMD E2                  | 2         | 0.15%   |
| AMD Athlon II X2        | 2         | 0.15%   |
| Intel Pentium Gold      | 1         | 0.08%   |
| Intel Pentium 4         | 1         | 0.08%   |
| Intel Genuine           | 1         | 0.08%   |
| Intel Core m7           | 1         | 0.08%   |
| Intel Core M            | 1         | 0.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 488       | 37%     |
| 2       | 412       | 31.24%  |
| 6       | 200       | 15.16%  |
| 8       | 147       | 11.14%  |
| 12      | 32        | 2.43%   |
| 16      | 15        | 1.14%   |
| 1       | 10        | 0.76%   |
| 3       | 8         | 0.61%   |
| 10      | 3         | 0.23%   |
| 32      | 1         | 0.08%   |
| 24      | 1         | 0.08%   |
| 14      | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1313      | 99.7%   |
| 2       | 3         | 0.23%   |
| Unknown | 1         | 0.08%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1016      | 77.15%  |
| 1       | 300       | 22.78%  |
| Unknown | 1         | 0.08%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1309      | 99.47%  |
| Unknown        | 7         | 0.53%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 154       | 11.5%   |
| 0x906ea    | 74        | 5.53%   |
| 0x306c3    | 73        | 5.45%   |
| 0x206a7    | 69        | 5.15%   |
| 0x306a9    | 68        | 5.08%   |
| 0x08701021 | 56        | 4.18%   |
| 0x906e9    | 54        | 4.03%   |
| 0x806ea    | 43        | 3.21%   |
| 0x506e3    | 40        | 2.99%   |
| 0x806e9    | 39        | 2.91%   |
| 0x406e3    | 36        | 2.69%   |
| 0x0800820d | 32        | 2.39%   |
| 0x806ec    | 26        | 1.94%   |
| 0x40651    | 26        | 1.94%   |
| 0x0a201016 | 25        | 1.87%   |
| 0x306d4    | 22        | 1.64%   |
| 0x806c1    | 21        | 1.57%   |
| 0x20655    | 21        | 1.57%   |
| 0x1067a    | 21        | 1.57%   |
| 0x0a201009 | 21        | 1.57%   |
| 0x08108109 | 21        | 1.57%   |
| 0x08600106 | 20        | 1.49%   |
| 0x08108102 | 18        | 1.34%   |
| 0xa0652    | 16        | 1.19%   |
| 0x0a50000c | 14        | 1.05%   |
| 0x706e5    | 13        | 0.97%   |
| 0x08701013 | 13        | 0.97%   |
| 0x106e5    | 12        | 0.9%    |
| 0x506f1    | 10        | 0.75%   |
| 0x30678    | 10        | 0.75%   |
| 0x08600104 | 10        | 0.75%   |
| 0x08101016 | 10        | 0.75%   |
| 0x0810100b | 10        | 0.75%   |
| 0x906ec    | 9         | 0.67%   |
| 0x806eb    | 9         | 0.67%   |
| 0x08600103 | 9         | 0.67%   |
| 0xa0653    | 8         | 0.6%    |
| 0x906ed    | 8         | 0.6%    |
| 0x706a8    | 7         | 0.52%   |
| 0x506c9    | 7         | 0.52%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 297       | 22.52%  |
| Haswell          | 120       | 9.1%    |
| Zen 2            | 115       | 8.72%   |
| Skylake          | 88        | 6.67%   |
| IvyBridge        | 86        | 6.52%   |
| SandyBridge      | 81        | 6.14%   |
| Zen+             | 78        | 5.91%   |
| Zen 3            | 76        | 5.76%   |
| Zen              | 37        | 2.81%   |
| Westmere         | 37        | 2.81%   |
| Penryn           | 31        | 2.35%   |
| CometLake        | 30        | 2.27%   |
| Broadwell        | 26        | 1.97%   |
| Excavator        | 24        | 1.82%   |
| TigerLake        | 23        | 1.74%   |
| Silvermont       | 23        | 1.74%   |
| IceLake          | 23        | 1.74%   |
| Piledriver       | 19        | 1.44%   |
| Goldmont         | 18        | 1.36%   |
| Nehalem          | 16        | 1.21%   |
| K10              | 13        | 0.99%   |
| Goldmont plus    | 11        | 0.83%   |
| Unknown          | 10        | 0.76%   |
| Core             | 9         | 0.68%   |
| Steamroller      | 7         | 0.53%   |
| K8 Hammer        | 4         | 0.3%    |
| Puma             | 3         | 0.23%   |
| Jaguar           | 3         | 0.23%   |
| Bonnell          | 3         | 0.23%   |
| Alderlake Hybrid | 3         | 0.23%   |
| Bulldozer        | 2         | 0.15%   |
| Tremont          | 1         | 0.08%   |
| NetBurst         | 1         | 0.08%   |
| K10 Llano        | 1         | 0.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 691       | 43.11%  |
| Nvidia                     | 538       | 33.56%  |
| AMD                        | 358       | 22.33%  |
| ASPEED Technology          | 14        | 0.87%   |
| Matrox Electronics Systems | 1         | 0.06%   |
| ATI Technologies           | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 59        | 3.6%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 50        | 3.05%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 47        | 2.87%   |
| Intel UHD Graphics 620                                                                   | 42        | 2.57%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 42        | 2.57%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 40        | 2.44%   |
| Intel HD Graphics 630                                                                    | 39        | 2.38%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 38        | 2.32%   |
| Intel HD Graphics 620                                                                    | 37        | 2.26%   |
| AMD Renoir                                                                               | 36        | 2.2%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 30        | 1.83%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 28        | 1.71%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 24        | 1.47%   |
| Intel Core Processor Integrated Graphics Controller                                      | 24        | 1.47%   |
| Intel HD Graphics 530                                                                    | 22        | 1.34%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 21        | 1.28%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 21        | 1.28%   |
| AMD Cezanne                                                                              | 21        | 1.28%   |
| Intel HD Graphics 5500                                                                   | 20        | 1.22%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 19        | 1.16%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 19        | 1.16%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 19        | 1.16%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 18        | 1.1%    |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 17        | 1.04%   |
| Nvidia GP104 [GeForce GTX 1080]                                                          | 15        | 0.92%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                                       | 15        | 0.92%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 15        | 0.92%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                                           | 15        | 0.92%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 14        | 0.86%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 14        | 0.86%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 14        | 0.86%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 14        | 0.86%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 13        | 0.79%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 12        | 0.73%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 12        | 0.73%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 12        | 0.73%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 12        | 0.73%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 11        | 0.67%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 11        | 0.67%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 430       | 32.4%   |
| 1 x Nvidia     | 312       | 23.51%  |
| 1 x AMD        | 287       | 21.63%  |
| Intel + Nvidia | 204       | 15.37%  |
| Intel + AMD    | 32        | 2.41%   |
| AMD + Nvidia   | 22        | 1.66%   |
| 2 x AMD        | 19        | 1.43%   |
| 1 x ASPEED     | 14        | 1.06%   |
| Other          | 3         | 0.23%   |
| 2 x Nvidia     | 2         | 0.15%   |
| 2 x Intel      | 1         | 0.08%   |
| 1 x Matrox     | 1         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 947       | 71.15%  |
| Proprietary | 343       | 25.77%  |
| Unknown     | 41        | 3.08%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 703       | 52.15%  |
| 1.01-2.0   | 138       | 10.24%  |
| 7.01-8.0   | 111       | 8.23%   |
| 3.01-4.0   | 109       | 8.09%   |
| 0.01-0.5   | 106       | 7.86%   |
| 0.51-1.0   | 69        | 5.12%   |
| 5.01-6.0   | 53        | 3.93%   |
| 8.01-16.0  | 45        | 3.34%   |
| 2.01-3.0   | 13        | 0.96%   |
| 16.01-24.0 | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 166       | 10.79%  |
| LG Display              | 150       | 9.75%   |
| AU Optronics            | 148       | 9.62%   |
| Chimei Innolux          | 122       | 7.93%   |
| BOE                     | 117       | 7.61%   |
| Dell                    | 115       | 7.48%   |
| Goldstar                | 113       | 7.35%   |
| Acer                    | 58        | 3.77%   |
| AOC                     | 50        | 3.25%   |
| BenQ                    | 49        | 3.19%   |
| Ancor Communications    | 46        | 2.99%   |
| Hewlett-Packard         | 41        | 2.67%   |
| Sharp                   | 32        | 2.08%   |
| Apple                   | 30        | 1.95%   |
| Lenovo                  | 25        | 1.63%   |
| Philips                 | 24        | 1.56%   |
| ViewSonic               | 19        | 1.24%   |
| ASUSTek Computer        | 19        | 1.24%   |
| Sony                    | 15        | 0.98%   |
| PANDA                   | 13        | 0.85%   |
| Iiyama                  | 12        | 0.78%   |
| MSI                     | 11        | 0.72%   |
| Panasonic               | 10        | 0.65%   |
| Eizo                    | 10        | 0.65%   |
| Unknown                 | 9         | 0.59%   |
| Chi Mei Optoelectronics | 9         | 0.59%   |
| Vizio                   | 8         | 0.52%   |
| Sceptre Tech            | 7         | 0.46%   |
| InfoVision              | 7         | 0.46%   |
| CSO                     | 7         | 0.46%   |
| Toshiba                 | 5         | 0.33%   |
| Gigabyte Technology     | 5         | 0.33%   |
| Vestel Elektronik       | 4         | 0.26%   |
| HannStar                | 4         | 0.26%   |
| VIE                     | 3         | 0.2%    |
| MStar                   | 3         | 0.2%    |
| Compal                  | 3         | 0.2%    |
| VIZ                     | 2         | 0.13%   |
| UTV                     | 2         | 0.13%   |
| ONN                     | 2         | 0.13%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 10        | 0.63%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 10        | 0.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 10        | 0.63%   |
| Dell SE2416H DELD081 1920x1080 527x296mm 23.8-inch                    | 9         | 0.57%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 9         | 0.57%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 7         | 0.44%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 7         | 0.44%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 7         | 0.44%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 6         | 0.38%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 6         | 0.38%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 6         | 0.38%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 353x198mm 15.9-inch  | 5         | 0.31%   |
| Panasonic TDM13O56 MEI96A2 3000x2000 285x190mm 13.5-inch              | 5         | 0.31%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 5         | 0.31%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 5         | 0.31%   |
| Goldstar HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch                 | 5         | 0.31%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 5         | 0.31%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 5         | 0.31%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 5         | 0.31%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                  | 5         | 0.31%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch         | 5         | 0.31%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 5         | 0.31%   |
| Acer V173 ACR0053 1280x1024 338x270mm 17.0-inch                       | 5         | 0.31%   |
| Vestel Elektronik 24W_LCD_TV VES3700 1920x1080 706x398mm 31.9-inch    | 4         | 0.25%   |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 4         | 0.25%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 4         | 0.25%   |
| Samsung Electronics S22E310 SAM0C2D 1920x1080 477x268mm 21.5-inch     | 4         | 0.25%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 890x500mm 40.2-inch | 4         | 0.25%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 600x340mm 27.2-inch     | 4         | 0.25%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                    | 4         | 0.25%   |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch          | 4         | 0.25%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                   | 4         | 0.25%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 4         | 0.25%   |
| Chimei Innolux LCD Monitor CMN1738 1920x1080 381x214mm 17.2-inch      | 4         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 4         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 4         | 0.25%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch       | 4         | 0.25%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 4         | 0.25%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                  | 4         | 0.25%   |
| BenQ GW2780 BNQ78E6 1920x1080 598x336mm 27.0-inch                     | 4         | 0.25%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 710       | 49.37%  |
| 1366x768 (WXGA)    | 205       | 14.26%  |
| 2560x1440 (QHD)    | 116       | 8.07%   |
| 3840x2160 (4K)     | 107       | 7.44%   |
| 1600x900 (HD+)     | 49        | 3.41%   |
| 2560x1080          | 27        | 1.88%   |
| 1680x1050 (WSXGA+) | 27        | 1.88%   |
| 1920x1200 (WUXGA)  | 26        | 1.81%   |
| 1280x1024 (SXGA)   | 26        | 1.81%   |
| 1440x900 (WXGA+)   | 23        | 1.6%    |
| 1280x800 (WXGA)    | 22        | 1.53%   |
| 3440x1440          | 19        | 1.32%   |
| 1360x768           | 11        | 0.76%   |
| 2880x1800          | 10        | 0.7%    |
| 3840x1080          | 8         | 0.56%   |
| 2560x1600          | 8         | 0.56%   |
| 1920x540           | 8         | 0.56%   |
| 2160x1440          | 6         | 0.42%   |
| 3200x1800 (QHD+)   | 5         | 0.35%   |
| Unknown            | 5         | 0.35%   |
| 3840x2400          | 3         | 0.21%   |
| 3840x1600          | 3         | 0.21%   |
| 2160x1350          | 2         | 0.14%   |
| 1600x1200          | 2         | 0.14%   |
| 1024x600           | 2         | 0.14%   |
| 5760x2160          | 1         | 0.07%   |
| 3840x1200          | 1         | 0.07%   |
| 3240x2160          | 1         | 0.07%   |
| 3000x2000          | 1         | 0.07%   |
| 2288x1287          | 1         | 0.07%   |
| 2048x1152          | 1         | 0.07%   |
| 1400x1050          | 1         | 0.07%   |
| 1024x768 (XGA)     | 1         | 0.07%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 356       | 23.28%  |
| 27      | 168       | 10.99%  |
| 24      | 132       | 8.63%   |
| 13      | 116       | 7.59%   |
| 14      | 110       | 7.19%   |
| 23      | 105       | 6.87%   |
| 21      | 96        | 6.28%   |
| 17      | 85        | 5.56%   |
| 31      | 47        | 3.07%   |
| 34      | 38        | 2.49%   |
| Unknown | 36        | 2.35%   |
| 19      | 29        | 1.9%    |
| 12      | 28        | 1.83%   |
| 18      | 22        | 1.44%   |
| 22      | 20        | 1.31%   |
| 84      | 14        | 0.92%   |
| 20      | 14        | 0.92%   |
| 72      | 12        | 0.78%   |
| 54      | 11        | 0.72%   |
| 25      | 8         | 0.52%   |
| 16      | 8         | 0.52%   |
| 11      | 8         | 0.52%   |
| 32      | 6         | 0.39%   |
| 28      | 6         | 0.39%   |
| 40      | 5         | 0.33%   |
| 26      | 5         | 0.33%   |
| 52      | 4         | 0.26%   |
| 48      | 4         | 0.26%   |
| 39      | 4         | 0.26%   |
| 10      | 4         | 0.26%   |
| 49      | 3         | 0.2%    |
| 46      | 3         | 0.2%    |
| 42      | 3         | 0.2%    |
| 35      | 3         | 0.2%    |
| 65      | 2         | 0.13%   |
| 55      | 2         | 0.13%   |
| 43      | 2         | 0.13%   |
| 37      | 2         | 0.13%   |
| 29      | 2         | 0.13%   |
| 142     | 1         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 528       | 35.53%  |
| 501-600        | 366       | 24.63%  |
| 401-500        | 165       | 11.1%   |
| 201-300        | 109       | 7.34%   |
| 351-400        | 84        | 5.65%   |
| 601-700        | 75        | 5.05%   |
| 701-800        | 46        | 3.1%    |
| Unknown        | 36        | 2.42%   |
| 1001-1500      | 30        | 2.02%   |
| 1501-2000      | 26        | 1.75%   |
| 801-900        | 15        | 1.01%   |
| 901-1000       | 5         | 0.34%   |
| More than 2000 | 1         | 0.07%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1081      | 80.49%  |
| 16/10   | 130       | 9.68%   |
| 21/9    | 50        | 3.72%   |
| Unknown | 26        | 1.94%   |
| 5/4     | 25        | 1.86%   |
| 3/2     | 14        | 1.04%   |
| 4/3     | 9         | 0.67%   |
| 32/9    | 5         | 0.37%   |
| 6/5     | 2         | 0.15%   |
| 1.00    | 1         | 0.07%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 352       | 23.37%  |
| 201-250        | 292       | 19.39%  |
| 301-350        | 170       | 11.29%  |
| 81-90          | 169       | 11.22%  |
| 351-500        | 96        | 6.37%   |
| 121-130        | 65        | 4.32%   |
| 71-80          | 57        | 3.78%   |
| 151-200        | 56        | 3.72%   |
| More than 1000 | 48        | 3.19%   |
| 251-300        | 47        | 3.12%   |
| 141-150        | 39        | 2.59%   |
| Unknown        | 36        | 2.39%   |
| 501-1000       | 25        | 1.66%   |
| 61-70          | 24        | 1.59%   |
| 51-60          | 9         | 0.6%    |
| 91-100         | 8         | 0.53%   |
| 131-140        | 6         | 0.4%    |
| 111-120        | 4         | 0.27%   |
| 41-50          | 3         | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 476       | 32.69%  |
| 121-160       | 416       | 28.57%  |
| 101-120       | 372       | 25.55%  |
| 161-240       | 87        | 5.98%   |
| 1-50          | 39        | 2.68%   |
| Unknown       | 36        | 2.47%   |
| More than 240 | 30        | 2.06%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 981       | 73.15%  |
| 2     | 276       | 20.58%  |
| 0     | 52        | 3.88%   |
| 3     | 30        | 2.24%   |
| 4     | 2         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 730       | 37.86%  |
| Intel                                  | 726       | 37.66%  |
| Qualcomm Atheros                       | 205       | 10.63%  |
| Broadcom                               | 85        | 4.41%   |
| Ralink Technology                      | 21        | 1.09%   |
| Broadcom Limited                       | 17        | 0.88%   |
| TP-Link                                | 15        | 0.78%   |
| Nvidia                                 | 11        | 0.57%   |
| Marvell Technology Group               | 11        | 0.57%   |
| ASIX Electronics                       | 8         | 0.41%   |
| Sierra Wireless                        | 7         | 0.36%   |
| Microsoft                              | 7         | 0.36%   |
| Dell                                   | 7         | 0.36%   |
| MediaTek                               | 6         | 0.31%   |
| Ralink                                 | 5         | 0.26%   |
| NetGear                                | 4         | 0.21%   |
| Lenovo                                 | 4         | 0.21%   |
| Insyde Software                        | 4         | 0.21%   |
| D-Link System                          | 4         | 0.21%   |
| Aquantia                               | 4         | 0.21%   |
| Samsung Electronics                    | 3         | 0.16%   |
| Qualcomm Atheros Communications        | 3         | 0.16%   |
| Ericsson Business Mobile Networks      | 3         | 0.16%   |
| DisplayLink                            | 3         | 0.16%   |
| D-Link                                 | 3         | 0.16%   |
| Qualcomm                               | 2         | 0.1%    |
| Oculus VR                              | 2         | 0.1%    |
| Huawei Technologies                    | 2         | 0.1%    |
| Hewlett-Packard                        | 2         | 0.1%    |
| ASUSTek Computer                       | 2         | 0.1%    |
| Xiaomi                                 | 1         | 0.05%   |
| vivo                                   | 1         | 0.05%   |
| U-Blox                                 | 1         | 0.05%   |
| Tenda                                  | 1         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| Solarflare Communications              | 1         | 0.05%   |
| Seeed Technology                       | 1         | 0.05%   |
| Motorola PCS                           | 1         | 0.05%   |
| Motorola                               | 1         | 0.05%   |
| Microchip Technology                   | 1         | 0.05%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 551       | 23.73%  |
| Intel Wi-Fi 6 AX200                                               | 108       | 4.65%   |
| Intel I211 Gigabit Network Connection                             | 70        | 3.01%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 61        | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 58        | 2.5%    |
| Intel Wireless 8265 / 8275                                        | 50        | 2.15%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 50        | 2.15%   |
| Intel Ethernet Connection (2) I219-V                              | 40        | 1.72%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 40        | 1.72%   |
| Realtek RTL8125 2.5GbE Controller                                 | 37        | 1.59%   |
| Intel Wireless 7260                                               | 36        | 1.55%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 32        | 1.38%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 32        | 1.38%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 30        | 1.29%   |
| Intel Wireless 8260                                               | 30        | 1.29%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 27        | 1.16%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 27        | 1.16%   |
| Intel Wireless-AC 9260                                            | 26        | 1.12%   |
| Intel Ethernet Connection I217-LM                                 | 25        | 1.08%   |
| Intel Wireless 7265                                               | 24        | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 24        | 1.03%   |
| Intel Wireless 3165                                               | 23        | 0.99%   |
| Intel Ethernet Connection (7) I219-V                              | 22        | 0.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 21        | 0.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 18        | 0.78%   |
| Intel Wi-Fi 6 AX201                                               | 18        | 0.78%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 18        | 0.78%   |
| Intel Ethernet Controller I225-V                                  | 17        | 0.73%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 17        | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 15        | 0.65%   |
| Intel Centrino Ultimate-N 6300                                    | 15        | 0.65%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 15        | 0.65%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 13        | 0.56%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 12        | 0.52%   |
| Intel Centrino Advanced-N 6200                                    | 12        | 0.52%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 0.47%   |
| Intel Ethernet Connection I217-V                                  | 11        | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 10        | 0.43%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 10        | 0.43%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 551       | 53.39%  |
| Qualcomm Atheros                  | 162       | 15.7%   |
| Realtek Semiconductor             | 160       | 15.5%   |
| Broadcom                          | 63        | 6.1%    |
| Ralink Technology                 | 21        | 2.03%   |
| TP-Link                           | 14        | 1.36%   |
| Broadcom Limited                  | 12        | 1.16%   |
| Sierra Wireless                   | 7         | 0.68%   |
| Microsoft                         | 7         | 0.68%   |
| MediaTek                          | 6         | 0.58%   |
| Ralink                            | 5         | 0.48%   |
| NetGear                           | 4         | 0.39%   |
| Qualcomm Atheros Communications   | 3         | 0.29%   |
| Dell                              | 3         | 0.29%   |
| D-Link                            | 3         | 0.29%   |
| D-Link System                     | 2         | 0.19%   |
| ASUSTek Computer                  | 2         | 0.19%   |
| Tenda                             | 1         | 0.1%    |
| Marvell Technology Group          | 1         | 0.1%    |
| IMC Networks                      | 1         | 0.1%    |
| FIBOCOM                           | 1         | 0.1%    |
| Ericsson Business Mobile Networks | 1         | 0.1%    |
| Edimax Technology                 | 1         | 0.1%    |
| CyberTAN Technology               | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 108       | 10.39%  |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 58        | 5.58%   |
| Intel Wireless 8265 / 8275                                     | 50        | 4.81%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 40        | 3.85%   |
| Intel Wireless 7260                                            | 36        | 3.46%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 32        | 3.08%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 30        | 2.89%   |
| Intel Wireless 8260                                            | 30        | 2.89%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 27        | 2.6%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 27        | 2.6%    |
| Intel Wireless-AC 9260                                         | 26        | 2.5%    |
| Intel Wireless 7265                                            | 24        | 2.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 24        | 2.31%   |
| Intel Wireless 3165                                            | 23        | 2.21%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 21        | 2.02%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 18        | 1.73%   |
| Intel Wi-Fi 6 AX201                                            | 18        | 1.73%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 18        | 1.73%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 17        | 1.64%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 15        | 1.44%   |
| Intel Centrino Ultimate-N 6300                                 | 15        | 1.44%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 15        | 1.44%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 13        | 1.25%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 12        | 1.15%   |
| Intel Centrino Advanced-N 6200                                 | 12        | 1.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11        | 1.06%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 10        | 0.96%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 10        | 0.96%   |
| Realtek 802.11ac NIC                                           | 10        | 0.96%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 9         | 0.87%   |
| Ralink MT7601U Wireless Adapter                                | 9         | 0.87%   |
| Intel Wireless 3160                                            | 9         | 0.87%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 9         | 0.87%   |
| Intel Centrino Advanced-N 6235                                 | 9         | 0.87%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 8         | 0.77%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 8         | 0.77%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 8         | 0.77%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 8         | 0.77%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 7         | 0.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 7         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 678       | 55.44%  |
| Intel                                  | 380       | 31.07%  |
| Qualcomm Atheros                       | 61        | 4.99%   |
| Broadcom                               | 36        | 2.94%   |
| Nvidia                                 | 11        | 0.9%    |
| Marvell Technology Group               | 10        | 0.82%   |
| ASIX Electronics                       | 8         | 0.65%   |
| Broadcom Limited                       | 5         | 0.41%   |
| Lenovo                                 | 4         | 0.33%   |
| Insyde Software                        | 4         | 0.33%   |
| Aquantia                               | 4         | 0.33%   |
| Samsung Electronics                    | 3         | 0.25%   |
| DisplayLink                            | 3         | 0.25%   |
| Qualcomm                               | 2         | 0.16%   |
| D-Link System                          | 2         | 0.16%   |
| Xiaomi                                 | 1         | 0.08%   |
| TP-Link                                | 1         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.08%   |
| Solarflare Communications              | 1         | 0.08%   |
| Motorola PCS                           | 1         | 0.08%   |
| MediaTek                               | 1         | 0.08%   |
| JMicron Technology                     | 1         | 0.08%   |
| ICS Advent                             | 1         | 0.08%   |
| Google                                 | 1         | 0.08%   |
| Emulex                                 | 1         | 0.08%   |
| Apple                                  | 1         | 0.08%   |
| 3Com                                   | 1         | 0.08%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 551       | 43.59%  |
| Intel I211 Gigabit Network Connection                             | 70        | 5.54%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 61        | 4.83%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 50        | 3.96%   |
| Intel Ethernet Connection (2) I219-V                              | 40        | 3.16%   |
| Realtek RTL8125 2.5GbE Controller                                 | 37        | 2.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 32        | 2.53%   |
| Intel Ethernet Connection I217-LM                                 | 25        | 1.98%   |
| Intel Ethernet Connection (7) I219-V                              | 22        | 1.74%   |
| Intel Ethernet Controller I225-V                                  | 17        | 1.34%   |
| Intel 82577LM Gigabit Network Connection                          | 14        | 1.11%   |
| Intel Ethernet Connection I217-V                                  | 11        | 0.87%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 10        | 0.79%   |
| Intel Ethernet Connection X553 1GbE                               | 10        | 0.79%   |
| Intel Ethernet Connection I219-LM                                 | 10        | 0.79%   |
| Intel Ethernet Connection I218-LM                                 | 10        | 0.79%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 9         | 0.71%   |
| Intel Ethernet Connection (4) I219-V                              | 9         | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                             | 9         | 0.71%   |
| Intel 82579V Gigabit Network Connection                           | 9         | 0.71%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.63%   |
| Intel I210 Gigabit Network Connection                             | 8         | 0.63%   |
| Intel Ethernet Connection (4) I219-LM                             | 8         | 0.63%   |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 0.63%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 8         | 0.63%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7         | 0.55%   |
| Intel Ethernet Connection I219-V                                  | 7         | 0.55%   |
| ASIX AX88179 Gigabit Ethernet                                     | 7         | 0.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 6         | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 6         | 0.47%   |
| Nvidia MCP79 Ethernet                                             | 6         | 0.47%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.47%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 6         | 0.47%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5         | 0.4%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 0.4%    |
| Intel Ethernet Connection (2) I218-V                              | 5         | 0.4%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 5         | 0.4%    |
| Marvell Group 88E8057 PCI-E Gigabit Ethernet Controller           | 4         | 0.32%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 0.32%   |
| Intel Ethernet Connection (5) I219-LM                             | 4         | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1164      | 53.52%  |
| WiFi     | 992       | 45.61%  |
| Modem    | 18        | 0.83%   |
| Unknown  | 1         | 0.05%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 747       | 54.25%  |
| Ethernet | 630       | 45.75%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 742       | 56.21%  |
| 1     | 513       | 38.86%  |
| 3     | 40        | 3.03%   |
| 4     | 18        | 1.36%   |
| 0     | 6         | 0.45%   |
| 9     | 1         | 0.08%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1058      | 79.13%  |
| Yes  | 279       | 20.87%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 456       | 51.06%  |
| Realtek Semiconductor           | 88        | 9.85%   |
| Qualcomm Atheros Communications | 70        | 7.84%   |
| Cambridge Silicon Radio         | 56        | 6.27%   |
| Broadcom                        | 40        | 4.48%   |
| Apple                           | 39        | 4.37%   |
| IMC Networks                    | 34        | 3.81%   |
| Lite-On Technology              | 31        | 3.47%   |
| ASUSTek Computer                | 26        | 2.91%   |
| Foxconn / Hon Hai               | 19        | 2.13%   |
| Dell                            | 9         | 1.01%   |
| Toshiba                         | 3         | 0.34%   |
| Realtek                         | 3         | 0.34%   |
| Edimax Technology               | 3         | 0.34%   |
| Dynex                           | 3         | 0.34%   |
| Belkin Components               | 3         | 0.34%   |
| HTC (High Tech Computer)        | 2         | 0.22%   |
| Hewlett-Packard                 | 2         | 0.22%   |
| SINO WEALTH                     | 1         | 0.11%   |
| Ralink Technology               | 1         | 0.11%   |
| Ralink                          | 1         | 0.11%   |
| MediaTek                        | 1         | 0.11%   |
| Marvell Semiconductor           | 1         | 0.11%   |
| Chicony Electronics             | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 165       | 18.46%  |
| Intel AX200 Bluetooth                                                               | 105       | 11.74%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 68        | 7.61%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 56        | 6.26%   |
| Realtek Bluetooth Radio                                                             | 54        | 6.04%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 50        | 5.59%   |
| Intel AX201 Bluetooth                                                               | 49        | 5.48%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 26        | 2.91%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 25        | 2.8%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 22        | 2.46%   |
| Apple Bluetooth Host Controller                                                     | 18        | 2.01%   |
| Apple Bluetooth USB Host Controller                                                 | 16        | 1.79%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 15        | 1.68%   |
| Lite-On Bluetooth Device                                                            | 14        | 1.57%   |
| IMC Networks Bluetooth Device                                                       | 14        | 1.57%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 13        | 1.45%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 11        | 1.23%   |
| IMC Networks Bluetooth Radio                                                        | 10        | 1.12%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 10        | 1.12%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 9         | 1.01%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 7         | 0.78%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 7         | 0.78%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 6         | 0.67%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 5         | 0.56%   |
| ASUS ASUS USB-BT500                                                                 | 5         | 0.56%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 5         | 0.56%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 4         | 0.45%   |
| Realtek RTL8723B Bluetooth                                                          | 4         | 0.45%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 4         | 0.45%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 4         | 0.45%   |
| Realtek Bluetooth Radio                                                             | 3         | 0.34%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 3         | 0.34%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 0.34%   |
| IMC Networks Bluetooth USB Host Controller                                          | 3         | 0.34%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.34%   |
| Edimax Bluetooth Adapter                                                            | 3         | 0.34%   |
| Dynex BCM20702A0                                                                    | 3         | 0.34%   |
| Dell DW375 Bluetooth Module                                                         | 3         | 0.34%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                               | 3         | 0.34%   |
| Toshiba Bluetooth Device                                                            | 2         | 0.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 892       | 43.39%  |
| AMD                                  | 454       | 22.08%  |
| Nvidia                               | 430       | 20.91%  |
| C-Media Electronics                  | 41        | 1.99%   |
| Logitech                             | 27        | 1.31%   |
| Kingston Technology                  | 16        | 0.78%   |
| Texas Instruments                    | 12        | 0.58%   |
| JMTek                                | 12        | 0.58%   |
| Focusrite-Novation                   | 12        | 0.58%   |
| Creative Technology                  | 10        | 0.49%   |
| Corsair                              | 10        | 0.49%   |
| Realtek Semiconductor                | 9         | 0.44%   |
| Razer USA                            | 8         | 0.39%   |
| SteelSeries ApS                      | 7         | 0.34%   |
| RODE Microphones                     | 6         | 0.29%   |
| Creative Labs                        | 6         | 0.29%   |
| Generalplus Technology               | 5         | 0.24%   |
| Blue Microphones                     | 5         | 0.24%   |
| Thesycon Systemsoftware & Consulting | 4         | 0.19%   |
| Sennheiser Communications            | 4         | 0.19%   |
| SAVITECH                             | 4         | 0.19%   |
| Samson Technologies                  | 4         | 0.19%   |
| GN Netcom                            | 4         | 0.19%   |
| BEHRINGER International              | 4         | 0.19%   |
| Yamaha                               | 3         | 0.15%   |
| VIA Technologies                     | 3         | 0.15%   |
| Sony                                 | 3         | 0.15%   |
| PreSonus Audio Electronics           | 3         | 0.15%   |
| Plantronics                          | 3         | 0.15%   |
| Lenovo                               | 3         | 0.15%   |
| Project                              | 2         | 0.1%    |
| Native Instruments                   | 2         | 0.1%    |
| Mark of the Unicorn                  | 2         | 0.1%    |
| FIFINE Microphones                   | 2         | 0.1%    |
| Dell                                 | 2         | 0.1%    |
| Cambridge Silicon Radio              | 2         | 0.1%    |
| Asahi Kasei Microsystems             | 2         | 0.1%    |
| XMOS                                 | 1         | 0.05%   |
| USB-MIC                              | 1         | 0.05%   |
| Unknown                              | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 141       | 5.84%   |
| Intel Sunrise Point-LP HD Audio                                            | 129       | 5.34%   |
| AMD Starship/Matisse HD Audio Controller                                   | 122       | 5.05%   |
| Intel Cannon Lake PCH cAVS                                                 | 86        | 3.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 86        | 3.56%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 77        | 3.19%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 74        | 3.06%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 57        | 2.36%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 55        | 2.28%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 51        | 2.11%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 49        | 2.03%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 48        | 1.99%   |
| Intel 200 Series PCH HD Audio                                              | 46        | 1.9%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 45        | 1.86%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 43        | 1.78%   |
| Nvidia TU116 High Definition Audio Controller                              | 37        | 1.53%   |
| Nvidia GP106 High Definition Audio Controller                              | 36        | 1.49%   |
| Nvidia GP107GL High Definition Audio Controller                            | 35        | 1.45%   |
| Nvidia GP104 High Definition Audio Controller                              | 35        | 1.45%   |
| Nvidia TU106 High Definition Audio Controller                              | 30        | 1.24%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 28        | 1.16%   |
| Intel Haswell-ULT HD Audio Controller                                      | 28        | 1.16%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 28        | 1.16%   |
| Intel 8 Series HD Audio Controller                                         | 28        | 1.16%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 25        | 1.04%   |
| Intel CM238 HD Audio Controller                                            | 25        | 1.04%   |
| Intel Broadwell-U Audio Controller                                         | 25        | 1.04%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 24        | 0.99%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 23        | 0.95%   |
| Intel Comet Lake PCH cAVS                                                  | 23        | 0.95%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 23        | 0.95%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 23        | 0.95%   |
| AMD FCH Azalia Controller                                                  | 21        | 0.87%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 19        | 0.79%   |
| AMD Navi 10 HDMI Audio                                                     | 19        | 0.79%   |
| Nvidia GA104 High Definition Audio Controller                              | 18        | 0.75%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 18        | 0.75%   |
| Nvidia GM204 High Definition Audio Controller                              | 17        | 0.7%    |
| Nvidia GK107 HDMI Audio Controller                                         | 17        | 0.7%    |
| AMD Kabini HDMI/DP Audio                                                   | 17        | 0.7%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 296       | 21.17%  |
| SK hynix            | 239       | 17.1%   |
| Kingston            | 141       | 10.09%  |
| Corsair             | 135       | 9.66%   |
| Micron Technology   | 126       | 9.01%   |
| Crucial             | 106       | 7.58%   |
| G.Skill             | 83        | 5.94%   |
| Unknown             | 81        | 5.79%   |
| A-DATA Technology   | 29        | 2.07%   |
| Team                | 23        | 1.65%   |
| Ramaxel Technology  | 20        | 1.43%   |
| Nanya Technology    | 18        | 1.29%   |
| Elpida              | 16        | 1.14%   |
| Patriot             | 12        | 0.86%   |
| Unknown (ABCD)      | 7         | 0.5%    |
| Unknown             | 7         | 0.5%    |
| Avant               | 5         | 0.36%   |
| Transcend           | 4         | 0.29%   |
| Silicon Power       | 4         | 0.29%   |
| Goldkey             | 4         | 0.29%   |
| ASint Technology    | 4         | 0.29%   |
| Apacer              | 4         | 0.29%   |
| Neo Forza           | 3         | 0.21%   |
| PNY                 | 2         | 0.14%   |
| Lexar               | 2         | 0.14%   |
| Kingmax             | 2         | 0.14%   |
| GOODRAM             | 2         | 0.14%   |
| GeIL                | 2         | 0.14%   |
| AMD                 | 2         | 0.14%   |
| Unknown (898F)      | 1         | 0.07%   |
| Unknown (0x8634)    | 1         | 0.07%   |
| Unknown (0x8319)    | 1         | 0.07%   |
| Unknown (09D5)      | 1         | 0.07%   |
| Unifosa             | 1         | 0.07%   |
| Timetec             | 1         | 0.07%   |
| Smart               | 1         | 0.07%   |
| Sesame              | 1         | 0.07%   |
| Saikano             | 1         | 0.07%   |
| S                   | 1         | 0.07%   |
| Lexar Co Limited    | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 18        | 1.2%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 17        | 1.13%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 17        | 1.13%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 13        | 0.86%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 13        | 0.86%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 13        | 0.86%   |
| SK hynix RAM HMA82GR7DJR8N-XN 16GB DIMM DDR4 3200MT/s            | 12        | 0.8%    |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 12        | 0.8%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 12        | 0.8%    |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 11        | 0.73%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 11        | 0.73%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 11        | 0.73%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 11        | 0.73%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 9         | 0.6%    |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 9         | 0.6%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.53%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.53%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 7         | 0.47%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.47%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 7         | 0.47%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 7         | 0.47%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 7         | 0.47%   |
| Unknown                                                          | 7         | 0.47%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s           | 6         | 0.4%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.4%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.4%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.4%    |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.4%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.4%    |
| Samsung RAM M471B1G73QH0-YK0 8192MB SODIMM DDR3 1600MT/s         | 6         | 0.4%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                        | 5         | 0.33%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 5         | 0.33%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 5         | 0.33%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s             | 5         | 0.33%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 0.33%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8192MB SODIMM DDR4 2667MT/s        | 5         | 0.33%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 5         | 0.33%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 700       | 58.68%  |
| DDR3    | 374       | 31.35%  |
| LPDDR3  | 32        | 2.68%   |
| LPDDR4  | 25        | 2.1%    |
| Unknown | 24        | 2.01%   |
| SDRAM   | 17        | 1.42%   |
| DDR2    | 16        | 1.34%   |
| DDR     | 3         | 0.25%   |
| LPDDR5  | 1         | 0.08%   |
| DDR5    | 1         | 0.08%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 628       | 52.73%  |
| DIMM         | 497       | 41.73%  |
| Row Of Chips | 58        | 4.87%   |
| Chip         | 8         | 0.67%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 565       | 43.3%   |
| 4096  | 370       | 28.35%  |
| 16384 | 219       | 16.78%  |
| 2048  | 99        | 7.59%   |
| 32768 | 37        | 2.84%   |
| 1024  | 13        | 1%      |
| 64    | 1         | 0.08%   |
| 16    | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 268       | 20.18%  |
| 2667    | 220       | 16.57%  |
| 3200    | 206       | 15.51%  |
| 2400    | 127       | 9.56%   |
| 1333    | 69        | 5.2%    |
| 2133    | 65        | 4.89%   |
| 3600    | 61        | 4.59%   |
| 1334    | 31        | 2.33%   |
| 1867    | 28        | 2.11%   |
| 3466    | 23        | 1.73%   |
| 3266    | 21        | 1.58%   |
| 3000    | 20        | 1.51%   |
| 1067    | 20        | 1.51%   |
| 3400    | 15        | 1.13%   |
| 3733    | 13        | 0.98%   |
| 2933    | 12        | 0.9%    |
| 800     | 12        | 0.9%    |
| 667     | 12        | 0.9%    |
| Unknown | 11        | 0.83%   |
| 4267    | 9         | 0.68%   |
| 2800    | 9         | 0.68%   |
| 2666    | 8         | 0.6%    |
| 4199    | 5         | 0.38%   |
| 1866    | 5         | 0.38%   |
| 8400    | 4         | 0.3%    |
| 3800    | 4         | 0.3%    |
| 2048    | 4         | 0.3%    |
| 1800    | 4         | 0.3%    |
| 1066    | 4         | 0.3%    |
| 3866    | 3         | 0.23%   |
| 3334    | 3         | 0.23%   |
| 975     | 3         | 0.23%   |
| 3333    | 2         | 0.15%   |
| 3067    | 2         | 0.15%   |
| 2934    | 2         | 0.15%   |
| 2465    | 2         | 0.15%   |
| 2200    | 2         | 0.15%   |
| 533     | 2         | 0.15%   |
| 52217   | 1         | 0.08%   |
| 6400    | 1         | 0.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 14        | 38.89%  |
| Brother Industries  | 13        | 36.11%  |
| Seiko Epson         | 3         | 8.33%   |
| Canon               | 3         | 8.33%   |
| Samsung Electronics | 1         | 2.78%   |
| MIIIW               | 1         | 2.78%   |
| Dymo-CoStar         | 1         | 2.78%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Seiko Epson ET-4700 Series             | 2         | 5.56%   |
| HP DeskJet 2620 All-in-One Printer     | 2         | 5.56%   |
| Brother Printer                        | 2         | 5.56%   |
| Brother DCP-7055 scanner/printer       | 2         | 5.56%   |
| Seiko Epson ET-2710 Series             | 1         | 2.78%   |
| Samsung SCX-3400 Series                | 1         | 2.78%   |
| MIIIW MW Keyboard Air Mini             | 1         | 2.78%   |
| HP OfficeJet Pro 8020 series           | 1         | 2.78%   |
| HP OfficeJet Pro 6960                  | 1         | 2.78%   |
| HP OfficeJet 5200 series               | 1         | 2.78%   |
| HP OfficeJet 4650 series               | 1         | 2.78%   |
| HP LaserJet Professional P1102w        | 1         | 2.78%   |
| HP LaserJet P1005                      | 1         | 2.78%   |
| HP LaserJet M203-M206                  | 1         | 2.78%   |
| HP ENVY 4500 series                    | 1         | 2.78%   |
| HP Deskjet 4640 series                 | 1         | 2.78%   |
| HP DeskJet 3700 series                 | 1         | 2.78%   |
| HP DeskJet 2700 series                 | 1         | 2.78%   |
| HP Deskjet 1050 J410                   | 1         | 2.78%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo | 1         | 2.78%   |
| Canon PIXMA MG3600 Series              | 1         | 2.78%   |
| Canon LiDE 300                         | 1         | 2.78%   |
| Canon G2000 series                     | 1         | 2.78%   |
| Brother MFC-L3770CDW series            | 1         | 2.78%   |
| Brother MFC-L3750CDW                   | 1         | 2.78%   |
| Brother MFC-J6545DW                    | 1         | 2.78%   |
| Brother MFC-J497DW                     | 1         | 2.78%   |
| Brother MFC-J485DW                     | 1         | 2.78%   |
| Brother MFC-J450DW                     | 1         | 2.78%   |
| Brother HL-3140CW series               | 1         | 2.78%   |
| Brother DCP-L3550CDW                   | 1         | 2.78%   |
| Brother DCP-1610W                      | 1         | 2.78%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Seiko Epson     | 2         | 50%     |
| Hewlett-Packard | 2         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 25%     |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]           | 1         | 25%     |
| HP ScanJet 2400c                                        | 1         | 25%     |
| HP ScanJet 2200c                                        | 1         | 25%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                            | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Electronics                               | 188       | 23.12%  |
| IMC Networks                                      | 89        | 10.95%  |
| Logitech                                          | 73        | 8.98%   |
| Acer                                              | 70        | 8.61%   |
| Realtek Semiconductor                             | 62        | 7.63%   |
| Microdia                                          | 62        | 7.63%   |
| Sunplus Innovation Technology                     | 37        | 4.55%   |
| Apple                                             | 30        | 3.69%   |
| Cheng Uei Precision Industry (Foxlink)            | 28        | 3.44%   |
| Quanta                                            | 26        | 3.2%    |
| Syntek                                            | 19        | 2.34%   |
| Lite-On Technology                                | 15        | 1.85%   |
| Suyin                                             | 14        | 1.72%   |
| Lenovo                                            | 10        | 1.23%   |
| Microsoft                                         | 9         | 1.11%   |
| Silicon Motion                                    | 7         | 0.86%   |
| Samsung Electronics                               | 5         | 0.62%   |
| Primax Electronics                                | 5         | 0.62%   |
| Luxvisions Innotech Limited                       | 5         | 0.62%   |
| KYE Systems (Mouse Systems)                       | 5         | 0.62%   |
| Hewlett-Packard                                   | 4         | 0.49%   |
| Generalplus Technology                            | 4         | 0.49%   |
| Creative Technology                               | 4         | 0.49%   |
| Alcor Micro                                       | 4         | 0.49%   |
| Razer USA                                         | 3         | 0.37%   |
| Importek                                          | 3         | 0.37%   |
| GEMBIRD                                           | 3         | 0.37%   |
| WaveRider Communications                          | 2         | 0.25%   |
| Unknown                                           | 2         | 0.25%   |
| Sunplus Technology                                | 2         | 0.25%   |
| Sonix Technology                                  | 2         | 0.25%   |
| Ruision                                           | 2         | 0.25%   |
| Ricoh                                             | 2         | 0.25%   |
| AVerMedia Technologies                            | 2         | 0.25%   |
| ARC International                                 | 2         | 0.25%   |
| Z-Star Microelectronics                           | 1         | 0.12%   |
| STMicroelectronics Imaging Division (VLSI Vision) | 1         | 0.12%   |
| OmniVision Technologies                           | 1         | 0.12%   |
| Mimaki Engineering                                | 1         | 0.12%   |
| MacroSilicon                                      | 1         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                        | 53        | 6.48%   |
| Microdia Integrated_Webcam_HD                    | 28        | 3.42%   |
| Realtek Integrated_Webcam_HD                     | 26        | 3.18%   |
| IMC Networks Integrated Camera                   | 25        | 3.06%   |
| Acer Integrated Camera                           | 23        | 2.81%   |
| Chicony HD WebCam                                | 22        | 2.69%   |
| Logitech HD Pro Webcam C920                      | 20        | 2.44%   |
| IMC Networks USB2.0 HD UVC WebCam                | 19        | 2.32%   |
| Logitech Webcam C270                             | 17        | 2.08%   |
| Syntek Integrated Camera                         | 13        | 1.59%   |
| Lite-On Integrated Camera                        | 12        | 1.47%   |
| IMC Networks USB2.0 VGA UVC WebCam               | 11        | 1.34%   |
| Acer EasyCamera                                  | 11        | 1.34%   |
| Chicony USB2.0 Camera                            | 10        | 1.22%   |
| Sunplus Integrated_Webcam_HD                     | 9         | 1.1%    |
| Apple Built-in iSight                            | 9         | 1.1%    |
| Microdia Integrated Webcam                       | 8         | 0.98%   |
| Chicony HP Truevision HD                         | 8         | 0.98%   |
| Apple iPhone5/5C/5S/6                            | 8         | 0.98%   |
| Quanta HD Webcam                                 | 7         | 0.86%   |
| Logitech C922 Pro Stream Webcam                  | 7         | 0.86%   |
| Chicony USB2.0 VGA UVC WebCam                    | 7         | 0.86%   |
| Chicony HP Wide Vision HD Camera                 | 7         | 0.86%   |
| Apple FaceTime HD Camera (Built-in)              | 7         | 0.86%   |
| Acer BisonCam,NB Pro                             | 7         | 0.86%   |
| Lenovo Integrated Webcam [R5U877]                | 6         | 0.73%   |
| IMC Networks Lenovo EasyCamera                   | 6         | 0.73%   |
| Chicony HP HD Camera                             | 6         | 0.73%   |
| Chicony EasyCamera                               | 6         | 0.73%   |
| Samsung Galaxy A5 (MTP)                          | 5         | 0.61%   |
| Quanta HD User Facing                            | 5         | 0.61%   |
| Microsoft LifeCam HD-3000                        | 5         | 0.61%   |
| IMC Networks VGA UVC WebCam                      | 5         | 0.61%   |
| Chicony USB2.0 HD UVC WebCam                     | 5         | 0.61%   |
| Chicony TOSHIBA Web Camera - HD                  | 5         | 0.61%   |
| Chicony Integrated Camera (1280x720@30)          | 5         | 0.61%   |
| Chicony HP TrueVision HD Camera                  | 5         | 0.61%   |
| Chicony HP HD Webcam                             | 5         | 0.61%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam | 5         | 0.61%   |
| Apple FaceTime HD Camera                         | 5         | 0.61%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 56        | 39.72%  |
| Synaptics                  | 30        | 21.28%  |
| Shenzhen Goodix Technology | 24        | 17.02%  |
| Upek                       | 9         | 6.38%   |
| Elan Microelectronics      | 9         | 6.38%   |
| LighTuning Technology      | 6         | 4.26%   |
| AuthenTec                  | 6         | 4.26%   |
| STMicroelectronics         | 1         | 0.71%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 16        | 11.35%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 10        | 7.09%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 9         | 6.38%   |
| Validity Sensors Synaptics WBDI                                            | 9         | 6.38%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 6.38%   |
| Shenzhen Goodix Fingerprint Reader                                         | 9         | 6.38%   |
| Shenzhen Goodix  FingerPrint Device                                        | 8         | 5.67%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 4.96%   |
| Unknown                                                                    | 6         | 4.26%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 3.55%   |
| Synaptics  WBDI                                                            | 5         | 3.55%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 3.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 3.55%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 4         | 2.84%   |
| Elan ELAN:Fingerprint                                                      | 4         | 2.84%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 2.13%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 3         | 2.13%   |
| Elan ELAN:ARM-M4                                                           | 3         | 2.13%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 1.42%   |
| Synaptics WBDI Device                                                      | 2         | 1.42%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 1.42%   |
| AuthenTec AES1600                                                          | 2         | 1.42%   |
| Validity Sensors VFS491                                                    | 1         | 0.71%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 0.71%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 0.71%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 0.71%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.71%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 1         | 0.71%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.71%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.71%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.71%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.71%   |
| AuthenTec AES2810                                                          | 1         | 0.71%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.71%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.71%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 23        | 37.1%   |
| Alcor Micro           | 22        | 35.48%  |
| O2 Micro              | 5         | 8.06%   |
| Lenovo                | 4         | 6.45%   |
| Upek                  | 2         | 3.23%   |
| Gemalto (was Gemplus) | 2         | 3.23%   |
| Yubico.com            | 1         | 1.61%   |
| SCM Microsystems      | 1         | 1.61%   |
| Clay Logic            | 1         | 1.61%   |
| Cherry                | 1         | 1.61%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 22        | 35.48%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 6         | 9.68%   |
| Broadcom BCM5880 Secure Applications Processor                               | 6         | 9.68%   |
| Broadcom 5880                                                                | 5         | 8.06%   |
| Broadcom 58200                                                               | 5         | 8.06%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 6.45%   |
| Lenovo Integrated Smart Card Reader                                          | 4         | 6.45%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 3.23%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 2         | 3.23%   |
| Yubico.com Yubikey NEO(-N) OTP+CCID                                          | 1         | 1.61%   |
| SCM Microsystems SCR3500 A Contact Reader                                    | 1         | 1.61%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 1.61%   |
| Clay Logic Nitrokey Pro                                                      | 1         | 1.61%   |
| Cherry Smart Card Reader USB                                                 | 1         | 1.61%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 1.61%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 963       | 71.55%  |
| 1     | 302       | 22.44%  |
| 2     | 74        | 5.5%    |
| 3     | 5         | 0.37%   |
| 4     | 2         | 0.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 140       | 31.04%  |
| Graphics card            | 118       | 26.16%  |
| Chipcard                 | 59        | 13.08%  |
| Net/wireless             | 46        | 10.2%   |
| Multimedia controller    | 22        | 4.88%   |
| Camera                   | 20        | 4.43%   |
| Communication controller | 15        | 3.33%   |
| Unassigned class         | 10        | 2.22%   |
| Bluetooth                | 7         | 1.55%   |
| Network                  | 3         | 0.67%   |
| Card reader              | 3         | 0.67%   |
| Net/ethernet             | 2         | 0.44%   |
| Modem                    | 2         | 0.44%   |
| Dvb card                 | 2         | 0.44%   |
| Storage/nvme             | 1         | 0.22%   |
| Storage                  | 1         | 0.22%   |

