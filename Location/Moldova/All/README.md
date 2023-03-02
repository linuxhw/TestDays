Linux in Moldova - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Moldova.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Moldova/Desktop/README.md) and [notebooks](/Location/Moldova/Notebook/README.md).

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

Total: 280

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple    | MacBookPro8,1               | Notebook    | [60ab083fe9](https://linux-hardware.org/?probe=60ab083fe9) | Feb 25, 2023 |
| ASUSTek  | PN41                        | Mini pc     | [2e3da97146](https://linux-hardware.org/?probe=2e3da97146) | Feb 19, 2023 |
| HP       | Pavilion Gaming Laptop 1... | Notebook    | [138e1ff0a8](https://linux-hardware.org/?probe=138e1ff0a8) | Feb 15, 2023 |
| ASUSTek  | K55A                        | Notebook    | [3faca30fb5](https://linux-hardware.org/?probe=3faca30fb5) | Feb 07, 2023 |
| Timi     | TM1701                      | Notebook    | [a474c92380](https://linux-hardware.org/?probe=a474c92380) | Jan 31, 2023 |
| Unknown  | Unknown                     | Desktop     | [7e53e3c6e8](https://linux-hardware.org/?probe=7e53e3c6e8) | Jan 31, 2023 |
| Lenovo   | 3111 SDK0J40697 WIN 3305... | Mini pc     | [bb70858194](https://linux-hardware.org/?probe=bb70858194) | Jan 19, 2023 |
| Gigabyte | H81M-S2PV                   | Desktop     | [72e7e2e1cf](https://linux-hardware.org/?probe=72e7e2e1cf) | Jan 11, 2023 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | Notebook    | [93fd2967ab](https://linux-hardware.org/?probe=93fd2967ab) | Jan 07, 2023 |
| Gigabyte | Z690 AORUS ULTRA            | Desktop     | [55627fc077](https://linux-hardware.org/?probe=55627fc077) | Jan 03, 2023 |
| Gigabyte | Z490M GAMING X              | Desktop     | [9012a42d6e](https://linux-hardware.org/?probe=9012a42d6e) | Jan 03, 2023 |
| Apple    | Mac-942B5BF58194151B        | All in one  | [6d047b6620](https://linux-hardware.org/?probe=6d047b6620) | Dec 30, 2022 |
| Apple    | Mac-942B5BF58194151B        | All in one  | [26e56628ec](https://linux-hardware.org/?probe=26e56628ec) | Dec 30, 2022 |
| Lenovo   | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [0760eec7e2](https://linux-hardware.org/?probe=0760eec7e2) | Dec 28, 2022 |
| ASRock   | 970DE3/U3S3                 | Desktop     | [1505706e04](https://linux-hardware.org/?probe=1505706e04) | Dec 25, 2022 |
| ASRock   | 970DE3/U3S3                 | Desktop     | [1c996d8122](https://linux-hardware.org/?probe=1c996d8122) | Dec 25, 2022 |
| Biostar  | GF8200C M2+                 | Desktop     | [e42ae4deef](https://linux-hardware.org/?probe=e42ae4deef) | Dec 08, 2022 |
| Valve    | Jupiter                     | Notebook    | [d008ed40fe](https://linux-hardware.org/?probe=d008ed40fe) | Nov 17, 2022 |
| Lenovo   | ThinkPad W520 4282BA9       | Notebook    | [4666660667](https://linux-hardware.org/?probe=4666660667) | Nov 12, 2022 |
| Biostar  | N68S3+                      | Desktop     | [a37667f835](https://linux-hardware.org/?probe=a37667f835) | Nov 11, 2022 |
| Unknown  | Unknown                     | Notebook    | [9247927a69](https://linux-hardware.org/?probe=9247927a69) | Nov 08, 2022 |
| Lenovo   | IdeaPad 330S-15ARR 81FB     | Notebook    | [8979e951e5](https://linux-hardware.org/?probe=8979e951e5) | Nov 07, 2022 |
| Google   | Droid                       | Notebook    | [c8e4007ce4](https://linux-hardware.org/?probe=c8e4007ce4) | Oct 26, 2022 |
| Lenovo   | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [71f188e90c](https://linux-hardware.org/?probe=71f188e90c) | Oct 19, 2022 |
| Intel    | NUC5i3RYB H41000-503        | Mini pc     | [52764efed5](https://linux-hardware.org/?probe=52764efed5) | Oct 12, 2022 |
| Biostar  | TB250-BTC PRO               | Desktop     | [09be95ac2c](https://linux-hardware.org/?probe=09be95ac2c) | Oct 10, 2022 |
| Acer     | Extensa 215-32              | Notebook    | [3e6ce67bb5](https://linux-hardware.org/?probe=3e6ce67bb5) | Oct 08, 2022 |
| Acer     | Extensa 215-32              | Notebook    | [366f0e7930](https://linux-hardware.org/?probe=366f0e7930) | Oct 08, 2022 |
| ASUSTek  | P8H61-M LX2 R2.0            | Desktop     | [0f690e6e12](https://linux-hardware.org/?probe=0f690e6e12) | Oct 08, 2022 |
| ASUSTek  | P8H61-M LX2 R2.0            | Desktop     | [e9bc8b1f10](https://linux-hardware.org/?probe=e9bc8b1f10) | Sep 26, 2022 |
| Acer     | Aspire A315-56              | Notebook    | [644bb082f4](https://linux-hardware.org/?probe=644bb082f4) | Sep 18, 2022 |
| ASUSTek  | VivoBook_ASUSLaptop X509... | Notebook    | [3c214d75b2](https://linux-hardware.org/?probe=3c214d75b2) | Sep 10, 2022 |
| HP       | ProBook 450 G7              | Notebook    | [5fa4bf5fc8](https://linux-hardware.org/?probe=5fa4bf5fc8) | Aug 29, 2022 |
| Lenovo   | Legion 5 Pro 16ITH6H 82J... | Notebook    | [681486095a](https://linux-hardware.org/?probe=681486095a) | Aug 27, 2022 |
| Gigabyte | B550 AORUS ELITE            | Desktop     | [08e3444b3c](https://linux-hardware.org/?probe=08e3444b3c) | Aug 15, 2022 |
| Foxconn  | nT-330i                     | Desktop     | [64504a98ed](https://linux-hardware.org/?probe=64504a98ed) | Aug 04, 2022 |
| Timi     | TM1701                      | Notebook    | [5b62dea22f](https://linux-hardware.org/?probe=5b62dea22f) | Aug 03, 2022 |
| Timi     | TM1701                      | Notebook    | [cddc7cb825](https://linux-hardware.org/?probe=cddc7cb825) | Aug 03, 2022 |
| Lenovo   | ThinkPad X1 Carbon 5th 2... | Notebook    | [d77ac14ae9](https://linux-hardware.org/?probe=d77ac14ae9) | Aug 01, 2022 |
| HP       | EliteBook 820 G3            | Notebook    | [a96c616d62](https://linux-hardware.org/?probe=a96c616d62) | Jul 28, 2022 |
| Dell     | Latitude 5480               | Notebook    | [151c4b8c85](https://linux-hardware.org/?probe=151c4b8c85) | Jul 21, 2022 |
| HP       | ProBook 450 G7              | Notebook    | [e011908e80](https://linux-hardware.org/?probe=e011908e80) | Jul 18, 2022 |
| HP       | ENVY 15                     | Notebook    | [9c0990eedf](https://linux-hardware.org/?probe=9c0990eedf) | Jul 18, 2022 |
| HP       | ProBook 450 G7              | Notebook    | [5d41d810e8](https://linux-hardware.org/?probe=5d41d810e8) | Jul 18, 2022 |
| ASUSTek  | TUF Gaming FX705DT_FX705... | Notebook    | [1d5a0f6177](https://linux-hardware.org/?probe=1d5a0f6177) | Jul 12, 2022 |
| Dell     | 0782GW A01                  | Desktop     | [20cb4c3e27](https://linux-hardware.org/?probe=20cb4c3e27) | Jul 11, 2022 |
| Lenovo   | IdeaPad Gaming 3 15ARH05... | Notebook    | [567077c28d](https://linux-hardware.org/?probe=567077c28d) | Jul 08, 2022 |
| Gigabyte | B450M S2H V2                | Desktop     | [e0e21604de](https://linux-hardware.org/?probe=e0e21604de) | Jun 24, 2022 |
| Lenovo   | IdeaPad L340-15API 81LW     | Notebook    | [dda5fb9c20](https://linux-hardware.org/?probe=dda5fb9c20) | Jun 21, 2022 |
| ASUSTek  | X555LD                      | Notebook    | [d5d6eeb639](https://linux-hardware.org/?probe=d5d6eeb639) | Jun 11, 2022 |
| Lenovo   | Legion 5 15IMH05 82AU       | Notebook    | [cd7bc92bcd](https://linux-hardware.org/?probe=cd7bc92bcd) | Jun 06, 2022 |
| ASUSTek  | PRIME A520M-K               | Desktop     | [72dd09a86a](https://linux-hardware.org/?probe=72dd09a86a) | Jun 05, 2022 |
| Lenovo   | IdeaPad 100-15IBY 80MJ      | Notebook    | [db944454c8](https://linux-hardware.org/?probe=db944454c8) | May 23, 2022 |
| Lenovo   | Legion Y530-15ICH 81FV      | Notebook    | [428509b262](https://linux-hardware.org/?probe=428509b262) | May 01, 2022 |
| ASUSTek  | X541NC                      | Notebook    | [d1dc342eb9](https://linux-hardware.org/?probe=d1dc342eb9) | Apr 17, 2022 |
| ASUSTek  | M4A785-M                    | Desktop     | [25526ee77d](https://linux-hardware.org/?probe=25526ee77d) | Apr 17, 2022 |
| ASUSTek  | PRIME B550-PLUS             | Desktop     | [8c88f1c50a](https://linux-hardware.org/?probe=8c88f1c50a) | Apr 12, 2022 |
| Lenovo   | ThinkPad X240 20AL0067RT    | Notebook    | [f246d643b4](https://linux-hardware.org/?probe=f246d643b4) | Feb 26, 2022 |
| Gigabyte | Z690 UD DDR4                | Desktop     | [6c4ff21b02](https://linux-hardware.org/?probe=6c4ff21b02) | Feb 21, 2022 |
| Sony     | VPCEB1J8E                   | Notebook    | [b00a6a15b2](https://linux-hardware.org/?probe=b00a6a15b2) | Feb 20, 2022 |
| ASUSTek  | U32U                        | Notebook    | [f7b7d4d2db](https://linux-hardware.org/?probe=f7b7d4d2db) | Feb 20, 2022 |
| ASUSTek  | U32U                        | Notebook    | [1cb943e596](https://linux-hardware.org/?probe=1cb943e596) | Feb 20, 2022 |
| Acer     | Swift SF314-57              | Notebook    | [de92ca9fec](https://linux-hardware.org/?probe=de92ca9fec) | Feb 05, 2022 |
| Lenovo   | ThinkPad E15 Gen 2 20TD0... | Notebook    | [4c95ae549f](https://linux-hardware.org/?probe=4c95ae549f) | Jan 21, 2022 |
| HP       | 21F5                        | Desktop     | [ce8e06508d](https://linux-hardware.org/?probe=ce8e06508d) | Jan 16, 2022 |
| HP       | Unknown                     | Notebook    | [1fbb31af8d](https://linux-hardware.org/?probe=1fbb31af8d) | Jan 05, 2022 |
| Jumper   | EZbook                      | Notebook    | [6e9ee100f8](https://linux-hardware.org/?probe=6e9ee100f8) | Dec 22, 2021 |
| HP       | Pavilion Laptop 15-eh1xx... | Notebook    | [ab93ce9eb8](https://linux-hardware.org/?probe=ab93ce9eb8) | Dec 21, 2021 |
| Jumper   | EZbook                      | Notebook    | [992b2479e4](https://linux-hardware.org/?probe=992b2479e4) | Dec 21, 2021 |
| HP       | EliteBook 8470p             | Notebook    | [8ab831bf5f](https://linux-hardware.org/?probe=8ab831bf5f) | Dec 21, 2021 |
| Biostar  | N68S3+                      | Desktop     | [8812de783f](https://linux-hardware.org/?probe=8812de783f) | Dec 16, 2021 |
| ASUSTek  | A_F_K20CE                   | Desktop     | [926db6c655](https://linux-hardware.org/?probe=926db6c655) | Dec 15, 2021 |
| ASUSTek  | Z97I-PLUS                   | Desktop     | [a379cfa431](https://linux-hardware.org/?probe=a379cfa431) | Dec 12, 2021 |
| Chuwi    | GemiBook Pro                | Notebook    | [493d55cb16](https://linux-hardware.org/?probe=493d55cb16) | Dec 11, 2021 |
| Dell     | Latitude 3520               | Notebook    | [8fb7494494](https://linux-hardware.org/?probe=8fb7494494) | Dec 06, 2021 |
| Gigabyte | H61M-S2-B3                  | Desktop     | [960d7d5035](https://linux-hardware.org/?probe=960d7d5035) | Dec 05, 2021 |
| ASRock   | M3A770DE                    | Desktop     | [b6ee8bc974](https://linux-hardware.org/?probe=b6ee8bc974) | Dec 01, 2021 |
| Gigabyte | H81M-HD3                    | Desktop     | [953c3f9284](https://linux-hardware.org/?probe=953c3f9284) | Nov 13, 2021 |
| Acer     | Aspire 5253G                | Notebook    | [f7c885dedd](https://linux-hardware.org/?probe=f7c885dedd) | Nov 08, 2021 |
| MSI      | MS-7309                     | Desktop     | [0a4d7fb95d](https://linux-hardware.org/?probe=0a4d7fb95d) | Oct 30, 2021 |
| MSI      | A75A-G35                    | Desktop     | [7223bfa184](https://linux-hardware.org/?probe=7223bfa184) | Oct 22, 2021 |
| Toshiba  | Satellite Pro S300L         | Notebook    | [93c5def444](https://linux-hardware.org/?probe=93c5def444) | Oct 06, 2021 |
| ASUSTek  | VivoBook S15 X510UF         | Notebook    | [336bbdae35](https://linux-hardware.org/?probe=336bbdae35) | Oct 02, 2021 |
| Lenovo   | ThinkPad E15 Gen 2 20TD0... | Notebook    | [7820254b55](https://linux-hardware.org/?probe=7820254b55) | Sep 23, 2021 |
| Dell     | Latitude 5591               | Notebook    | [0235ac49c6](https://linux-hardware.org/?probe=0235ac49c6) | Sep 15, 2021 |
| Lenovo   | ThinkPad E15 Gen 3 20YG0... | Notebook    | [02666996c0](https://linux-hardware.org/?probe=02666996c0) | Sep 12, 2021 |
| Lenovo   | ThinkPad E15 Gen 3 20YG0... | Notebook    | [97b45da8a7](https://linux-hardware.org/?probe=97b45da8a7) | Sep 12, 2021 |
| HP       | Laptop 15-da1xxx            | Notebook    | [c6f3848c20](https://linux-hardware.org/?probe=c6f3848c20) | Sep 12, 2021 |
| HP       | Laptop 15-da1xxx            | Notebook    | [b73b5ecab7](https://linux-hardware.org/?probe=b73b5ecab7) | Sep 11, 2021 |
| Lenovo   | Yoga 730-15IKB 81CU         | Convertible | [f0da92a413](https://linux-hardware.org/?probe=f0da92a413) | Aug 25, 2021 |
| Lenovo   | Yoga 730-15IKB 81CU         | Convertible | [c7b0b8b25a](https://linux-hardware.org/?probe=c7b0b8b25a) | Aug 21, 2021 |
| HP       | ProBook 450 G6              | Notebook    | [227d87ab66](https://linux-hardware.org/?probe=227d87ab66) | Aug 20, 2021 |
| Biostar  | N68S3+                      | Desktop     | [1eae78eec0](https://linux-hardware.org/?probe=1eae78eec0) | Aug 04, 2021 |
| Gigabyte | B460M DS3H V2               | Desktop     | [6177f24834](https://linux-hardware.org/?probe=6177f24834) | Aug 02, 2021 |
| Gigabyte | B460M DS3H V2               | Desktop     | [7fa66f2f95](https://linux-hardware.org/?probe=7fa66f2f95) | Aug 02, 2021 |
| Toshiba  | TECRA Z40-B                 | Notebook    | [d353412a4f](https://linux-hardware.org/?probe=d353412a4f) | Jul 29, 2021 |
| Lenovo   | IdeaPad 5 15ARE05 81YQ      | Notebook    | [8430084f74](https://linux-hardware.org/?probe=8430084f74) | Jul 15, 2021 |
| System76 | Adder WS                    | Notebook    | [d128c1d16b](https://linux-hardware.org/?probe=d128c1d16b) | Jul 08, 2021 |
| HP       | ProLiant DL360 G5           | Server      | [e1ec1d09c1](https://linux-hardware.org/?probe=e1ec1d09c1) | Jul 07, 2021 |
| Lenovo   | ThinkPad T440 20B7S1N809    | Notebook    | [b9ab49e917](https://linux-hardware.org/?probe=b9ab49e917) | Jul 07, 2021 |
| Gigabyte | EP43-UD3L                   | Desktop     | [3b6839e225](https://linux-hardware.org/?probe=3b6839e225) | Jul 01, 2021 |
| Dell     | Vostro 5590                 | Notebook    | [1cc0df9bfd](https://linux-hardware.org/?probe=1cc0df9bfd) | Jun 28, 2021 |
| Dell     | Vostro 5590                 | Notebook    | [0caade1304](https://linux-hardware.org/?probe=0caade1304) | Jun 28, 2021 |
| ASUSTek  | X555LJ                      | Notebook    | [aab7280bd9](https://linux-hardware.org/?probe=aab7280bd9) | Jun 20, 2021 |
| Timi     | A35S                        | Notebook    | [226823eb5b](https://linux-hardware.org/?probe=226823eb5b) | Jun 19, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X521... | Notebook    | [79e70ff708](https://linux-hardware.org/?probe=79e70ff708) | Jun 17, 2021 |
| ASUSTek  | TUF Gaming FX705DT_FX705... | Notebook    | [447e508593](https://linux-hardware.org/?probe=447e508593) | Jun 14, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X521... | Notebook    | [47d894d771](https://linux-hardware.org/?probe=47d894d771) | Jun 12, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X521... | Notebook    | [5c14296bc9](https://linux-hardware.org/?probe=5c14296bc9) | Jun 12, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X521... | Notebook    | [73e1185f6e](https://linux-hardware.org/?probe=73e1185f6e) | Jun 12, 2021 |
| ASUSTek  | F1A75-M LE                  | Desktop     | [b453e98364](https://linux-hardware.org/?probe=b453e98364) | May 21, 2021 |
| ASUSTek  | TUF Gaming FX705DT_FX705... | Notebook    | [666ddeb09c](https://linux-hardware.org/?probe=666ddeb09c) | May 19, 2021 |
| Dell     | Inspiron 3541               | Notebook    | [88d0f731fd](https://linux-hardware.org/?probe=88d0f731fd) | Apr 29, 2021 |
| Dell     | Inspiron 3541               | Notebook    | [4267385ad8](https://linux-hardware.org/?probe=4267385ad8) | Apr 29, 2021 |
| Dell     | Inspiron 3593               | Notebook    | [5facbef10b](https://linux-hardware.org/?probe=5facbef10b) | Apr 24, 2021 |
| Biostar  | A58MD                       | Desktop     | [3effc9a4ed](https://linux-hardware.org/?probe=3effc9a4ed) | Apr 18, 2021 |
| Dell     | Latitude E7440              | Notebook    | [c59d5358b3](https://linux-hardware.org/?probe=c59d5358b3) | Apr 04, 2021 |
| Biostar  | H110MHC                     | Desktop     | [acc13c8156](https://linux-hardware.org/?probe=acc13c8156) | Mar 24, 2021 |
| HP       | Pavilion dv7                | Notebook    | [b7756075fd](https://linux-hardware.org/?probe=b7756075fd) | Mar 15, 2021 |
| Lenovo   | Legion Y530-15ICH 81FV      | Notebook    | [bd5d97f7e7](https://linux-hardware.org/?probe=bd5d97f7e7) | Mar 07, 2021 |
| HP       | ZBook Fury 15 G7 Mobile ... | Notebook    | [c2435842e1](https://linux-hardware.org/?probe=c2435842e1) | Mar 04, 2021 |
| HP       | ZBook Fury 15 G7 Mobile ... | Notebook    | [5cc3d3f3ed](https://linux-hardware.org/?probe=5cc3d3f3ed) | Mar 04, 2021 |
| Lenovo   | IdeaPad 330-15IKB 81DE      | Notebook    | [16d0cd0b17](https://linux-hardware.org/?probe=16d0cd0b17) | Mar 04, 2021 |
| Lenovo   | IdeaPad 330-15IKB 81DE      | Notebook    | [7a3239606c](https://linux-hardware.org/?probe=7a3239606c) | Mar 04, 2021 |
| ASUSTek  | P8Z77-V PRO                 | Desktop     | [a3d54dee1b](https://linux-hardware.org/?probe=a3d54dee1b) | Feb 22, 2021 |
| ASUSTek  | P8Z77-V PRO                 | Desktop     | [7f75cd3e14](https://linux-hardware.org/?probe=7f75cd3e14) | Feb 22, 2021 |
| Lenovo   | Legion Y530-15ICH 81FV      | Notebook    | [88bab7f6e7](https://linux-hardware.org/?probe=88bab7f6e7) | Feb 22, 2021 |
| ASUSTek  | PRIME B350-PLUS             | Desktop     | [23ddb098d4](https://linux-hardware.org/?probe=23ddb098d4) | Feb 18, 2021 |
| ASRock   | Z87 Extreme4                | Desktop     | [2fc1d961c0](https://linux-hardware.org/?probe=2fc1d961c0) | Feb 14, 2021 |
| ASUSTek  | ZenBook UX333FA_UX333FA     | Notebook    | [454ea43e4a](https://linux-hardware.org/?probe=454ea43e4a) | Feb 11, 2021 |
| HP       | ProBook 650 G2              | Notebook    | [043b7f867b](https://linux-hardware.org/?probe=043b7f867b) | Jan 23, 2021 |
| HP       | Laptop 15-dw0xxx            | Notebook    | [a69f5fa59f](https://linux-hardware.org/?probe=a69f5fa59f) | Jan 17, 2021 |
| Gateway  | NV55S                       | Notebook    | [8ed7215a68](https://linux-hardware.org/?probe=8ed7215a68) | Jan 17, 2021 |
| ASUSTek  | B85M-E                      | Desktop     | [024b12b22d](https://linux-hardware.org/?probe=024b12b22d) | Jan 17, 2021 |
| ASUSTek  | ZenBook UX333FA_UX333FA     | Notebook    | [a2da0e78db](https://linux-hardware.org/?probe=a2da0e78db) | Jan 14, 2021 |
| ASUSTek  | ZenBook UX333FA_UX333FA     | Notebook    | [84f50057c5](https://linux-hardware.org/?probe=84f50057c5) | Jan 14, 2021 |
| ASUSTek  | ZenBook UX333FA_UX333FA     | Notebook    | [c3b5acb8ff](https://linux-hardware.org/?probe=c3b5acb8ff) | Jan 14, 2021 |
| Gateway  | NV55S                       | Notebook    | [149e658abf](https://linux-hardware.org/?probe=149e658abf) | Jan 10, 2021 |
| HP       | EliteBook 855 G7 Noteboo... | Notebook    | [9f70a6e397](https://linux-hardware.org/?probe=9f70a6e397) | Jan 06, 2021 |
| HP       | Pavilion 17                 | Notebook    | [ac1360247b](https://linux-hardware.org/?probe=ac1360247b) | Dec 22, 2020 |
| HP       | EliteBook 855 G7 Noteboo... | Notebook    | [049fa926a1](https://linux-hardware.org/?probe=049fa926a1) | Dec 21, 2020 |
| Gigabyte | GA-970A-DS3                 | Desktop     | [f333aed432](https://linux-hardware.org/?probe=f333aed432) | Dec 04, 2020 |
| Gigabyte | X570 AORUS ULTRA            | Desktop     | [bdc9ccf5d5](https://linux-hardware.org/?probe=bdc9ccf5d5) | Nov 23, 2020 |
| HP       | EliteBook 855 G7 Noteboo... | Notebook    | [69e21f1387](https://linux-hardware.org/?probe=69e21f1387) | Nov 09, 2020 |
| Lenovo   | ThinkPad Yoga 11e 3rd Ge... | Notebook    | [bc1158d1d3](https://linux-hardware.org/?probe=bc1158d1d3) | Nov 09, 2020 |
| HP       | EliteBook 855 G7 Noteboo... | Notebook    | [8725886c61](https://linux-hardware.org/?probe=8725886c61) | Nov 06, 2020 |
| Dell     | Inspiron N5110              | Notebook    | [ee5fa15c46](https://linux-hardware.org/?probe=ee5fa15c46) | Nov 06, 2020 |
| ASUSTek  | Strix 17 GL703GE            | Notebook    | [6e4daa0a3c](https://linux-hardware.org/?probe=6e4daa0a3c) | Nov 05, 2020 |
| ASUSTek  | Strix 17 GL703GE            | Notebook    | [3a9f43c320](https://linux-hardware.org/?probe=3a9f43c320) | Nov 04, 2020 |
| HUAWEI   | NBLK-WAX9X                  | Notebook    | [4088a13026](https://linux-hardware.org/?probe=4088a13026) | Oct 09, 2020 |
| Biostar  | A960D+V3                    | Desktop     | [86864a3f9a](https://linux-hardware.org/?probe=86864a3f9a) | Oct 01, 2020 |
| Biostar  | A960D+V3                    | Desktop     | [781ac4ebab](https://linux-hardware.org/?probe=781ac4ebab) | Sep 30, 2020 |
| Gigabyte | P41-ES3G                    | Desktop     | [30feb0323e](https://linux-hardware.org/?probe=30feb0323e) | Sep 29, 2020 |
| Gigabyte | P41-ES3G                    | Desktop     | [395e492e72](https://linux-hardware.org/?probe=395e492e72) | Sep 29, 2020 |
| ASUSTek  | X200MA                      | Notebook    | [794220eee6](https://linux-hardware.org/?probe=794220eee6) | Sep 26, 2020 |
| Lenovo   | G710 20252                  | Notebook    | [c166b56839](https://linux-hardware.org/?probe=c166b56839) | Aug 26, 2020 |
| ASUSTek  | P8H61-MX                    | Desktop     | [46cff277d4](https://linux-hardware.org/?probe=46cff277d4) | Aug 16, 2020 |
| ASUSTek  | M2N-SLI DELUXE              | Desktop     | [02ab999339](https://linux-hardware.org/?probe=02ab999339) | Aug 04, 2020 |
| ASUSTek  | X541NA                      | Notebook    | [3f4978f463](https://linux-hardware.org/?probe=3f4978f463) | Aug 03, 2020 |
| HP       | ProBook 6465b               | Notebook    | [378cd77f66](https://linux-hardware.org/?probe=378cd77f66) | Jul 26, 2020 |
| ASRock   | A320M-HDV R4.0              | Desktop     | [0320a45205](https://linux-hardware.org/?probe=0320a45205) | Jul 25, 2020 |
| ASUSTek  | VivoBook S15 X510UF         | Notebook    | [66a180cdab](https://linux-hardware.org/?probe=66a180cdab) | Jul 24, 2020 |
| ASUSTek  | VivoBook S15 X510UF         | Notebook    | [ed25557a01](https://linux-hardware.org/?probe=ed25557a01) | Jul 20, 2020 |
| HP       | Compaq Presario CQ60        | Notebook    | [8d24316f6b](https://linux-hardware.org/?probe=8d24316f6b) | Jul 15, 2020 |
| HP       | ProBook 450 G7              | Notebook    | [3638848f89](https://linux-hardware.org/?probe=3638848f89) | Jun 24, 2020 |
| Dell     | XPS 15 9570                 | Notebook    | [c14028664d](https://linux-hardware.org/?probe=c14028664d) | Jun 23, 2020 |
| ASUSTek  | X541NA                      | Notebook    | [6d3495ee91](https://linux-hardware.org/?probe=6d3495ee91) | Jun 14, 2020 |
| HP       | ProBook 470 G2              | Notebook    | [bce3965ebb](https://linux-hardware.org/?probe=bce3965ebb) | Jun 13, 2020 |
| ASUSTek  | M4A785TD-V EVO              | Desktop     | [734d413d2f](https://linux-hardware.org/?probe=734d413d2f) | May 25, 2020 |
| ASUSTek  | M4A785TD-V EVO              | Desktop     | [a5f24237a6](https://linux-hardware.org/?probe=a5f24237a6) | May 22, 2020 |
| ASUSTek  | P8B75-M LE                  | Desktop     | [3051982d33](https://linux-hardware.org/?probe=3051982d33) | Apr 28, 2020 |
| ASUSTek  | P8B75-M LE                  | Desktop     | [6e3a1017c8](https://linux-hardware.org/?probe=6e3a1017c8) | Apr 28, 2020 |
| Lenovo   | IdeaPad 130-15IKB 81H7      | Notebook    | [54b25b6a82](https://linux-hardware.org/?probe=54b25b6a82) | Apr 18, 2020 |
| HP       | EliteBook 850 G6            | Notebook    | [92d96a7e87](https://linux-hardware.org/?probe=92d96a7e87) | Apr 11, 2020 |
| Acer     | Aspire C22-820              | All in one  | [3075b9fbfc](https://linux-hardware.org/?probe=3075b9fbfc) | Apr 07, 2020 |
| ASUSTek  | H110M-K                     | Desktop     | [d65e7d1bb6](https://linux-hardware.org/?probe=d65e7d1bb6) | Mar 28, 2020 |
| ASUSTek  | F1A75-M LE                  | Desktop     | [3cee091303](https://linux-hardware.org/?probe=3cee091303) | Mar 25, 2020 |
| Acer     | Aspire C22-820              | All in one  | [cfac371a18](https://linux-hardware.org/?probe=cfac371a18) | Mar 24, 2020 |
| Acer     | Aspire C22-820              | All in one  | [b283f093f1](https://linux-hardware.org/?probe=b283f093f1) | Mar 24, 2020 |
| ASUSTek  | H110M-K                     | Desktop     | [c0aa963f37](https://linux-hardware.org/?probe=c0aa963f37) | Mar 21, 2020 |
| MSI      | 2A9C                        | Desktop     | [cb1789ae00](https://linux-hardware.org/?probe=cb1789ae00) | Mar 18, 2020 |
| Samsung  | RV413/RV513                 | Notebook    | [996451817e](https://linux-hardware.org/?probe=996451817e) | Mar 12, 2020 |
| Lenovo   | IdeaPad 330-15IGM 81D1      | Notebook    | [c0c091dee5](https://linux-hardware.org/?probe=c0c091dee5) | Feb 22, 2020 |
| Lenovo   | IdeaPad 330-15IGM 81D1      | Notebook    | [f1e8d4fb95](https://linux-hardware.org/?probe=f1e8d4fb95) | Feb 22, 2020 |
| ASUSTek  | X541NA                      | Notebook    | [3df0912982](https://linux-hardware.org/?probe=3df0912982) | Feb 15, 2020 |
| Lenovo   | G710 20252                  | Notebook    | [7df7fd3c10](https://linux-hardware.org/?probe=7df7fd3c10) | Feb 15, 2020 |
| Toshiba  | Satellite C55D-A            | Notebook    | [19713fa1aa](https://linux-hardware.org/?probe=19713fa1aa) | Feb 05, 2020 |
| Dell     | Inspiron 3582               | Notebook    | [6916c1087b](https://linux-hardware.org/?probe=6916c1087b) | Jan 21, 2020 |
| Dell     | Inspiron 3582               | Notebook    | [b873ab0117](https://linux-hardware.org/?probe=b873ab0117) | Jan 16, 2020 |
| Dell     | Inspiron 3582               | Notebook    | [cf3745ead4](https://linux-hardware.org/?probe=cf3745ead4) | Jan 16, 2020 |
| ASUSTek  | K54C                        | Notebook    | [42b284e62d](https://linux-hardware.org/?probe=42b284e62d) | Dec 17, 2019 |
| ASUSTek  | X542UR                      | Notebook    | [8c29a78852](https://linux-hardware.org/?probe=8c29a78852) | Dec 15, 2019 |
| ASUSTek  | M5A78L-M LX                 | Desktop     | [90f55c011b](https://linux-hardware.org/?probe=90f55c011b) | Dec 04, 2019 |
| ASUSTek  | X542UR                      | Notebook    | [106dcde5e2](https://linux-hardware.org/?probe=106dcde5e2) | Oct 24, 2019 |
| ASUSTek  | P5QL/EPU                    | Desktop     | [8f31c009af](https://linux-hardware.org/?probe=8f31c009af) | Oct 20, 2019 |
| ASUSTek  | X542UR                      | Notebook    | [d5d9fe7ed0](https://linux-hardware.org/?probe=d5d9fe7ed0) | Oct 15, 2019 |
| ASUSTek  | X542UR                      | Notebook    | [f0e44b13bf](https://linux-hardware.org/?probe=f0e44b13bf) | Sep 15, 2019 |
| ASUSTek  | X541SA                      | Notebook    | [f4ec1608f1](https://linux-hardware.org/?probe=f4ec1608f1) | Aug 19, 2019 |
| Samsung  | RV413/RV513                 | Notebook    | [a569d1638b](https://linux-hardware.org/?probe=a569d1638b) | Aug 16, 2019 |
| ASUSTek  | F1A75-M LE                  | Desktop     | [bdb727808f](https://linux-hardware.org/?probe=bdb727808f) | Jul 26, 2019 |
| ASUSTek  | F1A75-M LE                  | Desktop     | [961de73328](https://linux-hardware.org/?probe=961de73328) | Jul 26, 2019 |
| HP       | Compaq 6910p                | Notebook    | [2b9b5142af](https://linux-hardware.org/?probe=2b9b5142af) | Jul 02, 2019 |
| Dell     | Inspiron 3521               | Notebook    | [5129fbc2b3](https://linux-hardware.org/?probe=5129fbc2b3) | Jun 13, 2019 |
| Dell     | Inspiron 3521               | Notebook    | [de72a9023b](https://linux-hardware.org/?probe=de72a9023b) | Jun 12, 2019 |
| Acer     | Aspire C24-865              | All in one  | [2288828f06](https://linux-hardware.org/?probe=2288828f06) | Jun 11, 2019 |
| Timi     | TM1701                      | Notebook    | [b2b217c7ba](https://linux-hardware.org/?probe=b2b217c7ba) | Jun 04, 2019 |
| Lenovo   | IdeaPad 330S-14IKB 81F4     | Notebook    | [1df14b9671](https://linux-hardware.org/?probe=1df14b9671) | May 31, 2019 |
| Acer     | Aspire E1-572G              | Notebook    | [d7c9cc59b9](https://linux-hardware.org/?probe=d7c9cc59b9) | May 17, 2019 |
| ASUSTek  | X550JX                      | Notebook    | [a268d267b1](https://linux-hardware.org/?probe=a268d267b1) | May 14, 2019 |
| Toshiba  | Satellite A210              | Notebook    | [b08d78a7fe](https://linux-hardware.org/?probe=b08d78a7fe) | May 12, 2019 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | Notebook    | [adff6b4ec1](https://linux-hardware.org/?probe=adff6b4ec1) | May 08, 2019 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | Notebook    | [1427bdb593](https://linux-hardware.org/?probe=1427bdb593) | May 08, 2019 |
| Biostar  | GF8100 M2+ SE               | Desktop     | [52b394c153](https://linux-hardware.org/?probe=52b394c153) | May 05, 2019 |
| ASUSTek  | P5P43TD                     | Desktop     | [bbfc5c83ed](https://linux-hardware.org/?probe=bbfc5c83ed) | Apr 23, 2019 |
| ASUSTek  | P5P43TD                     | Desktop     | [a1df618ae9](https://linux-hardware.org/?probe=a1df618ae9) | Apr 18, 2019 |
| Gigabyte | G41M-ES2L                   | Desktop     | [62f911ea35](https://linux-hardware.org/?probe=62f911ea35) | Apr 09, 2019 |
| HP       | Compaq Presario CQ60        | Notebook    | [c4ee62ecc8](https://linux-hardware.org/?probe=c4ee62ecc8) | Mar 21, 2019 |
| HP       | 82A1                        | Desktop     | [f04f3b1720](https://linux-hardware.org/?probe=f04f3b1720) | Mar 18, 2019 |
| Acer     | Aspire A515-51G             | Notebook    | [bc2c6a0308](https://linux-hardware.org/?probe=bc2c6a0308) | Jan 21, 2019 |
| Acer     | Aspire A515-51G             | Notebook    | [a4fa6be429](https://linux-hardware.org/?probe=a4fa6be429) | Jan 21, 2019 |
| Samsung  | 300E4C/300E5C/300E7C        | Notebook    | [761e996b51](https://linux-hardware.org/?probe=761e996b51) | Jan 13, 2019 |
| HP       | 635                         | Notebook    | [26ac239a00](https://linux-hardware.org/?probe=26ac239a00) | Jan 13, 2019 |
| HP       | 635                         | Notebook    | [88b6088e86](https://linux-hardware.org/?probe=88b6088e86) | Jan 13, 2019 |
| Dell     | Latitude E5420              | Notebook    | [58a37ca1d7](https://linux-hardware.org/?probe=58a37ca1d7) | Jan 08, 2019 |
| ASRock   | B250M Pro4                  | Desktop     | [05dfa7d080](https://linux-hardware.org/?probe=05dfa7d080) | Jan 07, 2019 |
| ASRock   | B250M Pro4                  | Desktop     | [4ca432ffe1](https://linux-hardware.org/?probe=4ca432ffe1) | Jan 03, 2019 |
| HP       | Compaq CQ58                 | Notebook    | [f930811937](https://linux-hardware.org/?probe=f930811937) | Dec 25, 2018 |
| HP       | Compaq CQ58                 | Notebook    | [092addb321](https://linux-hardware.org/?probe=092addb321) | Dec 25, 2018 |
| Samsung  | R517/R717                   | Notebook    | [cf1386553c](https://linux-hardware.org/?probe=cf1386553c) | Dec 11, 2018 |
| HP       | ENVY m6                     | Notebook    | [a2443c2500](https://linux-hardware.org/?probe=a2443c2500) | Nov 28, 2018 |
| Biostar  | NF61D-A2                    | Desktop     | [8920fb5da2](https://linux-hardware.org/?probe=8920fb5da2) | Nov 24, 2018 |
| Lenovo   | ThinkPad X131e 33711T0      | Notebook    | [d765880811](https://linux-hardware.org/?probe=d765880811) | Nov 20, 2018 |
| Gigabyte | H61M-S1                     | Desktop     | [f035a927b4](https://linux-hardware.org/?probe=f035a927b4) | Oct 16, 2018 |
| Gigabyte | H61M-S1                     | Desktop     | [0cb176039a](https://linux-hardware.org/?probe=0cb176039a) | Oct 16, 2018 |
| ASUSTek  | K56CM                       | Notebook    | [9801230a74](https://linux-hardware.org/?probe=9801230a74) | Oct 11, 2018 |
| ASUSTek  | H110M-R                     | Desktop     | [e8cf4914df](https://linux-hardware.org/?probe=e8cf4914df) | Oct 11, 2018 |
| Lenovo   | G710 20252                  | Notebook    | [67b5fc31a6](https://linux-hardware.org/?probe=67b5fc31a6) | Sep 03, 2018 |
| ASUSTek  | TUF X299 MARK 1             | Desktop     | [4ff6f8b306](https://linux-hardware.org/?probe=4ff6f8b306) | Aug 28, 2018 |
| ASUSTek  | H110M-R                     | Desktop     | [856815508e](https://linux-hardware.org/?probe=856815508e) | Jul 20, 2018 |
| ASUSTek  | H110M-R                     | Desktop     | [2c6e982e0a](https://linux-hardware.org/?probe=2c6e982e0a) | Jul 20, 2018 |
| ASUSTek  | K50AB                       | Notebook    | [5309fc98bb](https://linux-hardware.org/?probe=5309fc98bb) | Jun 21, 2018 |
| Lenovo   | Y520-15IKBN 80WK            | Notebook    | [9c2fa220c0](https://linux-hardware.org/?probe=9c2fa220c0) | Jun 07, 2018 |
| Lenovo   | Y520-15IKBN 80WK            | Notebook    | [23cd9fcd79](https://linux-hardware.org/?probe=23cd9fcd79) | Jun 07, 2018 |
| ASRock   | H110M-DGS                   | Desktop     | [2bf308c36a](https://linux-hardware.org/?probe=2bf308c36a) | Apr 22, 2018 |
| Gigabyte | H81M-S2PV                   | Desktop     | [d73e7cdaf7](https://linux-hardware.org/?probe=d73e7cdaf7) | Apr 10, 2018 |
| ASUSTek  | M5A78L LE                   | Desktop     | [324ea287af](https://linux-hardware.org/?probe=324ea287af) | Mar 25, 2018 |
| ASUSTek  | M5A78L LE                   | Desktop     | [c4796ca0ba](https://linux-hardware.org/?probe=c4796ca0ba) | Mar 25, 2018 |
| MSI      | G31M3-L V2                  | Desktop     | [a010b34c1d](https://linux-hardware.org/?probe=a010b34c1d) | Mar 14, 2018 |
| ASUSTek  | K52N                        | Notebook    | [9b6027f7f9](https://linux-hardware.org/?probe=9b6027f7f9) | Mar 04, 2018 |
| Gigabyte | GA-880GM-USB3               | Desktop     | [488c7af7b3](https://linux-hardware.org/?probe=488c7af7b3) | Feb 13, 2018 |
| ASUSTek  | K52N                        | Notebook    | [a31f696968](https://linux-hardware.org/?probe=a31f696968) | Jan 27, 2018 |
| Biostar  | H61MGV3                     | Desktop     | [601f3981af](https://linux-hardware.org/?probe=601f3981af) | Jan 25, 2018 |
| MSI      | G31M3-L V2                  | Desktop     | [cb825d670e](https://linux-hardware.org/?probe=cb825d670e) | Jan 23, 2018 |
| Biostar  | A960G+                      | Desktop     | [1ed969e51e](https://linux-hardware.org/?probe=1ed969e51e) | Jan 02, 2018 |
| ASUSTek  | E502SA                      | Notebook    | [f82780c45f](https://linux-hardware.org/?probe=f82780c45f) | Dec 22, 2017 |
| Samsung  | R517/R717                   | Notebook    | [88501ec4d2](https://linux-hardware.org/?probe=88501ec4d2) | Nov 23, 2017 |
| Acer     | Aspire E5-575               | Notebook    | [d7a774808d](https://linux-hardware.org/?probe=d7a774808d) | Nov 07, 2017 |
| Gigabyte | H81M-S2PV                   | Desktop     | [b4b5168bf0](https://linux-hardware.org/?probe=b4b5168bf0) | Oct 22, 2017 |
| Biostar  | TA790GX 128M                | Desktop     | [13dafc619e](https://linux-hardware.org/?probe=13dafc619e) | Sep 07, 2017 |
| Lenovo   | V580 20147                  | Notebook    | [7b4ec145fd](https://linux-hardware.org/?probe=7b4ec145fd) | Sep 05, 2017 |
| ASUSTek  | E502SA                      | Notebook    | [f80e3a3361](https://linux-hardware.org/?probe=f80e3a3361) | Jul 02, 2017 |
| Acer     | AO756                       | Notebook    | [750d61ea27](https://linux-hardware.org/?probe=750d61ea27) | Jun 28, 2017 |
| ASUSTek  | E502SA                      | Notebook    | [e638970390](https://linux-hardware.org/?probe=e638970390) | Jun 27, 2017 |
| Samsung  | R517/R717                   | Notebook    | [a037b05f1c](https://linux-hardware.org/?probe=a037b05f1c) | Jun 07, 2017 |
| Lenovo   | V580 20147                  | Notebook    | [e4a66b20cf](https://linux-hardware.org/?probe=e4a66b20cf) | May 09, 2017 |
| ASUSTek  | P7P55D-E                    | Desktop     | [7ead295d4f](https://linux-hardware.org/?probe=7ead295d4f) | May 04, 2017 |
| ASUSTek  | P5GPL                       | Desktop     | [dc412a96d7](https://linux-hardware.org/?probe=dc412a96d7) | Mar 11, 2017 |
| ASUSTek  | P5GPL                       | Desktop     | [704d76d7f0](https://linux-hardware.org/?probe=704d76d7f0) | Mar 11, 2017 |
| HP       | 550                         | Notebook    | [21d69ed69f](https://linux-hardware.org/?probe=21d69ed69f) | Feb 14, 2017 |
| ECS      | GeForce7050M-M              | Desktop     | [dffec0e1ef](https://linux-hardware.org/?probe=dffec0e1ef) | Jan 26, 2017 |
| MSI      | G41M-P26                    | Desktop     | [3a93859874](https://linux-hardware.org/?probe=3a93859874) | Jan 21, 2017 |
| Dell     | 0HJ054                      | Desktop     | [3a64a2e7cc](https://linux-hardware.org/?probe=3a64a2e7cc) | Jan 14, 2017 |
| ASUSTek  | M5A78L-M LX3                | Desktop     | [de5986b48c](https://linux-hardware.org/?probe=de5986b48c) | Dec 27, 2016 |
| Acer     | Aspire E1-531G              | Notebook    | [0481735487](https://linux-hardware.org/?probe=0481735487) | Dec 19, 2016 |
| ASUSTek  | P8H61-M LX3                 | Desktop     | [51108b9a7b](https://linux-hardware.org/?probe=51108b9a7b) | Nov 26, 2016 |
| ASUSTek  | A88X-PLUS                   | Desktop     | [e5165dfe31](https://linux-hardware.org/?probe=e5165dfe31) | Nov 25, 2016 |
| ASUSTek  | A88X-PLUS                   | Desktop     | [53f70342b5](https://linux-hardware.org/?probe=53f70342b5) | Nov 23, 2016 |
| MSI      | CR610                       | Notebook    | [fa269a3f05](https://linux-hardware.org/?probe=fa269a3f05) | Nov 20, 2016 |
| ASUSTek  | P5KPL-AM IN/ROEM/SI         | Desktop     | [c140d93dd9](https://linux-hardware.org/?probe=c140d93dd9) | Nov 08, 2016 |
| ECS      | GeForce7050M-M              | Desktop     | [3f276c748c](https://linux-hardware.org/?probe=3f276c748c) | Nov 04, 2016 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| ROSA R10          | 21        | 9.81%   |
| Ubuntu 20.04      | 15        | 7.01%   |
| Ubuntu 18.04      | 15        | 7.01%   |
| ROSA R11          | 14        | 6.54%   |
| ROSA R8           | 10        | 4.67%   |
| ROSA R11.1        | 10        | 4.67%   |
| ROSA R8.1         | 8         | 3.74%   |
| Ubuntu 22.04      | 7         | 3.27%   |
| OpenMandriva 4.2  | 6         | 2.8%    |
| OpenMandriva 4.3  | 5         | 2.34%   |
| Linux Mint 20.1   | 5         | 2.34%   |
| KDE neon 20.04    | 5         | 2.34%   |
| ROSA R9           | 4         | 1.87%   |
| ROSA 12.2         | 4         | 1.87%   |
| Manjaro           | 4         | 1.87%   |
| Arch              | 4         | 1.87%   |
| Ubuntu 22.10      | 3         | 1.4%    |
| Linux Mint 19.1   | 3         | 1.4%    |
| Fedora 36         | 3         | 1.4%    |
| Fedora 34         | 3         | 1.4%    |
| Arch Rolling      | 3         | 1.4%    |
| Zorin 16          | 2         | 0.93%   |
| Ubuntu 19.10      | 2         | 0.93%   |
| Ubuntu 16.04      | 2         | 0.93%   |
| ROSA 12.1         | 2         | 0.93%   |
| Pop!_OS 21.04     | 2         | 0.93%   |
| Pop!_OS 20.10     | 2         | 0.93%   |
| Linux Mint 21.1   | 2         | 0.93%   |
| Linux Mint 20.2   | 2         | 0.93%   |
| Linux Mint 20     | 2         | 0.93%   |
| Linux Mint 19.3   | 2         | 0.93%   |
| Debian 11         | 2         | 0.93%   |
| BlackPanther 18.1 | 2         | 0.93%   |
| Ubuntu 21.10      | 1         | 0.47%   |
| Ubuntu 21.04      | 1         | 0.47%   |
| Ubuntu 19.04      | 1         | 0.47%   |
| SteamOS 3.3.2     | 1         | 0.47%   |
| SteamOS 3.3       | 1         | 0.47%   |
| ROSA 12.3         | 1         | 0.47%   |
| Pop!_OS 21.10     | 1         | 0.47%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| ROSA         | 68        | 33.01%  |
| Ubuntu       | 47        | 22.82%  |
| Linux Mint   | 17        | 8.25%   |
| OpenMandriva | 13        | 6.31%   |
| Manjaro      | 10        | 4.85%   |
| Fedora       | 10        | 4.85%   |
| Arch         | 7         | 3.4%    |
| Pop!_OS      | 6         | 2.91%   |
| KDE neon     | 5         | 2.43%   |
| Endless      | 4         | 1.94%   |
| Kali         | 3         | 1.46%   |
| Debian       | 3         | 1.46%   |
| Zorin        | 2         | 0.97%   |
| SteamOS      | 2         | 0.97%   |
| Kubuntu      | 2         | 0.97%   |
| BuildRoot    | 2         | 0.97%   |
| BlackPanther | 2         | 0.97%   |
| Nobara       | 1         | 0.49%   |
| Lubuntu      | 1         | 0.49%   |
| Ctlos        | 1         | 0.49%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64     | 10        | 4.46%   |
| 5.10.14-desktop-1omv4002            | 6         | 2.68%   |
| 4.9.20-nrj-desktop-1rosa-x86_64     | 6         | 2.68%   |
| 4.15.0-desktop-45.1rosa-x86_64      | 6         | 2.68%   |
| 5.16.7-desktop-1omv4003             | 5         | 2.23%   |
| 5.10.74-generic-2rosa2021.1-x86_64  | 5         | 2.23%   |
| 4.1.34-nrj-desktop-2rosa-x86_64     | 5         | 2.23%   |
| 5.15.0-41-generic                   | 4         | 1.79%   |
| 4.9.60-nrj-desktop-1rosa-i586       | 4         | 1.79%   |
| 4.9.155-nrj-desktop-1rosa-x86_64    | 4         | 1.79%   |
| 4.15.0-desktop-68.5rosa-x86_64      | 4         | 1.79%   |
| 5.8.0-33-generic                    | 3         | 1.34%   |
| 5.4.32-generic-2rosa-x86_64         | 2         | 0.89%   |
| 5.4.0-48-generic                    | 2         | 0.89%   |
| 5.4.0-37-generic                    | 2         | 0.89%   |
| 5.17.11-generic-2rosa2021.1-x86_64  | 2         | 0.89%   |
| 5.15.0-58-generic                   | 2         | 0.89%   |
| 5.11.0-7614-generic                 | 2         | 0.89%   |
| 5.11.0-41-generic                   | 2         | 0.89%   |
| 5.11.0-34-generic                   | 2         | 0.89%   |
| 5.11.0-25-generic                   | 2         | 0.89%   |
| 5.10.2-2-MANJARO                    | 2         | 0.89%   |
| 4.9.95-nrj-desktop-2rosa-x86_64     | 2         | 0.89%   |
| 4.9.41-nrj-desktop-1rosa-x86_64     | 2         | 0.89%   |
| 4.9.124-nrj-desktop-1rosa-x86_64    | 2         | 0.89%   |
| 4.15.0-desktop-47.2rosa-x86_64      | 2         | 0.89%   |
| 4.15.0-desktop-122.124.1rosa-x86_64 | 2         | 0.89%   |
| 4.1.34-nrj-desktop-2rosa-i586       | 2         | 0.89%   |
| 4.1.25-nrj-desktop-1rosa-i586       | 2         | 0.89%   |
| 6.1.12                              | 1         | 0.45%   |
| 6.1.1-desktop-1omv2290              | 1         | 0.45%   |
| 6.1.1-arch1-1                       | 1         | 0.45%   |
| 6.0.14-201.fsync.fc36.x86_64        | 1         | 0.45%   |
| 5.9.3-1-MANJARO                     | 1         | 0.45%   |
| 5.9.3-050903-generic                | 1         | 0.45%   |
| 5.8.18-100.fc31.x86_64              | 1         | 0.45%   |
| 5.8.18-1-MANJARO                    | 1         | 0.45%   |
| 5.8.0-7642-generic                  | 1         | 0.45%   |
| 5.8.0-38-generic                    | 1         | 0.45%   |
| 5.8.0-36-generic                    | 1         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15.0  | 27        | 12.33%  |
| 5.4.0   | 18        | 8.22%   |
| 4.9.60  | 13        | 5.94%   |
| 5.15.0  | 12        | 5.48%   |
| 5.11.0  | 12        | 5.48%   |
| 5.8.0   | 7         | 3.2%    |
| 4.1.34  | 7         | 3.2%    |
| 5.10.14 | 6         | 2.74%   |
| 4.9.20  | 6         | 2.74%   |
| 5.3.0   | 5         | 2.28%   |
| 5.16.7  | 5         | 2.28%   |
| 5.13.0  | 5         | 2.28%   |
| 5.10.74 | 5         | 2.28%   |
| 5.0.0   | 4         | 1.83%   |
| 4.9.155 | 4         | 1.83%   |
| 4.18.0  | 4         | 1.83%   |
| 5.4.32  | 3         | 1.37%   |
| 5.19.0  | 3         | 1.37%   |
| 4.9.124 | 3         | 1.37%   |
| 4.1.38  | 3         | 1.37%   |
| 6.1.1   | 2         | 0.91%   |
| 5.9.3   | 2         | 0.91%   |
| 5.8.18  | 2         | 0.91%   |
| 5.18.1  | 2         | 0.91%   |
| 5.17.11 | 2         | 0.91%   |
| 5.10.2  | 2         | 0.91%   |
| 5.10.0  | 2         | 0.91%   |
| 4.9.95  | 2         | 0.91%   |
| 4.9.9   | 2         | 0.91%   |
| 4.9.76  | 2         | 0.91%   |
| 4.9.41  | 2         | 0.91%   |
| 4.10.0  | 2         | 0.91%   |
| 4.1.25  | 2         | 0.91%   |
| 6.1.12  | 1         | 0.46%   |
| 6.0.14  | 1         | 0.46%   |
| 5.6.14  | 1         | 0.46%   |
| 5.5.9   | 1         | 0.46%   |
| 5.4.83  | 1         | 0.46%   |
| 5.4.49  | 1         | 0.46%   |
| 5.2.0   | 1         | 0.46%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 32        | 14.95%  |
| 4.15    | 27        | 12.62%  |
| 5.4     | 23        | 10.75%  |
| 5.10    | 19        | 8.88%   |
| 5.15    | 18        | 8.41%   |
| 5.11    | 13        | 6.07%   |
| 4.1     | 12        | 5.61%   |
| 5.8     | 9         | 4.21%   |
| 5.18    | 7         | 3.27%   |
| 5.16    | 7         | 3.27%   |
| 5.13    | 6         | 2.8%    |
| 5.3     | 5         | 2.34%   |
| 5.19    | 5         | 2.34%   |
| 5.0     | 5         | 2.34%   |
| 5.17    | 4         | 1.87%   |
| 4.18    | 4         | 1.87%   |
| 6.1     | 3         | 1.4%    |
| 5.9     | 2         | 0.93%   |
| 5.14    | 2         | 0.93%   |
| 5.12    | 2         | 0.93%   |
| 4.10    | 2         | 0.93%   |
| 6.0     | 1         | 0.47%   |
| 5.6     | 1         | 0.47%   |
| 5.5     | 1         | 0.47%   |
| 5.2     | 1         | 0.47%   |
| 5.1     | 1         | 0.47%   |
| 4.19    | 1         | 0.47%   |
| 4.16    | 1         | 0.47%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 191       | 92.27%  |
| i686   | 16        | 7.73%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 54        | 25.71%  |
| KDE5            | 51        | 24.29%  |
| KDE4            | 47        | 22.38%  |
| Unknown         | 18        | 8.57%   |
| X-Cinnamon      | 13        | 6.19%   |
| XFCE            | 8         | 3.81%   |
| MATE            | 3         | 1.43%   |
| LXQt            | 3         | 1.43%   |
| KDE             | 3         | 1.43%   |
| sway            | 2         | 0.95%   |
| GNOME Flashback | 2         | 0.95%   |
| Cinnamon        | 2         | 0.95%   |
| xinitrc         | 1         | 0.48%   |
| LXDE            | 1         | 0.48%   |
| i3              | 1         | 0.48%   |
| bspwm           | 1         | 0.48%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 166       | 79.81%  |
| Wayland | 29        | 13.94%  |
| Unknown | 13        | 6.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 67        | 31.75%  |
| SDDM    | 47        | 22.27%  |
| KDM     | 47        | 22.27%  |
| GDM     | 22        | 10.43%  |
| LightDM | 10        | 4.74%   |
| GDM3    | 10        | 4.74%   |
| TDM     | 8         | 3.79%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 75        | 36.06%  |
| en_US   | 61        | 29.33%  |
| ru_RU   | 49        | 23.56%  |
| ro_RO   | 9         | 4.33%   |
| en_GB   | 5         | 2.4%    |
| C       | 4         | 1.92%   |
| ru_UA   | 2         | 0.96%   |
| nl_NL   | 1         | 0.48%   |
| en_150  | 1         | 0.48%   |
| de_DE   | 1         | 0.48%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 120       | 57.97%  |
| EFI  | 87        | 42.03%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 140       | 67.63%  |
| Unknown | 37        | 17.87%  |
| Overlay | 14        | 6.76%   |
| Btrfs   | 12        | 5.8%    |
| Xfs     | 2         | 0.97%   |
| F2fs    | 1         | 0.48%   |
| Ext2    | 1         | 0.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 78        | 37.14%  |
| MBR     | 66        | 31.43%  |
| GPT     | 66        | 31.43%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 183       | 87.98%  |
| Yes       | 25        | 12.02%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 147       | 70.67%  |
| Yes       | 61        | 29.33%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 55        | 26.83%  |
| Lenovo              | 29        | 14.15%  |
| Hewlett-Packard     | 29        | 14.15%  |
| Gigabyte Technology | 17        | 8.29%   |
| Dell                | 14        | 6.83%   |
| Biostar             | 11        | 5.37%   |
| Acer                | 11        | 5.37%   |
| MSI                 | 6         | 2.93%   |
| ASRock              | 6         | 2.93%   |
| Toshiba             | 4         | 1.95%   |
| Timi                | 4         | 1.95%   |
| Samsung Electronics | 4         | 1.95%   |
| Apple               | 2         | 0.98%   |
| Unknown             | 2         | 0.98%   |
| Valve               | 1         | 0.49%   |
| System76            | 1         | 0.49%   |
| Sony                | 1         | 0.49%   |
| Jumper              | 1         | 0.49%   |
| Intel               | 1         | 0.49%   |
| HUAWEI              | 1         | 0.49%   |
| Google              | 1         | 0.49%   |
| Gateway             | 1         | 0.49%   |
| Foxconn             | 1         | 0.49%   |
| ECS                 | 1         | 0.49%   |
| Chuwi               | 1         | 0.49%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Timi TM1701                                 | 3         | 1.46%   |
| ASUS VivoBook_ASUSLaptop X521IA_D533IA      | 3         | 1.46%   |
| Unknown                                     | 3         | 1.46%   |
| Samsung RV413/RV513                         | 2         | 0.98%   |
| Lenovo Legion Y530-15ICH 81FV               | 2         | 0.98%   |
| HP ProBook 450 G7                           | 2         | 0.98%   |
| HP Compaq Presario CQ60                     | 2         | 0.98%   |
| Gigabyte H81M-S2PV                          | 2         | 0.98%   |
| ASUS VivoBook S15 X510UF                    | 2         | 0.98%   |
| ASUS H110M-R                                | 2         | 0.98%   |
| ASUS All Series                             | 2         | 0.98%   |
| Valve Jupiter                               | 1         | 0.49%   |
| Toshiba TECRA Z40-B                         | 1         | 0.49%   |
| Toshiba Satellite Pro S300L                 | 1         | 0.49%   |
| Toshiba Satellite C55D-A                    | 1         | 0.49%   |
| Toshiba Satellite A210                      | 1         | 0.49%   |
| Timi A35S                                   | 1         | 0.49%   |
| System76 Adder WS                           | 1         | 0.49%   |
| Sony VPCEB1J8E                              | 1         | 0.49%   |
| Samsung R517/R717                           | 1         | 0.49%   |
| Samsung 300E4C/300E5C/300E7C                | 1         | 0.49%   |
| MSI Pro 3130 Microtower PC                  | 1         | 0.49%   |
| MSI MS-7695                                 | 1         | 0.49%   |
| MSI MS-7592                                 | 1         | 0.49%   |
| MSI MS-7529                                 | 1         | 0.49%   |
| MSI MS-7309                                 | 1         | 0.49%   |
| MSI CR610                                   | 1         | 0.49%   |
| Lenovo Yoga 730-15IKB 81CU                  | 1         | 0.49%   |
| Lenovo Y520-15IKBN 80WK                     | 1         | 0.49%   |
| Lenovo V580 20147                           | 1         | 0.49%   |
| Lenovo ThinkPad Yoga 11e 3rd Gen 20G8S0MG00 | 1         | 0.49%   |
| Lenovo ThinkPad X240 20AL0067RT             | 1         | 0.49%   |
| Lenovo ThinkPad X131e 33711T0               | 1         | 0.49%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR002MMX    | 1         | 0.49%   |
| Lenovo ThinkPad W520 4282BA9                | 1         | 0.49%   |
| Lenovo ThinkPad T440 20B7S1N809             | 1         | 0.49%   |
| Lenovo ThinkPad E15 Gen 3 20YG004BRT        | 1         | 0.49%   |
| Lenovo ThinkPad E15 Gen 2 20TD003TRT        | 1         | 0.49%   |
| Lenovo ThinkPad E15 Gen 2 20TD002NRA        | 1         | 0.49%   |
| Lenovo ThinkCentre M710q 10MR003UUS         | 1         | 0.49%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 11        | 5.37%   |
| Lenovo ThinkPad    | 9         | 4.39%   |
| ASUS VivoBook      | 8         | 3.9%    |
| Acer Aspire        | 8         | 3.9%    |
| HP ProBook         | 6         | 2.93%   |
| Dell Latitude      | 5         | 2.44%   |
| Dell Inspiron      | 5         | 2.44%   |
| Lenovo Legion      | 4         | 1.95%   |
| HP Pavilion        | 4         | 1.95%   |
| HP EliteBook       | 4         | 1.95%   |
| HP Compaq          | 4         | 1.95%   |
| Toshiba Satellite  | 3         | 1.46%   |
| Timi TM1701        | 3         | 1.46%   |
| ASUS PRIME         | 3         | 1.46%   |
| Unknown            | 3         | 1.46%   |
| Samsung RV413      | 2         | 0.98%   |
| HP ProDesk         | 2         | 0.98%   |
| HP Laptop          | 2         | 0.98%   |
| HP ENVY            | 2         | 0.98%   |
| Gigabyte Z690      | 2         | 0.98%   |
| Gigabyte H81M-S2PV | 2         | 0.98%   |
| ASUS TUF           | 2         | 0.98%   |
| ASUS P8H61-M       | 2         | 0.98%   |
| ASUS M5A78L-M      | 2         | 0.98%   |
| ASUS H110M-R       | 2         | 0.98%   |
| ASUS All           | 2         | 0.98%   |
| Valve Jupiter      | 1         | 0.49%   |
| Toshiba TECRA      | 1         | 0.49%   |
| Timi A35S          | 1         | 0.49%   |
| System76 Adder     | 1         | 0.49%   |
| Sony VPCEB1J8E     | 1         | 0.49%   |
| Samsung R517       | 1         | 0.49%   |
| Samsung 300E4C     | 1         | 0.49%   |
| MSI Pro            | 1         | 0.49%   |
| MSI MS-7695        | 1         | 0.49%   |
| MSI MS-7592        | 1         | 0.49%   |
| MSI MS-7529        | 1         | 0.49%   |
| MSI MS-7309        | 1         | 0.49%   |
| MSI CR610          | 1         | 0.49%   |
| Lenovo Yoga        | 1         | 0.49%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2011 | 21        | 10.24%  |
| 2018 | 20        | 9.76%   |
| 2012 | 19        | 9.27%   |
| 2021 | 18        | 8.78%   |
| 2017 | 18        | 8.78%   |
| 2019 | 17        | 8.29%   |
| 2009 | 16        | 7.8%    |
| 2013 | 14        | 6.83%   |
| 2020 | 13        | 6.34%   |
| 2016 | 11        | 5.37%   |
| 2010 | 9         | 4.39%   |
| 2015 | 8         | 3.9%    |
| 2014 | 5         | 2.44%   |
| 2008 | 5         | 2.44%   |
| 2007 | 4         | 1.95%   |
| 2022 | 3         | 1.46%   |
| 2006 | 3         | 1.46%   |
| 2005 | 1         | 0.49%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 123       | 60%     |
| Desktop     | 74        | 36.1%   |
| Mini pc     | 3         | 1.46%   |
| All in one  | 3         | 1.46%   |
| Convertible | 1         | 0.49%   |
| Server      | 1         | 0.49%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 195       | 95.12%  |
| Enabled  | 10        | 4.88%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 204       | 99.51%  |
| Yes  | 1         | 0.49%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 60        | 29.13%  |
| 4.01-8.0    | 42        | 20.39%  |
| 8.01-16.0   | 39        | 18.93%  |
| 16.01-24.0  | 29        | 14.08%  |
| 32.01-64.0  | 13        | 6.31%   |
| 1.01-2.0    | 11        | 5.34%   |
| 2.01-3.0    | 8         | 3.88%   |
| 64.01-256.0 | 2         | 0.97%   |
| 24.01-32.0  | 1         | 0.49%   |
| 0.51-1.0    | 1         | 0.49%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 81        | 36.99%  |
| 0.51-1.0   | 42        | 19.18%  |
| 2.01-3.0   | 38        | 17.35%  |
| 4.01-8.0   | 29        | 13.24%  |
| 3.01-4.0   | 18        | 8.22%   |
| 8.01-16.0  | 5         | 2.28%   |
| 0.01-0.5   | 3         | 1.37%   |
| 16.01-24.0 | 2         | 0.91%   |
| 24.01-32.0 | 1         | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 140       | 67.96%  |
| 2      | 45        | 21.84%  |
| 3      | 14        | 6.8%    |
| 4      | 5         | 2.43%   |
| 0      | 2         | 0.97%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 135       | 65.85%  |
| Yes       | 70        | 34.15%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 183       | 88.83%  |
| No        | 23        | 11.17%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 146       | 71.22%  |
| No        | 59        | 28.78%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 112       | 54.37%  |
| No        | 94        | 45.63%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Moldova | 205       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Chisinau        | 113       | 54.33%  |
| Tiraspol        | 43        | 20.67%  |
| Bălţi         | 7         | 3.37%   |
| Straseni        | 5         | 2.4%    |
| Tighina         | 4         | 1.92%   |
| Hincesti        | 3         | 1.44%   |
| Soroca          | 2         | 0.96%   |
| Ialoveni        | 2         | 0.96%   |
| Căușeni       | 2         | 0.96%   |
| Cahul           | 2         | 0.96%   |
| Zaicana         | 1         | 0.48%   |
| Tvardița       | 1         | 0.48%   |
| Tintareni       | 1         | 0.48%   |
| Soldanesti      | 1         | 0.48%   |
| Sofia           | 1         | 0.48%   |
| Singera         | 1         | 0.48%   |
| Rîbniţa       | 1         | 0.48%   |
| Rezina          | 1         | 0.48%   |
| Rautel          | 1         | 0.48%   |
| Prajila         | 1         | 0.48%   |
| Pociumbeni      | 1         | 0.48%   |
| Nisporeni       | 1         | 0.48%   |
| Lapusna         | 1         | 0.48%   |
| Gangura         | 1         | 0.48%   |
| Floresti        | 1         | 0.48%   |
| Floreni         | 1         | 0.48%   |
| Edineţ         | 1         | 0.48%   |
| Durlesti        | 1         | 0.48%   |
| Drochia         | 1         | 0.48%   |
| Donduseni       | 1         | 0.48%   |
| Criuleni        | 1         | 0.48%   |
| Crasnoarmeiscoe | 1         | 0.48%   |
| Cojusna         | 1         | 0.48%   |
| Cenac           | 1         | 0.48%   |
| Cazanesti       | 1         | 0.48%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 57        | 68     | 20.21%  |
| WDC                 | 36        | 38     | 12.77%  |
| Seagate             | 36        | 41     | 12.77%  |
| Toshiba             | 29        | 34     | 10.28%  |
| Hitachi             | 17        | 20     | 6.03%   |
| Kingston            | 14        | 17     | 4.96%   |
| SanDisk             | 11        | 11     | 3.9%    |
| SPCC                | 7         | 9      | 2.48%   |
| SK hynix            | 6         | 6      | 2.13%   |
| Micron Technology   | 6         | 8      | 2.13%   |
| Unknown             | 5         | 5      | 1.77%   |
| Transcend           | 5         | 5      | 1.77%   |
| Intel               | 4         | 6      | 1.42%   |
| HGST                | 4         | 4      | 1.42%   |
| Apacer              | 4         | 4      | 1.42%   |
| Netac               | 3         | 3      | 1.06%   |
| Maxtor              | 3         | 4      | 1.06%   |
| Crucial             | 3         | 4      | 1.06%   |
| Phison              | 2         | 3      | 0.71%   |
| OCZ                 | 2         | 2      | 0.71%   |
| GOODRAM             | 2         | 2      | 0.71%   |
| Fujitsu             | 2         | 2      | 0.71%   |
| China               | 2         | 2      | 0.71%   |
| A-DATA Technology   | 2         | 2      | 0.71%   |
| ZOTAC               | 1         | 3      | 0.35%   |
| XPG                 | 1         | 1      | 0.35%   |
| UMIS                | 1         | 1      | 0.35%   |
| Team                | 1         | 1      | 0.35%   |
| Solid State Storage | 1         | 1      | 0.35%   |
| PNY                 | 1         | 1      | 0.35%   |
| Patriot             | 1         | 1      | 0.35%   |
| O2 Micro            | 1         | 1      | 0.35%   |
| LITEONIT            | 1         | 1      | 0.35%   |
| Lite-On Technology  | 1         | 1      | 0.35%   |
| Leven               | 1         | 1      | 0.35%   |
| Lenovo              | 1         | 1      | 0.35%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.35%   |
| KIOXIA              | 1         | 1      | 0.35%   |
| KingDian            | 1         | 1      | 0.35%   |
| Intenso             | 1         | 1      | 0.35%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SHFS37A120G 120GB SSD         | 7         | 2.41%   |
| Samsung NVMe SSD Drive 512GB           | 6         | 2.07%   |
| Toshiba MQ01ABD100 1TB                 | 4         | 1.38%   |
| Toshiba DT01ACA050 500GB               | 4         | 1.38%   |
| Seagate ST500LT012-9WS142 500GB        | 4         | 1.38%   |
| Seagate ST1000LM035-1RK172 1TB         | 4         | 1.38%   |
| Samsung SSD 860 EVO 500GB              | 4         | 1.38%   |
| Toshiba MQ04ABF100 1TB                 | 3         | 1.03%   |
| Toshiba DT01ACA100 1TB                 | 3         | 1.03%   |
| SanDisk NVMe SSD Drive 512GB           | 3         | 1.03%   |
| Samsung MZVLW256HEHP-00000 256GB       | 3         | 1.03%   |
| Samsung HD502HJ 500GB                  | 3         | 1.03%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD    | 3         | 1.03%   |
| Hitachi HTS543232A7A384 320GB          | 3         | 1.03%   |
| WDC WD5000AZRX-00A8LB0 500GB           | 2         | 0.69%   |
| WDC WD10SPZX-24Z10T0 1TB               | 2         | 0.69%   |
| WDC WD10SPZX-22Z10T1 1TB               | 2         | 0.69%   |
| Unknown MMC Card  64GB                 | 2         | 0.69%   |
| Transcend TS64GSSD370S 64GB            | 2         | 0.69%   |
| Toshiba MQ01ACF032 320GB               | 2         | 0.69%   |
| Toshiba MQ01ABF050 500GB               | 2         | 0.69%   |
| Toshiba HDWD110 1TB                    | 2         | 0.69%   |
| SPCC Solid State Disk 128GB            | 2         | 0.69%   |
| SK hynix NVMe SSD Drive 256GB          | 2         | 0.69%   |
| Seagate ST9500325AS 500GB              | 2         | 0.69%   |
| Seagate ST500DM002-1BD142 500GB        | 2         | 0.69%   |
| Seagate ST4000VM000-2AF166 4TB         | 2         | 0.69%   |
| Seagate ST3160023A 160GB               | 2         | 0.69%   |
| Seagate ST2000DM008-2FR102 2TB         | 2         | 0.69%   |
| Seagate ST1000DL002-9TT153 1TB         | 2         | 0.69%   |
| SanDisk SD7UB3Q256G1001 256GB SSD      | 2         | 0.69%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 2         | 0.69%   |
| Samsung HD251HJ 249GB                  | 2         | 0.69%   |
| Samsung HD082GJ 80GB                   | 2         | 0.69%   |
| Netac SSD 256GB                        | 2         | 0.69%   |
| Intel NVMe SSD Drive 512GB             | 2         | 0.69%   |
| Hitachi HTS547575A9E384 752GB          | 2         | 0.69%   |
| Hitachi HTS542525K9SA00 250GB          | 2         | 0.69%   |
| Apacer AS340 240GB SSD                 | 2         | 0.69%   |
| ZOTAC ZTSSD-S11-240G-P 240GB           | 1         | 0.34%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 36        | 41     | 25.35%  |
| WDC                 | 35        | 37     | 24.65%  |
| Toshiba             | 24        | 29     | 16.9%   |
| Samsung Electronics | 19        | 22     | 13.38%  |
| Hitachi             | 17        | 20     | 11.97%  |
| HGST                | 4         | 4      | 2.82%   |
| Maxtor              | 3         | 4      | 2.11%   |
| Fujitsu             | 2         | 2      | 1.41%   |
| Unknown             | 1         | 1      | 0.7%    |
| ASMT                | 1         | 1      | 0.7%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 13        | 16     | 17.11%  |
| Samsung Electronics | 12        | 15     | 15.79%  |
| SPCC                | 6         | 8      | 7.89%   |
| SanDisk             | 6         | 6      | 7.89%   |
| Transcend           | 5         | 5      | 6.58%   |
| Apacer              | 4         | 4      | 5.26%   |
| Micron Technology   | 3         | 3      | 3.95%   |
| Crucial             | 3         | 4      | 3.95%   |
| Toshiba             | 2         | 2      | 2.63%   |
| OCZ                 | 2         | 2      | 2.63%   |
| Netac               | 2         | 2      | 2.63%   |
| GOODRAM             | 2         | 2      | 2.63%   |
| China               | 2         | 2      | 2.63%   |
| ZOTAC               | 1         | 3      | 1.32%   |
| Team                | 1         | 1      | 1.32%   |
| PNY                 | 1         | 1      | 1.32%   |
| Patriot             | 1         | 1      | 1.32%   |
| LITEONIT            | 1         | 1      | 1.32%   |
| Leven               | 1         | 1      | 1.32%   |
| KIOXIA-EXCERIA      | 1         | 1      | 1.32%   |
| KingDian            | 1         | 1      | 1.32%   |
| Intenso             | 1         | 1      | 1.32%   |
| Intel               | 1         | 1      | 1.32%   |
| Goldkey             | 1         | 1      | 1.32%   |
| Gigabyte Technology | 1         | 2      | 1.32%   |
| CHN25SATAS1         | 1         | 1      | 1.32%   |
| A-DATA Technology   | 1         | 1      | 1.32%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 122       | 161    | 48.41%  |
| SSD  | 71        | 88     | 28.17%  |
| NVMe | 55        | 70     | 21.83%  |
| MMC  | 4         | 4      | 1.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 162       | 247    | 72.65%  |
| NVMe | 55        | 70     | 24.66%  |
| MMC  | 4         | 4      | 1.79%   |
| SAS  | 2         | 2      | 0.9%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 133       | 186    | 71.51%  |
| 0.51-1.0   | 40        | 50     | 21.51%  |
| 1.01-2.0   | 9         | 9      | 4.84%   |
| 3.01-4.0   | 3         | 3      | 1.61%   |
| 4.01-10.0  | 1         | 1      | 0.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 59        | 27.57%  |
| 251-500        | 58        | 27.1%   |
| 501-1000       | 26        | 12.15%  |
| 51-100         | 25        | 11.68%  |
| 1-20           | 19        | 8.88%   |
| 21-50          | 8         | 3.74%   |
| 1001-2000      | 8         | 3.74%   |
| Unknown        | 6         | 2.8%    |
| 2001-3000      | 3         | 1.4%    |
| More than 3000 | 2         | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 104       | 47.71%  |
| 21-50          | 34        | 15.6%   |
| 51-100         | 26        | 11.93%  |
| 101-250        | 21        | 9.63%   |
| 251-500        | 15        | 6.88%   |
| 501-1000       | 8         | 3.67%   |
| Unknown        | 6         | 2.75%   |
| 1001-2000      | 3         | 1.38%   |
| More than 3000 | 1         | 0.46%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB   | 3         | 3      | 6.38%   |
| Seagate ST3160023A 160GB          | 2         | 2      | 4.26%   |
| Samsung Electronics HD082GJ 80GB  | 2         | 2      | 4.26%   |
| Kingston SHFS37A120G 120GB SSD    | 2         | 4      | 4.26%   |
| Hitachi HTS547575A9E384 752GB     | 2         | 2      | 4.26%   |
| WDC WD800JD-22LSA0 80GB           | 1         | 1      | 2.13%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1         | 1      | 2.13%   |
| WDC WD5000AAKS-75V0A0 500GB       | 1         | 1      | 2.13%   |
| WDC WD5000AAKS-00WWPA0 500GB      | 1         | 1      | 2.13%   |
| WDC WD5000AADS-56S9B1 500GB       | 1         | 1      | 2.13%   |
| WDC WD3200BEVT-22A23T0 320GB      | 1         | 1      | 2.13%   |
| WDC WD2500AAKX-00U6AA0 250GB      | 1         | 1      | 2.13%   |
| WDC WD1600BEVS-60RST0 160GB       | 1         | 1      | 2.13%   |
| WDC WD1600BEVS-07RST0 160GB       | 1         | 1      | 2.13%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 2.13%   |
| Toshiba MQ01ABD032 320GB          | 1         | 1      | 2.13%   |
| Toshiba DT01ACA050 500GB          | 1         | 1      | 2.13%   |
| Team L5 LITE SSD 240GB            | 1         | 1      | 2.13%   |
| SPCC SSD162 120GB                 | 1         | 1      | 2.13%   |
| SPCC Solid State Disk 56GB        | 1         | 2      | 2.13%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 2.13%   |
| Seagate ST3500418AS 500GB         | 1         | 1      | 2.13%   |
| Seagate ST320DM001 HD322GJ 320GB  | 1         | 1      | 2.13%   |
| Seagate ST31000340NS 1TB          | 1         | 1      | 2.13%   |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1      | 2.13%   |
| Seagate ST1000DL002-9TT153 1TB    | 1         | 1      | 2.13%   |
| SanDisk SD7UB3Q256G1001 256GB SSD | 1         | 1      | 2.13%   |
| Samsung Electronics HD753LJ 752GB | 1         | 1      | 2.13%   |
| Samsung Electronics HD103UJ 1TB   | 1         | 1      | 2.13%   |
| Samsung Electronics HD080HJ 80GB  | 1         | 1      | 2.13%   |
| Maxtor STM380215AS 80GB           | 1         | 1      | 2.13%   |
| Maxtor STM3160811AS 160GB         | 1         | 1      | 2.13%   |
| Maxtor STM3160211AS 160GB         | 1         | 1      | 2.13%   |
| Maxtor 4R120L0 122GB              | 1         | 1      | 2.13%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 1      | 2.13%   |
| Hitachi HTS545025B9A300 250GB     | 1         | 1      | 2.13%   |
| Hitachi HDT721010SLA360 1TB       | 1         | 2      | 2.13%   |
| Hitachi HDP725050GLA360 500GB     | 1         | 1      | 2.13%   |
| Hitachi HDP725025GLA380 250GB     | 1         | 2      | 2.13%   |
| Fujitsu MHW2080BH PL 80GB         | 1         | 1      | 2.13%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 23.91%  |
| WDC                 | 9         | 9      | 19.57%  |
| Hitachi             | 7         | 9      | 15.22%  |
| Samsung Electronics | 5         | 5      | 10.87%  |
| Toshiba             | 3         | 3      | 6.52%   |
| Maxtor              | 3         | 4      | 6.52%   |
| SPCC                | 2         | 3      | 4.35%   |
| Kingston            | 2         | 4      | 4.35%   |
| Team                | 1         | 1      | 2.17%   |
| SanDisk             | 1         | 1      | 2.17%   |
| Fujitsu             | 1         | 1      | 2.17%   |
| A-DATA Technology   | 1         | 1      | 2.17%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 11        | 11     | 28.21%  |
| WDC                 | 9         | 9      | 23.08%  |
| Hitachi             | 7         | 9      | 17.95%  |
| Samsung Electronics | 5         | 5      | 12.82%  |
| Toshiba             | 3         | 3      | 7.69%   |
| Maxtor              | 3         | 4      | 7.69%   |
| Fujitsu             | 1         | 1      | 2.56%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 35        | 42     | 83.33%  |
| SSD  | 7         | 10     | 16.67%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-24ZEST0 320GB      | 1         | 1      | 25%     |
| Seagate ST9250315AS 250GB         | 1         | 1      | 25%     |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 25%     |
| Samsung Electronics HD322GJ 320GB | 1         | 2      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 50%     |
| WDC                 | 1         | 1      | 25%     |
| Seagate             | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 102       | 154    | 45.33%  |
| Detected | 77        | 112    | 34.22%  |
| Malfunc  | 42        | 52     | 18.67%  |
| Failed   | 4         | 5      | 1.78%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 126       | 49.22%  |
| AMD                            | 53        | 20.7%   |
| Samsung Electronics            | 26        | 10.16%  |
| Nvidia                         | 10        | 3.91%   |
| SK hynix                       | 6         | 2.34%   |
| SanDisk                        | 6         | 2.34%   |
| JMicron Technology             | 5         | 1.95%   |
| Toshiba America Info Systems   | 3         | 1.17%   |
| Micron Technology              | 3         | 1.17%   |
| ASMedia Technology             | 3         | 1.17%   |
| Phison Electronics             | 2         | 0.78%   |
| ADATA Technology               | 2         | 0.78%   |
| Union Memory (Shenzhen)        | 1         | 0.39%   |
| Solid State Storage Technology | 1         | 0.39%   |
| Silicon Motion                 | 1         | 0.39%   |
| O2 Micro                       | 1         | 0.39%   |
| Netac Technology               | 1         | 0.39%   |
| Marvell Technology Group       | 1         | 0.39%   |
| Lite-On Technology             | 1         | 0.39%   |
| Lenovo                         | 1         | 0.39%   |
| KIOXIA                         | 1         | 0.39%   |
| Kingston Technology Company    | 1         | 0.39%   |
| Hewlett-Packard                | 1         | 0.39%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 26        | 8.44%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 14        | 4.55%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 12        | 3.9%    |
| Samsung NVMe SSD Controller 980                                                         | 11        | 3.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 11        | 3.57%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 9         | 2.92%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8         | 2.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 8         | 2.6%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 7         | 2.27%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 6         | 1.95%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 6         | 1.95%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 6         | 1.95%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 1.95%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 6         | 1.95%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 1.62%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 1.62%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 1.62%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 5         | 1.62%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 4         | 1.3%    |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 4         | 1.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.3%    |
| Intel Comet Lake SATA AHCI Controller                                                   | 4         | 1.3%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 4         | 1.3%    |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 1.3%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 1.3%    |
| Nvidia MCP61 SATA Controller                                                            | 3         | 0.97%   |
| Nvidia MCP61 IDE                                                                        | 3         | 0.97%   |
| Micron Non-Volatile memory controller                                                   | 3         | 0.97%   |
| JMicron JMB368 IDE controller                                                           | 3         | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 3         | 0.97%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 3         | 0.97%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 3         | 0.97%   |
| AMD FCH IDE Controller                                                                  | 3         | 0.97%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3         | 0.97%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.65%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 2         | 0.65%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 2         | 0.65%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 2         | 0.65%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2         | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 152       | 56.72%  |
| NVMe | 55        | 20.52%  |
| IDE  | 51        | 19.03%  |
| RAID | 10        | 3.73%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 138       | 67.32%  |
| AMD    | 67        | 32.68%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.44%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 4         | 1.95%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.46%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.46%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 3         | 1.46%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 1.46%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.46%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 3         | 1.46%   |
| AMD E-450 APU with Radeon HD Graphics         | 3         | 1.46%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 2         | 0.98%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 0.98%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 0.98%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 0.98%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 0.98%   |
| Intel Core i5-4670K CPU @ 3.40GHz             | 2         | 0.98%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 0.98%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 0.98%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 0.98%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 0.98%   |
| Intel Core i3-5010U CPU @ 2.10GHz             | 2         | 0.98%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 0.98%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 2         | 0.98%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 0.98%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 2         | 0.98%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 0.98%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 0.98%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 0.98%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 2         | 0.98%   |
| AMD Phenom II X6 1055T Processor              | 2         | 0.98%   |
| AMD E-300 APU with Radeon HD Graphics         | 2         | 0.98%   |
| AMD Athlon II X2 280 Processor                | 2         | 0.98%   |
| Intel Xeon CPU E5405 @ 2.00GHz                | 1         | 0.49%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.49%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.49%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz      | 1         | 0.49%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.49%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 1         | 0.49%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 1         | 0.49%   |
| Intel Pentium D CPU 2.80GHz                   | 1         | 0.49%   |
| Intel Pentium D CPU 2.66GHz                   | 1         | 0.49%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 42        | 20.49%  |
| Intel Core i7                  | 22        | 10.73%  |
| Intel Core i3                  | 20        | 9.76%   |
| Intel Celeron                  | 16        | 7.8%    |
| Intel Pentium                  | 13        | 6.34%   |
| AMD Ryzen 5                    | 11        | 5.37%   |
| AMD Ryzen 7                    | 8         | 3.9%    |
| Other                          | 7         | 3.41%   |
| AMD Athlon II X2               | 7         | 3.41%   |
| Intel Core 2 Duo               | 5         | 2.44%   |
| AMD E                          | 5         | 2.44%   |
| AMD Athlon 64 X2               | 5         | 2.44%   |
| AMD A4                         | 4         | 1.95%   |
| Intel Pentium Silver           | 3         | 1.46%   |
| AMD Ryzen 3                    | 3         | 1.46%   |
| AMD FX                         | 3         | 1.46%   |
| AMD E1                         | 3         | 1.46%   |
| AMD A10                        | 3         | 1.46%   |
| Intel Pentium Dual-Core        | 2         | 0.98%   |
| Intel Pentium D                | 2         | 0.98%   |
| Intel Core i9                  | 2         | 0.98%   |
| AMD Sempron                    | 2         | 0.98%   |
| AMD Phenom II X6               | 2         | 0.98%   |
| AMD Athlon II X4               | 2         | 0.98%   |
| AMD Athlon                     | 2         | 0.98%   |
| Intel Xeon                     | 1         | 0.49%   |
| Intel Pentium Dual             | 1         | 0.49%   |
| Intel Pentium 4                | 1         | 0.49%   |
| Intel Core 2 Quad              | 1         | 0.49%   |
| Intel Atom                     | 1         | 0.49%   |
| AMD V140                       | 1         | 0.49%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.49%   |
| AMD Ryzen 5 PRO                | 1         | 0.49%   |
| AMD Phenom II X4               | 1         | 0.49%   |
| AMD A8                         | 1         | 0.49%   |
| AMD A6                         | 1         | 0.49%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 96        | 46.6%   |
| 4       | 73        | 35.44%  |
| 6       | 14        | 6.8%    |
| 8       | 11        | 5.34%   |
| 1       | 5         | 2.43%   |
| Unknown | 4         | 1.94%   |
| 10      | 2         | 0.97%   |
| 12      | 1         | 0.49%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 204       | 99.51%  |
| 2      | 1         | 0.49%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 109       | 52.91%  |
| 1       | 93        | 45.15%  |
| Unknown | 4         | 1.94%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 202       | 98.54%  |
| Unknown        | 3         | 1.46%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 32        | 15.53%  |
| 0x206a7    | 13        | 6.31%   |
| 0x806ea    | 11        | 5.34%   |
| 0x306c3    | 9         | 4.37%   |
| 0x05000119 | 8         | 3.88%   |
| 0x306a9    | 7         | 3.4%    |
| 0x010000c8 | 7         | 3.4%    |
| 0x906e9    | 6         | 2.91%   |
| 0x806ec    | 6         | 2.91%   |
| 0x08600106 | 5         | 2.43%   |
| 0x906ea    | 4         | 1.94%   |
| 0x706a1    | 4         | 1.94%   |
| 0x506e3    | 4         | 1.94%   |
| 0x406e3    | 4         | 1.94%   |
| 0x40651    | 4         | 1.94%   |
| 0x306d4    | 4         | 1.94%   |
| 0x1067a    | 4         | 1.94%   |
| 0x806e9    | 3         | 1.46%   |
| 0x6fd      | 3         | 1.46%   |
| 0x506c9    | 3         | 1.46%   |
| 0x0a50000c | 3         | 1.46%   |
| 0x08108109 | 3         | 1.46%   |
| 0x03000027 | 3         | 1.46%   |
| 0xf47      | 2         | 0.97%   |
| 0xa0655    | 2         | 0.97%   |
| 0xa0652    | 2         | 0.97%   |
| 0x90672    | 2         | 0.97%   |
| 0x806c1    | 2         | 0.97%   |
| 0x706e5    | 2         | 0.97%   |
| 0x706a8    | 2         | 0.97%   |
| 0x406c4    | 2         | 0.97%   |
| 0x406c3    | 2         | 0.97%   |
| 0x30678    | 2         | 0.97%   |
| 0x10676    | 2         | 0.97%   |
| 0x08701021 | 2         | 0.97%   |
| 0x08608103 | 2         | 0.97%   |
| 0x08108102 | 2         | 0.97%   |
| 0x06001119 | 2         | 0.97%   |
| 0x06000852 | 2         | 0.97%   |
| 0x02000057 | 2         | 0.97%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 35        | 17.07%  |
| SandyBridge      | 16        | 7.8%    |
| Haswell          | 16        | 7.8%    |
| K10              | 14        | 6.83%   |
| Zen 2            | 10        | 4.88%   |
| Skylake          | 10        | 4.88%   |
| Bobcat           | 8         | 3.9%    |
| IvyBridge        | 7         | 3.41%   |
| Goldmont plus    | 7         | 3.41%   |
| Zen+             | 6         | 2.93%   |
| Silvermont       | 6         | 2.93%   |
| Penryn           | 6         | 2.93%   |
| Piledriver       | 5         | 2.44%   |
| K8 Hammer        | 5         | 2.44%   |
| Core             | 5         | 2.44%   |
| NetBurst         | 4         | 1.95%   |
| K10 Llano        | 4         | 1.95%   |
| Icelake          | 4         | 1.95%   |
| CometLake        | 4         | 1.95%   |
| Broadwell        | 4         | 1.95%   |
| Unknown          | 4         | 1.95%   |
| Zen 3            | 3         | 1.46%   |
| Zen              | 3         | 1.46%   |
| TigerLake        | 3         | 1.46%   |
| K8 & K10 hybrid  | 3         | 1.46%   |
| Goldmont         | 3         | 1.46%   |
| Westmere         | 2         | 0.98%   |
| Alderlake Hybrid | 2         | 0.98%   |
| Tremont          | 1         | 0.49%   |
| Steamroller      | 1         | 0.49%   |
| Puma             | 1         | 0.49%   |
| Nehalem          | 1         | 0.49%   |
| Bulldozer        | 1         | 0.49%   |
| Bonnell          | 1         | 0.49%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 111       | 46.25%  |
| Nvidia | 65        | 27.08%  |
| AMD    | 64        | 26.67%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 15        | 6.07%   |
| Intel UHD Graphics 620                                                                   | 11        | 4.45%   |
| AMD Renoir                                                                               | 7         | 2.83%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.43%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 6         | 2.43%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.02%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.02%   |
| Nvidia GP108M [GeForce MX150]                                                            | 4         | 1.62%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 4         | 1.62%   |
| Intel HD Graphics 630                                                                    | 4         | 1.62%   |
| Intel HD Graphics 620                                                                    | 4         | 1.62%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.62%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 4         | 1.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.62%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.62%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.21%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1.21%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 3         | 1.21%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 3         | 1.21%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.21%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.21%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 1.21%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.21%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 1.21%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 3         | 1.21%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3         | 1.21%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 1.21%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 1.21%   |
| Nvidia TU117M                                                                            | 2         | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.81%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.81%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.81%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.81%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2         | 0.81%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 2         | 0.81%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.81%   |
| Intel JasperLake [UHD Graphics]                                                          | 2         | 0.81%   |
| Intel HD Graphics 530                                                                    | 2         | 0.81%   |
| Intel HD Graphics 500                                                                    | 2         | 0.81%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 81        | 39.13%  |
| 1 x AMD        | 51        | 24.64%  |
| 1 x Nvidia     | 36        | 17.39%  |
| Intel + Nvidia | 25        | 12.08%  |
| 2 x AMD        | 6         | 2.9%    |
| AMD + Nvidia   | 4         | 1.93%   |
| Intel + AMD    | 3         | 1.45%   |
| Other          | 1         | 0.48%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 171       | 80.66%  |
| Proprietary | 29        | 13.68%  |
| Unknown     | 12        | 5.66%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 96        | 44.86%  |
| 0.01-0.5   | 45        | 21.03%  |
| 1.01-2.0   | 39        | 18.22%  |
| 3.01-4.0   | 16        | 7.48%   |
| 0.51-1.0   | 12        | 5.61%   |
| 7.01-8.0   | 3         | 1.4%    |
| 5.01-6.0   | 2         | 0.93%   |
| 2.01-3.0   | 1         | 0.47%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 34        | 15.53%  |
| AU Optronics            | 33        | 15.07%  |
| LG Display              | 21        | 9.59%   |
| Chimei Innolux          | 21        | 9.59%   |
| Goldstar                | 17        | 7.76%   |
| Philips                 | 16        | 7.31%   |
| BOE                     | 14        | 6.39%   |
| Dell                    | 10        | 4.57%   |
| Acer                    | 8         | 3.65%   |
| AOC                     | 6         | 2.74%   |
| Chi Mei Optoelectronics | 5         | 2.28%   |
| InfoVision              | 4         | 1.83%   |
| Hewlett-Packard         | 4         | 1.83%   |
| Sharp                   | 3         | 1.37%   |
| Lenovo                  | 3         | 1.37%   |
| BenQ                    | 3         | 1.37%   |
| CSO                     | 2         | 0.91%   |
| Apple                   | 2         | 0.91%   |
| ViewSonic               | 1         | 0.46%   |
| Valve                   | 1         | 0.46%   |
| Toshiba                 | 1         | 0.46%   |
| Plain Tree Systems      | 1         | 0.46%   |
| PANDA                   | 1         | 0.46%   |
| Medion                  | 1         | 0.46%   |
| LG Electronics          | 1         | 0.46%   |
| KTC                     | 1         | 0.46%   |
| ITE                     | 1         | 0.46%   |
| Hitachi                 | 1         | 0.46%   |
| HannStar                | 1         | 0.46%   |
| ASUSTek Computer        | 1         | 0.46%   |
| Ancor Communications    | 1         | 0.46%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 4         | 1.79%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 4         | 1.79%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch         | 3         | 1.35%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                | 3         | 1.35%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch        | 3         | 1.35%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 3         | 1.35%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch        | 3         | 1.35%   |
| Samsung Electronics SyncMaster SAM0108 1280x1024 312x234mm 15.4-inch | 2         | 0.9%    |
| Philips 223E PHLC049 1920x1080 476x268mm 21.5-inch                   | 2         | 0.9%    |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch         | 2         | 0.9%    |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch           | 2         | 0.9%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch     | 2         | 0.9%    |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch      | 2         | 0.9%    |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                | 2         | 0.9%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                 | 2         | 0.9%    |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                      | 2         | 0.9%    |
| ViewSonic VA521-1 VSCF318 1024x768 304x228mm 15.0-inch               | 1         | 0.45%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                  | 1         | 0.45%   |
| Toshiba TV TSB0108 1440x900 700x390mm 31.5-inch                      | 1         | 0.45%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch              | 1         | 0.45%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch              | 1         | 0.45%   |
| Sharp LCD Monitor SHP13CF 1280x800 331x207mm 15.4-inch               | 1         | 0.45%   |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch    | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM03D1 1680x1050 433x271mm 20.1-inch | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch  | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch  | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch  | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 338x270mm 17.0-inch | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM0214 1680x1050 408x306mm 20.1-inch | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM0213 1680x1050 408x306mm 20.1-inch | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM011E 1280x1024 338x270mm 17.0-inch | 1         | 0.45%   |
| Samsung Electronics SyncMaster SAM0088 1024x768 304x228mm 15.0-inch  | 1         | 0.45%   |
| Samsung Electronics SMB2440 SAM06AF 1920x1080 531x299mm 24.0-inch    | 1         | 0.45%   |
| Samsung Electronics SMB2030 SAM063D 1600x900 443x249mm 20.0-inch     | 1         | 0.45%   |
| Samsung Electronics S27F358 SAM0D73 1920x1080 598x336mm 27.0-inch    | 1         | 0.45%   |
| Samsung Electronics S22E391 SAM0C0D 1920x1080 477x268mm 21.5-inch    | 1         | 0.45%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch    | 1         | 0.45%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 87        | 41.43%  |
| 1366x768 (WXGA)    | 51        | 24.29%  |
| 1600x900 (HD+)     | 13        | 6.19%   |
| 1280x1024 (SXGA)   | 13        | 6.19%   |
| 2560x1440 (QHD)    | 10        | 4.76%   |
| 3840x2160 (4K)     | 6         | 2.86%   |
| 1680x1050 (WSXGA+) | 6         | 2.86%   |
| 1440x900 (WXGA+)   | 5         | 2.38%   |
| 1280x800 (WXGA)    | 4         | 1.9%    |
| 2560x1600          | 2         | 0.95%   |
| 2560x1080          | 2         | 0.95%   |
| 1600x1200          | 2         | 0.95%   |
| 1024x768 (XGA)     | 2         | 0.95%   |
| 800x1280           | 1         | 0.48%   |
| 3456x2160          | 1         | 0.48%   |
| 3200x1080          | 1         | 0.48%   |
| 2160x1440          | 1         | 0.48%   |
| 1920x540           | 1         | 0.48%   |
| 1360x768           | 1         | 0.48%   |
| Unknown            | 1         | 0.48%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 92        | 41.63%  |
| 24      | 14        | 6.33%   |
| 23      | 14        | 6.33%   |
| 27      | 13        | 5.88%   |
| 21      | 13        | 5.88%   |
| 17      | 12        | 5.43%   |
| 19      | 11        | 4.98%   |
| 14      | 10        | 4.52%   |
| 20      | 9         | 4.07%   |
| 18      | 7         | 3.17%   |
| 13      | 7         | 3.17%   |
| 11      | 4         | 1.81%   |
| 84      | 2         | 0.9%    |
| 72      | 2         | 0.9%    |
| 34      | 2         | 0.9%    |
| 16      | 2         | 0.9%    |
| 12      | 2         | 0.9%    |
| 32      | 1         | 0.45%   |
| 31      | 1         | 0.45%   |
| 22      | 1         | 0.45%   |
| 7       | 1         | 0.45%   |
| Unknown | 1         | 0.45%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 112       | 51.38%  |
| 501-600     | 37        | 16.97%  |
| 401-500     | 35        | 16.06%  |
| 351-400     | 13        | 5.96%   |
| 201-300     | 10        | 4.59%   |
| 1501-2000   | 4         | 1.83%   |
| 701-800     | 3         | 1.38%   |
| 601-700     | 2         | 0.92%   |
| 1-100       | 1         | 0.46%   |
| Unknown     | 1         | 0.46%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 157       | 79.7%   |
| 16/10   | 15        | 7.61%   |
| 5/4     | 11        | 5.58%   |
| 4/3     | 8         | 4.06%   |
| 3/2     | 2         | 1.02%   |
| 21/9    | 2         | 1.02%   |
| 0.67    | 1         | 0.51%   |
| Unknown | 1         | 0.51%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 88        | 40%     |
| 201-250        | 38        | 17.27%  |
| 151-200        | 24        | 10.91%  |
| 81-90          | 15        | 6.82%   |
| 301-350        | 13        | 5.91%   |
| 141-150        | 12        | 5.45%   |
| 111-120        | 6         | 2.73%   |
| More than 1000 | 4         | 1.82%   |
| 51-60          | 4         | 1.82%   |
| 351-500        | 4         | 1.82%   |
| 121-130        | 4         | 1.82%   |
| 71-80          | 2         | 0.91%   |
| 61-70          | 2         | 0.91%   |
| 131-140        | 2         | 0.91%   |
| 1-40           | 1         | 0.45%   |
| Unknown        | 1         | 0.45%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 76        | 35.19%  |
| 121-160       | 64        | 29.63%  |
| 101-120       | 64        | 29.63%  |
| 161-240       | 7         | 3.24%   |
| More than 240 | 2         | 0.93%   |
| 1-50          | 2         | 0.93%   |
| Unknown       | 1         | 0.46%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 176       | 85.02%  |
| 2     | 27        | 13.04%  |
| 0     | 4         | 1.93%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 132       | 44.44%  |
| Intel                             | 65        | 21.89%  |
| Qualcomm Atheros                  | 47        | 15.82%  |
| Broadcom                          | 14        | 4.71%   |
| Nvidia                            | 9         | 3.03%   |
| Xiaomi                            | 4         | 1.35%   |
| Ralink                            | 4         | 1.35%   |
| Broadcom Limited                  | 4         | 1.35%   |
| MediaTek                          | 3         | 1.01%   |
| TP-Link                           | 2         | 0.67%   |
| Marvell Technology Group          | 2         | 0.67%   |
| Sierra Wireless                   | 1         | 0.34%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.34%   |
| Mercucys                          | 1         | 0.34%   |
| JMicron Technology                | 1         | 0.34%   |
| ICS Advent                        | 1         | 0.34%   |
| Huawei Technologies               | 1         | 0.34%   |
| Hewlett-Packard                   | 1         | 0.34%   |
| Ericsson Business Mobile Networks | 1         | 0.34%   |
| D-Link System                     | 1         | 0.34%   |
| D-Link                            | 1         | 0.34%   |
| ASIX Electronics                  | 1         | 0.34%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 94        | 27.49%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 21        | 6.14%   |
| Intel Wireless 8265 / 8275                                              | 10        | 2.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 2.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 2.63%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 2.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 1.75%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 1.75%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 1.46%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 1.17%   |
| Nvidia MCP77 Ethernet                                                   | 4         | 1.17%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.17%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.88%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.88%   |
| Realtek RTL8125 2.5GbE Controller                                       | 3         | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.88%   |
| Nvidia MCP61 Ethernet                                                   | 3         | 0.88%   |
| Intel Wireless 7260                                                     | 3         | 0.88%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 0.88%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 0.88%   |
| Intel Ethernet Connection (2) I219-V                                    | 3         | 0.88%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 0.88%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 0.88%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.58%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 0.58%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 0.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 2         | 0.58%   |
| Intel Wireless 8260                                                     | 2         | 0.58%   |
| Intel Wireless 7265                                                     | 2         | 0.58%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 0.58%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.58%   |
| Intel I211 Gigabit Network Connection                                   | 2         | 0.58%   |
| Intel Ethernet Controller I225-V                                        | 2         | 0.58%   |
| Intel Ethernet Connection I217-V                                        | 2         | 0.58%   |
| Intel Ethernet Connection (3) I218-V                                    | 2         | 0.58%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 53        | 35.57%  |
| Qualcomm Atheros      | 41        | 27.52%  |
| Realtek Semiconductor | 34        | 22.82%  |
| Broadcom              | 10        | 6.71%   |
| Ralink                | 4         | 2.68%   |
| TP-Link               | 2         | 1.34%   |
| Sierra Wireless       | 1         | 0.67%   |
| Mercucys              | 1         | 0.67%   |
| D-Link System         | 1         | 0.67%   |
| D-Link                | 1         | 0.67%   |
| Broadcom Limited      | 1         | 0.67%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 10        | 6.71%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 9         | 6.04%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 6.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 6.04%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 5.37%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 6         | 4.03%   |
| Intel Wi-Fi 6 AX200                                                     | 6         | 4.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 5         | 3.36%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 2.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 3         | 2.01%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 2.01%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 2.01%   |
| Intel Wireless 7260                                                     | 3         | 2.01%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 2.01%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 3         | 2.01%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.01%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 2.01%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 2         | 1.34%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 2         | 1.34%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.34%   |
| Intel Wireless 8260                                                     | 2         | 1.34%   |
| Intel Wireless 7265                                                     | 2         | 1.34%   |
| Intel Wi-Fi 6 AX201 160MHz                                              | 2         | 1.34%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.34%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.34%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.34%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.34%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.34%   |
| Sierra Wireless EM7455                                                  | 1         | 0.67%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.67%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.67%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.67%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.67%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.67%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.67%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.67%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]        | 1         | 0.67%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 120       | 63.49%  |
| Intel                    | 30        | 15.87%  |
| Nvidia                   | 9         | 4.76%   |
| Qualcomm Atheros         | 8         | 4.23%   |
| Broadcom                 | 5         | 2.65%   |
| Xiaomi                   | 4         | 2.12%   |
| MediaTek                 | 3         | 1.59%   |
| Broadcom Limited         | 3         | 1.59%   |
| Marvell Technology Group | 2         | 1.06%   |
| JMicron Technology       | 1         | 0.53%   |
| ICS Advent               | 1         | 0.53%   |
| Huawei Technologies      | 1         | 0.53%   |
| Hewlett-Packard          | 1         | 0.53%   |
| ASIX Electronics         | 1         | 0.53%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 94        | 49.21%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 21        | 10.99%  |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 2.09%   |
| Nvidia MCP77 Ethernet                                                          | 4         | 2.09%   |
| Realtek RTL8125 2.5GbE Controller                                              | 3         | 1.57%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 1.57%   |
| Nvidia MCP61 Ethernet                                                          | 3         | 1.57%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 1.57%   |
| Intel Ethernet Connection (2) I219-V                                           | 3         | 1.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 2         | 1.05%   |
| Intel I211 Gigabit Network Connection                                          | 2         | 1.05%   |
| Intel Ethernet Controller I225-V                                               | 2         | 1.05%   |
| Intel Ethernet Connection I217-V                                               | 2         | 1.05%   |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 1.05%   |
| Intel Ethernet Connection (11) I219-V                                          | 2         | 1.05%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 2         | 1.05%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                              | 2         | 1.05%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.05%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.52%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.52%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.52%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.52%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.52%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.52%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.52%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.52%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.52%   |
| Nvidia MCP55 Ethernet                                                          | 1         | 0.52%   |
| MediaTek moto e(6) plus                                                        | 1         | 0.52%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.52%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1         | 0.52%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.52%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 1         | 0.52%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.52%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.52%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.52%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.52%   |
| Intel Ethernet Connection (5) I219-V                                           | 1         | 0.52%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.52%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.52%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 183       | 55.29%  |
| WiFi     | 146       | 44.11%  |
| Modem    | 1         | 0.3%    |
| Unknown  | 1         | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 106       | 50.96%  |
| Ethernet | 102       | 49.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 115       | 56.1%   |
| 1     | 90        | 43.9%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 197       | 96.1%   |
| Yes  | 8         | 3.9%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 44        | 39.29%  |
| IMC Networks                    | 15        | 13.39%  |
| Qualcomm Atheros Communications | 13        | 11.61%  |
| Realtek Semiconductor           | 12        | 10.71%  |
| Broadcom                        | 6         | 5.36%   |
| Lite-On Technology              | 5         | 4.46%   |
| Foxconn / Hon Hai               | 4         | 3.57%   |
| Cambridge Silicon Radio         | 4         | 3.57%   |
| Apple                           | 2         | 1.79%   |
| Toshiba                         | 1         | 0.89%   |
| Realtek                         | 1         | 0.89%   |
| Ralink Technology               | 1         | 0.89%   |
| Integrated System Solution      | 1         | 0.89%   |
| Hewlett-Packard                 | 1         | 0.89%   |
| Dell                            | 1         | 0.89%   |
| ASUSTek Computer                | 1         | 0.89%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 18        | 16.07%  |
| Realtek Bluetooth Radio                                                             | 10        | 8.93%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 8.04%   |
| Intel AX201 Bluetooth                                                               | 8         | 7.14%   |
| IMC Networks Bluetooth Radio                                                        | 8         | 7.14%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 5.36%   |
| Intel AX200 Bluetooth                                                               | 6         | 5.36%   |
| IMC Networks Bluetooth Device                                                       | 4         | 3.57%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 4         | 3.57%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 2.68%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 3         | 2.68%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 1.79%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.79%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 1.79%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 2         | 1.79%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 2         | 1.79%   |
| Broadcom BCM20702A0                                                                 | 2         | 1.79%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 0.89%   |
| Realtek 802.11ac WLAN Adapter                                                       | 1         | 0.89%   |
| Ralink CSR BS8510                                                                   | 1         | 0.89%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.89%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.89%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.89%   |
| Lite-On Bluetooth Device                                                            | 1         | 0.89%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 0.89%   |
| Integrated System Solution Bluetooth Device                                         | 1         | 0.89%   |
| IMC Networks Bluetooth Module                                                       | 1         | 0.89%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 0.89%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.89%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 0.89%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 0.89%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 0.89%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.89%   |
| Broadcom BCM92045B3 ROM                                                             | 1         | 0.89%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 0.89%   |
| ASUS BCM20702A0                                                                     | 1         | 0.89%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 1         | 0.89%   |
| Apple Bluetooth Host Controller                                                     | 1         | 0.89%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 135       | 51.33%  |
| AMD                       | 68        | 25.86%  |
| Nvidia                    | 44        | 16.73%  |
| Plantronics               | 3         | 1.14%   |
| Logitech                  | 2         | 0.76%   |
| Creative Labs             | 2         | 0.76%   |
| C-Media Electronics       | 2         | 0.76%   |
| Texas Instruments         | 1         | 0.38%   |
| SteelSeries ApS           | 1         | 0.38%   |
| Shenzhen Rapoo Technology | 1         | 0.38%   |
| Kingston Technology       | 1         | 0.38%   |
| GN Netcom                 | 1         | 0.38%   |
| Giga-Byte Technology      | 1         | 0.38%   |
| DSEA A/S                  | 1         | 0.38%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                                      | 21        | 6.56%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 20        | 6.25%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 19        | 5.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 13        | 4.06%   |
| AMD FCH Azalia Controller                                                                         | 12        | 3.75%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 11        | 3.44%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 10        | 3.13%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 9         | 2.81%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 9         | 2.81%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 2.5%    |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 7         | 2.19%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 6         | 1.88%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 1.88%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 1.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 6         | 1.88%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 5         | 1.56%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 1.56%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.56%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 1.56%   |
| Intel 200 Series PCH HD Audio                                                                     | 5         | 1.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.56%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.25%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 4         | 1.25%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.25%   |
| Intel Comet Lake PCH cAVS                                                                         | 4         | 1.25%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.25%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.25%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 0.94%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 0.94%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 0.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 0.94%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 0.94%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 0.94%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 0.94%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 0.94%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 0.94%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 0.94%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 0.94%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 0.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 0.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Unknown               | 36        | 22.09%  |
| Samsung Electronics   | 34        | 20.86%  |
| Kingston              | 21        | 12.88%  |
| SK hynix              | 19        | 11.66%  |
| Micron Technology     | 9         | 5.52%   |
| GOODRAM               | 6         | 3.68%   |
| Unknown (ABCD)        | 3         | 1.84%   |
| Transcend             | 3         | 1.84%   |
| Elpida                | 3         | 1.84%   |
| Crucial               | 3         | 1.84%   |
| Corsair               | 3         | 1.84%   |
| Ramaxel Technology    | 2         | 1.23%   |
| Patriot               | 2         | 1.23%   |
| Nanya Technology      | 2         | 1.23%   |
| G.Skill               | 2         | 1.23%   |
| Apacer                | 2         | 1.23%   |
| A-DATA Technology     | 2         | 1.23%   |
| Unifosa               | 1         | 0.61%   |
| Team                  | 1         | 0.61%   |
| Silicon Power         | 1         | 0.61%   |
| SGS/Thomson           | 1         | 0.61%   |
| Kingmax Semiconductor | 1         | 0.61%   |
| Hexon                 | 1         | 0.61%   |
| Goldkey               | 1         | 0.61%   |
| Axiom                 | 1         | 0.61%   |
| AVEXIR                | 1         | 0.61%   |
| ASint Technology      | 1         | 0.61%   |
| Unknown               | 1         | 0.61%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                      | 3         | 1.67%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 3         | 1.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.67%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 1.67%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 2         | 1.11%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 2         | 1.11%   |
| Unknown RAM Module 2048MB SODIMM DRAM 667MT/s                    | 2         | 1.11%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 2         | 1.11%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 2         | 1.11%   |
| Unknown RAM Module 1024MB SODIMM DRAM 667MT/s                    | 2         | 1.11%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s                      | 2         | 1.11%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.11%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.11%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.11%   |
| Samsung RAM M471B2873FHS-CF8 1GB SODIMM DDR3 1067MT/s            | 2         | 1.11%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.11%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.11%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 2         | 1.11%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                          | 1         | 0.56%   |
| Unknown RAM Module 512MB DIMM SDRAM                              | 1         | 0.56%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.56%   |
| Unknown RAM Module 4GB DIMM 667MT/s                              | 1         | 0.56%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.56%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.56%   |
| Unknown RAM Module 4096MB FB-DIMM DDR2 667MT/s                   | 1         | 0.56%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 1         | 0.56%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.56%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.56%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.56%   |
| Unknown RAM Module 2048MB SODIMM DDR2 400MT/s                    | 1         | 0.56%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                     | 1         | 0.56%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.56%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.56%   |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s                       | 1         | 0.56%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                      | 1         | 0.56%   |
| Unknown RAM Module 2048MB DIMM                                   | 1         | 0.56%   |
| Unknown RAM Module 1GB SODIMM LPDDR4 2400MT/s                    | 1         | 0.56%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 0.56%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                      | 1         | 0.56%   |
| Unknown RAM Module 1024MB DIMM DDR2 400MT/s                      | 1         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 51        | 34.69%  |
| DDR4    | 48        | 32.65%  |
| DDR2    | 13        | 8.84%   |
| Unknown | 12        | 8.16%   |
| SDRAM   | 10        | 6.8%    |
| LPDDR4  | 6         | 4.08%   |
| DDR     | 3         | 2.04%   |
| LPDDR3  | 2         | 1.36%   |
| DRAM    | 2         | 1.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 71        | 50%     |
| DIMM         | 63        | 44.37%  |
| Row Of Chips | 7         | 4.93%   |
| FB-DIMM      | 1         | 0.7%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 53        | 32.52%  |
| 2048  | 38        | 23.31%  |
| 8192  | 35        | 21.47%  |
| 16384 | 17        | 10.43%  |
| 1024  | 15        | 9.2%    |
| 32768 | 4         | 2.45%   |
| 512   | 1         | 0.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 37        | 23.72%  |
| 2667    | 23        | 14.74%  |
| 1333    | 18        | 11.54%  |
| 3200    | 10        | 6.41%   |
| 2400    | 7         | 4.49%   |
| 2133    | 7         | 4.49%   |
| 800     | 7         | 4.49%   |
| 667     | 6         | 3.85%   |
| 1334    | 5         | 3.21%   |
| 400     | 4         | 2.56%   |
| Unknown | 4         | 2.56%   |
| 3266    | 3         | 1.92%   |
| 2048    | 3         | 1.92%   |
| 333     | 3         | 1.92%   |
| 4199    | 2         | 1.28%   |
| 3600    | 2         | 1.28%   |
| 3000    | 2         | 1.28%   |
| 2933    | 2         | 1.28%   |
| 1067    | 2         | 1.28%   |
| 6000    | 1         | 0.64%   |
| 4800    | 1         | 0.64%   |
| 3500    | 1         | 0.64%   |
| 2800    | 1         | 0.64%   |
| 2666    | 1         | 0.64%   |
| 1867    | 1         | 0.64%   |
| 1400    | 1         | 0.64%   |
| 975     | 1         | 0.64%   |
| 533     | 1         | 0.64%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 40%     |
| Canon           | 2         | 40%     |
| Seiko Epson     | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seiko Epson USB2.0 Printer (Hi-speed) | 1         | 20%     |
| HP LaserJet M14-M17                   | 1         | 20%     |
| HP LaserJet 1020                      | 1         | 20%     |
| Canon LaserShot LBP-1120 Printer      | 1         | 20%     |
| Canon iP7200 series                   | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Canon CanoScan LiDE 700F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 28        | 20.44%  |
| IMC Networks                           | 23        | 16.79%  |
| Realtek Semiconductor                  | 12        | 8.76%   |
| Microdia                               | 10        | 7.3%    |
| Acer                                   | 8         | 5.84%   |
| Logitech                               | 7         | 5.11%   |
| Quanta                                 | 6         | 4.38%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 3.65%   |
| Sunplus Innovation Technology          | 4         | 2.92%   |
| Z-Star Microelectronics                | 3         | 2.19%   |
| Syntek                                 | 3         | 2.19%   |
| Silicon Motion                         | 3         | 2.19%   |
| Lite-On Technology                     | 3         | 2.19%   |
| Suyin                                  | 2         | 1.46%   |
| Samsung Electronics                    | 2         | 1.46%   |
| Luxvisions Innotech Limited            | 2         | 1.46%   |
| KYE Systems (Mouse Systems)            | 2         | 1.46%   |
| Apple                                  | 2         | 1.46%   |
| Alcor Micro                            | 2         | 1.46%   |
| Trust                                  | 1         | 0.73%   |
| Pixart Imaging                         | 1         | 0.73%   |
| Microsoft                              | 1         | 0.73%   |
| Importek                               | 1         | 0.73%   |
| HD WEBCAM                              | 1         | 0.73%   |
| Genesys Logic                          | 1         | 0.73%   |
| GEMBIRD                                | 1         | 0.73%   |
| ezcap                                  | 1         | 0.73%   |
| Cubeternet                             | 1         | 0.73%   |
| Aveo Technology                        | 1         | 0.73%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                           | 6         | 4.38%   |
| Chicony Integrated Camera                                    | 6         | 4.38%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 5         | 3.65%   |
| IMC Networks Integrated Camera                               | 4         | 2.92%   |
| Realtek Integrated_Webcam_HD                                 | 3         | 2.19%   |
| Quanta HP HD Camera                                          | 3         | 2.19%   |
| Microdia Camera                                              | 3         | 2.19%   |
| Logitech Webcam C270                                         | 3         | 2.19%   |
| Chicony HD WebCam                                            | 3         | 2.19%   |
| Acer Integrated Camera                                       | 3         | 2.19%   |
| Z-Star Venus USB2.0 Camera                                   | 2         | 1.46%   |
| Syntek Lenovo EasyCamera                                     | 2         | 1.46%   |
| Silicon Motion WebCam SC-0311139N                            | 2         | 1.46%   |
| Realtek USB Camera                                           | 2         | 1.46%   |
| Quanta HP TrueVision HD Camera                               | 2         | 1.46%   |
| Microdia Laptop_Integrated_Webcam_HD                         | 2         | 1.46%   |
| Microdia Integrated_Webcam_HD                                | 2         | 1.46%   |
| Lite-On HP HD Webcam                                         | 2         | 1.46%   |
| IMC Networks VGA UVC WebCam                                  | 2         | 1.46%   |
| Chicony USB2.0 VGA UVC WebCam                                | 2         | 1.46%   |
| Chicony Integrated Camera (1280x720@30)                      | 2         | 1.46%   |
| Chicony EasyCamera                                           | 2         | 1.46%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 2         | 1.46%   |
| Z-Star WebCam SCB-0320N                                      | 1         | 0.73%   |
| Trust FHD Webcam                                             | 1         | 0.73%   |
| Syntek Integrated Camera                                     | 1         | 0.73%   |
| Suyin HP Truevision HD                                       | 1         | 0.73%   |
| Suyin HD WebCam                                              | 1         | 0.73%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 0.73%   |
| Sunplus Integrated_Webcam_HD                                 | 1         | 0.73%   |
| Sunplus HD WebCam                                            | 1         | 0.73%   |
| Sunplus Asus Webcam                                          | 1         | 0.73%   |
| Silicon Motion WebCam SC-13HDL11939N                         | 1         | 0.73%   |
| Samsung Galaxy A5 (MTP)                                      | 1         | 0.73%   |
| Samsung Galaxy (PTP mode)                                    | 1         | 0.73%   |
| Realtek USB2.0 VGA UVC WebCam                                | 1         | 0.73%   |
| Realtek Integrated Webcam_HD                                 | 1         | 0.73%   |
| Realtek Integrated Webcam HD                                 | 1         | 0.73%   |
| Realtek HP Truevision HD                                     | 1         | 0.73%   |
| Realtek HP "Truevision HD" laptop camera                     | 1         | 0.73%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 32.14%  |
| Synaptics                  | 8         | 28.57%  |
| Elan Microelectronics      | 4         | 14.29%  |
| Shenzhen Goodix Technology | 3         | 10.71%  |
| Upek                       | 2         | 7.14%   |
| LighTuning Technology      | 1         | 3.57%   |
| AuthenTec                  | 1         | 3.57%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 4         | 14.29%  |
| Shenzhen Goodix  FingerPrint Device                        | 3         | 10.71%  |
| Elan ELAN:Fingerprint                                      | 3         | 10.71%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 7.14%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 2         | 7.14%   |
| Validity Sensors Fingerprint scanner                       | 2         | 7.14%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 2         | 7.14%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 7.14%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 3.57%   |
| Validity Sensors Synaptics WBDI                            | 1         | 3.57%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 3.57%   |
| Synaptics  WBDI                                            | 1         | 3.57%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 3.57%   |
| Elan ELAN:ARM-M4                                           | 1         | 3.57%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 3.57%   |
| Unknown                                                    | 1         | 3.57%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 1         | 50%     |
| O2 Micro              | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 1         | 50%     |
| O2 Micro OZ776 CCID Smartcard Reader              | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 157       | 74.06%  |
| 1     | 45        | 21.23%  |
| 2     | 9         | 4.25%   |
| 3     | 1         | 0.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 28        | 45.16%  |
| Graphics card         | 21        | 33.87%  |
| Net/wireless          | 5         | 8.06%   |
| Multimedia controller | 2         | 3.23%   |
| Chipcard              | 2         | 3.23%   |
| Camera                | 2         | 3.23%   |
| Storage               | 1         | 1.61%   |
| Sound                 | 1         | 1.61%   |

