Linux in Austria - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Austria.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Austria/Desktop/README.md) and [notebooks](/Location/Austria/Notebook/README.md).

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

Total: 2827

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG STRIX B560-E GAMING ... | Desktop     | [498958a11d](https://linux-hardware.org/?probe=498958a11d) | Sep 07, 2023 |
| Unknown       | Unknown                     | Desktop     | [59544c398a](https://linux-hardware.org/?probe=59544c398a) | Sep 07, 2023 |
| GMKtec        | NucBox G2                   | Desktop     | [8c03fc694f](https://linux-hardware.org/?probe=8c03fc694f) | Sep 05, 2023 |
| GMKtec        | NucBox G2                   | Desktop     | [ba313b48f8](https://linux-hardware.org/?probe=ba313b48f8) | Sep 05, 2023 |
| Inter Sale... | NID-11125DE                 | Notebook    | [2c94bcc096](https://linux-hardware.org/?probe=2c94bcc096) | Sep 05, 2023 |
| Lenovo        | ThinkPad L380 Yoga 20M70... | Convertible | [245441c639](https://linux-hardware.org/?probe=245441c639) | Sep 05, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [5e7621ae15](https://linux-hardware.org/?probe=5e7621ae15) | Sep 04, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [73e3b8ef8a](https://linux-hardware.org/?probe=73e3b8ef8a) | Sep 04, 2023 |
| Lenovo        | IdeaPad Pro 5 14APH8 83A... | Notebook    | [7a27c6dd8d](https://linux-hardware.org/?probe=7a27c6dd8d) | Sep 03, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [4764776393](https://linux-hardware.org/?probe=4764776393) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [ddae17d733](https://linux-hardware.org/?probe=ddae17d733) | Sep 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [60889fc028](https://linux-hardware.org/?probe=60889fc028) | Sep 02, 2023 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [7cf0b6a1c4](https://linux-hardware.org/?probe=7cf0b6a1c4) | Sep 01, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [75ad357b16](https://linux-hardware.org/?probe=75ad357b16) | Sep 01, 2023 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [5f50ef24fe](https://linux-hardware.org/?probe=5f50ef24fe) | Sep 01, 2023 |
| Sony          | VPCEH2J1E                   | Notebook    | [0d1017e65a](https://linux-hardware.org/?probe=0d1017e65a) | Aug 31, 2023 |
| Dell          | 0P4T42 A01                  | All in one  | [0dd23cfbaa](https://linux-hardware.org/?probe=0dd23cfbaa) | Aug 31, 2023 |
| ASUSTek       | X555LAB                     | Notebook    | [e7d07d7c88](https://linux-hardware.org/?probe=e7d07d7c88) | Aug 31, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [05b083817c](https://linux-hardware.org/?probe=05b083817c) | Aug 31, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [f6f76a2e9d](https://linux-hardware.org/?probe=f6f76a2e9d) | Aug 30, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [6bf92318e7](https://linux-hardware.org/?probe=6bf92318e7) | Aug 30, 2023 |
| Lenovo        | ThinkPad A475 20KMS0K20S    | Notebook    | [2685098cd9](https://linux-hardware.org/?probe=2685098cd9) | Aug 29, 2023 |
| Lenovo        | G70-35 80Q5                 | Notebook    | [0e3563cf3e](https://linux-hardware.org/?probe=0e3563cf3e) | Aug 29, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [036ad179d7](https://linux-hardware.org/?probe=036ad179d7) | Aug 26, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [9e90f8b308](https://linux-hardware.org/?probe=9e90f8b308) | Aug 26, 2023 |
| Lenovo        | G70-35 80Q5                 | Notebook    | [1025de1dcf](https://linux-hardware.org/?probe=1025de1dcf) | Aug 25, 2023 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2707044ee5](https://linux-hardware.org/?probe=2707044ee5) | Aug 25, 2023 |
| Lenovo        | ThinkPad T410 2537UT5       | Notebook    | [8c0f550b61](https://linux-hardware.org/?probe=8c0f550b61) | Aug 24, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [b141917712](https://linux-hardware.org/?probe=b141917712) | Aug 23, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [90faf14c05](https://linux-hardware.org/?probe=90faf14c05) | Aug 23, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [86f9b36e03](https://linux-hardware.org/?probe=86f9b36e03) | Aug 20, 2023 |
| Chuwi         | LapBook SE                  | Notebook    | [8c338913ab](https://linux-hardware.org/?probe=8c338913ab) | Aug 19, 2023 |
| ASUSTek       | M4A77                       | Desktop     | [89bb5a2821](https://linux-hardware.org/?probe=89bb5a2821) | Aug 19, 2023 |
| Acer          | Predator PH317-52           | Notebook    | [c942508cf0](https://linux-hardware.org/?probe=c942508cf0) | Aug 18, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [3b6cc87ac7](https://linux-hardware.org/?probe=3b6cc87ac7) | Aug 17, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [af217ce6dc](https://linux-hardware.org/?probe=af217ce6dc) | Aug 16, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [feeb3d8bbe](https://linux-hardware.org/?probe=feeb3d8bbe) | Aug 16, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [0122fef8fd](https://linux-hardware.org/?probe=0122fef8fd) | Aug 15, 2023 |
| MSI           | MS-B1831                    | Desktop     | [25e33380e5](https://linux-hardware.org/?probe=25e33380e5) | Aug 14, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [1bb822c058](https://linux-hardware.org/?probe=1bb822c058) | Aug 13, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [c24273512e](https://linux-hardware.org/?probe=c24273512e) | Aug 13, 2023 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [400e17fe60](https://linux-hardware.org/?probe=400e17fe60) | Aug 13, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [d344d7ada0](https://linux-hardware.org/?probe=d344d7ada0) | Aug 13, 2023 |
| HP            | 350 G2                      | Notebook    | [f0fa8865d3](https://linux-hardware.org/?probe=f0fa8865d3) | Aug 12, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [6f722400c2](https://linux-hardware.org/?probe=6f722400c2) | Aug 11, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [e6624cc619](https://linux-hardware.org/?probe=e6624cc619) | Aug 11, 2023 |
| HP            | 350 G2                      | Notebook    | [dde52cb361](https://linux-hardware.org/?probe=dde52cb361) | Aug 10, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [aacbd7403c](https://linux-hardware.org/?probe=aacbd7403c) | Aug 10, 2023 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [a7a57a8a56](https://linux-hardware.org/?probe=a7a57a8a56) | Aug 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CF0... | Notebook    | [89cb081c1f](https://linux-hardware.org/?probe=89cb081c1f) | Aug 10, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [c5a255abcb](https://linux-hardware.org/?probe=c5a255abcb) | Aug 10, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [69a5fc6981](https://linux-hardware.org/?probe=69a5fc6981) | Aug 10, 2023 |
| ASRock        | Z68 Pro3                    | Desktop     | [f949a6e2a5](https://linux-hardware.org/?probe=f949a6e2a5) | Aug 09, 2023 |
| Toshiba       | Satellite C70D-B            | Notebook    | [ac775a3228](https://linux-hardware.org/?probe=ac775a3228) | Aug 09, 2023 |
| HP            | 350 G2                      | Notebook    | [3b79bb8a69](https://linux-hardware.org/?probe=3b79bb8a69) | Aug 09, 2023 |
| Toshiba       | Satellite C70D-B            | Notebook    | [e3f3b2fcfb](https://linux-hardware.org/?probe=e3f3b2fcfb) | Aug 09, 2023 |
| Dell          | Latitude 5540               | Notebook    | [08c875f58b](https://linux-hardware.org/?probe=08c875f58b) | Aug 08, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [1134279f41](https://linux-hardware.org/?probe=1134279f41) | Aug 06, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [fe4aa817e1](https://linux-hardware.org/?probe=fe4aa817e1) | Aug 06, 2023 |
| ASUSTek       | ROG Ally RC71L_RC71L        | Tablet      | [cb3d78955a](https://linux-hardware.org/?probe=cb3d78955a) | Aug 05, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [b30001b3fe](https://linux-hardware.org/?probe=b30001b3fe) | Aug 05, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [15826fe271](https://linux-hardware.org/?probe=15826fe271) | Aug 04, 2023 |
| Dell          | Latitude E6400              | Notebook    | [ca61145546](https://linux-hardware.org/?probe=ca61145546) | Aug 04, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | Notebook    | [64e640ff2b](https://linux-hardware.org/?probe=64e640ff2b) | Aug 04, 2023 |
| ASUSTek       | M3A78-T                     | Desktop     | [e97447ea9d](https://linux-hardware.org/?probe=e97447ea9d) | Aug 03, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [2254be2ae2](https://linux-hardware.org/?probe=2254be2ae2) | Aug 03, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [49a27fb8fb](https://linux-hardware.org/?probe=49a27fb8fb) | Aug 03, 2023 |
| HP            | EliteBook 8740w             | Notebook    | [e2d58e4a51](https://linux-hardware.org/?probe=e2d58e4a51) | Aug 03, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [59cd10f50e](https://linux-hardware.org/?probe=59cd10f50e) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [291bf82303](https://linux-hardware.org/?probe=291bf82303) | Aug 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 8... | Notebook    | [7a9c57ad84](https://linux-hardware.org/?probe=7a9c57ad84) | Aug 02, 2023 |
| ASRock        | Z170 Extreme6+              | Desktop     | [84c1a14a56](https://linux-hardware.org/?probe=84c1a14a56) | Aug 01, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [c04f6d6467](https://linux-hardware.org/?probe=c04f6d6467) | Aug 01, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [19c877cd88](https://linux-hardware.org/?probe=19c877cd88) | Jul 31, 2023 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [cd96592ef8](https://linux-hardware.org/?probe=cd96592ef8) | Jul 31, 2023 |
| Dell          | Latitude E6400              | Notebook    | [5863677081](https://linux-hardware.org/?probe=5863677081) | Jul 31, 2023 |
| Lenovo        | ThinkPad T470 20HES2C000    | Notebook    | [6cb5b31808](https://linux-hardware.org/?probe=6cb5b31808) | Jul 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [68d5cb02bf](https://linux-hardware.org/?probe=68d5cb02bf) | Jul 29, 2023 |
| MSI           | B250M PRO-VDH               | Desktop     | [5bcf13119e](https://linux-hardware.org/?probe=5bcf13119e) | Jul 27, 2023 |
| Dell          | Inspiron 5720               | Notebook    | [8674c464bd](https://linux-hardware.org/?probe=8674c464bd) | Jul 27, 2023 |
| Microsoft     | Surface Pro 4               | Tablet      | [067a1b82b7](https://linux-hardware.org/?probe=067a1b82b7) | Jul 25, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [ac0ba8e136](https://linux-hardware.org/?probe=ac0ba8e136) | Jul 25, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [60b9e2fbc9](https://linux-hardware.org/?probe=60b9e2fbc9) | Jul 24, 2023 |
| Microsoft     | Surface Go 3                | Tablet      | [bc4c439514](https://linux-hardware.org/?probe=bc4c439514) | Jul 23, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [c78a2441ee](https://linux-hardware.org/?probe=c78a2441ee) | Jul 23, 2023 |
| ASRock        | TRX40 Creator               | Desktop     | [5bf3142c39](https://linux-hardware.org/?probe=5bf3142c39) | Jul 21, 2023 |
| Dell          | Latitude E6440              | Notebook    | [b60d8ab453](https://linux-hardware.org/?probe=b60d8ab453) | Jul 21, 2023 |
| Valve         | Jupiter                     | Notebook    | [db220d13d6](https://linux-hardware.org/?probe=db220d13d6) | Jul 20, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [7171de16ea](https://linux-hardware.org/?probe=7171de16ea) | Jul 19, 2023 |
| ASRock        | Z170 Extreme6+              | Desktop     | [5ead4ab228](https://linux-hardware.org/?probe=5ead4ab228) | Jul 17, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [01b8ada2a7](https://linux-hardware.org/?probe=01b8ada2a7) | Jul 15, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [6b351b341e](https://linux-hardware.org/?probe=6b351b341e) | Jul 15, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B3402FEA... | Convertible | [4be00d26b2](https://linux-hardware.org/?probe=4be00d26b2) | Jul 14, 2023 |
| Lenovo        | IdeaPadFlex 5 14IAU7 82R... | Convertible | [080a9244cf](https://linux-hardware.org/?probe=080a9244cf) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2A50... | Notebook    | [69bd0f2129](https://linux-hardware.org/?probe=69bd0f2129) | Jul 13, 2023 |
| Lenovo        | ThinkPad T460s 20FAS2A50... | Notebook    | [20225a0680](https://linux-hardware.org/?probe=20225a0680) | Jul 13, 2023 |
| ASRock        | H97 Performance             | Desktop     | [3d8cc4b423](https://linux-hardware.org/?probe=3d8cc4b423) | Jul 11, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [2749c7cf78](https://linux-hardware.org/?probe=2749c7cf78) | Jul 11, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [b2de29a3db](https://linux-hardware.org/?probe=b2de29a3db) | Jul 10, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [04c6c9ba2b](https://linux-hardware.org/?probe=04c6c9ba2b) | Jul 10, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [3ad7db3176](https://linux-hardware.org/?probe=3ad7db3176) | Jul 10, 2023 |
| Dell          | 09KPNV A01                  | Desktop     | [596389ea27](https://linux-hardware.org/?probe=596389ea27) | Jul 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [7c9b47b69f](https://linux-hardware.org/?probe=7c9b47b69f) | Jul 10, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [919d1fc65b](https://linux-hardware.org/?probe=919d1fc65b) | Jul 09, 2023 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [89dc06fa6d](https://linux-hardware.org/?probe=89dc06fa6d) | Jul 09, 2023 |
| ASUSTek       | G60VX                       | Notebook    | [3273a8de27](https://linux-hardware.org/?probe=3273a8de27) | Jul 09, 2023 |
| MSI           | MS-B9181                    | Desktop     | [4702ba374d](https://linux-hardware.org/?probe=4702ba374d) | Jul 09, 2023 |
| ASRock        | H97 Performance             | Desktop     | [8058c54fb2](https://linux-hardware.org/?probe=8058c54fb2) | Jul 08, 2023 |
| ASRock        | H97 Performance             | Desktop     | [6994d9f579](https://linux-hardware.org/?probe=6994d9f579) | Jul 08, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [c1b5a5f99b](https://linux-hardware.org/?probe=c1b5a5f99b) | Jul 08, 2023 |
| Acer          | TravelMate P215-53          | Notebook    | [5810f4f1f8](https://linux-hardware.org/?probe=5810f4f1f8) | Jul 08, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [4e0acb57f9](https://linux-hardware.org/?probe=4e0acb57f9) | Jul 07, 2023 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [cae21c5121](https://linux-hardware.org/?probe=cae21c5121) | Jul 07, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [e328019dd8](https://linux-hardware.org/?probe=e328019dd8) | Jul 07, 2023 |
| Medion        | Unknown                     | Notebook    | [8fd3bc8734](https://linux-hardware.org/?probe=8fd3bc8734) | Jul 07, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [2fd3eada0f](https://linux-hardware.org/?probe=2fd3eada0f) | Jul 07, 2023 |
| ASUSTek       | M4A78-E                     | Desktop     | [c5e94d62b9](https://linux-hardware.org/?probe=c5e94d62b9) | Jul 06, 2023 |
| MSI           | H110 PC MATE                | Desktop     | [cc74c165b7](https://linux-hardware.org/?probe=cc74c165b7) | Jul 06, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [bbce89859f](https://linux-hardware.org/?probe=bbce89859f) | Jul 06, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [bb708e03aa](https://linux-hardware.org/?probe=bb708e03aa) | Jul 05, 2023 |
| HP            | ProBook 4740s               | Notebook    | [c920d177db](https://linux-hardware.org/?probe=c920d177db) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [117a651e12](https://linux-hardware.org/?probe=117a651e12) | Jul 03, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [5f2c613312](https://linux-hardware.org/?probe=5f2c613312) | Jul 03, 2023 |
| MSI           | Z370 OC GAMING              | Desktop     | [f2796b9262](https://linux-hardware.org/?probe=f2796b9262) | Jul 02, 2023 |
| HP            | 2129                        | Desktop     | [cc9462c976](https://linux-hardware.org/?probe=cc9462c976) | Jul 02, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [31a9983e65](https://linux-hardware.org/?probe=31a9983e65) | Jul 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [88b0de8666](https://linux-hardware.org/?probe=88b0de8666) | Jul 01, 2023 |
| Valve         | Jupiter                     | Notebook    | [cd28af9419](https://linux-hardware.org/?probe=cd28af9419) | Jun 30, 2023 |
| ASUSTek       | F1A75-V EVO                 | Desktop     | [b59f4f203c](https://linux-hardware.org/?probe=b59f4f203c) | Jun 30, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [0fae87e118](https://linux-hardware.org/?probe=0fae87e118) | Jun 29, 2023 |
| Acer          | Aspire VN7-593G             | Notebook    | [2302cbfba7](https://linux-hardware.org/?probe=2302cbfba7) | Jun 28, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [d4c9f8de35](https://linux-hardware.org/?probe=d4c9f8de35) | Jun 27, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [eeb516967a](https://linux-hardware.org/?probe=eeb516967a) | Jun 26, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [a2a87af2a4](https://linux-hardware.org/?probe=a2a87af2a4) | Jun 26, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [2f3a03f9d4](https://linux-hardware.org/?probe=2f3a03f9d4) | Jun 25, 2023 |
| ASUSTek       | ROG STRIX B760-F GAMING ... | Desktop     | [117bfb7088](https://linux-hardware.org/?probe=117bfb7088) | Jun 25, 2023 |
| Lenovo        | ThinkPad X230 2324H58       | Notebook    | [bcf8a71bb4](https://linux-hardware.org/?probe=bcf8a71bb4) | Jun 25, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [3cb015a09d](https://linux-hardware.org/?probe=3cb015a09d) | Jun 23, 2023 |
| ASUSTek       | M4A77                       | Desktop     | [67e6b51c63](https://linux-hardware.org/?probe=67e6b51c63) | Jun 23, 2023 |
| MSI           | 760GM -E51                  | Desktop     | [3f0c7f7d21](https://linux-hardware.org/?probe=3f0c7f7d21) | Jun 22, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [66736b8fbb](https://linux-hardware.org/?probe=66736b8fbb) | Jun 21, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [c3961b2aa5](https://linux-hardware.org/?probe=c3961b2aa5) | Jun 21, 2023 |
| ASUSTek       | K56CB                       | Notebook    | [e00f1f735d](https://linux-hardware.org/?probe=e00f1f735d) | Jun 20, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [9fa828d2e4](https://linux-hardware.org/?probe=9fa828d2e4) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [513165d4f6](https://linux-hardware.org/?probe=513165d4f6) | Jun 20, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [15e75e17fc](https://linux-hardware.org/?probe=15e75e17fc) | Jun 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [576a62665a](https://linux-hardware.org/?probe=576a62665a) | Jun 20, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [d95fa943f1](https://linux-hardware.org/?probe=d95fa943f1) | Jun 19, 2023 |
| MSI           | Bravo 17 A4DDR              | Notebook    | [bae46c4d0b](https://linux-hardware.org/?probe=bae46c4d0b) | Jun 19, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [22fc172f71](https://linux-hardware.org/?probe=22fc172f71) | Jun 18, 2023 |
| HP            | 3646h                       | Desktop     | [bbe600a4ab](https://linux-hardware.org/?probe=bbe600a4ab) | Jun 18, 2023 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [2b3a058830](https://linux-hardware.org/?probe=2b3a058830) | Jun 17, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [288db43785](https://linux-hardware.org/?probe=288db43785) | Jun 16, 2023 |
| Apple         | MacBookPro8,2               | Notebook    | [d254709437](https://linux-hardware.org/?probe=d254709437) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [e0a00a71de](https://linux-hardware.org/?probe=e0a00a71de) | Jun 15, 2023 |
| HP            | Notebook                    | Notebook    | [76433ab03f](https://linux-hardware.org/?probe=76433ab03f) | Jun 15, 2023 |
| Acer          | TravelMate 5742Z            | Notebook    | [abf5dbde31](https://linux-hardware.org/?probe=abf5dbde31) | Jun 14, 2023 |
| Lenovo        | ThinkPad T470s 20HF005QM... | Notebook    | [2eed8e0355](https://linux-hardware.org/?probe=2eed8e0355) | Jun 13, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [d2a0d735db](https://linux-hardware.org/?probe=d2a0d735db) | Jun 13, 2023 |
| Samsung       | 355V4C/355V4X/355V5C/355... | Notebook    | [fdc4101cba](https://linux-hardware.org/?probe=fdc4101cba) | Jun 13, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [93fe499e47](https://linux-hardware.org/?probe=93fe499e47) | Jun 12, 2023 |
| Lenovo        | ThinkPad W541 20EGS15J0N    | Notebook    | [ba935e9d5c](https://linux-hardware.org/?probe=ba935e9d5c) | Jun 12, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [3918c9dc55](https://linux-hardware.org/?probe=3918c9dc55) | Jun 12, 2023 |
| HP            | ProBook 440 G4              | Notebook    | [411faeafd4](https://linux-hardware.org/?probe=411faeafd4) | Jun 11, 2023 |
| Dell          | 0KC9NP A01                  | Desktop     | [ab5b79d6fd](https://linux-hardware.org/?probe=ab5b79d6fd) | Jun 10, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d6be89e452](https://linux-hardware.org/?probe=d6be89e452) | Jun 10, 2023 |
| Notebook      | NJ50_70CU                   | Notebook    | [d39b8694fd](https://linux-hardware.org/?probe=d39b8694fd) | Jun 10, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [4dcc51e897](https://linux-hardware.org/?probe=4dcc51e897) | Jun 10, 2023 |
| ASRock        | B365M Pro4-F                | Desktop     | [e54f1a9447](https://linux-hardware.org/?probe=e54f1a9447) | Jun 10, 2023 |
| ASRock        | Z690M-ITX/ax                | Desktop     | [f0bad84fca](https://linux-hardware.org/?probe=f0bad84fca) | Jun 08, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [09b2301e59](https://linux-hardware.org/?probe=09b2301e59) | Jun 08, 2023 |
| ASRock        | B365M Pro4-F                | Desktop     | [7ed0f0346c](https://linux-hardware.org/?probe=7ed0f0346c) | Jun 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [7e07a9c15d](https://linux-hardware.org/?probe=7e07a9c15d) | Jun 07, 2023 |
| Dell          | Latitude E7250              | Notebook    | [a80182e728](https://linux-hardware.org/?probe=a80182e728) | Jun 06, 2023 |
| HP            | 8265                        | Desktop     | [7afc259b97](https://linux-hardware.org/?probe=7afc259b97) | Jun 05, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [5b7617b9c0](https://linux-hardware.org/?probe=5b7617b9c0) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [f53388e7df](https://linux-hardware.org/?probe=f53388e7df) | Jun 05, 2023 |
| HP            | 1998                        | Desktop     | [c6183bd564](https://linux-hardware.org/?probe=c6183bd564) | Jun 05, 2023 |
| Dell          | Latitude E7450              | Notebook    | [e19dbd1a84](https://linux-hardware.org/?probe=e19dbd1a84) | Jun 05, 2023 |
| Lenovo        | ThinkPad X1 Extreme 2nd ... | Notebook    | [6c151a9750](https://linux-hardware.org/?probe=6c151a9750) | Jun 05, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [274b78cda3](https://linux-hardware.org/?probe=274b78cda3) | Jun 03, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [119fd5249f](https://linux-hardware.org/?probe=119fd5249f) | Jun 03, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [e0008bd879](https://linux-hardware.org/?probe=e0008bd879) | Jun 03, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [979df15914](https://linux-hardware.org/?probe=979df15914) | Jun 03, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [2378902ae8](https://linux-hardware.org/?probe=2378902ae8) | Jun 03, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [2cacb34a0d](https://linux-hardware.org/?probe=2cacb34a0d) | Jun 02, 2023 |
| Supermicro    | X12STD-F                    | Desktop     | [df7c4a738e](https://linux-hardware.org/?probe=df7c4a738e) | Jun 01, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [0c0dc06847](https://linux-hardware.org/?probe=0c0dc06847) | May 31, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [c496e8a74f](https://linux-hardware.org/?probe=c496e8a74f) | May 30, 2023 |
| ASUSTek       | PRIME TRX40-PRO             | Desktop     | [4cbc2f9044](https://linux-hardware.org/?probe=4cbc2f9044) | May 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c2d144c313](https://linux-hardware.org/?probe=c2d144c313) | May 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4d7ccd868f](https://linux-hardware.org/?probe=4d7ccd868f) | May 30, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RW... | Notebook    | [74447476fe](https://linux-hardware.org/?probe=74447476fe) | May 30, 2023 |
| Valve         | Jupiter                     | Notebook    | [f2f00bcfcc](https://linux-hardware.org/?probe=f2f00bcfcc) | May 29, 2023 |
| Valve         | Jupiter                     | Notebook    | [242a13f378](https://linux-hardware.org/?probe=242a13f378) | May 27, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [69adae13fe](https://linux-hardware.org/?probe=69adae13fe) | May 27, 2023 |
| HP            | ZBook 17 G6                 | Notebook    | [177d184559](https://linux-hardware.org/?probe=177d184559) | May 26, 2023 |
| HP            | ZBook 17 G6                 | Notebook    | [56a8a0e368](https://linux-hardware.org/?probe=56a8a0e368) | May 26, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [3eb016e8c7](https://linux-hardware.org/?probe=3eb016e8c7) | May 23, 2023 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [692ba9d18f](https://linux-hardware.org/?probe=692ba9d18f) | May 22, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | Desktop     | [b68e5e0285](https://linux-hardware.org/?probe=b68e5e0285) | May 20, 2023 |
| ASUSTek       | PRIME B650M-A II            | Desktop     | [183b85c77c](https://linux-hardware.org/?probe=183b85c77c) | May 19, 2023 |
| Dell          | 08DM12 A05                  | Server      | [a6c10986c9](https://linux-hardware.org/?probe=a6c10986c9) | May 19, 2023 |
| ASRock        | AM1B-ITX                    | Desktop     | [a2e80bffac](https://linux-hardware.org/?probe=a2e80bffac) | May 19, 2023 |
| ASRock        | AM1B-ITX                    | Desktop     | [d0633ac39d](https://linux-hardware.org/?probe=d0633ac39d) | May 19, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [9d66e80652](https://linux-hardware.org/?probe=9d66e80652) | May 18, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [44bc1d8d62](https://linux-hardware.org/?probe=44bc1d8d62) | May 17, 2023 |
| HP            | ProBook 6570b               | Notebook    | [7d8b9d4be1](https://linux-hardware.org/?probe=7d8b9d4be1) | May 16, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [996d19a70c](https://linux-hardware.org/?probe=996d19a70c) | May 15, 2023 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [3bd39e50a8](https://linux-hardware.org/?probe=3bd39e50a8) | May 15, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [82db8cdf8a](https://linux-hardware.org/?probe=82db8cdf8a) | May 15, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [66f97c57e2](https://linux-hardware.org/?probe=66f97c57e2) | May 14, 2023 |
| Biostar       | N61PB-M2S                   | Desktop     | [4ac75a003b](https://linux-hardware.org/?probe=4ac75a003b) | May 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [a130b1b1d0](https://linux-hardware.org/?probe=a130b1b1d0) | May 14, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [66ae15a360](https://linux-hardware.org/?probe=66ae15a360) | May 14, 2023 |
| MSI           | GF65 Thin 10UE              | Notebook    | [7d8bb12818](https://linux-hardware.org/?probe=7d8bb12818) | May 14, 2023 |
| Gigabyte      | Z170X-UD5 TH-CF             | Desktop     | [6a84af6428](https://linux-hardware.org/?probe=6a84af6428) | May 14, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [5dceebaf6c](https://linux-hardware.org/?probe=5dceebaf6c) | May 13, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [53bfb33732](https://linux-hardware.org/?probe=53bfb33732) | May 13, 2023 |
| ASRock        | H510M-ITX/ac                | Desktop     | [9a8da03c1e](https://linux-hardware.org/?probe=9a8da03c1e) | May 12, 2023 |
| Sony          | SVE1513Z1EB                 | Notebook    | [d47ba48012](https://linux-hardware.org/?probe=d47ba48012) | May 12, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [cf7c801d5c](https://linux-hardware.org/?probe=cf7c801d5c) | May 12, 2023 |
| Biostar       | A68N-5600E                  | Desktop     | [55db0c720e](https://linux-hardware.org/?probe=55db0c720e) | May 12, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [55046e008f](https://linux-hardware.org/?probe=55046e008f) | May 11, 2023 |
| ASUSTek       | Z170-P                      | Desktop     | [17d57b61d7](https://linux-hardware.org/?probe=17d57b61d7) | May 11, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [aefc60eaea](https://linux-hardware.org/?probe=aefc60eaea) | May 11, 2023 |
| Sony          | VPCEH2J1E                   | Notebook    | [fb307bc1bb](https://linux-hardware.org/?probe=fb307bc1bb) | May 11, 2023 |
| TUXEDO        | Book XP1511                 | Notebook    | [37a17568a0](https://linux-hardware.org/?probe=37a17568a0) | May 11, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [c40c2cb964](https://linux-hardware.org/?probe=c40c2cb964) | May 10, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [a9df4bc7fb](https://linux-hardware.org/?probe=a9df4bc7fb) | May 10, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [6fd3dea188](https://linux-hardware.org/?probe=6fd3dea188) | May 10, 2023 |
| MSI           | MAG B560 TOMAHAWK WIFI      | Desktop     | [e55b8813e3](https://linux-hardware.org/?probe=e55b8813e3) | May 10, 2023 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | Desktop     | [58a9b45939](https://linux-hardware.org/?probe=58a9b45939) | May 09, 2023 |
| Dell          | Latitude 5310               | Notebook    | [d72db172f0](https://linux-hardware.org/?probe=d72db172f0) | May 07, 2023 |
| Toshiba       | TECRA A11                   | Notebook    | [456421ff37](https://linux-hardware.org/?probe=456421ff37) | May 07, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [40d1bba9e2](https://linux-hardware.org/?probe=40d1bba9e2) | May 07, 2023 |
| Lenovo        | 1038 SDK0Q40104 WIN 3305... | Server      | [7630762f0e](https://linux-hardware.org/?probe=7630762f0e) | May 06, 2023 |
| Acer          | Aspire 7741                 | Notebook    | [25f9d02593](https://linux-hardware.org/?probe=25f9d02593) | May 06, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [d7c37a25de](https://linux-hardware.org/?probe=d7c37a25de) | May 05, 2023 |
| Acer          | Aspire A114-31              | Notebook    | [a7e0c2d3b6](https://linux-hardware.org/?probe=a7e0c2d3b6) | May 05, 2023 |
| Toshiba       | Satellite U300              | Notebook    | [470632e542](https://linux-hardware.org/?probe=470632e542) | May 05, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [65ddedbd24](https://linux-hardware.org/?probe=65ddedbd24) | May 05, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [7d642208ec](https://linux-hardware.org/?probe=7d642208ec) | May 04, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [e31ba8f396](https://linux-hardware.org/?probe=e31ba8f396) | May 04, 2023 |
| Sony          | VPCEH2J1E                   | Notebook    | [c9b6063699](https://linux-hardware.org/?probe=c9b6063699) | May 04, 2023 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | Desktop     | [4e80f798e2](https://linux-hardware.org/?probe=4e80f798e2) | May 04, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [0d4ad3c608](https://linux-hardware.org/?probe=0d4ad3c608) | May 04, 2023 |
| Medion        | MS-7848                     | Desktop     | [ab7b4e658f](https://linux-hardware.org/?probe=ab7b4e658f) | May 03, 2023 |
| Lenovo        | Yoga C940-15IRH 81TE        | Convertible | [b8764f73bc](https://linux-hardware.org/?probe=b8764f73bc) | May 03, 2023 |
| Lenovo        | Yoga C940-15IRH 81TE        | Convertible | [da5caa8155](https://linux-hardware.org/?probe=da5caa8155) | May 03, 2023 |
| Lenovo        | 314F SDK0T08861 WIN 3305... | Desktop     | [0b303a3773](https://linux-hardware.org/?probe=0b303a3773) | May 03, 2023 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [22f50229d9](https://linux-hardware.org/?probe=22f50229d9) | May 03, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [a99c9cd007](https://linux-hardware.org/?probe=a99c9cd007) | May 02, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [79bad18cb6](https://linux-hardware.org/?probe=79bad18cb6) | May 02, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [9ca19209fd](https://linux-hardware.org/?probe=9ca19209fd) | May 01, 2023 |
| Lenovo        | Tablet 10 20L3000KGE        | Tablet      | [05edd845df](https://linux-hardware.org/?probe=05edd845df) | May 01, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [3fc2c4e9d9](https://linux-hardware.org/?probe=3fc2c4e9d9) | May 01, 2023 |
| Lenovo        | ThinkPad T470s W10DG 20J... | Notebook    | [e3984b7285](https://linux-hardware.org/?probe=e3984b7285) | May 01, 2023 |
| Medion        | E16402                      | Notebook    | [cff2f785ad](https://linux-hardware.org/?probe=cff2f785ad) | May 01, 2023 |
| ZOTAC         | ZBOX-CI527/CI547            | Mini pc     | [86e1a89b72](https://linux-hardware.org/?probe=86e1a89b72) | Apr 30, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [f1faff33de](https://linux-hardware.org/?probe=f1faff33de) | Apr 30, 2023 |
| MSI           | A68HM GRENADE               | Desktop     | [938aa1cb46](https://linux-hardware.org/?probe=938aa1cb46) | Apr 30, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [91011c02d6](https://linux-hardware.org/?probe=91011c02d6) | Apr 29, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [c374148e49](https://linux-hardware.org/?probe=c374148e49) | Apr 29, 2023 |
| Hampoo        | I1D6_C109S_Hi10Pro          | Tablet      | [e70ee6019c](https://linux-hardware.org/?probe=e70ee6019c) | Apr 29, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [7ce0658b0f](https://linux-hardware.org/?probe=7ce0658b0f) | Apr 29, 2023 |
| Lenovo        | ThinkPad X280 20KESBC402    | Notebook    | [0d5b86146e](https://linux-hardware.org/?probe=0d5b86146e) | Apr 29, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [1404923301](https://linux-hardware.org/?probe=1404923301) | Apr 28, 2023 |
| HP            | 8715                        | Mini pc     | [8d210cce39](https://linux-hardware.org/?probe=8d210cce39) | Apr 28, 2023 |
| Dell          | Latitude D630               | Notebook    | [0fecf73eea](https://linux-hardware.org/?probe=0fecf73eea) | Apr 28, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [57261fe5ec](https://linux-hardware.org/?probe=57261fe5ec) | Apr 27, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [1fa553ab02](https://linux-hardware.org/?probe=1fa553ab02) | Apr 27, 2023 |
| IGEL Techn... | M340C                       | Notebook    | [40970f0528](https://linux-hardware.org/?probe=40970f0528) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | Notebook    | [c3c972facf](https://linux-hardware.org/?probe=c3c972facf) | Apr 26, 2023 |
| IGEL Techn... | M340C                       | Notebook    | [f993513cd3](https://linux-hardware.org/?probe=f993513cd3) | Apr 26, 2023 |
| Biostar       | A68N-5600E                  | Desktop     | [ccaeaae27b](https://linux-hardware.org/?probe=ccaeaae27b) | Apr 25, 2023 |
| HP            | Elite x2 1012 G2            | Tablet      | [f76dc1b9b7](https://linux-hardware.org/?probe=f76dc1b9b7) | Apr 24, 2023 |
| Notebook      | NH5x_NH7x_HHx_HJx_HKx       | Notebook    | [0be1fdd77a](https://linux-hardware.org/?probe=0be1fdd77a) | Apr 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [0d6278dd3a](https://linux-hardware.org/?probe=0d6278dd3a) | Apr 22, 2023 |
| ASRock        | Z97E-ITX/ac                 | Desktop     | [f916f697ed](https://linux-hardware.org/?probe=f916f697ed) | Apr 22, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [820acdb913](https://linux-hardware.org/?probe=820acdb913) | Apr 22, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [a7359e872e](https://linux-hardware.org/?probe=a7359e872e) | Apr 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [d315f00cd8](https://linux-hardware.org/?probe=d315f00cd8) | Apr 21, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [3219512811](https://linux-hardware.org/?probe=3219512811) | Apr 20, 2023 |
| Medion        | P17605                      | Notebook    | [b68359f3d1](https://linux-hardware.org/?probe=b68359f3d1) | Apr 20, 2023 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [bebc7ec91b](https://linux-hardware.org/?probe=bebc7ec91b) | Apr 19, 2023 |
| Acer          | AS5755                      | Notebook    | [1c163eb17f](https://linux-hardware.org/?probe=1c163eb17f) | Apr 19, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [c36b1a5778](https://linux-hardware.org/?probe=c36b1a5778) | Apr 19, 2023 |
| Fujitsu       | D2778-C1 S26361-D2778-C1    | Desktop     | [10693010af](https://linux-hardware.org/?probe=10693010af) | Apr 18, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [58b159ef8f](https://linux-hardware.org/?probe=58b159ef8f) | Apr 18, 2023 |
| HUAWEI        | RLEF-XX                     | Notebook    | [b425e2afaf](https://linux-hardware.org/?probe=b425e2afaf) | Apr 18, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [52272d52d3](https://linux-hardware.org/?probe=52272d52d3) | Apr 18, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [c00d85072e](https://linux-hardware.org/?probe=c00d85072e) | Apr 18, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [aa1a6072ce](https://linux-hardware.org/?probe=aa1a6072ce) | Apr 18, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [f3ad72b64d](https://linux-hardware.org/?probe=f3ad72b64d) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [4964eb99e9](https://linux-hardware.org/?probe=4964eb99e9) | Apr 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X712... | Notebook    | [6c2d6d52e9](https://linux-hardware.org/?probe=6c2d6d52e9) | Apr 17, 2023 |
| Lenovo        | ThinkPad X13 Gen 1 20T20... | Notebook    | [19bb54bd98](https://linux-hardware.org/?probe=19bb54bd98) | Apr 16, 2023 |
| Lenovo        | ThinkPad P16 Gen 1 21D6S... | Notebook    | [6686a91041](https://linux-hardware.org/?probe=6686a91041) | Apr 16, 2023 |
| ASUSTek       | PRIME X299-DELUXE II        | Desktop     | [fad0ef7fef](https://linux-hardware.org/?probe=fad0ef7fef) | Apr 16, 2023 |
| Medion        | E7220                       | Notebook    | [ab189f426b](https://linux-hardware.org/?probe=ab189f426b) | Apr 15, 2023 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [6e9640e9c2](https://linux-hardware.org/?probe=6e9640e9c2) | Apr 15, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [424d545740](https://linux-hardware.org/?probe=424d545740) | Apr 14, 2023 |
| MSI           | A520M-A PRO                 | Desktop     | [b5f4a1670f](https://linux-hardware.org/?probe=b5f4a1670f) | Apr 13, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [c639e22b34](https://linux-hardware.org/?probe=c639e22b34) | Apr 13, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [fcbc0b286f](https://linux-hardware.org/?probe=fcbc0b286f) | Apr 12, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [2f7cf166f0](https://linux-hardware.org/?probe=2f7cf166f0) | Apr 11, 2023 |
| Gigabyte      | A520I AC                    | Desktop     | [32867fa30e](https://linux-hardware.org/?probe=32867fa30e) | Apr 09, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [5c0467f4cb](https://linux-hardware.org/?probe=5c0467f4cb) | Apr 09, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [f410666614](https://linux-hardware.org/?probe=f410666614) | Apr 09, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [44351926f8](https://linux-hardware.org/?probe=44351926f8) | Apr 08, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [11aee4ed7b](https://linux-hardware.org/?probe=11aee4ed7b) | Apr 08, 2023 |
| Lenovo        | Yoga Duet 7 13ITL6 82MA     | Tablet      | [a651483f3c](https://linux-hardware.org/?probe=a651483f3c) | Apr 07, 2023 |
| Lenovo        | ThinkPad X121e 3045A63      | Notebook    | [e9fa009df9](https://linux-hardware.org/?probe=e9fa009df9) | Apr 06, 2023 |
| Lenovo        | V15 G2 ITL 82KB             | Notebook    | [0ca203f8b0](https://linux-hardware.org/?probe=0ca203f8b0) | Apr 06, 2023 |
| ASUSTek       | ROG STRIX Z490-E GAMING     | Desktop     | [b81dc294df](https://linux-hardware.org/?probe=b81dc294df) | Apr 06, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [62debd585f](https://linux-hardware.org/?probe=62debd585f) | Apr 05, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [8e769590fb](https://linux-hardware.org/?probe=8e769590fb) | Apr 05, 2023 |
| HP            | 2B52                        | Desktop     | [4def1937bc](https://linux-hardware.org/?probe=4def1937bc) | Apr 04, 2023 |
| Fujitsu       | D3236-S1 S26361-D3236-S1    | Desktop     | [89962b2435](https://linux-hardware.org/?probe=89962b2435) | Apr 04, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [e33abdae24](https://linux-hardware.org/?probe=e33abdae24) | Apr 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [9f9f72230c](https://linux-hardware.org/?probe=9f9f72230c) | Apr 03, 2023 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | Desktop     | [2cbd354a8f](https://linux-hardware.org/?probe=2cbd354a8f) | Apr 03, 2023 |
| Valve         | Jupiter                     | Notebook    | [a3c3e3267a](https://linux-hardware.org/?probe=a3c3e3267a) | Apr 02, 2023 |
| Valve         | Jupiter                     | Notebook    | [774af9fced](https://linux-hardware.org/?probe=774af9fced) | Apr 02, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [68dade8d0a](https://linux-hardware.org/?probe=68dade8d0a) | Apr 02, 2023 |
| Lenovo        | ThinkPad E480 20KQS0B800    | Notebook    | [9c9b561ca2](https://linux-hardware.org/?probe=9c9b561ca2) | Apr 02, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [5dddcdcb25](https://linux-hardware.org/?probe=5dddcdcb25) | Apr 01, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [277d3c7f43](https://linux-hardware.org/?probe=277d3c7f43) | Apr 01, 2023 |
| HP            | 8715                        | Mini pc     | [bcd377dcb7](https://linux-hardware.org/?probe=bcd377dcb7) | Apr 01, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [b272d7b271](https://linux-hardware.org/?probe=b272d7b271) | Apr 01, 2023 |
| HP            | 8715                        | Mini pc     | [222fde0a83](https://linux-hardware.org/?probe=222fde0a83) | Mar 31, 2023 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [029afd6a5c](https://linux-hardware.org/?probe=029afd6a5c) | Mar 31, 2023 |
| HP            | EliteBook 2530p (KR059AV... | Notebook    | [e7f9bce466](https://linux-hardware.org/?probe=e7f9bce466) | Mar 31, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [fcb2279eb0](https://linux-hardware.org/?probe=fcb2279eb0) | Mar 31, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | Desktop     | [514d8ed8d6](https://linux-hardware.org/?probe=514d8ed8d6) | Mar 30, 2023 |
| Lenovo        | Yoga 500-15IBD 80N6         | Notebook    | [225e13e1f0](https://linux-hardware.org/?probe=225e13e1f0) | Mar 30, 2023 |
| HP            | Pavilion 17                 | Notebook    | [46e0a0aed1](https://linux-hardware.org/?probe=46e0a0aed1) | Mar 30, 2023 |
| HP            | Pavilion 17                 | Notebook    | [3da4500905](https://linux-hardware.org/?probe=3da4500905) | Mar 30, 2023 |
| HP            | ProBook 640 G1              | Notebook    | [5aa6a42aa2](https://linux-hardware.org/?probe=5aa6a42aa2) | Mar 29, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [147c0afb99](https://linux-hardware.org/?probe=147c0afb99) | Mar 29, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [b165f54c80](https://linux-hardware.org/?probe=b165f54c80) | Mar 28, 2023 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [f6236c5962](https://linux-hardware.org/?probe=f6236c5962) | Mar 27, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [9f3138d8d5](https://linux-hardware.org/?probe=9f3138d8d5) | Mar 27, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [91e01e5646](https://linux-hardware.org/?probe=91e01e5646) | Mar 26, 2023 |
| HP            | 8158 A01                    | Mini pc     | [8d1c60fe86](https://linux-hardware.org/?probe=8d1c60fe86) | Mar 26, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [ad2be3eba7](https://linux-hardware.org/?probe=ad2be3eba7) | Mar 26, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [3c68ddf942](https://linux-hardware.org/?probe=3c68ddf942) | Mar 26, 2023 |
| Lenovo        | ThinkPad SL 2743NSC         | Notebook    | [48d6301eaa](https://linux-hardware.org/?probe=48d6301eaa) | Mar 26, 2023 |
| HP            | 1497                        | Desktop     | [fb8706575a](https://linux-hardware.org/?probe=fb8706575a) | Mar 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [64485e9b53](https://linux-hardware.org/?probe=64485e9b53) | Mar 25, 2023 |
| Dell          | 0T7D40 A01                  | Desktop     | [9320ecf2b2](https://linux-hardware.org/?probe=9320ecf2b2) | Mar 25, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [76338f95ea](https://linux-hardware.org/?probe=76338f95ea) | Mar 25, 2023 |
| MSI           | A320M-A PRO MAX             | Desktop     | [505777b9b6](https://linux-hardware.org/?probe=505777b9b6) | Mar 25, 2023 |
| Lenovo        | 3746 WIN SDK0T76463 3422... | All in one  | [ec07bb84cf](https://linux-hardware.org/?probe=ec07bb84cf) | Mar 25, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [2f5c339d88](https://linux-hardware.org/?probe=2f5c339d88) | Mar 25, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [befbe47acc](https://linux-hardware.org/?probe=befbe47acc) | Mar 23, 2023 |
| Unknown       | Unknown                     | Soc         | [4a630d847a](https://linux-hardware.org/?probe=4a630d847a) | Mar 23, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [fab7c8ab05](https://linux-hardware.org/?probe=fab7c8ab05) | Mar 22, 2023 |
| Hampoo        | Cherry Trail CR             | Notebook    | [b293f3ba3e](https://linux-hardware.org/?probe=b293f3ba3e) | Mar 22, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [b616377b13](https://linux-hardware.org/?probe=b616377b13) | Mar 22, 2023 |
| Lenovo        | ThinkPad X121e 3045A63      | Notebook    | [f4830d41d6](https://linux-hardware.org/?probe=f4830d41d6) | Mar 21, 2023 |
| BESSTAR Te... | UM700                       | Desktop     | [32116dbba8](https://linux-hardware.org/?probe=32116dbba8) | Mar 21, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [844b9094f9](https://linux-hardware.org/?probe=844b9094f9) | Mar 21, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [42629ad13b](https://linux-hardware.org/?probe=42629ad13b) | Mar 21, 2023 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [c7c5415a8c](https://linux-hardware.org/?probe=c7c5415a8c) | Mar 21, 2023 |
| Lenovo        | ThinkPad Edge S430 33643... | Notebook    | [f6b05c3b0b](https://linux-hardware.org/?probe=f6b05c3b0b) | Mar 21, 2023 |
| Hampoo        | Cherry Trail CR             | Notebook    | [aef19ecbd7](https://linux-hardware.org/?probe=aef19ecbd7) | Mar 21, 2023 |
| Hampoo        | Cherry Trail CR             | Notebook    | [82d9122ebf](https://linux-hardware.org/?probe=82d9122ebf) | Mar 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [3298f3c951](https://linux-hardware.org/?probe=3298f3c951) | Mar 20, 2023 |
| ASUSTek       | ZenBook 13 UX331UAL         | Notebook    | [9d44bf5769](https://linux-hardware.org/?probe=9d44bf5769) | Mar 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [192fe75be4](https://linux-hardware.org/?probe=192fe75be4) | Mar 19, 2023 |
| HP            | 8715                        | Mini pc     | [1c2c765978](https://linux-hardware.org/?probe=1c2c765978) | Mar 18, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [3b0eb35766](https://linux-hardware.org/?probe=3b0eb35766) | Mar 18, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [7743b2a5a9](https://linux-hardware.org/?probe=7743b2a5a9) | Mar 18, 2023 |
| Hampoo        | Cherry Trail CR             | Notebook    | [fcb7a079cf](https://linux-hardware.org/?probe=fcb7a079cf) | Mar 18, 2023 |
| HP            | 1495                        | Desktop     | [d83e879ba0](https://linux-hardware.org/?probe=d83e879ba0) | Mar 18, 2023 |
| HP            | 1495                        | Desktop     | [b7b5d46ce0](https://linux-hardware.org/?probe=b7b5d46ce0) | Mar 18, 2023 |
| HP            | 8715                        | Mini pc     | [cd9310c350](https://linux-hardware.org/?probe=cd9310c350) | Mar 17, 2023 |
| HP            | EliteBook 1050 G1           | Notebook    | [6dcfa134ac](https://linux-hardware.org/?probe=6dcfa134ac) | Mar 16, 2023 |
| Biostar       | A10N-8800E                  | Desktop     | [1f081ed675](https://linux-hardware.org/?probe=1f081ed675) | Mar 16, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [b78130eae1](https://linux-hardware.org/?probe=b78130eae1) | Mar 16, 2023 |
| Acer          | Aspire ES1-521              | Notebook    | [8ea6223dc5](https://linux-hardware.org/?probe=8ea6223dc5) | Mar 16, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [8f1af30bba](https://linux-hardware.org/?probe=8f1af30bba) | Mar 15, 2023 |
| HP            | 8715                        | Mini pc     | [7f9acb1f3e](https://linux-hardware.org/?probe=7f9acb1f3e) | Mar 15, 2023 |
| Valve         | Jupiter                     | Notebook    | [36eacafa6f](https://linux-hardware.org/?probe=36eacafa6f) | Mar 15, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [fb73add0f6](https://linux-hardware.org/?probe=fb73add0f6) | Mar 14, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [c4be4f7d67](https://linux-hardware.org/?probe=c4be4f7d67) | Mar 14, 2023 |
| HP            | 2B52                        | Desktop     | [b541e6085e](https://linux-hardware.org/?probe=b541e6085e) | Mar 14, 2023 |
| ASRock        | Z97E-ITX/ac                 | Desktop     | [02c6d19dfa](https://linux-hardware.org/?probe=02c6d19dfa) | Mar 14, 2023 |
| Hampoo        | Cherry Trail CR             | Notebook    | [c9936da6ba](https://linux-hardware.org/?probe=c9936da6ba) | Mar 14, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [0eefdece9c](https://linux-hardware.org/?probe=0eefdece9c) | Mar 13, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [22ae0716b2](https://linux-hardware.org/?probe=22ae0716b2) | Mar 13, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [77569b52db](https://linux-hardware.org/?probe=77569b52db) | Mar 13, 2023 |
| Lenovo        | ThinkPad X230 2325Y2S       | Notebook    | [7f15f7ce79](https://linux-hardware.org/?probe=7f15f7ce79) | Mar 12, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [3ec784f6be](https://linux-hardware.org/?probe=3ec784f6be) | Mar 11, 2023 |
| ASUSTek       | PN40                        | Mini pc     | [8c5e382d0a](https://linux-hardware.org/?probe=8c5e382d0a) | Mar 11, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b6661b1166](https://linux-hardware.org/?probe=b6661b1166) | Mar 10, 2023 |
| TUXEDO        | XMG FUSION 15 (XFU15L19)    | Notebook    | [3cde6f345c](https://linux-hardware.org/?probe=3cde6f345c) | Mar 10, 2023 |
| Samsung       | 950QDB                      | Convertible | [1ed34d5e26](https://linux-hardware.org/?probe=1ed34d5e26) | Mar 09, 2023 |
| Samsung       | 950QDB                      | Convertible | [1d1e08a117](https://linux-hardware.org/?probe=1d1e08a117) | Mar 09, 2023 |
| ASUSTek       | F2A85-V                     | Desktop     | [1470c9fc46](https://linux-hardware.org/?probe=1470c9fc46) | Mar 09, 2023 |
| MSI           | Z68MA-ED55                  | Desktop     | [17a3d0c88b](https://linux-hardware.org/?probe=17a3d0c88b) | Mar 09, 2023 |
| Intel         | NUC5i5RYB H40999-502        | Mini pc     | [7d6aa1edeb](https://linux-hardware.org/?probe=7d6aa1edeb) | Mar 08, 2023 |
| Acer          | Spin SP313-51N              | Convertible | [c1339ac8de](https://linux-hardware.org/?probe=c1339ac8de) | Mar 08, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [44c6479881](https://linux-hardware.org/?probe=44c6479881) | Mar 07, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [e2c5933515](https://linux-hardware.org/?probe=e2c5933515) | Mar 07, 2023 |
| Clevo         | P370EM                      | Notebook    | [4ac46a0dab](https://linux-hardware.org/?probe=4ac46a0dab) | Mar 07, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [a4ab100e59](https://linux-hardware.org/?probe=a4ab100e59) | Mar 07, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [b27b730e8f](https://linux-hardware.org/?probe=b27b730e8f) | Mar 06, 2023 |
| Dell          | 0F5C5X A00                  | Desktop     | [5f0ab2a253](https://linux-hardware.org/?probe=5f0ab2a253) | Mar 06, 2023 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [fc381c78e7](https://linux-hardware.org/?probe=fc381c78e7) | Mar 05, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1ac55121cf](https://linux-hardware.org/?probe=1ac55121cf) | Mar 05, 2023 |
| Acer          | Nitro N50-600 V:1.1         | Desktop     | [1e09dd1123](https://linux-hardware.org/?probe=1e09dd1123) | Mar 04, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | Notebook    | [414dc8dc29](https://linux-hardware.org/?probe=414dc8dc29) | Mar 04, 2023 |
| Lenovo        | ThinkPad X201 3680Z38       | Notebook    | [3e60e33df2](https://linux-hardware.org/?probe=3e60e33df2) | Mar 04, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [188ba8d836](https://linux-hardware.org/?probe=188ba8d836) | Mar 02, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [0ad3a8182e](https://linux-hardware.org/?probe=0ad3a8182e) | Mar 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [22c9e146ee](https://linux-hardware.org/?probe=22c9e146ee) | Mar 02, 2023 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [422fa2cf16](https://linux-hardware.org/?probe=422fa2cf16) | Mar 02, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [72b59f777e](https://linux-hardware.org/?probe=72b59f777e) | Mar 01, 2023 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [d008353c16](https://linux-hardware.org/?probe=d008353c16) | Mar 01, 2023 |
| Lenovo        | MIIX 520-12IKB 20M3         | Tablet      | [6ff1d34454](https://linux-hardware.org/?probe=6ff1d34454) | Feb 28, 2023 |
| ASRock        | G41M-S                      | Desktop     | [8802d04f08](https://linux-hardware.org/?probe=8802d04f08) | Feb 27, 2023 |
| HP            | 3397                        | Desktop     | [8081d24eb1](https://linux-hardware.org/?probe=8081d24eb1) | Feb 27, 2023 |
| Apple         | MacBookAir4,2               | Notebook    | [a9605bf85e](https://linux-hardware.org/?probe=a9605bf85e) | Feb 27, 2023 |
| MSI           | B150M PRO-VDH               | Desktop     | [e538527e6c](https://linux-hardware.org/?probe=e538527e6c) | Feb 26, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [3ab842532b](https://linux-hardware.org/?probe=3ab842532b) | Feb 26, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | Desktop     | [659ff1672e](https://linux-hardware.org/?probe=659ff1672e) | Feb 26, 2023 |
| Dell          | Latitude E7250              | Notebook    | [db6ac786ef](https://linux-hardware.org/?probe=db6ac786ef) | Feb 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [c8006c3bd5](https://linux-hardware.org/?probe=c8006c3bd5) | Feb 26, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [2943aa6cd7](https://linux-hardware.org/?probe=2943aa6cd7) | Feb 25, 2023 |
| ASRock        | H81M-HDS                    | Desktop     | [d4a6916e4f](https://linux-hardware.org/?probe=d4a6916e4f) | Feb 24, 2023 |
| Toshiba       | Satellite C70D-B            | Notebook    | [0c69e8ef9b](https://linux-hardware.org/?probe=0c69e8ef9b) | Feb 23, 2023 |
| Toshiba       | Satellite C70D-B            | Notebook    | [bcae8ff254](https://linux-hardware.org/?probe=bcae8ff254) | Feb 23, 2023 |
| Gigabyte      | H610M S2H DDR4              | Desktop     | [e44618f1c3](https://linux-hardware.org/?probe=e44618f1c3) | Feb 23, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [49007433d0](https://linux-hardware.org/?probe=49007433d0) | Feb 23, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [e67cca4a6c](https://linux-hardware.org/?probe=e67cca4a6c) | Feb 23, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [09c45a0b09](https://linux-hardware.org/?probe=09c45a0b09) | Feb 21, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [f5a22b7bb9](https://linux-hardware.org/?probe=f5a22b7bb9) | Feb 21, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [d5f5531b82](https://linux-hardware.org/?probe=d5f5531b82) | Feb 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [1f89daceb8](https://linux-hardware.org/?probe=1f89daceb8) | Feb 20, 2023 |
| HP            | Spectre x360 Convertible... | Convertible | [72b8072c9a](https://linux-hardware.org/?probe=72b8072c9a) | Feb 20, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [1263eaf1f9](https://linux-hardware.org/?probe=1263eaf1f9) | Feb 19, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [f4065623e5](https://linux-hardware.org/?probe=f4065623e5) | Feb 18, 2023 |
| Chuwi         | HeroBook Pro                | Notebook    | [f49ba07c1e](https://linux-hardware.org/?probe=f49ba07c1e) | Feb 18, 2023 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [5ecce23878](https://linux-hardware.org/?probe=5ecce23878) | Feb 18, 2023 |
| Medion        | E7220                       | Notebook    | [289b7dc6aa](https://linux-hardware.org/?probe=289b7dc6aa) | Feb 17, 2023 |
| MSI           | A78M-E35                    | Desktop     | [30c75db366](https://linux-hardware.org/?probe=30c75db366) | Feb 16, 2023 |
| Gigabyte      | GB-BSi7A-6500               | Notebook    | [9c461d33db](https://linux-hardware.org/?probe=9c461d33db) | Feb 16, 2023 |
| Medion        | E7220                       | Notebook    | [dd9de8bf69](https://linux-hardware.org/?probe=dd9de8bf69) | Feb 15, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y3S... | Notebook    | [580215c6bb](https://linux-hardware.org/?probe=580215c6bb) | Feb 15, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Notebook    | [ca4349a929](https://linux-hardware.org/?probe=ca4349a929) | Feb 15, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [d2d359be39](https://linux-hardware.org/?probe=d2d359be39) | Feb 14, 2023 |
| Apple         | MacBook5,2                  | Notebook    | [72b8d495ff](https://linux-hardware.org/?probe=72b8d495ff) | Feb 13, 2023 |
| Acer          | Aspire 7740                 | Notebook    | [caeb61e835](https://linux-hardware.org/?probe=caeb61e835) | Feb 12, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [78e7a0ae85](https://linux-hardware.org/?probe=78e7a0ae85) | Feb 12, 2023 |
| Unknown       | Unknown                     | Desktop     | [f2f95aef80](https://linux-hardware.org/?probe=f2f95aef80) | Feb 12, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [632c139c4b](https://linux-hardware.org/?probe=632c139c4b) | Feb 12, 2023 |
| ASUSTek       | P8H77-I                     | Desktop     | [74013e0688](https://linux-hardware.org/?probe=74013e0688) | Feb 11, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502FBA... | Convertible | [dd34aed5d9](https://linux-hardware.org/?probe=dd34aed5d9) | Feb 11, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [b7e924b0cd](https://linux-hardware.org/?probe=b7e924b0cd) | Feb 11, 2023 |
| Lenovo        | ThinkPad T450 20BUS1110E    | Notebook    | [d08c46c46d](https://linux-hardware.org/?probe=d08c46c46d) | Feb 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [3f4b71a601](https://linux-hardware.org/?probe=3f4b71a601) | Feb 09, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [7f27fb0a83](https://linux-hardware.org/?probe=7f27fb0a83) | Feb 09, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [82173d3b08](https://linux-hardware.org/?probe=82173d3b08) | Feb 09, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [10cf328828](https://linux-hardware.org/?probe=10cf328828) | Feb 06, 2023 |
| ASUSTek       | P8P67 WS REVOLUTION         | Desktop     | [c0190f8f57](https://linux-hardware.org/?probe=c0190f8f57) | Feb 06, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [a57b142e05](https://linux-hardware.org/?probe=a57b142e05) | Feb 06, 2023 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [7ca566f68b](https://linux-hardware.org/?probe=7ca566f68b) | Feb 05, 2023 |
| Dell          | Inspiron 7586               | Convertible | [732b3c8fb1](https://linux-hardware.org/?probe=732b3c8fb1) | Feb 05, 2023 |
| Apple         | MacBookPro11,5              | Notebook    | [3407774ba7](https://linux-hardware.org/?probe=3407774ba7) | Feb 05, 2023 |
| HP            | 0A98h                       | Desktop     | [1d3ae20ff5](https://linux-hardware.org/?probe=1d3ae20ff5) | Feb 04, 2023 |
| Dell          | MXG061                      | Notebook    | [40883298a9](https://linux-hardware.org/?probe=40883298a9) | Feb 04, 2023 |
| Dell          | 0D28YY A03                  | Desktop     | [ae7eeb7487](https://linux-hardware.org/?probe=ae7eeb7487) | Feb 04, 2023 |
| Dell          | 0D28YY A03                  | Desktop     | [0fe32fbdc2](https://linux-hardware.org/?probe=0fe32fbdc2) | Feb 04, 2023 |
| ASUSTek       | PN50-E1                     | Mini pc     | [063a4bb843](https://linux-hardware.org/?probe=063a4bb843) | Feb 03, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [82845bb849](https://linux-hardware.org/?probe=82845bb849) | Feb 02, 2023 |
| MSI           | GF63 Thin 11UC              | Notebook    | [b34b3228d3](https://linux-hardware.org/?probe=b34b3228d3) | Feb 01, 2023 |
| ASUSTek       | F2A85-V                     | Desktop     | [c68678a1a5](https://linux-hardware.org/?probe=c68678a1a5) | Jan 31, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [a57a68e42f](https://linux-hardware.org/?probe=a57a68e42f) | Jan 31, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [0d500d9d33](https://linux-hardware.org/?probe=0d500d9d33) | Jan 31, 2023 |
| Dell          | Latitude 5480               | Notebook    | [8b43efc7ea](https://linux-hardware.org/?probe=8b43efc7ea) | Jan 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [f2a2476d45](https://linux-hardware.org/?probe=f2a2476d45) | Jan 31, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [78d987fedf](https://linux-hardware.org/?probe=78d987fedf) | Jan 30, 2023 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [a178301183](https://linux-hardware.org/?probe=a178301183) | Jan 30, 2023 |
| Fujitsu       | D3183-A1 S26361-D3183-A1    | Desktop     | [bfb86ee660](https://linux-hardware.org/?probe=bfb86ee660) | Jan 29, 2023 |
| ASUSTek       | G750JX                      | Notebook    | [d868c23c4b](https://linux-hardware.org/?probe=d868c23c4b) | Jan 29, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [32d5472e21](https://linux-hardware.org/?probe=32d5472e21) | Jan 29, 2023 |
| ASUSTek       | F2A85-V                     | Desktop     | [d528677cfd](https://linux-hardware.org/?probe=d528677cfd) | Jan 28, 2023 |
| HP            | 1495                        | Desktop     | [8c1f7b5fbd](https://linux-hardware.org/?probe=8c1f7b5fbd) | Jan 27, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [c5168e6b33](https://linux-hardware.org/?probe=c5168e6b33) | Jan 27, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [4ecf66ddd9](https://linux-hardware.org/?probe=4ecf66ddd9) | Jan 27, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [4024f7c3bd](https://linux-hardware.org/?probe=4024f7c3bd) | Jan 26, 2023 |
| Gigabyte      | GA-990FXA-UD3               | Desktop     | [6e5884ec0c](https://linux-hardware.org/?probe=6e5884ec0c) | Jan 26, 2023 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [ea142e4848](https://linux-hardware.org/?probe=ea142e4848) | Jan 25, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [5973888b27](https://linux-hardware.org/?probe=5973888b27) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [be73748546](https://linux-hardware.org/?probe=be73748546) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [7595deef91](https://linux-hardware.org/?probe=7595deef91) | Jan 24, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [e9c7c42a8b](https://linux-hardware.org/?probe=e9c7c42a8b) | Jan 22, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [9035a00600](https://linux-hardware.org/?probe=9035a00600) | Jan 22, 2023 |
| Toshiba       | Satellite Pro C660          | Notebook    | [f1c0237cc0](https://linux-hardware.org/?probe=f1c0237cc0) | Jan 22, 2023 |
| Foxconn       | NETBOX NT-425/525 Ver       | Desktop     | [dfb8c476f9](https://linux-hardware.org/?probe=dfb8c476f9) | Jan 21, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [2b5b2da951](https://linux-hardware.org/?probe=2b5b2da951) | Jan 20, 2023 |
| Lenovo        | ThinkPad X230 2333AZ2       | Notebook    | [d9d0138294](https://linux-hardware.org/?probe=d9d0138294) | Jan 19, 2023 |
| ASUSTek       | A6U                         | Notebook    | [58c040d67c](https://linux-hardware.org/?probe=58c040d67c) | Jan 19, 2023 |
| ASUSTek       | A6U                         | Notebook    | [9156e1c9cd](https://linux-hardware.org/?probe=9156e1c9cd) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [eddf4927eb](https://linux-hardware.org/?probe=eddf4927eb) | Jan 19, 2023 |
| MSI           | VR630                       | Notebook    | [943c1d68fa](https://linux-hardware.org/?probe=943c1d68fa) | Jan 19, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [a5cbba39d7](https://linux-hardware.org/?probe=a5cbba39d7) | Jan 19, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [4197c5f3d3](https://linux-hardware.org/?probe=4197c5f3d3) | Jan 19, 2023 |
| ASUSTek       | K53TA                       | Notebook    | [a56a3691e9](https://linux-hardware.org/?probe=a56a3691e9) | Jan 18, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [c99128e783](https://linux-hardware.org/?probe=c99128e783) | Jan 16, 2023 |
| Lenovo        | ThinkPad W510 43892AG       | Notebook    | [b68853abf6](https://linux-hardware.org/?probe=b68853abf6) | Jan 16, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [a159136180](https://linux-hardware.org/?probe=a159136180) | Jan 16, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [6f3b4fc131](https://linux-hardware.org/?probe=6f3b4fc131) | Jan 16, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [b33bedc4c2](https://linux-hardware.org/?probe=b33bedc4c2) | Jan 15, 2023 |
| Lenovo        | IdeaPad 3 17ITL6 82H9       | Notebook    | [80f9124e5a](https://linux-hardware.org/?probe=80f9124e5a) | Jan 14, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [81d232a246](https://linux-hardware.org/?probe=81d232a246) | Jan 14, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [ba09b2045b](https://linux-hardware.org/?probe=ba09b2045b) | Jan 13, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [5721ffbc43](https://linux-hardware.org/?probe=5721ffbc43) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [c3a30838c3](https://linux-hardware.org/?probe=c3a30838c3) | Jan 13, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [64c403ce6d](https://linux-hardware.org/?probe=64c403ce6d) | Jan 13, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [806da9b386](https://linux-hardware.org/?probe=806da9b386) | Jan 12, 2023 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [29e6fcfd32](https://linux-hardware.org/?probe=29e6fcfd32) | Jan 12, 2023 |
| Dell          | Latitude E5550              | Notebook    | [0b14eb18d9](https://linux-hardware.org/?probe=0b14eb18d9) | Jan 12, 2023 |
| Medion        | E6222                       | Notebook    | [e3b3da28fa](https://linux-hardware.org/?probe=e3b3da28fa) | Jan 11, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e608d09ac5](https://linux-hardware.org/?probe=e608d09ac5) | Jan 11, 2023 |
| Dell          | Latitude E5550              | Notebook    | [5e76d378f9](https://linux-hardware.org/?probe=5e76d378f9) | Jan 11, 2023 |
| ASUSTek       | F2A85-V                     | Desktop     | [0ddddc438d](https://linux-hardware.org/?probe=0ddddc438d) | Jan 11, 2023 |
| HP            | 8906 SMVB                   | Desktop     | [7d56f2f733](https://linux-hardware.org/?probe=7d56f2f733) | Jan 11, 2023 |
| Dell          | Latitude E7440              | Notebook    | [bfdc9dfc63](https://linux-hardware.org/?probe=bfdc9dfc63) | Jan 11, 2023 |
| ASUSTek       | Z170-A                      | Desktop     | [0f0b38970a](https://linux-hardware.org/?probe=0f0b38970a) | Jan 11, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [b2d69bd762](https://linux-hardware.org/?probe=b2d69bd762) | Jan 11, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [d8ab62070c](https://linux-hardware.org/?probe=d8ab62070c) | Jan 11, 2023 |
| Intel         | NUC8BEB J72688-307          | Mini pc     | [3e54ca06f5](https://linux-hardware.org/?probe=3e54ca06f5) | Jan 10, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [fbde9a1dba](https://linux-hardware.org/?probe=fbde9a1dba) | Jan 10, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [a365222a35](https://linux-hardware.org/?probe=a365222a35) | Jan 09, 2023 |
| MSI           | GS63VR 7RF                  | Notebook    | [95aadb3cc4](https://linux-hardware.org/?probe=95aadb3cc4) | Jan 09, 2023 |
| Sony          | SVE1512H1EB                 | Notebook    | [723e8bfbe6](https://linux-hardware.org/?probe=723e8bfbe6) | Jan 09, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [297380c89a](https://linux-hardware.org/?probe=297380c89a) | Jan 09, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [919b259ea2](https://linux-hardware.org/?probe=919b259ea2) | Jan 09, 2023 |
| Acer          | Iconia W700                 | Notebook    | [bcfec36896](https://linux-hardware.org/?probe=bcfec36896) | Jan 09, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [d67718b4e8](https://linux-hardware.org/?probe=d67718b4e8) | Jan 08, 2023 |
| Google        | Kled                        | Notebook    | [3cb98a4497](https://linux-hardware.org/?probe=3cb98a4497) | Jan 07, 2023 |
| Lenovo        | ThinkPad X220 4290KJ6       | Notebook    | [8296e61afd](https://linux-hardware.org/?probe=8296e61afd) | Jan 05, 2023 |
| Sony          | VPCEH2D0E                   | Notebook    | [78367f11f5](https://linux-hardware.org/?probe=78367f11f5) | Jan 04, 2023 |
| Gigabyte      | Z690 UD AX                  | Desktop     | [e6ee0cd764](https://linux-hardware.org/?probe=e6ee0cd764) | Jan 04, 2023 |
| ASUSTek       | K93SM                       | Notebook    | [c0fb78e9a3](https://linux-hardware.org/?probe=c0fb78e9a3) | Jan 03, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Desktop     | [b1771ee07c](https://linux-hardware.org/?probe=b1771ee07c) | Jan 03, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [a35156e0c3](https://linux-hardware.org/?probe=a35156e0c3) | Jan 02, 2023 |
| ASUSTek       | P7P55D-E                    | Desktop     | [8f4f98da64](https://linux-hardware.org/?probe=8f4f98da64) | Jan 02, 2023 |
| ASUSTek       | PRIME B350M-E               | Desktop     | [f39e3e8350](https://linux-hardware.org/?probe=f39e3e8350) | Jan 02, 2023 |
| Dell          | Latitude 7430               | Notebook    | [ad796336f7](https://linux-hardware.org/?probe=ad796336f7) | Jan 01, 2023 |
| Lenovo        | ThinkPad X270 20K60018GE    | Notebook    | [a92939c1f5](https://linux-hardware.org/?probe=a92939c1f5) | Jan 01, 2023 |
| Lenovo        | ThinkPad X390 20Q00051GE    | Notebook    | [5b3d1b750d](https://linux-hardware.org/?probe=5b3d1b750d) | Dec 31, 2022 |
| Lenovo        | ThinkPad X390 20Q00051GE    | Notebook    | [775096be09](https://linux-hardware.org/?probe=775096be09) | Dec 31, 2022 |
| Chuwi         | HeroBook Pro                | Notebook    | [cdc31b8338](https://linux-hardware.org/?probe=cdc31b8338) | Dec 30, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [de6ea0ae2e](https://linux-hardware.org/?probe=de6ea0ae2e) | Dec 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [c28fb2edb2](https://linux-hardware.org/?probe=c28fb2edb2) | Dec 30, 2022 |
| ASUSTek       | P7P55D-E                    | Desktop     | [f725a0095a](https://linux-hardware.org/?probe=f725a0095a) | Dec 30, 2022 |
| Supermicro    | H8SCM                       | Server      | [9ee42dcf6f](https://linux-hardware.org/?probe=9ee42dcf6f) | Dec 29, 2022 |
| Intel         | NUC10i7FNB K61360-306       | Mini pc     | [6e3a112190](https://linux-hardware.org/?probe=6e3a112190) | Dec 28, 2022 |
| Gigabyte      | Z590 AORUS PRO AX           | Desktop     | [d680b8dd2a](https://linux-hardware.org/?probe=d680b8dd2a) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | Desktop     | [e8dce940d8](https://linux-hardware.org/?probe=e8dce940d8) | Dec 26, 2022 |
| Medion        | X782X/X783X                 | Notebook    | [a8befc040f](https://linux-hardware.org/?probe=a8befc040f) | Dec 26, 2022 |
| Matrox Ele... | 4GPMOBIL 7449-03-0          | Desktop     | [c02a37a124](https://linux-hardware.org/?probe=c02a37a124) | Dec 26, 2022 |
| ASUSTek       | P7P55D-E                    | Desktop     | [a6be229477](https://linux-hardware.org/?probe=a6be229477) | Dec 24, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e3e2773bde](https://linux-hardware.org/?probe=e3e2773bde) | Dec 24, 2022 |
| Notebook      | P64_HJ,HK1                  | Notebook    | [26a548a6f3](https://linux-hardware.org/?probe=26a548a6f3) | Dec 23, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [431eac7d11](https://linux-hardware.org/?probe=431eac7d11) | Dec 22, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | Notebook    | [b934598049](https://linux-hardware.org/?probe=b934598049) | Dec 22, 2022 |
| Lenovo        | ThinkPad T490 20N20048GE    | Notebook    | [629a725afa](https://linux-hardware.org/?probe=629a725afa) | Dec 21, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [aeb826326b](https://linux-hardware.org/?probe=aeb826326b) | Dec 20, 2022 |
| Acer          | Aspire A715-72G             | Notebook    | [8e15fef839](https://linux-hardware.org/?probe=8e15fef839) | Dec 19, 2022 |
| MSI           | GE63 Raider RGB 8RF         | Notebook    | [a85193c482](https://linux-hardware.org/?probe=a85193c482) | Dec 19, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [74207a9fec](https://linux-hardware.org/?probe=74207a9fec) | Dec 19, 2022 |
| Google        | Cyan                        | Notebook    | [fff3502929](https://linux-hardware.org/?probe=fff3502929) | Dec 19, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [88d7491a00](https://linux-hardware.org/?probe=88d7491a00) | Dec 19, 2022 |
| AXDIA Inte... | myBook PRO14 SE V2          | Notebook    | [14b79d7a8b](https://linux-hardware.org/?probe=14b79d7a8b) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [86c9426d80](https://linux-hardware.org/?probe=86c9426d80) | Dec 18, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [05fcf7302f](https://linux-hardware.org/?probe=05fcf7302f) | Dec 18, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [fa03fe621a](https://linux-hardware.org/?probe=fa03fe621a) | Dec 17, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [8480834751](https://linux-hardware.org/?probe=8480834751) | Dec 17, 2022 |
| Lenovo        | ThinkPad A485 20MVS0LG00    | Notebook    | [12b3654541](https://linux-hardware.org/?probe=12b3654541) | Dec 15, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [ffe85423d8](https://linux-hardware.org/?probe=ffe85423d8) | Dec 15, 2022 |
| HP            | EliteBook 850 G2            | Notebook    | [d0d30cd96f](https://linux-hardware.org/?probe=d0d30cd96f) | Dec 14, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [943bcd1d12](https://linux-hardware.org/?probe=943bcd1d12) | Dec 14, 2022 |
| ASRock        | X670E PG Lightning          | Desktop     | [08e4e03d36](https://linux-hardware.org/?probe=08e4e03d36) | Dec 13, 2022 |
| ASRock        | X670E PG Lightning          | Desktop     | [3a6a347ff9](https://linux-hardware.org/?probe=3a6a347ff9) | Dec 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [9b02acceb3](https://linux-hardware.org/?probe=9b02acceb3) | Dec 12, 2022 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | Desktop     | [fd77b80943](https://linux-hardware.org/?probe=fd77b80943) | Dec 12, 2022 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [37267c6b3f](https://linux-hardware.org/?probe=37267c6b3f) | Dec 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [b518609312](https://linux-hardware.org/?probe=b518609312) | Dec 12, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [f815a2e4a3](https://linux-hardware.org/?probe=f815a2e4a3) | Dec 12, 2022 |
| MSI           | GE63 Raider RGB 8RF         | Notebook    | [b311865418](https://linux-hardware.org/?probe=b311865418) | Dec 12, 2022 |
| HUAWEI        | RLEF-XX                     | Notebook    | [e0b1d50b7c](https://linux-hardware.org/?probe=e0b1d50b7c) | Dec 11, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [cc2d9043d9](https://linux-hardware.org/?probe=cc2d9043d9) | Dec 11, 2022 |
| Lenovo        | ThinkPad T470s 20HF005QM... | Notebook    | [32ce05790e](https://linux-hardware.org/?probe=32ce05790e) | Dec 11, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [13434876df](https://linux-hardware.org/?probe=13434876df) | Dec 11, 2022 |
| Medion        | H81H3-EM2 H81EM2W08.309     | Desktop     | [f6341e7afb](https://linux-hardware.org/?probe=f6341e7afb) | Dec 10, 2022 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | Notebook    | [50e5b72a10](https://linux-hardware.org/?probe=50e5b72a10) | Dec 10, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [8f38dcc9d4](https://linux-hardware.org/?probe=8f38dcc9d4) | Dec 10, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [7ae8aecc25](https://linux-hardware.org/?probe=7ae8aecc25) | Dec 08, 2022 |
| Lenovo        | ThinkPad L14 Gen 2a 20X6... | Notebook    | [b7171256c0](https://linux-hardware.org/?probe=b7171256c0) | Dec 07, 2022 |
| Lenovo        | ThinkStation S20 4157DT6    | Desktop     | [7c45cf5115](https://linux-hardware.org/?probe=7c45cf5115) | Dec 07, 2022 |
| Packard Be... | EasyNote TS11HR             | Notebook    | [cd166beede](https://linux-hardware.org/?probe=cd166beede) | Dec 06, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [8d5d04f931](https://linux-hardware.org/?probe=8d5d04f931) | Dec 05, 2022 |
| Lenovo        | G700 20251                  | Notebook    | [4e8f04ce8f](https://linux-hardware.org/?probe=4e8f04ce8f) | Dec 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [2b34016cad](https://linux-hardware.org/?probe=2b34016cad) | Dec 04, 2022 |
| Acer          | Aspire A514-53              | Notebook    | [f0c20f1a0a](https://linux-hardware.org/?probe=f0c20f1a0a) | Dec 04, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [05131558b5](https://linux-hardware.org/?probe=05131558b5) | Dec 03, 2022 |
| ASUSTek       | P8H67-M PRO                 | Desktop     | [9fcc18738b](https://linux-hardware.org/?probe=9fcc18738b) | Dec 03, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [027cd08fb1](https://linux-hardware.org/?probe=027cd08fb1) | Dec 03, 2022 |
| Toshiba       | Satellite C50-A-1HF         | Notebook    | [74902de02b](https://linux-hardware.org/?probe=74902de02b) | Dec 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII FORMU... | Desktop     | [790ae8be94](https://linux-hardware.org/?probe=790ae8be94) | Dec 02, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [4f36906529](https://linux-hardware.org/?probe=4f36906529) | Dec 02, 2022 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [373dac5bbb](https://linux-hardware.org/?probe=373dac5bbb) | Dec 02, 2022 |
| Intel         | NUC10i5FNB K61361-303       | Mini pc     | [d9bba42204](https://linux-hardware.org/?probe=d9bba42204) | Dec 02, 2022 |
| Apple         | MacBookPro14,1              | Notebook    | [eb13a8db03](https://linux-hardware.org/?probe=eb13a8db03) | Dec 02, 2022 |
| Acer          | Aspire A514-53              | Notebook    | [07ff06f360](https://linux-hardware.org/?probe=07ff06f360) | Dec 02, 2022 |
| ASUSTek       | H110M-A                     | Desktop     | [d7694493c0](https://linux-hardware.org/?probe=d7694493c0) | Dec 02, 2022 |
| ASRock        | H110M-DVS R3.0              | Desktop     | [01dfdc071e](https://linux-hardware.org/?probe=01dfdc071e) | Dec 01, 2022 |
| Medion        | H81H3-EM2 H81EM2W08.309     | Desktop     | [9aa4880856](https://linux-hardware.org/?probe=9aa4880856) | Dec 01, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e03c6b53ed](https://linux-hardware.org/?probe=e03c6b53ed) | Dec 01, 2022 |
| Medion        | H81H3-EM2 H81EM2W08.309     | Desktop     | [c1f5a1f413](https://linux-hardware.org/?probe=c1f5a1f413) | Dec 01, 2022 |
| HP            | Stream Laptop 11-ak0xxx     | Notebook    | [d2c04dd7cd](https://linux-hardware.org/?probe=d2c04dd7cd) | Dec 01, 2022 |
| W271ELQ       | Unknown                     | Notebook    | [ae170d1e81](https://linux-hardware.org/?probe=ae170d1e81) | Dec 01, 2022 |
| Gigabyte      | Z97X-SLI-CF                 | Desktop     | [ae01075720](https://linux-hardware.org/?probe=ae01075720) | Nov 28, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [ceb78dbe4e](https://linux-hardware.org/?probe=ceb78dbe4e) | Nov 28, 2022 |
| Lenovo        | ThinkPad T520 4243F53       | Notebook    | [8f9e96442a](https://linux-hardware.org/?probe=8f9e96442a) | Nov 27, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [ee234d62ec](https://linux-hardware.org/?probe=ee234d62ec) | Nov 27, 2022 |
| Acer          | Aspire E5-571G              | Notebook    | [7d6eeaf95c](https://linux-hardware.org/?probe=7d6eeaf95c) | Nov 26, 2022 |
| Dell          | Latitude 3520               | Notebook    | [896180c55d](https://linux-hardware.org/?probe=896180c55d) | Nov 25, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [6646978243](https://linux-hardware.org/?probe=6646978243) | Nov 23, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [ddcb37ea55](https://linux-hardware.org/?probe=ddcb37ea55) | Nov 23, 2022 |
| Gigabyte      | Z270-HD3P-CF                | Desktop     | [6d3657ecde](https://linux-hardware.org/?probe=6d3657ecde) | Nov 23, 2022 |
| Dell          | Precision 5560              | Notebook    | [f20218fb35](https://linux-hardware.org/?probe=f20218fb35) | Nov 23, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [fc53a66047](https://linux-hardware.org/?probe=fc53a66047) | Nov 22, 2022 |
| TUXEDO        | N7x0WU                      | Notebook    | [614f59ceaf](https://linux-hardware.org/?probe=614f59ceaf) | Nov 22, 2022 |
| Gigabyte      | Z590 UD AC                  | Desktop     | [4fc70b9ddc](https://linux-hardware.org/?probe=4fc70b9ddc) | Nov 21, 2022 |
| Lenovo        | ThinkPad L15 Gen 2a 20X7... | Notebook    | [dc848e747b](https://linux-hardware.org/?probe=dc848e747b) | Nov 21, 2022 |
| Microsoft     | Surface Laptop              | Tablet      | [b6697363ea](https://linux-hardware.org/?probe=b6697363ea) | Nov 20, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [8c271e833d](https://linux-hardware.org/?probe=8c271e833d) | Nov 20, 2022 |
| ASUSTek       | Zenbook UM6702RA_RM6702R... | Notebook    | [4ea8f7dbb0](https://linux-hardware.org/?probe=4ea8f7dbb0) | Nov 19, 2022 |
| Valve         | Jupiter                     | Notebook    | [5932954a14](https://linux-hardware.org/?probe=5932954a14) | Nov 19, 2022 |
| Acer          | FMP55                       | Desktop     | [f35d63ca8b](https://linux-hardware.org/?probe=f35d63ca8b) | Nov 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [93ad560f52](https://linux-hardware.org/?probe=93ad560f52) | Nov 17, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [478fa166bd](https://linux-hardware.org/?probe=478fa166bd) | Nov 17, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c8c74ea1ec](https://linux-hardware.org/?probe=c8c74ea1ec) | Nov 15, 2022 |
| Dell          | Latitude E6220              | Notebook    | [b1270460e6](https://linux-hardware.org/?probe=b1270460e6) | Nov 15, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [d6b19cfd9d](https://linux-hardware.org/?probe=d6b19cfd9d) | Nov 15, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [a83e2b1a92](https://linux-hardware.org/?probe=a83e2b1a92) | Nov 13, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [d4240ae5c7](https://linux-hardware.org/?probe=d4240ae5c7) | Nov 12, 2022 |
| Lenovo        | ThinkPad S1 Yoga 20CD003... | Notebook    | [4406929fb6](https://linux-hardware.org/?probe=4406929fb6) | Nov 11, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [695b0b0356](https://linux-hardware.org/?probe=695b0b0356) | Nov 11, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | Notebook    | [24c5edc9f9](https://linux-hardware.org/?probe=24c5edc9f9) | Nov 10, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [9c6a00b034](https://linux-hardware.org/?probe=9c6a00b034) | Nov 09, 2022 |
| ASUSTek       | VM40B                       | Desktop     | [5736f2e2ae](https://linux-hardware.org/?probe=5736f2e2ae) | Nov 08, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [2670a536f0](https://linux-hardware.org/?probe=2670a536f0) | Nov 08, 2022 |
| Medion        | MS-7797                     | Desktop     | [41ba0c8fdc](https://linux-hardware.org/?probe=41ba0c8fdc) | Nov 08, 2022 |
| ASUSTek       | X55A                        | Notebook    | [6391006e3d](https://linux-hardware.org/?probe=6391006e3d) | Nov 07, 2022 |
| ASUSTek       | X55A                        | Notebook    | [ae4277aa87](https://linux-hardware.org/?probe=ae4277aa87) | Nov 07, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1a0fbb4d0d](https://linux-hardware.org/?probe=1a0fbb4d0d) | Nov 06, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | Notebook    | [4c47d0ef97](https://linux-hardware.org/?probe=4c47d0ef97) | Nov 05, 2022 |
| Olimex        | A20-Olinuxino Micro         | Soc         | [82674b87bb](https://linux-hardware.org/?probe=82674b87bb) | Nov 03, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [7007ab7df6](https://linux-hardware.org/?probe=7007ab7df6) | Nov 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [18b0671002](https://linux-hardware.org/?probe=18b0671002) | Nov 03, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [565ad502cc](https://linux-hardware.org/?probe=565ad502cc) | Nov 02, 2022 |
| HP            | ProLiant DL380p Gen8        | Server      | [9d0e85aed7](https://linux-hardware.org/?probe=9d0e85aed7) | Nov 01, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [05eeb9e341](https://linux-hardware.org/?probe=05eeb9e341) | Nov 01, 2022 |
| ASUSTek       | K54L                        | Notebook    | [200f6044c2](https://linux-hardware.org/?probe=200f6044c2) | Oct 31, 2022 |
| Adlinktech    | SB-MLC                      | Notebook    | [203d95e012](https://linux-hardware.org/?probe=203d95e012) | Oct 31, 2022 |
| Dell          | Latitude E6400              | Notebook    | [8f2639b285](https://linux-hardware.org/?probe=8f2639b285) | Oct 31, 2022 |
| Lenovo        | ThinkPad T510 4384WKU       | Notebook    | [86fee6e260](https://linux-hardware.org/?probe=86fee6e260) | Oct 30, 2022 |
| Dell          | Studio 1737                 | Notebook    | [97f398804e](https://linux-hardware.org/?probe=97f398804e) | Oct 29, 2022 |
| Dell          | 0NW6H5 A00                  | Desktop     | [d768cd4c66](https://linux-hardware.org/?probe=d768cd4c66) | Oct 29, 2022 |
| HP            | EliteBook 820 G4            | Notebook    | [c41402e832](https://linux-hardware.org/?probe=c41402e832) | Oct 29, 2022 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | Notebook    | [c079764998](https://linux-hardware.org/?probe=c079764998) | Oct 28, 2022 |
| Lenovo        | IdeaPad 500-15ACZ 80K4      | Notebook    | [5ef9b4213f](https://linux-hardware.org/?probe=5ef9b4213f) | Oct 28, 2022 |
| Raspberry ... | Raspberry Pi                | Soc         | [c9cd061f05](https://linux-hardware.org/?probe=c9cd061f05) | Oct 28, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [2f6e4235f7](https://linux-hardware.org/?probe=2f6e4235f7) | Oct 28, 2022 |
| ASUSTek       | UX303LAB                    | Notebook    | [5748274da1](https://linux-hardware.org/?probe=5748274da1) | Oct 27, 2022 |
| Dell          | Precision 7530              | Notebook    | [daee9e9524](https://linux-hardware.org/?probe=daee9e9524) | Oct 26, 2022 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [a943d9879c](https://linux-hardware.org/?probe=a943d9879c) | Oct 26, 2022 |
| ASUSTek       | Z87-A                       | Desktop     | [0b4711df41](https://linux-hardware.org/?probe=0b4711df41) | Oct 26, 2022 |
| ASUSTek       | UX303LAB                    | Notebook    | [622aa11277](https://linux-hardware.org/?probe=622aa11277) | Oct 26, 2022 |
| MSI           | H81M-P33                    | Desktop     | [b0f36ae0c5](https://linux-hardware.org/?probe=b0f36ae0c5) | Oct 25, 2022 |
| Lenovo        | ThinkPad P1 20MD000NGE      | Notebook    | [561f09ba0f](https://linux-hardware.org/?probe=561f09ba0f) | Oct 25, 2022 |
| ASUSTek       | P5QL-E                      | Desktop     | [41810c587a](https://linux-hardware.org/?probe=41810c587a) | Oct 24, 2022 |
| MSI           | Z68MA-G45                   | Desktop     | [3f398756eb](https://linux-hardware.org/?probe=3f398756eb) | Oct 23, 2022 |
| MSI           | Z68MA-G45                   | Desktop     | [d96627943d](https://linux-hardware.org/?probe=d96627943d) | Oct 23, 2022 |
| Lenovo        | ThinkPad T410s 2912AJ7      | Notebook    | [efb2913d22](https://linux-hardware.org/?probe=efb2913d22) | Oct 23, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [e59cef718b](https://linux-hardware.org/?probe=e59cef718b) | Oct 23, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [5b61c1c241](https://linux-hardware.org/?probe=5b61c1c241) | Oct 23, 2022 |
| ASUSTek       | A88X-PLUS                   | Desktop     | [7435d326b7](https://linux-hardware.org/?probe=7435d326b7) | Oct 23, 2022 |
| Unknown       | Unknown                     | Desktop     | [dcb8b694a7](https://linux-hardware.org/?probe=dcb8b694a7) | Oct 23, 2022 |
| Gigabyte      | H87-HD3                     | Desktop     | [bdd6e6d3a5](https://linux-hardware.org/?probe=bdd6e6d3a5) | Oct 23, 2022 |
| Lenovo        | ThinkPad Edge S430 33643... | Notebook    | [a73e4a9246](https://linux-hardware.org/?probe=a73e4a9246) | Oct 23, 2022 |
| Valve         | Jupiter                     | Notebook    | [b05efe341f](https://linux-hardware.org/?probe=b05efe341f) | Oct 22, 2022 |
| Lenovo        | ThinkPad L580 20LW0010GE    | Notebook    | [99da3e6f09](https://linux-hardware.org/?probe=99da3e6f09) | Oct 22, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [eb651764eb](https://linux-hardware.org/?probe=eb651764eb) | Oct 22, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [80032ce2ea](https://linux-hardware.org/?probe=80032ce2ea) | Oct 22, 2022 |
| MSI           | H81M-P33                    | Desktop     | [efbd4959b8](https://linux-hardware.org/?probe=efbd4959b8) | Oct 21, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [1ce3fc664e](https://linux-hardware.org/?probe=1ce3fc664e) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [06328b7f7c](https://linux-hardware.org/?probe=06328b7f7c) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7d35a56915](https://linux-hardware.org/?probe=7d35a56915) | Oct 20, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [285e78cfbe](https://linux-hardware.org/?probe=285e78cfbe) | Oct 19, 2022 |
| Dell          | Latitude 5520               | Notebook    | [fc014585a8](https://linux-hardware.org/?probe=fc014585a8) | Oct 19, 2022 |
| Dell          | Latitude 5520               | Notebook    | [3589f77c74](https://linux-hardware.org/?probe=3589f77c74) | Oct 19, 2022 |
| Lenovo        | ThinkPad T15g Gen 1 20US... | Notebook    | [ec42bc932e](https://linux-hardware.org/?probe=ec42bc932e) | Oct 18, 2022 |
| Dell          | Precision 5510              | Notebook    | [d56d0aceaf](https://linux-hardware.org/?probe=d56d0aceaf) | Oct 18, 2022 |
| Lenovo        | ThinkPad T410s 2912AJ7      | Notebook    | [8c97c331b9](https://linux-hardware.org/?probe=8c97c331b9) | Oct 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [76f9929a9c](https://linux-hardware.org/?probe=76f9929a9c) | Oct 17, 2022 |
| Dell          | Latitude 3520               | Notebook    | [f556b42181](https://linux-hardware.org/?probe=f556b42181) | Oct 16, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [59ecc7da84](https://linux-hardware.org/?probe=59ecc7da84) | Oct 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | Notebook    | [766f4b2d1f](https://linux-hardware.org/?probe=766f4b2d1f) | Oct 14, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BS... | Notebook    | [bf46cd0c9e](https://linux-hardware.org/?probe=bf46cd0c9e) | Oct 14, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [bc23ce28e0](https://linux-hardware.org/?probe=bc23ce28e0) | Oct 14, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [8dc5e6f530](https://linux-hardware.org/?probe=8dc5e6f530) | Oct 14, 2022 |
| Dell          | Inspiron 3505               | Notebook    | [04147466b3](https://linux-hardware.org/?probe=04147466b3) | Oct 13, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [dc990d0395](https://linux-hardware.org/?probe=dc990d0395) | Oct 12, 2022 |
| Dell          | Latitude E6440              | Notebook    | [3b13c28e46](https://linux-hardware.org/?probe=3b13c28e46) | Oct 12, 2022 |
| HP            | Spectre x360 Convertible    | Convertible | [073deeb58c](https://linux-hardware.org/?probe=073deeb58c) | Oct 11, 2022 |
| Dell          | Latitude E6540              | Notebook    | [d1b0bd16b5](https://linux-hardware.org/?probe=d1b0bd16b5) | Oct 11, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [da36ee9925](https://linux-hardware.org/?probe=da36ee9925) | Oct 11, 2022 |
| ASUSTek       | PRIME H410I-PLUS            | Desktop     | [10709dd95e](https://linux-hardware.org/?probe=10709dd95e) | Oct 10, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [e860301211](https://linux-hardware.org/?probe=e860301211) | Oct 09, 2022 |
| Valve         | Jupiter                     | Notebook    | [eb5a512250](https://linux-hardware.org/?probe=eb5a512250) | Oct 09, 2022 |
| Dell          | 0MN1TX A01                  | Desktop     | [a9faf44fe8](https://linux-hardware.org/?probe=a9faf44fe8) | Oct 07, 2022 |
| MSI           | Modern 14 B11M              | Notebook    | [e0391b5084](https://linux-hardware.org/?probe=e0391b5084) | Oct 05, 2022 |
| HP            | ProBook 450 G3              | Notebook    | [16b58b369a](https://linux-hardware.org/?probe=16b58b369a) | Oct 05, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [3915f19817](https://linux-hardware.org/?probe=3915f19817) | Oct 03, 2022 |
| Lenovo        | IdeaPad 3 17IML05 81WC      | Notebook    | [e722d17a52](https://linux-hardware.org/?probe=e722d17a52) | Oct 01, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [9667dac801](https://linux-hardware.org/?probe=9667dac801) | Sep 30, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [e829c9c0c6](https://linux-hardware.org/?probe=e829c9c0c6) | Sep 30, 2022 |
| Lenovo        | ThinkBook 15p Gen 2 21B1    | Notebook    | [16f1ddb076](https://linux-hardware.org/?probe=16f1ddb076) | Sep 30, 2022 |
| Unknown       | 775VM8                      | Desktop     | [114c84d76c](https://linux-hardware.org/?probe=114c84d76c) | Sep 30, 2022 |
| Unknown       | 775VM8                      | Desktop     | [903649eae9](https://linux-hardware.org/?probe=903649eae9) | Sep 30, 2022 |
| MSI           | H110 PC MATE                | Desktop     | [ac97c636a5](https://linux-hardware.org/?probe=ac97c636a5) | Sep 30, 2022 |
| Notebook      | NJ50_70CU                   | Notebook    | [4914d3ffe1](https://linux-hardware.org/?probe=4914d3ffe1) | Sep 29, 2022 |
| Biostar       | A10N-8800E                  | Desktop     | [d27bf09dc8](https://linux-hardware.org/?probe=d27bf09dc8) | Sep 27, 2022 |
| Medion        | MS-7728                     | Desktop     | [82da4b643b](https://linux-hardware.org/?probe=82da4b643b) | Sep 27, 2022 |
| Gigabyte      | 990FXA-UD5                  | Desktop     | [89303afdb5](https://linux-hardware.org/?probe=89303afdb5) | Sep 26, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [3c0a494baa](https://linux-hardware.org/?probe=3c0a494baa) | Sep 26, 2022 |
| Dell          | Latitude E6400              | Notebook    | [c1190109d0](https://linux-hardware.org/?probe=c1190109d0) | Sep 26, 2022 |
| Dell          | XPS 17 9700                 | Notebook    | [76166adede](https://linux-hardware.org/?probe=76166adede) | Sep 26, 2022 |
| MSI           | MAG B460 TOMAHAWK           | Desktop     | [a213c6d22a](https://linux-hardware.org/?probe=a213c6d22a) | Sep 26, 2022 |
| AMI           | Intel                       | Notebook    | [56de8f8b8a](https://linux-hardware.org/?probe=56de8f8b8a) | Sep 25, 2022 |
| AMI           | Intel                       | Notebook    | [330585dcd8](https://linux-hardware.org/?probe=330585dcd8) | Sep 25, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0047e2de0e](https://linux-hardware.org/?probe=0047e2de0e) | Sep 24, 2022 |
| Acer          | Aspire E5-771G              | Notebook    | [39dc43058e](https://linux-hardware.org/?probe=39dc43058e) | Sep 23, 2022 |
| MSI           | H110 PC MATE                | Desktop     | [006830e521](https://linux-hardware.org/?probe=006830e521) | Sep 23, 2022 |
| HP            | Compaq 15                   | Notebook    | [345fe48777](https://linux-hardware.org/?probe=345fe48777) | Sep 22, 2022 |
| Dell          | Latitude E6510              | Notebook    | [fa644f90c4](https://linux-hardware.org/?probe=fa644f90c4) | Sep 22, 2022 |
| ASUSTek       | WS C422 PRO_SE              | Desktop     | [e278a4ab5e](https://linux-hardware.org/?probe=e278a4ab5e) | Sep 21, 2022 |
| HP            | Pavilion 17                 | Notebook    | [0f7eec1f7a](https://linux-hardware.org/?probe=0f7eec1f7a) | Sep 21, 2022 |
| HP            | 1998                        | Desktop     | [5148539ae1](https://linux-hardware.org/?probe=5148539ae1) | Sep 21, 2022 |
| ASUSTek       | UX303LAB                    | Notebook    | [2165b4b046](https://linux-hardware.org/?probe=2165b4b046) | Sep 20, 2022 |
| HP            | EliteBook 840 G3            | Notebook    | [233ba928b8](https://linux-hardware.org/?probe=233ba928b8) | Sep 20, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [256ff04106](https://linux-hardware.org/?probe=256ff04106) | Sep 20, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20YDS... | Notebook    | [7561f24877](https://linux-hardware.org/?probe=7561f24877) | Sep 20, 2022 |
| Dell          | XPS 13 9380                 | Notebook    | [0c6c042af0](https://linux-hardware.org/?probe=0c6c042af0) | Sep 20, 2022 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [4d5fc6b39f](https://linux-hardware.org/?probe=4d5fc6b39f) | Sep 20, 2022 |
| Samsung       | R530/R730                   | Notebook    | [0d4e13e70f](https://linux-hardware.org/?probe=0d4e13e70f) | Sep 19, 2022 |
| Dell          | 02M8NY A01                  | Desktop     | [498286eb91](https://linux-hardware.org/?probe=498286eb91) | Sep 19, 2022 |
| HP            | ProBook 470 G4              | Notebook    | [c11b354c39](https://linux-hardware.org/?probe=c11b354c39) | Sep 18, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [9eba047248](https://linux-hardware.org/?probe=9eba047248) | Sep 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [004d0a2b9d](https://linux-hardware.org/?probe=004d0a2b9d) | Sep 17, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [980e4272fb](https://linux-hardware.org/?probe=980e4272fb) | Sep 17, 2022 |
| Intel         | DH67BL AAG10189-209         | Desktop     | [3507c0cdb7](https://linux-hardware.org/?probe=3507c0cdb7) | Sep 14, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [3c37d36ba8](https://linux-hardware.org/?probe=3c37d36ba8) | Sep 13, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [321432c752](https://linux-hardware.org/?probe=321432c752) | Sep 12, 2022 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [cae551826b](https://linux-hardware.org/?probe=cae551826b) | Sep 10, 2022 |
| Valve         | Jupiter                     | Notebook    | [49694d92f6](https://linux-hardware.org/?probe=49694d92f6) | Sep 09, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [07dfc865cf](https://linux-hardware.org/?probe=07dfc865cf) | Sep 08, 2022 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [df80ca89ee](https://linux-hardware.org/?probe=df80ca89ee) | Sep 08, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [044bee5e0c](https://linux-hardware.org/?probe=044bee5e0c) | Sep 07, 2022 |
| Dell          | XPS 13 9310 2-in-1          | Convertible | [b5270dfd32](https://linux-hardware.org/?probe=b5270dfd32) | Sep 07, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [e1a78657ba](https://linux-hardware.org/?probe=e1a78657ba) | Sep 07, 2022 |
| Acer          | Aspire S3                   | Notebook    | [cb62300974](https://linux-hardware.org/?probe=cb62300974) | Sep 07, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [12abaecf7e](https://linux-hardware.org/?probe=12abaecf7e) | Sep 05, 2022 |
| Acer          | Aspire A517-52G             | Notebook    | [c1709e40b7](https://linux-hardware.org/?probe=c1709e40b7) | Sep 05, 2022 |
| TrekStor      | Notebook Slim S130          | Notebook    | [abd3c1ccf8](https://linux-hardware.org/?probe=abd3c1ccf8) | Sep 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [e2115bf207](https://linux-hardware.org/?probe=e2115bf207) | Sep 05, 2022 |
| Lenovo        | ThinkPad T500 2241WH7       | Notebook    | [1e14648d27](https://linux-hardware.org/?probe=1e14648d27) | Sep 04, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [106bdf4d1b](https://linux-hardware.org/?probe=106bdf4d1b) | Sep 04, 2022 |
| ASUSTek       | H81M-E                      | Desktop     | [ebceb9b949](https://linux-hardware.org/?probe=ebceb9b949) | Sep 04, 2022 |
| ASUSTek       | H81M-E                      | Desktop     | [d7c48b7007](https://linux-hardware.org/?probe=d7c48b7007) | Sep 04, 2022 |
| Samsung       | 950QDB                      | Convertible | [ec7cdfdff7](https://linux-hardware.org/?probe=ec7cdfdff7) | Sep 04, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [b298d162b1](https://linux-hardware.org/?probe=b298d162b1) | Sep 04, 2022 |
| ASUSTek       | H61M-A/USB3                 | Desktop     | [7801ef775b](https://linux-hardware.org/?probe=7801ef775b) | Sep 03, 2022 |
| BESSTAR Te... | X400                        | Notebook    | [8eb69c0ad6](https://linux-hardware.org/?probe=8eb69c0ad6) | Sep 03, 2022 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [1ce3a883a0](https://linux-hardware.org/?probe=1ce3a883a0) | Sep 03, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [6109fc3fa8](https://linux-hardware.org/?probe=6109fc3fa8) | Sep 02, 2022 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [9f98c80601](https://linux-hardware.org/?probe=9f98c80601) | Sep 02, 2022 |
| Dell          | XPS 13 9305                 | Notebook    | [1746053c5b](https://linux-hardware.org/?probe=1746053c5b) | Sep 01, 2022 |
| Panasonic     | CF-191HACHFG                | Notebook    | [c1f0177dcb](https://linux-hardware.org/?probe=c1f0177dcb) | Sep 01, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [37695eb7e5](https://linux-hardware.org/?probe=37695eb7e5) | Aug 31, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [0968e0629e](https://linux-hardware.org/?probe=0968e0629e) | Aug 31, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [f07bd2b99b](https://linux-hardware.org/?probe=f07bd2b99b) | Aug 28, 2022 |
| BESSTAR Te... | X400                        | Notebook    | [ab70086ae7](https://linux-hardware.org/?probe=ab70086ae7) | Aug 27, 2022 |
| Dell          | XPS 15 9575                 | Convertible | [e18118bf63](https://linux-hardware.org/?probe=e18118bf63) | Aug 27, 2022 |
| Foxconn       | A6VMX 0A                    | Desktop     | [f31fcbf60d](https://linux-hardware.org/?probe=f31fcbf60d) | Aug 26, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [adf76251c5](https://linux-hardware.org/?probe=adf76251c5) | Aug 26, 2022 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [7c7a83f951](https://linux-hardware.org/?probe=7c7a83f951) | Aug 26, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [cf7da7df12](https://linux-hardware.org/?probe=cf7da7df12) | Aug 26, 2022 |
| Lenovo        | ThinkBook 13s G2 ITL 20V... | Notebook    | [76db86107b](https://linux-hardware.org/?probe=76db86107b) | Aug 26, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [fcfd89bb32](https://linux-hardware.org/?probe=fcfd89bb32) | Aug 25, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [c579b49e4c](https://linux-hardware.org/?probe=c579b49e4c) | Aug 25, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [57727c2af7](https://linux-hardware.org/?probe=57727c2af7) | Aug 23, 2022 |
| Acer          | Predator G3-710             | Desktop     | [7a58c9348e](https://linux-hardware.org/?probe=7a58c9348e) | Aug 22, 2022 |
| MSI           | 2A9C                        | Desktop     | [4f15bcded6](https://linux-hardware.org/?probe=4f15bcded6) | Aug 22, 2022 |
| Dell          | 0T10XW A01                  | Desktop     | [30ebde5edc](https://linux-hardware.org/?probe=30ebde5edc) | Aug 21, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ced2388c29](https://linux-hardware.org/?probe=ced2388c29) | Aug 21, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [e4869235d8](https://linux-hardware.org/?probe=e4869235d8) | Aug 20, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [782466213a](https://linux-hardware.org/?probe=782466213a) | Aug 19, 2022 |
| MSI           | 760GM-P23                   | Desktop     | [42245b8fc8](https://linux-hardware.org/?probe=42245b8fc8) | Aug 18, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [859884934f](https://linux-hardware.org/?probe=859884934f) | Aug 17, 2022 |
| Shuttle       | DS437                       | Notebook    | [21e0ca6a77](https://linux-hardware.org/?probe=21e0ca6a77) | Aug 17, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [9b0baef94d](https://linux-hardware.org/?probe=9b0baef94d) | Aug 17, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [8ea659cd8c](https://linux-hardware.org/?probe=8ea659cd8c) | Aug 17, 2022 |
| TrekStor      | Notebook Slim S130          | Notebook    | [2b5689655d](https://linux-hardware.org/?probe=2b5689655d) | Aug 16, 2022 |
| TrekStor      | Notebook Slim S130          | Notebook    | [baf685c170](https://linux-hardware.org/?probe=baf685c170) | Aug 16, 2022 |
| ASUSTek       | F2A85-V                     | Desktop     | [cc26af3a41](https://linux-hardware.org/?probe=cc26af3a41) | Aug 16, 2022 |
| VALE          | Notebook Classic C170       | Notebook    | [e1563aa775](https://linux-hardware.org/?probe=e1563aa775) | Aug 15, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [ce03a2383e](https://linux-hardware.org/?probe=ce03a2383e) | Aug 15, 2022 |
| Apple         | MacBookPro15,1              | Notebook    | [cb10c34587](https://linux-hardware.org/?probe=cb10c34587) | Aug 15, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [76e185a2e5](https://linux-hardware.org/?probe=76e185a2e5) | Aug 15, 2022 |
| Acer          | Spin SP314-54N              | Convertible | [24b804043b](https://linux-hardware.org/?probe=24b804043b) | Aug 14, 2022 |
| Lenovo        | ThinkPad T440p 20AWS1C00... | Notebook    | [dbbae31450](https://linux-hardware.org/?probe=dbbae31450) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fb405688fe](https://linux-hardware.org/?probe=fb405688fe) | Aug 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [62a1acd85d](https://linux-hardware.org/?probe=62a1acd85d) | Aug 13, 2022 |
| Lenovo        | ThinkPad T430s 2356A89      | Notebook    | [4a52da1c38](https://linux-hardware.org/?probe=4a52da1c38) | Aug 13, 2022 |
| Lenovo        | ThinkPad T430s 2356A89      | Notebook    | [f71b1992c9](https://linux-hardware.org/?probe=f71b1992c9) | Aug 13, 2022 |
| BESSTAR Te... | X400                        | Notebook    | [e8424e153d](https://linux-hardware.org/?probe=e8424e153d) | Aug 12, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [059e0786bf](https://linux-hardware.org/?probe=059e0786bf) | Aug 11, 2022 |
| MSI           | MS-77311                    | Desktop     | [86b4d71bc0](https://linux-hardware.org/?probe=86b4d71bc0) | Aug 11, 2022 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [0f33fa05f5](https://linux-hardware.org/?probe=0f33fa05f5) | Aug 10, 2022 |
| AMI           | Intel                       | Notebook    | [8d8db9dc8b](https://linux-hardware.org/?probe=8d8db9dc8b) | Aug 09, 2022 |
| AMI           | Intel                       | Notebook    | [0958b0a578](https://linux-hardware.org/?probe=0958b0a578) | Aug 09, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [3ee621b609](https://linux-hardware.org/?probe=3ee621b609) | Aug 07, 2022 |
| Lenovo        | ThinkPad T460s 20FAS6JY0... | Notebook    | [7d85d4f00b](https://linux-hardware.org/?probe=7d85d4f00b) | Aug 06, 2022 |
| HP            | 3031h                       | Desktop     | [2409514846](https://linux-hardware.org/?probe=2409514846) | Aug 06, 2022 |
| Dell          | Latitude E5550              | Notebook    | [c1d9204443](https://linux-hardware.org/?probe=c1d9204443) | Aug 06, 2022 |
| MSI           | 2A9C                        | Desktop     | [e279622ca6](https://linux-hardware.org/?probe=e279622ca6) | Aug 06, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [91998a6bfe](https://linux-hardware.org/?probe=91998a6bfe) | Aug 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d19309cb56](https://linux-hardware.org/?probe=d19309cb56) | Aug 06, 2022 |
| Fujitsu Si... | MS-7504VP-PV                | Desktop     | [03f6cbc20a](https://linux-hardware.org/?probe=03f6cbc20a) | Aug 05, 2022 |
| HP            | 8054                        | Desktop     | [888466c84e](https://linux-hardware.org/?probe=888466c84e) | Aug 04, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [8f934de8ef](https://linux-hardware.org/?probe=8f934de8ef) | Aug 03, 2022 |
| Dell          | Latitude E6430              | Notebook    | [82abc4b330](https://linux-hardware.org/?probe=82abc4b330) | Aug 03, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [8251f56856](https://linux-hardware.org/?probe=8251f56856) | Aug 03, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | Desktop     | [06c0366665](https://linux-hardware.org/?probe=06c0366665) | Aug 03, 2022 |
| HP            | EliteBook x360 1030 G2      | Convertible | [a43bd517bb](https://linux-hardware.org/?probe=a43bd517bb) | Aug 02, 2022 |
| Sony          | VGN-FW51ZF_H                | Notebook    | [f42e9458c7](https://linux-hardware.org/?probe=f42e9458c7) | Jul 31, 2022 |
| ASUSTek       | P9X79                       | Desktop     | [4a518ab792](https://linux-hardware.org/?probe=4a518ab792) | Jul 31, 2022 |
| Acer          | RS880M05                    | Desktop     | [0a5ede14e3](https://linux-hardware.org/?probe=0a5ede14e3) | Jul 30, 2022 |
| Toshiba       | Satellite L70-B             | Notebook    | [bee2cdca79](https://linux-hardware.org/?probe=bee2cdca79) | Jul 29, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [31b2d82a52](https://linux-hardware.org/?probe=31b2d82a52) | Jul 29, 2022 |
| HP            | 0AA0h                       | Desktop     | [5d21c69a99](https://linux-hardware.org/?probe=5d21c69a99) | Jul 29, 2022 |
| ASUSTek       | B85M-G                      | Desktop     | [5d5fd15071](https://linux-hardware.org/?probe=5d5fd15071) | Jul 28, 2022 |
| MSI           | B350 TOMAHAWK               | Desktop     | [1d04421fd5](https://linux-hardware.org/?probe=1d04421fd5) | Jul 27, 2022 |
| Dell          | 08WKV3 A00                  | Desktop     | [fe23b6e49a](https://linux-hardware.org/?probe=fe23b6e49a) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [c1ab099582](https://linux-hardware.org/?probe=c1ab099582) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [b690b57222](https://linux-hardware.org/?probe=b690b57222) | Jul 27, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [af6e67c798](https://linux-hardware.org/?probe=af6e67c798) | Jul 27, 2022 |
| MSI           | X79A-GD45 Plus              | Desktop     | [5496428dac](https://linux-hardware.org/?probe=5496428dac) | Jul 27, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [611f1d79e3](https://linux-hardware.org/?probe=611f1d79e3) | Jul 26, 2022 |
| Acer          | Aspire 3810T                | Notebook    | [92f9c99b5e](https://linux-hardware.org/?probe=92f9c99b5e) | Jul 26, 2022 |
| Intel         | NUC5i5RYB H40999-503        | Mini pc     | [f2f3a8788e](https://linux-hardware.org/?probe=f2f3a8788e) | Jul 23, 2022 |
| ASUSTek       | P5QPL-AM                    | Desktop     | [79113b8782](https://linux-hardware.org/?probe=79113b8782) | Jul 23, 2022 |
| ASUSTek       | X556UQK                     | Notebook    | [3e6c333747](https://linux-hardware.org/?probe=3e6c333747) | Jul 22, 2022 |
| Shuttle       | FH67H                       | Desktop     | [fe77bc1ab0](https://linux-hardware.org/?probe=fe77bc1ab0) | Jul 22, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J2... | Notebook    | [f611683c8a](https://linux-hardware.org/?probe=f611683c8a) | Jul 22, 2022 |
| Lenovo        | ThinkPad E495 20NE000BGE    | Notebook    | [bad36e8ab5](https://linux-hardware.org/?probe=bad36e8ab5) | Jul 19, 2022 |
| Lenovo        | ThinkPad T440 20B7S1QQ1P    | Notebook    | [b8220c7bb8](https://linux-hardware.org/?probe=b8220c7bb8) | Jul 18, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [b2e75a35a2](https://linux-hardware.org/?probe=b2e75a35a2) | Jul 17, 2022 |
| ASUSTek       | UX31E                       | Notebook    | [b3059e0094](https://linux-hardware.org/?probe=b3059e0094) | Jul 17, 2022 |
| Lenovo        | ThinkPad T440 20B7S1QQ1P    | Notebook    | [01fae3a07c](https://linux-hardware.org/?probe=01fae3a07c) | Jul 15, 2022 |
| MSI           | H77MA-G43                   | Desktop     | [4cb547564b](https://linux-hardware.org/?probe=4cb547564b) | Jul 13, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [05b0102f01](https://linux-hardware.org/?probe=05b0102f01) | Jul 11, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [bb0bb0b58f](https://linux-hardware.org/?probe=bb0bb0b58f) | Jul 07, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [3b7528beab](https://linux-hardware.org/?probe=3b7528beab) | Jul 07, 2022 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [0e7b73b341](https://linux-hardware.org/?probe=0e7b73b341) | Jul 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [6606cb7d46](https://linux-hardware.org/?probe=6606cb7d46) | Jul 06, 2022 |
| Sony          | VPCEH2J1E                   | Notebook    | [e51b908744](https://linux-hardware.org/?probe=e51b908744) | Jul 06, 2022 |
| HP            | ZBook Firefly 15.6 inch ... | Notebook    | [454fed051a](https://linux-hardware.org/?probe=454fed051a) | Jul 06, 2022 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [a5e8e3a046](https://linux-hardware.org/?probe=a5e8e3a046) | Jul 05, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [9fd928b97f](https://linux-hardware.org/?probe=9fd928b97f) | Jul 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [949457a05f](https://linux-hardware.org/?probe=949457a05f) | Jul 03, 2022 |
| AXDIA Inte... | WINPAD 12                   | Notebook    | [c263197569](https://linux-hardware.org/?probe=c263197569) | Jul 02, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [42b1694c97](https://linux-hardware.org/?probe=42b1694c97) | Jul 01, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [ccb50bd0f4](https://linux-hardware.org/?probe=ccb50bd0f4) | Jun 30, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [d400a91be1](https://linux-hardware.org/?probe=d400a91be1) | Jun 28, 2022 |
| ASRock        | Z490 Pro4                   | Desktop     | [f84c8a756c](https://linux-hardware.org/?probe=f84c8a756c) | Jun 25, 2022 |
| MSI           | MAG Z690 TORPEDO            | Desktop     | [44700880cf](https://linux-hardware.org/?probe=44700880cf) | Jun 24, 2022 |
| MSI           | MAG Z690 TORPEDO            | Desktop     | [517a155f9b](https://linux-hardware.org/?probe=517a155f9b) | Jun 24, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [a10adc5a33](https://linux-hardware.org/?probe=a10adc5a33) | Jun 24, 2022 |
| Clevo         | Modified by dsanke          | Notebook    | [b88e7a22fe](https://linux-hardware.org/?probe=b88e7a22fe) | Jun 22, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [e18983e0d8](https://linux-hardware.org/?probe=e18983e0d8) | Jun 22, 2022 |
| Acer          | Aspire A315-53              | Notebook    | [d59ef2842d](https://linux-hardware.org/?probe=d59ef2842d) | Jun 21, 2022 |
| ASRock        | Z370 Extreme4               | Desktop     | [c971857c53](https://linux-hardware.org/?probe=c971857c53) | Jun 20, 2022 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [de5d975c12](https://linux-hardware.org/?probe=de5d975c12) | Jun 20, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [bfc7b65dee](https://linux-hardware.org/?probe=bfc7b65dee) | Jun 18, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [eb60cda77f](https://linux-hardware.org/?probe=eb60cda77f) | Jun 18, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [e19c095325](https://linux-hardware.org/?probe=e19c095325) | Jun 18, 2022 |
| MSI           | 970A-G43                    | Desktop     | [9514e1e2ef](https://linux-hardware.org/?probe=9514e1e2ef) | Jun 16, 2022 |
| AZW           | U59                         | Desktop     | [5a661910dc](https://linux-hardware.org/?probe=5a661910dc) | Jun 16, 2022 |
| Acer          | Aspire A515-44G             | Notebook    | [f07dc47259](https://linux-hardware.org/?probe=f07dc47259) | Jun 16, 2022 |
| MSI           | H510M PRO                   | Desktop     | [b75b035492](https://linux-hardware.org/?probe=b75b035492) | Jun 14, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [772043704c](https://linux-hardware.org/?probe=772043704c) | Jun 13, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [7cc9d90361](https://linux-hardware.org/?probe=7cc9d90361) | Jun 12, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [6db07f5434](https://linux-hardware.org/?probe=6db07f5434) | Jun 11, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [c637722355](https://linux-hardware.org/?probe=c637722355) | Jun 11, 2022 |
| Valve         | Jupiter                     | Notebook    | [2353bf0f9d](https://linux-hardware.org/?probe=2353bf0f9d) | Jun 11, 2022 |
| Lenovo        | ThinkPad X220 4291IR6       | Notebook    | [958f8bb25b](https://linux-hardware.org/?probe=958f8bb25b) | Jun 09, 2022 |
| HP            | ProBook 450 G6              | Notebook    | [898eff4fae](https://linux-hardware.org/?probe=898eff4fae) | Jun 09, 2022 |
| MSI           | B350 GAMING PRO CARBON      | Desktop     | [2f1acce421](https://linux-hardware.org/?probe=2f1acce421) | Jun 08, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [37e02e84a5](https://linux-hardware.org/?probe=37e02e84a5) | Jun 07, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [90b2505b78](https://linux-hardware.org/?probe=90b2505b78) | Jun 07, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [b2f7663fc9](https://linux-hardware.org/?probe=b2f7663fc9) | Jun 07, 2022 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [39bb0fa0c5](https://linux-hardware.org/?probe=39bb0fa0c5) | Jun 07, 2022 |
| Dell          | Inspiron 14 5410 2-in-1     | Notebook    | [5ad950659b](https://linux-hardware.org/?probe=5ad950659b) | Jun 06, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [722cfa9375](https://linux-hardware.org/?probe=722cfa9375) | Jun 06, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [24da0cf09c](https://linux-hardware.org/?probe=24da0cf09c) | Jun 06, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [2aeb22bc4b](https://linux-hardware.org/?probe=2aeb22bc4b) | Jun 06, 2022 |
| ASUSTek       | H87-PRO                     | Desktop     | [fd496870e4](https://linux-hardware.org/?probe=fd496870e4) | Jun 06, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS WIF... | Desktop     | [eccf357f9f](https://linux-hardware.org/?probe=eccf357f9f) | Jun 03, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [38fb3963cd](https://linux-hardware.org/?probe=38fb3963cd) | Jun 01, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [6f5f1c9373](https://linux-hardware.org/?probe=6f5f1c9373) | Jun 01, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [156b265da0](https://linux-hardware.org/?probe=156b265da0) | Jun 01, 2022 |
| Gigabyte      | 970A-UD3                    | Desktop     | [c56522071c](https://linux-hardware.org/?probe=c56522071c) | Jun 01, 2022 |
| Dell          | Latitude 5520               | Notebook    | [03622600a8](https://linux-hardware.org/?probe=03622600a8) | May 30, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [b86f47e828](https://linux-hardware.org/?probe=b86f47e828) | May 29, 2022 |
| Dell          | Latitude E6410              | Notebook    | [72345f9352](https://linux-hardware.org/?probe=72345f9352) | May 28, 2022 |
| HP            | ProBook 470 G4              | Notebook    | [6049c10c3c](https://linux-hardware.org/?probe=6049c10c3c) | May 28, 2022 |
| HP            | 158B                        | Desktop     | [a74e9da8aa](https://linux-hardware.org/?probe=a74e9da8aa) | May 28, 2022 |
| HP            | 304Bh                       | Desktop     | [eaf30cead9](https://linux-hardware.org/?probe=eaf30cead9) | May 27, 2022 |
| System76      | Lemur Pro                   | Notebook    | [dcfd3abdd6](https://linux-hardware.org/?probe=dcfd3abdd6) | May 26, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [d6bd3ae553](https://linux-hardware.org/?probe=d6bd3ae553) | May 26, 2022 |
| Valve         | Jupiter                     | Notebook    | [643322d821](https://linux-hardware.org/?probe=643322d821) | May 26, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [257b7363bd](https://linux-hardware.org/?probe=257b7363bd) | May 24, 2022 |
| ASUSTek       | M5A97 EVO R2.0              | Desktop     | [666b9afd8f](https://linux-hardware.org/?probe=666b9afd8f) | May 24, 2022 |
| Lenovo        | ThinkPad T480s 20L8S1RS0... | Notebook    | [174f6e2270](https://linux-hardware.org/?probe=174f6e2270) | May 23, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | Desktop     | [e4fa1610cb](https://linux-hardware.org/?probe=e4fa1610cb) | May 22, 2022 |
| ASUSTek       | F2A85-V                     | Desktop     | [4d990d8f08](https://linux-hardware.org/?probe=4d990d8f08) | May 21, 2022 |
| ASUSTek       | H61M-A/USB3                 | Desktop     | [4d5f3d8c33](https://linux-hardware.org/?probe=4d5f3d8c33) | May 21, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [886a958a28](https://linux-hardware.org/?probe=886a958a28) | May 20, 2022 |
| Dell          | Latitude E6410              | Notebook    | [39be06dd23](https://linux-hardware.org/?probe=39be06dd23) | May 19, 2022 |
| Acer          | Extensa 2509                | Notebook    | [46df59d8b3](https://linux-hardware.org/?probe=46df59d8b3) | May 19, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [371eb0d1b7](https://linux-hardware.org/?probe=371eb0d1b7) | May 19, 2022 |
| Gigabyte      | Z68XP-UD3                   | Desktop     | [063aeed1a1](https://linux-hardware.org/?probe=063aeed1a1) | May 19, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [9a945a6cf5](https://linux-hardware.org/?probe=9a945a6cf5) | May 17, 2022 |
| Intel         | NUC10i5FNB K61361-306       | Mini pc     | [c118c850c6](https://linux-hardware.org/?probe=c118c850c6) | May 15, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [cea36d8ad8](https://linux-hardware.org/?probe=cea36d8ad8) | May 15, 2022 |
| Apple         | MacBookPro5,4               | Notebook    | [5b7383f9cb](https://linux-hardware.org/?probe=5b7383f9cb) | May 15, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [b28d047360](https://linux-hardware.org/?probe=b28d047360) | May 14, 2022 |
| ASUSTek       | ROG Strix G733QS_G733QS     | Notebook    | [36ccfac84d](https://linux-hardware.org/?probe=36ccfac84d) | May 14, 2022 |
| Gigabyte      | B450M S2H                   | Desktop     | [1185abcaaa](https://linux-hardware.org/?probe=1185abcaaa) | May 14, 2022 |
| ASRock        | N68C-S UCC                  | Desktop     | [369f214ed2](https://linux-hardware.org/?probe=369f214ed2) | May 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [6003e5a67f](https://linux-hardware.org/?probe=6003e5a67f) | May 13, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [f7d09ea6c5](https://linux-hardware.org/?probe=f7d09ea6c5) | May 13, 2022 |
| Valve         | Jupiter                     | Notebook    | [9cf4d23a81](https://linux-hardware.org/?probe=9cf4d23a81) | May 13, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [75587e5d3e](https://linux-hardware.org/?probe=75587e5d3e) | May 12, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [d3d6871bf7](https://linux-hardware.org/?probe=d3d6871bf7) | May 12, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [91404c39c7](https://linux-hardware.org/?probe=91404c39c7) | May 12, 2022 |
| Dell          | Latitude 5520               | Notebook    | [927a4b0ed0](https://linux-hardware.org/?probe=927a4b0ed0) | May 12, 2022 |
| Lenovo        | ThinkBook 14-IML 20RV       | Notebook    | [17dda821a0](https://linux-hardware.org/?probe=17dda821a0) | May 11, 2022 |
| ASUSTek       | Z87-A                       | Desktop     | [62ffc7ab1a](https://linux-hardware.org/?probe=62ffc7ab1a) | May 11, 2022 |
| Apple         | MacBook1,1                  | Notebook    | [399e291a66](https://linux-hardware.org/?probe=399e291a66) | May 09, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [d95a50c16a](https://linux-hardware.org/?probe=d95a50c16a) | May 09, 2022 |
| Dell          | 0T7D40 A01                  | Desktop     | [36b253f8bc](https://linux-hardware.org/?probe=36b253f8bc) | May 09, 2022 |
| Dell          | Latitude E6430              | Notebook    | [a6b570e125](https://linux-hardware.org/?probe=a6b570e125) | May 08, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [ee92f88374](https://linux-hardware.org/?probe=ee92f88374) | May 07, 2022 |
| ASUSTek       | ROG ZENITH EXTREME          | Desktop     | [5f90cb38d2](https://linux-hardware.org/?probe=5f90cb38d2) | May 07, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [8fda480b12](https://linux-hardware.org/?probe=8fda480b12) | May 06, 2022 |
| Lenovo        | ThinkPad T450s 20BWS1U60... | Notebook    | [ffafca2b97](https://linux-hardware.org/?probe=ffafca2b97) | May 06, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [d2a6709c96](https://linux-hardware.org/?probe=d2a6709c96) | May 06, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [feaa2cb9fb](https://linux-hardware.org/?probe=feaa2cb9fb) | May 06, 2022 |
| HP            | ZBook 17 G5                 | Notebook    | [5190bc7cf3](https://linux-hardware.org/?probe=5190bc7cf3) | May 06, 2022 |
| Toshiba       | Satellite C70D-B            | Notebook    | [0bc5a5fb9f](https://linux-hardware.org/?probe=0bc5a5fb9f) | May 05, 2022 |
| BESSTAR Te... | GB1B                        | Mini pc     | [9a83464a3b](https://linux-hardware.org/?probe=9a83464a3b) | May 04, 2022 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [935eb1722b](https://linux-hardware.org/?probe=935eb1722b) | May 02, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [925447d7e9](https://linux-hardware.org/?probe=925447d7e9) | May 01, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [b1e331055f](https://linux-hardware.org/?probe=b1e331055f) | May 01, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [5838cd4268](https://linux-hardware.org/?probe=5838cd4268) | Apr 30, 2022 |
| Sony          | VPCEH2J1E                   | Notebook    | [86f6b8c750](https://linux-hardware.org/?probe=86f6b8c750) | Apr 30, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [9f5c24d3e8](https://linux-hardware.org/?probe=9f5c24d3e8) | Apr 29, 2022 |
| Lenovo        | ThinkPad P14s Gen 2a 21A... | Notebook    | [da73d0b77d](https://linux-hardware.org/?probe=da73d0b77d) | Apr 29, 2022 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [b923126955](https://linux-hardware.org/?probe=b923126955) | Apr 27, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [2b7f66b701](https://linux-hardware.org/?probe=2b7f66b701) | Apr 26, 2022 |
| Fujitsu       | LIFEBOOK E751               | Notebook    | [ace84bb1e5](https://linux-hardware.org/?probe=ace84bb1e5) | Apr 25, 2022 |
| Lenovo        | Yoga C940-14IIL 81Q9        | Convertible | [bf7a7381a8](https://linux-hardware.org/?probe=bf7a7381a8) | Apr 24, 2022 |
| ASRock        | H110 Pro BTC+               | Desktop     | [1251ef669d](https://linux-hardware.org/?probe=1251ef669d) | Apr 24, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [dbb48b83bf](https://linux-hardware.org/?probe=dbb48b83bf) | Apr 24, 2022 |
| ASUSTek       | M4A78-E                     | Desktop     | [e4779f4dc8](https://linux-hardware.org/?probe=e4779f4dc8) | Apr 23, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [a8038d3972](https://linux-hardware.org/?probe=a8038d3972) | Apr 22, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [77a6f92da0](https://linux-hardware.org/?probe=77a6f92da0) | Apr 22, 2022 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [208e83a199](https://linux-hardware.org/?probe=208e83a199) | Apr 22, 2022 |
| HP            | 250 G7 Notebook PC          | Notebook    | [e7f7e1188e](https://linux-hardware.org/?probe=e7f7e1188e) | Apr 21, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Austria/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 260       | 12.68%  |
| Ubuntu 18.04                 | 125       | 6.1%    |
| Ubuntu 22.04                 | 117       | 5.71%   |
| Arch Rolling                 | 57        | 2.78%   |
| OpenMandriva 4.3             | 54        | 2.63%   |
| Debian 11                    | 51        | 2.49%   |
| Arch                         | 46        | 2.24%   |
| Linux Mint 20.2              | 43        | 2.1%    |
| OpenMandriva 4.2             | 41        | 2%      |
| Manjaro                      | 34        | 1.66%   |
| Fedora 35                    | 34        | 1.66%   |
| Fedora 37                    | 32        | 1.56%   |
| Zorin 16                     | 31        | 1.51%   |
| Linux Mint 21.1              | 31        | 1.51%   |
| Pop!_OS 22.04                | 29        | 1.41%   |
| Ubuntu 21.04                 | 28        | 1.37%   |
| Linux Mint 20.1              | 27        | 1.32%   |
| Linux Mint 19.3              | 26        | 1.27%   |
| BlackPanther 18.1            | 26        | 1.27%   |
| Ubuntu 20.10                 | 23        | 1.12%   |
| Fedora 38                    | 22        | 1.07%   |
| Fedora 33                    | 22        | 1.07%   |
| OpenMandriva 23.01           | 21        | 1.02%   |
| Linux Mint 20                | 21        | 1.02%   |
| Ubuntu 22.10                 | 20        | 0.98%   |
| Fedora 32                    | 20        | 0.98%   |
| Linux Mint 20.3              | 19        | 0.93%   |
| KDE neon 20.04               | 19        | 0.93%   |
| Fedora 34                    | 19        | 0.93%   |
| Ubuntu 19.10                 | 18        | 0.88%   |
| Xubuntu 20.04                | 17        | 0.83%   |
| Ubuntu 21.10                 | 17        | 0.83%   |
| Pop!_OS 20.10                | 17        | 0.83%   |
| openSUSE Tumbleweed-XXXXXXXX | 17        | 0.83%   |
| Linux Mint 21                | 16        | 0.78%   |
| EndeavourOS Rolling          | 16        | 0.78%   |
| Fedora 36                    | 15        | 0.73%   |
| Debian 10                    | 15        | 0.73%   |
| ArcoLinux Rolling            | 15        | 0.73%   |
| Pop!_OS 20.04                | 14        | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 633       | 32.81%  |
| Linux Mint    | 195       | 10.11%  |
| Fedora        | 148       | 7.67%   |
| OpenMandriva  | 142       | 7.36%   |
| Arch          | 98        | 5.08%   |
| Manjaro       | 97        | 5.03%   |
| Debian        | 97        | 5.03%   |
| Pop!_OS       | 75        | 3.89%   |
| Zorin         | 43        | 2.23%   |
| ROSA          | 36        | 1.87%   |
| Kubuntu       | 34        | 1.76%   |
| Xubuntu       | 30        | 1.56%   |
| openSUSE      | 28        | 1.45%   |
| KDE neon      | 27        | 1.4%    |
| BlackPanther  | 27        | 1.4%    |
| Elementary    | 21        | 1.09%   |
| EndeavourOS   | 16        | 0.83%   |
| ArcoLinux     | 16        | 0.83%   |
| Ubuntu MATE   | 13        | 0.67%   |
| Gentoo        | 12        | 0.62%   |
| SteamOS       | 11        | 0.57%   |
| Endless       | 11        | 0.57%   |
| Ubuntu Budgie | 9         | 0.47%   |
| Ubuntu Unity  | 8         | 0.41%   |
| Nobara        | 8         | 0.41%   |
| LMDE          | 8         | 0.41%   |
| MX            | 7         | 0.36%   |
| Clear Linux   | 6         | 0.31%   |
| Ubuntu Studio | 5         | 0.26%   |
| Raspbian      | 5         | 0.26%   |
| NixOS         | 5         | 0.26%   |
| Lubuntu       | 5         | 0.26%   |
| Kali          | 5         | 0.26%   |
| Parrot        | 4         | 0.21%   |
| Siduction     | 3         | 0.16%   |
| Garuda Linux  | 3         | 0.16%   |
| Deepin        | 3         | 0.16%   |
| CentOS        | 3         | 0.16%   |
| CachyOS       | 3         | 0.16%   |
| UbuntuDDE     | 2         | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.16.7-desktop-1omv4003  | 54        | 2.38%   |
| 5.10.14-desktop-1omv4002 | 40        | 1.76%   |
| 5.4.0-42-generic         | 30        | 1.32%   |
| 5.15.0-56-generic        | 22        | 0.97%   |
| 5.4.0-58-generic         | 21        | 0.93%   |
| 5.4.0-52-generic         | 18        | 0.79%   |
| 5.15.0-52-generic        | 18        | 0.79%   |
| 6.1.1-desktop-1omv2290   | 17        | 0.75%   |
| 5.13.0-39-generic        | 17        | 0.75%   |
| 4.18.16-desktop-1bP      | 17        | 0.75%   |
| 5.3.0-46-generic         | 16        | 0.71%   |
| 5.15.0-43-generic        | 16        | 0.71%   |
| 6.2.6-desktop-1omv2390   | 15        | 0.66%   |
| 5.15.0-58-generic        | 15        | 0.66%   |
| 5.4.0-91-generic         | 14        | 0.62%   |
| 5.4.0-48-generic         | 13        | 0.57%   |
| 5.4.0-26-generic         | 13        | 0.57%   |
| 5.13.0-27-generic        | 13        | 0.57%   |
| 5.4.0-33-generic         | 12        | 0.53%   |
| 5.4.0-28-generic         | 12        | 0.53%   |
| 5.13.0-28-generic        | 12        | 0.53%   |
| 5.11.0-37-generic        | 12        | 0.53%   |
| 5.6.14-desktop-2bP       | 11        | 0.49%   |
| 5.4.0-74-generic         | 11        | 0.49%   |
| 5.4.0-29-generic         | 11        | 0.49%   |
| 5.3.0-26-generic         | 11        | 0.49%   |
| 5.19.0-46-generic        | 11        | 0.49%   |
| 6.2.6-76060206-generic   | 10        | 0.44%   |
| 5.8.0-7630-generic       | 10        | 0.44%   |
| 5.19.0-35-generic        | 10        | 0.44%   |
| 5.15.0-47-generic        | 10        | 0.44%   |
| 5.11.0-27-generic        | 10        | 0.44%   |
| 5.11.0-25-generic        | 10        | 0.44%   |
| 5.4.0-80-generic         | 9         | 0.4%    |
| 5.4.0-72-generic         | 9         | 0.4%    |
| 5.3.0-42-generic         | 9         | 0.4%    |
| 5.19.0-38-generic        | 9         | 0.4%    |
| 5.15.0-46-generic        | 9         | 0.4%    |
| 5.13.0-35-generic        | 9         | 0.4%    |
| 5.13.0-30-generic        | 9         | 0.4%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 312       | 14.55%  |
| 5.15.0  | 180       | 8.4%    |
| 5.13.0  | 114       | 5.32%   |
| 5.11.0  | 103       | 4.8%    |
| 4.15.0  | 103       | 4.8%    |
| 5.8.0   | 94        | 4.38%   |
| 5.19.0  | 70        | 3.26%   |
| 5.3.0   | 66        | 3.08%   |
| 5.16.7  | 56        | 2.61%   |
| 5.10.0  | 55        | 2.57%   |
| 5.10.14 | 42        | 1.96%   |
| 5.0.0   | 34        | 1.59%   |
| 4.18.0  | 34        | 1.59%   |
| 6.2.6   | 32        | 1.49%   |
| 4.19.0  | 22        | 1.03%   |
| 6.2.0   | 20        | 0.93%   |
| 6.1.1   | 18        | 0.84%   |
| 6.1.0   | 18        | 0.84%   |
| 4.18.16 | 17        | 0.79%   |
| 5.6.14  | 11        | 0.51%   |
| 5.17.5  | 11        | 0.51%   |
| 5.12.4  | 9         | 0.42%   |
| 6.0.7   | 8         | 0.37%   |
| 5.9.11  | 8         | 0.37%   |
| 4.9.60  | 8         | 0.37%   |
| 4.4.0   | 8         | 0.37%   |
| 6.3.5   | 7         | 0.33%   |
| 5.9.16  | 7         | 0.33%   |
| 5.15.12 | 7         | 0.33%   |
| 6.2.8   | 6         | 0.28%   |
| 6.2.12  | 6         | 0.28%   |
| 6.2.11  | 6         | 0.28%   |
| 6.1.4   | 6         | 0.28%   |
| 6.1.12  | 6         | 0.28%   |
| 6.0.12  | 6         | 0.28%   |
| 5.3.18  | 6         | 0.28%   |
| 5.19.7  | 6         | 0.28%   |
| 5.19.2  | 6         | 0.28%   |
| 5.16.0  | 6         | 0.28%   |
| 5.14.9  | 6         | 0.28%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 347       | 16.47%  |
| 5.15    | 234       | 11.11%  |
| 5.10    | 138       | 6.55%   |
| 5.13    | 136       | 6.45%   |
| 5.11    | 125       | 5.93%   |
| 5.8     | 124       | 5.89%   |
| 4.15    | 103       | 4.89%   |
| 5.19    | 95        | 4.51%   |
| 6.2     | 85        | 4.03%   |
| 5.16    | 85        | 4.03%   |
| 5.3     | 79        | 3.75%   |
| 6.1     | 76        | 3.61%   |
| 4.18    | 53        | 2.52%   |
| 6.0     | 49        | 2.33%   |
| 5.17    | 37        | 1.76%   |
| 5.0     | 35        | 1.66%   |
| 5.9     | 33        | 1.57%   |
| 5.6     | 32        | 1.52%   |
| 4.19    | 30        | 1.42%   |
| 5.12    | 28        | 1.33%   |
| 5.18    | 26        | 1.23%   |
| 5.7     | 25        | 1.19%   |
| 5.14    | 23        | 1.09%   |
| 6.3     | 21        | 1%      |
| 4.9     | 21        | 1%      |
| 6.4     | 17        | 0.81%   |
| 5.5     | 11        | 0.52%   |
| 4.4     | 9         | 0.43%   |
| 4.17    | 4         | 0.19%   |
| 4.12    | 4         | 0.19%   |
| 4.1     | 4         | 0.19%   |
| 5.2     | 3         | 0.14%   |
| 4.10    | 3         | 0.14%   |
| 3.10    | 3         | 0.14%   |
| 5.1     | 2         | 0.09%   |
| 4.13    | 2         | 0.09%   |
| 4.8     | 1         | 0.05%   |
| 4.6     | 1         | 0.05%   |
| 4.20    | 1         | 0.05%   |
| 4.14    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1830      | 97.97%  |
| i686    | 19        | 1.02%   |
| aarch64 | 12        | 0.64%   |
| armv7l  | 7         | 0.37%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 822       | 42.44%  |
| KDE5             | 360       | 18.59%  |
| Unknown          | 221       | 11.41%  |
| X-Cinnamon       | 154       | 7.95%   |
| XFCE             | 142       | 7.33%   |
| MATE             | 54        | 2.79%   |
| KDE              | 38        | 1.96%   |
| Cinnamon         | 23        | 1.19%   |
| Pantheon         | 21        | 1.08%   |
| KDE4             | 19        | 0.98%   |
| Budgie           | 13        | 0.67%   |
| i3               | 12        | 0.62%   |
| LXQt             | 10        | 0.52%   |
| Unity            | 8         | 0.41%   |
| LXDE             | 7         | 0.36%   |
| Deepin           | 6         | 0.31%   |
| awesome          | 6         | 0.31%   |
| sway             | 4         | 0.21%   |
| GNOME Flashback  | 4         | 0.21%   |
| xmonad           | 2         | 0.1%    |
| lightdm-xsession | 2         | 0.1%    |
| qtile            | 1         | 0.05%   |
| openbox          | 1         | 0.05%   |
| leftwm           | 1         | 0.05%   |
| Hyprland         | 1         | 0.05%   |
| GNOME Classic    | 1         | 0.05%   |
| fluxbox          | 1         | 0.05%   |
| Enlightenment    | 1         | 0.05%   |
| DWM              | 1         | 0.05%   |
| Bspwm            | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1460      | 75.69%  |
| Wayland | 309       | 16.02%  |
| Unknown | 120       | 6.22%   |
| Tty     | 40        | 2.07%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 882       | 45.3%   |
| SDDM    | 321       | 16.49%  |
| GDM3    | 237       | 12.17%  |
| GDM     | 215       | 11.04%  |
| LightDM | 213       | 10.94%  |
| TDM     | 50        | 2.57%   |
| KDM     | 20        | 1.03%   |
| SLiM    | 5         | 0.26%   |
| XDM     | 2         | 0.1%    |
| MDM     | 1         | 0.05%   |
| LXDM    | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang       | Computers | Percent |
|------------|-----------|---------|
| de_AT      | 716       | 37.1%   |
| en_US      | 546       | 28.29%  |
| de_DE      | 271       | 14.04%  |
| Unknown    | 218       | 11.3%   |
| en_GB      | 69        | 3.58%   |
| C          | 31        | 1.61%   |
| en_IE      | 13        | 0.67%   |
| pl_PL      | 9         | 0.47%   |
| it_IT      | 6         | 0.31%   |
| ru_RU      | 5         | 0.26%   |
| es_ES      | 5         | 0.26%   |
| en_AT      | 5         | 0.26%   |
| POSIX      | 4         | 0.21%   |
| de_CH      | 4         | 0.21%   |
| tr_TR      | 3         | 0.16%   |
| uk_UA      | 2         | 0.1%    |
| hu_HU      | 2         | 0.1%    |
| en_DE      | 2         | 0.1%    |
| de_AT.UTF8 | 2         | 0.1%    |
| sv_SE      | 1         | 0.05%   |
| ro_RO      | 1         | 0.05%   |
| pt_BR      | 1         | 0.05%   |
| nl_NL      | 1         | 0.05%   |
| nl_BE      | 1         | 0.05%   |
| hr_HR      | 1         | 0.05%   |
| fr_FR      | 1         | 0.05%   |
| fa_IR      | 1         | 0.05%   |
| en_US.UTF8 | 1         | 0.05%   |
| en_CA      | 1         | 0.05%   |
| en_AU      | 1         | 0.05%   |
| en         | 1         | 0.05%   |
| de_LI      | 1         | 0.05%   |
| da_DK      | 1         | 0.05%   |
| cs_CZ      | 1         | 0.05%   |
| C.UTF8     | 1         | 0.05%   |
| bg_BG      | 1         | 0.05%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 984       | 51.25%  |
| BIOS | 936       | 48.75%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 1411      | 73.64%  |
| Btrfs   | 191       | 9.97%   |
| Overlay | 176       | 9.19%   |
| Unknown | 62        | 3.24%   |
| Tmpfs   | 30        | 1.57%   |
| Xfs     | 20        | 1.04%   |
| Zfs     | 14        | 0.73%   |
| Ext2    | 5         | 0.26%   |
| F2fs    | 2         | 0.1%    |
| Ext3    | 2         | 0.1%    |
| XXXXXXX | 1         | 0.05%   |
| Nfs     | 1         | 0.05%   |
| Aufs    | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 932       | 48.54%  |
| GPT     | 790       | 41.15%  |
| MBR     | 198       | 10.31%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1601      | 83.91%  |
| Yes       | 307       | 16.09%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1313      | 68.92%  |
| Yes       | 592       | 31.08%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 334       | 17.89%  |
| ASUSTek Computer                     | 333       | 17.84%  |
| Hewlett-Packard                      | 263       | 14.09%  |
| Dell                                 | 139       | 7.45%   |
| MSI                                  | 134       | 7.18%   |
| Acer                                 | 108       | 5.78%   |
| Gigabyte Technology                  | 91        | 4.87%   |
| ASRock                               | 81        | 4.34%   |
| Medion                               | 50        | 2.68%   |
| Apple                                | 38        | 2.04%   |
| Toshiba                              | 25        | 1.34%   |
| Intel                                | 23        | 1.23%   |
| TUXEDO                               | 20        | 1.07%   |
| Fujitsu                              | 20        | 1.07%   |
| Sony                                 | 19        | 1.02%   |
| Unknown                              | 16        | 0.86%   |
| Raspberry Pi Foundation              | 12        | 0.64%   |
| Valve                                | 10        | 0.54%   |
| Samsung Electronics                  | 10        | 0.54%   |
| HUAWEI                               | 9         | 0.48%   |
| Biostar                              | 9         | 0.48%   |
| Microsoft                            | 8         | 0.43%   |
| TrekStor                             | 7         | 0.37%   |
| Fujitsu Siemens                      | 6         | 0.32%   |
| ZOTAC                                | 5         | 0.27%   |
| Supermicro                           | 5         | 0.27%   |
| Shuttle                              | 5         | 0.27%   |
| Notebook                             | 5         | 0.27%   |
| Foxconn                              | 5         | 0.27%   |
| Hampoo                               | 4         | 0.21%   |
| Clevo                                | 4         | 0.21%   |
| BESSTAR Tech                         | 4         | 0.21%   |
| Wortmann AG                          | 3         | 0.16%   |
| Shenzhen Meigao Electronic Equipment | 3         | 0.16%   |
| Razer                                | 3         | 0.16%   |
| Pegatron                             | 3         | 0.16%   |
| AMI                                  | 3         | 0.16%   |
| VALE                                 | 2         | 0.11%   |
| Timi                                 | 2         | 0.11%   |
| theobroma-systems                    | 2         | 0.11%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                               | Computers | Percent |
|------------------------------------|-----------|---------|
| ASUS All Series                    | 27        | 1.45%   |
| Unknown                            | 22        | 1.18%   |
| MSI MS-7C37                        | 15        | 0.8%    |
| Valve Jupiter                      | 10        | 0.54%   |
| ASUS H110M-A                       | 9         | 0.48%   |
| Apple MacBookPro15,1               | 8         | 0.43%   |
| MSI MS-7B86                        | 7         | 0.37%   |
| MSI MS-7B79                        | 7         | 0.37%   |
| MSI MS-7C91                        | 6         | 0.32%   |
| HP EliteBook 8570p                 | 6         | 0.32%   |
| HP EliteBook 840 G3                | 6         | 0.32%   |
| ASUS ROG STRIX B550-F GAMING       | 6         | 0.32%   |
| ASUS PRIME B450-PLUS               | 6         | 0.32%   |
| ASRock Z87 Killer                  | 6         | 0.32%   |
| Lenovo IdeaPad 5 15ARE05 81YQ      | 5         | 0.27%   |
| HP Pavilion dv6                    | 5         | 0.27%   |
| Dell Latitude E6400                | 5         | 0.27%   |
| ASUS TUF Gaming X570-PLUS          | 5         | 0.27%   |
| ASUS ROG STRIX B450-F GAMING       | 5         | 0.27%   |
| Toshiba Satellite C70D-B           | 4         | 0.21%   |
| RPi Raspberry Pi 4 Model B Rev 1.1 | 4         | 0.21%   |
| RPi Raspberry Pi                   | 4         | 0.21%   |
| Lenovo Yoga Slim 7 14ARE05 82A2    | 4         | 0.21%   |
| HP EliteDesk 800 G1 SFF            | 4         | 0.21%   |
| HP EliteBook 8460p                 | 4         | 0.21%   |
| HP EliteBook 840 G6                | 4         | 0.21%   |
| HP EliteBook 6930p                 | 4         | 0.21%   |
| HP Compaq 8200 Elite SFF PC        | 4         | 0.21%   |
| Dell XPS 15 9570                   | 4         | 0.21%   |
| Dell Latitude E7450                | 4         | 0.21%   |
| Dell Latitude 5520                 | 4         | 0.21%   |
| ASUS UX303LAB                      | 4         | 0.21%   |
| ASUS TUF Gaming B550-PLUS          | 4         | 0.21%   |
| ASUS ROG STRIX B550-I GAMING       | 4         | 0.21%   |
| ASUS PRIME A320M-K                 | 4         | 0.21%   |
| Apple MacBookPro8,1                | 4         | 0.21%   |
| TrekStor Notebook Slim S130        | 3         | 0.16%   |
| RPi Raspberry Pi 4 Model B Rev 1.2 | 3         | 0.16%   |
| MSI MS-7C02                        | 3         | 0.16%   |
| MSI MS-7A38                        | 3         | 0.16%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 200       | 10.71%  |
| HP EliteBook       | 68        | 3.64%   |
| Acer Aspire        | 62        | 3.32%   |
| Dell Latitude      | 51        | 2.73%   |
| ASUS ROG           | 41        | 2.2%    |
| ASUS PRIME         | 41        | 2.2%    |
| Lenovo IdeaPad     | 32        | 1.71%   |
| HP ProBook         | 32        | 1.71%   |
| HP Pavilion        | 32        | 1.71%   |
| Dell XPS           | 30        | 1.61%   |
| ASUS All           | 27        | 1.45%   |
| HP Compaq          | 24        | 1.29%   |
| Toshiba Satellite  | 22        | 1.18%   |
| Lenovo Yoga        | 22        | 1.18%   |
| Unknown            | 22        | 1.18%   |
| ASUS TUF           | 18        | 0.96%   |
| Lenovo ThinkCentre | 17        | 0.91%   |
| Dell Inspiron      | 17        | 0.91%   |
| Dell OptiPlex      | 16        | 0.86%   |
| MSI MS-7C37        | 15        | 0.8%    |
| HP ENVY            | 14        | 0.75%   |
| Dell Precision     | 13        | 0.7%    |
| RPi Raspberry      | 12        | 0.64%   |
| HP ZBook           | 12        | 0.64%   |
| ASUS VivoBook      | 12        | 0.64%   |
| Lenovo ThinkBook   | 11        | 0.59%   |
| Acer TravelMate    | 11        | 0.59%   |
| Valve Jupiter      | 10        | 0.54%   |
| HP Laptop          | 10        | 0.54%   |
| Fujitsu LIFEBOOK   | 10        | 0.54%   |
| ASUS H110M-A       | 9         | 0.48%   |
| Acer Swift         | 9         | 0.48%   |
| Microsoft Surface  | 8         | 0.43%   |
| Gigabyte X570      | 8         | 0.43%   |
| Apple MacBookPro15 | 8         | 0.43%   |
| Acer Nitro         | 8         | 0.43%   |
| MSI MS-7B86        | 7         | 0.37%   |
| MSI MS-7B79        | 7         | 0.37%   |
| HP EliteDesk       | 7         | 0.37%   |
| ASUS ZenBook       | 7         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 219       | 11.73%  |
| 2019    | 180       | 9.64%   |
| 2018    | 177       | 9.48%   |
| 2012    | 156       | 8.36%   |
| 2011    | 135       | 7.23%   |
| 2021    | 134       | 7.18%   |
| 2013    | 123       | 6.59%   |
| 2015    | 120       | 6.43%   |
| 2017    | 111       | 5.95%   |
| 2016    | 105       | 5.62%   |
| 2014    | 99        | 5.3%    |
| 2010    | 68        | 3.64%   |
| 2009    | 64        | 3.43%   |
| 2008    | 55        | 2.95%   |
| 2022    | 52        | 2.79%   |
| 2007    | 35        | 1.87%   |
| Unknown | 13        | 0.7%    |
| 2006    | 12        | 0.64%   |
| 2023    | 6         | 0.32%   |
| 2005    | 3         | 0.16%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 982       | 52.6%   |
| Desktop        | 730       | 39.1%   |
| Convertible    | 59        | 3.16%   |
| Mini pc        | 34        | 1.82%   |
| Tablet         | 22        | 1.18%   |
| System on chip | 19        | 1.02%   |
| Server         | 16        | 0.86%   |
| All in one     | 5         | 0.27%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1728      | 91.57%  |
| Enabled  | 159       | 8.43%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1862      | 99.73%  |
| Yes  | 5         | 0.27%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 419       | 22.2%   |
| 4.01-8.0        | 393       | 20.83%  |
| 8.01-16.0       | 361       | 19.13%  |
| 3.01-4.0        | 276       | 14.63%  |
| 32.01-64.0      | 243       | 12.88%  |
| 64.01-256.0     | 65        | 3.44%   |
| 1.01-2.0        | 51        | 2.7%    |
| 24.01-32.0      | 46        | 2.44%   |
| 2.01-3.0        | 14        | 0.74%   |
| 0.51-1.0        | 12        | 0.64%   |
| More than 256.0 | 6         | 0.32%   |
| Unknown         | 1         | 0.05%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 702       | 33.73%  |
| 2.01-3.0   | 516       | 24.8%   |
| 4.01-8.0   | 320       | 15.38%  |
| 3.01-4.0   | 257       | 12.35%  |
| 0.51-1.0   | 117       | 5.62%   |
| 8.01-16.0  | 111       | 5.33%   |
| 0.01-0.5   | 20        | 0.96%   |
| 16.01-24.0 | 19        | 0.91%   |
| 24.01-32.0 | 10        | 0.48%   |
| 32.01-64.0 | 8         | 0.38%   |
| Unknown    | 1         | 0.05%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1100      | 56.73%  |
| 2      | 471       | 24.29%  |
| 3      | 179       | 9.23%   |
| 4      | 88        | 4.54%   |
| 5      | 37        | 1.91%   |
| 6      | 20        | 1.03%   |
| 9      | 10        | 0.52%   |
| 0      | 10        | 0.52%   |
| 7      | 9         | 0.46%   |
| 10     | 6         | 0.31%   |
| 11     | 3         | 0.15%   |
| 8      | 3         | 0.15%   |
| 18     | 2         | 0.1%    |
| 12     | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1136      | 60.49%  |
| Yes       | 742       | 39.51%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1625      | 86.81%  |
| No        | 247       | 13.19%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1404      | 74.88%  |
| No        | 471       | 25.12%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1107      | 59.01%  |
| No        | 769       | 40.99%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Austria | 1867      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Vienna            | 1076      | 54.62%  |
| Graz              | 99        | 5.03%   |
| Linz              | 55        | 2.79%   |
| Innsbruck         | 54        | 2.74%   |
| Salzburg          | 44        | 2.23%   |
| Bad Hall          | 31        | 1.57%   |
| Klagenfurt        | 23        | 1.17%   |
| Sankt Pölten     | 20        | 1.02%   |
| Wels              | 17        | 0.86%   |
| Dornbirn          | 16        | 0.81%   |
| Wiener Neustadt   | 13        | 0.66%   |
| Perg              | 10        | 0.51%   |
| Leonding          | 10        | 0.51%   |
| Villach           | 9         | 0.46%   |
| Steyr             | 9         | 0.46%   |
| Wörgl            | 8         | 0.41%   |
| Korneuburg        | 7         | 0.36%   |
| Feldkirch         | 7         | 0.36%   |
| Baden bei Wien    | 7         | 0.36%   |
| Bregenz           | 6         | 0.3%    |
| Zell am See       | 5         | 0.25%   |
| Traunkirchen      | 5         | 0.25%   |
| Traun             | 5         | 0.25%   |
| Mautern           | 5         | 0.25%   |
| Brunn am Gebirge  | 5         | 0.25%   |
| Voecklabruck      | 4         | 0.2%    |
| Umhausen          | 4         | 0.2%    |
| Seiersberg        | 4         | 0.2%    |
| Schwechat         | 4         | 0.2%    |
| Perchtoldsdorf    | 4         | 0.2%    |
| Lustenau          | 4         | 0.2%    |
| Klosterneuburg    | 4         | 0.2%    |
| Kalsdorf bei Graz | 4         | 0.2%    |
| Hallein           | 4         | 0.2%    |
| Gaenserndorf      | 4         | 0.2%    |
| Falkenstein       | 4         | 0.2%    |
| Zirl              | 3         | 0.15%   |
| Sommerein         | 3         | 0.15%   |
| Ried im Innkreis  | 3         | 0.15%   |
| Ober-Grafendorf   | 3         | 0.15%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 655       | 1054   | 23.04%  |
| Seagate                     | 329       | 500    | 11.57%  |
| WDC                         | 312       | 488    | 10.97%  |
| Sandisk                     | 254       | 355    | 8.93%   |
| Toshiba                     | 175       | 282    | 6.16%   |
| Kingston                    | 129       | 164    | 4.54%   |
| Unknown                     | 122       | 175    | 4.29%   |
| Crucial                     | 118       | 190    | 4.15%   |
| Intel                       | 70        | 86     | 2.46%   |
| SK hynix                    | 67        | 93     | 2.36%   |
| Hitachi                     | 65        | 74     | 2.29%   |
| Intenso                     | 61        | 75     | 2.15%   |
| Micron Technology           | 46        | 55     | 1.62%   |
| HGST                        | 40        | 68     | 1.41%   |
| Transcend                   | 30        | 36     | 1.06%   |
| Phison                      | 23        | 32     | 0.81%   |
| KIOXIA                      | 20        | 32     | 0.7%    |
| A-DATA Technology           | 20        | 27     | 0.7%    |
| Micron/Crucial Technology   | 18        | 20     | 0.63%   |
| China                       | 18        | 22     | 0.63%   |
| Apple                       | 18        | 30     | 0.63%   |
| OCZ                         | 14        | 24     | 0.49%   |
| Corsair                     | 12        | 15     | 0.42%   |
| ASMT                        | 11        | 19     | 0.39%   |
| Phison Electronics          | 10        | 13     | 0.35%   |
| Kingston Technology Company | 10        | 12     | 0.35%   |
| JMicron Technology          | 9         | 19     | 0.32%   |
| SABRENT                     | 8         | 9      | 0.28%   |
| LITEONIT                    | 8         | 11     | 0.28%   |
| LITEON                      | 8         | 9      | 0.28%   |
| Unknown                     | 8         | 13     | 0.28%   |
| Silicon Motion              | 7         | 9      | 0.25%   |
| Patriot                     | 6         | 9      | 0.21%   |
| Apacer                      | 6         | 9      | 0.21%   |
| INNOVATION IT               | 5         | 6      | 0.18%   |
| Hewlett-Packard             | 5         | 11     | 0.18%   |
| GOODRAM                     | 5         | 5      | 0.18%   |
| Verbatim                    | 4         | 4      | 0.14%   |
| SPCC                        | 4         | 14     | 0.14%   |
| Maxtor                      | 4         | 5      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 850 EVO 250GB                           | 38        | 1.19%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 33        | 1.03%   |
| Samsung SSD 860 EVO 500GB                           | 31        | 0.97%   |
| Samsung SSD 850 EVO 500GB                           | 28        | 0.87%   |
| Samsung NVMe SSD Drive 512GB                        | 27        | 0.84%   |
| Unknown MMC Card  64GB                              | 24        | 0.75%   |
| Seagate Expansion 2TB                               | 22        | 0.69%   |
| Samsung SSD 840 EVO 250GB                           | 21        | 0.66%   |
| Crucial CT500MX500SSD1 500GB                        | 20        | 0.62%   |
| SanDisk SSD PLUS 240GB                              | 19        | 0.59%   |
| Samsung SSD 860 EVO 250GB                           | 19        | 0.59%   |
| Samsung SSD 850 PRO 256GB                           | 19        | 0.59%   |
| Samsung SSD 860 EVO 1TB                             | 18        | 0.56%   |
| Samsung NVMe SSD Drive 500GB                        | 18        | 0.56%   |
| Samsung NVMe SSD Drive 1TB                          | 18        | 0.56%   |
| Samsung SSD 970 EVO Plus 1TB                        | 17        | 0.53%   |
| Toshiba DT01ACA200 2TB                              | 16        | 0.5%    |
| Crucial CT1000MX500SSD1 1TB                         | 16        | 0.5%    |
| Toshiba MQ01ABD100 1TB                              | 15        | 0.47%   |
| SanDisk SSD PLUS 1000GB                             | 15        | 0.47%   |
| Samsung SSD 980 PRO 1TB                             | 15        | 0.47%   |
| Unknown SD/MMC/MS PRO 1GB                           | 14        | 0.44%   |
| Unknown MMC Card  32GB                              | 14        | 0.44%   |
| Kingston SUV400S37240G 240GB SSD                    | 14        | 0.44%   |
| Toshiba MQ04ABF100 1TB                              | 13        | 0.41%   |
| SanDisk NVMe SSD Drive 512GB                        | 13        | 0.41%   |
| Seagate ST2000DM008-2FR102 2TB                      | 12        | 0.37%   |
| SanDisk SSD PLUS 480GB                              | 12        | 0.37%   |
| SanDisk SDSSDH3 1T00 1TB                            | 12        | 0.37%   |
| SanDisk SDSSDA240G 240GB                            | 12        | 0.37%   |
| SanDisk NVMe SSD Drive 1TB                          | 12        | 0.37%   |
| Samsung NVMe SSD Drive 1024GB                       | 12        | 0.37%   |
| Kingston SA400S37120G 120GB SSD                     | 12        | 0.37%   |
| Crucial CT240BX500SSD1 240GB                        | 12        | 0.37%   |
| Toshiba HDWD110 1TB                                 | 11        | 0.34%   |
| Seagate ST4000VN008-2DR166 4TB                      | 11        | 0.34%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 11        | 0.34%   |
| Seagate ST1000DM010-2EP102 1TB                      | 11        | 0.34%   |
| Samsung SSD 860 QVO 1TB                             | 11        | 0.34%   |
| Seagate ST500LT012-1DG142 500GB                     | 10        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 321       | 479    | 34.97%  |
| WDC                 | 243       | 386    | 26.47%  |
| Toshiba             | 128       | 199    | 13.94%  |
| Hitachi             | 65        | 74     | 7.08%   |
| Samsung Electronics | 56        | 79     | 6.1%    |
| HGST                | 40        | 68     | 4.36%   |
| Unknown             | 15        | 22     | 1.63%   |
| Intenso             | 14        | 14     | 1.53%   |
| SABRENT             | 8         | 9      | 0.87%   |
| Maxtor              | 4         | 5      | 0.44%   |
| JMicron Technology  | 4         | 14     | 0.44%   |
| USB                 | 2         | 2      | 0.22%   |
| LaCie               | 2         | 2      | 0.22%   |
| Hewlett-Packard     | 2         | 9      | 0.22%   |
| Fujitsu             | 2         | 2      | 0.22%   |
| ASMT                | 2         | 8      | 0.22%   |
| WD MediaMax         | 1         | 1      | 0.11%   |
| Synology            | 1         | 8      | 0.11%   |
| Magnetic Data       | 1         | 1      | 0.11%   |
| Inateck             | 1         | 1      | 0.11%   |
| IBM-ESXS            | 1         | 2      | 0.11%   |
| IB-1122             | 1         | 1      | 0.11%   |
| IB                  | 1         | 2      | 0.11%   |
| Ext Hard            | 1         | 1      | 0.11%   |
| ASMedia             | 1         | 1      | 0.11%   |
| Apple               | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 350       | 531    | 31.82%  |
| SanDisk             | 189       | 270    | 17.18%  |
| Crucial             | 110       | 168    | 10%     |
| Kingston            | 98        | 119    | 8.91%   |
| Intenso             | 40        | 52     | 3.64%   |
| Intel               | 32        | 39     | 2.91%   |
| Transcend           | 27        | 31     | 2.45%   |
| WDC                 | 26        | 32     | 2.36%   |
| Micron Technology   | 22        | 27     | 2%      |
| SK hynix            | 21        | 35     | 1.91%   |
| China               | 18        | 22     | 1.64%   |
| OCZ                 | 14        | 24     | 1.27%   |
| A-DATA Technology   | 14        | 19     | 1.27%   |
| Toshiba             | 10        | 12     | 0.91%   |
| LITEONIT            | 8         | 11     | 0.73%   |
| LITEON              | 8         | 9      | 0.73%   |
| Corsair             | 8         | 8      | 0.73%   |
| Apple               | 8         | 8      | 0.73%   |
| ASMT                | 7         | 7      | 0.64%   |
| Patriot             | 5         | 5      | 0.45%   |
| INNOVATION IT       | 5         | 6      | 0.45%   |
| GOODRAM             | 5         | 5      | 0.45%   |
| Apacer              | 5         | 6      | 0.45%   |
| Verbatim            | 4         | 4      | 0.36%   |
| JMicron Technology  | 4         | 4      | 0.36%   |
| SPCC                | 3         | 3      | 0.27%   |
| Phison              | 3         | 4      | 0.27%   |
| KingDian            | 3         | 3      | 0.27%   |
| BAITITON            | 3         | 3      | 0.27%   |
| Unknown             | 2         | 3      | 0.18%   |
| TrekStor            | 2         | 4      | 0.18%   |
| Teclast             | 2         | 2      | 0.18%   |
| TCSUNBOW            | 2         | 2      | 0.18%   |
| Seagate             | 2         | 3      | 0.18%   |
| Plextor             | 2         | 2      | 0.18%   |
| Netac               | 2         | 5      | 0.18%   |
| Leven               | 2         | 2      | 0.18%   |
| Hewlett-Packard     | 2         | 2      | 0.18%   |
| Dogfish             | 2         | 2      | 0.18%   |
| BIWIN               | 2         | 2      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 945       | 1531   | 37.34%  |
| HDD     | 753       | 1391   | 29.75%  |
| NVMe    | 687       | 1047   | 27.14%  |
| MMC     | 107       | 154    | 4.23%   |
| Unknown | 39        | 87     | 1.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1328      | 2755   | 58.53%  |
| NVMe | 687       | 1047   | 30.28%  |
| SAS  | 147       | 254    | 6.48%   |
| MMC  | 107       | 154    | 4.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 999       | 1642   | 54.74%  |
| 0.51-1.0   | 500       | 716    | 27.4%   |
| 1.01-2.0   | 175       | 283    | 9.59%   |
| 3.01-4.0   | 68        | 133    | 3.73%   |
| 4.01-10.0  | 40        | 67     | 2.19%   |
| 2.01-3.0   | 35        | 51     | 1.92%   |
| 10.01-20.0 | 8         | 30     | 0.44%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 489       | 24.57%  |
| 251-500        | 374       | 18.79%  |
| 501-1000       | 304       | 15.28%  |
| 1001-2000      | 162       | 8.14%   |
| 1-20           | 153       | 7.69%   |
| More than 3000 | 130       | 6.53%   |
| 51-100         | 130       | 6.53%   |
| Unknown        | 98        | 4.92%   |
| 21-50          | 82        | 4.12%   |
| 2001-3000      | 68        | 3.42%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 743       | 36.03%  |
| 21-50          | 324       | 15.71%  |
| 101-250        | 243       | 11.78%  |
| 51-100         | 189       | 9.17%   |
| 251-500        | 153       | 7.42%   |
| 501-1000       | 145       | 7.03%   |
| Unknown        | 98        | 4.75%   |
| 1001-2000      | 84        | 4.07%   |
| More than 3000 | 51        | 2.47%   |
| 2001-3000      | 32        | 1.55%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| WDC WD10EADS-22M2B0 1TB                  | 7         | 7      | 4.22%   |
| SanDisk SD6SF1M128G1022I 128GB SSD       | 5         | 5      | 3.01%   |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 4         | 4      | 2.41%   |
| Toshiba MQ01ABF050 500GB                 | 3         | 4      | 1.81%   |
| Samsung Electronics HD103UJ 1TB          | 3         | 3      | 1.81%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 2         | 2      | 1.2%    |
| Seagate ST3500413AS 500GB                | 2         | 2      | 1.2%    |
| SanDisk SSD PLUS 480GB                   | 2         | 2      | 1.2%    |
| Samsung Electronics SSD 840 Series 120GB | 2         | 2      | 1.2%    |
| Samsung Electronics HM500JI 500GB        | 2         | 2      | 1.2%    |
| Samsung Electronics HD753LJ 752GB        | 2         | 2      | 1.2%    |
| Hitachi HTS547575A9E384 752GB            | 2         | 2      | 1.2%    |
| HGST HTS725050A7E630 500GB               | 2         | 14     | 1.2%    |
| HGST HTS721010A9E630 1TB                 | 2         | 3      | 1.2%    |
| WDC WD6400AACS-00G8B0 640GB              | 1         | 1      | 0.6%    |
| WDC WD5000LPLX-00ZNTT0 500GB             | 1         | 1      | 0.6%    |
| WDC WD5000AAKX-08U6AA0 500GB             | 1         | 1      | 0.6%    |
| WDC WD5000AAKS-60Z1A0 500GB              | 1         | 1      | 0.6%    |
| WDC WD5000AAKS-00UU3A0 500GB             | 1         | 1      | 0.6%    |
| WDC WD5000AADS-00M2B0 500GB              | 1         | 1      | 0.6%    |
| WDC WD3200BEVT-08A23T1 320GB             | 1         | 1      | 0.6%    |
| WDC WD20EZRZ-00Z5HB0 2TB                 | 1         | 1      | 0.6%    |
| WDC WD20EZRX-22D8PB0 2TB                 | 1         | 1      | 0.6%    |
| WDC WD20EZRX-00D8PB0 2TB                 | 1         | 1      | 0.6%    |
| WDC WD20EFRX-68AX9N0 2TB                 | 1         | 11     | 0.6%    |
| WDC WD2003FYYS-02W0B1 2TB                | 1         | 1      | 0.6%    |
| WDC WD2002FYPS-02W3B0 2TB                | 1         | 1      | 0.6%    |
| WDC WD2000FYYZ-01UL1B1 2TB               | 1         | 1      | 0.6%    |
| WDC WD1600BEVT-22ZCT0 160GB              | 1         | 1      | 0.6%    |
| WDC WD10EZRX-00L4HB0 1TB                 | 1         | 1      | 0.6%    |
| WDC WD10EZEX-75M2NA0 1TB                 | 1         | 1      | 0.6%    |
| WDC WD10EZEX-60WN4A0 1TB                 | 1         | 1      | 0.6%    |
| WDC WD10EACS-00D6B0 1TB                  | 1         | 2      | 0.6%    |
| WDC WD1002FAEX-00Y9A0 1TB                | 1         | 1      | 0.6%    |
| WDC WD1001FALS-40K1B0 1TB                | 1         | 1      | 0.6%    |
| TrekStor TREKSTORSSD128GB                | 1         | 1      | 0.6%    |
| Transcend TS240GSSD220S 240GB            | 1         | 1      | 0.6%    |
| Toshiba MQ02ABF050H 500GB                | 1         | 1      | 0.6%    |
| Toshiba MQ01ABD100M 1TB                  | 1         | 1      | 0.6%    |
| Toshiba MQ01ABD100 1TB                   | 1         | 1      | 0.6%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| WDC                         | 29        | 41     | 18.24%  |
| Seagate                     | 28        | 44     | 17.61%  |
| Samsung Electronics         | 25        | 31     | 15.72%  |
| Toshiba                     | 15        | 17     | 9.43%   |
| SanDisk                     | 14        | 15     | 8.81%   |
| Hitachi                     | 13        | 14     | 8.18%   |
| HGST                        | 7         | 20     | 4.4%    |
| Intel                       | 4         | 4      | 2.52%   |
| Kingston                    | 3         | 3      | 1.89%   |
| SK hynix                    | 2         | 12     | 1.26%   |
| OCZ                         | 2         | 4      | 1.26%   |
| LITEONIT                    | 2         | 3      | 1.26%   |
| Crucial                     | 2         | 2      | 1.26%   |
| TrekStor                    | 1         | 1      | 0.63%   |
| Transcend                   | 1         | 1      | 0.63%   |
| Patriot                     | 1         | 1      | 0.63%   |
| Maxtor                      | 1         | 1      | 0.63%   |
| LITEON                      | 1         | 1      | 0.63%   |
| Kingston Technology Company | 1         | 1      | 0.63%   |
| Intenso                     | 1         | 1      | 0.63%   |
| HP Phison                   | 1         | 1      | 0.63%   |
| GOODRAM                     | 1         | 1      | 0.63%   |
| Fujitsu                     | 1         | 1      | 0.63%   |
| Corsair                     | 1         | 1      | 0.63%   |
| BAITITON                    | 1         | 1      | 0.63%   |
| A-DATA Technology           | 1         | 3      | 0.63%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 29        | 41     | 27.62%  |
| Seagate             | 28        | 44     | 26.67%  |
| Toshiba             | 14        | 16     | 13.33%  |
| Hitachi             | 13        | 14     | 12.38%  |
| Samsung Electronics | 12        | 13     | 11.43%  |
| HGST                | 7         | 20     | 6.67%   |
| Maxtor              | 1         | 1      | 0.95%   |
| Fujitsu             | 1         | 1      | 0.95%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 99        | 150    | 64.71%  |
| SSD  | 45        | 65     | 29.41%  |
| NVMe | 9         | 10     | 5.88%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD6400BEVT-22A0RT0 640GB      | 1         | 1      | 50%     |
| Samsung Electronics SSD 980 500GB | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 50%     |
| Samsung Electronics | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1130      | 2297   | 54.59%  |
| Works    | 794       | 1685   | 38.36%  |
| Malfunc  | 143       | 225    | 6.91%   |
| Failed   | 2         | 2      | 0.1%    |
| Limited  | 1         | 1      | 0.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1155      | 46.82%  |
| AMD                              | 391       | 15.85%  |
| Samsung Electronics              | 312       | 12.65%  |
| SanDisk                          | 109       | 4.42%   |
| ASMedia Technology               | 69        | 2.8%    |
| SK hynix                         | 47        | 1.91%   |
| Kingston Technology Company      | 42        | 1.7%    |
| Toshiba America Info Systems     | 40        | 1.62%   |
| Phison Electronics               | 39        | 1.58%   |
| Marvell Technology Group         | 39        | 1.58%   |
| JMicron Technology               | 31        | 1.26%   |
| Micron/Crucial Technology        | 26        | 1.05%   |
| Micron Technology                | 25        | 1.01%   |
| Nvidia                           | 24        | 0.97%   |
| KIOXIA                           | 18        | 0.73%   |
| LSI Logic / Symbios Logic        | 11        | 0.45%   |
| Broadcom / LSI                   | 11        | 0.45%   |
| Silicon Motion                   | 10        | 0.41%   |
| Apple                            | 9         | 0.36%   |
| ADATA Technology                 | 9         | 0.36%   |
| Union Memory (Shenzhen)          | 8         | 0.32%   |
| Seagate Technology               | 7         | 0.28%   |
| VIA Technologies                 | 6         | 0.24%   |
| Silicon Image                    | 5         | 0.2%    |
| Lenovo                           | 4         | 0.16%   |
| MAXIO Technology (Hangzhou)      | 3         | 0.12%   |
| Solid State Storage Technology   | 2         | 0.08%   |
| Realtek Semiconductor            | 2         | 0.08%   |
| OCZ Technology Group             | 2         | 0.08%   |
| Hewlett-Packard                  | 2         | 0.08%   |
| Adaptec                          | 2         | 0.08%   |
| Transcend                        | 1         | 0.04%   |
| Silicon Integrated Systems [SiS] | 1         | 0.04%   |
| Lite-On Technology               | 1         | 0.04%   |
| Lite-On IT Corp. / Plextor       | 1         | 0.04%   |
| Integrated Technology Express    | 1         | 0.04%   |
| INNOGRIT                         | 1         | 0.04%   |
| HighPoint Technologies           | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 265       | 9.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 165       | 5.88%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 92        | 3.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 86        | 3.07%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 83        | 2.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 75        | 2.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 62        | 2.21%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 60        | 2.14%   |
| AMD 400 Series Chipset SATA Controller                                         | 59        | 2.1%    |
| Samsung NVMe SSD Controller 980                                                | 58        | 2.07%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 55        | 1.96%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 46        | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 46        | 1.64%   |
| AMD 500 Series Chipset SATA Controller                                         | 45        | 1.6%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 42        | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 41        | 1.46%   |
| Intel Volume Management Device NVMe RAID Controller                            | 37        | 1.32%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 36        | 1.28%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 35        | 1.25%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 35        | 1.25%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 34        | 1.21%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 33        | 1.18%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 31        | 1.11%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 31        | 1.11%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 25        | 0.89%   |
| Intel Comet Lake SATA AHCI Controller                                          | 24        | 0.86%   |
| Intel SATA Controller [RAID mode]                                              | 23        | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 23        | 0.82%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 23        | 0.82%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 22        | 0.78%   |
| JMicron JMB363 SATA/IDE Controller                                             | 22        | 0.78%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 21        | 0.75%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 21        | 0.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 21        | 0.75%   |
| Intel SSD 660P Series                                                          | 20        | 0.71%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 20        | 0.71%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 20        | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 19        | 0.68%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 18        | 0.64%   |
| Phison E12 NVMe Controller                                                     | 18        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1366      | 56.33%  |
| NVMe | 692       | 28.54%  |
| IDE  | 207       | 8.54%   |
| RAID | 143       | 5.9%    |
| SAS  | 9         | 0.37%   |
| SCSI | 8         | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1348      | 72.2%   |
| AMD      | 500       | 26.78%  |
| ARM      | 18        | 0.96%   |
| Qualcomm | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8565U CPU @ 1.80GHz           | 25        | 1.34%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 24        | 1.28%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 23        | 1.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz          | 19        | 1.02%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 18        | 0.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 18        | 0.96%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 18        | 0.96%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 18        | 0.96%   |
| Intel Core i7-8550U CPU @ 1.80GHz           | 17        | 0.91%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 16        | 0.86%   |
| AMD Ryzen 5 3600 6-Core Processor           | 16        | 0.86%   |
| Intel Core i5-6300U CPU @ 2.40GHz           | 15        | 0.8%    |
| Intel Core i5-6200U CPU @ 2.30GHz           | 15        | 0.8%    |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 14        | 0.75%   |
| Intel Core i7-8750H CPU @ 2.20GHz           | 13        | 0.7%    |
| Intel Core i7-6700K CPU @ 4.00GHz           | 13        | 0.7%    |
| Intel Core i5-6600 CPU @ 3.30GHz            | 13        | 0.7%    |
| Intel Core i5-5200U CPU @ 2.20GHz           | 13        | 0.7%    |
| AMD Ryzen 7 5800X 8-Core Processor          | 13        | 0.7%    |
| Intel Core i7-7500U CPU @ 2.70GHz           | 12        | 0.64%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 12        | 0.64%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 12        | 0.64%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics  | 12        | 0.64%   |
| Intel Core i7-8850H CPU @ 2.60GHz           | 11        | 0.59%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 11        | 0.59%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 11        | 0.59%   |
| ARM Processor                               | 11        | 0.59%   |
| AMD Ryzen 7 4700U with Radeon Graphics      | 11        | 0.59%   |
| AMD Ryzen 5 4500U with Radeon Graphics      | 11        | 0.59%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 11        | 0.59%   |
| AMD FX-8350 Eight-Core Processor            | 11        | 0.59%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 10        | 0.54%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 10        | 0.54%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz           | 10        | 0.54%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 10        | 0.54%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 10        | 0.54%   |
| AMD Custom APU 0405                         | 10        | 0.54%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 9         | 0.48%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 9         | 0.48%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 9         | 0.48%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 426       | 22.81%  |
| Intel Core i7           | 409       | 21.9%   |
| Other                   | 123       | 6.58%   |
| AMD Ryzen 5             | 119       | 6.37%   |
| AMD Ryzen 7             | 114       | 6.1%    |
| Intel Core i3           | 77        | 4.12%   |
| Intel Core 2 Duo        | 69        | 3.69%   |
| Intel Celeron           | 67        | 3.59%   |
| Intel Xeon              | 44        | 2.36%   |
| Intel Pentium           | 38        | 2.03%   |
| Intel Atom              | 34        | 1.82%   |
| AMD Ryzen 9             | 34        | 1.82%   |
| AMD FX                  | 30        | 1.61%   |
| Intel Core i9           | 24        | 1.28%   |
| AMD Ryzen 7 PRO         | 24        | 1.28%   |
| AMD A8                  | 20        | 1.07%   |
| AMD Ryzen 3             | 19        | 1.02%   |
| Intel Pentium Dual-Core | 15        | 0.8%    |
| AMD Phenom II X4        | 15        | 0.8%    |
| AMD A10                 | 12        | 0.64%   |
| Intel Core 2 Quad       | 11        | 0.59%   |
| Intel Core 2            | 10        | 0.54%   |
| AMD A4                  | 10        | 0.54%   |
| AMD Ryzen 5 PRO         | 9         | 0.48%   |
| AMD A6                  | 9         | 0.48%   |
| AMD Phenom II X6        | 8         | 0.43%   |
| Intel Pentium Silver    | 7         | 0.37%   |
| AMD E                   | 6         | 0.32%   |
| AMD Athlon II X4        | 6         | 0.32%   |
| AMD Athlon 64 X2        | 6         | 0.32%   |
| AMD Athlon              | 6         | 0.32%   |
| Intel Genuine           | 5         | 0.27%   |
| ARM BCM                 | 5         | 0.27%   |
| AMD Ryzen Threadripper  | 5         | 0.27%   |
| AMD E2                  | 5         | 0.27%   |
| Intel Xeon Silver       | 4         | 0.21%   |
| AMD E1                  | 4         | 0.21%   |
| AMD Athlon II X2        | 4         | 0.21%   |
| Intel Pentium Dual      | 3         | 0.16%   |
| Intel Pentium 4         | 3         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 753       | 40.25%  |
| 2       | 623       | 33.3%   |
| 6       | 197       | 10.53%  |
| 8       | 189       | 10.1%   |
| 12      | 29        | 1.55%   |
| 16      | 24        | 1.28%   |
| 1       | 19        | 1.02%   |
| 10      | 9         | 0.48%   |
| 14      | 6         | 0.32%   |
| 3       | 6         | 0.32%   |
| Unknown | 6         | 0.32%   |
| 20      | 4         | 0.21%   |
| 24      | 3         | 0.16%   |
| 64      | 1         | 0.05%   |
| 48      | 1         | 0.05%   |
| 40      | 1         | 0.05%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1846      | 98.82%  |
| 2       | 20        | 1.07%   |
| Unknown | 2         | 0.11%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1305      | 69.71%  |
| 1       | 561       | 29.97%  |
| Unknown | 6         | 0.32%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1820      | 97.43%  |
| Unknown        | 38        | 2.03%   |
| 32-bit         | 9         | 0.48%   |
| 64-bit         | 1         | 0.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 500       | 25.69%  |
| 0x206a7    | 104       | 5.34%   |
| 0x306a9    | 100       | 5.14%   |
| 0x306c3    | 81        | 4.16%   |
| 0x806ec    | 58        | 2.98%   |
| 0x1067a    | 48        | 2.47%   |
| 0x506e3    | 46        | 2.36%   |
| 0x806ea    | 44        | 2.26%   |
| 0x906ea    | 43        | 2.21%   |
| 0x806c1    | 42        | 2.16%   |
| 0x406e3    | 37        | 1.9%    |
| 0x306d4    | 36        | 1.85%   |
| 0x906e9    | 31        | 1.59%   |
| 0x08701021 | 31        | 1.59%   |
| 0x40651    | 30        | 1.54%   |
| 0x806e9    | 28        | 1.44%   |
| 0x0a50000c | 24        | 1.23%   |
| 0x08600106 | 24        | 1.23%   |
| 0x506c9    | 18        | 0.92%   |
| 0x08108109 | 18        | 0.92%   |
| 0x20655    | 17        | 0.87%   |
| 0x08701013 | 16        | 0.82%   |
| 0x06000852 | 16        | 0.82%   |
| 0x010000c8 | 16        | 0.82%   |
| 0x706e5    | 15        | 0.77%   |
| 0x106e5    | 15        | 0.77%   |
| 0x10676    | 15        | 0.77%   |
| 0x406c4    | 14        | 0.72%   |
| 0x08600103 | 14        | 0.72%   |
| 0x08108102 | 14        | 0.72%   |
| 0x0800820d | 14        | 0.72%   |
| 0x06001119 | 14        | 0.72%   |
| 0x706a8    | 12        | 0.62%   |
| 0x0a201016 | 12        | 0.62%   |
| 0xa0652    | 11        | 0.57%   |
| 0x906ed    | 11        | 0.57%   |
| 0x806eb    | 11        | 0.57%   |
| 0x406c3    | 11        | 0.57%   |
| 0x30678    | 11        | 0.57%   |
| 0x08608103 | 11        | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 305       | 16.33%  |
| Haswell          | 158       | 8.46%   |
| SandyBridge      | 138       | 7.39%   |
| IvyBridge        | 134       | 7.17%   |
| Zen 2            | 133       | 7.12%   |
| Skylake          | 125       | 6.69%   |
| Penryn           | 80        | 4.28%   |
| Unknown          | 77        | 4.12%   |
| Zen 3            | 74        | 3.96%   |
| Zen+             | 61        | 3.27%   |
| TigerLake        | 56        | 3%      |
| Broadwell        | 46        | 2.46%   |
| Silvermont       | 44        | 2.36%   |
| Piledriver       | 40        | 2.14%   |
| K10              | 40        | 2.14%   |
| Westmere         | 39        | 2.09%   |
| CometLake        | 36        | 1.93%   |
| Zen              | 33        | 1.77%   |
| Core             | 32        | 1.71%   |
| IceLake          | 28        | 1.5%    |
| Nehalem          | 25        | 1.34%   |
| Goldmont plus    | 23        | 1.23%   |
| Goldmont         | 21        | 1.12%   |
| Excavator        | 18        | 0.96%   |
| Alderlake Hybrid | 18        | 0.96%   |
| Puma             | 14        | 0.75%   |
| Bonnell          | 12        | 0.64%   |
| Bobcat           | 12        | 0.64%   |
| K8 Hammer        | 10        | 0.54%   |
| Steamroller      | 7         | 0.37%   |
| K10 Llano        | 7         | 0.37%   |
| Jaguar           | 6         | 0.32%   |
| NetBurst         | 4         | 0.21%   |
| Bulldozer        | 4         | 0.21%   |
| Tremont          | 3         | 0.16%   |
| P6               | 3         | 0.16%   |
| K8 & K10 hybrid  | 2         | 0.11%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 969       | 44.94%  |
| Nvidia                           | 615       | 28.53%  |
| AMD                              | 551       | 25.56%  |
| Matrox Electronics Systems       | 10        | 0.46%   |
| ASPEED Technology                | 8         | 0.37%   |
| ATI Technologies                 | 2         | 0.09%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 91        | 4.12%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 78        | 3.53%   |
| AMD Renoir                                                                               | 64        | 2.9%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 52        | 2.36%   |
| Intel UHD Graphics 620                                                                   | 49        | 2.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 43        | 1.95%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 41        | 1.86%   |
| Intel HD Graphics 620                                                                    | 40        | 1.81%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 37        | 1.68%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 36        | 1.63%   |
| Intel HD Graphics 5500                                                                   | 35        | 1.59%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 34        | 1.54%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 33        | 1.49%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 33        | 1.49%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 32        | 1.45%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 31        | 1.4%    |
| Intel HD Graphics 530                                                                    | 31        | 1.4%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 31        | 1.4%    |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 24        | 1.09%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 22        | 1%      |
| Intel HD Graphics 630                                                                    | 22        | 1%      |
| Intel Core Processor Integrated Graphics Controller                                      | 22        | 1%      |
| Intel GeminiLake [UHD Graphics 600]                                                      | 20        | 0.91%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 18        | 0.82%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 18        | 0.82%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 17        | 0.77%   |
| AMD Lucienne                                                                             | 17        | 0.77%   |
| Nvidia GP108M [GeForce MX250]                                                            | 16        | 0.72%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 16        | 0.72%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 16        | 0.72%   |
| Intel HD Graphics 500                                                                    | 15        | 0.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 14        | 0.63%   |
| Intel Iris Plus Graphics G7                                                              | 14        | 0.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 14        | 0.63%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 13        | 0.59%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                      | 13        | 0.59%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 12        | 0.54%   |
| Nvidia TU104 [GeForce RTX 2070 SUPER]                                                    | 11        | 0.5%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 11        | 0.5%    |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 11        | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 700       | 37.15%  |
| 1 x AMD                 | 455       | 24.15%  |
| 1 x Nvidia              | 378       | 20.06%  |
| Intel + Nvidia          | 206       | 10.93%  |
| Intel + AMD             | 45        | 2.39%   |
| 2 x AMD                 | 29        | 1.54%   |
| AMD + Nvidia            | 25        | 1.33%   |
| Other                   | 20        | 1.06%   |
| 1 x Matrox              | 9         | 0.48%   |
| 1 x ASPEED              | 6         | 0.32%   |
| 2 x Nvidia              | 4         | 0.21%   |
| Nvidia + ASPEED         | 3         | 0.16%   |
| 2 x Intel               | 2         | 0.11%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.05%   |
| 1 x SiS                 | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1496      | 78.94%  |
| Proprietary | 320       | 16.89%  |
| Unknown     | 79        | 4.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1031      | 53.59%  |
| 1.01-2.0   | 229       | 11.9%   |
| 0.01-0.5   | 203       | 10.55%  |
| 0.51-1.0   | 140       | 7.28%   |
| 3.01-4.0   | 135       | 7.02%   |
| 7.01-8.0   | 96        | 4.99%   |
| 5.01-6.0   | 46        | 2.39%   |
| 8.01-16.0  | 27        | 1.4%    |
| 2.01-3.0   | 11        | 0.57%   |
| 16.01-24.0 | 5         | 0.26%   |
| 4.01-5.0   | 1         | 0.05%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 303       | 14.45%  |
| AU Optronics            | 254       | 12.11%  |
| LG Display              | 182       | 8.68%   |
| Chimei Innolux          | 136       | 6.49%   |
| BOE                     | 125       | 5.96%   |
| Dell                    | 101       | 4.82%   |
| BenQ                    | 96        | 4.58%   |
| Goldstar                | 77        | 3.67%   |
| Hewlett-Packard         | 71        | 3.39%   |
| Acer                    | 68        | 3.24%   |
| AOC                     | 58        | 2.77%   |
| Lenovo                  | 53        | 2.53%   |
| Philips                 | 47        | 2.24%   |
| Iiyama                  | 47        | 2.24%   |
| Apple                   | 40        | 1.91%   |
| Sharp                   | 39        | 1.86%   |
| Ancor Communications    | 36        | 1.72%   |
| Eizo                    | 32        | 1.53%   |
| Gericom                 | 24        | 1.14%   |
| Medion                  | 23        | 1.1%    |
| Chi Mei Optoelectronics | 21        | 1%      |
| Fujitsu Siemens         | 17        | 0.81%   |
| ViewSonic               | 14        | 0.67%   |
| NEC Computers           | 13        | 0.62%   |
| InfoVision              | 13        | 0.62%   |
| PANDA                   | 12        | 0.57%   |
| Sony                    | 11        | 0.52%   |
| Unknown                 | 10        | 0.48%   |
| ASUSTek Computer        | 10        | 0.48%   |
| LG Philips              | 9         | 0.43%   |
| HannStar                | 9         | 0.43%   |
| CSO                     | 9         | 0.43%   |
| Valve                   | 8         | 0.38%   |
| Toshiba                 | 8         | 0.38%   |
| Vestel Elektronik       | 6         | 0.29%   |
| LG Electronics          | 6         | 0.29%   |
| Idek Iiyama             | 5         | 0.24%   |
| GRM                     | 5         | 0.24%   |
| CPT                     | 5         | 0.24%   |
| TMX                     | 4         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch  | 11        | 0.5%    |
| AU Optronics LCD Monitor AUO573D 1920x1080 309x174mm 14.0-inch    | 10        | 0.45%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch      | 9         | 0.41%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch       | 9         | 0.41%   |
| Gericom Q26 QMX2426 1920x1080 550x344mm 25.5-inch                 | 9         | 0.41%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch    | 9         | 0.41%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch      | 8         | 0.36%   |
| BenQ GL2450H BNQ78A7 1920x1080 531x298mm 24.0-inch                | 8         | 0.36%   |
| Apple Color LCD APPA040 2880x1800 331x207mm 15.4-inch             | 8         | 0.36%   |
| Acer B193 ACR001D 1280x1024 376x301mm 19.0-inch                   | 8         | 0.36%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch               | 7         | 0.32%   |
| NEC Computers EA243WM NEC6864 1920x1200 519x324mm 24.1-inch       | 7         | 0.32%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch      | 7         | 0.32%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                 | 7         | 0.32%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch  | 7         | 0.32%   |
| AU Optronics LCD Monitor AUO683D 1920x1080 309x174mm 14.0-inch    | 7         | 0.32%   |
| Vestel Elektronik 40W_LCD_TV VES3700 1920x540                     | 6         | 0.27%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch | 6         | 0.27%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch | 6         | 0.27%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch | 6         | 0.27%   |
| Lenovo LCD Monitor LEN40B1 1600x900 344x194mm 15.5-inch           | 6         | 0.27%   |
| Gericom Q24 QMX2421 1920x1080 521x293mm 23.5-inch                 | 6         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch  | 6         | 0.27%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch  | 6         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch  | 6         | 0.27%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch     | 6         | 0.27%   |
| Samsung Electronics U28E590 SAM0C4C 3840x2160 608x345mm 27.5-inch | 5         | 0.23%   |
| Samsung Electronics S34J55x SAM0F70 3440x1440 797x333mm 34.0-inch | 5         | 0.23%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch      | 5         | 0.23%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch       | 5         | 0.23%   |
| GRM GM2600 GRM5BC6 1920x1200 550x344mm 25.5-inch                  | 5         | 0.23%   |
| Goldstar ULTRAWIDE GSM59F2 2560x1080 798x334mm 34.1-inch          | 5         | 0.23%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch  | 5         | 0.23%   |
| Chimei Innolux LCD Monitor CMN1239 1920x1080 276x155mm 12.5-inch  | 5         | 0.23%   |
| BOE LCD Monitor BOE084E 1920x1080 382x215mm 17.3-inch             | 5         | 0.23%   |
| AU Optronics LCD Monitor AUO2036 2560x1440 309x174mm 14.0-inch    | 5         | 0.23%   |
| AU Optronics LCD Monitor AUO123D 1920x1080 309x173mm 13.9-inch    | 5         | 0.23%   |
| AOC 24G2W1G4 AOC2402 1920x1080 527x296mm 23.8-inch                | 5         | 0.23%   |
| Ancor Communications VS248 ACI2498 1920x1080 531x299mm 24.0-inch  | 5         | 0.23%   |
| Samsung Electronics U28E570 SAM0D6F 3840x2160 607x345mm 27.5-inch | 4         | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 921       | 45.62%  |
| 1366x768 (WXGA)    | 200       | 9.91%   |
| 3840x2160 (4K)     | 170       | 8.42%   |
| 2560x1440 (QHD)    | 134       | 6.64%   |
| 1600x900 (HD+)     | 88        | 4.36%   |
| 1920x1200 (WUXGA)  | 77        | 3.81%   |
| 1680x1050 (WSXGA+) | 76        | 3.76%   |
| 1280x1024 (SXGA)   | 64        | 3.17%   |
| 1280x800 (WXGA)    | 45        | 2.23%   |
| 3440x1440          | 35        | 1.73%   |
| 1440x900 (WXGA+)   | 31        | 1.54%   |
| Unknown            | 23        | 1.14%   |
| 2560x1080          | 16        | 0.79%   |
| 2560x1600          | 15        | 0.74%   |
| 3840x1080          | 14        | 0.69%   |
| 2880x1800          | 13        | 0.64%   |
| 1920x540           | 10        | 0.5%    |
| 800x1280           | 9         | 0.45%   |
| 3840x2400          | 9         | 0.45%   |
| 1024x600           | 6         | 0.3%    |
| 3200x1800 (QHD+)   | 4         | 0.2%    |
| 2736x1824          | 4         | 0.2%    |
| 2288x1287          | 4         | 0.2%    |
| 2160x1440          | 4         | 0.2%    |
| 2048x1152          | 4         | 0.2%    |
| 1600x1200          | 4         | 0.2%    |
| 1024x768 (XGA)     | 4         | 0.2%    |
| 2160x1200          | 3         | 0.15%   |
| 1920x1280          | 3         | 0.15%   |
| 5760x2160          | 2         | 0.1%    |
| 5760x1080          | 2         | 0.1%    |
| 5120x1440          | 2         | 0.1%    |
| 4480x1440          | 2         | 0.1%    |
| 3456x2160          | 2         | 0.1%    |
| 3360x1050          | 2         | 0.1%    |
| 1360x768           | 2         | 0.1%    |
| 6400x1440          | 1         | 0.05%   |
| 3840x2560          | 1         | 0.05%   |
| 3840x1600          | 1         | 0.05%   |
| 3840x1200          | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 410       | 19.52%  |
| 27      | 204       | 9.71%   |
| 24      | 200       | 9.52%   |
| 13      | 176       | 8.38%   |
| 14      | 161       | 7.67%   |
| 17      | 132       | 6.29%   |
| 23      | 128       | 6.1%    |
| Unknown | 102       | 4.86%   |
| 21      | 72        | 3.43%   |
| 31      | 59        | 2.81%   |
| 19      | 58        | 2.76%   |
| 22      | 53        | 2.52%   |
| 12      | 48        | 2.29%   |
| 34      | 43        | 2.05%   |
| 25      | 33        | 1.57%   |
| 11      | 21        | 1%      |
| 20      | 20        | 0.95%   |
| 84      | 18        | 0.86%   |
| 54      | 16        | 0.76%   |
| 16      | 15        | 0.71%   |
| 40      | 13        | 0.62%   |
| 18      | 12        | 0.57%   |
| 10      | 11        | 0.52%   |
| 28      | 10        | 0.48%   |
| 7       | 8         | 0.38%   |
| 72      | 7         | 0.33%   |
| 32      | 7         | 0.33%   |
| 48      | 6         | 0.29%   |
| 26      | 6         | 0.29%   |
| 65      | 5         | 0.24%   |
| 35      | 5         | 0.24%   |
| 42      | 4         | 0.19%   |
| 33      | 4         | 0.19%   |
| 142     | 3         | 0.14%   |
| 36      | 3         | 0.14%   |
| 29      | 3         | 0.14%   |
| 3       | 3         | 0.14%   |
| 75      | 2         | 0.1%    |
| 52      | 2         | 0.1%    |
| 49      | 2         | 0.1%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 661       | 32.21%  |
| 501-600        | 483       | 23.54%  |
| 351-400        | 190       | 9.26%   |
| 201-300        | 178       | 8.67%   |
| 401-500        | 162       | 7.89%   |
| 601-700        | 115       | 5.6%    |
| Unknown        | 102       | 4.97%   |
| 701-800        | 55        | 2.68%   |
| 1001-1500      | 38        | 1.85%   |
| 1501-2000      | 28        | 1.36%   |
| 801-900        | 21        | 1.02%   |
| 1-100          | 9         | 0.44%   |
| 901-1000       | 6         | 0.29%   |
| More than 2000 | 3         | 0.15%   |
| 101-200        | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1366      | 71.97%  |
| 16/10   | 283       | 14.91%  |
| Unknown | 79        | 4.16%   |
| 5/4     | 65        | 3.42%   |
| 21/9    | 48        | 2.53%   |
| 3/2     | 19        | 1%      |
| 32/9    | 11        | 0.58%   |
| 4/3     | 9         | 0.47%   |
| 0.67    | 7         | 0.37%   |
| 6/5     | 6         | 0.32%   |
| 1.00    | 3         | 0.16%   |
| 0.80    | 1         | 0.05%   |
| 0.56    | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 412       | 19.84%  |
| 201-250        | 338       | 16.27%  |
| 81-90          | 256       | 12.33%  |
| 301-350        | 207       | 9.97%   |
| 351-500        | 129       | 6.21%   |
| 251-300        | 113       | 5.44%   |
| 151-200        | 106       | 5.1%    |
| Unknown        | 102       | 4.91%   |
| 121-130        | 101       | 4.86%   |
| 71-80          | 83        | 4%      |
| More than 1000 | 58        | 2.79%   |
| 61-70          | 45        | 2.17%   |
| 501-1000       | 34        | 1.64%   |
| 51-60          | 22        | 1.06%   |
| 141-150        | 21        | 1.01%   |
| 131-140        | 19        | 0.91%   |
| 41-50          | 10        | 0.48%   |
| 1-40           | 10        | 0.48%   |
| 111-120        | 9         | 0.43%   |
| 91-100         | 2         | 0.1%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 681       | 33.95%  |
| 121-160       | 581       | 28.96%  |
| 101-120       | 413       | 20.59%  |
| 161-240       | 137       | 6.83%   |
| Unknown       | 102       | 5.08%   |
| More than 240 | 53        | 2.64%   |
| 1-50          | 39        | 1.94%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1444      | 75.52%  |
| 2     | 325       | 17%     |
| 0     | 82        | 4.29%   |
| 3     | 56        | 2.93%   |
| 4     | 5         | 0.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Intel                             | 1040      | 37.08%  |
| Realtek Semiconductor             | 917       | 32.69%  |
| Qualcomm Atheros                  | 243       | 8.66%   |
| Broadcom                          | 122       | 4.35%   |
| Marvell Technology Group          | 27        | 0.96%   |
| Ralink Technology                 | 26        | 0.93%   |
| Ralink                            | 26        | 0.93%   |
| Broadcom Limited                  | 26        | 0.93%   |
| TP-Link                           | 24        | 0.86%   |
| MediaTek                          | 22        | 0.78%   |
| Nvidia                            | 20        | 0.71%   |
| Sierra Wireless                   | 18        | 0.64%   |
| Dell                              | 17        | 0.61%   |
| Ericsson Business Mobile Networks | 16        | 0.57%   |
| ASIX Electronics                  | 16        | 0.57%   |
| NetGear                           | 15        | 0.53%   |
| Microsoft                         | 13        | 0.46%   |
| Lenovo                            | 13        | 0.46%   |
| IMC Networks                      | 13        | 0.46%   |
| Huawei Technologies               | 13        | 0.46%   |
| Edimax Technology                 | 13        | 0.46%   |
| Aquantia                          | 13        | 0.46%   |
| ASUSTek Computer                  | 12        | 0.43%   |
| Samsung Electronics               | 10        | 0.36%   |
| Hewlett-Packard                   | 10        | 0.36%   |
| Fibocom                           | 10        | 0.36%   |
| DisplayLink                       | 10        | 0.36%   |
| D-Link System                     | 9         | 0.32%   |
| Qualcomm Atheros Communications   | 7         | 0.25%   |
| Qualcomm                          | 6         | 0.21%   |
| Google                            | 6         | 0.21%   |
| D-Link                            | 6         | 0.21%   |
| Xiaomi                            | 4         | 0.14%   |
| OnePlus Technology (Shenzhen)     | 4         | 0.14%   |
| JMicron Technology                | 4         | 0.14%   |
| ZyXEL Communications              | 3         | 0.11%   |
| VIA Technologies                  | 3         | 0.11%   |
| Sigma Sport                       | 3         | 0.11%   |
| Motorola PCS                      | 3         | 0.11%   |
| Microchip Technology              | 3         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 663       | 19.63%  |
| Intel Wi-Fi 6 AX200                                               | 122       | 3.61%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 83        | 2.46%   |
| Intel Wireless 8265 / 8275                                        | 69        | 2.04%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 60        | 1.78%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 58        | 1.72%   |
| Intel I211 Gigabit Network Connection                             | 52        | 1.54%   |
| Intel Wireless 7265                                               | 46        | 1.36%   |
| Realtek RTL8125 2.5GbE Controller                                 | 44        | 1.3%    |
| Intel Wi-Fi 6 AX201                                               | 43        | 1.27%   |
| Intel Ethernet Connection (2) I219-V                              | 42        | 1.24%   |
| Intel Wireless 8260                                               | 40        | 1.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 39        | 1.15%   |
| Intel Ethernet Controller I225-V                                  | 38        | 1.13%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 34        | 1.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 33        | 0.98%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 33        | 0.98%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 31        | 0.92%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 29        | 0.86%   |
| Intel Wireless 3165                                               | 29        | 0.86%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 28        | 0.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 28        | 0.83%   |
| Intel Wireless 7260                                               | 28        | 0.83%   |
| Intel Wireless-AC 9260                                            | 27        | 0.8%    |
| Intel Ethernet Connection I217-LM                                 | 27        | 0.8%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 25        | 0.74%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 25        | 0.74%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 24        | 0.71%   |
| Intel Ethernet Connection (6) I219-V                              | 23        | 0.68%   |
| Intel Centrino Ultimate-N 6300                                    | 22        | 0.65%   |
| Intel 82579V Gigabit Network Connection                           | 21        | 0.62%   |
| Intel Ethernet Connection I219-LM                                 | 20        | 0.59%   |
| Intel Ethernet Connection (7) I219-V                              | 20        | 0.59%   |
| Intel Ethernet Connection (4) I219-V                              | 20        | 0.59%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 19        | 0.56%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 17        | 0.5%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 17        | 0.5%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17        | 0.5%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 17        | 0.5%    |
| Intel I210 Gigabit Network Connection                             | 17        | 0.5%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 774       | 50.92%  |
| Realtek Semiconductor                 | 226       | 14.87%  |
| Qualcomm Atheros                      | 176       | 11.58%  |
| Broadcom                              | 86        | 5.66%   |
| Ralink Technology                     | 26        | 1.71%   |
| Ralink                                | 26        | 1.71%   |
| TP-Link                               | 24        | 1.58%   |
| MediaTek                              | 21        | 1.38%   |
| Sierra Wireless                       | 18        | 1.18%   |
| NetGear                               | 14        | 0.92%   |
| IMC Networks                          | 13        | 0.86%   |
| Edimax Technology                     | 13        | 0.86%   |
| Microsoft                             | 12        | 0.79%   |
| Broadcom Limited                      | 12        | 0.79%   |
| ASUSTek Computer                      | 12        | 0.79%   |
| Dell                                  | 11        | 0.72%   |
| Fibocom                               | 10        | 0.66%   |
| Qualcomm Atheros Communications       | 7         | 0.46%   |
| D-Link System                         | 7         | 0.46%   |
| Qualcomm                              | 5         | 0.33%   |
| Ericsson Business Mobile Networks     | 4         | 0.26%   |
| D-Link                                | 4         | 0.26%   |
| ZyXEL Communications                  | 3         | 0.2%    |
| Marvell Technology Group              | 3         | 0.2%    |
| Sitecom Europe                        | 2         | 0.13%   |
| AVM                                   | 2         | 0.13%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.13%   |
| ZyDAS                                 | 1         | 0.07%   |
| Wilocity                              | 1         | 0.07%   |
| Philips (or NXP)                      | 1         | 0.07%   |
| Linksys                               | 1         | 0.07%   |
| Hewlett-Packard                       | 1         | 0.07%   |
| BUFFALO                               | 1         | 0.07%   |
| Belkin Components                     | 1         | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 122       | 7.99%   |
| Intel Wireless 8265 / 8275                                              | 69        | 4.52%   |
| Intel Wireless 7265                                                     | 46        | 3.01%   |
| Intel Wi-Fi 6 AX201                                                     | 43        | 2.82%   |
| Intel Wireless 8260                                                     | 40        | 2.62%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 39        | 2.55%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 34        | 2.23%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 33        | 2.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 33        | 2.16%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 31        | 2.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 29        | 1.9%    |
| Intel Wireless 3165                                                     | 29        | 1.9%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 28        | 1.83%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 28        | 1.83%   |
| Intel Wireless 7260                                                     | 28        | 1.83%   |
| Intel Wireless-AC 9260                                                  | 27        | 1.77%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 25        | 1.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 25        | 1.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 24        | 1.57%   |
| Intel Centrino Ultimate-N 6300                                          | 22        | 1.44%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 19        | 1.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 17        | 1.11%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 17        | 1.11%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 17        | 1.11%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 15        | 0.98%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                         | 15        | 0.98%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 15        | 0.98%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 14        | 0.92%   |
| Intel WiFi Link 5100                                                    | 14        | 0.92%   |
| Broadcom BCM43142 802.11b/g/n                                           | 14        | 0.92%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 13        | 0.85%   |
| Intel Centrino Advanced-N 6235                                          | 12        | 0.79%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 11        | 0.72%   |
| Intel Wireless 3160                                                     | 11        | 0.72%   |
| Intel Centrino Wireless-N 2230                                          | 11        | 0.72%   |
| Edimax EW-7811Un 802.11n Wireless Adapter [Realtek RTL8188CUS]          | 11        | 0.72%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 11        | 0.72%   |
| Sierra Wireless EM7455                                                  | 10        | 0.65%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 10        | 0.65%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 10        | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 828       | 47.4%   |
| Intel                         | 601       | 34.4%   |
| Qualcomm Atheros              | 92        | 5.27%   |
| Broadcom                      | 53        | 3.03%   |
| Marvell Technology Group      | 24        | 1.37%   |
| Nvidia                        | 20        | 1.14%   |
| ASIX Electronics              | 16        | 0.92%   |
| Broadcom Limited              | 14        | 0.8%    |
| Aquantia                      | 13        | 0.74%   |
| Lenovo                        | 12        | 0.69%   |
| Samsung Electronics           | 10        | 0.57%   |
| DisplayLink                   | 10        | 0.57%   |
| Google                        | 6         | 0.34%   |
| Huawei Technologies           | 5         | 0.29%   |
| Xiaomi                        | 4         | 0.23%   |
| OnePlus Technology (Shenzhen) | 4         | 0.23%   |
| JMicron Technology            | 4         | 0.23%   |
| VIA Technologies              | 3         | 0.17%   |
| Motorola PCS                  | 3         | 0.17%   |
| ZTE WCDMA Technologies MSM    | 2         | 0.11%   |
| Hewlett-Packard               | 2         | 0.11%   |
| Dell                          | 2         | 0.11%   |
| D-Link System                 | 2         | 0.11%   |
| D-Link                        | 2         | 0.11%   |
| Apple                         | 2         | 0.11%   |
| Research In Motion            | 1         | 0.06%   |
| Qualcomm                      | 1         | 0.06%   |
| NetGear                       | 1         | 0.06%   |
| Microsoft                     | 1         | 0.06%   |
| Microchip Technology          | 1         | 0.06%   |
| Mellanox Technologies         | 1         | 0.06%   |
| MediaTek                      | 1         | 0.06%   |
| Linksys                       | 1         | 0.06%   |
| Insyde Software               | 1         | 0.06%   |
| IBM                           | 1         | 0.06%   |
| Emulex                        | 1         | 0.06%   |
| Cypress Semiconductor         | 1         | 0.06%   |
| Attansic Technology           | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 663       | 36.87%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 83        | 4.62%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 60        | 3.34%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 58        | 3.23%   |
| Intel I211 Gigabit Network Connection                             | 52        | 2.89%   |
| Realtek RTL8125 2.5GbE Controller                                 | 44        | 2.45%   |
| Intel Ethernet Connection (2) I219-V                              | 42        | 2.34%   |
| Intel Ethernet Controller I225-V                                  | 38        | 2.11%   |
| Intel Ethernet Connection I217-LM                                 | 27        | 1.5%    |
| Intel Ethernet Connection (6) I219-V                              | 23        | 1.28%   |
| Intel 82579V Gigabit Network Connection                           | 21        | 1.17%   |
| Intel Ethernet Connection I219-LM                                 | 20        | 1.11%   |
| Intel Ethernet Connection (7) I219-V                              | 20        | 1.11%   |
| Intel Ethernet Connection (4) I219-V                              | 20        | 1.11%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 17        | 0.95%   |
| Intel I210 Gigabit Network Connection                             | 17        | 0.95%   |
| Intel 82577LM Gigabit Network Connection                          | 16        | 0.89%   |
| Intel 82567LM Gigabit Network Connection                          | 16        | 0.89%   |
| Intel Ethernet Connection (3) I218-LM                             | 15        | 0.83%   |
| Intel Ethernet Connection (2) I219-LM                             | 15        | 0.83%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 14        | 0.78%   |
| Intel Ethernet Connection I218-LM                                 | 14        | 0.78%   |
| Intel Ethernet Connection (7) I219-LM                             | 14        | 0.78%   |
| Intel Ethernet Connection I217-V                                  | 13        | 0.72%   |
| Intel Ethernet Connection (10) I219-V                             | 13        | 0.72%   |
| Intel 82574L Gigabit Network Connection                           | 13        | 0.72%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.61%   |
| Intel Ethernet Connection (4) I219-LM                             | 11        | 0.61%   |
| Intel Ethernet Connection (2) I218-V                              | 11        | 0.61%   |
| ASIX AX88179 Gigabit Ethernet                                     | 11        | 0.61%   |
| Intel Ethernet Connection I219-V                                  | 9         | 0.5%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 8         | 0.44%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.44%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 8         | 0.44%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 8         | 0.44%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 7         | 0.39%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 7         | 0.39%   |
| Nvidia MCP79 Ethernet                                             | 7         | 0.39%   |
| Intel I350 Gigabit Network Connection                             | 7         | 0.39%   |
| Intel Ethernet Connection (13) I219-V                             | 7         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1622      | 52.75%  |
| WiFi     | 1403      | 45.63%  |
| Modem    | 46        | 1.5%    |
| Unknown  | 4         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1053      | 54.67%  |
| Ethernet | 873       | 45.33%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 992       | 53.05%  |
| 1     | 755       | 40.37%  |
| 3     | 62        | 3.32%   |
| 0     | 41        | 2.19%   |
| 4     | 10        | 0.53%   |
| 5     | 4         | 0.21%   |
| 6     | 3         | 0.16%   |
| 12    | 2         | 0.11%   |
| 13    | 1         | 0.05%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1646      | 86.86%  |
| Yes  | 249       | 13.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 609       | 54.13%  |
| Realtek Semiconductor           | 110       | 9.78%   |
| Cambridge Silicon Radio         | 68        | 6.04%   |
| Qualcomm Atheros Communications | 59        | 5.24%   |
| Broadcom                        | 55        | 4.89%   |
| IMC Networks                    | 38        | 3.38%   |
| Lite-On Technology              | 30        | 2.67%   |
| Apple                           | 30        | 2.67%   |
| Foxconn / Hon Hai               | 25        | 2.22%   |
| ASUSTek Computer                | 19        | 1.69%   |
| Hewlett-Packard                 | 15        | 1.33%   |
| Dell                            | 14        | 1.24%   |
| Toshiba                         | 9         | 0.8%    |
| MediaTek                        | 6         | 0.53%   |
| Ralink                          | 5         | 0.44%   |
| Marvell Semiconductor           | 5         | 0.44%   |
| Foxconn International           | 5         | 0.44%   |
| Belkin Components               | 4         | 0.36%   |
| TP-Link                         | 3         | 0.27%   |
| HTC (High Tech Computer)        | 3         | 0.27%   |
| USI                             | 2         | 0.18%   |
| Realtek                         | 2         | 0.18%   |
| Edimax Technology               | 2         | 0.18%   |
| D-Link System                   | 2         | 0.18%   |
| Alps Electric                   | 2         | 0.18%   |
| Micro Star International        | 1         | 0.09%   |
| Logitech                        | 1         | 0.09%   |
| i.Tech Dynamic Limited          | 1         | 0.09%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 211       | 18.76%  |
| Intel AX200 Bluetooth                               | 120       | 10.67%  |
| Intel AX201 Bluetooth                               | 109       | 9.69%   |
| Realtek Bluetooth Radio                             | 81        | 7.2%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 68        | 6.04%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 60        | 5.33%   |
| Intel Bluetooth Device                              | 35        | 3.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 25        | 2.22%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 22        | 1.96%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 20        | 1.78%   |
| Realtek  Bluetooth 4.2 Adapter                      | 19        | 1.69%   |
| IMC Networks Bluetooth Radio                        | 18        | 1.6%    |
| Intel AX210 Bluetooth                               | 17        | 1.51%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 16        | 1.42%   |
| Broadcom BCM2045B (BDC-2.1)                         | 14        | 1.24%   |
| Apple Bluetooth Host Controller                     | 13        | 1.16%   |
| Qualcomm Atheros  Bluetooth Device                  | 12        | 1.07%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 12        | 1.07%   |
| Foxconn / Hon Hai Bluetooth Device                  | 11        | 0.98%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 10        | 0.89%   |
| HP Broadcom 2070 Bluetooth Combo                    | 9         | 0.8%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 9         | 0.8%    |
| Apple Bluetooth USB Host Controller                 | 9         | 0.8%    |
| IMC Networks Bluetooth Device                       | 8         | 0.71%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 7         | 0.62%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 0.62%   |
| Lite-On Bluetooth Device                            | 7         | 0.62%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 7         | 0.62%   |
| IMC Networks Wireless_Device                        | 6         | 0.53%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 6         | 0.53%   |
| Broadcom HP Portable SoftSailing                    | 6         | 0.53%   |
| Ralink RT3290 Bluetooth                             | 5         | 0.44%   |
| MediaTek Wireless_Device                            | 5         | 0.44%   |
| Lite-On Atheros AR3012 Bluetooth                    | 5         | 0.44%   |
| Foxconn International BCM43142A0 Bluetooth module   | 5         | 0.44%   |
| Dell BCM20702A0 Bluetooth Module                    | 5         | 0.44%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 5         | 0.44%   |
| Lite-On Wireless_Device                             | 4         | 0.36%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller     | 4         | 0.36%   |
| Broadcom BCM2045 Bluetooth                          | 4         | 0.36%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 1279      | 47.71%  |
| AMD                                          | 599       | 22.34%  |
| Nvidia                                       | 455       | 16.97%  |
| C-Media Electronics                          | 62        | 2.31%   |
| Logitech                                     | 31        | 1.16%   |
| GN Netcom                                    | 20        | 0.75%   |
| Lenovo                                       | 13        | 0.48%   |
| Creative Labs                                | 13        | 0.48%   |
| Realtek Semiconductor                        | 12        | 0.45%   |
| SteelSeries ApS                              | 11        | 0.41%   |
| Texas Instruments                            | 10        | 0.37%   |
| Apple                                        | 10        | 0.37%   |
| Razer USA                                    | 9         | 0.34%   |
| ASUSTek Computer                             | 9         | 0.34%   |
| Hewlett-Packard                              | 8         | 0.3%    |
| JMTek                                        | 7         | 0.26%   |
| Focusrite-Novation                           | 7         | 0.26%   |
| Kingston Technology                          | 6         | 0.22%   |
| Creative Technology                          | 6         | 0.22%   |
| Sony                                         | 5         | 0.19%   |
| RODE Microphones                             | 5         | 0.19%   |
| Plantronics                                  | 5         | 0.19%   |
| Corsair                                      | 5         | 0.19%   |
| Bose                                         | 5         | 0.19%   |
| Generalplus Technology                       | 4         | 0.15%   |
| Zoran Co. Personal Media Division (Nogatech) | 3         | 0.11%   |
| Sennheiser Communications                    | 3         | 0.11%   |
| Micro Star International                     | 3         | 0.11%   |
| GYROCOM C&C                                  | 3         | 0.11%   |
| Asahi Kasei Microsystems                     | 3         | 0.11%   |
| ZOOM                                         | 2         | 0.07%   |
| Yamaha                                       | 2         | 0.07%   |
| XMOS                                         | 2         | 0.07%   |
| Thomann                                      | 2         | 0.07%   |
| SAVITECH                                     | 2         | 0.07%   |
| Samson Technologies                          | 2         | 0.07%   |
| Project                                      | 2         | 0.07%   |
| Microsoft                                    | 2         | 0.07%   |
| Microdia                                     | 2         | 0.07%   |
| M-Audio                                      | 2         | 0.07%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 189       | 5.92%   |
| Intel Sunrise Point-LP HD Audio                                            | 143       | 4.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 130       | 4.07%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 121       | 3.79%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 112       | 3.51%   |
| AMD Starship/Matisse HD Audio Controller                                   | 94        | 2.94%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 92        | 2.88%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 72        | 2.25%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 70        | 2.19%   |
| Intel Cannon Lake PCH cAVS                                                 | 68        | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 58        | 1.82%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 56        | 1.75%   |
| AMD FCH Azalia Controller                                                  | 54        | 1.69%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 51        | 1.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 51        | 1.6%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 45        | 1.41%   |
| Intel Comet Lake PCH-LP cAVS                                               | 44        | 1.38%   |
| Intel Broadwell-U Audio Controller                                         | 43        | 1.35%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 41        | 1.28%   |
| Intel Haswell-ULT HD Audio Controller                                      | 39        | 1.22%   |
| Intel 8 Series HD Audio Controller                                         | 39        | 1.22%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 38        | 1.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 37        | 1.16%   |
| Nvidia GP107GL High Definition Audio Controller                            | 34        | 1.06%   |
| Intel 200 Series PCH HD Audio                                              | 34        | 1.06%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 32        | 1%      |
| AMD Kabini HDMI/DP Audio                                                   | 30        | 0.94%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 29        | 0.91%   |
| Nvidia GP106 High Definition Audio Controller                              | 28        | 0.88%   |
| Nvidia GP104 High Definition Audio Controller                              | 28        | 0.88%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 27        | 0.85%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 26        | 0.81%   |
| Nvidia TU106 High Definition Audio Controller                              | 25        | 0.78%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 25        | 0.78%   |
| Intel Comet Lake PCH cAVS                                                  | 24        | 0.75%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 24        | 0.75%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 23        | 0.72%   |
| Nvidia GM204 High Definition Audio Controller                              | 23        | 0.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 23        | 0.72%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 22        | 0.69%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Samsung Electronics   | 266       | 22.15%  |
| SK hynix              | 190       | 15.82%  |
| Kingston              | 149       | 12.41%  |
| Micron Technology     | 126       | 10.49%  |
| Corsair               | 115       | 9.58%   |
| Crucial               | 101       | 8.41%   |
| Unknown               | 90        | 7.49%   |
| G.Skill               | 64        | 5.33%   |
| Ramaxel Technology    | 16        | 1.33%   |
| Elpida                | 15        | 1.25%   |
| Unknown (ABCD)        | 13        | 1.08%   |
| A-DATA Technology     | 10        | 0.83%   |
| Nanya Technology      | 9         | 0.75%   |
| Silicon Power         | 4         | 0.33%   |
| Transcend             | 3         | 0.25%   |
| Team                  | 3         | 0.25%   |
| GOODRAM               | 3         | 0.25%   |
| Avant                 | 3         | 0.25%   |
| Toshiba               | 2         | 0.17%   |
| JOY-IT                | 2         | 0.17%   |
| Hewlett-Packard       | 2         | 0.17%   |
| Unknown               | 2         | 0.17%   |
| Vaseky                | 1         | 0.08%   |
| Unifosa               | 1         | 0.08%   |
| TakeMS                | 1         | 0.08%   |
| Smart                 | 1         | 0.08%   |
| Qimonda               | 1         | 0.08%   |
| PNY                   | 1         | 0.08%   |
| Patriot               | 1         | 0.08%   |
| Mushkin               | 1         | 0.08%   |
| Kingmax Semiconductor | 1         | 0.08%   |
| Hitachi               | 1         | 0.08%   |
| CSX                   | 1         | 0.08%   |
| ASint Technology      | 1         | 0.08%   |
| 51010818AB6A1D42      | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 18        | 1.41%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 16        | 1.26%   |
| Crucial RAM BLS8G3D1609DS1S00. 8GB DIMM DDR3 1800MT/s            | 12        | 0.94%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 11        | 0.86%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 10        | 0.78%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.78%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.78%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 9         | 0.71%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 8         | 0.63%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 8         | 0.63%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.63%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 7         | 0.55%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 7         | 0.55%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 7         | 0.55%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 7         | 0.55%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 7         | 0.55%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.55%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 7         | 0.55%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 7         | 0.55%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 6         | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.47%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 6         | 0.47%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 6         | 0.47%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 6         | 0.47%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s           | 6         | 0.47%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s              | 6         | 0.47%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s              | 6         | 0.47%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 5         | 0.39%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s         | 5         | 0.39%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 5         | 0.39%   |
| Samsung RAM M471A4G43MB1-CTD 32GB SODIMM DDR4 2667MT/s           | 5         | 0.39%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 5         | 0.39%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s           | 5         | 0.39%   |
| Kingston RAM KHX3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s          | 5         | 0.39%   |
| Corsair RAM CMK32GX4M2D3600C18 16GB DIMM DDR4 3800MT/s           | 5         | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 4         | 0.31%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.31%   |
| SK hynix RAM HMT351S6EFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 4         | 0.31%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 4         | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 535       | 51.54%  |
| DDR3    | 339       | 32.66%  |
| DDR2    | 44        | 4.24%   |
| LPDDR4  | 43        | 4.14%   |
| LPDDR3  | 25        | 2.41%   |
| SDRAM   | 22        | 2.12%   |
| Unknown | 13        | 1.25%   |
| LPDDR5  | 7         | 0.67%   |
| DDR5    | 7         | 0.67%   |
| DDR     | 3         | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 559       | 53.91%  |
| DIMM         | 391       | 37.7%   |
| Row Of Chips | 79        | 7.62%   |
| Chip         | 7         | 0.68%   |
| FB-DIMM      | 1         | 0.1%    |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 474       | 41.98%  |
| 4096  | 253       | 22.41%  |
| 16384 | 217       | 19.22%  |
| 2048  | 116       | 10.27%  |
| 32768 | 39        | 3.45%   |
| 1024  | 23        | 2.04%   |
| 512   | 4         | 0.35%   |
| 65536 | 1         | 0.09%   |
| 256   | 1         | 0.09%   |
| 16    | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 208       | 18.6%   |
| 3200    | 195       | 17.44%  |
| 2667    | 151       | 13.51%  |
| 2400    | 91        | 8.14%   |
| 1333    | 66        | 5.9%    |
| 2133    | 56        | 5.01%   |
| 3600    | 36        | 3.22%   |
| 1334    | 28        | 2.5%    |
| 667     | 27        | 2.42%   |
| 4267    | 19        | 1.7%    |
| 1867    | 19        | 1.7%    |
| 1800    | 15        | 1.34%   |
| 800     | 14        | 1.25%   |
| 3733    | 12        | 1.07%   |
| 3000    | 11        | 0.98%   |
| 1067    | 11        | 0.98%   |
| Unknown | 11        | 0.98%   |
| 3800    | 9         | 0.81%   |
| 3266    | 9         | 0.81%   |
| 8400    | 8         | 0.72%   |
| 4800    | 8         | 0.72%   |
| 3400    | 8         | 0.72%   |
| 6400    | 7         | 0.63%   |
| 4199    | 7         | 0.63%   |
| 3533    | 7         | 0.63%   |
| 2933    | 7         | 0.63%   |
| 2666    | 7         | 0.63%   |
| 1866    | 7         | 0.63%   |
| 3866    | 6         | 0.54%   |
| 1066    | 6         | 0.54%   |
| 2048    | 5         | 0.45%   |
| 4266    | 4         | 0.36%   |
| 2800    | 4         | 0.36%   |
| 3666    | 3         | 0.27%   |
| 3534    | 3         | 0.27%   |
| 3466    | 3         | 0.27%   |
| 533     | 3         | 0.27%   |
| 4000    | 2         | 0.18%   |
| 3933    | 2         | 0.18%   |
| 3066    | 2         | 0.18%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 17        | 30.91%  |
| Canon                 | 15        | 27.27%  |
| Brother Industries    | 11        | 20%     |
| Seiko Epson           | 4         | 7.27%   |
| Samsung Electronics   | 3         | 5.45%   |
| Ricoh                 | 1         | 1.82%   |
| QinHeng Electronics   | 1         | 1.82%   |
| Prolific Technology   | 1         | 1.82%   |
| Oki Data              | 1         | 1.82%   |
| Lexmark International | 1         | 1.82%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| HP Deskjet 3520 series                                     | 3         | 5.26%   |
| Seiko Epson WF-2530 Series                                 | 2         | 3.51%   |
| Samsung C48x Series Color Laser Multifunction Printer      | 2         | 3.51%   |
| HP LaserJet 1320                                           | 2         | 3.51%   |
| HP ENVY 4520 series                                        | 2         | 3.51%   |
| Canon TS5100 series                                        | 2         | 3.51%   |
| Canon CanoScan LiDE 300                                    | 2         | 3.51%   |
| Brother Printer                                            | 2         | 3.51%   |
| Brother MFC-L2710DW series                                 | 2         | 3.51%   |
| Brother HL-3040CN series                                   | 2         | 3.51%   |
| Seiko Epson XP-230 Series                                  | 1         | 1.75%   |
| Seiko Epson ET-4750 [WorkForce ET-4750 EcoTank All-in-One] | 1         | 1.75%   |
| Samsung SCX-4300 Series                                    | 1         | 1.75%   |
| Ricoh SP 210SU                                             | 1         | 1.75%   |
| QinHeng CH340S                                             | 1         | 1.75%   |
| Prolific PL2305 Parallel Port                              | 1         | 1.75%   |
| Oki Data USB Device                                        | 1         | 1.75%   |
| Lexmark International CS417dn                              | 1         | 1.75%   |
| HP OfficeJet Pro 7720 series                               | 1         | 1.75%   |
| HP LaserJet Professional P1102w                            | 1         | 1.75%   |
| HP LaserJet P1102                                          | 1         | 1.75%   |
| HP LaserJet 1200                                           | 1         | 1.75%   |
| HP LaserJet 1022                                           | 1         | 1.75%   |
| HP ENVY Pro 6400 series                                    | 1         | 1.75%   |
| HP ENVY 5000 series                                        | 1         | 1.75%   |
| HP DeskJet 940c                                            | 1         | 1.75%   |
| HP DeskJet 2700 series                                     | 1         | 1.75%   |
| HP DeskJet 2600 series                                     | 1         | 1.75%   |
| HP Deskjet 2050 J510                                       | 1         | 1.75%   |
| HP Color Laser 150nw                                       | 1         | 1.75%   |
| Canon TS700 series                                         | 1         | 1.75%   |
| Canon TS6300 series                                        | 1         | 1.75%   |
| Canon PIXMA MX320 series                                   | 1         | 1.75%   |
| Canon PIXMA MG2500 Series                                  | 1         | 1.75%   |
| Canon PIXMA iX6850 Printer                                 | 1         | 1.75%   |
| Canon MG2100 series                                        | 1         | 1.75%   |
| Canon MF5650 (FAX)                                         | 1         | 1.75%   |
| Canon LBP2900                                              | 1         | 1.75%   |
| Canon LaserShot LBP-1120 Printer                           | 1         | 1.75%   |
| Canon L100/L150/L170                                       | 1         | 1.75%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 24        | 77.42%  |
| Seiko Epson     | 3         | 9.68%   |
| Fujitsu         | 3         | 9.68%   |
| Hewlett-Packard | 1         | 3.23%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Canon CanoScan                                           | 4         | 12.9%   |
| Fujitsu ScanSnap SV600                                   | 3         | 9.68%   |
| Canon CanoScan LiDE 110                                  | 3         | 9.68%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO] | 2         | 6.45%   |
| Canon CanoScan N670U/N676U/LiDE 20                       | 2         | 6.45%   |
| Canon CanoScan N1240U/LiDE 30                            | 2         | 6.45%   |
| Canon CanoScan LiDE 60                                   | 2         | 6.45%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                   | 2         | 6.45%   |
| Canon CanoScan LiDE 220                                  | 2         | 6.45%   |
| Canon CanoScan LiDE 200                                  | 2         | 6.45%   |
| Canon CanoScan LiDE 100                                  | 2         | 6.45%   |
| Seiko Epson GT-7200U [Perfection 1250/1250 PHOTO]        | 1         | 3.23%   |
| HP ScanJet 4850C/4890C                                   | 1         | 3.23%   |
| Canon CanoScan N650U/N656U                               | 1         | 3.23%   |
| Canon CanoScan LiDE 210                                  | 1         | 3.23%   |
| Canon CanoScan FB630U                                    | 1         | 3.23%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 270       | 25.3%   |
| IMC Networks                           | 96        | 9%      |
| Bison Electronics                      | 81        | 7.59%   |
| Microdia                               | 68        | 6.37%   |
| Logitech                               | 63        | 5.9%    |
| Realtek Semiconductor                  | 57        | 5.34%   |
| Sunplus Innovation Technology          | 56        | 5.25%   |
| Quanta                                 | 50        | 4.69%   |
| Lite-On Technology                     | 36        | 3.37%   |
| Cheng Uei Precision Industry (Foxlink) | 31        | 2.91%   |
| Suyin                                  | 30        | 2.81%   |
| Apple                                  | 30        | 2.81%   |
| Syntek                                 | 19        | 1.78%   |
| Luxvisions Innotech Limited            | 19        | 1.78%   |
| Acer                                   | 18        | 1.69%   |
| Microsoft                              | 16        | 1.5%    |
| Alcor Micro                            | 15        | 1.41%   |
| Samsung Electronics                    | 11        | 1.03%   |
| Lenovo                                 | 9         | 0.84%   |
| Z-Star Microelectronics                | 7         | 0.66%   |
| Ricoh                                  | 7         | 0.66%   |
| Primax Electronics                     | 6         | 0.56%   |
| SunplusIT                              | 5         | 0.47%   |
| OmniVision Technologies                | 4         | 0.37%   |
| Jieli Technology                       | 4         | 0.37%   |
| icSpring                               | 4         | 0.37%   |
| ARC International                      | 4         | 0.37%   |
| Silicon Motion                         | 3         | 0.28%   |
| SHENZHEN EMEET TECHNOLOGY              | 3         | 0.28%   |
| SHENZHEN AONI ELECTRONIC               | 3         | 0.28%   |
| KYE Systems (Mouse Systems)            | 3         | 0.28%   |
| Fujitsu                                | 3         | 0.28%   |
| DigiTech                               | 3         | 0.28%   |
| XHT-211220-ZW                          | 2         | 0.19%   |
| Tobii Technology AB                    | 2         | 0.19%   |
| Sony                                   | 2         | 0.19%   |
| Sonix Technology                       | 2         | 0.19%   |
| Shenzhen Kingcome Optoelectronic       | 2         | 0.19%   |
| Generalplus Technology                 | 2         | 0.19%   |
| GEMBIRD                                | 2         | 0.19%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Chicony Integrated Camera                | 73        | 6.78%   |
| IMC Networks Integrated Camera           | 47        | 4.36%   |
| Bison Integrated Camera                  | 35        | 3.25%   |
| Microdia Integrated_Webcam_HD            | 28        | 2.6%    |
| Chicony HP HD Camera                     | 19        | 1.76%   |
| Chicony HD Webcam                        | 19        | 1.76%   |
| Quanta HD User Facing                    | 16        | 1.49%   |
| IMC Networks USB2.0 HD UVC WebCam        | 15        | 1.39%   |
| Logitech HD Pro Webcam C920              | 14        | 1.3%    |
| Sunplus Integrated_Webcam_HD             | 13        | 1.21%   |
| Realtek Integrated_Webcam_HD             | 13        | 1.21%   |
| Lite-On Integrated Camera                | 13        | 1.21%   |
| IMC Networks USB2.0 VGA UVC WebCam       | 12        | 1.11%   |
| Samsung Galaxy series, misc. (MTP mode)  | 11        | 1.02%   |
| Quanta HP HD Camera                      | 11        | 1.02%   |
| Chicony TOSHIBA Web Camera - HD          | 11        | 1.02%   |
| Logitech Webcam C270                     | 10        | 0.93%   |
| Lite-On HP HD Camera                     | 10        | 0.93%   |
| Sunplus HD WebCam                        | 9         | 0.84%   |
| Chicony USB2.0 HD UVC WebCam             | 9         | 0.84%   |
| Chicony HP HD Webcam                     | 9         | 0.84%   |
| Chicony VGA WebCam                       | 8         | 0.74%   |
| Bison SunplusIT Integrated Camera        | 8         | 0.74%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X          | 8         | 0.74%   |
| Apple FaceTime HD Camera                 | 8         | 0.74%   |
| Apple Built-in iSight                    | 8         | 0.74%   |
| Syntek Integrated Camera                 | 7         | 0.65%   |
| Sunplus FHD Camera Microphone            | 7         | 0.65%   |
| Luxvisions Innotech Limited HP HD Camera | 7         | 0.65%   |
| Chicony USB 2.0 Camera                   | 7         | 0.65%   |
| Chicony Lenovo Integrated Camera (0.3MP) | 7         | 0.65%   |
| Chicony Integrated HP HD Webcam          | 7         | 0.65%   |
| Chicony Integrated Camera (1280x720@30)  | 7         | 0.65%   |
| Chicony HP Truevision HD camera          | 7         | 0.65%   |
| Bison HD Webcam                          | 7         | 0.65%   |
| Syntek Lenovo EasyCamera                 | 6         | 0.56%   |
| Realtek USB2.0 HD UVC WebCam             | 6         | 0.56%   |
| Realtek HD WebCam                        | 6         | 0.56%   |
| Microsoft LifeCam HD-3000                | 6         | 0.56%   |
| Microdia Webcam Vitade AF                | 6         | 0.56%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 113       | 37.17%  |
| Validity Sensors           | 108       | 35.53%  |
| Shenzhen Goodix Technology | 30        | 9.87%   |
| Upek                       | 18        | 5.92%   |
| AuthenTec                  | 16        | 5.26%   |
| Elan Microelectronics      | 11        | 3.62%   |
| LighTuning Technology      | 6         | 1.97%   |
| STMicroelectronics         | 1         | 0.33%   |
| Focal-systems.Corp         | 1         | 0.33%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 49        | 16.07%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 30        | 9.84%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 18        | 5.9%    |
| Shenzhen Goodix  Fingerprint Device                                        | 18        | 5.9%    |
| Validity Sensors Synaptics WBDI                                            | 15        | 4.92%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 3.28%   |
| Synaptics WBDI                                                             | 10        | 3.28%   |
| Synaptics Fingerprint reader [HP G6]                                       | 10        | 3.28%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 9         | 2.95%   |
| Validity Sensors VFS491                                                    | 9         | 2.95%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 2.62%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 7         | 2.3%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 7         | 2.3%    |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 7         | 2.3%    |
| Shenzhen Goodix Fingerprint Reader                                         | 7         | 2.3%    |
| AuthenTec AES2810                                                          | 7         | 2.3%    |
| Synaptics UWP WBDI                                                         | 6         | 1.97%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.97%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.64%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 1.64%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 5         | 1.64%   |
| Shenzhen Goodix FingerPrint                                                | 5         | 1.64%   |
| Synaptics UWP WBDI Device                                                  | 4         | 1.31%   |
| Elan ELAN:ARM-M4                                                           | 4         | 1.31%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 1.31%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 3         | 0.98%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 0.98%   |
| Synaptics WBDI Device                                                      | 3         | 0.98%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 3         | 0.98%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 3         | 0.98%   |
| Elan ELAN:Fingerprint                                                      | 3         | 0.98%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 3         | 0.98%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.66%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 2         | 0.66%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 0.66%   |
| Elan WBF Fingerprint Sensor                                                | 2         | 0.66%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 0.66%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.33%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.33%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 1         | 0.33%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 72        | 49.66%  |
| Broadcom              | 41        | 28.28%  |
| Lenovo                | 12        | 8.28%   |
| Upek                  | 9         | 6.21%   |
| O2 Micro              | 5         | 3.45%   |
| Realtek Semiconductor | 2         | 1.38%   |
| Cherry                | 2         | 1.38%   |
| SCM Microsystems      | 1         | 0.69%   |
| Advanced Card Systems | 1         | 0.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 71        | 48.97%  |
| Broadcom BCM5880 Secure Applications Processor                               | 17        | 11.72%  |
| Lenovo Integrated Smart Card Reader                                          | 11        | 7.59%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 11        | 7.59%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 9         | 6.21%   |
| Broadcom 58200                                                               | 7         | 4.83%   |
| Broadcom 5880                                                                | 6         | 4.14%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 4         | 2.76%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.38%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 1         | 0.69%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.69%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.69%   |
| Cherry SmartTerminal XX44                                                    | 1         | 0.69%   |
| Cherry Smart Terminal XX44                                                   | 1         | 0.69%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 0.69%   |
| Advanced Card Systems ACR122U                                                | 1         | 0.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1262      | 65.63%  |
| 1     | 499       | 25.95%  |
| 2     | 117       | 6.08%   |
| 3     | 26        | 1.35%   |
| 4     | 9         | 0.47%   |
| 5     | 5         | 0.26%   |
| 6     | 3         | 0.16%   |
| 8     | 2         | 0.1%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 298       | 35.27%  |
| Graphics card            | 149       | 17.63%  |
| Chipcard                 | 114       | 13.49%  |
| Net/wireless             | 95        | 11.24%  |
| Multimedia controller    | 38        | 4.5%    |
| Communication controller | 30        | 3.55%   |
| Unassigned class         | 21        | 2.49%   |
| Sound                    | 20        | 2.37%   |
| Bluetooth                | 20        | 2.37%   |
| Camera                   | 19        | 2.25%   |
| Net/ethernet             | 9         | 1.07%   |
| Card reader              | 9         | 1.07%   |
| Storage                  | 5         | 0.59%   |
| Modem                    | 5         | 0.59%   |
| Network                  | 3         | 0.36%   |
| Tv card                  | 2         | 0.24%   |
| Storage/raid             | 2         | 0.24%   |
| Flash memory             | 2         | 0.24%   |
| Storage/nvme             | 1         | 0.12%   |
| Storage/ide              | 1         | 0.12%   |
| Storage/ata              | 1         | 0.12%   |
| Firewire controller      | 1         | 0.12%   |

